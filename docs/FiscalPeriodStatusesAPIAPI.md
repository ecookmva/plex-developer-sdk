# \FiscalPeriodStatusesAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**FiscalPeriodStatusesApiListFiscalPeriodStatuses**](FiscalPeriodStatusesAPIAPI.md#FiscalPeriodStatusesApiListFiscalPeriodStatuses) | **Get** /accounting/v1/fiscal-period-statuses | List Fiscal Period Statuses



## FiscalPeriodStatusesApiListFiscalPeriodStatuses

> []FiscalPeriodStatusesApiListFiscalPeriodStatusesItem FiscalPeriodStatusesApiListFiscalPeriodStatuses(ctx).PeriodDisplayBegin(periodDisplayBegin).PeriodDisplayEnd(periodDisplayEnd).Execute()

List Fiscal Period Statuses



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
	periodDisplayBegin := "string" // string | The starting period used to return fiscal period status records. (optional)
	periodDisplayEnd := "string" // string | The ending period used to return fiscal period status records. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FiscalPeriodStatusesAPIAPI.FiscalPeriodStatusesApiListFiscalPeriodStatuses(context.Background()).PeriodDisplayBegin(periodDisplayBegin).PeriodDisplayEnd(periodDisplayEnd).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FiscalPeriodStatusesAPIAPI.FiscalPeriodStatusesApiListFiscalPeriodStatuses``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FiscalPeriodStatusesApiListFiscalPeriodStatuses`: []FiscalPeriodStatusesApiListFiscalPeriodStatusesItem
	fmt.Fprintf(os.Stdout, "Response from `FiscalPeriodStatusesAPIAPI.FiscalPeriodStatusesApiListFiscalPeriodStatuses`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiFiscalPeriodStatusesApiListFiscalPeriodStatusesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **periodDisplayBegin** | **string** | The starting period used to return fiscal period status records. | 
 **periodDisplayEnd** | **string** | The ending period used to return fiscal period status records. | 

### Return type

[**[]FiscalPeriodStatusesApiListFiscalPeriodStatusesItem**](FiscalPeriodStatusesApiListFiscalPeriodStatusesItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

