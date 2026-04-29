# AddressesItem1

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

## Methods

### NewAddressesItem1

`func NewAddressesItem1() *AddressesItem1`

NewAddressesItem1 instantiates a new AddressesItem1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAddressesItem1WithDefaults

`func NewAddressesItem1WithDefaults() *AddressesItem1`

NewAddressesItem1WithDefaults instantiates a new AddressesItem1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AddressesItem1) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AddressesItem1) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AddressesItem1) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *AddressesItem1) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCode

`func (o *AddressesItem1) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *AddressesItem1) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *AddressesItem1) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *AddressesItem1) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetType

`func (o *AddressesItem1) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *AddressesItem1) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *AddressesItem1) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *AddressesItem1) HasType() bool`

HasType returns a boolean if a field has been set.

### GetCountry

`func (o *AddressesItem1) GetCountry() string`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *AddressesItem1) GetCountryOk() (*string, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *AddressesItem1) SetCountry(v string)`

SetCountry sets Country field to given value.

### HasCountry

`func (o *AddressesItem1) HasCountry() bool`

HasCountry returns a boolean if a field has been set.

### GetAddress

`func (o *AddressesItem1) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *AddressesItem1) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *AddressesItem1) SetAddress(v string)`

SetAddress sets Address field to given value.

### HasAddress

`func (o *AddressesItem1) HasAddress() bool`

HasAddress returns a boolean if a field has been set.

### GetCity

`func (o *AddressesItem1) GetCity() string`

GetCity returns the City field if non-nil, zero value otherwise.

### GetCityOk

`func (o *AddressesItem1) GetCityOk() (*string, bool)`

GetCityOk returns a tuple with the City field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCity

`func (o *AddressesItem1) SetCity(v string)`

SetCity sets City field to given value.

### HasCity

`func (o *AddressesItem1) HasCity() bool`

HasCity returns a boolean if a field has been set.

### GetZip

`func (o *AddressesItem1) GetZip() string`

GetZip returns the Zip field if non-nil, zero value otherwise.

### GetZipOk

`func (o *AddressesItem1) GetZipOk() (*string, bool)`

GetZipOk returns a tuple with the Zip field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetZip

`func (o *AddressesItem1) SetZip(v string)`

SetZip sets Zip field to given value.

### HasZip

`func (o *AddressesItem1) HasZip() bool`

HasZip returns a boolean if a field has been set.

### GetState

`func (o *AddressesItem1) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *AddressesItem1) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *AddressesItem1) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *AddressesItem1) HasState() bool`

HasState returns a boolean if a field has been set.

### GetMain

`func (o *AddressesItem1) GetMain() bool`

GetMain returns the Main field if non-nil, zero value otherwise.

### GetMainOk

`func (o *AddressesItem1) GetMainOk() (*bool, bool)`

GetMainOk returns a tuple with the Main field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMain

`func (o *AddressesItem1) SetMain(v bool)`

SetMain sets Main field to given value.

### HasMain

`func (o *AddressesItem1) HasMain() bool`

HasMain returns a boolean if a field has been set.

### GetRemit

`func (o *AddressesItem1) GetRemit() bool`

GetRemit returns the Remit field if non-nil, zero value otherwise.

### GetRemitOk

`func (o *AddressesItem1) GetRemitOk() (*bool, bool)`

GetRemitOk returns a tuple with the Remit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemit

`func (o *AddressesItem1) SetRemit(v bool)`

SetRemit sets Remit field to given value.

### HasRemit

`func (o *AddressesItem1) HasRemit() bool`

HasRemit returns a boolean if a field has been set.

### GetPhone

`func (o *AddressesItem1) GetPhone() string`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *AddressesItem1) GetPhoneOk() (*string, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *AddressesItem1) SetPhone(v string)`

SetPhone sets Phone field to given value.

### HasPhone

`func (o *AddressesItem1) HasPhone() bool`

HasPhone returns a boolean if a field has been set.

### GetFax

`func (o *AddressesItem1) GetFax() string`

GetFax returns the Fax field if non-nil, zero value otherwise.

### GetFaxOk

`func (o *AddressesItem1) GetFaxOk() (*string, bool)`

GetFaxOk returns a tuple with the Fax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFax

`func (o *AddressesItem1) SetFax(v string)`

SetFax sets Fax field to given value.

### HasFax

`func (o *AddressesItem1) HasFax() bool`

HasFax returns a boolean if a field has been set.

### GetEmail

`func (o *AddressesItem1) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *AddressesItem1) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *AddressesItem1) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *AddressesItem1) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetAlternateSupplierName

`func (o *AddressesItem1) GetAlternateSupplierName() string`

GetAlternateSupplierName returns the AlternateSupplierName field if non-nil, zero value otherwise.

### GetAlternateSupplierNameOk

`func (o *AddressesItem1) GetAlternateSupplierNameOk() (*string, bool)`

GetAlternateSupplierNameOk returns a tuple with the AlternateSupplierName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlternateSupplierName

`func (o *AddressesItem1) SetAlternateSupplierName(v string)`

SetAlternateSupplierName sets AlternateSupplierName field to given value.

### HasAlternateSupplierName

`func (o *AddressesItem1) HasAlternateSupplierName() bool`

HasAlternateSupplierName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


