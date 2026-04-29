# InventoryOperationsManagementApiUnshipInventory202Response

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

### NewInventoryOperationsManagementApiUnshipInventory202Response

`func NewInventoryOperationsManagementApiUnshipInventory202Response() *InventoryOperationsManagementApiUnshipInventory202Response`

NewInventoryOperationsManagementApiUnshipInventory202Response instantiates a new InventoryOperationsManagementApiUnshipInventory202Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInventoryOperationsManagementApiUnshipInventory202ResponseWithDefaults

`func NewInventoryOperationsManagementApiUnshipInventory202ResponseWithDefaults() *InventoryOperationsManagementApiUnshipInventory202Response`

NewInventoryOperationsManagementApiUnshipInventory202ResponseWithDefaults instantiates a new InventoryOperationsManagementApiUnshipInventory202Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *InventoryOperationsManagementApiUnshipInventory202Response) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *InventoryOperationsManagementApiUnshipInventory202Response) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *InventoryOperationsManagementApiUnshipInventory202Response) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *InventoryOperationsManagementApiUnshipInventory202Response) HasId() bool`

HasId returns a boolean if a field has been set.

### GetExternalShipmentCode

`func (o *InventoryOperationsManagementApiUnshipInventory202Response) GetExternalShipmentCode() string`

GetExternalShipmentCode returns the ExternalShipmentCode field if non-nil, zero value otherwise.

### GetExternalShipmentCodeOk

`func (o *InventoryOperationsManagementApiUnshipInventory202Response) GetExternalShipmentCodeOk() (*string, bool)`

GetExternalShipmentCodeOk returns a tuple with the ExternalShipmentCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalShipmentCode

`func (o *InventoryOperationsManagementApiUnshipInventory202Response) SetExternalShipmentCode(v string)`

SetExternalShipmentCode sets ExternalShipmentCode field to given value.

### HasExternalShipmentCode

`func (o *InventoryOperationsManagementApiUnshipInventory202Response) HasExternalShipmentCode() bool`

HasExternalShipmentCode returns a boolean if a field has been set.

### GetShipmentStatus

`func (o *InventoryOperationsManagementApiUnshipInventory202Response) GetShipmentStatus() string`

GetShipmentStatus returns the ShipmentStatus field if non-nil, zero value otherwise.

### GetShipmentStatusOk

`func (o *InventoryOperationsManagementApiUnshipInventory202Response) GetShipmentStatusOk() (*string, bool)`

GetShipmentStatusOk returns a tuple with the ShipmentStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipmentStatus

`func (o *InventoryOperationsManagementApiUnshipInventory202Response) SetShipmentStatus(v string)`

SetShipmentStatus sets ShipmentStatus field to given value.

### HasShipmentStatus

`func (o *InventoryOperationsManagementApiUnshipInventory202Response) HasShipmentStatus() bool`

HasShipmentStatus returns a boolean if a field has been set.

### GetContainers

`func (o *InventoryOperationsManagementApiUnshipInventory202Response) GetContainers() []ContainersItem`

GetContainers returns the Containers field if non-nil, zero value otherwise.

### GetContainersOk

`func (o *InventoryOperationsManagementApiUnshipInventory202Response) GetContainersOk() (*[]ContainersItem, bool)`

GetContainersOk returns a tuple with the Containers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContainers

`func (o *InventoryOperationsManagementApiUnshipInventory202Response) SetContainers(v []ContainersItem)`

SetContainers sets Containers field to given value.

### HasContainers

`func (o *InventoryOperationsManagementApiUnshipInventory202Response) HasContainers() bool`

HasContainers returns a boolean if a field has been set.

### GetCreatedById

`func (o *InventoryOperationsManagementApiUnshipInventory202Response) GetCreatedById() string`

GetCreatedById returns the CreatedById field if non-nil, zero value otherwise.

### GetCreatedByIdOk

`func (o *InventoryOperationsManagementApiUnshipInventory202Response) GetCreatedByIdOk() (*string, bool)`

GetCreatedByIdOk returns a tuple with the CreatedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedById

`func (o *InventoryOperationsManagementApiUnshipInventory202Response) SetCreatedById(v string)`

SetCreatedById sets CreatedById field to given value.

### HasCreatedById

`func (o *InventoryOperationsManagementApiUnshipInventory202Response) HasCreatedById() bool`

HasCreatedById returns a boolean if a field has been set.

### GetCreatedDate

`func (o *InventoryOperationsManagementApiUnshipInventory202Response) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *InventoryOperationsManagementApiUnshipInventory202Response) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *InventoryOperationsManagementApiUnshipInventory202Response) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *InventoryOperationsManagementApiUnshipInventory202Response) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


