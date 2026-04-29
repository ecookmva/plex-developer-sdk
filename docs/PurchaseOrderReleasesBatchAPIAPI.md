# \PurchaseOrderReleasesBatchAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**PurchaseOrderReleasesBatchApiCancelReleaseBatch**](PurchaseOrderReleasesBatchAPIAPI.md#PurchaseOrderReleasesBatchApiCancelReleaseBatch) | **Post** /purchasing/v1/release-batch/cancel | Cancel Release Batch
[**PurchaseOrderReleasesBatchApiCreateReleaseBatch**](PurchaseOrderReleasesBatchAPIAPI.md#PurchaseOrderReleasesBatchApiCreateReleaseBatch) | **Post** /purchasing/v2-beta1/release-batch/create | Create Release Batch
[**PurchaseOrderReleasesBatchApiDeleteReleaseBatch**](PurchaseOrderReleasesBatchAPIAPI.md#PurchaseOrderReleasesBatchApiDeleteReleaseBatch) | **Post** /purchasing/v2-beta1/release-batch/delete | Delete Release Batch
[**PurchaseOrderReleasesBatchApiGetReleaseBatch**](PurchaseOrderReleasesBatchAPIAPI.md#PurchaseOrderReleasesBatchApiGetReleaseBatch) | **Get** /purchasing/v2-beta1/release-batch/{id} | Get Release Batch
[**PurchaseOrderReleasesBatchApiUpdateReleaseBatch**](PurchaseOrderReleasesBatchAPIAPI.md#PurchaseOrderReleasesBatchApiUpdateReleaseBatch) | **Post** /purchasing/v2-beta1/release-batch/update | Update Release Batch



## PurchaseOrderReleasesBatchApiCancelReleaseBatch

> PurchaseOrderReleasesBatchApiCancelReleaseBatch202Response PurchaseOrderReleasesBatchApiCancelReleaseBatch(ctx).PurchaseOrderReleasesBatchApiCancelReleaseBatchRequest(purchaseOrderReleasesBatchApiCancelReleaseBatchRequest).Execute()

Cancel Release Batch



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
	purchaseOrderReleasesBatchApiCancelReleaseBatchRequest := *openapiclient.NewPurchaseOrderReleasesBatchApiCancelReleaseBatchRequest() // PurchaseOrderReleasesBatchApiCancelReleaseBatchRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PurchaseOrderReleasesBatchAPIAPI.PurchaseOrderReleasesBatchApiCancelReleaseBatch(context.Background()).PurchaseOrderReleasesBatchApiCancelReleaseBatchRequest(purchaseOrderReleasesBatchApiCancelReleaseBatchRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PurchaseOrderReleasesBatchAPIAPI.PurchaseOrderReleasesBatchApiCancelReleaseBatch``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PurchaseOrderReleasesBatchApiCancelReleaseBatch`: PurchaseOrderReleasesBatchApiCancelReleaseBatch202Response
	fmt.Fprintf(os.Stdout, "Response from `PurchaseOrderReleasesBatchAPIAPI.PurchaseOrderReleasesBatchApiCancelReleaseBatch`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPurchaseOrderReleasesBatchApiCancelReleaseBatchRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **purchaseOrderReleasesBatchApiCancelReleaseBatchRequest** | [**PurchaseOrderReleasesBatchApiCancelReleaseBatchRequest**](PurchaseOrderReleasesBatchApiCancelReleaseBatchRequest.md) |  | 

### Return type

[**PurchaseOrderReleasesBatchApiCancelReleaseBatch202Response**](PurchaseOrderReleasesBatchApiCancelReleaseBatch202Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PurchaseOrderReleasesBatchApiCreateReleaseBatch

> PurchaseOrderReleasesBatchApiCreateReleaseBatch202Response PurchaseOrderReleasesBatchApiCreateReleaseBatch(ctx).PurchaseOrderReleasesBatchApiCreateReleaseBatchRequest(purchaseOrderReleasesBatchApiCreateReleaseBatchRequest).Execute()

Create Release Batch



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
	purchaseOrderReleasesBatchApiCreateReleaseBatchRequest := *openapiclient.NewPurchaseOrderReleasesBatchApiCreateReleaseBatchRequest() // PurchaseOrderReleasesBatchApiCreateReleaseBatchRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PurchaseOrderReleasesBatchAPIAPI.PurchaseOrderReleasesBatchApiCreateReleaseBatch(context.Background()).PurchaseOrderReleasesBatchApiCreateReleaseBatchRequest(purchaseOrderReleasesBatchApiCreateReleaseBatchRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PurchaseOrderReleasesBatchAPIAPI.PurchaseOrderReleasesBatchApiCreateReleaseBatch``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PurchaseOrderReleasesBatchApiCreateReleaseBatch`: PurchaseOrderReleasesBatchApiCreateReleaseBatch202Response
	fmt.Fprintf(os.Stdout, "Response from `PurchaseOrderReleasesBatchAPIAPI.PurchaseOrderReleasesBatchApiCreateReleaseBatch`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPurchaseOrderReleasesBatchApiCreateReleaseBatchRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **purchaseOrderReleasesBatchApiCreateReleaseBatchRequest** | [**PurchaseOrderReleasesBatchApiCreateReleaseBatchRequest**](PurchaseOrderReleasesBatchApiCreateReleaseBatchRequest.md) |  | 

### Return type

[**PurchaseOrderReleasesBatchApiCreateReleaseBatch202Response**](PurchaseOrderReleasesBatchApiCreateReleaseBatch202Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PurchaseOrderReleasesBatchApiDeleteReleaseBatch

> PurchaseOrderReleasesBatchApiDeleteReleaseBatch202Response PurchaseOrderReleasesBatchApiDeleteReleaseBatch(ctx).PurchaseOrderReleasesBatchApiDeleteReleaseBatchRequest(purchaseOrderReleasesBatchApiDeleteReleaseBatchRequest).Execute()

Delete Release Batch



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
	purchaseOrderReleasesBatchApiDeleteReleaseBatchRequest := *openapiclient.NewPurchaseOrderReleasesBatchApiDeleteReleaseBatchRequest() // PurchaseOrderReleasesBatchApiDeleteReleaseBatchRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PurchaseOrderReleasesBatchAPIAPI.PurchaseOrderReleasesBatchApiDeleteReleaseBatch(context.Background()).PurchaseOrderReleasesBatchApiDeleteReleaseBatchRequest(purchaseOrderReleasesBatchApiDeleteReleaseBatchRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PurchaseOrderReleasesBatchAPIAPI.PurchaseOrderReleasesBatchApiDeleteReleaseBatch``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PurchaseOrderReleasesBatchApiDeleteReleaseBatch`: PurchaseOrderReleasesBatchApiDeleteReleaseBatch202Response
	fmt.Fprintf(os.Stdout, "Response from `PurchaseOrderReleasesBatchAPIAPI.PurchaseOrderReleasesBatchApiDeleteReleaseBatch`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPurchaseOrderReleasesBatchApiDeleteReleaseBatchRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **purchaseOrderReleasesBatchApiDeleteReleaseBatchRequest** | [**PurchaseOrderReleasesBatchApiDeleteReleaseBatchRequest**](PurchaseOrderReleasesBatchApiDeleteReleaseBatchRequest.md) |  | 

### Return type

[**PurchaseOrderReleasesBatchApiDeleteReleaseBatch202Response**](PurchaseOrderReleasesBatchApiDeleteReleaseBatch202Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PurchaseOrderReleasesBatchApiGetReleaseBatch

> PurchaseOrderReleasesBatchApiGetReleaseBatchResponse PurchaseOrderReleasesBatchApiGetReleaseBatch(ctx, id).Execute()

Get Release Batch



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
	id := "00000000-0000-0000-0000-000000000000" // string | The Batch ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PurchaseOrderReleasesBatchAPIAPI.PurchaseOrderReleasesBatchApiGetReleaseBatch(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PurchaseOrderReleasesBatchAPIAPI.PurchaseOrderReleasesBatchApiGetReleaseBatch``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PurchaseOrderReleasesBatchApiGetReleaseBatch`: PurchaseOrderReleasesBatchApiGetReleaseBatchResponse
	fmt.Fprintf(os.Stdout, "Response from `PurchaseOrderReleasesBatchAPIAPI.PurchaseOrderReleasesBatchApiGetReleaseBatch`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The Batch ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiPurchaseOrderReleasesBatchApiGetReleaseBatchRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**PurchaseOrderReleasesBatchApiGetReleaseBatchResponse**](PurchaseOrderReleasesBatchApiGetReleaseBatchResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PurchaseOrderReleasesBatchApiUpdateReleaseBatch

> PurchaseOrderReleasesBatchApiUpdateReleaseBatch202Response PurchaseOrderReleasesBatchApiUpdateReleaseBatch(ctx).PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest(purchaseOrderReleasesBatchApiUpdateReleaseBatchRequest).Execute()

Update Release Batch



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
	purchaseOrderReleasesBatchApiUpdateReleaseBatchRequest := *openapiclient.NewPurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest() // PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PurchaseOrderReleasesBatchAPIAPI.PurchaseOrderReleasesBatchApiUpdateReleaseBatch(context.Background()).PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest(purchaseOrderReleasesBatchApiUpdateReleaseBatchRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PurchaseOrderReleasesBatchAPIAPI.PurchaseOrderReleasesBatchApiUpdateReleaseBatch``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PurchaseOrderReleasesBatchApiUpdateReleaseBatch`: PurchaseOrderReleasesBatchApiUpdateReleaseBatch202Response
	fmt.Fprintf(os.Stdout, "Response from `PurchaseOrderReleasesBatchAPIAPI.PurchaseOrderReleasesBatchApiUpdateReleaseBatch`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **purchaseOrderReleasesBatchApiUpdateReleaseBatchRequest** | [**PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest**](PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest.md) |  | 

### Return type

[**PurchaseOrderReleasesBatchApiUpdateReleaseBatch202Response**](PurchaseOrderReleasesBatchApiUpdateReleaseBatch202Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

