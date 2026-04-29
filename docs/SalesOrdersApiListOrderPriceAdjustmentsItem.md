# SalesOrdersApiListOrderPriceAdjustmentsItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OrderId** | Pointer to **string** | The ID of the Sales Order associated with the Price Adjustment. | [optional] 
**PriceAdjustmentId** | Pointer to **string** | The ID of the Price Adjustment. | [optional] 
**Amount** | Pointer to **float64** | The Amount of the Price Adjustment. | [optional] 
**SortOrder** | Pointer to **int32** | Determines the order in which Price Adjustments are applied to the Order Lines. | [optional] 

## Methods

### NewSalesOrdersApiListOrderPriceAdjustmentsItem

`func NewSalesOrdersApiListOrderPriceAdjustmentsItem() *SalesOrdersApiListOrderPriceAdjustmentsItem`

NewSalesOrdersApiListOrderPriceAdjustmentsItem instantiates a new SalesOrdersApiListOrderPriceAdjustmentsItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSalesOrdersApiListOrderPriceAdjustmentsItemWithDefaults

`func NewSalesOrdersApiListOrderPriceAdjustmentsItemWithDefaults() *SalesOrdersApiListOrderPriceAdjustmentsItem`

NewSalesOrdersApiListOrderPriceAdjustmentsItemWithDefaults instantiates a new SalesOrdersApiListOrderPriceAdjustmentsItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrderId

`func (o *SalesOrdersApiListOrderPriceAdjustmentsItem) GetOrderId() string`

GetOrderId returns the OrderId field if non-nil, zero value otherwise.

### GetOrderIdOk

`func (o *SalesOrdersApiListOrderPriceAdjustmentsItem) GetOrderIdOk() (*string, bool)`

GetOrderIdOk returns a tuple with the OrderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderId

`func (o *SalesOrdersApiListOrderPriceAdjustmentsItem) SetOrderId(v string)`

SetOrderId sets OrderId field to given value.

### HasOrderId

`func (o *SalesOrdersApiListOrderPriceAdjustmentsItem) HasOrderId() bool`

HasOrderId returns a boolean if a field has been set.

### GetPriceAdjustmentId

`func (o *SalesOrdersApiListOrderPriceAdjustmentsItem) GetPriceAdjustmentId() string`

GetPriceAdjustmentId returns the PriceAdjustmentId field if non-nil, zero value otherwise.

### GetPriceAdjustmentIdOk

`func (o *SalesOrdersApiListOrderPriceAdjustmentsItem) GetPriceAdjustmentIdOk() (*string, bool)`

GetPriceAdjustmentIdOk returns a tuple with the PriceAdjustmentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriceAdjustmentId

`func (o *SalesOrdersApiListOrderPriceAdjustmentsItem) SetPriceAdjustmentId(v string)`

SetPriceAdjustmentId sets PriceAdjustmentId field to given value.

### HasPriceAdjustmentId

`func (o *SalesOrdersApiListOrderPriceAdjustmentsItem) HasPriceAdjustmentId() bool`

HasPriceAdjustmentId returns a boolean if a field has been set.

### GetAmount

`func (o *SalesOrdersApiListOrderPriceAdjustmentsItem) GetAmount() float64`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *SalesOrdersApiListOrderPriceAdjustmentsItem) GetAmountOk() (*float64, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *SalesOrdersApiListOrderPriceAdjustmentsItem) SetAmount(v float64)`

SetAmount sets Amount field to given value.

### HasAmount

`func (o *SalesOrdersApiListOrderPriceAdjustmentsItem) HasAmount() bool`

HasAmount returns a boolean if a field has been set.

### GetSortOrder

`func (o *SalesOrdersApiListOrderPriceAdjustmentsItem) GetSortOrder() int32`

GetSortOrder returns the SortOrder field if non-nil, zero value otherwise.

### GetSortOrderOk

`func (o *SalesOrdersApiListOrderPriceAdjustmentsItem) GetSortOrderOk() (*int32, bool)`

GetSortOrderOk returns a tuple with the SortOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSortOrder

`func (o *SalesOrdersApiListOrderPriceAdjustmentsItem) SetSortOrder(v int32)`

SetSortOrder sets SortOrder field to given value.

### HasSortOrder

`func (o *SalesOrdersApiListOrderPriceAdjustmentsItem) HasSortOrder() bool`

HasSortOrder returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


