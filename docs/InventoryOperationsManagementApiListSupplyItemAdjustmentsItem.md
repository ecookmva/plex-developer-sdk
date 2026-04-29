# InventoryOperationsManagementApiListSupplyItemAdjustmentsItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AdjustmentDate** | Pointer to **time.Time** | The Item Adjustment Date. | [optional] 
**ItemId** | Pointer to **string** | The unique identifier for the Item Adjustment. | [optional] 
**ItemNo** | Pointer to **string** | The Item No. | [optional] 
**Location** | Pointer to **string** | The Location of the Item Adjustment. | [optional] 
**LocationId** | Pointer to **string** | The unique identifier for the Location. | [optional] 
**Quantity** | Pointer to **float64** | The Item Adjustment Quantity. | [optional] 
**TransactionType** | Pointer to **string** | The Transaction Type for the Item Adjustment. | [optional] 

## Methods

### NewInventoryOperationsManagementApiListSupplyItemAdjustmentsItem

`func NewInventoryOperationsManagementApiListSupplyItemAdjustmentsItem() *InventoryOperationsManagementApiListSupplyItemAdjustmentsItem`

NewInventoryOperationsManagementApiListSupplyItemAdjustmentsItem instantiates a new InventoryOperationsManagementApiListSupplyItemAdjustmentsItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInventoryOperationsManagementApiListSupplyItemAdjustmentsItemWithDefaults

`func NewInventoryOperationsManagementApiListSupplyItemAdjustmentsItemWithDefaults() *InventoryOperationsManagementApiListSupplyItemAdjustmentsItem`

NewInventoryOperationsManagementApiListSupplyItemAdjustmentsItemWithDefaults instantiates a new InventoryOperationsManagementApiListSupplyItemAdjustmentsItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAdjustmentDate

`func (o *InventoryOperationsManagementApiListSupplyItemAdjustmentsItem) GetAdjustmentDate() time.Time`

GetAdjustmentDate returns the AdjustmentDate field if non-nil, zero value otherwise.

### GetAdjustmentDateOk

`func (o *InventoryOperationsManagementApiListSupplyItemAdjustmentsItem) GetAdjustmentDateOk() (*time.Time, bool)`

GetAdjustmentDateOk returns a tuple with the AdjustmentDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdjustmentDate

`func (o *InventoryOperationsManagementApiListSupplyItemAdjustmentsItem) SetAdjustmentDate(v time.Time)`

SetAdjustmentDate sets AdjustmentDate field to given value.

### HasAdjustmentDate

`func (o *InventoryOperationsManagementApiListSupplyItemAdjustmentsItem) HasAdjustmentDate() bool`

HasAdjustmentDate returns a boolean if a field has been set.

### GetItemId

`func (o *InventoryOperationsManagementApiListSupplyItemAdjustmentsItem) GetItemId() string`

GetItemId returns the ItemId field if non-nil, zero value otherwise.

### GetItemIdOk

`func (o *InventoryOperationsManagementApiListSupplyItemAdjustmentsItem) GetItemIdOk() (*string, bool)`

GetItemIdOk returns a tuple with the ItemId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItemId

`func (o *InventoryOperationsManagementApiListSupplyItemAdjustmentsItem) SetItemId(v string)`

SetItemId sets ItemId field to given value.

### HasItemId

`func (o *InventoryOperationsManagementApiListSupplyItemAdjustmentsItem) HasItemId() bool`

HasItemId returns a boolean if a field has been set.

### GetItemNo

`func (o *InventoryOperationsManagementApiListSupplyItemAdjustmentsItem) GetItemNo() string`

GetItemNo returns the ItemNo field if non-nil, zero value otherwise.

### GetItemNoOk

`func (o *InventoryOperationsManagementApiListSupplyItemAdjustmentsItem) GetItemNoOk() (*string, bool)`

GetItemNoOk returns a tuple with the ItemNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItemNo

`func (o *InventoryOperationsManagementApiListSupplyItemAdjustmentsItem) SetItemNo(v string)`

SetItemNo sets ItemNo field to given value.

### HasItemNo

`func (o *InventoryOperationsManagementApiListSupplyItemAdjustmentsItem) HasItemNo() bool`

HasItemNo returns a boolean if a field has been set.

### GetLocation

`func (o *InventoryOperationsManagementApiListSupplyItemAdjustmentsItem) GetLocation() string`

GetLocation returns the Location field if non-nil, zero value otherwise.

### GetLocationOk

`func (o *InventoryOperationsManagementApiListSupplyItemAdjustmentsItem) GetLocationOk() (*string, bool)`

GetLocationOk returns a tuple with the Location field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocation

`func (o *InventoryOperationsManagementApiListSupplyItemAdjustmentsItem) SetLocation(v string)`

SetLocation sets Location field to given value.

### HasLocation

`func (o *InventoryOperationsManagementApiListSupplyItemAdjustmentsItem) HasLocation() bool`

HasLocation returns a boolean if a field has been set.

### GetLocationId

`func (o *InventoryOperationsManagementApiListSupplyItemAdjustmentsItem) GetLocationId() string`

GetLocationId returns the LocationId field if non-nil, zero value otherwise.

### GetLocationIdOk

`func (o *InventoryOperationsManagementApiListSupplyItemAdjustmentsItem) GetLocationIdOk() (*string, bool)`

GetLocationIdOk returns a tuple with the LocationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocationId

`func (o *InventoryOperationsManagementApiListSupplyItemAdjustmentsItem) SetLocationId(v string)`

SetLocationId sets LocationId field to given value.

### HasLocationId

`func (o *InventoryOperationsManagementApiListSupplyItemAdjustmentsItem) HasLocationId() bool`

HasLocationId returns a boolean if a field has been set.

### GetQuantity

`func (o *InventoryOperationsManagementApiListSupplyItemAdjustmentsItem) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *InventoryOperationsManagementApiListSupplyItemAdjustmentsItem) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *InventoryOperationsManagementApiListSupplyItemAdjustmentsItem) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *InventoryOperationsManagementApiListSupplyItemAdjustmentsItem) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetTransactionType

`func (o *InventoryOperationsManagementApiListSupplyItemAdjustmentsItem) GetTransactionType() string`

GetTransactionType returns the TransactionType field if non-nil, zero value otherwise.

### GetTransactionTypeOk

`func (o *InventoryOperationsManagementApiListSupplyItemAdjustmentsItem) GetTransactionTypeOk() (*string, bool)`

GetTransactionTypeOk returns a tuple with the TransactionType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransactionType

`func (o *InventoryOperationsManagementApiListSupplyItemAdjustmentsItem) SetTransactionType(v string)`

SetTransactionType sets TransactionType field to given value.

### HasTransactionType

`func (o *InventoryOperationsManagementApiListSupplyItemAdjustmentsItem) HasTransactionType() bool`

HasTransactionType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


