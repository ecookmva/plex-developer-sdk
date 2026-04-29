# \ProcessControlRecipeFamilyAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ProcessControlRecipeFamilyApiGetProcessControlRecipe**](ProcessControlRecipeFamilyAPIAPI.md#ProcessControlRecipeFamilyApiGetProcessControlRecipe) | **Get** /quality/v1/process-control-recipe-families/{processControlRecipeFamilyId}/process-control-recipes/{id} | Get Process Control Recipe
[**ProcessControlRecipeFamilyApiGetProcessControlRecipeFamily**](ProcessControlRecipeFamilyAPIAPI.md#ProcessControlRecipeFamilyApiGetProcessControlRecipeFamily) | **Get** /quality/v1/process-control-recipe-families/{id} | Get Process Control Recipe Family
[**ProcessControlRecipeFamilyApiListProcessControlRecipeFamilies**](ProcessControlRecipeFamilyAPIAPI.md#ProcessControlRecipeFamilyApiListProcessControlRecipeFamilies) | **Get** /quality/v1/process-control-recipe-families | List Process Control Recipe Families
[**ProcessControlRecipeFamilyApiListProcessControlRecipes**](ProcessControlRecipeFamilyAPIAPI.md#ProcessControlRecipeFamilyApiListProcessControlRecipes) | **Get** /quality/v1/process-control-recipe-families/{processControlRecipeFamilyId}/process-control-recipes | List Process Control Recipes



## ProcessControlRecipeFamilyApiGetProcessControlRecipe

> ProcessControlRecipeFamilyApiGetProcessControlRecipeResponse ProcessControlRecipeFamilyApiGetProcessControlRecipe(ctx, processControlRecipeFamilyId, id).Execute()

Get Process Control Recipe



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
	processControlRecipeFamilyId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the process control recipe family.
	id := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the process control recipe.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProcessControlRecipeFamilyAPIAPI.ProcessControlRecipeFamilyApiGetProcessControlRecipe(context.Background(), processControlRecipeFamilyId, id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProcessControlRecipeFamilyAPIAPI.ProcessControlRecipeFamilyApiGetProcessControlRecipe``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProcessControlRecipeFamilyApiGetProcessControlRecipe`: ProcessControlRecipeFamilyApiGetProcessControlRecipeResponse
	fmt.Fprintf(os.Stdout, "Response from `ProcessControlRecipeFamilyAPIAPI.ProcessControlRecipeFamilyApiGetProcessControlRecipe`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**processControlRecipeFamilyId** | **string** | A unique identifier for the process control recipe family. | 
**id** | **string** | A unique identifier for the process control recipe. | 

### Other Parameters

Other parameters are passed through a pointer to a apiProcessControlRecipeFamilyApiGetProcessControlRecipeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**ProcessControlRecipeFamilyApiGetProcessControlRecipeResponse**](ProcessControlRecipeFamilyApiGetProcessControlRecipeResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProcessControlRecipeFamilyApiGetProcessControlRecipeFamily

> ProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponse ProcessControlRecipeFamilyApiGetProcessControlRecipeFamily(ctx, id).Execute()

Get Process Control Recipe Family



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
	id := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the process control recipe family.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProcessControlRecipeFamilyAPIAPI.ProcessControlRecipeFamilyApiGetProcessControlRecipeFamily(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProcessControlRecipeFamilyAPIAPI.ProcessControlRecipeFamilyApiGetProcessControlRecipeFamily``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProcessControlRecipeFamilyApiGetProcessControlRecipeFamily`: ProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponse
	fmt.Fprintf(os.Stdout, "Response from `ProcessControlRecipeFamilyAPIAPI.ProcessControlRecipeFamilyApiGetProcessControlRecipeFamily`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | A unique identifier for the process control recipe family. | 

### Other Parameters

Other parameters are passed through a pointer to a apiProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponse**](ProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProcessControlRecipeFamilyApiListProcessControlRecipeFamilies

> []ProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItem ProcessControlRecipeFamilyApiListProcessControlRecipeFamilies(ctx).Ids(ids).PartIds(partIds).Code(code).OperationId(operationId).Execute()

List Process Control Recipe Families



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
	ids := []string{"00000000-0000-0000-0000-000000000000"} // []string | A list of IDs representing the Process Control Recipe Family. (optional)
	partIds := []string{"00000000-0000-0000-0000-000000000000"} // []string | A list of IDs representing the Part. (optional)
	code := []string{"string"} // []string | A list of Process Control Recipe Family Codes. (optional)
	operationId := "00000000-0000-0000-0000-000000000000" // string | The Operation ID associated with the Process Control Recipe. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProcessControlRecipeFamilyAPIAPI.ProcessControlRecipeFamilyApiListProcessControlRecipeFamilies(context.Background()).Ids(ids).PartIds(partIds).Code(code).OperationId(operationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProcessControlRecipeFamilyAPIAPI.ProcessControlRecipeFamilyApiListProcessControlRecipeFamilies``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProcessControlRecipeFamilyApiListProcessControlRecipeFamilies`: []ProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItem
	fmt.Fprintf(os.Stdout, "Response from `ProcessControlRecipeFamilyAPIAPI.ProcessControlRecipeFamilyApiListProcessControlRecipeFamilies`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ids** | **[]string** | A list of IDs representing the Process Control Recipe Family. | 
 **partIds** | **[]string** | A list of IDs representing the Part. | 
 **code** | **[]string** | A list of Process Control Recipe Family Codes. | 
 **operationId** | **string** | The Operation ID associated with the Process Control Recipe. | 

### Return type

[**[]ProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItem**](ProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProcessControlRecipeFamilyApiListProcessControlRecipes

> []ProcessControlRecipeFamilyApiListProcessControlRecipesItem ProcessControlRecipeFamilyApiListProcessControlRecipes(ctx, processControlRecipeFamilyId).Ids(ids).Code(code).WorkcenterIds(workcenterIds).Execute()

List Process Control Recipes



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
	processControlRecipeFamilyId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the process control recipe family.
	ids := []string{"00000000-0000-0000-0000-000000000000"} // []string | A list of IDs representing the Process Control Recipe. (optional)
	code := []string{"string"} // []string | A list of Process Control Recipe Codes. (optional)
	workcenterIds := []string{"00000000-0000-0000-0000-000000000000"} // []string | A list of IDs representing the Process Control Recipe. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProcessControlRecipeFamilyAPIAPI.ProcessControlRecipeFamilyApiListProcessControlRecipes(context.Background(), processControlRecipeFamilyId).Ids(ids).Code(code).WorkcenterIds(workcenterIds).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProcessControlRecipeFamilyAPIAPI.ProcessControlRecipeFamilyApiListProcessControlRecipes``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProcessControlRecipeFamilyApiListProcessControlRecipes`: []ProcessControlRecipeFamilyApiListProcessControlRecipesItem
	fmt.Fprintf(os.Stdout, "Response from `ProcessControlRecipeFamilyAPIAPI.ProcessControlRecipeFamilyApiListProcessControlRecipes`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**processControlRecipeFamilyId** | **string** | A unique identifier for the process control recipe family. | 

### Other Parameters

Other parameters are passed through a pointer to a apiProcessControlRecipeFamilyApiListProcessControlRecipesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **ids** | **[]string** | A list of IDs representing the Process Control Recipe. | 
 **code** | **[]string** | A list of Process Control Recipe Codes. | 
 **workcenterIds** | **[]string** | A list of IDs representing the Process Control Recipe. | 

### Return type

[**[]ProcessControlRecipeFamilyApiListProcessControlRecipesItem**](ProcessControlRecipeFamilyApiListProcessControlRecipesItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

