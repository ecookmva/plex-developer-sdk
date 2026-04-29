# JobSchedulingApiScheduleJobOperationsRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**JobOperationId** | Pointer to **string** | A unique identifier of the job operation. | [optional] 
**JobOperationStatus** | Pointer to **string** | Status of the job operation. Setup Table &amp;quot;Job_Op_Status&amp;quot; (part.dbo.Job_Op_Status). | [optional] 
**ScheduleDetails** | Pointer to [**[]ScheduleDetailsItem**](ScheduleDetailsItem.md) | List of scheduling details refres to model &amp;quot;ScheduleDetails&amp;quot;. | [optional] 
**WorkcenterId** | Pointer to **string** | A unique identifier for the workcenter. | [optional] 
**StartDateTime** | Pointer to **time.Time** | Start of the date range for the job op scheduling. | [optional] 
**RunLength** | Pointer to **int32** | Run length of scheduled operation in minutes. | [optional] 

## Methods

### NewJobSchedulingApiScheduleJobOperationsRequest

`func NewJobSchedulingApiScheduleJobOperationsRequest() *JobSchedulingApiScheduleJobOperationsRequest`

NewJobSchedulingApiScheduleJobOperationsRequest instantiates a new JobSchedulingApiScheduleJobOperationsRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewJobSchedulingApiScheduleJobOperationsRequestWithDefaults

`func NewJobSchedulingApiScheduleJobOperationsRequestWithDefaults() *JobSchedulingApiScheduleJobOperationsRequest`

NewJobSchedulingApiScheduleJobOperationsRequestWithDefaults instantiates a new JobSchedulingApiScheduleJobOperationsRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetJobOperationId

`func (o *JobSchedulingApiScheduleJobOperationsRequest) GetJobOperationId() string`

GetJobOperationId returns the JobOperationId field if non-nil, zero value otherwise.

### GetJobOperationIdOk

`func (o *JobSchedulingApiScheduleJobOperationsRequest) GetJobOperationIdOk() (*string, bool)`

GetJobOperationIdOk returns a tuple with the JobOperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobOperationId

`func (o *JobSchedulingApiScheduleJobOperationsRequest) SetJobOperationId(v string)`

SetJobOperationId sets JobOperationId field to given value.

### HasJobOperationId

`func (o *JobSchedulingApiScheduleJobOperationsRequest) HasJobOperationId() bool`

HasJobOperationId returns a boolean if a field has been set.

### GetJobOperationStatus

`func (o *JobSchedulingApiScheduleJobOperationsRequest) GetJobOperationStatus() string`

GetJobOperationStatus returns the JobOperationStatus field if non-nil, zero value otherwise.

### GetJobOperationStatusOk

`func (o *JobSchedulingApiScheduleJobOperationsRequest) GetJobOperationStatusOk() (*string, bool)`

GetJobOperationStatusOk returns a tuple with the JobOperationStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobOperationStatus

`func (o *JobSchedulingApiScheduleJobOperationsRequest) SetJobOperationStatus(v string)`

SetJobOperationStatus sets JobOperationStatus field to given value.

### HasJobOperationStatus

`func (o *JobSchedulingApiScheduleJobOperationsRequest) HasJobOperationStatus() bool`

HasJobOperationStatus returns a boolean if a field has been set.

### GetScheduleDetails

`func (o *JobSchedulingApiScheduleJobOperationsRequest) GetScheduleDetails() []ScheduleDetailsItem`

GetScheduleDetails returns the ScheduleDetails field if non-nil, zero value otherwise.

### GetScheduleDetailsOk

`func (o *JobSchedulingApiScheduleJobOperationsRequest) GetScheduleDetailsOk() (*[]ScheduleDetailsItem, bool)`

GetScheduleDetailsOk returns a tuple with the ScheduleDetails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScheduleDetails

`func (o *JobSchedulingApiScheduleJobOperationsRequest) SetScheduleDetails(v []ScheduleDetailsItem)`

SetScheduleDetails sets ScheduleDetails field to given value.

### HasScheduleDetails

`func (o *JobSchedulingApiScheduleJobOperationsRequest) HasScheduleDetails() bool`

HasScheduleDetails returns a boolean if a field has been set.

### GetWorkcenterId

`func (o *JobSchedulingApiScheduleJobOperationsRequest) GetWorkcenterId() string`

GetWorkcenterId returns the WorkcenterId field if non-nil, zero value otherwise.

### GetWorkcenterIdOk

`func (o *JobSchedulingApiScheduleJobOperationsRequest) GetWorkcenterIdOk() (*string, bool)`

GetWorkcenterIdOk returns a tuple with the WorkcenterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkcenterId

`func (o *JobSchedulingApiScheduleJobOperationsRequest) SetWorkcenterId(v string)`

SetWorkcenterId sets WorkcenterId field to given value.

### HasWorkcenterId

`func (o *JobSchedulingApiScheduleJobOperationsRequest) HasWorkcenterId() bool`

HasWorkcenterId returns a boolean if a field has been set.

### GetStartDateTime

`func (o *JobSchedulingApiScheduleJobOperationsRequest) GetStartDateTime() time.Time`

GetStartDateTime returns the StartDateTime field if non-nil, zero value otherwise.

### GetStartDateTimeOk

`func (o *JobSchedulingApiScheduleJobOperationsRequest) GetStartDateTimeOk() (*time.Time, bool)`

GetStartDateTimeOk returns a tuple with the StartDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartDateTime

`func (o *JobSchedulingApiScheduleJobOperationsRequest) SetStartDateTime(v time.Time)`

SetStartDateTime sets StartDateTime field to given value.

### HasStartDateTime

`func (o *JobSchedulingApiScheduleJobOperationsRequest) HasStartDateTime() bool`

HasStartDateTime returns a boolean if a field has been set.

### GetRunLength

`func (o *JobSchedulingApiScheduleJobOperationsRequest) GetRunLength() int32`

GetRunLength returns the RunLength field if non-nil, zero value otherwise.

### GetRunLengthOk

`func (o *JobSchedulingApiScheduleJobOperationsRequest) GetRunLengthOk() (*int32, bool)`

GetRunLengthOk returns a tuple with the RunLength field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunLength

`func (o *JobSchedulingApiScheduleJobOperationsRequest) SetRunLength(v int32)`

SetRunLength sets RunLength field to given value.

### HasRunLength

`func (o *JobSchedulingApiScheduleJobOperationsRequest) HasRunLength() bool`

HasRunLength returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


