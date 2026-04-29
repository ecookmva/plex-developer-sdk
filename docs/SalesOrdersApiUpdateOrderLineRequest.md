# SalesOrdersApiUpdateOrderLineRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
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

### NewSalesOrdersApiUpdateOrderLineRequest

`func NewSalesOrdersApiUpdateOrderLineRequest() *SalesOrdersApiUpdateOrderLineRequest`

NewSalesOrdersApiUpdateOrderLineRequest instantiates a new SalesOrdersApiUpdateOrderLineRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSalesOrdersApiUpdateOrderLineRequestWithDefaults

`func NewSalesOrdersApiUpdateOrderLineRequestWithDefaults() *SalesOrdersApiUpdateOrderLineRequest`

NewSalesOrdersApiUpdateOrderLineRequestWithDefaults instantiates a new SalesOrdersApiUpdateOrderLineRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCustomerPartId

`func (o *SalesOrdersApiUpdateOrderLineRequest) GetCustomerPartId() string`

GetCustomerPartId returns the CustomerPartId field if non-nil, zero value otherwise.

### GetCustomerPartIdOk

`func (o *SalesOrdersApiUpdateOrderLineRequest) GetCustomerPartIdOk() (*string, bool)`

GetCustomerPartIdOk returns a tuple with the CustomerPartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerPartId

`func (o *SalesOrdersApiUpdateOrderLineRequest) SetCustomerPartId(v string)`

SetCustomerPartId sets CustomerPartId field to given value.

### HasCustomerPartId

`func (o *SalesOrdersApiUpdateOrderLineRequest) HasCustomerPartId() bool`

HasCustomerPartId returns a boolean if a field has been set.

### GetNote

`func (o *SalesOrdersApiUpdateOrderLineRequest) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *SalesOrdersApiUpdateOrderLineRequest) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *SalesOrdersApiUpdateOrderLineRequest) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *SalesOrdersApiUpdateOrderLineRequest) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetLineNumber

`func (o *SalesOrdersApiUpdateOrderLineRequest) GetLineNumber() string`

GetLineNumber returns the LineNumber field if non-nil, zero value otherwise.

### GetLineNumberOk

`func (o *SalesOrdersApiUpdateOrderLineRequest) GetLineNumberOk() (*string, bool)`

GetLineNumberOk returns a tuple with the LineNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineNumber

`func (o *SalesOrdersApiUpdateOrderLineRequest) SetLineNumber(v string)`

SetLineNumber sets LineNumber field to given value.

### HasLineNumber

`func (o *SalesOrdersApiUpdateOrderLineRequest) HasLineNumber() bool`

HasLineNumber returns a boolean if a field has been set.

### GetContainerType

`func (o *SalesOrdersApiUpdateOrderLineRequest) GetContainerType() string`

GetContainerType returns the ContainerType field if non-nil, zero value otherwise.

### GetContainerTypeOk

`func (o *SalesOrdersApiUpdateOrderLineRequest) GetContainerTypeOk() (*string, bool)`

GetContainerTypeOk returns a tuple with the ContainerType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContainerType

`func (o *SalesOrdersApiUpdateOrderLineRequest) SetContainerType(v string)`

SetContainerType sets ContainerType field to given value.

### HasContainerType

`func (o *SalesOrdersApiUpdateOrderLineRequest) HasContainerType() bool`

HasContainerType returns a boolean if a field has been set.

### GetStandardPackQuantity

`func (o *SalesOrdersApiUpdateOrderLineRequest) GetStandardPackQuantity() float64`

GetStandardPackQuantity returns the StandardPackQuantity field if non-nil, zero value otherwise.

### GetStandardPackQuantityOk

`func (o *SalesOrdersApiUpdateOrderLineRequest) GetStandardPackQuantityOk() (*float64, bool)`

GetStandardPackQuantityOk returns a tuple with the StandardPackQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStandardPackQuantity

`func (o *SalesOrdersApiUpdateOrderLineRequest) SetStandardPackQuantity(v float64)`

SetStandardPackQuantity sets StandardPackQuantity field to given value.

### HasStandardPackQuantity

`func (o *SalesOrdersApiUpdateOrderLineRequest) HasStandardPackQuantity() bool`

HasStandardPackQuantity returns a boolean if a field has been set.

### GetAccountingJobNumber

`func (o *SalesOrdersApiUpdateOrderLineRequest) GetAccountingJobNumber() string`

GetAccountingJobNumber returns the AccountingJobNumber field if non-nil, zero value otherwise.

### GetAccountingJobNumberOk

`func (o *SalesOrdersApiUpdateOrderLineRequest) GetAccountingJobNumberOk() (*string, bool)`

GetAccountingJobNumberOk returns a tuple with the AccountingJobNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountingJobNumber

`func (o *SalesOrdersApiUpdateOrderLineRequest) SetAccountingJobNumber(v string)`

SetAccountingJobNumber sets AccountingJobNumber field to given value.

### HasAccountingJobNumber

`func (o *SalesOrdersApiUpdateOrderLineRequest) HasAccountingJobNumber() bool`

HasAccountingJobNumber returns a boolean if a field has been set.

### GetActive

`func (o *SalesOrdersApiUpdateOrderLineRequest) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *SalesOrdersApiUpdateOrderLineRequest) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *SalesOrdersApiUpdateOrderLineRequest) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *SalesOrdersApiUpdateOrderLineRequest) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetTransportationAdjustmentDays

`func (o *SalesOrdersApiUpdateOrderLineRequest) GetTransportationAdjustmentDays() int32`

GetTransportationAdjustmentDays returns the TransportationAdjustmentDays field if non-nil, zero value otherwise.

### GetTransportationAdjustmentDaysOk

`func (o *SalesOrdersApiUpdateOrderLineRequest) GetTransportationAdjustmentDaysOk() (*int32, bool)`

GetTransportationAdjustmentDaysOk returns a tuple with the TransportationAdjustmentDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransportationAdjustmentDays

`func (o *SalesOrdersApiUpdateOrderLineRequest) SetTransportationAdjustmentDays(v int32)`

SetTransportationAdjustmentDays sets TransportationAdjustmentDays field to given value.

### HasTransportationAdjustmentDays

`func (o *SalesOrdersApiUpdateOrderLineRequest) HasTransportationAdjustmentDays() bool`

HasTransportationAdjustmentDays returns a boolean if a field has been set.

### GetDefaultOrderUnitId

`func (o *SalesOrdersApiUpdateOrderLineRequest) GetDefaultOrderUnitId() string`

GetDefaultOrderUnitId returns the DefaultOrderUnitId field if non-nil, zero value otherwise.

### GetDefaultOrderUnitIdOk

`func (o *SalesOrdersApiUpdateOrderLineRequest) GetDefaultOrderUnitIdOk() (*string, bool)`

GetDefaultOrderUnitIdOk returns a tuple with the DefaultOrderUnitId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultOrderUnitId

`func (o *SalesOrdersApiUpdateOrderLineRequest) SetDefaultOrderUnitId(v string)`

SetDefaultOrderUnitId sets DefaultOrderUnitId field to given value.

### HasDefaultOrderUnitId

`func (o *SalesOrdersApiUpdateOrderLineRequest) HasDefaultOrderUnitId() bool`

HasDefaultOrderUnitId returns a boolean if a field has been set.

### GetMinimumShipQuantity

`func (o *SalesOrdersApiUpdateOrderLineRequest) GetMinimumShipQuantity() float64`

GetMinimumShipQuantity returns the MinimumShipQuantity field if non-nil, zero value otherwise.

### GetMinimumShipQuantityOk

`func (o *SalesOrdersApiUpdateOrderLineRequest) GetMinimumShipQuantityOk() (*float64, bool)`

GetMinimumShipQuantityOk returns a tuple with the MinimumShipQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinimumShipQuantity

`func (o *SalesOrdersApiUpdateOrderLineRequest) SetMinimumShipQuantity(v float64)`

SetMinimumShipQuantity sets MinimumShipQuantity field to given value.

### HasMinimumShipQuantity

`func (o *SalesOrdersApiUpdateOrderLineRequest) HasMinimumShipQuantity() bool`

HasMinimumShipQuantity returns a boolean if a field has been set.

### GetPackagingNote

`func (o *SalesOrdersApiUpdateOrderLineRequest) GetPackagingNote() string`

GetPackagingNote returns the PackagingNote field if non-nil, zero value otherwise.

### GetPackagingNoteOk

`func (o *SalesOrdersApiUpdateOrderLineRequest) GetPackagingNoteOk() (*string, bool)`

GetPackagingNoteOk returns a tuple with the PackagingNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackagingNote

`func (o *SalesOrdersApiUpdateOrderLineRequest) SetPackagingNote(v string)`

SetPackagingNote sets PackagingNote field to given value.

### HasPackagingNote

`func (o *SalesOrdersApiUpdateOrderLineRequest) HasPackagingNote() bool`

HasPackagingNote returns a boolean if a field has been set.

### GetShippingInstructions

`func (o *SalesOrdersApiUpdateOrderLineRequest) GetShippingInstructions() string`

GetShippingInstructions returns the ShippingInstructions field if non-nil, zero value otherwise.

### GetShippingInstructionsOk

`func (o *SalesOrdersApiUpdateOrderLineRequest) GetShippingInstructionsOk() (*string, bool)`

GetShippingInstructionsOk returns a tuple with the ShippingInstructions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingInstructions

`func (o *SalesOrdersApiUpdateOrderLineRequest) SetShippingInstructions(v string)`

SetShippingInstructions sets ShippingInstructions field to given value.

### HasShippingInstructions

`func (o *SalesOrdersApiUpdateOrderLineRequest) HasShippingInstructions() bool`

HasShippingInstructions returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


