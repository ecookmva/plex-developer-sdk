# ProductionOperationsManagementApiCreateApprovedWorkcenterRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PartId** | Pointer to **string** | The ID of the part that is produced. | [optional] 
**PartOperationId** | Pointer to **string** | The ID of the part operation. | [optional] 
**WorkcenterId** | Pointer to **string** | The ID of the workcenter. | [optional] 
**CrewSize** | Pointer to **float64** | The crew size associated with the workcenter. | [optional] 
**StandardProductionRate** | Pointer to **float64** | The standard production rate associated with the workcenter. | [optional] 
**Note** | Pointer to **string** | The note associated with the workcenter. | [optional] 
**SetupTime** | Pointer to **float64** | The setup time associated with the workcenter. | [optional] 
**IdealRate** | Pointer to **float64** | The ideal rate associated with the workcenter. | [optional] 
**TargetRate** | Pointer to **float64** | The target rate associated with the workcenter. | [optional] 
**SetupCrewSize** | Pointer to **float64** | The setup crew size associated with the workcenter. | [optional] 
**SequenceRate** | Pointer to **float64** | The sequence rate associated with the workcenter. | [optional] 

## Methods

### NewProductionOperationsManagementApiCreateApprovedWorkcenterRequest

`func NewProductionOperationsManagementApiCreateApprovedWorkcenterRequest() *ProductionOperationsManagementApiCreateApprovedWorkcenterRequest`

NewProductionOperationsManagementApiCreateApprovedWorkcenterRequest instantiates a new ProductionOperationsManagementApiCreateApprovedWorkcenterRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductionOperationsManagementApiCreateApprovedWorkcenterRequestWithDefaults

`func NewProductionOperationsManagementApiCreateApprovedWorkcenterRequestWithDefaults() *ProductionOperationsManagementApiCreateApprovedWorkcenterRequest`

NewProductionOperationsManagementApiCreateApprovedWorkcenterRequestWithDefaults instantiates a new ProductionOperationsManagementApiCreateApprovedWorkcenterRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPartId

`func (o *ProductionOperationsManagementApiCreateApprovedWorkcenterRequest) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *ProductionOperationsManagementApiCreateApprovedWorkcenterRequest) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *ProductionOperationsManagementApiCreateApprovedWorkcenterRequest) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *ProductionOperationsManagementApiCreateApprovedWorkcenterRequest) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetPartOperationId

`func (o *ProductionOperationsManagementApiCreateApprovedWorkcenterRequest) GetPartOperationId() string`

GetPartOperationId returns the PartOperationId field if non-nil, zero value otherwise.

### GetPartOperationIdOk

`func (o *ProductionOperationsManagementApiCreateApprovedWorkcenterRequest) GetPartOperationIdOk() (*string, bool)`

GetPartOperationIdOk returns a tuple with the PartOperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartOperationId

`func (o *ProductionOperationsManagementApiCreateApprovedWorkcenterRequest) SetPartOperationId(v string)`

SetPartOperationId sets PartOperationId field to given value.

### HasPartOperationId

`func (o *ProductionOperationsManagementApiCreateApprovedWorkcenterRequest) HasPartOperationId() bool`

HasPartOperationId returns a boolean if a field has been set.

### GetWorkcenterId

`func (o *ProductionOperationsManagementApiCreateApprovedWorkcenterRequest) GetWorkcenterId() string`

GetWorkcenterId returns the WorkcenterId field if non-nil, zero value otherwise.

### GetWorkcenterIdOk

`func (o *ProductionOperationsManagementApiCreateApprovedWorkcenterRequest) GetWorkcenterIdOk() (*string, bool)`

GetWorkcenterIdOk returns a tuple with the WorkcenterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkcenterId

`func (o *ProductionOperationsManagementApiCreateApprovedWorkcenterRequest) SetWorkcenterId(v string)`

SetWorkcenterId sets WorkcenterId field to given value.

### HasWorkcenterId

`func (o *ProductionOperationsManagementApiCreateApprovedWorkcenterRequest) HasWorkcenterId() bool`

HasWorkcenterId returns a boolean if a field has been set.

### GetCrewSize

`func (o *ProductionOperationsManagementApiCreateApprovedWorkcenterRequest) GetCrewSize() float64`

GetCrewSize returns the CrewSize field if non-nil, zero value otherwise.

### GetCrewSizeOk

`func (o *ProductionOperationsManagementApiCreateApprovedWorkcenterRequest) GetCrewSizeOk() (*float64, bool)`

GetCrewSizeOk returns a tuple with the CrewSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCrewSize

`func (o *ProductionOperationsManagementApiCreateApprovedWorkcenterRequest) SetCrewSize(v float64)`

SetCrewSize sets CrewSize field to given value.

### HasCrewSize

`func (o *ProductionOperationsManagementApiCreateApprovedWorkcenterRequest) HasCrewSize() bool`

HasCrewSize returns a boolean if a field has been set.

### GetStandardProductionRate

`func (o *ProductionOperationsManagementApiCreateApprovedWorkcenterRequest) GetStandardProductionRate() float64`

GetStandardProductionRate returns the StandardProductionRate field if non-nil, zero value otherwise.

### GetStandardProductionRateOk

`func (o *ProductionOperationsManagementApiCreateApprovedWorkcenterRequest) GetStandardProductionRateOk() (*float64, bool)`

GetStandardProductionRateOk returns a tuple with the StandardProductionRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStandardProductionRate

`func (o *ProductionOperationsManagementApiCreateApprovedWorkcenterRequest) SetStandardProductionRate(v float64)`

SetStandardProductionRate sets StandardProductionRate field to given value.

### HasStandardProductionRate

`func (o *ProductionOperationsManagementApiCreateApprovedWorkcenterRequest) HasStandardProductionRate() bool`

HasStandardProductionRate returns a boolean if a field has been set.

### GetNote

`func (o *ProductionOperationsManagementApiCreateApprovedWorkcenterRequest) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *ProductionOperationsManagementApiCreateApprovedWorkcenterRequest) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *ProductionOperationsManagementApiCreateApprovedWorkcenterRequest) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *ProductionOperationsManagementApiCreateApprovedWorkcenterRequest) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetSetupTime

`func (o *ProductionOperationsManagementApiCreateApprovedWorkcenterRequest) GetSetupTime() float64`

GetSetupTime returns the SetupTime field if non-nil, zero value otherwise.

### GetSetupTimeOk

`func (o *ProductionOperationsManagementApiCreateApprovedWorkcenterRequest) GetSetupTimeOk() (*float64, bool)`

GetSetupTimeOk returns a tuple with the SetupTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSetupTime

`func (o *ProductionOperationsManagementApiCreateApprovedWorkcenterRequest) SetSetupTime(v float64)`

SetSetupTime sets SetupTime field to given value.

### HasSetupTime

`func (o *ProductionOperationsManagementApiCreateApprovedWorkcenterRequest) HasSetupTime() bool`

HasSetupTime returns a boolean if a field has been set.

### GetIdealRate

`func (o *ProductionOperationsManagementApiCreateApprovedWorkcenterRequest) GetIdealRate() float64`

GetIdealRate returns the IdealRate field if non-nil, zero value otherwise.

### GetIdealRateOk

`func (o *ProductionOperationsManagementApiCreateApprovedWorkcenterRequest) GetIdealRateOk() (*float64, bool)`

GetIdealRateOk returns a tuple with the IdealRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdealRate

`func (o *ProductionOperationsManagementApiCreateApprovedWorkcenterRequest) SetIdealRate(v float64)`

SetIdealRate sets IdealRate field to given value.

### HasIdealRate

`func (o *ProductionOperationsManagementApiCreateApprovedWorkcenterRequest) HasIdealRate() bool`

HasIdealRate returns a boolean if a field has been set.

### GetTargetRate

`func (o *ProductionOperationsManagementApiCreateApprovedWorkcenterRequest) GetTargetRate() float64`

GetTargetRate returns the TargetRate field if non-nil, zero value otherwise.

### GetTargetRateOk

`func (o *ProductionOperationsManagementApiCreateApprovedWorkcenterRequest) GetTargetRateOk() (*float64, bool)`

GetTargetRateOk returns a tuple with the TargetRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetRate

`func (o *ProductionOperationsManagementApiCreateApprovedWorkcenterRequest) SetTargetRate(v float64)`

SetTargetRate sets TargetRate field to given value.

### HasTargetRate

`func (o *ProductionOperationsManagementApiCreateApprovedWorkcenterRequest) HasTargetRate() bool`

HasTargetRate returns a boolean if a field has been set.

### GetSetupCrewSize

`func (o *ProductionOperationsManagementApiCreateApprovedWorkcenterRequest) GetSetupCrewSize() float64`

GetSetupCrewSize returns the SetupCrewSize field if non-nil, zero value otherwise.

### GetSetupCrewSizeOk

`func (o *ProductionOperationsManagementApiCreateApprovedWorkcenterRequest) GetSetupCrewSizeOk() (*float64, bool)`

GetSetupCrewSizeOk returns a tuple with the SetupCrewSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSetupCrewSize

`func (o *ProductionOperationsManagementApiCreateApprovedWorkcenterRequest) SetSetupCrewSize(v float64)`

SetSetupCrewSize sets SetupCrewSize field to given value.

### HasSetupCrewSize

`func (o *ProductionOperationsManagementApiCreateApprovedWorkcenterRequest) HasSetupCrewSize() bool`

HasSetupCrewSize returns a boolean if a field has been set.

### GetSequenceRate

`func (o *ProductionOperationsManagementApiCreateApprovedWorkcenterRequest) GetSequenceRate() float64`

GetSequenceRate returns the SequenceRate field if non-nil, zero value otherwise.

### GetSequenceRateOk

`func (o *ProductionOperationsManagementApiCreateApprovedWorkcenterRequest) GetSequenceRateOk() (*float64, bool)`

GetSequenceRateOk returns a tuple with the SequenceRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSequenceRate

`func (o *ProductionOperationsManagementApiCreateApprovedWorkcenterRequest) SetSequenceRate(v float64)`

SetSequenceRate sets SequenceRate field to given value.

### HasSequenceRate

`func (o *ProductionOperationsManagementApiCreateApprovedWorkcenterRequest) HasSequenceRate() bool`

HasSequenceRate returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


