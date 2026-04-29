# CustomerShippersApiListCustomerShipperLineContainersItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ReleaseId** | Pointer to **string** | The ID of the release associated with the container on the shipper line. | [optional] 
**SerialNumber** | Pointer to **string** | The serial number of the inventory container assigned to the shipper line. | [optional] 
**Quantity** | Pointer to **float64** | The part quantity of the container that was loaded to the shipper line. | [optional] 
**LoadedDate** | Pointer to **time.Time** | The date on which the inventory container was loaded to the shipper line. | [optional] 

## Methods

### NewCustomerShippersApiListCustomerShipperLineContainersItem

`func NewCustomerShippersApiListCustomerShipperLineContainersItem() *CustomerShippersApiListCustomerShipperLineContainersItem`

NewCustomerShippersApiListCustomerShipperLineContainersItem instantiates a new CustomerShippersApiListCustomerShipperLineContainersItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomerShippersApiListCustomerShipperLineContainersItemWithDefaults

`func NewCustomerShippersApiListCustomerShipperLineContainersItemWithDefaults() *CustomerShippersApiListCustomerShipperLineContainersItem`

NewCustomerShippersApiListCustomerShipperLineContainersItemWithDefaults instantiates a new CustomerShippersApiListCustomerShipperLineContainersItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetReleaseId

`func (o *CustomerShippersApiListCustomerShipperLineContainersItem) GetReleaseId() string`

GetReleaseId returns the ReleaseId field if non-nil, zero value otherwise.

### GetReleaseIdOk

`func (o *CustomerShippersApiListCustomerShipperLineContainersItem) GetReleaseIdOk() (*string, bool)`

GetReleaseIdOk returns a tuple with the ReleaseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleaseId

`func (o *CustomerShippersApiListCustomerShipperLineContainersItem) SetReleaseId(v string)`

SetReleaseId sets ReleaseId field to given value.

### HasReleaseId

`func (o *CustomerShippersApiListCustomerShipperLineContainersItem) HasReleaseId() bool`

HasReleaseId returns a boolean if a field has been set.

### GetSerialNumber

`func (o *CustomerShippersApiListCustomerShipperLineContainersItem) GetSerialNumber() string`

GetSerialNumber returns the SerialNumber field if non-nil, zero value otherwise.

### GetSerialNumberOk

`func (o *CustomerShippersApiListCustomerShipperLineContainersItem) GetSerialNumberOk() (*string, bool)`

GetSerialNumberOk returns a tuple with the SerialNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSerialNumber

`func (o *CustomerShippersApiListCustomerShipperLineContainersItem) SetSerialNumber(v string)`

SetSerialNumber sets SerialNumber field to given value.

### HasSerialNumber

`func (o *CustomerShippersApiListCustomerShipperLineContainersItem) HasSerialNumber() bool`

HasSerialNumber returns a boolean if a field has been set.

### GetQuantity

`func (o *CustomerShippersApiListCustomerShipperLineContainersItem) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *CustomerShippersApiListCustomerShipperLineContainersItem) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *CustomerShippersApiListCustomerShipperLineContainersItem) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *CustomerShippersApiListCustomerShipperLineContainersItem) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetLoadedDate

`func (o *CustomerShippersApiListCustomerShipperLineContainersItem) GetLoadedDate() time.Time`

GetLoadedDate returns the LoadedDate field if non-nil, zero value otherwise.

### GetLoadedDateOk

`func (o *CustomerShippersApiListCustomerShipperLineContainersItem) GetLoadedDateOk() (*time.Time, bool)`

GetLoadedDateOk returns a tuple with the LoadedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLoadedDate

`func (o *CustomerShippersApiListCustomerShipperLineContainersItem) SetLoadedDate(v time.Time)`

SetLoadedDate sets LoadedDate field to given value.

### HasLoadedDate

`func (o *CustomerShippersApiListCustomerShipperLineContainersItem) HasLoadedDate() bool`

HasLoadedDate returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


