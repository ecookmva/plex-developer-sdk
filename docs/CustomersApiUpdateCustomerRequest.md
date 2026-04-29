# CustomersApiUpdateCustomerRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
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
**Region** | Pointer to **string** | Screen: Region List | [optional] 
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

## Methods

### NewCustomersApiUpdateCustomerRequest

`func NewCustomersApiUpdateCustomerRequest() *CustomersApiUpdateCustomerRequest`

NewCustomersApiUpdateCustomerRequest instantiates a new CustomersApiUpdateCustomerRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomersApiUpdateCustomerRequestWithDefaults

`func NewCustomersApiUpdateCustomerRequestWithDefaults() *CustomersApiUpdateCustomerRequest`

NewCustomersApiUpdateCustomerRequestWithDefaults instantiates a new CustomersApiUpdateCustomerRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCode

`func (o *CustomersApiUpdateCustomerRequest) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *CustomersApiUpdateCustomerRequest) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *CustomersApiUpdateCustomerRequest) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *CustomersApiUpdateCustomerRequest) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetName

`func (o *CustomersApiUpdateCustomerRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CustomersApiUpdateCustomerRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CustomersApiUpdateCustomerRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *CustomersApiUpdateCustomerRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### GetStatus

`func (o *CustomersApiUpdateCustomerRequest) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CustomersApiUpdateCustomerRequest) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CustomersApiUpdateCustomerRequest) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *CustomersApiUpdateCustomerRequest) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetType

`func (o *CustomersApiUpdateCustomerRequest) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *CustomersApiUpdateCustomerRequest) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *CustomersApiUpdateCustomerRequest) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *CustomersApiUpdateCustomerRequest) HasType() bool`

HasType returns a boolean if a field has been set.

### GetNote

`func (o *CustomersApiUpdateCustomerRequest) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *CustomersApiUpdateCustomerRequest) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *CustomersApiUpdateCustomerRequest) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *CustomersApiUpdateCustomerRequest) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetSupplierCode

`func (o *CustomersApiUpdateCustomerRequest) GetSupplierCode() string`

GetSupplierCode returns the SupplierCode field if non-nil, zero value otherwise.

### GetSupplierCodeOk

`func (o *CustomersApiUpdateCustomerRequest) GetSupplierCodeOk() (*string, bool)`

GetSupplierCodeOk returns a tuple with the SupplierCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierCode

`func (o *CustomersApiUpdateCustomerRequest) SetSupplierCode(v string)`

SetSupplierCode sets SupplierCode field to given value.

### HasSupplierCode

`func (o *CustomersApiUpdateCustomerRequest) HasSupplierCode() bool`

HasSupplierCode returns a boolean if a field has been set.

### GetOtherCustomerCode

`func (o *CustomersApiUpdateCustomerRequest) GetOtherCustomerCode() string`

GetOtherCustomerCode returns the OtherCustomerCode field if non-nil, zero value otherwise.

### GetOtherCustomerCodeOk

`func (o *CustomersApiUpdateCustomerRequest) GetOtherCustomerCodeOk() (*string, bool)`

GetOtherCustomerCodeOk returns a tuple with the OtherCustomerCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOtherCustomerCode

`func (o *CustomersApiUpdateCustomerRequest) SetOtherCustomerCode(v string)`

SetOtherCustomerCode sets OtherCustomerCode field to given value.

### HasOtherCustomerCode

`func (o *CustomersApiUpdateCustomerRequest) HasOtherCustomerCode() bool`

HasOtherCustomerCode returns a boolean if a field has been set.

### GetRating

`func (o *CustomersApiUpdateCustomerRequest) GetRating() string`

GetRating returns the Rating field if non-nil, zero value otherwise.

### GetRatingOk

`func (o *CustomersApiUpdateCustomerRequest) GetRatingOk() (*string, bool)`

GetRatingOk returns a tuple with the Rating field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRating

`func (o *CustomersApiUpdateCustomerRequest) SetRating(v string)`

SetRating sets Rating field to given value.

### HasRating

`func (o *CustomersApiUpdateCustomerRequest) HasRating() bool`

HasRating returns a boolean if a field has been set.

### GetIndustries

`func (o *CustomersApiUpdateCustomerRequest) GetIndustries() []string`

GetIndustries returns the Industries field if non-nil, zero value otherwise.

### GetIndustriesOk

`func (o *CustomersApiUpdateCustomerRequest) GetIndustriesOk() (*[]string, bool)`

GetIndustriesOk returns a tuple with the Industries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIndustries

`func (o *CustomersApiUpdateCustomerRequest) SetIndustries(v []string)`

SetIndustries sets Industries field to given value.

### HasIndustries

`func (o *CustomersApiUpdateCustomerRequest) HasIndustries() bool`

HasIndustries returns a boolean if a field has been set.

### GetDefaultCarrierIds

`func (o *CustomersApiUpdateCustomerRequest) GetDefaultCarrierIds() []string`

GetDefaultCarrierIds returns the DefaultCarrierIds field if non-nil, zero value otherwise.

### GetDefaultCarrierIdsOk

`func (o *CustomersApiUpdateCustomerRequest) GetDefaultCarrierIdsOk() (*[]string, bool)`

GetDefaultCarrierIdsOk returns a tuple with the DefaultCarrierIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultCarrierIds

`func (o *CustomersApiUpdateCustomerRequest) SetDefaultCarrierIds(v []string)`

SetDefaultCarrierIds sets DefaultCarrierIds field to given value.

### HasDefaultCarrierIds

`func (o *CustomersApiUpdateCustomerRequest) HasDefaultCarrierIds() bool`

HasDefaultCarrierIds returns a boolean if a field has been set.

### GetRegion

`func (o *CustomersApiUpdateCustomerRequest) GetRegion() string`

GetRegion returns the Region field if non-nil, zero value otherwise.

### GetRegionOk

`func (o *CustomersApiUpdateCustomerRequest) GetRegionOk() (*string, bool)`

GetRegionOk returns a tuple with the Region field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegion

`func (o *CustomersApiUpdateCustomerRequest) SetRegion(v string)`

SetRegion sets Region field to given value.

### HasRegion

`func (o *CustomersApiUpdateCustomerRequest) HasRegion() bool`

HasRegion returns a boolean if a field has been set.

### GetBusinessType

`func (o *CustomersApiUpdateCustomerRequest) GetBusinessType() string`

GetBusinessType returns the BusinessType field if non-nil, zero value otherwise.

### GetBusinessTypeOk

`func (o *CustomersApiUpdateCustomerRequest) GetBusinessTypeOk() (*string, bool)`

GetBusinessTypeOk returns a tuple with the BusinessType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusinessType

`func (o *CustomersApiUpdateCustomerRequest) SetBusinessType(v string)`

SetBusinessType sets BusinessType field to given value.

### HasBusinessType

`func (o *CustomersApiUpdateCustomerRequest) HasBusinessType() bool`

HasBusinessType returns a boolean if a field has been set.

### GetCategory

`func (o *CustomersApiUpdateCustomerRequest) GetCategory() string`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *CustomersApiUpdateCustomerRequest) GetCategoryOk() (*string, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *CustomersApiUpdateCustomerRequest) SetCategory(v string)`

SetCategory sets Category field to given value.

### HasCategory

`func (o *CustomersApiUpdateCustomerRequest) HasCategory() bool`

HasCategory returns a boolean if a field has been set.

### GetClass

`func (o *CustomersApiUpdateCustomerRequest) GetClass() string`

GetClass returns the Class field if non-nil, zero value otherwise.

### GetClassOk

`func (o *CustomersApiUpdateCustomerRequest) GetClassOk() (*string, bool)`

GetClassOk returns a tuple with the Class field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClass

`func (o *CustomersApiUpdateCustomerRequest) SetClass(v string)`

SetClass sets Class field to given value.

### HasClass

`func (o *CustomersApiUpdateCustomerRequest) HasClass() bool`

HasClass returns a boolean if a field has been set.

### GetCatalog

`func (o *CustomersApiUpdateCustomerRequest) GetCatalog() string`

GetCatalog returns the Catalog field if non-nil, zero value otherwise.

### GetCatalogOk

`func (o *CustomersApiUpdateCustomerRequest) GetCatalogOk() (*string, bool)`

GetCatalogOk returns a tuple with the Catalog field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCatalog

`func (o *CustomersApiUpdateCustomerRequest) SetCatalog(v string)`

SetCatalog sets Catalog field to given value.

### HasCatalog

`func (o *CustomersApiUpdateCustomerRequest) HasCatalog() bool`

HasCatalog returns a boolean if a field has been set.

### GetAssignedToId

`func (o *CustomersApiUpdateCustomerRequest) GetAssignedToId() string`

GetAssignedToId returns the AssignedToId field if non-nil, zero value otherwise.

### GetAssignedToIdOk

`func (o *CustomersApiUpdateCustomerRequest) GetAssignedToIdOk() (*string, bool)`

GetAssignedToIdOk returns a tuple with the AssignedToId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignedToId

`func (o *CustomersApiUpdateCustomerRequest) SetAssignedToId(v string)`

SetAssignedToId sets AssignedToId field to given value.

### HasAssignedToId

`func (o *CustomersApiUpdateCustomerRequest) HasAssignedToId() bool`

HasAssignedToId returns a boolean if a field has been set.

### GetAssignedTo2Id

`func (o *CustomersApiUpdateCustomerRequest) GetAssignedTo2Id() string`

GetAssignedTo2Id returns the AssignedTo2Id field if non-nil, zero value otherwise.

### GetAssignedTo2IdOk

`func (o *CustomersApiUpdateCustomerRequest) GetAssignedTo2IdOk() (*string, bool)`

GetAssignedTo2IdOk returns a tuple with the AssignedTo2Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignedTo2Id

`func (o *CustomersApiUpdateCustomerRequest) SetAssignedTo2Id(v string)`

SetAssignedTo2Id sets AssignedTo2Id field to given value.

### HasAssignedTo2Id

`func (o *CustomersApiUpdateCustomerRequest) HasAssignedTo2Id() bool`

HasAssignedTo2Id returns a boolean if a field has been set.

### GetAssignedTo3Id

`func (o *CustomersApiUpdateCustomerRequest) GetAssignedTo3Id() string`

GetAssignedTo3Id returns the AssignedTo3Id field if non-nil, zero value otherwise.

### GetAssignedTo3IdOk

`func (o *CustomersApiUpdateCustomerRequest) GetAssignedTo3IdOk() (*string, bool)`

GetAssignedTo3IdOk returns a tuple with the AssignedTo3Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignedTo3Id

`func (o *CustomersApiUpdateCustomerRequest) SetAssignedTo3Id(v string)`

SetAssignedTo3Id sets AssignedTo3Id field to given value.

### HasAssignedTo3Id

`func (o *CustomersApiUpdateCustomerRequest) HasAssignedTo3Id() bool`

HasAssignedTo3Id returns a boolean if a field has been set.

### GetAssignedToGroup

`func (o *CustomersApiUpdateCustomerRequest) GetAssignedToGroup() string`

GetAssignedToGroup returns the AssignedToGroup field if non-nil, zero value otherwise.

### GetAssignedToGroupOk

`func (o *CustomersApiUpdateCustomerRequest) GetAssignedToGroupOk() (*string, bool)`

GetAssignedToGroupOk returns a tuple with the AssignedToGroup field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignedToGroup

`func (o *CustomersApiUpdateCustomerRequest) SetAssignedToGroup(v string)`

SetAssignedToGroup sets AssignedToGroup field to given value.

### HasAssignedToGroup

`func (o *CustomersApiUpdateCustomerRequest) HasAssignedToGroup() bool`

HasAssignedToGroup returns a boolean if a field has been set.

### GetContactResourceId

`func (o *CustomersApiUpdateCustomerRequest) GetContactResourceId() string`

GetContactResourceId returns the ContactResourceId field if non-nil, zero value otherwise.

### GetContactResourceIdOk

`func (o *CustomersApiUpdateCustomerRequest) GetContactResourceIdOk() (*string, bool)`

GetContactResourceIdOk returns a tuple with the ContactResourceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactResourceId

`func (o *CustomersApiUpdateCustomerRequest) SetContactResourceId(v string)`

SetContactResourceId sets ContactResourceId field to given value.

### HasContactResourceId

`func (o *CustomersApiUpdateCustomerRequest) HasContactResourceId() bool`

HasContactResourceId returns a boolean if a field has been set.

### GetAnnualSalesMillions

`func (o *CustomersApiUpdateCustomerRequest) GetAnnualSalesMillions() float64`

GetAnnualSalesMillions returns the AnnualSalesMillions field if non-nil, zero value otherwise.

### GetAnnualSalesMillionsOk

`func (o *CustomersApiUpdateCustomerRequest) GetAnnualSalesMillionsOk() (*float64, bool)`

GetAnnualSalesMillionsOk returns a tuple with the AnnualSalesMillions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnnualSalesMillions

`func (o *CustomersApiUpdateCustomerRequest) SetAnnualSalesMillions(v float64)`

SetAnnualSalesMillions sets AnnualSalesMillions field to given value.

### HasAnnualSalesMillions

`func (o *CustomersApiUpdateCustomerRequest) HasAnnualSalesMillions() bool`

HasAnnualSalesMillions returns a boolean if a field has been set.

### GetEstimatedEmployees

`func (o *CustomersApiUpdateCustomerRequest) GetEstimatedEmployees() string`

GetEstimatedEmployees returns the EstimatedEmployees field if non-nil, zero value otherwise.

### GetEstimatedEmployeesOk

`func (o *CustomersApiUpdateCustomerRequest) GetEstimatedEmployeesOk() (*string, bool)`

GetEstimatedEmployeesOk returns a tuple with the EstimatedEmployees field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEstimatedEmployees

`func (o *CustomersApiUpdateCustomerRequest) SetEstimatedEmployees(v string)`

SetEstimatedEmployees sets EstimatedEmployees field to given value.

### HasEstimatedEmployees

`func (o *CustomersApiUpdateCustomerRequest) HasEstimatedEmployees() bool`

HasEstimatedEmployees returns a boolean if a field has been set.

### GetPhone

`func (o *CustomersApiUpdateCustomerRequest) GetPhone() string`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *CustomersApiUpdateCustomerRequest) GetPhoneOk() (*string, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *CustomersApiUpdateCustomerRequest) SetPhone(v string)`

SetPhone sets Phone field to given value.

### HasPhone

`func (o *CustomersApiUpdateCustomerRequest) HasPhone() bool`

HasPhone returns a boolean if a field has been set.

### GetFax

`func (o *CustomersApiUpdateCustomerRequest) GetFax() string`

GetFax returns the Fax field if non-nil, zero value otherwise.

### GetFaxOk

`func (o *CustomersApiUpdateCustomerRequest) GetFaxOk() (*string, bool)`

GetFaxOk returns a tuple with the Fax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFax

`func (o *CustomersApiUpdateCustomerRequest) SetFax(v string)`

SetFax sets Fax field to given value.

### HasFax

`func (o *CustomersApiUpdateCustomerRequest) HasFax() bool`

HasFax returns a boolean if a field has been set.

### GetEmail

`func (o *CustomersApiUpdateCustomerRequest) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *CustomersApiUpdateCustomerRequest) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *CustomersApiUpdateCustomerRequest) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *CustomersApiUpdateCustomerRequest) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetTrackingNoOnWeighScaleRequired

`func (o *CustomersApiUpdateCustomerRequest) GetTrackingNoOnWeighScaleRequired() bool`

GetTrackingNoOnWeighScaleRequired returns the TrackingNoOnWeighScaleRequired field if non-nil, zero value otherwise.

### GetTrackingNoOnWeighScaleRequiredOk

`func (o *CustomersApiUpdateCustomerRequest) GetTrackingNoOnWeighScaleRequiredOk() (*bool, bool)`

GetTrackingNoOnWeighScaleRequiredOk returns a tuple with the TrackingNoOnWeighScaleRequired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackingNoOnWeighScaleRequired

`func (o *CustomersApiUpdateCustomerRequest) SetTrackingNoOnWeighScaleRequired(v bool)`

SetTrackingNoOnWeighScaleRequired sets TrackingNoOnWeighScaleRequired field to given value.

### HasTrackingNoOnWeighScaleRequired

`func (o *CustomersApiUpdateCustomerRequest) HasTrackingNoOnWeighScaleRequired() bool`

HasTrackingNoOnWeighScaleRequired returns a boolean if a field has been set.

### GetMultipleOrdersPerShipper

`func (o *CustomersApiUpdateCustomerRequest) GetMultipleOrdersPerShipper() bool`

GetMultipleOrdersPerShipper returns the MultipleOrdersPerShipper field if non-nil, zero value otherwise.

### GetMultipleOrdersPerShipperOk

`func (o *CustomersApiUpdateCustomerRequest) GetMultipleOrdersPerShipperOk() (*bool, bool)`

GetMultipleOrdersPerShipperOk returns a tuple with the MultipleOrdersPerShipper field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMultipleOrdersPerShipper

`func (o *CustomersApiUpdateCustomerRequest) SetMultipleOrdersPerShipper(v bool)`

SetMultipleOrdersPerShipper sets MultipleOrdersPerShipper field to given value.

### HasMultipleOrdersPerShipper

`func (o *CustomersApiUpdateCustomerRequest) HasMultipleOrdersPerShipper() bool`

HasMultipleOrdersPerShipper returns a boolean if a field has been set.

### GetEstimatedAnnualSales

`func (o *CustomersApiUpdateCustomerRequest) GetEstimatedAnnualSales() string`

GetEstimatedAnnualSales returns the EstimatedAnnualSales field if non-nil, zero value otherwise.

### GetEstimatedAnnualSalesOk

`func (o *CustomersApiUpdateCustomerRequest) GetEstimatedAnnualSalesOk() (*string, bool)`

GetEstimatedAnnualSalesOk returns a tuple with the EstimatedAnnualSales field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEstimatedAnnualSales

`func (o *CustomersApiUpdateCustomerRequest) SetEstimatedAnnualSales(v string)`

SetEstimatedAnnualSales sets EstimatedAnnualSales field to given value.

### HasEstimatedAnnualSales

`func (o *CustomersApiUpdateCustomerRequest) HasEstimatedAnnualSales() bool`

HasEstimatedAnnualSales returns a boolean if a field has been set.

### GetNewShipperPerReleaseNo

`func (o *CustomersApiUpdateCustomerRequest) GetNewShipperPerReleaseNo() bool`

GetNewShipperPerReleaseNo returns the NewShipperPerReleaseNo field if non-nil, zero value otherwise.

### GetNewShipperPerReleaseNoOk

`func (o *CustomersApiUpdateCustomerRequest) GetNewShipperPerReleaseNoOk() (*bool, bool)`

GetNewShipperPerReleaseNoOk returns a tuple with the NewShipperPerReleaseNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNewShipperPerReleaseNo

`func (o *CustomersApiUpdateCustomerRequest) SetNewShipperPerReleaseNo(v bool)`

SetNewShipperPerReleaseNo sets NewShipperPerReleaseNo field to given value.

### HasNewShipperPerReleaseNo

`func (o *CustomersApiUpdateCustomerRequest) HasNewShipperPerReleaseNo() bool`

HasNewShipperPerReleaseNo returns a boolean if a field has been set.

### GetDefaultBackOrder

`func (o *CustomersApiUpdateCustomerRequest) GetDefaultBackOrder() string`

GetDefaultBackOrder returns the DefaultBackOrder field if non-nil, zero value otherwise.

### GetDefaultBackOrderOk

`func (o *CustomersApiUpdateCustomerRequest) GetDefaultBackOrderOk() (*string, bool)`

GetDefaultBackOrderOk returns a tuple with the DefaultBackOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultBackOrder

`func (o *CustomersApiUpdateCustomerRequest) SetDefaultBackOrder(v string)`

SetDefaultBackOrder sets DefaultBackOrder field to given value.

### HasDefaultBackOrder

`func (o *CustomersApiUpdateCustomerRequest) HasDefaultBackOrder() bool`

HasDefaultBackOrder returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


