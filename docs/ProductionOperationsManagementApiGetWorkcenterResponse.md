# ProductionOperationsManagementApiGetWorkcenterResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**WorkcenterId** | Pointer to **string** | The UUID assigned to the workcenter. | [optional] 
**WorkcenterCode** | Pointer to **string** | 50 characters max. A short name associated to the workcenterID, and a unique code to reference the workcenter. This code shows up throughout the system, primarily on the Control Panel. | [optional] 
**Name** | Pointer to **string** | 100 characters max. The full name associated to the workcenterID that is a more descriptive name for the Workcenter. Depending on your settings, this name can also display on the control panel and sequence board. | [optional] 
**WorkcenterType** | Pointer to **string** | 50 characters max. Setup table &amp;quot;Workcenter Type&amp;quot; (part.dbo.workcenter_type). Grouping of similar workcenters. The Workcenter Type influences how the workcenter behaves, but is also available as a filter in different places (control panel, production status, Workcenter log, sequence board). | [optional] 
**WorkcenterGroup** | Pointer to **string** | 50 characters max. Setup table &amp;quot;Workcenter Group&amp;quot; (part.dbo.workcenter_group). An optional grouping of similar workcenters. This is helpful when there are many workcenters that can be chosen from the Control Panel. If the Workcenter Group setting is on, the Control Panel will display the Workcenter Groups then once a group is chosen, the list of workcenters only in that group will display. | [optional] 
**BuildingId** | Pointer to **string** | UUID of the building the workcenter is located in. | [optional] 
**BuildingCode** | Pointer to **string** | 50 characters max. A short name for the building. | [optional] 
**TankSilo** | Pointer to **bool** | Boolean flag to indicate whether the workcenter is a Tank/Silo. | [optional] 
**ProductionLineId** | Pointer to **string** | The unique identifier for the production line associated with the workcenter. | [optional] 
**IpAddress** | Pointer to **string** | The IP Address of the workcenter. | [optional] 
**PlcName** | Pointer to **string** | The PLC Name of the workcenter. | [optional] 

## Methods

### NewProductionOperationsManagementApiGetWorkcenterResponse

`func NewProductionOperationsManagementApiGetWorkcenterResponse() *ProductionOperationsManagementApiGetWorkcenterResponse`

NewProductionOperationsManagementApiGetWorkcenterResponse instantiates a new ProductionOperationsManagementApiGetWorkcenterResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductionOperationsManagementApiGetWorkcenterResponseWithDefaults

`func NewProductionOperationsManagementApiGetWorkcenterResponseWithDefaults() *ProductionOperationsManagementApiGetWorkcenterResponse`

NewProductionOperationsManagementApiGetWorkcenterResponseWithDefaults instantiates a new ProductionOperationsManagementApiGetWorkcenterResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetWorkcenterId

`func (o *ProductionOperationsManagementApiGetWorkcenterResponse) GetWorkcenterId() string`

GetWorkcenterId returns the WorkcenterId field if non-nil, zero value otherwise.

### GetWorkcenterIdOk

`func (o *ProductionOperationsManagementApiGetWorkcenterResponse) GetWorkcenterIdOk() (*string, bool)`

GetWorkcenterIdOk returns a tuple with the WorkcenterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkcenterId

`func (o *ProductionOperationsManagementApiGetWorkcenterResponse) SetWorkcenterId(v string)`

SetWorkcenterId sets WorkcenterId field to given value.

### HasWorkcenterId

`func (o *ProductionOperationsManagementApiGetWorkcenterResponse) HasWorkcenterId() bool`

HasWorkcenterId returns a boolean if a field has been set.

### GetWorkcenterCode

`func (o *ProductionOperationsManagementApiGetWorkcenterResponse) GetWorkcenterCode() string`

GetWorkcenterCode returns the WorkcenterCode field if non-nil, zero value otherwise.

### GetWorkcenterCodeOk

`func (o *ProductionOperationsManagementApiGetWorkcenterResponse) GetWorkcenterCodeOk() (*string, bool)`

GetWorkcenterCodeOk returns a tuple with the WorkcenterCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkcenterCode

`func (o *ProductionOperationsManagementApiGetWorkcenterResponse) SetWorkcenterCode(v string)`

SetWorkcenterCode sets WorkcenterCode field to given value.

### HasWorkcenterCode

`func (o *ProductionOperationsManagementApiGetWorkcenterResponse) HasWorkcenterCode() bool`

HasWorkcenterCode returns a boolean if a field has been set.

### GetName

`func (o *ProductionOperationsManagementApiGetWorkcenterResponse) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ProductionOperationsManagementApiGetWorkcenterResponse) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ProductionOperationsManagementApiGetWorkcenterResponse) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ProductionOperationsManagementApiGetWorkcenterResponse) HasName() bool`

HasName returns a boolean if a field has been set.

### GetWorkcenterType

`func (o *ProductionOperationsManagementApiGetWorkcenterResponse) GetWorkcenterType() string`

GetWorkcenterType returns the WorkcenterType field if non-nil, zero value otherwise.

### GetWorkcenterTypeOk

`func (o *ProductionOperationsManagementApiGetWorkcenterResponse) GetWorkcenterTypeOk() (*string, bool)`

GetWorkcenterTypeOk returns a tuple with the WorkcenterType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkcenterType

`func (o *ProductionOperationsManagementApiGetWorkcenterResponse) SetWorkcenterType(v string)`

SetWorkcenterType sets WorkcenterType field to given value.

### HasWorkcenterType

`func (o *ProductionOperationsManagementApiGetWorkcenterResponse) HasWorkcenterType() bool`

HasWorkcenterType returns a boolean if a field has been set.

### GetWorkcenterGroup

`func (o *ProductionOperationsManagementApiGetWorkcenterResponse) GetWorkcenterGroup() string`

GetWorkcenterGroup returns the WorkcenterGroup field if non-nil, zero value otherwise.

### GetWorkcenterGroupOk

`func (o *ProductionOperationsManagementApiGetWorkcenterResponse) GetWorkcenterGroupOk() (*string, bool)`

GetWorkcenterGroupOk returns a tuple with the WorkcenterGroup field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkcenterGroup

`func (o *ProductionOperationsManagementApiGetWorkcenterResponse) SetWorkcenterGroup(v string)`

SetWorkcenterGroup sets WorkcenterGroup field to given value.

### HasWorkcenterGroup

`func (o *ProductionOperationsManagementApiGetWorkcenterResponse) HasWorkcenterGroup() bool`

HasWorkcenterGroup returns a boolean if a field has been set.

### GetBuildingId

`func (o *ProductionOperationsManagementApiGetWorkcenterResponse) GetBuildingId() string`

GetBuildingId returns the BuildingId field if non-nil, zero value otherwise.

### GetBuildingIdOk

`func (o *ProductionOperationsManagementApiGetWorkcenterResponse) GetBuildingIdOk() (*string, bool)`

GetBuildingIdOk returns a tuple with the BuildingId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildingId

`func (o *ProductionOperationsManagementApiGetWorkcenterResponse) SetBuildingId(v string)`

SetBuildingId sets BuildingId field to given value.

### HasBuildingId

`func (o *ProductionOperationsManagementApiGetWorkcenterResponse) HasBuildingId() bool`

HasBuildingId returns a boolean if a field has been set.

### GetBuildingCode

`func (o *ProductionOperationsManagementApiGetWorkcenterResponse) GetBuildingCode() string`

GetBuildingCode returns the BuildingCode field if non-nil, zero value otherwise.

### GetBuildingCodeOk

`func (o *ProductionOperationsManagementApiGetWorkcenterResponse) GetBuildingCodeOk() (*string, bool)`

GetBuildingCodeOk returns a tuple with the BuildingCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildingCode

`func (o *ProductionOperationsManagementApiGetWorkcenterResponse) SetBuildingCode(v string)`

SetBuildingCode sets BuildingCode field to given value.

### HasBuildingCode

`func (o *ProductionOperationsManagementApiGetWorkcenterResponse) HasBuildingCode() bool`

HasBuildingCode returns a boolean if a field has been set.

### GetTankSilo

`func (o *ProductionOperationsManagementApiGetWorkcenterResponse) GetTankSilo() bool`

GetTankSilo returns the TankSilo field if non-nil, zero value otherwise.

### GetTankSiloOk

`func (o *ProductionOperationsManagementApiGetWorkcenterResponse) GetTankSiloOk() (*bool, bool)`

GetTankSiloOk returns a tuple with the TankSilo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTankSilo

`func (o *ProductionOperationsManagementApiGetWorkcenterResponse) SetTankSilo(v bool)`

SetTankSilo sets TankSilo field to given value.

### HasTankSilo

`func (o *ProductionOperationsManagementApiGetWorkcenterResponse) HasTankSilo() bool`

HasTankSilo returns a boolean if a field has been set.

### GetProductionLineId

`func (o *ProductionOperationsManagementApiGetWorkcenterResponse) GetProductionLineId() string`

GetProductionLineId returns the ProductionLineId field if non-nil, zero value otherwise.

### GetProductionLineIdOk

`func (o *ProductionOperationsManagementApiGetWorkcenterResponse) GetProductionLineIdOk() (*string, bool)`

GetProductionLineIdOk returns a tuple with the ProductionLineId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductionLineId

`func (o *ProductionOperationsManagementApiGetWorkcenterResponse) SetProductionLineId(v string)`

SetProductionLineId sets ProductionLineId field to given value.

### HasProductionLineId

`func (o *ProductionOperationsManagementApiGetWorkcenterResponse) HasProductionLineId() bool`

HasProductionLineId returns a boolean if a field has been set.

### GetIpAddress

`func (o *ProductionOperationsManagementApiGetWorkcenterResponse) GetIpAddress() string`

GetIpAddress returns the IpAddress field if non-nil, zero value otherwise.

### GetIpAddressOk

`func (o *ProductionOperationsManagementApiGetWorkcenterResponse) GetIpAddressOk() (*string, bool)`

GetIpAddressOk returns a tuple with the IpAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpAddress

`func (o *ProductionOperationsManagementApiGetWorkcenterResponse) SetIpAddress(v string)`

SetIpAddress sets IpAddress field to given value.

### HasIpAddress

`func (o *ProductionOperationsManagementApiGetWorkcenterResponse) HasIpAddress() bool`

HasIpAddress returns a boolean if a field has been set.

### GetPlcName

`func (o *ProductionOperationsManagementApiGetWorkcenterResponse) GetPlcName() string`

GetPlcName returns the PlcName field if non-nil, zero value otherwise.

### GetPlcNameOk

`func (o *ProductionOperationsManagementApiGetWorkcenterResponse) GetPlcNameOk() (*string, bool)`

GetPlcNameOk returns a tuple with the PlcName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlcName

`func (o *ProductionOperationsManagementApiGetWorkcenterResponse) SetPlcName(v string)`

SetPlcName sets PlcName field to given value.

### HasPlcName

`func (o *ProductionOperationsManagementApiGetWorkcenterResponse) HasPlcName() bool`

HasPlcName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


