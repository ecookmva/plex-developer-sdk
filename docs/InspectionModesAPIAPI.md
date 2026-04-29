# \InspectionModesAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**InspectionModesApiListInspectionModes**](InspectionModesAPIAPI.md#InspectionModesApiListInspectionModes) | **Get** /quality/v1/inspection-modes | List Inspection Modes



## InspectionModesApiListInspectionModes

> []InspectionModesApiListInspectionModesItem InspectionModesApiListInspectionModes(ctx).Description(description).PlcIntegrated(plcIntegrated).Manufacturing(manufacturing).ProcessCheck(processCheck).OutOfSpecNotify(outOfSpecNotify).GageRequired(gageRequired).ExceptionOverrideRequired(exceptionOverrideRequired).Execute()

List Inspection Modes



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
	description := []string{"string"} // []string | The list of inspection mode descriptions. (optional)
	plcIntegrated := false // bool | The PLC integrated flag. (optional)
	manufacturing := false // bool | The Manufacturing flag. (optional)
	processCheck := false // bool | The Process Check flag. (optional)
	outOfSpecNotify := false // bool | The Out of Spec Notify flag. (optional)
	gageRequired := false // bool | The Gage Required flag. (optional)
	exceptionOverrideRequired := false // bool | The Exception Override Required flag. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InspectionModesAPIAPI.InspectionModesApiListInspectionModes(context.Background()).Description(description).PlcIntegrated(plcIntegrated).Manufacturing(manufacturing).ProcessCheck(processCheck).OutOfSpecNotify(outOfSpecNotify).GageRequired(gageRequired).ExceptionOverrideRequired(exceptionOverrideRequired).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InspectionModesAPIAPI.InspectionModesApiListInspectionModes``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `InspectionModesApiListInspectionModes`: []InspectionModesApiListInspectionModesItem
	fmt.Fprintf(os.Stdout, "Response from `InspectionModesAPIAPI.InspectionModesApiListInspectionModes`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiInspectionModesApiListInspectionModesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **description** | **[]string** | The list of inspection mode descriptions. | 
 **plcIntegrated** | **bool** | The PLC integrated flag. | 
 **manufacturing** | **bool** | The Manufacturing flag. | 
 **processCheck** | **bool** | The Process Check flag. | 
 **outOfSpecNotify** | **bool** | The Out of Spec Notify flag. | 
 **gageRequired** | **bool** | The Gage Required flag. | 
 **exceptionOverrideRequired** | **bool** | The Exception Override Required flag. | 

### Return type

[**[]InspectionModesApiListInspectionModesItem**](InspectionModesApiListInspectionModesItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

