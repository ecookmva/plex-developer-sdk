# InventoryOperationsManagementApiGetContainerResponse

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

### NewInventoryOperationsManagementApiGetContainerResponse

`func NewInventoryOperationsManagementApiGetContainerResponse() *InventoryOperationsManagementApiGetContainerResponse`

NewInventoryOperationsManagementApiGetContainerResponse instantiates a new InventoryOperationsManagementApiGetContainerResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInventoryOperationsManagementApiGetContainerResponseWithDefaults

`func NewInventoryOperationsManagementApiGetContainerResponseWithDefaults() *InventoryOperationsManagementApiGetContainerResponse`

NewInventoryOperationsManagementApiGetContainerResponseWithDefaults instantiates a new InventoryOperationsManagementApiGetContainerResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSerialNo

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetSerialNo() string`

GetSerialNo returns the SerialNo field if non-nil, zero value otherwise.

### GetSerialNoOk

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetSerialNoOk() (*string, bool)`

GetSerialNoOk returns a tuple with the SerialNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSerialNo

`func (o *InventoryOperationsManagementApiGetContainerResponse) SetSerialNo(v string)`

SetSerialNo sets SerialNo field to given value.

### HasSerialNo

`func (o *InventoryOperationsManagementApiGetContainerResponse) HasSerialNo() bool`

HasSerialNo returns a boolean if a field has been set.

### GetPartId

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *InventoryOperationsManagementApiGetContainerResponse) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *InventoryOperationsManagementApiGetContainerResponse) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetPartNo

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetPartNo() string`

GetPartNo returns the PartNo field if non-nil, zero value otherwise.

### GetPartNoOk

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetPartNoOk() (*string, bool)`

GetPartNoOk returns a tuple with the PartNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNo

`func (o *InventoryOperationsManagementApiGetContainerResponse) SetPartNo(v string)`

SetPartNo sets PartNo field to given value.

### HasPartNo

`func (o *InventoryOperationsManagementApiGetContainerResponse) HasPartNo() bool`

HasPartNo returns a boolean if a field has been set.

### GetRevision

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetRevision() string`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetRevisionOk() (*string, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *InventoryOperationsManagementApiGetContainerResponse) SetRevision(v string)`

SetRevision sets Revision field to given value.

### HasRevision

`func (o *InventoryOperationsManagementApiGetContainerResponse) HasRevision() bool`

HasRevision returns a boolean if a field has been set.

### GetPartNoRevision

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetPartNoRevision() string`

GetPartNoRevision returns the PartNoRevision field if non-nil, zero value otherwise.

### GetPartNoRevisionOk

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetPartNoRevisionOk() (*string, bool)`

GetPartNoRevisionOk returns a tuple with the PartNoRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNoRevision

`func (o *InventoryOperationsManagementApiGetContainerResponse) SetPartNoRevision(v string)`

SetPartNoRevision sets PartNoRevision field to given value.

### HasPartNoRevision

`func (o *InventoryOperationsManagementApiGetContainerResponse) HasPartNoRevision() bool`

HasPartNoRevision returns a boolean if a field has been set.

### GetPartName

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetPartName() string`

GetPartName returns the PartName field if non-nil, zero value otherwise.

### GetPartNameOk

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetPartNameOk() (*string, bool)`

GetPartNameOk returns a tuple with the PartName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartName

`func (o *InventoryOperationsManagementApiGetContainerResponse) SetPartName(v string)`

SetPartName sets PartName field to given value.

### HasPartName

`func (o *InventoryOperationsManagementApiGetContainerResponse) HasPartName() bool`

HasPartName returns a boolean if a field has been set.

### GetPartOperationId

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetPartOperationId() string`

GetPartOperationId returns the PartOperationId field if non-nil, zero value otherwise.

### GetPartOperationIdOk

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetPartOperationIdOk() (*string, bool)`

GetPartOperationIdOk returns a tuple with the PartOperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartOperationId

`func (o *InventoryOperationsManagementApiGetContainerResponse) SetPartOperationId(v string)`

SetPartOperationId sets PartOperationId field to given value.

### HasPartOperationId

`func (o *InventoryOperationsManagementApiGetContainerResponse) HasPartOperationId() bool`

HasPartOperationId returns a boolean if a field has been set.

### GetOperationNo

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetOperationNo() int32`

GetOperationNo returns the OperationNo field if non-nil, zero value otherwise.

### GetOperationNoOk

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetOperationNoOk() (*int32, bool)`

GetOperationNoOk returns a tuple with the OperationNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationNo

`func (o *InventoryOperationsManagementApiGetContainerResponse) SetOperationNo(v int32)`

SetOperationNo sets OperationNo field to given value.

### HasOperationNo

`func (o *InventoryOperationsManagementApiGetContainerResponse) HasOperationNo() bool`

HasOperationNo returns a boolean if a field has been set.

### GetOperationCode

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetOperationCode() string`

GetOperationCode returns the OperationCode field if non-nil, zero value otherwise.

### GetOperationCodeOk

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetOperationCodeOk() (*string, bool)`

GetOperationCodeOk returns a tuple with the OperationCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationCode

`func (o *InventoryOperationsManagementApiGetContainerResponse) SetOperationCode(v string)`

SetOperationCode sets OperationCode field to given value.

### HasOperationCode

`func (o *InventoryOperationsManagementApiGetContainerResponse) HasOperationCode() bool`

HasOperationCode returns a boolean if a field has been set.

### GetContainerStatus

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetContainerStatus() string`

GetContainerStatus returns the ContainerStatus field if non-nil, zero value otherwise.

### GetContainerStatusOk

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetContainerStatusOk() (*string, bool)`

GetContainerStatusOk returns a tuple with the ContainerStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContainerStatus

`func (o *InventoryOperationsManagementApiGetContainerResponse) SetContainerStatus(v string)`

SetContainerStatus sets ContainerStatus field to given value.

### HasContainerStatus

`func (o *InventoryOperationsManagementApiGetContainerResponse) HasContainerStatus() bool`

HasContainerStatus returns a boolean if a field has been set.

### GetLocationId

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetLocationId() string`

GetLocationId returns the LocationId field if non-nil, zero value otherwise.

### GetLocationIdOk

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetLocationIdOk() (*string, bool)`

GetLocationIdOk returns a tuple with the LocationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocationId

`func (o *InventoryOperationsManagementApiGetContainerResponse) SetLocationId(v string)`

SetLocationId sets LocationId field to given value.

### HasLocationId

`func (o *InventoryOperationsManagementApiGetContainerResponse) HasLocationId() bool`

HasLocationId returns a boolean if a field has been set.

### GetLocation

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetLocation() string`

GetLocation returns the Location field if non-nil, zero value otherwise.

### GetLocationOk

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetLocationOk() (*string, bool)`

GetLocationOk returns a tuple with the Location field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocation

`func (o *InventoryOperationsManagementApiGetContainerResponse) SetLocation(v string)`

SetLocation sets Location field to given value.

### HasLocation

`func (o *InventoryOperationsManagementApiGetContainerResponse) HasLocation() bool`

HasLocation returns a boolean if a field has been set.

### GetQuantity

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *InventoryOperationsManagementApiGetContainerResponse) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *InventoryOperationsManagementApiGetContainerResponse) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetQuantityInventoryUnit

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetQuantityInventoryUnit() string`

GetQuantityInventoryUnit returns the QuantityInventoryUnit field if non-nil, zero value otherwise.

### GetQuantityInventoryUnitOk

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetQuantityInventoryUnitOk() (*string, bool)`

GetQuantityInventoryUnitOk returns a tuple with the QuantityInventoryUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantityInventoryUnit

`func (o *InventoryOperationsManagementApiGetContainerResponse) SetQuantityInventoryUnit(v string)`

SetQuantityInventoryUnit sets QuantityInventoryUnit field to given value.

### HasQuantityInventoryUnit

`func (o *InventoryOperationsManagementApiGetContainerResponse) HasQuantityInventoryUnit() bool`

HasQuantityInventoryUnit returns a boolean if a field has been set.

### GetGrossWeight

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetGrossWeight() float64`

GetGrossWeight returns the GrossWeight field if non-nil, zero value otherwise.

### GetGrossWeightOk

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetGrossWeightOk() (*float64, bool)`

GetGrossWeightOk returns a tuple with the GrossWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrossWeight

`func (o *InventoryOperationsManagementApiGetContainerResponse) SetGrossWeight(v float64)`

SetGrossWeight sets GrossWeight field to given value.

### HasGrossWeight

`func (o *InventoryOperationsManagementApiGetContainerResponse) HasGrossWeight() bool`

HasGrossWeight returns a boolean if a field has been set.

### GetNetWeight

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetNetWeight() float64`

GetNetWeight returns the NetWeight field if non-nil, zero value otherwise.

### GetNetWeightOk

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetNetWeightOk() (*float64, bool)`

GetNetWeightOk returns a tuple with the NetWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetWeight

`func (o *InventoryOperationsManagementApiGetContainerResponse) SetNetWeight(v float64)`

SetNetWeight sets NetWeight field to given value.

### HasNetWeight

`func (o *InventoryOperationsManagementApiGetContainerResponse) HasNetWeight() bool`

HasNetWeight returns a boolean if a field has been set.

### GetTareWeight

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetTareWeight() float64`

GetTareWeight returns the TareWeight field if non-nil, zero value otherwise.

### GetTareWeightOk

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetTareWeightOk() (*float64, bool)`

GetTareWeightOk returns a tuple with the TareWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTareWeight

`func (o *InventoryOperationsManagementApiGetContainerResponse) SetTareWeight(v float64)`

SetTareWeight sets TareWeight field to given value.

### HasTareWeight

`func (o *InventoryOperationsManagementApiGetContainerResponse) HasTareWeight() bool`

HasTareWeight returns a boolean if a field has been set.

### GetContainerType

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetContainerType() string`

GetContainerType returns the ContainerType field if non-nil, zero value otherwise.

### GetContainerTypeOk

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetContainerTypeOk() (*string, bool)`

GetContainerTypeOk returns a tuple with the ContainerType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContainerType

`func (o *InventoryOperationsManagementApiGetContainerResponse) SetContainerType(v string)`

SetContainerType sets ContainerType field to given value.

### HasContainerType

`func (o *InventoryOperationsManagementApiGetContainerResponse) HasContainerType() bool`

HasContainerType returns a boolean if a field has been set.

### GetTrackingNo

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetTrackingNo() string`

GetTrackingNo returns the TrackingNo field if non-nil, zero value otherwise.

### GetTrackingNoOk

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetTrackingNoOk() (*string, bool)`

GetTrackingNoOk returns a tuple with the TrackingNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackingNo

`func (o *InventoryOperationsManagementApiGetContainerResponse) SetTrackingNo(v string)`

SetTrackingNo sets TrackingNo field to given value.

### HasTrackingNo

`func (o *InventoryOperationsManagementApiGetContainerResponse) HasTrackingNo() bool`

HasTrackingNo returns a boolean if a field has been set.

### GetAddDateTime

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetAddDateTime() time.Time`

GetAddDateTime returns the AddDateTime field if non-nil, zero value otherwise.

### GetAddDateTimeOk

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetAddDateTimeOk() (*time.Time, bool)`

GetAddDateTimeOk returns a tuple with the AddDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddDateTime

`func (o *InventoryOperationsManagementApiGetContainerResponse) SetAddDateTime(v time.Time)`

SetAddDateTime sets AddDateTime field to given value.

### HasAddDateTime

`func (o *InventoryOperationsManagementApiGetContainerResponse) HasAddDateTime() bool`

HasAddDateTime returns a boolean if a field has been set.

### GetUpdateDateTime

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetUpdateDateTime() time.Time`

GetUpdateDateTime returns the UpdateDateTime field if non-nil, zero value otherwise.

### GetUpdateDateTimeOk

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetUpdateDateTimeOk() (*time.Time, bool)`

GetUpdateDateTimeOk returns a tuple with the UpdateDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdateDateTime

`func (o *InventoryOperationsManagementApiGetContainerResponse) SetUpdateDateTime(v time.Time)`

SetUpdateDateTime sets UpdateDateTime field to given value.

### HasUpdateDateTime

`func (o *InventoryOperationsManagementApiGetContainerResponse) HasUpdateDateTime() bool`

HasUpdateDateTime returns a boolean if a field has been set.

### GetContainerShelfDateTime

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetContainerShelfDateTime() time.Time`

GetContainerShelfDateTime returns the ContainerShelfDateTime field if non-nil, zero value otherwise.

### GetContainerShelfDateTimeOk

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetContainerShelfDateTimeOk() (*time.Time, bool)`

GetContainerShelfDateTimeOk returns a tuple with the ContainerShelfDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContainerShelfDateTime

`func (o *InventoryOperationsManagementApiGetContainerResponse) SetContainerShelfDateTime(v time.Time)`

SetContainerShelfDateTime sets ContainerShelfDateTime field to given value.

### HasContainerShelfDateTime

`func (o *InventoryOperationsManagementApiGetContainerResponse) HasContainerShelfDateTime() bool`

HasContainerShelfDateTime returns a boolean if a field has been set.

### GetMasterUnitId

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetMasterUnitId() string`

GetMasterUnitId returns the MasterUnitId field if non-nil, zero value otherwise.

### GetMasterUnitIdOk

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetMasterUnitIdOk() (*string, bool)`

GetMasterUnitIdOk returns a tuple with the MasterUnitId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMasterUnitId

`func (o *InventoryOperationsManagementApiGetContainerResponse) SetMasterUnitId(v string)`

SetMasterUnitId sets MasterUnitId field to given value.

### HasMasterUnitId

`func (o *InventoryOperationsManagementApiGetContainerResponse) HasMasterUnitId() bool`

HasMasterUnitId returns a boolean if a field has been set.

### GetMasterUnitNo

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetMasterUnitNo() string`

GetMasterUnitNo returns the MasterUnitNo field if non-nil, zero value otherwise.

### GetMasterUnitNoOk

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetMasterUnitNoOk() (*string, bool)`

GetMasterUnitNoOk returns a tuple with the MasterUnitNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMasterUnitNo

`func (o *InventoryOperationsManagementApiGetContainerResponse) SetMasterUnitNo(v string)`

SetMasterUnitNo sets MasterUnitNo field to given value.

### HasMasterUnitNo

`func (o *InventoryOperationsManagementApiGetContainerResponse) HasMasterUnitNo() bool`

HasMasterUnitNo returns a boolean if a field has been set.

### GetLotId

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetLotId() string`

GetLotId returns the LotId field if non-nil, zero value otherwise.

### GetLotIdOk

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetLotIdOk() (*string, bool)`

GetLotIdOk returns a tuple with the LotId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLotId

`func (o *InventoryOperationsManagementApiGetContainerResponse) SetLotId(v string)`

SetLotId sets LotId field to given value.

### HasLotId

`func (o *InventoryOperationsManagementApiGetContainerResponse) HasLotId() bool`

HasLotId returns a boolean if a field has been set.

### GetLotNo

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetLotNo() string`

GetLotNo returns the LotNo field if non-nil, zero value otherwise.

### GetLotNoOk

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetLotNoOk() (*string, bool)`

GetLotNoOk returns a tuple with the LotNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLotNo

`func (o *InventoryOperationsManagementApiGetContainerResponse) SetLotNo(v string)`

SetLotNo sets LotNo field to given value.

### HasLotNo

`func (o *InventoryOperationsManagementApiGetContainerResponse) HasLotNo() bool`

HasLotNo returns a boolean if a field has been set.

### GetHeatId

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetHeatId() string`

GetHeatId returns the HeatId field if non-nil, zero value otherwise.

### GetHeatIdOk

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetHeatIdOk() (*string, bool)`

GetHeatIdOk returns a tuple with the HeatId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeatId

`func (o *InventoryOperationsManagementApiGetContainerResponse) SetHeatId(v string)`

SetHeatId sets HeatId field to given value.

### HasHeatId

`func (o *InventoryOperationsManagementApiGetContainerResponse) HasHeatId() bool`

HasHeatId returns a boolean if a field has been set.

### GetHeatCode

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetHeatCode() string`

GetHeatCode returns the HeatCode field if non-nil, zero value otherwise.

### GetHeatCodeOk

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetHeatCodeOk() (*string, bool)`

GetHeatCodeOk returns a tuple with the HeatCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeatCode

`func (o *InventoryOperationsManagementApiGetContainerResponse) SetHeatCode(v string)`

SetHeatCode sets HeatCode field to given value.

### HasHeatCode

`func (o *InventoryOperationsManagementApiGetContainerResponse) HasHeatCode() bool`

HasHeatCode returns a boolean if a field has been set.

### GetHeatNo

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetHeatNo() string`

GetHeatNo returns the HeatNo field if non-nil, zero value otherwise.

### GetHeatNoOk

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetHeatNoOk() (*string, bool)`

GetHeatNoOk returns a tuple with the HeatNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeatNo

`func (o *InventoryOperationsManagementApiGetContainerResponse) SetHeatNo(v string)`

SetHeatNo sets HeatNo field to given value.

### HasHeatNo

`func (o *InventoryOperationsManagementApiGetContainerResponse) HasHeatNo() bool`

HasHeatNo returns a boolean if a field has been set.

### GetEun

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetEun() string`

GetEun returns the Eun field if non-nil, zero value otherwise.

### GetEunOk

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetEunOk() (*string, bool)`

GetEunOk returns a tuple with the Eun field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEun

`func (o *InventoryOperationsManagementApiGetContainerResponse) SetEun(v string)`

SetEun sets Eun field to given value.

### HasEun

`func (o *InventoryOperationsManagementApiGetContainerResponse) HasEun() bool`

HasEun returns a boolean if a field has been set.

### GetInventoryType

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetInventoryType() string`

GetInventoryType returns the InventoryType field if non-nil, zero value otherwise.

### GetInventoryTypeOk

`func (o *InventoryOperationsManagementApiGetContainerResponse) GetInventoryTypeOk() (*string, bool)`

GetInventoryTypeOk returns a tuple with the InventoryType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInventoryType

`func (o *InventoryOperationsManagementApiGetContainerResponse) SetInventoryType(v string)`

SetInventoryType sets InventoryType field to given value.

### HasInventoryType

`func (o *InventoryOperationsManagementApiGetContainerResponse) HasInventoryType() bool`

HasInventoryType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


