# OperatingParametersApiListOperatingParametersItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | The unique identifier of the Operating Parameter. | [optional] 
**Active** | Pointer to **bool** | The active status of the Operating Parameter. | [optional] 
**Code** | Pointer to **string** | The code or name of the Operating Parameter. | [optional] 
**Description** | Pointer to **string** | The description of the Operating Parameter. | [optional] 
**Unit** | Pointer to **string** | The unit of measurement for the Operating Parameter. | [optional] 
**DefaultTextValue** | Pointer to **string** | The default text value of the Operating Parameter, if applicable. | [optional] 
**DefaultNumericValue** | Pointer to **float64** | The default numeric value of the Operating Parameter, if applicable. | [optional] 
**DefaultNumericPrecision** | Pointer to **int32** | The precision of the default numeric value, if applicable. | [optional] 
**DefaultListValue** | Pointer to [**[]DefaultListValueItem**](DefaultListValueItem.md) | The default list values of the Operating Parameter, if applicable. | [optional] 
**DisplayType** | Pointer to [**DisplayType**](DisplayType.md) |  | [optional] 

## Methods

### NewOperatingParametersApiListOperatingParametersItem

`func NewOperatingParametersApiListOperatingParametersItem() *OperatingParametersApiListOperatingParametersItem`

NewOperatingParametersApiListOperatingParametersItem instantiates a new OperatingParametersApiListOperatingParametersItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperatingParametersApiListOperatingParametersItemWithDefaults

`func NewOperatingParametersApiListOperatingParametersItemWithDefaults() *OperatingParametersApiListOperatingParametersItem`

NewOperatingParametersApiListOperatingParametersItemWithDefaults instantiates a new OperatingParametersApiListOperatingParametersItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *OperatingParametersApiListOperatingParametersItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *OperatingParametersApiListOperatingParametersItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *OperatingParametersApiListOperatingParametersItem) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *OperatingParametersApiListOperatingParametersItem) HasId() bool`

HasId returns a boolean if a field has been set.

### GetActive

`func (o *OperatingParametersApiListOperatingParametersItem) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *OperatingParametersApiListOperatingParametersItem) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *OperatingParametersApiListOperatingParametersItem) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *OperatingParametersApiListOperatingParametersItem) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetCode

`func (o *OperatingParametersApiListOperatingParametersItem) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *OperatingParametersApiListOperatingParametersItem) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *OperatingParametersApiListOperatingParametersItem) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *OperatingParametersApiListOperatingParametersItem) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetDescription

`func (o *OperatingParametersApiListOperatingParametersItem) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *OperatingParametersApiListOperatingParametersItem) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *OperatingParametersApiListOperatingParametersItem) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *OperatingParametersApiListOperatingParametersItem) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetUnit

`func (o *OperatingParametersApiListOperatingParametersItem) GetUnit() string`

GetUnit returns the Unit field if non-nil, zero value otherwise.

### GetUnitOk

`func (o *OperatingParametersApiListOperatingParametersItem) GetUnitOk() (*string, bool)`

GetUnitOk returns a tuple with the Unit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnit

`func (o *OperatingParametersApiListOperatingParametersItem) SetUnit(v string)`

SetUnit sets Unit field to given value.

### HasUnit

`func (o *OperatingParametersApiListOperatingParametersItem) HasUnit() bool`

HasUnit returns a boolean if a field has been set.

### GetDefaultTextValue

`func (o *OperatingParametersApiListOperatingParametersItem) GetDefaultTextValue() string`

GetDefaultTextValue returns the DefaultTextValue field if non-nil, zero value otherwise.

### GetDefaultTextValueOk

`func (o *OperatingParametersApiListOperatingParametersItem) GetDefaultTextValueOk() (*string, bool)`

GetDefaultTextValueOk returns a tuple with the DefaultTextValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultTextValue

`func (o *OperatingParametersApiListOperatingParametersItem) SetDefaultTextValue(v string)`

SetDefaultTextValue sets DefaultTextValue field to given value.

### HasDefaultTextValue

`func (o *OperatingParametersApiListOperatingParametersItem) HasDefaultTextValue() bool`

HasDefaultTextValue returns a boolean if a field has been set.

### GetDefaultNumericValue

`func (o *OperatingParametersApiListOperatingParametersItem) GetDefaultNumericValue() float64`

GetDefaultNumericValue returns the DefaultNumericValue field if non-nil, zero value otherwise.

### GetDefaultNumericValueOk

`func (o *OperatingParametersApiListOperatingParametersItem) GetDefaultNumericValueOk() (*float64, bool)`

GetDefaultNumericValueOk returns a tuple with the DefaultNumericValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultNumericValue

`func (o *OperatingParametersApiListOperatingParametersItem) SetDefaultNumericValue(v float64)`

SetDefaultNumericValue sets DefaultNumericValue field to given value.

### HasDefaultNumericValue

`func (o *OperatingParametersApiListOperatingParametersItem) HasDefaultNumericValue() bool`

HasDefaultNumericValue returns a boolean if a field has been set.

### GetDefaultNumericPrecision

`func (o *OperatingParametersApiListOperatingParametersItem) GetDefaultNumericPrecision() int32`

GetDefaultNumericPrecision returns the DefaultNumericPrecision field if non-nil, zero value otherwise.

### GetDefaultNumericPrecisionOk

`func (o *OperatingParametersApiListOperatingParametersItem) GetDefaultNumericPrecisionOk() (*int32, bool)`

GetDefaultNumericPrecisionOk returns a tuple with the DefaultNumericPrecision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultNumericPrecision

`func (o *OperatingParametersApiListOperatingParametersItem) SetDefaultNumericPrecision(v int32)`

SetDefaultNumericPrecision sets DefaultNumericPrecision field to given value.

### HasDefaultNumericPrecision

`func (o *OperatingParametersApiListOperatingParametersItem) HasDefaultNumericPrecision() bool`

HasDefaultNumericPrecision returns a boolean if a field has been set.

### GetDefaultListValue

`func (o *OperatingParametersApiListOperatingParametersItem) GetDefaultListValue() []DefaultListValueItem`

GetDefaultListValue returns the DefaultListValue field if non-nil, zero value otherwise.

### GetDefaultListValueOk

`func (o *OperatingParametersApiListOperatingParametersItem) GetDefaultListValueOk() (*[]DefaultListValueItem, bool)`

GetDefaultListValueOk returns a tuple with the DefaultListValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultListValue

`func (o *OperatingParametersApiListOperatingParametersItem) SetDefaultListValue(v []DefaultListValueItem)`

SetDefaultListValue sets DefaultListValue field to given value.

### HasDefaultListValue

`func (o *OperatingParametersApiListOperatingParametersItem) HasDefaultListValue() bool`

HasDefaultListValue returns a boolean if a field has been set.

### GetDisplayType

`func (o *OperatingParametersApiListOperatingParametersItem) GetDisplayType() DisplayType`

GetDisplayType returns the DisplayType field if non-nil, zero value otherwise.

### GetDisplayTypeOk

`func (o *OperatingParametersApiListOperatingParametersItem) GetDisplayTypeOk() (*DisplayType, bool)`

GetDisplayTypeOk returns a tuple with the DisplayType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplayType

`func (o *OperatingParametersApiListOperatingParametersItem) SetDisplayType(v DisplayType)`

SetDisplayType sets DisplayType field to given value.

### HasDisplayType

`func (o *OperatingParametersApiListOperatingParametersItem) HasDisplayType() bool`

HasDisplayType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


