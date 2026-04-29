# \BuildingsAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**BuildingsApiGetBuilding**](BuildingsAPIAPI.md#BuildingsApiGetBuilding) | **Get** /mdm/v1/buildings/{id} | Get Building
[**BuildingsApiListBuildings**](BuildingsAPIAPI.md#BuildingsApiListBuildings) | **Get** /mdm/v1/buildings | List Buildings



## BuildingsApiGetBuilding

> BuildingsApiGetBuildingResponse BuildingsApiGetBuilding(ctx, id).Execute()

Get Building



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
	id := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the building.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BuildingsAPIAPI.BuildingsApiGetBuilding(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BuildingsAPIAPI.BuildingsApiGetBuilding``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `BuildingsApiGetBuilding`: BuildingsApiGetBuildingResponse
	fmt.Fprintf(os.Stdout, "Response from `BuildingsAPIAPI.BuildingsApiGetBuilding`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | A unique identifier for the building. | 

### Other Parameters

Other parameters are passed through a pointer to a apiBuildingsApiGetBuildingRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**BuildingsApiGetBuildingResponse**](BuildingsApiGetBuildingResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## BuildingsApiListBuildings

> []BuildingsApiListBuildingsItem BuildingsApiListBuildings(ctx).Id(id).BuildingCode(buildingCode).BuildingType(buildingType).Name(name).Active(active).Execute()

List Buildings



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
	id := []string{"00000000-0000-0000-0000-000000000000"} // []string | A unique identifier for the building. (optional)
	buildingCode := "string" // string | The building code. (optional)
	buildingType := "string" // string | The building type. (optional)
	name := "string" // string | The name of the building. (optional)
	active := false // bool | The active status of the building. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BuildingsAPIAPI.BuildingsApiListBuildings(context.Background()).Id(id).BuildingCode(buildingCode).BuildingType(buildingType).Name(name).Active(active).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BuildingsAPIAPI.BuildingsApiListBuildings``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `BuildingsApiListBuildings`: []BuildingsApiListBuildingsItem
	fmt.Fprintf(os.Stdout, "Response from `BuildingsAPIAPI.BuildingsApiListBuildings`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiBuildingsApiListBuildingsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **[]string** | A unique identifier for the building. | 
 **buildingCode** | **string** | The building code. | 
 **buildingType** | **string** | The building type. | 
 **name** | **string** | The name of the building. | 
 **active** | **bool** | The active status of the building. | 

### Return type

[**[]BuildingsApiListBuildingsItem**](BuildingsApiListBuildingsItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

