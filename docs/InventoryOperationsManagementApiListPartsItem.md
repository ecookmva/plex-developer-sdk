# InventoryOperationsManagementApiListPartsItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PartId** | Pointer to **string** | The UUID assigned to a part. | [optional] 
**PartNumber** | Pointer to **string** | 100 characters max. A short code or number to call the part. This value shows up throughout the system, so use something others will recognize. Acceptable Part Number characters include uppercase and lowercase letters (A-Z), numbers (0-9), and special characters such as dashes (-), underscores ( _ ), and spaces. Other characters may cause issues. | [optional] 
**Revision** | Pointer to **string** | 8 characters max. A revision level represents a change or modification to a part or part drawing that is usually initiated through an engineering change request (ECR). | [optional] 
**PartNumberRevision** | Pointer to **string** | Format {partNumber}{part rev separator}{revision}. If a part number has a revision, Plex will return the part number and the revision separated by the Part Rev Separator setting. A Part Rev Separator can be up to 5 characters long. | [optional] 
**Type** | Pointer to **string** | 50 characters max. Setup table &amp;quot;Part Type&amp;quot; (part.dbo.Part_Type). Subclassification for the part. Examples include flange, fastener, gears, crown wheels, clutch hubs, body panels, gear shafts. | [optional] 
**Source** | Pointer to **string** | 50 characters max. Setup table &amp;quot;Part Source&amp;quot; (part.dbo.Part_Source). Categorize where the parts are from, purchased or made in house. The field is not tied to purchasing for lookups or searches. | [optional] 
**Status** | Pointer to **string** | 50 characters max. Setup table &amp;quot;Part Status&amp;quot; (part.dbo.Part_Status)The part status indicates the life cycle phase of the part. | [optional] 
**LotRequired** | Pointer to **bool** | Boolean flag to indicate whether lot required is enabled for this part. | [optional] 

## Methods

### NewInventoryOperationsManagementApiListPartsItem

`func NewInventoryOperationsManagementApiListPartsItem() *InventoryOperationsManagementApiListPartsItem`

NewInventoryOperationsManagementApiListPartsItem instantiates a new InventoryOperationsManagementApiListPartsItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInventoryOperationsManagementApiListPartsItemWithDefaults

`func NewInventoryOperationsManagementApiListPartsItemWithDefaults() *InventoryOperationsManagementApiListPartsItem`

NewInventoryOperationsManagementApiListPartsItemWithDefaults instantiates a new InventoryOperationsManagementApiListPartsItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPartId

`func (o *InventoryOperationsManagementApiListPartsItem) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *InventoryOperationsManagementApiListPartsItem) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *InventoryOperationsManagementApiListPartsItem) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *InventoryOperationsManagementApiListPartsItem) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetPartNumber

`func (o *InventoryOperationsManagementApiListPartsItem) GetPartNumber() string`

GetPartNumber returns the PartNumber field if non-nil, zero value otherwise.

### GetPartNumberOk

`func (o *InventoryOperationsManagementApiListPartsItem) GetPartNumberOk() (*string, bool)`

GetPartNumberOk returns a tuple with the PartNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumber

`func (o *InventoryOperationsManagementApiListPartsItem) SetPartNumber(v string)`

SetPartNumber sets PartNumber field to given value.

### HasPartNumber

`func (o *InventoryOperationsManagementApiListPartsItem) HasPartNumber() bool`

HasPartNumber returns a boolean if a field has been set.

### GetRevision

`func (o *InventoryOperationsManagementApiListPartsItem) GetRevision() string`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *InventoryOperationsManagementApiListPartsItem) GetRevisionOk() (*string, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *InventoryOperationsManagementApiListPartsItem) SetRevision(v string)`

SetRevision sets Revision field to given value.

### HasRevision

`func (o *InventoryOperationsManagementApiListPartsItem) HasRevision() bool`

HasRevision returns a boolean if a field has been set.

### GetPartNumberRevision

`func (o *InventoryOperationsManagementApiListPartsItem) GetPartNumberRevision() string`

GetPartNumberRevision returns the PartNumberRevision field if non-nil, zero value otherwise.

### GetPartNumberRevisionOk

`func (o *InventoryOperationsManagementApiListPartsItem) GetPartNumberRevisionOk() (*string, bool)`

GetPartNumberRevisionOk returns a tuple with the PartNumberRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumberRevision

`func (o *InventoryOperationsManagementApiListPartsItem) SetPartNumberRevision(v string)`

SetPartNumberRevision sets PartNumberRevision field to given value.

### HasPartNumberRevision

`func (o *InventoryOperationsManagementApiListPartsItem) HasPartNumberRevision() bool`

HasPartNumberRevision returns a boolean if a field has been set.

### GetType

`func (o *InventoryOperationsManagementApiListPartsItem) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *InventoryOperationsManagementApiListPartsItem) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *InventoryOperationsManagementApiListPartsItem) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *InventoryOperationsManagementApiListPartsItem) HasType() bool`

HasType returns a boolean if a field has been set.

### GetSource

`func (o *InventoryOperationsManagementApiListPartsItem) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *InventoryOperationsManagementApiListPartsItem) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *InventoryOperationsManagementApiListPartsItem) SetSource(v string)`

SetSource sets Source field to given value.

### HasSource

`func (o *InventoryOperationsManagementApiListPartsItem) HasSource() bool`

HasSource returns a boolean if a field has been set.

### GetStatus

`func (o *InventoryOperationsManagementApiListPartsItem) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *InventoryOperationsManagementApiListPartsItem) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *InventoryOperationsManagementApiListPartsItem) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *InventoryOperationsManagementApiListPartsItem) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetLotRequired

`func (o *InventoryOperationsManagementApiListPartsItem) GetLotRequired() bool`

GetLotRequired returns the LotRequired field if non-nil, zero value otherwise.

### GetLotRequiredOk

`func (o *InventoryOperationsManagementApiListPartsItem) GetLotRequiredOk() (*bool, bool)`

GetLotRequiredOk returns a tuple with the LotRequired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLotRequired

`func (o *InventoryOperationsManagementApiListPartsItem) SetLotRequired(v bool)`

SetLotRequired sets LotRequired field to given value.

### HasLotRequired

`func (o *InventoryOperationsManagementApiListPartsItem) HasLotRequired() bool`

HasLotRequired returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


