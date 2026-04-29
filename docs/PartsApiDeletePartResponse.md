# PartsApiDeletePartResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | A unique identifier for a part. | [optional] 
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
**LeadTimeDays** | Pointer to **float64** |  | [optional] 
**BuildingCode** | Pointer to **string** | Setup Table: Building | [optional] 
**CreatedById** | Pointer to **string** | IAM Account ID | [optional] 
**CreatedDate** | Pointer to **time.Time** |  | [optional] 
**ModifiedById** | Pointer to **string** | IAM Account ID | [optional] 
**ModifiedDate** | Pointer to **time.Time** |  | [optional] 
**Allergens** | Pointer to **[]string** | Setup Table: Allergen. HACCP Module must be enabled. | [optional] 

## Methods

### NewPartsApiDeletePartResponse

`func NewPartsApiDeletePartResponse() *PartsApiDeletePartResponse`

NewPartsApiDeletePartResponse instantiates a new PartsApiDeletePartResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartsApiDeletePartResponseWithDefaults

`func NewPartsApiDeletePartResponseWithDefaults() *PartsApiDeletePartResponse`

NewPartsApiDeletePartResponseWithDefaults instantiates a new PartsApiDeletePartResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *PartsApiDeletePartResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PartsApiDeletePartResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PartsApiDeletePartResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *PartsApiDeletePartResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetNumber

`func (o *PartsApiDeletePartResponse) GetNumber() string`

GetNumber returns the Number field if non-nil, zero value otherwise.

### GetNumberOk

`func (o *PartsApiDeletePartResponse) GetNumberOk() (*string, bool)`

GetNumberOk returns a tuple with the Number field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumber

`func (o *PartsApiDeletePartResponse) SetNumber(v string)`

SetNumber sets Number field to given value.

### HasNumber

`func (o *PartsApiDeletePartResponse) HasNumber() bool`

HasNumber returns a boolean if a field has been set.

### GetName

`func (o *PartsApiDeletePartResponse) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PartsApiDeletePartResponse) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PartsApiDeletePartResponse) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *PartsApiDeletePartResponse) HasName() bool`

HasName returns a boolean if a field has been set.

### GetRevision

`func (o *PartsApiDeletePartResponse) GetRevision() string`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *PartsApiDeletePartResponse) GetRevisionOk() (*string, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *PartsApiDeletePartResponse) SetRevision(v string)`

SetRevision sets Revision field to given value.

### HasRevision

`func (o *PartsApiDeletePartResponse) HasRevision() bool`

HasRevision returns a boolean if a field has been set.

### GetDescription

`func (o *PartsApiDeletePartResponse) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *PartsApiDeletePartResponse) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *PartsApiDeletePartResponse) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *PartsApiDeletePartResponse) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetType

`func (o *PartsApiDeletePartResponse) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *PartsApiDeletePartResponse) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *PartsApiDeletePartResponse) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *PartsApiDeletePartResponse) HasType() bool`

HasType returns a boolean if a field has been set.

### GetGroup

`func (o *PartsApiDeletePartResponse) GetGroup() string`

GetGroup returns the Group field if non-nil, zero value otherwise.

### GetGroupOk

`func (o *PartsApiDeletePartResponse) GetGroupOk() (*string, bool)`

GetGroupOk returns a tuple with the Group field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroup

`func (o *PartsApiDeletePartResponse) SetGroup(v string)`

SetGroup sets Group field to given value.

### HasGroup

`func (o *PartsApiDeletePartResponse) HasGroup() bool`

HasGroup returns a boolean if a field has been set.

### GetSource

`func (o *PartsApiDeletePartResponse) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *PartsApiDeletePartResponse) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *PartsApiDeletePartResponse) SetSource(v string)`

SetSource sets Source field to given value.

### HasSource

`func (o *PartsApiDeletePartResponse) HasSource() bool`

HasSource returns a boolean if a field has been set.

### GetProductType

`func (o *PartsApiDeletePartResponse) GetProductType() string`

GetProductType returns the ProductType field if non-nil, zero value otherwise.

### GetProductTypeOk

`func (o *PartsApiDeletePartResponse) GetProductTypeOk() (*string, bool)`

GetProductTypeOk returns a tuple with the ProductType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductType

`func (o *PartsApiDeletePartResponse) SetProductType(v string)`

SetProductType sets ProductType field to given value.

### HasProductType

`func (o *PartsApiDeletePartResponse) HasProductType() bool`

HasProductType returns a boolean if a field has been set.

### GetStatus

`func (o *PartsApiDeletePartResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PartsApiDeletePartResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PartsApiDeletePartResponse) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *PartsApiDeletePartResponse) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetNote

`func (o *PartsApiDeletePartResponse) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *PartsApiDeletePartResponse) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *PartsApiDeletePartResponse) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *PartsApiDeletePartResponse) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetLeadTimeDays

`func (o *PartsApiDeletePartResponse) GetLeadTimeDays() float64`

GetLeadTimeDays returns the LeadTimeDays field if non-nil, zero value otherwise.

### GetLeadTimeDaysOk

`func (o *PartsApiDeletePartResponse) GetLeadTimeDaysOk() (*float64, bool)`

GetLeadTimeDaysOk returns a tuple with the LeadTimeDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeadTimeDays

`func (o *PartsApiDeletePartResponse) SetLeadTimeDays(v float64)`

SetLeadTimeDays sets LeadTimeDays field to given value.

### HasLeadTimeDays

`func (o *PartsApiDeletePartResponse) HasLeadTimeDays() bool`

HasLeadTimeDays returns a boolean if a field has been set.

### GetBuildingCode

`func (o *PartsApiDeletePartResponse) GetBuildingCode() string`

GetBuildingCode returns the BuildingCode field if non-nil, zero value otherwise.

### GetBuildingCodeOk

`func (o *PartsApiDeletePartResponse) GetBuildingCodeOk() (*string, bool)`

GetBuildingCodeOk returns a tuple with the BuildingCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildingCode

`func (o *PartsApiDeletePartResponse) SetBuildingCode(v string)`

SetBuildingCode sets BuildingCode field to given value.

### HasBuildingCode

`func (o *PartsApiDeletePartResponse) HasBuildingCode() bool`

HasBuildingCode returns a boolean if a field has been set.

### GetCreatedById

`func (o *PartsApiDeletePartResponse) GetCreatedById() string`

GetCreatedById returns the CreatedById field if non-nil, zero value otherwise.

### GetCreatedByIdOk

`func (o *PartsApiDeletePartResponse) GetCreatedByIdOk() (*string, bool)`

GetCreatedByIdOk returns a tuple with the CreatedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedById

`func (o *PartsApiDeletePartResponse) SetCreatedById(v string)`

SetCreatedById sets CreatedById field to given value.

### HasCreatedById

`func (o *PartsApiDeletePartResponse) HasCreatedById() bool`

HasCreatedById returns a boolean if a field has been set.

### GetCreatedDate

`func (o *PartsApiDeletePartResponse) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *PartsApiDeletePartResponse) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *PartsApiDeletePartResponse) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *PartsApiDeletePartResponse) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.

### GetModifiedById

`func (o *PartsApiDeletePartResponse) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *PartsApiDeletePartResponse) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *PartsApiDeletePartResponse) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *PartsApiDeletePartResponse) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetModifiedDate

`func (o *PartsApiDeletePartResponse) GetModifiedDate() time.Time`

GetModifiedDate returns the ModifiedDate field if non-nil, zero value otherwise.

### GetModifiedDateOk

`func (o *PartsApiDeletePartResponse) GetModifiedDateOk() (*time.Time, bool)`

GetModifiedDateOk returns a tuple with the ModifiedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDate

`func (o *PartsApiDeletePartResponse) SetModifiedDate(v time.Time)`

SetModifiedDate sets ModifiedDate field to given value.

### HasModifiedDate

`func (o *PartsApiDeletePartResponse) HasModifiedDate() bool`

HasModifiedDate returns a boolean if a field has been set.

### GetAllergens

`func (o *PartsApiDeletePartResponse) GetAllergens() []string`

GetAllergens returns the Allergens field if non-nil, zero value otherwise.

### GetAllergensOk

`func (o *PartsApiDeletePartResponse) GetAllergensOk() (*[]string, bool)`

GetAllergensOk returns a tuple with the Allergens field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllergens

`func (o *PartsApiDeletePartResponse) SetAllergens(v []string)`

SetAllergens sets Allergens field to given value.

### HasAllergens

`func (o *PartsApiDeletePartResponse) HasAllergens() bool`

HasAllergens returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


