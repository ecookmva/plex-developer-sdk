# \ShippingInventoryAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ShippingInventoryApiGetContainerShippingDetails**](ShippingInventoryAPIAPI.md#ShippingInventoryApiGetContainerShippingDetails) | **Get** /shipping/v1-beta1/inventory/containers/{serialNo}/shipping-details | Get Container Shipping Details
[**ShippingInventoryApiGetMasterUnit**](ShippingInventoryAPIAPI.md#ShippingInventoryApiGetMasterUnit) | **Get** /shipping/v1-beta1/inventory/master-units/{masterUnitId} | Get Master Unit
[**ShippingInventoryApiGetPartShippingDetails**](ShippingInventoryAPIAPI.md#ShippingInventoryApiGetPartShippingDetails) | **Get** /shipping/v1-beta1/inventory/parts/{partId}/shipping-details | Get Part Shipping Details
[**ShippingInventoryApiListShippableContainers**](ShippingInventoryAPIAPI.md#ShippingInventoryApiListShippableContainers) | **Get** /shipping/v1-beta1/inventory/customer-shippers/{shipperId}/shippable-containers | List Shippable Containers



## ShippingInventoryApiGetContainerShippingDetails

> ShippingInventoryApiGetContainerShippingDetailsResponse ShippingInventoryApiGetContainerShippingDetails(ctx, serialNo).Execute()

Get Container Shipping Details



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
	serialNo := "string" // string | The serial number of the container.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ShippingInventoryAPIAPI.ShippingInventoryApiGetContainerShippingDetails(context.Background(), serialNo).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShippingInventoryAPIAPI.ShippingInventoryApiGetContainerShippingDetails``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ShippingInventoryApiGetContainerShippingDetails`: ShippingInventoryApiGetContainerShippingDetailsResponse
	fmt.Fprintf(os.Stdout, "Response from `ShippingInventoryAPIAPI.ShippingInventoryApiGetContainerShippingDetails`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serialNo** | **string** | The serial number of the container. | 

### Other Parameters

Other parameters are passed through a pointer to a apiShippingInventoryApiGetContainerShippingDetailsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ShippingInventoryApiGetContainerShippingDetailsResponse**](ShippingInventoryApiGetContainerShippingDetailsResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ShippingInventoryApiGetMasterUnit

> ShippingInventoryApiGetMasterUnitResponse ShippingInventoryApiGetMasterUnit(ctx, masterUnitId).Execute()

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
	masterUnitId := "00000000-0000-0000-0000-000000000000" // string | The unique master unit identifier.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ShippingInventoryAPIAPI.ShippingInventoryApiGetMasterUnit(context.Background(), masterUnitId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShippingInventoryAPIAPI.ShippingInventoryApiGetMasterUnit``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ShippingInventoryApiGetMasterUnit`: ShippingInventoryApiGetMasterUnitResponse
	fmt.Fprintf(os.Stdout, "Response from `ShippingInventoryAPIAPI.ShippingInventoryApiGetMasterUnit`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**masterUnitId** | **string** | The unique master unit identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiShippingInventoryApiGetMasterUnitRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ShippingInventoryApiGetMasterUnitResponse**](ShippingInventoryApiGetMasterUnitResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ShippingInventoryApiGetPartShippingDetails

> ShippingInventoryApiGetPartShippingDetailsResponse ShippingInventoryApiGetPartShippingDetails(ctx, partId).Execute()

Get Part Shipping Details



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
	partId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the part.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ShippingInventoryAPIAPI.ShippingInventoryApiGetPartShippingDetails(context.Background(), partId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShippingInventoryAPIAPI.ShippingInventoryApiGetPartShippingDetails``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ShippingInventoryApiGetPartShippingDetails`: ShippingInventoryApiGetPartShippingDetailsResponse
	fmt.Fprintf(os.Stdout, "Response from `ShippingInventoryAPIAPI.ShippingInventoryApiGetPartShippingDetails`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**partId** | **string** | A unique identifier for the part. | 

### Other Parameters

Other parameters are passed through a pointer to a apiShippingInventoryApiGetPartShippingDetailsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ShippingInventoryApiGetPartShippingDetailsResponse**](ShippingInventoryApiGetPartShippingDetailsResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ShippingInventoryApiListShippableContainers

> []ShippingInventoryApiListShippableContainersItem ShippingInventoryApiListShippableContainers(ctx, shipperId).BuildingId(buildingId).Location(location).LocationGroup(locationGroup).PartId(partId).Execute()

List Shippable Containers



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
	shipperId := "00000000-0000-0000-0000-000000000000" // string | The shipper ID associated with the container.
	buildingId := "00000000-0000-0000-0000-000000000000" // string | The ID of the building associated with the shippable container. (optional)
	location := "string" // string | The location associated with the shippable container. (optional)
	locationGroup := "string" // string | The location group associated with the shippable container. (optional)
	partId := "00000000-0000-0000-0000-000000000000" // string | The ID of the part associated with the shippable container. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ShippingInventoryAPIAPI.ShippingInventoryApiListShippableContainers(context.Background(), shipperId).BuildingId(buildingId).Location(location).LocationGroup(locationGroup).PartId(partId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShippingInventoryAPIAPI.ShippingInventoryApiListShippableContainers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ShippingInventoryApiListShippableContainers`: []ShippingInventoryApiListShippableContainersItem
	fmt.Fprintf(os.Stdout, "Response from `ShippingInventoryAPIAPI.ShippingInventoryApiListShippableContainers`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**shipperId** | **string** | The shipper ID associated with the container. | 

### Other Parameters

Other parameters are passed through a pointer to a apiShippingInventoryApiListShippableContainersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **buildingId** | **string** | The ID of the building associated with the shippable container. | 
 **location** | **string** | The location associated with the shippable container. | 
 **locationGroup** | **string** | The location group associated with the shippable container. | 
 **partId** | **string** | The ID of the part associated with the shippable container. | 

### Return type

[**[]ShippingInventoryApiListShippableContainersItem**](ShippingInventoryApiListShippableContainersItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

