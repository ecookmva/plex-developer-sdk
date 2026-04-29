# ProductionOperationsManagementApiListScrapEntriesItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TransactionDate** | Pointer to **time.Time** | Date/Time Format YYYY-MM-DDThh:mm:ss.fffffffZ See Knowledge center topic &amp;quot;Dates and Times&amp;quot; for more information (KC path Platform &amp;gt; Plex APIs &amp;gt; HTTP Data Source API &amp;gt; Dates and Times). The date and time on which the scrap transaction was recorded in Plex. | [optional] 
**ScrapReason** | Pointer to **string** | 50 characters max. Setup table &amp;quot;Scrap Reason&amp;quot; (part.dbo.scrap_reason). The reason code which indicates why the material or part was scrapped. | [optional] 
**TransactionType** | Pointer to **string** | Possible values are &amp;quot;Control Panel Scrap&amp;quot; and &amp;quot;Scrap&amp;quot;. Scrapping a part being produced in Control Panel will be identified as Control Panel Scrap. Recording scrap using any other application will be identified as Scrap. | [optional] 
**Quantity** | Pointer to **float64** | Decimal, (19,5) max characters. Quantity that was scrapped. | [optional] 
**WorkcenterId** | Pointer to **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the workcenter where scrap was recorded. | [optional] 
**WorkcenterCode** | Pointer to **string** | 50 characters max. A short name associated to the workcenterID, and a unique code to reference the workcenter. This code shows up throughout the system, primarily on the Control Panel. | [optional] 
**JobId** | Pointer to **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the production job that scrap was recorded against. Note that a production job is not necessary to record scrap. Another scheduling method such as kanban may have been used. | [optional] 
**JobCode** | Pointer to **string** | 20 characters max. Job number, including prefix and suffix, associated to the jobID that scrap was recorded against. | [optional] 
**PartId** | Pointer to **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the part that was scrapped. | [optional] 
**PartNumber** | Pointer to **string** | 100 characters max. Part Number associated to the partId that was scrapped. A short code or number to call the part. This value shows up throughout the system, so use something others will recognize. Acceptable Part Number characters include uppercase and lowercase letters (A-Z), numbers (0-9), and special characters such as dashes (-), underscores ( _ ), and spaces. Other characters may cause issues. | [optional] 
**Revision** | Pointer to **string** | 8 characters max. Part Revision of the partID. A revision level represents a change or modification to a part or part drawing that is usually initiated through an engineering change request (ECR). | [optional] 
**PartNumberRevision** | Pointer to **string** | Format {partNumber}{part rev separator}{revision}. Part Number and Revision formatted with separator. If a part number has a revision, Plex will return the part number and the revision separated by the Part Rev Separator setting. A Part Rev Separator can be up to 5 characters long. | [optional] 
**PartOperationId** | Pointer to **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the part operation that was scrapped. | [optional] 
**OperationNumber** | Pointer to **int32** | 10 characters max. The Operation Number (sequence order) of the part Operation that was scrapped. | [optional] 
**OperationCode** | Pointer to **string** | 30 characters max. The Operation Code associated to the partOperationID. | [optional] 
**SerialNo** | Pointer to **string** | 25 characters max. The Serial No of the Scrap/Rejection Container. | [optional] 

## Methods

### NewProductionOperationsManagementApiListScrapEntriesItem

`func NewProductionOperationsManagementApiListScrapEntriesItem() *ProductionOperationsManagementApiListScrapEntriesItem`

NewProductionOperationsManagementApiListScrapEntriesItem instantiates a new ProductionOperationsManagementApiListScrapEntriesItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductionOperationsManagementApiListScrapEntriesItemWithDefaults

`func NewProductionOperationsManagementApiListScrapEntriesItemWithDefaults() *ProductionOperationsManagementApiListScrapEntriesItem`

NewProductionOperationsManagementApiListScrapEntriesItemWithDefaults instantiates a new ProductionOperationsManagementApiListScrapEntriesItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTransactionDate

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) GetTransactionDate() time.Time`

GetTransactionDate returns the TransactionDate field if non-nil, zero value otherwise.

### GetTransactionDateOk

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) GetTransactionDateOk() (*time.Time, bool)`

GetTransactionDateOk returns a tuple with the TransactionDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransactionDate

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) SetTransactionDate(v time.Time)`

SetTransactionDate sets TransactionDate field to given value.

### HasTransactionDate

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) HasTransactionDate() bool`

HasTransactionDate returns a boolean if a field has been set.

### GetScrapReason

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) GetScrapReason() string`

GetScrapReason returns the ScrapReason field if non-nil, zero value otherwise.

### GetScrapReasonOk

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) GetScrapReasonOk() (*string, bool)`

GetScrapReasonOk returns a tuple with the ScrapReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScrapReason

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) SetScrapReason(v string)`

SetScrapReason sets ScrapReason field to given value.

### HasScrapReason

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) HasScrapReason() bool`

HasScrapReason returns a boolean if a field has been set.

### GetTransactionType

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) GetTransactionType() string`

GetTransactionType returns the TransactionType field if non-nil, zero value otherwise.

### GetTransactionTypeOk

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) GetTransactionTypeOk() (*string, bool)`

GetTransactionTypeOk returns a tuple with the TransactionType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransactionType

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) SetTransactionType(v string)`

SetTransactionType sets TransactionType field to given value.

### HasTransactionType

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) HasTransactionType() bool`

HasTransactionType returns a boolean if a field has been set.

### GetQuantity

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetWorkcenterId

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) GetWorkcenterId() string`

GetWorkcenterId returns the WorkcenterId field if non-nil, zero value otherwise.

### GetWorkcenterIdOk

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) GetWorkcenterIdOk() (*string, bool)`

GetWorkcenterIdOk returns a tuple with the WorkcenterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkcenterId

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) SetWorkcenterId(v string)`

SetWorkcenterId sets WorkcenterId field to given value.

### HasWorkcenterId

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) HasWorkcenterId() bool`

HasWorkcenterId returns a boolean if a field has been set.

### GetWorkcenterCode

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) GetWorkcenterCode() string`

GetWorkcenterCode returns the WorkcenterCode field if non-nil, zero value otherwise.

### GetWorkcenterCodeOk

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) GetWorkcenterCodeOk() (*string, bool)`

GetWorkcenterCodeOk returns a tuple with the WorkcenterCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkcenterCode

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) SetWorkcenterCode(v string)`

SetWorkcenterCode sets WorkcenterCode field to given value.

### HasWorkcenterCode

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) HasWorkcenterCode() bool`

HasWorkcenterCode returns a boolean if a field has been set.

### GetJobId

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) GetJobId() string`

GetJobId returns the JobId field if non-nil, zero value otherwise.

### GetJobIdOk

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) GetJobIdOk() (*string, bool)`

GetJobIdOk returns a tuple with the JobId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobId

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) SetJobId(v string)`

SetJobId sets JobId field to given value.

### HasJobId

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) HasJobId() bool`

HasJobId returns a boolean if a field has been set.

### GetJobCode

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) GetJobCode() string`

GetJobCode returns the JobCode field if non-nil, zero value otherwise.

### GetJobCodeOk

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) GetJobCodeOk() (*string, bool)`

GetJobCodeOk returns a tuple with the JobCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobCode

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) SetJobCode(v string)`

SetJobCode sets JobCode field to given value.

### HasJobCode

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) HasJobCode() bool`

HasJobCode returns a boolean if a field has been set.

### GetPartId

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetPartNumber

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) GetPartNumber() string`

GetPartNumber returns the PartNumber field if non-nil, zero value otherwise.

### GetPartNumberOk

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) GetPartNumberOk() (*string, bool)`

GetPartNumberOk returns a tuple with the PartNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumber

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) SetPartNumber(v string)`

SetPartNumber sets PartNumber field to given value.

### HasPartNumber

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) HasPartNumber() bool`

HasPartNumber returns a boolean if a field has been set.

### GetRevision

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) GetRevision() string`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) GetRevisionOk() (*string, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) SetRevision(v string)`

SetRevision sets Revision field to given value.

### HasRevision

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) HasRevision() bool`

HasRevision returns a boolean if a field has been set.

### GetPartNumberRevision

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) GetPartNumberRevision() string`

GetPartNumberRevision returns the PartNumberRevision field if non-nil, zero value otherwise.

### GetPartNumberRevisionOk

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) GetPartNumberRevisionOk() (*string, bool)`

GetPartNumberRevisionOk returns a tuple with the PartNumberRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumberRevision

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) SetPartNumberRevision(v string)`

SetPartNumberRevision sets PartNumberRevision field to given value.

### HasPartNumberRevision

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) HasPartNumberRevision() bool`

HasPartNumberRevision returns a boolean if a field has been set.

### GetPartOperationId

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) GetPartOperationId() string`

GetPartOperationId returns the PartOperationId field if non-nil, zero value otherwise.

### GetPartOperationIdOk

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) GetPartOperationIdOk() (*string, bool)`

GetPartOperationIdOk returns a tuple with the PartOperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartOperationId

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) SetPartOperationId(v string)`

SetPartOperationId sets PartOperationId field to given value.

### HasPartOperationId

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) HasPartOperationId() bool`

HasPartOperationId returns a boolean if a field has been set.

### GetOperationNumber

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) GetOperationNumber() int32`

GetOperationNumber returns the OperationNumber field if non-nil, zero value otherwise.

### GetOperationNumberOk

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) GetOperationNumberOk() (*int32, bool)`

GetOperationNumberOk returns a tuple with the OperationNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationNumber

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) SetOperationNumber(v int32)`

SetOperationNumber sets OperationNumber field to given value.

### HasOperationNumber

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) HasOperationNumber() bool`

HasOperationNumber returns a boolean if a field has been set.

### GetOperationCode

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) GetOperationCode() string`

GetOperationCode returns the OperationCode field if non-nil, zero value otherwise.

### GetOperationCodeOk

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) GetOperationCodeOk() (*string, bool)`

GetOperationCodeOk returns a tuple with the OperationCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationCode

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) SetOperationCode(v string)`

SetOperationCode sets OperationCode field to given value.

### HasOperationCode

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) HasOperationCode() bool`

HasOperationCode returns a boolean if a field has been set.

### GetSerialNo

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) GetSerialNo() string`

GetSerialNo returns the SerialNo field if non-nil, zero value otherwise.

### GetSerialNoOk

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) GetSerialNoOk() (*string, bool)`

GetSerialNoOk returns a tuple with the SerialNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSerialNo

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) SetSerialNo(v string)`

SetSerialNo sets SerialNo field to given value.

### HasSerialNo

`func (o *ProductionOperationsManagementApiListScrapEntriesItem) HasSerialNo() bool`

HasSerialNo returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


