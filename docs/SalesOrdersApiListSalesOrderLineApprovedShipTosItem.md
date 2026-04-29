# SalesOrdersApiListSalesOrderLineApprovedShipTosItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | The ID of the sales order. | [optional] 
**LineId** | Pointer to **string** | The ID of the order line. | [optional] 
**ShipToAddressId** | Pointer to **string** | The ID of the ship to customer address record assigned to an order line. | [optional] 
**DefaultCarrierId** | Pointer to **string** | The ID of the carrier assigned to an order line approved Ship To record. | [optional] 
**DefaultCarrier** | Pointer to **string** | The carrier assigned to an order line approved Ship To record. | [optional] 
**DefaultShipFromId** | Pointer to **string** | The ID of the default building from which shipments will be sent. | [optional] 
**DefaultShipFromCode** | Pointer to **string** | The building code from which the shipment will be shipped from by default. | [optional] 

## Methods

### NewSalesOrdersApiListSalesOrderLineApprovedShipTosItem

`func NewSalesOrdersApiListSalesOrderLineApprovedShipTosItem() *SalesOrdersApiListSalesOrderLineApprovedShipTosItem`

NewSalesOrdersApiListSalesOrderLineApprovedShipTosItem instantiates a new SalesOrdersApiListSalesOrderLineApprovedShipTosItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSalesOrdersApiListSalesOrderLineApprovedShipTosItemWithDefaults

`func NewSalesOrdersApiListSalesOrderLineApprovedShipTosItemWithDefaults() *SalesOrdersApiListSalesOrderLineApprovedShipTosItem`

NewSalesOrdersApiListSalesOrderLineApprovedShipTosItemWithDefaults instantiates a new SalesOrdersApiListSalesOrderLineApprovedShipTosItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SalesOrdersApiListSalesOrderLineApprovedShipTosItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SalesOrdersApiListSalesOrderLineApprovedShipTosItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SalesOrdersApiListSalesOrderLineApprovedShipTosItem) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *SalesOrdersApiListSalesOrderLineApprovedShipTosItem) HasId() bool`

HasId returns a boolean if a field has been set.

### GetLineId

`func (o *SalesOrdersApiListSalesOrderLineApprovedShipTosItem) GetLineId() string`

GetLineId returns the LineId field if non-nil, zero value otherwise.

### GetLineIdOk

`func (o *SalesOrdersApiListSalesOrderLineApprovedShipTosItem) GetLineIdOk() (*string, bool)`

GetLineIdOk returns a tuple with the LineId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineId

`func (o *SalesOrdersApiListSalesOrderLineApprovedShipTosItem) SetLineId(v string)`

SetLineId sets LineId field to given value.

### HasLineId

`func (o *SalesOrdersApiListSalesOrderLineApprovedShipTosItem) HasLineId() bool`

HasLineId returns a boolean if a field has been set.

### GetShipToAddressId

`func (o *SalesOrdersApiListSalesOrderLineApprovedShipTosItem) GetShipToAddressId() string`

GetShipToAddressId returns the ShipToAddressId field if non-nil, zero value otherwise.

### GetShipToAddressIdOk

`func (o *SalesOrdersApiListSalesOrderLineApprovedShipTosItem) GetShipToAddressIdOk() (*string, bool)`

GetShipToAddressIdOk returns a tuple with the ShipToAddressId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipToAddressId

`func (o *SalesOrdersApiListSalesOrderLineApprovedShipTosItem) SetShipToAddressId(v string)`

SetShipToAddressId sets ShipToAddressId field to given value.

### HasShipToAddressId

`func (o *SalesOrdersApiListSalesOrderLineApprovedShipTosItem) HasShipToAddressId() bool`

HasShipToAddressId returns a boolean if a field has been set.

### GetDefaultCarrierId

`func (o *SalesOrdersApiListSalesOrderLineApprovedShipTosItem) GetDefaultCarrierId() string`

GetDefaultCarrierId returns the DefaultCarrierId field if non-nil, zero value otherwise.

### GetDefaultCarrierIdOk

`func (o *SalesOrdersApiListSalesOrderLineApprovedShipTosItem) GetDefaultCarrierIdOk() (*string, bool)`

GetDefaultCarrierIdOk returns a tuple with the DefaultCarrierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultCarrierId

`func (o *SalesOrdersApiListSalesOrderLineApprovedShipTosItem) SetDefaultCarrierId(v string)`

SetDefaultCarrierId sets DefaultCarrierId field to given value.

### HasDefaultCarrierId

`func (o *SalesOrdersApiListSalesOrderLineApprovedShipTosItem) HasDefaultCarrierId() bool`

HasDefaultCarrierId returns a boolean if a field has been set.

### GetDefaultCarrier

`func (o *SalesOrdersApiListSalesOrderLineApprovedShipTosItem) GetDefaultCarrier() string`

GetDefaultCarrier returns the DefaultCarrier field if non-nil, zero value otherwise.

### GetDefaultCarrierOk

`func (o *SalesOrdersApiListSalesOrderLineApprovedShipTosItem) GetDefaultCarrierOk() (*string, bool)`

GetDefaultCarrierOk returns a tuple with the DefaultCarrier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultCarrier

`func (o *SalesOrdersApiListSalesOrderLineApprovedShipTosItem) SetDefaultCarrier(v string)`

SetDefaultCarrier sets DefaultCarrier field to given value.

### HasDefaultCarrier

`func (o *SalesOrdersApiListSalesOrderLineApprovedShipTosItem) HasDefaultCarrier() bool`

HasDefaultCarrier returns a boolean if a field has been set.

### GetDefaultShipFromId

`func (o *SalesOrdersApiListSalesOrderLineApprovedShipTosItem) GetDefaultShipFromId() string`

GetDefaultShipFromId returns the DefaultShipFromId field if non-nil, zero value otherwise.

### GetDefaultShipFromIdOk

`func (o *SalesOrdersApiListSalesOrderLineApprovedShipTosItem) GetDefaultShipFromIdOk() (*string, bool)`

GetDefaultShipFromIdOk returns a tuple with the DefaultShipFromId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultShipFromId

`func (o *SalesOrdersApiListSalesOrderLineApprovedShipTosItem) SetDefaultShipFromId(v string)`

SetDefaultShipFromId sets DefaultShipFromId field to given value.

### HasDefaultShipFromId

`func (o *SalesOrdersApiListSalesOrderLineApprovedShipTosItem) HasDefaultShipFromId() bool`

HasDefaultShipFromId returns a boolean if a field has been set.

### GetDefaultShipFromCode

`func (o *SalesOrdersApiListSalesOrderLineApprovedShipTosItem) GetDefaultShipFromCode() string`

GetDefaultShipFromCode returns the DefaultShipFromCode field if non-nil, zero value otherwise.

### GetDefaultShipFromCodeOk

`func (o *SalesOrdersApiListSalesOrderLineApprovedShipTosItem) GetDefaultShipFromCodeOk() (*string, bool)`

GetDefaultShipFromCodeOk returns a tuple with the DefaultShipFromCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultShipFromCode

`func (o *SalesOrdersApiListSalesOrderLineApprovedShipTosItem) SetDefaultShipFromCode(v string)`

SetDefaultShipFromCode sets DefaultShipFromCode field to given value.

### HasDefaultShipFromCode

`func (o *SalesOrdersApiListSalesOrderLineApprovedShipTosItem) HasDefaultShipFromCode() bool`

HasDefaultShipFromCode returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


