# ProductionOperationsManagementApiAssignLotRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**JobOpId** | Pointer to **string** | A unique identifier of a job operation. | [optional] 
**BatchNo** | Pointer to **string** | The batch number. | [optional] 
**ForceCreateNewLot** | Pointer to **bool** | A boolean flag indicating whether new lot creation should be forced. | [optional] 

## Methods

### NewProductionOperationsManagementApiAssignLotRequest

`func NewProductionOperationsManagementApiAssignLotRequest() *ProductionOperationsManagementApiAssignLotRequest`

NewProductionOperationsManagementApiAssignLotRequest instantiates a new ProductionOperationsManagementApiAssignLotRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductionOperationsManagementApiAssignLotRequestWithDefaults

`func NewProductionOperationsManagementApiAssignLotRequestWithDefaults() *ProductionOperationsManagementApiAssignLotRequest`

NewProductionOperationsManagementApiAssignLotRequestWithDefaults instantiates a new ProductionOperationsManagementApiAssignLotRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetJobOpId

`func (o *ProductionOperationsManagementApiAssignLotRequest) GetJobOpId() string`

GetJobOpId returns the JobOpId field if non-nil, zero value otherwise.

### GetJobOpIdOk

`func (o *ProductionOperationsManagementApiAssignLotRequest) GetJobOpIdOk() (*string, bool)`

GetJobOpIdOk returns a tuple with the JobOpId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobOpId

`func (o *ProductionOperationsManagementApiAssignLotRequest) SetJobOpId(v string)`

SetJobOpId sets JobOpId field to given value.

### HasJobOpId

`func (o *ProductionOperationsManagementApiAssignLotRequest) HasJobOpId() bool`

HasJobOpId returns a boolean if a field has been set.

### GetBatchNo

`func (o *ProductionOperationsManagementApiAssignLotRequest) GetBatchNo() string`

GetBatchNo returns the BatchNo field if non-nil, zero value otherwise.

### GetBatchNoOk

`func (o *ProductionOperationsManagementApiAssignLotRequest) GetBatchNoOk() (*string, bool)`

GetBatchNoOk returns a tuple with the BatchNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBatchNo

`func (o *ProductionOperationsManagementApiAssignLotRequest) SetBatchNo(v string)`

SetBatchNo sets BatchNo field to given value.

### HasBatchNo

`func (o *ProductionOperationsManagementApiAssignLotRequest) HasBatchNo() bool`

HasBatchNo returns a boolean if a field has been set.

### GetForceCreateNewLot

`func (o *ProductionOperationsManagementApiAssignLotRequest) GetForceCreateNewLot() bool`

GetForceCreateNewLot returns the ForceCreateNewLot field if non-nil, zero value otherwise.

### GetForceCreateNewLotOk

`func (o *ProductionOperationsManagementApiAssignLotRequest) GetForceCreateNewLotOk() (*bool, bool)`

GetForceCreateNewLotOk returns a tuple with the ForceCreateNewLot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForceCreateNewLot

`func (o *ProductionOperationsManagementApiAssignLotRequest) SetForceCreateNewLot(v bool)`

SetForceCreateNewLot sets ForceCreateNewLot field to given value.

### HasForceCreateNewLot

`func (o *ProductionOperationsManagementApiAssignLotRequest) HasForceCreateNewLot() bool`

HasForceCreateNewLot returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


