# TrialBalanceLinesItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccountId** | Pointer to **string** | A unique identifier for the trial balance account. | [optional] 
**AccountNumber** | Pointer to **string** | The trial balance account number. | [optional] 
**AccountName** | Pointer to **string** | The name of the account. | [optional] 
**BaseSegment** | Pointer to **string** | The trial balance base account segment. | [optional] 
**CostCenterSegment** | Pointer to **string** | The trial balance account cost center segment. | [optional] 
**SubAccountSegment** | Pointer to **string** | The trial balance account location segment. | [optional] 
**CurrentDebit** | Pointer to **float64** | Current period account debit. | [optional] 
**CurrentCredit** | Pointer to **float64** | Current period account credit. | [optional] 
**CurrentBalance** | Pointer to **float64** | Current period net Balance of the account. | [optional] 
**YtdDebit** | Pointer to **float64** | Identifies year to date debit account balance. | [optional] 
**YtdCredit** | Pointer to **float64** | Identifies year to date credit account balance. | [optional] 
**YtdBalance** | Pointer to **float64** | Identifies year to date net Balance. | [optional] 
**StatutoryName** | Pointer to **string** | Statutory account trial balance name. | [optional] 
**StatutoryNumber** | Pointer to **string** | Statutory account trial balance account number. | [optional] 
**PeriodDisplay** | Pointer to **string** | The period in which trial balance is recorded. | [optional] 

## Methods

### NewTrialBalanceLinesItem

`func NewTrialBalanceLinesItem() *TrialBalanceLinesItem`

NewTrialBalanceLinesItem instantiates a new TrialBalanceLinesItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrialBalanceLinesItemWithDefaults

`func NewTrialBalanceLinesItemWithDefaults() *TrialBalanceLinesItem`

NewTrialBalanceLinesItemWithDefaults instantiates a new TrialBalanceLinesItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccountId

`func (o *TrialBalanceLinesItem) GetAccountId() string`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *TrialBalanceLinesItem) GetAccountIdOk() (*string, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *TrialBalanceLinesItem) SetAccountId(v string)`

SetAccountId sets AccountId field to given value.

### HasAccountId

`func (o *TrialBalanceLinesItem) HasAccountId() bool`

HasAccountId returns a boolean if a field has been set.

### GetAccountNumber

`func (o *TrialBalanceLinesItem) GetAccountNumber() string`

GetAccountNumber returns the AccountNumber field if non-nil, zero value otherwise.

### GetAccountNumberOk

`func (o *TrialBalanceLinesItem) GetAccountNumberOk() (*string, bool)`

GetAccountNumberOk returns a tuple with the AccountNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumber

`func (o *TrialBalanceLinesItem) SetAccountNumber(v string)`

SetAccountNumber sets AccountNumber field to given value.

### HasAccountNumber

`func (o *TrialBalanceLinesItem) HasAccountNumber() bool`

HasAccountNumber returns a boolean if a field has been set.

### GetAccountName

`func (o *TrialBalanceLinesItem) GetAccountName() string`

GetAccountName returns the AccountName field if non-nil, zero value otherwise.

### GetAccountNameOk

`func (o *TrialBalanceLinesItem) GetAccountNameOk() (*string, bool)`

GetAccountNameOk returns a tuple with the AccountName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountName

`func (o *TrialBalanceLinesItem) SetAccountName(v string)`

SetAccountName sets AccountName field to given value.

### HasAccountName

`func (o *TrialBalanceLinesItem) HasAccountName() bool`

HasAccountName returns a boolean if a field has been set.

### GetBaseSegment

`func (o *TrialBalanceLinesItem) GetBaseSegment() string`

GetBaseSegment returns the BaseSegment field if non-nil, zero value otherwise.

### GetBaseSegmentOk

`func (o *TrialBalanceLinesItem) GetBaseSegmentOk() (*string, bool)`

GetBaseSegmentOk returns a tuple with the BaseSegment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaseSegment

`func (o *TrialBalanceLinesItem) SetBaseSegment(v string)`

SetBaseSegment sets BaseSegment field to given value.

### HasBaseSegment

`func (o *TrialBalanceLinesItem) HasBaseSegment() bool`

HasBaseSegment returns a boolean if a field has been set.

### GetCostCenterSegment

`func (o *TrialBalanceLinesItem) GetCostCenterSegment() string`

GetCostCenterSegment returns the CostCenterSegment field if non-nil, zero value otherwise.

### GetCostCenterSegmentOk

`func (o *TrialBalanceLinesItem) GetCostCenterSegmentOk() (*string, bool)`

GetCostCenterSegmentOk returns a tuple with the CostCenterSegment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostCenterSegment

`func (o *TrialBalanceLinesItem) SetCostCenterSegment(v string)`

SetCostCenterSegment sets CostCenterSegment field to given value.

### HasCostCenterSegment

`func (o *TrialBalanceLinesItem) HasCostCenterSegment() bool`

HasCostCenterSegment returns a boolean if a field has been set.

### GetSubAccountSegment

`func (o *TrialBalanceLinesItem) GetSubAccountSegment() string`

GetSubAccountSegment returns the SubAccountSegment field if non-nil, zero value otherwise.

### GetSubAccountSegmentOk

`func (o *TrialBalanceLinesItem) GetSubAccountSegmentOk() (*string, bool)`

GetSubAccountSegmentOk returns a tuple with the SubAccountSegment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubAccountSegment

`func (o *TrialBalanceLinesItem) SetSubAccountSegment(v string)`

SetSubAccountSegment sets SubAccountSegment field to given value.

### HasSubAccountSegment

`func (o *TrialBalanceLinesItem) HasSubAccountSegment() bool`

HasSubAccountSegment returns a boolean if a field has been set.

### GetCurrentDebit

`func (o *TrialBalanceLinesItem) GetCurrentDebit() float64`

GetCurrentDebit returns the CurrentDebit field if non-nil, zero value otherwise.

### GetCurrentDebitOk

`func (o *TrialBalanceLinesItem) GetCurrentDebitOk() (*float64, bool)`

GetCurrentDebitOk returns a tuple with the CurrentDebit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentDebit

`func (o *TrialBalanceLinesItem) SetCurrentDebit(v float64)`

SetCurrentDebit sets CurrentDebit field to given value.

### HasCurrentDebit

`func (o *TrialBalanceLinesItem) HasCurrentDebit() bool`

HasCurrentDebit returns a boolean if a field has been set.

### GetCurrentCredit

`func (o *TrialBalanceLinesItem) GetCurrentCredit() float64`

GetCurrentCredit returns the CurrentCredit field if non-nil, zero value otherwise.

### GetCurrentCreditOk

`func (o *TrialBalanceLinesItem) GetCurrentCreditOk() (*float64, bool)`

GetCurrentCreditOk returns a tuple with the CurrentCredit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentCredit

`func (o *TrialBalanceLinesItem) SetCurrentCredit(v float64)`

SetCurrentCredit sets CurrentCredit field to given value.

### HasCurrentCredit

`func (o *TrialBalanceLinesItem) HasCurrentCredit() bool`

HasCurrentCredit returns a boolean if a field has been set.

### GetCurrentBalance

`func (o *TrialBalanceLinesItem) GetCurrentBalance() float64`

GetCurrentBalance returns the CurrentBalance field if non-nil, zero value otherwise.

### GetCurrentBalanceOk

`func (o *TrialBalanceLinesItem) GetCurrentBalanceOk() (*float64, bool)`

GetCurrentBalanceOk returns a tuple with the CurrentBalance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentBalance

`func (o *TrialBalanceLinesItem) SetCurrentBalance(v float64)`

SetCurrentBalance sets CurrentBalance field to given value.

### HasCurrentBalance

`func (o *TrialBalanceLinesItem) HasCurrentBalance() bool`

HasCurrentBalance returns a boolean if a field has been set.

### GetYtdDebit

`func (o *TrialBalanceLinesItem) GetYtdDebit() float64`

GetYtdDebit returns the YtdDebit field if non-nil, zero value otherwise.

### GetYtdDebitOk

`func (o *TrialBalanceLinesItem) GetYtdDebitOk() (*float64, bool)`

GetYtdDebitOk returns a tuple with the YtdDebit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYtdDebit

`func (o *TrialBalanceLinesItem) SetYtdDebit(v float64)`

SetYtdDebit sets YtdDebit field to given value.

### HasYtdDebit

`func (o *TrialBalanceLinesItem) HasYtdDebit() bool`

HasYtdDebit returns a boolean if a field has been set.

### GetYtdCredit

`func (o *TrialBalanceLinesItem) GetYtdCredit() float64`

GetYtdCredit returns the YtdCredit field if non-nil, zero value otherwise.

### GetYtdCreditOk

`func (o *TrialBalanceLinesItem) GetYtdCreditOk() (*float64, bool)`

GetYtdCreditOk returns a tuple with the YtdCredit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYtdCredit

`func (o *TrialBalanceLinesItem) SetYtdCredit(v float64)`

SetYtdCredit sets YtdCredit field to given value.

### HasYtdCredit

`func (o *TrialBalanceLinesItem) HasYtdCredit() bool`

HasYtdCredit returns a boolean if a field has been set.

### GetYtdBalance

`func (o *TrialBalanceLinesItem) GetYtdBalance() float64`

GetYtdBalance returns the YtdBalance field if non-nil, zero value otherwise.

### GetYtdBalanceOk

`func (o *TrialBalanceLinesItem) GetYtdBalanceOk() (*float64, bool)`

GetYtdBalanceOk returns a tuple with the YtdBalance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYtdBalance

`func (o *TrialBalanceLinesItem) SetYtdBalance(v float64)`

SetYtdBalance sets YtdBalance field to given value.

### HasYtdBalance

`func (o *TrialBalanceLinesItem) HasYtdBalance() bool`

HasYtdBalance returns a boolean if a field has been set.

### GetStatutoryName

`func (o *TrialBalanceLinesItem) GetStatutoryName() string`

GetStatutoryName returns the StatutoryName field if non-nil, zero value otherwise.

### GetStatutoryNameOk

`func (o *TrialBalanceLinesItem) GetStatutoryNameOk() (*string, bool)`

GetStatutoryNameOk returns a tuple with the StatutoryName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatutoryName

`func (o *TrialBalanceLinesItem) SetStatutoryName(v string)`

SetStatutoryName sets StatutoryName field to given value.

### HasStatutoryName

`func (o *TrialBalanceLinesItem) HasStatutoryName() bool`

HasStatutoryName returns a boolean if a field has been set.

### GetStatutoryNumber

`func (o *TrialBalanceLinesItem) GetStatutoryNumber() string`

GetStatutoryNumber returns the StatutoryNumber field if non-nil, zero value otherwise.

### GetStatutoryNumberOk

`func (o *TrialBalanceLinesItem) GetStatutoryNumberOk() (*string, bool)`

GetStatutoryNumberOk returns a tuple with the StatutoryNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatutoryNumber

`func (o *TrialBalanceLinesItem) SetStatutoryNumber(v string)`

SetStatutoryNumber sets StatutoryNumber field to given value.

### HasStatutoryNumber

`func (o *TrialBalanceLinesItem) HasStatutoryNumber() bool`

HasStatutoryNumber returns a boolean if a field has been set.

### GetPeriodDisplay

`func (o *TrialBalanceLinesItem) GetPeriodDisplay() string`

GetPeriodDisplay returns the PeriodDisplay field if non-nil, zero value otherwise.

### GetPeriodDisplayOk

`func (o *TrialBalanceLinesItem) GetPeriodDisplayOk() (*string, bool)`

GetPeriodDisplayOk returns a tuple with the PeriodDisplay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriodDisplay

`func (o *TrialBalanceLinesItem) SetPeriodDisplay(v string)`

SetPeriodDisplay sets PeriodDisplay field to given value.

### HasPeriodDisplay

`func (o *TrialBalanceLinesItem) HasPeriodDisplay() bool`

HasPeriodDisplay returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


