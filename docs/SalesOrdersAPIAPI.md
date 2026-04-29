# \SalesOrdersAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SalesOrdersApiCreateCustomerPurchaseOrder**](SalesOrdersAPIAPI.md#SalesOrdersApiCreateCustomerPurchaseOrder) | **Post** /sales/v1/orders | Create Customer Purchase Order
[**SalesOrdersApiCreateOrderLine**](SalesOrdersAPIAPI.md#SalesOrdersApiCreateOrderLine) | **Post** /sales/v1/orders/{id}/lines | Create Order Line
[**SalesOrdersApiCreateSalesOrderLineApprovedShipTo**](SalesOrdersAPIAPI.md#SalesOrdersApiCreateSalesOrderLineApprovedShipTo) | **Post** /sales/v1/orders/{id}/lines/{lineId}/approved-ship-tos | Create Sales Order Line Approved Ship To
[**SalesOrdersApiCreateSalesOrderLinePrice**](SalesOrdersAPIAPI.md#SalesOrdersApiCreateSalesOrderLinePrice) | **Post** /sales/v1/orders/{id}/lines/{lineId}/prices | Create Sales Order Line Price
[**SalesOrdersApiGetSalesOrder**](SalesOrdersAPIAPI.md#SalesOrdersApiGetSalesOrder) | **Get** /sales/v1/orders/{id} | Get Sales Order
[**SalesOrdersApiGetSalesOrderLine**](SalesOrdersAPIAPI.md#SalesOrdersApiGetSalesOrderLine) | **Get** /sales/v1/orders/{id}/lines/{lineId} | Get Sales Order Line
[**SalesOrdersApiGetSalesOrderLinePrice**](SalesOrdersAPIAPI.md#SalesOrdersApiGetSalesOrderLinePrice) | **Get** /sales/v1/orders/{id}/lines/{lineId}/prices/{priceId} | Get Sales Order Line Price
[**SalesOrdersApiListOrderLinePriceAdjustments**](SalesOrdersAPIAPI.md#SalesOrdersApiListOrderLinePriceAdjustments) | **Get** /sales/v1/orders/{id}/lines/{lineId}/price-adjustments | List Order Line Price Adjustments
[**SalesOrdersApiListOrderPriceAdjustments**](SalesOrdersAPIAPI.md#SalesOrdersApiListOrderPriceAdjustments) | **Get** /sales/v1/orders/{id}/price-adjustments | List Order Price Adjustments
[**SalesOrdersApiListSalesOrderLineApprovedShipTos**](SalesOrdersAPIAPI.md#SalesOrdersApiListSalesOrderLineApprovedShipTos) | **Get** /sales/v1/orders/{id}/lines/{lineId}/approved-ship-tos | List Sales Order Line Approved Ship Tos
[**SalesOrdersApiListSalesOrderLinePrices**](SalesOrdersAPIAPI.md#SalesOrdersApiListSalesOrderLinePrices) | **Get** /sales/v1/orders/{id}/lines/{lineId}/prices | List Sales Order Line Prices
[**SalesOrdersApiListSalesOrderLines**](SalesOrdersAPIAPI.md#SalesOrdersApiListSalesOrderLines) | **Get** /sales/v1/orders/{id}/lines | List Sales Order Lines
[**SalesOrdersApiListSalesOrders**](SalesOrdersAPIAPI.md#SalesOrdersApiListSalesOrders) | **Get** /sales/v1/orders | List Sales Orders
[**SalesOrdersApiUpdateCustomerPurchaseOrder**](SalesOrdersAPIAPI.md#SalesOrdersApiUpdateCustomerPurchaseOrder) | **Put** /sales/v1/orders/{id} | Update Customer Purchase Order
[**SalesOrdersApiUpdateOrderLine**](SalesOrdersAPIAPI.md#SalesOrdersApiUpdateOrderLine) | **Put** /sales/v1/orders/{id}/line/{lineId} | Update Order Line
[**SalesOrdersApiUpdateSalesOrderLinePrice**](SalesOrdersAPIAPI.md#SalesOrdersApiUpdateSalesOrderLinePrice) | **Put** /sales/v1/orders/{id}/lines/{lineId}/prices/{priceId} | Update Sales Order Line Price



## SalesOrdersApiCreateCustomerPurchaseOrder

> SalesOrdersApiCreateCustomerPurchaseOrder201Response SalesOrdersApiCreateCustomerPurchaseOrder(ctx).SalesOrdersApiCreateCustomerPurchaseOrderRequest(salesOrdersApiCreateCustomerPurchaseOrderRequest).Execute()

Create Customer Purchase Order



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
	salesOrdersApiCreateCustomerPurchaseOrderRequest := *openapiclient.NewSalesOrdersApiCreateCustomerPurchaseOrderRequest() // SalesOrdersApiCreateCustomerPurchaseOrderRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SalesOrdersAPIAPI.SalesOrdersApiCreateCustomerPurchaseOrder(context.Background()).SalesOrdersApiCreateCustomerPurchaseOrderRequest(salesOrdersApiCreateCustomerPurchaseOrderRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SalesOrdersAPIAPI.SalesOrdersApiCreateCustomerPurchaseOrder``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SalesOrdersApiCreateCustomerPurchaseOrder`: SalesOrdersApiCreateCustomerPurchaseOrder201Response
	fmt.Fprintf(os.Stdout, "Response from `SalesOrdersAPIAPI.SalesOrdersApiCreateCustomerPurchaseOrder`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSalesOrdersApiCreateCustomerPurchaseOrderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **salesOrdersApiCreateCustomerPurchaseOrderRequest** | [**SalesOrdersApiCreateCustomerPurchaseOrderRequest**](SalesOrdersApiCreateCustomerPurchaseOrderRequest.md) |  | 

### Return type

[**SalesOrdersApiCreateCustomerPurchaseOrder201Response**](SalesOrdersApiCreateCustomerPurchaseOrder201Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SalesOrdersApiCreateOrderLine

> SalesOrdersApiCreateOrderLine201Response SalesOrdersApiCreateOrderLine(ctx, id).SalesOrdersApiCreateOrderLineRequest(salesOrdersApiCreateOrderLineRequest).Execute()

Create Order Line



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
	id := "00000000-0000-0000-0000-000000000000" // string | The order id.
	salesOrdersApiCreateOrderLineRequest := *openapiclient.NewSalesOrdersApiCreateOrderLineRequest() // SalesOrdersApiCreateOrderLineRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SalesOrdersAPIAPI.SalesOrdersApiCreateOrderLine(context.Background(), id).SalesOrdersApiCreateOrderLineRequest(salesOrdersApiCreateOrderLineRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SalesOrdersAPIAPI.SalesOrdersApiCreateOrderLine``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SalesOrdersApiCreateOrderLine`: SalesOrdersApiCreateOrderLine201Response
	fmt.Fprintf(os.Stdout, "Response from `SalesOrdersAPIAPI.SalesOrdersApiCreateOrderLine`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The order id. | 

### Other Parameters

Other parameters are passed through a pointer to a apiSalesOrdersApiCreateOrderLineRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **salesOrdersApiCreateOrderLineRequest** | [**SalesOrdersApiCreateOrderLineRequest**](SalesOrdersApiCreateOrderLineRequest.md) |  | 

### Return type

[**SalesOrdersApiCreateOrderLine201Response**](SalesOrdersApiCreateOrderLine201Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SalesOrdersApiCreateSalesOrderLineApprovedShipTo

> SalesOrdersApiCreateSalesOrderLineApprovedShipTo201Response SalesOrdersApiCreateSalesOrderLineApprovedShipTo(ctx, id, lineId).SalesOrdersApiCreateSalesOrderLineApprovedShipToRequest(salesOrdersApiCreateSalesOrderLineApprovedShipToRequest).Execute()

Create Sales Order Line Approved Ship To



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
	id := "00000000-0000-0000-0000-000000000000" // string | The order id.
	lineId := "00000000-0000-0000-0000-000000000000" // string | The order line id.
	salesOrdersApiCreateSalesOrderLineApprovedShipToRequest := *openapiclient.NewSalesOrdersApiCreateSalesOrderLineApprovedShipToRequest() // SalesOrdersApiCreateSalesOrderLineApprovedShipToRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SalesOrdersAPIAPI.SalesOrdersApiCreateSalesOrderLineApprovedShipTo(context.Background(), id, lineId).SalesOrdersApiCreateSalesOrderLineApprovedShipToRequest(salesOrdersApiCreateSalesOrderLineApprovedShipToRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SalesOrdersAPIAPI.SalesOrdersApiCreateSalesOrderLineApprovedShipTo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SalesOrdersApiCreateSalesOrderLineApprovedShipTo`: SalesOrdersApiCreateSalesOrderLineApprovedShipTo201Response
	fmt.Fprintf(os.Stdout, "Response from `SalesOrdersAPIAPI.SalesOrdersApiCreateSalesOrderLineApprovedShipTo`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The order id. | 
**lineId** | **string** | The order line id. | 

### Other Parameters

Other parameters are passed through a pointer to a apiSalesOrdersApiCreateSalesOrderLineApprovedShipToRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **salesOrdersApiCreateSalesOrderLineApprovedShipToRequest** | [**SalesOrdersApiCreateSalesOrderLineApprovedShipToRequest**](SalesOrdersApiCreateSalesOrderLineApprovedShipToRequest.md) |  | 

### Return type

[**SalesOrdersApiCreateSalesOrderLineApprovedShipTo201Response**](SalesOrdersApiCreateSalesOrderLineApprovedShipTo201Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SalesOrdersApiCreateSalesOrderLinePrice

> SalesOrdersApiCreateSalesOrderLinePrice201Response SalesOrdersApiCreateSalesOrderLinePrice(ctx, id, lineId).SalesOrdersApiCreateSalesOrderLinePriceRequest(salesOrdersApiCreateSalesOrderLinePriceRequest).Execute()

Create Sales Order Line Price



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
	id := "00000000-0000-0000-0000-000000000000" // string | The order Id.
	lineId := "00000000-0000-0000-0000-000000000000" // string | The order line Id.
	salesOrdersApiCreateSalesOrderLinePriceRequest := *openapiclient.NewSalesOrdersApiCreateSalesOrderLinePriceRequest() // SalesOrdersApiCreateSalesOrderLinePriceRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SalesOrdersAPIAPI.SalesOrdersApiCreateSalesOrderLinePrice(context.Background(), id, lineId).SalesOrdersApiCreateSalesOrderLinePriceRequest(salesOrdersApiCreateSalesOrderLinePriceRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SalesOrdersAPIAPI.SalesOrdersApiCreateSalesOrderLinePrice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SalesOrdersApiCreateSalesOrderLinePrice`: SalesOrdersApiCreateSalesOrderLinePrice201Response
	fmt.Fprintf(os.Stdout, "Response from `SalesOrdersAPIAPI.SalesOrdersApiCreateSalesOrderLinePrice`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The order Id. | 
**lineId** | **string** | The order line Id. | 

### Other Parameters

Other parameters are passed through a pointer to a apiSalesOrdersApiCreateSalesOrderLinePriceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **salesOrdersApiCreateSalesOrderLinePriceRequest** | [**SalesOrdersApiCreateSalesOrderLinePriceRequest**](SalesOrdersApiCreateSalesOrderLinePriceRequest.md) |  | 

### Return type

[**SalesOrdersApiCreateSalesOrderLinePrice201Response**](SalesOrdersApiCreateSalesOrderLinePrice201Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SalesOrdersApiGetSalesOrder

> SalesOrdersApiGetSalesOrderResponse SalesOrdersApiGetSalesOrder(ctx, id).Execute()

Get Sales Order



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
	id := "00000000-0000-0000-0000-000000000000" // string | Sales order ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SalesOrdersAPIAPI.SalesOrdersApiGetSalesOrder(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SalesOrdersAPIAPI.SalesOrdersApiGetSalesOrder``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SalesOrdersApiGetSalesOrder`: SalesOrdersApiGetSalesOrderResponse
	fmt.Fprintf(os.Stdout, "Response from `SalesOrdersAPIAPI.SalesOrdersApiGetSalesOrder`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Sales order ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiSalesOrdersApiGetSalesOrderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**SalesOrdersApiGetSalesOrderResponse**](SalesOrdersApiGetSalesOrderResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SalesOrdersApiGetSalesOrderLine

> SalesOrdersApiGetSalesOrderLineResponse SalesOrdersApiGetSalesOrderLine(ctx, id, lineId).Execute()

Get Sales Order Line



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
	id := "00000000-0000-0000-0000-000000000000" // string | The order id.
	lineId := "00000000-0000-0000-0000-000000000000" // string | The order line id.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SalesOrdersAPIAPI.SalesOrdersApiGetSalesOrderLine(context.Background(), id, lineId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SalesOrdersAPIAPI.SalesOrdersApiGetSalesOrderLine``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SalesOrdersApiGetSalesOrderLine`: SalesOrdersApiGetSalesOrderLineResponse
	fmt.Fprintf(os.Stdout, "Response from `SalesOrdersAPIAPI.SalesOrdersApiGetSalesOrderLine`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The order id. | 
**lineId** | **string** | The order line id. | 

### Other Parameters

Other parameters are passed through a pointer to a apiSalesOrdersApiGetSalesOrderLineRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**SalesOrdersApiGetSalesOrderLineResponse**](SalesOrdersApiGetSalesOrderLineResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SalesOrdersApiGetSalesOrderLinePrice

> SalesOrdersApiGetSalesOrderLinePriceResponse SalesOrdersApiGetSalesOrderLinePrice(ctx, id, lineId, priceId).Execute()

Get Sales Order Line Price



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
	id := "00000000-0000-0000-0000-000000000000" // string | The order id.
	lineId := "00000000-0000-0000-0000-000000000000" // string | The line id.
	priceId := "00000000-0000-0000-0000-000000000000" // string | The order line price id.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SalesOrdersAPIAPI.SalesOrdersApiGetSalesOrderLinePrice(context.Background(), id, lineId, priceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SalesOrdersAPIAPI.SalesOrdersApiGetSalesOrderLinePrice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SalesOrdersApiGetSalesOrderLinePrice`: SalesOrdersApiGetSalesOrderLinePriceResponse
	fmt.Fprintf(os.Stdout, "Response from `SalesOrdersAPIAPI.SalesOrdersApiGetSalesOrderLinePrice`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The order id. | 
**lineId** | **string** | The line id. | 
**priceId** | **string** | The order line price id. | 

### Other Parameters

Other parameters are passed through a pointer to a apiSalesOrdersApiGetSalesOrderLinePriceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------




### Return type

[**SalesOrdersApiGetSalesOrderLinePriceResponse**](SalesOrdersApiGetSalesOrderLinePriceResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SalesOrdersApiListOrderLinePriceAdjustments

> []SalesOrdersApiListOrderLinePriceAdjustmentsItem SalesOrdersApiListOrderLinePriceAdjustments(ctx, id, lineId).Execute()

List Order Line Price Adjustments



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
	id := "00000000-0000-0000-0000-000000000000" // string | The order id.
	lineId := "00000000-0000-0000-0000-000000000000" // string | The order line id.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SalesOrdersAPIAPI.SalesOrdersApiListOrderLinePriceAdjustments(context.Background(), id, lineId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SalesOrdersAPIAPI.SalesOrdersApiListOrderLinePriceAdjustments``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SalesOrdersApiListOrderLinePriceAdjustments`: []SalesOrdersApiListOrderLinePriceAdjustmentsItem
	fmt.Fprintf(os.Stdout, "Response from `SalesOrdersAPIAPI.SalesOrdersApiListOrderLinePriceAdjustments`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The order id. | 
**lineId** | **string** | The order line id. | 

### Other Parameters

Other parameters are passed through a pointer to a apiSalesOrdersApiListOrderLinePriceAdjustmentsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**[]SalesOrdersApiListOrderLinePriceAdjustmentsItem**](SalesOrdersApiListOrderLinePriceAdjustmentsItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SalesOrdersApiListOrderPriceAdjustments

> []SalesOrdersApiListOrderPriceAdjustmentsItem SalesOrdersApiListOrderPriceAdjustments(ctx, id).Execute()

List Order Price Adjustments



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
	id := "00000000-0000-0000-0000-000000000000" // string | The order id.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SalesOrdersAPIAPI.SalesOrdersApiListOrderPriceAdjustments(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SalesOrdersAPIAPI.SalesOrdersApiListOrderPriceAdjustments``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SalesOrdersApiListOrderPriceAdjustments`: []SalesOrdersApiListOrderPriceAdjustmentsItem
	fmt.Fprintf(os.Stdout, "Response from `SalesOrdersAPIAPI.SalesOrdersApiListOrderPriceAdjustments`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The order id. | 

### Other Parameters

Other parameters are passed through a pointer to a apiSalesOrdersApiListOrderPriceAdjustmentsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]SalesOrdersApiListOrderPriceAdjustmentsItem**](SalesOrdersApiListOrderPriceAdjustmentsItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SalesOrdersApiListSalesOrderLineApprovedShipTos

> []SalesOrdersApiListSalesOrderLineApprovedShipTosItem SalesOrdersApiListSalesOrderLineApprovedShipTos(ctx, id, lineId).ShipToAddressId(shipToAddressId).DefaultShipFromId(defaultShipFromId).DefaultShipFromCode(defaultShipFromCode).Execute()

List Sales Order Line Approved Ship Tos



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
	id := "00000000-0000-0000-0000-000000000000" // string | The order id.
	lineId := "00000000-0000-0000-0000-000000000000" // string | The order line id.
	shipToAddressId := "00000000-0000-0000-0000-000000000000" // string | The ID of the ship to customer address record assigned to an order line. (optional)
	defaultShipFromId := "00000000-0000-0000-0000-000000000000" // string | The ID of the default building from which shipments will be sent. (optional)
	defaultShipFromCode := "string" // string | The building code from which the shipment will be shipped from by default. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SalesOrdersAPIAPI.SalesOrdersApiListSalesOrderLineApprovedShipTos(context.Background(), id, lineId).ShipToAddressId(shipToAddressId).DefaultShipFromId(defaultShipFromId).DefaultShipFromCode(defaultShipFromCode).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SalesOrdersAPIAPI.SalesOrdersApiListSalesOrderLineApprovedShipTos``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SalesOrdersApiListSalesOrderLineApprovedShipTos`: []SalesOrdersApiListSalesOrderLineApprovedShipTosItem
	fmt.Fprintf(os.Stdout, "Response from `SalesOrdersAPIAPI.SalesOrdersApiListSalesOrderLineApprovedShipTos`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The order id. | 
**lineId** | **string** | The order line id. | 

### Other Parameters

Other parameters are passed through a pointer to a apiSalesOrdersApiListSalesOrderLineApprovedShipTosRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **shipToAddressId** | **string** | The ID of the ship to customer address record assigned to an order line. | 
 **defaultShipFromId** | **string** | The ID of the default building from which shipments will be sent. | 
 **defaultShipFromCode** | **string** | The building code from which the shipment will be shipped from by default. | 

### Return type

[**[]SalesOrdersApiListSalesOrderLineApprovedShipTosItem**](SalesOrdersApiListSalesOrderLineApprovedShipTosItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SalesOrdersApiListSalesOrderLinePrices

> []SalesOrdersApiListSalesOrderLinePricesItem SalesOrdersApiListSalesOrderLinePrices(ctx, id, lineId).Execute()

List Sales Order Line Prices



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
	id := "00000000-0000-0000-0000-000000000000" // string | The order id.
	lineId := "00000000-0000-0000-0000-000000000000" // string | The order line id.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SalesOrdersAPIAPI.SalesOrdersApiListSalesOrderLinePrices(context.Background(), id, lineId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SalesOrdersAPIAPI.SalesOrdersApiListSalesOrderLinePrices``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SalesOrdersApiListSalesOrderLinePrices`: []SalesOrdersApiListSalesOrderLinePricesItem
	fmt.Fprintf(os.Stdout, "Response from `SalesOrdersAPIAPI.SalesOrdersApiListSalesOrderLinePrices`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The order id. | 
**lineId** | **string** | The order line id. | 

### Other Parameters

Other parameters are passed through a pointer to a apiSalesOrdersApiListSalesOrderLinePricesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**[]SalesOrdersApiListSalesOrderLinePricesItem**](SalesOrdersApiListSalesOrderLinePricesItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SalesOrdersApiListSalesOrderLines

> []SalesOrdersApiListSalesOrderLinesItem SalesOrdersApiListSalesOrderLines(ctx, id).Execute()

List Sales Order Lines



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
	id := "00000000-0000-0000-0000-000000000000" // string | The order id.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SalesOrdersAPIAPI.SalesOrdersApiListSalesOrderLines(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SalesOrdersAPIAPI.SalesOrdersApiListSalesOrderLines``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SalesOrdersApiListSalesOrderLines`: []SalesOrdersApiListSalesOrderLinesItem
	fmt.Fprintf(os.Stdout, "Response from `SalesOrdersAPIAPI.SalesOrdersApiListSalesOrderLines`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The order id. | 

### Other Parameters

Other parameters are passed through a pointer to a apiSalesOrdersApiListSalesOrderLinesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]SalesOrdersApiListSalesOrderLinesItem**](SalesOrdersApiListSalesOrderLinesItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SalesOrdersApiListSalesOrders

> []SalesOrdersApiListSalesOrdersItem SalesOrdersApiListSalesOrders(ctx).Id(id).CustomerId(customerId).OrderNumber(orderNumber).PoNumber(poNumber).PoNumberRevisionDateBegin(poNumberRevisionDateBegin).PoNumberRevisionDateEnd(poNumberRevisionDateEnd).Status(status).Type_(type_).Category(category).OrderDateBegin(orderDateBegin).OrderDateEnd(orderDateEnd).ExpirationDateBegin(expirationDateBegin).ExpirationDateEnd(expirationDateEnd).Terms(terms).IncoTerms(incoTerms).Fob(fob).FreightTerms(freightTerms).InsideSalesId(insideSalesId).OutsideSalesId(outsideSalesId).CreatedById(createdById).CreatedDateBegin(createdDateBegin).CreatedDateEnd(createdDateEnd).ModifiedById(modifiedById).ModifiedByDateBegin(modifiedByDateBegin).ModifiedByDateEnd(modifiedByDateEnd).Execute()

List Sales Orders



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
	id := []string{"00000000-0000-0000-0000-000000000000"} // []string | A unique identifier for the sales order. This will be automatically generated if omitted from the request. (optional)
	customerId := "00000000-0000-0000-0000-000000000000" // string | The ID of the customer associated with the sales order. (optional)
	orderNumber := "string" // string | The internal order number generated by Plex that corresponds to a given sales order. (Applicable to two-tier ordering only.) (optional)
	poNumber := "string" // string | The customer's purchase order number on the sales order. (optional)
	poNumberRevisionDateBegin := time.Now() // time.Time | The beginning date used to return order records with revisions during a time frame, if applicable. (optional)
	poNumberRevisionDateEnd := time.Now() // time.Time | The end date used to return order records with revisions within a time frame, if applicable. (optional)
	status := []string{"string"} // []string | The purchase order status. (optional)
	type_ := []string{"string"} // []string | The purchase order type. (optional)
	category := "string" // string | The purchase order category. (optional)
	orderDateBegin := time.Now() // time.Time | The beginning date used to return orders that were placed within a time frame. (optional)
	orderDateEnd := time.Now() // time.Time | The end date used to return orders that were placed within a time frame. (optional)
	expirationDateBegin := time.Now() // time.Time | The beginning date used to return purchase orders with an expiration date within a time frame. (optional)
	expirationDateEnd := time.Now() // time.Time | The end date used to return purchase orders with an expiration date within a time frame. (optional)
	terms := "string" // string | The order's payment terms. (optional)
	incoTerms := "string" // string | International Commercial (INCO) Terms applied to the sales order. (optional)
	fob := "string" // string | The Freight on Board terms of the order. (optional)
	freightTerms := "string" // string | The freight terms applied to the order. (optional)
	insideSalesId := "00000000-0000-0000-0000-000000000000" // string | The ID of the inside salesperson associated with the order. (optional)
	outsideSalesId := "00000000-0000-0000-0000-000000000000" // string | The ID of the outside salesperson associated with the order. (optional)
	createdById := "00000000-0000-0000-0000-000000000000" // string | The ID of the user who created the record. (optional)
	createdDateBegin := time.Now() // time.Time | The beginning date used to return orders that were created within a time frame. (optional)
	createdDateEnd := time.Now() // time.Time | The end date used to return orders that were created within a time frame. (optional)
	modifiedById := "00000000-0000-0000-0000-000000000000" // string | The ID of the user who last modified the record. (optional)
	modifiedByDateBegin := time.Now() // time.Time | The beginning date used to return orders that were last modified within a time frame. (optional)
	modifiedByDateEnd := time.Now() // time.Time | The end date used to return orders that were last modified within a time frame. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SalesOrdersAPIAPI.SalesOrdersApiListSalesOrders(context.Background()).Id(id).CustomerId(customerId).OrderNumber(orderNumber).PoNumber(poNumber).PoNumberRevisionDateBegin(poNumberRevisionDateBegin).PoNumberRevisionDateEnd(poNumberRevisionDateEnd).Status(status).Type_(type_).Category(category).OrderDateBegin(orderDateBegin).OrderDateEnd(orderDateEnd).ExpirationDateBegin(expirationDateBegin).ExpirationDateEnd(expirationDateEnd).Terms(terms).IncoTerms(incoTerms).Fob(fob).FreightTerms(freightTerms).InsideSalesId(insideSalesId).OutsideSalesId(outsideSalesId).CreatedById(createdById).CreatedDateBegin(createdDateBegin).CreatedDateEnd(createdDateEnd).ModifiedById(modifiedById).ModifiedByDateBegin(modifiedByDateBegin).ModifiedByDateEnd(modifiedByDateEnd).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SalesOrdersAPIAPI.SalesOrdersApiListSalesOrders``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SalesOrdersApiListSalesOrders`: []SalesOrdersApiListSalesOrdersItem
	fmt.Fprintf(os.Stdout, "Response from `SalesOrdersAPIAPI.SalesOrdersApiListSalesOrders`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSalesOrdersApiListSalesOrdersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **[]string** | A unique identifier for the sales order. This will be automatically generated if omitted from the request. | 
 **customerId** | **string** | The ID of the customer associated with the sales order. | 
 **orderNumber** | **string** | The internal order number generated by Plex that corresponds to a given sales order. (Applicable to two-tier ordering only.) | 
 **poNumber** | **string** | The customer&#39;s purchase order number on the sales order. | 
 **poNumberRevisionDateBegin** | **time.Time** | The beginning date used to return order records with revisions during a time frame, if applicable. | 
 **poNumberRevisionDateEnd** | **time.Time** | The end date used to return order records with revisions within a time frame, if applicable. | 
 **status** | **[]string** | The purchase order status. | 
 **type_** | **[]string** | The purchase order type. | 
 **category** | **string** | The purchase order category. | 
 **orderDateBegin** | **time.Time** | The beginning date used to return orders that were placed within a time frame. | 
 **orderDateEnd** | **time.Time** | The end date used to return orders that were placed within a time frame. | 
 **expirationDateBegin** | **time.Time** | The beginning date used to return purchase orders with an expiration date within a time frame. | 
 **expirationDateEnd** | **time.Time** | The end date used to return purchase orders with an expiration date within a time frame. | 
 **terms** | **string** | The order&#39;s payment terms. | 
 **incoTerms** | **string** | International Commercial (INCO) Terms applied to the sales order. | 
 **fob** | **string** | The Freight on Board terms of the order. | 
 **freightTerms** | **string** | The freight terms applied to the order. | 
 **insideSalesId** | **string** | The ID of the inside salesperson associated with the order. | 
 **outsideSalesId** | **string** | The ID of the outside salesperson associated with the order. | 
 **createdById** | **string** | The ID of the user who created the record. | 
 **createdDateBegin** | **time.Time** | The beginning date used to return orders that were created within a time frame. | 
 **createdDateEnd** | **time.Time** | The end date used to return orders that were created within a time frame. | 
 **modifiedById** | **string** | The ID of the user who last modified the record. | 
 **modifiedByDateBegin** | **time.Time** | The beginning date used to return orders that were last modified within a time frame. | 
 **modifiedByDateEnd** | **time.Time** | The end date used to return orders that were last modified within a time frame. | 

### Return type

[**[]SalesOrdersApiListSalesOrdersItem**](SalesOrdersApiListSalesOrdersItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SalesOrdersApiUpdateCustomerPurchaseOrder

> SalesOrdersApiUpdateCustomerPurchaseOrderResponse SalesOrdersApiUpdateCustomerPurchaseOrder(ctx, id).SalesOrdersApiUpdateCustomerPurchaseOrderRequest(salesOrdersApiUpdateCustomerPurchaseOrderRequest).Execute()

Update Customer Purchase Order



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
	id := "00000000-0000-0000-0000-000000000000" // string | The id of customer purchase order to be updated.
	salesOrdersApiUpdateCustomerPurchaseOrderRequest := *openapiclient.NewSalesOrdersApiUpdateCustomerPurchaseOrderRequest() // SalesOrdersApiUpdateCustomerPurchaseOrderRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SalesOrdersAPIAPI.SalesOrdersApiUpdateCustomerPurchaseOrder(context.Background(), id).SalesOrdersApiUpdateCustomerPurchaseOrderRequest(salesOrdersApiUpdateCustomerPurchaseOrderRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SalesOrdersAPIAPI.SalesOrdersApiUpdateCustomerPurchaseOrder``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SalesOrdersApiUpdateCustomerPurchaseOrder`: SalesOrdersApiUpdateCustomerPurchaseOrderResponse
	fmt.Fprintf(os.Stdout, "Response from `SalesOrdersAPIAPI.SalesOrdersApiUpdateCustomerPurchaseOrder`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The id of customer purchase order to be updated. | 

### Other Parameters

Other parameters are passed through a pointer to a apiSalesOrdersApiUpdateCustomerPurchaseOrderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **salesOrdersApiUpdateCustomerPurchaseOrderRequest** | [**SalesOrdersApiUpdateCustomerPurchaseOrderRequest**](SalesOrdersApiUpdateCustomerPurchaseOrderRequest.md) |  | 

### Return type

[**SalesOrdersApiUpdateCustomerPurchaseOrderResponse**](SalesOrdersApiUpdateCustomerPurchaseOrderResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SalesOrdersApiUpdateOrderLine

> SalesOrdersApiUpdateOrderLineResponse SalesOrdersApiUpdateOrderLine(ctx, id, lineId).SalesOrdersApiUpdateOrderLineRequest(salesOrdersApiUpdateOrderLineRequest).Execute()

Update Order Line



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
	id := "00000000-0000-0000-0000-000000000000" // string | The order id.
	lineId := "00000000-0000-0000-0000-000000000000" // string | The order line id.
	salesOrdersApiUpdateOrderLineRequest := *openapiclient.NewSalesOrdersApiUpdateOrderLineRequest() // SalesOrdersApiUpdateOrderLineRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SalesOrdersAPIAPI.SalesOrdersApiUpdateOrderLine(context.Background(), id, lineId).SalesOrdersApiUpdateOrderLineRequest(salesOrdersApiUpdateOrderLineRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SalesOrdersAPIAPI.SalesOrdersApiUpdateOrderLine``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SalesOrdersApiUpdateOrderLine`: SalesOrdersApiUpdateOrderLineResponse
	fmt.Fprintf(os.Stdout, "Response from `SalesOrdersAPIAPI.SalesOrdersApiUpdateOrderLine`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The order id. | 
**lineId** | **string** | The order line id. | 

### Other Parameters

Other parameters are passed through a pointer to a apiSalesOrdersApiUpdateOrderLineRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **salesOrdersApiUpdateOrderLineRequest** | [**SalesOrdersApiUpdateOrderLineRequest**](SalesOrdersApiUpdateOrderLineRequest.md) |  | 

### Return type

[**SalesOrdersApiUpdateOrderLineResponse**](SalesOrdersApiUpdateOrderLineResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SalesOrdersApiUpdateSalesOrderLinePrice

> SalesOrdersApiUpdateSalesOrderLinePriceResponse SalesOrdersApiUpdateSalesOrderLinePrice(ctx, id, lineId, priceId).SalesOrdersApiUpdateSalesOrderLinePriceRequest(salesOrdersApiUpdateSalesOrderLinePriceRequest).Execute()

Update Sales Order Line Price



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
	id := "00000000-0000-0000-0000-000000000000" // string | The order id.
	lineId := "00000000-0000-0000-0000-000000000000" // string | The order line id.
	priceId := "00000000-0000-0000-0000-000000000000" // string | The order line price id.
	salesOrdersApiUpdateSalesOrderLinePriceRequest := *openapiclient.NewSalesOrdersApiUpdateSalesOrderLinePriceRequest() // SalesOrdersApiUpdateSalesOrderLinePriceRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SalesOrdersAPIAPI.SalesOrdersApiUpdateSalesOrderLinePrice(context.Background(), id, lineId, priceId).SalesOrdersApiUpdateSalesOrderLinePriceRequest(salesOrdersApiUpdateSalesOrderLinePriceRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SalesOrdersAPIAPI.SalesOrdersApiUpdateSalesOrderLinePrice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SalesOrdersApiUpdateSalesOrderLinePrice`: SalesOrdersApiUpdateSalesOrderLinePriceResponse
	fmt.Fprintf(os.Stdout, "Response from `SalesOrdersAPIAPI.SalesOrdersApiUpdateSalesOrderLinePrice`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The order id. | 
**lineId** | **string** | The order line id. | 
**priceId** | **string** | The order line price id. | 

### Other Parameters

Other parameters are passed through a pointer to a apiSalesOrdersApiUpdateSalesOrderLinePriceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **salesOrdersApiUpdateSalesOrderLinePriceRequest** | [**SalesOrdersApiUpdateSalesOrderLinePriceRequest**](SalesOrdersApiUpdateSalesOrderLinePriceRequest.md) |  | 

### Return type

[**SalesOrdersApiUpdateSalesOrderLinePriceResponse**](SalesOrdersApiUpdateSalesOrderLinePriceResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

