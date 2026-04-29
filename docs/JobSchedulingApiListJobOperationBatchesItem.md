# JobSchedulingApiListJobOperationBatchesItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | A unique identifier of the batch. | [optional] 
**Number** | Pointer to **int32** | Identifier of the batch for the current job operation. | [optional] 
**BatchStatus** | Pointer to **string** | The status of the batch. | [optional] 
**Size** | Pointer to **float64** | The quantity to be produced in the batch. | [optional] 
**WorkcenterId** | Pointer to **string** | A unique identifier of the workcenter. | [optional] 
**WorkcenterCode** | Pointer to **string** | A short name associated with the workcenter ID, and a unique code to reference the workcenter. This code displays throughout the system, primarily on the Control Panel. 50 characters max. | [optional] 
**JobOperationId** | Pointer to **string** | A unique identifier for the job operation. | [optional] 
**DueDateTime** | Pointer to **time.Time** | The due date of the batch. | [optional] 
**StartDateTime** | Pointer to **time.Time** | The scheduled start date of the batch. | [optional] 

## Methods

### NewJobSchedulingApiListJobOperationBatchesItem

`func NewJobSchedulingApiListJobOperationBatchesItem() *JobSchedulingApiListJobOperationBatchesItem`

NewJobSchedulingApiListJobOperationBatchesItem instantiates a new JobSchedulingApiListJobOperationBatchesItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewJobSchedulingApiListJobOperationBatchesItemWithDefaults

`func NewJobSchedulingApiListJobOperationBatchesItemWithDefaults() *JobSchedulingApiListJobOperationBatchesItem`

NewJobSchedulingApiListJobOperationBatchesItemWithDefaults instantiates a new JobSchedulingApiListJobOperationBatchesItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *JobSchedulingApiListJobOperationBatchesItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *JobSchedulingApiListJobOperationBatchesItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *JobSchedulingApiListJobOperationBatchesItem) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *JobSchedulingApiListJobOperationBatchesItem) HasId() bool`

HasId returns a boolean if a field has been set.

### GetNumber

`func (o *JobSchedulingApiListJobOperationBatchesItem) GetNumber() int32`

GetNumber returns the Number field if non-nil, zero value otherwise.

### GetNumberOk

`func (o *JobSchedulingApiListJobOperationBatchesItem) GetNumberOk() (*int32, bool)`

GetNumberOk returns a tuple with the Number field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumber

`func (o *JobSchedulingApiListJobOperationBatchesItem) SetNumber(v int32)`

SetNumber sets Number field to given value.

### HasNumber

`func (o *JobSchedulingApiListJobOperationBatchesItem) HasNumber() bool`

HasNumber returns a boolean if a field has been set.

### GetBatchStatus

`func (o *JobSchedulingApiListJobOperationBatchesItem) GetBatchStatus() string`

GetBatchStatus returns the BatchStatus field if non-nil, zero value otherwise.

### GetBatchStatusOk

`func (o *JobSchedulingApiListJobOperationBatchesItem) GetBatchStatusOk() (*string, bool)`

GetBatchStatusOk returns a tuple with the BatchStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBatchStatus

`func (o *JobSchedulingApiListJobOperationBatchesItem) SetBatchStatus(v string)`

SetBatchStatus sets BatchStatus field to given value.

### HasBatchStatus

`func (o *JobSchedulingApiListJobOperationBatchesItem) HasBatchStatus() bool`

HasBatchStatus returns a boolean if a field has been set.

### GetSize

`func (o *JobSchedulingApiListJobOperationBatchesItem) GetSize() float64`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *JobSchedulingApiListJobOperationBatchesItem) GetSizeOk() (*float64, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *JobSchedulingApiListJobOperationBatchesItem) SetSize(v float64)`

SetSize sets Size field to given value.

### HasSize

`func (o *JobSchedulingApiListJobOperationBatchesItem) HasSize() bool`

HasSize returns a boolean if a field has been set.

### GetWorkcenterId

`func (o *JobSchedulingApiListJobOperationBatchesItem) GetWorkcenterId() string`

GetWorkcenterId returns the WorkcenterId field if non-nil, zero value otherwise.

### GetWorkcenterIdOk

`func (o *JobSchedulingApiListJobOperationBatchesItem) GetWorkcenterIdOk() (*string, bool)`

GetWorkcenterIdOk returns a tuple with the WorkcenterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkcenterId

`func (o *JobSchedulingApiListJobOperationBatchesItem) SetWorkcenterId(v string)`

SetWorkcenterId sets WorkcenterId field to given value.

### HasWorkcenterId

`func (o *JobSchedulingApiListJobOperationBatchesItem) HasWorkcenterId() bool`

HasWorkcenterId returns a boolean if a field has been set.

### GetWorkcenterCode

`func (o *JobSchedulingApiListJobOperationBatchesItem) GetWorkcenterCode() string`

GetWorkcenterCode returns the WorkcenterCode field if non-nil, zero value otherwise.

### GetWorkcenterCodeOk

`func (o *JobSchedulingApiListJobOperationBatchesItem) GetWorkcenterCodeOk() (*string, bool)`

GetWorkcenterCodeOk returns a tuple with the WorkcenterCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkcenterCode

`func (o *JobSchedulingApiListJobOperationBatchesItem) SetWorkcenterCode(v string)`

SetWorkcenterCode sets WorkcenterCode field to given value.

### HasWorkcenterCode

`func (o *JobSchedulingApiListJobOperationBatchesItem) HasWorkcenterCode() bool`

HasWorkcenterCode returns a boolean if a field has been set.

### GetJobOperationId

`func (o *JobSchedulingApiListJobOperationBatchesItem) GetJobOperationId() string`

GetJobOperationId returns the JobOperationId field if non-nil, zero value otherwise.

### GetJobOperationIdOk

`func (o *JobSchedulingApiListJobOperationBatchesItem) GetJobOperationIdOk() (*string, bool)`

GetJobOperationIdOk returns a tuple with the JobOperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobOperationId

`func (o *JobSchedulingApiListJobOperationBatchesItem) SetJobOperationId(v string)`

SetJobOperationId sets JobOperationId field to given value.

### HasJobOperationId

`func (o *JobSchedulingApiListJobOperationBatchesItem) HasJobOperationId() bool`

HasJobOperationId returns a boolean if a field has been set.

### GetDueDateTime

`func (o *JobSchedulingApiListJobOperationBatchesItem) GetDueDateTime() time.Time`

GetDueDateTime returns the DueDateTime field if non-nil, zero value otherwise.

### GetDueDateTimeOk

`func (o *JobSchedulingApiListJobOperationBatchesItem) GetDueDateTimeOk() (*time.Time, bool)`

GetDueDateTimeOk returns a tuple with the DueDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueDateTime

`func (o *JobSchedulingApiListJobOperationBatchesItem) SetDueDateTime(v time.Time)`

SetDueDateTime sets DueDateTime field to given value.

### HasDueDateTime

`func (o *JobSchedulingApiListJobOperationBatchesItem) HasDueDateTime() bool`

HasDueDateTime returns a boolean if a field has been set.

### GetStartDateTime

`func (o *JobSchedulingApiListJobOperationBatchesItem) GetStartDateTime() time.Time`

GetStartDateTime returns the StartDateTime field if non-nil, zero value otherwise.

### GetStartDateTimeOk

`func (o *JobSchedulingApiListJobOperationBatchesItem) GetStartDateTimeOk() (*time.Time, bool)`

GetStartDateTimeOk returns a tuple with the StartDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartDateTime

`func (o *JobSchedulingApiListJobOperationBatchesItem) SetStartDateTime(v time.Time)`

SetStartDateTime sets StartDateTime field to given value.

### HasStartDateTime

`func (o *JobSchedulingApiListJobOperationBatchesItem) HasStartDateTime() bool`

HasStartDateTime returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


