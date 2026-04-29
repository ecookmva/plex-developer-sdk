# PartsItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PartId** | Pointer to **string** |  | [optional] 
**SpecificationId** | Pointer to **string** |  | [optional] 
**Target** | Pointer to **float64** |  | [optional] 
**TargetPlus** | Pointer to **float64** |  | [optional] 
**TargetMinus** | Pointer to **float64** |  | [optional] 
**OneSidedMinimum** | Pointer to **float64** |  | [optional] 
**OneSidedMaximum** | Pointer to **float64** |  | [optional] 
**MeasurementText** | Pointer to **string** |  | [optional] 
**CompareValue** | Pointer to **string** |  | [optional] 

## Methods

### NewPartsItem

`func NewPartsItem() *PartsItem`

NewPartsItem instantiates a new PartsItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartsItemWithDefaults

`func NewPartsItemWithDefaults() *PartsItem`

NewPartsItemWithDefaults instantiates a new PartsItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPartId

`func (o *PartsItem) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *PartsItem) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *PartsItem) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *PartsItem) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetSpecificationId

`func (o *PartsItem) GetSpecificationId() string`

GetSpecificationId returns the SpecificationId field if non-nil, zero value otherwise.

### GetSpecificationIdOk

`func (o *PartsItem) GetSpecificationIdOk() (*string, bool)`

GetSpecificationIdOk returns a tuple with the SpecificationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpecificationId

`func (o *PartsItem) SetSpecificationId(v string)`

SetSpecificationId sets SpecificationId field to given value.

### HasSpecificationId

`func (o *PartsItem) HasSpecificationId() bool`

HasSpecificationId returns a boolean if a field has been set.

### GetTarget

`func (o *PartsItem) GetTarget() float64`

GetTarget returns the Target field if non-nil, zero value otherwise.

### GetTargetOk

`func (o *PartsItem) GetTargetOk() (*float64, bool)`

GetTargetOk returns a tuple with the Target field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTarget

`func (o *PartsItem) SetTarget(v float64)`

SetTarget sets Target field to given value.

### HasTarget

`func (o *PartsItem) HasTarget() bool`

HasTarget returns a boolean if a field has been set.

### GetTargetPlus

`func (o *PartsItem) GetTargetPlus() float64`

GetTargetPlus returns the TargetPlus field if non-nil, zero value otherwise.

### GetTargetPlusOk

`func (o *PartsItem) GetTargetPlusOk() (*float64, bool)`

GetTargetPlusOk returns a tuple with the TargetPlus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetPlus

`func (o *PartsItem) SetTargetPlus(v float64)`

SetTargetPlus sets TargetPlus field to given value.

### HasTargetPlus

`func (o *PartsItem) HasTargetPlus() bool`

HasTargetPlus returns a boolean if a field has been set.

### GetTargetMinus

`func (o *PartsItem) GetTargetMinus() float64`

GetTargetMinus returns the TargetMinus field if non-nil, zero value otherwise.

### GetTargetMinusOk

`func (o *PartsItem) GetTargetMinusOk() (*float64, bool)`

GetTargetMinusOk returns a tuple with the TargetMinus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetMinus

`func (o *PartsItem) SetTargetMinus(v float64)`

SetTargetMinus sets TargetMinus field to given value.

### HasTargetMinus

`func (o *PartsItem) HasTargetMinus() bool`

HasTargetMinus returns a boolean if a field has been set.

### GetOneSidedMinimum

`func (o *PartsItem) GetOneSidedMinimum() float64`

GetOneSidedMinimum returns the OneSidedMinimum field if non-nil, zero value otherwise.

### GetOneSidedMinimumOk

`func (o *PartsItem) GetOneSidedMinimumOk() (*float64, bool)`

GetOneSidedMinimumOk returns a tuple with the OneSidedMinimum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOneSidedMinimum

`func (o *PartsItem) SetOneSidedMinimum(v float64)`

SetOneSidedMinimum sets OneSidedMinimum field to given value.

### HasOneSidedMinimum

`func (o *PartsItem) HasOneSidedMinimum() bool`

HasOneSidedMinimum returns a boolean if a field has been set.

### GetOneSidedMaximum

`func (o *PartsItem) GetOneSidedMaximum() float64`

GetOneSidedMaximum returns the OneSidedMaximum field if non-nil, zero value otherwise.

### GetOneSidedMaximumOk

`func (o *PartsItem) GetOneSidedMaximumOk() (*float64, bool)`

GetOneSidedMaximumOk returns a tuple with the OneSidedMaximum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOneSidedMaximum

`func (o *PartsItem) SetOneSidedMaximum(v float64)`

SetOneSidedMaximum sets OneSidedMaximum field to given value.

### HasOneSidedMaximum

`func (o *PartsItem) HasOneSidedMaximum() bool`

HasOneSidedMaximum returns a boolean if a field has been set.

### GetMeasurementText

`func (o *PartsItem) GetMeasurementText() string`

GetMeasurementText returns the MeasurementText field if non-nil, zero value otherwise.

### GetMeasurementTextOk

`func (o *PartsItem) GetMeasurementTextOk() (*string, bool)`

GetMeasurementTextOk returns a tuple with the MeasurementText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeasurementText

`func (o *PartsItem) SetMeasurementText(v string)`

SetMeasurementText sets MeasurementText field to given value.

### HasMeasurementText

`func (o *PartsItem) HasMeasurementText() bool`

HasMeasurementText returns a boolean if a field has been set.

### GetCompareValue

`func (o *PartsItem) GetCompareValue() string`

GetCompareValue returns the CompareValue field if non-nil, zero value otherwise.

### GetCompareValueOk

`func (o *PartsItem) GetCompareValueOk() (*string, bool)`

GetCompareValueOk returns a tuple with the CompareValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompareValue

`func (o *PartsItem) SetCompareValue(v string)`

SetCompareValue sets CompareValue field to given value.

### HasCompareValue

`func (o *PartsItem) HasCompareValue() bool`

HasCompareValue returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


