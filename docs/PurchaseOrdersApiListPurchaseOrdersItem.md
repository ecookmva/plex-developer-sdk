# PurchaseOrdersApiListPurchaseOrdersItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | A unique identifier for the purchase order. | [optional] 
**PoNumber** | Pointer to **string** | The purchase order number. | [optional] 
**CurrencyCode** | Pointer to **string** | The ISO 4217 three digit alphanumeric currency code designation. | [optional] 
**Status** | Pointer to **string** | Setup Table: PO Status | [optional] 
**Active** | Pointer to **bool** | This flag will be set to true by default. | [optional] 
**Receive** | Pointer to **bool** | Indicates that purchase orders in this status allow receiving. | [optional] 
**Type** | Pointer to **string** | Application: PO Type | [optional] 
**SupplierId** | Pointer to **string** | A unique identifier for the supplier. | [optional] 
**SupplierAddressId** | Pointer to **string** | A unique identifier for the supplier address. | [optional] 
**IssuedById** | Pointer to **string** | The ID of the user who issued the PO. | [optional] 
**PoDate** | Pointer to **time.Time** | The date the PO was created. | [optional] 
**Terms** | Pointer to **string** | The payment terms associated with the purchase order. Setup Table: Terms | [optional] 
**FreightTerms** | Pointer to **string** | Setup Table: PO Freight Terms | [optional] 
**LineItemCount** | Pointer to **int32** | The number of line items on the PO. | [optional] 
**LineItemTotal** | Pointer to **float64** | The total value of all line items on the PO. | [optional] 
**ShipTo** | Pointer to **string** | The destination to which goods and services on the PO will be shipped to. Application: PO Ship To | [optional] 
**ShipVia** | Pointer to **string** | The method by which the order will be shipped. Setup Table: PO Ship Via | [optional] 
**OrderedById** | Pointer to **string** | The ID of the user who ordered the PO. | [optional] 
**OrderedDate** | Pointer to **time.Time** | The date on which the status was set to On Order. | [optional] 
**Fob** | Pointer to **string** | Freight on Board. Setup Table: PO FOB | [optional] 
**DueDate** | Pointer to **time.Time** | The Due Date for the PO, not for individual lines or releases. | [optional] 
**ContactId** | Pointer to **string** | A unique identifier for the contact. | [optional] 
**ScheduledReceiptDate** | Pointer to **time.Time** | The date on which receipt of the PO is scheduled. | [optional] 
**ApprovedById** | Pointer to **string** | The ID of the user who approved the PO. | [optional] 
**ApprovedDate** | Pointer to **time.Time** | The date on which the PO was approved. | [optional] 
**InternalNote** | Pointer to **string** | A note that can only be viewed on the Purchase Order Detail form. | [optional] 
**Note** | Pointer to **string** | A note for the purchase order that is displayed in grid records. | [optional] 
**Consignment** | Pointer to **bool** | Indicates that the purchase order is a supplier consignment order and will not be invoiced until the goods are used. | [optional] 
**CarrierId** | Pointer to **string** | The ID of the Carrier associated with this PO. A Carrier is a Supplier with a Type of &#39;Carrier&#39;. | [optional] 
**Building** | Pointer to **string** | Application: Buildings | [optional] 
**Department** | Pointer to **string** | Application: Department List | [optional] 
**RouteToEmployeeId** | Pointer to **string** | The ID of the employee to which the PO should sent upon receipt. | [optional] 
**IncoTerms** | Pointer to **string** | International Commercial (INCO) Terms applied to the sales order. Setup Table: INCO Terms | [optional] 
**WeightQuantityTotal** | Pointer to **float64** |  | [optional] 
**BlanketOrder** | Pointer to **bool** | Determines whether the Purchase Order is a blanket order or discrete order. | [optional] 
**CreatedById** | Pointer to **string** | The ID of the user who created the record. | [optional] 
**CreatedDate** | Pointer to **time.Time** | The date on which the record was created. | [optional] 
**ModifiedById** | Pointer to **string** | The ID of the user who last modified the record. | [optional] 
**ModifiedDate** | Pointer to **time.Time** | The date on which the record was last modified. | [optional] 

## Methods

### NewPurchaseOrdersApiListPurchaseOrdersItem

`func NewPurchaseOrdersApiListPurchaseOrdersItem() *PurchaseOrdersApiListPurchaseOrdersItem`

NewPurchaseOrdersApiListPurchaseOrdersItem instantiates a new PurchaseOrdersApiListPurchaseOrdersItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPurchaseOrdersApiListPurchaseOrdersItemWithDefaults

`func NewPurchaseOrdersApiListPurchaseOrdersItemWithDefaults() *PurchaseOrdersApiListPurchaseOrdersItem`

NewPurchaseOrdersApiListPurchaseOrdersItemWithDefaults instantiates a new PurchaseOrdersApiListPurchaseOrdersItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) HasId() bool`

HasId returns a boolean if a field has been set.

### GetPoNumber

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetPoNumber() string`

GetPoNumber returns the PoNumber field if non-nil, zero value otherwise.

### GetPoNumberOk

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetPoNumberOk() (*string, bool)`

GetPoNumberOk returns a tuple with the PoNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoNumber

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) SetPoNumber(v string)`

SetPoNumber sets PoNumber field to given value.

### HasPoNumber

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) HasPoNumber() bool`

HasPoNumber returns a boolean if a field has been set.

### GetCurrencyCode

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetCurrencyCode() string`

GetCurrencyCode returns the CurrencyCode field if non-nil, zero value otherwise.

### GetCurrencyCodeOk

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetCurrencyCodeOk() (*string, bool)`

GetCurrencyCodeOk returns a tuple with the CurrencyCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyCode

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) SetCurrencyCode(v string)`

SetCurrencyCode sets CurrencyCode field to given value.

### HasCurrencyCode

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) HasCurrencyCode() bool`

HasCurrencyCode returns a boolean if a field has been set.

### GetStatus

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetActive

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetReceive

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetReceive() bool`

GetReceive returns the Receive field if non-nil, zero value otherwise.

### GetReceiveOk

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetReceiveOk() (*bool, bool)`

GetReceiveOk returns a tuple with the Receive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceive

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) SetReceive(v bool)`

SetReceive sets Receive field to given value.

### HasReceive

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) HasReceive() bool`

HasReceive returns a boolean if a field has been set.

### GetType

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) HasType() bool`

HasType returns a boolean if a field has been set.

### GetSupplierId

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetSupplierId() string`

GetSupplierId returns the SupplierId field if non-nil, zero value otherwise.

### GetSupplierIdOk

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetSupplierIdOk() (*string, bool)`

GetSupplierIdOk returns a tuple with the SupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierId

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) SetSupplierId(v string)`

SetSupplierId sets SupplierId field to given value.

### HasSupplierId

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) HasSupplierId() bool`

HasSupplierId returns a boolean if a field has been set.

### GetSupplierAddressId

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetSupplierAddressId() string`

GetSupplierAddressId returns the SupplierAddressId field if non-nil, zero value otherwise.

### GetSupplierAddressIdOk

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetSupplierAddressIdOk() (*string, bool)`

GetSupplierAddressIdOk returns a tuple with the SupplierAddressId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierAddressId

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) SetSupplierAddressId(v string)`

SetSupplierAddressId sets SupplierAddressId field to given value.

### HasSupplierAddressId

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) HasSupplierAddressId() bool`

HasSupplierAddressId returns a boolean if a field has been set.

### GetIssuedById

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetIssuedById() string`

GetIssuedById returns the IssuedById field if non-nil, zero value otherwise.

### GetIssuedByIdOk

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetIssuedByIdOk() (*string, bool)`

GetIssuedByIdOk returns a tuple with the IssuedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIssuedById

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) SetIssuedById(v string)`

SetIssuedById sets IssuedById field to given value.

### HasIssuedById

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) HasIssuedById() bool`

HasIssuedById returns a boolean if a field has been set.

### GetPoDate

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetPoDate() time.Time`

GetPoDate returns the PoDate field if non-nil, zero value otherwise.

### GetPoDateOk

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetPoDateOk() (*time.Time, bool)`

GetPoDateOk returns a tuple with the PoDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoDate

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) SetPoDate(v time.Time)`

SetPoDate sets PoDate field to given value.

### HasPoDate

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) HasPoDate() bool`

HasPoDate returns a boolean if a field has been set.

### GetTerms

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetTerms() string`

GetTerms returns the Terms field if non-nil, zero value otherwise.

### GetTermsOk

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetTermsOk() (*string, bool)`

GetTermsOk returns a tuple with the Terms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTerms

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) SetTerms(v string)`

SetTerms sets Terms field to given value.

### HasTerms

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) HasTerms() bool`

HasTerms returns a boolean if a field has been set.

### GetFreightTerms

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetFreightTerms() string`

GetFreightTerms returns the FreightTerms field if non-nil, zero value otherwise.

### GetFreightTermsOk

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetFreightTermsOk() (*string, bool)`

GetFreightTermsOk returns a tuple with the FreightTerms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFreightTerms

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) SetFreightTerms(v string)`

SetFreightTerms sets FreightTerms field to given value.

### HasFreightTerms

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) HasFreightTerms() bool`

HasFreightTerms returns a boolean if a field has been set.

### GetLineItemCount

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetLineItemCount() int32`

GetLineItemCount returns the LineItemCount field if non-nil, zero value otherwise.

### GetLineItemCountOk

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetLineItemCountOk() (*int32, bool)`

GetLineItemCountOk returns a tuple with the LineItemCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineItemCount

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) SetLineItemCount(v int32)`

SetLineItemCount sets LineItemCount field to given value.

### HasLineItemCount

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) HasLineItemCount() bool`

HasLineItemCount returns a boolean if a field has been set.

### GetLineItemTotal

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetLineItemTotal() float64`

GetLineItemTotal returns the LineItemTotal field if non-nil, zero value otherwise.

### GetLineItemTotalOk

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetLineItemTotalOk() (*float64, bool)`

GetLineItemTotalOk returns a tuple with the LineItemTotal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineItemTotal

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) SetLineItemTotal(v float64)`

SetLineItemTotal sets LineItemTotal field to given value.

### HasLineItemTotal

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) HasLineItemTotal() bool`

HasLineItemTotal returns a boolean if a field has been set.

### GetShipTo

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetShipTo() string`

GetShipTo returns the ShipTo field if non-nil, zero value otherwise.

### GetShipToOk

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetShipToOk() (*string, bool)`

GetShipToOk returns a tuple with the ShipTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipTo

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) SetShipTo(v string)`

SetShipTo sets ShipTo field to given value.

### HasShipTo

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) HasShipTo() bool`

HasShipTo returns a boolean if a field has been set.

### GetShipVia

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetShipVia() string`

GetShipVia returns the ShipVia field if non-nil, zero value otherwise.

### GetShipViaOk

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetShipViaOk() (*string, bool)`

GetShipViaOk returns a tuple with the ShipVia field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipVia

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) SetShipVia(v string)`

SetShipVia sets ShipVia field to given value.

### HasShipVia

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) HasShipVia() bool`

HasShipVia returns a boolean if a field has been set.

### GetOrderedById

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetOrderedById() string`

GetOrderedById returns the OrderedById field if non-nil, zero value otherwise.

### GetOrderedByIdOk

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetOrderedByIdOk() (*string, bool)`

GetOrderedByIdOk returns a tuple with the OrderedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderedById

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) SetOrderedById(v string)`

SetOrderedById sets OrderedById field to given value.

### HasOrderedById

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) HasOrderedById() bool`

HasOrderedById returns a boolean if a field has been set.

### GetOrderedDate

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetOrderedDate() time.Time`

GetOrderedDate returns the OrderedDate field if non-nil, zero value otherwise.

### GetOrderedDateOk

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetOrderedDateOk() (*time.Time, bool)`

GetOrderedDateOk returns a tuple with the OrderedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderedDate

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) SetOrderedDate(v time.Time)`

SetOrderedDate sets OrderedDate field to given value.

### HasOrderedDate

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) HasOrderedDate() bool`

HasOrderedDate returns a boolean if a field has been set.

### GetFob

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetFob() string`

GetFob returns the Fob field if non-nil, zero value otherwise.

### GetFobOk

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetFobOk() (*string, bool)`

GetFobOk returns a tuple with the Fob field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFob

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) SetFob(v string)`

SetFob sets Fob field to given value.

### HasFob

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) HasFob() bool`

HasFob returns a boolean if a field has been set.

### GetDueDate

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetDueDate() time.Time`

GetDueDate returns the DueDate field if non-nil, zero value otherwise.

### GetDueDateOk

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetDueDateOk() (*time.Time, bool)`

GetDueDateOk returns a tuple with the DueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueDate

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) SetDueDate(v time.Time)`

SetDueDate sets DueDate field to given value.

### HasDueDate

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) HasDueDate() bool`

HasDueDate returns a boolean if a field has been set.

### GetContactId

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetContactId() string`

GetContactId returns the ContactId field if non-nil, zero value otherwise.

### GetContactIdOk

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetContactIdOk() (*string, bool)`

GetContactIdOk returns a tuple with the ContactId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactId

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) SetContactId(v string)`

SetContactId sets ContactId field to given value.

### HasContactId

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) HasContactId() bool`

HasContactId returns a boolean if a field has been set.

### GetScheduledReceiptDate

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetScheduledReceiptDate() time.Time`

GetScheduledReceiptDate returns the ScheduledReceiptDate field if non-nil, zero value otherwise.

### GetScheduledReceiptDateOk

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetScheduledReceiptDateOk() (*time.Time, bool)`

GetScheduledReceiptDateOk returns a tuple with the ScheduledReceiptDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScheduledReceiptDate

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) SetScheduledReceiptDate(v time.Time)`

SetScheduledReceiptDate sets ScheduledReceiptDate field to given value.

### HasScheduledReceiptDate

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) HasScheduledReceiptDate() bool`

HasScheduledReceiptDate returns a boolean if a field has been set.

### GetApprovedById

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetApprovedById() string`

GetApprovedById returns the ApprovedById field if non-nil, zero value otherwise.

### GetApprovedByIdOk

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetApprovedByIdOk() (*string, bool)`

GetApprovedByIdOk returns a tuple with the ApprovedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovedById

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) SetApprovedById(v string)`

SetApprovedById sets ApprovedById field to given value.

### HasApprovedById

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) HasApprovedById() bool`

HasApprovedById returns a boolean if a field has been set.

### GetApprovedDate

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetApprovedDate() time.Time`

GetApprovedDate returns the ApprovedDate field if non-nil, zero value otherwise.

### GetApprovedDateOk

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetApprovedDateOk() (*time.Time, bool)`

GetApprovedDateOk returns a tuple with the ApprovedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovedDate

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) SetApprovedDate(v time.Time)`

SetApprovedDate sets ApprovedDate field to given value.

### HasApprovedDate

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) HasApprovedDate() bool`

HasApprovedDate returns a boolean if a field has been set.

### GetInternalNote

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetInternalNote() string`

GetInternalNote returns the InternalNote field if non-nil, zero value otherwise.

### GetInternalNoteOk

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetInternalNoteOk() (*string, bool)`

GetInternalNoteOk returns a tuple with the InternalNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInternalNote

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) SetInternalNote(v string)`

SetInternalNote sets InternalNote field to given value.

### HasInternalNote

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) HasInternalNote() bool`

HasInternalNote returns a boolean if a field has been set.

### GetNote

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetConsignment

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetConsignment() bool`

GetConsignment returns the Consignment field if non-nil, zero value otherwise.

### GetConsignmentOk

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetConsignmentOk() (*bool, bool)`

GetConsignmentOk returns a tuple with the Consignment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsignment

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) SetConsignment(v bool)`

SetConsignment sets Consignment field to given value.

### HasConsignment

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) HasConsignment() bool`

HasConsignment returns a boolean if a field has been set.

### GetCarrierId

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetCarrierId() string`

GetCarrierId returns the CarrierId field if non-nil, zero value otherwise.

### GetCarrierIdOk

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetCarrierIdOk() (*string, bool)`

GetCarrierIdOk returns a tuple with the CarrierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierId

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) SetCarrierId(v string)`

SetCarrierId sets CarrierId field to given value.

### HasCarrierId

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) HasCarrierId() bool`

HasCarrierId returns a boolean if a field has been set.

### GetBuilding

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetBuilding() string`

GetBuilding returns the Building field if non-nil, zero value otherwise.

### GetBuildingOk

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetBuildingOk() (*string, bool)`

GetBuildingOk returns a tuple with the Building field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuilding

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) SetBuilding(v string)`

SetBuilding sets Building field to given value.

### HasBuilding

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) HasBuilding() bool`

HasBuilding returns a boolean if a field has been set.

### GetDepartment

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetDepartment() string`

GetDepartment returns the Department field if non-nil, zero value otherwise.

### GetDepartmentOk

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetDepartmentOk() (*string, bool)`

GetDepartmentOk returns a tuple with the Department field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDepartment

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) SetDepartment(v string)`

SetDepartment sets Department field to given value.

### HasDepartment

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) HasDepartment() bool`

HasDepartment returns a boolean if a field has been set.

### GetRouteToEmployeeId

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetRouteToEmployeeId() string`

GetRouteToEmployeeId returns the RouteToEmployeeId field if non-nil, zero value otherwise.

### GetRouteToEmployeeIdOk

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetRouteToEmployeeIdOk() (*string, bool)`

GetRouteToEmployeeIdOk returns a tuple with the RouteToEmployeeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRouteToEmployeeId

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) SetRouteToEmployeeId(v string)`

SetRouteToEmployeeId sets RouteToEmployeeId field to given value.

### HasRouteToEmployeeId

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) HasRouteToEmployeeId() bool`

HasRouteToEmployeeId returns a boolean if a field has been set.

### GetIncoTerms

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetIncoTerms() string`

GetIncoTerms returns the IncoTerms field if non-nil, zero value otherwise.

### GetIncoTermsOk

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetIncoTermsOk() (*string, bool)`

GetIncoTermsOk returns a tuple with the IncoTerms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncoTerms

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) SetIncoTerms(v string)`

SetIncoTerms sets IncoTerms field to given value.

### HasIncoTerms

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) HasIncoTerms() bool`

HasIncoTerms returns a boolean if a field has been set.

### GetWeightQuantityTotal

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetWeightQuantityTotal() float64`

GetWeightQuantityTotal returns the WeightQuantityTotal field if non-nil, zero value otherwise.

### GetWeightQuantityTotalOk

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetWeightQuantityTotalOk() (*float64, bool)`

GetWeightQuantityTotalOk returns a tuple with the WeightQuantityTotal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeightQuantityTotal

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) SetWeightQuantityTotal(v float64)`

SetWeightQuantityTotal sets WeightQuantityTotal field to given value.

### HasWeightQuantityTotal

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) HasWeightQuantityTotal() bool`

HasWeightQuantityTotal returns a boolean if a field has been set.

### GetBlanketOrder

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetBlanketOrder() bool`

GetBlanketOrder returns the BlanketOrder field if non-nil, zero value otherwise.

### GetBlanketOrderOk

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetBlanketOrderOk() (*bool, bool)`

GetBlanketOrderOk returns a tuple with the BlanketOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlanketOrder

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) SetBlanketOrder(v bool)`

SetBlanketOrder sets BlanketOrder field to given value.

### HasBlanketOrder

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) HasBlanketOrder() bool`

HasBlanketOrder returns a boolean if a field has been set.

### GetCreatedById

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetCreatedById() string`

GetCreatedById returns the CreatedById field if non-nil, zero value otherwise.

### GetCreatedByIdOk

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetCreatedByIdOk() (*string, bool)`

GetCreatedByIdOk returns a tuple with the CreatedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedById

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) SetCreatedById(v string)`

SetCreatedById sets CreatedById field to given value.

### HasCreatedById

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) HasCreatedById() bool`

HasCreatedById returns a boolean if a field has been set.

### GetCreatedDate

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.

### GetModifiedById

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetModifiedDate

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetModifiedDate() time.Time`

GetModifiedDate returns the ModifiedDate field if non-nil, zero value otherwise.

### GetModifiedDateOk

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) GetModifiedDateOk() (*time.Time, bool)`

GetModifiedDateOk returns a tuple with the ModifiedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDate

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) SetModifiedDate(v time.Time)`

SetModifiedDate sets ModifiedDate field to given value.

### HasModifiedDate

`func (o *PurchaseOrdersApiListPurchaseOrdersItem) HasModifiedDate() bool`

HasModifiedDate returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


