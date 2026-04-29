# \SupplyItemsAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SupplyItemsApiActivateSupplyItem**](SupplyItemsAPIAPI.md#SupplyItemsApiActivateSupplyItem) | **Post** /mdm/v1/supply-items/{id}/activate | Activate Supply Item
[**SupplyItemsApiCreateSupplyItem**](SupplyItemsAPIAPI.md#SupplyItemsApiCreateSupplyItem) | **Post** /mdm/v1/supply-items | Create Supply Item
[**SupplyItemsApiDeactivateSupplyItem**](SupplyItemsAPIAPI.md#SupplyItemsApiDeactivateSupplyItem) | **Post** /mdm/v1/supply-items/{id}/deactivate | Deactivate Supply Item
[**SupplyItemsApiDeleteSupplyItem**](SupplyItemsAPIAPI.md#SupplyItemsApiDeleteSupplyItem) | **Delete** /mdm/v1/supply-items/{id} | Delete Supply Item
[**SupplyItemsApiGetSupplyItem**](SupplyItemsAPIAPI.md#SupplyItemsApiGetSupplyItem) | **Get** /mdm/v1/supply-items/{id} | Get Supply Item
[**SupplyItemsApiListSupplyItems**](SupplyItemsAPIAPI.md#SupplyItemsApiListSupplyItems) | **Get** /mdm/v1/supply-items | List Supply Items
[**SupplyItemsApiSyncSupplyItem**](SupplyItemsAPIAPI.md#SupplyItemsApiSyncSupplyItem) | **Post** /mdm/v1/supply-items/sync | Sync Supply Item
[**SupplyItemsApiUpdateSupplyItem**](SupplyItemsAPIAPI.md#SupplyItemsApiUpdateSupplyItem) | **Put** /mdm/v1/supply-items/{id} | Update Supply Item



## SupplyItemsApiActivateSupplyItem

> SupplyItemsApiActivateSupplyItem(ctx, id).Execute()

Activate Supply Item



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
	r, err := apiClient.SupplyItemsAPIAPI.SupplyItemsApiActivateSupplyItem(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SupplyItemsAPIAPI.SupplyItemsApiActivateSupplyItem``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSupplyItemsApiActivateSupplyItemRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SupplyItemsApiCreateSupplyItem

> SupplyItemsApiCreateSupplyItem201Response SupplyItemsApiCreateSupplyItem(ctx).SupplyItemsApiCreateSupplyItemRequest(supplyItemsApiCreateSupplyItemRequest).Execute()

Create Supply Item



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
	supplyItemsApiCreateSupplyItemRequest := *openapiclient.NewSupplyItemsApiCreateSupplyItemRequest() // SupplyItemsApiCreateSupplyItemRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SupplyItemsAPIAPI.SupplyItemsApiCreateSupplyItem(context.Background()).SupplyItemsApiCreateSupplyItemRequest(supplyItemsApiCreateSupplyItemRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SupplyItemsAPIAPI.SupplyItemsApiCreateSupplyItem``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SupplyItemsApiCreateSupplyItem`: SupplyItemsApiCreateSupplyItem201Response
	fmt.Fprintf(os.Stdout, "Response from `SupplyItemsAPIAPI.SupplyItemsApiCreateSupplyItem`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSupplyItemsApiCreateSupplyItemRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **supplyItemsApiCreateSupplyItemRequest** | [**SupplyItemsApiCreateSupplyItemRequest**](SupplyItemsApiCreateSupplyItemRequest.md) |  | 

### Return type

[**SupplyItemsApiCreateSupplyItem201Response**](SupplyItemsApiCreateSupplyItem201Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SupplyItemsApiDeactivateSupplyItem

> SupplyItemsApiDeactivateSupplyItem(ctx, id).Execute()

Deactivate Supply Item



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
	r, err := apiClient.SupplyItemsAPIAPI.SupplyItemsApiDeactivateSupplyItem(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SupplyItemsAPIAPI.SupplyItemsApiDeactivateSupplyItem``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSupplyItemsApiDeactivateSupplyItemRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SupplyItemsApiDeleteSupplyItem

> SupplyItemsApiDeleteSupplyItemResponse SupplyItemsApiDeleteSupplyItem(ctx, id).Execute()

Delete Supply Item



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
	resp, r, err := apiClient.SupplyItemsAPIAPI.SupplyItemsApiDeleteSupplyItem(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SupplyItemsAPIAPI.SupplyItemsApiDeleteSupplyItem``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SupplyItemsApiDeleteSupplyItem`: SupplyItemsApiDeleteSupplyItemResponse
	fmt.Fprintf(os.Stdout, "Response from `SupplyItemsAPIAPI.SupplyItemsApiDeleteSupplyItem`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSupplyItemsApiDeleteSupplyItemRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**SupplyItemsApiDeleteSupplyItemResponse**](SupplyItemsApiDeleteSupplyItemResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SupplyItemsApiGetSupplyItem

> SupplyItemsApiGetSupplyItemResponse SupplyItemsApiGetSupplyItem(ctx, id).Execute()

Get Supply Item



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
	resp, r, err := apiClient.SupplyItemsAPIAPI.SupplyItemsApiGetSupplyItem(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SupplyItemsAPIAPI.SupplyItemsApiGetSupplyItem``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SupplyItemsApiGetSupplyItem`: SupplyItemsApiGetSupplyItemResponse
	fmt.Fprintf(os.Stdout, "Response from `SupplyItemsAPIAPI.SupplyItemsApiGetSupplyItem`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSupplyItemsApiGetSupplyItemRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**SupplyItemsApiGetSupplyItemResponse**](SupplyItemsApiGetSupplyItemResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SupplyItemsApiListSupplyItems

> []SupplyItemsApiListSupplyItemsItem SupplyItemsApiListSupplyItems(ctx).Id(id).SupplyItemNumber(supplyItemNumber).Type_(type_).Category(category).Priority(priority).Group(group).CreatedById(createdById).CreatedDateBegin(createdDateBegin).CreatedDateEnd(createdDateEnd).ModifiedById(modifiedById).ModifiedDateBegin(modifiedDateBegin).ModifiedDateEnd(modifiedDateEnd).Execute()

List Supply Items



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
	id := []string{"00000000-0000-0000-0000-000000000000"} // []string | A list of supply item IDs. (optional)
	supplyItemNumber := "string" // string | A short identifier for the Supply Item. (optional)
	type_ := "string" // string | Indicates the Supply Item type, such as office supplies or shop supplies. Setup Table: Item Type (optional)
	category := "string" // string | Setup Table: Supply Category (optional)
	priority := "string" // string | Setup Table: Item Priority (optional)
	group := "string" // string | A supply group, used to categorize Supply Items, such as Electrical, Mechanical, Office Supplies. Setup Table: Item Group (optional)
	createdById := "00000000-0000-0000-0000-000000000000" // string | The IAM Account ID of the user who created the record. (optional)
	createdDateBegin := time.Now() // time.Time | The date on which the record was created. (optional)
	createdDateEnd := time.Now() // time.Time | The date on which the record was created. (optional)
	modifiedById := "00000000-0000-0000-0000-000000000000" // string | The IAM Account ID of the user who last modified the record. (optional)
	modifiedDateBegin := time.Now() // time.Time | The date on which the record was last modified. (optional)
	modifiedDateEnd := time.Now() // time.Time | The date on which the record was last modified. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SupplyItemsAPIAPI.SupplyItemsApiListSupplyItems(context.Background()).Id(id).SupplyItemNumber(supplyItemNumber).Type_(type_).Category(category).Priority(priority).Group(group).CreatedById(createdById).CreatedDateBegin(createdDateBegin).CreatedDateEnd(createdDateEnd).ModifiedById(modifiedById).ModifiedDateBegin(modifiedDateBegin).ModifiedDateEnd(modifiedDateEnd).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SupplyItemsAPIAPI.SupplyItemsApiListSupplyItems``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SupplyItemsApiListSupplyItems`: []SupplyItemsApiListSupplyItemsItem
	fmt.Fprintf(os.Stdout, "Response from `SupplyItemsAPIAPI.SupplyItemsApiListSupplyItems`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSupplyItemsApiListSupplyItemsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **[]string** | A list of supply item IDs. | 
 **supplyItemNumber** | **string** | A short identifier for the Supply Item. | 
 **type_** | **string** | Indicates the Supply Item type, such as office supplies or shop supplies. Setup Table: Item Type | 
 **category** | **string** | Setup Table: Supply Category | 
 **priority** | **string** | Setup Table: Item Priority | 
 **group** | **string** | A supply group, used to categorize Supply Items, such as Electrical, Mechanical, Office Supplies. Setup Table: Item Group | 
 **createdById** | **string** | The IAM Account ID of the user who created the record. | 
 **createdDateBegin** | **time.Time** | The date on which the record was created. | 
 **createdDateEnd** | **time.Time** | The date on which the record was created. | 
 **modifiedById** | **string** | The IAM Account ID of the user who last modified the record. | 
 **modifiedDateBegin** | **time.Time** | The date on which the record was last modified. | 
 **modifiedDateEnd** | **time.Time** | The date on which the record was last modified. | 

### Return type

[**[]SupplyItemsApiListSupplyItemsItem**](SupplyItemsApiListSupplyItemsItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SupplyItemsApiSyncSupplyItem

> SupplyItemsApiSyncSupplyItem(ctx).SupplyItemsApiSyncSupplyItemRequest(supplyItemsApiSyncSupplyItemRequest).Execute()

Sync Supply Item



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
	supplyItemsApiSyncSupplyItemRequest := *openapiclient.NewSupplyItemsApiSyncSupplyItemRequest() // SupplyItemsApiSyncSupplyItemRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.SupplyItemsAPIAPI.SupplyItemsApiSyncSupplyItem(context.Background()).SupplyItemsApiSyncSupplyItemRequest(supplyItemsApiSyncSupplyItemRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SupplyItemsAPIAPI.SupplyItemsApiSyncSupplyItem``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSupplyItemsApiSyncSupplyItemRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **supplyItemsApiSyncSupplyItemRequest** | [**SupplyItemsApiSyncSupplyItemRequest**](SupplyItemsApiSyncSupplyItemRequest.md) |  | 

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


## SupplyItemsApiUpdateSupplyItem

> SupplyItemsApiUpdateSupplyItemResponse SupplyItemsApiUpdateSupplyItem(ctx, id).SupplyItemsApiUpdateSupplyItemRequest(supplyItemsApiUpdateSupplyItemRequest).Execute()

Update Supply Item



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
	supplyItemsApiUpdateSupplyItemRequest := *openapiclient.NewSupplyItemsApiUpdateSupplyItemRequest() // SupplyItemsApiUpdateSupplyItemRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SupplyItemsAPIAPI.SupplyItemsApiUpdateSupplyItem(context.Background(), id).SupplyItemsApiUpdateSupplyItemRequest(supplyItemsApiUpdateSupplyItemRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SupplyItemsAPIAPI.SupplyItemsApiUpdateSupplyItem``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SupplyItemsApiUpdateSupplyItem`: SupplyItemsApiUpdateSupplyItemResponse
	fmt.Fprintf(os.Stdout, "Response from `SupplyItemsAPIAPI.SupplyItemsApiUpdateSupplyItem`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSupplyItemsApiUpdateSupplyItemRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **supplyItemsApiUpdateSupplyItemRequest** | [**SupplyItemsApiUpdateSupplyItemRequest**](SupplyItemsApiUpdateSupplyItemRequest.md) |  | 

### Return type

[**SupplyItemsApiUpdateSupplyItemResponse**](SupplyItemsApiUpdateSupplyItemResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

