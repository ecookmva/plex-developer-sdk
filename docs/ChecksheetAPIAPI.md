# \ChecksheetAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ChecksheetApiCreateChecksheet**](ChecksheetAPIAPI.md#ChecksheetApiCreateChecksheet) | **Post** /quality/v1/checksheets | Create Checksheet
[**ChecksheetApiGetChecksheet**](ChecksheetAPIAPI.md#ChecksheetApiGetChecksheet) | **Get** /quality/v1/checksheets/{id} | Get Checksheet



## ChecksheetApiCreateChecksheet

> ChecksheetApiCreateChecksheet201Response ChecksheetApiCreateChecksheet(ctx).ChecksheetApiCreateChecksheetRequest(checksheetApiCreateChecksheetRequest).Execute()

Create Checksheet



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
	checksheetApiCreateChecksheetRequest := *openapiclient.NewChecksheetApiCreateChecksheetRequest() // ChecksheetApiCreateChecksheetRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ChecksheetAPIAPI.ChecksheetApiCreateChecksheet(context.Background()).ChecksheetApiCreateChecksheetRequest(checksheetApiCreateChecksheetRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ChecksheetAPIAPI.ChecksheetApiCreateChecksheet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ChecksheetApiCreateChecksheet`: ChecksheetApiCreateChecksheet201Response
	fmt.Fprintf(os.Stdout, "Response from `ChecksheetAPIAPI.ChecksheetApiCreateChecksheet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiChecksheetApiCreateChecksheetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **checksheetApiCreateChecksheetRequest** | [**ChecksheetApiCreateChecksheetRequest**](ChecksheetApiCreateChecksheetRequest.md) |  | 

### Return type

[**ChecksheetApiCreateChecksheet201Response**](ChecksheetApiCreateChecksheet201Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ChecksheetApiGetChecksheet

> ChecksheetApiGetChecksheetResponse ChecksheetApiGetChecksheet(ctx, id).Execute()

Get Checksheet



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
	id := int32(0) // int32 | The Checksheet Number.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ChecksheetAPIAPI.ChecksheetApiGetChecksheet(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ChecksheetAPIAPI.ChecksheetApiGetChecksheet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ChecksheetApiGetChecksheet`: ChecksheetApiGetChecksheetResponse
	fmt.Fprintf(os.Stdout, "Response from `ChecksheetAPIAPI.ChecksheetApiGetChecksheet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | The Checksheet Number. | 

### Other Parameters

Other parameters are passed through a pointer to a apiChecksheetApiGetChecksheetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ChecksheetApiGetChecksheetResponse**](ChecksheetApiGetChecksheetResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

