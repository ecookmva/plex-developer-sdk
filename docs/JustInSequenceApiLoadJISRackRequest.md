# JustInSequenceApiLoadJISRackRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TruckId** | Pointer to **string** | The ID of the truck to which sequenced racks will be loaded. | [optional] 
**TrailerNumber** | Pointer to **string** | The trailer number to which a rack can be assigned. If a truck with the trailer number already exists, the rack will be loaded to that truck; otherwise, a new truck will be created with the specified trailer number. | [optional] 

## Methods

### NewJustInSequenceApiLoadJISRackRequest

`func NewJustInSequenceApiLoadJISRackRequest() *JustInSequenceApiLoadJISRackRequest`

NewJustInSequenceApiLoadJISRackRequest instantiates a new JustInSequenceApiLoadJISRackRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewJustInSequenceApiLoadJISRackRequestWithDefaults

`func NewJustInSequenceApiLoadJISRackRequestWithDefaults() *JustInSequenceApiLoadJISRackRequest`

NewJustInSequenceApiLoadJISRackRequestWithDefaults instantiates a new JustInSequenceApiLoadJISRackRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTruckId

`func (o *JustInSequenceApiLoadJISRackRequest) GetTruckId() string`

GetTruckId returns the TruckId field if non-nil, zero value otherwise.

### GetTruckIdOk

`func (o *JustInSequenceApiLoadJISRackRequest) GetTruckIdOk() (*string, bool)`

GetTruckIdOk returns a tuple with the TruckId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckId

`func (o *JustInSequenceApiLoadJISRackRequest) SetTruckId(v string)`

SetTruckId sets TruckId field to given value.

### HasTruckId

`func (o *JustInSequenceApiLoadJISRackRequest) HasTruckId() bool`

HasTruckId returns a boolean if a field has been set.

### GetTrailerNumber

`func (o *JustInSequenceApiLoadJISRackRequest) GetTrailerNumber() string`

GetTrailerNumber returns the TrailerNumber field if non-nil, zero value otherwise.

### GetTrailerNumberOk

`func (o *JustInSequenceApiLoadJISRackRequest) GetTrailerNumberOk() (*string, bool)`

GetTrailerNumberOk returns a tuple with the TrailerNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrailerNumber

`func (o *JustInSequenceApiLoadJISRackRequest) SetTrailerNumber(v string)`

SetTrailerNumber sets TrailerNumber field to given value.

### HasTrailerNumber

`func (o *JustInSequenceApiLoadJISRackRequest) HasTrailerNumber() bool`

HasTrailerNumber returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


