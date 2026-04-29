# \PartSpecificationsAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**PartSpecificationsApiGetPartSpecification**](PartSpecificationsAPIAPI.md#PartSpecificationsApiGetPartSpecification) | **Get** /quality/v1/part-specifications/{id} | Get Part Specification
[**PartSpecificationsApiListPartSpecifications**](PartSpecificationsAPIAPI.md#PartSpecificationsApiListPartSpecifications) | **Get** /quality/v1/part-specifications | List Part Specifications



## PartSpecificationsApiGetPartSpecification

> PartSpecificationsApiGetPartSpecificationResponse PartSpecificationsApiGetPartSpecification(ctx, id).Execute()

Get Part Specification



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
	id := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the part specification.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartSpecificationsAPIAPI.PartSpecificationsApiGetPartSpecification(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartSpecificationsAPIAPI.PartSpecificationsApiGetPartSpecification``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PartSpecificationsApiGetPartSpecification`: PartSpecificationsApiGetPartSpecificationResponse
	fmt.Fprintf(os.Stdout, "Response from `PartSpecificationsAPIAPI.PartSpecificationsApiGetPartSpecification`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | A unique identifier for the part specification. | 

### Other Parameters

Other parameters are passed through a pointer to a apiPartSpecificationsApiGetPartSpecificationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**PartSpecificationsApiGetPartSpecificationResponse**](PartSpecificationsApiGetPartSpecificationResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PartSpecificationsApiListPartSpecifications

> []PartSpecificationsApiListPartSpecificationsItem PartSpecificationsApiListPartSpecifications(ctx).PartId(partId).Ids(ids).SpecificationNumber(specificationNumber).Execute()

List Part Specifications



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
	partId := "00000000-0000-0000-0000-000000000000" // string | The Specification Part ID. (optional)
	ids := []string{"00000000-0000-0000-0000-000000000000"} // []string | The ID of the Part Specification. (optional)
	specificationNumber := "string" // string | The Specification number of the Part Specification. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartSpecificationsAPIAPI.PartSpecificationsApiListPartSpecifications(context.Background()).PartId(partId).Ids(ids).SpecificationNumber(specificationNumber).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartSpecificationsAPIAPI.PartSpecificationsApiListPartSpecifications``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PartSpecificationsApiListPartSpecifications`: []PartSpecificationsApiListPartSpecificationsItem
	fmt.Fprintf(os.Stdout, "Response from `PartSpecificationsAPIAPI.PartSpecificationsApiListPartSpecifications`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPartSpecificationsApiListPartSpecificationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **partId** | **string** | The Specification Part ID. | 
 **ids** | **[]string** | The ID of the Part Specification. | 
 **specificationNumber** | **string** | The Specification number of the Part Specification. | 

### Return type

[**[]PartSpecificationsApiListPartSpecificationsItem**](PartSpecificationsApiListPartSpecificationsItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

