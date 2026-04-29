# ProductionOperationsManagementApiListLaborEntriesItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Employee** | Pointer to **string** | Format {Last Name}, {First Name} ({Department}) Example &amp;quot;Smith, John (Quality)&amp;quot;.&amp;quot; The name of an employee associated to labor record. | [optional] 
**EmployeeId** | Pointer to **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID assigned to employee that is associated to labor record. | [optional] 
**AccountId** | Pointer to **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID assigned to an IAM account that is associated to labor record. | [optional] 
**CostActivity** | Pointer to **string** | 50 characters max. The type of manufacturing labor activity that was performed, such as Setup, Maintenance, Production. This is the Cost Sub Type configured in Cost Types Setup application. | [optional] 
**WorkcenterId** | Pointer to **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the workcenter where the labor transaction was recorded. | [optional] 
**WorkcenterCode** | Pointer to **string** | 50 characters max. A short name associated to the workcenterID at which a labor transaction occurred. | [optional] 
**JobId** | Pointer to **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the production job that was loaded to the workcenter when labor record was created. | [optional] 
**JobCode** | Pointer to **string** | 20 characters max. Job number, including prefix and suffix, associated to the jobID that was loaded to the workcenter when labor record was created. | [optional] 
**PartId** | Pointer to **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the part that was being produced in the workcenter when the labor activity was recorded. | [optional] 
**PartNumber** | Pointer to **string** | 100 characters max. Part Number associated to the partId that was being produced in the workcenter when the labor activity was recorded. A short code or number to call the part. This value shows up throughout the system, so use something others will recognize. Acceptable Part Number characters include uppercase and lowercase letters (A-Z), numbers (0-9), and special characters such as dashes (-), underscores ( _ ), and spaces. Other characters may cause issues. | [optional] 
**Revision** | Pointer to **string** | 8 characters max. Part Revision of the partID. A revision level represents a change or modification to a part or part drawing that is usually initiated through an engineering change request (ECR). | [optional] 
**PartNumberRevision** | Pointer to **string** | Format {partNumber}{part rev separator}{revision}. Part Number and Revision formatted with separator. If a part number has a revision, Plex will return the part number and the revision separated by the Part Rev Separator setting. A Part Rev Separator can be up to 5 characters long. | [optional] 
**PartOperationId** | Pointer to **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. The UUID of the part operation that was being produced in the workcenter when the labor activity was recorded. | [optional] 
**OperationNumber** | Pointer to **int32** | 10 characters max. The Operation Number (sequence order) of the part Operation that was being produced in the workcenter when the labor activity was recorded. | [optional] 
**OperationCode** | Pointer to **string** | 30 characters max. The Operation Code associated to the partOperationID. | [optional] 
**BeginTime** | Pointer to **time.Time** | Date/Time Format YYYY-MM-DDThh:mm:ss.fffffffZ See Knowledge center topic &amp;quot;Dates and Times&amp;quot; for more information (KC path Platform &amp;gt; Plex APIs &amp;gt; HTTP Data Source API &amp;gt; Dates and Times). The start date and time of the activity. | [optional] 
**EndTime** | Pointer to **time.Time** | Date/Time Format YYYY-MM-DDThh:mm:ss.fffffffZ See Knowledge center topic &amp;quot;Dates and Times&amp;quot; for more information (KC path Platform &amp;gt; Plex APIs &amp;gt; HTTP Data Source API &amp;gt; Dates and Times). The end date and time of the activity. | [optional] 
**Duration** | Pointer to **int32** | The duration of the labor record in minutes. | [optional] 

## Methods

### NewProductionOperationsManagementApiListLaborEntriesItem

`func NewProductionOperationsManagementApiListLaborEntriesItem() *ProductionOperationsManagementApiListLaborEntriesItem`

NewProductionOperationsManagementApiListLaborEntriesItem instantiates a new ProductionOperationsManagementApiListLaborEntriesItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductionOperationsManagementApiListLaborEntriesItemWithDefaults

`func NewProductionOperationsManagementApiListLaborEntriesItemWithDefaults() *ProductionOperationsManagementApiListLaborEntriesItem`

NewProductionOperationsManagementApiListLaborEntriesItemWithDefaults instantiates a new ProductionOperationsManagementApiListLaborEntriesItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEmployee

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) GetEmployee() string`

GetEmployee returns the Employee field if non-nil, zero value otherwise.

### GetEmployeeOk

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) GetEmployeeOk() (*string, bool)`

GetEmployeeOk returns a tuple with the Employee field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmployee

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) SetEmployee(v string)`

SetEmployee sets Employee field to given value.

### HasEmployee

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) HasEmployee() bool`

HasEmployee returns a boolean if a field has been set.

### GetEmployeeId

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) GetEmployeeId() string`

GetEmployeeId returns the EmployeeId field if non-nil, zero value otherwise.

### GetEmployeeIdOk

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) GetEmployeeIdOk() (*string, bool)`

GetEmployeeIdOk returns a tuple with the EmployeeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmployeeId

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) SetEmployeeId(v string)`

SetEmployeeId sets EmployeeId field to given value.

### HasEmployeeId

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) HasEmployeeId() bool`

HasEmployeeId returns a boolean if a field has been set.

### GetAccountId

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) GetAccountId() string`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) GetAccountIdOk() (*string, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) SetAccountId(v string)`

SetAccountId sets AccountId field to given value.

### HasAccountId

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) HasAccountId() bool`

HasAccountId returns a boolean if a field has been set.

### GetCostActivity

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) GetCostActivity() string`

GetCostActivity returns the CostActivity field if non-nil, zero value otherwise.

### GetCostActivityOk

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) GetCostActivityOk() (*string, bool)`

GetCostActivityOk returns a tuple with the CostActivity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostActivity

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) SetCostActivity(v string)`

SetCostActivity sets CostActivity field to given value.

### HasCostActivity

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) HasCostActivity() bool`

HasCostActivity returns a boolean if a field has been set.

### GetWorkcenterId

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) GetWorkcenterId() string`

GetWorkcenterId returns the WorkcenterId field if non-nil, zero value otherwise.

### GetWorkcenterIdOk

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) GetWorkcenterIdOk() (*string, bool)`

GetWorkcenterIdOk returns a tuple with the WorkcenterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkcenterId

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) SetWorkcenterId(v string)`

SetWorkcenterId sets WorkcenterId field to given value.

### HasWorkcenterId

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) HasWorkcenterId() bool`

HasWorkcenterId returns a boolean if a field has been set.

### GetWorkcenterCode

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) GetWorkcenterCode() string`

GetWorkcenterCode returns the WorkcenterCode field if non-nil, zero value otherwise.

### GetWorkcenterCodeOk

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) GetWorkcenterCodeOk() (*string, bool)`

GetWorkcenterCodeOk returns a tuple with the WorkcenterCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkcenterCode

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) SetWorkcenterCode(v string)`

SetWorkcenterCode sets WorkcenterCode field to given value.

### HasWorkcenterCode

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) HasWorkcenterCode() bool`

HasWorkcenterCode returns a boolean if a field has been set.

### GetJobId

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) GetJobId() string`

GetJobId returns the JobId field if non-nil, zero value otherwise.

### GetJobIdOk

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) GetJobIdOk() (*string, bool)`

GetJobIdOk returns a tuple with the JobId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobId

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) SetJobId(v string)`

SetJobId sets JobId field to given value.

### HasJobId

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) HasJobId() bool`

HasJobId returns a boolean if a field has been set.

### GetJobCode

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) GetJobCode() string`

GetJobCode returns the JobCode field if non-nil, zero value otherwise.

### GetJobCodeOk

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) GetJobCodeOk() (*string, bool)`

GetJobCodeOk returns a tuple with the JobCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobCode

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) SetJobCode(v string)`

SetJobCode sets JobCode field to given value.

### HasJobCode

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) HasJobCode() bool`

HasJobCode returns a boolean if a field has been set.

### GetPartId

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetPartNumber

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) GetPartNumber() string`

GetPartNumber returns the PartNumber field if non-nil, zero value otherwise.

### GetPartNumberOk

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) GetPartNumberOk() (*string, bool)`

GetPartNumberOk returns a tuple with the PartNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumber

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) SetPartNumber(v string)`

SetPartNumber sets PartNumber field to given value.

### HasPartNumber

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) HasPartNumber() bool`

HasPartNumber returns a boolean if a field has been set.

### GetRevision

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) GetRevision() string`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) GetRevisionOk() (*string, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) SetRevision(v string)`

SetRevision sets Revision field to given value.

### HasRevision

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) HasRevision() bool`

HasRevision returns a boolean if a field has been set.

### GetPartNumberRevision

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) GetPartNumberRevision() string`

GetPartNumberRevision returns the PartNumberRevision field if non-nil, zero value otherwise.

### GetPartNumberRevisionOk

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) GetPartNumberRevisionOk() (*string, bool)`

GetPartNumberRevisionOk returns a tuple with the PartNumberRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumberRevision

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) SetPartNumberRevision(v string)`

SetPartNumberRevision sets PartNumberRevision field to given value.

### HasPartNumberRevision

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) HasPartNumberRevision() bool`

HasPartNumberRevision returns a boolean if a field has been set.

### GetPartOperationId

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) GetPartOperationId() string`

GetPartOperationId returns the PartOperationId field if non-nil, zero value otherwise.

### GetPartOperationIdOk

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) GetPartOperationIdOk() (*string, bool)`

GetPartOperationIdOk returns a tuple with the PartOperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartOperationId

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) SetPartOperationId(v string)`

SetPartOperationId sets PartOperationId field to given value.

### HasPartOperationId

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) HasPartOperationId() bool`

HasPartOperationId returns a boolean if a field has been set.

### GetOperationNumber

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) GetOperationNumber() int32`

GetOperationNumber returns the OperationNumber field if non-nil, zero value otherwise.

### GetOperationNumberOk

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) GetOperationNumberOk() (*int32, bool)`

GetOperationNumberOk returns a tuple with the OperationNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationNumber

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) SetOperationNumber(v int32)`

SetOperationNumber sets OperationNumber field to given value.

### HasOperationNumber

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) HasOperationNumber() bool`

HasOperationNumber returns a boolean if a field has been set.

### GetOperationCode

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) GetOperationCode() string`

GetOperationCode returns the OperationCode field if non-nil, zero value otherwise.

### GetOperationCodeOk

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) GetOperationCodeOk() (*string, bool)`

GetOperationCodeOk returns a tuple with the OperationCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationCode

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) SetOperationCode(v string)`

SetOperationCode sets OperationCode field to given value.

### HasOperationCode

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) HasOperationCode() bool`

HasOperationCode returns a boolean if a field has been set.

### GetBeginTime

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) GetBeginTime() time.Time`

GetBeginTime returns the BeginTime field if non-nil, zero value otherwise.

### GetBeginTimeOk

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) GetBeginTimeOk() (*time.Time, bool)`

GetBeginTimeOk returns a tuple with the BeginTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBeginTime

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) SetBeginTime(v time.Time)`

SetBeginTime sets BeginTime field to given value.

### HasBeginTime

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) HasBeginTime() bool`

HasBeginTime returns a boolean if a field has been set.

### GetEndTime

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) GetEndTime() time.Time`

GetEndTime returns the EndTime field if non-nil, zero value otherwise.

### GetEndTimeOk

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) GetEndTimeOk() (*time.Time, bool)`

GetEndTimeOk returns a tuple with the EndTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndTime

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) SetEndTime(v time.Time)`

SetEndTime sets EndTime field to given value.

### HasEndTime

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) HasEndTime() bool`

HasEndTime returns a boolean if a field has been set.

### GetDuration

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) GetDuration() int32`

GetDuration returns the Duration field if non-nil, zero value otherwise.

### GetDurationOk

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) GetDurationOk() (*int32, bool)`

GetDurationOk returns a tuple with the Duration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuration

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) SetDuration(v int32)`

SetDuration sets Duration field to given value.

### HasDuration

`func (o *ProductionOperationsManagementApiListLaborEntriesItem) HasDuration() bool`

HasDuration returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


