# \PlexAPMAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**PlexApmApiGetAssetList**](PlexAPMAPIAPI.md#PlexApmApiGetAssetList) | **Get** /cm/exhaust/v1/assets | Get Asset List
[**PlexApmApiGetAssetNumericalData**](PlexAPMAPIAPI.md#PlexApmApiGetAssetNumericalData) | **Get** /cm/exhaust/v1/asset-data-points | Get Asset Numerical Data
[**PlexApmApiGetAssetStatuses**](PlexAPMAPIAPI.md#PlexApmApiGetAssetStatuses) | **Get** /cm/exhaust/v1/asset-statuses | Get Asset Statuses
[**PlexApmApiGetElapsedTimeByAssets**](PlexAPMAPIAPI.md#PlexApmApiGetElapsedTimeByAssets) | **Get** /cm/exhaust/v1/event/asset/elapsed-time | Get Elapsed Time By Assets
[**PlexApmApiGetElapsedTimeByTags**](PlexAPMAPIAPI.md#PlexApmApiGetElapsedTimeByTags) | **Get** /cm/exhaust/v1/event/tag/elapsed-time | Get Elapsed Time By Tags
[**PlexApmApiGetLatestTagValue**](PlexAPMAPIAPI.md#PlexApmApiGetLatestTagValue) | **Get** /cm/exhaust/v1/tags/values/latest | Get Latest Tag Value
[**PlexApmApiGetTagValueAtSpecifiedTime**](PlexAPMAPIAPI.md#PlexApmApiGetTagValueAtSpecifiedTime) | **Get** /cm/exhaust/v1/tags/values/{specificTime} | Get Tag Value At Specified Time



## PlexApmApiGetAssetList

> []PlexApmApiGetAssetListItem PlexApmApiGetAssetList(ctx).Enabled(enabled).AssetNames(assetNames).AssetCodes(assetCodes).AssetSerialNumbers(assetSerialNumbers).Descriptions(descriptions).GatewayIds(gatewayIds).GatewayNames(gatewayNames).FiixSiteNames(fiixSiteNames).FiixAssetNames(fiixAssetNames).PlexMaintenanceEquipmentIds(plexMaintenanceEquipmentIds).AssetBridgeAttributeName(assetBridgeAttributeName).BridgeAttributeValues(bridgeAttributeValues).AssetAttributeName(assetAttributeName).AssetAttributeValues(assetAttributeValues).Execute()

Get Asset List



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	enabled := "string" // string | True/False and it accepts either one. In case you want to fetch all assets keep this parameter blank. (optional)
	assetNames := "string" // string | Comma separated list of Asset names for which Asset records are required. Complete match is required. Invalid asset codes will be ignored and no records will be returned for them. (optional)
	assetCodes := "string" // string | Comma separated list of Asset codes for which status records are required. Complete match is required. Invalid asset codes will be ignored and no records will be returned for them. (optional)
	assetSerialNumbers := "string" // string | Comma separated list of Asset Serial Numbers for which assets records are required. Complete match is required. Invalid Asset Serial Numbers will be ignored and no records will be returned for them. (optional)
	descriptions := "string" // string | Comma separated list of Descriptions for which Asset records are required. Complete match is required. (optional)
	gatewayIds := "string" // string | Comma separated list of Gateway Ids for which Asset records are required. Complete match is required. Invalid asset codes will be ignored and no records will be returned for them. (optional)
	gatewayNames := "string" // string | Comma separated list of Gateway Names for which Asset records are required. Complete match is required. Invalid Gateway Names will be ignored and no records will be returned for them. (optional)
	fiixSiteNames := "string" // string | Comma separated list of Fiix Site Names for which Asset records are required. Complete match is required. Invalid Fiix Site Names will be ignored and no records will be returned for them. (optional)
	fiixAssetNames := "string" // string | Comma separated list of Fiix Asset Names for which Asset records are required. Complete match is required. Invalid Fiix Asset Names will be ignored and no records will be returned for them. (optional)
	plexMaintenanceEquipmentIds := "string" // string | Comma separated list of Plex Maintenance EquipmentIds for which Asset records are required. Complete match is required. Invalid Plex Maintenance EquipmentIds will be ignored and no records will be returned for them. (optional)
	assetBridgeAttributeName := "string" // string | Comma separated list of Asset Bridge Attribute Name for which Asset records are required. Complete match is required. Invalid Asset Bridge Attribute Name will be ignored and no records will be returned for them. (optional)
	bridgeAttributeValues := "string" // string | Comma separated list of Bridge Attribute Values for which Asset records are required. Complete match is required. Invalid Bridge Attribute Values will be ignored and no records will be returned for them. (optional)
	assetAttributeName := "string" // string | Comma separated list of Asset Attribute Name for which Asset records are required. Complete match is required. Invalid Asset Attribute Name will be ignored and no records will be returned for them. (optional)
	assetAttributeValues := "string" // string | Comma separated list of Asset Attribute Values for which Asset records are required. Complete match is required. Invalid asset codes will be ignored and no records will be returned for them. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PlexAPMAPIAPI.PlexApmApiGetAssetList(context.Background()).Enabled(enabled).AssetNames(assetNames).AssetCodes(assetCodes).AssetSerialNumbers(assetSerialNumbers).Descriptions(descriptions).GatewayIds(gatewayIds).GatewayNames(gatewayNames).FiixSiteNames(fiixSiteNames).FiixAssetNames(fiixAssetNames).PlexMaintenanceEquipmentIds(plexMaintenanceEquipmentIds).AssetBridgeAttributeName(assetBridgeAttributeName).BridgeAttributeValues(bridgeAttributeValues).AssetAttributeName(assetAttributeName).AssetAttributeValues(assetAttributeValues).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PlexAPMAPIAPI.PlexApmApiGetAssetList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PlexApmApiGetAssetList`: []PlexApmApiGetAssetListItem
	fmt.Fprintf(os.Stdout, "Response from `PlexAPMAPIAPI.PlexApmApiGetAssetList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPlexApmApiGetAssetListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **enabled** | **string** | True/False and it accepts either one. In case you want to fetch all assets keep this parameter blank. | 
 **assetNames** | **string** | Comma separated list of Asset names for which Asset records are required. Complete match is required. Invalid asset codes will be ignored and no records will be returned for them. | 
 **assetCodes** | **string** | Comma separated list of Asset codes for which status records are required. Complete match is required. Invalid asset codes will be ignored and no records will be returned for them. | 
 **assetSerialNumbers** | **string** | Comma separated list of Asset Serial Numbers for which assets records are required. Complete match is required. Invalid Asset Serial Numbers will be ignored and no records will be returned for them. | 
 **descriptions** | **string** | Comma separated list of Descriptions for which Asset records are required. Complete match is required. | 
 **gatewayIds** | **string** | Comma separated list of Gateway Ids for which Asset records are required. Complete match is required. Invalid asset codes will be ignored and no records will be returned for them. | 
 **gatewayNames** | **string** | Comma separated list of Gateway Names for which Asset records are required. Complete match is required. Invalid Gateway Names will be ignored and no records will be returned for them. | 
 **fiixSiteNames** | **string** | Comma separated list of Fiix Site Names for which Asset records are required. Complete match is required. Invalid Fiix Site Names will be ignored and no records will be returned for them. | 
 **fiixAssetNames** | **string** | Comma separated list of Fiix Asset Names for which Asset records are required. Complete match is required. Invalid Fiix Asset Names will be ignored and no records will be returned for them. | 
 **plexMaintenanceEquipmentIds** | **string** | Comma separated list of Plex Maintenance EquipmentIds for which Asset records are required. Complete match is required. Invalid Plex Maintenance EquipmentIds will be ignored and no records will be returned for them. | 
 **assetBridgeAttributeName** | **string** | Comma separated list of Asset Bridge Attribute Name for which Asset records are required. Complete match is required. Invalid Asset Bridge Attribute Name will be ignored and no records will be returned for them. | 
 **bridgeAttributeValues** | **string** | Comma separated list of Bridge Attribute Values for which Asset records are required. Complete match is required. Invalid Bridge Attribute Values will be ignored and no records will be returned for them. | 
 **assetAttributeName** | **string** | Comma separated list of Asset Attribute Name for which Asset records are required. Complete match is required. Invalid Asset Attribute Name will be ignored and no records will be returned for them. | 
 **assetAttributeValues** | **string** | Comma separated list of Asset Attribute Values for which Asset records are required. Complete match is required. Invalid asset codes will be ignored and no records will be returned for them. | 

### Return type

[**[]PlexApmApiGetAssetListItem**](PlexApmApiGetAssetListItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PlexApmApiGetAssetNumericalData

> []PlexApmApiGetAssetNumericalDataItem PlexApmApiGetAssetNumericalData(ctx).StartDate(startDate).EndDate(endDate).AssetCodes(assetCodes).TagNames(tagNames).DaysOfTheWeek(daysOfTheWeek).PeriodStartTime(periodStartTime).PeriodEndTime(periodEndTime).Quality(quality).SortOrder(sortOrder).Limit(limit).Execute()

Get Asset Numerical Data



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	startDate := time.Now() // time.Time | Start datetime for the query. Valid format: YYYY-MM-DDThh:mm:ss.fffffffZ
	endDate := time.Now() // time.Time | End datetime for the query. Valid format: YYYY-MM-DDThh:mm:ss.fffffffZ
	assetCodes := "string" // string | Comma separated list of Asset codes for which status records are required. Complete match is required. Invalid asset codes will be ignored and no records will be returned for them. (optional)
	tagNames := "string" // string | Comma separated list of tag names for which status records are required. Complete match is required. Invalid tag names will be ignored and no records will be returned for them. (optional)
	daysOfTheWeek := "string" // string | Comma separated list of Days of the week to include in the result. Valid values: Monday, Tuesday, Wednesday, Thursday, Friday, Saturday, Sunday (optional)
	periodStartTime := "string" // string | Start period of the results to be returned in HH:mm:ss format. Should be used along with periodEndTime. Example- '08:00:00' (optional)
	periodEndTime := "string" // string | End period of the results to be returned in HH:mm:ss format. Should be used along with periodStartTime. Example- '16:00:00' (optional)
	quality := "string" // string | Comma separated list of Event quality for which status records are required. Valid values are Good/Bad (optional)
	sortOrder := "string" // string | Sort order of status records by timestamp. Valid values: asc/desc. Default: desc (optional)
	limit := int32(0) // int32 | Top N records to return. Do not pass or pass 0 to return maximum allowed records (100,000) (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PlexAPMAPIAPI.PlexApmApiGetAssetNumericalData(context.Background()).StartDate(startDate).EndDate(endDate).AssetCodes(assetCodes).TagNames(tagNames).DaysOfTheWeek(daysOfTheWeek).PeriodStartTime(periodStartTime).PeriodEndTime(periodEndTime).Quality(quality).SortOrder(sortOrder).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PlexAPMAPIAPI.PlexApmApiGetAssetNumericalData``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PlexApmApiGetAssetNumericalData`: []PlexApmApiGetAssetNumericalDataItem
	fmt.Fprintf(os.Stdout, "Response from `PlexAPMAPIAPI.PlexApmApiGetAssetNumericalData`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPlexApmApiGetAssetNumericalDataRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **startDate** | **time.Time** | Start datetime for the query. Valid format: YYYY-MM-DDThh:mm:ss.fffffffZ | 
 **endDate** | **time.Time** | End datetime for the query. Valid format: YYYY-MM-DDThh:mm:ss.fffffffZ | 
 **assetCodes** | **string** | Comma separated list of Asset codes for which status records are required. Complete match is required. Invalid asset codes will be ignored and no records will be returned for them. | 
 **tagNames** | **string** | Comma separated list of tag names for which status records are required. Complete match is required. Invalid tag names will be ignored and no records will be returned for them. | 
 **daysOfTheWeek** | **string** | Comma separated list of Days of the week to include in the result. Valid values: Monday, Tuesday, Wednesday, Thursday, Friday, Saturday, Sunday | 
 **periodStartTime** | **string** | Start period of the results to be returned in HH:mm:ss format. Should be used along with periodEndTime. Example- &#39;08:00:00&#39; | 
 **periodEndTime** | **string** | End period of the results to be returned in HH:mm:ss format. Should be used along with periodStartTime. Example- &#39;16:00:00&#39; | 
 **quality** | **string** | Comma separated list of Event quality for which status records are required. Valid values are Good/Bad | 
 **sortOrder** | **string** | Sort order of status records by timestamp. Valid values: asc/desc. Default: desc | 
 **limit** | **int32** | Top N records to return. Do not pass or pass 0 to return maximum allowed records (100,000) | 

### Return type

[**[]PlexApmApiGetAssetNumericalDataItem**](PlexApmApiGetAssetNumericalDataItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PlexApmApiGetAssetStatuses

> []PlexApmApiGetAssetStatusesItem PlexApmApiGetAssetStatuses(ctx).StartDate(startDate).EndDate(endDate).AssetCodes(assetCodes).TagNames(tagNames).DaysOfTheWeek(daysOfTheWeek).PeriodStartTime(periodStartTime).PeriodEndTime(periodEndTime).EventTypes(eventTypes).EventStates(eventStates).Quality(quality).SortOrder(sortOrder).Limit(limit).Execute()

Get Asset Statuses



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	startDate := time.Now() // time.Time | Start datetime for the query. Valid format: YYYY-MM-DDThh:mm:ss.fffffffZ
	endDate := time.Now() // time.Time | End datetime for the query. Valid format: YYYY-MM-DDThh:mm:ss.fffffffZ
	assetCodes := "string" // string | Comma separated list of Asset codes for which status records are required. Complete match is required. Invalid asset codes will be ignored and no records will be returned for them. (optional)
	tagNames := "string" // string | Comma separated list of tag names for which status records are required. Complete match is required. Invalid tag names will be ignored and no records will be returned for them. (optional)
	daysOfTheWeek := "string" // string | Comma separated list of Days of the week to include in the result. Valid values: Monday, Tuesday, Wednesday, Thursday, Friday, Saturday, Sunday (optional)
	periodStartTime := "string" // string | Start period of the results to be returned in HH:mm:ss format. Should be used along with periodEndTime. Example- '08:00:00' (optional)
	periodEndTime := "string" // string | End period of the results to be returned in HH:mm:ss format. Should be used along with periodStartTime. Example- '16:00:00' (optional)
	eventTypes := "string" // string | Comma separated list of Event Types for which status records are required. Passing &quot;Problem or Abnormal&quot; will return &quot;High Problem/Abnormal&quot; and &quot;Low Problem/Abnormal&quot; as well. Valid values are Problem, Abnormal, Action Required, Maintenance, InCycle, Idle, Off, Other (optional)
	eventStates := "string" // string | Comma separated list of Event States for which status records are required. Valid values are True/ False. Example- 'True,False' (optional)
	quality := "string" // string | Comma separated list of Event quality for which status records are required. Valid values are Good/Bad (optional)
	sortOrder := "string" // string | Sort order of status records by timestamp. Valid values: asc/desc. Default: desc (optional)
	limit := int32(0) // int32 | Top N records to return. Do not pass or pass 0 to return maximum allowed records (100,000) (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PlexAPMAPIAPI.PlexApmApiGetAssetStatuses(context.Background()).StartDate(startDate).EndDate(endDate).AssetCodes(assetCodes).TagNames(tagNames).DaysOfTheWeek(daysOfTheWeek).PeriodStartTime(periodStartTime).PeriodEndTime(periodEndTime).EventTypes(eventTypes).EventStates(eventStates).Quality(quality).SortOrder(sortOrder).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PlexAPMAPIAPI.PlexApmApiGetAssetStatuses``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PlexApmApiGetAssetStatuses`: []PlexApmApiGetAssetStatusesItem
	fmt.Fprintf(os.Stdout, "Response from `PlexAPMAPIAPI.PlexApmApiGetAssetStatuses`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPlexApmApiGetAssetStatusesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **startDate** | **time.Time** | Start datetime for the query. Valid format: YYYY-MM-DDThh:mm:ss.fffffffZ | 
 **endDate** | **time.Time** | End datetime for the query. Valid format: YYYY-MM-DDThh:mm:ss.fffffffZ | 
 **assetCodes** | **string** | Comma separated list of Asset codes for which status records are required. Complete match is required. Invalid asset codes will be ignored and no records will be returned for them. | 
 **tagNames** | **string** | Comma separated list of tag names for which status records are required. Complete match is required. Invalid tag names will be ignored and no records will be returned for them. | 
 **daysOfTheWeek** | **string** | Comma separated list of Days of the week to include in the result. Valid values: Monday, Tuesday, Wednesday, Thursday, Friday, Saturday, Sunday | 
 **periodStartTime** | **string** | Start period of the results to be returned in HH:mm:ss format. Should be used along with periodEndTime. Example- &#39;08:00:00&#39; | 
 **periodEndTime** | **string** | End period of the results to be returned in HH:mm:ss format. Should be used along with periodStartTime. Example- &#39;16:00:00&#39; | 
 **eventTypes** | **string** | Comma separated list of Event Types for which status records are required. Passing &amp;quot;Problem or Abnormal&amp;quot; will return &amp;quot;High Problem/Abnormal&amp;quot; and &amp;quot;Low Problem/Abnormal&amp;quot; as well. Valid values are Problem, Abnormal, Action Required, Maintenance, InCycle, Idle, Off, Other | 
 **eventStates** | **string** | Comma separated list of Event States for which status records are required. Valid values are True/ False. Example- &#39;True,False&#39; | 
 **quality** | **string** | Comma separated list of Event quality for which status records are required. Valid values are Good/Bad | 
 **sortOrder** | **string** | Sort order of status records by timestamp. Valid values: asc/desc. Default: desc | 
 **limit** | **int32** | Top N records to return. Do not pass or pass 0 to return maximum allowed records (100,000) | 

### Return type

[**[]PlexApmApiGetAssetStatusesItem**](PlexApmApiGetAssetStatusesItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PlexApmApiGetElapsedTimeByAssets

> PlexApmApiGetElapsedTimeByAssetsResponse PlexApmApiGetElapsedTimeByAssets(ctx).StartDateTime(startDateTime).EndDateTime(endDateTime).AssetCodes(assetCodes).TagNames(tagNames).EventTypes(eventTypes).Execute()

Get Elapsed Time By Assets



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	startDateTime := time.Now() // time.Time | Start date-time for the query. The valid date-time in UTC format is: YYYY-MM-DDThh:mm:ss.fffffffZ. Future date-time is not allowed.
	endDateTime := time.Now() // time.Time | End date-time for the query. The valid date-time in UTC format is: YYYY-MM-DDThh:mm:ss.fffffffZ. Future date-time is not allowed.
	assetCodes := "string" // string | Comma separated list of asset codes for which event elapsed time records are required. Complete match is required. Asset codes are case-sensitive. An error response will be given when provided asset codes are invalid.
	tagNames := "string" // string | Comma separated list of tag names for which event elapsed time records are required. Complete match is required. Tag names are case-sensitive. An error response will be given when provided tag names are invalid. (optional)
	eventTypes := "string" // string | Comma separated list of event Types for which event elapsed time records are required. Valid values are Problem, Abnormal, Action Required, Maintenance, InCycle, Idle, Off and Other. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PlexAPMAPIAPI.PlexApmApiGetElapsedTimeByAssets(context.Background()).StartDateTime(startDateTime).EndDateTime(endDateTime).AssetCodes(assetCodes).TagNames(tagNames).EventTypes(eventTypes).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PlexAPMAPIAPI.PlexApmApiGetElapsedTimeByAssets``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PlexApmApiGetElapsedTimeByAssets`: PlexApmApiGetElapsedTimeByAssetsResponse
	fmt.Fprintf(os.Stdout, "Response from `PlexAPMAPIAPI.PlexApmApiGetElapsedTimeByAssets`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPlexApmApiGetElapsedTimeByAssetsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **startDateTime** | **time.Time** | Start date-time for the query. The valid date-time in UTC format is: YYYY-MM-DDThh:mm:ss.fffffffZ. Future date-time is not allowed. | 
 **endDateTime** | **time.Time** | End date-time for the query. The valid date-time in UTC format is: YYYY-MM-DDThh:mm:ss.fffffffZ. Future date-time is not allowed. | 
 **assetCodes** | **string** | Comma separated list of asset codes for which event elapsed time records are required. Complete match is required. Asset codes are case-sensitive. An error response will be given when provided asset codes are invalid. | 
 **tagNames** | **string** | Comma separated list of tag names for which event elapsed time records are required. Complete match is required. Tag names are case-sensitive. An error response will be given when provided tag names are invalid. | 
 **eventTypes** | **string** | Comma separated list of event Types for which event elapsed time records are required. Valid values are Problem, Abnormal, Action Required, Maintenance, InCycle, Idle, Off and Other. | 

### Return type

[**PlexApmApiGetElapsedTimeByAssetsResponse**](PlexApmApiGetElapsedTimeByAssetsResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PlexApmApiGetElapsedTimeByTags

> PlexApmApiGetElapsedTimeByTagsResponse PlexApmApiGetElapsedTimeByTags(ctx).StartDateTime(startDateTime).EndDateTime(endDateTime).AssetCodes(assetCodes).TagNames(tagNames).EventTypes(eventTypes).Execute()

Get Elapsed Time By Tags



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	startDateTime := time.Now() // time.Time | Start date-time for the query. The valid date-time in UTC format is: YYYY-MM-DDThh:mm:ss.fffffffZ. Future date-time is not allowed.
	endDateTime := time.Now() // time.Time | End date-time for the query. The valid date-time in UTC format is: YYYY-MM-DDThh:mm:ss.fffffffZ. Future date-time is not allowed.
	assetCodes := "string" // string | Comma separated list of asset codes for which event elapsed time records are required. Complete match is required. Asset codes are case-sensitive. An error response will be given when provided asset codes are invalid.
	tagNames := "string" // string | Comma separated list of tag names for which event elapsed time records are required. Complete match is required. Tag names are case-sensitive. An error response will be given when provided tag names are invalid. (optional)
	eventTypes := "string" // string | Comma separated list of event Types for which event elapsed time records are required. Valid values are Problem, Abnormal, Action Required, Maintenance, InCycle, Idle, Off and Other. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PlexAPMAPIAPI.PlexApmApiGetElapsedTimeByTags(context.Background()).StartDateTime(startDateTime).EndDateTime(endDateTime).AssetCodes(assetCodes).TagNames(tagNames).EventTypes(eventTypes).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PlexAPMAPIAPI.PlexApmApiGetElapsedTimeByTags``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PlexApmApiGetElapsedTimeByTags`: PlexApmApiGetElapsedTimeByTagsResponse
	fmt.Fprintf(os.Stdout, "Response from `PlexAPMAPIAPI.PlexApmApiGetElapsedTimeByTags`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPlexApmApiGetElapsedTimeByTagsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **startDateTime** | **time.Time** | Start date-time for the query. The valid date-time in UTC format is: YYYY-MM-DDThh:mm:ss.fffffffZ. Future date-time is not allowed. | 
 **endDateTime** | **time.Time** | End date-time for the query. The valid date-time in UTC format is: YYYY-MM-DDThh:mm:ss.fffffffZ. Future date-time is not allowed. | 
 **assetCodes** | **string** | Comma separated list of asset codes for which event elapsed time records are required. Complete match is required. Asset codes are case-sensitive. An error response will be given when provided asset codes are invalid. | 
 **tagNames** | **string** | Comma separated list of tag names for which event elapsed time records are required. Complete match is required. Tag names are case-sensitive. An error response will be given when provided tag names are invalid. | 
 **eventTypes** | **string** | Comma separated list of event Types for which event elapsed time records are required. Valid values are Problem, Abnormal, Action Required, Maintenance, InCycle, Idle, Off and Other. | 

### Return type

[**PlexApmApiGetElapsedTimeByTagsResponse**](PlexApmApiGetElapsedTimeByTagsResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PlexApmApiGetLatestTagValue

> []PlexApmApiGetLatestTagValueItem PlexApmApiGetLatestTagValue(ctx).AssetCodes(assetCodes).AssetNames(assetNames).GatewayNames(gatewayNames).TagNames(tagNames).TagAlias(tagAlias).StreamNames(streamNames).DataTypeNames(dataTypeNames).Execute()

Get Latest Tag Value



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	assetCodes := "string" // string | Comma separated list of Asset codes for which status records are required. Complete match is required. Invalid asset codes will be ignored and no records will be returned for them.
	assetNames := "string" // string | Comma separated list of Asset names for which Asset records are required. Complete match is required. Invalid asset codes will be ignored and no records will be returned for them. (optional)
	gatewayNames := "string" // string | Comma separated list of Gateway Names for which Asset records are required. Complete match is required. Invalid Gateway Names will be ignored and no records will be returned for them. (optional)
	tagNames := "string" // string | Comma separated list of tag names for which status records are required. Complete match is required. Invalid tag names will be ignored and no records will be returned for them. (optional)
	tagAlias := "string" // string | Comma separated list of tag alias for which latest tag records are required. Complete match is required. Invalid tag alias will be ignored and no records will be returned for them. (optional)
	streamNames := "string" // string | Comma separated list of Stream Names for which latest tag records are required. Complete match is required. Invalid Stream Names will be ignored and no records will be returned for them. (optional)
	dataTypeNames := "string" // string | Comma separated list of DataType Names for which latest tag records are required. Complete match is required. Invalid DataType Names will be ignored and no records will be returned for them. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PlexAPMAPIAPI.PlexApmApiGetLatestTagValue(context.Background()).AssetCodes(assetCodes).AssetNames(assetNames).GatewayNames(gatewayNames).TagNames(tagNames).TagAlias(tagAlias).StreamNames(streamNames).DataTypeNames(dataTypeNames).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PlexAPMAPIAPI.PlexApmApiGetLatestTagValue``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PlexApmApiGetLatestTagValue`: []PlexApmApiGetLatestTagValueItem
	fmt.Fprintf(os.Stdout, "Response from `PlexAPMAPIAPI.PlexApmApiGetLatestTagValue`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPlexApmApiGetLatestTagValueRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **assetCodes** | **string** | Comma separated list of Asset codes for which status records are required. Complete match is required. Invalid asset codes will be ignored and no records will be returned for them. | 
 **assetNames** | **string** | Comma separated list of Asset names for which Asset records are required. Complete match is required. Invalid asset codes will be ignored and no records will be returned for them. | 
 **gatewayNames** | **string** | Comma separated list of Gateway Names for which Asset records are required. Complete match is required. Invalid Gateway Names will be ignored and no records will be returned for them. | 
 **tagNames** | **string** | Comma separated list of tag names for which status records are required. Complete match is required. Invalid tag names will be ignored and no records will be returned for them. | 
 **tagAlias** | **string** | Comma separated list of tag alias for which latest tag records are required. Complete match is required. Invalid tag alias will be ignored and no records will be returned for them. | 
 **streamNames** | **string** | Comma separated list of Stream Names for which latest tag records are required. Complete match is required. Invalid Stream Names will be ignored and no records will be returned for them. | 
 **dataTypeNames** | **string** | Comma separated list of DataType Names for which latest tag records are required. Complete match is required. Invalid DataType Names will be ignored and no records will be returned for them. | 

### Return type

[**[]PlexApmApiGetLatestTagValueItem**](PlexApmApiGetLatestTagValueItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PlexApmApiGetTagValueAtSpecifiedTime

> []PlexApmApiGetTagValueAtSpecifiedTimeItem PlexApmApiGetTagValueAtSpecifiedTime(ctx, specificTime).AssetCodes(assetCodes).AssetNames(assetNames).GatewayNames(gatewayNames).TagNames(tagNames).TagAlias(tagAlias).StreamNames(streamNames).DataTypeNames(dataTypeNames).Execute()

Get Tag Value At Specified Time



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	specificTime := time.Now() // time.Time | Valid format: YYYY-MM-DDThh:mm:ssZ
	assetCodes := "string" // string | Comma separated list of Asset codes for which status records are required. Complete match is required. Invalid asset codes will be ignored and no records will be returned for them.
	assetNames := "string" // string | Comma separated list of Asset names for which Asset records are required. Complete match is required. Invalid asset codes will be ignored and no records will be returned for them. (optional)
	gatewayNames := "string" // string | Comma separated list of Gateway Names for which Asset records are required. Complete match is required. Invalid Gateway Names will be ignored and no records will be returned for them. (optional)
	tagNames := "string" // string | Comma separated list of tag names for which status records are required. Complete match is required. Invalid tag names will be ignored and no records will be returned for them. (optional)
	tagAlias := "string" // string | Comma separated list of tag alias for which latest tag records are required. Complete match is required. Invalid tag alias will be ignored and no records will be returned for them. (optional)
	streamNames := "string" // string | Comma separated list of Stream Names for which latest tag records are required. Complete match is required. Invalid Stream Names will be ignored and no records will be returned for them. (optional)
	dataTypeNames := "string" // string | Comma separated list of DataType Names for which latest tag records are required. Complete match is required. Invalid DataType Names will be ignored and no records will be returned for them. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PlexAPMAPIAPI.PlexApmApiGetTagValueAtSpecifiedTime(context.Background(), specificTime).AssetCodes(assetCodes).AssetNames(assetNames).GatewayNames(gatewayNames).TagNames(tagNames).TagAlias(tagAlias).StreamNames(streamNames).DataTypeNames(dataTypeNames).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PlexAPMAPIAPI.PlexApmApiGetTagValueAtSpecifiedTime``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PlexApmApiGetTagValueAtSpecifiedTime`: []PlexApmApiGetTagValueAtSpecifiedTimeItem
	fmt.Fprintf(os.Stdout, "Response from `PlexAPMAPIAPI.PlexApmApiGetTagValueAtSpecifiedTime`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**specificTime** | **time.Time** | Valid format: YYYY-MM-DDThh:mm:ssZ | 

### Other Parameters

Other parameters are passed through a pointer to a apiPlexApmApiGetTagValueAtSpecifiedTimeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **assetCodes** | **string** | Comma separated list of Asset codes for which status records are required. Complete match is required. Invalid asset codes will be ignored and no records will be returned for them. | 
 **assetNames** | **string** | Comma separated list of Asset names for which Asset records are required. Complete match is required. Invalid asset codes will be ignored and no records will be returned for them. | 
 **gatewayNames** | **string** | Comma separated list of Gateway Names for which Asset records are required. Complete match is required. Invalid Gateway Names will be ignored and no records will be returned for them. | 
 **tagNames** | **string** | Comma separated list of tag names for which status records are required. Complete match is required. Invalid tag names will be ignored and no records will be returned for them. | 
 **tagAlias** | **string** | Comma separated list of tag alias for which latest tag records are required. Complete match is required. Invalid tag alias will be ignored and no records will be returned for them. | 
 **streamNames** | **string** | Comma separated list of Stream Names for which latest tag records are required. Complete match is required. Invalid Stream Names will be ignored and no records will be returned for them. | 
 **dataTypeNames** | **string** | Comma separated list of DataType Names for which latest tag records are required. Complete match is required. Invalid DataType Names will be ignored and no records will be returned for them. | 

### Return type

[**[]PlexApmApiGetTagValueAtSpecifiedTimeItem**](PlexApmApiGetTagValueAtSpecifiedTimeItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

