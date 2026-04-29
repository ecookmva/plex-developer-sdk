# LinesItem10

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**LineId** | Pointer to **string** | The unique identifier for the GL journal entry line. | [optional] 
**AccountNo** | Pointer to **string** | The unique identifier for the GL journal entry line account. | [optional] 
**Description** | Pointer to **string** | A description of the GL journal entry line. | [optional] 
**Debit** | Pointer to **float64** | The GL journal entry line distribution is calculated as a debit. | [optional] 
**Credit** | Pointer to **float64** | The GL journal entry line distribution is calculated as a credit. | [optional] 
**ExpenseProject** | Pointer to **string** | The GL journal entry line expense project code. | [optional] 
**AccountingJobNo** | Pointer to **string** | The accounting job number for the GL journal entry line, if applicable. | [optional] 
**VoucherDescription** | Pointer to **string** | The GL journal entry line voucher description. | [optional] 
**CurrencyDebit** | Pointer to **float64** | The GL journal entry line distribution amount is a foreign currency debit. | [optional] 
**CurrencyCredit** | Pointer to **float64** | The GL journal entry line distribution amount is a foreign currency credit. | [optional] 

## Methods

### NewLinesItem10

`func NewLinesItem10() *LinesItem10`

NewLinesItem10 instantiates a new LinesItem10 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLinesItem10WithDefaults

`func NewLinesItem10WithDefaults() *LinesItem10`

NewLinesItem10WithDefaults instantiates a new LinesItem10 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLineId

`func (o *LinesItem10) GetLineId() string`

GetLineId returns the LineId field if non-nil, zero value otherwise.

### GetLineIdOk

`func (o *LinesItem10) GetLineIdOk() (*string, bool)`

GetLineIdOk returns a tuple with the LineId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineId

`func (o *LinesItem10) SetLineId(v string)`

SetLineId sets LineId field to given value.

### HasLineId

`func (o *LinesItem10) HasLineId() bool`

HasLineId returns a boolean if a field has been set.

### GetAccountNo

`func (o *LinesItem10) GetAccountNo() string`

GetAccountNo returns the AccountNo field if non-nil, zero value otherwise.

### GetAccountNoOk

`func (o *LinesItem10) GetAccountNoOk() (*string, bool)`

GetAccountNoOk returns a tuple with the AccountNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNo

`func (o *LinesItem10) SetAccountNo(v string)`

SetAccountNo sets AccountNo field to given value.

### HasAccountNo

`func (o *LinesItem10) HasAccountNo() bool`

HasAccountNo returns a boolean if a field has been set.

### GetDescription

`func (o *LinesItem10) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *LinesItem10) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *LinesItem10) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *LinesItem10) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetDebit

`func (o *LinesItem10) GetDebit() float64`

GetDebit returns the Debit field if non-nil, zero value otherwise.

### GetDebitOk

`func (o *LinesItem10) GetDebitOk() (*float64, bool)`

GetDebitOk returns a tuple with the Debit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDebit

`func (o *LinesItem10) SetDebit(v float64)`

SetDebit sets Debit field to given value.

### HasDebit

`func (o *LinesItem10) HasDebit() bool`

HasDebit returns a boolean if a field has been set.

### GetCredit

`func (o *LinesItem10) GetCredit() float64`

GetCredit returns the Credit field if non-nil, zero value otherwise.

### GetCreditOk

`func (o *LinesItem10) GetCreditOk() (*float64, bool)`

GetCreditOk returns a tuple with the Credit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCredit

`func (o *LinesItem10) SetCredit(v float64)`

SetCredit sets Credit field to given value.

### HasCredit

`func (o *LinesItem10) HasCredit() bool`

HasCredit returns a boolean if a field has been set.

### GetExpenseProject

`func (o *LinesItem10) GetExpenseProject() string`

GetExpenseProject returns the ExpenseProject field if non-nil, zero value otherwise.

### GetExpenseProjectOk

`func (o *LinesItem10) GetExpenseProjectOk() (*string, bool)`

GetExpenseProjectOk returns a tuple with the ExpenseProject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpenseProject

`func (o *LinesItem10) SetExpenseProject(v string)`

SetExpenseProject sets ExpenseProject field to given value.

### HasExpenseProject

`func (o *LinesItem10) HasExpenseProject() bool`

HasExpenseProject returns a boolean if a field has been set.

### GetAccountingJobNo

`func (o *LinesItem10) GetAccountingJobNo() string`

GetAccountingJobNo returns the AccountingJobNo field if non-nil, zero value otherwise.

### GetAccountingJobNoOk

`func (o *LinesItem10) GetAccountingJobNoOk() (*string, bool)`

GetAccountingJobNoOk returns a tuple with the AccountingJobNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountingJobNo

`func (o *LinesItem10) SetAccountingJobNo(v string)`

SetAccountingJobNo sets AccountingJobNo field to given value.

### HasAccountingJobNo

`func (o *LinesItem10) HasAccountingJobNo() bool`

HasAccountingJobNo returns a boolean if a field has been set.

### GetVoucherDescription

`func (o *LinesItem10) GetVoucherDescription() string`

GetVoucherDescription returns the VoucherDescription field if non-nil, zero value otherwise.

### GetVoucherDescriptionOk

`func (o *LinesItem10) GetVoucherDescriptionOk() (*string, bool)`

GetVoucherDescriptionOk returns a tuple with the VoucherDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoucherDescription

`func (o *LinesItem10) SetVoucherDescription(v string)`

SetVoucherDescription sets VoucherDescription field to given value.

### HasVoucherDescription

`func (o *LinesItem10) HasVoucherDescription() bool`

HasVoucherDescription returns a boolean if a field has been set.

### GetCurrencyDebit

`func (o *LinesItem10) GetCurrencyDebit() float64`

GetCurrencyDebit returns the CurrencyDebit field if non-nil, zero value otherwise.

### GetCurrencyDebitOk

`func (o *LinesItem10) GetCurrencyDebitOk() (*float64, bool)`

GetCurrencyDebitOk returns a tuple with the CurrencyDebit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyDebit

`func (o *LinesItem10) SetCurrencyDebit(v float64)`

SetCurrencyDebit sets CurrencyDebit field to given value.

### HasCurrencyDebit

`func (o *LinesItem10) HasCurrencyDebit() bool`

HasCurrencyDebit returns a boolean if a field has been set.

### GetCurrencyCredit

`func (o *LinesItem10) GetCurrencyCredit() float64`

GetCurrencyCredit returns the CurrencyCredit field if non-nil, zero value otherwise.

### GetCurrencyCreditOk

`func (o *LinesItem10) GetCurrencyCreditOk() (*float64, bool)`

GetCurrencyCreditOk returns a tuple with the CurrencyCredit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyCredit

`func (o *LinesItem10) SetCurrencyCredit(v float64)`

SetCurrencyCredit sets CurrencyCredit field to given value.

### HasCurrencyCredit

`func (o *LinesItem10) HasCurrencyCredit() bool`

HasCurrencyCredit returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


