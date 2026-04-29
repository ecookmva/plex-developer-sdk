# SuppliersApiUpdateSupplierAddressRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Code** | Pointer to **string** | This must be unique in the context of a supplier. | [optional] 
**Type** | Pointer to **string** | Setup Table: Supplier_Address_Type | [optional] 
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

### NewSuppliersApiUpdateSupplierAddressRequest

`func NewSuppliersApiUpdateSupplierAddressRequest() *SuppliersApiUpdateSupplierAddressRequest`

NewSuppliersApiUpdateSupplierAddressRequest instantiates a new SuppliersApiUpdateSupplierAddressRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSuppliersApiUpdateSupplierAddressRequestWithDefaults

`func NewSuppliersApiUpdateSupplierAddressRequestWithDefaults() *SuppliersApiUpdateSupplierAddressRequest`

NewSuppliersApiUpdateSupplierAddressRequestWithDefaults instantiates a new SuppliersApiUpdateSupplierAddressRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCode

`func (o *SuppliersApiUpdateSupplierAddressRequest) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *SuppliersApiUpdateSupplierAddressRequest) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *SuppliersApiUpdateSupplierAddressRequest) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *SuppliersApiUpdateSupplierAddressRequest) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetType

`func (o *SuppliersApiUpdateSupplierAddressRequest) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *SuppliersApiUpdateSupplierAddressRequest) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *SuppliersApiUpdateSupplierAddressRequest) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *SuppliersApiUpdateSupplierAddressRequest) HasType() bool`

HasType returns a boolean if a field has been set.

### GetCountry

`func (o *SuppliersApiUpdateSupplierAddressRequest) GetCountry() string`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *SuppliersApiUpdateSupplierAddressRequest) GetCountryOk() (*string, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *SuppliersApiUpdateSupplierAddressRequest) SetCountry(v string)`

SetCountry sets Country field to given value.

### HasCountry

`func (o *SuppliersApiUpdateSupplierAddressRequest) HasCountry() bool`

HasCountry returns a boolean if a field has been set.

### GetAddress

`func (o *SuppliersApiUpdateSupplierAddressRequest) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *SuppliersApiUpdateSupplierAddressRequest) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *SuppliersApiUpdateSupplierAddressRequest) SetAddress(v string)`

SetAddress sets Address field to given value.

### HasAddress

`func (o *SuppliersApiUpdateSupplierAddressRequest) HasAddress() bool`

HasAddress returns a boolean if a field has been set.

### GetCity

`func (o *SuppliersApiUpdateSupplierAddressRequest) GetCity() string`

GetCity returns the City field if non-nil, zero value otherwise.

### GetCityOk

`func (o *SuppliersApiUpdateSupplierAddressRequest) GetCityOk() (*string, bool)`

GetCityOk returns a tuple with the City field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCity

`func (o *SuppliersApiUpdateSupplierAddressRequest) SetCity(v string)`

SetCity sets City field to given value.

### HasCity

`func (o *SuppliersApiUpdateSupplierAddressRequest) HasCity() bool`

HasCity returns a boolean if a field has been set.

### GetZip

`func (o *SuppliersApiUpdateSupplierAddressRequest) GetZip() string`

GetZip returns the Zip field if non-nil, zero value otherwise.

### GetZipOk

`func (o *SuppliersApiUpdateSupplierAddressRequest) GetZipOk() (*string, bool)`

GetZipOk returns a tuple with the Zip field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetZip

`func (o *SuppliersApiUpdateSupplierAddressRequest) SetZip(v string)`

SetZip sets Zip field to given value.

### HasZip

`func (o *SuppliersApiUpdateSupplierAddressRequest) HasZip() bool`

HasZip returns a boolean if a field has been set.

### GetState

`func (o *SuppliersApiUpdateSupplierAddressRequest) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *SuppliersApiUpdateSupplierAddressRequest) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *SuppliersApiUpdateSupplierAddressRequest) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *SuppliersApiUpdateSupplierAddressRequest) HasState() bool`

HasState returns a boolean if a field has been set.

### GetMain

`func (o *SuppliersApiUpdateSupplierAddressRequest) GetMain() bool`

GetMain returns the Main field if non-nil, zero value otherwise.

### GetMainOk

`func (o *SuppliersApiUpdateSupplierAddressRequest) GetMainOk() (*bool, bool)`

GetMainOk returns a tuple with the Main field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMain

`func (o *SuppliersApiUpdateSupplierAddressRequest) SetMain(v bool)`

SetMain sets Main field to given value.

### HasMain

`func (o *SuppliersApiUpdateSupplierAddressRequest) HasMain() bool`

HasMain returns a boolean if a field has been set.

### GetRemit

`func (o *SuppliersApiUpdateSupplierAddressRequest) GetRemit() bool`

GetRemit returns the Remit field if non-nil, zero value otherwise.

### GetRemitOk

`func (o *SuppliersApiUpdateSupplierAddressRequest) GetRemitOk() (*bool, bool)`

GetRemitOk returns a tuple with the Remit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemit

`func (o *SuppliersApiUpdateSupplierAddressRequest) SetRemit(v bool)`

SetRemit sets Remit field to given value.

### HasRemit

`func (o *SuppliersApiUpdateSupplierAddressRequest) HasRemit() bool`

HasRemit returns a boolean if a field has been set.

### GetPhone

`func (o *SuppliersApiUpdateSupplierAddressRequest) GetPhone() string`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *SuppliersApiUpdateSupplierAddressRequest) GetPhoneOk() (*string, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *SuppliersApiUpdateSupplierAddressRequest) SetPhone(v string)`

SetPhone sets Phone field to given value.

### HasPhone

`func (o *SuppliersApiUpdateSupplierAddressRequest) HasPhone() bool`

HasPhone returns a boolean if a field has been set.

### GetFax

`func (o *SuppliersApiUpdateSupplierAddressRequest) GetFax() string`

GetFax returns the Fax field if non-nil, zero value otherwise.

### GetFaxOk

`func (o *SuppliersApiUpdateSupplierAddressRequest) GetFaxOk() (*string, bool)`

GetFaxOk returns a tuple with the Fax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFax

`func (o *SuppliersApiUpdateSupplierAddressRequest) SetFax(v string)`

SetFax sets Fax field to given value.

### HasFax

`func (o *SuppliersApiUpdateSupplierAddressRequest) HasFax() bool`

HasFax returns a boolean if a field has been set.

### GetEmail

`func (o *SuppliersApiUpdateSupplierAddressRequest) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *SuppliersApiUpdateSupplierAddressRequest) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *SuppliersApiUpdateSupplierAddressRequest) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *SuppliersApiUpdateSupplierAddressRequest) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetAlternateSupplierName

`func (o *SuppliersApiUpdateSupplierAddressRequest) GetAlternateSupplierName() string`

GetAlternateSupplierName returns the AlternateSupplierName field if non-nil, zero value otherwise.

### GetAlternateSupplierNameOk

`func (o *SuppliersApiUpdateSupplierAddressRequest) GetAlternateSupplierNameOk() (*string, bool)`

GetAlternateSupplierNameOk returns a tuple with the AlternateSupplierName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlternateSupplierName

`func (o *SuppliersApiUpdateSupplierAddressRequest) SetAlternateSupplierName(v string)`

SetAlternateSupplierName sets AlternateSupplierName field to given value.

### HasAlternateSupplierName

`func (o *SuppliersApiUpdateSupplierAddressRequest) HasAlternateSupplierName() bool`

HasAlternateSupplierName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


