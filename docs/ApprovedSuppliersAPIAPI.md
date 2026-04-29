# \ApprovedSuppliersAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ApprovedSuppliersApiGetApprovedSupplier**](ApprovedSuppliersAPIAPI.md#ApprovedSuppliersApiGetApprovedSupplier) | **Get** /purchasing/v1/approved-suppliers/{id} | Get Approved Supplier
[**ApprovedSuppliersApiGetEDIDetails**](ApprovedSuppliersAPIAPI.md#ApprovedSuppliersApiGetEDIDetails) | **Get** /purchasing/v1/approved-suppliers/{id}/edi-details | Get EDI Details
[**ApprovedSuppliersApiGetMRPDetails**](ApprovedSuppliersAPIAPI.md#ApprovedSuppliersApiGetMRPDetails) | **Get** /purchasing/v1/approved-suppliers/{id}/mrp-details | Get MRP Details
[**ApprovedSuppliersApiListApprovedSuppliers**](ApprovedSuppliersAPIAPI.md#ApprovedSuppliersApiListApprovedSuppliers) | **Get** /purchasing/v1/approved-suppliers | List Approved Suppliers
[**ApprovedSuppliersApiListPrices**](ApprovedSuppliersAPIAPI.md#ApprovedSuppliersApiListPrices) | **Get** /purchasing/v1/approved-suppliers/{id}/prices | List Prices



## ApprovedSuppliersApiGetApprovedSupplier

> ApprovedSuppliersApiGetApprovedSupplierResponse ApprovedSuppliersApiGetApprovedSupplier(ctx, id).Execute()

Get Approved Supplier



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
	resp, r, err := apiClient.ApprovedSuppliersAPIAPI.ApprovedSuppliersApiGetApprovedSupplier(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApprovedSuppliersAPIAPI.ApprovedSuppliersApiGetApprovedSupplier``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApprovedSuppliersApiGetApprovedSupplier`: ApprovedSuppliersApiGetApprovedSupplierResponse
	fmt.Fprintf(os.Stdout, "Response from `ApprovedSuppliersAPIAPI.ApprovedSuppliersApiGetApprovedSupplier`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiApprovedSuppliersApiGetApprovedSupplierRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ApprovedSuppliersApiGetApprovedSupplierResponse**](ApprovedSuppliersApiGetApprovedSupplierResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApprovedSuppliersApiGetEDIDetails

> ApprovedSuppliersApiGetEDIDetailsResponse ApprovedSuppliersApiGetEDIDetails(ctx, id).Execute()

Get EDI Details



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
	id := "00000000-0000-0000-0000-000000000000" // string | The resource ID of the approved supplier.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApprovedSuppliersAPIAPI.ApprovedSuppliersApiGetEDIDetails(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApprovedSuppliersAPIAPI.ApprovedSuppliersApiGetEDIDetails``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApprovedSuppliersApiGetEDIDetails`: ApprovedSuppliersApiGetEDIDetailsResponse
	fmt.Fprintf(os.Stdout, "Response from `ApprovedSuppliersAPIAPI.ApprovedSuppliersApiGetEDIDetails`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The resource ID of the approved supplier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiApprovedSuppliersApiGetEDIDetailsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ApprovedSuppliersApiGetEDIDetailsResponse**](ApprovedSuppliersApiGetEDIDetailsResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApprovedSuppliersApiGetMRPDetails

> ApprovedSuppliersApiGetMRPDetailsResponse ApprovedSuppliersApiGetMRPDetails(ctx, id).Execute()

Get MRP Details



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
	id := "00000000-0000-0000-0000-000000000000" // string | The resource ID of the approved supplier.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApprovedSuppliersAPIAPI.ApprovedSuppliersApiGetMRPDetails(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApprovedSuppliersAPIAPI.ApprovedSuppliersApiGetMRPDetails``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApprovedSuppliersApiGetMRPDetails`: ApprovedSuppliersApiGetMRPDetailsResponse
	fmt.Fprintf(os.Stdout, "Response from `ApprovedSuppliersAPIAPI.ApprovedSuppliersApiGetMRPDetails`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The resource ID of the approved supplier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiApprovedSuppliersApiGetMRPDetailsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ApprovedSuppliersApiGetMRPDetailsResponse**](ApprovedSuppliersApiGetMRPDetailsResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApprovedSuppliersApiListApprovedSuppliers

> []ApprovedSuppliersApiListApprovedSuppliersItem ApprovedSuppliersApiListApprovedSuppliers(ctx).Id(id).PartId(partId).OperationCode(operationCode).SupplierId(supplierId).Execute()

List Approved Suppliers



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
	id := []string{"00000000-0000-0000-0000-000000000000"} // []string | A list of approved supplier IDs. (optional)
	partId := "00000000-0000-0000-0000-000000000000" // string | The part ID. (optional)
	operationCode := "string" // string | Application: Operation List (optional)
	supplierId := "00000000-0000-0000-0000-000000000000" // string | The supplier ID. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApprovedSuppliersAPIAPI.ApprovedSuppliersApiListApprovedSuppliers(context.Background()).Id(id).PartId(partId).OperationCode(operationCode).SupplierId(supplierId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApprovedSuppliersAPIAPI.ApprovedSuppliersApiListApprovedSuppliers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApprovedSuppliersApiListApprovedSuppliers`: []ApprovedSuppliersApiListApprovedSuppliersItem
	fmt.Fprintf(os.Stdout, "Response from `ApprovedSuppliersAPIAPI.ApprovedSuppliersApiListApprovedSuppliers`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApprovedSuppliersApiListApprovedSuppliersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **[]string** | A list of approved supplier IDs. | 
 **partId** | **string** | The part ID. | 
 **operationCode** | **string** | Application: Operation List | 
 **supplierId** | **string** | The supplier ID. | 

### Return type

[**[]ApprovedSuppliersApiListApprovedSuppliersItem**](ApprovedSuppliersApiListApprovedSuppliersItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApprovedSuppliersApiListPrices

> []ApprovedSuppliersApiListPricesItem ApprovedSuppliersApiListPrices(ctx, id).Active(active).EffectiveDateBegin(effectiveDateBegin).EffectiveDateEnd(effectiveDateEnd).ExpirationDateBegin(expirationDateBegin).ExpirationDateEnd(expirationDateEnd).ModifiedById(modifiedById).ModifiedDateBegin(modifiedDateBegin).ModifiedDateEnd(modifiedDateEnd).Execute()

List Prices



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
	id := "00000000-0000-0000-0000-000000000000" // string | 
	active := false // bool |  (optional)
	effectiveDateBegin := time.Now() // time.Time | The date on which the price is effective. (optional)
	effectiveDateEnd := time.Now() // time.Time | The date on which the price is effective. (optional)
	expirationDateBegin := time.Now() // time.Time | The date on which the price expires. (optional)
	expirationDateEnd := time.Now() // time.Time | The date on which the price expires. (optional)
	modifiedById := "00000000-0000-0000-0000-000000000000" // string | The ID of the last person to modify the record. (optional)
	modifiedDateBegin := time.Now() // time.Time | The date on which the record was last modified. (optional)
	modifiedDateEnd := time.Now() // time.Time | The date on which the record was last modified. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApprovedSuppliersAPIAPI.ApprovedSuppliersApiListPrices(context.Background(), id).Active(active).EffectiveDateBegin(effectiveDateBegin).EffectiveDateEnd(effectiveDateEnd).ExpirationDateBegin(expirationDateBegin).ExpirationDateEnd(expirationDateEnd).ModifiedById(modifiedById).ModifiedDateBegin(modifiedDateBegin).ModifiedDateEnd(modifiedDateEnd).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApprovedSuppliersAPIAPI.ApprovedSuppliersApiListPrices``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApprovedSuppliersApiListPrices`: []ApprovedSuppliersApiListPricesItem
	fmt.Fprintf(os.Stdout, "Response from `ApprovedSuppliersAPIAPI.ApprovedSuppliersApiListPrices`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiApprovedSuppliersApiListPricesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **active** | **bool** |  | 
 **effectiveDateBegin** | **time.Time** | The date on which the price is effective. | 
 **effectiveDateEnd** | **time.Time** | The date on which the price is effective. | 
 **expirationDateBegin** | **time.Time** | The date on which the price expires. | 
 **expirationDateEnd** | **time.Time** | The date on which the price expires. | 
 **modifiedById** | **string** | The ID of the last person to modify the record. | 
 **modifiedDateBegin** | **time.Time** | The date on which the record was last modified. | 
 **modifiedDateEnd** | **time.Time** | The date on which the record was last modified. | 

### Return type

[**[]ApprovedSuppliersApiListPricesItem**](ApprovedSuppliersApiListPricesItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

