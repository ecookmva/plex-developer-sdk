# SuppliersApiSyncSuppliersRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | A unique identifier for the supplier address. This will be automatically generated if omitted from the request. | [optional] 
**Code** | Pointer to **string** | This must be unique in the context of a supplier. | [optional] 
**OldCode** | Pointer to **string** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Language** | Pointer to **string** |  | [optional] 
**Category** | Pointer to **string** | Setup Table: Supplier_Category | [optional] 
**Status** | Pointer to **string** | Setup Table: Supplier_Status | [optional] 
**Type** | Pointer to **string** | Setup Table: Supplier_Address_Type. | [optional] 
**ParentSupplierId** | Pointer to **string** | The ID of a parent supplier. | [optional] 
**WebAddress** | Pointer to **string** |  | [optional] 
**ContactNote** | Pointer to **string** |  | [optional] 
**Note** | Pointer to **string** |  | [optional] 
**Financials** | Pointer to [**Financials1**](Financials1.md) |  | [optional] 
**PurchasingDefaults** | Pointer to [**PurchasingDefaults**](PurchasingDefaults.md) |  | [optional] 
**Addresses** | Pointer to [**[]AddressesItem1**](AddressesItem1.md) | A list of supplier addresses. | [optional] 
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
**DefaultCarrierId** | Pointer to **string** | This is the ID of another supplier that has their supplier type flagged as a Carrier. | [optional] 
**Customs** | Pointer to **string** | Setup Table: Customs | [optional] 
**DefaultShipTo** | Pointer to **string** | Screen: PO Ship To | [optional] 
**DefaultShipVia** | Pointer to **string** | Setup Table: PO_Ship_Via | [optional] 
**DefaultFreightTerms** | Pointer to **string** | Setup Table: PO_Freight_Terms | [optional] 
**DefaultINCOTerms** | Pointer to **string** | Setup Table: INCO_Terms | [optional] 
**DefaultFOB** | Pointer to **string** | Setup Table: PO_FOB | [optional] 
**DefaultPaymentTerms** | Pointer to **string** | Setup Table: Terms | [optional] 
**DefaultCurrencyCode** | Pointer to **string** |  | [optional] 
**DefaultTaxCode** | Pointer to **string** | Screen: Tax Codes | [optional] 
**DefaultPOType** | Pointer to **string** | Screen: PO Type | [optional] 
**DefaultExpenseAccount** | Pointer to **string** | Screen: Chart of Accounts | [optional] 
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

### NewSuppliersApiSyncSuppliersRequest

`func NewSuppliersApiSyncSuppliersRequest() *SuppliersApiSyncSuppliersRequest`

NewSuppliersApiSyncSuppliersRequest instantiates a new SuppliersApiSyncSuppliersRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSuppliersApiSyncSuppliersRequestWithDefaults

`func NewSuppliersApiSyncSuppliersRequestWithDefaults() *SuppliersApiSyncSuppliersRequest`

NewSuppliersApiSyncSuppliersRequestWithDefaults instantiates a new SuppliersApiSyncSuppliersRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SuppliersApiSyncSuppliersRequest) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SuppliersApiSyncSuppliersRequest) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SuppliersApiSyncSuppliersRequest) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *SuppliersApiSyncSuppliersRequest) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCode

`func (o *SuppliersApiSyncSuppliersRequest) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *SuppliersApiSyncSuppliersRequest) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *SuppliersApiSyncSuppliersRequest) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *SuppliersApiSyncSuppliersRequest) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetOldCode

`func (o *SuppliersApiSyncSuppliersRequest) GetOldCode() string`

GetOldCode returns the OldCode field if non-nil, zero value otherwise.

### GetOldCodeOk

`func (o *SuppliersApiSyncSuppliersRequest) GetOldCodeOk() (*string, bool)`

GetOldCodeOk returns a tuple with the OldCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOldCode

`func (o *SuppliersApiSyncSuppliersRequest) SetOldCode(v string)`

SetOldCode sets OldCode field to given value.

### HasOldCode

`func (o *SuppliersApiSyncSuppliersRequest) HasOldCode() bool`

HasOldCode returns a boolean if a field has been set.

### GetName

`func (o *SuppliersApiSyncSuppliersRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *SuppliersApiSyncSuppliersRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *SuppliersApiSyncSuppliersRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *SuppliersApiSyncSuppliersRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### GetLanguage

`func (o *SuppliersApiSyncSuppliersRequest) GetLanguage() string`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *SuppliersApiSyncSuppliersRequest) GetLanguageOk() (*string, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *SuppliersApiSyncSuppliersRequest) SetLanguage(v string)`

SetLanguage sets Language field to given value.

### HasLanguage

`func (o *SuppliersApiSyncSuppliersRequest) HasLanguage() bool`

HasLanguage returns a boolean if a field has been set.

### GetCategory

`func (o *SuppliersApiSyncSuppliersRequest) GetCategory() string`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *SuppliersApiSyncSuppliersRequest) GetCategoryOk() (*string, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *SuppliersApiSyncSuppliersRequest) SetCategory(v string)`

SetCategory sets Category field to given value.

### HasCategory

`func (o *SuppliersApiSyncSuppliersRequest) HasCategory() bool`

HasCategory returns a boolean if a field has been set.

### GetStatus

`func (o *SuppliersApiSyncSuppliersRequest) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *SuppliersApiSyncSuppliersRequest) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *SuppliersApiSyncSuppliersRequest) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *SuppliersApiSyncSuppliersRequest) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetType

`func (o *SuppliersApiSyncSuppliersRequest) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *SuppliersApiSyncSuppliersRequest) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *SuppliersApiSyncSuppliersRequest) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *SuppliersApiSyncSuppliersRequest) HasType() bool`

HasType returns a boolean if a field has been set.

### GetParentSupplierId

`func (o *SuppliersApiSyncSuppliersRequest) GetParentSupplierId() string`

GetParentSupplierId returns the ParentSupplierId field if non-nil, zero value otherwise.

### GetParentSupplierIdOk

`func (o *SuppliersApiSyncSuppliersRequest) GetParentSupplierIdOk() (*string, bool)`

GetParentSupplierIdOk returns a tuple with the ParentSupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentSupplierId

`func (o *SuppliersApiSyncSuppliersRequest) SetParentSupplierId(v string)`

SetParentSupplierId sets ParentSupplierId field to given value.

### HasParentSupplierId

`func (o *SuppliersApiSyncSuppliersRequest) HasParentSupplierId() bool`

HasParentSupplierId returns a boolean if a field has been set.

### GetWebAddress

`func (o *SuppliersApiSyncSuppliersRequest) GetWebAddress() string`

GetWebAddress returns the WebAddress field if non-nil, zero value otherwise.

### GetWebAddressOk

`func (o *SuppliersApiSyncSuppliersRequest) GetWebAddressOk() (*string, bool)`

GetWebAddressOk returns a tuple with the WebAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebAddress

`func (o *SuppliersApiSyncSuppliersRequest) SetWebAddress(v string)`

SetWebAddress sets WebAddress field to given value.

### HasWebAddress

`func (o *SuppliersApiSyncSuppliersRequest) HasWebAddress() bool`

HasWebAddress returns a boolean if a field has been set.

### GetContactNote

`func (o *SuppliersApiSyncSuppliersRequest) GetContactNote() string`

GetContactNote returns the ContactNote field if non-nil, zero value otherwise.

### GetContactNoteOk

`func (o *SuppliersApiSyncSuppliersRequest) GetContactNoteOk() (*string, bool)`

GetContactNoteOk returns a tuple with the ContactNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactNote

`func (o *SuppliersApiSyncSuppliersRequest) SetContactNote(v string)`

SetContactNote sets ContactNote field to given value.

### HasContactNote

`func (o *SuppliersApiSyncSuppliersRequest) HasContactNote() bool`

HasContactNote returns a boolean if a field has been set.

### GetNote

`func (o *SuppliersApiSyncSuppliersRequest) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *SuppliersApiSyncSuppliersRequest) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *SuppliersApiSyncSuppliersRequest) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *SuppliersApiSyncSuppliersRequest) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetFinancials

`func (o *SuppliersApiSyncSuppliersRequest) GetFinancials() Financials1`

GetFinancials returns the Financials field if non-nil, zero value otherwise.

### GetFinancialsOk

`func (o *SuppliersApiSyncSuppliersRequest) GetFinancialsOk() (*Financials1, bool)`

GetFinancialsOk returns a tuple with the Financials field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFinancials

`func (o *SuppliersApiSyncSuppliersRequest) SetFinancials(v Financials1)`

SetFinancials sets Financials field to given value.

### HasFinancials

`func (o *SuppliersApiSyncSuppliersRequest) HasFinancials() bool`

HasFinancials returns a boolean if a field has been set.

### GetPurchasingDefaults

`func (o *SuppliersApiSyncSuppliersRequest) GetPurchasingDefaults() PurchasingDefaults`

GetPurchasingDefaults returns the PurchasingDefaults field if non-nil, zero value otherwise.

### GetPurchasingDefaultsOk

`func (o *SuppliersApiSyncSuppliersRequest) GetPurchasingDefaultsOk() (*PurchasingDefaults, bool)`

GetPurchasingDefaultsOk returns a tuple with the PurchasingDefaults field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPurchasingDefaults

`func (o *SuppliersApiSyncSuppliersRequest) SetPurchasingDefaults(v PurchasingDefaults)`

SetPurchasingDefaults sets PurchasingDefaults field to given value.

### HasPurchasingDefaults

`func (o *SuppliersApiSyncSuppliersRequest) HasPurchasingDefaults() bool`

HasPurchasingDefaults returns a boolean if a field has been set.

### GetAddresses

`func (o *SuppliersApiSyncSuppliersRequest) GetAddresses() []AddressesItem1`

GetAddresses returns the Addresses field if non-nil, zero value otherwise.

### GetAddressesOk

`func (o *SuppliersApiSyncSuppliersRequest) GetAddressesOk() (*[]AddressesItem1, bool)`

GetAddressesOk returns a tuple with the Addresses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddresses

`func (o *SuppliersApiSyncSuppliersRequest) SetAddresses(v []AddressesItem1)`

SetAddresses sets Addresses field to given value.

### HasAddresses

`func (o *SuppliersApiSyncSuppliersRequest) HasAddresses() bool`

HasAddresses returns a boolean if a field has been set.

### GetDunsNo

`func (o *SuppliersApiSyncSuppliersRequest) GetDunsNo() string`

GetDunsNo returns the DunsNo field if non-nil, zero value otherwise.

### GetDunsNoOk

`func (o *SuppliersApiSyncSuppliersRequest) GetDunsNoOk() (*string, bool)`

GetDunsNoOk returns a tuple with the DunsNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDunsNo

`func (o *SuppliersApiSyncSuppliersRequest) SetDunsNo(v string)`

SetDunsNo sets DunsNo field to given value.

### HasDunsNo

`func (o *SuppliersApiSyncSuppliersRequest) HasDunsNo() bool`

HasDunsNo returns a boolean if a field has been set.

### GetPaymentStatus

`func (o *SuppliersApiSyncSuppliersRequest) GetPaymentStatus() string`

GetPaymentStatus returns the PaymentStatus field if non-nil, zero value otherwise.

### GetPaymentStatusOk

`func (o *SuppliersApiSyncSuppliersRequest) GetPaymentStatusOk() (*string, bool)`

GetPaymentStatusOk returns a tuple with the PaymentStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentStatus

`func (o *SuppliersApiSyncSuppliersRequest) SetPaymentStatus(v string)`

SetPaymentStatus sets PaymentStatus field to given value.

### HasPaymentStatus

`func (o *SuppliersApiSyncSuppliersRequest) HasPaymentStatus() bool`

HasPaymentStatus returns a boolean if a field has been set.

### GetPaymentType

`func (o *SuppliersApiSyncSuppliersRequest) GetPaymentType() string`

GetPaymentType returns the PaymentType field if non-nil, zero value otherwise.

### GetPaymentTypeOk

`func (o *SuppliersApiSyncSuppliersRequest) GetPaymentTypeOk() (*string, bool)`

GetPaymentTypeOk returns a tuple with the PaymentType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentType

`func (o *SuppliersApiSyncSuppliersRequest) SetPaymentType(v string)`

SetPaymentType sets PaymentType field to given value.

### HasPaymentType

`func (o *SuppliersApiSyncSuppliersRequest) HasPaymentType() bool`

HasPaymentType returns a boolean if a field has been set.

### GetBankRemittanceCode

`func (o *SuppliersApiSyncSuppliersRequest) GetBankRemittanceCode() string`

GetBankRemittanceCode returns the BankRemittanceCode field if non-nil, zero value otherwise.

### GetBankRemittanceCodeOk

`func (o *SuppliersApiSyncSuppliersRequest) GetBankRemittanceCodeOk() (*string, bool)`

GetBankRemittanceCodeOk returns a tuple with the BankRemittanceCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankRemittanceCode

`func (o *SuppliersApiSyncSuppliersRequest) SetBankRemittanceCode(v string)`

SetBankRemittanceCode sets BankRemittanceCode field to given value.

### HasBankRemittanceCode

`func (o *SuppliersApiSyncSuppliersRequest) HasBankRemittanceCode() bool`

HasBankRemittanceCode returns a boolean if a field has been set.

### GetPaymentSupplierId

`func (o *SuppliersApiSyncSuppliersRequest) GetPaymentSupplierId() string`

GetPaymentSupplierId returns the PaymentSupplierId field if non-nil, zero value otherwise.

### GetPaymentSupplierIdOk

`func (o *SuppliersApiSyncSuppliersRequest) GetPaymentSupplierIdOk() (*string, bool)`

GetPaymentSupplierIdOk returns a tuple with the PaymentSupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentSupplierId

`func (o *SuppliersApiSyncSuppliersRequest) SetPaymentSupplierId(v string)`

SetPaymentSupplierId sets PaymentSupplierId field to given value.

### HasPaymentSupplierId

`func (o *SuppliersApiSyncSuppliersRequest) HasPaymentSupplierId() bool`

HasPaymentSupplierId returns a boolean if a field has been set.

### GetTaxId

`func (o *SuppliersApiSyncSuppliersRequest) GetTaxId() string`

GetTaxId returns the TaxId field if non-nil, zero value otherwise.

### GetTaxIdOk

`func (o *SuppliersApiSyncSuppliersRequest) GetTaxIdOk() (*string, bool)`

GetTaxIdOk returns a tuple with the TaxId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxId

`func (o *SuppliersApiSyncSuppliersRequest) SetTaxId(v string)`

SetTaxId sets TaxId field to given value.

### HasTaxId

`func (o *SuppliersApiSyncSuppliersRequest) HasTaxId() bool`

HasTaxId returns a boolean if a field has been set.

### GetTaxIdType

`func (o *SuppliersApiSyncSuppliersRequest) GetTaxIdType() string`

GetTaxIdType returns the TaxIdType field if non-nil, zero value otherwise.

### GetTaxIdTypeOk

`func (o *SuppliersApiSyncSuppliersRequest) GetTaxIdTypeOk() (*string, bool)`

GetTaxIdTypeOk returns a tuple with the TaxIdType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxIdType

`func (o *SuppliersApiSyncSuppliersRequest) SetTaxIdType(v string)`

SetTaxIdType sets TaxIdType field to given value.

### HasTaxIdType

`func (o *SuppliersApiSyncSuppliersRequest) HasTaxIdType() bool`

HasTaxIdType returns a boolean if a field has been set.

### GetBankId

`func (o *SuppliersApiSyncSuppliersRequest) GetBankId() string`

GetBankId returns the BankId field if non-nil, zero value otherwise.

### GetBankIdOk

`func (o *SuppliersApiSyncSuppliersRequest) GetBankIdOk() (*string, bool)`

GetBankIdOk returns a tuple with the BankId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankId

`func (o *SuppliersApiSyncSuppliersRequest) SetBankId(v string)`

SetBankId sets BankId field to given value.

### HasBankId

`func (o *SuppliersApiSyncSuppliersRequest) HasBankId() bool`

HasBankId returns a boolean if a field has been set.

### GetBankRoutingNo

`func (o *SuppliersApiSyncSuppliersRequest) GetBankRoutingNo() string`

GetBankRoutingNo returns the BankRoutingNo field if non-nil, zero value otherwise.

### GetBankRoutingNoOk

`func (o *SuppliersApiSyncSuppliersRequest) GetBankRoutingNoOk() (*string, bool)`

GetBankRoutingNoOk returns a tuple with the BankRoutingNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankRoutingNo

`func (o *SuppliersApiSyncSuppliersRequest) SetBankRoutingNo(v string)`

SetBankRoutingNo sets BankRoutingNo field to given value.

### HasBankRoutingNo

`func (o *SuppliersApiSyncSuppliersRequest) HasBankRoutingNo() bool`

HasBankRoutingNo returns a boolean if a field has been set.

### GetBankAccountNo

`func (o *SuppliersApiSyncSuppliersRequest) GetBankAccountNo() string`

GetBankAccountNo returns the BankAccountNo field if non-nil, zero value otherwise.

### GetBankAccountNoOk

`func (o *SuppliersApiSyncSuppliersRequest) GetBankAccountNoOk() (*string, bool)`

GetBankAccountNoOk returns a tuple with the BankAccountNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankAccountNo

`func (o *SuppliersApiSyncSuppliersRequest) SetBankAccountNo(v string)`

SetBankAccountNo sets BankAccountNo field to given value.

### HasBankAccountNo

`func (o *SuppliersApiSyncSuppliersRequest) HasBankAccountNo() bool`

HasBankAccountNo returns a boolean if a field has been set.

### GetBankName

`func (o *SuppliersApiSyncSuppliersRequest) GetBankName() string`

GetBankName returns the BankName field if non-nil, zero value otherwise.

### GetBankNameOk

`func (o *SuppliersApiSyncSuppliersRequest) GetBankNameOk() (*string, bool)`

GetBankNameOk returns a tuple with the BankName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankName

`func (o *SuppliersApiSyncSuppliersRequest) SetBankName(v string)`

SetBankName sets BankName field to given value.

### HasBankName

`func (o *SuppliersApiSyncSuppliersRequest) HasBankName() bool`

HasBankName returns a boolean if a field has been set.

### GetBankAddress

`func (o *SuppliersApiSyncSuppliersRequest) GetBankAddress() string`

GetBankAddress returns the BankAddress field if non-nil, zero value otherwise.

### GetBankAddressOk

`func (o *SuppliersApiSyncSuppliersRequest) GetBankAddressOk() (*string, bool)`

GetBankAddressOk returns a tuple with the BankAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankAddress

`func (o *SuppliersApiSyncSuppliersRequest) SetBankAddress(v string)`

SetBankAddress sets BankAddress field to given value.

### HasBankAddress

`func (o *SuppliersApiSyncSuppliersRequest) HasBankAddress() bool`

HasBankAddress returns a boolean if a field has been set.

### GetBankCity

`func (o *SuppliersApiSyncSuppliersRequest) GetBankCity() string`

GetBankCity returns the BankCity field if non-nil, zero value otherwise.

### GetBankCityOk

`func (o *SuppliersApiSyncSuppliersRequest) GetBankCityOk() (*string, bool)`

GetBankCityOk returns a tuple with the BankCity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankCity

`func (o *SuppliersApiSyncSuppliersRequest) SetBankCity(v string)`

SetBankCity sets BankCity field to given value.

### HasBankCity

`func (o *SuppliersApiSyncSuppliersRequest) HasBankCity() bool`

HasBankCity returns a boolean if a field has been set.

### GetBankState

`func (o *SuppliersApiSyncSuppliersRequest) GetBankState() string`

GetBankState returns the BankState field if non-nil, zero value otherwise.

### GetBankStateOk

`func (o *SuppliersApiSyncSuppliersRequest) GetBankStateOk() (*string, bool)`

GetBankStateOk returns a tuple with the BankState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankState

`func (o *SuppliersApiSyncSuppliersRequest) SetBankState(v string)`

SetBankState sets BankState field to given value.

### HasBankState

`func (o *SuppliersApiSyncSuppliersRequest) HasBankState() bool`

HasBankState returns a boolean if a field has been set.

### GetBankCountry

`func (o *SuppliersApiSyncSuppliersRequest) GetBankCountry() string`

GetBankCountry returns the BankCountry field if non-nil, zero value otherwise.

### GetBankCountryOk

`func (o *SuppliersApiSyncSuppliersRequest) GetBankCountryOk() (*string, bool)`

GetBankCountryOk returns a tuple with the BankCountry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankCountry

`func (o *SuppliersApiSyncSuppliersRequest) SetBankCountry(v string)`

SetBankCountry sets BankCountry field to given value.

### HasBankCountry

`func (o *SuppliersApiSyncSuppliersRequest) HasBankCountry() bool`

HasBankCountry returns a boolean if a field has been set.

### GetBankZipCode

`func (o *SuppliersApiSyncSuppliersRequest) GetBankZipCode() string`

GetBankZipCode returns the BankZipCode field if non-nil, zero value otherwise.

### GetBankZipCodeOk

`func (o *SuppliersApiSyncSuppliersRequest) GetBankZipCodeOk() (*string, bool)`

GetBankZipCodeOk returns a tuple with the BankZipCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankZipCode

`func (o *SuppliersApiSyncSuppliersRequest) SetBankZipCode(v string)`

SetBankZipCode sets BankZipCode field to given value.

### HasBankZipCode

`func (o *SuppliersApiSyncSuppliersRequest) HasBankZipCode() bool`

HasBankZipCode returns a boolean if a field has been set.

### GetSwiftNo

`func (o *SuppliersApiSyncSuppliersRequest) GetSwiftNo() string`

GetSwiftNo returns the SwiftNo field if non-nil, zero value otherwise.

### GetSwiftNoOk

`func (o *SuppliersApiSyncSuppliersRequest) GetSwiftNoOk() (*string, bool)`

GetSwiftNoOk returns a tuple with the SwiftNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSwiftNo

`func (o *SuppliersApiSyncSuppliersRequest) SetSwiftNo(v string)`

SetSwiftNo sets SwiftNo field to given value.

### HasSwiftNo

`func (o *SuppliersApiSyncSuppliersRequest) HasSwiftNo() bool`

HasSwiftNo returns a boolean if a field has been set.

### GetIbanNo

`func (o *SuppliersApiSyncSuppliersRequest) GetIbanNo() string`

GetIbanNo returns the IbanNo field if non-nil, zero value otherwise.

### GetIbanNoOk

`func (o *SuppliersApiSyncSuppliersRequest) GetIbanNoOk() (*string, bool)`

GetIbanNoOk returns a tuple with the IbanNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIbanNo

`func (o *SuppliersApiSyncSuppliersRequest) SetIbanNo(v string)`

SetIbanNo sets IbanNo field to given value.

### HasIbanNo

`func (o *SuppliersApiSyncSuppliersRequest) HasIbanNo() bool`

HasIbanNo returns a boolean if a field has been set.

### GetMisc1099

`func (o *SuppliersApiSyncSuppliersRequest) GetMisc1099() bool`

GetMisc1099 returns the Misc1099 field if non-nil, zero value otherwise.

### GetMisc1099Ok

`func (o *SuppliersApiSyncSuppliersRequest) GetMisc1099Ok() (*bool, bool)`

GetMisc1099Ok returns a tuple with the Misc1099 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMisc1099

`func (o *SuppliersApiSyncSuppliersRequest) SetMisc1099(v bool)`

SetMisc1099 sets Misc1099 field to given value.

### HasMisc1099

`func (o *SuppliersApiSyncSuppliersRequest) HasMisc1099() bool`

HasMisc1099 returns a boolean if a field has been set.

### GetDefaultCarrierId

`func (o *SuppliersApiSyncSuppliersRequest) GetDefaultCarrierId() string`

GetDefaultCarrierId returns the DefaultCarrierId field if non-nil, zero value otherwise.

### GetDefaultCarrierIdOk

`func (o *SuppliersApiSyncSuppliersRequest) GetDefaultCarrierIdOk() (*string, bool)`

GetDefaultCarrierIdOk returns a tuple with the DefaultCarrierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultCarrierId

`func (o *SuppliersApiSyncSuppliersRequest) SetDefaultCarrierId(v string)`

SetDefaultCarrierId sets DefaultCarrierId field to given value.

### HasDefaultCarrierId

`func (o *SuppliersApiSyncSuppliersRequest) HasDefaultCarrierId() bool`

HasDefaultCarrierId returns a boolean if a field has been set.

### GetCustoms

`func (o *SuppliersApiSyncSuppliersRequest) GetCustoms() string`

GetCustoms returns the Customs field if non-nil, zero value otherwise.

### GetCustomsOk

`func (o *SuppliersApiSyncSuppliersRequest) GetCustomsOk() (*string, bool)`

GetCustomsOk returns a tuple with the Customs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustoms

`func (o *SuppliersApiSyncSuppliersRequest) SetCustoms(v string)`

SetCustoms sets Customs field to given value.

### HasCustoms

`func (o *SuppliersApiSyncSuppliersRequest) HasCustoms() bool`

HasCustoms returns a boolean if a field has been set.

### GetDefaultShipTo

`func (o *SuppliersApiSyncSuppliersRequest) GetDefaultShipTo() string`

GetDefaultShipTo returns the DefaultShipTo field if non-nil, zero value otherwise.

### GetDefaultShipToOk

`func (o *SuppliersApiSyncSuppliersRequest) GetDefaultShipToOk() (*string, bool)`

GetDefaultShipToOk returns a tuple with the DefaultShipTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultShipTo

`func (o *SuppliersApiSyncSuppliersRequest) SetDefaultShipTo(v string)`

SetDefaultShipTo sets DefaultShipTo field to given value.

### HasDefaultShipTo

`func (o *SuppliersApiSyncSuppliersRequest) HasDefaultShipTo() bool`

HasDefaultShipTo returns a boolean if a field has been set.

### GetDefaultShipVia

`func (o *SuppliersApiSyncSuppliersRequest) GetDefaultShipVia() string`

GetDefaultShipVia returns the DefaultShipVia field if non-nil, zero value otherwise.

### GetDefaultShipViaOk

`func (o *SuppliersApiSyncSuppliersRequest) GetDefaultShipViaOk() (*string, bool)`

GetDefaultShipViaOk returns a tuple with the DefaultShipVia field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultShipVia

`func (o *SuppliersApiSyncSuppliersRequest) SetDefaultShipVia(v string)`

SetDefaultShipVia sets DefaultShipVia field to given value.

### HasDefaultShipVia

`func (o *SuppliersApiSyncSuppliersRequest) HasDefaultShipVia() bool`

HasDefaultShipVia returns a boolean if a field has been set.

### GetDefaultFreightTerms

`func (o *SuppliersApiSyncSuppliersRequest) GetDefaultFreightTerms() string`

GetDefaultFreightTerms returns the DefaultFreightTerms field if non-nil, zero value otherwise.

### GetDefaultFreightTermsOk

`func (o *SuppliersApiSyncSuppliersRequest) GetDefaultFreightTermsOk() (*string, bool)`

GetDefaultFreightTermsOk returns a tuple with the DefaultFreightTerms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultFreightTerms

`func (o *SuppliersApiSyncSuppliersRequest) SetDefaultFreightTerms(v string)`

SetDefaultFreightTerms sets DefaultFreightTerms field to given value.

### HasDefaultFreightTerms

`func (o *SuppliersApiSyncSuppliersRequest) HasDefaultFreightTerms() bool`

HasDefaultFreightTerms returns a boolean if a field has been set.

### GetDefaultINCOTerms

`func (o *SuppliersApiSyncSuppliersRequest) GetDefaultINCOTerms() string`

GetDefaultINCOTerms returns the DefaultINCOTerms field if non-nil, zero value otherwise.

### GetDefaultINCOTermsOk

`func (o *SuppliersApiSyncSuppliersRequest) GetDefaultINCOTermsOk() (*string, bool)`

GetDefaultINCOTermsOk returns a tuple with the DefaultINCOTerms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultINCOTerms

`func (o *SuppliersApiSyncSuppliersRequest) SetDefaultINCOTerms(v string)`

SetDefaultINCOTerms sets DefaultINCOTerms field to given value.

### HasDefaultINCOTerms

`func (o *SuppliersApiSyncSuppliersRequest) HasDefaultINCOTerms() bool`

HasDefaultINCOTerms returns a boolean if a field has been set.

### GetDefaultFOB

`func (o *SuppliersApiSyncSuppliersRequest) GetDefaultFOB() string`

GetDefaultFOB returns the DefaultFOB field if non-nil, zero value otherwise.

### GetDefaultFOBOk

`func (o *SuppliersApiSyncSuppliersRequest) GetDefaultFOBOk() (*string, bool)`

GetDefaultFOBOk returns a tuple with the DefaultFOB field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultFOB

`func (o *SuppliersApiSyncSuppliersRequest) SetDefaultFOB(v string)`

SetDefaultFOB sets DefaultFOB field to given value.

### HasDefaultFOB

`func (o *SuppliersApiSyncSuppliersRequest) HasDefaultFOB() bool`

HasDefaultFOB returns a boolean if a field has been set.

### GetDefaultPaymentTerms

`func (o *SuppliersApiSyncSuppliersRequest) GetDefaultPaymentTerms() string`

GetDefaultPaymentTerms returns the DefaultPaymentTerms field if non-nil, zero value otherwise.

### GetDefaultPaymentTermsOk

`func (o *SuppliersApiSyncSuppliersRequest) GetDefaultPaymentTermsOk() (*string, bool)`

GetDefaultPaymentTermsOk returns a tuple with the DefaultPaymentTerms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultPaymentTerms

`func (o *SuppliersApiSyncSuppliersRequest) SetDefaultPaymentTerms(v string)`

SetDefaultPaymentTerms sets DefaultPaymentTerms field to given value.

### HasDefaultPaymentTerms

`func (o *SuppliersApiSyncSuppliersRequest) HasDefaultPaymentTerms() bool`

HasDefaultPaymentTerms returns a boolean if a field has been set.

### GetDefaultCurrencyCode

`func (o *SuppliersApiSyncSuppliersRequest) GetDefaultCurrencyCode() string`

GetDefaultCurrencyCode returns the DefaultCurrencyCode field if non-nil, zero value otherwise.

### GetDefaultCurrencyCodeOk

`func (o *SuppliersApiSyncSuppliersRequest) GetDefaultCurrencyCodeOk() (*string, bool)`

GetDefaultCurrencyCodeOk returns a tuple with the DefaultCurrencyCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultCurrencyCode

`func (o *SuppliersApiSyncSuppliersRequest) SetDefaultCurrencyCode(v string)`

SetDefaultCurrencyCode sets DefaultCurrencyCode field to given value.

### HasDefaultCurrencyCode

`func (o *SuppliersApiSyncSuppliersRequest) HasDefaultCurrencyCode() bool`

HasDefaultCurrencyCode returns a boolean if a field has been set.

### GetDefaultTaxCode

`func (o *SuppliersApiSyncSuppliersRequest) GetDefaultTaxCode() string`

GetDefaultTaxCode returns the DefaultTaxCode field if non-nil, zero value otherwise.

### GetDefaultTaxCodeOk

`func (o *SuppliersApiSyncSuppliersRequest) GetDefaultTaxCodeOk() (*string, bool)`

GetDefaultTaxCodeOk returns a tuple with the DefaultTaxCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultTaxCode

`func (o *SuppliersApiSyncSuppliersRequest) SetDefaultTaxCode(v string)`

SetDefaultTaxCode sets DefaultTaxCode field to given value.

### HasDefaultTaxCode

`func (o *SuppliersApiSyncSuppliersRequest) HasDefaultTaxCode() bool`

HasDefaultTaxCode returns a boolean if a field has been set.

### GetDefaultPOType

`func (o *SuppliersApiSyncSuppliersRequest) GetDefaultPOType() string`

GetDefaultPOType returns the DefaultPOType field if non-nil, zero value otherwise.

### GetDefaultPOTypeOk

`func (o *SuppliersApiSyncSuppliersRequest) GetDefaultPOTypeOk() (*string, bool)`

GetDefaultPOTypeOk returns a tuple with the DefaultPOType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultPOType

`func (o *SuppliersApiSyncSuppliersRequest) SetDefaultPOType(v string)`

SetDefaultPOType sets DefaultPOType field to given value.

### HasDefaultPOType

`func (o *SuppliersApiSyncSuppliersRequest) HasDefaultPOType() bool`

HasDefaultPOType returns a boolean if a field has been set.

### GetDefaultExpenseAccount

`func (o *SuppliersApiSyncSuppliersRequest) GetDefaultExpenseAccount() string`

GetDefaultExpenseAccount returns the DefaultExpenseAccount field if non-nil, zero value otherwise.

### GetDefaultExpenseAccountOk

`func (o *SuppliersApiSyncSuppliersRequest) GetDefaultExpenseAccountOk() (*string, bool)`

GetDefaultExpenseAccountOk returns a tuple with the DefaultExpenseAccount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultExpenseAccount

`func (o *SuppliersApiSyncSuppliersRequest) SetDefaultExpenseAccount(v string)`

SetDefaultExpenseAccount sets DefaultExpenseAccount field to given value.

### HasDefaultExpenseAccount

`func (o *SuppliersApiSyncSuppliersRequest) HasDefaultExpenseAccount() bool`

HasDefaultExpenseAccount returns a boolean if a field has been set.

### GetCountry

`func (o *SuppliersApiSyncSuppliersRequest) GetCountry() string`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *SuppliersApiSyncSuppliersRequest) GetCountryOk() (*string, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *SuppliersApiSyncSuppliersRequest) SetCountry(v string)`

SetCountry sets Country field to given value.

### HasCountry

`func (o *SuppliersApiSyncSuppliersRequest) HasCountry() bool`

HasCountry returns a boolean if a field has been set.

### GetAddress

`func (o *SuppliersApiSyncSuppliersRequest) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *SuppliersApiSyncSuppliersRequest) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *SuppliersApiSyncSuppliersRequest) SetAddress(v string)`

SetAddress sets Address field to given value.

### HasAddress

`func (o *SuppliersApiSyncSuppliersRequest) HasAddress() bool`

HasAddress returns a boolean if a field has been set.

### GetCity

`func (o *SuppliersApiSyncSuppliersRequest) GetCity() string`

GetCity returns the City field if non-nil, zero value otherwise.

### GetCityOk

`func (o *SuppliersApiSyncSuppliersRequest) GetCityOk() (*string, bool)`

GetCityOk returns a tuple with the City field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCity

`func (o *SuppliersApiSyncSuppliersRequest) SetCity(v string)`

SetCity sets City field to given value.

### HasCity

`func (o *SuppliersApiSyncSuppliersRequest) HasCity() bool`

HasCity returns a boolean if a field has been set.

### GetZip

`func (o *SuppliersApiSyncSuppliersRequest) GetZip() string`

GetZip returns the Zip field if non-nil, zero value otherwise.

### GetZipOk

`func (o *SuppliersApiSyncSuppliersRequest) GetZipOk() (*string, bool)`

GetZipOk returns a tuple with the Zip field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetZip

`func (o *SuppliersApiSyncSuppliersRequest) SetZip(v string)`

SetZip sets Zip field to given value.

### HasZip

`func (o *SuppliersApiSyncSuppliersRequest) HasZip() bool`

HasZip returns a boolean if a field has been set.

### GetState

`func (o *SuppliersApiSyncSuppliersRequest) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *SuppliersApiSyncSuppliersRequest) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *SuppliersApiSyncSuppliersRequest) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *SuppliersApiSyncSuppliersRequest) HasState() bool`

HasState returns a boolean if a field has been set.

### GetMain

`func (o *SuppliersApiSyncSuppliersRequest) GetMain() bool`

GetMain returns the Main field if non-nil, zero value otherwise.

### GetMainOk

`func (o *SuppliersApiSyncSuppliersRequest) GetMainOk() (*bool, bool)`

GetMainOk returns a tuple with the Main field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMain

`func (o *SuppliersApiSyncSuppliersRequest) SetMain(v bool)`

SetMain sets Main field to given value.

### HasMain

`func (o *SuppliersApiSyncSuppliersRequest) HasMain() bool`

HasMain returns a boolean if a field has been set.

### GetRemit

`func (o *SuppliersApiSyncSuppliersRequest) GetRemit() bool`

GetRemit returns the Remit field if non-nil, zero value otherwise.

### GetRemitOk

`func (o *SuppliersApiSyncSuppliersRequest) GetRemitOk() (*bool, bool)`

GetRemitOk returns a tuple with the Remit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemit

`func (o *SuppliersApiSyncSuppliersRequest) SetRemit(v bool)`

SetRemit sets Remit field to given value.

### HasRemit

`func (o *SuppliersApiSyncSuppliersRequest) HasRemit() bool`

HasRemit returns a boolean if a field has been set.

### GetPhone

`func (o *SuppliersApiSyncSuppliersRequest) GetPhone() string`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *SuppliersApiSyncSuppliersRequest) GetPhoneOk() (*string, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *SuppliersApiSyncSuppliersRequest) SetPhone(v string)`

SetPhone sets Phone field to given value.

### HasPhone

`func (o *SuppliersApiSyncSuppliersRequest) HasPhone() bool`

HasPhone returns a boolean if a field has been set.

### GetFax

`func (o *SuppliersApiSyncSuppliersRequest) GetFax() string`

GetFax returns the Fax field if non-nil, zero value otherwise.

### GetFaxOk

`func (o *SuppliersApiSyncSuppliersRequest) GetFaxOk() (*string, bool)`

GetFaxOk returns a tuple with the Fax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFax

`func (o *SuppliersApiSyncSuppliersRequest) SetFax(v string)`

SetFax sets Fax field to given value.

### HasFax

`func (o *SuppliersApiSyncSuppliersRequest) HasFax() bool`

HasFax returns a boolean if a field has been set.

### GetEmail

`func (o *SuppliersApiSyncSuppliersRequest) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *SuppliersApiSyncSuppliersRequest) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *SuppliersApiSyncSuppliersRequest) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *SuppliersApiSyncSuppliersRequest) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetAlternateSupplierName

`func (o *SuppliersApiSyncSuppliersRequest) GetAlternateSupplierName() string`

GetAlternateSupplierName returns the AlternateSupplierName field if non-nil, zero value otherwise.

### GetAlternateSupplierNameOk

`func (o *SuppliersApiSyncSuppliersRequest) GetAlternateSupplierNameOk() (*string, bool)`

GetAlternateSupplierNameOk returns a tuple with the AlternateSupplierName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlternateSupplierName

`func (o *SuppliersApiSyncSuppliersRequest) SetAlternateSupplierName(v string)`

SetAlternateSupplierName sets AlternateSupplierName field to given value.

### HasAlternateSupplierName

`func (o *SuppliersApiSyncSuppliersRequest) HasAlternateSupplierName() bool`

HasAlternateSupplierName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


