# TransferOrdersApiCreateTransferOrderRequest

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
**Id** | Pointer to **string** | A unique identifier for the transfer order. This will be automatically generated if omitted from the request. | [optional] 

## Methods

### NewTransferOrdersApiCreateTransferOrderRequest

`func NewTransferOrdersApiCreateTransferOrderRequest() *TransferOrdersApiCreateTransferOrderRequest`

NewTransferOrdersApiCreateTransferOrderRequest instantiates a new TransferOrdersApiCreateTransferOrderRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTransferOrdersApiCreateTransferOrderRequestWithDefaults

`func NewTransferOrdersApiCreateTransferOrderRequestWithDefaults() *TransferOrdersApiCreateTransferOrderRequest`

NewTransferOrdersApiCreateTransferOrderRequestWithDefaults instantiates a new TransferOrdersApiCreateTransferOrderRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *TransferOrdersApiCreateTransferOrderRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *TransferOrdersApiCreateTransferOrderRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *TransferOrdersApiCreateTransferOrderRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *TransferOrdersApiCreateTransferOrderRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetFromLocationId

`func (o *TransferOrdersApiCreateTransferOrderRequest) GetFromLocationId() string`

GetFromLocationId returns the FromLocationId field if non-nil, zero value otherwise.

### GetFromLocationIdOk

`func (o *TransferOrdersApiCreateTransferOrderRequest) GetFromLocationIdOk() (*string, bool)`

GetFromLocationIdOk returns a tuple with the FromLocationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFromLocationId

`func (o *TransferOrdersApiCreateTransferOrderRequest) SetFromLocationId(v string)`

SetFromLocationId sets FromLocationId field to given value.

### HasFromLocationId

`func (o *TransferOrdersApiCreateTransferOrderRequest) HasFromLocationId() bool`

HasFromLocationId returns a boolean if a field has been set.

### GetLotId

`func (o *TransferOrdersApiCreateTransferOrderRequest) GetLotId() string`

GetLotId returns the LotId field if non-nil, zero value otherwise.

### GetLotIdOk

`func (o *TransferOrdersApiCreateTransferOrderRequest) GetLotIdOk() (*string, bool)`

GetLotIdOk returns a tuple with the LotId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLotId

`func (o *TransferOrdersApiCreateTransferOrderRequest) SetLotId(v string)`

SetLotId sets LotId field to given value.

### HasLotId

`func (o *TransferOrdersApiCreateTransferOrderRequest) HasLotId() bool`

HasLotId returns a boolean if a field has been set.

### GetOrderQuantity

`func (o *TransferOrdersApiCreateTransferOrderRequest) GetOrderQuantity() float64`

GetOrderQuantity returns the OrderQuantity field if non-nil, zero value otherwise.

### GetOrderQuantityOk

`func (o *TransferOrdersApiCreateTransferOrderRequest) GetOrderQuantityOk() (*float64, bool)`

GetOrderQuantityOk returns a tuple with the OrderQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderQuantity

`func (o *TransferOrdersApiCreateTransferOrderRequest) SetOrderQuantity(v float64)`

SetOrderQuantity sets OrderQuantity field to given value.

### HasOrderQuantity

`func (o *TransferOrdersApiCreateTransferOrderRequest) HasOrderQuantity() bool`

HasOrderQuantity returns a boolean if a field has been set.

### GetOperationId

`func (o *TransferOrdersApiCreateTransferOrderRequest) GetOperationId() string`

GetOperationId returns the OperationId field if non-nil, zero value otherwise.

### GetOperationIdOk

`func (o *TransferOrdersApiCreateTransferOrderRequest) GetOperationIdOk() (*string, bool)`

GetOperationIdOk returns a tuple with the OperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationId

`func (o *TransferOrdersApiCreateTransferOrderRequest) SetOperationId(v string)`

SetOperationId sets OperationId field to given value.

### HasOperationId

`func (o *TransferOrdersApiCreateTransferOrderRequest) HasOperationId() bool`

HasOperationId returns a boolean if a field has been set.

### GetPartId

`func (o *TransferOrdersApiCreateTransferOrderRequest) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *TransferOrdersApiCreateTransferOrderRequest) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *TransferOrdersApiCreateTransferOrderRequest) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *TransferOrdersApiCreateTransferOrderRequest) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetRequiredShipDate

`func (o *TransferOrdersApiCreateTransferOrderRequest) GetRequiredShipDate() time.Time`

GetRequiredShipDate returns the RequiredShipDate field if non-nil, zero value otherwise.

### GetRequiredShipDateOk

`func (o *TransferOrdersApiCreateTransferOrderRequest) GetRequiredShipDateOk() (*time.Time, bool)`

GetRequiredShipDateOk returns a tuple with the RequiredShipDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequiredShipDate

`func (o *TransferOrdersApiCreateTransferOrderRequest) SetRequiredShipDate(v time.Time)`

SetRequiredShipDate sets RequiredShipDate field to given value.

### HasRequiredShipDate

`func (o *TransferOrdersApiCreateTransferOrderRequest) HasRequiredShipDate() bool`

HasRequiredShipDate returns a boolean if a field has been set.

### GetShipFromId

`func (o *TransferOrdersApiCreateTransferOrderRequest) GetShipFromId() string`

GetShipFromId returns the ShipFromId field if non-nil, zero value otherwise.

### GetShipFromIdOk

`func (o *TransferOrdersApiCreateTransferOrderRequest) GetShipFromIdOk() (*string, bool)`

GetShipFromIdOk returns a tuple with the ShipFromId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipFromId

`func (o *TransferOrdersApiCreateTransferOrderRequest) SetShipFromId(v string)`

SetShipFromId sets ShipFromId field to given value.

### HasShipFromId

`func (o *TransferOrdersApiCreateTransferOrderRequest) HasShipFromId() bool`

HasShipFromId returns a boolean if a field has been set.

### GetShipToId

`func (o *TransferOrdersApiCreateTransferOrderRequest) GetShipToId() string`

GetShipToId returns the ShipToId field if non-nil, zero value otherwise.

### GetShipToIdOk

`func (o *TransferOrdersApiCreateTransferOrderRequest) GetShipToIdOk() (*string, bool)`

GetShipToIdOk returns a tuple with the ShipToId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipToId

`func (o *TransferOrdersApiCreateTransferOrderRequest) SetShipToId(v string)`

SetShipToId sets ShipToId field to given value.

### HasShipToId

`func (o *TransferOrdersApiCreateTransferOrderRequest) HasShipToId() bool`

HasShipToId returns a boolean if a field has been set.

### GetSupplyItemId

`func (o *TransferOrdersApiCreateTransferOrderRequest) GetSupplyItemId() string`

GetSupplyItemId returns the SupplyItemId field if non-nil, zero value otherwise.

### GetSupplyItemIdOk

`func (o *TransferOrdersApiCreateTransferOrderRequest) GetSupplyItemIdOk() (*string, bool)`

GetSupplyItemIdOk returns a tuple with the SupplyItemId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplyItemId

`func (o *TransferOrdersApiCreateTransferOrderRequest) SetSupplyItemId(v string)`

SetSupplyItemId sets SupplyItemId field to given value.

### HasSupplyItemId

`func (o *TransferOrdersApiCreateTransferOrderRequest) HasSupplyItemId() bool`

HasSupplyItemId returns a boolean if a field has been set.

### GetType

`func (o *TransferOrdersApiCreateTransferOrderRequest) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *TransferOrdersApiCreateTransferOrderRequest) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *TransferOrdersApiCreateTransferOrderRequest) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *TransferOrdersApiCreateTransferOrderRequest) HasType() bool`

HasType returns a boolean if a field has been set.

### GetId

`func (o *TransferOrdersApiCreateTransferOrderRequest) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *TransferOrdersApiCreateTransferOrderRequest) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *TransferOrdersApiCreateTransferOrderRequest) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *TransferOrdersApiCreateTransferOrderRequest) HasId() bool`

HasId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


