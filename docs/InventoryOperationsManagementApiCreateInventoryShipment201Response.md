# InventoryOperationsManagementApiCreateInventoryShipment201Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. The Inventory Shipment Resource ID. | [optional] 
**ExternalShipmentCode** | Pointer to **string** | 50 character max. The external inventory shipment code. This code is not provided by Plex and is distinct from the shipment ID. | [optional] 
**ShipmentStatus** | Pointer to **string** | The inventory shipment status. Valid statuses include &amp;quot;Unstaged&amp;quot;, &amp;quot;Staged&amp;quot;, and &amp;quot;Shipped&amp;quot;. | [optional] 
**Containers** | Pointer to [**[]ContainersItem**](ContainersItem.md) | The containers associated with the inventory shipment. | [optional] 
**CreatedById** | Pointer to **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. The tenant ID used to create this inventory shipment. | [optional] 
**CreatedDate** | Pointer to **time.Time** | Date/Time Format YYYY-MM-DDThh:mm:ss.fffffffZ The date and time when an inventory shipment was made. See &amp;quot;Dates and Times&amp;quot; in the Get Started section of the Plex Developer Portal (APIs &amp;gt; Get Started). | [optional] 

## Methods

### NewInventoryOperationsManagementApiCreateInventoryShipment201Response

`func NewInventoryOperationsManagementApiCreateInventoryShipment201Response() *InventoryOperationsManagementApiCreateInventoryShipment201Response`

NewInventoryOperationsManagementApiCreateInventoryShipment201Response instantiates a new InventoryOperationsManagementApiCreateInventoryShipment201Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInventoryOperationsManagementApiCreateInventoryShipment201ResponseWithDefaults

`func NewInventoryOperationsManagementApiCreateInventoryShipment201ResponseWithDefaults() *InventoryOperationsManagementApiCreateInventoryShipment201Response`

NewInventoryOperationsManagementApiCreateInventoryShipment201ResponseWithDefaults instantiates a new InventoryOperationsManagementApiCreateInventoryShipment201Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *InventoryOperationsManagementApiCreateInventoryShipment201Response) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *InventoryOperationsManagementApiCreateInventoryShipment201Response) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *InventoryOperationsManagementApiCreateInventoryShipment201Response) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *InventoryOperationsManagementApiCreateInventoryShipment201Response) HasId() bool`

HasId returns a boolean if a field has been set.

### GetExternalShipmentCode

`func (o *InventoryOperationsManagementApiCreateInventoryShipment201Response) GetExternalShipmentCode() string`

GetExternalShipmentCode returns the ExternalShipmentCode field if non-nil, zero value otherwise.

### GetExternalShipmentCodeOk

`func (o *InventoryOperationsManagementApiCreateInventoryShipment201Response) GetExternalShipmentCodeOk() (*string, bool)`

GetExternalShipmentCodeOk returns a tuple with the ExternalShipmentCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalShipmentCode

`func (o *InventoryOperationsManagementApiCreateInventoryShipment201Response) SetExternalShipmentCode(v string)`

SetExternalShipmentCode sets ExternalShipmentCode field to given value.

### HasExternalShipmentCode

`func (o *InventoryOperationsManagementApiCreateInventoryShipment201Response) HasExternalShipmentCode() bool`

HasExternalShipmentCode returns a boolean if a field has been set.

### GetShipmentStatus

`func (o *InventoryOperationsManagementApiCreateInventoryShipment201Response) GetShipmentStatus() string`

GetShipmentStatus returns the ShipmentStatus field if non-nil, zero value otherwise.

### GetShipmentStatusOk

`func (o *InventoryOperationsManagementApiCreateInventoryShipment201Response) GetShipmentStatusOk() (*string, bool)`

GetShipmentStatusOk returns a tuple with the ShipmentStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipmentStatus

`func (o *InventoryOperationsManagementApiCreateInventoryShipment201Response) SetShipmentStatus(v string)`

SetShipmentStatus sets ShipmentStatus field to given value.

### HasShipmentStatus

`func (o *InventoryOperationsManagementApiCreateInventoryShipment201Response) HasShipmentStatus() bool`

HasShipmentStatus returns a boolean if a field has been set.

### GetContainers

`func (o *InventoryOperationsManagementApiCreateInventoryShipment201Response) GetContainers() []ContainersItem`

GetContainers returns the Containers field if non-nil, zero value otherwise.

### GetContainersOk

`func (o *InventoryOperationsManagementApiCreateInventoryShipment201Response) GetContainersOk() (*[]ContainersItem, bool)`

GetContainersOk returns a tuple with the Containers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContainers

`func (o *InventoryOperationsManagementApiCreateInventoryShipment201Response) SetContainers(v []ContainersItem)`

SetContainers sets Containers field to given value.

### HasContainers

`func (o *InventoryOperationsManagementApiCreateInventoryShipment201Response) HasContainers() bool`

HasContainers returns a boolean if a field has been set.

### GetCreatedById

`func (o *InventoryOperationsManagementApiCreateInventoryShipment201Response) GetCreatedById() string`

GetCreatedById returns the CreatedById field if non-nil, zero value otherwise.

### GetCreatedByIdOk

`func (o *InventoryOperationsManagementApiCreateInventoryShipment201Response) GetCreatedByIdOk() (*string, bool)`

GetCreatedByIdOk returns a tuple with the CreatedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedById

`func (o *InventoryOperationsManagementApiCreateInventoryShipment201Response) SetCreatedById(v string)`

SetCreatedById sets CreatedById field to given value.

### HasCreatedById

`func (o *InventoryOperationsManagementApiCreateInventoryShipment201Response) HasCreatedById() bool`

HasCreatedById returns a boolean if a field has been set.

### GetCreatedDate

`func (o *InventoryOperationsManagementApiCreateInventoryShipment201Response) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *InventoryOperationsManagementApiCreateInventoryShipment201Response) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *InventoryOperationsManagementApiCreateInventoryShipment201Response) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *InventoryOperationsManagementApiCreateInventoryShipment201Response) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


