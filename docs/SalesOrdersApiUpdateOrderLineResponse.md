# SalesOrdersApiUpdateOrderLineResponse

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

### NewSalesOrdersApiUpdateOrderLineResponse

`func NewSalesOrdersApiUpdateOrderLineResponse() *SalesOrdersApiUpdateOrderLineResponse`

NewSalesOrdersApiUpdateOrderLineResponse instantiates a new SalesOrdersApiUpdateOrderLineResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSalesOrdersApiUpdateOrderLineResponseWithDefaults

`func NewSalesOrdersApiUpdateOrderLineResponseWithDefaults() *SalesOrdersApiUpdateOrderLineResponse`

NewSalesOrdersApiUpdateOrderLineResponseWithDefaults instantiates a new SalesOrdersApiUpdateOrderLineResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SalesOrdersApiUpdateOrderLineResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SalesOrdersApiUpdateOrderLineResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SalesOrdersApiUpdateOrderLineResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *SalesOrdersApiUpdateOrderLineResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetOrderId

`func (o *SalesOrdersApiUpdateOrderLineResponse) GetOrderId() string`

GetOrderId returns the OrderId field if non-nil, zero value otherwise.

### GetOrderIdOk

`func (o *SalesOrdersApiUpdateOrderLineResponse) GetOrderIdOk() (*string, bool)`

GetOrderIdOk returns a tuple with the OrderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderId

`func (o *SalesOrdersApiUpdateOrderLineResponse) SetOrderId(v string)`

SetOrderId sets OrderId field to given value.

### HasOrderId

`func (o *SalesOrdersApiUpdateOrderLineResponse) HasOrderId() bool`

HasOrderId returns a boolean if a field has been set.

### GetPartId

`func (o *SalesOrdersApiUpdateOrderLineResponse) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *SalesOrdersApiUpdateOrderLineResponse) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *SalesOrdersApiUpdateOrderLineResponse) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *SalesOrdersApiUpdateOrderLineResponse) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetCustomerPartId

`func (o *SalesOrdersApiUpdateOrderLineResponse) GetCustomerPartId() string`

GetCustomerPartId returns the CustomerPartId field if non-nil, zero value otherwise.

### GetCustomerPartIdOk

`func (o *SalesOrdersApiUpdateOrderLineResponse) GetCustomerPartIdOk() (*string, bool)`

GetCustomerPartIdOk returns a tuple with the CustomerPartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerPartId

`func (o *SalesOrdersApiUpdateOrderLineResponse) SetCustomerPartId(v string)`

SetCustomerPartId sets CustomerPartId field to given value.

### HasCustomerPartId

`func (o *SalesOrdersApiUpdateOrderLineResponse) HasCustomerPartId() bool`

HasCustomerPartId returns a boolean if a field has been set.

### GetNote

`func (o *SalesOrdersApiUpdateOrderLineResponse) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *SalesOrdersApiUpdateOrderLineResponse) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *SalesOrdersApiUpdateOrderLineResponse) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *SalesOrdersApiUpdateOrderLineResponse) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetLineNumber

`func (o *SalesOrdersApiUpdateOrderLineResponse) GetLineNumber() string`

GetLineNumber returns the LineNumber field if non-nil, zero value otherwise.

### GetLineNumberOk

`func (o *SalesOrdersApiUpdateOrderLineResponse) GetLineNumberOk() (*string, bool)`

GetLineNumberOk returns a tuple with the LineNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineNumber

`func (o *SalesOrdersApiUpdateOrderLineResponse) SetLineNumber(v string)`

SetLineNumber sets LineNumber field to given value.

### HasLineNumber

`func (o *SalesOrdersApiUpdateOrderLineResponse) HasLineNumber() bool`

HasLineNumber returns a boolean if a field has been set.

### GetContainerType

`func (o *SalesOrdersApiUpdateOrderLineResponse) GetContainerType() string`

GetContainerType returns the ContainerType field if non-nil, zero value otherwise.

### GetContainerTypeOk

`func (o *SalesOrdersApiUpdateOrderLineResponse) GetContainerTypeOk() (*string, bool)`

GetContainerTypeOk returns a tuple with the ContainerType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContainerType

`func (o *SalesOrdersApiUpdateOrderLineResponse) SetContainerType(v string)`

SetContainerType sets ContainerType field to given value.

### HasContainerType

`func (o *SalesOrdersApiUpdateOrderLineResponse) HasContainerType() bool`

HasContainerType returns a boolean if a field has been set.

### GetStandardPackQuantity

`func (o *SalesOrdersApiUpdateOrderLineResponse) GetStandardPackQuantity() float64`

GetStandardPackQuantity returns the StandardPackQuantity field if non-nil, zero value otherwise.

### GetStandardPackQuantityOk

`func (o *SalesOrdersApiUpdateOrderLineResponse) GetStandardPackQuantityOk() (*float64, bool)`

GetStandardPackQuantityOk returns a tuple with the StandardPackQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStandardPackQuantity

`func (o *SalesOrdersApiUpdateOrderLineResponse) SetStandardPackQuantity(v float64)`

SetStandardPackQuantity sets StandardPackQuantity field to given value.

### HasStandardPackQuantity

`func (o *SalesOrdersApiUpdateOrderLineResponse) HasStandardPackQuantity() bool`

HasStandardPackQuantity returns a boolean if a field has been set.

### GetAccountingJobNumber

`func (o *SalesOrdersApiUpdateOrderLineResponse) GetAccountingJobNumber() string`

GetAccountingJobNumber returns the AccountingJobNumber field if non-nil, zero value otherwise.

### GetAccountingJobNumberOk

`func (o *SalesOrdersApiUpdateOrderLineResponse) GetAccountingJobNumberOk() (*string, bool)`

GetAccountingJobNumberOk returns a tuple with the AccountingJobNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountingJobNumber

`func (o *SalesOrdersApiUpdateOrderLineResponse) SetAccountingJobNumber(v string)`

SetAccountingJobNumber sets AccountingJobNumber field to given value.

### HasAccountingJobNumber

`func (o *SalesOrdersApiUpdateOrderLineResponse) HasAccountingJobNumber() bool`

HasAccountingJobNumber returns a boolean if a field has been set.

### GetActive

`func (o *SalesOrdersApiUpdateOrderLineResponse) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *SalesOrdersApiUpdateOrderLineResponse) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *SalesOrdersApiUpdateOrderLineResponse) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *SalesOrdersApiUpdateOrderLineResponse) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetCreatedById

`func (o *SalesOrdersApiUpdateOrderLineResponse) GetCreatedById() string`

GetCreatedById returns the CreatedById field if non-nil, zero value otherwise.

### GetCreatedByIdOk

`func (o *SalesOrdersApiUpdateOrderLineResponse) GetCreatedByIdOk() (*string, bool)`

GetCreatedByIdOk returns a tuple with the CreatedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedById

`func (o *SalesOrdersApiUpdateOrderLineResponse) SetCreatedById(v string)`

SetCreatedById sets CreatedById field to given value.

### HasCreatedById

`func (o *SalesOrdersApiUpdateOrderLineResponse) HasCreatedById() bool`

HasCreatedById returns a boolean if a field has been set.

### GetCreatedDate

`func (o *SalesOrdersApiUpdateOrderLineResponse) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *SalesOrdersApiUpdateOrderLineResponse) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *SalesOrdersApiUpdateOrderLineResponse) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *SalesOrdersApiUpdateOrderLineResponse) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.

### GetModifiedById

`func (o *SalesOrdersApiUpdateOrderLineResponse) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *SalesOrdersApiUpdateOrderLineResponse) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *SalesOrdersApiUpdateOrderLineResponse) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *SalesOrdersApiUpdateOrderLineResponse) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetModifiedDate

`func (o *SalesOrdersApiUpdateOrderLineResponse) GetModifiedDate() time.Time`

GetModifiedDate returns the ModifiedDate field if non-nil, zero value otherwise.

### GetModifiedDateOk

`func (o *SalesOrdersApiUpdateOrderLineResponse) GetModifiedDateOk() (*time.Time, bool)`

GetModifiedDateOk returns a tuple with the ModifiedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDate

`func (o *SalesOrdersApiUpdateOrderLineResponse) SetModifiedDate(v time.Time)`

SetModifiedDate sets ModifiedDate field to given value.

### HasModifiedDate

`func (o *SalesOrdersApiUpdateOrderLineResponse) HasModifiedDate() bool`

HasModifiedDate returns a boolean if a field has been set.

### GetTransportationAdjustmentDays

`func (o *SalesOrdersApiUpdateOrderLineResponse) GetTransportationAdjustmentDays() int32`

GetTransportationAdjustmentDays returns the TransportationAdjustmentDays field if non-nil, zero value otherwise.

### GetTransportationAdjustmentDaysOk

`func (o *SalesOrdersApiUpdateOrderLineResponse) GetTransportationAdjustmentDaysOk() (*int32, bool)`

GetTransportationAdjustmentDaysOk returns a tuple with the TransportationAdjustmentDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransportationAdjustmentDays

`func (o *SalesOrdersApiUpdateOrderLineResponse) SetTransportationAdjustmentDays(v int32)`

SetTransportationAdjustmentDays sets TransportationAdjustmentDays field to given value.

### HasTransportationAdjustmentDays

`func (o *SalesOrdersApiUpdateOrderLineResponse) HasTransportationAdjustmentDays() bool`

HasTransportationAdjustmentDays returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


