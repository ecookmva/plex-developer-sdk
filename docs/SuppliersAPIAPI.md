# \SuppliersAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SuppliersApiCreateSupplier**](SuppliersAPIAPI.md#SuppliersApiCreateSupplier) | **Post** /mdm/v1/suppliers | Create Supplier
[**SuppliersApiCreateSupplierAddress**](SuppliersAPIAPI.md#SuppliersApiCreateSupplierAddress) | **Post** /mdm/v1/suppliers/{supplierId}/addresses | Create Supplier Address
[**SuppliersApiDeactivateSupplier**](SuppliersAPIAPI.md#SuppliersApiDeactivateSupplier) | **Post** /mdm/v1/suppliers/{id}/deactivate | Deactivate Supplier
[**SuppliersApiDeleteSupplierAddress**](SuppliersAPIAPI.md#SuppliersApiDeleteSupplierAddress) | **Delete** /mdm/v1/suppliers/{supplierId}/addresses/{addressId} | Delete Supplier Address
[**SuppliersApiGetSupplier**](SuppliersAPIAPI.md#SuppliersApiGetSupplier) | **Get** /mdm/v1/suppliers/{id} | Get Supplier
[**SuppliersApiGetSupplierAddress**](SuppliersAPIAPI.md#SuppliersApiGetSupplierAddress) | **Get** /mdm/v1/suppliers/{supplierId}/addresses/{addressId} | Get Supplier Address
[**SuppliersApiGetSupplierFinancials**](SuppliersAPIAPI.md#SuppliersApiGetSupplierFinancials) | **Get** /mdm/v1/suppliers/{id}/financials | Get Supplier Financials
[**SuppliersApiGetSupplierPurchasingDefaults**](SuppliersAPIAPI.md#SuppliersApiGetSupplierPurchasingDefaults) | **Get** /mdm/v1/suppliers/{id}/purchasing-defaults | Get Supplier Purchasing Defaults
[**SuppliersApiListSupplierAddresses**](SuppliersAPIAPI.md#SuppliersApiListSupplierAddresses) | **Get** /mdm/v1/suppliers/{supplierId}/addresses | List Supplier Addresses
[**SuppliersApiListSuppliers**](SuppliersAPIAPI.md#SuppliersApiListSuppliers) | **Get** /mdm/v1/suppliers | List Suppliers
[**SuppliersApiSyncSuppliers**](SuppliersAPIAPI.md#SuppliersApiSyncSuppliers) | **Post** /mdm/v1/suppliers/sync | Sync Suppliers
[**SuppliersApiUpdateSupplier**](SuppliersAPIAPI.md#SuppliersApiUpdateSupplier) | **Put** /mdm/v1/suppliers/{id} | Update Supplier
[**SuppliersApiUpdateSupplierAddress**](SuppliersAPIAPI.md#SuppliersApiUpdateSupplierAddress) | **Put** /mdm/v1/suppliers/{supplierId}/addresses/{addressId} | Update Supplier Address
[**SuppliersApiUpdateSupplierFinancials**](SuppliersAPIAPI.md#SuppliersApiUpdateSupplierFinancials) | **Put** /mdm/v2/suppliers/{id}/financials | Update Supplier Financials
[**SuppliersApiUpdateSupplierPurchasingDefaults**](SuppliersAPIAPI.md#SuppliersApiUpdateSupplierPurchasingDefaults) | **Put** /mdm/v1/suppliers/{id}/purchasing-defaults | Update Supplier Purchasing Defaults



## SuppliersApiCreateSupplier

> SuppliersApiCreateSupplier201Response SuppliersApiCreateSupplier(ctx).SuppliersApiCreateSupplierRequest(suppliersApiCreateSupplierRequest).Execute()

Create Supplier



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
	suppliersApiCreateSupplierRequest := *openapiclient.NewSuppliersApiCreateSupplierRequest() // SuppliersApiCreateSupplierRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SuppliersAPIAPI.SuppliersApiCreateSupplier(context.Background()).SuppliersApiCreateSupplierRequest(suppliersApiCreateSupplierRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SuppliersAPIAPI.SuppliersApiCreateSupplier``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SuppliersApiCreateSupplier`: SuppliersApiCreateSupplier201Response
	fmt.Fprintf(os.Stdout, "Response from `SuppliersAPIAPI.SuppliersApiCreateSupplier`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSuppliersApiCreateSupplierRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **suppliersApiCreateSupplierRequest** | [**SuppliersApiCreateSupplierRequest**](SuppliersApiCreateSupplierRequest.md) |  | 

### Return type

[**SuppliersApiCreateSupplier201Response**](SuppliersApiCreateSupplier201Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SuppliersApiCreateSupplierAddress

> SuppliersApiCreateSupplierAddress201Response SuppliersApiCreateSupplierAddress(ctx, supplierId).SuppliersApiCreateSupplierAddressRequest(suppliersApiCreateSupplierAddressRequest).Execute()

Create Supplier Address



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
	supplierId := "00000000-0000-0000-0000-000000000000" // string | 
	suppliersApiCreateSupplierAddressRequest := *openapiclient.NewSuppliersApiCreateSupplierAddressRequest() // SuppliersApiCreateSupplierAddressRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SuppliersAPIAPI.SuppliersApiCreateSupplierAddress(context.Background(), supplierId).SuppliersApiCreateSupplierAddressRequest(suppliersApiCreateSupplierAddressRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SuppliersAPIAPI.SuppliersApiCreateSupplierAddress``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SuppliersApiCreateSupplierAddress`: SuppliersApiCreateSupplierAddress201Response
	fmt.Fprintf(os.Stdout, "Response from `SuppliersAPIAPI.SuppliersApiCreateSupplierAddress`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**supplierId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSuppliersApiCreateSupplierAddressRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **suppliersApiCreateSupplierAddressRequest** | [**SuppliersApiCreateSupplierAddressRequest**](SuppliersApiCreateSupplierAddressRequest.md) |  | 

### Return type

[**SuppliersApiCreateSupplierAddress201Response**](SuppliersApiCreateSupplierAddress201Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SuppliersApiDeactivateSupplier

> SuppliersApiDeactivateSupplier(ctx, id).SuppliersApiDeactivateSupplierRequest(suppliersApiDeactivateSupplierRequest).Execute()

Deactivate Supplier



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
	suppliersApiDeactivateSupplierRequest := *openapiclient.NewSuppliersApiDeactivateSupplierRequest() // SuppliersApiDeactivateSupplierRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.SuppliersAPIAPI.SuppliersApiDeactivateSupplier(context.Background(), id).SuppliersApiDeactivateSupplierRequest(suppliersApiDeactivateSupplierRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SuppliersAPIAPI.SuppliersApiDeactivateSupplier``: %v\n", err)
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

Other parameters are passed through a pointer to a apiSuppliersApiDeactivateSupplierRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **suppliersApiDeactivateSupplierRequest** | [**SuppliersApiDeactivateSupplierRequest**](SuppliersApiDeactivateSupplierRequest.md) |  | 

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


## SuppliersApiDeleteSupplierAddress

> SuppliersApiDeleteSupplierAddress(ctx, supplierId, addressId).Execute()

Delete Supplier Address



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
	supplierId := "00000000-0000-0000-0000-000000000000" // string | 
	addressId := "00000000-0000-0000-0000-000000000000" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.SuppliersAPIAPI.SuppliersApiDeleteSupplierAddress(context.Background(), supplierId, addressId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SuppliersAPIAPI.SuppliersApiDeleteSupplierAddress``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**supplierId** | **string** |  | 
**addressId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSuppliersApiDeleteSupplierAddressRequest struct via the builder pattern


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


## SuppliersApiGetSupplier

> SuppliersApiGetSupplierResponse SuppliersApiGetSupplier(ctx, id).Execute()

Get Supplier



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
	resp, r, err := apiClient.SuppliersAPIAPI.SuppliersApiGetSupplier(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SuppliersAPIAPI.SuppliersApiGetSupplier``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SuppliersApiGetSupplier`: SuppliersApiGetSupplierResponse
	fmt.Fprintf(os.Stdout, "Response from `SuppliersAPIAPI.SuppliersApiGetSupplier`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSuppliersApiGetSupplierRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**SuppliersApiGetSupplierResponse**](SuppliersApiGetSupplierResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SuppliersApiGetSupplierAddress

> SuppliersApiGetSupplierAddressResponse SuppliersApiGetSupplierAddress(ctx, supplierId, addressId).Execute()

Get Supplier Address



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
	supplierId := "00000000-0000-0000-0000-000000000000" // string | 
	addressId := "00000000-0000-0000-0000-000000000000" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SuppliersAPIAPI.SuppliersApiGetSupplierAddress(context.Background(), supplierId, addressId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SuppliersAPIAPI.SuppliersApiGetSupplierAddress``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SuppliersApiGetSupplierAddress`: SuppliersApiGetSupplierAddressResponse
	fmt.Fprintf(os.Stdout, "Response from `SuppliersAPIAPI.SuppliersApiGetSupplierAddress`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**supplierId** | **string** |  | 
**addressId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSuppliersApiGetSupplierAddressRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**SuppliersApiGetSupplierAddressResponse**](SuppliersApiGetSupplierAddressResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SuppliersApiGetSupplierFinancials

> SuppliersApiGetSupplierFinancialsResponse SuppliersApiGetSupplierFinancials(ctx, id).Execute()

Get Supplier Financials



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
	resp, r, err := apiClient.SuppliersAPIAPI.SuppliersApiGetSupplierFinancials(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SuppliersAPIAPI.SuppliersApiGetSupplierFinancials``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SuppliersApiGetSupplierFinancials`: SuppliersApiGetSupplierFinancialsResponse
	fmt.Fprintf(os.Stdout, "Response from `SuppliersAPIAPI.SuppliersApiGetSupplierFinancials`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSuppliersApiGetSupplierFinancialsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**SuppliersApiGetSupplierFinancialsResponse**](SuppliersApiGetSupplierFinancialsResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SuppliersApiGetSupplierPurchasingDefaults

> SuppliersApiGetSupplierPurchasingDefaultsResponse SuppliersApiGetSupplierPurchasingDefaults(ctx, id).Execute()

Get Supplier Purchasing Defaults



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
	resp, r, err := apiClient.SuppliersAPIAPI.SuppliersApiGetSupplierPurchasingDefaults(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SuppliersAPIAPI.SuppliersApiGetSupplierPurchasingDefaults``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SuppliersApiGetSupplierPurchasingDefaults`: SuppliersApiGetSupplierPurchasingDefaultsResponse
	fmt.Fprintf(os.Stdout, "Response from `SuppliersAPIAPI.SuppliersApiGetSupplierPurchasingDefaults`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSuppliersApiGetSupplierPurchasingDefaultsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**SuppliersApiGetSupplierPurchasingDefaultsResponse**](SuppliersApiGetSupplierPurchasingDefaultsResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SuppliersApiListSupplierAddresses

> []SuppliersApiListSupplierAddressesItem SuppliersApiListSupplierAddresses(ctx, supplierId).Id(id).Code(code).CreatedById(createdById).CreatedDateBegin(createdDateBegin).CreatedDateEnd(createdDateEnd).ModifiedById(modifiedById).ModifiedDateBegin(modifiedDateBegin).ModifiedDateEnd(modifiedDateEnd).Execute()

List Supplier Addresses



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
	supplierId := "00000000-0000-0000-0000-000000000000" // string | 
	id := []string{"00000000-0000-0000-0000-000000000000"} // []string | A list of supplier address IDs. (optional)
	code := "string" // string | This must be unique in the context of a supplier. (optional)
	createdById := "00000000-0000-0000-0000-000000000000" // string | IAM Account ID (optional)
	createdDateBegin := time.Now() // time.Time |  (optional)
	createdDateEnd := time.Now() // time.Time |  (optional)
	modifiedById := "00000000-0000-0000-0000-000000000000" // string | IAM Account ID (optional)
	modifiedDateBegin := time.Now() // time.Time |  (optional)
	modifiedDateEnd := time.Now() // time.Time |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SuppliersAPIAPI.SuppliersApiListSupplierAddresses(context.Background(), supplierId).Id(id).Code(code).CreatedById(createdById).CreatedDateBegin(createdDateBegin).CreatedDateEnd(createdDateEnd).ModifiedById(modifiedById).ModifiedDateBegin(modifiedDateBegin).ModifiedDateEnd(modifiedDateEnd).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SuppliersAPIAPI.SuppliersApiListSupplierAddresses``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SuppliersApiListSupplierAddresses`: []SuppliersApiListSupplierAddressesItem
	fmt.Fprintf(os.Stdout, "Response from `SuppliersAPIAPI.SuppliersApiListSupplierAddresses`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**supplierId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSuppliersApiListSupplierAddressesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **id** | **[]string** | A list of supplier address IDs. | 
 **code** | **string** | This must be unique in the context of a supplier. | 
 **createdById** | **string** | IAM Account ID | 
 **createdDateBegin** | **time.Time** |  | 
 **createdDateEnd** | **time.Time** |  | 
 **modifiedById** | **string** | IAM Account ID | 
 **modifiedDateBegin** | **time.Time** |  | 
 **modifiedDateEnd** | **time.Time** |  | 

### Return type

[**[]SuppliersApiListSupplierAddressesItem**](SuppliersApiListSupplierAddressesItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SuppliersApiListSuppliers

> []SuppliersApiListSuppliersItem SuppliersApiListSuppliers(ctx).Id(id).Code(code).OldCode(oldCode).Name(name).Language(language).Category(category).Status(status).Type_(type_).ParentSupplierId(parentSupplierId).CreatedById(createdById).CreatedDateBegin(createdDateBegin).CreatedDateEnd(createdDateEnd).ModifiedById(modifiedById).ModifiedDateBegin(modifiedDateBegin).ModifiedDateEnd(modifiedDateEnd).Execute()

List Suppliers



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
	id := []string{"00000000-0000-0000-0000-000000000000"} // []string | A list of supplier IDs. (optional)
	code := "string" // string | The Supplier Code used in Plex to identify the supplier. This must be unique in the context of a tenant. (optional)
	oldCode := "string" // string |  (optional)
	name := "string" // string |  (optional)
	language := "string" // string |  (optional)
	category := "string" // string | Setup Table: Supplier_Category (optional)
	status := "string" // string | Setup Table: Supplier_Status (optional)
	type_ := "string" // string | Setup Table: Supplier_Type (optional)
	parentSupplierId := "00000000-0000-0000-0000-000000000000" // string | The ID of a parent supplier. (optional)
	createdById := "00000000-0000-0000-0000-000000000000" // string | IAM Account ID (optional)
	createdDateBegin := time.Now() // time.Time |  (optional)
	createdDateEnd := time.Now() // time.Time |  (optional)
	modifiedById := "00000000-0000-0000-0000-000000000000" // string | IAM Account ID (optional)
	modifiedDateBegin := time.Now() // time.Time |  (optional)
	modifiedDateEnd := time.Now() // time.Time |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SuppliersAPIAPI.SuppliersApiListSuppliers(context.Background()).Id(id).Code(code).OldCode(oldCode).Name(name).Language(language).Category(category).Status(status).Type_(type_).ParentSupplierId(parentSupplierId).CreatedById(createdById).CreatedDateBegin(createdDateBegin).CreatedDateEnd(createdDateEnd).ModifiedById(modifiedById).ModifiedDateBegin(modifiedDateBegin).ModifiedDateEnd(modifiedDateEnd).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SuppliersAPIAPI.SuppliersApiListSuppliers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SuppliersApiListSuppliers`: []SuppliersApiListSuppliersItem
	fmt.Fprintf(os.Stdout, "Response from `SuppliersAPIAPI.SuppliersApiListSuppliers`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSuppliersApiListSuppliersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **[]string** | A list of supplier IDs. | 
 **code** | **string** | The Supplier Code used in Plex to identify the supplier. This must be unique in the context of a tenant. | 
 **oldCode** | **string** |  | 
 **name** | **string** |  | 
 **language** | **string** |  | 
 **category** | **string** | Setup Table: Supplier_Category | 
 **status** | **string** | Setup Table: Supplier_Status | 
 **type_** | **string** | Setup Table: Supplier_Type | 
 **parentSupplierId** | **string** | The ID of a parent supplier. | 
 **createdById** | **string** | IAM Account ID | 
 **createdDateBegin** | **time.Time** |  | 
 **createdDateEnd** | **time.Time** |  | 
 **modifiedById** | **string** | IAM Account ID | 
 **modifiedDateBegin** | **time.Time** |  | 
 **modifiedDateEnd** | **time.Time** |  | 

### Return type

[**[]SuppliersApiListSuppliersItem**](SuppliersApiListSuppliersItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SuppliersApiSyncSuppliers

> SuppliersApiSyncSuppliers(ctx).SuppliersApiSyncSuppliersRequest(suppliersApiSyncSuppliersRequest).Execute()

Sync Suppliers



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
	suppliersApiSyncSuppliersRequest := *openapiclient.NewSuppliersApiSyncSuppliersRequest() // SuppliersApiSyncSuppliersRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.SuppliersAPIAPI.SuppliersApiSyncSuppliers(context.Background()).SuppliersApiSyncSuppliersRequest(suppliersApiSyncSuppliersRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SuppliersAPIAPI.SuppliersApiSyncSuppliers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSuppliersApiSyncSuppliersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **suppliersApiSyncSuppliersRequest** | [**SuppliersApiSyncSuppliersRequest**](SuppliersApiSyncSuppliersRequest.md) |  | 

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


## SuppliersApiUpdateSupplier

> SuppliersApiUpdateSupplierResponse SuppliersApiUpdateSupplier(ctx, id).SuppliersApiUpdateSupplierRequest(suppliersApiUpdateSupplierRequest).Execute()

Update Supplier



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
	suppliersApiUpdateSupplierRequest := *openapiclient.NewSuppliersApiUpdateSupplierRequest() // SuppliersApiUpdateSupplierRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SuppliersAPIAPI.SuppliersApiUpdateSupplier(context.Background(), id).SuppliersApiUpdateSupplierRequest(suppliersApiUpdateSupplierRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SuppliersAPIAPI.SuppliersApiUpdateSupplier``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SuppliersApiUpdateSupplier`: SuppliersApiUpdateSupplierResponse
	fmt.Fprintf(os.Stdout, "Response from `SuppliersAPIAPI.SuppliersApiUpdateSupplier`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSuppliersApiUpdateSupplierRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **suppliersApiUpdateSupplierRequest** | [**SuppliersApiUpdateSupplierRequest**](SuppliersApiUpdateSupplierRequest.md) |  | 

### Return type

[**SuppliersApiUpdateSupplierResponse**](SuppliersApiUpdateSupplierResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SuppliersApiUpdateSupplierAddress

> SuppliersApiUpdateSupplierAddressResponse SuppliersApiUpdateSupplierAddress(ctx, supplierId, addressId).SuppliersApiUpdateSupplierAddressRequest(suppliersApiUpdateSupplierAddressRequest).Execute()

Update Supplier Address



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
	supplierId := "00000000-0000-0000-0000-000000000000" // string | 
	addressId := "00000000-0000-0000-0000-000000000000" // string | 
	suppliersApiUpdateSupplierAddressRequest := *openapiclient.NewSuppliersApiUpdateSupplierAddressRequest() // SuppliersApiUpdateSupplierAddressRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SuppliersAPIAPI.SuppliersApiUpdateSupplierAddress(context.Background(), supplierId, addressId).SuppliersApiUpdateSupplierAddressRequest(suppliersApiUpdateSupplierAddressRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SuppliersAPIAPI.SuppliersApiUpdateSupplierAddress``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SuppliersApiUpdateSupplierAddress`: SuppliersApiUpdateSupplierAddressResponse
	fmt.Fprintf(os.Stdout, "Response from `SuppliersAPIAPI.SuppliersApiUpdateSupplierAddress`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**supplierId** | **string** |  | 
**addressId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSuppliersApiUpdateSupplierAddressRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **suppliersApiUpdateSupplierAddressRequest** | [**SuppliersApiUpdateSupplierAddressRequest**](SuppliersApiUpdateSupplierAddressRequest.md) |  | 

### Return type

[**SuppliersApiUpdateSupplierAddressResponse**](SuppliersApiUpdateSupplierAddressResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SuppliersApiUpdateSupplierFinancials

> SuppliersApiUpdateSupplierFinancialsResponse SuppliersApiUpdateSupplierFinancials(ctx, id).SuppliersApiUpdateSupplierFinancialsRequest(suppliersApiUpdateSupplierFinancialsRequest).Execute()

Update Supplier Financials



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
	suppliersApiUpdateSupplierFinancialsRequest := *openapiclient.NewSuppliersApiUpdateSupplierFinancialsRequest() // SuppliersApiUpdateSupplierFinancialsRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SuppliersAPIAPI.SuppliersApiUpdateSupplierFinancials(context.Background(), id).SuppliersApiUpdateSupplierFinancialsRequest(suppliersApiUpdateSupplierFinancialsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SuppliersAPIAPI.SuppliersApiUpdateSupplierFinancials``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SuppliersApiUpdateSupplierFinancials`: SuppliersApiUpdateSupplierFinancialsResponse
	fmt.Fprintf(os.Stdout, "Response from `SuppliersAPIAPI.SuppliersApiUpdateSupplierFinancials`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSuppliersApiUpdateSupplierFinancialsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **suppliersApiUpdateSupplierFinancialsRequest** | [**SuppliersApiUpdateSupplierFinancialsRequest**](SuppliersApiUpdateSupplierFinancialsRequest.md) |  | 

### Return type

[**SuppliersApiUpdateSupplierFinancialsResponse**](SuppliersApiUpdateSupplierFinancialsResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SuppliersApiUpdateSupplierPurchasingDefaults

> SuppliersApiUpdateSupplierPurchasingDefaultsResponse SuppliersApiUpdateSupplierPurchasingDefaults(ctx, id).SuppliersApiUpdateSupplierPurchasingDefaultsRequest(suppliersApiUpdateSupplierPurchasingDefaultsRequest).Execute()

Update Supplier Purchasing Defaults



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
	suppliersApiUpdateSupplierPurchasingDefaultsRequest := *openapiclient.NewSuppliersApiUpdateSupplierPurchasingDefaultsRequest() // SuppliersApiUpdateSupplierPurchasingDefaultsRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SuppliersAPIAPI.SuppliersApiUpdateSupplierPurchasingDefaults(context.Background(), id).SuppliersApiUpdateSupplierPurchasingDefaultsRequest(suppliersApiUpdateSupplierPurchasingDefaultsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SuppliersAPIAPI.SuppliersApiUpdateSupplierPurchasingDefaults``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SuppliersApiUpdateSupplierPurchasingDefaults`: SuppliersApiUpdateSupplierPurchasingDefaultsResponse
	fmt.Fprintf(os.Stdout, "Response from `SuppliersAPIAPI.SuppliersApiUpdateSupplierPurchasingDefaults`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSuppliersApiUpdateSupplierPurchasingDefaultsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **suppliersApiUpdateSupplierPurchasingDefaultsRequest** | [**SuppliersApiUpdateSupplierPurchasingDefaultsRequest**](SuppliersApiUpdateSupplierPurchasingDefaultsRequest.md) |  | 

### Return type

[**SuppliersApiUpdateSupplierPurchasingDefaultsResponse**](SuppliersApiUpdateSupplierPurchasingDefaultsResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

