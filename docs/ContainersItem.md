# ContainersItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SerialNo** | Pointer to **string** | 25 characters max. The serial number of the container that was adjusted. | [optional] 
**CreatedById** | Pointer to **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. The tenant ID used to create this container. | [optional] 
**CreatedDate** | Pointer to **time.Time** | Date/Time Format YYYY-MM-DDThh:mm:ss.fffffffZ The date and time when Container was created. See \&quot;Dates and Times\&quot; in the Get Started section of the Plex Developer Portal (APIs &gt; Get Started). | [optional] 
**Eun** | Pointer to **string** | 40 character max. The Container&#39;s End Unit Number. | [optional] 
**LotId** | Pointer to **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. The lot ID. | [optional] 
**LotNo** | Pointer to **string** | The unique number to reference lot. 25 characters max. | [optional] 

## Methods

### NewContainersItem

`func NewContainersItem() *ContainersItem`

NewContainersItem instantiates a new ContainersItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContainersItemWithDefaults

`func NewContainersItemWithDefaults() *ContainersItem`

NewContainersItemWithDefaults instantiates a new ContainersItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSerialNo

`func (o *ContainersItem) GetSerialNo() string`

GetSerialNo returns the SerialNo field if non-nil, zero value otherwise.

### GetSerialNoOk

`func (o *ContainersItem) GetSerialNoOk() (*string, bool)`

GetSerialNoOk returns a tuple with the SerialNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSerialNo

`func (o *ContainersItem) SetSerialNo(v string)`

SetSerialNo sets SerialNo field to given value.

### HasSerialNo

`func (o *ContainersItem) HasSerialNo() bool`

HasSerialNo returns a boolean if a field has been set.

### GetCreatedById

`func (o *ContainersItem) GetCreatedById() string`

GetCreatedById returns the CreatedById field if non-nil, zero value otherwise.

### GetCreatedByIdOk

`func (o *ContainersItem) GetCreatedByIdOk() (*string, bool)`

GetCreatedByIdOk returns a tuple with the CreatedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedById

`func (o *ContainersItem) SetCreatedById(v string)`

SetCreatedById sets CreatedById field to given value.

### HasCreatedById

`func (o *ContainersItem) HasCreatedById() bool`

HasCreatedById returns a boolean if a field has been set.

### GetCreatedDate

`func (o *ContainersItem) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *ContainersItem) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *ContainersItem) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *ContainersItem) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.

### GetEun

`func (o *ContainersItem) GetEun() string`

GetEun returns the Eun field if non-nil, zero value otherwise.

### GetEunOk

`func (o *ContainersItem) GetEunOk() (*string, bool)`

GetEunOk returns a tuple with the Eun field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEun

`func (o *ContainersItem) SetEun(v string)`

SetEun sets Eun field to given value.

### HasEun

`func (o *ContainersItem) HasEun() bool`

HasEun returns a boolean if a field has been set.

### GetLotId

`func (o *ContainersItem) GetLotId() string`

GetLotId returns the LotId field if non-nil, zero value otherwise.

### GetLotIdOk

`func (o *ContainersItem) GetLotIdOk() (*string, bool)`

GetLotIdOk returns a tuple with the LotId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLotId

`func (o *ContainersItem) SetLotId(v string)`

SetLotId sets LotId field to given value.

### HasLotId

`func (o *ContainersItem) HasLotId() bool`

HasLotId returns a boolean if a field has been set.

### GetLotNo

`func (o *ContainersItem) GetLotNo() string`

GetLotNo returns the LotNo field if non-nil, zero value otherwise.

### GetLotNoOk

`func (o *ContainersItem) GetLotNoOk() (*string, bool)`

GetLotNoOk returns a tuple with the LotNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLotNo

`func (o *ContainersItem) SetLotNo(v string)`

SetLotNo sets LotNo field to given value.

### HasLotNo

`func (o *ContainersItem) HasLotNo() bool`

HasLotNo returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


