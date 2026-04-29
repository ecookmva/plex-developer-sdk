# EquipmentApiGetEquipmentResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | The ID of the Equipment. | [optional] 
**EquipmentId** | Pointer to **string** | The Equipment ID. | [optional] 
**Description** | Pointer to **string** | The Equipment Description. | [optional] 
**Brand** | Pointer to **string** | The Equipment Brand. | [optional] 
**ModelNo** | Pointer to **string** | The Equipment Model Number. | [optional] 
**EquipmentType** | Pointer to **string** | The Equipment Type of the Equipment. | [optional] 
**EquipmentTypeId** | Pointer to **string** | The ID of the Equipment Type. | [optional] 
**EquipmentGroup** | Pointer to **string** | The Group of the Equipment. | [optional] 
**EquipmentCategory** | Pointer to **string** | The Category of the Equipment. | [optional] 
**EquipmentPriority** | Pointer to **string** | The Priority of the Equipment. | [optional] 
**Location** | Pointer to **string** | The Location of the Equipment. | [optional] 
**LocationId** | Pointer to **string** | The ID of the Equipment Location. | [optional] 
**Building** | Pointer to **string** | The Building of the Equipment. | [optional] 
**BuildingId** | Pointer to **string** | The ID of the Equipment Building. | [optional] 
**Workcenter** | Pointer to **string** | The Workcenter of the Equipment. | [optional] 
**WorkcenterId** | Pointer to **string** | The ID of the Equipment Workcenter. | [optional] 
**Department** | Pointer to **string** | The Department of the Equipment. | [optional] 
**Status** | Pointer to **string** | The Status of the Equipment. | [optional] 
**TaxClassification** | Pointer to **string** | The Tax Classification of the Equipment. | [optional] 
**Champion** | Pointer to **string** | The Champion of the Equipment. | [optional] 
**SerialNo** | Pointer to **string** | The Equipment Serial Number. | [optional] 
**Active** | Pointer to **bool** | The Equipment Active flag. | [optional] 
**EquipmentAttributes** | Pointer to [**[]EquipmentAttributesItem**](EquipmentAttributesItem.md) | The list of associated Equipment Attributes. | [optional] 
**Parts** | Pointer to [**[]PartsItem1**](PartsItem1.md) | The list of associated Parts. | [optional] 

## Methods

### NewEquipmentApiGetEquipmentResponse

`func NewEquipmentApiGetEquipmentResponse() *EquipmentApiGetEquipmentResponse`

NewEquipmentApiGetEquipmentResponse instantiates a new EquipmentApiGetEquipmentResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEquipmentApiGetEquipmentResponseWithDefaults

`func NewEquipmentApiGetEquipmentResponseWithDefaults() *EquipmentApiGetEquipmentResponse`

NewEquipmentApiGetEquipmentResponseWithDefaults instantiates a new EquipmentApiGetEquipmentResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *EquipmentApiGetEquipmentResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *EquipmentApiGetEquipmentResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *EquipmentApiGetEquipmentResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *EquipmentApiGetEquipmentResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetEquipmentId

`func (o *EquipmentApiGetEquipmentResponse) GetEquipmentId() string`

GetEquipmentId returns the EquipmentId field if non-nil, zero value otherwise.

### GetEquipmentIdOk

`func (o *EquipmentApiGetEquipmentResponse) GetEquipmentIdOk() (*string, bool)`

GetEquipmentIdOk returns a tuple with the EquipmentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEquipmentId

`func (o *EquipmentApiGetEquipmentResponse) SetEquipmentId(v string)`

SetEquipmentId sets EquipmentId field to given value.

### HasEquipmentId

`func (o *EquipmentApiGetEquipmentResponse) HasEquipmentId() bool`

HasEquipmentId returns a boolean if a field has been set.

### GetDescription

`func (o *EquipmentApiGetEquipmentResponse) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *EquipmentApiGetEquipmentResponse) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *EquipmentApiGetEquipmentResponse) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *EquipmentApiGetEquipmentResponse) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetBrand

`func (o *EquipmentApiGetEquipmentResponse) GetBrand() string`

GetBrand returns the Brand field if non-nil, zero value otherwise.

### GetBrandOk

`func (o *EquipmentApiGetEquipmentResponse) GetBrandOk() (*string, bool)`

GetBrandOk returns a tuple with the Brand field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrand

`func (o *EquipmentApiGetEquipmentResponse) SetBrand(v string)`

SetBrand sets Brand field to given value.

### HasBrand

`func (o *EquipmentApiGetEquipmentResponse) HasBrand() bool`

HasBrand returns a boolean if a field has been set.

### GetModelNo

`func (o *EquipmentApiGetEquipmentResponse) GetModelNo() string`

GetModelNo returns the ModelNo field if non-nil, zero value otherwise.

### GetModelNoOk

`func (o *EquipmentApiGetEquipmentResponse) GetModelNoOk() (*string, bool)`

GetModelNoOk returns a tuple with the ModelNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModelNo

`func (o *EquipmentApiGetEquipmentResponse) SetModelNo(v string)`

SetModelNo sets ModelNo field to given value.

### HasModelNo

`func (o *EquipmentApiGetEquipmentResponse) HasModelNo() bool`

HasModelNo returns a boolean if a field has been set.

### GetEquipmentType

`func (o *EquipmentApiGetEquipmentResponse) GetEquipmentType() string`

GetEquipmentType returns the EquipmentType field if non-nil, zero value otherwise.

### GetEquipmentTypeOk

`func (o *EquipmentApiGetEquipmentResponse) GetEquipmentTypeOk() (*string, bool)`

GetEquipmentTypeOk returns a tuple with the EquipmentType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEquipmentType

`func (o *EquipmentApiGetEquipmentResponse) SetEquipmentType(v string)`

SetEquipmentType sets EquipmentType field to given value.

### HasEquipmentType

`func (o *EquipmentApiGetEquipmentResponse) HasEquipmentType() bool`

HasEquipmentType returns a boolean if a field has been set.

### GetEquipmentTypeId

`func (o *EquipmentApiGetEquipmentResponse) GetEquipmentTypeId() string`

GetEquipmentTypeId returns the EquipmentTypeId field if non-nil, zero value otherwise.

### GetEquipmentTypeIdOk

`func (o *EquipmentApiGetEquipmentResponse) GetEquipmentTypeIdOk() (*string, bool)`

GetEquipmentTypeIdOk returns a tuple with the EquipmentTypeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEquipmentTypeId

`func (o *EquipmentApiGetEquipmentResponse) SetEquipmentTypeId(v string)`

SetEquipmentTypeId sets EquipmentTypeId field to given value.

### HasEquipmentTypeId

`func (o *EquipmentApiGetEquipmentResponse) HasEquipmentTypeId() bool`

HasEquipmentTypeId returns a boolean if a field has been set.

### GetEquipmentGroup

`func (o *EquipmentApiGetEquipmentResponse) GetEquipmentGroup() string`

GetEquipmentGroup returns the EquipmentGroup field if non-nil, zero value otherwise.

### GetEquipmentGroupOk

`func (o *EquipmentApiGetEquipmentResponse) GetEquipmentGroupOk() (*string, bool)`

GetEquipmentGroupOk returns a tuple with the EquipmentGroup field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEquipmentGroup

`func (o *EquipmentApiGetEquipmentResponse) SetEquipmentGroup(v string)`

SetEquipmentGroup sets EquipmentGroup field to given value.

### HasEquipmentGroup

`func (o *EquipmentApiGetEquipmentResponse) HasEquipmentGroup() bool`

HasEquipmentGroup returns a boolean if a field has been set.

### GetEquipmentCategory

`func (o *EquipmentApiGetEquipmentResponse) GetEquipmentCategory() string`

GetEquipmentCategory returns the EquipmentCategory field if non-nil, zero value otherwise.

### GetEquipmentCategoryOk

`func (o *EquipmentApiGetEquipmentResponse) GetEquipmentCategoryOk() (*string, bool)`

GetEquipmentCategoryOk returns a tuple with the EquipmentCategory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEquipmentCategory

`func (o *EquipmentApiGetEquipmentResponse) SetEquipmentCategory(v string)`

SetEquipmentCategory sets EquipmentCategory field to given value.

### HasEquipmentCategory

`func (o *EquipmentApiGetEquipmentResponse) HasEquipmentCategory() bool`

HasEquipmentCategory returns a boolean if a field has been set.

### GetEquipmentPriority

`func (o *EquipmentApiGetEquipmentResponse) GetEquipmentPriority() string`

GetEquipmentPriority returns the EquipmentPriority field if non-nil, zero value otherwise.

### GetEquipmentPriorityOk

`func (o *EquipmentApiGetEquipmentResponse) GetEquipmentPriorityOk() (*string, bool)`

GetEquipmentPriorityOk returns a tuple with the EquipmentPriority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEquipmentPriority

`func (o *EquipmentApiGetEquipmentResponse) SetEquipmentPriority(v string)`

SetEquipmentPriority sets EquipmentPriority field to given value.

### HasEquipmentPriority

`func (o *EquipmentApiGetEquipmentResponse) HasEquipmentPriority() bool`

HasEquipmentPriority returns a boolean if a field has been set.

### GetLocation

`func (o *EquipmentApiGetEquipmentResponse) GetLocation() string`

GetLocation returns the Location field if non-nil, zero value otherwise.

### GetLocationOk

`func (o *EquipmentApiGetEquipmentResponse) GetLocationOk() (*string, bool)`

GetLocationOk returns a tuple with the Location field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocation

`func (o *EquipmentApiGetEquipmentResponse) SetLocation(v string)`

SetLocation sets Location field to given value.

### HasLocation

`func (o *EquipmentApiGetEquipmentResponse) HasLocation() bool`

HasLocation returns a boolean if a field has been set.

### GetLocationId

`func (o *EquipmentApiGetEquipmentResponse) GetLocationId() string`

GetLocationId returns the LocationId field if non-nil, zero value otherwise.

### GetLocationIdOk

`func (o *EquipmentApiGetEquipmentResponse) GetLocationIdOk() (*string, bool)`

GetLocationIdOk returns a tuple with the LocationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocationId

`func (o *EquipmentApiGetEquipmentResponse) SetLocationId(v string)`

SetLocationId sets LocationId field to given value.

### HasLocationId

`func (o *EquipmentApiGetEquipmentResponse) HasLocationId() bool`

HasLocationId returns a boolean if a field has been set.

### GetBuilding

`func (o *EquipmentApiGetEquipmentResponse) GetBuilding() string`

GetBuilding returns the Building field if non-nil, zero value otherwise.

### GetBuildingOk

`func (o *EquipmentApiGetEquipmentResponse) GetBuildingOk() (*string, bool)`

GetBuildingOk returns a tuple with the Building field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuilding

`func (o *EquipmentApiGetEquipmentResponse) SetBuilding(v string)`

SetBuilding sets Building field to given value.

### HasBuilding

`func (o *EquipmentApiGetEquipmentResponse) HasBuilding() bool`

HasBuilding returns a boolean if a field has been set.

### GetBuildingId

`func (o *EquipmentApiGetEquipmentResponse) GetBuildingId() string`

GetBuildingId returns the BuildingId field if non-nil, zero value otherwise.

### GetBuildingIdOk

`func (o *EquipmentApiGetEquipmentResponse) GetBuildingIdOk() (*string, bool)`

GetBuildingIdOk returns a tuple with the BuildingId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildingId

`func (o *EquipmentApiGetEquipmentResponse) SetBuildingId(v string)`

SetBuildingId sets BuildingId field to given value.

### HasBuildingId

`func (o *EquipmentApiGetEquipmentResponse) HasBuildingId() bool`

HasBuildingId returns a boolean if a field has been set.

### GetWorkcenter

`func (o *EquipmentApiGetEquipmentResponse) GetWorkcenter() string`

GetWorkcenter returns the Workcenter field if non-nil, zero value otherwise.

### GetWorkcenterOk

`func (o *EquipmentApiGetEquipmentResponse) GetWorkcenterOk() (*string, bool)`

GetWorkcenterOk returns a tuple with the Workcenter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkcenter

`func (o *EquipmentApiGetEquipmentResponse) SetWorkcenter(v string)`

SetWorkcenter sets Workcenter field to given value.

### HasWorkcenter

`func (o *EquipmentApiGetEquipmentResponse) HasWorkcenter() bool`

HasWorkcenter returns a boolean if a field has been set.

### GetWorkcenterId

`func (o *EquipmentApiGetEquipmentResponse) GetWorkcenterId() string`

GetWorkcenterId returns the WorkcenterId field if non-nil, zero value otherwise.

### GetWorkcenterIdOk

`func (o *EquipmentApiGetEquipmentResponse) GetWorkcenterIdOk() (*string, bool)`

GetWorkcenterIdOk returns a tuple with the WorkcenterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkcenterId

`func (o *EquipmentApiGetEquipmentResponse) SetWorkcenterId(v string)`

SetWorkcenterId sets WorkcenterId field to given value.

### HasWorkcenterId

`func (o *EquipmentApiGetEquipmentResponse) HasWorkcenterId() bool`

HasWorkcenterId returns a boolean if a field has been set.

### GetDepartment

`func (o *EquipmentApiGetEquipmentResponse) GetDepartment() string`

GetDepartment returns the Department field if non-nil, zero value otherwise.

### GetDepartmentOk

`func (o *EquipmentApiGetEquipmentResponse) GetDepartmentOk() (*string, bool)`

GetDepartmentOk returns a tuple with the Department field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDepartment

`func (o *EquipmentApiGetEquipmentResponse) SetDepartment(v string)`

SetDepartment sets Department field to given value.

### HasDepartment

`func (o *EquipmentApiGetEquipmentResponse) HasDepartment() bool`

HasDepartment returns a boolean if a field has been set.

### GetStatus

`func (o *EquipmentApiGetEquipmentResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *EquipmentApiGetEquipmentResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *EquipmentApiGetEquipmentResponse) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *EquipmentApiGetEquipmentResponse) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetTaxClassification

`func (o *EquipmentApiGetEquipmentResponse) GetTaxClassification() string`

GetTaxClassification returns the TaxClassification field if non-nil, zero value otherwise.

### GetTaxClassificationOk

`func (o *EquipmentApiGetEquipmentResponse) GetTaxClassificationOk() (*string, bool)`

GetTaxClassificationOk returns a tuple with the TaxClassification field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxClassification

`func (o *EquipmentApiGetEquipmentResponse) SetTaxClassification(v string)`

SetTaxClassification sets TaxClassification field to given value.

### HasTaxClassification

`func (o *EquipmentApiGetEquipmentResponse) HasTaxClassification() bool`

HasTaxClassification returns a boolean if a field has been set.

### GetChampion

`func (o *EquipmentApiGetEquipmentResponse) GetChampion() string`

GetChampion returns the Champion field if non-nil, zero value otherwise.

### GetChampionOk

`func (o *EquipmentApiGetEquipmentResponse) GetChampionOk() (*string, bool)`

GetChampionOk returns a tuple with the Champion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChampion

`func (o *EquipmentApiGetEquipmentResponse) SetChampion(v string)`

SetChampion sets Champion field to given value.

### HasChampion

`func (o *EquipmentApiGetEquipmentResponse) HasChampion() bool`

HasChampion returns a boolean if a field has been set.

### GetSerialNo

`func (o *EquipmentApiGetEquipmentResponse) GetSerialNo() string`

GetSerialNo returns the SerialNo field if non-nil, zero value otherwise.

### GetSerialNoOk

`func (o *EquipmentApiGetEquipmentResponse) GetSerialNoOk() (*string, bool)`

GetSerialNoOk returns a tuple with the SerialNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSerialNo

`func (o *EquipmentApiGetEquipmentResponse) SetSerialNo(v string)`

SetSerialNo sets SerialNo field to given value.

### HasSerialNo

`func (o *EquipmentApiGetEquipmentResponse) HasSerialNo() bool`

HasSerialNo returns a boolean if a field has been set.

### GetActive

`func (o *EquipmentApiGetEquipmentResponse) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *EquipmentApiGetEquipmentResponse) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *EquipmentApiGetEquipmentResponse) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *EquipmentApiGetEquipmentResponse) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetEquipmentAttributes

`func (o *EquipmentApiGetEquipmentResponse) GetEquipmentAttributes() []EquipmentAttributesItem`

GetEquipmentAttributes returns the EquipmentAttributes field if non-nil, zero value otherwise.

### GetEquipmentAttributesOk

`func (o *EquipmentApiGetEquipmentResponse) GetEquipmentAttributesOk() (*[]EquipmentAttributesItem, bool)`

GetEquipmentAttributesOk returns a tuple with the EquipmentAttributes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEquipmentAttributes

`func (o *EquipmentApiGetEquipmentResponse) SetEquipmentAttributes(v []EquipmentAttributesItem)`

SetEquipmentAttributes sets EquipmentAttributes field to given value.

### HasEquipmentAttributes

`func (o *EquipmentApiGetEquipmentResponse) HasEquipmentAttributes() bool`

HasEquipmentAttributes returns a boolean if a field has been set.

### GetParts

`func (o *EquipmentApiGetEquipmentResponse) GetParts() []PartsItem1`

GetParts returns the Parts field if non-nil, zero value otherwise.

### GetPartsOk

`func (o *EquipmentApiGetEquipmentResponse) GetPartsOk() (*[]PartsItem1, bool)`

GetPartsOk returns a tuple with the Parts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParts

`func (o *EquipmentApiGetEquipmentResponse) SetParts(v []PartsItem1)`

SetParts sets Parts field to given value.

### HasParts

`func (o *EquipmentApiGetEquipmentResponse) HasParts() bool`

HasParts returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


