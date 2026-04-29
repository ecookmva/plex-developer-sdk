# \SupplierReturnsAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SupplierReturnsApiGetSupplierReturn**](SupplierReturnsAPIAPI.md#SupplierReturnsApiGetSupplierReturn) | **Get** /purchasing/v1/supplier-returns/{id} | Get Supplier Return
[**SupplierReturnsApiListSupplierReturnLines**](SupplierReturnsAPIAPI.md#SupplierReturnsApiListSupplierReturnLines) | **Get** /purchasing/v1/supplier-returns/{id}/lines | List Supplier Return Lines
[**SupplierReturnsApiListSupplierReturns**](SupplierReturnsAPIAPI.md#SupplierReturnsApiListSupplierReturns) | **Get** /purchasing/v1/supplier-returns | List Supplier Returns



## SupplierReturnsApiGetSupplierReturn

> SupplierReturnsApiGetSupplierReturnResponse SupplierReturnsApiGetSupplierReturn(ctx, id).Execute()

Get Supplier Return



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
	resp, r, err := apiClient.SupplierReturnsAPIAPI.SupplierReturnsApiGetSupplierReturn(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SupplierReturnsAPIAPI.SupplierReturnsApiGetSupplierReturn``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SupplierReturnsApiGetSupplierReturn`: SupplierReturnsApiGetSupplierReturnResponse
	fmt.Fprintf(os.Stdout, "Response from `SupplierReturnsAPIAPI.SupplierReturnsApiGetSupplierReturn`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSupplierReturnsApiGetSupplierReturnRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**SupplierReturnsApiGetSupplierReturnResponse**](SupplierReturnsApiGetSupplierReturnResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SupplierReturnsApiListSupplierReturnLines

> []SupplierReturnsApiListSupplierReturnLinesItem SupplierReturnsApiListSupplierReturnLines(ctx, id).CreatedDateBegin(createdDateBegin).CreatedDateEnd(createdDateEnd).ModifiedDateBegin(modifiedDateBegin).ModifiedDateEnd(modifiedDateEnd).Execute()

List Supplier Return Lines



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
	createdDateBegin := time.Now() // time.Time | The date on which the record was created. (optional)
	createdDateEnd := time.Now() // time.Time | The date on which the record was created. (optional)
	modifiedDateBegin := time.Now() // time.Time | The date and time of the last modification to the record. (optional)
	modifiedDateEnd := time.Now() // time.Time | The date and time of the last modification to the record. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SupplierReturnsAPIAPI.SupplierReturnsApiListSupplierReturnLines(context.Background(), id).CreatedDateBegin(createdDateBegin).CreatedDateEnd(createdDateEnd).ModifiedDateBegin(modifiedDateBegin).ModifiedDateEnd(modifiedDateEnd).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SupplierReturnsAPIAPI.SupplierReturnsApiListSupplierReturnLines``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SupplierReturnsApiListSupplierReturnLines`: []SupplierReturnsApiListSupplierReturnLinesItem
	fmt.Fprintf(os.Stdout, "Response from `SupplierReturnsAPIAPI.SupplierReturnsApiListSupplierReturnLines`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSupplierReturnsApiListSupplierReturnLinesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createdDateBegin** | **time.Time** | The date on which the record was created. | 
 **createdDateEnd** | **time.Time** | The date on which the record was created. | 
 **modifiedDateBegin** | **time.Time** | The date and time of the last modification to the record. | 
 **modifiedDateEnd** | **time.Time** | The date and time of the last modification to the record. | 

### Return type

[**[]SupplierReturnsApiListSupplierReturnLinesItem**](SupplierReturnsApiListSupplierReturnLinesItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SupplierReturnsApiListSupplierReturns

> []SupplierReturnsApiListSupplierReturnsItem SupplierReturnsApiListSupplierReturns(ctx).Id(id).SupplierReturnNumber(supplierReturnNumber).SupplierId(supplierId).Status(status).Type_(type_).SupplierAddressId(supplierAddressId).CreatedById(createdById).CreatedDateBegin(createdDateBegin).CreatedDateEnd(createdDateEnd).ModifiedById(modifiedById).ModifiedDateBegin(modifiedDateBegin).ModifiedDateEnd(modifiedDateEnd).Execute()

List Supplier Returns



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
	id := []string{"00000000-0000-0000-0000-000000000000"} // []string | A List of Supplier Return IDs. (optional)
	supplierReturnNumber := "string" // string | Return Number. (optional)
	supplierId := "00000000-0000-0000-0000-000000000000" // string | The ID of the Supplier. (optional)
	status := "string" // string | Setup Table: Supplier Return Status (optional)
	type_ := "string" // string | Setup Table: Supplier Return Type (optional)
	supplierAddressId := "00000000-0000-0000-0000-000000000000" // string |  (optional)
	createdById := "00000000-0000-0000-0000-000000000000" // string | The ID of the user who created the record. (optional)
	createdDateBegin := time.Now() // time.Time | The date on which the record was created. (optional)
	createdDateEnd := time.Now() // time.Time | The date on which the record was created. (optional)
	modifiedById := "00000000-0000-0000-0000-000000000000" // string | The ID of the user who last modified the record. (optional)
	modifiedDateBegin := time.Now() // time.Time | The date and time of the last modification to the return. (optional)
	modifiedDateEnd := time.Now() // time.Time | The date and time of the last modification to the return. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SupplierReturnsAPIAPI.SupplierReturnsApiListSupplierReturns(context.Background()).Id(id).SupplierReturnNumber(supplierReturnNumber).SupplierId(supplierId).Status(status).Type_(type_).SupplierAddressId(supplierAddressId).CreatedById(createdById).CreatedDateBegin(createdDateBegin).CreatedDateEnd(createdDateEnd).ModifiedById(modifiedById).ModifiedDateBegin(modifiedDateBegin).ModifiedDateEnd(modifiedDateEnd).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SupplierReturnsAPIAPI.SupplierReturnsApiListSupplierReturns``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SupplierReturnsApiListSupplierReturns`: []SupplierReturnsApiListSupplierReturnsItem
	fmt.Fprintf(os.Stdout, "Response from `SupplierReturnsAPIAPI.SupplierReturnsApiListSupplierReturns`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSupplierReturnsApiListSupplierReturnsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **[]string** | A List of Supplier Return IDs. | 
 **supplierReturnNumber** | **string** | Return Number. | 
 **supplierId** | **string** | The ID of the Supplier. | 
 **status** | **string** | Setup Table: Supplier Return Status | 
 **type_** | **string** | Setup Table: Supplier Return Type | 
 **supplierAddressId** | **string** |  | 
 **createdById** | **string** | The ID of the user who created the record. | 
 **createdDateBegin** | **time.Time** | The date on which the record was created. | 
 **createdDateEnd** | **time.Time** | The date on which the record was created. | 
 **modifiedById** | **string** | The ID of the user who last modified the record. | 
 **modifiedDateBegin** | **time.Time** | The date and time of the last modification to the return. | 
 **modifiedDateEnd** | **time.Time** | The date and time of the last modification to the return. | 

### Return type

[**[]SupplierReturnsApiListSupplierReturnsItem**](SupplierReturnsApiListSupplierReturnsItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

