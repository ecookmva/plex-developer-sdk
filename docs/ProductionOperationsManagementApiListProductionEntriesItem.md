# ProductionOperationsManagementApiListProductionEntriesItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TransactionDate** | Pointer to **time.Time** | The date and time on which the production transaction was recorded in Plex. | [optional] 
**WorkcenterId** | Pointer to **string** | The ID of the workcenter where the production transaction was recorded. | [optional] 
**WorkcenterCode** | Pointer to **string** | A short name associated to the &amp;quot;workcenterID&amp;quot; and a unique code to reference the workcenter. This code shows up throughout the system, primarily on the Control Panel. 50 characters max. | [optional] 
**SerialNo** | Pointer to **string** | The serial number of the container. 25 characters max. | [optional] 
**LotNo** | Pointer to **string** | The unique lot number. 25 characters max. | [optional] 
**EmployeeId** | Pointer to **string** | The employee resource ID. | [optional] 
**EmployeeName** | Pointer to **string** | The employee name using the Plex User Display Name format. | [optional] 
**Quantity** | Pointer to **float64** | The quantity that was produced. | [optional] 
**JobId** | Pointer to **string** | The ID of the production job that production was recorded against. Note that a production job is not necessary to record production. Another scheduling method such as Kanban may have been used. | [optional] 
**JobCode** | Pointer to **string** | The job number, including prefix and suffix, associated to the &amp;quot;jobId&amp;quot; that production was recorded against. 20 characters max. | [optional] 
**JobNo** | Pointer to **string** | The unique job number. 20 characters max. | [optional] 
**PartId** | Pointer to **string** | The ID of the part that was produced. | [optional] 
**PartNumber** | Pointer to **string** | The part number associated to the &amp;quot;partId&amp;quot; that was produced. Acceptable part number characters include uppercase and lowercase letters (A-Z), numbers (0-9), and special characters such as dashes (-), underscores ( _ ), and spaces. Other characters may cause issues. | [optional] 
**Revision** | Pointer to **string** | The part revision of the &amp;quot;partId&amp;quot;. A revision represents a change or modification to a part or part drawing that is usually initiated through an engineering change request (ECR). | [optional] 
**PartNumberRevision** | Pointer to **string** | The part number and revision formatted with separator. If a part number has a revision, Plex will return the part number and the revision separated by the Part Rev Separator setting. A Part Rev Separator can be up to 5 characters long. Format: {partNumber}{part rev separator}{revision}. | [optional] 
**PartOperationId** | Pointer to **string** | The ID of the part operation. | [optional] 
**OperationNumber** | Pointer to **int32** | The operation number of the part operation. | [optional] 
**OperationCode** | Pointer to **string** | The operation code associated to the &amp;quot;partOperationId&amp;quot;. 30 characters max. | [optional] 
**MasterUnitNo** | Pointer to **string** | The master unit number of the master unit. 10 characters max. | [optional] 
**MasterUnitId** | Pointer to **string** | The master unit resource ID. | [optional] 
**LotId** | Pointer to **string** | The lot resource ID. | [optional] 
**HeatCode** | Pointer to **string** | The heat code of the heat. 50 characters max. | [optional] 
**HeatNo** | Pointer to **string** | The heat number of the heat. 30 characters max. | [optional] 
**HeatId** | Pointer to **string** | The material heat resource ID. | [optional] 
**Unit** | Pointer to **string** | The unit of measure for the operation. 20 characters max. | [optional] 
**TrackingNo** | Pointer to **string** | The tracking number of the container. 50 characters max. | [optional] 
**ShelfDateTime** | Pointer to **time.Time** | The shelf life date of the container. | [optional] 
**ManufacturedDateTime** | Pointer to **time.Time** | The date a lot was manufactured, either in Plex or by a supplier or subcontractor. | [optional] 
**BestByDateTime** | Pointer to **time.Time** | The best-by date which represents the last date for consumption of products in a lot by consumers. | [optional] 
**UseByDateTime** | Pointer to **time.Time** | The last date to use a lot for production. | [optional] 
**SellByDateTime** | Pointer to **time.Time** | The last date for the sale of a product in a lot to consumers. | [optional] 

## Methods

### NewProductionOperationsManagementApiListProductionEntriesItem

`func NewProductionOperationsManagementApiListProductionEntriesItem() *ProductionOperationsManagementApiListProductionEntriesItem`

NewProductionOperationsManagementApiListProductionEntriesItem instantiates a new ProductionOperationsManagementApiListProductionEntriesItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductionOperationsManagementApiListProductionEntriesItemWithDefaults

`func NewProductionOperationsManagementApiListProductionEntriesItemWithDefaults() *ProductionOperationsManagementApiListProductionEntriesItem`

NewProductionOperationsManagementApiListProductionEntriesItemWithDefaults instantiates a new ProductionOperationsManagementApiListProductionEntriesItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTransactionDate

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetTransactionDate() time.Time`

GetTransactionDate returns the TransactionDate field if non-nil, zero value otherwise.

### GetTransactionDateOk

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetTransactionDateOk() (*time.Time, bool)`

GetTransactionDateOk returns a tuple with the TransactionDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransactionDate

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) SetTransactionDate(v time.Time)`

SetTransactionDate sets TransactionDate field to given value.

### HasTransactionDate

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) HasTransactionDate() bool`

HasTransactionDate returns a boolean if a field has been set.

### GetWorkcenterId

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetWorkcenterId() string`

GetWorkcenterId returns the WorkcenterId field if non-nil, zero value otherwise.

### GetWorkcenterIdOk

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetWorkcenterIdOk() (*string, bool)`

GetWorkcenterIdOk returns a tuple with the WorkcenterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkcenterId

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) SetWorkcenterId(v string)`

SetWorkcenterId sets WorkcenterId field to given value.

### HasWorkcenterId

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) HasWorkcenterId() bool`

HasWorkcenterId returns a boolean if a field has been set.

### GetWorkcenterCode

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetWorkcenterCode() string`

GetWorkcenterCode returns the WorkcenterCode field if non-nil, zero value otherwise.

### GetWorkcenterCodeOk

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetWorkcenterCodeOk() (*string, bool)`

GetWorkcenterCodeOk returns a tuple with the WorkcenterCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkcenterCode

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) SetWorkcenterCode(v string)`

SetWorkcenterCode sets WorkcenterCode field to given value.

### HasWorkcenterCode

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) HasWorkcenterCode() bool`

HasWorkcenterCode returns a boolean if a field has been set.

### GetSerialNo

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetSerialNo() string`

GetSerialNo returns the SerialNo field if non-nil, zero value otherwise.

### GetSerialNoOk

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetSerialNoOk() (*string, bool)`

GetSerialNoOk returns a tuple with the SerialNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSerialNo

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) SetSerialNo(v string)`

SetSerialNo sets SerialNo field to given value.

### HasSerialNo

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) HasSerialNo() bool`

HasSerialNo returns a boolean if a field has been set.

### GetLotNo

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetLotNo() string`

GetLotNo returns the LotNo field if non-nil, zero value otherwise.

### GetLotNoOk

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetLotNoOk() (*string, bool)`

GetLotNoOk returns a tuple with the LotNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLotNo

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) SetLotNo(v string)`

SetLotNo sets LotNo field to given value.

### HasLotNo

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) HasLotNo() bool`

HasLotNo returns a boolean if a field has been set.

### GetEmployeeId

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetEmployeeId() string`

GetEmployeeId returns the EmployeeId field if non-nil, zero value otherwise.

### GetEmployeeIdOk

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetEmployeeIdOk() (*string, bool)`

GetEmployeeIdOk returns a tuple with the EmployeeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmployeeId

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) SetEmployeeId(v string)`

SetEmployeeId sets EmployeeId field to given value.

### HasEmployeeId

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) HasEmployeeId() bool`

HasEmployeeId returns a boolean if a field has been set.

### GetEmployeeName

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetEmployeeName() string`

GetEmployeeName returns the EmployeeName field if non-nil, zero value otherwise.

### GetEmployeeNameOk

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetEmployeeNameOk() (*string, bool)`

GetEmployeeNameOk returns a tuple with the EmployeeName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmployeeName

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) SetEmployeeName(v string)`

SetEmployeeName sets EmployeeName field to given value.

### HasEmployeeName

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) HasEmployeeName() bool`

HasEmployeeName returns a boolean if a field has been set.

### GetQuantity

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetJobId

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetJobId() string`

GetJobId returns the JobId field if non-nil, zero value otherwise.

### GetJobIdOk

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetJobIdOk() (*string, bool)`

GetJobIdOk returns a tuple with the JobId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobId

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) SetJobId(v string)`

SetJobId sets JobId field to given value.

### HasJobId

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) HasJobId() bool`

HasJobId returns a boolean if a field has been set.

### GetJobCode

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetJobCode() string`

GetJobCode returns the JobCode field if non-nil, zero value otherwise.

### GetJobCodeOk

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetJobCodeOk() (*string, bool)`

GetJobCodeOk returns a tuple with the JobCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobCode

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) SetJobCode(v string)`

SetJobCode sets JobCode field to given value.

### HasJobCode

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) HasJobCode() bool`

HasJobCode returns a boolean if a field has been set.

### GetJobNo

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetJobNo() string`

GetJobNo returns the JobNo field if non-nil, zero value otherwise.

### GetJobNoOk

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetJobNoOk() (*string, bool)`

GetJobNoOk returns a tuple with the JobNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobNo

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) SetJobNo(v string)`

SetJobNo sets JobNo field to given value.

### HasJobNo

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) HasJobNo() bool`

HasJobNo returns a boolean if a field has been set.

### GetPartId

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetPartNumber

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetPartNumber() string`

GetPartNumber returns the PartNumber field if non-nil, zero value otherwise.

### GetPartNumberOk

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetPartNumberOk() (*string, bool)`

GetPartNumberOk returns a tuple with the PartNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumber

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) SetPartNumber(v string)`

SetPartNumber sets PartNumber field to given value.

### HasPartNumber

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) HasPartNumber() bool`

HasPartNumber returns a boolean if a field has been set.

### GetRevision

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetRevision() string`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetRevisionOk() (*string, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) SetRevision(v string)`

SetRevision sets Revision field to given value.

### HasRevision

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) HasRevision() bool`

HasRevision returns a boolean if a field has been set.

### GetPartNumberRevision

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetPartNumberRevision() string`

GetPartNumberRevision returns the PartNumberRevision field if non-nil, zero value otherwise.

### GetPartNumberRevisionOk

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetPartNumberRevisionOk() (*string, bool)`

GetPartNumberRevisionOk returns a tuple with the PartNumberRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumberRevision

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) SetPartNumberRevision(v string)`

SetPartNumberRevision sets PartNumberRevision field to given value.

### HasPartNumberRevision

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) HasPartNumberRevision() bool`

HasPartNumberRevision returns a boolean if a field has been set.

### GetPartOperationId

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetPartOperationId() string`

GetPartOperationId returns the PartOperationId field if non-nil, zero value otherwise.

### GetPartOperationIdOk

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetPartOperationIdOk() (*string, bool)`

GetPartOperationIdOk returns a tuple with the PartOperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartOperationId

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) SetPartOperationId(v string)`

SetPartOperationId sets PartOperationId field to given value.

### HasPartOperationId

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) HasPartOperationId() bool`

HasPartOperationId returns a boolean if a field has been set.

### GetOperationNumber

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetOperationNumber() int32`

GetOperationNumber returns the OperationNumber field if non-nil, zero value otherwise.

### GetOperationNumberOk

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetOperationNumberOk() (*int32, bool)`

GetOperationNumberOk returns a tuple with the OperationNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationNumber

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) SetOperationNumber(v int32)`

SetOperationNumber sets OperationNumber field to given value.

### HasOperationNumber

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) HasOperationNumber() bool`

HasOperationNumber returns a boolean if a field has been set.

### GetOperationCode

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetOperationCode() string`

GetOperationCode returns the OperationCode field if non-nil, zero value otherwise.

### GetOperationCodeOk

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetOperationCodeOk() (*string, bool)`

GetOperationCodeOk returns a tuple with the OperationCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationCode

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) SetOperationCode(v string)`

SetOperationCode sets OperationCode field to given value.

### HasOperationCode

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) HasOperationCode() bool`

HasOperationCode returns a boolean if a field has been set.

### GetMasterUnitNo

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetMasterUnitNo() string`

GetMasterUnitNo returns the MasterUnitNo field if non-nil, zero value otherwise.

### GetMasterUnitNoOk

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetMasterUnitNoOk() (*string, bool)`

GetMasterUnitNoOk returns a tuple with the MasterUnitNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMasterUnitNo

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) SetMasterUnitNo(v string)`

SetMasterUnitNo sets MasterUnitNo field to given value.

### HasMasterUnitNo

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) HasMasterUnitNo() bool`

HasMasterUnitNo returns a boolean if a field has been set.

### GetMasterUnitId

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetMasterUnitId() string`

GetMasterUnitId returns the MasterUnitId field if non-nil, zero value otherwise.

### GetMasterUnitIdOk

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetMasterUnitIdOk() (*string, bool)`

GetMasterUnitIdOk returns a tuple with the MasterUnitId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMasterUnitId

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) SetMasterUnitId(v string)`

SetMasterUnitId sets MasterUnitId field to given value.

### HasMasterUnitId

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) HasMasterUnitId() bool`

HasMasterUnitId returns a boolean if a field has been set.

### GetLotId

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetLotId() string`

GetLotId returns the LotId field if non-nil, zero value otherwise.

### GetLotIdOk

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetLotIdOk() (*string, bool)`

GetLotIdOk returns a tuple with the LotId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLotId

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) SetLotId(v string)`

SetLotId sets LotId field to given value.

### HasLotId

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) HasLotId() bool`

HasLotId returns a boolean if a field has been set.

### GetHeatCode

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetHeatCode() string`

GetHeatCode returns the HeatCode field if non-nil, zero value otherwise.

### GetHeatCodeOk

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetHeatCodeOk() (*string, bool)`

GetHeatCodeOk returns a tuple with the HeatCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeatCode

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) SetHeatCode(v string)`

SetHeatCode sets HeatCode field to given value.

### HasHeatCode

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) HasHeatCode() bool`

HasHeatCode returns a boolean if a field has been set.

### GetHeatNo

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetHeatNo() string`

GetHeatNo returns the HeatNo field if non-nil, zero value otherwise.

### GetHeatNoOk

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetHeatNoOk() (*string, bool)`

GetHeatNoOk returns a tuple with the HeatNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeatNo

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) SetHeatNo(v string)`

SetHeatNo sets HeatNo field to given value.

### HasHeatNo

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) HasHeatNo() bool`

HasHeatNo returns a boolean if a field has been set.

### GetHeatId

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetHeatId() string`

GetHeatId returns the HeatId field if non-nil, zero value otherwise.

### GetHeatIdOk

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetHeatIdOk() (*string, bool)`

GetHeatIdOk returns a tuple with the HeatId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeatId

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) SetHeatId(v string)`

SetHeatId sets HeatId field to given value.

### HasHeatId

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) HasHeatId() bool`

HasHeatId returns a boolean if a field has been set.

### GetUnit

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetUnit() string`

GetUnit returns the Unit field if non-nil, zero value otherwise.

### GetUnitOk

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetUnitOk() (*string, bool)`

GetUnitOk returns a tuple with the Unit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnit

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) SetUnit(v string)`

SetUnit sets Unit field to given value.

### HasUnit

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) HasUnit() bool`

HasUnit returns a boolean if a field has been set.

### GetTrackingNo

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetTrackingNo() string`

GetTrackingNo returns the TrackingNo field if non-nil, zero value otherwise.

### GetTrackingNoOk

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetTrackingNoOk() (*string, bool)`

GetTrackingNoOk returns a tuple with the TrackingNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackingNo

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) SetTrackingNo(v string)`

SetTrackingNo sets TrackingNo field to given value.

### HasTrackingNo

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) HasTrackingNo() bool`

HasTrackingNo returns a boolean if a field has been set.

### GetShelfDateTime

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetShelfDateTime() time.Time`

GetShelfDateTime returns the ShelfDateTime field if non-nil, zero value otherwise.

### GetShelfDateTimeOk

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetShelfDateTimeOk() (*time.Time, bool)`

GetShelfDateTimeOk returns a tuple with the ShelfDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShelfDateTime

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) SetShelfDateTime(v time.Time)`

SetShelfDateTime sets ShelfDateTime field to given value.

### HasShelfDateTime

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) HasShelfDateTime() bool`

HasShelfDateTime returns a boolean if a field has been set.

### GetManufacturedDateTime

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetManufacturedDateTime() time.Time`

GetManufacturedDateTime returns the ManufacturedDateTime field if non-nil, zero value otherwise.

### GetManufacturedDateTimeOk

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetManufacturedDateTimeOk() (*time.Time, bool)`

GetManufacturedDateTimeOk returns a tuple with the ManufacturedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManufacturedDateTime

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) SetManufacturedDateTime(v time.Time)`

SetManufacturedDateTime sets ManufacturedDateTime field to given value.

### HasManufacturedDateTime

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) HasManufacturedDateTime() bool`

HasManufacturedDateTime returns a boolean if a field has been set.

### GetBestByDateTime

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetBestByDateTime() time.Time`

GetBestByDateTime returns the BestByDateTime field if non-nil, zero value otherwise.

### GetBestByDateTimeOk

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetBestByDateTimeOk() (*time.Time, bool)`

GetBestByDateTimeOk returns a tuple with the BestByDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBestByDateTime

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) SetBestByDateTime(v time.Time)`

SetBestByDateTime sets BestByDateTime field to given value.

### HasBestByDateTime

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) HasBestByDateTime() bool`

HasBestByDateTime returns a boolean if a field has been set.

### GetUseByDateTime

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetUseByDateTime() time.Time`

GetUseByDateTime returns the UseByDateTime field if non-nil, zero value otherwise.

### GetUseByDateTimeOk

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetUseByDateTimeOk() (*time.Time, bool)`

GetUseByDateTimeOk returns a tuple with the UseByDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUseByDateTime

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) SetUseByDateTime(v time.Time)`

SetUseByDateTime sets UseByDateTime field to given value.

### HasUseByDateTime

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) HasUseByDateTime() bool`

HasUseByDateTime returns a boolean if a field has been set.

### GetSellByDateTime

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetSellByDateTime() time.Time`

GetSellByDateTime returns the SellByDateTime field if non-nil, zero value otherwise.

### GetSellByDateTimeOk

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) GetSellByDateTimeOk() (*time.Time, bool)`

GetSellByDateTimeOk returns a tuple with the SellByDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSellByDateTime

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) SetSellByDateTime(v time.Time)`

SetSellByDateTime sets SellByDateTime field to given value.

### HasSellByDateTime

`func (o *ProductionOperationsManagementApiListProductionEntriesItem) HasSellByDateTime() bool`

HasSellByDateTime returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


