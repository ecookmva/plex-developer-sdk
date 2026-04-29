# CustomerShippersApiListCustomerShipperLinesItem

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

### NewCustomerShippersApiListCustomerShipperLinesItem

`func NewCustomerShippersApiListCustomerShipperLinesItem() *CustomerShippersApiListCustomerShipperLinesItem`

NewCustomerShippersApiListCustomerShipperLinesItem instantiates a new CustomerShippersApiListCustomerShipperLinesItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomerShippersApiListCustomerShipperLinesItemWithDefaults

`func NewCustomerShippersApiListCustomerShipperLinesItemWithDefaults() *CustomerShippersApiListCustomerShipperLinesItem`

NewCustomerShippersApiListCustomerShipperLinesItemWithDefaults instantiates a new CustomerShippersApiListCustomerShipperLinesItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CustomerShippersApiListCustomerShipperLinesItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CustomerShippersApiListCustomerShipperLinesItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CustomerShippersApiListCustomerShipperLinesItem) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *CustomerShippersApiListCustomerShipperLinesItem) HasId() bool`

HasId returns a boolean if a field has been set.

### GetShipperId

`func (o *CustomerShippersApiListCustomerShipperLinesItem) GetShipperId() string`

GetShipperId returns the ShipperId field if non-nil, zero value otherwise.

### GetShipperIdOk

`func (o *CustomerShippersApiListCustomerShipperLinesItem) GetShipperIdOk() (*string, bool)`

GetShipperIdOk returns a tuple with the ShipperId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipperId

`func (o *CustomerShippersApiListCustomerShipperLinesItem) SetShipperId(v string)`

SetShipperId sets ShipperId field to given value.

### HasShipperId

`func (o *CustomerShippersApiListCustomerShipperLinesItem) HasShipperId() bool`

HasShipperId returns a boolean if a field has been set.

### GetPartId

`func (o *CustomerShippersApiListCustomerShipperLinesItem) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *CustomerShippersApiListCustomerShipperLinesItem) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *CustomerShippersApiListCustomerShipperLinesItem) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *CustomerShippersApiListCustomerShipperLinesItem) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetQuantity

`func (o *CustomerShippersApiListCustomerShipperLinesItem) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *CustomerShippersApiListCustomerShipperLinesItem) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *CustomerShippersApiListCustomerShipperLinesItem) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *CustomerShippersApiListCustomerShipperLinesItem) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetReleaseId

`func (o *CustomerShippersApiListCustomerShipperLinesItem) GetReleaseId() string`

GetReleaseId returns the ReleaseId field if non-nil, zero value otherwise.

### GetReleaseIdOk

`func (o *CustomerShippersApiListCustomerShipperLinesItem) GetReleaseIdOk() (*string, bool)`

GetReleaseIdOk returns a tuple with the ReleaseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleaseId

`func (o *CustomerShippersApiListCustomerShipperLinesItem) SetReleaseId(v string)`

SetReleaseId sets ReleaseId field to given value.

### HasReleaseId

`func (o *CustomerShippersApiListCustomerShipperLinesItem) HasReleaseId() bool`

HasReleaseId returns a boolean if a field has been set.

### GetPrice

`func (o *CustomerShippersApiListCustomerShipperLinesItem) GetPrice() float64`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *CustomerShippersApiListCustomerShipperLinesItem) GetPriceOk() (*float64, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *CustomerShippersApiListCustomerShipperLinesItem) SetPrice(v float64)`

SetPrice sets Price field to given value.

### HasPrice

`func (o *CustomerShippersApiListCustomerShipperLinesItem) HasPrice() bool`

HasPrice returns a boolean if a field has been set.

### GetCustomerPartId

`func (o *CustomerShippersApiListCustomerShipperLinesItem) GetCustomerPartId() string`

GetCustomerPartId returns the CustomerPartId field if non-nil, zero value otherwise.

### GetCustomerPartIdOk

`func (o *CustomerShippersApiListCustomerShipperLinesItem) GetCustomerPartIdOk() (*string, bool)`

GetCustomerPartIdOk returns a tuple with the CustomerPartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerPartId

`func (o *CustomerShippersApiListCustomerShipperLinesItem) SetCustomerPartId(v string)`

SetCustomerPartId sets CustomerPartId field to given value.

### HasCustomerPartId

`func (o *CustomerShippersApiListCustomerShipperLinesItem) HasCustomerPartId() bool`

HasCustomerPartId returns a boolean if a field has been set.

### GetPriceId

`func (o *CustomerShippersApiListCustomerShipperLinesItem) GetPriceId() string`

GetPriceId returns the PriceId field if non-nil, zero value otherwise.

### GetPriceIdOk

`func (o *CustomerShippersApiListCustomerShipperLinesItem) GetPriceIdOk() (*string, bool)`

GetPriceIdOk returns a tuple with the PriceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriceId

`func (o *CustomerShippersApiListCustomerShipperLinesItem) SetPriceId(v string)`

SetPriceId sets PriceId field to given value.

### HasPriceId

`func (o *CustomerShippersApiListCustomerShipperLinesItem) HasPriceId() bool`

HasPriceId returns a boolean if a field has been set.

### GetGrossWeight

`func (o *CustomerShippersApiListCustomerShipperLinesItem) GetGrossWeight() float64`

GetGrossWeight returns the GrossWeight field if non-nil, zero value otherwise.

### GetGrossWeightOk

`func (o *CustomerShippersApiListCustomerShipperLinesItem) GetGrossWeightOk() (*float64, bool)`

GetGrossWeightOk returns a tuple with the GrossWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrossWeight

`func (o *CustomerShippersApiListCustomerShipperLinesItem) SetGrossWeight(v float64)`

SetGrossWeight sets GrossWeight field to given value.

### HasGrossWeight

`func (o *CustomerShippersApiListCustomerShipperLinesItem) HasGrossWeight() bool`

HasGrossWeight returns a boolean if a field has been set.

### GetNetWeight

`func (o *CustomerShippersApiListCustomerShipperLinesItem) GetNetWeight() float64`

GetNetWeight returns the NetWeight field if non-nil, zero value otherwise.

### GetNetWeightOk

`func (o *CustomerShippersApiListCustomerShipperLinesItem) GetNetWeightOk() (*float64, bool)`

GetNetWeightOk returns a tuple with the NetWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetWeight

`func (o *CustomerShippersApiListCustomerShipperLinesItem) SetNetWeight(v float64)`

SetNetWeight sets NetWeight field to given value.

### HasNetWeight

`func (o *CustomerShippersApiListCustomerShipperLinesItem) HasNetWeight() bool`

HasNetWeight returns a boolean if a field has been set.

### GetTareWeight

`func (o *CustomerShippersApiListCustomerShipperLinesItem) GetTareWeight() float64`

GetTareWeight returns the TareWeight field if non-nil, zero value otherwise.

### GetTareWeightOk

`func (o *CustomerShippersApiListCustomerShipperLinesItem) GetTareWeightOk() (*float64, bool)`

GetTareWeightOk returns a tuple with the TareWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTareWeight

`func (o *CustomerShippersApiListCustomerShipperLinesItem) SetTareWeight(v float64)`

SetTareWeight sets TareWeight field to given value.

### HasTareWeight

`func (o *CustomerShippersApiListCustomerShipperLinesItem) HasTareWeight() bool`

HasTareWeight returns a boolean if a field has been set.

### GetShipperLineNote

`func (o *CustomerShippersApiListCustomerShipperLinesItem) GetShipperLineNote() string`

GetShipperLineNote returns the ShipperLineNote field if non-nil, zero value otherwise.

### GetShipperLineNoteOk

`func (o *CustomerShippersApiListCustomerShipperLinesItem) GetShipperLineNoteOk() (*string, bool)`

GetShipperLineNoteOk returns a tuple with the ShipperLineNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipperLineNote

`func (o *CustomerShippersApiListCustomerShipperLinesItem) SetShipperLineNote(v string)`

SetShipperLineNote sets ShipperLineNote field to given value.

### HasShipperLineNote

`func (o *CustomerShippersApiListCustomerShipperLinesItem) HasShipperLineNote() bool`

HasShipperLineNote returns a boolean if a field has been set.

### GetPackingComplete

`func (o *CustomerShippersApiListCustomerShipperLinesItem) GetPackingComplete() bool`

GetPackingComplete returns the PackingComplete field if non-nil, zero value otherwise.

### GetPackingCompleteOk

`func (o *CustomerShippersApiListCustomerShipperLinesItem) GetPackingCompleteOk() (*bool, bool)`

GetPackingCompleteOk returns a tuple with the PackingComplete field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackingComplete

`func (o *CustomerShippersApiListCustomerShipperLinesItem) SetPackingComplete(v bool)`

SetPackingComplete sets PackingComplete field to given value.

### HasPackingComplete

`func (o *CustomerShippersApiListCustomerShipperLinesItem) HasPackingComplete() bool`

HasPackingComplete returns a boolean if a field has been set.

### GetConversion

`func (o *CustomerShippersApiListCustomerShipperLinesItem) GetConversion() float64`

GetConversion returns the Conversion field if non-nil, zero value otherwise.

### GetConversionOk

`func (o *CustomerShippersApiListCustomerShipperLinesItem) GetConversionOk() (*float64, bool)`

GetConversionOk returns a tuple with the Conversion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConversion

`func (o *CustomerShippersApiListCustomerShipperLinesItem) SetConversion(v float64)`

SetConversion sets Conversion field to given value.

### HasConversion

`func (o *CustomerShippersApiListCustomerShipperLinesItem) HasConversion() bool`

HasConversion returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


