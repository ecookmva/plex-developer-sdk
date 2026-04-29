# \PriceAdjustmentsAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**PriceAdjustmentsApiCreatePriceAdjustment**](PriceAdjustmentsAPIAPI.md#PriceAdjustmentsApiCreatePriceAdjustment) | **Post** /sales/v1/price-adjustments | Create Price Adjustment
[**PriceAdjustmentsApiGetPriceAdjustment**](PriceAdjustmentsAPIAPI.md#PriceAdjustmentsApiGetPriceAdjustment) | **Get** /sales/v1/price-adjustments/{id} | Get Price Adjustment
[**PriceAdjustmentsApiListPriceAdjustments**](PriceAdjustmentsAPIAPI.md#PriceAdjustmentsApiListPriceAdjustments) | **Get** /sales/v1/price-adjustments | List Price Adjustments



## PriceAdjustmentsApiCreatePriceAdjustment

> PriceAdjustmentsApiCreatePriceAdjustment201Response PriceAdjustmentsApiCreatePriceAdjustment(ctx).PriceAdjustmentsApiCreatePriceAdjustmentRequest(priceAdjustmentsApiCreatePriceAdjustmentRequest).Execute()

Create Price Adjustment



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
	priceAdjustmentsApiCreatePriceAdjustmentRequest := *openapiclient.NewPriceAdjustmentsApiCreatePriceAdjustmentRequest() // PriceAdjustmentsApiCreatePriceAdjustmentRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PriceAdjustmentsAPIAPI.PriceAdjustmentsApiCreatePriceAdjustment(context.Background()).PriceAdjustmentsApiCreatePriceAdjustmentRequest(priceAdjustmentsApiCreatePriceAdjustmentRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PriceAdjustmentsAPIAPI.PriceAdjustmentsApiCreatePriceAdjustment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PriceAdjustmentsApiCreatePriceAdjustment`: PriceAdjustmentsApiCreatePriceAdjustment201Response
	fmt.Fprintf(os.Stdout, "Response from `PriceAdjustmentsAPIAPI.PriceAdjustmentsApiCreatePriceAdjustment`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPriceAdjustmentsApiCreatePriceAdjustmentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **priceAdjustmentsApiCreatePriceAdjustmentRequest** | [**PriceAdjustmentsApiCreatePriceAdjustmentRequest**](PriceAdjustmentsApiCreatePriceAdjustmentRequest.md) |  | 

### Return type

[**PriceAdjustmentsApiCreatePriceAdjustment201Response**](PriceAdjustmentsApiCreatePriceAdjustment201Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PriceAdjustmentsApiGetPriceAdjustment

> PriceAdjustmentsApiGetPriceAdjustmentResponse PriceAdjustmentsApiGetPriceAdjustment(ctx, id).Execute()

Get Price Adjustment



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
	resp, r, err := apiClient.PriceAdjustmentsAPIAPI.PriceAdjustmentsApiGetPriceAdjustment(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PriceAdjustmentsAPIAPI.PriceAdjustmentsApiGetPriceAdjustment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PriceAdjustmentsApiGetPriceAdjustment`: PriceAdjustmentsApiGetPriceAdjustmentResponse
	fmt.Fprintf(os.Stdout, "Response from `PriceAdjustmentsAPIAPI.PriceAdjustmentsApiGetPriceAdjustment`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiPriceAdjustmentsApiGetPriceAdjustmentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**PriceAdjustmentsApiGetPriceAdjustmentResponse**](PriceAdjustmentsApiGetPriceAdjustmentResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PriceAdjustmentsApiListPriceAdjustments

> []PriceAdjustmentsApiListPriceAdjustmentsItem PriceAdjustmentsApiListPriceAdjustments(ctx).Id(id).Type_(type_).AccountNo(accountNo).PartId(partId).Active(active).EffectiveDateBegin(effectiveDateBegin).EffectiveDateEnd(effectiveDateEnd).ExpirationDateBegin(expirationDateBegin).ExpirationDateEnd(expirationDateEnd).CustomerType(customerType).PartProductType(partProductType).Grade(grade).PartType(partType).Region(region).PartGroup(partGroup).PartProductGroup(partProductGroup).Execute()

List Price Adjustments



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
	id := "00000000-0000-0000-0000-000000000000" // string | The ID of the price adjustment. (optional)
	type_ := "string" // string | The price adjustment type assigned to the price adjustment. (optional)
	accountNo := "string" // string | The GL account number associated with the price adjustment record. (optional)
	partId := "00000000-0000-0000-0000-000000000000" // string | The ID of the internal part number to which the price adjustment record applies. (optional)
	active := false // bool | Identifies if the price adjustment record is active, regardless of effective and expiration dates. (optional)
	effectiveDateBegin := time.Now() // time.Time | The beginning date used to return price adjustments with an effective date within a time frame. (optional)
	effectiveDateEnd := time.Now() // time.Time | The end date used to return price adjustments with an effective date within a time frame. (optional)
	expirationDateBegin := time.Now() // time.Time | The beginning date used to return price adjustments with an expiration date within a time frame. (optional)
	expirationDateEnd := time.Now() // time.Time | The end date used to return price adjustments with an expiration date within a time frame. (optional)
	customerType := "string" // string | The customer type to which the price adjustment record applies. (optional)
	partProductType := "string" // string | The price adjustment record pertains to internal part numbers of a specific part product type. (optional)
	grade := "string" // string | The material grade assigned to a price adjustment. (optional)
	partType := "string" // string | The price adjustment record pertains to part numbers of a specific part type. (optional)
	region := "string" // string | The region associated with the price adjustment. (optional)
	partGroup := "string" // string | The price adjustment record pertains to part numbers of a specific part group. (optional)
	partProductGroup := "string" // string | The price adjustment record pertains to part numbers of a specific part product group. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PriceAdjustmentsAPIAPI.PriceAdjustmentsApiListPriceAdjustments(context.Background()).Id(id).Type_(type_).AccountNo(accountNo).PartId(partId).Active(active).EffectiveDateBegin(effectiveDateBegin).EffectiveDateEnd(effectiveDateEnd).ExpirationDateBegin(expirationDateBegin).ExpirationDateEnd(expirationDateEnd).CustomerType(customerType).PartProductType(partProductType).Grade(grade).PartType(partType).Region(region).PartGroup(partGroup).PartProductGroup(partProductGroup).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PriceAdjustmentsAPIAPI.PriceAdjustmentsApiListPriceAdjustments``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PriceAdjustmentsApiListPriceAdjustments`: []PriceAdjustmentsApiListPriceAdjustmentsItem
	fmt.Fprintf(os.Stdout, "Response from `PriceAdjustmentsAPIAPI.PriceAdjustmentsApiListPriceAdjustments`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPriceAdjustmentsApiListPriceAdjustmentsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **string** | The ID of the price adjustment. | 
 **type_** | **string** | The price adjustment type assigned to the price adjustment. | 
 **accountNo** | **string** | The GL account number associated with the price adjustment record. | 
 **partId** | **string** | The ID of the internal part number to which the price adjustment record applies. | 
 **active** | **bool** | Identifies if the price adjustment record is active, regardless of effective and expiration dates. | 
 **effectiveDateBegin** | **time.Time** | The beginning date used to return price adjustments with an effective date within a time frame. | 
 **effectiveDateEnd** | **time.Time** | The end date used to return price adjustments with an effective date within a time frame. | 
 **expirationDateBegin** | **time.Time** | The beginning date used to return price adjustments with an expiration date within a time frame. | 
 **expirationDateEnd** | **time.Time** | The end date used to return price adjustments with an expiration date within a time frame. | 
 **customerType** | **string** | The customer type to which the price adjustment record applies. | 
 **partProductType** | **string** | The price adjustment record pertains to internal part numbers of a specific part product type. | 
 **grade** | **string** | The material grade assigned to a price adjustment. | 
 **partType** | **string** | The price adjustment record pertains to part numbers of a specific part type. | 
 **region** | **string** | The region associated with the price adjustment. | 
 **partGroup** | **string** | The price adjustment record pertains to part numbers of a specific part group. | 
 **partProductGroup** | **string** | The price adjustment record pertains to part numbers of a specific part product group. | 

### Return type

[**[]PriceAdjustmentsApiListPriceAdjustmentsItem**](PriceAdjustmentsApiListPriceAdjustmentsItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

