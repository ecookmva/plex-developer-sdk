# JobSchedulingApiListJobsItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | A unique identifier of the production job. | [optional] 
**ExternalJobCode** | Pointer to **string** | A code or number assigned to the production job in an external scheduling system. | [optional] 
**JobNumber** | Pointer to **string** | Job number, including prefix and suffix, associated to jobId. | [optional] 
**CreatedDate** | Pointer to **time.Time** | Date on which the job was created. | [optional] 
**PartId** | Pointer to **string** | A unique identifier of the part. | [optional] 
**PartNumber** | Pointer to **string** | Part Number associated to partId. | [optional] 
**PartRevision** | Pointer to **string** | Part Revision associated to partId. | [optional] 
**PartNumberRevision** | Pointer to **string** | Combination of Part Number and Revision associated to partId, separated with the value from the Part Rev Separator configuration setting. | [optional] 
**DueDate** | Pointer to **time.Time** | Date by which the entire job quantity must be completed. | [optional] 
**CompletedDate** | Pointer to **time.Time** | Date on which the job was completed. | [optional] 
**Quantity** | Pointer to **float64** | The quantity of parts that must be produced in order to complete the job. | [optional] 
**QuantityCompleted** | Pointer to **float64** | The quantity of parts produced. | [optional] 
**JobStatus** | Pointer to **string** | Status of the job. Setup Table &amp;quot;Job Status&amp;quot; (part.dbo.Job_Status). | [optional] 
**BuildingId** | Pointer to **string** | A unique identifier of the building in which the job is completed. | [optional] 
**BuildingCode** | Pointer to **string** | Building Code associated to buidlingId. | [optional] 
**JobType** | Pointer to **string** | The job type associated to job. Setup Table &amp;quot;Job Type&amp;quot; (part.dbo.Job_Type). | [optional] 
**EarliestStartDateTime** | Pointer to **time.Time** | The earliest date the job can be started on. | [optional] 
**Priority** | Pointer to **string** | The priority assigned to the job. | [optional] 

## Methods

### NewJobSchedulingApiListJobsItem

`func NewJobSchedulingApiListJobsItem() *JobSchedulingApiListJobsItem`

NewJobSchedulingApiListJobsItem instantiates a new JobSchedulingApiListJobsItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewJobSchedulingApiListJobsItemWithDefaults

`func NewJobSchedulingApiListJobsItemWithDefaults() *JobSchedulingApiListJobsItem`

NewJobSchedulingApiListJobsItemWithDefaults instantiates a new JobSchedulingApiListJobsItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *JobSchedulingApiListJobsItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *JobSchedulingApiListJobsItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *JobSchedulingApiListJobsItem) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *JobSchedulingApiListJobsItem) HasId() bool`

HasId returns a boolean if a field has been set.

### GetExternalJobCode

`func (o *JobSchedulingApiListJobsItem) GetExternalJobCode() string`

GetExternalJobCode returns the ExternalJobCode field if non-nil, zero value otherwise.

### GetExternalJobCodeOk

`func (o *JobSchedulingApiListJobsItem) GetExternalJobCodeOk() (*string, bool)`

GetExternalJobCodeOk returns a tuple with the ExternalJobCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalJobCode

`func (o *JobSchedulingApiListJobsItem) SetExternalJobCode(v string)`

SetExternalJobCode sets ExternalJobCode field to given value.

### HasExternalJobCode

`func (o *JobSchedulingApiListJobsItem) HasExternalJobCode() bool`

HasExternalJobCode returns a boolean if a field has been set.

### GetJobNumber

`func (o *JobSchedulingApiListJobsItem) GetJobNumber() string`

GetJobNumber returns the JobNumber field if non-nil, zero value otherwise.

### GetJobNumberOk

`func (o *JobSchedulingApiListJobsItem) GetJobNumberOk() (*string, bool)`

GetJobNumberOk returns a tuple with the JobNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobNumber

`func (o *JobSchedulingApiListJobsItem) SetJobNumber(v string)`

SetJobNumber sets JobNumber field to given value.

### HasJobNumber

`func (o *JobSchedulingApiListJobsItem) HasJobNumber() bool`

HasJobNumber returns a boolean if a field has been set.

### GetCreatedDate

`func (o *JobSchedulingApiListJobsItem) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *JobSchedulingApiListJobsItem) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *JobSchedulingApiListJobsItem) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *JobSchedulingApiListJobsItem) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.

### GetPartId

`func (o *JobSchedulingApiListJobsItem) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *JobSchedulingApiListJobsItem) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *JobSchedulingApiListJobsItem) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *JobSchedulingApiListJobsItem) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetPartNumber

`func (o *JobSchedulingApiListJobsItem) GetPartNumber() string`

GetPartNumber returns the PartNumber field if non-nil, zero value otherwise.

### GetPartNumberOk

`func (o *JobSchedulingApiListJobsItem) GetPartNumberOk() (*string, bool)`

GetPartNumberOk returns a tuple with the PartNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumber

`func (o *JobSchedulingApiListJobsItem) SetPartNumber(v string)`

SetPartNumber sets PartNumber field to given value.

### HasPartNumber

`func (o *JobSchedulingApiListJobsItem) HasPartNumber() bool`

HasPartNumber returns a boolean if a field has been set.

### GetPartRevision

`func (o *JobSchedulingApiListJobsItem) GetPartRevision() string`

GetPartRevision returns the PartRevision field if non-nil, zero value otherwise.

### GetPartRevisionOk

`func (o *JobSchedulingApiListJobsItem) GetPartRevisionOk() (*string, bool)`

GetPartRevisionOk returns a tuple with the PartRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartRevision

`func (o *JobSchedulingApiListJobsItem) SetPartRevision(v string)`

SetPartRevision sets PartRevision field to given value.

### HasPartRevision

`func (o *JobSchedulingApiListJobsItem) HasPartRevision() bool`

HasPartRevision returns a boolean if a field has been set.

### GetPartNumberRevision

`func (o *JobSchedulingApiListJobsItem) GetPartNumberRevision() string`

GetPartNumberRevision returns the PartNumberRevision field if non-nil, zero value otherwise.

### GetPartNumberRevisionOk

`func (o *JobSchedulingApiListJobsItem) GetPartNumberRevisionOk() (*string, bool)`

GetPartNumberRevisionOk returns a tuple with the PartNumberRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumberRevision

`func (o *JobSchedulingApiListJobsItem) SetPartNumberRevision(v string)`

SetPartNumberRevision sets PartNumberRevision field to given value.

### HasPartNumberRevision

`func (o *JobSchedulingApiListJobsItem) HasPartNumberRevision() bool`

HasPartNumberRevision returns a boolean if a field has been set.

### GetDueDate

`func (o *JobSchedulingApiListJobsItem) GetDueDate() time.Time`

GetDueDate returns the DueDate field if non-nil, zero value otherwise.

### GetDueDateOk

`func (o *JobSchedulingApiListJobsItem) GetDueDateOk() (*time.Time, bool)`

GetDueDateOk returns a tuple with the DueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueDate

`func (o *JobSchedulingApiListJobsItem) SetDueDate(v time.Time)`

SetDueDate sets DueDate field to given value.

### HasDueDate

`func (o *JobSchedulingApiListJobsItem) HasDueDate() bool`

HasDueDate returns a boolean if a field has been set.

### GetCompletedDate

`func (o *JobSchedulingApiListJobsItem) GetCompletedDate() time.Time`

GetCompletedDate returns the CompletedDate field if non-nil, zero value otherwise.

### GetCompletedDateOk

`func (o *JobSchedulingApiListJobsItem) GetCompletedDateOk() (*time.Time, bool)`

GetCompletedDateOk returns a tuple with the CompletedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedDate

`func (o *JobSchedulingApiListJobsItem) SetCompletedDate(v time.Time)`

SetCompletedDate sets CompletedDate field to given value.

### HasCompletedDate

`func (o *JobSchedulingApiListJobsItem) HasCompletedDate() bool`

HasCompletedDate returns a boolean if a field has been set.

### GetQuantity

`func (o *JobSchedulingApiListJobsItem) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *JobSchedulingApiListJobsItem) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *JobSchedulingApiListJobsItem) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *JobSchedulingApiListJobsItem) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetQuantityCompleted

`func (o *JobSchedulingApiListJobsItem) GetQuantityCompleted() float64`

GetQuantityCompleted returns the QuantityCompleted field if non-nil, zero value otherwise.

### GetQuantityCompletedOk

`func (o *JobSchedulingApiListJobsItem) GetQuantityCompletedOk() (*float64, bool)`

GetQuantityCompletedOk returns a tuple with the QuantityCompleted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantityCompleted

`func (o *JobSchedulingApiListJobsItem) SetQuantityCompleted(v float64)`

SetQuantityCompleted sets QuantityCompleted field to given value.

### HasQuantityCompleted

`func (o *JobSchedulingApiListJobsItem) HasQuantityCompleted() bool`

HasQuantityCompleted returns a boolean if a field has been set.

### GetJobStatus

`func (o *JobSchedulingApiListJobsItem) GetJobStatus() string`

GetJobStatus returns the JobStatus field if non-nil, zero value otherwise.

### GetJobStatusOk

`func (o *JobSchedulingApiListJobsItem) GetJobStatusOk() (*string, bool)`

GetJobStatusOk returns a tuple with the JobStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobStatus

`func (o *JobSchedulingApiListJobsItem) SetJobStatus(v string)`

SetJobStatus sets JobStatus field to given value.

### HasJobStatus

`func (o *JobSchedulingApiListJobsItem) HasJobStatus() bool`

HasJobStatus returns a boolean if a field has been set.

### GetBuildingId

`func (o *JobSchedulingApiListJobsItem) GetBuildingId() string`

GetBuildingId returns the BuildingId field if non-nil, zero value otherwise.

### GetBuildingIdOk

`func (o *JobSchedulingApiListJobsItem) GetBuildingIdOk() (*string, bool)`

GetBuildingIdOk returns a tuple with the BuildingId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildingId

`func (o *JobSchedulingApiListJobsItem) SetBuildingId(v string)`

SetBuildingId sets BuildingId field to given value.

### HasBuildingId

`func (o *JobSchedulingApiListJobsItem) HasBuildingId() bool`

HasBuildingId returns a boolean if a field has been set.

### GetBuildingCode

`func (o *JobSchedulingApiListJobsItem) GetBuildingCode() string`

GetBuildingCode returns the BuildingCode field if non-nil, zero value otherwise.

### GetBuildingCodeOk

`func (o *JobSchedulingApiListJobsItem) GetBuildingCodeOk() (*string, bool)`

GetBuildingCodeOk returns a tuple with the BuildingCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildingCode

`func (o *JobSchedulingApiListJobsItem) SetBuildingCode(v string)`

SetBuildingCode sets BuildingCode field to given value.

### HasBuildingCode

`func (o *JobSchedulingApiListJobsItem) HasBuildingCode() bool`

HasBuildingCode returns a boolean if a field has been set.

### GetJobType

`func (o *JobSchedulingApiListJobsItem) GetJobType() string`

GetJobType returns the JobType field if non-nil, zero value otherwise.

### GetJobTypeOk

`func (o *JobSchedulingApiListJobsItem) GetJobTypeOk() (*string, bool)`

GetJobTypeOk returns a tuple with the JobType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobType

`func (o *JobSchedulingApiListJobsItem) SetJobType(v string)`

SetJobType sets JobType field to given value.

### HasJobType

`func (o *JobSchedulingApiListJobsItem) HasJobType() bool`

HasJobType returns a boolean if a field has been set.

### GetEarliestStartDateTime

`func (o *JobSchedulingApiListJobsItem) GetEarliestStartDateTime() time.Time`

GetEarliestStartDateTime returns the EarliestStartDateTime field if non-nil, zero value otherwise.

### GetEarliestStartDateTimeOk

`func (o *JobSchedulingApiListJobsItem) GetEarliestStartDateTimeOk() (*time.Time, bool)`

GetEarliestStartDateTimeOk returns a tuple with the EarliestStartDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEarliestStartDateTime

`func (o *JobSchedulingApiListJobsItem) SetEarliestStartDateTime(v time.Time)`

SetEarliestStartDateTime sets EarliestStartDateTime field to given value.

### HasEarliestStartDateTime

`func (o *JobSchedulingApiListJobsItem) HasEarliestStartDateTime() bool`

HasEarliestStartDateTime returns a boolean if a field has been set.

### GetPriority

`func (o *JobSchedulingApiListJobsItem) GetPriority() string`

GetPriority returns the Priority field if non-nil, zero value otherwise.

### GetPriorityOk

`func (o *JobSchedulingApiListJobsItem) GetPriorityOk() (*string, bool)`

GetPriorityOk returns a tuple with the Priority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriority

`func (o *JobSchedulingApiListJobsItem) SetPriority(v string)`

SetPriority sets Priority field to given value.

### HasPriority

`func (o *JobSchedulingApiListJobsItem) HasPriority() bool`

HasPriority returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


