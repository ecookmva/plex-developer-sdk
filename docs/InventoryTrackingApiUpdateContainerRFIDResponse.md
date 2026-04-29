# InventoryTrackingApiUpdateContainerRFIDResponse

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

### NewInventoryTrackingApiUpdateContainerRFIDResponse

`func NewInventoryTrackingApiUpdateContainerRFIDResponse() *InventoryTrackingApiUpdateContainerRFIDResponse`

NewInventoryTrackingApiUpdateContainerRFIDResponse instantiates a new InventoryTrackingApiUpdateContainerRFIDResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInventoryTrackingApiUpdateContainerRFIDResponseWithDefaults

`func NewInventoryTrackingApiUpdateContainerRFIDResponseWithDefaults() *InventoryTrackingApiUpdateContainerRFIDResponse`

NewInventoryTrackingApiUpdateContainerRFIDResponseWithDefaults instantiates a new InventoryTrackingApiUpdateContainerRFIDResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSerialNumber

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetSerialNumber() string`

GetSerialNumber returns the SerialNumber field if non-nil, zero value otherwise.

### GetSerialNumberOk

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetSerialNumberOk() (*string, bool)`

GetSerialNumberOk returns a tuple with the SerialNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSerialNumber

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) SetSerialNumber(v string)`

SetSerialNumber sets SerialNumber field to given value.

### HasSerialNumber

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) HasSerialNumber() bool`

HasSerialNumber returns a boolean if a field has been set.

### GetStatus

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetPartId

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetPartNumber

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetPartNumber() string`

GetPartNumber returns the PartNumber field if non-nil, zero value otherwise.

### GetPartNumberOk

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetPartNumberOk() (*string, bool)`

GetPartNumberOk returns a tuple with the PartNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumber

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) SetPartNumber(v string)`

SetPartNumber sets PartNumber field to given value.

### HasPartNumber

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) HasPartNumber() bool`

HasPartNumber returns a boolean if a field has been set.

### GetPartRevision

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetPartRevision() string`

GetPartRevision returns the PartRevision field if non-nil, zero value otherwise.

### GetPartRevisionOk

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetPartRevisionOk() (*string, bool)`

GetPartRevisionOk returns a tuple with the PartRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartRevision

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) SetPartRevision(v string)`

SetPartRevision sets PartRevision field to given value.

### HasPartRevision

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) HasPartRevision() bool`

HasPartRevision returns a boolean if a field has been set.

### GetPartNumberRevision

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetPartNumberRevision() string`

GetPartNumberRevision returns the PartNumberRevision field if non-nil, zero value otherwise.

### GetPartNumberRevisionOk

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetPartNumberRevisionOk() (*string, bool)`

GetPartNumberRevisionOk returns a tuple with the PartNumberRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumberRevision

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) SetPartNumberRevision(v string)`

SetPartNumberRevision sets PartNumberRevision field to given value.

### HasPartNumberRevision

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) HasPartNumberRevision() bool`

HasPartNumberRevision returns a boolean if a field has been set.

### GetPartOperationId

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetPartOperationId() string`

GetPartOperationId returns the PartOperationId field if non-nil, zero value otherwise.

### GetPartOperationIdOk

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetPartOperationIdOk() (*string, bool)`

GetPartOperationIdOk returns a tuple with the PartOperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartOperationId

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) SetPartOperationId(v string)`

SetPartOperationId sets PartOperationId field to given value.

### HasPartOperationId

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) HasPartOperationId() bool`

HasPartOperationId returns a boolean if a field has been set.

### GetOperationNumber

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetOperationNumber() int32`

GetOperationNumber returns the OperationNumber field if non-nil, zero value otherwise.

### GetOperationNumberOk

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetOperationNumberOk() (*int32, bool)`

GetOperationNumberOk returns a tuple with the OperationNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationNumber

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) SetOperationNumber(v int32)`

SetOperationNumber sets OperationNumber field to given value.

### HasOperationNumber

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) HasOperationNumber() bool`

HasOperationNumber returns a boolean if a field has been set.

### GetOperationCode

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetOperationCode() string`

GetOperationCode returns the OperationCode field if non-nil, zero value otherwise.

### GetOperationCodeOk

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetOperationCodeOk() (*string, bool)`

GetOperationCodeOk returns a tuple with the OperationCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationCode

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) SetOperationCode(v string)`

SetOperationCode sets OperationCode field to given value.

### HasOperationCode

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) HasOperationCode() bool`

HasOperationCode returns a boolean if a field has been set.

### GetLocation

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetLocation() string`

GetLocation returns the Location field if non-nil, zero value otherwise.

### GetLocationOk

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetLocationOk() (*string, bool)`

GetLocationOk returns a tuple with the Location field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocation

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) SetLocation(v string)`

SetLocation sets Location field to given value.

### HasLocation

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) HasLocation() bool`

HasLocation returns a boolean if a field has been set.

### GetJobNumber

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetJobNumber() string`

GetJobNumber returns the JobNumber field if non-nil, zero value otherwise.

### GetJobNumberOk

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetJobNumberOk() (*string, bool)`

GetJobNumberOk returns a tuple with the JobNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobNumber

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) SetJobNumber(v string)`

SetJobNumber sets JobNumber field to given value.

### HasJobNumber

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) HasJobNumber() bool`

HasJobNumber returns a boolean if a field has been set.

### GetJobId

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetJobId() string`

GetJobId returns the JobId field if non-nil, zero value otherwise.

### GetJobIdOk

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetJobIdOk() (*string, bool)`

GetJobIdOk returns a tuple with the JobId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobId

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) SetJobId(v string)`

SetJobId sets JobId field to given value.

### HasJobId

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) HasJobId() bool`

HasJobId returns a boolean if a field has been set.

### GetType

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) HasType() bool`

HasType returns a boolean if a field has been set.

### GetQuantity

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetActive

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetCreatedDate

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.

### GetModifiedDate

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetModifiedDate() time.Time`

GetModifiedDate returns the ModifiedDate field if non-nil, zero value otherwise.

### GetModifiedDateOk

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetModifiedDateOk() (*time.Time, bool)`

GetModifiedDateOk returns a tuple with the ModifiedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDate

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) SetModifiedDate(v time.Time)`

SetModifiedDate sets ModifiedDate field to given value.

### HasModifiedDate

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) HasModifiedDate() bool`

HasModifiedDate returns a boolean if a field has been set.

### GetQuantityUnit

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetQuantityUnit() string`

GetQuantityUnit returns the QuantityUnit field if non-nil, zero value otherwise.

### GetQuantityUnitOk

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetQuantityUnitOk() (*string, bool)`

GetQuantityUnitOk returns a tuple with the QuantityUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantityUnit

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) SetQuantityUnit(v string)`

SetQuantityUnit sets QuantityUnit field to given value.

### HasQuantityUnit

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) HasQuantityUnit() bool`

HasQuantityUnit returns a boolean if a field has been set.

### GetGrossWeight

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetGrossWeight() float64`

GetGrossWeight returns the GrossWeight field if non-nil, zero value otherwise.

### GetGrossWeightOk

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetGrossWeightOk() (*float64, bool)`

GetGrossWeightOk returns a tuple with the GrossWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrossWeight

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) SetGrossWeight(v float64)`

SetGrossWeight sets GrossWeight field to given value.

### HasGrossWeight

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) HasGrossWeight() bool`

HasGrossWeight returns a boolean if a field has been set.

### GetNetWeight

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetNetWeight() float64`

GetNetWeight returns the NetWeight field if non-nil, zero value otherwise.

### GetNetWeightOk

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetNetWeightOk() (*float64, bool)`

GetNetWeightOk returns a tuple with the NetWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetWeight

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) SetNetWeight(v float64)`

SetNetWeight sets NetWeight field to given value.

### HasNetWeight

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) HasNetWeight() bool`

HasNetWeight returns a boolean if a field has been set.

### GetTareWeight

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetTareWeight() float64`

GetTareWeight returns the TareWeight field if non-nil, zero value otherwise.

### GetTareWeightOk

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetTareWeightOk() (*float64, bool)`

GetTareWeightOk returns a tuple with the TareWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTareWeight

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) SetTareWeight(v float64)`

SetTareWeight sets TareWeight field to given value.

### HasTareWeight

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) HasTareWeight() bool`

HasTareWeight returns a boolean if a field has been set.

### GetTrackingNumber

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetTrackingNumber() string`

GetTrackingNumber returns the TrackingNumber field if non-nil, zero value otherwise.

### GetTrackingNumberOk

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetTrackingNumberOk() (*string, bool)`

GetTrackingNumberOk returns a tuple with the TrackingNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackingNumber

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) SetTrackingNumber(v string)`

SetTrackingNumber sets TrackingNumber field to given value.

### HasTrackingNumber

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) HasTrackingNumber() bool`

HasTrackingNumber returns a boolean if a field has been set.

### GetHeatNumber

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetHeatNumber() string`

GetHeatNumber returns the HeatNumber field if non-nil, zero value otherwise.

### GetHeatNumberOk

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetHeatNumberOk() (*string, bool)`

GetHeatNumberOk returns a tuple with the HeatNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeatNumber

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) SetHeatNumber(v string)`

SetHeatNumber sets HeatNumber field to given value.

### HasHeatNumber

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) HasHeatNumber() bool`

HasHeatNumber returns a boolean if a field has been set.

### GetLotNumber

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetLotNumber() string`

GetLotNumber returns the LotNumber field if non-nil, zero value otherwise.

### GetLotNumberOk

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetLotNumberOk() (*string, bool)`

GetLotNumberOk returns a tuple with the LotNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLotNumber

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) SetLotNumber(v string)`

SetLotNumber sets LotNumber field to given value.

### HasLotNumber

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) HasLotNumber() bool`

HasLotNumber returns a boolean if a field has been set.

### GetMasterUnitNo

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetMasterUnitNo() string`

GetMasterUnitNo returns the MasterUnitNo field if non-nil, zero value otherwise.

### GetMasterUnitNoOk

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetMasterUnitNoOk() (*string, bool)`

GetMasterUnitNoOk returns a tuple with the MasterUnitNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMasterUnitNo

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) SetMasterUnitNo(v string)`

SetMasterUnitNo sets MasterUnitNo field to given value.

### HasMasterUnitNo

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) HasMasterUnitNo() bool`

HasMasterUnitNo returns a boolean if a field has been set.

### GetMasterUnitId

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetMasterUnitId() string`

GetMasterUnitId returns the MasterUnitId field if non-nil, zero value otherwise.

### GetMasterUnitIdOk

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetMasterUnitIdOk() (*string, bool)`

GetMasterUnitIdOk returns a tuple with the MasterUnitId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMasterUnitId

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) SetMasterUnitId(v string)`

SetMasterUnitId sets MasterUnitId field to given value.

### HasMasterUnitId

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) HasMasterUnitId() bool`

HasMasterUnitId returns a boolean if a field has been set.

### GetLotId

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetLotId() string`

GetLotId returns the LotId field if non-nil, zero value otherwise.

### GetLotIdOk

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetLotIdOk() (*string, bool)`

GetLotIdOk returns a tuple with the LotId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLotId

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) SetLotId(v string)`

SetLotId sets LotId field to given value.

### HasLotId

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) HasLotId() bool`

HasLotId returns a boolean if a field has been set.

### GetHeatCode

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetHeatCode() string`

GetHeatCode returns the HeatCode field if non-nil, zero value otherwise.

### GetHeatCodeOk

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetHeatCodeOk() (*string, bool)`

GetHeatCodeOk returns a tuple with the HeatCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeatCode

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) SetHeatCode(v string)`

SetHeatCode sets HeatCode field to given value.

### HasHeatCode

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) HasHeatCode() bool`

HasHeatCode returns a boolean if a field has been set.

### GetHeatId

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetHeatId() string`

GetHeatId returns the HeatId field if non-nil, zero value otherwise.

### GetHeatIdOk

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetHeatIdOk() (*string, bool)`

GetHeatIdOk returns a tuple with the HeatId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeatId

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) SetHeatId(v string)`

SetHeatId sets HeatId field to given value.

### HasHeatId

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) HasHeatId() bool`

HasHeatId returns a boolean if a field has been set.

### GetShelfDateTime

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetShelfDateTime() time.Time`

GetShelfDateTime returns the ShelfDateTime field if non-nil, zero value otherwise.

### GetShelfDateTimeOk

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetShelfDateTimeOk() (*time.Time, bool)`

GetShelfDateTimeOk returns a tuple with the ShelfDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShelfDateTime

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) SetShelfDateTime(v time.Time)`

SetShelfDateTime sets ShelfDateTime field to given value.

### HasShelfDateTime

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) HasShelfDateTime() bool`

HasShelfDateTime returns a boolean if a field has been set.

### GetManufacturedDateTime

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetManufacturedDateTime() time.Time`

GetManufacturedDateTime returns the ManufacturedDateTime field if non-nil, zero value otherwise.

### GetManufacturedDateTimeOk

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetManufacturedDateTimeOk() (*time.Time, bool)`

GetManufacturedDateTimeOk returns a tuple with the ManufacturedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManufacturedDateTime

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) SetManufacturedDateTime(v time.Time)`

SetManufacturedDateTime sets ManufacturedDateTime field to given value.

### HasManufacturedDateTime

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) HasManufacturedDateTime() bool`

HasManufacturedDateTime returns a boolean if a field has been set.

### GetBestByDateTime

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetBestByDateTime() time.Time`

GetBestByDateTime returns the BestByDateTime field if non-nil, zero value otherwise.

### GetBestByDateTimeOk

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetBestByDateTimeOk() (*time.Time, bool)`

GetBestByDateTimeOk returns a tuple with the BestByDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBestByDateTime

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) SetBestByDateTime(v time.Time)`

SetBestByDateTime sets BestByDateTime field to given value.

### HasBestByDateTime

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) HasBestByDateTime() bool`

HasBestByDateTime returns a boolean if a field has been set.

### GetUseByDateTime

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetUseByDateTime() time.Time`

GetUseByDateTime returns the UseByDateTime field if non-nil, zero value otherwise.

### GetUseByDateTimeOk

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetUseByDateTimeOk() (*time.Time, bool)`

GetUseByDateTimeOk returns a tuple with the UseByDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUseByDateTime

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) SetUseByDateTime(v time.Time)`

SetUseByDateTime sets UseByDateTime field to given value.

### HasUseByDateTime

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) HasUseByDateTime() bool`

HasUseByDateTime returns a boolean if a field has been set.

### GetSellByDateTime

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetSellByDateTime() time.Time`

GetSellByDateTime returns the SellByDateTime field if non-nil, zero value otherwise.

### GetSellByDateTimeOk

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetSellByDateTimeOk() (*time.Time, bool)`

GetSellByDateTimeOk returns a tuple with the SellByDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSellByDateTime

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) SetSellByDateTime(v time.Time)`

SetSellByDateTime sets SellByDateTime field to given value.

### HasSellByDateTime

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) HasSellByDateTime() bool`

HasSellByDateTime returns a boolean if a field has been set.

### GetRfid

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetRfid() string`

GetRfid returns the Rfid field if non-nil, zero value otherwise.

### GetRfidOk

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) GetRfidOk() (*string, bool)`

GetRfidOk returns a tuple with the Rfid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRfid

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) SetRfid(v string)`

SetRfid sets Rfid field to given value.

### HasRfid

`func (o *InventoryTrackingApiUpdateContainerRFIDResponse) HasRfid() bool`

HasRfid returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


