# \CustomObjectsAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CustomObjectsApiCreateCustomObjectData**](CustomObjectsAPIAPI.md#CustomObjectsApiCreateCustomObjectData) | **Post** /platform/custom-objects/v1/data/{customObjectName} | Create Custom Object Data
[**CustomObjectsApiCreateCustomObjectDataInBulk**](CustomObjectsAPIAPI.md#CustomObjectsApiCreateCustomObjectDataInBulk) | **Post** /platform/custom-objects/v1/data/{customObjectName}/add | Create Custom Object Data In Bulk
[**CustomObjectsApiDeleteCustomObjectData**](CustomObjectsAPIAPI.md#CustomObjectsApiDeleteCustomObjectData) | **Delete** /platform/custom-objects/v1/data/{customObjectName}/{id} | Delete Custom Object Data
[**CustomObjectsApiDeleteCustomObjectDataInBulk**](CustomObjectsAPIAPI.md#CustomObjectsApiDeleteCustomObjectDataInBulk) | **Post** /platform/custom-objects/v1/data/{customObjectName}/delete | Delete Custom Object Data In Bulk
[**CustomObjectsApiGetCustomObjectData**](CustomObjectsAPIAPI.md#CustomObjectsApiGetCustomObjectData) | **Get** /platform/custom-objects/v1/data/{customObjectName}/{id} | Get Custom Object Data
[**CustomObjectsApiGetFieldDefinition**](CustomObjectsAPIAPI.md#CustomObjectsApiGetFieldDefinition) | **Get** /platform/custom-objects/v1/field-definitions/{customObjectName}/{fieldName} | Get Field Definition
[**CustomObjectsApiListAllCustomObjectData**](CustomObjectsAPIAPI.md#CustomObjectsApiListAllCustomObjectData) | **Get** /platform/custom-objects/v1/data/{customObjectName} | List All Custom Object Data
[**CustomObjectsApiListCustomObjectData**](CustomObjectsAPIAPI.md#CustomObjectsApiListCustomObjectData) | **Post** /platform/custom-objects/v1/data/{customObjectName}/search | List Custom Object Data
[**CustomObjectsApiListCustomObjects**](CustomObjectsAPIAPI.md#CustomObjectsApiListCustomObjects) | **Get** /platform/custom-objects/v1/objects | List Custom Objects
[**CustomObjectsApiListFieldDefinitions**](CustomObjectsAPIAPI.md#CustomObjectsApiListFieldDefinitions) | **Get** /platform/custom-objects/v1/field-definitions/{customObjectName} | List Field Definitions
[**CustomObjectsApiUpdateCustomObjectData**](CustomObjectsAPIAPI.md#CustomObjectsApiUpdateCustomObjectData) | **Put** /platform/custom-objects/v1/data/{customObjectName}/{id} | Update Custom Object Data
[**CustomObjectsApiUpdateCustomObjectDataInBulk**](CustomObjectsAPIAPI.md#CustomObjectsApiUpdateCustomObjectDataInBulk) | **Post** /platform/custom-objects/v1/data/{customObjectName}/update | Update Custom Object Data In Bulk



## CustomObjectsApiCreateCustomObjectData

> CustomObjectsApiCreateCustomObjectData201Response CustomObjectsApiCreateCustomObjectData(ctx, customObjectName).CustomObjectsApiCreateCustomObjectDataRequest(customObjectsApiCreateCustomObjectDataRequest).Execute()

Create Custom Object Data



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
	customObjectName := "string" // string | The name of the custom object.
	customObjectsApiCreateCustomObjectDataRequest := *openapiclient.NewCustomObjectsApiCreateCustomObjectDataRequest() // CustomObjectsApiCreateCustomObjectDataRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomObjectsAPIAPI.CustomObjectsApiCreateCustomObjectData(context.Background(), customObjectName).CustomObjectsApiCreateCustomObjectDataRequest(customObjectsApiCreateCustomObjectDataRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomObjectsAPIAPI.CustomObjectsApiCreateCustomObjectData``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomObjectsApiCreateCustomObjectData`: CustomObjectsApiCreateCustomObjectData201Response
	fmt.Fprintf(os.Stdout, "Response from `CustomObjectsAPIAPI.CustomObjectsApiCreateCustomObjectData`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**customObjectName** | **string** | The name of the custom object. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustomObjectsApiCreateCustomObjectDataRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **customObjectsApiCreateCustomObjectDataRequest** | [**CustomObjectsApiCreateCustomObjectDataRequest**](CustomObjectsApiCreateCustomObjectDataRequest.md) |  | 

### Return type

[**CustomObjectsApiCreateCustomObjectData201Response**](CustomObjectsApiCreateCustomObjectData201Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomObjectsApiCreateCustomObjectDataInBulk

> CustomObjectsApiCreateCustomObjectDataInBulk201Response CustomObjectsApiCreateCustomObjectDataInBulk(ctx, customObjectName).CustomObjectsApiCreateCustomObjectDataInBulkRequest(customObjectsApiCreateCustomObjectDataInBulkRequest).Execute()

Create Custom Object Data In Bulk



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
	customObjectName := "string" // string | The name of the custom object.
	customObjectsApiCreateCustomObjectDataInBulkRequest := *openapiclient.NewCustomObjectsApiCreateCustomObjectDataInBulkRequest() // CustomObjectsApiCreateCustomObjectDataInBulkRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomObjectsAPIAPI.CustomObjectsApiCreateCustomObjectDataInBulk(context.Background(), customObjectName).CustomObjectsApiCreateCustomObjectDataInBulkRequest(customObjectsApiCreateCustomObjectDataInBulkRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomObjectsAPIAPI.CustomObjectsApiCreateCustomObjectDataInBulk``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomObjectsApiCreateCustomObjectDataInBulk`: CustomObjectsApiCreateCustomObjectDataInBulk201Response
	fmt.Fprintf(os.Stdout, "Response from `CustomObjectsAPIAPI.CustomObjectsApiCreateCustomObjectDataInBulk`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**customObjectName** | **string** | The name of the custom object. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustomObjectsApiCreateCustomObjectDataInBulkRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **customObjectsApiCreateCustomObjectDataInBulkRequest** | [**CustomObjectsApiCreateCustomObjectDataInBulkRequest**](CustomObjectsApiCreateCustomObjectDataInBulkRequest.md) |  | 

### Return type

[**CustomObjectsApiCreateCustomObjectDataInBulk201Response**](CustomObjectsApiCreateCustomObjectDataInBulk201Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomObjectsApiDeleteCustomObjectData

> CustomObjectsApiDeleteCustomObjectDataResponse CustomObjectsApiDeleteCustomObjectData(ctx, customObjectName, id).Execute()

Delete Custom Object Data



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
	customObjectName := "string" // string | The name of the custom object.
	id := "00000000-0000-0000-0000-000000000000" // string | The ID of the record to delete.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomObjectsAPIAPI.CustomObjectsApiDeleteCustomObjectData(context.Background(), customObjectName, id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomObjectsAPIAPI.CustomObjectsApiDeleteCustomObjectData``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomObjectsApiDeleteCustomObjectData`: CustomObjectsApiDeleteCustomObjectDataResponse
	fmt.Fprintf(os.Stdout, "Response from `CustomObjectsAPIAPI.CustomObjectsApiDeleteCustomObjectData`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**customObjectName** | **string** | The name of the custom object. | 
**id** | **string** | The ID of the record to delete. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustomObjectsApiDeleteCustomObjectDataRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**CustomObjectsApiDeleteCustomObjectDataResponse**](CustomObjectsApiDeleteCustomObjectDataResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomObjectsApiDeleteCustomObjectDataInBulk

> CustomObjectsApiDeleteCustomObjectDataInBulkResponse CustomObjectsApiDeleteCustomObjectDataInBulk(ctx, customObjectName).Body(body).Execute()

Delete Custom Object Data In Bulk



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
	customObjectName := "string" // string | The name of the custom object.
	body := "body_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomObjectsAPIAPI.CustomObjectsApiDeleteCustomObjectDataInBulk(context.Background(), customObjectName).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomObjectsAPIAPI.CustomObjectsApiDeleteCustomObjectDataInBulk``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomObjectsApiDeleteCustomObjectDataInBulk`: CustomObjectsApiDeleteCustomObjectDataInBulkResponse
	fmt.Fprintf(os.Stdout, "Response from `CustomObjectsAPIAPI.CustomObjectsApiDeleteCustomObjectDataInBulk`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**customObjectName** | **string** | The name of the custom object. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustomObjectsApiDeleteCustomObjectDataInBulkRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **body** | **string** |  | 

### Return type

[**CustomObjectsApiDeleteCustomObjectDataInBulkResponse**](CustomObjectsApiDeleteCustomObjectDataInBulkResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomObjectsApiGetCustomObjectData

> CustomObjectsApiGetCustomObjectDataResponse CustomObjectsApiGetCustomObjectData(ctx, customObjectName, id).Execute()

Get Custom Object Data



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
	customObjectName := "string" // string | The name of the custom object.
	id := "00000000-0000-0000-0000-000000000000" // string | The ID of the record to look up.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomObjectsAPIAPI.CustomObjectsApiGetCustomObjectData(context.Background(), customObjectName, id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomObjectsAPIAPI.CustomObjectsApiGetCustomObjectData``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomObjectsApiGetCustomObjectData`: CustomObjectsApiGetCustomObjectDataResponse
	fmt.Fprintf(os.Stdout, "Response from `CustomObjectsAPIAPI.CustomObjectsApiGetCustomObjectData`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**customObjectName** | **string** | The name of the custom object. | 
**id** | **string** | The ID of the record to look up. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustomObjectsApiGetCustomObjectDataRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**CustomObjectsApiGetCustomObjectDataResponse**](CustomObjectsApiGetCustomObjectDataResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomObjectsApiGetFieldDefinition

> CustomObjectsApiGetFieldDefinitionResponse CustomObjectsApiGetFieldDefinition(ctx, customObjectName, fieldName).Execute()

Get Field Definition



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
	customObjectName := "string" // string | The name of the custom object.
	fieldName := "string" // string | The name of the field that uniquely identifies the field within a custom object and is used internally by the system.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomObjectsAPIAPI.CustomObjectsApiGetFieldDefinition(context.Background(), customObjectName, fieldName).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomObjectsAPIAPI.CustomObjectsApiGetFieldDefinition``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomObjectsApiGetFieldDefinition`: CustomObjectsApiGetFieldDefinitionResponse
	fmt.Fprintf(os.Stdout, "Response from `CustomObjectsAPIAPI.CustomObjectsApiGetFieldDefinition`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**customObjectName** | **string** | The name of the custom object. | 
**fieldName** | **string** | The name of the field that uniquely identifies the field within a custom object and is used internally by the system. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustomObjectsApiGetFieldDefinitionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**CustomObjectsApiGetFieldDefinitionResponse**](CustomObjectsApiGetFieldDefinitionResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomObjectsApiListAllCustomObjectData

> []CustomObjectsApiListAllCustomObjectDataItem CustomObjectsApiListAllCustomObjectData(ctx, customObjectName).Execute()

List All Custom Object Data



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
	customObjectName := "string" // string | The name of the custom object.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomObjectsAPIAPI.CustomObjectsApiListAllCustomObjectData(context.Background(), customObjectName).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomObjectsAPIAPI.CustomObjectsApiListAllCustomObjectData``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomObjectsApiListAllCustomObjectData`: []CustomObjectsApiListAllCustomObjectDataItem
	fmt.Fprintf(os.Stdout, "Response from `CustomObjectsAPIAPI.CustomObjectsApiListAllCustomObjectData`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**customObjectName** | **string** | The name of the custom object. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustomObjectsApiListAllCustomObjectDataRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]CustomObjectsApiListAllCustomObjectDataItem**](CustomObjectsApiListAllCustomObjectDataItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomObjectsApiListCustomObjectData

> []CustomObjectsApiListCustomObjectDataItem CustomObjectsApiListCustomObjectData(ctx, customObjectName).CustomObjectsApiListCustomObjectDataRequest(customObjectsApiListCustomObjectDataRequest).Execute()

List Custom Object Data



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
	customObjectName := "string" // string | The name of the custom object.
	customObjectsApiListCustomObjectDataRequest := *openapiclient.NewCustomObjectsApiListCustomObjectDataRequest() // CustomObjectsApiListCustomObjectDataRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomObjectsAPIAPI.CustomObjectsApiListCustomObjectData(context.Background(), customObjectName).CustomObjectsApiListCustomObjectDataRequest(customObjectsApiListCustomObjectDataRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomObjectsAPIAPI.CustomObjectsApiListCustomObjectData``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomObjectsApiListCustomObjectData`: []CustomObjectsApiListCustomObjectDataItem
	fmt.Fprintf(os.Stdout, "Response from `CustomObjectsAPIAPI.CustomObjectsApiListCustomObjectData`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**customObjectName** | **string** | The name of the custom object. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustomObjectsApiListCustomObjectDataRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **customObjectsApiListCustomObjectDataRequest** | [**CustomObjectsApiListCustomObjectDataRequest**](CustomObjectsApiListCustomObjectDataRequest.md) |  | 

### Return type

[**[]CustomObjectsApiListCustomObjectDataItem**](CustomObjectsApiListCustomObjectDataItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomObjectsApiListCustomObjects

> []CustomObjectsApiListCustomObjectsItem CustomObjectsApiListCustomObjects(ctx).CustomObjectName(customObjectName).Execute()

List Custom Objects



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
	customObjectName := "string" // string | The name of the custom object that is used internally by the system. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomObjectsAPIAPI.CustomObjectsApiListCustomObjects(context.Background()).CustomObjectName(customObjectName).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomObjectsAPIAPI.CustomObjectsApiListCustomObjects``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomObjectsApiListCustomObjects`: []CustomObjectsApiListCustomObjectsItem
	fmt.Fprintf(os.Stdout, "Response from `CustomObjectsAPIAPI.CustomObjectsApiListCustomObjects`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCustomObjectsApiListCustomObjectsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **customObjectName** | **string** | The name of the custom object that is used internally by the system. | 

### Return type

[**[]CustomObjectsApiListCustomObjectsItem**](CustomObjectsApiListCustomObjectsItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomObjectsApiListFieldDefinitions

> []CustomObjectsApiListFieldDefinitionsItem CustomObjectsApiListFieldDefinitions(ctx, customObjectName).Execute()

List Field Definitions



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
	customObjectName := "string" // string | The name of the custom object.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomObjectsAPIAPI.CustomObjectsApiListFieldDefinitions(context.Background(), customObjectName).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomObjectsAPIAPI.CustomObjectsApiListFieldDefinitions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomObjectsApiListFieldDefinitions`: []CustomObjectsApiListFieldDefinitionsItem
	fmt.Fprintf(os.Stdout, "Response from `CustomObjectsAPIAPI.CustomObjectsApiListFieldDefinitions`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**customObjectName** | **string** | The name of the custom object. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustomObjectsApiListFieldDefinitionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]CustomObjectsApiListFieldDefinitionsItem**](CustomObjectsApiListFieldDefinitionsItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomObjectsApiUpdateCustomObjectData

> CustomObjectsApiUpdateCustomObjectDataResponse CustomObjectsApiUpdateCustomObjectData(ctx, customObjectName, id).CustomObjectsApiUpdateCustomObjectDataRequest(customObjectsApiUpdateCustomObjectDataRequest).Execute()

Update Custom Object Data



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
	customObjectName := "string" // string | The name of the custom object.
	id := "00000000-0000-0000-0000-000000000000" // string | The ID of the record to update.
	customObjectsApiUpdateCustomObjectDataRequest := *openapiclient.NewCustomObjectsApiUpdateCustomObjectDataRequest() // CustomObjectsApiUpdateCustomObjectDataRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomObjectsAPIAPI.CustomObjectsApiUpdateCustomObjectData(context.Background(), customObjectName, id).CustomObjectsApiUpdateCustomObjectDataRequest(customObjectsApiUpdateCustomObjectDataRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomObjectsAPIAPI.CustomObjectsApiUpdateCustomObjectData``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomObjectsApiUpdateCustomObjectData`: CustomObjectsApiUpdateCustomObjectDataResponse
	fmt.Fprintf(os.Stdout, "Response from `CustomObjectsAPIAPI.CustomObjectsApiUpdateCustomObjectData`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**customObjectName** | **string** | The name of the custom object. | 
**id** | **string** | The ID of the record to update. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustomObjectsApiUpdateCustomObjectDataRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **customObjectsApiUpdateCustomObjectDataRequest** | [**CustomObjectsApiUpdateCustomObjectDataRequest**](CustomObjectsApiUpdateCustomObjectDataRequest.md) |  | 

### Return type

[**CustomObjectsApiUpdateCustomObjectDataResponse**](CustomObjectsApiUpdateCustomObjectDataResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomObjectsApiUpdateCustomObjectDataInBulk

> CustomObjectsApiUpdateCustomObjectDataInBulkResponse CustomObjectsApiUpdateCustomObjectDataInBulk(ctx, customObjectName).CustomObjectsApiUpdateCustomObjectDataInBulkRequest(customObjectsApiUpdateCustomObjectDataInBulkRequest).Execute()

Update Custom Object Data In Bulk



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
	customObjectName := "string" // string | The name of the custom object.
	customObjectsApiUpdateCustomObjectDataInBulkRequest := *openapiclient.NewCustomObjectsApiUpdateCustomObjectDataInBulkRequest() // CustomObjectsApiUpdateCustomObjectDataInBulkRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomObjectsAPIAPI.CustomObjectsApiUpdateCustomObjectDataInBulk(context.Background(), customObjectName).CustomObjectsApiUpdateCustomObjectDataInBulkRequest(customObjectsApiUpdateCustomObjectDataInBulkRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomObjectsAPIAPI.CustomObjectsApiUpdateCustomObjectDataInBulk``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomObjectsApiUpdateCustomObjectDataInBulk`: CustomObjectsApiUpdateCustomObjectDataInBulkResponse
	fmt.Fprintf(os.Stdout, "Response from `CustomObjectsAPIAPI.CustomObjectsApiUpdateCustomObjectDataInBulk`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**customObjectName** | **string** | The name of the custom object. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustomObjectsApiUpdateCustomObjectDataInBulkRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **customObjectsApiUpdateCustomObjectDataInBulkRequest** | [**CustomObjectsApiUpdateCustomObjectDataInBulkRequest**](CustomObjectsApiUpdateCustomObjectDataInBulkRequest.md) |  | 

### Return type

[**CustomObjectsApiUpdateCustomObjectDataInBulkResponse**](CustomObjectsApiUpdateCustomObjectDataInBulkResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

