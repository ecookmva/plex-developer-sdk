# ProductionOperationsManagementApiAddSourceInventoryRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**LoadFIFO** | Pointer to **bool** | Flag used to indicate what sort order the added container will be added with. If true, the container will be added to the front of the queue. If false, the container will be added to the back of the queue. | [optional] 
**SerialNo** | Pointer to **string** | The serial no of a container. | [optional] 

## Methods

### NewProductionOperationsManagementApiAddSourceInventoryRequest

`func NewProductionOperationsManagementApiAddSourceInventoryRequest() *ProductionOperationsManagementApiAddSourceInventoryRequest`

NewProductionOperationsManagementApiAddSourceInventoryRequest instantiates a new ProductionOperationsManagementApiAddSourceInventoryRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductionOperationsManagementApiAddSourceInventoryRequestWithDefaults

`func NewProductionOperationsManagementApiAddSourceInventoryRequestWithDefaults() *ProductionOperationsManagementApiAddSourceInventoryRequest`

NewProductionOperationsManagementApiAddSourceInventoryRequestWithDefaults instantiates a new ProductionOperationsManagementApiAddSourceInventoryRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLoadFIFO

`func (o *ProductionOperationsManagementApiAddSourceInventoryRequest) GetLoadFIFO() bool`

GetLoadFIFO returns the LoadFIFO field if non-nil, zero value otherwise.

### GetLoadFIFOOk

`func (o *ProductionOperationsManagementApiAddSourceInventoryRequest) GetLoadFIFOOk() (*bool, bool)`

GetLoadFIFOOk returns a tuple with the LoadFIFO field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLoadFIFO

`func (o *ProductionOperationsManagementApiAddSourceInventoryRequest) SetLoadFIFO(v bool)`

SetLoadFIFO sets LoadFIFO field to given value.

### HasLoadFIFO

`func (o *ProductionOperationsManagementApiAddSourceInventoryRequest) HasLoadFIFO() bool`

HasLoadFIFO returns a boolean if a field has been set.

### GetSerialNo

`func (o *ProductionOperationsManagementApiAddSourceInventoryRequest) GetSerialNo() string`

GetSerialNo returns the SerialNo field if non-nil, zero value otherwise.

### GetSerialNoOk

`func (o *ProductionOperationsManagementApiAddSourceInventoryRequest) GetSerialNoOk() (*string, bool)`

GetSerialNoOk returns a tuple with the SerialNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSerialNo

`func (o *ProductionOperationsManagementApiAddSourceInventoryRequest) SetSerialNo(v string)`

SetSerialNo sets SerialNo field to given value.

### HasSerialNo

`func (o *ProductionOperationsManagementApiAddSourceInventoryRequest) HasSerialNo() bool`

HasSerialNo returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


