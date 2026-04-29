# \PurchaseOrderReleasesAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**PurchaseOrderReleasesApiCancelRelease**](PurchaseOrderReleasesAPIAPI.md#PurchaseOrderReleasesApiCancelRelease) | **Post** /purchasing/v1/releases/{id}/cancel | Cancel Release
[**PurchaseOrderReleasesApiCreateRelease**](PurchaseOrderReleasesAPIAPI.md#PurchaseOrderReleasesApiCreateRelease) | **Post** /purchasing/v2-beta1/releases | Create Release
[**PurchaseOrderReleasesApiCreateReleases**](PurchaseOrderReleasesAPIAPI.md#PurchaseOrderReleasesApiCreateReleases) | **Post** /purchasing/v3/releases/create | Create Releases
[**PurchaseOrderReleasesApiDeleteRelease**](PurchaseOrderReleasesAPIAPI.md#PurchaseOrderReleasesApiDeleteRelease) | **Delete** /purchasing/v1/releases/{id} | Delete Release
[**PurchaseOrderReleasesApiGetRelease**](PurchaseOrderReleasesAPIAPI.md#PurchaseOrderReleasesApiGetRelease) | **Get** /purchasing/v2-beta1/releases/{id} | Get Release
[**PurchaseOrderReleasesApiListReleaseStatuses**](PurchaseOrderReleasesAPIAPI.md#PurchaseOrderReleasesApiListReleaseStatuses) | **Get** /purchasing/v1/release-statuses | List Release Statuses
[**PurchaseOrderReleasesApiListReleases**](PurchaseOrderReleasesAPIAPI.md#PurchaseOrderReleasesApiListReleases) | **Get** /purchasing/v2-beta1/releases | List Releases
[**PurchaseOrderReleasesApiUpdateRelease**](PurchaseOrderReleasesAPIAPI.md#PurchaseOrderReleasesApiUpdateRelease) | **Put** /purchasing/v2-beta1/releases/{id} | Update Release



## PurchaseOrderReleasesApiCancelRelease

> PurchaseOrderReleasesApiCancelRelease(ctx, id).PurchaseOrderReleasesApiCancelReleaseRequest(purchaseOrderReleasesApiCancelReleaseRequest).Execute()

Cancel Release



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
	id := "00000000-0000-0000-0000-000000000000" // string | The Release Resource Id.
	purchaseOrderReleasesApiCancelReleaseRequest := *openapiclient.NewPurchaseOrderReleasesApiCancelReleaseRequest() // PurchaseOrderReleasesApiCancelReleaseRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.PurchaseOrderReleasesAPIAPI.PurchaseOrderReleasesApiCancelRelease(context.Background(), id).PurchaseOrderReleasesApiCancelReleaseRequest(purchaseOrderReleasesApiCancelReleaseRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PurchaseOrderReleasesAPIAPI.PurchaseOrderReleasesApiCancelRelease``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The Release Resource Id. | 

### Other Parameters

Other parameters are passed through a pointer to a apiPurchaseOrderReleasesApiCancelReleaseRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **purchaseOrderReleasesApiCancelReleaseRequest** | [**PurchaseOrderReleasesApiCancelReleaseRequest**](PurchaseOrderReleasesApiCancelReleaseRequest.md) |  | 

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


## PurchaseOrderReleasesApiCreateRelease

> PurchaseOrderReleasesApiCreateRelease201Response PurchaseOrderReleasesApiCreateRelease(ctx).PurchaseOrderReleasesApiCreateReleaseRequest(purchaseOrderReleasesApiCreateReleaseRequest).Execute()

Create Release



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
	purchaseOrderReleasesApiCreateReleaseRequest := *openapiclient.NewPurchaseOrderReleasesApiCreateReleaseRequest() // PurchaseOrderReleasesApiCreateReleaseRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PurchaseOrderReleasesAPIAPI.PurchaseOrderReleasesApiCreateRelease(context.Background()).PurchaseOrderReleasesApiCreateReleaseRequest(purchaseOrderReleasesApiCreateReleaseRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PurchaseOrderReleasesAPIAPI.PurchaseOrderReleasesApiCreateRelease``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PurchaseOrderReleasesApiCreateRelease`: PurchaseOrderReleasesApiCreateRelease201Response
	fmt.Fprintf(os.Stdout, "Response from `PurchaseOrderReleasesAPIAPI.PurchaseOrderReleasesApiCreateRelease`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPurchaseOrderReleasesApiCreateReleaseRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **purchaseOrderReleasesApiCreateReleaseRequest** | [**PurchaseOrderReleasesApiCreateReleaseRequest**](PurchaseOrderReleasesApiCreateReleaseRequest.md) |  | 

### Return type

[**PurchaseOrderReleasesApiCreateRelease201Response**](PurchaseOrderReleasesApiCreateRelease201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PurchaseOrderReleasesApiCreateReleases

> PurchaseOrderReleasesApiCreateReleases201Response PurchaseOrderReleasesApiCreateReleases(ctx).PurchaseOrderReleasesApiCreateReleasesRequest(purchaseOrderReleasesApiCreateReleasesRequest).Execute()

Create Releases



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
	purchaseOrderReleasesApiCreateReleasesRequest := *openapiclient.NewPurchaseOrderReleasesApiCreateReleasesRequest() // PurchaseOrderReleasesApiCreateReleasesRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PurchaseOrderReleasesAPIAPI.PurchaseOrderReleasesApiCreateReleases(context.Background()).PurchaseOrderReleasesApiCreateReleasesRequest(purchaseOrderReleasesApiCreateReleasesRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PurchaseOrderReleasesAPIAPI.PurchaseOrderReleasesApiCreateReleases``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PurchaseOrderReleasesApiCreateReleases`: PurchaseOrderReleasesApiCreateReleases201Response
	fmt.Fprintf(os.Stdout, "Response from `PurchaseOrderReleasesAPIAPI.PurchaseOrderReleasesApiCreateReleases`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPurchaseOrderReleasesApiCreateReleasesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **purchaseOrderReleasesApiCreateReleasesRequest** | [**PurchaseOrderReleasesApiCreateReleasesRequest**](PurchaseOrderReleasesApiCreateReleasesRequest.md) |  | 

### Return type

[**PurchaseOrderReleasesApiCreateReleases201Response**](PurchaseOrderReleasesApiCreateReleases201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PurchaseOrderReleasesApiDeleteRelease

> PurchaseOrderReleasesApiDeleteRelease(ctx, id).Execute()

Delete Release



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
	r, err := apiClient.PurchaseOrderReleasesAPIAPI.PurchaseOrderReleasesApiDeleteRelease(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PurchaseOrderReleasesAPIAPI.PurchaseOrderReleasesApiDeleteRelease``: %v\n", err)
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

Other parameters are passed through a pointer to a apiPurchaseOrderReleasesApiDeleteReleaseRequest struct via the builder pattern


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


## PurchaseOrderReleasesApiGetRelease

> PurchaseOrderReleasesApiGetReleaseResponse PurchaseOrderReleasesApiGetRelease(ctx, id).Execute()

Get Release



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
	resp, r, err := apiClient.PurchaseOrderReleasesAPIAPI.PurchaseOrderReleasesApiGetRelease(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PurchaseOrderReleasesAPIAPI.PurchaseOrderReleasesApiGetRelease``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PurchaseOrderReleasesApiGetRelease`: PurchaseOrderReleasesApiGetReleaseResponse
	fmt.Fprintf(os.Stdout, "Response from `PurchaseOrderReleasesAPIAPI.PurchaseOrderReleasesApiGetRelease`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiPurchaseOrderReleasesApiGetReleaseRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**PurchaseOrderReleasesApiGetReleaseResponse**](PurchaseOrderReleasesApiGetReleaseResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PurchaseOrderReleasesApiListReleaseStatuses

> []PurchaseOrderReleasesApiListReleaseStatusesItem PurchaseOrderReleasesApiListReleaseStatuses(ctx).Name(name).IncludeInMrp(includeInMrp).Default_(default_).Active(active).Cancelled(cancelled).Received(received).Partial(partial).Forecast(forecast).PlanStatus(planStatus).MrpAutoChange(mrpAutoChange).Open(open).ImmediateStatus(immediateStatus).Execute()

List Release Statuses



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
	name := []string{"string"} // []string | A List of Release Status Names. (optional)
	includeInMrp := false // bool | IncludeInMrp Flag (optional)
	default_ := false // bool | Default Flag (optional)
	active := false // bool | Active Flag (optional)
	cancelled := false // bool | Cancelled Flag (optional)
	received := false // bool | Received Flag (optional)
	partial := false // bool | Partial Flag (optional)
	forecast := false // bool | Forecast Flag (optional)
	planStatus := false // bool | PlanStatus Flag (optional)
	mrpAutoChange := false // bool | MrpAutoChange Flag (optional)
	open := false // bool | Open Flag (optional)
	immediateStatus := false // bool | ImmediateStatus Flag (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PurchaseOrderReleasesAPIAPI.PurchaseOrderReleasesApiListReleaseStatuses(context.Background()).Name(name).IncludeInMrp(includeInMrp).Default_(default_).Active(active).Cancelled(cancelled).Received(received).Partial(partial).Forecast(forecast).PlanStatus(planStatus).MrpAutoChange(mrpAutoChange).Open(open).ImmediateStatus(immediateStatus).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PurchaseOrderReleasesAPIAPI.PurchaseOrderReleasesApiListReleaseStatuses``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PurchaseOrderReleasesApiListReleaseStatuses`: []PurchaseOrderReleasesApiListReleaseStatusesItem
	fmt.Fprintf(os.Stdout, "Response from `PurchaseOrderReleasesAPIAPI.PurchaseOrderReleasesApiListReleaseStatuses`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPurchaseOrderReleasesApiListReleaseStatusesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **name** | **[]string** | A List of Release Status Names. | 
 **includeInMrp** | **bool** | IncludeInMrp Flag | 
 **default_** | **bool** | Default Flag | 
 **active** | **bool** | Active Flag | 
 **cancelled** | **bool** | Cancelled Flag | 
 **received** | **bool** | Received Flag | 
 **partial** | **bool** | Partial Flag | 
 **forecast** | **bool** | Forecast Flag | 
 **planStatus** | **bool** | PlanStatus Flag | 
 **mrpAutoChange** | **bool** | MrpAutoChange Flag | 
 **open** | **bool** | Open Flag | 
 **immediateStatus** | **bool** | ImmediateStatus Flag | 

### Return type

[**[]PurchaseOrderReleasesApiListReleaseStatusesItem**](PurchaseOrderReleasesApiListReleaseStatusesItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PurchaseOrderReleasesApiListReleases

> []PurchaseOrderReleasesApiListReleasesItem PurchaseOrderReleasesApiListReleases(ctx).Id(id).POLineItemId(pOLineItemId).Status(status).ReleaseDateBegin(releaseDateBegin).ReleaseDateEnd(releaseDateEnd).DueDateBegin(dueDateBegin).DueDateEnd(dueDateEnd).ReleaseLineNumber(releaseLineNumber).CreatedDateBegin(createdDateBegin).CreatedDateEnd(createdDateEnd).ModifiedDateBegin(modifiedDateBegin).ModifiedDateEnd(modifiedDateEnd).PartId(partId).OriginalDueDateBegin(originalDueDateBegin).OriginalDueDateEnd(originalDueDateEnd).POId(pOId).SupplierId(supplierId).ReleaseAuthorizationNumber(releaseAuthorizationNumber).OperationCode(operationCode).Type_(type_).Execute()

List Releases



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := []string{"00000000-0000-0000-0000-000000000000"} // []string | A List of Release IDs. (optional)
	pOLineItemId := "00000000-0000-0000-0000-000000000000" // string | Purchase Order Line Item ID. (optional)
	status := []string{"string"} // []string |  (optional)
	releaseDateBegin := time.Now() // time.Time |  (optional)
	releaseDateEnd := time.Now() // time.Time |  (optional)
	dueDateBegin := time.Now() // time.Time | The Due Date of the Release. (optional)
	dueDateEnd := time.Now() // time.Time | The Due Date of the Release. (optional)
	releaseLineNumber := int32(0) // int32 | Release Line Number. (optional)
	createdDateBegin := time.Now() // time.Time | The date on which the record was created. (optional)
	createdDateEnd := time.Now() // time.Time | The date on which the record was created. (optional)
	modifiedDateBegin := time.Now() // time.Time | The date on which the record was last modified. (optional)
	modifiedDateEnd := time.Now() // time.Time | The date on which the record was last modified. (optional)
	partId := []string{"00000000-0000-0000-0000-000000000000"} // []string | The List of Part IDs associated with the Line item. (optional)
	originalDueDateBegin := time.Now() // time.Time | Original Due Date of the Release. (optional)
	originalDueDateEnd := time.Now() // time.Time | Original Due Date of the Release. (optional)
	pOId := []string{"00000000-0000-0000-0000-000000000000"} // []string | List Purchase Order ID. (optional)
	supplierId := []string{"00000000-0000-0000-0000-000000000000"} // []string |  (optional)
	releaseAuthorizationNumber := "string" // string | Release Authorization Number (optional)
	operationCode := "string" // string |  (optional)
	type_ := "string" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PurchaseOrderReleasesAPIAPI.PurchaseOrderReleasesApiListReleases(context.Background()).Id(id).POLineItemId(pOLineItemId).Status(status).ReleaseDateBegin(releaseDateBegin).ReleaseDateEnd(releaseDateEnd).DueDateBegin(dueDateBegin).DueDateEnd(dueDateEnd).ReleaseLineNumber(releaseLineNumber).CreatedDateBegin(createdDateBegin).CreatedDateEnd(createdDateEnd).ModifiedDateBegin(modifiedDateBegin).ModifiedDateEnd(modifiedDateEnd).PartId(partId).OriginalDueDateBegin(originalDueDateBegin).OriginalDueDateEnd(originalDueDateEnd).POId(pOId).SupplierId(supplierId).ReleaseAuthorizationNumber(releaseAuthorizationNumber).OperationCode(operationCode).Type_(type_).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PurchaseOrderReleasesAPIAPI.PurchaseOrderReleasesApiListReleases``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PurchaseOrderReleasesApiListReleases`: []PurchaseOrderReleasesApiListReleasesItem
	fmt.Fprintf(os.Stdout, "Response from `PurchaseOrderReleasesAPIAPI.PurchaseOrderReleasesApiListReleases`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPurchaseOrderReleasesApiListReleasesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **[]string** | A List of Release IDs. | 
 **pOLineItemId** | **string** | Purchase Order Line Item ID. | 
 **status** | **[]string** |  | 
 **releaseDateBegin** | **time.Time** |  | 
 **releaseDateEnd** | **time.Time** |  | 
 **dueDateBegin** | **time.Time** | The Due Date of the Release. | 
 **dueDateEnd** | **time.Time** | The Due Date of the Release. | 
 **releaseLineNumber** | **int32** | Release Line Number. | 
 **createdDateBegin** | **time.Time** | The date on which the record was created. | 
 **createdDateEnd** | **time.Time** | The date on which the record was created. | 
 **modifiedDateBegin** | **time.Time** | The date on which the record was last modified. | 
 **modifiedDateEnd** | **time.Time** | The date on which the record was last modified. | 
 **partId** | **[]string** | The List of Part IDs associated with the Line item. | 
 **originalDueDateBegin** | **time.Time** | Original Due Date of the Release. | 
 **originalDueDateEnd** | **time.Time** | Original Due Date of the Release. | 
 **pOId** | **[]string** | List Purchase Order ID. | 
 **supplierId** | **[]string** |  | 
 **releaseAuthorizationNumber** | **string** | Release Authorization Number | 
 **operationCode** | **string** |  | 
 **type_** | **string** |  | 

### Return type

[**[]PurchaseOrderReleasesApiListReleasesItem**](PurchaseOrderReleasesApiListReleasesItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PurchaseOrderReleasesApiUpdateRelease

> PurchaseOrderReleasesApiUpdateReleaseResponse PurchaseOrderReleasesApiUpdateRelease(ctx, id).PurchaseOrderReleasesApiUpdateReleaseRequest(purchaseOrderReleasesApiUpdateReleaseRequest).Execute()

Update Release



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
	id := "00000000-0000-0000-0000-000000000000" // string | The Release Resource ID.
	purchaseOrderReleasesApiUpdateReleaseRequest := *openapiclient.NewPurchaseOrderReleasesApiUpdateReleaseRequest() // PurchaseOrderReleasesApiUpdateReleaseRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PurchaseOrderReleasesAPIAPI.PurchaseOrderReleasesApiUpdateRelease(context.Background(), id).PurchaseOrderReleasesApiUpdateReleaseRequest(purchaseOrderReleasesApiUpdateReleaseRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PurchaseOrderReleasesAPIAPI.PurchaseOrderReleasesApiUpdateRelease``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PurchaseOrderReleasesApiUpdateRelease`: PurchaseOrderReleasesApiUpdateReleaseResponse
	fmt.Fprintf(os.Stdout, "Response from `PurchaseOrderReleasesAPIAPI.PurchaseOrderReleasesApiUpdateRelease`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The Release Resource ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiPurchaseOrderReleasesApiUpdateReleaseRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **purchaseOrderReleasesApiUpdateReleaseRequest** | [**PurchaseOrderReleasesApiUpdateReleaseRequest**](PurchaseOrderReleasesApiUpdateReleaseRequest.md) |  | 

### Return type

[**PurchaseOrderReleasesApiUpdateReleaseResponse**](PurchaseOrderReleasesApiUpdateReleaseResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

