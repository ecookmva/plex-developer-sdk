# ProductionOperationsManagementApiSetWorkcenterStatusRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**WorkcenterStatusId** | Pointer to **string** | A unique identifier of a workcenter status. | [optional] 
**WorkcenterEventId** | Pointer to **string** | A unique identifier of a workcenter event. | [optional] 
**AccountId** | Pointer to **string** | A unique identifier of a plex user. If no user is specified the user account associated with the API key will be used. | [optional] 

## Methods

### NewProductionOperationsManagementApiSetWorkcenterStatusRequest

`func NewProductionOperationsManagementApiSetWorkcenterStatusRequest() *ProductionOperationsManagementApiSetWorkcenterStatusRequest`

NewProductionOperationsManagementApiSetWorkcenterStatusRequest instantiates a new ProductionOperationsManagementApiSetWorkcenterStatusRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductionOperationsManagementApiSetWorkcenterStatusRequestWithDefaults

`func NewProductionOperationsManagementApiSetWorkcenterStatusRequestWithDefaults() *ProductionOperationsManagementApiSetWorkcenterStatusRequest`

NewProductionOperationsManagementApiSetWorkcenterStatusRequestWithDefaults instantiates a new ProductionOperationsManagementApiSetWorkcenterStatusRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetWorkcenterStatusId

`func (o *ProductionOperationsManagementApiSetWorkcenterStatusRequest) GetWorkcenterStatusId() string`

GetWorkcenterStatusId returns the WorkcenterStatusId field if non-nil, zero value otherwise.

### GetWorkcenterStatusIdOk

`func (o *ProductionOperationsManagementApiSetWorkcenterStatusRequest) GetWorkcenterStatusIdOk() (*string, bool)`

GetWorkcenterStatusIdOk returns a tuple with the WorkcenterStatusId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkcenterStatusId

`func (o *ProductionOperationsManagementApiSetWorkcenterStatusRequest) SetWorkcenterStatusId(v string)`

SetWorkcenterStatusId sets WorkcenterStatusId field to given value.

### HasWorkcenterStatusId

`func (o *ProductionOperationsManagementApiSetWorkcenterStatusRequest) HasWorkcenterStatusId() bool`

HasWorkcenterStatusId returns a boolean if a field has been set.

### GetWorkcenterEventId

`func (o *ProductionOperationsManagementApiSetWorkcenterStatusRequest) GetWorkcenterEventId() string`

GetWorkcenterEventId returns the WorkcenterEventId field if non-nil, zero value otherwise.

### GetWorkcenterEventIdOk

`func (o *ProductionOperationsManagementApiSetWorkcenterStatusRequest) GetWorkcenterEventIdOk() (*string, bool)`

GetWorkcenterEventIdOk returns a tuple with the WorkcenterEventId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkcenterEventId

`func (o *ProductionOperationsManagementApiSetWorkcenterStatusRequest) SetWorkcenterEventId(v string)`

SetWorkcenterEventId sets WorkcenterEventId field to given value.

### HasWorkcenterEventId

`func (o *ProductionOperationsManagementApiSetWorkcenterStatusRequest) HasWorkcenterEventId() bool`

HasWorkcenterEventId returns a boolean if a field has been set.

### GetAccountId

`func (o *ProductionOperationsManagementApiSetWorkcenterStatusRequest) GetAccountId() string`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *ProductionOperationsManagementApiSetWorkcenterStatusRequest) GetAccountIdOk() (*string, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *ProductionOperationsManagementApiSetWorkcenterStatusRequest) SetAccountId(v string)`

SetAccountId sets AccountId field to given value.

### HasAccountId

`func (o *ProductionOperationsManagementApiSetWorkcenterStatusRequest) HasAccountId() bool`

HasAccountId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


