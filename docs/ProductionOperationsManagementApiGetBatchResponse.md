# ProductionOperationsManagementApiGetBatchResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | A unique identifier of the batch. | [optional] 
**Number** | Pointer to **int32** | Identifier of the batch for the current job operation. | [optional] 
**BatchStatus** | Pointer to **string** | The status of the batch. | [optional] 
**Size** | Pointer to **float64** | The quantity to be produced in the batch. | [optional] 
**WorkcenterId** | Pointer to **string** | A unique identifier of the workcenter. | [optional] 
**WorkcenterCode** | Pointer to **string** | A short name associated with the workcenter ID, and a unique code to reference the workcenter. This code displays throughout the system, primarily on the Control Panel. 50 characters max. | [optional] 
**PartId** | Pointer to **string** | A unique identifier of the part. | [optional] 
**PartNumber** | Pointer to **string** | The part number associated with the part ID. | [optional] 
**PartRevision** | Pointer to **string** | The part revision associated with the part ID. | [optional] 
**PartNumberRevision** | Pointer to **string** | A combination of the part number and revision associated with the part ID, separated with the value from the Part Rev Separator setting. | [optional] 
**JobId** | Pointer to **string** | A unique identifier of the production job. | [optional] 
**JobNumber** | Pointer to **string** | The job number, including prefix and suffix, associated with the job ID. | [optional] 
**JobStatus** | Pointer to **string** | The job status. | [optional] 
**JobOperationId** | Pointer to **string** | A unique identifier for the job operation. | [optional] 
**JobOperationStatus** | Pointer to **string** | The job operation status. | [optional] 
**OperationNumber** | Pointer to **float64** | The operation number of the part operation. | [optional] 
**OperationCode** | Pointer to **string** | The operation code of the part operation. 30 characters max. | [optional] 
**JobOperationQuantity** | Pointer to **float64** | The quantity to be produced across all batches in this job operation. | [optional] 
**BatchComponents** | Pointer to [**[]BatchComponentsItem**](BatchComponentsItem.md) | A list of all batch component parts from the job BOM. | [optional] 
**DueDate** | Pointer to **time.Time** | The due date of the batch. | [optional] 
**StartDate** | Pointer to **time.Time** | The scheduled start date of the batch. | [optional] 

## Methods

### NewProductionOperationsManagementApiGetBatchResponse

`func NewProductionOperationsManagementApiGetBatchResponse() *ProductionOperationsManagementApiGetBatchResponse`

NewProductionOperationsManagementApiGetBatchResponse instantiates a new ProductionOperationsManagementApiGetBatchResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductionOperationsManagementApiGetBatchResponseWithDefaults

`func NewProductionOperationsManagementApiGetBatchResponseWithDefaults() *ProductionOperationsManagementApiGetBatchResponse`

NewProductionOperationsManagementApiGetBatchResponseWithDefaults instantiates a new ProductionOperationsManagementApiGetBatchResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ProductionOperationsManagementApiGetBatchResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ProductionOperationsManagementApiGetBatchResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ProductionOperationsManagementApiGetBatchResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *ProductionOperationsManagementApiGetBatchResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetNumber

`func (o *ProductionOperationsManagementApiGetBatchResponse) GetNumber() int32`

GetNumber returns the Number field if non-nil, zero value otherwise.

### GetNumberOk

`func (o *ProductionOperationsManagementApiGetBatchResponse) GetNumberOk() (*int32, bool)`

GetNumberOk returns a tuple with the Number field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumber

`func (o *ProductionOperationsManagementApiGetBatchResponse) SetNumber(v int32)`

SetNumber sets Number field to given value.

### HasNumber

`func (o *ProductionOperationsManagementApiGetBatchResponse) HasNumber() bool`

HasNumber returns a boolean if a field has been set.

### GetBatchStatus

`func (o *ProductionOperationsManagementApiGetBatchResponse) GetBatchStatus() string`

GetBatchStatus returns the BatchStatus field if non-nil, zero value otherwise.

### GetBatchStatusOk

`func (o *ProductionOperationsManagementApiGetBatchResponse) GetBatchStatusOk() (*string, bool)`

GetBatchStatusOk returns a tuple with the BatchStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBatchStatus

`func (o *ProductionOperationsManagementApiGetBatchResponse) SetBatchStatus(v string)`

SetBatchStatus sets BatchStatus field to given value.

### HasBatchStatus

`func (o *ProductionOperationsManagementApiGetBatchResponse) HasBatchStatus() bool`

HasBatchStatus returns a boolean if a field has been set.

### GetSize

`func (o *ProductionOperationsManagementApiGetBatchResponse) GetSize() float64`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *ProductionOperationsManagementApiGetBatchResponse) GetSizeOk() (*float64, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *ProductionOperationsManagementApiGetBatchResponse) SetSize(v float64)`

SetSize sets Size field to given value.

### HasSize

`func (o *ProductionOperationsManagementApiGetBatchResponse) HasSize() bool`

HasSize returns a boolean if a field has been set.

### GetWorkcenterId

`func (o *ProductionOperationsManagementApiGetBatchResponse) GetWorkcenterId() string`

GetWorkcenterId returns the WorkcenterId field if non-nil, zero value otherwise.

### GetWorkcenterIdOk

`func (o *ProductionOperationsManagementApiGetBatchResponse) GetWorkcenterIdOk() (*string, bool)`

GetWorkcenterIdOk returns a tuple with the WorkcenterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkcenterId

`func (o *ProductionOperationsManagementApiGetBatchResponse) SetWorkcenterId(v string)`

SetWorkcenterId sets WorkcenterId field to given value.

### HasWorkcenterId

`func (o *ProductionOperationsManagementApiGetBatchResponse) HasWorkcenterId() bool`

HasWorkcenterId returns a boolean if a field has been set.

### GetWorkcenterCode

`func (o *ProductionOperationsManagementApiGetBatchResponse) GetWorkcenterCode() string`

GetWorkcenterCode returns the WorkcenterCode field if non-nil, zero value otherwise.

### GetWorkcenterCodeOk

`func (o *ProductionOperationsManagementApiGetBatchResponse) GetWorkcenterCodeOk() (*string, bool)`

GetWorkcenterCodeOk returns a tuple with the WorkcenterCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkcenterCode

`func (o *ProductionOperationsManagementApiGetBatchResponse) SetWorkcenterCode(v string)`

SetWorkcenterCode sets WorkcenterCode field to given value.

### HasWorkcenterCode

`func (o *ProductionOperationsManagementApiGetBatchResponse) HasWorkcenterCode() bool`

HasWorkcenterCode returns a boolean if a field has been set.

### GetPartId

`func (o *ProductionOperationsManagementApiGetBatchResponse) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *ProductionOperationsManagementApiGetBatchResponse) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *ProductionOperationsManagementApiGetBatchResponse) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *ProductionOperationsManagementApiGetBatchResponse) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetPartNumber

`func (o *ProductionOperationsManagementApiGetBatchResponse) GetPartNumber() string`

GetPartNumber returns the PartNumber field if non-nil, zero value otherwise.

### GetPartNumberOk

`func (o *ProductionOperationsManagementApiGetBatchResponse) GetPartNumberOk() (*string, bool)`

GetPartNumberOk returns a tuple with the PartNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumber

`func (o *ProductionOperationsManagementApiGetBatchResponse) SetPartNumber(v string)`

SetPartNumber sets PartNumber field to given value.

### HasPartNumber

`func (o *ProductionOperationsManagementApiGetBatchResponse) HasPartNumber() bool`

HasPartNumber returns a boolean if a field has been set.

### GetPartRevision

`func (o *ProductionOperationsManagementApiGetBatchResponse) GetPartRevision() string`

GetPartRevision returns the PartRevision field if non-nil, zero value otherwise.

### GetPartRevisionOk

`func (o *ProductionOperationsManagementApiGetBatchResponse) GetPartRevisionOk() (*string, bool)`

GetPartRevisionOk returns a tuple with the PartRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartRevision

`func (o *ProductionOperationsManagementApiGetBatchResponse) SetPartRevision(v string)`

SetPartRevision sets PartRevision field to given value.

### HasPartRevision

`func (o *ProductionOperationsManagementApiGetBatchResponse) HasPartRevision() bool`

HasPartRevision returns a boolean if a field has been set.

### GetPartNumberRevision

`func (o *ProductionOperationsManagementApiGetBatchResponse) GetPartNumberRevision() string`

GetPartNumberRevision returns the PartNumberRevision field if non-nil, zero value otherwise.

### GetPartNumberRevisionOk

`func (o *ProductionOperationsManagementApiGetBatchResponse) GetPartNumberRevisionOk() (*string, bool)`

GetPartNumberRevisionOk returns a tuple with the PartNumberRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumberRevision

`func (o *ProductionOperationsManagementApiGetBatchResponse) SetPartNumberRevision(v string)`

SetPartNumberRevision sets PartNumberRevision field to given value.

### HasPartNumberRevision

`func (o *ProductionOperationsManagementApiGetBatchResponse) HasPartNumberRevision() bool`

HasPartNumberRevision returns a boolean if a field has been set.

### GetJobId

`func (o *ProductionOperationsManagementApiGetBatchResponse) GetJobId() string`

GetJobId returns the JobId field if non-nil, zero value otherwise.

### GetJobIdOk

`func (o *ProductionOperationsManagementApiGetBatchResponse) GetJobIdOk() (*string, bool)`

GetJobIdOk returns a tuple with the JobId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobId

`func (o *ProductionOperationsManagementApiGetBatchResponse) SetJobId(v string)`

SetJobId sets JobId field to given value.

### HasJobId

`func (o *ProductionOperationsManagementApiGetBatchResponse) HasJobId() bool`

HasJobId returns a boolean if a field has been set.

### GetJobNumber

`func (o *ProductionOperationsManagementApiGetBatchResponse) GetJobNumber() string`

GetJobNumber returns the JobNumber field if non-nil, zero value otherwise.

### GetJobNumberOk

`func (o *ProductionOperationsManagementApiGetBatchResponse) GetJobNumberOk() (*string, bool)`

GetJobNumberOk returns a tuple with the JobNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobNumber

`func (o *ProductionOperationsManagementApiGetBatchResponse) SetJobNumber(v string)`

SetJobNumber sets JobNumber field to given value.

### HasJobNumber

`func (o *ProductionOperationsManagementApiGetBatchResponse) HasJobNumber() bool`

HasJobNumber returns a boolean if a field has been set.

### GetJobStatus

`func (o *ProductionOperationsManagementApiGetBatchResponse) GetJobStatus() string`

GetJobStatus returns the JobStatus field if non-nil, zero value otherwise.

### GetJobStatusOk

`func (o *ProductionOperationsManagementApiGetBatchResponse) GetJobStatusOk() (*string, bool)`

GetJobStatusOk returns a tuple with the JobStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobStatus

`func (o *ProductionOperationsManagementApiGetBatchResponse) SetJobStatus(v string)`

SetJobStatus sets JobStatus field to given value.

### HasJobStatus

`func (o *ProductionOperationsManagementApiGetBatchResponse) HasJobStatus() bool`

HasJobStatus returns a boolean if a field has been set.

### GetJobOperationId

`func (o *ProductionOperationsManagementApiGetBatchResponse) GetJobOperationId() string`

GetJobOperationId returns the JobOperationId field if non-nil, zero value otherwise.

### GetJobOperationIdOk

`func (o *ProductionOperationsManagementApiGetBatchResponse) GetJobOperationIdOk() (*string, bool)`

GetJobOperationIdOk returns a tuple with the JobOperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobOperationId

`func (o *ProductionOperationsManagementApiGetBatchResponse) SetJobOperationId(v string)`

SetJobOperationId sets JobOperationId field to given value.

### HasJobOperationId

`func (o *ProductionOperationsManagementApiGetBatchResponse) HasJobOperationId() bool`

HasJobOperationId returns a boolean if a field has been set.

### GetJobOperationStatus

`func (o *ProductionOperationsManagementApiGetBatchResponse) GetJobOperationStatus() string`

GetJobOperationStatus returns the JobOperationStatus field if non-nil, zero value otherwise.

### GetJobOperationStatusOk

`func (o *ProductionOperationsManagementApiGetBatchResponse) GetJobOperationStatusOk() (*string, bool)`

GetJobOperationStatusOk returns a tuple with the JobOperationStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobOperationStatus

`func (o *ProductionOperationsManagementApiGetBatchResponse) SetJobOperationStatus(v string)`

SetJobOperationStatus sets JobOperationStatus field to given value.

### HasJobOperationStatus

`func (o *ProductionOperationsManagementApiGetBatchResponse) HasJobOperationStatus() bool`

HasJobOperationStatus returns a boolean if a field has been set.

### GetOperationNumber

`func (o *ProductionOperationsManagementApiGetBatchResponse) GetOperationNumber() float64`

GetOperationNumber returns the OperationNumber field if non-nil, zero value otherwise.

### GetOperationNumberOk

`func (o *ProductionOperationsManagementApiGetBatchResponse) GetOperationNumberOk() (*float64, bool)`

GetOperationNumberOk returns a tuple with the OperationNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationNumber

`func (o *ProductionOperationsManagementApiGetBatchResponse) SetOperationNumber(v float64)`

SetOperationNumber sets OperationNumber field to given value.

### HasOperationNumber

`func (o *ProductionOperationsManagementApiGetBatchResponse) HasOperationNumber() bool`

HasOperationNumber returns a boolean if a field has been set.

### GetOperationCode

`func (o *ProductionOperationsManagementApiGetBatchResponse) GetOperationCode() string`

GetOperationCode returns the OperationCode field if non-nil, zero value otherwise.

### GetOperationCodeOk

`func (o *ProductionOperationsManagementApiGetBatchResponse) GetOperationCodeOk() (*string, bool)`

GetOperationCodeOk returns a tuple with the OperationCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationCode

`func (o *ProductionOperationsManagementApiGetBatchResponse) SetOperationCode(v string)`

SetOperationCode sets OperationCode field to given value.

### HasOperationCode

`func (o *ProductionOperationsManagementApiGetBatchResponse) HasOperationCode() bool`

HasOperationCode returns a boolean if a field has been set.

### GetJobOperationQuantity

`func (o *ProductionOperationsManagementApiGetBatchResponse) GetJobOperationQuantity() float64`

GetJobOperationQuantity returns the JobOperationQuantity field if non-nil, zero value otherwise.

### GetJobOperationQuantityOk

`func (o *ProductionOperationsManagementApiGetBatchResponse) GetJobOperationQuantityOk() (*float64, bool)`

GetJobOperationQuantityOk returns a tuple with the JobOperationQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobOperationQuantity

`func (o *ProductionOperationsManagementApiGetBatchResponse) SetJobOperationQuantity(v float64)`

SetJobOperationQuantity sets JobOperationQuantity field to given value.

### HasJobOperationQuantity

`func (o *ProductionOperationsManagementApiGetBatchResponse) HasJobOperationQuantity() bool`

HasJobOperationQuantity returns a boolean if a field has been set.

### GetBatchComponents

`func (o *ProductionOperationsManagementApiGetBatchResponse) GetBatchComponents() []BatchComponentsItem`

GetBatchComponents returns the BatchComponents field if non-nil, zero value otherwise.

### GetBatchComponentsOk

`func (o *ProductionOperationsManagementApiGetBatchResponse) GetBatchComponentsOk() (*[]BatchComponentsItem, bool)`

GetBatchComponentsOk returns a tuple with the BatchComponents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBatchComponents

`func (o *ProductionOperationsManagementApiGetBatchResponse) SetBatchComponents(v []BatchComponentsItem)`

SetBatchComponents sets BatchComponents field to given value.

### HasBatchComponents

`func (o *ProductionOperationsManagementApiGetBatchResponse) HasBatchComponents() bool`

HasBatchComponents returns a boolean if a field has been set.

### GetDueDate

`func (o *ProductionOperationsManagementApiGetBatchResponse) GetDueDate() time.Time`

GetDueDate returns the DueDate field if non-nil, zero value otherwise.

### GetDueDateOk

`func (o *ProductionOperationsManagementApiGetBatchResponse) GetDueDateOk() (*time.Time, bool)`

GetDueDateOk returns a tuple with the DueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueDate

`func (o *ProductionOperationsManagementApiGetBatchResponse) SetDueDate(v time.Time)`

SetDueDate sets DueDate field to given value.

### HasDueDate

`func (o *ProductionOperationsManagementApiGetBatchResponse) HasDueDate() bool`

HasDueDate returns a boolean if a field has been set.

### GetStartDate

`func (o *ProductionOperationsManagementApiGetBatchResponse) GetStartDate() time.Time`

GetStartDate returns the StartDate field if non-nil, zero value otherwise.

### GetStartDateOk

`func (o *ProductionOperationsManagementApiGetBatchResponse) GetStartDateOk() (*time.Time, bool)`

GetStartDateOk returns a tuple with the StartDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartDate

`func (o *ProductionOperationsManagementApiGetBatchResponse) SetStartDate(v time.Time)`

SetStartDate sets StartDate field to given value.

### HasStartDate

`func (o *ProductionOperationsManagementApiGetBatchResponse) HasStartDate() bool`

HasStartDate returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


