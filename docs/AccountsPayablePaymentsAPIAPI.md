# \AccountsPayablePaymentsAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AccountsPayablePaymentsApiGetAPPayment**](AccountsPayablePaymentsAPIAPI.md#AccountsPayablePaymentsApiGetAPPayment) | **Get** /accounting/v1/ap-payments/{id} | Get AP Payment
[**AccountsPayablePaymentsApiListAPPayments**](AccountsPayablePaymentsAPIAPI.md#AccountsPayablePaymentsApiListAPPayments) | **Get** /accounting/v1/ap-payments | List AP Payments



## AccountsPayablePaymentsApiGetAPPayment

> AccountsPayablePaymentsApiGetAPPaymentResponse AccountsPayablePaymentsApiGetAPPayment(ctx, id).Execute()

Get AP Payment



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
	id := "00000000-0000-0000-0000-000000000000" // string | The Accounts Payable Payment resource id.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AccountsPayablePaymentsAPIAPI.AccountsPayablePaymentsApiGetAPPayment(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AccountsPayablePaymentsAPIAPI.AccountsPayablePaymentsApiGetAPPayment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AccountsPayablePaymentsApiGetAPPayment`: AccountsPayablePaymentsApiGetAPPaymentResponse
	fmt.Fprintf(os.Stdout, "Response from `AccountsPayablePaymentsAPIAPI.AccountsPayablePaymentsApiGetAPPayment`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The Accounts Payable Payment resource id. | 

### Other Parameters

Other parameters are passed through a pointer to a apiAccountsPayablePaymentsApiGetAPPaymentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AccountsPayablePaymentsApiGetAPPaymentResponse**](AccountsPayablePaymentsApiGetAPPaymentResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## AccountsPayablePaymentsApiListAPPayments

> []AccountsPayablePaymentsApiListAPPaymentsItem AccountsPayablePaymentsApiListAPPayments(ctx).Id(id).PaymentNumber(paymentNumber).PeriodDisplayBegin(periodDisplayBegin).PeriodDisplayEnd(periodDisplayEnd).TransactionDateBegin(transactionDateBegin).TransactionDateEnd(transactionDateEnd).CreatedDateBegin(createdDateBegin).CreatedDateEnd(createdDateEnd).Booked(booked).Execute()

List AP Payments



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
	id := []string{"00000000-0000-0000-0000-000000000000"} // []string | The ID of the AP Payment. (optional)
	paymentNumber := "string" // string | The AP payment number. (optional)
	periodDisplayBegin := "string" // string | The starting period used to return AP payment records. (optional)
	periodDisplayEnd := "string" // string | The ending period used to return AP payment records. (optional)
	transactionDateBegin := time.Now() // time.Time | The start date used to return AP payment transaction records during a period. (optional)
	transactionDateEnd := time.Now() // time.Time | The end date used to return AP payment transaction records during a period. (optional)
	createdDateBegin := time.Now() // time.Time | The beginning date used to return AP payments created within a time frame. (optional)
	createdDateEnd := time.Now() // time.Time | The ending date used to return AP payments created within a time frame. (optional)
	booked := false // bool | Specify AP payment is booked. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AccountsPayablePaymentsAPIAPI.AccountsPayablePaymentsApiListAPPayments(context.Background()).Id(id).PaymentNumber(paymentNumber).PeriodDisplayBegin(periodDisplayBegin).PeriodDisplayEnd(periodDisplayEnd).TransactionDateBegin(transactionDateBegin).TransactionDateEnd(transactionDateEnd).CreatedDateBegin(createdDateBegin).CreatedDateEnd(createdDateEnd).Booked(booked).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AccountsPayablePaymentsAPIAPI.AccountsPayablePaymentsApiListAPPayments``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AccountsPayablePaymentsApiListAPPayments`: []AccountsPayablePaymentsApiListAPPaymentsItem
	fmt.Fprintf(os.Stdout, "Response from `AccountsPayablePaymentsAPIAPI.AccountsPayablePaymentsApiListAPPayments`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiAccountsPayablePaymentsApiListAPPaymentsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **[]string** | The ID of the AP Payment. | 
 **paymentNumber** | **string** | The AP payment number. | 
 **periodDisplayBegin** | **string** | The starting period used to return AP payment records. | 
 **periodDisplayEnd** | **string** | The ending period used to return AP payment records. | 
 **transactionDateBegin** | **time.Time** | The start date used to return AP payment transaction records during a period. | 
 **transactionDateEnd** | **time.Time** | The end date used to return AP payment transaction records during a period. | 
 **createdDateBegin** | **time.Time** | The beginning date used to return AP payments created within a time frame. | 
 **createdDateEnd** | **time.Time** | The ending date used to return AP payments created within a time frame. | 
 **booked** | **bool** | Specify AP payment is booked. | 

### Return type

[**[]AccountsPayablePaymentsApiListAPPaymentsItem**](AccountsPayablePaymentsApiListAPPaymentsItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

