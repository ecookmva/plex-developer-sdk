# \BOMAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**BomApiCreateBOMComponent**](BOMAPIAPI.md#BomApiCreateBOMComponent) | **Post** /engineering/v1/boms | Create BOM Component
[**BomApiDeactivateBOMComponent**](BOMAPIAPI.md#BomApiDeactivateBOMComponent) | **Post** /engineering/v1/boms/{id}/deactivate | Deactivate BOM Component
[**BomApiGetBOMComponent**](BOMAPIAPI.md#BomApiGetBOMComponent) | **Get** /engineering/v1/boms/{id} | Get BOM Component
[**BomApiListBOMComponents**](BOMAPIAPI.md#BomApiListBOMComponents) | **Get** /engineering/v1/boms | List BOM Components
[**BomApiPatchBOMComponent**](BOMAPIAPI.md#BomApiPatchBOMComponent) | **Patch** /engineering/v1/boms/{id} | Patch BOM Component



## BomApiCreateBOMComponent

> BomApiCreateBOMComponent201Response BomApiCreateBOMComponent(ctx).BomApiCreateBOMComponentRequest(bomApiCreateBOMComponentRequest).Execute()

Create BOM Component



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
	bomApiCreateBOMComponentRequest := *openapiclient.NewBomApiCreateBOMComponentRequest() // BomApiCreateBOMComponentRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BOMAPIAPI.BomApiCreateBOMComponent(context.Background()).BomApiCreateBOMComponentRequest(bomApiCreateBOMComponentRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BOMAPIAPI.BomApiCreateBOMComponent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `BomApiCreateBOMComponent`: BomApiCreateBOMComponent201Response
	fmt.Fprintf(os.Stdout, "Response from `BOMAPIAPI.BomApiCreateBOMComponent`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiBomApiCreateBOMComponentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **bomApiCreateBOMComponentRequest** | [**BomApiCreateBOMComponentRequest**](BomApiCreateBOMComponentRequest.md) |  | 

### Return type

[**BomApiCreateBOMComponent201Response**](BomApiCreateBOMComponent201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## BomApiDeactivateBOMComponent

> BomApiDeactivateBOMComponent(ctx, id).Execute()

Deactivate BOM Component



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
	id := "00000000-0000-0000-0000-000000000000" // string | The ID of the BOM Component.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.BOMAPIAPI.BomApiDeactivateBOMComponent(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BOMAPIAPI.BomApiDeactivateBOMComponent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The ID of the BOM Component. | 

### Other Parameters

Other parameters are passed through a pointer to a apiBomApiDeactivateBOMComponentRequest struct via the builder pattern


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


## BomApiGetBOMComponent

> BomApiGetBOMComponentResponse BomApiGetBOMComponent(ctx, id).Execute()

Get BOM Component



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
	id := "00000000-0000-0000-0000-000000000000" // string | The ID of the BOM Component.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BOMAPIAPI.BomApiGetBOMComponent(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BOMAPIAPI.BomApiGetBOMComponent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `BomApiGetBOMComponent`: BomApiGetBOMComponentResponse
	fmt.Fprintf(os.Stdout, "Response from `BOMAPIAPI.BomApiGetBOMComponent`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The ID of the BOM Component. | 

### Other Parameters

Other parameters are passed through a pointer to a apiBomApiGetBOMComponentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**BomApiGetBOMComponentResponse**](BomApiGetBOMComponentResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## BomApiListBOMComponents

> []BomApiListBOMComponentsItem BomApiListBOMComponents(ctx).PartId(partId).PartOperationId(partOperationId).Execute()

List BOM Components



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
	partId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the part resource.
	partOperationId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the part operation identifier. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BOMAPIAPI.BomApiListBOMComponents(context.Background()).PartId(partId).PartOperationId(partOperationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BOMAPIAPI.BomApiListBOMComponents``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `BomApiListBOMComponents`: []BomApiListBOMComponentsItem
	fmt.Fprintf(os.Stdout, "Response from `BOMAPIAPI.BomApiListBOMComponents`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiBomApiListBOMComponentsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **partId** | **string** | A unique identifier for the part resource. | 
 **partOperationId** | **string** | A unique identifier for the part operation identifier. | 

### Return type

[**[]BomApiListBOMComponentsItem**](BomApiListBOMComponentsItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## BomApiPatchBOMComponent

> BomApiPatchBOMComponentResponse BomApiPatchBOMComponent(ctx, id).BomApiPatchBOMComponentRequest(bomApiPatchBOMComponentRequest).Execute()

Patch BOM Component



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
	id := "00000000-0000-0000-0000-000000000000" // string | The ID of the BOM Component.
	bomApiPatchBOMComponentRequest := *openapiclient.NewBomApiPatchBOMComponentRequest() // BomApiPatchBOMComponentRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BOMAPIAPI.BomApiPatchBOMComponent(context.Background(), id).BomApiPatchBOMComponentRequest(bomApiPatchBOMComponentRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BOMAPIAPI.BomApiPatchBOMComponent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `BomApiPatchBOMComponent`: BomApiPatchBOMComponentResponse
	fmt.Fprintf(os.Stdout, "Response from `BOMAPIAPI.BomApiPatchBOMComponent`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The ID of the BOM Component. | 

### Other Parameters

Other parameters are passed through a pointer to a apiBomApiPatchBOMComponentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **bomApiPatchBOMComponentRequest** | [**BomApiPatchBOMComponentRequest**](BomApiPatchBOMComponentRequest.md) |  | 

### Return type

[**BomApiPatchBOMComponentResponse**](BomApiPatchBOMComponentResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

