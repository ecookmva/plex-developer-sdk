# \UserAccountsAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**UserAccountsApiGetUserAccount**](UserAccountsAPIAPI.md#UserAccountsApiGetUserAccount) | **Get** /mdm/v1/user-accounts/{id} | Get User Account
[**UserAccountsApiListUserAccounts**](UserAccountsAPIAPI.md#UserAccountsApiListUserAccounts) | **Get** /mdm/v1/user-accounts | List User Accounts



## UserAccountsApiGetUserAccount

> UserAccountsApiGetUserAccountResponse UserAccountsApiGetUserAccount(ctx, id).Execute()

Get User Account



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
	resp, r, err := apiClient.UserAccountsAPIAPI.UserAccountsApiGetUserAccount(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UserAccountsAPIAPI.UserAccountsApiGetUserAccount``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UserAccountsApiGetUserAccount`: UserAccountsApiGetUserAccountResponse
	fmt.Fprintf(os.Stdout, "Response from `UserAccountsAPIAPI.UserAccountsApiGetUserAccount`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUserAccountsApiGetUserAccountRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**UserAccountsApiGetUserAccountResponse**](UserAccountsApiGetUserAccountResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UserAccountsApiListUserAccounts

> []UserAccountsApiListUserAccountsItem UserAccountsApiListUserAccounts(ctx).Id(id).UserId(userId).FirstName(firstName).MiddleName(middleName).LastName(lastName).Email(email).Position(position).Department(department).Execute()

List User Accounts



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
	id := []string{"00000000-0000-0000-0000-000000000000"} // []string | A unique identifier for the User Account. This will be automatically generated if omitted from the request. (optional)
	userId := "string" // string | The User ID as seen on Plex login screens. (optional)
	firstName := "string" // string |  (optional)
	middleName := "string" // string |  (optional)
	lastName := "string" // string |  (optional)
	email := "string" // string |  (optional)
	position := "string" // string | Position or title within the organization. (optional)
	department := "string" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UserAccountsAPIAPI.UserAccountsApiListUserAccounts(context.Background()).Id(id).UserId(userId).FirstName(firstName).MiddleName(middleName).LastName(lastName).Email(email).Position(position).Department(department).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UserAccountsAPIAPI.UserAccountsApiListUserAccounts``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UserAccountsApiListUserAccounts`: []UserAccountsApiListUserAccountsItem
	fmt.Fprintf(os.Stdout, "Response from `UserAccountsAPIAPI.UserAccountsApiListUserAccounts`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUserAccountsApiListUserAccountsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **[]string** | A unique identifier for the User Account. This will be automatically generated if omitted from the request. | 
 **userId** | **string** | The User ID as seen on Plex login screens. | 
 **firstName** | **string** |  | 
 **middleName** | **string** |  | 
 **lastName** | **string** |  | 
 **email** | **string** |  | 
 **position** | **string** | Position or title within the organization. | 
 **department** | **string** |  | 

### Return type

[**[]UserAccountsApiListUserAccountsItem**](UserAccountsApiListUserAccountsItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

