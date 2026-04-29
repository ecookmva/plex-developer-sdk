# ChecksheetTypeApiListChecksheetTypesItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | Pointer to **string** | The description of the Checksheet Type. | [optional] 
**Specifications** | Pointer to **string** | Determines the configuration of specifications on the checksheet setup form. When &#39;Single Part Spec&#39;, a single part specification for the part on the checksheet may be selected. When &#39;Multiple Part Specs&#39;, multiple part specifications may be selected. When &#39;Enter Single Spec&#39;, any single part specification may be selected. | [optional] 
**PreselectedSpecifications** | Pointer to **string** | Determines if Customer Specified or Dock Audit specifications are preselected on the checksheet setup form when Specifications is set to Multiple Part Specs. | [optional] 
**InProcess** | Pointer to **bool** | Designation if the checksheet type is used for production checksheets launched from the Control Panel. | [optional] 
**Pieces** | Pointer to **int32** | The default number of measurements on the checksheet setup form. | [optional] 
**Container** | Pointer to **bool** | Designation if container serial numbers are used on the checksheet form. Used in conjunction with the setting Container Text Standalone Display to enable the SPC Checksheet Container Text field on the checksheet form. | [optional] 
**Operation** | Pointer to **bool** | Designation if the operation field is enabled on the checksheet form. | [optional] 
**Workcenter** | Pointer to **bool** | Designation if workcenters are used on the checksheet setup. | [optional] 
**SubgroupSize** | Pointer to **int32** | The subgroup size. | [optional] 
**Subgroup** | Pointer to **bool** | Designation if subgroups are used on the checksheet. | [optional] 
**Process** | Pointer to **bool** | Designation if the checksheet type is used for Process Control checksheets. | [optional] 
**StatusRequired** | Pointer to **bool** | Designation if the Status and Days Until Expiration fields are enabled on the checksheet. | [optional] 

## Methods

### NewChecksheetTypeApiListChecksheetTypesItem

`func NewChecksheetTypeApiListChecksheetTypesItem() *ChecksheetTypeApiListChecksheetTypesItem`

NewChecksheetTypeApiListChecksheetTypesItem instantiates a new ChecksheetTypeApiListChecksheetTypesItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChecksheetTypeApiListChecksheetTypesItemWithDefaults

`func NewChecksheetTypeApiListChecksheetTypesItemWithDefaults() *ChecksheetTypeApiListChecksheetTypesItem`

NewChecksheetTypeApiListChecksheetTypesItemWithDefaults instantiates a new ChecksheetTypeApiListChecksheetTypesItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *ChecksheetTypeApiListChecksheetTypesItem) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ChecksheetTypeApiListChecksheetTypesItem) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ChecksheetTypeApiListChecksheetTypesItem) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ChecksheetTypeApiListChecksheetTypesItem) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetSpecifications

`func (o *ChecksheetTypeApiListChecksheetTypesItem) GetSpecifications() string`

GetSpecifications returns the Specifications field if non-nil, zero value otherwise.

### GetSpecificationsOk

`func (o *ChecksheetTypeApiListChecksheetTypesItem) GetSpecificationsOk() (*string, bool)`

GetSpecificationsOk returns a tuple with the Specifications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpecifications

`func (o *ChecksheetTypeApiListChecksheetTypesItem) SetSpecifications(v string)`

SetSpecifications sets Specifications field to given value.

### HasSpecifications

`func (o *ChecksheetTypeApiListChecksheetTypesItem) HasSpecifications() bool`

HasSpecifications returns a boolean if a field has been set.

### GetPreselectedSpecifications

`func (o *ChecksheetTypeApiListChecksheetTypesItem) GetPreselectedSpecifications() string`

GetPreselectedSpecifications returns the PreselectedSpecifications field if non-nil, zero value otherwise.

### GetPreselectedSpecificationsOk

`func (o *ChecksheetTypeApiListChecksheetTypesItem) GetPreselectedSpecificationsOk() (*string, bool)`

GetPreselectedSpecificationsOk returns a tuple with the PreselectedSpecifications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreselectedSpecifications

`func (o *ChecksheetTypeApiListChecksheetTypesItem) SetPreselectedSpecifications(v string)`

SetPreselectedSpecifications sets PreselectedSpecifications field to given value.

### HasPreselectedSpecifications

`func (o *ChecksheetTypeApiListChecksheetTypesItem) HasPreselectedSpecifications() bool`

HasPreselectedSpecifications returns a boolean if a field has been set.

### GetInProcess

`func (o *ChecksheetTypeApiListChecksheetTypesItem) GetInProcess() bool`

GetInProcess returns the InProcess field if non-nil, zero value otherwise.

### GetInProcessOk

`func (o *ChecksheetTypeApiListChecksheetTypesItem) GetInProcessOk() (*bool, bool)`

GetInProcessOk returns a tuple with the InProcess field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInProcess

`func (o *ChecksheetTypeApiListChecksheetTypesItem) SetInProcess(v bool)`

SetInProcess sets InProcess field to given value.

### HasInProcess

`func (o *ChecksheetTypeApiListChecksheetTypesItem) HasInProcess() bool`

HasInProcess returns a boolean if a field has been set.

### GetPieces

`func (o *ChecksheetTypeApiListChecksheetTypesItem) GetPieces() int32`

GetPieces returns the Pieces field if non-nil, zero value otherwise.

### GetPiecesOk

`func (o *ChecksheetTypeApiListChecksheetTypesItem) GetPiecesOk() (*int32, bool)`

GetPiecesOk returns a tuple with the Pieces field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPieces

`func (o *ChecksheetTypeApiListChecksheetTypesItem) SetPieces(v int32)`

SetPieces sets Pieces field to given value.

### HasPieces

`func (o *ChecksheetTypeApiListChecksheetTypesItem) HasPieces() bool`

HasPieces returns a boolean if a field has been set.

### GetContainer

`func (o *ChecksheetTypeApiListChecksheetTypesItem) GetContainer() bool`

GetContainer returns the Container field if non-nil, zero value otherwise.

### GetContainerOk

`func (o *ChecksheetTypeApiListChecksheetTypesItem) GetContainerOk() (*bool, bool)`

GetContainerOk returns a tuple with the Container field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContainer

`func (o *ChecksheetTypeApiListChecksheetTypesItem) SetContainer(v bool)`

SetContainer sets Container field to given value.

### HasContainer

`func (o *ChecksheetTypeApiListChecksheetTypesItem) HasContainer() bool`

HasContainer returns a boolean if a field has been set.

### GetOperation

`func (o *ChecksheetTypeApiListChecksheetTypesItem) GetOperation() bool`

GetOperation returns the Operation field if non-nil, zero value otherwise.

### GetOperationOk

`func (o *ChecksheetTypeApiListChecksheetTypesItem) GetOperationOk() (*bool, bool)`

GetOperationOk returns a tuple with the Operation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperation

`func (o *ChecksheetTypeApiListChecksheetTypesItem) SetOperation(v bool)`

SetOperation sets Operation field to given value.

### HasOperation

`func (o *ChecksheetTypeApiListChecksheetTypesItem) HasOperation() bool`

HasOperation returns a boolean if a field has been set.

### GetWorkcenter

`func (o *ChecksheetTypeApiListChecksheetTypesItem) GetWorkcenter() bool`

GetWorkcenter returns the Workcenter field if non-nil, zero value otherwise.

### GetWorkcenterOk

`func (o *ChecksheetTypeApiListChecksheetTypesItem) GetWorkcenterOk() (*bool, bool)`

GetWorkcenterOk returns a tuple with the Workcenter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkcenter

`func (o *ChecksheetTypeApiListChecksheetTypesItem) SetWorkcenter(v bool)`

SetWorkcenter sets Workcenter field to given value.

### HasWorkcenter

`func (o *ChecksheetTypeApiListChecksheetTypesItem) HasWorkcenter() bool`

HasWorkcenter returns a boolean if a field has been set.

### GetSubgroupSize

`func (o *ChecksheetTypeApiListChecksheetTypesItem) GetSubgroupSize() int32`

GetSubgroupSize returns the SubgroupSize field if non-nil, zero value otherwise.

### GetSubgroupSizeOk

`func (o *ChecksheetTypeApiListChecksheetTypesItem) GetSubgroupSizeOk() (*int32, bool)`

GetSubgroupSizeOk returns a tuple with the SubgroupSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubgroupSize

`func (o *ChecksheetTypeApiListChecksheetTypesItem) SetSubgroupSize(v int32)`

SetSubgroupSize sets SubgroupSize field to given value.

### HasSubgroupSize

`func (o *ChecksheetTypeApiListChecksheetTypesItem) HasSubgroupSize() bool`

HasSubgroupSize returns a boolean if a field has been set.

### GetSubgroup

`func (o *ChecksheetTypeApiListChecksheetTypesItem) GetSubgroup() bool`

GetSubgroup returns the Subgroup field if non-nil, zero value otherwise.

### GetSubgroupOk

`func (o *ChecksheetTypeApiListChecksheetTypesItem) GetSubgroupOk() (*bool, bool)`

GetSubgroupOk returns a tuple with the Subgroup field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubgroup

`func (o *ChecksheetTypeApiListChecksheetTypesItem) SetSubgroup(v bool)`

SetSubgroup sets Subgroup field to given value.

### HasSubgroup

`func (o *ChecksheetTypeApiListChecksheetTypesItem) HasSubgroup() bool`

HasSubgroup returns a boolean if a field has been set.

### GetProcess

`func (o *ChecksheetTypeApiListChecksheetTypesItem) GetProcess() bool`

GetProcess returns the Process field if non-nil, zero value otherwise.

### GetProcessOk

`func (o *ChecksheetTypeApiListChecksheetTypesItem) GetProcessOk() (*bool, bool)`

GetProcessOk returns a tuple with the Process field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcess

`func (o *ChecksheetTypeApiListChecksheetTypesItem) SetProcess(v bool)`

SetProcess sets Process field to given value.

### HasProcess

`func (o *ChecksheetTypeApiListChecksheetTypesItem) HasProcess() bool`

HasProcess returns a boolean if a field has been set.

### GetStatusRequired

`func (o *ChecksheetTypeApiListChecksheetTypesItem) GetStatusRequired() bool`

GetStatusRequired returns the StatusRequired field if non-nil, zero value otherwise.

### GetStatusRequiredOk

`func (o *ChecksheetTypeApiListChecksheetTypesItem) GetStatusRequiredOk() (*bool, bool)`

GetStatusRequiredOk returns a tuple with the StatusRequired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatusRequired

`func (o *ChecksheetTypeApiListChecksheetTypesItem) SetStatusRequired(v bool)`

SetStatusRequired sets StatusRequired field to given value.

### HasStatusRequired

`func (o *ChecksheetTypeApiListChecksheetTypesItem) HasStatusRequired() bool`

HasStatusRequired returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


