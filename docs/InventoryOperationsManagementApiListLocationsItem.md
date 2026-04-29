# InventoryOperationsManagementApiListLocationsItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**LocationId** | Pointer to **string** | The Location ID. | [optional] 
**LocationCode** | Pointer to **string** | The Location Code. | [optional] 
**BuildingName** | Pointer to **string** | The Building Name. | [optional] 
**BuildingCode** | Pointer to **string** | The Building Code. | [optional] 
**LocationType** | Pointer to **string** | The Location Type. | [optional] 
**InventoryLocation** | Pointer to **bool** | Boolean flag to indicate whether the Location type is of Inventory or not. | [optional] 
**SupplyLocation** | Pointer to **bool** | Boolean flag to indicate whether the Location type is of Supply Location or not. | [optional] 
**TankSilo** | Pointer to **bool** | Boolean flag to indicate whether the workcenter is a Tank/Silo. | [optional] 

## Methods

### NewInventoryOperationsManagementApiListLocationsItem

`func NewInventoryOperationsManagementApiListLocationsItem() *InventoryOperationsManagementApiListLocationsItem`

NewInventoryOperationsManagementApiListLocationsItem instantiates a new InventoryOperationsManagementApiListLocationsItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInventoryOperationsManagementApiListLocationsItemWithDefaults

`func NewInventoryOperationsManagementApiListLocationsItemWithDefaults() *InventoryOperationsManagementApiListLocationsItem`

NewInventoryOperationsManagementApiListLocationsItemWithDefaults instantiates a new InventoryOperationsManagementApiListLocationsItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLocationId

`func (o *InventoryOperationsManagementApiListLocationsItem) GetLocationId() string`

GetLocationId returns the LocationId field if non-nil, zero value otherwise.

### GetLocationIdOk

`func (o *InventoryOperationsManagementApiListLocationsItem) GetLocationIdOk() (*string, bool)`

GetLocationIdOk returns a tuple with the LocationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocationId

`func (o *InventoryOperationsManagementApiListLocationsItem) SetLocationId(v string)`

SetLocationId sets LocationId field to given value.

### HasLocationId

`func (o *InventoryOperationsManagementApiListLocationsItem) HasLocationId() bool`

HasLocationId returns a boolean if a field has been set.

### GetLocationCode

`func (o *InventoryOperationsManagementApiListLocationsItem) GetLocationCode() string`

GetLocationCode returns the LocationCode field if non-nil, zero value otherwise.

### GetLocationCodeOk

`func (o *InventoryOperationsManagementApiListLocationsItem) GetLocationCodeOk() (*string, bool)`

GetLocationCodeOk returns a tuple with the LocationCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocationCode

`func (o *InventoryOperationsManagementApiListLocationsItem) SetLocationCode(v string)`

SetLocationCode sets LocationCode field to given value.

### HasLocationCode

`func (o *InventoryOperationsManagementApiListLocationsItem) HasLocationCode() bool`

HasLocationCode returns a boolean if a field has been set.

### GetBuildingName

`func (o *InventoryOperationsManagementApiListLocationsItem) GetBuildingName() string`

GetBuildingName returns the BuildingName field if non-nil, zero value otherwise.

### GetBuildingNameOk

`func (o *InventoryOperationsManagementApiListLocationsItem) GetBuildingNameOk() (*string, bool)`

GetBuildingNameOk returns a tuple with the BuildingName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildingName

`func (o *InventoryOperationsManagementApiListLocationsItem) SetBuildingName(v string)`

SetBuildingName sets BuildingName field to given value.

### HasBuildingName

`func (o *InventoryOperationsManagementApiListLocationsItem) HasBuildingName() bool`

HasBuildingName returns a boolean if a field has been set.

### GetBuildingCode

`func (o *InventoryOperationsManagementApiListLocationsItem) GetBuildingCode() string`

GetBuildingCode returns the BuildingCode field if non-nil, zero value otherwise.

### GetBuildingCodeOk

`func (o *InventoryOperationsManagementApiListLocationsItem) GetBuildingCodeOk() (*string, bool)`

GetBuildingCodeOk returns a tuple with the BuildingCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildingCode

`func (o *InventoryOperationsManagementApiListLocationsItem) SetBuildingCode(v string)`

SetBuildingCode sets BuildingCode field to given value.

### HasBuildingCode

`func (o *InventoryOperationsManagementApiListLocationsItem) HasBuildingCode() bool`

HasBuildingCode returns a boolean if a field has been set.

### GetLocationType

`func (o *InventoryOperationsManagementApiListLocationsItem) GetLocationType() string`

GetLocationType returns the LocationType field if non-nil, zero value otherwise.

### GetLocationTypeOk

`func (o *InventoryOperationsManagementApiListLocationsItem) GetLocationTypeOk() (*string, bool)`

GetLocationTypeOk returns a tuple with the LocationType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocationType

`func (o *InventoryOperationsManagementApiListLocationsItem) SetLocationType(v string)`

SetLocationType sets LocationType field to given value.

### HasLocationType

`func (o *InventoryOperationsManagementApiListLocationsItem) HasLocationType() bool`

HasLocationType returns a boolean if a field has been set.

### GetInventoryLocation

`func (o *InventoryOperationsManagementApiListLocationsItem) GetInventoryLocation() bool`

GetInventoryLocation returns the InventoryLocation field if non-nil, zero value otherwise.

### GetInventoryLocationOk

`func (o *InventoryOperationsManagementApiListLocationsItem) GetInventoryLocationOk() (*bool, bool)`

GetInventoryLocationOk returns a tuple with the InventoryLocation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInventoryLocation

`func (o *InventoryOperationsManagementApiListLocationsItem) SetInventoryLocation(v bool)`

SetInventoryLocation sets InventoryLocation field to given value.

### HasInventoryLocation

`func (o *InventoryOperationsManagementApiListLocationsItem) HasInventoryLocation() bool`

HasInventoryLocation returns a boolean if a field has been set.

### GetSupplyLocation

`func (o *InventoryOperationsManagementApiListLocationsItem) GetSupplyLocation() bool`

GetSupplyLocation returns the SupplyLocation field if non-nil, zero value otherwise.

### GetSupplyLocationOk

`func (o *InventoryOperationsManagementApiListLocationsItem) GetSupplyLocationOk() (*bool, bool)`

GetSupplyLocationOk returns a tuple with the SupplyLocation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplyLocation

`func (o *InventoryOperationsManagementApiListLocationsItem) SetSupplyLocation(v bool)`

SetSupplyLocation sets SupplyLocation field to given value.

### HasSupplyLocation

`func (o *InventoryOperationsManagementApiListLocationsItem) HasSupplyLocation() bool`

HasSupplyLocation returns a boolean if a field has been set.

### GetTankSilo

`func (o *InventoryOperationsManagementApiListLocationsItem) GetTankSilo() bool`

GetTankSilo returns the TankSilo field if non-nil, zero value otherwise.

### GetTankSiloOk

`func (o *InventoryOperationsManagementApiListLocationsItem) GetTankSiloOk() (*bool, bool)`

GetTankSiloOk returns a tuple with the TankSilo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTankSilo

`func (o *InventoryOperationsManagementApiListLocationsItem) SetTankSilo(v bool)`

SetTankSilo sets TankSilo field to given value.

### HasTankSilo

`func (o *InventoryOperationsManagementApiListLocationsItem) HasTankSilo() bool`

HasTankSilo returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


