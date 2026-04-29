# ProductionOperationsManagementApiSearchWorkcenterSetupsItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | A unique identifier of the workcenter. | [optional] 
**Code** | Pointer to **string** | A short name associated with the workcenter ID, and a unique code to reference the workcenter. This code displays throughout the system, primarily on the Control Panel. 50 characters max. | [optional] 
**Name** | Pointer to **string** | A long name associated with the workcenter ID. 100 characters max. | [optional] 
**Type** | Pointer to **string** | The workcenter type. | [optional] 
**Group** | Pointer to **string** | The workcenter group. | [optional] 
**StatusId** | Pointer to **string** | A unique identifier of the workcenter status. | [optional] 
**StatusDescription** | Pointer to **string** | A workcenter status description. | [optional] 
**JobId** | Pointer to **string** | A unique identifier of the production job. | [optional] 
**JobNumber** | Pointer to **string** | The job number, including prefix and suffix, associated with the job ID. | [optional] 
**JobOperationId** | Pointer to **string** | A unique identifier for the job operation. | [optional] 
**OperationNumber** | Pointer to **float64** | The operation number of the part operation. | [optional] 
**OperationCode** | Pointer to **string** | The operation code of the part operation. 30 characters max. | [optional] 
**JobOperationQuantity** | Pointer to **float64** | The quantity to be produced in this job operation. | [optional] 
**PartId** | Pointer to **string** | A unique identifier of the part. | [optional] 
**PartNumber** | Pointer to **string** | The part number associated with the part ID. | [optional] 
**PartRevision** | Pointer to **string** | 8 characters max. The part revision. A revision level represents a change or modification to a part or part drawing that is usually initiated through an engineering change request (ECR). | [optional] 
**PartNumberRevision** | Pointer to **string** | Format {partNumber}{part rev separator}{revision}. The part number revision formatted with separator. If a part number has a revision, Plex will return the part number and the revision separated by the Part Rev Separator setting. A Part Rev Separator can be up to 5 characters long. | [optional] 
**PartName** | Pointer to **string** | The name of the part. | [optional] 
**JobOperationStatus** | Pointer to **string** | The job operation status. | [optional] 
**JobOperationQuantityCompleted** | Pointer to **float64** | The quantity of parts produced at job operation. | [optional] 
**JobOperationQuantityBalance** | Pointer to **float64** | The quantity of parts remaining to be produced at job operation. | [optional] 
**ContainerType** | Pointer to **string** | The container type. | [optional] 
**StandardQuantity** | Pointer to **float64** | Standard pack size for the Part Operation. | [optional] 

## Methods

### NewProductionOperationsManagementApiSearchWorkcenterSetupsItem

`func NewProductionOperationsManagementApiSearchWorkcenterSetupsItem() *ProductionOperationsManagementApiSearchWorkcenterSetupsItem`

NewProductionOperationsManagementApiSearchWorkcenterSetupsItem instantiates a new ProductionOperationsManagementApiSearchWorkcenterSetupsItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductionOperationsManagementApiSearchWorkcenterSetupsItemWithDefaults

`func NewProductionOperationsManagementApiSearchWorkcenterSetupsItemWithDefaults() *ProductionOperationsManagementApiSearchWorkcenterSetupsItem`

NewProductionOperationsManagementApiSearchWorkcenterSetupsItemWithDefaults instantiates a new ProductionOperationsManagementApiSearchWorkcenterSetupsItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCode

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetName

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) HasName() bool`

HasName returns a boolean if a field has been set.

### GetType

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) HasType() bool`

HasType returns a boolean if a field has been set.

### GetGroup

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) GetGroup() string`

GetGroup returns the Group field if non-nil, zero value otherwise.

### GetGroupOk

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) GetGroupOk() (*string, bool)`

GetGroupOk returns a tuple with the Group field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroup

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) SetGroup(v string)`

SetGroup sets Group field to given value.

### HasGroup

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) HasGroup() bool`

HasGroup returns a boolean if a field has been set.

### GetStatusId

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) GetStatusId() string`

GetStatusId returns the StatusId field if non-nil, zero value otherwise.

### GetStatusIdOk

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) GetStatusIdOk() (*string, bool)`

GetStatusIdOk returns a tuple with the StatusId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatusId

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) SetStatusId(v string)`

SetStatusId sets StatusId field to given value.

### HasStatusId

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) HasStatusId() bool`

HasStatusId returns a boolean if a field has been set.

### GetStatusDescription

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) GetStatusDescription() string`

GetStatusDescription returns the StatusDescription field if non-nil, zero value otherwise.

### GetStatusDescriptionOk

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) GetStatusDescriptionOk() (*string, bool)`

GetStatusDescriptionOk returns a tuple with the StatusDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatusDescription

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) SetStatusDescription(v string)`

SetStatusDescription sets StatusDescription field to given value.

### HasStatusDescription

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) HasStatusDescription() bool`

HasStatusDescription returns a boolean if a field has been set.

### GetJobId

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) GetJobId() string`

GetJobId returns the JobId field if non-nil, zero value otherwise.

### GetJobIdOk

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) GetJobIdOk() (*string, bool)`

GetJobIdOk returns a tuple with the JobId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobId

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) SetJobId(v string)`

SetJobId sets JobId field to given value.

### HasJobId

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) HasJobId() bool`

HasJobId returns a boolean if a field has been set.

### GetJobNumber

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) GetJobNumber() string`

GetJobNumber returns the JobNumber field if non-nil, zero value otherwise.

### GetJobNumberOk

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) GetJobNumberOk() (*string, bool)`

GetJobNumberOk returns a tuple with the JobNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobNumber

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) SetJobNumber(v string)`

SetJobNumber sets JobNumber field to given value.

### HasJobNumber

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) HasJobNumber() bool`

HasJobNumber returns a boolean if a field has been set.

### GetJobOperationId

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) GetJobOperationId() string`

GetJobOperationId returns the JobOperationId field if non-nil, zero value otherwise.

### GetJobOperationIdOk

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) GetJobOperationIdOk() (*string, bool)`

GetJobOperationIdOk returns a tuple with the JobOperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobOperationId

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) SetJobOperationId(v string)`

SetJobOperationId sets JobOperationId field to given value.

### HasJobOperationId

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) HasJobOperationId() bool`

HasJobOperationId returns a boolean if a field has been set.

### GetOperationNumber

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) GetOperationNumber() float64`

GetOperationNumber returns the OperationNumber field if non-nil, zero value otherwise.

### GetOperationNumberOk

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) GetOperationNumberOk() (*float64, bool)`

GetOperationNumberOk returns a tuple with the OperationNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationNumber

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) SetOperationNumber(v float64)`

SetOperationNumber sets OperationNumber field to given value.

### HasOperationNumber

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) HasOperationNumber() bool`

HasOperationNumber returns a boolean if a field has been set.

### GetOperationCode

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) GetOperationCode() string`

GetOperationCode returns the OperationCode field if non-nil, zero value otherwise.

### GetOperationCodeOk

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) GetOperationCodeOk() (*string, bool)`

GetOperationCodeOk returns a tuple with the OperationCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationCode

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) SetOperationCode(v string)`

SetOperationCode sets OperationCode field to given value.

### HasOperationCode

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) HasOperationCode() bool`

HasOperationCode returns a boolean if a field has been set.

### GetJobOperationQuantity

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) GetJobOperationQuantity() float64`

GetJobOperationQuantity returns the JobOperationQuantity field if non-nil, zero value otherwise.

### GetJobOperationQuantityOk

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) GetJobOperationQuantityOk() (*float64, bool)`

GetJobOperationQuantityOk returns a tuple with the JobOperationQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobOperationQuantity

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) SetJobOperationQuantity(v float64)`

SetJobOperationQuantity sets JobOperationQuantity field to given value.

### HasJobOperationQuantity

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) HasJobOperationQuantity() bool`

HasJobOperationQuantity returns a boolean if a field has been set.

### GetPartId

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetPartNumber

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) GetPartNumber() string`

GetPartNumber returns the PartNumber field if non-nil, zero value otherwise.

### GetPartNumberOk

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) GetPartNumberOk() (*string, bool)`

GetPartNumberOk returns a tuple with the PartNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumber

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) SetPartNumber(v string)`

SetPartNumber sets PartNumber field to given value.

### HasPartNumber

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) HasPartNumber() bool`

HasPartNumber returns a boolean if a field has been set.

### GetPartRevision

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) GetPartRevision() string`

GetPartRevision returns the PartRevision field if non-nil, zero value otherwise.

### GetPartRevisionOk

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) GetPartRevisionOk() (*string, bool)`

GetPartRevisionOk returns a tuple with the PartRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartRevision

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) SetPartRevision(v string)`

SetPartRevision sets PartRevision field to given value.

### HasPartRevision

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) HasPartRevision() bool`

HasPartRevision returns a boolean if a field has been set.

### GetPartNumberRevision

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) GetPartNumberRevision() string`

GetPartNumberRevision returns the PartNumberRevision field if non-nil, zero value otherwise.

### GetPartNumberRevisionOk

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) GetPartNumberRevisionOk() (*string, bool)`

GetPartNumberRevisionOk returns a tuple with the PartNumberRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumberRevision

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) SetPartNumberRevision(v string)`

SetPartNumberRevision sets PartNumberRevision field to given value.

### HasPartNumberRevision

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) HasPartNumberRevision() bool`

HasPartNumberRevision returns a boolean if a field has been set.

### GetPartName

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) GetPartName() string`

GetPartName returns the PartName field if non-nil, zero value otherwise.

### GetPartNameOk

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) GetPartNameOk() (*string, bool)`

GetPartNameOk returns a tuple with the PartName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartName

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) SetPartName(v string)`

SetPartName sets PartName field to given value.

### HasPartName

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) HasPartName() bool`

HasPartName returns a boolean if a field has been set.

### GetJobOperationStatus

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) GetJobOperationStatus() string`

GetJobOperationStatus returns the JobOperationStatus field if non-nil, zero value otherwise.

### GetJobOperationStatusOk

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) GetJobOperationStatusOk() (*string, bool)`

GetJobOperationStatusOk returns a tuple with the JobOperationStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobOperationStatus

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) SetJobOperationStatus(v string)`

SetJobOperationStatus sets JobOperationStatus field to given value.

### HasJobOperationStatus

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) HasJobOperationStatus() bool`

HasJobOperationStatus returns a boolean if a field has been set.

### GetJobOperationQuantityCompleted

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) GetJobOperationQuantityCompleted() float64`

GetJobOperationQuantityCompleted returns the JobOperationQuantityCompleted field if non-nil, zero value otherwise.

### GetJobOperationQuantityCompletedOk

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) GetJobOperationQuantityCompletedOk() (*float64, bool)`

GetJobOperationQuantityCompletedOk returns a tuple with the JobOperationQuantityCompleted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobOperationQuantityCompleted

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) SetJobOperationQuantityCompleted(v float64)`

SetJobOperationQuantityCompleted sets JobOperationQuantityCompleted field to given value.

### HasJobOperationQuantityCompleted

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) HasJobOperationQuantityCompleted() bool`

HasJobOperationQuantityCompleted returns a boolean if a field has been set.

### GetJobOperationQuantityBalance

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) GetJobOperationQuantityBalance() float64`

GetJobOperationQuantityBalance returns the JobOperationQuantityBalance field if non-nil, zero value otherwise.

### GetJobOperationQuantityBalanceOk

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) GetJobOperationQuantityBalanceOk() (*float64, bool)`

GetJobOperationQuantityBalanceOk returns a tuple with the JobOperationQuantityBalance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobOperationQuantityBalance

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) SetJobOperationQuantityBalance(v float64)`

SetJobOperationQuantityBalance sets JobOperationQuantityBalance field to given value.

### HasJobOperationQuantityBalance

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) HasJobOperationQuantityBalance() bool`

HasJobOperationQuantityBalance returns a boolean if a field has been set.

### GetContainerType

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) GetContainerType() string`

GetContainerType returns the ContainerType field if non-nil, zero value otherwise.

### GetContainerTypeOk

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) GetContainerTypeOk() (*string, bool)`

GetContainerTypeOk returns a tuple with the ContainerType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContainerType

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) SetContainerType(v string)`

SetContainerType sets ContainerType field to given value.

### HasContainerType

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) HasContainerType() bool`

HasContainerType returns a boolean if a field has been set.

### GetStandardQuantity

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) GetStandardQuantity() float64`

GetStandardQuantity returns the StandardQuantity field if non-nil, zero value otherwise.

### GetStandardQuantityOk

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) GetStandardQuantityOk() (*float64, bool)`

GetStandardQuantityOk returns a tuple with the StandardQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStandardQuantity

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) SetStandardQuantity(v float64)`

SetStandardQuantity sets StandardQuantity field to given value.

### HasStandardQuantity

`func (o *ProductionOperationsManagementApiSearchWorkcenterSetupsItem) HasStandardQuantity() bool`

HasStandardQuantity returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


