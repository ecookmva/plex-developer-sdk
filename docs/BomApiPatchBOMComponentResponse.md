# BomApiPatchBOMComponentResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | A unique identifier for a Bom component. | [optional] 
**PartId** | Pointer to **string** | A unique identifier for a Part resource. | [optional] 
**PartNumber** | Pointer to **string** | Part number associated to a part. | [optional] 
**PartRevision** | Pointer to **string** | Part revision associated to a part. | [optional] 
**PartNumberRevision** | Pointer to **string** | Combination of PartNumber and PartRevision separated by the PCN specific separator. | [optional] 
**PartOperationId** | Pointer to **string** | A unique identifier for a PartOperation resource. | [optional] 
**PartOperationCode** | Pointer to **string** | Part operation code associated with the PartOperation. | [optional] 
**PartOperationNumber** | Pointer to **int32** | Part operation number associated with the PartOperation. | [optional] 
**PartOperationType** | Pointer to **string** | Part operation type associated with the PartOperation. | [optional] 
**ComponentPartId** | Pointer to **string** | ID of the component part against which this Bom component is related. Will be null if the ComponentSupplyItemId is present. | [optional] 
**ComponentPartNumber** | Pointer to **string** | Part number associated to the component part. | [optional] 
**ComponentPartRevision** | Pointer to **string** | Part revision associated to the component part. | [optional] 
**ComponentPartNumberRevision** | Pointer to **string** | Combination of ComponentPartNumber and ComponentPartRevision separated by the PCN specific separator. | [optional] 
**ComponentSupplyItemId** | Pointer to **string** | ID of the component supply-item against which this Bom component is related. Will be null if the ComponentPartId is present. | [optional] 
**ComponentSupplyItemNumber** | Pointer to **string** | Supply item number associated with the component supply item. | [optional] 
**ComponentUnitOfMeasure** | Pointer to **string** | The unit of measure for the component part or supply item. | [optional] 
**Quantity** | Pointer to **float64** | The quantity being consumed. | [optional] 
**MinimumQuantity** | Pointer to **float64** | For variable Boms where the consumption and batch size can vary, this is the minimum required quantity. | [optional] 
**MaximumQuantity** | Pointer to **float64** | For variable Boms where the consumption and batch size can vary, this is the maximum required quantity. | [optional] 
**QuantityFixed** | Pointer to **bool** | For variable Boms where the consumption and batch size can vary, this indicates that the component quantity is a fixed required amount regardless of the amount being produced. | [optional] 
**DepletionUnitOfMeasure** | Pointer to **string** | For variable Boms where the consumption unit is very different than the Boms material&#39;s inventory unit (eg. grams vs kg), this value defines the unit of measure for a variable bom. | [optional] 
**DepletionConversionFactor** | Pointer to **float64** | The conversion factor to use if the DepletionUnitOfMeasure field is set. | [optional] 
**SortOrder** | Pointer to **float64** | The sort order of this Bom resource. | [optional] 
**Active** | Pointer to **bool** | A flag that determines if the Bom is active. | [optional] 
**Position** | Pointer to **string** | Position of the Bom resource. | [optional] 
**Side** | Pointer to **string** | Side related to the Bom resource. | [optional] 
**Scaling** | Pointer to **bool** | A flag that determines if the Bom is scaling. | [optional] 
**Validate** | Pointer to **bool** | A flag that determines if the Bom is validate. | [optional] 
**AutoDeplete** | Pointer to **bool** | A flag that determines if the Bom is set for auto depletion. | [optional] 
**TransferHeat** | Pointer to **bool** | A flag that determines the value for transfer heat. | [optional] 
**Note** | Pointer to **string** | A note about the Bom Component. | [optional] 

## Methods

### NewBomApiPatchBOMComponentResponse

`func NewBomApiPatchBOMComponentResponse() *BomApiPatchBOMComponentResponse`

NewBomApiPatchBOMComponentResponse instantiates a new BomApiPatchBOMComponentResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBomApiPatchBOMComponentResponseWithDefaults

`func NewBomApiPatchBOMComponentResponseWithDefaults() *BomApiPatchBOMComponentResponse`

NewBomApiPatchBOMComponentResponseWithDefaults instantiates a new BomApiPatchBOMComponentResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *BomApiPatchBOMComponentResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *BomApiPatchBOMComponentResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *BomApiPatchBOMComponentResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *BomApiPatchBOMComponentResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetPartId

`func (o *BomApiPatchBOMComponentResponse) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *BomApiPatchBOMComponentResponse) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *BomApiPatchBOMComponentResponse) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *BomApiPatchBOMComponentResponse) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetPartNumber

`func (o *BomApiPatchBOMComponentResponse) GetPartNumber() string`

GetPartNumber returns the PartNumber field if non-nil, zero value otherwise.

### GetPartNumberOk

`func (o *BomApiPatchBOMComponentResponse) GetPartNumberOk() (*string, bool)`

GetPartNumberOk returns a tuple with the PartNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumber

`func (o *BomApiPatchBOMComponentResponse) SetPartNumber(v string)`

SetPartNumber sets PartNumber field to given value.

### HasPartNumber

`func (o *BomApiPatchBOMComponentResponse) HasPartNumber() bool`

HasPartNumber returns a boolean if a field has been set.

### GetPartRevision

`func (o *BomApiPatchBOMComponentResponse) GetPartRevision() string`

GetPartRevision returns the PartRevision field if non-nil, zero value otherwise.

### GetPartRevisionOk

`func (o *BomApiPatchBOMComponentResponse) GetPartRevisionOk() (*string, bool)`

GetPartRevisionOk returns a tuple with the PartRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartRevision

`func (o *BomApiPatchBOMComponentResponse) SetPartRevision(v string)`

SetPartRevision sets PartRevision field to given value.

### HasPartRevision

`func (o *BomApiPatchBOMComponentResponse) HasPartRevision() bool`

HasPartRevision returns a boolean if a field has been set.

### GetPartNumberRevision

`func (o *BomApiPatchBOMComponentResponse) GetPartNumberRevision() string`

GetPartNumberRevision returns the PartNumberRevision field if non-nil, zero value otherwise.

### GetPartNumberRevisionOk

`func (o *BomApiPatchBOMComponentResponse) GetPartNumberRevisionOk() (*string, bool)`

GetPartNumberRevisionOk returns a tuple with the PartNumberRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumberRevision

`func (o *BomApiPatchBOMComponentResponse) SetPartNumberRevision(v string)`

SetPartNumberRevision sets PartNumberRevision field to given value.

### HasPartNumberRevision

`func (o *BomApiPatchBOMComponentResponse) HasPartNumberRevision() bool`

HasPartNumberRevision returns a boolean if a field has been set.

### GetPartOperationId

`func (o *BomApiPatchBOMComponentResponse) GetPartOperationId() string`

GetPartOperationId returns the PartOperationId field if non-nil, zero value otherwise.

### GetPartOperationIdOk

`func (o *BomApiPatchBOMComponentResponse) GetPartOperationIdOk() (*string, bool)`

GetPartOperationIdOk returns a tuple with the PartOperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartOperationId

`func (o *BomApiPatchBOMComponentResponse) SetPartOperationId(v string)`

SetPartOperationId sets PartOperationId field to given value.

### HasPartOperationId

`func (o *BomApiPatchBOMComponentResponse) HasPartOperationId() bool`

HasPartOperationId returns a boolean if a field has been set.

### GetPartOperationCode

`func (o *BomApiPatchBOMComponentResponse) GetPartOperationCode() string`

GetPartOperationCode returns the PartOperationCode field if non-nil, zero value otherwise.

### GetPartOperationCodeOk

`func (o *BomApiPatchBOMComponentResponse) GetPartOperationCodeOk() (*string, bool)`

GetPartOperationCodeOk returns a tuple with the PartOperationCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartOperationCode

`func (o *BomApiPatchBOMComponentResponse) SetPartOperationCode(v string)`

SetPartOperationCode sets PartOperationCode field to given value.

### HasPartOperationCode

`func (o *BomApiPatchBOMComponentResponse) HasPartOperationCode() bool`

HasPartOperationCode returns a boolean if a field has been set.

### GetPartOperationNumber

`func (o *BomApiPatchBOMComponentResponse) GetPartOperationNumber() int32`

GetPartOperationNumber returns the PartOperationNumber field if non-nil, zero value otherwise.

### GetPartOperationNumberOk

`func (o *BomApiPatchBOMComponentResponse) GetPartOperationNumberOk() (*int32, bool)`

GetPartOperationNumberOk returns a tuple with the PartOperationNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartOperationNumber

`func (o *BomApiPatchBOMComponentResponse) SetPartOperationNumber(v int32)`

SetPartOperationNumber sets PartOperationNumber field to given value.

### HasPartOperationNumber

`func (o *BomApiPatchBOMComponentResponse) HasPartOperationNumber() bool`

HasPartOperationNumber returns a boolean if a field has been set.

### GetPartOperationType

`func (o *BomApiPatchBOMComponentResponse) GetPartOperationType() string`

GetPartOperationType returns the PartOperationType field if non-nil, zero value otherwise.

### GetPartOperationTypeOk

`func (o *BomApiPatchBOMComponentResponse) GetPartOperationTypeOk() (*string, bool)`

GetPartOperationTypeOk returns a tuple with the PartOperationType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartOperationType

`func (o *BomApiPatchBOMComponentResponse) SetPartOperationType(v string)`

SetPartOperationType sets PartOperationType field to given value.

### HasPartOperationType

`func (o *BomApiPatchBOMComponentResponse) HasPartOperationType() bool`

HasPartOperationType returns a boolean if a field has been set.

### GetComponentPartId

`func (o *BomApiPatchBOMComponentResponse) GetComponentPartId() string`

GetComponentPartId returns the ComponentPartId field if non-nil, zero value otherwise.

### GetComponentPartIdOk

`func (o *BomApiPatchBOMComponentResponse) GetComponentPartIdOk() (*string, bool)`

GetComponentPartIdOk returns a tuple with the ComponentPartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponentPartId

`func (o *BomApiPatchBOMComponentResponse) SetComponentPartId(v string)`

SetComponentPartId sets ComponentPartId field to given value.

### HasComponentPartId

`func (o *BomApiPatchBOMComponentResponse) HasComponentPartId() bool`

HasComponentPartId returns a boolean if a field has been set.

### GetComponentPartNumber

`func (o *BomApiPatchBOMComponentResponse) GetComponentPartNumber() string`

GetComponentPartNumber returns the ComponentPartNumber field if non-nil, zero value otherwise.

### GetComponentPartNumberOk

`func (o *BomApiPatchBOMComponentResponse) GetComponentPartNumberOk() (*string, bool)`

GetComponentPartNumberOk returns a tuple with the ComponentPartNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponentPartNumber

`func (o *BomApiPatchBOMComponentResponse) SetComponentPartNumber(v string)`

SetComponentPartNumber sets ComponentPartNumber field to given value.

### HasComponentPartNumber

`func (o *BomApiPatchBOMComponentResponse) HasComponentPartNumber() bool`

HasComponentPartNumber returns a boolean if a field has been set.

### GetComponentPartRevision

`func (o *BomApiPatchBOMComponentResponse) GetComponentPartRevision() string`

GetComponentPartRevision returns the ComponentPartRevision field if non-nil, zero value otherwise.

### GetComponentPartRevisionOk

`func (o *BomApiPatchBOMComponentResponse) GetComponentPartRevisionOk() (*string, bool)`

GetComponentPartRevisionOk returns a tuple with the ComponentPartRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponentPartRevision

`func (o *BomApiPatchBOMComponentResponse) SetComponentPartRevision(v string)`

SetComponentPartRevision sets ComponentPartRevision field to given value.

### HasComponentPartRevision

`func (o *BomApiPatchBOMComponentResponse) HasComponentPartRevision() bool`

HasComponentPartRevision returns a boolean if a field has been set.

### GetComponentPartNumberRevision

`func (o *BomApiPatchBOMComponentResponse) GetComponentPartNumberRevision() string`

GetComponentPartNumberRevision returns the ComponentPartNumberRevision field if non-nil, zero value otherwise.

### GetComponentPartNumberRevisionOk

`func (o *BomApiPatchBOMComponentResponse) GetComponentPartNumberRevisionOk() (*string, bool)`

GetComponentPartNumberRevisionOk returns a tuple with the ComponentPartNumberRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponentPartNumberRevision

`func (o *BomApiPatchBOMComponentResponse) SetComponentPartNumberRevision(v string)`

SetComponentPartNumberRevision sets ComponentPartNumberRevision field to given value.

### HasComponentPartNumberRevision

`func (o *BomApiPatchBOMComponentResponse) HasComponentPartNumberRevision() bool`

HasComponentPartNumberRevision returns a boolean if a field has been set.

### GetComponentSupplyItemId

`func (o *BomApiPatchBOMComponentResponse) GetComponentSupplyItemId() string`

GetComponentSupplyItemId returns the ComponentSupplyItemId field if non-nil, zero value otherwise.

### GetComponentSupplyItemIdOk

`func (o *BomApiPatchBOMComponentResponse) GetComponentSupplyItemIdOk() (*string, bool)`

GetComponentSupplyItemIdOk returns a tuple with the ComponentSupplyItemId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponentSupplyItemId

`func (o *BomApiPatchBOMComponentResponse) SetComponentSupplyItemId(v string)`

SetComponentSupplyItemId sets ComponentSupplyItemId field to given value.

### HasComponentSupplyItemId

`func (o *BomApiPatchBOMComponentResponse) HasComponentSupplyItemId() bool`

HasComponentSupplyItemId returns a boolean if a field has been set.

### GetComponentSupplyItemNumber

`func (o *BomApiPatchBOMComponentResponse) GetComponentSupplyItemNumber() string`

GetComponentSupplyItemNumber returns the ComponentSupplyItemNumber field if non-nil, zero value otherwise.

### GetComponentSupplyItemNumberOk

`func (o *BomApiPatchBOMComponentResponse) GetComponentSupplyItemNumberOk() (*string, bool)`

GetComponentSupplyItemNumberOk returns a tuple with the ComponentSupplyItemNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponentSupplyItemNumber

`func (o *BomApiPatchBOMComponentResponse) SetComponentSupplyItemNumber(v string)`

SetComponentSupplyItemNumber sets ComponentSupplyItemNumber field to given value.

### HasComponentSupplyItemNumber

`func (o *BomApiPatchBOMComponentResponse) HasComponentSupplyItemNumber() bool`

HasComponentSupplyItemNumber returns a boolean if a field has been set.

### GetComponentUnitOfMeasure

`func (o *BomApiPatchBOMComponentResponse) GetComponentUnitOfMeasure() string`

GetComponentUnitOfMeasure returns the ComponentUnitOfMeasure field if non-nil, zero value otherwise.

### GetComponentUnitOfMeasureOk

`func (o *BomApiPatchBOMComponentResponse) GetComponentUnitOfMeasureOk() (*string, bool)`

GetComponentUnitOfMeasureOk returns a tuple with the ComponentUnitOfMeasure field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponentUnitOfMeasure

`func (o *BomApiPatchBOMComponentResponse) SetComponentUnitOfMeasure(v string)`

SetComponentUnitOfMeasure sets ComponentUnitOfMeasure field to given value.

### HasComponentUnitOfMeasure

`func (o *BomApiPatchBOMComponentResponse) HasComponentUnitOfMeasure() bool`

HasComponentUnitOfMeasure returns a boolean if a field has been set.

### GetQuantity

`func (o *BomApiPatchBOMComponentResponse) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *BomApiPatchBOMComponentResponse) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *BomApiPatchBOMComponentResponse) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *BomApiPatchBOMComponentResponse) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetMinimumQuantity

`func (o *BomApiPatchBOMComponentResponse) GetMinimumQuantity() float64`

GetMinimumQuantity returns the MinimumQuantity field if non-nil, zero value otherwise.

### GetMinimumQuantityOk

`func (o *BomApiPatchBOMComponentResponse) GetMinimumQuantityOk() (*float64, bool)`

GetMinimumQuantityOk returns a tuple with the MinimumQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinimumQuantity

`func (o *BomApiPatchBOMComponentResponse) SetMinimumQuantity(v float64)`

SetMinimumQuantity sets MinimumQuantity field to given value.

### HasMinimumQuantity

`func (o *BomApiPatchBOMComponentResponse) HasMinimumQuantity() bool`

HasMinimumQuantity returns a boolean if a field has been set.

### GetMaximumQuantity

`func (o *BomApiPatchBOMComponentResponse) GetMaximumQuantity() float64`

GetMaximumQuantity returns the MaximumQuantity field if non-nil, zero value otherwise.

### GetMaximumQuantityOk

`func (o *BomApiPatchBOMComponentResponse) GetMaximumQuantityOk() (*float64, bool)`

GetMaximumQuantityOk returns a tuple with the MaximumQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaximumQuantity

`func (o *BomApiPatchBOMComponentResponse) SetMaximumQuantity(v float64)`

SetMaximumQuantity sets MaximumQuantity field to given value.

### HasMaximumQuantity

`func (o *BomApiPatchBOMComponentResponse) HasMaximumQuantity() bool`

HasMaximumQuantity returns a boolean if a field has been set.

### GetQuantityFixed

`func (o *BomApiPatchBOMComponentResponse) GetQuantityFixed() bool`

GetQuantityFixed returns the QuantityFixed field if non-nil, zero value otherwise.

### GetQuantityFixedOk

`func (o *BomApiPatchBOMComponentResponse) GetQuantityFixedOk() (*bool, bool)`

GetQuantityFixedOk returns a tuple with the QuantityFixed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantityFixed

`func (o *BomApiPatchBOMComponentResponse) SetQuantityFixed(v bool)`

SetQuantityFixed sets QuantityFixed field to given value.

### HasQuantityFixed

`func (o *BomApiPatchBOMComponentResponse) HasQuantityFixed() bool`

HasQuantityFixed returns a boolean if a field has been set.

### GetDepletionUnitOfMeasure

`func (o *BomApiPatchBOMComponentResponse) GetDepletionUnitOfMeasure() string`

GetDepletionUnitOfMeasure returns the DepletionUnitOfMeasure field if non-nil, zero value otherwise.

### GetDepletionUnitOfMeasureOk

`func (o *BomApiPatchBOMComponentResponse) GetDepletionUnitOfMeasureOk() (*string, bool)`

GetDepletionUnitOfMeasureOk returns a tuple with the DepletionUnitOfMeasure field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDepletionUnitOfMeasure

`func (o *BomApiPatchBOMComponentResponse) SetDepletionUnitOfMeasure(v string)`

SetDepletionUnitOfMeasure sets DepletionUnitOfMeasure field to given value.

### HasDepletionUnitOfMeasure

`func (o *BomApiPatchBOMComponentResponse) HasDepletionUnitOfMeasure() bool`

HasDepletionUnitOfMeasure returns a boolean if a field has been set.

### GetDepletionConversionFactor

`func (o *BomApiPatchBOMComponentResponse) GetDepletionConversionFactor() float64`

GetDepletionConversionFactor returns the DepletionConversionFactor field if non-nil, zero value otherwise.

### GetDepletionConversionFactorOk

`func (o *BomApiPatchBOMComponentResponse) GetDepletionConversionFactorOk() (*float64, bool)`

GetDepletionConversionFactorOk returns a tuple with the DepletionConversionFactor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDepletionConversionFactor

`func (o *BomApiPatchBOMComponentResponse) SetDepletionConversionFactor(v float64)`

SetDepletionConversionFactor sets DepletionConversionFactor field to given value.

### HasDepletionConversionFactor

`func (o *BomApiPatchBOMComponentResponse) HasDepletionConversionFactor() bool`

HasDepletionConversionFactor returns a boolean if a field has been set.

### GetSortOrder

`func (o *BomApiPatchBOMComponentResponse) GetSortOrder() float64`

GetSortOrder returns the SortOrder field if non-nil, zero value otherwise.

### GetSortOrderOk

`func (o *BomApiPatchBOMComponentResponse) GetSortOrderOk() (*float64, bool)`

GetSortOrderOk returns a tuple with the SortOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSortOrder

`func (o *BomApiPatchBOMComponentResponse) SetSortOrder(v float64)`

SetSortOrder sets SortOrder field to given value.

### HasSortOrder

`func (o *BomApiPatchBOMComponentResponse) HasSortOrder() bool`

HasSortOrder returns a boolean if a field has been set.

### GetActive

`func (o *BomApiPatchBOMComponentResponse) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *BomApiPatchBOMComponentResponse) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *BomApiPatchBOMComponentResponse) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *BomApiPatchBOMComponentResponse) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetPosition

`func (o *BomApiPatchBOMComponentResponse) GetPosition() string`

GetPosition returns the Position field if non-nil, zero value otherwise.

### GetPositionOk

`func (o *BomApiPatchBOMComponentResponse) GetPositionOk() (*string, bool)`

GetPositionOk returns a tuple with the Position field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosition

`func (o *BomApiPatchBOMComponentResponse) SetPosition(v string)`

SetPosition sets Position field to given value.

### HasPosition

`func (o *BomApiPatchBOMComponentResponse) HasPosition() bool`

HasPosition returns a boolean if a field has been set.

### GetSide

`func (o *BomApiPatchBOMComponentResponse) GetSide() string`

GetSide returns the Side field if non-nil, zero value otherwise.

### GetSideOk

`func (o *BomApiPatchBOMComponentResponse) GetSideOk() (*string, bool)`

GetSideOk returns a tuple with the Side field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSide

`func (o *BomApiPatchBOMComponentResponse) SetSide(v string)`

SetSide sets Side field to given value.

### HasSide

`func (o *BomApiPatchBOMComponentResponse) HasSide() bool`

HasSide returns a boolean if a field has been set.

### GetScaling

`func (o *BomApiPatchBOMComponentResponse) GetScaling() bool`

GetScaling returns the Scaling field if non-nil, zero value otherwise.

### GetScalingOk

`func (o *BomApiPatchBOMComponentResponse) GetScalingOk() (*bool, bool)`

GetScalingOk returns a tuple with the Scaling field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScaling

`func (o *BomApiPatchBOMComponentResponse) SetScaling(v bool)`

SetScaling sets Scaling field to given value.

### HasScaling

`func (o *BomApiPatchBOMComponentResponse) HasScaling() bool`

HasScaling returns a boolean if a field has been set.

### GetValidate

`func (o *BomApiPatchBOMComponentResponse) GetValidate() bool`

GetValidate returns the Validate field if non-nil, zero value otherwise.

### GetValidateOk

`func (o *BomApiPatchBOMComponentResponse) GetValidateOk() (*bool, bool)`

GetValidateOk returns a tuple with the Validate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidate

`func (o *BomApiPatchBOMComponentResponse) SetValidate(v bool)`

SetValidate sets Validate field to given value.

### HasValidate

`func (o *BomApiPatchBOMComponentResponse) HasValidate() bool`

HasValidate returns a boolean if a field has been set.

### GetAutoDeplete

`func (o *BomApiPatchBOMComponentResponse) GetAutoDeplete() bool`

GetAutoDeplete returns the AutoDeplete field if non-nil, zero value otherwise.

### GetAutoDepleteOk

`func (o *BomApiPatchBOMComponentResponse) GetAutoDepleteOk() (*bool, bool)`

GetAutoDepleteOk returns a tuple with the AutoDeplete field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutoDeplete

`func (o *BomApiPatchBOMComponentResponse) SetAutoDeplete(v bool)`

SetAutoDeplete sets AutoDeplete field to given value.

### HasAutoDeplete

`func (o *BomApiPatchBOMComponentResponse) HasAutoDeplete() bool`

HasAutoDeplete returns a boolean if a field has been set.

### GetTransferHeat

`func (o *BomApiPatchBOMComponentResponse) GetTransferHeat() bool`

GetTransferHeat returns the TransferHeat field if non-nil, zero value otherwise.

### GetTransferHeatOk

`func (o *BomApiPatchBOMComponentResponse) GetTransferHeatOk() (*bool, bool)`

GetTransferHeatOk returns a tuple with the TransferHeat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransferHeat

`func (o *BomApiPatchBOMComponentResponse) SetTransferHeat(v bool)`

SetTransferHeat sets TransferHeat field to given value.

### HasTransferHeat

`func (o *BomApiPatchBOMComponentResponse) HasTransferHeat() bool`

HasTransferHeat returns a boolean if a field has been set.

### GetNote

`func (o *BomApiPatchBOMComponentResponse) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *BomApiPatchBOMComponentResponse) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *BomApiPatchBOMComponentResponse) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *BomApiPatchBOMComponentResponse) HasNote() bool`

HasNote returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


