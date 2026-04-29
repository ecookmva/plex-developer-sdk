# \ProcessControlRecipeFamilyTypesAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ProcessControlRecipeFamilyTypesApiListProcessControlRecipeFamilyTypes**](ProcessControlRecipeFamilyTypesAPIAPI.md#ProcessControlRecipeFamilyTypesApiListProcessControlRecipeFamilyTypes) | **Get** /quality/v1/process-control-recipe-family-types | List Process Control Recipe Family Types



## ProcessControlRecipeFamilyTypesApiListProcessControlRecipeFamilyTypes

> []ProcessControlRecipeFamilyTypesApiListProcessControlRecipeFamilyTypesItem ProcessControlRecipeFamilyTypesApiListProcessControlRecipeFamilyTypes(ctx).Name(name).WorkcenterOnly(workcenterOnly).Execute()

List Process Control Recipe Family Types



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
	name := []string{"string"} // []string | The list of process control recipe family type names. (optional)
	workcenterOnly := false // bool | The designation to signify the type is workcenter only. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProcessControlRecipeFamilyTypesAPIAPI.ProcessControlRecipeFamilyTypesApiListProcessControlRecipeFamilyTypes(context.Background()).Name(name).WorkcenterOnly(workcenterOnly).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProcessControlRecipeFamilyTypesAPIAPI.ProcessControlRecipeFamilyTypesApiListProcessControlRecipeFamilyTypes``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProcessControlRecipeFamilyTypesApiListProcessControlRecipeFamilyTypes`: []ProcessControlRecipeFamilyTypesApiListProcessControlRecipeFamilyTypesItem
	fmt.Fprintf(os.Stdout, "Response from `ProcessControlRecipeFamilyTypesAPIAPI.ProcessControlRecipeFamilyTypesApiListProcessControlRecipeFamilyTypes`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiProcessControlRecipeFamilyTypesApiListProcessControlRecipeFamilyTypesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **name** | **[]string** | The list of process control recipe family type names. | 
 **workcenterOnly** | **bool** | The designation to signify the type is workcenter only. | 

### Return type

[**[]ProcessControlRecipeFamilyTypesApiListProcessControlRecipeFamilyTypesItem**](ProcessControlRecipeFamilyTypesApiListProcessControlRecipeFamilyTypesItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

