# \ControlPlanTypesAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ControlPlanTypesApiListControlPlanTypes**](ControlPlanTypesAPIAPI.md#ControlPlanTypesApiListControlPlanTypes) | **Get** /quality/v1/control-plan-types | List Control Plan Types



## ControlPlanTypesApiListControlPlanTypes

> []ControlPlanTypesApiListControlPlanTypesItem ControlPlanTypesApiListControlPlanTypes(ctx).ControlPlanType(controlPlanType).Production(production).Process(process).Execute()

List Control Plan Types



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
	controlPlanType := []string{"string"} // []string | A list of Control Plan Types. (optional)
	production := false // bool | The production flag. (optional)
	process := false // bool | The process flag. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ControlPlanTypesAPIAPI.ControlPlanTypesApiListControlPlanTypes(context.Background()).ControlPlanType(controlPlanType).Production(production).Process(process).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ControlPlanTypesAPIAPI.ControlPlanTypesApiListControlPlanTypes``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ControlPlanTypesApiListControlPlanTypes`: []ControlPlanTypesApiListControlPlanTypesItem
	fmt.Fprintf(os.Stdout, "Response from `ControlPlanTypesAPIAPI.ControlPlanTypesApiListControlPlanTypes`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiControlPlanTypesApiListControlPlanTypesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **controlPlanType** | **[]string** | A list of Control Plan Types. | 
 **production** | **bool** | The production flag. | 
 **process** | **bool** | The process flag. | 

### Return type

[**[]ControlPlanTypesApiListControlPlanTypesItem**](ControlPlanTypesApiListControlPlanTypesItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

