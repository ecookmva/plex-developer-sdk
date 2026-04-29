# \JustInSequenceAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**JustInSequenceApiAuditJISRelease**](JustInSequenceAPIAPI.md#JustInSequenceApiAuditJISRelease) | **Post** /shipping/v1/jis/releases/{id}/confirm | Audit JIS Release
[**JustInSequenceApiCreateJISKit**](JustInSequenceAPIAPI.md#JustInSequenceApiCreateJISKit) | **Post** /shipping/v1/jis/kits | Create JIS Kit
[**JustInSequenceApiCreateJISRack**](JustInSequenceAPIAPI.md#JustInSequenceApiCreateJISRack) | **Post** /shipping/v1/jis/racks | Create JIS Rack
[**JustInSequenceApiCreateJISRelease**](JustInSequenceAPIAPI.md#JustInSequenceApiCreateJISRelease) | **Post** /shipping/v1/jis/releases | Create JIS Release
[**JustInSequenceApiCreatePlannedJISRack**](JustInSequenceAPIAPI.md#JustInSequenceApiCreatePlannedJISRack) | **Post** /shipping/v1/jis/create-planned-rack | Create Planned JIS Rack
[**JustInSequenceApiGetJISKit**](JustInSequenceAPIAPI.md#JustInSequenceApiGetJISKit) | **Get** /shipping/v1/jis/kits/{id} | Get JIS Kit
[**JustInSequenceApiGetJISRack**](JustInSequenceAPIAPI.md#JustInSequenceApiGetJISRack) | **Get** /shipping/v1/jis/racks/{id} | Get JIS Rack
[**JustInSequenceApiGetJISRelease**](JustInSequenceAPIAPI.md#JustInSequenceApiGetJISRelease) | **Get** /shipping/v1/jis/releases/{id} | Get JIS Release
[**JustInSequenceApiListJISKits**](JustInSequenceAPIAPI.md#JustInSequenceApiListJISKits) | **Get** /shipping/v1/jis/kits | List JIS Kits
[**JustInSequenceApiListJISRacks**](JustInSequenceAPIAPI.md#JustInSequenceApiListJISRacks) | **Get** /shipping/v1/jis/racks | List JIS Racks
[**JustInSequenceApiListJISReleases**](JustInSequenceAPIAPI.md#JustInSequenceApiListJISReleases) | **Get** /shipping/v1/jis/releases | List JIS Releases
[**JustInSequenceApiLoadJISRack**](JustInSequenceAPIAPI.md#JustInSequenceApiLoadJISRack) | **Post** /shipping/v1/jis/racks/{id}/load-to-truck | Load JIS Rack
[**JustInSequenceApiPackJISKitByModule**](JustInSequenceAPIAPI.md#JustInSequenceApiPackJISKitByModule) | **Post** /shipping/v1/jis/kits/{id}/pack-by-module | Pack JIS Kit By Module
[**JustInSequenceApiPackJISRackByFIFO**](JustInSequenceAPIAPI.md#JustInSequenceApiPackJISRackByFIFO) | **Post** /shipping/v1/jis/racks/{id}/pack-by-fifo | Pack JIS Rack By FIFO
[**JustInSequenceApiPackJISRackByMasterUnit**](JustInSequenceAPIAPI.md#JustInSequenceApiPackJISRackByMasterUnit) | **Post** /shipping/v1/jis/racks/{id}/pack-by-master-unit | Pack JIS Rack By Master Unit
[**JustInSequenceApiPackJISReleaseByContainer**](JustInSequenceAPIAPI.md#JustInSequenceApiPackJISReleaseByContainer) | **Post** /shipping/v1/jis/releases/{id}/pack-by-container | Pack JIS Release By Container
[**JustInSequenceApiPackJISReleaseByFIFO**](JustInSequenceAPIAPI.md#JustInSequenceApiPackJISReleaseByFIFO) | **Post** /shipping/v1/jis/releases/{id}/pack-by-fifo | Pack JIS Release By FIFO



## JustInSequenceApiAuditJISRelease

> JustInSequenceApiAuditJISRelease(ctx, id).JustInSequenceApiAuditJISReleaseRequest(justInSequenceApiAuditJISReleaseRequest).Execute()

Audit JIS Release



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
	id := "00000000-0000-0000-0000-000000000000" // string | The ID of the sequenced release.
	justInSequenceApiAuditJISReleaseRequest := *openapiclient.NewJustInSequenceApiAuditJISReleaseRequest() // JustInSequenceApiAuditJISReleaseRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.JustInSequenceAPIAPI.JustInSequenceApiAuditJISRelease(context.Background(), id).JustInSequenceApiAuditJISReleaseRequest(justInSequenceApiAuditJISReleaseRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JustInSequenceAPIAPI.JustInSequenceApiAuditJISRelease``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The ID of the sequenced release. | 

### Other Parameters

Other parameters are passed through a pointer to a apiJustInSequenceApiAuditJISReleaseRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **justInSequenceApiAuditJISReleaseRequest** | [**JustInSequenceApiAuditJISReleaseRequest**](JustInSequenceApiAuditJISReleaseRequest.md) |  | 

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


## JustInSequenceApiCreateJISKit

> JustInSequenceApiCreateJISKit201Response JustInSequenceApiCreateJISKit(ctx).JustInSequenceApiCreateJISKitRequest(justInSequenceApiCreateJISKitRequest).Execute()

Create JIS Kit



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
	justInSequenceApiCreateJISKitRequest := *openapiclient.NewJustInSequenceApiCreateJISKitRequest() // JustInSequenceApiCreateJISKitRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.JustInSequenceAPIAPI.JustInSequenceApiCreateJISKit(context.Background()).JustInSequenceApiCreateJISKitRequest(justInSequenceApiCreateJISKitRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JustInSequenceAPIAPI.JustInSequenceApiCreateJISKit``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `JustInSequenceApiCreateJISKit`: JustInSequenceApiCreateJISKit201Response
	fmt.Fprintf(os.Stdout, "Response from `JustInSequenceAPIAPI.JustInSequenceApiCreateJISKit`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiJustInSequenceApiCreateJISKitRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **justInSequenceApiCreateJISKitRequest** | [**JustInSequenceApiCreateJISKitRequest**](JustInSequenceApiCreateJISKitRequest.md) |  | 

### Return type

[**JustInSequenceApiCreateJISKit201Response**](JustInSequenceApiCreateJISKit201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## JustInSequenceApiCreateJISRack

> JustInSequenceApiCreateJISRack201Response JustInSequenceApiCreateJISRack(ctx).JustInSequenceApiCreateJISRackRequest(justInSequenceApiCreateJISRackRequest).Execute()

Create JIS Rack



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
	justInSequenceApiCreateJISRackRequest := *openapiclient.NewJustInSequenceApiCreateJISRackRequest() // JustInSequenceApiCreateJISRackRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.JustInSequenceAPIAPI.JustInSequenceApiCreateJISRack(context.Background()).JustInSequenceApiCreateJISRackRequest(justInSequenceApiCreateJISRackRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JustInSequenceAPIAPI.JustInSequenceApiCreateJISRack``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `JustInSequenceApiCreateJISRack`: JustInSequenceApiCreateJISRack201Response
	fmt.Fprintf(os.Stdout, "Response from `JustInSequenceAPIAPI.JustInSequenceApiCreateJISRack`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiJustInSequenceApiCreateJISRackRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **justInSequenceApiCreateJISRackRequest** | [**JustInSequenceApiCreateJISRackRequest**](JustInSequenceApiCreateJISRackRequest.md) |  | 

### Return type

[**JustInSequenceApiCreateJISRack201Response**](JustInSequenceApiCreateJISRack201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## JustInSequenceApiCreateJISRelease

> JustInSequenceApiCreateJISRelease201Response JustInSequenceApiCreateJISRelease(ctx).JustInSequenceApiCreateJISReleaseRequest(justInSequenceApiCreateJISReleaseRequest).Execute()

Create JIS Release



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
	justInSequenceApiCreateJISReleaseRequest := *openapiclient.NewJustInSequenceApiCreateJISReleaseRequest() // JustInSequenceApiCreateJISReleaseRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.JustInSequenceAPIAPI.JustInSequenceApiCreateJISRelease(context.Background()).JustInSequenceApiCreateJISReleaseRequest(justInSequenceApiCreateJISReleaseRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JustInSequenceAPIAPI.JustInSequenceApiCreateJISRelease``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `JustInSequenceApiCreateJISRelease`: JustInSequenceApiCreateJISRelease201Response
	fmt.Fprintf(os.Stdout, "Response from `JustInSequenceAPIAPI.JustInSequenceApiCreateJISRelease`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiJustInSequenceApiCreateJISReleaseRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **justInSequenceApiCreateJISReleaseRequest** | [**JustInSequenceApiCreateJISReleaseRequest**](JustInSequenceApiCreateJISReleaseRequest.md) |  | 

### Return type

[**JustInSequenceApiCreateJISRelease201Response**](JustInSequenceApiCreateJISRelease201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## JustInSequenceApiCreatePlannedJISRack

> JustInSequenceApiCreatePlannedJISRack201Response JustInSequenceApiCreatePlannedJISRack(ctx).JustInSequenceApiCreatePlannedJISRackRequest(justInSequenceApiCreatePlannedJISRackRequest).Execute()

Create Planned JIS Rack



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
	justInSequenceApiCreatePlannedJISRackRequest := *openapiclient.NewJustInSequenceApiCreatePlannedJISRackRequest() // JustInSequenceApiCreatePlannedJISRackRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.JustInSequenceAPIAPI.JustInSequenceApiCreatePlannedJISRack(context.Background()).JustInSequenceApiCreatePlannedJISRackRequest(justInSequenceApiCreatePlannedJISRackRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JustInSequenceAPIAPI.JustInSequenceApiCreatePlannedJISRack``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `JustInSequenceApiCreatePlannedJISRack`: JustInSequenceApiCreatePlannedJISRack201Response
	fmt.Fprintf(os.Stdout, "Response from `JustInSequenceAPIAPI.JustInSequenceApiCreatePlannedJISRack`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiJustInSequenceApiCreatePlannedJISRackRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **justInSequenceApiCreatePlannedJISRackRequest** | [**JustInSequenceApiCreatePlannedJISRackRequest**](JustInSequenceApiCreatePlannedJISRackRequest.md) |  | 

### Return type

[**JustInSequenceApiCreatePlannedJISRack201Response**](JustInSequenceApiCreatePlannedJISRack201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## JustInSequenceApiGetJISKit

> JustInSequenceApiGetJISKitResponse JustInSequenceApiGetJISKit(ctx, id).Execute()

Get JIS Kit



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
	id := "00000000-0000-0000-0000-000000000000" // string | Kit ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.JustInSequenceAPIAPI.JustInSequenceApiGetJISKit(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JustInSequenceAPIAPI.JustInSequenceApiGetJISKit``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `JustInSequenceApiGetJISKit`: JustInSequenceApiGetJISKitResponse
	fmt.Fprintf(os.Stdout, "Response from `JustInSequenceAPIAPI.JustInSequenceApiGetJISKit`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Kit ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiJustInSequenceApiGetJISKitRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**JustInSequenceApiGetJISKitResponse**](JustInSequenceApiGetJISKitResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## JustInSequenceApiGetJISRack

> JustInSequenceApiGetJISRackResponse JustInSequenceApiGetJISRack(ctx, id).Execute()

Get JIS Rack



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
	id := "00000000-0000-0000-0000-000000000000" // string | Rack ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.JustInSequenceAPIAPI.JustInSequenceApiGetJISRack(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JustInSequenceAPIAPI.JustInSequenceApiGetJISRack``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `JustInSequenceApiGetJISRack`: JustInSequenceApiGetJISRackResponse
	fmt.Fprintf(os.Stdout, "Response from `JustInSequenceAPIAPI.JustInSequenceApiGetJISRack`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Rack ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiJustInSequenceApiGetJISRackRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**JustInSequenceApiGetJISRackResponse**](JustInSequenceApiGetJISRackResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## JustInSequenceApiGetJISRelease

> JustInSequenceApiGetJISReleaseResponse JustInSequenceApiGetJISRelease(ctx, id).Execute()

Get JIS Release



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
	id := "00000000-0000-0000-0000-000000000000" // string | The Release's resource id.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.JustInSequenceAPIAPI.JustInSequenceApiGetJISRelease(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JustInSequenceAPIAPI.JustInSequenceApiGetJISRelease``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `JustInSequenceApiGetJISRelease`: JustInSequenceApiGetJISReleaseResponse
	fmt.Fprintf(os.Stdout, "Response from `JustInSequenceAPIAPI.JustInSequenceApiGetJISRelease`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The Release&#39;s resource id. | 

### Other Parameters

Other parameters are passed through a pointer to a apiJustInSequenceApiGetJISReleaseRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**JustInSequenceApiGetJISReleaseResponse**](JustInSequenceApiGetJISReleaseResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## JustInSequenceApiListJISKits

> []JustInSequenceApiListJISKitsItem JustInSequenceApiListJISKits(ctx).Id(id).JisKitStatus(jisKitStatus).KitName(kitName).IsReprintNeeded(isReprintNeeded).AddDateTimeBegin(addDateTimeBegin).AddDateTimeEnd(addDateTimeEnd).RackSequenceNumber(rackSequenceNumber).LabelPrintedDateTimeBegin(labelPrintedDateTimeBegin).LabelPrintedDateTimeEnd(labelPrintedDateTimeEnd).Execute()

List JIS Kits



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
	id := "00000000-0000-0000-0000-000000000000" // string | The ID of the sequenced kit. (optional)
	jisKitStatus := "string" // string | The sequenced kit's status. (optional)
	kitName := "string" // string | The sequenced kit's name. (optional)
	isReprintNeeded := false // bool | Determines whether the kit requires its paperwork to be reprinted. (optional)
	addDateTimeBegin := time.Now() // time.Time | The beginning date and time on which the kit was created. (optional)
	addDateTimeEnd := time.Now() // time.Time | The ending date and time on which the kit was created. (optional)
	rackSequenceNumber := "string" // string | The kit's rack number. (optional)
	labelPrintedDateTimeBegin := time.Now() // time.Time | The beginning date and time on which the kit label was last printed. (optional)
	labelPrintedDateTimeEnd := time.Now() // time.Time | The ending date and time on which the kit label was last printed. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.JustInSequenceAPIAPI.JustInSequenceApiListJISKits(context.Background()).Id(id).JisKitStatus(jisKitStatus).KitName(kitName).IsReprintNeeded(isReprintNeeded).AddDateTimeBegin(addDateTimeBegin).AddDateTimeEnd(addDateTimeEnd).RackSequenceNumber(rackSequenceNumber).LabelPrintedDateTimeBegin(labelPrintedDateTimeBegin).LabelPrintedDateTimeEnd(labelPrintedDateTimeEnd).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JustInSequenceAPIAPI.JustInSequenceApiListJISKits``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `JustInSequenceApiListJISKits`: []JustInSequenceApiListJISKitsItem
	fmt.Fprintf(os.Stdout, "Response from `JustInSequenceAPIAPI.JustInSequenceApiListJISKits`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiJustInSequenceApiListJISKitsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **string** | The ID of the sequenced kit. | 
 **jisKitStatus** | **string** | The sequenced kit&#39;s status. | 
 **kitName** | **string** | The sequenced kit&#39;s name. | 
 **isReprintNeeded** | **bool** | Determines whether the kit requires its paperwork to be reprinted. | 
 **addDateTimeBegin** | **time.Time** | The beginning date and time on which the kit was created. | 
 **addDateTimeEnd** | **time.Time** | The ending date and time on which the kit was created. | 
 **rackSequenceNumber** | **string** | The kit&#39;s rack number. | 
 **labelPrintedDateTimeBegin** | **time.Time** | The beginning date and time on which the kit label was last printed. | 
 **labelPrintedDateTimeEnd** | **time.Time** | The ending date and time on which the kit label was last printed. | 

### Return type

[**[]JustInSequenceApiListJISKitsItem**](JustInSequenceApiListJISKitsItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## JustInSequenceApiListJISRacks

> []JustInSequenceApiListJISRacksItem JustInSequenceApiListJISRacks(ctx).Id(id).RackStatus(rackStatus).RackSequenceNumber(rackSequenceNumber).MasterUnitNumber(masterUnitNumber).LineSequenceSetupName(lineSequenceSetupName).CreatedDateTimeStart(createdDateTimeStart).CreatedDateTimeEnd(createdDateTimeEnd).ReprintNeeded(reprintNeeded).PrintedDateTimeStart(printedDateTimeStart).PrintedDateTimeEnd(printedDateTimeEnd).TruckID(truckID).TruckNumber(truckNumber).TrailerNumber(trailerNumber).LabelPrintedDateTimeStart(labelPrintedDateTimeStart).LabelPrintedDateTimeEnd(labelPrintedDateTimeEnd).Execute()

List JIS Racks



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
	id := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the sales order. This will be automatically generated if omitted from the request. (optional)
	rackStatus := []string{"string"} // []string | The status of the rack. (optional)
	rackSequenceNumber := "string" // string | The rack sequence number. (optional)
	masterUnitNumber := "string" // string | The master unit number associated with the rack. (optional)
	lineSequenceSetupName := "string" // string | The rack's line sequence setup name. (optional)
	createdDateTimeStart := time.Now() // time.Time | The start date and time on which the rack was added. (optional)
	createdDateTimeEnd := time.Now() // time.Time | The end date and time on which the rack was added. (optional)
	reprintNeeded := false // bool | Determines whether the rack requires its paperwork to be reprinted. (optional)
	printedDateTimeStart := time.Now() // time.Time | The start date and time on which the rack paperwork was last printed. (optional)
	printedDateTimeEnd := time.Now() // time.Time | The end date and time on which the rack paperwork was last printed. (optional)
	truckID := "00000000-0000-0000-0000-000000000000" // string | The unique ID of the truck associated with the rack. (optional)
	truckNumber := "string" // string | The truck number associated with the rack. (optional)
	trailerNumber := "string" // string | The trailer number of the rack's associated truck. (optional)
	labelPrintedDateTimeStart := time.Now() // time.Time | The start date and time on which the rack label was last printed. (optional)
	labelPrintedDateTimeEnd := time.Now() // time.Time | The end date and time on which the rack label was last printed. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.JustInSequenceAPIAPI.JustInSequenceApiListJISRacks(context.Background()).Id(id).RackStatus(rackStatus).RackSequenceNumber(rackSequenceNumber).MasterUnitNumber(masterUnitNumber).LineSequenceSetupName(lineSequenceSetupName).CreatedDateTimeStart(createdDateTimeStart).CreatedDateTimeEnd(createdDateTimeEnd).ReprintNeeded(reprintNeeded).PrintedDateTimeStart(printedDateTimeStart).PrintedDateTimeEnd(printedDateTimeEnd).TruckID(truckID).TruckNumber(truckNumber).TrailerNumber(trailerNumber).LabelPrintedDateTimeStart(labelPrintedDateTimeStart).LabelPrintedDateTimeEnd(labelPrintedDateTimeEnd).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JustInSequenceAPIAPI.JustInSequenceApiListJISRacks``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `JustInSequenceApiListJISRacks`: []JustInSequenceApiListJISRacksItem
	fmt.Fprintf(os.Stdout, "Response from `JustInSequenceAPIAPI.JustInSequenceApiListJISRacks`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiJustInSequenceApiListJISRacksRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **string** | A unique identifier for the sales order. This will be automatically generated if omitted from the request. | 
 **rackStatus** | **[]string** | The status of the rack. | 
 **rackSequenceNumber** | **string** | The rack sequence number. | 
 **masterUnitNumber** | **string** | The master unit number associated with the rack. | 
 **lineSequenceSetupName** | **string** | The rack&#39;s line sequence setup name. | 
 **createdDateTimeStart** | **time.Time** | The start date and time on which the rack was added. | 
 **createdDateTimeEnd** | **time.Time** | The end date and time on which the rack was added. | 
 **reprintNeeded** | **bool** | Determines whether the rack requires its paperwork to be reprinted. | 
 **printedDateTimeStart** | **time.Time** | The start date and time on which the rack paperwork was last printed. | 
 **printedDateTimeEnd** | **time.Time** | The end date and time on which the rack paperwork was last printed. | 
 **truckID** | **string** | The unique ID of the truck associated with the rack. | 
 **truckNumber** | **string** | The truck number associated with the rack. | 
 **trailerNumber** | **string** | The trailer number of the rack&#39;s associated truck. | 
 **labelPrintedDateTimeStart** | **time.Time** | The start date and time on which the rack label was last printed. | 
 **labelPrintedDateTimeEnd** | **time.Time** | The end date and time on which the rack label was last printed. | 

### Return type

[**[]JustInSequenceApiListJISRacksItem**](JustInSequenceApiListJISRacksItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## JustInSequenceApiListJISReleases

> []JustInSequenceApiListJISReleasesItem JustInSequenceApiListJISReleases(ctx).Id(id).SalesReleaseNumber(salesReleaseNumber).ReleaseStatus(releaseStatus).SalesReleaseId(salesReleaseId).KitId(kitId).KitName(kitName).CreatedDateTimeBegin(createdDateTimeBegin).CreatedDateTimeEnd(createdDateTimeEnd).Execute()

List JIS Releases



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
	id := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the sequenced release. (optional)
	salesReleaseNumber := "string" // string | The release number. (optional)
	releaseStatus := "string" // string | The status assigned to the sequenced release. (optional)
	salesReleaseId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the sales release. (optional)
	kitId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the kit. (optional)
	kitName := "string" // string | The kit name. (optional)
	createdDateTimeBegin := time.Now() // time.Time | The date and time on which the release was created. (optional)
	createdDateTimeEnd := time.Now() // time.Time | The date and time on which the release was created. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.JustInSequenceAPIAPI.JustInSequenceApiListJISReleases(context.Background()).Id(id).SalesReleaseNumber(salesReleaseNumber).ReleaseStatus(releaseStatus).SalesReleaseId(salesReleaseId).KitId(kitId).KitName(kitName).CreatedDateTimeBegin(createdDateTimeBegin).CreatedDateTimeEnd(createdDateTimeEnd).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JustInSequenceAPIAPI.JustInSequenceApiListJISReleases``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `JustInSequenceApiListJISReleases`: []JustInSequenceApiListJISReleasesItem
	fmt.Fprintf(os.Stdout, "Response from `JustInSequenceAPIAPI.JustInSequenceApiListJISReleases`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiJustInSequenceApiListJISReleasesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **string** | A unique identifier for the sequenced release. | 
 **salesReleaseNumber** | **string** | The release number. | 
 **releaseStatus** | **string** | The status assigned to the sequenced release. | 
 **salesReleaseId** | **string** | A unique identifier for the sales release. | 
 **kitId** | **string** | A unique identifier for the kit. | 
 **kitName** | **string** | The kit name. | 
 **createdDateTimeBegin** | **time.Time** | The date and time on which the release was created. | 
 **createdDateTimeEnd** | **time.Time** | The date and time on which the release was created. | 

### Return type

[**[]JustInSequenceApiListJISReleasesItem**](JustInSequenceApiListJISReleasesItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## JustInSequenceApiLoadJISRack

> JustInSequenceApiLoadJISRackResponse JustInSequenceApiLoadJISRack(ctx, id).JustInSequenceApiLoadJISRackRequest(justInSequenceApiLoadJISRackRequest).Execute()

Load JIS Rack



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
	id := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the sequenced rack.
	justInSequenceApiLoadJISRackRequest := *openapiclient.NewJustInSequenceApiLoadJISRackRequest() // JustInSequenceApiLoadJISRackRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.JustInSequenceAPIAPI.JustInSequenceApiLoadJISRack(context.Background(), id).JustInSequenceApiLoadJISRackRequest(justInSequenceApiLoadJISRackRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JustInSequenceAPIAPI.JustInSequenceApiLoadJISRack``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `JustInSequenceApiLoadJISRack`: JustInSequenceApiLoadJISRackResponse
	fmt.Fprintf(os.Stdout, "Response from `JustInSequenceAPIAPI.JustInSequenceApiLoadJISRack`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | A unique identifier for the sequenced rack. | 

### Other Parameters

Other parameters are passed through a pointer to a apiJustInSequenceApiLoadJISRackRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **justInSequenceApiLoadJISRackRequest** | [**JustInSequenceApiLoadJISRackRequest**](JustInSequenceApiLoadJISRackRequest.md) |  | 

### Return type

[**JustInSequenceApiLoadJISRackResponse**](JustInSequenceApiLoadJISRackResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## JustInSequenceApiPackJISKitByModule

> JustInSequenceApiPackJISKitByModule201Response JustInSequenceApiPackJISKitByModule(ctx, id).JustInSequenceApiPackJISKitByModuleRequest(justInSequenceApiPackJISKitByModuleRequest).Execute()

Pack JIS Kit By Module



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
	id := "00000000-0000-0000-0000-000000000000" // string | Kit ID.
	justInSequenceApiPackJISKitByModuleRequest := *openapiclient.NewJustInSequenceApiPackJISKitByModuleRequest() // JustInSequenceApiPackJISKitByModuleRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.JustInSequenceAPIAPI.JustInSequenceApiPackJISKitByModule(context.Background(), id).JustInSequenceApiPackJISKitByModuleRequest(justInSequenceApiPackJISKitByModuleRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JustInSequenceAPIAPI.JustInSequenceApiPackJISKitByModule``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `JustInSequenceApiPackJISKitByModule`: JustInSequenceApiPackJISKitByModule201Response
	fmt.Fprintf(os.Stdout, "Response from `JustInSequenceAPIAPI.JustInSequenceApiPackJISKitByModule`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Kit ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiJustInSequenceApiPackJISKitByModuleRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **justInSequenceApiPackJISKitByModuleRequest** | [**JustInSequenceApiPackJISKitByModuleRequest**](JustInSequenceApiPackJISKitByModuleRequest.md) |  | 

### Return type

[**JustInSequenceApiPackJISKitByModule201Response**](JustInSequenceApiPackJISKitByModule201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## JustInSequenceApiPackJISRackByFIFO

> JustInSequenceApiPackJISRackByFIFOResponse JustInSequenceApiPackJISRackByFIFO(ctx, id).Execute()

Pack JIS Rack By FIFO



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
	id := "00000000-0000-0000-0000-000000000000" // string | The ID of the sequenced rack.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.JustInSequenceAPIAPI.JustInSequenceApiPackJISRackByFIFO(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JustInSequenceAPIAPI.JustInSequenceApiPackJISRackByFIFO``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `JustInSequenceApiPackJISRackByFIFO`: JustInSequenceApiPackJISRackByFIFOResponse
	fmt.Fprintf(os.Stdout, "Response from `JustInSequenceAPIAPI.JustInSequenceApiPackJISRackByFIFO`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The ID of the sequenced rack. | 

### Other Parameters

Other parameters are passed through a pointer to a apiJustInSequenceApiPackJISRackByFIFORequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**JustInSequenceApiPackJISRackByFIFOResponse**](JustInSequenceApiPackJISRackByFIFOResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## JustInSequenceApiPackJISRackByMasterUnit

> JustInSequenceApiPackJISRackByMasterUnitResponse JustInSequenceApiPackJISRackByMasterUnit(ctx, id).JustInSequenceApiPackJISRackByMasterUnitRequest(justInSequenceApiPackJISRackByMasterUnitRequest).Execute()

Pack JIS Rack By Master Unit



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
	id := "00000000-0000-0000-0000-000000000000" // string | The ID of the sequenced rack.
	justInSequenceApiPackJISRackByMasterUnitRequest := *openapiclient.NewJustInSequenceApiPackJISRackByMasterUnitRequest() // JustInSequenceApiPackJISRackByMasterUnitRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.JustInSequenceAPIAPI.JustInSequenceApiPackJISRackByMasterUnit(context.Background(), id).JustInSequenceApiPackJISRackByMasterUnitRequest(justInSequenceApiPackJISRackByMasterUnitRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JustInSequenceAPIAPI.JustInSequenceApiPackJISRackByMasterUnit``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `JustInSequenceApiPackJISRackByMasterUnit`: JustInSequenceApiPackJISRackByMasterUnitResponse
	fmt.Fprintf(os.Stdout, "Response from `JustInSequenceAPIAPI.JustInSequenceApiPackJISRackByMasterUnit`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The ID of the sequenced rack. | 

### Other Parameters

Other parameters are passed through a pointer to a apiJustInSequenceApiPackJISRackByMasterUnitRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **justInSequenceApiPackJISRackByMasterUnitRequest** | [**JustInSequenceApiPackJISRackByMasterUnitRequest**](JustInSequenceApiPackJISRackByMasterUnitRequest.md) |  | 

### Return type

[**JustInSequenceApiPackJISRackByMasterUnitResponse**](JustInSequenceApiPackJISRackByMasterUnitResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## JustInSequenceApiPackJISReleaseByContainer

> JustInSequenceApiPackJISReleaseByContainerResponse JustInSequenceApiPackJISReleaseByContainer(ctx, id).JustInSequenceApiPackJISReleaseByContainerRequest(justInSequenceApiPackJISReleaseByContainerRequest).Execute()

Pack JIS Release By Container



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
	id := "00000000-0000-0000-0000-000000000000" // string | The ID of the sequenced release.
	justInSequenceApiPackJISReleaseByContainerRequest := *openapiclient.NewJustInSequenceApiPackJISReleaseByContainerRequest() // JustInSequenceApiPackJISReleaseByContainerRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.JustInSequenceAPIAPI.JustInSequenceApiPackJISReleaseByContainer(context.Background(), id).JustInSequenceApiPackJISReleaseByContainerRequest(justInSequenceApiPackJISReleaseByContainerRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JustInSequenceAPIAPI.JustInSequenceApiPackJISReleaseByContainer``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `JustInSequenceApiPackJISReleaseByContainer`: JustInSequenceApiPackJISReleaseByContainerResponse
	fmt.Fprintf(os.Stdout, "Response from `JustInSequenceAPIAPI.JustInSequenceApiPackJISReleaseByContainer`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The ID of the sequenced release. | 

### Other Parameters

Other parameters are passed through a pointer to a apiJustInSequenceApiPackJISReleaseByContainerRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **justInSequenceApiPackJISReleaseByContainerRequest** | [**JustInSequenceApiPackJISReleaseByContainerRequest**](JustInSequenceApiPackJISReleaseByContainerRequest.md) |  | 

### Return type

[**JustInSequenceApiPackJISReleaseByContainerResponse**](JustInSequenceApiPackJISReleaseByContainerResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## JustInSequenceApiPackJISReleaseByFIFO

> JustInSequenceApiPackJISReleaseByFIFOResponse JustInSequenceApiPackJISReleaseByFIFO(ctx, id).Execute()

Pack JIS Release By FIFO



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
	id := "00000000-0000-0000-0000-000000000000" // string | The ID of the sequenced release.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.JustInSequenceAPIAPI.JustInSequenceApiPackJISReleaseByFIFO(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JustInSequenceAPIAPI.JustInSequenceApiPackJISReleaseByFIFO``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `JustInSequenceApiPackJISReleaseByFIFO`: JustInSequenceApiPackJISReleaseByFIFOResponse
	fmt.Fprintf(os.Stdout, "Response from `JustInSequenceAPIAPI.JustInSequenceApiPackJISReleaseByFIFO`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The ID of the sequenced release. | 

### Other Parameters

Other parameters are passed through a pointer to a apiJustInSequenceApiPackJISReleaseByFIFORequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**JustInSequenceApiPackJISReleaseByFIFOResponse**](JustInSequenceApiPackJISReleaseByFIFOResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

