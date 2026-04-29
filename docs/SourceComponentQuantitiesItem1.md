# SourceComponentQuantitiesItem1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PartId** | Pointer to **string** | A unique identifier of a part. | [optional] 
**PartOperationId** | Pointer to **string** | A unique identifier of a part operation. | [optional] 
**SupplyItemId** | Pointer to **string** | A unique identifier of a supply item. If no PartId is provided, this is required. | [optional] 
**LoadedQuantity** | Pointer to **float64** | Amount of source loaded to the workcenter. | [optional] 
**CurrentQuantity** | Pointer to **float64** | Amount of source added to the batch. | [optional] 
**MinimumQuantity** | Pointer to **float64** | The minimum batch quantity. | [optional] 
**MaximumQuantity** | Pointer to **float64** | The maximum batch quantity. | [optional] 
**StandardQuantity** | Pointer to **float64** | The standard batch quantity. | [optional] 

## Methods

### NewSourceComponentQuantitiesItem1

`func NewSourceComponentQuantitiesItem1() *SourceComponentQuantitiesItem1`

NewSourceComponentQuantitiesItem1 instantiates a new SourceComponentQuantitiesItem1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSourceComponentQuantitiesItem1WithDefaults

`func NewSourceComponentQuantitiesItem1WithDefaults() *SourceComponentQuantitiesItem1`

NewSourceComponentQuantitiesItem1WithDefaults instantiates a new SourceComponentQuantitiesItem1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPartId

`func (o *SourceComponentQuantitiesItem1) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *SourceComponentQuantitiesItem1) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *SourceComponentQuantitiesItem1) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *SourceComponentQuantitiesItem1) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetPartOperationId

`func (o *SourceComponentQuantitiesItem1) GetPartOperationId() string`

GetPartOperationId returns the PartOperationId field if non-nil, zero value otherwise.

### GetPartOperationIdOk

`func (o *SourceComponentQuantitiesItem1) GetPartOperationIdOk() (*string, bool)`

GetPartOperationIdOk returns a tuple with the PartOperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartOperationId

`func (o *SourceComponentQuantitiesItem1) SetPartOperationId(v string)`

SetPartOperationId sets PartOperationId field to given value.

### HasPartOperationId

`func (o *SourceComponentQuantitiesItem1) HasPartOperationId() bool`

HasPartOperationId returns a boolean if a field has been set.

### GetSupplyItemId

`func (o *SourceComponentQuantitiesItem1) GetSupplyItemId() string`

GetSupplyItemId returns the SupplyItemId field if non-nil, zero value otherwise.

### GetSupplyItemIdOk

`func (o *SourceComponentQuantitiesItem1) GetSupplyItemIdOk() (*string, bool)`

GetSupplyItemIdOk returns a tuple with the SupplyItemId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplyItemId

`func (o *SourceComponentQuantitiesItem1) SetSupplyItemId(v string)`

SetSupplyItemId sets SupplyItemId field to given value.

### HasSupplyItemId

`func (o *SourceComponentQuantitiesItem1) HasSupplyItemId() bool`

HasSupplyItemId returns a boolean if a field has been set.

### GetLoadedQuantity

`func (o *SourceComponentQuantitiesItem1) GetLoadedQuantity() float64`

GetLoadedQuantity returns the LoadedQuantity field if non-nil, zero value otherwise.

### GetLoadedQuantityOk

`func (o *SourceComponentQuantitiesItem1) GetLoadedQuantityOk() (*float64, bool)`

GetLoadedQuantityOk returns a tuple with the LoadedQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLoadedQuantity

`func (o *SourceComponentQuantitiesItem1) SetLoadedQuantity(v float64)`

SetLoadedQuantity sets LoadedQuantity field to given value.

### HasLoadedQuantity

`func (o *SourceComponentQuantitiesItem1) HasLoadedQuantity() bool`

HasLoadedQuantity returns a boolean if a field has been set.

### GetCurrentQuantity

`func (o *SourceComponentQuantitiesItem1) GetCurrentQuantity() float64`

GetCurrentQuantity returns the CurrentQuantity field if non-nil, zero value otherwise.

### GetCurrentQuantityOk

`func (o *SourceComponentQuantitiesItem1) GetCurrentQuantityOk() (*float64, bool)`

GetCurrentQuantityOk returns a tuple with the CurrentQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentQuantity

`func (o *SourceComponentQuantitiesItem1) SetCurrentQuantity(v float64)`

SetCurrentQuantity sets CurrentQuantity field to given value.

### HasCurrentQuantity

`func (o *SourceComponentQuantitiesItem1) HasCurrentQuantity() bool`

HasCurrentQuantity returns a boolean if a field has been set.

### GetMinimumQuantity

`func (o *SourceComponentQuantitiesItem1) GetMinimumQuantity() float64`

GetMinimumQuantity returns the MinimumQuantity field if non-nil, zero value otherwise.

### GetMinimumQuantityOk

`func (o *SourceComponentQuantitiesItem1) GetMinimumQuantityOk() (*float64, bool)`

GetMinimumQuantityOk returns a tuple with the MinimumQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinimumQuantity

`func (o *SourceComponentQuantitiesItem1) SetMinimumQuantity(v float64)`

SetMinimumQuantity sets MinimumQuantity field to given value.

### HasMinimumQuantity

`func (o *SourceComponentQuantitiesItem1) HasMinimumQuantity() bool`

HasMinimumQuantity returns a boolean if a field has been set.

### GetMaximumQuantity

`func (o *SourceComponentQuantitiesItem1) GetMaximumQuantity() float64`

GetMaximumQuantity returns the MaximumQuantity field if non-nil, zero value otherwise.

### GetMaximumQuantityOk

`func (o *SourceComponentQuantitiesItem1) GetMaximumQuantityOk() (*float64, bool)`

GetMaximumQuantityOk returns a tuple with the MaximumQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaximumQuantity

`func (o *SourceComponentQuantitiesItem1) SetMaximumQuantity(v float64)`

SetMaximumQuantity sets MaximumQuantity field to given value.

### HasMaximumQuantity

`func (o *SourceComponentQuantitiesItem1) HasMaximumQuantity() bool`

HasMaximumQuantity returns a boolean if a field has been set.

### GetStandardQuantity

`func (o *SourceComponentQuantitiesItem1) GetStandardQuantity() float64`

GetStandardQuantity returns the StandardQuantity field if non-nil, zero value otherwise.

### GetStandardQuantityOk

`func (o *SourceComponentQuantitiesItem1) GetStandardQuantityOk() (*float64, bool)`

GetStandardQuantityOk returns a tuple with the StandardQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStandardQuantity

`func (o *SourceComponentQuantitiesItem1) SetStandardQuantity(v float64)`

SetStandardQuantity sets StandardQuantity field to given value.

### HasStandardQuantity

`func (o *SourceComponentQuantitiesItem1) HasStandardQuantity() bool`

HasStandardQuantity returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


