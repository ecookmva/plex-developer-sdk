# \JobSchedulingAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**JobSchedulingApiAddJob**](JobSchedulingAPIAPI.md#JobSchedulingApiAddJob) | **Post** /scheduling/v1/jobs | Add Job
[**JobSchedulingApiAddUpdateJobBom**](JobSchedulingAPIAPI.md#JobSchedulingApiAddUpdateJobBom) | **Post** /scheduling/v1/jobs/{id}/bom-components | Add Update Job Bom
[**JobSchedulingApiBackwardsSchedule**](JobSchedulingAPIAPI.md#JobSchedulingApiBackwardsSchedule) | **Post** /scheduling/v1/jobs/{id}/backwards-schedule | Backwards Schedule
[**JobSchedulingApiCancelJob**](JobSchedulingAPIAPI.md#JobSchedulingApiCancelJob) | **Post** /scheduling/v1/jobs/{id}/cancel | Cancel Job
[**JobSchedulingApiGetJob**](JobSchedulingAPIAPI.md#JobSchedulingApiGetJob) | **Get** /scheduling/v1/jobs/{id} | Get Job
[**JobSchedulingApiGetJobOperation**](JobSchedulingAPIAPI.md#JobSchedulingApiGetJobOperation) | **Get** /scheduling/v1-beta1/jobs/{id}/operations/{jobOperationId} | Get Job Operation
[**JobSchedulingApiGetJobOperationBatch**](JobSchedulingAPIAPI.md#JobSchedulingApiGetJobOperationBatch) | **Get** /scheduling/v1-beta1/jobs/{id}/operations/{jobOperationId}/batches/{batchId} | Get Job Operation Batch
[**JobSchedulingApiHoldJob**](JobSchedulingAPIAPI.md#JobSchedulingApiHoldJob) | **Post** /scheduling/v1-beta1/jobs/{id}/hold | Hold Job
[**JobSchedulingApiListJobOperationBatches**](JobSchedulingAPIAPI.md#JobSchedulingApiListJobOperationBatches) | **Get** /scheduling/v1-beta1/jobs/{id}/operations/{jobOperationId}/batches | List Job Operation Batches
[**JobSchedulingApiListJobOperations**](JobSchedulingAPIAPI.md#JobSchedulingApiListJobOperations) | **Get** /scheduling/v1/jobs/{id}/operations | List Job Operations
[**JobSchedulingApiListJobTypes**](JobSchedulingAPIAPI.md#JobSchedulingApiListJobTypes) | **Get** /scheduling/v1/job-definitions/types | List Job Types
[**JobSchedulingApiListJobs**](JobSchedulingAPIAPI.md#JobSchedulingApiListJobs) | **Get** /scheduling/v1/jobs | List Jobs
[**JobSchedulingApiReleaseJobHold**](JobSchedulingAPIAPI.md#JobSchedulingApiReleaseJobHold) | **Post** /scheduling/v1-beta1/jobs/{id}/release-hold | Release Job Hold
[**JobSchedulingApiScheduleJobOperations**](JobSchedulingAPIAPI.md#JobSchedulingApiScheduleJobOperations) | **Post** /scheduling/v1/jobs/{id}/operations-schedule | Schedule Job Operations
[**JobSchedulingApiUpdateJob**](JobSchedulingAPIAPI.md#JobSchedulingApiUpdateJob) | **Put** /scheduling/v1/jobs/{id} | Update Job



## JobSchedulingApiAddJob

> JobSchedulingApiAddJob201Response JobSchedulingApiAddJob(ctx).JobSchedulingApiAddJobRequest(jobSchedulingApiAddJobRequest).Execute()

Add Job



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
	jobSchedulingApiAddJobRequest := *openapiclient.NewJobSchedulingApiAddJobRequest() // JobSchedulingApiAddJobRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.JobSchedulingAPIAPI.JobSchedulingApiAddJob(context.Background()).JobSchedulingApiAddJobRequest(jobSchedulingApiAddJobRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JobSchedulingAPIAPI.JobSchedulingApiAddJob``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `JobSchedulingApiAddJob`: JobSchedulingApiAddJob201Response
	fmt.Fprintf(os.Stdout, "Response from `JobSchedulingAPIAPI.JobSchedulingApiAddJob`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiJobSchedulingApiAddJobRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **jobSchedulingApiAddJobRequest** | [**JobSchedulingApiAddJobRequest**](JobSchedulingApiAddJobRequest.md) |  | 

### Return type

[**JobSchedulingApiAddJob201Response**](JobSchedulingApiAddJob201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## JobSchedulingApiAddUpdateJobBom

> JobSchedulingApiAddUpdateJobBom(ctx, id).JobSchedulingApiAddUpdateJobBomRequest(jobSchedulingApiAddUpdateJobBomRequest).Execute()

Add Update Job Bom



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
	jobSchedulingApiAddUpdateJobBomRequest := *openapiclient.NewJobSchedulingApiAddUpdateJobBomRequest() // JobSchedulingApiAddUpdateJobBomRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.JobSchedulingAPIAPI.JobSchedulingApiAddUpdateJobBom(context.Background(), id).JobSchedulingApiAddUpdateJobBomRequest(jobSchedulingApiAddUpdateJobBomRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JobSchedulingAPIAPI.JobSchedulingApiAddUpdateJobBom``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiJobSchedulingApiAddUpdateJobBomRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **jobSchedulingApiAddUpdateJobBomRequest** | [**JobSchedulingApiAddUpdateJobBomRequest**](JobSchedulingApiAddUpdateJobBomRequest.md) |  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## JobSchedulingApiBackwardsSchedule

> []JobSchedulingApiBackwardsScheduleItem JobSchedulingApiBackwardsSchedule(ctx, id).JobSchedulingApiBackwardsScheduleRequest(jobSchedulingApiBackwardsScheduleRequest).Execute()

Backwards Schedule



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
	id := "00000000-0000-0000-0000-000000000000" // string | A unique identifier of the production job.
	jobSchedulingApiBackwardsScheduleRequest := *openapiclient.NewJobSchedulingApiBackwardsScheduleRequest() // JobSchedulingApiBackwardsScheduleRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.JobSchedulingAPIAPI.JobSchedulingApiBackwardsSchedule(context.Background(), id).JobSchedulingApiBackwardsScheduleRequest(jobSchedulingApiBackwardsScheduleRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JobSchedulingAPIAPI.JobSchedulingApiBackwardsSchedule``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `JobSchedulingApiBackwardsSchedule`: []JobSchedulingApiBackwardsScheduleItem
	fmt.Fprintf(os.Stdout, "Response from `JobSchedulingAPIAPI.JobSchedulingApiBackwardsSchedule`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | A unique identifier of the production job. | 

### Other Parameters

Other parameters are passed through a pointer to a apiJobSchedulingApiBackwardsScheduleRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **jobSchedulingApiBackwardsScheduleRequest** | [**JobSchedulingApiBackwardsScheduleRequest**](JobSchedulingApiBackwardsScheduleRequest.md) |  | 

### Return type

[**[]JobSchedulingApiBackwardsScheduleItem**](JobSchedulingApiBackwardsScheduleItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## JobSchedulingApiCancelJob

> JobSchedulingApiCancelJob(ctx, id).Execute()

Cancel Job



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
	id := "00000000-0000-0000-0000-000000000000" // string | A unique identifier of the production job.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.JobSchedulingAPIAPI.JobSchedulingApiCancelJob(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JobSchedulingAPIAPI.JobSchedulingApiCancelJob``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | A unique identifier of the production job. | 

### Other Parameters

Other parameters are passed through a pointer to a apiJobSchedulingApiCancelJobRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## JobSchedulingApiGetJob

> JobSchedulingApiGetJobResponse JobSchedulingApiGetJob(ctx, id).Execute()

Get Job



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
	id := "00000000-0000-0000-0000-000000000000" // string | A unique identifier of the production job.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.JobSchedulingAPIAPI.JobSchedulingApiGetJob(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JobSchedulingAPIAPI.JobSchedulingApiGetJob``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `JobSchedulingApiGetJob`: JobSchedulingApiGetJobResponse
	fmt.Fprintf(os.Stdout, "Response from `JobSchedulingAPIAPI.JobSchedulingApiGetJob`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | A unique identifier of the production job. | 

### Other Parameters

Other parameters are passed through a pointer to a apiJobSchedulingApiGetJobRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**JobSchedulingApiGetJobResponse**](JobSchedulingApiGetJobResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## JobSchedulingApiGetJobOperation

> JobSchedulingApiGetJobOperationResponse JobSchedulingApiGetJobOperation(ctx, id, jobOperationId).Execute()

Get Job Operation



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
	jobOperationId := "00000000-0000-0000-0000-000000000000" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.JobSchedulingAPIAPI.JobSchedulingApiGetJobOperation(context.Background(), id, jobOperationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JobSchedulingAPIAPI.JobSchedulingApiGetJobOperation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `JobSchedulingApiGetJobOperation`: JobSchedulingApiGetJobOperationResponse
	fmt.Fprintf(os.Stdout, "Response from `JobSchedulingAPIAPI.JobSchedulingApiGetJobOperation`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 
**jobOperationId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiJobSchedulingApiGetJobOperationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**JobSchedulingApiGetJobOperationResponse**](JobSchedulingApiGetJobOperationResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## JobSchedulingApiGetJobOperationBatch

> JobSchedulingApiGetJobOperationBatchResponse JobSchedulingApiGetJobOperationBatch(ctx, id, jobOperationId, batchId).Execute()

Get Job Operation Batch



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
	jobOperationId := "00000000-0000-0000-0000-000000000000" // string | 
	batchId := "00000000-0000-0000-0000-000000000000" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.JobSchedulingAPIAPI.JobSchedulingApiGetJobOperationBatch(context.Background(), id, jobOperationId, batchId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JobSchedulingAPIAPI.JobSchedulingApiGetJobOperationBatch``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `JobSchedulingApiGetJobOperationBatch`: JobSchedulingApiGetJobOperationBatchResponse
	fmt.Fprintf(os.Stdout, "Response from `JobSchedulingAPIAPI.JobSchedulingApiGetJobOperationBatch`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 
**jobOperationId** | **string** |  | 
**batchId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiJobSchedulingApiGetJobOperationBatchRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------




### Return type

[**JobSchedulingApiGetJobOperationBatchResponse**](JobSchedulingApiGetJobOperationBatchResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## JobSchedulingApiHoldJob

> JobSchedulingApiHoldJob(ctx, id).Execute()

Hold Job



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
	id := "00000000-0000-0000-0000-000000000000" // string | A unique identifier of the production job.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.JobSchedulingAPIAPI.JobSchedulingApiHoldJob(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JobSchedulingAPIAPI.JobSchedulingApiHoldJob``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | A unique identifier of the production job. | 

### Other Parameters

Other parameters are passed through a pointer to a apiJobSchedulingApiHoldJobRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## JobSchedulingApiListJobOperationBatches

> []JobSchedulingApiListJobOperationBatchesItem JobSchedulingApiListJobOperationBatches(ctx, id, jobOperationId).WorkcenterID(workcenterID).BatchStatus(batchStatus).Execute()

List Job Operation Batches



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
	jobOperationId := "00000000-0000-0000-0000-000000000000" // string | 
	workcenterID := "00000000-0000-0000-0000-000000000000" // string | A unique identifier of a workcenter. (optional)
	batchStatus := "string" // string | The status of a batch. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.JobSchedulingAPIAPI.JobSchedulingApiListJobOperationBatches(context.Background(), id, jobOperationId).WorkcenterID(workcenterID).BatchStatus(batchStatus).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JobSchedulingAPIAPI.JobSchedulingApiListJobOperationBatches``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `JobSchedulingApiListJobOperationBatches`: []JobSchedulingApiListJobOperationBatchesItem
	fmt.Fprintf(os.Stdout, "Response from `JobSchedulingAPIAPI.JobSchedulingApiListJobOperationBatches`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 
**jobOperationId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiJobSchedulingApiListJobOperationBatchesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **workcenterID** | **string** | A unique identifier of a workcenter. | 
 **batchStatus** | **string** | The status of a batch. | 

### Return type

[**[]JobSchedulingApiListJobOperationBatchesItem**](JobSchedulingApiListJobOperationBatchesItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## JobSchedulingApiListJobOperations

> []JobSchedulingApiListJobOperationsItem JobSchedulingApiListJobOperations(ctx, id).PartOperationType(partOperationType).JobOperationStatus(jobOperationStatus).OperationCode(operationCode).JobOperationId(jobOperationId).WorkcenterId(workcenterId).BeginScheduledStartDate(beginScheduledStartDate).EndScheduledStartDate(endScheduledStartDate).Execute()

List Job Operations



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
	id := "00000000-0000-0000-0000-000000000000" // string | A unique identifier of the production job.
	partOperationType := "string" // string | Identifies the part operation type. Max 50 characters. (optional)
	jobOperationStatus := "string" // string | Status of the job. More than one status can be specified. Setup Table &quot;Job Status&quot; (part.dbo.Job_Status). Maximum 50 characters. (optional)
	operationCode := "string" // string | Name of the operation. (optional)
	jobOperationId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier of the job operation. (optional)
	workcenterId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier of the assigned workcenter. (optional)
	beginScheduledStartDate := time.Now() // time.Time | Start of the date range for the job start date. If ScheduledStartDate range parameters are specified, only job operations with an ScheduledStartDate value that is within the date/time range will be returned. (optional)
	endScheduledStartDate := time.Now() // time.Time | End of the date range for the job start date. If ScheduledStartDate range parameters are specified, only job operations with an ScheduledStartDate value that is within the date/time range will be returned. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.JobSchedulingAPIAPI.JobSchedulingApiListJobOperations(context.Background(), id).PartOperationType(partOperationType).JobOperationStatus(jobOperationStatus).OperationCode(operationCode).JobOperationId(jobOperationId).WorkcenterId(workcenterId).BeginScheduledStartDate(beginScheduledStartDate).EndScheduledStartDate(endScheduledStartDate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JobSchedulingAPIAPI.JobSchedulingApiListJobOperations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `JobSchedulingApiListJobOperations`: []JobSchedulingApiListJobOperationsItem
	fmt.Fprintf(os.Stdout, "Response from `JobSchedulingAPIAPI.JobSchedulingApiListJobOperations`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | A unique identifier of the production job. | 

### Other Parameters

Other parameters are passed through a pointer to a apiJobSchedulingApiListJobOperationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **partOperationType** | **string** | Identifies the part operation type. Max 50 characters. | 
 **jobOperationStatus** | **string** | Status of the job. More than one status can be specified. Setup Table &amp;quot;Job Status&amp;quot; (part.dbo.Job_Status). Maximum 50 characters. | 
 **operationCode** | **string** | Name of the operation. | 
 **jobOperationId** | **string** | A unique identifier of the job operation. | 
 **workcenterId** | **string** | A unique identifier of the assigned workcenter. | 
 **beginScheduledStartDate** | **time.Time** | Start of the date range for the job start date. If ScheduledStartDate range parameters are specified, only job operations with an ScheduledStartDate value that is within the date/time range will be returned. | 
 **endScheduledStartDate** | **time.Time** | End of the date range for the job start date. If ScheduledStartDate range parameters are specified, only job operations with an ScheduledStartDate value that is within the date/time range will be returned. | 

### Return type

[**[]JobSchedulingApiListJobOperationsItem**](JobSchedulingApiListJobOperationsItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## JobSchedulingApiListJobTypes

> []JobSchedulingApiListJobTypesItem JobSchedulingApiListJobTypes(ctx).Execute()

List Job Types



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.JobSchedulingAPIAPI.JobSchedulingApiListJobTypes(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JobSchedulingAPIAPI.JobSchedulingApiListJobTypes``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `JobSchedulingApiListJobTypes`: []JobSchedulingApiListJobTypesItem
	fmt.Fprintf(os.Stdout, "Response from `JobSchedulingAPIAPI.JobSchedulingApiListJobTypes`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiJobSchedulingApiListJobTypesRequest struct via the builder pattern


### Return type

[**[]JobSchedulingApiListJobTypesItem**](JobSchedulingApiListJobTypesItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## JobSchedulingApiListJobs

> []JobSchedulingApiListJobsItem JobSchedulingApiListJobs(ctx).PartId(partId).ExternalJobCode(externalJobCode).JobNumber(jobNumber).JobStatuses(jobStatuses).DueDateBegin(dueDateBegin).DueDateEnd(dueDateEnd).BuildingId(buildingId).CompletedDateBegin(completedDateBegin).CompletedDateEnd(completedDateEnd).BeginEarliestStartDateTime(beginEarliestStartDateTime).EndEarliestStartDateTime(endEarliestStartDateTime).Priority(priority).Execute()

List Jobs



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
	partId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier of the part. (optional)
	externalJobCode := "string" // string | A code or number assigned to the production job in an external scheduling system. (optional)
	jobNumber := "string" // string | Job number, including prefix and suffix, assigned to a production job. (optional)
	jobStatuses := []string{"string"} // []string | Status of the job. More than one status can be specified. Setup Table &quot;Job Status&quot; (part.dbo.Job_Status). (optional)
	dueDateBegin := time.Now() // time.Time | Start of the date range for the job due date. (optional)
	dueDateEnd := time.Now() // time.Time | End of the date range for the job due date. (optional)
	buildingId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier of the building in which the job is completed. (optional)
	completedDateBegin := time.Now() // time.Time | Start of the date range for the job completed date. If completedDate range parameters are specified, only jobs that have a completed date within the date/time range will be returned. (optional)
	completedDateEnd := time.Now() // time.Time | End of the date range for the job completed date. If completedDate range parameters are specified, only jobs that have a completed date within the date/time range will be returned. (optional)
	beginEarliestStartDateTime := time.Now() // time.Time | Beginning of the date range for the earliest date the job can be started. (optional)
	endEarliestStartDateTime := time.Now() // time.Time | End of the date range for the earliest date the job can be started. (optional)
	priority := "string" // string | The priority of the job. Setup Table &quot;Priority (Part)&quot; (part.dbo.Priority). If not provided the default priority will be used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.JobSchedulingAPIAPI.JobSchedulingApiListJobs(context.Background()).PartId(partId).ExternalJobCode(externalJobCode).JobNumber(jobNumber).JobStatuses(jobStatuses).DueDateBegin(dueDateBegin).DueDateEnd(dueDateEnd).BuildingId(buildingId).CompletedDateBegin(completedDateBegin).CompletedDateEnd(completedDateEnd).BeginEarliestStartDateTime(beginEarliestStartDateTime).EndEarliestStartDateTime(endEarliestStartDateTime).Priority(priority).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JobSchedulingAPIAPI.JobSchedulingApiListJobs``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `JobSchedulingApiListJobs`: []JobSchedulingApiListJobsItem
	fmt.Fprintf(os.Stdout, "Response from `JobSchedulingAPIAPI.JobSchedulingApiListJobs`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiJobSchedulingApiListJobsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **partId** | **string** | A unique identifier of the part. | 
 **externalJobCode** | **string** | A code or number assigned to the production job in an external scheduling system. | 
 **jobNumber** | **string** | Job number, including prefix and suffix, assigned to a production job. | 
 **jobStatuses** | **[]string** | Status of the job. More than one status can be specified. Setup Table &amp;quot;Job Status&amp;quot; (part.dbo.Job_Status). | 
 **dueDateBegin** | **time.Time** | Start of the date range for the job due date. | 
 **dueDateEnd** | **time.Time** | End of the date range for the job due date. | 
 **buildingId** | **string** | A unique identifier of the building in which the job is completed. | 
 **completedDateBegin** | **time.Time** | Start of the date range for the job completed date. If completedDate range parameters are specified, only jobs that have a completed date within the date/time range will be returned. | 
 **completedDateEnd** | **time.Time** | End of the date range for the job completed date. If completedDate range parameters are specified, only jobs that have a completed date within the date/time range will be returned. | 
 **beginEarliestStartDateTime** | **time.Time** | Beginning of the date range for the earliest date the job can be started. | 
 **endEarliestStartDateTime** | **time.Time** | End of the date range for the earliest date the job can be started. | 
 **priority** | **string** | The priority of the job. Setup Table &amp;quot;Priority (Part)&amp;quot; (part.dbo.Priority). If not provided the default priority will be used. | 

### Return type

[**[]JobSchedulingApiListJobsItem**](JobSchedulingApiListJobsItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## JobSchedulingApiReleaseJobHold

> JobSchedulingApiReleaseJobHold(ctx, id).Execute()

Release Job Hold



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
	id := "00000000-0000-0000-0000-000000000000" // string | A unique identifier of the production job.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.JobSchedulingAPIAPI.JobSchedulingApiReleaseJobHold(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JobSchedulingAPIAPI.JobSchedulingApiReleaseJobHold``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | A unique identifier of the production job. | 

### Other Parameters

Other parameters are passed through a pointer to a apiJobSchedulingApiReleaseJobHoldRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## JobSchedulingApiScheduleJobOperations

> JobSchedulingApiScheduleJobOperations(ctx, id).JobSchedulingApiScheduleJobOperationsRequest(jobSchedulingApiScheduleJobOperationsRequest).Execute()

Schedule Job Operations



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
	id := "00000000-0000-0000-0000-000000000000" // string | A unique identifier of the production job.
	jobSchedulingApiScheduleJobOperationsRequest := *openapiclient.NewJobSchedulingApiScheduleJobOperationsRequest() // JobSchedulingApiScheduleJobOperationsRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.JobSchedulingAPIAPI.JobSchedulingApiScheduleJobOperations(context.Background(), id).JobSchedulingApiScheduleJobOperationsRequest(jobSchedulingApiScheduleJobOperationsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JobSchedulingAPIAPI.JobSchedulingApiScheduleJobOperations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | A unique identifier of the production job. | 

### Other Parameters

Other parameters are passed through a pointer to a apiJobSchedulingApiScheduleJobOperationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **jobSchedulingApiScheduleJobOperationsRequest** | [**JobSchedulingApiScheduleJobOperationsRequest**](JobSchedulingApiScheduleJobOperationsRequest.md) |  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## JobSchedulingApiUpdateJob

> JobSchedulingApiUpdateJob(ctx, id).JobSchedulingApiUpdateJobRequest(jobSchedulingApiUpdateJobRequest).Execute()

Update Job



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
	jobSchedulingApiUpdateJobRequest := *openapiclient.NewJobSchedulingApiUpdateJobRequest() // JobSchedulingApiUpdateJobRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.JobSchedulingAPIAPI.JobSchedulingApiUpdateJob(context.Background(), id).JobSchedulingApiUpdateJobRequest(jobSchedulingApiUpdateJobRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JobSchedulingAPIAPI.JobSchedulingApiUpdateJob``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiJobSchedulingApiUpdateJobRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **jobSchedulingApiUpdateJobRequest** | [**JobSchedulingApiUpdateJobRequest**](JobSchedulingApiUpdateJobRequest.md) |  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

