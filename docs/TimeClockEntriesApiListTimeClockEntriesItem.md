# TimeClockEntriesApiListTimeClockEntriesItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**EmployeeId** | Pointer to **string** | A unique identifier for the Employee. This will be automatically generated if omitted from the request. | [optional] 
**PayDate** | Pointer to **time.Time** | Pay Date | [optional] 
**Type** | Pointer to **string** | Clock in type. Setup Table: Clockin_Attribute_Type | [optional] 
**TotalHours** | Pointer to **float64** | The total of Regular hours, Overtime_Hours, and Doubletime_Hours | [optional] 
**Shift** | Pointer to **string** | Setup Table: Shift | [optional] 
**Approved** | Pointer to **int32** |  | [optional] 
**ClockinTime** | Pointer to **time.Time** | The time at which the user clocked in. | [optional] 
**ClockoutTime** | Pointer to **time.Time** | The time at which the user clocked out. | [optional] 
**CreatedBy** | Pointer to **string** | The ID of the user who created the record. | [optional] 
**CreatedDate** | Pointer to **time.Time** | The date on which the record was created. | [optional] 
**ModifiedById** | Pointer to **string** | The ID of the user who last modified the record. | [optional] 
**ModifiedDate** | Pointer to **time.Time** | The date on which the record was last modified. | [optional] 

## Methods

### NewTimeClockEntriesApiListTimeClockEntriesItem

`func NewTimeClockEntriesApiListTimeClockEntriesItem() *TimeClockEntriesApiListTimeClockEntriesItem`

NewTimeClockEntriesApiListTimeClockEntriesItem instantiates a new TimeClockEntriesApiListTimeClockEntriesItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTimeClockEntriesApiListTimeClockEntriesItemWithDefaults

`func NewTimeClockEntriesApiListTimeClockEntriesItemWithDefaults() *TimeClockEntriesApiListTimeClockEntriesItem`

NewTimeClockEntriesApiListTimeClockEntriesItemWithDefaults instantiates a new TimeClockEntriesApiListTimeClockEntriesItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEmployeeId

`func (o *TimeClockEntriesApiListTimeClockEntriesItem) GetEmployeeId() string`

GetEmployeeId returns the EmployeeId field if non-nil, zero value otherwise.

### GetEmployeeIdOk

`func (o *TimeClockEntriesApiListTimeClockEntriesItem) GetEmployeeIdOk() (*string, bool)`

GetEmployeeIdOk returns a tuple with the EmployeeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmployeeId

`func (o *TimeClockEntriesApiListTimeClockEntriesItem) SetEmployeeId(v string)`

SetEmployeeId sets EmployeeId field to given value.

### HasEmployeeId

`func (o *TimeClockEntriesApiListTimeClockEntriesItem) HasEmployeeId() bool`

HasEmployeeId returns a boolean if a field has been set.

### GetPayDate

`func (o *TimeClockEntriesApiListTimeClockEntriesItem) GetPayDate() time.Time`

GetPayDate returns the PayDate field if non-nil, zero value otherwise.

### GetPayDateOk

`func (o *TimeClockEntriesApiListTimeClockEntriesItem) GetPayDateOk() (*time.Time, bool)`

GetPayDateOk returns a tuple with the PayDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPayDate

`func (o *TimeClockEntriesApiListTimeClockEntriesItem) SetPayDate(v time.Time)`

SetPayDate sets PayDate field to given value.

### HasPayDate

`func (o *TimeClockEntriesApiListTimeClockEntriesItem) HasPayDate() bool`

HasPayDate returns a boolean if a field has been set.

### GetType

`func (o *TimeClockEntriesApiListTimeClockEntriesItem) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *TimeClockEntriesApiListTimeClockEntriesItem) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *TimeClockEntriesApiListTimeClockEntriesItem) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *TimeClockEntriesApiListTimeClockEntriesItem) HasType() bool`

HasType returns a boolean if a field has been set.

### GetTotalHours

`func (o *TimeClockEntriesApiListTimeClockEntriesItem) GetTotalHours() float64`

GetTotalHours returns the TotalHours field if non-nil, zero value otherwise.

### GetTotalHoursOk

`func (o *TimeClockEntriesApiListTimeClockEntriesItem) GetTotalHoursOk() (*float64, bool)`

GetTotalHoursOk returns a tuple with the TotalHours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalHours

`func (o *TimeClockEntriesApiListTimeClockEntriesItem) SetTotalHours(v float64)`

SetTotalHours sets TotalHours field to given value.

### HasTotalHours

`func (o *TimeClockEntriesApiListTimeClockEntriesItem) HasTotalHours() bool`

HasTotalHours returns a boolean if a field has been set.

### GetShift

`func (o *TimeClockEntriesApiListTimeClockEntriesItem) GetShift() string`

GetShift returns the Shift field if non-nil, zero value otherwise.

### GetShiftOk

`func (o *TimeClockEntriesApiListTimeClockEntriesItem) GetShiftOk() (*string, bool)`

GetShiftOk returns a tuple with the Shift field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShift

`func (o *TimeClockEntriesApiListTimeClockEntriesItem) SetShift(v string)`

SetShift sets Shift field to given value.

### HasShift

`func (o *TimeClockEntriesApiListTimeClockEntriesItem) HasShift() bool`

HasShift returns a boolean if a field has been set.

### GetApproved

`func (o *TimeClockEntriesApiListTimeClockEntriesItem) GetApproved() int32`

GetApproved returns the Approved field if non-nil, zero value otherwise.

### GetApprovedOk

`func (o *TimeClockEntriesApiListTimeClockEntriesItem) GetApprovedOk() (*int32, bool)`

GetApprovedOk returns a tuple with the Approved field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApproved

`func (o *TimeClockEntriesApiListTimeClockEntriesItem) SetApproved(v int32)`

SetApproved sets Approved field to given value.

### HasApproved

`func (o *TimeClockEntriesApiListTimeClockEntriesItem) HasApproved() bool`

HasApproved returns a boolean if a field has been set.

### GetClockinTime

`func (o *TimeClockEntriesApiListTimeClockEntriesItem) GetClockinTime() time.Time`

GetClockinTime returns the ClockinTime field if non-nil, zero value otherwise.

### GetClockinTimeOk

`func (o *TimeClockEntriesApiListTimeClockEntriesItem) GetClockinTimeOk() (*time.Time, bool)`

GetClockinTimeOk returns a tuple with the ClockinTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClockinTime

`func (o *TimeClockEntriesApiListTimeClockEntriesItem) SetClockinTime(v time.Time)`

SetClockinTime sets ClockinTime field to given value.

### HasClockinTime

`func (o *TimeClockEntriesApiListTimeClockEntriesItem) HasClockinTime() bool`

HasClockinTime returns a boolean if a field has been set.

### GetClockoutTime

`func (o *TimeClockEntriesApiListTimeClockEntriesItem) GetClockoutTime() time.Time`

GetClockoutTime returns the ClockoutTime field if non-nil, zero value otherwise.

### GetClockoutTimeOk

`func (o *TimeClockEntriesApiListTimeClockEntriesItem) GetClockoutTimeOk() (*time.Time, bool)`

GetClockoutTimeOk returns a tuple with the ClockoutTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClockoutTime

`func (o *TimeClockEntriesApiListTimeClockEntriesItem) SetClockoutTime(v time.Time)`

SetClockoutTime sets ClockoutTime field to given value.

### HasClockoutTime

`func (o *TimeClockEntriesApiListTimeClockEntriesItem) HasClockoutTime() bool`

HasClockoutTime returns a boolean if a field has been set.

### GetCreatedBy

`func (o *TimeClockEntriesApiListTimeClockEntriesItem) GetCreatedBy() string`

GetCreatedBy returns the CreatedBy field if non-nil, zero value otherwise.

### GetCreatedByOk

`func (o *TimeClockEntriesApiListTimeClockEntriesItem) GetCreatedByOk() (*string, bool)`

GetCreatedByOk returns a tuple with the CreatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedBy

`func (o *TimeClockEntriesApiListTimeClockEntriesItem) SetCreatedBy(v string)`

SetCreatedBy sets CreatedBy field to given value.

### HasCreatedBy

`func (o *TimeClockEntriesApiListTimeClockEntriesItem) HasCreatedBy() bool`

HasCreatedBy returns a boolean if a field has been set.

### GetCreatedDate

`func (o *TimeClockEntriesApiListTimeClockEntriesItem) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *TimeClockEntriesApiListTimeClockEntriesItem) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *TimeClockEntriesApiListTimeClockEntriesItem) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *TimeClockEntriesApiListTimeClockEntriesItem) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.

### GetModifiedById

`func (o *TimeClockEntriesApiListTimeClockEntriesItem) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *TimeClockEntriesApiListTimeClockEntriesItem) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *TimeClockEntriesApiListTimeClockEntriesItem) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *TimeClockEntriesApiListTimeClockEntriesItem) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetModifiedDate

`func (o *TimeClockEntriesApiListTimeClockEntriesItem) GetModifiedDate() time.Time`

GetModifiedDate returns the ModifiedDate field if non-nil, zero value otherwise.

### GetModifiedDateOk

`func (o *TimeClockEntriesApiListTimeClockEntriesItem) GetModifiedDateOk() (*time.Time, bool)`

GetModifiedDateOk returns a tuple with the ModifiedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDate

`func (o *TimeClockEntriesApiListTimeClockEntriesItem) SetModifiedDate(v time.Time)`

SetModifiedDate sets ModifiedDate field to given value.

### HasModifiedDate

`func (o *TimeClockEntriesApiListTimeClockEntriesItem) HasModifiedDate() bool`

HasModifiedDate returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


