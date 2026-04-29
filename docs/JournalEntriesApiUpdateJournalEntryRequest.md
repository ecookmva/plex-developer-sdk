# JournalEntriesApiUpdateJournalEntryRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** |  | [optional] 
**Period** | Pointer to **string** | The accounting period represented by a 2 digit month and a 4 digit year format [MM-YYYY]. | [optional] 
**Description** | Pointer to **string** | A description of the GL journal entry line. | [optional] 
**Note** | Pointer to **string** | The GL journal entry note. | [optional] 
**Period13** | Pointer to **bool** | The 13th Period flag. | [optional] 
**PeriodAdjustment** | Pointer to **bool** | The Period Adjustment flag. | [optional] 
**Status** | Pointer to **string** | The GL journal entry status. | [optional] 
**PostDate** | Pointer to **time.Time** | The GL journal entry post date. | [optional] 
**Currency** | Pointer to **string** | The 3 digit alphanumeric currency code designation. | [optional] 
**ExchangeRate** | Pointer to **float64** | The GL journal entry exchange rate. | [optional] 
**GovernmentIssuedNo** | Pointer to **string** | The GL journal entry government issued number. | [optional] 
**Lines** | Pointer to [**[]LinesItem10**](LinesItem10.md) | A list of GL journal entry distribution lines. | [optional] 
**LineId** | Pointer to **string** | The unique identifier for the GL journal entry line. | [optional] 
**AccountNo** | Pointer to **string** | The unique identifier for the GL journal entry line account. | [optional] 
**Debit** | Pointer to **float64** | The GL journal entry line distribution is calculated as a debit. | [optional] 
**Credit** | Pointer to **float64** | The GL journal entry line distribution is calculated as a credit. | [optional] 
**ExpenseProject** | Pointer to **string** | The GL journal entry line expense project code. | [optional] 
**AccountingJobNo** | Pointer to **string** | The accounting job number for the GL journal entry line, if applicable. | [optional] 
**VoucherDescription** | Pointer to **string** | The GL journal entry line voucher description. | [optional] 
**CurrencyDebit** | Pointer to **float64** | The GL journal entry line distribution amount is a foreign currency debit. | [optional] 
**CurrencyCredit** | Pointer to **float64** | The GL journal entry line distribution amount is a foreign currency credit. | [optional] 

## Methods

### NewJournalEntriesApiUpdateJournalEntryRequest

`func NewJournalEntriesApiUpdateJournalEntryRequest() *JournalEntriesApiUpdateJournalEntryRequest`

NewJournalEntriesApiUpdateJournalEntryRequest instantiates a new JournalEntriesApiUpdateJournalEntryRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewJournalEntriesApiUpdateJournalEntryRequestWithDefaults

`func NewJournalEntriesApiUpdateJournalEntryRequestWithDefaults() *JournalEntriesApiUpdateJournalEntryRequest`

NewJournalEntriesApiUpdateJournalEntryRequestWithDefaults instantiates a new JournalEntriesApiUpdateJournalEntryRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *JournalEntriesApiUpdateJournalEntryRequest) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *JournalEntriesApiUpdateJournalEntryRequest) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *JournalEntriesApiUpdateJournalEntryRequest) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *JournalEntriesApiUpdateJournalEntryRequest) HasId() bool`

HasId returns a boolean if a field has been set.

### GetPeriod

`func (o *JournalEntriesApiUpdateJournalEntryRequest) GetPeriod() string`

GetPeriod returns the Period field if non-nil, zero value otherwise.

### GetPeriodOk

`func (o *JournalEntriesApiUpdateJournalEntryRequest) GetPeriodOk() (*string, bool)`

GetPeriodOk returns a tuple with the Period field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriod

`func (o *JournalEntriesApiUpdateJournalEntryRequest) SetPeriod(v string)`

SetPeriod sets Period field to given value.

### HasPeriod

`func (o *JournalEntriesApiUpdateJournalEntryRequest) HasPeriod() bool`

HasPeriod returns a boolean if a field has been set.

### GetDescription

`func (o *JournalEntriesApiUpdateJournalEntryRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *JournalEntriesApiUpdateJournalEntryRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *JournalEntriesApiUpdateJournalEntryRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *JournalEntriesApiUpdateJournalEntryRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetNote

`func (o *JournalEntriesApiUpdateJournalEntryRequest) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *JournalEntriesApiUpdateJournalEntryRequest) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *JournalEntriesApiUpdateJournalEntryRequest) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *JournalEntriesApiUpdateJournalEntryRequest) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetPeriod13

`func (o *JournalEntriesApiUpdateJournalEntryRequest) GetPeriod13() bool`

GetPeriod13 returns the Period13 field if non-nil, zero value otherwise.

### GetPeriod13Ok

`func (o *JournalEntriesApiUpdateJournalEntryRequest) GetPeriod13Ok() (*bool, bool)`

GetPeriod13Ok returns a tuple with the Period13 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriod13

`func (o *JournalEntriesApiUpdateJournalEntryRequest) SetPeriod13(v bool)`

SetPeriod13 sets Period13 field to given value.

### HasPeriod13

`func (o *JournalEntriesApiUpdateJournalEntryRequest) HasPeriod13() bool`

HasPeriod13 returns a boolean if a field has been set.

### GetPeriodAdjustment

`func (o *JournalEntriesApiUpdateJournalEntryRequest) GetPeriodAdjustment() bool`

GetPeriodAdjustment returns the PeriodAdjustment field if non-nil, zero value otherwise.

### GetPeriodAdjustmentOk

`func (o *JournalEntriesApiUpdateJournalEntryRequest) GetPeriodAdjustmentOk() (*bool, bool)`

GetPeriodAdjustmentOk returns a tuple with the PeriodAdjustment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriodAdjustment

`func (o *JournalEntriesApiUpdateJournalEntryRequest) SetPeriodAdjustment(v bool)`

SetPeriodAdjustment sets PeriodAdjustment field to given value.

### HasPeriodAdjustment

`func (o *JournalEntriesApiUpdateJournalEntryRequest) HasPeriodAdjustment() bool`

HasPeriodAdjustment returns a boolean if a field has been set.

### GetStatus

`func (o *JournalEntriesApiUpdateJournalEntryRequest) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *JournalEntriesApiUpdateJournalEntryRequest) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *JournalEntriesApiUpdateJournalEntryRequest) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *JournalEntriesApiUpdateJournalEntryRequest) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetPostDate

`func (o *JournalEntriesApiUpdateJournalEntryRequest) GetPostDate() time.Time`

GetPostDate returns the PostDate field if non-nil, zero value otherwise.

### GetPostDateOk

`func (o *JournalEntriesApiUpdateJournalEntryRequest) GetPostDateOk() (*time.Time, bool)`

GetPostDateOk returns a tuple with the PostDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostDate

`func (o *JournalEntriesApiUpdateJournalEntryRequest) SetPostDate(v time.Time)`

SetPostDate sets PostDate field to given value.

### HasPostDate

`func (o *JournalEntriesApiUpdateJournalEntryRequest) HasPostDate() bool`

HasPostDate returns a boolean if a field has been set.

### GetCurrency

`func (o *JournalEntriesApiUpdateJournalEntryRequest) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *JournalEntriesApiUpdateJournalEntryRequest) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *JournalEntriesApiUpdateJournalEntryRequest) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *JournalEntriesApiUpdateJournalEntryRequest) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### GetExchangeRate

`func (o *JournalEntriesApiUpdateJournalEntryRequest) GetExchangeRate() float64`

GetExchangeRate returns the ExchangeRate field if non-nil, zero value otherwise.

### GetExchangeRateOk

`func (o *JournalEntriesApiUpdateJournalEntryRequest) GetExchangeRateOk() (*float64, bool)`

GetExchangeRateOk returns a tuple with the ExchangeRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExchangeRate

`func (o *JournalEntriesApiUpdateJournalEntryRequest) SetExchangeRate(v float64)`

SetExchangeRate sets ExchangeRate field to given value.

### HasExchangeRate

`func (o *JournalEntriesApiUpdateJournalEntryRequest) HasExchangeRate() bool`

HasExchangeRate returns a boolean if a field has been set.

### GetGovernmentIssuedNo

`func (o *JournalEntriesApiUpdateJournalEntryRequest) GetGovernmentIssuedNo() string`

GetGovernmentIssuedNo returns the GovernmentIssuedNo field if non-nil, zero value otherwise.

### GetGovernmentIssuedNoOk

`func (o *JournalEntriesApiUpdateJournalEntryRequest) GetGovernmentIssuedNoOk() (*string, bool)`

GetGovernmentIssuedNoOk returns a tuple with the GovernmentIssuedNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGovernmentIssuedNo

`func (o *JournalEntriesApiUpdateJournalEntryRequest) SetGovernmentIssuedNo(v string)`

SetGovernmentIssuedNo sets GovernmentIssuedNo field to given value.

### HasGovernmentIssuedNo

`func (o *JournalEntriesApiUpdateJournalEntryRequest) HasGovernmentIssuedNo() bool`

HasGovernmentIssuedNo returns a boolean if a field has been set.

### GetLines

`func (o *JournalEntriesApiUpdateJournalEntryRequest) GetLines() []LinesItem10`

GetLines returns the Lines field if non-nil, zero value otherwise.

### GetLinesOk

`func (o *JournalEntriesApiUpdateJournalEntryRequest) GetLinesOk() (*[]LinesItem10, bool)`

GetLinesOk returns a tuple with the Lines field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLines

`func (o *JournalEntriesApiUpdateJournalEntryRequest) SetLines(v []LinesItem10)`

SetLines sets Lines field to given value.

### HasLines

`func (o *JournalEntriesApiUpdateJournalEntryRequest) HasLines() bool`

HasLines returns a boolean if a field has been set.

### GetLineId

`func (o *JournalEntriesApiUpdateJournalEntryRequest) GetLineId() string`

GetLineId returns the LineId field if non-nil, zero value otherwise.

### GetLineIdOk

`func (o *JournalEntriesApiUpdateJournalEntryRequest) GetLineIdOk() (*string, bool)`

GetLineIdOk returns a tuple with the LineId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineId

`func (o *JournalEntriesApiUpdateJournalEntryRequest) SetLineId(v string)`

SetLineId sets LineId field to given value.

### HasLineId

`func (o *JournalEntriesApiUpdateJournalEntryRequest) HasLineId() bool`

HasLineId returns a boolean if a field has been set.

### GetAccountNo

`func (o *JournalEntriesApiUpdateJournalEntryRequest) GetAccountNo() string`

GetAccountNo returns the AccountNo field if non-nil, zero value otherwise.

### GetAccountNoOk

`func (o *JournalEntriesApiUpdateJournalEntryRequest) GetAccountNoOk() (*string, bool)`

GetAccountNoOk returns a tuple with the AccountNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNo

`func (o *JournalEntriesApiUpdateJournalEntryRequest) SetAccountNo(v string)`

SetAccountNo sets AccountNo field to given value.

### HasAccountNo

`func (o *JournalEntriesApiUpdateJournalEntryRequest) HasAccountNo() bool`

HasAccountNo returns a boolean if a field has been set.

### GetDebit

`func (o *JournalEntriesApiUpdateJournalEntryRequest) GetDebit() float64`

GetDebit returns the Debit field if non-nil, zero value otherwise.

### GetDebitOk

`func (o *JournalEntriesApiUpdateJournalEntryRequest) GetDebitOk() (*float64, bool)`

GetDebitOk returns a tuple with the Debit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDebit

`func (o *JournalEntriesApiUpdateJournalEntryRequest) SetDebit(v float64)`

SetDebit sets Debit field to given value.

### HasDebit

`func (o *JournalEntriesApiUpdateJournalEntryRequest) HasDebit() bool`

HasDebit returns a boolean if a field has been set.

### GetCredit

`func (o *JournalEntriesApiUpdateJournalEntryRequest) GetCredit() float64`

GetCredit returns the Credit field if non-nil, zero value otherwise.

### GetCreditOk

`func (o *JournalEntriesApiUpdateJournalEntryRequest) GetCreditOk() (*float64, bool)`

GetCreditOk returns a tuple with the Credit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCredit

`func (o *JournalEntriesApiUpdateJournalEntryRequest) SetCredit(v float64)`

SetCredit sets Credit field to given value.

### HasCredit

`func (o *JournalEntriesApiUpdateJournalEntryRequest) HasCredit() bool`

HasCredit returns a boolean if a field has been set.

### GetExpenseProject

`func (o *JournalEntriesApiUpdateJournalEntryRequest) GetExpenseProject() string`

GetExpenseProject returns the ExpenseProject field if non-nil, zero value otherwise.

### GetExpenseProjectOk

`func (o *JournalEntriesApiUpdateJournalEntryRequest) GetExpenseProjectOk() (*string, bool)`

GetExpenseProjectOk returns a tuple with the ExpenseProject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpenseProject

`func (o *JournalEntriesApiUpdateJournalEntryRequest) SetExpenseProject(v string)`

SetExpenseProject sets ExpenseProject field to given value.

### HasExpenseProject

`func (o *JournalEntriesApiUpdateJournalEntryRequest) HasExpenseProject() bool`

HasExpenseProject returns a boolean if a field has been set.

### GetAccountingJobNo

`func (o *JournalEntriesApiUpdateJournalEntryRequest) GetAccountingJobNo() string`

GetAccountingJobNo returns the AccountingJobNo field if non-nil, zero value otherwise.

### GetAccountingJobNoOk

`func (o *JournalEntriesApiUpdateJournalEntryRequest) GetAccountingJobNoOk() (*string, bool)`

GetAccountingJobNoOk returns a tuple with the AccountingJobNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountingJobNo

`func (o *JournalEntriesApiUpdateJournalEntryRequest) SetAccountingJobNo(v string)`

SetAccountingJobNo sets AccountingJobNo field to given value.

### HasAccountingJobNo

`func (o *JournalEntriesApiUpdateJournalEntryRequest) HasAccountingJobNo() bool`

HasAccountingJobNo returns a boolean if a field has been set.

### GetVoucherDescription

`func (o *JournalEntriesApiUpdateJournalEntryRequest) GetVoucherDescription() string`

GetVoucherDescription returns the VoucherDescription field if non-nil, zero value otherwise.

### GetVoucherDescriptionOk

`func (o *JournalEntriesApiUpdateJournalEntryRequest) GetVoucherDescriptionOk() (*string, bool)`

GetVoucherDescriptionOk returns a tuple with the VoucherDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoucherDescription

`func (o *JournalEntriesApiUpdateJournalEntryRequest) SetVoucherDescription(v string)`

SetVoucherDescription sets VoucherDescription field to given value.

### HasVoucherDescription

`func (o *JournalEntriesApiUpdateJournalEntryRequest) HasVoucherDescription() bool`

HasVoucherDescription returns a boolean if a field has been set.

### GetCurrencyDebit

`func (o *JournalEntriesApiUpdateJournalEntryRequest) GetCurrencyDebit() float64`

GetCurrencyDebit returns the CurrencyDebit field if non-nil, zero value otherwise.

### GetCurrencyDebitOk

`func (o *JournalEntriesApiUpdateJournalEntryRequest) GetCurrencyDebitOk() (*float64, bool)`

GetCurrencyDebitOk returns a tuple with the CurrencyDebit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyDebit

`func (o *JournalEntriesApiUpdateJournalEntryRequest) SetCurrencyDebit(v float64)`

SetCurrencyDebit sets CurrencyDebit field to given value.

### HasCurrencyDebit

`func (o *JournalEntriesApiUpdateJournalEntryRequest) HasCurrencyDebit() bool`

HasCurrencyDebit returns a boolean if a field has been set.

### GetCurrencyCredit

`func (o *JournalEntriesApiUpdateJournalEntryRequest) GetCurrencyCredit() float64`

GetCurrencyCredit returns the CurrencyCredit field if non-nil, zero value otherwise.

### GetCurrencyCreditOk

`func (o *JournalEntriesApiUpdateJournalEntryRequest) GetCurrencyCreditOk() (*float64, bool)`

GetCurrencyCreditOk returns a tuple with the CurrencyCredit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyCredit

`func (o *JournalEntriesApiUpdateJournalEntryRequest) SetCurrencyCredit(v float64)`

SetCurrencyCredit sets CurrencyCredit field to given value.

### HasCurrencyCredit

`func (o *JournalEntriesApiUpdateJournalEntryRequest) HasCurrencyCredit() bool`

HasCurrencyCredit returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


