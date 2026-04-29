# ProductionOperationsManagementApiRecordVariableBOMProductionResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SerialNo** | Pointer to **string** | 25 characters max. The Serial No of the produced container. | [optional] 
**Quantity** | Pointer to **float64** | The output container quantity. | [optional] 
**SourceComponentQuantities** | Pointer to [**[]SourceComponentQuantitiesItem1**](SourceComponentQuantitiesItem1.md) | The batch components. | [optional] 

## Methods

### NewProductionOperationsManagementApiRecordVariableBOMProductionResponse

`func NewProductionOperationsManagementApiRecordVariableBOMProductionResponse() *ProductionOperationsManagementApiRecordVariableBOMProductionResponse`

NewProductionOperationsManagementApiRecordVariableBOMProductionResponse instantiates a new ProductionOperationsManagementApiRecordVariableBOMProductionResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductionOperationsManagementApiRecordVariableBOMProductionResponseWithDefaults

`func NewProductionOperationsManagementApiRecordVariableBOMProductionResponseWithDefaults() *ProductionOperationsManagementApiRecordVariableBOMProductionResponse`

NewProductionOperationsManagementApiRecordVariableBOMProductionResponseWithDefaults instantiates a new ProductionOperationsManagementApiRecordVariableBOMProductionResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSerialNo

`func (o *ProductionOperationsManagementApiRecordVariableBOMProductionResponse) GetSerialNo() string`

GetSerialNo returns the SerialNo field if non-nil, zero value otherwise.

### GetSerialNoOk

`func (o *ProductionOperationsManagementApiRecordVariableBOMProductionResponse) GetSerialNoOk() (*string, bool)`

GetSerialNoOk returns a tuple with the SerialNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSerialNo

`func (o *ProductionOperationsManagementApiRecordVariableBOMProductionResponse) SetSerialNo(v string)`

SetSerialNo sets SerialNo field to given value.

### HasSerialNo

`func (o *ProductionOperationsManagementApiRecordVariableBOMProductionResponse) HasSerialNo() bool`

HasSerialNo returns a boolean if a field has been set.

### GetQuantity

`func (o *ProductionOperationsManagementApiRecordVariableBOMProductionResponse) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *ProductionOperationsManagementApiRecordVariableBOMProductionResponse) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *ProductionOperationsManagementApiRecordVariableBOMProductionResponse) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *ProductionOperationsManagementApiRecordVariableBOMProductionResponse) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetSourceComponentQuantities

`func (o *ProductionOperationsManagementApiRecordVariableBOMProductionResponse) GetSourceComponentQuantities() []SourceComponentQuantitiesItem1`

GetSourceComponentQuantities returns the SourceComponentQuantities field if non-nil, zero value otherwise.

### GetSourceComponentQuantitiesOk

`func (o *ProductionOperationsManagementApiRecordVariableBOMProductionResponse) GetSourceComponentQuantitiesOk() (*[]SourceComponentQuantitiesItem1, bool)`

GetSourceComponentQuantitiesOk returns a tuple with the SourceComponentQuantities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceComponentQuantities

`func (o *ProductionOperationsManagementApiRecordVariableBOMProductionResponse) SetSourceComponentQuantities(v []SourceComponentQuantitiesItem1)`

SetSourceComponentQuantities sets SourceComponentQuantities field to given value.

### HasSourceComponentQuantities

`func (o *ProductionOperationsManagementApiRecordVariableBOMProductionResponse) HasSourceComponentQuantities() bool`

HasSourceComponentQuantities returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


