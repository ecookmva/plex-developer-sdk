# KeyMeasurablesApiGetMetricResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | The ID of a metric. | [optional] 
**Name** | Pointer to **string** | The name of the metric. | [optional] 
**BusinessFunctionId** | Pointer to **string** | The ID of the business function for the metric. | [optional] 
**BusinessFunctionValue** | Pointer to **string** | The name of the business function for the metric. | [optional] 
**DataSetId** | Pointer to **string** | The ID of the data set for the metric. | [optional] 
**DataSetName** | Pointer to **string** | The name of the data set for the metric. | [optional] 
**DataSetPeriodValue** | Pointer to **string** | The time period of the data set for the metric. | [optional] 
**MeasureId** | Pointer to **string** | The ID of the measure used to collect metric data. | [optional] 
**MeasureName** | Pointer to **string** | The name of the measure used to collect metric data. | [optional] 
**Unit** | Pointer to **string** | The unit of measure used for the metric. | [optional] 
**FrequencyId** | Pointer to **string** | The ID of the aggregation frequency used for the metric. | [optional] 
**FrequencyDescription** | Pointer to **string** | The description of the aggregation frequency used for the metric. | [optional] 
**FrequencyMethodName** | Pointer to **string** | The name of the aggregation method for the metric data in the specified frequency. | [optional] 
**DimensionId** | Pointer to **string** | The ID of the dimension for the metric. | [optional] 
**DimensionDescription** | Pointer to **string** | The description of the dimension for the metric. | [optional] 
**NumberOfDimensionValues** | Pointer to **int32** | The number of dimension values for the metric. | [optional] 
**DisplayTopBottomName** | Pointer to **string** | The name of the option for displaying top or bottom values for the metric data. | [optional] 
**BenchmarkType** | Pointer to **string** | The name of the benchmark (goal) type for the metric (i.e., threshold or target). | [optional] 
**SuccessIndicatorName** | Pointer to **string** | The name of the success indicator for the metric (High or Low). | [optional] 
**Benchmarks** | Pointer to **[]string** | The benchmark IDs for the metric. | [optional] 
**StrategicObjectives** | Pointer to **[]int32** | The strategic objectives keys for the metric. | [optional] 
**CreatedBy** | Pointer to **string** | The IAM account ID of the user who created the metric. | [optional] 
**CreatedDateTime** | Pointer to **time.Time** | The date on which the metric was created. | [optional] 
**LastModifiedBy** | Pointer to **string** | The ID of the user that last modified the metric. | [optional] 
**LastModifiedDateTime** | Pointer to **time.Time** | The date on which the metric was last modified. | [optional] 

## Methods

### NewKeyMeasurablesApiGetMetricResponse

`func NewKeyMeasurablesApiGetMetricResponse() *KeyMeasurablesApiGetMetricResponse`

NewKeyMeasurablesApiGetMetricResponse instantiates a new KeyMeasurablesApiGetMetricResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewKeyMeasurablesApiGetMetricResponseWithDefaults

`func NewKeyMeasurablesApiGetMetricResponseWithDefaults() *KeyMeasurablesApiGetMetricResponse`

NewKeyMeasurablesApiGetMetricResponseWithDefaults instantiates a new KeyMeasurablesApiGetMetricResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *KeyMeasurablesApiGetMetricResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *KeyMeasurablesApiGetMetricResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *KeyMeasurablesApiGetMetricResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *KeyMeasurablesApiGetMetricResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *KeyMeasurablesApiGetMetricResponse) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *KeyMeasurablesApiGetMetricResponse) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *KeyMeasurablesApiGetMetricResponse) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *KeyMeasurablesApiGetMetricResponse) HasName() bool`

HasName returns a boolean if a field has been set.

### GetBusinessFunctionId

`func (o *KeyMeasurablesApiGetMetricResponse) GetBusinessFunctionId() string`

GetBusinessFunctionId returns the BusinessFunctionId field if non-nil, zero value otherwise.

### GetBusinessFunctionIdOk

`func (o *KeyMeasurablesApiGetMetricResponse) GetBusinessFunctionIdOk() (*string, bool)`

GetBusinessFunctionIdOk returns a tuple with the BusinessFunctionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusinessFunctionId

`func (o *KeyMeasurablesApiGetMetricResponse) SetBusinessFunctionId(v string)`

SetBusinessFunctionId sets BusinessFunctionId field to given value.

### HasBusinessFunctionId

`func (o *KeyMeasurablesApiGetMetricResponse) HasBusinessFunctionId() bool`

HasBusinessFunctionId returns a boolean if a field has been set.

### GetBusinessFunctionValue

`func (o *KeyMeasurablesApiGetMetricResponse) GetBusinessFunctionValue() string`

GetBusinessFunctionValue returns the BusinessFunctionValue field if non-nil, zero value otherwise.

### GetBusinessFunctionValueOk

`func (o *KeyMeasurablesApiGetMetricResponse) GetBusinessFunctionValueOk() (*string, bool)`

GetBusinessFunctionValueOk returns a tuple with the BusinessFunctionValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusinessFunctionValue

`func (o *KeyMeasurablesApiGetMetricResponse) SetBusinessFunctionValue(v string)`

SetBusinessFunctionValue sets BusinessFunctionValue field to given value.

### HasBusinessFunctionValue

`func (o *KeyMeasurablesApiGetMetricResponse) HasBusinessFunctionValue() bool`

HasBusinessFunctionValue returns a boolean if a field has been set.

### GetDataSetId

`func (o *KeyMeasurablesApiGetMetricResponse) GetDataSetId() string`

GetDataSetId returns the DataSetId field if non-nil, zero value otherwise.

### GetDataSetIdOk

`func (o *KeyMeasurablesApiGetMetricResponse) GetDataSetIdOk() (*string, bool)`

GetDataSetIdOk returns a tuple with the DataSetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataSetId

`func (o *KeyMeasurablesApiGetMetricResponse) SetDataSetId(v string)`

SetDataSetId sets DataSetId field to given value.

### HasDataSetId

`func (o *KeyMeasurablesApiGetMetricResponse) HasDataSetId() bool`

HasDataSetId returns a boolean if a field has been set.

### GetDataSetName

`func (o *KeyMeasurablesApiGetMetricResponse) GetDataSetName() string`

GetDataSetName returns the DataSetName field if non-nil, zero value otherwise.

### GetDataSetNameOk

`func (o *KeyMeasurablesApiGetMetricResponse) GetDataSetNameOk() (*string, bool)`

GetDataSetNameOk returns a tuple with the DataSetName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataSetName

`func (o *KeyMeasurablesApiGetMetricResponse) SetDataSetName(v string)`

SetDataSetName sets DataSetName field to given value.

### HasDataSetName

`func (o *KeyMeasurablesApiGetMetricResponse) HasDataSetName() bool`

HasDataSetName returns a boolean if a field has been set.

### GetDataSetPeriodValue

`func (o *KeyMeasurablesApiGetMetricResponse) GetDataSetPeriodValue() string`

GetDataSetPeriodValue returns the DataSetPeriodValue field if non-nil, zero value otherwise.

### GetDataSetPeriodValueOk

`func (o *KeyMeasurablesApiGetMetricResponse) GetDataSetPeriodValueOk() (*string, bool)`

GetDataSetPeriodValueOk returns a tuple with the DataSetPeriodValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataSetPeriodValue

`func (o *KeyMeasurablesApiGetMetricResponse) SetDataSetPeriodValue(v string)`

SetDataSetPeriodValue sets DataSetPeriodValue field to given value.

### HasDataSetPeriodValue

`func (o *KeyMeasurablesApiGetMetricResponse) HasDataSetPeriodValue() bool`

HasDataSetPeriodValue returns a boolean if a field has been set.

### GetMeasureId

`func (o *KeyMeasurablesApiGetMetricResponse) GetMeasureId() string`

GetMeasureId returns the MeasureId field if non-nil, zero value otherwise.

### GetMeasureIdOk

`func (o *KeyMeasurablesApiGetMetricResponse) GetMeasureIdOk() (*string, bool)`

GetMeasureIdOk returns a tuple with the MeasureId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeasureId

`func (o *KeyMeasurablesApiGetMetricResponse) SetMeasureId(v string)`

SetMeasureId sets MeasureId field to given value.

### HasMeasureId

`func (o *KeyMeasurablesApiGetMetricResponse) HasMeasureId() bool`

HasMeasureId returns a boolean if a field has been set.

### GetMeasureName

`func (o *KeyMeasurablesApiGetMetricResponse) GetMeasureName() string`

GetMeasureName returns the MeasureName field if non-nil, zero value otherwise.

### GetMeasureNameOk

`func (o *KeyMeasurablesApiGetMetricResponse) GetMeasureNameOk() (*string, bool)`

GetMeasureNameOk returns a tuple with the MeasureName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeasureName

`func (o *KeyMeasurablesApiGetMetricResponse) SetMeasureName(v string)`

SetMeasureName sets MeasureName field to given value.

### HasMeasureName

`func (o *KeyMeasurablesApiGetMetricResponse) HasMeasureName() bool`

HasMeasureName returns a boolean if a field has been set.

### GetUnit

`func (o *KeyMeasurablesApiGetMetricResponse) GetUnit() string`

GetUnit returns the Unit field if non-nil, zero value otherwise.

### GetUnitOk

`func (o *KeyMeasurablesApiGetMetricResponse) GetUnitOk() (*string, bool)`

GetUnitOk returns a tuple with the Unit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnit

`func (o *KeyMeasurablesApiGetMetricResponse) SetUnit(v string)`

SetUnit sets Unit field to given value.

### HasUnit

`func (o *KeyMeasurablesApiGetMetricResponse) HasUnit() bool`

HasUnit returns a boolean if a field has been set.

### GetFrequencyId

`func (o *KeyMeasurablesApiGetMetricResponse) GetFrequencyId() string`

GetFrequencyId returns the FrequencyId field if non-nil, zero value otherwise.

### GetFrequencyIdOk

`func (o *KeyMeasurablesApiGetMetricResponse) GetFrequencyIdOk() (*string, bool)`

GetFrequencyIdOk returns a tuple with the FrequencyId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrequencyId

`func (o *KeyMeasurablesApiGetMetricResponse) SetFrequencyId(v string)`

SetFrequencyId sets FrequencyId field to given value.

### HasFrequencyId

`func (o *KeyMeasurablesApiGetMetricResponse) HasFrequencyId() bool`

HasFrequencyId returns a boolean if a field has been set.

### GetFrequencyDescription

`func (o *KeyMeasurablesApiGetMetricResponse) GetFrequencyDescription() string`

GetFrequencyDescription returns the FrequencyDescription field if non-nil, zero value otherwise.

### GetFrequencyDescriptionOk

`func (o *KeyMeasurablesApiGetMetricResponse) GetFrequencyDescriptionOk() (*string, bool)`

GetFrequencyDescriptionOk returns a tuple with the FrequencyDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrequencyDescription

`func (o *KeyMeasurablesApiGetMetricResponse) SetFrequencyDescription(v string)`

SetFrequencyDescription sets FrequencyDescription field to given value.

### HasFrequencyDescription

`func (o *KeyMeasurablesApiGetMetricResponse) HasFrequencyDescription() bool`

HasFrequencyDescription returns a boolean if a field has been set.

### GetFrequencyMethodName

`func (o *KeyMeasurablesApiGetMetricResponse) GetFrequencyMethodName() string`

GetFrequencyMethodName returns the FrequencyMethodName field if non-nil, zero value otherwise.

### GetFrequencyMethodNameOk

`func (o *KeyMeasurablesApiGetMetricResponse) GetFrequencyMethodNameOk() (*string, bool)`

GetFrequencyMethodNameOk returns a tuple with the FrequencyMethodName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrequencyMethodName

`func (o *KeyMeasurablesApiGetMetricResponse) SetFrequencyMethodName(v string)`

SetFrequencyMethodName sets FrequencyMethodName field to given value.

### HasFrequencyMethodName

`func (o *KeyMeasurablesApiGetMetricResponse) HasFrequencyMethodName() bool`

HasFrequencyMethodName returns a boolean if a field has been set.

### GetDimensionId

`func (o *KeyMeasurablesApiGetMetricResponse) GetDimensionId() string`

GetDimensionId returns the DimensionId field if non-nil, zero value otherwise.

### GetDimensionIdOk

`func (o *KeyMeasurablesApiGetMetricResponse) GetDimensionIdOk() (*string, bool)`

GetDimensionIdOk returns a tuple with the DimensionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDimensionId

`func (o *KeyMeasurablesApiGetMetricResponse) SetDimensionId(v string)`

SetDimensionId sets DimensionId field to given value.

### HasDimensionId

`func (o *KeyMeasurablesApiGetMetricResponse) HasDimensionId() bool`

HasDimensionId returns a boolean if a field has been set.

### GetDimensionDescription

`func (o *KeyMeasurablesApiGetMetricResponse) GetDimensionDescription() string`

GetDimensionDescription returns the DimensionDescription field if non-nil, zero value otherwise.

### GetDimensionDescriptionOk

`func (o *KeyMeasurablesApiGetMetricResponse) GetDimensionDescriptionOk() (*string, bool)`

GetDimensionDescriptionOk returns a tuple with the DimensionDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDimensionDescription

`func (o *KeyMeasurablesApiGetMetricResponse) SetDimensionDescription(v string)`

SetDimensionDescription sets DimensionDescription field to given value.

### HasDimensionDescription

`func (o *KeyMeasurablesApiGetMetricResponse) HasDimensionDescription() bool`

HasDimensionDescription returns a boolean if a field has been set.

### GetNumberOfDimensionValues

`func (o *KeyMeasurablesApiGetMetricResponse) GetNumberOfDimensionValues() int32`

GetNumberOfDimensionValues returns the NumberOfDimensionValues field if non-nil, zero value otherwise.

### GetNumberOfDimensionValuesOk

`func (o *KeyMeasurablesApiGetMetricResponse) GetNumberOfDimensionValuesOk() (*int32, bool)`

GetNumberOfDimensionValuesOk returns a tuple with the NumberOfDimensionValues field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumberOfDimensionValues

`func (o *KeyMeasurablesApiGetMetricResponse) SetNumberOfDimensionValues(v int32)`

SetNumberOfDimensionValues sets NumberOfDimensionValues field to given value.

### HasNumberOfDimensionValues

`func (o *KeyMeasurablesApiGetMetricResponse) HasNumberOfDimensionValues() bool`

HasNumberOfDimensionValues returns a boolean if a field has been set.

### GetDisplayTopBottomName

`func (o *KeyMeasurablesApiGetMetricResponse) GetDisplayTopBottomName() string`

GetDisplayTopBottomName returns the DisplayTopBottomName field if non-nil, zero value otherwise.

### GetDisplayTopBottomNameOk

`func (o *KeyMeasurablesApiGetMetricResponse) GetDisplayTopBottomNameOk() (*string, bool)`

GetDisplayTopBottomNameOk returns a tuple with the DisplayTopBottomName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplayTopBottomName

`func (o *KeyMeasurablesApiGetMetricResponse) SetDisplayTopBottomName(v string)`

SetDisplayTopBottomName sets DisplayTopBottomName field to given value.

### HasDisplayTopBottomName

`func (o *KeyMeasurablesApiGetMetricResponse) HasDisplayTopBottomName() bool`

HasDisplayTopBottomName returns a boolean if a field has been set.

### GetBenchmarkType

`func (o *KeyMeasurablesApiGetMetricResponse) GetBenchmarkType() string`

GetBenchmarkType returns the BenchmarkType field if non-nil, zero value otherwise.

### GetBenchmarkTypeOk

`func (o *KeyMeasurablesApiGetMetricResponse) GetBenchmarkTypeOk() (*string, bool)`

GetBenchmarkTypeOk returns a tuple with the BenchmarkType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBenchmarkType

`func (o *KeyMeasurablesApiGetMetricResponse) SetBenchmarkType(v string)`

SetBenchmarkType sets BenchmarkType field to given value.

### HasBenchmarkType

`func (o *KeyMeasurablesApiGetMetricResponse) HasBenchmarkType() bool`

HasBenchmarkType returns a boolean if a field has been set.

### GetSuccessIndicatorName

`func (o *KeyMeasurablesApiGetMetricResponse) GetSuccessIndicatorName() string`

GetSuccessIndicatorName returns the SuccessIndicatorName field if non-nil, zero value otherwise.

### GetSuccessIndicatorNameOk

`func (o *KeyMeasurablesApiGetMetricResponse) GetSuccessIndicatorNameOk() (*string, bool)`

GetSuccessIndicatorNameOk returns a tuple with the SuccessIndicatorName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccessIndicatorName

`func (o *KeyMeasurablesApiGetMetricResponse) SetSuccessIndicatorName(v string)`

SetSuccessIndicatorName sets SuccessIndicatorName field to given value.

### HasSuccessIndicatorName

`func (o *KeyMeasurablesApiGetMetricResponse) HasSuccessIndicatorName() bool`

HasSuccessIndicatorName returns a boolean if a field has been set.

### GetBenchmarks

`func (o *KeyMeasurablesApiGetMetricResponse) GetBenchmarks() []string`

GetBenchmarks returns the Benchmarks field if non-nil, zero value otherwise.

### GetBenchmarksOk

`func (o *KeyMeasurablesApiGetMetricResponse) GetBenchmarksOk() (*[]string, bool)`

GetBenchmarksOk returns a tuple with the Benchmarks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBenchmarks

`func (o *KeyMeasurablesApiGetMetricResponse) SetBenchmarks(v []string)`

SetBenchmarks sets Benchmarks field to given value.

### HasBenchmarks

`func (o *KeyMeasurablesApiGetMetricResponse) HasBenchmarks() bool`

HasBenchmarks returns a boolean if a field has been set.

### GetStrategicObjectives

`func (o *KeyMeasurablesApiGetMetricResponse) GetStrategicObjectives() []int32`

GetStrategicObjectives returns the StrategicObjectives field if non-nil, zero value otherwise.

### GetStrategicObjectivesOk

`func (o *KeyMeasurablesApiGetMetricResponse) GetStrategicObjectivesOk() (*[]int32, bool)`

GetStrategicObjectivesOk returns a tuple with the StrategicObjectives field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStrategicObjectives

`func (o *KeyMeasurablesApiGetMetricResponse) SetStrategicObjectives(v []int32)`

SetStrategicObjectives sets StrategicObjectives field to given value.

### HasStrategicObjectives

`func (o *KeyMeasurablesApiGetMetricResponse) HasStrategicObjectives() bool`

HasStrategicObjectives returns a boolean if a field has been set.

### GetCreatedBy

`func (o *KeyMeasurablesApiGetMetricResponse) GetCreatedBy() string`

GetCreatedBy returns the CreatedBy field if non-nil, zero value otherwise.

### GetCreatedByOk

`func (o *KeyMeasurablesApiGetMetricResponse) GetCreatedByOk() (*string, bool)`

GetCreatedByOk returns a tuple with the CreatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedBy

`func (o *KeyMeasurablesApiGetMetricResponse) SetCreatedBy(v string)`

SetCreatedBy sets CreatedBy field to given value.

### HasCreatedBy

`func (o *KeyMeasurablesApiGetMetricResponse) HasCreatedBy() bool`

HasCreatedBy returns a boolean if a field has been set.

### GetCreatedDateTime

`func (o *KeyMeasurablesApiGetMetricResponse) GetCreatedDateTime() time.Time`

GetCreatedDateTime returns the CreatedDateTime field if non-nil, zero value otherwise.

### GetCreatedDateTimeOk

`func (o *KeyMeasurablesApiGetMetricResponse) GetCreatedDateTimeOk() (*time.Time, bool)`

GetCreatedDateTimeOk returns a tuple with the CreatedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDateTime

`func (o *KeyMeasurablesApiGetMetricResponse) SetCreatedDateTime(v time.Time)`

SetCreatedDateTime sets CreatedDateTime field to given value.

### HasCreatedDateTime

`func (o *KeyMeasurablesApiGetMetricResponse) HasCreatedDateTime() bool`

HasCreatedDateTime returns a boolean if a field has been set.

### GetLastModifiedBy

`func (o *KeyMeasurablesApiGetMetricResponse) GetLastModifiedBy() string`

GetLastModifiedBy returns the LastModifiedBy field if non-nil, zero value otherwise.

### GetLastModifiedByOk

`func (o *KeyMeasurablesApiGetMetricResponse) GetLastModifiedByOk() (*string, bool)`

GetLastModifiedByOk returns a tuple with the LastModifiedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastModifiedBy

`func (o *KeyMeasurablesApiGetMetricResponse) SetLastModifiedBy(v string)`

SetLastModifiedBy sets LastModifiedBy field to given value.

### HasLastModifiedBy

`func (o *KeyMeasurablesApiGetMetricResponse) HasLastModifiedBy() bool`

HasLastModifiedBy returns a boolean if a field has been set.

### GetLastModifiedDateTime

`func (o *KeyMeasurablesApiGetMetricResponse) GetLastModifiedDateTime() time.Time`

GetLastModifiedDateTime returns the LastModifiedDateTime field if non-nil, zero value otherwise.

### GetLastModifiedDateTimeOk

`func (o *KeyMeasurablesApiGetMetricResponse) GetLastModifiedDateTimeOk() (*time.Time, bool)`

GetLastModifiedDateTimeOk returns a tuple with the LastModifiedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastModifiedDateTime

`func (o *KeyMeasurablesApiGetMetricResponse) SetLastModifiedDateTime(v time.Time)`

SetLastModifiedDateTime sets LastModifiedDateTime field to given value.

### HasLastModifiedDateTime

`func (o *KeyMeasurablesApiGetMetricResponse) HasLastModifiedDateTime() bool`

HasLastModifiedDateTime returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


