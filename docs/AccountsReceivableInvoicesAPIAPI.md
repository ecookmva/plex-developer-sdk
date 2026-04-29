# \AccountsReceivableInvoicesAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AccountsReceivableInvoicesApiCreateARInvoice**](AccountsReceivableInvoicesAPIAPI.md#AccountsReceivableInvoicesApiCreateARInvoice) | **Post** /accounting/v1/ar-invoices | Create AR Invoice
[**AccountsReceivableInvoicesApiGetARInvoice**](AccountsReceivableInvoicesAPIAPI.md#AccountsReceivableInvoicesApiGetARInvoice) | **Get** /accounting/v1/ar-invoices/{id} | Get AR Invoice
[**AccountsReceivableInvoicesApiListARInvoices**](AccountsReceivableInvoicesAPIAPI.md#AccountsReceivableInvoicesApiListARInvoices) | **Get** /accounting/v1/ar-invoices | List AR Invoices
[**AccountsReceivableInvoicesApiUpdateARInvoice**](AccountsReceivableInvoicesAPIAPI.md#AccountsReceivableInvoicesApiUpdateARInvoice) | **Put** /accounting/v1/ar-invoices/{id} | Update AR Invoice



## AccountsReceivableInvoicesApiCreateARInvoice

> AccountsReceivableInvoicesApiCreateARInvoice201Response AccountsReceivableInvoicesApiCreateARInvoice(ctx).AccountsReceivableInvoicesApiCreateARInvoiceRequest(accountsReceivableInvoicesApiCreateARInvoiceRequest).Execute()

Create AR Invoice



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
	accountsReceivableInvoicesApiCreateARInvoiceRequest := *openapiclient.NewAccountsReceivableInvoicesApiCreateARInvoiceRequest() // AccountsReceivableInvoicesApiCreateARInvoiceRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AccountsReceivableInvoicesAPIAPI.AccountsReceivableInvoicesApiCreateARInvoice(context.Background()).AccountsReceivableInvoicesApiCreateARInvoiceRequest(accountsReceivableInvoicesApiCreateARInvoiceRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AccountsReceivableInvoicesAPIAPI.AccountsReceivableInvoicesApiCreateARInvoice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AccountsReceivableInvoicesApiCreateARInvoice`: AccountsReceivableInvoicesApiCreateARInvoice201Response
	fmt.Fprintf(os.Stdout, "Response from `AccountsReceivableInvoicesAPIAPI.AccountsReceivableInvoicesApiCreateARInvoice`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiAccountsReceivableInvoicesApiCreateARInvoiceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accountsReceivableInvoicesApiCreateARInvoiceRequest** | [**AccountsReceivableInvoicesApiCreateARInvoiceRequest**](AccountsReceivableInvoicesApiCreateARInvoiceRequest.md) |  | 

### Return type

[**AccountsReceivableInvoicesApiCreateARInvoice201Response**](AccountsReceivableInvoicesApiCreateARInvoice201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## AccountsReceivableInvoicesApiGetARInvoice

> AccountsReceivableInvoicesApiGetARInvoiceResponse AccountsReceivableInvoicesApiGetARInvoice(ctx, id).Execute()

Get AR Invoice



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
	id := "00000000-0000-0000-0000-000000000000" // string | The Accounts Receivable invoice ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AccountsReceivableInvoicesAPIAPI.AccountsReceivableInvoicesApiGetARInvoice(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AccountsReceivableInvoicesAPIAPI.AccountsReceivableInvoicesApiGetARInvoice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AccountsReceivableInvoicesApiGetARInvoice`: AccountsReceivableInvoicesApiGetARInvoiceResponse
	fmt.Fprintf(os.Stdout, "Response from `AccountsReceivableInvoicesAPIAPI.AccountsReceivableInvoicesApiGetARInvoice`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The Accounts Receivable invoice ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiAccountsReceivableInvoicesApiGetARInvoiceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AccountsReceivableInvoicesApiGetARInvoiceResponse**](AccountsReceivableInvoicesApiGetARInvoiceResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## AccountsReceivableInvoicesApiListARInvoices

> []AccountsReceivableInvoicesApiListARInvoicesItem AccountsReceivableInvoicesApiListARInvoices(ctx).Id(id).InvoiceNumber(invoiceNumber).PeriodDisplayBegin(periodDisplayBegin).PeriodDisplayEnd(periodDisplayEnd).TransactionDateBegin(transactionDateBegin).TransactionDateEnd(transactionDateEnd).CreatedDateBegin(createdDateBegin).CreatedDateEnd(createdDateEnd).Booked(booked).ModifiedDateBegin(modifiedDateBegin).ModifiedDateEnd(modifiedDateEnd).CustomerCode(customerCode).CustomerPONo(customerPONo).Status(status).Paid(paid).Void(void).Execute()

List AR Invoices



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
	id := []string{"00000000-0000-0000-0000-000000000000"} // []string | The ID of the AR invoice. (optional)
	invoiceNumber := "string" // string | The AR invoice number. (optional)
	periodDisplayBegin := "string" // string | The beginning date used to return AR invoice records during a period. (optional)
	periodDisplayEnd := "string" // string | The end date used to return AR invoice records during a period. (optional)
	transactionDateBegin := time.Now() // time.Time | The beginning date used to return AR transaction records during a period. (optional)
	transactionDateEnd := time.Now() // time.Time | The end date used to return AR transaction records during a period. (optional)
	createdDateBegin := time.Now() // time.Time | The beginning date used to return AR invoices created within a time frame. (optional)
	createdDateEnd := time.Now() // time.Time | The end date used to return AR invoices created within a time frame. (optional)
	booked := false // bool | Specify that an AR invoice has a booked status. (optional)
	modifiedDateBegin := time.Now() // time.Time | The beginning date used to return AR invoices modified within a time frame. (optional)
	modifiedDateEnd := time.Now() // time.Time | The end date used to return AR invoices modified within a time frame. (optional)
	customerCode := "string" // string | The AR invoice customer code. (optional)
	customerPONo := "string" // string | The AR invoice customer purchase order number. (optional)
	status := "string" // string | The AR invoice status. (optional)
	paid := int32(0) // int32 | Specify whether or not the AR invoices in your query results have been paid by entering one of the following: 0 - Unpaid invoices only, 1 - Fully paid invoices only, 2 - Partially paid invoices only, 3 - All invoices. (optional)
	void := false // bool | Specify that the AR invoice is void. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AccountsReceivableInvoicesAPIAPI.AccountsReceivableInvoicesApiListARInvoices(context.Background()).Id(id).InvoiceNumber(invoiceNumber).PeriodDisplayBegin(periodDisplayBegin).PeriodDisplayEnd(periodDisplayEnd).TransactionDateBegin(transactionDateBegin).TransactionDateEnd(transactionDateEnd).CreatedDateBegin(createdDateBegin).CreatedDateEnd(createdDateEnd).Booked(booked).ModifiedDateBegin(modifiedDateBegin).ModifiedDateEnd(modifiedDateEnd).CustomerCode(customerCode).CustomerPONo(customerPONo).Status(status).Paid(paid).Void(void).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AccountsReceivableInvoicesAPIAPI.AccountsReceivableInvoicesApiListARInvoices``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AccountsReceivableInvoicesApiListARInvoices`: []AccountsReceivableInvoicesApiListARInvoicesItem
	fmt.Fprintf(os.Stdout, "Response from `AccountsReceivableInvoicesAPIAPI.AccountsReceivableInvoicesApiListARInvoices`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiAccountsReceivableInvoicesApiListARInvoicesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **[]string** | The ID of the AR invoice. | 
 **invoiceNumber** | **string** | The AR invoice number. | 
 **periodDisplayBegin** | **string** | The beginning date used to return AR invoice records during a period. | 
 **periodDisplayEnd** | **string** | The end date used to return AR invoice records during a period. | 
 **transactionDateBegin** | **time.Time** | The beginning date used to return AR transaction records during a period. | 
 **transactionDateEnd** | **time.Time** | The end date used to return AR transaction records during a period. | 
 **createdDateBegin** | **time.Time** | The beginning date used to return AR invoices created within a time frame. | 
 **createdDateEnd** | **time.Time** | The end date used to return AR invoices created within a time frame. | 
 **booked** | **bool** | Specify that an AR invoice has a booked status. | 
 **modifiedDateBegin** | **time.Time** | The beginning date used to return AR invoices modified within a time frame. | 
 **modifiedDateEnd** | **time.Time** | The end date used to return AR invoices modified within a time frame. | 
 **customerCode** | **string** | The AR invoice customer code. | 
 **customerPONo** | **string** | The AR invoice customer purchase order number. | 
 **status** | **string** | The AR invoice status. | 
 **paid** | **int32** | Specify whether or not the AR invoices in your query results have been paid by entering one of the following: 0 - Unpaid invoices only, 1 - Fully paid invoices only, 2 - Partially paid invoices only, 3 - All invoices. | 
 **void** | **bool** | Specify that the AR invoice is void. | 

### Return type

[**[]AccountsReceivableInvoicesApiListARInvoicesItem**](AccountsReceivableInvoicesApiListARInvoicesItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## AccountsReceivableInvoicesApiUpdateARInvoice

> AccountsReceivableInvoicesApiUpdateARInvoiceResponse AccountsReceivableInvoicesApiUpdateARInvoice(ctx, id).AccountsReceivableInvoicesApiUpdateARInvoiceRequest(accountsReceivableInvoicesApiUpdateARInvoiceRequest).Execute()

Update AR Invoice



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
	accountsReceivableInvoicesApiUpdateARInvoiceRequest := *openapiclient.NewAccountsReceivableInvoicesApiUpdateARInvoiceRequest() // AccountsReceivableInvoicesApiUpdateARInvoiceRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AccountsReceivableInvoicesAPIAPI.AccountsReceivableInvoicesApiUpdateARInvoice(context.Background(), id).AccountsReceivableInvoicesApiUpdateARInvoiceRequest(accountsReceivableInvoicesApiUpdateARInvoiceRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AccountsReceivableInvoicesAPIAPI.AccountsReceivableInvoicesApiUpdateARInvoice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AccountsReceivableInvoicesApiUpdateARInvoice`: AccountsReceivableInvoicesApiUpdateARInvoiceResponse
	fmt.Fprintf(os.Stdout, "Response from `AccountsReceivableInvoicesAPIAPI.AccountsReceivableInvoicesApiUpdateARInvoice`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiAccountsReceivableInvoicesApiUpdateARInvoiceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **accountsReceivableInvoicesApiUpdateARInvoiceRequest** | [**AccountsReceivableInvoicesApiUpdateARInvoiceRequest**](AccountsReceivableInvoicesApiUpdateARInvoiceRequest.md) |  | 

### Return type

[**AccountsReceivableInvoicesApiUpdateARInvoiceResponse**](AccountsReceivableInvoicesApiUpdateARInvoiceResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

