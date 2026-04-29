# \ControlPlansAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ControlPlansApiGetControlPlan**](ControlPlansAPIAPI.md#ControlPlansApiGetControlPlan) | **Get** /quality/v1/control-plans/{id} | Get Control Plan
[**ControlPlansApiGetControlPlanLine**](ControlPlansAPIAPI.md#ControlPlansApiGetControlPlanLine) | **Get** /quality/v1/control-plans/{id}/control-plan-lines/{lineId} | Get Control Plan Line
[**ControlPlansApiListControlPlanLines**](ControlPlansAPIAPI.md#ControlPlansApiListControlPlanLines) | **Get** /quality/v1/control-plans/{id}/control-plan-lines | List Control Plan Lines
[**ControlPlansApiListControlPlans**](ControlPlansAPIAPI.md#ControlPlansApiListControlPlans) | **Get** /quality/v1/control-plans | List Control Plans



## ControlPlansApiGetControlPlan

> ControlPlansApiGetControlPlanResponse ControlPlansApiGetControlPlan(ctx, id).Execute()

Get Control Plan



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
	resp, r, err := apiClient.ControlPlansAPIAPI.ControlPlansApiGetControlPlan(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ControlPlansAPIAPI.ControlPlansApiGetControlPlan``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ControlPlansApiGetControlPlan`: ControlPlansApiGetControlPlanResponse
	fmt.Fprintf(os.Stdout, "Response from `ControlPlansAPIAPI.ControlPlansApiGetControlPlan`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiControlPlansApiGetControlPlanRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ControlPlansApiGetControlPlanResponse**](ControlPlansApiGetControlPlanResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ControlPlansApiGetControlPlanLine

> ControlPlansApiGetControlPlanLineResponse ControlPlansApiGetControlPlanLine(ctx, id, lineId).Execute()

Get Control Plan Line



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
	lineId := "00000000-0000-0000-0000-000000000000" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ControlPlansAPIAPI.ControlPlansApiGetControlPlanLine(context.Background(), id, lineId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ControlPlansAPIAPI.ControlPlansApiGetControlPlanLine``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ControlPlansApiGetControlPlanLine`: ControlPlansApiGetControlPlanLineResponse
	fmt.Fprintf(os.Stdout, "Response from `ControlPlansAPIAPI.ControlPlansApiGetControlPlanLine`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 
**lineId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiControlPlansApiGetControlPlanLineRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**ControlPlansApiGetControlPlanLineResponse**](ControlPlansApiGetControlPlanLineResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ControlPlansApiListControlPlanLines

> []ControlPlansApiListControlPlanLinesItem ControlPlansApiListControlPlanLines(ctx, id).Ids(ids).JobOpId(jobOpId).SpecificToWorkcenterId(specificToWorkcenterId).PartOperationId(partOperationId).InspectionMode(inspectionMode).Execute()

List Control Plan Lines



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
	ids := []string{"00000000-0000-0000-0000-000000000000"} // []string | A list of IDs representing the Control Plan Line. (optional)
	jobOpId := "00000000-0000-0000-0000-000000000000" // string | ID representing the job op on the deviation. (optional)
	specificToWorkcenterId := "00000000-0000-0000-0000-000000000000" // string | ID representing the workcenter. (optional)
	partOperationId := "00000000-0000-0000-0000-000000000000" // string | ID representing the part operation. (optional)
	inspectionMode := "string" // string | The inspection mode. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ControlPlansAPIAPI.ControlPlansApiListControlPlanLines(context.Background(), id).Ids(ids).JobOpId(jobOpId).SpecificToWorkcenterId(specificToWorkcenterId).PartOperationId(partOperationId).InspectionMode(inspectionMode).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ControlPlansAPIAPI.ControlPlansApiListControlPlanLines``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ControlPlansApiListControlPlanLines`: []ControlPlansApiListControlPlanLinesItem
	fmt.Fprintf(os.Stdout, "Response from `ControlPlansAPIAPI.ControlPlansApiListControlPlanLines`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiControlPlansApiListControlPlanLinesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **ids** | **[]string** | A list of IDs representing the Control Plan Line. | 
 **jobOpId** | **string** | ID representing the job op on the deviation. | 
 **specificToWorkcenterId** | **string** | ID representing the workcenter. | 
 **partOperationId** | **string** | ID representing the part operation. | 
 **inspectionMode** | **string** | The inspection mode. | 

### Return type

[**[]ControlPlansApiListControlPlanLinesItem**](ControlPlansApiListControlPlanLinesItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ControlPlansApiListControlPlans

> []ControlPlansApiListControlPlansItem ControlPlansApiListControlPlans(ctx).Ids(ids).ControlPlanNo(controlPlanNo).ControlPlanTypes(controlPlanTypes).PartId(partId).Primary(primary).Execute()

List Control Plans



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
	ids := []string{"00000000-0000-0000-0000-000000000000"} // []string | A list of IDs representing the Control Plan. (optional)
	controlPlanNo := float64(0.1) // float64 | The Control Plan No. (optional)
	controlPlanTypes := []string{"string"} // []string | A list of Control Plan types. (optional)
	partId := "00000000-0000-0000-0000-000000000000" // string | ID representing the Control Plan part number. (optional)
	primary := false // bool | The primary flag. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ControlPlansAPIAPI.ControlPlansApiListControlPlans(context.Background()).Ids(ids).ControlPlanNo(controlPlanNo).ControlPlanTypes(controlPlanTypes).PartId(partId).Primary(primary).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ControlPlansAPIAPI.ControlPlansApiListControlPlans``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ControlPlansApiListControlPlans`: []ControlPlansApiListControlPlansItem
	fmt.Fprintf(os.Stdout, "Response from `ControlPlansAPIAPI.ControlPlansApiListControlPlans`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiControlPlansApiListControlPlansRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ids** | **[]string** | A list of IDs representing the Control Plan. | 
 **controlPlanNo** | **float64** | The Control Plan No. | 
 **controlPlanTypes** | **[]string** | A list of Control Plan types. | 
 **partId** | **string** | ID representing the Control Plan part number. | 
 **primary** | **bool** | The primary flag. | 

### Return type

[**[]ControlPlansApiListControlPlansItem**](ControlPlansApiListControlPlansItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

