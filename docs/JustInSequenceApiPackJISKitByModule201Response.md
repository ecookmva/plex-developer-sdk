# JustInSequenceApiPackJISKitByModule201Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RackId** | Pointer to **string** | The unique identifier for the sequenced rack. | [optional] 
**RackStatus** | Pointer to **string** | The status assigned to the sequenced rack. | [optional] 
**MasterUnitNumber** | Pointer to **string** | The master unit number associated with the rack. | [optional] 
**SourceSerialNumber** | Pointer to **string** | The source container&#39;s serial number. | [optional] 
**KitId** | Pointer to **string** | The unique identifier for the sequenced kit. | [optional] 
**KitStatus** | Pointer to **string** | The status assigned to the sequenced kit. | [optional] 
**Releases** | Pointer to [**[]ReleasesItem2**](ReleasesItem2.md) | The releases related to the packed kit. | [optional] 

## Methods

### NewJustInSequenceApiPackJISKitByModule201Response

`func NewJustInSequenceApiPackJISKitByModule201Response() *JustInSequenceApiPackJISKitByModule201Response`

NewJustInSequenceApiPackJISKitByModule201Response instantiates a new JustInSequenceApiPackJISKitByModule201Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewJustInSequenceApiPackJISKitByModule201ResponseWithDefaults

`func NewJustInSequenceApiPackJISKitByModule201ResponseWithDefaults() *JustInSequenceApiPackJISKitByModule201Response`

NewJustInSequenceApiPackJISKitByModule201ResponseWithDefaults instantiates a new JustInSequenceApiPackJISKitByModule201Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRackId

`func (o *JustInSequenceApiPackJISKitByModule201Response) GetRackId() string`

GetRackId returns the RackId field if non-nil, zero value otherwise.

### GetRackIdOk

`func (o *JustInSequenceApiPackJISKitByModule201Response) GetRackIdOk() (*string, bool)`

GetRackIdOk returns a tuple with the RackId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRackId

`func (o *JustInSequenceApiPackJISKitByModule201Response) SetRackId(v string)`

SetRackId sets RackId field to given value.

### HasRackId

`func (o *JustInSequenceApiPackJISKitByModule201Response) HasRackId() bool`

HasRackId returns a boolean if a field has been set.

### GetRackStatus

`func (o *JustInSequenceApiPackJISKitByModule201Response) GetRackStatus() string`

GetRackStatus returns the RackStatus field if non-nil, zero value otherwise.

### GetRackStatusOk

`func (o *JustInSequenceApiPackJISKitByModule201Response) GetRackStatusOk() (*string, bool)`

GetRackStatusOk returns a tuple with the RackStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRackStatus

`func (o *JustInSequenceApiPackJISKitByModule201Response) SetRackStatus(v string)`

SetRackStatus sets RackStatus field to given value.

### HasRackStatus

`func (o *JustInSequenceApiPackJISKitByModule201Response) HasRackStatus() bool`

HasRackStatus returns a boolean if a field has been set.

### GetMasterUnitNumber

`func (o *JustInSequenceApiPackJISKitByModule201Response) GetMasterUnitNumber() string`

GetMasterUnitNumber returns the MasterUnitNumber field if non-nil, zero value otherwise.

### GetMasterUnitNumberOk

`func (o *JustInSequenceApiPackJISKitByModule201Response) GetMasterUnitNumberOk() (*string, bool)`

GetMasterUnitNumberOk returns a tuple with the MasterUnitNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMasterUnitNumber

`func (o *JustInSequenceApiPackJISKitByModule201Response) SetMasterUnitNumber(v string)`

SetMasterUnitNumber sets MasterUnitNumber field to given value.

### HasMasterUnitNumber

`func (o *JustInSequenceApiPackJISKitByModule201Response) HasMasterUnitNumber() bool`

HasMasterUnitNumber returns a boolean if a field has been set.

### GetSourceSerialNumber

`func (o *JustInSequenceApiPackJISKitByModule201Response) GetSourceSerialNumber() string`

GetSourceSerialNumber returns the SourceSerialNumber field if non-nil, zero value otherwise.

### GetSourceSerialNumberOk

`func (o *JustInSequenceApiPackJISKitByModule201Response) GetSourceSerialNumberOk() (*string, bool)`

GetSourceSerialNumberOk returns a tuple with the SourceSerialNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceSerialNumber

`func (o *JustInSequenceApiPackJISKitByModule201Response) SetSourceSerialNumber(v string)`

SetSourceSerialNumber sets SourceSerialNumber field to given value.

### HasSourceSerialNumber

`func (o *JustInSequenceApiPackJISKitByModule201Response) HasSourceSerialNumber() bool`

HasSourceSerialNumber returns a boolean if a field has been set.

### GetKitId

`func (o *JustInSequenceApiPackJISKitByModule201Response) GetKitId() string`

GetKitId returns the KitId field if non-nil, zero value otherwise.

### GetKitIdOk

`func (o *JustInSequenceApiPackJISKitByModule201Response) GetKitIdOk() (*string, bool)`

GetKitIdOk returns a tuple with the KitId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKitId

`func (o *JustInSequenceApiPackJISKitByModule201Response) SetKitId(v string)`

SetKitId sets KitId field to given value.

### HasKitId

`func (o *JustInSequenceApiPackJISKitByModule201Response) HasKitId() bool`

HasKitId returns a boolean if a field has been set.

### GetKitStatus

`func (o *JustInSequenceApiPackJISKitByModule201Response) GetKitStatus() string`

GetKitStatus returns the KitStatus field if non-nil, zero value otherwise.

### GetKitStatusOk

`func (o *JustInSequenceApiPackJISKitByModule201Response) GetKitStatusOk() (*string, bool)`

GetKitStatusOk returns a tuple with the KitStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKitStatus

`func (o *JustInSequenceApiPackJISKitByModule201Response) SetKitStatus(v string)`

SetKitStatus sets KitStatus field to given value.

### HasKitStatus

`func (o *JustInSequenceApiPackJISKitByModule201Response) HasKitStatus() bool`

HasKitStatus returns a boolean if a field has been set.

### GetReleases

`func (o *JustInSequenceApiPackJISKitByModule201Response) GetReleases() []ReleasesItem2`

GetReleases returns the Releases field if non-nil, zero value otherwise.

### GetReleasesOk

`func (o *JustInSequenceApiPackJISKitByModule201Response) GetReleasesOk() (*[]ReleasesItem2, bool)`

GetReleasesOk returns a tuple with the Releases field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleases

`func (o *JustInSequenceApiPackJISKitByModule201Response) SetReleases(v []ReleasesItem2)`

SetReleases sets Releases field to given value.

### HasReleases

`func (o *JustInSequenceApiPackJISKitByModule201Response) HasReleases() bool`

HasReleases returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


