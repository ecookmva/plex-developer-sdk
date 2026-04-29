# PartSpecificGagesItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**GageId** | Pointer to **string** | A unique ID representing the Gage. | [optional] 
**GageType** | Pointer to **string** | The gage type. | [optional] 
**NextCalibrationDate** | Pointer to **time.Time** | The next calibration date. | [optional] 
**Note** | Pointer to **string** | The gage note. | [optional] 
**ElectronicGage** | Pointer to **bool** | The designation if the gage is electronic. | [optional] 

## Methods

### NewPartSpecificGagesItem

`func NewPartSpecificGagesItem() *PartSpecificGagesItem`

NewPartSpecificGagesItem instantiates a new PartSpecificGagesItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartSpecificGagesItemWithDefaults

`func NewPartSpecificGagesItemWithDefaults() *PartSpecificGagesItem`

NewPartSpecificGagesItemWithDefaults instantiates a new PartSpecificGagesItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetGageId

`func (o *PartSpecificGagesItem) GetGageId() string`

GetGageId returns the GageId field if non-nil, zero value otherwise.

### GetGageIdOk

`func (o *PartSpecificGagesItem) GetGageIdOk() (*string, bool)`

GetGageIdOk returns a tuple with the GageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGageId

`func (o *PartSpecificGagesItem) SetGageId(v string)`

SetGageId sets GageId field to given value.

### HasGageId

`func (o *PartSpecificGagesItem) HasGageId() bool`

HasGageId returns a boolean if a field has been set.

### GetGageType

`func (o *PartSpecificGagesItem) GetGageType() string`

GetGageType returns the GageType field if non-nil, zero value otherwise.

### GetGageTypeOk

`func (o *PartSpecificGagesItem) GetGageTypeOk() (*string, bool)`

GetGageTypeOk returns a tuple with the GageType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGageType

`func (o *PartSpecificGagesItem) SetGageType(v string)`

SetGageType sets GageType field to given value.

### HasGageType

`func (o *PartSpecificGagesItem) HasGageType() bool`

HasGageType returns a boolean if a field has been set.

### GetNextCalibrationDate

`func (o *PartSpecificGagesItem) GetNextCalibrationDate() time.Time`

GetNextCalibrationDate returns the NextCalibrationDate field if non-nil, zero value otherwise.

### GetNextCalibrationDateOk

`func (o *PartSpecificGagesItem) GetNextCalibrationDateOk() (*time.Time, bool)`

GetNextCalibrationDateOk returns a tuple with the NextCalibrationDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextCalibrationDate

`func (o *PartSpecificGagesItem) SetNextCalibrationDate(v time.Time)`

SetNextCalibrationDate sets NextCalibrationDate field to given value.

### HasNextCalibrationDate

`func (o *PartSpecificGagesItem) HasNextCalibrationDate() bool`

HasNextCalibrationDate returns a boolean if a field has been set.

### GetNote

`func (o *PartSpecificGagesItem) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *PartSpecificGagesItem) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *PartSpecificGagesItem) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *PartSpecificGagesItem) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetElectronicGage

`func (o *PartSpecificGagesItem) GetElectronicGage() bool`

GetElectronicGage returns the ElectronicGage field if non-nil, zero value otherwise.

### GetElectronicGageOk

`func (o *PartSpecificGagesItem) GetElectronicGageOk() (*bool, bool)`

GetElectronicGageOk returns a tuple with the ElectronicGage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetElectronicGage

`func (o *PartSpecificGagesItem) SetElectronicGage(v bool)`

SetElectronicGage sets ElectronicGage field to given value.

### HasElectronicGage

`func (o *PartSpecificGagesItem) HasElectronicGage() bool`

HasElectronicGage returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


