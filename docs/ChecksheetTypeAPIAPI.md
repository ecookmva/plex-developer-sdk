# \ChecksheetTypeAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ChecksheetTypeApiListChecksheetTypes**](ChecksheetTypeAPIAPI.md#ChecksheetTypeApiListChecksheetTypes) | **Get** /quality/v1/checksheet-types | List Checksheet Types



## ChecksheetTypeApiListChecksheetTypes

> []ChecksheetTypeApiListChecksheetTypesItem ChecksheetTypeApiListChecksheetTypes(ctx).Description(description).PreselectedSpecifications(preselectedSpecifications).InProcess(inProcess).Pieces(pieces).Container(container).Operation(operation).Workcenter(workcenter).SubgroupSize(subgroupSize).Subgroup(subgroup).Process(process).StatusRequired(statusRequired).Execute()

List Checksheet Types



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
	description := []string{"string"} // []string | A list of Checksheet Type descriptions. (optional)
	preselectedSpecifications := "string" // string | Determines if Customer Specified or Dock Audit specifications are preselected on the checksheet setup form when Specifications is set to Multiple Part Specs. (optional)
	inProcess := false // bool | Designation if the checksheet type is used for production checksheets launched from the Control Panel. (optional)
	pieces := int32(0) // int32 | The default number of measurements on the checksheet setup form. (optional)
	container := false // bool | Designation if container serial numbers are used on the checksheet form. Used in conjunction with the setting Container Text Standalone Display to enable the SPC Checksheet Container Text field on the checksheet form. (optional)
	operation := false // bool | Designation if the operation field is enabled on the checksheet form. (optional)
	workcenter := false // bool | Designation if workcenters are used on the checksheet setup. (optional)
	subgroupSize := int32(0) // int32 | The subgroup size. (optional)
	subgroup := false // bool | Designation if subgroups are used on the checksheet. (optional)
	process := false // bool | Designation if the checksheet type is used for Process Control checksheets. (optional)
	statusRequired := false // bool | Designation if the Status and Days Until Expiration fields are enabled on the checksheet. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ChecksheetTypeAPIAPI.ChecksheetTypeApiListChecksheetTypes(context.Background()).Description(description).PreselectedSpecifications(preselectedSpecifications).InProcess(inProcess).Pieces(pieces).Container(container).Operation(operation).Workcenter(workcenter).SubgroupSize(subgroupSize).Subgroup(subgroup).Process(process).StatusRequired(statusRequired).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ChecksheetTypeAPIAPI.ChecksheetTypeApiListChecksheetTypes``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ChecksheetTypeApiListChecksheetTypes`: []ChecksheetTypeApiListChecksheetTypesItem
	fmt.Fprintf(os.Stdout, "Response from `ChecksheetTypeAPIAPI.ChecksheetTypeApiListChecksheetTypes`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiChecksheetTypeApiListChecksheetTypesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **description** | **[]string** | A list of Checksheet Type descriptions. | 
 **preselectedSpecifications** | **string** | Determines if Customer Specified or Dock Audit specifications are preselected on the checksheet setup form when Specifications is set to Multiple Part Specs. | 
 **inProcess** | **bool** | Designation if the checksheet type is used for production checksheets launched from the Control Panel. | 
 **pieces** | **int32** | The default number of measurements on the checksheet setup form. | 
 **container** | **bool** | Designation if container serial numbers are used on the checksheet form. Used in conjunction with the setting Container Text Standalone Display to enable the SPC Checksheet Container Text field on the checksheet form. | 
 **operation** | **bool** | Designation if the operation field is enabled on the checksheet form. | 
 **workcenter** | **bool** | Designation if workcenters are used on the checksheet setup. | 
 **subgroupSize** | **int32** | The subgroup size. | 
 **subgroup** | **bool** | Designation if subgroups are used on the checksheet. | 
 **process** | **bool** | Designation if the checksheet type is used for Process Control checksheets. | 
 **statusRequired** | **bool** | Designation if the Status and Days Until Expiration fields are enabled on the checksheet. | 

### Return type

[**[]ChecksheetTypeApiListChecksheetTypesItem**](ChecksheetTypeApiListChecksheetTypesItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

