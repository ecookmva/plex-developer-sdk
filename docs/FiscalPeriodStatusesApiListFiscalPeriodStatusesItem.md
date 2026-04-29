# FiscalPeriodStatusesApiListFiscalPeriodStatusesItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FiscalYear** | Pointer to **string** | Fiscal Year. | [optional] 
**PeriodDisplay** | Pointer to **string** | Fiscal Period. | [optional] 
**BeginDate** | Pointer to **time.Time** | The calendar start date of a fiscal period. | [optional] 
**EndDate** | Pointer to **time.Time** | The calendar end date of a fiscal period. | [optional] 
**PeriodStatus** | Pointer to **string** | Period status. Open - Transactions can be posted in open periods. Soft Closed - Transactions can be viewed, and posted/modified by users with access permissions. Closed - The period has ended. Transactions cannot be posted. | [optional] 
**YearStatus** | Pointer to **string** | Fiscal year status. Open - The fiscal year is open. Transactions can be posted in open periods. Closed - The fiscal year has ended. Transactions cannot be posted to fiscal year periods. | [optional] 

## Methods

### NewFiscalPeriodStatusesApiListFiscalPeriodStatusesItem

`func NewFiscalPeriodStatusesApiListFiscalPeriodStatusesItem() *FiscalPeriodStatusesApiListFiscalPeriodStatusesItem`

NewFiscalPeriodStatusesApiListFiscalPeriodStatusesItem instantiates a new FiscalPeriodStatusesApiListFiscalPeriodStatusesItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFiscalPeriodStatusesApiListFiscalPeriodStatusesItemWithDefaults

`func NewFiscalPeriodStatusesApiListFiscalPeriodStatusesItemWithDefaults() *FiscalPeriodStatusesApiListFiscalPeriodStatusesItem`

NewFiscalPeriodStatusesApiListFiscalPeriodStatusesItemWithDefaults instantiates a new FiscalPeriodStatusesApiListFiscalPeriodStatusesItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFiscalYear

`func (o *FiscalPeriodStatusesApiListFiscalPeriodStatusesItem) GetFiscalYear() string`

GetFiscalYear returns the FiscalYear field if non-nil, zero value otherwise.

### GetFiscalYearOk

`func (o *FiscalPeriodStatusesApiListFiscalPeriodStatusesItem) GetFiscalYearOk() (*string, bool)`

GetFiscalYearOk returns a tuple with the FiscalYear field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFiscalYear

`func (o *FiscalPeriodStatusesApiListFiscalPeriodStatusesItem) SetFiscalYear(v string)`

SetFiscalYear sets FiscalYear field to given value.

### HasFiscalYear

`func (o *FiscalPeriodStatusesApiListFiscalPeriodStatusesItem) HasFiscalYear() bool`

HasFiscalYear returns a boolean if a field has been set.

### GetPeriodDisplay

`func (o *FiscalPeriodStatusesApiListFiscalPeriodStatusesItem) GetPeriodDisplay() string`

GetPeriodDisplay returns the PeriodDisplay field if non-nil, zero value otherwise.

### GetPeriodDisplayOk

`func (o *FiscalPeriodStatusesApiListFiscalPeriodStatusesItem) GetPeriodDisplayOk() (*string, bool)`

GetPeriodDisplayOk returns a tuple with the PeriodDisplay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriodDisplay

`func (o *FiscalPeriodStatusesApiListFiscalPeriodStatusesItem) SetPeriodDisplay(v string)`

SetPeriodDisplay sets PeriodDisplay field to given value.

### HasPeriodDisplay

`func (o *FiscalPeriodStatusesApiListFiscalPeriodStatusesItem) HasPeriodDisplay() bool`

HasPeriodDisplay returns a boolean if a field has been set.

### GetBeginDate

`func (o *FiscalPeriodStatusesApiListFiscalPeriodStatusesItem) GetBeginDate() time.Time`

GetBeginDate returns the BeginDate field if non-nil, zero value otherwise.

### GetBeginDateOk

`func (o *FiscalPeriodStatusesApiListFiscalPeriodStatusesItem) GetBeginDateOk() (*time.Time, bool)`

GetBeginDateOk returns a tuple with the BeginDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBeginDate

`func (o *FiscalPeriodStatusesApiListFiscalPeriodStatusesItem) SetBeginDate(v time.Time)`

SetBeginDate sets BeginDate field to given value.

### HasBeginDate

`func (o *FiscalPeriodStatusesApiListFiscalPeriodStatusesItem) HasBeginDate() bool`

HasBeginDate returns a boolean if a field has been set.

### GetEndDate

`func (o *FiscalPeriodStatusesApiListFiscalPeriodStatusesItem) GetEndDate() time.Time`

GetEndDate returns the EndDate field if non-nil, zero value otherwise.

### GetEndDateOk

`func (o *FiscalPeriodStatusesApiListFiscalPeriodStatusesItem) GetEndDateOk() (*time.Time, bool)`

GetEndDateOk returns a tuple with the EndDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndDate

`func (o *FiscalPeriodStatusesApiListFiscalPeriodStatusesItem) SetEndDate(v time.Time)`

SetEndDate sets EndDate field to given value.

### HasEndDate

`func (o *FiscalPeriodStatusesApiListFiscalPeriodStatusesItem) HasEndDate() bool`

HasEndDate returns a boolean if a field has been set.

### GetPeriodStatus

`func (o *FiscalPeriodStatusesApiListFiscalPeriodStatusesItem) GetPeriodStatus() string`

GetPeriodStatus returns the PeriodStatus field if non-nil, zero value otherwise.

### GetPeriodStatusOk

`func (o *FiscalPeriodStatusesApiListFiscalPeriodStatusesItem) GetPeriodStatusOk() (*string, bool)`

GetPeriodStatusOk returns a tuple with the PeriodStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriodStatus

`func (o *FiscalPeriodStatusesApiListFiscalPeriodStatusesItem) SetPeriodStatus(v string)`

SetPeriodStatus sets PeriodStatus field to given value.

### HasPeriodStatus

`func (o *FiscalPeriodStatusesApiListFiscalPeriodStatusesItem) HasPeriodStatus() bool`

HasPeriodStatus returns a boolean if a field has been set.

### GetYearStatus

`func (o *FiscalPeriodStatusesApiListFiscalPeriodStatusesItem) GetYearStatus() string`

GetYearStatus returns the YearStatus field if non-nil, zero value otherwise.

### GetYearStatusOk

`func (o *FiscalPeriodStatusesApiListFiscalPeriodStatusesItem) GetYearStatusOk() (*string, bool)`

GetYearStatusOk returns a tuple with the YearStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYearStatus

`func (o *FiscalPeriodStatusesApiListFiscalPeriodStatusesItem) SetYearStatus(v string)`

SetYearStatus sets YearStatus field to given value.

### HasYearStatus

`func (o *FiscalPeriodStatusesApiListFiscalPeriodStatusesItem) HasYearStatus() bool`

HasYearStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


