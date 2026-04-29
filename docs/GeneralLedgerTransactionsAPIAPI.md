# \GeneralLedgerTransactionsAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoices**](GeneralLedgerTransactionsAPIAPI.md#GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoices) | **Get** /accounting/v1/general-ledger-activity/ap-invoices | List GL Transaction Lines For AP Invoices
[**GeneralLedgerTransactionsApiListGLTransactionLinesForAPPayments**](GeneralLedgerTransactionsAPIAPI.md#GeneralLedgerTransactionsApiListGLTransactionLinesForAPPayments) | **Get** /accounting/v1/general-ledger-activity/ap-payments | List GL Transaction Lines For AP Payments
[**GeneralLedgerTransactionsApiListGLTransactionLinesForARDeposits**](GeneralLedgerTransactionsAPIAPI.md#GeneralLedgerTransactionsApiListGLTransactionLinesForARDeposits) | **Get** /accounting/v1/general-ledger-activity/ar-deposits | List GL Transaction Lines For AR Deposits
[**GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoices**](GeneralLedgerTransactionsAPIAPI.md#GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoices) | **Get** /accounting/v1/general-ledger-activity/ar-invoices | List GL Transaction Lines For AR Invoices
[**GeneralLedgerTransactionsApiListGLTransactionLinesForJournals**](GeneralLedgerTransactionsAPIAPI.md#GeneralLedgerTransactionsApiListGLTransactionLinesForJournals) | **Get** /accounting/v1/general-ledger-activity/journal-entries | List GL Transaction Lines For Journals



## GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoices

> []GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoices(ctx).AccountId(accountId).PeriodDisplay(periodDisplay).TransactionDateBegin(transactionDateBegin).TransactionDateEnd(transactionDateEnd).Execute()

List GL Transaction Lines For AP Invoices



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
	accountId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the GL transaction account.
	periodDisplay := "string" // string | The GL transaction fiscal period. (optional)
	transactionDateBegin := time.Now() // time.Time | The beginning date on which a GL transaction was recorded. (optional)
	transactionDateEnd := time.Now() // time.Time | The end date on which a GL transaction was recorded. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GeneralLedgerTransactionsAPIAPI.GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoices(context.Background()).AccountId(accountId).PeriodDisplay(periodDisplay).TransactionDateBegin(transactionDateBegin).TransactionDateEnd(transactionDateEnd).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GeneralLedgerTransactionsAPIAPI.GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoices``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoices`: []GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem
	fmt.Fprintf(os.Stdout, "Response from `GeneralLedgerTransactionsAPIAPI.GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoices`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accountId** | **string** | A unique identifier for the GL transaction account. | 
 **periodDisplay** | **string** | The GL transaction fiscal period. | 
 **transactionDateBegin** | **time.Time** | The beginning date on which a GL transaction was recorded. | 
 **transactionDateEnd** | **time.Time** | The end date on which a GL transaction was recorded. | 

### Return type

[**[]GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem**](GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GeneralLedgerTransactionsApiListGLTransactionLinesForAPPayments

> []GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem GeneralLedgerTransactionsApiListGLTransactionLinesForAPPayments(ctx).AccountId(accountId).PeriodDisplay(periodDisplay).TransactionDateBegin(transactionDateBegin).TransactionDateEnd(transactionDateEnd).Execute()

List GL Transaction Lines For AP Payments



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
	accountId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the GL transaction account.
	periodDisplay := "string" // string | The GL transaction fiscal period. (optional)
	transactionDateBegin := time.Now() // time.Time | The beginning date on which a GL transaction was recorded. (optional)
	transactionDateEnd := time.Now() // time.Time | The end date on which a GL transaction was recorded. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GeneralLedgerTransactionsAPIAPI.GeneralLedgerTransactionsApiListGLTransactionLinesForAPPayments(context.Background()).AccountId(accountId).PeriodDisplay(periodDisplay).TransactionDateBegin(transactionDateBegin).TransactionDateEnd(transactionDateEnd).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GeneralLedgerTransactionsAPIAPI.GeneralLedgerTransactionsApiListGLTransactionLinesForAPPayments``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GeneralLedgerTransactionsApiListGLTransactionLinesForAPPayments`: []GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem
	fmt.Fprintf(os.Stdout, "Response from `GeneralLedgerTransactionsAPIAPI.GeneralLedgerTransactionsApiListGLTransactionLinesForAPPayments`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accountId** | **string** | A unique identifier for the GL transaction account. | 
 **periodDisplay** | **string** | The GL transaction fiscal period. | 
 **transactionDateBegin** | **time.Time** | The beginning date on which a GL transaction was recorded. | 
 **transactionDateEnd** | **time.Time** | The end date on which a GL transaction was recorded. | 

### Return type

[**[]GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem**](GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GeneralLedgerTransactionsApiListGLTransactionLinesForARDeposits

> []GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem GeneralLedgerTransactionsApiListGLTransactionLinesForARDeposits(ctx).AccountId(accountId).PeriodDisplay(periodDisplay).TransactionDateBegin(transactionDateBegin).TransactionDateEnd(transactionDateEnd).Execute()

List GL Transaction Lines For AR Deposits



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
	accountId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the GL transaction account.
	periodDisplay := "string" // string | The GL transaction fiscal period. (optional)
	transactionDateBegin := time.Now() // time.Time | The beginning date on which a GL transaction was recorded. (optional)
	transactionDateEnd := time.Now() // time.Time | The end date on which a GL transaction was recorded. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GeneralLedgerTransactionsAPIAPI.GeneralLedgerTransactionsApiListGLTransactionLinesForARDeposits(context.Background()).AccountId(accountId).PeriodDisplay(periodDisplay).TransactionDateBegin(transactionDateBegin).TransactionDateEnd(transactionDateEnd).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GeneralLedgerTransactionsAPIAPI.GeneralLedgerTransactionsApiListGLTransactionLinesForARDeposits``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GeneralLedgerTransactionsApiListGLTransactionLinesForARDeposits`: []GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem
	fmt.Fprintf(os.Stdout, "Response from `GeneralLedgerTransactionsAPIAPI.GeneralLedgerTransactionsApiListGLTransactionLinesForARDeposits`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accountId** | **string** | A unique identifier for the GL transaction account. | 
 **periodDisplay** | **string** | The GL transaction fiscal period. | 
 **transactionDateBegin** | **time.Time** | The beginning date on which a GL transaction was recorded. | 
 **transactionDateEnd** | **time.Time** | The end date on which a GL transaction was recorded. | 

### Return type

[**[]GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem**](GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoices

> []GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoices(ctx).AccountId(accountId).PeriodDisplay(periodDisplay).TransactionDateBegin(transactionDateBegin).TransactionDateEnd(transactionDateEnd).Execute()

List GL Transaction Lines For AR Invoices



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
	accountId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the GL transaction account.
	periodDisplay := "string" // string | The GL transaction fiscal period. (optional)
	transactionDateBegin := time.Now() // time.Time | The beginning date on which a GL transaction was recorded. (optional)
	transactionDateEnd := time.Now() // time.Time | The end date on which a GL transaction was recorded. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GeneralLedgerTransactionsAPIAPI.GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoices(context.Background()).AccountId(accountId).PeriodDisplay(periodDisplay).TransactionDateBegin(transactionDateBegin).TransactionDateEnd(transactionDateEnd).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GeneralLedgerTransactionsAPIAPI.GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoices``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoices`: []GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem
	fmt.Fprintf(os.Stdout, "Response from `GeneralLedgerTransactionsAPIAPI.GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoices`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accountId** | **string** | A unique identifier for the GL transaction account. | 
 **periodDisplay** | **string** | The GL transaction fiscal period. | 
 **transactionDateBegin** | **time.Time** | The beginning date on which a GL transaction was recorded. | 
 **transactionDateEnd** | **time.Time** | The end date on which a GL transaction was recorded. | 

### Return type

[**[]GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem**](GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GeneralLedgerTransactionsApiListGLTransactionLinesForJournals

> []GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem GeneralLedgerTransactionsApiListGLTransactionLinesForJournals(ctx).AccountId(accountId).PeriodDisplay(periodDisplay).TransactionDateBegin(transactionDateBegin).TransactionDateEnd(transactionDateEnd).ModifiedDateBegin(modifiedDateBegin).ModifiedDateEnd(modifiedDateEnd).Period13(period13).PeriodAdjustmentEntries(periodAdjustmentEntries).Execute()

List GL Transaction Lines For Journals



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
	accountId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the GL transaction account.
	periodDisplay := "string" // string | The GL transaction fiscal period. (optional)
	transactionDateBegin := time.Now() // time.Time | The beginning date on which a GL transaction was recorded. (optional)
	transactionDateEnd := time.Now() // time.Time | The end date on which a GL transaction was recorded. (optional)
	modifiedDateBegin := time.Now() // time.Time | The beginning date used to return GL journal entries modified within a time frame. (optional)
	modifiedDateEnd := time.Now() // time.Time | The end date used to return GL journal entries modified within a time frame. (optional)
	period13 := false // bool | Specify that a GL journal entry has a 13th period. (optional)
	periodAdjustmentEntries := false // bool | Specify that a GL journal entry has a period adjustment use. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GeneralLedgerTransactionsAPIAPI.GeneralLedgerTransactionsApiListGLTransactionLinesForJournals(context.Background()).AccountId(accountId).PeriodDisplay(periodDisplay).TransactionDateBegin(transactionDateBegin).TransactionDateEnd(transactionDateEnd).ModifiedDateBegin(modifiedDateBegin).ModifiedDateEnd(modifiedDateEnd).Period13(period13).PeriodAdjustmentEntries(periodAdjustmentEntries).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GeneralLedgerTransactionsAPIAPI.GeneralLedgerTransactionsApiListGLTransactionLinesForJournals``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GeneralLedgerTransactionsApiListGLTransactionLinesForJournals`: []GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem
	fmt.Fprintf(os.Stdout, "Response from `GeneralLedgerTransactionsAPIAPI.GeneralLedgerTransactionsApiListGLTransactionLinesForJournals`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGeneralLedgerTransactionsApiListGLTransactionLinesForJournalsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accountId** | **string** | A unique identifier for the GL transaction account. | 
 **periodDisplay** | **string** | The GL transaction fiscal period. | 
 **transactionDateBegin** | **time.Time** | The beginning date on which a GL transaction was recorded. | 
 **transactionDateEnd** | **time.Time** | The end date on which a GL transaction was recorded. | 
 **modifiedDateBegin** | **time.Time** | The beginning date used to return GL journal entries modified within a time frame. | 
 **modifiedDateEnd** | **time.Time** | The end date used to return GL journal entries modified within a time frame. | 
 **period13** | **bool** | Specify that a GL journal entry has a 13th period. | 
 **periodAdjustmentEntries** | **bool** | Specify that a GL journal entry has a period adjustment use. | 

### Return type

[**[]GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem**](GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

