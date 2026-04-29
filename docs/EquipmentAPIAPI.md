# \EquipmentAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**EquipmentApiCreateEquipmentAttribute**](EquipmentAPIAPI.md#EquipmentApiCreateEquipmentAttribute) | **Post** /maintenance/v1/equipment-attributes | Create Equipment Attribute
[**EquipmentApiGetEquipment**](EquipmentAPIAPI.md#EquipmentApiGetEquipment) | **Get** /maintenance/v1/equipment/{id} | Get Equipment
[**EquipmentApiGetEquipmentAttributes**](EquipmentAPIAPI.md#EquipmentApiGetEquipmentAttributes) | **Get** /maintenance/v1/equipment-attributes/{id} | Get Equipment Attributes
[**EquipmentApiGetEquipmentTypes**](EquipmentAPIAPI.md#EquipmentApiGetEquipmentTypes) | **Get** /maintenance/v1/equipment-types/{id} | Get Equipment Types
[**EquipmentApiListEquipment**](EquipmentAPIAPI.md#EquipmentApiListEquipment) | **Get** /maintenance/v1/equipment | List Equipment
[**EquipmentApiListEquipmentAttributes**](EquipmentAPIAPI.md#EquipmentApiListEquipmentAttributes) | **Get** /maintenance/v1/equipment-attributes | List Equipment Attributes
[**EquipmentApiListEquipmentTypes**](EquipmentAPIAPI.md#EquipmentApiListEquipmentTypes) | **Get** /maintenance/v1/equipment-types | List Equipment Types
[**EquipmentApiUpdateEquipmentAttribute**](EquipmentAPIAPI.md#EquipmentApiUpdateEquipmentAttribute) | **Put** /maintenance/v1/equipment-attributes/{id} | Update Equipment Attribute



## EquipmentApiCreateEquipmentAttribute

> EquipmentApiCreateEquipmentAttribute201Response EquipmentApiCreateEquipmentAttribute(ctx).EquipmentApiCreateEquipmentAttributeRequest(equipmentApiCreateEquipmentAttributeRequest).Execute()

Create Equipment Attribute



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
	equipmentApiCreateEquipmentAttributeRequest := *openapiclient.NewEquipmentApiCreateEquipmentAttributeRequest() // EquipmentApiCreateEquipmentAttributeRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EquipmentAPIAPI.EquipmentApiCreateEquipmentAttribute(context.Background()).EquipmentApiCreateEquipmentAttributeRequest(equipmentApiCreateEquipmentAttributeRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EquipmentAPIAPI.EquipmentApiCreateEquipmentAttribute``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EquipmentApiCreateEquipmentAttribute`: EquipmentApiCreateEquipmentAttribute201Response
	fmt.Fprintf(os.Stdout, "Response from `EquipmentAPIAPI.EquipmentApiCreateEquipmentAttribute`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiEquipmentApiCreateEquipmentAttributeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **equipmentApiCreateEquipmentAttributeRequest** | [**EquipmentApiCreateEquipmentAttributeRequest**](EquipmentApiCreateEquipmentAttributeRequest.md) |  | 

### Return type

[**EquipmentApiCreateEquipmentAttribute201Response**](EquipmentApiCreateEquipmentAttribute201Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EquipmentApiGetEquipment

> EquipmentApiGetEquipmentResponse EquipmentApiGetEquipment(ctx, id).Execute()

Get Equipment



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
	resp, r, err := apiClient.EquipmentAPIAPI.EquipmentApiGetEquipment(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EquipmentAPIAPI.EquipmentApiGetEquipment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EquipmentApiGetEquipment`: EquipmentApiGetEquipmentResponse
	fmt.Fprintf(os.Stdout, "Response from `EquipmentAPIAPI.EquipmentApiGetEquipment`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiEquipmentApiGetEquipmentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**EquipmentApiGetEquipmentResponse**](EquipmentApiGetEquipmentResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EquipmentApiGetEquipmentAttributes

> EquipmentApiGetEquipmentAttributesResponse EquipmentApiGetEquipmentAttributes(ctx, id).Execute()

Get Equipment Attributes



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
	resp, r, err := apiClient.EquipmentAPIAPI.EquipmentApiGetEquipmentAttributes(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EquipmentAPIAPI.EquipmentApiGetEquipmentAttributes``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EquipmentApiGetEquipmentAttributes`: EquipmentApiGetEquipmentAttributesResponse
	fmt.Fprintf(os.Stdout, "Response from `EquipmentAPIAPI.EquipmentApiGetEquipmentAttributes`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiEquipmentApiGetEquipmentAttributesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**EquipmentApiGetEquipmentAttributesResponse**](EquipmentApiGetEquipmentAttributesResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EquipmentApiGetEquipmentTypes

> EquipmentApiGetEquipmentTypesResponse EquipmentApiGetEquipmentTypes(ctx, id).Execute()

Get Equipment Types



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
	resp, r, err := apiClient.EquipmentAPIAPI.EquipmentApiGetEquipmentTypes(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EquipmentAPIAPI.EquipmentApiGetEquipmentTypes``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EquipmentApiGetEquipmentTypes`: EquipmentApiGetEquipmentTypesResponse
	fmt.Fprintf(os.Stdout, "Response from `EquipmentAPIAPI.EquipmentApiGetEquipmentTypes`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiEquipmentApiGetEquipmentTypesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**EquipmentApiGetEquipmentTypesResponse**](EquipmentApiGetEquipmentTypesResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EquipmentApiListEquipment

> []EquipmentApiListEquipmentItem EquipmentApiListEquipment(ctx).EquipmentId(equipmentId).EquipmentTypeId(equipmentTypeId).BuildingId(buildingId).LocationId(locationId).WorkcenterId(workcenterId).PartId(partId).PartType(partType).Status(status).SerialNo(serialNo).Active(active).Execute()

List Equipment



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
	equipmentId := "string" // string | The Equipment ID. (optional)
	equipmentTypeId := "00000000-0000-0000-0000-000000000000" // string | The ID of the Equipment Type. (optional)
	buildingId := "00000000-0000-0000-0000-000000000000" // string | The ID of the Equipment Building. (optional)
	locationId := "00000000-0000-0000-0000-000000000000" // string | The ID of the Equipment Location. (optional)
	workcenterId := "00000000-0000-0000-0000-000000000000" // string | The ID of the Equipment Workcenter. (optional)
	partId := "00000000-0000-0000-0000-000000000000" // string | The ID of the associated Part. (optional)
	partType := "string" // string | The associated Part Type. (optional)
	status := "string" // string | The associated Equipment Status. (optional)
	serialNo := "string" // string | The Equipment Serial Number. (optional)
	active := false // bool | The Equipment Active flag. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EquipmentAPIAPI.EquipmentApiListEquipment(context.Background()).EquipmentId(equipmentId).EquipmentTypeId(equipmentTypeId).BuildingId(buildingId).LocationId(locationId).WorkcenterId(workcenterId).PartId(partId).PartType(partType).Status(status).SerialNo(serialNo).Active(active).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EquipmentAPIAPI.EquipmentApiListEquipment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EquipmentApiListEquipment`: []EquipmentApiListEquipmentItem
	fmt.Fprintf(os.Stdout, "Response from `EquipmentAPIAPI.EquipmentApiListEquipment`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiEquipmentApiListEquipmentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **equipmentId** | **string** | The Equipment ID. | 
 **equipmentTypeId** | **string** | The ID of the Equipment Type. | 
 **buildingId** | **string** | The ID of the Equipment Building. | 
 **locationId** | **string** | The ID of the Equipment Location. | 
 **workcenterId** | **string** | The ID of the Equipment Workcenter. | 
 **partId** | **string** | The ID of the associated Part. | 
 **partType** | **string** | The associated Part Type. | 
 **status** | **string** | The associated Equipment Status. | 
 **serialNo** | **string** | The Equipment Serial Number. | 
 **active** | **bool** | The Equipment Active flag. | 

### Return type

[**[]EquipmentApiListEquipmentItem**](EquipmentApiListEquipmentItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EquipmentApiListEquipmentAttributes

> []EquipmentApiListEquipmentAttributesItem EquipmentApiListEquipmentAttributes(ctx).AttributeName(attributeName).Unit(unit).TypeAttribute(typeAttribute).GroupAttribute(groupAttribute).CategoryAttribute(categoryAttribute).UseValues(useValues).SmartAttribute(smartAttribute).Active(active).Execute()

List Equipment Attributes



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
	attributeName := "string" // string | The name of an Equipment Attribute. (optional)
	unit := "string" // string | The unit associated with the Equipment Attribute. (optional)
	typeAttribute := false // bool | If true, only the list of Type Equipment Attributes will be returned. (optional)
	groupAttribute := false // bool | If true, only the list of Group Equipment Attributes will be returned. (optional)
	categoryAttribute := false // bool | If true, only the list of Category Equipment Attributes will be returned. (optional)
	useValues := false // bool | If true, only the list of Equipment Attributes where values are being use will be returned. (optional)
	smartAttribute := false // bool | If true, only the list of Smart Equipment Attributes will be returned. (optional)
	active := false // bool | If true, only the list of Active Equipment Attributes will be returned. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EquipmentAPIAPI.EquipmentApiListEquipmentAttributes(context.Background()).AttributeName(attributeName).Unit(unit).TypeAttribute(typeAttribute).GroupAttribute(groupAttribute).CategoryAttribute(categoryAttribute).UseValues(useValues).SmartAttribute(smartAttribute).Active(active).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EquipmentAPIAPI.EquipmentApiListEquipmentAttributes``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EquipmentApiListEquipmentAttributes`: []EquipmentApiListEquipmentAttributesItem
	fmt.Fprintf(os.Stdout, "Response from `EquipmentAPIAPI.EquipmentApiListEquipmentAttributes`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiEquipmentApiListEquipmentAttributesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **attributeName** | **string** | The name of an Equipment Attribute. | 
 **unit** | **string** | The unit associated with the Equipment Attribute. | 
 **typeAttribute** | **bool** | If true, only the list of Type Equipment Attributes will be returned. | 
 **groupAttribute** | **bool** | If true, only the list of Group Equipment Attributes will be returned. | 
 **categoryAttribute** | **bool** | If true, only the list of Category Equipment Attributes will be returned. | 
 **useValues** | **bool** | If true, only the list of Equipment Attributes where values are being use will be returned. | 
 **smartAttribute** | **bool** | If true, only the list of Smart Equipment Attributes will be returned. | 
 **active** | **bool** | If true, only the list of Active Equipment Attributes will be returned. | 

### Return type

[**[]EquipmentApiListEquipmentAttributesItem**](EquipmentApiListEquipmentAttributesItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EquipmentApiListEquipmentTypes

> []EquipmentApiListEquipmentTypesItem EquipmentApiListEquipmentTypes(ctx).EquipmentType(equipmentType).Execute()

List Equipment Types



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
	equipmentType := "string" // string | The name of an Equipment Type. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EquipmentAPIAPI.EquipmentApiListEquipmentTypes(context.Background()).EquipmentType(equipmentType).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EquipmentAPIAPI.EquipmentApiListEquipmentTypes``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EquipmentApiListEquipmentTypes`: []EquipmentApiListEquipmentTypesItem
	fmt.Fprintf(os.Stdout, "Response from `EquipmentAPIAPI.EquipmentApiListEquipmentTypes`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiEquipmentApiListEquipmentTypesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **equipmentType** | **string** | The name of an Equipment Type. | 

### Return type

[**[]EquipmentApiListEquipmentTypesItem**](EquipmentApiListEquipmentTypesItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EquipmentApiUpdateEquipmentAttribute

> EquipmentApiUpdateEquipmentAttributeResponse EquipmentApiUpdateEquipmentAttribute(ctx, id).EquipmentApiUpdateEquipmentAttributeRequest(equipmentApiUpdateEquipmentAttributeRequest).Execute()

Update Equipment Attribute



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
	equipmentApiUpdateEquipmentAttributeRequest := *openapiclient.NewEquipmentApiUpdateEquipmentAttributeRequest() // EquipmentApiUpdateEquipmentAttributeRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EquipmentAPIAPI.EquipmentApiUpdateEquipmentAttribute(context.Background(), id).EquipmentApiUpdateEquipmentAttributeRequest(equipmentApiUpdateEquipmentAttributeRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EquipmentAPIAPI.EquipmentApiUpdateEquipmentAttribute``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EquipmentApiUpdateEquipmentAttribute`: EquipmentApiUpdateEquipmentAttributeResponse
	fmt.Fprintf(os.Stdout, "Response from `EquipmentAPIAPI.EquipmentApiUpdateEquipmentAttribute`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiEquipmentApiUpdateEquipmentAttributeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **equipmentApiUpdateEquipmentAttributeRequest** | [**EquipmentApiUpdateEquipmentAttributeRequest**](EquipmentApiUpdateEquipmentAttributeRequest.md) |  | 

### Return type

[**EquipmentApiUpdateEquipmentAttributeResponse**](EquipmentApiUpdateEquipmentAttributeResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

