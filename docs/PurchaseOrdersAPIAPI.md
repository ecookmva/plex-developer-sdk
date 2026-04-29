# \PurchaseOrdersAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**PurchaseOrdersApiGetLineItem**](PurchaseOrdersAPIAPI.md#PurchaseOrdersApiGetLineItem) | **Get** /purchasing/v1/purchase-orders/{id}/line-items/{lineItemId} | Get Line Item
[**PurchaseOrdersApiGetPurchaseOrder**](PurchaseOrdersAPIAPI.md#PurchaseOrdersApiGetPurchaseOrder) | **Get** /purchasing/v1/purchase-orders/{id} | Get Purchase Order
[**PurchaseOrdersApiListLineItems**](PurchaseOrdersAPIAPI.md#PurchaseOrdersApiListLineItems) | **Get** /purchasing/v1/purchase-orders/{poId}/line-items | List Line Items
[**PurchaseOrdersApiListPurchaseOrderPrices**](PurchaseOrdersAPIAPI.md#PurchaseOrdersApiListPurchaseOrderPrices) | **Get** /purchasing/v1/purchase-orders/{id}/line-items/{lineItemId}/prices | List Purchase Order Prices
[**PurchaseOrdersApiListPurchaseOrderStatuses**](PurchaseOrdersAPIAPI.md#PurchaseOrdersApiListPurchaseOrderStatuses) | **Get** /purchasing/v1/purchase-order-statuses | List Purchase Order Statuses
[**PurchaseOrdersApiListPurchaseOrderTypes**](PurchaseOrdersAPIAPI.md#PurchaseOrdersApiListPurchaseOrderTypes) | **Get** /purchasing/v1/purchase-order-types | List Purchase Order Types
[**PurchaseOrdersApiListPurchaseOrders**](PurchaseOrdersAPIAPI.md#PurchaseOrdersApiListPurchaseOrders) | **Get** /purchasing/v1/purchase-orders | List Purchase Orders



## PurchaseOrdersApiGetLineItem

> PurchaseOrdersApiGetLineItemResponse PurchaseOrdersApiGetLineItem(ctx, id, lineItemId).Execute()

Get Line Item



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
	id := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the purchase order.
	lineItemId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the line item.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PurchaseOrdersAPIAPI.PurchaseOrdersApiGetLineItem(context.Background(), id, lineItemId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PurchaseOrdersAPIAPI.PurchaseOrdersApiGetLineItem``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PurchaseOrdersApiGetLineItem`: PurchaseOrdersApiGetLineItemResponse
	fmt.Fprintf(os.Stdout, "Response from `PurchaseOrdersAPIAPI.PurchaseOrdersApiGetLineItem`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | A unique identifier for the purchase order. | 
**lineItemId** | **string** | A unique identifier for the line item. | 

### Other Parameters

Other parameters are passed through a pointer to a apiPurchaseOrdersApiGetLineItemRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**PurchaseOrdersApiGetLineItemResponse**](PurchaseOrdersApiGetLineItemResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PurchaseOrdersApiGetPurchaseOrder

> PurchaseOrdersApiGetPurchaseOrderResponse PurchaseOrdersApiGetPurchaseOrder(ctx, id).Execute()

Get Purchase Order



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
	id := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the purchase order.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PurchaseOrdersAPIAPI.PurchaseOrdersApiGetPurchaseOrder(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PurchaseOrdersAPIAPI.PurchaseOrdersApiGetPurchaseOrder``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PurchaseOrdersApiGetPurchaseOrder`: PurchaseOrdersApiGetPurchaseOrderResponse
	fmt.Fprintf(os.Stdout, "Response from `PurchaseOrdersAPIAPI.PurchaseOrdersApiGetPurchaseOrder`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | A unique identifier for the purchase order. | 

### Other Parameters

Other parameters are passed through a pointer to a apiPurchaseOrdersApiGetPurchaseOrderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**PurchaseOrdersApiGetPurchaseOrderResponse**](PurchaseOrdersApiGetPurchaseOrderResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PurchaseOrdersApiListLineItems

> []PurchaseOrdersApiListLineItemsItem PurchaseOrdersApiListLineItems(ctx, poId).Id(id).LineItemNumber(lineItemNumber).Status(status).Manufacturer(manufacturer).ManufacturerPartNumber(manufacturerPartNumber).SupplierPartNumber(supplierPartNumber).ItemId(itemId).PartId(partId).Building(building).Department(department).CreatedDateBegin(createdDateBegin).CreatedDateEnd(createdDateEnd).ModifiedById(modifiedById).ModifiedDateBegin(modifiedDateBegin).ModifiedDateEnd(modifiedDateEnd).Execute()

List Line Items



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
	poId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the purchase order.
	id := []string{"00000000-0000-0000-0000-000000000000"} // []string | A list of unique identifiers for line items. (optional)
	lineItemNumber := int32(0) // int32 | The PO line item number. (optional)
	status := "string" // string | Setup Table: PO Line Item Status (optional)
	manufacturer := "string" // string | Application: Manufacturers (optional)
	manufacturerPartNumber := "string" // string | Manufacturer part number, this may be different than the Plex part number. (optional)
	supplierPartNumber := "string" // string | Supplier part number, this may be different than the Plex part number. (optional)
	itemId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the supply item. (optional)
	partId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the part. (optional)
	building := "string" // string | Application: Buildings (optional)
	department := "string" // string | Application: Department List (optional)
	createdDateBegin := time.Now() // time.Time | The date on which the record was created. (optional)
	createdDateEnd := time.Now() // time.Time | The date on which the record was created. (optional)
	modifiedById := "00000000-0000-0000-0000-000000000000" // string | The ID of the user who last modified the record. (optional)
	modifiedDateBegin := time.Now() // time.Time | The date on which the record was last modified. (optional)
	modifiedDateEnd := time.Now() // time.Time | The date on which the record was last modified. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PurchaseOrdersAPIAPI.PurchaseOrdersApiListLineItems(context.Background(), poId).Id(id).LineItemNumber(lineItemNumber).Status(status).Manufacturer(manufacturer).ManufacturerPartNumber(manufacturerPartNumber).SupplierPartNumber(supplierPartNumber).ItemId(itemId).PartId(partId).Building(building).Department(department).CreatedDateBegin(createdDateBegin).CreatedDateEnd(createdDateEnd).ModifiedById(modifiedById).ModifiedDateBegin(modifiedDateBegin).ModifiedDateEnd(modifiedDateEnd).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PurchaseOrdersAPIAPI.PurchaseOrdersApiListLineItems``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PurchaseOrdersApiListLineItems`: []PurchaseOrdersApiListLineItemsItem
	fmt.Fprintf(os.Stdout, "Response from `PurchaseOrdersAPIAPI.PurchaseOrdersApiListLineItems`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**poId** | **string** | A unique identifier for the purchase order. | 

### Other Parameters

Other parameters are passed through a pointer to a apiPurchaseOrdersApiListLineItemsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **id** | **[]string** | A list of unique identifiers for line items. | 
 **lineItemNumber** | **int32** | The PO line item number. | 
 **status** | **string** | Setup Table: PO Line Item Status | 
 **manufacturer** | **string** | Application: Manufacturers | 
 **manufacturerPartNumber** | **string** | Manufacturer part number, this may be different than the Plex part number. | 
 **supplierPartNumber** | **string** | Supplier part number, this may be different than the Plex part number. | 
 **itemId** | **string** | A unique identifier for the supply item. | 
 **partId** | **string** | A unique identifier for the part. | 
 **building** | **string** | Application: Buildings | 
 **department** | **string** | Application: Department List | 
 **createdDateBegin** | **time.Time** | The date on which the record was created. | 
 **createdDateEnd** | **time.Time** | The date on which the record was created. | 
 **modifiedById** | **string** | The ID of the user who last modified the record. | 
 **modifiedDateBegin** | **time.Time** | The date on which the record was last modified. | 
 **modifiedDateEnd** | **time.Time** | The date on which the record was last modified. | 

### Return type

[**[]PurchaseOrdersApiListLineItemsItem**](PurchaseOrdersApiListLineItemsItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PurchaseOrdersApiListPurchaseOrderPrices

> []PurchaseOrdersApiListPurchaseOrderPricesItem PurchaseOrdersApiListPurchaseOrderPrices(ctx, id, lineItemId).PriceByDateBegin(priceByDateBegin).PriceByDateEnd(priceByDateEnd).EffectiveDateBegin(effectiveDateBegin).EffectiveDateEnd(effectiveDateEnd).ExpirationDateBegin(expirationDateBegin).ExpirationDateEnd(expirationDateEnd).Execute()

List Purchase Order Prices



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
	id := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the purchase order.
	lineItemId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the line item.
	priceByDateBegin := time.Now() // time.Time | A date on which to validate if the Price is effective. Only returns records with an Expiration Date on or after this value when it is specified. (optional)
	priceByDateEnd := time.Now() // time.Time | A date on which to validate if the Price is effective. Only returns records with an Effective Date on or before this value when it is specified. (optional)
	effectiveDateBegin := time.Now() // time.Time | A date on which to validate if the Price is effective. Only returns records with an Effective Date on or after this value when it is specified. (optional)
	effectiveDateEnd := time.Now() // time.Time | A date on which to validate if the Price is effective. Only returns records with an Effective Date on or before this value when it is specified. (optional)
	expirationDateBegin := time.Now() // time.Time | A date on which to validate if the Price is effective. Only returns records with an Expiration Date on or after this value when it is specified. (optional)
	expirationDateEnd := time.Now() // time.Time | A date on which to validate if the Price is effective. Only returns records with an Expiration Date on or before this value when it is specified. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PurchaseOrdersAPIAPI.PurchaseOrdersApiListPurchaseOrderPrices(context.Background(), id, lineItemId).PriceByDateBegin(priceByDateBegin).PriceByDateEnd(priceByDateEnd).EffectiveDateBegin(effectiveDateBegin).EffectiveDateEnd(effectiveDateEnd).ExpirationDateBegin(expirationDateBegin).ExpirationDateEnd(expirationDateEnd).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PurchaseOrdersAPIAPI.PurchaseOrdersApiListPurchaseOrderPrices``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PurchaseOrdersApiListPurchaseOrderPrices`: []PurchaseOrdersApiListPurchaseOrderPricesItem
	fmt.Fprintf(os.Stdout, "Response from `PurchaseOrdersAPIAPI.PurchaseOrdersApiListPurchaseOrderPrices`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | A unique identifier for the purchase order. | 
**lineItemId** | **string** | A unique identifier for the line item. | 

### Other Parameters

Other parameters are passed through a pointer to a apiPurchaseOrdersApiListPurchaseOrderPricesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **priceByDateBegin** | **time.Time** | A date on which to validate if the Price is effective. Only returns records with an Expiration Date on or after this value when it is specified. | 
 **priceByDateEnd** | **time.Time** | A date on which to validate if the Price is effective. Only returns records with an Effective Date on or before this value when it is specified. | 
 **effectiveDateBegin** | **time.Time** | A date on which to validate if the Price is effective. Only returns records with an Effective Date on or after this value when it is specified. | 
 **effectiveDateEnd** | **time.Time** | A date on which to validate if the Price is effective. Only returns records with an Effective Date on or before this value when it is specified. | 
 **expirationDateBegin** | **time.Time** | A date on which to validate if the Price is effective. Only returns records with an Expiration Date on or after this value when it is specified. | 
 **expirationDateEnd** | **time.Time** | A date on which to validate if the Price is effective. Only returns records with an Expiration Date on or before this value when it is specified. | 

### Return type

[**[]PurchaseOrdersApiListPurchaseOrderPricesItem**](PurchaseOrdersApiListPurchaseOrderPricesItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PurchaseOrdersApiListPurchaseOrderStatuses

> []PurchaseOrdersApiListPurchaseOrderStatusesItem PurchaseOrdersApiListPurchaseOrderStatuses(ctx).Name(name).Active(active).Default_(default_).Receive(receive).IncludeInMrp(includeInMrp).Cancelled(cancelled).Release(release).OnOrder(onOrder).Received(received).Execute()

List Purchase Order Statuses



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
	name := []string{"string"} // []string | List of purchase order status names. (optional)
	active := false // bool | Indicates whether the purchase order status is active or inactive. (optional)
	default_ := false // bool | Indicates that this purchase order status is the default for purchase orders. (optional)
	receive := false // bool | Indicates that purchase orders in this status allow receiving. (optional)
	includeInMrp := false // bool | Indicates that purchase orders in this status are included in MRP (Material Requirements Planning). (optional)
	cancelled := false // bool | Indicates that purchase orders in this status are canceled. (optional)
	release := false // bool | Indicates that purchase orders in this status are released. (optional)
	onOrder := false // bool | Indicates that purchase orders in this status are on order (sent to the supplier). (optional)
	received := false // bool | Indicates that purchase orders in this status were fully received. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PurchaseOrdersAPIAPI.PurchaseOrdersApiListPurchaseOrderStatuses(context.Background()).Name(name).Active(active).Default_(default_).Receive(receive).IncludeInMrp(includeInMrp).Cancelled(cancelled).Release(release).OnOrder(onOrder).Received(received).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PurchaseOrdersAPIAPI.PurchaseOrdersApiListPurchaseOrderStatuses``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PurchaseOrdersApiListPurchaseOrderStatuses`: []PurchaseOrdersApiListPurchaseOrderStatusesItem
	fmt.Fprintf(os.Stdout, "Response from `PurchaseOrdersAPIAPI.PurchaseOrdersApiListPurchaseOrderStatuses`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPurchaseOrdersApiListPurchaseOrderStatusesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **name** | **[]string** | List of purchase order status names. | 
 **active** | **bool** | Indicates whether the purchase order status is active or inactive. | 
 **default_** | **bool** | Indicates that this purchase order status is the default for purchase orders. | 
 **receive** | **bool** | Indicates that purchase orders in this status allow receiving. | 
 **includeInMrp** | **bool** | Indicates that purchase orders in this status are included in MRP (Material Requirements Planning). | 
 **cancelled** | **bool** | Indicates that purchase orders in this status are canceled. | 
 **release** | **bool** | Indicates that purchase orders in this status are released. | 
 **onOrder** | **bool** | Indicates that purchase orders in this status are on order (sent to the supplier). | 
 **received** | **bool** | Indicates that purchase orders in this status were fully received. | 

### Return type

[**[]PurchaseOrdersApiListPurchaseOrderStatusesItem**](PurchaseOrdersApiListPurchaseOrderStatusesItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PurchaseOrdersApiListPurchaseOrderTypes

> []PurchaseOrdersApiListPurchaseOrderTypesItem PurchaseOrdersApiListPurchaseOrderTypes(ctx).Name(name).Active(active).Default_(default_).IncludeInMRP(includeInMRP).Execute()

List Purchase Order Types



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
	name := []string{"string"} // []string | List of purchase order type names. (optional)
	active := false // bool | Indicates whether the purchase order type is active or inactive. (optional)
	default_ := false // bool | Indicates that this purchase order type is the default for purchase orders. (optional)
	includeInMRP := false // bool | Indicates that purchase orders of this type are included in MRP (Material Requirements Planning). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PurchaseOrdersAPIAPI.PurchaseOrdersApiListPurchaseOrderTypes(context.Background()).Name(name).Active(active).Default_(default_).IncludeInMRP(includeInMRP).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PurchaseOrdersAPIAPI.PurchaseOrdersApiListPurchaseOrderTypes``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PurchaseOrdersApiListPurchaseOrderTypes`: []PurchaseOrdersApiListPurchaseOrderTypesItem
	fmt.Fprintf(os.Stdout, "Response from `PurchaseOrdersAPIAPI.PurchaseOrdersApiListPurchaseOrderTypes`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPurchaseOrdersApiListPurchaseOrderTypesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **name** | **[]string** | List of purchase order type names. | 
 **active** | **bool** | Indicates whether the purchase order type is active or inactive. | 
 **default_** | **bool** | Indicates that this purchase order type is the default for purchase orders. | 
 **includeInMRP** | **bool** | Indicates that purchase orders of this type are included in MRP (Material Requirements Planning). | 

### Return type

[**[]PurchaseOrdersApiListPurchaseOrderTypesItem**](PurchaseOrdersApiListPurchaseOrderTypesItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PurchaseOrdersApiListPurchaseOrders

> []PurchaseOrdersApiListPurchaseOrdersItem PurchaseOrdersApiListPurchaseOrders(ctx).Id(id).PONumber(pONumber).Status(status).Active(active).Receive(receive).Type_(type_).SupplierId(supplierId).ShipTo(shipTo).OrderedDateBegin(orderedDateBegin).OrderedDateEnd(orderedDateEnd).DueDateBegin(dueDateBegin).DueDateEnd(dueDateEnd).Building(building).Department(department).BlanketOrder(blanketOrder).CreatedById(createdById).CreatedDateBegin(createdDateBegin).CreatedDateEnd(createdDateEnd).ModifiedById(modifiedById).ModifiedDateBegin(modifiedDateBegin).ModifiedDateEnd(modifiedDateEnd).Execute()

List Purchase Orders



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
	id := []string{"00000000-0000-0000-0000-000000000000"} // []string | A list of purchase order IDs. (optional)
	pONumber := "string" // string | The purchase order number. (optional)
	status := "string" // string | Setup Table: PO Status (optional)
	active := false // bool | This flag will be set to true by default. (optional)
	receive := false // bool | Indicates that purchase orders in this status allow receiving. (optional)
	type_ := "string" // string | Application: PO Type (optional)
	supplierId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the supplier. (optional)
	shipTo := "string" // string | The destination to which goods and services on the PO will be shipped to. Application: PO Ship To (optional)
	orderedDateBegin := time.Now() // time.Time | The date on which the status was set to On Order. (optional)
	orderedDateEnd := time.Now() // time.Time | The date on which the status was set to On Order. (optional)
	dueDateBegin := time.Now() // time.Time | The Due Date for the PO, not for individual lines or releases. (optional)
	dueDateEnd := time.Now() // time.Time | The Due Date for the PO, not for individual lines or releases. (optional)
	building := "string" // string | Application: Buildings (optional)
	department := "string" // string | Application: Department List (optional)
	blanketOrder := false // bool | Determines whether the Purchase Order is a blanket order or discrete order. (optional)
	createdById := "00000000-0000-0000-0000-000000000000" // string | The ID of the user who created the record. (optional)
	createdDateBegin := time.Now() // time.Time | The date on which the record was created. (optional)
	createdDateEnd := time.Now() // time.Time | The date on which the record was created. (optional)
	modifiedById := "00000000-0000-0000-0000-000000000000" // string | The ID of the user who last modified the record. (optional)
	modifiedDateBegin := time.Now() // time.Time | The date on which the record was last modified. (optional)
	modifiedDateEnd := time.Now() // time.Time | The date on which the record was last modified. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PurchaseOrdersAPIAPI.PurchaseOrdersApiListPurchaseOrders(context.Background()).Id(id).PONumber(pONumber).Status(status).Active(active).Receive(receive).Type_(type_).SupplierId(supplierId).ShipTo(shipTo).OrderedDateBegin(orderedDateBegin).OrderedDateEnd(orderedDateEnd).DueDateBegin(dueDateBegin).DueDateEnd(dueDateEnd).Building(building).Department(department).BlanketOrder(blanketOrder).CreatedById(createdById).CreatedDateBegin(createdDateBegin).CreatedDateEnd(createdDateEnd).ModifiedById(modifiedById).ModifiedDateBegin(modifiedDateBegin).ModifiedDateEnd(modifiedDateEnd).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PurchaseOrdersAPIAPI.PurchaseOrdersApiListPurchaseOrders``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PurchaseOrdersApiListPurchaseOrders`: []PurchaseOrdersApiListPurchaseOrdersItem
	fmt.Fprintf(os.Stdout, "Response from `PurchaseOrdersAPIAPI.PurchaseOrdersApiListPurchaseOrders`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPurchaseOrdersApiListPurchaseOrdersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **[]string** | A list of purchase order IDs. | 
 **pONumber** | **string** | The purchase order number. | 
 **status** | **string** | Setup Table: PO Status | 
 **active** | **bool** | This flag will be set to true by default. | 
 **receive** | **bool** | Indicates that purchase orders in this status allow receiving. | 
 **type_** | **string** | Application: PO Type | 
 **supplierId** | **string** | A unique identifier for the supplier. | 
 **shipTo** | **string** | The destination to which goods and services on the PO will be shipped to. Application: PO Ship To | 
 **orderedDateBegin** | **time.Time** | The date on which the status was set to On Order. | 
 **orderedDateEnd** | **time.Time** | The date on which the status was set to On Order. | 
 **dueDateBegin** | **time.Time** | The Due Date for the PO, not for individual lines or releases. | 
 **dueDateEnd** | **time.Time** | The Due Date for the PO, not for individual lines or releases. | 
 **building** | **string** | Application: Buildings | 
 **department** | **string** | Application: Department List | 
 **blanketOrder** | **bool** | Determines whether the Purchase Order is a blanket order or discrete order. | 
 **createdById** | **string** | The ID of the user who created the record. | 
 **createdDateBegin** | **time.Time** | The date on which the record was created. | 
 **createdDateEnd** | **time.Time** | The date on which the record was created. | 
 **modifiedById** | **string** | The ID of the user who last modified the record. | 
 **modifiedDateBegin** | **time.Time** | The date on which the record was last modified. | 
 **modifiedDateEnd** | **time.Time** | The date on which the record was last modified. | 

### Return type

[**[]PurchaseOrdersApiListPurchaseOrdersItem**](PurchaseOrdersApiListPurchaseOrdersItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

