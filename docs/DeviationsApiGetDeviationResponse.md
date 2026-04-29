# DeviationsApiGetDeviationResponse

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

### NewDeviationsApiGetDeviationResponse

`func NewDeviationsApiGetDeviationResponse() *DeviationsApiGetDeviationResponse`

NewDeviationsApiGetDeviationResponse instantiates a new DeviationsApiGetDeviationResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeviationsApiGetDeviationResponseWithDefaults

`func NewDeviationsApiGetDeviationResponseWithDefaults() *DeviationsApiGetDeviationResponse`

NewDeviationsApiGetDeviationResponseWithDefaults instantiates a new DeviationsApiGetDeviationResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *DeviationsApiGetDeviationResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *DeviationsApiGetDeviationResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *DeviationsApiGetDeviationResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *DeviationsApiGetDeviationResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetAcknowledgementLimit

`func (o *DeviationsApiGetDeviationResponse) GetAcknowledgementLimit() int32`

GetAcknowledgementLimit returns the AcknowledgementLimit field if non-nil, zero value otherwise.

### GetAcknowledgementLimitOk

`func (o *DeviationsApiGetDeviationResponse) GetAcknowledgementLimitOk() (*int32, bool)`

GetAcknowledgementLimitOk returns a tuple with the AcknowledgementLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAcknowledgementLimit

`func (o *DeviationsApiGetDeviationResponse) SetAcknowledgementLimit(v int32)`

SetAcknowledgementLimit sets AcknowledgementLimit field to given value.

### HasAcknowledgementLimit

`func (o *DeviationsApiGetDeviationResponse) HasAcknowledgementLimit() bool`

HasAcknowledgementLimit returns a boolean if a field has been set.

### GetApprovedByUserId

`func (o *DeviationsApiGetDeviationResponse) GetApprovedByUserId() string`

GetApprovedByUserId returns the ApprovedByUserId field if non-nil, zero value otherwise.

### GetApprovedByUserIdOk

`func (o *DeviationsApiGetDeviationResponse) GetApprovedByUserIdOk() (*string, bool)`

GetApprovedByUserIdOk returns a tuple with the ApprovedByUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovedByUserId

`func (o *DeviationsApiGetDeviationResponse) SetApprovedByUserId(v string)`

SetApprovedByUserId sets ApprovedByUserId field to given value.

### HasApprovedByUserId

`func (o *DeviationsApiGetDeviationResponse) HasApprovedByUserId() bool`

HasApprovedByUserId returns a boolean if a field has been set.

### GetApprovedDate

`func (o *DeviationsApiGetDeviationResponse) GetApprovedDate() time.Time`

GetApprovedDate returns the ApprovedDate field if non-nil, zero value otherwise.

### GetApprovedDateOk

`func (o *DeviationsApiGetDeviationResponse) GetApprovedDateOk() (*time.Time, bool)`

GetApprovedDateOk returns a tuple with the ApprovedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovedDate

`func (o *DeviationsApiGetDeviationResponse) SetApprovedDate(v time.Time)`

SetApprovedDate sets ApprovedDate field to given value.

### HasApprovedDate

`func (o *DeviationsApiGetDeviationResponse) HasApprovedDate() bool`

HasApprovedDate returns a boolean if a field has been set.

### GetBuildingId

`func (o *DeviationsApiGetDeviationResponse) GetBuildingId() string`

GetBuildingId returns the BuildingId field if non-nil, zero value otherwise.

### GetBuildingIdOk

`func (o *DeviationsApiGetDeviationResponse) GetBuildingIdOk() (*string, bool)`

GetBuildingIdOk returns a tuple with the BuildingId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildingId

`func (o *DeviationsApiGetDeviationResponse) SetBuildingId(v string)`

SetBuildingId sets BuildingId field to given value.

### HasBuildingId

`func (o *DeviationsApiGetDeviationResponse) HasBuildingId() bool`

HasBuildingId returns a boolean if a field has been set.

### GetBuildingCode

`func (o *DeviationsApiGetDeviationResponse) GetBuildingCode() string`

GetBuildingCode returns the BuildingCode field if non-nil, zero value otherwise.

### GetBuildingCodeOk

`func (o *DeviationsApiGetDeviationResponse) GetBuildingCodeOk() (*string, bool)`

GetBuildingCodeOk returns a tuple with the BuildingCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildingCode

`func (o *DeviationsApiGetDeviationResponse) SetBuildingCode(v string)`

SetBuildingCode sets BuildingCode field to given value.

### HasBuildingCode

`func (o *DeviationsApiGetDeviationResponse) HasBuildingCode() bool`

HasBuildingCode returns a boolean if a field has been set.

### GetCodeNo

`func (o *DeviationsApiGetDeviationResponse) GetCodeNo() string`

GetCodeNo returns the CodeNo field if non-nil, zero value otherwise.

### GetCodeNoOk

`func (o *DeviationsApiGetDeviationResponse) GetCodeNoOk() (*string, bool)`

GetCodeNoOk returns a tuple with the CodeNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCodeNo

`func (o *DeviationsApiGetDeviationResponse) SetCodeNo(v string)`

SetCodeNo sets CodeNo field to given value.

### HasCodeNo

`func (o *DeviationsApiGetDeviationResponse) HasCodeNo() bool`

HasCodeNo returns a boolean if a field has been set.

### GetDepartmentCode

`func (o *DeviationsApiGetDeviationResponse) GetDepartmentCode() string`

GetDepartmentCode returns the DepartmentCode field if non-nil, zero value otherwise.

### GetDepartmentCodeOk

`func (o *DeviationsApiGetDeviationResponse) GetDepartmentCodeOk() (*string, bool)`

GetDepartmentCodeOk returns a tuple with the DepartmentCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDepartmentCode

`func (o *DeviationsApiGetDeviationResponse) SetDepartmentCode(v string)`

SetDepartmentCode sets DepartmentCode field to given value.

### HasDepartmentCode

`func (o *DeviationsApiGetDeviationResponse) HasDepartmentCode() bool`

HasDepartmentCode returns a boolean if a field has been set.

### GetDeviationAcknowledgementFrequencyDescription

`func (o *DeviationsApiGetDeviationResponse) GetDeviationAcknowledgementFrequencyDescription() string`

GetDeviationAcknowledgementFrequencyDescription returns the DeviationAcknowledgementFrequencyDescription field if non-nil, zero value otherwise.

### GetDeviationAcknowledgementFrequencyDescriptionOk

`func (o *DeviationsApiGetDeviationResponse) GetDeviationAcknowledgementFrequencyDescriptionOk() (*string, bool)`

GetDeviationAcknowledgementFrequencyDescriptionOk returns a tuple with the DeviationAcknowledgementFrequencyDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviationAcknowledgementFrequencyDescription

`func (o *DeviationsApiGetDeviationResponse) SetDeviationAcknowledgementFrequencyDescription(v string)`

SetDeviationAcknowledgementFrequencyDescription sets DeviationAcknowledgementFrequencyDescription field to given value.

### HasDeviationAcknowledgementFrequencyDescription

`func (o *DeviationsApiGetDeviationResponse) HasDeviationAcknowledgementFrequencyDescription() bool`

HasDeviationAcknowledgementFrequencyDescription returns a boolean if a field has been set.

### GetDeviationNo

`func (o *DeviationsApiGetDeviationResponse) GetDeviationNo() string`

GetDeviationNo returns the DeviationNo field if non-nil, zero value otherwise.

### GetDeviationNoOk

`func (o *DeviationsApiGetDeviationResponse) GetDeviationNoOk() (*string, bool)`

GetDeviationNoOk returns a tuple with the DeviationNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviationNo

`func (o *DeviationsApiGetDeviationResponse) SetDeviationNo(v string)`

SetDeviationNo sets DeviationNo field to given value.

### HasDeviationNo

`func (o *DeviationsApiGetDeviationResponse) HasDeviationNo() bool`

HasDeviationNo returns a boolean if a field has been set.

### GetDeviationStatus

`func (o *DeviationsApiGetDeviationResponse) GetDeviationStatus() string`

GetDeviationStatus returns the DeviationStatus field if non-nil, zero value otherwise.

### GetDeviationStatusOk

`func (o *DeviationsApiGetDeviationResponse) GetDeviationStatusOk() (*string, bool)`

GetDeviationStatusOk returns a tuple with the DeviationStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviationStatus

`func (o *DeviationsApiGetDeviationResponse) SetDeviationStatus(v string)`

SetDeviationStatus sets DeviationStatus field to given value.

### HasDeviationStatus

`func (o *DeviationsApiGetDeviationResponse) HasDeviationStatus() bool`

HasDeviationStatus returns a boolean if a field has been set.

### GetEffectiveDate

`func (o *DeviationsApiGetDeviationResponse) GetEffectiveDate() time.Time`

GetEffectiveDate returns the EffectiveDate field if non-nil, zero value otherwise.

### GetEffectiveDateOk

`func (o *DeviationsApiGetDeviationResponse) GetEffectiveDateOk() (*time.Time, bool)`

GetEffectiveDateOk returns a tuple with the EffectiveDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEffectiveDate

`func (o *DeviationsApiGetDeviationResponse) SetEffectiveDate(v time.Time)`

SetEffectiveDate sets EffectiveDate field to given value.

### HasEffectiveDate

`func (o *DeviationsApiGetDeviationResponse) HasEffectiveDate() bool`

HasEffectiveDate returns a boolean if a field has been set.

### GetExpirationDate

`func (o *DeviationsApiGetDeviationResponse) GetExpirationDate() time.Time`

GetExpirationDate returns the ExpirationDate field if non-nil, zero value otherwise.

### GetExpirationDateOk

`func (o *DeviationsApiGetDeviationResponse) GetExpirationDateOk() (*time.Time, bool)`

GetExpirationDateOk returns a tuple with the ExpirationDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpirationDate

`func (o *DeviationsApiGetDeviationResponse) SetExpirationDate(v time.Time)`

SetExpirationDate sets ExpirationDate field to given value.

### HasExpirationDate

`func (o *DeviationsApiGetDeviationResponse) HasExpirationDate() bool`

HasExpirationDate returns a boolean if a field has been set.

### GetJobIds

`func (o *DeviationsApiGetDeviationResponse) GetJobIds() []string`

GetJobIds returns the JobIds field if non-nil, zero value otherwise.

### GetJobIdsOk

`func (o *DeviationsApiGetDeviationResponse) GetJobIdsOk() (*[]string, bool)`

GetJobIdsOk returns a tuple with the JobIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobIds

`func (o *DeviationsApiGetDeviationResponse) SetJobIds(v []string)`

SetJobIds sets JobIds field to given value.

### HasJobIds

`func (o *DeviationsApiGetDeviationResponse) HasJobIds() bool`

HasJobIds returns a boolean if a field has been set.

### GetNote

`func (o *DeviationsApiGetDeviationResponse) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *DeviationsApiGetDeviationResponse) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *DeviationsApiGetDeviationResponse) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *DeviationsApiGetDeviationResponse) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetType

`func (o *DeviationsApiGetDeviationResponse) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *DeviationsApiGetDeviationResponse) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *DeviationsApiGetDeviationResponse) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *DeviationsApiGetDeviationResponse) HasType() bool`

HasType returns a boolean if a field has been set.

### GetParts

`func (o *DeviationsApiGetDeviationResponse) GetParts() []PartsItem`

GetParts returns the Parts field if non-nil, zero value otherwise.

### GetPartsOk

`func (o *DeviationsApiGetDeviationResponse) GetPartsOk() (*[]PartsItem, bool)`

GetPartsOk returns a tuple with the Parts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParts

`func (o *DeviationsApiGetDeviationResponse) SetParts(v []PartsItem)`

SetParts sets Parts field to given value.

### HasParts

`func (o *DeviationsApiGetDeviationResponse) HasParts() bool`

HasParts returns a boolean if a field has been set.

### GetPiecesAffected

`func (o *DeviationsApiGetDeviationResponse) GetPiecesAffected() int32`

GetPiecesAffected returns the PiecesAffected field if non-nil, zero value otherwise.

### GetPiecesAffectedOk

`func (o *DeviationsApiGetDeviationResponse) GetPiecesAffectedOk() (*int32, bool)`

GetPiecesAffectedOk returns a tuple with the PiecesAffected field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPiecesAffected

`func (o *DeviationsApiGetDeviationResponse) SetPiecesAffected(v int32)`

SetPiecesAffected sets PiecesAffected field to given value.

### HasPiecesAffected

`func (o *DeviationsApiGetDeviationResponse) HasPiecesAffected() bool`

HasPiecesAffected returns a boolean if a field has been set.

### GetReason

`func (o *DeviationsApiGetDeviationResponse) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *DeviationsApiGetDeviationResponse) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *DeviationsApiGetDeviationResponse) SetReason(v string)`

SetReason sets Reason field to given value.

### HasReason

`func (o *DeviationsApiGetDeviationResponse) HasReason() bool`

HasReason returns a boolean if a field has been set.

### GetRevisionDeviationId

`func (o *DeviationsApiGetDeviationResponse) GetRevisionDeviationId() string`

GetRevisionDeviationId returns the RevisionDeviationId field if non-nil, zero value otherwise.

### GetRevisionDeviationIdOk

`func (o *DeviationsApiGetDeviationResponse) GetRevisionDeviationIdOk() (*string, bool)`

GetRevisionDeviationIdOk returns a tuple with the RevisionDeviationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevisionDeviationId

`func (o *DeviationsApiGetDeviationResponse) SetRevisionDeviationId(v string)`

SetRevisionDeviationId sets RevisionDeviationId field to given value.

### HasRevisionDeviationId

`func (o *DeviationsApiGetDeviationResponse) HasRevisionDeviationId() bool`

HasRevisionDeviationId returns a boolean if a field has been set.

### GetRevisionDeviationNo

`func (o *DeviationsApiGetDeviationResponse) GetRevisionDeviationNo() string`

GetRevisionDeviationNo returns the RevisionDeviationNo field if non-nil, zero value otherwise.

### GetRevisionDeviationNoOk

`func (o *DeviationsApiGetDeviationResponse) GetRevisionDeviationNoOk() (*string, bool)`

GetRevisionDeviationNoOk returns a tuple with the RevisionDeviationNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevisionDeviationNo

`func (o *DeviationsApiGetDeviationResponse) SetRevisionDeviationNo(v string)`

SetRevisionDeviationNo sets RevisionDeviationNo field to given value.

### HasRevisionDeviationNo

`func (o *DeviationsApiGetDeviationResponse) HasRevisionDeviationNo() bool`

HasRevisionDeviationNo returns a boolean if a field has been set.

### GetSupplierId

`func (o *DeviationsApiGetDeviationResponse) GetSupplierId() string`

GetSupplierId returns the SupplierId field if non-nil, zero value otherwise.

### GetSupplierIdOk

`func (o *DeviationsApiGetDeviationResponse) GetSupplierIdOk() (*string, bool)`

GetSupplierIdOk returns a tuple with the SupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierId

`func (o *DeviationsApiGetDeviationResponse) SetSupplierId(v string)`

SetSupplierId sets SupplierId field to given value.

### HasSupplierId

`func (o *DeviationsApiGetDeviationResponse) HasSupplierId() bool`

HasSupplierId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


