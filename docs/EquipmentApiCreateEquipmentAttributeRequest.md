# EquipmentApiCreateEquipmentAttributeRequest

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

### NewEquipmentApiCreateEquipmentAttributeRequest

`func NewEquipmentApiCreateEquipmentAttributeRequest() *EquipmentApiCreateEquipmentAttributeRequest`

NewEquipmentApiCreateEquipmentAttributeRequest instantiates a new EquipmentApiCreateEquipmentAttributeRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEquipmentApiCreateEquipmentAttributeRequestWithDefaults

`func NewEquipmentApiCreateEquipmentAttributeRequestWithDefaults() *EquipmentApiCreateEquipmentAttributeRequest`

NewEquipmentApiCreateEquipmentAttributeRequestWithDefaults instantiates a new EquipmentApiCreateEquipmentAttributeRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAttributeName

`func (o *EquipmentApiCreateEquipmentAttributeRequest) GetAttributeName() string`

GetAttributeName returns the AttributeName field if non-nil, zero value otherwise.

### GetAttributeNameOk

`func (o *EquipmentApiCreateEquipmentAttributeRequest) GetAttributeNameOk() (*string, bool)`

GetAttributeNameOk returns a tuple with the AttributeName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttributeName

`func (o *EquipmentApiCreateEquipmentAttributeRequest) SetAttributeName(v string)`

SetAttributeName sets AttributeName field to given value.

### HasAttributeName

`func (o *EquipmentApiCreateEquipmentAttributeRequest) HasAttributeName() bool`

HasAttributeName returns a boolean if a field has been set.

### GetDescription

`func (o *EquipmentApiCreateEquipmentAttributeRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *EquipmentApiCreateEquipmentAttributeRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *EquipmentApiCreateEquipmentAttributeRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *EquipmentApiCreateEquipmentAttributeRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetUnitId

`func (o *EquipmentApiCreateEquipmentAttributeRequest) GetUnitId() string`

GetUnitId returns the UnitId field if non-nil, zero value otherwise.

### GetUnitIdOk

`func (o *EquipmentApiCreateEquipmentAttributeRequest) GetUnitIdOk() (*string, bool)`

GetUnitIdOk returns a tuple with the UnitId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitId

`func (o *EquipmentApiCreateEquipmentAttributeRequest) SetUnitId(v string)`

SetUnitId sets UnitId field to given value.

### HasUnitId

`func (o *EquipmentApiCreateEquipmentAttributeRequest) HasUnitId() bool`

HasUnitId returns a boolean if a field has been set.

### GetUseValues

`func (o *EquipmentApiCreateEquipmentAttributeRequest) GetUseValues() bool`

GetUseValues returns the UseValues field if non-nil, zero value otherwise.

### GetUseValuesOk

`func (o *EquipmentApiCreateEquipmentAttributeRequest) GetUseValuesOk() (*bool, bool)`

GetUseValuesOk returns a tuple with the UseValues field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUseValues

`func (o *EquipmentApiCreateEquipmentAttributeRequest) SetUseValues(v bool)`

SetUseValues sets UseValues field to given value.

### HasUseValues

`func (o *EquipmentApiCreateEquipmentAttributeRequest) HasUseValues() bool`

HasUseValues returns a boolean if a field has been set.

### GetTypeAttribute

`func (o *EquipmentApiCreateEquipmentAttributeRequest) GetTypeAttribute() bool`

GetTypeAttribute returns the TypeAttribute field if non-nil, zero value otherwise.

### GetTypeAttributeOk

`func (o *EquipmentApiCreateEquipmentAttributeRequest) GetTypeAttributeOk() (*bool, bool)`

GetTypeAttributeOk returns a tuple with the TypeAttribute field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTypeAttribute

`func (o *EquipmentApiCreateEquipmentAttributeRequest) SetTypeAttribute(v bool)`

SetTypeAttribute sets TypeAttribute field to given value.

### HasTypeAttribute

`func (o *EquipmentApiCreateEquipmentAttributeRequest) HasTypeAttribute() bool`

HasTypeAttribute returns a boolean if a field has been set.

### GetGroupAttribute

`func (o *EquipmentApiCreateEquipmentAttributeRequest) GetGroupAttribute() bool`

GetGroupAttribute returns the GroupAttribute field if non-nil, zero value otherwise.

### GetGroupAttributeOk

`func (o *EquipmentApiCreateEquipmentAttributeRequest) GetGroupAttributeOk() (*bool, bool)`

GetGroupAttributeOk returns a tuple with the GroupAttribute field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroupAttribute

`func (o *EquipmentApiCreateEquipmentAttributeRequest) SetGroupAttribute(v bool)`

SetGroupAttribute sets GroupAttribute field to given value.

### HasGroupAttribute

`func (o *EquipmentApiCreateEquipmentAttributeRequest) HasGroupAttribute() bool`

HasGroupAttribute returns a boolean if a field has been set.

### GetCategoryAttribute

`func (o *EquipmentApiCreateEquipmentAttributeRequest) GetCategoryAttribute() bool`

GetCategoryAttribute returns the CategoryAttribute field if non-nil, zero value otherwise.

### GetCategoryAttributeOk

`func (o *EquipmentApiCreateEquipmentAttributeRequest) GetCategoryAttributeOk() (*bool, bool)`

GetCategoryAttributeOk returns a tuple with the CategoryAttribute field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategoryAttribute

`func (o *EquipmentApiCreateEquipmentAttributeRequest) SetCategoryAttribute(v bool)`

SetCategoryAttribute sets CategoryAttribute field to given value.

### HasCategoryAttribute

`func (o *EquipmentApiCreateEquipmentAttributeRequest) HasCategoryAttribute() bool`

HasCategoryAttribute returns a boolean if a field has been set.

### GetSmartAttribute

`func (o *EquipmentApiCreateEquipmentAttributeRequest) GetSmartAttribute() bool`

GetSmartAttribute returns the SmartAttribute field if non-nil, zero value otherwise.

### GetSmartAttributeOk

`func (o *EquipmentApiCreateEquipmentAttributeRequest) GetSmartAttributeOk() (*bool, bool)`

GetSmartAttributeOk returns a tuple with the SmartAttribute field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSmartAttribute

`func (o *EquipmentApiCreateEquipmentAttributeRequest) SetSmartAttribute(v bool)`

SetSmartAttribute sets SmartAttribute field to given value.

### HasSmartAttribute

`func (o *EquipmentApiCreateEquipmentAttributeRequest) HasSmartAttribute() bool`

HasSmartAttribute returns a boolean if a field has been set.

### GetActive

`func (o *EquipmentApiCreateEquipmentAttributeRequest) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *EquipmentApiCreateEquipmentAttributeRequest) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *EquipmentApiCreateEquipmentAttributeRequest) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *EquipmentApiCreateEquipmentAttributeRequest) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetAttributeValues

`func (o *EquipmentApiCreateEquipmentAttributeRequest) GetAttributeValues() []AttributeValuesItem`

GetAttributeValues returns the AttributeValues field if non-nil, zero value otherwise.

### GetAttributeValuesOk

`func (o *EquipmentApiCreateEquipmentAttributeRequest) GetAttributeValuesOk() (*[]AttributeValuesItem, bool)`

GetAttributeValuesOk returns a tuple with the AttributeValues field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttributeValues

`func (o *EquipmentApiCreateEquipmentAttributeRequest) SetAttributeValues(v []AttributeValuesItem)`

SetAttributeValues sets AttributeValues field to given value.

### HasAttributeValues

`func (o *EquipmentApiCreateEquipmentAttributeRequest) HasAttributeValues() bool`

HasAttributeValues returns a boolean if a field has been set.

### GetAttributeValue

`func (o *EquipmentApiCreateEquipmentAttributeRequest) GetAttributeValue() string`

GetAttributeValue returns the AttributeValue field if non-nil, zero value otherwise.

### GetAttributeValueOk

`func (o *EquipmentApiCreateEquipmentAttributeRequest) GetAttributeValueOk() (*string, bool)`

GetAttributeValueOk returns a tuple with the AttributeValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttributeValue

`func (o *EquipmentApiCreateEquipmentAttributeRequest) SetAttributeValue(v string)`

SetAttributeValue sets AttributeValue field to given value.

### HasAttributeValue

`func (o *EquipmentApiCreateEquipmentAttributeRequest) HasAttributeValue() bool`

HasAttributeValue returns a boolean if a field has been set.

### GetSortOrder

`func (o *EquipmentApiCreateEquipmentAttributeRequest) GetSortOrder() int32`

GetSortOrder returns the SortOrder field if non-nil, zero value otherwise.

### GetSortOrderOk

`func (o *EquipmentApiCreateEquipmentAttributeRequest) GetSortOrderOk() (*int32, bool)`

GetSortOrderOk returns a tuple with the SortOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSortOrder

`func (o *EquipmentApiCreateEquipmentAttributeRequest) SetSortOrder(v int32)`

SetSortOrder sets SortOrder field to given value.

### HasSortOrder

`func (o *EquipmentApiCreateEquipmentAttributeRequest) HasSortOrder() bool`

HasSortOrder returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


