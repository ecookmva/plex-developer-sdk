# \ProcessSpecificationsAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ProcessSpecificationsApiGetProcessSpecification**](ProcessSpecificationsAPIAPI.md#ProcessSpecificationsApiGetProcessSpecification) | **Get** /quality/v1/process-specifications/{id} | Get Process Specification
[**ProcessSpecificationsApiListProcessSpecifications**](ProcessSpecificationsAPIAPI.md#ProcessSpecificationsApiListProcessSpecifications) | **Get** /quality/v1/process-specifications | List Process Specifications



## ProcessSpecificationsApiGetProcessSpecification

> ProcessSpecificationsApiGetProcessSpecificationResponse ProcessSpecificationsApiGetProcessSpecification(ctx, id).Execute()

Get Process Specification



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
	id := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the process specification.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProcessSpecificationsAPIAPI.ProcessSpecificationsApiGetProcessSpecification(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProcessSpecificationsAPIAPI.ProcessSpecificationsApiGetProcessSpecification``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProcessSpecificationsApiGetProcessSpecification`: ProcessSpecificationsApiGetProcessSpecificationResponse
	fmt.Fprintf(os.Stdout, "Response from `ProcessSpecificationsAPIAPI.ProcessSpecificationsApiGetProcessSpecification`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | A unique identifier for the process specification. | 

### Other Parameters

Other parameters are passed through a pointer to a apiProcessSpecificationsApiGetProcessSpecificationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ProcessSpecificationsApiGetProcessSpecificationResponse**](ProcessSpecificationsApiGetProcessSpecificationResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProcessSpecificationsApiListProcessSpecifications

> []ProcessSpecificationsApiListProcessSpecificationsItem ProcessSpecificationsApiListProcessSpecifications(ctx).Ids(ids).ProcessControlRecipeFamilyId(processControlRecipeFamilyId).ProcessControlRecipeId(processControlRecipeId).OperationId(operationId).Execute()

List Process Specifications



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
	ids := []string{"00000000-0000-0000-0000-000000000000"} // []string | A list of IDs representing the specification. (optional)
	processControlRecipeFamilyId := "00000000-0000-0000-0000-000000000000" // string | ID representing the process control recipe family. (optional)
	processControlRecipeId := "00000000-0000-0000-0000-000000000000" // string | ID representing the process control recipe. (optional)
	operationId := "00000000-0000-0000-0000-000000000000" // string | ID representing the operation. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProcessSpecificationsAPIAPI.ProcessSpecificationsApiListProcessSpecifications(context.Background()).Ids(ids).ProcessControlRecipeFamilyId(processControlRecipeFamilyId).ProcessControlRecipeId(processControlRecipeId).OperationId(operationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProcessSpecificationsAPIAPI.ProcessSpecificationsApiListProcessSpecifications``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProcessSpecificationsApiListProcessSpecifications`: []ProcessSpecificationsApiListProcessSpecificationsItem
	fmt.Fprintf(os.Stdout, "Response from `ProcessSpecificationsAPIAPI.ProcessSpecificationsApiListProcessSpecifications`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiProcessSpecificationsApiListProcessSpecificationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ids** | **[]string** | A list of IDs representing the specification. | 
 **processControlRecipeFamilyId** | **string** | ID representing the process control recipe family. | 
 **processControlRecipeId** | **string** | ID representing the process control recipe. | 
 **operationId** | **string** | ID representing the operation. | 

### Return type

[**[]ProcessSpecificationsApiListProcessSpecificationsItem**](ProcessSpecificationsApiListProcessSpecificationsItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

