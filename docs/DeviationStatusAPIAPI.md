# \DeviationStatusAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**DeviationStatusApiListDeviationStatus**](DeviationStatusAPIAPI.md#DeviationStatusApiListDeviationStatus) | **Get** /quality/v1/deviation-status | List Deviation Status



## DeviationStatusApiListDeviationStatus

> []DeviationStatusApiListDeviationStatusItem DeviationStatusApiListDeviationStatus(ctx).DeviationStatus(deviationStatus).Active(active).DefaultStatus(defaultStatus).Approved(approved).AwaitingApproval(awaitingApproval).Rejected(rejected).Expired(expired).Execute()

List Deviation Status



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
	deviationStatus := []string{"string"} // []string | The name of the Deviation Status. (optional)
	active := false // bool | The designation to signify the deviations are active. (optional)
	defaultStatus := false // bool | The designation to signify the default status for deviations. (optional)
	approved := false // bool | The designation to signify the deviations are approved. (optional)
	awaitingApproval := false // bool | The designation to signify the deviations are awaiting approval. (optional)
	rejected := false // bool | The designation to signify the deviations are rejected. (optional)
	expired := false // bool | The designation to signify the deviations are expired. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeviationStatusAPIAPI.DeviationStatusApiListDeviationStatus(context.Background()).DeviationStatus(deviationStatus).Active(active).DefaultStatus(defaultStatus).Approved(approved).AwaitingApproval(awaitingApproval).Rejected(rejected).Expired(expired).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeviationStatusAPIAPI.DeviationStatusApiListDeviationStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeviationStatusApiListDeviationStatus`: []DeviationStatusApiListDeviationStatusItem
	fmt.Fprintf(os.Stdout, "Response from `DeviationStatusAPIAPI.DeviationStatusApiListDeviationStatus`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiDeviationStatusApiListDeviationStatusRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **deviationStatus** | **[]string** | The name of the Deviation Status. | 
 **active** | **bool** | The designation to signify the deviations are active. | 
 **defaultStatus** | **bool** | The designation to signify the default status for deviations. | 
 **approved** | **bool** | The designation to signify the deviations are approved. | 
 **awaitingApproval** | **bool** | The designation to signify the deviations are awaiting approval. | 
 **rejected** | **bool** | The designation to signify the deviations are rejected. | 
 **expired** | **bool** | The designation to signify the deviations are expired. | 

### Return type

[**[]DeviationStatusApiListDeviationStatusItem**](DeviationStatusApiListDeviationStatusItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

