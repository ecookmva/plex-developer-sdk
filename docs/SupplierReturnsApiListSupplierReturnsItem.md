# SupplierReturnsApiListSupplierReturnsItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | A unique identifier for the Supplier Return. This will be automatically generated if omitted from the request. | [optional] 
**SupplierReturnNumber** | Pointer to **string** | Return Number. | [optional] 
**SupplierId** | Pointer to **string** | The ID of the Supplier. | [optional] 
**Status** | Pointer to **string** | Setup Table: Supplier Return Status | [optional] 
**Type** | Pointer to **string** | Setup Table: Supplier Return Type | [optional] 
**CreatedById** | Pointer to **string** | The ID of the user who created the record. | [optional] 
**CreatedDate** | Pointer to **time.Time** | The date on which the record was created. | [optional] 
**SupplierAddressId** | Pointer to **string** |  | [optional] 
**ShipTo** | Pointer to **string** | The shipping address for the return. | [optional] 
**ModifiedById** | Pointer to **string** | The ID of the user who last modified the record. | [optional] 
**ModifiedDate** | Pointer to **time.Time** | The date and time of the last modification to the return. | [optional] 
**CarrierId** | Pointer to **string** | If the Supplier has a Supplier Type of Carrier, this ID will link to Supplier_No. | [optional] 
**Note** | Pointer to **string** |  | [optional] 
**ContactId** | Pointer to **string** |  | [optional] 

## Methods

### NewSupplierReturnsApiListSupplierReturnsItem

`func NewSupplierReturnsApiListSupplierReturnsItem() *SupplierReturnsApiListSupplierReturnsItem`

NewSupplierReturnsApiListSupplierReturnsItem instantiates a new SupplierReturnsApiListSupplierReturnsItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSupplierReturnsApiListSupplierReturnsItemWithDefaults

`func NewSupplierReturnsApiListSupplierReturnsItemWithDefaults() *SupplierReturnsApiListSupplierReturnsItem`

NewSupplierReturnsApiListSupplierReturnsItemWithDefaults instantiates a new SupplierReturnsApiListSupplierReturnsItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SupplierReturnsApiListSupplierReturnsItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SupplierReturnsApiListSupplierReturnsItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SupplierReturnsApiListSupplierReturnsItem) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *SupplierReturnsApiListSupplierReturnsItem) HasId() bool`

HasId returns a boolean if a field has been set.

### GetSupplierReturnNumber

`func (o *SupplierReturnsApiListSupplierReturnsItem) GetSupplierReturnNumber() string`

GetSupplierReturnNumber returns the SupplierReturnNumber field if non-nil, zero value otherwise.

### GetSupplierReturnNumberOk

`func (o *SupplierReturnsApiListSupplierReturnsItem) GetSupplierReturnNumberOk() (*string, bool)`

GetSupplierReturnNumberOk returns a tuple with the SupplierReturnNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierReturnNumber

`func (o *SupplierReturnsApiListSupplierReturnsItem) SetSupplierReturnNumber(v string)`

SetSupplierReturnNumber sets SupplierReturnNumber field to given value.

### HasSupplierReturnNumber

`func (o *SupplierReturnsApiListSupplierReturnsItem) HasSupplierReturnNumber() bool`

HasSupplierReturnNumber returns a boolean if a field has been set.

### GetSupplierId

`func (o *SupplierReturnsApiListSupplierReturnsItem) GetSupplierId() string`

GetSupplierId returns the SupplierId field if non-nil, zero value otherwise.

### GetSupplierIdOk

`func (o *SupplierReturnsApiListSupplierReturnsItem) GetSupplierIdOk() (*string, bool)`

GetSupplierIdOk returns a tuple with the SupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierId

`func (o *SupplierReturnsApiListSupplierReturnsItem) SetSupplierId(v string)`

SetSupplierId sets SupplierId field to given value.

### HasSupplierId

`func (o *SupplierReturnsApiListSupplierReturnsItem) HasSupplierId() bool`

HasSupplierId returns a boolean if a field has been set.

### GetStatus

`func (o *SupplierReturnsApiListSupplierReturnsItem) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *SupplierReturnsApiListSupplierReturnsItem) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *SupplierReturnsApiListSupplierReturnsItem) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *SupplierReturnsApiListSupplierReturnsItem) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetType

`func (o *SupplierReturnsApiListSupplierReturnsItem) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *SupplierReturnsApiListSupplierReturnsItem) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *SupplierReturnsApiListSupplierReturnsItem) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *SupplierReturnsApiListSupplierReturnsItem) HasType() bool`

HasType returns a boolean if a field has been set.

### GetCreatedById

`func (o *SupplierReturnsApiListSupplierReturnsItem) GetCreatedById() string`

GetCreatedById returns the CreatedById field if non-nil, zero value otherwise.

### GetCreatedByIdOk

`func (o *SupplierReturnsApiListSupplierReturnsItem) GetCreatedByIdOk() (*string, bool)`

GetCreatedByIdOk returns a tuple with the CreatedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedById

`func (o *SupplierReturnsApiListSupplierReturnsItem) SetCreatedById(v string)`

SetCreatedById sets CreatedById field to given value.

### HasCreatedById

`func (o *SupplierReturnsApiListSupplierReturnsItem) HasCreatedById() bool`

HasCreatedById returns a boolean if a field has been set.

### GetCreatedDate

`func (o *SupplierReturnsApiListSupplierReturnsItem) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *SupplierReturnsApiListSupplierReturnsItem) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *SupplierReturnsApiListSupplierReturnsItem) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *SupplierReturnsApiListSupplierReturnsItem) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.

### GetSupplierAddressId

`func (o *SupplierReturnsApiListSupplierReturnsItem) GetSupplierAddressId() string`

GetSupplierAddressId returns the SupplierAddressId field if non-nil, zero value otherwise.

### GetSupplierAddressIdOk

`func (o *SupplierReturnsApiListSupplierReturnsItem) GetSupplierAddressIdOk() (*string, bool)`

GetSupplierAddressIdOk returns a tuple with the SupplierAddressId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierAddressId

`func (o *SupplierReturnsApiListSupplierReturnsItem) SetSupplierAddressId(v string)`

SetSupplierAddressId sets SupplierAddressId field to given value.

### HasSupplierAddressId

`func (o *SupplierReturnsApiListSupplierReturnsItem) HasSupplierAddressId() bool`

HasSupplierAddressId returns a boolean if a field has been set.

### GetShipTo

`func (o *SupplierReturnsApiListSupplierReturnsItem) GetShipTo() string`

GetShipTo returns the ShipTo field if non-nil, zero value otherwise.

### GetShipToOk

`func (o *SupplierReturnsApiListSupplierReturnsItem) GetShipToOk() (*string, bool)`

GetShipToOk returns a tuple with the ShipTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipTo

`func (o *SupplierReturnsApiListSupplierReturnsItem) SetShipTo(v string)`

SetShipTo sets ShipTo field to given value.

### HasShipTo

`func (o *SupplierReturnsApiListSupplierReturnsItem) HasShipTo() bool`

HasShipTo returns a boolean if a field has been set.

### GetModifiedById

`func (o *SupplierReturnsApiListSupplierReturnsItem) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *SupplierReturnsApiListSupplierReturnsItem) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *SupplierReturnsApiListSupplierReturnsItem) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *SupplierReturnsApiListSupplierReturnsItem) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetModifiedDate

`func (o *SupplierReturnsApiListSupplierReturnsItem) GetModifiedDate() time.Time`

GetModifiedDate returns the ModifiedDate field if non-nil, zero value otherwise.

### GetModifiedDateOk

`func (o *SupplierReturnsApiListSupplierReturnsItem) GetModifiedDateOk() (*time.Time, bool)`

GetModifiedDateOk returns a tuple with the ModifiedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDate

`func (o *SupplierReturnsApiListSupplierReturnsItem) SetModifiedDate(v time.Time)`

SetModifiedDate sets ModifiedDate field to given value.

### HasModifiedDate

`func (o *SupplierReturnsApiListSupplierReturnsItem) HasModifiedDate() bool`

HasModifiedDate returns a boolean if a field has been set.

### GetCarrierId

`func (o *SupplierReturnsApiListSupplierReturnsItem) GetCarrierId() string`

GetCarrierId returns the CarrierId field if non-nil, zero value otherwise.

### GetCarrierIdOk

`func (o *SupplierReturnsApiListSupplierReturnsItem) GetCarrierIdOk() (*string, bool)`

GetCarrierIdOk returns a tuple with the CarrierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierId

`func (o *SupplierReturnsApiListSupplierReturnsItem) SetCarrierId(v string)`

SetCarrierId sets CarrierId field to given value.

### HasCarrierId

`func (o *SupplierReturnsApiListSupplierReturnsItem) HasCarrierId() bool`

HasCarrierId returns a boolean if a field has been set.

### GetNote

`func (o *SupplierReturnsApiListSupplierReturnsItem) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *SupplierReturnsApiListSupplierReturnsItem) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *SupplierReturnsApiListSupplierReturnsItem) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *SupplierReturnsApiListSupplierReturnsItem) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetContactId

`func (o *SupplierReturnsApiListSupplierReturnsItem) GetContactId() string`

GetContactId returns the ContactId field if non-nil, zero value otherwise.

### GetContactIdOk

`func (o *SupplierReturnsApiListSupplierReturnsItem) GetContactIdOk() (*string, bool)`

GetContactIdOk returns a tuple with the ContactId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactId

`func (o *SupplierReturnsApiListSupplierReturnsItem) SetContactId(v string)`

SetContactId sets ContactId field to given value.

### HasContactId

`func (o *SupplierReturnsApiListSupplierReturnsItem) HasContactId() bool`

HasContactId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


