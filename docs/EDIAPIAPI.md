# \EDIAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**EdiApiClearLogLoadError**](EDIAPIAPI.md#EdiApiClearLogLoadError) | **Delete** /edi/v1/logs/{id}/load-error | Clear Log Load Error
[**EdiApiClearLogProblem**](EDIAPIAPI.md#EdiApiClearLogProblem) | **Delete** /edi/v1/logs/{id}/problem | Clear Log Problem
[**EdiApiCreateDocument**](EDIAPIAPI.md#EdiApiCreateDocument) | **Post** /edi/v1/documents/{id} | Create Document
[**EdiApiCreateLog**](EDIAPIAPI.md#EdiApiCreateLog) | **Post** /edi/v1/logs | Create Log
[**EdiApiCreateLogLoadError**](EDIAPIAPI.md#EdiApiCreateLogLoadError) | **Post** /edi/v1/logs/{id}/load-error | Create Log Load Error
[**EdiApiCreateLogProblem**](EDIAPIAPI.md#EdiApiCreateLogProblem) | **Post** /edi/v1/logs/{id}/problem | Create Log Problem
[**EdiApiCreateLogXMLRepresentation**](EDIAPIAPI.md#EdiApiCreateLogXMLRepresentation) | **Post** /edi/v1/logs/{id}/xml-representation-add | Create Log XML Representation
[**EdiApiCreateNotification**](EDIAPIAPI.md#EdiApiCreateNotification) | **Post** /edi/v1/notification | Create Notification
[**EdiApiCreateReleaseSnapshot**](EDIAPIAPI.md#EdiApiCreateReleaseSnapshot) | **Post** /edi/v1/logs/{id}/release-snapshot/{releaseId} | Create Release Snapshot
[**EdiApiDeleteReleaseSnapshot**](EDIAPIAPI.md#EdiApiDeleteReleaseSnapshot) | **Delete** /edi/v1/logs/{id}/release-snapshot/{releaseId} | Delete Release Snapshot
[**EdiApiDeleteReleaseSnapshots**](EDIAPIAPI.md#EdiApiDeleteReleaseSnapshots) | **Delete** /edi/v1/logs/{id}/release-snapshot | Delete Release Snapshots
[**EdiApiGetEDIDocument**](EDIAPIAPI.md#EdiApiGetEDIDocument) | **Get** /edi/v1/documents/{id} | Get EDI Document
[**EdiApiGetLoadErrorTypes**](EDIAPIAPI.md#EdiApiGetLoadErrorTypes) | **Get** /edi/v1/load-error-types | Get Load Error Types
[**EdiApiGetLog**](EDIAPIAPI.md#EdiApiGetLog) | **Get** /edi/v1/logs/{id} | Get Log
[**EdiApiGetLogStatuses**](EDIAPIAPI.md#EdiApiGetLogStatuses) | **Get** /edi/v1/log-statuses | Get Log Statuses
[**EdiApiGetLogs**](EDIAPIAPI.md#EdiApiGetLogs) | **Get** /edi/v1/logs | Get Logs
[**EdiApiGetMailbox**](EDIAPIAPI.md#EdiApiGetMailbox) | **Get** /edi/v1/mailboxes/{id} | Get Mailbox
[**EdiApiGetMailboxes**](EDIAPIAPI.md#EdiApiGetMailboxes) | **Get** /edi/v1/mailboxes | Get Mailboxes
[**EdiApiGetTransformedData**](EDIAPIAPI.md#EdiApiGetTransformedData) | **Get** /edi/v1/logs/{id}/raw | Get Transformed Data
[**EdiApiGetUnit**](EDIAPIAPI.md#EdiApiGetUnit) | **Get** /edi/v1/units/{id} | Get Unit
[**EdiApiGetUnits**](EDIAPIAPI.md#EdiApiGetUnits) | **Get** /edi/v1/units | Get Units
[**EdiApiGetWorkflowRunID**](EDIAPIAPI.md#EdiApiGetWorkflowRunID) | **Get** /edi/v1/logs/{id}/workflow-run | Get Workflow Run ID
[**EdiApiUpdateEDILogTrackingNo**](EDIAPIAPI.md#EdiApiUpdateEDILogTrackingNo) | **Put** /edi/v1/logs/{id}/tracking-no | Update EDI Log Tracking No
[**EdiApiUpdateInboundReceive**](EDIAPIAPI.md#EdiApiUpdateInboundReceive) | **Put** /edi/v1/logs/inbound-receive | Update Inbound Receive
[**EdiApiUpdateLogStatus**](EDIAPIAPI.md#EdiApiUpdateLogStatus) | **Put** /edi/v1/logs/{id}/log-status-update | Update Log Status
[**EdiApiUpdateTransformedData**](EDIAPIAPI.md#EdiApiUpdateTransformedData) | **Put** /edi/v1/logs/{id}/raw | Update Transformed Data
[**EdiApiUpdateWorkflowRunID**](EDIAPIAPI.md#EdiApiUpdateWorkflowRunID) | **Put** /edi/v1/logs/{id}/workflow-run | Update Workflow Run ID



## EdiApiClearLogLoadError

> EdiApiClearLogLoadError(ctx, id).Execute()

Clear Log Load Error



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
	id := "00000000-0000-0000-0000-000000000000" // string | The Log resource id.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EDIAPIAPI.EdiApiClearLogLoadError(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EDIAPIAPI.EdiApiClearLogLoadError``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The Log resource id. | 

### Other Parameters

Other parameters are passed through a pointer to a apiEdiApiClearLogLoadErrorRequest struct via the builder pattern


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


## EdiApiClearLogProblem

> EdiApiClearLogProblem(ctx, id).Execute()

Clear Log Problem



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
	id := "00000000-0000-0000-0000-000000000000" // string | The Log resource id.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EDIAPIAPI.EdiApiClearLogProblem(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EDIAPIAPI.EdiApiClearLogProblem``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The Log resource id. | 

### Other Parameters

Other parameters are passed through a pointer to a apiEdiApiClearLogProblemRequest struct via the builder pattern


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


## EdiApiCreateDocument

> EdiApiCreateDocument(ctx, id).EdiApiCreateDocumentRequest(ediApiCreateDocumentRequest).Execute()

Create Document



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
	id := "00000000-0000-0000-0000-000000000000" // string | The id identifying the EDI log
	ediApiCreateDocumentRequest := *openapiclient.NewEdiApiCreateDocumentRequest() // EdiApiCreateDocumentRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EDIAPIAPI.EdiApiCreateDocument(context.Background(), id).EdiApiCreateDocumentRequest(ediApiCreateDocumentRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EDIAPIAPI.EdiApiCreateDocument``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The id identifying the EDI log | 

### Other Parameters

Other parameters are passed through a pointer to a apiEdiApiCreateDocumentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **ediApiCreateDocumentRequest** | [**EdiApiCreateDocumentRequest**](EdiApiCreateDocumentRequest.md) |  | 

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


## EdiApiCreateLog

> EdiApiCreateLog201Response EdiApiCreateLog(ctx).EdiApiCreateLogRequest(ediApiCreateLogRequest).Execute()

Create Log



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
	ediApiCreateLogRequest := *openapiclient.NewEdiApiCreateLogRequest() // EdiApiCreateLogRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EDIAPIAPI.EdiApiCreateLog(context.Background()).EdiApiCreateLogRequest(ediApiCreateLogRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EDIAPIAPI.EdiApiCreateLog``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EdiApiCreateLog`: EdiApiCreateLog201Response
	fmt.Fprintf(os.Stdout, "Response from `EDIAPIAPI.EdiApiCreateLog`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiEdiApiCreateLogRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ediApiCreateLogRequest** | [**EdiApiCreateLogRequest**](EdiApiCreateLogRequest.md) |  | 

### Return type

[**EdiApiCreateLog201Response**](EdiApiCreateLog201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EdiApiCreateLogLoadError

> EdiApiCreateLogLoadError(ctx, id).EdiApiCreateLogLoadErrorRequest(ediApiCreateLogLoadErrorRequest).Execute()

Create Log Load Error



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
	id := "00000000-0000-0000-0000-000000000000" // string | The Log resource id.
	ediApiCreateLogLoadErrorRequest := *openapiclient.NewEdiApiCreateLogLoadErrorRequest() // EdiApiCreateLogLoadErrorRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EDIAPIAPI.EdiApiCreateLogLoadError(context.Background(), id).EdiApiCreateLogLoadErrorRequest(ediApiCreateLogLoadErrorRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EDIAPIAPI.EdiApiCreateLogLoadError``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The Log resource id. | 

### Other Parameters

Other parameters are passed through a pointer to a apiEdiApiCreateLogLoadErrorRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **ediApiCreateLogLoadErrorRequest** | [**EdiApiCreateLogLoadErrorRequest**](EdiApiCreateLogLoadErrorRequest.md) |  | 

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


## EdiApiCreateLogProblem

> EdiApiCreateLogProblem(ctx, id).EdiApiCreateLogProblemRequest(ediApiCreateLogProblemRequest).Execute()

Create Log Problem



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
	id := "00000000-0000-0000-0000-000000000000" // string | The Log resource id.
	ediApiCreateLogProblemRequest := *openapiclient.NewEdiApiCreateLogProblemRequest() // EdiApiCreateLogProblemRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EDIAPIAPI.EdiApiCreateLogProblem(context.Background(), id).EdiApiCreateLogProblemRequest(ediApiCreateLogProblemRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EDIAPIAPI.EdiApiCreateLogProblem``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The Log resource id. | 

### Other Parameters

Other parameters are passed through a pointer to a apiEdiApiCreateLogProblemRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **ediApiCreateLogProblemRequest** | [**EdiApiCreateLogProblemRequest**](EdiApiCreateLogProblemRequest.md) |  | 

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


## EdiApiCreateLogXMLRepresentation

> EdiApiCreateLogXMLRepresentation(ctx, id).EdiApiCreateLogXMLRepresentationRequest(ediApiCreateLogXMLRepresentationRequest).Execute()

Create Log XML Representation



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
	id := "00000000-0000-0000-0000-000000000000" // string | The Log resource id.
	ediApiCreateLogXMLRepresentationRequest := *openapiclient.NewEdiApiCreateLogXMLRepresentationRequest() // EdiApiCreateLogXMLRepresentationRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EDIAPIAPI.EdiApiCreateLogXMLRepresentation(context.Background(), id).EdiApiCreateLogXMLRepresentationRequest(ediApiCreateLogXMLRepresentationRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EDIAPIAPI.EdiApiCreateLogXMLRepresentation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The Log resource id. | 

### Other Parameters

Other parameters are passed through a pointer to a apiEdiApiCreateLogXMLRepresentationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **ediApiCreateLogXMLRepresentationRequest** | [**EdiApiCreateLogXMLRepresentationRequest**](EdiApiCreateLogXMLRepresentationRequest.md) |  | 

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


## EdiApiCreateNotification

> EdiApiCreateNotification(ctx).EdiApiCreateNotificationRequest(ediApiCreateNotificationRequest).Execute()

Create Notification



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
	ediApiCreateNotificationRequest := *openapiclient.NewEdiApiCreateNotificationRequest() // EdiApiCreateNotificationRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EDIAPIAPI.EdiApiCreateNotification(context.Background()).EdiApiCreateNotificationRequest(ediApiCreateNotificationRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EDIAPIAPI.EdiApiCreateNotification``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiEdiApiCreateNotificationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ediApiCreateNotificationRequest** | [**EdiApiCreateNotificationRequest**](EdiApiCreateNotificationRequest.md) |  | 

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


## EdiApiCreateReleaseSnapshot

> EdiApiCreateReleaseSnapshot(ctx, id, releaseId).EdiApiCreateReleaseSnapshotRequest(ediApiCreateReleaseSnapshotRequest).Execute()

Create Release Snapshot



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
	id := "00000000-0000-0000-0000-000000000000" // string | The Log resource id.
	releaseId := "00000000-0000-0000-0000-000000000000" // string | The Release resource id.
	ediApiCreateReleaseSnapshotRequest := *openapiclient.NewEdiApiCreateReleaseSnapshotRequest() // EdiApiCreateReleaseSnapshotRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EDIAPIAPI.EdiApiCreateReleaseSnapshot(context.Background(), id, releaseId).EdiApiCreateReleaseSnapshotRequest(ediApiCreateReleaseSnapshotRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EDIAPIAPI.EdiApiCreateReleaseSnapshot``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The Log resource id. | 
**releaseId** | **string** | The Release resource id. | 

### Other Parameters

Other parameters are passed through a pointer to a apiEdiApiCreateReleaseSnapshotRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **ediApiCreateReleaseSnapshotRequest** | [**EdiApiCreateReleaseSnapshotRequest**](EdiApiCreateReleaseSnapshotRequest.md) |  | 

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


## EdiApiDeleteReleaseSnapshot

> EdiApiDeleteReleaseSnapshot(ctx, id, releaseId).Execute()

Delete Release Snapshot



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
	id := "00000000-0000-0000-0000-000000000000" // string | The Log resource id.
	releaseId := "00000000-0000-0000-0000-000000000000" // string | The Release resource id.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EDIAPIAPI.EdiApiDeleteReleaseSnapshot(context.Background(), id, releaseId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EDIAPIAPI.EdiApiDeleteReleaseSnapshot``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The Log resource id. | 
**releaseId** | **string** | The Release resource id. | 

### Other Parameters

Other parameters are passed through a pointer to a apiEdiApiDeleteReleaseSnapshotRequest struct via the builder pattern


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


## EdiApiDeleteReleaseSnapshots

> EdiApiDeleteReleaseSnapshots(ctx, id).Execute()

Delete Release Snapshots



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
	id := "00000000-0000-0000-0000-000000000000" // string | The Log resource id.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EDIAPIAPI.EdiApiDeleteReleaseSnapshots(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EDIAPIAPI.EdiApiDeleteReleaseSnapshots``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The Log resource id. | 

### Other Parameters

Other parameters are passed through a pointer to a apiEdiApiDeleteReleaseSnapshotsRequest struct via the builder pattern


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


## EdiApiGetEDIDocument

> EdiApiGetEDIDocumentResponse EdiApiGetEDIDocument(ctx, id).Execute()

Get EDI Document



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
	id := "00000000-0000-0000-0000-000000000000" // string | The Log resource id.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EDIAPIAPI.EdiApiGetEDIDocument(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EDIAPIAPI.EdiApiGetEDIDocument``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EdiApiGetEDIDocument`: EdiApiGetEDIDocumentResponse
	fmt.Fprintf(os.Stdout, "Response from `EDIAPIAPI.EdiApiGetEDIDocument`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The Log resource id. | 

### Other Parameters

Other parameters are passed through a pointer to a apiEdiApiGetEDIDocumentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**EdiApiGetEDIDocumentResponse**](EdiApiGetEDIDocumentResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EdiApiGetLoadErrorTypes

> []EdiApiGetLoadErrorTypesItem EdiApiGetLoadErrorTypes(ctx).Description(description).Execute()

Get Load Error Types



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
	description := "string" // string | The Load Error Type Description. Must be a unique value. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EDIAPIAPI.EdiApiGetLoadErrorTypes(context.Background()).Description(description).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EDIAPIAPI.EdiApiGetLoadErrorTypes``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EdiApiGetLoadErrorTypes`: []EdiApiGetLoadErrorTypesItem
	fmt.Fprintf(os.Stdout, "Response from `EDIAPIAPI.EdiApiGetLoadErrorTypes`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiEdiApiGetLoadErrorTypesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **description** | **string** | The Load Error Type Description. Must be a unique value. | 

### Return type

[**[]EdiApiGetLoadErrorTypesItem**](EdiApiGetLoadErrorTypesItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EdiApiGetLog

> EdiApiGetLogResponse EdiApiGetLog(ctx, id).Execute()

Get Log



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
	id := "00000000-0000-0000-0000-000000000000" // string | The Log resource id.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EDIAPIAPI.EdiApiGetLog(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EDIAPIAPI.EdiApiGetLog``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EdiApiGetLog`: EdiApiGetLogResponse
	fmt.Fprintf(os.Stdout, "Response from `EDIAPIAPI.EdiApiGetLog`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The Log resource id. | 

### Other Parameters

Other parameters are passed through a pointer to a apiEdiApiGetLogRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**EdiApiGetLogResponse**](EdiApiGetLogResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EdiApiGetLogStatuses

> []EdiApiGetLogStatusesItem EdiApiGetLogStatuses(ctx).Execute()

Get Log Statuses



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EDIAPIAPI.EdiApiGetLogStatuses(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EDIAPIAPI.EdiApiGetLogStatuses``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EdiApiGetLogStatuses`: []EdiApiGetLogStatusesItem
	fmt.Fprintf(os.Stdout, "Response from `EDIAPIAPI.EdiApiGetLogStatuses`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiEdiApiGetLogStatusesRequest struct via the builder pattern


### Return type

[**[]EdiApiGetLogStatusesItem**](EdiApiGetLogStatusesItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EdiApiGetLogs

> []EdiApiGetLogsItem EdiApiGetLogs(ctx).MailboxId(mailboxId).CustomerId(customerId).Action(action).Status(status).DocumentName(documentName).LogDateBegin(logDateBegin).LogDateEnd(logDateEnd).MailboxActive(mailboxActive).WorkflowName(workflowName).WorkflowType(workflowType).WorkflowActive(workflowActive).Execute()

Get Logs



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
	mailboxId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for a Mailbox. (optional)
	customerId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for a Customer. (optional)
	action := "string" // string | EDI Action. Must be a unique value. (optional)
	status := "string" // string | The Status of the EDI Log entry, supports a comma delimited list of desired statuses (optional)
	documentName := "string" // string | The Document Name. (optional)
	logDateBegin := time.Now() // time.Time | The start of the date range for filtering the log entries. (optional)
	logDateEnd := time.Now() // time.Time | The end of the date range for filtering the log entries. (optional)
	mailboxActive := false // bool | The Active flag of the EDI Mailbox. Set to true to return logs associated with active mailboxes, false for inactive mailboxes, and do not include the parameter to return active and inactive mailboxes. (optional)
	workflowName := "string" // string | The name of the workflow to filter on. (optional)
	workflowType := "string" // string | This Type of the Workflow. (optional)
	workflowActive := false // bool | The Active flag of the Workflow of the EDI Mailbox. Set to true to return logs associated with active workflows, false for inactive workflows, and do not include the parameter to return active and inactive workflows or logs that are not associated with a workflow. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EDIAPIAPI.EdiApiGetLogs(context.Background()).MailboxId(mailboxId).CustomerId(customerId).Action(action).Status(status).DocumentName(documentName).LogDateBegin(logDateBegin).LogDateEnd(logDateEnd).MailboxActive(mailboxActive).WorkflowName(workflowName).WorkflowType(workflowType).WorkflowActive(workflowActive).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EDIAPIAPI.EdiApiGetLogs``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EdiApiGetLogs`: []EdiApiGetLogsItem
	fmt.Fprintf(os.Stdout, "Response from `EDIAPIAPI.EdiApiGetLogs`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiEdiApiGetLogsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **mailboxId** | **string** | A unique identifier for a Mailbox. | 
 **customerId** | **string** | A unique identifier for a Customer. | 
 **action** | **string** | EDI Action. Must be a unique value. | 
 **status** | **string** | The Status of the EDI Log entry, supports a comma delimited list of desired statuses | 
 **documentName** | **string** | The Document Name. | 
 **logDateBegin** | **time.Time** | The start of the date range for filtering the log entries. | 
 **logDateEnd** | **time.Time** | The end of the date range for filtering the log entries. | 
 **mailboxActive** | **bool** | The Active flag of the EDI Mailbox. Set to true to return logs associated with active mailboxes, false for inactive mailboxes, and do not include the parameter to return active and inactive mailboxes. | 
 **workflowName** | **string** | The name of the workflow to filter on. | 
 **workflowType** | **string** | This Type of the Workflow. | 
 **workflowActive** | **bool** | The Active flag of the Workflow of the EDI Mailbox. Set to true to return logs associated with active workflows, false for inactive workflows, and do not include the parameter to return active and inactive workflows or logs that are not associated with a workflow. | 

### Return type

[**[]EdiApiGetLogsItem**](EdiApiGetLogsItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EdiApiGetMailbox

> EdiApiGetMailboxResponse EdiApiGetMailbox(ctx, id).Execute()

Get Mailbox



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
	id := "00000000-0000-0000-0000-000000000000" // string | The Log resource id.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EDIAPIAPI.EdiApiGetMailbox(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EDIAPIAPI.EdiApiGetMailbox``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EdiApiGetMailbox`: EdiApiGetMailboxResponse
	fmt.Fprintf(os.Stdout, "Response from `EDIAPIAPI.EdiApiGetMailbox`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The Log resource id. | 

### Other Parameters

Other parameters are passed through a pointer to a apiEdiApiGetMailboxRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**EdiApiGetMailboxResponse**](EdiApiGetMailboxResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EdiApiGetMailboxes

> []EdiApiGetMailboxesItem EdiApiGetMailboxes(ctx).Id(id).Name(name).Code(code).Active(active).DestinationMailbox(destinationMailbox).Execute()

Get Mailboxes



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
	id := []string{"00000000-0000-0000-0000-000000000000"} // []string | A list of unique identifiers for Mailboxes. (optional)
	name := "string" // string | EDI Mailbox Name. Must be a unique value. (optional)
	code := "string" // string | The User Code mapped to outbound documents. (optional)
	active := false // bool | This flag will be set to Active by default. (optional)
	destinationMailbox := "string" // string | The destination mailbox to filter on. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EDIAPIAPI.EdiApiGetMailboxes(context.Background()).Id(id).Name(name).Code(code).Active(active).DestinationMailbox(destinationMailbox).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EDIAPIAPI.EdiApiGetMailboxes``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EdiApiGetMailboxes`: []EdiApiGetMailboxesItem
	fmt.Fprintf(os.Stdout, "Response from `EDIAPIAPI.EdiApiGetMailboxes`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiEdiApiGetMailboxesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **[]string** | A list of unique identifiers for Mailboxes. | 
 **name** | **string** | EDI Mailbox Name. Must be a unique value. | 
 **code** | **string** | The User Code mapped to outbound documents. | 
 **active** | **bool** | This flag will be set to Active by default. | 
 **destinationMailbox** | **string** | The destination mailbox to filter on. | 

### Return type

[**[]EdiApiGetMailboxesItem**](EdiApiGetMailboxesItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EdiApiGetTransformedData

> EdiApiGetTransformedDataResponse EdiApiGetTransformedData(ctx, id).Execute()

Get Transformed Data



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
	id := "00000000-0000-0000-0000-000000000000" // string | The Log resource id.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EDIAPIAPI.EdiApiGetTransformedData(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EDIAPIAPI.EdiApiGetTransformedData``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EdiApiGetTransformedData`: EdiApiGetTransformedDataResponse
	fmt.Fprintf(os.Stdout, "Response from `EDIAPIAPI.EdiApiGetTransformedData`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The Log resource id. | 

### Other Parameters

Other parameters are passed through a pointer to a apiEdiApiGetTransformedDataRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**EdiApiGetTransformedDataResponse**](EdiApiGetTransformedDataResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EdiApiGetUnit

> EdiApiGetUnitResponse EdiApiGetUnit(ctx, id).Execute()

Get Unit



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
	resp, r, err := apiClient.EDIAPIAPI.EdiApiGetUnit(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EDIAPIAPI.EdiApiGetUnit``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EdiApiGetUnit`: EdiApiGetUnitResponse
	fmt.Fprintf(os.Stdout, "Response from `EDIAPIAPI.EdiApiGetUnit`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiEdiApiGetUnitRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**EdiApiGetUnitResponse**](EdiApiGetUnitResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EdiApiGetUnits

> []EdiApiGetUnitsItem EdiApiGetUnits(ctx).IdList(idList).Unit(unit).Execute()

Get Units



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
	idList := []string{"00000000-0000-0000-0000-000000000000"} // []string | A list of unit unique identifiers. (optional)
	unit := "string" // string | Unit. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EDIAPIAPI.EdiApiGetUnits(context.Background()).IdList(idList).Unit(unit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EDIAPIAPI.EdiApiGetUnits``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EdiApiGetUnits`: []EdiApiGetUnitsItem
	fmt.Fprintf(os.Stdout, "Response from `EDIAPIAPI.EdiApiGetUnits`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiEdiApiGetUnitsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **idList** | **[]string** | A list of unit unique identifiers. | 
 **unit** | **string** | Unit. | 

### Return type

[**[]EdiApiGetUnitsItem**](EdiApiGetUnitsItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EdiApiGetWorkflowRunID

> EdiApiGetWorkflowRunIDResponse EdiApiGetWorkflowRunID(ctx, id).Execute()

Get Workflow Run ID



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
	id := "00000000-0000-0000-0000-000000000000" // string | The Log resource id.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EDIAPIAPI.EdiApiGetWorkflowRunID(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EDIAPIAPI.EdiApiGetWorkflowRunID``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EdiApiGetWorkflowRunID`: EdiApiGetWorkflowRunIDResponse
	fmt.Fprintf(os.Stdout, "Response from `EDIAPIAPI.EdiApiGetWorkflowRunID`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The Log resource id. | 

### Other Parameters

Other parameters are passed through a pointer to a apiEdiApiGetWorkflowRunIDRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**EdiApiGetWorkflowRunIDResponse**](EdiApiGetWorkflowRunIDResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EdiApiUpdateEDILogTrackingNo

> EdiApiUpdateEDILogTrackingNo(ctx, id).EdiApiUpdateEDILogTrackingNoRequest(ediApiUpdateEDILogTrackingNoRequest).Execute()

Update EDI Log Tracking No



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
	id := "00000000-0000-0000-0000-000000000000" // string | The Log resource id.
	ediApiUpdateEDILogTrackingNoRequest := *openapiclient.NewEdiApiUpdateEDILogTrackingNoRequest() // EdiApiUpdateEDILogTrackingNoRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EDIAPIAPI.EdiApiUpdateEDILogTrackingNo(context.Background(), id).EdiApiUpdateEDILogTrackingNoRequest(ediApiUpdateEDILogTrackingNoRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EDIAPIAPI.EdiApiUpdateEDILogTrackingNo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The Log resource id. | 

### Other Parameters

Other parameters are passed through a pointer to a apiEdiApiUpdateEDILogTrackingNoRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **ediApiUpdateEDILogTrackingNoRequest** | [**EdiApiUpdateEDILogTrackingNoRequest**](EdiApiUpdateEDILogTrackingNoRequest.md) |  | 

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


## EdiApiUpdateInboundReceive

> EdiApiUpdateInboundReceive(ctx).EdiApiUpdateInboundReceiveRequest(ediApiUpdateInboundReceiveRequest).Execute()

Update Inbound Receive



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
	ediApiUpdateInboundReceiveRequest := *openapiclient.NewEdiApiUpdateInboundReceiveRequest() // EdiApiUpdateInboundReceiveRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EDIAPIAPI.EdiApiUpdateInboundReceive(context.Background()).EdiApiUpdateInboundReceiveRequest(ediApiUpdateInboundReceiveRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EDIAPIAPI.EdiApiUpdateInboundReceive``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiEdiApiUpdateInboundReceiveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ediApiUpdateInboundReceiveRequest** | [**EdiApiUpdateInboundReceiveRequest**](EdiApiUpdateInboundReceiveRequest.md) |  | 

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


## EdiApiUpdateLogStatus

> EdiApiUpdateLogStatus(ctx, id).EdiApiUpdateLogStatusRequest(ediApiUpdateLogStatusRequest).Execute()

Update Log Status



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
	id := "00000000-0000-0000-0000-000000000000" // string | The Log resource id.
	ediApiUpdateLogStatusRequest := *openapiclient.NewEdiApiUpdateLogStatusRequest() // EdiApiUpdateLogStatusRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EDIAPIAPI.EdiApiUpdateLogStatus(context.Background(), id).EdiApiUpdateLogStatusRequest(ediApiUpdateLogStatusRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EDIAPIAPI.EdiApiUpdateLogStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The Log resource id. | 

### Other Parameters

Other parameters are passed through a pointer to a apiEdiApiUpdateLogStatusRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **ediApiUpdateLogStatusRequest** | [**EdiApiUpdateLogStatusRequest**](EdiApiUpdateLogStatusRequest.md) |  | 

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


## EdiApiUpdateTransformedData

> EdiApiUpdateTransformedData(ctx, id).EdiApiUpdateTransformedDataRequest(ediApiUpdateTransformedDataRequest).Execute()

Update Transformed Data



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
	id := "00000000-0000-0000-0000-000000000000" // string | The resource id to the EDI Log
	ediApiUpdateTransformedDataRequest := *openapiclient.NewEdiApiUpdateTransformedDataRequest() // EdiApiUpdateTransformedDataRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EDIAPIAPI.EdiApiUpdateTransformedData(context.Background(), id).EdiApiUpdateTransformedDataRequest(ediApiUpdateTransformedDataRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EDIAPIAPI.EdiApiUpdateTransformedData``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The resource id to the EDI Log | 

### Other Parameters

Other parameters are passed through a pointer to a apiEdiApiUpdateTransformedDataRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **ediApiUpdateTransformedDataRequest** | [**EdiApiUpdateTransformedDataRequest**](EdiApiUpdateTransformedDataRequest.md) |  | 

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


## EdiApiUpdateWorkflowRunID

> EdiApiUpdateWorkflowRunID(ctx, id).EdiApiUpdateWorkflowRunIDRequest(ediApiUpdateWorkflowRunIDRequest).Execute()

Update Workflow Run ID



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
	id := "00000000-0000-0000-0000-000000000000" // string | The Log resource id.
	ediApiUpdateWorkflowRunIDRequest := *openapiclient.NewEdiApiUpdateWorkflowRunIDRequest() // EdiApiUpdateWorkflowRunIDRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EDIAPIAPI.EdiApiUpdateWorkflowRunID(context.Background(), id).EdiApiUpdateWorkflowRunIDRequest(ediApiUpdateWorkflowRunIDRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EDIAPIAPI.EdiApiUpdateWorkflowRunID``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The Log resource id. | 

### Other Parameters

Other parameters are passed through a pointer to a apiEdiApiUpdateWorkflowRunIDRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **ediApiUpdateWorkflowRunIDRequest** | [**EdiApiUpdateWorkflowRunIDRequest**](EdiApiUpdateWorkflowRunIDRequest.md) |  | 

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

