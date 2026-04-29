# \PlexAPMODataAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**PlexApmOdataApiGetTagData**](PlexAPMODataAPIAPI.md#PlexApmOdataApiGetTagData) | **Get** /cm/odata/v2/events | Get Tag Data



## PlexApmOdataApiGetTagData

> PlexApmOdataApiGetTagDataResponse PlexApmOdataApiGetTagData(ctx).Filter(filter).Select_(select_).Top(top).Execute()

Get Tag Data



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
	filter := "string" // string | For fetching the tag data, you must provide $filter parameter. Allowed logical operators for filter query are - &quot;eq&quot;, &quot;and&quot;, &quot;in&quot;, &quot;startswith&quot;, &quot;endswith&quot;.
	select_ := "string" // string | For retrieving specific columns in the response, you should provide $select parameter. (optional)
	top := int32(0) // int32 | For limiting response to a specific record count, you should provide $top parameter. If you do not provide $top parameter, response will be served with a default limit of 50000. $top accepts a non-zero, non-negative integer value. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PlexAPMODataAPIAPI.PlexApmOdataApiGetTagData(context.Background()).Filter(filter).Select_(select_).Top(top).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PlexAPMODataAPIAPI.PlexApmOdataApiGetTagData``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PlexApmOdataApiGetTagData`: PlexApmOdataApiGetTagDataResponse
	fmt.Fprintf(os.Stdout, "Response from `PlexAPMODataAPIAPI.PlexApmOdataApiGetTagData`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPlexApmOdataApiGetTagDataRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **filter** | **string** | For fetching the tag data, you must provide $filter parameter. Allowed logical operators for filter query are - &amp;quot;eq&amp;quot;, &amp;quot;and&amp;quot;, &amp;quot;in&amp;quot;, &amp;quot;startswith&amp;quot;, &amp;quot;endswith&amp;quot;. | 
 **select_** | **string** | For retrieving specific columns in the response, you should provide $select parameter. | 
 **top** | **int32** | For limiting response to a specific record count, you should provide $top parameter. If you do not provide $top parameter, response will be served with a default limit of 50000. $top accepts a non-zero, non-negative integer value. | 

### Return type

[**PlexApmOdataApiGetTagDataResponse**](PlexApmOdataApiGetTagDataResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

