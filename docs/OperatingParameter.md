# OperatingParameter

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** |  | [optional] 
**Active** | Pointer to **bool** |  | [optional] 
**Code** | Pointer to **string** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**Unit** | Pointer to **string** |  | [optional] 
**DefaultTextValue** | Pointer to **string** |  | [optional] 
**DefaultNumericValue** | Pointer to **float64** |  | [optional] 
**DefaultNumericPrecision** | Pointer to **int32** |  | [optional] 
**DefaultListValue** | Pointer to **[]interface{}** |  | [optional] 
**DisplayType** | Pointer to **map[string]interface{}** |  | [optional] 

## Methods

### NewOperatingParameter

`func NewOperatingParameter() *OperatingParameter`

NewOperatingParameter instantiates a new OperatingParameter object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperatingParameterWithDefaults

`func NewOperatingParameterWithDefaults() *OperatingParameter`

NewOperatingParameterWithDefaults instantiates a new OperatingParameter object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *OperatingParameter) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *OperatingParameter) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *OperatingParameter) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *OperatingParameter) HasId() bool`

HasId returns a boolean if a field has been set.

### GetActive

`func (o *OperatingParameter) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *OperatingParameter) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *OperatingParameter) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *OperatingParameter) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetCode

`func (o *OperatingParameter) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *OperatingParameter) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *OperatingParameter) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *OperatingParameter) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetDescription

`func (o *OperatingParameter) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *OperatingParameter) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *OperatingParameter) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *OperatingParameter) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetUnit

`func (o *OperatingParameter) GetUnit() string`

GetUnit returns the Unit field if non-nil, zero value otherwise.

### GetUnitOk

`func (o *OperatingParameter) GetUnitOk() (*string, bool)`

GetUnitOk returns a tuple with the Unit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnit

`func (o *OperatingParameter) SetUnit(v string)`

SetUnit sets Unit field to given value.

### HasUnit

`func (o *OperatingParameter) HasUnit() bool`

HasUnit returns a boolean if a field has been set.

### GetDefaultTextValue

`func (o *OperatingParameter) GetDefaultTextValue() string`

GetDefaultTextValue returns the DefaultTextValue field if non-nil, zero value otherwise.

### GetDefaultTextValueOk

`func (o *OperatingParameter) GetDefaultTextValueOk() (*string, bool)`

GetDefaultTextValueOk returns a tuple with the DefaultTextValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultTextValue

`func (o *OperatingParameter) SetDefaultTextValue(v string)`

SetDefaultTextValue sets DefaultTextValue field to given value.

### HasDefaultTextValue

`func (o *OperatingParameter) HasDefaultTextValue() bool`

HasDefaultTextValue returns a boolean if a field has been set.

### GetDefaultNumericValue

`func (o *OperatingParameter) GetDefaultNumericValue() float64`

GetDefaultNumericValue returns the DefaultNumericValue field if non-nil, zero value otherwise.

### GetDefaultNumericValueOk

`func (o *OperatingParameter) GetDefaultNumericValueOk() (*float64, bool)`

GetDefaultNumericValueOk returns a tuple with the DefaultNumericValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultNumericValue

`func (o *OperatingParameter) SetDefaultNumericValue(v float64)`

SetDefaultNumericValue sets DefaultNumericValue field to given value.

### HasDefaultNumericValue

`func (o *OperatingParameter) HasDefaultNumericValue() bool`

HasDefaultNumericValue returns a boolean if a field has been set.

### GetDefaultNumericPrecision

`func (o *OperatingParameter) GetDefaultNumericPrecision() int32`

GetDefaultNumericPrecision returns the DefaultNumericPrecision field if non-nil, zero value otherwise.

### GetDefaultNumericPrecisionOk

`func (o *OperatingParameter) GetDefaultNumericPrecisionOk() (*int32, bool)`

GetDefaultNumericPrecisionOk returns a tuple with the DefaultNumericPrecision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultNumericPrecision

`func (o *OperatingParameter) SetDefaultNumericPrecision(v int32)`

SetDefaultNumericPrecision sets DefaultNumericPrecision field to given value.

### HasDefaultNumericPrecision

`func (o *OperatingParameter) HasDefaultNumericPrecision() bool`

HasDefaultNumericPrecision returns a boolean if a field has been set.

### GetDefaultListValue

`func (o *OperatingParameter) GetDefaultListValue() []interface{}`

GetDefaultListValue returns the DefaultListValue field if non-nil, zero value otherwise.

### GetDefaultListValueOk

`func (o *OperatingParameter) GetDefaultListValueOk() (*[]interface{}, bool)`

GetDefaultListValueOk returns a tuple with the DefaultListValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultListValue

`func (o *OperatingParameter) SetDefaultListValue(v []interface{})`

SetDefaultListValue sets DefaultListValue field to given value.

### HasDefaultListValue

`func (o *OperatingParameter) HasDefaultListValue() bool`

HasDefaultListValue returns a boolean if a field has been set.

### GetDisplayType

`func (o *OperatingParameter) GetDisplayType() map[string]interface{}`

GetDisplayType returns the DisplayType field if non-nil, zero value otherwise.

### GetDisplayTypeOk

`func (o *OperatingParameter) GetDisplayTypeOk() (*map[string]interface{}, bool)`

GetDisplayTypeOk returns a tuple with the DisplayType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplayType

`func (o *OperatingParameter) SetDisplayType(v map[string]interface{})`

SetDisplayType sets DisplayType field to given value.

### HasDisplayType

`func (o *OperatingParameter) HasDisplayType() bool`

HasDisplayType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


