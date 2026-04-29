# ProductionOperationsManagementApiRecordBatchProductionRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BatchId** | Pointer to **string** | A unique identifier of the batch. | [optional] 
**BatchComponentQuantities** | Pointer to [**[]BatchComponentQuantitiesItem**](BatchComponentQuantitiesItem.md) | List of Batch Component Sources. | [optional] 
**OperatorId** | Pointer to **string** | A unique identifier of an IAM account used to indicate what user is recording production. If no value is provided the IAM account associated with the API Key will be used. | [optional] 
**Quantity** | Pointer to **float64** | Quantity to be depleted from source. | [optional] 
**LotId** | Pointer to **string** | A unique identifier of a lot that is being produced for. | [optional] 
**LocationId** | Pointer to **string** | A unique identifier of a location that is being produced to. | [optional] 
**PartId** | Pointer to **string** | A unique identifier of a part. If no SupplyItemId is provided, this is required. | [optional] 
**SupplyItemId** | Pointer to **string** | A unique identifier of a supply item. If no PartId is provided, this is required. | [optional] 

## Methods

### NewProductionOperationsManagementApiRecordBatchProductionRequest

`func NewProductionOperationsManagementApiRecordBatchProductionRequest() *ProductionOperationsManagementApiRecordBatchProductionRequest`

NewProductionOperationsManagementApiRecordBatchProductionRequest instantiates a new ProductionOperationsManagementApiRecordBatchProductionRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductionOperationsManagementApiRecordBatchProductionRequestWithDefaults

`func NewProductionOperationsManagementApiRecordBatchProductionRequestWithDefaults() *ProductionOperationsManagementApiRecordBatchProductionRequest`

NewProductionOperationsManagementApiRecordBatchProductionRequestWithDefaults instantiates a new ProductionOperationsManagementApiRecordBatchProductionRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBatchId

`func (o *ProductionOperationsManagementApiRecordBatchProductionRequest) GetBatchId() string`

GetBatchId returns the BatchId field if non-nil, zero value otherwise.

### GetBatchIdOk

`func (o *ProductionOperationsManagementApiRecordBatchProductionRequest) GetBatchIdOk() (*string, bool)`

GetBatchIdOk returns a tuple with the BatchId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBatchId

`func (o *ProductionOperationsManagementApiRecordBatchProductionRequest) SetBatchId(v string)`

SetBatchId sets BatchId field to given value.

### HasBatchId

`func (o *ProductionOperationsManagementApiRecordBatchProductionRequest) HasBatchId() bool`

HasBatchId returns a boolean if a field has been set.

### GetBatchComponentQuantities

`func (o *ProductionOperationsManagementApiRecordBatchProductionRequest) GetBatchComponentQuantities() []BatchComponentQuantitiesItem`

GetBatchComponentQuantities returns the BatchComponentQuantities field if non-nil, zero value otherwise.

### GetBatchComponentQuantitiesOk

`func (o *ProductionOperationsManagementApiRecordBatchProductionRequest) GetBatchComponentQuantitiesOk() (*[]BatchComponentQuantitiesItem, bool)`

GetBatchComponentQuantitiesOk returns a tuple with the BatchComponentQuantities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBatchComponentQuantities

`func (o *ProductionOperationsManagementApiRecordBatchProductionRequest) SetBatchComponentQuantities(v []BatchComponentQuantitiesItem)`

SetBatchComponentQuantities sets BatchComponentQuantities field to given value.

### HasBatchComponentQuantities

`func (o *ProductionOperationsManagementApiRecordBatchProductionRequest) HasBatchComponentQuantities() bool`

HasBatchComponentQuantities returns a boolean if a field has been set.

### GetOperatorId

`func (o *ProductionOperationsManagementApiRecordBatchProductionRequest) GetOperatorId() string`

GetOperatorId returns the OperatorId field if non-nil, zero value otherwise.

### GetOperatorIdOk

`func (o *ProductionOperationsManagementApiRecordBatchProductionRequest) GetOperatorIdOk() (*string, bool)`

GetOperatorIdOk returns a tuple with the OperatorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperatorId

`func (o *ProductionOperationsManagementApiRecordBatchProductionRequest) SetOperatorId(v string)`

SetOperatorId sets OperatorId field to given value.

### HasOperatorId

`func (o *ProductionOperationsManagementApiRecordBatchProductionRequest) HasOperatorId() bool`

HasOperatorId returns a boolean if a field has been set.

### GetQuantity

`func (o *ProductionOperationsManagementApiRecordBatchProductionRequest) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *ProductionOperationsManagementApiRecordBatchProductionRequest) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *ProductionOperationsManagementApiRecordBatchProductionRequest) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *ProductionOperationsManagementApiRecordBatchProductionRequest) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetLotId

`func (o *ProductionOperationsManagementApiRecordBatchProductionRequest) GetLotId() string`

GetLotId returns the LotId field if non-nil, zero value otherwise.

### GetLotIdOk

`func (o *ProductionOperationsManagementApiRecordBatchProductionRequest) GetLotIdOk() (*string, bool)`

GetLotIdOk returns a tuple with the LotId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLotId

`func (o *ProductionOperationsManagementApiRecordBatchProductionRequest) SetLotId(v string)`

SetLotId sets LotId field to given value.

### HasLotId

`func (o *ProductionOperationsManagementApiRecordBatchProductionRequest) HasLotId() bool`

HasLotId returns a boolean if a field has been set.

### GetLocationId

`func (o *ProductionOperationsManagementApiRecordBatchProductionRequest) GetLocationId() string`

GetLocationId returns the LocationId field if non-nil, zero value otherwise.

### GetLocationIdOk

`func (o *ProductionOperationsManagementApiRecordBatchProductionRequest) GetLocationIdOk() (*string, bool)`

GetLocationIdOk returns a tuple with the LocationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocationId

`func (o *ProductionOperationsManagementApiRecordBatchProductionRequest) SetLocationId(v string)`

SetLocationId sets LocationId field to given value.

### HasLocationId

`func (o *ProductionOperationsManagementApiRecordBatchProductionRequest) HasLocationId() bool`

HasLocationId returns a boolean if a field has been set.

### GetPartId

`func (o *ProductionOperationsManagementApiRecordBatchProductionRequest) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *ProductionOperationsManagementApiRecordBatchProductionRequest) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *ProductionOperationsManagementApiRecordBatchProductionRequest) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *ProductionOperationsManagementApiRecordBatchProductionRequest) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetSupplyItemId

`func (o *ProductionOperationsManagementApiRecordBatchProductionRequest) GetSupplyItemId() string`

GetSupplyItemId returns the SupplyItemId field if non-nil, zero value otherwise.

### GetSupplyItemIdOk

`func (o *ProductionOperationsManagementApiRecordBatchProductionRequest) GetSupplyItemIdOk() (*string, bool)`

GetSupplyItemIdOk returns a tuple with the SupplyItemId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplyItemId

`func (o *ProductionOperationsManagementApiRecordBatchProductionRequest) SetSupplyItemId(v string)`

SetSupplyItemId sets SupplyItemId field to given value.

### HasSupplyItemId

`func (o *ProductionOperationsManagementApiRecordBatchProductionRequest) HasSupplyItemId() bool`

HasSupplyItemId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


