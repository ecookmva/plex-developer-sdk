# JournalEntriesApiUpdateJournalEntryResponse

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

### NewJournalEntriesApiUpdateJournalEntryResponse

`func NewJournalEntriesApiUpdateJournalEntryResponse() *JournalEntriesApiUpdateJournalEntryResponse`

NewJournalEntriesApiUpdateJournalEntryResponse instantiates a new JournalEntriesApiUpdateJournalEntryResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewJournalEntriesApiUpdateJournalEntryResponseWithDefaults

`func NewJournalEntriesApiUpdateJournalEntryResponseWithDefaults() *JournalEntriesApiUpdateJournalEntryResponse`

NewJournalEntriesApiUpdateJournalEntryResponseWithDefaults instantiates a new JournalEntriesApiUpdateJournalEntryResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *JournalEntriesApiUpdateJournalEntryResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *JournalEntriesApiUpdateJournalEntryResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *JournalEntriesApiUpdateJournalEntryResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *JournalEntriesApiUpdateJournalEntryResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetJournalNumber

`func (o *JournalEntriesApiUpdateJournalEntryResponse) GetJournalNumber() int32`

GetJournalNumber returns the JournalNumber field if non-nil, zero value otherwise.

### GetJournalNumberOk

`func (o *JournalEntriesApiUpdateJournalEntryResponse) GetJournalNumberOk() (*int32, bool)`

GetJournalNumberOk returns a tuple with the JournalNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJournalNumber

`func (o *JournalEntriesApiUpdateJournalEntryResponse) SetJournalNumber(v int32)`

SetJournalNumber sets JournalNumber field to given value.

### HasJournalNumber

`func (o *JournalEntriesApiUpdateJournalEntryResponse) HasJournalNumber() bool`

HasJournalNumber returns a boolean if a field has been set.

### GetPeriodDisplay

`func (o *JournalEntriesApiUpdateJournalEntryResponse) GetPeriodDisplay() string`

GetPeriodDisplay returns the PeriodDisplay field if non-nil, zero value otherwise.

### GetPeriodDisplayOk

`func (o *JournalEntriesApiUpdateJournalEntryResponse) GetPeriodDisplayOk() (*string, bool)`

GetPeriodDisplayOk returns a tuple with the PeriodDisplay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriodDisplay

`func (o *JournalEntriesApiUpdateJournalEntryResponse) SetPeriodDisplay(v string)`

SetPeriodDisplay sets PeriodDisplay field to given value.

### HasPeriodDisplay

`func (o *JournalEntriesApiUpdateJournalEntryResponse) HasPeriodDisplay() bool`

HasPeriodDisplay returns a boolean if a field has been set.

### GetDescription

`func (o *JournalEntriesApiUpdateJournalEntryResponse) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *JournalEntriesApiUpdateJournalEntryResponse) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *JournalEntriesApiUpdateJournalEntryResponse) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *JournalEntriesApiUpdateJournalEntryResponse) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetNote

`func (o *JournalEntriesApiUpdateJournalEntryResponse) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *JournalEntriesApiUpdateJournalEntryResponse) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *JournalEntriesApiUpdateJournalEntryResponse) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *JournalEntriesApiUpdateJournalEntryResponse) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetPostDate

`func (o *JournalEntriesApiUpdateJournalEntryResponse) GetPostDate() time.Time`

GetPostDate returns the PostDate field if non-nil, zero value otherwise.

### GetPostDateOk

`func (o *JournalEntriesApiUpdateJournalEntryResponse) GetPostDateOk() (*time.Time, bool)`

GetPostDateOk returns a tuple with the PostDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostDate

`func (o *JournalEntriesApiUpdateJournalEntryResponse) SetPostDate(v time.Time)`

SetPostDate sets PostDate field to given value.

### HasPostDate

`func (o *JournalEntriesApiUpdateJournalEntryResponse) HasPostDate() bool`

HasPostDate returns a boolean if a field has been set.

### GetReversing

`func (o *JournalEntriesApiUpdateJournalEntryResponse) GetReversing() bool`

GetReversing returns the Reversing field if non-nil, zero value otherwise.

### GetReversingOk

`func (o *JournalEntriesApiUpdateJournalEntryResponse) GetReversingOk() (*bool, bool)`

GetReversingOk returns a tuple with the Reversing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReversing

`func (o *JournalEntriesApiUpdateJournalEntryResponse) SetReversing(v bool)`

SetReversing sets Reversing field to given value.

### HasReversing

`func (o *JournalEntriesApiUpdateJournalEntryResponse) HasReversing() bool`

HasReversing returns a boolean if a field has been set.

### GetCurrency

`func (o *JournalEntriesApiUpdateJournalEntryResponse) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *JournalEntriesApiUpdateJournalEntryResponse) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *JournalEntriesApiUpdateJournalEntryResponse) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *JournalEntriesApiUpdateJournalEntryResponse) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### GetExchangeRate

`func (o *JournalEntriesApiUpdateJournalEntryResponse) GetExchangeRate() float64`

GetExchangeRate returns the ExchangeRate field if non-nil, zero value otherwise.

### GetExchangeRateOk

`func (o *JournalEntriesApiUpdateJournalEntryResponse) GetExchangeRateOk() (*float64, bool)`

GetExchangeRateOk returns a tuple with the ExchangeRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExchangeRate

`func (o *JournalEntriesApiUpdateJournalEntryResponse) SetExchangeRate(v float64)`

SetExchangeRate sets ExchangeRate field to given value.

### HasExchangeRate

`func (o *JournalEntriesApiUpdateJournalEntryResponse) HasExchangeRate() bool`

HasExchangeRate returns a boolean if a field has been set.

### GetStatus

`func (o *JournalEntriesApiUpdateJournalEntryResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *JournalEntriesApiUpdateJournalEntryResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *JournalEntriesApiUpdateJournalEntryResponse) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *JournalEntriesApiUpdateJournalEntryResponse) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetCreatedById

`func (o *JournalEntriesApiUpdateJournalEntryResponse) GetCreatedById() string`

GetCreatedById returns the CreatedById field if non-nil, zero value otherwise.

### GetCreatedByIdOk

`func (o *JournalEntriesApiUpdateJournalEntryResponse) GetCreatedByIdOk() (*string, bool)`

GetCreatedByIdOk returns a tuple with the CreatedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedById

`func (o *JournalEntriesApiUpdateJournalEntryResponse) SetCreatedById(v string)`

SetCreatedById sets CreatedById field to given value.

### HasCreatedById

`func (o *JournalEntriesApiUpdateJournalEntryResponse) HasCreatedById() bool`

HasCreatedById returns a boolean if a field has been set.

### GetCreatedDate

`func (o *JournalEntriesApiUpdateJournalEntryResponse) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *JournalEntriesApiUpdateJournalEntryResponse) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *JournalEntriesApiUpdateJournalEntryResponse) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *JournalEntriesApiUpdateJournalEntryResponse) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.

### GetModifiedById

`func (o *JournalEntriesApiUpdateJournalEntryResponse) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *JournalEntriesApiUpdateJournalEntryResponse) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *JournalEntriesApiUpdateJournalEntryResponse) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *JournalEntriesApiUpdateJournalEntryResponse) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetModifiedDate

`func (o *JournalEntriesApiUpdateJournalEntryResponse) GetModifiedDate() time.Time`

GetModifiedDate returns the ModifiedDate field if non-nil, zero value otherwise.

### GetModifiedDateOk

`func (o *JournalEntriesApiUpdateJournalEntryResponse) GetModifiedDateOk() (*time.Time, bool)`

GetModifiedDateOk returns a tuple with the ModifiedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDate

`func (o *JournalEntriesApiUpdateJournalEntryResponse) SetModifiedDate(v time.Time)`

SetModifiedDate sets ModifiedDate field to given value.

### HasModifiedDate

`func (o *JournalEntriesApiUpdateJournalEntryResponse) HasModifiedDate() bool`

HasModifiedDate returns a boolean if a field has been set.

### GetVoucherNumber

`func (o *JournalEntriesApiUpdateJournalEntryResponse) GetVoucherNumber() string`

GetVoucherNumber returns the VoucherNumber field if non-nil, zero value otherwise.

### GetVoucherNumberOk

`func (o *JournalEntriesApiUpdateJournalEntryResponse) GetVoucherNumberOk() (*string, bool)`

GetVoucherNumberOk returns a tuple with the VoucherNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoucherNumber

`func (o *JournalEntriesApiUpdateJournalEntryResponse) SetVoucherNumber(v string)`

SetVoucherNumber sets VoucherNumber field to given value.

### HasVoucherNumber

`func (o *JournalEntriesApiUpdateJournalEntryResponse) HasVoucherNumber() bool`

HasVoucherNumber returns a boolean if a field has been set.

### GetBooked

`func (o *JournalEntriesApiUpdateJournalEntryResponse) GetBooked() bool`

GetBooked returns the Booked field if non-nil, zero value otherwise.

### GetBookedOk

`func (o *JournalEntriesApiUpdateJournalEntryResponse) GetBookedOk() (*bool, bool)`

GetBookedOk returns a tuple with the Booked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBooked

`func (o *JournalEntriesApiUpdateJournalEntryResponse) SetBooked(v bool)`

SetBooked sets Booked field to given value.

### HasBooked

`func (o *JournalEntriesApiUpdateJournalEntryResponse) HasBooked() bool`

HasBooked returns a boolean if a field has been set.

### GetPeriod13

`func (o *JournalEntriesApiUpdateJournalEntryResponse) GetPeriod13() bool`

GetPeriod13 returns the Period13 field if non-nil, zero value otherwise.

### GetPeriod13Ok

`func (o *JournalEntriesApiUpdateJournalEntryResponse) GetPeriod13Ok() (*bool, bool)`

GetPeriod13Ok returns a tuple with the Period13 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriod13

`func (o *JournalEntriesApiUpdateJournalEntryResponse) SetPeriod13(v bool)`

SetPeriod13 sets Period13 field to given value.

### HasPeriod13

`func (o *JournalEntriesApiUpdateJournalEntryResponse) HasPeriod13() bool`

HasPeriod13 returns a boolean if a field has been set.

### GetGovernmentIssuedNo

`func (o *JournalEntriesApiUpdateJournalEntryResponse) GetGovernmentIssuedNo() string`

GetGovernmentIssuedNo returns the GovernmentIssuedNo field if non-nil, zero value otherwise.

### GetGovernmentIssuedNoOk

`func (o *JournalEntriesApiUpdateJournalEntryResponse) GetGovernmentIssuedNoOk() (*string, bool)`

GetGovernmentIssuedNoOk returns a tuple with the GovernmentIssuedNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGovernmentIssuedNo

`func (o *JournalEntriesApiUpdateJournalEntryResponse) SetGovernmentIssuedNo(v string)`

SetGovernmentIssuedNo sets GovernmentIssuedNo field to given value.

### HasGovernmentIssuedNo

`func (o *JournalEntriesApiUpdateJournalEntryResponse) HasGovernmentIssuedNo() bool`

HasGovernmentIssuedNo returns a boolean if a field has been set.

### GetPeriodAdjustment

`func (o *JournalEntriesApiUpdateJournalEntryResponse) GetPeriodAdjustment() bool`

GetPeriodAdjustment returns the PeriodAdjustment field if non-nil, zero value otherwise.

### GetPeriodAdjustmentOk

`func (o *JournalEntriesApiUpdateJournalEntryResponse) GetPeriodAdjustmentOk() (*bool, bool)`

GetPeriodAdjustmentOk returns a tuple with the PeriodAdjustment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriodAdjustment

`func (o *JournalEntriesApiUpdateJournalEntryResponse) SetPeriodAdjustment(v bool)`

SetPeriodAdjustment sets PeriodAdjustment field to given value.

### HasPeriodAdjustment

`func (o *JournalEntriesApiUpdateJournalEntryResponse) HasPeriodAdjustment() bool`

HasPeriodAdjustment returns a boolean if a field has been set.

### GetLines

`func (o *JournalEntriesApiUpdateJournalEntryResponse) GetLines() []LinesItem8`

GetLines returns the Lines field if non-nil, zero value otherwise.

### GetLinesOk

`func (o *JournalEntriesApiUpdateJournalEntryResponse) GetLinesOk() (*[]LinesItem8, bool)`

GetLinesOk returns a tuple with the Lines field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLines

`func (o *JournalEntriesApiUpdateJournalEntryResponse) SetLines(v []LinesItem8)`

SetLines sets Lines field to given value.

### HasLines

`func (o *JournalEntriesApiUpdateJournalEntryResponse) HasLines() bool`

HasLines returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


