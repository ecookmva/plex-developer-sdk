# \DynamicMultiOutTemplatesAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**DynamicMultiOutTemplatesApiGetDynamicMultiOutTemplate**](DynamicMultiOutTemplatesAPIAPI.md#DynamicMultiOutTemplatesApiGetDynamicMultiOutTemplate) | **Get** /engineering/v1/dynamic-multi-out-templates/{id} | Get Dynamic Multi Out Template
[**DynamicMultiOutTemplatesApiGetDynamicMultiOutTemplatePartOperation**](DynamicMultiOutTemplatesAPIAPI.md#DynamicMultiOutTemplatesApiGetDynamicMultiOutTemplatePartOperation) | **Get** /engineering/v1/dynamic-multi-out-templates/{id}/part-operations/{partOperationId} | Get Dynamic Multi Out Template Part Operation
[**DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperations**](DynamicMultiOutTemplatesAPIAPI.md#DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperations) | **Get** /engineering/v1/dynamic-multi-out-templates/{id}/part-operations | List Dynamic Multi Out Template Part Operations
[**DynamicMultiOutTemplatesApiListDynamicMultiOutTemplates**](DynamicMultiOutTemplatesAPIAPI.md#DynamicMultiOutTemplatesApiListDynamicMultiOutTemplates) | **Get** /engineering/v1/dynamic-multi-out-templates | List Dynamic Multi Out Templates



## DynamicMultiOutTemplatesApiGetDynamicMultiOutTemplate

> DynamicMultiOutTemplatesApiGetDynamicMultiOutTemplateResponse DynamicMultiOutTemplatesApiGetDynamicMultiOutTemplate(ctx, id).Execute()

Get Dynamic Multi Out Template



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
	id := "00000000-0000-0000-0000-000000000000" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DynamicMultiOutTemplatesAPIAPI.DynamicMultiOutTemplatesApiGetDynamicMultiOutTemplate(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DynamicMultiOutTemplatesAPIAPI.DynamicMultiOutTemplatesApiGetDynamicMultiOutTemplate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DynamicMultiOutTemplatesApiGetDynamicMultiOutTemplate`: DynamicMultiOutTemplatesApiGetDynamicMultiOutTemplateResponse
	fmt.Fprintf(os.Stdout, "Response from `DynamicMultiOutTemplatesAPIAPI.DynamicMultiOutTemplatesApiGetDynamicMultiOutTemplate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDynamicMultiOutTemplatesApiGetDynamicMultiOutTemplateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**DynamicMultiOutTemplatesApiGetDynamicMultiOutTemplateResponse**](DynamicMultiOutTemplatesApiGetDynamicMultiOutTemplateResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DynamicMultiOutTemplatesApiGetDynamicMultiOutTemplatePartOperation

> DynamicMultiOutTemplatesApiGetDynamicMultiOutTemplatePartOperationResponse DynamicMultiOutTemplatesApiGetDynamicMultiOutTemplatePartOperation(ctx, id, partOperationId).Execute()

Get Dynamic Multi Out Template Part Operation



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
	id := "00000000-0000-0000-0000-000000000000" // string | 
	partOperationId := "00000000-0000-0000-0000-000000000000" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DynamicMultiOutTemplatesAPIAPI.DynamicMultiOutTemplatesApiGetDynamicMultiOutTemplatePartOperation(context.Background(), id, partOperationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DynamicMultiOutTemplatesAPIAPI.DynamicMultiOutTemplatesApiGetDynamicMultiOutTemplatePartOperation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DynamicMultiOutTemplatesApiGetDynamicMultiOutTemplatePartOperation`: DynamicMultiOutTemplatesApiGetDynamicMultiOutTemplatePartOperationResponse
	fmt.Fprintf(os.Stdout, "Response from `DynamicMultiOutTemplatesAPIAPI.DynamicMultiOutTemplatesApiGetDynamicMultiOutTemplatePartOperation`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 
**partOperationId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDynamicMultiOutTemplatesApiGetDynamicMultiOutTemplatePartOperationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**DynamicMultiOutTemplatesApiGetDynamicMultiOutTemplatePartOperationResponse**](DynamicMultiOutTemplatesApiGetDynamicMultiOutTemplatePartOperationResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperations

> []DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperations(ctx, id).Execute()

List Dynamic Multi Out Template Part Operations



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
	id := "00000000-0000-0000-0000-000000000000" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DynamicMultiOutTemplatesAPIAPI.DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperations(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DynamicMultiOutTemplatesAPIAPI.DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperations`: []DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem
	fmt.Fprintf(os.Stdout, "Response from `DynamicMultiOutTemplatesAPIAPI.DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperations`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem**](DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DynamicMultiOutTemplatesApiListDynamicMultiOutTemplates

> []DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatesItem DynamicMultiOutTemplatesApiListDynamicMultiOutTemplates(ctx).Id(id).Code(code).Active(active).Execute()

List Dynamic Multi Out Templates



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
	id := []string{"00000000-0000-0000-0000-000000000000"} // []string | A unique identifier for the Dynamic Multi Out Templates. (optional)
	code := "string" // string | An additional unique field used to identify a Dynamic Multi Out Template. (optional)
	active := false // bool | A flag used to filter on active status. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DynamicMultiOutTemplatesAPIAPI.DynamicMultiOutTemplatesApiListDynamicMultiOutTemplates(context.Background()).Id(id).Code(code).Active(active).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DynamicMultiOutTemplatesAPIAPI.DynamicMultiOutTemplatesApiListDynamicMultiOutTemplates``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DynamicMultiOutTemplatesApiListDynamicMultiOutTemplates`: []DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatesItem
	fmt.Fprintf(os.Stdout, "Response from `DynamicMultiOutTemplatesAPIAPI.DynamicMultiOutTemplatesApiListDynamicMultiOutTemplates`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiDynamicMultiOutTemplatesApiListDynamicMultiOutTemplatesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **[]string** | A unique identifier for the Dynamic Multi Out Templates. | 
 **code** | **string** | An additional unique field used to identify a Dynamic Multi Out Template. | 
 **active** | **bool** | A flag used to filter on active status. | 

### Return type

[**[]DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatesItem**](DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatesItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

