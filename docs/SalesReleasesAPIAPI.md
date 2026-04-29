# \SalesReleasesAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SalesReleasesApiCreateRelease**](SalesReleasesAPIAPI.md#SalesReleasesApiCreateRelease) | **Post** /sales/v1/releases | Create Release
[**SalesReleasesApiGetRelease**](SalesReleasesAPIAPI.md#SalesReleasesApiGetRelease) | **Get** /sales/v1/releases/{id} | Get Release
[**SalesReleasesApiGetReleaseEDIDetails**](SalesReleasesAPIAPI.md#SalesReleasesApiGetReleaseEDIDetails) | **Get** /sales/v1/releases/{id}/edi-details | Get Release EDI Details
[**SalesReleasesApiListReleases**](SalesReleasesAPIAPI.md#SalesReleasesApiListReleases) | **Get** /sales/v1/releases | List Releases
[**SalesReleasesApiUpdateRelease**](SalesReleasesAPIAPI.md#SalesReleasesApiUpdateRelease) | **Put** /sales/v1/releases/{id} | Update Release
[**SalesReleasesApiUpdateReleaseEDIDetails**](SalesReleasesAPIAPI.md#SalesReleasesApiUpdateReleaseEDIDetails) | **Put** /sales/v1/releases/{id}/edi-details | Update Release EDI Details



## SalesReleasesApiCreateRelease

> SalesReleasesApiCreateRelease201Response SalesReleasesApiCreateRelease(ctx).SalesReleasesApiCreateReleaseRequest(salesReleasesApiCreateReleaseRequest).Execute()

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
	salesReleasesApiCreateReleaseRequest := *openapiclient.NewSalesReleasesApiCreateReleaseRequest() // SalesReleasesApiCreateReleaseRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SalesReleasesAPIAPI.SalesReleasesApiCreateRelease(context.Background()).SalesReleasesApiCreateReleaseRequest(salesReleasesApiCreateReleaseRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SalesReleasesAPIAPI.SalesReleasesApiCreateRelease``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SalesReleasesApiCreateRelease`: SalesReleasesApiCreateRelease201Response
	fmt.Fprintf(os.Stdout, "Response from `SalesReleasesAPIAPI.SalesReleasesApiCreateRelease`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSalesReleasesApiCreateReleaseRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **salesReleasesApiCreateReleaseRequest** | [**SalesReleasesApiCreateReleaseRequest**](SalesReleasesApiCreateReleaseRequest.md) |  | 

### Return type

[**SalesReleasesApiCreateRelease201Response**](SalesReleasesApiCreateRelease201Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SalesReleasesApiGetRelease

> SalesReleasesApiGetReleaseResponse SalesReleasesApiGetRelease(ctx, id).Execute()

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
	id := "00000000-0000-0000-0000-000000000000" // string | The release ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SalesReleasesAPIAPI.SalesReleasesApiGetRelease(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SalesReleasesAPIAPI.SalesReleasesApiGetRelease``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SalesReleasesApiGetRelease`: SalesReleasesApiGetReleaseResponse
	fmt.Fprintf(os.Stdout, "Response from `SalesReleasesAPIAPI.SalesReleasesApiGetRelease`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The release ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiSalesReleasesApiGetReleaseRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**SalesReleasesApiGetReleaseResponse**](SalesReleasesApiGetReleaseResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SalesReleasesApiGetReleaseEDIDetails

> SalesReleasesApiGetReleaseEDIDetailsResponse SalesReleasesApiGetReleaseEDIDetails(ctx, id).Execute()

Get Release EDI Details



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
	id := "00000000-0000-0000-0000-000000000000" // string | The release ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SalesReleasesAPIAPI.SalesReleasesApiGetReleaseEDIDetails(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SalesReleasesAPIAPI.SalesReleasesApiGetReleaseEDIDetails``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SalesReleasesApiGetReleaseEDIDetails`: SalesReleasesApiGetReleaseEDIDetailsResponse
	fmt.Fprintf(os.Stdout, "Response from `SalesReleasesAPIAPI.SalesReleasesApiGetReleaseEDIDetails`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The release ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiSalesReleasesApiGetReleaseEDIDetailsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**SalesReleasesApiGetReleaseEDIDetailsResponse**](SalesReleasesApiGetReleaseEDIDetailsResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SalesReleasesApiListReleases

> []SalesReleasesApiListReleasesItem SalesReleasesApiListReleases(ctx).Id(id).ReleaseNumber(releaseNumber).OrderLineIds(orderLineIds).Type_(type_).ShipToAddressId(shipToAddressId).ShipDateBegin(shipDateBegin).ShipDateEnd(shipDateEnd).DueDateBegin(dueDateBegin).DueDateEnd(dueDateEnd).Status(status).Source(source).ScheduleDateBegin(scheduleDateBegin).ScheduleDateEnd(scheduleDateEnd).CreatedById(createdById).CreatedDateBegin(createdDateBegin).CreatedDateEnd(createdDateEnd).ModifiedById(modifiedById).ModifiedDateBegin(modifiedDateBegin).ModifiedDateEnd(modifiedDateEnd).PartNumber(partNumber).Execute()

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
	id := "00000000-0000-0000-0000-000000000000" // string | The ID of the sales release. (optional)
	releaseNumber := "string" // string | The release number, typically dictated by the customer, for a specific sales release. (optional)
	orderLineIds := []string{"00000000-0000-0000-0000-000000000000"} // []string | The ID of the purchase order line. (optional)
	type_ := "string" // string | The release type for a specific sales release. (optional)
	shipToAddressId := "00000000-0000-0000-0000-000000000000" // string | The ID of the customer address to which the release will ship. (optional)
	shipDateBegin := time.Now() // time.Time | The date on which a sales release must be shipped to satisfy the release's due date. (optional)
	shipDateEnd := time.Now() // time.Time | The date on which a sales release must be shipped to satisfy the release's due date. (optional)
	dueDateBegin := time.Now() // time.Time | The date on which a sales release is expected to be fulfilled. (optional)
	dueDateEnd := time.Now() // time.Time | The date on which a sales release is expected to be fulfilled. (optional)
	status := "string" // string | The sales release's current status. (optional)
	source := "string" // string | Identifies the source of the sales release, such as EDI or email. (optional)
	scheduleDateBegin := time.Now() // time.Time | The schedule date relates multiple releases, which may span various parts and/or purchase orders, to a customer's schedule. This is typically populated via EDI. (optional)
	scheduleDateEnd := time.Now() // time.Time | The schedule date relates multiple releases, which may span various parts and/or purchase orders, to a customer's schedule. This is typically populated via EDI. (optional)
	createdById := "00000000-0000-0000-0000-000000000000" // string | The ID of the Plex user who created the record. (optional)
	createdDateBegin := time.Now() // time.Time | The date on which the record was created. (optional)
	createdDateEnd := time.Now() // time.Time | The date on which the record was created. (optional)
	modifiedById := "00000000-0000-0000-0000-000000000000" // string | The ID of the Plex user who last modified the record. (optional)
	modifiedDateBegin := time.Now() // time.Time | The date on which the record was last modified. (optional)
	modifiedDateEnd := time.Now() // time.Time | The date on which the record was last modified. (optional)
	partNumber := "string" // string | The part number for the sales release. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SalesReleasesAPIAPI.SalesReleasesApiListReleases(context.Background()).Id(id).ReleaseNumber(releaseNumber).OrderLineIds(orderLineIds).Type_(type_).ShipToAddressId(shipToAddressId).ShipDateBegin(shipDateBegin).ShipDateEnd(shipDateEnd).DueDateBegin(dueDateBegin).DueDateEnd(dueDateEnd).Status(status).Source(source).ScheduleDateBegin(scheduleDateBegin).ScheduleDateEnd(scheduleDateEnd).CreatedById(createdById).CreatedDateBegin(createdDateBegin).CreatedDateEnd(createdDateEnd).ModifiedById(modifiedById).ModifiedDateBegin(modifiedDateBegin).ModifiedDateEnd(modifiedDateEnd).PartNumber(partNumber).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SalesReleasesAPIAPI.SalesReleasesApiListReleases``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SalesReleasesApiListReleases`: []SalesReleasesApiListReleasesItem
	fmt.Fprintf(os.Stdout, "Response from `SalesReleasesAPIAPI.SalesReleasesApiListReleases`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSalesReleasesApiListReleasesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **string** | The ID of the sales release. | 
 **releaseNumber** | **string** | The release number, typically dictated by the customer, for a specific sales release. | 
 **orderLineIds** | **[]string** | The ID of the purchase order line. | 
 **type_** | **string** | The release type for a specific sales release. | 
 **shipToAddressId** | **string** | The ID of the customer address to which the release will ship. | 
 **shipDateBegin** | **time.Time** | The date on which a sales release must be shipped to satisfy the release&#39;s due date. | 
 **shipDateEnd** | **time.Time** | The date on which a sales release must be shipped to satisfy the release&#39;s due date. | 
 **dueDateBegin** | **time.Time** | The date on which a sales release is expected to be fulfilled. | 
 **dueDateEnd** | **time.Time** | The date on which a sales release is expected to be fulfilled. | 
 **status** | **string** | The sales release&#39;s current status. | 
 **source** | **string** | Identifies the source of the sales release, such as EDI or email. | 
 **scheduleDateBegin** | **time.Time** | The schedule date relates multiple releases, which may span various parts and/or purchase orders, to a customer&#39;s schedule. This is typically populated via EDI. | 
 **scheduleDateEnd** | **time.Time** | The schedule date relates multiple releases, which may span various parts and/or purchase orders, to a customer&#39;s schedule. This is typically populated via EDI. | 
 **createdById** | **string** | The ID of the Plex user who created the record. | 
 **createdDateBegin** | **time.Time** | The date on which the record was created. | 
 **createdDateEnd** | **time.Time** | The date on which the record was created. | 
 **modifiedById** | **string** | The ID of the Plex user who last modified the record. | 
 **modifiedDateBegin** | **time.Time** | The date on which the record was last modified. | 
 **modifiedDateEnd** | **time.Time** | The date on which the record was last modified. | 
 **partNumber** | **string** | The part number for the sales release. | 

### Return type

[**[]SalesReleasesApiListReleasesItem**](SalesReleasesApiListReleasesItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SalesReleasesApiUpdateRelease

> SalesReleasesApiUpdateReleaseResponse SalesReleasesApiUpdateRelease(ctx, id).SalesReleasesApiUpdateReleaseRequest(salesReleasesApiUpdateReleaseRequest).Execute()

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
	id := "00000000-0000-0000-0000-000000000000" // string | 
	salesReleasesApiUpdateReleaseRequest := *openapiclient.NewSalesReleasesApiUpdateReleaseRequest() // SalesReleasesApiUpdateReleaseRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SalesReleasesAPIAPI.SalesReleasesApiUpdateRelease(context.Background(), id).SalesReleasesApiUpdateReleaseRequest(salesReleasesApiUpdateReleaseRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SalesReleasesAPIAPI.SalesReleasesApiUpdateRelease``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SalesReleasesApiUpdateRelease`: SalesReleasesApiUpdateReleaseResponse
	fmt.Fprintf(os.Stdout, "Response from `SalesReleasesAPIAPI.SalesReleasesApiUpdateRelease`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSalesReleasesApiUpdateReleaseRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **salesReleasesApiUpdateReleaseRequest** | [**SalesReleasesApiUpdateReleaseRequest**](SalesReleasesApiUpdateReleaseRequest.md) |  | 

### Return type

[**SalesReleasesApiUpdateReleaseResponse**](SalesReleasesApiUpdateReleaseResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SalesReleasesApiUpdateReleaseEDIDetails

> SalesReleasesApiUpdateReleaseEDIDetailsResponse SalesReleasesApiUpdateReleaseEDIDetails(ctx, id).SalesReleasesApiUpdateReleaseEDIDetailsRequest(salesReleasesApiUpdateReleaseEDIDetailsRequest).Execute()

Update Release EDI Details



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
	id := "00000000-0000-0000-0000-000000000000" // string | The release ID.
	salesReleasesApiUpdateReleaseEDIDetailsRequest := *openapiclient.NewSalesReleasesApiUpdateReleaseEDIDetailsRequest() // SalesReleasesApiUpdateReleaseEDIDetailsRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SalesReleasesAPIAPI.SalesReleasesApiUpdateReleaseEDIDetails(context.Background(), id).SalesReleasesApiUpdateReleaseEDIDetailsRequest(salesReleasesApiUpdateReleaseEDIDetailsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SalesReleasesAPIAPI.SalesReleasesApiUpdateReleaseEDIDetails``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SalesReleasesApiUpdateReleaseEDIDetails`: SalesReleasesApiUpdateReleaseEDIDetailsResponse
	fmt.Fprintf(os.Stdout, "Response from `SalesReleasesAPIAPI.SalesReleasesApiUpdateReleaseEDIDetails`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The release ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiSalesReleasesApiUpdateReleaseEDIDetailsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **salesReleasesApiUpdateReleaseEDIDetailsRequest** | [**SalesReleasesApiUpdateReleaseEDIDetailsRequest**](SalesReleasesApiUpdateReleaseEDIDetailsRequest.md) |  | 

### Return type

[**SalesReleasesApiUpdateReleaseEDIDetailsResponse**](SalesReleasesApiUpdateReleaseEDIDetailsResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

