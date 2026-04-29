# \DeviationsAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**DeviationsApiGetDeviation**](DeviationsAPIAPI.md#DeviationsApiGetDeviation) | **Get** /quality/v1/deviations/{id} | Get Deviation
[**DeviationsApiListDeviations**](DeviationsAPIAPI.md#DeviationsApiListDeviations) | **Get** /quality/v1/deviations | List Deviations



## DeviationsApiGetDeviation

> DeviationsApiGetDeviationResponse DeviationsApiGetDeviation(ctx, id).Execute()

Get Deviation



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
	resp, r, err := apiClient.DeviationsAPIAPI.DeviationsApiGetDeviation(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeviationsAPIAPI.DeviationsApiGetDeviation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeviationsApiGetDeviation`: DeviationsApiGetDeviationResponse
	fmt.Fprintf(os.Stdout, "Response from `DeviationsAPIAPI.DeviationsApiGetDeviation`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeviationsApiGetDeviationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**DeviationsApiGetDeviationResponse**](DeviationsApiGetDeviationResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeviationsApiListDeviations

> []DeviationsApiListDeviationsItem DeviationsApiListDeviations(ctx).Ids(ids).SpecificationId(specificationId).JobId(jobId).PartId(partId).DeviationStatus(deviationStatus).CurrentlyEffectiveOnly(currentlyEffectiveOnly).Execute()

List Deviations



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
	ids := []string{"00000000-0000-0000-0000-000000000000"} // []string | A list of IDs representing the Deviation. (optional)
	specificationId := "00000000-0000-0000-0000-000000000000" // string | ID representing a Specification. (optional)
	jobId := "00000000-0000-0000-0000-000000000000" // string | ID representing a Job. (optional)
	partId := "00000000-0000-0000-0000-000000000000" // string | ID representing a Part. (optional)
	deviationStatus := []string{"string"} // []string | The list of deviation status. (optional)
	currentlyEffectiveOnly := false // bool | If true, only the list of deviations with effective date less than or equal to today and an expiration date or is greater than today will be returned. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeviationsAPIAPI.DeviationsApiListDeviations(context.Background()).Ids(ids).SpecificationId(specificationId).JobId(jobId).PartId(partId).DeviationStatus(deviationStatus).CurrentlyEffectiveOnly(currentlyEffectiveOnly).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeviationsAPIAPI.DeviationsApiListDeviations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeviationsApiListDeviations`: []DeviationsApiListDeviationsItem
	fmt.Fprintf(os.Stdout, "Response from `DeviationsAPIAPI.DeviationsApiListDeviations`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiDeviationsApiListDeviationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ids** | **[]string** | A list of IDs representing the Deviation. | 
 **specificationId** | **string** | ID representing a Specification. | 
 **jobId** | **string** | ID representing a Job. | 
 **partId** | **string** | ID representing a Part. | 
 **deviationStatus** | **[]string** | The list of deviation status. | 
 **currentlyEffectiveOnly** | **bool** | If true, only the list of deviations with effective date less than or equal to today and an expiration date or is greater than today will be returned. | 

### Return type

[**[]DeviationsApiListDeviationsItem**](DeviationsApiListDeviationsItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

