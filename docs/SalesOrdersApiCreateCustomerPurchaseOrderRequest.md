# SalesOrdersApiCreateCustomerPurchaseOrderRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CustomerId** | Pointer to **string** | The ID of the customer associated with the sales order. | [optional] 
**PoNumber** | Pointer to **string** | The customer&#39;s purchase order number on the sales order. | [optional] 
**Status** | Pointer to **string** | The purchase order status. | [optional] 
**Type** | Pointer to **string** | The purchase order type. | [optional] 
**Category** | Pointer to **string** | The purchase order category. | [optional] 
**Terms** | Pointer to **string** | The order&#39;s payment terms. | [optional] 
**IncoTerms** | Pointer to **string** | International Commercial (INCO) Terms applied to the sales order. | [optional] 
**Fob** | Pointer to **string** | The Freight on Board terms of the order. | [optional] 
**FreightTerms** | Pointer to **string** | The freight terms applied to the order. | [optional] 
**InsideSalesId** | Pointer to **string** | The ID of the inside salesperson associated with the order. | [optional] 
**OutsideSalesId** | Pointer to **string** | The ID of the outside salesperson associated with the order. | [optional] 
**PoNumberRevision** | Pointer to **string** | The revision number of the purchase order. | [optional] 
**PoNumberRevisionDate** | Pointer to **time.Time** | The date on which the purchase order was revised. | [optional] 
**OrderDate** | Pointer to **time.Time** | The date on which the order was placed. | [optional] 
**ExpirationDate** | Pointer to **time.Time** | The date on which the purchase order expires. | [optional] 
**ContactId** | Pointer to **string** | The ID of the contact associated with this order. | [optional] 
**Carrier** | Pointer to **string** | The carrier associated with the purchase order. (A carrier is a supplier that has a Supplier Type of &amp;quot;Carrier&amp;quot;.) | [optional] 
**Note** | Pointer to **string** | A note on the sales order. | [optional] 
**InvoiceInternalNote** | Pointer to **string** | A note on the sales order that will populate the Internal Note field on the accounts receivable customer invoice record. | [optional] 
**InvoicePrintedNote** | Pointer to **string** | A note on the sales order that will populate the printed Note field on the accounts receivable customer invoice record. | [optional] 
**MultipleDocksPerShipper** | Pointer to **bool** | Identifies whether multiple releases with different shipping docks on a single shipper are allowed. | [optional] 
**MultiplePOPerShipper** | Pointer to **bool** | Identifies whether multiple orders on one shipper are allowed. | [optional] 
**Id** | Pointer to **string** | A unique identifier for the customer purchase order. This will be automatically generated if omitted from the request. | [optional] 

## Methods

### NewSalesOrdersApiCreateCustomerPurchaseOrderRequest

`func NewSalesOrdersApiCreateCustomerPurchaseOrderRequest() *SalesOrdersApiCreateCustomerPurchaseOrderRequest`

NewSalesOrdersApiCreateCustomerPurchaseOrderRequest instantiates a new SalesOrdersApiCreateCustomerPurchaseOrderRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSalesOrdersApiCreateCustomerPurchaseOrderRequestWithDefaults

`func NewSalesOrdersApiCreateCustomerPurchaseOrderRequestWithDefaults() *SalesOrdersApiCreateCustomerPurchaseOrderRequest`

NewSalesOrdersApiCreateCustomerPurchaseOrderRequestWithDefaults instantiates a new SalesOrdersApiCreateCustomerPurchaseOrderRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCustomerId

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### GetPoNumber

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) GetPoNumber() string`

GetPoNumber returns the PoNumber field if non-nil, zero value otherwise.

### GetPoNumberOk

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) GetPoNumberOk() (*string, bool)`

GetPoNumberOk returns a tuple with the PoNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoNumber

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) SetPoNumber(v string)`

SetPoNumber sets PoNumber field to given value.

### HasPoNumber

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) HasPoNumber() bool`

HasPoNumber returns a boolean if a field has been set.

### GetStatus

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetType

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) HasType() bool`

HasType returns a boolean if a field has been set.

### GetCategory

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) GetCategory() string`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) GetCategoryOk() (*string, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) SetCategory(v string)`

SetCategory sets Category field to given value.

### HasCategory

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) HasCategory() bool`

HasCategory returns a boolean if a field has been set.

### GetTerms

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) GetTerms() string`

GetTerms returns the Terms field if non-nil, zero value otherwise.

### GetTermsOk

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) GetTermsOk() (*string, bool)`

GetTermsOk returns a tuple with the Terms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTerms

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) SetTerms(v string)`

SetTerms sets Terms field to given value.

### HasTerms

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) HasTerms() bool`

HasTerms returns a boolean if a field has been set.

### GetIncoTerms

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) GetIncoTerms() string`

GetIncoTerms returns the IncoTerms field if non-nil, zero value otherwise.

### GetIncoTermsOk

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) GetIncoTermsOk() (*string, bool)`

GetIncoTermsOk returns a tuple with the IncoTerms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncoTerms

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) SetIncoTerms(v string)`

SetIncoTerms sets IncoTerms field to given value.

### HasIncoTerms

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) HasIncoTerms() bool`

HasIncoTerms returns a boolean if a field has been set.

### GetFob

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) GetFob() string`

GetFob returns the Fob field if non-nil, zero value otherwise.

### GetFobOk

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) GetFobOk() (*string, bool)`

GetFobOk returns a tuple with the Fob field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFob

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) SetFob(v string)`

SetFob sets Fob field to given value.

### HasFob

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) HasFob() bool`

HasFob returns a boolean if a field has been set.

### GetFreightTerms

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) GetFreightTerms() string`

GetFreightTerms returns the FreightTerms field if non-nil, zero value otherwise.

### GetFreightTermsOk

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) GetFreightTermsOk() (*string, bool)`

GetFreightTermsOk returns a tuple with the FreightTerms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFreightTerms

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) SetFreightTerms(v string)`

SetFreightTerms sets FreightTerms field to given value.

### HasFreightTerms

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) HasFreightTerms() bool`

HasFreightTerms returns a boolean if a field has been set.

### GetInsideSalesId

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) GetInsideSalesId() string`

GetInsideSalesId returns the InsideSalesId field if non-nil, zero value otherwise.

### GetInsideSalesIdOk

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) GetInsideSalesIdOk() (*string, bool)`

GetInsideSalesIdOk returns a tuple with the InsideSalesId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInsideSalesId

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) SetInsideSalesId(v string)`

SetInsideSalesId sets InsideSalesId field to given value.

### HasInsideSalesId

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) HasInsideSalesId() bool`

HasInsideSalesId returns a boolean if a field has been set.

### GetOutsideSalesId

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) GetOutsideSalesId() string`

GetOutsideSalesId returns the OutsideSalesId field if non-nil, zero value otherwise.

### GetOutsideSalesIdOk

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) GetOutsideSalesIdOk() (*string, bool)`

GetOutsideSalesIdOk returns a tuple with the OutsideSalesId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutsideSalesId

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) SetOutsideSalesId(v string)`

SetOutsideSalesId sets OutsideSalesId field to given value.

### HasOutsideSalesId

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) HasOutsideSalesId() bool`

HasOutsideSalesId returns a boolean if a field has been set.

### GetPoNumberRevision

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) GetPoNumberRevision() string`

GetPoNumberRevision returns the PoNumberRevision field if non-nil, zero value otherwise.

### GetPoNumberRevisionOk

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) GetPoNumberRevisionOk() (*string, bool)`

GetPoNumberRevisionOk returns a tuple with the PoNumberRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoNumberRevision

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) SetPoNumberRevision(v string)`

SetPoNumberRevision sets PoNumberRevision field to given value.

### HasPoNumberRevision

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) HasPoNumberRevision() bool`

HasPoNumberRevision returns a boolean if a field has been set.

### GetPoNumberRevisionDate

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) GetPoNumberRevisionDate() time.Time`

GetPoNumberRevisionDate returns the PoNumberRevisionDate field if non-nil, zero value otherwise.

### GetPoNumberRevisionDateOk

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) GetPoNumberRevisionDateOk() (*time.Time, bool)`

GetPoNumberRevisionDateOk returns a tuple with the PoNumberRevisionDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoNumberRevisionDate

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) SetPoNumberRevisionDate(v time.Time)`

SetPoNumberRevisionDate sets PoNumberRevisionDate field to given value.

### HasPoNumberRevisionDate

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) HasPoNumberRevisionDate() bool`

HasPoNumberRevisionDate returns a boolean if a field has been set.

### GetOrderDate

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) GetOrderDate() time.Time`

GetOrderDate returns the OrderDate field if non-nil, zero value otherwise.

### GetOrderDateOk

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) GetOrderDateOk() (*time.Time, bool)`

GetOrderDateOk returns a tuple with the OrderDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderDate

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) SetOrderDate(v time.Time)`

SetOrderDate sets OrderDate field to given value.

### HasOrderDate

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) HasOrderDate() bool`

HasOrderDate returns a boolean if a field has been set.

### GetExpirationDate

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) GetExpirationDate() time.Time`

GetExpirationDate returns the ExpirationDate field if non-nil, zero value otherwise.

### GetExpirationDateOk

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) GetExpirationDateOk() (*time.Time, bool)`

GetExpirationDateOk returns a tuple with the ExpirationDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpirationDate

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) SetExpirationDate(v time.Time)`

SetExpirationDate sets ExpirationDate field to given value.

### HasExpirationDate

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) HasExpirationDate() bool`

HasExpirationDate returns a boolean if a field has been set.

### GetContactId

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) GetContactId() string`

GetContactId returns the ContactId field if non-nil, zero value otherwise.

### GetContactIdOk

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) GetContactIdOk() (*string, bool)`

GetContactIdOk returns a tuple with the ContactId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactId

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) SetContactId(v string)`

SetContactId sets ContactId field to given value.

### HasContactId

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) HasContactId() bool`

HasContactId returns a boolean if a field has been set.

### GetCarrier

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) GetCarrier() string`

GetCarrier returns the Carrier field if non-nil, zero value otherwise.

### GetCarrierOk

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) GetCarrierOk() (*string, bool)`

GetCarrierOk returns a tuple with the Carrier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrier

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) SetCarrier(v string)`

SetCarrier sets Carrier field to given value.

### HasCarrier

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) HasCarrier() bool`

HasCarrier returns a boolean if a field has been set.

### GetNote

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetInvoiceInternalNote

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) GetInvoiceInternalNote() string`

GetInvoiceInternalNote returns the InvoiceInternalNote field if non-nil, zero value otherwise.

### GetInvoiceInternalNoteOk

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) GetInvoiceInternalNoteOk() (*string, bool)`

GetInvoiceInternalNoteOk returns a tuple with the InvoiceInternalNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceInternalNote

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) SetInvoiceInternalNote(v string)`

SetInvoiceInternalNote sets InvoiceInternalNote field to given value.

### HasInvoiceInternalNote

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) HasInvoiceInternalNote() bool`

HasInvoiceInternalNote returns a boolean if a field has been set.

### GetInvoicePrintedNote

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) GetInvoicePrintedNote() string`

GetInvoicePrintedNote returns the InvoicePrintedNote field if non-nil, zero value otherwise.

### GetInvoicePrintedNoteOk

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) GetInvoicePrintedNoteOk() (*string, bool)`

GetInvoicePrintedNoteOk returns a tuple with the InvoicePrintedNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoicePrintedNote

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) SetInvoicePrintedNote(v string)`

SetInvoicePrintedNote sets InvoicePrintedNote field to given value.

### HasInvoicePrintedNote

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) HasInvoicePrintedNote() bool`

HasInvoicePrintedNote returns a boolean if a field has been set.

### GetMultipleDocksPerShipper

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) GetMultipleDocksPerShipper() bool`

GetMultipleDocksPerShipper returns the MultipleDocksPerShipper field if non-nil, zero value otherwise.

### GetMultipleDocksPerShipperOk

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) GetMultipleDocksPerShipperOk() (*bool, bool)`

GetMultipleDocksPerShipperOk returns a tuple with the MultipleDocksPerShipper field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMultipleDocksPerShipper

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) SetMultipleDocksPerShipper(v bool)`

SetMultipleDocksPerShipper sets MultipleDocksPerShipper field to given value.

### HasMultipleDocksPerShipper

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) HasMultipleDocksPerShipper() bool`

HasMultipleDocksPerShipper returns a boolean if a field has been set.

### GetMultiplePOPerShipper

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) GetMultiplePOPerShipper() bool`

GetMultiplePOPerShipper returns the MultiplePOPerShipper field if non-nil, zero value otherwise.

### GetMultiplePOPerShipperOk

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) GetMultiplePOPerShipperOk() (*bool, bool)`

GetMultiplePOPerShipperOk returns a tuple with the MultiplePOPerShipper field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMultiplePOPerShipper

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) SetMultiplePOPerShipper(v bool)`

SetMultiplePOPerShipper sets MultiplePOPerShipper field to given value.

### HasMultiplePOPerShipper

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) HasMultiplePOPerShipper() bool`

HasMultiplePOPerShipper returns a boolean if a field has been set.

### GetId

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *SalesOrdersApiCreateCustomerPurchaseOrderRequest) HasId() bool`

HasId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


