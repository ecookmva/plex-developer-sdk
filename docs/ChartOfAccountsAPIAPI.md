# \ChartOfAccountsAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ChartOfAccountsApiActivateAccount**](ChartOfAccountsAPIAPI.md#ChartOfAccountsApiActivateAccount) | **Post** /mdm/v1/chart-of-accounts/{id}/activate | Activate Account
[**ChartOfAccountsApiCreateAccount**](ChartOfAccountsAPIAPI.md#ChartOfAccountsApiCreateAccount) | **Post** /mdm/v1/chart-of-accounts | Create Account
[**ChartOfAccountsApiDeactivateAccount**](ChartOfAccountsAPIAPI.md#ChartOfAccountsApiDeactivateAccount) | **Post** /mdm/v1/chart-of-accounts/{id}/deactivate | Deactivate Account
[**ChartOfAccountsApiGetAccount**](ChartOfAccountsAPIAPI.md#ChartOfAccountsApiGetAccount) | **Get** /mdm/v1/chart-of-accounts/{id} | Get Account
[**ChartOfAccountsApiListAccounts**](ChartOfAccountsAPIAPI.md#ChartOfAccountsApiListAccounts) | **Get** /mdm/v1/chart-of-accounts | List Accounts
[**ChartOfAccountsApiSyncAccounts**](ChartOfAccountsAPIAPI.md#ChartOfAccountsApiSyncAccounts) | **Post** /mdm/v1/chart-of-accounts/sync | Sync Accounts
[**ChartOfAccountsApiUpdateAccount**](ChartOfAccountsAPIAPI.md#ChartOfAccountsApiUpdateAccount) | **Put** /mdm/v1/chart-of-accounts/{id} | Update Account



## ChartOfAccountsApiActivateAccount

> ChartOfAccountsApiActivateAccount(ctx, id).Execute()

Activate Account



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
	r, err := apiClient.ChartOfAccountsAPIAPI.ChartOfAccountsApiActivateAccount(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ChartOfAccountsAPIAPI.ChartOfAccountsApiActivateAccount``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiChartOfAccountsApiActivateAccountRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ChartOfAccountsApiCreateAccount

> ChartOfAccountsApiCreateAccount201Response ChartOfAccountsApiCreateAccount(ctx).ChartOfAccountsApiCreateAccountRequest(chartOfAccountsApiCreateAccountRequest).Execute()

Create Account



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
	chartOfAccountsApiCreateAccountRequest := *openapiclient.NewChartOfAccountsApiCreateAccountRequest() // ChartOfAccountsApiCreateAccountRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ChartOfAccountsAPIAPI.ChartOfAccountsApiCreateAccount(context.Background()).ChartOfAccountsApiCreateAccountRequest(chartOfAccountsApiCreateAccountRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ChartOfAccountsAPIAPI.ChartOfAccountsApiCreateAccount``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ChartOfAccountsApiCreateAccount`: ChartOfAccountsApiCreateAccount201Response
	fmt.Fprintf(os.Stdout, "Response from `ChartOfAccountsAPIAPI.ChartOfAccountsApiCreateAccount`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiChartOfAccountsApiCreateAccountRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **chartOfAccountsApiCreateAccountRequest** | [**ChartOfAccountsApiCreateAccountRequest**](ChartOfAccountsApiCreateAccountRequest.md) |  | 

### Return type

[**ChartOfAccountsApiCreateAccount201Response**](ChartOfAccountsApiCreateAccount201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ChartOfAccountsApiDeactivateAccount

> ChartOfAccountsApiDeactivateAccount(ctx, id).Execute()

Deactivate Account



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
	r, err := apiClient.ChartOfAccountsAPIAPI.ChartOfAccountsApiDeactivateAccount(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ChartOfAccountsAPIAPI.ChartOfAccountsApiDeactivateAccount``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiChartOfAccountsApiDeactivateAccountRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ChartOfAccountsApiGetAccount

> ChartOfAccountsApiGetAccountResponse ChartOfAccountsApiGetAccount(ctx, id).Execute()

Get Account



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
	resp, r, err := apiClient.ChartOfAccountsAPIAPI.ChartOfAccountsApiGetAccount(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ChartOfAccountsAPIAPI.ChartOfAccountsApiGetAccount``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ChartOfAccountsApiGetAccount`: ChartOfAccountsApiGetAccountResponse
	fmt.Fprintf(os.Stdout, "Response from `ChartOfAccountsAPIAPI.ChartOfAccountsApiGetAccount`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiChartOfAccountsApiGetAccountRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ChartOfAccountsApiGetAccountResponse**](ChartOfAccountsApiGetAccountResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ChartOfAccountsApiListAccounts

> []ChartOfAccountsApiListAccountsItem ChartOfAccountsApiListAccounts(ctx).Id(id).AccountNumber(accountNumber).Name(name).CategoryType(categoryType).Active(active).Execute()

List Accounts



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
	id := []string{"00000000-0000-0000-0000-000000000000"} // []string | A unique identifier for the Account. (optional)
	accountNumber := "string" // string | A supplemental ID field used to identify an account. (optional)
	name := "string" // string | A unique name for the account. (optional)
	categoryType := "string" // string | Must be one of the following values: Asset, Equity, Expense, Liability,  or Revenue. (optional)
	active := false // bool | This flag will be set to Active by default. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ChartOfAccountsAPIAPI.ChartOfAccountsApiListAccounts(context.Background()).Id(id).AccountNumber(accountNumber).Name(name).CategoryType(categoryType).Active(active).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ChartOfAccountsAPIAPI.ChartOfAccountsApiListAccounts``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ChartOfAccountsApiListAccounts`: []ChartOfAccountsApiListAccountsItem
	fmt.Fprintf(os.Stdout, "Response from `ChartOfAccountsAPIAPI.ChartOfAccountsApiListAccounts`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiChartOfAccountsApiListAccountsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **[]string** | A unique identifier for the Account. | 
 **accountNumber** | **string** | A supplemental ID field used to identify an account. | 
 **name** | **string** | A unique name for the account. | 
 **categoryType** | **string** | Must be one of the following values: Asset, Equity, Expense, Liability,  or Revenue. | 
 **active** | **bool** | This flag will be set to Active by default. | 

### Return type

[**[]ChartOfAccountsApiListAccountsItem**](ChartOfAccountsApiListAccountsItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ChartOfAccountsApiSyncAccounts

> ChartOfAccountsApiSyncAccounts(ctx).ChartOfAccountsApiSyncAccountsRequest(chartOfAccountsApiSyncAccountsRequest).Execute()

Sync Accounts



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
	chartOfAccountsApiSyncAccountsRequest := *openapiclient.NewChartOfAccountsApiSyncAccountsRequest() // ChartOfAccountsApiSyncAccountsRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ChartOfAccountsAPIAPI.ChartOfAccountsApiSyncAccounts(context.Background()).ChartOfAccountsApiSyncAccountsRequest(chartOfAccountsApiSyncAccountsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ChartOfAccountsAPIAPI.ChartOfAccountsApiSyncAccounts``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiChartOfAccountsApiSyncAccountsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **chartOfAccountsApiSyncAccountsRequest** | [**ChartOfAccountsApiSyncAccountsRequest**](ChartOfAccountsApiSyncAccountsRequest.md) |  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ChartOfAccountsApiUpdateAccount

> ChartOfAccountsApiUpdateAccountResponse ChartOfAccountsApiUpdateAccount(ctx, id).ChartOfAccountsApiUpdateAccountRequest(chartOfAccountsApiUpdateAccountRequest).Execute()

Update Account



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
	chartOfAccountsApiUpdateAccountRequest := *openapiclient.NewChartOfAccountsApiUpdateAccountRequest() // ChartOfAccountsApiUpdateAccountRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ChartOfAccountsAPIAPI.ChartOfAccountsApiUpdateAccount(context.Background(), id).ChartOfAccountsApiUpdateAccountRequest(chartOfAccountsApiUpdateAccountRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ChartOfAccountsAPIAPI.ChartOfAccountsApiUpdateAccount``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ChartOfAccountsApiUpdateAccount`: ChartOfAccountsApiUpdateAccountResponse
	fmt.Fprintf(os.Stdout, "Response from `ChartOfAccountsAPIAPI.ChartOfAccountsApiUpdateAccount`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiChartOfAccountsApiUpdateAccountRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **chartOfAccountsApiUpdateAccountRequest** | [**ChartOfAccountsApiUpdateAccountRequest**](ChartOfAccountsApiUpdateAccountRequest.md) |  | 

### Return type

[**ChartOfAccountsApiUpdateAccountResponse**](ChartOfAccountsApiUpdateAccountResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

