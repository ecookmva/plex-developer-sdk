# JustInSequenceApiCreatePlannedJISRackRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | A unique identifier for the sequenced release. | [optional] 
**RackSequenceNumber** | Pointer to **string** | The rack sequence number. | [optional] 
**LineSequenceSetupName** | Pointer to **string** | The rack&#39;s line sequence setup name. | [optional] 
**Kits** | Pointer to [**[]KitsItem**](KitsItem.md) | The list of planned kits in the rack. | [optional] 
**PackOrder** | Pointer to **int32** | The kit&#39;s pack order. | [optional] 
**KitName** | Pointer to **string** | The sequenced kit&#39;s name. | [optional] 
**RackCellName** | Pointer to **string** | The cell name on the rack (if a physical rack structure is defined). | [optional] 
**Releases** | Pointer to [**[]ReleasesItem**](ReleasesItem.md) | The list of planned releases in the kit. | [optional] 
**SalesReleaseId** | Pointer to **string** | A unique identifier for the sales release. | [optional] 

## Methods

### NewJustInSequenceApiCreatePlannedJISRackRequest

`func NewJustInSequenceApiCreatePlannedJISRackRequest() *JustInSequenceApiCreatePlannedJISRackRequest`

NewJustInSequenceApiCreatePlannedJISRackRequest instantiates a new JustInSequenceApiCreatePlannedJISRackRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewJustInSequenceApiCreatePlannedJISRackRequestWithDefaults

`func NewJustInSequenceApiCreatePlannedJISRackRequestWithDefaults() *JustInSequenceApiCreatePlannedJISRackRequest`

NewJustInSequenceApiCreatePlannedJISRackRequestWithDefaults instantiates a new JustInSequenceApiCreatePlannedJISRackRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *JustInSequenceApiCreatePlannedJISRackRequest) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *JustInSequenceApiCreatePlannedJISRackRequest) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *JustInSequenceApiCreatePlannedJISRackRequest) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *JustInSequenceApiCreatePlannedJISRackRequest) HasId() bool`

HasId returns a boolean if a field has been set.

### GetRackSequenceNumber

`func (o *JustInSequenceApiCreatePlannedJISRackRequest) GetRackSequenceNumber() string`

GetRackSequenceNumber returns the RackSequenceNumber field if non-nil, zero value otherwise.

### GetRackSequenceNumberOk

`func (o *JustInSequenceApiCreatePlannedJISRackRequest) GetRackSequenceNumberOk() (*string, bool)`

GetRackSequenceNumberOk returns a tuple with the RackSequenceNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRackSequenceNumber

`func (o *JustInSequenceApiCreatePlannedJISRackRequest) SetRackSequenceNumber(v string)`

SetRackSequenceNumber sets RackSequenceNumber field to given value.

### HasRackSequenceNumber

`func (o *JustInSequenceApiCreatePlannedJISRackRequest) HasRackSequenceNumber() bool`

HasRackSequenceNumber returns a boolean if a field has been set.

### GetLineSequenceSetupName

`func (o *JustInSequenceApiCreatePlannedJISRackRequest) GetLineSequenceSetupName() string`

GetLineSequenceSetupName returns the LineSequenceSetupName field if non-nil, zero value otherwise.

### GetLineSequenceSetupNameOk

`func (o *JustInSequenceApiCreatePlannedJISRackRequest) GetLineSequenceSetupNameOk() (*string, bool)`

GetLineSequenceSetupNameOk returns a tuple with the LineSequenceSetupName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineSequenceSetupName

`func (o *JustInSequenceApiCreatePlannedJISRackRequest) SetLineSequenceSetupName(v string)`

SetLineSequenceSetupName sets LineSequenceSetupName field to given value.

### HasLineSequenceSetupName

`func (o *JustInSequenceApiCreatePlannedJISRackRequest) HasLineSequenceSetupName() bool`

HasLineSequenceSetupName returns a boolean if a field has been set.

### GetKits

`func (o *JustInSequenceApiCreatePlannedJISRackRequest) GetKits() []KitsItem`

GetKits returns the Kits field if non-nil, zero value otherwise.

### GetKitsOk

`func (o *JustInSequenceApiCreatePlannedJISRackRequest) GetKitsOk() (*[]KitsItem, bool)`

GetKitsOk returns a tuple with the Kits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKits

`func (o *JustInSequenceApiCreatePlannedJISRackRequest) SetKits(v []KitsItem)`

SetKits sets Kits field to given value.

### HasKits

`func (o *JustInSequenceApiCreatePlannedJISRackRequest) HasKits() bool`

HasKits returns a boolean if a field has been set.

### GetPackOrder

`func (o *JustInSequenceApiCreatePlannedJISRackRequest) GetPackOrder() int32`

GetPackOrder returns the PackOrder field if non-nil, zero value otherwise.

### GetPackOrderOk

`func (o *JustInSequenceApiCreatePlannedJISRackRequest) GetPackOrderOk() (*int32, bool)`

GetPackOrderOk returns a tuple with the PackOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackOrder

`func (o *JustInSequenceApiCreatePlannedJISRackRequest) SetPackOrder(v int32)`

SetPackOrder sets PackOrder field to given value.

### HasPackOrder

`func (o *JustInSequenceApiCreatePlannedJISRackRequest) HasPackOrder() bool`

HasPackOrder returns a boolean if a field has been set.

### GetKitName

`func (o *JustInSequenceApiCreatePlannedJISRackRequest) GetKitName() string`

GetKitName returns the KitName field if non-nil, zero value otherwise.

### GetKitNameOk

`func (o *JustInSequenceApiCreatePlannedJISRackRequest) GetKitNameOk() (*string, bool)`

GetKitNameOk returns a tuple with the KitName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKitName

`func (o *JustInSequenceApiCreatePlannedJISRackRequest) SetKitName(v string)`

SetKitName sets KitName field to given value.

### HasKitName

`func (o *JustInSequenceApiCreatePlannedJISRackRequest) HasKitName() bool`

HasKitName returns a boolean if a field has been set.

### GetRackCellName

`func (o *JustInSequenceApiCreatePlannedJISRackRequest) GetRackCellName() string`

GetRackCellName returns the RackCellName field if non-nil, zero value otherwise.

### GetRackCellNameOk

`func (o *JustInSequenceApiCreatePlannedJISRackRequest) GetRackCellNameOk() (*string, bool)`

GetRackCellNameOk returns a tuple with the RackCellName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRackCellName

`func (o *JustInSequenceApiCreatePlannedJISRackRequest) SetRackCellName(v string)`

SetRackCellName sets RackCellName field to given value.

### HasRackCellName

`func (o *JustInSequenceApiCreatePlannedJISRackRequest) HasRackCellName() bool`

HasRackCellName returns a boolean if a field has been set.

### GetReleases

`func (o *JustInSequenceApiCreatePlannedJISRackRequest) GetReleases() []ReleasesItem`

GetReleases returns the Releases field if non-nil, zero value otherwise.

### GetReleasesOk

`func (o *JustInSequenceApiCreatePlannedJISRackRequest) GetReleasesOk() (*[]ReleasesItem, bool)`

GetReleasesOk returns a tuple with the Releases field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleases

`func (o *JustInSequenceApiCreatePlannedJISRackRequest) SetReleases(v []ReleasesItem)`

SetReleases sets Releases field to given value.

### HasReleases

`func (o *JustInSequenceApiCreatePlannedJISRackRequest) HasReleases() bool`

HasReleases returns a boolean if a field has been set.

### GetSalesReleaseId

`func (o *JustInSequenceApiCreatePlannedJISRackRequest) GetSalesReleaseId() string`

GetSalesReleaseId returns the SalesReleaseId field if non-nil, zero value otherwise.

### GetSalesReleaseIdOk

`func (o *JustInSequenceApiCreatePlannedJISRackRequest) GetSalesReleaseIdOk() (*string, bool)`

GetSalesReleaseIdOk returns a tuple with the SalesReleaseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSalesReleaseId

`func (o *JustInSequenceApiCreatePlannedJISRackRequest) SetSalesReleaseId(v string)`

SetSalesReleaseId sets SalesReleaseId field to given value.

### HasSalesReleaseId

`func (o *JustInSequenceApiCreatePlannedJISRackRequest) HasSalesReleaseId() bool`

HasSalesReleaseId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


