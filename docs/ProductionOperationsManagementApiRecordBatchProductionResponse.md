# ProductionOperationsManagementApiRecordBatchProductionResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BatchId** | Pointer to **string** | A unique identifier of a batch. | [optional] 
**JobId** | Pointer to **string** | A unique identifier of the production job. | [optional] 
**JobNumber** | Pointer to **string** | The job number, including prefix and suffix, associated with the job ID. | [optional] 
**JobOperationId** | Pointer to **string** | A unique identifier for the job operation. | [optional] 
**JobOperationStatus** | Pointer to **string** | The job operation status. | [optional] 
**JobStatus** | Pointer to **string** | The job status. | [optional] 
**MasterUnitID** | Pointer to **string** | A unique identifier of a master unit. | [optional] 
**OperationCode** | Pointer to **string** | The operation code of the part operation. 30 characters max. | [optional] 
**OperationNumber** | Pointer to **float64** | The operation number of the part operation. | [optional] 
**PartId** | Pointer to **string** | A unique identifier of the part. | [optional] 
**PartNumber** | Pointer to **string** | The part number associated with the part ID. | [optional] 
**PartNumberRevision** | Pointer to **string** | A combination of the part number and revision associated with the part ID, separated with the value from the Part Rev Separator setting. | [optional] 
**PartRevision** | Pointer to **string** | The part revision associated with the part ID. | [optional] 
**PrintMasterUnitID** | Pointer to **string** | A unique identifier of a master unit to be used for triggering a master unit label print job. | [optional] 
**Quantity** | Pointer to **float64** | The quantity produced. | [optional] 
**SerialNo** | Pointer to **string** | 25 characters max. The Serial No of the produced container. | [optional] 
**TrackingNo** | Pointer to **string** | The tracking no. | [optional] 
**WorkcenterCode** | Pointer to **string** | A short name associated with the workcenter ID, and a unique code to reference the workcenter. This code displays throughout the system, primarily on the Control Panel. 50 characters max. | [optional] 
**WorkcenterId** | Pointer to **string** | A unique identifier of the workcenter. | [optional] 
**LocationId** | Pointer to **string** | A unique identifier of the container&#39;s location. | [optional] 
**Location** | Pointer to **string** | The containers location. | [optional] 

## Methods

### NewProductionOperationsManagementApiRecordBatchProductionResponse

`func NewProductionOperationsManagementApiRecordBatchProductionResponse() *ProductionOperationsManagementApiRecordBatchProductionResponse`

NewProductionOperationsManagementApiRecordBatchProductionResponse instantiates a new ProductionOperationsManagementApiRecordBatchProductionResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductionOperationsManagementApiRecordBatchProductionResponseWithDefaults

`func NewProductionOperationsManagementApiRecordBatchProductionResponseWithDefaults() *ProductionOperationsManagementApiRecordBatchProductionResponse`

NewProductionOperationsManagementApiRecordBatchProductionResponseWithDefaults instantiates a new ProductionOperationsManagementApiRecordBatchProductionResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBatchId

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) GetBatchId() string`

GetBatchId returns the BatchId field if non-nil, zero value otherwise.

### GetBatchIdOk

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) GetBatchIdOk() (*string, bool)`

GetBatchIdOk returns a tuple with the BatchId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBatchId

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) SetBatchId(v string)`

SetBatchId sets BatchId field to given value.

### HasBatchId

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) HasBatchId() bool`

HasBatchId returns a boolean if a field has been set.

### GetJobId

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) GetJobId() string`

GetJobId returns the JobId field if non-nil, zero value otherwise.

### GetJobIdOk

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) GetJobIdOk() (*string, bool)`

GetJobIdOk returns a tuple with the JobId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobId

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) SetJobId(v string)`

SetJobId sets JobId field to given value.

### HasJobId

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) HasJobId() bool`

HasJobId returns a boolean if a field has been set.

### GetJobNumber

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) GetJobNumber() string`

GetJobNumber returns the JobNumber field if non-nil, zero value otherwise.

### GetJobNumberOk

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) GetJobNumberOk() (*string, bool)`

GetJobNumberOk returns a tuple with the JobNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobNumber

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) SetJobNumber(v string)`

SetJobNumber sets JobNumber field to given value.

### HasJobNumber

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) HasJobNumber() bool`

HasJobNumber returns a boolean if a field has been set.

### GetJobOperationId

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) GetJobOperationId() string`

GetJobOperationId returns the JobOperationId field if non-nil, zero value otherwise.

### GetJobOperationIdOk

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) GetJobOperationIdOk() (*string, bool)`

GetJobOperationIdOk returns a tuple with the JobOperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobOperationId

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) SetJobOperationId(v string)`

SetJobOperationId sets JobOperationId field to given value.

### HasJobOperationId

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) HasJobOperationId() bool`

HasJobOperationId returns a boolean if a field has been set.

### GetJobOperationStatus

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) GetJobOperationStatus() string`

GetJobOperationStatus returns the JobOperationStatus field if non-nil, zero value otherwise.

### GetJobOperationStatusOk

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) GetJobOperationStatusOk() (*string, bool)`

GetJobOperationStatusOk returns a tuple with the JobOperationStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobOperationStatus

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) SetJobOperationStatus(v string)`

SetJobOperationStatus sets JobOperationStatus field to given value.

### HasJobOperationStatus

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) HasJobOperationStatus() bool`

HasJobOperationStatus returns a boolean if a field has been set.

### GetJobStatus

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) GetJobStatus() string`

GetJobStatus returns the JobStatus field if non-nil, zero value otherwise.

### GetJobStatusOk

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) GetJobStatusOk() (*string, bool)`

GetJobStatusOk returns a tuple with the JobStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobStatus

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) SetJobStatus(v string)`

SetJobStatus sets JobStatus field to given value.

### HasJobStatus

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) HasJobStatus() bool`

HasJobStatus returns a boolean if a field has been set.

### GetMasterUnitID

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) GetMasterUnitID() string`

GetMasterUnitID returns the MasterUnitID field if non-nil, zero value otherwise.

### GetMasterUnitIDOk

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) GetMasterUnitIDOk() (*string, bool)`

GetMasterUnitIDOk returns a tuple with the MasterUnitID field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMasterUnitID

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) SetMasterUnitID(v string)`

SetMasterUnitID sets MasterUnitID field to given value.

### HasMasterUnitID

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) HasMasterUnitID() bool`

HasMasterUnitID returns a boolean if a field has been set.

### GetOperationCode

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) GetOperationCode() string`

GetOperationCode returns the OperationCode field if non-nil, zero value otherwise.

### GetOperationCodeOk

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) GetOperationCodeOk() (*string, bool)`

GetOperationCodeOk returns a tuple with the OperationCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationCode

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) SetOperationCode(v string)`

SetOperationCode sets OperationCode field to given value.

### HasOperationCode

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) HasOperationCode() bool`

HasOperationCode returns a boolean if a field has been set.

### GetOperationNumber

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) GetOperationNumber() float64`

GetOperationNumber returns the OperationNumber field if non-nil, zero value otherwise.

### GetOperationNumberOk

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) GetOperationNumberOk() (*float64, bool)`

GetOperationNumberOk returns a tuple with the OperationNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationNumber

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) SetOperationNumber(v float64)`

SetOperationNumber sets OperationNumber field to given value.

### HasOperationNumber

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) HasOperationNumber() bool`

HasOperationNumber returns a boolean if a field has been set.

### GetPartId

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetPartNumber

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) GetPartNumber() string`

GetPartNumber returns the PartNumber field if non-nil, zero value otherwise.

### GetPartNumberOk

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) GetPartNumberOk() (*string, bool)`

GetPartNumberOk returns a tuple with the PartNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumber

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) SetPartNumber(v string)`

SetPartNumber sets PartNumber field to given value.

### HasPartNumber

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) HasPartNumber() bool`

HasPartNumber returns a boolean if a field has been set.

### GetPartNumberRevision

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) GetPartNumberRevision() string`

GetPartNumberRevision returns the PartNumberRevision field if non-nil, zero value otherwise.

### GetPartNumberRevisionOk

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) GetPartNumberRevisionOk() (*string, bool)`

GetPartNumberRevisionOk returns a tuple with the PartNumberRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumberRevision

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) SetPartNumberRevision(v string)`

SetPartNumberRevision sets PartNumberRevision field to given value.

### HasPartNumberRevision

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) HasPartNumberRevision() bool`

HasPartNumberRevision returns a boolean if a field has been set.

### GetPartRevision

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) GetPartRevision() string`

GetPartRevision returns the PartRevision field if non-nil, zero value otherwise.

### GetPartRevisionOk

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) GetPartRevisionOk() (*string, bool)`

GetPartRevisionOk returns a tuple with the PartRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartRevision

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) SetPartRevision(v string)`

SetPartRevision sets PartRevision field to given value.

### HasPartRevision

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) HasPartRevision() bool`

HasPartRevision returns a boolean if a field has been set.

### GetPrintMasterUnitID

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) GetPrintMasterUnitID() string`

GetPrintMasterUnitID returns the PrintMasterUnitID field if non-nil, zero value otherwise.

### GetPrintMasterUnitIDOk

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) GetPrintMasterUnitIDOk() (*string, bool)`

GetPrintMasterUnitIDOk returns a tuple with the PrintMasterUnitID field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrintMasterUnitID

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) SetPrintMasterUnitID(v string)`

SetPrintMasterUnitID sets PrintMasterUnitID field to given value.

### HasPrintMasterUnitID

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) HasPrintMasterUnitID() bool`

HasPrintMasterUnitID returns a boolean if a field has been set.

### GetQuantity

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetSerialNo

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) GetSerialNo() string`

GetSerialNo returns the SerialNo field if non-nil, zero value otherwise.

### GetSerialNoOk

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) GetSerialNoOk() (*string, bool)`

GetSerialNoOk returns a tuple with the SerialNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSerialNo

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) SetSerialNo(v string)`

SetSerialNo sets SerialNo field to given value.

### HasSerialNo

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) HasSerialNo() bool`

HasSerialNo returns a boolean if a field has been set.

### GetTrackingNo

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) GetTrackingNo() string`

GetTrackingNo returns the TrackingNo field if non-nil, zero value otherwise.

### GetTrackingNoOk

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) GetTrackingNoOk() (*string, bool)`

GetTrackingNoOk returns a tuple with the TrackingNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackingNo

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) SetTrackingNo(v string)`

SetTrackingNo sets TrackingNo field to given value.

### HasTrackingNo

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) HasTrackingNo() bool`

HasTrackingNo returns a boolean if a field has been set.

### GetWorkcenterCode

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) GetWorkcenterCode() string`

GetWorkcenterCode returns the WorkcenterCode field if non-nil, zero value otherwise.

### GetWorkcenterCodeOk

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) GetWorkcenterCodeOk() (*string, bool)`

GetWorkcenterCodeOk returns a tuple with the WorkcenterCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkcenterCode

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) SetWorkcenterCode(v string)`

SetWorkcenterCode sets WorkcenterCode field to given value.

### HasWorkcenterCode

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) HasWorkcenterCode() bool`

HasWorkcenterCode returns a boolean if a field has been set.

### GetWorkcenterId

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) GetWorkcenterId() string`

GetWorkcenterId returns the WorkcenterId field if non-nil, zero value otherwise.

### GetWorkcenterIdOk

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) GetWorkcenterIdOk() (*string, bool)`

GetWorkcenterIdOk returns a tuple with the WorkcenterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkcenterId

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) SetWorkcenterId(v string)`

SetWorkcenterId sets WorkcenterId field to given value.

### HasWorkcenterId

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) HasWorkcenterId() bool`

HasWorkcenterId returns a boolean if a field has been set.

### GetLocationId

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) GetLocationId() string`

GetLocationId returns the LocationId field if non-nil, zero value otherwise.

### GetLocationIdOk

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) GetLocationIdOk() (*string, bool)`

GetLocationIdOk returns a tuple with the LocationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocationId

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) SetLocationId(v string)`

SetLocationId sets LocationId field to given value.

### HasLocationId

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) HasLocationId() bool`

HasLocationId returns a boolean if a field has been set.

### GetLocation

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) GetLocation() string`

GetLocation returns the Location field if non-nil, zero value otherwise.

### GetLocationOk

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) GetLocationOk() (*string, bool)`

GetLocationOk returns a tuple with the Location field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocation

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) SetLocation(v string)`

SetLocation sets Location field to given value.

### HasLocation

`func (o *ProductionOperationsManagementApiRecordBatchProductionResponse) HasLocation() bool`

HasLocation returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


