# JustInSequenceApiLoadJISRackResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | The ID of the truck to which sequenced racks will be loaded. | [optional] 
**TrailerNumber** | Pointer to **string** | The trailer number to which a rack can be assigned. If a truck with the trailer number already exists, the rack will be loaded to that truck; otherwise, a new truck will be created with the specified trailer number. | [optional] 
**Status** | Pointer to **string** | Truck Status. | [optional] 
**TruckNumber** | Pointer to **string** | A Plex-generated unique number representing the Truck shipment. | [optional] 

## Methods

### NewJustInSequenceApiLoadJISRackResponse

`func NewJustInSequenceApiLoadJISRackResponse() *JustInSequenceApiLoadJISRackResponse`

NewJustInSequenceApiLoadJISRackResponse instantiates a new JustInSequenceApiLoadJISRackResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewJustInSequenceApiLoadJISRackResponseWithDefaults

`func NewJustInSequenceApiLoadJISRackResponseWithDefaults() *JustInSequenceApiLoadJISRackResponse`

NewJustInSequenceApiLoadJISRackResponseWithDefaults instantiates a new JustInSequenceApiLoadJISRackResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *JustInSequenceApiLoadJISRackResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *JustInSequenceApiLoadJISRackResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *JustInSequenceApiLoadJISRackResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *JustInSequenceApiLoadJISRackResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetTrailerNumber

`func (o *JustInSequenceApiLoadJISRackResponse) GetTrailerNumber() string`

GetTrailerNumber returns the TrailerNumber field if non-nil, zero value otherwise.

### GetTrailerNumberOk

`func (o *JustInSequenceApiLoadJISRackResponse) GetTrailerNumberOk() (*string, bool)`

GetTrailerNumberOk returns a tuple with the TrailerNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrailerNumber

`func (o *JustInSequenceApiLoadJISRackResponse) SetTrailerNumber(v string)`

SetTrailerNumber sets TrailerNumber field to given value.

### HasTrailerNumber

`func (o *JustInSequenceApiLoadJISRackResponse) HasTrailerNumber() bool`

HasTrailerNumber returns a boolean if a field has been set.

### GetStatus

`func (o *JustInSequenceApiLoadJISRackResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *JustInSequenceApiLoadJISRackResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *JustInSequenceApiLoadJISRackResponse) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *JustInSequenceApiLoadJISRackResponse) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetTruckNumber

`func (o *JustInSequenceApiLoadJISRackResponse) GetTruckNumber() string`

GetTruckNumber returns the TruckNumber field if non-nil, zero value otherwise.

### GetTruckNumberOk

`func (o *JustInSequenceApiLoadJISRackResponse) GetTruckNumberOk() (*string, bool)`

GetTruckNumberOk returns a tuple with the TruckNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckNumber

`func (o *JustInSequenceApiLoadJISRackResponse) SetTruckNumber(v string)`

SetTruckNumber sets TruckNumber field to given value.

### HasTruckNumber

`func (o *JustInSequenceApiLoadJISRackResponse) HasTruckNumber() bool`

HasTruckNumber returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


