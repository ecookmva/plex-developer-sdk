# \SamplePlansAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SamplePlansApiListSamplePlans**](SamplePlansAPIAPI.md#SamplePlansApiListSamplePlans) | **Get** /quality/v1/sample-plans | List Sample Plans



## SamplePlansApiListSamplePlans

> []SamplePlansApiListSamplePlansItem SamplePlansApiListSamplePlans(ctx).SamplePlan(samplePlan).Execute()

List Sample Plans



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	samplePlan := []string{"string"} // []string | A list of Sample Plans. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SamplePlansAPIAPI.SamplePlansApiListSamplePlans(context.Background()).SamplePlan(samplePlan).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SamplePlansAPIAPI.SamplePlansApiListSamplePlans``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SamplePlansApiListSamplePlans`: []SamplePlansApiListSamplePlansItem
	fmt.Fprintf(os.Stdout, "Response from `SamplePlansAPIAPI.SamplePlansApiListSamplePlans`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSamplePlansApiListSamplePlansRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **samplePlan** | **[]string** | A list of Sample Plans. | 

### Return type

[**[]SamplePlansApiListSamplePlansItem**](SamplePlansApiListSamplePlansItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

