# GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem

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
**DepositNumber** | Pointer to **string** | The GL transaction AR deposit number. | [optional] 

## Methods

### NewGeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem

`func NewGeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem() *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem`

NewGeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem instantiates a new GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItemWithDefaults

`func NewGeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItemWithDefaults() *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem`

NewGeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItemWithDefaults instantiates a new GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPeriodDisplay

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) GetPeriodDisplay() string`

GetPeriodDisplay returns the PeriodDisplay field if non-nil, zero value otherwise.

### GetPeriodDisplayOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) GetPeriodDisplayOk() (*string, bool)`

GetPeriodDisplayOk returns a tuple with the PeriodDisplay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriodDisplay

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) SetPeriodDisplay(v string)`

SetPeriodDisplay sets PeriodDisplay field to given value.

### HasPeriodDisplay

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) HasPeriodDisplay() bool`

HasPeriodDisplay returns a boolean if a field has been set.

### GetTransactionDate

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) GetTransactionDate() time.Time`

GetTransactionDate returns the TransactionDate field if non-nil, zero value otherwise.

### GetTransactionDateOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) GetTransactionDateOk() (*time.Time, bool)`

GetTransactionDateOk returns a tuple with the TransactionDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransactionDate

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) SetTransactionDate(v time.Time)`

SetTransactionDate sets TransactionDate field to given value.

### HasTransactionDate

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) HasTransactionDate() bool`

HasTransactionDate returns a boolean if a field has been set.

### GetAccountId

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) GetAccountId() string`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) GetAccountIdOk() (*string, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) SetAccountId(v string)`

SetAccountId sets AccountId field to given value.

### HasAccountId

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) HasAccountId() bool`

HasAccountId returns a boolean if a field has been set.

### GetAccountNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) GetAccountNumber() string`

GetAccountNumber returns the AccountNumber field if non-nil, zero value otherwise.

### GetAccountNumberOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) GetAccountNumberOk() (*string, bool)`

GetAccountNumberOk returns a tuple with the AccountNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) SetAccountNumber(v string)`

SetAccountNumber sets AccountNumber field to given value.

### HasAccountNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) HasAccountNumber() bool`

HasAccountNumber returns a boolean if a field has been set.

### GetBaseSegment

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) GetBaseSegment() string`

GetBaseSegment returns the BaseSegment field if non-nil, zero value otherwise.

### GetBaseSegmentOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) GetBaseSegmentOk() (*string, bool)`

GetBaseSegmentOk returns a tuple with the BaseSegment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaseSegment

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) SetBaseSegment(v string)`

SetBaseSegment sets BaseSegment field to given value.

### HasBaseSegment

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) HasBaseSegment() bool`

HasBaseSegment returns a boolean if a field has been set.

### GetCostCenterSegment

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) GetCostCenterSegment() string`

GetCostCenterSegment returns the CostCenterSegment field if non-nil, zero value otherwise.

### GetCostCenterSegmentOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) GetCostCenterSegmentOk() (*string, bool)`

GetCostCenterSegmentOk returns a tuple with the CostCenterSegment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostCenterSegment

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) SetCostCenterSegment(v string)`

SetCostCenterSegment sets CostCenterSegment field to given value.

### HasCostCenterSegment

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) HasCostCenterSegment() bool`

HasCostCenterSegment returns a boolean if a field has been set.

### GetSubAccountSegment

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) GetSubAccountSegment() string`

GetSubAccountSegment returns the SubAccountSegment field if non-nil, zero value otherwise.

### GetSubAccountSegmentOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) GetSubAccountSegmentOk() (*string, bool)`

GetSubAccountSegmentOk returns a tuple with the SubAccountSegment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubAccountSegment

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) SetSubAccountSegment(v string)`

SetSubAccountSegment sets SubAccountSegment field to given value.

### HasSubAccountSegment

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) HasSubAccountSegment() bool`

HasSubAccountSegment returns a boolean if a field has been set.

### GetDescription

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetCredit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) GetCredit() float64`

GetCredit returns the Credit field if non-nil, zero value otherwise.

### GetCreditOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) GetCreditOk() (*float64, bool)`

GetCreditOk returns a tuple with the Credit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCredit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) SetCredit(v float64)`

SetCredit sets Credit field to given value.

### HasCredit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) HasCredit() bool`

HasCredit returns a boolean if a field has been set.

### GetDebit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) GetDebit() float64`

GetDebit returns the Debit field if non-nil, zero value otherwise.

### GetDebitOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) GetDebitOk() (*float64, bool)`

GetDebitOk returns a tuple with the Debit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDebit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) SetDebit(v float64)`

SetDebit sets Debit field to given value.

### HasDebit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) HasDebit() bool`

HasDebit returns a boolean if a field has been set.

### GetCurrencyCredit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) GetCurrencyCredit() float64`

GetCurrencyCredit returns the CurrencyCredit field if non-nil, zero value otherwise.

### GetCurrencyCreditOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) GetCurrencyCreditOk() (*float64, bool)`

GetCurrencyCreditOk returns a tuple with the CurrencyCredit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyCredit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) SetCurrencyCredit(v float64)`

SetCurrencyCredit sets CurrencyCredit field to given value.

### HasCurrencyCredit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) HasCurrencyCredit() bool`

HasCurrencyCredit returns a boolean if a field has been set.

### GetCurrencyDebit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) GetCurrencyDebit() float64`

GetCurrencyDebit returns the CurrencyDebit field if non-nil, zero value otherwise.

### GetCurrencyDebitOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) GetCurrencyDebitOk() (*float64, bool)`

GetCurrencyDebitOk returns a tuple with the CurrencyDebit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyDebit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) SetCurrencyDebit(v float64)`

SetCurrencyDebit sets CurrencyDebit field to given value.

### HasCurrencyDebit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) HasCurrencyDebit() bool`

HasCurrencyDebit returns a boolean if a field has been set.

### GetAccountingJobNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) GetAccountingJobNumber() string`

GetAccountingJobNumber returns the AccountingJobNumber field if non-nil, zero value otherwise.

### GetAccountingJobNumberOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) GetAccountingJobNumberOk() (*string, bool)`

GetAccountingJobNumberOk returns a tuple with the AccountingJobNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountingJobNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) SetAccountingJobNumber(v string)`

SetAccountingJobNumber sets AccountingJobNumber field to given value.

### HasAccountingJobNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) HasAccountingJobNumber() bool`

HasAccountingJobNumber returns a boolean if a field has been set.

### GetVoucherNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) GetVoucherNumber() string`

GetVoucherNumber returns the VoucherNumber field if non-nil, zero value otherwise.

### GetVoucherNumberOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) GetVoucherNumberOk() (*string, bool)`

GetVoucherNumberOk returns a tuple with the VoucherNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoucherNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) SetVoucherNumber(v string)`

SetVoucherNumber sets VoucherNumber field to given value.

### HasVoucherNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) HasVoucherNumber() bool`

HasVoucherNumber returns a boolean if a field has been set.

### GetDepositNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) GetDepositNumber() string`

GetDepositNumber returns the DepositNumber field if non-nil, zero value otherwise.

### GetDepositNumberOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) GetDepositNumberOk() (*string, bool)`

GetDepositNumberOk returns a tuple with the DepositNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDepositNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) SetDepositNumber(v string)`

SetDepositNumber sets DepositNumber field to given value.

### HasDepositNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForARDepositsItem) HasDepositNumber() bool`

HasDepositNumber returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


