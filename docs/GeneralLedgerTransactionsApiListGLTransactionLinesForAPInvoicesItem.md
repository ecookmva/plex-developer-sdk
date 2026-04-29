# GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PeriodDisplay** | Pointer to **string** | The GL transaction fiscal period date. | [optional] 
**TransactionDate** | Pointer to **time.Time** | The date on which a GL transaction was recorded. | [optional] 
**AccountId** | Pointer to **string** | A unique identifier for the GL transaction account. | [optional] 
**AccountNumber** | Pointer to **string** | The GL transaction account number. | [optional] 
**BaseSegment** | Pointer to **string** | The GL transaction base account segment. | [optional] 
**CostCenterSegment** | Pointer to **string** | The GL transaction account cost center segment. | [optional] 
**SubAccountSegment** | Pointer to **string** | The GL transaction account location segment. | [optional] 
**Description** | Pointer to **string** | A description of the GL transaction. | [optional] 
**Credit** | Pointer to **float64** | GL transaction distribution is calculated as a credit. | [optional] 
**Debit** | Pointer to **float64** | GL transaction distribution is calculated as a debit. | [optional] 
**CurrencyCredit** | Pointer to **float64** | GL transaction distribution amount is a foreign currency credit. | [optional] 
**CurrencyDebit** | Pointer to **float64** | GL transaction distribution amount is a foreign currency debit. | [optional] 
**AccountingJobNumber** | Pointer to **string** | Accounting job number for GL transaction, if applicable. | [optional] 
**VoucherNumber** | Pointer to **string** | The GL transaction voucher number. | [optional] 
**InvoiceNumber** | Pointer to **string** | The GL transaction invoice number. | [optional] 
**SupplierId** | Pointer to **string** | A unique identifier for the GL transaction AP supplier ID. | [optional] 
**SupplierCode** | Pointer to **string** | The GL transaction AP customer code, typically an abbreviated name for the customer. | [optional] 

## Methods

### NewGeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem

`func NewGeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem() *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem`

NewGeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem instantiates a new GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItemWithDefaults

`func NewGeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItemWithDefaults() *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem`

NewGeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItemWithDefaults instantiates a new GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPeriodDisplay

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) GetPeriodDisplay() string`

GetPeriodDisplay returns the PeriodDisplay field if non-nil, zero value otherwise.

### GetPeriodDisplayOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) GetPeriodDisplayOk() (*string, bool)`

GetPeriodDisplayOk returns a tuple with the PeriodDisplay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriodDisplay

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) SetPeriodDisplay(v string)`

SetPeriodDisplay sets PeriodDisplay field to given value.

### HasPeriodDisplay

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) HasPeriodDisplay() bool`

HasPeriodDisplay returns a boolean if a field has been set.

### GetTransactionDate

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) GetTransactionDate() time.Time`

GetTransactionDate returns the TransactionDate field if non-nil, zero value otherwise.

### GetTransactionDateOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) GetTransactionDateOk() (*time.Time, bool)`

GetTransactionDateOk returns a tuple with the TransactionDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransactionDate

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) SetTransactionDate(v time.Time)`

SetTransactionDate sets TransactionDate field to given value.

### HasTransactionDate

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) HasTransactionDate() bool`

HasTransactionDate returns a boolean if a field has been set.

### GetAccountId

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) GetAccountId() string`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) GetAccountIdOk() (*string, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) SetAccountId(v string)`

SetAccountId sets AccountId field to given value.

### HasAccountId

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) HasAccountId() bool`

HasAccountId returns a boolean if a field has been set.

### GetAccountNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) GetAccountNumber() string`

GetAccountNumber returns the AccountNumber field if non-nil, zero value otherwise.

### GetAccountNumberOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) GetAccountNumberOk() (*string, bool)`

GetAccountNumberOk returns a tuple with the AccountNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) SetAccountNumber(v string)`

SetAccountNumber sets AccountNumber field to given value.

### HasAccountNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) HasAccountNumber() bool`

HasAccountNumber returns a boolean if a field has been set.

### GetBaseSegment

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) GetBaseSegment() string`

GetBaseSegment returns the BaseSegment field if non-nil, zero value otherwise.

### GetBaseSegmentOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) GetBaseSegmentOk() (*string, bool)`

GetBaseSegmentOk returns a tuple with the BaseSegment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaseSegment

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) SetBaseSegment(v string)`

SetBaseSegment sets BaseSegment field to given value.

### HasBaseSegment

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) HasBaseSegment() bool`

HasBaseSegment returns a boolean if a field has been set.

### GetCostCenterSegment

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) GetCostCenterSegment() string`

GetCostCenterSegment returns the CostCenterSegment field if non-nil, zero value otherwise.

### GetCostCenterSegmentOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) GetCostCenterSegmentOk() (*string, bool)`

GetCostCenterSegmentOk returns a tuple with the CostCenterSegment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostCenterSegment

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) SetCostCenterSegment(v string)`

SetCostCenterSegment sets CostCenterSegment field to given value.

### HasCostCenterSegment

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) HasCostCenterSegment() bool`

HasCostCenterSegment returns a boolean if a field has been set.

### GetSubAccountSegment

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) GetSubAccountSegment() string`

GetSubAccountSegment returns the SubAccountSegment field if non-nil, zero value otherwise.

### GetSubAccountSegmentOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) GetSubAccountSegmentOk() (*string, bool)`

GetSubAccountSegmentOk returns a tuple with the SubAccountSegment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubAccountSegment

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) SetSubAccountSegment(v string)`

SetSubAccountSegment sets SubAccountSegment field to given value.

### HasSubAccountSegment

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) HasSubAccountSegment() bool`

HasSubAccountSegment returns a boolean if a field has been set.

### GetDescription

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetCredit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) GetCredit() float64`

GetCredit returns the Credit field if non-nil, zero value otherwise.

### GetCreditOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) GetCreditOk() (*float64, bool)`

GetCreditOk returns a tuple with the Credit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCredit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) SetCredit(v float64)`

SetCredit sets Credit field to given value.

### HasCredit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) HasCredit() bool`

HasCredit returns a boolean if a field has been set.

### GetDebit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) GetDebit() float64`

GetDebit returns the Debit field if non-nil, zero value otherwise.

### GetDebitOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) GetDebitOk() (*float64, bool)`

GetDebitOk returns a tuple with the Debit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDebit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) SetDebit(v float64)`

SetDebit sets Debit field to given value.

### HasDebit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) HasDebit() bool`

HasDebit returns a boolean if a field has been set.

### GetCurrencyCredit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) GetCurrencyCredit() float64`

GetCurrencyCredit returns the CurrencyCredit field if non-nil, zero value otherwise.

### GetCurrencyCreditOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) GetCurrencyCreditOk() (*float64, bool)`

GetCurrencyCreditOk returns a tuple with the CurrencyCredit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyCredit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) SetCurrencyCredit(v float64)`

SetCurrencyCredit sets CurrencyCredit field to given value.

### HasCurrencyCredit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) HasCurrencyCredit() bool`

HasCurrencyCredit returns a boolean if a field has been set.

### GetCurrencyDebit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) GetCurrencyDebit() float64`

GetCurrencyDebit returns the CurrencyDebit field if non-nil, zero value otherwise.

### GetCurrencyDebitOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) GetCurrencyDebitOk() (*float64, bool)`

GetCurrencyDebitOk returns a tuple with the CurrencyDebit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyDebit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) SetCurrencyDebit(v float64)`

SetCurrencyDebit sets CurrencyDebit field to given value.

### HasCurrencyDebit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) HasCurrencyDebit() bool`

HasCurrencyDebit returns a boolean if a field has been set.

### GetAccountingJobNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) GetAccountingJobNumber() string`

GetAccountingJobNumber returns the AccountingJobNumber field if non-nil, zero value otherwise.

### GetAccountingJobNumberOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) GetAccountingJobNumberOk() (*string, bool)`

GetAccountingJobNumberOk returns a tuple with the AccountingJobNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountingJobNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) SetAccountingJobNumber(v string)`

SetAccountingJobNumber sets AccountingJobNumber field to given value.

### HasAccountingJobNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) HasAccountingJobNumber() bool`

HasAccountingJobNumber returns a boolean if a field has been set.

### GetVoucherNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) GetVoucherNumber() string`

GetVoucherNumber returns the VoucherNumber field if non-nil, zero value otherwise.

### GetVoucherNumberOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) GetVoucherNumberOk() (*string, bool)`

GetVoucherNumberOk returns a tuple with the VoucherNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoucherNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) SetVoucherNumber(v string)`

SetVoucherNumber sets VoucherNumber field to given value.

### HasVoucherNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) HasVoucherNumber() bool`

HasVoucherNumber returns a boolean if a field has been set.

### GetInvoiceNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) GetInvoiceNumber() string`

GetInvoiceNumber returns the InvoiceNumber field if non-nil, zero value otherwise.

### GetInvoiceNumberOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) GetInvoiceNumberOk() (*string, bool)`

GetInvoiceNumberOk returns a tuple with the InvoiceNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) SetInvoiceNumber(v string)`

SetInvoiceNumber sets InvoiceNumber field to given value.

### HasInvoiceNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) HasInvoiceNumber() bool`

HasInvoiceNumber returns a boolean if a field has been set.

### GetSupplierId

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) GetSupplierId() string`

GetSupplierId returns the SupplierId field if non-nil, zero value otherwise.

### GetSupplierIdOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) GetSupplierIdOk() (*string, bool)`

GetSupplierIdOk returns a tuple with the SupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierId

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) SetSupplierId(v string)`

SetSupplierId sets SupplierId field to given value.

### HasSupplierId

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) HasSupplierId() bool`

HasSupplierId returns a boolean if a field has been set.

### GetSupplierCode

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) GetSupplierCode() string`

GetSupplierCode returns the SupplierCode field if non-nil, zero value otherwise.

### GetSupplierCodeOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) GetSupplierCodeOk() (*string, bool)`

GetSupplierCodeOk returns a tuple with the SupplierCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierCode

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) SetSupplierCode(v string)`

SetSupplierCode sets SupplierCode field to given value.

### HasSupplierCode

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPInvoicesItem) HasSupplierCode() bool`

HasSupplierCode returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


