# InventoryOperationsManagementApiListContainersItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SerialNo** | Pointer to **string** | The serial number associated with the container. | [optional] 
**PartId** | Pointer to **string** | The ID of the part. | [optional] 
**PartNo** | Pointer to **string** | The part number associated to the &amp;quot;partId&amp;quot; that is produced. Acceptable part number characters include uppercase and lowercase letters (A-Z), numbers (0-9), and special characters such as dashes (-), underscores ( _ ), and spaces. Part numbers cannot use question marks or ampersands. Other characters may cause issues. | [optional] 
**Revision** | Pointer to **string** | The part revision associated with the container. 8 characters max. | [optional] 
**PartNoRevision** | Pointer to **string** | Format {partNumber}{part rev separator}{revision}. If a part number has a revision, Plex will return the part number and the revision separated by the Part Rev Separator setting. | [optional] 
**PartName** | Pointer to **string** | The name of the part. | [optional] 
**PartOperationId** | Pointer to **string** | The ID of the part operation. | [optional] 
**OperationNo** | Pointer to **int32** | The operation number associated with the part operation. | [optional] 
**OperationCode** | Pointer to **string** | The operation code associated with the &amp;quot;partOperationId&amp;quot;. 30 characters max. | [optional] 
**ContainerStatus** | Pointer to **string** | The status of the container. | [optional] 
**LocationId** | Pointer to **string** | The ID of location. | [optional] 
**Location** | Pointer to **string** | The location name associated with the &amp;quot;locationId&amp;quot;. | [optional] 
**Quantity** | Pointer to **float64** | The container quantity value. | [optional] 
**QuantityInventoryUnit** | Pointer to **string** | The unit of measure associated with the container quantity. | [optional] 
**GrossWeight** | Pointer to **float64** | The gross weight of the container. | [optional] 
**NetWeight** | Pointer to **float64** | The net weight of the container. | [optional] 
**TareWeight** | Pointer to **float64** | The tare weight of the container. | [optional] 
**ContainerType** | Pointer to **string** | The container type. | [optional] 
**TrackingNo** | Pointer to **string** | The tracking number associated with the container. | [optional] 
**AddDateTime** | Pointer to **time.Time** | The date and time when the container was added to the system. | [optional] 
**UpdateDateTime** | Pointer to **time.Time** | The date and time when the container was last updated. | [optional] 
**ContainerShelfDateTime** | Pointer to **time.Time** | The container shelf date. | [optional] 
**MasterUnitId** | Pointer to **string** | The ID of the master unit associated with the container. | [optional] 
**MasterUnitNo** | Pointer to **string** | The unit number associated with the &amp;quot;masterUnitId&amp;quot;. | [optional] 
**LotId** | Pointer to **string** | The lot ID associated with the container. | [optional] 
**LotNo** | Pointer to **string** | The unique lot number for the container. 25 characters max. | [optional] 
**HeatId** | Pointer to **string** | The ID associated with the heat. | [optional] 
**HeatCode** | Pointer to **string** | The heat code associated with the &amp;quot;heatId&amp;quot;. | [optional] 
**HeatNo** | Pointer to **string** | The heat number associated with the &amp;quot;heatId&amp;quot;. | [optional] 
**Eun** | Pointer to **string** | The EUN associated with the container. | [optional] 
**InventoryType** | Pointer to **string** | The Inventory Type associated with the container. | [optional] 

## Methods

### NewInventoryOperationsManagementApiListContainersItem

`func NewInventoryOperationsManagementApiListContainersItem() *InventoryOperationsManagementApiListContainersItem`

NewInventoryOperationsManagementApiListContainersItem instantiates a new InventoryOperationsManagementApiListContainersItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInventoryOperationsManagementApiListContainersItemWithDefaults

`func NewInventoryOperationsManagementApiListContainersItemWithDefaults() *InventoryOperationsManagementApiListContainersItem`

NewInventoryOperationsManagementApiListContainersItemWithDefaults instantiates a new InventoryOperationsManagementApiListContainersItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSerialNo

`func (o *InventoryOperationsManagementApiListContainersItem) GetSerialNo() string`

GetSerialNo returns the SerialNo field if non-nil, zero value otherwise.

### GetSerialNoOk

`func (o *InventoryOperationsManagementApiListContainersItem) GetSerialNoOk() (*string, bool)`

GetSerialNoOk returns a tuple with the SerialNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSerialNo

`func (o *InventoryOperationsManagementApiListContainersItem) SetSerialNo(v string)`

SetSerialNo sets SerialNo field to given value.

### HasSerialNo

`func (o *InventoryOperationsManagementApiListContainersItem) HasSerialNo() bool`

HasSerialNo returns a boolean if a field has been set.

### GetPartId

`func (o *InventoryOperationsManagementApiListContainersItem) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *InventoryOperationsManagementApiListContainersItem) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *InventoryOperationsManagementApiListContainersItem) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *InventoryOperationsManagementApiListContainersItem) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetPartNo

`func (o *InventoryOperationsManagementApiListContainersItem) GetPartNo() string`

GetPartNo returns the PartNo field if non-nil, zero value otherwise.

### GetPartNoOk

`func (o *InventoryOperationsManagementApiListContainersItem) GetPartNoOk() (*string, bool)`

GetPartNoOk returns a tuple with the PartNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNo

`func (o *InventoryOperationsManagementApiListContainersItem) SetPartNo(v string)`

SetPartNo sets PartNo field to given value.

### HasPartNo

`func (o *InventoryOperationsManagementApiListContainersItem) HasPartNo() bool`

HasPartNo returns a boolean if a field has been set.

### GetRevision

`func (o *InventoryOperationsManagementApiListContainersItem) GetRevision() string`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *InventoryOperationsManagementApiListContainersItem) GetRevisionOk() (*string, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *InventoryOperationsManagementApiListContainersItem) SetRevision(v string)`

SetRevision sets Revision field to given value.

### HasRevision

`func (o *InventoryOperationsManagementApiListContainersItem) HasRevision() bool`

HasRevision returns a boolean if a field has been set.

### GetPartNoRevision

`func (o *InventoryOperationsManagementApiListContainersItem) GetPartNoRevision() string`

GetPartNoRevision returns the PartNoRevision field if non-nil, zero value otherwise.

### GetPartNoRevisionOk

`func (o *InventoryOperationsManagementApiListContainersItem) GetPartNoRevisionOk() (*string, bool)`

GetPartNoRevisionOk returns a tuple with the PartNoRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNoRevision

`func (o *InventoryOperationsManagementApiListContainersItem) SetPartNoRevision(v string)`

SetPartNoRevision sets PartNoRevision field to given value.

### HasPartNoRevision

`func (o *InventoryOperationsManagementApiListContainersItem) HasPartNoRevision() bool`

HasPartNoRevision returns a boolean if a field has been set.

### GetPartName

`func (o *InventoryOperationsManagementApiListContainersItem) GetPartName() string`

GetPartName returns the PartName field if non-nil, zero value otherwise.

### GetPartNameOk

`func (o *InventoryOperationsManagementApiListContainersItem) GetPartNameOk() (*string, bool)`

GetPartNameOk returns a tuple with the PartName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartName

`func (o *InventoryOperationsManagementApiListContainersItem) SetPartName(v string)`

SetPartName sets PartName field to given value.

### HasPartName

`func (o *InventoryOperationsManagementApiListContainersItem) HasPartName() bool`

HasPartName returns a boolean if a field has been set.

### GetPartOperationId

`func (o *InventoryOperationsManagementApiListContainersItem) GetPartOperationId() string`

GetPartOperationId returns the PartOperationId field if non-nil, zero value otherwise.

### GetPartOperationIdOk

`func (o *InventoryOperationsManagementApiListContainersItem) GetPartOperationIdOk() (*string, bool)`

GetPartOperationIdOk returns a tuple with the PartOperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartOperationId

`func (o *InventoryOperationsManagementApiListContainersItem) SetPartOperationId(v string)`

SetPartOperationId sets PartOperationId field to given value.

### HasPartOperationId

`func (o *InventoryOperationsManagementApiListContainersItem) HasPartOperationId() bool`

HasPartOperationId returns a boolean if a field has been set.

### GetOperationNo

`func (o *InventoryOperationsManagementApiListContainersItem) GetOperationNo() int32`

GetOperationNo returns the OperationNo field if non-nil, zero value otherwise.

### GetOperationNoOk

`func (o *InventoryOperationsManagementApiListContainersItem) GetOperationNoOk() (*int32, bool)`

GetOperationNoOk returns a tuple with the OperationNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationNo

`func (o *InventoryOperationsManagementApiListContainersItem) SetOperationNo(v int32)`

SetOperationNo sets OperationNo field to given value.

### HasOperationNo

`func (o *InventoryOperationsManagementApiListContainersItem) HasOperationNo() bool`

HasOperationNo returns a boolean if a field has been set.

### GetOperationCode

`func (o *InventoryOperationsManagementApiListContainersItem) GetOperationCode() string`

GetOperationCode returns the OperationCode field if non-nil, zero value otherwise.

### GetOperationCodeOk

`func (o *InventoryOperationsManagementApiListContainersItem) GetOperationCodeOk() (*string, bool)`

GetOperationCodeOk returns a tuple with the OperationCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationCode

`func (o *InventoryOperationsManagementApiListContainersItem) SetOperationCode(v string)`

SetOperationCode sets OperationCode field to given value.

### HasOperationCode

`func (o *InventoryOperationsManagementApiListContainersItem) HasOperationCode() bool`

HasOperationCode returns a boolean if a field has been set.

### GetContainerStatus

`func (o *InventoryOperationsManagementApiListContainersItem) GetContainerStatus() string`

GetContainerStatus returns the ContainerStatus field if non-nil, zero value otherwise.

### GetContainerStatusOk

`func (o *InventoryOperationsManagementApiListContainersItem) GetContainerStatusOk() (*string, bool)`

GetContainerStatusOk returns a tuple with the ContainerStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContainerStatus

`func (o *InventoryOperationsManagementApiListContainersItem) SetContainerStatus(v string)`

SetContainerStatus sets ContainerStatus field to given value.

### HasContainerStatus

`func (o *InventoryOperationsManagementApiListContainersItem) HasContainerStatus() bool`

HasContainerStatus returns a boolean if a field has been set.

### GetLocationId

`func (o *InventoryOperationsManagementApiListContainersItem) GetLocationId() string`

GetLocationId returns the LocationId field if non-nil, zero value otherwise.

### GetLocationIdOk

`func (o *InventoryOperationsManagementApiListContainersItem) GetLocationIdOk() (*string, bool)`

GetLocationIdOk returns a tuple with the LocationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocationId

`func (o *InventoryOperationsManagementApiListContainersItem) SetLocationId(v string)`

SetLocationId sets LocationId field to given value.

### HasLocationId

`func (o *InventoryOperationsManagementApiListContainersItem) HasLocationId() bool`

HasLocationId returns a boolean if a field has been set.

### GetLocation

`func (o *InventoryOperationsManagementApiListContainersItem) GetLocation() string`

GetLocation returns the Location field if non-nil, zero value otherwise.

### GetLocationOk

`func (o *InventoryOperationsManagementApiListContainersItem) GetLocationOk() (*string, bool)`

GetLocationOk returns a tuple with the Location field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocation

`func (o *InventoryOperationsManagementApiListContainersItem) SetLocation(v string)`

SetLocation sets Location field to given value.

### HasLocation

`func (o *InventoryOperationsManagementApiListContainersItem) HasLocation() bool`

HasLocation returns a boolean if a field has been set.

### GetQuantity

`func (o *InventoryOperationsManagementApiListContainersItem) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *InventoryOperationsManagementApiListContainersItem) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *InventoryOperationsManagementApiListContainersItem) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *InventoryOperationsManagementApiListContainersItem) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetQuantityInventoryUnit

`func (o *InventoryOperationsManagementApiListContainersItem) GetQuantityInventoryUnit() string`

GetQuantityInventoryUnit returns the QuantityInventoryUnit field if non-nil, zero value otherwise.

### GetQuantityInventoryUnitOk

`func (o *InventoryOperationsManagementApiListContainersItem) GetQuantityInventoryUnitOk() (*string, bool)`

GetQuantityInventoryUnitOk returns a tuple with the QuantityInventoryUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantityInventoryUnit

`func (o *InventoryOperationsManagementApiListContainersItem) SetQuantityInventoryUnit(v string)`

SetQuantityInventoryUnit sets QuantityInventoryUnit field to given value.

### HasQuantityInventoryUnit

`func (o *InventoryOperationsManagementApiListContainersItem) HasQuantityInventoryUnit() bool`

HasQuantityInventoryUnit returns a boolean if a field has been set.

### GetGrossWeight

`func (o *InventoryOperationsManagementApiListContainersItem) GetGrossWeight() float64`

GetGrossWeight returns the GrossWeight field if non-nil, zero value otherwise.

### GetGrossWeightOk

`func (o *InventoryOperationsManagementApiListContainersItem) GetGrossWeightOk() (*float64, bool)`

GetGrossWeightOk returns a tuple with the GrossWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrossWeight

`func (o *InventoryOperationsManagementApiListContainersItem) SetGrossWeight(v float64)`

SetGrossWeight sets GrossWeight field to given value.

### HasGrossWeight

`func (o *InventoryOperationsManagementApiListContainersItem) HasGrossWeight() bool`

HasGrossWeight returns a boolean if a field has been set.

### GetNetWeight

`func (o *InventoryOperationsManagementApiListContainersItem) GetNetWeight() float64`

GetNetWeight returns the NetWeight field if non-nil, zero value otherwise.

### GetNetWeightOk

`func (o *InventoryOperationsManagementApiListContainersItem) GetNetWeightOk() (*float64, bool)`

GetNetWeightOk returns a tuple with the NetWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetWeight

`func (o *InventoryOperationsManagementApiListContainersItem) SetNetWeight(v float64)`

SetNetWeight sets NetWeight field to given value.

### HasNetWeight

`func (o *InventoryOperationsManagementApiListContainersItem) HasNetWeight() bool`

HasNetWeight returns a boolean if a field has been set.

### GetTareWeight

`func (o *InventoryOperationsManagementApiListContainersItem) GetTareWeight() float64`

GetTareWeight returns the TareWeight field if non-nil, zero value otherwise.

### GetTareWeightOk

`func (o *InventoryOperationsManagementApiListContainersItem) GetTareWeightOk() (*float64, bool)`

GetTareWeightOk returns a tuple with the TareWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTareWeight

`func (o *InventoryOperationsManagementApiListContainersItem) SetTareWeight(v float64)`

SetTareWeight sets TareWeight field to given value.

### HasTareWeight

`func (o *InventoryOperationsManagementApiListContainersItem) HasTareWeight() bool`

HasTareWeight returns a boolean if a field has been set.

### GetContainerType

`func (o *InventoryOperationsManagementApiListContainersItem) GetContainerType() string`

GetContainerType returns the ContainerType field if non-nil, zero value otherwise.

### GetContainerTypeOk

`func (o *InventoryOperationsManagementApiListContainersItem) GetContainerTypeOk() (*string, bool)`

GetContainerTypeOk returns a tuple with the ContainerType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContainerType

`func (o *InventoryOperationsManagementApiListContainersItem) SetContainerType(v string)`

SetContainerType sets ContainerType field to given value.

### HasContainerType

`func (o *InventoryOperationsManagementApiListContainersItem) HasContainerType() bool`

HasContainerType returns a boolean if a field has been set.

### GetTrackingNo

`func (o *InventoryOperationsManagementApiListContainersItem) GetTrackingNo() string`

GetTrackingNo returns the TrackingNo field if non-nil, zero value otherwise.

### GetTrackingNoOk

`func (o *InventoryOperationsManagementApiListContainersItem) GetTrackingNoOk() (*string, bool)`

GetTrackingNoOk returns a tuple with the TrackingNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackingNo

`func (o *InventoryOperationsManagementApiListContainersItem) SetTrackingNo(v string)`

SetTrackingNo sets TrackingNo field to given value.

### HasTrackingNo

`func (o *InventoryOperationsManagementApiListContainersItem) HasTrackingNo() bool`

HasTrackingNo returns a boolean if a field has been set.

### GetAddDateTime

`func (o *InventoryOperationsManagementApiListContainersItem) GetAddDateTime() time.Time`

GetAddDateTime returns the AddDateTime field if non-nil, zero value otherwise.

### GetAddDateTimeOk

`func (o *InventoryOperationsManagementApiListContainersItem) GetAddDateTimeOk() (*time.Time, bool)`

GetAddDateTimeOk returns a tuple with the AddDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddDateTime

`func (o *InventoryOperationsManagementApiListContainersItem) SetAddDateTime(v time.Time)`

SetAddDateTime sets AddDateTime field to given value.

### HasAddDateTime

`func (o *InventoryOperationsManagementApiListContainersItem) HasAddDateTime() bool`

HasAddDateTime returns a boolean if a field has been set.

### GetUpdateDateTime

`func (o *InventoryOperationsManagementApiListContainersItem) GetUpdateDateTime() time.Time`

GetUpdateDateTime returns the UpdateDateTime field if non-nil, zero value otherwise.

### GetUpdateDateTimeOk

`func (o *InventoryOperationsManagementApiListContainersItem) GetUpdateDateTimeOk() (*time.Time, bool)`

GetUpdateDateTimeOk returns a tuple with the UpdateDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdateDateTime

`func (o *InventoryOperationsManagementApiListContainersItem) SetUpdateDateTime(v time.Time)`

SetUpdateDateTime sets UpdateDateTime field to given value.

### HasUpdateDateTime

`func (o *InventoryOperationsManagementApiListContainersItem) HasUpdateDateTime() bool`

HasUpdateDateTime returns a boolean if a field has been set.

### GetContainerShelfDateTime

`func (o *InventoryOperationsManagementApiListContainersItem) GetContainerShelfDateTime() time.Time`

GetContainerShelfDateTime returns the ContainerShelfDateTime field if non-nil, zero value otherwise.

### GetContainerShelfDateTimeOk

`func (o *InventoryOperationsManagementApiListContainersItem) GetContainerShelfDateTimeOk() (*time.Time, bool)`

GetContainerShelfDateTimeOk returns a tuple with the ContainerShelfDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContainerShelfDateTime

`func (o *InventoryOperationsManagementApiListContainersItem) SetContainerShelfDateTime(v time.Time)`

SetContainerShelfDateTime sets ContainerShelfDateTime field to given value.

### HasContainerShelfDateTime

`func (o *InventoryOperationsManagementApiListContainersItem) HasContainerShelfDateTime() bool`

HasContainerShelfDateTime returns a boolean if a field has been set.

### GetMasterUnitId

`func (o *InventoryOperationsManagementApiListContainersItem) GetMasterUnitId() string`

GetMasterUnitId returns the MasterUnitId field if non-nil, zero value otherwise.

### GetMasterUnitIdOk

`func (o *InventoryOperationsManagementApiListContainersItem) GetMasterUnitIdOk() (*string, bool)`

GetMasterUnitIdOk returns a tuple with the MasterUnitId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMasterUnitId

`func (o *InventoryOperationsManagementApiListContainersItem) SetMasterUnitId(v string)`

SetMasterUnitId sets MasterUnitId field to given value.

### HasMasterUnitId

`func (o *InventoryOperationsManagementApiListContainersItem) HasMasterUnitId() bool`

HasMasterUnitId returns a boolean if a field has been set.

### GetMasterUnitNo

`func (o *InventoryOperationsManagementApiListContainersItem) GetMasterUnitNo() string`

GetMasterUnitNo returns the MasterUnitNo field if non-nil, zero value otherwise.

### GetMasterUnitNoOk

`func (o *InventoryOperationsManagementApiListContainersItem) GetMasterUnitNoOk() (*string, bool)`

GetMasterUnitNoOk returns a tuple with the MasterUnitNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMasterUnitNo

`func (o *InventoryOperationsManagementApiListContainersItem) SetMasterUnitNo(v string)`

SetMasterUnitNo sets MasterUnitNo field to given value.

### HasMasterUnitNo

`func (o *InventoryOperationsManagementApiListContainersItem) HasMasterUnitNo() bool`

HasMasterUnitNo returns a boolean if a field has been set.

### GetLotId

`func (o *InventoryOperationsManagementApiListContainersItem) GetLotId() string`

GetLotId returns the LotId field if non-nil, zero value otherwise.

### GetLotIdOk

`func (o *InventoryOperationsManagementApiListContainersItem) GetLotIdOk() (*string, bool)`

GetLotIdOk returns a tuple with the LotId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLotId

`func (o *InventoryOperationsManagementApiListContainersItem) SetLotId(v string)`

SetLotId sets LotId field to given value.

### HasLotId

`func (o *InventoryOperationsManagementApiListContainersItem) HasLotId() bool`

HasLotId returns a boolean if a field has been set.

### GetLotNo

`func (o *InventoryOperationsManagementApiListContainersItem) GetLotNo() string`

GetLotNo returns the LotNo field if non-nil, zero value otherwise.

### GetLotNoOk

`func (o *InventoryOperationsManagementApiListContainersItem) GetLotNoOk() (*string, bool)`

GetLotNoOk returns a tuple with the LotNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLotNo

`func (o *InventoryOperationsManagementApiListContainersItem) SetLotNo(v string)`

SetLotNo sets LotNo field to given value.

### HasLotNo

`func (o *InventoryOperationsManagementApiListContainersItem) HasLotNo() bool`

HasLotNo returns a boolean if a field has been set.

### GetHeatId

`func (o *InventoryOperationsManagementApiListContainersItem) GetHeatId() string`

GetHeatId returns the HeatId field if non-nil, zero value otherwise.

### GetHeatIdOk

`func (o *InventoryOperationsManagementApiListContainersItem) GetHeatIdOk() (*string, bool)`

GetHeatIdOk returns a tuple with the HeatId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeatId

`func (o *InventoryOperationsManagementApiListContainersItem) SetHeatId(v string)`

SetHeatId sets HeatId field to given value.

### HasHeatId

`func (o *InventoryOperationsManagementApiListContainersItem) HasHeatId() bool`

HasHeatId returns a boolean if a field has been set.

### GetHeatCode

`func (o *InventoryOperationsManagementApiListContainersItem) GetHeatCode() string`

GetHeatCode returns the HeatCode field if non-nil, zero value otherwise.

### GetHeatCodeOk

`func (o *InventoryOperationsManagementApiListContainersItem) GetHeatCodeOk() (*string, bool)`

GetHeatCodeOk returns a tuple with the HeatCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeatCode

`func (o *InventoryOperationsManagementApiListContainersItem) SetHeatCode(v string)`

SetHeatCode sets HeatCode field to given value.

### HasHeatCode

`func (o *InventoryOperationsManagementApiListContainersItem) HasHeatCode() bool`

HasHeatCode returns a boolean if a field has been set.

### GetHeatNo

`func (o *InventoryOperationsManagementApiListContainersItem) GetHeatNo() string`

GetHeatNo returns the HeatNo field if non-nil, zero value otherwise.

### GetHeatNoOk

`func (o *InventoryOperationsManagementApiListContainersItem) GetHeatNoOk() (*string, bool)`

GetHeatNoOk returns a tuple with the HeatNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeatNo

`func (o *InventoryOperationsManagementApiListContainersItem) SetHeatNo(v string)`

SetHeatNo sets HeatNo field to given value.

### HasHeatNo

`func (o *InventoryOperationsManagementApiListContainersItem) HasHeatNo() bool`

HasHeatNo returns a boolean if a field has been set.

### GetEun

`func (o *InventoryOperationsManagementApiListContainersItem) GetEun() string`

GetEun returns the Eun field if non-nil, zero value otherwise.

### GetEunOk

`func (o *InventoryOperationsManagementApiListContainersItem) GetEunOk() (*string, bool)`

GetEunOk returns a tuple with the Eun field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEun

`func (o *InventoryOperationsManagementApiListContainersItem) SetEun(v string)`

SetEun sets Eun field to given value.

### HasEun

`func (o *InventoryOperationsManagementApiListContainersItem) HasEun() bool`

HasEun returns a boolean if a field has been set.

### GetInventoryType

`func (o *InventoryOperationsManagementApiListContainersItem) GetInventoryType() string`

GetInventoryType returns the InventoryType field if non-nil, zero value otherwise.

### GetInventoryTypeOk

`func (o *InventoryOperationsManagementApiListContainersItem) GetInventoryTypeOk() (*string, bool)`

GetInventoryTypeOk returns a tuple with the InventoryType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInventoryType

`func (o *InventoryOperationsManagementApiListContainersItem) SetInventoryType(v string)`

SetInventoryType sets InventoryType field to given value.

### HasInventoryType

`func (o *InventoryOperationsManagementApiListContainersItem) HasInventoryType() bool`

HasInventoryType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


