# KitsItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | The ID of the sequenced kit. | [optional] 
**PackOrder** | Pointer to **int32** | The kit&#39;s pack order. | [optional] 
**KitName** | Pointer to **string** | The sequenced kit&#39;s name. | [optional] 
**RackCellName** | Pointer to **string** | The cell name on the rack (if a physical rack structure is defined). | [optional] 
**Releases** | Pointer to [**[]ReleasesItem**](ReleasesItem.md) | The list of planned releases in the kit. | [optional] 

## Methods

### NewKitsItem

`func NewKitsItem() *KitsItem`

NewKitsItem instantiates a new KitsItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewKitsItemWithDefaults

`func NewKitsItemWithDefaults() *KitsItem`

NewKitsItemWithDefaults instantiates a new KitsItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *KitsItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *KitsItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *KitsItem) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *KitsItem) HasId() bool`

HasId returns a boolean if a field has been set.

### GetPackOrder

`func (o *KitsItem) GetPackOrder() int32`

GetPackOrder returns the PackOrder field if non-nil, zero value otherwise.

### GetPackOrderOk

`func (o *KitsItem) GetPackOrderOk() (*int32, bool)`

GetPackOrderOk returns a tuple with the PackOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackOrder

`func (o *KitsItem) SetPackOrder(v int32)`

SetPackOrder sets PackOrder field to given value.

### HasPackOrder

`func (o *KitsItem) HasPackOrder() bool`

HasPackOrder returns a boolean if a field has been set.

### GetKitName

`func (o *KitsItem) GetKitName() string`

GetKitName returns the KitName field if non-nil, zero value otherwise.

### GetKitNameOk

`func (o *KitsItem) GetKitNameOk() (*string, bool)`

GetKitNameOk returns a tuple with the KitName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKitName

`func (o *KitsItem) SetKitName(v string)`

SetKitName sets KitName field to given value.

### HasKitName

`func (o *KitsItem) HasKitName() bool`

HasKitName returns a boolean if a field has been set.

### GetRackCellName

`func (o *KitsItem) GetRackCellName() string`

GetRackCellName returns the RackCellName field if non-nil, zero value otherwise.

### GetRackCellNameOk

`func (o *KitsItem) GetRackCellNameOk() (*string, bool)`

GetRackCellNameOk returns a tuple with the RackCellName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRackCellName

`func (o *KitsItem) SetRackCellName(v string)`

SetRackCellName sets RackCellName field to given value.

### HasRackCellName

`func (o *KitsItem) HasRackCellName() bool`

HasRackCellName returns a boolean if a field has been set.

### GetReleases

`func (o *KitsItem) GetReleases() []ReleasesItem`

GetReleases returns the Releases field if non-nil, zero value otherwise.

### GetReleasesOk

`func (o *KitsItem) GetReleasesOk() (*[]ReleasesItem, bool)`

GetReleasesOk returns a tuple with the Releases field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleases

`func (o *KitsItem) SetReleases(v []ReleasesItem)`

SetReleases sets Releases field to given value.

### HasReleases

`func (o *KitsItem) HasReleases() bool`

HasReleases returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


