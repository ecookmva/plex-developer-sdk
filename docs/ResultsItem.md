# ResultsItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TagName** | Pointer to **string** | Tag Name | [optional] 
**StartTimeUnixTimestamp** | Pointer to **int64** | Unix timestamp of start time | [optional] 
**StartTimeISOTimestamp** | Pointer to **string** | Date and time representation of start time | [optional] 
**ElapsedTimeMilliseconds** | Pointer to **int32** | Returns time duration in milliseconds spent by a Boolean tag in TRUE state | [optional] 
**EventType** | Pointer to **string** | Event type | [optional] 

## Methods

### NewResultsItem

`func NewResultsItem() *ResultsItem`

NewResultsItem instantiates a new ResultsItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResultsItemWithDefaults

`func NewResultsItemWithDefaults() *ResultsItem`

NewResultsItemWithDefaults instantiates a new ResultsItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTagName

`func (o *ResultsItem) GetTagName() string`

GetTagName returns the TagName field if non-nil, zero value otherwise.

### GetTagNameOk

`func (o *ResultsItem) GetTagNameOk() (*string, bool)`

GetTagNameOk returns a tuple with the TagName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTagName

`func (o *ResultsItem) SetTagName(v string)`

SetTagName sets TagName field to given value.

### HasTagName

`func (o *ResultsItem) HasTagName() bool`

HasTagName returns a boolean if a field has been set.

### GetStartTimeUnixTimestamp

`func (o *ResultsItem) GetStartTimeUnixTimestamp() int64`

GetStartTimeUnixTimestamp returns the StartTimeUnixTimestamp field if non-nil, zero value otherwise.

### GetStartTimeUnixTimestampOk

`func (o *ResultsItem) GetStartTimeUnixTimestampOk() (*int64, bool)`

GetStartTimeUnixTimestampOk returns a tuple with the StartTimeUnixTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartTimeUnixTimestamp

`func (o *ResultsItem) SetStartTimeUnixTimestamp(v int64)`

SetStartTimeUnixTimestamp sets StartTimeUnixTimestamp field to given value.

### HasStartTimeUnixTimestamp

`func (o *ResultsItem) HasStartTimeUnixTimestamp() bool`

HasStartTimeUnixTimestamp returns a boolean if a field has been set.

### GetStartTimeISOTimestamp

`func (o *ResultsItem) GetStartTimeISOTimestamp() string`

GetStartTimeISOTimestamp returns the StartTimeISOTimestamp field if non-nil, zero value otherwise.

### GetStartTimeISOTimestampOk

`func (o *ResultsItem) GetStartTimeISOTimestampOk() (*string, bool)`

GetStartTimeISOTimestampOk returns a tuple with the StartTimeISOTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartTimeISOTimestamp

`func (o *ResultsItem) SetStartTimeISOTimestamp(v string)`

SetStartTimeISOTimestamp sets StartTimeISOTimestamp field to given value.

### HasStartTimeISOTimestamp

`func (o *ResultsItem) HasStartTimeISOTimestamp() bool`

HasStartTimeISOTimestamp returns a boolean if a field has been set.

### GetElapsedTimeMilliseconds

`func (o *ResultsItem) GetElapsedTimeMilliseconds() int32`

GetElapsedTimeMilliseconds returns the ElapsedTimeMilliseconds field if non-nil, zero value otherwise.

### GetElapsedTimeMillisecondsOk

`func (o *ResultsItem) GetElapsedTimeMillisecondsOk() (*int32, bool)`

GetElapsedTimeMillisecondsOk returns a tuple with the ElapsedTimeMilliseconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetElapsedTimeMilliseconds

`func (o *ResultsItem) SetElapsedTimeMilliseconds(v int32)`

SetElapsedTimeMilliseconds sets ElapsedTimeMilliseconds field to given value.

### HasElapsedTimeMilliseconds

`func (o *ResultsItem) HasElapsedTimeMilliseconds() bool`

HasElapsedTimeMilliseconds returns a boolean if a field has been set.

### GetEventType

`func (o *ResultsItem) GetEventType() string`

GetEventType returns the EventType field if non-nil, zero value otherwise.

### GetEventTypeOk

`func (o *ResultsItem) GetEventTypeOk() (*string, bool)`

GetEventTypeOk returns a tuple with the EventType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventType

`func (o *ResultsItem) SetEventType(v string)`

SetEventType sets EventType field to given value.

### HasEventType

`func (o *ResultsItem) HasEventType() bool`

HasEventType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


