# \IdConversionAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**IdConversionApiListIds**](IdConversionAPIAPI.md#IdConversionApiListIds) | **Post** /platform/identity-mappings/v1/keys-to-ids | List Ids
[**IdConversionApiListKeys**](IdConversionAPIAPI.md#IdConversionApiListKeys) | **Post** /platform/identity-mappings/v1/ids-to-keys | List Keys



## IdConversionApiListIds

> IdConversionApiListIdsResponse IdConversionApiListIds(ctx).IdConversionApiListIdsRequest(idConversionApiListIdsRequest).Execute()

List Ids



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
	idConversionApiListIdsRequest := *openapiclient.NewIdConversionApiListIdsRequest() // IdConversionApiListIdsRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.IdConversionAPIAPI.IdConversionApiListIds(context.Background()).IdConversionApiListIdsRequest(idConversionApiListIdsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `IdConversionAPIAPI.IdConversionApiListIds``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `IdConversionApiListIds`: IdConversionApiListIdsResponse
	fmt.Fprintf(os.Stdout, "Response from `IdConversionAPIAPI.IdConversionApiListIds`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiIdConversionApiListIdsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **idConversionApiListIdsRequest** | [**IdConversionApiListIdsRequest**](IdConversionApiListIdsRequest.md) |  | 

### Return type

[**IdConversionApiListIdsResponse**](IdConversionApiListIdsResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## IdConversionApiListKeys

> IdConversionApiListKeysResponse IdConversionApiListKeys(ctx).IdConversionApiListKeysRequest(idConversionApiListKeysRequest).Execute()

List Keys



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
	idConversionApiListKeysRequest := *openapiclient.NewIdConversionApiListKeysRequest() // IdConversionApiListKeysRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.IdConversionAPIAPI.IdConversionApiListKeys(context.Background()).IdConversionApiListKeysRequest(idConversionApiListKeysRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `IdConversionAPIAPI.IdConversionApiListKeys``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `IdConversionApiListKeys`: IdConversionApiListKeysResponse
	fmt.Fprintf(os.Stdout, "Response from `IdConversionAPIAPI.IdConversionApiListKeys`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiIdConversionApiListKeysRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **idConversionApiListKeysRequest** | [**IdConversionApiListKeysRequest**](IdConversionApiListKeysRequest.md) |  | 

### Return type

[**IdConversionApiListKeysResponse**](IdConversionApiListKeysResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

