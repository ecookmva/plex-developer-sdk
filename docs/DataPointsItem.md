# DataPointsItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DisplayTimestamp** | Pointer to **string** | The display timestamp for the data point. | [optional] 
**Value** | Pointer to **float64** | The value for the data point. | [optional] 

## Methods

### NewDataPointsItem

`func NewDataPointsItem() *DataPointsItem`

NewDataPointsItem instantiates a new DataPointsItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDataPointsItemWithDefaults

`func NewDataPointsItemWithDefaults() *DataPointsItem`

NewDataPointsItemWithDefaults instantiates a new DataPointsItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDisplayTimestamp

`func (o *DataPointsItem) GetDisplayTimestamp() string`

GetDisplayTimestamp returns the DisplayTimestamp field if non-nil, zero value otherwise.

### GetDisplayTimestampOk

`func (o *DataPointsItem) GetDisplayTimestampOk() (*string, bool)`

GetDisplayTimestampOk returns a tuple with the DisplayTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplayTimestamp

`func (o *DataPointsItem) SetDisplayTimestamp(v string)`

SetDisplayTimestamp sets DisplayTimestamp field to given value.

### HasDisplayTimestamp

`func (o *DataPointsItem) HasDisplayTimestamp() bool`

HasDisplayTimestamp returns a boolean if a field has been set.

### GetValue

`func (o *DataPointsItem) GetValue() float64`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *DataPointsItem) GetValueOk() (*float64, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *DataPointsItem) SetValue(v float64)`

SetValue sets Value field to given value.

### HasValue

`func (o *DataPointsItem) HasValue() bool`

HasValue returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


