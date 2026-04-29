# JournalEntriesApiListJournalEntriesItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | The GL journal entry ID. | [optional] 
**JournalNumber** | Pointer to **int32** | The GL journal entry journal number. | [optional] 
**PeriodDisplay** | Pointer to **string** | The period in which a GL journal entry is recorded. | [optional] 
**Description** | Pointer to **string** | A description of the GL journal entry. | [optional] 
**Note** | Pointer to **string** | A note added to the GL journal entry. | [optional] 
**PostDate** | Pointer to **time.Time** | The date a GL journal entry was posted. | [optional] 
**Reversing** | Pointer to **bool** | Specify a GL journal entry has been reversed. | [optional] 
**Currency** | Pointer to **string** | The GL journal entry currency. | [optional] 
**ExchangeRate** | Pointer to **float64** | The GL journal entry exchange rate. | [optional] 
**Status** | Pointer to **string** | The GL journal entry status. | [optional] 
**CreatedById** | Pointer to **string** | The IAM ID with which the GL journal entry was created. | [optional] 
**CreatedDate** | Pointer to **time.Time** | The date the GL journal entry was created. | [optional] 
**ModifiedById** | Pointer to **string** | The IAM ID that last modified the GL journal entry. | [optional] 
**ModifiedDate** | Pointer to **time.Time** | The date a GL journal entry was last modified. | [optional] 
**VoucherNumber** | Pointer to **string** | The GL journal entry voucher number. | [optional] 
**Booked** | Pointer to **bool** | Specify if a GL journal entry has been booked. | [optional] 
**Period13** | Pointer to **bool** | Specify if a GL journal entry is in the 13th period. | [optional] 
**GovernmentIssuedNo** | Pointer to **string** | The GL journal entry Government Issued No. | [optional] 
**PeriodAdjustment** | Pointer to **bool** | The GL journal entry period adjustment. | [optional] 
**Lines** | Pointer to [**[]LinesItem8**](LinesItem8.md) | A list of GL journal lines. | [optional] 

## Methods

### NewJournalEntriesApiListJournalEntriesItem

`func NewJournalEntriesApiListJournalEntriesItem() *JournalEntriesApiListJournalEntriesItem`

NewJournalEntriesApiListJournalEntriesItem instantiates a new JournalEntriesApiListJournalEntriesItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewJournalEntriesApiListJournalEntriesItemWithDefaults

`func NewJournalEntriesApiListJournalEntriesItemWithDefaults() *JournalEntriesApiListJournalEntriesItem`

NewJournalEntriesApiListJournalEntriesItemWithDefaults instantiates a new JournalEntriesApiListJournalEntriesItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *JournalEntriesApiListJournalEntriesItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *JournalEntriesApiListJournalEntriesItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *JournalEntriesApiListJournalEntriesItem) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *JournalEntriesApiListJournalEntriesItem) HasId() bool`

HasId returns a boolean if a field has been set.

### GetJournalNumber

`func (o *JournalEntriesApiListJournalEntriesItem) GetJournalNumber() int32`

GetJournalNumber returns the JournalNumber field if non-nil, zero value otherwise.

### GetJournalNumberOk

`func (o *JournalEntriesApiListJournalEntriesItem) GetJournalNumberOk() (*int32, bool)`

GetJournalNumberOk returns a tuple with the JournalNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJournalNumber

`func (o *JournalEntriesApiListJournalEntriesItem) SetJournalNumber(v int32)`

SetJournalNumber sets JournalNumber field to given value.

### HasJournalNumber

`func (o *JournalEntriesApiListJournalEntriesItem) HasJournalNumber() bool`

HasJournalNumber returns a boolean if a field has been set.

### GetPeriodDisplay

`func (o *JournalEntriesApiListJournalEntriesItem) GetPeriodDisplay() string`

GetPeriodDisplay returns the PeriodDisplay field if non-nil, zero value otherwise.

### GetPeriodDisplayOk

`func (o *JournalEntriesApiListJournalEntriesItem) GetPeriodDisplayOk() (*string, bool)`

GetPeriodDisplayOk returns a tuple with the PeriodDisplay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriodDisplay

`func (o *JournalEntriesApiListJournalEntriesItem) SetPeriodDisplay(v string)`

SetPeriodDisplay sets PeriodDisplay field to given value.

### HasPeriodDisplay

`func (o *JournalEntriesApiListJournalEntriesItem) HasPeriodDisplay() bool`

HasPeriodDisplay returns a boolean if a field has been set.

### GetDescription

`func (o *JournalEntriesApiListJournalEntriesItem) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *JournalEntriesApiListJournalEntriesItem) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *JournalEntriesApiListJournalEntriesItem) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *JournalEntriesApiListJournalEntriesItem) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetNote

`func (o *JournalEntriesApiListJournalEntriesItem) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *JournalEntriesApiListJournalEntriesItem) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *JournalEntriesApiListJournalEntriesItem) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *JournalEntriesApiListJournalEntriesItem) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetPostDate

`func (o *JournalEntriesApiListJournalEntriesItem) GetPostDate() time.Time`

GetPostDate returns the PostDate field if non-nil, zero value otherwise.

### GetPostDateOk

`func (o *JournalEntriesApiListJournalEntriesItem) GetPostDateOk() (*time.Time, bool)`

GetPostDateOk returns a tuple with the PostDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostDate

`func (o *JournalEntriesApiListJournalEntriesItem) SetPostDate(v time.Time)`

SetPostDate sets PostDate field to given value.

### HasPostDate

`func (o *JournalEntriesApiListJournalEntriesItem) HasPostDate() bool`

HasPostDate returns a boolean if a field has been set.

### GetReversing

`func (o *JournalEntriesApiListJournalEntriesItem) GetReversing() bool`

GetReversing returns the Reversing field if non-nil, zero value otherwise.

### GetReversingOk

`func (o *JournalEntriesApiListJournalEntriesItem) GetReversingOk() (*bool, bool)`

GetReversingOk returns a tuple with the Reversing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReversing

`func (o *JournalEntriesApiListJournalEntriesItem) SetReversing(v bool)`

SetReversing sets Reversing field to given value.

### HasReversing

`func (o *JournalEntriesApiListJournalEntriesItem) HasReversing() bool`

HasReversing returns a boolean if a field has been set.

### GetCurrency

`func (o *JournalEntriesApiListJournalEntriesItem) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *JournalEntriesApiListJournalEntriesItem) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *JournalEntriesApiListJournalEntriesItem) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *JournalEntriesApiListJournalEntriesItem) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### GetExchangeRate

`func (o *JournalEntriesApiListJournalEntriesItem) GetExchangeRate() float64`

GetExchangeRate returns the ExchangeRate field if non-nil, zero value otherwise.

### GetExchangeRateOk

`func (o *JournalEntriesApiListJournalEntriesItem) GetExchangeRateOk() (*float64, bool)`

GetExchangeRateOk returns a tuple with the ExchangeRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExchangeRate

`func (o *JournalEntriesApiListJournalEntriesItem) SetExchangeRate(v float64)`

SetExchangeRate sets ExchangeRate field to given value.

### HasExchangeRate

`func (o *JournalEntriesApiListJournalEntriesItem) HasExchangeRate() bool`

HasExchangeRate returns a boolean if a field has been set.

### GetStatus

`func (o *JournalEntriesApiListJournalEntriesItem) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *JournalEntriesApiListJournalEntriesItem) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *JournalEntriesApiListJournalEntriesItem) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *JournalEntriesApiListJournalEntriesItem) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetCreatedById

`func (o *JournalEntriesApiListJournalEntriesItem) GetCreatedById() string`

GetCreatedById returns the CreatedById field if non-nil, zero value otherwise.

### GetCreatedByIdOk

`func (o *JournalEntriesApiListJournalEntriesItem) GetCreatedByIdOk() (*string, bool)`

GetCreatedByIdOk returns a tuple with the CreatedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedById

`func (o *JournalEntriesApiListJournalEntriesItem) SetCreatedById(v string)`

SetCreatedById sets CreatedById field to given value.

### HasCreatedById

`func (o *JournalEntriesApiListJournalEntriesItem) HasCreatedById() bool`

HasCreatedById returns a boolean if a field has been set.

### GetCreatedDate

`func (o *JournalEntriesApiListJournalEntriesItem) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *JournalEntriesApiListJournalEntriesItem) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *JournalEntriesApiListJournalEntriesItem) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *JournalEntriesApiListJournalEntriesItem) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.

### GetModifiedById

`func (o *JournalEntriesApiListJournalEntriesItem) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *JournalEntriesApiListJournalEntriesItem) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *JournalEntriesApiListJournalEntriesItem) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *JournalEntriesApiListJournalEntriesItem) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetModifiedDate

`func (o *JournalEntriesApiListJournalEntriesItem) GetModifiedDate() time.Time`

GetModifiedDate returns the ModifiedDate field if non-nil, zero value otherwise.

### GetModifiedDateOk

`func (o *JournalEntriesApiListJournalEntriesItem) GetModifiedDateOk() (*time.Time, bool)`

GetModifiedDateOk returns a tuple with the ModifiedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDate

`func (o *JournalEntriesApiListJournalEntriesItem) SetModifiedDate(v time.Time)`

SetModifiedDate sets ModifiedDate field to given value.

### HasModifiedDate

`func (o *JournalEntriesApiListJournalEntriesItem) HasModifiedDate() bool`

HasModifiedDate returns a boolean if a field has been set.

### GetVoucherNumber

`func (o *JournalEntriesApiListJournalEntriesItem) GetVoucherNumber() string`

GetVoucherNumber returns the VoucherNumber field if non-nil, zero value otherwise.

### GetVoucherNumberOk

`func (o *JournalEntriesApiListJournalEntriesItem) GetVoucherNumberOk() (*string, bool)`

GetVoucherNumberOk returns a tuple with the VoucherNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoucherNumber

`func (o *JournalEntriesApiListJournalEntriesItem) SetVoucherNumber(v string)`

SetVoucherNumber sets VoucherNumber field to given value.

### HasVoucherNumber

`func (o *JournalEntriesApiListJournalEntriesItem) HasVoucherNumber() bool`

HasVoucherNumber returns a boolean if a field has been set.

### GetBooked

`func (o *JournalEntriesApiListJournalEntriesItem) GetBooked() bool`

GetBooked returns the Booked field if non-nil, zero value otherwise.

### GetBookedOk

`func (o *JournalEntriesApiListJournalEntriesItem) GetBookedOk() (*bool, bool)`

GetBookedOk returns a tuple with the Booked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBooked

`func (o *JournalEntriesApiListJournalEntriesItem) SetBooked(v bool)`

SetBooked sets Booked field to given value.

### HasBooked

`func (o *JournalEntriesApiListJournalEntriesItem) HasBooked() bool`

HasBooked returns a boolean if a field has been set.

### GetPeriod13

`func (o *JournalEntriesApiListJournalEntriesItem) GetPeriod13() bool`

GetPeriod13 returns the Period13 field if non-nil, zero value otherwise.

### GetPeriod13Ok

`func (o *JournalEntriesApiListJournalEntriesItem) GetPeriod13Ok() (*bool, bool)`

GetPeriod13Ok returns a tuple with the Period13 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriod13

`func (o *JournalEntriesApiListJournalEntriesItem) SetPeriod13(v bool)`

SetPeriod13 sets Period13 field to given value.

### HasPeriod13

`func (o *JournalEntriesApiListJournalEntriesItem) HasPeriod13() bool`

HasPeriod13 returns a boolean if a field has been set.

### GetGovernmentIssuedNo

`func (o *JournalEntriesApiListJournalEntriesItem) GetGovernmentIssuedNo() string`

GetGovernmentIssuedNo returns the GovernmentIssuedNo field if non-nil, zero value otherwise.

### GetGovernmentIssuedNoOk

`func (o *JournalEntriesApiListJournalEntriesItem) GetGovernmentIssuedNoOk() (*string, bool)`

GetGovernmentIssuedNoOk returns a tuple with the GovernmentIssuedNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGovernmentIssuedNo

`func (o *JournalEntriesApiListJournalEntriesItem) SetGovernmentIssuedNo(v string)`

SetGovernmentIssuedNo sets GovernmentIssuedNo field to given value.

### HasGovernmentIssuedNo

`func (o *JournalEntriesApiListJournalEntriesItem) HasGovernmentIssuedNo() bool`

HasGovernmentIssuedNo returns a boolean if a field has been set.

### GetPeriodAdjustment

`func (o *JournalEntriesApiListJournalEntriesItem) GetPeriodAdjustment() bool`

GetPeriodAdjustment returns the PeriodAdjustment field if non-nil, zero value otherwise.

### GetPeriodAdjustmentOk

`func (o *JournalEntriesApiListJournalEntriesItem) GetPeriodAdjustmentOk() (*bool, bool)`

GetPeriodAdjustmentOk returns a tuple with the PeriodAdjustment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriodAdjustment

`func (o *JournalEntriesApiListJournalEntriesItem) SetPeriodAdjustment(v bool)`

SetPeriodAdjustment sets PeriodAdjustment field to given value.

### HasPeriodAdjustment

`func (o *JournalEntriesApiListJournalEntriesItem) HasPeriodAdjustment() bool`

HasPeriodAdjustment returns a boolean if a field has been set.

### GetLines

`func (o *JournalEntriesApiListJournalEntriesItem) GetLines() []LinesItem8`

GetLines returns the Lines field if non-nil, zero value otherwise.

### GetLinesOk

`func (o *JournalEntriesApiListJournalEntriesItem) GetLinesOk() (*[]LinesItem8, bool)`

GetLinesOk returns a tuple with the Lines field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLines

`func (o *JournalEntriesApiListJournalEntriesItem) SetLines(v []LinesItem8)`

SetLines sets Lines field to given value.

### HasLines

`func (o *JournalEntriesApiListJournalEntriesItem) HasLines() bool`

HasLines returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


