# \CustomerTrucksAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CustomerTrucksApiCreateCustomerTruck**](CustomerTrucksAPIAPI.md#CustomerTrucksApiCreateCustomerTruck) | **Post** /shipping/v1-beta1/customer-trucks | Create Customer Truck
[**CustomerTrucksApiGetCustomerTruck**](CustomerTrucksAPIAPI.md#CustomerTrucksApiGetCustomerTruck) | **Get** /shipping/v1/customer-trucks/{id} | Get Customer Truck
[**CustomerTrucksApiListCustomerTrucks**](CustomerTrucksAPIAPI.md#CustomerTrucksApiListCustomerTrucks) | **Get** /shipping/v1/customer-trucks | List Customer Trucks
[**CustomerTrucksApiShipTruck**](CustomerTrucksAPIAPI.md#CustomerTrucksApiShipTruck) | **Post** /shipping/v1-beta1/customer-trucks/{id}/ship | Ship Truck
[**CustomerTrucksApiUpdateCustomerTruck**](CustomerTrucksAPIAPI.md#CustomerTrucksApiUpdateCustomerTruck) | **Put** /shipping/v1-beta1/customer-trucks/{id} | Update Customer Truck



## CustomerTrucksApiCreateCustomerTruck

> CustomerTrucksApiCreateCustomerTruck201Response CustomerTrucksApiCreateCustomerTruck(ctx).CustomerTrucksApiCreateCustomerTruckRequest(customerTrucksApiCreateCustomerTruckRequest).Execute()

Create Customer Truck



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
	customerTrucksApiCreateCustomerTruckRequest := *openapiclient.NewCustomerTrucksApiCreateCustomerTruckRequest() // CustomerTrucksApiCreateCustomerTruckRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomerTrucksAPIAPI.CustomerTrucksApiCreateCustomerTruck(context.Background()).CustomerTrucksApiCreateCustomerTruckRequest(customerTrucksApiCreateCustomerTruckRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomerTrucksAPIAPI.CustomerTrucksApiCreateCustomerTruck``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomerTrucksApiCreateCustomerTruck`: CustomerTrucksApiCreateCustomerTruck201Response
	fmt.Fprintf(os.Stdout, "Response from `CustomerTrucksAPIAPI.CustomerTrucksApiCreateCustomerTruck`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCustomerTrucksApiCreateCustomerTruckRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **customerTrucksApiCreateCustomerTruckRequest** | [**CustomerTrucksApiCreateCustomerTruckRequest**](CustomerTrucksApiCreateCustomerTruckRequest.md) |  | 

### Return type

[**CustomerTrucksApiCreateCustomerTruck201Response**](CustomerTrucksApiCreateCustomerTruck201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomerTrucksApiGetCustomerTruck

> CustomerTrucksApiGetCustomerTruckResponse CustomerTrucksApiGetCustomerTruck(ctx, id).Execute()

Get Customer Truck



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
	id := "00000000-0000-0000-0000-000000000000" // string | The unique identifier for the truck record.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomerTrucksAPIAPI.CustomerTrucksApiGetCustomerTruck(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomerTrucksAPIAPI.CustomerTrucksApiGetCustomerTruck``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomerTrucksApiGetCustomerTruck`: CustomerTrucksApiGetCustomerTruckResponse
	fmt.Fprintf(os.Stdout, "Response from `CustomerTrucksAPIAPI.CustomerTrucksApiGetCustomerTruck`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The unique identifier for the truck record. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustomerTrucksApiGetCustomerTruckRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**CustomerTrucksApiGetCustomerTruckResponse**](CustomerTrucksApiGetCustomerTruckResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomerTrucksApiListCustomerTrucks

> []CustomerTrucksApiListCustomerTrucksItem CustomerTrucksApiListCustomerTrucks(ctx).Id(id).ShipDateBegin(shipDateBegin).ShipDateEnd(shipDateEnd).ShippedById(shippedById).CarrierId(carrierId).FreightTerms(freightTerms).TrackingNumber(trackingNumber).TrailerNumber(trailerNumber).TruckCalled(truckCalled).TruckArrivalTimeBegin(truckArrivalTimeBegin).TruckArrivalTimeEnd(truckArrivalTimeEnd).BOLNumber(bOLNumber).Pool(pool).PoolCustomerAddressId(poolCustomerAddressId).TrailerCarrierId(trailerCarrierId).BrokeredCarrierId(brokeredCarrierId).ScheduledShipDateBegin(scheduledShipDateBegin).ScheduledShipDateEnd(scheduledShipDateEnd).CreatedById(createdById).CreatedDateBegin(createdDateBegin).CreatedDateEnd(createdDateEnd).ModifiedById(modifiedById).ModifiedDateBegin(modifiedDateBegin).ModifiedDateEnd(modifiedDateEnd).MilkRun(milkRun).Type_(type_).Status(status).TruckNumber(truckNumber).TransMode(transMode).ShipFromId(shipFromId).INCOTerms(iNCOTerms).CustomsBrokerSupplierId(customsBrokerSupplierId).SubBuilding(subBuilding).DropshipSupplierCode(dropshipSupplierCode).TruckRoute(truckRoute).TruckArrivalTimeOfDayBegin(truckArrivalTimeOfDayBegin).TruckArrivalTimeOfDayEnd(truckArrivalTimeOfDayEnd).TruckArrivalPlexTimeOfDayBegin(truckArrivalPlexTimeOfDayBegin).TruckArrivalPlexTimeOfDayEnd(truckArrivalPlexTimeOfDayEnd).Execute()

List Customer Trucks



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
	id := []string{"00000000-0000-0000-0000-000000000000"} // []string | A unique identifier for the truck. This will be automatically generated if omitted from the request. (optional)
	shipDateBegin := time.Now() // time.Time | The beginning date used to return truck records with a Ship Date within a specified time frame. (optional)
	shipDateEnd := time.Now() // time.Time | The end date used to return truck records with a Ship Date within a specified time frame. (optional)
	shippedById := "00000000-0000-0000-0000-000000000000" // string | The ID of the user who shipped the truck. (optional)
	carrierId := "00000000-0000-0000-0000-000000000000" // string | The ID of the carrier associated with the truck. (A carrier is a supplier with a supplier type of &quot;Carrier&quot;.) (optional)
	freightTerms := "string" // string | Terms of the freight payment; for example, COD, Collect, or Prepaid. (optional)
	trackingNumber := "string" // string | The tracking number, often provided by a carrier, related to a specific shipment. (optional)
	trailerNumber := "string" // string | The trailer number associated with the physical trailer that a specific shipment was shipped on. (optional)
	truckCalled := false // bool | Indicates if the carrier has been contacted. (optional)
	truckArrivalTimeBegin := time.Now() // time.Time | The beginning time used to return truck records with an arrival time within the specified time frame (arrival time can be planned or actual, depending on implementation). (optional)
	truckArrivalTimeEnd := time.Now() // time.Time | The ending time used to return truck records with an arrival time within the specified time frame (arrival time can be planned or actual, depending on implementation). (optional)
	bOLNumber := "string" // string | The bill of lading number. (optional)
	pool := false // bool | Indicates that the truck is part of a pool shipment. A pool is a central warehouse that redistributes shippers from one truck to another before shipping to customer locations. (optional)
	poolCustomerAddressId := "00000000-0000-0000-0000-000000000000" // string | The customer address ID of the pool location associated with the truck. (optional)
	trailerCarrierId := "00000000-0000-0000-0000-000000000000" // string | The ID of the supplier with a &quot;Carrier&quot; type used as the trailer carrier. (optional)
	brokeredCarrierId := "00000000-0000-0000-0000-000000000000" // string | The ID of the supplier with a &quot;Carrier&quot; type used as the brokered carrier. (optional)
	scheduledShipDateBegin := time.Now() // time.Time | The beginning date used to return truck records with a scheduled ship date within the specified time frame. (optional)
	scheduledShipDateEnd := time.Now() // time.Time | The ending date used to return truck records with a scheduled ship date within the specified time frame. (optional)
	createdById := "00000000-0000-0000-0000-000000000000" // string | The ID of the user who created the record. (optional)
	createdDateBegin := time.Now() // time.Time | The beginning date used to return truck records that were created within the specified time frame. (optional)
	createdDateEnd := time.Now() // time.Time | The ending date used to return truck records that were created within the specified time frame. (optional)
	modifiedById := "00000000-0000-0000-0000-000000000000" // string | The ID of the user who last modified the record. (optional)
	modifiedDateBegin := time.Now() // time.Time | The beginning date used to return truck records that were last modified within the specified time frame. (optional)
	modifiedDateEnd := time.Now() // time.Time | The ending date used to return truck records that were last modified within the specified time frame. (optional)
	milkRun := "string" // string | The name of a route with multiple stops that happens on a recurring basis. (optional)
	type_ := "string" // string | The truck type. (optional)
	status := "string" // string | The truck status. (optional)
	truckNumber := "string" // string | A Plex-generated unique number representing the truck shipment. (optional)
	transMode := "string" // string | The transportation mode associated with the truck. (optional)
	shipFromId := "00000000-0000-0000-0000-000000000000" // string | The ID of the customer address from which the truck was shipped. (optional)
	iNCOTerms := "string" // string | International Commercial (INCO) terms applied to the sales order. (optional)
	customsBrokerSupplierId := "00000000-0000-0000-0000-000000000000" // string | The ID of the supplier with a &quot;Customs Broker&quot; type. (optional)
	subBuilding := "string" // string | The sub-building code indicating the location in the building where the truck will be loaded. (optional)
	dropshipSupplierCode := "string" // string | The dropship supplier code associated with the truck. (optional)
	truckRoute := "string" // string | The route for the truck. (optional)
	truckArrivalTimeOfDayBegin := "string" // string | The time at which the truck arrived. (optional)
	truckArrivalTimeOfDayEnd := "string" // string | The time at which the truck arrived. (optional)
	truckArrivalPlexTimeOfDayBegin := time.Now() // time.Time | The time at which the truck arrived. (optional)
	truckArrivalPlexTimeOfDayEnd := time.Now() // time.Time | The time at which the truck arrived. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomerTrucksAPIAPI.CustomerTrucksApiListCustomerTrucks(context.Background()).Id(id).ShipDateBegin(shipDateBegin).ShipDateEnd(shipDateEnd).ShippedById(shippedById).CarrierId(carrierId).FreightTerms(freightTerms).TrackingNumber(trackingNumber).TrailerNumber(trailerNumber).TruckCalled(truckCalled).TruckArrivalTimeBegin(truckArrivalTimeBegin).TruckArrivalTimeEnd(truckArrivalTimeEnd).BOLNumber(bOLNumber).Pool(pool).PoolCustomerAddressId(poolCustomerAddressId).TrailerCarrierId(trailerCarrierId).BrokeredCarrierId(brokeredCarrierId).ScheduledShipDateBegin(scheduledShipDateBegin).ScheduledShipDateEnd(scheduledShipDateEnd).CreatedById(createdById).CreatedDateBegin(createdDateBegin).CreatedDateEnd(createdDateEnd).ModifiedById(modifiedById).ModifiedDateBegin(modifiedDateBegin).ModifiedDateEnd(modifiedDateEnd).MilkRun(milkRun).Type_(type_).Status(status).TruckNumber(truckNumber).TransMode(transMode).ShipFromId(shipFromId).INCOTerms(iNCOTerms).CustomsBrokerSupplierId(customsBrokerSupplierId).SubBuilding(subBuilding).DropshipSupplierCode(dropshipSupplierCode).TruckRoute(truckRoute).TruckArrivalTimeOfDayBegin(truckArrivalTimeOfDayBegin).TruckArrivalTimeOfDayEnd(truckArrivalTimeOfDayEnd).TruckArrivalPlexTimeOfDayBegin(truckArrivalPlexTimeOfDayBegin).TruckArrivalPlexTimeOfDayEnd(truckArrivalPlexTimeOfDayEnd).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomerTrucksAPIAPI.CustomerTrucksApiListCustomerTrucks``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomerTrucksApiListCustomerTrucks`: []CustomerTrucksApiListCustomerTrucksItem
	fmt.Fprintf(os.Stdout, "Response from `CustomerTrucksAPIAPI.CustomerTrucksApiListCustomerTrucks`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCustomerTrucksApiListCustomerTrucksRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **[]string** | A unique identifier for the truck. This will be automatically generated if omitted from the request. | 
 **shipDateBegin** | **time.Time** | The beginning date used to return truck records with a Ship Date within a specified time frame. | 
 **shipDateEnd** | **time.Time** | The end date used to return truck records with a Ship Date within a specified time frame. | 
 **shippedById** | **string** | The ID of the user who shipped the truck. | 
 **carrierId** | **string** | The ID of the carrier associated with the truck. (A carrier is a supplier with a supplier type of &amp;quot;Carrier&amp;quot;.) | 
 **freightTerms** | **string** | Terms of the freight payment; for example, COD, Collect, or Prepaid. | 
 **trackingNumber** | **string** | The tracking number, often provided by a carrier, related to a specific shipment. | 
 **trailerNumber** | **string** | The trailer number associated with the physical trailer that a specific shipment was shipped on. | 
 **truckCalled** | **bool** | Indicates if the carrier has been contacted. | 
 **truckArrivalTimeBegin** | **time.Time** | The beginning time used to return truck records with an arrival time within the specified time frame (arrival time can be planned or actual, depending on implementation). | 
 **truckArrivalTimeEnd** | **time.Time** | The ending time used to return truck records with an arrival time within the specified time frame (arrival time can be planned or actual, depending on implementation). | 
 **bOLNumber** | **string** | The bill of lading number. | 
 **pool** | **bool** | Indicates that the truck is part of a pool shipment. A pool is a central warehouse that redistributes shippers from one truck to another before shipping to customer locations. | 
 **poolCustomerAddressId** | **string** | The customer address ID of the pool location associated with the truck. | 
 **trailerCarrierId** | **string** | The ID of the supplier with a &amp;quot;Carrier&amp;quot; type used as the trailer carrier. | 
 **brokeredCarrierId** | **string** | The ID of the supplier with a &amp;quot;Carrier&amp;quot; type used as the brokered carrier. | 
 **scheduledShipDateBegin** | **time.Time** | The beginning date used to return truck records with a scheduled ship date within the specified time frame. | 
 **scheduledShipDateEnd** | **time.Time** | The ending date used to return truck records with a scheduled ship date within the specified time frame. | 
 **createdById** | **string** | The ID of the user who created the record. | 
 **createdDateBegin** | **time.Time** | The beginning date used to return truck records that were created within the specified time frame. | 
 **createdDateEnd** | **time.Time** | The ending date used to return truck records that were created within the specified time frame. | 
 **modifiedById** | **string** | The ID of the user who last modified the record. | 
 **modifiedDateBegin** | **time.Time** | The beginning date used to return truck records that were last modified within the specified time frame. | 
 **modifiedDateEnd** | **time.Time** | The ending date used to return truck records that were last modified within the specified time frame. | 
 **milkRun** | **string** | The name of a route with multiple stops that happens on a recurring basis. | 
 **type_** | **string** | The truck type. | 
 **status** | **string** | The truck status. | 
 **truckNumber** | **string** | A Plex-generated unique number representing the truck shipment. | 
 **transMode** | **string** | The transportation mode associated with the truck. | 
 **shipFromId** | **string** | The ID of the customer address from which the truck was shipped. | 
 **iNCOTerms** | **string** | International Commercial (INCO) terms applied to the sales order. | 
 **customsBrokerSupplierId** | **string** | The ID of the supplier with a &amp;quot;Customs Broker&amp;quot; type. | 
 **subBuilding** | **string** | The sub-building code indicating the location in the building where the truck will be loaded. | 
 **dropshipSupplierCode** | **string** | The dropship supplier code associated with the truck. | 
 **truckRoute** | **string** | The route for the truck. | 
 **truckArrivalTimeOfDayBegin** | **string** | The time at which the truck arrived. | 
 **truckArrivalTimeOfDayEnd** | **string** | The time at which the truck arrived. | 
 **truckArrivalPlexTimeOfDayBegin** | **time.Time** | The time at which the truck arrived. | 
 **truckArrivalPlexTimeOfDayEnd** | **time.Time** | The time at which the truck arrived. | 

### Return type

[**[]CustomerTrucksApiListCustomerTrucksItem**](CustomerTrucksApiListCustomerTrucksItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomerTrucksApiShipTruck

> CustomerTrucksApiShipTruckResponse CustomerTrucksApiShipTruck(ctx, id).Execute()

Ship Truck



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
	id := "00000000-0000-0000-0000-000000000000" // string | The resource identifier for the truck to be shipped.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomerTrucksAPIAPI.CustomerTrucksApiShipTruck(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomerTrucksAPIAPI.CustomerTrucksApiShipTruck``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomerTrucksApiShipTruck`: CustomerTrucksApiShipTruckResponse
	fmt.Fprintf(os.Stdout, "Response from `CustomerTrucksAPIAPI.CustomerTrucksApiShipTruck`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The resource identifier for the truck to be shipped. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustomerTrucksApiShipTruckRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**CustomerTrucksApiShipTruckResponse**](CustomerTrucksApiShipTruckResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomerTrucksApiUpdateCustomerTruck

> CustomerTrucksApiUpdateCustomerTruckResponse CustomerTrucksApiUpdateCustomerTruck(ctx, id).CustomerTrucksApiUpdateCustomerTruckRequest(customerTrucksApiUpdateCustomerTruckRequest).Execute()

Update Customer Truck



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
	id := "00000000-0000-0000-0000-000000000000" // string | The resource identifier of truck to be updated.
	customerTrucksApiUpdateCustomerTruckRequest := *openapiclient.NewCustomerTrucksApiUpdateCustomerTruckRequest() // CustomerTrucksApiUpdateCustomerTruckRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomerTrucksAPIAPI.CustomerTrucksApiUpdateCustomerTruck(context.Background(), id).CustomerTrucksApiUpdateCustomerTruckRequest(customerTrucksApiUpdateCustomerTruckRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomerTrucksAPIAPI.CustomerTrucksApiUpdateCustomerTruck``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomerTrucksApiUpdateCustomerTruck`: CustomerTrucksApiUpdateCustomerTruckResponse
	fmt.Fprintf(os.Stdout, "Response from `CustomerTrucksAPIAPI.CustomerTrucksApiUpdateCustomerTruck`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The resource identifier of truck to be updated. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustomerTrucksApiUpdateCustomerTruckRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **customerTrucksApiUpdateCustomerTruckRequest** | [**CustomerTrucksApiUpdateCustomerTruckRequest**](CustomerTrucksApiUpdateCustomerTruckRequest.md) |  | 

### Return type

[**CustomerTrucksApiUpdateCustomerTruckResponse**](CustomerTrucksApiUpdateCustomerTruckResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

