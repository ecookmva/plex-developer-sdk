# JustInSequenceApiCreateJISRackRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | A unique identifier for the rack. This will be automatically generated if omitted from the request. | [optional] 
**RackSequenceNumber** | Pointer to **string** | The rack sequence number. | [optional] 
**LineSequenceSetupName** | Pointer to **string** | The rack&#39;s line sequence setup name. | [optional] 

## Methods

### NewJustInSequenceApiCreateJISRackRequest

`func NewJustInSequenceApiCreateJISRackRequest() *JustInSequenceApiCreateJISRackRequest`

NewJustInSequenceApiCreateJISRackRequest instantiates a new JustInSequenceApiCreateJISRackRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewJustInSequenceApiCreateJISRackRequestWithDefaults

`func NewJustInSequenceApiCreateJISRackRequestWithDefaults() *JustInSequenceApiCreateJISRackRequest`

NewJustInSequenceApiCreateJISRackRequestWithDefaults instantiates a new JustInSequenceApiCreateJISRackRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *JustInSequenceApiCreateJISRackRequest) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *JustInSequenceApiCreateJISRackRequest) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *JustInSequenceApiCreateJISRackRequest) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *JustInSequenceApiCreateJISRackRequest) HasId() bool`

HasId returns a boolean if a field has been set.

### GetRackSequenceNumber

`func (o *JustInSequenceApiCreateJISRackRequest) GetRackSequenceNumber() string`

GetRackSequenceNumber returns the RackSequenceNumber field if non-nil, zero value otherwise.

### GetRackSequenceNumberOk

`func (o *JustInSequenceApiCreateJISRackRequest) GetRackSequenceNumberOk() (*string, bool)`

GetRackSequenceNumberOk returns a tuple with the RackSequenceNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRackSequenceNumber

`func (o *JustInSequenceApiCreateJISRackRequest) SetRackSequenceNumber(v string)`

SetRackSequenceNumber sets RackSequenceNumber field to given value.

### HasRackSequenceNumber

`func (o *JustInSequenceApiCreateJISRackRequest) HasRackSequenceNumber() bool`

HasRackSequenceNumber returns a boolean if a field has been set.

### GetLineSequenceSetupName

`func (o *JustInSequenceApiCreateJISRackRequest) GetLineSequenceSetupName() string`

GetLineSequenceSetupName returns the LineSequenceSetupName field if non-nil, zero value otherwise.

### GetLineSequenceSetupNameOk

`func (o *JustInSequenceApiCreateJISRackRequest) GetLineSequenceSetupNameOk() (*string, bool)`

GetLineSequenceSetupNameOk returns a tuple with the LineSequenceSetupName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineSequenceSetupName

`func (o *JustInSequenceApiCreateJISRackRequest) SetLineSequenceSetupName(v string)`

SetLineSequenceSetupName sets LineSequenceSetupName field to given value.

### HasLineSequenceSetupName

`func (o *JustInSequenceApiCreateJISRackRequest) HasLineSequenceSetupName() bool`

HasLineSequenceSetupName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


