# InventoryOperationsManagementApiGetInventoryReceiptResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | The ID of the inventory receipt. | [optional] 
**ExternalReceiptCode** | Pointer to **string** | The Tracking Number for the Inventory Receipt. | [optional] 
**ReceivedContainers** | Pointer to [**[]ReceivedContainersItem**](ReceivedContainersItem.md) | List of received containers associated to the receipt. | [optional] 
**SupplierId** | Pointer to **string** | The ID of the supplier. | [optional] 
**SupplierCode** | Pointer to **string** | The supplier code of the supplier. 25 characters max. | [optional] 

## Methods

### NewInventoryOperationsManagementApiGetInventoryReceiptResponse

`func NewInventoryOperationsManagementApiGetInventoryReceiptResponse() *InventoryOperationsManagementApiGetInventoryReceiptResponse`

NewInventoryOperationsManagementApiGetInventoryReceiptResponse instantiates a new InventoryOperationsManagementApiGetInventoryReceiptResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInventoryOperationsManagementApiGetInventoryReceiptResponseWithDefaults

`func NewInventoryOperationsManagementApiGetInventoryReceiptResponseWithDefaults() *InventoryOperationsManagementApiGetInventoryReceiptResponse`

NewInventoryOperationsManagementApiGetInventoryReceiptResponseWithDefaults instantiates a new InventoryOperationsManagementApiGetInventoryReceiptResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *InventoryOperationsManagementApiGetInventoryReceiptResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *InventoryOperationsManagementApiGetInventoryReceiptResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *InventoryOperationsManagementApiGetInventoryReceiptResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *InventoryOperationsManagementApiGetInventoryReceiptResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetExternalReceiptCode

`func (o *InventoryOperationsManagementApiGetInventoryReceiptResponse) GetExternalReceiptCode() string`

GetExternalReceiptCode returns the ExternalReceiptCode field if non-nil, zero value otherwise.

### GetExternalReceiptCodeOk

`func (o *InventoryOperationsManagementApiGetInventoryReceiptResponse) GetExternalReceiptCodeOk() (*string, bool)`

GetExternalReceiptCodeOk returns a tuple with the ExternalReceiptCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalReceiptCode

`func (o *InventoryOperationsManagementApiGetInventoryReceiptResponse) SetExternalReceiptCode(v string)`

SetExternalReceiptCode sets ExternalReceiptCode field to given value.

### HasExternalReceiptCode

`func (o *InventoryOperationsManagementApiGetInventoryReceiptResponse) HasExternalReceiptCode() bool`

HasExternalReceiptCode returns a boolean if a field has been set.

### GetReceivedContainers

`func (o *InventoryOperationsManagementApiGetInventoryReceiptResponse) GetReceivedContainers() []ReceivedContainersItem`

GetReceivedContainers returns the ReceivedContainers field if non-nil, zero value otherwise.

### GetReceivedContainersOk

`func (o *InventoryOperationsManagementApiGetInventoryReceiptResponse) GetReceivedContainersOk() (*[]ReceivedContainersItem, bool)`

GetReceivedContainersOk returns a tuple with the ReceivedContainers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceivedContainers

`func (o *InventoryOperationsManagementApiGetInventoryReceiptResponse) SetReceivedContainers(v []ReceivedContainersItem)`

SetReceivedContainers sets ReceivedContainers field to given value.

### HasReceivedContainers

`func (o *InventoryOperationsManagementApiGetInventoryReceiptResponse) HasReceivedContainers() bool`

HasReceivedContainers returns a boolean if a field has been set.

### GetSupplierId

`func (o *InventoryOperationsManagementApiGetInventoryReceiptResponse) GetSupplierId() string`

GetSupplierId returns the SupplierId field if non-nil, zero value otherwise.

### GetSupplierIdOk

`func (o *InventoryOperationsManagementApiGetInventoryReceiptResponse) GetSupplierIdOk() (*string, bool)`

GetSupplierIdOk returns a tuple with the SupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierId

`func (o *InventoryOperationsManagementApiGetInventoryReceiptResponse) SetSupplierId(v string)`

SetSupplierId sets SupplierId field to given value.

### HasSupplierId

`func (o *InventoryOperationsManagementApiGetInventoryReceiptResponse) HasSupplierId() bool`

HasSupplierId returns a boolean if a field has been set.

### GetSupplierCode

`func (o *InventoryOperationsManagementApiGetInventoryReceiptResponse) GetSupplierCode() string`

GetSupplierCode returns the SupplierCode field if non-nil, zero value otherwise.

### GetSupplierCodeOk

`func (o *InventoryOperationsManagementApiGetInventoryReceiptResponse) GetSupplierCodeOk() (*string, bool)`

GetSupplierCodeOk returns a tuple with the SupplierCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierCode

`func (o *InventoryOperationsManagementApiGetInventoryReceiptResponse) SetSupplierCode(v string)`

SetSupplierCode sets SupplierCode field to given value.

### HasSupplierCode

`func (o *InventoryOperationsManagementApiGetInventoryReceiptResponse) HasSupplierCode() bool`

HasSupplierCode returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


