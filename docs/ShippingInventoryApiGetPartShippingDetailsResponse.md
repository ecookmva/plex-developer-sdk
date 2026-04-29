# ShippingInventoryApiGetPartShippingDetailsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PartId** | Pointer to **string** | A unique identifier for the part. | [optional] 
**PartNumber** | Pointer to **string** | The part&#39;s number. | [optional] 
**PartRevision** | Pointer to **string** | The part&#39;s revision. | [optional] 
**PartNumberRevision** | Pointer to **string** | The part&#39;s number and revision number, including the revision separator. | [optional] 
**ContainerType** | Pointer to **string** | The container type. | [optional] 
**PartPieceWeight** | Pointer to **float64** | The piece weight of the part. | [optional] 
**WeightUnit** | Pointer to **string** | The weight unit of the container. | [optional] 
**CubeHeight** | Pointer to **float64** | The cube height of the container. | [optional] 
**CubeLength** | Pointer to **float64** | The cube length of the container. | [optional] 
**CubeWidth** | Pointer to **float64** | The cube width of the container. | [optional] 
**CommodityCode** | Pointer to **string** | The commodity code associated with the container. | [optional] 
**HarmonizedTariffCode** | Pointer to **string** | The harmonized tariff code associated with the container. | [optional] 
**Hazardous** | Pointer to **bool** | Indicates whether the container contents are hazardous or not. | [optional] 
**FreightClassification** | Pointer to **string** | The freight classification associated with the container. | [optional] 
**WeightClassification** | Pointer to **string** | The weight classification associated with the container. | [optional] 

## Methods

### NewShippingInventoryApiGetPartShippingDetailsResponse

`func NewShippingInventoryApiGetPartShippingDetailsResponse() *ShippingInventoryApiGetPartShippingDetailsResponse`

NewShippingInventoryApiGetPartShippingDetailsResponse instantiates a new ShippingInventoryApiGetPartShippingDetailsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewShippingInventoryApiGetPartShippingDetailsResponseWithDefaults

`func NewShippingInventoryApiGetPartShippingDetailsResponseWithDefaults() *ShippingInventoryApiGetPartShippingDetailsResponse`

NewShippingInventoryApiGetPartShippingDetailsResponseWithDefaults instantiates a new ShippingInventoryApiGetPartShippingDetailsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPartId

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetPartNumber

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) GetPartNumber() string`

GetPartNumber returns the PartNumber field if non-nil, zero value otherwise.

### GetPartNumberOk

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) GetPartNumberOk() (*string, bool)`

GetPartNumberOk returns a tuple with the PartNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumber

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) SetPartNumber(v string)`

SetPartNumber sets PartNumber field to given value.

### HasPartNumber

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) HasPartNumber() bool`

HasPartNumber returns a boolean if a field has been set.

### GetPartRevision

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) GetPartRevision() string`

GetPartRevision returns the PartRevision field if non-nil, zero value otherwise.

### GetPartRevisionOk

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) GetPartRevisionOk() (*string, bool)`

GetPartRevisionOk returns a tuple with the PartRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartRevision

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) SetPartRevision(v string)`

SetPartRevision sets PartRevision field to given value.

### HasPartRevision

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) HasPartRevision() bool`

HasPartRevision returns a boolean if a field has been set.

### GetPartNumberRevision

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) GetPartNumberRevision() string`

GetPartNumberRevision returns the PartNumberRevision field if non-nil, zero value otherwise.

### GetPartNumberRevisionOk

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) GetPartNumberRevisionOk() (*string, bool)`

GetPartNumberRevisionOk returns a tuple with the PartNumberRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumberRevision

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) SetPartNumberRevision(v string)`

SetPartNumberRevision sets PartNumberRevision field to given value.

### HasPartNumberRevision

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) HasPartNumberRevision() bool`

HasPartNumberRevision returns a boolean if a field has been set.

### GetContainerType

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) GetContainerType() string`

GetContainerType returns the ContainerType field if non-nil, zero value otherwise.

### GetContainerTypeOk

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) GetContainerTypeOk() (*string, bool)`

GetContainerTypeOk returns a tuple with the ContainerType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContainerType

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) SetContainerType(v string)`

SetContainerType sets ContainerType field to given value.

### HasContainerType

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) HasContainerType() bool`

HasContainerType returns a boolean if a field has been set.

### GetPartPieceWeight

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) GetPartPieceWeight() float64`

GetPartPieceWeight returns the PartPieceWeight field if non-nil, zero value otherwise.

### GetPartPieceWeightOk

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) GetPartPieceWeightOk() (*float64, bool)`

GetPartPieceWeightOk returns a tuple with the PartPieceWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartPieceWeight

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) SetPartPieceWeight(v float64)`

SetPartPieceWeight sets PartPieceWeight field to given value.

### HasPartPieceWeight

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) HasPartPieceWeight() bool`

HasPartPieceWeight returns a boolean if a field has been set.

### GetWeightUnit

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) GetWeightUnit() string`

GetWeightUnit returns the WeightUnit field if non-nil, zero value otherwise.

### GetWeightUnitOk

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) GetWeightUnitOk() (*string, bool)`

GetWeightUnitOk returns a tuple with the WeightUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeightUnit

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) SetWeightUnit(v string)`

SetWeightUnit sets WeightUnit field to given value.

### HasWeightUnit

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) HasWeightUnit() bool`

HasWeightUnit returns a boolean if a field has been set.

### GetCubeHeight

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) GetCubeHeight() float64`

GetCubeHeight returns the CubeHeight field if non-nil, zero value otherwise.

### GetCubeHeightOk

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) GetCubeHeightOk() (*float64, bool)`

GetCubeHeightOk returns a tuple with the CubeHeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCubeHeight

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) SetCubeHeight(v float64)`

SetCubeHeight sets CubeHeight field to given value.

### HasCubeHeight

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) HasCubeHeight() bool`

HasCubeHeight returns a boolean if a field has been set.

### GetCubeLength

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) GetCubeLength() float64`

GetCubeLength returns the CubeLength field if non-nil, zero value otherwise.

### GetCubeLengthOk

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) GetCubeLengthOk() (*float64, bool)`

GetCubeLengthOk returns a tuple with the CubeLength field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCubeLength

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) SetCubeLength(v float64)`

SetCubeLength sets CubeLength field to given value.

### HasCubeLength

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) HasCubeLength() bool`

HasCubeLength returns a boolean if a field has been set.

### GetCubeWidth

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) GetCubeWidth() float64`

GetCubeWidth returns the CubeWidth field if non-nil, zero value otherwise.

### GetCubeWidthOk

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) GetCubeWidthOk() (*float64, bool)`

GetCubeWidthOk returns a tuple with the CubeWidth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCubeWidth

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) SetCubeWidth(v float64)`

SetCubeWidth sets CubeWidth field to given value.

### HasCubeWidth

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) HasCubeWidth() bool`

HasCubeWidth returns a boolean if a field has been set.

### GetCommodityCode

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) GetCommodityCode() string`

GetCommodityCode returns the CommodityCode field if non-nil, zero value otherwise.

### GetCommodityCodeOk

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) GetCommodityCodeOk() (*string, bool)`

GetCommodityCodeOk returns a tuple with the CommodityCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCommodityCode

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) SetCommodityCode(v string)`

SetCommodityCode sets CommodityCode field to given value.

### HasCommodityCode

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) HasCommodityCode() bool`

HasCommodityCode returns a boolean if a field has been set.

### GetHarmonizedTariffCode

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) GetHarmonizedTariffCode() string`

GetHarmonizedTariffCode returns the HarmonizedTariffCode field if non-nil, zero value otherwise.

### GetHarmonizedTariffCodeOk

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) GetHarmonizedTariffCodeOk() (*string, bool)`

GetHarmonizedTariffCodeOk returns a tuple with the HarmonizedTariffCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHarmonizedTariffCode

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) SetHarmonizedTariffCode(v string)`

SetHarmonizedTariffCode sets HarmonizedTariffCode field to given value.

### HasHarmonizedTariffCode

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) HasHarmonizedTariffCode() bool`

HasHarmonizedTariffCode returns a boolean if a field has been set.

### GetHazardous

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) GetHazardous() bool`

GetHazardous returns the Hazardous field if non-nil, zero value otherwise.

### GetHazardousOk

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) GetHazardousOk() (*bool, bool)`

GetHazardousOk returns a tuple with the Hazardous field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHazardous

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) SetHazardous(v bool)`

SetHazardous sets Hazardous field to given value.

### HasHazardous

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) HasHazardous() bool`

HasHazardous returns a boolean if a field has been set.

### GetFreightClassification

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) GetFreightClassification() string`

GetFreightClassification returns the FreightClassification field if non-nil, zero value otherwise.

### GetFreightClassificationOk

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) GetFreightClassificationOk() (*string, bool)`

GetFreightClassificationOk returns a tuple with the FreightClassification field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFreightClassification

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) SetFreightClassification(v string)`

SetFreightClassification sets FreightClassification field to given value.

### HasFreightClassification

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) HasFreightClassification() bool`

HasFreightClassification returns a boolean if a field has been set.

### GetWeightClassification

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) GetWeightClassification() string`

GetWeightClassification returns the WeightClassification field if non-nil, zero value otherwise.

### GetWeightClassificationOk

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) GetWeightClassificationOk() (*string, bool)`

GetWeightClassificationOk returns a tuple with the WeightClassification field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeightClassification

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) SetWeightClassification(v string)`

SetWeightClassification sets WeightClassification field to given value.

### HasWeightClassification

`func (o *ShippingInventoryApiGetPartShippingDetailsResponse) HasWeightClassification() bool`

HasWeightClassification returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


