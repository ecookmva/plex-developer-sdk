# ProductionOperationsManagementApiGetWorkcenter404Response

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

### NewProductionOperationsManagementApiGetWorkcenter404Response

`func NewProductionOperationsManagementApiGetWorkcenter404Response() *ProductionOperationsManagementApiGetWorkcenter404Response`

NewProductionOperationsManagementApiGetWorkcenter404Response instantiates a new ProductionOperationsManagementApiGetWorkcenter404Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductionOperationsManagementApiGetWorkcenter404ResponseWithDefaults

`func NewProductionOperationsManagementApiGetWorkcenter404ResponseWithDefaults() *ProductionOperationsManagementApiGetWorkcenter404Response`

NewProductionOperationsManagementApiGetWorkcenter404ResponseWithDefaults instantiates a new ProductionOperationsManagementApiGetWorkcenter404Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetWorkcenterId

`func (o *ProductionOperationsManagementApiGetWorkcenter404Response) GetWorkcenterId() string`

GetWorkcenterId returns the WorkcenterId field if non-nil, zero value otherwise.

### GetWorkcenterIdOk

`func (o *ProductionOperationsManagementApiGetWorkcenter404Response) GetWorkcenterIdOk() (*string, bool)`

GetWorkcenterIdOk returns a tuple with the WorkcenterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkcenterId

`func (o *ProductionOperationsManagementApiGetWorkcenter404Response) SetWorkcenterId(v string)`

SetWorkcenterId sets WorkcenterId field to given value.

### HasWorkcenterId

`func (o *ProductionOperationsManagementApiGetWorkcenter404Response) HasWorkcenterId() bool`

HasWorkcenterId returns a boolean if a field has been set.

### GetWorkcenterCode

`func (o *ProductionOperationsManagementApiGetWorkcenter404Response) GetWorkcenterCode() string`

GetWorkcenterCode returns the WorkcenterCode field if non-nil, zero value otherwise.

### GetWorkcenterCodeOk

`func (o *ProductionOperationsManagementApiGetWorkcenter404Response) GetWorkcenterCodeOk() (*string, bool)`

GetWorkcenterCodeOk returns a tuple with the WorkcenterCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkcenterCode

`func (o *ProductionOperationsManagementApiGetWorkcenter404Response) SetWorkcenterCode(v string)`

SetWorkcenterCode sets WorkcenterCode field to given value.

### HasWorkcenterCode

`func (o *ProductionOperationsManagementApiGetWorkcenter404Response) HasWorkcenterCode() bool`

HasWorkcenterCode returns a boolean if a field has been set.

### GetName

`func (o *ProductionOperationsManagementApiGetWorkcenter404Response) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ProductionOperationsManagementApiGetWorkcenter404Response) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ProductionOperationsManagementApiGetWorkcenter404Response) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ProductionOperationsManagementApiGetWorkcenter404Response) HasName() bool`

HasName returns a boolean if a field has been set.

### GetWorkcenterType

`func (o *ProductionOperationsManagementApiGetWorkcenter404Response) GetWorkcenterType() string`

GetWorkcenterType returns the WorkcenterType field if non-nil, zero value otherwise.

### GetWorkcenterTypeOk

`func (o *ProductionOperationsManagementApiGetWorkcenter404Response) GetWorkcenterTypeOk() (*string, bool)`

GetWorkcenterTypeOk returns a tuple with the WorkcenterType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkcenterType

`func (o *ProductionOperationsManagementApiGetWorkcenter404Response) SetWorkcenterType(v string)`

SetWorkcenterType sets WorkcenterType field to given value.

### HasWorkcenterType

`func (o *ProductionOperationsManagementApiGetWorkcenter404Response) HasWorkcenterType() bool`

HasWorkcenterType returns a boolean if a field has been set.

### GetWorkcenterGroup

`func (o *ProductionOperationsManagementApiGetWorkcenter404Response) GetWorkcenterGroup() string`

GetWorkcenterGroup returns the WorkcenterGroup field if non-nil, zero value otherwise.

### GetWorkcenterGroupOk

`func (o *ProductionOperationsManagementApiGetWorkcenter404Response) GetWorkcenterGroupOk() (*string, bool)`

GetWorkcenterGroupOk returns a tuple with the WorkcenterGroup field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkcenterGroup

`func (o *ProductionOperationsManagementApiGetWorkcenter404Response) SetWorkcenterGroup(v string)`

SetWorkcenterGroup sets WorkcenterGroup field to given value.

### HasWorkcenterGroup

`func (o *ProductionOperationsManagementApiGetWorkcenter404Response) HasWorkcenterGroup() bool`

HasWorkcenterGroup returns a boolean if a field has been set.

### GetBuildingId

`func (o *ProductionOperationsManagementApiGetWorkcenter404Response) GetBuildingId() string`

GetBuildingId returns the BuildingId field if non-nil, zero value otherwise.

### GetBuildingIdOk

`func (o *ProductionOperationsManagementApiGetWorkcenter404Response) GetBuildingIdOk() (*string, bool)`

GetBuildingIdOk returns a tuple with the BuildingId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildingId

`func (o *ProductionOperationsManagementApiGetWorkcenter404Response) SetBuildingId(v string)`

SetBuildingId sets BuildingId field to given value.

### HasBuildingId

`func (o *ProductionOperationsManagementApiGetWorkcenter404Response) HasBuildingId() bool`

HasBuildingId returns a boolean if a field has been set.

### GetBuildingCode

`func (o *ProductionOperationsManagementApiGetWorkcenter404Response) GetBuildingCode() string`

GetBuildingCode returns the BuildingCode field if non-nil, zero value otherwise.

### GetBuildingCodeOk

`func (o *ProductionOperationsManagementApiGetWorkcenter404Response) GetBuildingCodeOk() (*string, bool)`

GetBuildingCodeOk returns a tuple with the BuildingCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildingCode

`func (o *ProductionOperationsManagementApiGetWorkcenter404Response) SetBuildingCode(v string)`

SetBuildingCode sets BuildingCode field to given value.

### HasBuildingCode

`func (o *ProductionOperationsManagementApiGetWorkcenter404Response) HasBuildingCode() bool`

HasBuildingCode returns a boolean if a field has been set.

### GetTankSilo

`func (o *ProductionOperationsManagementApiGetWorkcenter404Response) GetTankSilo() bool`

GetTankSilo returns the TankSilo field if non-nil, zero value otherwise.

### GetTankSiloOk

`func (o *ProductionOperationsManagementApiGetWorkcenter404Response) GetTankSiloOk() (*bool, bool)`

GetTankSiloOk returns a tuple with the TankSilo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTankSilo

`func (o *ProductionOperationsManagementApiGetWorkcenter404Response) SetTankSilo(v bool)`

SetTankSilo sets TankSilo field to given value.

### HasTankSilo

`func (o *ProductionOperationsManagementApiGetWorkcenter404Response) HasTankSilo() bool`

HasTankSilo returns a boolean if a field has been set.

### GetProductionLineId

`func (o *ProductionOperationsManagementApiGetWorkcenter404Response) GetProductionLineId() string`

GetProductionLineId returns the ProductionLineId field if non-nil, zero value otherwise.

### GetProductionLineIdOk

`func (o *ProductionOperationsManagementApiGetWorkcenter404Response) GetProductionLineIdOk() (*string, bool)`

GetProductionLineIdOk returns a tuple with the ProductionLineId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductionLineId

`func (o *ProductionOperationsManagementApiGetWorkcenter404Response) SetProductionLineId(v string)`

SetProductionLineId sets ProductionLineId field to given value.

### HasProductionLineId

`func (o *ProductionOperationsManagementApiGetWorkcenter404Response) HasProductionLineId() bool`

HasProductionLineId returns a boolean if a field has been set.

### GetIpAddress

`func (o *ProductionOperationsManagementApiGetWorkcenter404Response) GetIpAddress() string`

GetIpAddress returns the IpAddress field if non-nil, zero value otherwise.

### GetIpAddressOk

`func (o *ProductionOperationsManagementApiGetWorkcenter404Response) GetIpAddressOk() (*string, bool)`

GetIpAddressOk returns a tuple with the IpAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpAddress

`func (o *ProductionOperationsManagementApiGetWorkcenter404Response) SetIpAddress(v string)`

SetIpAddress sets IpAddress field to given value.

### HasIpAddress

`func (o *ProductionOperationsManagementApiGetWorkcenter404Response) HasIpAddress() bool`

HasIpAddress returns a boolean if a field has been set.

### GetPlcName

`func (o *ProductionOperationsManagementApiGetWorkcenter404Response) GetPlcName() string`

GetPlcName returns the PlcName field if non-nil, zero value otherwise.

### GetPlcNameOk

`func (o *ProductionOperationsManagementApiGetWorkcenter404Response) GetPlcNameOk() (*string, bool)`

GetPlcNameOk returns a tuple with the PlcName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlcName

`func (o *ProductionOperationsManagementApiGetWorkcenter404Response) SetPlcName(v string)`

SetPlcName sets PlcName field to given value.

### HasPlcName

`func (o *ProductionOperationsManagementApiGetWorkcenter404Response) HasPlcName() bool`

HasPlcName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


