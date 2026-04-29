# SuppliersApiGetSupplierResponse

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

### NewSuppliersApiGetSupplierResponse

`func NewSuppliersApiGetSupplierResponse() *SuppliersApiGetSupplierResponse`

NewSuppliersApiGetSupplierResponse instantiates a new SuppliersApiGetSupplierResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSuppliersApiGetSupplierResponseWithDefaults

`func NewSuppliersApiGetSupplierResponseWithDefaults() *SuppliersApiGetSupplierResponse`

NewSuppliersApiGetSupplierResponseWithDefaults instantiates a new SuppliersApiGetSupplierResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SuppliersApiGetSupplierResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SuppliersApiGetSupplierResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SuppliersApiGetSupplierResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *SuppliersApiGetSupplierResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCode

`func (o *SuppliersApiGetSupplierResponse) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *SuppliersApiGetSupplierResponse) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *SuppliersApiGetSupplierResponse) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *SuppliersApiGetSupplierResponse) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetOldCode

`func (o *SuppliersApiGetSupplierResponse) GetOldCode() string`

GetOldCode returns the OldCode field if non-nil, zero value otherwise.

### GetOldCodeOk

`func (o *SuppliersApiGetSupplierResponse) GetOldCodeOk() (*string, bool)`

GetOldCodeOk returns a tuple with the OldCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOldCode

`func (o *SuppliersApiGetSupplierResponse) SetOldCode(v string)`

SetOldCode sets OldCode field to given value.

### HasOldCode

`func (o *SuppliersApiGetSupplierResponse) HasOldCode() bool`

HasOldCode returns a boolean if a field has been set.

### GetName

`func (o *SuppliersApiGetSupplierResponse) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *SuppliersApiGetSupplierResponse) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *SuppliersApiGetSupplierResponse) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *SuppliersApiGetSupplierResponse) HasName() bool`

HasName returns a boolean if a field has been set.

### GetLanguage

`func (o *SuppliersApiGetSupplierResponse) GetLanguage() string`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *SuppliersApiGetSupplierResponse) GetLanguageOk() (*string, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *SuppliersApiGetSupplierResponse) SetLanguage(v string)`

SetLanguage sets Language field to given value.

### HasLanguage

`func (o *SuppliersApiGetSupplierResponse) HasLanguage() bool`

HasLanguage returns a boolean if a field has been set.

### GetCategory

`func (o *SuppliersApiGetSupplierResponse) GetCategory() string`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *SuppliersApiGetSupplierResponse) GetCategoryOk() (*string, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *SuppliersApiGetSupplierResponse) SetCategory(v string)`

SetCategory sets Category field to given value.

### HasCategory

`func (o *SuppliersApiGetSupplierResponse) HasCategory() bool`

HasCategory returns a boolean if a field has been set.

### GetStatus

`func (o *SuppliersApiGetSupplierResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *SuppliersApiGetSupplierResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *SuppliersApiGetSupplierResponse) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *SuppliersApiGetSupplierResponse) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetType

`func (o *SuppliersApiGetSupplierResponse) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *SuppliersApiGetSupplierResponse) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *SuppliersApiGetSupplierResponse) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *SuppliersApiGetSupplierResponse) HasType() bool`

HasType returns a boolean if a field has been set.

### GetParentSupplierId

`func (o *SuppliersApiGetSupplierResponse) GetParentSupplierId() string`

GetParentSupplierId returns the ParentSupplierId field if non-nil, zero value otherwise.

### GetParentSupplierIdOk

`func (o *SuppliersApiGetSupplierResponse) GetParentSupplierIdOk() (*string, bool)`

GetParentSupplierIdOk returns a tuple with the ParentSupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentSupplierId

`func (o *SuppliersApiGetSupplierResponse) SetParentSupplierId(v string)`

SetParentSupplierId sets ParentSupplierId field to given value.

### HasParentSupplierId

`func (o *SuppliersApiGetSupplierResponse) HasParentSupplierId() bool`

HasParentSupplierId returns a boolean if a field has been set.

### GetWebAddress

`func (o *SuppliersApiGetSupplierResponse) GetWebAddress() string`

GetWebAddress returns the WebAddress field if non-nil, zero value otherwise.

### GetWebAddressOk

`func (o *SuppliersApiGetSupplierResponse) GetWebAddressOk() (*string, bool)`

GetWebAddressOk returns a tuple with the WebAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebAddress

`func (o *SuppliersApiGetSupplierResponse) SetWebAddress(v string)`

SetWebAddress sets WebAddress field to given value.

### HasWebAddress

`func (o *SuppliersApiGetSupplierResponse) HasWebAddress() bool`

HasWebAddress returns a boolean if a field has been set.

### GetContactNote

`func (o *SuppliersApiGetSupplierResponse) GetContactNote() string`

GetContactNote returns the ContactNote field if non-nil, zero value otherwise.

### GetContactNoteOk

`func (o *SuppliersApiGetSupplierResponse) GetContactNoteOk() (*string, bool)`

GetContactNoteOk returns a tuple with the ContactNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactNote

`func (o *SuppliersApiGetSupplierResponse) SetContactNote(v string)`

SetContactNote sets ContactNote field to given value.

### HasContactNote

`func (o *SuppliersApiGetSupplierResponse) HasContactNote() bool`

HasContactNote returns a boolean if a field has been set.

### GetNote

`func (o *SuppliersApiGetSupplierResponse) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *SuppliersApiGetSupplierResponse) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *SuppliersApiGetSupplierResponse) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *SuppliersApiGetSupplierResponse) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetCreatedById

`func (o *SuppliersApiGetSupplierResponse) GetCreatedById() string`

GetCreatedById returns the CreatedById field if non-nil, zero value otherwise.

### GetCreatedByIdOk

`func (o *SuppliersApiGetSupplierResponse) GetCreatedByIdOk() (*string, bool)`

GetCreatedByIdOk returns a tuple with the CreatedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedById

`func (o *SuppliersApiGetSupplierResponse) SetCreatedById(v string)`

SetCreatedById sets CreatedById field to given value.

### HasCreatedById

`func (o *SuppliersApiGetSupplierResponse) HasCreatedById() bool`

HasCreatedById returns a boolean if a field has been set.

### GetCreatedDate

`func (o *SuppliersApiGetSupplierResponse) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *SuppliersApiGetSupplierResponse) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *SuppliersApiGetSupplierResponse) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *SuppliersApiGetSupplierResponse) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.

### GetModifiedById

`func (o *SuppliersApiGetSupplierResponse) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *SuppliersApiGetSupplierResponse) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *SuppliersApiGetSupplierResponse) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *SuppliersApiGetSupplierResponse) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetModifiedDate

`func (o *SuppliersApiGetSupplierResponse) GetModifiedDate() time.Time`

GetModifiedDate returns the ModifiedDate field if non-nil, zero value otherwise.

### GetModifiedDateOk

`func (o *SuppliersApiGetSupplierResponse) GetModifiedDateOk() (*time.Time, bool)`

GetModifiedDateOk returns a tuple with the ModifiedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDate

`func (o *SuppliersApiGetSupplierResponse) SetModifiedDate(v time.Time)`

SetModifiedDate sets ModifiedDate field to given value.

### HasModifiedDate

`func (o *SuppliersApiGetSupplierResponse) HasModifiedDate() bool`

HasModifiedDate returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


