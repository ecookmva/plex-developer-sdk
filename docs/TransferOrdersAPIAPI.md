# \TransferOrdersAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**TransferOrdersApiCancelTransferOrder**](TransferOrdersAPIAPI.md#TransferOrdersApiCancelTransferOrder) | **Post** /shipping/v1-beta1/transfer-orders/{id}/cancel | Cancel Transfer Order
[**TransferOrdersApiCreateTransferOrder**](TransferOrdersAPIAPI.md#TransferOrdersApiCreateTransferOrder) | **Post** /shipping/v1-beta1/transfer-orders | Create Transfer Order
[**TransferOrdersApiGetTransferOrder**](TransferOrdersAPIAPI.md#TransferOrdersApiGetTransferOrder) | **Get** /shipping/v1-beta1/transfer-orders/{id} | Get Transfer Order
[**TransferOrdersApiListTransferOrders**](TransferOrdersAPIAPI.md#TransferOrdersApiListTransferOrders) | **Get** /shipping/v1-beta1/transfer-orders | List Transfer Orders
[**TransferOrdersApiUpdateTransferOrder**](TransferOrdersAPIAPI.md#TransferOrdersApiUpdateTransferOrder) | **Put** /shipping/v1-beta1/transfer-orders/{id} | Update Transfer Order



## TransferOrdersApiCancelTransferOrder

> TransferOrdersApiCancelTransferOrderResponse TransferOrdersApiCancelTransferOrder(ctx, id).Execute()

Cancel Transfer Order



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
	id := "00000000-0000-0000-0000-000000000000" // string | The id of transfer order to be cancelled.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TransferOrdersAPIAPI.TransferOrdersApiCancelTransferOrder(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TransferOrdersAPIAPI.TransferOrdersApiCancelTransferOrder``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TransferOrdersApiCancelTransferOrder`: TransferOrdersApiCancelTransferOrderResponse
	fmt.Fprintf(os.Stdout, "Response from `TransferOrdersAPIAPI.TransferOrdersApiCancelTransferOrder`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The id of transfer order to be cancelled. | 

### Other Parameters

Other parameters are passed through a pointer to a apiTransferOrdersApiCancelTransferOrderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**TransferOrdersApiCancelTransferOrderResponse**](TransferOrdersApiCancelTransferOrderResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TransferOrdersApiCreateTransferOrder

> TransferOrdersApiCreateTransferOrder201Response TransferOrdersApiCreateTransferOrder(ctx).TransferOrdersApiCreateTransferOrderRequest(transferOrdersApiCreateTransferOrderRequest).Execute()

Create Transfer Order



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
	transferOrdersApiCreateTransferOrderRequest := *openapiclient.NewTransferOrdersApiCreateTransferOrderRequest() // TransferOrdersApiCreateTransferOrderRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TransferOrdersAPIAPI.TransferOrdersApiCreateTransferOrder(context.Background()).TransferOrdersApiCreateTransferOrderRequest(transferOrdersApiCreateTransferOrderRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TransferOrdersAPIAPI.TransferOrdersApiCreateTransferOrder``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TransferOrdersApiCreateTransferOrder`: TransferOrdersApiCreateTransferOrder201Response
	fmt.Fprintf(os.Stdout, "Response from `TransferOrdersAPIAPI.TransferOrdersApiCreateTransferOrder`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiTransferOrdersApiCreateTransferOrderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **transferOrdersApiCreateTransferOrderRequest** | [**TransferOrdersApiCreateTransferOrderRequest**](TransferOrdersApiCreateTransferOrderRequest.md) |  | 

### Return type

[**TransferOrdersApiCreateTransferOrder201Response**](TransferOrdersApiCreateTransferOrder201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TransferOrdersApiGetTransferOrder

> TransferOrdersApiGetTransferOrderResponse TransferOrdersApiGetTransferOrder(ctx, id).Execute()

Get Transfer Order



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
	id := "00000000-0000-0000-0000-000000000000" // string | Transfer order ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TransferOrdersAPIAPI.TransferOrdersApiGetTransferOrder(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TransferOrdersAPIAPI.TransferOrdersApiGetTransferOrder``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TransferOrdersApiGetTransferOrder`: TransferOrdersApiGetTransferOrderResponse
	fmt.Fprintf(os.Stdout, "Response from `TransferOrdersAPIAPI.TransferOrdersApiGetTransferOrder`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Transfer order ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiTransferOrdersApiGetTransferOrderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**TransferOrdersApiGetTransferOrderResponse**](TransferOrdersApiGetTransferOrderResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TransferOrdersApiListTransferOrders

> []TransferOrdersApiListTransferOrdersItem TransferOrdersApiListTransferOrders(ctx).CreatedDateBegin(createdDateBegin).CreatedDateEnd(createdDateEnd).Id(id).LotId(lotId).PartId(partId).RequiredShipDateBegin(requiredShipDateBegin).RequiredShipDateEnd(requiredShipDateEnd).ShipFromId(shipFromId).ShipToId(shipToId).Status(status).SupplyItemId(supplyItemId).TransferOrderNo(transferOrderNo).Type_(type_).Execute()

List Transfer Orders



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	createdDateBegin := time.Now() // time.Time | The beginning date used to return orders that were created within a time frame. (optional)
	createdDateEnd := time.Now() // time.Time | The end date used to return orders that were created within a time frame. (optional)
	id := []string{"00000000-0000-0000-0000-000000000000"} // []string | A unique identifier for the transfer order. (optional)
	lotId := "00000000-0000-0000-0000-000000000000" // string | The ID of the lot allowed on the transfer order. (optional)
	partId := "00000000-0000-0000-0000-000000000000" // string | The ID for a part. (optional)
	requiredShipDateBegin := time.Now() // time.Time | The beginning date used to return orders that were placed within a time frame. (optional)
	requiredShipDateEnd := time.Now() // time.Time | The end date used to return orders that were placed within a time frame. (optional)
	shipFromId := "00000000-0000-0000-0000-000000000000" // string | The ID of the building from which the order will ship. (optional)
	shipToId := "00000000-0000-0000-0000-000000000000" // string | The ID of the building the order will ship to. (optional)
	status := []string{"string"} // []string | The transfer order status. (optional)
	supplyItemId := "00000000-0000-0000-0000-000000000000" // string | The ID for a supply item. (optional)
	transferOrderNo := "string" // string | The internal order number generated by Plex that corresponds to a given transfer order. (optional)
	type_ := "string" // string | The transfer order type. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TransferOrdersAPIAPI.TransferOrdersApiListTransferOrders(context.Background()).CreatedDateBegin(createdDateBegin).CreatedDateEnd(createdDateEnd).Id(id).LotId(lotId).PartId(partId).RequiredShipDateBegin(requiredShipDateBegin).RequiredShipDateEnd(requiredShipDateEnd).ShipFromId(shipFromId).ShipToId(shipToId).Status(status).SupplyItemId(supplyItemId).TransferOrderNo(transferOrderNo).Type_(type_).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TransferOrdersAPIAPI.TransferOrdersApiListTransferOrders``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TransferOrdersApiListTransferOrders`: []TransferOrdersApiListTransferOrdersItem
	fmt.Fprintf(os.Stdout, "Response from `TransferOrdersAPIAPI.TransferOrdersApiListTransferOrders`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiTransferOrdersApiListTransferOrdersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createdDateBegin** | **time.Time** | The beginning date used to return orders that were created within a time frame. | 
 **createdDateEnd** | **time.Time** | The end date used to return orders that were created within a time frame. | 
 **id** | **[]string** | A unique identifier for the transfer order. | 
 **lotId** | **string** | The ID of the lot allowed on the transfer order. | 
 **partId** | **string** | The ID for a part. | 
 **requiredShipDateBegin** | **time.Time** | The beginning date used to return orders that were placed within a time frame. | 
 **requiredShipDateEnd** | **time.Time** | The end date used to return orders that were placed within a time frame. | 
 **shipFromId** | **string** | The ID of the building from which the order will ship. | 
 **shipToId** | **string** | The ID of the building the order will ship to. | 
 **status** | **[]string** | The transfer order status. | 
 **supplyItemId** | **string** | The ID for a supply item. | 
 **transferOrderNo** | **string** | The internal order number generated by Plex that corresponds to a given transfer order. | 
 **type_** | **string** | The transfer order type. | 

### Return type

[**[]TransferOrdersApiListTransferOrdersItem**](TransferOrdersApiListTransferOrdersItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TransferOrdersApiUpdateTransferOrder

> TransferOrdersApiUpdateTransferOrderResponse TransferOrdersApiUpdateTransferOrder(ctx, id).TransferOrdersApiUpdateTransferOrderRequest(transferOrdersApiUpdateTransferOrderRequest).Execute()

Update Transfer Order



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
	id := "00000000-0000-0000-0000-000000000000" // string | The id of transfer order to be updated.
	transferOrdersApiUpdateTransferOrderRequest := *openapiclient.NewTransferOrdersApiUpdateTransferOrderRequest() // TransferOrdersApiUpdateTransferOrderRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TransferOrdersAPIAPI.TransferOrdersApiUpdateTransferOrder(context.Background(), id).TransferOrdersApiUpdateTransferOrderRequest(transferOrdersApiUpdateTransferOrderRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TransferOrdersAPIAPI.TransferOrdersApiUpdateTransferOrder``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TransferOrdersApiUpdateTransferOrder`: TransferOrdersApiUpdateTransferOrderResponse
	fmt.Fprintf(os.Stdout, "Response from `TransferOrdersAPIAPI.TransferOrdersApiUpdateTransferOrder`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The id of transfer order to be updated. | 

### Other Parameters

Other parameters are passed through a pointer to a apiTransferOrdersApiUpdateTransferOrderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **transferOrdersApiUpdateTransferOrderRequest** | [**TransferOrdersApiUpdateTransferOrderRequest**](TransferOrdersApiUpdateTransferOrderRequest.md) |  | 

### Return type

[**TransferOrdersApiUpdateTransferOrderResponse**](TransferOrdersApiUpdateTransferOrderResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

