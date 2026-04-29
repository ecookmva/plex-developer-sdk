# \AccountsReceivableDepositsAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AccountsReceivableDepositsApiGetARDeposit**](AccountsReceivableDepositsAPIAPI.md#AccountsReceivableDepositsApiGetARDeposit) | **Get** /accounting/v1/ar-deposits/{id} | Get AR Deposit
[**AccountsReceivableDepositsApiListARDeposits**](AccountsReceivableDepositsAPIAPI.md#AccountsReceivableDepositsApiListARDeposits) | **Get** /accounting/v1/ar-deposits | List AR Deposits



## AccountsReceivableDepositsApiGetARDeposit

> AccountsReceivableDepositsApiGetARDepositResponse AccountsReceivableDepositsApiGetARDeposit(ctx, id).Execute()

Get AR Deposit



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
	id := "00000000-0000-0000-0000-000000000000" // string | The Accounts Receivable Deposit's resource id.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AccountsReceivableDepositsAPIAPI.AccountsReceivableDepositsApiGetARDeposit(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AccountsReceivableDepositsAPIAPI.AccountsReceivableDepositsApiGetARDeposit``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AccountsReceivableDepositsApiGetARDeposit`: AccountsReceivableDepositsApiGetARDepositResponse
	fmt.Fprintf(os.Stdout, "Response from `AccountsReceivableDepositsAPIAPI.AccountsReceivableDepositsApiGetARDeposit`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The Accounts Receivable Deposit&#39;s resource id. | 

### Other Parameters

Other parameters are passed through a pointer to a apiAccountsReceivableDepositsApiGetARDepositRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AccountsReceivableDepositsApiGetARDepositResponse**](AccountsReceivableDepositsApiGetARDepositResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## AccountsReceivableDepositsApiListARDeposits

> []AccountsReceivableDepositsApiListARDepositsItem AccountsReceivableDepositsApiListARDeposits(ctx).Id(id).DepositNumber(depositNumber).PeriodDisplayBegin(periodDisplayBegin).PeriodDisplayEnd(periodDisplayEnd).TransactionDateBegin(transactionDateBegin).TransactionDateEnd(transactionDateEnd).CreatedDateBegin(createdDateBegin).CreatedDateEnd(createdDateEnd).Booked(booked).Execute()

List AR Deposits



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
	id := []string{"00000000-0000-0000-0000-000000000000"} // []string | The ID of the AR Deposit. (optional)
	depositNumber := "string" // string | The AR deposit number. (optional)
	periodDisplayBegin := "string" // string | The start date used to return AR deposit records during a period. (optional)
	periodDisplayEnd := "string" // string | The end date used to return AR deposit records during a period. (optional)
	transactionDateBegin := time.Now() // time.Time | The beginning date used to return AR deposit transaction records during a period. (optional)
	transactionDateEnd := time.Now() // time.Time | The ending date used to return AR deposit transaction records during a period. (optional)
	createdDateBegin := time.Now() // time.Time | The beginning date used to return AR deposits created within a time frame. (optional)
	createdDateEnd := time.Now() // time.Time | The ending date used to return AR deposits created within a time frame. (optional)
	booked := false // bool | Specify AR deposit is booked. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AccountsReceivableDepositsAPIAPI.AccountsReceivableDepositsApiListARDeposits(context.Background()).Id(id).DepositNumber(depositNumber).PeriodDisplayBegin(periodDisplayBegin).PeriodDisplayEnd(periodDisplayEnd).TransactionDateBegin(transactionDateBegin).TransactionDateEnd(transactionDateEnd).CreatedDateBegin(createdDateBegin).CreatedDateEnd(createdDateEnd).Booked(booked).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AccountsReceivableDepositsAPIAPI.AccountsReceivableDepositsApiListARDeposits``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AccountsReceivableDepositsApiListARDeposits`: []AccountsReceivableDepositsApiListARDepositsItem
	fmt.Fprintf(os.Stdout, "Response from `AccountsReceivableDepositsAPIAPI.AccountsReceivableDepositsApiListARDeposits`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiAccountsReceivableDepositsApiListARDepositsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **[]string** | The ID of the AR Deposit. | 
 **depositNumber** | **string** | The AR deposit number. | 
 **periodDisplayBegin** | **string** | The start date used to return AR deposit records during a period. | 
 **periodDisplayEnd** | **string** | The end date used to return AR deposit records during a period. | 
 **transactionDateBegin** | **time.Time** | The beginning date used to return AR deposit transaction records during a period. | 
 **transactionDateEnd** | **time.Time** | The ending date used to return AR deposit transaction records during a period. | 
 **createdDateBegin** | **time.Time** | The beginning date used to return AR deposits created within a time frame. | 
 **createdDateEnd** | **time.Time** | The ending date used to return AR deposits created within a time frame. | 
 **booked** | **bool** | Specify AR deposit is booked. | 

### Return type

[**[]AccountsReceivableDepositsApiListARDepositsItem**](AccountsReceivableDepositsApiListARDepositsItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

