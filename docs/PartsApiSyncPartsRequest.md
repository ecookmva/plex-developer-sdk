# PartsApiSyncPartsRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | A unique identifier for a part. This will be automatically generated if omitted from the request. | [optional] 
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

### NewPartsApiSyncPartsRequest

`func NewPartsApiSyncPartsRequest() *PartsApiSyncPartsRequest`

NewPartsApiSyncPartsRequest instantiates a new PartsApiSyncPartsRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartsApiSyncPartsRequestWithDefaults

`func NewPartsApiSyncPartsRequestWithDefaults() *PartsApiSyncPartsRequest`

NewPartsApiSyncPartsRequestWithDefaults instantiates a new PartsApiSyncPartsRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *PartsApiSyncPartsRequest) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PartsApiSyncPartsRequest) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PartsApiSyncPartsRequest) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *PartsApiSyncPartsRequest) HasId() bool`

HasId returns a boolean if a field has been set.

### GetNumber

`func (o *PartsApiSyncPartsRequest) GetNumber() string`

GetNumber returns the Number field if non-nil, zero value otherwise.

### GetNumberOk

`func (o *PartsApiSyncPartsRequest) GetNumberOk() (*string, bool)`

GetNumberOk returns a tuple with the Number field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumber

`func (o *PartsApiSyncPartsRequest) SetNumber(v string)`

SetNumber sets Number field to given value.

### HasNumber

`func (o *PartsApiSyncPartsRequest) HasNumber() bool`

HasNumber returns a boolean if a field has been set.

### GetName

`func (o *PartsApiSyncPartsRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PartsApiSyncPartsRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PartsApiSyncPartsRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *PartsApiSyncPartsRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### GetRevision

`func (o *PartsApiSyncPartsRequest) GetRevision() string`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *PartsApiSyncPartsRequest) GetRevisionOk() (*string, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *PartsApiSyncPartsRequest) SetRevision(v string)`

SetRevision sets Revision field to given value.

### HasRevision

`func (o *PartsApiSyncPartsRequest) HasRevision() bool`

HasRevision returns a boolean if a field has been set.

### GetDescription

`func (o *PartsApiSyncPartsRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *PartsApiSyncPartsRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *PartsApiSyncPartsRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *PartsApiSyncPartsRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetType

`func (o *PartsApiSyncPartsRequest) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *PartsApiSyncPartsRequest) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *PartsApiSyncPartsRequest) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *PartsApiSyncPartsRequest) HasType() bool`

HasType returns a boolean if a field has been set.

### GetGroup

`func (o *PartsApiSyncPartsRequest) GetGroup() string`

GetGroup returns the Group field if non-nil, zero value otherwise.

### GetGroupOk

`func (o *PartsApiSyncPartsRequest) GetGroupOk() (*string, bool)`

GetGroupOk returns a tuple with the Group field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroup

`func (o *PartsApiSyncPartsRequest) SetGroup(v string)`

SetGroup sets Group field to given value.

### HasGroup

`func (o *PartsApiSyncPartsRequest) HasGroup() bool`

HasGroup returns a boolean if a field has been set.

### GetSource

`func (o *PartsApiSyncPartsRequest) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *PartsApiSyncPartsRequest) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *PartsApiSyncPartsRequest) SetSource(v string)`

SetSource sets Source field to given value.

### HasSource

`func (o *PartsApiSyncPartsRequest) HasSource() bool`

HasSource returns a boolean if a field has been set.

### GetProductType

`func (o *PartsApiSyncPartsRequest) GetProductType() string`

GetProductType returns the ProductType field if non-nil, zero value otherwise.

### GetProductTypeOk

`func (o *PartsApiSyncPartsRequest) GetProductTypeOk() (*string, bool)`

GetProductTypeOk returns a tuple with the ProductType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductType

`func (o *PartsApiSyncPartsRequest) SetProductType(v string)`

SetProductType sets ProductType field to given value.

### HasProductType

`func (o *PartsApiSyncPartsRequest) HasProductType() bool`

HasProductType returns a boolean if a field has been set.

### GetStatus

`func (o *PartsApiSyncPartsRequest) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PartsApiSyncPartsRequest) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PartsApiSyncPartsRequest) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *PartsApiSyncPartsRequest) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetNote

`func (o *PartsApiSyncPartsRequest) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *PartsApiSyncPartsRequest) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *PartsApiSyncPartsRequest) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *PartsApiSyncPartsRequest) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetLeadTimeDays

`func (o *PartsApiSyncPartsRequest) GetLeadTimeDays() int32`

GetLeadTimeDays returns the LeadTimeDays field if non-nil, zero value otherwise.

### GetLeadTimeDaysOk

`func (o *PartsApiSyncPartsRequest) GetLeadTimeDaysOk() (*int32, bool)`

GetLeadTimeDaysOk returns a tuple with the LeadTimeDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeadTimeDays

`func (o *PartsApiSyncPartsRequest) SetLeadTimeDays(v int32)`

SetLeadTimeDays sets LeadTimeDays field to given value.

### HasLeadTimeDays

`func (o *PartsApiSyncPartsRequest) HasLeadTimeDays() bool`

HasLeadTimeDays returns a boolean if a field has been set.

### GetBuildingCode

`func (o *PartsApiSyncPartsRequest) GetBuildingCode() string`

GetBuildingCode returns the BuildingCode field if non-nil, zero value otherwise.

### GetBuildingCodeOk

`func (o *PartsApiSyncPartsRequest) GetBuildingCodeOk() (*string, bool)`

GetBuildingCodeOk returns a tuple with the BuildingCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildingCode

`func (o *PartsApiSyncPartsRequest) SetBuildingCode(v string)`

SetBuildingCode sets BuildingCode field to given value.

### HasBuildingCode

`func (o *PartsApiSyncPartsRequest) HasBuildingCode() bool`

HasBuildingCode returns a boolean if a field has been set.

### GetAllergens

`func (o *PartsApiSyncPartsRequest) GetAllergens() []string`

GetAllergens returns the Allergens field if non-nil, zero value otherwise.

### GetAllergensOk

`func (o *PartsApiSyncPartsRequest) GetAllergensOk() (*[]string, bool)`

GetAllergensOk returns a tuple with the Allergens field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllergens

`func (o *PartsApiSyncPartsRequest) SetAllergens(v []string)`

SetAllergens sets Allergens field to given value.

### HasAllergens

`func (o *PartsApiSyncPartsRequest) HasAllergens() bool`

HasAllergens returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


