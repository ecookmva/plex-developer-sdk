# AccountsReceivableDepositsApiListARDepositsItem

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

### NewAccountsReceivableDepositsApiListARDepositsItem

`func NewAccountsReceivableDepositsApiListARDepositsItem() *AccountsReceivableDepositsApiListARDepositsItem`

NewAccountsReceivableDepositsApiListARDepositsItem instantiates a new AccountsReceivableDepositsApiListARDepositsItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccountsReceivableDepositsApiListARDepositsItemWithDefaults

`func NewAccountsReceivableDepositsApiListARDepositsItemWithDefaults() *AccountsReceivableDepositsApiListARDepositsItem`

NewAccountsReceivableDepositsApiListARDepositsItemWithDefaults instantiates a new AccountsReceivableDepositsApiListARDepositsItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AccountsReceivableDepositsApiListARDepositsItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AccountsReceivableDepositsApiListARDepositsItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AccountsReceivableDepositsApiListARDepositsItem) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *AccountsReceivableDepositsApiListARDepositsItem) HasId() bool`

HasId returns a boolean if a field has been set.

### GetDepositNumber

`func (o *AccountsReceivableDepositsApiListARDepositsItem) GetDepositNumber() string`

GetDepositNumber returns the DepositNumber field if non-nil, zero value otherwise.

### GetDepositNumberOk

`func (o *AccountsReceivableDepositsApiListARDepositsItem) GetDepositNumberOk() (*string, bool)`

GetDepositNumberOk returns a tuple with the DepositNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDepositNumber

`func (o *AccountsReceivableDepositsApiListARDepositsItem) SetDepositNumber(v string)`

SetDepositNumber sets DepositNumber field to given value.

### HasDepositNumber

`func (o *AccountsReceivableDepositsApiListARDepositsItem) HasDepositNumber() bool`

HasDepositNumber returns a boolean if a field has been set.

### GetAmount

`func (o *AccountsReceivableDepositsApiListARDepositsItem) GetAmount() float64`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *AccountsReceivableDepositsApiListARDepositsItem) GetAmountOk() (*float64, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *AccountsReceivableDepositsApiListARDepositsItem) SetAmount(v float64)`

SetAmount sets Amount field to given value.

### HasAmount

`func (o *AccountsReceivableDepositsApiListARDepositsItem) HasAmount() bool`

HasAmount returns a boolean if a field has been set.

### GetPeriodDisplay

`func (o *AccountsReceivableDepositsApiListARDepositsItem) GetPeriodDisplay() string`

GetPeriodDisplay returns the PeriodDisplay field if non-nil, zero value otherwise.

### GetPeriodDisplayOk

`func (o *AccountsReceivableDepositsApiListARDepositsItem) GetPeriodDisplayOk() (*string, bool)`

GetPeriodDisplayOk returns a tuple with the PeriodDisplay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriodDisplay

`func (o *AccountsReceivableDepositsApiListARDepositsItem) SetPeriodDisplay(v string)`

SetPeriodDisplay sets PeriodDisplay field to given value.

### HasPeriodDisplay

`func (o *AccountsReceivableDepositsApiListARDepositsItem) HasPeriodDisplay() bool`

HasPeriodDisplay returns a boolean if a field has been set.

### GetTransactionDate

`func (o *AccountsReceivableDepositsApiListARDepositsItem) GetTransactionDate() time.Time`

GetTransactionDate returns the TransactionDate field if non-nil, zero value otherwise.

### GetTransactionDateOk

`func (o *AccountsReceivableDepositsApiListARDepositsItem) GetTransactionDateOk() (*time.Time, bool)`

GetTransactionDateOk returns a tuple with the TransactionDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransactionDate

`func (o *AccountsReceivableDepositsApiListARDepositsItem) SetTransactionDate(v time.Time)`

SetTransactionDate sets TransactionDate field to given value.

### HasTransactionDate

`func (o *AccountsReceivableDepositsApiListARDepositsItem) HasTransactionDate() bool`

HasTransactionDate returns a boolean if a field has been set.

### GetCurrencyCode

`func (o *AccountsReceivableDepositsApiListARDepositsItem) GetCurrencyCode() string`

GetCurrencyCode returns the CurrencyCode field if non-nil, zero value otherwise.

### GetCurrencyCodeOk

`func (o *AccountsReceivableDepositsApiListARDepositsItem) GetCurrencyCodeOk() (*string, bool)`

GetCurrencyCodeOk returns a tuple with the CurrencyCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyCode

`func (o *AccountsReceivableDepositsApiListARDepositsItem) SetCurrencyCode(v string)`

SetCurrencyCode sets CurrencyCode field to given value.

### HasCurrencyCode

`func (o *AccountsReceivableDepositsApiListARDepositsItem) HasCurrencyCode() bool`

HasCurrencyCode returns a boolean if a field has been set.

### GetExchangeRate

`func (o *AccountsReceivableDepositsApiListARDepositsItem) GetExchangeRate() float64`

GetExchangeRate returns the ExchangeRate field if non-nil, zero value otherwise.

### GetExchangeRateOk

`func (o *AccountsReceivableDepositsApiListARDepositsItem) GetExchangeRateOk() (*float64, bool)`

GetExchangeRateOk returns a tuple with the ExchangeRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExchangeRate

`func (o *AccountsReceivableDepositsApiListARDepositsItem) SetExchangeRate(v float64)`

SetExchangeRate sets ExchangeRate field to given value.

### HasExchangeRate

`func (o *AccountsReceivableDepositsApiListARDepositsItem) HasExchangeRate() bool`

HasExchangeRate returns a boolean if a field has been set.

### GetInternalNote

`func (o *AccountsReceivableDepositsApiListARDepositsItem) GetInternalNote() string`

GetInternalNote returns the InternalNote field if non-nil, zero value otherwise.

### GetInternalNoteOk

`func (o *AccountsReceivableDepositsApiListARDepositsItem) GetInternalNoteOk() (*string, bool)`

GetInternalNoteOk returns a tuple with the InternalNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInternalNote

`func (o *AccountsReceivableDepositsApiListARDepositsItem) SetInternalNote(v string)`

SetInternalNote sets InternalNote field to given value.

### HasInternalNote

`func (o *AccountsReceivableDepositsApiListARDepositsItem) HasInternalNote() bool`

HasInternalNote returns a boolean if a field has been set.

### GetCreatedById

`func (o *AccountsReceivableDepositsApiListARDepositsItem) GetCreatedById() string`

GetCreatedById returns the CreatedById field if non-nil, zero value otherwise.

### GetCreatedByIdOk

`func (o *AccountsReceivableDepositsApiListARDepositsItem) GetCreatedByIdOk() (*string, bool)`

GetCreatedByIdOk returns a tuple with the CreatedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedById

`func (o *AccountsReceivableDepositsApiListARDepositsItem) SetCreatedById(v string)`

SetCreatedById sets CreatedById field to given value.

### HasCreatedById

`func (o *AccountsReceivableDepositsApiListARDepositsItem) HasCreatedById() bool`

HasCreatedById returns a boolean if a field has been set.

### GetCreatedDate

`func (o *AccountsReceivableDepositsApiListARDepositsItem) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *AccountsReceivableDepositsApiListARDepositsItem) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *AccountsReceivableDepositsApiListARDepositsItem) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *AccountsReceivableDepositsApiListARDepositsItem) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.

### GetDepositCurrencyAmount

`func (o *AccountsReceivableDepositsApiListARDepositsItem) GetDepositCurrencyAmount() float64`

GetDepositCurrencyAmount returns the DepositCurrencyAmount field if non-nil, zero value otherwise.

### GetDepositCurrencyAmountOk

`func (o *AccountsReceivableDepositsApiListARDepositsItem) GetDepositCurrencyAmountOk() (*float64, bool)`

GetDepositCurrencyAmountOk returns a tuple with the DepositCurrencyAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDepositCurrencyAmount

`func (o *AccountsReceivableDepositsApiListARDepositsItem) SetDepositCurrencyAmount(v float64)`

SetDepositCurrencyAmount sets DepositCurrencyAmount field to given value.

### HasDepositCurrencyAmount

`func (o *AccountsReceivableDepositsApiListARDepositsItem) HasDepositCurrencyAmount() bool`

HasDepositCurrencyAmount returns a boolean if a field has been set.

### GetCleared

`func (o *AccountsReceivableDepositsApiListARDepositsItem) GetCleared() string`

GetCleared returns the Cleared field if non-nil, zero value otherwise.

### GetClearedOk

`func (o *AccountsReceivableDepositsApiListARDepositsItem) GetClearedOk() (*string, bool)`

GetClearedOk returns a tuple with the Cleared field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCleared

`func (o *AccountsReceivableDepositsApiListARDepositsItem) SetCleared(v string)`

SetCleared sets Cleared field to given value.

### HasCleared

`func (o *AccountsReceivableDepositsApiListARDepositsItem) HasCleared() bool`

HasCleared returns a boolean if a field has been set.

### GetClearDate

`func (o *AccountsReceivableDepositsApiListARDepositsItem) GetClearDate() time.Time`

GetClearDate returns the ClearDate field if non-nil, zero value otherwise.

### GetClearDateOk

`func (o *AccountsReceivableDepositsApiListARDepositsItem) GetClearDateOk() (*time.Time, bool)`

GetClearDateOk returns a tuple with the ClearDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClearDate

`func (o *AccountsReceivableDepositsApiListARDepositsItem) SetClearDate(v time.Time)`

SetClearDate sets ClearDate field to given value.

### HasClearDate

`func (o *AccountsReceivableDepositsApiListARDepositsItem) HasClearDate() bool`

HasClearDate returns a boolean if a field has been set.

### GetClearPeriod

`func (o *AccountsReceivableDepositsApiListARDepositsItem) GetClearPeriod() string`

GetClearPeriod returns the ClearPeriod field if non-nil, zero value otherwise.

### GetClearPeriodOk

`func (o *AccountsReceivableDepositsApiListARDepositsItem) GetClearPeriodOk() (*string, bool)`

GetClearPeriodOk returns a tuple with the ClearPeriod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClearPeriod

`func (o *AccountsReceivableDepositsApiListARDepositsItem) SetClearPeriod(v string)`

SetClearPeriod sets ClearPeriod field to given value.

### HasClearPeriod

`func (o *AccountsReceivableDepositsApiListARDepositsItem) HasClearPeriod() bool`

HasClearPeriod returns a boolean if a field has been set.

### GetModifiedById

`func (o *AccountsReceivableDepositsApiListARDepositsItem) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *AccountsReceivableDepositsApiListARDepositsItem) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *AccountsReceivableDepositsApiListARDepositsItem) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *AccountsReceivableDepositsApiListARDepositsItem) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetModifiedDate

`func (o *AccountsReceivableDepositsApiListARDepositsItem) GetModifiedDate() time.Time`

GetModifiedDate returns the ModifiedDate field if non-nil, zero value otherwise.

### GetModifiedDateOk

`func (o *AccountsReceivableDepositsApiListARDepositsItem) GetModifiedDateOk() (*time.Time, bool)`

GetModifiedDateOk returns a tuple with the ModifiedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDate

`func (o *AccountsReceivableDepositsApiListARDepositsItem) SetModifiedDate(v time.Time)`

SetModifiedDate sets ModifiedDate field to given value.

### HasModifiedDate

`func (o *AccountsReceivableDepositsApiListARDepositsItem) HasModifiedDate() bool`

HasModifiedDate returns a boolean if a field has been set.

### GetVoucherNumber

`func (o *AccountsReceivableDepositsApiListARDepositsItem) GetVoucherNumber() string`

GetVoucherNumber returns the VoucherNumber field if non-nil, zero value otherwise.

### GetVoucherNumberOk

`func (o *AccountsReceivableDepositsApiListARDepositsItem) GetVoucherNumberOk() (*string, bool)`

GetVoucherNumberOk returns a tuple with the VoucherNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoucherNumber

`func (o *AccountsReceivableDepositsApiListARDepositsItem) SetVoucherNumber(v string)`

SetVoucherNumber sets VoucherNumber field to given value.

### HasVoucherNumber

`func (o *AccountsReceivableDepositsApiListARDepositsItem) HasVoucherNumber() bool`

HasVoucherNumber returns a boolean if a field has been set.

### GetClearedAmount

`func (o *AccountsReceivableDepositsApiListARDepositsItem) GetClearedAmount() float64`

GetClearedAmount returns the ClearedAmount field if non-nil, zero value otherwise.

### GetClearedAmountOk

`func (o *AccountsReceivableDepositsApiListARDepositsItem) GetClearedAmountOk() (*float64, bool)`

GetClearedAmountOk returns a tuple with the ClearedAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClearedAmount

`func (o *AccountsReceivableDepositsApiListARDepositsItem) SetClearedAmount(v float64)`

SetClearedAmount sets ClearedAmount field to given value.

### HasClearedAmount

`func (o *AccountsReceivableDepositsApiListARDepositsItem) HasClearedAmount() bool`

HasClearedAmount returns a boolean if a field has been set.

### GetBooked

`func (o *AccountsReceivableDepositsApiListARDepositsItem) GetBooked() bool`

GetBooked returns the Booked field if non-nil, zero value otherwise.

### GetBookedOk

`func (o *AccountsReceivableDepositsApiListARDepositsItem) GetBookedOk() (*bool, bool)`

GetBookedOk returns a tuple with the Booked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBooked

`func (o *AccountsReceivableDepositsApiListARDepositsItem) SetBooked(v bool)`

SetBooked sets Booked field to given value.

### HasBooked

`func (o *AccountsReceivableDepositsApiListARDepositsItem) HasBooked() bool`

HasBooked returns a boolean if a field has been set.

### GetLines

`func (o *AccountsReceivableDepositsApiListARDepositsItem) GetLines() []LinesItem4`

GetLines returns the Lines field if non-nil, zero value otherwise.

### GetLinesOk

`func (o *AccountsReceivableDepositsApiListARDepositsItem) GetLinesOk() (*[]LinesItem4, bool)`

GetLinesOk returns a tuple with the Lines field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLines

`func (o *AccountsReceivableDepositsApiListARDepositsItem) SetLines(v []LinesItem4)`

SetLines sets Lines field to given value.

### HasLines

`func (o *AccountsReceivableDepositsApiListARDepositsItem) HasLines() bool`

HasLines returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


