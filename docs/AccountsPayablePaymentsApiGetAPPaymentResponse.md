# AccountsPayablePaymentsApiGetAPPaymentResponse

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

### NewAccountsPayablePaymentsApiGetAPPaymentResponse

`func NewAccountsPayablePaymentsApiGetAPPaymentResponse() *AccountsPayablePaymentsApiGetAPPaymentResponse`

NewAccountsPayablePaymentsApiGetAPPaymentResponse instantiates a new AccountsPayablePaymentsApiGetAPPaymentResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccountsPayablePaymentsApiGetAPPaymentResponseWithDefaults

`func NewAccountsPayablePaymentsApiGetAPPaymentResponseWithDefaults() *AccountsPayablePaymentsApiGetAPPaymentResponse`

NewAccountsPayablePaymentsApiGetAPPaymentResponseWithDefaults instantiates a new AccountsPayablePaymentsApiGetAPPaymentResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetPaymentNumber

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetPaymentNumber() string`

GetPaymentNumber returns the PaymentNumber field if non-nil, zero value otherwise.

### GetPaymentNumberOk

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetPaymentNumberOk() (*string, bool)`

GetPaymentNumberOk returns a tuple with the PaymentNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentNumber

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) SetPaymentNumber(v string)`

SetPaymentNumber sets PaymentNumber field to given value.

### HasPaymentNumber

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) HasPaymentNumber() bool`

HasPaymentNumber returns a boolean if a field has been set.

### GetSupplierId

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetSupplierId() string`

GetSupplierId returns the SupplierId field if non-nil, zero value otherwise.

### GetSupplierIdOk

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetSupplierIdOk() (*string, bool)`

GetSupplierIdOk returns a tuple with the SupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierId

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) SetSupplierId(v string)`

SetSupplierId sets SupplierId field to given value.

### HasSupplierId

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) HasSupplierId() bool`

HasSupplierId returns a boolean if a field has been set.

### GetSupplierCode

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetSupplierCode() string`

GetSupplierCode returns the SupplierCode field if non-nil, zero value otherwise.

### GetSupplierCodeOk

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetSupplierCodeOk() (*string, bool)`

GetSupplierCodeOk returns a tuple with the SupplierCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierCode

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) SetSupplierCode(v string)`

SetSupplierCode sets SupplierCode field to given value.

### HasSupplierCode

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) HasSupplierCode() bool`

HasSupplierCode returns a boolean if a field has been set.

### GetAmount

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetAmount() float64`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetAmountOk() (*float64, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) SetAmount(v float64)`

SetAmount sets Amount field to given value.

### HasAmount

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) HasAmount() bool`

HasAmount returns a boolean if a field has been set.

### GetPeriodDisplay

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetPeriodDisplay() string`

GetPeriodDisplay returns the PeriodDisplay field if non-nil, zero value otherwise.

### GetPeriodDisplayOk

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetPeriodDisplayOk() (*string, bool)`

GetPeriodDisplayOk returns a tuple with the PeriodDisplay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriodDisplay

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) SetPeriodDisplay(v string)`

SetPeriodDisplay sets PeriodDisplay field to given value.

### HasPeriodDisplay

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) HasPeriodDisplay() bool`

HasPeriodDisplay returns a boolean if a field has been set.

### GetTransactionDate

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetTransactionDate() time.Time`

GetTransactionDate returns the TransactionDate field if non-nil, zero value otherwise.

### GetTransactionDateOk

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetTransactionDateOk() (*time.Time, bool)`

GetTransactionDateOk returns a tuple with the TransactionDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransactionDate

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) SetTransactionDate(v time.Time)`

SetTransactionDate sets TransactionDate field to given value.

### HasTransactionDate

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) HasTransactionDate() bool`

HasTransactionDate returns a boolean if a field has been set.

### GetNote

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetCreatedById

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetCreatedById() string`

GetCreatedById returns the CreatedById field if non-nil, zero value otherwise.

### GetCreatedByIdOk

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetCreatedByIdOk() (*string, bool)`

GetCreatedByIdOk returns a tuple with the CreatedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedById

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) SetCreatedById(v string)`

SetCreatedById sets CreatedById field to given value.

### HasCreatedById

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) HasCreatedById() bool`

HasCreatedById returns a boolean if a field has been set.

### GetCreatedDate

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.

### GetModifiedById

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetModifiedDate

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetModifiedDate() time.Time`

GetModifiedDate returns the ModifiedDate field if non-nil, zero value otherwise.

### GetModifiedDateOk

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetModifiedDateOk() (*time.Time, bool)`

GetModifiedDateOk returns a tuple with the ModifiedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDate

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) SetModifiedDate(v time.Time)`

SetModifiedDate sets ModifiedDate field to given value.

### HasModifiedDate

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) HasModifiedDate() bool`

HasModifiedDate returns a boolean if a field has been set.

### GetPaymentType

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetPaymentType() string`

GetPaymentType returns the PaymentType field if non-nil, zero value otherwise.

### GetPaymentTypeOk

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetPaymentTypeOk() (*string, bool)`

GetPaymentTypeOk returns a tuple with the PaymentType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentType

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) SetPaymentType(v string)`

SetPaymentType sets PaymentType field to given value.

### HasPaymentType

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) HasPaymentType() bool`

HasPaymentType returns a boolean if a field has been set.

### GetStatus

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetCheckDate

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetCheckDate() time.Time`

GetCheckDate returns the CheckDate field if non-nil, zero value otherwise.

### GetCheckDateOk

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetCheckDateOk() (*time.Time, bool)`

GetCheckDateOk returns a tuple with the CheckDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckDate

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) SetCheckDate(v time.Time)`

SetCheckDate sets CheckDate field to given value.

### HasCheckDate

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) HasCheckDate() bool`

HasCheckDate returns a boolean if a field has been set.

### GetBooked

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetBooked() bool`

GetBooked returns the Booked field if non-nil, zero value otherwise.

### GetBookedOk

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetBookedOk() (*bool, bool)`

GetBookedOk returns a tuple with the Booked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBooked

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) SetBooked(v bool)`

SetBooked sets Booked field to given value.

### HasBooked

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) HasBooked() bool`

HasBooked returns a boolean if a field has been set.

### GetCleared

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetCleared() string`

GetCleared returns the Cleared field if non-nil, zero value otherwise.

### GetClearedOk

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetClearedOk() (*string, bool)`

GetClearedOk returns a tuple with the Cleared field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCleared

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) SetCleared(v string)`

SetCleared sets Cleared field to given value.

### HasCleared

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) HasCleared() bool`

HasCleared returns a boolean if a field has been set.

### GetClearDate

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetClearDate() time.Time`

GetClearDate returns the ClearDate field if non-nil, zero value otherwise.

### GetClearDateOk

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetClearDateOk() (*time.Time, bool)`

GetClearDateOk returns a tuple with the ClearDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClearDate

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) SetClearDate(v time.Time)`

SetClearDate sets ClearDate field to given value.

### HasClearDate

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) HasClearDate() bool`

HasClearDate returns a boolean if a field has been set.

### GetClearPeriod

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetClearPeriod() string`

GetClearPeriod returns the ClearPeriod field if non-nil, zero value otherwise.

### GetClearPeriodOk

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetClearPeriodOk() (*string, bool)`

GetClearPeriodOk returns a tuple with the ClearPeriod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClearPeriod

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) SetClearPeriod(v string)`

SetClearPeriod sets ClearPeriod field to given value.

### HasClearPeriod

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) HasClearPeriod() bool`

HasClearPeriod returns a boolean if a field has been set.

### GetClearedAmount

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetClearedAmount() float64`

GetClearedAmount returns the ClearedAmount field if non-nil, zero value otherwise.

### GetClearedAmountOk

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetClearedAmountOk() (*float64, bool)`

GetClearedAmountOk returns a tuple with the ClearedAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClearedAmount

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) SetClearedAmount(v float64)`

SetClearedAmount sets ClearedAmount field to given value.

### HasClearedAmount

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) HasClearedAmount() bool`

HasClearedAmount returns a boolean if a field has been set.

### GetVoid

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetVoid() bool`

GetVoid returns the Void field if non-nil, zero value otherwise.

### GetVoidOk

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetVoidOk() (*bool, bool)`

GetVoidOk returns a tuple with the Void field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoid

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) SetVoid(v bool)`

SetVoid sets Void field to given value.

### HasVoid

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) HasVoid() bool`

HasVoid returns a boolean if a field has been set.

### GetVoucherNo

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetVoucherNo() string`

GetVoucherNo returns the VoucherNo field if non-nil, zero value otherwise.

### GetVoucherNoOk

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetVoucherNoOk() (*string, bool)`

GetVoucherNoOk returns a tuple with the VoucherNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoucherNo

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) SetVoucherNo(v string)`

SetVoucherNo sets VoucherNo field to given value.

### HasVoucherNo

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) HasVoucherNo() bool`

HasVoucherNo returns a boolean if a field has been set.

### GetCheckNote

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetCheckNote() string`

GetCheckNote returns the CheckNote field if non-nil, zero value otherwise.

### GetCheckNoteOk

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetCheckNoteOk() (*string, bool)`

GetCheckNoteOk returns a tuple with the CheckNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckNote

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) SetCheckNote(v string)`

SetCheckNote sets CheckNote field to given value.

### HasCheckNote

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) HasCheckNote() bool`

HasCheckNote returns a boolean if a field has been set.

### GetMailedDate

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetMailedDate() time.Time`

GetMailedDate returns the MailedDate field if non-nil, zero value otherwise.

### GetMailedDateOk

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetMailedDateOk() (*time.Time, bool)`

GetMailedDateOk returns a tuple with the MailedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMailedDate

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) SetMailedDate(v time.Time)`

SetMailedDate sets MailedDate field to given value.

### HasMailedDate

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) HasMailedDate() bool`

HasMailedDate returns a boolean if a field has been set.

### GetExchangeRate

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetExchangeRate() float64`

GetExchangeRate returns the ExchangeRate field if non-nil, zero value otherwise.

### GetExchangeRateOk

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetExchangeRateOk() (*float64, bool)`

GetExchangeRateOk returns a tuple with the ExchangeRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExchangeRate

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) SetExchangeRate(v float64)`

SetExchangeRate sets ExchangeRate field to given value.

### HasExchangeRate

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) HasExchangeRate() bool`

HasExchangeRate returns a boolean if a field has been set.

### GetCurrencyCode

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetCurrencyCode() string`

GetCurrencyCode returns the CurrencyCode field if non-nil, zero value otherwise.

### GetCurrencyCodeOk

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetCurrencyCodeOk() (*string, bool)`

GetCurrencyCodeOk returns a tuple with the CurrencyCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyCode

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) SetCurrencyCode(v string)`

SetCurrencyCode sets CurrencyCode field to given value.

### HasCurrencyCode

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) HasCurrencyCode() bool`

HasCurrencyCode returns a boolean if a field has been set.

### GetLines

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetLines() []LinesItem3`

GetLines returns the Lines field if non-nil, zero value otherwise.

### GetLinesOk

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) GetLinesOk() (*[]LinesItem3, bool)`

GetLinesOk returns a tuple with the Lines field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLines

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) SetLines(v []LinesItem3)`

SetLines sets Lines field to given value.

### HasLines

`func (o *AccountsPayablePaymentsApiGetAPPaymentResponse) HasLines() bool`

HasLines returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


