# \InventoryTrackingAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**InventoryTrackingApiGetContainerBySerialNumber**](InventoryTrackingAPIAPI.md#InventoryTrackingApiGetContainerBySerialNumber) | **Get** /inventory-tracking/v1/containers/{serialNumber} | Get Container By Serial Number
[**InventoryTrackingApiGetMasterUnit**](InventoryTrackingAPIAPI.md#InventoryTrackingApiGetMasterUnit) | **Get** /inventory-tracking/v1/master-units/{id} | Get Master Unit
[**InventoryTrackingApiListMasterUnits**](InventoryTrackingAPIAPI.md#InventoryTrackingApiListMasterUnits) | **Get** /inventory-tracking/v1/master-units | List Master Units
[**InventoryTrackingApiUpdateContainerRFID**](InventoryTrackingAPIAPI.md#InventoryTrackingApiUpdateContainerRFID) | **Put** /inventory-tracking/v1/containers/{serialNo}/rfid | Update Container RFID
[**InventoryTrackingApiUpdateMasterUnitRFID**](InventoryTrackingAPIAPI.md#InventoryTrackingApiUpdateMasterUnitRFID) | **Put** /inventory-tracking/v1/master-units/{id}/rfid | Update Master Unit RFID



## InventoryTrackingApiGetContainerBySerialNumber

> InventoryTrackingApiGetContainerBySerialNumberResponse InventoryTrackingApiGetContainerBySerialNumber(ctx, serialNumber).Execute()

Get Container By Serial Number



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
	serialNumber := "string" // string | The container serial number.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InventoryTrackingAPIAPI.InventoryTrackingApiGetContainerBySerialNumber(context.Background(), serialNumber).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InventoryTrackingAPIAPI.InventoryTrackingApiGetContainerBySerialNumber``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `InventoryTrackingApiGetContainerBySerialNumber`: InventoryTrackingApiGetContainerBySerialNumberResponse
	fmt.Fprintf(os.Stdout, "Response from `InventoryTrackingAPIAPI.InventoryTrackingApiGetContainerBySerialNumber`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serialNumber** | **string** | The container serial number. | 

### Other Parameters

Other parameters are passed through a pointer to a apiInventoryTrackingApiGetContainerBySerialNumberRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**InventoryTrackingApiGetContainerBySerialNumberResponse**](InventoryTrackingApiGetContainerBySerialNumberResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## InventoryTrackingApiGetMasterUnit

> InventoryTrackingApiGetMasterUnitResponse InventoryTrackingApiGetMasterUnit(ctx, id).Execute()

Get Master Unit



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
	id := "00000000-0000-0000-0000-000000000000" // string | A unique identifier of the master unit.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InventoryTrackingAPIAPI.InventoryTrackingApiGetMasterUnit(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InventoryTrackingAPIAPI.InventoryTrackingApiGetMasterUnit``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `InventoryTrackingApiGetMasterUnit`: InventoryTrackingApiGetMasterUnitResponse
	fmt.Fprintf(os.Stdout, "Response from `InventoryTrackingAPIAPI.InventoryTrackingApiGetMasterUnit`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | A unique identifier of the master unit. | 

### Other Parameters

Other parameters are passed through a pointer to a apiInventoryTrackingApiGetMasterUnitRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**InventoryTrackingApiGetMasterUnitResponse**](InventoryTrackingApiGetMasterUnitResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## InventoryTrackingApiListMasterUnits

> []InventoryTrackingApiListMasterUnitsItem InventoryTrackingApiListMasterUnits(ctx).InventoryTrackingApiListMasterUnitsRequest(inventoryTrackingApiListMasterUnitsRequest).Execute()

List Master Units



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
	inventoryTrackingApiListMasterUnitsRequest := *openapiclient.NewInventoryTrackingApiListMasterUnitsRequest() // InventoryTrackingApiListMasterUnitsRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InventoryTrackingAPIAPI.InventoryTrackingApiListMasterUnits(context.Background()).InventoryTrackingApiListMasterUnitsRequest(inventoryTrackingApiListMasterUnitsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InventoryTrackingAPIAPI.InventoryTrackingApiListMasterUnits``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `InventoryTrackingApiListMasterUnits`: []InventoryTrackingApiListMasterUnitsItem
	fmt.Fprintf(os.Stdout, "Response from `InventoryTrackingAPIAPI.InventoryTrackingApiListMasterUnits`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiInventoryTrackingApiListMasterUnitsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **inventoryTrackingApiListMasterUnitsRequest** | [**InventoryTrackingApiListMasterUnitsRequest**](InventoryTrackingApiListMasterUnitsRequest.md) |  | 

### Return type

[**[]InventoryTrackingApiListMasterUnitsItem**](InventoryTrackingApiListMasterUnitsItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## InventoryTrackingApiUpdateContainerRFID

> InventoryTrackingApiUpdateContainerRFIDResponse InventoryTrackingApiUpdateContainerRFID(ctx, serialNo).InventoryTrackingApiUpdateContainerRFIDRequest(inventoryTrackingApiUpdateContainerRFIDRequest).Execute()

Update Container RFID



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
	serialNo := "string" // string | The container serial no.
	inventoryTrackingApiUpdateContainerRFIDRequest := *openapiclient.NewInventoryTrackingApiUpdateContainerRFIDRequest() // InventoryTrackingApiUpdateContainerRFIDRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InventoryTrackingAPIAPI.InventoryTrackingApiUpdateContainerRFID(context.Background(), serialNo).InventoryTrackingApiUpdateContainerRFIDRequest(inventoryTrackingApiUpdateContainerRFIDRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InventoryTrackingAPIAPI.InventoryTrackingApiUpdateContainerRFID``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `InventoryTrackingApiUpdateContainerRFID`: InventoryTrackingApiUpdateContainerRFIDResponse
	fmt.Fprintf(os.Stdout, "Response from `InventoryTrackingAPIAPI.InventoryTrackingApiUpdateContainerRFID`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serialNo** | **string** | The container serial no. | 

### Other Parameters

Other parameters are passed through a pointer to a apiInventoryTrackingApiUpdateContainerRFIDRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **inventoryTrackingApiUpdateContainerRFIDRequest** | [**InventoryTrackingApiUpdateContainerRFIDRequest**](InventoryTrackingApiUpdateContainerRFIDRequest.md) |  | 

### Return type

[**InventoryTrackingApiUpdateContainerRFIDResponse**](InventoryTrackingApiUpdateContainerRFIDResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## InventoryTrackingApiUpdateMasterUnitRFID

> InventoryTrackingApiUpdateMasterUnitRFIDResponse InventoryTrackingApiUpdateMasterUnitRFID(ctx, id).InventoryTrackingApiUpdateMasterUnitRFIDRequest(inventoryTrackingApiUpdateMasterUnitRFIDRequest).Execute()

Update Master Unit RFID



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
	id := "00000000-0000-0000-0000-000000000000" // string | A unique identifier of the master unit.
	inventoryTrackingApiUpdateMasterUnitRFIDRequest := *openapiclient.NewInventoryTrackingApiUpdateMasterUnitRFIDRequest() // InventoryTrackingApiUpdateMasterUnitRFIDRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InventoryTrackingAPIAPI.InventoryTrackingApiUpdateMasterUnitRFID(context.Background(), id).InventoryTrackingApiUpdateMasterUnitRFIDRequest(inventoryTrackingApiUpdateMasterUnitRFIDRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InventoryTrackingAPIAPI.InventoryTrackingApiUpdateMasterUnitRFID``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `InventoryTrackingApiUpdateMasterUnitRFID`: InventoryTrackingApiUpdateMasterUnitRFIDResponse
	fmt.Fprintf(os.Stdout, "Response from `InventoryTrackingAPIAPI.InventoryTrackingApiUpdateMasterUnitRFID`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | A unique identifier of the master unit. | 

### Other Parameters

Other parameters are passed through a pointer to a apiInventoryTrackingApiUpdateMasterUnitRFIDRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **inventoryTrackingApiUpdateMasterUnitRFIDRequest** | [**InventoryTrackingApiUpdateMasterUnitRFIDRequest**](InventoryTrackingApiUpdateMasterUnitRFIDRequest.md) |  | 

### Return type

[**InventoryTrackingApiUpdateMasterUnitRFIDResponse**](InventoryTrackingApiUpdateMasterUnitRFIDResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

