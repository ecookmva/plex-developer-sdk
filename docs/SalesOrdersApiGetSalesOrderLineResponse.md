# SalesOrdersApiGetSalesOrderLineResponse

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

### NewSalesOrdersApiGetSalesOrderLineResponse

`func NewSalesOrdersApiGetSalesOrderLineResponse() *SalesOrdersApiGetSalesOrderLineResponse`

NewSalesOrdersApiGetSalesOrderLineResponse instantiates a new SalesOrdersApiGetSalesOrderLineResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSalesOrdersApiGetSalesOrderLineResponseWithDefaults

`func NewSalesOrdersApiGetSalesOrderLineResponseWithDefaults() *SalesOrdersApiGetSalesOrderLineResponse`

NewSalesOrdersApiGetSalesOrderLineResponseWithDefaults instantiates a new SalesOrdersApiGetSalesOrderLineResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SalesOrdersApiGetSalesOrderLineResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SalesOrdersApiGetSalesOrderLineResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SalesOrdersApiGetSalesOrderLineResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *SalesOrdersApiGetSalesOrderLineResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetOrderId

`func (o *SalesOrdersApiGetSalesOrderLineResponse) GetOrderId() string`

GetOrderId returns the OrderId field if non-nil, zero value otherwise.

### GetOrderIdOk

`func (o *SalesOrdersApiGetSalesOrderLineResponse) GetOrderIdOk() (*string, bool)`

GetOrderIdOk returns a tuple with the OrderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderId

`func (o *SalesOrdersApiGetSalesOrderLineResponse) SetOrderId(v string)`

SetOrderId sets OrderId field to given value.

### HasOrderId

`func (o *SalesOrdersApiGetSalesOrderLineResponse) HasOrderId() bool`

HasOrderId returns a boolean if a field has been set.

### GetPartId

`func (o *SalesOrdersApiGetSalesOrderLineResponse) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *SalesOrdersApiGetSalesOrderLineResponse) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *SalesOrdersApiGetSalesOrderLineResponse) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *SalesOrdersApiGetSalesOrderLineResponse) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetCustomerPartId

`func (o *SalesOrdersApiGetSalesOrderLineResponse) GetCustomerPartId() string`

GetCustomerPartId returns the CustomerPartId field if non-nil, zero value otherwise.

### GetCustomerPartIdOk

`func (o *SalesOrdersApiGetSalesOrderLineResponse) GetCustomerPartIdOk() (*string, bool)`

GetCustomerPartIdOk returns a tuple with the CustomerPartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerPartId

`func (o *SalesOrdersApiGetSalesOrderLineResponse) SetCustomerPartId(v string)`

SetCustomerPartId sets CustomerPartId field to given value.

### HasCustomerPartId

`func (o *SalesOrdersApiGetSalesOrderLineResponse) HasCustomerPartId() bool`

HasCustomerPartId returns a boolean if a field has been set.

### GetNote

`func (o *SalesOrdersApiGetSalesOrderLineResponse) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *SalesOrdersApiGetSalesOrderLineResponse) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *SalesOrdersApiGetSalesOrderLineResponse) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *SalesOrdersApiGetSalesOrderLineResponse) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetLineNumber

`func (o *SalesOrdersApiGetSalesOrderLineResponse) GetLineNumber() string`

GetLineNumber returns the LineNumber field if non-nil, zero value otherwise.

### GetLineNumberOk

`func (o *SalesOrdersApiGetSalesOrderLineResponse) GetLineNumberOk() (*string, bool)`

GetLineNumberOk returns a tuple with the LineNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineNumber

`func (o *SalesOrdersApiGetSalesOrderLineResponse) SetLineNumber(v string)`

SetLineNumber sets LineNumber field to given value.

### HasLineNumber

`func (o *SalesOrdersApiGetSalesOrderLineResponse) HasLineNumber() bool`

HasLineNumber returns a boolean if a field has been set.

### GetContainerType

`func (o *SalesOrdersApiGetSalesOrderLineResponse) GetContainerType() string`

GetContainerType returns the ContainerType field if non-nil, zero value otherwise.

### GetContainerTypeOk

`func (o *SalesOrdersApiGetSalesOrderLineResponse) GetContainerTypeOk() (*string, bool)`

GetContainerTypeOk returns a tuple with the ContainerType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContainerType

`func (o *SalesOrdersApiGetSalesOrderLineResponse) SetContainerType(v string)`

SetContainerType sets ContainerType field to given value.

### HasContainerType

`func (o *SalesOrdersApiGetSalesOrderLineResponse) HasContainerType() bool`

HasContainerType returns a boolean if a field has been set.

### GetStandardPackQuantity

`func (o *SalesOrdersApiGetSalesOrderLineResponse) GetStandardPackQuantity() float64`

GetStandardPackQuantity returns the StandardPackQuantity field if non-nil, zero value otherwise.

### GetStandardPackQuantityOk

`func (o *SalesOrdersApiGetSalesOrderLineResponse) GetStandardPackQuantityOk() (*float64, bool)`

GetStandardPackQuantityOk returns a tuple with the StandardPackQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStandardPackQuantity

`func (o *SalesOrdersApiGetSalesOrderLineResponse) SetStandardPackQuantity(v float64)`

SetStandardPackQuantity sets StandardPackQuantity field to given value.

### HasStandardPackQuantity

`func (o *SalesOrdersApiGetSalesOrderLineResponse) HasStandardPackQuantity() bool`

HasStandardPackQuantity returns a boolean if a field has been set.

### GetAccountingJobNumber

`func (o *SalesOrdersApiGetSalesOrderLineResponse) GetAccountingJobNumber() string`

GetAccountingJobNumber returns the AccountingJobNumber field if non-nil, zero value otherwise.

### GetAccountingJobNumberOk

`func (o *SalesOrdersApiGetSalesOrderLineResponse) GetAccountingJobNumberOk() (*string, bool)`

GetAccountingJobNumberOk returns a tuple with the AccountingJobNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountingJobNumber

`func (o *SalesOrdersApiGetSalesOrderLineResponse) SetAccountingJobNumber(v string)`

SetAccountingJobNumber sets AccountingJobNumber field to given value.

### HasAccountingJobNumber

`func (o *SalesOrdersApiGetSalesOrderLineResponse) HasAccountingJobNumber() bool`

HasAccountingJobNumber returns a boolean if a field has been set.

### GetActive

`func (o *SalesOrdersApiGetSalesOrderLineResponse) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *SalesOrdersApiGetSalesOrderLineResponse) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *SalesOrdersApiGetSalesOrderLineResponse) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *SalesOrdersApiGetSalesOrderLineResponse) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetCreatedById

`func (o *SalesOrdersApiGetSalesOrderLineResponse) GetCreatedById() string`

GetCreatedById returns the CreatedById field if non-nil, zero value otherwise.

### GetCreatedByIdOk

`func (o *SalesOrdersApiGetSalesOrderLineResponse) GetCreatedByIdOk() (*string, bool)`

GetCreatedByIdOk returns a tuple with the CreatedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedById

`func (o *SalesOrdersApiGetSalesOrderLineResponse) SetCreatedById(v string)`

SetCreatedById sets CreatedById field to given value.

### HasCreatedById

`func (o *SalesOrdersApiGetSalesOrderLineResponse) HasCreatedById() bool`

HasCreatedById returns a boolean if a field has been set.

### GetCreatedDate

`func (o *SalesOrdersApiGetSalesOrderLineResponse) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *SalesOrdersApiGetSalesOrderLineResponse) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *SalesOrdersApiGetSalesOrderLineResponse) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *SalesOrdersApiGetSalesOrderLineResponse) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.

### GetModifiedById

`func (o *SalesOrdersApiGetSalesOrderLineResponse) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *SalesOrdersApiGetSalesOrderLineResponse) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *SalesOrdersApiGetSalesOrderLineResponse) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *SalesOrdersApiGetSalesOrderLineResponse) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetModifiedDate

`func (o *SalesOrdersApiGetSalesOrderLineResponse) GetModifiedDate() time.Time`

GetModifiedDate returns the ModifiedDate field if non-nil, zero value otherwise.

### GetModifiedDateOk

`func (o *SalesOrdersApiGetSalesOrderLineResponse) GetModifiedDateOk() (*time.Time, bool)`

GetModifiedDateOk returns a tuple with the ModifiedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDate

`func (o *SalesOrdersApiGetSalesOrderLineResponse) SetModifiedDate(v time.Time)`

SetModifiedDate sets ModifiedDate field to given value.

### HasModifiedDate

`func (o *SalesOrdersApiGetSalesOrderLineResponse) HasModifiedDate() bool`

HasModifiedDate returns a boolean if a field has been set.

### GetTransportationAdjustmentDays

`func (o *SalesOrdersApiGetSalesOrderLineResponse) GetTransportationAdjustmentDays() int32`

GetTransportationAdjustmentDays returns the TransportationAdjustmentDays field if non-nil, zero value otherwise.

### GetTransportationAdjustmentDaysOk

`func (o *SalesOrdersApiGetSalesOrderLineResponse) GetTransportationAdjustmentDaysOk() (*int32, bool)`

GetTransportationAdjustmentDaysOk returns a tuple with the TransportationAdjustmentDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransportationAdjustmentDays

`func (o *SalesOrdersApiGetSalesOrderLineResponse) SetTransportationAdjustmentDays(v int32)`

SetTransportationAdjustmentDays sets TransportationAdjustmentDays field to given value.

### HasTransportationAdjustmentDays

`func (o *SalesOrdersApiGetSalesOrderLineResponse) HasTransportationAdjustmentDays() bool`

HasTransportationAdjustmentDays returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


