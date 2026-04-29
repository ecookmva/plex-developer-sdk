# InventoryOperationsManagementApiCreateInventoryReceiptLotRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SupplierLotNumber** | Pointer to **string** | The Supplier Lot Number. | [optional] 
**ManufacturedDateTime** | Pointer to **time.Time** | The manufactured date. | [optional] 
**PartId** | Pointer to **string** | A unique identifier of a part to associate with the lot. | [optional] 

## Methods

### NewInventoryOperationsManagementApiCreateInventoryReceiptLotRequest

`func NewInventoryOperationsManagementApiCreateInventoryReceiptLotRequest() *InventoryOperationsManagementApiCreateInventoryReceiptLotRequest`

NewInventoryOperationsManagementApiCreateInventoryReceiptLotRequest instantiates a new InventoryOperationsManagementApiCreateInventoryReceiptLotRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInventoryOperationsManagementApiCreateInventoryReceiptLotRequestWithDefaults

`func NewInventoryOperationsManagementApiCreateInventoryReceiptLotRequestWithDefaults() *InventoryOperationsManagementApiCreateInventoryReceiptLotRequest`

NewInventoryOperationsManagementApiCreateInventoryReceiptLotRequestWithDefaults instantiates a new InventoryOperationsManagementApiCreateInventoryReceiptLotRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSupplierLotNumber

`func (o *InventoryOperationsManagementApiCreateInventoryReceiptLotRequest) GetSupplierLotNumber() string`

GetSupplierLotNumber returns the SupplierLotNumber field if non-nil, zero value otherwise.

### GetSupplierLotNumberOk

`func (o *InventoryOperationsManagementApiCreateInventoryReceiptLotRequest) GetSupplierLotNumberOk() (*string, bool)`

GetSupplierLotNumberOk returns a tuple with the SupplierLotNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierLotNumber

`func (o *InventoryOperationsManagementApiCreateInventoryReceiptLotRequest) SetSupplierLotNumber(v string)`

SetSupplierLotNumber sets SupplierLotNumber field to given value.

### HasSupplierLotNumber

`func (o *InventoryOperationsManagementApiCreateInventoryReceiptLotRequest) HasSupplierLotNumber() bool`

HasSupplierLotNumber returns a boolean if a field has been set.

### GetManufacturedDateTime

`func (o *InventoryOperationsManagementApiCreateInventoryReceiptLotRequest) GetManufacturedDateTime() time.Time`

GetManufacturedDateTime returns the ManufacturedDateTime field if non-nil, zero value otherwise.

### GetManufacturedDateTimeOk

`func (o *InventoryOperationsManagementApiCreateInventoryReceiptLotRequest) GetManufacturedDateTimeOk() (*time.Time, bool)`

GetManufacturedDateTimeOk returns a tuple with the ManufacturedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManufacturedDateTime

`func (o *InventoryOperationsManagementApiCreateInventoryReceiptLotRequest) SetManufacturedDateTime(v time.Time)`

SetManufacturedDateTime sets ManufacturedDateTime field to given value.

### HasManufacturedDateTime

`func (o *InventoryOperationsManagementApiCreateInventoryReceiptLotRequest) HasManufacturedDateTime() bool`

HasManufacturedDateTime returns a boolean if a field has been set.

### GetPartId

`func (o *InventoryOperationsManagementApiCreateInventoryReceiptLotRequest) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *InventoryOperationsManagementApiCreateInventoryReceiptLotRequest) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *InventoryOperationsManagementApiCreateInventoryReceiptLotRequest) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *InventoryOperationsManagementApiCreateInventoryReceiptLotRequest) HasPartId() bool`

HasPartId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


