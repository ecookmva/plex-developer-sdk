# \JournalEntriesAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**JournalEntriesApiCreateJournalEntry**](JournalEntriesAPIAPI.md#JournalEntriesApiCreateJournalEntry) | **Post** /accounting/v2/journal-entries | Create Journal Entry
[**JournalEntriesApiGetJournalEntry**](JournalEntriesAPIAPI.md#JournalEntriesApiGetJournalEntry) | **Get** /accounting/v2/journal-entries/{id} | Get Journal Entry
[**JournalEntriesApiListJournalEntries**](JournalEntriesAPIAPI.md#JournalEntriesApiListJournalEntries) | **Get** /accounting/v2/journal-entries | List Journal Entries
[**JournalEntriesApiListJournalEntryLines**](JournalEntriesAPIAPI.md#JournalEntriesApiListJournalEntryLines) | **Get** /accounting/v1/journal-entries/{id}/lines | List Journal Entry Lines
[**JournalEntriesApiUpdateJournalEntry**](JournalEntriesAPIAPI.md#JournalEntriesApiUpdateJournalEntry) | **Put** /accounting/v2/journal-entries/{id} | Update Journal Entry



## JournalEntriesApiCreateJournalEntry

> JournalEntriesApiCreateJournalEntry201Response JournalEntriesApiCreateJournalEntry(ctx).JournalEntriesApiCreateJournalEntryRequest(journalEntriesApiCreateJournalEntryRequest).Execute()

Create Journal Entry



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
	journalEntriesApiCreateJournalEntryRequest := *openapiclient.NewJournalEntriesApiCreateJournalEntryRequest() // JournalEntriesApiCreateJournalEntryRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.JournalEntriesAPIAPI.JournalEntriesApiCreateJournalEntry(context.Background()).JournalEntriesApiCreateJournalEntryRequest(journalEntriesApiCreateJournalEntryRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JournalEntriesAPIAPI.JournalEntriesApiCreateJournalEntry``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `JournalEntriesApiCreateJournalEntry`: JournalEntriesApiCreateJournalEntry201Response
	fmt.Fprintf(os.Stdout, "Response from `JournalEntriesAPIAPI.JournalEntriesApiCreateJournalEntry`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiJournalEntriesApiCreateJournalEntryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **journalEntriesApiCreateJournalEntryRequest** | [**JournalEntriesApiCreateJournalEntryRequest**](JournalEntriesApiCreateJournalEntryRequest.md) |  | 

### Return type

[**JournalEntriesApiCreateJournalEntry201Response**](JournalEntriesApiCreateJournalEntry201Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## JournalEntriesApiGetJournalEntry

> JournalEntriesApiGetJournalEntryResponse JournalEntriesApiGetJournalEntry(ctx, id).Execute()

Get Journal Entry



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
	id := "00000000-0000-0000-0000-000000000000" // string | The GL journal entry's ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.JournalEntriesAPIAPI.JournalEntriesApiGetJournalEntry(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JournalEntriesAPIAPI.JournalEntriesApiGetJournalEntry``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `JournalEntriesApiGetJournalEntry`: JournalEntriesApiGetJournalEntryResponse
	fmt.Fprintf(os.Stdout, "Response from `JournalEntriesAPIAPI.JournalEntriesApiGetJournalEntry`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The GL journal entry&#39;s ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiJournalEntriesApiGetJournalEntryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**JournalEntriesApiGetJournalEntryResponse**](JournalEntriesApiGetJournalEntryResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## JournalEntriesApiListJournalEntries

> []JournalEntriesApiListJournalEntriesItem JournalEntriesApiListJournalEntries(ctx).Id(id).JournalNumber(journalNumber).PeriodDisplay(periodDisplay).Description(description).PostDateBegin(postDateBegin).PostDateEnd(postDateEnd).Reversing(reversing).Status(status).CreatedById(createdById).CreatedDateBegin(createdDateBegin).CreatedDateEnd(createdDateEnd).ModifiedById(modifiedById).ModifiedDateBegin(modifiedDateBegin).ModifiedDateEnd(modifiedDateEnd).Booked(booked).Period13(period13).PeriodAdjustmentEntries(periodAdjustmentEntries).Execute()

List Journal Entries



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
	id := []string{"00000000-0000-0000-0000-000000000000"} // []string | The list of GL journal entry IDs. (optional)
	journalNumber := int32(0) // int32 | The GL journal entry journal number. (optional)
	periodDisplay := "string" // string | The period in which a GL journal entry is recorded. (optional)
	description := "string" // string | A description of the GL journal entry. (optional)
	postDateBegin := time.Now() // time.Time | The beginning date used to return GL journal entries posted within a time frame. (optional)
	postDateEnd := time.Now() // time.Time | The end date used to return GL journal entries posted within a time frame. (optional)
	reversing := false // bool | Specify a GL journal entry has been reversed. (optional)
	status := "string" // string | The GL journal entry status. (optional)
	createdById := "00000000-0000-0000-0000-000000000000" // string | The IAM ID with which the GL journal entry was created. (optional)
	createdDateBegin := time.Now() // time.Time | The beginning date used to return GL journal entries created within a time frame. (optional)
	createdDateEnd := time.Now() // time.Time | The end date used to return GL journal entries created within a time frame. (optional)
	modifiedById := "00000000-0000-0000-0000-000000000000" // string | The IAM ID that last modified the GL journal entry. (optional)
	modifiedDateBegin := time.Now() // time.Time | The beginning date used to return GL journal entries modified within a time frame. (optional)
	modifiedDateEnd := time.Now() // time.Time | The end date used to return GL journal entries modified within a time frame. (optional)
	booked := false // bool | Specify a GL journal entry has been booked. (optional)
	period13 := false // bool | Specify a GL journal entry has a 13th period. (optional)
	periodAdjustmentEntries := false // bool | Specify that the period for a GL journal entry has been adjusted. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.JournalEntriesAPIAPI.JournalEntriesApiListJournalEntries(context.Background()).Id(id).JournalNumber(journalNumber).PeriodDisplay(periodDisplay).Description(description).PostDateBegin(postDateBegin).PostDateEnd(postDateEnd).Reversing(reversing).Status(status).CreatedById(createdById).CreatedDateBegin(createdDateBegin).CreatedDateEnd(createdDateEnd).ModifiedById(modifiedById).ModifiedDateBegin(modifiedDateBegin).ModifiedDateEnd(modifiedDateEnd).Booked(booked).Period13(period13).PeriodAdjustmentEntries(periodAdjustmentEntries).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JournalEntriesAPIAPI.JournalEntriesApiListJournalEntries``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `JournalEntriesApiListJournalEntries`: []JournalEntriesApiListJournalEntriesItem
	fmt.Fprintf(os.Stdout, "Response from `JournalEntriesAPIAPI.JournalEntriesApiListJournalEntries`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiJournalEntriesApiListJournalEntriesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **[]string** | The list of GL journal entry IDs. | 
 **journalNumber** | **int32** | The GL journal entry journal number. | 
 **periodDisplay** | **string** | The period in which a GL journal entry is recorded. | 
 **description** | **string** | A description of the GL journal entry. | 
 **postDateBegin** | **time.Time** | The beginning date used to return GL journal entries posted within a time frame. | 
 **postDateEnd** | **time.Time** | The end date used to return GL journal entries posted within a time frame. | 
 **reversing** | **bool** | Specify a GL journal entry has been reversed. | 
 **status** | **string** | The GL journal entry status. | 
 **createdById** | **string** | The IAM ID with which the GL journal entry was created. | 
 **createdDateBegin** | **time.Time** | The beginning date used to return GL journal entries created within a time frame. | 
 **createdDateEnd** | **time.Time** | The end date used to return GL journal entries created within a time frame. | 
 **modifiedById** | **string** | The IAM ID that last modified the GL journal entry. | 
 **modifiedDateBegin** | **time.Time** | The beginning date used to return GL journal entries modified within a time frame. | 
 **modifiedDateEnd** | **time.Time** | The end date used to return GL journal entries modified within a time frame. | 
 **booked** | **bool** | Specify a GL journal entry has been booked. | 
 **period13** | **bool** | Specify a GL journal entry has a 13th period. | 
 **periodAdjustmentEntries** | **bool** | Specify that the period for a GL journal entry has been adjusted. | 

### Return type

[**[]JournalEntriesApiListJournalEntriesItem**](JournalEntriesApiListJournalEntriesItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## JournalEntriesApiListJournalEntryLines

> []JournalEntriesApiListJournalEntryLinesItem JournalEntriesApiListJournalEntryLines(ctx, id).Execute()

List Journal Entry Lines



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.JournalEntriesAPIAPI.JournalEntriesApiListJournalEntryLines(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JournalEntriesAPIAPI.JournalEntriesApiListJournalEntryLines``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `JournalEntriesApiListJournalEntryLines`: []JournalEntriesApiListJournalEntryLinesItem
	fmt.Fprintf(os.Stdout, "Response from `JournalEntriesAPIAPI.JournalEntriesApiListJournalEntryLines`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiJournalEntriesApiListJournalEntryLinesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]JournalEntriesApiListJournalEntryLinesItem**](JournalEntriesApiListJournalEntryLinesItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## JournalEntriesApiUpdateJournalEntry

> JournalEntriesApiUpdateJournalEntryResponse JournalEntriesApiUpdateJournalEntry(ctx, id).JournalEntriesApiUpdateJournalEntryRequest(journalEntriesApiUpdateJournalEntryRequest).Execute()

Update Journal Entry



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
	journalEntriesApiUpdateJournalEntryRequest := *openapiclient.NewJournalEntriesApiUpdateJournalEntryRequest() // JournalEntriesApiUpdateJournalEntryRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.JournalEntriesAPIAPI.JournalEntriesApiUpdateJournalEntry(context.Background(), id).JournalEntriesApiUpdateJournalEntryRequest(journalEntriesApiUpdateJournalEntryRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JournalEntriesAPIAPI.JournalEntriesApiUpdateJournalEntry``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `JournalEntriesApiUpdateJournalEntry`: JournalEntriesApiUpdateJournalEntryResponse
	fmt.Fprintf(os.Stdout, "Response from `JournalEntriesAPIAPI.JournalEntriesApiUpdateJournalEntry`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiJournalEntriesApiUpdateJournalEntryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **journalEntriesApiUpdateJournalEntryRequest** | [**JournalEntriesApiUpdateJournalEntryRequest**](JournalEntriesApiUpdateJournalEntryRequest.md) |  | 

### Return type

[**JournalEntriesApiUpdateJournalEntryResponse**](JournalEntriesApiUpdateJournalEntryResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

