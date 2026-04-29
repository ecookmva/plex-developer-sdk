# SuppliersApiCreateSupplier201Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | A unique identifier for the Supplier. This will be automatically generated if omitted from the request. | [optional] 
**Code** | Pointer to **string** | The Supplier Code used in Plex to identify the supplier. This must be unique in the context of a tenant. | [optional] 
**OldCode** | Pointer to **string** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Language** | Pointer to **string** |  | [optional] 
**Category** | Pointer to **string** | Setup Table: Supplier_Category | [optional] 
**Status** | Pointer to **string** | Setup Table: Supplier_Status | [optional] 
**Type** | Pointer to **string** | Setup Table: Supplier_Type | [optional] 
**ParentSupplierId** | Pointer to **string** | The ID of a parent supplier. | [optional] 
**WebAddress** | Pointer to **string** |  | [optional] 
**ContactNote** | Pointer to **string** |  | [optional] 
**Note** | Pointer to **string** |  | [optional] 
**CreatedById** | Pointer to **string** | IAM Account ID | [optional] 
**CreatedDate** | Pointer to **time.Time** |  | [optional] 
**ModifiedById** | Pointer to **string** | IAM Account ID | [optional] 
**ModifiedDate** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewSuppliersApiCreateSupplier201Response

`func NewSuppliersApiCreateSupplier201Response() *SuppliersApiCreateSupplier201Response`

NewSuppliersApiCreateSupplier201Response instantiates a new SuppliersApiCreateSupplier201Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSuppliersApiCreateSupplier201ResponseWithDefaults

`func NewSuppliersApiCreateSupplier201ResponseWithDefaults() *SuppliersApiCreateSupplier201Response`

NewSuppliersApiCreateSupplier201ResponseWithDefaults instantiates a new SuppliersApiCreateSupplier201Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SuppliersApiCreateSupplier201Response) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SuppliersApiCreateSupplier201Response) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SuppliersApiCreateSupplier201Response) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *SuppliersApiCreateSupplier201Response) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCode

`func (o *SuppliersApiCreateSupplier201Response) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *SuppliersApiCreateSupplier201Response) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *SuppliersApiCreateSupplier201Response) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *SuppliersApiCreateSupplier201Response) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetOldCode

`func (o *SuppliersApiCreateSupplier201Response) GetOldCode() string`

GetOldCode returns the OldCode field if non-nil, zero value otherwise.

### GetOldCodeOk

`func (o *SuppliersApiCreateSupplier201Response) GetOldCodeOk() (*string, bool)`

GetOldCodeOk returns a tuple with the OldCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOldCode

`func (o *SuppliersApiCreateSupplier201Response) SetOldCode(v string)`

SetOldCode sets OldCode field to given value.

### HasOldCode

`func (o *SuppliersApiCreateSupplier201Response) HasOldCode() bool`

HasOldCode returns a boolean if a field has been set.

### GetName

`func (o *SuppliersApiCreateSupplier201Response) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *SuppliersApiCreateSupplier201Response) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *SuppliersApiCreateSupplier201Response) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *SuppliersApiCreateSupplier201Response) HasName() bool`

HasName returns a boolean if a field has been set.

### GetLanguage

`func (o *SuppliersApiCreateSupplier201Response) GetLanguage() string`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *SuppliersApiCreateSupplier201Response) GetLanguageOk() (*string, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *SuppliersApiCreateSupplier201Response) SetLanguage(v string)`

SetLanguage sets Language field to given value.

### HasLanguage

`func (o *SuppliersApiCreateSupplier201Response) HasLanguage() bool`

HasLanguage returns a boolean if a field has been set.

### GetCategory

`func (o *SuppliersApiCreateSupplier201Response) GetCategory() string`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *SuppliersApiCreateSupplier201Response) GetCategoryOk() (*string, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *SuppliersApiCreateSupplier201Response) SetCategory(v string)`

SetCategory sets Category field to given value.

### HasCategory

`func (o *SuppliersApiCreateSupplier201Response) HasCategory() bool`

HasCategory returns a boolean if a field has been set.

### GetStatus

`func (o *SuppliersApiCreateSupplier201Response) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *SuppliersApiCreateSupplier201Response) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *SuppliersApiCreateSupplier201Response) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *SuppliersApiCreateSupplier201Response) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetType

`func (o *SuppliersApiCreateSupplier201Response) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *SuppliersApiCreateSupplier201Response) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *SuppliersApiCreateSupplier201Response) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *SuppliersApiCreateSupplier201Response) HasType() bool`

HasType returns a boolean if a field has been set.

### GetParentSupplierId

`func (o *SuppliersApiCreateSupplier201Response) GetParentSupplierId() string`

GetParentSupplierId returns the ParentSupplierId field if non-nil, zero value otherwise.

### GetParentSupplierIdOk

`func (o *SuppliersApiCreateSupplier201Response) GetParentSupplierIdOk() (*string, bool)`

GetParentSupplierIdOk returns a tuple with the ParentSupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentSupplierId

`func (o *SuppliersApiCreateSupplier201Response) SetParentSupplierId(v string)`

SetParentSupplierId sets ParentSupplierId field to given value.

### HasParentSupplierId

`func (o *SuppliersApiCreateSupplier201Response) HasParentSupplierId() bool`

HasParentSupplierId returns a boolean if a field has been set.

### GetWebAddress

`func (o *SuppliersApiCreateSupplier201Response) GetWebAddress() string`

GetWebAddress returns the WebAddress field if non-nil, zero value otherwise.

### GetWebAddressOk

`func (o *SuppliersApiCreateSupplier201Response) GetWebAddressOk() (*string, bool)`

GetWebAddressOk returns a tuple with the WebAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebAddress

`func (o *SuppliersApiCreateSupplier201Response) SetWebAddress(v string)`

SetWebAddress sets WebAddress field to given value.

### HasWebAddress

`func (o *SuppliersApiCreateSupplier201Response) HasWebAddress() bool`

HasWebAddress returns a boolean if a field has been set.

### GetContactNote

`func (o *SuppliersApiCreateSupplier201Response) GetContactNote() string`

GetContactNote returns the ContactNote field if non-nil, zero value otherwise.

### GetContactNoteOk

`func (o *SuppliersApiCreateSupplier201Response) GetContactNoteOk() (*string, bool)`

GetContactNoteOk returns a tuple with the ContactNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactNote

`func (o *SuppliersApiCreateSupplier201Response) SetContactNote(v string)`

SetContactNote sets ContactNote field to given value.

### HasContactNote

`func (o *SuppliersApiCreateSupplier201Response) HasContactNote() bool`

HasContactNote returns a boolean if a field has been set.

### GetNote

`func (o *SuppliersApiCreateSupplier201Response) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *SuppliersApiCreateSupplier201Response) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *SuppliersApiCreateSupplier201Response) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *SuppliersApiCreateSupplier201Response) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetCreatedById

`func (o *SuppliersApiCreateSupplier201Response) GetCreatedById() string`

GetCreatedById returns the CreatedById field if non-nil, zero value otherwise.

### GetCreatedByIdOk

`func (o *SuppliersApiCreateSupplier201Response) GetCreatedByIdOk() (*string, bool)`

GetCreatedByIdOk returns a tuple with the CreatedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedById

`func (o *SuppliersApiCreateSupplier201Response) SetCreatedById(v string)`

SetCreatedById sets CreatedById field to given value.

### HasCreatedById

`func (o *SuppliersApiCreateSupplier201Response) HasCreatedById() bool`

HasCreatedById returns a boolean if a field has been set.

### GetCreatedDate

`func (o *SuppliersApiCreateSupplier201Response) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *SuppliersApiCreateSupplier201Response) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *SuppliersApiCreateSupplier201Response) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *SuppliersApiCreateSupplier201Response) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.

### GetModifiedById

`func (o *SuppliersApiCreateSupplier201Response) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *SuppliersApiCreateSupplier201Response) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *SuppliersApiCreateSupplier201Response) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *SuppliersApiCreateSupplier201Response) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetModifiedDate

`func (o *SuppliersApiCreateSupplier201Response) GetModifiedDate() time.Time`

GetModifiedDate returns the ModifiedDate field if non-nil, zero value otherwise.

### GetModifiedDateOk

`func (o *SuppliersApiCreateSupplier201Response) GetModifiedDateOk() (*time.Time, bool)`

GetModifiedDateOk returns a tuple with the ModifiedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDate

`func (o *SuppliersApiCreateSupplier201Response) SetModifiedDate(v time.Time)`

SetModifiedDate sets ModifiedDate field to given value.

### HasModifiedDate

`func (o *SuppliersApiCreateSupplier201Response) HasModifiedDate() bool`

HasModifiedDate returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


