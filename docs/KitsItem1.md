# KitsItem1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | The id of the kit. | [optional] 
**RackId** | Pointer to **string** | The id of the rack the kit belongs to. | [optional] 
**JisKitStatus** | Pointer to **string** | The JIS kit status. | [optional] 
**PackOrder** | Pointer to **int32** | The pack order. | [optional] 
**RackCellName** | Pointer to **string** | The rack cell name. | [optional] 
**Releases** | Pointer to [**[]ReleasesItem1**](ReleasesItem1.md) | The releases associated with the kit. | [optional] 

## Methods

### NewKitsItem1

`func NewKitsItem1() *KitsItem1`

NewKitsItem1 instantiates a new KitsItem1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewKitsItem1WithDefaults

`func NewKitsItem1WithDefaults() *KitsItem1`

NewKitsItem1WithDefaults instantiates a new KitsItem1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *KitsItem1) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *KitsItem1) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *KitsItem1) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *KitsItem1) HasId() bool`

HasId returns a boolean if a field has been set.

### GetRackId

`func (o *KitsItem1) GetRackId() string`

GetRackId returns the RackId field if non-nil, zero value otherwise.

### GetRackIdOk

`func (o *KitsItem1) GetRackIdOk() (*string, bool)`

GetRackIdOk returns a tuple with the RackId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRackId

`func (o *KitsItem1) SetRackId(v string)`

SetRackId sets RackId field to given value.

### HasRackId

`func (o *KitsItem1) HasRackId() bool`

HasRackId returns a boolean if a field has been set.

### GetJisKitStatus

`func (o *KitsItem1) GetJisKitStatus() string`

GetJisKitStatus returns the JisKitStatus field if non-nil, zero value otherwise.

### GetJisKitStatusOk

`func (o *KitsItem1) GetJisKitStatusOk() (*string, bool)`

GetJisKitStatusOk returns a tuple with the JisKitStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJisKitStatus

`func (o *KitsItem1) SetJisKitStatus(v string)`

SetJisKitStatus sets JisKitStatus field to given value.

### HasJisKitStatus

`func (o *KitsItem1) HasJisKitStatus() bool`

HasJisKitStatus returns a boolean if a field has been set.

### GetPackOrder

`func (o *KitsItem1) GetPackOrder() int32`

GetPackOrder returns the PackOrder field if non-nil, zero value otherwise.

### GetPackOrderOk

`func (o *KitsItem1) GetPackOrderOk() (*int32, bool)`

GetPackOrderOk returns a tuple with the PackOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackOrder

`func (o *KitsItem1) SetPackOrder(v int32)`

SetPackOrder sets PackOrder field to given value.

### HasPackOrder

`func (o *KitsItem1) HasPackOrder() bool`

HasPackOrder returns a boolean if a field has been set.

### GetRackCellName

`func (o *KitsItem1) GetRackCellName() string`

GetRackCellName returns the RackCellName field if non-nil, zero value otherwise.

### GetRackCellNameOk

`func (o *KitsItem1) GetRackCellNameOk() (*string, bool)`

GetRackCellNameOk returns a tuple with the RackCellName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRackCellName

`func (o *KitsItem1) SetRackCellName(v string)`

SetRackCellName sets RackCellName field to given value.

### HasRackCellName

`func (o *KitsItem1) HasRackCellName() bool`

HasRackCellName returns a boolean if a field has been set.

### GetReleases

`func (o *KitsItem1) GetReleases() []ReleasesItem1`

GetReleases returns the Releases field if non-nil, zero value otherwise.

### GetReleasesOk

`func (o *KitsItem1) GetReleasesOk() (*[]ReleasesItem1, bool)`

GetReleasesOk returns a tuple with the Releases field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleases

`func (o *KitsItem1) SetReleases(v []ReleasesItem1)`

SetReleases sets Releases field to given value.

### HasReleases

`func (o *KitsItem1) HasReleases() bool`

HasReleases returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


