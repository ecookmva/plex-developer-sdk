# PlexApmApiGetElapsedTimeByAssetsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssetCode** | Pointer to **string** | Asset code | [optional] 
**Results** | Pointer to [**[]ResultsItem**](ResultsItem.md) |  | [optional] 

## Methods

### NewPlexApmApiGetElapsedTimeByAssetsResponse

`func NewPlexApmApiGetElapsedTimeByAssetsResponse() *PlexApmApiGetElapsedTimeByAssetsResponse`

NewPlexApmApiGetElapsedTimeByAssetsResponse instantiates a new PlexApmApiGetElapsedTimeByAssetsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPlexApmApiGetElapsedTimeByAssetsResponseWithDefaults

`func NewPlexApmApiGetElapsedTimeByAssetsResponseWithDefaults() *PlexApmApiGetElapsedTimeByAssetsResponse`

NewPlexApmApiGetElapsedTimeByAssetsResponseWithDefaults instantiates a new PlexApmApiGetElapsedTimeByAssetsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssetCode

`func (o *PlexApmApiGetElapsedTimeByAssetsResponse) GetAssetCode() string`

GetAssetCode returns the AssetCode field if non-nil, zero value otherwise.

### GetAssetCodeOk

`func (o *PlexApmApiGetElapsedTimeByAssetsResponse) GetAssetCodeOk() (*string, bool)`

GetAssetCodeOk returns a tuple with the AssetCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetCode

`func (o *PlexApmApiGetElapsedTimeByAssetsResponse) SetAssetCode(v string)`

SetAssetCode sets AssetCode field to given value.

### HasAssetCode

`func (o *PlexApmApiGetElapsedTimeByAssetsResponse) HasAssetCode() bool`

HasAssetCode returns a boolean if a field has been set.

### GetResults

`func (o *PlexApmApiGetElapsedTimeByAssetsResponse) GetResults() []ResultsItem`

GetResults returns the Results field if non-nil, zero value otherwise.

### GetResultsOk

`func (o *PlexApmApiGetElapsedTimeByAssetsResponse) GetResultsOk() (*[]ResultsItem, bool)`

GetResultsOk returns a tuple with the Results field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResults

`func (o *PlexApmApiGetElapsedTimeByAssetsResponse) SetResults(v []ResultsItem)`

SetResults sets Results field to given value.

### HasResults

`func (o *PlexApmApiGetElapsedTimeByAssetsResponse) HasResults() bool`

HasResults returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


