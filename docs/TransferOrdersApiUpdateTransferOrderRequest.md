# TransferOrdersApiUpdateTransferOrderRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | Pointer to **string** | The transfer order description. | [optional] 
**FromLocationId** | Pointer to **string** | The ID of the location the supply item will ship from. | [optional] 
**LotId** | Pointer to **string** | The ID of the lot allowed on the transfer order. | [optional] 
**OrderQuantity** | Pointer to **float64** | The quantity for the transfer order. | [optional] 
**OperationId** | Pointer to **string** | The ID of the operation the part must be in to satisfy the transfer order. | [optional] 
**PartId** | Pointer to **string** | The ID for a part. | [optional] 
**RequiredShipDate** | Pointer to **time.Time** | The date the transfer order is required to ship by. | [optional] 
**ShipFromId** | Pointer to **string** | The ID of the building the order will ship from. | [optional] 
**ShipToId** | Pointer to **string** | The ID of the building the order will ship to. | [optional] 
**SupplyItemId** | Pointer to **string** | The ID for a supply item. | [optional] 
**Type** | Pointer to **string** | The transfer order type. | [optional] 

## Methods

### NewTransferOrdersApiUpdateTransferOrderRequest

`func NewTransferOrdersApiUpdateTransferOrderRequest() *TransferOrdersApiUpdateTransferOrderRequest`

NewTransferOrdersApiUpdateTransferOrderRequest instantiates a new TransferOrdersApiUpdateTransferOrderRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTransferOrdersApiUpdateTransferOrderRequestWithDefaults

`func NewTransferOrdersApiUpdateTransferOrderRequestWithDefaults() *TransferOrdersApiUpdateTransferOrderRequest`

NewTransferOrdersApiUpdateTransferOrderRequestWithDefaults instantiates a new TransferOrdersApiUpdateTransferOrderRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *TransferOrdersApiUpdateTransferOrderRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *TransferOrdersApiUpdateTransferOrderRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *TransferOrdersApiUpdateTransferOrderRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *TransferOrdersApiUpdateTransferOrderRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetFromLocationId

`func (o *TransferOrdersApiUpdateTransferOrderRequest) GetFromLocationId() string`

GetFromLocationId returns the FromLocationId field if non-nil, zero value otherwise.

### GetFromLocationIdOk

`func (o *TransferOrdersApiUpdateTransferOrderRequest) GetFromLocationIdOk() (*string, bool)`

GetFromLocationIdOk returns a tuple with the FromLocationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFromLocationId

`func (o *TransferOrdersApiUpdateTransferOrderRequest) SetFromLocationId(v string)`

SetFromLocationId sets FromLocationId field to given value.

### HasFromLocationId

`func (o *TransferOrdersApiUpdateTransferOrderRequest) HasFromLocationId() bool`

HasFromLocationId returns a boolean if a field has been set.

### GetLotId

`func (o *TransferOrdersApiUpdateTransferOrderRequest) GetLotId() string`

GetLotId returns the LotId field if non-nil, zero value otherwise.

### GetLotIdOk

`func (o *TransferOrdersApiUpdateTransferOrderRequest) GetLotIdOk() (*string, bool)`

GetLotIdOk returns a tuple with the LotId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLotId

`func (o *TransferOrdersApiUpdateTransferOrderRequest) SetLotId(v string)`

SetLotId sets LotId field to given value.

### HasLotId

`func (o *TransferOrdersApiUpdateTransferOrderRequest) HasLotId() bool`

HasLotId returns a boolean if a field has been set.

### GetOrderQuantity

`func (o *TransferOrdersApiUpdateTransferOrderRequest) GetOrderQuantity() float64`

GetOrderQuantity returns the OrderQuantity field if non-nil, zero value otherwise.

### GetOrderQuantityOk

`func (o *TransferOrdersApiUpdateTransferOrderRequest) GetOrderQuantityOk() (*float64, bool)`

GetOrderQuantityOk returns a tuple with the OrderQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderQuantity

`func (o *TransferOrdersApiUpdateTransferOrderRequest) SetOrderQuantity(v float64)`

SetOrderQuantity sets OrderQuantity field to given value.

### HasOrderQuantity

`func (o *TransferOrdersApiUpdateTransferOrderRequest) HasOrderQuantity() bool`

HasOrderQuantity returns a boolean if a field has been set.

### GetOperationId

`func (o *TransferOrdersApiUpdateTransferOrderRequest) GetOperationId() string`

GetOperationId returns the OperationId field if non-nil, zero value otherwise.

### GetOperationIdOk

`func (o *TransferOrdersApiUpdateTransferOrderRequest) GetOperationIdOk() (*string, bool)`

GetOperationIdOk returns a tuple with the OperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationId

`func (o *TransferOrdersApiUpdateTransferOrderRequest) SetOperationId(v string)`

SetOperationId sets OperationId field to given value.

### HasOperationId

`func (o *TransferOrdersApiUpdateTransferOrderRequest) HasOperationId() bool`

HasOperationId returns a boolean if a field has been set.

### GetPartId

`func (o *TransferOrdersApiUpdateTransferOrderRequest) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *TransferOrdersApiUpdateTransferOrderRequest) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *TransferOrdersApiUpdateTransferOrderRequest) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *TransferOrdersApiUpdateTransferOrderRequest) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetRequiredShipDate

`func (o *TransferOrdersApiUpdateTransferOrderRequest) GetRequiredShipDate() time.Time`

GetRequiredShipDate returns the RequiredShipDate field if non-nil, zero value otherwise.

### GetRequiredShipDateOk

`func (o *TransferOrdersApiUpdateTransferOrderRequest) GetRequiredShipDateOk() (*time.Time, bool)`

GetRequiredShipDateOk returns a tuple with the RequiredShipDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequiredShipDate

`func (o *TransferOrdersApiUpdateTransferOrderRequest) SetRequiredShipDate(v time.Time)`

SetRequiredShipDate sets RequiredShipDate field to given value.

### HasRequiredShipDate

`func (o *TransferOrdersApiUpdateTransferOrderRequest) HasRequiredShipDate() bool`

HasRequiredShipDate returns a boolean if a field has been set.

### GetShipFromId

`func (o *TransferOrdersApiUpdateTransferOrderRequest) GetShipFromId() string`

GetShipFromId returns the ShipFromId field if non-nil, zero value otherwise.

### GetShipFromIdOk

`func (o *TransferOrdersApiUpdateTransferOrderRequest) GetShipFromIdOk() (*string, bool)`

GetShipFromIdOk returns a tuple with the ShipFromId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipFromId

`func (o *TransferOrdersApiUpdateTransferOrderRequest) SetShipFromId(v string)`

SetShipFromId sets ShipFromId field to given value.

### HasShipFromId

`func (o *TransferOrdersApiUpdateTransferOrderRequest) HasShipFromId() bool`

HasShipFromId returns a boolean if a field has been set.

### GetShipToId

`func (o *TransferOrdersApiUpdateTransferOrderRequest) GetShipToId() string`

GetShipToId returns the ShipToId field if non-nil, zero value otherwise.

### GetShipToIdOk

`func (o *TransferOrdersApiUpdateTransferOrderRequest) GetShipToIdOk() (*string, bool)`

GetShipToIdOk returns a tuple with the ShipToId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipToId

`func (o *TransferOrdersApiUpdateTransferOrderRequest) SetShipToId(v string)`

SetShipToId sets ShipToId field to given value.

### HasShipToId

`func (o *TransferOrdersApiUpdateTransferOrderRequest) HasShipToId() bool`

HasShipToId returns a boolean if a field has been set.

### GetSupplyItemId

`func (o *TransferOrdersApiUpdateTransferOrderRequest) GetSupplyItemId() string`

GetSupplyItemId returns the SupplyItemId field if non-nil, zero value otherwise.

### GetSupplyItemIdOk

`func (o *TransferOrdersApiUpdateTransferOrderRequest) GetSupplyItemIdOk() (*string, bool)`

GetSupplyItemIdOk returns a tuple with the SupplyItemId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplyItemId

`func (o *TransferOrdersApiUpdateTransferOrderRequest) SetSupplyItemId(v string)`

SetSupplyItemId sets SupplyItemId field to given value.

### HasSupplyItemId

`func (o *TransferOrdersApiUpdateTransferOrderRequest) HasSupplyItemId() bool`

HasSupplyItemId returns a boolean if a field has been set.

### GetType

`func (o *TransferOrdersApiUpdateTransferOrderRequest) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *TransferOrdersApiUpdateTransferOrderRequest) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *TransferOrdersApiUpdateTransferOrderRequest) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *TransferOrdersApiUpdateTransferOrderRequest) HasType() bool`

HasType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


