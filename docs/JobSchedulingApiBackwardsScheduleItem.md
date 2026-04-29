# JobSchedulingApiBackwardsScheduleItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**JobId** | Pointer to **string** | A unique identifier of the production job. | [optional] 
**JobNumber** | Pointer to **string** | Job number, including prefix and suffix, associated to jobId. | [optional] 
**PartId** | Pointer to **string** | A unique identifier of the part associated to the job operation. | [optional] 
**PartNumber** | Pointer to **string** | Part Number associated to partId. | [optional] 
**PartRevision** | Pointer to **string** | Part Revision associated to partId. | [optional] 
**PartNumberRevision** | Pointer to **string** | Combination of Part Number and Revision associated to partId, separated with the value from the Part Rev Separator configuration setting. | [optional] 
**JobOperationId** | Pointer to **string** | A unique identifier of the job operation. | [optional] 
**JobOperationNumber** | Pointer to **int32** | Operation Number associated to jobOperationId. | [optional] 
**OperationCode** | Pointer to **string** | Operation Code associated to jobOperationId. | [optional] 
**WorkcenterId** | Pointer to **string** | A unique identifier of the workcenter where the operation is scheduled to be performed. | [optional] 
**WorkcenterCode** | Pointer to **string** | Operation Code associated to workcenterId. | [optional] 
**Quantity** | Pointer to **float64** | The quantity of parts that must be produced in order to complete the job operation. | [optional] 
**QuantityCompleted** | Pointer to **float64** | The quantity of parts produced at job operation. | [optional] 
**DueDate** | Pointer to **time.Time** | Date by which the entire job operation must be completed. | [optional] 
**ScheduledStartDate** | Pointer to **time.Time** | Date on which the job operation is scheduled to start. | [optional] 
**CompletedDate** | Pointer to **time.Time** | Date on which the job operation was completed. | [optional] 
**JobOperationStatus** | Pointer to **string** | Status of the job operation. Setup Table &amp;quot;Job_Op_Status&amp;quot; (part.dbo.Job_Op_Status). | [optional] 
**SetupTime** | Pointer to **float64** | Time required to setup workcenter for job operation. Time returned is in hours. | [optional] 
**Rate** | Pointer to **float64** | Standard rate of goods that can be produced at this operation during a given time period. | [optional] 
**UnitOfMeasure** | Pointer to **string** | Unit of measure of the rate. Determined in setting &amp;quot;Job Op Rate Unit&amp;quot;. Possible values are &amp;quot;hrs&amp;quot;, &amp;quot;hrs/pc&amp;quot;, or &amp;quot;pcs/hr&amp;quot;. | [optional] 
**RunTime** | Pointer to **float64** | Time required to complete job operation. Time returned is in hours. | [optional] 
**BatchCriteria** | Pointer to **string** | Batch ID or code established by external software. Used to specify a batch ID that, if shared among two operations, could result in the operations being run in parallel on a common approved workcenter. | [optional] 
**PartOperationType** | Pointer to **string** | The part operation type. | [optional] 
**BatchOperation** | Pointer to **bool** | A flag indicating whether the job operation is a variable BOM batch operation. | [optional] 
**PreProcessOperation** | Pointer to **bool** | A flag indicating whether the job operation is a pre-process operation. | [optional] 

## Methods

### NewJobSchedulingApiBackwardsScheduleItem

`func NewJobSchedulingApiBackwardsScheduleItem() *JobSchedulingApiBackwardsScheduleItem`

NewJobSchedulingApiBackwardsScheduleItem instantiates a new JobSchedulingApiBackwardsScheduleItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewJobSchedulingApiBackwardsScheduleItemWithDefaults

`func NewJobSchedulingApiBackwardsScheduleItemWithDefaults() *JobSchedulingApiBackwardsScheduleItem`

NewJobSchedulingApiBackwardsScheduleItemWithDefaults instantiates a new JobSchedulingApiBackwardsScheduleItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetJobId

`func (o *JobSchedulingApiBackwardsScheduleItem) GetJobId() string`

GetJobId returns the JobId field if non-nil, zero value otherwise.

### GetJobIdOk

`func (o *JobSchedulingApiBackwardsScheduleItem) GetJobIdOk() (*string, bool)`

GetJobIdOk returns a tuple with the JobId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobId

`func (o *JobSchedulingApiBackwardsScheduleItem) SetJobId(v string)`

SetJobId sets JobId field to given value.

### HasJobId

`func (o *JobSchedulingApiBackwardsScheduleItem) HasJobId() bool`

HasJobId returns a boolean if a field has been set.

### GetJobNumber

`func (o *JobSchedulingApiBackwardsScheduleItem) GetJobNumber() string`

GetJobNumber returns the JobNumber field if non-nil, zero value otherwise.

### GetJobNumberOk

`func (o *JobSchedulingApiBackwardsScheduleItem) GetJobNumberOk() (*string, bool)`

GetJobNumberOk returns a tuple with the JobNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobNumber

`func (o *JobSchedulingApiBackwardsScheduleItem) SetJobNumber(v string)`

SetJobNumber sets JobNumber field to given value.

### HasJobNumber

`func (o *JobSchedulingApiBackwardsScheduleItem) HasJobNumber() bool`

HasJobNumber returns a boolean if a field has been set.

### GetPartId

`func (o *JobSchedulingApiBackwardsScheduleItem) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *JobSchedulingApiBackwardsScheduleItem) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *JobSchedulingApiBackwardsScheduleItem) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *JobSchedulingApiBackwardsScheduleItem) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetPartNumber

`func (o *JobSchedulingApiBackwardsScheduleItem) GetPartNumber() string`

GetPartNumber returns the PartNumber field if non-nil, zero value otherwise.

### GetPartNumberOk

`func (o *JobSchedulingApiBackwardsScheduleItem) GetPartNumberOk() (*string, bool)`

GetPartNumberOk returns a tuple with the PartNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumber

`func (o *JobSchedulingApiBackwardsScheduleItem) SetPartNumber(v string)`

SetPartNumber sets PartNumber field to given value.

### HasPartNumber

`func (o *JobSchedulingApiBackwardsScheduleItem) HasPartNumber() bool`

HasPartNumber returns a boolean if a field has been set.

### GetPartRevision

`func (o *JobSchedulingApiBackwardsScheduleItem) GetPartRevision() string`

GetPartRevision returns the PartRevision field if non-nil, zero value otherwise.

### GetPartRevisionOk

`func (o *JobSchedulingApiBackwardsScheduleItem) GetPartRevisionOk() (*string, bool)`

GetPartRevisionOk returns a tuple with the PartRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartRevision

`func (o *JobSchedulingApiBackwardsScheduleItem) SetPartRevision(v string)`

SetPartRevision sets PartRevision field to given value.

### HasPartRevision

`func (o *JobSchedulingApiBackwardsScheduleItem) HasPartRevision() bool`

HasPartRevision returns a boolean if a field has been set.

### GetPartNumberRevision

`func (o *JobSchedulingApiBackwardsScheduleItem) GetPartNumberRevision() string`

GetPartNumberRevision returns the PartNumberRevision field if non-nil, zero value otherwise.

### GetPartNumberRevisionOk

`func (o *JobSchedulingApiBackwardsScheduleItem) GetPartNumberRevisionOk() (*string, bool)`

GetPartNumberRevisionOk returns a tuple with the PartNumberRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumberRevision

`func (o *JobSchedulingApiBackwardsScheduleItem) SetPartNumberRevision(v string)`

SetPartNumberRevision sets PartNumberRevision field to given value.

### HasPartNumberRevision

`func (o *JobSchedulingApiBackwardsScheduleItem) HasPartNumberRevision() bool`

HasPartNumberRevision returns a boolean if a field has been set.

### GetJobOperationId

`func (o *JobSchedulingApiBackwardsScheduleItem) GetJobOperationId() string`

GetJobOperationId returns the JobOperationId field if non-nil, zero value otherwise.

### GetJobOperationIdOk

`func (o *JobSchedulingApiBackwardsScheduleItem) GetJobOperationIdOk() (*string, bool)`

GetJobOperationIdOk returns a tuple with the JobOperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobOperationId

`func (o *JobSchedulingApiBackwardsScheduleItem) SetJobOperationId(v string)`

SetJobOperationId sets JobOperationId field to given value.

### HasJobOperationId

`func (o *JobSchedulingApiBackwardsScheduleItem) HasJobOperationId() bool`

HasJobOperationId returns a boolean if a field has been set.

### GetJobOperationNumber

`func (o *JobSchedulingApiBackwardsScheduleItem) GetJobOperationNumber() int32`

GetJobOperationNumber returns the JobOperationNumber field if non-nil, zero value otherwise.

### GetJobOperationNumberOk

`func (o *JobSchedulingApiBackwardsScheduleItem) GetJobOperationNumberOk() (*int32, bool)`

GetJobOperationNumberOk returns a tuple with the JobOperationNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobOperationNumber

`func (o *JobSchedulingApiBackwardsScheduleItem) SetJobOperationNumber(v int32)`

SetJobOperationNumber sets JobOperationNumber field to given value.

### HasJobOperationNumber

`func (o *JobSchedulingApiBackwardsScheduleItem) HasJobOperationNumber() bool`

HasJobOperationNumber returns a boolean if a field has been set.

### GetOperationCode

`func (o *JobSchedulingApiBackwardsScheduleItem) GetOperationCode() string`

GetOperationCode returns the OperationCode field if non-nil, zero value otherwise.

### GetOperationCodeOk

`func (o *JobSchedulingApiBackwardsScheduleItem) GetOperationCodeOk() (*string, bool)`

GetOperationCodeOk returns a tuple with the OperationCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationCode

`func (o *JobSchedulingApiBackwardsScheduleItem) SetOperationCode(v string)`

SetOperationCode sets OperationCode field to given value.

### HasOperationCode

`func (o *JobSchedulingApiBackwardsScheduleItem) HasOperationCode() bool`

HasOperationCode returns a boolean if a field has been set.

### GetWorkcenterId

`func (o *JobSchedulingApiBackwardsScheduleItem) GetWorkcenterId() string`

GetWorkcenterId returns the WorkcenterId field if non-nil, zero value otherwise.

### GetWorkcenterIdOk

`func (o *JobSchedulingApiBackwardsScheduleItem) GetWorkcenterIdOk() (*string, bool)`

GetWorkcenterIdOk returns a tuple with the WorkcenterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkcenterId

`func (o *JobSchedulingApiBackwardsScheduleItem) SetWorkcenterId(v string)`

SetWorkcenterId sets WorkcenterId field to given value.

### HasWorkcenterId

`func (o *JobSchedulingApiBackwardsScheduleItem) HasWorkcenterId() bool`

HasWorkcenterId returns a boolean if a field has been set.

### GetWorkcenterCode

`func (o *JobSchedulingApiBackwardsScheduleItem) GetWorkcenterCode() string`

GetWorkcenterCode returns the WorkcenterCode field if non-nil, zero value otherwise.

### GetWorkcenterCodeOk

`func (o *JobSchedulingApiBackwardsScheduleItem) GetWorkcenterCodeOk() (*string, bool)`

GetWorkcenterCodeOk returns a tuple with the WorkcenterCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkcenterCode

`func (o *JobSchedulingApiBackwardsScheduleItem) SetWorkcenterCode(v string)`

SetWorkcenterCode sets WorkcenterCode field to given value.

### HasWorkcenterCode

`func (o *JobSchedulingApiBackwardsScheduleItem) HasWorkcenterCode() bool`

HasWorkcenterCode returns a boolean if a field has been set.

### GetQuantity

`func (o *JobSchedulingApiBackwardsScheduleItem) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *JobSchedulingApiBackwardsScheduleItem) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *JobSchedulingApiBackwardsScheduleItem) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *JobSchedulingApiBackwardsScheduleItem) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetQuantityCompleted

`func (o *JobSchedulingApiBackwardsScheduleItem) GetQuantityCompleted() float64`

GetQuantityCompleted returns the QuantityCompleted field if non-nil, zero value otherwise.

### GetQuantityCompletedOk

`func (o *JobSchedulingApiBackwardsScheduleItem) GetQuantityCompletedOk() (*float64, bool)`

GetQuantityCompletedOk returns a tuple with the QuantityCompleted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantityCompleted

`func (o *JobSchedulingApiBackwardsScheduleItem) SetQuantityCompleted(v float64)`

SetQuantityCompleted sets QuantityCompleted field to given value.

### HasQuantityCompleted

`func (o *JobSchedulingApiBackwardsScheduleItem) HasQuantityCompleted() bool`

HasQuantityCompleted returns a boolean if a field has been set.

### GetDueDate

`func (o *JobSchedulingApiBackwardsScheduleItem) GetDueDate() time.Time`

GetDueDate returns the DueDate field if non-nil, zero value otherwise.

### GetDueDateOk

`func (o *JobSchedulingApiBackwardsScheduleItem) GetDueDateOk() (*time.Time, bool)`

GetDueDateOk returns a tuple with the DueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueDate

`func (o *JobSchedulingApiBackwardsScheduleItem) SetDueDate(v time.Time)`

SetDueDate sets DueDate field to given value.

### HasDueDate

`func (o *JobSchedulingApiBackwardsScheduleItem) HasDueDate() bool`

HasDueDate returns a boolean if a field has been set.

### GetScheduledStartDate

`func (o *JobSchedulingApiBackwardsScheduleItem) GetScheduledStartDate() time.Time`

GetScheduledStartDate returns the ScheduledStartDate field if non-nil, zero value otherwise.

### GetScheduledStartDateOk

`func (o *JobSchedulingApiBackwardsScheduleItem) GetScheduledStartDateOk() (*time.Time, bool)`

GetScheduledStartDateOk returns a tuple with the ScheduledStartDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScheduledStartDate

`func (o *JobSchedulingApiBackwardsScheduleItem) SetScheduledStartDate(v time.Time)`

SetScheduledStartDate sets ScheduledStartDate field to given value.

### HasScheduledStartDate

`func (o *JobSchedulingApiBackwardsScheduleItem) HasScheduledStartDate() bool`

HasScheduledStartDate returns a boolean if a field has been set.

### GetCompletedDate

`func (o *JobSchedulingApiBackwardsScheduleItem) GetCompletedDate() time.Time`

GetCompletedDate returns the CompletedDate field if non-nil, zero value otherwise.

### GetCompletedDateOk

`func (o *JobSchedulingApiBackwardsScheduleItem) GetCompletedDateOk() (*time.Time, bool)`

GetCompletedDateOk returns a tuple with the CompletedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedDate

`func (o *JobSchedulingApiBackwardsScheduleItem) SetCompletedDate(v time.Time)`

SetCompletedDate sets CompletedDate field to given value.

### HasCompletedDate

`func (o *JobSchedulingApiBackwardsScheduleItem) HasCompletedDate() bool`

HasCompletedDate returns a boolean if a field has been set.

### GetJobOperationStatus

`func (o *JobSchedulingApiBackwardsScheduleItem) GetJobOperationStatus() string`

GetJobOperationStatus returns the JobOperationStatus field if non-nil, zero value otherwise.

### GetJobOperationStatusOk

`func (o *JobSchedulingApiBackwardsScheduleItem) GetJobOperationStatusOk() (*string, bool)`

GetJobOperationStatusOk returns a tuple with the JobOperationStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobOperationStatus

`func (o *JobSchedulingApiBackwardsScheduleItem) SetJobOperationStatus(v string)`

SetJobOperationStatus sets JobOperationStatus field to given value.

### HasJobOperationStatus

`func (o *JobSchedulingApiBackwardsScheduleItem) HasJobOperationStatus() bool`

HasJobOperationStatus returns a boolean if a field has been set.

### GetSetupTime

`func (o *JobSchedulingApiBackwardsScheduleItem) GetSetupTime() float64`

GetSetupTime returns the SetupTime field if non-nil, zero value otherwise.

### GetSetupTimeOk

`func (o *JobSchedulingApiBackwardsScheduleItem) GetSetupTimeOk() (*float64, bool)`

GetSetupTimeOk returns a tuple with the SetupTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSetupTime

`func (o *JobSchedulingApiBackwardsScheduleItem) SetSetupTime(v float64)`

SetSetupTime sets SetupTime field to given value.

### HasSetupTime

`func (o *JobSchedulingApiBackwardsScheduleItem) HasSetupTime() bool`

HasSetupTime returns a boolean if a field has been set.

### GetRate

`func (o *JobSchedulingApiBackwardsScheduleItem) GetRate() float64`

GetRate returns the Rate field if non-nil, zero value otherwise.

### GetRateOk

`func (o *JobSchedulingApiBackwardsScheduleItem) GetRateOk() (*float64, bool)`

GetRateOk returns a tuple with the Rate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRate

`func (o *JobSchedulingApiBackwardsScheduleItem) SetRate(v float64)`

SetRate sets Rate field to given value.

### HasRate

`func (o *JobSchedulingApiBackwardsScheduleItem) HasRate() bool`

HasRate returns a boolean if a field has been set.

### GetUnitOfMeasure

`func (o *JobSchedulingApiBackwardsScheduleItem) GetUnitOfMeasure() string`

GetUnitOfMeasure returns the UnitOfMeasure field if non-nil, zero value otherwise.

### GetUnitOfMeasureOk

`func (o *JobSchedulingApiBackwardsScheduleItem) GetUnitOfMeasureOk() (*string, bool)`

GetUnitOfMeasureOk returns a tuple with the UnitOfMeasure field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitOfMeasure

`func (o *JobSchedulingApiBackwardsScheduleItem) SetUnitOfMeasure(v string)`

SetUnitOfMeasure sets UnitOfMeasure field to given value.

### HasUnitOfMeasure

`func (o *JobSchedulingApiBackwardsScheduleItem) HasUnitOfMeasure() bool`

HasUnitOfMeasure returns a boolean if a field has been set.

### GetRunTime

`func (o *JobSchedulingApiBackwardsScheduleItem) GetRunTime() float64`

GetRunTime returns the RunTime field if non-nil, zero value otherwise.

### GetRunTimeOk

`func (o *JobSchedulingApiBackwardsScheduleItem) GetRunTimeOk() (*float64, bool)`

GetRunTimeOk returns a tuple with the RunTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunTime

`func (o *JobSchedulingApiBackwardsScheduleItem) SetRunTime(v float64)`

SetRunTime sets RunTime field to given value.

### HasRunTime

`func (o *JobSchedulingApiBackwardsScheduleItem) HasRunTime() bool`

HasRunTime returns a boolean if a field has been set.

### GetBatchCriteria

`func (o *JobSchedulingApiBackwardsScheduleItem) GetBatchCriteria() string`

GetBatchCriteria returns the BatchCriteria field if non-nil, zero value otherwise.

### GetBatchCriteriaOk

`func (o *JobSchedulingApiBackwardsScheduleItem) GetBatchCriteriaOk() (*string, bool)`

GetBatchCriteriaOk returns a tuple with the BatchCriteria field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBatchCriteria

`func (o *JobSchedulingApiBackwardsScheduleItem) SetBatchCriteria(v string)`

SetBatchCriteria sets BatchCriteria field to given value.

### HasBatchCriteria

`func (o *JobSchedulingApiBackwardsScheduleItem) HasBatchCriteria() bool`

HasBatchCriteria returns a boolean if a field has been set.

### GetPartOperationType

`func (o *JobSchedulingApiBackwardsScheduleItem) GetPartOperationType() string`

GetPartOperationType returns the PartOperationType field if non-nil, zero value otherwise.

### GetPartOperationTypeOk

`func (o *JobSchedulingApiBackwardsScheduleItem) GetPartOperationTypeOk() (*string, bool)`

GetPartOperationTypeOk returns a tuple with the PartOperationType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartOperationType

`func (o *JobSchedulingApiBackwardsScheduleItem) SetPartOperationType(v string)`

SetPartOperationType sets PartOperationType field to given value.

### HasPartOperationType

`func (o *JobSchedulingApiBackwardsScheduleItem) HasPartOperationType() bool`

HasPartOperationType returns a boolean if a field has been set.

### GetBatchOperation

`func (o *JobSchedulingApiBackwardsScheduleItem) GetBatchOperation() bool`

GetBatchOperation returns the BatchOperation field if non-nil, zero value otherwise.

### GetBatchOperationOk

`func (o *JobSchedulingApiBackwardsScheduleItem) GetBatchOperationOk() (*bool, bool)`

GetBatchOperationOk returns a tuple with the BatchOperation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBatchOperation

`func (o *JobSchedulingApiBackwardsScheduleItem) SetBatchOperation(v bool)`

SetBatchOperation sets BatchOperation field to given value.

### HasBatchOperation

`func (o *JobSchedulingApiBackwardsScheduleItem) HasBatchOperation() bool`

HasBatchOperation returns a boolean if a field has been set.

### GetPreProcessOperation

`func (o *JobSchedulingApiBackwardsScheduleItem) GetPreProcessOperation() bool`

GetPreProcessOperation returns the PreProcessOperation field if non-nil, zero value otherwise.

### GetPreProcessOperationOk

`func (o *JobSchedulingApiBackwardsScheduleItem) GetPreProcessOperationOk() (*bool, bool)`

GetPreProcessOperationOk returns a tuple with the PreProcessOperation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreProcessOperation

`func (o *JobSchedulingApiBackwardsScheduleItem) SetPreProcessOperation(v bool)`

SetPreProcessOperation sets PreProcessOperation field to given value.

### HasPreProcessOperation

`func (o *JobSchedulingApiBackwardsScheduleItem) HasPreProcessOperation() bool`

HasPreProcessOperation returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


