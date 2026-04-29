# BatchComponentQuantitiesItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PartId** | Pointer to **string** | A unique identifier of a part. If no SupplyItemId is provided, this is required. | [optional] 
**Quantity** | Pointer to **float64** | Quantity to be depleted from source. | [optional] 
**SupplyItemId** | Pointer to **string** | A unique identifier of a supply item. If no PartId is provided, this is required. | [optional] 

## Methods

### NewBatchComponentQuantitiesItem

`func NewBatchComponentQuantitiesItem() *BatchComponentQuantitiesItem`

NewBatchComponentQuantitiesItem instantiates a new BatchComponentQuantitiesItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBatchComponentQuantitiesItemWithDefaults

`func NewBatchComponentQuantitiesItemWithDefaults() *BatchComponentQuantitiesItem`

NewBatchComponentQuantitiesItemWithDefaults instantiates a new BatchComponentQuantitiesItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPartId

`func (o *BatchComponentQuantitiesItem) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *BatchComponentQuantitiesItem) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *BatchComponentQuantitiesItem) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *BatchComponentQuantitiesItem) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetQuantity

`func (o *BatchComponentQuantitiesItem) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *BatchComponentQuantitiesItem) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *BatchComponentQuantitiesItem) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *BatchComponentQuantitiesItem) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetSupplyItemId

`func (o *BatchComponentQuantitiesItem) GetSupplyItemId() string`

GetSupplyItemId returns the SupplyItemId field if non-nil, zero value otherwise.

### GetSupplyItemIdOk

`func (o *BatchComponentQuantitiesItem) GetSupplyItemIdOk() (*string, bool)`

GetSupplyItemIdOk returns a tuple with the SupplyItemId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplyItemId

`func (o *BatchComponentQuantitiesItem) SetSupplyItemId(v string)`

SetSupplyItemId sets SupplyItemId field to given value.

### HasSupplyItemId

`func (o *BatchComponentQuantitiesItem) HasSupplyItemId() bool`

HasSupplyItemId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


