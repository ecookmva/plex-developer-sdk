# SuppliersApiListSupplierAddressesItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | A unique identifier for the supplier address. This will be automatically generated if omitted from the request. | [optional] 
**Code** | Pointer to **string** | This must be unique in the context of a supplier. | [optional] 
**Type** | Pointer to **string** | Setup Table: Supplier_Address_Type. | [optional] 
**Country** | Pointer to **string** |  | [optional] 
**Address** | Pointer to **string** |  | [optional] 
**City** | Pointer to **string** |  | [optional] 
**Zip** | Pointer to **string** |  | [optional] 
**State** | Pointer to **string** |  | [optional] 
**Main** | Pointer to **bool** | A supplier may have only one address designated as their Main address. | [optional] 
**Remit** | Pointer to **bool** | A supplier may have only one address designated as their Remit payment address. | [optional] 
**Phone** | Pointer to **string** |  | [optional] 
**Fax** | Pointer to **string** |  | [optional] 
**Email** | Pointer to **string** |  | [optional] 
**AlternateSupplierName** | Pointer to **string** |  | [optional] 
**CreatedById** | Pointer to **string** | IAM Account ID | [optional] 
**CreatedDate** | Pointer to **time.Time** |  | [optional] 
**ModifiedById** | Pointer to **string** | IAM Account ID | [optional] 
**ModifiedDate** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewSuppliersApiListSupplierAddressesItem

`func NewSuppliersApiListSupplierAddressesItem() *SuppliersApiListSupplierAddressesItem`

NewSuppliersApiListSupplierAddressesItem instantiates a new SuppliersApiListSupplierAddressesItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSuppliersApiListSupplierAddressesItemWithDefaults

`func NewSuppliersApiListSupplierAddressesItemWithDefaults() *SuppliersApiListSupplierAddressesItem`

NewSuppliersApiListSupplierAddressesItemWithDefaults instantiates a new SuppliersApiListSupplierAddressesItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SuppliersApiListSupplierAddressesItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SuppliersApiListSupplierAddressesItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SuppliersApiListSupplierAddressesItem) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *SuppliersApiListSupplierAddressesItem) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCode

`func (o *SuppliersApiListSupplierAddressesItem) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *SuppliersApiListSupplierAddressesItem) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *SuppliersApiListSupplierAddressesItem) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *SuppliersApiListSupplierAddressesItem) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetType

`func (o *SuppliersApiListSupplierAddressesItem) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *SuppliersApiListSupplierAddressesItem) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *SuppliersApiListSupplierAddressesItem) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *SuppliersApiListSupplierAddressesItem) HasType() bool`

HasType returns a boolean if a field has been set.

### GetCountry

`func (o *SuppliersApiListSupplierAddressesItem) GetCountry() string`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *SuppliersApiListSupplierAddressesItem) GetCountryOk() (*string, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *SuppliersApiListSupplierAddressesItem) SetCountry(v string)`

SetCountry sets Country field to given value.

### HasCountry

`func (o *SuppliersApiListSupplierAddressesItem) HasCountry() bool`

HasCountry returns a boolean if a field has been set.

### GetAddress

`func (o *SuppliersApiListSupplierAddressesItem) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *SuppliersApiListSupplierAddressesItem) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *SuppliersApiListSupplierAddressesItem) SetAddress(v string)`

SetAddress sets Address field to given value.

### HasAddress

`func (o *SuppliersApiListSupplierAddressesItem) HasAddress() bool`

HasAddress returns a boolean if a field has been set.

### GetCity

`func (o *SuppliersApiListSupplierAddressesItem) GetCity() string`

GetCity returns the City field if non-nil, zero value otherwise.

### GetCityOk

`func (o *SuppliersApiListSupplierAddressesItem) GetCityOk() (*string, bool)`

GetCityOk returns a tuple with the City field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCity

`func (o *SuppliersApiListSupplierAddressesItem) SetCity(v string)`

SetCity sets City field to given value.

### HasCity

`func (o *SuppliersApiListSupplierAddressesItem) HasCity() bool`

HasCity returns a boolean if a field has been set.

### GetZip

`func (o *SuppliersApiListSupplierAddressesItem) GetZip() string`

GetZip returns the Zip field if non-nil, zero value otherwise.

### GetZipOk

`func (o *SuppliersApiListSupplierAddressesItem) GetZipOk() (*string, bool)`

GetZipOk returns a tuple with the Zip field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetZip

`func (o *SuppliersApiListSupplierAddressesItem) SetZip(v string)`

SetZip sets Zip field to given value.

### HasZip

`func (o *SuppliersApiListSupplierAddressesItem) HasZip() bool`

HasZip returns a boolean if a field has been set.

### GetState

`func (o *SuppliersApiListSupplierAddressesItem) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *SuppliersApiListSupplierAddressesItem) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *SuppliersApiListSupplierAddressesItem) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *SuppliersApiListSupplierAddressesItem) HasState() bool`

HasState returns a boolean if a field has been set.

### GetMain

`func (o *SuppliersApiListSupplierAddressesItem) GetMain() bool`

GetMain returns the Main field if non-nil, zero value otherwise.

### GetMainOk

`func (o *SuppliersApiListSupplierAddressesItem) GetMainOk() (*bool, bool)`

GetMainOk returns a tuple with the Main field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMain

`func (o *SuppliersApiListSupplierAddressesItem) SetMain(v bool)`

SetMain sets Main field to given value.

### HasMain

`func (o *SuppliersApiListSupplierAddressesItem) HasMain() bool`

HasMain returns a boolean if a field has been set.

### GetRemit

`func (o *SuppliersApiListSupplierAddressesItem) GetRemit() bool`

GetRemit returns the Remit field if non-nil, zero value otherwise.

### GetRemitOk

`func (o *SuppliersApiListSupplierAddressesItem) GetRemitOk() (*bool, bool)`

GetRemitOk returns a tuple with the Remit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemit

`func (o *SuppliersApiListSupplierAddressesItem) SetRemit(v bool)`

SetRemit sets Remit field to given value.

### HasRemit

`func (o *SuppliersApiListSupplierAddressesItem) HasRemit() bool`

HasRemit returns a boolean if a field has been set.

### GetPhone

`func (o *SuppliersApiListSupplierAddressesItem) GetPhone() string`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *SuppliersApiListSupplierAddressesItem) GetPhoneOk() (*string, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *SuppliersApiListSupplierAddressesItem) SetPhone(v string)`

SetPhone sets Phone field to given value.

### HasPhone

`func (o *SuppliersApiListSupplierAddressesItem) HasPhone() bool`

HasPhone returns a boolean if a field has been set.

### GetFax

`func (o *SuppliersApiListSupplierAddressesItem) GetFax() string`

GetFax returns the Fax field if non-nil, zero value otherwise.

### GetFaxOk

`func (o *SuppliersApiListSupplierAddressesItem) GetFaxOk() (*string, bool)`

GetFaxOk returns a tuple with the Fax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFax

`func (o *SuppliersApiListSupplierAddressesItem) SetFax(v string)`

SetFax sets Fax field to given value.

### HasFax

`func (o *SuppliersApiListSupplierAddressesItem) HasFax() bool`

HasFax returns a boolean if a field has been set.

### GetEmail

`func (o *SuppliersApiListSupplierAddressesItem) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *SuppliersApiListSupplierAddressesItem) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *SuppliersApiListSupplierAddressesItem) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *SuppliersApiListSupplierAddressesItem) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetAlternateSupplierName

`func (o *SuppliersApiListSupplierAddressesItem) GetAlternateSupplierName() string`

GetAlternateSupplierName returns the AlternateSupplierName field if non-nil, zero value otherwise.

### GetAlternateSupplierNameOk

`func (o *SuppliersApiListSupplierAddressesItem) GetAlternateSupplierNameOk() (*string, bool)`

GetAlternateSupplierNameOk returns a tuple with the AlternateSupplierName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlternateSupplierName

`func (o *SuppliersApiListSupplierAddressesItem) SetAlternateSupplierName(v string)`

SetAlternateSupplierName sets AlternateSupplierName field to given value.

### HasAlternateSupplierName

`func (o *SuppliersApiListSupplierAddressesItem) HasAlternateSupplierName() bool`

HasAlternateSupplierName returns a boolean if a field has been set.

### GetCreatedById

`func (o *SuppliersApiListSupplierAddressesItem) GetCreatedById() string`

GetCreatedById returns the CreatedById field if non-nil, zero value otherwise.

### GetCreatedByIdOk

`func (o *SuppliersApiListSupplierAddressesItem) GetCreatedByIdOk() (*string, bool)`

GetCreatedByIdOk returns a tuple with the CreatedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedById

`func (o *SuppliersApiListSupplierAddressesItem) SetCreatedById(v string)`

SetCreatedById sets CreatedById field to given value.

### HasCreatedById

`func (o *SuppliersApiListSupplierAddressesItem) HasCreatedById() bool`

HasCreatedById returns a boolean if a field has been set.

### GetCreatedDate

`func (o *SuppliersApiListSupplierAddressesItem) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *SuppliersApiListSupplierAddressesItem) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *SuppliersApiListSupplierAddressesItem) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *SuppliersApiListSupplierAddressesItem) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.

### GetModifiedById

`func (o *SuppliersApiListSupplierAddressesItem) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *SuppliersApiListSupplierAddressesItem) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *SuppliersApiListSupplierAddressesItem) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *SuppliersApiListSupplierAddressesItem) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetModifiedDate

`func (o *SuppliersApiListSupplierAddressesItem) GetModifiedDate() time.Time`

GetModifiedDate returns the ModifiedDate field if non-nil, zero value otherwise.

### GetModifiedDateOk

`func (o *SuppliersApiListSupplierAddressesItem) GetModifiedDateOk() (*time.Time, bool)`

GetModifiedDateOk returns a tuple with the ModifiedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDate

`func (o *SuppliersApiListSupplierAddressesItem) SetModifiedDate(v time.Time)`

SetModifiedDate sets ModifiedDate field to given value.

### HasModifiedDate

`func (o *SuppliersApiListSupplierAddressesItem) HasModifiedDate() bool`

HasModifiedDate returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


