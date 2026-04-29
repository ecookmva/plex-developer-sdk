# ChecksheetApiCreateChecksheetRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ControlPlanId** | Pointer to **string** | A unique identifier representing the Control Plan. | [optional] 
**ProductionWorkcenterId** | Pointer to **string** | A unique identifier representing the Workcenter. This will usually represent a live checksheet. | [optional] 
**JobOperationId** | Pointer to **string** | A unique identifier representing the Job Operation. | [optional] 
**PartId** | Pointer to **string** | A unique identifier representing the Part. | [optional] 
**PartOperationId** | Pointer to **string** | A unique identifier representing the Part Operation. | [optional] 
**OperationId** | Pointer to **string** | A unique identifier representing the Operation. | [optional] 
**InspectionMode** | Pointer to **string** | The Inspection Mode. | [optional] 
**ApprovedWorkcenterId** | Pointer to **string** | A unique identifier representing the Approved Workcenter for the Part and Operation. | [optional] 
**ContainerSerialNos** | Pointer to **[]string** | A list of Container Serial Nos. The serial number sent must belong to the part and operation of the intended control plan line being sent. | [optional] 
**Note** | Pointer to **string** | The note on the Measurement Group. | [optional] 
**InspectorEmployeeId** | Pointer to **string** | A unique identifier representing the Inspector Employee. | [optional] 
**Measurements** | Pointer to [**[]MeasurementsItem**](MeasurementsItem.md) | A list of Measurements. | [optional] 
**SpcChecksheetContainerText** | Pointer to **string** | SPC Checksheet Container Text. | [optional] 
**SpcChecksheetHeatText** | Pointer to **string** | SPC Checksheet Heat Text. | [optional] 
**SpcChecksheetProductionText** | Pointer to **string** | SPC Checksheet Production Text. | [optional] 
**SpecificationId** | Pointer to **string** | A unique identifier representing the Specification. | [optional] 
**Value** | Pointer to **float64** | The Measurement Value.   Attribute specifications are qualitative part features that can only result in a count of non-conformances,    like the presence of a burrs on a part, leak or no leak etc.   You may collect attribute data against a variable spec by specifying the pass / fail condition on the control plan line form,    so if a specification can be measured on a continuous scale, then enter it as a variable spec.   Measurements for attribute type must specify either a 1 or a 0 signifying a pass or a fail scenario.      Variable specifications are something that is not an attribute specification.    It can be measured on a continuous scale, such as height, weight, diameter, temperature, etc.   These would be tolerance types such as:   Two Sided (10 mm +/- 0.05 mm)   One Sided Maximum (10 mm max)   Based on which tolerance type you select, the limits will be calculated. For example, for a Two Sided Tolerance,    fields for the target and +/- values will be needed.     A specification could have one or more bonus tolerances associated with it.   An example for when this is needed: You have a feature size between 10mm to 11mm or 10.5mm +/- .5mm.    In addition there is an allowable maximum material condition of .02 or bonus tolerance for straightness.   If the feature size was at it&#39;s maximum say 11mm, then the bonus tolerance would be .02mm.   The way this will be need to be defined in part specification would be as below :   - Create a Part Specification for the Feature Size of 10.5mm +/- .5mm.   - Create another Part Specification for the Bonus Tolerance. In this example we are using a Tolerance Type &amp;quot;One-Sided Maximum&amp;quot; and added the .02mm.   - Specify a Bonus Tolerance and add a Part Specification with the feature size of 10.5mm as the Dependent Specification.    - Make the Applied To as &amp;quot;Upper&amp;quot; and the Bonus Side as &amp;quot;Upper&amp;quot;.   Finally create a Control Plan using these two Part Specifications. When you fillout a checksheet and add a dimenstion for the feature size,    the bonus specification will calculate in the target area automatically and you can enter a measurement as long as it meets the allowed target.   Note: The setting &amp;quot;Bonus Tolerance When Out of Spec Apply&amp;quot; will also contribute to the upper and lower bonus tolerance.   When turned on, bonus tolerance values will be calculated even when the bonus is based on a measurement that is out-of-spec.    When off, no bonus is applied from out-of-spec measurements.     Compare value specifications only apply to attribute Specifications.    It works in conjunction with the Control Plan line if you turn on the setting &amp;quot;Custom Checksheet Data Collection Type Display&amp;quot;.    For specifying such compare value functions add the value on the note section of measurements. | [optional] 
**Values** | Pointer to **[]float64** | The Measurement Values. | [optional] 
**GageId** | Pointer to **string** | The Gage ID for the Measurement Group. Note this will be saved on the checksheet only if the Setting Control_Plans , Gage ID Store is set to true. This field will be required if the corresponding inspection mode requires it. | [optional] 

## Methods

### NewChecksheetApiCreateChecksheetRequest

`func NewChecksheetApiCreateChecksheetRequest() *ChecksheetApiCreateChecksheetRequest`

NewChecksheetApiCreateChecksheetRequest instantiates a new ChecksheetApiCreateChecksheetRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChecksheetApiCreateChecksheetRequestWithDefaults

`func NewChecksheetApiCreateChecksheetRequestWithDefaults() *ChecksheetApiCreateChecksheetRequest`

NewChecksheetApiCreateChecksheetRequestWithDefaults instantiates a new ChecksheetApiCreateChecksheetRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetControlPlanId

`func (o *ChecksheetApiCreateChecksheetRequest) GetControlPlanId() string`

GetControlPlanId returns the ControlPlanId field if non-nil, zero value otherwise.

### GetControlPlanIdOk

`func (o *ChecksheetApiCreateChecksheetRequest) GetControlPlanIdOk() (*string, bool)`

GetControlPlanIdOk returns a tuple with the ControlPlanId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetControlPlanId

`func (o *ChecksheetApiCreateChecksheetRequest) SetControlPlanId(v string)`

SetControlPlanId sets ControlPlanId field to given value.

### HasControlPlanId

`func (o *ChecksheetApiCreateChecksheetRequest) HasControlPlanId() bool`

HasControlPlanId returns a boolean if a field has been set.

### GetProductionWorkcenterId

`func (o *ChecksheetApiCreateChecksheetRequest) GetProductionWorkcenterId() string`

GetProductionWorkcenterId returns the ProductionWorkcenterId field if non-nil, zero value otherwise.

### GetProductionWorkcenterIdOk

`func (o *ChecksheetApiCreateChecksheetRequest) GetProductionWorkcenterIdOk() (*string, bool)`

GetProductionWorkcenterIdOk returns a tuple with the ProductionWorkcenterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductionWorkcenterId

`func (o *ChecksheetApiCreateChecksheetRequest) SetProductionWorkcenterId(v string)`

SetProductionWorkcenterId sets ProductionWorkcenterId field to given value.

### HasProductionWorkcenterId

`func (o *ChecksheetApiCreateChecksheetRequest) HasProductionWorkcenterId() bool`

HasProductionWorkcenterId returns a boolean if a field has been set.

### GetJobOperationId

`func (o *ChecksheetApiCreateChecksheetRequest) GetJobOperationId() string`

GetJobOperationId returns the JobOperationId field if non-nil, zero value otherwise.

### GetJobOperationIdOk

`func (o *ChecksheetApiCreateChecksheetRequest) GetJobOperationIdOk() (*string, bool)`

GetJobOperationIdOk returns a tuple with the JobOperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobOperationId

`func (o *ChecksheetApiCreateChecksheetRequest) SetJobOperationId(v string)`

SetJobOperationId sets JobOperationId field to given value.

### HasJobOperationId

`func (o *ChecksheetApiCreateChecksheetRequest) HasJobOperationId() bool`

HasJobOperationId returns a boolean if a field has been set.

### GetPartId

`func (o *ChecksheetApiCreateChecksheetRequest) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *ChecksheetApiCreateChecksheetRequest) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *ChecksheetApiCreateChecksheetRequest) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *ChecksheetApiCreateChecksheetRequest) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetPartOperationId

`func (o *ChecksheetApiCreateChecksheetRequest) GetPartOperationId() string`

GetPartOperationId returns the PartOperationId field if non-nil, zero value otherwise.

### GetPartOperationIdOk

`func (o *ChecksheetApiCreateChecksheetRequest) GetPartOperationIdOk() (*string, bool)`

GetPartOperationIdOk returns a tuple with the PartOperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartOperationId

`func (o *ChecksheetApiCreateChecksheetRequest) SetPartOperationId(v string)`

SetPartOperationId sets PartOperationId field to given value.

### HasPartOperationId

`func (o *ChecksheetApiCreateChecksheetRequest) HasPartOperationId() bool`

HasPartOperationId returns a boolean if a field has been set.

### GetOperationId

`func (o *ChecksheetApiCreateChecksheetRequest) GetOperationId() string`

GetOperationId returns the OperationId field if non-nil, zero value otherwise.

### GetOperationIdOk

`func (o *ChecksheetApiCreateChecksheetRequest) GetOperationIdOk() (*string, bool)`

GetOperationIdOk returns a tuple with the OperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationId

`func (o *ChecksheetApiCreateChecksheetRequest) SetOperationId(v string)`

SetOperationId sets OperationId field to given value.

### HasOperationId

`func (o *ChecksheetApiCreateChecksheetRequest) HasOperationId() bool`

HasOperationId returns a boolean if a field has been set.

### GetInspectionMode

`func (o *ChecksheetApiCreateChecksheetRequest) GetInspectionMode() string`

GetInspectionMode returns the InspectionMode field if non-nil, zero value otherwise.

### GetInspectionModeOk

`func (o *ChecksheetApiCreateChecksheetRequest) GetInspectionModeOk() (*string, bool)`

GetInspectionModeOk returns a tuple with the InspectionMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInspectionMode

`func (o *ChecksheetApiCreateChecksheetRequest) SetInspectionMode(v string)`

SetInspectionMode sets InspectionMode field to given value.

### HasInspectionMode

`func (o *ChecksheetApiCreateChecksheetRequest) HasInspectionMode() bool`

HasInspectionMode returns a boolean if a field has been set.

### GetApprovedWorkcenterId

`func (o *ChecksheetApiCreateChecksheetRequest) GetApprovedWorkcenterId() string`

GetApprovedWorkcenterId returns the ApprovedWorkcenterId field if non-nil, zero value otherwise.

### GetApprovedWorkcenterIdOk

`func (o *ChecksheetApiCreateChecksheetRequest) GetApprovedWorkcenterIdOk() (*string, bool)`

GetApprovedWorkcenterIdOk returns a tuple with the ApprovedWorkcenterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovedWorkcenterId

`func (o *ChecksheetApiCreateChecksheetRequest) SetApprovedWorkcenterId(v string)`

SetApprovedWorkcenterId sets ApprovedWorkcenterId field to given value.

### HasApprovedWorkcenterId

`func (o *ChecksheetApiCreateChecksheetRequest) HasApprovedWorkcenterId() bool`

HasApprovedWorkcenterId returns a boolean if a field has been set.

### GetContainerSerialNos

`func (o *ChecksheetApiCreateChecksheetRequest) GetContainerSerialNos() []string`

GetContainerSerialNos returns the ContainerSerialNos field if non-nil, zero value otherwise.

### GetContainerSerialNosOk

`func (o *ChecksheetApiCreateChecksheetRequest) GetContainerSerialNosOk() (*[]string, bool)`

GetContainerSerialNosOk returns a tuple with the ContainerSerialNos field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContainerSerialNos

`func (o *ChecksheetApiCreateChecksheetRequest) SetContainerSerialNos(v []string)`

SetContainerSerialNos sets ContainerSerialNos field to given value.

### HasContainerSerialNos

`func (o *ChecksheetApiCreateChecksheetRequest) HasContainerSerialNos() bool`

HasContainerSerialNos returns a boolean if a field has been set.

### GetNote

`func (o *ChecksheetApiCreateChecksheetRequest) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *ChecksheetApiCreateChecksheetRequest) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *ChecksheetApiCreateChecksheetRequest) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *ChecksheetApiCreateChecksheetRequest) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetInspectorEmployeeId

`func (o *ChecksheetApiCreateChecksheetRequest) GetInspectorEmployeeId() string`

GetInspectorEmployeeId returns the InspectorEmployeeId field if non-nil, zero value otherwise.

### GetInspectorEmployeeIdOk

`func (o *ChecksheetApiCreateChecksheetRequest) GetInspectorEmployeeIdOk() (*string, bool)`

GetInspectorEmployeeIdOk returns a tuple with the InspectorEmployeeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInspectorEmployeeId

`func (o *ChecksheetApiCreateChecksheetRequest) SetInspectorEmployeeId(v string)`

SetInspectorEmployeeId sets InspectorEmployeeId field to given value.

### HasInspectorEmployeeId

`func (o *ChecksheetApiCreateChecksheetRequest) HasInspectorEmployeeId() bool`

HasInspectorEmployeeId returns a boolean if a field has been set.

### GetMeasurements

`func (o *ChecksheetApiCreateChecksheetRequest) GetMeasurements() []MeasurementsItem`

GetMeasurements returns the Measurements field if non-nil, zero value otherwise.

### GetMeasurementsOk

`func (o *ChecksheetApiCreateChecksheetRequest) GetMeasurementsOk() (*[]MeasurementsItem, bool)`

GetMeasurementsOk returns a tuple with the Measurements field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeasurements

`func (o *ChecksheetApiCreateChecksheetRequest) SetMeasurements(v []MeasurementsItem)`

SetMeasurements sets Measurements field to given value.

### HasMeasurements

`func (o *ChecksheetApiCreateChecksheetRequest) HasMeasurements() bool`

HasMeasurements returns a boolean if a field has been set.

### GetSpcChecksheetContainerText

`func (o *ChecksheetApiCreateChecksheetRequest) GetSpcChecksheetContainerText() string`

GetSpcChecksheetContainerText returns the SpcChecksheetContainerText field if non-nil, zero value otherwise.

### GetSpcChecksheetContainerTextOk

`func (o *ChecksheetApiCreateChecksheetRequest) GetSpcChecksheetContainerTextOk() (*string, bool)`

GetSpcChecksheetContainerTextOk returns a tuple with the SpcChecksheetContainerText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpcChecksheetContainerText

`func (o *ChecksheetApiCreateChecksheetRequest) SetSpcChecksheetContainerText(v string)`

SetSpcChecksheetContainerText sets SpcChecksheetContainerText field to given value.

### HasSpcChecksheetContainerText

`func (o *ChecksheetApiCreateChecksheetRequest) HasSpcChecksheetContainerText() bool`

HasSpcChecksheetContainerText returns a boolean if a field has been set.

### GetSpcChecksheetHeatText

`func (o *ChecksheetApiCreateChecksheetRequest) GetSpcChecksheetHeatText() string`

GetSpcChecksheetHeatText returns the SpcChecksheetHeatText field if non-nil, zero value otherwise.

### GetSpcChecksheetHeatTextOk

`func (o *ChecksheetApiCreateChecksheetRequest) GetSpcChecksheetHeatTextOk() (*string, bool)`

GetSpcChecksheetHeatTextOk returns a tuple with the SpcChecksheetHeatText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpcChecksheetHeatText

`func (o *ChecksheetApiCreateChecksheetRequest) SetSpcChecksheetHeatText(v string)`

SetSpcChecksheetHeatText sets SpcChecksheetHeatText field to given value.

### HasSpcChecksheetHeatText

`func (o *ChecksheetApiCreateChecksheetRequest) HasSpcChecksheetHeatText() bool`

HasSpcChecksheetHeatText returns a boolean if a field has been set.

### GetSpcChecksheetProductionText

`func (o *ChecksheetApiCreateChecksheetRequest) GetSpcChecksheetProductionText() string`

GetSpcChecksheetProductionText returns the SpcChecksheetProductionText field if non-nil, zero value otherwise.

### GetSpcChecksheetProductionTextOk

`func (o *ChecksheetApiCreateChecksheetRequest) GetSpcChecksheetProductionTextOk() (*string, bool)`

GetSpcChecksheetProductionTextOk returns a tuple with the SpcChecksheetProductionText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpcChecksheetProductionText

`func (o *ChecksheetApiCreateChecksheetRequest) SetSpcChecksheetProductionText(v string)`

SetSpcChecksheetProductionText sets SpcChecksheetProductionText field to given value.

### HasSpcChecksheetProductionText

`func (o *ChecksheetApiCreateChecksheetRequest) HasSpcChecksheetProductionText() bool`

HasSpcChecksheetProductionText returns a boolean if a field has been set.

### GetSpecificationId

`func (o *ChecksheetApiCreateChecksheetRequest) GetSpecificationId() string`

GetSpecificationId returns the SpecificationId field if non-nil, zero value otherwise.

### GetSpecificationIdOk

`func (o *ChecksheetApiCreateChecksheetRequest) GetSpecificationIdOk() (*string, bool)`

GetSpecificationIdOk returns a tuple with the SpecificationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpecificationId

`func (o *ChecksheetApiCreateChecksheetRequest) SetSpecificationId(v string)`

SetSpecificationId sets SpecificationId field to given value.

### HasSpecificationId

`func (o *ChecksheetApiCreateChecksheetRequest) HasSpecificationId() bool`

HasSpecificationId returns a boolean if a field has been set.

### GetValue

`func (o *ChecksheetApiCreateChecksheetRequest) GetValue() float64`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *ChecksheetApiCreateChecksheetRequest) GetValueOk() (*float64, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *ChecksheetApiCreateChecksheetRequest) SetValue(v float64)`

SetValue sets Value field to given value.

### HasValue

`func (o *ChecksheetApiCreateChecksheetRequest) HasValue() bool`

HasValue returns a boolean if a field has been set.

### GetValues

`func (o *ChecksheetApiCreateChecksheetRequest) GetValues() []float64`

GetValues returns the Values field if non-nil, zero value otherwise.

### GetValuesOk

`func (o *ChecksheetApiCreateChecksheetRequest) GetValuesOk() (*[]float64, bool)`

GetValuesOk returns a tuple with the Values field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValues

`func (o *ChecksheetApiCreateChecksheetRequest) SetValues(v []float64)`

SetValues sets Values field to given value.

### HasValues

`func (o *ChecksheetApiCreateChecksheetRequest) HasValues() bool`

HasValues returns a boolean if a field has been set.

### GetGageId

`func (o *ChecksheetApiCreateChecksheetRequest) GetGageId() string`

GetGageId returns the GageId field if non-nil, zero value otherwise.

### GetGageIdOk

`func (o *ChecksheetApiCreateChecksheetRequest) GetGageIdOk() (*string, bool)`

GetGageIdOk returns a tuple with the GageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGageId

`func (o *ChecksheetApiCreateChecksheetRequest) SetGageId(v string)`

SetGageId sets GageId field to given value.

### HasGageId

`func (o *ChecksheetApiCreateChecksheetRequest) HasGageId() bool`

HasGageId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


