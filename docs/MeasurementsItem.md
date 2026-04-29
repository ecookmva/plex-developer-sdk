# MeasurementsItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SpecificationId** | Pointer to **string** | A unique identifier representing the Specification. | [optional] 
**Value** | Pointer to **float64** | The Measurement Value.           Attribute specifications are qualitative part features that can only result in a count of non-conformances,         like the presence of a burrs on a part, leak or no leak etc.        You may collect attribute data against a variable spec by specifying the pass / fail condition on the control plan line form,         so if a specification can be measured on a continuous scale, then enter it as a variable spec.        Measurements for attribute type must specify either a 1 or a 0 signifying a pass or a fail scenario.                  Variable specifications are something that is not an attribute specification.         It can be measured on a continuous scale, such as height, weight, diameter, temperature, etc.        These would be tolerance types such as:        Two Sided (10 mm +/- 0.05 mm)        One Sided Maximum (10 mm max)        Based on which tolerance type you select, the limits will be calculated. For example, for a Two Sided Tolerance,         fields for the target and +/- values will be needed.                A specification could have one or more bonus tolerances associated with it.        An example for when this is needed: You have a feature size between 10mm to 11mm or 10.5mm +/- .5mm.         In addition there is an allowable maximum material condition of .02 or bonus tolerance for straightness.        If the feature size was at it&#39;s maximum say 11mm, then the bonus tolerance would be .02mm.        The way this will be need to be defined in part specification would be as below :        - Create a Part Specification for the Feature Size of 10.5mm +/- .5mm.        - Create another Part Specification for the Bonus Tolerance. In this example we are using a Tolerance Type \&quot;One-Sided Maximum\&quot; and added the .02mm.        - Specify a Bonus Tolerance and add a Part Specification with the feature size of 10.5mm as the Dependent Specification.         - Make the Applied To as \&quot;Upper\&quot; and the Bonus Side as \&quot;Upper\&quot;.        Finally create a Control Plan using these two Part Specifications. When you fillout a checksheet and add a dimenstion for the feature size,         the bonus specification will calculate in the target area automatically and you can enter a measurement as long as it meets the allowed target.        Note: The setting \&quot;Bonus Tolerance When Out of Spec Apply\&quot; will also contribute to the upper and lower bonus tolerance.        When turned on, bonus tolerance values will be calculated even when the bonus is based on a measurement that is out-of-spec.         When off, no bonus is applied from out-of-spec measurements.                Compare value specifications only apply to attribute Specifications.         It works in conjunction with the Control Plan line if you turn on the setting \&quot;Custom Checksheet Data Collection Type Display\&quot;.         For specifying such compare value functions add the value on the note section of measurements. | [optional] 
**Values** | Pointer to **[]float64** | The Measurement Values. | [optional] 
**Note** | Pointer to **string** | The note on the Measurement Group. | [optional] 
**GageId** | Pointer to **string** | The Gage ID for the Measurement Group. Note this will be saved on the checksheet only if the Setting Control_Plans , Gage ID Store is set to true. This field will be required if the corresponding inspection mode requires it. | [optional] 

## Methods

### NewMeasurementsItem

`func NewMeasurementsItem() *MeasurementsItem`

NewMeasurementsItem instantiates a new MeasurementsItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMeasurementsItemWithDefaults

`func NewMeasurementsItemWithDefaults() *MeasurementsItem`

NewMeasurementsItemWithDefaults instantiates a new MeasurementsItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSpecificationId

`func (o *MeasurementsItem) GetSpecificationId() string`

GetSpecificationId returns the SpecificationId field if non-nil, zero value otherwise.

### GetSpecificationIdOk

`func (o *MeasurementsItem) GetSpecificationIdOk() (*string, bool)`

GetSpecificationIdOk returns a tuple with the SpecificationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpecificationId

`func (o *MeasurementsItem) SetSpecificationId(v string)`

SetSpecificationId sets SpecificationId field to given value.

### HasSpecificationId

`func (o *MeasurementsItem) HasSpecificationId() bool`

HasSpecificationId returns a boolean if a field has been set.

### GetValue

`func (o *MeasurementsItem) GetValue() float64`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *MeasurementsItem) GetValueOk() (*float64, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *MeasurementsItem) SetValue(v float64)`

SetValue sets Value field to given value.

### HasValue

`func (o *MeasurementsItem) HasValue() bool`

HasValue returns a boolean if a field has been set.

### GetValues

`func (o *MeasurementsItem) GetValues() []float64`

GetValues returns the Values field if non-nil, zero value otherwise.

### GetValuesOk

`func (o *MeasurementsItem) GetValuesOk() (*[]float64, bool)`

GetValuesOk returns a tuple with the Values field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValues

`func (o *MeasurementsItem) SetValues(v []float64)`

SetValues sets Values field to given value.

### HasValues

`func (o *MeasurementsItem) HasValues() bool`

HasValues returns a boolean if a field has been set.

### GetNote

`func (o *MeasurementsItem) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *MeasurementsItem) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *MeasurementsItem) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *MeasurementsItem) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetGageId

`func (o *MeasurementsItem) GetGageId() string`

GetGageId returns the GageId field if non-nil, zero value otherwise.

### GetGageIdOk

`func (o *MeasurementsItem) GetGageIdOk() (*string, bool)`

GetGageIdOk returns a tuple with the GageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGageId

`func (o *MeasurementsItem) SetGageId(v string)`

SetGageId sets GageId field to given value.

### HasGageId

`func (o *MeasurementsItem) HasGageId() bool`

HasGageId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


