# \EmployeesAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**EmployeesApiActivateEmployee**](EmployeesAPIAPI.md#EmployeesApiActivateEmployee) | **Post** /mdm/v1/employees/{id}/activate | Activate Employee
[**EmployeesApiCreateEmployee**](EmployeesAPIAPI.md#EmployeesApiCreateEmployee) | **Post** /mdm/v1/employees | Create Employee
[**EmployeesApiDeactivateEmployee**](EmployeesAPIAPI.md#EmployeesApiDeactivateEmployee) | **Post** /mdm/v1/employees/{id}/deactivate | Deactivate Employee
[**EmployeesApiGetEmployee**](EmployeesAPIAPI.md#EmployeesApiGetEmployee) | **Get** /mdm/v1/employees/{id} | Get Employee
[**EmployeesApiListEmployees**](EmployeesAPIAPI.md#EmployeesApiListEmployees) | **Get** /mdm/v1/employees | List Employees
[**EmployeesApiSyncEmployees**](EmployeesAPIAPI.md#EmployeesApiSyncEmployees) | **Post** /mdm/v1/employees/sync | Sync Employees
[**EmployeesApiTransferEmployee**](EmployeesAPIAPI.md#EmployeesApiTransferEmployee) | **Post** /mdm/v1/employees/{id}/transfer | Transfer Employee
[**EmployeesApiUpdateEmployee**](EmployeesAPIAPI.md#EmployeesApiUpdateEmployee) | **Put** /mdm/v1/employees/{id} | Update Employee



## EmployeesApiActivateEmployee

> EmployeesApiActivateEmployee(ctx, id).EmployeesApiActivateEmployeeRequest(employeesApiActivateEmployeeRequest).Execute()

Activate Employee



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
	employeesApiActivateEmployeeRequest := *openapiclient.NewEmployeesApiActivateEmployeeRequest() // EmployeesApiActivateEmployeeRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EmployeesAPIAPI.EmployeesApiActivateEmployee(context.Background(), id).EmployeesApiActivateEmployeeRequest(employeesApiActivateEmployeeRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EmployeesAPIAPI.EmployeesApiActivateEmployee``: %v\n", err)
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

Other parameters are passed through a pointer to a apiEmployeesApiActivateEmployeeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **employeesApiActivateEmployeeRequest** | [**EmployeesApiActivateEmployeeRequest**](EmployeesApiActivateEmployeeRequest.md) |  | 

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


## EmployeesApiCreateEmployee

> EmployeesApiCreateEmployee201Response EmployeesApiCreateEmployee(ctx).EmployeesApiCreateEmployeeRequest(employeesApiCreateEmployeeRequest).Execute()

Create Employee



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
	employeesApiCreateEmployeeRequest := *openapiclient.NewEmployeesApiCreateEmployeeRequest() // EmployeesApiCreateEmployeeRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EmployeesAPIAPI.EmployeesApiCreateEmployee(context.Background()).EmployeesApiCreateEmployeeRequest(employeesApiCreateEmployeeRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EmployeesAPIAPI.EmployeesApiCreateEmployee``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EmployeesApiCreateEmployee`: EmployeesApiCreateEmployee201Response
	fmt.Fprintf(os.Stdout, "Response from `EmployeesAPIAPI.EmployeesApiCreateEmployee`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiEmployeesApiCreateEmployeeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **employeesApiCreateEmployeeRequest** | [**EmployeesApiCreateEmployeeRequest**](EmployeesApiCreateEmployeeRequest.md) |  | 

### Return type

[**EmployeesApiCreateEmployee201Response**](EmployeesApiCreateEmployee201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EmployeesApiDeactivateEmployee

> EmployeesApiDeactivateEmployee(ctx, id).EmployeesApiDeactivateEmployeeRequest(employeesApiDeactivateEmployeeRequest).Execute()

Deactivate Employee



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
	employeesApiDeactivateEmployeeRequest := *openapiclient.NewEmployeesApiDeactivateEmployeeRequest() // EmployeesApiDeactivateEmployeeRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EmployeesAPIAPI.EmployeesApiDeactivateEmployee(context.Background(), id).EmployeesApiDeactivateEmployeeRequest(employeesApiDeactivateEmployeeRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EmployeesAPIAPI.EmployeesApiDeactivateEmployee``: %v\n", err)
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

Other parameters are passed through a pointer to a apiEmployeesApiDeactivateEmployeeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **employeesApiDeactivateEmployeeRequest** | [**EmployeesApiDeactivateEmployeeRequest**](EmployeesApiDeactivateEmployeeRequest.md) |  | 

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


## EmployeesApiGetEmployee

> EmployeesApiGetEmployeeResponse EmployeesApiGetEmployee(ctx, id).Execute()

Get Employee



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
	resp, r, err := apiClient.EmployeesAPIAPI.EmployeesApiGetEmployee(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EmployeesAPIAPI.EmployeesApiGetEmployee``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EmployeesApiGetEmployee`: EmployeesApiGetEmployeeResponse
	fmt.Fprintf(os.Stdout, "Response from `EmployeesAPIAPI.EmployeesApiGetEmployee`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiEmployeesApiGetEmployeeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**EmployeesApiGetEmployeeResponse**](EmployeesApiGetEmployeeResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EmployeesApiListEmployees

> []EmployeesApiListEmployeesItem EmployeesApiListEmployees(ctx).Id(id).BadgeNumber(badgeNumber).UserId(userId).FirstName(firstName).LastName(lastName).SupervisorId(supervisorId).Status(status).Position(position).Shift(shift).Building(building).Type_(type_).Department(department).Email(email).Execute()

List Employees



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
	id := []string{"00000000-0000-0000-0000-000000000000"} // []string | A list of unique identifiers for Employees. (optional)
	badgeNumber := "string" // string | Employee badge number as used in Plex. (optional)
	userId := "string" // string | The User ID as seen on Plex login screens. (optional)
	firstName := "string" // string |  (optional)
	lastName := "string" // string |  (optional)
	supervisorId := "00000000-0000-0000-0000-000000000000" // string | Refers to another Employee's ID within the same Enterprise. (optional)
	status := "string" // string | Setup Table: Employee Status (optional)
	position := "string" // string | Job title or position. Plex Classic Screen: Positions. Plex UX Screen: Employee Positions. (optional)
	shift := "string" // string | The Employee's default shift. Setup Table: Shift (optional)
	building := "string" // string | The Employee's default building. Screen: Buildings (optional)
	type_ := "string" // string | Typically full-time or part-time. Setup Table: Employee Type (optional)
	department := "string" // string | Setup Table: Department (optional)
	email := "string" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EmployeesAPIAPI.EmployeesApiListEmployees(context.Background()).Id(id).BadgeNumber(badgeNumber).UserId(userId).FirstName(firstName).LastName(lastName).SupervisorId(supervisorId).Status(status).Position(position).Shift(shift).Building(building).Type_(type_).Department(department).Email(email).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EmployeesAPIAPI.EmployeesApiListEmployees``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EmployeesApiListEmployees`: []EmployeesApiListEmployeesItem
	fmt.Fprintf(os.Stdout, "Response from `EmployeesAPIAPI.EmployeesApiListEmployees`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiEmployeesApiListEmployeesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **[]string** | A list of unique identifiers for Employees. | 
 **badgeNumber** | **string** | Employee badge number as used in Plex. | 
 **userId** | **string** | The User ID as seen on Plex login screens. | 
 **firstName** | **string** |  | 
 **lastName** | **string** |  | 
 **supervisorId** | **string** | Refers to another Employee&#39;s ID within the same Enterprise. | 
 **status** | **string** | Setup Table: Employee Status | 
 **position** | **string** | Job title or position. Plex Classic Screen: Positions. Plex UX Screen: Employee Positions. | 
 **shift** | **string** | The Employee&#39;s default shift. Setup Table: Shift | 
 **building** | **string** | The Employee&#39;s default building. Screen: Buildings | 
 **type_** | **string** | Typically full-time or part-time. Setup Table: Employee Type | 
 **department** | **string** | Setup Table: Department | 
 **email** | **string** |  | 

### Return type

[**[]EmployeesApiListEmployeesItem**](EmployeesApiListEmployeesItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EmployeesApiSyncEmployees

> EmployeesApiSyncEmployees(ctx).EmployeesApiSyncEmployeesRequest(employeesApiSyncEmployeesRequest).Execute()

Sync Employees



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
	employeesApiSyncEmployeesRequest := *openapiclient.NewEmployeesApiSyncEmployeesRequest() // EmployeesApiSyncEmployeesRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EmployeesAPIAPI.EmployeesApiSyncEmployees(context.Background()).EmployeesApiSyncEmployeesRequest(employeesApiSyncEmployeesRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EmployeesAPIAPI.EmployeesApiSyncEmployees``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiEmployeesApiSyncEmployeesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **employeesApiSyncEmployeesRequest** | [**EmployeesApiSyncEmployeesRequest**](EmployeesApiSyncEmployeesRequest.md) |  | 

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


## EmployeesApiTransferEmployee

> EmployeesApiTransferEmployee(ctx, id).EmployeesApiTransferEmployeeRequest(employeesApiTransferEmployeeRequest).Execute()

Transfer Employee



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
	employeesApiTransferEmployeeRequest := *openapiclient.NewEmployeesApiTransferEmployeeRequest() // EmployeesApiTransferEmployeeRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EmployeesAPIAPI.EmployeesApiTransferEmployee(context.Background(), id).EmployeesApiTransferEmployeeRequest(employeesApiTransferEmployeeRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EmployeesAPIAPI.EmployeesApiTransferEmployee``: %v\n", err)
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

Other parameters are passed through a pointer to a apiEmployeesApiTransferEmployeeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **employeesApiTransferEmployeeRequest** | [**EmployeesApiTransferEmployeeRequest**](EmployeesApiTransferEmployeeRequest.md) |  | 

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


## EmployeesApiUpdateEmployee

> EmployeesApiUpdateEmployeeResponse EmployeesApiUpdateEmployee(ctx, id).EmployeesApiUpdateEmployeeRequest(employeesApiUpdateEmployeeRequest).Execute()

Update Employee



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
	employeesApiUpdateEmployeeRequest := *openapiclient.NewEmployeesApiUpdateEmployeeRequest() // EmployeesApiUpdateEmployeeRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EmployeesAPIAPI.EmployeesApiUpdateEmployee(context.Background(), id).EmployeesApiUpdateEmployeeRequest(employeesApiUpdateEmployeeRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EmployeesAPIAPI.EmployeesApiUpdateEmployee``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EmployeesApiUpdateEmployee`: EmployeesApiUpdateEmployeeResponse
	fmt.Fprintf(os.Stdout, "Response from `EmployeesAPIAPI.EmployeesApiUpdateEmployee`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiEmployeesApiUpdateEmployeeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **employeesApiUpdateEmployeeRequest** | [**EmployeesApiUpdateEmployeeRequest**](EmployeesApiUpdateEmployeeRequest.md) |  | 

### Return type

[**EmployeesApiUpdateEmployeeResponse**](EmployeesApiUpdateEmployeeResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

