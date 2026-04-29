# CustomerShippersApiLoadShipperLineFIFOResponse

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

### NewCustomerShippersApiLoadShipperLineFIFOResponse

`func NewCustomerShippersApiLoadShipperLineFIFOResponse() *CustomerShippersApiLoadShipperLineFIFOResponse`

NewCustomerShippersApiLoadShipperLineFIFOResponse instantiates a new CustomerShippersApiLoadShipperLineFIFOResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomerShippersApiLoadShipperLineFIFOResponseWithDefaults

`func NewCustomerShippersApiLoadShipperLineFIFOResponseWithDefaults() *CustomerShippersApiLoadShipperLineFIFOResponse`

NewCustomerShippersApiLoadShipperLineFIFOResponseWithDefaults instantiates a new CustomerShippersApiLoadShipperLineFIFOResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetShipperId

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) GetShipperId() string`

GetShipperId returns the ShipperId field if non-nil, zero value otherwise.

### GetShipperIdOk

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) GetShipperIdOk() (*string, bool)`

GetShipperIdOk returns a tuple with the ShipperId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipperId

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) SetShipperId(v string)`

SetShipperId sets ShipperId field to given value.

### HasShipperId

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) HasShipperId() bool`

HasShipperId returns a boolean if a field has been set.

### GetPartId

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetQuantity

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetReleaseId

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) GetReleaseId() string`

GetReleaseId returns the ReleaseId field if non-nil, zero value otherwise.

### GetReleaseIdOk

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) GetReleaseIdOk() (*string, bool)`

GetReleaseIdOk returns a tuple with the ReleaseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleaseId

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) SetReleaseId(v string)`

SetReleaseId sets ReleaseId field to given value.

### HasReleaseId

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) HasReleaseId() bool`

HasReleaseId returns a boolean if a field has been set.

### GetPrice

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) GetPrice() float64`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) GetPriceOk() (*float64, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) SetPrice(v float64)`

SetPrice sets Price field to given value.

### HasPrice

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) HasPrice() bool`

HasPrice returns a boolean if a field has been set.

### GetCustomerPartId

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) GetCustomerPartId() string`

GetCustomerPartId returns the CustomerPartId field if non-nil, zero value otherwise.

### GetCustomerPartIdOk

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) GetCustomerPartIdOk() (*string, bool)`

GetCustomerPartIdOk returns a tuple with the CustomerPartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerPartId

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) SetCustomerPartId(v string)`

SetCustomerPartId sets CustomerPartId field to given value.

### HasCustomerPartId

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) HasCustomerPartId() bool`

HasCustomerPartId returns a boolean if a field has been set.

### GetPriceId

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) GetPriceId() string`

GetPriceId returns the PriceId field if non-nil, zero value otherwise.

### GetPriceIdOk

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) GetPriceIdOk() (*string, bool)`

GetPriceIdOk returns a tuple with the PriceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriceId

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) SetPriceId(v string)`

SetPriceId sets PriceId field to given value.

### HasPriceId

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) HasPriceId() bool`

HasPriceId returns a boolean if a field has been set.

### GetGrossWeight

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) GetGrossWeight() float64`

GetGrossWeight returns the GrossWeight field if non-nil, zero value otherwise.

### GetGrossWeightOk

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) GetGrossWeightOk() (*float64, bool)`

GetGrossWeightOk returns a tuple with the GrossWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrossWeight

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) SetGrossWeight(v float64)`

SetGrossWeight sets GrossWeight field to given value.

### HasGrossWeight

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) HasGrossWeight() bool`

HasGrossWeight returns a boolean if a field has been set.

### GetNetWeight

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) GetNetWeight() float64`

GetNetWeight returns the NetWeight field if non-nil, zero value otherwise.

### GetNetWeightOk

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) GetNetWeightOk() (*float64, bool)`

GetNetWeightOk returns a tuple with the NetWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetWeight

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) SetNetWeight(v float64)`

SetNetWeight sets NetWeight field to given value.

### HasNetWeight

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) HasNetWeight() bool`

HasNetWeight returns a boolean if a field has been set.

### GetTareWeight

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) GetTareWeight() float64`

GetTareWeight returns the TareWeight field if non-nil, zero value otherwise.

### GetTareWeightOk

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) GetTareWeightOk() (*float64, bool)`

GetTareWeightOk returns a tuple with the TareWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTareWeight

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) SetTareWeight(v float64)`

SetTareWeight sets TareWeight field to given value.

### HasTareWeight

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) HasTareWeight() bool`

HasTareWeight returns a boolean if a field has been set.

### GetShipperLineNote

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) GetShipperLineNote() string`

GetShipperLineNote returns the ShipperLineNote field if non-nil, zero value otherwise.

### GetShipperLineNoteOk

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) GetShipperLineNoteOk() (*string, bool)`

GetShipperLineNoteOk returns a tuple with the ShipperLineNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipperLineNote

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) SetShipperLineNote(v string)`

SetShipperLineNote sets ShipperLineNote field to given value.

### HasShipperLineNote

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) HasShipperLineNote() bool`

HasShipperLineNote returns a boolean if a field has been set.

### GetPackingComplete

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) GetPackingComplete() bool`

GetPackingComplete returns the PackingComplete field if non-nil, zero value otherwise.

### GetPackingCompleteOk

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) GetPackingCompleteOk() (*bool, bool)`

GetPackingCompleteOk returns a tuple with the PackingComplete field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackingComplete

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) SetPackingComplete(v bool)`

SetPackingComplete sets PackingComplete field to given value.

### HasPackingComplete

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) HasPackingComplete() bool`

HasPackingComplete returns a boolean if a field has been set.

### GetConversion

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) GetConversion() float64`

GetConversion returns the Conversion field if non-nil, zero value otherwise.

### GetConversionOk

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) GetConversionOk() (*float64, bool)`

GetConversionOk returns a tuple with the Conversion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConversion

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) SetConversion(v float64)`

SetConversion sets Conversion field to given value.

### HasConversion

`func (o *CustomerShippersApiLoadShipperLineFIFOResponse) HasConversion() bool`

HasConversion returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


