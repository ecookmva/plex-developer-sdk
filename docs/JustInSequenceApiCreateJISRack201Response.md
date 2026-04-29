# JustInSequenceApiCreateJISRack201Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | The ID of the sequenced rack. | [optional] 
**RackSequenceNumber** | Pointer to **string** | The rack sequence number. | [optional] 
**RackStatus** | Pointer to **string** | The status of the rack. | [optional] 
**MasterUnitNumber** | Pointer to **string** | The master unit number associated with the rack. | [optional] 
**LineSequenceSetupName** | Pointer to **string** | The rack&#39;s line sequence setup name. | [optional] 
**CreatedByAccountId** | Pointer to **string** | The account ID of the user who added the rack. | [optional] 
**CreatedDateTime** | Pointer to **time.Time** | The date and time on which the rack was added. | [optional] 
**ModifiedByAccountId** | Pointer to **string** | The account ID of the user who last modified the rack. | [optional] 
**ModifiedDateTime** | Pointer to **time.Time** | The date and time on which the rack was last modified. | [optional] 
**ReprintNeeded** | Pointer to **bool** | Determines whether the rack requires its paperwork to be reprinted. | [optional] 
**PrintedByAccountId** | Pointer to **string** | The account ID of the user who last printed the rack paperwork. | [optional] 
**PrintedDateTime** | Pointer to **time.Time** | The date and time on which the rack paperwork was last printed. | [optional] 
**TruckId** | Pointer to **string** | The unique ID of the truck associated with the rack. | [optional] 
**TruckNumber** | Pointer to **string** | The truck number associated with the rack. | [optional] 
**TrailerNumber** | Pointer to **string** | The trailer number of the rack&#39;s associated truck. | [optional] 
**LabelPrintedByAccountId** | Pointer to **string** | The account ID of the user who last printed the rack label. | [optional] 
**LabelPrintedDateTime** | Pointer to **time.Time** | The date and time on which the rack label was last printed. | [optional] 

## Methods

### NewJustInSequenceApiCreateJISRack201Response

`func NewJustInSequenceApiCreateJISRack201Response() *JustInSequenceApiCreateJISRack201Response`

NewJustInSequenceApiCreateJISRack201Response instantiates a new JustInSequenceApiCreateJISRack201Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewJustInSequenceApiCreateJISRack201ResponseWithDefaults

`func NewJustInSequenceApiCreateJISRack201ResponseWithDefaults() *JustInSequenceApiCreateJISRack201Response`

NewJustInSequenceApiCreateJISRack201ResponseWithDefaults instantiates a new JustInSequenceApiCreateJISRack201Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *JustInSequenceApiCreateJISRack201Response) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *JustInSequenceApiCreateJISRack201Response) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *JustInSequenceApiCreateJISRack201Response) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *JustInSequenceApiCreateJISRack201Response) HasId() bool`

HasId returns a boolean if a field has been set.

### GetRackSequenceNumber

`func (o *JustInSequenceApiCreateJISRack201Response) GetRackSequenceNumber() string`

GetRackSequenceNumber returns the RackSequenceNumber field if non-nil, zero value otherwise.

### GetRackSequenceNumberOk

`func (o *JustInSequenceApiCreateJISRack201Response) GetRackSequenceNumberOk() (*string, bool)`

GetRackSequenceNumberOk returns a tuple with the RackSequenceNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRackSequenceNumber

`func (o *JustInSequenceApiCreateJISRack201Response) SetRackSequenceNumber(v string)`

SetRackSequenceNumber sets RackSequenceNumber field to given value.

### HasRackSequenceNumber

`func (o *JustInSequenceApiCreateJISRack201Response) HasRackSequenceNumber() bool`

HasRackSequenceNumber returns a boolean if a field has been set.

### GetRackStatus

`func (o *JustInSequenceApiCreateJISRack201Response) GetRackStatus() string`

GetRackStatus returns the RackStatus field if non-nil, zero value otherwise.

### GetRackStatusOk

`func (o *JustInSequenceApiCreateJISRack201Response) GetRackStatusOk() (*string, bool)`

GetRackStatusOk returns a tuple with the RackStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRackStatus

`func (o *JustInSequenceApiCreateJISRack201Response) SetRackStatus(v string)`

SetRackStatus sets RackStatus field to given value.

### HasRackStatus

`func (o *JustInSequenceApiCreateJISRack201Response) HasRackStatus() bool`

HasRackStatus returns a boolean if a field has been set.

### GetMasterUnitNumber

`func (o *JustInSequenceApiCreateJISRack201Response) GetMasterUnitNumber() string`

GetMasterUnitNumber returns the MasterUnitNumber field if non-nil, zero value otherwise.

### GetMasterUnitNumberOk

`func (o *JustInSequenceApiCreateJISRack201Response) GetMasterUnitNumberOk() (*string, bool)`

GetMasterUnitNumberOk returns a tuple with the MasterUnitNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMasterUnitNumber

`func (o *JustInSequenceApiCreateJISRack201Response) SetMasterUnitNumber(v string)`

SetMasterUnitNumber sets MasterUnitNumber field to given value.

### HasMasterUnitNumber

`func (o *JustInSequenceApiCreateJISRack201Response) HasMasterUnitNumber() bool`

HasMasterUnitNumber returns a boolean if a field has been set.

### GetLineSequenceSetupName

`func (o *JustInSequenceApiCreateJISRack201Response) GetLineSequenceSetupName() string`

GetLineSequenceSetupName returns the LineSequenceSetupName field if non-nil, zero value otherwise.

### GetLineSequenceSetupNameOk

`func (o *JustInSequenceApiCreateJISRack201Response) GetLineSequenceSetupNameOk() (*string, bool)`

GetLineSequenceSetupNameOk returns a tuple with the LineSequenceSetupName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineSequenceSetupName

`func (o *JustInSequenceApiCreateJISRack201Response) SetLineSequenceSetupName(v string)`

SetLineSequenceSetupName sets LineSequenceSetupName field to given value.

### HasLineSequenceSetupName

`func (o *JustInSequenceApiCreateJISRack201Response) HasLineSequenceSetupName() bool`

HasLineSequenceSetupName returns a boolean if a field has been set.

### GetCreatedByAccountId

`func (o *JustInSequenceApiCreateJISRack201Response) GetCreatedByAccountId() string`

GetCreatedByAccountId returns the CreatedByAccountId field if non-nil, zero value otherwise.

### GetCreatedByAccountIdOk

`func (o *JustInSequenceApiCreateJISRack201Response) GetCreatedByAccountIdOk() (*string, bool)`

GetCreatedByAccountIdOk returns a tuple with the CreatedByAccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedByAccountId

`func (o *JustInSequenceApiCreateJISRack201Response) SetCreatedByAccountId(v string)`

SetCreatedByAccountId sets CreatedByAccountId field to given value.

### HasCreatedByAccountId

`func (o *JustInSequenceApiCreateJISRack201Response) HasCreatedByAccountId() bool`

HasCreatedByAccountId returns a boolean if a field has been set.

### GetCreatedDateTime

`func (o *JustInSequenceApiCreateJISRack201Response) GetCreatedDateTime() time.Time`

GetCreatedDateTime returns the CreatedDateTime field if non-nil, zero value otherwise.

### GetCreatedDateTimeOk

`func (o *JustInSequenceApiCreateJISRack201Response) GetCreatedDateTimeOk() (*time.Time, bool)`

GetCreatedDateTimeOk returns a tuple with the CreatedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDateTime

`func (o *JustInSequenceApiCreateJISRack201Response) SetCreatedDateTime(v time.Time)`

SetCreatedDateTime sets CreatedDateTime field to given value.

### HasCreatedDateTime

`func (o *JustInSequenceApiCreateJISRack201Response) HasCreatedDateTime() bool`

HasCreatedDateTime returns a boolean if a field has been set.

### GetModifiedByAccountId

`func (o *JustInSequenceApiCreateJISRack201Response) GetModifiedByAccountId() string`

GetModifiedByAccountId returns the ModifiedByAccountId field if non-nil, zero value otherwise.

### GetModifiedByAccountIdOk

`func (o *JustInSequenceApiCreateJISRack201Response) GetModifiedByAccountIdOk() (*string, bool)`

GetModifiedByAccountIdOk returns a tuple with the ModifiedByAccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedByAccountId

`func (o *JustInSequenceApiCreateJISRack201Response) SetModifiedByAccountId(v string)`

SetModifiedByAccountId sets ModifiedByAccountId field to given value.

### HasModifiedByAccountId

`func (o *JustInSequenceApiCreateJISRack201Response) HasModifiedByAccountId() bool`

HasModifiedByAccountId returns a boolean if a field has been set.

### GetModifiedDateTime

`func (o *JustInSequenceApiCreateJISRack201Response) GetModifiedDateTime() time.Time`

GetModifiedDateTime returns the ModifiedDateTime field if non-nil, zero value otherwise.

### GetModifiedDateTimeOk

`func (o *JustInSequenceApiCreateJISRack201Response) GetModifiedDateTimeOk() (*time.Time, bool)`

GetModifiedDateTimeOk returns a tuple with the ModifiedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDateTime

`func (o *JustInSequenceApiCreateJISRack201Response) SetModifiedDateTime(v time.Time)`

SetModifiedDateTime sets ModifiedDateTime field to given value.

### HasModifiedDateTime

`func (o *JustInSequenceApiCreateJISRack201Response) HasModifiedDateTime() bool`

HasModifiedDateTime returns a boolean if a field has been set.

### GetReprintNeeded

`func (o *JustInSequenceApiCreateJISRack201Response) GetReprintNeeded() bool`

GetReprintNeeded returns the ReprintNeeded field if non-nil, zero value otherwise.

### GetReprintNeededOk

`func (o *JustInSequenceApiCreateJISRack201Response) GetReprintNeededOk() (*bool, bool)`

GetReprintNeededOk returns a tuple with the ReprintNeeded field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReprintNeeded

`func (o *JustInSequenceApiCreateJISRack201Response) SetReprintNeeded(v bool)`

SetReprintNeeded sets ReprintNeeded field to given value.

### HasReprintNeeded

`func (o *JustInSequenceApiCreateJISRack201Response) HasReprintNeeded() bool`

HasReprintNeeded returns a boolean if a field has been set.

### GetPrintedByAccountId

`func (o *JustInSequenceApiCreateJISRack201Response) GetPrintedByAccountId() string`

GetPrintedByAccountId returns the PrintedByAccountId field if non-nil, zero value otherwise.

### GetPrintedByAccountIdOk

`func (o *JustInSequenceApiCreateJISRack201Response) GetPrintedByAccountIdOk() (*string, bool)`

GetPrintedByAccountIdOk returns a tuple with the PrintedByAccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrintedByAccountId

`func (o *JustInSequenceApiCreateJISRack201Response) SetPrintedByAccountId(v string)`

SetPrintedByAccountId sets PrintedByAccountId field to given value.

### HasPrintedByAccountId

`func (o *JustInSequenceApiCreateJISRack201Response) HasPrintedByAccountId() bool`

HasPrintedByAccountId returns a boolean if a field has been set.

### GetPrintedDateTime

`func (o *JustInSequenceApiCreateJISRack201Response) GetPrintedDateTime() time.Time`

GetPrintedDateTime returns the PrintedDateTime field if non-nil, zero value otherwise.

### GetPrintedDateTimeOk

`func (o *JustInSequenceApiCreateJISRack201Response) GetPrintedDateTimeOk() (*time.Time, bool)`

GetPrintedDateTimeOk returns a tuple with the PrintedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrintedDateTime

`func (o *JustInSequenceApiCreateJISRack201Response) SetPrintedDateTime(v time.Time)`

SetPrintedDateTime sets PrintedDateTime field to given value.

### HasPrintedDateTime

`func (o *JustInSequenceApiCreateJISRack201Response) HasPrintedDateTime() bool`

HasPrintedDateTime returns a boolean if a field has been set.

### GetTruckId

`func (o *JustInSequenceApiCreateJISRack201Response) GetTruckId() string`

GetTruckId returns the TruckId field if non-nil, zero value otherwise.

### GetTruckIdOk

`func (o *JustInSequenceApiCreateJISRack201Response) GetTruckIdOk() (*string, bool)`

GetTruckIdOk returns a tuple with the TruckId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckId

`func (o *JustInSequenceApiCreateJISRack201Response) SetTruckId(v string)`

SetTruckId sets TruckId field to given value.

### HasTruckId

`func (o *JustInSequenceApiCreateJISRack201Response) HasTruckId() bool`

HasTruckId returns a boolean if a field has been set.

### GetTruckNumber

`func (o *JustInSequenceApiCreateJISRack201Response) GetTruckNumber() string`

GetTruckNumber returns the TruckNumber field if non-nil, zero value otherwise.

### GetTruckNumberOk

`func (o *JustInSequenceApiCreateJISRack201Response) GetTruckNumberOk() (*string, bool)`

GetTruckNumberOk returns a tuple with the TruckNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckNumber

`func (o *JustInSequenceApiCreateJISRack201Response) SetTruckNumber(v string)`

SetTruckNumber sets TruckNumber field to given value.

### HasTruckNumber

`func (o *JustInSequenceApiCreateJISRack201Response) HasTruckNumber() bool`

HasTruckNumber returns a boolean if a field has been set.

### GetTrailerNumber

`func (o *JustInSequenceApiCreateJISRack201Response) GetTrailerNumber() string`

GetTrailerNumber returns the TrailerNumber field if non-nil, zero value otherwise.

### GetTrailerNumberOk

`func (o *JustInSequenceApiCreateJISRack201Response) GetTrailerNumberOk() (*string, bool)`

GetTrailerNumberOk returns a tuple with the TrailerNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrailerNumber

`func (o *JustInSequenceApiCreateJISRack201Response) SetTrailerNumber(v string)`

SetTrailerNumber sets TrailerNumber field to given value.

### HasTrailerNumber

`func (o *JustInSequenceApiCreateJISRack201Response) HasTrailerNumber() bool`

HasTrailerNumber returns a boolean if a field has been set.

### GetLabelPrintedByAccountId

`func (o *JustInSequenceApiCreateJISRack201Response) GetLabelPrintedByAccountId() string`

GetLabelPrintedByAccountId returns the LabelPrintedByAccountId field if non-nil, zero value otherwise.

### GetLabelPrintedByAccountIdOk

`func (o *JustInSequenceApiCreateJISRack201Response) GetLabelPrintedByAccountIdOk() (*string, bool)`

GetLabelPrintedByAccountIdOk returns a tuple with the LabelPrintedByAccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabelPrintedByAccountId

`func (o *JustInSequenceApiCreateJISRack201Response) SetLabelPrintedByAccountId(v string)`

SetLabelPrintedByAccountId sets LabelPrintedByAccountId field to given value.

### HasLabelPrintedByAccountId

`func (o *JustInSequenceApiCreateJISRack201Response) HasLabelPrintedByAccountId() bool`

HasLabelPrintedByAccountId returns a boolean if a field has been set.

### GetLabelPrintedDateTime

`func (o *JustInSequenceApiCreateJISRack201Response) GetLabelPrintedDateTime() time.Time`

GetLabelPrintedDateTime returns the LabelPrintedDateTime field if non-nil, zero value otherwise.

### GetLabelPrintedDateTimeOk

`func (o *JustInSequenceApiCreateJISRack201Response) GetLabelPrintedDateTimeOk() (*time.Time, bool)`

GetLabelPrintedDateTimeOk returns a tuple with the LabelPrintedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabelPrintedDateTime

`func (o *JustInSequenceApiCreateJISRack201Response) SetLabelPrintedDateTime(v time.Time)`

SetLabelPrintedDateTime sets LabelPrintedDateTime field to given value.

### HasLabelPrintedDateTime

`func (o *JustInSequenceApiCreateJISRack201Response) HasLabelPrintedDateTime() bool`

HasLabelPrintedDateTime returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


