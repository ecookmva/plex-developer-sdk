# AccountsPayablePaymentsApiListAPPaymentsItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | The ID of the AP payment. | [optional] 
**PaymentNumber** | Pointer to **string** | The AP payment number. | [optional] 
**SupplierId** | Pointer to **string** | The ID of the AP supplier. | [optional] 
**SupplierCode** | Pointer to **string** | The AP supplier code. | [optional] 
**Amount** | Pointer to **float64** | AP payment amount. | [optional] 
**PeriodDisplay** | Pointer to **string** | The period in which an AP payment is recorded. | [optional] 
**TransactionDate** | Pointer to **time.Time** | The date on which an AP payment transaction was recorded. | [optional] 
**Note** | Pointer to **string** | Note added to an AP payment. | [optional] 
**CreatedById** | Pointer to **string** | The ID of the user who created the record. | [optional] 
**CreatedDate** | Pointer to **time.Time** | The date on which an AP payment was created. | [optional] 
**ModifiedById** | Pointer to **string** | The ID of the user who last modified the record. | [optional] 
**ModifiedDate** | Pointer to **time.Time** | The date on which an AP payment was modified. | [optional] 
**PaymentType** | Pointer to **string** | AP Payment Type. | [optional] 
**Status** | Pointer to **string** | AP payment status. | [optional] 
**CheckDate** | Pointer to **time.Time** | Date the AP payment check was issued. | [optional] 
**Booked** | Pointer to **bool** | Specify AP payment is booked. | [optional] 
**Cleared** | Pointer to **string** | Specify AP payment has cleared. Uncleared - the transaction is not part of a bank reconciliation Pending - the transaction is part of a saved bank reconciliation that has not yet been finalized Cleared - the transaction is part of a finalized bank reconciliation and has cleared the relevant bank account | [optional] 
**ClearDate** | Pointer to **time.Time** | Date the AP payment cleared. | [optional] 
**ClearPeriod** | Pointer to **string** | Period in which the AP payment cleared. | [optional] 
**ClearedAmount** | Pointer to **float64** | AP payment cleared amount. | [optional] 
**Void** | Pointer to **bool** | Specify AP payment has been voided. | [optional] 
**VoucherNo** | Pointer to **string** | AP payment voucher number. | [optional] 
**CheckNote** | Pointer to **string** | Note added to an AP payment check. | [optional] 
**MailedDate** | Pointer to **time.Time** | Date on which AP payment check was mailed. | [optional] 
**ExchangeRate** | Pointer to **float64** | AP payment exchange rate. | [optional] 
**CurrencyCode** | Pointer to **string** | AP payment currency code. | [optional] 
**Lines** | Pointer to [**[]LinesItem3**](LinesItem3.md) | List of AP Payment lines | [optional] 

## Methods

### NewAccountsPayablePaymentsApiListAPPaymentsItem

`func NewAccountsPayablePaymentsApiListAPPaymentsItem() *AccountsPayablePaymentsApiListAPPaymentsItem`

NewAccountsPayablePaymentsApiListAPPaymentsItem instantiates a new AccountsPayablePaymentsApiListAPPaymentsItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccountsPayablePaymentsApiListAPPaymentsItemWithDefaults

`func NewAccountsPayablePaymentsApiListAPPaymentsItemWithDefaults() *AccountsPayablePaymentsApiListAPPaymentsItem`

NewAccountsPayablePaymentsApiListAPPaymentsItemWithDefaults instantiates a new AccountsPayablePaymentsApiListAPPaymentsItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) HasId() bool`

HasId returns a boolean if a field has been set.

### GetPaymentNumber

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetPaymentNumber() string`

GetPaymentNumber returns the PaymentNumber field if non-nil, zero value otherwise.

### GetPaymentNumberOk

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetPaymentNumberOk() (*string, bool)`

GetPaymentNumberOk returns a tuple with the PaymentNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentNumber

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) SetPaymentNumber(v string)`

SetPaymentNumber sets PaymentNumber field to given value.

### HasPaymentNumber

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) HasPaymentNumber() bool`

HasPaymentNumber returns a boolean if a field has been set.

### GetSupplierId

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetSupplierId() string`

GetSupplierId returns the SupplierId field if non-nil, zero value otherwise.

### GetSupplierIdOk

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetSupplierIdOk() (*string, bool)`

GetSupplierIdOk returns a tuple with the SupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierId

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) SetSupplierId(v string)`

SetSupplierId sets SupplierId field to given value.

### HasSupplierId

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) HasSupplierId() bool`

HasSupplierId returns a boolean if a field has been set.

### GetSupplierCode

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetSupplierCode() string`

GetSupplierCode returns the SupplierCode field if non-nil, zero value otherwise.

### GetSupplierCodeOk

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetSupplierCodeOk() (*string, bool)`

GetSupplierCodeOk returns a tuple with the SupplierCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierCode

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) SetSupplierCode(v string)`

SetSupplierCode sets SupplierCode field to given value.

### HasSupplierCode

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) HasSupplierCode() bool`

HasSupplierCode returns a boolean if a field has been set.

### GetAmount

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetAmount() float64`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetAmountOk() (*float64, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) SetAmount(v float64)`

SetAmount sets Amount field to given value.

### HasAmount

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) HasAmount() bool`

HasAmount returns a boolean if a field has been set.

### GetPeriodDisplay

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetPeriodDisplay() string`

GetPeriodDisplay returns the PeriodDisplay field if non-nil, zero value otherwise.

### GetPeriodDisplayOk

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetPeriodDisplayOk() (*string, bool)`

GetPeriodDisplayOk returns a tuple with the PeriodDisplay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriodDisplay

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) SetPeriodDisplay(v string)`

SetPeriodDisplay sets PeriodDisplay field to given value.

### HasPeriodDisplay

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) HasPeriodDisplay() bool`

HasPeriodDisplay returns a boolean if a field has been set.

### GetTransactionDate

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetTransactionDate() time.Time`

GetTransactionDate returns the TransactionDate field if non-nil, zero value otherwise.

### GetTransactionDateOk

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetTransactionDateOk() (*time.Time, bool)`

GetTransactionDateOk returns a tuple with the TransactionDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransactionDate

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) SetTransactionDate(v time.Time)`

SetTransactionDate sets TransactionDate field to given value.

### HasTransactionDate

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) HasTransactionDate() bool`

HasTransactionDate returns a boolean if a field has been set.

### GetNote

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetCreatedById

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetCreatedById() string`

GetCreatedById returns the CreatedById field if non-nil, zero value otherwise.

### GetCreatedByIdOk

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetCreatedByIdOk() (*string, bool)`

GetCreatedByIdOk returns a tuple with the CreatedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedById

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) SetCreatedById(v string)`

SetCreatedById sets CreatedById field to given value.

### HasCreatedById

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) HasCreatedById() bool`

HasCreatedById returns a boolean if a field has been set.

### GetCreatedDate

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.

### GetModifiedById

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetModifiedDate

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetModifiedDate() time.Time`

GetModifiedDate returns the ModifiedDate field if non-nil, zero value otherwise.

### GetModifiedDateOk

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetModifiedDateOk() (*time.Time, bool)`

GetModifiedDateOk returns a tuple with the ModifiedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDate

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) SetModifiedDate(v time.Time)`

SetModifiedDate sets ModifiedDate field to given value.

### HasModifiedDate

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) HasModifiedDate() bool`

HasModifiedDate returns a boolean if a field has been set.

### GetPaymentType

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetPaymentType() string`

GetPaymentType returns the PaymentType field if non-nil, zero value otherwise.

### GetPaymentTypeOk

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetPaymentTypeOk() (*string, bool)`

GetPaymentTypeOk returns a tuple with the PaymentType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentType

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) SetPaymentType(v string)`

SetPaymentType sets PaymentType field to given value.

### HasPaymentType

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) HasPaymentType() bool`

HasPaymentType returns a boolean if a field has been set.

### GetStatus

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetCheckDate

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetCheckDate() time.Time`

GetCheckDate returns the CheckDate field if non-nil, zero value otherwise.

### GetCheckDateOk

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetCheckDateOk() (*time.Time, bool)`

GetCheckDateOk returns a tuple with the CheckDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckDate

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) SetCheckDate(v time.Time)`

SetCheckDate sets CheckDate field to given value.

### HasCheckDate

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) HasCheckDate() bool`

HasCheckDate returns a boolean if a field has been set.

### GetBooked

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetBooked() bool`

GetBooked returns the Booked field if non-nil, zero value otherwise.

### GetBookedOk

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetBookedOk() (*bool, bool)`

GetBookedOk returns a tuple with the Booked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBooked

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) SetBooked(v bool)`

SetBooked sets Booked field to given value.

### HasBooked

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) HasBooked() bool`

HasBooked returns a boolean if a field has been set.

### GetCleared

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetCleared() string`

GetCleared returns the Cleared field if non-nil, zero value otherwise.

### GetClearedOk

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetClearedOk() (*string, bool)`

GetClearedOk returns a tuple with the Cleared field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCleared

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) SetCleared(v string)`

SetCleared sets Cleared field to given value.

### HasCleared

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) HasCleared() bool`

HasCleared returns a boolean if a field has been set.

### GetClearDate

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetClearDate() time.Time`

GetClearDate returns the ClearDate field if non-nil, zero value otherwise.

### GetClearDateOk

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetClearDateOk() (*time.Time, bool)`

GetClearDateOk returns a tuple with the ClearDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClearDate

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) SetClearDate(v time.Time)`

SetClearDate sets ClearDate field to given value.

### HasClearDate

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) HasClearDate() bool`

HasClearDate returns a boolean if a field has been set.

### GetClearPeriod

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetClearPeriod() string`

GetClearPeriod returns the ClearPeriod field if non-nil, zero value otherwise.

### GetClearPeriodOk

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetClearPeriodOk() (*string, bool)`

GetClearPeriodOk returns a tuple with the ClearPeriod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClearPeriod

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) SetClearPeriod(v string)`

SetClearPeriod sets ClearPeriod field to given value.

### HasClearPeriod

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) HasClearPeriod() bool`

HasClearPeriod returns a boolean if a field has been set.

### GetClearedAmount

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetClearedAmount() float64`

GetClearedAmount returns the ClearedAmount field if non-nil, zero value otherwise.

### GetClearedAmountOk

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetClearedAmountOk() (*float64, bool)`

GetClearedAmountOk returns a tuple with the ClearedAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClearedAmount

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) SetClearedAmount(v float64)`

SetClearedAmount sets ClearedAmount field to given value.

### HasClearedAmount

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) HasClearedAmount() bool`

HasClearedAmount returns a boolean if a field has been set.

### GetVoid

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetVoid() bool`

GetVoid returns the Void field if non-nil, zero value otherwise.

### GetVoidOk

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetVoidOk() (*bool, bool)`

GetVoidOk returns a tuple with the Void field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoid

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) SetVoid(v bool)`

SetVoid sets Void field to given value.

### HasVoid

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) HasVoid() bool`

HasVoid returns a boolean if a field has been set.

### GetVoucherNo

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetVoucherNo() string`

GetVoucherNo returns the VoucherNo field if non-nil, zero value otherwise.

### GetVoucherNoOk

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetVoucherNoOk() (*string, bool)`

GetVoucherNoOk returns a tuple with the VoucherNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoucherNo

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) SetVoucherNo(v string)`

SetVoucherNo sets VoucherNo field to given value.

### HasVoucherNo

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) HasVoucherNo() bool`

HasVoucherNo returns a boolean if a field has been set.

### GetCheckNote

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetCheckNote() string`

GetCheckNote returns the CheckNote field if non-nil, zero value otherwise.

### GetCheckNoteOk

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetCheckNoteOk() (*string, bool)`

GetCheckNoteOk returns a tuple with the CheckNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckNote

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) SetCheckNote(v string)`

SetCheckNote sets CheckNote field to given value.

### HasCheckNote

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) HasCheckNote() bool`

HasCheckNote returns a boolean if a field has been set.

### GetMailedDate

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetMailedDate() time.Time`

GetMailedDate returns the MailedDate field if non-nil, zero value otherwise.

### GetMailedDateOk

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetMailedDateOk() (*time.Time, bool)`

GetMailedDateOk returns a tuple with the MailedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMailedDate

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) SetMailedDate(v time.Time)`

SetMailedDate sets MailedDate field to given value.

### HasMailedDate

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) HasMailedDate() bool`

HasMailedDate returns a boolean if a field has been set.

### GetExchangeRate

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetExchangeRate() float64`

GetExchangeRate returns the ExchangeRate field if non-nil, zero value otherwise.

### GetExchangeRateOk

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetExchangeRateOk() (*float64, bool)`

GetExchangeRateOk returns a tuple with the ExchangeRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExchangeRate

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) SetExchangeRate(v float64)`

SetExchangeRate sets ExchangeRate field to given value.

### HasExchangeRate

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) HasExchangeRate() bool`

HasExchangeRate returns a boolean if a field has been set.

### GetCurrencyCode

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetCurrencyCode() string`

GetCurrencyCode returns the CurrencyCode field if non-nil, zero value otherwise.

### GetCurrencyCodeOk

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetCurrencyCodeOk() (*string, bool)`

GetCurrencyCodeOk returns a tuple with the CurrencyCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyCode

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) SetCurrencyCode(v string)`

SetCurrencyCode sets CurrencyCode field to given value.

### HasCurrencyCode

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) HasCurrencyCode() bool`

HasCurrencyCode returns a boolean if a field has been set.

### GetLines

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetLines() []LinesItem3`

GetLines returns the Lines field if non-nil, zero value otherwise.

### GetLinesOk

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) GetLinesOk() (*[]LinesItem3, bool)`

GetLinesOk returns a tuple with the Lines field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLines

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) SetLines(v []LinesItem3)`

SetLines sets Lines field to given value.

### HasLines

`func (o *AccountsPayablePaymentsApiListAPPaymentsItem) HasLines() bool`

HasLines returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


