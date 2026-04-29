# ProductionOperationsManagementApiGetRequiredSourceInventoryItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PartId** | Pointer to **string** | A unique identifier for the part. | [optional] 
**PartOperationId** | Pointer to **string** | A unique identifier for the part operation. | [optional] 
**SupplyItemId** | Pointer to **string** | A unique identifier for a supply item. | [optional] 
**Loaded** | Pointer to **bool** | Flag indicating if the required source inventory has been loaded. | [optional] 
**TotalLoaded** | Pointer to **float64** | The quantity of the source inventory that has been loaded. | [optional] 
**TotalYield** | Pointer to **float64** | The total yield of the loaded source inventory. | [optional] 
**BomQuantity** | Pointer to **float64** | The quantity of the source inventory that is required per unit of production. | [optional] 
**SourceType** | Pointer to **string** | The source inventory type. | [optional] 
**Name** | Pointer to **string** | The source inventory name. | [optional] 

## Methods

### NewProductionOperationsManagementApiGetRequiredSourceInventoryItem

`func NewProductionOperationsManagementApiGetRequiredSourceInventoryItem() *ProductionOperationsManagementApiGetRequiredSourceInventoryItem`

NewProductionOperationsManagementApiGetRequiredSourceInventoryItem instantiates a new ProductionOperationsManagementApiGetRequiredSourceInventoryItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductionOperationsManagementApiGetRequiredSourceInventoryItemWithDefaults

`func NewProductionOperationsManagementApiGetRequiredSourceInventoryItemWithDefaults() *ProductionOperationsManagementApiGetRequiredSourceInventoryItem`

NewProductionOperationsManagementApiGetRequiredSourceInventoryItemWithDefaults instantiates a new ProductionOperationsManagementApiGetRequiredSourceInventoryItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPartId

`func (o *ProductionOperationsManagementApiGetRequiredSourceInventoryItem) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *ProductionOperationsManagementApiGetRequiredSourceInventoryItem) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *ProductionOperationsManagementApiGetRequiredSourceInventoryItem) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *ProductionOperationsManagementApiGetRequiredSourceInventoryItem) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetPartOperationId

`func (o *ProductionOperationsManagementApiGetRequiredSourceInventoryItem) GetPartOperationId() string`

GetPartOperationId returns the PartOperationId field if non-nil, zero value otherwise.

### GetPartOperationIdOk

`func (o *ProductionOperationsManagementApiGetRequiredSourceInventoryItem) GetPartOperationIdOk() (*string, bool)`

GetPartOperationIdOk returns a tuple with the PartOperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartOperationId

`func (o *ProductionOperationsManagementApiGetRequiredSourceInventoryItem) SetPartOperationId(v string)`

SetPartOperationId sets PartOperationId field to given value.

### HasPartOperationId

`func (o *ProductionOperationsManagementApiGetRequiredSourceInventoryItem) HasPartOperationId() bool`

HasPartOperationId returns a boolean if a field has been set.

### GetSupplyItemId

`func (o *ProductionOperationsManagementApiGetRequiredSourceInventoryItem) GetSupplyItemId() string`

GetSupplyItemId returns the SupplyItemId field if non-nil, zero value otherwise.

### GetSupplyItemIdOk

`func (o *ProductionOperationsManagementApiGetRequiredSourceInventoryItem) GetSupplyItemIdOk() (*string, bool)`

GetSupplyItemIdOk returns a tuple with the SupplyItemId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplyItemId

`func (o *ProductionOperationsManagementApiGetRequiredSourceInventoryItem) SetSupplyItemId(v string)`

SetSupplyItemId sets SupplyItemId field to given value.

### HasSupplyItemId

`func (o *ProductionOperationsManagementApiGetRequiredSourceInventoryItem) HasSupplyItemId() bool`

HasSupplyItemId returns a boolean if a field has been set.

### GetLoaded

`func (o *ProductionOperationsManagementApiGetRequiredSourceInventoryItem) GetLoaded() bool`

GetLoaded returns the Loaded field if non-nil, zero value otherwise.

### GetLoadedOk

`func (o *ProductionOperationsManagementApiGetRequiredSourceInventoryItem) GetLoadedOk() (*bool, bool)`

GetLoadedOk returns a tuple with the Loaded field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLoaded

`func (o *ProductionOperationsManagementApiGetRequiredSourceInventoryItem) SetLoaded(v bool)`

SetLoaded sets Loaded field to given value.

### HasLoaded

`func (o *ProductionOperationsManagementApiGetRequiredSourceInventoryItem) HasLoaded() bool`

HasLoaded returns a boolean if a field has been set.

### GetTotalLoaded

`func (o *ProductionOperationsManagementApiGetRequiredSourceInventoryItem) GetTotalLoaded() float64`

GetTotalLoaded returns the TotalLoaded field if non-nil, zero value otherwise.

### GetTotalLoadedOk

`func (o *ProductionOperationsManagementApiGetRequiredSourceInventoryItem) GetTotalLoadedOk() (*float64, bool)`

GetTotalLoadedOk returns a tuple with the TotalLoaded field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalLoaded

`func (o *ProductionOperationsManagementApiGetRequiredSourceInventoryItem) SetTotalLoaded(v float64)`

SetTotalLoaded sets TotalLoaded field to given value.

### HasTotalLoaded

`func (o *ProductionOperationsManagementApiGetRequiredSourceInventoryItem) HasTotalLoaded() bool`

HasTotalLoaded returns a boolean if a field has been set.

### GetTotalYield

`func (o *ProductionOperationsManagementApiGetRequiredSourceInventoryItem) GetTotalYield() float64`

GetTotalYield returns the TotalYield field if non-nil, zero value otherwise.

### GetTotalYieldOk

`func (o *ProductionOperationsManagementApiGetRequiredSourceInventoryItem) GetTotalYieldOk() (*float64, bool)`

GetTotalYieldOk returns a tuple with the TotalYield field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalYield

`func (o *ProductionOperationsManagementApiGetRequiredSourceInventoryItem) SetTotalYield(v float64)`

SetTotalYield sets TotalYield field to given value.

### HasTotalYield

`func (o *ProductionOperationsManagementApiGetRequiredSourceInventoryItem) HasTotalYield() bool`

HasTotalYield returns a boolean if a field has been set.

### GetBomQuantity

`func (o *ProductionOperationsManagementApiGetRequiredSourceInventoryItem) GetBomQuantity() float64`

GetBomQuantity returns the BomQuantity field if non-nil, zero value otherwise.

### GetBomQuantityOk

`func (o *ProductionOperationsManagementApiGetRequiredSourceInventoryItem) GetBomQuantityOk() (*float64, bool)`

GetBomQuantityOk returns a tuple with the BomQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBomQuantity

`func (o *ProductionOperationsManagementApiGetRequiredSourceInventoryItem) SetBomQuantity(v float64)`

SetBomQuantity sets BomQuantity field to given value.

### HasBomQuantity

`func (o *ProductionOperationsManagementApiGetRequiredSourceInventoryItem) HasBomQuantity() bool`

HasBomQuantity returns a boolean if a field has been set.

### GetSourceType

`func (o *ProductionOperationsManagementApiGetRequiredSourceInventoryItem) GetSourceType() string`

GetSourceType returns the SourceType field if non-nil, zero value otherwise.

### GetSourceTypeOk

`func (o *ProductionOperationsManagementApiGetRequiredSourceInventoryItem) GetSourceTypeOk() (*string, bool)`

GetSourceTypeOk returns a tuple with the SourceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceType

`func (o *ProductionOperationsManagementApiGetRequiredSourceInventoryItem) SetSourceType(v string)`

SetSourceType sets SourceType field to given value.

### HasSourceType

`func (o *ProductionOperationsManagementApiGetRequiredSourceInventoryItem) HasSourceType() bool`

HasSourceType returns a boolean if a field has been set.

### GetName

`func (o *ProductionOperationsManagementApiGetRequiredSourceInventoryItem) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ProductionOperationsManagementApiGetRequiredSourceInventoryItem) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ProductionOperationsManagementApiGetRequiredSourceInventoryItem) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ProductionOperationsManagementApiGetRequiredSourceInventoryItem) HasName() bool`

HasName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


