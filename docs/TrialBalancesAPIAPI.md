# \TrialBalancesAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**TrialBalancesApiGetTrialBalance**](TrialBalancesAPIAPI.md#TrialBalancesApiGetTrialBalance) | **Get** /accounting/v1/trial-balance | Get Trial Balance



## TrialBalancesApiGetTrialBalance

> TrialBalancesApiGetTrialBalanceResponse TrialBalancesApiGetTrialBalance(ctx).PeriodDisplayBegin(periodDisplayBegin).PeriodDisplayEnd(periodDisplayEnd).ExcludePeriod13(excludePeriod13).PeriodAdjustmentEntries(periodAdjustmentEntries).Execute()

Get Trial Balance



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
	periodDisplayBegin := "string" // string | The starting period used to return trial balance records. (optional)
	periodDisplayEnd := "string" // string | The ending period used to return trial balance records. (optional)
	excludePeriod13 := false // bool | Specify if 13th period records are excluded from the trial balance report. (optional)
	periodAdjustmentEntries := false // bool | Specify if period adjustment records are included in the trial balance report. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TrialBalancesAPIAPI.TrialBalancesApiGetTrialBalance(context.Background()).PeriodDisplayBegin(periodDisplayBegin).PeriodDisplayEnd(periodDisplayEnd).ExcludePeriod13(excludePeriod13).PeriodAdjustmentEntries(periodAdjustmentEntries).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TrialBalancesAPIAPI.TrialBalancesApiGetTrialBalance``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TrialBalancesApiGetTrialBalance`: TrialBalancesApiGetTrialBalanceResponse
	fmt.Fprintf(os.Stdout, "Response from `TrialBalancesAPIAPI.TrialBalancesApiGetTrialBalance`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiTrialBalancesApiGetTrialBalanceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **periodDisplayBegin** | **string** | The starting period used to return trial balance records. | 
 **periodDisplayEnd** | **string** | The ending period used to return trial balance records. | 
 **excludePeriod13** | **bool** | Specify if 13th period records are excluded from the trial balance report. | 
 **periodAdjustmentEntries** | **bool** | Specify if period adjustment records are included in the trial balance report. | 

### Return type

[**TrialBalancesApiGetTrialBalanceResponse**](TrialBalancesApiGetTrialBalanceResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

