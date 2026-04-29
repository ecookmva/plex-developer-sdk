# PurchaseOrdersApiListPurchaseOrderPricesItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**EffectiveDate** | Pointer to **time.Time** | The effective date of the price. | [optional] 
**ExpirationDate** | Pointer to **time.Time** | The expiration date of the price. | [optional] 
**UnitPrice** | Pointer to **float64** | Price per unit. | [optional] 
**Note** | Pointer to **string** |  | [optional] 
**CreatedById** | Pointer to **string** | The ID of the user who created the record. | [optional] 
**CreatedDate** | Pointer to **time.Time** | The date on which the record was created. | [optional] 
**ModifiedById** | Pointer to **string** | The ID of the user who last modified the record. | [optional] 
**ModifiedDate** | Pointer to **time.Time** | The date on which the record was last modified. | [optional] 

## Methods

### NewPurchaseOrdersApiListPurchaseOrderPricesItem

`func NewPurchaseOrdersApiListPurchaseOrderPricesItem() *PurchaseOrdersApiListPurchaseOrderPricesItem`

NewPurchaseOrdersApiListPurchaseOrderPricesItem instantiates a new PurchaseOrdersApiListPurchaseOrderPricesItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPurchaseOrdersApiListPurchaseOrderPricesItemWithDefaults

`func NewPurchaseOrdersApiListPurchaseOrderPricesItemWithDefaults() *PurchaseOrdersApiListPurchaseOrderPricesItem`

NewPurchaseOrdersApiListPurchaseOrderPricesItemWithDefaults instantiates a new PurchaseOrdersApiListPurchaseOrderPricesItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEffectiveDate

`func (o *PurchaseOrdersApiListPurchaseOrderPricesItem) GetEffectiveDate() time.Time`

GetEffectiveDate returns the EffectiveDate field if non-nil, zero value otherwise.

### GetEffectiveDateOk

`func (o *PurchaseOrdersApiListPurchaseOrderPricesItem) GetEffectiveDateOk() (*time.Time, bool)`

GetEffectiveDateOk returns a tuple with the EffectiveDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEffectiveDate

`func (o *PurchaseOrdersApiListPurchaseOrderPricesItem) SetEffectiveDate(v time.Time)`

SetEffectiveDate sets EffectiveDate field to given value.

### HasEffectiveDate

`func (o *PurchaseOrdersApiListPurchaseOrderPricesItem) HasEffectiveDate() bool`

HasEffectiveDate returns a boolean if a field has been set.

### GetExpirationDate

`func (o *PurchaseOrdersApiListPurchaseOrderPricesItem) GetExpirationDate() time.Time`

GetExpirationDate returns the ExpirationDate field if non-nil, zero value otherwise.

### GetExpirationDateOk

`func (o *PurchaseOrdersApiListPurchaseOrderPricesItem) GetExpirationDateOk() (*time.Time, bool)`

GetExpirationDateOk returns a tuple with the ExpirationDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpirationDate

`func (o *PurchaseOrdersApiListPurchaseOrderPricesItem) SetExpirationDate(v time.Time)`

SetExpirationDate sets ExpirationDate field to given value.

### HasExpirationDate

`func (o *PurchaseOrdersApiListPurchaseOrderPricesItem) HasExpirationDate() bool`

HasExpirationDate returns a boolean if a field has been set.

### GetUnitPrice

`func (o *PurchaseOrdersApiListPurchaseOrderPricesItem) GetUnitPrice() float64`

GetUnitPrice returns the UnitPrice field if non-nil, zero value otherwise.

### GetUnitPriceOk

`func (o *PurchaseOrdersApiListPurchaseOrderPricesItem) GetUnitPriceOk() (*float64, bool)`

GetUnitPriceOk returns a tuple with the UnitPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitPrice

`func (o *PurchaseOrdersApiListPurchaseOrderPricesItem) SetUnitPrice(v float64)`

SetUnitPrice sets UnitPrice field to given value.

### HasUnitPrice

`func (o *PurchaseOrdersApiListPurchaseOrderPricesItem) HasUnitPrice() bool`

HasUnitPrice returns a boolean if a field has been set.

### GetNote

`func (o *PurchaseOrdersApiListPurchaseOrderPricesItem) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *PurchaseOrdersApiListPurchaseOrderPricesItem) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *PurchaseOrdersApiListPurchaseOrderPricesItem) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *PurchaseOrdersApiListPurchaseOrderPricesItem) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetCreatedById

`func (o *PurchaseOrdersApiListPurchaseOrderPricesItem) GetCreatedById() string`

GetCreatedById returns the CreatedById field if non-nil, zero value otherwise.

### GetCreatedByIdOk

`func (o *PurchaseOrdersApiListPurchaseOrderPricesItem) GetCreatedByIdOk() (*string, bool)`

GetCreatedByIdOk returns a tuple with the CreatedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedById

`func (o *PurchaseOrdersApiListPurchaseOrderPricesItem) SetCreatedById(v string)`

SetCreatedById sets CreatedById field to given value.

### HasCreatedById

`func (o *PurchaseOrdersApiListPurchaseOrderPricesItem) HasCreatedById() bool`

HasCreatedById returns a boolean if a field has been set.

### GetCreatedDate

`func (o *PurchaseOrdersApiListPurchaseOrderPricesItem) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *PurchaseOrdersApiListPurchaseOrderPricesItem) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *PurchaseOrdersApiListPurchaseOrderPricesItem) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *PurchaseOrdersApiListPurchaseOrderPricesItem) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.

### GetModifiedById

`func (o *PurchaseOrdersApiListPurchaseOrderPricesItem) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *PurchaseOrdersApiListPurchaseOrderPricesItem) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *PurchaseOrdersApiListPurchaseOrderPricesItem) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *PurchaseOrdersApiListPurchaseOrderPricesItem) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetModifiedDate

`func (o *PurchaseOrdersApiListPurchaseOrderPricesItem) GetModifiedDate() time.Time`

GetModifiedDate returns the ModifiedDate field if non-nil, zero value otherwise.

### GetModifiedDateOk

`func (o *PurchaseOrdersApiListPurchaseOrderPricesItem) GetModifiedDateOk() (*time.Time, bool)`

GetModifiedDateOk returns a tuple with the ModifiedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDate

`func (o *PurchaseOrdersApiListPurchaseOrderPricesItem) SetModifiedDate(v time.Time)`

SetModifiedDate sets ModifiedDate field to given value.

### HasModifiedDate

`func (o *PurchaseOrdersApiListPurchaseOrderPricesItem) HasModifiedDate() bool`

HasModifiedDate returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


