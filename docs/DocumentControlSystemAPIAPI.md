# \DocumentControlSystemAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**DocumentControlSystemApiCreateWebAttachment**](DocumentControlSystemAPIAPI.md#DocumentControlSystemApiCreateWebAttachment) | **Post** /platform/dcs/v1/attachments/{attachmentGroupId}/{recordId}/web-address | Create Web Attachment
[**DocumentControlSystemApiGetDocumentFile**](DocumentControlSystemAPIAPI.md#DocumentControlSystemApiGetDocumentFile) | **Get** /platform/dcs/v1/documents/{nodeNo}/file | Get Document File
[**DocumentControlSystemApiListAttachmentGroups**](DocumentControlSystemAPIAPI.md#DocumentControlSystemApiListAttachmentGroups) | **Get** /platform/dcs/v1/attachment-groups | List Attachment Groups
[**DocumentControlSystemApiListAttachments**](DocumentControlSystemAPIAPI.md#DocumentControlSystemApiListAttachments) | **Get** /platform/dcs/v1/attachments/{attachmentGroupId}/{recordId} | List Attachments



## DocumentControlSystemApiCreateWebAttachment

> []DocumentControlSystemApiCreateWebAttachmentItem DocumentControlSystemApiCreateWebAttachment(ctx, attachmentGroupId, recordId).DocumentControlSystemApiCreateWebAttachmentRequest(documentControlSystemApiCreateWebAttachmentRequest).Execute()

Create Web Attachment



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
	attachmentGroupId := "string" // string | The ID of an attachment group returned by the &quot;List Attachment Groups&quot; endpoint.
	recordId := "string" // string | The unique identifier of a record within the specified attachment group. The format of this input can be either an integer or uuid. See the API description for details.
	documentControlSystemApiCreateWebAttachmentRequest := *openapiclient.NewDocumentControlSystemApiCreateWebAttachmentRequest() // DocumentControlSystemApiCreateWebAttachmentRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DocumentControlSystemAPIAPI.DocumentControlSystemApiCreateWebAttachment(context.Background(), attachmentGroupId, recordId).DocumentControlSystemApiCreateWebAttachmentRequest(documentControlSystemApiCreateWebAttachmentRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DocumentControlSystemAPIAPI.DocumentControlSystemApiCreateWebAttachment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DocumentControlSystemApiCreateWebAttachment`: []DocumentControlSystemApiCreateWebAttachmentItem
	fmt.Fprintf(os.Stdout, "Response from `DocumentControlSystemAPIAPI.DocumentControlSystemApiCreateWebAttachment`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**attachmentGroupId** | **string** | The ID of an attachment group returned by the &amp;quot;List Attachment Groups&amp;quot; endpoint. | 
**recordId** | **string** | The unique identifier of a record within the specified attachment group. The format of this input can be either an integer or uuid. See the API description for details. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDocumentControlSystemApiCreateWebAttachmentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **documentControlSystemApiCreateWebAttachmentRequest** | [**DocumentControlSystemApiCreateWebAttachmentRequest**](DocumentControlSystemApiCreateWebAttachmentRequest.md) |  | 

### Return type

[**[]DocumentControlSystemApiCreateWebAttachmentItem**](DocumentControlSystemApiCreateWebAttachmentItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DocumentControlSystemApiGetDocumentFile

> DocumentControlSystemApiGetDocumentFile(ctx, nodeNo).Execute()

Get Document File



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
	nodeNo := int32(0) // int32 | A node number that represents a reference to a document. Note: multiple node numbers can point to the same document.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DocumentControlSystemAPIAPI.DocumentControlSystemApiGetDocumentFile(context.Background(), nodeNo).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DocumentControlSystemAPIAPI.DocumentControlSystemApiGetDocumentFile``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**nodeNo** | **int32** | A node number that represents a reference to a document. Note: multiple node numbers can point to the same document. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDocumentControlSystemApiGetDocumentFileRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DocumentControlSystemApiListAttachmentGroups

> []DocumentControlSystemApiListAttachmentGroupsItem DocumentControlSystemApiListAttachmentGroups(ctx).Execute()

List Attachment Groups



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
	resp, r, err := apiClient.DocumentControlSystemAPIAPI.DocumentControlSystemApiListAttachmentGroups(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DocumentControlSystemAPIAPI.DocumentControlSystemApiListAttachmentGroups``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DocumentControlSystemApiListAttachmentGroups`: []DocumentControlSystemApiListAttachmentGroupsItem
	fmt.Fprintf(os.Stdout, "Response from `DocumentControlSystemAPIAPI.DocumentControlSystemApiListAttachmentGroups`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiDocumentControlSystemApiListAttachmentGroupsRequest struct via the builder pattern


### Return type

[**[]DocumentControlSystemApiListAttachmentGroupsItem**](DocumentControlSystemApiListAttachmentGroupsItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DocumentControlSystemApiListAttachments

> []DocumentControlSystemApiListAttachmentsItem DocumentControlSystemApiListAttachments(ctx, attachmentGroupId, recordId).Execute()

List Attachments



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
	attachmentGroupId := "string" // string | The ID of an attachment group returned by the &quot;List Attachment Groups&quot; API.
	recordId := "string" // string | The unique identifier of a record within the specified attachment group. The format of this input can be either an integer or uuid. See the API description for details.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DocumentControlSystemAPIAPI.DocumentControlSystemApiListAttachments(context.Background(), attachmentGroupId, recordId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DocumentControlSystemAPIAPI.DocumentControlSystemApiListAttachments``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DocumentControlSystemApiListAttachments`: []DocumentControlSystemApiListAttachmentsItem
	fmt.Fprintf(os.Stdout, "Response from `DocumentControlSystemAPIAPI.DocumentControlSystemApiListAttachments`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**attachmentGroupId** | **string** | The ID of an attachment group returned by the &amp;quot;List Attachment Groups&amp;quot; API. | 
**recordId** | **string** | The unique identifier of a record within the specified attachment group. The format of this input can be either an integer or uuid. See the API description for details. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDocumentControlSystemApiListAttachmentsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**[]DocumentControlSystemApiListAttachmentsItem**](DocumentControlSystemApiListAttachmentsItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

