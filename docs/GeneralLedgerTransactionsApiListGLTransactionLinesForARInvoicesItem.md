# GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem

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
**CustomerId** | Pointer to **string** | A unique identifier for the GL transaction AR customer. | [optional] 
**CustomerCode** | Pointer to **string** | The GL transaction AR customer code, typically an abbreviated name for the customer. | [optional] 

## Methods

### NewGeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem

`func NewGeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem() *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem`

NewGeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem instantiates a new GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItemWithDefaults

`func NewGeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItemWithDefaults() *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem`

NewGeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItemWithDefaults instantiates a new GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPeriodDisplay

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) GetPeriodDisplay() string`

GetPeriodDisplay returns the PeriodDisplay field if non-nil, zero value otherwise.

### GetPeriodDisplayOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) GetPeriodDisplayOk() (*string, bool)`

GetPeriodDisplayOk returns a tuple with the PeriodDisplay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriodDisplay

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) SetPeriodDisplay(v string)`

SetPeriodDisplay sets PeriodDisplay field to given value.

### HasPeriodDisplay

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) HasPeriodDisplay() bool`

HasPeriodDisplay returns a boolean if a field has been set.

### GetTransactionDate

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) GetTransactionDate() time.Time`

GetTransactionDate returns the TransactionDate field if non-nil, zero value otherwise.

### GetTransactionDateOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) GetTransactionDateOk() (*time.Time, bool)`

GetTransactionDateOk returns a tuple with the TransactionDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransactionDate

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) SetTransactionDate(v time.Time)`

SetTransactionDate sets TransactionDate field to given value.

### HasTransactionDate

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) HasTransactionDate() bool`

HasTransactionDate returns a boolean if a field has been set.

### GetAccountId

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) GetAccountId() string`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) GetAccountIdOk() (*string, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) SetAccountId(v string)`

SetAccountId sets AccountId field to given value.

### HasAccountId

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) HasAccountId() bool`

HasAccountId returns a boolean if a field has been set.

### GetAccountNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) GetAccountNumber() string`

GetAccountNumber returns the AccountNumber field if non-nil, zero value otherwise.

### GetAccountNumberOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) GetAccountNumberOk() (*string, bool)`

GetAccountNumberOk returns a tuple with the AccountNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) SetAccountNumber(v string)`

SetAccountNumber sets AccountNumber field to given value.

### HasAccountNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) HasAccountNumber() bool`

HasAccountNumber returns a boolean if a field has been set.

### GetBaseSegment

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) GetBaseSegment() string`

GetBaseSegment returns the BaseSegment field if non-nil, zero value otherwise.

### GetBaseSegmentOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) GetBaseSegmentOk() (*string, bool)`

GetBaseSegmentOk returns a tuple with the BaseSegment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaseSegment

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) SetBaseSegment(v string)`

SetBaseSegment sets BaseSegment field to given value.

### HasBaseSegment

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) HasBaseSegment() bool`

HasBaseSegment returns a boolean if a field has been set.

### GetCostCenterSegment

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) GetCostCenterSegment() string`

GetCostCenterSegment returns the CostCenterSegment field if non-nil, zero value otherwise.

### GetCostCenterSegmentOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) GetCostCenterSegmentOk() (*string, bool)`

GetCostCenterSegmentOk returns a tuple with the CostCenterSegment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostCenterSegment

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) SetCostCenterSegment(v string)`

SetCostCenterSegment sets CostCenterSegment field to given value.

### HasCostCenterSegment

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) HasCostCenterSegment() bool`

HasCostCenterSegment returns a boolean if a field has been set.

### GetSubAccountSegment

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) GetSubAccountSegment() string`

GetSubAccountSegment returns the SubAccountSegment field if non-nil, zero value otherwise.

### GetSubAccountSegmentOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) GetSubAccountSegmentOk() (*string, bool)`

GetSubAccountSegmentOk returns a tuple with the SubAccountSegment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubAccountSegment

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) SetSubAccountSegment(v string)`

SetSubAccountSegment sets SubAccountSegment field to given value.

### HasSubAccountSegment

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) HasSubAccountSegment() bool`

HasSubAccountSegment returns a boolean if a field has been set.

### GetDescription

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetCredit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) GetCredit() float64`

GetCredit returns the Credit field if non-nil, zero value otherwise.

### GetCreditOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) GetCreditOk() (*float64, bool)`

GetCreditOk returns a tuple with the Credit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCredit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) SetCredit(v float64)`

SetCredit sets Credit field to given value.

### HasCredit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) HasCredit() bool`

HasCredit returns a boolean if a field has been set.

### GetDebit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) GetDebit() float64`

GetDebit returns the Debit field if non-nil, zero value otherwise.

### GetDebitOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) GetDebitOk() (*float64, bool)`

GetDebitOk returns a tuple with the Debit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDebit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) SetDebit(v float64)`

SetDebit sets Debit field to given value.

### HasDebit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) HasDebit() bool`

HasDebit returns a boolean if a field has been set.

### GetCurrencyCredit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) GetCurrencyCredit() float64`

GetCurrencyCredit returns the CurrencyCredit field if non-nil, zero value otherwise.

### GetCurrencyCreditOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) GetCurrencyCreditOk() (*float64, bool)`

GetCurrencyCreditOk returns a tuple with the CurrencyCredit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyCredit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) SetCurrencyCredit(v float64)`

SetCurrencyCredit sets CurrencyCredit field to given value.

### HasCurrencyCredit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) HasCurrencyCredit() bool`

HasCurrencyCredit returns a boolean if a field has been set.

### GetCurrencyDebit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) GetCurrencyDebit() float64`

GetCurrencyDebit returns the CurrencyDebit field if non-nil, zero value otherwise.

### GetCurrencyDebitOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) GetCurrencyDebitOk() (*float64, bool)`

GetCurrencyDebitOk returns a tuple with the CurrencyDebit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyDebit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) SetCurrencyDebit(v float64)`

SetCurrencyDebit sets CurrencyDebit field to given value.

### HasCurrencyDebit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) HasCurrencyDebit() bool`

HasCurrencyDebit returns a boolean if a field has been set.

### GetAccountingJobNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) GetAccountingJobNumber() string`

GetAccountingJobNumber returns the AccountingJobNumber field if non-nil, zero value otherwise.

### GetAccountingJobNumberOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) GetAccountingJobNumberOk() (*string, bool)`

GetAccountingJobNumberOk returns a tuple with the AccountingJobNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountingJobNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) SetAccountingJobNumber(v string)`

SetAccountingJobNumber sets AccountingJobNumber field to given value.

### HasAccountingJobNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) HasAccountingJobNumber() bool`

HasAccountingJobNumber returns a boolean if a field has been set.

### GetVoucherNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) GetVoucherNumber() string`

GetVoucherNumber returns the VoucherNumber field if non-nil, zero value otherwise.

### GetVoucherNumberOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) GetVoucherNumberOk() (*string, bool)`

GetVoucherNumberOk returns a tuple with the VoucherNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoucherNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) SetVoucherNumber(v string)`

SetVoucherNumber sets VoucherNumber field to given value.

### HasVoucherNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) HasVoucherNumber() bool`

HasVoucherNumber returns a boolean if a field has been set.

### GetInvoiceNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) GetInvoiceNumber() string`

GetInvoiceNumber returns the InvoiceNumber field if non-nil, zero value otherwise.

### GetInvoiceNumberOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) GetInvoiceNumberOk() (*string, bool)`

GetInvoiceNumberOk returns a tuple with the InvoiceNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) SetInvoiceNumber(v string)`

SetInvoiceNumber sets InvoiceNumber field to given value.

### HasInvoiceNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) HasInvoiceNumber() bool`

HasInvoiceNumber returns a boolean if a field has been set.

### GetCustomerId

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### GetCustomerCode

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) GetCustomerCode() string`

GetCustomerCode returns the CustomerCode field if non-nil, zero value otherwise.

### GetCustomerCodeOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) GetCustomerCodeOk() (*string, bool)`

GetCustomerCodeOk returns a tuple with the CustomerCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerCode

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) SetCustomerCode(v string)`

SetCustomerCode sets CustomerCode field to given value.

### HasCustomerCode

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARInvoicesItem) HasCustomerCode() bool`

HasCustomerCode returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


