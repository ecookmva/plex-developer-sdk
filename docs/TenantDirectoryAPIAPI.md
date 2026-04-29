# \TenantDirectoryAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**TenantDirectoryApiGetTenant**](TenantDirectoryAPIAPI.md#TenantDirectoryApiGetTenant) | **Get** /mdm/v1/tenants/{id} | Get Tenant
[**TenantDirectoryApiListTenants**](TenantDirectoryAPIAPI.md#TenantDirectoryApiListTenants) | **Get** /mdm/v1/tenants | List Tenants



## TenantDirectoryApiGetTenant

> TenantDirectoryApiGetTenantResponse TenantDirectoryApiGetTenant(ctx, id).Execute()

Get Tenant



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
	resp, r, err := apiClient.TenantDirectoryAPIAPI.TenantDirectoryApiGetTenant(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TenantDirectoryAPIAPI.TenantDirectoryApiGetTenant``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TenantDirectoryApiGetTenant`: TenantDirectoryApiGetTenantResponse
	fmt.Fprintf(os.Stdout, "Response from `TenantDirectoryAPIAPI.TenantDirectoryApiGetTenant`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiTenantDirectoryApiGetTenantRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**TenantDirectoryApiGetTenantResponse**](TenantDirectoryApiGetTenantResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TenantDirectoryApiListTenants

> []TenantDirectoryApiListTenantsItem TenantDirectoryApiListTenants(ctx).IdList(idList).Code(code).CodeList(codeList).Execute()

List Tenants



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
	idList := []string{"00000000-0000-0000-0000-000000000000"} // []string | A list of Tenant IDs. (optional)
	code := "string" // string | The Company Code as seen on Plex login screens. (optional)
	codeList := []string{"string"} // []string | A list of Company Codes as seen on Plex login screens. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TenantDirectoryAPIAPI.TenantDirectoryApiListTenants(context.Background()).IdList(idList).Code(code).CodeList(codeList).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TenantDirectoryAPIAPI.TenantDirectoryApiListTenants``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TenantDirectoryApiListTenants`: []TenantDirectoryApiListTenantsItem
	fmt.Fprintf(os.Stdout, "Response from `TenantDirectoryAPIAPI.TenantDirectoryApiListTenants`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiTenantDirectoryApiListTenantsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **idList** | **[]string** | A list of Tenant IDs. | 
 **code** | **string** | The Company Code as seen on Plex login screens. | 
 **codeList** | **[]string** | A list of Company Codes as seen on Plex login screens. | 

### Return type

[**[]TenantDirectoryApiListTenantsItem**](TenantDirectoryApiListTenantsItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

