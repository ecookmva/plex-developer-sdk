# \TimeClockEntriesAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**TimeClockEntriesApiListTimeClockEntries**](TimeClockEntriesAPIAPI.md#TimeClockEntriesApiListTimeClockEntries) | **Get** /hcm/v1/time-clock-entries | List Time Clock Entries



## TimeClockEntriesApiListTimeClockEntries

> []TimeClockEntriesApiListTimeClockEntriesItem TimeClockEntriesApiListTimeClockEntries(ctx).EmployeeId(employeeId).PayDateStart(payDateStart).PayDateEnd(payDateEnd).Type_(type_).Shift(shift).Approved(approved).CreatedBy(createdBy).CreatedDateStart(createdDateStart).CreatedDateEnd(createdDateEnd).ModifiedById(modifiedById).ModifiedDateStart(modifiedDateStart).ModifiedDateEnd(modifiedDateEnd).Execute()

List Time Clock Entries



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
	employeeId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the Employee. This will be automatically generated if omitted from the request. (optional)
	payDateStart := time.Now() // time.Time | Pay Date Start (optional)
	payDateEnd := time.Now() // time.Time | Pay Date End (optional)
	type_ := "string" // string | Clock in type. Setup Table: Clockin_Attribute_Type (optional)
	shift := "string" // string | Setup Table: Shift (optional)
	approved := false // bool |  (optional)
	createdBy := "00000000-0000-0000-0000-000000000000" // string | The ID of the user who created the record. (optional)
	createdDateStart := time.Now() // time.Time | Created Date Start (optional)
	createdDateEnd := time.Now() // time.Time | Created Date End (optional)
	modifiedById := "00000000-0000-0000-0000-000000000000" // string | The ID of the user who last modified the record. (optional)
	modifiedDateStart := time.Now() // time.Time | Modified Date Start (optional)
	modifiedDateEnd := time.Now() // time.Time | Modified Date End (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TimeClockEntriesAPIAPI.TimeClockEntriesApiListTimeClockEntries(context.Background()).EmployeeId(employeeId).PayDateStart(payDateStart).PayDateEnd(payDateEnd).Type_(type_).Shift(shift).Approved(approved).CreatedBy(createdBy).CreatedDateStart(createdDateStart).CreatedDateEnd(createdDateEnd).ModifiedById(modifiedById).ModifiedDateStart(modifiedDateStart).ModifiedDateEnd(modifiedDateEnd).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TimeClockEntriesAPIAPI.TimeClockEntriesApiListTimeClockEntries``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TimeClockEntriesApiListTimeClockEntries`: []TimeClockEntriesApiListTimeClockEntriesItem
	fmt.Fprintf(os.Stdout, "Response from `TimeClockEntriesAPIAPI.TimeClockEntriesApiListTimeClockEntries`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiTimeClockEntriesApiListTimeClockEntriesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **employeeId** | **string** | A unique identifier for the Employee. This will be automatically generated if omitted from the request. | 
 **payDateStart** | **time.Time** | Pay Date Start | 
 **payDateEnd** | **time.Time** | Pay Date End | 
 **type_** | **string** | Clock in type. Setup Table: Clockin_Attribute_Type | 
 **shift** | **string** | Setup Table: Shift | 
 **approved** | **bool** |  | 
 **createdBy** | **string** | The ID of the user who created the record. | 
 **createdDateStart** | **time.Time** | Created Date Start | 
 **createdDateEnd** | **time.Time** | Created Date End | 
 **modifiedById** | **string** | The ID of the user who last modified the record. | 
 **modifiedDateStart** | **time.Time** | Modified Date Start | 
 **modifiedDateEnd** | **time.Time** | Modified Date End | 

### Return type

[**[]TimeClockEntriesApiListTimeClockEntriesItem**](TimeClockEntriesApiListTimeClockEntriesItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

