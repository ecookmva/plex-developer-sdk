# CustomerShippersApiGetCustomerShipperLineResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | A unique identifier for the shipper line. This will be automatically generated if omitted from the request. | [optional] 
**ShipperId** | Pointer to **string** | The ID of the shipper associated with this shipper line. | [optional] 
**PartId** | Pointer to **string** | The ID of the Part Number associated with the shipper line. | [optional] 
**Quantity** | Pointer to **float64** | The part quantity on the shipper line. | [optional] 
**ReleaseId** | Pointer to **string** | The ID of the release on the specified shipper line. | [optional] 
**Price** | Pointer to **float64** | The shipping order unit price assigned to the shipper line. | [optional] 
**CustomerPartId** | Pointer to **string** | The ID of the customer part on the shipper line. | [optional] 
**PriceId** | Pointer to **string** | The ID of the price used on the shipper line. | [optional] 
**GrossWeight** | Pointer to **float64** | The gross weight of the shipper line. | [optional] 
**NetWeight** | Pointer to **float64** | The net weight of the shipper line. | [optional] 
**TareWeight** | Pointer to **float64** | The tare weight of the shipper line. | [optional] 
**ShipperLineNote** | Pointer to **string** | The note on the shipper line. | [optional] 
**PackingComplete** | Pointer to **bool** | Indicates if packing is complete for the shipper line. | [optional] 
**Conversion** | Pointer to **float64** | The unit conversion used on the shipper line. | [optional] 

## Methods

### NewCustomerShippersApiGetCustomerShipperLineResponse

`func NewCustomerShippersApiGetCustomerShipperLineResponse() *CustomerShippersApiGetCustomerShipperLineResponse`

NewCustomerShippersApiGetCustomerShipperLineResponse instantiates a new CustomerShippersApiGetCustomerShipperLineResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomerShippersApiGetCustomerShipperLineResponseWithDefaults

`func NewCustomerShippersApiGetCustomerShipperLineResponseWithDefaults() *CustomerShippersApiGetCustomerShipperLineResponse`

NewCustomerShippersApiGetCustomerShipperLineResponseWithDefaults instantiates a new CustomerShippersApiGetCustomerShipperLineResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetShipperId

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) GetShipperId() string`

GetShipperId returns the ShipperId field if non-nil, zero value otherwise.

### GetShipperIdOk

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) GetShipperIdOk() (*string, bool)`

GetShipperIdOk returns a tuple with the ShipperId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipperId

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) SetShipperId(v string)`

SetShipperId sets ShipperId field to given value.

### HasShipperId

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) HasShipperId() bool`

HasShipperId returns a boolean if a field has been set.

### GetPartId

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetQuantity

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetReleaseId

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) GetReleaseId() string`

GetReleaseId returns the ReleaseId field if non-nil, zero value otherwise.

### GetReleaseIdOk

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) GetReleaseIdOk() (*string, bool)`

GetReleaseIdOk returns a tuple with the ReleaseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleaseId

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) SetReleaseId(v string)`

SetReleaseId sets ReleaseId field to given value.

### HasReleaseId

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) HasReleaseId() bool`

HasReleaseId returns a boolean if a field has been set.

### GetPrice

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) GetPrice() float64`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) GetPriceOk() (*float64, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) SetPrice(v float64)`

SetPrice sets Price field to given value.

### HasPrice

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) HasPrice() bool`

HasPrice returns a boolean if a field has been set.

### GetCustomerPartId

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) GetCustomerPartId() string`

GetCustomerPartId returns the CustomerPartId field if non-nil, zero value otherwise.

### GetCustomerPartIdOk

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) GetCustomerPartIdOk() (*string, bool)`

GetCustomerPartIdOk returns a tuple with the CustomerPartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerPartId

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) SetCustomerPartId(v string)`

SetCustomerPartId sets CustomerPartId field to given value.

### HasCustomerPartId

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) HasCustomerPartId() bool`

HasCustomerPartId returns a boolean if a field has been set.

### GetPriceId

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) GetPriceId() string`

GetPriceId returns the PriceId field if non-nil, zero value otherwise.

### GetPriceIdOk

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) GetPriceIdOk() (*string, bool)`

GetPriceIdOk returns a tuple with the PriceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriceId

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) SetPriceId(v string)`

SetPriceId sets PriceId field to given value.

### HasPriceId

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) HasPriceId() bool`

HasPriceId returns a boolean if a field has been set.

### GetGrossWeight

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) GetGrossWeight() float64`

GetGrossWeight returns the GrossWeight field if non-nil, zero value otherwise.

### GetGrossWeightOk

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) GetGrossWeightOk() (*float64, bool)`

GetGrossWeightOk returns a tuple with the GrossWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrossWeight

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) SetGrossWeight(v float64)`

SetGrossWeight sets GrossWeight field to given value.

### HasGrossWeight

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) HasGrossWeight() bool`

HasGrossWeight returns a boolean if a field has been set.

### GetNetWeight

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) GetNetWeight() float64`

GetNetWeight returns the NetWeight field if non-nil, zero value otherwise.

### GetNetWeightOk

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) GetNetWeightOk() (*float64, bool)`

GetNetWeightOk returns a tuple with the NetWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetWeight

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) SetNetWeight(v float64)`

SetNetWeight sets NetWeight field to given value.

### HasNetWeight

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) HasNetWeight() bool`

HasNetWeight returns a boolean if a field has been set.

### GetTareWeight

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) GetTareWeight() float64`

GetTareWeight returns the TareWeight field if non-nil, zero value otherwise.

### GetTareWeightOk

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) GetTareWeightOk() (*float64, bool)`

GetTareWeightOk returns a tuple with the TareWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTareWeight

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) SetTareWeight(v float64)`

SetTareWeight sets TareWeight field to given value.

### HasTareWeight

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) HasTareWeight() bool`

HasTareWeight returns a boolean if a field has been set.

### GetShipperLineNote

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) GetShipperLineNote() string`

GetShipperLineNote returns the ShipperLineNote field if non-nil, zero value otherwise.

### GetShipperLineNoteOk

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) GetShipperLineNoteOk() (*string, bool)`

GetShipperLineNoteOk returns a tuple with the ShipperLineNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipperLineNote

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) SetShipperLineNote(v string)`

SetShipperLineNote sets ShipperLineNote field to given value.

### HasShipperLineNote

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) HasShipperLineNote() bool`

HasShipperLineNote returns a boolean if a field has been set.

### GetPackingComplete

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) GetPackingComplete() bool`

GetPackingComplete returns the PackingComplete field if non-nil, zero value otherwise.

### GetPackingCompleteOk

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) GetPackingCompleteOk() (*bool, bool)`

GetPackingCompleteOk returns a tuple with the PackingComplete field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackingComplete

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) SetPackingComplete(v bool)`

SetPackingComplete sets PackingComplete field to given value.

### HasPackingComplete

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) HasPackingComplete() bool`

HasPackingComplete returns a boolean if a field has been set.

### GetConversion

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) GetConversion() float64`

GetConversion returns the Conversion field if non-nil, zero value otherwise.

### GetConversionOk

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) GetConversionOk() (*float64, bool)`

GetConversionOk returns a tuple with the Conversion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConversion

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) SetConversion(v float64)`

SetConversion sets Conversion field to given value.

### HasConversion

`func (o *CustomerShippersApiGetCustomerShipperLineResponse) HasConversion() bool`

HasConversion returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


