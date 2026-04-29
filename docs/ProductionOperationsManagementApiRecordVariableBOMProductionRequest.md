# ProductionOperationsManagementApiRecordVariableBOMProductionRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SourceComponentQuantities** | Pointer to [**[]SourceComponentQuantitiesItem**](SourceComponentQuantitiesItem.md) | The list of source components to add to the batch. | [optional] 
**Quantity** | Pointer to **float64** | The source component quantity. | [optional] 
**JobOpId** | Pointer to **string** | A unique identifier for the job op on the workcenter. | [optional] 
**CompleteContainer** | Pointer to **bool** | Flag indicating if the output container should be finalized. | [optional] 
**PartId** | Pointer to **string** | A unique identifier for a part. | [optional] 
**ItemId** | Pointer to **string** | A unique identifier for a supply item. | [optional] 

## Methods

### NewProductionOperationsManagementApiRecordVariableBOMProductionRequest

`func NewProductionOperationsManagementApiRecordVariableBOMProductionRequest() *ProductionOperationsManagementApiRecordVariableBOMProductionRequest`

NewProductionOperationsManagementApiRecordVariableBOMProductionRequest instantiates a new ProductionOperationsManagementApiRecordVariableBOMProductionRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductionOperationsManagementApiRecordVariableBOMProductionRequestWithDefaults

`func NewProductionOperationsManagementApiRecordVariableBOMProductionRequestWithDefaults() *ProductionOperationsManagementApiRecordVariableBOMProductionRequest`

NewProductionOperationsManagementApiRecordVariableBOMProductionRequestWithDefaults instantiates a new ProductionOperationsManagementApiRecordVariableBOMProductionRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSourceComponentQuantities

`func (o *ProductionOperationsManagementApiRecordVariableBOMProductionRequest) GetSourceComponentQuantities() []SourceComponentQuantitiesItem`

GetSourceComponentQuantities returns the SourceComponentQuantities field if non-nil, zero value otherwise.

### GetSourceComponentQuantitiesOk

`func (o *ProductionOperationsManagementApiRecordVariableBOMProductionRequest) GetSourceComponentQuantitiesOk() (*[]SourceComponentQuantitiesItem, bool)`

GetSourceComponentQuantitiesOk returns a tuple with the SourceComponentQuantities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceComponentQuantities

`func (o *ProductionOperationsManagementApiRecordVariableBOMProductionRequest) SetSourceComponentQuantities(v []SourceComponentQuantitiesItem)`

SetSourceComponentQuantities sets SourceComponentQuantities field to given value.

### HasSourceComponentQuantities

`func (o *ProductionOperationsManagementApiRecordVariableBOMProductionRequest) HasSourceComponentQuantities() bool`

HasSourceComponentQuantities returns a boolean if a field has been set.

### GetQuantity

`func (o *ProductionOperationsManagementApiRecordVariableBOMProductionRequest) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *ProductionOperationsManagementApiRecordVariableBOMProductionRequest) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *ProductionOperationsManagementApiRecordVariableBOMProductionRequest) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *ProductionOperationsManagementApiRecordVariableBOMProductionRequest) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetJobOpId

`func (o *ProductionOperationsManagementApiRecordVariableBOMProductionRequest) GetJobOpId() string`

GetJobOpId returns the JobOpId field if non-nil, zero value otherwise.

### GetJobOpIdOk

`func (o *ProductionOperationsManagementApiRecordVariableBOMProductionRequest) GetJobOpIdOk() (*string, bool)`

GetJobOpIdOk returns a tuple with the JobOpId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobOpId

`func (o *ProductionOperationsManagementApiRecordVariableBOMProductionRequest) SetJobOpId(v string)`

SetJobOpId sets JobOpId field to given value.

### HasJobOpId

`func (o *ProductionOperationsManagementApiRecordVariableBOMProductionRequest) HasJobOpId() bool`

HasJobOpId returns a boolean if a field has been set.

### GetCompleteContainer

`func (o *ProductionOperationsManagementApiRecordVariableBOMProductionRequest) GetCompleteContainer() bool`

GetCompleteContainer returns the CompleteContainer field if non-nil, zero value otherwise.

### GetCompleteContainerOk

`func (o *ProductionOperationsManagementApiRecordVariableBOMProductionRequest) GetCompleteContainerOk() (*bool, bool)`

GetCompleteContainerOk returns a tuple with the CompleteContainer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompleteContainer

`func (o *ProductionOperationsManagementApiRecordVariableBOMProductionRequest) SetCompleteContainer(v bool)`

SetCompleteContainer sets CompleteContainer field to given value.

### HasCompleteContainer

`func (o *ProductionOperationsManagementApiRecordVariableBOMProductionRequest) HasCompleteContainer() bool`

HasCompleteContainer returns a boolean if a field has been set.

### GetPartId

`func (o *ProductionOperationsManagementApiRecordVariableBOMProductionRequest) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *ProductionOperationsManagementApiRecordVariableBOMProductionRequest) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *ProductionOperationsManagementApiRecordVariableBOMProductionRequest) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *ProductionOperationsManagementApiRecordVariableBOMProductionRequest) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetItemId

`func (o *ProductionOperationsManagementApiRecordVariableBOMProductionRequest) GetItemId() string`

GetItemId returns the ItemId field if non-nil, zero value otherwise.

### GetItemIdOk

`func (o *ProductionOperationsManagementApiRecordVariableBOMProductionRequest) GetItemIdOk() (*string, bool)`

GetItemIdOk returns a tuple with the ItemId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItemId

`func (o *ProductionOperationsManagementApiRecordVariableBOMProductionRequest) SetItemId(v string)`

SetItemId sets ItemId field to given value.

### HasItemId

`func (o *ProductionOperationsManagementApiRecordVariableBOMProductionRequest) HasItemId() bool`

HasItemId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


