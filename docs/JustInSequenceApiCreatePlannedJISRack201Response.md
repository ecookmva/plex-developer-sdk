# JustInSequenceApiCreatePlannedJISRack201Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RackId** | Pointer to **string** | The ID of the sequenced rack. | [optional] 
**RackSequenceNumber** | Pointer to **string** | The rack sequence number. | [optional] 
**RackStatus** | Pointer to **string** | The rack status. | [optional] 
**MasterUnitNumber** | Pointer to **string** | The master unit number. | [optional] 
**LineSequenceSetupName** | Pointer to **string** | The line sequence setup name. | [optional] 
**Kits** | Pointer to [**[]KitsItem1**](KitsItem1.md) | The kits associated with the sequenced rack. | [optional] 

## Methods

### NewJustInSequenceApiCreatePlannedJISRack201Response

`func NewJustInSequenceApiCreatePlannedJISRack201Response() *JustInSequenceApiCreatePlannedJISRack201Response`

NewJustInSequenceApiCreatePlannedJISRack201Response instantiates a new JustInSequenceApiCreatePlannedJISRack201Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewJustInSequenceApiCreatePlannedJISRack201ResponseWithDefaults

`func NewJustInSequenceApiCreatePlannedJISRack201ResponseWithDefaults() *JustInSequenceApiCreatePlannedJISRack201Response`

NewJustInSequenceApiCreatePlannedJISRack201ResponseWithDefaults instantiates a new JustInSequenceApiCreatePlannedJISRack201Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRackId

`func (o *JustInSequenceApiCreatePlannedJISRack201Response) GetRackId() string`

GetRackId returns the RackId field if non-nil, zero value otherwise.

### GetRackIdOk

`func (o *JustInSequenceApiCreatePlannedJISRack201Response) GetRackIdOk() (*string, bool)`

GetRackIdOk returns a tuple with the RackId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRackId

`func (o *JustInSequenceApiCreatePlannedJISRack201Response) SetRackId(v string)`

SetRackId sets RackId field to given value.

### HasRackId

`func (o *JustInSequenceApiCreatePlannedJISRack201Response) HasRackId() bool`

HasRackId returns a boolean if a field has been set.

### GetRackSequenceNumber

`func (o *JustInSequenceApiCreatePlannedJISRack201Response) GetRackSequenceNumber() string`

GetRackSequenceNumber returns the RackSequenceNumber field if non-nil, zero value otherwise.

### GetRackSequenceNumberOk

`func (o *JustInSequenceApiCreatePlannedJISRack201Response) GetRackSequenceNumberOk() (*string, bool)`

GetRackSequenceNumberOk returns a tuple with the RackSequenceNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRackSequenceNumber

`func (o *JustInSequenceApiCreatePlannedJISRack201Response) SetRackSequenceNumber(v string)`

SetRackSequenceNumber sets RackSequenceNumber field to given value.

### HasRackSequenceNumber

`func (o *JustInSequenceApiCreatePlannedJISRack201Response) HasRackSequenceNumber() bool`

HasRackSequenceNumber returns a boolean if a field has been set.

### GetRackStatus

`func (o *JustInSequenceApiCreatePlannedJISRack201Response) GetRackStatus() string`

GetRackStatus returns the RackStatus field if non-nil, zero value otherwise.

### GetRackStatusOk

`func (o *JustInSequenceApiCreatePlannedJISRack201Response) GetRackStatusOk() (*string, bool)`

GetRackStatusOk returns a tuple with the RackStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRackStatus

`func (o *JustInSequenceApiCreatePlannedJISRack201Response) SetRackStatus(v string)`

SetRackStatus sets RackStatus field to given value.

### HasRackStatus

`func (o *JustInSequenceApiCreatePlannedJISRack201Response) HasRackStatus() bool`

HasRackStatus returns a boolean if a field has been set.

### GetMasterUnitNumber

`func (o *JustInSequenceApiCreatePlannedJISRack201Response) GetMasterUnitNumber() string`

GetMasterUnitNumber returns the MasterUnitNumber field if non-nil, zero value otherwise.

### GetMasterUnitNumberOk

`func (o *JustInSequenceApiCreatePlannedJISRack201Response) GetMasterUnitNumberOk() (*string, bool)`

GetMasterUnitNumberOk returns a tuple with the MasterUnitNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMasterUnitNumber

`func (o *JustInSequenceApiCreatePlannedJISRack201Response) SetMasterUnitNumber(v string)`

SetMasterUnitNumber sets MasterUnitNumber field to given value.

### HasMasterUnitNumber

`func (o *JustInSequenceApiCreatePlannedJISRack201Response) HasMasterUnitNumber() bool`

HasMasterUnitNumber returns a boolean if a field has been set.

### GetLineSequenceSetupName

`func (o *JustInSequenceApiCreatePlannedJISRack201Response) GetLineSequenceSetupName() string`

GetLineSequenceSetupName returns the LineSequenceSetupName field if non-nil, zero value otherwise.

### GetLineSequenceSetupNameOk

`func (o *JustInSequenceApiCreatePlannedJISRack201Response) GetLineSequenceSetupNameOk() (*string, bool)`

GetLineSequenceSetupNameOk returns a tuple with the LineSequenceSetupName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineSequenceSetupName

`func (o *JustInSequenceApiCreatePlannedJISRack201Response) SetLineSequenceSetupName(v string)`

SetLineSequenceSetupName sets LineSequenceSetupName field to given value.

### HasLineSequenceSetupName

`func (o *JustInSequenceApiCreatePlannedJISRack201Response) HasLineSequenceSetupName() bool`

HasLineSequenceSetupName returns a boolean if a field has been set.

### GetKits

`func (o *JustInSequenceApiCreatePlannedJISRack201Response) GetKits() []KitsItem1`

GetKits returns the Kits field if non-nil, zero value otherwise.

### GetKitsOk

`func (o *JustInSequenceApiCreatePlannedJISRack201Response) GetKitsOk() (*[]KitsItem1, bool)`

GetKitsOk returns a tuple with the Kits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKits

`func (o *JustInSequenceApiCreatePlannedJISRack201Response) SetKits(v []KitsItem1)`

SetKits sets Kits field to given value.

### HasKits

`func (o *JustInSequenceApiCreatePlannedJISRack201Response) HasKits() bool`

HasKits returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


