# EquipmentApiUpdateEquipmentAttributeRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AttributeName** | Pointer to **string** | The name of the Equipment Attribute. | [optional] 
**Description** | Pointer to **string** | A description of the Equipment Attribute. | [optional] 
**UnitId** | Pointer to **string** | The unit ID associated with the Equipment Attribute. | [optional] 
**UseValues** | Pointer to **bool** | The Use Value Flag. | [optional] 
**TypeAttribute** | Pointer to **bool** | The Type Attribute Flag. | [optional] 
**GroupAttribute** | Pointer to **bool** | The Group Attribute Flag. | [optional] 
**CategoryAttribute** | Pointer to **bool** | The Category Attribute Flag. | [optional] 
**SmartAttribute** | Pointer to **bool** | The Smart Attribute Flag. Operating Parameters module must be enabled for Smart Attributes. | [optional] 
**Active** | Pointer to **bool** | The Active Flag. | [optional] 
**AttributeValues** | Pointer to [**[]AttributeValuesItem**](AttributeValuesItem.md) | List of associated Values if Use Value is enabled. | [optional] 
**AttributeValue** | Pointer to **string** | A value of the Equipment Attribute. | [optional] 
**SortOrder** | Pointer to **int32** | The sort order for the Equipment Attribute Value. | [optional] 

## Methods

### NewEquipmentApiUpdateEquipmentAttributeRequest

`func NewEquipmentApiUpdateEquipmentAttributeRequest() *EquipmentApiUpdateEquipmentAttributeRequest`

NewEquipmentApiUpdateEquipmentAttributeRequest instantiates a new EquipmentApiUpdateEquipmentAttributeRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEquipmentApiUpdateEquipmentAttributeRequestWithDefaults

`func NewEquipmentApiUpdateEquipmentAttributeRequestWithDefaults() *EquipmentApiUpdateEquipmentAttributeRequest`

NewEquipmentApiUpdateEquipmentAttributeRequestWithDefaults instantiates a new EquipmentApiUpdateEquipmentAttributeRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAttributeName

`func (o *EquipmentApiUpdateEquipmentAttributeRequest) GetAttributeName() string`

GetAttributeName returns the AttributeName field if non-nil, zero value otherwise.

### GetAttributeNameOk

`func (o *EquipmentApiUpdateEquipmentAttributeRequest) GetAttributeNameOk() (*string, bool)`

GetAttributeNameOk returns a tuple with the AttributeName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttributeName

`func (o *EquipmentApiUpdateEquipmentAttributeRequest) SetAttributeName(v string)`

SetAttributeName sets AttributeName field to given value.

### HasAttributeName

`func (o *EquipmentApiUpdateEquipmentAttributeRequest) HasAttributeName() bool`

HasAttributeName returns a boolean if a field has been set.

### GetDescription

`func (o *EquipmentApiUpdateEquipmentAttributeRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *EquipmentApiUpdateEquipmentAttributeRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *EquipmentApiUpdateEquipmentAttributeRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *EquipmentApiUpdateEquipmentAttributeRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetUnitId

`func (o *EquipmentApiUpdateEquipmentAttributeRequest) GetUnitId() string`

GetUnitId returns the UnitId field if non-nil, zero value otherwise.

### GetUnitIdOk

`func (o *EquipmentApiUpdateEquipmentAttributeRequest) GetUnitIdOk() (*string, bool)`

GetUnitIdOk returns a tuple with the UnitId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitId

`func (o *EquipmentApiUpdateEquipmentAttributeRequest) SetUnitId(v string)`

SetUnitId sets UnitId field to given value.

### HasUnitId

`func (o *EquipmentApiUpdateEquipmentAttributeRequest) HasUnitId() bool`

HasUnitId returns a boolean if a field has been set.

### GetUseValues

`func (o *EquipmentApiUpdateEquipmentAttributeRequest) GetUseValues() bool`

GetUseValues returns the UseValues field if non-nil, zero value otherwise.

### GetUseValuesOk

`func (o *EquipmentApiUpdateEquipmentAttributeRequest) GetUseValuesOk() (*bool, bool)`

GetUseValuesOk returns a tuple with the UseValues field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUseValues

`func (o *EquipmentApiUpdateEquipmentAttributeRequest) SetUseValues(v bool)`

SetUseValues sets UseValues field to given value.

### HasUseValues

`func (o *EquipmentApiUpdateEquipmentAttributeRequest) HasUseValues() bool`

HasUseValues returns a boolean if a field has been set.

### GetTypeAttribute

`func (o *EquipmentApiUpdateEquipmentAttributeRequest) GetTypeAttribute() bool`

GetTypeAttribute returns the TypeAttribute field if non-nil, zero value otherwise.

### GetTypeAttributeOk

`func (o *EquipmentApiUpdateEquipmentAttributeRequest) GetTypeAttributeOk() (*bool, bool)`

GetTypeAttributeOk returns a tuple with the TypeAttribute field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTypeAttribute

`func (o *EquipmentApiUpdateEquipmentAttributeRequest) SetTypeAttribute(v bool)`

SetTypeAttribute sets TypeAttribute field to given value.

### HasTypeAttribute

`func (o *EquipmentApiUpdateEquipmentAttributeRequest) HasTypeAttribute() bool`

HasTypeAttribute returns a boolean if a field has been set.

### GetGroupAttribute

`func (o *EquipmentApiUpdateEquipmentAttributeRequest) GetGroupAttribute() bool`

GetGroupAttribute returns the GroupAttribute field if non-nil, zero value otherwise.

### GetGroupAttributeOk

`func (o *EquipmentApiUpdateEquipmentAttributeRequest) GetGroupAttributeOk() (*bool, bool)`

GetGroupAttributeOk returns a tuple with the GroupAttribute field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroupAttribute

`func (o *EquipmentApiUpdateEquipmentAttributeRequest) SetGroupAttribute(v bool)`

SetGroupAttribute sets GroupAttribute field to given value.

### HasGroupAttribute

`func (o *EquipmentApiUpdateEquipmentAttributeRequest) HasGroupAttribute() bool`

HasGroupAttribute returns a boolean if a field has been set.

### GetCategoryAttribute

`func (o *EquipmentApiUpdateEquipmentAttributeRequest) GetCategoryAttribute() bool`

GetCategoryAttribute returns the CategoryAttribute field if non-nil, zero value otherwise.

### GetCategoryAttributeOk

`func (o *EquipmentApiUpdateEquipmentAttributeRequest) GetCategoryAttributeOk() (*bool, bool)`

GetCategoryAttributeOk returns a tuple with the CategoryAttribute field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategoryAttribute

`func (o *EquipmentApiUpdateEquipmentAttributeRequest) SetCategoryAttribute(v bool)`

SetCategoryAttribute sets CategoryAttribute field to given value.

### HasCategoryAttribute

`func (o *EquipmentApiUpdateEquipmentAttributeRequest) HasCategoryAttribute() bool`

HasCategoryAttribute returns a boolean if a field has been set.

### GetSmartAttribute

`func (o *EquipmentApiUpdateEquipmentAttributeRequest) GetSmartAttribute() bool`

GetSmartAttribute returns the SmartAttribute field if non-nil, zero value otherwise.

### GetSmartAttributeOk

`func (o *EquipmentApiUpdateEquipmentAttributeRequest) GetSmartAttributeOk() (*bool, bool)`

GetSmartAttributeOk returns a tuple with the SmartAttribute field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSmartAttribute

`func (o *EquipmentApiUpdateEquipmentAttributeRequest) SetSmartAttribute(v bool)`

SetSmartAttribute sets SmartAttribute field to given value.

### HasSmartAttribute

`func (o *EquipmentApiUpdateEquipmentAttributeRequest) HasSmartAttribute() bool`

HasSmartAttribute returns a boolean if a field has been set.

### GetActive

`func (o *EquipmentApiUpdateEquipmentAttributeRequest) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *EquipmentApiUpdateEquipmentAttributeRequest) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *EquipmentApiUpdateEquipmentAttributeRequest) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *EquipmentApiUpdateEquipmentAttributeRequest) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetAttributeValues

`func (o *EquipmentApiUpdateEquipmentAttributeRequest) GetAttributeValues() []AttributeValuesItem`

GetAttributeValues returns the AttributeValues field if non-nil, zero value otherwise.

### GetAttributeValuesOk

`func (o *EquipmentApiUpdateEquipmentAttributeRequest) GetAttributeValuesOk() (*[]AttributeValuesItem, bool)`

GetAttributeValuesOk returns a tuple with the AttributeValues field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttributeValues

`func (o *EquipmentApiUpdateEquipmentAttributeRequest) SetAttributeValues(v []AttributeValuesItem)`

SetAttributeValues sets AttributeValues field to given value.

### HasAttributeValues

`func (o *EquipmentApiUpdateEquipmentAttributeRequest) HasAttributeValues() bool`

HasAttributeValues returns a boolean if a field has been set.

### GetAttributeValue

`func (o *EquipmentApiUpdateEquipmentAttributeRequest) GetAttributeValue() string`

GetAttributeValue returns the AttributeValue field if non-nil, zero value otherwise.

### GetAttributeValueOk

`func (o *EquipmentApiUpdateEquipmentAttributeRequest) GetAttributeValueOk() (*string, bool)`

GetAttributeValueOk returns a tuple with the AttributeValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttributeValue

`func (o *EquipmentApiUpdateEquipmentAttributeRequest) SetAttributeValue(v string)`

SetAttributeValue sets AttributeValue field to given value.

### HasAttributeValue

`func (o *EquipmentApiUpdateEquipmentAttributeRequest) HasAttributeValue() bool`

HasAttributeValue returns a boolean if a field has been set.

### GetSortOrder

`func (o *EquipmentApiUpdateEquipmentAttributeRequest) GetSortOrder() int32`

GetSortOrder returns the SortOrder field if non-nil, zero value otherwise.

### GetSortOrderOk

`func (o *EquipmentApiUpdateEquipmentAttributeRequest) GetSortOrderOk() (*int32, bool)`

GetSortOrderOk returns a tuple with the SortOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSortOrder

`func (o *EquipmentApiUpdateEquipmentAttributeRequest) SetSortOrder(v int32)`

SetSortOrder sets SortOrder field to given value.

### HasSortOrder

`func (o *EquipmentApiUpdateEquipmentAttributeRequest) HasSortOrder() bool`

HasSortOrder returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


