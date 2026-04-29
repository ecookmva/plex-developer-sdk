# \KeyMeasurablesAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**KeyMeasurablesApiGetMetric**](KeyMeasurablesAPIAPI.md#KeyMeasurablesApiGetMetric) | **Get** /management/v1/metrics/{id} | Get Metric
[**KeyMeasurablesApiGetMetricData**](KeyMeasurablesAPIAPI.md#KeyMeasurablesApiGetMetricData) | **Get** /management/v1/metrics/{id}/data | Get Metric Data
[**KeyMeasurablesApiListDataSetDimensions**](KeyMeasurablesAPIAPI.md#KeyMeasurablesApiListDataSetDimensions) | **Get** /management/v1/data-sets/{id}/dimensions | List Data Set Dimensions
[**KeyMeasurablesApiListDataSetMeasures**](KeyMeasurablesAPIAPI.md#KeyMeasurablesApiListDataSetMeasures) | **Get** /management/v1/data-sets/{id}/measures | List Data Set Measures
[**KeyMeasurablesApiListDataSets**](KeyMeasurablesAPIAPI.md#KeyMeasurablesApiListDataSets) | **Get** /management/v1/data-sets | List Data Sets
[**KeyMeasurablesApiListMetricBenchmarks**](KeyMeasurablesAPIAPI.md#KeyMeasurablesApiListMetricBenchmarks) | **Get** /management/v1/metrics/{id}/benchmarks | List Metric Benchmarks
[**KeyMeasurablesApiListMetrics**](KeyMeasurablesAPIAPI.md#KeyMeasurablesApiListMetrics) | **Get** /management/v1/metrics | List Metrics
[**KeyMeasurablesApiUploadDataSetFile**](KeyMeasurablesAPIAPI.md#KeyMeasurablesApiUploadDataSetFile) | **Post** /management/v1/data-sets/{id}/upload-data | Upload Data Set File



## KeyMeasurablesApiGetMetric

> KeyMeasurablesApiGetMetricResponse KeyMeasurablesApiGetMetric(ctx, id).Execute()

Get Metric



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
	id := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the metric record.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.KeyMeasurablesAPIAPI.KeyMeasurablesApiGetMetric(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `KeyMeasurablesAPIAPI.KeyMeasurablesApiGetMetric``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `KeyMeasurablesApiGetMetric`: KeyMeasurablesApiGetMetricResponse
	fmt.Fprintf(os.Stdout, "Response from `KeyMeasurablesAPIAPI.KeyMeasurablesApiGetMetric`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | A unique identifier for the metric record. | 

### Other Parameters

Other parameters are passed through a pointer to a apiKeyMeasurablesApiGetMetricRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**KeyMeasurablesApiGetMetricResponse**](KeyMeasurablesApiGetMetricResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## KeyMeasurablesApiGetMetricData

> KeyMeasurablesApiGetMetricDataResponse KeyMeasurablesApiGetMetricData(ctx, id).Execute()

Get Metric Data



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
	id := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the metric record.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.KeyMeasurablesAPIAPI.KeyMeasurablesApiGetMetricData(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `KeyMeasurablesAPIAPI.KeyMeasurablesApiGetMetricData``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `KeyMeasurablesApiGetMetricData`: KeyMeasurablesApiGetMetricDataResponse
	fmt.Fprintf(os.Stdout, "Response from `KeyMeasurablesAPIAPI.KeyMeasurablesApiGetMetricData`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | A unique identifier for the metric record. | 

### Other Parameters

Other parameters are passed through a pointer to a apiKeyMeasurablesApiGetMetricDataRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**KeyMeasurablesApiGetMetricDataResponse**](KeyMeasurablesApiGetMetricDataResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## KeyMeasurablesApiListDataSetDimensions

> []KeyMeasurablesApiListDataSetDimensionsItem KeyMeasurablesApiListDataSetDimensions(ctx, id).Execute()

List Data Set Dimensions



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
	id := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the associated data set.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.KeyMeasurablesAPIAPI.KeyMeasurablesApiListDataSetDimensions(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `KeyMeasurablesAPIAPI.KeyMeasurablesApiListDataSetDimensions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `KeyMeasurablesApiListDataSetDimensions`: []KeyMeasurablesApiListDataSetDimensionsItem
	fmt.Fprintf(os.Stdout, "Response from `KeyMeasurablesAPIAPI.KeyMeasurablesApiListDataSetDimensions`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | A unique identifier for the associated data set. | 

### Other Parameters

Other parameters are passed through a pointer to a apiKeyMeasurablesApiListDataSetDimensionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]KeyMeasurablesApiListDataSetDimensionsItem**](KeyMeasurablesApiListDataSetDimensionsItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## KeyMeasurablesApiListDataSetMeasures

> []KeyMeasurablesApiListDataSetMeasuresItem KeyMeasurablesApiListDataSetMeasures(ctx, id).Execute()

List Data Set Measures



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
	id := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the data set record.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.KeyMeasurablesAPIAPI.KeyMeasurablesApiListDataSetMeasures(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `KeyMeasurablesAPIAPI.KeyMeasurablesApiListDataSetMeasures``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `KeyMeasurablesApiListDataSetMeasures`: []KeyMeasurablesApiListDataSetMeasuresItem
	fmt.Fprintf(os.Stdout, "Response from `KeyMeasurablesAPIAPI.KeyMeasurablesApiListDataSetMeasures`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | A unique identifier for the data set record. | 

### Other Parameters

Other parameters are passed through a pointer to a apiKeyMeasurablesApiListDataSetMeasuresRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]KeyMeasurablesApiListDataSetMeasuresItem**](KeyMeasurablesApiListDataSetMeasuresItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## KeyMeasurablesApiListDataSets

> []KeyMeasurablesApiListDataSetsItem KeyMeasurablesApiListDataSets(ctx).Execute()

List Data Sets



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
	resp, r, err := apiClient.KeyMeasurablesAPIAPI.KeyMeasurablesApiListDataSets(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `KeyMeasurablesAPIAPI.KeyMeasurablesApiListDataSets``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `KeyMeasurablesApiListDataSets`: []KeyMeasurablesApiListDataSetsItem
	fmt.Fprintf(os.Stdout, "Response from `KeyMeasurablesAPIAPI.KeyMeasurablesApiListDataSets`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiKeyMeasurablesApiListDataSetsRequest struct via the builder pattern


### Return type

[**[]KeyMeasurablesApiListDataSetsItem**](KeyMeasurablesApiListDataSetsItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## KeyMeasurablesApiListMetricBenchmarks

> []KeyMeasurablesApiListMetricBenchmarksItem KeyMeasurablesApiListMetricBenchmarks(ctx, id).Execute()

List Metric Benchmarks



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
	id := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the metric record.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.KeyMeasurablesAPIAPI.KeyMeasurablesApiListMetricBenchmarks(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `KeyMeasurablesAPIAPI.KeyMeasurablesApiListMetricBenchmarks``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `KeyMeasurablesApiListMetricBenchmarks`: []KeyMeasurablesApiListMetricBenchmarksItem
	fmt.Fprintf(os.Stdout, "Response from `KeyMeasurablesAPIAPI.KeyMeasurablesApiListMetricBenchmarks`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | A unique identifier for the metric record. | 

### Other Parameters

Other parameters are passed through a pointer to a apiKeyMeasurablesApiListMetricBenchmarksRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]KeyMeasurablesApiListMetricBenchmarksItem**](KeyMeasurablesApiListMetricBenchmarksItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## KeyMeasurablesApiListMetrics

> []KeyMeasurablesApiListMetricsItem KeyMeasurablesApiListMetrics(ctx).Execute()

List Metrics



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
	resp, r, err := apiClient.KeyMeasurablesAPIAPI.KeyMeasurablesApiListMetrics(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `KeyMeasurablesAPIAPI.KeyMeasurablesApiListMetrics``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `KeyMeasurablesApiListMetrics`: []KeyMeasurablesApiListMetricsItem
	fmt.Fprintf(os.Stdout, "Response from `KeyMeasurablesAPIAPI.KeyMeasurablesApiListMetrics`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiKeyMeasurablesApiListMetricsRequest struct via the builder pattern


### Return type

[**[]KeyMeasurablesApiListMetricsItem**](KeyMeasurablesApiListMetricsItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## KeyMeasurablesApiUploadDataSetFile

> KeyMeasurablesApiUploadDataSetFileResponse KeyMeasurablesApiUploadDataSetFile(ctx, id).Body(body).Execute()

Upload Data Set File



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
	id := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the data set.
	body := "body_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.KeyMeasurablesAPIAPI.KeyMeasurablesApiUploadDataSetFile(context.Background(), id).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `KeyMeasurablesAPIAPI.KeyMeasurablesApiUploadDataSetFile``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `KeyMeasurablesApiUploadDataSetFile`: KeyMeasurablesApiUploadDataSetFileResponse
	fmt.Fprintf(os.Stdout, "Response from `KeyMeasurablesAPIAPI.KeyMeasurablesApiUploadDataSetFile`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | A unique identifier for the data set. | 

### Other Parameters

Other parameters are passed through a pointer to a apiKeyMeasurablesApiUploadDataSetFileRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **body** | **string** |  | 

### Return type

[**KeyMeasurablesApiUploadDataSetFileResponse**](KeyMeasurablesApiUploadDataSetFileResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

