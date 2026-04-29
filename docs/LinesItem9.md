# LinesItem9

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | The unique identifier for the GL journal entry line item number. | [optional] 
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

### NewLinesItem9

`func NewLinesItem9() *LinesItem9`

NewLinesItem9 instantiates a new LinesItem9 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLinesItem9WithDefaults

`func NewLinesItem9WithDefaults() *LinesItem9`

NewLinesItem9WithDefaults instantiates a new LinesItem9 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *LinesItem9) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *LinesItem9) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *LinesItem9) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *LinesItem9) HasId() bool`

HasId returns a boolean if a field has been set.

### GetAccountNo

`func (o *LinesItem9) GetAccountNo() string`

GetAccountNo returns the AccountNo field if non-nil, zero value otherwise.

### GetAccountNoOk

`func (o *LinesItem9) GetAccountNoOk() (*string, bool)`

GetAccountNoOk returns a tuple with the AccountNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNo

`func (o *LinesItem9) SetAccountNo(v string)`

SetAccountNo sets AccountNo field to given value.

### HasAccountNo

`func (o *LinesItem9) HasAccountNo() bool`

HasAccountNo returns a boolean if a field has been set.

### GetDescription

`func (o *LinesItem9) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *LinesItem9) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *LinesItem9) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *LinesItem9) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetDebit

`func (o *LinesItem9) GetDebit() float64`

GetDebit returns the Debit field if non-nil, zero value otherwise.

### GetDebitOk

`func (o *LinesItem9) GetDebitOk() (*float64, bool)`

GetDebitOk returns a tuple with the Debit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDebit

`func (o *LinesItem9) SetDebit(v float64)`

SetDebit sets Debit field to given value.

### HasDebit

`func (o *LinesItem9) HasDebit() bool`

HasDebit returns a boolean if a field has been set.

### GetCredit

`func (o *LinesItem9) GetCredit() float64`

GetCredit returns the Credit field if non-nil, zero value otherwise.

### GetCreditOk

`func (o *LinesItem9) GetCreditOk() (*float64, bool)`

GetCreditOk returns a tuple with the Credit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCredit

`func (o *LinesItem9) SetCredit(v float64)`

SetCredit sets Credit field to given value.

### HasCredit

`func (o *LinesItem9) HasCredit() bool`

HasCredit returns a boolean if a field has been set.

### GetExpenseProject

`func (o *LinesItem9) GetExpenseProject() string`

GetExpenseProject returns the ExpenseProject field if non-nil, zero value otherwise.

### GetExpenseProjectOk

`func (o *LinesItem9) GetExpenseProjectOk() (*string, bool)`

GetExpenseProjectOk returns a tuple with the ExpenseProject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpenseProject

`func (o *LinesItem9) SetExpenseProject(v string)`

SetExpenseProject sets ExpenseProject field to given value.

### HasExpenseProject

`func (o *LinesItem9) HasExpenseProject() bool`

HasExpenseProject returns a boolean if a field has been set.

### GetAccountingJobNo

`func (o *LinesItem9) GetAccountingJobNo() string`

GetAccountingJobNo returns the AccountingJobNo field if non-nil, zero value otherwise.

### GetAccountingJobNoOk

`func (o *LinesItem9) GetAccountingJobNoOk() (*string, bool)`

GetAccountingJobNoOk returns a tuple with the AccountingJobNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountingJobNo

`func (o *LinesItem9) SetAccountingJobNo(v string)`

SetAccountingJobNo sets AccountingJobNo field to given value.

### HasAccountingJobNo

`func (o *LinesItem9) HasAccountingJobNo() bool`

HasAccountingJobNo returns a boolean if a field has been set.

### GetVoucherDescription

`func (o *LinesItem9) GetVoucherDescription() string`

GetVoucherDescription returns the VoucherDescription field if non-nil, zero value otherwise.

### GetVoucherDescriptionOk

`func (o *LinesItem9) GetVoucherDescriptionOk() (*string, bool)`

GetVoucherDescriptionOk returns a tuple with the VoucherDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoucherDescription

`func (o *LinesItem9) SetVoucherDescription(v string)`

SetVoucherDescription sets VoucherDescription field to given value.

### HasVoucherDescription

`func (o *LinesItem9) HasVoucherDescription() bool`

HasVoucherDescription returns a boolean if a field has been set.

### GetCurrencyDebit

`func (o *LinesItem9) GetCurrencyDebit() float64`

GetCurrencyDebit returns the CurrencyDebit field if non-nil, zero value otherwise.

### GetCurrencyDebitOk

`func (o *LinesItem9) GetCurrencyDebitOk() (*float64, bool)`

GetCurrencyDebitOk returns a tuple with the CurrencyDebit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyDebit

`func (o *LinesItem9) SetCurrencyDebit(v float64)`

SetCurrencyDebit sets CurrencyDebit field to given value.

### HasCurrencyDebit

`func (o *LinesItem9) HasCurrencyDebit() bool`

HasCurrencyDebit returns a boolean if a field has been set.

### GetCurrencyCredit

`func (o *LinesItem9) GetCurrencyCredit() float64`

GetCurrencyCredit returns the CurrencyCredit field if non-nil, zero value otherwise.

### GetCurrencyCreditOk

`func (o *LinesItem9) GetCurrencyCreditOk() (*float64, bool)`

GetCurrencyCreditOk returns a tuple with the CurrencyCredit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyCredit

`func (o *LinesItem9) SetCurrencyCredit(v float64)`

SetCurrencyCredit sets CurrencyCredit field to given value.

### HasCurrencyCredit

`func (o *LinesItem9) HasCurrencyCredit() bool`

HasCurrencyCredit returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


