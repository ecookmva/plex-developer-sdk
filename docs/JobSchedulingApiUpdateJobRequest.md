# JobSchedulingApiUpdateJobRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DueDate** | Pointer to **time.Time** | Date by which the entire job operation quantity must be completed. | [optional] 
**Quantity** | Pointer to **float64** | The quantity of parts that must be produced in order to complete the job operation. | [optional] 
**BuildingId** | Pointer to **string** | A unique identifier of the building in which the job is completed. | [optional] 
**JobType** | Pointer to **string** | The job type associated to job. Setup Table &amp;quot;Job Type&amp;quot; (part.dbo.Job_Type). | [optional] 
**Priority** | Pointer to **string** | The priority of the job. Setup Table &amp;quot;Priority (Part)&amp;quot; (part.dbo.Priority). If not provided the default priority will be used. | [optional] 
**EarliestStartDateTime** | Pointer to **time.Time** | The earliest scheduled start time for a job. | [optional] 

## Methods

### NewJobSchedulingApiUpdateJobRequest

`func NewJobSchedulingApiUpdateJobRequest() *JobSchedulingApiUpdateJobRequest`

NewJobSchedulingApiUpdateJobRequest instantiates a new JobSchedulingApiUpdateJobRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewJobSchedulingApiUpdateJobRequestWithDefaults

`func NewJobSchedulingApiUpdateJobRequestWithDefaults() *JobSchedulingApiUpdateJobRequest`

NewJobSchedulingApiUpdateJobRequestWithDefaults instantiates a new JobSchedulingApiUpdateJobRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDueDate

`func (o *JobSchedulingApiUpdateJobRequest) GetDueDate() time.Time`

GetDueDate returns the DueDate field if non-nil, zero value otherwise.

### GetDueDateOk

`func (o *JobSchedulingApiUpdateJobRequest) GetDueDateOk() (*time.Time, bool)`

GetDueDateOk returns a tuple with the DueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueDate

`func (o *JobSchedulingApiUpdateJobRequest) SetDueDate(v time.Time)`

SetDueDate sets DueDate field to given value.

### HasDueDate

`func (o *JobSchedulingApiUpdateJobRequest) HasDueDate() bool`

HasDueDate returns a boolean if a field has been set.

### GetQuantity

`func (o *JobSchedulingApiUpdateJobRequest) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *JobSchedulingApiUpdateJobRequest) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *JobSchedulingApiUpdateJobRequest) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *JobSchedulingApiUpdateJobRequest) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetBuildingId

`func (o *JobSchedulingApiUpdateJobRequest) GetBuildingId() string`

GetBuildingId returns the BuildingId field if non-nil, zero value otherwise.

### GetBuildingIdOk

`func (o *JobSchedulingApiUpdateJobRequest) GetBuildingIdOk() (*string, bool)`

GetBuildingIdOk returns a tuple with the BuildingId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildingId

`func (o *JobSchedulingApiUpdateJobRequest) SetBuildingId(v string)`

SetBuildingId sets BuildingId field to given value.

### HasBuildingId

`func (o *JobSchedulingApiUpdateJobRequest) HasBuildingId() bool`

HasBuildingId returns a boolean if a field has been set.

### GetJobType

`func (o *JobSchedulingApiUpdateJobRequest) GetJobType() string`

GetJobType returns the JobType field if non-nil, zero value otherwise.

### GetJobTypeOk

`func (o *JobSchedulingApiUpdateJobRequest) GetJobTypeOk() (*string, bool)`

GetJobTypeOk returns a tuple with the JobType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobType

`func (o *JobSchedulingApiUpdateJobRequest) SetJobType(v string)`

SetJobType sets JobType field to given value.

### HasJobType

`func (o *JobSchedulingApiUpdateJobRequest) HasJobType() bool`

HasJobType returns a boolean if a field has been set.

### GetPriority

`func (o *JobSchedulingApiUpdateJobRequest) GetPriority() string`

GetPriority returns the Priority field if non-nil, zero value otherwise.

### GetPriorityOk

`func (o *JobSchedulingApiUpdateJobRequest) GetPriorityOk() (*string, bool)`

GetPriorityOk returns a tuple with the Priority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriority

`func (o *JobSchedulingApiUpdateJobRequest) SetPriority(v string)`

SetPriority sets Priority field to given value.

### HasPriority

`func (o *JobSchedulingApiUpdateJobRequest) HasPriority() bool`

HasPriority returns a boolean if a field has been set.

### GetEarliestStartDateTime

`func (o *JobSchedulingApiUpdateJobRequest) GetEarliestStartDateTime() time.Time`

GetEarliestStartDateTime returns the EarliestStartDateTime field if non-nil, zero value otherwise.

### GetEarliestStartDateTimeOk

`func (o *JobSchedulingApiUpdateJobRequest) GetEarliestStartDateTimeOk() (*time.Time, bool)`

GetEarliestStartDateTimeOk returns a tuple with the EarliestStartDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEarliestStartDateTime

`func (o *JobSchedulingApiUpdateJobRequest) SetEarliestStartDateTime(v time.Time)`

SetEarliestStartDateTime sets EarliestStartDateTime field to given value.

### HasEarliestStartDateTime

`func (o *JobSchedulingApiUpdateJobRequest) HasEarliestStartDateTime() bool`

HasEarliestStartDateTime returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


