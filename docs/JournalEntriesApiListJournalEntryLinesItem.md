# JournalEntriesApiListJournalEntryLinesItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccountId** | Pointer to **string** | A unique identifier for the account. This will be automatically generated if omitted from the request. | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**Debit** | Pointer to **float64** | The debit amount shown in the default currency for the entity. | [optional] 
**Credit** | Pointer to **float64** | The debit amount shown in the default currency for the entity. | [optional] 
**CreatedDate** | Pointer to **time.Time** | The date on which the record was created. | [optional] 
**ModifiedById** | Pointer to **string** | The IAM Account ID of the user who last modified the record. | [optional] 
**ModifiedDate** | Pointer to **time.Time** | The date on which the record was last modified. | [optional] 
**CurrencyDebit** | Pointer to **float64** | Use if the Journal Entry is in a foreign currency. | [optional] 
**CurrencyCredit** | Pointer to **float64** | Use if the Journal Entry is in a foreign currency. | [optional] 

## Methods

### NewJournalEntriesApiListJournalEntryLinesItem

`func NewJournalEntriesApiListJournalEntryLinesItem() *JournalEntriesApiListJournalEntryLinesItem`

NewJournalEntriesApiListJournalEntryLinesItem instantiates a new JournalEntriesApiListJournalEntryLinesItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewJournalEntriesApiListJournalEntryLinesItemWithDefaults

`func NewJournalEntriesApiListJournalEntryLinesItemWithDefaults() *JournalEntriesApiListJournalEntryLinesItem`

NewJournalEntriesApiListJournalEntryLinesItemWithDefaults instantiates a new JournalEntriesApiListJournalEntryLinesItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccountId

`func (o *JournalEntriesApiListJournalEntryLinesItem) GetAccountId() string`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *JournalEntriesApiListJournalEntryLinesItem) GetAccountIdOk() (*string, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *JournalEntriesApiListJournalEntryLinesItem) SetAccountId(v string)`

SetAccountId sets AccountId field to given value.

### HasAccountId

`func (o *JournalEntriesApiListJournalEntryLinesItem) HasAccountId() bool`

HasAccountId returns a boolean if a field has been set.

### GetDescription

`func (o *JournalEntriesApiListJournalEntryLinesItem) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *JournalEntriesApiListJournalEntryLinesItem) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *JournalEntriesApiListJournalEntryLinesItem) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *JournalEntriesApiListJournalEntryLinesItem) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetDebit

`func (o *JournalEntriesApiListJournalEntryLinesItem) GetDebit() float64`

GetDebit returns the Debit field if non-nil, zero value otherwise.

### GetDebitOk

`func (o *JournalEntriesApiListJournalEntryLinesItem) GetDebitOk() (*float64, bool)`

GetDebitOk returns a tuple with the Debit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDebit

`func (o *JournalEntriesApiListJournalEntryLinesItem) SetDebit(v float64)`

SetDebit sets Debit field to given value.

### HasDebit

`func (o *JournalEntriesApiListJournalEntryLinesItem) HasDebit() bool`

HasDebit returns a boolean if a field has been set.

### GetCredit

`func (o *JournalEntriesApiListJournalEntryLinesItem) GetCredit() float64`

GetCredit returns the Credit field if non-nil, zero value otherwise.

### GetCreditOk

`func (o *JournalEntriesApiListJournalEntryLinesItem) GetCreditOk() (*float64, bool)`

GetCreditOk returns a tuple with the Credit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCredit

`func (o *JournalEntriesApiListJournalEntryLinesItem) SetCredit(v float64)`

SetCredit sets Credit field to given value.

### HasCredit

`func (o *JournalEntriesApiListJournalEntryLinesItem) HasCredit() bool`

HasCredit returns a boolean if a field has been set.

### GetCreatedDate

`func (o *JournalEntriesApiListJournalEntryLinesItem) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *JournalEntriesApiListJournalEntryLinesItem) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *JournalEntriesApiListJournalEntryLinesItem) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *JournalEntriesApiListJournalEntryLinesItem) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.

### GetModifiedById

`func (o *JournalEntriesApiListJournalEntryLinesItem) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *JournalEntriesApiListJournalEntryLinesItem) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *JournalEntriesApiListJournalEntryLinesItem) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *JournalEntriesApiListJournalEntryLinesItem) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetModifiedDate

`func (o *JournalEntriesApiListJournalEntryLinesItem) GetModifiedDate() time.Time`

GetModifiedDate returns the ModifiedDate field if non-nil, zero value otherwise.

### GetModifiedDateOk

`func (o *JournalEntriesApiListJournalEntryLinesItem) GetModifiedDateOk() (*time.Time, bool)`

GetModifiedDateOk returns a tuple with the ModifiedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDate

`func (o *JournalEntriesApiListJournalEntryLinesItem) SetModifiedDate(v time.Time)`

SetModifiedDate sets ModifiedDate field to given value.

### HasModifiedDate

`func (o *JournalEntriesApiListJournalEntryLinesItem) HasModifiedDate() bool`

HasModifiedDate returns a boolean if a field has been set.

### GetCurrencyDebit

`func (o *JournalEntriesApiListJournalEntryLinesItem) GetCurrencyDebit() float64`

GetCurrencyDebit returns the CurrencyDebit field if non-nil, zero value otherwise.

### GetCurrencyDebitOk

`func (o *JournalEntriesApiListJournalEntryLinesItem) GetCurrencyDebitOk() (*float64, bool)`

GetCurrencyDebitOk returns a tuple with the CurrencyDebit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyDebit

`func (o *JournalEntriesApiListJournalEntryLinesItem) SetCurrencyDebit(v float64)`

SetCurrencyDebit sets CurrencyDebit field to given value.

### HasCurrencyDebit

`func (o *JournalEntriesApiListJournalEntryLinesItem) HasCurrencyDebit() bool`

HasCurrencyDebit returns a boolean if a field has been set.

### GetCurrencyCredit

`func (o *JournalEntriesApiListJournalEntryLinesItem) GetCurrencyCredit() float64`

GetCurrencyCredit returns the CurrencyCredit field if non-nil, zero value otherwise.

### GetCurrencyCreditOk

`func (o *JournalEntriesApiListJournalEntryLinesItem) GetCurrencyCreditOk() (*float64, bool)`

GetCurrencyCreditOk returns a tuple with the CurrencyCredit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyCredit

`func (o *JournalEntriesApiListJournalEntryLinesItem) SetCurrencyCredit(v float64)`

SetCurrencyCredit sets CurrencyCredit field to given value.

### HasCurrencyCredit

`func (o *JournalEntriesApiListJournalEntryLinesItem) HasCurrencyCredit() bool`

HasCurrencyCredit returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


