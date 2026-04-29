# ProductionOperationsManagementApiListWorkcenterStatusItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | A unique identifier of the workcenter status. | [optional] 
**Description** | Pointer to **string** | The workcenter status description. | [optional] 
**CanRunProduction** | Pointer to **bool** | Indicates workcenter status can run production. | [optional] 
**OffStatus** | Pointer to **bool** | Indicates workcenter status is an off status. | [optional] 
**ClockoutOperators** | Pointer to **bool** | Indicates workcenter status can cause clockout operators when selected in ux. | [optional] 
**IdleStatus** | Pointer to **bool** | Indicates workcenter status is an idle status. | [optional] 
**DefaultAfterJobChange** | Pointer to **bool** | Indicates workcenter status is the default after a job change. | [optional] 
**ProductionStatus** | Pointer to **bool** | Indicates workcenter status is a production status. | [optional] 
**SetupStatus** | Pointer to **bool** | Indicates workcenter status is a setup status. | [optional] 
**DowntimeStatus** | Pointer to **bool** | Indicates workcenter status is a downtime status. | [optional] 
**NoOperatorRequired** | Pointer to **bool** | Indicates workcenter status does not require operators to be logged in. | [optional] 
**LaborCostSubTypeId** | Pointer to **string** | A unique identifier of a Cost Sub Type used for labor. | [optional] 
**MaintenanceStatus** | Pointer to **bool** | Indicates workcenter status is a maintenance status. | [optional] 
**Active** | Pointer to **bool** | Indicates workcenter status is active. | [optional] 
**ExcessSetup** | Pointer to **bool** | Indicates workcenter status is an excess setup status. | [optional] 
**WorkcenterGroupWorkcenters** | Pointer to **[]string** | List of workcenter IDs belonging to the workcenter group associated with this workcenter status. | [optional] 
**LinkedWorkcenterEvents** | Pointer to **[]string** | List of workcenter event IDs linked to this status. | [optional] 

## Methods

### NewProductionOperationsManagementApiListWorkcenterStatusItem

`func NewProductionOperationsManagementApiListWorkcenterStatusItem() *ProductionOperationsManagementApiListWorkcenterStatusItem`

NewProductionOperationsManagementApiListWorkcenterStatusItem instantiates a new ProductionOperationsManagementApiListWorkcenterStatusItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductionOperationsManagementApiListWorkcenterStatusItemWithDefaults

`func NewProductionOperationsManagementApiListWorkcenterStatusItemWithDefaults() *ProductionOperationsManagementApiListWorkcenterStatusItem`

NewProductionOperationsManagementApiListWorkcenterStatusItemWithDefaults instantiates a new ProductionOperationsManagementApiListWorkcenterStatusItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) HasId() bool`

HasId returns a boolean if a field has been set.

### GetDescription

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetCanRunProduction

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) GetCanRunProduction() bool`

GetCanRunProduction returns the CanRunProduction field if non-nil, zero value otherwise.

### GetCanRunProductionOk

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) GetCanRunProductionOk() (*bool, bool)`

GetCanRunProductionOk returns a tuple with the CanRunProduction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCanRunProduction

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) SetCanRunProduction(v bool)`

SetCanRunProduction sets CanRunProduction field to given value.

### HasCanRunProduction

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) HasCanRunProduction() bool`

HasCanRunProduction returns a boolean if a field has been set.

### GetOffStatus

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) GetOffStatus() bool`

GetOffStatus returns the OffStatus field if non-nil, zero value otherwise.

### GetOffStatusOk

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) GetOffStatusOk() (*bool, bool)`

GetOffStatusOk returns a tuple with the OffStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffStatus

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) SetOffStatus(v bool)`

SetOffStatus sets OffStatus field to given value.

### HasOffStatus

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) HasOffStatus() bool`

HasOffStatus returns a boolean if a field has been set.

### GetClockoutOperators

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) GetClockoutOperators() bool`

GetClockoutOperators returns the ClockoutOperators field if non-nil, zero value otherwise.

### GetClockoutOperatorsOk

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) GetClockoutOperatorsOk() (*bool, bool)`

GetClockoutOperatorsOk returns a tuple with the ClockoutOperators field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClockoutOperators

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) SetClockoutOperators(v bool)`

SetClockoutOperators sets ClockoutOperators field to given value.

### HasClockoutOperators

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) HasClockoutOperators() bool`

HasClockoutOperators returns a boolean if a field has been set.

### GetIdleStatus

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) GetIdleStatus() bool`

GetIdleStatus returns the IdleStatus field if non-nil, zero value otherwise.

### GetIdleStatusOk

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) GetIdleStatusOk() (*bool, bool)`

GetIdleStatusOk returns a tuple with the IdleStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdleStatus

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) SetIdleStatus(v bool)`

SetIdleStatus sets IdleStatus field to given value.

### HasIdleStatus

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) HasIdleStatus() bool`

HasIdleStatus returns a boolean if a field has been set.

### GetDefaultAfterJobChange

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) GetDefaultAfterJobChange() bool`

GetDefaultAfterJobChange returns the DefaultAfterJobChange field if non-nil, zero value otherwise.

### GetDefaultAfterJobChangeOk

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) GetDefaultAfterJobChangeOk() (*bool, bool)`

GetDefaultAfterJobChangeOk returns a tuple with the DefaultAfterJobChange field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultAfterJobChange

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) SetDefaultAfterJobChange(v bool)`

SetDefaultAfterJobChange sets DefaultAfterJobChange field to given value.

### HasDefaultAfterJobChange

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) HasDefaultAfterJobChange() bool`

HasDefaultAfterJobChange returns a boolean if a field has been set.

### GetProductionStatus

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) GetProductionStatus() bool`

GetProductionStatus returns the ProductionStatus field if non-nil, zero value otherwise.

### GetProductionStatusOk

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) GetProductionStatusOk() (*bool, bool)`

GetProductionStatusOk returns a tuple with the ProductionStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductionStatus

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) SetProductionStatus(v bool)`

SetProductionStatus sets ProductionStatus field to given value.

### HasProductionStatus

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) HasProductionStatus() bool`

HasProductionStatus returns a boolean if a field has been set.

### GetSetupStatus

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) GetSetupStatus() bool`

GetSetupStatus returns the SetupStatus field if non-nil, zero value otherwise.

### GetSetupStatusOk

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) GetSetupStatusOk() (*bool, bool)`

GetSetupStatusOk returns a tuple with the SetupStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSetupStatus

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) SetSetupStatus(v bool)`

SetSetupStatus sets SetupStatus field to given value.

### HasSetupStatus

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) HasSetupStatus() bool`

HasSetupStatus returns a boolean if a field has been set.

### GetDowntimeStatus

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) GetDowntimeStatus() bool`

GetDowntimeStatus returns the DowntimeStatus field if non-nil, zero value otherwise.

### GetDowntimeStatusOk

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) GetDowntimeStatusOk() (*bool, bool)`

GetDowntimeStatusOk returns a tuple with the DowntimeStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDowntimeStatus

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) SetDowntimeStatus(v bool)`

SetDowntimeStatus sets DowntimeStatus field to given value.

### HasDowntimeStatus

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) HasDowntimeStatus() bool`

HasDowntimeStatus returns a boolean if a field has been set.

### GetNoOperatorRequired

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) GetNoOperatorRequired() bool`

GetNoOperatorRequired returns the NoOperatorRequired field if non-nil, zero value otherwise.

### GetNoOperatorRequiredOk

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) GetNoOperatorRequiredOk() (*bool, bool)`

GetNoOperatorRequiredOk returns a tuple with the NoOperatorRequired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNoOperatorRequired

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) SetNoOperatorRequired(v bool)`

SetNoOperatorRequired sets NoOperatorRequired field to given value.

### HasNoOperatorRequired

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) HasNoOperatorRequired() bool`

HasNoOperatorRequired returns a boolean if a field has been set.

### GetLaborCostSubTypeId

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) GetLaborCostSubTypeId() string`

GetLaborCostSubTypeId returns the LaborCostSubTypeId field if non-nil, zero value otherwise.

### GetLaborCostSubTypeIdOk

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) GetLaborCostSubTypeIdOk() (*string, bool)`

GetLaborCostSubTypeIdOk returns a tuple with the LaborCostSubTypeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLaborCostSubTypeId

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) SetLaborCostSubTypeId(v string)`

SetLaborCostSubTypeId sets LaborCostSubTypeId field to given value.

### HasLaborCostSubTypeId

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) HasLaborCostSubTypeId() bool`

HasLaborCostSubTypeId returns a boolean if a field has been set.

### GetMaintenanceStatus

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) GetMaintenanceStatus() bool`

GetMaintenanceStatus returns the MaintenanceStatus field if non-nil, zero value otherwise.

### GetMaintenanceStatusOk

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) GetMaintenanceStatusOk() (*bool, bool)`

GetMaintenanceStatusOk returns a tuple with the MaintenanceStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaintenanceStatus

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) SetMaintenanceStatus(v bool)`

SetMaintenanceStatus sets MaintenanceStatus field to given value.

### HasMaintenanceStatus

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) HasMaintenanceStatus() bool`

HasMaintenanceStatus returns a boolean if a field has been set.

### GetActive

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetExcessSetup

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) GetExcessSetup() bool`

GetExcessSetup returns the ExcessSetup field if non-nil, zero value otherwise.

### GetExcessSetupOk

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) GetExcessSetupOk() (*bool, bool)`

GetExcessSetupOk returns a tuple with the ExcessSetup field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExcessSetup

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) SetExcessSetup(v bool)`

SetExcessSetup sets ExcessSetup field to given value.

### HasExcessSetup

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) HasExcessSetup() bool`

HasExcessSetup returns a boolean if a field has been set.

### GetWorkcenterGroupWorkcenters

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) GetWorkcenterGroupWorkcenters() []string`

GetWorkcenterGroupWorkcenters returns the WorkcenterGroupWorkcenters field if non-nil, zero value otherwise.

### GetWorkcenterGroupWorkcentersOk

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) GetWorkcenterGroupWorkcentersOk() (*[]string, bool)`

GetWorkcenterGroupWorkcentersOk returns a tuple with the WorkcenterGroupWorkcenters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkcenterGroupWorkcenters

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) SetWorkcenterGroupWorkcenters(v []string)`

SetWorkcenterGroupWorkcenters sets WorkcenterGroupWorkcenters field to given value.

### HasWorkcenterGroupWorkcenters

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) HasWorkcenterGroupWorkcenters() bool`

HasWorkcenterGroupWorkcenters returns a boolean if a field has been set.

### GetLinkedWorkcenterEvents

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) GetLinkedWorkcenterEvents() []string`

GetLinkedWorkcenterEvents returns the LinkedWorkcenterEvents field if non-nil, zero value otherwise.

### GetLinkedWorkcenterEventsOk

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) GetLinkedWorkcenterEventsOk() (*[]string, bool)`

GetLinkedWorkcenterEventsOk returns a tuple with the LinkedWorkcenterEvents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinkedWorkcenterEvents

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) SetLinkedWorkcenterEvents(v []string)`

SetLinkedWorkcenterEvents sets LinkedWorkcenterEvents field to given value.

### HasLinkedWorkcenterEvents

`func (o *ProductionOperationsManagementApiListWorkcenterStatusItem) HasLinkedWorkcenterEvents() bool`

HasLinkedWorkcenterEvents returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


