# BomApiCreateBOMComponentRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PartOperationId** | Pointer to **string** | ID of the Part Operation for which the BOM component is being created. | [optional] 
**ComponentId** | Pointer to **string** | ID of the Part or the Supply Item for which the BOM component is being created. | [optional] 
**Quantity** | Pointer to **float64** | Required quantity of the component to produce the end product. | [optional] 
**MinimumQuantity** | Pointer to **float64** | Minimum quantity required to produce the end product. | [optional] 
**MaximumQuantity** | Pointer to **float64** | Maximum quantity required to produce the end product. | [optional] 
**QuantityFixed** | Pointer to **bool** | Boolean flag to identify that regardless of the amount being produced, the quantity is a fixed required amount. | [optional] 
**DepletionUnitOfMeasure** | Pointer to **string** | Consumption unit of the BOM component to aid readability. | [optional] 
**DepletionConversionFactor** | Pointer to **float64** | Conversion factor to be used if DepletionUnitOfMeasure is set. | [optional] 
**SortOrder** | Pointer to **float64** | The order to display BOM Components. | [optional] 
**Position** | Pointer to **string** | Position to describe something physically present at the workcenter during production. | [optional] 
**Side** | Pointer to **string** | Side to determine relationships between BOM source components and multi-out parts. | [optional] 
**Scaling** | Pointer to **bool** | Boolean flag to set scaling. | [optional] 
**Validate** | Pointer to **bool** | Boolean flag to ensure that BOM material is present and loaded before allowing production to run. | [optional] 
**AutoDeplete** | Pointer to **bool** | Boolean flag to determine if the BOM material should be auto depleted as production is recorded. | [optional] 
**TransferHeat** | Pointer to **bool** | Boolean flag to indicate the heat number should be transferred from the BOM material to an output container. | [optional] 
**Note** | Pointer to **string** | Any note about the BOM Component. | [optional] 

## Methods

### NewBomApiCreateBOMComponentRequest

`func NewBomApiCreateBOMComponentRequest() *BomApiCreateBOMComponentRequest`

NewBomApiCreateBOMComponentRequest instantiates a new BomApiCreateBOMComponentRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBomApiCreateBOMComponentRequestWithDefaults

`func NewBomApiCreateBOMComponentRequestWithDefaults() *BomApiCreateBOMComponentRequest`

NewBomApiCreateBOMComponentRequestWithDefaults instantiates a new BomApiCreateBOMComponentRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPartOperationId

`func (o *BomApiCreateBOMComponentRequest) GetPartOperationId() string`

GetPartOperationId returns the PartOperationId field if non-nil, zero value otherwise.

### GetPartOperationIdOk

`func (o *BomApiCreateBOMComponentRequest) GetPartOperationIdOk() (*string, bool)`

GetPartOperationIdOk returns a tuple with the PartOperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartOperationId

`func (o *BomApiCreateBOMComponentRequest) SetPartOperationId(v string)`

SetPartOperationId sets PartOperationId field to given value.

### HasPartOperationId

`func (o *BomApiCreateBOMComponentRequest) HasPartOperationId() bool`

HasPartOperationId returns a boolean if a field has been set.

### GetComponentId

`func (o *BomApiCreateBOMComponentRequest) GetComponentId() string`

GetComponentId returns the ComponentId field if non-nil, zero value otherwise.

### GetComponentIdOk

`func (o *BomApiCreateBOMComponentRequest) GetComponentIdOk() (*string, bool)`

GetComponentIdOk returns a tuple with the ComponentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponentId

`func (o *BomApiCreateBOMComponentRequest) SetComponentId(v string)`

SetComponentId sets ComponentId field to given value.

### HasComponentId

`func (o *BomApiCreateBOMComponentRequest) HasComponentId() bool`

HasComponentId returns a boolean if a field has been set.

### GetQuantity

`func (o *BomApiCreateBOMComponentRequest) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *BomApiCreateBOMComponentRequest) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *BomApiCreateBOMComponentRequest) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *BomApiCreateBOMComponentRequest) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetMinimumQuantity

`func (o *BomApiCreateBOMComponentRequest) GetMinimumQuantity() float64`

GetMinimumQuantity returns the MinimumQuantity field if non-nil, zero value otherwise.

### GetMinimumQuantityOk

`func (o *BomApiCreateBOMComponentRequest) GetMinimumQuantityOk() (*float64, bool)`

GetMinimumQuantityOk returns a tuple with the MinimumQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinimumQuantity

`func (o *BomApiCreateBOMComponentRequest) SetMinimumQuantity(v float64)`

SetMinimumQuantity sets MinimumQuantity field to given value.

### HasMinimumQuantity

`func (o *BomApiCreateBOMComponentRequest) HasMinimumQuantity() bool`

HasMinimumQuantity returns a boolean if a field has been set.

### GetMaximumQuantity

`func (o *BomApiCreateBOMComponentRequest) GetMaximumQuantity() float64`

GetMaximumQuantity returns the MaximumQuantity field if non-nil, zero value otherwise.

### GetMaximumQuantityOk

`func (o *BomApiCreateBOMComponentRequest) GetMaximumQuantityOk() (*float64, bool)`

GetMaximumQuantityOk returns a tuple with the MaximumQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaximumQuantity

`func (o *BomApiCreateBOMComponentRequest) SetMaximumQuantity(v float64)`

SetMaximumQuantity sets MaximumQuantity field to given value.

### HasMaximumQuantity

`func (o *BomApiCreateBOMComponentRequest) HasMaximumQuantity() bool`

HasMaximumQuantity returns a boolean if a field has been set.

### GetQuantityFixed

`func (o *BomApiCreateBOMComponentRequest) GetQuantityFixed() bool`

GetQuantityFixed returns the QuantityFixed field if non-nil, zero value otherwise.

### GetQuantityFixedOk

`func (o *BomApiCreateBOMComponentRequest) GetQuantityFixedOk() (*bool, bool)`

GetQuantityFixedOk returns a tuple with the QuantityFixed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantityFixed

`func (o *BomApiCreateBOMComponentRequest) SetQuantityFixed(v bool)`

SetQuantityFixed sets QuantityFixed field to given value.

### HasQuantityFixed

`func (o *BomApiCreateBOMComponentRequest) HasQuantityFixed() bool`

HasQuantityFixed returns a boolean if a field has been set.

### GetDepletionUnitOfMeasure

`func (o *BomApiCreateBOMComponentRequest) GetDepletionUnitOfMeasure() string`

GetDepletionUnitOfMeasure returns the DepletionUnitOfMeasure field if non-nil, zero value otherwise.

### GetDepletionUnitOfMeasureOk

`func (o *BomApiCreateBOMComponentRequest) GetDepletionUnitOfMeasureOk() (*string, bool)`

GetDepletionUnitOfMeasureOk returns a tuple with the DepletionUnitOfMeasure field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDepletionUnitOfMeasure

`func (o *BomApiCreateBOMComponentRequest) SetDepletionUnitOfMeasure(v string)`

SetDepletionUnitOfMeasure sets DepletionUnitOfMeasure field to given value.

### HasDepletionUnitOfMeasure

`func (o *BomApiCreateBOMComponentRequest) HasDepletionUnitOfMeasure() bool`

HasDepletionUnitOfMeasure returns a boolean if a field has been set.

### GetDepletionConversionFactor

`func (o *BomApiCreateBOMComponentRequest) GetDepletionConversionFactor() float64`

GetDepletionConversionFactor returns the DepletionConversionFactor field if non-nil, zero value otherwise.

### GetDepletionConversionFactorOk

`func (o *BomApiCreateBOMComponentRequest) GetDepletionConversionFactorOk() (*float64, bool)`

GetDepletionConversionFactorOk returns a tuple with the DepletionConversionFactor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDepletionConversionFactor

`func (o *BomApiCreateBOMComponentRequest) SetDepletionConversionFactor(v float64)`

SetDepletionConversionFactor sets DepletionConversionFactor field to given value.

### HasDepletionConversionFactor

`func (o *BomApiCreateBOMComponentRequest) HasDepletionConversionFactor() bool`

HasDepletionConversionFactor returns a boolean if a field has been set.

### GetSortOrder

`func (o *BomApiCreateBOMComponentRequest) GetSortOrder() float64`

GetSortOrder returns the SortOrder field if non-nil, zero value otherwise.

### GetSortOrderOk

`func (o *BomApiCreateBOMComponentRequest) GetSortOrderOk() (*float64, bool)`

GetSortOrderOk returns a tuple with the SortOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSortOrder

`func (o *BomApiCreateBOMComponentRequest) SetSortOrder(v float64)`

SetSortOrder sets SortOrder field to given value.

### HasSortOrder

`func (o *BomApiCreateBOMComponentRequest) HasSortOrder() bool`

HasSortOrder returns a boolean if a field has been set.

### GetPosition

`func (o *BomApiCreateBOMComponentRequest) GetPosition() string`

GetPosition returns the Position field if non-nil, zero value otherwise.

### GetPositionOk

`func (o *BomApiCreateBOMComponentRequest) GetPositionOk() (*string, bool)`

GetPositionOk returns a tuple with the Position field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosition

`func (o *BomApiCreateBOMComponentRequest) SetPosition(v string)`

SetPosition sets Position field to given value.

### HasPosition

`func (o *BomApiCreateBOMComponentRequest) HasPosition() bool`

HasPosition returns a boolean if a field has been set.

### GetSide

`func (o *BomApiCreateBOMComponentRequest) GetSide() string`

GetSide returns the Side field if non-nil, zero value otherwise.

### GetSideOk

`func (o *BomApiCreateBOMComponentRequest) GetSideOk() (*string, bool)`

GetSideOk returns a tuple with the Side field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSide

`func (o *BomApiCreateBOMComponentRequest) SetSide(v string)`

SetSide sets Side field to given value.

### HasSide

`func (o *BomApiCreateBOMComponentRequest) HasSide() bool`

HasSide returns a boolean if a field has been set.

### GetScaling

`func (o *BomApiCreateBOMComponentRequest) GetScaling() bool`

GetScaling returns the Scaling field if non-nil, zero value otherwise.

### GetScalingOk

`func (o *BomApiCreateBOMComponentRequest) GetScalingOk() (*bool, bool)`

GetScalingOk returns a tuple with the Scaling field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScaling

`func (o *BomApiCreateBOMComponentRequest) SetScaling(v bool)`

SetScaling sets Scaling field to given value.

### HasScaling

`func (o *BomApiCreateBOMComponentRequest) HasScaling() bool`

HasScaling returns a boolean if a field has been set.

### GetValidate

`func (o *BomApiCreateBOMComponentRequest) GetValidate() bool`

GetValidate returns the Validate field if non-nil, zero value otherwise.

### GetValidateOk

`func (o *BomApiCreateBOMComponentRequest) GetValidateOk() (*bool, bool)`

GetValidateOk returns a tuple with the Validate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidate

`func (o *BomApiCreateBOMComponentRequest) SetValidate(v bool)`

SetValidate sets Validate field to given value.

### HasValidate

`func (o *BomApiCreateBOMComponentRequest) HasValidate() bool`

HasValidate returns a boolean if a field has been set.

### GetAutoDeplete

`func (o *BomApiCreateBOMComponentRequest) GetAutoDeplete() bool`

GetAutoDeplete returns the AutoDeplete field if non-nil, zero value otherwise.

### GetAutoDepleteOk

`func (o *BomApiCreateBOMComponentRequest) GetAutoDepleteOk() (*bool, bool)`

GetAutoDepleteOk returns a tuple with the AutoDeplete field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutoDeplete

`func (o *BomApiCreateBOMComponentRequest) SetAutoDeplete(v bool)`

SetAutoDeplete sets AutoDeplete field to given value.

### HasAutoDeplete

`func (o *BomApiCreateBOMComponentRequest) HasAutoDeplete() bool`

HasAutoDeplete returns a boolean if a field has been set.

### GetTransferHeat

`func (o *BomApiCreateBOMComponentRequest) GetTransferHeat() bool`

GetTransferHeat returns the TransferHeat field if non-nil, zero value otherwise.

### GetTransferHeatOk

`func (o *BomApiCreateBOMComponentRequest) GetTransferHeatOk() (*bool, bool)`

GetTransferHeatOk returns a tuple with the TransferHeat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransferHeat

`func (o *BomApiCreateBOMComponentRequest) SetTransferHeat(v bool)`

SetTransferHeat sets TransferHeat field to given value.

### HasTransferHeat

`func (o *BomApiCreateBOMComponentRequest) HasTransferHeat() bool`

HasTransferHeat returns a boolean if a field has been set.

### GetNote

`func (o *BomApiCreateBOMComponentRequest) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *BomApiCreateBOMComponentRequest) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *BomApiCreateBOMComponentRequest) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *BomApiCreateBOMComponentRequest) HasNote() bool`

HasNote returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


