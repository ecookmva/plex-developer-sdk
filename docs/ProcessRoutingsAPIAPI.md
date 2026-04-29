# \ProcessRoutingsAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ProcessRoutingsApiCreatePartOperation**](ProcessRoutingsAPIAPI.md#ProcessRoutingsApiCreatePartOperation) | **Post** /mdm/v1/part-operations | Create Part Operation
[**ProcessRoutingsApiDeactivatePartOperation**](ProcessRoutingsAPIAPI.md#ProcessRoutingsApiDeactivatePartOperation) | **Put** /mdm/v1/part-operations/{id}/deactivate | Deactivate Part Operation
[**ProcessRoutingsApiGetNote**](ProcessRoutingsAPIAPI.md#ProcessRoutingsApiGetNote) | **Get** /mdm/v1/part-operations/{id}/notes | Get Note
[**ProcessRoutingsApiGetOperation**](ProcessRoutingsAPIAPI.md#ProcessRoutingsApiGetOperation) | **Get** /mdm/v1/operations/{id} | Get Operation
[**ProcessRoutingsApiGetPartOperation**](ProcessRoutingsAPIAPI.md#ProcessRoutingsApiGetPartOperation) | **Get** /mdm/v1/part-operations/{id} | Get Part Operation
[**ProcessRoutingsApiGetPartOperationDescription**](ProcessRoutingsAPIAPI.md#ProcessRoutingsApiGetPartOperationDescription) | **Get** /mdm/v1/part-operations/{id}/description | Get Part Operation Description
[**ProcessRoutingsApiGetProductionDetails**](ProcessRoutingsAPIAPI.md#ProcessRoutingsApiGetProductionDetails) | **Get** /mdm/v1/part-operations/{id}/production-details | Get Production Details
[**ProcessRoutingsApiGetSchedulingDetails**](ProcessRoutingsAPIAPI.md#ProcessRoutingsApiGetSchedulingDetails) | **Get** /mdm/v1/part-operations/{id}/scheduling-details | Get Scheduling Details
[**ProcessRoutingsApiGetStorageDetails**](ProcessRoutingsAPIAPI.md#ProcessRoutingsApiGetStorageDetails) | **Get** /mdm/v1/part-operations/{id}/storage-details | Get Storage Details
[**ProcessRoutingsApiListOperations**](ProcessRoutingsAPIAPI.md#ProcessRoutingsApiListOperations) | **Get** /mdm/v1/operations | List Operations
[**ProcessRoutingsApiListPartOperations**](ProcessRoutingsAPIAPI.md#ProcessRoutingsApiListPartOperations) | **Get** /mdm/v1/part-operations | List Part Operations
[**ProcessRoutingsApiUpdateNote**](ProcessRoutingsAPIAPI.md#ProcessRoutingsApiUpdateNote) | **Put** /mdm/v1/part-operations/{id}/notes | Update Note
[**ProcessRoutingsApiUpdatePartOperation**](ProcessRoutingsAPIAPI.md#ProcessRoutingsApiUpdatePartOperation) | **Put** /mdm/v1/part-operations/{id} | Update Part Operation
[**ProcessRoutingsApiUpdatePartOperationDescription**](ProcessRoutingsAPIAPI.md#ProcessRoutingsApiUpdatePartOperationDescription) | **Put** /mdm/v1/part-operations/{id}/description | Update Part Operation Description
[**ProcessRoutingsApiUpdateProductionDetails**](ProcessRoutingsAPIAPI.md#ProcessRoutingsApiUpdateProductionDetails) | **Put** /mdm/v1/part-operations/{id}/production-details | Update Production Details
[**ProcessRoutingsApiUpdateSchedulingDetails**](ProcessRoutingsAPIAPI.md#ProcessRoutingsApiUpdateSchedulingDetails) | **Put** /mdm/v1/part-operations/{id}/scheduling-details | Update Scheduling Details
[**ProcessRoutingsApiUpdateStorageDetails**](ProcessRoutingsAPIAPI.md#ProcessRoutingsApiUpdateStorageDetails) | **Put** /mdm/v1/part-operations/{id}/storage-details | Update Storage Details



## ProcessRoutingsApiCreatePartOperation

> ProcessRoutingsApiCreatePartOperation201Response ProcessRoutingsApiCreatePartOperation(ctx).ProcessRoutingsApiCreatePartOperationRequest(processRoutingsApiCreatePartOperationRequest).Execute()

Create Part Operation



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
	processRoutingsApiCreatePartOperationRequest := *openapiclient.NewProcessRoutingsApiCreatePartOperationRequest() // ProcessRoutingsApiCreatePartOperationRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProcessRoutingsAPIAPI.ProcessRoutingsApiCreatePartOperation(context.Background()).ProcessRoutingsApiCreatePartOperationRequest(processRoutingsApiCreatePartOperationRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProcessRoutingsAPIAPI.ProcessRoutingsApiCreatePartOperation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProcessRoutingsApiCreatePartOperation`: ProcessRoutingsApiCreatePartOperation201Response
	fmt.Fprintf(os.Stdout, "Response from `ProcessRoutingsAPIAPI.ProcessRoutingsApiCreatePartOperation`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiProcessRoutingsApiCreatePartOperationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **processRoutingsApiCreatePartOperationRequest** | [**ProcessRoutingsApiCreatePartOperationRequest**](ProcessRoutingsApiCreatePartOperationRequest.md) |  | 

### Return type

[**ProcessRoutingsApiCreatePartOperation201Response**](ProcessRoutingsApiCreatePartOperation201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProcessRoutingsApiDeactivatePartOperation

> ProcessRoutingsApiDeactivatePartOperation(ctx, id).Execute()

Deactivate Part Operation



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
	r, err := apiClient.ProcessRoutingsAPIAPI.ProcessRoutingsApiDeactivatePartOperation(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProcessRoutingsAPIAPI.ProcessRoutingsApiDeactivatePartOperation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiProcessRoutingsApiDeactivatePartOperationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProcessRoutingsApiGetNote

> ProcessRoutingsApiGetNoteResponse ProcessRoutingsApiGetNote(ctx, id).Execute()

Get Note



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
	resp, r, err := apiClient.ProcessRoutingsAPIAPI.ProcessRoutingsApiGetNote(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProcessRoutingsAPIAPI.ProcessRoutingsApiGetNote``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProcessRoutingsApiGetNote`: ProcessRoutingsApiGetNoteResponse
	fmt.Fprintf(os.Stdout, "Response from `ProcessRoutingsAPIAPI.ProcessRoutingsApiGetNote`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiProcessRoutingsApiGetNoteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ProcessRoutingsApiGetNoteResponse**](ProcessRoutingsApiGetNoteResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProcessRoutingsApiGetOperation

> ProcessRoutingsApiGetOperationResponse ProcessRoutingsApiGetOperation(ctx, id).Execute()

Get Operation



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
	id := "00000000-0000-0000-0000-000000000000" // string | The operation ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProcessRoutingsAPIAPI.ProcessRoutingsApiGetOperation(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProcessRoutingsAPIAPI.ProcessRoutingsApiGetOperation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProcessRoutingsApiGetOperation`: ProcessRoutingsApiGetOperationResponse
	fmt.Fprintf(os.Stdout, "Response from `ProcessRoutingsAPIAPI.ProcessRoutingsApiGetOperation`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The operation ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiProcessRoutingsApiGetOperationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ProcessRoutingsApiGetOperationResponse**](ProcessRoutingsApiGetOperationResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProcessRoutingsApiGetPartOperation

> ProcessRoutingsApiGetPartOperationResponse ProcessRoutingsApiGetPartOperation(ctx, id).Execute()

Get Part Operation



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
	resp, r, err := apiClient.ProcessRoutingsAPIAPI.ProcessRoutingsApiGetPartOperation(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProcessRoutingsAPIAPI.ProcessRoutingsApiGetPartOperation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProcessRoutingsApiGetPartOperation`: ProcessRoutingsApiGetPartOperationResponse
	fmt.Fprintf(os.Stdout, "Response from `ProcessRoutingsAPIAPI.ProcessRoutingsApiGetPartOperation`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiProcessRoutingsApiGetPartOperationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ProcessRoutingsApiGetPartOperationResponse**](ProcessRoutingsApiGetPartOperationResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProcessRoutingsApiGetPartOperationDescription

> ProcessRoutingsApiGetPartOperationDescriptionResponse ProcessRoutingsApiGetPartOperationDescription(ctx, id).Execute()

Get Part Operation Description



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
	resp, r, err := apiClient.ProcessRoutingsAPIAPI.ProcessRoutingsApiGetPartOperationDescription(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProcessRoutingsAPIAPI.ProcessRoutingsApiGetPartOperationDescription``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProcessRoutingsApiGetPartOperationDescription`: ProcessRoutingsApiGetPartOperationDescriptionResponse
	fmt.Fprintf(os.Stdout, "Response from `ProcessRoutingsAPIAPI.ProcessRoutingsApiGetPartOperationDescription`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiProcessRoutingsApiGetPartOperationDescriptionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ProcessRoutingsApiGetPartOperationDescriptionResponse**](ProcessRoutingsApiGetPartOperationDescriptionResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProcessRoutingsApiGetProductionDetails

> ProcessRoutingsApiGetProductionDetailsResponse ProcessRoutingsApiGetProductionDetails(ctx, id).Execute()

Get Production Details



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
	resp, r, err := apiClient.ProcessRoutingsAPIAPI.ProcessRoutingsApiGetProductionDetails(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProcessRoutingsAPIAPI.ProcessRoutingsApiGetProductionDetails``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProcessRoutingsApiGetProductionDetails`: ProcessRoutingsApiGetProductionDetailsResponse
	fmt.Fprintf(os.Stdout, "Response from `ProcessRoutingsAPIAPI.ProcessRoutingsApiGetProductionDetails`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiProcessRoutingsApiGetProductionDetailsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ProcessRoutingsApiGetProductionDetailsResponse**](ProcessRoutingsApiGetProductionDetailsResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProcessRoutingsApiGetSchedulingDetails

> ProcessRoutingsApiGetSchedulingDetailsResponse ProcessRoutingsApiGetSchedulingDetails(ctx, id).Execute()

Get Scheduling Details



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
	resp, r, err := apiClient.ProcessRoutingsAPIAPI.ProcessRoutingsApiGetSchedulingDetails(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProcessRoutingsAPIAPI.ProcessRoutingsApiGetSchedulingDetails``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProcessRoutingsApiGetSchedulingDetails`: ProcessRoutingsApiGetSchedulingDetailsResponse
	fmt.Fprintf(os.Stdout, "Response from `ProcessRoutingsAPIAPI.ProcessRoutingsApiGetSchedulingDetails`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiProcessRoutingsApiGetSchedulingDetailsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ProcessRoutingsApiGetSchedulingDetailsResponse**](ProcessRoutingsApiGetSchedulingDetailsResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProcessRoutingsApiGetStorageDetails

> ProcessRoutingsApiGetStorageDetailsResponse ProcessRoutingsApiGetStorageDetails(ctx, id).Execute()

Get Storage Details



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
	resp, r, err := apiClient.ProcessRoutingsAPIAPI.ProcessRoutingsApiGetStorageDetails(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProcessRoutingsAPIAPI.ProcessRoutingsApiGetStorageDetails``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProcessRoutingsApiGetStorageDetails`: ProcessRoutingsApiGetStorageDetailsResponse
	fmt.Fprintf(os.Stdout, "Response from `ProcessRoutingsAPIAPI.ProcessRoutingsApiGetStorageDetails`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiProcessRoutingsApiGetStorageDetailsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ProcessRoutingsApiGetStorageDetailsResponse**](ProcessRoutingsApiGetStorageDetailsResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProcessRoutingsApiListOperations

> []ProcessRoutingsApiListOperationsItem ProcessRoutingsApiListOperations(ctx).Id(id).Code(code).Type_(type_).InventoryType(inventoryType).Execute()

List Operations



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
	id := "00000000-0000-0000-0000-000000000000" // string |  (optional)
	code := "string" // string |  (optional)
	type_ := "string" // string |  (optional)
	inventoryType := "string" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProcessRoutingsAPIAPI.ProcessRoutingsApiListOperations(context.Background()).Id(id).Code(code).Type_(type_).InventoryType(inventoryType).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProcessRoutingsAPIAPI.ProcessRoutingsApiListOperations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProcessRoutingsApiListOperations`: []ProcessRoutingsApiListOperationsItem
	fmt.Fprintf(os.Stdout, "Response from `ProcessRoutingsAPIAPI.ProcessRoutingsApiListOperations`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiProcessRoutingsApiListOperationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **string** |  | 
 **code** | **string** |  | 
 **type_** | **string** |  | 
 **inventoryType** | **string** |  | 

### Return type

[**[]ProcessRoutingsApiListOperationsItem**](ProcessRoutingsApiListOperationsItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProcessRoutingsApiListPartOperations

> []ProcessRoutingsApiListPartOperationsItem ProcessRoutingsApiListPartOperations(ctx).PartId(partId).OperationId(operationId).Active(active).SubOperation(subOperation).OperationNumber(operationNumber).Execute()

List Part Operations



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
	partId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier to a part. (optional)
	operationId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier to an operation. (optional)
	active := false // bool | If the routing is activated for use in production. (optional)
	subOperation := false // bool | Refers to if the operation is encapsulated within another operation. (optional)
	operationNumber := int32(0) // int32 | The order this operation is executed in, usually added in increments of 10 to leave room for inserting additional operations. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProcessRoutingsAPIAPI.ProcessRoutingsApiListPartOperations(context.Background()).PartId(partId).OperationId(operationId).Active(active).SubOperation(subOperation).OperationNumber(operationNumber).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProcessRoutingsAPIAPI.ProcessRoutingsApiListPartOperations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProcessRoutingsApiListPartOperations`: []ProcessRoutingsApiListPartOperationsItem
	fmt.Fprintf(os.Stdout, "Response from `ProcessRoutingsAPIAPI.ProcessRoutingsApiListPartOperations`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiProcessRoutingsApiListPartOperationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **partId** | **string** | A unique identifier to a part. | 
 **operationId** | **string** | A unique identifier to an operation. | 
 **active** | **bool** | If the routing is activated for use in production. | 
 **subOperation** | **bool** | Refers to if the operation is encapsulated within another operation. | 
 **operationNumber** | **int32** | The order this operation is executed in, usually added in increments of 10 to leave room for inserting additional operations. | 

### Return type

[**[]ProcessRoutingsApiListPartOperationsItem**](ProcessRoutingsApiListPartOperationsItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProcessRoutingsApiUpdateNote

> ProcessRoutingsApiUpdateNoteResponse ProcessRoutingsApiUpdateNote(ctx, id).ProcessRoutingsApiUpdateNoteRequest(processRoutingsApiUpdateNoteRequest).Execute()

Update Note



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
	processRoutingsApiUpdateNoteRequest := *openapiclient.NewProcessRoutingsApiUpdateNoteRequest() // ProcessRoutingsApiUpdateNoteRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProcessRoutingsAPIAPI.ProcessRoutingsApiUpdateNote(context.Background(), id).ProcessRoutingsApiUpdateNoteRequest(processRoutingsApiUpdateNoteRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProcessRoutingsAPIAPI.ProcessRoutingsApiUpdateNote``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProcessRoutingsApiUpdateNote`: ProcessRoutingsApiUpdateNoteResponse
	fmt.Fprintf(os.Stdout, "Response from `ProcessRoutingsAPIAPI.ProcessRoutingsApiUpdateNote`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiProcessRoutingsApiUpdateNoteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **processRoutingsApiUpdateNoteRequest** | [**ProcessRoutingsApiUpdateNoteRequest**](ProcessRoutingsApiUpdateNoteRequest.md) |  | 

### Return type

[**ProcessRoutingsApiUpdateNoteResponse**](ProcessRoutingsApiUpdateNoteResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProcessRoutingsApiUpdatePartOperation

> ProcessRoutingsApiUpdatePartOperationResponse ProcessRoutingsApiUpdatePartOperation(ctx, id).ProcessRoutingsApiUpdatePartOperationRequest(processRoutingsApiUpdatePartOperationRequest).Execute()

Update Part Operation



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
	processRoutingsApiUpdatePartOperationRequest := *openapiclient.NewProcessRoutingsApiUpdatePartOperationRequest() // ProcessRoutingsApiUpdatePartOperationRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProcessRoutingsAPIAPI.ProcessRoutingsApiUpdatePartOperation(context.Background(), id).ProcessRoutingsApiUpdatePartOperationRequest(processRoutingsApiUpdatePartOperationRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProcessRoutingsAPIAPI.ProcessRoutingsApiUpdatePartOperation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProcessRoutingsApiUpdatePartOperation`: ProcessRoutingsApiUpdatePartOperationResponse
	fmt.Fprintf(os.Stdout, "Response from `ProcessRoutingsAPIAPI.ProcessRoutingsApiUpdatePartOperation`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiProcessRoutingsApiUpdatePartOperationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **processRoutingsApiUpdatePartOperationRequest** | [**ProcessRoutingsApiUpdatePartOperationRequest**](ProcessRoutingsApiUpdatePartOperationRequest.md) |  | 

### Return type

[**ProcessRoutingsApiUpdatePartOperationResponse**](ProcessRoutingsApiUpdatePartOperationResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProcessRoutingsApiUpdatePartOperationDescription

> ProcessRoutingsApiUpdatePartOperationDescriptionResponse ProcessRoutingsApiUpdatePartOperationDescription(ctx, id).ProcessRoutingsApiUpdatePartOperationDescriptionRequest(processRoutingsApiUpdatePartOperationDescriptionRequest).Execute()

Update Part Operation Description



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
	processRoutingsApiUpdatePartOperationDescriptionRequest := *openapiclient.NewProcessRoutingsApiUpdatePartOperationDescriptionRequest() // ProcessRoutingsApiUpdatePartOperationDescriptionRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProcessRoutingsAPIAPI.ProcessRoutingsApiUpdatePartOperationDescription(context.Background(), id).ProcessRoutingsApiUpdatePartOperationDescriptionRequest(processRoutingsApiUpdatePartOperationDescriptionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProcessRoutingsAPIAPI.ProcessRoutingsApiUpdatePartOperationDescription``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProcessRoutingsApiUpdatePartOperationDescription`: ProcessRoutingsApiUpdatePartOperationDescriptionResponse
	fmt.Fprintf(os.Stdout, "Response from `ProcessRoutingsAPIAPI.ProcessRoutingsApiUpdatePartOperationDescription`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiProcessRoutingsApiUpdatePartOperationDescriptionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **processRoutingsApiUpdatePartOperationDescriptionRequest** | [**ProcessRoutingsApiUpdatePartOperationDescriptionRequest**](ProcessRoutingsApiUpdatePartOperationDescriptionRequest.md) |  | 

### Return type

[**ProcessRoutingsApiUpdatePartOperationDescriptionResponse**](ProcessRoutingsApiUpdatePartOperationDescriptionResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProcessRoutingsApiUpdateProductionDetails

> ProcessRoutingsApiUpdateProductionDetailsResponse ProcessRoutingsApiUpdateProductionDetails(ctx, id).ProcessRoutingsApiUpdateProductionDetailsRequest(processRoutingsApiUpdateProductionDetailsRequest).Execute()

Update Production Details



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
	processRoutingsApiUpdateProductionDetailsRequest := *openapiclient.NewProcessRoutingsApiUpdateProductionDetailsRequest() // ProcessRoutingsApiUpdateProductionDetailsRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProcessRoutingsAPIAPI.ProcessRoutingsApiUpdateProductionDetails(context.Background(), id).ProcessRoutingsApiUpdateProductionDetailsRequest(processRoutingsApiUpdateProductionDetailsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProcessRoutingsAPIAPI.ProcessRoutingsApiUpdateProductionDetails``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProcessRoutingsApiUpdateProductionDetails`: ProcessRoutingsApiUpdateProductionDetailsResponse
	fmt.Fprintf(os.Stdout, "Response from `ProcessRoutingsAPIAPI.ProcessRoutingsApiUpdateProductionDetails`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiProcessRoutingsApiUpdateProductionDetailsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **processRoutingsApiUpdateProductionDetailsRequest** | [**ProcessRoutingsApiUpdateProductionDetailsRequest**](ProcessRoutingsApiUpdateProductionDetailsRequest.md) |  | 

### Return type

[**ProcessRoutingsApiUpdateProductionDetailsResponse**](ProcessRoutingsApiUpdateProductionDetailsResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProcessRoutingsApiUpdateSchedulingDetails

> ProcessRoutingsApiUpdateSchedulingDetailsResponse ProcessRoutingsApiUpdateSchedulingDetails(ctx, id).ProcessRoutingsApiUpdateSchedulingDetailsRequest(processRoutingsApiUpdateSchedulingDetailsRequest).Execute()

Update Scheduling Details



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
	processRoutingsApiUpdateSchedulingDetailsRequest := *openapiclient.NewProcessRoutingsApiUpdateSchedulingDetailsRequest() // ProcessRoutingsApiUpdateSchedulingDetailsRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProcessRoutingsAPIAPI.ProcessRoutingsApiUpdateSchedulingDetails(context.Background(), id).ProcessRoutingsApiUpdateSchedulingDetailsRequest(processRoutingsApiUpdateSchedulingDetailsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProcessRoutingsAPIAPI.ProcessRoutingsApiUpdateSchedulingDetails``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProcessRoutingsApiUpdateSchedulingDetails`: ProcessRoutingsApiUpdateSchedulingDetailsResponse
	fmt.Fprintf(os.Stdout, "Response from `ProcessRoutingsAPIAPI.ProcessRoutingsApiUpdateSchedulingDetails`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiProcessRoutingsApiUpdateSchedulingDetailsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **processRoutingsApiUpdateSchedulingDetailsRequest** | [**ProcessRoutingsApiUpdateSchedulingDetailsRequest**](ProcessRoutingsApiUpdateSchedulingDetailsRequest.md) |  | 

### Return type

[**ProcessRoutingsApiUpdateSchedulingDetailsResponse**](ProcessRoutingsApiUpdateSchedulingDetailsResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProcessRoutingsApiUpdateStorageDetails

> ProcessRoutingsApiUpdateStorageDetailsResponse ProcessRoutingsApiUpdateStorageDetails(ctx, id).ProcessRoutingsApiUpdateStorageDetailsRequest(processRoutingsApiUpdateStorageDetailsRequest).Execute()

Update Storage Details



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
	processRoutingsApiUpdateStorageDetailsRequest := *openapiclient.NewProcessRoutingsApiUpdateStorageDetailsRequest() // ProcessRoutingsApiUpdateStorageDetailsRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProcessRoutingsAPIAPI.ProcessRoutingsApiUpdateStorageDetails(context.Background(), id).ProcessRoutingsApiUpdateStorageDetailsRequest(processRoutingsApiUpdateStorageDetailsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProcessRoutingsAPIAPI.ProcessRoutingsApiUpdateStorageDetails``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProcessRoutingsApiUpdateStorageDetails`: ProcessRoutingsApiUpdateStorageDetailsResponse
	fmt.Fprintf(os.Stdout, "Response from `ProcessRoutingsAPIAPI.ProcessRoutingsApiUpdateStorageDetails`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiProcessRoutingsApiUpdateStorageDetailsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **processRoutingsApiUpdateStorageDetailsRequest** | [**ProcessRoutingsApiUpdateStorageDetailsRequest**](ProcessRoutingsApiUpdateStorageDetailsRequest.md) |  | 

### Return type

[**ProcessRoutingsApiUpdateStorageDetailsResponse**](ProcessRoutingsApiUpdateStorageDetailsResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

