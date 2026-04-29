# KeyMeasurablesApiListMetricBenchmarksItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | The metric benchmark ID. | [optional] 
**MetricId** | Pointer to **string** | The metric ID. | [optional] 
**StartDateTime** | Pointer to **time.Time** | The start date for the metric benchmark. | [optional] 
**EndDateTime** | Pointer to **time.Time** | The end date for the metric benchmark. | [optional] 
**Success** | Pointer to **float64** | The success value for the metric benchmark. | [optional] 
**Warning** | Pointer to **float64** | The warning value for the metric benchmark. | [optional] 
**WarningPercent** | Pointer to **float64** | The warning percentage for the metric benchmark. | [optional] 
**Critical** | Pointer to **float64** | The critical value for the metric benchmark. | [optional] 
**CriticalPercent** | Pointer to **float64** | The critical percentage for the metric benchmark. | [optional] 

## Methods

### NewKeyMeasurablesApiListMetricBenchmarksItem

`func NewKeyMeasurablesApiListMetricBenchmarksItem() *KeyMeasurablesApiListMetricBenchmarksItem`

NewKeyMeasurablesApiListMetricBenchmarksItem instantiates a new KeyMeasurablesApiListMetricBenchmarksItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewKeyMeasurablesApiListMetricBenchmarksItemWithDefaults

`func NewKeyMeasurablesApiListMetricBenchmarksItemWithDefaults() *KeyMeasurablesApiListMetricBenchmarksItem`

NewKeyMeasurablesApiListMetricBenchmarksItemWithDefaults instantiates a new KeyMeasurablesApiListMetricBenchmarksItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *KeyMeasurablesApiListMetricBenchmarksItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *KeyMeasurablesApiListMetricBenchmarksItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *KeyMeasurablesApiListMetricBenchmarksItem) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *KeyMeasurablesApiListMetricBenchmarksItem) HasId() bool`

HasId returns a boolean if a field has been set.

### GetMetricId

`func (o *KeyMeasurablesApiListMetricBenchmarksItem) GetMetricId() string`

GetMetricId returns the MetricId field if non-nil, zero value otherwise.

### GetMetricIdOk

`func (o *KeyMeasurablesApiListMetricBenchmarksItem) GetMetricIdOk() (*string, bool)`

GetMetricIdOk returns a tuple with the MetricId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetricId

`func (o *KeyMeasurablesApiListMetricBenchmarksItem) SetMetricId(v string)`

SetMetricId sets MetricId field to given value.

### HasMetricId

`func (o *KeyMeasurablesApiListMetricBenchmarksItem) HasMetricId() bool`

HasMetricId returns a boolean if a field has been set.

### GetStartDateTime

`func (o *KeyMeasurablesApiListMetricBenchmarksItem) GetStartDateTime() time.Time`

GetStartDateTime returns the StartDateTime field if non-nil, zero value otherwise.

### GetStartDateTimeOk

`func (o *KeyMeasurablesApiListMetricBenchmarksItem) GetStartDateTimeOk() (*time.Time, bool)`

GetStartDateTimeOk returns a tuple with the StartDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartDateTime

`func (o *KeyMeasurablesApiListMetricBenchmarksItem) SetStartDateTime(v time.Time)`

SetStartDateTime sets StartDateTime field to given value.

### HasStartDateTime

`func (o *KeyMeasurablesApiListMetricBenchmarksItem) HasStartDateTime() bool`

HasStartDateTime returns a boolean if a field has been set.

### GetEndDateTime

`func (o *KeyMeasurablesApiListMetricBenchmarksItem) GetEndDateTime() time.Time`

GetEndDateTime returns the EndDateTime field if non-nil, zero value otherwise.

### GetEndDateTimeOk

`func (o *KeyMeasurablesApiListMetricBenchmarksItem) GetEndDateTimeOk() (*time.Time, bool)`

GetEndDateTimeOk returns a tuple with the EndDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndDateTime

`func (o *KeyMeasurablesApiListMetricBenchmarksItem) SetEndDateTime(v time.Time)`

SetEndDateTime sets EndDateTime field to given value.

### HasEndDateTime

`func (o *KeyMeasurablesApiListMetricBenchmarksItem) HasEndDateTime() bool`

HasEndDateTime returns a boolean if a field has been set.

### GetSuccess

`func (o *KeyMeasurablesApiListMetricBenchmarksItem) GetSuccess() float64`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *KeyMeasurablesApiListMetricBenchmarksItem) GetSuccessOk() (*float64, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *KeyMeasurablesApiListMetricBenchmarksItem) SetSuccess(v float64)`

SetSuccess sets Success field to given value.

### HasSuccess

`func (o *KeyMeasurablesApiListMetricBenchmarksItem) HasSuccess() bool`

HasSuccess returns a boolean if a field has been set.

### GetWarning

`func (o *KeyMeasurablesApiListMetricBenchmarksItem) GetWarning() float64`

GetWarning returns the Warning field if non-nil, zero value otherwise.

### GetWarningOk

`func (o *KeyMeasurablesApiListMetricBenchmarksItem) GetWarningOk() (*float64, bool)`

GetWarningOk returns a tuple with the Warning field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarning

`func (o *KeyMeasurablesApiListMetricBenchmarksItem) SetWarning(v float64)`

SetWarning sets Warning field to given value.

### HasWarning

`func (o *KeyMeasurablesApiListMetricBenchmarksItem) HasWarning() bool`

HasWarning returns a boolean if a field has been set.

### GetWarningPercent

`func (o *KeyMeasurablesApiListMetricBenchmarksItem) GetWarningPercent() float64`

GetWarningPercent returns the WarningPercent field if non-nil, zero value otherwise.

### GetWarningPercentOk

`func (o *KeyMeasurablesApiListMetricBenchmarksItem) GetWarningPercentOk() (*float64, bool)`

GetWarningPercentOk returns a tuple with the WarningPercent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarningPercent

`func (o *KeyMeasurablesApiListMetricBenchmarksItem) SetWarningPercent(v float64)`

SetWarningPercent sets WarningPercent field to given value.

### HasWarningPercent

`func (o *KeyMeasurablesApiListMetricBenchmarksItem) HasWarningPercent() bool`

HasWarningPercent returns a boolean if a field has been set.

### GetCritical

`func (o *KeyMeasurablesApiListMetricBenchmarksItem) GetCritical() float64`

GetCritical returns the Critical field if non-nil, zero value otherwise.

### GetCriticalOk

`func (o *KeyMeasurablesApiListMetricBenchmarksItem) GetCriticalOk() (*float64, bool)`

GetCriticalOk returns a tuple with the Critical field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCritical

`func (o *KeyMeasurablesApiListMetricBenchmarksItem) SetCritical(v float64)`

SetCritical sets Critical field to given value.

### HasCritical

`func (o *KeyMeasurablesApiListMetricBenchmarksItem) HasCritical() bool`

HasCritical returns a boolean if a field has been set.

### GetCriticalPercent

`func (o *KeyMeasurablesApiListMetricBenchmarksItem) GetCriticalPercent() float64`

GetCriticalPercent returns the CriticalPercent field if non-nil, zero value otherwise.

### GetCriticalPercentOk

`func (o *KeyMeasurablesApiListMetricBenchmarksItem) GetCriticalPercentOk() (*float64, bool)`

GetCriticalPercentOk returns a tuple with the CriticalPercent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCriticalPercent

`func (o *KeyMeasurablesApiListMetricBenchmarksItem) SetCriticalPercent(v float64)`

SetCriticalPercent sets CriticalPercent field to given value.

### HasCriticalPercent

`func (o *KeyMeasurablesApiListMetricBenchmarksItem) HasCriticalPercent() bool`

HasCriticalPercent returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


