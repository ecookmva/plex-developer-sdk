# LinesItem8

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**LineId** | Pointer to **string** | The unique identifier for the GL journal entry line item number. | [optional] 
**AccountId** | Pointer to **string** | The unique identifier for the GL journal entry line account. | [optional] 
**AccountNumber** | Pointer to **string** | The GL journal entry line account number. | [optional] 
**Description** | Pointer to **string** | A description of the GL journal entry line. | [optional] 
**Debit** | Pointer to **float64** | The GL journal entry line distribution is calculated as a debit. | [optional] 
**Credit** | Pointer to **float64** | The GL journal entry line distribution is calculated as a credit. | [optional] 
**CreatedDate** | Pointer to **time.Time** | The date a GL journal entry line was created. | [optional] 
**ModifiedById** | Pointer to **string** | The ID of the user who last modified the GL journal entry line record. | [optional] 
**ModifiedDate** | Pointer to **time.Time** | The date the GL journal entry line was last modified. | [optional] 
**CurrencyDebit** | Pointer to **float64** | The GL journal entry line distribution amount is a foreign currency debit. | [optional] 
**CurrencyCredit** | Pointer to **float64** | The GL journal entry line distribution amount is a foreign currency credit. | [optional] 
**BaseSegment** | Pointer to **string** | The GL journal entry line base account segment. | [optional] 
**CostCenterSegment** | Pointer to **string** | The GL journal entry line account cost center segment. | [optional] 
**SubAccountSegment** | Pointer to **string** | The GL journal entry line account location segment. | [optional] 
**AccountingJobNumber** | Pointer to **string** | The accounting job number for the GL journal entry line, if applicable. | [optional] 
**VoucherDescription** | Pointer to **string** | The GL entry line voucher description. | [optional] 
**ExpenseProject** | Pointer to **string** | The GL entry line expense project code. | [optional] 

## Methods

### NewLinesItem8

`func NewLinesItem8() *LinesItem8`

NewLinesItem8 instantiates a new LinesItem8 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLinesItem8WithDefaults

`func NewLinesItem8WithDefaults() *LinesItem8`

NewLinesItem8WithDefaults instantiates a new LinesItem8 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLineId

`func (o *LinesItem8) GetLineId() string`

GetLineId returns the LineId field if non-nil, zero value otherwise.

### GetLineIdOk

`func (o *LinesItem8) GetLineIdOk() (*string, bool)`

GetLineIdOk returns a tuple with the LineId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineId

`func (o *LinesItem8) SetLineId(v string)`

SetLineId sets LineId field to given value.

### HasLineId

`func (o *LinesItem8) HasLineId() bool`

HasLineId returns a boolean if a field has been set.

### GetAccountId

`func (o *LinesItem8) GetAccountId() string`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *LinesItem8) GetAccountIdOk() (*string, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *LinesItem8) SetAccountId(v string)`

SetAccountId sets AccountId field to given value.

### HasAccountId

`func (o *LinesItem8) HasAccountId() bool`

HasAccountId returns a boolean if a field has been set.

### GetAccountNumber

`func (o *LinesItem8) GetAccountNumber() string`

GetAccountNumber returns the AccountNumber field if non-nil, zero value otherwise.

### GetAccountNumberOk

`func (o *LinesItem8) GetAccountNumberOk() (*string, bool)`

GetAccountNumberOk returns a tuple with the AccountNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumber

`func (o *LinesItem8) SetAccountNumber(v string)`

SetAccountNumber sets AccountNumber field to given value.

### HasAccountNumber

`func (o *LinesItem8) HasAccountNumber() bool`

HasAccountNumber returns a boolean if a field has been set.

### GetDescription

`func (o *LinesItem8) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *LinesItem8) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *LinesItem8) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *LinesItem8) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetDebit

`func (o *LinesItem8) GetDebit() float64`

GetDebit returns the Debit field if non-nil, zero value otherwise.

### GetDebitOk

`func (o *LinesItem8) GetDebitOk() (*float64, bool)`

GetDebitOk returns a tuple with the Debit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDebit

`func (o *LinesItem8) SetDebit(v float64)`

SetDebit sets Debit field to given value.

### HasDebit

`func (o *LinesItem8) HasDebit() bool`

HasDebit returns a boolean if a field has been set.

### GetCredit

`func (o *LinesItem8) GetCredit() float64`

GetCredit returns the Credit field if non-nil, zero value otherwise.

### GetCreditOk

`func (o *LinesItem8) GetCreditOk() (*float64, bool)`

GetCreditOk returns a tuple with the Credit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCredit

`func (o *LinesItem8) SetCredit(v float64)`

SetCredit sets Credit field to given value.

### HasCredit

`func (o *LinesItem8) HasCredit() bool`

HasCredit returns a boolean if a field has been set.

### GetCreatedDate

`func (o *LinesItem8) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *LinesItem8) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *LinesItem8) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *LinesItem8) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.

### GetModifiedById

`func (o *LinesItem8) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *LinesItem8) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *LinesItem8) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *LinesItem8) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetModifiedDate

`func (o *LinesItem8) GetModifiedDate() time.Time`

GetModifiedDate returns the ModifiedDate field if non-nil, zero value otherwise.

### GetModifiedDateOk

`func (o *LinesItem8) GetModifiedDateOk() (*time.Time, bool)`

GetModifiedDateOk returns a tuple with the ModifiedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDate

`func (o *LinesItem8) SetModifiedDate(v time.Time)`

SetModifiedDate sets ModifiedDate field to given value.

### HasModifiedDate

`func (o *LinesItem8) HasModifiedDate() bool`

HasModifiedDate returns a boolean if a field has been set.

### GetCurrencyDebit

`func (o *LinesItem8) GetCurrencyDebit() float64`

GetCurrencyDebit returns the CurrencyDebit field if non-nil, zero value otherwise.

### GetCurrencyDebitOk

`func (o *LinesItem8) GetCurrencyDebitOk() (*float64, bool)`

GetCurrencyDebitOk returns a tuple with the CurrencyDebit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyDebit

`func (o *LinesItem8) SetCurrencyDebit(v float64)`

SetCurrencyDebit sets CurrencyDebit field to given value.

### HasCurrencyDebit

`func (o *LinesItem8) HasCurrencyDebit() bool`

HasCurrencyDebit returns a boolean if a field has been set.

### GetCurrencyCredit

`func (o *LinesItem8) GetCurrencyCredit() float64`

GetCurrencyCredit returns the CurrencyCredit field if non-nil, zero value otherwise.

### GetCurrencyCreditOk

`func (o *LinesItem8) GetCurrencyCreditOk() (*float64, bool)`

GetCurrencyCreditOk returns a tuple with the CurrencyCredit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyCredit

`func (o *LinesItem8) SetCurrencyCredit(v float64)`

SetCurrencyCredit sets CurrencyCredit field to given value.

### HasCurrencyCredit

`func (o *LinesItem8) HasCurrencyCredit() bool`

HasCurrencyCredit returns a boolean if a field has been set.

### GetBaseSegment

`func (o *LinesItem8) GetBaseSegment() string`

GetBaseSegment returns the BaseSegment field if non-nil, zero value otherwise.

### GetBaseSegmentOk

`func (o *LinesItem8) GetBaseSegmentOk() (*string, bool)`

GetBaseSegmentOk returns a tuple with the BaseSegment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaseSegment

`func (o *LinesItem8) SetBaseSegment(v string)`

SetBaseSegment sets BaseSegment field to given value.

### HasBaseSegment

`func (o *LinesItem8) HasBaseSegment() bool`

HasBaseSegment returns a boolean if a field has been set.

### GetCostCenterSegment

`func (o *LinesItem8) GetCostCenterSegment() string`

GetCostCenterSegment returns the CostCenterSegment field if non-nil, zero value otherwise.

### GetCostCenterSegmentOk

`func (o *LinesItem8) GetCostCenterSegmentOk() (*string, bool)`

GetCostCenterSegmentOk returns a tuple with the CostCenterSegment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostCenterSegment

`func (o *LinesItem8) SetCostCenterSegment(v string)`

SetCostCenterSegment sets CostCenterSegment field to given value.

### HasCostCenterSegment

`func (o *LinesItem8) HasCostCenterSegment() bool`

HasCostCenterSegment returns a boolean if a field has been set.

### GetSubAccountSegment

`func (o *LinesItem8) GetSubAccountSegment() string`

GetSubAccountSegment returns the SubAccountSegment field if non-nil, zero value otherwise.

### GetSubAccountSegmentOk

`func (o *LinesItem8) GetSubAccountSegmentOk() (*string, bool)`

GetSubAccountSegmentOk returns a tuple with the SubAccountSegment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubAccountSegment

`func (o *LinesItem8) SetSubAccountSegment(v string)`

SetSubAccountSegment sets SubAccountSegment field to given value.

### HasSubAccountSegment

`func (o *LinesItem8) HasSubAccountSegment() bool`

HasSubAccountSegment returns a boolean if a field has been set.

### GetAccountingJobNumber

`func (o *LinesItem8) GetAccountingJobNumber() string`

GetAccountingJobNumber returns the AccountingJobNumber field if non-nil, zero value otherwise.

### GetAccountingJobNumberOk

`func (o *LinesItem8) GetAccountingJobNumberOk() (*string, bool)`

GetAccountingJobNumberOk returns a tuple with the AccountingJobNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountingJobNumber

`func (o *LinesItem8) SetAccountingJobNumber(v string)`

SetAccountingJobNumber sets AccountingJobNumber field to given value.

### HasAccountingJobNumber

`func (o *LinesItem8) HasAccountingJobNumber() bool`

HasAccountingJobNumber returns a boolean if a field has been set.

### GetVoucherDescription

`func (o *LinesItem8) GetVoucherDescription() string`

GetVoucherDescription returns the VoucherDescription field if non-nil, zero value otherwise.

### GetVoucherDescriptionOk

`func (o *LinesItem8) GetVoucherDescriptionOk() (*string, bool)`

GetVoucherDescriptionOk returns a tuple with the VoucherDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoucherDescription

`func (o *LinesItem8) SetVoucherDescription(v string)`

SetVoucherDescription sets VoucherDescription field to given value.

### HasVoucherDescription

`func (o *LinesItem8) HasVoucherDescription() bool`

HasVoucherDescription returns a boolean if a field has been set.

### GetExpenseProject

`func (o *LinesItem8) GetExpenseProject() string`

GetExpenseProject returns the ExpenseProject field if non-nil, zero value otherwise.

### GetExpenseProjectOk

`func (o *LinesItem8) GetExpenseProjectOk() (*string, bool)`

GetExpenseProjectOk returns a tuple with the ExpenseProject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpenseProject

`func (o *LinesItem8) SetExpenseProject(v string)`

SetExpenseProject sets ExpenseProject field to given value.

### HasExpenseProject

`func (o *LinesItem8) HasExpenseProject() bool`

HasExpenseProject returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


