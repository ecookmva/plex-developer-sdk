# PlexApmApiGetAssetNumericalDataItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ReceivedISOTimestamp** | Pointer to **time.Time** | ISO Timestamp of the data | [optional] 
**ReceivedUnixTimestamp** | Pointer to **int64** | 13 digit UNIX timestamp of the data | [optional] 
**Source** | Pointer to **string** | Source of the data. | [optional] 
**GatewayId** | Pointer to **string** | Gateway Identifier | [optional] 
**Asset** | Pointer to **string** | If the asset has a name, the name is returned else the asset code is returned | [optional] 
**TagName** | Pointer to **string** | Tag Name | [optional] 
**TagAlias** | Pointer to **string** | Tag Alias | [optional] 
**Value** | Pointer to **float64** | Value. NaN if not a valid number | [optional] 
**Quality** | Pointer to **string** | Quality of the data - Good/Bad | [optional] 

## Methods

### NewPlexApmApiGetAssetNumericalDataItem

`func NewPlexApmApiGetAssetNumericalDataItem() *PlexApmApiGetAssetNumericalDataItem`

NewPlexApmApiGetAssetNumericalDataItem instantiates a new PlexApmApiGetAssetNumericalDataItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPlexApmApiGetAssetNumericalDataItemWithDefaults

`func NewPlexApmApiGetAssetNumericalDataItemWithDefaults() *PlexApmApiGetAssetNumericalDataItem`

NewPlexApmApiGetAssetNumericalDataItemWithDefaults instantiates a new PlexApmApiGetAssetNumericalDataItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetReceivedISOTimestamp

`func (o *PlexApmApiGetAssetNumericalDataItem) GetReceivedISOTimestamp() time.Time`

GetReceivedISOTimestamp returns the ReceivedISOTimestamp field if non-nil, zero value otherwise.

### GetReceivedISOTimestampOk

`func (o *PlexApmApiGetAssetNumericalDataItem) GetReceivedISOTimestampOk() (*time.Time, bool)`

GetReceivedISOTimestampOk returns a tuple with the ReceivedISOTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceivedISOTimestamp

`func (o *PlexApmApiGetAssetNumericalDataItem) SetReceivedISOTimestamp(v time.Time)`

SetReceivedISOTimestamp sets ReceivedISOTimestamp field to given value.

### HasReceivedISOTimestamp

`func (o *PlexApmApiGetAssetNumericalDataItem) HasReceivedISOTimestamp() bool`

HasReceivedISOTimestamp returns a boolean if a field has been set.

### GetReceivedUnixTimestamp

`func (o *PlexApmApiGetAssetNumericalDataItem) GetReceivedUnixTimestamp() int64`

GetReceivedUnixTimestamp returns the ReceivedUnixTimestamp field if non-nil, zero value otherwise.

### GetReceivedUnixTimestampOk

`func (o *PlexApmApiGetAssetNumericalDataItem) GetReceivedUnixTimestampOk() (*int64, bool)`

GetReceivedUnixTimestampOk returns a tuple with the ReceivedUnixTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceivedUnixTimestamp

`func (o *PlexApmApiGetAssetNumericalDataItem) SetReceivedUnixTimestamp(v int64)`

SetReceivedUnixTimestamp sets ReceivedUnixTimestamp field to given value.

### HasReceivedUnixTimestamp

`func (o *PlexApmApiGetAssetNumericalDataItem) HasReceivedUnixTimestamp() bool`

HasReceivedUnixTimestamp returns a boolean if a field has been set.

### GetSource

`func (o *PlexApmApiGetAssetNumericalDataItem) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *PlexApmApiGetAssetNumericalDataItem) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *PlexApmApiGetAssetNumericalDataItem) SetSource(v string)`

SetSource sets Source field to given value.

### HasSource

`func (o *PlexApmApiGetAssetNumericalDataItem) HasSource() bool`

HasSource returns a boolean if a field has been set.

### GetGatewayId

`func (o *PlexApmApiGetAssetNumericalDataItem) GetGatewayId() string`

GetGatewayId returns the GatewayId field if non-nil, zero value otherwise.

### GetGatewayIdOk

`func (o *PlexApmApiGetAssetNumericalDataItem) GetGatewayIdOk() (*string, bool)`

GetGatewayIdOk returns a tuple with the GatewayId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGatewayId

`func (o *PlexApmApiGetAssetNumericalDataItem) SetGatewayId(v string)`

SetGatewayId sets GatewayId field to given value.

### HasGatewayId

`func (o *PlexApmApiGetAssetNumericalDataItem) HasGatewayId() bool`

HasGatewayId returns a boolean if a field has been set.

### GetAsset

`func (o *PlexApmApiGetAssetNumericalDataItem) GetAsset() string`

GetAsset returns the Asset field if non-nil, zero value otherwise.

### GetAssetOk

`func (o *PlexApmApiGetAssetNumericalDataItem) GetAssetOk() (*string, bool)`

GetAssetOk returns a tuple with the Asset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAsset

`func (o *PlexApmApiGetAssetNumericalDataItem) SetAsset(v string)`

SetAsset sets Asset field to given value.

### HasAsset

`func (o *PlexApmApiGetAssetNumericalDataItem) HasAsset() bool`

HasAsset returns a boolean if a field has been set.

### GetTagName

`func (o *PlexApmApiGetAssetNumericalDataItem) GetTagName() string`

GetTagName returns the TagName field if non-nil, zero value otherwise.

### GetTagNameOk

`func (o *PlexApmApiGetAssetNumericalDataItem) GetTagNameOk() (*string, bool)`

GetTagNameOk returns a tuple with the TagName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTagName

`func (o *PlexApmApiGetAssetNumericalDataItem) SetTagName(v string)`

SetTagName sets TagName field to given value.

### HasTagName

`func (o *PlexApmApiGetAssetNumericalDataItem) HasTagName() bool`

HasTagName returns a boolean if a field has been set.

### GetTagAlias

`func (o *PlexApmApiGetAssetNumericalDataItem) GetTagAlias() string`

GetTagAlias returns the TagAlias field if non-nil, zero value otherwise.

### GetTagAliasOk

`func (o *PlexApmApiGetAssetNumericalDataItem) GetTagAliasOk() (*string, bool)`

GetTagAliasOk returns a tuple with the TagAlias field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTagAlias

`func (o *PlexApmApiGetAssetNumericalDataItem) SetTagAlias(v string)`

SetTagAlias sets TagAlias field to given value.

### HasTagAlias

`func (o *PlexApmApiGetAssetNumericalDataItem) HasTagAlias() bool`

HasTagAlias returns a boolean if a field has been set.

### GetValue

`func (o *PlexApmApiGetAssetNumericalDataItem) GetValue() float64`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *PlexApmApiGetAssetNumericalDataItem) GetValueOk() (*float64, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *PlexApmApiGetAssetNumericalDataItem) SetValue(v float64)`

SetValue sets Value field to given value.

### HasValue

`func (o *PlexApmApiGetAssetNumericalDataItem) HasValue() bool`

HasValue returns a boolean if a field has been set.

### GetQuality

`func (o *PlexApmApiGetAssetNumericalDataItem) GetQuality() string`

GetQuality returns the Quality field if non-nil, zero value otherwise.

### GetQualityOk

`func (o *PlexApmApiGetAssetNumericalDataItem) GetQualityOk() (*string, bool)`

GetQualityOk returns a tuple with the Quality field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuality

`func (o *PlexApmApiGetAssetNumericalDataItem) SetQuality(v string)`

SetQuality sets Quality field to given value.

### HasQuality

`func (o *PlexApmApiGetAssetNumericalDataItem) HasQuality() bool`

HasQuality returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


