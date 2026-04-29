# \SupplyItemSuppliersAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SupplyItemSuppliersApiGetSupplyItemSupplier**](SupplyItemSuppliersAPIAPI.md#SupplyItemSuppliersApiGetSupplyItemSupplier) | **Get** /purchasing/v1/item-suppliers/{id} | Get Supply Item Supplier
[**SupplyItemSuppliersApiListPrices**](SupplyItemSuppliersAPIAPI.md#SupplyItemSuppliersApiListPrices) | **Get** /purchasing/v1/item-suppliers/{id}/prices | List Prices
[**SupplyItemSuppliersApiListSupplierItemSuppliers**](SupplyItemSuppliersAPIAPI.md#SupplyItemSuppliersApiListSupplierItemSuppliers) | **Get** /purchasing/v1/item-suppliers | List Supplier Item Suppliers



## SupplyItemSuppliersApiGetSupplyItemSupplier

> SupplyItemSuppliersApiGetSupplyItemSupplierResponse SupplyItemSuppliersApiGetSupplyItemSupplier(ctx, id).Execute()

Get Supply Item Supplier



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
	resp, r, err := apiClient.SupplyItemSuppliersAPIAPI.SupplyItemSuppliersApiGetSupplyItemSupplier(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SupplyItemSuppliersAPIAPI.SupplyItemSuppliersApiGetSupplyItemSupplier``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SupplyItemSuppliersApiGetSupplyItemSupplier`: SupplyItemSuppliersApiGetSupplyItemSupplierResponse
	fmt.Fprintf(os.Stdout, "Response from `SupplyItemSuppliersAPIAPI.SupplyItemSuppliersApiGetSupplyItemSupplier`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSupplyItemSuppliersApiGetSupplyItemSupplierRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**SupplyItemSuppliersApiGetSupplyItemSupplierResponse**](SupplyItemSuppliersApiGetSupplyItemSupplierResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SupplyItemSuppliersApiListPrices

> []SupplyItemSuppliersApiListPricesItem SupplyItemSuppliersApiListPrices(ctx, id).Execute()

List Prices



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
	resp, r, err := apiClient.SupplyItemSuppliersAPIAPI.SupplyItemSuppliersApiListPrices(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SupplyItemSuppliersAPIAPI.SupplyItemSuppliersApiListPrices``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SupplyItemSuppliersApiListPrices`: []SupplyItemSuppliersApiListPricesItem
	fmt.Fprintf(os.Stdout, "Response from `SupplyItemSuppliersAPIAPI.SupplyItemSuppliersApiListPrices`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSupplyItemSuppliersApiListPricesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]SupplyItemSuppliersApiListPricesItem**](SupplyItemSuppliersApiListPricesItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SupplyItemSuppliersApiListSupplierItemSuppliers

> []SupplyItemSuppliersApiListSupplierItemSuppliersItem SupplyItemSuppliersApiListSupplierItemSuppliers(ctx).Id(id).ItemId(itemId).SupplierId(supplierId).SupplierItemNumber(supplierItemNumber).Execute()

List Supplier Item Suppliers



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
	id := []string{"00000000-0000-0000-0000-000000000000"} // []string | A List of Item Supplier Resource IDs. (optional)
	itemId := "00000000-0000-0000-0000-000000000000" // string | The ID of the Supply Item. (optional)
	supplierId := "00000000-0000-0000-0000-000000000000" // string | The ID of the Supplier. (optional)
	supplierItemNumber := "string" // string | The Supplier's Item Number (this may be different from the Plex Supply Item Number). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SupplyItemSuppliersAPIAPI.SupplyItemSuppliersApiListSupplierItemSuppliers(context.Background()).Id(id).ItemId(itemId).SupplierId(supplierId).SupplierItemNumber(supplierItemNumber).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SupplyItemSuppliersAPIAPI.SupplyItemSuppliersApiListSupplierItemSuppliers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SupplyItemSuppliersApiListSupplierItemSuppliers`: []SupplyItemSuppliersApiListSupplierItemSuppliersItem
	fmt.Fprintf(os.Stdout, "Response from `SupplyItemSuppliersAPIAPI.SupplyItemSuppliersApiListSupplierItemSuppliers`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSupplyItemSuppliersApiListSupplierItemSuppliersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **[]string** | A List of Item Supplier Resource IDs. | 
 **itemId** | **string** | The ID of the Supply Item. | 
 **supplierId** | **string** | The ID of the Supplier. | 
 **supplierItemNumber** | **string** | The Supplier&#39;s Item Number (this may be different from the Plex Supply Item Number). | 

### Return type

[**[]SupplyItemSuppliersApiListSupplierItemSuppliersItem**](SupplyItemSuppliersApiListSupplierItemSuppliersItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

