# CustomersApiSyncCustomersRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | A unique identifier for the Customer Address. This will be automatically generated if omitted from the request. | [optional] 
**Code** | Pointer to **string** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Status** | Pointer to **string** | Setup Table: Customer Status | [optional] 
**Type** | Pointer to **string** | Setup Table: Customer Type | [optional] 
**Note** | Pointer to **string** |  | [optional] 
**SupplierCode** | Pointer to **string** |  | [optional] 
**OtherCustomerCode** | Pointer to **string** |  | [optional] 
**Rating** | Pointer to **string** | Setup Table: Customer Rating | [optional] 
**Industries** | Pointer to **[]string** | Setup Table: Industries | [optional] 
**DefaultCarrierIds** | Pointer to **[]string** | A list of Default Carriers, by Supplier ID. | [optional] 
**Region** | Pointer to **string** |  | [optional] 
**BusinessType** | Pointer to **string** | Setup Table: Business Type | [optional] 
**Category** | Pointer to **string** | Setup Table: Customer Category | [optional] 
**Class** | Pointer to **string** | Setup Table: Customer Class | [optional] 
**Catalog** | Pointer to **string** | Screen: Catalogs | [optional] 
**AssignedToId** | Pointer to **string** | The sales person assigned to this customer, by IAM Account ID. | [optional] 
**AssignedTo2Id** | Pointer to **string** | The sales person assigned to this customer, by IAM Account ID. | [optional] 
**AssignedTo3Id** | Pointer to **string** | The sales person assigned to this customer, by IAM Account ID. | [optional] 
**AssignedToGroup** | Pointer to **string** |  | [optional] 
**ContactResourceId** | Pointer to **string** | The Contact_Id of the sales person assigned to this Customer. | [optional] 
**AnnualSalesMillions** | Pointer to **float64** |  | [optional] 
**EstimatedEmployees** | Pointer to **string** |  | [optional] 
**Phone** | Pointer to **string** |  | [optional] 
**Fax** | Pointer to **string** |  | [optional] 
**Email** | Pointer to **string** |  | [optional] 
**TrackingNoOnWeighScaleRequired** | Pointer to **bool** |  | [optional] 
**MultipleOrdersPerShipper** | Pointer to **bool** |  | [optional] 
**EstimatedAnnualSales** | Pointer to **string** |  | [optional] 
**NewShipperPerReleaseNo** | Pointer to **bool** |  | [optional] 
**DefaultBackOrder** | Pointer to **string** | Setup Table: Back Order | [optional] 
**Financials** | Pointer to [**Financials**](Financials.md) |  | [optional] 
**Addresses** | Pointer to [**[]AddressesItem**](AddressesItem.md) | The customer&#39;s sub-resources: customer addresses | [optional] 
**MaxDaysOutstanding** | Pointer to **int32** |  | [optional] 
**CurrencyCode** | Pointer to **string** |  | [optional] 
**Terms** | Pointer to **string** | Setup Table: Terms | [optional] 
**RequestedTerms** | Pointer to **string** | Setup Table: Terms | [optional] 
**CreditLimit** | Pointer to **float64** |  | [optional] 
**SalesTaxExempt** | Pointer to **bool** |  | [optional] 
**CreditHold** | Pointer to **bool** |  | [optional] 
**CreditStatus** | Pointer to **string** | Setup Table: Credit Status | [optional] 
**CreditRating** | Pointer to **string** | Setup Table: Credit Rating | [optional] 
**CreditReviewDate** | Pointer to **time.Time** |  | [optional] 
**CreditNote** | Pointer to **string** |  | [optional] 
**InvoiceDelivery** | Pointer to **string** | Setup Table: Invoice Delivery. The default value is &amp;quot;Mail/Print Invoice&amp;quot;. | [optional] 
**SalesTaxExemptNo** | Pointer to **string** |  | [optional] 
**BillingSeparation** | Pointer to **int32** |  | [optional] 
**InvoiceLineReference** | Pointer to **string** | The customer&#39;s invoices will reference one of the following options: Part No, Release No, Customer Order No | [optional] 
**TaxIdNo** | Pointer to **string** |  | [optional] 
**RetroactivePricing** | Pointer to **bool** |  | [optional] 
**GovernmentIssuedTaxNo** | Pointer to **string** |  | [optional] 
**InvoicePo** | Pointer to **string** | The invoice PO will reference of the following options: Release No or Customer Release No. | [optional] 
**QuoteTo** | Pointer to **bool** | If true, this address may be used for customer quotes. | [optional] 
**ShipTo** | Pointer to **bool** | If true, this address may be used for customer shipping. | [optional] 
**BillTo** | Pointer to **bool** | If true, this address may be used for customer invoices. | [optional] 
**BillToAddressId** | Pointer to **string** | The customer address ID to be used for customer billing. | [optional] 
**RemitTo** | Pointer to **bool** | If true, this address may be used for remittance. | [optional] 
**ThirdPartyShipTo** | Pointer to **bool** | If true, this is a valid third-party shipping address. | [optional] 
**ThirdPartyShipToAddressId** | Pointer to **string** | The customer address ID to be used for third-party shipping. | [optional] 
**Pool** | Pointer to **bool** | If true, this is a valid pool address. A pool is a location used to organize shipments and routes the shippers to the Ship To location. | [optional] 
**PoolAddressId** | Pointer to **string** | The customer address ID to be used for pooling. | [optional] 
**OldCustomerNo** | Pointer to **string** |  | [optional] 
**Active** | Pointer to **bool** |  | [optional] 
**Address** | Pointer to **string** |  | [optional] 
**City** | Pointer to **string** |  | [optional] 
**State** | Pointer to **string** |  | [optional] 
**Zip** | Pointer to **string** |  | [optional] 
**Country** | Pointer to **string** |  | [optional] 
**County** | Pointer to **string** |  | [optional] 
**ShippingInstructions** | Pointer to **string** |  | [optional] 
**IgnoreTransitOnWeekends** | Pointer to **bool** |  | [optional] 
**TransportationLeadTime** | Pointer to **int32** |  | [optional] 
**TruckType** | Pointer to **string** | Screen: Truck Types | [optional] 
**SalespersonId** | Pointer to **string** | The salesperson assigned to this customer, by IAM account ID. | [optional] 
**StatementAddressId** | Pointer to **string** | The address to which statements should be sent, if this address is a valid Billing address. | [optional] 
**FreightTerms** | Pointer to **string** | Setup Table: Freight Terms | [optional] 
**InsideSalespersonId** | Pointer to **string** | The salesperson assigned to this customer, by IAM account ID. | [optional] 
**DefaultShipFrom** | Pointer to **string** | Screen: Building List | [optional] 
**FreightBillTo** | Pointer to **bool** | If true, this is a valid address for freight billing. | [optional] 
**FreightBillToAddressId** | Pointer to **string** | The customer address to be used for freight billing. | [optional] 
**SoldTo** | Pointer to **bool** |  | [optional] 
**DunsNo** | Pointer to **string** |  | [optional] 
**CommercialInvoiceVatNo** | Pointer to **string** |  | [optional] 
**Template** | Pointer to **bool** | Only one address can be used as the address template. | [optional] 
**IncoTerms** | Pointer to **string** |  | [optional] 
**NegotiatedPlace** | Pointer to **string** |  | [optional] 
**BackOrder** | Pointer to **string** | Setup Table: Back_Order | [optional] 

## Methods

### NewCustomersApiSyncCustomersRequest

`func NewCustomersApiSyncCustomersRequest() *CustomersApiSyncCustomersRequest`

NewCustomersApiSyncCustomersRequest instantiates a new CustomersApiSyncCustomersRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomersApiSyncCustomersRequestWithDefaults

`func NewCustomersApiSyncCustomersRequestWithDefaults() *CustomersApiSyncCustomersRequest`

NewCustomersApiSyncCustomersRequestWithDefaults instantiates a new CustomersApiSyncCustomersRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CustomersApiSyncCustomersRequest) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CustomersApiSyncCustomersRequest) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CustomersApiSyncCustomersRequest) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *CustomersApiSyncCustomersRequest) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCode

`func (o *CustomersApiSyncCustomersRequest) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *CustomersApiSyncCustomersRequest) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *CustomersApiSyncCustomersRequest) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *CustomersApiSyncCustomersRequest) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetName

`func (o *CustomersApiSyncCustomersRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CustomersApiSyncCustomersRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CustomersApiSyncCustomersRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *CustomersApiSyncCustomersRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### GetStatus

`func (o *CustomersApiSyncCustomersRequest) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CustomersApiSyncCustomersRequest) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CustomersApiSyncCustomersRequest) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *CustomersApiSyncCustomersRequest) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetType

`func (o *CustomersApiSyncCustomersRequest) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *CustomersApiSyncCustomersRequest) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *CustomersApiSyncCustomersRequest) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *CustomersApiSyncCustomersRequest) HasType() bool`

HasType returns a boolean if a field has been set.

### GetNote

`func (o *CustomersApiSyncCustomersRequest) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *CustomersApiSyncCustomersRequest) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *CustomersApiSyncCustomersRequest) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *CustomersApiSyncCustomersRequest) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetSupplierCode

`func (o *CustomersApiSyncCustomersRequest) GetSupplierCode() string`

GetSupplierCode returns the SupplierCode field if non-nil, zero value otherwise.

### GetSupplierCodeOk

`func (o *CustomersApiSyncCustomersRequest) GetSupplierCodeOk() (*string, bool)`

GetSupplierCodeOk returns a tuple with the SupplierCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierCode

`func (o *CustomersApiSyncCustomersRequest) SetSupplierCode(v string)`

SetSupplierCode sets SupplierCode field to given value.

### HasSupplierCode

`func (o *CustomersApiSyncCustomersRequest) HasSupplierCode() bool`

HasSupplierCode returns a boolean if a field has been set.

### GetOtherCustomerCode

`func (o *CustomersApiSyncCustomersRequest) GetOtherCustomerCode() string`

GetOtherCustomerCode returns the OtherCustomerCode field if non-nil, zero value otherwise.

### GetOtherCustomerCodeOk

`func (o *CustomersApiSyncCustomersRequest) GetOtherCustomerCodeOk() (*string, bool)`

GetOtherCustomerCodeOk returns a tuple with the OtherCustomerCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOtherCustomerCode

`func (o *CustomersApiSyncCustomersRequest) SetOtherCustomerCode(v string)`

SetOtherCustomerCode sets OtherCustomerCode field to given value.

### HasOtherCustomerCode

`func (o *CustomersApiSyncCustomersRequest) HasOtherCustomerCode() bool`

HasOtherCustomerCode returns a boolean if a field has been set.

### GetRating

`func (o *CustomersApiSyncCustomersRequest) GetRating() string`

GetRating returns the Rating field if non-nil, zero value otherwise.

### GetRatingOk

`func (o *CustomersApiSyncCustomersRequest) GetRatingOk() (*string, bool)`

GetRatingOk returns a tuple with the Rating field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRating

`func (o *CustomersApiSyncCustomersRequest) SetRating(v string)`

SetRating sets Rating field to given value.

### HasRating

`func (o *CustomersApiSyncCustomersRequest) HasRating() bool`

HasRating returns a boolean if a field has been set.

### GetIndustries

`func (o *CustomersApiSyncCustomersRequest) GetIndustries() []string`

GetIndustries returns the Industries field if non-nil, zero value otherwise.

### GetIndustriesOk

`func (o *CustomersApiSyncCustomersRequest) GetIndustriesOk() (*[]string, bool)`

GetIndustriesOk returns a tuple with the Industries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIndustries

`func (o *CustomersApiSyncCustomersRequest) SetIndustries(v []string)`

SetIndustries sets Industries field to given value.

### HasIndustries

`func (o *CustomersApiSyncCustomersRequest) HasIndustries() bool`

HasIndustries returns a boolean if a field has been set.

### GetDefaultCarrierIds

`func (o *CustomersApiSyncCustomersRequest) GetDefaultCarrierIds() []string`

GetDefaultCarrierIds returns the DefaultCarrierIds field if non-nil, zero value otherwise.

### GetDefaultCarrierIdsOk

`func (o *CustomersApiSyncCustomersRequest) GetDefaultCarrierIdsOk() (*[]string, bool)`

GetDefaultCarrierIdsOk returns a tuple with the DefaultCarrierIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultCarrierIds

`func (o *CustomersApiSyncCustomersRequest) SetDefaultCarrierIds(v []string)`

SetDefaultCarrierIds sets DefaultCarrierIds field to given value.

### HasDefaultCarrierIds

`func (o *CustomersApiSyncCustomersRequest) HasDefaultCarrierIds() bool`

HasDefaultCarrierIds returns a boolean if a field has been set.

### GetRegion

`func (o *CustomersApiSyncCustomersRequest) GetRegion() string`

GetRegion returns the Region field if non-nil, zero value otherwise.

### GetRegionOk

`func (o *CustomersApiSyncCustomersRequest) GetRegionOk() (*string, bool)`

GetRegionOk returns a tuple with the Region field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegion

`func (o *CustomersApiSyncCustomersRequest) SetRegion(v string)`

SetRegion sets Region field to given value.

### HasRegion

`func (o *CustomersApiSyncCustomersRequest) HasRegion() bool`

HasRegion returns a boolean if a field has been set.

### GetBusinessType

`func (o *CustomersApiSyncCustomersRequest) GetBusinessType() string`

GetBusinessType returns the BusinessType field if non-nil, zero value otherwise.

### GetBusinessTypeOk

`func (o *CustomersApiSyncCustomersRequest) GetBusinessTypeOk() (*string, bool)`

GetBusinessTypeOk returns a tuple with the BusinessType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusinessType

`func (o *CustomersApiSyncCustomersRequest) SetBusinessType(v string)`

SetBusinessType sets BusinessType field to given value.

### HasBusinessType

`func (o *CustomersApiSyncCustomersRequest) HasBusinessType() bool`

HasBusinessType returns a boolean if a field has been set.

### GetCategory

`func (o *CustomersApiSyncCustomersRequest) GetCategory() string`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *CustomersApiSyncCustomersRequest) GetCategoryOk() (*string, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *CustomersApiSyncCustomersRequest) SetCategory(v string)`

SetCategory sets Category field to given value.

### HasCategory

`func (o *CustomersApiSyncCustomersRequest) HasCategory() bool`

HasCategory returns a boolean if a field has been set.

### GetClass

`func (o *CustomersApiSyncCustomersRequest) GetClass() string`

GetClass returns the Class field if non-nil, zero value otherwise.

### GetClassOk

`func (o *CustomersApiSyncCustomersRequest) GetClassOk() (*string, bool)`

GetClassOk returns a tuple with the Class field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClass

`func (o *CustomersApiSyncCustomersRequest) SetClass(v string)`

SetClass sets Class field to given value.

### HasClass

`func (o *CustomersApiSyncCustomersRequest) HasClass() bool`

HasClass returns a boolean if a field has been set.

### GetCatalog

`func (o *CustomersApiSyncCustomersRequest) GetCatalog() string`

GetCatalog returns the Catalog field if non-nil, zero value otherwise.

### GetCatalogOk

`func (o *CustomersApiSyncCustomersRequest) GetCatalogOk() (*string, bool)`

GetCatalogOk returns a tuple with the Catalog field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCatalog

`func (o *CustomersApiSyncCustomersRequest) SetCatalog(v string)`

SetCatalog sets Catalog field to given value.

### HasCatalog

`func (o *CustomersApiSyncCustomersRequest) HasCatalog() bool`

HasCatalog returns a boolean if a field has been set.

### GetAssignedToId

`func (o *CustomersApiSyncCustomersRequest) GetAssignedToId() string`

GetAssignedToId returns the AssignedToId field if non-nil, zero value otherwise.

### GetAssignedToIdOk

`func (o *CustomersApiSyncCustomersRequest) GetAssignedToIdOk() (*string, bool)`

GetAssignedToIdOk returns a tuple with the AssignedToId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignedToId

`func (o *CustomersApiSyncCustomersRequest) SetAssignedToId(v string)`

SetAssignedToId sets AssignedToId field to given value.

### HasAssignedToId

`func (o *CustomersApiSyncCustomersRequest) HasAssignedToId() bool`

HasAssignedToId returns a boolean if a field has been set.

### GetAssignedTo2Id

`func (o *CustomersApiSyncCustomersRequest) GetAssignedTo2Id() string`

GetAssignedTo2Id returns the AssignedTo2Id field if non-nil, zero value otherwise.

### GetAssignedTo2IdOk

`func (o *CustomersApiSyncCustomersRequest) GetAssignedTo2IdOk() (*string, bool)`

GetAssignedTo2IdOk returns a tuple with the AssignedTo2Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignedTo2Id

`func (o *CustomersApiSyncCustomersRequest) SetAssignedTo2Id(v string)`

SetAssignedTo2Id sets AssignedTo2Id field to given value.

### HasAssignedTo2Id

`func (o *CustomersApiSyncCustomersRequest) HasAssignedTo2Id() bool`

HasAssignedTo2Id returns a boolean if a field has been set.

### GetAssignedTo3Id

`func (o *CustomersApiSyncCustomersRequest) GetAssignedTo3Id() string`

GetAssignedTo3Id returns the AssignedTo3Id field if non-nil, zero value otherwise.

### GetAssignedTo3IdOk

`func (o *CustomersApiSyncCustomersRequest) GetAssignedTo3IdOk() (*string, bool)`

GetAssignedTo3IdOk returns a tuple with the AssignedTo3Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignedTo3Id

`func (o *CustomersApiSyncCustomersRequest) SetAssignedTo3Id(v string)`

SetAssignedTo3Id sets AssignedTo3Id field to given value.

### HasAssignedTo3Id

`func (o *CustomersApiSyncCustomersRequest) HasAssignedTo3Id() bool`

HasAssignedTo3Id returns a boolean if a field has been set.

### GetAssignedToGroup

`func (o *CustomersApiSyncCustomersRequest) GetAssignedToGroup() string`

GetAssignedToGroup returns the AssignedToGroup field if non-nil, zero value otherwise.

### GetAssignedToGroupOk

`func (o *CustomersApiSyncCustomersRequest) GetAssignedToGroupOk() (*string, bool)`

GetAssignedToGroupOk returns a tuple with the AssignedToGroup field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignedToGroup

`func (o *CustomersApiSyncCustomersRequest) SetAssignedToGroup(v string)`

SetAssignedToGroup sets AssignedToGroup field to given value.

### HasAssignedToGroup

`func (o *CustomersApiSyncCustomersRequest) HasAssignedToGroup() bool`

HasAssignedToGroup returns a boolean if a field has been set.

### GetContactResourceId

`func (o *CustomersApiSyncCustomersRequest) GetContactResourceId() string`

GetContactResourceId returns the ContactResourceId field if non-nil, zero value otherwise.

### GetContactResourceIdOk

`func (o *CustomersApiSyncCustomersRequest) GetContactResourceIdOk() (*string, bool)`

GetContactResourceIdOk returns a tuple with the ContactResourceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactResourceId

`func (o *CustomersApiSyncCustomersRequest) SetContactResourceId(v string)`

SetContactResourceId sets ContactResourceId field to given value.

### HasContactResourceId

`func (o *CustomersApiSyncCustomersRequest) HasContactResourceId() bool`

HasContactResourceId returns a boolean if a field has been set.

### GetAnnualSalesMillions

`func (o *CustomersApiSyncCustomersRequest) GetAnnualSalesMillions() float64`

GetAnnualSalesMillions returns the AnnualSalesMillions field if non-nil, zero value otherwise.

### GetAnnualSalesMillionsOk

`func (o *CustomersApiSyncCustomersRequest) GetAnnualSalesMillionsOk() (*float64, bool)`

GetAnnualSalesMillionsOk returns a tuple with the AnnualSalesMillions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnnualSalesMillions

`func (o *CustomersApiSyncCustomersRequest) SetAnnualSalesMillions(v float64)`

SetAnnualSalesMillions sets AnnualSalesMillions field to given value.

### HasAnnualSalesMillions

`func (o *CustomersApiSyncCustomersRequest) HasAnnualSalesMillions() bool`

HasAnnualSalesMillions returns a boolean if a field has been set.

### GetEstimatedEmployees

`func (o *CustomersApiSyncCustomersRequest) GetEstimatedEmployees() string`

GetEstimatedEmployees returns the EstimatedEmployees field if non-nil, zero value otherwise.

### GetEstimatedEmployeesOk

`func (o *CustomersApiSyncCustomersRequest) GetEstimatedEmployeesOk() (*string, bool)`

GetEstimatedEmployeesOk returns a tuple with the EstimatedEmployees field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEstimatedEmployees

`func (o *CustomersApiSyncCustomersRequest) SetEstimatedEmployees(v string)`

SetEstimatedEmployees sets EstimatedEmployees field to given value.

### HasEstimatedEmployees

`func (o *CustomersApiSyncCustomersRequest) HasEstimatedEmployees() bool`

HasEstimatedEmployees returns a boolean if a field has been set.

### GetPhone

`func (o *CustomersApiSyncCustomersRequest) GetPhone() string`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *CustomersApiSyncCustomersRequest) GetPhoneOk() (*string, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *CustomersApiSyncCustomersRequest) SetPhone(v string)`

SetPhone sets Phone field to given value.

### HasPhone

`func (o *CustomersApiSyncCustomersRequest) HasPhone() bool`

HasPhone returns a boolean if a field has been set.

### GetFax

`func (o *CustomersApiSyncCustomersRequest) GetFax() string`

GetFax returns the Fax field if non-nil, zero value otherwise.

### GetFaxOk

`func (o *CustomersApiSyncCustomersRequest) GetFaxOk() (*string, bool)`

GetFaxOk returns a tuple with the Fax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFax

`func (o *CustomersApiSyncCustomersRequest) SetFax(v string)`

SetFax sets Fax field to given value.

### HasFax

`func (o *CustomersApiSyncCustomersRequest) HasFax() bool`

HasFax returns a boolean if a field has been set.

### GetEmail

`func (o *CustomersApiSyncCustomersRequest) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *CustomersApiSyncCustomersRequest) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *CustomersApiSyncCustomersRequest) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *CustomersApiSyncCustomersRequest) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetTrackingNoOnWeighScaleRequired

`func (o *CustomersApiSyncCustomersRequest) GetTrackingNoOnWeighScaleRequired() bool`

GetTrackingNoOnWeighScaleRequired returns the TrackingNoOnWeighScaleRequired field if non-nil, zero value otherwise.

### GetTrackingNoOnWeighScaleRequiredOk

`func (o *CustomersApiSyncCustomersRequest) GetTrackingNoOnWeighScaleRequiredOk() (*bool, bool)`

GetTrackingNoOnWeighScaleRequiredOk returns a tuple with the TrackingNoOnWeighScaleRequired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackingNoOnWeighScaleRequired

`func (o *CustomersApiSyncCustomersRequest) SetTrackingNoOnWeighScaleRequired(v bool)`

SetTrackingNoOnWeighScaleRequired sets TrackingNoOnWeighScaleRequired field to given value.

### HasTrackingNoOnWeighScaleRequired

`func (o *CustomersApiSyncCustomersRequest) HasTrackingNoOnWeighScaleRequired() bool`

HasTrackingNoOnWeighScaleRequired returns a boolean if a field has been set.

### GetMultipleOrdersPerShipper

`func (o *CustomersApiSyncCustomersRequest) GetMultipleOrdersPerShipper() bool`

GetMultipleOrdersPerShipper returns the MultipleOrdersPerShipper field if non-nil, zero value otherwise.

### GetMultipleOrdersPerShipperOk

`func (o *CustomersApiSyncCustomersRequest) GetMultipleOrdersPerShipperOk() (*bool, bool)`

GetMultipleOrdersPerShipperOk returns a tuple with the MultipleOrdersPerShipper field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMultipleOrdersPerShipper

`func (o *CustomersApiSyncCustomersRequest) SetMultipleOrdersPerShipper(v bool)`

SetMultipleOrdersPerShipper sets MultipleOrdersPerShipper field to given value.

### HasMultipleOrdersPerShipper

`func (o *CustomersApiSyncCustomersRequest) HasMultipleOrdersPerShipper() bool`

HasMultipleOrdersPerShipper returns a boolean if a field has been set.

### GetEstimatedAnnualSales

`func (o *CustomersApiSyncCustomersRequest) GetEstimatedAnnualSales() string`

GetEstimatedAnnualSales returns the EstimatedAnnualSales field if non-nil, zero value otherwise.

### GetEstimatedAnnualSalesOk

`func (o *CustomersApiSyncCustomersRequest) GetEstimatedAnnualSalesOk() (*string, bool)`

GetEstimatedAnnualSalesOk returns a tuple with the EstimatedAnnualSales field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEstimatedAnnualSales

`func (o *CustomersApiSyncCustomersRequest) SetEstimatedAnnualSales(v string)`

SetEstimatedAnnualSales sets EstimatedAnnualSales field to given value.

### HasEstimatedAnnualSales

`func (o *CustomersApiSyncCustomersRequest) HasEstimatedAnnualSales() bool`

HasEstimatedAnnualSales returns a boolean if a field has been set.

### GetNewShipperPerReleaseNo

`func (o *CustomersApiSyncCustomersRequest) GetNewShipperPerReleaseNo() bool`

GetNewShipperPerReleaseNo returns the NewShipperPerReleaseNo field if non-nil, zero value otherwise.

### GetNewShipperPerReleaseNoOk

`func (o *CustomersApiSyncCustomersRequest) GetNewShipperPerReleaseNoOk() (*bool, bool)`

GetNewShipperPerReleaseNoOk returns a tuple with the NewShipperPerReleaseNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNewShipperPerReleaseNo

`func (o *CustomersApiSyncCustomersRequest) SetNewShipperPerReleaseNo(v bool)`

SetNewShipperPerReleaseNo sets NewShipperPerReleaseNo field to given value.

### HasNewShipperPerReleaseNo

`func (o *CustomersApiSyncCustomersRequest) HasNewShipperPerReleaseNo() bool`

HasNewShipperPerReleaseNo returns a boolean if a field has been set.

### GetDefaultBackOrder

`func (o *CustomersApiSyncCustomersRequest) GetDefaultBackOrder() string`

GetDefaultBackOrder returns the DefaultBackOrder field if non-nil, zero value otherwise.

### GetDefaultBackOrderOk

`func (o *CustomersApiSyncCustomersRequest) GetDefaultBackOrderOk() (*string, bool)`

GetDefaultBackOrderOk returns a tuple with the DefaultBackOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultBackOrder

`func (o *CustomersApiSyncCustomersRequest) SetDefaultBackOrder(v string)`

SetDefaultBackOrder sets DefaultBackOrder field to given value.

### HasDefaultBackOrder

`func (o *CustomersApiSyncCustomersRequest) HasDefaultBackOrder() bool`

HasDefaultBackOrder returns a boolean if a field has been set.

### GetFinancials

`func (o *CustomersApiSyncCustomersRequest) GetFinancials() Financials`

GetFinancials returns the Financials field if non-nil, zero value otherwise.

### GetFinancialsOk

`func (o *CustomersApiSyncCustomersRequest) GetFinancialsOk() (*Financials, bool)`

GetFinancialsOk returns a tuple with the Financials field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFinancials

`func (o *CustomersApiSyncCustomersRequest) SetFinancials(v Financials)`

SetFinancials sets Financials field to given value.

### HasFinancials

`func (o *CustomersApiSyncCustomersRequest) HasFinancials() bool`

HasFinancials returns a boolean if a field has been set.

### GetAddresses

`func (o *CustomersApiSyncCustomersRequest) GetAddresses() []AddressesItem`

GetAddresses returns the Addresses field if non-nil, zero value otherwise.

### GetAddressesOk

`func (o *CustomersApiSyncCustomersRequest) GetAddressesOk() (*[]AddressesItem, bool)`

GetAddressesOk returns a tuple with the Addresses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddresses

`func (o *CustomersApiSyncCustomersRequest) SetAddresses(v []AddressesItem)`

SetAddresses sets Addresses field to given value.

### HasAddresses

`func (o *CustomersApiSyncCustomersRequest) HasAddresses() bool`

HasAddresses returns a boolean if a field has been set.

### GetMaxDaysOutstanding

`func (o *CustomersApiSyncCustomersRequest) GetMaxDaysOutstanding() int32`

GetMaxDaysOutstanding returns the MaxDaysOutstanding field if non-nil, zero value otherwise.

### GetMaxDaysOutstandingOk

`func (o *CustomersApiSyncCustomersRequest) GetMaxDaysOutstandingOk() (*int32, bool)`

GetMaxDaysOutstandingOk returns a tuple with the MaxDaysOutstanding field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxDaysOutstanding

`func (o *CustomersApiSyncCustomersRequest) SetMaxDaysOutstanding(v int32)`

SetMaxDaysOutstanding sets MaxDaysOutstanding field to given value.

### HasMaxDaysOutstanding

`func (o *CustomersApiSyncCustomersRequest) HasMaxDaysOutstanding() bool`

HasMaxDaysOutstanding returns a boolean if a field has been set.

### GetCurrencyCode

`func (o *CustomersApiSyncCustomersRequest) GetCurrencyCode() string`

GetCurrencyCode returns the CurrencyCode field if non-nil, zero value otherwise.

### GetCurrencyCodeOk

`func (o *CustomersApiSyncCustomersRequest) GetCurrencyCodeOk() (*string, bool)`

GetCurrencyCodeOk returns a tuple with the CurrencyCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyCode

`func (o *CustomersApiSyncCustomersRequest) SetCurrencyCode(v string)`

SetCurrencyCode sets CurrencyCode field to given value.

### HasCurrencyCode

`func (o *CustomersApiSyncCustomersRequest) HasCurrencyCode() bool`

HasCurrencyCode returns a boolean if a field has been set.

### GetTerms

`func (o *CustomersApiSyncCustomersRequest) GetTerms() string`

GetTerms returns the Terms field if non-nil, zero value otherwise.

### GetTermsOk

`func (o *CustomersApiSyncCustomersRequest) GetTermsOk() (*string, bool)`

GetTermsOk returns a tuple with the Terms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTerms

`func (o *CustomersApiSyncCustomersRequest) SetTerms(v string)`

SetTerms sets Terms field to given value.

### HasTerms

`func (o *CustomersApiSyncCustomersRequest) HasTerms() bool`

HasTerms returns a boolean if a field has been set.

### GetRequestedTerms

`func (o *CustomersApiSyncCustomersRequest) GetRequestedTerms() string`

GetRequestedTerms returns the RequestedTerms field if non-nil, zero value otherwise.

### GetRequestedTermsOk

`func (o *CustomersApiSyncCustomersRequest) GetRequestedTermsOk() (*string, bool)`

GetRequestedTermsOk returns a tuple with the RequestedTerms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestedTerms

`func (o *CustomersApiSyncCustomersRequest) SetRequestedTerms(v string)`

SetRequestedTerms sets RequestedTerms field to given value.

### HasRequestedTerms

`func (o *CustomersApiSyncCustomersRequest) HasRequestedTerms() bool`

HasRequestedTerms returns a boolean if a field has been set.

### GetCreditLimit

`func (o *CustomersApiSyncCustomersRequest) GetCreditLimit() float64`

GetCreditLimit returns the CreditLimit field if non-nil, zero value otherwise.

### GetCreditLimitOk

`func (o *CustomersApiSyncCustomersRequest) GetCreditLimitOk() (*float64, bool)`

GetCreditLimitOk returns a tuple with the CreditLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditLimit

`func (o *CustomersApiSyncCustomersRequest) SetCreditLimit(v float64)`

SetCreditLimit sets CreditLimit field to given value.

### HasCreditLimit

`func (o *CustomersApiSyncCustomersRequest) HasCreditLimit() bool`

HasCreditLimit returns a boolean if a field has been set.

### GetSalesTaxExempt

`func (o *CustomersApiSyncCustomersRequest) GetSalesTaxExempt() bool`

GetSalesTaxExempt returns the SalesTaxExempt field if non-nil, zero value otherwise.

### GetSalesTaxExemptOk

`func (o *CustomersApiSyncCustomersRequest) GetSalesTaxExemptOk() (*bool, bool)`

GetSalesTaxExemptOk returns a tuple with the SalesTaxExempt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSalesTaxExempt

`func (o *CustomersApiSyncCustomersRequest) SetSalesTaxExempt(v bool)`

SetSalesTaxExempt sets SalesTaxExempt field to given value.

### HasSalesTaxExempt

`func (o *CustomersApiSyncCustomersRequest) HasSalesTaxExempt() bool`

HasSalesTaxExempt returns a boolean if a field has been set.

### GetCreditHold

`func (o *CustomersApiSyncCustomersRequest) GetCreditHold() bool`

GetCreditHold returns the CreditHold field if non-nil, zero value otherwise.

### GetCreditHoldOk

`func (o *CustomersApiSyncCustomersRequest) GetCreditHoldOk() (*bool, bool)`

GetCreditHoldOk returns a tuple with the CreditHold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditHold

`func (o *CustomersApiSyncCustomersRequest) SetCreditHold(v bool)`

SetCreditHold sets CreditHold field to given value.

### HasCreditHold

`func (o *CustomersApiSyncCustomersRequest) HasCreditHold() bool`

HasCreditHold returns a boolean if a field has been set.

### GetCreditStatus

`func (o *CustomersApiSyncCustomersRequest) GetCreditStatus() string`

GetCreditStatus returns the CreditStatus field if non-nil, zero value otherwise.

### GetCreditStatusOk

`func (o *CustomersApiSyncCustomersRequest) GetCreditStatusOk() (*string, bool)`

GetCreditStatusOk returns a tuple with the CreditStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditStatus

`func (o *CustomersApiSyncCustomersRequest) SetCreditStatus(v string)`

SetCreditStatus sets CreditStatus field to given value.

### HasCreditStatus

`func (o *CustomersApiSyncCustomersRequest) HasCreditStatus() bool`

HasCreditStatus returns a boolean if a field has been set.

### GetCreditRating

`func (o *CustomersApiSyncCustomersRequest) GetCreditRating() string`

GetCreditRating returns the CreditRating field if non-nil, zero value otherwise.

### GetCreditRatingOk

`func (o *CustomersApiSyncCustomersRequest) GetCreditRatingOk() (*string, bool)`

GetCreditRatingOk returns a tuple with the CreditRating field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditRating

`func (o *CustomersApiSyncCustomersRequest) SetCreditRating(v string)`

SetCreditRating sets CreditRating field to given value.

### HasCreditRating

`func (o *CustomersApiSyncCustomersRequest) HasCreditRating() bool`

HasCreditRating returns a boolean if a field has been set.

### GetCreditReviewDate

`func (o *CustomersApiSyncCustomersRequest) GetCreditReviewDate() time.Time`

GetCreditReviewDate returns the CreditReviewDate field if non-nil, zero value otherwise.

### GetCreditReviewDateOk

`func (o *CustomersApiSyncCustomersRequest) GetCreditReviewDateOk() (*time.Time, bool)`

GetCreditReviewDateOk returns a tuple with the CreditReviewDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditReviewDate

`func (o *CustomersApiSyncCustomersRequest) SetCreditReviewDate(v time.Time)`

SetCreditReviewDate sets CreditReviewDate field to given value.

### HasCreditReviewDate

`func (o *CustomersApiSyncCustomersRequest) HasCreditReviewDate() bool`

HasCreditReviewDate returns a boolean if a field has been set.

### GetCreditNote

`func (o *CustomersApiSyncCustomersRequest) GetCreditNote() string`

GetCreditNote returns the CreditNote field if non-nil, zero value otherwise.

### GetCreditNoteOk

`func (o *CustomersApiSyncCustomersRequest) GetCreditNoteOk() (*string, bool)`

GetCreditNoteOk returns a tuple with the CreditNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditNote

`func (o *CustomersApiSyncCustomersRequest) SetCreditNote(v string)`

SetCreditNote sets CreditNote field to given value.

### HasCreditNote

`func (o *CustomersApiSyncCustomersRequest) HasCreditNote() bool`

HasCreditNote returns a boolean if a field has been set.

### GetInvoiceDelivery

`func (o *CustomersApiSyncCustomersRequest) GetInvoiceDelivery() string`

GetInvoiceDelivery returns the InvoiceDelivery field if non-nil, zero value otherwise.

### GetInvoiceDeliveryOk

`func (o *CustomersApiSyncCustomersRequest) GetInvoiceDeliveryOk() (*string, bool)`

GetInvoiceDeliveryOk returns a tuple with the InvoiceDelivery field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceDelivery

`func (o *CustomersApiSyncCustomersRequest) SetInvoiceDelivery(v string)`

SetInvoiceDelivery sets InvoiceDelivery field to given value.

### HasInvoiceDelivery

`func (o *CustomersApiSyncCustomersRequest) HasInvoiceDelivery() bool`

HasInvoiceDelivery returns a boolean if a field has been set.

### GetSalesTaxExemptNo

`func (o *CustomersApiSyncCustomersRequest) GetSalesTaxExemptNo() string`

GetSalesTaxExemptNo returns the SalesTaxExemptNo field if non-nil, zero value otherwise.

### GetSalesTaxExemptNoOk

`func (o *CustomersApiSyncCustomersRequest) GetSalesTaxExemptNoOk() (*string, bool)`

GetSalesTaxExemptNoOk returns a tuple with the SalesTaxExemptNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSalesTaxExemptNo

`func (o *CustomersApiSyncCustomersRequest) SetSalesTaxExemptNo(v string)`

SetSalesTaxExemptNo sets SalesTaxExemptNo field to given value.

### HasSalesTaxExemptNo

`func (o *CustomersApiSyncCustomersRequest) HasSalesTaxExemptNo() bool`

HasSalesTaxExemptNo returns a boolean if a field has been set.

### GetBillingSeparation

`func (o *CustomersApiSyncCustomersRequest) GetBillingSeparation() int32`

GetBillingSeparation returns the BillingSeparation field if non-nil, zero value otherwise.

### GetBillingSeparationOk

`func (o *CustomersApiSyncCustomersRequest) GetBillingSeparationOk() (*int32, bool)`

GetBillingSeparationOk returns a tuple with the BillingSeparation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingSeparation

`func (o *CustomersApiSyncCustomersRequest) SetBillingSeparation(v int32)`

SetBillingSeparation sets BillingSeparation field to given value.

### HasBillingSeparation

`func (o *CustomersApiSyncCustomersRequest) HasBillingSeparation() bool`

HasBillingSeparation returns a boolean if a field has been set.

### GetInvoiceLineReference

`func (o *CustomersApiSyncCustomersRequest) GetInvoiceLineReference() string`

GetInvoiceLineReference returns the InvoiceLineReference field if non-nil, zero value otherwise.

### GetInvoiceLineReferenceOk

`func (o *CustomersApiSyncCustomersRequest) GetInvoiceLineReferenceOk() (*string, bool)`

GetInvoiceLineReferenceOk returns a tuple with the InvoiceLineReference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceLineReference

`func (o *CustomersApiSyncCustomersRequest) SetInvoiceLineReference(v string)`

SetInvoiceLineReference sets InvoiceLineReference field to given value.

### HasInvoiceLineReference

`func (o *CustomersApiSyncCustomersRequest) HasInvoiceLineReference() bool`

HasInvoiceLineReference returns a boolean if a field has been set.

### GetTaxIdNo

`func (o *CustomersApiSyncCustomersRequest) GetTaxIdNo() string`

GetTaxIdNo returns the TaxIdNo field if non-nil, zero value otherwise.

### GetTaxIdNoOk

`func (o *CustomersApiSyncCustomersRequest) GetTaxIdNoOk() (*string, bool)`

GetTaxIdNoOk returns a tuple with the TaxIdNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxIdNo

`func (o *CustomersApiSyncCustomersRequest) SetTaxIdNo(v string)`

SetTaxIdNo sets TaxIdNo field to given value.

### HasTaxIdNo

`func (o *CustomersApiSyncCustomersRequest) HasTaxIdNo() bool`

HasTaxIdNo returns a boolean if a field has been set.

### GetRetroactivePricing

`func (o *CustomersApiSyncCustomersRequest) GetRetroactivePricing() bool`

GetRetroactivePricing returns the RetroactivePricing field if non-nil, zero value otherwise.

### GetRetroactivePricingOk

`func (o *CustomersApiSyncCustomersRequest) GetRetroactivePricingOk() (*bool, bool)`

GetRetroactivePricingOk returns a tuple with the RetroactivePricing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRetroactivePricing

`func (o *CustomersApiSyncCustomersRequest) SetRetroactivePricing(v bool)`

SetRetroactivePricing sets RetroactivePricing field to given value.

### HasRetroactivePricing

`func (o *CustomersApiSyncCustomersRequest) HasRetroactivePricing() bool`

HasRetroactivePricing returns a boolean if a field has been set.

### GetGovernmentIssuedTaxNo

`func (o *CustomersApiSyncCustomersRequest) GetGovernmentIssuedTaxNo() string`

GetGovernmentIssuedTaxNo returns the GovernmentIssuedTaxNo field if non-nil, zero value otherwise.

### GetGovernmentIssuedTaxNoOk

`func (o *CustomersApiSyncCustomersRequest) GetGovernmentIssuedTaxNoOk() (*string, bool)`

GetGovernmentIssuedTaxNoOk returns a tuple with the GovernmentIssuedTaxNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGovernmentIssuedTaxNo

`func (o *CustomersApiSyncCustomersRequest) SetGovernmentIssuedTaxNo(v string)`

SetGovernmentIssuedTaxNo sets GovernmentIssuedTaxNo field to given value.

### HasGovernmentIssuedTaxNo

`func (o *CustomersApiSyncCustomersRequest) HasGovernmentIssuedTaxNo() bool`

HasGovernmentIssuedTaxNo returns a boolean if a field has been set.

### GetInvoicePo

`func (o *CustomersApiSyncCustomersRequest) GetInvoicePo() string`

GetInvoicePo returns the InvoicePo field if non-nil, zero value otherwise.

### GetInvoicePoOk

`func (o *CustomersApiSyncCustomersRequest) GetInvoicePoOk() (*string, bool)`

GetInvoicePoOk returns a tuple with the InvoicePo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoicePo

`func (o *CustomersApiSyncCustomersRequest) SetInvoicePo(v string)`

SetInvoicePo sets InvoicePo field to given value.

### HasInvoicePo

`func (o *CustomersApiSyncCustomersRequest) HasInvoicePo() bool`

HasInvoicePo returns a boolean if a field has been set.

### GetQuoteTo

`func (o *CustomersApiSyncCustomersRequest) GetQuoteTo() bool`

GetQuoteTo returns the QuoteTo field if non-nil, zero value otherwise.

### GetQuoteToOk

`func (o *CustomersApiSyncCustomersRequest) GetQuoteToOk() (*bool, bool)`

GetQuoteToOk returns a tuple with the QuoteTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuoteTo

`func (o *CustomersApiSyncCustomersRequest) SetQuoteTo(v bool)`

SetQuoteTo sets QuoteTo field to given value.

### HasQuoteTo

`func (o *CustomersApiSyncCustomersRequest) HasQuoteTo() bool`

HasQuoteTo returns a boolean if a field has been set.

### GetShipTo

`func (o *CustomersApiSyncCustomersRequest) GetShipTo() bool`

GetShipTo returns the ShipTo field if non-nil, zero value otherwise.

### GetShipToOk

`func (o *CustomersApiSyncCustomersRequest) GetShipToOk() (*bool, bool)`

GetShipToOk returns a tuple with the ShipTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipTo

`func (o *CustomersApiSyncCustomersRequest) SetShipTo(v bool)`

SetShipTo sets ShipTo field to given value.

### HasShipTo

`func (o *CustomersApiSyncCustomersRequest) HasShipTo() bool`

HasShipTo returns a boolean if a field has been set.

### GetBillTo

`func (o *CustomersApiSyncCustomersRequest) GetBillTo() bool`

GetBillTo returns the BillTo field if non-nil, zero value otherwise.

### GetBillToOk

`func (o *CustomersApiSyncCustomersRequest) GetBillToOk() (*bool, bool)`

GetBillToOk returns a tuple with the BillTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillTo

`func (o *CustomersApiSyncCustomersRequest) SetBillTo(v bool)`

SetBillTo sets BillTo field to given value.

### HasBillTo

`func (o *CustomersApiSyncCustomersRequest) HasBillTo() bool`

HasBillTo returns a boolean if a field has been set.

### GetBillToAddressId

`func (o *CustomersApiSyncCustomersRequest) GetBillToAddressId() string`

GetBillToAddressId returns the BillToAddressId field if non-nil, zero value otherwise.

### GetBillToAddressIdOk

`func (o *CustomersApiSyncCustomersRequest) GetBillToAddressIdOk() (*string, bool)`

GetBillToAddressIdOk returns a tuple with the BillToAddressId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillToAddressId

`func (o *CustomersApiSyncCustomersRequest) SetBillToAddressId(v string)`

SetBillToAddressId sets BillToAddressId field to given value.

### HasBillToAddressId

`func (o *CustomersApiSyncCustomersRequest) HasBillToAddressId() bool`

HasBillToAddressId returns a boolean if a field has been set.

### GetRemitTo

`func (o *CustomersApiSyncCustomersRequest) GetRemitTo() bool`

GetRemitTo returns the RemitTo field if non-nil, zero value otherwise.

### GetRemitToOk

`func (o *CustomersApiSyncCustomersRequest) GetRemitToOk() (*bool, bool)`

GetRemitToOk returns a tuple with the RemitTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemitTo

`func (o *CustomersApiSyncCustomersRequest) SetRemitTo(v bool)`

SetRemitTo sets RemitTo field to given value.

### HasRemitTo

`func (o *CustomersApiSyncCustomersRequest) HasRemitTo() bool`

HasRemitTo returns a boolean if a field has been set.

### GetThirdPartyShipTo

`func (o *CustomersApiSyncCustomersRequest) GetThirdPartyShipTo() bool`

GetThirdPartyShipTo returns the ThirdPartyShipTo field if non-nil, zero value otherwise.

### GetThirdPartyShipToOk

`func (o *CustomersApiSyncCustomersRequest) GetThirdPartyShipToOk() (*bool, bool)`

GetThirdPartyShipToOk returns a tuple with the ThirdPartyShipTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThirdPartyShipTo

`func (o *CustomersApiSyncCustomersRequest) SetThirdPartyShipTo(v bool)`

SetThirdPartyShipTo sets ThirdPartyShipTo field to given value.

### HasThirdPartyShipTo

`func (o *CustomersApiSyncCustomersRequest) HasThirdPartyShipTo() bool`

HasThirdPartyShipTo returns a boolean if a field has been set.

### GetThirdPartyShipToAddressId

`func (o *CustomersApiSyncCustomersRequest) GetThirdPartyShipToAddressId() string`

GetThirdPartyShipToAddressId returns the ThirdPartyShipToAddressId field if non-nil, zero value otherwise.

### GetThirdPartyShipToAddressIdOk

`func (o *CustomersApiSyncCustomersRequest) GetThirdPartyShipToAddressIdOk() (*string, bool)`

GetThirdPartyShipToAddressIdOk returns a tuple with the ThirdPartyShipToAddressId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThirdPartyShipToAddressId

`func (o *CustomersApiSyncCustomersRequest) SetThirdPartyShipToAddressId(v string)`

SetThirdPartyShipToAddressId sets ThirdPartyShipToAddressId field to given value.

### HasThirdPartyShipToAddressId

`func (o *CustomersApiSyncCustomersRequest) HasThirdPartyShipToAddressId() bool`

HasThirdPartyShipToAddressId returns a boolean if a field has been set.

### GetPool

`func (o *CustomersApiSyncCustomersRequest) GetPool() bool`

GetPool returns the Pool field if non-nil, zero value otherwise.

### GetPoolOk

`func (o *CustomersApiSyncCustomersRequest) GetPoolOk() (*bool, bool)`

GetPoolOk returns a tuple with the Pool field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPool

`func (o *CustomersApiSyncCustomersRequest) SetPool(v bool)`

SetPool sets Pool field to given value.

### HasPool

`func (o *CustomersApiSyncCustomersRequest) HasPool() bool`

HasPool returns a boolean if a field has been set.

### GetPoolAddressId

`func (o *CustomersApiSyncCustomersRequest) GetPoolAddressId() string`

GetPoolAddressId returns the PoolAddressId field if non-nil, zero value otherwise.

### GetPoolAddressIdOk

`func (o *CustomersApiSyncCustomersRequest) GetPoolAddressIdOk() (*string, bool)`

GetPoolAddressIdOk returns a tuple with the PoolAddressId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoolAddressId

`func (o *CustomersApiSyncCustomersRequest) SetPoolAddressId(v string)`

SetPoolAddressId sets PoolAddressId field to given value.

### HasPoolAddressId

`func (o *CustomersApiSyncCustomersRequest) HasPoolAddressId() bool`

HasPoolAddressId returns a boolean if a field has been set.

### GetOldCustomerNo

`func (o *CustomersApiSyncCustomersRequest) GetOldCustomerNo() string`

GetOldCustomerNo returns the OldCustomerNo field if non-nil, zero value otherwise.

### GetOldCustomerNoOk

`func (o *CustomersApiSyncCustomersRequest) GetOldCustomerNoOk() (*string, bool)`

GetOldCustomerNoOk returns a tuple with the OldCustomerNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOldCustomerNo

`func (o *CustomersApiSyncCustomersRequest) SetOldCustomerNo(v string)`

SetOldCustomerNo sets OldCustomerNo field to given value.

### HasOldCustomerNo

`func (o *CustomersApiSyncCustomersRequest) HasOldCustomerNo() bool`

HasOldCustomerNo returns a boolean if a field has been set.

### GetActive

`func (o *CustomersApiSyncCustomersRequest) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *CustomersApiSyncCustomersRequest) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *CustomersApiSyncCustomersRequest) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *CustomersApiSyncCustomersRequest) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetAddress

`func (o *CustomersApiSyncCustomersRequest) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *CustomersApiSyncCustomersRequest) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *CustomersApiSyncCustomersRequest) SetAddress(v string)`

SetAddress sets Address field to given value.

### HasAddress

`func (o *CustomersApiSyncCustomersRequest) HasAddress() bool`

HasAddress returns a boolean if a field has been set.

### GetCity

`func (o *CustomersApiSyncCustomersRequest) GetCity() string`

GetCity returns the City field if non-nil, zero value otherwise.

### GetCityOk

`func (o *CustomersApiSyncCustomersRequest) GetCityOk() (*string, bool)`

GetCityOk returns a tuple with the City field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCity

`func (o *CustomersApiSyncCustomersRequest) SetCity(v string)`

SetCity sets City field to given value.

### HasCity

`func (o *CustomersApiSyncCustomersRequest) HasCity() bool`

HasCity returns a boolean if a field has been set.

### GetState

`func (o *CustomersApiSyncCustomersRequest) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *CustomersApiSyncCustomersRequest) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *CustomersApiSyncCustomersRequest) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *CustomersApiSyncCustomersRequest) HasState() bool`

HasState returns a boolean if a field has been set.

### GetZip

`func (o *CustomersApiSyncCustomersRequest) GetZip() string`

GetZip returns the Zip field if non-nil, zero value otherwise.

### GetZipOk

`func (o *CustomersApiSyncCustomersRequest) GetZipOk() (*string, bool)`

GetZipOk returns a tuple with the Zip field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetZip

`func (o *CustomersApiSyncCustomersRequest) SetZip(v string)`

SetZip sets Zip field to given value.

### HasZip

`func (o *CustomersApiSyncCustomersRequest) HasZip() bool`

HasZip returns a boolean if a field has been set.

### GetCountry

`func (o *CustomersApiSyncCustomersRequest) GetCountry() string`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *CustomersApiSyncCustomersRequest) GetCountryOk() (*string, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *CustomersApiSyncCustomersRequest) SetCountry(v string)`

SetCountry sets Country field to given value.

### HasCountry

`func (o *CustomersApiSyncCustomersRequest) HasCountry() bool`

HasCountry returns a boolean if a field has been set.

### GetCounty

`func (o *CustomersApiSyncCustomersRequest) GetCounty() string`

GetCounty returns the County field if non-nil, zero value otherwise.

### GetCountyOk

`func (o *CustomersApiSyncCustomersRequest) GetCountyOk() (*string, bool)`

GetCountyOk returns a tuple with the County field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCounty

`func (o *CustomersApiSyncCustomersRequest) SetCounty(v string)`

SetCounty sets County field to given value.

### HasCounty

`func (o *CustomersApiSyncCustomersRequest) HasCounty() bool`

HasCounty returns a boolean if a field has been set.

### GetShippingInstructions

`func (o *CustomersApiSyncCustomersRequest) GetShippingInstructions() string`

GetShippingInstructions returns the ShippingInstructions field if non-nil, zero value otherwise.

### GetShippingInstructionsOk

`func (o *CustomersApiSyncCustomersRequest) GetShippingInstructionsOk() (*string, bool)`

GetShippingInstructionsOk returns a tuple with the ShippingInstructions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingInstructions

`func (o *CustomersApiSyncCustomersRequest) SetShippingInstructions(v string)`

SetShippingInstructions sets ShippingInstructions field to given value.

### HasShippingInstructions

`func (o *CustomersApiSyncCustomersRequest) HasShippingInstructions() bool`

HasShippingInstructions returns a boolean if a field has been set.

### GetIgnoreTransitOnWeekends

`func (o *CustomersApiSyncCustomersRequest) GetIgnoreTransitOnWeekends() bool`

GetIgnoreTransitOnWeekends returns the IgnoreTransitOnWeekends field if non-nil, zero value otherwise.

### GetIgnoreTransitOnWeekendsOk

`func (o *CustomersApiSyncCustomersRequest) GetIgnoreTransitOnWeekendsOk() (*bool, bool)`

GetIgnoreTransitOnWeekendsOk returns a tuple with the IgnoreTransitOnWeekends field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIgnoreTransitOnWeekends

`func (o *CustomersApiSyncCustomersRequest) SetIgnoreTransitOnWeekends(v bool)`

SetIgnoreTransitOnWeekends sets IgnoreTransitOnWeekends field to given value.

### HasIgnoreTransitOnWeekends

`func (o *CustomersApiSyncCustomersRequest) HasIgnoreTransitOnWeekends() bool`

HasIgnoreTransitOnWeekends returns a boolean if a field has been set.

### GetTransportationLeadTime

`func (o *CustomersApiSyncCustomersRequest) GetTransportationLeadTime() int32`

GetTransportationLeadTime returns the TransportationLeadTime field if non-nil, zero value otherwise.

### GetTransportationLeadTimeOk

`func (o *CustomersApiSyncCustomersRequest) GetTransportationLeadTimeOk() (*int32, bool)`

GetTransportationLeadTimeOk returns a tuple with the TransportationLeadTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransportationLeadTime

`func (o *CustomersApiSyncCustomersRequest) SetTransportationLeadTime(v int32)`

SetTransportationLeadTime sets TransportationLeadTime field to given value.

### HasTransportationLeadTime

`func (o *CustomersApiSyncCustomersRequest) HasTransportationLeadTime() bool`

HasTransportationLeadTime returns a boolean if a field has been set.

### GetTruckType

`func (o *CustomersApiSyncCustomersRequest) GetTruckType() string`

GetTruckType returns the TruckType field if non-nil, zero value otherwise.

### GetTruckTypeOk

`func (o *CustomersApiSyncCustomersRequest) GetTruckTypeOk() (*string, bool)`

GetTruckTypeOk returns a tuple with the TruckType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckType

`func (o *CustomersApiSyncCustomersRequest) SetTruckType(v string)`

SetTruckType sets TruckType field to given value.

### HasTruckType

`func (o *CustomersApiSyncCustomersRequest) HasTruckType() bool`

HasTruckType returns a boolean if a field has been set.

### GetSalespersonId

`func (o *CustomersApiSyncCustomersRequest) GetSalespersonId() string`

GetSalespersonId returns the SalespersonId field if non-nil, zero value otherwise.

### GetSalespersonIdOk

`func (o *CustomersApiSyncCustomersRequest) GetSalespersonIdOk() (*string, bool)`

GetSalespersonIdOk returns a tuple with the SalespersonId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSalespersonId

`func (o *CustomersApiSyncCustomersRequest) SetSalespersonId(v string)`

SetSalespersonId sets SalespersonId field to given value.

### HasSalespersonId

`func (o *CustomersApiSyncCustomersRequest) HasSalespersonId() bool`

HasSalespersonId returns a boolean if a field has been set.

### GetStatementAddressId

`func (o *CustomersApiSyncCustomersRequest) GetStatementAddressId() string`

GetStatementAddressId returns the StatementAddressId field if non-nil, zero value otherwise.

### GetStatementAddressIdOk

`func (o *CustomersApiSyncCustomersRequest) GetStatementAddressIdOk() (*string, bool)`

GetStatementAddressIdOk returns a tuple with the StatementAddressId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatementAddressId

`func (o *CustomersApiSyncCustomersRequest) SetStatementAddressId(v string)`

SetStatementAddressId sets StatementAddressId field to given value.

### HasStatementAddressId

`func (o *CustomersApiSyncCustomersRequest) HasStatementAddressId() bool`

HasStatementAddressId returns a boolean if a field has been set.

### GetFreightTerms

`func (o *CustomersApiSyncCustomersRequest) GetFreightTerms() string`

GetFreightTerms returns the FreightTerms field if non-nil, zero value otherwise.

### GetFreightTermsOk

`func (o *CustomersApiSyncCustomersRequest) GetFreightTermsOk() (*string, bool)`

GetFreightTermsOk returns a tuple with the FreightTerms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFreightTerms

`func (o *CustomersApiSyncCustomersRequest) SetFreightTerms(v string)`

SetFreightTerms sets FreightTerms field to given value.

### HasFreightTerms

`func (o *CustomersApiSyncCustomersRequest) HasFreightTerms() bool`

HasFreightTerms returns a boolean if a field has been set.

### GetInsideSalespersonId

`func (o *CustomersApiSyncCustomersRequest) GetInsideSalespersonId() string`

GetInsideSalespersonId returns the InsideSalespersonId field if non-nil, zero value otherwise.

### GetInsideSalespersonIdOk

`func (o *CustomersApiSyncCustomersRequest) GetInsideSalespersonIdOk() (*string, bool)`

GetInsideSalespersonIdOk returns a tuple with the InsideSalespersonId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInsideSalespersonId

`func (o *CustomersApiSyncCustomersRequest) SetInsideSalespersonId(v string)`

SetInsideSalespersonId sets InsideSalespersonId field to given value.

### HasInsideSalespersonId

`func (o *CustomersApiSyncCustomersRequest) HasInsideSalespersonId() bool`

HasInsideSalespersonId returns a boolean if a field has been set.

### GetDefaultShipFrom

`func (o *CustomersApiSyncCustomersRequest) GetDefaultShipFrom() string`

GetDefaultShipFrom returns the DefaultShipFrom field if non-nil, zero value otherwise.

### GetDefaultShipFromOk

`func (o *CustomersApiSyncCustomersRequest) GetDefaultShipFromOk() (*string, bool)`

GetDefaultShipFromOk returns a tuple with the DefaultShipFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultShipFrom

`func (o *CustomersApiSyncCustomersRequest) SetDefaultShipFrom(v string)`

SetDefaultShipFrom sets DefaultShipFrom field to given value.

### HasDefaultShipFrom

`func (o *CustomersApiSyncCustomersRequest) HasDefaultShipFrom() bool`

HasDefaultShipFrom returns a boolean if a field has been set.

### GetFreightBillTo

`func (o *CustomersApiSyncCustomersRequest) GetFreightBillTo() bool`

GetFreightBillTo returns the FreightBillTo field if non-nil, zero value otherwise.

### GetFreightBillToOk

`func (o *CustomersApiSyncCustomersRequest) GetFreightBillToOk() (*bool, bool)`

GetFreightBillToOk returns a tuple with the FreightBillTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFreightBillTo

`func (o *CustomersApiSyncCustomersRequest) SetFreightBillTo(v bool)`

SetFreightBillTo sets FreightBillTo field to given value.

### HasFreightBillTo

`func (o *CustomersApiSyncCustomersRequest) HasFreightBillTo() bool`

HasFreightBillTo returns a boolean if a field has been set.

### GetFreightBillToAddressId

`func (o *CustomersApiSyncCustomersRequest) GetFreightBillToAddressId() string`

GetFreightBillToAddressId returns the FreightBillToAddressId field if non-nil, zero value otherwise.

### GetFreightBillToAddressIdOk

`func (o *CustomersApiSyncCustomersRequest) GetFreightBillToAddressIdOk() (*string, bool)`

GetFreightBillToAddressIdOk returns a tuple with the FreightBillToAddressId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFreightBillToAddressId

`func (o *CustomersApiSyncCustomersRequest) SetFreightBillToAddressId(v string)`

SetFreightBillToAddressId sets FreightBillToAddressId field to given value.

### HasFreightBillToAddressId

`func (o *CustomersApiSyncCustomersRequest) HasFreightBillToAddressId() bool`

HasFreightBillToAddressId returns a boolean if a field has been set.

### GetSoldTo

`func (o *CustomersApiSyncCustomersRequest) GetSoldTo() bool`

GetSoldTo returns the SoldTo field if non-nil, zero value otherwise.

### GetSoldToOk

`func (o *CustomersApiSyncCustomersRequest) GetSoldToOk() (*bool, bool)`

GetSoldToOk returns a tuple with the SoldTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSoldTo

`func (o *CustomersApiSyncCustomersRequest) SetSoldTo(v bool)`

SetSoldTo sets SoldTo field to given value.

### HasSoldTo

`func (o *CustomersApiSyncCustomersRequest) HasSoldTo() bool`

HasSoldTo returns a boolean if a field has been set.

### GetDunsNo

`func (o *CustomersApiSyncCustomersRequest) GetDunsNo() string`

GetDunsNo returns the DunsNo field if non-nil, zero value otherwise.

### GetDunsNoOk

`func (o *CustomersApiSyncCustomersRequest) GetDunsNoOk() (*string, bool)`

GetDunsNoOk returns a tuple with the DunsNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDunsNo

`func (o *CustomersApiSyncCustomersRequest) SetDunsNo(v string)`

SetDunsNo sets DunsNo field to given value.

### HasDunsNo

`func (o *CustomersApiSyncCustomersRequest) HasDunsNo() bool`

HasDunsNo returns a boolean if a field has been set.

### GetCommercialInvoiceVatNo

`func (o *CustomersApiSyncCustomersRequest) GetCommercialInvoiceVatNo() string`

GetCommercialInvoiceVatNo returns the CommercialInvoiceVatNo field if non-nil, zero value otherwise.

### GetCommercialInvoiceVatNoOk

`func (o *CustomersApiSyncCustomersRequest) GetCommercialInvoiceVatNoOk() (*string, bool)`

GetCommercialInvoiceVatNoOk returns a tuple with the CommercialInvoiceVatNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCommercialInvoiceVatNo

`func (o *CustomersApiSyncCustomersRequest) SetCommercialInvoiceVatNo(v string)`

SetCommercialInvoiceVatNo sets CommercialInvoiceVatNo field to given value.

### HasCommercialInvoiceVatNo

`func (o *CustomersApiSyncCustomersRequest) HasCommercialInvoiceVatNo() bool`

HasCommercialInvoiceVatNo returns a boolean if a field has been set.

### GetTemplate

`func (o *CustomersApiSyncCustomersRequest) GetTemplate() bool`

GetTemplate returns the Template field if non-nil, zero value otherwise.

### GetTemplateOk

`func (o *CustomersApiSyncCustomersRequest) GetTemplateOk() (*bool, bool)`

GetTemplateOk returns a tuple with the Template field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemplate

`func (o *CustomersApiSyncCustomersRequest) SetTemplate(v bool)`

SetTemplate sets Template field to given value.

### HasTemplate

`func (o *CustomersApiSyncCustomersRequest) HasTemplate() bool`

HasTemplate returns a boolean if a field has been set.

### GetIncoTerms

`func (o *CustomersApiSyncCustomersRequest) GetIncoTerms() string`

GetIncoTerms returns the IncoTerms field if non-nil, zero value otherwise.

### GetIncoTermsOk

`func (o *CustomersApiSyncCustomersRequest) GetIncoTermsOk() (*string, bool)`

GetIncoTermsOk returns a tuple with the IncoTerms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncoTerms

`func (o *CustomersApiSyncCustomersRequest) SetIncoTerms(v string)`

SetIncoTerms sets IncoTerms field to given value.

### HasIncoTerms

`func (o *CustomersApiSyncCustomersRequest) HasIncoTerms() bool`

HasIncoTerms returns a boolean if a field has been set.

### GetNegotiatedPlace

`func (o *CustomersApiSyncCustomersRequest) GetNegotiatedPlace() string`

GetNegotiatedPlace returns the NegotiatedPlace field if non-nil, zero value otherwise.

### GetNegotiatedPlaceOk

`func (o *CustomersApiSyncCustomersRequest) GetNegotiatedPlaceOk() (*string, bool)`

GetNegotiatedPlaceOk returns a tuple with the NegotiatedPlace field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNegotiatedPlace

`func (o *CustomersApiSyncCustomersRequest) SetNegotiatedPlace(v string)`

SetNegotiatedPlace sets NegotiatedPlace field to given value.

### HasNegotiatedPlace

`func (o *CustomersApiSyncCustomersRequest) HasNegotiatedPlace() bool`

HasNegotiatedPlace returns a boolean if a field has been set.

### GetBackOrder

`func (o *CustomersApiSyncCustomersRequest) GetBackOrder() string`

GetBackOrder returns the BackOrder field if non-nil, zero value otherwise.

### GetBackOrderOk

`func (o *CustomersApiSyncCustomersRequest) GetBackOrderOk() (*string, bool)`

GetBackOrderOk returns a tuple with the BackOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBackOrder

`func (o *CustomersApiSyncCustomersRequest) SetBackOrder(v string)`

SetBackOrder sets BackOrder field to given value.

### HasBackOrder

`func (o *CustomersApiSyncCustomersRequest) HasBackOrder() bool`

HasBackOrder returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


