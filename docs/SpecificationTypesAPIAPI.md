# \SpecificationTypesAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SpecificationTypesApiListSpecificationTypes**](SpecificationTypesAPIAPI.md#SpecificationTypesApiListSpecificationTypes) | **Get** /quality/v1/specification-types | List Specification Types



## SpecificationTypesApiListSpecificationTypes

> []SpecificationTypesApiListSpecificationTypesItem SpecificationTypesApiListSpecificationTypes(ctx).SpecificationType(specificationType).ChecksheetType(checksheetType).Process(process).Standard(standard).FoundationProcess(foundationProcess).FoundationProduct(foundationProduct).Execute()

List Specification Types



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
	specificationType := []string{"string"} // []string | The specification type. (optional)
	checksheetType := "string" // string | The checksheet type. (optional)
	process := false // bool | The process flag. (optional)
	standard := false // bool | The standard flag. (optional)
	foundationProcess := false // bool | The foundation process flag. (optional)
	foundationProduct := false // bool | The foundation product flag. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SpecificationTypesAPIAPI.SpecificationTypesApiListSpecificationTypes(context.Background()).SpecificationType(specificationType).ChecksheetType(checksheetType).Process(process).Standard(standard).FoundationProcess(foundationProcess).FoundationProduct(foundationProduct).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SpecificationTypesAPIAPI.SpecificationTypesApiListSpecificationTypes``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SpecificationTypesApiListSpecificationTypes`: []SpecificationTypesApiListSpecificationTypesItem
	fmt.Fprintf(os.Stdout, "Response from `SpecificationTypesAPIAPI.SpecificationTypesApiListSpecificationTypes`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSpecificationTypesApiListSpecificationTypesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **specificationType** | **[]string** | The specification type. | 
 **checksheetType** | **string** | The checksheet type. | 
 **process** | **bool** | The process flag. | 
 **standard** | **bool** | The standard flag. | 
 **foundationProcess** | **bool** | The foundation process flag. | 
 **foundationProduct** | **bool** | The foundation product flag. | 

### Return type

[**[]SpecificationTypesApiListSpecificationTypesItem**](SpecificationTypesApiListSpecificationTypesItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

