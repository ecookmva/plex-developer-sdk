# \ReceiptsAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ReceiptsApiGetReceipt**](ReceiptsAPIAPI.md#ReceiptsApiGetReceipt) | **Get** /purchasing/v1/receipts/{id} | Get Receipt
[**ReceiptsApiListReceipts**](ReceiptsAPIAPI.md#ReceiptsApiListReceipts) | **Get** /purchasing/v1/receipts | List Receipts



## ReceiptsApiGetReceipt

> ReceiptsApiGetReceiptResponse ReceiptsApiGetReceipt(ctx, id).Execute()

Get Receipt



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
	resp, r, err := apiClient.ReceiptsAPIAPI.ReceiptsApiGetReceipt(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ReceiptsAPIAPI.ReceiptsApiGetReceipt``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ReceiptsApiGetReceipt`: ReceiptsApiGetReceiptResponse
	fmt.Fprintf(os.Stdout, "Response from `ReceiptsAPIAPI.ReceiptsApiGetReceipt`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiReceiptsApiGetReceiptRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ReceiptsApiGetReceiptResponse**](ReceiptsApiGetReceiptResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ReceiptsApiListReceipts

> []ReceiptsApiListReceiptsItem ReceiptsApiListReceipts(ctx).Id(id).POLineItemId(pOLineItemId).SupplierId(supplierId).POId(pOId).PartId(partId).ItemId(itemId).OperationCode(operationCode).ReleaseId(releaseId).SupplierShipperNumber(supplierShipperNumber).ReceiveDateBegin(receiveDateBegin).ReceiveDateEnd(receiveDateEnd).ReceivedById(receivedById).Execute()

List Receipts



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
	id := []string{"00000000-0000-0000-0000-000000000000"} // []string | A list of receipt IDs. (optional)
	pOLineItemId := "00000000-0000-0000-0000-000000000000" // string |  (optional)
	supplierId := "00000000-0000-0000-0000-000000000000" // string |  (optional)
	pOId := "00000000-0000-0000-0000-000000000000" // string |  (optional)
	partId := "00000000-0000-0000-0000-000000000000" // string |  (optional)
	itemId := "00000000-0000-0000-0000-000000000000" // string |  (optional)
	operationCode := "string" // string |  (optional)
	releaseId := "00000000-0000-0000-0000-000000000000" // string |  (optional)
	supplierShipperNumber := "string" // string |  (optional)
	receiveDateBegin := time.Now() // time.Time | The date on which the receipt was received. (optional)
	receiveDateEnd := time.Now() // time.Time | The date on which the receipt was received. (optional)
	receivedById := "00000000-0000-0000-0000-000000000000" // string | The IAM Account ID of the user who received the receipt. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ReceiptsAPIAPI.ReceiptsApiListReceipts(context.Background()).Id(id).POLineItemId(pOLineItemId).SupplierId(supplierId).POId(pOId).PartId(partId).ItemId(itemId).OperationCode(operationCode).ReleaseId(releaseId).SupplierShipperNumber(supplierShipperNumber).ReceiveDateBegin(receiveDateBegin).ReceiveDateEnd(receiveDateEnd).ReceivedById(receivedById).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ReceiptsAPIAPI.ReceiptsApiListReceipts``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ReceiptsApiListReceipts`: []ReceiptsApiListReceiptsItem
	fmt.Fprintf(os.Stdout, "Response from `ReceiptsAPIAPI.ReceiptsApiListReceipts`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiReceiptsApiListReceiptsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **[]string** | A list of receipt IDs. | 
 **pOLineItemId** | **string** |  | 
 **supplierId** | **string** |  | 
 **pOId** | **string** |  | 
 **partId** | **string** |  | 
 **itemId** | **string** |  | 
 **operationCode** | **string** |  | 
 **releaseId** | **string** |  | 
 **supplierShipperNumber** | **string** |  | 
 **receiveDateBegin** | **time.Time** | The date on which the receipt was received. | 
 **receiveDateEnd** | **time.Time** | The date on which the receipt was received. | 
 **receivedById** | **string** | The IAM Account ID of the user who received the receipt. | 

### Return type

[**[]ReceiptsApiListReceiptsItem**](ReceiptsApiListReceiptsItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

