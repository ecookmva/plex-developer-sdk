# ProductionOperationsManagementApiGetWorkcenterSetupResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | A unique identifier of the workcenter. | [optional] 
**Code** | Pointer to **string** | A short name associated with the workcenter ID, and a unique code to reference the workcenter. This code displays throughout the system, primarily on the Control Panel. 50 characters max. | [optional] 
**Name** | Pointer to **string** | A long name associated with the workcenter ID. 100 characters max. | [optional] 
**Type** | Pointer to **string** | The workcenter type. | [optional] 
**StatusId** | Pointer to **string** | A unique identifier of the workcenter status. | [optional] 
**StatusDescription** | Pointer to **string** | A workcenter status description. | [optional] 
**JobId** | Pointer to **string** | A unique identifier of the production job. | [optional] 
**JobNumber** | Pointer to **string** | The job number, including prefix and suffix, associated with the job ID. | [optional] 
**JobOperationId** | Pointer to **string** | A unique identifier for the job operation. | [optional] 
**OperationNumber** | Pointer to **float64** | The operation number of the part operation. | [optional] 
**OperationCode** | Pointer to **string** | The operation code of the part operation. 30 characters max. | [optional] 
**JobOperationQuantity** | Pointer to **float64** | The quantity to be produced in this job operation. | [optional] 
**LotId** | Pointer to **string** | The unique identifier for the lot in this job operation. | [optional] 
**ProductionLineId** | Pointer to **string** | The unique identifier for the production line associated with the workcenter. | [optional] 
**Batches** | Pointer to [**[]BatchesItem**](BatchesItem.md) | A list of all batches in this job operation. | [optional] 
**Operators** | Pointer to [**[]OperatorsItem**](OperatorsItem.md) | A list of all operators logged in at this workcenter. | [optional] 

## Methods

### NewProductionOperationsManagementApiGetWorkcenterSetupResponse

`func NewProductionOperationsManagementApiGetWorkcenterSetupResponse() *ProductionOperationsManagementApiGetWorkcenterSetupResponse`

NewProductionOperationsManagementApiGetWorkcenterSetupResponse instantiates a new ProductionOperationsManagementApiGetWorkcenterSetupResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductionOperationsManagementApiGetWorkcenterSetupResponseWithDefaults

`func NewProductionOperationsManagementApiGetWorkcenterSetupResponseWithDefaults() *ProductionOperationsManagementApiGetWorkcenterSetupResponse`

NewProductionOperationsManagementApiGetWorkcenterSetupResponseWithDefaults instantiates a new ProductionOperationsManagementApiGetWorkcenterSetupResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCode

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetName

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) HasName() bool`

HasName returns a boolean if a field has been set.

### GetType

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) HasType() bool`

HasType returns a boolean if a field has been set.

### GetStatusId

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) GetStatusId() string`

GetStatusId returns the StatusId field if non-nil, zero value otherwise.

### GetStatusIdOk

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) GetStatusIdOk() (*string, bool)`

GetStatusIdOk returns a tuple with the StatusId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatusId

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) SetStatusId(v string)`

SetStatusId sets StatusId field to given value.

### HasStatusId

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) HasStatusId() bool`

HasStatusId returns a boolean if a field has been set.

### GetStatusDescription

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) GetStatusDescription() string`

GetStatusDescription returns the StatusDescription field if non-nil, zero value otherwise.

### GetStatusDescriptionOk

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) GetStatusDescriptionOk() (*string, bool)`

GetStatusDescriptionOk returns a tuple with the StatusDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatusDescription

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) SetStatusDescription(v string)`

SetStatusDescription sets StatusDescription field to given value.

### HasStatusDescription

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) HasStatusDescription() bool`

HasStatusDescription returns a boolean if a field has been set.

### GetJobId

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) GetJobId() string`

GetJobId returns the JobId field if non-nil, zero value otherwise.

### GetJobIdOk

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) GetJobIdOk() (*string, bool)`

GetJobIdOk returns a tuple with the JobId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobId

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) SetJobId(v string)`

SetJobId sets JobId field to given value.

### HasJobId

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) HasJobId() bool`

HasJobId returns a boolean if a field has been set.

### GetJobNumber

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) GetJobNumber() string`

GetJobNumber returns the JobNumber field if non-nil, zero value otherwise.

### GetJobNumberOk

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) GetJobNumberOk() (*string, bool)`

GetJobNumberOk returns a tuple with the JobNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobNumber

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) SetJobNumber(v string)`

SetJobNumber sets JobNumber field to given value.

### HasJobNumber

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) HasJobNumber() bool`

HasJobNumber returns a boolean if a field has been set.

### GetJobOperationId

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) GetJobOperationId() string`

GetJobOperationId returns the JobOperationId field if non-nil, zero value otherwise.

### GetJobOperationIdOk

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) GetJobOperationIdOk() (*string, bool)`

GetJobOperationIdOk returns a tuple with the JobOperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobOperationId

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) SetJobOperationId(v string)`

SetJobOperationId sets JobOperationId field to given value.

### HasJobOperationId

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) HasJobOperationId() bool`

HasJobOperationId returns a boolean if a field has been set.

### GetOperationNumber

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) GetOperationNumber() float64`

GetOperationNumber returns the OperationNumber field if non-nil, zero value otherwise.

### GetOperationNumberOk

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) GetOperationNumberOk() (*float64, bool)`

GetOperationNumberOk returns a tuple with the OperationNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationNumber

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) SetOperationNumber(v float64)`

SetOperationNumber sets OperationNumber field to given value.

### HasOperationNumber

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) HasOperationNumber() bool`

HasOperationNumber returns a boolean if a field has been set.

### GetOperationCode

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) GetOperationCode() string`

GetOperationCode returns the OperationCode field if non-nil, zero value otherwise.

### GetOperationCodeOk

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) GetOperationCodeOk() (*string, bool)`

GetOperationCodeOk returns a tuple with the OperationCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationCode

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) SetOperationCode(v string)`

SetOperationCode sets OperationCode field to given value.

### HasOperationCode

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) HasOperationCode() bool`

HasOperationCode returns a boolean if a field has been set.

### GetJobOperationQuantity

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) GetJobOperationQuantity() float64`

GetJobOperationQuantity returns the JobOperationQuantity field if non-nil, zero value otherwise.

### GetJobOperationQuantityOk

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) GetJobOperationQuantityOk() (*float64, bool)`

GetJobOperationQuantityOk returns a tuple with the JobOperationQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobOperationQuantity

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) SetJobOperationQuantity(v float64)`

SetJobOperationQuantity sets JobOperationQuantity field to given value.

### HasJobOperationQuantity

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) HasJobOperationQuantity() bool`

HasJobOperationQuantity returns a boolean if a field has been set.

### GetLotId

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) GetLotId() string`

GetLotId returns the LotId field if non-nil, zero value otherwise.

### GetLotIdOk

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) GetLotIdOk() (*string, bool)`

GetLotIdOk returns a tuple with the LotId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLotId

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) SetLotId(v string)`

SetLotId sets LotId field to given value.

### HasLotId

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) HasLotId() bool`

HasLotId returns a boolean if a field has been set.

### GetProductionLineId

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) GetProductionLineId() string`

GetProductionLineId returns the ProductionLineId field if non-nil, zero value otherwise.

### GetProductionLineIdOk

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) GetProductionLineIdOk() (*string, bool)`

GetProductionLineIdOk returns a tuple with the ProductionLineId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductionLineId

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) SetProductionLineId(v string)`

SetProductionLineId sets ProductionLineId field to given value.

### HasProductionLineId

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) HasProductionLineId() bool`

HasProductionLineId returns a boolean if a field has been set.

### GetBatches

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) GetBatches() []BatchesItem`

GetBatches returns the Batches field if non-nil, zero value otherwise.

### GetBatchesOk

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) GetBatchesOk() (*[]BatchesItem, bool)`

GetBatchesOk returns a tuple with the Batches field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBatches

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) SetBatches(v []BatchesItem)`

SetBatches sets Batches field to given value.

### HasBatches

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) HasBatches() bool`

HasBatches returns a boolean if a field has been set.

### GetOperators

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) GetOperators() []OperatorsItem`

GetOperators returns the Operators field if non-nil, zero value otherwise.

### GetOperatorsOk

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) GetOperatorsOk() (*[]OperatorsItem, bool)`

GetOperatorsOk returns a tuple with the Operators field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperators

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) SetOperators(v []OperatorsItem)`

SetOperators sets Operators field to given value.

### HasOperators

`func (o *ProductionOperationsManagementApiGetWorkcenterSetupResponse) HasOperators() bool`

HasOperators returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


