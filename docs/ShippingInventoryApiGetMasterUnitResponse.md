# ShippingInventoryApiGetMasterUnitResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**MasterUnitId** | Pointer to **string** | The master unit ID. | [optional] 
**MasterUnitNo** | Pointer to **string** | The master unit number. | [optional] 
**MasterUnitType** | Pointer to **string** | The master unit type. | [optional] 
**Description** | Pointer to **string** | The master unit type description. | [optional] 
**Active** | Pointer to **bool** | The master unit&#39;s active status. | [optional] 
**Location** | Pointer to **string** | The master unit location. | [optional] 
**ContainerCount** | Pointer to **int32** | The number of containers on the master unit. | [optional] 
**TareWeight** | Pointer to **float64** | The master unit type&#39;s tare weight. | [optional] 
**Height** | Pointer to **float64** | The master unit type&#39;s height. | [optional] 
**Length** | Pointer to **float64** | The master unit type&#39;s length. | [optional] 
**Width** | Pointer to **float64** | The master unit type&#39;s width. | [optional] 
**Returnable** | Pointer to **bool** | The master unit type&#39;s returnable status. | [optional] 

## Methods

### NewShippingInventoryApiGetMasterUnitResponse

`func NewShippingInventoryApiGetMasterUnitResponse() *ShippingInventoryApiGetMasterUnitResponse`

NewShippingInventoryApiGetMasterUnitResponse instantiates a new ShippingInventoryApiGetMasterUnitResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewShippingInventoryApiGetMasterUnitResponseWithDefaults

`func NewShippingInventoryApiGetMasterUnitResponseWithDefaults() *ShippingInventoryApiGetMasterUnitResponse`

NewShippingInventoryApiGetMasterUnitResponseWithDefaults instantiates a new ShippingInventoryApiGetMasterUnitResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMasterUnitId

`func (o *ShippingInventoryApiGetMasterUnitResponse) GetMasterUnitId() string`

GetMasterUnitId returns the MasterUnitId field if non-nil, zero value otherwise.

### GetMasterUnitIdOk

`func (o *ShippingInventoryApiGetMasterUnitResponse) GetMasterUnitIdOk() (*string, bool)`

GetMasterUnitIdOk returns a tuple with the MasterUnitId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMasterUnitId

`func (o *ShippingInventoryApiGetMasterUnitResponse) SetMasterUnitId(v string)`

SetMasterUnitId sets MasterUnitId field to given value.

### HasMasterUnitId

`func (o *ShippingInventoryApiGetMasterUnitResponse) HasMasterUnitId() bool`

HasMasterUnitId returns a boolean if a field has been set.

### GetMasterUnitNo

`func (o *ShippingInventoryApiGetMasterUnitResponse) GetMasterUnitNo() string`

GetMasterUnitNo returns the MasterUnitNo field if non-nil, zero value otherwise.

### GetMasterUnitNoOk

`func (o *ShippingInventoryApiGetMasterUnitResponse) GetMasterUnitNoOk() (*string, bool)`

GetMasterUnitNoOk returns a tuple with the MasterUnitNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMasterUnitNo

`func (o *ShippingInventoryApiGetMasterUnitResponse) SetMasterUnitNo(v string)`

SetMasterUnitNo sets MasterUnitNo field to given value.

### HasMasterUnitNo

`func (o *ShippingInventoryApiGetMasterUnitResponse) HasMasterUnitNo() bool`

HasMasterUnitNo returns a boolean if a field has been set.

### GetMasterUnitType

`func (o *ShippingInventoryApiGetMasterUnitResponse) GetMasterUnitType() string`

GetMasterUnitType returns the MasterUnitType field if non-nil, zero value otherwise.

### GetMasterUnitTypeOk

`func (o *ShippingInventoryApiGetMasterUnitResponse) GetMasterUnitTypeOk() (*string, bool)`

GetMasterUnitTypeOk returns a tuple with the MasterUnitType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMasterUnitType

`func (o *ShippingInventoryApiGetMasterUnitResponse) SetMasterUnitType(v string)`

SetMasterUnitType sets MasterUnitType field to given value.

### HasMasterUnitType

`func (o *ShippingInventoryApiGetMasterUnitResponse) HasMasterUnitType() bool`

HasMasterUnitType returns a boolean if a field has been set.

### GetDescription

`func (o *ShippingInventoryApiGetMasterUnitResponse) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ShippingInventoryApiGetMasterUnitResponse) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ShippingInventoryApiGetMasterUnitResponse) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ShippingInventoryApiGetMasterUnitResponse) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetActive

`func (o *ShippingInventoryApiGetMasterUnitResponse) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *ShippingInventoryApiGetMasterUnitResponse) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *ShippingInventoryApiGetMasterUnitResponse) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *ShippingInventoryApiGetMasterUnitResponse) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetLocation

`func (o *ShippingInventoryApiGetMasterUnitResponse) GetLocation() string`

GetLocation returns the Location field if non-nil, zero value otherwise.

### GetLocationOk

`func (o *ShippingInventoryApiGetMasterUnitResponse) GetLocationOk() (*string, bool)`

GetLocationOk returns a tuple with the Location field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocation

`func (o *ShippingInventoryApiGetMasterUnitResponse) SetLocation(v string)`

SetLocation sets Location field to given value.

### HasLocation

`func (o *ShippingInventoryApiGetMasterUnitResponse) HasLocation() bool`

HasLocation returns a boolean if a field has been set.

### GetContainerCount

`func (o *ShippingInventoryApiGetMasterUnitResponse) GetContainerCount() int32`

GetContainerCount returns the ContainerCount field if non-nil, zero value otherwise.

### GetContainerCountOk

`func (o *ShippingInventoryApiGetMasterUnitResponse) GetContainerCountOk() (*int32, bool)`

GetContainerCountOk returns a tuple with the ContainerCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContainerCount

`func (o *ShippingInventoryApiGetMasterUnitResponse) SetContainerCount(v int32)`

SetContainerCount sets ContainerCount field to given value.

### HasContainerCount

`func (o *ShippingInventoryApiGetMasterUnitResponse) HasContainerCount() bool`

HasContainerCount returns a boolean if a field has been set.

### GetTareWeight

`func (o *ShippingInventoryApiGetMasterUnitResponse) GetTareWeight() float64`

GetTareWeight returns the TareWeight field if non-nil, zero value otherwise.

### GetTareWeightOk

`func (o *ShippingInventoryApiGetMasterUnitResponse) GetTareWeightOk() (*float64, bool)`

GetTareWeightOk returns a tuple with the TareWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTareWeight

`func (o *ShippingInventoryApiGetMasterUnitResponse) SetTareWeight(v float64)`

SetTareWeight sets TareWeight field to given value.

### HasTareWeight

`func (o *ShippingInventoryApiGetMasterUnitResponse) HasTareWeight() bool`

HasTareWeight returns a boolean if a field has been set.

### GetHeight

`func (o *ShippingInventoryApiGetMasterUnitResponse) GetHeight() float64`

GetHeight returns the Height field if non-nil, zero value otherwise.

### GetHeightOk

`func (o *ShippingInventoryApiGetMasterUnitResponse) GetHeightOk() (*float64, bool)`

GetHeightOk returns a tuple with the Height field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeight

`func (o *ShippingInventoryApiGetMasterUnitResponse) SetHeight(v float64)`

SetHeight sets Height field to given value.

### HasHeight

`func (o *ShippingInventoryApiGetMasterUnitResponse) HasHeight() bool`

HasHeight returns a boolean if a field has been set.

### GetLength

`func (o *ShippingInventoryApiGetMasterUnitResponse) GetLength() float64`

GetLength returns the Length field if non-nil, zero value otherwise.

### GetLengthOk

`func (o *ShippingInventoryApiGetMasterUnitResponse) GetLengthOk() (*float64, bool)`

GetLengthOk returns a tuple with the Length field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLength

`func (o *ShippingInventoryApiGetMasterUnitResponse) SetLength(v float64)`

SetLength sets Length field to given value.

### HasLength

`func (o *ShippingInventoryApiGetMasterUnitResponse) HasLength() bool`

HasLength returns a boolean if a field has been set.

### GetWidth

`func (o *ShippingInventoryApiGetMasterUnitResponse) GetWidth() float64`

GetWidth returns the Width field if non-nil, zero value otherwise.

### GetWidthOk

`func (o *ShippingInventoryApiGetMasterUnitResponse) GetWidthOk() (*float64, bool)`

GetWidthOk returns a tuple with the Width field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidth

`func (o *ShippingInventoryApiGetMasterUnitResponse) SetWidth(v float64)`

SetWidth sets Width field to given value.

### HasWidth

`func (o *ShippingInventoryApiGetMasterUnitResponse) HasWidth() bool`

HasWidth returns a boolean if a field has been set.

### GetReturnable

`func (o *ShippingInventoryApiGetMasterUnitResponse) GetReturnable() bool`

GetReturnable returns the Returnable field if non-nil, zero value otherwise.

### GetReturnableOk

`func (o *ShippingInventoryApiGetMasterUnitResponse) GetReturnableOk() (*bool, bool)`

GetReturnableOk returns a tuple with the Returnable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReturnable

`func (o *ShippingInventoryApiGetMasterUnitResponse) SetReturnable(v bool)`

SetReturnable sets Returnable field to given value.

### HasReturnable

`func (o *ShippingInventoryApiGetMasterUnitResponse) HasReturnable() bool`

HasReturnable returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


