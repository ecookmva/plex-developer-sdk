# OperatingParametersApiGetOperatingParameterByIDResponse

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

### NewOperatingParametersApiGetOperatingParameterByIDResponse

`func NewOperatingParametersApiGetOperatingParameterByIDResponse() *OperatingParametersApiGetOperatingParameterByIDResponse`

NewOperatingParametersApiGetOperatingParameterByIDResponse instantiates a new OperatingParametersApiGetOperatingParameterByIDResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperatingParametersApiGetOperatingParameterByIDResponseWithDefaults

`func NewOperatingParametersApiGetOperatingParameterByIDResponseWithDefaults() *OperatingParametersApiGetOperatingParameterByIDResponse`

NewOperatingParametersApiGetOperatingParameterByIDResponseWithDefaults instantiates a new OperatingParametersApiGetOperatingParameterByIDResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *OperatingParametersApiGetOperatingParameterByIDResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *OperatingParametersApiGetOperatingParameterByIDResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *OperatingParametersApiGetOperatingParameterByIDResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *OperatingParametersApiGetOperatingParameterByIDResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetActive

`func (o *OperatingParametersApiGetOperatingParameterByIDResponse) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *OperatingParametersApiGetOperatingParameterByIDResponse) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *OperatingParametersApiGetOperatingParameterByIDResponse) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *OperatingParametersApiGetOperatingParameterByIDResponse) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetCode

`func (o *OperatingParametersApiGetOperatingParameterByIDResponse) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *OperatingParametersApiGetOperatingParameterByIDResponse) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *OperatingParametersApiGetOperatingParameterByIDResponse) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *OperatingParametersApiGetOperatingParameterByIDResponse) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetDescription

`func (o *OperatingParametersApiGetOperatingParameterByIDResponse) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *OperatingParametersApiGetOperatingParameterByIDResponse) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *OperatingParametersApiGetOperatingParameterByIDResponse) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *OperatingParametersApiGetOperatingParameterByIDResponse) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetUnit

`func (o *OperatingParametersApiGetOperatingParameterByIDResponse) GetUnit() string`

GetUnit returns the Unit field if non-nil, zero value otherwise.

### GetUnitOk

`func (o *OperatingParametersApiGetOperatingParameterByIDResponse) GetUnitOk() (*string, bool)`

GetUnitOk returns a tuple with the Unit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnit

`func (o *OperatingParametersApiGetOperatingParameterByIDResponse) SetUnit(v string)`

SetUnit sets Unit field to given value.

### HasUnit

`func (o *OperatingParametersApiGetOperatingParameterByIDResponse) HasUnit() bool`

HasUnit returns a boolean if a field has been set.

### GetDefaultTextValue

`func (o *OperatingParametersApiGetOperatingParameterByIDResponse) GetDefaultTextValue() string`

GetDefaultTextValue returns the DefaultTextValue field if non-nil, zero value otherwise.

### GetDefaultTextValueOk

`func (o *OperatingParametersApiGetOperatingParameterByIDResponse) GetDefaultTextValueOk() (*string, bool)`

GetDefaultTextValueOk returns a tuple with the DefaultTextValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultTextValue

`func (o *OperatingParametersApiGetOperatingParameterByIDResponse) SetDefaultTextValue(v string)`

SetDefaultTextValue sets DefaultTextValue field to given value.

### HasDefaultTextValue

`func (o *OperatingParametersApiGetOperatingParameterByIDResponse) HasDefaultTextValue() bool`

HasDefaultTextValue returns a boolean if a field has been set.

### GetDefaultNumericValue

`func (o *OperatingParametersApiGetOperatingParameterByIDResponse) GetDefaultNumericValue() float64`

GetDefaultNumericValue returns the DefaultNumericValue field if non-nil, zero value otherwise.

### GetDefaultNumericValueOk

`func (o *OperatingParametersApiGetOperatingParameterByIDResponse) GetDefaultNumericValueOk() (*float64, bool)`

GetDefaultNumericValueOk returns a tuple with the DefaultNumericValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultNumericValue

`func (o *OperatingParametersApiGetOperatingParameterByIDResponse) SetDefaultNumericValue(v float64)`

SetDefaultNumericValue sets DefaultNumericValue field to given value.

### HasDefaultNumericValue

`func (o *OperatingParametersApiGetOperatingParameterByIDResponse) HasDefaultNumericValue() bool`

HasDefaultNumericValue returns a boolean if a field has been set.

### GetDefaultNumericPrecision

`func (o *OperatingParametersApiGetOperatingParameterByIDResponse) GetDefaultNumericPrecision() int32`

GetDefaultNumericPrecision returns the DefaultNumericPrecision field if non-nil, zero value otherwise.

### GetDefaultNumericPrecisionOk

`func (o *OperatingParametersApiGetOperatingParameterByIDResponse) GetDefaultNumericPrecisionOk() (*int32, bool)`

GetDefaultNumericPrecisionOk returns a tuple with the DefaultNumericPrecision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultNumericPrecision

`func (o *OperatingParametersApiGetOperatingParameterByIDResponse) SetDefaultNumericPrecision(v int32)`

SetDefaultNumericPrecision sets DefaultNumericPrecision field to given value.

### HasDefaultNumericPrecision

`func (o *OperatingParametersApiGetOperatingParameterByIDResponse) HasDefaultNumericPrecision() bool`

HasDefaultNumericPrecision returns a boolean if a field has been set.

### GetDefaultListValue

`func (o *OperatingParametersApiGetOperatingParameterByIDResponse) GetDefaultListValue() []DefaultListValueItem`

GetDefaultListValue returns the DefaultListValue field if non-nil, zero value otherwise.

### GetDefaultListValueOk

`func (o *OperatingParametersApiGetOperatingParameterByIDResponse) GetDefaultListValueOk() (*[]DefaultListValueItem, bool)`

GetDefaultListValueOk returns a tuple with the DefaultListValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultListValue

`func (o *OperatingParametersApiGetOperatingParameterByIDResponse) SetDefaultListValue(v []DefaultListValueItem)`

SetDefaultListValue sets DefaultListValue field to given value.

### HasDefaultListValue

`func (o *OperatingParametersApiGetOperatingParameterByIDResponse) HasDefaultListValue() bool`

HasDefaultListValue returns a boolean if a field has been set.

### GetDisplayType

`func (o *OperatingParametersApiGetOperatingParameterByIDResponse) GetDisplayType() DisplayType`

GetDisplayType returns the DisplayType field if non-nil, zero value otherwise.

### GetDisplayTypeOk

`func (o *OperatingParametersApiGetOperatingParameterByIDResponse) GetDisplayTypeOk() (*DisplayType, bool)`

GetDisplayTypeOk returns a tuple with the DisplayType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplayType

`func (o *OperatingParametersApiGetOperatingParameterByIDResponse) SetDisplayType(v DisplayType)`

SetDisplayType sets DisplayType field to given value.

### HasDisplayType

`func (o *OperatingParametersApiGetOperatingParameterByIDResponse) HasDisplayType() bool`

HasDisplayType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


