# EquipmentApiGetEquipmentAttributesResponse

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

## Methods

### NewEquipmentApiGetEquipmentAttributesResponse

`func NewEquipmentApiGetEquipmentAttributesResponse() *EquipmentApiGetEquipmentAttributesResponse`

NewEquipmentApiGetEquipmentAttributesResponse instantiates a new EquipmentApiGetEquipmentAttributesResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEquipmentApiGetEquipmentAttributesResponseWithDefaults

`func NewEquipmentApiGetEquipmentAttributesResponseWithDefaults() *EquipmentApiGetEquipmentAttributesResponse`

NewEquipmentApiGetEquipmentAttributesResponseWithDefaults instantiates a new EquipmentApiGetEquipmentAttributesResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *EquipmentApiGetEquipmentAttributesResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *EquipmentApiGetEquipmentAttributesResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *EquipmentApiGetEquipmentAttributesResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *EquipmentApiGetEquipmentAttributesResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetAttributeName

`func (o *EquipmentApiGetEquipmentAttributesResponse) GetAttributeName() string`

GetAttributeName returns the AttributeName field if non-nil, zero value otherwise.

### GetAttributeNameOk

`func (o *EquipmentApiGetEquipmentAttributesResponse) GetAttributeNameOk() (*string, bool)`

GetAttributeNameOk returns a tuple with the AttributeName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttributeName

`func (o *EquipmentApiGetEquipmentAttributesResponse) SetAttributeName(v string)`

SetAttributeName sets AttributeName field to given value.

### HasAttributeName

`func (o *EquipmentApiGetEquipmentAttributesResponse) HasAttributeName() bool`

HasAttributeName returns a boolean if a field has been set.

### GetDescription

`func (o *EquipmentApiGetEquipmentAttributesResponse) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *EquipmentApiGetEquipmentAttributesResponse) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *EquipmentApiGetEquipmentAttributesResponse) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *EquipmentApiGetEquipmentAttributesResponse) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetUnit

`func (o *EquipmentApiGetEquipmentAttributesResponse) GetUnit() string`

GetUnit returns the Unit field if non-nil, zero value otherwise.

### GetUnitOk

`func (o *EquipmentApiGetEquipmentAttributesResponse) GetUnitOk() (*string, bool)`

GetUnitOk returns a tuple with the Unit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnit

`func (o *EquipmentApiGetEquipmentAttributesResponse) SetUnit(v string)`

SetUnit sets Unit field to given value.

### HasUnit

`func (o *EquipmentApiGetEquipmentAttributesResponse) HasUnit() bool`

HasUnit returns a boolean if a field has been set.

### GetUseValues

`func (o *EquipmentApiGetEquipmentAttributesResponse) GetUseValues() bool`

GetUseValues returns the UseValues field if non-nil, zero value otherwise.

### GetUseValuesOk

`func (o *EquipmentApiGetEquipmentAttributesResponse) GetUseValuesOk() (*bool, bool)`

GetUseValuesOk returns a tuple with the UseValues field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUseValues

`func (o *EquipmentApiGetEquipmentAttributesResponse) SetUseValues(v bool)`

SetUseValues sets UseValues field to given value.

### HasUseValues

`func (o *EquipmentApiGetEquipmentAttributesResponse) HasUseValues() bool`

HasUseValues returns a boolean if a field has been set.

### GetTypeAttribute

`func (o *EquipmentApiGetEquipmentAttributesResponse) GetTypeAttribute() bool`

GetTypeAttribute returns the TypeAttribute field if non-nil, zero value otherwise.

### GetTypeAttributeOk

`func (o *EquipmentApiGetEquipmentAttributesResponse) GetTypeAttributeOk() (*bool, bool)`

GetTypeAttributeOk returns a tuple with the TypeAttribute field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTypeAttribute

`func (o *EquipmentApiGetEquipmentAttributesResponse) SetTypeAttribute(v bool)`

SetTypeAttribute sets TypeAttribute field to given value.

### HasTypeAttribute

`func (o *EquipmentApiGetEquipmentAttributesResponse) HasTypeAttribute() bool`

HasTypeAttribute returns a boolean if a field has been set.

### GetGroupAttribute

`func (o *EquipmentApiGetEquipmentAttributesResponse) GetGroupAttribute() bool`

GetGroupAttribute returns the GroupAttribute field if non-nil, zero value otherwise.

### GetGroupAttributeOk

`func (o *EquipmentApiGetEquipmentAttributesResponse) GetGroupAttributeOk() (*bool, bool)`

GetGroupAttributeOk returns a tuple with the GroupAttribute field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroupAttribute

`func (o *EquipmentApiGetEquipmentAttributesResponse) SetGroupAttribute(v bool)`

SetGroupAttribute sets GroupAttribute field to given value.

### HasGroupAttribute

`func (o *EquipmentApiGetEquipmentAttributesResponse) HasGroupAttribute() bool`

HasGroupAttribute returns a boolean if a field has been set.

### GetCategoryAttribute

`func (o *EquipmentApiGetEquipmentAttributesResponse) GetCategoryAttribute() bool`

GetCategoryAttribute returns the CategoryAttribute field if non-nil, zero value otherwise.

### GetCategoryAttributeOk

`func (o *EquipmentApiGetEquipmentAttributesResponse) GetCategoryAttributeOk() (*bool, bool)`

GetCategoryAttributeOk returns a tuple with the CategoryAttribute field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategoryAttribute

`func (o *EquipmentApiGetEquipmentAttributesResponse) SetCategoryAttribute(v bool)`

SetCategoryAttribute sets CategoryAttribute field to given value.

### HasCategoryAttribute

`func (o *EquipmentApiGetEquipmentAttributesResponse) HasCategoryAttribute() bool`

HasCategoryAttribute returns a boolean if a field has been set.

### GetSmartAttribute

`func (o *EquipmentApiGetEquipmentAttributesResponse) GetSmartAttribute() bool`

GetSmartAttribute returns the SmartAttribute field if non-nil, zero value otherwise.

### GetSmartAttributeOk

`func (o *EquipmentApiGetEquipmentAttributesResponse) GetSmartAttributeOk() (*bool, bool)`

GetSmartAttributeOk returns a tuple with the SmartAttribute field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSmartAttribute

`func (o *EquipmentApiGetEquipmentAttributesResponse) SetSmartAttribute(v bool)`

SetSmartAttribute sets SmartAttribute field to given value.

### HasSmartAttribute

`func (o *EquipmentApiGetEquipmentAttributesResponse) HasSmartAttribute() bool`

HasSmartAttribute returns a boolean if a field has been set.

### GetActive

`func (o *EquipmentApiGetEquipmentAttributesResponse) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *EquipmentApiGetEquipmentAttributesResponse) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *EquipmentApiGetEquipmentAttributesResponse) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *EquipmentApiGetEquipmentAttributesResponse) HasActive() bool`

HasActive returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


