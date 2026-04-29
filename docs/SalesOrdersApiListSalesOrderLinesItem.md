# SalesOrdersApiListSalesOrderLinesItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | The ID of the line on the sales order. | [optional] 
**OrderId** | Pointer to **string** | The ID of the sales order. | [optional] 
**PartId** | Pointer to **string** | The ID of the part number assigned to the sales order line. | [optional] 
**CustomerPartId** | Pointer to **string** | The ID of the customer part number assigned to the sales order line. | [optional] 
**Note** | Pointer to **string** | A note on the sales order line. | [optional] 
**LineNumber** | Pointer to **string** | Typically corresponds to the line item number on the physical copy of the purchase order. | [optional] 
**ContainerType** | Pointer to **string** | The container type that should be used when packing inventory to satisfy the order line. | [optional] 
**StandardPackQuantity** | Pointer to **float64** | The standard quantity that should be packed into a container when fulfilling the order line. | [optional] 
**AccountingJobNumber** | Pointer to **string** | The accounting job number, from the Project Accounting module, applied to the sales order line. | [optional] 
**Active** | Pointer to **bool** | Identifies whether the sales order line is active. | [optional] 
**CreatedById** | Pointer to **string** | The ID of the user who created the record. | [optional] 
**CreatedDate** | Pointer to **time.Time** | The date on which the record was created. | [optional] 
**ModifiedById** | Pointer to **string** | The ID of the user who last modified the record. | [optional] 
**ModifiedDate** | Pointer to **time.Time** | The date on which the record was last modified. | [optional] 
**TransportationAdjustmentDays** | Pointer to **int32** | The transportation adjustment (in days) that should be applied when calculating the ship date of releases associated with the PO line. | [optional] 

## Methods

### NewSalesOrdersApiListSalesOrderLinesItem

`func NewSalesOrdersApiListSalesOrderLinesItem() *SalesOrdersApiListSalesOrderLinesItem`

NewSalesOrdersApiListSalesOrderLinesItem instantiates a new SalesOrdersApiListSalesOrderLinesItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSalesOrdersApiListSalesOrderLinesItemWithDefaults

`func NewSalesOrdersApiListSalesOrderLinesItemWithDefaults() *SalesOrdersApiListSalesOrderLinesItem`

NewSalesOrdersApiListSalesOrderLinesItemWithDefaults instantiates a new SalesOrdersApiListSalesOrderLinesItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SalesOrdersApiListSalesOrderLinesItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SalesOrdersApiListSalesOrderLinesItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SalesOrdersApiListSalesOrderLinesItem) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *SalesOrdersApiListSalesOrderLinesItem) HasId() bool`

HasId returns a boolean if a field has been set.

### GetOrderId

`func (o *SalesOrdersApiListSalesOrderLinesItem) GetOrderId() string`

GetOrderId returns the OrderId field if non-nil, zero value otherwise.

### GetOrderIdOk

`func (o *SalesOrdersApiListSalesOrderLinesItem) GetOrderIdOk() (*string, bool)`

GetOrderIdOk returns a tuple with the OrderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderId

`func (o *SalesOrdersApiListSalesOrderLinesItem) SetOrderId(v string)`

SetOrderId sets OrderId field to given value.

### HasOrderId

`func (o *SalesOrdersApiListSalesOrderLinesItem) HasOrderId() bool`

HasOrderId returns a boolean if a field has been set.

### GetPartId

`func (o *SalesOrdersApiListSalesOrderLinesItem) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *SalesOrdersApiListSalesOrderLinesItem) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *SalesOrdersApiListSalesOrderLinesItem) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *SalesOrdersApiListSalesOrderLinesItem) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetCustomerPartId

`func (o *SalesOrdersApiListSalesOrderLinesItem) GetCustomerPartId() string`

GetCustomerPartId returns the CustomerPartId field if non-nil, zero value otherwise.

### GetCustomerPartIdOk

`func (o *SalesOrdersApiListSalesOrderLinesItem) GetCustomerPartIdOk() (*string, bool)`

GetCustomerPartIdOk returns a tuple with the CustomerPartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerPartId

`func (o *SalesOrdersApiListSalesOrderLinesItem) SetCustomerPartId(v string)`

SetCustomerPartId sets CustomerPartId field to given value.

### HasCustomerPartId

`func (o *SalesOrdersApiListSalesOrderLinesItem) HasCustomerPartId() bool`

HasCustomerPartId returns a boolean if a field has been set.

### GetNote

`func (o *SalesOrdersApiListSalesOrderLinesItem) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *SalesOrdersApiListSalesOrderLinesItem) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *SalesOrdersApiListSalesOrderLinesItem) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *SalesOrdersApiListSalesOrderLinesItem) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetLineNumber

`func (o *SalesOrdersApiListSalesOrderLinesItem) GetLineNumber() string`

GetLineNumber returns the LineNumber field if non-nil, zero value otherwise.

### GetLineNumberOk

`func (o *SalesOrdersApiListSalesOrderLinesItem) GetLineNumberOk() (*string, bool)`

GetLineNumberOk returns a tuple with the LineNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineNumber

`func (o *SalesOrdersApiListSalesOrderLinesItem) SetLineNumber(v string)`

SetLineNumber sets LineNumber field to given value.

### HasLineNumber

`func (o *SalesOrdersApiListSalesOrderLinesItem) HasLineNumber() bool`

HasLineNumber returns a boolean if a field has been set.

### GetContainerType

`func (o *SalesOrdersApiListSalesOrderLinesItem) GetContainerType() string`

GetContainerType returns the ContainerType field if non-nil, zero value otherwise.

### GetContainerTypeOk

`func (o *SalesOrdersApiListSalesOrderLinesItem) GetContainerTypeOk() (*string, bool)`

GetContainerTypeOk returns a tuple with the ContainerType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContainerType

`func (o *SalesOrdersApiListSalesOrderLinesItem) SetContainerType(v string)`

SetContainerType sets ContainerType field to given value.

### HasContainerType

`func (o *SalesOrdersApiListSalesOrderLinesItem) HasContainerType() bool`

HasContainerType returns a boolean if a field has been set.

### GetStandardPackQuantity

`func (o *SalesOrdersApiListSalesOrderLinesItem) GetStandardPackQuantity() float64`

GetStandardPackQuantity returns the StandardPackQuantity field if non-nil, zero value otherwise.

### GetStandardPackQuantityOk

`func (o *SalesOrdersApiListSalesOrderLinesItem) GetStandardPackQuantityOk() (*float64, bool)`

GetStandardPackQuantityOk returns a tuple with the StandardPackQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStandardPackQuantity

`func (o *SalesOrdersApiListSalesOrderLinesItem) SetStandardPackQuantity(v float64)`

SetStandardPackQuantity sets StandardPackQuantity field to given value.

### HasStandardPackQuantity

`func (o *SalesOrdersApiListSalesOrderLinesItem) HasStandardPackQuantity() bool`

HasStandardPackQuantity returns a boolean if a field has been set.

### GetAccountingJobNumber

`func (o *SalesOrdersApiListSalesOrderLinesItem) GetAccountingJobNumber() string`

GetAccountingJobNumber returns the AccountingJobNumber field if non-nil, zero value otherwise.

### GetAccountingJobNumberOk

`func (o *SalesOrdersApiListSalesOrderLinesItem) GetAccountingJobNumberOk() (*string, bool)`

GetAccountingJobNumberOk returns a tuple with the AccountingJobNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountingJobNumber

`func (o *SalesOrdersApiListSalesOrderLinesItem) SetAccountingJobNumber(v string)`

SetAccountingJobNumber sets AccountingJobNumber field to given value.

### HasAccountingJobNumber

`func (o *SalesOrdersApiListSalesOrderLinesItem) HasAccountingJobNumber() bool`

HasAccountingJobNumber returns a boolean if a field has been set.

### GetActive

`func (o *SalesOrdersApiListSalesOrderLinesItem) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *SalesOrdersApiListSalesOrderLinesItem) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *SalesOrdersApiListSalesOrderLinesItem) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *SalesOrdersApiListSalesOrderLinesItem) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetCreatedById

`func (o *SalesOrdersApiListSalesOrderLinesItem) GetCreatedById() string`

GetCreatedById returns the CreatedById field if non-nil, zero value otherwise.

### GetCreatedByIdOk

`func (o *SalesOrdersApiListSalesOrderLinesItem) GetCreatedByIdOk() (*string, bool)`

GetCreatedByIdOk returns a tuple with the CreatedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedById

`func (o *SalesOrdersApiListSalesOrderLinesItem) SetCreatedById(v string)`

SetCreatedById sets CreatedById field to given value.

### HasCreatedById

`func (o *SalesOrdersApiListSalesOrderLinesItem) HasCreatedById() bool`

HasCreatedById returns a boolean if a field has been set.

### GetCreatedDate

`func (o *SalesOrdersApiListSalesOrderLinesItem) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *SalesOrdersApiListSalesOrderLinesItem) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *SalesOrdersApiListSalesOrderLinesItem) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *SalesOrdersApiListSalesOrderLinesItem) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.

### GetModifiedById

`func (o *SalesOrdersApiListSalesOrderLinesItem) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *SalesOrdersApiListSalesOrderLinesItem) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *SalesOrdersApiListSalesOrderLinesItem) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *SalesOrdersApiListSalesOrderLinesItem) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetModifiedDate

`func (o *SalesOrdersApiListSalesOrderLinesItem) GetModifiedDate() time.Time`

GetModifiedDate returns the ModifiedDate field if non-nil, zero value otherwise.

### GetModifiedDateOk

`func (o *SalesOrdersApiListSalesOrderLinesItem) GetModifiedDateOk() (*time.Time, bool)`

GetModifiedDateOk returns a tuple with the ModifiedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDate

`func (o *SalesOrdersApiListSalesOrderLinesItem) SetModifiedDate(v time.Time)`

SetModifiedDate sets ModifiedDate field to given value.

### HasModifiedDate

`func (o *SalesOrdersApiListSalesOrderLinesItem) HasModifiedDate() bool`

HasModifiedDate returns a boolean if a field has been set.

### GetTransportationAdjustmentDays

`func (o *SalesOrdersApiListSalesOrderLinesItem) GetTransportationAdjustmentDays() int32`

GetTransportationAdjustmentDays returns the TransportationAdjustmentDays field if non-nil, zero value otherwise.

### GetTransportationAdjustmentDaysOk

`func (o *SalesOrdersApiListSalesOrderLinesItem) GetTransportationAdjustmentDaysOk() (*int32, bool)`

GetTransportationAdjustmentDaysOk returns a tuple with the TransportationAdjustmentDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransportationAdjustmentDays

`func (o *SalesOrdersApiListSalesOrderLinesItem) SetTransportationAdjustmentDays(v int32)`

SetTransportationAdjustmentDays sets TransportationAdjustmentDays field to given value.

### HasTransportationAdjustmentDays

`func (o *SalesOrdersApiListSalesOrderLinesItem) HasTransportationAdjustmentDays() bool`

HasTransportationAdjustmentDays returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


