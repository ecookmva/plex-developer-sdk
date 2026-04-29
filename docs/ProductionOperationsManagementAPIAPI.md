# \ProductionOperationsManagementAPIAPI

All URIs are relative to *https://connect.plex.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ProductionOperationsManagementApiActivateTankEventsLocationIgnoreForLotTrace**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiActivateTankEventsLocationIgnoreForLotTrace) | **Post** /production/v1/tank-management/locations/{locationId}/tank-events/ignore-for-lot-trace | Activate Tank Events Location Ignore For Lot Trace
[**ProductionOperationsManagementApiActivateTankEventsWorkcenterIgnoreForLotTrace**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiActivateTankEventsWorkcenterIgnoreForLotTrace) | **Post** /production/v1/tank-management/workcenters/{workcenterId}/tank-events/ignore-for-lot-trace | Activate Tank Events Workcenter Ignore For Lot Trace
[**ProductionOperationsManagementApiAddSourceInventory**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiAddSourceInventory) | **Post** /production/v1/control/workcenters/{workcenterId}/loaded-source-inventory | Add Source Inventory
[**ProductionOperationsManagementApiAssignLot**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiAssignLot) | **Post** /production/v1/control/workcenters/{workcenterId}/assign-lot | Assign Lot
[**ProductionOperationsManagementApiClearLotFromSetupContainer**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiClearLotFromSetupContainer) | **Post** /production/v1/control/workcenters/{workcenterId}/clear-lot | Clear Lot From Setup Container
[**ProductionOperationsManagementApiClockInOperator**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiClockInOperator) | **Post** /production/v1/control/workcenters/{workcenterId}/operators/clockin | Clock In Operator
[**ProductionOperationsManagementApiClockOutOperators**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiClockOutOperators) | **Post** /production/v1/control/workcenters/{workcenterId}/operators/clockout | Clock Out Operators
[**ProductionOperationsManagementApiCreateApprovedSupplier**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiCreateApprovedSupplier) | **Post** /production/v1/production-definitions/approved-suppliers | Create Approved Supplier
[**ProductionOperationsManagementApiCreateApprovedWorkcenter**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiCreateApprovedWorkcenter) | **Post** /production/v1/production-definitions/approved-workcenters | Create Approved Workcenter
[**ProductionOperationsManagementApiCreateSanitizationEvent**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiCreateSanitizationEvent) | **Post** /production/v1/tank-management/locations/{locationId}/sanitize | Create Sanitization Event
[**ProductionOperationsManagementApiGetBatch**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiGetBatch) | **Get** /production/v1/control/workcenters/{workcenterId}/batches/{batchId} | Get Batch
[**ProductionOperationsManagementApiGetCostSubType**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiGetCostSubType) | **Get** /production/v1/production-definitions/cost-sub-types/{costSubTypeId} | Get Cost Sub Type
[**ProductionOperationsManagementApiGetLoadedSourceInventory**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiGetLoadedSourceInventory) | **Get** /production/v1/control/workcenters/{workcenterId}/loaded-source-inventory | Get Loaded Source Inventory
[**ProductionOperationsManagementApiGetLocation**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiGetLocation) | **Get** /production/v1/production-definitions/locations/{locationId} | Get Location
[**ProductionOperationsManagementApiGetNextBatch**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiGetNextBatch) | **Get** /production/v1/control/workcenters/{workcenterId}/next-batch | Get Next Batch
[**ProductionOperationsManagementApiGetProductionLine**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiGetProductionLine) | **Get** /production/v1/production-definitions/production-lines/{id} | Get Production Line
[**ProductionOperationsManagementApiGetRequiredSourceInventory**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiGetRequiredSourceInventory) | **Get** /production/v1/control/workcenters/{workcenterId}/required-source-inventory | Get Required Source Inventory
[**ProductionOperationsManagementApiGetWorkcenter**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiGetWorkcenter) | **Get** /production/v1/production-definitions/workcenters/{id} | Get Workcenter
[**ProductionOperationsManagementApiGetWorkcenterEvent**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiGetWorkcenterEvent) | **Get** /production/v1/production-definitions/workcenter-events/{workcenterEventId} | Get Workcenter Event
[**ProductionOperationsManagementApiGetWorkcenterSetup**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiGetWorkcenterSetup) | **Get** /production/v1/control/workcenters/{workcenterId} | Get Workcenter Setup
[**ProductionOperationsManagementApiGetWorkcenterStatus**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiGetWorkcenterStatus) | **Get** /production/v1/production-definitions/workcenter-statuses/{workcenterStatusId} | Get Workcenter Status
[**ProductionOperationsManagementApiListApprovedSuppliers**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiListApprovedSuppliers) | **Get** /production/v1/production-definitions/approved-suppliers | List Approved Suppliers
[**ProductionOperationsManagementApiListApprovedWorkcenters**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiListApprovedWorkcenters) | **Get** /production/v1/production-definitions/approved-workcenters | List Approved Workcenters
[**ProductionOperationsManagementApiListBatches**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiListBatches) | **Get** /production/v1/control/workcenters/{workcenterId}/batches | List Batches
[**ProductionOperationsManagementApiListCostSubTypes**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiListCostSubTypes) | **Get** /production/v1/production-definitions/cost-sub-types | List Cost Sub Types
[**ProductionOperationsManagementApiListLaborEntries**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiListLaborEntries) | **Get** /production/v1/production-history/labor-entries | List Labor Entries
[**ProductionOperationsManagementApiListLocationTankEvents**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiListLocationTankEvents) | **Get** /production/v1/tank-management/locations/{locationId}/tank-events | List Location Tank Events
[**ProductionOperationsManagementApiListLocations**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiListLocations) | **Get** /production/v1/production-definitions/locations | List Locations
[**ProductionOperationsManagementApiListProductionEntries**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiListProductionEntries) | **Get** /production/v1/production-history/production-entries | List Production Entries
[**ProductionOperationsManagementApiListProductionEntriesSummary**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiListProductionEntriesSummary) | **Get** /production/v1-beta1/production-history/production-entries-summary | List Production Entries Summary
[**ProductionOperationsManagementApiListProductionLineWorkcenters**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiListProductionLineWorkcenters) | **Get** /production/v1/production-definitions/production-lines/{id}/workcenters | List Production Line Workcenters
[**ProductionOperationsManagementApiListProductionLines**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiListProductionLines) | **Get** /production/v1/production-definitions/production-lines | List Production Lines
[**ProductionOperationsManagementApiListSanitizationCodes**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiListSanitizationCodes) | **Get** /production/v1/tank-management/sanitization-codes | List Sanitization Codes
[**ProductionOperationsManagementApiListScrapEntries**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiListScrapEntries) | **Get** /production/v1/production-history/scrap-entries | List Scrap Entries
[**ProductionOperationsManagementApiListScrapEntriesSummary**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiListScrapEntriesSummary) | **Get** /production/v1-beta1/production-history/scrap-entries-summary | List Scrap Entries Summary
[**ProductionOperationsManagementApiListSubcontractReceipts**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiListSubcontractReceipts) | **Get** /production/v1-beta1/production-history/subcontract-receipts | List Subcontract Receipts
[**ProductionOperationsManagementApiListWorkcenterEvents**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiListWorkcenterEvents) | **Get** /production/v1/production-definitions/workcenter-events | List Workcenter Events
[**ProductionOperationsManagementApiListWorkcenterSetupEntries**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiListWorkcenterSetupEntries) | **Get** /production/v1/production-history/workcenter-setup-entries | List Workcenter Setup Entries
[**ProductionOperationsManagementApiListWorkcenterStatus**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiListWorkcenterStatus) | **Get** /production/v1/production-definitions/workcenter-statuses | List Workcenter Status
[**ProductionOperationsManagementApiListWorkcenterStatusEntries**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiListWorkcenterStatusEntries) | **Get** /production/v1/production-history/workcenter-status-entries | List Workcenter Status Entries
[**ProductionOperationsManagementApiListWorkcenterTankEvents**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiListWorkcenterTankEvents) | **Get** /production/v1/tank-management/workcenters/{workcenterId}/tank-events | List Workcenter Tank Events
[**ProductionOperationsManagementApiListWorkcenters**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiListWorkcenters) | **Get** /production/v1/production-definitions/workcenters | List Workcenters
[**ProductionOperationsManagementApiMoveTankContainers**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiMoveTankContainers) | **Post** /production/v1/tank-management/containers/move-containers | Move Tank Containers
[**ProductionOperationsManagementApiRecordBatchProduction**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiRecordBatchProduction) | **Post** /production/v1/control/workcenters/{workcenterId}/record-batch-production | Record Batch Production
[**ProductionOperationsManagementApiRecordVariableBOMProduction**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiRecordVariableBOMProduction) | **Post** /production/v1/control/workcenters/{workcenterId}/record-variable-bom-production | Record Variable BOM Production
[**ProductionOperationsManagementApiSearchWorkcenterSetups**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiSearchWorkcenterSetups) | **Post** /production/v1/control/workcenter-setups | Search Workcenter Setups
[**ProductionOperationsManagementApiSetWorkcenterStatus**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiSetWorkcenterStatus) | **Post** /production/v1/control/workcenters/{workcenterId}/status | Set Workcenter Status
[**ProductionOperationsManagementApiSetupJob**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiSetupJob) | **Post** /production/v1/control/workcenters/{workcenterId}/setup-job | Setup Job
[**ProductionOperationsManagementApiUnloadAllSourceInventory**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiUnloadAllSourceInventory) | **Delete** /production/v1/control/workcenters/{workcenterId}/loaded-source-inventory | Unload All Source Inventory
[**ProductionOperationsManagementApiUnloadSourceInventoryBySerialNo**](ProductionOperationsManagementAPIAPI.md#ProductionOperationsManagementApiUnloadSourceInventoryBySerialNo) | **Delete** /production/v1/control/workcenters/{workcenterId}/loaded-source-inventory/{serialNo} | Unload Source Inventory By Serial No



## ProductionOperationsManagementApiActivateTankEventsLocationIgnoreForLotTrace

> ProductionOperationsManagementApiActivateTankEventsLocationIgnoreForLotTrace204Response ProductionOperationsManagementApiActivateTankEventsLocationIgnoreForLotTrace(ctx, locationId).ProductionOperationsManagementApiActivateTankEventsLocationIgnoreForLotTraceRequest(productionOperationsManagementApiActivateTankEventsLocationIgnoreForLotTraceRequest).Execute()

Activate Tank Events Location Ignore For Lot Trace



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
	locationId := "00000000-0000-0000-0000-000000000000" // string | The unique identifier of the location.
	productionOperationsManagementApiActivateTankEventsLocationIgnoreForLotTraceRequest := *openapiclient.NewProductionOperationsManagementApiActivateTankEventsLocationIgnoreForLotTraceRequest() // ProductionOperationsManagementApiActivateTankEventsLocationIgnoreForLotTraceRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiActivateTankEventsLocationIgnoreForLotTrace(context.Background(), locationId).ProductionOperationsManagementApiActivateTankEventsLocationIgnoreForLotTraceRequest(productionOperationsManagementApiActivateTankEventsLocationIgnoreForLotTraceRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiActivateTankEventsLocationIgnoreForLotTrace``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductionOperationsManagementApiActivateTankEventsLocationIgnoreForLotTrace`: ProductionOperationsManagementApiActivateTankEventsLocationIgnoreForLotTrace204Response
	fmt.Fprintf(os.Stdout, "Response from `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiActivateTankEventsLocationIgnoreForLotTrace`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**locationId** | **string** | The unique identifier of the location. | 

### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiActivateTankEventsLocationIgnoreForLotTraceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **productionOperationsManagementApiActivateTankEventsLocationIgnoreForLotTraceRequest** | [**ProductionOperationsManagementApiActivateTankEventsLocationIgnoreForLotTraceRequest**](ProductionOperationsManagementApiActivateTankEventsLocationIgnoreForLotTraceRequest.md) |  | 

### Return type

[**ProductionOperationsManagementApiActivateTankEventsLocationIgnoreForLotTrace204Response**](ProductionOperationsManagementApiActivateTankEventsLocationIgnoreForLotTrace204Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductionOperationsManagementApiActivateTankEventsWorkcenterIgnoreForLotTrace

> ProductionOperationsManagementApiActivateTankEventsWorkcenterIgnoreForLotTrace204Response ProductionOperationsManagementApiActivateTankEventsWorkcenterIgnoreForLotTrace(ctx, workcenterId).ProductionOperationsManagementApiActivateTankEventsWorkcenterIgnoreForLotTraceRequest(productionOperationsManagementApiActivateTankEventsWorkcenterIgnoreForLotTraceRequest).Execute()

Activate Tank Events Workcenter Ignore For Lot Trace



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
	workcenterId := "00000000-0000-0000-0000-000000000000" // string | The unique identifier of the workcenter.
	productionOperationsManagementApiActivateTankEventsWorkcenterIgnoreForLotTraceRequest := *openapiclient.NewProductionOperationsManagementApiActivateTankEventsWorkcenterIgnoreForLotTraceRequest() // ProductionOperationsManagementApiActivateTankEventsWorkcenterIgnoreForLotTraceRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiActivateTankEventsWorkcenterIgnoreForLotTrace(context.Background(), workcenterId).ProductionOperationsManagementApiActivateTankEventsWorkcenterIgnoreForLotTraceRequest(productionOperationsManagementApiActivateTankEventsWorkcenterIgnoreForLotTraceRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiActivateTankEventsWorkcenterIgnoreForLotTrace``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductionOperationsManagementApiActivateTankEventsWorkcenterIgnoreForLotTrace`: ProductionOperationsManagementApiActivateTankEventsWorkcenterIgnoreForLotTrace204Response
	fmt.Fprintf(os.Stdout, "Response from `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiActivateTankEventsWorkcenterIgnoreForLotTrace`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workcenterId** | **string** | The unique identifier of the workcenter. | 

### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiActivateTankEventsWorkcenterIgnoreForLotTraceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **productionOperationsManagementApiActivateTankEventsWorkcenterIgnoreForLotTraceRequest** | [**ProductionOperationsManagementApiActivateTankEventsWorkcenterIgnoreForLotTraceRequest**](ProductionOperationsManagementApiActivateTankEventsWorkcenterIgnoreForLotTraceRequest.md) |  | 

### Return type

[**ProductionOperationsManagementApiActivateTankEventsWorkcenterIgnoreForLotTrace204Response**](ProductionOperationsManagementApiActivateTankEventsWorkcenterIgnoreForLotTrace204Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductionOperationsManagementApiAddSourceInventory

> []ProductionOperationsManagementApiAddSourceInventoryItem ProductionOperationsManagementApiAddSourceInventory(ctx, workcenterId).ProductionOperationsManagementApiAddSourceInventoryRequest(productionOperationsManagementApiAddSourceInventoryRequest).Execute()

Add Source Inventory



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
	workcenterId := "00000000-0000-0000-0000-000000000000" // string | 
	productionOperationsManagementApiAddSourceInventoryRequest := *openapiclient.NewProductionOperationsManagementApiAddSourceInventoryRequest() // ProductionOperationsManagementApiAddSourceInventoryRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiAddSourceInventory(context.Background(), workcenterId).ProductionOperationsManagementApiAddSourceInventoryRequest(productionOperationsManagementApiAddSourceInventoryRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiAddSourceInventory``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductionOperationsManagementApiAddSourceInventory`: []ProductionOperationsManagementApiAddSourceInventoryItem
	fmt.Fprintf(os.Stdout, "Response from `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiAddSourceInventory`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workcenterId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiAddSourceInventoryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **productionOperationsManagementApiAddSourceInventoryRequest** | [**ProductionOperationsManagementApiAddSourceInventoryRequest**](ProductionOperationsManagementApiAddSourceInventoryRequest.md) |  | 

### Return type

[**[]ProductionOperationsManagementApiAddSourceInventoryItem**](ProductionOperationsManagementApiAddSourceInventoryItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductionOperationsManagementApiAssignLot

> ProductionOperationsManagementApiAssignLotResponse ProductionOperationsManagementApiAssignLot(ctx, workcenterId).ProductionOperationsManagementApiAssignLotRequest(productionOperationsManagementApiAssignLotRequest).Execute()

Assign Lot



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
	workcenterId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier of the workcenter.
	productionOperationsManagementApiAssignLotRequest := *openapiclient.NewProductionOperationsManagementApiAssignLotRequest() // ProductionOperationsManagementApiAssignLotRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiAssignLot(context.Background(), workcenterId).ProductionOperationsManagementApiAssignLotRequest(productionOperationsManagementApiAssignLotRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiAssignLot``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductionOperationsManagementApiAssignLot`: ProductionOperationsManagementApiAssignLotResponse
	fmt.Fprintf(os.Stdout, "Response from `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiAssignLot`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workcenterId** | **string** | A unique identifier of the workcenter. | 

### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiAssignLotRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **productionOperationsManagementApiAssignLotRequest** | [**ProductionOperationsManagementApiAssignLotRequest**](ProductionOperationsManagementApiAssignLotRequest.md) |  | 

### Return type

[**ProductionOperationsManagementApiAssignLotResponse**](ProductionOperationsManagementApiAssignLotResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductionOperationsManagementApiClearLotFromSetupContainer

> ProductionOperationsManagementApiClearLotFromSetupContainer(ctx, workcenterId).ProductionOperationsManagementApiClearLotFromSetupContainerRequest(productionOperationsManagementApiClearLotFromSetupContainerRequest).Execute()

Clear Lot From Setup Container



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
	workcenterId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier of the workcenter.
	productionOperationsManagementApiClearLotFromSetupContainerRequest := *openapiclient.NewProductionOperationsManagementApiClearLotFromSetupContainerRequest() // ProductionOperationsManagementApiClearLotFromSetupContainerRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiClearLotFromSetupContainer(context.Background(), workcenterId).ProductionOperationsManagementApiClearLotFromSetupContainerRequest(productionOperationsManagementApiClearLotFromSetupContainerRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiClearLotFromSetupContainer``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workcenterId** | **string** | A unique identifier of the workcenter. | 

### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiClearLotFromSetupContainerRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **productionOperationsManagementApiClearLotFromSetupContainerRequest** | [**ProductionOperationsManagementApiClearLotFromSetupContainerRequest**](ProductionOperationsManagementApiClearLotFromSetupContainerRequest.md) |  | 

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


## ProductionOperationsManagementApiClockInOperator

> ProductionOperationsManagementApiClockInOperatorResponse ProductionOperationsManagementApiClockInOperator(ctx, workcenterId).ProductionOperationsManagementApiClockInOperatorRequest(productionOperationsManagementApiClockInOperatorRequest).Execute()

Clock In Operator



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
	workcenterId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier of the workcenter.
	productionOperationsManagementApiClockInOperatorRequest := *openapiclient.NewProductionOperationsManagementApiClockInOperatorRequest() // ProductionOperationsManagementApiClockInOperatorRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiClockInOperator(context.Background(), workcenterId).ProductionOperationsManagementApiClockInOperatorRequest(productionOperationsManagementApiClockInOperatorRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiClockInOperator``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductionOperationsManagementApiClockInOperator`: ProductionOperationsManagementApiClockInOperatorResponse
	fmt.Fprintf(os.Stdout, "Response from `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiClockInOperator`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workcenterId** | **string** | A unique identifier of the workcenter. | 

### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiClockInOperatorRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **productionOperationsManagementApiClockInOperatorRequest** | [**ProductionOperationsManagementApiClockInOperatorRequest**](ProductionOperationsManagementApiClockInOperatorRequest.md) |  | 

### Return type

[**ProductionOperationsManagementApiClockInOperatorResponse**](ProductionOperationsManagementApiClockInOperatorResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductionOperationsManagementApiClockOutOperators

> ProductionOperationsManagementApiClockOutOperatorsResponse ProductionOperationsManagementApiClockOutOperators(ctx, workcenterId).AccountIDs(accountIDs).Execute()

Clock Out Operators



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
	workcenterId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier of the workcenter.
	accountIDs := []string{"00000000-0000-0000-0000-000000000000"} // []string | A list of unique identifiers of IAM accounts to be clocked out of the workcenter. If not provided all operators will be clocked out. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiClockOutOperators(context.Background(), workcenterId).AccountIDs(accountIDs).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiClockOutOperators``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductionOperationsManagementApiClockOutOperators`: ProductionOperationsManagementApiClockOutOperatorsResponse
	fmt.Fprintf(os.Stdout, "Response from `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiClockOutOperators`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workcenterId** | **string** | A unique identifier of the workcenter. | 

### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiClockOutOperatorsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **accountIDs** | **[]string** | A list of unique identifiers of IAM accounts to be clocked out of the workcenter. If not provided all operators will be clocked out. | 

### Return type

[**ProductionOperationsManagementApiClockOutOperatorsResponse**](ProductionOperationsManagementApiClockOutOperatorsResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductionOperationsManagementApiCreateApprovedSupplier

> ProductionOperationsManagementApiCreateApprovedSupplier201Response ProductionOperationsManagementApiCreateApprovedSupplier(ctx).ProductionOperationsManagementApiCreateApprovedSupplierRequest(productionOperationsManagementApiCreateApprovedSupplierRequest).Execute()

Create Approved Supplier



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
	productionOperationsManagementApiCreateApprovedSupplierRequest := *openapiclient.NewProductionOperationsManagementApiCreateApprovedSupplierRequest() // ProductionOperationsManagementApiCreateApprovedSupplierRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiCreateApprovedSupplier(context.Background()).ProductionOperationsManagementApiCreateApprovedSupplierRequest(productionOperationsManagementApiCreateApprovedSupplierRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiCreateApprovedSupplier``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductionOperationsManagementApiCreateApprovedSupplier`: ProductionOperationsManagementApiCreateApprovedSupplier201Response
	fmt.Fprintf(os.Stdout, "Response from `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiCreateApprovedSupplier`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiCreateApprovedSupplierRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **productionOperationsManagementApiCreateApprovedSupplierRequest** | [**ProductionOperationsManagementApiCreateApprovedSupplierRequest**](ProductionOperationsManagementApiCreateApprovedSupplierRequest.md) |  | 

### Return type

[**ProductionOperationsManagementApiCreateApprovedSupplier201Response**](ProductionOperationsManagementApiCreateApprovedSupplier201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductionOperationsManagementApiCreateApprovedWorkcenter

> ProductionOperationsManagementApiCreateApprovedWorkcenter201Response ProductionOperationsManagementApiCreateApprovedWorkcenter(ctx).ProductionOperationsManagementApiCreateApprovedWorkcenterRequest(productionOperationsManagementApiCreateApprovedWorkcenterRequest).Execute()

Create Approved Workcenter



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
	productionOperationsManagementApiCreateApprovedWorkcenterRequest := *openapiclient.NewProductionOperationsManagementApiCreateApprovedWorkcenterRequest() // ProductionOperationsManagementApiCreateApprovedWorkcenterRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiCreateApprovedWorkcenter(context.Background()).ProductionOperationsManagementApiCreateApprovedWorkcenterRequest(productionOperationsManagementApiCreateApprovedWorkcenterRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiCreateApprovedWorkcenter``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductionOperationsManagementApiCreateApprovedWorkcenter`: ProductionOperationsManagementApiCreateApprovedWorkcenter201Response
	fmt.Fprintf(os.Stdout, "Response from `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiCreateApprovedWorkcenter`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiCreateApprovedWorkcenterRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **productionOperationsManagementApiCreateApprovedWorkcenterRequest** | [**ProductionOperationsManagementApiCreateApprovedWorkcenterRequest**](ProductionOperationsManagementApiCreateApprovedWorkcenterRequest.md) |  | 

### Return type

[**ProductionOperationsManagementApiCreateApprovedWorkcenter201Response**](ProductionOperationsManagementApiCreateApprovedWorkcenter201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductionOperationsManagementApiCreateSanitizationEvent

> ProductionOperationsManagementApiCreateSanitizationEvent201Response ProductionOperationsManagementApiCreateSanitizationEvent(ctx, locationId).ProductionOperationsManagementApiCreateSanitizationEventRequest(productionOperationsManagementApiCreateSanitizationEventRequest).Execute()

Create Sanitization Event



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
	locationId := "00000000-0000-0000-0000-000000000000" // string | The unique identifier of location.
	productionOperationsManagementApiCreateSanitizationEventRequest := *openapiclient.NewProductionOperationsManagementApiCreateSanitizationEventRequest() // ProductionOperationsManagementApiCreateSanitizationEventRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiCreateSanitizationEvent(context.Background(), locationId).ProductionOperationsManagementApiCreateSanitizationEventRequest(productionOperationsManagementApiCreateSanitizationEventRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiCreateSanitizationEvent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductionOperationsManagementApiCreateSanitizationEvent`: ProductionOperationsManagementApiCreateSanitizationEvent201Response
	fmt.Fprintf(os.Stdout, "Response from `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiCreateSanitizationEvent`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**locationId** | **string** | The unique identifier of location. | 

### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiCreateSanitizationEventRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **productionOperationsManagementApiCreateSanitizationEventRequest** | [**ProductionOperationsManagementApiCreateSanitizationEventRequest**](ProductionOperationsManagementApiCreateSanitizationEventRequest.md) |  | 

### Return type

[**ProductionOperationsManagementApiCreateSanitizationEvent201Response**](ProductionOperationsManagementApiCreateSanitizationEvent201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductionOperationsManagementApiGetBatch

> ProductionOperationsManagementApiGetBatchResponse ProductionOperationsManagementApiGetBatch(ctx, workcenterId, batchId).Execute()

Get Batch



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
	workcenterId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier of the workcenter.
	batchId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier of the batch.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiGetBatch(context.Background(), workcenterId, batchId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiGetBatch``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductionOperationsManagementApiGetBatch`: ProductionOperationsManagementApiGetBatchResponse
	fmt.Fprintf(os.Stdout, "Response from `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiGetBatch`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workcenterId** | **string** | A unique identifier of the workcenter. | 
**batchId** | **string** | A unique identifier of the batch. | 

### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiGetBatchRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**ProductionOperationsManagementApiGetBatchResponse**](ProductionOperationsManagementApiGetBatchResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductionOperationsManagementApiGetCostSubType

> ProductionOperationsManagementApiGetCostSubTypeResponse ProductionOperationsManagementApiGetCostSubType(ctx, costSubTypeId).Execute()

Get Cost Sub Type



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
	costSubTypeId := "00000000-0000-0000-0000-000000000000" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiGetCostSubType(context.Background(), costSubTypeId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiGetCostSubType``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductionOperationsManagementApiGetCostSubType`: ProductionOperationsManagementApiGetCostSubTypeResponse
	fmt.Fprintf(os.Stdout, "Response from `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiGetCostSubType`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**costSubTypeId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiGetCostSubTypeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ProductionOperationsManagementApiGetCostSubTypeResponse**](ProductionOperationsManagementApiGetCostSubTypeResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductionOperationsManagementApiGetLoadedSourceInventory

> []ProductionOperationsManagementApiGetLoadedSourceInventoryItem ProductionOperationsManagementApiGetLoadedSourceInventory(ctx, workcenterId).PartId(partId).PartOperationId(partOperationId).Execute()

Get Loaded Source Inventory



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
	workcenterId := "00000000-0000-0000-0000-000000000000" // string | 
	partId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for a part. (optional)
	partOperationId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for a part operation. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiGetLoadedSourceInventory(context.Background(), workcenterId).PartId(partId).PartOperationId(partOperationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiGetLoadedSourceInventory``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductionOperationsManagementApiGetLoadedSourceInventory`: []ProductionOperationsManagementApiGetLoadedSourceInventoryItem
	fmt.Fprintf(os.Stdout, "Response from `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiGetLoadedSourceInventory`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workcenterId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiGetLoadedSourceInventoryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **partId** | **string** | A unique identifier for a part. | 
 **partOperationId** | **string** | A unique identifier for a part operation. | 

### Return type

[**[]ProductionOperationsManagementApiGetLoadedSourceInventoryItem**](ProductionOperationsManagementApiGetLoadedSourceInventoryItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductionOperationsManagementApiGetLocation

> ProductionOperationsManagementApiGetLocationResponse ProductionOperationsManagementApiGetLocation(ctx, locationId).Execute()

Get Location



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
	locationId := "00000000-0000-0000-0000-000000000000" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiGetLocation(context.Background(), locationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiGetLocation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductionOperationsManagementApiGetLocation`: ProductionOperationsManagementApiGetLocationResponse
	fmt.Fprintf(os.Stdout, "Response from `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiGetLocation`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**locationId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiGetLocationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ProductionOperationsManagementApiGetLocationResponse**](ProductionOperationsManagementApiGetLocationResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductionOperationsManagementApiGetNextBatch

> ProductionOperationsManagementApiGetNextBatchResponse ProductionOperationsManagementApiGetNextBatch(ctx, workcenterId).PartId(partId).JobId(jobId).SortOrder(sortOrder).Execute()

Get Next Batch



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
	workcenterId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier of the workcenter.
	partId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the part. (optional)
	jobId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the job. (optional)
	sortOrder := "string" // string | The sort order method used to determine how to order scheduled jobs. If omitted from the request, the default value is SortOrder unless the &quot;Run Record SortOrder Use&quot; setting is enabled, in which case the default is StartDate. Sort order values are: SortOrder, StartDate, CompletionDate, ToolAssemblyNo, Job. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiGetNextBatch(context.Background(), workcenterId).PartId(partId).JobId(jobId).SortOrder(sortOrder).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiGetNextBatch``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductionOperationsManagementApiGetNextBatch`: ProductionOperationsManagementApiGetNextBatchResponse
	fmt.Fprintf(os.Stdout, "Response from `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiGetNextBatch`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workcenterId** | **string** | A unique identifier of the workcenter. | 

### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiGetNextBatchRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **partId** | **string** | A unique identifier for the part. | 
 **jobId** | **string** | A unique identifier for the job. | 
 **sortOrder** | **string** | The sort order method used to determine how to order scheduled jobs. If omitted from the request, the default value is SortOrder unless the &amp;quot;Run Record SortOrder Use&amp;quot; setting is enabled, in which case the default is StartDate. Sort order values are: SortOrder, StartDate, CompletionDate, ToolAssemblyNo, Job. | 

### Return type

[**ProductionOperationsManagementApiGetNextBatchResponse**](ProductionOperationsManagementApiGetNextBatchResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductionOperationsManagementApiGetProductionLine

> ProductionOperationsManagementApiGetProductionLineResponse ProductionOperationsManagementApiGetProductionLine(ctx, id).Execute()

Get Production Line



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
	id := "00000000-0000-0000-0000-000000000000" // string | The production line ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiGetProductionLine(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiGetProductionLine``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductionOperationsManagementApiGetProductionLine`: ProductionOperationsManagementApiGetProductionLineResponse
	fmt.Fprintf(os.Stdout, "Response from `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiGetProductionLine`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The production line ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiGetProductionLineRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ProductionOperationsManagementApiGetProductionLineResponse**](ProductionOperationsManagementApiGetProductionLineResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductionOperationsManagementApiGetRequiredSourceInventory

> []ProductionOperationsManagementApiGetRequiredSourceInventoryItem ProductionOperationsManagementApiGetRequiredSourceInventory(ctx, workcenterId).Execute()

Get Required Source Inventory



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
	workcenterId := "00000000-0000-0000-0000-000000000000" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiGetRequiredSourceInventory(context.Background(), workcenterId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiGetRequiredSourceInventory``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductionOperationsManagementApiGetRequiredSourceInventory`: []ProductionOperationsManagementApiGetRequiredSourceInventoryItem
	fmt.Fprintf(os.Stdout, "Response from `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiGetRequiredSourceInventory`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workcenterId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiGetRequiredSourceInventoryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]ProductionOperationsManagementApiGetRequiredSourceInventoryItem**](ProductionOperationsManagementApiGetRequiredSourceInventoryItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductionOperationsManagementApiGetWorkcenter

> ProductionOperationsManagementApiGetWorkcenterResponse ProductionOperationsManagementApiGetWorkcenter(ctx, id).Execute()

Get Workcenter



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
	id := "00000000-0000-0000-0000-000000000000" // string | The UUID assigned to the workcenter.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiGetWorkcenter(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiGetWorkcenter``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductionOperationsManagementApiGetWorkcenter`: ProductionOperationsManagementApiGetWorkcenterResponse
	fmt.Fprintf(os.Stdout, "Response from `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiGetWorkcenter`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The UUID assigned to the workcenter. | 

### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiGetWorkcenterRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ProductionOperationsManagementApiGetWorkcenterResponse**](ProductionOperationsManagementApiGetWorkcenterResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductionOperationsManagementApiGetWorkcenterEvent

> ProductionOperationsManagementApiGetWorkcenterEventResponse ProductionOperationsManagementApiGetWorkcenterEvent(ctx, workcenterEventId).Execute()

Get Workcenter Event



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
	workcenterEventId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier of a workcenter event

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiGetWorkcenterEvent(context.Background(), workcenterEventId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiGetWorkcenterEvent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductionOperationsManagementApiGetWorkcenterEvent`: ProductionOperationsManagementApiGetWorkcenterEventResponse
	fmt.Fprintf(os.Stdout, "Response from `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiGetWorkcenterEvent`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workcenterEventId** | **string** | A unique identifier of a workcenter event | 

### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiGetWorkcenterEventRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ProductionOperationsManagementApiGetWorkcenterEventResponse**](ProductionOperationsManagementApiGetWorkcenterEventResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductionOperationsManagementApiGetWorkcenterSetup

> ProductionOperationsManagementApiGetWorkcenterSetupResponse ProductionOperationsManagementApiGetWorkcenterSetup(ctx, workcenterId).Execute()

Get Workcenter Setup



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
	workcenterId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier of the workcenter.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiGetWorkcenterSetup(context.Background(), workcenterId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiGetWorkcenterSetup``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductionOperationsManagementApiGetWorkcenterSetup`: ProductionOperationsManagementApiGetWorkcenterSetupResponse
	fmt.Fprintf(os.Stdout, "Response from `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiGetWorkcenterSetup`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workcenterId** | **string** | A unique identifier of the workcenter. | 

### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiGetWorkcenterSetupRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ProductionOperationsManagementApiGetWorkcenterSetupResponse**](ProductionOperationsManagementApiGetWorkcenterSetupResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductionOperationsManagementApiGetWorkcenterStatus

> ProductionOperationsManagementApiGetWorkcenterStatusResponse ProductionOperationsManagementApiGetWorkcenterStatus(ctx, workcenterStatusId).Execute()

Get Workcenter Status



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
	workcenterStatusId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier of a workcenter status.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiGetWorkcenterStatus(context.Background(), workcenterStatusId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiGetWorkcenterStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductionOperationsManagementApiGetWorkcenterStatus`: ProductionOperationsManagementApiGetWorkcenterStatusResponse
	fmt.Fprintf(os.Stdout, "Response from `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiGetWorkcenterStatus`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workcenterStatusId** | **string** | A unique identifier of a workcenter status. | 

### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiGetWorkcenterStatusRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ProductionOperationsManagementApiGetWorkcenterStatusResponse**](ProductionOperationsManagementApiGetWorkcenterStatusResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductionOperationsManagementApiListApprovedSuppliers

> []ProductionOperationsManagementApiListApprovedSuppliersItem ProductionOperationsManagementApiListApprovedSuppliers(ctx).PartId(partId).PartOperationId(partOperationId).SupplierId(supplierId).Execute()

List Approved Suppliers



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
	partId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the part. (optional)
	partOperationId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the part operation. (optional)
	supplierId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for the supplier. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListApprovedSuppliers(context.Background()).PartId(partId).PartOperationId(partOperationId).SupplierId(supplierId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListApprovedSuppliers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductionOperationsManagementApiListApprovedSuppliers`: []ProductionOperationsManagementApiListApprovedSuppliersItem
	fmt.Fprintf(os.Stdout, "Response from `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListApprovedSuppliers`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiListApprovedSuppliersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **partId** | **string** | A unique identifier for the part. | 
 **partOperationId** | **string** | A unique identifier for the part operation. | 
 **supplierId** | **string** | A unique identifier for the supplier. | 

### Return type

[**[]ProductionOperationsManagementApiListApprovedSuppliersItem**](ProductionOperationsManagementApiListApprovedSuppliersItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductionOperationsManagementApiListApprovedWorkcenters

> []ProductionOperationsManagementApiListApprovedWorkcentersItem ProductionOperationsManagementApiListApprovedWorkcenters(ctx).WorkcenterId(workcenterId).PartId(partId).PartOperationId(partOperationId).OperationId(operationId).Execute()

List Approved Workcenters



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
	workcenterId := "00000000-0000-0000-0000-000000000000" // string | The ID of the workcenter where part is produced. (optional)
	partId := "00000000-0000-0000-0000-000000000000" // string | The ID of the part that is produced. (optional)
	partOperationId := "00000000-0000-0000-0000-000000000000" // string | The ID of the part operation. (optional)
	operationId := "00000000-0000-0000-0000-000000000000" // string | The ID of the operation. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListApprovedWorkcenters(context.Background()).WorkcenterId(workcenterId).PartId(partId).PartOperationId(partOperationId).OperationId(operationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListApprovedWorkcenters``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductionOperationsManagementApiListApprovedWorkcenters`: []ProductionOperationsManagementApiListApprovedWorkcentersItem
	fmt.Fprintf(os.Stdout, "Response from `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListApprovedWorkcenters`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiListApprovedWorkcentersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **workcenterId** | **string** | The ID of the workcenter where part is produced. | 
 **partId** | **string** | The ID of the part that is produced. | 
 **partOperationId** | **string** | The ID of the part operation. | 
 **operationId** | **string** | The ID of the operation. | 

### Return type

[**[]ProductionOperationsManagementApiListApprovedWorkcentersItem**](ProductionOperationsManagementApiListApprovedWorkcentersItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductionOperationsManagementApiListBatches

> []ProductionOperationsManagementApiListBatchesItem ProductionOperationsManagementApiListBatches(ctx, workcenterId).BeginDueDate(beginDueDate).EndDueDate(endDueDate).BeginStartDate(beginStartDate).EndStartDate(endStartDate).PartId(partId).BatchStatus(batchStatus).SortOrder(sortOrder).Execute()

List Batches



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
	workcenterId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier of the workcenter.
	beginDueDate := time.Now() // time.Time | The beginning date used to return batches that are due within a time period. (optional)
	endDueDate := time.Now() // time.Time | The end date used to return batches that are due within a time period. (optional)
	beginStartDate := time.Now() // time.Time | The beginning date used to return batches that start within a time period. (optional)
	endStartDate := time.Now() // time.Time | The end date used to return batches that start within a time period. (optional)
	partId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier for a part. (optional)
	batchStatus := "string" // string | The status of the job operation batch as defined by the setup table Job_Op_Batch_Status. (optional)
	sortOrder := "string" // string | The sort order method used to determine how to order scheduled jobs. If omitted from the request, the default value is SortOrder unless the &quot;Run Record SortOrder Use&quot; setting is enabled, in which case the default is StartDate. Sort order values are: SortOrder, StartDate, CompletionDate, ToolAssemblyNo, Job. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListBatches(context.Background(), workcenterId).BeginDueDate(beginDueDate).EndDueDate(endDueDate).BeginStartDate(beginStartDate).EndStartDate(endStartDate).PartId(partId).BatchStatus(batchStatus).SortOrder(sortOrder).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListBatches``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductionOperationsManagementApiListBatches`: []ProductionOperationsManagementApiListBatchesItem
	fmt.Fprintf(os.Stdout, "Response from `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListBatches`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workcenterId** | **string** | A unique identifier of the workcenter. | 

### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiListBatchesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **beginDueDate** | **time.Time** | The beginning date used to return batches that are due within a time period. | 
 **endDueDate** | **time.Time** | The end date used to return batches that are due within a time period. | 
 **beginStartDate** | **time.Time** | The beginning date used to return batches that start within a time period. | 
 **endStartDate** | **time.Time** | The end date used to return batches that start within a time period. | 
 **partId** | **string** | A unique identifier for a part. | 
 **batchStatus** | **string** | The status of the job operation batch as defined by the setup table Job_Op_Batch_Status. | 
 **sortOrder** | **string** | The sort order method used to determine how to order scheduled jobs. If omitted from the request, the default value is SortOrder unless the &amp;quot;Run Record SortOrder Use&amp;quot; setting is enabled, in which case the default is StartDate. Sort order values are: SortOrder, StartDate, CompletionDate, ToolAssemblyNo, Job. | 

### Return type

[**[]ProductionOperationsManagementApiListBatchesItem**](ProductionOperationsManagementApiListBatchesItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductionOperationsManagementApiListCostSubTypes

> []ProductionOperationsManagementApiListCostSubTypesItem ProductionOperationsManagementApiListCostSubTypes(ctx).CostSubTypeName(costSubTypeName).Active(active).Execute()

List Cost Sub Types



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
	costSubTypeName := "string" // string | A cost sub type name. (optional)
	active := false // bool | Filters results by if cost sub type is active or not. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListCostSubTypes(context.Background()).CostSubTypeName(costSubTypeName).Active(active).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListCostSubTypes``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductionOperationsManagementApiListCostSubTypes`: []ProductionOperationsManagementApiListCostSubTypesItem
	fmt.Fprintf(os.Stdout, "Response from `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListCostSubTypes`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiListCostSubTypesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **costSubTypeName** | **string** | A cost sub type name. | 
 **active** | **bool** | Filters results by if cost sub type is active or not. | 

### Return type

[**[]ProductionOperationsManagementApiListCostSubTypesItem**](ProductionOperationsManagementApiListCostSubTypesItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductionOperationsManagementApiListLaborEntries

> []ProductionOperationsManagementApiListLaborEntriesItem ProductionOperationsManagementApiListLaborEntries(ctx).BeginDate(beginDate).EndDate(endDate).AccountId(accountId).EmployeeId(employeeId).JobId(jobId).WorkcenterId(workcenterId).PartId(partId).CostActivity(costActivity).Execute()

List Labor Entries



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
	beginDate := time.Now() // time.Time | Date/Time Format YYYY-MM-DDThh:mm:ss.fffffffZ See Knowledge center topic &quot;Dates and Times&quot; for more information (KC path Platform &gt; Plex APIs &gt; HTTP Data Source API &gt; Dates and Times). The date and time range from when closed labor entries are to be retrieved. Labor activities that end within specified date/time range will be retrieved.
	endDate := time.Now() // time.Time | Date/Time Format YYYY-MM-DDThh:mm:ss.fffffffZ See Knowledge center topic &quot;Dates and Times&quot; for more information (KC path Platform &gt; Plex APIs &gt; HTTP Data Source API &gt; Dates and Times). The date and time until when closed labor entries are to be retrieved. Labor activities that end within specified date/time range will be retrieved.
	accountId := "00000000-0000-0000-0000-000000000000" // string | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID assigned to a specific IAM account. (optional)
	employeeId := "00000000-0000-0000-0000-000000000000" // string | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID assigned to a specific employee. (optional)
	jobId := "00000000-0000-0000-0000-000000000000" // string | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the production job that was loaded to the workcenter when the labor activity was recorded. Note that a production job is not necessary to set or change teh workcenter's status. (optional)
	workcenterId := "00000000-0000-0000-0000-000000000000" // string | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the workcenter where the labor transaction was recorded. (optional)
	partId := "00000000-0000-0000-0000-000000000000" // string | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the part that was being produced in the workcenter when the labor activity was recorded. (optional)
	costActivity := "string" // string | 50 characters max. The type of manufacturing labor activity that was performed, such as Setup, Maintenance, Production. This is the Cost Sub Type configured in Cost Types Setup application. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListLaborEntries(context.Background()).BeginDate(beginDate).EndDate(endDate).AccountId(accountId).EmployeeId(employeeId).JobId(jobId).WorkcenterId(workcenterId).PartId(partId).CostActivity(costActivity).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListLaborEntries``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductionOperationsManagementApiListLaborEntries`: []ProductionOperationsManagementApiListLaborEntriesItem
	fmt.Fprintf(os.Stdout, "Response from `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListLaborEntries`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiListLaborEntriesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **beginDate** | **time.Time** | Date/Time Format YYYY-MM-DDThh:mm:ss.fffffffZ See Knowledge center topic &amp;quot;Dates and Times&amp;quot; for more information (KC path Platform &amp;gt; Plex APIs &amp;gt; HTTP Data Source API &amp;gt; Dates and Times). The date and time range from when closed labor entries are to be retrieved. Labor activities that end within specified date/time range will be retrieved. | 
 **endDate** | **time.Time** | Date/Time Format YYYY-MM-DDThh:mm:ss.fffffffZ See Knowledge center topic &amp;quot;Dates and Times&amp;quot; for more information (KC path Platform &amp;gt; Plex APIs &amp;gt; HTTP Data Source API &amp;gt; Dates and Times). The date and time until when closed labor entries are to be retrieved. Labor activities that end within specified date/time range will be retrieved. | 
 **accountId** | **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID assigned to a specific IAM account. | 
 **employeeId** | **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID assigned to a specific employee. | 
 **jobId** | **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the production job that was loaded to the workcenter when the labor activity was recorded. Note that a production job is not necessary to set or change teh workcenter&#39;s status. | 
 **workcenterId** | **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the workcenter where the labor transaction was recorded. | 
 **partId** | **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the part that was being produced in the workcenter when the labor activity was recorded. | 
 **costActivity** | **string** | 50 characters max. The type of manufacturing labor activity that was performed, such as Setup, Maintenance, Production. This is the Cost Sub Type configured in Cost Types Setup application. | 

### Return type

[**[]ProductionOperationsManagementApiListLaborEntriesItem**](ProductionOperationsManagementApiListLaborEntriesItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductionOperationsManagementApiListLocationTankEvents

> []ProductionOperationsManagementApiListLocationTankEventsItem ProductionOperationsManagementApiListLocationTankEvents(ctx, locationId).BeginDate(beginDate).EndDate(endDate).Execute()

List Location Tank Events



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
	locationId := "00000000-0000-0000-0000-000000000000" // string | The unique identifier of location.
	beginDate := time.Now() // time.Time | Begin datetime for query.
	endDate := time.Now() // time.Time | End datetime for query. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListLocationTankEvents(context.Background(), locationId).BeginDate(beginDate).EndDate(endDate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListLocationTankEvents``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductionOperationsManagementApiListLocationTankEvents`: []ProductionOperationsManagementApiListLocationTankEventsItem
	fmt.Fprintf(os.Stdout, "Response from `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListLocationTankEvents`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**locationId** | **string** | The unique identifier of location. | 

### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiListLocationTankEventsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **beginDate** | **time.Time** | Begin datetime for query. | 
 **endDate** | **time.Time** | End datetime for query. | 

### Return type

[**[]ProductionOperationsManagementApiListLocationTankEventsItem**](ProductionOperationsManagementApiListLocationTankEventsItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductionOperationsManagementApiListLocations

> []ProductionOperationsManagementApiListLocationsItem ProductionOperationsManagementApiListLocations(ctx).BuildingId(buildingId).LocationName(locationName).LocationType(locationType).Execute()

List Locations



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
	buildingId := "00000000-0000-0000-0000-000000000000" // string | The building identifier. (optional)
	locationName := "string" // string | The location name. (optional)
	locationType := "string" // string | The location type. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListLocations(context.Background()).BuildingId(buildingId).LocationName(locationName).LocationType(locationType).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListLocations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductionOperationsManagementApiListLocations`: []ProductionOperationsManagementApiListLocationsItem
	fmt.Fprintf(os.Stdout, "Response from `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListLocations`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiListLocationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **buildingId** | **string** | The building identifier. | 
 **locationName** | **string** | The location name. | 
 **locationType** | **string** | The location type. | 

### Return type

[**[]ProductionOperationsManagementApiListLocationsItem**](ProductionOperationsManagementApiListLocationsItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductionOperationsManagementApiListProductionEntries

> []ProductionOperationsManagementApiListProductionEntriesItem ProductionOperationsManagementApiListProductionEntries(ctx).BeginDate(beginDate).EndDate(endDate).WorkcenterId(workcenterId).JobId(jobId).PartId(partId).PartOperationId(partOperationId).Execute()

List Production Entries



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
	beginDate := time.Now() // time.Time | Date/Time Format YYYY-MM-DDThh:mm:ss.fffffffZ See Knowledge center topic &quot;Dates and Times&quot; for more information (KC path Platform &gt; Plex APIs &gt; HTTP Data Source API &gt; Dates and Times). The date and time from when recorded production transaction are to be retrieved.
	endDate := time.Now() // time.Time | Date/Time Format YYYY-MM-DDThh:mm:ss.fffffffZ See Knowledge center topic &quot;Dates and Times&quot; for more information (KC path Platform &gt; Plex APIs &gt; HTTP Data Source API &gt; Dates and Times). The date and time until when recorded production transaction are to be retrieved.
	workcenterId := "00000000-0000-0000-0000-000000000000" // string | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the workcenter where the production transaction was recorded. (optional)
	jobId := "00000000-0000-0000-0000-000000000000" // string | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the production job that production was recorded against. Note that a production job is not necessary to record production. Another scheduling method such as Kanban may have been used. (optional)
	partId := "00000000-0000-0000-0000-000000000000" // string | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the part that was produced. (optional)
	partOperationId := "00000000-0000-0000-0000-000000000000" // string | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the part operation that was produced. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListProductionEntries(context.Background()).BeginDate(beginDate).EndDate(endDate).WorkcenterId(workcenterId).JobId(jobId).PartId(partId).PartOperationId(partOperationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListProductionEntries``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductionOperationsManagementApiListProductionEntries`: []ProductionOperationsManagementApiListProductionEntriesItem
	fmt.Fprintf(os.Stdout, "Response from `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListProductionEntries`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiListProductionEntriesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **beginDate** | **time.Time** | Date/Time Format YYYY-MM-DDThh:mm:ss.fffffffZ See Knowledge center topic &amp;quot;Dates and Times&amp;quot; for more information (KC path Platform &amp;gt; Plex APIs &amp;gt; HTTP Data Source API &amp;gt; Dates and Times). The date and time from when recorded production transaction are to be retrieved. | 
 **endDate** | **time.Time** | Date/Time Format YYYY-MM-DDThh:mm:ss.fffffffZ See Knowledge center topic &amp;quot;Dates and Times&amp;quot; for more information (KC path Platform &amp;gt; Plex APIs &amp;gt; HTTP Data Source API &amp;gt; Dates and Times). The date and time until when recorded production transaction are to be retrieved. | 
 **workcenterId** | **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the workcenter where the production transaction was recorded. | 
 **jobId** | **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the production job that production was recorded against. Note that a production job is not necessary to record production. Another scheduling method such as Kanban may have been used. | 
 **partId** | **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the part that was produced. | 
 **partOperationId** | **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the part operation that was produced. | 

### Return type

[**[]ProductionOperationsManagementApiListProductionEntriesItem**](ProductionOperationsManagementApiListProductionEntriesItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductionOperationsManagementApiListProductionEntriesSummary

> []ProductionOperationsManagementApiListProductionEntriesSummaryItem ProductionOperationsManagementApiListProductionEntriesSummary(ctx).BeginDate(beginDate).EndDate(endDate).WorkcenterId(workcenterId).JobId(jobId).PartId(partId).PartOperationId(partOperationId).Execute()

List Production Entries Summary



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
	beginDate := time.Now() // time.Time | Date/Time Format YYYY-MM-DDThh:mm:ss.fffffffZ See Knowledge center topic &quot;Dates and Times&quot; for more information (KC path Platform &gt; Plex APIs &gt; HTTP Data Source API &gt; Dates and Times). The date and time from when recorded production transaction are to be retrieved.
	endDate := time.Now() // time.Time | Date/Time Format YYYY-MM-DDThh:mm:ss.fffffffZ See Knowledge center topic &quot;Dates and Times&quot; for more information (KC path Platform &gt; Plex APIs &gt; HTTP Data Source API &gt; Dates and Times). The date and time until when recorded production transaction are to be retrieved.
	workcenterId := "00000000-0000-0000-0000-000000000000" // string | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the workcenter where the production transaction was recorded. (optional)
	jobId := "00000000-0000-0000-0000-000000000000" // string | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the production job that production was recorded against. Note that a production job is not necessary to record production. Another scheduling method such as Kanban may have been used. (optional)
	partId := "00000000-0000-0000-0000-000000000000" // string | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the part that was produced. (optional)
	partOperationId := "00000000-0000-0000-0000-000000000000" // string | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the part operation that was produced. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListProductionEntriesSummary(context.Background()).BeginDate(beginDate).EndDate(endDate).WorkcenterId(workcenterId).JobId(jobId).PartId(partId).PartOperationId(partOperationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListProductionEntriesSummary``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductionOperationsManagementApiListProductionEntriesSummary`: []ProductionOperationsManagementApiListProductionEntriesSummaryItem
	fmt.Fprintf(os.Stdout, "Response from `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListProductionEntriesSummary`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiListProductionEntriesSummaryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **beginDate** | **time.Time** | Date/Time Format YYYY-MM-DDThh:mm:ss.fffffffZ See Knowledge center topic &amp;quot;Dates and Times&amp;quot; for more information (KC path Platform &amp;gt; Plex APIs &amp;gt; HTTP Data Source API &amp;gt; Dates and Times). The date and time from when recorded production transaction are to be retrieved. | 
 **endDate** | **time.Time** | Date/Time Format YYYY-MM-DDThh:mm:ss.fffffffZ See Knowledge center topic &amp;quot;Dates and Times&amp;quot; for more information (KC path Platform &amp;gt; Plex APIs &amp;gt; HTTP Data Source API &amp;gt; Dates and Times). The date and time until when recorded production transaction are to be retrieved. | 
 **workcenterId** | **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the workcenter where the production transaction was recorded. | 
 **jobId** | **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the production job that production was recorded against. Note that a production job is not necessary to record production. Another scheduling method such as Kanban may have been used. | 
 **partId** | **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the part that was produced. | 
 **partOperationId** | **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the part operation that was produced. | 

### Return type

[**[]ProductionOperationsManagementApiListProductionEntriesSummaryItem**](ProductionOperationsManagementApiListProductionEntriesSummaryItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductionOperationsManagementApiListProductionLineWorkcenters

> []ProductionOperationsManagementApiListProductionLineWorkcentersItem ProductionOperationsManagementApiListProductionLineWorkcenters(ctx, id).Execute()

List Production Line Workcenters



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
	id := "00000000-0000-0000-0000-000000000000" // string | The production line ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListProductionLineWorkcenters(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListProductionLineWorkcenters``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductionOperationsManagementApiListProductionLineWorkcenters`: []ProductionOperationsManagementApiListProductionLineWorkcentersItem
	fmt.Fprintf(os.Stdout, "Response from `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListProductionLineWorkcenters`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The production line ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiListProductionLineWorkcentersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]ProductionOperationsManagementApiListProductionLineWorkcentersItem**](ProductionOperationsManagementApiListProductionLineWorkcentersItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductionOperationsManagementApiListProductionLines

> []ProductionOperationsManagementApiListProductionLinesItem ProductionOperationsManagementApiListProductionLines(ctx).ProductionLineId(productionLineId).ProductionLineCode(productionLineCode).EquipmentId(equipmentId).Execute()

List Production Lines



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
	productionLineId := "00000000-0000-0000-0000-000000000000" // string | The unique identifier assigned to the production line. (optional)
	productionLineCode := "string" // string | 50 characters max. A short name associated to the productionLineID, and a unique code to reference the production line. (optional)
	equipmentId := "string" // string | 50 characters max. A short name associated to the equipment. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListProductionLines(context.Background()).ProductionLineId(productionLineId).ProductionLineCode(productionLineCode).EquipmentId(equipmentId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListProductionLines``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductionOperationsManagementApiListProductionLines`: []ProductionOperationsManagementApiListProductionLinesItem
	fmt.Fprintf(os.Stdout, "Response from `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListProductionLines`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiListProductionLinesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **productionLineId** | **string** | The unique identifier assigned to the production line. | 
 **productionLineCode** | **string** | 50 characters max. A short name associated to the productionLineID, and a unique code to reference the production line. | 
 **equipmentId** | **string** | 50 characters max. A short name associated to the equipment. | 

### Return type

[**[]ProductionOperationsManagementApiListProductionLinesItem**](ProductionOperationsManagementApiListProductionLinesItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductionOperationsManagementApiListSanitizationCodes

> []ProductionOperationsManagementApiListSanitizationCodesItem ProductionOperationsManagementApiListSanitizationCodes(ctx).Execute()

List Sanitization Codes



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
	resp, r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListSanitizationCodes(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListSanitizationCodes``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductionOperationsManagementApiListSanitizationCodes`: []ProductionOperationsManagementApiListSanitizationCodesItem
	fmt.Fprintf(os.Stdout, "Response from `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListSanitizationCodes`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiListSanitizationCodesRequest struct via the builder pattern


### Return type

[**[]ProductionOperationsManagementApiListSanitizationCodesItem**](ProductionOperationsManagementApiListSanitizationCodesItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductionOperationsManagementApiListScrapEntries

> []ProductionOperationsManagementApiListScrapEntriesItem ProductionOperationsManagementApiListScrapEntries(ctx).BeginDate(beginDate).EndDate(endDate).ScrapReason(scrapReason).WorkcenterId(workcenterId).JobId(jobId).PartId(partId).PartOperationId(partOperationId).Execute()

List Scrap Entries



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
	beginDate := time.Now() // time.Time | Date/Time Format YYYY-MM-DDThh:mm:ss.fffffffZ See Knowledge center topic &quot;Dates and Times&quot; for more information (KC path Platform &gt; Plex APIs &gt; HTTP Data Source API &gt; Dates and Times). The date and time from when scrap transaction are to be retrieved.
	endDate := time.Now() // time.Time | Date/Time Format YYYY-MM-DDThh:mm:ss.fffffffZ See Knowledge center topic &quot;Dates and Times&quot; for more information (KC path Platform &gt; Plex APIs &gt; HTTP Data Source API &gt; Dates and Times). The date and time until when scrap transaction are to be retrieved.
	scrapReason := "string" // string | 50 characters max. Setup table &quot;Scrap Reason&quot; (part.dbo.scrap_reason). The reason code which indicates why the material or part was scrapped. (optional)
	workcenterId := "00000000-0000-0000-0000-000000000000" // string | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the workcenter where the scrap transaction was recorded. (optional)
	jobId := "00000000-0000-0000-0000-000000000000" // string | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the production job that scrap was recorded against. Note that a production job is not necessary to record scrap. Another scheduling method such as kanban may have been used. (optional)
	partId := "00000000-0000-0000-0000-000000000000" // string | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the part that was scrapped. (optional)
	partOperationId := "00000000-0000-0000-0000-000000000000" // string | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the part operation that was produced. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListScrapEntries(context.Background()).BeginDate(beginDate).EndDate(endDate).ScrapReason(scrapReason).WorkcenterId(workcenterId).JobId(jobId).PartId(partId).PartOperationId(partOperationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListScrapEntries``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductionOperationsManagementApiListScrapEntries`: []ProductionOperationsManagementApiListScrapEntriesItem
	fmt.Fprintf(os.Stdout, "Response from `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListScrapEntries`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiListScrapEntriesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **beginDate** | **time.Time** | Date/Time Format YYYY-MM-DDThh:mm:ss.fffffffZ See Knowledge center topic &amp;quot;Dates and Times&amp;quot; for more information (KC path Platform &amp;gt; Plex APIs &amp;gt; HTTP Data Source API &amp;gt; Dates and Times). The date and time from when scrap transaction are to be retrieved. | 
 **endDate** | **time.Time** | Date/Time Format YYYY-MM-DDThh:mm:ss.fffffffZ See Knowledge center topic &amp;quot;Dates and Times&amp;quot; for more information (KC path Platform &amp;gt; Plex APIs &amp;gt; HTTP Data Source API &amp;gt; Dates and Times). The date and time until when scrap transaction are to be retrieved. | 
 **scrapReason** | **string** | 50 characters max. Setup table &amp;quot;Scrap Reason&amp;quot; (part.dbo.scrap_reason). The reason code which indicates why the material or part was scrapped. | 
 **workcenterId** | **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the workcenter where the scrap transaction was recorded. | 
 **jobId** | **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the production job that scrap was recorded against. Note that a production job is not necessary to record scrap. Another scheduling method such as kanban may have been used. | 
 **partId** | **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the part that was scrapped. | 
 **partOperationId** | **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the part operation that was produced. | 

### Return type

[**[]ProductionOperationsManagementApiListScrapEntriesItem**](ProductionOperationsManagementApiListScrapEntriesItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductionOperationsManagementApiListScrapEntriesSummary

> []ProductionOperationsManagementApiListScrapEntriesSummaryItem ProductionOperationsManagementApiListScrapEntriesSummary(ctx).BeginDate(beginDate).EndDate(endDate).ScrapReason(scrapReason).WorkcenterId(workcenterId).JobId(jobId).PartId(partId).PartOperationId(partOperationId).Execute()

List Scrap Entries Summary



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
	beginDate := time.Now() // time.Time | Date/Time Format YYYY-MM-DDThh:mm:ss.fffffffZ See Knowledge center topic &quot;Dates and Times&quot; for more information (KC path Platform &gt; Plex APIs &gt; HTTP Data Source API &gt; Dates and Times). The date and time from when scrap transaction are to be retrieved.
	endDate := time.Now() // time.Time | Date/Time Format YYYY-MM-DDThh:mm:ss.fffffffZ See Knowledge center topic &quot;Dates and Times&quot; for more information (KC path Platform &gt; Plex APIs &gt; HTTP Data Source API &gt; Dates and Times). The date and time until when scrap transaction are to be retrieved.
	scrapReason := "string" // string | 50 characters max. Setup table &quot;Scrap Reason&quot; (part.dbo.scrap_reason). The reason code which indicates why the material or part was scrapped. (optional)
	workcenterId := "00000000-0000-0000-0000-000000000000" // string | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the workcenter where the scrap transaction was recorded. (optional)
	jobId := "00000000-0000-0000-0000-000000000000" // string | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the production job that scrap was recorded against. Note that a production job is not necessary to record scrap. Another scheduling method such as kanban may have been used. (optional)
	partId := "00000000-0000-0000-0000-000000000000" // string | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the part that was scrapped. (optional)
	partOperationId := "00000000-0000-0000-0000-000000000000" // string | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the part operation that was produced. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListScrapEntriesSummary(context.Background()).BeginDate(beginDate).EndDate(endDate).ScrapReason(scrapReason).WorkcenterId(workcenterId).JobId(jobId).PartId(partId).PartOperationId(partOperationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListScrapEntriesSummary``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductionOperationsManagementApiListScrapEntriesSummary`: []ProductionOperationsManagementApiListScrapEntriesSummaryItem
	fmt.Fprintf(os.Stdout, "Response from `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListScrapEntriesSummary`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiListScrapEntriesSummaryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **beginDate** | **time.Time** | Date/Time Format YYYY-MM-DDThh:mm:ss.fffffffZ See Knowledge center topic &amp;quot;Dates and Times&amp;quot; for more information (KC path Platform &amp;gt; Plex APIs &amp;gt; HTTP Data Source API &amp;gt; Dates and Times). The date and time from when scrap transaction are to be retrieved. | 
 **endDate** | **time.Time** | Date/Time Format YYYY-MM-DDThh:mm:ss.fffffffZ See Knowledge center topic &amp;quot;Dates and Times&amp;quot; for more information (KC path Platform &amp;gt; Plex APIs &amp;gt; HTTP Data Source API &amp;gt; Dates and Times). The date and time until when scrap transaction are to be retrieved. | 
 **scrapReason** | **string** | 50 characters max. Setup table &amp;quot;Scrap Reason&amp;quot; (part.dbo.scrap_reason). The reason code which indicates why the material or part was scrapped. | 
 **workcenterId** | **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the workcenter where the scrap transaction was recorded. | 
 **jobId** | **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the production job that scrap was recorded against. Note that a production job is not necessary to record scrap. Another scheduling method such as kanban may have been used. | 
 **partId** | **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the part that was scrapped. | 
 **partOperationId** | **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the part operation that was produced. | 

### Return type

[**[]ProductionOperationsManagementApiListScrapEntriesSummaryItem**](ProductionOperationsManagementApiListScrapEntriesSummaryItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductionOperationsManagementApiListSubcontractReceipts

> []ProductionOperationsManagementApiListSubcontractReceiptsItem ProductionOperationsManagementApiListSubcontractReceipts(ctx).BeginDate(beginDate).EndDate(endDate).PartId(partId).SupplierId(supplierId).SupplierShipperNo(supplierShipperNo).Execute()

List Subcontract Receipts



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
	beginDate := time.Now() // time.Time | Date/Time Format YYYY-MM-DDThh:mm:ss.fffffffZ The date and time from when the subcontract receipts are to be retrieved. See &quot;Dates and Times&quot; in the Get Started section of the Plex Developer Portal (APIs &gt; Get Started).
	endDate := time.Now() // time.Time | Date/Time Format YYYY-MM-DDThh:mm:ss.fffffffZ The date and time until when the subcontract receipts are to be retrieved. See &quot;Dates and Times&quot; in the Get Started section of the Plex Developer Portal (APIs &gt; Get Started).
	partId := "00000000-0000-0000-0000-000000000000" // string | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. The part resource ID. (optional)
	supplierId := "00000000-0000-0000-0000-000000000000" // string | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. The supplier resource ID. (optional)
	supplierShipperNo := "string" // string | 50 characters max. The supplier shipper number. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListSubcontractReceipts(context.Background()).BeginDate(beginDate).EndDate(endDate).PartId(partId).SupplierId(supplierId).SupplierShipperNo(supplierShipperNo).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListSubcontractReceipts``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductionOperationsManagementApiListSubcontractReceipts`: []ProductionOperationsManagementApiListSubcontractReceiptsItem
	fmt.Fprintf(os.Stdout, "Response from `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListSubcontractReceipts`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiListSubcontractReceiptsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **beginDate** | **time.Time** | Date/Time Format YYYY-MM-DDThh:mm:ss.fffffffZ The date and time from when the subcontract receipts are to be retrieved. See &amp;quot;Dates and Times&amp;quot; in the Get Started section of the Plex Developer Portal (APIs &amp;gt; Get Started). | 
 **endDate** | **time.Time** | Date/Time Format YYYY-MM-DDThh:mm:ss.fffffffZ The date and time until when the subcontract receipts are to be retrieved. See &amp;quot;Dates and Times&amp;quot; in the Get Started section of the Plex Developer Portal (APIs &amp;gt; Get Started). | 
 **partId** | **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. The part resource ID. | 
 **supplierId** | **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. The supplier resource ID. | 
 **supplierShipperNo** | **string** | 50 characters max. The supplier shipper number. | 

### Return type

[**[]ProductionOperationsManagementApiListSubcontractReceiptsItem**](ProductionOperationsManagementApiListSubcontractReceiptsItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductionOperationsManagementApiListWorkcenterEvents

> []ProductionOperationsManagementApiListWorkcenterEventsItem ProductionOperationsManagementApiListWorkcenterEvents(ctx).Active(active).Description(description).Execute()

List Workcenter Events



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
	active := false // bool | Filters results by if workcenter event is active or not. (optional)
	description := "string" // string | The description of a workcenter event. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListWorkcenterEvents(context.Background()).Active(active).Description(description).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListWorkcenterEvents``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductionOperationsManagementApiListWorkcenterEvents`: []ProductionOperationsManagementApiListWorkcenterEventsItem
	fmt.Fprintf(os.Stdout, "Response from `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListWorkcenterEvents`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiListWorkcenterEventsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **active** | **bool** | Filters results by if workcenter event is active or not. | 
 **description** | **string** | The description of a workcenter event. | 

### Return type

[**[]ProductionOperationsManagementApiListWorkcenterEventsItem**](ProductionOperationsManagementApiListWorkcenterEventsItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductionOperationsManagementApiListWorkcenterSetupEntries

> []ProductionOperationsManagementApiListWorkcenterSetupEntriesItem ProductionOperationsManagementApiListWorkcenterSetupEntries(ctx).BeginSetupDate(beginSetupDate).EndSetupDate(endSetupDate).WorkcenterId(workcenterId).PartId(partId).Execute()

List Workcenter Setup Entries



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
	beginSetupDate := time.Now() // time.Time | Gets or sets the Start of the DateTime (in UTC) Range for the requested setup entries
	endSetupDate := time.Now() // time.Time | Gets or sets the End of the DateTime (in UTC) Range for the requested setup entries (optional)
	workcenterId := "00000000-0000-0000-0000-000000000000" // string | Gets or sets the WorkCenterId (UUID) (optional)
	partId := "00000000-0000-0000-0000-000000000000" // string | Gets or sets the PartId (UUID) (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListWorkcenterSetupEntries(context.Background()).BeginSetupDate(beginSetupDate).EndSetupDate(endSetupDate).WorkcenterId(workcenterId).PartId(partId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListWorkcenterSetupEntries``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductionOperationsManagementApiListWorkcenterSetupEntries`: []ProductionOperationsManagementApiListWorkcenterSetupEntriesItem
	fmt.Fprintf(os.Stdout, "Response from `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListWorkcenterSetupEntries`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiListWorkcenterSetupEntriesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **beginSetupDate** | **time.Time** | Gets or sets the Start of the DateTime (in UTC) Range for the requested setup entries | 
 **endSetupDate** | **time.Time** | Gets or sets the End of the DateTime (in UTC) Range for the requested setup entries | 
 **workcenterId** | **string** | Gets or sets the WorkCenterId (UUID) | 
 **partId** | **string** | Gets or sets the PartId (UUID) | 

### Return type

[**[]ProductionOperationsManagementApiListWorkcenterSetupEntriesItem**](ProductionOperationsManagementApiListWorkcenterSetupEntriesItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductionOperationsManagementApiListWorkcenterStatus

> []ProductionOperationsManagementApiListWorkcenterStatusItem ProductionOperationsManagementApiListWorkcenterStatus(ctx).Description(description).Active(active).OffStatus(offStatus).Execute()

List Workcenter Status



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
	description := "string" // string | The description of a workcenter status. (optional)
	active := false // bool | Filters results by if status is active or not. (optional)
	offStatus := false // bool | Filters results if status is an off status or not. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListWorkcenterStatus(context.Background()).Description(description).Active(active).OffStatus(offStatus).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListWorkcenterStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductionOperationsManagementApiListWorkcenterStatus`: []ProductionOperationsManagementApiListWorkcenterStatusItem
	fmt.Fprintf(os.Stdout, "Response from `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListWorkcenterStatus`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiListWorkcenterStatusRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **description** | **string** | The description of a workcenter status. | 
 **active** | **bool** | Filters results by if status is active or not. | 
 **offStatus** | **bool** | Filters results if status is an off status or not. | 

### Return type

[**[]ProductionOperationsManagementApiListWorkcenterStatusItem**](ProductionOperationsManagementApiListWorkcenterStatusItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductionOperationsManagementApiListWorkcenterStatusEntries

> []ProductionOperationsManagementApiListWorkcenterStatusEntriesItem ProductionOperationsManagementApiListWorkcenterStatusEntries(ctx).BeginDate(beginDate).EndDate(endDate).WorkcenterId(workcenterId).JobId(jobId).PartId(partId).Status(status).Execute()

List Workcenter Status Entries



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
	beginDate := time.Now() // time.Time | Date/Time Format YYYY-MM-DDThh:mm:ss.fffffffZ See Knowledge center topic &quot;Dates and Times&quot; for more information (KC path Platform &gt; Plex APIs &gt; HTTP Data Source API &gt; Dates and Times). The date and time from when recorded workcenter status transaction are to be retrieved.
	endDate := time.Now() // time.Time | Date/Time Format YYYY-MM-DDThh:mm:ss.fffffffZ See Knowledge center topic &quot;Dates and Times&quot; for more information (KC path Platform &gt; Plex APIs &gt; HTTP Data Source API &gt; Dates and Times). The date and time until when recorded workcenter status transaction are to be retrieved.
	workcenterId := "00000000-0000-0000-0000-000000000000" // string | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the workcenter where the status transaction was recorded. (optional)
	jobId := "00000000-0000-0000-0000-000000000000" // string | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the production job that was loaded to the workcenter when the workcenter status entry was recorded.  Note that a production job is not necessary to set or change the workcenter's status. (optional)
	partId := "00000000-0000-0000-0000-000000000000" // string | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the part that was being produced in the workcenter when the workcenter status entry was recorded. (optional)
	status := "string" // string | 50 characters max. The status of a workcenter. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListWorkcenterStatusEntries(context.Background()).BeginDate(beginDate).EndDate(endDate).WorkcenterId(workcenterId).JobId(jobId).PartId(partId).Status(status).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListWorkcenterStatusEntries``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductionOperationsManagementApiListWorkcenterStatusEntries`: []ProductionOperationsManagementApiListWorkcenterStatusEntriesItem
	fmt.Fprintf(os.Stdout, "Response from `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListWorkcenterStatusEntries`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiListWorkcenterStatusEntriesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **beginDate** | **time.Time** | Date/Time Format YYYY-MM-DDThh:mm:ss.fffffffZ See Knowledge center topic &amp;quot;Dates and Times&amp;quot; for more information (KC path Platform &amp;gt; Plex APIs &amp;gt; HTTP Data Source API &amp;gt; Dates and Times). The date and time from when recorded workcenter status transaction are to be retrieved. | 
 **endDate** | **time.Time** | Date/Time Format YYYY-MM-DDThh:mm:ss.fffffffZ See Knowledge center topic &amp;quot;Dates and Times&amp;quot; for more information (KC path Platform &amp;gt; Plex APIs &amp;gt; HTTP Data Source API &amp;gt; Dates and Times). The date and time until when recorded workcenter status transaction are to be retrieved. | 
 **workcenterId** | **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the workcenter where the status transaction was recorded. | 
 **jobId** | **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the production job that was loaded to the workcenter when the workcenter status entry was recorded.  Note that a production job is not necessary to set or change the workcenter&#39;s status. | 
 **partId** | **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the part that was being produced in the workcenter when the workcenter status entry was recorded. | 
 **status** | **string** | 50 characters max. The status of a workcenter. | 

### Return type

[**[]ProductionOperationsManagementApiListWorkcenterStatusEntriesItem**](ProductionOperationsManagementApiListWorkcenterStatusEntriesItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductionOperationsManagementApiListWorkcenterTankEvents

> []ProductionOperationsManagementApiListWorkcenterTankEventsItem ProductionOperationsManagementApiListWorkcenterTankEvents(ctx, workcenterId).BeginDate(beginDate).EndDate(endDate).Execute()

List Workcenter Tank Events



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
	workcenterId := "00000000-0000-0000-0000-000000000000" // string | The unique identifier of the workcenter.
	beginDate := time.Now() // time.Time | Begin datetime for query.
	endDate := time.Now() // time.Time | End datetime for query. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListWorkcenterTankEvents(context.Background(), workcenterId).BeginDate(beginDate).EndDate(endDate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListWorkcenterTankEvents``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductionOperationsManagementApiListWorkcenterTankEvents`: []ProductionOperationsManagementApiListWorkcenterTankEventsItem
	fmt.Fprintf(os.Stdout, "Response from `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListWorkcenterTankEvents`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workcenterId** | **string** | The unique identifier of the workcenter. | 

### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiListWorkcenterTankEventsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **beginDate** | **time.Time** | Begin datetime for query. | 
 **endDate** | **time.Time** | End datetime for query. | 

### Return type

[**[]ProductionOperationsManagementApiListWorkcenterTankEventsItem**](ProductionOperationsManagementApiListWorkcenterTankEventsItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductionOperationsManagementApiListWorkcenters

> []ProductionOperationsManagementApiListWorkcentersItem ProductionOperationsManagementApiListWorkcenters(ctx).WorkcenterCode(workcenterCode).Name(name).WorkcenterType(workcenterType).WorkcenterGroup(workcenterGroup).BuildingId(buildingId).TankSilo(tankSilo).PlcName(plcName).IpAddress(ipAddress).Execute()

List Workcenters



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
	workcenterCode := "string" // string | A short name associated to the workcenterID, and a unique code to reference the workcenter. This code displays throughout the system, primarily on the Control Panel. 50 characters max. (optional)
	name := "string" // string | The full name associated to the workcenterID that serves as a more descriptive name for the workcenter. Depending on your settings, this name can also display on the Control Panel and sequence board. 100 characters max. (optional)
	workcenterType := "string" // string | A grouping of similar workcenters. The workcenter type influences how the workcenter behaves and is also available as a filter in different areas of the application, such as the Control Panel, Production Statuses, and more. Setup table &quot;Workcenter Type&quot; (part.dbo.workcenter_type). 50 characters max. (optional)
	workcenterGroup := "string" // string | 50 characters max. Setup table &quot;Workcenter Group&quot; (part.dbo.workcenter_group). An optional grouping of similar workcenters. This is helpful when there are many workcenters that can be chosen from the Control Panel. If the Workcenter Group setting is on, the Control Panel will display the Workcenter Groups then once a group is chosen, the list of workcenters only in that group will display. (optional)
	buildingId := "00000000-0000-0000-0000-000000000000" // string | UUID of the building the workcenter is located in. (optional)
	tankSilo := false // bool | Boolean indicating whether the results should be filtered to only return tank/silo results. (optional)
	plcName := "string" // string | The PLC Name of the workcenter. 50 characters max. (optional)
	ipAddress := "string" // string | The IP Address of the workcenter. 15 characters max. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListWorkcenters(context.Background()).WorkcenterCode(workcenterCode).Name(name).WorkcenterType(workcenterType).WorkcenterGroup(workcenterGroup).BuildingId(buildingId).TankSilo(tankSilo).PlcName(plcName).IpAddress(ipAddress).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListWorkcenters``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductionOperationsManagementApiListWorkcenters`: []ProductionOperationsManagementApiListWorkcentersItem
	fmt.Fprintf(os.Stdout, "Response from `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiListWorkcenters`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiListWorkcentersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **workcenterCode** | **string** | A short name associated to the workcenterID, and a unique code to reference the workcenter. This code displays throughout the system, primarily on the Control Panel. 50 characters max. | 
 **name** | **string** | The full name associated to the workcenterID that serves as a more descriptive name for the workcenter. Depending on your settings, this name can also display on the Control Panel and sequence board. 100 characters max. | 
 **workcenterType** | **string** | A grouping of similar workcenters. The workcenter type influences how the workcenter behaves and is also available as a filter in different areas of the application, such as the Control Panel, Production Statuses, and more. Setup table &amp;quot;Workcenter Type&amp;quot; (part.dbo.workcenter_type). 50 characters max. | 
 **workcenterGroup** | **string** | 50 characters max. Setup table &amp;quot;Workcenter Group&amp;quot; (part.dbo.workcenter_group). An optional grouping of similar workcenters. This is helpful when there are many workcenters that can be chosen from the Control Panel. If the Workcenter Group setting is on, the Control Panel will display the Workcenter Groups then once a group is chosen, the list of workcenters only in that group will display. | 
 **buildingId** | **string** | UUID of the building the workcenter is located in. | 
 **tankSilo** | **bool** | Boolean indicating whether the results should be filtered to only return tank/silo results. | 
 **plcName** | **string** | The PLC Name of the workcenter. 50 characters max. | 
 **ipAddress** | **string** | The IP Address of the workcenter. 15 characters max. | 

### Return type

[**[]ProductionOperationsManagementApiListWorkcentersItem**](ProductionOperationsManagementApiListWorkcentersItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductionOperationsManagementApiMoveTankContainers

> ProductionOperationsManagementApiMoveTankContainers202Response ProductionOperationsManagementApiMoveTankContainers(ctx).ProductionOperationsManagementApiMoveTankContainersRequest(productionOperationsManagementApiMoveTankContainersRequest).Execute()

Move Tank Containers



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
	productionOperationsManagementApiMoveTankContainersRequest := *openapiclient.NewProductionOperationsManagementApiMoveTankContainersRequest() // ProductionOperationsManagementApiMoveTankContainersRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiMoveTankContainers(context.Background()).ProductionOperationsManagementApiMoveTankContainersRequest(productionOperationsManagementApiMoveTankContainersRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiMoveTankContainers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductionOperationsManagementApiMoveTankContainers`: ProductionOperationsManagementApiMoveTankContainers202Response
	fmt.Fprintf(os.Stdout, "Response from `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiMoveTankContainers`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiMoveTankContainersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **productionOperationsManagementApiMoveTankContainersRequest** | [**ProductionOperationsManagementApiMoveTankContainersRequest**](ProductionOperationsManagementApiMoveTankContainersRequest.md) |  | 

### Return type

[**ProductionOperationsManagementApiMoveTankContainers202Response**](ProductionOperationsManagementApiMoveTankContainers202Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductionOperationsManagementApiRecordBatchProduction

> ProductionOperationsManagementApiRecordBatchProductionResponse ProductionOperationsManagementApiRecordBatchProduction(ctx, workcenterId).ProductionOperationsManagementApiRecordBatchProductionRequest(productionOperationsManagementApiRecordBatchProductionRequest).Execute()

Record Batch Production



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
	workcenterId := "00000000-0000-0000-0000-000000000000" // string | The workcenter ID.
	productionOperationsManagementApiRecordBatchProductionRequest := *openapiclient.NewProductionOperationsManagementApiRecordBatchProductionRequest() // ProductionOperationsManagementApiRecordBatchProductionRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiRecordBatchProduction(context.Background(), workcenterId).ProductionOperationsManagementApiRecordBatchProductionRequest(productionOperationsManagementApiRecordBatchProductionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiRecordBatchProduction``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductionOperationsManagementApiRecordBatchProduction`: ProductionOperationsManagementApiRecordBatchProductionResponse
	fmt.Fprintf(os.Stdout, "Response from `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiRecordBatchProduction`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workcenterId** | **string** | The workcenter ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiRecordBatchProductionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **productionOperationsManagementApiRecordBatchProductionRequest** | [**ProductionOperationsManagementApiRecordBatchProductionRequest**](ProductionOperationsManagementApiRecordBatchProductionRequest.md) |  | 

### Return type

[**ProductionOperationsManagementApiRecordBatchProductionResponse**](ProductionOperationsManagementApiRecordBatchProductionResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductionOperationsManagementApiRecordVariableBOMProduction

> ProductionOperationsManagementApiRecordVariableBOMProductionResponse ProductionOperationsManagementApiRecordVariableBOMProduction(ctx, workcenterId).ProductionOperationsManagementApiRecordVariableBOMProductionRequest(productionOperationsManagementApiRecordVariableBOMProductionRequest).Execute()

Record Variable BOM Production



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
	workcenterId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier of the workcenter.
	productionOperationsManagementApiRecordVariableBOMProductionRequest := *openapiclient.NewProductionOperationsManagementApiRecordVariableBOMProductionRequest() // ProductionOperationsManagementApiRecordVariableBOMProductionRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiRecordVariableBOMProduction(context.Background(), workcenterId).ProductionOperationsManagementApiRecordVariableBOMProductionRequest(productionOperationsManagementApiRecordVariableBOMProductionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiRecordVariableBOMProduction``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductionOperationsManagementApiRecordVariableBOMProduction`: ProductionOperationsManagementApiRecordVariableBOMProductionResponse
	fmt.Fprintf(os.Stdout, "Response from `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiRecordVariableBOMProduction`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workcenterId** | **string** | A unique identifier of the workcenter. | 

### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiRecordVariableBOMProductionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **productionOperationsManagementApiRecordVariableBOMProductionRequest** | [**ProductionOperationsManagementApiRecordVariableBOMProductionRequest**](ProductionOperationsManagementApiRecordVariableBOMProductionRequest.md) |  | 

### Return type

[**ProductionOperationsManagementApiRecordVariableBOMProductionResponse**](ProductionOperationsManagementApiRecordVariableBOMProductionResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductionOperationsManagementApiSearchWorkcenterSetups

> []ProductionOperationsManagementApiSearchWorkcenterSetupsItem ProductionOperationsManagementApiSearchWorkcenterSetups(ctx).ProductionOperationsManagementApiSearchWorkcenterSetupsRequest(productionOperationsManagementApiSearchWorkcenterSetupsRequest).Execute()

Search Workcenter Setups



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
	productionOperationsManagementApiSearchWorkcenterSetupsRequest := *openapiclient.NewProductionOperationsManagementApiSearchWorkcenterSetupsRequest() // ProductionOperationsManagementApiSearchWorkcenterSetupsRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiSearchWorkcenterSetups(context.Background()).ProductionOperationsManagementApiSearchWorkcenterSetupsRequest(productionOperationsManagementApiSearchWorkcenterSetupsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiSearchWorkcenterSetups``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductionOperationsManagementApiSearchWorkcenterSetups`: []ProductionOperationsManagementApiSearchWorkcenterSetupsItem
	fmt.Fprintf(os.Stdout, "Response from `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiSearchWorkcenterSetups`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiSearchWorkcenterSetupsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **productionOperationsManagementApiSearchWorkcenterSetupsRequest** | [**ProductionOperationsManagementApiSearchWorkcenterSetupsRequest**](ProductionOperationsManagementApiSearchWorkcenterSetupsRequest.md) |  | 

### Return type

[**[]ProductionOperationsManagementApiSearchWorkcenterSetupsItem**](ProductionOperationsManagementApiSearchWorkcenterSetupsItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductionOperationsManagementApiSetWorkcenterStatus

> ProductionOperationsManagementApiSetWorkcenterStatusResponse ProductionOperationsManagementApiSetWorkcenterStatus(ctx, workcenterId).ProductionOperationsManagementApiSetWorkcenterStatusRequest(productionOperationsManagementApiSetWorkcenterStatusRequest).Execute()

Set Workcenter Status



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
	workcenterId := "00000000-0000-0000-0000-000000000000" // string | 
	productionOperationsManagementApiSetWorkcenterStatusRequest := *openapiclient.NewProductionOperationsManagementApiSetWorkcenterStatusRequest() // ProductionOperationsManagementApiSetWorkcenterStatusRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiSetWorkcenterStatus(context.Background(), workcenterId).ProductionOperationsManagementApiSetWorkcenterStatusRequest(productionOperationsManagementApiSetWorkcenterStatusRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiSetWorkcenterStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductionOperationsManagementApiSetWorkcenterStatus`: ProductionOperationsManagementApiSetWorkcenterStatusResponse
	fmt.Fprintf(os.Stdout, "Response from `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiSetWorkcenterStatus`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workcenterId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiSetWorkcenterStatusRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **productionOperationsManagementApiSetWorkcenterStatusRequest** | [**ProductionOperationsManagementApiSetWorkcenterStatusRequest**](ProductionOperationsManagementApiSetWorkcenterStatusRequest.md) |  | 

### Return type

[**ProductionOperationsManagementApiSetWorkcenterStatusResponse**](ProductionOperationsManagementApiSetWorkcenterStatusResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductionOperationsManagementApiSetupJob

> ProductionOperationsManagementApiSetupJobResponse ProductionOperationsManagementApiSetupJob(ctx, workcenterId).ProductionOperationsManagementApiSetupJobRequest(productionOperationsManagementApiSetupJobRequest).Execute()

Setup Job



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
	workcenterId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier of the workcenter.
	productionOperationsManagementApiSetupJobRequest := *openapiclient.NewProductionOperationsManagementApiSetupJobRequest() // ProductionOperationsManagementApiSetupJobRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiSetupJob(context.Background(), workcenterId).ProductionOperationsManagementApiSetupJobRequest(productionOperationsManagementApiSetupJobRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiSetupJob``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductionOperationsManagementApiSetupJob`: ProductionOperationsManagementApiSetupJobResponse
	fmt.Fprintf(os.Stdout, "Response from `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiSetupJob`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workcenterId** | **string** | A unique identifier of the workcenter. | 

### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiSetupJobRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **productionOperationsManagementApiSetupJobRequest** | [**ProductionOperationsManagementApiSetupJobRequest**](ProductionOperationsManagementApiSetupJobRequest.md) |  | 

### Return type

[**ProductionOperationsManagementApiSetupJobResponse**](ProductionOperationsManagementApiSetupJobResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductionOperationsManagementApiUnloadAllSourceInventory

> ProductionOperationsManagementApiUnloadAllSourceInventory(ctx, workcenterId).Execute()

Unload All Source Inventory



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
	workcenterId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier of the workcenter.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiUnloadAllSourceInventory(context.Background(), workcenterId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiUnloadAllSourceInventory``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workcenterId** | **string** | A unique identifier of the workcenter. | 

### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiUnloadAllSourceInventoryRequest struct via the builder pattern


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


## ProductionOperationsManagementApiUnloadSourceInventoryBySerialNo

> []ProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem ProductionOperationsManagementApiUnloadSourceInventoryBySerialNo(ctx, workcenterId, serialNo).Execute()

Unload Source Inventory By Serial No



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
	workcenterId := "00000000-0000-0000-0000-000000000000" // string | A unique identifier of the workcenter.
	serialNo := "string" // string | A serial number of a part container.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiUnloadSourceInventoryBySerialNo(context.Background(), workcenterId, serialNo).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiUnloadSourceInventoryBySerialNo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductionOperationsManagementApiUnloadSourceInventoryBySerialNo`: []ProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem
	fmt.Fprintf(os.Stdout, "Response from `ProductionOperationsManagementAPIAPI.ProductionOperationsManagementApiUnloadSourceInventoryBySerialNo`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workcenterId** | **string** | A unique identifier of the workcenter. | 
**serialNo** | **string** | A serial number of a part container. | 

### Other Parameters

Other parameters are passed through a pointer to a apiProductionOperationsManagementApiUnloadSourceInventoryBySerialNoRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**[]ProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem**](ProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

