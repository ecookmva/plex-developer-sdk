# ToleranceType1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** |  | [optional] 
**Attribute** | Pointer to **bool** |  | [optional] 
**Target** | Pointer to **float64** |  | [optional] 
**TargetPlus** | Pointer to **float64** |  | [optional] 
**TargetMinus** | Pointer to **float64** |  | [optional] 
**DecimalPrecision** | Pointer to **int32** |  | [optional] 
**Unit** | Pointer to **string** |  | [optional] 
**OneSidedMinimum** | Pointer to **float64** |  | [optional] 
**OneSidedMaximum** | Pointer to **float64** |  | [optional] 
**MeasurementText** | Pointer to **string** |  | [optional] 
**CompareValue** | Pointer to **string** |  | [optional] 
**ReferenceDisplayPopup** | Pointer to **bool** |  | [optional] 
**ReferencePopupMessage** | Pointer to **string** |  | [optional] 

## Methods

### NewToleranceType1

`func NewToleranceType1() *ToleranceType1`

NewToleranceType1 instantiates a new ToleranceType1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewToleranceType1WithDefaults

`func NewToleranceType1WithDefaults() *ToleranceType1`

NewToleranceType1WithDefaults instantiates a new ToleranceType1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *ToleranceType1) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ToleranceType1) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ToleranceType1) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ToleranceType1) HasName() bool`

HasName returns a boolean if a field has been set.

### GetAttribute

`func (o *ToleranceType1) GetAttribute() bool`

GetAttribute returns the Attribute field if non-nil, zero value otherwise.

### GetAttributeOk

`func (o *ToleranceType1) GetAttributeOk() (*bool, bool)`

GetAttributeOk returns a tuple with the Attribute field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttribute

`func (o *ToleranceType1) SetAttribute(v bool)`

SetAttribute sets Attribute field to given value.

### HasAttribute

`func (o *ToleranceType1) HasAttribute() bool`

HasAttribute returns a boolean if a field has been set.

### GetTarget

`func (o *ToleranceType1) GetTarget() float64`

GetTarget returns the Target field if non-nil, zero value otherwise.

### GetTargetOk

`func (o *ToleranceType1) GetTargetOk() (*float64, bool)`

GetTargetOk returns a tuple with the Target field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTarget

`func (o *ToleranceType1) SetTarget(v float64)`

SetTarget sets Target field to given value.

### HasTarget

`func (o *ToleranceType1) HasTarget() bool`

HasTarget returns a boolean if a field has been set.

### GetTargetPlus

`func (o *ToleranceType1) GetTargetPlus() float64`

GetTargetPlus returns the TargetPlus field if non-nil, zero value otherwise.

### GetTargetPlusOk

`func (o *ToleranceType1) GetTargetPlusOk() (*float64, bool)`

GetTargetPlusOk returns a tuple with the TargetPlus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetPlus

`func (o *ToleranceType1) SetTargetPlus(v float64)`

SetTargetPlus sets TargetPlus field to given value.

### HasTargetPlus

`func (o *ToleranceType1) HasTargetPlus() bool`

HasTargetPlus returns a boolean if a field has been set.

### GetTargetMinus

`func (o *ToleranceType1) GetTargetMinus() float64`

GetTargetMinus returns the TargetMinus field if non-nil, zero value otherwise.

### GetTargetMinusOk

`func (o *ToleranceType1) GetTargetMinusOk() (*float64, bool)`

GetTargetMinusOk returns a tuple with the TargetMinus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetMinus

`func (o *ToleranceType1) SetTargetMinus(v float64)`

SetTargetMinus sets TargetMinus field to given value.

### HasTargetMinus

`func (o *ToleranceType1) HasTargetMinus() bool`

HasTargetMinus returns a boolean if a field has been set.

### GetDecimalPrecision

`func (o *ToleranceType1) GetDecimalPrecision() int32`

GetDecimalPrecision returns the DecimalPrecision field if non-nil, zero value otherwise.

### GetDecimalPrecisionOk

`func (o *ToleranceType1) GetDecimalPrecisionOk() (*int32, bool)`

GetDecimalPrecisionOk returns a tuple with the DecimalPrecision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDecimalPrecision

`func (o *ToleranceType1) SetDecimalPrecision(v int32)`

SetDecimalPrecision sets DecimalPrecision field to given value.

### HasDecimalPrecision

`func (o *ToleranceType1) HasDecimalPrecision() bool`

HasDecimalPrecision returns a boolean if a field has been set.

### GetUnit

`func (o *ToleranceType1) GetUnit() string`

GetUnit returns the Unit field if non-nil, zero value otherwise.

### GetUnitOk

`func (o *ToleranceType1) GetUnitOk() (*string, bool)`

GetUnitOk returns a tuple with the Unit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnit

`func (o *ToleranceType1) SetUnit(v string)`

SetUnit sets Unit field to given value.

### HasUnit

`func (o *ToleranceType1) HasUnit() bool`

HasUnit returns a boolean if a field has been set.

### GetOneSidedMinimum

`func (o *ToleranceType1) GetOneSidedMinimum() float64`

GetOneSidedMinimum returns the OneSidedMinimum field if non-nil, zero value otherwise.

### GetOneSidedMinimumOk

`func (o *ToleranceType1) GetOneSidedMinimumOk() (*float64, bool)`

GetOneSidedMinimumOk returns a tuple with the OneSidedMinimum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOneSidedMinimum

`func (o *ToleranceType1) SetOneSidedMinimum(v float64)`

SetOneSidedMinimum sets OneSidedMinimum field to given value.

### HasOneSidedMinimum

`func (o *ToleranceType1) HasOneSidedMinimum() bool`

HasOneSidedMinimum returns a boolean if a field has been set.

### GetOneSidedMaximum

`func (o *ToleranceType1) GetOneSidedMaximum() float64`

GetOneSidedMaximum returns the OneSidedMaximum field if non-nil, zero value otherwise.

### GetOneSidedMaximumOk

`func (o *ToleranceType1) GetOneSidedMaximumOk() (*float64, bool)`

GetOneSidedMaximumOk returns a tuple with the OneSidedMaximum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOneSidedMaximum

`func (o *ToleranceType1) SetOneSidedMaximum(v float64)`

SetOneSidedMaximum sets OneSidedMaximum field to given value.

### HasOneSidedMaximum

`func (o *ToleranceType1) HasOneSidedMaximum() bool`

HasOneSidedMaximum returns a boolean if a field has been set.

### GetMeasurementText

`func (o *ToleranceType1) GetMeasurementText() string`

GetMeasurementText returns the MeasurementText field if non-nil, zero value otherwise.

### GetMeasurementTextOk

`func (o *ToleranceType1) GetMeasurementTextOk() (*string, bool)`

GetMeasurementTextOk returns a tuple with the MeasurementText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeasurementText

`func (o *ToleranceType1) SetMeasurementText(v string)`

SetMeasurementText sets MeasurementText field to given value.

### HasMeasurementText

`func (o *ToleranceType1) HasMeasurementText() bool`

HasMeasurementText returns a boolean if a field has been set.

### GetCompareValue

`func (o *ToleranceType1) GetCompareValue() string`

GetCompareValue returns the CompareValue field if non-nil, zero value otherwise.

### GetCompareValueOk

`func (o *ToleranceType1) GetCompareValueOk() (*string, bool)`

GetCompareValueOk returns a tuple with the CompareValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompareValue

`func (o *ToleranceType1) SetCompareValue(v string)`

SetCompareValue sets CompareValue field to given value.

### HasCompareValue

`func (o *ToleranceType1) HasCompareValue() bool`

HasCompareValue returns a boolean if a field has been set.

### GetReferenceDisplayPopup

`func (o *ToleranceType1) GetReferenceDisplayPopup() bool`

GetReferenceDisplayPopup returns the ReferenceDisplayPopup field if non-nil, zero value otherwise.

### GetReferenceDisplayPopupOk

`func (o *ToleranceType1) GetReferenceDisplayPopupOk() (*bool, bool)`

GetReferenceDisplayPopupOk returns a tuple with the ReferenceDisplayPopup field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferenceDisplayPopup

`func (o *ToleranceType1) SetReferenceDisplayPopup(v bool)`

SetReferenceDisplayPopup sets ReferenceDisplayPopup field to given value.

### HasReferenceDisplayPopup

`func (o *ToleranceType1) HasReferenceDisplayPopup() bool`

HasReferenceDisplayPopup returns a boolean if a field has been set.

### GetReferencePopupMessage

`func (o *ToleranceType1) GetReferencePopupMessage() string`

GetReferencePopupMessage returns the ReferencePopupMessage field if non-nil, zero value otherwise.

### GetReferencePopupMessageOk

`func (o *ToleranceType1) GetReferencePopupMessageOk() (*string, bool)`

GetReferencePopupMessageOk returns a tuple with the ReferencePopupMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferencePopupMessage

`func (o *ToleranceType1) SetReferencePopupMessage(v string)`

SetReferencePopupMessage sets ReferencePopupMessage field to given value.

### HasReferencePopupMessage

`func (o *ToleranceType1) HasReferencePopupMessage() bool`

HasReferencePopupMessage returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


