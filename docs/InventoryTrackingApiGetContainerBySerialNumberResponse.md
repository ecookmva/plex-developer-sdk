# InventoryTrackingApiGetContainerBySerialNumberResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SerialNumber** | Pointer to **string** | The serial number of the container. 25 characters max. | [optional] 
**Status** | Pointer to **string** | The container&#39;s status. | [optional] 
**PartId** | Pointer to **string** | The ID of the part that was produced. | [optional] 
**PartNumber** | Pointer to **string** | The part number associated to the &amp;quot;partId&amp;quot; that was produced. Acceptable part number characters include uppercase and lowercase letters (A-Z), numbers (0-9), and special characters such as dashes (-), underscores ( _ ), and spaces. Part numbers cannot use question marks (?) or ampersands. Other characters may cause issues. | [optional] 
**PartRevision** | Pointer to **string** | The part revision of the &amp;quot;partId&amp;quot;. A revision represents a change or modification to a part or part drawing that is usually initiated through an engineering change request (ECR). | [optional] 
**PartNumberRevision** | Pointer to **string** | The part number and revision formatted with separator. If a part number has a revision, Plex will return the part number and the revision separated by the Part Rev Separator setting. A Part Rev Separator can be up to 5 characters long. Format: {partNumber}{part rev separator}{revision}. | [optional] 
**PartOperationId** | Pointer to **string** | The ID of the part operation. | [optional] 
**OperationNumber** | Pointer to **int32** | The operation number of the part operation. | [optional] 
**OperationCode** | Pointer to **string** | The operation code associated to the &amp;quot;partOperationId&amp;quot;. 30 characters max. | [optional] 
**Location** | Pointer to **string** | The container&#39;s location. | [optional] 
**JobNumber** | Pointer to **string** | The unique job number. 20 characters max. | [optional] 
**JobId** | Pointer to **string** | The ID of the production job that production was recorded against. Note that a production job is not necessary to record production. Another scheduling method such as Kanban may have been used. | [optional] 
**Type** | Pointer to **string** | The container type of the container&#39;s. | [optional] 
**Quantity** | Pointer to **float64** | The container&#39;s part quantity. | [optional] 
**Active** | Pointer to **bool** | The container&#39;s active status (active or inactive). | [optional] 
**CreatedDate** | Pointer to **time.Time** | The date on which the container record was added. | [optional] 
**ModifiedDate** | Pointer to **time.Time** | The date on which the container record was updated. | [optional] 
**QuantityUnit** | Pointer to **string** | The unit used for the container quantity, as defined on the operation. | [optional] 
**GrossWeight** | Pointer to **float64** | The container&#39;s gross weight. | [optional] 
**NetWeight** | Pointer to **float64** | The container&#39;s net weight. | [optional] 
**TareWeight** | Pointer to **float64** | The container&#39;s tare weight. | [optional] 
**TrackingNumber** | Pointer to **string** | The tracking number of the container. 50 characters max. | [optional] 
**HeatNumber** | Pointer to **string** | The heat number of the heat. 30 characters max. | [optional] 
**LotNumber** | Pointer to **string** | The unique lot number. 25 characters max. | [optional] 
**MasterUnitNo** | Pointer to **string** | The master unit number of the master unit. 10 characters max. | [optional] 
**MasterUnitId** | Pointer to **string** | The master unit resource ID. | [optional] 
**LotId** | Pointer to **string** | The lot resource ID. | [optional] 
**HeatCode** | Pointer to **string** | The heat code of the heat. 50 characters max. | [optional] 
**HeatId** | Pointer to **string** | The material heat resource ID. | [optional] 
**ShelfDateTime** | Pointer to **time.Time** | The shelf life date of the container. | [optional] 
**ManufacturedDateTime** | Pointer to **time.Time** | The date a lot was manufactured, either in Plex or by a supplier or subcontractor. | [optional] 
**BestByDateTime** | Pointer to **time.Time** | The best-by date which represents the last date for consumption of products in a lot by consumers. | [optional] 
**UseByDateTime** | Pointer to **time.Time** | The last date to use a lot for production. | [optional] 
**SellByDateTime** | Pointer to **time.Time** | The last date for the sale of a product in a lot to consumers. | [optional] 
**Rfid** | Pointer to **string** | The RFID of the container. Maximum length is 64 characters. | [optional] 

## Methods

### NewInventoryTrackingApiGetContainerBySerialNumberResponse

`func NewInventoryTrackingApiGetContainerBySerialNumberResponse() *InventoryTrackingApiGetContainerBySerialNumberResponse`

NewInventoryTrackingApiGetContainerBySerialNumberResponse instantiates a new InventoryTrackingApiGetContainerBySerialNumberResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInventoryTrackingApiGetContainerBySerialNumberResponseWithDefaults

`func NewInventoryTrackingApiGetContainerBySerialNumberResponseWithDefaults() *InventoryTrackingApiGetContainerBySerialNumberResponse`

NewInventoryTrackingApiGetContainerBySerialNumberResponseWithDefaults instantiates a new InventoryTrackingApiGetContainerBySerialNumberResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSerialNumber

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetSerialNumber() string`

GetSerialNumber returns the SerialNumber field if non-nil, zero value otherwise.

### GetSerialNumberOk

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetSerialNumberOk() (*string, bool)`

GetSerialNumberOk returns a tuple with the SerialNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSerialNumber

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) SetSerialNumber(v string)`

SetSerialNumber sets SerialNumber field to given value.

### HasSerialNumber

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) HasSerialNumber() bool`

HasSerialNumber returns a boolean if a field has been set.

### GetStatus

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetPartId

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetPartNumber

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetPartNumber() string`

GetPartNumber returns the PartNumber field if non-nil, zero value otherwise.

### GetPartNumberOk

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetPartNumberOk() (*string, bool)`

GetPartNumberOk returns a tuple with the PartNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumber

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) SetPartNumber(v string)`

SetPartNumber sets PartNumber field to given value.

### HasPartNumber

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) HasPartNumber() bool`

HasPartNumber returns a boolean if a field has been set.

### GetPartRevision

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetPartRevision() string`

GetPartRevision returns the PartRevision field if non-nil, zero value otherwise.

### GetPartRevisionOk

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetPartRevisionOk() (*string, bool)`

GetPartRevisionOk returns a tuple with the PartRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartRevision

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) SetPartRevision(v string)`

SetPartRevision sets PartRevision field to given value.

### HasPartRevision

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) HasPartRevision() bool`

HasPartRevision returns a boolean if a field has been set.

### GetPartNumberRevision

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetPartNumberRevision() string`

GetPartNumberRevision returns the PartNumberRevision field if non-nil, zero value otherwise.

### GetPartNumberRevisionOk

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetPartNumberRevisionOk() (*string, bool)`

GetPartNumberRevisionOk returns a tuple with the PartNumberRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumberRevision

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) SetPartNumberRevision(v string)`

SetPartNumberRevision sets PartNumberRevision field to given value.

### HasPartNumberRevision

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) HasPartNumberRevision() bool`

HasPartNumberRevision returns a boolean if a field has been set.

### GetPartOperationId

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetPartOperationId() string`

GetPartOperationId returns the PartOperationId field if non-nil, zero value otherwise.

### GetPartOperationIdOk

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetPartOperationIdOk() (*string, bool)`

GetPartOperationIdOk returns a tuple with the PartOperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartOperationId

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) SetPartOperationId(v string)`

SetPartOperationId sets PartOperationId field to given value.

### HasPartOperationId

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) HasPartOperationId() bool`

HasPartOperationId returns a boolean if a field has been set.

### GetOperationNumber

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetOperationNumber() int32`

GetOperationNumber returns the OperationNumber field if non-nil, zero value otherwise.

### GetOperationNumberOk

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetOperationNumberOk() (*int32, bool)`

GetOperationNumberOk returns a tuple with the OperationNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationNumber

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) SetOperationNumber(v int32)`

SetOperationNumber sets OperationNumber field to given value.

### HasOperationNumber

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) HasOperationNumber() bool`

HasOperationNumber returns a boolean if a field has been set.

### GetOperationCode

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetOperationCode() string`

GetOperationCode returns the OperationCode field if non-nil, zero value otherwise.

### GetOperationCodeOk

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetOperationCodeOk() (*string, bool)`

GetOperationCodeOk returns a tuple with the OperationCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationCode

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) SetOperationCode(v string)`

SetOperationCode sets OperationCode field to given value.

### HasOperationCode

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) HasOperationCode() bool`

HasOperationCode returns a boolean if a field has been set.

### GetLocation

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetLocation() string`

GetLocation returns the Location field if non-nil, zero value otherwise.

### GetLocationOk

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetLocationOk() (*string, bool)`

GetLocationOk returns a tuple with the Location field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocation

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) SetLocation(v string)`

SetLocation sets Location field to given value.

### HasLocation

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) HasLocation() bool`

HasLocation returns a boolean if a field has been set.

### GetJobNumber

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetJobNumber() string`

GetJobNumber returns the JobNumber field if non-nil, zero value otherwise.

### GetJobNumberOk

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetJobNumberOk() (*string, bool)`

GetJobNumberOk returns a tuple with the JobNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobNumber

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) SetJobNumber(v string)`

SetJobNumber sets JobNumber field to given value.

### HasJobNumber

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) HasJobNumber() bool`

HasJobNumber returns a boolean if a field has been set.

### GetJobId

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetJobId() string`

GetJobId returns the JobId field if non-nil, zero value otherwise.

### GetJobIdOk

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetJobIdOk() (*string, bool)`

GetJobIdOk returns a tuple with the JobId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobId

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) SetJobId(v string)`

SetJobId sets JobId field to given value.

### HasJobId

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) HasJobId() bool`

HasJobId returns a boolean if a field has been set.

### GetType

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) HasType() bool`

HasType returns a boolean if a field has been set.

### GetQuantity

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetActive

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetCreatedDate

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.

### GetModifiedDate

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetModifiedDate() time.Time`

GetModifiedDate returns the ModifiedDate field if non-nil, zero value otherwise.

### GetModifiedDateOk

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetModifiedDateOk() (*time.Time, bool)`

GetModifiedDateOk returns a tuple with the ModifiedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDate

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) SetModifiedDate(v time.Time)`

SetModifiedDate sets ModifiedDate field to given value.

### HasModifiedDate

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) HasModifiedDate() bool`

HasModifiedDate returns a boolean if a field has been set.

### GetQuantityUnit

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetQuantityUnit() string`

GetQuantityUnit returns the QuantityUnit field if non-nil, zero value otherwise.

### GetQuantityUnitOk

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetQuantityUnitOk() (*string, bool)`

GetQuantityUnitOk returns a tuple with the QuantityUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantityUnit

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) SetQuantityUnit(v string)`

SetQuantityUnit sets QuantityUnit field to given value.

### HasQuantityUnit

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) HasQuantityUnit() bool`

HasQuantityUnit returns a boolean if a field has been set.

### GetGrossWeight

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetGrossWeight() float64`

GetGrossWeight returns the GrossWeight field if non-nil, zero value otherwise.

### GetGrossWeightOk

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetGrossWeightOk() (*float64, bool)`

GetGrossWeightOk returns a tuple with the GrossWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrossWeight

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) SetGrossWeight(v float64)`

SetGrossWeight sets GrossWeight field to given value.

### HasGrossWeight

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) HasGrossWeight() bool`

HasGrossWeight returns a boolean if a field has been set.

### GetNetWeight

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetNetWeight() float64`

GetNetWeight returns the NetWeight field if non-nil, zero value otherwise.

### GetNetWeightOk

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetNetWeightOk() (*float64, bool)`

GetNetWeightOk returns a tuple with the NetWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetWeight

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) SetNetWeight(v float64)`

SetNetWeight sets NetWeight field to given value.

### HasNetWeight

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) HasNetWeight() bool`

HasNetWeight returns a boolean if a field has been set.

### GetTareWeight

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetTareWeight() float64`

GetTareWeight returns the TareWeight field if non-nil, zero value otherwise.

### GetTareWeightOk

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetTareWeightOk() (*float64, bool)`

GetTareWeightOk returns a tuple with the TareWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTareWeight

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) SetTareWeight(v float64)`

SetTareWeight sets TareWeight field to given value.

### HasTareWeight

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) HasTareWeight() bool`

HasTareWeight returns a boolean if a field has been set.

### GetTrackingNumber

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetTrackingNumber() string`

GetTrackingNumber returns the TrackingNumber field if non-nil, zero value otherwise.

### GetTrackingNumberOk

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetTrackingNumberOk() (*string, bool)`

GetTrackingNumberOk returns a tuple with the TrackingNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackingNumber

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) SetTrackingNumber(v string)`

SetTrackingNumber sets TrackingNumber field to given value.

### HasTrackingNumber

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) HasTrackingNumber() bool`

HasTrackingNumber returns a boolean if a field has been set.

### GetHeatNumber

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetHeatNumber() string`

GetHeatNumber returns the HeatNumber field if non-nil, zero value otherwise.

### GetHeatNumberOk

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetHeatNumberOk() (*string, bool)`

GetHeatNumberOk returns a tuple with the HeatNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeatNumber

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) SetHeatNumber(v string)`

SetHeatNumber sets HeatNumber field to given value.

### HasHeatNumber

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) HasHeatNumber() bool`

HasHeatNumber returns a boolean if a field has been set.

### GetLotNumber

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetLotNumber() string`

GetLotNumber returns the LotNumber field if non-nil, zero value otherwise.

### GetLotNumberOk

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetLotNumberOk() (*string, bool)`

GetLotNumberOk returns a tuple with the LotNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLotNumber

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) SetLotNumber(v string)`

SetLotNumber sets LotNumber field to given value.

### HasLotNumber

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) HasLotNumber() bool`

HasLotNumber returns a boolean if a field has been set.

### GetMasterUnitNo

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetMasterUnitNo() string`

GetMasterUnitNo returns the MasterUnitNo field if non-nil, zero value otherwise.

### GetMasterUnitNoOk

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetMasterUnitNoOk() (*string, bool)`

GetMasterUnitNoOk returns a tuple with the MasterUnitNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMasterUnitNo

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) SetMasterUnitNo(v string)`

SetMasterUnitNo sets MasterUnitNo field to given value.

### HasMasterUnitNo

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) HasMasterUnitNo() bool`

HasMasterUnitNo returns a boolean if a field has been set.

### GetMasterUnitId

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetMasterUnitId() string`

GetMasterUnitId returns the MasterUnitId field if non-nil, zero value otherwise.

### GetMasterUnitIdOk

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetMasterUnitIdOk() (*string, bool)`

GetMasterUnitIdOk returns a tuple with the MasterUnitId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMasterUnitId

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) SetMasterUnitId(v string)`

SetMasterUnitId sets MasterUnitId field to given value.

### HasMasterUnitId

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) HasMasterUnitId() bool`

HasMasterUnitId returns a boolean if a field has been set.

### GetLotId

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetLotId() string`

GetLotId returns the LotId field if non-nil, zero value otherwise.

### GetLotIdOk

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetLotIdOk() (*string, bool)`

GetLotIdOk returns a tuple with the LotId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLotId

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) SetLotId(v string)`

SetLotId sets LotId field to given value.

### HasLotId

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) HasLotId() bool`

HasLotId returns a boolean if a field has been set.

### GetHeatCode

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetHeatCode() string`

GetHeatCode returns the HeatCode field if non-nil, zero value otherwise.

### GetHeatCodeOk

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetHeatCodeOk() (*string, bool)`

GetHeatCodeOk returns a tuple with the HeatCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeatCode

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) SetHeatCode(v string)`

SetHeatCode sets HeatCode field to given value.

### HasHeatCode

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) HasHeatCode() bool`

HasHeatCode returns a boolean if a field has been set.

### GetHeatId

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetHeatId() string`

GetHeatId returns the HeatId field if non-nil, zero value otherwise.

### GetHeatIdOk

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetHeatIdOk() (*string, bool)`

GetHeatIdOk returns a tuple with the HeatId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeatId

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) SetHeatId(v string)`

SetHeatId sets HeatId field to given value.

### HasHeatId

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) HasHeatId() bool`

HasHeatId returns a boolean if a field has been set.

### GetShelfDateTime

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetShelfDateTime() time.Time`

GetShelfDateTime returns the ShelfDateTime field if non-nil, zero value otherwise.

### GetShelfDateTimeOk

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetShelfDateTimeOk() (*time.Time, bool)`

GetShelfDateTimeOk returns a tuple with the ShelfDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShelfDateTime

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) SetShelfDateTime(v time.Time)`

SetShelfDateTime sets ShelfDateTime field to given value.

### HasShelfDateTime

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) HasShelfDateTime() bool`

HasShelfDateTime returns a boolean if a field has been set.

### GetManufacturedDateTime

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetManufacturedDateTime() time.Time`

GetManufacturedDateTime returns the ManufacturedDateTime field if non-nil, zero value otherwise.

### GetManufacturedDateTimeOk

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetManufacturedDateTimeOk() (*time.Time, bool)`

GetManufacturedDateTimeOk returns a tuple with the ManufacturedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManufacturedDateTime

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) SetManufacturedDateTime(v time.Time)`

SetManufacturedDateTime sets ManufacturedDateTime field to given value.

### HasManufacturedDateTime

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) HasManufacturedDateTime() bool`

HasManufacturedDateTime returns a boolean if a field has been set.

### GetBestByDateTime

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetBestByDateTime() time.Time`

GetBestByDateTime returns the BestByDateTime field if non-nil, zero value otherwise.

### GetBestByDateTimeOk

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetBestByDateTimeOk() (*time.Time, bool)`

GetBestByDateTimeOk returns a tuple with the BestByDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBestByDateTime

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) SetBestByDateTime(v time.Time)`

SetBestByDateTime sets BestByDateTime field to given value.

### HasBestByDateTime

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) HasBestByDateTime() bool`

HasBestByDateTime returns a boolean if a field has been set.

### GetUseByDateTime

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetUseByDateTime() time.Time`

GetUseByDateTime returns the UseByDateTime field if non-nil, zero value otherwise.

### GetUseByDateTimeOk

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetUseByDateTimeOk() (*time.Time, bool)`

GetUseByDateTimeOk returns a tuple with the UseByDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUseByDateTime

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) SetUseByDateTime(v time.Time)`

SetUseByDateTime sets UseByDateTime field to given value.

### HasUseByDateTime

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) HasUseByDateTime() bool`

HasUseByDateTime returns a boolean if a field has been set.

### GetSellByDateTime

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetSellByDateTime() time.Time`

GetSellByDateTime returns the SellByDateTime field if non-nil, zero value otherwise.

### GetSellByDateTimeOk

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetSellByDateTimeOk() (*time.Time, bool)`

GetSellByDateTimeOk returns a tuple with the SellByDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSellByDateTime

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) SetSellByDateTime(v time.Time)`

SetSellByDateTime sets SellByDateTime field to given value.

### HasSellByDateTime

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) HasSellByDateTime() bool`

HasSellByDateTime returns a boolean if a field has been set.

### GetRfid

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetRfid() string`

GetRfid returns the Rfid field if non-nil, zero value otherwise.

### GetRfidOk

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) GetRfidOk() (*string, bool)`

GetRfidOk returns a tuple with the Rfid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRfid

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) SetRfid(v string)`

SetRfid sets Rfid field to given value.

### HasRfid

`func (o *InventoryTrackingApiGetContainerBySerialNumberResponse) HasRfid() bool`

HasRfid returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


