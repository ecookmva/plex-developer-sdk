# \ProcessControlPlansAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ProcessControlPlansApiGetProcessControlRecipePlan**](ProcessControlPlansAPIAPI.md#ProcessControlPlansApiGetProcessControlRecipePlan) | **Get** /quality/v1/process-control-plans/{id} | Get Process Control Recipe Plan
[**ProcessControlPlansApiGetProcessControlRecipePlanLine**](ProcessControlPlansAPIAPI.md#ProcessControlPlansApiGetProcessControlRecipePlanLine) | **Get** /quality/v1/process-control-plans/{id}/control-plan-lines/{lineId} | Get Process Control Recipe Plan Line
[**ProcessControlPlansApiListProcessControlRecipePlanLines**](ProcessControlPlansAPIAPI.md#ProcessControlPlansApiListProcessControlRecipePlanLines) | **Get** /quality/v1/process-control-plans/{id}/control-plan-lines | List Process Control Recipe Plan Lines
[**ProcessControlPlansApiListProcessControlRecipePlans**](ProcessControlPlansAPIAPI.md#ProcessControlPlansApiListProcessControlRecipePlans) | **Get** /quality/v1/process-control-plans | List Process Control Recipe Plans



## ProcessControlPlansApiGetProcessControlRecipePlan

> ProcessControlPlansApiGetProcessControlRecipePlanResponse ProcessControlPlansApiGetProcessControlRecipePlan(ctx, id).Execute()

Get Process Control Recipe Plan



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
	resp, r, err := apiClient.ProcessControlPlansAPIAPI.ProcessControlPlansApiGetProcessControlRecipePlan(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProcessControlPlansAPIAPI.ProcessControlPlansApiGetProcessControlRecipePlan``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProcessControlPlansApiGetProcessControlRecipePlan`: ProcessControlPlansApiGetProcessControlRecipePlanResponse
	fmt.Fprintf(os.Stdout, "Response from `ProcessControlPlansAPIAPI.ProcessControlPlansApiGetProcessControlRecipePlan`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiProcessControlPlansApiGetProcessControlRecipePlanRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ProcessControlPlansApiGetProcessControlRecipePlanResponse**](ProcessControlPlansApiGetProcessControlRecipePlanResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProcessControlPlansApiGetProcessControlRecipePlanLine

> ProcessControlPlansApiGetProcessControlRecipePlanLineResponse ProcessControlPlansApiGetProcessControlRecipePlanLine(ctx, id, lineId).Execute()

Get Process Control Recipe Plan Line



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
	resp, r, err := apiClient.ProcessControlPlansAPIAPI.ProcessControlPlansApiGetProcessControlRecipePlanLine(context.Background(), id, lineId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProcessControlPlansAPIAPI.ProcessControlPlansApiGetProcessControlRecipePlanLine``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProcessControlPlansApiGetProcessControlRecipePlanLine`: ProcessControlPlansApiGetProcessControlRecipePlanLineResponse
	fmt.Fprintf(os.Stdout, "Response from `ProcessControlPlansAPIAPI.ProcessControlPlansApiGetProcessControlRecipePlanLine`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 
**lineId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiProcessControlPlansApiGetProcessControlRecipePlanLineRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**ProcessControlPlansApiGetProcessControlRecipePlanLineResponse**](ProcessControlPlansApiGetProcessControlRecipePlanLineResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProcessControlPlansApiListProcessControlRecipePlanLines

> []ProcessControlPlansApiListProcessControlRecipePlanLinesItem ProcessControlPlansApiListProcessControlRecipePlanLines(ctx, id).Ids(ids).InspectionMode(inspectionMode).ProcessControlRecipeId(processControlRecipeId).Execute()

List Process Control Recipe Plan Lines



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
	ids := []string{"00000000-0000-0000-0000-000000000000"} // []string | A list of IDs representing the Process Control Plan Line. (optional)
	inspectionMode := "string" // string | The inspection mode. (optional)
	processControlRecipeId := "00000000-0000-0000-0000-000000000000" // string | ID representing the process control recipe. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProcessControlPlansAPIAPI.ProcessControlPlansApiListProcessControlRecipePlanLines(context.Background(), id).Ids(ids).InspectionMode(inspectionMode).ProcessControlRecipeId(processControlRecipeId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProcessControlPlansAPIAPI.ProcessControlPlansApiListProcessControlRecipePlanLines``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProcessControlPlansApiListProcessControlRecipePlanLines`: []ProcessControlPlansApiListProcessControlRecipePlanLinesItem
	fmt.Fprintf(os.Stdout, "Response from `ProcessControlPlansAPIAPI.ProcessControlPlansApiListProcessControlRecipePlanLines`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiProcessControlPlansApiListProcessControlRecipePlanLinesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **ids** | **[]string** | A list of IDs representing the Process Control Plan Line. | 
 **inspectionMode** | **string** | The inspection mode. | 
 **processControlRecipeId** | **string** | ID representing the process control recipe. | 

### Return type

[**[]ProcessControlPlansApiListProcessControlRecipePlanLinesItem**](ProcessControlPlansApiListProcessControlRecipePlanLinesItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProcessControlPlansApiListProcessControlRecipePlans

> []ProcessControlPlansApiListProcessControlRecipePlansItem ProcessControlPlansApiListProcessControlRecipePlans(ctx).Ids(ids).ControlPlanNo(controlPlanNo).ControlPlanTypes(controlPlanTypes).Primary(primary).ProcessControlRecipeFamilyId(processControlRecipeFamilyId).Execute()

List Process Control Recipe Plans



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
	primary := false // bool | The primary flag. (optional)
	processControlRecipeFamilyId := "00000000-0000-0000-0000-000000000000" // string | The Process Control Recipe Family ID. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProcessControlPlansAPIAPI.ProcessControlPlansApiListProcessControlRecipePlans(context.Background()).Ids(ids).ControlPlanNo(controlPlanNo).ControlPlanTypes(controlPlanTypes).Primary(primary).ProcessControlRecipeFamilyId(processControlRecipeFamilyId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProcessControlPlansAPIAPI.ProcessControlPlansApiListProcessControlRecipePlans``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProcessControlPlansApiListProcessControlRecipePlans`: []ProcessControlPlansApiListProcessControlRecipePlansItem
	fmt.Fprintf(os.Stdout, "Response from `ProcessControlPlansAPIAPI.ProcessControlPlansApiListProcessControlRecipePlans`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiProcessControlPlansApiListProcessControlRecipePlansRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ids** | **[]string** | A list of IDs representing the Control Plan. | 
 **controlPlanNo** | **float64** | The Control Plan No. | 
 **controlPlanTypes** | **[]string** | A list of Control Plan types. | 
 **primary** | **bool** | The primary flag. | 
 **processControlRecipeFamilyId** | **string** | The Process Control Recipe Family ID. | 

### Return type

[**[]ProcessControlPlansApiListProcessControlRecipePlansItem**](ProcessControlPlansApiListProcessControlRecipePlansItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

