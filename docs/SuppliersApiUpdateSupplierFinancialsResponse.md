# SuppliersApiUpdateSupplierFinancialsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DunsNo** | Pointer to **string** | Free text field for DUNS Number. | [optional] 
**PaymentStatus** | Pointer to **string** | Values come from the Payment_Status setup table. | [optional] 
**PaymentType** | Pointer to **string** | Values come from the Payment Type screen. | [optional] 
**BankRemittanceCode** | Pointer to **string** | Values come from the Bank Remittance Codes on the Bank Account Detail form. | [optional] 
**PaymentSupplierId** | Pointer to **string** | The default value is the ID of the current supplier. | [optional] 
**TaxId** | Pointer to **string** | Free text field for the Tax ID. | [optional] 
**TaxIdType** | Pointer to **string** | The Tax ID Type. | [optional] 
**BankId** | Pointer to **string** | Free text field for the Bank ID. | [optional] 
**BankRoutingNo** | Pointer to **string** | Free text field for the Bank Routing Number. | [optional] 
**BankAccountNo** | Pointer to **string** | Free text field for the Bank Account Number. | [optional] 
**BankName** | Pointer to **string** | Free text field for the Bank Name. | [optional] 
**BankAddress** | Pointer to **string** | Free text field for the Bank Street Address. | [optional] 
**BankCity** | Pointer to **string** | Free text field for the Bank City. | [optional] 
**BankState** | Pointer to **string** | State the bank resides in. | [optional] 
**BankCountry** | Pointer to **string** | Country the bank resides in. | [optional] 
**BankZipCode** | Pointer to **string** | Zip Code for the bank. | [optional] 
**SwiftNo** | Pointer to **string** | Free text field for SWIFT Number. | [optional] 
**IbanNo** | Pointer to **string** | Free text field for IBAN Number. | [optional] 
**Misc1099** | Pointer to **bool** | Defines the supplier as 1099. This displays the 1099 check box on supplier invoices. When enabled, supplier invoices are flagged as 1099 by default. | [optional] 

## Methods

### NewSuppliersApiUpdateSupplierFinancialsResponse

`func NewSuppliersApiUpdateSupplierFinancialsResponse() *SuppliersApiUpdateSupplierFinancialsResponse`

NewSuppliersApiUpdateSupplierFinancialsResponse instantiates a new SuppliersApiUpdateSupplierFinancialsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSuppliersApiUpdateSupplierFinancialsResponseWithDefaults

`func NewSuppliersApiUpdateSupplierFinancialsResponseWithDefaults() *SuppliersApiUpdateSupplierFinancialsResponse`

NewSuppliersApiUpdateSupplierFinancialsResponseWithDefaults instantiates a new SuppliersApiUpdateSupplierFinancialsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDunsNo

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) GetDunsNo() string`

GetDunsNo returns the DunsNo field if non-nil, zero value otherwise.

### GetDunsNoOk

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) GetDunsNoOk() (*string, bool)`

GetDunsNoOk returns a tuple with the DunsNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDunsNo

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) SetDunsNo(v string)`

SetDunsNo sets DunsNo field to given value.

### HasDunsNo

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) HasDunsNo() bool`

HasDunsNo returns a boolean if a field has been set.

### GetPaymentStatus

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) GetPaymentStatus() string`

GetPaymentStatus returns the PaymentStatus field if non-nil, zero value otherwise.

### GetPaymentStatusOk

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) GetPaymentStatusOk() (*string, bool)`

GetPaymentStatusOk returns a tuple with the PaymentStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentStatus

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) SetPaymentStatus(v string)`

SetPaymentStatus sets PaymentStatus field to given value.

### HasPaymentStatus

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) HasPaymentStatus() bool`

HasPaymentStatus returns a boolean if a field has been set.

### GetPaymentType

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) GetPaymentType() string`

GetPaymentType returns the PaymentType field if non-nil, zero value otherwise.

### GetPaymentTypeOk

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) GetPaymentTypeOk() (*string, bool)`

GetPaymentTypeOk returns a tuple with the PaymentType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentType

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) SetPaymentType(v string)`

SetPaymentType sets PaymentType field to given value.

### HasPaymentType

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) HasPaymentType() bool`

HasPaymentType returns a boolean if a field has been set.

### GetBankRemittanceCode

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) GetBankRemittanceCode() string`

GetBankRemittanceCode returns the BankRemittanceCode field if non-nil, zero value otherwise.

### GetBankRemittanceCodeOk

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) GetBankRemittanceCodeOk() (*string, bool)`

GetBankRemittanceCodeOk returns a tuple with the BankRemittanceCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankRemittanceCode

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) SetBankRemittanceCode(v string)`

SetBankRemittanceCode sets BankRemittanceCode field to given value.

### HasBankRemittanceCode

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) HasBankRemittanceCode() bool`

HasBankRemittanceCode returns a boolean if a field has been set.

### GetPaymentSupplierId

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) GetPaymentSupplierId() string`

GetPaymentSupplierId returns the PaymentSupplierId field if non-nil, zero value otherwise.

### GetPaymentSupplierIdOk

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) GetPaymentSupplierIdOk() (*string, bool)`

GetPaymentSupplierIdOk returns a tuple with the PaymentSupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentSupplierId

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) SetPaymentSupplierId(v string)`

SetPaymentSupplierId sets PaymentSupplierId field to given value.

### HasPaymentSupplierId

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) HasPaymentSupplierId() bool`

HasPaymentSupplierId returns a boolean if a field has been set.

### GetTaxId

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) GetTaxId() string`

GetTaxId returns the TaxId field if non-nil, zero value otherwise.

### GetTaxIdOk

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) GetTaxIdOk() (*string, bool)`

GetTaxIdOk returns a tuple with the TaxId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxId

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) SetTaxId(v string)`

SetTaxId sets TaxId field to given value.

### HasTaxId

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) HasTaxId() bool`

HasTaxId returns a boolean if a field has been set.

### GetTaxIdType

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) GetTaxIdType() string`

GetTaxIdType returns the TaxIdType field if non-nil, zero value otherwise.

### GetTaxIdTypeOk

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) GetTaxIdTypeOk() (*string, bool)`

GetTaxIdTypeOk returns a tuple with the TaxIdType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxIdType

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) SetTaxIdType(v string)`

SetTaxIdType sets TaxIdType field to given value.

### HasTaxIdType

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) HasTaxIdType() bool`

HasTaxIdType returns a boolean if a field has been set.

### GetBankId

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) GetBankId() string`

GetBankId returns the BankId field if non-nil, zero value otherwise.

### GetBankIdOk

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) GetBankIdOk() (*string, bool)`

GetBankIdOk returns a tuple with the BankId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankId

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) SetBankId(v string)`

SetBankId sets BankId field to given value.

### HasBankId

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) HasBankId() bool`

HasBankId returns a boolean if a field has been set.

### GetBankRoutingNo

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) GetBankRoutingNo() string`

GetBankRoutingNo returns the BankRoutingNo field if non-nil, zero value otherwise.

### GetBankRoutingNoOk

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) GetBankRoutingNoOk() (*string, bool)`

GetBankRoutingNoOk returns a tuple with the BankRoutingNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankRoutingNo

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) SetBankRoutingNo(v string)`

SetBankRoutingNo sets BankRoutingNo field to given value.

### HasBankRoutingNo

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) HasBankRoutingNo() bool`

HasBankRoutingNo returns a boolean if a field has been set.

### GetBankAccountNo

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) GetBankAccountNo() string`

GetBankAccountNo returns the BankAccountNo field if non-nil, zero value otherwise.

### GetBankAccountNoOk

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) GetBankAccountNoOk() (*string, bool)`

GetBankAccountNoOk returns a tuple with the BankAccountNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankAccountNo

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) SetBankAccountNo(v string)`

SetBankAccountNo sets BankAccountNo field to given value.

### HasBankAccountNo

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) HasBankAccountNo() bool`

HasBankAccountNo returns a boolean if a field has been set.

### GetBankName

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) GetBankName() string`

GetBankName returns the BankName field if non-nil, zero value otherwise.

### GetBankNameOk

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) GetBankNameOk() (*string, bool)`

GetBankNameOk returns a tuple with the BankName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankName

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) SetBankName(v string)`

SetBankName sets BankName field to given value.

### HasBankName

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) HasBankName() bool`

HasBankName returns a boolean if a field has been set.

### GetBankAddress

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) GetBankAddress() string`

GetBankAddress returns the BankAddress field if non-nil, zero value otherwise.

### GetBankAddressOk

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) GetBankAddressOk() (*string, bool)`

GetBankAddressOk returns a tuple with the BankAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankAddress

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) SetBankAddress(v string)`

SetBankAddress sets BankAddress field to given value.

### HasBankAddress

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) HasBankAddress() bool`

HasBankAddress returns a boolean if a field has been set.

### GetBankCity

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) GetBankCity() string`

GetBankCity returns the BankCity field if non-nil, zero value otherwise.

### GetBankCityOk

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) GetBankCityOk() (*string, bool)`

GetBankCityOk returns a tuple with the BankCity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankCity

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) SetBankCity(v string)`

SetBankCity sets BankCity field to given value.

### HasBankCity

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) HasBankCity() bool`

HasBankCity returns a boolean if a field has been set.

### GetBankState

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) GetBankState() string`

GetBankState returns the BankState field if non-nil, zero value otherwise.

### GetBankStateOk

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) GetBankStateOk() (*string, bool)`

GetBankStateOk returns a tuple with the BankState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankState

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) SetBankState(v string)`

SetBankState sets BankState field to given value.

### HasBankState

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) HasBankState() bool`

HasBankState returns a boolean if a field has been set.

### GetBankCountry

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) GetBankCountry() string`

GetBankCountry returns the BankCountry field if non-nil, zero value otherwise.

### GetBankCountryOk

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) GetBankCountryOk() (*string, bool)`

GetBankCountryOk returns a tuple with the BankCountry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankCountry

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) SetBankCountry(v string)`

SetBankCountry sets BankCountry field to given value.

### HasBankCountry

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) HasBankCountry() bool`

HasBankCountry returns a boolean if a field has been set.

### GetBankZipCode

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) GetBankZipCode() string`

GetBankZipCode returns the BankZipCode field if non-nil, zero value otherwise.

### GetBankZipCodeOk

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) GetBankZipCodeOk() (*string, bool)`

GetBankZipCodeOk returns a tuple with the BankZipCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankZipCode

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) SetBankZipCode(v string)`

SetBankZipCode sets BankZipCode field to given value.

### HasBankZipCode

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) HasBankZipCode() bool`

HasBankZipCode returns a boolean if a field has been set.

### GetSwiftNo

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) GetSwiftNo() string`

GetSwiftNo returns the SwiftNo field if non-nil, zero value otherwise.

### GetSwiftNoOk

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) GetSwiftNoOk() (*string, bool)`

GetSwiftNoOk returns a tuple with the SwiftNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSwiftNo

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) SetSwiftNo(v string)`

SetSwiftNo sets SwiftNo field to given value.

### HasSwiftNo

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) HasSwiftNo() bool`

HasSwiftNo returns a boolean if a field has been set.

### GetIbanNo

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) GetIbanNo() string`

GetIbanNo returns the IbanNo field if non-nil, zero value otherwise.

### GetIbanNoOk

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) GetIbanNoOk() (*string, bool)`

GetIbanNoOk returns a tuple with the IbanNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIbanNo

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) SetIbanNo(v string)`

SetIbanNo sets IbanNo field to given value.

### HasIbanNo

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) HasIbanNo() bool`

HasIbanNo returns a boolean if a field has been set.

### GetMisc1099

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) GetMisc1099() bool`

GetMisc1099 returns the Misc1099 field if non-nil, zero value otherwise.

### GetMisc1099Ok

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) GetMisc1099Ok() (*bool, bool)`

GetMisc1099Ok returns a tuple with the Misc1099 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMisc1099

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) SetMisc1099(v bool)`

SetMisc1099 sets Misc1099 field to given value.

### HasMisc1099

`func (o *SuppliersApiUpdateSupplierFinancialsResponse) HasMisc1099() bool`

HasMisc1099 returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


