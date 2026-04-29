# CustomersApiDeleteCustomerAddressResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | A unique identifier for the Customer.  This will be automatically generated if omitted from the request. | [optional] 
**Code** | Pointer to **string** | A short name for a customer. | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Status** | Pointer to **string** | Setup Table: Customer Status | [optional] 
**Type** | Pointer to **string** | Setup Table: Customer Type | [optional] 
**Note** | Pointer to **string** |  | [optional] 
**SupplierCode** | Pointer to **string** |  | [optional] 
**OtherCustomerCode** | Pointer to **string** |  | [optional] 
**Rating** | Pointer to **string** | Setup Table: Customer Rating | [optional] 
**Industries** | Pointer to **[]string** | Setup Table: Industries | [optional] 
**DefaultCarrierIds** | Pointer to **[]string** | A carrier is a Supplier Resource with a Supplier Type of Carrier. | [optional] 
**Region** | Pointer to **string** | Screen List: Region List | [optional] 
**BusinessType** | Pointer to **string** | Setup Table: Business Type | [optional] 
**Category** | Pointer to **string** | Setup Table: Customer Category | [optional] 
**Class** | Pointer to **string** | Setup Table: Customer Class | [optional] 
**Catalog** | Pointer to **string** | Screen: Catalogs | [optional] 
**AssignedToId** | Pointer to **string** | The sales person assigned to this customer, by IAM Account ID. | [optional] 
**AssignedTo2Id** | Pointer to **string** | The sales person assigned to this customer, by IAM Account ID. | [optional] 
**AssignedTo3Id** | Pointer to **string** | The sales person assigned to this customer, by IAM Account ID. | [optional] 
**AssignedToGroup** | Pointer to **string** |  | [optional] 
**ContactResourceId** | Pointer to **string** | The  Contact_Id of the sales person assigned to this Customer. | [optional] 
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
**CreatedById** | Pointer to **string** | IAM Account Id | [optional] 
**CreatedDate** | Pointer to **time.Time** |  | [optional] 
**ModifiedById** | Pointer to **string** | IAM Account Id | [optional] 
**ModifiedDate** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewCustomersApiDeleteCustomerAddressResponse

`func NewCustomersApiDeleteCustomerAddressResponse() *CustomersApiDeleteCustomerAddressResponse`

NewCustomersApiDeleteCustomerAddressResponse instantiates a new CustomersApiDeleteCustomerAddressResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomersApiDeleteCustomerAddressResponseWithDefaults

`func NewCustomersApiDeleteCustomerAddressResponseWithDefaults() *CustomersApiDeleteCustomerAddressResponse`

NewCustomersApiDeleteCustomerAddressResponseWithDefaults instantiates a new CustomersApiDeleteCustomerAddressResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CustomersApiDeleteCustomerAddressResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CustomersApiDeleteCustomerAddressResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CustomersApiDeleteCustomerAddressResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *CustomersApiDeleteCustomerAddressResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCode

`func (o *CustomersApiDeleteCustomerAddressResponse) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *CustomersApiDeleteCustomerAddressResponse) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *CustomersApiDeleteCustomerAddressResponse) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *CustomersApiDeleteCustomerAddressResponse) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetName

`func (o *CustomersApiDeleteCustomerAddressResponse) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CustomersApiDeleteCustomerAddressResponse) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CustomersApiDeleteCustomerAddressResponse) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *CustomersApiDeleteCustomerAddressResponse) HasName() bool`

HasName returns a boolean if a field has been set.

### GetStatus

`func (o *CustomersApiDeleteCustomerAddressResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CustomersApiDeleteCustomerAddressResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CustomersApiDeleteCustomerAddressResponse) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *CustomersApiDeleteCustomerAddressResponse) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetType

`func (o *CustomersApiDeleteCustomerAddressResponse) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *CustomersApiDeleteCustomerAddressResponse) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *CustomersApiDeleteCustomerAddressResponse) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *CustomersApiDeleteCustomerAddressResponse) HasType() bool`

HasType returns a boolean if a field has been set.

### GetNote

`func (o *CustomersApiDeleteCustomerAddressResponse) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *CustomersApiDeleteCustomerAddressResponse) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *CustomersApiDeleteCustomerAddressResponse) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *CustomersApiDeleteCustomerAddressResponse) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetSupplierCode

`func (o *CustomersApiDeleteCustomerAddressResponse) GetSupplierCode() string`

GetSupplierCode returns the SupplierCode field if non-nil, zero value otherwise.

### GetSupplierCodeOk

`func (o *CustomersApiDeleteCustomerAddressResponse) GetSupplierCodeOk() (*string, bool)`

GetSupplierCodeOk returns a tuple with the SupplierCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierCode

`func (o *CustomersApiDeleteCustomerAddressResponse) SetSupplierCode(v string)`

SetSupplierCode sets SupplierCode field to given value.

### HasSupplierCode

`func (o *CustomersApiDeleteCustomerAddressResponse) HasSupplierCode() bool`

HasSupplierCode returns a boolean if a field has been set.

### GetOtherCustomerCode

`func (o *CustomersApiDeleteCustomerAddressResponse) GetOtherCustomerCode() string`

GetOtherCustomerCode returns the OtherCustomerCode field if non-nil, zero value otherwise.

### GetOtherCustomerCodeOk

`func (o *CustomersApiDeleteCustomerAddressResponse) GetOtherCustomerCodeOk() (*string, bool)`

GetOtherCustomerCodeOk returns a tuple with the OtherCustomerCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOtherCustomerCode

`func (o *CustomersApiDeleteCustomerAddressResponse) SetOtherCustomerCode(v string)`

SetOtherCustomerCode sets OtherCustomerCode field to given value.

### HasOtherCustomerCode

`func (o *CustomersApiDeleteCustomerAddressResponse) HasOtherCustomerCode() bool`

HasOtherCustomerCode returns a boolean if a field has been set.

### GetRating

`func (o *CustomersApiDeleteCustomerAddressResponse) GetRating() string`

GetRating returns the Rating field if non-nil, zero value otherwise.

### GetRatingOk

`func (o *CustomersApiDeleteCustomerAddressResponse) GetRatingOk() (*string, bool)`

GetRatingOk returns a tuple with the Rating field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRating

`func (o *CustomersApiDeleteCustomerAddressResponse) SetRating(v string)`

SetRating sets Rating field to given value.

### HasRating

`func (o *CustomersApiDeleteCustomerAddressResponse) HasRating() bool`

HasRating returns a boolean if a field has been set.

### GetIndustries

`func (o *CustomersApiDeleteCustomerAddressResponse) GetIndustries() []string`

GetIndustries returns the Industries field if non-nil, zero value otherwise.

### GetIndustriesOk

`func (o *CustomersApiDeleteCustomerAddressResponse) GetIndustriesOk() (*[]string, bool)`

GetIndustriesOk returns a tuple with the Industries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIndustries

`func (o *CustomersApiDeleteCustomerAddressResponse) SetIndustries(v []string)`

SetIndustries sets Industries field to given value.

### HasIndustries

`func (o *CustomersApiDeleteCustomerAddressResponse) HasIndustries() bool`

HasIndustries returns a boolean if a field has been set.

### GetDefaultCarrierIds

`func (o *CustomersApiDeleteCustomerAddressResponse) GetDefaultCarrierIds() []string`

GetDefaultCarrierIds returns the DefaultCarrierIds field if non-nil, zero value otherwise.

### GetDefaultCarrierIdsOk

`func (o *CustomersApiDeleteCustomerAddressResponse) GetDefaultCarrierIdsOk() (*[]string, bool)`

GetDefaultCarrierIdsOk returns a tuple with the DefaultCarrierIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultCarrierIds

`func (o *CustomersApiDeleteCustomerAddressResponse) SetDefaultCarrierIds(v []string)`

SetDefaultCarrierIds sets DefaultCarrierIds field to given value.

### HasDefaultCarrierIds

`func (o *CustomersApiDeleteCustomerAddressResponse) HasDefaultCarrierIds() bool`

HasDefaultCarrierIds returns a boolean if a field has been set.

### GetRegion

`func (o *CustomersApiDeleteCustomerAddressResponse) GetRegion() string`

GetRegion returns the Region field if non-nil, zero value otherwise.

### GetRegionOk

`func (o *CustomersApiDeleteCustomerAddressResponse) GetRegionOk() (*string, bool)`

GetRegionOk returns a tuple with the Region field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegion

`func (o *CustomersApiDeleteCustomerAddressResponse) SetRegion(v string)`

SetRegion sets Region field to given value.

### HasRegion

`func (o *CustomersApiDeleteCustomerAddressResponse) HasRegion() bool`

HasRegion returns a boolean if a field has been set.

### GetBusinessType

`func (o *CustomersApiDeleteCustomerAddressResponse) GetBusinessType() string`

GetBusinessType returns the BusinessType field if non-nil, zero value otherwise.

### GetBusinessTypeOk

`func (o *CustomersApiDeleteCustomerAddressResponse) GetBusinessTypeOk() (*string, bool)`

GetBusinessTypeOk returns a tuple with the BusinessType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusinessType

`func (o *CustomersApiDeleteCustomerAddressResponse) SetBusinessType(v string)`

SetBusinessType sets BusinessType field to given value.

### HasBusinessType

`func (o *CustomersApiDeleteCustomerAddressResponse) HasBusinessType() bool`

HasBusinessType returns a boolean if a field has been set.

### GetCategory

`func (o *CustomersApiDeleteCustomerAddressResponse) GetCategory() string`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *CustomersApiDeleteCustomerAddressResponse) GetCategoryOk() (*string, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *CustomersApiDeleteCustomerAddressResponse) SetCategory(v string)`

SetCategory sets Category field to given value.

### HasCategory

`func (o *CustomersApiDeleteCustomerAddressResponse) HasCategory() bool`

HasCategory returns a boolean if a field has been set.

### GetClass

`func (o *CustomersApiDeleteCustomerAddressResponse) GetClass() string`

GetClass returns the Class field if non-nil, zero value otherwise.

### GetClassOk

`func (o *CustomersApiDeleteCustomerAddressResponse) GetClassOk() (*string, bool)`

GetClassOk returns a tuple with the Class field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClass

`func (o *CustomersApiDeleteCustomerAddressResponse) SetClass(v string)`

SetClass sets Class field to given value.

### HasClass

`func (o *CustomersApiDeleteCustomerAddressResponse) HasClass() bool`

HasClass returns a boolean if a field has been set.

### GetCatalog

`func (o *CustomersApiDeleteCustomerAddressResponse) GetCatalog() string`

GetCatalog returns the Catalog field if non-nil, zero value otherwise.

### GetCatalogOk

`func (o *CustomersApiDeleteCustomerAddressResponse) GetCatalogOk() (*string, bool)`

GetCatalogOk returns a tuple with the Catalog field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCatalog

`func (o *CustomersApiDeleteCustomerAddressResponse) SetCatalog(v string)`

SetCatalog sets Catalog field to given value.

### HasCatalog

`func (o *CustomersApiDeleteCustomerAddressResponse) HasCatalog() bool`

HasCatalog returns a boolean if a field has been set.

### GetAssignedToId

`func (o *CustomersApiDeleteCustomerAddressResponse) GetAssignedToId() string`

GetAssignedToId returns the AssignedToId field if non-nil, zero value otherwise.

### GetAssignedToIdOk

`func (o *CustomersApiDeleteCustomerAddressResponse) GetAssignedToIdOk() (*string, bool)`

GetAssignedToIdOk returns a tuple with the AssignedToId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignedToId

`func (o *CustomersApiDeleteCustomerAddressResponse) SetAssignedToId(v string)`

SetAssignedToId sets AssignedToId field to given value.

### HasAssignedToId

`func (o *CustomersApiDeleteCustomerAddressResponse) HasAssignedToId() bool`

HasAssignedToId returns a boolean if a field has been set.

### GetAssignedTo2Id

`func (o *CustomersApiDeleteCustomerAddressResponse) GetAssignedTo2Id() string`

GetAssignedTo2Id returns the AssignedTo2Id field if non-nil, zero value otherwise.

### GetAssignedTo2IdOk

`func (o *CustomersApiDeleteCustomerAddressResponse) GetAssignedTo2IdOk() (*string, bool)`

GetAssignedTo2IdOk returns a tuple with the AssignedTo2Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignedTo2Id

`func (o *CustomersApiDeleteCustomerAddressResponse) SetAssignedTo2Id(v string)`

SetAssignedTo2Id sets AssignedTo2Id field to given value.

### HasAssignedTo2Id

`func (o *CustomersApiDeleteCustomerAddressResponse) HasAssignedTo2Id() bool`

HasAssignedTo2Id returns a boolean if a field has been set.

### GetAssignedTo3Id

`func (o *CustomersApiDeleteCustomerAddressResponse) GetAssignedTo3Id() string`

GetAssignedTo3Id returns the AssignedTo3Id field if non-nil, zero value otherwise.

### GetAssignedTo3IdOk

`func (o *CustomersApiDeleteCustomerAddressResponse) GetAssignedTo3IdOk() (*string, bool)`

GetAssignedTo3IdOk returns a tuple with the AssignedTo3Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignedTo3Id

`func (o *CustomersApiDeleteCustomerAddressResponse) SetAssignedTo3Id(v string)`

SetAssignedTo3Id sets AssignedTo3Id field to given value.

### HasAssignedTo3Id

`func (o *CustomersApiDeleteCustomerAddressResponse) HasAssignedTo3Id() bool`

HasAssignedTo3Id returns a boolean if a field has been set.

### GetAssignedToGroup

`func (o *CustomersApiDeleteCustomerAddressResponse) GetAssignedToGroup() string`

GetAssignedToGroup returns the AssignedToGroup field if non-nil, zero value otherwise.

### GetAssignedToGroupOk

`func (o *CustomersApiDeleteCustomerAddressResponse) GetAssignedToGroupOk() (*string, bool)`

GetAssignedToGroupOk returns a tuple with the AssignedToGroup field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignedToGroup

`func (o *CustomersApiDeleteCustomerAddressResponse) SetAssignedToGroup(v string)`

SetAssignedToGroup sets AssignedToGroup field to given value.

### HasAssignedToGroup

`func (o *CustomersApiDeleteCustomerAddressResponse) HasAssignedToGroup() bool`

HasAssignedToGroup returns a boolean if a field has been set.

### GetContactResourceId

`func (o *CustomersApiDeleteCustomerAddressResponse) GetContactResourceId() string`

GetContactResourceId returns the ContactResourceId field if non-nil, zero value otherwise.

### GetContactResourceIdOk

`func (o *CustomersApiDeleteCustomerAddressResponse) GetContactResourceIdOk() (*string, bool)`

GetContactResourceIdOk returns a tuple with the ContactResourceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactResourceId

`func (o *CustomersApiDeleteCustomerAddressResponse) SetContactResourceId(v string)`

SetContactResourceId sets ContactResourceId field to given value.

### HasContactResourceId

`func (o *CustomersApiDeleteCustomerAddressResponse) HasContactResourceId() bool`

HasContactResourceId returns a boolean if a field has been set.

### GetAnnualSalesMillions

`func (o *CustomersApiDeleteCustomerAddressResponse) GetAnnualSalesMillions() float64`

GetAnnualSalesMillions returns the AnnualSalesMillions field if non-nil, zero value otherwise.

### GetAnnualSalesMillionsOk

`func (o *CustomersApiDeleteCustomerAddressResponse) GetAnnualSalesMillionsOk() (*float64, bool)`

GetAnnualSalesMillionsOk returns a tuple with the AnnualSalesMillions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnnualSalesMillions

`func (o *CustomersApiDeleteCustomerAddressResponse) SetAnnualSalesMillions(v float64)`

SetAnnualSalesMillions sets AnnualSalesMillions field to given value.

### HasAnnualSalesMillions

`func (o *CustomersApiDeleteCustomerAddressResponse) HasAnnualSalesMillions() bool`

HasAnnualSalesMillions returns a boolean if a field has been set.

### GetEstimatedEmployees

`func (o *CustomersApiDeleteCustomerAddressResponse) GetEstimatedEmployees() string`

GetEstimatedEmployees returns the EstimatedEmployees field if non-nil, zero value otherwise.

### GetEstimatedEmployeesOk

`func (o *CustomersApiDeleteCustomerAddressResponse) GetEstimatedEmployeesOk() (*string, bool)`

GetEstimatedEmployeesOk returns a tuple with the EstimatedEmployees field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEstimatedEmployees

`func (o *CustomersApiDeleteCustomerAddressResponse) SetEstimatedEmployees(v string)`

SetEstimatedEmployees sets EstimatedEmployees field to given value.

### HasEstimatedEmployees

`func (o *CustomersApiDeleteCustomerAddressResponse) HasEstimatedEmployees() bool`

HasEstimatedEmployees returns a boolean if a field has been set.

### GetPhone

`func (o *CustomersApiDeleteCustomerAddressResponse) GetPhone() string`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *CustomersApiDeleteCustomerAddressResponse) GetPhoneOk() (*string, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *CustomersApiDeleteCustomerAddressResponse) SetPhone(v string)`

SetPhone sets Phone field to given value.

### HasPhone

`func (o *CustomersApiDeleteCustomerAddressResponse) HasPhone() bool`

HasPhone returns a boolean if a field has been set.

### GetFax

`func (o *CustomersApiDeleteCustomerAddressResponse) GetFax() string`

GetFax returns the Fax field if non-nil, zero value otherwise.

### GetFaxOk

`func (o *CustomersApiDeleteCustomerAddressResponse) GetFaxOk() (*string, bool)`

GetFaxOk returns a tuple with the Fax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFax

`func (o *CustomersApiDeleteCustomerAddressResponse) SetFax(v string)`

SetFax sets Fax field to given value.

### HasFax

`func (o *CustomersApiDeleteCustomerAddressResponse) HasFax() bool`

HasFax returns a boolean if a field has been set.

### GetEmail

`func (o *CustomersApiDeleteCustomerAddressResponse) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *CustomersApiDeleteCustomerAddressResponse) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *CustomersApiDeleteCustomerAddressResponse) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *CustomersApiDeleteCustomerAddressResponse) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetTrackingNoOnWeighScaleRequired

`func (o *CustomersApiDeleteCustomerAddressResponse) GetTrackingNoOnWeighScaleRequired() bool`

GetTrackingNoOnWeighScaleRequired returns the TrackingNoOnWeighScaleRequired field if non-nil, zero value otherwise.

### GetTrackingNoOnWeighScaleRequiredOk

`func (o *CustomersApiDeleteCustomerAddressResponse) GetTrackingNoOnWeighScaleRequiredOk() (*bool, bool)`

GetTrackingNoOnWeighScaleRequiredOk returns a tuple with the TrackingNoOnWeighScaleRequired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackingNoOnWeighScaleRequired

`func (o *CustomersApiDeleteCustomerAddressResponse) SetTrackingNoOnWeighScaleRequired(v bool)`

SetTrackingNoOnWeighScaleRequired sets TrackingNoOnWeighScaleRequired field to given value.

### HasTrackingNoOnWeighScaleRequired

`func (o *CustomersApiDeleteCustomerAddressResponse) HasTrackingNoOnWeighScaleRequired() bool`

HasTrackingNoOnWeighScaleRequired returns a boolean if a field has been set.

### GetMultipleOrdersPerShipper

`func (o *CustomersApiDeleteCustomerAddressResponse) GetMultipleOrdersPerShipper() bool`

GetMultipleOrdersPerShipper returns the MultipleOrdersPerShipper field if non-nil, zero value otherwise.

### GetMultipleOrdersPerShipperOk

`func (o *CustomersApiDeleteCustomerAddressResponse) GetMultipleOrdersPerShipperOk() (*bool, bool)`

GetMultipleOrdersPerShipperOk returns a tuple with the MultipleOrdersPerShipper field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMultipleOrdersPerShipper

`func (o *CustomersApiDeleteCustomerAddressResponse) SetMultipleOrdersPerShipper(v bool)`

SetMultipleOrdersPerShipper sets MultipleOrdersPerShipper field to given value.

### HasMultipleOrdersPerShipper

`func (o *CustomersApiDeleteCustomerAddressResponse) HasMultipleOrdersPerShipper() bool`

HasMultipleOrdersPerShipper returns a boolean if a field has been set.

### GetEstimatedAnnualSales

`func (o *CustomersApiDeleteCustomerAddressResponse) GetEstimatedAnnualSales() string`

GetEstimatedAnnualSales returns the EstimatedAnnualSales field if non-nil, zero value otherwise.

### GetEstimatedAnnualSalesOk

`func (o *CustomersApiDeleteCustomerAddressResponse) GetEstimatedAnnualSalesOk() (*string, bool)`

GetEstimatedAnnualSalesOk returns a tuple with the EstimatedAnnualSales field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEstimatedAnnualSales

`func (o *CustomersApiDeleteCustomerAddressResponse) SetEstimatedAnnualSales(v string)`

SetEstimatedAnnualSales sets EstimatedAnnualSales field to given value.

### HasEstimatedAnnualSales

`func (o *CustomersApiDeleteCustomerAddressResponse) HasEstimatedAnnualSales() bool`

HasEstimatedAnnualSales returns a boolean if a field has been set.

### GetNewShipperPerReleaseNo

`func (o *CustomersApiDeleteCustomerAddressResponse) GetNewShipperPerReleaseNo() bool`

GetNewShipperPerReleaseNo returns the NewShipperPerReleaseNo field if non-nil, zero value otherwise.

### GetNewShipperPerReleaseNoOk

`func (o *CustomersApiDeleteCustomerAddressResponse) GetNewShipperPerReleaseNoOk() (*bool, bool)`

GetNewShipperPerReleaseNoOk returns a tuple with the NewShipperPerReleaseNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNewShipperPerReleaseNo

`func (o *CustomersApiDeleteCustomerAddressResponse) SetNewShipperPerReleaseNo(v bool)`

SetNewShipperPerReleaseNo sets NewShipperPerReleaseNo field to given value.

### HasNewShipperPerReleaseNo

`func (o *CustomersApiDeleteCustomerAddressResponse) HasNewShipperPerReleaseNo() bool`

HasNewShipperPerReleaseNo returns a boolean if a field has been set.

### GetDefaultBackOrder

`func (o *CustomersApiDeleteCustomerAddressResponse) GetDefaultBackOrder() string`

GetDefaultBackOrder returns the DefaultBackOrder field if non-nil, zero value otherwise.

### GetDefaultBackOrderOk

`func (o *CustomersApiDeleteCustomerAddressResponse) GetDefaultBackOrderOk() (*string, bool)`

GetDefaultBackOrderOk returns a tuple with the DefaultBackOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultBackOrder

`func (o *CustomersApiDeleteCustomerAddressResponse) SetDefaultBackOrder(v string)`

SetDefaultBackOrder sets DefaultBackOrder field to given value.

### HasDefaultBackOrder

`func (o *CustomersApiDeleteCustomerAddressResponse) HasDefaultBackOrder() bool`

HasDefaultBackOrder returns a boolean if a field has been set.

### GetCreatedById

`func (o *CustomersApiDeleteCustomerAddressResponse) GetCreatedById() string`

GetCreatedById returns the CreatedById field if non-nil, zero value otherwise.

### GetCreatedByIdOk

`func (o *CustomersApiDeleteCustomerAddressResponse) GetCreatedByIdOk() (*string, bool)`

GetCreatedByIdOk returns a tuple with the CreatedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedById

`func (o *CustomersApiDeleteCustomerAddressResponse) SetCreatedById(v string)`

SetCreatedById sets CreatedById field to given value.

### HasCreatedById

`func (o *CustomersApiDeleteCustomerAddressResponse) HasCreatedById() bool`

HasCreatedById returns a boolean if a field has been set.

### GetCreatedDate

`func (o *CustomersApiDeleteCustomerAddressResponse) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *CustomersApiDeleteCustomerAddressResponse) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *CustomersApiDeleteCustomerAddressResponse) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *CustomersApiDeleteCustomerAddressResponse) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.

### GetModifiedById

`func (o *CustomersApiDeleteCustomerAddressResponse) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *CustomersApiDeleteCustomerAddressResponse) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *CustomersApiDeleteCustomerAddressResponse) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *CustomersApiDeleteCustomerAddressResponse) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetModifiedDate

`func (o *CustomersApiDeleteCustomerAddressResponse) GetModifiedDate() time.Time`

GetModifiedDate returns the ModifiedDate field if non-nil, zero value otherwise.

### GetModifiedDateOk

`func (o *CustomersApiDeleteCustomerAddressResponse) GetModifiedDateOk() (*time.Time, bool)`

GetModifiedDateOk returns a tuple with the ModifiedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDate

`func (o *CustomersApiDeleteCustomerAddressResponse) SetModifiedDate(v time.Time)`

SetModifiedDate sets ModifiedDate field to given value.

### HasModifiedDate

`func (o *CustomersApiDeleteCustomerAddressResponse) HasModifiedDate() bool`

HasModifiedDate returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


