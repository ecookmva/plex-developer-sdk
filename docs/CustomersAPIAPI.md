# \CustomersAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CustomersApiCreateCustomer**](CustomersAPIAPI.md#CustomersApiCreateCustomer) | **Post** /mdm/v1/customers | Create Customer
[**CustomersApiCreateCustomerAddress**](CustomersAPIAPI.md#CustomersApiCreateCustomerAddress) | **Post** /mdm/v1/customers/{customerId}/addresses | Create Customer Address
[**CustomersApiDeactivateCustomer**](CustomersAPIAPI.md#CustomersApiDeactivateCustomer) | **Post** /mdm/v1/customers/{id}/deactivate | Deactivate Customer
[**CustomersApiDeleteCustomerAddress**](CustomersAPIAPI.md#CustomersApiDeleteCustomerAddress) | **Delete** /mdm/v1/customers/{customerId}/addresses/{addressId} | Delete Customer Address
[**CustomersApiGetCustomer**](CustomersAPIAPI.md#CustomersApiGetCustomer) | **Get** /mdm/v1/customers/{id} | Get Customer
[**CustomersApiGetCustomerAddress**](CustomersAPIAPI.md#CustomersApiGetCustomerAddress) | **Get** /mdm/v1/customers/{customerId}/addresses/{addressId} | Get Customer Address
[**CustomersApiGetCustomerAddressesEDIDetails**](CustomersAPIAPI.md#CustomersApiGetCustomerAddressesEDIDetails) | **Get** /mdm/v1/customers/{customerId}/addresses/{addressId}/edi-details | Get Customer Addresses EDI Details
[**CustomersApiGetCustomerFinancials**](CustomersAPIAPI.md#CustomersApiGetCustomerFinancials) | **Get** /mdm/v1/customers/{id}/financials | Get Customer Financials
[**CustomersApiListCustomerAddresses**](CustomersAPIAPI.md#CustomersApiListCustomerAddresses) | **Get** /mdm/v1/customers/{customerId}/addresses | List Customer Addresses
[**CustomersApiListCustomers**](CustomersAPIAPI.md#CustomersApiListCustomers) | **Get** /mdm/v1/customers | List Customers
[**CustomersApiSyncCustomers**](CustomersAPIAPI.md#CustomersApiSyncCustomers) | **Post** /mdm/v1/customers/sync | Sync Customers
[**CustomersApiUpdateCustomer**](CustomersAPIAPI.md#CustomersApiUpdateCustomer) | **Put** /mdm/v1/customers/{id} | Update Customer
[**CustomersApiUpdateCustomerAddress**](CustomersAPIAPI.md#CustomersApiUpdateCustomerAddress) | **Put** /mdm/v1/customers/{customerId}/addresses/{addressId} | Update Customer Address
[**CustomersApiUpdateCustomerAddressEDIDetails**](CustomersAPIAPI.md#CustomersApiUpdateCustomerAddressEDIDetails) | **Put** /mdm/v1/customers/{customerId}/addresses/{addressId}/edi-details | Update Customer Address EDI Details
[**CustomersApiUpdateCustomerFinancials**](CustomersAPIAPI.md#CustomersApiUpdateCustomerFinancials) | **Put** /mdm/v1/customers/{id}/financials | Update Customer Financials



## CustomersApiCreateCustomer

> CustomersApiCreateCustomer201Response CustomersApiCreateCustomer(ctx).CustomersApiCreateCustomerRequest(customersApiCreateCustomerRequest).Execute()

Create Customer



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
	customersApiCreateCustomerRequest := *openapiclient.NewCustomersApiCreateCustomerRequest() // CustomersApiCreateCustomerRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomersAPIAPI.CustomersApiCreateCustomer(context.Background()).CustomersApiCreateCustomerRequest(customersApiCreateCustomerRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomersAPIAPI.CustomersApiCreateCustomer``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomersApiCreateCustomer`: CustomersApiCreateCustomer201Response
	fmt.Fprintf(os.Stdout, "Response from `CustomersAPIAPI.CustomersApiCreateCustomer`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCustomersApiCreateCustomerRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **customersApiCreateCustomerRequest** | [**CustomersApiCreateCustomerRequest**](CustomersApiCreateCustomerRequest.md) |  | 

### Return type

[**CustomersApiCreateCustomer201Response**](CustomersApiCreateCustomer201Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomersApiCreateCustomerAddress

> CustomersApiCreateCustomerAddress201Response CustomersApiCreateCustomerAddress(ctx, customerId).CustomersApiCreateCustomerAddressRequest(customersApiCreateCustomerAddressRequest).Execute()

Create Customer Address



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
	customerId := "00000000-0000-0000-0000-000000000000" // string | The customer ID.
	customersApiCreateCustomerAddressRequest := *openapiclient.NewCustomersApiCreateCustomerAddressRequest() // CustomersApiCreateCustomerAddressRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomersAPIAPI.CustomersApiCreateCustomerAddress(context.Background(), customerId).CustomersApiCreateCustomerAddressRequest(customersApiCreateCustomerAddressRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomersAPIAPI.CustomersApiCreateCustomerAddress``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomersApiCreateCustomerAddress`: CustomersApiCreateCustomerAddress201Response
	fmt.Fprintf(os.Stdout, "Response from `CustomersAPIAPI.CustomersApiCreateCustomerAddress`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**customerId** | **string** | The customer ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustomersApiCreateCustomerAddressRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **customersApiCreateCustomerAddressRequest** | [**CustomersApiCreateCustomerAddressRequest**](CustomersApiCreateCustomerAddressRequest.md) |  | 

### Return type

[**CustomersApiCreateCustomerAddress201Response**](CustomersApiCreateCustomerAddress201Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomersApiDeactivateCustomer

> CustomersApiDeactivateCustomer(ctx, id).Execute()

Deactivate Customer



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
	id := "00000000-0000-0000-0000-000000000000" // string | The customer ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.CustomersAPIAPI.CustomersApiDeactivateCustomer(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomersAPIAPI.CustomersApiDeactivateCustomer``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The customer ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustomersApiDeactivateCustomerRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomersApiDeleteCustomerAddress

> CustomersApiDeleteCustomerAddressResponse CustomersApiDeleteCustomerAddress(ctx, customerId, addressId).Execute()

Delete Customer Address



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
	customerId := "00000000-0000-0000-0000-000000000000" // string | The customer ID.
	addressId := "00000000-0000-0000-0000-000000000000" // string | The customer address ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomersAPIAPI.CustomersApiDeleteCustomerAddress(context.Background(), customerId, addressId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomersAPIAPI.CustomersApiDeleteCustomerAddress``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomersApiDeleteCustomerAddress`: CustomersApiDeleteCustomerAddressResponse
	fmt.Fprintf(os.Stdout, "Response from `CustomersAPIAPI.CustomersApiDeleteCustomerAddress`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**customerId** | **string** | The customer ID. | 
**addressId** | **string** | The customer address ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustomersApiDeleteCustomerAddressRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**CustomersApiDeleteCustomerAddressResponse**](CustomersApiDeleteCustomerAddressResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomersApiGetCustomer

> CustomersApiGetCustomerResponse CustomersApiGetCustomer(ctx, id).Execute()

Get Customer



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
	id := "00000000-0000-0000-0000-000000000000" // string | The customer ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomersAPIAPI.CustomersApiGetCustomer(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomersAPIAPI.CustomersApiGetCustomer``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomersApiGetCustomer`: CustomersApiGetCustomerResponse
	fmt.Fprintf(os.Stdout, "Response from `CustomersAPIAPI.CustomersApiGetCustomer`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The customer ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustomersApiGetCustomerRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**CustomersApiGetCustomerResponse**](CustomersApiGetCustomerResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomersApiGetCustomerAddress

> CustomersApiGetCustomerAddressResponse CustomersApiGetCustomerAddress(ctx, customerId, addressId).Execute()

Get Customer Address



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
	customerId := "00000000-0000-0000-0000-000000000000" // string | The customer ID.
	addressId := "00000000-0000-0000-0000-000000000000" // string | The customer address ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomersAPIAPI.CustomersApiGetCustomerAddress(context.Background(), customerId, addressId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomersAPIAPI.CustomersApiGetCustomerAddress``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomersApiGetCustomerAddress`: CustomersApiGetCustomerAddressResponse
	fmt.Fprintf(os.Stdout, "Response from `CustomersAPIAPI.CustomersApiGetCustomerAddress`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**customerId** | **string** | The customer ID. | 
**addressId** | **string** | The customer address ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustomersApiGetCustomerAddressRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**CustomersApiGetCustomerAddressResponse**](CustomersApiGetCustomerAddressResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomersApiGetCustomerAddressesEDIDetails

> CustomersApiGetCustomerAddressesEDIDetailsResponse CustomersApiGetCustomerAddressesEDIDetails(ctx, customerId, addressId).Execute()

Get Customer Addresses EDI Details



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
	customerId := "00000000-0000-0000-0000-000000000000" // string | The customer ID.
	addressId := "00000000-0000-0000-0000-000000000000" // string | The customer address ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomersAPIAPI.CustomersApiGetCustomerAddressesEDIDetails(context.Background(), customerId, addressId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomersAPIAPI.CustomersApiGetCustomerAddressesEDIDetails``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomersApiGetCustomerAddressesEDIDetails`: CustomersApiGetCustomerAddressesEDIDetailsResponse
	fmt.Fprintf(os.Stdout, "Response from `CustomersAPIAPI.CustomersApiGetCustomerAddressesEDIDetails`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**customerId** | **string** | The customer ID. | 
**addressId** | **string** | The customer address ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustomersApiGetCustomerAddressesEDIDetailsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**CustomersApiGetCustomerAddressesEDIDetailsResponse**](CustomersApiGetCustomerAddressesEDIDetailsResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomersApiGetCustomerFinancials

> CustomersApiGetCustomerFinancialsResponse CustomersApiGetCustomerFinancials(ctx, id).Execute()

Get Customer Financials



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
	id := "00000000-0000-0000-0000-000000000000" // string | The customer ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomersAPIAPI.CustomersApiGetCustomerFinancials(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomersAPIAPI.CustomersApiGetCustomerFinancials``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomersApiGetCustomerFinancials`: CustomersApiGetCustomerFinancialsResponse
	fmt.Fprintf(os.Stdout, "Response from `CustomersAPIAPI.CustomersApiGetCustomerFinancials`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The customer ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustomersApiGetCustomerFinancialsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**CustomersApiGetCustomerFinancialsResponse**](CustomersApiGetCustomerFinancialsResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomersApiListCustomerAddresses

> []CustomersApiListCustomerAddressesItem CustomersApiListCustomerAddresses(ctx, customerId).Id(id).Code(code).QuoteTo(quoteTo).ShipTo(shipTo).BillTo(billTo).RemitTo(remitTo).ThirdPartyShipTo(thirdPartyShipTo).Pool(pool).OldCustomerNo(oldCustomerNo).Active(active).ModifiedDateBegin(modifiedDateBegin).ModifiedDateEnd(modifiedDateEnd).Execute()

List Customer Addresses



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
	customerId := "00000000-0000-0000-0000-000000000000" // string | The customer ID.
	id := []string{"00000000-0000-0000-0000-000000000000"} // []string | A List of CustomerAddress Resource Ids. (optional)
	code := "string" // string |  (optional)
	quoteTo := false // bool | If true, this address may be used for customer quotes. (optional)
	shipTo := false // bool | If true, this address may be used for customer shipping. (optional)
	billTo := false // bool | If true, this address may be used for customer invoices. (optional)
	remitTo := false // bool | If true, this address may be used for remittance. (optional)
	thirdPartyShipTo := false // bool | If true, this is a valid third-party shipping address. (optional)
	pool := false // bool | If true, this is a valid pool address. A pool is a location used to organize shipments and routes the shippers to the Ship To location. (optional)
	oldCustomerNo := "string" // string |  (optional)
	active := false // bool |  (optional)
	modifiedDateBegin := time.Now() // time.Time | The beginning date and time to use for records that were last modified within a time frame. (optional)
	modifiedDateEnd := time.Now() // time.Time | The ending date and time to use for records that were last modified within a time frame. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomersAPIAPI.CustomersApiListCustomerAddresses(context.Background(), customerId).Id(id).Code(code).QuoteTo(quoteTo).ShipTo(shipTo).BillTo(billTo).RemitTo(remitTo).ThirdPartyShipTo(thirdPartyShipTo).Pool(pool).OldCustomerNo(oldCustomerNo).Active(active).ModifiedDateBegin(modifiedDateBegin).ModifiedDateEnd(modifiedDateEnd).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomersAPIAPI.CustomersApiListCustomerAddresses``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomersApiListCustomerAddresses`: []CustomersApiListCustomerAddressesItem
	fmt.Fprintf(os.Stdout, "Response from `CustomersAPIAPI.CustomersApiListCustomerAddresses`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**customerId** | **string** | The customer ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustomersApiListCustomerAddressesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **id** | **[]string** | A List of CustomerAddress Resource Ids. | 
 **code** | **string** |  | 
 **quoteTo** | **bool** | If true, this address may be used for customer quotes. | 
 **shipTo** | **bool** | If true, this address may be used for customer shipping. | 
 **billTo** | **bool** | If true, this address may be used for customer invoices. | 
 **remitTo** | **bool** | If true, this address may be used for remittance. | 
 **thirdPartyShipTo** | **bool** | If true, this is a valid third-party shipping address. | 
 **pool** | **bool** | If true, this is a valid pool address. A pool is a location used to organize shipments and routes the shippers to the Ship To location. | 
 **oldCustomerNo** | **string** |  | 
 **active** | **bool** |  | 
 **modifiedDateBegin** | **time.Time** | The beginning date and time to use for records that were last modified within a time frame. | 
 **modifiedDateEnd** | **time.Time** | The ending date and time to use for records that were last modified within a time frame. | 

### Return type

[**[]CustomersApiListCustomerAddressesItem**](CustomersApiListCustomerAddressesItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomersApiListCustomers

> []CustomersApiListCustomersItem CustomersApiListCustomers(ctx).Id(id).Code(code).Name(name).Status(status).Type_(type_).OtherCustomerCode(otherCustomerCode).Rating(rating).Industries(industries).Region(region).Category(category).Class(class).Catalog(catalog).AssignedToId(assignedToId).AssignedTo2Id(assignedTo2Id).AssignedTo3Id(assignedTo3Id).AssignedToGroup(assignedToGroup).ContactResourceID(contactResourceID).TrackingNoOnWeighScaleRequired(trackingNoOnWeighScaleRequired).EstimatedAnnualSales(estimatedAnnualSales).ModifiedDateBegin(modifiedDateBegin).ModifiedDateEnd(modifiedDateEnd).Execute()

List Customers



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
	id := []string{"00000000-0000-0000-0000-000000000000"} // []string | A list of customer IDs. (optional)
	code := "string" // string |  (optional)
	name := "string" // string |  (optional)
	status := "string" // string | Setup Table: Customer Status (optional)
	type_ := "string" // string | Setup Table: Customer Type (optional)
	otherCustomerCode := "string" // string |  (optional)
	rating := "string" // string | Setup Table: Customer Rating (optional)
	industries := []string{"string"} // []string | Setup Table: Industries (optional)
	region := "string" // string | Screen: Region List (optional)
	category := "string" // string | Setup Table: Customer Category (optional)
	class := "string" // string | Setup Table: Customer Class (optional)
	catalog := "string" // string | Screen: Catalogs (optional)
	assignedToId := "00000000-0000-0000-0000-000000000000" // string | The sales person assigned to this customer, by IAM Account ID. (optional)
	assignedTo2Id := "00000000-0000-0000-0000-000000000000" // string | The sales person assigned to this customer, by IAM Account ID. (optional)
	assignedTo3Id := "00000000-0000-0000-0000-000000000000" // string | The sales person assigned to this customer, by IAM Account ID. (optional)
	assignedToGroup := "string" // string |  (optional)
	contactResourceID := "00000000-0000-0000-0000-000000000000" // string | The  Contact_Id of the sales person assigned to this Customer. (optional)
	trackingNoOnWeighScaleRequired := false // bool |  (optional)
	estimatedAnnualSales := "string" // string |  (optional)
	modifiedDateBegin := time.Now() // time.Time | The beginning date on which the record was last modified. (optional)
	modifiedDateEnd := time.Now() // time.Time | The ending date on which the record was last modified. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomersAPIAPI.CustomersApiListCustomers(context.Background()).Id(id).Code(code).Name(name).Status(status).Type_(type_).OtherCustomerCode(otherCustomerCode).Rating(rating).Industries(industries).Region(region).Category(category).Class(class).Catalog(catalog).AssignedToId(assignedToId).AssignedTo2Id(assignedTo2Id).AssignedTo3Id(assignedTo3Id).AssignedToGroup(assignedToGroup).ContactResourceID(contactResourceID).TrackingNoOnWeighScaleRequired(trackingNoOnWeighScaleRequired).EstimatedAnnualSales(estimatedAnnualSales).ModifiedDateBegin(modifiedDateBegin).ModifiedDateEnd(modifiedDateEnd).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomersAPIAPI.CustomersApiListCustomers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomersApiListCustomers`: []CustomersApiListCustomersItem
	fmt.Fprintf(os.Stdout, "Response from `CustomersAPIAPI.CustomersApiListCustomers`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCustomersApiListCustomersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **[]string** | A list of customer IDs. | 
 **code** | **string** |  | 
 **name** | **string** |  | 
 **status** | **string** | Setup Table: Customer Status | 
 **type_** | **string** | Setup Table: Customer Type | 
 **otherCustomerCode** | **string** |  | 
 **rating** | **string** | Setup Table: Customer Rating | 
 **industries** | **[]string** | Setup Table: Industries | 
 **region** | **string** | Screen: Region List | 
 **category** | **string** | Setup Table: Customer Category | 
 **class** | **string** | Setup Table: Customer Class | 
 **catalog** | **string** | Screen: Catalogs | 
 **assignedToId** | **string** | The sales person assigned to this customer, by IAM Account ID. | 
 **assignedTo2Id** | **string** | The sales person assigned to this customer, by IAM Account ID. | 
 **assignedTo3Id** | **string** | The sales person assigned to this customer, by IAM Account ID. | 
 **assignedToGroup** | **string** |  | 
 **contactResourceID** | **string** | The  Contact_Id of the sales person assigned to this Customer. | 
 **trackingNoOnWeighScaleRequired** | **bool** |  | 
 **estimatedAnnualSales** | **string** |  | 
 **modifiedDateBegin** | **time.Time** | The beginning date on which the record was last modified. | 
 **modifiedDateEnd** | **time.Time** | The ending date on which the record was last modified. | 

### Return type

[**[]CustomersApiListCustomersItem**](CustomersApiListCustomersItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomersApiSyncCustomers

> CustomersApiSyncCustomers(ctx).CustomersApiSyncCustomersRequest(customersApiSyncCustomersRequest).Execute()

Sync Customers



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
	customersApiSyncCustomersRequest := *openapiclient.NewCustomersApiSyncCustomersRequest() // CustomersApiSyncCustomersRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.CustomersAPIAPI.CustomersApiSyncCustomers(context.Background()).CustomersApiSyncCustomersRequest(customersApiSyncCustomersRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomersAPIAPI.CustomersApiSyncCustomers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCustomersApiSyncCustomersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **customersApiSyncCustomersRequest** | [**CustomersApiSyncCustomersRequest**](CustomersApiSyncCustomersRequest.md) |  | 

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


## CustomersApiUpdateCustomer

> CustomersApiUpdateCustomerResponse CustomersApiUpdateCustomer(ctx, id).CustomersApiUpdateCustomerRequest(customersApiUpdateCustomerRequest).Execute()

Update Customer



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
	id := "00000000-0000-0000-0000-000000000000" // string | The customer ID.
	customersApiUpdateCustomerRequest := *openapiclient.NewCustomersApiUpdateCustomerRequest() // CustomersApiUpdateCustomerRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomersAPIAPI.CustomersApiUpdateCustomer(context.Background(), id).CustomersApiUpdateCustomerRequest(customersApiUpdateCustomerRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomersAPIAPI.CustomersApiUpdateCustomer``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomersApiUpdateCustomer`: CustomersApiUpdateCustomerResponse
	fmt.Fprintf(os.Stdout, "Response from `CustomersAPIAPI.CustomersApiUpdateCustomer`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The customer ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustomersApiUpdateCustomerRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **customersApiUpdateCustomerRequest** | [**CustomersApiUpdateCustomerRequest**](CustomersApiUpdateCustomerRequest.md) |  | 

### Return type

[**CustomersApiUpdateCustomerResponse**](CustomersApiUpdateCustomerResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomersApiUpdateCustomerAddress

> CustomersApiUpdateCustomerAddressResponse CustomersApiUpdateCustomerAddress(ctx, customerId, addressId).CustomersApiUpdateCustomerAddressRequest(customersApiUpdateCustomerAddressRequest).Execute()

Update Customer Address



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
	customerId := "00000000-0000-0000-0000-000000000000" // string | The customer ID.
	addressId := "00000000-0000-0000-0000-000000000000" // string | The customer address ID.
	customersApiUpdateCustomerAddressRequest := *openapiclient.NewCustomersApiUpdateCustomerAddressRequest() // CustomersApiUpdateCustomerAddressRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomersAPIAPI.CustomersApiUpdateCustomerAddress(context.Background(), customerId, addressId).CustomersApiUpdateCustomerAddressRequest(customersApiUpdateCustomerAddressRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomersAPIAPI.CustomersApiUpdateCustomerAddress``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomersApiUpdateCustomerAddress`: CustomersApiUpdateCustomerAddressResponse
	fmt.Fprintf(os.Stdout, "Response from `CustomersAPIAPI.CustomersApiUpdateCustomerAddress`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**customerId** | **string** | The customer ID. | 
**addressId** | **string** | The customer address ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustomersApiUpdateCustomerAddressRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **customersApiUpdateCustomerAddressRequest** | [**CustomersApiUpdateCustomerAddressRequest**](CustomersApiUpdateCustomerAddressRequest.md) |  | 

### Return type

[**CustomersApiUpdateCustomerAddressResponse**](CustomersApiUpdateCustomerAddressResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomersApiUpdateCustomerAddressEDIDetails

> CustomersApiUpdateCustomerAddressEDIDetailsResponse CustomersApiUpdateCustomerAddressEDIDetails(ctx, customerId, addressId).CustomersApiUpdateCustomerAddressEDIDetailsRequest(customersApiUpdateCustomerAddressEDIDetailsRequest).Execute()

Update Customer Address EDI Details



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
	customerId := "00000000-0000-0000-0000-000000000000" // string | The customer ID.
	addressId := "00000000-0000-0000-0000-000000000000" // string | The customer address ID.
	customersApiUpdateCustomerAddressEDIDetailsRequest := *openapiclient.NewCustomersApiUpdateCustomerAddressEDIDetailsRequest() // CustomersApiUpdateCustomerAddressEDIDetailsRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomersAPIAPI.CustomersApiUpdateCustomerAddressEDIDetails(context.Background(), customerId, addressId).CustomersApiUpdateCustomerAddressEDIDetailsRequest(customersApiUpdateCustomerAddressEDIDetailsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomersAPIAPI.CustomersApiUpdateCustomerAddressEDIDetails``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomersApiUpdateCustomerAddressEDIDetails`: CustomersApiUpdateCustomerAddressEDIDetailsResponse
	fmt.Fprintf(os.Stdout, "Response from `CustomersAPIAPI.CustomersApiUpdateCustomerAddressEDIDetails`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**customerId** | **string** | The customer ID. | 
**addressId** | **string** | The customer address ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustomersApiUpdateCustomerAddressEDIDetailsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **customersApiUpdateCustomerAddressEDIDetailsRequest** | [**CustomersApiUpdateCustomerAddressEDIDetailsRequest**](CustomersApiUpdateCustomerAddressEDIDetailsRequest.md) |  | 

### Return type

[**CustomersApiUpdateCustomerAddressEDIDetailsResponse**](CustomersApiUpdateCustomerAddressEDIDetailsResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomersApiUpdateCustomerFinancials

> CustomersApiUpdateCustomerFinancialsResponse CustomersApiUpdateCustomerFinancials(ctx, id).CustomersApiUpdateCustomerFinancialsRequest(customersApiUpdateCustomerFinancialsRequest).Execute()

Update Customer Financials



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
	id := "00000000-0000-0000-0000-000000000000" // string | The customer ID.
	customersApiUpdateCustomerFinancialsRequest := *openapiclient.NewCustomersApiUpdateCustomerFinancialsRequest() // CustomersApiUpdateCustomerFinancialsRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomersAPIAPI.CustomersApiUpdateCustomerFinancials(context.Background(), id).CustomersApiUpdateCustomerFinancialsRequest(customersApiUpdateCustomerFinancialsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomersAPIAPI.CustomersApiUpdateCustomerFinancials``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomersApiUpdateCustomerFinancials`: CustomersApiUpdateCustomerFinancialsResponse
	fmt.Fprintf(os.Stdout, "Response from `CustomersAPIAPI.CustomersApiUpdateCustomerFinancials`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The customer ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustomersApiUpdateCustomerFinancialsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **customersApiUpdateCustomerFinancialsRequest** | [**CustomersApiUpdateCustomerFinancialsRequest**](CustomersApiUpdateCustomerFinancialsRequest.md) |  | 

### Return type

[**CustomersApiUpdateCustomerFinancialsResponse**](CustomersApiUpdateCustomerFinancialsResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

