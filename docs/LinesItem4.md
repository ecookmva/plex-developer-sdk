# LinesItem4

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccountNumber** | Pointer to **string** | The AR deposit line account number. | [optional] 
**AccountId** | Pointer to **string** | A unique identifier for the AR deposit line account. | [optional] 
**BaseSegment** | Pointer to **string** | The AR deposit line base account segment. | [optional] 
**CostCenterSegment** | Pointer to **string** | The AR deposit line account cost center segment. | [optional] 
**SubAccountSegment** | Pointer to **string** | The AR deposit line account location segment. | [optional] 
**Credit** | Pointer to **float64** | AR deposit line distribution is calculated as a credit. | [optional] 
**Debit** | Pointer to **float64** | AR deposit line distribution is calculated as a debit. | [optional] 
**CurrencyCredit** | Pointer to **float64** | AR deposit line distribution amount is a foreign currency credit. | [optional] 
**CurrencyDebit** | Pointer to **float64** | AR deposit line distribution amount is a foreign currency debit. | [optional] 

## Methods

### NewLinesItem4

`func NewLinesItem4() *LinesItem4`

NewLinesItem4 instantiates a new LinesItem4 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLinesItem4WithDefaults

`func NewLinesItem4WithDefaults() *LinesItem4`

NewLinesItem4WithDefaults instantiates a new LinesItem4 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccountNumber

`func (o *LinesItem4) GetAccountNumber() string`

GetAccountNumber returns the AccountNumber field if non-nil, zero value otherwise.

### GetAccountNumberOk

`func (o *LinesItem4) GetAccountNumberOk() (*string, bool)`

GetAccountNumberOk returns a tuple with the AccountNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumber

`func (o *LinesItem4) SetAccountNumber(v string)`

SetAccountNumber sets AccountNumber field to given value.

### HasAccountNumber

`func (o *LinesItem4) HasAccountNumber() bool`

HasAccountNumber returns a boolean if a field has been set.

### GetAccountId

`func (o *LinesItem4) GetAccountId() string`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *LinesItem4) GetAccountIdOk() (*string, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *LinesItem4) SetAccountId(v string)`

SetAccountId sets AccountId field to given value.

### HasAccountId

`func (o *LinesItem4) HasAccountId() bool`

HasAccountId returns a boolean if a field has been set.

### GetBaseSegment

`func (o *LinesItem4) GetBaseSegment() string`

GetBaseSegment returns the BaseSegment field if non-nil, zero value otherwise.

### GetBaseSegmentOk

`func (o *LinesItem4) GetBaseSegmentOk() (*string, bool)`

GetBaseSegmentOk returns a tuple with the BaseSegment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaseSegment

`func (o *LinesItem4) SetBaseSegment(v string)`

SetBaseSegment sets BaseSegment field to given value.

### HasBaseSegment

`func (o *LinesItem4) HasBaseSegment() bool`

HasBaseSegment returns a boolean if a field has been set.

### GetCostCenterSegment

`func (o *LinesItem4) GetCostCenterSegment() string`

GetCostCenterSegment returns the CostCenterSegment field if non-nil, zero value otherwise.

### GetCostCenterSegmentOk

`func (o *LinesItem4) GetCostCenterSegmentOk() (*string, bool)`

GetCostCenterSegmentOk returns a tuple with the CostCenterSegment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostCenterSegment

`func (o *LinesItem4) SetCostCenterSegment(v string)`

SetCostCenterSegment sets CostCenterSegment field to given value.

### HasCostCenterSegment

`func (o *LinesItem4) HasCostCenterSegment() bool`

HasCostCenterSegment returns a boolean if a field has been set.

### GetSubAccountSegment

`func (o *LinesItem4) GetSubAccountSegment() string`

GetSubAccountSegment returns the SubAccountSegment field if non-nil, zero value otherwise.

### GetSubAccountSegmentOk

`func (o *LinesItem4) GetSubAccountSegmentOk() (*string, bool)`

GetSubAccountSegmentOk returns a tuple with the SubAccountSegment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubAccountSegment

`func (o *LinesItem4) SetSubAccountSegment(v string)`

SetSubAccountSegment sets SubAccountSegment field to given value.

### HasSubAccountSegment

`func (o *LinesItem4) HasSubAccountSegment() bool`

HasSubAccountSegment returns a boolean if a field has been set.

### GetCredit

`func (o *LinesItem4) GetCredit() float64`

GetCredit returns the Credit field if non-nil, zero value otherwise.

### GetCreditOk

`func (o *LinesItem4) GetCreditOk() (*float64, bool)`

GetCreditOk returns a tuple with the Credit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCredit

`func (o *LinesItem4) SetCredit(v float64)`

SetCredit sets Credit field to given value.

### HasCredit

`func (o *LinesItem4) HasCredit() bool`

HasCredit returns a boolean if a field has been set.

### GetDebit

`func (o *LinesItem4) GetDebit() float64`

GetDebit returns the Debit field if non-nil, zero value otherwise.

### GetDebitOk

`func (o *LinesItem4) GetDebitOk() (*float64, bool)`

GetDebitOk returns a tuple with the Debit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDebit

`func (o *LinesItem4) SetDebit(v float64)`

SetDebit sets Debit field to given value.

### HasDebit

`func (o *LinesItem4) HasDebit() bool`

HasDebit returns a boolean if a field has been set.

### GetCurrencyCredit

`func (o *LinesItem4) GetCurrencyCredit() float64`

GetCurrencyCredit returns the CurrencyCredit field if non-nil, zero value otherwise.

### GetCurrencyCreditOk

`func (o *LinesItem4) GetCurrencyCreditOk() (*float64, bool)`

GetCurrencyCreditOk returns a tuple with the CurrencyCredit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyCredit

`func (o *LinesItem4) SetCurrencyCredit(v float64)`

SetCurrencyCredit sets CurrencyCredit field to given value.

### HasCurrencyCredit

`func (o *LinesItem4) HasCurrencyCredit() bool`

HasCurrencyCredit returns a boolean if a field has been set.

### GetCurrencyDebit

`func (o *LinesItem4) GetCurrencyDebit() float64`

GetCurrencyDebit returns the CurrencyDebit field if non-nil, zero value otherwise.

### GetCurrencyDebitOk

`func (o *LinesItem4) GetCurrencyDebitOk() (*float64, bool)`

GetCurrencyDebitOk returns a tuple with the CurrencyDebit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyDebit

`func (o *LinesItem4) SetCurrencyDebit(v float64)`

SetCurrencyDebit sets CurrencyDebit field to given value.

### HasCurrencyDebit

`func (o *LinesItem4) HasCurrencyDebit() bool`

HasCurrencyDebit returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


