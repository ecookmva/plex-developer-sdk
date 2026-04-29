# EquipmentAttributesItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | An ID representing the Equipment Attribute. | [optional] 
**AttributeName** | Pointer to **string** | The name of the Equipment Attribute. | [optional] 
**Description** | Pointer to **string** | A description of the Equipment Attribute. | [optional] 
**Unit** | Pointer to **string** | The unit associated with the Equipment Attribute. | [optional] 
**UseValues** | Pointer to **bool** | The Use Value Flag. | [optional] 
**TypeAttribute** | Pointer to **bool** | The Type Attribute Flag. | [optional] 
**GroupAttribute** | Pointer to **bool** | The Group Attribute Flag. | [optional] 
**CategoryAttribute** | Pointer to **bool** | The Category Attribute Flag. | [optional] 
**SmartAttribute** | Pointer to **bool** | The Smart Attribute Flag. | [optional] 
**Active** | Pointer to **bool** | The Active Flag. | [optional] 
**Value** | Pointer to **string** | The Value of the Equipment Attribute. | [optional] 
**Note** | Pointer to **string** | The Note of the Equipment Attribute. | [optional] 
**PlcName** | Pointer to **string** | The PLC Name for the Equipment Attribute. | [optional] 

## Methods

### NewEquipmentAttributesItem

`func NewEquipmentAttributesItem() *EquipmentAttributesItem`

NewEquipmentAttributesItem instantiates a new EquipmentAttributesItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEquipmentAttributesItemWithDefaults

`func NewEquipmentAttributesItemWithDefaults() *EquipmentAttributesItem`

NewEquipmentAttributesItemWithDefaults instantiates a new EquipmentAttributesItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *EquipmentAttributesItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *EquipmentAttributesItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *EquipmentAttributesItem) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *EquipmentAttributesItem) HasId() bool`

HasId returns a boolean if a field has been set.

### GetAttributeName

`func (o *EquipmentAttributesItem) GetAttributeName() string`

GetAttributeName returns the AttributeName field if non-nil, zero value otherwise.

### GetAttributeNameOk

`func (o *EquipmentAttributesItem) GetAttributeNameOk() (*string, bool)`

GetAttributeNameOk returns a tuple with the AttributeName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttributeName

`func (o *EquipmentAttributesItem) SetAttributeName(v string)`

SetAttributeName sets AttributeName field to given value.

### HasAttributeName

`func (o *EquipmentAttributesItem) HasAttributeName() bool`

HasAttributeName returns a boolean if a field has been set.

### GetDescription

`func (o *EquipmentAttributesItem) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *EquipmentAttributesItem) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *EquipmentAttributesItem) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *EquipmentAttributesItem) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetUnit

`func (o *EquipmentAttributesItem) GetUnit() string`

GetUnit returns the Unit field if non-nil, zero value otherwise.

### GetUnitOk

`func (o *EquipmentAttributesItem) GetUnitOk() (*string, bool)`

GetUnitOk returns a tuple with the Unit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnit

`func (o *EquipmentAttributesItem) SetUnit(v string)`

SetUnit sets Unit field to given value.

### HasUnit

`func (o *EquipmentAttributesItem) HasUnit() bool`

HasUnit returns a boolean if a field has been set.

### GetUseValues

`func (o *EquipmentAttributesItem) GetUseValues() bool`

GetUseValues returns the UseValues field if non-nil, zero value otherwise.

### GetUseValuesOk

`func (o *EquipmentAttributesItem) GetUseValuesOk() (*bool, bool)`

GetUseValuesOk returns a tuple with the UseValues field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUseValues

`func (o *EquipmentAttributesItem) SetUseValues(v bool)`

SetUseValues sets UseValues field to given value.

### HasUseValues

`func (o *EquipmentAttributesItem) HasUseValues() bool`

HasUseValues returns a boolean if a field has been set.

### GetTypeAttribute

`func (o *EquipmentAttributesItem) GetTypeAttribute() bool`

GetTypeAttribute returns the TypeAttribute field if non-nil, zero value otherwise.

### GetTypeAttributeOk

`func (o *EquipmentAttributesItem) GetTypeAttributeOk() (*bool, bool)`

GetTypeAttributeOk returns a tuple with the TypeAttribute field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTypeAttribute

`func (o *EquipmentAttributesItem) SetTypeAttribute(v bool)`

SetTypeAttribute sets TypeAttribute field to given value.

### HasTypeAttribute

`func (o *EquipmentAttributesItem) HasTypeAttribute() bool`

HasTypeAttribute returns a boolean if a field has been set.

### GetGroupAttribute

`func (o *EquipmentAttributesItem) GetGroupAttribute() bool`

GetGroupAttribute returns the GroupAttribute field if non-nil, zero value otherwise.

### GetGroupAttributeOk

`func (o *EquipmentAttributesItem) GetGroupAttributeOk() (*bool, bool)`

GetGroupAttributeOk returns a tuple with the GroupAttribute field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroupAttribute

`func (o *EquipmentAttributesItem) SetGroupAttribute(v bool)`

SetGroupAttribute sets GroupAttribute field to given value.

### HasGroupAttribute

`func (o *EquipmentAttributesItem) HasGroupAttribute() bool`

HasGroupAttribute returns a boolean if a field has been set.

### GetCategoryAttribute

`func (o *EquipmentAttributesItem) GetCategoryAttribute() bool`

GetCategoryAttribute returns the CategoryAttribute field if non-nil, zero value otherwise.

### GetCategoryAttributeOk

`func (o *EquipmentAttributesItem) GetCategoryAttributeOk() (*bool, bool)`

GetCategoryAttributeOk returns a tuple with the CategoryAttribute field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategoryAttribute

`func (o *EquipmentAttributesItem) SetCategoryAttribute(v bool)`

SetCategoryAttribute sets CategoryAttribute field to given value.

### HasCategoryAttribute

`func (o *EquipmentAttributesItem) HasCategoryAttribute() bool`

HasCategoryAttribute returns a boolean if a field has been set.

### GetSmartAttribute

`func (o *EquipmentAttributesItem) GetSmartAttribute() bool`

GetSmartAttribute returns the SmartAttribute field if non-nil, zero value otherwise.

### GetSmartAttributeOk

`func (o *EquipmentAttributesItem) GetSmartAttributeOk() (*bool, bool)`

GetSmartAttributeOk returns a tuple with the SmartAttribute field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSmartAttribute

`func (o *EquipmentAttributesItem) SetSmartAttribute(v bool)`

SetSmartAttribute sets SmartAttribute field to given value.

### HasSmartAttribute

`func (o *EquipmentAttributesItem) HasSmartAttribute() bool`

HasSmartAttribute returns a boolean if a field has been set.

### GetActive

`func (o *EquipmentAttributesItem) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *EquipmentAttributesItem) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *EquipmentAttributesItem) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *EquipmentAttributesItem) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetValue

`func (o *EquipmentAttributesItem) GetValue() string`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *EquipmentAttributesItem) GetValueOk() (*string, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *EquipmentAttributesItem) SetValue(v string)`

SetValue sets Value field to given value.

### HasValue

`func (o *EquipmentAttributesItem) HasValue() bool`

HasValue returns a boolean if a field has been set.

### GetNote

`func (o *EquipmentAttributesItem) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *EquipmentAttributesItem) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *EquipmentAttributesItem) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *EquipmentAttributesItem) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetPlcName

`func (o *EquipmentAttributesItem) GetPlcName() string`

GetPlcName returns the PlcName field if non-nil, zero value otherwise.

### GetPlcNameOk

`func (o *EquipmentAttributesItem) GetPlcNameOk() (*string, bool)`

GetPlcNameOk returns a tuple with the PlcName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlcName

`func (o *EquipmentAttributesItem) SetPlcName(v string)`

SetPlcName sets PlcName field to given value.

### HasPlcName

`func (o *EquipmentAttributesItem) HasPlcName() bool`

HasPlcName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


