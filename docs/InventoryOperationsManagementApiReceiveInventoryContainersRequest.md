# InventoryOperationsManagementApiReceiveInventoryContainersRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PartId** | Pointer to **string** | The part ID. | [optional] 
**Quantity** | Pointer to **float64** | The inventory quantity. | [optional] 
**LocationId** | Pointer to **string** | The location ID. | [optional] 
**ExternalSerialNumber** | Pointer to **string** | External container serial number, used to override automatic serial generation. | [optional] 
**TrackingNumber** | Pointer to **string** | The container tracking number. | [optional] 
**LotId** | Pointer to **string** | The lot ID. | [optional] 
**Eun** | Pointer to **string** | 40 character max. The container&#39;s end unit number. | [optional] 
**BeginManufacturerDateTime** | Pointer to **time.Time** | The start manufactured date of the container. | [optional] 
**EndManufacturerDateTime** | Pointer to **time.Time** | The end manufactured date of the container. | [optional] 
**ContainerStatus** | Pointer to **string** | The status of the container, can be either Receiving or OK. If not provided default is Receiving. | [optional] 

## Methods

### NewInventoryOperationsManagementApiReceiveInventoryContainersRequest

`func NewInventoryOperationsManagementApiReceiveInventoryContainersRequest() *InventoryOperationsManagementApiReceiveInventoryContainersRequest`

NewInventoryOperationsManagementApiReceiveInventoryContainersRequest instantiates a new InventoryOperationsManagementApiReceiveInventoryContainersRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInventoryOperationsManagementApiReceiveInventoryContainersRequestWithDefaults

`func NewInventoryOperationsManagementApiReceiveInventoryContainersRequestWithDefaults() *InventoryOperationsManagementApiReceiveInventoryContainersRequest`

NewInventoryOperationsManagementApiReceiveInventoryContainersRequestWithDefaults instantiates a new InventoryOperationsManagementApiReceiveInventoryContainersRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPartId

`func (o *InventoryOperationsManagementApiReceiveInventoryContainersRequest) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *InventoryOperationsManagementApiReceiveInventoryContainersRequest) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *InventoryOperationsManagementApiReceiveInventoryContainersRequest) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *InventoryOperationsManagementApiReceiveInventoryContainersRequest) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetQuantity

`func (o *InventoryOperationsManagementApiReceiveInventoryContainersRequest) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *InventoryOperationsManagementApiReceiveInventoryContainersRequest) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *InventoryOperationsManagementApiReceiveInventoryContainersRequest) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *InventoryOperationsManagementApiReceiveInventoryContainersRequest) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetLocationId

`func (o *InventoryOperationsManagementApiReceiveInventoryContainersRequest) GetLocationId() string`

GetLocationId returns the LocationId field if non-nil, zero value otherwise.

### GetLocationIdOk

`func (o *InventoryOperationsManagementApiReceiveInventoryContainersRequest) GetLocationIdOk() (*string, bool)`

GetLocationIdOk returns a tuple with the LocationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocationId

`func (o *InventoryOperationsManagementApiReceiveInventoryContainersRequest) SetLocationId(v string)`

SetLocationId sets LocationId field to given value.

### HasLocationId

`func (o *InventoryOperationsManagementApiReceiveInventoryContainersRequest) HasLocationId() bool`

HasLocationId returns a boolean if a field has been set.

### GetExternalSerialNumber

`func (o *InventoryOperationsManagementApiReceiveInventoryContainersRequest) GetExternalSerialNumber() string`

GetExternalSerialNumber returns the ExternalSerialNumber field if non-nil, zero value otherwise.

### GetExternalSerialNumberOk

`func (o *InventoryOperationsManagementApiReceiveInventoryContainersRequest) GetExternalSerialNumberOk() (*string, bool)`

GetExternalSerialNumberOk returns a tuple with the ExternalSerialNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalSerialNumber

`func (o *InventoryOperationsManagementApiReceiveInventoryContainersRequest) SetExternalSerialNumber(v string)`

SetExternalSerialNumber sets ExternalSerialNumber field to given value.

### HasExternalSerialNumber

`func (o *InventoryOperationsManagementApiReceiveInventoryContainersRequest) HasExternalSerialNumber() bool`

HasExternalSerialNumber returns a boolean if a field has been set.

### GetTrackingNumber

`func (o *InventoryOperationsManagementApiReceiveInventoryContainersRequest) GetTrackingNumber() string`

GetTrackingNumber returns the TrackingNumber field if non-nil, zero value otherwise.

### GetTrackingNumberOk

`func (o *InventoryOperationsManagementApiReceiveInventoryContainersRequest) GetTrackingNumberOk() (*string, bool)`

GetTrackingNumberOk returns a tuple with the TrackingNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackingNumber

`func (o *InventoryOperationsManagementApiReceiveInventoryContainersRequest) SetTrackingNumber(v string)`

SetTrackingNumber sets TrackingNumber field to given value.

### HasTrackingNumber

`func (o *InventoryOperationsManagementApiReceiveInventoryContainersRequest) HasTrackingNumber() bool`

HasTrackingNumber returns a boolean if a field has been set.

### GetLotId

`func (o *InventoryOperationsManagementApiReceiveInventoryContainersRequest) GetLotId() string`

GetLotId returns the LotId field if non-nil, zero value otherwise.

### GetLotIdOk

`func (o *InventoryOperationsManagementApiReceiveInventoryContainersRequest) GetLotIdOk() (*string, bool)`

GetLotIdOk returns a tuple with the LotId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLotId

`func (o *InventoryOperationsManagementApiReceiveInventoryContainersRequest) SetLotId(v string)`

SetLotId sets LotId field to given value.

### HasLotId

`func (o *InventoryOperationsManagementApiReceiveInventoryContainersRequest) HasLotId() bool`

HasLotId returns a boolean if a field has been set.

### GetEun

`func (o *InventoryOperationsManagementApiReceiveInventoryContainersRequest) GetEun() string`

GetEun returns the Eun field if non-nil, zero value otherwise.

### GetEunOk

`func (o *InventoryOperationsManagementApiReceiveInventoryContainersRequest) GetEunOk() (*string, bool)`

GetEunOk returns a tuple with the Eun field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEun

`func (o *InventoryOperationsManagementApiReceiveInventoryContainersRequest) SetEun(v string)`

SetEun sets Eun field to given value.

### HasEun

`func (o *InventoryOperationsManagementApiReceiveInventoryContainersRequest) HasEun() bool`

HasEun returns a boolean if a field has been set.

### GetBeginManufacturerDateTime

`func (o *InventoryOperationsManagementApiReceiveInventoryContainersRequest) GetBeginManufacturerDateTime() time.Time`

GetBeginManufacturerDateTime returns the BeginManufacturerDateTime field if non-nil, zero value otherwise.

### GetBeginManufacturerDateTimeOk

`func (o *InventoryOperationsManagementApiReceiveInventoryContainersRequest) GetBeginManufacturerDateTimeOk() (*time.Time, bool)`

GetBeginManufacturerDateTimeOk returns a tuple with the BeginManufacturerDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBeginManufacturerDateTime

`func (o *InventoryOperationsManagementApiReceiveInventoryContainersRequest) SetBeginManufacturerDateTime(v time.Time)`

SetBeginManufacturerDateTime sets BeginManufacturerDateTime field to given value.

### HasBeginManufacturerDateTime

`func (o *InventoryOperationsManagementApiReceiveInventoryContainersRequest) HasBeginManufacturerDateTime() bool`

HasBeginManufacturerDateTime returns a boolean if a field has been set.

### GetEndManufacturerDateTime

`func (o *InventoryOperationsManagementApiReceiveInventoryContainersRequest) GetEndManufacturerDateTime() time.Time`

GetEndManufacturerDateTime returns the EndManufacturerDateTime field if non-nil, zero value otherwise.

### GetEndManufacturerDateTimeOk

`func (o *InventoryOperationsManagementApiReceiveInventoryContainersRequest) GetEndManufacturerDateTimeOk() (*time.Time, bool)`

GetEndManufacturerDateTimeOk returns a tuple with the EndManufacturerDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndManufacturerDateTime

`func (o *InventoryOperationsManagementApiReceiveInventoryContainersRequest) SetEndManufacturerDateTime(v time.Time)`

SetEndManufacturerDateTime sets EndManufacturerDateTime field to given value.

### HasEndManufacturerDateTime

`func (o *InventoryOperationsManagementApiReceiveInventoryContainersRequest) HasEndManufacturerDateTime() bool`

HasEndManufacturerDateTime returns a boolean if a field has been set.

### GetContainerStatus

`func (o *InventoryOperationsManagementApiReceiveInventoryContainersRequest) GetContainerStatus() string`

GetContainerStatus returns the ContainerStatus field if non-nil, zero value otherwise.

### GetContainerStatusOk

`func (o *InventoryOperationsManagementApiReceiveInventoryContainersRequest) GetContainerStatusOk() (*string, bool)`

GetContainerStatusOk returns a tuple with the ContainerStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContainerStatus

`func (o *InventoryOperationsManagementApiReceiveInventoryContainersRequest) SetContainerStatus(v string)`

SetContainerStatus sets ContainerStatus field to given value.

### HasContainerStatus

`func (o *InventoryOperationsManagementApiReceiveInventoryContainersRequest) HasContainerStatus() bool`

HasContainerStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


