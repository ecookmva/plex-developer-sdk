# ScheduleDetailsItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**WorkcenterId** | Pointer to **string** | A unique identifier for the workcenter. | [optional] 
**StartDateTime** | Pointer to **time.Time** | Start of the date range for the job op scheduling. | [optional] 
**RunLength** | Pointer to **int32** | Run length of scheduled operation in minutes. | [optional] 

## Methods

### NewScheduleDetailsItem

`func NewScheduleDetailsItem() *ScheduleDetailsItem`

NewScheduleDetailsItem instantiates a new ScheduleDetailsItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewScheduleDetailsItemWithDefaults

`func NewScheduleDetailsItemWithDefaults() *ScheduleDetailsItem`

NewScheduleDetailsItemWithDefaults instantiates a new ScheduleDetailsItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetWorkcenterId

`func (o *ScheduleDetailsItem) GetWorkcenterId() string`

GetWorkcenterId returns the WorkcenterId field if non-nil, zero value otherwise.

### GetWorkcenterIdOk

`func (o *ScheduleDetailsItem) GetWorkcenterIdOk() (*string, bool)`

GetWorkcenterIdOk returns a tuple with the WorkcenterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkcenterId

`func (o *ScheduleDetailsItem) SetWorkcenterId(v string)`

SetWorkcenterId sets WorkcenterId field to given value.

### HasWorkcenterId

`func (o *ScheduleDetailsItem) HasWorkcenterId() bool`

HasWorkcenterId returns a boolean if a field has been set.

### GetStartDateTime

`func (o *ScheduleDetailsItem) GetStartDateTime() time.Time`

GetStartDateTime returns the StartDateTime field if non-nil, zero value otherwise.

### GetStartDateTimeOk

`func (o *ScheduleDetailsItem) GetStartDateTimeOk() (*time.Time, bool)`

GetStartDateTimeOk returns a tuple with the StartDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartDateTime

`func (o *ScheduleDetailsItem) SetStartDateTime(v time.Time)`

SetStartDateTime sets StartDateTime field to given value.

### HasStartDateTime

`func (o *ScheduleDetailsItem) HasStartDateTime() bool`

HasStartDateTime returns a boolean if a field has been set.

### GetRunLength

`func (o *ScheduleDetailsItem) GetRunLength() int32`

GetRunLength returns the RunLength field if non-nil, zero value otherwise.

### GetRunLengthOk

`func (o *ScheduleDetailsItem) GetRunLengthOk() (*int32, bool)`

GetRunLengthOk returns a tuple with the RunLength field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunLength

`func (o *ScheduleDetailsItem) SetRunLength(v int32)`

SetRunLength sets RunLength field to given value.

### HasRunLength

`func (o *ScheduleDetailsItem) HasRunLength() bool`

HasRunLength returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


