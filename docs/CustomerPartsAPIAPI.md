# \CustomerPartsAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CustomerPartsApiCreateCustomerPart**](CustomerPartsAPIAPI.md#CustomerPartsApiCreateCustomerPart) | **Post** /mdm/v1/customer-parts | Create Customer Part
[**CustomerPartsApiDeleteCustomerPart**](CustomerPartsAPIAPI.md#CustomerPartsApiDeleteCustomerPart) | **Delete** /mdm/v1/customer-parts/{id} | Delete Customer Part
[**CustomerPartsApiGetCustomerPart**](CustomerPartsAPIAPI.md#CustomerPartsApiGetCustomerPart) | **Get** /mdm/v1/customer-parts/{id} | Get Customer Part
[**CustomerPartsApiListCustomerParts**](CustomerPartsAPIAPI.md#CustomerPartsApiListCustomerParts) | **Get** /mdm/v1/customer-parts | List Customer Parts
[**CustomerPartsApiSyncCustomerParts**](CustomerPartsAPIAPI.md#CustomerPartsApiSyncCustomerParts) | **Post** /mdm/v1/customer-parts/sync | Sync Customer Parts
[**CustomerPartsApiUpdateCustomerPart**](CustomerPartsAPIAPI.md#CustomerPartsApiUpdateCustomerPart) | **Put** /mdm/v1/customer-parts/{id} | Update Customer Part



## CustomerPartsApiCreateCustomerPart

> CustomerPartsApiCreateCustomerPart201Response CustomerPartsApiCreateCustomerPart(ctx).CustomerPartsApiCreateCustomerPartRequest(customerPartsApiCreateCustomerPartRequest).Execute()

Create Customer Part



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
	customerPartsApiCreateCustomerPartRequest := *openapiclient.NewCustomerPartsApiCreateCustomerPartRequest() // CustomerPartsApiCreateCustomerPartRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomerPartsAPIAPI.CustomerPartsApiCreateCustomerPart(context.Background()).CustomerPartsApiCreateCustomerPartRequest(customerPartsApiCreateCustomerPartRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomerPartsAPIAPI.CustomerPartsApiCreateCustomerPart``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomerPartsApiCreateCustomerPart`: CustomerPartsApiCreateCustomerPart201Response
	fmt.Fprintf(os.Stdout, "Response from `CustomerPartsAPIAPI.CustomerPartsApiCreateCustomerPart`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCustomerPartsApiCreateCustomerPartRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **customerPartsApiCreateCustomerPartRequest** | [**CustomerPartsApiCreateCustomerPartRequest**](CustomerPartsApiCreateCustomerPartRequest.md) |  | 

### Return type

[**CustomerPartsApiCreateCustomerPart201Response**](CustomerPartsApiCreateCustomerPart201Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomerPartsApiDeleteCustomerPart

> CustomerPartsApiDeleteCustomerPartResponse CustomerPartsApiDeleteCustomerPart(ctx, id).Execute()

Delete Customer Part



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
	id := "00000000-0000-0000-0000-000000000000" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomerPartsAPIAPI.CustomerPartsApiDeleteCustomerPart(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomerPartsAPIAPI.CustomerPartsApiDeleteCustomerPart``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomerPartsApiDeleteCustomerPart`: CustomerPartsApiDeleteCustomerPartResponse
	fmt.Fprintf(os.Stdout, "Response from `CustomerPartsAPIAPI.CustomerPartsApiDeleteCustomerPart`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustomerPartsApiDeleteCustomerPartRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**CustomerPartsApiDeleteCustomerPartResponse**](CustomerPartsApiDeleteCustomerPartResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomerPartsApiGetCustomerPart

> CustomerPartsApiGetCustomerPartResponse CustomerPartsApiGetCustomerPart(ctx, id).Execute()

Get Customer Part



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
	id := "00000000-0000-0000-0000-000000000000" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomerPartsAPIAPI.CustomerPartsApiGetCustomerPart(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomerPartsAPIAPI.CustomerPartsApiGetCustomerPart``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomerPartsApiGetCustomerPart`: CustomerPartsApiGetCustomerPartResponse
	fmt.Fprintf(os.Stdout, "Response from `CustomerPartsAPIAPI.CustomerPartsApiGetCustomerPart`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustomerPartsApiGetCustomerPartRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**CustomerPartsApiGetCustomerPartResponse**](CustomerPartsApiGetCustomerPartResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomerPartsApiListCustomerParts

> []CustomerPartsApiListCustomerPartsItem CustomerPartsApiListCustomerParts(ctx).Id(id).Number(number).PartId(partId).CustomerId(customerId).ModifiedDateTimeBegin(modifiedDateTimeBegin).ModifiedDateTimeEnd(modifiedDateTimeEnd).Execute()

List Customer Parts



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
	id := []string{"00000000-0000-0000-0000-000000000000"} // []string | A list of customer part IDs. (optional)
	number := "string" // string | The customer part number. (optional)
	partId := "00000000-0000-0000-0000-000000000000" // string | The part ID. (optional)
	customerId := "00000000-0000-0000-0000-000000000000" // string | The customer ID. (optional)
	modifiedDateTimeBegin := time.Now() // time.Time | The beginning date and time to use for records that were last modified within a time frame. (optional)
	modifiedDateTimeEnd := time.Now() // time.Time | The ending date and time to use for records that were last modified within a time frame. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomerPartsAPIAPI.CustomerPartsApiListCustomerParts(context.Background()).Id(id).Number(number).PartId(partId).CustomerId(customerId).ModifiedDateTimeBegin(modifiedDateTimeBegin).ModifiedDateTimeEnd(modifiedDateTimeEnd).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomerPartsAPIAPI.CustomerPartsApiListCustomerParts``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomerPartsApiListCustomerParts`: []CustomerPartsApiListCustomerPartsItem
	fmt.Fprintf(os.Stdout, "Response from `CustomerPartsAPIAPI.CustomerPartsApiListCustomerParts`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCustomerPartsApiListCustomerPartsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **[]string** | A list of customer part IDs. | 
 **number** | **string** | The customer part number. | 
 **partId** | **string** | The part ID. | 
 **customerId** | **string** | The customer ID. | 
 **modifiedDateTimeBegin** | **time.Time** | The beginning date and time to use for records that were last modified within a time frame. | 
 **modifiedDateTimeEnd** | **time.Time** | The ending date and time to use for records that were last modified within a time frame. | 

### Return type

[**[]CustomerPartsApiListCustomerPartsItem**](CustomerPartsApiListCustomerPartsItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomerPartsApiSyncCustomerParts

> CustomerPartsApiSyncCustomerParts(ctx).CustomerPartsApiSyncCustomerPartsRequest(customerPartsApiSyncCustomerPartsRequest).Execute()

Sync Customer Parts



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
	customerPartsApiSyncCustomerPartsRequest := *openapiclient.NewCustomerPartsApiSyncCustomerPartsRequest() // CustomerPartsApiSyncCustomerPartsRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.CustomerPartsAPIAPI.CustomerPartsApiSyncCustomerParts(context.Background()).CustomerPartsApiSyncCustomerPartsRequest(customerPartsApiSyncCustomerPartsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomerPartsAPIAPI.CustomerPartsApiSyncCustomerParts``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCustomerPartsApiSyncCustomerPartsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **customerPartsApiSyncCustomerPartsRequest** | [**CustomerPartsApiSyncCustomerPartsRequest**](CustomerPartsApiSyncCustomerPartsRequest.md) |  | 

### Return type

 (empty response body)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomerPartsApiUpdateCustomerPart

> CustomerPartsApiUpdateCustomerPartResponse CustomerPartsApiUpdateCustomerPart(ctx, id).CustomerPartsApiUpdateCustomerPartRequest(customerPartsApiUpdateCustomerPartRequest).Execute()

Update Customer Part



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
	id := "00000000-0000-0000-0000-000000000000" // string | 
	customerPartsApiUpdateCustomerPartRequest := *openapiclient.NewCustomerPartsApiUpdateCustomerPartRequest() // CustomerPartsApiUpdateCustomerPartRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomerPartsAPIAPI.CustomerPartsApiUpdateCustomerPart(context.Background(), id).CustomerPartsApiUpdateCustomerPartRequest(customerPartsApiUpdateCustomerPartRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomerPartsAPIAPI.CustomerPartsApiUpdateCustomerPart``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomerPartsApiUpdateCustomerPart`: CustomerPartsApiUpdateCustomerPartResponse
	fmt.Fprintf(os.Stdout, "Response from `CustomerPartsAPIAPI.CustomerPartsApiUpdateCustomerPart`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustomerPartsApiUpdateCustomerPartRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **customerPartsApiUpdateCustomerPartRequest** | [**CustomerPartsApiUpdateCustomerPartRequest**](CustomerPartsApiUpdateCustomerPartRequest.md) |  | 

### Return type

[**CustomerPartsApiUpdateCustomerPartResponse**](CustomerPartsApiUpdateCustomerPartResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

