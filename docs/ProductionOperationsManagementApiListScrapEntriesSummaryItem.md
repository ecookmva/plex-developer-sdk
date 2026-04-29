# ProductionOperationsManagementApiListScrapEntriesSummaryItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PartId** | Pointer to **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the part that was scrapped. | [optional] 
**PartNumber** | Pointer to **string** | 100 characters max. Part Number associated to the partId that was scrapped. A short code or number to call the part. This value shows up throughout the system, so use something others will recognize. Acceptable Part Number characters include uppercase and lowercase letters (A-Z), numbers (0-9), and special characters such as dashes (-), underscores ( _ ), and spaces. Other characters may cause issues. | [optional] 
**Revision** | Pointer to **string** | 8 characters max. Part Revision of the partID. A revision level represents a change or modification to a part or part drawing that is usually initiated through an engineering change request (ECR). | [optional] 
**PartNumberRevision** | Pointer to **string** | Format {partNumber}{part rev separator}{revision}. Part Number and Revision formatted with separator. If a part number has a revision, Plex will return the part number and the revision separated by the Part Rev Separator setting. A Part Rev Separator can be up to 5 characters long. | [optional] 
**PartOperationId** | Pointer to **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the part operation that was scrapped. | [optional] 
**OperationCode** | Pointer to **string** | 30 characters max. The Operation Code associated to the partoperationID. | [optional] 
**SerialNo** | Pointer to **string** | 50 characters max. The Serial No of the Scrap/Rejection Container. | [optional] 
**OperationNumber** | Pointer to **int32** | 10 characters max. The Operation Number (sequence order) of the part Operation that was scrapped. | [optional] 
**WorkcenterId** | Pointer to **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the workcenter where scrap was recorded. | [optional] 
**WorkcenterCode** | Pointer to **string** | 50 characters max. A short name associated to the workcenterID, and a unique code to reference the workcenter. This code shows up throughout the system, primarily on the Control Panel. | [optional] 
**JobId** | Pointer to **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. UUID of the production job that scrap was recorded against. Note that a production job is not necessary to record scrap. Another scheduling method such as kanban may have been used. | [optional] 
**JobNumber** | Pointer to **string** | 20 characters max. Job number, including prefix and suffix, associated to the jobID that scrap was recorded against. | [optional] 
**ScrapReason** | Pointer to **string** | 50 characters max. Setup table &amp;quot;Scrap Reason&amp;quot; (part.dbo.scrap_reason). The reason code which indicates why the material or part was scrapped. | [optional] 
**TotalQuantity** | Pointer to **float64** | Decimal, (19,5) max characters. Total Quantity that was scrapped. | [optional] 

## Methods

### NewProductionOperationsManagementApiListScrapEntriesSummaryItem

`func NewProductionOperationsManagementApiListScrapEntriesSummaryItem() *ProductionOperationsManagementApiListScrapEntriesSummaryItem`

NewProductionOperationsManagementApiListScrapEntriesSummaryItem instantiates a new ProductionOperationsManagementApiListScrapEntriesSummaryItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductionOperationsManagementApiListScrapEntriesSummaryItemWithDefaults

`func NewProductionOperationsManagementApiListScrapEntriesSummaryItemWithDefaults() *ProductionOperationsManagementApiListScrapEntriesSummaryItem`

NewProductionOperationsManagementApiListScrapEntriesSummaryItemWithDefaults instantiates a new ProductionOperationsManagementApiListScrapEntriesSummaryItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPartId

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetPartNumber

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) GetPartNumber() string`

GetPartNumber returns the PartNumber field if non-nil, zero value otherwise.

### GetPartNumberOk

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) GetPartNumberOk() (*string, bool)`

GetPartNumberOk returns a tuple with the PartNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumber

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) SetPartNumber(v string)`

SetPartNumber sets PartNumber field to given value.

### HasPartNumber

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) HasPartNumber() bool`

HasPartNumber returns a boolean if a field has been set.

### GetRevision

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) GetRevision() string`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) GetRevisionOk() (*string, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) SetRevision(v string)`

SetRevision sets Revision field to given value.

### HasRevision

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) HasRevision() bool`

HasRevision returns a boolean if a field has been set.

### GetPartNumberRevision

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) GetPartNumberRevision() string`

GetPartNumberRevision returns the PartNumberRevision field if non-nil, zero value otherwise.

### GetPartNumberRevisionOk

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) GetPartNumberRevisionOk() (*string, bool)`

GetPartNumberRevisionOk returns a tuple with the PartNumberRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumberRevision

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) SetPartNumberRevision(v string)`

SetPartNumberRevision sets PartNumberRevision field to given value.

### HasPartNumberRevision

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) HasPartNumberRevision() bool`

HasPartNumberRevision returns a boolean if a field has been set.

### GetPartOperationId

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) GetPartOperationId() string`

GetPartOperationId returns the PartOperationId field if non-nil, zero value otherwise.

### GetPartOperationIdOk

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) GetPartOperationIdOk() (*string, bool)`

GetPartOperationIdOk returns a tuple with the PartOperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartOperationId

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) SetPartOperationId(v string)`

SetPartOperationId sets PartOperationId field to given value.

### HasPartOperationId

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) HasPartOperationId() bool`

HasPartOperationId returns a boolean if a field has been set.

### GetOperationCode

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) GetOperationCode() string`

GetOperationCode returns the OperationCode field if non-nil, zero value otherwise.

### GetOperationCodeOk

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) GetOperationCodeOk() (*string, bool)`

GetOperationCodeOk returns a tuple with the OperationCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationCode

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) SetOperationCode(v string)`

SetOperationCode sets OperationCode field to given value.

### HasOperationCode

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) HasOperationCode() bool`

HasOperationCode returns a boolean if a field has been set.

### GetSerialNo

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) GetSerialNo() string`

GetSerialNo returns the SerialNo field if non-nil, zero value otherwise.

### GetSerialNoOk

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) GetSerialNoOk() (*string, bool)`

GetSerialNoOk returns a tuple with the SerialNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSerialNo

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) SetSerialNo(v string)`

SetSerialNo sets SerialNo field to given value.

### HasSerialNo

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) HasSerialNo() bool`

HasSerialNo returns a boolean if a field has been set.

### GetOperationNumber

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) GetOperationNumber() int32`

GetOperationNumber returns the OperationNumber field if non-nil, zero value otherwise.

### GetOperationNumberOk

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) GetOperationNumberOk() (*int32, bool)`

GetOperationNumberOk returns a tuple with the OperationNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationNumber

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) SetOperationNumber(v int32)`

SetOperationNumber sets OperationNumber field to given value.

### HasOperationNumber

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) HasOperationNumber() bool`

HasOperationNumber returns a boolean if a field has been set.

### GetWorkcenterId

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) GetWorkcenterId() string`

GetWorkcenterId returns the WorkcenterId field if non-nil, zero value otherwise.

### GetWorkcenterIdOk

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) GetWorkcenterIdOk() (*string, bool)`

GetWorkcenterIdOk returns a tuple with the WorkcenterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkcenterId

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) SetWorkcenterId(v string)`

SetWorkcenterId sets WorkcenterId field to given value.

### HasWorkcenterId

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) HasWorkcenterId() bool`

HasWorkcenterId returns a boolean if a field has been set.

### GetWorkcenterCode

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) GetWorkcenterCode() string`

GetWorkcenterCode returns the WorkcenterCode field if non-nil, zero value otherwise.

### GetWorkcenterCodeOk

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) GetWorkcenterCodeOk() (*string, bool)`

GetWorkcenterCodeOk returns a tuple with the WorkcenterCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkcenterCode

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) SetWorkcenterCode(v string)`

SetWorkcenterCode sets WorkcenterCode field to given value.

### HasWorkcenterCode

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) HasWorkcenterCode() bool`

HasWorkcenterCode returns a boolean if a field has been set.

### GetJobId

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) GetJobId() string`

GetJobId returns the JobId field if non-nil, zero value otherwise.

### GetJobIdOk

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) GetJobIdOk() (*string, bool)`

GetJobIdOk returns a tuple with the JobId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobId

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) SetJobId(v string)`

SetJobId sets JobId field to given value.

### HasJobId

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) HasJobId() bool`

HasJobId returns a boolean if a field has been set.

### GetJobNumber

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) GetJobNumber() string`

GetJobNumber returns the JobNumber field if non-nil, zero value otherwise.

### GetJobNumberOk

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) GetJobNumberOk() (*string, bool)`

GetJobNumberOk returns a tuple with the JobNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobNumber

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) SetJobNumber(v string)`

SetJobNumber sets JobNumber field to given value.

### HasJobNumber

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) HasJobNumber() bool`

HasJobNumber returns a boolean if a field has been set.

### GetScrapReason

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) GetScrapReason() string`

GetScrapReason returns the ScrapReason field if non-nil, zero value otherwise.

### GetScrapReasonOk

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) GetScrapReasonOk() (*string, bool)`

GetScrapReasonOk returns a tuple with the ScrapReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScrapReason

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) SetScrapReason(v string)`

SetScrapReason sets ScrapReason field to given value.

### HasScrapReason

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) HasScrapReason() bool`

HasScrapReason returns a boolean if a field has been set.

### GetTotalQuantity

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) GetTotalQuantity() float64`

GetTotalQuantity returns the TotalQuantity field if non-nil, zero value otherwise.

### GetTotalQuantityOk

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) GetTotalQuantityOk() (*float64, bool)`

GetTotalQuantityOk returns a tuple with the TotalQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalQuantity

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) SetTotalQuantity(v float64)`

SetTotalQuantity sets TotalQuantity field to given value.

### HasTotalQuantity

`func (o *ProductionOperationsManagementApiListScrapEntriesSummaryItem) HasTotalQuantity() bool`

HasTotalQuantity returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


