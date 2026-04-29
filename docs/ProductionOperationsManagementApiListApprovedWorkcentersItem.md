# ProductionOperationsManagementApiListApprovedWorkcentersItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**WorkcenterId** | Pointer to **string** | The ID of the workcenter. | [optional] 
**WorkcenterCode** | Pointer to **string** | A short name associated to the &amp;quot;workcenterID&amp;quot; and a unique code to reference the workcenter. This code shows up throughout the system, primarily on the Control Panel. 50 characters max. | [optional] 
**WorkcenterName** | Pointer to **string** | The name associated to the &amp;quot;workcenterID&amp;quot;. | [optional] 
**PartId** | Pointer to **string** | The ID of the part that is produced. | [optional] 
**PartNo** | Pointer to **string** | The part number associated to the &amp;quot;partId&amp;quot; that is produced. Acceptable part number characters include uppercase and lowercase letters (A-Z), numbers (0-9), and special characters such as dashes (-), underscores ( _ ), and spaces. Part numbers cannot use question marks or ampersands. Other characters may cause issues. | [optional] 
**PartRevision** | Pointer to **string** | The part revision of the &amp;quot;partId&amp;quot;. A revision represents a change or modification to a part or part drawing that is usually initiated through an engineering change request (ECR). | [optional] 
**PartNoRevision** | Pointer to **string** | The part number and revision formatted with separator. If a part number has a revision, Plex will return the part number and the revision separated by the Part Rev Separator setting. A Part Rev Separator can be up to 5 characters long. Format {partNumber}{part rev separator}{revision}. | [optional] 
**PartOperationId** | Pointer to **string** | The ID of the part operation. | [optional] 
**OperationId** | Pointer to **string** | The operation associated with the Part Operation. | [optional] 
**OperationNo** | Pointer to **int32** | The operation number of the part operation. | [optional] 
**OperationCode** | Pointer to **string** | The operation code associated to the &amp;quot;partOperationId&amp;quot;. 30 characters max. | [optional] 
**CrewSize** | Pointer to **float64** | The crew size associated with the workcenter. | [optional] 
**StandardProductionRate** | Pointer to **float64** | The standard production rate associated with the workcenter. | [optional] 
**Note** | Pointer to **string** | The note associated with the workcenter. | [optional] 
**SetupTime** | Pointer to **float64** | The setup time associated with the workcenter. | [optional] 
**IdealRate** | Pointer to **float64** | The ideal rate associated with the workcenter. | [optional] 
**TargetRate** | Pointer to **float64** | The target rate associated with the workcenter. | [optional] 
**SetupCrewSize** | Pointer to **float64** | The setup crew size associated with the workcenter. | [optional] 
**SequenceRate** | Pointer to **float64** | The sequence rate associated with the workcenter. | [optional] 

## Methods

### NewProductionOperationsManagementApiListApprovedWorkcentersItem

`func NewProductionOperationsManagementApiListApprovedWorkcentersItem() *ProductionOperationsManagementApiListApprovedWorkcentersItem`

NewProductionOperationsManagementApiListApprovedWorkcentersItem instantiates a new ProductionOperationsManagementApiListApprovedWorkcentersItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductionOperationsManagementApiListApprovedWorkcentersItemWithDefaults

`func NewProductionOperationsManagementApiListApprovedWorkcentersItemWithDefaults() *ProductionOperationsManagementApiListApprovedWorkcentersItem`

NewProductionOperationsManagementApiListApprovedWorkcentersItemWithDefaults instantiates a new ProductionOperationsManagementApiListApprovedWorkcentersItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetWorkcenterId

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) GetWorkcenterId() string`

GetWorkcenterId returns the WorkcenterId field if non-nil, zero value otherwise.

### GetWorkcenterIdOk

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) GetWorkcenterIdOk() (*string, bool)`

GetWorkcenterIdOk returns a tuple with the WorkcenterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkcenterId

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) SetWorkcenterId(v string)`

SetWorkcenterId sets WorkcenterId field to given value.

### HasWorkcenterId

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) HasWorkcenterId() bool`

HasWorkcenterId returns a boolean if a field has been set.

### GetWorkcenterCode

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) GetWorkcenterCode() string`

GetWorkcenterCode returns the WorkcenterCode field if non-nil, zero value otherwise.

### GetWorkcenterCodeOk

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) GetWorkcenterCodeOk() (*string, bool)`

GetWorkcenterCodeOk returns a tuple with the WorkcenterCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkcenterCode

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) SetWorkcenterCode(v string)`

SetWorkcenterCode sets WorkcenterCode field to given value.

### HasWorkcenterCode

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) HasWorkcenterCode() bool`

HasWorkcenterCode returns a boolean if a field has been set.

### GetWorkcenterName

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) GetWorkcenterName() string`

GetWorkcenterName returns the WorkcenterName field if non-nil, zero value otherwise.

### GetWorkcenterNameOk

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) GetWorkcenterNameOk() (*string, bool)`

GetWorkcenterNameOk returns a tuple with the WorkcenterName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkcenterName

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) SetWorkcenterName(v string)`

SetWorkcenterName sets WorkcenterName field to given value.

### HasWorkcenterName

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) HasWorkcenterName() bool`

HasWorkcenterName returns a boolean if a field has been set.

### GetPartId

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetPartNo

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) GetPartNo() string`

GetPartNo returns the PartNo field if non-nil, zero value otherwise.

### GetPartNoOk

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) GetPartNoOk() (*string, bool)`

GetPartNoOk returns a tuple with the PartNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNo

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) SetPartNo(v string)`

SetPartNo sets PartNo field to given value.

### HasPartNo

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) HasPartNo() bool`

HasPartNo returns a boolean if a field has been set.

### GetPartRevision

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) GetPartRevision() string`

GetPartRevision returns the PartRevision field if non-nil, zero value otherwise.

### GetPartRevisionOk

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) GetPartRevisionOk() (*string, bool)`

GetPartRevisionOk returns a tuple with the PartRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartRevision

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) SetPartRevision(v string)`

SetPartRevision sets PartRevision field to given value.

### HasPartRevision

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) HasPartRevision() bool`

HasPartRevision returns a boolean if a field has been set.

### GetPartNoRevision

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) GetPartNoRevision() string`

GetPartNoRevision returns the PartNoRevision field if non-nil, zero value otherwise.

### GetPartNoRevisionOk

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) GetPartNoRevisionOk() (*string, bool)`

GetPartNoRevisionOk returns a tuple with the PartNoRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNoRevision

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) SetPartNoRevision(v string)`

SetPartNoRevision sets PartNoRevision field to given value.

### HasPartNoRevision

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) HasPartNoRevision() bool`

HasPartNoRevision returns a boolean if a field has been set.

### GetPartOperationId

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) GetPartOperationId() string`

GetPartOperationId returns the PartOperationId field if non-nil, zero value otherwise.

### GetPartOperationIdOk

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) GetPartOperationIdOk() (*string, bool)`

GetPartOperationIdOk returns a tuple with the PartOperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartOperationId

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) SetPartOperationId(v string)`

SetPartOperationId sets PartOperationId field to given value.

### HasPartOperationId

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) HasPartOperationId() bool`

HasPartOperationId returns a boolean if a field has been set.

### GetOperationId

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) GetOperationId() string`

GetOperationId returns the OperationId field if non-nil, zero value otherwise.

### GetOperationIdOk

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) GetOperationIdOk() (*string, bool)`

GetOperationIdOk returns a tuple with the OperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationId

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) SetOperationId(v string)`

SetOperationId sets OperationId field to given value.

### HasOperationId

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) HasOperationId() bool`

HasOperationId returns a boolean if a field has been set.

### GetOperationNo

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) GetOperationNo() int32`

GetOperationNo returns the OperationNo field if non-nil, zero value otherwise.

### GetOperationNoOk

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) GetOperationNoOk() (*int32, bool)`

GetOperationNoOk returns a tuple with the OperationNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationNo

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) SetOperationNo(v int32)`

SetOperationNo sets OperationNo field to given value.

### HasOperationNo

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) HasOperationNo() bool`

HasOperationNo returns a boolean if a field has been set.

### GetOperationCode

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) GetOperationCode() string`

GetOperationCode returns the OperationCode field if non-nil, zero value otherwise.

### GetOperationCodeOk

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) GetOperationCodeOk() (*string, bool)`

GetOperationCodeOk returns a tuple with the OperationCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationCode

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) SetOperationCode(v string)`

SetOperationCode sets OperationCode field to given value.

### HasOperationCode

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) HasOperationCode() bool`

HasOperationCode returns a boolean if a field has been set.

### GetCrewSize

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) GetCrewSize() float64`

GetCrewSize returns the CrewSize field if non-nil, zero value otherwise.

### GetCrewSizeOk

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) GetCrewSizeOk() (*float64, bool)`

GetCrewSizeOk returns a tuple with the CrewSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCrewSize

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) SetCrewSize(v float64)`

SetCrewSize sets CrewSize field to given value.

### HasCrewSize

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) HasCrewSize() bool`

HasCrewSize returns a boolean if a field has been set.

### GetStandardProductionRate

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) GetStandardProductionRate() float64`

GetStandardProductionRate returns the StandardProductionRate field if non-nil, zero value otherwise.

### GetStandardProductionRateOk

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) GetStandardProductionRateOk() (*float64, bool)`

GetStandardProductionRateOk returns a tuple with the StandardProductionRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStandardProductionRate

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) SetStandardProductionRate(v float64)`

SetStandardProductionRate sets StandardProductionRate field to given value.

### HasStandardProductionRate

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) HasStandardProductionRate() bool`

HasStandardProductionRate returns a boolean if a field has been set.

### GetNote

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetSetupTime

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) GetSetupTime() float64`

GetSetupTime returns the SetupTime field if non-nil, zero value otherwise.

### GetSetupTimeOk

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) GetSetupTimeOk() (*float64, bool)`

GetSetupTimeOk returns a tuple with the SetupTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSetupTime

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) SetSetupTime(v float64)`

SetSetupTime sets SetupTime field to given value.

### HasSetupTime

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) HasSetupTime() bool`

HasSetupTime returns a boolean if a field has been set.

### GetIdealRate

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) GetIdealRate() float64`

GetIdealRate returns the IdealRate field if non-nil, zero value otherwise.

### GetIdealRateOk

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) GetIdealRateOk() (*float64, bool)`

GetIdealRateOk returns a tuple with the IdealRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdealRate

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) SetIdealRate(v float64)`

SetIdealRate sets IdealRate field to given value.

### HasIdealRate

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) HasIdealRate() bool`

HasIdealRate returns a boolean if a field has been set.

### GetTargetRate

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) GetTargetRate() float64`

GetTargetRate returns the TargetRate field if non-nil, zero value otherwise.

### GetTargetRateOk

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) GetTargetRateOk() (*float64, bool)`

GetTargetRateOk returns a tuple with the TargetRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetRate

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) SetTargetRate(v float64)`

SetTargetRate sets TargetRate field to given value.

### HasTargetRate

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) HasTargetRate() bool`

HasTargetRate returns a boolean if a field has been set.

### GetSetupCrewSize

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) GetSetupCrewSize() float64`

GetSetupCrewSize returns the SetupCrewSize field if non-nil, zero value otherwise.

### GetSetupCrewSizeOk

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) GetSetupCrewSizeOk() (*float64, bool)`

GetSetupCrewSizeOk returns a tuple with the SetupCrewSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSetupCrewSize

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) SetSetupCrewSize(v float64)`

SetSetupCrewSize sets SetupCrewSize field to given value.

### HasSetupCrewSize

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) HasSetupCrewSize() bool`

HasSetupCrewSize returns a boolean if a field has been set.

### GetSequenceRate

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) GetSequenceRate() float64`

GetSequenceRate returns the SequenceRate field if non-nil, zero value otherwise.

### GetSequenceRateOk

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) GetSequenceRateOk() (*float64, bool)`

GetSequenceRateOk returns a tuple with the SequenceRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSequenceRate

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) SetSequenceRate(v float64)`

SetSequenceRate sets SequenceRate field to given value.

### HasSequenceRate

`func (o *ProductionOperationsManagementApiListApprovedWorkcentersItem) HasSequenceRate() bool`

HasSequenceRate returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


