# \OperatingParametersAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**OperatingParametersApiGetOperatingParameterByID**](OperatingParametersAPIAPI.md#OperatingParametersApiGetOperatingParameterByID) | **Get** /engineering/v1/operating-parameters/{id} | Get Operating Parameter By ID
[**OperatingParametersApiListOperatingParameterGroups**](OperatingParametersAPIAPI.md#OperatingParametersApiListOperatingParameterGroups) | **Get** /engineering/v1/operating-parameter-groups | List Operating Parameter Groups
[**OperatingParametersApiListOperatingParameters**](OperatingParametersAPIAPI.md#OperatingParametersApiListOperatingParameters) | **Get** /engineering/v1/operating-parameters | List Operating Parameters



## OperatingParametersApiGetOperatingParameterByID

> OperatingParametersApiGetOperatingParameterByIDResponse OperatingParametersApiGetOperatingParameterByID(ctx, id).Execute()

Get Operating Parameter By ID



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
	id := "00000000-0000-0000-0000-000000000000" // string | The Operating Parameter ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatingParametersAPIAPI.OperatingParametersApiGetOperatingParameterByID(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatingParametersAPIAPI.OperatingParametersApiGetOperatingParameterByID``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatingParametersApiGetOperatingParameterByID`: OperatingParametersApiGetOperatingParameterByIDResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatingParametersAPIAPI.OperatingParametersApiGetOperatingParameterByID`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The Operating Parameter ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperatingParametersApiGetOperatingParameterByIDRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**OperatingParametersApiGetOperatingParameterByIDResponse**](OperatingParametersApiGetOperatingParameterByIDResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatingParametersApiListOperatingParameterGroups

> []OperatingParametersApiListOperatingParameterGroupsItem OperatingParametersApiListOperatingParameterGroups(ctx).PartId(partId).PartOpId(partOpId).EquipmentTypeId(equipmentTypeId).EquipmentId(equipmentId).Execute()

List Operating Parameter Groups



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
	partId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier representing the Part to filter by. (optional)
	partOpId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier representing the Part Operation to filter by. (optional)
	equipmentTypeId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier representing the EquipmentType to filter by. (optional)
	equipmentId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier representing the Equipment to filter by. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatingParametersAPIAPI.OperatingParametersApiListOperatingParameterGroups(context.Background()).PartId(partId).PartOpId(partOpId).EquipmentTypeId(equipmentTypeId).EquipmentId(equipmentId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatingParametersAPIAPI.OperatingParametersApiListOperatingParameterGroups``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatingParametersApiListOperatingParameterGroups`: []OperatingParametersApiListOperatingParameterGroupsItem
	fmt.Fprintf(os.Stdout, "Response from `OperatingParametersAPIAPI.OperatingParametersApiListOperatingParameterGroups`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOperatingParametersApiListOperatingParameterGroupsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **partId** | **string** | A unique identifier representing the Part to filter by. | 
 **partOpId** | **string** | A unique identifier representing the Part Operation to filter by. | 
 **equipmentTypeId** | **string** | A unique identifier representing the EquipmentType to filter by. | 
 **equipmentId** | **string** | A unique identifier representing the Equipment to filter by. | 

### Return type

[**[]OperatingParametersApiListOperatingParameterGroupsItem**](OperatingParametersApiListOperatingParameterGroupsItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatingParametersApiListOperatingParameters

> []OperatingParametersApiListOperatingParametersItem OperatingParametersApiListOperatingParameters(ctx).OperatingParameterCode(operatingParameterCode).Active(active).UnitId(unitId).Execute()

List Operating Parameters



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
	operatingParameterCode := "string" // string | The code of the Operating Parameter to filter by. (optional)
	active := false // bool | A filter to return only active or inactive Operating Parameters. If not specified, defaults to true (active only). (optional)
	unitId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier representing the Unit to filter by. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatingParametersAPIAPI.OperatingParametersApiListOperatingParameters(context.Background()).OperatingParameterCode(operatingParameterCode).Active(active).UnitId(unitId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatingParametersAPIAPI.OperatingParametersApiListOperatingParameters``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatingParametersApiListOperatingParameters`: []OperatingParametersApiListOperatingParametersItem
	fmt.Fprintf(os.Stdout, "Response from `OperatingParametersAPIAPI.OperatingParametersApiListOperatingParameters`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOperatingParametersApiListOperatingParametersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **operatingParameterCode** | **string** | The code of the Operating Parameter to filter by. | 
 **active** | **bool** | A filter to return only active or inactive Operating Parameters. If not specified, defaults to true (active only). | 
 **unitId** | **string** | A unique identifier representing the Unit to filter by. | 

### Return type

[**[]OperatingParametersApiListOperatingParametersItem**](OperatingParametersApiListOperatingParametersItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

