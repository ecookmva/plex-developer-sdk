# DeviationsApiListDeviationsItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | ID representing the deviation. | [optional] 
**AcknowledgementLimit** | Pointer to **int32** | The acknowledgement limit. | [optional] 
**ApprovedByUserId** | Pointer to **string** | ID representing the approving user. | [optional] 
**ApprovedDate** | Pointer to **time.Time** | The approved date. | [optional] 
**BuildingId** | Pointer to **string** | ID representing the building. | [optional] 
**BuildingCode** | Pointer to **string** | The building code. | [optional] 
**CodeNo** | Pointer to **string** | The code no. | [optional] 
**DepartmentCode** | Pointer to **string** | The department code. | [optional] 
**DeviationAcknowledgementFrequencyDescription** | Pointer to **string** | The deviation acknowledgement frequency. | [optional] 
**DeviationNo** | Pointer to **string** | The deviation no. | [optional] 
**DeviationStatus** | Pointer to **string** | The deviation status. | [optional] 
**EffectiveDate** | Pointer to **time.Time** | The effective date. | [optional] 
**ExpirationDate** | Pointer to **time.Time** | The expiration date. | [optional] 
**JobIds** | Pointer to **[]string** | A list of IDs representing deviation jobs. | [optional] 
**Note** | Pointer to **string** | The deviation note. | [optional] 
**Type** | Pointer to **string** | The deviation type. | [optional] 
**Parts** | Pointer to [**[]PartsItem**](PartsItem.md) | A list of deviation parts. | [optional] 
**PiecesAffected** | Pointer to **int32** | The pieces affected. | [optional] 
**Reason** | Pointer to **string** | The deviation reason. | [optional] 
**RevisionDeviationId** | Pointer to **string** | ID representing the revision deviation. | [optional] 
**RevisionDeviationNo** | Pointer to **string** | The revision deviation no. | [optional] 
**SupplierId** | Pointer to **string** | ID representing the supplier. | [optional] 

## Methods

### NewDeviationsApiListDeviationsItem

`func NewDeviationsApiListDeviationsItem() *DeviationsApiListDeviationsItem`

NewDeviationsApiListDeviationsItem instantiates a new DeviationsApiListDeviationsItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeviationsApiListDeviationsItemWithDefaults

`func NewDeviationsApiListDeviationsItemWithDefaults() *DeviationsApiListDeviationsItem`

NewDeviationsApiListDeviationsItemWithDefaults instantiates a new DeviationsApiListDeviationsItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *DeviationsApiListDeviationsItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *DeviationsApiListDeviationsItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *DeviationsApiListDeviationsItem) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *DeviationsApiListDeviationsItem) HasId() bool`

HasId returns a boolean if a field has been set.

### GetAcknowledgementLimit

`func (o *DeviationsApiListDeviationsItem) GetAcknowledgementLimit() int32`

GetAcknowledgementLimit returns the AcknowledgementLimit field if non-nil, zero value otherwise.

### GetAcknowledgementLimitOk

`func (o *DeviationsApiListDeviationsItem) GetAcknowledgementLimitOk() (*int32, bool)`

GetAcknowledgementLimitOk returns a tuple with the AcknowledgementLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAcknowledgementLimit

`func (o *DeviationsApiListDeviationsItem) SetAcknowledgementLimit(v int32)`

SetAcknowledgementLimit sets AcknowledgementLimit field to given value.

### HasAcknowledgementLimit

`func (o *DeviationsApiListDeviationsItem) HasAcknowledgementLimit() bool`

HasAcknowledgementLimit returns a boolean if a field has been set.

### GetApprovedByUserId

`func (o *DeviationsApiListDeviationsItem) GetApprovedByUserId() string`

GetApprovedByUserId returns the ApprovedByUserId field if non-nil, zero value otherwise.

### GetApprovedByUserIdOk

`func (o *DeviationsApiListDeviationsItem) GetApprovedByUserIdOk() (*string, bool)`

GetApprovedByUserIdOk returns a tuple with the ApprovedByUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovedByUserId

`func (o *DeviationsApiListDeviationsItem) SetApprovedByUserId(v string)`

SetApprovedByUserId sets ApprovedByUserId field to given value.

### HasApprovedByUserId

`func (o *DeviationsApiListDeviationsItem) HasApprovedByUserId() bool`

HasApprovedByUserId returns a boolean if a field has been set.

### GetApprovedDate

`func (o *DeviationsApiListDeviationsItem) GetApprovedDate() time.Time`

GetApprovedDate returns the ApprovedDate field if non-nil, zero value otherwise.

### GetApprovedDateOk

`func (o *DeviationsApiListDeviationsItem) GetApprovedDateOk() (*time.Time, bool)`

GetApprovedDateOk returns a tuple with the ApprovedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovedDate

`func (o *DeviationsApiListDeviationsItem) SetApprovedDate(v time.Time)`

SetApprovedDate sets ApprovedDate field to given value.

### HasApprovedDate

`func (o *DeviationsApiListDeviationsItem) HasApprovedDate() bool`

HasApprovedDate returns a boolean if a field has been set.

### GetBuildingId

`func (o *DeviationsApiListDeviationsItem) GetBuildingId() string`

GetBuildingId returns the BuildingId field if non-nil, zero value otherwise.

### GetBuildingIdOk

`func (o *DeviationsApiListDeviationsItem) GetBuildingIdOk() (*string, bool)`

GetBuildingIdOk returns a tuple with the BuildingId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildingId

`func (o *DeviationsApiListDeviationsItem) SetBuildingId(v string)`

SetBuildingId sets BuildingId field to given value.

### HasBuildingId

`func (o *DeviationsApiListDeviationsItem) HasBuildingId() bool`

HasBuildingId returns a boolean if a field has been set.

### GetBuildingCode

`func (o *DeviationsApiListDeviationsItem) GetBuildingCode() string`

GetBuildingCode returns the BuildingCode field if non-nil, zero value otherwise.

### GetBuildingCodeOk

`func (o *DeviationsApiListDeviationsItem) GetBuildingCodeOk() (*string, bool)`

GetBuildingCodeOk returns a tuple with the BuildingCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildingCode

`func (o *DeviationsApiListDeviationsItem) SetBuildingCode(v string)`

SetBuildingCode sets BuildingCode field to given value.

### HasBuildingCode

`func (o *DeviationsApiListDeviationsItem) HasBuildingCode() bool`

HasBuildingCode returns a boolean if a field has been set.

### GetCodeNo

`func (o *DeviationsApiListDeviationsItem) GetCodeNo() string`

GetCodeNo returns the CodeNo field if non-nil, zero value otherwise.

### GetCodeNoOk

`func (o *DeviationsApiListDeviationsItem) GetCodeNoOk() (*string, bool)`

GetCodeNoOk returns a tuple with the CodeNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCodeNo

`func (o *DeviationsApiListDeviationsItem) SetCodeNo(v string)`

SetCodeNo sets CodeNo field to given value.

### HasCodeNo

`func (o *DeviationsApiListDeviationsItem) HasCodeNo() bool`

HasCodeNo returns a boolean if a field has been set.

### GetDepartmentCode

`func (o *DeviationsApiListDeviationsItem) GetDepartmentCode() string`

GetDepartmentCode returns the DepartmentCode field if non-nil, zero value otherwise.

### GetDepartmentCodeOk

`func (o *DeviationsApiListDeviationsItem) GetDepartmentCodeOk() (*string, bool)`

GetDepartmentCodeOk returns a tuple with the DepartmentCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDepartmentCode

`func (o *DeviationsApiListDeviationsItem) SetDepartmentCode(v string)`

SetDepartmentCode sets DepartmentCode field to given value.

### HasDepartmentCode

`func (o *DeviationsApiListDeviationsItem) HasDepartmentCode() bool`

HasDepartmentCode returns a boolean if a field has been set.

### GetDeviationAcknowledgementFrequencyDescription

`func (o *DeviationsApiListDeviationsItem) GetDeviationAcknowledgementFrequencyDescription() string`

GetDeviationAcknowledgementFrequencyDescription returns the DeviationAcknowledgementFrequencyDescription field if non-nil, zero value otherwise.

### GetDeviationAcknowledgementFrequencyDescriptionOk

`func (o *DeviationsApiListDeviationsItem) GetDeviationAcknowledgementFrequencyDescriptionOk() (*string, bool)`

GetDeviationAcknowledgementFrequencyDescriptionOk returns a tuple with the DeviationAcknowledgementFrequencyDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviationAcknowledgementFrequencyDescription

`func (o *DeviationsApiListDeviationsItem) SetDeviationAcknowledgementFrequencyDescription(v string)`

SetDeviationAcknowledgementFrequencyDescription sets DeviationAcknowledgementFrequencyDescription field to given value.

### HasDeviationAcknowledgementFrequencyDescription

`func (o *DeviationsApiListDeviationsItem) HasDeviationAcknowledgementFrequencyDescription() bool`

HasDeviationAcknowledgementFrequencyDescription returns a boolean if a field has been set.

### GetDeviationNo

`func (o *DeviationsApiListDeviationsItem) GetDeviationNo() string`

GetDeviationNo returns the DeviationNo field if non-nil, zero value otherwise.

### GetDeviationNoOk

`func (o *DeviationsApiListDeviationsItem) GetDeviationNoOk() (*string, bool)`

GetDeviationNoOk returns a tuple with the DeviationNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviationNo

`func (o *DeviationsApiListDeviationsItem) SetDeviationNo(v string)`

SetDeviationNo sets DeviationNo field to given value.

### HasDeviationNo

`func (o *DeviationsApiListDeviationsItem) HasDeviationNo() bool`

HasDeviationNo returns a boolean if a field has been set.

### GetDeviationStatus

`func (o *DeviationsApiListDeviationsItem) GetDeviationStatus() string`

GetDeviationStatus returns the DeviationStatus field if non-nil, zero value otherwise.

### GetDeviationStatusOk

`func (o *DeviationsApiListDeviationsItem) GetDeviationStatusOk() (*string, bool)`

GetDeviationStatusOk returns a tuple with the DeviationStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviationStatus

`func (o *DeviationsApiListDeviationsItem) SetDeviationStatus(v string)`

SetDeviationStatus sets DeviationStatus field to given value.

### HasDeviationStatus

`func (o *DeviationsApiListDeviationsItem) HasDeviationStatus() bool`

HasDeviationStatus returns a boolean if a field has been set.

### GetEffectiveDate

`func (o *DeviationsApiListDeviationsItem) GetEffectiveDate() time.Time`

GetEffectiveDate returns the EffectiveDate field if non-nil, zero value otherwise.

### GetEffectiveDateOk

`func (o *DeviationsApiListDeviationsItem) GetEffectiveDateOk() (*time.Time, bool)`

GetEffectiveDateOk returns a tuple with the EffectiveDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEffectiveDate

`func (o *DeviationsApiListDeviationsItem) SetEffectiveDate(v time.Time)`

SetEffectiveDate sets EffectiveDate field to given value.

### HasEffectiveDate

`func (o *DeviationsApiListDeviationsItem) HasEffectiveDate() bool`

HasEffectiveDate returns a boolean if a field has been set.

### GetExpirationDate

`func (o *DeviationsApiListDeviationsItem) GetExpirationDate() time.Time`

GetExpirationDate returns the ExpirationDate field if non-nil, zero value otherwise.

### GetExpirationDateOk

`func (o *DeviationsApiListDeviationsItem) GetExpirationDateOk() (*time.Time, bool)`

GetExpirationDateOk returns a tuple with the ExpirationDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpirationDate

`func (o *DeviationsApiListDeviationsItem) SetExpirationDate(v time.Time)`

SetExpirationDate sets ExpirationDate field to given value.

### HasExpirationDate

`func (o *DeviationsApiListDeviationsItem) HasExpirationDate() bool`

HasExpirationDate returns a boolean if a field has been set.

### GetJobIds

`func (o *DeviationsApiListDeviationsItem) GetJobIds() []string`

GetJobIds returns the JobIds field if non-nil, zero value otherwise.

### GetJobIdsOk

`func (o *DeviationsApiListDeviationsItem) GetJobIdsOk() (*[]string, bool)`

GetJobIdsOk returns a tuple with the JobIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobIds

`func (o *DeviationsApiListDeviationsItem) SetJobIds(v []string)`

SetJobIds sets JobIds field to given value.

### HasJobIds

`func (o *DeviationsApiListDeviationsItem) HasJobIds() bool`

HasJobIds returns a boolean if a field has been set.

### GetNote

`func (o *DeviationsApiListDeviationsItem) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *DeviationsApiListDeviationsItem) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *DeviationsApiListDeviationsItem) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *DeviationsApiListDeviationsItem) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetType

`func (o *DeviationsApiListDeviationsItem) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *DeviationsApiListDeviationsItem) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *DeviationsApiListDeviationsItem) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *DeviationsApiListDeviationsItem) HasType() bool`

HasType returns a boolean if a field has been set.

### GetParts

`func (o *DeviationsApiListDeviationsItem) GetParts() []PartsItem`

GetParts returns the Parts field if non-nil, zero value otherwise.

### GetPartsOk

`func (o *DeviationsApiListDeviationsItem) GetPartsOk() (*[]PartsItem, bool)`

GetPartsOk returns a tuple with the Parts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParts

`func (o *DeviationsApiListDeviationsItem) SetParts(v []PartsItem)`

SetParts sets Parts field to given value.

### HasParts

`func (o *DeviationsApiListDeviationsItem) HasParts() bool`

HasParts returns a boolean if a field has been set.

### GetPiecesAffected

`func (o *DeviationsApiListDeviationsItem) GetPiecesAffected() int32`

GetPiecesAffected returns the PiecesAffected field if non-nil, zero value otherwise.

### GetPiecesAffectedOk

`func (o *DeviationsApiListDeviationsItem) GetPiecesAffectedOk() (*int32, bool)`

GetPiecesAffectedOk returns a tuple with the PiecesAffected field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPiecesAffected

`func (o *DeviationsApiListDeviationsItem) SetPiecesAffected(v int32)`

SetPiecesAffected sets PiecesAffected field to given value.

### HasPiecesAffected

`func (o *DeviationsApiListDeviationsItem) HasPiecesAffected() bool`

HasPiecesAffected returns a boolean if a field has been set.

### GetReason

`func (o *DeviationsApiListDeviationsItem) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *DeviationsApiListDeviationsItem) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *DeviationsApiListDeviationsItem) SetReason(v string)`

SetReason sets Reason field to given value.

### HasReason

`func (o *DeviationsApiListDeviationsItem) HasReason() bool`

HasReason returns a boolean if a field has been set.

### GetRevisionDeviationId

`func (o *DeviationsApiListDeviationsItem) GetRevisionDeviationId() string`

GetRevisionDeviationId returns the RevisionDeviationId field if non-nil, zero value otherwise.

### GetRevisionDeviationIdOk

`func (o *DeviationsApiListDeviationsItem) GetRevisionDeviationIdOk() (*string, bool)`

GetRevisionDeviationIdOk returns a tuple with the RevisionDeviationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevisionDeviationId

`func (o *DeviationsApiListDeviationsItem) SetRevisionDeviationId(v string)`

SetRevisionDeviationId sets RevisionDeviationId field to given value.

### HasRevisionDeviationId

`func (o *DeviationsApiListDeviationsItem) HasRevisionDeviationId() bool`

HasRevisionDeviationId returns a boolean if a field has been set.

### GetRevisionDeviationNo

`func (o *DeviationsApiListDeviationsItem) GetRevisionDeviationNo() string`

GetRevisionDeviationNo returns the RevisionDeviationNo field if non-nil, zero value otherwise.

### GetRevisionDeviationNoOk

`func (o *DeviationsApiListDeviationsItem) GetRevisionDeviationNoOk() (*string, bool)`

GetRevisionDeviationNoOk returns a tuple with the RevisionDeviationNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevisionDeviationNo

`func (o *DeviationsApiListDeviationsItem) SetRevisionDeviationNo(v string)`

SetRevisionDeviationNo sets RevisionDeviationNo field to given value.

### HasRevisionDeviationNo

`func (o *DeviationsApiListDeviationsItem) HasRevisionDeviationNo() bool`

HasRevisionDeviationNo returns a boolean if a field has been set.

### GetSupplierId

`func (o *DeviationsApiListDeviationsItem) GetSupplierId() string`

GetSupplierId returns the SupplierId field if non-nil, zero value otherwise.

### GetSupplierIdOk

`func (o *DeviationsApiListDeviationsItem) GetSupplierIdOk() (*string, bool)`

GetSupplierIdOk returns a tuple with the SupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierId

`func (o *DeviationsApiListDeviationsItem) SetSupplierId(v string)`

SetSupplierId sets SupplierId field to given value.

### HasSupplierId

`func (o *DeviationsApiListDeviationsItem) HasSupplierId() bool`

HasSupplierId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


