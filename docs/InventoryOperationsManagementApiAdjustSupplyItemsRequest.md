# InventoryOperationsManagementApiAdjustSupplyItemsRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AdjustmentType** | Pointer to **string** | The Adjustment Transaction Type | [optional] 
**Adjustments** | Pointer to [**[]AdjustmentsItem**](AdjustmentsItem.md) | The Adjustments | [optional] 
**ItemId** | Pointer to **string** | The Item Resource Id | [optional] 
**LocationId** | Pointer to **string** | The Location Resource Id | [optional] 
**Quantity** | Pointer to **float64** | The Adjusted Quantity | [optional] 

## Methods

### NewInventoryOperationsManagementApiAdjustSupplyItemsRequest

`func NewInventoryOperationsManagementApiAdjustSupplyItemsRequest() *InventoryOperationsManagementApiAdjustSupplyItemsRequest`

NewInventoryOperationsManagementApiAdjustSupplyItemsRequest instantiates a new InventoryOperationsManagementApiAdjustSupplyItemsRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInventoryOperationsManagementApiAdjustSupplyItemsRequestWithDefaults

`func NewInventoryOperationsManagementApiAdjustSupplyItemsRequestWithDefaults() *InventoryOperationsManagementApiAdjustSupplyItemsRequest`

NewInventoryOperationsManagementApiAdjustSupplyItemsRequestWithDefaults instantiates a new InventoryOperationsManagementApiAdjustSupplyItemsRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAdjustmentType

`func (o *InventoryOperationsManagementApiAdjustSupplyItemsRequest) GetAdjustmentType() string`

GetAdjustmentType returns the AdjustmentType field if non-nil, zero value otherwise.

### GetAdjustmentTypeOk

`func (o *InventoryOperationsManagementApiAdjustSupplyItemsRequest) GetAdjustmentTypeOk() (*string, bool)`

GetAdjustmentTypeOk returns a tuple with the AdjustmentType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdjustmentType

`func (o *InventoryOperationsManagementApiAdjustSupplyItemsRequest) SetAdjustmentType(v string)`

SetAdjustmentType sets AdjustmentType field to given value.

### HasAdjustmentType

`func (o *InventoryOperationsManagementApiAdjustSupplyItemsRequest) HasAdjustmentType() bool`

HasAdjustmentType returns a boolean if a field has been set.

### GetAdjustments

`func (o *InventoryOperationsManagementApiAdjustSupplyItemsRequest) GetAdjustments() []AdjustmentsItem`

GetAdjustments returns the Adjustments field if non-nil, zero value otherwise.

### GetAdjustmentsOk

`func (o *InventoryOperationsManagementApiAdjustSupplyItemsRequest) GetAdjustmentsOk() (*[]AdjustmentsItem, bool)`

GetAdjustmentsOk returns a tuple with the Adjustments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdjustments

`func (o *InventoryOperationsManagementApiAdjustSupplyItemsRequest) SetAdjustments(v []AdjustmentsItem)`

SetAdjustments sets Adjustments field to given value.

### HasAdjustments

`func (o *InventoryOperationsManagementApiAdjustSupplyItemsRequest) HasAdjustments() bool`

HasAdjustments returns a boolean if a field has been set.

### GetItemId

`func (o *InventoryOperationsManagementApiAdjustSupplyItemsRequest) GetItemId() string`

GetItemId returns the ItemId field if non-nil, zero value otherwise.

### GetItemIdOk

`func (o *InventoryOperationsManagementApiAdjustSupplyItemsRequest) GetItemIdOk() (*string, bool)`

GetItemIdOk returns a tuple with the ItemId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItemId

`func (o *InventoryOperationsManagementApiAdjustSupplyItemsRequest) SetItemId(v string)`

SetItemId sets ItemId field to given value.

### HasItemId

`func (o *InventoryOperationsManagementApiAdjustSupplyItemsRequest) HasItemId() bool`

HasItemId returns a boolean if a field has been set.

### GetLocationId

`func (o *InventoryOperationsManagementApiAdjustSupplyItemsRequest) GetLocationId() string`

GetLocationId returns the LocationId field if non-nil, zero value otherwise.

### GetLocationIdOk

`func (o *InventoryOperationsManagementApiAdjustSupplyItemsRequest) GetLocationIdOk() (*string, bool)`

GetLocationIdOk returns a tuple with the LocationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocationId

`func (o *InventoryOperationsManagementApiAdjustSupplyItemsRequest) SetLocationId(v string)`

SetLocationId sets LocationId field to given value.

### HasLocationId

`func (o *InventoryOperationsManagementApiAdjustSupplyItemsRequest) HasLocationId() bool`

HasLocationId returns a boolean if a field has been set.

### GetQuantity

`func (o *InventoryOperationsManagementApiAdjustSupplyItemsRequest) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *InventoryOperationsManagementApiAdjustSupplyItemsRequest) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *InventoryOperationsManagementApiAdjustSupplyItemsRequest) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *InventoryOperationsManagementApiAdjustSupplyItemsRequest) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


