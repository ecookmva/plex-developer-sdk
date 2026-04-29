# PlexApmOdataApiGetTagDataResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssetName** | Pointer to **string** | If the asset has a name, the name is returned, else the asset name is empty. If the asset is deleted, &amp;quot;Asset Deleted&amp;quot; is returned as a placeholder. | [optional] 
**AssetCode** | Pointer to **string** | If the asset exists, asset code will be returned, else &amp;quot;Asset Deleted&amp;quot; is returned as a placeholder. | [optional] 
**TagName** | Pointer to **string** | Tag Name. | [optional] 
**TagAlias** | Pointer to **string** | Returns tag alias provided by you in Plex APM. | [optional] 
**DataType** | Pointer to **string** | Returns tag data type as - Boolean, Numerical, String. | [optional] 
**StreamType** | Pointer to **string** | Returns tag stream type defined in Plex APM. | [optional] 
**Value** | Pointer to **string** | Returns value of the tag as - true/false or number or string text. | [optional] 
**Source** | Pointer to **string** | Returns source of the tag as defined in Plex APM. | [optional] 
**GatewayName** | Pointer to **string** | Returns gateway name of the tag. If the gateway is deleted, &amp;quot;Gateway Deleted&amp;quot; is returned as a placeholder. | [optional] 
**GatewayId** | Pointer to **string** | Returns gateway ID of the tag. If the gateway is deleted, &amp;quot;Gateway Deleted&amp;quot; is returned as a placeholder. | [optional] 
**MeasuringUnit** | Pointer to **string** | If unit of measure is assigned to a numeric tag, the unit of measure is returned else No Unit(NONE) is returned as a placeholder. Null is returned for boolean and string tag. | [optional] 
**Quality** | Pointer to **string** | Returns quality of the tag - Good/Bad. | [optional] 
**Severity** | Pointer to **string** | Returns severity as defined in Plex APM for boolean tag. Null is returned for numeric and string tag. | [optional] 
**EventReason** | Pointer to **string** | If event reason is assigned to a boolean tag, the event reason is returned else null is returned as a placeholder. Null is returned for numeric and string tag. | [optional] 
**ReceivedISOTimestamp** | Pointer to **string** | Received timestamp of the event. | [optional] 
**StartDateTime** | Pointer to **string** | The response will always have StartDateTime returned 0001-01-01T00:00:00Z as a placeholder as tag does not have a start time. | [optional] 
**EndDateTime** | Pointer to **string** | The response will always have EndDateTime returned 0001-01-01T00:00:00Z as a placeholder as tag does not have an end time. | [optional] 

## Methods

### NewPlexApmOdataApiGetTagDataResponse

`func NewPlexApmOdataApiGetTagDataResponse() *PlexApmOdataApiGetTagDataResponse`

NewPlexApmOdataApiGetTagDataResponse instantiates a new PlexApmOdataApiGetTagDataResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPlexApmOdataApiGetTagDataResponseWithDefaults

`func NewPlexApmOdataApiGetTagDataResponseWithDefaults() *PlexApmOdataApiGetTagDataResponse`

NewPlexApmOdataApiGetTagDataResponseWithDefaults instantiates a new PlexApmOdataApiGetTagDataResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssetName

`func (o *PlexApmOdataApiGetTagDataResponse) GetAssetName() string`

GetAssetName returns the AssetName field if non-nil, zero value otherwise.

### GetAssetNameOk

`func (o *PlexApmOdataApiGetTagDataResponse) GetAssetNameOk() (*string, bool)`

GetAssetNameOk returns a tuple with the AssetName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetName

`func (o *PlexApmOdataApiGetTagDataResponse) SetAssetName(v string)`

SetAssetName sets AssetName field to given value.

### HasAssetName

`func (o *PlexApmOdataApiGetTagDataResponse) HasAssetName() bool`

HasAssetName returns a boolean if a field has been set.

### GetAssetCode

`func (o *PlexApmOdataApiGetTagDataResponse) GetAssetCode() string`

GetAssetCode returns the AssetCode field if non-nil, zero value otherwise.

### GetAssetCodeOk

`func (o *PlexApmOdataApiGetTagDataResponse) GetAssetCodeOk() (*string, bool)`

GetAssetCodeOk returns a tuple with the AssetCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetCode

`func (o *PlexApmOdataApiGetTagDataResponse) SetAssetCode(v string)`

SetAssetCode sets AssetCode field to given value.

### HasAssetCode

`func (o *PlexApmOdataApiGetTagDataResponse) HasAssetCode() bool`

HasAssetCode returns a boolean if a field has been set.

### GetTagName

`func (o *PlexApmOdataApiGetTagDataResponse) GetTagName() string`

GetTagName returns the TagName field if non-nil, zero value otherwise.

### GetTagNameOk

`func (o *PlexApmOdataApiGetTagDataResponse) GetTagNameOk() (*string, bool)`

GetTagNameOk returns a tuple with the TagName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTagName

`func (o *PlexApmOdataApiGetTagDataResponse) SetTagName(v string)`

SetTagName sets TagName field to given value.

### HasTagName

`func (o *PlexApmOdataApiGetTagDataResponse) HasTagName() bool`

HasTagName returns a boolean if a field has been set.

### GetTagAlias

`func (o *PlexApmOdataApiGetTagDataResponse) GetTagAlias() string`

GetTagAlias returns the TagAlias field if non-nil, zero value otherwise.

### GetTagAliasOk

`func (o *PlexApmOdataApiGetTagDataResponse) GetTagAliasOk() (*string, bool)`

GetTagAliasOk returns a tuple with the TagAlias field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTagAlias

`func (o *PlexApmOdataApiGetTagDataResponse) SetTagAlias(v string)`

SetTagAlias sets TagAlias field to given value.

### HasTagAlias

`func (o *PlexApmOdataApiGetTagDataResponse) HasTagAlias() bool`

HasTagAlias returns a boolean if a field has been set.

### GetDataType

`func (o *PlexApmOdataApiGetTagDataResponse) GetDataType() string`

GetDataType returns the DataType field if non-nil, zero value otherwise.

### GetDataTypeOk

`func (o *PlexApmOdataApiGetTagDataResponse) GetDataTypeOk() (*string, bool)`

GetDataTypeOk returns a tuple with the DataType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataType

`func (o *PlexApmOdataApiGetTagDataResponse) SetDataType(v string)`

SetDataType sets DataType field to given value.

### HasDataType

`func (o *PlexApmOdataApiGetTagDataResponse) HasDataType() bool`

HasDataType returns a boolean if a field has been set.

### GetStreamType

`func (o *PlexApmOdataApiGetTagDataResponse) GetStreamType() string`

GetStreamType returns the StreamType field if non-nil, zero value otherwise.

### GetStreamTypeOk

`func (o *PlexApmOdataApiGetTagDataResponse) GetStreamTypeOk() (*string, bool)`

GetStreamTypeOk returns a tuple with the StreamType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStreamType

`func (o *PlexApmOdataApiGetTagDataResponse) SetStreamType(v string)`

SetStreamType sets StreamType field to given value.

### HasStreamType

`func (o *PlexApmOdataApiGetTagDataResponse) HasStreamType() bool`

HasStreamType returns a boolean if a field has been set.

### GetValue

`func (o *PlexApmOdataApiGetTagDataResponse) GetValue() string`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *PlexApmOdataApiGetTagDataResponse) GetValueOk() (*string, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *PlexApmOdataApiGetTagDataResponse) SetValue(v string)`

SetValue sets Value field to given value.

### HasValue

`func (o *PlexApmOdataApiGetTagDataResponse) HasValue() bool`

HasValue returns a boolean if a field has been set.

### GetSource

`func (o *PlexApmOdataApiGetTagDataResponse) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *PlexApmOdataApiGetTagDataResponse) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *PlexApmOdataApiGetTagDataResponse) SetSource(v string)`

SetSource sets Source field to given value.

### HasSource

`func (o *PlexApmOdataApiGetTagDataResponse) HasSource() bool`

HasSource returns a boolean if a field has been set.

### GetGatewayName

`func (o *PlexApmOdataApiGetTagDataResponse) GetGatewayName() string`

GetGatewayName returns the GatewayName field if non-nil, zero value otherwise.

### GetGatewayNameOk

`func (o *PlexApmOdataApiGetTagDataResponse) GetGatewayNameOk() (*string, bool)`

GetGatewayNameOk returns a tuple with the GatewayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGatewayName

`func (o *PlexApmOdataApiGetTagDataResponse) SetGatewayName(v string)`

SetGatewayName sets GatewayName field to given value.

### HasGatewayName

`func (o *PlexApmOdataApiGetTagDataResponse) HasGatewayName() bool`

HasGatewayName returns a boolean if a field has been set.

### GetGatewayId

`func (o *PlexApmOdataApiGetTagDataResponse) GetGatewayId() string`

GetGatewayId returns the GatewayId field if non-nil, zero value otherwise.

### GetGatewayIdOk

`func (o *PlexApmOdataApiGetTagDataResponse) GetGatewayIdOk() (*string, bool)`

GetGatewayIdOk returns a tuple with the GatewayId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGatewayId

`func (o *PlexApmOdataApiGetTagDataResponse) SetGatewayId(v string)`

SetGatewayId sets GatewayId field to given value.

### HasGatewayId

`func (o *PlexApmOdataApiGetTagDataResponse) HasGatewayId() bool`

HasGatewayId returns a boolean if a field has been set.

### GetMeasuringUnit

`func (o *PlexApmOdataApiGetTagDataResponse) GetMeasuringUnit() string`

GetMeasuringUnit returns the MeasuringUnit field if non-nil, zero value otherwise.

### GetMeasuringUnitOk

`func (o *PlexApmOdataApiGetTagDataResponse) GetMeasuringUnitOk() (*string, bool)`

GetMeasuringUnitOk returns a tuple with the MeasuringUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeasuringUnit

`func (o *PlexApmOdataApiGetTagDataResponse) SetMeasuringUnit(v string)`

SetMeasuringUnit sets MeasuringUnit field to given value.

### HasMeasuringUnit

`func (o *PlexApmOdataApiGetTagDataResponse) HasMeasuringUnit() bool`

HasMeasuringUnit returns a boolean if a field has been set.

### GetQuality

`func (o *PlexApmOdataApiGetTagDataResponse) GetQuality() string`

GetQuality returns the Quality field if non-nil, zero value otherwise.

### GetQualityOk

`func (o *PlexApmOdataApiGetTagDataResponse) GetQualityOk() (*string, bool)`

GetQualityOk returns a tuple with the Quality field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuality

`func (o *PlexApmOdataApiGetTagDataResponse) SetQuality(v string)`

SetQuality sets Quality field to given value.

### HasQuality

`func (o *PlexApmOdataApiGetTagDataResponse) HasQuality() bool`

HasQuality returns a boolean if a field has been set.

### GetSeverity

`func (o *PlexApmOdataApiGetTagDataResponse) GetSeverity() string`

GetSeverity returns the Severity field if non-nil, zero value otherwise.

### GetSeverityOk

`func (o *PlexApmOdataApiGetTagDataResponse) GetSeverityOk() (*string, bool)`

GetSeverityOk returns a tuple with the Severity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeverity

`func (o *PlexApmOdataApiGetTagDataResponse) SetSeverity(v string)`

SetSeverity sets Severity field to given value.

### HasSeverity

`func (o *PlexApmOdataApiGetTagDataResponse) HasSeverity() bool`

HasSeverity returns a boolean if a field has been set.

### GetEventReason

`func (o *PlexApmOdataApiGetTagDataResponse) GetEventReason() string`

GetEventReason returns the EventReason field if non-nil, zero value otherwise.

### GetEventReasonOk

`func (o *PlexApmOdataApiGetTagDataResponse) GetEventReasonOk() (*string, bool)`

GetEventReasonOk returns a tuple with the EventReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventReason

`func (o *PlexApmOdataApiGetTagDataResponse) SetEventReason(v string)`

SetEventReason sets EventReason field to given value.

### HasEventReason

`func (o *PlexApmOdataApiGetTagDataResponse) HasEventReason() bool`

HasEventReason returns a boolean if a field has been set.

### GetReceivedISOTimestamp

`func (o *PlexApmOdataApiGetTagDataResponse) GetReceivedISOTimestamp() string`

GetReceivedISOTimestamp returns the ReceivedISOTimestamp field if non-nil, zero value otherwise.

### GetReceivedISOTimestampOk

`func (o *PlexApmOdataApiGetTagDataResponse) GetReceivedISOTimestampOk() (*string, bool)`

GetReceivedISOTimestampOk returns a tuple with the ReceivedISOTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceivedISOTimestamp

`func (o *PlexApmOdataApiGetTagDataResponse) SetReceivedISOTimestamp(v string)`

SetReceivedISOTimestamp sets ReceivedISOTimestamp field to given value.

### HasReceivedISOTimestamp

`func (o *PlexApmOdataApiGetTagDataResponse) HasReceivedISOTimestamp() bool`

HasReceivedISOTimestamp returns a boolean if a field has been set.

### GetStartDateTime

`func (o *PlexApmOdataApiGetTagDataResponse) GetStartDateTime() string`

GetStartDateTime returns the StartDateTime field if non-nil, zero value otherwise.

### GetStartDateTimeOk

`func (o *PlexApmOdataApiGetTagDataResponse) GetStartDateTimeOk() (*string, bool)`

GetStartDateTimeOk returns a tuple with the StartDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartDateTime

`func (o *PlexApmOdataApiGetTagDataResponse) SetStartDateTime(v string)`

SetStartDateTime sets StartDateTime field to given value.

### HasStartDateTime

`func (o *PlexApmOdataApiGetTagDataResponse) HasStartDateTime() bool`

HasStartDateTime returns a boolean if a field has been set.

### GetEndDateTime

`func (o *PlexApmOdataApiGetTagDataResponse) GetEndDateTime() string`

GetEndDateTime returns the EndDateTime field if non-nil, zero value otherwise.

### GetEndDateTimeOk

`func (o *PlexApmOdataApiGetTagDataResponse) GetEndDateTimeOk() (*string, bool)`

GetEndDateTimeOk returns a tuple with the EndDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndDateTime

`func (o *PlexApmOdataApiGetTagDataResponse) SetEndDateTime(v string)`

SetEndDateTime sets EndDateTime field to given value.

### HasEndDateTime

`func (o *PlexApmOdataApiGetTagDataResponse) HasEndDateTime() bool`

HasEndDateTime returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


