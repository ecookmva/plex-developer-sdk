# JobSchedulingApiAddUpdateJobBomRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**JobOpId** | Pointer to **string** | The ID of the Job Operation. | [optional] 
**ComponentPartId** | Pointer to **string** | The ID of the Part used as a component. | [optional] 
**PurchasingItemId** | Pointer to **string** | The ID of the Supply Item used as a component. | [optional] 
**Quantity** | Pointer to **float64** | Required quantity of the component to produce the end product. | [optional] 
**MinimumQuantity** | Pointer to **float64** | Minimum quantity required. | [optional] 
**MaximumQuantity** | Pointer to **float64** | Maximum quantity allowed. | [optional] 
**QuantityFixed** | Pointer to **bool** | If true, the quantity is fixed regardless of production volume. | [optional] 
**DepletionUnitOfMeasure** | Pointer to **string** | Consumption unit of the component for readability. | [optional] 
**DepletionConversionFact** | Pointer to **float64** | Conversion factor if depletion unit of measure is set. | [optional] 
**SortOrder** | Pointer to **float64** | Display order of BOM components. | [optional] 
**Position** | Pointer to **string** | Physical position of the component at the workcenter. | [optional] 
**Side** | Pointer to **string** | Used for multi-out jobs to indicate which output this component feeds. | [optional] 
**Scaling** | Pointer to **bool** | If true, the quantity scales with production quantity. | [optional] 
**Validate** | Pointer to **bool** | If true, material presence is required before production can run. | [optional] 
**AutoDeplete** | Pointer to **bool** | If true, the component is automatically depleted during production. | [optional] 
**TransferHeat** | Pointer to **bool** | If true, heat number is transferred from component to output container. | [optional] 
**Note** | Pointer to **string** | Free text note about the component. | [optional] 

## Methods

### NewJobSchedulingApiAddUpdateJobBomRequest

`func NewJobSchedulingApiAddUpdateJobBomRequest() *JobSchedulingApiAddUpdateJobBomRequest`

NewJobSchedulingApiAddUpdateJobBomRequest instantiates a new JobSchedulingApiAddUpdateJobBomRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewJobSchedulingApiAddUpdateJobBomRequestWithDefaults

`func NewJobSchedulingApiAddUpdateJobBomRequestWithDefaults() *JobSchedulingApiAddUpdateJobBomRequest`

NewJobSchedulingApiAddUpdateJobBomRequestWithDefaults instantiates a new JobSchedulingApiAddUpdateJobBomRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetJobOpId

`func (o *JobSchedulingApiAddUpdateJobBomRequest) GetJobOpId() string`

GetJobOpId returns the JobOpId field if non-nil, zero value otherwise.

### GetJobOpIdOk

`func (o *JobSchedulingApiAddUpdateJobBomRequest) GetJobOpIdOk() (*string, bool)`

GetJobOpIdOk returns a tuple with the JobOpId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobOpId

`func (o *JobSchedulingApiAddUpdateJobBomRequest) SetJobOpId(v string)`

SetJobOpId sets JobOpId field to given value.

### HasJobOpId

`func (o *JobSchedulingApiAddUpdateJobBomRequest) HasJobOpId() bool`

HasJobOpId returns a boolean if a field has been set.

### GetComponentPartId

`func (o *JobSchedulingApiAddUpdateJobBomRequest) GetComponentPartId() string`

GetComponentPartId returns the ComponentPartId field if non-nil, zero value otherwise.

### GetComponentPartIdOk

`func (o *JobSchedulingApiAddUpdateJobBomRequest) GetComponentPartIdOk() (*string, bool)`

GetComponentPartIdOk returns a tuple with the ComponentPartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponentPartId

`func (o *JobSchedulingApiAddUpdateJobBomRequest) SetComponentPartId(v string)`

SetComponentPartId sets ComponentPartId field to given value.

### HasComponentPartId

`func (o *JobSchedulingApiAddUpdateJobBomRequest) HasComponentPartId() bool`

HasComponentPartId returns a boolean if a field has been set.

### GetPurchasingItemId

`func (o *JobSchedulingApiAddUpdateJobBomRequest) GetPurchasingItemId() string`

GetPurchasingItemId returns the PurchasingItemId field if non-nil, zero value otherwise.

### GetPurchasingItemIdOk

`func (o *JobSchedulingApiAddUpdateJobBomRequest) GetPurchasingItemIdOk() (*string, bool)`

GetPurchasingItemIdOk returns a tuple with the PurchasingItemId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPurchasingItemId

`func (o *JobSchedulingApiAddUpdateJobBomRequest) SetPurchasingItemId(v string)`

SetPurchasingItemId sets PurchasingItemId field to given value.

### HasPurchasingItemId

`func (o *JobSchedulingApiAddUpdateJobBomRequest) HasPurchasingItemId() bool`

HasPurchasingItemId returns a boolean if a field has been set.

### GetQuantity

`func (o *JobSchedulingApiAddUpdateJobBomRequest) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *JobSchedulingApiAddUpdateJobBomRequest) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *JobSchedulingApiAddUpdateJobBomRequest) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *JobSchedulingApiAddUpdateJobBomRequest) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetMinimumQuantity

`func (o *JobSchedulingApiAddUpdateJobBomRequest) GetMinimumQuantity() float64`

GetMinimumQuantity returns the MinimumQuantity field if non-nil, zero value otherwise.

### GetMinimumQuantityOk

`func (o *JobSchedulingApiAddUpdateJobBomRequest) GetMinimumQuantityOk() (*float64, bool)`

GetMinimumQuantityOk returns a tuple with the MinimumQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinimumQuantity

`func (o *JobSchedulingApiAddUpdateJobBomRequest) SetMinimumQuantity(v float64)`

SetMinimumQuantity sets MinimumQuantity field to given value.

### HasMinimumQuantity

`func (o *JobSchedulingApiAddUpdateJobBomRequest) HasMinimumQuantity() bool`

HasMinimumQuantity returns a boolean if a field has been set.

### GetMaximumQuantity

`func (o *JobSchedulingApiAddUpdateJobBomRequest) GetMaximumQuantity() float64`

GetMaximumQuantity returns the MaximumQuantity field if non-nil, zero value otherwise.

### GetMaximumQuantityOk

`func (o *JobSchedulingApiAddUpdateJobBomRequest) GetMaximumQuantityOk() (*float64, bool)`

GetMaximumQuantityOk returns a tuple with the MaximumQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaximumQuantity

`func (o *JobSchedulingApiAddUpdateJobBomRequest) SetMaximumQuantity(v float64)`

SetMaximumQuantity sets MaximumQuantity field to given value.

### HasMaximumQuantity

`func (o *JobSchedulingApiAddUpdateJobBomRequest) HasMaximumQuantity() bool`

HasMaximumQuantity returns a boolean if a field has been set.

### GetQuantityFixed

`func (o *JobSchedulingApiAddUpdateJobBomRequest) GetQuantityFixed() bool`

GetQuantityFixed returns the QuantityFixed field if non-nil, zero value otherwise.

### GetQuantityFixedOk

`func (o *JobSchedulingApiAddUpdateJobBomRequest) GetQuantityFixedOk() (*bool, bool)`

GetQuantityFixedOk returns a tuple with the QuantityFixed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantityFixed

`func (o *JobSchedulingApiAddUpdateJobBomRequest) SetQuantityFixed(v bool)`

SetQuantityFixed sets QuantityFixed field to given value.

### HasQuantityFixed

`func (o *JobSchedulingApiAddUpdateJobBomRequest) HasQuantityFixed() bool`

HasQuantityFixed returns a boolean if a field has been set.

### GetDepletionUnitOfMeasure

`func (o *JobSchedulingApiAddUpdateJobBomRequest) GetDepletionUnitOfMeasure() string`

GetDepletionUnitOfMeasure returns the DepletionUnitOfMeasure field if non-nil, zero value otherwise.

### GetDepletionUnitOfMeasureOk

`func (o *JobSchedulingApiAddUpdateJobBomRequest) GetDepletionUnitOfMeasureOk() (*string, bool)`

GetDepletionUnitOfMeasureOk returns a tuple with the DepletionUnitOfMeasure field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDepletionUnitOfMeasure

`func (o *JobSchedulingApiAddUpdateJobBomRequest) SetDepletionUnitOfMeasure(v string)`

SetDepletionUnitOfMeasure sets DepletionUnitOfMeasure field to given value.

### HasDepletionUnitOfMeasure

`func (o *JobSchedulingApiAddUpdateJobBomRequest) HasDepletionUnitOfMeasure() bool`

HasDepletionUnitOfMeasure returns a boolean if a field has been set.

### GetDepletionConversionFact

`func (o *JobSchedulingApiAddUpdateJobBomRequest) GetDepletionConversionFact() float64`

GetDepletionConversionFact returns the DepletionConversionFact field if non-nil, zero value otherwise.

### GetDepletionConversionFactOk

`func (o *JobSchedulingApiAddUpdateJobBomRequest) GetDepletionConversionFactOk() (*float64, bool)`

GetDepletionConversionFactOk returns a tuple with the DepletionConversionFact field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDepletionConversionFact

`func (o *JobSchedulingApiAddUpdateJobBomRequest) SetDepletionConversionFact(v float64)`

SetDepletionConversionFact sets DepletionConversionFact field to given value.

### HasDepletionConversionFact

`func (o *JobSchedulingApiAddUpdateJobBomRequest) HasDepletionConversionFact() bool`

HasDepletionConversionFact returns a boolean if a field has been set.

### GetSortOrder

`func (o *JobSchedulingApiAddUpdateJobBomRequest) GetSortOrder() float64`

GetSortOrder returns the SortOrder field if non-nil, zero value otherwise.

### GetSortOrderOk

`func (o *JobSchedulingApiAddUpdateJobBomRequest) GetSortOrderOk() (*float64, bool)`

GetSortOrderOk returns a tuple with the SortOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSortOrder

`func (o *JobSchedulingApiAddUpdateJobBomRequest) SetSortOrder(v float64)`

SetSortOrder sets SortOrder field to given value.

### HasSortOrder

`func (o *JobSchedulingApiAddUpdateJobBomRequest) HasSortOrder() bool`

HasSortOrder returns a boolean if a field has been set.

### GetPosition

`func (o *JobSchedulingApiAddUpdateJobBomRequest) GetPosition() string`

GetPosition returns the Position field if non-nil, zero value otherwise.

### GetPositionOk

`func (o *JobSchedulingApiAddUpdateJobBomRequest) GetPositionOk() (*string, bool)`

GetPositionOk returns a tuple with the Position field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosition

`func (o *JobSchedulingApiAddUpdateJobBomRequest) SetPosition(v string)`

SetPosition sets Position field to given value.

### HasPosition

`func (o *JobSchedulingApiAddUpdateJobBomRequest) HasPosition() bool`

HasPosition returns a boolean if a field has been set.

### GetSide

`func (o *JobSchedulingApiAddUpdateJobBomRequest) GetSide() string`

GetSide returns the Side field if non-nil, zero value otherwise.

### GetSideOk

`func (o *JobSchedulingApiAddUpdateJobBomRequest) GetSideOk() (*string, bool)`

GetSideOk returns a tuple with the Side field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSide

`func (o *JobSchedulingApiAddUpdateJobBomRequest) SetSide(v string)`

SetSide sets Side field to given value.

### HasSide

`func (o *JobSchedulingApiAddUpdateJobBomRequest) HasSide() bool`

HasSide returns a boolean if a field has been set.

### GetScaling

`func (o *JobSchedulingApiAddUpdateJobBomRequest) GetScaling() bool`

GetScaling returns the Scaling field if non-nil, zero value otherwise.

### GetScalingOk

`func (o *JobSchedulingApiAddUpdateJobBomRequest) GetScalingOk() (*bool, bool)`

GetScalingOk returns a tuple with the Scaling field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScaling

`func (o *JobSchedulingApiAddUpdateJobBomRequest) SetScaling(v bool)`

SetScaling sets Scaling field to given value.

### HasScaling

`func (o *JobSchedulingApiAddUpdateJobBomRequest) HasScaling() bool`

HasScaling returns a boolean if a field has been set.

### GetValidate

`func (o *JobSchedulingApiAddUpdateJobBomRequest) GetValidate() bool`

GetValidate returns the Validate field if non-nil, zero value otherwise.

### GetValidateOk

`func (o *JobSchedulingApiAddUpdateJobBomRequest) GetValidateOk() (*bool, bool)`

GetValidateOk returns a tuple with the Validate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidate

`func (o *JobSchedulingApiAddUpdateJobBomRequest) SetValidate(v bool)`

SetValidate sets Validate field to given value.

### HasValidate

`func (o *JobSchedulingApiAddUpdateJobBomRequest) HasValidate() bool`

HasValidate returns a boolean if a field has been set.

### GetAutoDeplete

`func (o *JobSchedulingApiAddUpdateJobBomRequest) GetAutoDeplete() bool`

GetAutoDeplete returns the AutoDeplete field if non-nil, zero value otherwise.

### GetAutoDepleteOk

`func (o *JobSchedulingApiAddUpdateJobBomRequest) GetAutoDepleteOk() (*bool, bool)`

GetAutoDepleteOk returns a tuple with the AutoDeplete field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutoDeplete

`func (o *JobSchedulingApiAddUpdateJobBomRequest) SetAutoDeplete(v bool)`

SetAutoDeplete sets AutoDeplete field to given value.

### HasAutoDeplete

`func (o *JobSchedulingApiAddUpdateJobBomRequest) HasAutoDeplete() bool`

HasAutoDeplete returns a boolean if a field has been set.

### GetTransferHeat

`func (o *JobSchedulingApiAddUpdateJobBomRequest) GetTransferHeat() bool`

GetTransferHeat returns the TransferHeat field if non-nil, zero value otherwise.

### GetTransferHeatOk

`func (o *JobSchedulingApiAddUpdateJobBomRequest) GetTransferHeatOk() (*bool, bool)`

GetTransferHeatOk returns a tuple with the TransferHeat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransferHeat

`func (o *JobSchedulingApiAddUpdateJobBomRequest) SetTransferHeat(v bool)`

SetTransferHeat sets TransferHeat field to given value.

### HasTransferHeat

`func (o *JobSchedulingApiAddUpdateJobBomRequest) HasTransferHeat() bool`

HasTransferHeat returns a boolean if a field has been set.

### GetNote

`func (o *JobSchedulingApiAddUpdateJobBomRequest) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *JobSchedulingApiAddUpdateJobBomRequest) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *JobSchedulingApiAddUpdateJobBomRequest) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *JobSchedulingApiAddUpdateJobBomRequest) HasNote() bool`

HasNote returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


