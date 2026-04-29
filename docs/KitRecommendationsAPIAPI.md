# \KitRecommendationsAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**KitRecommendationsApiCreateKitRecommendation**](KitRecommendationsAPIAPI.md#KitRecommendationsApiCreateKitRecommendation) | **Post** /engineering/v1-beta1/kit-recommendations | Create Kit Recommendation
[**KitRecommendationsApiCreateKitRecommendationBomAssociation**](KitRecommendationsAPIAPI.md#KitRecommendationsApiCreateKitRecommendationBomAssociation) | **Post** /engineering/v1-beta1/kit-recommendations/{id}/bom | Create Kit Recommendation Bom Association
[**KitRecommendationsApiDeleteKitRecommendationBomAssociation**](KitRecommendationsAPIAPI.md#KitRecommendationsApiDeleteKitRecommendationBomAssociation) | **Delete** /engineering/v1-beta1/kit-recommendations/{id}/bom | Delete Kit Recommendation Bom Association
[**KitRecommendationsApiGetKitRecommendation**](KitRecommendationsAPIAPI.md#KitRecommendationsApiGetKitRecommendation) | **Get** /engineering/v1-beta1/kit-recommendations/{id} | Get Kit Recommendation
[**KitRecommendationsApiGetKitRecommendationBomAssociation**](KitRecommendationsAPIAPI.md#KitRecommendationsApiGetKitRecommendationBomAssociation) | **Get** /engineering/v1-beta1/kit-recommendations/{id}/bom | Get Kit Recommendation Bom Association
[**KitRecommendationsApiListKitRecommendations**](KitRecommendationsAPIAPI.md#KitRecommendationsApiListKitRecommendations) | **Get** /engineering/v1-beta1/kit-recommendations | List Kit Recommendations



## KitRecommendationsApiCreateKitRecommendation

> KitRecommendationsApiCreateKitRecommendation201Response KitRecommendationsApiCreateKitRecommendation(ctx).KitRecommendationsApiCreateKitRecommendationRequest(kitRecommendationsApiCreateKitRecommendationRequest).Execute()

Create Kit Recommendation



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
	kitRecommendationsApiCreateKitRecommendationRequest := *openapiclient.NewKitRecommendationsApiCreateKitRecommendationRequest() // KitRecommendationsApiCreateKitRecommendationRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.KitRecommendationsAPIAPI.KitRecommendationsApiCreateKitRecommendation(context.Background()).KitRecommendationsApiCreateKitRecommendationRequest(kitRecommendationsApiCreateKitRecommendationRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `KitRecommendationsAPIAPI.KitRecommendationsApiCreateKitRecommendation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `KitRecommendationsApiCreateKitRecommendation`: KitRecommendationsApiCreateKitRecommendation201Response
	fmt.Fprintf(os.Stdout, "Response from `KitRecommendationsAPIAPI.KitRecommendationsApiCreateKitRecommendation`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiKitRecommendationsApiCreateKitRecommendationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **kitRecommendationsApiCreateKitRecommendationRequest** | [**KitRecommendationsApiCreateKitRecommendationRequest**](KitRecommendationsApiCreateKitRecommendationRequest.md) |  | 

### Return type

[**KitRecommendationsApiCreateKitRecommendation201Response**](KitRecommendationsApiCreateKitRecommendation201Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## KitRecommendationsApiCreateKitRecommendationBomAssociation

> []KitRecommendationsApiCreateKitRecommendationBomAssociationItem KitRecommendationsApiCreateKitRecommendationBomAssociation(ctx, id).KitRecommendationsApiCreateKitRecommendationBomAssociationRequest(kitRecommendationsApiCreateKitRecommendationBomAssociationRequest).Execute()

Create Kit Recommendation Bom Association



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
	id := "00000000-0000-0000-0000-000000000000" // string | The Kit Recommendation ID.
	kitRecommendationsApiCreateKitRecommendationBomAssociationRequest := *openapiclient.NewKitRecommendationsApiCreateKitRecommendationBomAssociationRequest() // KitRecommendationsApiCreateKitRecommendationBomAssociationRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.KitRecommendationsAPIAPI.KitRecommendationsApiCreateKitRecommendationBomAssociation(context.Background(), id).KitRecommendationsApiCreateKitRecommendationBomAssociationRequest(kitRecommendationsApiCreateKitRecommendationBomAssociationRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `KitRecommendationsAPIAPI.KitRecommendationsApiCreateKitRecommendationBomAssociation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `KitRecommendationsApiCreateKitRecommendationBomAssociation`: []KitRecommendationsApiCreateKitRecommendationBomAssociationItem
	fmt.Fprintf(os.Stdout, "Response from `KitRecommendationsAPIAPI.KitRecommendationsApiCreateKitRecommendationBomAssociation`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The Kit Recommendation ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiKitRecommendationsApiCreateKitRecommendationBomAssociationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **kitRecommendationsApiCreateKitRecommendationBomAssociationRequest** | [**KitRecommendationsApiCreateKitRecommendationBomAssociationRequest**](KitRecommendationsApiCreateKitRecommendationBomAssociationRequest.md) |  | 

### Return type

[**[]KitRecommendationsApiCreateKitRecommendationBomAssociationItem**](KitRecommendationsApiCreateKitRecommendationBomAssociationItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## KitRecommendationsApiDeleteKitRecommendationBomAssociation

> KitRecommendationsApiDeleteKitRecommendationBomAssociation(ctx, id).KitRecommendationsApiDeleteKitRecommendationBomAssociationRequest(kitRecommendationsApiDeleteKitRecommendationBomAssociationRequest).Execute()

Delete Kit Recommendation Bom Association



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
	id := "00000000-0000-0000-0000-000000000000" // string | The Kit Recommendation ID.
	kitRecommendationsApiDeleteKitRecommendationBomAssociationRequest := *openapiclient.NewKitRecommendationsApiDeleteKitRecommendationBomAssociationRequest() // KitRecommendationsApiDeleteKitRecommendationBomAssociationRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.KitRecommendationsAPIAPI.KitRecommendationsApiDeleteKitRecommendationBomAssociation(context.Background(), id).KitRecommendationsApiDeleteKitRecommendationBomAssociationRequest(kitRecommendationsApiDeleteKitRecommendationBomAssociationRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `KitRecommendationsAPIAPI.KitRecommendationsApiDeleteKitRecommendationBomAssociation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The Kit Recommendation ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiKitRecommendationsApiDeleteKitRecommendationBomAssociationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **kitRecommendationsApiDeleteKitRecommendationBomAssociationRequest** | [**KitRecommendationsApiDeleteKitRecommendationBomAssociationRequest**](KitRecommendationsApiDeleteKitRecommendationBomAssociationRequest.md) |  | 

### Return type

 (empty response body)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## KitRecommendationsApiGetKitRecommendation

> KitRecommendationsApiGetKitRecommendationResponse KitRecommendationsApiGetKitRecommendation(ctx, id).Execute()

Get Kit Recommendation



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
	id := "00000000-0000-0000-0000-000000000000" // string | The Kit Recommendation ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.KitRecommendationsAPIAPI.KitRecommendationsApiGetKitRecommendation(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `KitRecommendationsAPIAPI.KitRecommendationsApiGetKitRecommendation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `KitRecommendationsApiGetKitRecommendation`: KitRecommendationsApiGetKitRecommendationResponse
	fmt.Fprintf(os.Stdout, "Response from `KitRecommendationsAPIAPI.KitRecommendationsApiGetKitRecommendation`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The Kit Recommendation ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiKitRecommendationsApiGetKitRecommendationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**KitRecommendationsApiGetKitRecommendationResponse**](KitRecommendationsApiGetKitRecommendationResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## KitRecommendationsApiGetKitRecommendationBomAssociation

> []KitRecommendationsApiGetKitRecommendationBomAssociationItem KitRecommendationsApiGetKitRecommendationBomAssociation(ctx, id).Execute()

Get Kit Recommendation Bom Association



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
	id := "00000000-0000-0000-0000-000000000000" // string | The Kit Recommendation ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.KitRecommendationsAPIAPI.KitRecommendationsApiGetKitRecommendationBomAssociation(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `KitRecommendationsAPIAPI.KitRecommendationsApiGetKitRecommendationBomAssociation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `KitRecommendationsApiGetKitRecommendationBomAssociation`: []KitRecommendationsApiGetKitRecommendationBomAssociationItem
	fmt.Fprintf(os.Stdout, "Response from `KitRecommendationsAPIAPI.KitRecommendationsApiGetKitRecommendationBomAssociation`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The Kit Recommendation ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiKitRecommendationsApiGetKitRecommendationBomAssociationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]KitRecommendationsApiGetKitRecommendationBomAssociationItem**](KitRecommendationsApiGetKitRecommendationBomAssociationItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## KitRecommendationsApiListKitRecommendations

> []KitRecommendationsApiListKitRecommendationsItem KitRecommendationsApiListKitRecommendations(ctx).Id(id).PartId(partId).BomId(bomId).Execute()

List Kit Recommendations



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
	id := []string{"00000000-0000-0000-0000-000000000000"} // []string | Search by Kit Recommendation ID. (optional)
	partId := []string{"00000000-0000-0000-0000-000000000000"} // []string | Search by Part ID. (optional)
	bomId := []string{"00000000-0000-0000-0000-000000000000"} // []string | Search by Bill of Material ID. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.KitRecommendationsAPIAPI.KitRecommendationsApiListKitRecommendations(context.Background()).Id(id).PartId(partId).BomId(bomId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `KitRecommendationsAPIAPI.KitRecommendationsApiListKitRecommendations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `KitRecommendationsApiListKitRecommendations`: []KitRecommendationsApiListKitRecommendationsItem
	fmt.Fprintf(os.Stdout, "Response from `KitRecommendationsAPIAPI.KitRecommendationsApiListKitRecommendations`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiKitRecommendationsApiListKitRecommendationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **[]string** | Search by Kit Recommendation ID. | 
 **partId** | **[]string** | Search by Part ID. | 
 **bomId** | **[]string** | Search by Bill of Material ID. | 

### Return type

[**[]KitRecommendationsApiListKitRecommendationsItem**](KitRecommendationsApiListKitRecommendationsItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

