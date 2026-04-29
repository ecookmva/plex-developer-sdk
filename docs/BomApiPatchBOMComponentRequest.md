# BomApiPatchBOMComponentRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Quantity** | Pointer to **float64** | The quantity being consumed. | [optional] 
**MinimumQuantity** | Pointer to **float64** | For variable Boms where the consumption and batch size can vary, this is the minimum required quantity. | [optional] 
**MaximumQuantity** | Pointer to **float64** | For variable Boms where the consumption and batch size can vary, this is the maximum required quantity. | [optional] 
**QuantityFixed** | Pointer to **bool** | For variable Boms where the consumption and batch size can vary, this indicates that the component quantity is a fixed required amount regardless of the amount being produced. | [optional] 
**DepletionUnitOfMeasure** | Pointer to **string** | For variable Boms where the consumption unit is very different than the Boms material&#39;s inventory unit (eg. grams vs kg), this value defines the unit of measure for a variable bom. | [optional] 
**DepletionConversionFactor** | Pointer to **float64** | The conversion factor to use if the DepletionUnitOfMeasure field is set. | [optional] 
**SortOrder** | Pointer to **float64** | The sort order of this Bom resource. | [optional] 
**Position** | Pointer to **string** | Position of the Bom resource. | [optional] 
**Side** | Pointer to **string** | Side related to the Bom resource. | [optional] 
**Scaling** | Pointer to **bool** | A flag that determines if the Bom is scaling. | [optional] 
**Validate** | Pointer to **bool** | A flag that determines if the Bom is validate. | [optional] 
**AutoDeplete** | Pointer to **bool** | A flag that determines if the Bom is set for auto depletion. | [optional] 
**TransferHeat** | Pointer to **bool** | A flag that determines the value for transfer heat. | [optional] 
**Note** | Pointer to **string** | A note about the Bom Component. | [optional] 

## Methods

### NewBomApiPatchBOMComponentRequest

`func NewBomApiPatchBOMComponentRequest() *BomApiPatchBOMComponentRequest`

NewBomApiPatchBOMComponentRequest instantiates a new BomApiPatchBOMComponentRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBomApiPatchBOMComponentRequestWithDefaults

`func NewBomApiPatchBOMComponentRequestWithDefaults() *BomApiPatchBOMComponentRequest`

NewBomApiPatchBOMComponentRequestWithDefaults instantiates a new BomApiPatchBOMComponentRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetQuantity

`func (o *BomApiPatchBOMComponentRequest) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *BomApiPatchBOMComponentRequest) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *BomApiPatchBOMComponentRequest) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *BomApiPatchBOMComponentRequest) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetMinimumQuantity

`func (o *BomApiPatchBOMComponentRequest) GetMinimumQuantity() float64`

GetMinimumQuantity returns the MinimumQuantity field if non-nil, zero value otherwise.

### GetMinimumQuantityOk

`func (o *BomApiPatchBOMComponentRequest) GetMinimumQuantityOk() (*float64, bool)`

GetMinimumQuantityOk returns a tuple with the MinimumQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinimumQuantity

`func (o *BomApiPatchBOMComponentRequest) SetMinimumQuantity(v float64)`

SetMinimumQuantity sets MinimumQuantity field to given value.

### HasMinimumQuantity

`func (o *BomApiPatchBOMComponentRequest) HasMinimumQuantity() bool`

HasMinimumQuantity returns a boolean if a field has been set.

### GetMaximumQuantity

`func (o *BomApiPatchBOMComponentRequest) GetMaximumQuantity() float64`

GetMaximumQuantity returns the MaximumQuantity field if non-nil, zero value otherwise.

### GetMaximumQuantityOk

`func (o *BomApiPatchBOMComponentRequest) GetMaximumQuantityOk() (*float64, bool)`

GetMaximumQuantityOk returns a tuple with the MaximumQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaximumQuantity

`func (o *BomApiPatchBOMComponentRequest) SetMaximumQuantity(v float64)`

SetMaximumQuantity sets MaximumQuantity field to given value.

### HasMaximumQuantity

`func (o *BomApiPatchBOMComponentRequest) HasMaximumQuantity() bool`

HasMaximumQuantity returns a boolean if a field has been set.

### GetQuantityFixed

`func (o *BomApiPatchBOMComponentRequest) GetQuantityFixed() bool`

GetQuantityFixed returns the QuantityFixed field if non-nil, zero value otherwise.

### GetQuantityFixedOk

`func (o *BomApiPatchBOMComponentRequest) GetQuantityFixedOk() (*bool, bool)`

GetQuantityFixedOk returns a tuple with the QuantityFixed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantityFixed

`func (o *BomApiPatchBOMComponentRequest) SetQuantityFixed(v bool)`

SetQuantityFixed sets QuantityFixed field to given value.

### HasQuantityFixed

`func (o *BomApiPatchBOMComponentRequest) HasQuantityFixed() bool`

HasQuantityFixed returns a boolean if a field has been set.

### GetDepletionUnitOfMeasure

`func (o *BomApiPatchBOMComponentRequest) GetDepletionUnitOfMeasure() string`

GetDepletionUnitOfMeasure returns the DepletionUnitOfMeasure field if non-nil, zero value otherwise.

### GetDepletionUnitOfMeasureOk

`func (o *BomApiPatchBOMComponentRequest) GetDepletionUnitOfMeasureOk() (*string, bool)`

GetDepletionUnitOfMeasureOk returns a tuple with the DepletionUnitOfMeasure field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDepletionUnitOfMeasure

`func (o *BomApiPatchBOMComponentRequest) SetDepletionUnitOfMeasure(v string)`

SetDepletionUnitOfMeasure sets DepletionUnitOfMeasure field to given value.

### HasDepletionUnitOfMeasure

`func (o *BomApiPatchBOMComponentRequest) HasDepletionUnitOfMeasure() bool`

HasDepletionUnitOfMeasure returns a boolean if a field has been set.

### GetDepletionConversionFactor

`func (o *BomApiPatchBOMComponentRequest) GetDepletionConversionFactor() float64`

GetDepletionConversionFactor returns the DepletionConversionFactor field if non-nil, zero value otherwise.

### GetDepletionConversionFactorOk

`func (o *BomApiPatchBOMComponentRequest) GetDepletionConversionFactorOk() (*float64, bool)`

GetDepletionConversionFactorOk returns a tuple with the DepletionConversionFactor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDepletionConversionFactor

`func (o *BomApiPatchBOMComponentRequest) SetDepletionConversionFactor(v float64)`

SetDepletionConversionFactor sets DepletionConversionFactor field to given value.

### HasDepletionConversionFactor

`func (o *BomApiPatchBOMComponentRequest) HasDepletionConversionFactor() bool`

HasDepletionConversionFactor returns a boolean if a field has been set.

### GetSortOrder

`func (o *BomApiPatchBOMComponentRequest) GetSortOrder() float64`

GetSortOrder returns the SortOrder field if non-nil, zero value otherwise.

### GetSortOrderOk

`func (o *BomApiPatchBOMComponentRequest) GetSortOrderOk() (*float64, bool)`

GetSortOrderOk returns a tuple with the SortOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSortOrder

`func (o *BomApiPatchBOMComponentRequest) SetSortOrder(v float64)`

SetSortOrder sets SortOrder field to given value.

### HasSortOrder

`func (o *BomApiPatchBOMComponentRequest) HasSortOrder() bool`

HasSortOrder returns a boolean if a field has been set.

### GetPosition

`func (o *BomApiPatchBOMComponentRequest) GetPosition() string`

GetPosition returns the Position field if non-nil, zero value otherwise.

### GetPositionOk

`func (o *BomApiPatchBOMComponentRequest) GetPositionOk() (*string, bool)`

GetPositionOk returns a tuple with the Position field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosition

`func (o *BomApiPatchBOMComponentRequest) SetPosition(v string)`

SetPosition sets Position field to given value.

### HasPosition

`func (o *BomApiPatchBOMComponentRequest) HasPosition() bool`

HasPosition returns a boolean if a field has been set.

### GetSide

`func (o *BomApiPatchBOMComponentRequest) GetSide() string`

GetSide returns the Side field if non-nil, zero value otherwise.

### GetSideOk

`func (o *BomApiPatchBOMComponentRequest) GetSideOk() (*string, bool)`

GetSideOk returns a tuple with the Side field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSide

`func (o *BomApiPatchBOMComponentRequest) SetSide(v string)`

SetSide sets Side field to given value.

### HasSide

`func (o *BomApiPatchBOMComponentRequest) HasSide() bool`

HasSide returns a boolean if a field has been set.

### GetScaling

`func (o *BomApiPatchBOMComponentRequest) GetScaling() bool`

GetScaling returns the Scaling field if non-nil, zero value otherwise.

### GetScalingOk

`func (o *BomApiPatchBOMComponentRequest) GetScalingOk() (*bool, bool)`

GetScalingOk returns a tuple with the Scaling field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScaling

`func (o *BomApiPatchBOMComponentRequest) SetScaling(v bool)`

SetScaling sets Scaling field to given value.

### HasScaling

`func (o *BomApiPatchBOMComponentRequest) HasScaling() bool`

HasScaling returns a boolean if a field has been set.

### GetValidate

`func (o *BomApiPatchBOMComponentRequest) GetValidate() bool`

GetValidate returns the Validate field if non-nil, zero value otherwise.

### GetValidateOk

`func (o *BomApiPatchBOMComponentRequest) GetValidateOk() (*bool, bool)`

GetValidateOk returns a tuple with the Validate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidate

`func (o *BomApiPatchBOMComponentRequest) SetValidate(v bool)`

SetValidate sets Validate field to given value.

### HasValidate

`func (o *BomApiPatchBOMComponentRequest) HasValidate() bool`

HasValidate returns a boolean if a field has been set.

### GetAutoDeplete

`func (o *BomApiPatchBOMComponentRequest) GetAutoDeplete() bool`

GetAutoDeplete returns the AutoDeplete field if non-nil, zero value otherwise.

### GetAutoDepleteOk

`func (o *BomApiPatchBOMComponentRequest) GetAutoDepleteOk() (*bool, bool)`

GetAutoDepleteOk returns a tuple with the AutoDeplete field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutoDeplete

`func (o *BomApiPatchBOMComponentRequest) SetAutoDeplete(v bool)`

SetAutoDeplete sets AutoDeplete field to given value.

### HasAutoDeplete

`func (o *BomApiPatchBOMComponentRequest) HasAutoDeplete() bool`

HasAutoDeplete returns a boolean if a field has been set.

### GetTransferHeat

`func (o *BomApiPatchBOMComponentRequest) GetTransferHeat() bool`

GetTransferHeat returns the TransferHeat field if non-nil, zero value otherwise.

### GetTransferHeatOk

`func (o *BomApiPatchBOMComponentRequest) GetTransferHeatOk() (*bool, bool)`

GetTransferHeatOk returns a tuple with the TransferHeat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransferHeat

`func (o *BomApiPatchBOMComponentRequest) SetTransferHeat(v bool)`

SetTransferHeat sets TransferHeat field to given value.

### HasTransferHeat

`func (o *BomApiPatchBOMComponentRequest) HasTransferHeat() bool`

HasTransferHeat returns a boolean if a field has been set.

### GetNote

`func (o *BomApiPatchBOMComponentRequest) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *BomApiPatchBOMComponentRequest) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *BomApiPatchBOMComponentRequest) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *BomApiPatchBOMComponentRequest) HasNote() bool`

HasNote returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


