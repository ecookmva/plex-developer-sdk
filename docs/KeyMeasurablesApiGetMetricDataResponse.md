# KeyMeasurablesApiGetMetricDataResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**MetricId** | Pointer to **string** | The metric ID. | [optional] 
**MetricName** | Pointer to **string** | The metric name. | [optional] 
**Unit** | Pointer to **string** | The unit of measure for the metric. | [optional] 
**Dimension** | Pointer to **string** | The dimension data (a list of data points and dates) for the metric. | [optional] 
**Frequency** | Pointer to **string** | The aggregation frequency for the metric data. | [optional] 
**Dimensions** | Pointer to [**[]DimensionsItem**](DimensionsItem.md) | The dimension data for the metric. | [optional] 

## Methods

### NewKeyMeasurablesApiGetMetricDataResponse

`func NewKeyMeasurablesApiGetMetricDataResponse() *KeyMeasurablesApiGetMetricDataResponse`

NewKeyMeasurablesApiGetMetricDataResponse instantiates a new KeyMeasurablesApiGetMetricDataResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewKeyMeasurablesApiGetMetricDataResponseWithDefaults

`func NewKeyMeasurablesApiGetMetricDataResponseWithDefaults() *KeyMeasurablesApiGetMetricDataResponse`

NewKeyMeasurablesApiGetMetricDataResponseWithDefaults instantiates a new KeyMeasurablesApiGetMetricDataResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMetricId

`func (o *KeyMeasurablesApiGetMetricDataResponse) GetMetricId() string`

GetMetricId returns the MetricId field if non-nil, zero value otherwise.

### GetMetricIdOk

`func (o *KeyMeasurablesApiGetMetricDataResponse) GetMetricIdOk() (*string, bool)`

GetMetricIdOk returns a tuple with the MetricId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetricId

`func (o *KeyMeasurablesApiGetMetricDataResponse) SetMetricId(v string)`

SetMetricId sets MetricId field to given value.

### HasMetricId

`func (o *KeyMeasurablesApiGetMetricDataResponse) HasMetricId() bool`

HasMetricId returns a boolean if a field has been set.

### GetMetricName

`func (o *KeyMeasurablesApiGetMetricDataResponse) GetMetricName() string`

GetMetricName returns the MetricName field if non-nil, zero value otherwise.

### GetMetricNameOk

`func (o *KeyMeasurablesApiGetMetricDataResponse) GetMetricNameOk() (*string, bool)`

GetMetricNameOk returns a tuple with the MetricName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetricName

`func (o *KeyMeasurablesApiGetMetricDataResponse) SetMetricName(v string)`

SetMetricName sets MetricName field to given value.

### HasMetricName

`func (o *KeyMeasurablesApiGetMetricDataResponse) HasMetricName() bool`

HasMetricName returns a boolean if a field has been set.

### GetUnit

`func (o *KeyMeasurablesApiGetMetricDataResponse) GetUnit() string`

GetUnit returns the Unit field if non-nil, zero value otherwise.

### GetUnitOk

`func (o *KeyMeasurablesApiGetMetricDataResponse) GetUnitOk() (*string, bool)`

GetUnitOk returns a tuple with the Unit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnit

`func (o *KeyMeasurablesApiGetMetricDataResponse) SetUnit(v string)`

SetUnit sets Unit field to given value.

### HasUnit

`func (o *KeyMeasurablesApiGetMetricDataResponse) HasUnit() bool`

HasUnit returns a boolean if a field has been set.

### GetDimension

`func (o *KeyMeasurablesApiGetMetricDataResponse) GetDimension() string`

GetDimension returns the Dimension field if non-nil, zero value otherwise.

### GetDimensionOk

`func (o *KeyMeasurablesApiGetMetricDataResponse) GetDimensionOk() (*string, bool)`

GetDimensionOk returns a tuple with the Dimension field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDimension

`func (o *KeyMeasurablesApiGetMetricDataResponse) SetDimension(v string)`

SetDimension sets Dimension field to given value.

### HasDimension

`func (o *KeyMeasurablesApiGetMetricDataResponse) HasDimension() bool`

HasDimension returns a boolean if a field has been set.

### GetFrequency

`func (o *KeyMeasurablesApiGetMetricDataResponse) GetFrequency() string`

GetFrequency returns the Frequency field if non-nil, zero value otherwise.

### GetFrequencyOk

`func (o *KeyMeasurablesApiGetMetricDataResponse) GetFrequencyOk() (*string, bool)`

GetFrequencyOk returns a tuple with the Frequency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrequency

`func (o *KeyMeasurablesApiGetMetricDataResponse) SetFrequency(v string)`

SetFrequency sets Frequency field to given value.

### HasFrequency

`func (o *KeyMeasurablesApiGetMetricDataResponse) HasFrequency() bool`

HasFrequency returns a boolean if a field has been set.

### GetDimensions

`func (o *KeyMeasurablesApiGetMetricDataResponse) GetDimensions() []DimensionsItem`

GetDimensions returns the Dimensions field if non-nil, zero value otherwise.

### GetDimensionsOk

`func (o *KeyMeasurablesApiGetMetricDataResponse) GetDimensionsOk() (*[]DimensionsItem, bool)`

GetDimensionsOk returns a tuple with the Dimensions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDimensions

`func (o *KeyMeasurablesApiGetMetricDataResponse) SetDimensions(v []DimensionsItem)`

SetDimensions sets Dimensions field to given value.

### HasDimensions

`func (o *KeyMeasurablesApiGetMetricDataResponse) HasDimensions() bool`

HasDimensions returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


