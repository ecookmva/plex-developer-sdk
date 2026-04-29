# ChecksheetApiGetChecksheetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ChecksheetNumber** | Pointer to **int32** | The Checksheet Number. | [optional] 
**InspectionMode** | Pointer to **string** | The Inspection Mode. | [optional] 
**OperationId** | Pointer to **string** | A unique identifier representing the Operation. | [optional] 
**InspectionDateTime** | Pointer to **time.Time** | The inspection Date and Time. | [optional] 
**PartId** | Pointer to **string** | A unique identifier representing the Part. | [optional] 
**PartNumber** | Pointer to **string** | The Part Number. | [optional] 
**PartRevision** | Pointer to **string** | The Part Revision. | [optional] 
**PartOperationId** | Pointer to **string** | A unique identifier representing the Part Operation. | [optional] 
**WorkcenterId** | Pointer to **string** | A unique identifier representing the Workcenter. | [optional] 
**JobId** | Pointer to **string** | A unique identifier representing the Job. | [optional] 
**JobOperationId** | Pointer to **string** | A unique identifier representing the Job Operation. | [optional] 
**SpcChecksheetContainerText** | Pointer to **string** | SPC Checksheet Container Text. | [optional] 
**SpcChecksheetHeatText** | Pointer to **string** | SPC Checksheet Heat Text. | [optional] 
**SpcChecksheetProductionText** | Pointer to **string** | SPC Checksheet Production Text. | [optional] 
**ContainerSerialNumbers** | Pointer to **[]string** | The list of containers associated with a Checksheet. | [optional] 
**InspectorEmployeeId** | Pointer to **string** | A unique identifier representing the Inspector Employee. | [optional] 
**Note** | Pointer to **string** | The Checksheet Note. | [optional] 
**OutOfSpecification** | Pointer to **bool** | The Checksheet Out of Specification Flag. | [optional] 

## Methods

### NewChecksheetApiGetChecksheetResponse

`func NewChecksheetApiGetChecksheetResponse() *ChecksheetApiGetChecksheetResponse`

NewChecksheetApiGetChecksheetResponse instantiates a new ChecksheetApiGetChecksheetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChecksheetApiGetChecksheetResponseWithDefaults

`func NewChecksheetApiGetChecksheetResponseWithDefaults() *ChecksheetApiGetChecksheetResponse`

NewChecksheetApiGetChecksheetResponseWithDefaults instantiates a new ChecksheetApiGetChecksheetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetChecksheetNumber

`func (o *ChecksheetApiGetChecksheetResponse) GetChecksheetNumber() int32`

GetChecksheetNumber returns the ChecksheetNumber field if non-nil, zero value otherwise.

### GetChecksheetNumberOk

`func (o *ChecksheetApiGetChecksheetResponse) GetChecksheetNumberOk() (*int32, bool)`

GetChecksheetNumberOk returns a tuple with the ChecksheetNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChecksheetNumber

`func (o *ChecksheetApiGetChecksheetResponse) SetChecksheetNumber(v int32)`

SetChecksheetNumber sets ChecksheetNumber field to given value.

### HasChecksheetNumber

`func (o *ChecksheetApiGetChecksheetResponse) HasChecksheetNumber() bool`

HasChecksheetNumber returns a boolean if a field has been set.

### GetInspectionMode

`func (o *ChecksheetApiGetChecksheetResponse) GetInspectionMode() string`

GetInspectionMode returns the InspectionMode field if non-nil, zero value otherwise.

### GetInspectionModeOk

`func (o *ChecksheetApiGetChecksheetResponse) GetInspectionModeOk() (*string, bool)`

GetInspectionModeOk returns a tuple with the InspectionMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInspectionMode

`func (o *ChecksheetApiGetChecksheetResponse) SetInspectionMode(v string)`

SetInspectionMode sets InspectionMode field to given value.

### HasInspectionMode

`func (o *ChecksheetApiGetChecksheetResponse) HasInspectionMode() bool`

HasInspectionMode returns a boolean if a field has been set.

### GetOperationId

`func (o *ChecksheetApiGetChecksheetResponse) GetOperationId() string`

GetOperationId returns the OperationId field if non-nil, zero value otherwise.

### GetOperationIdOk

`func (o *ChecksheetApiGetChecksheetResponse) GetOperationIdOk() (*string, bool)`

GetOperationIdOk returns a tuple with the OperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationId

`func (o *ChecksheetApiGetChecksheetResponse) SetOperationId(v string)`

SetOperationId sets OperationId field to given value.

### HasOperationId

`func (o *ChecksheetApiGetChecksheetResponse) HasOperationId() bool`

HasOperationId returns a boolean if a field has been set.

### GetInspectionDateTime

`func (o *ChecksheetApiGetChecksheetResponse) GetInspectionDateTime() time.Time`

GetInspectionDateTime returns the InspectionDateTime field if non-nil, zero value otherwise.

### GetInspectionDateTimeOk

`func (o *ChecksheetApiGetChecksheetResponse) GetInspectionDateTimeOk() (*time.Time, bool)`

GetInspectionDateTimeOk returns a tuple with the InspectionDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInspectionDateTime

`func (o *ChecksheetApiGetChecksheetResponse) SetInspectionDateTime(v time.Time)`

SetInspectionDateTime sets InspectionDateTime field to given value.

### HasInspectionDateTime

`func (o *ChecksheetApiGetChecksheetResponse) HasInspectionDateTime() bool`

HasInspectionDateTime returns a boolean if a field has been set.

### GetPartId

`func (o *ChecksheetApiGetChecksheetResponse) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *ChecksheetApiGetChecksheetResponse) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *ChecksheetApiGetChecksheetResponse) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *ChecksheetApiGetChecksheetResponse) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetPartNumber

`func (o *ChecksheetApiGetChecksheetResponse) GetPartNumber() string`

GetPartNumber returns the PartNumber field if non-nil, zero value otherwise.

### GetPartNumberOk

`func (o *ChecksheetApiGetChecksheetResponse) GetPartNumberOk() (*string, bool)`

GetPartNumberOk returns a tuple with the PartNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumber

`func (o *ChecksheetApiGetChecksheetResponse) SetPartNumber(v string)`

SetPartNumber sets PartNumber field to given value.

### HasPartNumber

`func (o *ChecksheetApiGetChecksheetResponse) HasPartNumber() bool`

HasPartNumber returns a boolean if a field has been set.

### GetPartRevision

`func (o *ChecksheetApiGetChecksheetResponse) GetPartRevision() string`

GetPartRevision returns the PartRevision field if non-nil, zero value otherwise.

### GetPartRevisionOk

`func (o *ChecksheetApiGetChecksheetResponse) GetPartRevisionOk() (*string, bool)`

GetPartRevisionOk returns a tuple with the PartRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartRevision

`func (o *ChecksheetApiGetChecksheetResponse) SetPartRevision(v string)`

SetPartRevision sets PartRevision field to given value.

### HasPartRevision

`func (o *ChecksheetApiGetChecksheetResponse) HasPartRevision() bool`

HasPartRevision returns a boolean if a field has been set.

### GetPartOperationId

`func (o *ChecksheetApiGetChecksheetResponse) GetPartOperationId() string`

GetPartOperationId returns the PartOperationId field if non-nil, zero value otherwise.

### GetPartOperationIdOk

`func (o *ChecksheetApiGetChecksheetResponse) GetPartOperationIdOk() (*string, bool)`

GetPartOperationIdOk returns a tuple with the PartOperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartOperationId

`func (o *ChecksheetApiGetChecksheetResponse) SetPartOperationId(v string)`

SetPartOperationId sets PartOperationId field to given value.

### HasPartOperationId

`func (o *ChecksheetApiGetChecksheetResponse) HasPartOperationId() bool`

HasPartOperationId returns a boolean if a field has been set.

### GetWorkcenterId

`func (o *ChecksheetApiGetChecksheetResponse) GetWorkcenterId() string`

GetWorkcenterId returns the WorkcenterId field if non-nil, zero value otherwise.

### GetWorkcenterIdOk

`func (o *ChecksheetApiGetChecksheetResponse) GetWorkcenterIdOk() (*string, bool)`

GetWorkcenterIdOk returns a tuple with the WorkcenterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkcenterId

`func (o *ChecksheetApiGetChecksheetResponse) SetWorkcenterId(v string)`

SetWorkcenterId sets WorkcenterId field to given value.

### HasWorkcenterId

`func (o *ChecksheetApiGetChecksheetResponse) HasWorkcenterId() bool`

HasWorkcenterId returns a boolean if a field has been set.

### GetJobId

`func (o *ChecksheetApiGetChecksheetResponse) GetJobId() string`

GetJobId returns the JobId field if non-nil, zero value otherwise.

### GetJobIdOk

`func (o *ChecksheetApiGetChecksheetResponse) GetJobIdOk() (*string, bool)`

GetJobIdOk returns a tuple with the JobId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobId

`func (o *ChecksheetApiGetChecksheetResponse) SetJobId(v string)`

SetJobId sets JobId field to given value.

### HasJobId

`func (o *ChecksheetApiGetChecksheetResponse) HasJobId() bool`

HasJobId returns a boolean if a field has been set.

### GetJobOperationId

`func (o *ChecksheetApiGetChecksheetResponse) GetJobOperationId() string`

GetJobOperationId returns the JobOperationId field if non-nil, zero value otherwise.

### GetJobOperationIdOk

`func (o *ChecksheetApiGetChecksheetResponse) GetJobOperationIdOk() (*string, bool)`

GetJobOperationIdOk returns a tuple with the JobOperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobOperationId

`func (o *ChecksheetApiGetChecksheetResponse) SetJobOperationId(v string)`

SetJobOperationId sets JobOperationId field to given value.

### HasJobOperationId

`func (o *ChecksheetApiGetChecksheetResponse) HasJobOperationId() bool`

HasJobOperationId returns a boolean if a field has been set.

### GetSpcChecksheetContainerText

`func (o *ChecksheetApiGetChecksheetResponse) GetSpcChecksheetContainerText() string`

GetSpcChecksheetContainerText returns the SpcChecksheetContainerText field if non-nil, zero value otherwise.

### GetSpcChecksheetContainerTextOk

`func (o *ChecksheetApiGetChecksheetResponse) GetSpcChecksheetContainerTextOk() (*string, bool)`

GetSpcChecksheetContainerTextOk returns a tuple with the SpcChecksheetContainerText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpcChecksheetContainerText

`func (o *ChecksheetApiGetChecksheetResponse) SetSpcChecksheetContainerText(v string)`

SetSpcChecksheetContainerText sets SpcChecksheetContainerText field to given value.

### HasSpcChecksheetContainerText

`func (o *ChecksheetApiGetChecksheetResponse) HasSpcChecksheetContainerText() bool`

HasSpcChecksheetContainerText returns a boolean if a field has been set.

### GetSpcChecksheetHeatText

`func (o *ChecksheetApiGetChecksheetResponse) GetSpcChecksheetHeatText() string`

GetSpcChecksheetHeatText returns the SpcChecksheetHeatText field if non-nil, zero value otherwise.

### GetSpcChecksheetHeatTextOk

`func (o *ChecksheetApiGetChecksheetResponse) GetSpcChecksheetHeatTextOk() (*string, bool)`

GetSpcChecksheetHeatTextOk returns a tuple with the SpcChecksheetHeatText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpcChecksheetHeatText

`func (o *ChecksheetApiGetChecksheetResponse) SetSpcChecksheetHeatText(v string)`

SetSpcChecksheetHeatText sets SpcChecksheetHeatText field to given value.

### HasSpcChecksheetHeatText

`func (o *ChecksheetApiGetChecksheetResponse) HasSpcChecksheetHeatText() bool`

HasSpcChecksheetHeatText returns a boolean if a field has been set.

### GetSpcChecksheetProductionText

`func (o *ChecksheetApiGetChecksheetResponse) GetSpcChecksheetProductionText() string`

GetSpcChecksheetProductionText returns the SpcChecksheetProductionText field if non-nil, zero value otherwise.

### GetSpcChecksheetProductionTextOk

`func (o *ChecksheetApiGetChecksheetResponse) GetSpcChecksheetProductionTextOk() (*string, bool)`

GetSpcChecksheetProductionTextOk returns a tuple with the SpcChecksheetProductionText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpcChecksheetProductionText

`func (o *ChecksheetApiGetChecksheetResponse) SetSpcChecksheetProductionText(v string)`

SetSpcChecksheetProductionText sets SpcChecksheetProductionText field to given value.

### HasSpcChecksheetProductionText

`func (o *ChecksheetApiGetChecksheetResponse) HasSpcChecksheetProductionText() bool`

HasSpcChecksheetProductionText returns a boolean if a field has been set.

### GetContainerSerialNumbers

`func (o *ChecksheetApiGetChecksheetResponse) GetContainerSerialNumbers() []string`

GetContainerSerialNumbers returns the ContainerSerialNumbers field if non-nil, zero value otherwise.

### GetContainerSerialNumbersOk

`func (o *ChecksheetApiGetChecksheetResponse) GetContainerSerialNumbersOk() (*[]string, bool)`

GetContainerSerialNumbersOk returns a tuple with the ContainerSerialNumbers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContainerSerialNumbers

`func (o *ChecksheetApiGetChecksheetResponse) SetContainerSerialNumbers(v []string)`

SetContainerSerialNumbers sets ContainerSerialNumbers field to given value.

### HasContainerSerialNumbers

`func (o *ChecksheetApiGetChecksheetResponse) HasContainerSerialNumbers() bool`

HasContainerSerialNumbers returns a boolean if a field has been set.

### GetInspectorEmployeeId

`func (o *ChecksheetApiGetChecksheetResponse) GetInspectorEmployeeId() string`

GetInspectorEmployeeId returns the InspectorEmployeeId field if non-nil, zero value otherwise.

### GetInspectorEmployeeIdOk

`func (o *ChecksheetApiGetChecksheetResponse) GetInspectorEmployeeIdOk() (*string, bool)`

GetInspectorEmployeeIdOk returns a tuple with the InspectorEmployeeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInspectorEmployeeId

`func (o *ChecksheetApiGetChecksheetResponse) SetInspectorEmployeeId(v string)`

SetInspectorEmployeeId sets InspectorEmployeeId field to given value.

### HasInspectorEmployeeId

`func (o *ChecksheetApiGetChecksheetResponse) HasInspectorEmployeeId() bool`

HasInspectorEmployeeId returns a boolean if a field has been set.

### GetNote

`func (o *ChecksheetApiGetChecksheetResponse) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *ChecksheetApiGetChecksheetResponse) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *ChecksheetApiGetChecksheetResponse) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *ChecksheetApiGetChecksheetResponse) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetOutOfSpecification

`func (o *ChecksheetApiGetChecksheetResponse) GetOutOfSpecification() bool`

GetOutOfSpecification returns the OutOfSpecification field if non-nil, zero value otherwise.

### GetOutOfSpecificationOk

`func (o *ChecksheetApiGetChecksheetResponse) GetOutOfSpecificationOk() (*bool, bool)`

GetOutOfSpecificationOk returns a tuple with the OutOfSpecification field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutOfSpecification

`func (o *ChecksheetApiGetChecksheetResponse) SetOutOfSpecification(v bool)`

SetOutOfSpecification sets OutOfSpecification field to given value.

### HasOutOfSpecification

`func (o *ChecksheetApiGetChecksheetResponse) HasOutOfSpecification() bool`

HasOutOfSpecification returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


