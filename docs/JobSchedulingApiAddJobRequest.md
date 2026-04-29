# JobSchedulingApiAddJobRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PartId** | Pointer to **string** | A unique identifier of the part. | [optional] 
**DueDate** | Pointer to **time.Time** | Date by which the entire job quantity must be completed. | [optional] 
**Quantity** | Pointer to **float64** | The quantity of parts that must be produced in order to complete the job. | [optional] 
**ExternalJobCode** | Pointer to **string** | A code or number assigned to the production job in an external scheduling system. Must be unique. | [optional] 
**BuildingId** | Pointer to **string** | A unique identifier of the building in which the job is completed. | [optional] 
**JobType** | Pointer to **string** | The job type associated to job. If no value submitted, the Job Type configured as &amp;quot;default&amp;quot; is assigned to the job. Setup Table &amp;quot;Job Type&amp;quot; (part.dbo.Job_Type). | [optional] 
**JobNumberPrefix** | Pointer to **string** | A prefix to be added before the job number. | [optional] 
**JobNumberSuffix** | Pointer to **string** | A suffix to be added after the job number. | [optional] 
**JobNumber** | Pointer to **string** | The job number identifying the job. | [optional] 
**Priority** | Pointer to **string** | The priority of the job. Setup Table &amp;quot;Priority (Part)&amp;quot; (part.dbo.Priority). If not provided the default priority will be used. | [optional] 
**EarliestStartDateTime** | Pointer to **time.Time** | The earliest scheduled start time for a job. | [optional] 

## Methods

### NewJobSchedulingApiAddJobRequest

`func NewJobSchedulingApiAddJobRequest() *JobSchedulingApiAddJobRequest`

NewJobSchedulingApiAddJobRequest instantiates a new JobSchedulingApiAddJobRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewJobSchedulingApiAddJobRequestWithDefaults

`func NewJobSchedulingApiAddJobRequestWithDefaults() *JobSchedulingApiAddJobRequest`

NewJobSchedulingApiAddJobRequestWithDefaults instantiates a new JobSchedulingApiAddJobRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPartId

`func (o *JobSchedulingApiAddJobRequest) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *JobSchedulingApiAddJobRequest) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *JobSchedulingApiAddJobRequest) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *JobSchedulingApiAddJobRequest) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetDueDate

`func (o *JobSchedulingApiAddJobRequest) GetDueDate() time.Time`

GetDueDate returns the DueDate field if non-nil, zero value otherwise.

### GetDueDateOk

`func (o *JobSchedulingApiAddJobRequest) GetDueDateOk() (*time.Time, bool)`

GetDueDateOk returns a tuple with the DueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueDate

`func (o *JobSchedulingApiAddJobRequest) SetDueDate(v time.Time)`

SetDueDate sets DueDate field to given value.

### HasDueDate

`func (o *JobSchedulingApiAddJobRequest) HasDueDate() bool`

HasDueDate returns a boolean if a field has been set.

### GetQuantity

`func (o *JobSchedulingApiAddJobRequest) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *JobSchedulingApiAddJobRequest) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *JobSchedulingApiAddJobRequest) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *JobSchedulingApiAddJobRequest) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetExternalJobCode

`func (o *JobSchedulingApiAddJobRequest) GetExternalJobCode() string`

GetExternalJobCode returns the ExternalJobCode field if non-nil, zero value otherwise.

### GetExternalJobCodeOk

`func (o *JobSchedulingApiAddJobRequest) GetExternalJobCodeOk() (*string, bool)`

GetExternalJobCodeOk returns a tuple with the ExternalJobCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalJobCode

`func (o *JobSchedulingApiAddJobRequest) SetExternalJobCode(v string)`

SetExternalJobCode sets ExternalJobCode field to given value.

### HasExternalJobCode

`func (o *JobSchedulingApiAddJobRequest) HasExternalJobCode() bool`

HasExternalJobCode returns a boolean if a field has been set.

### GetBuildingId

`func (o *JobSchedulingApiAddJobRequest) GetBuildingId() string`

GetBuildingId returns the BuildingId field if non-nil, zero value otherwise.

### GetBuildingIdOk

`func (o *JobSchedulingApiAddJobRequest) GetBuildingIdOk() (*string, bool)`

GetBuildingIdOk returns a tuple with the BuildingId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildingId

`func (o *JobSchedulingApiAddJobRequest) SetBuildingId(v string)`

SetBuildingId sets BuildingId field to given value.

### HasBuildingId

`func (o *JobSchedulingApiAddJobRequest) HasBuildingId() bool`

HasBuildingId returns a boolean if a field has been set.

### GetJobType

`func (o *JobSchedulingApiAddJobRequest) GetJobType() string`

GetJobType returns the JobType field if non-nil, zero value otherwise.

### GetJobTypeOk

`func (o *JobSchedulingApiAddJobRequest) GetJobTypeOk() (*string, bool)`

GetJobTypeOk returns a tuple with the JobType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobType

`func (o *JobSchedulingApiAddJobRequest) SetJobType(v string)`

SetJobType sets JobType field to given value.

### HasJobType

`func (o *JobSchedulingApiAddJobRequest) HasJobType() bool`

HasJobType returns a boolean if a field has been set.

### GetJobNumberPrefix

`func (o *JobSchedulingApiAddJobRequest) GetJobNumberPrefix() string`

GetJobNumberPrefix returns the JobNumberPrefix field if non-nil, zero value otherwise.

### GetJobNumberPrefixOk

`func (o *JobSchedulingApiAddJobRequest) GetJobNumberPrefixOk() (*string, bool)`

GetJobNumberPrefixOk returns a tuple with the JobNumberPrefix field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobNumberPrefix

`func (o *JobSchedulingApiAddJobRequest) SetJobNumberPrefix(v string)`

SetJobNumberPrefix sets JobNumberPrefix field to given value.

### HasJobNumberPrefix

`func (o *JobSchedulingApiAddJobRequest) HasJobNumberPrefix() bool`

HasJobNumberPrefix returns a boolean if a field has been set.

### GetJobNumberSuffix

`func (o *JobSchedulingApiAddJobRequest) GetJobNumberSuffix() string`

GetJobNumberSuffix returns the JobNumberSuffix field if non-nil, zero value otherwise.

### GetJobNumberSuffixOk

`func (o *JobSchedulingApiAddJobRequest) GetJobNumberSuffixOk() (*string, bool)`

GetJobNumberSuffixOk returns a tuple with the JobNumberSuffix field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobNumberSuffix

`func (o *JobSchedulingApiAddJobRequest) SetJobNumberSuffix(v string)`

SetJobNumberSuffix sets JobNumberSuffix field to given value.

### HasJobNumberSuffix

`func (o *JobSchedulingApiAddJobRequest) HasJobNumberSuffix() bool`

HasJobNumberSuffix returns a boolean if a field has been set.

### GetJobNumber

`func (o *JobSchedulingApiAddJobRequest) GetJobNumber() string`

GetJobNumber returns the JobNumber field if non-nil, zero value otherwise.

### GetJobNumberOk

`func (o *JobSchedulingApiAddJobRequest) GetJobNumberOk() (*string, bool)`

GetJobNumberOk returns a tuple with the JobNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobNumber

`func (o *JobSchedulingApiAddJobRequest) SetJobNumber(v string)`

SetJobNumber sets JobNumber field to given value.

### HasJobNumber

`func (o *JobSchedulingApiAddJobRequest) HasJobNumber() bool`

HasJobNumber returns a boolean if a field has been set.

### GetPriority

`func (o *JobSchedulingApiAddJobRequest) GetPriority() string`

GetPriority returns the Priority field if non-nil, zero value otherwise.

### GetPriorityOk

`func (o *JobSchedulingApiAddJobRequest) GetPriorityOk() (*string, bool)`

GetPriorityOk returns a tuple with the Priority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriority

`func (o *JobSchedulingApiAddJobRequest) SetPriority(v string)`

SetPriority sets Priority field to given value.

### HasPriority

`func (o *JobSchedulingApiAddJobRequest) HasPriority() bool`

HasPriority returns a boolean if a field has been set.

### GetEarliestStartDateTime

`func (o *JobSchedulingApiAddJobRequest) GetEarliestStartDateTime() time.Time`

GetEarliestStartDateTime returns the EarliestStartDateTime field if non-nil, zero value otherwise.

### GetEarliestStartDateTimeOk

`func (o *JobSchedulingApiAddJobRequest) GetEarliestStartDateTimeOk() (*time.Time, bool)`

GetEarliestStartDateTimeOk returns a tuple with the EarliestStartDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEarliestStartDateTime

`func (o *JobSchedulingApiAddJobRequest) SetEarliestStartDateTime(v time.Time)`

SetEarliestStartDateTime sets EarliestStartDateTime field to given value.

### HasEarliestStartDateTime

`func (o *JobSchedulingApiAddJobRequest) HasEarliestStartDateTime() bool`

HasEarliestStartDateTime returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


