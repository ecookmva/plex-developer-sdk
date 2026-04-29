# InventoryOperationsManagementApiListContainerLocationMovesItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AdjustmentDate** | Pointer to **time.Time** | The date and time when an inventory adjustment was made. | [optional] 
**SerialNo** | Pointer to **string** | 25 characters max. The serial number of the container that was changed. | [optional] 
**Quantity** | Pointer to **float64** | Decimal, (19,5) max characters. The delta quantity that was changed. This value could be a positive number (inventory quantity increased) or a negative number (inventory quantity decreased). | [optional] 
**NetWeight** | Pointer to **float64** | Decimal, (19,5) max characters. The delta net weight that was changed. This value could be a positive number (weight increased) or a negative number (weight decreased). | [optional] 
**AdjustmentCode** | Pointer to **string** | 50 characters max. Setup table &amp;quot;Adjustment Reason&amp;quot; (part.dbo.adjustment_reason). The Adjustment Reason setup table lists the acceptable reasons for inventory changes. | [optional] 
**PartId** | Pointer to **string** | The container&#39;s Part ID. | [optional] 
**PartNumber** | Pointer to **string** | 100 characters max. The container&#39;s Part Number. A short code or number to call the part. This value shows up throughout the system, so use something others will recognize. Acceptable Part Number characters include uppercase and lowercase letters (A-Z), numbers (0-9), and special characters such as dashes (-), underscores ( _ ), and spaces. Other characters may cause issues. | [optional] 
**Revision** | Pointer to **string** | 8 characters max. The container&#39;s Part Revision. A revision level represents a change or modification to a part or part drawing that is usually initiated through an engineering change request (ECR). | [optional] 
**PartNumberRevision** | Pointer to **string** | Format {partNumber}{part rev separator}{revision}. The container&#39;s Part Number Revision formatted with separator. If a part number has a revision, Plex will return the part number and the revision separated by the Part Rev Separator setting. A Part Rev Separator can be up to 5 characters long. | [optional] 
**PartOperationId** | Pointer to **string** | The container&#39;s Part Operation ID. | [optional] 
**OperationCode** | Pointer to **string** | 10 characters max. The container&#39;s Operation Code. | [optional] 
**OperationNumber** | Pointer to **int32** | 30 characters max. The container&#39;s Operation Number (sequence order). | [optional] 
**Location** | Pointer to **string** | 50 characters max. The Location Code of the container that was changed. | [optional] 
**LocationId** | Pointer to **string** | The location ID of the container that was changed. | [optional] 
**MovedFromLocation** | Pointer to **string** | 50 characters max. The prior Location Code of the container that was changed. | [optional] 
**MovedFromLocationId** | Pointer to **string** | The prior location ID of the container that was changed. | [optional] 

## Methods

### NewInventoryOperationsManagementApiListContainerLocationMovesItem

`func NewInventoryOperationsManagementApiListContainerLocationMovesItem() *InventoryOperationsManagementApiListContainerLocationMovesItem`

NewInventoryOperationsManagementApiListContainerLocationMovesItem instantiates a new InventoryOperationsManagementApiListContainerLocationMovesItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInventoryOperationsManagementApiListContainerLocationMovesItemWithDefaults

`func NewInventoryOperationsManagementApiListContainerLocationMovesItemWithDefaults() *InventoryOperationsManagementApiListContainerLocationMovesItem`

NewInventoryOperationsManagementApiListContainerLocationMovesItemWithDefaults instantiates a new InventoryOperationsManagementApiListContainerLocationMovesItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAdjustmentDate

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) GetAdjustmentDate() time.Time`

GetAdjustmentDate returns the AdjustmentDate field if non-nil, zero value otherwise.

### GetAdjustmentDateOk

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) GetAdjustmentDateOk() (*time.Time, bool)`

GetAdjustmentDateOk returns a tuple with the AdjustmentDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdjustmentDate

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) SetAdjustmentDate(v time.Time)`

SetAdjustmentDate sets AdjustmentDate field to given value.

### HasAdjustmentDate

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) HasAdjustmentDate() bool`

HasAdjustmentDate returns a boolean if a field has been set.

### GetSerialNo

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) GetSerialNo() string`

GetSerialNo returns the SerialNo field if non-nil, zero value otherwise.

### GetSerialNoOk

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) GetSerialNoOk() (*string, bool)`

GetSerialNoOk returns a tuple with the SerialNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSerialNo

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) SetSerialNo(v string)`

SetSerialNo sets SerialNo field to given value.

### HasSerialNo

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) HasSerialNo() bool`

HasSerialNo returns a boolean if a field has been set.

### GetQuantity

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetNetWeight

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) GetNetWeight() float64`

GetNetWeight returns the NetWeight field if non-nil, zero value otherwise.

### GetNetWeightOk

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) GetNetWeightOk() (*float64, bool)`

GetNetWeightOk returns a tuple with the NetWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetWeight

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) SetNetWeight(v float64)`

SetNetWeight sets NetWeight field to given value.

### HasNetWeight

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) HasNetWeight() bool`

HasNetWeight returns a boolean if a field has been set.

### GetAdjustmentCode

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) GetAdjustmentCode() string`

GetAdjustmentCode returns the AdjustmentCode field if non-nil, zero value otherwise.

### GetAdjustmentCodeOk

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) GetAdjustmentCodeOk() (*string, bool)`

GetAdjustmentCodeOk returns a tuple with the AdjustmentCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdjustmentCode

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) SetAdjustmentCode(v string)`

SetAdjustmentCode sets AdjustmentCode field to given value.

### HasAdjustmentCode

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) HasAdjustmentCode() bool`

HasAdjustmentCode returns a boolean if a field has been set.

### GetPartId

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetPartNumber

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) GetPartNumber() string`

GetPartNumber returns the PartNumber field if non-nil, zero value otherwise.

### GetPartNumberOk

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) GetPartNumberOk() (*string, bool)`

GetPartNumberOk returns a tuple with the PartNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumber

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) SetPartNumber(v string)`

SetPartNumber sets PartNumber field to given value.

### HasPartNumber

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) HasPartNumber() bool`

HasPartNumber returns a boolean if a field has been set.

### GetRevision

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) GetRevision() string`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) GetRevisionOk() (*string, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) SetRevision(v string)`

SetRevision sets Revision field to given value.

### HasRevision

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) HasRevision() bool`

HasRevision returns a boolean if a field has been set.

### GetPartNumberRevision

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) GetPartNumberRevision() string`

GetPartNumberRevision returns the PartNumberRevision field if non-nil, zero value otherwise.

### GetPartNumberRevisionOk

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) GetPartNumberRevisionOk() (*string, bool)`

GetPartNumberRevisionOk returns a tuple with the PartNumberRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumberRevision

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) SetPartNumberRevision(v string)`

SetPartNumberRevision sets PartNumberRevision field to given value.

### HasPartNumberRevision

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) HasPartNumberRevision() bool`

HasPartNumberRevision returns a boolean if a field has been set.

### GetPartOperationId

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) GetPartOperationId() string`

GetPartOperationId returns the PartOperationId field if non-nil, zero value otherwise.

### GetPartOperationIdOk

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) GetPartOperationIdOk() (*string, bool)`

GetPartOperationIdOk returns a tuple with the PartOperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartOperationId

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) SetPartOperationId(v string)`

SetPartOperationId sets PartOperationId field to given value.

### HasPartOperationId

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) HasPartOperationId() bool`

HasPartOperationId returns a boolean if a field has been set.

### GetOperationCode

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) GetOperationCode() string`

GetOperationCode returns the OperationCode field if non-nil, zero value otherwise.

### GetOperationCodeOk

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) GetOperationCodeOk() (*string, bool)`

GetOperationCodeOk returns a tuple with the OperationCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationCode

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) SetOperationCode(v string)`

SetOperationCode sets OperationCode field to given value.

### HasOperationCode

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) HasOperationCode() bool`

HasOperationCode returns a boolean if a field has been set.

### GetOperationNumber

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) GetOperationNumber() int32`

GetOperationNumber returns the OperationNumber field if non-nil, zero value otherwise.

### GetOperationNumberOk

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) GetOperationNumberOk() (*int32, bool)`

GetOperationNumberOk returns a tuple with the OperationNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationNumber

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) SetOperationNumber(v int32)`

SetOperationNumber sets OperationNumber field to given value.

### HasOperationNumber

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) HasOperationNumber() bool`

HasOperationNumber returns a boolean if a field has been set.

### GetLocation

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) GetLocation() string`

GetLocation returns the Location field if non-nil, zero value otherwise.

### GetLocationOk

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) GetLocationOk() (*string, bool)`

GetLocationOk returns a tuple with the Location field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocation

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) SetLocation(v string)`

SetLocation sets Location field to given value.

### HasLocation

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) HasLocation() bool`

HasLocation returns a boolean if a field has been set.

### GetLocationId

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) GetLocationId() string`

GetLocationId returns the LocationId field if non-nil, zero value otherwise.

### GetLocationIdOk

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) GetLocationIdOk() (*string, bool)`

GetLocationIdOk returns a tuple with the LocationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocationId

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) SetLocationId(v string)`

SetLocationId sets LocationId field to given value.

### HasLocationId

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) HasLocationId() bool`

HasLocationId returns a boolean if a field has been set.

### GetMovedFromLocation

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) GetMovedFromLocation() string`

GetMovedFromLocation returns the MovedFromLocation field if non-nil, zero value otherwise.

### GetMovedFromLocationOk

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) GetMovedFromLocationOk() (*string, bool)`

GetMovedFromLocationOk returns a tuple with the MovedFromLocation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMovedFromLocation

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) SetMovedFromLocation(v string)`

SetMovedFromLocation sets MovedFromLocation field to given value.

### HasMovedFromLocation

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) HasMovedFromLocation() bool`

HasMovedFromLocation returns a boolean if a field has been set.

### GetMovedFromLocationId

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) GetMovedFromLocationId() string`

GetMovedFromLocationId returns the MovedFromLocationId field if non-nil, zero value otherwise.

### GetMovedFromLocationIdOk

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) GetMovedFromLocationIdOk() (*string, bool)`

GetMovedFromLocationIdOk returns a tuple with the MovedFromLocationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMovedFromLocationId

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) SetMovedFromLocationId(v string)`

SetMovedFromLocationId sets MovedFromLocationId field to given value.

### HasMovedFromLocationId

`func (o *InventoryOperationsManagementApiListContainerLocationMovesItem) HasMovedFromLocationId() bool`

HasMovedFromLocationId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


