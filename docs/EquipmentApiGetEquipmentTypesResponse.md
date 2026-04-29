# EquipmentApiGetEquipmentTypesResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | An ID representing the Equipment Type. | [optional] 
**EquipmentType** | Pointer to **string** | The name of the Equipment Type. | [optional] 
**Group** | Pointer to **string** | The group of the Equipment Type. | [optional] 
**PartSectionUse** | Pointer to **bool** | The Part Section Use Flag. | [optional] 
**MaintenanceReadingUse** | Pointer to **bool** | The Maintenance Reading Use Flag. | [optional] 
**EquipmentLinkCascade** | Pointer to **bool** | The Equipment Link Cascade Flag. | [optional] 
**Subsystems** | Pointer to **[]string** | The list of associated Subsystems. | [optional] 
**EquipmentAttributes** | Pointer to [**[]EquipmentAttributesItem1**](EquipmentAttributesItem1.md) | The list of associated Equipment Attributes. | [optional] 

## Methods

### NewEquipmentApiGetEquipmentTypesResponse

`func NewEquipmentApiGetEquipmentTypesResponse() *EquipmentApiGetEquipmentTypesResponse`

NewEquipmentApiGetEquipmentTypesResponse instantiates a new EquipmentApiGetEquipmentTypesResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEquipmentApiGetEquipmentTypesResponseWithDefaults

`func NewEquipmentApiGetEquipmentTypesResponseWithDefaults() *EquipmentApiGetEquipmentTypesResponse`

NewEquipmentApiGetEquipmentTypesResponseWithDefaults instantiates a new EquipmentApiGetEquipmentTypesResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *EquipmentApiGetEquipmentTypesResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *EquipmentApiGetEquipmentTypesResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *EquipmentApiGetEquipmentTypesResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *EquipmentApiGetEquipmentTypesResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetEquipmentType

`func (o *EquipmentApiGetEquipmentTypesResponse) GetEquipmentType() string`

GetEquipmentType returns the EquipmentType field if non-nil, zero value otherwise.

### GetEquipmentTypeOk

`func (o *EquipmentApiGetEquipmentTypesResponse) GetEquipmentTypeOk() (*string, bool)`

GetEquipmentTypeOk returns a tuple with the EquipmentType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEquipmentType

`func (o *EquipmentApiGetEquipmentTypesResponse) SetEquipmentType(v string)`

SetEquipmentType sets EquipmentType field to given value.

### HasEquipmentType

`func (o *EquipmentApiGetEquipmentTypesResponse) HasEquipmentType() bool`

HasEquipmentType returns a boolean if a field has been set.

### GetGroup

`func (o *EquipmentApiGetEquipmentTypesResponse) GetGroup() string`

GetGroup returns the Group field if non-nil, zero value otherwise.

### GetGroupOk

`func (o *EquipmentApiGetEquipmentTypesResponse) GetGroupOk() (*string, bool)`

GetGroupOk returns a tuple with the Group field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroup

`func (o *EquipmentApiGetEquipmentTypesResponse) SetGroup(v string)`

SetGroup sets Group field to given value.

### HasGroup

`func (o *EquipmentApiGetEquipmentTypesResponse) HasGroup() bool`

HasGroup returns a boolean if a field has been set.

### GetPartSectionUse

`func (o *EquipmentApiGetEquipmentTypesResponse) GetPartSectionUse() bool`

GetPartSectionUse returns the PartSectionUse field if non-nil, zero value otherwise.

### GetPartSectionUseOk

`func (o *EquipmentApiGetEquipmentTypesResponse) GetPartSectionUseOk() (*bool, bool)`

GetPartSectionUseOk returns a tuple with the PartSectionUse field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartSectionUse

`func (o *EquipmentApiGetEquipmentTypesResponse) SetPartSectionUse(v bool)`

SetPartSectionUse sets PartSectionUse field to given value.

### HasPartSectionUse

`func (o *EquipmentApiGetEquipmentTypesResponse) HasPartSectionUse() bool`

HasPartSectionUse returns a boolean if a field has been set.

### GetMaintenanceReadingUse

`func (o *EquipmentApiGetEquipmentTypesResponse) GetMaintenanceReadingUse() bool`

GetMaintenanceReadingUse returns the MaintenanceReadingUse field if non-nil, zero value otherwise.

### GetMaintenanceReadingUseOk

`func (o *EquipmentApiGetEquipmentTypesResponse) GetMaintenanceReadingUseOk() (*bool, bool)`

GetMaintenanceReadingUseOk returns a tuple with the MaintenanceReadingUse field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaintenanceReadingUse

`func (o *EquipmentApiGetEquipmentTypesResponse) SetMaintenanceReadingUse(v bool)`

SetMaintenanceReadingUse sets MaintenanceReadingUse field to given value.

### HasMaintenanceReadingUse

`func (o *EquipmentApiGetEquipmentTypesResponse) HasMaintenanceReadingUse() bool`

HasMaintenanceReadingUse returns a boolean if a field has been set.

### GetEquipmentLinkCascade

`func (o *EquipmentApiGetEquipmentTypesResponse) GetEquipmentLinkCascade() bool`

GetEquipmentLinkCascade returns the EquipmentLinkCascade field if non-nil, zero value otherwise.

### GetEquipmentLinkCascadeOk

`func (o *EquipmentApiGetEquipmentTypesResponse) GetEquipmentLinkCascadeOk() (*bool, bool)`

GetEquipmentLinkCascadeOk returns a tuple with the EquipmentLinkCascade field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEquipmentLinkCascade

`func (o *EquipmentApiGetEquipmentTypesResponse) SetEquipmentLinkCascade(v bool)`

SetEquipmentLinkCascade sets EquipmentLinkCascade field to given value.

### HasEquipmentLinkCascade

`func (o *EquipmentApiGetEquipmentTypesResponse) HasEquipmentLinkCascade() bool`

HasEquipmentLinkCascade returns a boolean if a field has been set.

### GetSubsystems

`func (o *EquipmentApiGetEquipmentTypesResponse) GetSubsystems() []string`

GetSubsystems returns the Subsystems field if non-nil, zero value otherwise.

### GetSubsystemsOk

`func (o *EquipmentApiGetEquipmentTypesResponse) GetSubsystemsOk() (*[]string, bool)`

GetSubsystemsOk returns a tuple with the Subsystems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubsystems

`func (o *EquipmentApiGetEquipmentTypesResponse) SetSubsystems(v []string)`

SetSubsystems sets Subsystems field to given value.

### HasSubsystems

`func (o *EquipmentApiGetEquipmentTypesResponse) HasSubsystems() bool`

HasSubsystems returns a boolean if a field has been set.

### GetEquipmentAttributes

`func (o *EquipmentApiGetEquipmentTypesResponse) GetEquipmentAttributes() []EquipmentAttributesItem1`

GetEquipmentAttributes returns the EquipmentAttributes field if non-nil, zero value otherwise.

### GetEquipmentAttributesOk

`func (o *EquipmentApiGetEquipmentTypesResponse) GetEquipmentAttributesOk() (*[]EquipmentAttributesItem1, bool)`

GetEquipmentAttributesOk returns a tuple with the EquipmentAttributes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEquipmentAttributes

`func (o *EquipmentApiGetEquipmentTypesResponse) SetEquipmentAttributes(v []EquipmentAttributesItem1)`

SetEquipmentAttributes sets EquipmentAttributes field to given value.

### HasEquipmentAttributes

`func (o *EquipmentApiGetEquipmentTypesResponse) HasEquipmentAttributes() bool`

HasEquipmentAttributes returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


