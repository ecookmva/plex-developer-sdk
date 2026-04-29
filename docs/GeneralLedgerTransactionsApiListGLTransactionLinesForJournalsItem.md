# GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PeriodDisplay** | Pointer to **string** | The GL transaction fiscal period. | [optional] 
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
**JournalNumber** | Pointer to **int32** | The GL journal entry journal number. | [optional] 
**HeaderDescription** | Pointer to **string** | The GL journal entry header description. | [optional] 
**Period13** | Pointer to **bool** | Specify if a GL journal entry is in the 13th period. | [optional] 
**PeriodAdjustmentEntries** | Pointer to **bool** | Specify that a GL journal entry has a period adjustment use. | [optional] 
**GovernmentIssuedNo** | Pointer to **string** | The GL journal entry government issued number. | [optional] 
**ModifiedDate** | Pointer to **time.Time** | The date on which a GL journal entry was modified. | [optional] 

## Methods

### NewGeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem

`func NewGeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem() *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem`

NewGeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem instantiates a new GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItemWithDefaults

`func NewGeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItemWithDefaults() *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem`

NewGeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItemWithDefaults instantiates a new GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPeriodDisplay

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) GetPeriodDisplay() string`

GetPeriodDisplay returns the PeriodDisplay field if non-nil, zero value otherwise.

### GetPeriodDisplayOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) GetPeriodDisplayOk() (*string, bool)`

GetPeriodDisplayOk returns a tuple with the PeriodDisplay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriodDisplay

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) SetPeriodDisplay(v string)`

SetPeriodDisplay sets PeriodDisplay field to given value.

### HasPeriodDisplay

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) HasPeriodDisplay() bool`

HasPeriodDisplay returns a boolean if a field has been set.

### GetTransactionDate

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) GetTransactionDate() time.Time`

GetTransactionDate returns the TransactionDate field if non-nil, zero value otherwise.

### GetTransactionDateOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) GetTransactionDateOk() (*time.Time, bool)`

GetTransactionDateOk returns a tuple with the TransactionDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransactionDate

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) SetTransactionDate(v time.Time)`

SetTransactionDate sets TransactionDate field to given value.

### HasTransactionDate

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) HasTransactionDate() bool`

HasTransactionDate returns a boolean if a field has been set.

### GetAccountId

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) GetAccountId() string`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) GetAccountIdOk() (*string, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) SetAccountId(v string)`

SetAccountId sets AccountId field to given value.

### HasAccountId

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) HasAccountId() bool`

HasAccountId returns a boolean if a field has been set.

### GetAccountNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) GetAccountNumber() string`

GetAccountNumber returns the AccountNumber field if non-nil, zero value otherwise.

### GetAccountNumberOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) GetAccountNumberOk() (*string, bool)`

GetAccountNumberOk returns a tuple with the AccountNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) SetAccountNumber(v string)`

SetAccountNumber sets AccountNumber field to given value.

### HasAccountNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) HasAccountNumber() bool`

HasAccountNumber returns a boolean if a field has been set.

### GetBaseSegment

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) GetBaseSegment() string`

GetBaseSegment returns the BaseSegment field if non-nil, zero value otherwise.

### GetBaseSegmentOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) GetBaseSegmentOk() (*string, bool)`

GetBaseSegmentOk returns a tuple with the BaseSegment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaseSegment

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) SetBaseSegment(v string)`

SetBaseSegment sets BaseSegment field to given value.

### HasBaseSegment

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) HasBaseSegment() bool`

HasBaseSegment returns a boolean if a field has been set.

### GetCostCenterSegment

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) GetCostCenterSegment() string`

GetCostCenterSegment returns the CostCenterSegment field if non-nil, zero value otherwise.

### GetCostCenterSegmentOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) GetCostCenterSegmentOk() (*string, bool)`

GetCostCenterSegmentOk returns a tuple with the CostCenterSegment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostCenterSegment

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) SetCostCenterSegment(v string)`

SetCostCenterSegment sets CostCenterSegment field to given value.

### HasCostCenterSegment

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) HasCostCenterSegment() bool`

HasCostCenterSegment returns a boolean if a field has been set.

### GetSubAccountSegment

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) GetSubAccountSegment() string`

GetSubAccountSegment returns the SubAccountSegment field if non-nil, zero value otherwise.

### GetSubAccountSegmentOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) GetSubAccountSegmentOk() (*string, bool)`

GetSubAccountSegmentOk returns a tuple with the SubAccountSegment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubAccountSegment

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) SetSubAccountSegment(v string)`

SetSubAccountSegment sets SubAccountSegment field to given value.

### HasSubAccountSegment

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) HasSubAccountSegment() bool`

HasSubAccountSegment returns a boolean if a field has been set.

### GetDescription

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetCredit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) GetCredit() float64`

GetCredit returns the Credit field if non-nil, zero value otherwise.

### GetCreditOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) GetCreditOk() (*float64, bool)`

GetCreditOk returns a tuple with the Credit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCredit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) SetCredit(v float64)`

SetCredit sets Credit field to given value.

### HasCredit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) HasCredit() bool`

HasCredit returns a boolean if a field has been set.

### GetDebit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) GetDebit() float64`

GetDebit returns the Debit field if non-nil, zero value otherwise.

### GetDebitOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) GetDebitOk() (*float64, bool)`

GetDebitOk returns a tuple with the Debit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDebit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) SetDebit(v float64)`

SetDebit sets Debit field to given value.

### HasDebit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) HasDebit() bool`

HasDebit returns a boolean if a field has been set.

### GetCurrencyCredit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) GetCurrencyCredit() float64`

GetCurrencyCredit returns the CurrencyCredit field if non-nil, zero value otherwise.

### GetCurrencyCreditOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) GetCurrencyCreditOk() (*float64, bool)`

GetCurrencyCreditOk returns a tuple with the CurrencyCredit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyCredit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) SetCurrencyCredit(v float64)`

SetCurrencyCredit sets CurrencyCredit field to given value.

### HasCurrencyCredit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) HasCurrencyCredit() bool`

HasCurrencyCredit returns a boolean if a field has been set.

### GetCurrencyDebit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) GetCurrencyDebit() float64`

GetCurrencyDebit returns the CurrencyDebit field if non-nil, zero value otherwise.

### GetCurrencyDebitOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) GetCurrencyDebitOk() (*float64, bool)`

GetCurrencyDebitOk returns a tuple with the CurrencyDebit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyDebit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) SetCurrencyDebit(v float64)`

SetCurrencyDebit sets CurrencyDebit field to given value.

### HasCurrencyDebit

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) HasCurrencyDebit() bool`

HasCurrencyDebit returns a boolean if a field has been set.

### GetAccountingJobNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) GetAccountingJobNumber() string`

GetAccountingJobNumber returns the AccountingJobNumber field if non-nil, zero value otherwise.

### GetAccountingJobNumberOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) GetAccountingJobNumberOk() (*string, bool)`

GetAccountingJobNumberOk returns a tuple with the AccountingJobNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountingJobNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) SetAccountingJobNumber(v string)`

SetAccountingJobNumber sets AccountingJobNumber field to given value.

### HasAccountingJobNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) HasAccountingJobNumber() bool`

HasAccountingJobNumber returns a boolean if a field has been set.

### GetVoucherNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) GetVoucherNumber() string`

GetVoucherNumber returns the VoucherNumber field if non-nil, zero value otherwise.

### GetVoucherNumberOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) GetVoucherNumberOk() (*string, bool)`

GetVoucherNumberOk returns a tuple with the VoucherNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoucherNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) SetVoucherNumber(v string)`

SetVoucherNumber sets VoucherNumber field to given value.

### HasVoucherNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) HasVoucherNumber() bool`

HasVoucherNumber returns a boolean if a field has been set.

### GetJournalNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) GetJournalNumber() int32`

GetJournalNumber returns the JournalNumber field if non-nil, zero value otherwise.

### GetJournalNumberOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) GetJournalNumberOk() (*int32, bool)`

GetJournalNumberOk returns a tuple with the JournalNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJournalNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) SetJournalNumber(v int32)`

SetJournalNumber sets JournalNumber field to given value.

### HasJournalNumber

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) HasJournalNumber() bool`

HasJournalNumber returns a boolean if a field has been set.

### GetHeaderDescription

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) GetHeaderDescription() string`

GetHeaderDescription returns the HeaderDescription field if non-nil, zero value otherwise.

### GetHeaderDescriptionOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) GetHeaderDescriptionOk() (*string, bool)`

GetHeaderDescriptionOk returns a tuple with the HeaderDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeaderDescription

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) SetHeaderDescription(v string)`

SetHeaderDescription sets HeaderDescription field to given value.

### HasHeaderDescription

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) HasHeaderDescription() bool`

HasHeaderDescription returns a boolean if a field has been set.

### GetPeriod13

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) GetPeriod13() bool`

GetPeriod13 returns the Period13 field if non-nil, zero value otherwise.

### GetPeriod13Ok

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) GetPeriod13Ok() (*bool, bool)`

GetPeriod13Ok returns a tuple with the Period13 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriod13

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) SetPeriod13(v bool)`

SetPeriod13 sets Period13 field to given value.

### HasPeriod13

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) HasPeriod13() bool`

HasPeriod13 returns a boolean if a field has been set.

### GetPeriodAdjustmentEntries

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) GetPeriodAdjustmentEntries() bool`

GetPeriodAdjustmentEntries returns the PeriodAdjustmentEntries field if non-nil, zero value otherwise.

### GetPeriodAdjustmentEntriesOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) GetPeriodAdjustmentEntriesOk() (*bool, bool)`

GetPeriodAdjustmentEntriesOk returns a tuple with the PeriodAdjustmentEntries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriodAdjustmentEntries

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) SetPeriodAdjustmentEntries(v bool)`

SetPeriodAdjustmentEntries sets PeriodAdjustmentEntries field to given value.

### HasPeriodAdjustmentEntries

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) HasPeriodAdjustmentEntries() bool`

HasPeriodAdjustmentEntries returns a boolean if a field has been set.

### GetGovernmentIssuedNo

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) GetGovernmentIssuedNo() string`

GetGovernmentIssuedNo returns the GovernmentIssuedNo field if non-nil, zero value otherwise.

### GetGovernmentIssuedNoOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) GetGovernmentIssuedNoOk() (*string, bool)`

GetGovernmentIssuedNoOk returns a tuple with the GovernmentIssuedNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGovernmentIssuedNo

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) SetGovernmentIssuedNo(v string)`

SetGovernmentIssuedNo sets GovernmentIssuedNo field to given value.

### HasGovernmentIssuedNo

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) HasGovernmentIssuedNo() bool`

HasGovernmentIssuedNo returns a boolean if a field has been set.

### GetModifiedDate

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) GetModifiedDate() time.Time`

GetModifiedDate returns the ModifiedDate field if non-nil, zero value otherwise.

### GetModifiedDateOk

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) GetModifiedDateOk() (*time.Time, bool)`

GetModifiedDateOk returns a tuple with the ModifiedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDate

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) SetModifiedDate(v time.Time)`

SetModifiedDate sets ModifiedDate field to given value.

### HasModifiedDate

`func (o *GeneralLedgerTransactionsApiListGLTransactionLinesForJournalsItem) HasModifiedDate() bool`

HasModifiedDate returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


