# \ToleranceTypesAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ToleranceTypesApiListToleranceTypes**](ToleranceTypesAPIAPI.md#ToleranceTypesApiListToleranceTypes) | **Get** /quality/v1/tolerance-types | List Tolerance Types



## ToleranceTypesApiListToleranceTypes

> []ToleranceTypesApiListToleranceTypesItem ToleranceTypesApiListToleranceTypes(ctx).ToleranceType(toleranceType).AttributeData(attributeData).ReferenceOnly(referenceOnly).Execute()

List Tolerance Types



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
	toleranceType := []string{"string"} // []string | A list of tolerance types. (optional)
	attributeData := false // bool | The designation of whether the tolerance type is attribute data or not. (optional)
	referenceOnly := false // bool | The designation of whether the tolerance type is attribute data or not. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ToleranceTypesAPIAPI.ToleranceTypesApiListToleranceTypes(context.Background()).ToleranceType(toleranceType).AttributeData(attributeData).ReferenceOnly(referenceOnly).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ToleranceTypesAPIAPI.ToleranceTypesApiListToleranceTypes``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ToleranceTypesApiListToleranceTypes`: []ToleranceTypesApiListToleranceTypesItem
	fmt.Fprintf(os.Stdout, "Response from `ToleranceTypesAPIAPI.ToleranceTypesApiListToleranceTypes`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiToleranceTypesApiListToleranceTypesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **toleranceType** | **[]string** | A list of tolerance types. | 
 **attributeData** | **bool** | The designation of whether the tolerance type is attribute data or not. | 
 **referenceOnly** | **bool** | The designation of whether the tolerance type is attribute data or not. | 

### Return type

[**[]ToleranceTypesApiListToleranceTypesItem**](ToleranceTypesApiListToleranceTypesItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

