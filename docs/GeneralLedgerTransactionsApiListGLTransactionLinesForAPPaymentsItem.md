# GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem

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
**PaymentNumber** | Pointer to **string** | The GL transaction AP check payment number. | [optional] 
**SupplierId** | Pointer to **string** | A unique identifier for the GL transaction AP supplier ID. | [optional] 
**SupplierCode** | Pointer to **string** | The GL transaction AP customer code, typically an abbreviated name for the customer. | [optional] 

## Methods

### NewGeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem

`func NewGeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem() *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem`

NewGeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem instantiates a new GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItemWithDefaults

`func NewGeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItemWithDefaults() *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem`

NewGeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItemWithDefaults instantiates a new GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPeriodDisplay

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) GetPeriodDisplay() string`

GetPeriodDisplay returns the PeriodDisplay field if non-nil, zero value otherwise.

### GetPeriodDisplayOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) GetPeriodDisplayOk() (*string, bool)`

GetPeriodDisplayOk returns a tuple with the PeriodDisplay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriodDisplay

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) SetPeriodDisplay(v string)`

SetPeriodDisplay sets PeriodDisplay field to given value.

### HasPeriodDisplay

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) HasPeriodDisplay() bool`

HasPeriodDisplay returns a boolean if a field has been set.

### GetTransactionDate

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) GetTransactionDate() time.Time`

GetTransactionDate returns the TransactionDate field if non-nil, zero value otherwise.

### GetTransactionDateOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) GetTransactionDateOk() (*time.Time, bool)`

GetTransactionDateOk returns a tuple with the TransactionDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransactionDate

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) SetTransactionDate(v time.Time)`

SetTransactionDate sets TransactionDate field to given value.

### HasTransactionDate

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) HasTransactionDate() bool`

HasTransactionDate returns a boolean if a field has been set.

### GetAccountId

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) GetAccountId() string`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) GetAccountIdOk() (*string, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) SetAccountId(v string)`

SetAccountId sets AccountId field to given value.

### HasAccountId

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) HasAccountId() bool`

HasAccountId returns a boolean if a field has been set.

### GetAccountNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) GetAccountNumber() string`

GetAccountNumber returns the AccountNumber field if non-nil, zero value otherwise.

### GetAccountNumberOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) GetAccountNumberOk() (*string, bool)`

GetAccountNumberOk returns a tuple with the AccountNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) SetAccountNumber(v string)`

SetAccountNumber sets AccountNumber field to given value.

### HasAccountNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) HasAccountNumber() bool`

HasAccountNumber returns a boolean if a field has been set.

### GetBaseSegment

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) GetBaseSegment() string`

GetBaseSegment returns the BaseSegment field if non-nil, zero value otherwise.

### GetBaseSegmentOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) GetBaseSegmentOk() (*string, bool)`

GetBaseSegmentOk returns a tuple with the BaseSegment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaseSegment

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) SetBaseSegment(v string)`

SetBaseSegment sets BaseSegment field to given value.

### HasBaseSegment

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) HasBaseSegment() bool`

HasBaseSegment returns a boolean if a field has been set.

### GetCostCenterSegment

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) GetCostCenterSegment() string`

GetCostCenterSegment returns the CostCenterSegment field if non-nil, zero value otherwise.

### GetCostCenterSegmentOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) GetCostCenterSegmentOk() (*string, bool)`

GetCostCenterSegmentOk returns a tuple with the CostCenterSegment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostCenterSegment

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) SetCostCenterSegment(v string)`

SetCostCenterSegment sets CostCenterSegment field to given value.

### HasCostCenterSegment

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) HasCostCenterSegment() bool`

HasCostCenterSegment returns a boolean if a field has been set.

### GetSubAccountSegment

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) GetSubAccountSegment() string`

GetSubAccountSegment returns the SubAccountSegment field if non-nil, zero value otherwise.

### GetSubAccountSegmentOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) GetSubAccountSegmentOk() (*string, bool)`

GetSubAccountSegmentOk returns a tuple with the SubAccountSegment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubAccountSegment

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) SetSubAccountSegment(v string)`

SetSubAccountSegment sets SubAccountSegment field to given value.

### HasSubAccountSegment

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) HasSubAccountSegment() bool`

HasSubAccountSegment returns a boolean if a field has been set.

### GetDescription

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetCredit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) GetCredit() float64`

GetCredit returns the Credit field if non-nil, zero value otherwise.

### GetCreditOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) GetCreditOk() (*float64, bool)`

GetCreditOk returns a tuple with the Credit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCredit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) SetCredit(v float64)`

SetCredit sets Credit field to given value.

### HasCredit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) HasCredit() bool`

HasCredit returns a boolean if a field has been set.

### GetDebit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) GetDebit() float64`

GetDebit returns the Debit field if non-nil, zero value otherwise.

### GetDebitOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) GetDebitOk() (*float64, bool)`

GetDebitOk returns a tuple with the Debit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDebit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) SetDebit(v float64)`

SetDebit sets Debit field to given value.

### HasDebit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) HasDebit() bool`

HasDebit returns a boolean if a field has been set.

### GetCurrencyCredit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) GetCurrencyCredit() float64`

GetCurrencyCredit returns the CurrencyCredit field if non-nil, zero value otherwise.

### GetCurrencyCreditOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) GetCurrencyCreditOk() (*float64, bool)`

GetCurrencyCreditOk returns a tuple with the CurrencyCredit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyCredit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) SetCurrencyCredit(v float64)`

SetCurrencyCredit sets CurrencyCredit field to given value.

### HasCurrencyCredit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) HasCurrencyCredit() bool`

HasCurrencyCredit returns a boolean if a field has been set.

### GetCurrencyDebit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) GetCurrencyDebit() float64`

GetCurrencyDebit returns the CurrencyDebit field if non-nil, zero value otherwise.

### GetCurrencyDebitOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) GetCurrencyDebitOk() (*float64, bool)`

GetCurrencyDebitOk returns a tuple with the CurrencyDebit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyDebit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) SetCurrencyDebit(v float64)`

SetCurrencyDebit sets CurrencyDebit field to given value.

### HasCurrencyDebit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) HasCurrencyDebit() bool`

HasCurrencyDebit returns a boolean if a field has been set.

### GetAccountingJobNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) GetAccountingJobNumber() string`

GetAccountingJobNumber returns the AccountingJobNumber field if non-nil, zero value otherwise.

### GetAccountingJobNumberOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) GetAccountingJobNumberOk() (*string, bool)`

GetAccountingJobNumberOk returns a tuple with the AccountingJobNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountingJobNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) SetAccountingJobNumber(v string)`

SetAccountingJobNumber sets AccountingJobNumber field to given value.

### HasAccountingJobNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) HasAccountingJobNumber() bool`

HasAccountingJobNumber returns a boolean if a field has been set.

### GetVoucherNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) GetVoucherNumber() string`

GetVoucherNumber returns the VoucherNumber field if non-nil, zero value otherwise.

### GetVoucherNumberOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) GetVoucherNumberOk() (*string, bool)`

GetVoucherNumberOk returns a tuple with the VoucherNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoucherNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) SetVoucherNumber(v string)`

SetVoucherNumber sets VoucherNumber field to given value.

### HasVoucherNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) HasVoucherNumber() bool`

HasVoucherNumber returns a boolean if a field has been set.

### GetPaymentNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) GetPaymentNumber() string`

GetPaymentNumber returns the PaymentNumber field if non-nil, zero value otherwise.

### GetPaymentNumberOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) GetPaymentNumberOk() (*string, bool)`

GetPaymentNumberOk returns a tuple with the PaymentNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) SetPaymentNumber(v string)`

SetPaymentNumber sets PaymentNumber field to given value.

### HasPaymentNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) HasPaymentNumber() bool`

HasPaymentNumber returns a boolean if a field has been set.

### GetSupplierId

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) GetSupplierId() string`

GetSupplierId returns the SupplierId field if non-nil, zero value otherwise.

### GetSupplierIdOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) GetSupplierIdOk() (*string, bool)`

GetSupplierIdOk returns a tuple with the SupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierId

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) SetSupplierId(v string)`

SetSupplierId sets SupplierId field to given value.

### HasSupplierId

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) HasSupplierId() bool`

HasSupplierId returns a boolean if a field has been set.

### GetSupplierCode

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) GetSupplierCode() string`

GetSupplierCode returns the SupplierCode field if non-nil, zero value otherwise.

### GetSupplierCodeOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) GetSupplierCodeOk() (*string, bool)`

GetSupplierCodeOk returns a tuple with the SupplierCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierCode

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) SetSupplierCode(v string)`

SetSupplierCode sets SupplierCode field to given value.

### HasSupplierCode

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForAPPaymentsItem) HasSupplierCode() bool`

HasSupplierCode returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


