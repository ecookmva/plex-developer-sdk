# \DynamicMultiOutSetsAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**DynamicMultiOutSetsApiCreateDynamicMultiOutSet**](DynamicMultiOutSetsAPIAPI.md#DynamicMultiOutSetsApiCreateDynamicMultiOutSet) | **Post** /production-tracking/v1/dynamic-multi-out-sets | Create Dynamic Multi Out Set
[**DynamicMultiOutSetsApiGetDynamicMultiOutSet**](DynamicMultiOutSetsAPIAPI.md#DynamicMultiOutSetsApiGetDynamicMultiOutSet) | **Get** /production-tracking/v1/dynamic-multi-out-sets/{dynamicMultiOutSetId} | Get Dynamic Multi Out Set
[**DynamicMultiOutSetsApiListDynamicMultiOutSets**](DynamicMultiOutSetsAPIAPI.md#DynamicMultiOutSetsApiListDynamicMultiOutSets) | **Get** /production-tracking/v1/dynamic-multi-out-sets | List Dynamic Multi Out Sets



## DynamicMultiOutSetsApiCreateDynamicMultiOutSet

> DynamicMultiOutSetsApiCreateDynamicMultiOutSet201Response DynamicMultiOutSetsApiCreateDynamicMultiOutSet(ctx).DynamicMultiOutSetsApiCreateDynamicMultiOutSetRequest(dynamicMultiOutSetsApiCreateDynamicMultiOutSetRequest).Execute()

Create Dynamic Multi Out Set



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
	dynamicMultiOutSetsApiCreateDynamicMultiOutSetRequest := *openapiclient.NewDynamicMultiOutSetsApiCreateDynamicMultiOutSetRequest() // DynamicMultiOutSetsApiCreateDynamicMultiOutSetRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DynamicMultiOutSetsAPIAPI.DynamicMultiOutSetsApiCreateDynamicMultiOutSet(context.Background()).DynamicMultiOutSetsApiCreateDynamicMultiOutSetRequest(dynamicMultiOutSetsApiCreateDynamicMultiOutSetRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DynamicMultiOutSetsAPIAPI.DynamicMultiOutSetsApiCreateDynamicMultiOutSet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DynamicMultiOutSetsApiCreateDynamicMultiOutSet`: DynamicMultiOutSetsApiCreateDynamicMultiOutSet201Response
	fmt.Fprintf(os.Stdout, "Response from `DynamicMultiOutSetsAPIAPI.DynamicMultiOutSetsApiCreateDynamicMultiOutSet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiDynamicMultiOutSetsApiCreateDynamicMultiOutSetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **dynamicMultiOutSetsApiCreateDynamicMultiOutSetRequest** | [**DynamicMultiOutSetsApiCreateDynamicMultiOutSetRequest**](DynamicMultiOutSetsApiCreateDynamicMultiOutSetRequest.md) |  | 

### Return type

[**DynamicMultiOutSetsApiCreateDynamicMultiOutSet201Response**](DynamicMultiOutSetsApiCreateDynamicMultiOutSet201Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DynamicMultiOutSetsApiGetDynamicMultiOutSet

> DynamicMultiOutSetsApiGetDynamicMultiOutSetResponse DynamicMultiOutSetsApiGetDynamicMultiOutSet(ctx, dynamicMultiOutSetId).Execute()

Get Dynamic Multi Out Set



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
	dynamicMultiOutSetId := "00000000-0000-0000-0000-000000000000" // string | The Dynamic Multi Out Set ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DynamicMultiOutSetsAPIAPI.DynamicMultiOutSetsApiGetDynamicMultiOutSet(context.Background(), dynamicMultiOutSetId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DynamicMultiOutSetsAPIAPI.DynamicMultiOutSetsApiGetDynamicMultiOutSet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DynamicMultiOutSetsApiGetDynamicMultiOutSet`: DynamicMultiOutSetsApiGetDynamicMultiOutSetResponse
	fmt.Fprintf(os.Stdout, "Response from `DynamicMultiOutSetsAPIAPI.DynamicMultiOutSetsApiGetDynamicMultiOutSet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**dynamicMultiOutSetId** | **string** | The Dynamic Multi Out Set ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDynamicMultiOutSetsApiGetDynamicMultiOutSetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**DynamicMultiOutSetsApiGetDynamicMultiOutSetResponse**](DynamicMultiOutSetsApiGetDynamicMultiOutSetResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DynamicMultiOutSetsApiListDynamicMultiOutSets

> []DynamicMultiOutSetsApiListDynamicMultiOutSetsItem DynamicMultiOutSetsApiListDynamicMultiOutSets(ctx).Id(id).PlannedCalendarStartDateBegin(plannedCalendarStartDateBegin).PlannedCalendarStartDateEnd(plannedCalendarStartDateEnd).Execute()

List Dynamic Multi Out Sets



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
	id := []string{"00000000-0000-0000-0000-000000000000"} // []string | Unique identifiers for the Dynamic Multi Out Sets. (optional)
	plannedCalendarStartDateBegin := "string" // string | The Planned Start Date for the Dynamic Multi Out Set. (optional)
	plannedCalendarStartDateEnd := "string" // string | The Planned Start Date for the Dynamic Multi Out Set. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DynamicMultiOutSetsAPIAPI.DynamicMultiOutSetsApiListDynamicMultiOutSets(context.Background()).Id(id).PlannedCalendarStartDateBegin(plannedCalendarStartDateBegin).PlannedCalendarStartDateEnd(plannedCalendarStartDateEnd).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DynamicMultiOutSetsAPIAPI.DynamicMultiOutSetsApiListDynamicMultiOutSets``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DynamicMultiOutSetsApiListDynamicMultiOutSets`: []DynamicMultiOutSetsApiListDynamicMultiOutSetsItem
	fmt.Fprintf(os.Stdout, "Response from `DynamicMultiOutSetsAPIAPI.DynamicMultiOutSetsApiListDynamicMultiOutSets`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiDynamicMultiOutSetsApiListDynamicMultiOutSetsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **[]string** | Unique identifiers for the Dynamic Multi Out Sets. | 
 **plannedCalendarStartDateBegin** | **string** | The Planned Start Date for the Dynamic Multi Out Set. | 
 **plannedCalendarStartDateEnd** | **string** | The Planned Start Date for the Dynamic Multi Out Set. | 

### Return type

[**[]DynamicMultiOutSetsApiListDynamicMultiOutSetsItem**](DynamicMultiOutSetsApiListDynamicMultiOutSetsItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

