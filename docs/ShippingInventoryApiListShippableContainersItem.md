# ShippingInventoryApiListShippableContainersItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ShipperNo** | Pointer to **string** | The shipper number associated with the container. | [optional] 
**ShipperId** | Pointer to **string** | The shipper ID associated with the container. | [optional] 
**SerialNo** | Pointer to **string** | The container&#39;s serial number. | [optional] 
**PartNumber** | Pointer to **string** | The part number associated with the shippable container. | [optional] 
**PartRevision** | Pointer to **string** | The part revision associated with the shippable container. | [optional] 
**PartNumberRevision** | Pointer to **string** | The part&#39;s number and revision number, including the revision separator. | [optional] 
**PartId** | Pointer to **string** | The ID of the part associated with the shippable container. | [optional] 
**BuildingCode** | Pointer to **string** | The building code associated with the shippable container. | [optional] 
**BuildingId** | Pointer to **string** | The ID of the building associated with the shippable container. | [optional] 
**Location** | Pointer to **string** | The location associated with the shippable container. | [optional] 
**LocationGroup** | Pointer to **string** | The location group associated with the shippable container. | [optional] 
**AddDateTime** | Pointer to **time.Time** | The date and time the container was created. | [optional] 
**ShelfDateTime** | Pointer to **time.Time** | The shelf date and time of the container. | [optional] 
**Quantity** | Pointer to **float64** | The quantity associated with the container. | [optional] 
**ContainerStatus** | Pointer to **string** | The status of the container. | [optional] 
**ContainerType** | Pointer to **string** | The type of the container. | [optional] 
**MasterUnitId** | Pointer to **string** | The ID of the master unit associated with the container. | [optional] 
**GrossWeight** | Pointer to **float64** | The gross weight of the container. | [optional] 
**NetWeight** | Pointer to **float64** | The net weight of the container. | [optional] 
**WeightUnit** | Pointer to **string** | The weight unit of the container. | [optional] 
**HeatCode** | Pointer to **string** | The heat code associated with the container. | [optional] 
**HeatNo** | Pointer to **string** | The heat number associated with the container. | [optional] 
**TrackingNo** | Pointer to **string** | The tracking number of the container. | [optional] 
**LotNo** | Pointer to **string** | The lot number associated with the container. | [optional] 
**LotId** | Pointer to **string** | The ID of the lot associated with the container. | [optional] 

## Methods

### NewShippingInventoryApiListShippableContainersItem

`func NewShippingInventoryApiListShippableContainersItem() *ShippingInventoryApiListShippableContainersItem`

NewShippingInventoryApiListShippableContainersItem instantiates a new ShippingInventoryApiListShippableContainersItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewShippingInventoryApiListShippableContainersItemWithDefaults

`func NewShippingInventoryApiListShippableContainersItemWithDefaults() *ShippingInventoryApiListShippableContainersItem`

NewShippingInventoryApiListShippableContainersItemWithDefaults instantiates a new ShippingInventoryApiListShippableContainersItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetShipperNo

`func (o *ShippingInventoryApiListShippableContainersItem) GetShipperNo() string`

GetShipperNo returns the ShipperNo field if non-nil, zero value otherwise.

### GetShipperNoOk

`func (o *ShippingInventoryApiListShippableContainersItem) GetShipperNoOk() (*string, bool)`

GetShipperNoOk returns a tuple with the ShipperNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipperNo

`func (o *ShippingInventoryApiListShippableContainersItem) SetShipperNo(v string)`

SetShipperNo sets ShipperNo field to given value.

### HasShipperNo

`func (o *ShippingInventoryApiListShippableContainersItem) HasShipperNo() bool`

HasShipperNo returns a boolean if a field has been set.

### GetShipperId

`func (o *ShippingInventoryApiListShippableContainersItem) GetShipperId() string`

GetShipperId returns the ShipperId field if non-nil, zero value otherwise.

### GetShipperIdOk

`func (o *ShippingInventoryApiListShippableContainersItem) GetShipperIdOk() (*string, bool)`

GetShipperIdOk returns a tuple with the ShipperId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipperId

`func (o *ShippingInventoryApiListShippableContainersItem) SetShipperId(v string)`

SetShipperId sets ShipperId field to given value.

### HasShipperId

`func (o *ShippingInventoryApiListShippableContainersItem) HasShipperId() bool`

HasShipperId returns a boolean if a field has been set.

### GetSerialNo

`func (o *ShippingInventoryApiListShippableContainersItem) GetSerialNo() string`

GetSerialNo returns the SerialNo field if non-nil, zero value otherwise.

### GetSerialNoOk

`func (o *ShippingInventoryApiListShippableContainersItem) GetSerialNoOk() (*string, bool)`

GetSerialNoOk returns a tuple with the SerialNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSerialNo

`func (o *ShippingInventoryApiListShippableContainersItem) SetSerialNo(v string)`

SetSerialNo sets SerialNo field to given value.

### HasSerialNo

`func (o *ShippingInventoryApiListShippableContainersItem) HasSerialNo() bool`

HasSerialNo returns a boolean if a field has been set.

### GetPartNumber

`func (o *ShippingInventoryApiListShippableContainersItem) GetPartNumber() string`

GetPartNumber returns the PartNumber field if non-nil, zero value otherwise.

### GetPartNumberOk

`func (o *ShippingInventoryApiListShippableContainersItem) GetPartNumberOk() (*string, bool)`

GetPartNumberOk returns a tuple with the PartNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumber

`func (o *ShippingInventoryApiListShippableContainersItem) SetPartNumber(v string)`

SetPartNumber sets PartNumber field to given value.

### HasPartNumber

`func (o *ShippingInventoryApiListShippableContainersItem) HasPartNumber() bool`

HasPartNumber returns a boolean if a field has been set.

### GetPartRevision

`func (o *ShippingInventoryApiListShippableContainersItem) GetPartRevision() string`

GetPartRevision returns the PartRevision field if non-nil, zero value otherwise.

### GetPartRevisionOk

`func (o *ShippingInventoryApiListShippableContainersItem) GetPartRevisionOk() (*string, bool)`

GetPartRevisionOk returns a tuple with the PartRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartRevision

`func (o *ShippingInventoryApiListShippableContainersItem) SetPartRevision(v string)`

SetPartRevision sets PartRevision field to given value.

### HasPartRevision

`func (o *ShippingInventoryApiListShippableContainersItem) HasPartRevision() bool`

HasPartRevision returns a boolean if a field has been set.

### GetPartNumberRevision

`func (o *ShippingInventoryApiListShippableContainersItem) GetPartNumberRevision() string`

GetPartNumberRevision returns the PartNumberRevision field if non-nil, zero value otherwise.

### GetPartNumberRevisionOk

`func (o *ShippingInventoryApiListShippableContainersItem) GetPartNumberRevisionOk() (*string, bool)`

GetPartNumberRevisionOk returns a tuple with the PartNumberRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumberRevision

`func (o *ShippingInventoryApiListShippableContainersItem) SetPartNumberRevision(v string)`

SetPartNumberRevision sets PartNumberRevision field to given value.

### HasPartNumberRevision

`func (o *ShippingInventoryApiListShippableContainersItem) HasPartNumberRevision() bool`

HasPartNumberRevision returns a boolean if a field has been set.

### GetPartId

`func (o *ShippingInventoryApiListShippableContainersItem) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *ShippingInventoryApiListShippableContainersItem) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *ShippingInventoryApiListShippableContainersItem) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *ShippingInventoryApiListShippableContainersItem) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetBuildingCode

`func (o *ShippingInventoryApiListShippableContainersItem) GetBuildingCode() string`

GetBuildingCode returns the BuildingCode field if non-nil, zero value otherwise.

### GetBuildingCodeOk

`func (o *ShippingInventoryApiListShippableContainersItem) GetBuildingCodeOk() (*string, bool)`

GetBuildingCodeOk returns a tuple with the BuildingCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildingCode

`func (o *ShippingInventoryApiListShippableContainersItem) SetBuildingCode(v string)`

SetBuildingCode sets BuildingCode field to given value.

### HasBuildingCode

`func (o *ShippingInventoryApiListShippableContainersItem) HasBuildingCode() bool`

HasBuildingCode returns a boolean if a field has been set.

### GetBuildingId

`func (o *ShippingInventoryApiListShippableContainersItem) GetBuildingId() string`

GetBuildingId returns the BuildingId field if non-nil, zero value otherwise.

### GetBuildingIdOk

`func (o *ShippingInventoryApiListShippableContainersItem) GetBuildingIdOk() (*string, bool)`

GetBuildingIdOk returns a tuple with the BuildingId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildingId

`func (o *ShippingInventoryApiListShippableContainersItem) SetBuildingId(v string)`

SetBuildingId sets BuildingId field to given value.

### HasBuildingId

`func (o *ShippingInventoryApiListShippableContainersItem) HasBuildingId() bool`

HasBuildingId returns a boolean if a field has been set.

### GetLocation

`func (o *ShippingInventoryApiListShippableContainersItem) GetLocation() string`

GetLocation returns the Location field if non-nil, zero value otherwise.

### GetLocationOk

`func (o *ShippingInventoryApiListShippableContainersItem) GetLocationOk() (*string, bool)`

GetLocationOk returns a tuple with the Location field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocation

`func (o *ShippingInventoryApiListShippableContainersItem) SetLocation(v string)`

SetLocation sets Location field to given value.

### HasLocation

`func (o *ShippingInventoryApiListShippableContainersItem) HasLocation() bool`

HasLocation returns a boolean if a field has been set.

### GetLocationGroup

`func (o *ShippingInventoryApiListShippableContainersItem) GetLocationGroup() string`

GetLocationGroup returns the LocationGroup field if non-nil, zero value otherwise.

### GetLocationGroupOk

`func (o *ShippingInventoryApiListShippableContainersItem) GetLocationGroupOk() (*string, bool)`

GetLocationGroupOk returns a tuple with the LocationGroup field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocationGroup

`func (o *ShippingInventoryApiListShippableContainersItem) SetLocationGroup(v string)`

SetLocationGroup sets LocationGroup field to given value.

### HasLocationGroup

`func (o *ShippingInventoryApiListShippableContainersItem) HasLocationGroup() bool`

HasLocationGroup returns a boolean if a field has been set.

### GetAddDateTime

`func (o *ShippingInventoryApiListShippableContainersItem) GetAddDateTime() time.Time`

GetAddDateTime returns the AddDateTime field if non-nil, zero value otherwise.

### GetAddDateTimeOk

`func (o *ShippingInventoryApiListShippableContainersItem) GetAddDateTimeOk() (*time.Time, bool)`

GetAddDateTimeOk returns a tuple with the AddDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddDateTime

`func (o *ShippingInventoryApiListShippableContainersItem) SetAddDateTime(v time.Time)`

SetAddDateTime sets AddDateTime field to given value.

### HasAddDateTime

`func (o *ShippingInventoryApiListShippableContainersItem) HasAddDateTime() bool`

HasAddDateTime returns a boolean if a field has been set.

### GetShelfDateTime

`func (o *ShippingInventoryApiListShippableContainersItem) GetShelfDateTime() time.Time`

GetShelfDateTime returns the ShelfDateTime field if non-nil, zero value otherwise.

### GetShelfDateTimeOk

`func (o *ShippingInventoryApiListShippableContainersItem) GetShelfDateTimeOk() (*time.Time, bool)`

GetShelfDateTimeOk returns a tuple with the ShelfDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShelfDateTime

`func (o *ShippingInventoryApiListShippableContainersItem) SetShelfDateTime(v time.Time)`

SetShelfDateTime sets ShelfDateTime field to given value.

### HasShelfDateTime

`func (o *ShippingInventoryApiListShippableContainersItem) HasShelfDateTime() bool`

HasShelfDateTime returns a boolean if a field has been set.

### GetQuantity

`func (o *ShippingInventoryApiListShippableContainersItem) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *ShippingInventoryApiListShippableContainersItem) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *ShippingInventoryApiListShippableContainersItem) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *ShippingInventoryApiListShippableContainersItem) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetContainerStatus

`func (o *ShippingInventoryApiListShippableContainersItem) GetContainerStatus() string`

GetContainerStatus returns the ContainerStatus field if non-nil, zero value otherwise.

### GetContainerStatusOk

`func (o *ShippingInventoryApiListShippableContainersItem) GetContainerStatusOk() (*string, bool)`

GetContainerStatusOk returns a tuple with the ContainerStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContainerStatus

`func (o *ShippingInventoryApiListShippableContainersItem) SetContainerStatus(v string)`

SetContainerStatus sets ContainerStatus field to given value.

### HasContainerStatus

`func (o *ShippingInventoryApiListShippableContainersItem) HasContainerStatus() bool`

HasContainerStatus returns a boolean if a field has been set.

### GetContainerType

`func (o *ShippingInventoryApiListShippableContainersItem) GetContainerType() string`

GetContainerType returns the ContainerType field if non-nil, zero value otherwise.

### GetContainerTypeOk

`func (o *ShippingInventoryApiListShippableContainersItem) GetContainerTypeOk() (*string, bool)`

GetContainerTypeOk returns a tuple with the ContainerType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContainerType

`func (o *ShippingInventoryApiListShippableContainersItem) SetContainerType(v string)`

SetContainerType sets ContainerType field to given value.

### HasContainerType

`func (o *ShippingInventoryApiListShippableContainersItem) HasContainerType() bool`

HasContainerType returns a boolean if a field has been set.

### GetMasterUnitId

`func (o *ShippingInventoryApiListShippableContainersItem) GetMasterUnitId() string`

GetMasterUnitId returns the MasterUnitId field if non-nil, zero value otherwise.

### GetMasterUnitIdOk

`func (o *ShippingInventoryApiListShippableContainersItem) GetMasterUnitIdOk() (*string, bool)`

GetMasterUnitIdOk returns a tuple with the MasterUnitId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMasterUnitId

`func (o *ShippingInventoryApiListShippableContainersItem) SetMasterUnitId(v string)`

SetMasterUnitId sets MasterUnitId field to given value.

### HasMasterUnitId

`func (o *ShippingInventoryApiListShippableContainersItem) HasMasterUnitId() bool`

HasMasterUnitId returns a boolean if a field has been set.

### GetGrossWeight

`func (o *ShippingInventoryApiListShippableContainersItem) GetGrossWeight() float64`

GetGrossWeight returns the GrossWeight field if non-nil, zero value otherwise.

### GetGrossWeightOk

`func (o *ShippingInventoryApiListShippableContainersItem) GetGrossWeightOk() (*float64, bool)`

GetGrossWeightOk returns a tuple with the GrossWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrossWeight

`func (o *ShippingInventoryApiListShippableContainersItem) SetGrossWeight(v float64)`

SetGrossWeight sets GrossWeight field to given value.

### HasGrossWeight

`func (o *ShippingInventoryApiListShippableContainersItem) HasGrossWeight() bool`

HasGrossWeight returns a boolean if a field has been set.

### GetNetWeight

`func (o *ShippingInventoryApiListShippableContainersItem) GetNetWeight() float64`

GetNetWeight returns the NetWeight field if non-nil, zero value otherwise.

### GetNetWeightOk

`func (o *ShippingInventoryApiListShippableContainersItem) GetNetWeightOk() (*float64, bool)`

GetNetWeightOk returns a tuple with the NetWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetWeight

`func (o *ShippingInventoryApiListShippableContainersItem) SetNetWeight(v float64)`

SetNetWeight sets NetWeight field to given value.

### HasNetWeight

`func (o *ShippingInventoryApiListShippableContainersItem) HasNetWeight() bool`

HasNetWeight returns a boolean if a field has been set.

### GetWeightUnit

`func (o *ShippingInventoryApiListShippableContainersItem) GetWeightUnit() string`

GetWeightUnit returns the WeightUnit field if non-nil, zero value otherwise.

### GetWeightUnitOk

`func (o *ShippingInventoryApiListShippableContainersItem) GetWeightUnitOk() (*string, bool)`

GetWeightUnitOk returns a tuple with the WeightUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeightUnit

`func (o *ShippingInventoryApiListShippableContainersItem) SetWeightUnit(v string)`

SetWeightUnit sets WeightUnit field to given value.

### HasWeightUnit

`func (o *ShippingInventoryApiListShippableContainersItem) HasWeightUnit() bool`

HasWeightUnit returns a boolean if a field has been set.

### GetHeatCode

`func (o *ShippingInventoryApiListShippableContainersItem) GetHeatCode() string`

GetHeatCode returns the HeatCode field if non-nil, zero value otherwise.

### GetHeatCodeOk

`func (o *ShippingInventoryApiListShippableContainersItem) GetHeatCodeOk() (*string, bool)`

GetHeatCodeOk returns a tuple with the HeatCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeatCode

`func (o *ShippingInventoryApiListShippableContainersItem) SetHeatCode(v string)`

SetHeatCode sets HeatCode field to given value.

### HasHeatCode

`func (o *ShippingInventoryApiListShippableContainersItem) HasHeatCode() bool`

HasHeatCode returns a boolean if a field has been set.

### GetHeatNo

`func (o *ShippingInventoryApiListShippableContainersItem) GetHeatNo() string`

GetHeatNo returns the HeatNo field if non-nil, zero value otherwise.

### GetHeatNoOk

`func (o *ShippingInventoryApiListShippableContainersItem) GetHeatNoOk() (*string, bool)`

GetHeatNoOk returns a tuple with the HeatNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeatNo

`func (o *ShippingInventoryApiListShippableContainersItem) SetHeatNo(v string)`

SetHeatNo sets HeatNo field to given value.

### HasHeatNo

`func (o *ShippingInventoryApiListShippableContainersItem) HasHeatNo() bool`

HasHeatNo returns a boolean if a field has been set.

### GetTrackingNo

`func (o *ShippingInventoryApiListShippableContainersItem) GetTrackingNo() string`

GetTrackingNo returns the TrackingNo field if non-nil, zero value otherwise.

### GetTrackingNoOk

`func (o *ShippingInventoryApiListShippableContainersItem) GetTrackingNoOk() (*string, bool)`

GetTrackingNoOk returns a tuple with the TrackingNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackingNo

`func (o *ShippingInventoryApiListShippableContainersItem) SetTrackingNo(v string)`

SetTrackingNo sets TrackingNo field to given value.

### HasTrackingNo

`func (o *ShippingInventoryApiListShippableContainersItem) HasTrackingNo() bool`

HasTrackingNo returns a boolean if a field has been set.

### GetLotNo

`func (o *ShippingInventoryApiListShippableContainersItem) GetLotNo() string`

GetLotNo returns the LotNo field if non-nil, zero value otherwise.

### GetLotNoOk

`func (o *ShippingInventoryApiListShippableContainersItem) GetLotNoOk() (*string, bool)`

GetLotNoOk returns a tuple with the LotNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLotNo

`func (o *ShippingInventoryApiListShippableContainersItem) SetLotNo(v string)`

SetLotNo sets LotNo field to given value.

### HasLotNo

`func (o *ShippingInventoryApiListShippableContainersItem) HasLotNo() bool`

HasLotNo returns a boolean if a field has been set.

### GetLotId

`func (o *ShippingInventoryApiListShippableContainersItem) GetLotId() string`

GetLotId returns the LotId field if non-nil, zero value otherwise.

### GetLotIdOk

`func (o *ShippingInventoryApiListShippableContainersItem) GetLotIdOk() (*string, bool)`

GetLotIdOk returns a tuple with the LotId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLotId

`func (o *ShippingInventoryApiListShippableContainersItem) SetLotId(v string)`

SetLotId sets LotId field to given value.

### HasLotId

`func (o *ShippingInventoryApiListShippableContainersItem) HasLotId() bool`

HasLotId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


