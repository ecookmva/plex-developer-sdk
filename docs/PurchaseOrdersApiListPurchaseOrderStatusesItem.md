# PurchaseOrdersApiListPurchaseOrderStatusesItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** | The name of the purchase order status. | [optional] 
**Receive** | Pointer to **bool** | Indicates that purchase orders in this status allow receiving. | [optional] 
**Active** | Pointer to **bool** | Indicates whether the purchase order status is active or inactive. | [optional] 
**Default** | Pointer to **bool** | Indicates that this purchase order status is the default for purchase orders. | [optional] 
**IncludeInMrp** | Pointer to **bool** | Indicates that purchase orders in this status are included in MRP (Material Requirements Planning). | [optional] 
**Cancelled** | Pointer to **bool** | Indicates that purchase orders in this status are canceled. | [optional] 
**Release** | Pointer to **bool** | Indicates that purchase orders in this status are released. | [optional] 
**OnOrder** | Pointer to **bool** | Indicates that purchase orders in this status are on order (sent to the supplier). | [optional] 
**Received** | Pointer to **bool** | Indicates that purchase orders in this status were fully received. | [optional] 

## Methods

### NewPurchaseOrdersApiListPurchaseOrderStatusesItem

`func NewPurchaseOrdersApiListPurchaseOrderStatusesItem() *PurchaseOrdersApiListPurchaseOrderStatusesItem`

NewPurchaseOrdersApiListPurchaseOrderStatusesItem instantiates a new PurchaseOrdersApiListPurchaseOrderStatusesItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPurchaseOrdersApiListPurchaseOrderStatusesItemWithDefaults

`func NewPurchaseOrdersApiListPurchaseOrderStatusesItemWithDefaults() *PurchaseOrdersApiListPurchaseOrderStatusesItem`

NewPurchaseOrdersApiListPurchaseOrderStatusesItemWithDefaults instantiates a new PurchaseOrdersApiListPurchaseOrderStatusesItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *PurchaseOrdersApiListPurchaseOrderStatusesItem) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PurchaseOrdersApiListPurchaseOrderStatusesItem) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PurchaseOrdersApiListPurchaseOrderStatusesItem) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *PurchaseOrdersApiListPurchaseOrderStatusesItem) HasName() bool`

HasName returns a boolean if a field has been set.

### GetReceive

`func (o *PurchaseOrdersApiListPurchaseOrderStatusesItem) GetReceive() bool`

GetReceive returns the Receive field if non-nil, zero value otherwise.

### GetReceiveOk

`func (o *PurchaseOrdersApiListPurchaseOrderStatusesItem) GetReceiveOk() (*bool, bool)`

GetReceiveOk returns a tuple with the Receive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceive

`func (o *PurchaseOrdersApiListPurchaseOrderStatusesItem) SetReceive(v bool)`

SetReceive sets Receive field to given value.

### HasReceive

`func (o *PurchaseOrdersApiListPurchaseOrderStatusesItem) HasReceive() bool`

HasReceive returns a boolean if a field has been set.

### GetActive

`func (o *PurchaseOrdersApiListPurchaseOrderStatusesItem) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *PurchaseOrdersApiListPurchaseOrderStatusesItem) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *PurchaseOrdersApiListPurchaseOrderStatusesItem) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *PurchaseOrdersApiListPurchaseOrderStatusesItem) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetDefault

`func (o *PurchaseOrdersApiListPurchaseOrderStatusesItem) GetDefault() bool`

GetDefault returns the Default field if non-nil, zero value otherwise.

### GetDefaultOk

`func (o *PurchaseOrdersApiListPurchaseOrderStatusesItem) GetDefaultOk() (*bool, bool)`

GetDefaultOk returns a tuple with the Default field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefault

`func (o *PurchaseOrdersApiListPurchaseOrderStatusesItem) SetDefault(v bool)`

SetDefault sets Default field to given value.

### HasDefault

`func (o *PurchaseOrdersApiListPurchaseOrderStatusesItem) HasDefault() bool`

HasDefault returns a boolean if a field has been set.

### GetIncludeInMrp

`func (o *PurchaseOrdersApiListPurchaseOrderStatusesItem) GetIncludeInMrp() bool`

GetIncludeInMrp returns the IncludeInMrp field if non-nil, zero value otherwise.

### GetIncludeInMrpOk

`func (o *PurchaseOrdersApiListPurchaseOrderStatusesItem) GetIncludeInMrpOk() (*bool, bool)`

GetIncludeInMrpOk returns a tuple with the IncludeInMrp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludeInMrp

`func (o *PurchaseOrdersApiListPurchaseOrderStatusesItem) SetIncludeInMrp(v bool)`

SetIncludeInMrp sets IncludeInMrp field to given value.

### HasIncludeInMrp

`func (o *PurchaseOrdersApiListPurchaseOrderStatusesItem) HasIncludeInMrp() bool`

HasIncludeInMrp returns a boolean if a field has been set.

### GetCancelled

`func (o *PurchaseOrdersApiListPurchaseOrderStatusesItem) GetCancelled() bool`

GetCancelled returns the Cancelled field if non-nil, zero value otherwise.

### GetCancelledOk

`func (o *PurchaseOrdersApiListPurchaseOrderStatusesItem) GetCancelledOk() (*bool, bool)`

GetCancelledOk returns a tuple with the Cancelled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCancelled

`func (o *PurchaseOrdersApiListPurchaseOrderStatusesItem) SetCancelled(v bool)`

SetCancelled sets Cancelled field to given value.

### HasCancelled

`func (o *PurchaseOrdersApiListPurchaseOrderStatusesItem) HasCancelled() bool`

HasCancelled returns a boolean if a field has been set.

### GetRelease

`func (o *PurchaseOrdersApiListPurchaseOrderStatusesItem) GetRelease() bool`

GetRelease returns the Release field if non-nil, zero value otherwise.

### GetReleaseOk

`func (o *PurchaseOrdersApiListPurchaseOrderStatusesItem) GetReleaseOk() (*bool, bool)`

GetReleaseOk returns a tuple with the Release field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRelease

`func (o *PurchaseOrdersApiListPurchaseOrderStatusesItem) SetRelease(v bool)`

SetRelease sets Release field to given value.

### HasRelease

`func (o *PurchaseOrdersApiListPurchaseOrderStatusesItem) HasRelease() bool`

HasRelease returns a boolean if a field has been set.

### GetOnOrder

`func (o *PurchaseOrdersApiListPurchaseOrderStatusesItem) GetOnOrder() bool`

GetOnOrder returns the OnOrder field if non-nil, zero value otherwise.

### GetOnOrderOk

`func (o *PurchaseOrdersApiListPurchaseOrderStatusesItem) GetOnOrderOk() (*bool, bool)`

GetOnOrderOk returns a tuple with the OnOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOnOrder

`func (o *PurchaseOrdersApiListPurchaseOrderStatusesItem) SetOnOrder(v bool)`

SetOnOrder sets OnOrder field to given value.

### HasOnOrder

`func (o *PurchaseOrdersApiListPurchaseOrderStatusesItem) HasOnOrder() bool`

HasOnOrder returns a boolean if a field has been set.

### GetReceived

`func (o *PurchaseOrdersApiListPurchaseOrderStatusesItem) GetReceived() bool`

GetReceived returns the Received field if non-nil, zero value otherwise.

### GetReceivedOk

`func (o *PurchaseOrdersApiListPurchaseOrderStatusesItem) GetReceivedOk() (*bool, bool)`

GetReceivedOk returns a tuple with the Received field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceived

`func (o *PurchaseOrdersApiListPurchaseOrderStatusesItem) SetReceived(v bool)`

SetReceived sets Received field to given value.

### HasReceived

`func (o *PurchaseOrdersApiListPurchaseOrderStatusesItem) HasReceived() bool`

HasReceived returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


