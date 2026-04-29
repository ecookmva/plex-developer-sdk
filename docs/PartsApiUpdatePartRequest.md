# PartsApiUpdatePartRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Number** | Pointer to **string** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Revision** | Pointer to **string** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**Type** | Pointer to **string** | Setup Table: Part_Type | [optional] 
**Group** | Pointer to **string** | Setup Table: Part_Group | [optional] 
**Source** | Pointer to **string** | Setup Table: Part_Source | [optional] 
**ProductType** | Pointer to **string** | Setup Table: Part_Product_Type | [optional] 
**Status** | Pointer to **string** | Setup Table: Part_Status | [optional] 
**Note** | Pointer to **string** |  | [optional] 
**LeadTimeDays** | Pointer to **int32** |  | [optional] 
**BuildingCode** | Pointer to **string** | Setup Table: Building | [optional] 
**Allergens** | Pointer to **[]string** | Setup Table: Allergen. HACCP Module must be enabled. | [optional] 

## Methods

### NewPartsApiUpdatePartRequest

`func NewPartsApiUpdatePartRequest() *PartsApiUpdatePartRequest`

NewPartsApiUpdatePartRequest instantiates a new PartsApiUpdatePartRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartsApiUpdatePartRequestWithDefaults

`func NewPartsApiUpdatePartRequestWithDefaults() *PartsApiUpdatePartRequest`

NewPartsApiUpdatePartRequestWithDefaults instantiates a new PartsApiUpdatePartRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNumber

`func (o *PartsApiUpdatePartRequest) GetNumber() string`

GetNumber returns the Number field if non-nil, zero value otherwise.

### GetNumberOk

`func (o *PartsApiUpdatePartRequest) GetNumberOk() (*string, bool)`

GetNumberOk returns a tuple with the Number field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumber

`func (o *PartsApiUpdatePartRequest) SetNumber(v string)`

SetNumber sets Number field to given value.

### HasNumber

`func (o *PartsApiUpdatePartRequest) HasNumber() bool`

HasNumber returns a boolean if a field has been set.

### GetName

`func (o *PartsApiUpdatePartRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PartsApiUpdatePartRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PartsApiUpdatePartRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *PartsApiUpdatePartRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### GetRevision

`func (o *PartsApiUpdatePartRequest) GetRevision() string`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *PartsApiUpdatePartRequest) GetRevisionOk() (*string, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *PartsApiUpdatePartRequest) SetRevision(v string)`

SetRevision sets Revision field to given value.

### HasRevision

`func (o *PartsApiUpdatePartRequest) HasRevision() bool`

HasRevision returns a boolean if a field has been set.

### GetDescription

`func (o *PartsApiUpdatePartRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *PartsApiUpdatePartRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *PartsApiUpdatePartRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *PartsApiUpdatePartRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetType

`func (o *PartsApiUpdatePartRequest) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *PartsApiUpdatePartRequest) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *PartsApiUpdatePartRequest) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *PartsApiUpdatePartRequest) HasType() bool`

HasType returns a boolean if a field has been set.

### GetGroup

`func (o *PartsApiUpdatePartRequest) GetGroup() string`

GetGroup returns the Group field if non-nil, zero value otherwise.

### GetGroupOk

`func (o *PartsApiUpdatePartRequest) GetGroupOk() (*string, bool)`

GetGroupOk returns a tuple with the Group field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroup

`func (o *PartsApiUpdatePartRequest) SetGroup(v string)`

SetGroup sets Group field to given value.

### HasGroup

`func (o *PartsApiUpdatePartRequest) HasGroup() bool`

HasGroup returns a boolean if a field has been set.

### GetSource

`func (o *PartsApiUpdatePartRequest) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *PartsApiUpdatePartRequest) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *PartsApiUpdatePartRequest) SetSource(v string)`

SetSource sets Source field to given value.

### HasSource

`func (o *PartsApiUpdatePartRequest) HasSource() bool`

HasSource returns a boolean if a field has been set.

### GetProductType

`func (o *PartsApiUpdatePartRequest) GetProductType() string`

GetProductType returns the ProductType field if non-nil, zero value otherwise.

### GetProductTypeOk

`func (o *PartsApiUpdatePartRequest) GetProductTypeOk() (*string, bool)`

GetProductTypeOk returns a tuple with the ProductType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductType

`func (o *PartsApiUpdatePartRequest) SetProductType(v string)`

SetProductType sets ProductType field to given value.

### HasProductType

`func (o *PartsApiUpdatePartRequest) HasProductType() bool`

HasProductType returns a boolean if a field has been set.

### GetStatus

`func (o *PartsApiUpdatePartRequest) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PartsApiUpdatePartRequest) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PartsApiUpdatePartRequest) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *PartsApiUpdatePartRequest) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetNote

`func (o *PartsApiUpdatePartRequest) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *PartsApiUpdatePartRequest) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *PartsApiUpdatePartRequest) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *PartsApiUpdatePartRequest) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetLeadTimeDays

`func (o *PartsApiUpdatePartRequest) GetLeadTimeDays() int32`

GetLeadTimeDays returns the LeadTimeDays field if non-nil, zero value otherwise.

### GetLeadTimeDaysOk

`func (o *PartsApiUpdatePartRequest) GetLeadTimeDaysOk() (*int32, bool)`

GetLeadTimeDaysOk returns a tuple with the LeadTimeDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeadTimeDays

`func (o *PartsApiUpdatePartRequest) SetLeadTimeDays(v int32)`

SetLeadTimeDays sets LeadTimeDays field to given value.

### HasLeadTimeDays

`func (o *PartsApiUpdatePartRequest) HasLeadTimeDays() bool`

HasLeadTimeDays returns a boolean if a field has been set.

### GetBuildingCode

`func (o *PartsApiUpdatePartRequest) GetBuildingCode() string`

GetBuildingCode returns the BuildingCode field if non-nil, zero value otherwise.

### GetBuildingCodeOk

`func (o *PartsApiUpdatePartRequest) GetBuildingCodeOk() (*string, bool)`

GetBuildingCodeOk returns a tuple with the BuildingCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildingCode

`func (o *PartsApiUpdatePartRequest) SetBuildingCode(v string)`

SetBuildingCode sets BuildingCode field to given value.

### HasBuildingCode

`func (o *PartsApiUpdatePartRequest) HasBuildingCode() bool`

HasBuildingCode returns a boolean if a field has been set.

### GetAllergens

`func (o *PartsApiUpdatePartRequest) GetAllergens() []string`

GetAllergens returns the Allergens field if non-nil, zero value otherwise.

### GetAllergensOk

`func (o *PartsApiUpdatePartRequest) GetAllergensOk() (*[]string, bool)`

GetAllergensOk returns a tuple with the Allergens field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllergens

`func (o *PartsApiUpdatePartRequest) SetAllergens(v []string)`

SetAllergens sets Allergens field to given value.

### HasAllergens

`func (o *PartsApiUpdatePartRequest) HasAllergens() bool`

HasAllergens returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


