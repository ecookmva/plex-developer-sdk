# ProcessRoutingsApiUpdatePartOperationRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OperationId** | Pointer to **string** | A unique identifier to an operation. | [optional] 
**OperationNumber** | Pointer to **int32** | The order this operation is executed in, usually added in increments of 10 to leave room for inserting additional operations. | [optional] 
**Multiple** | Pointer to **int32** | The operation multiple. | [optional] 
**SubOperation** | Pointer to **bool** | Refers to if the operation is encapsulated within another operation. | [optional] 
**Shippable** | Pointer to **bool** | If shipping is allowed for operation on this Part Operation. The part should have at least one shippable operation. If not, MRP calculations are impacted. | [optional] 
**NetWeight** | Pointer to **float64** | The part weight per inventory unit at this operation. This is used in calculations for valuing inventory, standard costing, and shipping documents for subcontract WIP operations. | [optional] 
**Type** | Pointer to **string** | The part operation type. | [optional] 

## Methods

### NewProcessRoutingsApiUpdatePartOperationRequest

`func NewProcessRoutingsApiUpdatePartOperationRequest() *ProcessRoutingsApiUpdatePartOperationRequest`

NewProcessRoutingsApiUpdatePartOperationRequest instantiates a new ProcessRoutingsApiUpdatePartOperationRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProcessRoutingsApiUpdatePartOperationRequestWithDefaults

`func NewProcessRoutingsApiUpdatePartOperationRequestWithDefaults() *ProcessRoutingsApiUpdatePartOperationRequest`

NewProcessRoutingsApiUpdatePartOperationRequestWithDefaults instantiates a new ProcessRoutingsApiUpdatePartOperationRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOperationId

`func (o *ProcessRoutingsApiUpdatePartOperationRequest) GetOperationId() string`

GetOperationId returns the OperationId field if non-nil, zero value otherwise.

### GetOperationIdOk

`func (o *ProcessRoutingsApiUpdatePartOperationRequest) GetOperationIdOk() (*string, bool)`

GetOperationIdOk returns a tuple with the OperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationId

`func (o *ProcessRoutingsApiUpdatePartOperationRequest) SetOperationId(v string)`

SetOperationId sets OperationId field to given value.

### HasOperationId

`func (o *ProcessRoutingsApiUpdatePartOperationRequest) HasOperationId() bool`

HasOperationId returns a boolean if a field has been set.

### GetOperationNumber

`func (o *ProcessRoutingsApiUpdatePartOperationRequest) GetOperationNumber() int32`

GetOperationNumber returns the OperationNumber field if non-nil, zero value otherwise.

### GetOperationNumberOk

`func (o *ProcessRoutingsApiUpdatePartOperationRequest) GetOperationNumberOk() (*int32, bool)`

GetOperationNumberOk returns a tuple with the OperationNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationNumber

`func (o *ProcessRoutingsApiUpdatePartOperationRequest) SetOperationNumber(v int32)`

SetOperationNumber sets OperationNumber field to given value.

### HasOperationNumber

`func (o *ProcessRoutingsApiUpdatePartOperationRequest) HasOperationNumber() bool`

HasOperationNumber returns a boolean if a field has been set.

### GetMultiple

`func (o *ProcessRoutingsApiUpdatePartOperationRequest) GetMultiple() int32`

GetMultiple returns the Multiple field if non-nil, zero value otherwise.

### GetMultipleOk

`func (o *ProcessRoutingsApiUpdatePartOperationRequest) GetMultipleOk() (*int32, bool)`

GetMultipleOk returns a tuple with the Multiple field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMultiple

`func (o *ProcessRoutingsApiUpdatePartOperationRequest) SetMultiple(v int32)`

SetMultiple sets Multiple field to given value.

### HasMultiple

`func (o *ProcessRoutingsApiUpdatePartOperationRequest) HasMultiple() bool`

HasMultiple returns a boolean if a field has been set.

### GetSubOperation

`func (o *ProcessRoutingsApiUpdatePartOperationRequest) GetSubOperation() bool`

GetSubOperation returns the SubOperation field if non-nil, zero value otherwise.

### GetSubOperationOk

`func (o *ProcessRoutingsApiUpdatePartOperationRequest) GetSubOperationOk() (*bool, bool)`

GetSubOperationOk returns a tuple with the SubOperation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubOperation

`func (o *ProcessRoutingsApiUpdatePartOperationRequest) SetSubOperation(v bool)`

SetSubOperation sets SubOperation field to given value.

### HasSubOperation

`func (o *ProcessRoutingsApiUpdatePartOperationRequest) HasSubOperation() bool`

HasSubOperation returns a boolean if a field has been set.

### GetShippable

`func (o *ProcessRoutingsApiUpdatePartOperationRequest) GetShippable() bool`

GetShippable returns the Shippable field if non-nil, zero value otherwise.

### GetShippableOk

`func (o *ProcessRoutingsApiUpdatePartOperationRequest) GetShippableOk() (*bool, bool)`

GetShippableOk returns a tuple with the Shippable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippable

`func (o *ProcessRoutingsApiUpdatePartOperationRequest) SetShippable(v bool)`

SetShippable sets Shippable field to given value.

### HasShippable

`func (o *ProcessRoutingsApiUpdatePartOperationRequest) HasShippable() bool`

HasShippable returns a boolean if a field has been set.

### GetNetWeight

`func (o *ProcessRoutingsApiUpdatePartOperationRequest) GetNetWeight() float64`

GetNetWeight returns the NetWeight field if non-nil, zero value otherwise.

### GetNetWeightOk

`func (o *ProcessRoutingsApiUpdatePartOperationRequest) GetNetWeightOk() (*float64, bool)`

GetNetWeightOk returns a tuple with the NetWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetWeight

`func (o *ProcessRoutingsApiUpdatePartOperationRequest) SetNetWeight(v float64)`

SetNetWeight sets NetWeight field to given value.

### HasNetWeight

`func (o *ProcessRoutingsApiUpdatePartOperationRequest) HasNetWeight() bool`

HasNetWeight returns a boolean if a field has been set.

### GetType

`func (o *ProcessRoutingsApiUpdatePartOperationRequest) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ProcessRoutingsApiUpdatePartOperationRequest) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ProcessRoutingsApiUpdatePartOperationRequest) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *ProcessRoutingsApiUpdatePartOperationRequest) HasType() bool`

HasType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


