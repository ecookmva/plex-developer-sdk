# ProductionOperationsManagementApiListProductionLineWorkcentersItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**WorkcenterId** | Pointer to **string** | The unique identifier assigned to the workcenter. | [optional] 
**WorkcenterCode** | Pointer to **string** | 50 characters max. A short name associated to the workcenterID, and a unique code to reference the workcenter. This code shows up throughout the system, primarily on the Control Panel. | [optional] 
**Name** | Pointer to **string** | 100 characters max. The full name associated to the workcenterID that is a more descriptive name for the Workcenter. Depending on your settings, this name can also display on the control panel and sequence board. | [optional] 
**WorkcenterType** | Pointer to **string** | 50 characters max. Setup table &amp;quot;Workcenter Type&amp;quot; (part.dbo.workcenter_type). Grouping of similar workcenters. The Workcenter Type influences how the workcenter behaves, but is also available as a filter in different places (control panel, production status, Workcenter log, sequence board). | [optional] 
**WorkcenterGroup** | Pointer to **string** | 50 characters max. Setup table &amp;quot;Workcenter Group&amp;quot; (part.dbo.workcenter_group). An optional grouping of similar workcenters. This is helpful when there are many workcenters that can be chosen from the Control Panel. If the Workcenter Group setting is on, the Control Panel will display the Workcenter Groups then once a group is chosen, the list of workcenters only in that group will display. | [optional] 
**BuildingId** | Pointer to **string** | The unique identifier of the building the workcenter is located in. | [optional] 
**BuildingCode** | Pointer to **string** | 50 characters max. A short name for the building. | [optional] 
**ProductionLineStatusDriver** | Pointer to **bool** | True, if the workcenter is identified as the bottleneck in the production line. | [optional] 
**AddBy** | Pointer to **string** | 101 characters max. The name of the plex user who added the production line workcenter. | [optional] 
**AddDateTime** | Pointer to **time.Time** | The date and time the production line workcenter was added. | [optional] 

## Methods

### NewProductionOperationsManagementApiListProductionLineWorkcentersItem

`func NewProductionOperationsManagementApiListProductionLineWorkcentersItem() *ProductionOperationsManagementApiListProductionLineWorkcentersItem`

NewProductionOperationsManagementApiListProductionLineWorkcentersItem instantiates a new ProductionOperationsManagementApiListProductionLineWorkcentersItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductionOperationsManagementApiListProductionLineWorkcentersItemWithDefaults

`func NewProductionOperationsManagementApiListProductionLineWorkcentersItemWithDefaults() *ProductionOperationsManagementApiListProductionLineWorkcentersItem`

NewProductionOperationsManagementApiListProductionLineWorkcentersItemWithDefaults instantiates a new ProductionOperationsManagementApiListProductionLineWorkcentersItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetWorkcenterId

`func (o *ProductionOperationsManagementApiListProductionLineWorkcentersItem) GetWorkcenterId() string`

GetWorkcenterId returns the WorkcenterId field if non-nil, zero value otherwise.

### GetWorkcenterIdOk

`func (o *ProductionOperationsManagementApiListProductionLineWorkcentersItem) GetWorkcenterIdOk() (*string, bool)`

GetWorkcenterIdOk returns a tuple with the WorkcenterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkcenterId

`func (o *ProductionOperationsManagementApiListProductionLineWorkcentersItem) SetWorkcenterId(v string)`

SetWorkcenterId sets WorkcenterId field to given value.

### HasWorkcenterId

`func (o *ProductionOperationsManagementApiListProductionLineWorkcentersItem) HasWorkcenterId() bool`

HasWorkcenterId returns a boolean if a field has been set.

### GetWorkcenterCode

`func (o *ProductionOperationsManagementApiListProductionLineWorkcentersItem) GetWorkcenterCode() string`

GetWorkcenterCode returns the WorkcenterCode field if non-nil, zero value otherwise.

### GetWorkcenterCodeOk

`func (o *ProductionOperationsManagementApiListProductionLineWorkcentersItem) GetWorkcenterCodeOk() (*string, bool)`

GetWorkcenterCodeOk returns a tuple with the WorkcenterCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkcenterCode

`func (o *ProductionOperationsManagementApiListProductionLineWorkcentersItem) SetWorkcenterCode(v string)`

SetWorkcenterCode sets WorkcenterCode field to given value.

### HasWorkcenterCode

`func (o *ProductionOperationsManagementApiListProductionLineWorkcentersItem) HasWorkcenterCode() bool`

HasWorkcenterCode returns a boolean if a field has been set.

### GetName

`func (o *ProductionOperationsManagementApiListProductionLineWorkcentersItem) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ProductionOperationsManagementApiListProductionLineWorkcentersItem) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ProductionOperationsManagementApiListProductionLineWorkcentersItem) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ProductionOperationsManagementApiListProductionLineWorkcentersItem) HasName() bool`

HasName returns a boolean if a field has been set.

### GetWorkcenterType

`func (o *ProductionOperationsManagementApiListProductionLineWorkcentersItem) GetWorkcenterType() string`

GetWorkcenterType returns the WorkcenterType field if non-nil, zero value otherwise.

### GetWorkcenterTypeOk

`func (o *ProductionOperationsManagementApiListProductionLineWorkcentersItem) GetWorkcenterTypeOk() (*string, bool)`

GetWorkcenterTypeOk returns a tuple with the WorkcenterType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkcenterType

`func (o *ProductionOperationsManagementApiListProductionLineWorkcentersItem) SetWorkcenterType(v string)`

SetWorkcenterType sets WorkcenterType field to given value.

### HasWorkcenterType

`func (o *ProductionOperationsManagementApiListProductionLineWorkcentersItem) HasWorkcenterType() bool`

HasWorkcenterType returns a boolean if a field has been set.

### GetWorkcenterGroup

`func (o *ProductionOperationsManagementApiListProductionLineWorkcentersItem) GetWorkcenterGroup() string`

GetWorkcenterGroup returns the WorkcenterGroup field if non-nil, zero value otherwise.

### GetWorkcenterGroupOk

`func (o *ProductionOperationsManagementApiListProductionLineWorkcentersItem) GetWorkcenterGroupOk() (*string, bool)`

GetWorkcenterGroupOk returns a tuple with the WorkcenterGroup field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkcenterGroup

`func (o *ProductionOperationsManagementApiListProductionLineWorkcentersItem) SetWorkcenterGroup(v string)`

SetWorkcenterGroup sets WorkcenterGroup field to given value.

### HasWorkcenterGroup

`func (o *ProductionOperationsManagementApiListProductionLineWorkcentersItem) HasWorkcenterGroup() bool`

HasWorkcenterGroup returns a boolean if a field has been set.

### GetBuildingId

`func (o *ProductionOperationsManagementApiListProductionLineWorkcentersItem) GetBuildingId() string`

GetBuildingId returns the BuildingId field if non-nil, zero value otherwise.

### GetBuildingIdOk

`func (o *ProductionOperationsManagementApiListProductionLineWorkcentersItem) GetBuildingIdOk() (*string, bool)`

GetBuildingIdOk returns a tuple with the BuildingId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildingId

`func (o *ProductionOperationsManagementApiListProductionLineWorkcentersItem) SetBuildingId(v string)`

SetBuildingId sets BuildingId field to given value.

### HasBuildingId

`func (o *ProductionOperationsManagementApiListProductionLineWorkcentersItem) HasBuildingId() bool`

HasBuildingId returns a boolean if a field has been set.

### GetBuildingCode

`func (o *ProductionOperationsManagementApiListProductionLineWorkcentersItem) GetBuildingCode() string`

GetBuildingCode returns the BuildingCode field if non-nil, zero value otherwise.

### GetBuildingCodeOk

`func (o *ProductionOperationsManagementApiListProductionLineWorkcentersItem) GetBuildingCodeOk() (*string, bool)`

GetBuildingCodeOk returns a tuple with the BuildingCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildingCode

`func (o *ProductionOperationsManagementApiListProductionLineWorkcentersItem) SetBuildingCode(v string)`

SetBuildingCode sets BuildingCode field to given value.

### HasBuildingCode

`func (o *ProductionOperationsManagementApiListProductionLineWorkcentersItem) HasBuildingCode() bool`

HasBuildingCode returns a boolean if a field has been set.

### GetProductionLineStatusDriver

`func (o *ProductionOperationsManagementApiListProductionLineWorkcentersItem) GetProductionLineStatusDriver() bool`

GetProductionLineStatusDriver returns the ProductionLineStatusDriver field if non-nil, zero value otherwise.

### GetProductionLineStatusDriverOk

`func (o *ProductionOperationsManagementApiListProductionLineWorkcentersItem) GetProductionLineStatusDriverOk() (*bool, bool)`

GetProductionLineStatusDriverOk returns a tuple with the ProductionLineStatusDriver field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductionLineStatusDriver

`func (o *ProductionOperationsManagementApiListProductionLineWorkcentersItem) SetProductionLineStatusDriver(v bool)`

SetProductionLineStatusDriver sets ProductionLineStatusDriver field to given value.

### HasProductionLineStatusDriver

`func (o *ProductionOperationsManagementApiListProductionLineWorkcentersItem) HasProductionLineStatusDriver() bool`

HasProductionLineStatusDriver returns a boolean if a field has been set.

### GetAddBy

`func (o *ProductionOperationsManagementApiListProductionLineWorkcentersItem) GetAddBy() string`

GetAddBy returns the AddBy field if non-nil, zero value otherwise.

### GetAddByOk

`func (o *ProductionOperationsManagementApiListProductionLineWorkcentersItem) GetAddByOk() (*string, bool)`

GetAddByOk returns a tuple with the AddBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddBy

`func (o *ProductionOperationsManagementApiListProductionLineWorkcentersItem) SetAddBy(v string)`

SetAddBy sets AddBy field to given value.

### HasAddBy

`func (o *ProductionOperationsManagementApiListProductionLineWorkcentersItem) HasAddBy() bool`

HasAddBy returns a boolean if a field has been set.

### GetAddDateTime

`func (o *ProductionOperationsManagementApiListProductionLineWorkcentersItem) GetAddDateTime() time.Time`

GetAddDateTime returns the AddDateTime field if non-nil, zero value otherwise.

### GetAddDateTimeOk

`func (o *ProductionOperationsManagementApiListProductionLineWorkcentersItem) GetAddDateTimeOk() (*time.Time, bool)`

GetAddDateTimeOk returns a tuple with the AddDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddDateTime

`func (o *ProductionOperationsManagementApiListProductionLineWorkcentersItem) SetAddDateTime(v time.Time)`

SetAddDateTime sets AddDateTime field to given value.

### HasAddDateTime

`func (o *ProductionOperationsManagementApiListProductionLineWorkcentersItem) HasAddDateTime() bool`

HasAddDateTime returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


