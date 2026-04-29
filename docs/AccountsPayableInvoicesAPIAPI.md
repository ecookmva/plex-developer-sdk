# \AccountsPayableInvoicesAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AccountsPayableInvoicesApiCreateAPInvoice**](AccountsPayableInvoicesAPIAPI.md#AccountsPayableInvoicesApiCreateAPInvoice) | **Post** /accounting/v1/ap-invoices | Create AP Invoice
[**AccountsPayableInvoicesApiGetAPInvoice**](AccountsPayableInvoicesAPIAPI.md#AccountsPayableInvoicesApiGetAPInvoice) | **Get** /accounting/v1/ap-invoices/{id} | Get AP Invoice
[**AccountsPayableInvoicesApiLinkReceiptsWithAPInvoice**](AccountsPayableInvoicesAPIAPI.md#AccountsPayableInvoicesApiLinkReceiptsWithAPInvoice) | **Post** /accounting/v1/ap-invoices/{id}/linkreceipts | Link Receipts With AP Invoice
[**AccountsPayableInvoicesApiListAPInvoices**](AccountsPayableInvoicesAPIAPI.md#AccountsPayableInvoicesApiListAPInvoices) | **Get** /accounting/v1/ap-invoices | List AP Invoices
[**AccountsPayableInvoicesApiUnlinkReceiptsFromAPInvoice**](AccountsPayableInvoicesAPIAPI.md#AccountsPayableInvoicesApiUnlinkReceiptsFromAPInvoice) | **Post** /accounting/v1/ap-invoices/{id}/unlinkreceipts | Unlink Receipts From AP Invoice
[**AccountsPayableInvoicesApiUpdateAPInvoice**](AccountsPayableInvoicesAPIAPI.md#AccountsPayableInvoicesApiUpdateAPInvoice) | **Put** /accounting/v1/ap-invoices/{id} | Update AP Invoice



## AccountsPayableInvoicesApiCreateAPInvoice

> AccountsPayableInvoicesApiCreateAPInvoice201Response AccountsPayableInvoicesApiCreateAPInvoice(ctx).AccountsPayableInvoicesApiCreateAPInvoiceRequest(accountsPayableInvoicesApiCreateAPInvoiceRequest).Execute()

Create AP Invoice



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
	accountsPayableInvoicesApiCreateAPInvoiceRequest := *openapiclient.NewAccountsPayableInvoicesApiCreateAPInvoiceRequest() // AccountsPayableInvoicesApiCreateAPInvoiceRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AccountsPayableInvoicesAPIAPI.AccountsPayableInvoicesApiCreateAPInvoice(context.Background()).AccountsPayableInvoicesApiCreateAPInvoiceRequest(accountsPayableInvoicesApiCreateAPInvoiceRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AccountsPayableInvoicesAPIAPI.AccountsPayableInvoicesApiCreateAPInvoice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AccountsPayableInvoicesApiCreateAPInvoice`: AccountsPayableInvoicesApiCreateAPInvoice201Response
	fmt.Fprintf(os.Stdout, "Response from `AccountsPayableInvoicesAPIAPI.AccountsPayableInvoicesApiCreateAPInvoice`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiAccountsPayableInvoicesApiCreateAPInvoiceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accountsPayableInvoicesApiCreateAPInvoiceRequest** | [**AccountsPayableInvoicesApiCreateAPInvoiceRequest**](AccountsPayableInvoicesApiCreateAPInvoiceRequest.md) |  | 

### Return type

[**AccountsPayableInvoicesApiCreateAPInvoice201Response**](AccountsPayableInvoicesApiCreateAPInvoice201Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## AccountsPayableInvoicesApiGetAPInvoice

> AccountsPayableInvoicesApiGetAPInvoiceResponse AccountsPayableInvoicesApiGetAPInvoice(ctx, id).Execute()

Get AP Invoice



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
	id := "00000000-0000-0000-0000-000000000000" // string | The Accounts Payable invoice ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AccountsPayableInvoicesAPIAPI.AccountsPayableInvoicesApiGetAPInvoice(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AccountsPayableInvoicesAPIAPI.AccountsPayableInvoicesApiGetAPInvoice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AccountsPayableInvoicesApiGetAPInvoice`: AccountsPayableInvoicesApiGetAPInvoiceResponse
	fmt.Fprintf(os.Stdout, "Response from `AccountsPayableInvoicesAPIAPI.AccountsPayableInvoicesApiGetAPInvoice`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The Accounts Payable invoice ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiAccountsPayableInvoicesApiGetAPInvoiceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AccountsPayableInvoicesApiGetAPInvoiceResponse**](AccountsPayableInvoicesApiGetAPInvoiceResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## AccountsPayableInvoicesApiLinkReceiptsWithAPInvoice

> AccountsPayableInvoicesApiLinkReceiptsWithAPInvoiceResponse AccountsPayableInvoicesApiLinkReceiptsWithAPInvoice(ctx, id).AccountsPayableInvoicesApiLinkReceiptsWithAPInvoiceRequest(accountsPayableInvoicesApiLinkReceiptsWithAPInvoiceRequest).Execute()

Link Receipts With AP Invoice



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
	accountsPayableInvoicesApiLinkReceiptsWithAPInvoiceRequest := *openapiclient.NewAccountsPayableInvoicesApiLinkReceiptsWithAPInvoiceRequest() // AccountsPayableInvoicesApiLinkReceiptsWithAPInvoiceRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AccountsPayableInvoicesAPIAPI.AccountsPayableInvoicesApiLinkReceiptsWithAPInvoice(context.Background(), id).AccountsPayableInvoicesApiLinkReceiptsWithAPInvoiceRequest(accountsPayableInvoicesApiLinkReceiptsWithAPInvoiceRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AccountsPayableInvoicesAPIAPI.AccountsPayableInvoicesApiLinkReceiptsWithAPInvoice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AccountsPayableInvoicesApiLinkReceiptsWithAPInvoice`: AccountsPayableInvoicesApiLinkReceiptsWithAPInvoiceResponse
	fmt.Fprintf(os.Stdout, "Response from `AccountsPayableInvoicesAPIAPI.AccountsPayableInvoicesApiLinkReceiptsWithAPInvoice`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiAccountsPayableInvoicesApiLinkReceiptsWithAPInvoiceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **accountsPayableInvoicesApiLinkReceiptsWithAPInvoiceRequest** | [**AccountsPayableInvoicesApiLinkReceiptsWithAPInvoiceRequest**](AccountsPayableInvoicesApiLinkReceiptsWithAPInvoiceRequest.md) |  | 

### Return type

[**AccountsPayableInvoicesApiLinkReceiptsWithAPInvoiceResponse**](AccountsPayableInvoicesApiLinkReceiptsWithAPInvoiceResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## AccountsPayableInvoicesApiListAPInvoices

> []AccountsPayableInvoicesApiListAPInvoicesItem AccountsPayableInvoicesApiListAPInvoices(ctx).Id(id).InvoiceNumber(invoiceNumber).PeriodDisplayBegin(periodDisplayBegin).PeriodDisplayEnd(periodDisplayEnd).TransactionDateBegin(transactionDateBegin).TransactionDateEnd(transactionDateEnd).CreatedDateBegin(createdDateBegin).CreatedDateEnd(createdDateEnd).ModifiedDateBegin(modifiedDateBegin).ModifiedDateEnd(modifiedDateEnd).Booked(booked).SupplierCode(supplierCode).PoNumber(poNumber).ShipperNo(shipperNo).Status(status).ExternalReferenceCode(externalReferenceCode).Paid(paid).Execute()

List AP Invoices



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
	id := []string{"00000000-0000-0000-0000-000000000000"} // []string | The AP invoice ID. (optional)
	invoiceNumber := "string" // string | The AP invoice number. (optional)
	periodDisplayBegin := "string" // string | The beginning period used to return AP invoice records. (optional)
	periodDisplayEnd := "string" // string | The end period used to return AP invoice records. (optional)
	transactionDateBegin := time.Now() // time.Time | The beginning date used to return AP transaction records during a period. (optional)
	transactionDateEnd := time.Now() // time.Time | The end date used to return AP transaction records during a period. (optional)
	createdDateBegin := time.Now() // time.Time | The beginning date used to return AP invoices created within a time frame. (optional)
	createdDateEnd := time.Now() // time.Time | The end date used to return AP invoices created within a time frame. (optional)
	modifiedDateBegin := time.Now() // time.Time | The beginning date used to return AP invoices modified within a time frame. (optional)
	modifiedDateEnd := time.Now() // time.Time | The end date used to return AP invoices modified within a time frame. (optional)
	booked := false // bool | Specify that the AP invoice is booked. (optional)
	supplierCode := "string" // string | The AP invoice supplier code. (optional)
	poNumber := "string" // string | The AP invoice purchase order number. (optional)
	shipperNo := "string" // string | The AP invoice shipper number. (optional)
	status := "string" // string | The AP invoice status. (optional)
	externalReferenceCode := "string" // string | The AP invoice external reference code. (optional)
	paid := false // bool | Specify that the AP invoice is paid. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AccountsPayableInvoicesAPIAPI.AccountsPayableInvoicesApiListAPInvoices(context.Background()).Id(id).InvoiceNumber(invoiceNumber).PeriodDisplayBegin(periodDisplayBegin).PeriodDisplayEnd(periodDisplayEnd).TransactionDateBegin(transactionDateBegin).TransactionDateEnd(transactionDateEnd).CreatedDateBegin(createdDateBegin).CreatedDateEnd(createdDateEnd).ModifiedDateBegin(modifiedDateBegin).ModifiedDateEnd(modifiedDateEnd).Booked(booked).SupplierCode(supplierCode).PoNumber(poNumber).ShipperNo(shipperNo).Status(status).ExternalReferenceCode(externalReferenceCode).Paid(paid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AccountsPayableInvoicesAPIAPI.AccountsPayableInvoicesApiListAPInvoices``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AccountsPayableInvoicesApiListAPInvoices`: []AccountsPayableInvoicesApiListAPInvoicesItem
	fmt.Fprintf(os.Stdout, "Response from `AccountsPayableInvoicesAPIAPI.AccountsPayableInvoicesApiListAPInvoices`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiAccountsPayableInvoicesApiListAPInvoicesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **[]string** | The AP invoice ID. | 
 **invoiceNumber** | **string** | The AP invoice number. | 
 **periodDisplayBegin** | **string** | The beginning period used to return AP invoice records. | 
 **periodDisplayEnd** | **string** | The end period used to return AP invoice records. | 
 **transactionDateBegin** | **time.Time** | The beginning date used to return AP transaction records during a period. | 
 **transactionDateEnd** | **time.Time** | The end date used to return AP transaction records during a period. | 
 **createdDateBegin** | **time.Time** | The beginning date used to return AP invoices created within a time frame. | 
 **createdDateEnd** | **time.Time** | The end date used to return AP invoices created within a time frame. | 
 **modifiedDateBegin** | **time.Time** | The beginning date used to return AP invoices modified within a time frame. | 
 **modifiedDateEnd** | **time.Time** | The end date used to return AP invoices modified within a time frame. | 
 **booked** | **bool** | Specify that the AP invoice is booked. | 
 **supplierCode** | **string** | The AP invoice supplier code. | 
 **poNumber** | **string** | The AP invoice purchase order number. | 
 **shipperNo** | **string** | The AP invoice shipper number. | 
 **status** | **string** | The AP invoice status. | 
 **externalReferenceCode** | **string** | The AP invoice external reference code. | 
 **paid** | **bool** | Specify that the AP invoice is paid. | 

### Return type

[**[]AccountsPayableInvoicesApiListAPInvoicesItem**](AccountsPayableInvoicesApiListAPInvoicesItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## AccountsPayableInvoicesApiUnlinkReceiptsFromAPInvoice

> AccountsPayableInvoicesApiUnlinkReceiptsFromAPInvoiceResponse AccountsPayableInvoicesApiUnlinkReceiptsFromAPInvoice(ctx, id).AccountsPayableInvoicesApiUnlinkReceiptsFromAPInvoiceRequest(accountsPayableInvoicesApiUnlinkReceiptsFromAPInvoiceRequest).Execute()

Unlink Receipts From AP Invoice



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
	accountsPayableInvoicesApiUnlinkReceiptsFromAPInvoiceRequest := *openapiclient.NewAccountsPayableInvoicesApiUnlinkReceiptsFromAPInvoiceRequest() // AccountsPayableInvoicesApiUnlinkReceiptsFromAPInvoiceRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AccountsPayableInvoicesAPIAPI.AccountsPayableInvoicesApiUnlinkReceiptsFromAPInvoice(context.Background(), id).AccountsPayableInvoicesApiUnlinkReceiptsFromAPInvoiceRequest(accountsPayableInvoicesApiUnlinkReceiptsFromAPInvoiceRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AccountsPayableInvoicesAPIAPI.AccountsPayableInvoicesApiUnlinkReceiptsFromAPInvoice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AccountsPayableInvoicesApiUnlinkReceiptsFromAPInvoice`: AccountsPayableInvoicesApiUnlinkReceiptsFromAPInvoiceResponse
	fmt.Fprintf(os.Stdout, "Response from `AccountsPayableInvoicesAPIAPI.AccountsPayableInvoicesApiUnlinkReceiptsFromAPInvoice`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiAccountsPayableInvoicesApiUnlinkReceiptsFromAPInvoiceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **accountsPayableInvoicesApiUnlinkReceiptsFromAPInvoiceRequest** | [**AccountsPayableInvoicesApiUnlinkReceiptsFromAPInvoiceRequest**](AccountsPayableInvoicesApiUnlinkReceiptsFromAPInvoiceRequest.md) |  | 

### Return type

[**AccountsPayableInvoicesApiUnlinkReceiptsFromAPInvoiceResponse**](AccountsPayableInvoicesApiUnlinkReceiptsFromAPInvoiceResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## AccountsPayableInvoicesApiUpdateAPInvoice

> AccountsPayableInvoicesApiUpdateAPInvoiceResponse AccountsPayableInvoicesApiUpdateAPInvoice(ctx, id).AccountsPayableInvoicesApiUpdateAPInvoiceRequest(accountsPayableInvoicesApiUpdateAPInvoiceRequest).Execute()

Update AP Invoice



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
	accountsPayableInvoicesApiUpdateAPInvoiceRequest := *openapiclient.NewAccountsPayableInvoicesApiUpdateAPInvoiceRequest() // AccountsPayableInvoicesApiUpdateAPInvoiceRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AccountsPayableInvoicesAPIAPI.AccountsPayableInvoicesApiUpdateAPInvoice(context.Background(), id).AccountsPayableInvoicesApiUpdateAPInvoiceRequest(accountsPayableInvoicesApiUpdateAPInvoiceRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AccountsPayableInvoicesAPIAPI.AccountsPayableInvoicesApiUpdateAPInvoice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AccountsPayableInvoicesApiUpdateAPInvoice`: AccountsPayableInvoicesApiUpdateAPInvoiceResponse
	fmt.Fprintf(os.Stdout, "Response from `AccountsPayableInvoicesAPIAPI.AccountsPayableInvoicesApiUpdateAPInvoice`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiAccountsPayableInvoicesApiUpdateAPInvoiceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **accountsPayableInvoicesApiUpdateAPInvoiceRequest** | [**AccountsPayableInvoicesApiUpdateAPInvoiceRequest**](AccountsPayableInvoicesApiUpdateAPInvoiceRequest.md) |  | 

### Return type

[**AccountsPayableInvoicesApiUpdateAPInvoiceResponse**](AccountsPayableInvoicesApiUpdateAPInvoiceResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

