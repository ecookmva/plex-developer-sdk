# \InventoryOperationsManagementAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**InventoryOperationsManagementApiAdjustSupplyItems**](InventoryOperationsManagementAPIAPI.md#InventoryOperationsManagementApiAdjustSupplyItems) | **Post** /inventory/v1-beta1/inventory-control/adjust-supply-items | Adjust Supply Items
[**InventoryOperationsManagementApiCreateInventoryReceipt**](InventoryOperationsManagementAPIAPI.md#InventoryOperationsManagementApiCreateInventoryReceipt) | **Post** /inventory/v1/inventory-receiving/receipts | Create Inventory Receipt
[**InventoryOperationsManagementApiCreateInventoryReceiptLot**](InventoryOperationsManagementAPIAPI.md#InventoryOperationsManagementApiCreateInventoryReceiptLot) | **Post** /inventory/v1/inventory-receiving/receipts/{receiptId}/lots | Create Inventory Receipt Lot
[**InventoryOperationsManagementApiCreateInventoryShipment**](InventoryOperationsManagementAPIAPI.md#InventoryOperationsManagementApiCreateInventoryShipment) | **Post** /inventory/v1/inventory-shipping/shipments | Create Inventory Shipment
[**InventoryOperationsManagementApiGetContainer**](InventoryOperationsManagementAPIAPI.md#InventoryOperationsManagementApiGetContainer) | **Get** /inventory/v1/inventory-tracking/containers/{serialNo} | Get Container
[**InventoryOperationsManagementApiGetInventoryReceipt**](InventoryOperationsManagementAPIAPI.md#InventoryOperationsManagementApiGetInventoryReceipt) | **Get** /inventory/v1/inventory-receiving/receipts/{id} | Get Inventory Receipt
[**InventoryOperationsManagementApiGetInventoryReceiptLot**](InventoryOperationsManagementAPIAPI.md#InventoryOperationsManagementApiGetInventoryReceiptLot) | **Get** /inventory/v1/inventory-receiving/receipts/{receiptId}/lots/{lotId} | Get Inventory Receipt Lot
[**InventoryOperationsManagementApiGetInventoryShipment**](InventoryOperationsManagementAPIAPI.md#InventoryOperationsManagementApiGetInventoryShipment) | **Get** /inventory/v1/inventory-shipping/shipments/{id} | Get Inventory Shipment
[**InventoryOperationsManagementApiGetLot**](InventoryOperationsManagementAPIAPI.md#InventoryOperationsManagementApiGetLot) | **Get** /inventory/v1/inventory-tracking/lots/{lotId} | Get Lot
[**InventoryOperationsManagementApiGetPart**](InventoryOperationsManagementAPIAPI.md#InventoryOperationsManagementApiGetPart) | **Get** /inventory/v1/inventory-definitions/parts/{partId} | Get Part
[**InventoryOperationsManagementApiGetSupplyItem**](InventoryOperationsManagementAPIAPI.md#InventoryOperationsManagementApiGetSupplyItem) | **Get** /inventory/v1/inventory-definitions/supply-items/{id} | Get Supply Item
[**InventoryOperationsManagementApiListContainerAdjustments**](InventoryOperationsManagementAPIAPI.md#InventoryOperationsManagementApiListContainerAdjustments) | **Get** /inventory/v1/inventory-history/container-adjustments | List Container Adjustments
[**InventoryOperationsManagementApiListContainerLocationMoves**](InventoryOperationsManagementAPIAPI.md#InventoryOperationsManagementApiListContainerLocationMoves) | **Get** /inventory/v1/inventory-history/container-location-moves | List Container Location Moves
[**InventoryOperationsManagementApiListContainers**](InventoryOperationsManagementAPIAPI.md#InventoryOperationsManagementApiListContainers) | **Get** /inventory/v1/inventory-tracking/containers | List Containers
[**InventoryOperationsManagementApiListInventoryReceiptLots**](InventoryOperationsManagementAPIAPI.md#InventoryOperationsManagementApiListInventoryReceiptLots) | **Get** /inventory/v1/inventory-receiving/receipts/{receiptId}/lots | List Inventory Receipt Lots
[**InventoryOperationsManagementApiListInventoryReceipts**](InventoryOperationsManagementAPIAPI.md#InventoryOperationsManagementApiListInventoryReceipts) | **Get** /inventory/v1/inventory-receiving/receipts | List Inventory Receipts
[**InventoryOperationsManagementApiListInventoryShipments**](InventoryOperationsManagementAPIAPI.md#InventoryOperationsManagementApiListInventoryShipments) | **Get** /inventory/v1/inventory-shipping/shipments | List Inventory Shipments
[**InventoryOperationsManagementApiListLocations**](InventoryOperationsManagementAPIAPI.md#InventoryOperationsManagementApiListLocations) | **Get** /inventory/v1/inventory-definitions/locations | List Locations
[**InventoryOperationsManagementApiListLots**](InventoryOperationsManagementAPIAPI.md#InventoryOperationsManagementApiListLots) | **Get** /inventory/v1/inventory-tracking/lots | List Lots
[**InventoryOperationsManagementApiListParts**](InventoryOperationsManagementAPIAPI.md#InventoryOperationsManagementApiListParts) | **Get** /inventory/v1/inventory-definitions/parts | List Parts
[**InventoryOperationsManagementApiListScrapReasons**](InventoryOperationsManagementAPIAPI.md#InventoryOperationsManagementApiListScrapReasons) | **Get** /inventory/v1/inventory-definitions/scrap-reasons | List Scrap Reasons
[**InventoryOperationsManagementApiListSupplyItemAdjustments**](InventoryOperationsManagementAPIAPI.md#InventoryOperationsManagementApiListSupplyItemAdjustments) | **Get** /inventory/v1-beta1/inventory-history/item-adjustments | List Supply Item Adjustments
[**InventoryOperationsManagementApiListSupplyItems**](InventoryOperationsManagementAPIAPI.md#InventoryOperationsManagementApiListSupplyItems) | **Get** /inventory/v1/inventory-definitions/supply-items | List Supply Items
[**InventoryOperationsManagementApiReceiveInventoryContainers**](InventoryOperationsManagementAPIAPI.md#InventoryOperationsManagementApiReceiveInventoryContainers) | **Post** /inventory/v1/inventory-receiving/receipts/{id}/receive | Receive Inventory Containers
[**InventoryOperationsManagementApiRetireContainer**](InventoryOperationsManagementAPIAPI.md#InventoryOperationsManagementApiRetireContainer) | **Post** /inventory/v1/inventory-control/containers/{serialNo}/retire | Retire Container
[**InventoryOperationsManagementApiScrapContainer**](InventoryOperationsManagementAPIAPI.md#InventoryOperationsManagementApiScrapContainer) | **Post** /inventory/v1/inventory-control/containers/{serialNo}/scrap | Scrap Container
[**InventoryOperationsManagementApiShipInventory**](InventoryOperationsManagementAPIAPI.md#InventoryOperationsManagementApiShipInventory) | **Post** /inventory/v1-beta1/inventory-shipping/shipments/{id}/ship | Ship Inventory
[**InventoryOperationsManagementApiStageInventory**](InventoryOperationsManagementAPIAPI.md#InventoryOperationsManagementApiStageInventory) | **Post** /inventory/v1-beta1/inventory-shipping/shipments/{id}/stage | Stage Inventory
[**InventoryOperationsManagementApiUnshipInventory**](InventoryOperationsManagementAPIAPI.md#InventoryOperationsManagementApiUnshipInventory) | **Post** /inventory/v1-beta1/inventory-shipping/shipments/{id}/unship | Unship Inventory
[**InventoryOperationsManagementApiUnstageInventory**](InventoryOperationsManagementAPIAPI.md#InventoryOperationsManagementApiUnstageInventory) | **Post** /inventory/v1-beta1/inventory-shipping/shipments/{id}/unstage | Unstage Inventory



## InventoryOperationsManagementApiAdjustSupplyItems

> InventoryOperationsManagementApiAdjustSupplyItems(ctx).InventoryOperationsManagementApiAdjustSupplyItemsRequest(inventoryOperationsManagementApiAdjustSupplyItemsRequest).Execute()

Adjust Supply Items



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
	inventoryOperationsManagementApiAdjustSupplyItemsRequest := *openapiclient.NewInventoryOperationsManagementApiAdjustSupplyItemsRequest() // InventoryOperationsManagementApiAdjustSupplyItemsRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiAdjustSupplyItems(context.Background()).InventoryOperationsManagementApiAdjustSupplyItemsRequest(inventoryOperationsManagementApiAdjustSupplyItemsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiAdjustSupplyItems``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiInventoryOperationsManagementApiAdjustSupplyItemsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **inventoryOperationsManagementApiAdjustSupplyItemsRequest** | [**InventoryOperationsManagementApiAdjustSupplyItemsRequest**](InventoryOperationsManagementApiAdjustSupplyItemsRequest.md) |  | 

### Return type

 (empty response body)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## InventoryOperationsManagementApiCreateInventoryReceipt

> InventoryOperationsManagementApiCreateInventoryReceipt201Response InventoryOperationsManagementApiCreateInventoryReceipt(ctx).InventoryOperationsManagementApiCreateInventoryReceiptRequest(inventoryOperationsManagementApiCreateInventoryReceiptRequest).Execute()

Create Inventory Receipt



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
	inventoryOperationsManagementApiCreateInventoryReceiptRequest := *openapiclient.NewInventoryOperationsManagementApiCreateInventoryReceiptRequest() // InventoryOperationsManagementApiCreateInventoryReceiptRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiCreateInventoryReceipt(context.Background()).InventoryOperationsManagementApiCreateInventoryReceiptRequest(inventoryOperationsManagementApiCreateInventoryReceiptRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiCreateInventoryReceipt``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `InventoryOperationsManagementApiCreateInventoryReceipt`: InventoryOperationsManagementApiCreateInventoryReceipt201Response
	fmt.Fprintf(os.Stdout, "Response from `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiCreateInventoryReceipt`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiInventoryOperationsManagementApiCreateInventoryReceiptRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **inventoryOperationsManagementApiCreateInventoryReceiptRequest** | [**InventoryOperationsManagementApiCreateInventoryReceiptRequest**](InventoryOperationsManagementApiCreateInventoryReceiptRequest.md) |  | 

### Return type

[**InventoryOperationsManagementApiCreateInventoryReceipt201Response**](InventoryOperationsManagementApiCreateInventoryReceipt201Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## InventoryOperationsManagementApiCreateInventoryReceiptLot

> InventoryOperationsManagementApiCreateInventoryReceiptLot201Response InventoryOperationsManagementApiCreateInventoryReceiptLot(ctx, receiptId).InventoryOperationsManagementApiCreateInventoryReceiptLotRequest(inventoryOperationsManagementApiCreateInventoryReceiptLotRequest).Execute()

Create Inventory Receipt Lot



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
	receiptId := "00000000-0000-0000-0000-000000000000" // string | The inventory receipt ID.
	inventoryOperationsManagementApiCreateInventoryReceiptLotRequest := *openapiclient.NewInventoryOperationsManagementApiCreateInventoryReceiptLotRequest() // InventoryOperationsManagementApiCreateInventoryReceiptLotRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiCreateInventoryReceiptLot(context.Background(), receiptId).InventoryOperationsManagementApiCreateInventoryReceiptLotRequest(inventoryOperationsManagementApiCreateInventoryReceiptLotRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiCreateInventoryReceiptLot``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `InventoryOperationsManagementApiCreateInventoryReceiptLot`: InventoryOperationsManagementApiCreateInventoryReceiptLot201Response
	fmt.Fprintf(os.Stdout, "Response from `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiCreateInventoryReceiptLot`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**receiptId** | **string** | The inventory receipt ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiInventoryOperationsManagementApiCreateInventoryReceiptLotRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **inventoryOperationsManagementApiCreateInventoryReceiptLotRequest** | [**InventoryOperationsManagementApiCreateInventoryReceiptLotRequest**](InventoryOperationsManagementApiCreateInventoryReceiptLotRequest.md) |  | 

### Return type

[**InventoryOperationsManagementApiCreateInventoryReceiptLot201Response**](InventoryOperationsManagementApiCreateInventoryReceiptLot201Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## InventoryOperationsManagementApiCreateInventoryShipment

> InventoryOperationsManagementApiCreateInventoryShipment201Response InventoryOperationsManagementApiCreateInventoryShipment(ctx).InventoryOperationsManagementApiCreateInventoryShipmentRequest(inventoryOperationsManagementApiCreateInventoryShipmentRequest).Execute()

Create Inventory Shipment



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
	inventoryOperationsManagementApiCreateInventoryShipmentRequest := *openapiclient.NewInventoryOperationsManagementApiCreateInventoryShipmentRequest() // InventoryOperationsManagementApiCreateInventoryShipmentRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiCreateInventoryShipment(context.Background()).InventoryOperationsManagementApiCreateInventoryShipmentRequest(inventoryOperationsManagementApiCreateInventoryShipmentRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiCreateInventoryShipment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `InventoryOperationsManagementApiCreateInventoryShipment`: InventoryOperationsManagementApiCreateInventoryShipment201Response
	fmt.Fprintf(os.Stdout, "Response from `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiCreateInventoryShipment`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiInventoryOperationsManagementApiCreateInventoryShipmentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **inventoryOperationsManagementApiCreateInventoryShipmentRequest** | [**InventoryOperationsManagementApiCreateInventoryShipmentRequest**](InventoryOperationsManagementApiCreateInventoryShipmentRequest.md) |  | 

### Return type

[**InventoryOperationsManagementApiCreateInventoryShipment201Response**](InventoryOperationsManagementApiCreateInventoryShipment201Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## InventoryOperationsManagementApiGetContainer

> InventoryOperationsManagementApiGetContainerResponse InventoryOperationsManagementApiGetContainer(ctx, serialNo).Execute()

Get Container



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
	serialNo := "string" // string | Serial Number to search for.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiGetContainer(context.Background(), serialNo).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiGetContainer``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `InventoryOperationsManagementApiGetContainer`: InventoryOperationsManagementApiGetContainerResponse
	fmt.Fprintf(os.Stdout, "Response from `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiGetContainer`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serialNo** | **string** | Serial Number to search for. | 

### Other Parameters

Other parameters are passed through a pointer to a apiInventoryOperationsManagementApiGetContainerRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**InventoryOperationsManagementApiGetContainerResponse**](InventoryOperationsManagementApiGetContainerResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## InventoryOperationsManagementApiGetInventoryReceipt

> InventoryOperationsManagementApiGetInventoryReceiptResponse InventoryOperationsManagementApiGetInventoryReceipt(ctx, id).Execute()

Get Inventory Receipt



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
	id := "00000000-0000-0000-0000-000000000000" // string | The inventory receipt ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiGetInventoryReceipt(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiGetInventoryReceipt``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `InventoryOperationsManagementApiGetInventoryReceipt`: InventoryOperationsManagementApiGetInventoryReceiptResponse
	fmt.Fprintf(os.Stdout, "Response from `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiGetInventoryReceipt`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The inventory receipt ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiInventoryOperationsManagementApiGetInventoryReceiptRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**InventoryOperationsManagementApiGetInventoryReceiptResponse**](InventoryOperationsManagementApiGetInventoryReceiptResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## InventoryOperationsManagementApiGetInventoryReceiptLot

> InventoryOperationsManagementApiGetInventoryReceiptLotResponse InventoryOperationsManagementApiGetInventoryReceiptLot(ctx, receiptId, lotId).Execute()

Get Inventory Receipt Lot



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
	receiptId := "00000000-0000-0000-0000-000000000000" // string | The inventory receipt ID.
	lotId := "00000000-0000-0000-0000-000000000000" // string | The lot ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiGetInventoryReceiptLot(context.Background(), receiptId, lotId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiGetInventoryReceiptLot``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `InventoryOperationsManagementApiGetInventoryReceiptLot`: InventoryOperationsManagementApiGetInventoryReceiptLotResponse
	fmt.Fprintf(os.Stdout, "Response from `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiGetInventoryReceiptLot`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**receiptId** | **string** | The inventory receipt ID. | 
**lotId** | **string** | The lot ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiInventoryOperationsManagementApiGetInventoryReceiptLotRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**InventoryOperationsManagementApiGetInventoryReceiptLotResponse**](InventoryOperationsManagementApiGetInventoryReceiptLotResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## InventoryOperationsManagementApiGetInventoryShipment

> InventoryOperationsManagementApiGetInventoryShipmentResponse InventoryOperationsManagementApiGetInventoryShipment(ctx, id).Execute()

Get Inventory Shipment



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
	id := "00000000-0000-0000-0000-000000000000" // string | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. The Inventory Shipment Resource ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiGetInventoryShipment(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiGetInventoryShipment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `InventoryOperationsManagementApiGetInventoryShipment`: InventoryOperationsManagementApiGetInventoryShipmentResponse
	fmt.Fprintf(os.Stdout, "Response from `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiGetInventoryShipment`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. The Inventory Shipment Resource ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiInventoryOperationsManagementApiGetInventoryShipmentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**InventoryOperationsManagementApiGetInventoryShipmentResponse**](InventoryOperationsManagementApiGetInventoryShipmentResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## InventoryOperationsManagementApiGetLot

> InventoryOperationsManagementApiGetLotResponse InventoryOperationsManagementApiGetLot(ctx, lotId).Execute()

Get Lot



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
	lotId := "00000000-0000-0000-0000-000000000000" // string | The UUID assigned to a lot.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiGetLot(context.Background(), lotId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiGetLot``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `InventoryOperationsManagementApiGetLot`: InventoryOperationsManagementApiGetLotResponse
	fmt.Fprintf(os.Stdout, "Response from `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiGetLot`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**lotId** | **string** | The UUID assigned to a lot. | 

### Other Parameters

Other parameters are passed through a pointer to a apiInventoryOperationsManagementApiGetLotRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**InventoryOperationsManagementApiGetLotResponse**](InventoryOperationsManagementApiGetLotResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## InventoryOperationsManagementApiGetPart

> InventoryOperationsManagementApiGetPartResponse InventoryOperationsManagementApiGetPart(ctx, partId).Execute()

Get Part



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
	partId := "00000000-0000-0000-0000-000000000000" // string | The UUID assigned to a part.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiGetPart(context.Background(), partId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiGetPart``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `InventoryOperationsManagementApiGetPart`: InventoryOperationsManagementApiGetPartResponse
	fmt.Fprintf(os.Stdout, "Response from `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiGetPart`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**partId** | **string** | The UUID assigned to a part. | 

### Other Parameters

Other parameters are passed through a pointer to a apiInventoryOperationsManagementApiGetPartRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**InventoryOperationsManagementApiGetPartResponse**](InventoryOperationsManagementApiGetPartResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## InventoryOperationsManagementApiGetSupplyItem

> InventoryOperationsManagementApiGetSupplyItemResponse InventoryOperationsManagementApiGetSupplyItem(ctx, id).Execute()

Get Supply Item



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
	id := "00000000-0000-0000-0000-000000000000" // string | Supply Item Resource ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiGetSupplyItem(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiGetSupplyItem``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `InventoryOperationsManagementApiGetSupplyItem`: InventoryOperationsManagementApiGetSupplyItemResponse
	fmt.Fprintf(os.Stdout, "Response from `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiGetSupplyItem`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Supply Item Resource ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiInventoryOperationsManagementApiGetSupplyItemRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**InventoryOperationsManagementApiGetSupplyItemResponse**](InventoryOperationsManagementApiGetSupplyItemResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## InventoryOperationsManagementApiListContainerAdjustments

> []InventoryOperationsManagementApiListContainerAdjustmentsItem InventoryOperationsManagementApiListContainerAdjustments(ctx).BeginDate(beginDate).EndDate(endDate).SerialNo(serialNo).PartId(partId).PartOperationId(partOperationId).AdjustmentCode(adjustmentCode).LocationId(locationId).Execute()

List Container Adjustments



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
	beginDate := time.Now() // time.Time | The date and time from when container adjustment transactions are to be retrieved.
	endDate := time.Now() // time.Time | The date and time until when container adjustment transactions are to be retrieved.
	serialNo := "string" // string | 25 characters max. The serial number of the container that was adjusted. (optional)
	partId := "00000000-0000-0000-0000-000000000000" // string | The container's Part ID. (optional)
	partOperationId := "00000000-0000-0000-0000-000000000000" // string | The container's Part Operation ID. (optional)
	adjustmentCode := "string" // string | 50 characters max. Setup table &quot;Adjustment Reason&quot; (part.dbo.adjustment_reason). The Adjustment Reason setup table lists the acceptable reasons for inventory changes. (optional)
	locationId := "00000000-0000-0000-0000-000000000000" // string | The location ID of the container that was adjusted. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiListContainerAdjustments(context.Background()).BeginDate(beginDate).EndDate(endDate).SerialNo(serialNo).PartId(partId).PartOperationId(partOperationId).AdjustmentCode(adjustmentCode).LocationId(locationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiListContainerAdjustments``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `InventoryOperationsManagementApiListContainerAdjustments`: []InventoryOperationsManagementApiListContainerAdjustmentsItem
	fmt.Fprintf(os.Stdout, "Response from `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiListContainerAdjustments`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiInventoryOperationsManagementApiListContainerAdjustmentsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **beginDate** | **time.Time** | The date and time from when container adjustment transactions are to be retrieved. | 
 **endDate** | **time.Time** | The date and time until when container adjustment transactions are to be retrieved. | 
 **serialNo** | **string** | 25 characters max. The serial number of the container that was adjusted. | 
 **partId** | **string** | The container&#39;s Part ID. | 
 **partOperationId** | **string** | The container&#39;s Part Operation ID. | 
 **adjustmentCode** | **string** | 50 characters max. Setup table &amp;quot;Adjustment Reason&amp;quot; (part.dbo.adjustment_reason). The Adjustment Reason setup table lists the acceptable reasons for inventory changes. | 
 **locationId** | **string** | The location ID of the container that was adjusted. | 

### Return type

[**[]InventoryOperationsManagementApiListContainerAdjustmentsItem**](InventoryOperationsManagementApiListContainerAdjustmentsItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## InventoryOperationsManagementApiListContainerLocationMoves

> []InventoryOperationsManagementApiListContainerLocationMovesItem InventoryOperationsManagementApiListContainerLocationMoves(ctx).BeginDate(beginDate).EndDate(endDate).SerialNo(serialNo).PartId(partId).PartOperationId(partOperationId).PartType(partType).PartGroup(partGroup).PartSource(partSource).LocationId(locationId).MovedFromLocationId(movedFromLocationId).Execute()

List Container Location Moves



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
	beginDate := time.Now() // time.Time | The date and time from when container change transactions are to be retrieved.
	endDate := time.Now() // time.Time | The date and time until when container change transactions are to be retrieved.
	serialNo := "string" // string | 25 characters max. The serial number of the container that was changed. (optional)
	partId := "00000000-0000-0000-0000-000000000000" // string | The container's Part ID. (optional)
	partOperationId := "00000000-0000-0000-0000-000000000000" // string | The container's Part Operation ID. (optional)
	partType := "string" // string | 50 characters max. Setup table &quot;Part Type&quot; (part.dbo.Part_Type). Subclassification for the part. Examples include flange, fastener, gears, crown wheels, clutch hubs, body panels, gear shafts. (optional)
	partGroup := "string" // string | 50 characters max. Setup table &quot;Part Group&quot; (part.dbo.Part_Group). Subclassification for the part. (optional)
	partSource := "string" // string | 50 characters max. Setup table &quot;Part Source&quot; (part.dbo.Part_Source). Categorize where the parts are from, purchased or made in house. The field is not tied to purchasing for lookups or searches. (optional)
	locationId := "00000000-0000-0000-0000-000000000000" // string | The location ID of the container that was changed. (optional)
	movedFromLocationId := "00000000-0000-0000-0000-000000000000" // string | The prior location ID of the container before it was changed. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiListContainerLocationMoves(context.Background()).BeginDate(beginDate).EndDate(endDate).SerialNo(serialNo).PartId(partId).PartOperationId(partOperationId).PartType(partType).PartGroup(partGroup).PartSource(partSource).LocationId(locationId).MovedFromLocationId(movedFromLocationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiListContainerLocationMoves``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `InventoryOperationsManagementApiListContainerLocationMoves`: []InventoryOperationsManagementApiListContainerLocationMovesItem
	fmt.Fprintf(os.Stdout, "Response from `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiListContainerLocationMoves`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiInventoryOperationsManagementApiListContainerLocationMovesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **beginDate** | **time.Time** | The date and time from when container change transactions are to be retrieved. | 
 **endDate** | **time.Time** | The date and time until when container change transactions are to be retrieved. | 
 **serialNo** | **string** | 25 characters max. The serial number of the container that was changed. | 
 **partId** | **string** | The container&#39;s Part ID. | 
 **partOperationId** | **string** | The container&#39;s Part Operation ID. | 
 **partType** | **string** | 50 characters max. Setup table &amp;quot;Part Type&amp;quot; (part.dbo.Part_Type). Subclassification for the part. Examples include flange, fastener, gears, crown wheels, clutch hubs, body panels, gear shafts. | 
 **partGroup** | **string** | 50 characters max. Setup table &amp;quot;Part Group&amp;quot; (part.dbo.Part_Group). Subclassification for the part. | 
 **partSource** | **string** | 50 characters max. Setup table &amp;quot;Part Source&amp;quot; (part.dbo.Part_Source). Categorize where the parts are from, purchased or made in house. The field is not tied to purchasing for lookups or searches. | 
 **locationId** | **string** | The location ID of the container that was changed. | 
 **movedFromLocationId** | **string** | The prior location ID of the container before it was changed. | 

### Return type

[**[]InventoryOperationsManagementApiListContainerLocationMovesItem**](InventoryOperationsManagementApiListContainerLocationMovesItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## InventoryOperationsManagementApiListContainers

> []InventoryOperationsManagementApiListContainersItem InventoryOperationsManagementApiListContainers(ctx).PartId(partId).LocationId(locationId).MasterUnitId(masterUnitId).LotId(lotId).Eun(eun).InventoryType(inventoryType).Execute()

List Containers



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
	partId := "00000000-0000-0000-0000-000000000000" // string | The ID of the part. (optional)
	locationId := "00000000-0000-0000-0000-000000000000" // string | The ID associated with the inventory location. (optional)
	masterUnitId := "00000000-0000-0000-0000-000000000000" // string | The ID of the master unit associated with the container. (optional)
	lotId := "00000000-0000-0000-0000-000000000000" // string | The lot ID associated with the container. (optional)
	eun := "string" // string | The EUN associated with the container. (optional)
	inventoryType := []string{"string"} // []string | The list of inventory types. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiListContainers(context.Background()).PartId(partId).LocationId(locationId).MasterUnitId(masterUnitId).LotId(lotId).Eun(eun).InventoryType(inventoryType).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiListContainers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `InventoryOperationsManagementApiListContainers`: []InventoryOperationsManagementApiListContainersItem
	fmt.Fprintf(os.Stdout, "Response from `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiListContainers`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiInventoryOperationsManagementApiListContainersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **partId** | **string** | The ID of the part. | 
 **locationId** | **string** | The ID associated with the inventory location. | 
 **masterUnitId** | **string** | The ID of the master unit associated with the container. | 
 **lotId** | **string** | The lot ID associated with the container. | 
 **eun** | **string** | The EUN associated with the container. | 
 **inventoryType** | **[]string** | The list of inventory types. | 

### Return type

[**[]InventoryOperationsManagementApiListContainersItem**](InventoryOperationsManagementApiListContainersItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## InventoryOperationsManagementApiListInventoryReceiptLots

> []InventoryOperationsManagementApiListInventoryReceiptLotsItem InventoryOperationsManagementApiListInventoryReceiptLots(ctx, receiptId).LotNumber(lotNumber).PartId(partId).SupplierLotNumber(supplierLotNumber).BeginManufacturedDateTime(beginManufacturedDateTime).EndManufacturedDateTime(endManufacturedDateTime).Execute()

List Inventory Receipt Lots



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
	receiptId := "00000000-0000-0000-0000-000000000000" // string | The inventory receipt ID.
	lotNumber := "string" // string | Search by Lot Number. (optional)
	partId := "00000000-0000-0000-0000-000000000000" // string | Search by Part ID. (optional)
	supplierLotNumber := "string" // string | Search by supplier lot number. (optional)
	beginManufacturedDateTime := time.Now() // time.Time | Search by Manufactured Date begin date. (optional)
	endManufacturedDateTime := time.Now() // time.Time | Search by Manufactured Date end date. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiListInventoryReceiptLots(context.Background(), receiptId).LotNumber(lotNumber).PartId(partId).SupplierLotNumber(supplierLotNumber).BeginManufacturedDateTime(beginManufacturedDateTime).EndManufacturedDateTime(endManufacturedDateTime).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiListInventoryReceiptLots``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `InventoryOperationsManagementApiListInventoryReceiptLots`: []InventoryOperationsManagementApiListInventoryReceiptLotsItem
	fmt.Fprintf(os.Stdout, "Response from `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiListInventoryReceiptLots`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**receiptId** | **string** | The inventory receipt ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiInventoryOperationsManagementApiListInventoryReceiptLotsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **lotNumber** | **string** | Search by Lot Number. | 
 **partId** | **string** | Search by Part ID. | 
 **supplierLotNumber** | **string** | Search by supplier lot number. | 
 **beginManufacturedDateTime** | **time.Time** | Search by Manufactured Date begin date. | 
 **endManufacturedDateTime** | **time.Time** | Search by Manufactured Date end date. | 

### Return type

[**[]InventoryOperationsManagementApiListInventoryReceiptLotsItem**](InventoryOperationsManagementApiListInventoryReceiptLotsItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## InventoryOperationsManagementApiListInventoryReceipts

> []InventoryOperationsManagementApiListInventoryReceiptsItem InventoryOperationsManagementApiListInventoryReceipts(ctx).ExternalReceiptCode(externalReceiptCode).PartId(partId).Execute()

List Inventory Receipts



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
	externalReceiptCode := "string" // string | The external receipt code. (optional)
	partId := "00000000-0000-0000-0000-000000000000" // string | The part ID. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiListInventoryReceipts(context.Background()).ExternalReceiptCode(externalReceiptCode).PartId(partId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiListInventoryReceipts``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `InventoryOperationsManagementApiListInventoryReceipts`: []InventoryOperationsManagementApiListInventoryReceiptsItem
	fmt.Fprintf(os.Stdout, "Response from `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiListInventoryReceipts`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiInventoryOperationsManagementApiListInventoryReceiptsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **externalReceiptCode** | **string** | The external receipt code. | 
 **partId** | **string** | The part ID. | 

### Return type

[**[]InventoryOperationsManagementApiListInventoryReceiptsItem**](InventoryOperationsManagementApiListInventoryReceiptsItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## InventoryOperationsManagementApiListInventoryShipments

> []InventoryOperationsManagementApiListInventoryShipmentsItem InventoryOperationsManagementApiListInventoryShipments(ctx).ExternalShipmentCode(externalShipmentCode).ShipmentStatus(shipmentStatus).Execute()

List Inventory Shipments



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
	externalShipmentCode := "string" // string | 50 character max. The external inventory shipment code. This code is not provided by Plex and is distinct from the shipment ID. (optional)
	shipmentStatus := "string" // string | The inventory shipment status. Valid statuses include &quot;Unstaged&quot;, &quot;Staged&quot;, and &quot;Shipped&quot;. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiListInventoryShipments(context.Background()).ExternalShipmentCode(externalShipmentCode).ShipmentStatus(shipmentStatus).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiListInventoryShipments``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `InventoryOperationsManagementApiListInventoryShipments`: []InventoryOperationsManagementApiListInventoryShipmentsItem
	fmt.Fprintf(os.Stdout, "Response from `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiListInventoryShipments`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiInventoryOperationsManagementApiListInventoryShipmentsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **externalShipmentCode** | **string** | 50 character max. The external inventory shipment code. This code is not provided by Plex and is distinct from the shipment ID. | 
 **shipmentStatus** | **string** | The inventory shipment status. Valid statuses include &amp;quot;Unstaged&amp;quot;, &amp;quot;Staged&amp;quot;, and &amp;quot;Shipped&amp;quot;. | 

### Return type

[**[]InventoryOperationsManagementApiListInventoryShipmentsItem**](InventoryOperationsManagementApiListInventoryShipmentsItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## InventoryOperationsManagementApiListLocations

> []InventoryOperationsManagementApiListLocationsItem InventoryOperationsManagementApiListLocations(ctx).LocationId(locationId).LocationCode(locationCode).LocationTypeFlag(locationTypeFlag).TankSilo(tankSilo).Execute()

List Locations



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
	locationId := "00000000-0000-0000-0000-000000000000" // string | The Location ID. (optional)
	locationCode := "string" // string | The Location Code. (optional)
	locationTypeFlag := "string" // string | The Location Type Flag. (optional)
	tankSilo := false // bool | Boolean indicating whether the results should be filtered to only return tank/silo results. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiListLocations(context.Background()).LocationId(locationId).LocationCode(locationCode).LocationTypeFlag(locationTypeFlag).TankSilo(tankSilo).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiListLocations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `InventoryOperationsManagementApiListLocations`: []InventoryOperationsManagementApiListLocationsItem
	fmt.Fprintf(os.Stdout, "Response from `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiListLocations`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiInventoryOperationsManagementApiListLocationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **locationId** | **string** | The Location ID. | 
 **locationCode** | **string** | The Location Code. | 
 **locationTypeFlag** | **string** | The Location Type Flag. | 
 **tankSilo** | **bool** | Boolean indicating whether the results should be filtered to only return tank/silo results. | 

### Return type

[**[]InventoryOperationsManagementApiListLocationsItem**](InventoryOperationsManagementApiListLocationsItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## InventoryOperationsManagementApiListLots

> []InventoryOperationsManagementApiListLotsItem InventoryOperationsManagementApiListLots(ctx).PartId(partId).PartNumber(partNumber).PartRevision(partRevision).LotNumber(lotNumber).SupplierID(supplierID).BeginManufacturedDateTime(beginManufacturedDateTime).EndManufacturedDateTime(endManufacturedDateTime).BeginBestByDateTime(beginBestByDateTime).EndBestByDateTime(endBestByDateTime).BeginSellByDateTime(beginSellByDateTime).EndSellByDateTime(endSellByDateTime).BeginUseByDateTime(beginUseByDateTime).EndUseByDateTime(endUseByDateTime).Execute()

List Lots



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
	partId := "00000000-0000-0000-0000-000000000000" // string | The part ID. (optional)
	partNumber := "string" // string | 100 characters max. A short code or number to call the part. (optional)
	partRevision := "string" // string | 8 characters max. The container's Part Revision. (optional)
	lotNumber := "string" // string | 25 characters max. A short code or number to call the lot. (optional)
	supplierID := "00000000-0000-0000-0000-000000000000" // string | The supplier ID. (optional)
	beginManufacturedDateTime := time.Now() // time.Time | The date and time from when lots were manufactured are to be retrieved. (optional)
	endManufacturedDateTime := time.Now() // time.Time | The date and time up to when lots were manufactured are to be retrieved. (optional)
	beginBestByDateTime := time.Now() // time.Time | The date and time up to when lots are best by are to be retrieved. (optional)
	endBestByDateTime := time.Now() // time.Time | The date and time up to when lots are best by are to be retrieved. (optional)
	beginSellByDateTime := time.Now() // time.Time | The date and time from when lots can be sold by are to be retrieved. (optional)
	endSellByDateTime := time.Now() // time.Time | The date and time up to when lots can be sold by are to be retrieved. (optional)
	beginUseByDateTime := time.Now() // time.Time | The date and time from when lots can be used by are to be retrieved. (optional)
	endUseByDateTime := time.Now() // time.Time | The date and time up to when lots can be used by are to be retrieved. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiListLots(context.Background()).PartId(partId).PartNumber(partNumber).PartRevision(partRevision).LotNumber(lotNumber).SupplierID(supplierID).BeginManufacturedDateTime(beginManufacturedDateTime).EndManufacturedDateTime(endManufacturedDateTime).BeginBestByDateTime(beginBestByDateTime).EndBestByDateTime(endBestByDateTime).BeginSellByDateTime(beginSellByDateTime).EndSellByDateTime(endSellByDateTime).BeginUseByDateTime(beginUseByDateTime).EndUseByDateTime(endUseByDateTime).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiListLots``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `InventoryOperationsManagementApiListLots`: []InventoryOperationsManagementApiListLotsItem
	fmt.Fprintf(os.Stdout, "Response from `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiListLots`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiInventoryOperationsManagementApiListLotsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **partId** | **string** | The part ID. | 
 **partNumber** | **string** | 100 characters max. A short code or number to call the part. | 
 **partRevision** | **string** | 8 characters max. The container&#39;s Part Revision. | 
 **lotNumber** | **string** | 25 characters max. A short code or number to call the lot. | 
 **supplierID** | **string** | The supplier ID. | 
 **beginManufacturedDateTime** | **time.Time** | The date and time from when lots were manufactured are to be retrieved. | 
 **endManufacturedDateTime** | **time.Time** | The date and time up to when lots were manufactured are to be retrieved. | 
 **beginBestByDateTime** | **time.Time** | The date and time up to when lots are best by are to be retrieved. | 
 **endBestByDateTime** | **time.Time** | The date and time up to when lots are best by are to be retrieved. | 
 **beginSellByDateTime** | **time.Time** | The date and time from when lots can be sold by are to be retrieved. | 
 **endSellByDateTime** | **time.Time** | The date and time up to when lots can be sold by are to be retrieved. | 
 **beginUseByDateTime** | **time.Time** | The date and time from when lots can be used by are to be retrieved. | 
 **endUseByDateTime** | **time.Time** | The date and time up to when lots can be used by are to be retrieved. | 

### Return type

[**[]InventoryOperationsManagementApiListLotsItem**](InventoryOperationsManagementApiListLotsItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## InventoryOperationsManagementApiListParts

> []InventoryOperationsManagementApiListPartsItem InventoryOperationsManagementApiListParts(ctx).PartNumber(partNumber).PartRevision(partRevision).PartType(partType).PartSource(partSource).PartStatus(partStatus).BeginCreatedDateTime(beginCreatedDateTime).EndCreatedDateTime(endCreatedDateTime).BeginUpdatedDateTime(beginUpdatedDateTime).EndUpdatedDateTime(endUpdatedDateTime).Execute()

List Parts



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
	partNumber := "string" // string | 100 characters max. A short code or number to call the part. This value shows up throughout the system, so use something others will recognize. Acceptable Part Number characters include uppercase and lowercase letters (A-Z), numbers (0-9), and special characters such as dashes (-), underscores ( _ ), and spaces. Other characters may cause issues. (optional)
	partRevision := "string" // string | 8 characters max. A revision level represents a change or modification to a part or part drawing that is usually initiated through an engineering change request (ECR). (optional)
	partType := "string" // string | 50 characters max. Setup table &quot;Part Source&quot; (part.dbo.Part_Status). Subclassification for the part. Examples include flange, fastener, gears, crown wheels, clutch hubs, body panels, gear shafts. (optional)
	partSource := "string" // string | 50 characters max. Setup table &quot;Part Status&quot; (part.dbo.Part_Status). Categorize where the parts are from, purchased or made in house. The field is not tied to purchasing for lookups or searches. (optional)
	partStatus := "string" // string | 50 characters max. Setup table &quot;Part Status&quot; (part.dbo.Part_Status)The part status indicates the life cycle phase of the part. (optional)
	beginCreatedDateTime := time.Now() // time.Time | The beginning date and time from when the parts were created are to be retrieved. (optional)
	endCreatedDateTime := time.Now() // time.Time | The end date and time from when the parts were created are to be retrieved. (optional)
	beginUpdatedDateTime := time.Now() // time.Time | The beginning date and time from when the parts were last updated are to be retrieved. (optional)
	endUpdatedDateTime := time.Now() // time.Time | The end date and time from when the parts were last updated are to be retrieved. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiListParts(context.Background()).PartNumber(partNumber).PartRevision(partRevision).PartType(partType).PartSource(partSource).PartStatus(partStatus).BeginCreatedDateTime(beginCreatedDateTime).EndCreatedDateTime(endCreatedDateTime).BeginUpdatedDateTime(beginUpdatedDateTime).EndUpdatedDateTime(endUpdatedDateTime).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiListParts``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `InventoryOperationsManagementApiListParts`: []InventoryOperationsManagementApiListPartsItem
	fmt.Fprintf(os.Stdout, "Response from `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiListParts`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiInventoryOperationsManagementApiListPartsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **partNumber** | **string** | 100 characters max. A short code or number to call the part. This value shows up throughout the system, so use something others will recognize. Acceptable Part Number characters include uppercase and lowercase letters (A-Z), numbers (0-9), and special characters such as dashes (-), underscores ( _ ), and spaces. Other characters may cause issues. | 
 **partRevision** | **string** | 8 characters max. A revision level represents a change or modification to a part or part drawing that is usually initiated through an engineering change request (ECR). | 
 **partType** | **string** | 50 characters max. Setup table &amp;quot;Part Source&amp;quot; (part.dbo.Part_Status). Subclassification for the part. Examples include flange, fastener, gears, crown wheels, clutch hubs, body panels, gear shafts. | 
 **partSource** | **string** | 50 characters max. Setup table &amp;quot;Part Status&amp;quot; (part.dbo.Part_Status). Categorize where the parts are from, purchased or made in house. The field is not tied to purchasing for lookups or searches. | 
 **partStatus** | **string** | 50 characters max. Setup table &amp;quot;Part Status&amp;quot; (part.dbo.Part_Status)The part status indicates the life cycle phase of the part. | 
 **beginCreatedDateTime** | **time.Time** | The beginning date and time from when the parts were created are to be retrieved. | 
 **endCreatedDateTime** | **time.Time** | The end date and time from when the parts were created are to be retrieved. | 
 **beginUpdatedDateTime** | **time.Time** | The beginning date and time from when the parts were last updated are to be retrieved. | 
 **endUpdatedDateTime** | **time.Time** | The end date and time from when the parts were last updated are to be retrieved. | 

### Return type

[**[]InventoryOperationsManagementApiListPartsItem**](InventoryOperationsManagementApiListPartsItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## InventoryOperationsManagementApiListScrapReasons

> []InventoryOperationsManagementApiListScrapReasonsItem InventoryOperationsManagementApiListScrapReasons(ctx).Execute()

List Scrap Reasons



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiListScrapReasons(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiListScrapReasons``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `InventoryOperationsManagementApiListScrapReasons`: []InventoryOperationsManagementApiListScrapReasonsItem
	fmt.Fprintf(os.Stdout, "Response from `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiListScrapReasons`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiInventoryOperationsManagementApiListScrapReasonsRequest struct via the builder pattern


### Return type

[**[]InventoryOperationsManagementApiListScrapReasonsItem**](InventoryOperationsManagementApiListScrapReasonsItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## InventoryOperationsManagementApiListSupplyItemAdjustments

> []InventoryOperationsManagementApiListSupplyItemAdjustmentsItem InventoryOperationsManagementApiListSupplyItemAdjustments(ctx).ItemId(itemId).LocationId(locationId).BeginDate(beginDate).EndDate(endDate).Execute()

List Supply Item Adjustments



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
	itemId := "00000000-0000-0000-0000-000000000000" // string | Inventory History Item Resource ID.
	locationId := "00000000-0000-0000-0000-000000000000" // string | The Location ID. (optional)
	beginDate := time.Now() // time.Time | The Item Adjustment begin date. (optional)
	endDate := time.Now() // time.Time | The Item Adjustment end date. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiListSupplyItemAdjustments(context.Background()).ItemId(itemId).LocationId(locationId).BeginDate(beginDate).EndDate(endDate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiListSupplyItemAdjustments``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `InventoryOperationsManagementApiListSupplyItemAdjustments`: []InventoryOperationsManagementApiListSupplyItemAdjustmentsItem
	fmt.Fprintf(os.Stdout, "Response from `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiListSupplyItemAdjustments`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiInventoryOperationsManagementApiListSupplyItemAdjustmentsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **itemId** | **string** | Inventory History Item Resource ID. | 
 **locationId** | **string** | The Location ID. | 
 **beginDate** | **time.Time** | The Item Adjustment begin date. | 
 **endDate** | **time.Time** | The Item Adjustment end date. | 

### Return type

[**[]InventoryOperationsManagementApiListSupplyItemAdjustmentsItem**](InventoryOperationsManagementApiListSupplyItemAdjustmentsItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## InventoryOperationsManagementApiListSupplyItems

> []InventoryOperationsManagementApiListSupplyItemsItem InventoryOperationsManagementApiListSupplyItems(ctx).SupplyItemNumber(supplyItemNumber).Type_(type_).Category(category).Group(group).Execute()

List Supply Items



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
	supplyItemNumber := "string" // string | A short identifier for the Supply Item. (optional)
	type_ := "string" // string | Indicates the Supply Item type, such as office supplies or shop supplies. Setup Table: Item Type (optional)
	category := "string" // string | Setup Table: Supply Category (optional)
	group := "string" // string | A supply group, used to categorize Supply Items, such as Electrical, Mechanical, Office Supplies. Setup Table: Item Group (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiListSupplyItems(context.Background()).SupplyItemNumber(supplyItemNumber).Type_(type_).Category(category).Group(group).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiListSupplyItems``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `InventoryOperationsManagementApiListSupplyItems`: []InventoryOperationsManagementApiListSupplyItemsItem
	fmt.Fprintf(os.Stdout, "Response from `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiListSupplyItems`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiInventoryOperationsManagementApiListSupplyItemsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **supplyItemNumber** | **string** | A short identifier for the Supply Item. | 
 **type_** | **string** | Indicates the Supply Item type, such as office supplies or shop supplies. Setup Table: Item Type | 
 **category** | **string** | Setup Table: Supply Category | 
 **group** | **string** | A supply group, used to categorize Supply Items, such as Electrical, Mechanical, Office Supplies. Setup Table: Item Group | 

### Return type

[**[]InventoryOperationsManagementApiListSupplyItemsItem**](InventoryOperationsManagementApiListSupplyItemsItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## InventoryOperationsManagementApiReceiveInventoryContainers

> InventoryOperationsManagementApiReceiveInventoryContainers(ctx, id).InventoryOperationsManagementApiReceiveInventoryContainersRequest(inventoryOperationsManagementApiReceiveInventoryContainersRequest).Execute()

Receive Inventory Containers



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
	id := "00000000-0000-0000-0000-000000000000" // string | The inventory receipt ID.
	inventoryOperationsManagementApiReceiveInventoryContainersRequest := *openapiclient.NewInventoryOperationsManagementApiReceiveInventoryContainersRequest() // InventoryOperationsManagementApiReceiveInventoryContainersRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiReceiveInventoryContainers(context.Background(), id).InventoryOperationsManagementApiReceiveInventoryContainersRequest(inventoryOperationsManagementApiReceiveInventoryContainersRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiReceiveInventoryContainers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The inventory receipt ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiInventoryOperationsManagementApiReceiveInventoryContainersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **inventoryOperationsManagementApiReceiveInventoryContainersRequest** | [**InventoryOperationsManagementApiReceiveInventoryContainersRequest**](InventoryOperationsManagementApiReceiveInventoryContainersRequest.md) |  | 

### Return type

 (empty response body)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## InventoryOperationsManagementApiRetireContainer

> InventoryOperationsManagementApiRetireContainer(ctx, serialNo).InventoryOperationsManagementApiRetireContainerRequest(inventoryOperationsManagementApiRetireContainerRequest).Execute()

Retire Container



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
	serialNo := "string" // string | The container serial no.
	inventoryOperationsManagementApiRetireContainerRequest := *openapiclient.NewInventoryOperationsManagementApiRetireContainerRequest() // InventoryOperationsManagementApiRetireContainerRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiRetireContainer(context.Background(), serialNo).InventoryOperationsManagementApiRetireContainerRequest(inventoryOperationsManagementApiRetireContainerRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiRetireContainer``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serialNo** | **string** | The container serial no. | 

### Other Parameters

Other parameters are passed through a pointer to a apiInventoryOperationsManagementApiRetireContainerRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **inventoryOperationsManagementApiRetireContainerRequest** | [**InventoryOperationsManagementApiRetireContainerRequest**](InventoryOperationsManagementApiRetireContainerRequest.md) |  | 

### Return type

 (empty response body)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## InventoryOperationsManagementApiScrapContainer

> InventoryOperationsManagementApiScrapContainer(ctx, serialNo).InventoryOperationsManagementApiScrapContainerRequest(inventoryOperationsManagementApiScrapContainerRequest).Execute()

Scrap Container



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
	serialNo := "string" // string | The container serial no.
	inventoryOperationsManagementApiScrapContainerRequest := *openapiclient.NewInventoryOperationsManagementApiScrapContainerRequest() // InventoryOperationsManagementApiScrapContainerRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiScrapContainer(context.Background(), serialNo).InventoryOperationsManagementApiScrapContainerRequest(inventoryOperationsManagementApiScrapContainerRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiScrapContainer``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serialNo** | **string** | The container serial no. | 

### Other Parameters

Other parameters are passed through a pointer to a apiInventoryOperationsManagementApiScrapContainerRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **inventoryOperationsManagementApiScrapContainerRequest** | [**InventoryOperationsManagementApiScrapContainerRequest**](InventoryOperationsManagementApiScrapContainerRequest.md) |  | 

### Return type

 (empty response body)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## InventoryOperationsManagementApiShipInventory

> InventoryOperationsManagementApiShipInventory202Response InventoryOperationsManagementApiShipInventory(ctx, id).Execute()

Ship Inventory



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
	id := "00000000-0000-0000-0000-000000000000" // string | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. The Inventory Shipment Resource ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiShipInventory(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiShipInventory``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `InventoryOperationsManagementApiShipInventory`: InventoryOperationsManagementApiShipInventory202Response
	fmt.Fprintf(os.Stdout, "Response from `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiShipInventory`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. The Inventory Shipment Resource ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiInventoryOperationsManagementApiShipInventoryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**InventoryOperationsManagementApiShipInventory202Response**](InventoryOperationsManagementApiShipInventory202Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## InventoryOperationsManagementApiStageInventory

> InventoryOperationsManagementApiStageInventory202Response InventoryOperationsManagementApiStageInventory(ctx, id).InventoryOperationsManagementApiStageInventoryRequest(inventoryOperationsManagementApiStageInventoryRequest).Execute()

Stage Inventory



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
	id := "00000000-0000-0000-0000-000000000000" // string | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. The Inventory Shipment Resource ID.
	inventoryOperationsManagementApiStageInventoryRequest := *openapiclient.NewInventoryOperationsManagementApiStageInventoryRequest() // InventoryOperationsManagementApiStageInventoryRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiStageInventory(context.Background(), id).InventoryOperationsManagementApiStageInventoryRequest(inventoryOperationsManagementApiStageInventoryRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiStageInventory``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `InventoryOperationsManagementApiStageInventory`: InventoryOperationsManagementApiStageInventory202Response
	fmt.Fprintf(os.Stdout, "Response from `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiStageInventory`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. The Inventory Shipment Resource ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiInventoryOperationsManagementApiStageInventoryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **inventoryOperationsManagementApiStageInventoryRequest** | [**InventoryOperationsManagementApiStageInventoryRequest**](InventoryOperationsManagementApiStageInventoryRequest.md) |  | 

### Return type

[**InventoryOperationsManagementApiStageInventory202Response**](InventoryOperationsManagementApiStageInventory202Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## InventoryOperationsManagementApiUnshipInventory

> InventoryOperationsManagementApiUnshipInventory202Response InventoryOperationsManagementApiUnshipInventory(ctx, id).Execute()

Unship Inventory



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
	id := "00000000-0000-0000-0000-000000000000" // string | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. The Inventory Shipment Resource ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiUnshipInventory(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiUnshipInventory``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `InventoryOperationsManagementApiUnshipInventory`: InventoryOperationsManagementApiUnshipInventory202Response
	fmt.Fprintf(os.Stdout, "Response from `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiUnshipInventory`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. The Inventory Shipment Resource ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiInventoryOperationsManagementApiUnshipInventoryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**InventoryOperationsManagementApiUnshipInventory202Response**](InventoryOperationsManagementApiUnshipInventory202Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## InventoryOperationsManagementApiUnstageInventory

> InventoryOperationsManagementApiUnstageInventory202Response InventoryOperationsManagementApiUnstageInventory(ctx, id).InventoryOperationsManagementApiUnstageInventoryRequest(inventoryOperationsManagementApiUnstageInventoryRequest).Execute()

Unstage Inventory



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
	id := "00000000-0000-0000-0000-000000000000" // string | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. The Inventory Shipment Resource ID.
	inventoryOperationsManagementApiUnstageInventoryRequest := *openapiclient.NewInventoryOperationsManagementApiUnstageInventoryRequest() // InventoryOperationsManagementApiUnstageInventoryRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiUnstageInventory(context.Background(), id).InventoryOperationsManagementApiUnstageInventoryRequest(inventoryOperationsManagementApiUnstageInventoryRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiUnstageInventory``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `InventoryOperationsManagementApiUnstageInventory`: InventoryOperationsManagementApiUnstageInventory202Response
	fmt.Fprintf(os.Stdout, "Response from `InventoryOperationsManagementAPIAPI.InventoryOperationsManagementApiUnstageInventory`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. The Inventory Shipment Resource ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiInventoryOperationsManagementApiUnstageInventoryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **inventoryOperationsManagementApiUnstageInventoryRequest** | [**InventoryOperationsManagementApiUnstageInventoryRequest**](InventoryOperationsManagementApiUnstageInventoryRequest.md) |  | 

### Return type

[**InventoryOperationsManagementApiUnstageInventory202Response**](InventoryOperationsManagementApiUnstageInventory202Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

