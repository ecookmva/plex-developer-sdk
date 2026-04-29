# \PartsAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**PartsApiCreatePart**](PartsAPIAPI.md#PartsApiCreatePart) | **Post** /mdm/v1/parts | Create Part
[**PartsApiDeletePart**](PartsAPIAPI.md#PartsApiDeletePart) | **Delete** /mdm/v1/parts/{id} | Delete Part
[**PartsApiGetPart**](PartsAPIAPI.md#PartsApiGetPart) | **Get** /mdm/v1/parts/{id} | Get Part
[**PartsApiListParts**](PartsAPIAPI.md#PartsApiListParts) | **Get** /mdm/v1/parts | List Parts
[**PartsApiSyncParts**](PartsAPIAPI.md#PartsApiSyncParts) | **Post** /mdm/v1/parts/sync | Sync Parts
[**PartsApiUpdatePart**](PartsAPIAPI.md#PartsApiUpdatePart) | **Put** /mdm/v1/parts/{id} | Update Part



## PartsApiCreatePart

> PartsApiCreatePart201Response PartsApiCreatePart(ctx).PartsApiCreatePartRequest(partsApiCreatePartRequest).Execute()

Create Part



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
	partsApiCreatePartRequest := *openapiclient.NewPartsApiCreatePartRequest() // PartsApiCreatePartRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartsAPIAPI.PartsApiCreatePart(context.Background()).PartsApiCreatePartRequest(partsApiCreatePartRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartsAPIAPI.PartsApiCreatePart``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PartsApiCreatePart`: PartsApiCreatePart201Response
	fmt.Fprintf(os.Stdout, "Response from `PartsAPIAPI.PartsApiCreatePart`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPartsApiCreatePartRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **partsApiCreatePartRequest** | [**PartsApiCreatePartRequest**](PartsApiCreatePartRequest.md) |  | 

### Return type

[**PartsApiCreatePart201Response**](PartsApiCreatePart201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PartsApiDeletePart

> PartsApiDeletePartResponse PartsApiDeletePart(ctx, id).Execute()

Delete Part



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
	resp, r, err := apiClient.PartsAPIAPI.PartsApiDeletePart(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartsAPIAPI.PartsApiDeletePart``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PartsApiDeletePart`: PartsApiDeletePartResponse
	fmt.Fprintf(os.Stdout, "Response from `PartsAPIAPI.PartsApiDeletePart`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiPartsApiDeletePartRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**PartsApiDeletePartResponse**](PartsApiDeletePartResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PartsApiGetPart

> PartsApiGetPartResponse PartsApiGetPart(ctx, id).Execute()

Get Part



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
	resp, r, err := apiClient.PartsAPIAPI.PartsApiGetPart(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartsAPIAPI.PartsApiGetPart``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PartsApiGetPart`: PartsApiGetPartResponse
	fmt.Fprintf(os.Stdout, "Response from `PartsAPIAPI.PartsApiGetPart`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiPartsApiGetPartRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**PartsApiGetPartResponse**](PartsApiGetPartResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PartsApiListParts

> []PartsApiListPartsItem PartsApiListParts(ctx).Id(id).Number(number).Revision(revision).Type_(type_).Status(status).Source(source).ProductType(productType).Allergens(allergens).Execute()

List Parts



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
	id := []string{"00000000-0000-0000-0000-000000000000"} // []string | A list of Part Resource IDs. (optional)
	number := "string" // string |  (optional)
	revision := "string" // string |  (optional)
	type_ := "string" // string | Setup Table: Part_Type (optional)
	status := "string" // string | Setup Table: Part_Status (optional)
	source := "string" // string | Setup Table: Part_Source (optional)
	productType := "string" // string | Setup Table: Part_Product_Type (optional)
	allergens := []string{"string"} // []string | Setup Table: Allergen. HACCP Module must be enabled. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartsAPIAPI.PartsApiListParts(context.Background()).Id(id).Number(number).Revision(revision).Type_(type_).Status(status).Source(source).ProductType(productType).Allergens(allergens).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartsAPIAPI.PartsApiListParts``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PartsApiListParts`: []PartsApiListPartsItem
	fmt.Fprintf(os.Stdout, "Response from `PartsAPIAPI.PartsApiListParts`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPartsApiListPartsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **[]string** | A list of Part Resource IDs. | 
 **number** | **string** |  | 
 **revision** | **string** |  | 
 **type_** | **string** | Setup Table: Part_Type | 
 **status** | **string** | Setup Table: Part_Status | 
 **source** | **string** | Setup Table: Part_Source | 
 **productType** | **string** | Setup Table: Part_Product_Type | 
 **allergens** | **[]string** | Setup Table: Allergen. HACCP Module must be enabled. | 

### Return type

[**[]PartsApiListPartsItem**](PartsApiListPartsItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PartsApiSyncParts

> PartsApiSyncParts(ctx).PartsApiSyncPartsRequest(partsApiSyncPartsRequest).Execute()

Sync Parts



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
	partsApiSyncPartsRequest := *openapiclient.NewPartsApiSyncPartsRequest() // PartsApiSyncPartsRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.PartsAPIAPI.PartsApiSyncParts(context.Background()).PartsApiSyncPartsRequest(partsApiSyncPartsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartsAPIAPI.PartsApiSyncParts``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPartsApiSyncPartsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **partsApiSyncPartsRequest** | [**PartsApiSyncPartsRequest**](PartsApiSyncPartsRequest.md) |  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PartsApiUpdatePart

> PartsApiUpdatePartResponse PartsApiUpdatePart(ctx, id).PartsApiUpdatePartRequest(partsApiUpdatePartRequest).Execute()

Update Part



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
	partsApiUpdatePartRequest := *openapiclient.NewPartsApiUpdatePartRequest() // PartsApiUpdatePartRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartsAPIAPI.PartsApiUpdatePart(context.Background(), id).PartsApiUpdatePartRequest(partsApiUpdatePartRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartsAPIAPI.PartsApiUpdatePart``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PartsApiUpdatePart`: PartsApiUpdatePartResponse
	fmt.Fprintf(os.Stdout, "Response from `PartsAPIAPI.PartsApiUpdatePart`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiPartsApiUpdatePartRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **partsApiUpdatePartRequest** | [**PartsApiUpdatePartRequest**](PartsApiUpdatePartRequest.md) |  | 

### Return type

[**PartsApiUpdatePartResponse**](PartsApiUpdatePartResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

