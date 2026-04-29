# \ActivityManagerAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ActivityManagerApiCreateActivity**](ActivityManagerAPIAPI.md#ActivityManagerApiCreateActivity) | **Post** /management/v1/activity-manager | Create Activity
[**ActivityManagerApiGetActivity**](ActivityManagerAPIAPI.md#ActivityManagerApiGetActivity) | **Get** /management/v1/activity-manager/{id} | Get Activity
[**ActivityManagerApiListActivities**](ActivityManagerAPIAPI.md#ActivityManagerApiListActivities) | **Get** /management/v1/activity-manager | List Activities
[**ActivityManagerApiUpdateActivity**](ActivityManagerAPIAPI.md#ActivityManagerApiUpdateActivity) | **Put** /management/v1/activity-manager/{id} | Update Activity



## ActivityManagerApiCreateActivity

> ActivityManagerApiCreateActivity201Response ActivityManagerApiCreateActivity(ctx).ActivityManagerApiCreateActivityRequest(activityManagerApiCreateActivityRequest).Execute()

Create Activity



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
	activityManagerApiCreateActivityRequest := *openapiclient.NewActivityManagerApiCreateActivityRequest() // ActivityManagerApiCreateActivityRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ActivityManagerAPIAPI.ActivityManagerApiCreateActivity(context.Background()).ActivityManagerApiCreateActivityRequest(activityManagerApiCreateActivityRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ActivityManagerAPIAPI.ActivityManagerApiCreateActivity``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ActivityManagerApiCreateActivity`: ActivityManagerApiCreateActivity201Response
	fmt.Fprintf(os.Stdout, "Response from `ActivityManagerAPIAPI.ActivityManagerApiCreateActivity`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiActivityManagerApiCreateActivityRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **activityManagerApiCreateActivityRequest** | [**ActivityManagerApiCreateActivityRequest**](ActivityManagerApiCreateActivityRequest.md) |  | 

### Return type

[**ActivityManagerApiCreateActivity201Response**](ActivityManagerApiCreateActivity201Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ActivityManagerApiGetActivity

> ActivityManagerApiGetActivityResponse ActivityManagerApiGetActivity(ctx, id).Execute()

Get Activity



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
	id := "00000000-0000-0000-0000-000000000000" // string | The Activity ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ActivityManagerAPIAPI.ActivityManagerApiGetActivity(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ActivityManagerAPIAPI.ActivityManagerApiGetActivity``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ActivityManagerApiGetActivity`: ActivityManagerApiGetActivityResponse
	fmt.Fprintf(os.Stdout, "Response from `ActivityManagerAPIAPI.ActivityManagerApiGetActivity`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The Activity ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiActivityManagerApiGetActivityRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ActivityManagerApiGetActivityResponse**](ActivityManagerApiGetActivityResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ActivityManagerApiListActivities

> []ActivityManagerApiListActivitiesItem ActivityManagerApiListActivities(ctx).TenantId(tenantId).ActivityIds(activityIds).ActivityName(activityName).ActivityType(activityType).ActivityStatus(activityStatus).Priority(priority).DueDateStartDateTime(dueDateStartDateTime).DueDateEndDateTime(dueDateEndDateTime).CustomerCode(customerCode).SupplierCode(supplierCode).Location(location).Private(private).AssignedTo(assignedTo).AssignedToDepartment(assignedToDepartment).InvolvedUsers(involvedUsers).StatusType(statusType).ProgressType(progressType).ParentActivity(parentActivity).PlannedStartDateTime(plannedStartDateTime).PlannedFinishDateTime(plannedFinishDateTime).Execute()

List Activities



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
	tenantId := "00000000-0000-0000-0000-000000000000" // string | The Tenant ID. (optional)
	activityIds := []string{"00000000-0000-0000-0000-000000000000"} // []string | The ID of the activity. (optional)
	activityName := "string" // string | The name of the activity. (optional)
	activityType := "string" // string | The activity type. (optional)
	activityStatus := "string" // string | The status information of the activity. (optional)
	priority := int32(0) // int32 | The priority information about the activity. (optional)
	dueDateStartDateTime := time.Now() // time.Time | The due date of the activity. (optional)
	dueDateEndDateTime := time.Now() // time.Time | The due date of the activity. (optional)
	customerCode := "string" // string | The customer code of the activity. (optional)
	supplierCode := "string" // string | The supplier code of the activity. (optional)
	location := "string" // string | The location of the activity. (optional)
	private := false // bool | Indicates whether the activity is private or not. (optional)
	assignedTo := "00000000-0000-0000-0000-000000000000" // string | The User ID assigned to the activity. (optional)
	assignedToDepartment := "string" // string | The department code to which the activity is assigned. (optional)
	involvedUsers := []string{"00000000-0000-0000-0000-000000000000"} // []string | The user involved in the activity. (optional)
	statusType := int32(0) // int32 | The status type of the activity. (optional)
	progressType := int32(0) // int32 | The progress type of the activity. (optional)
	parentActivity := "00000000-0000-0000-0000-000000000000" // string | The parent ID of the activity. (optional)
	plannedStartDateTime := time.Now() // time.Time | The planned start date of the activity. (optional)
	plannedFinishDateTime := time.Now() // time.Time | The planned finish date of the activity. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ActivityManagerAPIAPI.ActivityManagerApiListActivities(context.Background()).TenantId(tenantId).ActivityIds(activityIds).ActivityName(activityName).ActivityType(activityType).ActivityStatus(activityStatus).Priority(priority).DueDateStartDateTime(dueDateStartDateTime).DueDateEndDateTime(dueDateEndDateTime).CustomerCode(customerCode).SupplierCode(supplierCode).Location(location).Private(private).AssignedTo(assignedTo).AssignedToDepartment(assignedToDepartment).InvolvedUsers(involvedUsers).StatusType(statusType).ProgressType(progressType).ParentActivity(parentActivity).PlannedStartDateTime(plannedStartDateTime).PlannedFinishDateTime(plannedFinishDateTime).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ActivityManagerAPIAPI.ActivityManagerApiListActivities``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ActivityManagerApiListActivities`: []ActivityManagerApiListActivitiesItem
	fmt.Fprintf(os.Stdout, "Response from `ActivityManagerAPIAPI.ActivityManagerApiListActivities`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiActivityManagerApiListActivitiesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **tenantId** | **string** | The Tenant ID. | 
 **activityIds** | **[]string** | The ID of the activity. | 
 **activityName** | **string** | The name of the activity. | 
 **activityType** | **string** | The activity type. | 
 **activityStatus** | **string** | The status information of the activity. | 
 **priority** | **int32** | The priority information about the activity. | 
 **dueDateStartDateTime** | **time.Time** | The due date of the activity. | 
 **dueDateEndDateTime** | **time.Time** | The due date of the activity. | 
 **customerCode** | **string** | The customer code of the activity. | 
 **supplierCode** | **string** | The supplier code of the activity. | 
 **location** | **string** | The location of the activity. | 
 **private** | **bool** | Indicates whether the activity is private or not. | 
 **assignedTo** | **string** | The User ID assigned to the activity. | 
 **assignedToDepartment** | **string** | The department code to which the activity is assigned. | 
 **involvedUsers** | **[]string** | The user involved in the activity. | 
 **statusType** | **int32** | The status type of the activity. | 
 **progressType** | **int32** | The progress type of the activity. | 
 **parentActivity** | **string** | The parent ID of the activity. | 
 **plannedStartDateTime** | **time.Time** | The planned start date of the activity. | 
 **plannedFinishDateTime** | **time.Time** | The planned finish date of the activity. | 

### Return type

[**[]ActivityManagerApiListActivitiesItem**](ActivityManagerApiListActivitiesItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ActivityManagerApiUpdateActivity

> ActivityManagerApiUpdateActivityResponse ActivityManagerApiUpdateActivity(ctx, id).ActivityManagerApiUpdateActivityRequest(activityManagerApiUpdateActivityRequest).Execute()

Update Activity



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
	id := "00000000-0000-0000-0000-000000000000" // string | The Activity ID.
	activityManagerApiUpdateActivityRequest := *openapiclient.NewActivityManagerApiUpdateActivityRequest() // ActivityManagerApiUpdateActivityRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ActivityManagerAPIAPI.ActivityManagerApiUpdateActivity(context.Background(), id).ActivityManagerApiUpdateActivityRequest(activityManagerApiUpdateActivityRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ActivityManagerAPIAPI.ActivityManagerApiUpdateActivity``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ActivityManagerApiUpdateActivity`: ActivityManagerApiUpdateActivityResponse
	fmt.Fprintf(os.Stdout, "Response from `ActivityManagerAPIAPI.ActivityManagerApiUpdateActivity`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The Activity ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiActivityManagerApiUpdateActivityRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **activityManagerApiUpdateActivityRequest** | [**ActivityManagerApiUpdateActivityRequest**](ActivityManagerApiUpdateActivityRequest.md) |  | 

### Return type

[**ActivityManagerApiUpdateActivityResponse**](ActivityManagerApiUpdateActivityResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

