# AvailableConstraints

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Unique** | Pointer to **bool** |  | [optional] 
**Required** | Pointer to **bool** |  | [optional] 
**MinimumValue** | Pointer to **bool** |  | [optional] 
**MinimumValueInclusive** | Pointer to **bool** |  | [optional] 
**MaximumValue** | Pointer to **bool** |  | [optional] 
**MaximumValueInclusive** | Pointer to **bool** |  | [optional] 
**AllowedValues** | Pointer to **bool** |  | [optional] 
**MaximumLength** | Pointer to **bool** |  | [optional] 

## Methods

### NewAvailableConstraints

`func NewAvailableConstraints() *AvailableConstraints`

NewAvailableConstraints instantiates a new AvailableConstraints object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAvailableConstraintsWithDefaults

`func NewAvailableConstraintsWithDefaults() *AvailableConstraints`

NewAvailableConstraintsWithDefaults instantiates a new AvailableConstraints object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUnique

`func (o *AvailableConstraints) GetUnique() bool`

GetUnique returns the Unique field if non-nil, zero value otherwise.

### GetUniqueOk

`func (o *AvailableConstraints) GetUniqueOk() (*bool, bool)`

GetUniqueOk returns a tuple with the Unique field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnique

`func (o *AvailableConstraints) SetUnique(v bool)`

SetUnique sets Unique field to given value.

### HasUnique

`func (o *AvailableConstraints) HasUnique() bool`

HasUnique returns a boolean if a field has been set.

### GetRequired

`func (o *AvailableConstraints) GetRequired() bool`

GetRequired returns the Required field if non-nil, zero value otherwise.

### GetRequiredOk

`func (o *AvailableConstraints) GetRequiredOk() (*bool, bool)`

GetRequiredOk returns a tuple with the Required field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequired

`func (o *AvailableConstraints) SetRequired(v bool)`

SetRequired sets Required field to given value.

### HasRequired

`func (o *AvailableConstraints) HasRequired() bool`

HasRequired returns a boolean if a field has been set.

### GetMinimumValue

`func (o *AvailableConstraints) GetMinimumValue() bool`

GetMinimumValue returns the MinimumValue field if non-nil, zero value otherwise.

### GetMinimumValueOk

`func (o *AvailableConstraints) GetMinimumValueOk() (*bool, bool)`

GetMinimumValueOk returns a tuple with the MinimumValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinimumValue

`func (o *AvailableConstraints) SetMinimumValue(v bool)`

SetMinimumValue sets MinimumValue field to given value.

### HasMinimumValue

`func (o *AvailableConstraints) HasMinimumValue() bool`

HasMinimumValue returns a boolean if a field has been set.

### GetMinimumValueInclusive

`func (o *AvailableConstraints) GetMinimumValueInclusive() bool`

GetMinimumValueInclusive returns the MinimumValueInclusive field if non-nil, zero value otherwise.

### GetMinimumValueInclusiveOk

`func (o *AvailableConstraints) GetMinimumValueInclusiveOk() (*bool, bool)`

GetMinimumValueInclusiveOk returns a tuple with the MinimumValueInclusive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinimumValueInclusive

`func (o *AvailableConstraints) SetMinimumValueInclusive(v bool)`

SetMinimumValueInclusive sets MinimumValueInclusive field to given value.

### HasMinimumValueInclusive

`func (o *AvailableConstraints) HasMinimumValueInclusive() bool`

HasMinimumValueInclusive returns a boolean if a field has been set.

### GetMaximumValue

`func (o *AvailableConstraints) GetMaximumValue() bool`

GetMaximumValue returns the MaximumValue field if non-nil, zero value otherwise.

### GetMaximumValueOk

`func (o *AvailableConstraints) GetMaximumValueOk() (*bool, bool)`

GetMaximumValueOk returns a tuple with the MaximumValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaximumValue

`func (o *AvailableConstraints) SetMaximumValue(v bool)`

SetMaximumValue sets MaximumValue field to given value.

### HasMaximumValue

`func (o *AvailableConstraints) HasMaximumValue() bool`

HasMaximumValue returns a boolean if a field has been set.

### GetMaximumValueInclusive

`func (o *AvailableConstraints) GetMaximumValueInclusive() bool`

GetMaximumValueInclusive returns the MaximumValueInclusive field if non-nil, zero value otherwise.

### GetMaximumValueInclusiveOk

`func (o *AvailableConstraints) GetMaximumValueInclusiveOk() (*bool, bool)`

GetMaximumValueInclusiveOk returns a tuple with the MaximumValueInclusive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaximumValueInclusive

`func (o *AvailableConstraints) SetMaximumValueInclusive(v bool)`

SetMaximumValueInclusive sets MaximumValueInclusive field to given value.

### HasMaximumValueInclusive

`func (o *AvailableConstraints) HasMaximumValueInclusive() bool`

HasMaximumValueInclusive returns a boolean if a field has been set.

### GetAllowedValues

`func (o *AvailableConstraints) GetAllowedValues() bool`

GetAllowedValues returns the AllowedValues field if non-nil, zero value otherwise.

### GetAllowedValuesOk

`func (o *AvailableConstraints) GetAllowedValuesOk() (*bool, bool)`

GetAllowedValuesOk returns a tuple with the AllowedValues field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowedValues

`func (o *AvailableConstraints) SetAllowedValues(v bool)`

SetAllowedValues sets AllowedValues field to given value.

### HasAllowedValues

`func (o *AvailableConstraints) HasAllowedValues() bool`

HasAllowedValues returns a boolean if a field has been set.

### GetMaximumLength

`func (o *AvailableConstraints) GetMaximumLength() bool`

GetMaximumLength returns the MaximumLength field if non-nil, zero value otherwise.

### GetMaximumLengthOk

`func (o *AvailableConstraints) GetMaximumLengthOk() (*bool, bool)`

GetMaximumLengthOk returns a tuple with the MaximumLength field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaximumLength

`func (o *AvailableConstraints) SetMaximumLength(v bool)`

SetMaximumLength sets MaximumLength field to given value.

### HasMaximumLength

`func (o *AvailableConstraints) HasMaximumLength() bool`

HasMaximumLength returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


