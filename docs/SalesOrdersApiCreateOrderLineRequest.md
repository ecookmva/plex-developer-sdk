# SalesOrdersApiCreateOrderLineRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | The ID of the line on the sales order. | [optional] 
**PartId** | Pointer to **string** | The ID of the part number assigned to the sales order line. | [optional] 
**CustomerPartId** | Pointer to **string** | The ID of the customer part number assigned to the sales order line. | [optional] 
**Note** | Pointer to **string** | A note on the sales order line. | [optional] 
**LineNumber** | Pointer to **string** | Typically corresponds to the line item number on the physical copy of the purchase order. | [optional] 
**ContainerType** | Pointer to **string** | The container type that should be used when packing inventory to satisfy the order line. | [optional] 
**StandardPackQuantity** | Pointer to **float64** | The standard quantity that should be packed into a container when fulfilling the order line. | [optional] 
**AccountingJobNumber** | Pointer to **string** | The accounting job number, from the Project Accounting module, applied to the sales order line. | [optional] 
**Active** | Pointer to **bool** | Identifies whether the sales order line is active. | [optional] 
**TransportationAdjustmentDays** | Pointer to **int32** | The transportation adjustment (in days) that should be applied when calculating the ship date of releases associated with the PO line. | [optional] 
**DefaultOrderUnitId** | Pointer to **string** | The resource identifier for the unit used as the order unit on the line. | [optional] 
**MinimumShipQuantity** | Pointer to **float64** | The minimum ship quantity that is required for the line. | [optional] 
**PackagingNote** | Pointer to **string** | A packaging note associated with the line. | [optional] 
**ShippingInstructions** | Pointer to **string** | A note with shipping instructions for the associated order line. | [optional] 

## Methods

### NewSalesOrdersApiCreateOrderLineRequest

`func NewSalesOrdersApiCreateOrderLineRequest() *SalesOrdersApiCreateOrderLineRequest`

NewSalesOrdersApiCreateOrderLineRequest instantiates a new SalesOrdersApiCreateOrderLineRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSalesOrdersApiCreateOrderLineRequestWithDefaults

`func NewSalesOrdersApiCreateOrderLineRequestWithDefaults() *SalesOrdersApiCreateOrderLineRequest`

NewSalesOrdersApiCreateOrderLineRequestWithDefaults instantiates a new SalesOrdersApiCreateOrderLineRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SalesOrdersApiCreateOrderLineRequest) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SalesOrdersApiCreateOrderLineRequest) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SalesOrdersApiCreateOrderLineRequest) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *SalesOrdersApiCreateOrderLineRequest) HasId() bool`

HasId returns a boolean if a field has been set.

### GetPartId

`func (o *SalesOrdersApiCreateOrderLineRequest) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *SalesOrdersApiCreateOrderLineRequest) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *SalesOrdersApiCreateOrderLineRequest) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *SalesOrdersApiCreateOrderLineRequest) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetCustomerPartId

`func (o *SalesOrdersApiCreateOrderLineRequest) GetCustomerPartId() string`

GetCustomerPartId returns the CustomerPartId field if non-nil, zero value otherwise.

### GetCustomerPartIdOk

`func (o *SalesOrdersApiCreateOrderLineRequest) GetCustomerPartIdOk() (*string, bool)`

GetCustomerPartIdOk returns a tuple with the CustomerPartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerPartId

`func (o *SalesOrdersApiCreateOrderLineRequest) SetCustomerPartId(v string)`

SetCustomerPartId sets CustomerPartId field to given value.

### HasCustomerPartId

`func (o *SalesOrdersApiCreateOrderLineRequest) HasCustomerPartId() bool`

HasCustomerPartId returns a boolean if a field has been set.

### GetNote

`func (o *SalesOrdersApiCreateOrderLineRequest) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *SalesOrdersApiCreateOrderLineRequest) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *SalesOrdersApiCreateOrderLineRequest) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *SalesOrdersApiCreateOrderLineRequest) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetLineNumber

`func (o *SalesOrdersApiCreateOrderLineRequest) GetLineNumber() string`

GetLineNumber returns the LineNumber field if non-nil, zero value otherwise.

### GetLineNumberOk

`func (o *SalesOrdersApiCreateOrderLineRequest) GetLineNumberOk() (*string, bool)`

GetLineNumberOk returns a tuple with the LineNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineNumber

`func (o *SalesOrdersApiCreateOrderLineRequest) SetLineNumber(v string)`

SetLineNumber sets LineNumber field to given value.

### HasLineNumber

`func (o *SalesOrdersApiCreateOrderLineRequest) HasLineNumber() bool`

HasLineNumber returns a boolean if a field has been set.

### GetContainerType

`func (o *SalesOrdersApiCreateOrderLineRequest) GetContainerType() string`

GetContainerType returns the ContainerType field if non-nil, zero value otherwise.

### GetContainerTypeOk

`func (o *SalesOrdersApiCreateOrderLineRequest) GetContainerTypeOk() (*string, bool)`

GetContainerTypeOk returns a tuple with the ContainerType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContainerType

`func (o *SalesOrdersApiCreateOrderLineRequest) SetContainerType(v string)`

SetContainerType sets ContainerType field to given value.

### HasContainerType

`func (o *SalesOrdersApiCreateOrderLineRequest) HasContainerType() bool`

HasContainerType returns a boolean if a field has been set.

### GetStandardPackQuantity

`func (o *SalesOrdersApiCreateOrderLineRequest) GetStandardPackQuantity() float64`

GetStandardPackQuantity returns the StandardPackQuantity field if non-nil, zero value otherwise.

### GetStandardPackQuantityOk

`func (o *SalesOrdersApiCreateOrderLineRequest) GetStandardPackQuantityOk() (*float64, bool)`

GetStandardPackQuantityOk returns a tuple with the StandardPackQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStandardPackQuantity

`func (o *SalesOrdersApiCreateOrderLineRequest) SetStandardPackQuantity(v float64)`

SetStandardPackQuantity sets StandardPackQuantity field to given value.

### HasStandardPackQuantity

`func (o *SalesOrdersApiCreateOrderLineRequest) HasStandardPackQuantity() bool`

HasStandardPackQuantity returns a boolean if a field has been set.

### GetAccountingJobNumber

`func (o *SalesOrdersApiCreateOrderLineRequest) GetAccountingJobNumber() string`

GetAccountingJobNumber returns the AccountingJobNumber field if non-nil, zero value otherwise.

### GetAccountingJobNumberOk

`func (o *SalesOrdersApiCreateOrderLineRequest) GetAccountingJobNumberOk() (*string, bool)`

GetAccountingJobNumberOk returns a tuple with the AccountingJobNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountingJobNumber

`func (o *SalesOrdersApiCreateOrderLineRequest) SetAccountingJobNumber(v string)`

SetAccountingJobNumber sets AccountingJobNumber field to given value.

### HasAccountingJobNumber

`func (o *SalesOrdersApiCreateOrderLineRequest) HasAccountingJobNumber() bool`

HasAccountingJobNumber returns a boolean if a field has been set.

### GetActive

`func (o *SalesOrdersApiCreateOrderLineRequest) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *SalesOrdersApiCreateOrderLineRequest) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *SalesOrdersApiCreateOrderLineRequest) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *SalesOrdersApiCreateOrderLineRequest) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetTransportationAdjustmentDays

`func (o *SalesOrdersApiCreateOrderLineRequest) GetTransportationAdjustmentDays() int32`

GetTransportationAdjustmentDays returns the TransportationAdjustmentDays field if non-nil, zero value otherwise.

### GetTransportationAdjustmentDaysOk

`func (o *SalesOrdersApiCreateOrderLineRequest) GetTransportationAdjustmentDaysOk() (*int32, bool)`

GetTransportationAdjustmentDaysOk returns a tuple with the TransportationAdjustmentDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransportationAdjustmentDays

`func (o *SalesOrdersApiCreateOrderLineRequest) SetTransportationAdjustmentDays(v int32)`

SetTransportationAdjustmentDays sets TransportationAdjustmentDays field to given value.

### HasTransportationAdjustmentDays

`func (o *SalesOrdersApiCreateOrderLineRequest) HasTransportationAdjustmentDays() bool`

HasTransportationAdjustmentDays returns a boolean if a field has been set.

### GetDefaultOrderUnitId

`func (o *SalesOrdersApiCreateOrderLineRequest) GetDefaultOrderUnitId() string`

GetDefaultOrderUnitId returns the DefaultOrderUnitId field if non-nil, zero value otherwise.

### GetDefaultOrderUnitIdOk

`func (o *SalesOrdersApiCreateOrderLineRequest) GetDefaultOrderUnitIdOk() (*string, bool)`

GetDefaultOrderUnitIdOk returns a tuple with the DefaultOrderUnitId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultOrderUnitId

`func (o *SalesOrdersApiCreateOrderLineRequest) SetDefaultOrderUnitId(v string)`

SetDefaultOrderUnitId sets DefaultOrderUnitId field to given value.

### HasDefaultOrderUnitId

`func (o *SalesOrdersApiCreateOrderLineRequest) HasDefaultOrderUnitId() bool`

HasDefaultOrderUnitId returns a boolean if a field has been set.

### GetMinimumShipQuantity

`func (o *SalesOrdersApiCreateOrderLineRequest) GetMinimumShipQuantity() float64`

GetMinimumShipQuantity returns the MinimumShipQuantity field if non-nil, zero value otherwise.

### GetMinimumShipQuantityOk

`func (o *SalesOrdersApiCreateOrderLineRequest) GetMinimumShipQuantityOk() (*float64, bool)`

GetMinimumShipQuantityOk returns a tuple with the MinimumShipQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinimumShipQuantity

`func (o *SalesOrdersApiCreateOrderLineRequest) SetMinimumShipQuantity(v float64)`

SetMinimumShipQuantity sets MinimumShipQuantity field to given value.

### HasMinimumShipQuantity

`func (o *SalesOrdersApiCreateOrderLineRequest) HasMinimumShipQuantity() bool`

HasMinimumShipQuantity returns a boolean if a field has been set.

### GetPackagingNote

`func (o *SalesOrdersApiCreateOrderLineRequest) GetPackagingNote() string`

GetPackagingNote returns the PackagingNote field if non-nil, zero value otherwise.

### GetPackagingNoteOk

`func (o *SalesOrdersApiCreateOrderLineRequest) GetPackagingNoteOk() (*string, bool)`

GetPackagingNoteOk returns a tuple with the PackagingNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackagingNote

`func (o *SalesOrdersApiCreateOrderLineRequest) SetPackagingNote(v string)`

SetPackagingNote sets PackagingNote field to given value.

### HasPackagingNote

`func (o *SalesOrdersApiCreateOrderLineRequest) HasPackagingNote() bool`

HasPackagingNote returns a boolean if a field has been set.

### GetShippingInstructions

`func (o *SalesOrdersApiCreateOrderLineRequest) GetShippingInstructions() string`

GetShippingInstructions returns the ShippingInstructions field if non-nil, zero value otherwise.

### GetShippingInstructionsOk

`func (o *SalesOrdersApiCreateOrderLineRequest) GetShippingInstructionsOk() (*string, bool)`

GetShippingInstructionsOk returns a tuple with the ShippingInstructions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingInstructions

`func (o *SalesOrdersApiCreateOrderLineRequest) SetShippingInstructions(v string)`

SetShippingInstructions sets ShippingInstructions field to given value.

### HasShippingInstructions

`func (o *SalesOrdersApiCreateOrderLineRequest) HasShippingInstructions() bool`

HasShippingInstructions returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


