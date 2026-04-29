# ToleranceTypesApiListToleranceTypesItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ToleranceType** | Pointer to **string** | The tolerance type name. | [optional] 
**ToleranceTypeCode** | Pointer to **string** | An abbreviation for the type of tolerance allowed for a specification. | [optional] 
**AttributeData** | Pointer to **bool** | The designation of this tolerance type is an attribute specification or not. | [optional] 
**ReferenceOnly** | Pointer to **bool** | The designation if this tolerance type is reference only. | [optional] 
**OneSidedMaxFlag** | Pointer to **bool** | The designation if this tolerance type is set to one sided maximum. | [optional] 
**OneSidedMinFlag** | Pointer to **bool** | The designation if this tolerance type is set to one sided minimum. | [optional] 
**OneSidedShowTargetFlag** | Pointer to **bool** | The designation if this tolerance type is one sided and needs to specify a target value as well. | [optional] 
**TargetOnlyFlag** | Pointer to **bool** | The designation if this tolerance type should only specify a target. | [optional] 
**TextOnlyFlag** | Pointer to **bool** | The designation if this tolerance type only needs a text for verification. | [optional] 
**Default** | Pointer to **bool** | This designates if this tolerance type is the default for part specifications. | [optional] 

## Methods

### NewToleranceTypesApiListToleranceTypesItem

`func NewToleranceTypesApiListToleranceTypesItem() *ToleranceTypesApiListToleranceTypesItem`

NewToleranceTypesApiListToleranceTypesItem instantiates a new ToleranceTypesApiListToleranceTypesItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewToleranceTypesApiListToleranceTypesItemWithDefaults

`func NewToleranceTypesApiListToleranceTypesItemWithDefaults() *ToleranceTypesApiListToleranceTypesItem`

NewToleranceTypesApiListToleranceTypesItemWithDefaults instantiates a new ToleranceTypesApiListToleranceTypesItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetToleranceType

`func (o *ToleranceTypesApiListToleranceTypesItem) GetToleranceType() string`

GetToleranceType returns the ToleranceType field if non-nil, zero value otherwise.

### GetToleranceTypeOk

`func (o *ToleranceTypesApiListToleranceTypesItem) GetToleranceTypeOk() (*string, bool)`

GetToleranceTypeOk returns a tuple with the ToleranceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToleranceType

`func (o *ToleranceTypesApiListToleranceTypesItem) SetToleranceType(v string)`

SetToleranceType sets ToleranceType field to given value.

### HasToleranceType

`func (o *ToleranceTypesApiListToleranceTypesItem) HasToleranceType() bool`

HasToleranceType returns a boolean if a field has been set.

### GetToleranceTypeCode

`func (o *ToleranceTypesApiListToleranceTypesItem) GetToleranceTypeCode() string`

GetToleranceTypeCode returns the ToleranceTypeCode field if non-nil, zero value otherwise.

### GetToleranceTypeCodeOk

`func (o *ToleranceTypesApiListToleranceTypesItem) GetToleranceTypeCodeOk() (*string, bool)`

GetToleranceTypeCodeOk returns a tuple with the ToleranceTypeCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToleranceTypeCode

`func (o *ToleranceTypesApiListToleranceTypesItem) SetToleranceTypeCode(v string)`

SetToleranceTypeCode sets ToleranceTypeCode field to given value.

### HasToleranceTypeCode

`func (o *ToleranceTypesApiListToleranceTypesItem) HasToleranceTypeCode() bool`

HasToleranceTypeCode returns a boolean if a field has been set.

### GetAttributeData

`func (o *ToleranceTypesApiListToleranceTypesItem) GetAttributeData() bool`

GetAttributeData returns the AttributeData field if non-nil, zero value otherwise.

### GetAttributeDataOk

`func (o *ToleranceTypesApiListToleranceTypesItem) GetAttributeDataOk() (*bool, bool)`

GetAttributeDataOk returns a tuple with the AttributeData field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttributeData

`func (o *ToleranceTypesApiListToleranceTypesItem) SetAttributeData(v bool)`

SetAttributeData sets AttributeData field to given value.

### HasAttributeData

`func (o *ToleranceTypesApiListToleranceTypesItem) HasAttributeData() bool`

HasAttributeData returns a boolean if a field has been set.

### GetReferenceOnly

`func (o *ToleranceTypesApiListToleranceTypesItem) GetReferenceOnly() bool`

GetReferenceOnly returns the ReferenceOnly field if non-nil, zero value otherwise.

### GetReferenceOnlyOk

`func (o *ToleranceTypesApiListToleranceTypesItem) GetReferenceOnlyOk() (*bool, bool)`

GetReferenceOnlyOk returns a tuple with the ReferenceOnly field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferenceOnly

`func (o *ToleranceTypesApiListToleranceTypesItem) SetReferenceOnly(v bool)`

SetReferenceOnly sets ReferenceOnly field to given value.

### HasReferenceOnly

`func (o *ToleranceTypesApiListToleranceTypesItem) HasReferenceOnly() bool`

HasReferenceOnly returns a boolean if a field has been set.

### GetOneSidedMaxFlag

`func (o *ToleranceTypesApiListToleranceTypesItem) GetOneSidedMaxFlag() bool`

GetOneSidedMaxFlag returns the OneSidedMaxFlag field if non-nil, zero value otherwise.

### GetOneSidedMaxFlagOk

`func (o *ToleranceTypesApiListToleranceTypesItem) GetOneSidedMaxFlagOk() (*bool, bool)`

GetOneSidedMaxFlagOk returns a tuple with the OneSidedMaxFlag field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOneSidedMaxFlag

`func (o *ToleranceTypesApiListToleranceTypesItem) SetOneSidedMaxFlag(v bool)`

SetOneSidedMaxFlag sets OneSidedMaxFlag field to given value.

### HasOneSidedMaxFlag

`func (o *ToleranceTypesApiListToleranceTypesItem) HasOneSidedMaxFlag() bool`

HasOneSidedMaxFlag returns a boolean if a field has been set.

### GetOneSidedMinFlag

`func (o *ToleranceTypesApiListToleranceTypesItem) GetOneSidedMinFlag() bool`

GetOneSidedMinFlag returns the OneSidedMinFlag field if non-nil, zero value otherwise.

### GetOneSidedMinFlagOk

`func (o *ToleranceTypesApiListToleranceTypesItem) GetOneSidedMinFlagOk() (*bool, bool)`

GetOneSidedMinFlagOk returns a tuple with the OneSidedMinFlag field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOneSidedMinFlag

`func (o *ToleranceTypesApiListToleranceTypesItem) SetOneSidedMinFlag(v bool)`

SetOneSidedMinFlag sets OneSidedMinFlag field to given value.

### HasOneSidedMinFlag

`func (o *ToleranceTypesApiListToleranceTypesItem) HasOneSidedMinFlag() bool`

HasOneSidedMinFlag returns a boolean if a field has been set.

### GetOneSidedShowTargetFlag

`func (o *ToleranceTypesApiListToleranceTypesItem) GetOneSidedShowTargetFlag() bool`

GetOneSidedShowTargetFlag returns the OneSidedShowTargetFlag field if non-nil, zero value otherwise.

### GetOneSidedShowTargetFlagOk

`func (o *ToleranceTypesApiListToleranceTypesItem) GetOneSidedShowTargetFlagOk() (*bool, bool)`

GetOneSidedShowTargetFlagOk returns a tuple with the OneSidedShowTargetFlag field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOneSidedShowTargetFlag

`func (o *ToleranceTypesApiListToleranceTypesItem) SetOneSidedShowTargetFlag(v bool)`

SetOneSidedShowTargetFlag sets OneSidedShowTargetFlag field to given value.

### HasOneSidedShowTargetFlag

`func (o *ToleranceTypesApiListToleranceTypesItem) HasOneSidedShowTargetFlag() bool`

HasOneSidedShowTargetFlag returns a boolean if a field has been set.

### GetTargetOnlyFlag

`func (o *ToleranceTypesApiListToleranceTypesItem) GetTargetOnlyFlag() bool`

GetTargetOnlyFlag returns the TargetOnlyFlag field if non-nil, zero value otherwise.

### GetTargetOnlyFlagOk

`func (o *ToleranceTypesApiListToleranceTypesItem) GetTargetOnlyFlagOk() (*bool, bool)`

GetTargetOnlyFlagOk returns a tuple with the TargetOnlyFlag field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetOnlyFlag

`func (o *ToleranceTypesApiListToleranceTypesItem) SetTargetOnlyFlag(v bool)`

SetTargetOnlyFlag sets TargetOnlyFlag field to given value.

### HasTargetOnlyFlag

`func (o *ToleranceTypesApiListToleranceTypesItem) HasTargetOnlyFlag() bool`

HasTargetOnlyFlag returns a boolean if a field has been set.

### GetTextOnlyFlag

`func (o *ToleranceTypesApiListToleranceTypesItem) GetTextOnlyFlag() bool`

GetTextOnlyFlag returns the TextOnlyFlag field if non-nil, zero value otherwise.

### GetTextOnlyFlagOk

`func (o *ToleranceTypesApiListToleranceTypesItem) GetTextOnlyFlagOk() (*bool, bool)`

GetTextOnlyFlagOk returns a tuple with the TextOnlyFlag field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTextOnlyFlag

`func (o *ToleranceTypesApiListToleranceTypesItem) SetTextOnlyFlag(v bool)`

SetTextOnlyFlag sets TextOnlyFlag field to given value.

### HasTextOnlyFlag

`func (o *ToleranceTypesApiListToleranceTypesItem) HasTextOnlyFlag() bool`

HasTextOnlyFlag returns a boolean if a field has been set.

### GetDefault

`func (o *ToleranceTypesApiListToleranceTypesItem) GetDefault() bool`

GetDefault returns the Default field if non-nil, zero value otherwise.

### GetDefaultOk

`func (o *ToleranceTypesApiListToleranceTypesItem) GetDefaultOk() (*bool, bool)`

GetDefaultOk returns a tuple with the Default field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefault

`func (o *ToleranceTypesApiListToleranceTypesItem) SetDefault(v bool)`

SetDefault sets Default field to given value.

### HasDefault

`func (o *ToleranceTypesApiListToleranceTypesItem) HasDefault() bool`

HasDefault returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


