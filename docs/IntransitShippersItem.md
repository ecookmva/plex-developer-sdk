# IntransitShippersItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ExpectedDeliveryDate** | Pointer to **time.Time** | The date when the interplant shipper is expected to arrive. | [optional] 
**Quantity** | Pointer to **float64** | The inventory quantity on the interplant shipper. | [optional] 

## Methods

### NewIntransitShippersItem

`func NewIntransitShippersItem() *IntransitShippersItem`

NewIntransitShippersItem instantiates a new IntransitShippersItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIntransitShippersItemWithDefaults

`func NewIntransitShippersItemWithDefaults() *IntransitShippersItem`

NewIntransitShippersItemWithDefaults instantiates a new IntransitShippersItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetExpectedDeliveryDate

`func (o *IntransitShippersItem) GetExpectedDeliveryDate() time.Time`

GetExpectedDeliveryDate returns the ExpectedDeliveryDate field if non-nil, zero value otherwise.

### GetExpectedDeliveryDateOk

`func (o *IntransitShippersItem) GetExpectedDeliveryDateOk() (*time.Time, bool)`

GetExpectedDeliveryDateOk returns a tuple with the ExpectedDeliveryDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedDeliveryDate

`func (o *IntransitShippersItem) SetExpectedDeliveryDate(v time.Time)`

SetExpectedDeliveryDate sets ExpectedDeliveryDate field to given value.

### HasExpectedDeliveryDate

`func (o *IntransitShippersItem) HasExpectedDeliveryDate() bool`

HasExpectedDeliveryDate returns a boolean if a field has been set.

### GetQuantity

`func (o *IntransitShippersItem) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *IntransitShippersItem) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *IntransitShippersItem) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *IntransitShippersItem) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


