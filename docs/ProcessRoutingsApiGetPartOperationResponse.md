# ProcessRoutingsApiGetPartOperationResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | A unique identifier to a Part Operation. | [optional] 
**PartId** | Pointer to **string** | A unique identifier to a part. | [optional] 
**OperationId** | Pointer to **string** | A unique identifier to an operation. | [optional] 
**Type** | Pointer to **string** | The routing type. | [optional] 
**OperationNumber** | Pointer to **int32** | The order this operation is executed in, usually added in increments of 10 to leave room for inserting additional operations. | [optional] 
**Active** | Pointer to **bool** | If the Part Operation is activated for use in production. | [optional] 
**SubOperation** | Pointer to **bool** | Refers to if the operation is encapsulated within another operation. | [optional] 
**Shippable** | Pointer to **bool** | If shipping is allowed for operation on this Part Operation. The part should have at least one shippable operation. If not, MRP calculations are impacted. | [optional] 
**Multiple** | Pointer to **int32** | The number of output parts each input part produces. Used primarily for non-BOM operations where one part results in multiples of the next operation. | [optional] 
**NetWeight** | Pointer to **float64** | The part weight per inventory unit at this operation. This is used in calculations for valuing inventory, standard costing, and shipping documents for subcontract WIP operations. | [optional] 

## Methods

### NewProcessRoutingsApiGetPartOperationResponse

`func NewProcessRoutingsApiGetPartOperationResponse() *ProcessRoutingsApiGetPartOperationResponse`

NewProcessRoutingsApiGetPartOperationResponse instantiates a new ProcessRoutingsApiGetPartOperationResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProcessRoutingsApiGetPartOperationResponseWithDefaults

`func NewProcessRoutingsApiGetPartOperationResponseWithDefaults() *ProcessRoutingsApiGetPartOperationResponse`

NewProcessRoutingsApiGetPartOperationResponseWithDefaults instantiates a new ProcessRoutingsApiGetPartOperationResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ProcessRoutingsApiGetPartOperationResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ProcessRoutingsApiGetPartOperationResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ProcessRoutingsApiGetPartOperationResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *ProcessRoutingsApiGetPartOperationResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetPartId

`func (o *ProcessRoutingsApiGetPartOperationResponse) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *ProcessRoutingsApiGetPartOperationResponse) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *ProcessRoutingsApiGetPartOperationResponse) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *ProcessRoutingsApiGetPartOperationResponse) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetOperationId

`func (o *ProcessRoutingsApiGetPartOperationResponse) GetOperationId() string`

GetOperationId returns the OperationId field if non-nil, zero value otherwise.

### GetOperationIdOk

`func (o *ProcessRoutingsApiGetPartOperationResponse) GetOperationIdOk() (*string, bool)`

GetOperationIdOk returns a tuple with the OperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationId

`func (o *ProcessRoutingsApiGetPartOperationResponse) SetOperationId(v string)`

SetOperationId sets OperationId field to given value.

### HasOperationId

`func (o *ProcessRoutingsApiGetPartOperationResponse) HasOperationId() bool`

HasOperationId returns a boolean if a field has been set.

### GetType

`func (o *ProcessRoutingsApiGetPartOperationResponse) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ProcessRoutingsApiGetPartOperationResponse) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ProcessRoutingsApiGetPartOperationResponse) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *ProcessRoutingsApiGetPartOperationResponse) HasType() bool`

HasType returns a boolean if a field has been set.

### GetOperationNumber

`func (o *ProcessRoutingsApiGetPartOperationResponse) GetOperationNumber() int32`

GetOperationNumber returns the OperationNumber field if non-nil, zero value otherwise.

### GetOperationNumberOk

`func (o *ProcessRoutingsApiGetPartOperationResponse) GetOperationNumberOk() (*int32, bool)`

GetOperationNumberOk returns a tuple with the OperationNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationNumber

`func (o *ProcessRoutingsApiGetPartOperationResponse) SetOperationNumber(v int32)`

SetOperationNumber sets OperationNumber field to given value.

### HasOperationNumber

`func (o *ProcessRoutingsApiGetPartOperationResponse) HasOperationNumber() bool`

HasOperationNumber returns a boolean if a field has been set.

### GetActive

`func (o *ProcessRoutingsApiGetPartOperationResponse) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *ProcessRoutingsApiGetPartOperationResponse) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *ProcessRoutingsApiGetPartOperationResponse) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *ProcessRoutingsApiGetPartOperationResponse) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetSubOperation

`func (o *ProcessRoutingsApiGetPartOperationResponse) GetSubOperation() bool`

GetSubOperation returns the SubOperation field if non-nil, zero value otherwise.

### GetSubOperationOk

`func (o *ProcessRoutingsApiGetPartOperationResponse) GetSubOperationOk() (*bool, bool)`

GetSubOperationOk returns a tuple with the SubOperation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubOperation

`func (o *ProcessRoutingsApiGetPartOperationResponse) SetSubOperation(v bool)`

SetSubOperation sets SubOperation field to given value.

### HasSubOperation

`func (o *ProcessRoutingsApiGetPartOperationResponse) HasSubOperation() bool`

HasSubOperation returns a boolean if a field has been set.

### GetShippable

`func (o *ProcessRoutingsApiGetPartOperationResponse) GetShippable() bool`

GetShippable returns the Shippable field if non-nil, zero value otherwise.

### GetShippableOk

`func (o *ProcessRoutingsApiGetPartOperationResponse) GetShippableOk() (*bool, bool)`

GetShippableOk returns a tuple with the Shippable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippable

`func (o *ProcessRoutingsApiGetPartOperationResponse) SetShippable(v bool)`

SetShippable sets Shippable field to given value.

### HasShippable

`func (o *ProcessRoutingsApiGetPartOperationResponse) HasShippable() bool`

HasShippable returns a boolean if a field has been set.

### GetMultiple

`func (o *ProcessRoutingsApiGetPartOperationResponse) GetMultiple() int32`

GetMultiple returns the Multiple field if non-nil, zero value otherwise.

### GetMultipleOk

`func (o *ProcessRoutingsApiGetPartOperationResponse) GetMultipleOk() (*int32, bool)`

GetMultipleOk returns a tuple with the Multiple field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMultiple

`func (o *ProcessRoutingsApiGetPartOperationResponse) SetMultiple(v int32)`

SetMultiple sets Multiple field to given value.

### HasMultiple

`func (o *ProcessRoutingsApiGetPartOperationResponse) HasMultiple() bool`

HasMultiple returns a boolean if a field has been set.

### GetNetWeight

`func (o *ProcessRoutingsApiGetPartOperationResponse) GetNetWeight() float64`

GetNetWeight returns the NetWeight field if non-nil, zero value otherwise.

### GetNetWeightOk

`func (o *ProcessRoutingsApiGetPartOperationResponse) GetNetWeightOk() (*float64, bool)`

GetNetWeightOk returns a tuple with the NetWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetWeight

`func (o *ProcessRoutingsApiGetPartOperationResponse) SetNetWeight(v float64)`

SetNetWeight sets NetWeight field to given value.

### HasNetWeight

`func (o *ProcessRoutingsApiGetPartOperationResponse) HasNetWeight() bool`

HasNetWeight returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


