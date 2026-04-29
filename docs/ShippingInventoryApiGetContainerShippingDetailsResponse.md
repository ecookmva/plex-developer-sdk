# ShippingInventoryApiGetContainerShippingDetailsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SerialNo** | Pointer to **string** | The container&#39;s serial number. | [optional] 
**ContainerType** | Pointer to **string** | The type of container. | [optional] 
**GrossWeight** | Pointer to **float64** | The gross weight of the container. | [optional] 
**NetWeight** | Pointer to **float64** | The net weight of the container. | [optional] 
**TareWeight** | Pointer to **float64** | The tare weight of the container. | [optional] 
**WeightUnit** | Pointer to **string** | The weight unit of the container. | [optional] 
**CubeHeight** | Pointer to **float64** | The cube height of the container. | [optional] 
**CubeLength** | Pointer to **float64** | The cube length of the container. | [optional] 
**CubeWidth** | Pointer to **float64** | The cube width of the container. | [optional] 
**DimensionUnit** | Pointer to **string** | The dimension unit used for the container. | [optional] 
**CommodityCode** | Pointer to **string** | The commodity code associated with the container. | [optional] 
**HarmonizedTariffCode** | Pointer to **string** | The harmonized tariff code associated with the container. | [optional] 
**Hazardous** | Pointer to **bool** | Indicates whether the container contents are hazardous or not. | [optional] 
**FreightClassification** | Pointer to **string** | The freight classification associated with the container. | [optional] 
**WeightClassification** | Pointer to **string** | The weight classification associated with the container. | [optional] 
**MasterUnitNo** | Pointer to **string** | The master unit number associated with the container. | [optional] 
**MasterUnitId** | Pointer to **string** | The master unit ID. | [optional] 

## Methods

### NewShippingInventoryApiGetContainerShippingDetailsResponse

`func NewShippingInventoryApiGetContainerShippingDetailsResponse() *ShippingInventoryApiGetContainerShippingDetailsResponse`

NewShippingInventoryApiGetContainerShippingDetailsResponse instantiates a new ShippingInventoryApiGetContainerShippingDetailsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewShippingInventoryApiGetContainerShippingDetailsResponseWithDefaults

`func NewShippingInventoryApiGetContainerShippingDetailsResponseWithDefaults() *ShippingInventoryApiGetContainerShippingDetailsResponse`

NewShippingInventoryApiGetContainerShippingDetailsResponseWithDefaults instantiates a new ShippingInventoryApiGetContainerShippingDetailsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSerialNo

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) GetSerialNo() string`

GetSerialNo returns the SerialNo field if non-nil, zero value otherwise.

### GetSerialNoOk

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) GetSerialNoOk() (*string, bool)`

GetSerialNoOk returns a tuple with the SerialNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSerialNo

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) SetSerialNo(v string)`

SetSerialNo sets SerialNo field to given value.

### HasSerialNo

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) HasSerialNo() bool`

HasSerialNo returns a boolean if a field has been set.

### GetContainerType

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) GetContainerType() string`

GetContainerType returns the ContainerType field if non-nil, zero value otherwise.

### GetContainerTypeOk

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) GetContainerTypeOk() (*string, bool)`

GetContainerTypeOk returns a tuple with the ContainerType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContainerType

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) SetContainerType(v string)`

SetContainerType sets ContainerType field to given value.

### HasContainerType

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) HasContainerType() bool`

HasContainerType returns a boolean if a field has been set.

### GetGrossWeight

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) GetGrossWeight() float64`

GetGrossWeight returns the GrossWeight field if non-nil, zero value otherwise.

### GetGrossWeightOk

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) GetGrossWeightOk() (*float64, bool)`

GetGrossWeightOk returns a tuple with the GrossWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrossWeight

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) SetGrossWeight(v float64)`

SetGrossWeight sets GrossWeight field to given value.

### HasGrossWeight

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) HasGrossWeight() bool`

HasGrossWeight returns a boolean if a field has been set.

### GetNetWeight

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) GetNetWeight() float64`

GetNetWeight returns the NetWeight field if non-nil, zero value otherwise.

### GetNetWeightOk

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) GetNetWeightOk() (*float64, bool)`

GetNetWeightOk returns a tuple with the NetWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetWeight

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) SetNetWeight(v float64)`

SetNetWeight sets NetWeight field to given value.

### HasNetWeight

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) HasNetWeight() bool`

HasNetWeight returns a boolean if a field has been set.

### GetTareWeight

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) GetTareWeight() float64`

GetTareWeight returns the TareWeight field if non-nil, zero value otherwise.

### GetTareWeightOk

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) GetTareWeightOk() (*float64, bool)`

GetTareWeightOk returns a tuple with the TareWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTareWeight

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) SetTareWeight(v float64)`

SetTareWeight sets TareWeight field to given value.

### HasTareWeight

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) HasTareWeight() bool`

HasTareWeight returns a boolean if a field has been set.

### GetWeightUnit

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) GetWeightUnit() string`

GetWeightUnit returns the WeightUnit field if non-nil, zero value otherwise.

### GetWeightUnitOk

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) GetWeightUnitOk() (*string, bool)`

GetWeightUnitOk returns a tuple with the WeightUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeightUnit

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) SetWeightUnit(v string)`

SetWeightUnit sets WeightUnit field to given value.

### HasWeightUnit

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) HasWeightUnit() bool`

HasWeightUnit returns a boolean if a field has been set.

### GetCubeHeight

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) GetCubeHeight() float64`

GetCubeHeight returns the CubeHeight field if non-nil, zero value otherwise.

### GetCubeHeightOk

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) GetCubeHeightOk() (*float64, bool)`

GetCubeHeightOk returns a tuple with the CubeHeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCubeHeight

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) SetCubeHeight(v float64)`

SetCubeHeight sets CubeHeight field to given value.

### HasCubeHeight

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) HasCubeHeight() bool`

HasCubeHeight returns a boolean if a field has been set.

### GetCubeLength

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) GetCubeLength() float64`

GetCubeLength returns the CubeLength field if non-nil, zero value otherwise.

### GetCubeLengthOk

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) GetCubeLengthOk() (*float64, bool)`

GetCubeLengthOk returns a tuple with the CubeLength field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCubeLength

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) SetCubeLength(v float64)`

SetCubeLength sets CubeLength field to given value.

### HasCubeLength

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) HasCubeLength() bool`

HasCubeLength returns a boolean if a field has been set.

### GetCubeWidth

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) GetCubeWidth() float64`

GetCubeWidth returns the CubeWidth field if non-nil, zero value otherwise.

### GetCubeWidthOk

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) GetCubeWidthOk() (*float64, bool)`

GetCubeWidthOk returns a tuple with the CubeWidth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCubeWidth

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) SetCubeWidth(v float64)`

SetCubeWidth sets CubeWidth field to given value.

### HasCubeWidth

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) HasCubeWidth() bool`

HasCubeWidth returns a boolean if a field has been set.

### GetDimensionUnit

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) GetDimensionUnit() string`

GetDimensionUnit returns the DimensionUnit field if non-nil, zero value otherwise.

### GetDimensionUnitOk

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) GetDimensionUnitOk() (*string, bool)`

GetDimensionUnitOk returns a tuple with the DimensionUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDimensionUnit

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) SetDimensionUnit(v string)`

SetDimensionUnit sets DimensionUnit field to given value.

### HasDimensionUnit

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) HasDimensionUnit() bool`

HasDimensionUnit returns a boolean if a field has been set.

### GetCommodityCode

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) GetCommodityCode() string`

GetCommodityCode returns the CommodityCode field if non-nil, zero value otherwise.

### GetCommodityCodeOk

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) GetCommodityCodeOk() (*string, bool)`

GetCommodityCodeOk returns a tuple with the CommodityCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCommodityCode

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) SetCommodityCode(v string)`

SetCommodityCode sets CommodityCode field to given value.

### HasCommodityCode

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) HasCommodityCode() bool`

HasCommodityCode returns a boolean if a field has been set.

### GetHarmonizedTariffCode

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) GetHarmonizedTariffCode() string`

GetHarmonizedTariffCode returns the HarmonizedTariffCode field if non-nil, zero value otherwise.

### GetHarmonizedTariffCodeOk

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) GetHarmonizedTariffCodeOk() (*string, bool)`

GetHarmonizedTariffCodeOk returns a tuple with the HarmonizedTariffCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHarmonizedTariffCode

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) SetHarmonizedTariffCode(v string)`

SetHarmonizedTariffCode sets HarmonizedTariffCode field to given value.

### HasHarmonizedTariffCode

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) HasHarmonizedTariffCode() bool`

HasHarmonizedTariffCode returns a boolean if a field has been set.

### GetHazardous

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) GetHazardous() bool`

GetHazardous returns the Hazardous field if non-nil, zero value otherwise.

### GetHazardousOk

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) GetHazardousOk() (*bool, bool)`

GetHazardousOk returns a tuple with the Hazardous field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHazardous

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) SetHazardous(v bool)`

SetHazardous sets Hazardous field to given value.

### HasHazardous

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) HasHazardous() bool`

HasHazardous returns a boolean if a field has been set.

### GetFreightClassification

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) GetFreightClassification() string`

GetFreightClassification returns the FreightClassification field if non-nil, zero value otherwise.

### GetFreightClassificationOk

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) GetFreightClassificationOk() (*string, bool)`

GetFreightClassificationOk returns a tuple with the FreightClassification field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFreightClassification

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) SetFreightClassification(v string)`

SetFreightClassification sets FreightClassification field to given value.

### HasFreightClassification

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) HasFreightClassification() bool`

HasFreightClassification returns a boolean if a field has been set.

### GetWeightClassification

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) GetWeightClassification() string`

GetWeightClassification returns the WeightClassification field if non-nil, zero value otherwise.

### GetWeightClassificationOk

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) GetWeightClassificationOk() (*string, bool)`

GetWeightClassificationOk returns a tuple with the WeightClassification field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeightClassification

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) SetWeightClassification(v string)`

SetWeightClassification sets WeightClassification field to given value.

### HasWeightClassification

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) HasWeightClassification() bool`

HasWeightClassification returns a boolean if a field has been set.

### GetMasterUnitNo

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) GetMasterUnitNo() string`

GetMasterUnitNo returns the MasterUnitNo field if non-nil, zero value otherwise.

### GetMasterUnitNoOk

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) GetMasterUnitNoOk() (*string, bool)`

GetMasterUnitNoOk returns a tuple with the MasterUnitNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMasterUnitNo

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) SetMasterUnitNo(v string)`

SetMasterUnitNo sets MasterUnitNo field to given value.

### HasMasterUnitNo

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) HasMasterUnitNo() bool`

HasMasterUnitNo returns a boolean if a field has been set.

### GetMasterUnitId

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) GetMasterUnitId() string`

GetMasterUnitId returns the MasterUnitId field if non-nil, zero value otherwise.

### GetMasterUnitIdOk

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) GetMasterUnitIdOk() (*string, bool)`

GetMasterUnitIdOk returns a tuple with the MasterUnitId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMasterUnitId

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) SetMasterUnitId(v string)`

SetMasterUnitId sets MasterUnitId field to given value.

### HasMasterUnitId

`func (o *ShippingInventoryApiGetContainerShippingDetailsResponse) HasMasterUnitId() bool`

HasMasterUnitId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


