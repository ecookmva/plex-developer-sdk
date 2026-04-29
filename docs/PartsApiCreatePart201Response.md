# PartsApiCreatePart201Response

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

### NewPartsApiCreatePart201Response

`func NewPartsApiCreatePart201Response() *PartsApiCreatePart201Response`

NewPartsApiCreatePart201Response instantiates a new PartsApiCreatePart201Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartsApiCreatePart201ResponseWithDefaults

`func NewPartsApiCreatePart201ResponseWithDefaults() *PartsApiCreatePart201Response`

NewPartsApiCreatePart201ResponseWithDefaults instantiates a new PartsApiCreatePart201Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *PartsApiCreatePart201Response) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PartsApiCreatePart201Response) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PartsApiCreatePart201Response) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *PartsApiCreatePart201Response) HasId() bool`

HasId returns a boolean if a field has been set.

### GetNumber

`func (o *PartsApiCreatePart201Response) GetNumber() string`

GetNumber returns the Number field if non-nil, zero value otherwise.

### GetNumberOk

`func (o *PartsApiCreatePart201Response) GetNumberOk() (*string, bool)`

GetNumberOk returns a tuple with the Number field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumber

`func (o *PartsApiCreatePart201Response) SetNumber(v string)`

SetNumber sets Number field to given value.

### HasNumber

`func (o *PartsApiCreatePart201Response) HasNumber() bool`

HasNumber returns a boolean if a field has been set.

### GetName

`func (o *PartsApiCreatePart201Response) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PartsApiCreatePart201Response) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PartsApiCreatePart201Response) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *PartsApiCreatePart201Response) HasName() bool`

HasName returns a boolean if a field has been set.

### GetRevision

`func (o *PartsApiCreatePart201Response) GetRevision() string`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *PartsApiCreatePart201Response) GetRevisionOk() (*string, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *PartsApiCreatePart201Response) SetRevision(v string)`

SetRevision sets Revision field to given value.

### HasRevision

`func (o *PartsApiCreatePart201Response) HasRevision() bool`

HasRevision returns a boolean if a field has been set.

### GetDescription

`func (o *PartsApiCreatePart201Response) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *PartsApiCreatePart201Response) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *PartsApiCreatePart201Response) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *PartsApiCreatePart201Response) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetType

`func (o *PartsApiCreatePart201Response) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *PartsApiCreatePart201Response) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *PartsApiCreatePart201Response) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *PartsApiCreatePart201Response) HasType() bool`

HasType returns a boolean if a field has been set.

### GetGroup

`func (o *PartsApiCreatePart201Response) GetGroup() string`

GetGroup returns the Group field if non-nil, zero value otherwise.

### GetGroupOk

`func (o *PartsApiCreatePart201Response) GetGroupOk() (*string, bool)`

GetGroupOk returns a tuple with the Group field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroup

`func (o *PartsApiCreatePart201Response) SetGroup(v string)`

SetGroup sets Group field to given value.

### HasGroup

`func (o *PartsApiCreatePart201Response) HasGroup() bool`

HasGroup returns a boolean if a field has been set.

### GetSource

`func (o *PartsApiCreatePart201Response) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *PartsApiCreatePart201Response) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *PartsApiCreatePart201Response) SetSource(v string)`

SetSource sets Source field to given value.

### HasSource

`func (o *PartsApiCreatePart201Response) HasSource() bool`

HasSource returns a boolean if a field has been set.

### GetProductType

`func (o *PartsApiCreatePart201Response) GetProductType() string`

GetProductType returns the ProductType field if non-nil, zero value otherwise.

### GetProductTypeOk

`func (o *PartsApiCreatePart201Response) GetProductTypeOk() (*string, bool)`

GetProductTypeOk returns a tuple with the ProductType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductType

`func (o *PartsApiCreatePart201Response) SetProductType(v string)`

SetProductType sets ProductType field to given value.

### HasProductType

`func (o *PartsApiCreatePart201Response) HasProductType() bool`

HasProductType returns a boolean if a field has been set.

### GetStatus

`func (o *PartsApiCreatePart201Response) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PartsApiCreatePart201Response) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PartsApiCreatePart201Response) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *PartsApiCreatePart201Response) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetNote

`func (o *PartsApiCreatePart201Response) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *PartsApiCreatePart201Response) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *PartsApiCreatePart201Response) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *PartsApiCreatePart201Response) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetLeadTimeDays

`func (o *PartsApiCreatePart201Response) GetLeadTimeDays() float64`

GetLeadTimeDays returns the LeadTimeDays field if non-nil, zero value otherwise.

### GetLeadTimeDaysOk

`func (o *PartsApiCreatePart201Response) GetLeadTimeDaysOk() (*float64, bool)`

GetLeadTimeDaysOk returns a tuple with the LeadTimeDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeadTimeDays

`func (o *PartsApiCreatePart201Response) SetLeadTimeDays(v float64)`

SetLeadTimeDays sets LeadTimeDays field to given value.

### HasLeadTimeDays

`func (o *PartsApiCreatePart201Response) HasLeadTimeDays() bool`

HasLeadTimeDays returns a boolean if a field has been set.

### GetBuildingCode

`func (o *PartsApiCreatePart201Response) GetBuildingCode() string`

GetBuildingCode returns the BuildingCode field if non-nil, zero value otherwise.

### GetBuildingCodeOk

`func (o *PartsApiCreatePart201Response) GetBuildingCodeOk() (*string, bool)`

GetBuildingCodeOk returns a tuple with the BuildingCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildingCode

`func (o *PartsApiCreatePart201Response) SetBuildingCode(v string)`

SetBuildingCode sets BuildingCode field to given value.

### HasBuildingCode

`func (o *PartsApiCreatePart201Response) HasBuildingCode() bool`

HasBuildingCode returns a boolean if a field has been set.

### GetCreatedById

`func (o *PartsApiCreatePart201Response) GetCreatedById() string`

GetCreatedById returns the CreatedById field if non-nil, zero value otherwise.

### GetCreatedByIdOk

`func (o *PartsApiCreatePart201Response) GetCreatedByIdOk() (*string, bool)`

GetCreatedByIdOk returns a tuple with the CreatedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedById

`func (o *PartsApiCreatePart201Response) SetCreatedById(v string)`

SetCreatedById sets CreatedById field to given value.

### HasCreatedById

`func (o *PartsApiCreatePart201Response) HasCreatedById() bool`

HasCreatedById returns a boolean if a field has been set.

### GetCreatedDate

`func (o *PartsApiCreatePart201Response) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *PartsApiCreatePart201Response) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *PartsApiCreatePart201Response) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *PartsApiCreatePart201Response) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.

### GetModifiedById

`func (o *PartsApiCreatePart201Response) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *PartsApiCreatePart201Response) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *PartsApiCreatePart201Response) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *PartsApiCreatePart201Response) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetModifiedDate

`func (o *PartsApiCreatePart201Response) GetModifiedDate() time.Time`

GetModifiedDate returns the ModifiedDate field if non-nil, zero value otherwise.

### GetModifiedDateOk

`func (o *PartsApiCreatePart201Response) GetModifiedDateOk() (*time.Time, bool)`

GetModifiedDateOk returns a tuple with the ModifiedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDate

`func (o *PartsApiCreatePart201Response) SetModifiedDate(v time.Time)`

SetModifiedDate sets ModifiedDate field to given value.

### HasModifiedDate

`func (o *PartsApiCreatePart201Response) HasModifiedDate() bool`

HasModifiedDate returns a boolean if a field has been set.

### GetAllergens

`func (o *PartsApiCreatePart201Response) GetAllergens() []string`

GetAllergens returns the Allergens field if non-nil, zero value otherwise.

### GetAllergensOk

`func (o *PartsApiCreatePart201Response) GetAllergensOk() (*[]string, bool)`

GetAllergensOk returns a tuple with the Allergens field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllergens

`func (o *PartsApiCreatePart201Response) SetAllergens(v []string)`

SetAllergens sets Allergens field to given value.

### HasAllergens

`func (o *PartsApiCreatePart201Response) HasAllergens() bool`

HasAllergens returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


