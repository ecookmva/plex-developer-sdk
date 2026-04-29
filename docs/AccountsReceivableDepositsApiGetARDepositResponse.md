# AccountsReceivableDepositsApiGetARDepositResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | The ID of the AR deposit. | [optional] 
**DepositNumber** | Pointer to **string** | The AR deposit number. | [optional] 
**Amount** | Pointer to **float64** | The AR deposit amount. | [optional] 
**PeriodDisplay** | Pointer to **string** | List of AR deposit records during a period. | [optional] 
**TransactionDate** | Pointer to **time.Time** | The date on which an AR deposit was recorded. | [optional] 
**CurrencyCode** | Pointer to **string** | The AR deposit currency code. | [optional] 
**ExchangeRate** | Pointer to **float64** | The AR deposit exchange rate. | [optional] 
**InternalNote** | Pointer to **string** | Internal note added to an AR deposit. | [optional] 
**CreatedById** | Pointer to **string** | The ID of the user who created the record. | [optional] 
**CreatedDate** | Pointer to **time.Time** | The date on which an AR deposit was created. | [optional] 
**DepositCurrencyAmount** | Pointer to **float64** | AR deposit currency amount. | [optional] 
**Cleared** | Pointer to **string** | Specify an AR deposit has cleared. Uncleared - the transaction is not part of a bank reconciliation Pending - the transaction is part of a saved bank reconciliation that has not yet been finalized Cleared - the transaction is part of a finalized bank reconciliation and has cleared the relevant bank account | [optional] 
**ClearDate** | Pointer to **time.Time** | The date on which an AR deposit cleared. | [optional] 
**ClearPeriod** | Pointer to **string** | The period in which an AR deposit cleared. | [optional] 
**ModifiedById** | Pointer to **string** | The ID of the user who last modified the record. | [optional] 
**ModifiedDate** | Pointer to **time.Time** | The date on which an AR deposit was modified. | [optional] 
**VoucherNumber** | Pointer to **string** | The AR deposit voucher number. | [optional] 
**ClearedAmount** | Pointer to **float64** | The cleared amount of the AR deposit. | [optional] 
**Booked** | Pointer to **bool** | Specify AR deposit booked status. | [optional] 
**Lines** | Pointer to [**[]LinesItem4**](LinesItem4.md) | List of AR Deposit lines | [optional] 

## Methods

### NewAccountsReceivableDepositsApiGetARDepositResponse

`func NewAccountsReceivableDepositsApiGetARDepositResponse() *AccountsReceivableDepositsApiGetARDepositResponse`

NewAccountsReceivableDepositsApiGetARDepositResponse instantiates a new AccountsReceivableDepositsApiGetARDepositResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccountsReceivableDepositsApiGetARDepositResponseWithDefaults

`func NewAccountsReceivableDepositsApiGetARDepositResponseWithDefaults() *AccountsReceivableDepositsApiGetARDepositResponse`

NewAccountsReceivableDepositsApiGetARDepositResponseWithDefaults instantiates a new AccountsReceivableDepositsApiGetARDepositResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetDepositNumber

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) GetDepositNumber() string`

GetDepositNumber returns the DepositNumber field if non-nil, zero value otherwise.

### GetDepositNumberOk

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) GetDepositNumberOk() (*string, bool)`

GetDepositNumberOk returns a tuple with the DepositNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDepositNumber

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) SetDepositNumber(v string)`

SetDepositNumber sets DepositNumber field to given value.

### HasDepositNumber

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) HasDepositNumber() bool`

HasDepositNumber returns a boolean if a field has been set.

### GetAmount

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) GetAmount() float64`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) GetAmountOk() (*float64, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) SetAmount(v float64)`

SetAmount sets Amount field to given value.

### HasAmount

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) HasAmount() bool`

HasAmount returns a boolean if a field has been set.

### GetPeriodDisplay

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) GetPeriodDisplay() string`

GetPeriodDisplay returns the PeriodDisplay field if non-nil, zero value otherwise.

### GetPeriodDisplayOk

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) GetPeriodDisplayOk() (*string, bool)`

GetPeriodDisplayOk returns a tuple with the PeriodDisplay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriodDisplay

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) SetPeriodDisplay(v string)`

SetPeriodDisplay sets PeriodDisplay field to given value.

### HasPeriodDisplay

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) HasPeriodDisplay() bool`

HasPeriodDisplay returns a boolean if a field has been set.

### GetTransactionDate

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) GetTransactionDate() time.Time`

GetTransactionDate returns the TransactionDate field if non-nil, zero value otherwise.

### GetTransactionDateOk

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) GetTransactionDateOk() (*time.Time, bool)`

GetTransactionDateOk returns a tuple with the TransactionDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransactionDate

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) SetTransactionDate(v time.Time)`

SetTransactionDate sets TransactionDate field to given value.

### HasTransactionDate

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) HasTransactionDate() bool`

HasTransactionDate returns a boolean if a field has been set.

### GetCurrencyCode

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) GetCurrencyCode() string`

GetCurrencyCode returns the CurrencyCode field if non-nil, zero value otherwise.

### GetCurrencyCodeOk

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) GetCurrencyCodeOk() (*string, bool)`

GetCurrencyCodeOk returns a tuple with the CurrencyCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyCode

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) SetCurrencyCode(v string)`

SetCurrencyCode sets CurrencyCode field to given value.

### HasCurrencyCode

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) HasCurrencyCode() bool`

HasCurrencyCode returns a boolean if a field has been set.

### GetExchangeRate

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) GetExchangeRate() float64`

GetExchangeRate returns the ExchangeRate field if non-nil, zero value otherwise.

### GetExchangeRateOk

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) GetExchangeRateOk() (*float64, bool)`

GetExchangeRateOk returns a tuple with the ExchangeRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExchangeRate

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) SetExchangeRate(v float64)`

SetExchangeRate sets ExchangeRate field to given value.

### HasExchangeRate

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) HasExchangeRate() bool`

HasExchangeRate returns a boolean if a field has been set.

### GetInternalNote

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) GetInternalNote() string`

GetInternalNote returns the InternalNote field if non-nil, zero value otherwise.

### GetInternalNoteOk

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) GetInternalNoteOk() (*string, bool)`

GetInternalNoteOk returns a tuple with the InternalNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInternalNote

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) SetInternalNote(v string)`

SetInternalNote sets InternalNote field to given value.

### HasInternalNote

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) HasInternalNote() bool`

HasInternalNote returns a boolean if a field has been set.

### GetCreatedById

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) GetCreatedById() string`

GetCreatedById returns the CreatedById field if non-nil, zero value otherwise.

### GetCreatedByIdOk

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) GetCreatedByIdOk() (*string, bool)`

GetCreatedByIdOk returns a tuple with the CreatedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedById

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) SetCreatedById(v string)`

SetCreatedById sets CreatedById field to given value.

### HasCreatedById

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) HasCreatedById() bool`

HasCreatedById returns a boolean if a field has been set.

### GetCreatedDate

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.

### GetDepositCurrencyAmount

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) GetDepositCurrencyAmount() float64`

GetDepositCurrencyAmount returns the DepositCurrencyAmount field if non-nil, zero value otherwise.

### GetDepositCurrencyAmountOk

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) GetDepositCurrencyAmountOk() (*float64, bool)`

GetDepositCurrencyAmountOk returns a tuple with the DepositCurrencyAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDepositCurrencyAmount

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) SetDepositCurrencyAmount(v float64)`

SetDepositCurrencyAmount sets DepositCurrencyAmount field to given value.

### HasDepositCurrencyAmount

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) HasDepositCurrencyAmount() bool`

HasDepositCurrencyAmount returns a boolean if a field has been set.

### GetCleared

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) GetCleared() string`

GetCleared returns the Cleared field if non-nil, zero value otherwise.

### GetClearedOk

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) GetClearedOk() (*string, bool)`

GetClearedOk returns a tuple with the Cleared field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCleared

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) SetCleared(v string)`

SetCleared sets Cleared field to given value.

### HasCleared

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) HasCleared() bool`

HasCleared returns a boolean if a field has been set.

### GetClearDate

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) GetClearDate() time.Time`

GetClearDate returns the ClearDate field if non-nil, zero value otherwise.

### GetClearDateOk

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) GetClearDateOk() (*time.Time, bool)`

GetClearDateOk returns a tuple with the ClearDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClearDate

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) SetClearDate(v time.Time)`

SetClearDate sets ClearDate field to given value.

### HasClearDate

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) HasClearDate() bool`

HasClearDate returns a boolean if a field has been set.

### GetClearPeriod

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) GetClearPeriod() string`

GetClearPeriod returns the ClearPeriod field if non-nil, zero value otherwise.

### GetClearPeriodOk

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) GetClearPeriodOk() (*string, bool)`

GetClearPeriodOk returns a tuple with the ClearPeriod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClearPeriod

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) SetClearPeriod(v string)`

SetClearPeriod sets ClearPeriod field to given value.

### HasClearPeriod

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) HasClearPeriod() bool`

HasClearPeriod returns a boolean if a field has been set.

### GetModifiedById

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetModifiedDate

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) GetModifiedDate() time.Time`

GetModifiedDate returns the ModifiedDate field if non-nil, zero value otherwise.

### GetModifiedDateOk

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) GetModifiedDateOk() (*time.Time, bool)`

GetModifiedDateOk returns a tuple with the ModifiedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDate

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) SetModifiedDate(v time.Time)`

SetModifiedDate sets ModifiedDate field to given value.

### HasModifiedDate

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) HasModifiedDate() bool`

HasModifiedDate returns a boolean if a field has been set.

### GetVoucherNumber

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) GetVoucherNumber() string`

GetVoucherNumber returns the VoucherNumber field if non-nil, zero value otherwise.

### GetVoucherNumberOk

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) GetVoucherNumberOk() (*string, bool)`

GetVoucherNumberOk returns a tuple with the VoucherNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoucherNumber

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) SetVoucherNumber(v string)`

SetVoucherNumber sets VoucherNumber field to given value.

### HasVoucherNumber

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) HasVoucherNumber() bool`

HasVoucherNumber returns a boolean if a field has been set.

### GetClearedAmount

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) GetClearedAmount() float64`

GetClearedAmount returns the ClearedAmount field if non-nil, zero value otherwise.

### GetClearedAmountOk

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) GetClearedAmountOk() (*float64, bool)`

GetClearedAmountOk returns a tuple with the ClearedAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClearedAmount

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) SetClearedAmount(v float64)`

SetClearedAmount sets ClearedAmount field to given value.

### HasClearedAmount

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) HasClearedAmount() bool`

HasClearedAmount returns a boolean if a field has been set.

### GetBooked

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) GetBooked() bool`

GetBooked returns the Booked field if non-nil, zero value otherwise.

### GetBookedOk

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) GetBookedOk() (*bool, bool)`

GetBookedOk returns a tuple with the Booked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBooked

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) SetBooked(v bool)`

SetBooked sets Booked field to given value.

### HasBooked

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) HasBooked() bool`

HasBooked returns a boolean if a field has been set.

### GetLines

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) GetLines() []LinesItem4`

GetLines returns the Lines field if non-nil, zero value otherwise.

### GetLinesOk

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) GetLinesOk() (*[]LinesItem4, bool)`

GetLinesOk returns a tuple with the Lines field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLines

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) SetLines(v []LinesItem4)`

SetLines sets Lines field to given value.

### HasLines

`func (o *AccountsReceivableDepositsApiGetARDepositResponse) HasLines() bool`

HasLines returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


