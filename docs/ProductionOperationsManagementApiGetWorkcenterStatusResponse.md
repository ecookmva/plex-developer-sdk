# ProductionOperationsManagementApiGetWorkcenterStatusResponse

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

### NewProductionOperationsManagementApiGetWorkcenterStatusResponse

`func NewProductionOperationsManagementApiGetWorkcenterStatusResponse() *ProductionOperationsManagementApiGetWorkcenterStatusResponse`

NewProductionOperationsManagementApiGetWorkcenterStatusResponse instantiates a new ProductionOperationsManagementApiGetWorkcenterStatusResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductionOperationsManagementApiGetWorkcenterStatusResponseWithDefaults

`func NewProductionOperationsManagementApiGetWorkcenterStatusResponseWithDefaults() *ProductionOperationsManagementApiGetWorkcenterStatusResponse`

NewProductionOperationsManagementApiGetWorkcenterStatusResponseWithDefaults instantiates a new ProductionOperationsManagementApiGetWorkcenterStatusResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetDescription

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetCanRunProduction

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) GetCanRunProduction() bool`

GetCanRunProduction returns the CanRunProduction field if non-nil, zero value otherwise.

### GetCanRunProductionOk

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) GetCanRunProductionOk() (*bool, bool)`

GetCanRunProductionOk returns a tuple with the CanRunProduction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCanRunProduction

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) SetCanRunProduction(v bool)`

SetCanRunProduction sets CanRunProduction field to given value.

### HasCanRunProduction

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) HasCanRunProduction() bool`

HasCanRunProduction returns a boolean if a field has been set.

### GetOffStatus

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) GetOffStatus() bool`

GetOffStatus returns the OffStatus field if non-nil, zero value otherwise.

### GetOffStatusOk

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) GetOffStatusOk() (*bool, bool)`

GetOffStatusOk returns a tuple with the OffStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffStatus

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) SetOffStatus(v bool)`

SetOffStatus sets OffStatus field to given value.

### HasOffStatus

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) HasOffStatus() bool`

HasOffStatus returns a boolean if a field has been set.

### GetClockoutOperators

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) GetClockoutOperators() bool`

GetClockoutOperators returns the ClockoutOperators field if non-nil, zero value otherwise.

### GetClockoutOperatorsOk

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) GetClockoutOperatorsOk() (*bool, bool)`

GetClockoutOperatorsOk returns a tuple with the ClockoutOperators field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClockoutOperators

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) SetClockoutOperators(v bool)`

SetClockoutOperators sets ClockoutOperators field to given value.

### HasClockoutOperators

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) HasClockoutOperators() bool`

HasClockoutOperators returns a boolean if a field has been set.

### GetIdleStatus

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) GetIdleStatus() bool`

GetIdleStatus returns the IdleStatus field if non-nil, zero value otherwise.

### GetIdleStatusOk

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) GetIdleStatusOk() (*bool, bool)`

GetIdleStatusOk returns a tuple with the IdleStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdleStatus

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) SetIdleStatus(v bool)`

SetIdleStatus sets IdleStatus field to given value.

### HasIdleStatus

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) HasIdleStatus() bool`

HasIdleStatus returns a boolean if a field has been set.

### GetDefaultAfterJobChange

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) GetDefaultAfterJobChange() bool`

GetDefaultAfterJobChange returns the DefaultAfterJobChange field if non-nil, zero value otherwise.

### GetDefaultAfterJobChangeOk

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) GetDefaultAfterJobChangeOk() (*bool, bool)`

GetDefaultAfterJobChangeOk returns a tuple with the DefaultAfterJobChange field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultAfterJobChange

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) SetDefaultAfterJobChange(v bool)`

SetDefaultAfterJobChange sets DefaultAfterJobChange field to given value.

### HasDefaultAfterJobChange

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) HasDefaultAfterJobChange() bool`

HasDefaultAfterJobChange returns a boolean if a field has been set.

### GetProductionStatus

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) GetProductionStatus() bool`

GetProductionStatus returns the ProductionStatus field if non-nil, zero value otherwise.

### GetProductionStatusOk

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) GetProductionStatusOk() (*bool, bool)`

GetProductionStatusOk returns a tuple with the ProductionStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductionStatus

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) SetProductionStatus(v bool)`

SetProductionStatus sets ProductionStatus field to given value.

### HasProductionStatus

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) HasProductionStatus() bool`

HasProductionStatus returns a boolean if a field has been set.

### GetSetupStatus

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) GetSetupStatus() bool`

GetSetupStatus returns the SetupStatus field if non-nil, zero value otherwise.

### GetSetupStatusOk

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) GetSetupStatusOk() (*bool, bool)`

GetSetupStatusOk returns a tuple with the SetupStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSetupStatus

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) SetSetupStatus(v bool)`

SetSetupStatus sets SetupStatus field to given value.

### HasSetupStatus

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) HasSetupStatus() bool`

HasSetupStatus returns a boolean if a field has been set.

### GetDowntimeStatus

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) GetDowntimeStatus() bool`

GetDowntimeStatus returns the DowntimeStatus field if non-nil, zero value otherwise.

### GetDowntimeStatusOk

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) GetDowntimeStatusOk() (*bool, bool)`

GetDowntimeStatusOk returns a tuple with the DowntimeStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDowntimeStatus

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) SetDowntimeStatus(v bool)`

SetDowntimeStatus sets DowntimeStatus field to given value.

### HasDowntimeStatus

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) HasDowntimeStatus() bool`

HasDowntimeStatus returns a boolean if a field has been set.

### GetNoOperatorRequired

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) GetNoOperatorRequired() bool`

GetNoOperatorRequired returns the NoOperatorRequired field if non-nil, zero value otherwise.

### GetNoOperatorRequiredOk

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) GetNoOperatorRequiredOk() (*bool, bool)`

GetNoOperatorRequiredOk returns a tuple with the NoOperatorRequired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNoOperatorRequired

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) SetNoOperatorRequired(v bool)`

SetNoOperatorRequired sets NoOperatorRequired field to given value.

### HasNoOperatorRequired

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) HasNoOperatorRequired() bool`

HasNoOperatorRequired returns a boolean if a field has been set.

### GetLaborCostSubTypeId

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) GetLaborCostSubTypeId() string`

GetLaborCostSubTypeId returns the LaborCostSubTypeId field if non-nil, zero value otherwise.

### GetLaborCostSubTypeIdOk

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) GetLaborCostSubTypeIdOk() (*string, bool)`

GetLaborCostSubTypeIdOk returns a tuple with the LaborCostSubTypeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLaborCostSubTypeId

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) SetLaborCostSubTypeId(v string)`

SetLaborCostSubTypeId sets LaborCostSubTypeId field to given value.

### HasLaborCostSubTypeId

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) HasLaborCostSubTypeId() bool`

HasLaborCostSubTypeId returns a boolean if a field has been set.

### GetMaintenanceStatus

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) GetMaintenanceStatus() bool`

GetMaintenanceStatus returns the MaintenanceStatus field if non-nil, zero value otherwise.

### GetMaintenanceStatusOk

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) GetMaintenanceStatusOk() (*bool, bool)`

GetMaintenanceStatusOk returns a tuple with the MaintenanceStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaintenanceStatus

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) SetMaintenanceStatus(v bool)`

SetMaintenanceStatus sets MaintenanceStatus field to given value.

### HasMaintenanceStatus

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) HasMaintenanceStatus() bool`

HasMaintenanceStatus returns a boolean if a field has been set.

### GetActive

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetExcessSetup

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) GetExcessSetup() bool`

GetExcessSetup returns the ExcessSetup field if non-nil, zero value otherwise.

### GetExcessSetupOk

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) GetExcessSetupOk() (*bool, bool)`

GetExcessSetupOk returns a tuple with the ExcessSetup field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExcessSetup

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) SetExcessSetup(v bool)`

SetExcessSetup sets ExcessSetup field to given value.

### HasExcessSetup

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) HasExcessSetup() bool`

HasExcessSetup returns a boolean if a field has been set.

### GetWorkcenterGroupWorkcenters

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) GetWorkcenterGroupWorkcenters() []string`

GetWorkcenterGroupWorkcenters returns the WorkcenterGroupWorkcenters field if non-nil, zero value otherwise.

### GetWorkcenterGroupWorkcentersOk

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) GetWorkcenterGroupWorkcentersOk() (*[]string, bool)`

GetWorkcenterGroupWorkcentersOk returns a tuple with the WorkcenterGroupWorkcenters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkcenterGroupWorkcenters

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) SetWorkcenterGroupWorkcenters(v []string)`

SetWorkcenterGroupWorkcenters sets WorkcenterGroupWorkcenters field to given value.

### HasWorkcenterGroupWorkcenters

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) HasWorkcenterGroupWorkcenters() bool`

HasWorkcenterGroupWorkcenters returns a boolean if a field has been set.

### GetLinkedWorkcenterEvents

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) GetLinkedWorkcenterEvents() []string`

GetLinkedWorkcenterEvents returns the LinkedWorkcenterEvents field if non-nil, zero value otherwise.

### GetLinkedWorkcenterEventsOk

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) GetLinkedWorkcenterEventsOk() (*[]string, bool)`

GetLinkedWorkcenterEventsOk returns a tuple with the LinkedWorkcenterEvents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinkedWorkcenterEvents

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) SetLinkedWorkcenterEvents(v []string)`

SetLinkedWorkcenterEvents sets LinkedWorkcenterEvents field to given value.

### HasLinkedWorkcenterEvents

`func (o *ProductionOperationsManagementApiGetWorkcenterStatusResponse) HasLinkedWorkcenterEvents() bool`

HasLinkedWorkcenterEvents returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


