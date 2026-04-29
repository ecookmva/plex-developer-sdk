# \CustomerShippersAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CustomerShippersApiCreateShipper**](CustomerShippersAPIAPI.md#CustomerShippersApiCreateShipper) | **Post** /shipping/v1-beta1/customer-shippers | Create Shipper
[**CustomerShippersApiGetCustomerShipper**](CustomerShippersAPIAPI.md#CustomerShippersApiGetCustomerShipper) | **Get** /shipping/v1/customer-shippers/{id} | Get Customer Shipper
[**CustomerShippersApiGetCustomerShipperLine**](CustomerShippersAPIAPI.md#CustomerShippersApiGetCustomerShipperLine) | **Get** /shipping/v1/customer-shippers/{shipperId}/lines/{lineId} | Get Customer Shipper Line
[**CustomerShippersApiListCustomerShipperLineContainers**](CustomerShippersAPIAPI.md#CustomerShippersApiListCustomerShipperLineContainers) | **Get** /shipping/v1/customer-shippers/{id}/lines/{lineId}/containers | List Customer Shipper Line Containers
[**CustomerShippersApiListCustomerShipperLineReleases**](CustomerShippersAPIAPI.md#CustomerShippersApiListCustomerShipperLineReleases) | **Get** /shipping/v1/customer-shippers/{id}/lines/{lineId}/releases | List Customer Shipper Line Releases
[**CustomerShippersApiListCustomerShipperLines**](CustomerShippersAPIAPI.md#CustomerShippersApiListCustomerShipperLines) | **Get** /shipping/v1/customer-shippers/{shipperId}/lines | List Customer Shipper Lines
[**CustomerShippersApiListCustomerShippers**](CustomerShippersAPIAPI.md#CustomerShippersApiListCustomerShippers) | **Get** /shipping/v1/customer-shippers | List Customer Shippers
[**CustomerShippersApiLoadContainer**](CustomerShippersAPIAPI.md#CustomerShippersApiLoadContainer) | **Post** /shipping/v1-beta1/customer-shippers/{shipperId}/lines/{lineId}/load-container | Load Container
[**CustomerShippersApiLoadShipperLineFIFO**](CustomerShippersAPIAPI.md#CustomerShippersApiLoadShipperLineFIFO) | **Post** /shipping/v1-beta1/customer-shippers/{shipperId}/lines/{lineId}/load-fifo | Load Shipper Line FIFO
[**CustomerShippersApiScheduleReleases**](CustomerShippersAPIAPI.md#CustomerShippersApiScheduleReleases) | **Post** /shipping/v1-beta1/customer-shippers/{id}/schedule-releases | Schedule Releases
[**CustomerShippersApiShipShipper**](CustomerShippersAPIAPI.md#CustomerShippersApiShipShipper) | **Post** /shipping/v1-beta1/customer-shippers/{shipperId}/ship | Ship Shipper
[**CustomerShippersApiUpdateShipper**](CustomerShippersAPIAPI.md#CustomerShippersApiUpdateShipper) | **Put** /shipping/v1-beta1/customer-shippers/{id} | Update Shipper



## CustomerShippersApiCreateShipper

> CustomerShippersApiCreateShipper201Response CustomerShippersApiCreateShipper(ctx).CustomerShippersApiCreateShipperRequest(customerShippersApiCreateShipperRequest).Execute()

Create Shipper



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
	customerShippersApiCreateShipperRequest := *openapiclient.NewCustomerShippersApiCreateShipperRequest() // CustomerShippersApiCreateShipperRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomerShippersAPIAPI.CustomerShippersApiCreateShipper(context.Background()).CustomerShippersApiCreateShipperRequest(customerShippersApiCreateShipperRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomerShippersAPIAPI.CustomerShippersApiCreateShipper``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomerShippersApiCreateShipper`: CustomerShippersApiCreateShipper201Response
	fmt.Fprintf(os.Stdout, "Response from `CustomerShippersAPIAPI.CustomerShippersApiCreateShipper`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCustomerShippersApiCreateShipperRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **customerShippersApiCreateShipperRequest** | [**CustomerShippersApiCreateShipperRequest**](CustomerShippersApiCreateShipperRequest.md) |  | 

### Return type

[**CustomerShippersApiCreateShipper201Response**](CustomerShippersApiCreateShipper201Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomerShippersApiGetCustomerShipper

> CustomerShippersApiGetCustomerShipperResponse CustomerShippersApiGetCustomerShipper(ctx, id).Execute()

Get Customer Shipper



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
	id := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the customer shipper record.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomerShippersAPIAPI.CustomerShippersApiGetCustomerShipper(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomerShippersAPIAPI.CustomerShippersApiGetCustomerShipper``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomerShippersApiGetCustomerShipper`: CustomerShippersApiGetCustomerShipperResponse
	fmt.Fprintf(os.Stdout, "Response from `CustomerShippersAPIAPI.CustomerShippersApiGetCustomerShipper`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | A unique identifier for the customer shipper record. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustomerShippersApiGetCustomerShipperRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**CustomerShippersApiGetCustomerShipperResponse**](CustomerShippersApiGetCustomerShipperResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomerShippersApiGetCustomerShipperLine

> CustomerShippersApiGetCustomerShipperLineResponse CustomerShippersApiGetCustomerShipperLine(ctx, shipperId, lineId).Execute()

Get Customer Shipper Line



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
	shipperId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the customer shipper record.
	lineId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the customer shipper line.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomerShippersAPIAPI.CustomerShippersApiGetCustomerShipperLine(context.Background(), shipperId, lineId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomerShippersAPIAPI.CustomerShippersApiGetCustomerShipperLine``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomerShippersApiGetCustomerShipperLine`: CustomerShippersApiGetCustomerShipperLineResponse
	fmt.Fprintf(os.Stdout, "Response from `CustomerShippersAPIAPI.CustomerShippersApiGetCustomerShipperLine`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**shipperId** | **string** | A unique identifier for the customer shipper record. | 
**lineId** | **string** | A unique identifier for the customer shipper line. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustomerShippersApiGetCustomerShipperLineRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**CustomerShippersApiGetCustomerShipperLineResponse**](CustomerShippersApiGetCustomerShipperLineResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomerShippersApiListCustomerShipperLineContainers

> []CustomerShippersApiListCustomerShipperLineContainersItem CustomerShippersApiListCustomerShipperLineContainers(ctx, id, lineId).Execute()

List Customer Shipper Line Containers



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
	id := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the customer shipper record.
	lineId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the customer shipper line record.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomerShippersAPIAPI.CustomerShippersApiListCustomerShipperLineContainers(context.Background(), id, lineId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomerShippersAPIAPI.CustomerShippersApiListCustomerShipperLineContainers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomerShippersApiListCustomerShipperLineContainers`: []CustomerShippersApiListCustomerShipperLineContainersItem
	fmt.Fprintf(os.Stdout, "Response from `CustomerShippersAPIAPI.CustomerShippersApiListCustomerShipperLineContainers`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | A unique identifier for the customer shipper record. | 
**lineId** | **string** | A unique identifier for the customer shipper line record. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustomerShippersApiListCustomerShipperLineContainersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**[]CustomerShippersApiListCustomerShipperLineContainersItem**](CustomerShippersApiListCustomerShipperLineContainersItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomerShippersApiListCustomerShipperLineReleases

> []CustomerShippersApiListCustomerShipperLineReleasesItem CustomerShippersApiListCustomerShipperLineReleases(ctx, id, lineId).Execute()

List Customer Shipper Line Releases



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
	id := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the customer shipper record.
	lineId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the customer shipper line record.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomerShippersAPIAPI.CustomerShippersApiListCustomerShipperLineReleases(context.Background(), id, lineId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomerShippersAPIAPI.CustomerShippersApiListCustomerShipperLineReleases``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomerShippersApiListCustomerShipperLineReleases`: []CustomerShippersApiListCustomerShipperLineReleasesItem
	fmt.Fprintf(os.Stdout, "Response from `CustomerShippersAPIAPI.CustomerShippersApiListCustomerShipperLineReleases`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | A unique identifier for the customer shipper record. | 
**lineId** | **string** | A unique identifier for the customer shipper line record. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustomerShippersApiListCustomerShipperLineReleasesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**[]CustomerShippersApiListCustomerShipperLineReleasesItem**](CustomerShippersApiListCustomerShipperLineReleasesItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomerShippersApiListCustomerShipperLines

> []CustomerShippersApiListCustomerShipperLinesItem CustomerShippersApiListCustomerShipperLines(ctx, shipperId).Id(id).Execute()

List Customer Shipper Lines



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
	shipperId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the customer shipper record.
	id := []string{"00000000-0000-0000-0000-000000000000"} // []string | One or more customer shipper line IDs. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomerShippersAPIAPI.CustomerShippersApiListCustomerShipperLines(context.Background(), shipperId).Id(id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomerShippersAPIAPI.CustomerShippersApiListCustomerShipperLines``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomerShippersApiListCustomerShipperLines`: []CustomerShippersApiListCustomerShipperLinesItem
	fmt.Fprintf(os.Stdout, "Response from `CustomerShippersAPIAPI.CustomerShippersApiListCustomerShipperLines`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**shipperId** | **string** | A unique identifier for the customer shipper record. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustomerShippersApiListCustomerShipperLinesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **id** | **[]string** | One or more customer shipper line IDs. | 

### Return type

[**[]CustomerShippersApiListCustomerShipperLinesItem**](CustomerShippersApiListCustomerShipperLinesItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomerShippersApiListCustomerShippers

> []CustomerShippersApiListCustomerShippersItem CustomerShippersApiListCustomerShippers(ctx).Id(id).ShipperNumber(shipperNumber).CustomerId(customerId).CustomerAddressId(customerAddressId).ShipDateBegin(shipDateBegin).ShipDateEnd(shipDateEnd).ShippedById(shippedById).CarrierId(carrierId).FreightTerms(freightTerms).Status(status).TrackingNumber(trackingNumber).TrailerNumber(trailerNumber).ScheduledShipDateBegin(scheduledShipDateBegin).ScheduledShipDateEnd(scheduledShipDateEnd).CreatedById(createdById).CreatedDateBegin(createdDateBegin).CreatedDateEnd(createdDateEnd).ModifiedById(modifiedById).ModifiedDateBegin(modifiedDateBegin).ModifiedDateEnd(modifiedDateEnd).TruckId(truckId).ExpediteReason(expediteReason).ExpediteDepartment(expediteDepartment).ExpediteAuthorizedById(expediteAuthorizedById).ShipFromCode(shipFromCode).TruckArrivalTimeBegin(truckArrivalTimeBegin).TruckArrivalTimeEnd(truckArrivalTimeEnd).PrintedById(printedById).PrintedDateBegin(printedDateBegin).PrintedDateEnd(printedDateEnd).PickListPrintedDateTimeBegin(pickListPrintedDateTimeBegin).PickListPrintedDateTimeEnd(pickListPrintedDateTimeEnd).TruckArrivalTimeOfDayBegin(truckArrivalTimeOfDayBegin).TruckArrivalTimeOfDayEnd(truckArrivalTimeOfDayEnd).Execute()

List Customer Shippers



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
	id := []string{"00000000-0000-0000-0000-000000000000"} // []string | One or more customer shipper line IDs. (optional)
	shipperNumber := "string" // string | The shipper number associated with a given shipment. (optional)
	customerId := "00000000-0000-0000-0000-000000000000" // string | The ID of the customer that is associated with the shipper. (optional)
	customerAddressId := "00000000-0000-0000-0000-000000000000" // string | The ID of the customer address that is associated with the shipper. (optional)
	shipDateBegin := time.Now() // time.Time | The date on which the shipper was shipped. (optional)
	shipDateEnd := time.Now() // time.Time | The date on which the shipper was shipped. (optional)
	shippedById := "00000000-0000-0000-0000-000000000000" // string | The ID of the user who shipped the shipper. (optional)
	carrierId := "00000000-0000-0000-0000-000000000000" // string | The supplier ID that is flagged as the carrier on this shipment. (optional)
	freightTerms := "string" // string | Terms of the freight payment; for example, COD, Collect, or Prepaid. (optional)
	status := "string" // string | The shipper's status. (optional)
	trackingNumber := "string" // string | The tracking number, often provided by a carrier, that is specified on the shipper. (optional)
	trailerNumber := "string" // string | The trailer number associated with the physical trailer that a specific shipment was shipped on. (optional)
	scheduledShipDateBegin := time.Now() // time.Time | The beginning date used to return shipper records that were scheduled to ship during a specified period of time. (optional)
	scheduledShipDateEnd := time.Now() // time.Time | The ending date used to return shipper records that were scheduled to ship during a specified period of time. (optional)
	createdById := "00000000-0000-0000-0000-000000000000" // string | The ID of the user who created the record. (optional)
	createdDateBegin := time.Now() // time.Time | The beginning date used to return shipper records that were created during a specified period of time. (optional)
	createdDateEnd := time.Now() // time.Time | The ending date used to return shipper records that were created during a specified period of time. (optional)
	modifiedById := "00000000-0000-0000-0000-000000000000" // string | The ID of the user who last modified the record. (optional)
	modifiedDateBegin := time.Now() // time.Time | The beginning date used to return shipper records that were last modified within a specified period of time. (optional)
	modifiedDateEnd := time.Now() // time.Time | The ending date used to return shipper records that were last modified within a specified period of time. (optional)
	truckId := "00000000-0000-0000-0000-000000000000" // string | The ID of the truck associated with the shipper. (optional)
	expediteReason := "string" // string | The reason for expedited shipping as specified on the shipper. (optional)
	expediteDepartment := "string" // string | The department that authorized or required an expedited shipment. (optional)
	expediteAuthorizedById := "00000000-0000-0000-0000-000000000000" // string | The ID of the user who authorized the expedited shipping. (optional)
	shipFromCode := "string" // string | The building code from which the shipper was shipped. (optional)
	truckArrivalTimeBegin := time.Now() // time.Time | This field has been deprecated. Use TruckArrivalTimeOfDayBegin. (optional)
	truckArrivalTimeEnd := time.Now() // time.Time | This field has been deprecated. Use TruckArrivalTimeOfDayEnd. (optional)
	printedById := "00000000-0000-0000-0000-000000000000" // string | The ID of the user who printed the record. (optional)
	printedDateBegin := time.Now() // time.Time | The beginning date used to return records that were printed within a specified period of time. (optional)
	printedDateEnd := time.Now() // time.Time | The ending date used to return records that were printed within a specified period of time. (optional)
	pickListPrintedDateTimeBegin := time.Now() // time.Time | The beginning date used to return pick list records that were printed within a specified period of time. (optional)
	pickListPrintedDateTimeEnd := time.Now() // time.Time | The ending date used to return pick list records that were printed within a specified period of time. (optional)
	truckArrivalTimeOfDayBegin := "string" // string | The beginning time of day used to return truck records that arrived within a specified period of time. (optional)
	truckArrivalTimeOfDayEnd := "string" // string | The beginning time of day used to return truck records that arrived within a specified period of time. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomerShippersAPIAPI.CustomerShippersApiListCustomerShippers(context.Background()).Id(id).ShipperNumber(shipperNumber).CustomerId(customerId).CustomerAddressId(customerAddressId).ShipDateBegin(shipDateBegin).ShipDateEnd(shipDateEnd).ShippedById(shippedById).CarrierId(carrierId).FreightTerms(freightTerms).Status(status).TrackingNumber(trackingNumber).TrailerNumber(trailerNumber).ScheduledShipDateBegin(scheduledShipDateBegin).ScheduledShipDateEnd(scheduledShipDateEnd).CreatedById(createdById).CreatedDateBegin(createdDateBegin).CreatedDateEnd(createdDateEnd).ModifiedById(modifiedById).ModifiedDateBegin(modifiedDateBegin).ModifiedDateEnd(modifiedDateEnd).TruckId(truckId).ExpediteReason(expediteReason).ExpediteDepartment(expediteDepartment).ExpediteAuthorizedById(expediteAuthorizedById).ShipFromCode(shipFromCode).TruckArrivalTimeBegin(truckArrivalTimeBegin).TruckArrivalTimeEnd(truckArrivalTimeEnd).PrintedById(printedById).PrintedDateBegin(printedDateBegin).PrintedDateEnd(printedDateEnd).PickListPrintedDateTimeBegin(pickListPrintedDateTimeBegin).PickListPrintedDateTimeEnd(pickListPrintedDateTimeEnd).TruckArrivalTimeOfDayBegin(truckArrivalTimeOfDayBegin).TruckArrivalTimeOfDayEnd(truckArrivalTimeOfDayEnd).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomerShippersAPIAPI.CustomerShippersApiListCustomerShippers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomerShippersApiListCustomerShippers`: []CustomerShippersApiListCustomerShippersItem
	fmt.Fprintf(os.Stdout, "Response from `CustomerShippersAPIAPI.CustomerShippersApiListCustomerShippers`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCustomerShippersApiListCustomerShippersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **[]string** | One or more customer shipper line IDs. | 
 **shipperNumber** | **string** | The shipper number associated with a given shipment. | 
 **customerId** | **string** | The ID of the customer that is associated with the shipper. | 
 **customerAddressId** | **string** | The ID of the customer address that is associated with the shipper. | 
 **shipDateBegin** | **time.Time** | The date on which the shipper was shipped. | 
 **shipDateEnd** | **time.Time** | The date on which the shipper was shipped. | 
 **shippedById** | **string** | The ID of the user who shipped the shipper. | 
 **carrierId** | **string** | The supplier ID that is flagged as the carrier on this shipment. | 
 **freightTerms** | **string** | Terms of the freight payment; for example, COD, Collect, or Prepaid. | 
 **status** | **string** | The shipper&#39;s status. | 
 **trackingNumber** | **string** | The tracking number, often provided by a carrier, that is specified on the shipper. | 
 **trailerNumber** | **string** | The trailer number associated with the physical trailer that a specific shipment was shipped on. | 
 **scheduledShipDateBegin** | **time.Time** | The beginning date used to return shipper records that were scheduled to ship during a specified period of time. | 
 **scheduledShipDateEnd** | **time.Time** | The ending date used to return shipper records that were scheduled to ship during a specified period of time. | 
 **createdById** | **string** | The ID of the user who created the record. | 
 **createdDateBegin** | **time.Time** | The beginning date used to return shipper records that were created during a specified period of time. | 
 **createdDateEnd** | **time.Time** | The ending date used to return shipper records that were created during a specified period of time. | 
 **modifiedById** | **string** | The ID of the user who last modified the record. | 
 **modifiedDateBegin** | **time.Time** | The beginning date used to return shipper records that were last modified within a specified period of time. | 
 **modifiedDateEnd** | **time.Time** | The ending date used to return shipper records that were last modified within a specified period of time. | 
 **truckId** | **string** | The ID of the truck associated with the shipper. | 
 **expediteReason** | **string** | The reason for expedited shipping as specified on the shipper. | 
 **expediteDepartment** | **string** | The department that authorized or required an expedited shipment. | 
 **expediteAuthorizedById** | **string** | The ID of the user who authorized the expedited shipping. | 
 **shipFromCode** | **string** | The building code from which the shipper was shipped. | 
 **truckArrivalTimeBegin** | **time.Time** | This field has been deprecated. Use TruckArrivalTimeOfDayBegin. | 
 **truckArrivalTimeEnd** | **time.Time** | This field has been deprecated. Use TruckArrivalTimeOfDayEnd. | 
 **printedById** | **string** | The ID of the user who printed the record. | 
 **printedDateBegin** | **time.Time** | The beginning date used to return records that were printed within a specified period of time. | 
 **printedDateEnd** | **time.Time** | The ending date used to return records that were printed within a specified period of time. | 
 **pickListPrintedDateTimeBegin** | **time.Time** | The beginning date used to return pick list records that were printed within a specified period of time. | 
 **pickListPrintedDateTimeEnd** | **time.Time** | The ending date used to return pick list records that were printed within a specified period of time. | 
 **truckArrivalTimeOfDayBegin** | **string** | The beginning time of day used to return truck records that arrived within a specified period of time. | 
 **truckArrivalTimeOfDayEnd** | **string** | The beginning time of day used to return truck records that arrived within a specified period of time. | 

### Return type

[**[]CustomerShippersApiListCustomerShippersItem**](CustomerShippersApiListCustomerShippersItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomerShippersApiLoadContainer

> CustomerShippersApiLoadContainerResponse CustomerShippersApiLoadContainer(ctx, shipperId, lineId).CustomerShippersApiLoadContainerRequest(customerShippersApiLoadContainerRequest).Execute()

Load Container



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
	shipperId := "00000000-0000-0000-0000-000000000000" // string | The shipper id.
	lineId := "00000000-0000-0000-0000-000000000000" // string | The line id.
	customerShippersApiLoadContainerRequest := *openapiclient.NewCustomerShippersApiLoadContainerRequest() // CustomerShippersApiLoadContainerRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomerShippersAPIAPI.CustomerShippersApiLoadContainer(context.Background(), shipperId, lineId).CustomerShippersApiLoadContainerRequest(customerShippersApiLoadContainerRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomerShippersAPIAPI.CustomerShippersApiLoadContainer``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomerShippersApiLoadContainer`: CustomerShippersApiLoadContainerResponse
	fmt.Fprintf(os.Stdout, "Response from `CustomerShippersAPIAPI.CustomerShippersApiLoadContainer`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**shipperId** | **string** | The shipper id. | 
**lineId** | **string** | The line id. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustomerShippersApiLoadContainerRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **customerShippersApiLoadContainerRequest** | [**CustomerShippersApiLoadContainerRequest**](CustomerShippersApiLoadContainerRequest.md) |  | 

### Return type

[**CustomerShippersApiLoadContainerResponse**](CustomerShippersApiLoadContainerResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomerShippersApiLoadShipperLineFIFO

> CustomerShippersApiLoadShipperLineFIFOResponse CustomerShippersApiLoadShipperLineFIFO(ctx, shipperId, lineId).Execute()

Load Shipper Line FIFO



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
	shipperId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the shipper.
	lineId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the shipper line.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomerShippersAPIAPI.CustomerShippersApiLoadShipperLineFIFO(context.Background(), shipperId, lineId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomerShippersAPIAPI.CustomerShippersApiLoadShipperLineFIFO``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomerShippersApiLoadShipperLineFIFO`: CustomerShippersApiLoadShipperLineFIFOResponse
	fmt.Fprintf(os.Stdout, "Response from `CustomerShippersAPIAPI.CustomerShippersApiLoadShipperLineFIFO`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**shipperId** | **string** | A unique identifier for the shipper. | 
**lineId** | **string** | A unique identifier for the shipper line. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustomerShippersApiLoadShipperLineFIFORequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**CustomerShippersApiLoadShipperLineFIFOResponse**](CustomerShippersApiLoadShipperLineFIFOResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomerShippersApiScheduleReleases

> []CustomerShippersApiScheduleReleasesItem CustomerShippersApiScheduleReleases(ctx, id).CustomerShippersApiScheduleReleasesRequest(customerShippersApiScheduleReleasesRequest).Execute()

Schedule Releases



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
	id := "00000000-0000-0000-0000-000000000000" // string | The ID of the customer shipper to schedule releases against.
	customerShippersApiScheduleReleasesRequest := *openapiclient.NewCustomerShippersApiScheduleReleasesRequest() // CustomerShippersApiScheduleReleasesRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomerShippersAPIAPI.CustomerShippersApiScheduleReleases(context.Background(), id).CustomerShippersApiScheduleReleasesRequest(customerShippersApiScheduleReleasesRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomerShippersAPIAPI.CustomerShippersApiScheduleReleases``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomerShippersApiScheduleReleases`: []CustomerShippersApiScheduleReleasesItem
	fmt.Fprintf(os.Stdout, "Response from `CustomerShippersAPIAPI.CustomerShippersApiScheduleReleases`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The ID of the customer shipper to schedule releases against. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustomerShippersApiScheduleReleasesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **customerShippersApiScheduleReleasesRequest** | [**CustomerShippersApiScheduleReleasesRequest**](CustomerShippersApiScheduleReleasesRequest.md) |  | 

### Return type

[**[]CustomerShippersApiScheduleReleasesItem**](CustomerShippersApiScheduleReleasesItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomerShippersApiShipShipper

> CustomerShippersApiShipShipperResponse CustomerShippersApiShipShipper(ctx, shipperId).Execute()

Ship Shipper



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
	shipperId := "00000000-0000-0000-0000-000000000000" // string | The ID of the shipper being shipped.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomerShippersAPIAPI.CustomerShippersApiShipShipper(context.Background(), shipperId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomerShippersAPIAPI.CustomerShippersApiShipShipper``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomerShippersApiShipShipper`: CustomerShippersApiShipShipperResponse
	fmt.Fprintf(os.Stdout, "Response from `CustomerShippersAPIAPI.CustomerShippersApiShipShipper`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**shipperId** | **string** | The ID of the shipper being shipped. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustomerShippersApiShipShipperRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**CustomerShippersApiShipShipperResponse**](CustomerShippersApiShipShipperResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomerShippersApiUpdateShipper

> CustomerShippersApiUpdateShipperResponse CustomerShippersApiUpdateShipper(ctx, id).CustomerShippersApiUpdateShipperRequest(customerShippersApiUpdateShipperRequest).Execute()

Update Shipper



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
	id := "00000000-0000-0000-0000-000000000000" // string | The ID of customer shipper to be update.
	customerShippersApiUpdateShipperRequest := *openapiclient.NewCustomerShippersApiUpdateShipperRequest() // CustomerShippersApiUpdateShipperRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomerShippersAPIAPI.CustomerShippersApiUpdateShipper(context.Background(), id).CustomerShippersApiUpdateShipperRequest(customerShippersApiUpdateShipperRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomerShippersAPIAPI.CustomerShippersApiUpdateShipper``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomerShippersApiUpdateShipper`: CustomerShippersApiUpdateShipperResponse
	fmt.Fprintf(os.Stdout, "Response from `CustomerShippersAPIAPI.CustomerShippersApiUpdateShipper`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The ID of customer shipper to be update. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustomerShippersApiUpdateShipperRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **customerShippersApiUpdateShipperRequest** | [**CustomerShippersApiUpdateShipperRequest**](CustomerShippersApiUpdateShipperRequest.md) |  | 

### Return type

[**CustomerShippersApiUpdateShipperResponse**](CustomerShippersApiUpdateShipperResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

