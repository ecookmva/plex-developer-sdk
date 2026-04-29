# \ContactsAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ContactsApiCreateContact**](ContactsAPIAPI.md#ContactsApiCreateContact) | **Post** /mdm/v1/contacts | Create Contact
[**ContactsApiDeactivateContact**](ContactsAPIAPI.md#ContactsApiDeactivateContact) | **Post** /mdm/v1/contacts/{id}/deactivate | Deactivate Contact
[**ContactsApiDeleteContact**](ContactsAPIAPI.md#ContactsApiDeleteContact) | **Delete** /mdm/v1/contacts/{id} | Delete Contact
[**ContactsApiGetContact**](ContactsAPIAPI.md#ContactsApiGetContact) | **Get** /mdm/v1/contacts/{id} | Get Contact
[**ContactsApiListContacts**](ContactsAPIAPI.md#ContactsApiListContacts) | **Get** /mdm/v1/contacts | List Contacts
[**ContactsApiSyncContacts**](ContactsAPIAPI.md#ContactsApiSyncContacts) | **Post** /mdm/v1/contacts/sync | Sync Contacts
[**ContactsApiUpdateContact**](ContactsAPIAPI.md#ContactsApiUpdateContact) | **Put** /mdm/v1/contacts/{id} | Update Contact



## ContactsApiCreateContact

> ContactsApiCreateContact201Response ContactsApiCreateContact(ctx).ContactsApiCreateContactRequest(contactsApiCreateContactRequest).Execute()

Create Contact



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
	contactsApiCreateContactRequest := *openapiclient.NewContactsApiCreateContactRequest() // ContactsApiCreateContactRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ContactsAPIAPI.ContactsApiCreateContact(context.Background()).ContactsApiCreateContactRequest(contactsApiCreateContactRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ContactsAPIAPI.ContactsApiCreateContact``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ContactsApiCreateContact`: ContactsApiCreateContact201Response
	fmt.Fprintf(os.Stdout, "Response from `ContactsAPIAPI.ContactsApiCreateContact`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiContactsApiCreateContactRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **contactsApiCreateContactRequest** | [**ContactsApiCreateContactRequest**](ContactsApiCreateContactRequest.md) |  | 

### Return type

[**ContactsApiCreateContact201Response**](ContactsApiCreateContact201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ContactsApiDeactivateContact

> ContactsApiDeactivateContact(ctx, id).Execute()

Deactivate Contact



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
	r, err := apiClient.ContactsAPIAPI.ContactsApiDeactivateContact(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ContactsAPIAPI.ContactsApiDeactivateContact``: %v\n", err)
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

Other parameters are passed through a pointer to a apiContactsApiDeactivateContactRequest struct via the builder pattern


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


## ContactsApiDeleteContact

> ContactsApiDeleteContact(ctx, id).Execute()

Delete Contact



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
	r, err := apiClient.ContactsAPIAPI.ContactsApiDeleteContact(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ContactsAPIAPI.ContactsApiDeleteContact``: %v\n", err)
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

Other parameters are passed through a pointer to a apiContactsApiDeleteContactRequest struct via the builder pattern


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


## ContactsApiGetContact

> ContactsApiGetContactResponse ContactsApiGetContact(ctx, id).Execute()

Get Contact



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
	id := "00000000-0000-0000-0000-000000000000" // string | Contact Resource ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ContactsAPIAPI.ContactsApiGetContact(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ContactsAPIAPI.ContactsApiGetContact``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ContactsApiGetContact`: ContactsApiGetContactResponse
	fmt.Fprintf(os.Stdout, "Response from `ContactsAPIAPI.ContactsApiGetContact`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Contact Resource ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiContactsApiGetContactRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ContactsApiGetContactResponse**](ContactsApiGetContactResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ContactsApiListContacts

> []ContactsApiListContactsItem ContactsApiListContacts(ctx).Id(id).CustomerId(customerId).FirstName(firstName).LastName(lastName).CompanyName(companyName).Description(description).SupplierId(supplierId).Type_(type_).AssociatedWithId(associatedWithId).Execute()

List Contacts



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
	id := []string{"00000000-0000-0000-0000-000000000000"} // []string | A list of contact IDs. (optional)
	customerId := "00000000-0000-0000-0000-000000000000" // string |  (optional)
	firstName := "string" // string |  (optional)
	lastName := "string" // string |  (optional)
	companyName := "string" // string |  (optional)
	description := "string" // string |  (optional)
	supplierId := "00000000-0000-0000-0000-000000000000" // string |  (optional)
	type_ := "string" // string | Setup table: Contact Type. (optional)
	associatedWithId := "00000000-0000-0000-0000-000000000000" // string | IAM Account Id (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ContactsAPIAPI.ContactsApiListContacts(context.Background()).Id(id).CustomerId(customerId).FirstName(firstName).LastName(lastName).CompanyName(companyName).Description(description).SupplierId(supplierId).Type_(type_).AssociatedWithId(associatedWithId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ContactsAPIAPI.ContactsApiListContacts``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ContactsApiListContacts`: []ContactsApiListContactsItem
	fmt.Fprintf(os.Stdout, "Response from `ContactsAPIAPI.ContactsApiListContacts`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiContactsApiListContactsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **[]string** | A list of contact IDs. | 
 **customerId** | **string** |  | 
 **firstName** | **string** |  | 
 **lastName** | **string** |  | 
 **companyName** | **string** |  | 
 **description** | **string** |  | 
 **supplierId** | **string** |  | 
 **type_** | **string** | Setup table: Contact Type. | 
 **associatedWithId** | **string** | IAM Account Id | 

### Return type

[**[]ContactsApiListContactsItem**](ContactsApiListContactsItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ContactsApiSyncContacts

> ContactsApiSyncContacts(ctx).ContactsApiSyncContactsRequest(contactsApiSyncContactsRequest).Execute()

Sync Contacts



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
	contactsApiSyncContactsRequest := *openapiclient.NewContactsApiSyncContactsRequest() // ContactsApiSyncContactsRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ContactsAPIAPI.ContactsApiSyncContacts(context.Background()).ContactsApiSyncContactsRequest(contactsApiSyncContactsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ContactsAPIAPI.ContactsApiSyncContacts``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiContactsApiSyncContactsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **contactsApiSyncContactsRequest** | [**ContactsApiSyncContactsRequest**](ContactsApiSyncContactsRequest.md) |  | 

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


## ContactsApiUpdateContact

> ContactsApiUpdateContactResponse ContactsApiUpdateContact(ctx, id).ContactsApiUpdateContactRequest(contactsApiUpdateContactRequest).Execute()

Update Contact



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
	contactsApiUpdateContactRequest := *openapiclient.NewContactsApiUpdateContactRequest() // ContactsApiUpdateContactRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ContactsAPIAPI.ContactsApiUpdateContact(context.Background(), id).ContactsApiUpdateContactRequest(contactsApiUpdateContactRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ContactsAPIAPI.ContactsApiUpdateContact``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ContactsApiUpdateContact`: ContactsApiUpdateContactResponse
	fmt.Fprintf(os.Stdout, "Response from `ContactsAPIAPI.ContactsApiUpdateContact`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiContactsApiUpdateContactRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **contactsApiUpdateContactRequest** | [**ContactsApiUpdateContactRequest**](ContactsApiUpdateContactRequest.md) |  | 

### Return type

[**ContactsApiUpdateContactResponse**](ContactsApiUpdateContactResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

