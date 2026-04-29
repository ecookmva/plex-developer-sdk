# JustInSequenceApiGetJISRackResponse

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

### NewJustInSequenceApiGetJISRackResponse

`func NewJustInSequenceApiGetJISRackResponse() *JustInSequenceApiGetJISRackResponse`

NewJustInSequenceApiGetJISRackResponse instantiates a new JustInSequenceApiGetJISRackResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewJustInSequenceApiGetJISRackResponseWithDefaults

`func NewJustInSequenceApiGetJISRackResponseWithDefaults() *JustInSequenceApiGetJISRackResponse`

NewJustInSequenceApiGetJISRackResponseWithDefaults instantiates a new JustInSequenceApiGetJISRackResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *JustInSequenceApiGetJISRackResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *JustInSequenceApiGetJISRackResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *JustInSequenceApiGetJISRackResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *JustInSequenceApiGetJISRackResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetRackSequenceNumber

`func (o *JustInSequenceApiGetJISRackResponse) GetRackSequenceNumber() string`

GetRackSequenceNumber returns the RackSequenceNumber field if non-nil, zero value otherwise.

### GetRackSequenceNumberOk

`func (o *JustInSequenceApiGetJISRackResponse) GetRackSequenceNumberOk() (*string, bool)`

GetRackSequenceNumberOk returns a tuple with the RackSequenceNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRackSequenceNumber

`func (o *JustInSequenceApiGetJISRackResponse) SetRackSequenceNumber(v string)`

SetRackSequenceNumber sets RackSequenceNumber field to given value.

### HasRackSequenceNumber

`func (o *JustInSequenceApiGetJISRackResponse) HasRackSequenceNumber() bool`

HasRackSequenceNumber returns a boolean if a field has been set.

### GetRackStatus

`func (o *JustInSequenceApiGetJISRackResponse) GetRackStatus() string`

GetRackStatus returns the RackStatus field if non-nil, zero value otherwise.

### GetRackStatusOk

`func (o *JustInSequenceApiGetJISRackResponse) GetRackStatusOk() (*string, bool)`

GetRackStatusOk returns a tuple with the RackStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRackStatus

`func (o *JustInSequenceApiGetJISRackResponse) SetRackStatus(v string)`

SetRackStatus sets RackStatus field to given value.

### HasRackStatus

`func (o *JustInSequenceApiGetJISRackResponse) HasRackStatus() bool`

HasRackStatus returns a boolean if a field has been set.

### GetMasterUnitNumber

`func (o *JustInSequenceApiGetJISRackResponse) GetMasterUnitNumber() string`

GetMasterUnitNumber returns the MasterUnitNumber field if non-nil, zero value otherwise.

### GetMasterUnitNumberOk

`func (o *JustInSequenceApiGetJISRackResponse) GetMasterUnitNumberOk() (*string, bool)`

GetMasterUnitNumberOk returns a tuple with the MasterUnitNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMasterUnitNumber

`func (o *JustInSequenceApiGetJISRackResponse) SetMasterUnitNumber(v string)`

SetMasterUnitNumber sets MasterUnitNumber field to given value.

### HasMasterUnitNumber

`func (o *JustInSequenceApiGetJISRackResponse) HasMasterUnitNumber() bool`

HasMasterUnitNumber returns a boolean if a field has been set.

### GetLineSequenceSetupName

`func (o *JustInSequenceApiGetJISRackResponse) GetLineSequenceSetupName() string`

GetLineSequenceSetupName returns the LineSequenceSetupName field if non-nil, zero value otherwise.

### GetLineSequenceSetupNameOk

`func (o *JustInSequenceApiGetJISRackResponse) GetLineSequenceSetupNameOk() (*string, bool)`

GetLineSequenceSetupNameOk returns a tuple with the LineSequenceSetupName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineSequenceSetupName

`func (o *JustInSequenceApiGetJISRackResponse) SetLineSequenceSetupName(v string)`

SetLineSequenceSetupName sets LineSequenceSetupName field to given value.

### HasLineSequenceSetupName

`func (o *JustInSequenceApiGetJISRackResponse) HasLineSequenceSetupName() bool`

HasLineSequenceSetupName returns a boolean if a field has been set.

### GetCreatedByAccountId

`func (o *JustInSequenceApiGetJISRackResponse) GetCreatedByAccountId() string`

GetCreatedByAccountId returns the CreatedByAccountId field if non-nil, zero value otherwise.

### GetCreatedByAccountIdOk

`func (o *JustInSequenceApiGetJISRackResponse) GetCreatedByAccountIdOk() (*string, bool)`

GetCreatedByAccountIdOk returns a tuple with the CreatedByAccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedByAccountId

`func (o *JustInSequenceApiGetJISRackResponse) SetCreatedByAccountId(v string)`

SetCreatedByAccountId sets CreatedByAccountId field to given value.

### HasCreatedByAccountId

`func (o *JustInSequenceApiGetJISRackResponse) HasCreatedByAccountId() bool`

HasCreatedByAccountId returns a boolean if a field has been set.

### GetCreatedDateTime

`func (o *JustInSequenceApiGetJISRackResponse) GetCreatedDateTime() time.Time`

GetCreatedDateTime returns the CreatedDateTime field if non-nil, zero value otherwise.

### GetCreatedDateTimeOk

`func (o *JustInSequenceApiGetJISRackResponse) GetCreatedDateTimeOk() (*time.Time, bool)`

GetCreatedDateTimeOk returns a tuple with the CreatedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDateTime

`func (o *JustInSequenceApiGetJISRackResponse) SetCreatedDateTime(v time.Time)`

SetCreatedDateTime sets CreatedDateTime field to given value.

### HasCreatedDateTime

`func (o *JustInSequenceApiGetJISRackResponse) HasCreatedDateTime() bool`

HasCreatedDateTime returns a boolean if a field has been set.

### GetModifiedByAccountId

`func (o *JustInSequenceApiGetJISRackResponse) GetModifiedByAccountId() string`

GetModifiedByAccountId returns the ModifiedByAccountId field if non-nil, zero value otherwise.

### GetModifiedByAccountIdOk

`func (o *JustInSequenceApiGetJISRackResponse) GetModifiedByAccountIdOk() (*string, bool)`

GetModifiedByAccountIdOk returns a tuple with the ModifiedByAccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedByAccountId

`func (o *JustInSequenceApiGetJISRackResponse) SetModifiedByAccountId(v string)`

SetModifiedByAccountId sets ModifiedByAccountId field to given value.

### HasModifiedByAccountId

`func (o *JustInSequenceApiGetJISRackResponse) HasModifiedByAccountId() bool`

HasModifiedByAccountId returns a boolean if a field has been set.

### GetModifiedDateTime

`func (o *JustInSequenceApiGetJISRackResponse) GetModifiedDateTime() time.Time`

GetModifiedDateTime returns the ModifiedDateTime field if non-nil, zero value otherwise.

### GetModifiedDateTimeOk

`func (o *JustInSequenceApiGetJISRackResponse) GetModifiedDateTimeOk() (*time.Time, bool)`

GetModifiedDateTimeOk returns a tuple with the ModifiedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDateTime

`func (o *JustInSequenceApiGetJISRackResponse) SetModifiedDateTime(v time.Time)`

SetModifiedDateTime sets ModifiedDateTime field to given value.

### HasModifiedDateTime

`func (o *JustInSequenceApiGetJISRackResponse) HasModifiedDateTime() bool`

HasModifiedDateTime returns a boolean if a field has been set.

### GetReprintNeeded

`func (o *JustInSequenceApiGetJISRackResponse) GetReprintNeeded() bool`

GetReprintNeeded returns the ReprintNeeded field if non-nil, zero value otherwise.

### GetReprintNeededOk

`func (o *JustInSequenceApiGetJISRackResponse) GetReprintNeededOk() (*bool, bool)`

GetReprintNeededOk returns a tuple with the ReprintNeeded field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReprintNeeded

`func (o *JustInSequenceApiGetJISRackResponse) SetReprintNeeded(v bool)`

SetReprintNeeded sets ReprintNeeded field to given value.

### HasReprintNeeded

`func (o *JustInSequenceApiGetJISRackResponse) HasReprintNeeded() bool`

HasReprintNeeded returns a boolean if a field has been set.

### GetPrintedByAccountId

`func (o *JustInSequenceApiGetJISRackResponse) GetPrintedByAccountId() string`

GetPrintedByAccountId returns the PrintedByAccountId field if non-nil, zero value otherwise.

### GetPrintedByAccountIdOk

`func (o *JustInSequenceApiGetJISRackResponse) GetPrintedByAccountIdOk() (*string, bool)`

GetPrintedByAccountIdOk returns a tuple with the PrintedByAccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrintedByAccountId

`func (o *JustInSequenceApiGetJISRackResponse) SetPrintedByAccountId(v string)`

SetPrintedByAccountId sets PrintedByAccountId field to given value.

### HasPrintedByAccountId

`func (o *JustInSequenceApiGetJISRackResponse) HasPrintedByAccountId() bool`

HasPrintedByAccountId returns a boolean if a field has been set.

### GetPrintedDateTime

`func (o *JustInSequenceApiGetJISRackResponse) GetPrintedDateTime() time.Time`

GetPrintedDateTime returns the PrintedDateTime field if non-nil, zero value otherwise.

### GetPrintedDateTimeOk

`func (o *JustInSequenceApiGetJISRackResponse) GetPrintedDateTimeOk() (*time.Time, bool)`

GetPrintedDateTimeOk returns a tuple with the PrintedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrintedDateTime

`func (o *JustInSequenceApiGetJISRackResponse) SetPrintedDateTime(v time.Time)`

SetPrintedDateTime sets PrintedDateTime field to given value.

### HasPrintedDateTime

`func (o *JustInSequenceApiGetJISRackResponse) HasPrintedDateTime() bool`

HasPrintedDateTime returns a boolean if a field has been set.

### GetTruckId

`func (o *JustInSequenceApiGetJISRackResponse) GetTruckId() string`

GetTruckId returns the TruckId field if non-nil, zero value otherwise.

### GetTruckIdOk

`func (o *JustInSequenceApiGetJISRackResponse) GetTruckIdOk() (*string, bool)`

GetTruckIdOk returns a tuple with the TruckId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckId

`func (o *JustInSequenceApiGetJISRackResponse) SetTruckId(v string)`

SetTruckId sets TruckId field to given value.

### HasTruckId

`func (o *JustInSequenceApiGetJISRackResponse) HasTruckId() bool`

HasTruckId returns a boolean if a field has been set.

### GetTruckNumber

`func (o *JustInSequenceApiGetJISRackResponse) GetTruckNumber() string`

GetTruckNumber returns the TruckNumber field if non-nil, zero value otherwise.

### GetTruckNumberOk

`func (o *JustInSequenceApiGetJISRackResponse) GetTruckNumberOk() (*string, bool)`

GetTruckNumberOk returns a tuple with the TruckNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckNumber

`func (o *JustInSequenceApiGetJISRackResponse) SetTruckNumber(v string)`

SetTruckNumber sets TruckNumber field to given value.

### HasTruckNumber

`func (o *JustInSequenceApiGetJISRackResponse) HasTruckNumber() bool`

HasTruckNumber returns a boolean if a field has been set.

### GetTrailerNumber

`func (o *JustInSequenceApiGetJISRackResponse) GetTrailerNumber() string`

GetTrailerNumber returns the TrailerNumber field if non-nil, zero value otherwise.

### GetTrailerNumberOk

`func (o *JustInSequenceApiGetJISRackResponse) GetTrailerNumberOk() (*string, bool)`

GetTrailerNumberOk returns a tuple with the TrailerNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrailerNumber

`func (o *JustInSequenceApiGetJISRackResponse) SetTrailerNumber(v string)`

SetTrailerNumber sets TrailerNumber field to given value.

### HasTrailerNumber

`func (o *JustInSequenceApiGetJISRackResponse) HasTrailerNumber() bool`

HasTrailerNumber returns a boolean if a field has been set.

### GetLabelPrintedByAccountId

`func (o *JustInSequenceApiGetJISRackResponse) GetLabelPrintedByAccountId() string`

GetLabelPrintedByAccountId returns the LabelPrintedByAccountId field if non-nil, zero value otherwise.

### GetLabelPrintedByAccountIdOk

`func (o *JustInSequenceApiGetJISRackResponse) GetLabelPrintedByAccountIdOk() (*string, bool)`

GetLabelPrintedByAccountIdOk returns a tuple with the LabelPrintedByAccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabelPrintedByAccountId

`func (o *JustInSequenceApiGetJISRackResponse) SetLabelPrintedByAccountId(v string)`

SetLabelPrintedByAccountId sets LabelPrintedByAccountId field to given value.

### HasLabelPrintedByAccountId

`func (o *JustInSequenceApiGetJISRackResponse) HasLabelPrintedByAccountId() bool`

HasLabelPrintedByAccountId returns a boolean if a field has been set.

### GetLabelPrintedDateTime

`func (o *JustInSequenceApiGetJISRackResponse) GetLabelPrintedDateTime() time.Time`

GetLabelPrintedDateTime returns the LabelPrintedDateTime field if non-nil, zero value otherwise.

### GetLabelPrintedDateTimeOk

`func (o *JustInSequenceApiGetJISRackResponse) GetLabelPrintedDateTimeOk() (*time.Time, bool)`

GetLabelPrintedDateTimeOk returns a tuple with the LabelPrintedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabelPrintedDateTime

`func (o *JustInSequenceApiGetJISRackResponse) SetLabelPrintedDateTime(v time.Time)`

SetLabelPrintedDateTime sets LabelPrintedDateTime field to given value.

### HasLabelPrintedDateTime

`func (o *JustInSequenceApiGetJISRackResponse) HasLabelPrintedDateTime() bool`

HasLabelPrintedDateTime returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


