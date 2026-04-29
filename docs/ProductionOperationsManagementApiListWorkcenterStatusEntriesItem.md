# ProductionOperationsManagementApiListWorkcenterStatusEntriesItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**WorkcenterId** | Pointer to **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the workcenter where the status transaction was recorded. | [optional] 
**WorkcenterCode** | Pointer to **string** | 50 characters max. A short name associated to the workcenterID, and a unique code to reference the workcenter. This code shows up throughout the system, primarily on the Control Panel. | [optional] 
**LogDate** | Pointer to **time.Time** | Date/Time Format YYYY-MM-DDThh:mm:ss.fffffffZ See Knowledge center topic &amp;quot;Dates and Times&amp;quot; for more information (KC path Platform &amp;gt; Plex APIs &amp;gt; HTTP Data Source API &amp;gt; Dates and Times). The date and time when the workcenter status transaction started. | [optional] 
**WorkcenterStatus** | Pointer to **string** | 50 characters max. The workcenter status associated to a recorded transaction. | [optional] 
**JobId** | Pointer to **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the production job that was loaded to the workcenter. | [optional] 
**JobCode** | Pointer to **string** | 20 characters max. Job number, including prefix and suffix, associated to the jobID. | [optional] 
**PartId** | Pointer to **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the part that was being produced in the workcenter when the workcenter status transaction was recorded. | [optional] 
**PartNumber** | Pointer to **string** | 100 characters max. Part Number associated to the partId that was being produced in the workcenter when the workcenter status transaction was recorded. A short code or number to call the part. This value shows up throughout the system, so use something others will recognize. Acceptable Part Number characters include uppercase and lowercase letters (A-Z), numbers (0-9), and special characters such as dashes (-), underscores ( _ ), and spaces. Other characters may cause issues. | [optional] 
**Revision** | Pointer to **string** | 8 characters max. Part Revision of the partID. A revision level represents a change or modification to a part or part drawing that is usually initiated through an engineering change request (ECR). | [optional] 
**PartNumberRevision** | Pointer to **string** | Format {partNumber}{part rev separator}{revision}. Part Number and Revision formatted with separator. If a part number has a revision, Plex will return the part number and the revision separated by the Part Rev Separator setting. A Part Rev Separator can be up to 5 characters long. | [optional] 
**PartOperationId** | Pointer to **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. The UUID of the part operation that was being produced in the workcenter when the workcenter status transaction was recorded. | [optional] 
**OperationNumber** | Pointer to **int32** | 10 characters max. The Operation Number (sequence order) of the part Operation that was being produced in the workcenter when the workcenter status transaction was recorded. | [optional] 
**OperationCode** | Pointer to **string** | 30 characters max. The Operation Code associated to the partOperationID. | [optional] 
**Duration** | Pointer to **int32** | Duration that the workcenter was in the workcenter status given in seconds. | [optional] 

## Methods

### NewProductionOperationsManagementApiListWorkcenterStatusEntriesItem

`func NewProductionOperationsManagementApiListWorkcenterStatusEntriesItem() *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem`

NewProductionOperationsManagementApiListWorkcenterStatusEntriesItem instantiates a new ProductionOperationsManagementApiListWorkcenterStatusEntriesItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductionOperationsManagementApiListWorkcenterStatusEntriesItemWithDefaults

`func NewProductionOperationsManagementApiListWorkcenterStatusEntriesItemWithDefaults() *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem`

NewProductionOperationsManagementApiListWorkcenterStatusEntriesItemWithDefaults instantiates a new ProductionOperationsManagementApiListWorkcenterStatusEntriesItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetWorkcenterId

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) GetWorkcenterId() string`

GetWorkcenterId returns the WorkcenterId field if non-nil, zero value otherwise.

### GetWorkcenterIdOk

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) GetWorkcenterIdOk() (*string, bool)`

GetWorkcenterIdOk returns a tuple with the WorkcenterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkcenterId

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) SetWorkcenterId(v string)`

SetWorkcenterId sets WorkcenterId field to given value.

### HasWorkcenterId

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) HasWorkcenterId() bool`

HasWorkcenterId returns a boolean if a field has been set.

### GetWorkcenterCode

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) GetWorkcenterCode() string`

GetWorkcenterCode returns the WorkcenterCode field if non-nil, zero value otherwise.

### GetWorkcenterCodeOk

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) GetWorkcenterCodeOk() (*string, bool)`

GetWorkcenterCodeOk returns a tuple with the WorkcenterCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkcenterCode

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) SetWorkcenterCode(v string)`

SetWorkcenterCode sets WorkcenterCode field to given value.

### HasWorkcenterCode

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) HasWorkcenterCode() bool`

HasWorkcenterCode returns a boolean if a field has been set.

### GetLogDate

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) GetLogDate() time.Time`

GetLogDate returns the LogDate field if non-nil, zero value otherwise.

### GetLogDateOk

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) GetLogDateOk() (*time.Time, bool)`

GetLogDateOk returns a tuple with the LogDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogDate

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) SetLogDate(v time.Time)`

SetLogDate sets LogDate field to given value.

### HasLogDate

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) HasLogDate() bool`

HasLogDate returns a boolean if a field has been set.

### GetWorkcenterStatus

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) GetWorkcenterStatus() string`

GetWorkcenterStatus returns the WorkcenterStatus field if non-nil, zero value otherwise.

### GetWorkcenterStatusOk

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) GetWorkcenterStatusOk() (*string, bool)`

GetWorkcenterStatusOk returns a tuple with the WorkcenterStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkcenterStatus

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) SetWorkcenterStatus(v string)`

SetWorkcenterStatus sets WorkcenterStatus field to given value.

### HasWorkcenterStatus

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) HasWorkcenterStatus() bool`

HasWorkcenterStatus returns a boolean if a field has been set.

### GetJobId

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) GetJobId() string`

GetJobId returns the JobId field if non-nil, zero value otherwise.

### GetJobIdOk

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) GetJobIdOk() (*string, bool)`

GetJobIdOk returns a tuple with the JobId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobId

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) SetJobId(v string)`

SetJobId sets JobId field to given value.

### HasJobId

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) HasJobId() bool`

HasJobId returns a boolean if a field has been set.

### GetJobCode

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) GetJobCode() string`

GetJobCode returns the JobCode field if non-nil, zero value otherwise.

### GetJobCodeOk

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) GetJobCodeOk() (*string, bool)`

GetJobCodeOk returns a tuple with the JobCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobCode

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) SetJobCode(v string)`

SetJobCode sets JobCode field to given value.

### HasJobCode

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) HasJobCode() bool`

HasJobCode returns a boolean if a field has been set.

### GetPartId

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetPartNumber

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) GetPartNumber() string`

GetPartNumber returns the PartNumber field if non-nil, zero value otherwise.

### GetPartNumberOk

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) GetPartNumberOk() (*string, bool)`

GetPartNumberOk returns a tuple with the PartNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumber

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) SetPartNumber(v string)`

SetPartNumber sets PartNumber field to given value.

### HasPartNumber

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) HasPartNumber() bool`

HasPartNumber returns a boolean if a field has been set.

### GetRevision

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) GetRevision() string`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) GetRevisionOk() (*string, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) SetRevision(v string)`

SetRevision sets Revision field to given value.

### HasRevision

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) HasRevision() bool`

HasRevision returns a boolean if a field has been set.

### GetPartNumberRevision

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) GetPartNumberRevision() string`

GetPartNumberRevision returns the PartNumberRevision field if non-nil, zero value otherwise.

### GetPartNumberRevisionOk

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) GetPartNumberRevisionOk() (*string, bool)`

GetPartNumberRevisionOk returns a tuple with the PartNumberRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumberRevision

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) SetPartNumberRevision(v string)`

SetPartNumberRevision sets PartNumberRevision field to given value.

### HasPartNumberRevision

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) HasPartNumberRevision() bool`

HasPartNumberRevision returns a boolean if a field has been set.

### GetPartOperationId

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) GetPartOperationId() string`

GetPartOperationId returns the PartOperationId field if non-nil, zero value otherwise.

### GetPartOperationIdOk

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) GetPartOperationIdOk() (*string, bool)`

GetPartOperationIdOk returns a tuple with the PartOperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartOperationId

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) SetPartOperationId(v string)`

SetPartOperationId sets PartOperationId field to given value.

### HasPartOperationId

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) HasPartOperationId() bool`

HasPartOperationId returns a boolean if a field has been set.

### GetOperationNumber

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) GetOperationNumber() int32`

GetOperationNumber returns the OperationNumber field if non-nil, zero value otherwise.

### GetOperationNumberOk

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) GetOperationNumberOk() (*int32, bool)`

GetOperationNumberOk returns a tuple with the OperationNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationNumber

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) SetOperationNumber(v int32)`

SetOperationNumber sets OperationNumber field to given value.

### HasOperationNumber

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) HasOperationNumber() bool`

HasOperationNumber returns a boolean if a field has been set.

### GetOperationCode

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) GetOperationCode() string`

GetOperationCode returns the OperationCode field if non-nil, zero value otherwise.

### GetOperationCodeOk

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) GetOperationCodeOk() (*string, bool)`

GetOperationCodeOk returns a tuple with the OperationCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationCode

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) SetOperationCode(v string)`

SetOperationCode sets OperationCode field to given value.

### HasOperationCode

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) HasOperationCode() bool`

HasOperationCode returns a boolean if a field has been set.

### GetDuration

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) GetDuration() int32`

GetDuration returns the Duration field if non-nil, zero value otherwise.

### GetDurationOk

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) GetDurationOk() (*int32, bool)`

GetDurationOk returns a tuple with the Duration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuration

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) SetDuration(v int32)`

SetDuration sets Duration field to given value.

### HasDuration

`func (o *ProductionOperationsManagementApiListWorkcenterStatusEntriesItem) HasDuration() bool`

HasDuration returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


