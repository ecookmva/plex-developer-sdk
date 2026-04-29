# SuppliersApiGetSupplierFinancialsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DunsNo** | Pointer to **string** |  | [optional] 
**PaymentStatus** | Pointer to **string** | Setup Table: Payment_Status | [optional] 
**PaymentType** | Pointer to **string** | Screen: Payment Type | [optional] 
**BankRemittanceCode** | Pointer to **string** | Setup Table: Supplier_Bank_Remittance | [optional] 
**PaymentSupplierId** | Pointer to **string** | The default value is the ID of the current Supplier. | [optional] 
**TaxId** | Pointer to **string** |  | [optional] 
**TaxIdType** | Pointer to **string** |  | [optional] 
**BankId** | Pointer to **string** |  | [optional] 
**BankRoutingNo** | Pointer to **string** |  | [optional] 
**BankAccountNo** | Pointer to **string** |  | [optional] 
**BankName** | Pointer to **string** |  | [optional] 
**BankAddress** | Pointer to **string** |  | [optional] 
**BankCity** | Pointer to **string** |  | [optional] 
**BankState** | Pointer to **string** |  | [optional] 
**BankCountry** | Pointer to **string** |  | [optional] 
**BankZipCode** | Pointer to **string** |  | [optional] 
**SwiftNo** | Pointer to **string** |  | [optional] 
**IbanNo** | Pointer to **string** |  | [optional] 
**Misc1099** | Pointer to **bool** | Defines the supplier as 1099. This displays the 1099 check box on supplier invoices. When enabled, supplier invoices are flagged as 1099 by default. | [optional] 

## Methods

### NewSuppliersApiGetSupplierFinancialsResponse

`func NewSuppliersApiGetSupplierFinancialsResponse() *SuppliersApiGetSupplierFinancialsResponse`

NewSuppliersApiGetSupplierFinancialsResponse instantiates a new SuppliersApiGetSupplierFinancialsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSuppliersApiGetSupplierFinancialsResponseWithDefaults

`func NewSuppliersApiGetSupplierFinancialsResponseWithDefaults() *SuppliersApiGetSupplierFinancialsResponse`

NewSuppliersApiGetSupplierFinancialsResponseWithDefaults instantiates a new SuppliersApiGetSupplierFinancialsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDunsNo

`func (o *SuppliersApiGetSupplierFinancialsResponse) GetDunsNo() string`

GetDunsNo returns the DunsNo field if non-nil, zero value otherwise.

### GetDunsNoOk

`func (o *SuppliersApiGetSupplierFinancialsResponse) GetDunsNoOk() (*string, bool)`

GetDunsNoOk returns a tuple with the DunsNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDunsNo

`func (o *SuppliersApiGetSupplierFinancialsResponse) SetDunsNo(v string)`

SetDunsNo sets DunsNo field to given value.

### HasDunsNo

`func (o *SuppliersApiGetSupplierFinancialsResponse) HasDunsNo() bool`

HasDunsNo returns a boolean if a field has been set.

### GetPaymentStatus

`func (o *SuppliersApiGetSupplierFinancialsResponse) GetPaymentStatus() string`

GetPaymentStatus returns the PaymentStatus field if non-nil, zero value otherwise.

### GetPaymentStatusOk

`func (o *SuppliersApiGetSupplierFinancialsResponse) GetPaymentStatusOk() (*string, bool)`

GetPaymentStatusOk returns a tuple with the PaymentStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentStatus

`func (o *SuppliersApiGetSupplierFinancialsResponse) SetPaymentStatus(v string)`

SetPaymentStatus sets PaymentStatus field to given value.

### HasPaymentStatus

`func (o *SuppliersApiGetSupplierFinancialsResponse) HasPaymentStatus() bool`

HasPaymentStatus returns a boolean if a field has been set.

### GetPaymentType

`func (o *SuppliersApiGetSupplierFinancialsResponse) GetPaymentType() string`

GetPaymentType returns the PaymentType field if non-nil, zero value otherwise.

### GetPaymentTypeOk

`func (o *SuppliersApiGetSupplierFinancialsResponse) GetPaymentTypeOk() (*string, bool)`

GetPaymentTypeOk returns a tuple with the PaymentType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentType

`func (o *SuppliersApiGetSupplierFinancialsResponse) SetPaymentType(v string)`

SetPaymentType sets PaymentType field to given value.

### HasPaymentType

`func (o *SuppliersApiGetSupplierFinancialsResponse) HasPaymentType() bool`

HasPaymentType returns a boolean if a field has been set.

### GetBankRemittanceCode

`func (o *SuppliersApiGetSupplierFinancialsResponse) GetBankRemittanceCode() string`

GetBankRemittanceCode returns the BankRemittanceCode field if non-nil, zero value otherwise.

### GetBankRemittanceCodeOk

`func (o *SuppliersApiGetSupplierFinancialsResponse) GetBankRemittanceCodeOk() (*string, bool)`

GetBankRemittanceCodeOk returns a tuple with the BankRemittanceCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankRemittanceCode

`func (o *SuppliersApiGetSupplierFinancialsResponse) SetBankRemittanceCode(v string)`

SetBankRemittanceCode sets BankRemittanceCode field to given value.

### HasBankRemittanceCode

`func (o *SuppliersApiGetSupplierFinancialsResponse) HasBankRemittanceCode() bool`

HasBankRemittanceCode returns a boolean if a field has been set.

### GetPaymentSupplierId

`func (o *SuppliersApiGetSupplierFinancialsResponse) GetPaymentSupplierId() string`

GetPaymentSupplierId returns the PaymentSupplierId field if non-nil, zero value otherwise.

### GetPaymentSupplierIdOk

`func (o *SuppliersApiGetSupplierFinancialsResponse) GetPaymentSupplierIdOk() (*string, bool)`

GetPaymentSupplierIdOk returns a tuple with the PaymentSupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentSupplierId

`func (o *SuppliersApiGetSupplierFinancialsResponse) SetPaymentSupplierId(v string)`

SetPaymentSupplierId sets PaymentSupplierId field to given value.

### HasPaymentSupplierId

`func (o *SuppliersApiGetSupplierFinancialsResponse) HasPaymentSupplierId() bool`

HasPaymentSupplierId returns a boolean if a field has been set.

### GetTaxId

`func (o *SuppliersApiGetSupplierFinancialsResponse) GetTaxId() string`

GetTaxId returns the TaxId field if non-nil, zero value otherwise.

### GetTaxIdOk

`func (o *SuppliersApiGetSupplierFinancialsResponse) GetTaxIdOk() (*string, bool)`

GetTaxIdOk returns a tuple with the TaxId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxId

`func (o *SuppliersApiGetSupplierFinancialsResponse) SetTaxId(v string)`

SetTaxId sets TaxId field to given value.

### HasTaxId

`func (o *SuppliersApiGetSupplierFinancialsResponse) HasTaxId() bool`

HasTaxId returns a boolean if a field has been set.

### GetTaxIdType

`func (o *SuppliersApiGetSupplierFinancialsResponse) GetTaxIdType() string`

GetTaxIdType returns the TaxIdType field if non-nil, zero value otherwise.

### GetTaxIdTypeOk

`func (o *SuppliersApiGetSupplierFinancialsResponse) GetTaxIdTypeOk() (*string, bool)`

GetTaxIdTypeOk returns a tuple with the TaxIdType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxIdType

`func (o *SuppliersApiGetSupplierFinancialsResponse) SetTaxIdType(v string)`

SetTaxIdType sets TaxIdType field to given value.

### HasTaxIdType

`func (o *SuppliersApiGetSupplierFinancialsResponse) HasTaxIdType() bool`

HasTaxIdType returns a boolean if a field has been set.

### GetBankId

`func (o *SuppliersApiGetSupplierFinancialsResponse) GetBankId() string`

GetBankId returns the BankId field if non-nil, zero value otherwise.

### GetBankIdOk

`func (o *SuppliersApiGetSupplierFinancialsResponse) GetBankIdOk() (*string, bool)`

GetBankIdOk returns a tuple with the BankId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankId

`func (o *SuppliersApiGetSupplierFinancialsResponse) SetBankId(v string)`

SetBankId sets BankId field to given value.

### HasBankId

`func (o *SuppliersApiGetSupplierFinancialsResponse) HasBankId() bool`

HasBankId returns a boolean if a field has been set.

### GetBankRoutingNo

`func (o *SuppliersApiGetSupplierFinancialsResponse) GetBankRoutingNo() string`

GetBankRoutingNo returns the BankRoutingNo field if non-nil, zero value otherwise.

### GetBankRoutingNoOk

`func (o *SuppliersApiGetSupplierFinancialsResponse) GetBankRoutingNoOk() (*string, bool)`

GetBankRoutingNoOk returns a tuple with the BankRoutingNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankRoutingNo

`func (o *SuppliersApiGetSupplierFinancialsResponse) SetBankRoutingNo(v string)`

SetBankRoutingNo sets BankRoutingNo field to given value.

### HasBankRoutingNo

`func (o *SuppliersApiGetSupplierFinancialsResponse) HasBankRoutingNo() bool`

HasBankRoutingNo returns a boolean if a field has been set.

### GetBankAccountNo

`func (o *SuppliersApiGetSupplierFinancialsResponse) GetBankAccountNo() string`

GetBankAccountNo returns the BankAccountNo field if non-nil, zero value otherwise.

### GetBankAccountNoOk

`func (o *SuppliersApiGetSupplierFinancialsResponse) GetBankAccountNoOk() (*string, bool)`

GetBankAccountNoOk returns a tuple with the BankAccountNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankAccountNo

`func (o *SuppliersApiGetSupplierFinancialsResponse) SetBankAccountNo(v string)`

SetBankAccountNo sets BankAccountNo field to given value.

### HasBankAccountNo

`func (o *SuppliersApiGetSupplierFinancialsResponse) HasBankAccountNo() bool`

HasBankAccountNo returns a boolean if a field has been set.

### GetBankName

`func (o *SuppliersApiGetSupplierFinancialsResponse) GetBankName() string`

GetBankName returns the BankName field if non-nil, zero value otherwise.

### GetBankNameOk

`func (o *SuppliersApiGetSupplierFinancialsResponse) GetBankNameOk() (*string, bool)`

GetBankNameOk returns a tuple with the BankName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankName

`func (o *SuppliersApiGetSupplierFinancialsResponse) SetBankName(v string)`

SetBankName sets BankName field to given value.

### HasBankName

`func (o *SuppliersApiGetSupplierFinancialsResponse) HasBankName() bool`

HasBankName returns a boolean if a field has been set.

### GetBankAddress

`func (o *SuppliersApiGetSupplierFinancialsResponse) GetBankAddress() string`

GetBankAddress returns the BankAddress field if non-nil, zero value otherwise.

### GetBankAddressOk

`func (o *SuppliersApiGetSupplierFinancialsResponse) GetBankAddressOk() (*string, bool)`

GetBankAddressOk returns a tuple with the BankAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankAddress

`func (o *SuppliersApiGetSupplierFinancialsResponse) SetBankAddress(v string)`

SetBankAddress sets BankAddress field to given value.

### HasBankAddress

`func (o *SuppliersApiGetSupplierFinancialsResponse) HasBankAddress() bool`

HasBankAddress returns a boolean if a field has been set.

### GetBankCity

`func (o *SuppliersApiGetSupplierFinancialsResponse) GetBankCity() string`

GetBankCity returns the BankCity field if non-nil, zero value otherwise.

### GetBankCityOk

`func (o *SuppliersApiGetSupplierFinancialsResponse) GetBankCityOk() (*string, bool)`

GetBankCityOk returns a tuple with the BankCity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankCity

`func (o *SuppliersApiGetSupplierFinancialsResponse) SetBankCity(v string)`

SetBankCity sets BankCity field to given value.

### HasBankCity

`func (o *SuppliersApiGetSupplierFinancialsResponse) HasBankCity() bool`

HasBankCity returns a boolean if a field has been set.

### GetBankState

`func (o *SuppliersApiGetSupplierFinancialsResponse) GetBankState() string`

GetBankState returns the BankState field if non-nil, zero value otherwise.

### GetBankStateOk

`func (o *SuppliersApiGetSupplierFinancialsResponse) GetBankStateOk() (*string, bool)`

GetBankStateOk returns a tuple with the BankState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankState

`func (o *SuppliersApiGetSupplierFinancialsResponse) SetBankState(v string)`

SetBankState sets BankState field to given value.

### HasBankState

`func (o *SuppliersApiGetSupplierFinancialsResponse) HasBankState() bool`

HasBankState returns a boolean if a field has been set.

### GetBankCountry

`func (o *SuppliersApiGetSupplierFinancialsResponse) GetBankCountry() string`

GetBankCountry returns the BankCountry field if non-nil, zero value otherwise.

### GetBankCountryOk

`func (o *SuppliersApiGetSupplierFinancialsResponse) GetBankCountryOk() (*string, bool)`

GetBankCountryOk returns a tuple with the BankCountry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankCountry

`func (o *SuppliersApiGetSupplierFinancialsResponse) SetBankCountry(v string)`

SetBankCountry sets BankCountry field to given value.

### HasBankCountry

`func (o *SuppliersApiGetSupplierFinancialsResponse) HasBankCountry() bool`

HasBankCountry returns a boolean if a field has been set.

### GetBankZipCode

`func (o *SuppliersApiGetSupplierFinancialsResponse) GetBankZipCode() string`

GetBankZipCode returns the BankZipCode field if non-nil, zero value otherwise.

### GetBankZipCodeOk

`func (o *SuppliersApiGetSupplierFinancialsResponse) GetBankZipCodeOk() (*string, bool)`

GetBankZipCodeOk returns a tuple with the BankZipCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankZipCode

`func (o *SuppliersApiGetSupplierFinancialsResponse) SetBankZipCode(v string)`

SetBankZipCode sets BankZipCode field to given value.

### HasBankZipCode

`func (o *SuppliersApiGetSupplierFinancialsResponse) HasBankZipCode() bool`

HasBankZipCode returns a boolean if a field has been set.

### GetSwiftNo

`func (o *SuppliersApiGetSupplierFinancialsResponse) GetSwiftNo() string`

GetSwiftNo returns the SwiftNo field if non-nil, zero value otherwise.

### GetSwiftNoOk

`func (o *SuppliersApiGetSupplierFinancialsResponse) GetSwiftNoOk() (*string, bool)`

GetSwiftNoOk returns a tuple with the SwiftNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSwiftNo

`func (o *SuppliersApiGetSupplierFinancialsResponse) SetSwiftNo(v string)`

SetSwiftNo sets SwiftNo field to given value.

### HasSwiftNo

`func (o *SuppliersApiGetSupplierFinancialsResponse) HasSwiftNo() bool`

HasSwiftNo returns a boolean if a field has been set.

### GetIbanNo

`func (o *SuppliersApiGetSupplierFinancialsResponse) GetIbanNo() string`

GetIbanNo returns the IbanNo field if non-nil, zero value otherwise.

### GetIbanNoOk

`func (o *SuppliersApiGetSupplierFinancialsResponse) GetIbanNoOk() (*string, bool)`

GetIbanNoOk returns a tuple with the IbanNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIbanNo

`func (o *SuppliersApiGetSupplierFinancialsResponse) SetIbanNo(v string)`

SetIbanNo sets IbanNo field to given value.

### HasIbanNo

`func (o *SuppliersApiGetSupplierFinancialsResponse) HasIbanNo() bool`

HasIbanNo returns a boolean if a field has been set.

### GetMisc1099

`func (o *SuppliersApiGetSupplierFinancialsResponse) GetMisc1099() bool`

GetMisc1099 returns the Misc1099 field if non-nil, zero value otherwise.

### GetMisc1099Ok

`func (o *SuppliersApiGetSupplierFinancialsResponse) GetMisc1099Ok() (*bool, bool)`

GetMisc1099Ok returns a tuple with the Misc1099 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMisc1099

`func (o *SuppliersApiGetSupplierFinancialsResponse) SetMisc1099(v bool)`

SetMisc1099 sets Misc1099 field to given value.

### HasMisc1099

`func (o *SuppliersApiGetSupplierFinancialsResponse) HasMisc1099() bool`

HasMisc1099 returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


