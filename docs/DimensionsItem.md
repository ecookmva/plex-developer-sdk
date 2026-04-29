# DimensionsItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | Pointer to **string** | The value of the dimension. | [optional] 
**DataPoints** | Pointer to [**[]DataPointsItem**](DataPointsItem.md) | A list of the data points for the dimension. | [optional] 

## Methods

### NewDimensionsItem

`func NewDimensionsItem() *DimensionsItem`

NewDimensionsItem instantiates a new DimensionsItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDimensionsItemWithDefaults

`func NewDimensionsItemWithDefaults() *DimensionsItem`

NewDimensionsItemWithDefaults instantiates a new DimensionsItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetValue

`func (o *DimensionsItem) GetValue() string`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *DimensionsItem) GetValueOk() (*string, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *DimensionsItem) SetValue(v string)`

SetValue sets Value field to given value.

### HasValue

`func (o *DimensionsItem) HasValue() bool`

HasValue returns a boolean if a field has been set.

### GetDataPoints

`func (o *DimensionsItem) GetDataPoints() []DataPointsItem`

GetDataPoints returns the DataPoints field if non-nil, zero value otherwise.

### GetDataPointsOk

`func (o *DimensionsItem) GetDataPointsOk() (*[]DataPointsItem, bool)`

GetDataPointsOk returns a tuple with the DataPoints field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataPoints

`func (o *DimensionsItem) SetDataPoints(v []DataPointsItem)`

SetDataPoints sets DataPoints field to given value.

### HasDataPoints

`func (o *DimensionsItem) HasDataPoints() bool`

HasDataPoints returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


