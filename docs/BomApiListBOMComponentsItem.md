# BomApiListBOMComponentsItem

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

### NewBomApiListBOMComponentsItem

`func NewBomApiListBOMComponentsItem() *BomApiListBOMComponentsItem`

NewBomApiListBOMComponentsItem instantiates a new BomApiListBOMComponentsItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBomApiListBOMComponentsItemWithDefaults

`func NewBomApiListBOMComponentsItemWithDefaults() *BomApiListBOMComponentsItem`

NewBomApiListBOMComponentsItemWithDefaults instantiates a new BomApiListBOMComponentsItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *BomApiListBOMComponentsItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *BomApiListBOMComponentsItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *BomApiListBOMComponentsItem) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *BomApiListBOMComponentsItem) HasId() bool`

HasId returns a boolean if a field has been set.

### GetPartId

`func (o *BomApiListBOMComponentsItem) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *BomApiListBOMComponentsItem) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *BomApiListBOMComponentsItem) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *BomApiListBOMComponentsItem) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetPartNumber

`func (o *BomApiListBOMComponentsItem) GetPartNumber() string`

GetPartNumber returns the PartNumber field if non-nil, zero value otherwise.

### GetPartNumberOk

`func (o *BomApiListBOMComponentsItem) GetPartNumberOk() (*string, bool)`

GetPartNumberOk returns a tuple with the PartNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumber

`func (o *BomApiListBOMComponentsItem) SetPartNumber(v string)`

SetPartNumber sets PartNumber field to given value.

### HasPartNumber

`func (o *BomApiListBOMComponentsItem) HasPartNumber() bool`

HasPartNumber returns a boolean if a field has been set.

### GetPartRevision

`func (o *BomApiListBOMComponentsItem) GetPartRevision() string`

GetPartRevision returns the PartRevision field if non-nil, zero value otherwise.

### GetPartRevisionOk

`func (o *BomApiListBOMComponentsItem) GetPartRevisionOk() (*string, bool)`

GetPartRevisionOk returns a tuple with the PartRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartRevision

`func (o *BomApiListBOMComponentsItem) SetPartRevision(v string)`

SetPartRevision sets PartRevision field to given value.

### HasPartRevision

`func (o *BomApiListBOMComponentsItem) HasPartRevision() bool`

HasPartRevision returns a boolean if a field has been set.

### GetPartNumberRevision

`func (o *BomApiListBOMComponentsItem) GetPartNumberRevision() string`

GetPartNumberRevision returns the PartNumberRevision field if non-nil, zero value otherwise.

### GetPartNumberRevisionOk

`func (o *BomApiListBOMComponentsItem) GetPartNumberRevisionOk() (*string, bool)`

GetPartNumberRevisionOk returns a tuple with the PartNumberRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumberRevision

`func (o *BomApiListBOMComponentsItem) SetPartNumberRevision(v string)`

SetPartNumberRevision sets PartNumberRevision field to given value.

### HasPartNumberRevision

`func (o *BomApiListBOMComponentsItem) HasPartNumberRevision() bool`

HasPartNumberRevision returns a boolean if a field has been set.

### GetPartOperationId

`func (o *BomApiListBOMComponentsItem) GetPartOperationId() string`

GetPartOperationId returns the PartOperationId field if non-nil, zero value otherwise.

### GetPartOperationIdOk

`func (o *BomApiListBOMComponentsItem) GetPartOperationIdOk() (*string, bool)`

GetPartOperationIdOk returns a tuple with the PartOperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartOperationId

`func (o *BomApiListBOMComponentsItem) SetPartOperationId(v string)`

SetPartOperationId sets PartOperationId field to given value.

### HasPartOperationId

`func (o *BomApiListBOMComponentsItem) HasPartOperationId() bool`

HasPartOperationId returns a boolean if a field has been set.

### GetPartOperationCode

`func (o *BomApiListBOMComponentsItem) GetPartOperationCode() string`

GetPartOperationCode returns the PartOperationCode field if non-nil, zero value otherwise.

### GetPartOperationCodeOk

`func (o *BomApiListBOMComponentsItem) GetPartOperationCodeOk() (*string, bool)`

GetPartOperationCodeOk returns a tuple with the PartOperationCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartOperationCode

`func (o *BomApiListBOMComponentsItem) SetPartOperationCode(v string)`

SetPartOperationCode sets PartOperationCode field to given value.

### HasPartOperationCode

`func (o *BomApiListBOMComponentsItem) HasPartOperationCode() bool`

HasPartOperationCode returns a boolean if a field has been set.

### GetPartOperationNumber

`func (o *BomApiListBOMComponentsItem) GetPartOperationNumber() int32`

GetPartOperationNumber returns the PartOperationNumber field if non-nil, zero value otherwise.

### GetPartOperationNumberOk

`func (o *BomApiListBOMComponentsItem) GetPartOperationNumberOk() (*int32, bool)`

GetPartOperationNumberOk returns a tuple with the PartOperationNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartOperationNumber

`func (o *BomApiListBOMComponentsItem) SetPartOperationNumber(v int32)`

SetPartOperationNumber sets PartOperationNumber field to given value.

### HasPartOperationNumber

`func (o *BomApiListBOMComponentsItem) HasPartOperationNumber() bool`

HasPartOperationNumber returns a boolean if a field has been set.

### GetPartOperationType

`func (o *BomApiListBOMComponentsItem) GetPartOperationType() string`

GetPartOperationType returns the PartOperationType field if non-nil, zero value otherwise.

### GetPartOperationTypeOk

`func (o *BomApiListBOMComponentsItem) GetPartOperationTypeOk() (*string, bool)`

GetPartOperationTypeOk returns a tuple with the PartOperationType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartOperationType

`func (o *BomApiListBOMComponentsItem) SetPartOperationType(v string)`

SetPartOperationType sets PartOperationType field to given value.

### HasPartOperationType

`func (o *BomApiListBOMComponentsItem) HasPartOperationType() bool`

HasPartOperationType returns a boolean if a field has been set.

### GetComponentPartId

`func (o *BomApiListBOMComponentsItem) GetComponentPartId() string`

GetComponentPartId returns the ComponentPartId field if non-nil, zero value otherwise.

### GetComponentPartIdOk

`func (o *BomApiListBOMComponentsItem) GetComponentPartIdOk() (*string, bool)`

GetComponentPartIdOk returns a tuple with the ComponentPartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponentPartId

`func (o *BomApiListBOMComponentsItem) SetComponentPartId(v string)`

SetComponentPartId sets ComponentPartId field to given value.

### HasComponentPartId

`func (o *BomApiListBOMComponentsItem) HasComponentPartId() bool`

HasComponentPartId returns a boolean if a field has been set.

### GetComponentPartNumber

`func (o *BomApiListBOMComponentsItem) GetComponentPartNumber() string`

GetComponentPartNumber returns the ComponentPartNumber field if non-nil, zero value otherwise.

### GetComponentPartNumberOk

`func (o *BomApiListBOMComponentsItem) GetComponentPartNumberOk() (*string, bool)`

GetComponentPartNumberOk returns a tuple with the ComponentPartNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponentPartNumber

`func (o *BomApiListBOMComponentsItem) SetComponentPartNumber(v string)`

SetComponentPartNumber sets ComponentPartNumber field to given value.

### HasComponentPartNumber

`func (o *BomApiListBOMComponentsItem) HasComponentPartNumber() bool`

HasComponentPartNumber returns a boolean if a field has been set.

### GetComponentPartRevision

`func (o *BomApiListBOMComponentsItem) GetComponentPartRevision() string`

GetComponentPartRevision returns the ComponentPartRevision field if non-nil, zero value otherwise.

### GetComponentPartRevisionOk

`func (o *BomApiListBOMComponentsItem) GetComponentPartRevisionOk() (*string, bool)`

GetComponentPartRevisionOk returns a tuple with the ComponentPartRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponentPartRevision

`func (o *BomApiListBOMComponentsItem) SetComponentPartRevision(v string)`

SetComponentPartRevision sets ComponentPartRevision field to given value.

### HasComponentPartRevision

`func (o *BomApiListBOMComponentsItem) HasComponentPartRevision() bool`

HasComponentPartRevision returns a boolean if a field has been set.

### GetComponentPartNumberRevision

`func (o *BomApiListBOMComponentsItem) GetComponentPartNumberRevision() string`

GetComponentPartNumberRevision returns the ComponentPartNumberRevision field if non-nil, zero value otherwise.

### GetComponentPartNumberRevisionOk

`func (o *BomApiListBOMComponentsItem) GetComponentPartNumberRevisionOk() (*string, bool)`

GetComponentPartNumberRevisionOk returns a tuple with the ComponentPartNumberRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponentPartNumberRevision

`func (o *BomApiListBOMComponentsItem) SetComponentPartNumberRevision(v string)`

SetComponentPartNumberRevision sets ComponentPartNumberRevision field to given value.

### HasComponentPartNumberRevision

`func (o *BomApiListBOMComponentsItem) HasComponentPartNumberRevision() bool`

HasComponentPartNumberRevision returns a boolean if a field has been set.

### GetComponentSupplyItemId

`func (o *BomApiListBOMComponentsItem) GetComponentSupplyItemId() string`

GetComponentSupplyItemId returns the ComponentSupplyItemId field if non-nil, zero value otherwise.

### GetComponentSupplyItemIdOk

`func (o *BomApiListBOMComponentsItem) GetComponentSupplyItemIdOk() (*string, bool)`

GetComponentSupplyItemIdOk returns a tuple with the ComponentSupplyItemId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponentSupplyItemId

`func (o *BomApiListBOMComponentsItem) SetComponentSupplyItemId(v string)`

SetComponentSupplyItemId sets ComponentSupplyItemId field to given value.

### HasComponentSupplyItemId

`func (o *BomApiListBOMComponentsItem) HasComponentSupplyItemId() bool`

HasComponentSupplyItemId returns a boolean if a field has been set.

### GetComponentSupplyItemNumber

`func (o *BomApiListBOMComponentsItem) GetComponentSupplyItemNumber() string`

GetComponentSupplyItemNumber returns the ComponentSupplyItemNumber field if non-nil, zero value otherwise.

### GetComponentSupplyItemNumberOk

`func (o *BomApiListBOMComponentsItem) GetComponentSupplyItemNumberOk() (*string, bool)`

GetComponentSupplyItemNumberOk returns a tuple with the ComponentSupplyItemNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponentSupplyItemNumber

`func (o *BomApiListBOMComponentsItem) SetComponentSupplyItemNumber(v string)`

SetComponentSupplyItemNumber sets ComponentSupplyItemNumber field to given value.

### HasComponentSupplyItemNumber

`func (o *BomApiListBOMComponentsItem) HasComponentSupplyItemNumber() bool`

HasComponentSupplyItemNumber returns a boolean if a field has been set.

### GetComponentUnitOfMeasure

`func (o *BomApiListBOMComponentsItem) GetComponentUnitOfMeasure() string`

GetComponentUnitOfMeasure returns the ComponentUnitOfMeasure field if non-nil, zero value otherwise.

### GetComponentUnitOfMeasureOk

`func (o *BomApiListBOMComponentsItem) GetComponentUnitOfMeasureOk() (*string, bool)`

GetComponentUnitOfMeasureOk returns a tuple with the ComponentUnitOfMeasure field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponentUnitOfMeasure

`func (o *BomApiListBOMComponentsItem) SetComponentUnitOfMeasure(v string)`

SetComponentUnitOfMeasure sets ComponentUnitOfMeasure field to given value.

### HasComponentUnitOfMeasure

`func (o *BomApiListBOMComponentsItem) HasComponentUnitOfMeasure() bool`

HasComponentUnitOfMeasure returns a boolean if a field has been set.

### GetQuantity

`func (o *BomApiListBOMComponentsItem) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *BomApiListBOMComponentsItem) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *BomApiListBOMComponentsItem) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *BomApiListBOMComponentsItem) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetMinimumQuantity

`func (o *BomApiListBOMComponentsItem) GetMinimumQuantity() float64`

GetMinimumQuantity returns the MinimumQuantity field if non-nil, zero value otherwise.

### GetMinimumQuantityOk

`func (o *BomApiListBOMComponentsItem) GetMinimumQuantityOk() (*float64, bool)`

GetMinimumQuantityOk returns a tuple with the MinimumQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinimumQuantity

`func (o *BomApiListBOMComponentsItem) SetMinimumQuantity(v float64)`

SetMinimumQuantity sets MinimumQuantity field to given value.

### HasMinimumQuantity

`func (o *BomApiListBOMComponentsItem) HasMinimumQuantity() bool`

HasMinimumQuantity returns a boolean if a field has been set.

### GetMaximumQuantity

`func (o *BomApiListBOMComponentsItem) GetMaximumQuantity() float64`

GetMaximumQuantity returns the MaximumQuantity field if non-nil, zero value otherwise.

### GetMaximumQuantityOk

`func (o *BomApiListBOMComponentsItem) GetMaximumQuantityOk() (*float64, bool)`

GetMaximumQuantityOk returns a tuple with the MaximumQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaximumQuantity

`func (o *BomApiListBOMComponentsItem) SetMaximumQuantity(v float64)`

SetMaximumQuantity sets MaximumQuantity field to given value.

### HasMaximumQuantity

`func (o *BomApiListBOMComponentsItem) HasMaximumQuantity() bool`

HasMaximumQuantity returns a boolean if a field has been set.

### GetQuantityFixed

`func (o *BomApiListBOMComponentsItem) GetQuantityFixed() bool`

GetQuantityFixed returns the QuantityFixed field if non-nil, zero value otherwise.

### GetQuantityFixedOk

`func (o *BomApiListBOMComponentsItem) GetQuantityFixedOk() (*bool, bool)`

GetQuantityFixedOk returns a tuple with the QuantityFixed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantityFixed

`func (o *BomApiListBOMComponentsItem) SetQuantityFixed(v bool)`

SetQuantityFixed sets QuantityFixed field to given value.

### HasQuantityFixed

`func (o *BomApiListBOMComponentsItem) HasQuantityFixed() bool`

HasQuantityFixed returns a boolean if a field has been set.

### GetDepletionUnitOfMeasure

`func (o *BomApiListBOMComponentsItem) GetDepletionUnitOfMeasure() string`

GetDepletionUnitOfMeasure returns the DepletionUnitOfMeasure field if non-nil, zero value otherwise.

### GetDepletionUnitOfMeasureOk

`func (o *BomApiListBOMComponentsItem) GetDepletionUnitOfMeasureOk() (*string, bool)`

GetDepletionUnitOfMeasureOk returns a tuple with the DepletionUnitOfMeasure field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDepletionUnitOfMeasure

`func (o *BomApiListBOMComponentsItem) SetDepletionUnitOfMeasure(v string)`

SetDepletionUnitOfMeasure sets DepletionUnitOfMeasure field to given value.

### HasDepletionUnitOfMeasure

`func (o *BomApiListBOMComponentsItem) HasDepletionUnitOfMeasure() bool`

HasDepletionUnitOfMeasure returns a boolean if a field has been set.

### GetDepletionConversionFactor

`func (o *BomApiListBOMComponentsItem) GetDepletionConversionFactor() float64`

GetDepletionConversionFactor returns the DepletionConversionFactor field if non-nil, zero value otherwise.

### GetDepletionConversionFactorOk

`func (o *BomApiListBOMComponentsItem) GetDepletionConversionFactorOk() (*float64, bool)`

GetDepletionConversionFactorOk returns a tuple with the DepletionConversionFactor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDepletionConversionFactor

`func (o *BomApiListBOMComponentsItem) SetDepletionConversionFactor(v float64)`

SetDepletionConversionFactor sets DepletionConversionFactor field to given value.

### HasDepletionConversionFactor

`func (o *BomApiListBOMComponentsItem) HasDepletionConversionFactor() bool`

HasDepletionConversionFactor returns a boolean if a field has been set.

### GetSortOrder

`func (o *BomApiListBOMComponentsItem) GetSortOrder() float64`

GetSortOrder returns the SortOrder field if non-nil, zero value otherwise.

### GetSortOrderOk

`func (o *BomApiListBOMComponentsItem) GetSortOrderOk() (*float64, bool)`

GetSortOrderOk returns a tuple with the SortOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSortOrder

`func (o *BomApiListBOMComponentsItem) SetSortOrder(v float64)`

SetSortOrder sets SortOrder field to given value.

### HasSortOrder

`func (o *BomApiListBOMComponentsItem) HasSortOrder() bool`

HasSortOrder returns a boolean if a field has been set.

### GetActive

`func (o *BomApiListBOMComponentsItem) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *BomApiListBOMComponentsItem) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *BomApiListBOMComponentsItem) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *BomApiListBOMComponentsItem) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetPosition

`func (o *BomApiListBOMComponentsItem) GetPosition() string`

GetPosition returns the Position field if non-nil, zero value otherwise.

### GetPositionOk

`func (o *BomApiListBOMComponentsItem) GetPositionOk() (*string, bool)`

GetPositionOk returns a tuple with the Position field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosition

`func (o *BomApiListBOMComponentsItem) SetPosition(v string)`

SetPosition sets Position field to given value.

### HasPosition

`func (o *BomApiListBOMComponentsItem) HasPosition() bool`

HasPosition returns a boolean if a field has been set.

### GetSide

`func (o *BomApiListBOMComponentsItem) GetSide() string`

GetSide returns the Side field if non-nil, zero value otherwise.

### GetSideOk

`func (o *BomApiListBOMComponentsItem) GetSideOk() (*string, bool)`

GetSideOk returns a tuple with the Side field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSide

`func (o *BomApiListBOMComponentsItem) SetSide(v string)`

SetSide sets Side field to given value.

### HasSide

`func (o *BomApiListBOMComponentsItem) HasSide() bool`

HasSide returns a boolean if a field has been set.

### GetScaling

`func (o *BomApiListBOMComponentsItem) GetScaling() bool`

GetScaling returns the Scaling field if non-nil, zero value otherwise.

### GetScalingOk

`func (o *BomApiListBOMComponentsItem) GetScalingOk() (*bool, bool)`

GetScalingOk returns a tuple with the Scaling field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScaling

`func (o *BomApiListBOMComponentsItem) SetScaling(v bool)`

SetScaling sets Scaling field to given value.

### HasScaling

`func (o *BomApiListBOMComponentsItem) HasScaling() bool`

HasScaling returns a boolean if a field has been set.

### GetValidate

`func (o *BomApiListBOMComponentsItem) GetValidate() bool`

GetValidate returns the Validate field if non-nil, zero value otherwise.

### GetValidateOk

`func (o *BomApiListBOMComponentsItem) GetValidateOk() (*bool, bool)`

GetValidateOk returns a tuple with the Validate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidate

`func (o *BomApiListBOMComponentsItem) SetValidate(v bool)`

SetValidate sets Validate field to given value.

### HasValidate

`func (o *BomApiListBOMComponentsItem) HasValidate() bool`

HasValidate returns a boolean if a field has been set.

### GetAutoDeplete

`func (o *BomApiListBOMComponentsItem) GetAutoDeplete() bool`

GetAutoDeplete returns the AutoDeplete field if non-nil, zero value otherwise.

### GetAutoDepleteOk

`func (o *BomApiListBOMComponentsItem) GetAutoDepleteOk() (*bool, bool)`

GetAutoDepleteOk returns a tuple with the AutoDeplete field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutoDeplete

`func (o *BomApiListBOMComponentsItem) SetAutoDeplete(v bool)`

SetAutoDeplete sets AutoDeplete field to given value.

### HasAutoDeplete

`func (o *BomApiListBOMComponentsItem) HasAutoDeplete() bool`

HasAutoDeplete returns a boolean if a field has been set.

### GetTransferHeat

`func (o *BomApiListBOMComponentsItem) GetTransferHeat() bool`

GetTransferHeat returns the TransferHeat field if non-nil, zero value otherwise.

### GetTransferHeatOk

`func (o *BomApiListBOMComponentsItem) GetTransferHeatOk() (*bool, bool)`

GetTransferHeatOk returns a tuple with the TransferHeat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransferHeat

`func (o *BomApiListBOMComponentsItem) SetTransferHeat(v bool)`

SetTransferHeat sets TransferHeat field to given value.

### HasTransferHeat

`func (o *BomApiListBOMComponentsItem) HasTransferHeat() bool`

HasTransferHeat returns a boolean if a field has been set.

### GetNote

`func (o *BomApiListBOMComponentsItem) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *BomApiListBOMComponentsItem) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *BomApiListBOMComponentsItem) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *BomApiListBOMComponentsItem) HasNote() bool`

HasNote returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


