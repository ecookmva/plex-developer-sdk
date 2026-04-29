# ToleranceType

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
**BonusTolerances** | Pointer to **[]interface{}** |  | [optional] 

## Methods

### NewToleranceType

`func NewToleranceType() *ToleranceType`

NewToleranceType instantiates a new ToleranceType object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewToleranceTypeWithDefaults

`func NewToleranceTypeWithDefaults() *ToleranceType`

NewToleranceTypeWithDefaults instantiates a new ToleranceType object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *ToleranceType) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ToleranceType) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ToleranceType) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ToleranceType) HasName() bool`

HasName returns a boolean if a field has been set.

### GetAttribute

`func (o *ToleranceType) GetAttribute() bool`

GetAttribute returns the Attribute field if non-nil, zero value otherwise.

### GetAttributeOk

`func (o *ToleranceType) GetAttributeOk() (*bool, bool)`

GetAttributeOk returns a tuple with the Attribute field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttribute

`func (o *ToleranceType) SetAttribute(v bool)`

SetAttribute sets Attribute field to given value.

### HasAttribute

`func (o *ToleranceType) HasAttribute() bool`

HasAttribute returns a boolean if a field has been set.

### GetTarget

`func (o *ToleranceType) GetTarget() float64`

GetTarget returns the Target field if non-nil, zero value otherwise.

### GetTargetOk

`func (o *ToleranceType) GetTargetOk() (*float64, bool)`

GetTargetOk returns a tuple with the Target field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTarget

`func (o *ToleranceType) SetTarget(v float64)`

SetTarget sets Target field to given value.

### HasTarget

`func (o *ToleranceType) HasTarget() bool`

HasTarget returns a boolean if a field has been set.

### GetTargetPlus

`func (o *ToleranceType) GetTargetPlus() float64`

GetTargetPlus returns the TargetPlus field if non-nil, zero value otherwise.

### GetTargetPlusOk

`func (o *ToleranceType) GetTargetPlusOk() (*float64, bool)`

GetTargetPlusOk returns a tuple with the TargetPlus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetPlus

`func (o *ToleranceType) SetTargetPlus(v float64)`

SetTargetPlus sets TargetPlus field to given value.

### HasTargetPlus

`func (o *ToleranceType) HasTargetPlus() bool`

HasTargetPlus returns a boolean if a field has been set.

### GetTargetMinus

`func (o *ToleranceType) GetTargetMinus() float64`

GetTargetMinus returns the TargetMinus field if non-nil, zero value otherwise.

### GetTargetMinusOk

`func (o *ToleranceType) GetTargetMinusOk() (*float64, bool)`

GetTargetMinusOk returns a tuple with the TargetMinus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetMinus

`func (o *ToleranceType) SetTargetMinus(v float64)`

SetTargetMinus sets TargetMinus field to given value.

### HasTargetMinus

`func (o *ToleranceType) HasTargetMinus() bool`

HasTargetMinus returns a boolean if a field has been set.

### GetDecimalPrecision

`func (o *ToleranceType) GetDecimalPrecision() int32`

GetDecimalPrecision returns the DecimalPrecision field if non-nil, zero value otherwise.

### GetDecimalPrecisionOk

`func (o *ToleranceType) GetDecimalPrecisionOk() (*int32, bool)`

GetDecimalPrecisionOk returns a tuple with the DecimalPrecision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDecimalPrecision

`func (o *ToleranceType) SetDecimalPrecision(v int32)`

SetDecimalPrecision sets DecimalPrecision field to given value.

### HasDecimalPrecision

`func (o *ToleranceType) HasDecimalPrecision() bool`

HasDecimalPrecision returns a boolean if a field has been set.

### GetUnit

`func (o *ToleranceType) GetUnit() string`

GetUnit returns the Unit field if non-nil, zero value otherwise.

### GetUnitOk

`func (o *ToleranceType) GetUnitOk() (*string, bool)`

GetUnitOk returns a tuple with the Unit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnit

`func (o *ToleranceType) SetUnit(v string)`

SetUnit sets Unit field to given value.

### HasUnit

`func (o *ToleranceType) HasUnit() bool`

HasUnit returns a boolean if a field has been set.

### GetOneSidedMinimum

`func (o *ToleranceType) GetOneSidedMinimum() float64`

GetOneSidedMinimum returns the OneSidedMinimum field if non-nil, zero value otherwise.

### GetOneSidedMinimumOk

`func (o *ToleranceType) GetOneSidedMinimumOk() (*float64, bool)`

GetOneSidedMinimumOk returns a tuple with the OneSidedMinimum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOneSidedMinimum

`func (o *ToleranceType) SetOneSidedMinimum(v float64)`

SetOneSidedMinimum sets OneSidedMinimum field to given value.

### HasOneSidedMinimum

`func (o *ToleranceType) HasOneSidedMinimum() bool`

HasOneSidedMinimum returns a boolean if a field has been set.

### GetOneSidedMaximum

`func (o *ToleranceType) GetOneSidedMaximum() float64`

GetOneSidedMaximum returns the OneSidedMaximum field if non-nil, zero value otherwise.

### GetOneSidedMaximumOk

`func (o *ToleranceType) GetOneSidedMaximumOk() (*float64, bool)`

GetOneSidedMaximumOk returns a tuple with the OneSidedMaximum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOneSidedMaximum

`func (o *ToleranceType) SetOneSidedMaximum(v float64)`

SetOneSidedMaximum sets OneSidedMaximum field to given value.

### HasOneSidedMaximum

`func (o *ToleranceType) HasOneSidedMaximum() bool`

HasOneSidedMaximum returns a boolean if a field has been set.

### GetMeasurementText

`func (o *ToleranceType) GetMeasurementText() string`

GetMeasurementText returns the MeasurementText field if non-nil, zero value otherwise.

### GetMeasurementTextOk

`func (o *ToleranceType) GetMeasurementTextOk() (*string, bool)`

GetMeasurementTextOk returns a tuple with the MeasurementText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeasurementText

`func (o *ToleranceType) SetMeasurementText(v string)`

SetMeasurementText sets MeasurementText field to given value.

### HasMeasurementText

`func (o *ToleranceType) HasMeasurementText() bool`

HasMeasurementText returns a boolean if a field has been set.

### GetCompareValue

`func (o *ToleranceType) GetCompareValue() string`

GetCompareValue returns the CompareValue field if non-nil, zero value otherwise.

### GetCompareValueOk

`func (o *ToleranceType) GetCompareValueOk() (*string, bool)`

GetCompareValueOk returns a tuple with the CompareValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompareValue

`func (o *ToleranceType) SetCompareValue(v string)`

SetCompareValue sets CompareValue field to given value.

### HasCompareValue

`func (o *ToleranceType) HasCompareValue() bool`

HasCompareValue returns a boolean if a field has been set.

### GetReferenceDisplayPopup

`func (o *ToleranceType) GetReferenceDisplayPopup() bool`

GetReferenceDisplayPopup returns the ReferenceDisplayPopup field if non-nil, zero value otherwise.

### GetReferenceDisplayPopupOk

`func (o *ToleranceType) GetReferenceDisplayPopupOk() (*bool, bool)`

GetReferenceDisplayPopupOk returns a tuple with the ReferenceDisplayPopup field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferenceDisplayPopup

`func (o *ToleranceType) SetReferenceDisplayPopup(v bool)`

SetReferenceDisplayPopup sets ReferenceDisplayPopup field to given value.

### HasReferenceDisplayPopup

`func (o *ToleranceType) HasReferenceDisplayPopup() bool`

HasReferenceDisplayPopup returns a boolean if a field has been set.

### GetReferencePopupMessage

`func (o *ToleranceType) GetReferencePopupMessage() string`

GetReferencePopupMessage returns the ReferencePopupMessage field if non-nil, zero value otherwise.

### GetReferencePopupMessageOk

`func (o *ToleranceType) GetReferencePopupMessageOk() (*string, bool)`

GetReferencePopupMessageOk returns a tuple with the ReferencePopupMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferencePopupMessage

`func (o *ToleranceType) SetReferencePopupMessage(v string)`

SetReferencePopupMessage sets ReferencePopupMessage field to given value.

### HasReferencePopupMessage

`func (o *ToleranceType) HasReferencePopupMessage() bool`

HasReferencePopupMessage returns a boolean if a field has been set.

### GetBonusTolerances

`func (o *ToleranceType) GetBonusTolerances() []interface{}`

GetBonusTolerances returns the BonusTolerances field if non-nil, zero value otherwise.

### GetBonusTolerancesOk

`func (o *ToleranceType) GetBonusTolerancesOk() (*[]interface{}, bool)`

GetBonusTolerancesOk returns a tuple with the BonusTolerances field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBonusTolerances

`func (o *ToleranceType) SetBonusTolerances(v []interface{})`

SetBonusTolerances sets BonusTolerances field to given value.

### HasBonusTolerances

`func (o *ToleranceType) HasBonusTolerances() bool`

HasBonusTolerances returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


