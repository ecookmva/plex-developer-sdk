# ProcessRoutingsApiCreatePartOperationRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PartId** | Pointer to **string** | A unique identifier to a part. | [optional] 
**OperationId** | Pointer to **string** | A unique identifier to an operation. | [optional] 
**Type** | Pointer to **string** | The Part Operation type. | [optional] 
**OperationNumber** | Pointer to **int32** | The order this operation is executed in, usually added in increments of 10 to leave room for inserting additional operations. | [optional] 
**SubOperation** | Pointer to **bool** | Refers to if the operation is encapsulated within another operation. | [optional] 
**Shippable** | Pointer to **bool** | If shipping is allowed for operation on this routing. The part should have at least one shippable operation. If not, MRP calculations are impacted. | [optional] 
**NetWeight** | Pointer to **float64** | The part weight per inventory unit at this operation. This is used in calculations for valuing inventory, standard costing, and shipping documents for subcontract WIP operations. | [optional] 
**StandardQuantity** | Pointer to **float64** | Standard pack size for the process routing. | [optional] 

## Methods

### NewProcessRoutingsApiCreatePartOperationRequest

`func NewProcessRoutingsApiCreatePartOperationRequest() *ProcessRoutingsApiCreatePartOperationRequest`

NewProcessRoutingsApiCreatePartOperationRequest instantiates a new ProcessRoutingsApiCreatePartOperationRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProcessRoutingsApiCreatePartOperationRequestWithDefaults

`func NewProcessRoutingsApiCreatePartOperationRequestWithDefaults() *ProcessRoutingsApiCreatePartOperationRequest`

NewProcessRoutingsApiCreatePartOperationRequestWithDefaults instantiates a new ProcessRoutingsApiCreatePartOperationRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPartId

`func (o *ProcessRoutingsApiCreatePartOperationRequest) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *ProcessRoutingsApiCreatePartOperationRequest) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *ProcessRoutingsApiCreatePartOperationRequest) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *ProcessRoutingsApiCreatePartOperationRequest) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetOperationId

`func (o *ProcessRoutingsApiCreatePartOperationRequest) GetOperationId() string`

GetOperationId returns the OperationId field if non-nil, zero value otherwise.

### GetOperationIdOk

`func (o *ProcessRoutingsApiCreatePartOperationRequest) GetOperationIdOk() (*string, bool)`

GetOperationIdOk returns a tuple with the OperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationId

`func (o *ProcessRoutingsApiCreatePartOperationRequest) SetOperationId(v string)`

SetOperationId sets OperationId field to given value.

### HasOperationId

`func (o *ProcessRoutingsApiCreatePartOperationRequest) HasOperationId() bool`

HasOperationId returns a boolean if a field has been set.

### GetType

`func (o *ProcessRoutingsApiCreatePartOperationRequest) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ProcessRoutingsApiCreatePartOperationRequest) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ProcessRoutingsApiCreatePartOperationRequest) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *ProcessRoutingsApiCreatePartOperationRequest) HasType() bool`

HasType returns a boolean if a field has been set.

### GetOperationNumber

`func (o *ProcessRoutingsApiCreatePartOperationRequest) GetOperationNumber() int32`

GetOperationNumber returns the OperationNumber field if non-nil, zero value otherwise.

### GetOperationNumberOk

`func (o *ProcessRoutingsApiCreatePartOperationRequest) GetOperationNumberOk() (*int32, bool)`

GetOperationNumberOk returns a tuple with the OperationNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationNumber

`func (o *ProcessRoutingsApiCreatePartOperationRequest) SetOperationNumber(v int32)`

SetOperationNumber sets OperationNumber field to given value.

### HasOperationNumber

`func (o *ProcessRoutingsApiCreatePartOperationRequest) HasOperationNumber() bool`

HasOperationNumber returns a boolean if a field has been set.

### GetSubOperation

`func (o *ProcessRoutingsApiCreatePartOperationRequest) GetSubOperation() bool`

GetSubOperation returns the SubOperation field if non-nil, zero value otherwise.

### GetSubOperationOk

`func (o *ProcessRoutingsApiCreatePartOperationRequest) GetSubOperationOk() (*bool, bool)`

GetSubOperationOk returns a tuple with the SubOperation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubOperation

`func (o *ProcessRoutingsApiCreatePartOperationRequest) SetSubOperation(v bool)`

SetSubOperation sets SubOperation field to given value.

### HasSubOperation

`func (o *ProcessRoutingsApiCreatePartOperationRequest) HasSubOperation() bool`

HasSubOperation returns a boolean if a field has been set.

### GetShippable

`func (o *ProcessRoutingsApiCreatePartOperationRequest) GetShippable() bool`

GetShippable returns the Shippable field if non-nil, zero value otherwise.

### GetShippableOk

`func (o *ProcessRoutingsApiCreatePartOperationRequest) GetShippableOk() (*bool, bool)`

GetShippableOk returns a tuple with the Shippable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippable

`func (o *ProcessRoutingsApiCreatePartOperationRequest) SetShippable(v bool)`

SetShippable sets Shippable field to given value.

### HasShippable

`func (o *ProcessRoutingsApiCreatePartOperationRequest) HasShippable() bool`

HasShippable returns a boolean if a field has been set.

### GetNetWeight

`func (o *ProcessRoutingsApiCreatePartOperationRequest) GetNetWeight() float64`

GetNetWeight returns the NetWeight field if non-nil, zero value otherwise.

### GetNetWeightOk

`func (o *ProcessRoutingsApiCreatePartOperationRequest) GetNetWeightOk() (*float64, bool)`

GetNetWeightOk returns a tuple with the NetWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetWeight

`func (o *ProcessRoutingsApiCreatePartOperationRequest) SetNetWeight(v float64)`

SetNetWeight sets NetWeight field to given value.

### HasNetWeight

`func (o *ProcessRoutingsApiCreatePartOperationRequest) HasNetWeight() bool`

HasNetWeight returns a boolean if a field has been set.

### GetStandardQuantity

`func (o *ProcessRoutingsApiCreatePartOperationRequest) GetStandardQuantity() float64`

GetStandardQuantity returns the StandardQuantity field if non-nil, zero value otherwise.

### GetStandardQuantityOk

`func (o *ProcessRoutingsApiCreatePartOperationRequest) GetStandardQuantityOk() (*float64, bool)`

GetStandardQuantityOk returns a tuple with the StandardQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStandardQuantity

`func (o *ProcessRoutingsApiCreatePartOperationRequest) SetStandardQuantity(v float64)`

SetStandardQuantity sets StandardQuantity field to given value.

### HasStandardQuantity

`func (o *ProcessRoutingsApiCreatePartOperationRequest) HasStandardQuantity() bool`

HasStandardQuantity returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


