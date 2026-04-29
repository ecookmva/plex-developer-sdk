# SuppliersApiCreateSupplierRequest

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

## Methods

### NewSuppliersApiCreateSupplierRequest

`func NewSuppliersApiCreateSupplierRequest() *SuppliersApiCreateSupplierRequest`

NewSuppliersApiCreateSupplierRequest instantiates a new SuppliersApiCreateSupplierRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSuppliersApiCreateSupplierRequestWithDefaults

`func NewSuppliersApiCreateSupplierRequestWithDefaults() *SuppliersApiCreateSupplierRequest`

NewSuppliersApiCreateSupplierRequestWithDefaults instantiates a new SuppliersApiCreateSupplierRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SuppliersApiCreateSupplierRequest) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SuppliersApiCreateSupplierRequest) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SuppliersApiCreateSupplierRequest) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *SuppliersApiCreateSupplierRequest) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCode

`func (o *SuppliersApiCreateSupplierRequest) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *SuppliersApiCreateSupplierRequest) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *SuppliersApiCreateSupplierRequest) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *SuppliersApiCreateSupplierRequest) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetOldCode

`func (o *SuppliersApiCreateSupplierRequest) GetOldCode() string`

GetOldCode returns the OldCode field if non-nil, zero value otherwise.

### GetOldCodeOk

`func (o *SuppliersApiCreateSupplierRequest) GetOldCodeOk() (*string, bool)`

GetOldCodeOk returns a tuple with the OldCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOldCode

`func (o *SuppliersApiCreateSupplierRequest) SetOldCode(v string)`

SetOldCode sets OldCode field to given value.

### HasOldCode

`func (o *SuppliersApiCreateSupplierRequest) HasOldCode() bool`

HasOldCode returns a boolean if a field has been set.

### GetName

`func (o *SuppliersApiCreateSupplierRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *SuppliersApiCreateSupplierRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *SuppliersApiCreateSupplierRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *SuppliersApiCreateSupplierRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### GetLanguage

`func (o *SuppliersApiCreateSupplierRequest) GetLanguage() string`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *SuppliersApiCreateSupplierRequest) GetLanguageOk() (*string, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *SuppliersApiCreateSupplierRequest) SetLanguage(v string)`

SetLanguage sets Language field to given value.

### HasLanguage

`func (o *SuppliersApiCreateSupplierRequest) HasLanguage() bool`

HasLanguage returns a boolean if a field has been set.

### GetCategory

`func (o *SuppliersApiCreateSupplierRequest) GetCategory() string`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *SuppliersApiCreateSupplierRequest) GetCategoryOk() (*string, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *SuppliersApiCreateSupplierRequest) SetCategory(v string)`

SetCategory sets Category field to given value.

### HasCategory

`func (o *SuppliersApiCreateSupplierRequest) HasCategory() bool`

HasCategory returns a boolean if a field has been set.

### GetStatus

`func (o *SuppliersApiCreateSupplierRequest) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *SuppliersApiCreateSupplierRequest) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *SuppliersApiCreateSupplierRequest) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *SuppliersApiCreateSupplierRequest) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetType

`func (o *SuppliersApiCreateSupplierRequest) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *SuppliersApiCreateSupplierRequest) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *SuppliersApiCreateSupplierRequest) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *SuppliersApiCreateSupplierRequest) HasType() bool`

HasType returns a boolean if a field has been set.

### GetParentSupplierId

`func (o *SuppliersApiCreateSupplierRequest) GetParentSupplierId() string`

GetParentSupplierId returns the ParentSupplierId field if non-nil, zero value otherwise.

### GetParentSupplierIdOk

`func (o *SuppliersApiCreateSupplierRequest) GetParentSupplierIdOk() (*string, bool)`

GetParentSupplierIdOk returns a tuple with the ParentSupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentSupplierId

`func (o *SuppliersApiCreateSupplierRequest) SetParentSupplierId(v string)`

SetParentSupplierId sets ParentSupplierId field to given value.

### HasParentSupplierId

`func (o *SuppliersApiCreateSupplierRequest) HasParentSupplierId() bool`

HasParentSupplierId returns a boolean if a field has been set.

### GetWebAddress

`func (o *SuppliersApiCreateSupplierRequest) GetWebAddress() string`

GetWebAddress returns the WebAddress field if non-nil, zero value otherwise.

### GetWebAddressOk

`func (o *SuppliersApiCreateSupplierRequest) GetWebAddressOk() (*string, bool)`

GetWebAddressOk returns a tuple with the WebAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebAddress

`func (o *SuppliersApiCreateSupplierRequest) SetWebAddress(v string)`

SetWebAddress sets WebAddress field to given value.

### HasWebAddress

`func (o *SuppliersApiCreateSupplierRequest) HasWebAddress() bool`

HasWebAddress returns a boolean if a field has been set.

### GetContactNote

`func (o *SuppliersApiCreateSupplierRequest) GetContactNote() string`

GetContactNote returns the ContactNote field if non-nil, zero value otherwise.

### GetContactNoteOk

`func (o *SuppliersApiCreateSupplierRequest) GetContactNoteOk() (*string, bool)`

GetContactNoteOk returns a tuple with the ContactNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactNote

`func (o *SuppliersApiCreateSupplierRequest) SetContactNote(v string)`

SetContactNote sets ContactNote field to given value.

### HasContactNote

`func (o *SuppliersApiCreateSupplierRequest) HasContactNote() bool`

HasContactNote returns a boolean if a field has been set.

### GetNote

`func (o *SuppliersApiCreateSupplierRequest) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *SuppliersApiCreateSupplierRequest) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *SuppliersApiCreateSupplierRequest) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *SuppliersApiCreateSupplierRequest) HasNote() bool`

HasNote returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


