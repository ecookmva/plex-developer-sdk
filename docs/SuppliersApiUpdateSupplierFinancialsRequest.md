# SuppliersApiUpdateSupplierFinancialsRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DunsNo** | Pointer to **string** | Free text field for DUNS Number. | [optional] 
**PaymentStatus** | Pointer to **string** | Values come from the Payment_Status setup table. | [optional] 
**PaymentType** | Pointer to **string** | Values come from the Payment Type screen. | [optional] 
**BankRemittanceCode** | Pointer to **string** | Values come from the Bank Remittance Codes on the Bank Account Detail form. | [optional] 
**PaymentSupplierId** | Pointer to **string** | The default value is the ID of the current supplier. | [optional] 
**TaxId** | Pointer to **string** | Free text field for the Tax ID. | [optional] 
**TaxIdType** | Pointer to **string** | The Tax ID Type (i.e., EIN, SSN, QI-EIN, Undetermined). | [optional] 
**BankId** | Pointer to **string** | Free text field for the Bank ID. | [optional] 
**BankRoutingNo** | Pointer to **string** | Free text field for the Bank Routing Number. | [optional] 
**BankAccountNo** | Pointer to **string** | Free text field for the Bank Account Number. | [optional] 
**BankName** | Pointer to **string** | Free text field for the Bank Name. | [optional] 
**BankAddress** | Pointer to **string** | Free text field for the Bank Street Address. | [optional] 
**BankCity** | Pointer to **string** | Free text field for the Bank City. | [optional] 
**BankState** | Pointer to **string** | State the bank resides in. | [optional] 
**BankCountry** | Pointer to **string** | Country the bank resides in. | [optional] 
**BankZipCode** | Pointer to **string** | Zip Code of the bank. | [optional] 
**SwiftNo** | Pointer to **string** | Free text field for SWIFT Number. | [optional] 
**IbanNo** | Pointer to **string** | Free text field for IBAN Number. | [optional] 
**Misc1099** | Pointer to **bool** | Defines the supplier as 1099. This displays the 1099 check box on supplier invoices. When enabled, supplier invoices are flagged as 1099 by default. | [optional] 
**BankAccountNoBankRemittanceCode** | Pointer to **string** | The Bank Account Number associated with the Bank Remittance Code. | [optional] 
**BankAccountCurrencyCode** | Pointer to **string** | The bank account&#39;s Currency Code. | [optional] 

## Methods

### NewSuppliersApiUpdateSupplierFinancialsRequest

`func NewSuppliersApiUpdateSupplierFinancialsRequest() *SuppliersApiUpdateSupplierFinancialsRequest`

NewSuppliersApiUpdateSupplierFinancialsRequest instantiates a new SuppliersApiUpdateSupplierFinancialsRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSuppliersApiUpdateSupplierFinancialsRequestWithDefaults

`func NewSuppliersApiUpdateSupplierFinancialsRequestWithDefaults() *SuppliersApiUpdateSupplierFinancialsRequest`

NewSuppliersApiUpdateSupplierFinancialsRequestWithDefaults instantiates a new SuppliersApiUpdateSupplierFinancialsRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDunsNo

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) GetDunsNo() string`

GetDunsNo returns the DunsNo field if non-nil, zero value otherwise.

### GetDunsNoOk

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) GetDunsNoOk() (*string, bool)`

GetDunsNoOk returns a tuple with the DunsNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDunsNo

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) SetDunsNo(v string)`

SetDunsNo sets DunsNo field to given value.

### HasDunsNo

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) HasDunsNo() bool`

HasDunsNo returns a boolean if a field has been set.

### GetPaymentStatus

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) GetPaymentStatus() string`

GetPaymentStatus returns the PaymentStatus field if non-nil, zero value otherwise.

### GetPaymentStatusOk

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) GetPaymentStatusOk() (*string, bool)`

GetPaymentStatusOk returns a tuple with the PaymentStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentStatus

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) SetPaymentStatus(v string)`

SetPaymentStatus sets PaymentStatus field to given value.

### HasPaymentStatus

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) HasPaymentStatus() bool`

HasPaymentStatus returns a boolean if a field has been set.

### GetPaymentType

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) GetPaymentType() string`

GetPaymentType returns the PaymentType field if non-nil, zero value otherwise.

### GetPaymentTypeOk

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) GetPaymentTypeOk() (*string, bool)`

GetPaymentTypeOk returns a tuple with the PaymentType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentType

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) SetPaymentType(v string)`

SetPaymentType sets PaymentType field to given value.

### HasPaymentType

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) HasPaymentType() bool`

HasPaymentType returns a boolean if a field has been set.

### GetBankRemittanceCode

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) GetBankRemittanceCode() string`

GetBankRemittanceCode returns the BankRemittanceCode field if non-nil, zero value otherwise.

### GetBankRemittanceCodeOk

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) GetBankRemittanceCodeOk() (*string, bool)`

GetBankRemittanceCodeOk returns a tuple with the BankRemittanceCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankRemittanceCode

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) SetBankRemittanceCode(v string)`

SetBankRemittanceCode sets BankRemittanceCode field to given value.

### HasBankRemittanceCode

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) HasBankRemittanceCode() bool`

HasBankRemittanceCode returns a boolean if a field has been set.

### GetPaymentSupplierId

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) GetPaymentSupplierId() string`

GetPaymentSupplierId returns the PaymentSupplierId field if non-nil, zero value otherwise.

### GetPaymentSupplierIdOk

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) GetPaymentSupplierIdOk() (*string, bool)`

GetPaymentSupplierIdOk returns a tuple with the PaymentSupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentSupplierId

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) SetPaymentSupplierId(v string)`

SetPaymentSupplierId sets PaymentSupplierId field to given value.

### HasPaymentSupplierId

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) HasPaymentSupplierId() bool`

HasPaymentSupplierId returns a boolean if a field has been set.

### GetTaxId

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) GetTaxId() string`

GetTaxId returns the TaxId field if non-nil, zero value otherwise.

### GetTaxIdOk

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) GetTaxIdOk() (*string, bool)`

GetTaxIdOk returns a tuple with the TaxId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxId

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) SetTaxId(v string)`

SetTaxId sets TaxId field to given value.

### HasTaxId

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) HasTaxId() bool`

HasTaxId returns a boolean if a field has been set.

### GetTaxIdType

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) GetTaxIdType() string`

GetTaxIdType returns the TaxIdType field if non-nil, zero value otherwise.

### GetTaxIdTypeOk

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) GetTaxIdTypeOk() (*string, bool)`

GetTaxIdTypeOk returns a tuple with the TaxIdType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxIdType

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) SetTaxIdType(v string)`

SetTaxIdType sets TaxIdType field to given value.

### HasTaxIdType

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) HasTaxIdType() bool`

HasTaxIdType returns a boolean if a field has been set.

### GetBankId

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) GetBankId() string`

GetBankId returns the BankId field if non-nil, zero value otherwise.

### GetBankIdOk

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) GetBankIdOk() (*string, bool)`

GetBankIdOk returns a tuple with the BankId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankId

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) SetBankId(v string)`

SetBankId sets BankId field to given value.

### HasBankId

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) HasBankId() bool`

HasBankId returns a boolean if a field has been set.

### GetBankRoutingNo

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) GetBankRoutingNo() string`

GetBankRoutingNo returns the BankRoutingNo field if non-nil, zero value otherwise.

### GetBankRoutingNoOk

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) GetBankRoutingNoOk() (*string, bool)`

GetBankRoutingNoOk returns a tuple with the BankRoutingNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankRoutingNo

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) SetBankRoutingNo(v string)`

SetBankRoutingNo sets BankRoutingNo field to given value.

### HasBankRoutingNo

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) HasBankRoutingNo() bool`

HasBankRoutingNo returns a boolean if a field has been set.

### GetBankAccountNo

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) GetBankAccountNo() string`

GetBankAccountNo returns the BankAccountNo field if non-nil, zero value otherwise.

### GetBankAccountNoOk

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) GetBankAccountNoOk() (*string, bool)`

GetBankAccountNoOk returns a tuple with the BankAccountNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankAccountNo

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) SetBankAccountNo(v string)`

SetBankAccountNo sets BankAccountNo field to given value.

### HasBankAccountNo

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) HasBankAccountNo() bool`

HasBankAccountNo returns a boolean if a field has been set.

### GetBankName

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) GetBankName() string`

GetBankName returns the BankName field if non-nil, zero value otherwise.

### GetBankNameOk

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) GetBankNameOk() (*string, bool)`

GetBankNameOk returns a tuple with the BankName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankName

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) SetBankName(v string)`

SetBankName sets BankName field to given value.

### HasBankName

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) HasBankName() bool`

HasBankName returns a boolean if a field has been set.

### GetBankAddress

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) GetBankAddress() string`

GetBankAddress returns the BankAddress field if non-nil, zero value otherwise.

### GetBankAddressOk

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) GetBankAddressOk() (*string, bool)`

GetBankAddressOk returns a tuple with the BankAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankAddress

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) SetBankAddress(v string)`

SetBankAddress sets BankAddress field to given value.

### HasBankAddress

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) HasBankAddress() bool`

HasBankAddress returns a boolean if a field has been set.

### GetBankCity

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) GetBankCity() string`

GetBankCity returns the BankCity field if non-nil, zero value otherwise.

### GetBankCityOk

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) GetBankCityOk() (*string, bool)`

GetBankCityOk returns a tuple with the BankCity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankCity

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) SetBankCity(v string)`

SetBankCity sets BankCity field to given value.

### HasBankCity

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) HasBankCity() bool`

HasBankCity returns a boolean if a field has been set.

### GetBankState

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) GetBankState() string`

GetBankState returns the BankState field if non-nil, zero value otherwise.

### GetBankStateOk

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) GetBankStateOk() (*string, bool)`

GetBankStateOk returns a tuple with the BankState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankState

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) SetBankState(v string)`

SetBankState sets BankState field to given value.

### HasBankState

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) HasBankState() bool`

HasBankState returns a boolean if a field has been set.

### GetBankCountry

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) GetBankCountry() string`

GetBankCountry returns the BankCountry field if non-nil, zero value otherwise.

### GetBankCountryOk

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) GetBankCountryOk() (*string, bool)`

GetBankCountryOk returns a tuple with the BankCountry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankCountry

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) SetBankCountry(v string)`

SetBankCountry sets BankCountry field to given value.

### HasBankCountry

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) HasBankCountry() bool`

HasBankCountry returns a boolean if a field has been set.

### GetBankZipCode

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) GetBankZipCode() string`

GetBankZipCode returns the BankZipCode field if non-nil, zero value otherwise.

### GetBankZipCodeOk

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) GetBankZipCodeOk() (*string, bool)`

GetBankZipCodeOk returns a tuple with the BankZipCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankZipCode

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) SetBankZipCode(v string)`

SetBankZipCode sets BankZipCode field to given value.

### HasBankZipCode

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) HasBankZipCode() bool`

HasBankZipCode returns a boolean if a field has been set.

### GetSwiftNo

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) GetSwiftNo() string`

GetSwiftNo returns the SwiftNo field if non-nil, zero value otherwise.

### GetSwiftNoOk

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) GetSwiftNoOk() (*string, bool)`

GetSwiftNoOk returns a tuple with the SwiftNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSwiftNo

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) SetSwiftNo(v string)`

SetSwiftNo sets SwiftNo field to given value.

### HasSwiftNo

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) HasSwiftNo() bool`

HasSwiftNo returns a boolean if a field has been set.

### GetIbanNo

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) GetIbanNo() string`

GetIbanNo returns the IbanNo field if non-nil, zero value otherwise.

### GetIbanNoOk

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) GetIbanNoOk() (*string, bool)`

GetIbanNoOk returns a tuple with the IbanNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIbanNo

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) SetIbanNo(v string)`

SetIbanNo sets IbanNo field to given value.

### HasIbanNo

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) HasIbanNo() bool`

HasIbanNo returns a boolean if a field has been set.

### GetMisc1099

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) GetMisc1099() bool`

GetMisc1099 returns the Misc1099 field if non-nil, zero value otherwise.

### GetMisc1099Ok

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) GetMisc1099Ok() (*bool, bool)`

GetMisc1099Ok returns a tuple with the Misc1099 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMisc1099

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) SetMisc1099(v bool)`

SetMisc1099 sets Misc1099 field to given value.

### HasMisc1099

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) HasMisc1099() bool`

HasMisc1099 returns a boolean if a field has been set.

### GetBankAccountNoBankRemittanceCode

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) GetBankAccountNoBankRemittanceCode() string`

GetBankAccountNoBankRemittanceCode returns the BankAccountNoBankRemittanceCode field if non-nil, zero value otherwise.

### GetBankAccountNoBankRemittanceCodeOk

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) GetBankAccountNoBankRemittanceCodeOk() (*string, bool)`

GetBankAccountNoBankRemittanceCodeOk returns a tuple with the BankAccountNoBankRemittanceCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankAccountNoBankRemittanceCode

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) SetBankAccountNoBankRemittanceCode(v string)`

SetBankAccountNoBankRemittanceCode sets BankAccountNoBankRemittanceCode field to given value.

### HasBankAccountNoBankRemittanceCode

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) HasBankAccountNoBankRemittanceCode() bool`

HasBankAccountNoBankRemittanceCode returns a boolean if a field has been set.

### GetBankAccountCurrencyCode

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) GetBankAccountCurrencyCode() string`

GetBankAccountCurrencyCode returns the BankAccountCurrencyCode field if non-nil, zero value otherwise.

### GetBankAccountCurrencyCodeOk

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) GetBankAccountCurrencyCodeOk() (*string, bool)`

GetBankAccountCurrencyCodeOk returns a tuple with the BankAccountCurrencyCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankAccountCurrencyCode

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) SetBankAccountCurrencyCode(v string)`

SetBankAccountCurrencyCode sets BankAccountCurrencyCode field to given value.

### HasBankAccountCurrencyCode

`func (o *SuppliersApiUpdateSupplierFinancialsRequest) HasBankAccountCurrencyCode() bool`

HasBankAccountCurrencyCode returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


