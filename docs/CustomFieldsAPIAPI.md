# \CustomFieldsAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CustomFieldsApiDeleteFieldValues**](CustomFieldsAPIAPI.md#CustomFieldsApiDeleteFieldValues) | **Post** /platform/custom-fields/v1/field-values/delete | Delete Field Values
[**CustomFieldsApiGetFieldDefinition**](CustomFieldsAPIAPI.md#CustomFieldsApiGetFieldDefinition) | **Get** /platform/custom-fields/v1/field-definitions/{fieldName} | Get Field Definition
[**CustomFieldsApiGetFieldType**](CustomFieldsAPIAPI.md#CustomFieldsApiGetFieldType) | **Get** /platform/custom-fields/v1/field-types/{fieldTypeName} | Get Field Type
[**CustomFieldsApiGetStandardObject**](CustomFieldsAPIAPI.md#CustomFieldsApiGetStandardObject) | **Get** /platform/custom-fields/v1/standard-objects/{standardObjectName} | Get Standard Object
[**CustomFieldsApiListFieldDefinitions**](CustomFieldsAPIAPI.md#CustomFieldsApiListFieldDefinitions) | **Get** /platform/custom-fields/v1/field-definitions | List Field Definitions
[**CustomFieldsApiListFieldTypes**](CustomFieldsAPIAPI.md#CustomFieldsApiListFieldTypes) | **Get** /platform/custom-fields/v1/field-types | List Field Types
[**CustomFieldsApiListStandardObjects**](CustomFieldsAPIAPI.md#CustomFieldsApiListStandardObjects) | **Get** /platform/custom-fields/v1/standard-objects | List Standard Objects
[**CustomFieldsApiSaveFieldValues**](CustomFieldsAPIAPI.md#CustomFieldsApiSaveFieldValues) | **Post** /platform/custom-fields/v1/field-values/save | Save Field Values
[**CustomFieldsApiSearchFieldValues**](CustomFieldsAPIAPI.md#CustomFieldsApiSearchFieldValues) | **Post** /platform/custom-fields/v1/field-values/search | Search Field Values
[**CustomFieldsApiValidateFieldValues**](CustomFieldsAPIAPI.md#CustomFieldsApiValidateFieldValues) | **Post** /platform/custom-fields/v1/field-values/validate | Validate Field Values



## CustomFieldsApiDeleteFieldValues

> CustomFieldsApiDeleteFieldValues(ctx).CustomFieldsApiDeleteFieldValuesRequest(customFieldsApiDeleteFieldValuesRequest).Execute()

Delete Field Values



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
	customFieldsApiDeleteFieldValuesRequest := *openapiclient.NewCustomFieldsApiDeleteFieldValuesRequest() // CustomFieldsApiDeleteFieldValuesRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.CustomFieldsAPIAPI.CustomFieldsApiDeleteFieldValues(context.Background()).CustomFieldsApiDeleteFieldValuesRequest(customFieldsApiDeleteFieldValuesRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomFieldsAPIAPI.CustomFieldsApiDeleteFieldValues``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCustomFieldsApiDeleteFieldValuesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **customFieldsApiDeleteFieldValuesRequest** | [**CustomFieldsApiDeleteFieldValuesRequest**](CustomFieldsApiDeleteFieldValuesRequest.md) |  | 

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


## CustomFieldsApiGetFieldDefinition

> []CustomFieldsApiGetFieldDefinitionItem CustomFieldsApiGetFieldDefinition(ctx, fieldName).Execute()

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
	fieldName := "string" // string | The name of the field definition that uniquely identifies the field within a standard object and is used internally by the system.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomFieldsAPIAPI.CustomFieldsApiGetFieldDefinition(context.Background(), fieldName).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomFieldsAPIAPI.CustomFieldsApiGetFieldDefinition``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomFieldsApiGetFieldDefinition`: []CustomFieldsApiGetFieldDefinitionItem
	fmt.Fprintf(os.Stdout, "Response from `CustomFieldsAPIAPI.CustomFieldsApiGetFieldDefinition`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**fieldName** | **string** | The name of the field definition that uniquely identifies the field within a standard object and is used internally by the system. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustomFieldsApiGetFieldDefinitionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]CustomFieldsApiGetFieldDefinitionItem**](CustomFieldsApiGetFieldDefinitionItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomFieldsApiGetFieldType

> CustomFieldsApiGetFieldTypeResponse CustomFieldsApiGetFieldType(ctx, fieldTypeName).Execute()

Get Field Type



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
	fieldTypeName := "string" // string | The name of the data type used internally by the system.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomFieldsAPIAPI.CustomFieldsApiGetFieldType(context.Background(), fieldTypeName).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomFieldsAPIAPI.CustomFieldsApiGetFieldType``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomFieldsApiGetFieldType`: CustomFieldsApiGetFieldTypeResponse
	fmt.Fprintf(os.Stdout, "Response from `CustomFieldsAPIAPI.CustomFieldsApiGetFieldType`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**fieldTypeName** | **string** | The name of the data type used internally by the system. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustomFieldsApiGetFieldTypeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**CustomFieldsApiGetFieldTypeResponse**](CustomFieldsApiGetFieldTypeResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomFieldsApiGetStandardObject

> CustomFieldsApiGetStandardObjectResponse CustomFieldsApiGetStandardObject(ctx, standardObjectName).Execute()

Get Standard Object



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
	standardObjectName := "string" // string | The name of the standard object that is used internally by the system.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomFieldsAPIAPI.CustomFieldsApiGetStandardObject(context.Background(), standardObjectName).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomFieldsAPIAPI.CustomFieldsApiGetStandardObject``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomFieldsApiGetStandardObject`: CustomFieldsApiGetStandardObjectResponse
	fmt.Fprintf(os.Stdout, "Response from `CustomFieldsAPIAPI.CustomFieldsApiGetStandardObject`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**standardObjectName** | **string** | The name of the standard object that is used internally by the system. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustomFieldsApiGetStandardObjectRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**CustomFieldsApiGetStandardObjectResponse**](CustomFieldsApiGetStandardObjectResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomFieldsApiListFieldDefinitions

> []CustomFieldsApiListFieldDefinitionsItem CustomFieldsApiListFieldDefinitions(ctx).FieldName(fieldName).FieldLabel(fieldLabel).StandardObjectName(standardObjectName).FieldTypeName(fieldTypeName).Execute()

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
	fieldName := "string" // string | The name of the field definition that uniquely identifies the field within a standard object and is used internally by the system. (optional)
	fieldLabel := "string" // string | The display name of the custom field that is used as a label on forms within Plex and on printed documents. (optional)
	standardObjectName := "string" // string | The name of the standard object that is used internally by the system. (optional)
	fieldTypeName := "string" // string | The name of the data type used internally by the system. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomFieldsAPIAPI.CustomFieldsApiListFieldDefinitions(context.Background()).FieldName(fieldName).FieldLabel(fieldLabel).StandardObjectName(standardObjectName).FieldTypeName(fieldTypeName).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomFieldsAPIAPI.CustomFieldsApiListFieldDefinitions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomFieldsApiListFieldDefinitions`: []CustomFieldsApiListFieldDefinitionsItem
	fmt.Fprintf(os.Stdout, "Response from `CustomFieldsAPIAPI.CustomFieldsApiListFieldDefinitions`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCustomFieldsApiListFieldDefinitionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **fieldName** | **string** | The name of the field definition that uniquely identifies the field within a standard object and is used internally by the system. | 
 **fieldLabel** | **string** | The display name of the custom field that is used as a label on forms within Plex and on printed documents. | 
 **standardObjectName** | **string** | The name of the standard object that is used internally by the system. | 
 **fieldTypeName** | **string** | The name of the data type used internally by the system. | 

### Return type

[**[]CustomFieldsApiListFieldDefinitionsItem**](CustomFieldsApiListFieldDefinitionsItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomFieldsApiListFieldTypes

> []CustomFieldsApiListFieldTypesItem CustomFieldsApiListFieldTypes(ctx).FieldTypeName(fieldTypeName).FieldTypeLabel(fieldTypeLabel).Execute()

List Field Types



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
	fieldTypeName := "string" // string | The name of the data type used internally by the system. (optional)
	fieldTypeLabel := "string" // string | The display name of the data type that is used as a label on forms within Plex. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomFieldsAPIAPI.CustomFieldsApiListFieldTypes(context.Background()).FieldTypeName(fieldTypeName).FieldTypeLabel(fieldTypeLabel).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomFieldsAPIAPI.CustomFieldsApiListFieldTypes``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomFieldsApiListFieldTypes`: []CustomFieldsApiListFieldTypesItem
	fmt.Fprintf(os.Stdout, "Response from `CustomFieldsAPIAPI.CustomFieldsApiListFieldTypes`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCustomFieldsApiListFieldTypesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **fieldTypeName** | **string** | The name of the data type used internally by the system. | 
 **fieldTypeLabel** | **string** | The display name of the data type that is used as a label on forms within Plex. | 

### Return type

[**[]CustomFieldsApiListFieldTypesItem**](CustomFieldsApiListFieldTypesItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomFieldsApiListStandardObjects

> []CustomFieldsApiListStandardObjectsItem CustomFieldsApiListStandardObjects(ctx).StandardObjectName(standardObjectName).StandardObjectLabel(standardObjectLabel).Execute()

List Standard Objects



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
	standardObjectName := "string" // string | The name of the standard object that is used internally by the system. (optional)
	standardObjectLabel := "string" // string | The display name of the standard object that is used on forms within Plex and on printed documents. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomFieldsAPIAPI.CustomFieldsApiListStandardObjects(context.Background()).StandardObjectName(standardObjectName).StandardObjectLabel(standardObjectLabel).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomFieldsAPIAPI.CustomFieldsApiListStandardObjects``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomFieldsApiListStandardObjects`: []CustomFieldsApiListStandardObjectsItem
	fmt.Fprintf(os.Stdout, "Response from `CustomFieldsAPIAPI.CustomFieldsApiListStandardObjects`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCustomFieldsApiListStandardObjectsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **standardObjectName** | **string** | The name of the standard object that is used internally by the system. | 
 **standardObjectLabel** | **string** | The display name of the standard object that is used on forms within Plex and on printed documents. | 

### Return type

[**[]CustomFieldsApiListStandardObjectsItem**](CustomFieldsApiListStandardObjectsItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomFieldsApiSaveFieldValues

> CustomFieldsApiSaveFieldValues(ctx).CustomFieldsApiSaveFieldValuesRequest(customFieldsApiSaveFieldValuesRequest).Execute()

Save Field Values



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
	customFieldsApiSaveFieldValuesRequest := *openapiclient.NewCustomFieldsApiSaveFieldValuesRequest() // CustomFieldsApiSaveFieldValuesRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.CustomFieldsAPIAPI.CustomFieldsApiSaveFieldValues(context.Background()).CustomFieldsApiSaveFieldValuesRequest(customFieldsApiSaveFieldValuesRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomFieldsAPIAPI.CustomFieldsApiSaveFieldValues``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCustomFieldsApiSaveFieldValuesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **customFieldsApiSaveFieldValuesRequest** | [**CustomFieldsApiSaveFieldValuesRequest**](CustomFieldsApiSaveFieldValuesRequest.md) |  | 

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


## CustomFieldsApiSearchFieldValues

> []CustomFieldsApiSearchFieldValuesItem CustomFieldsApiSearchFieldValues(ctx).CustomFieldsApiSearchFieldValuesRequest(customFieldsApiSearchFieldValuesRequest).Execute()

Search Field Values



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
	customFieldsApiSearchFieldValuesRequest := *openapiclient.NewCustomFieldsApiSearchFieldValuesRequest() // CustomFieldsApiSearchFieldValuesRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomFieldsAPIAPI.CustomFieldsApiSearchFieldValues(context.Background()).CustomFieldsApiSearchFieldValuesRequest(customFieldsApiSearchFieldValuesRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomFieldsAPIAPI.CustomFieldsApiSearchFieldValues``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomFieldsApiSearchFieldValues`: []CustomFieldsApiSearchFieldValuesItem
	fmt.Fprintf(os.Stdout, "Response from `CustomFieldsAPIAPI.CustomFieldsApiSearchFieldValues`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCustomFieldsApiSearchFieldValuesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **customFieldsApiSearchFieldValuesRequest** | [**CustomFieldsApiSearchFieldValuesRequest**](CustomFieldsApiSearchFieldValuesRequest.md) |  | 

### Return type

[**[]CustomFieldsApiSearchFieldValuesItem**](CustomFieldsApiSearchFieldValuesItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomFieldsApiValidateFieldValues

> CustomFieldsApiValidateFieldValues(ctx).CustomFieldsApiValidateFieldValuesRequest(customFieldsApiValidateFieldValuesRequest).Execute()

Validate Field Values



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
	customFieldsApiValidateFieldValuesRequest := *openapiclient.NewCustomFieldsApiValidateFieldValuesRequest() // CustomFieldsApiValidateFieldValuesRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.CustomFieldsAPIAPI.CustomFieldsApiValidateFieldValues(context.Background()).CustomFieldsApiValidateFieldValuesRequest(customFieldsApiValidateFieldValuesRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomFieldsAPIAPI.CustomFieldsApiValidateFieldValues``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCustomFieldsApiValidateFieldValuesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **customFieldsApiValidateFieldValuesRequest** | [**CustomFieldsApiValidateFieldValuesRequest**](CustomFieldsApiValidateFieldValuesRequest.md) |  | 

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

