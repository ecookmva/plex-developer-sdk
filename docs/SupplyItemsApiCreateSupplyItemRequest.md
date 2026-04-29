# SupplyItemsApiCreateSupplyItemRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | A unique identifier for the Supply Item. This will be automatically generated if omitted from the request. | [optional] 
**SupplyItemNumber** | Pointer to **string** | A short identifier for the Supply Item. | [optional] 
**Type** | Pointer to **string** | Indicates the Supply Item type, such as office supplies or shop supplies. Setup Table: Item Type | [optional] 
**Category** | Pointer to **string** | Setup Table: Supply Category | [optional] 
**Priority** | Pointer to **string** | Setup Table: Item Priority | [optional] 
**Group** | Pointer to **string** | A supply group, used to categorize Supply Items, such as Electrical, Mechanical, Office Supplies. Setup Table: Item Group | [optional] 
**CustomerUnitPrice** | Pointer to **float64** | Customer price per unit. | [optional] 
**Description** | Pointer to **string** | Text description of the Supply Item. | [optional] 
**InventoryUnit** | Pointer to **string** | The unit of measure for the Supply Item. | [optional] 
**BriefDescription** | Pointer to **string** | Short description of the Supply Item. | [optional] 
**AccountId** | Pointer to **string** | The default expense account for the Supply Item. | [optional] 
**ManufacturerCode** | Pointer to **string** | The manufacturer&#39;s code for the supply item. When this field is populated, the supplierId field cannot not be present in the request. | [optional] 
**SupplierId** | Pointer to **string** | The suppliers from whom the supplies are purchased. When this field is populated, the manufacturerCode cannot be present in the request. | [optional] 
**ManufacturerItemNumber** | Pointer to **string** | The manufacturer&#39;s item number. | [optional] 
**ManufacturerItemRevision** | Pointer to **string** | The manufacturer&#39;s revision number. | [optional] 
**ManufacturerText** | Pointer to **string** | Notes about the manufacturer | [optional] 
**TaxCodeNumber** | Pointer to **int32** |  | [optional] 
**MaxQuantity** | Pointer to **float64** | The maximum number of Supply Items allowed to be in inventory. | [optional] 
**MinQuantity** | Pointer to **float64** | The minimum number of Supply Items allowed to be in inventory. | [optional] 
**Note** | Pointer to **string** | Purchasing notes. | [optional] 
**UpdateWhenReceived** | Pointer to **bool** | Update inventory when supplies are received. | [optional] 
**Active** | Pointer to **bool** |  | [optional] 
**AverageCost** | Pointer to **float64** | Average cost of a Supply Item. | [optional] 
**ResponsiblePersonId** | Pointer to **string** | The ID of the person responsible for the Supply Item. | [optional] 
**VendorManaged** | Pointer to **bool** | Vendor Managed flag | [optional] 
**Commodity** | Pointer to **string** |  | [optional] 
**CountryOfOrigin** | Pointer to **string** | The country of origin of the Supply Item. | [optional] 
**Consignment** | Pointer to **bool** |  | [optional] 

## Methods

### NewSupplyItemsApiCreateSupplyItemRequest

`func NewSupplyItemsApiCreateSupplyItemRequest() *SupplyItemsApiCreateSupplyItemRequest`

NewSupplyItemsApiCreateSupplyItemRequest instantiates a new SupplyItemsApiCreateSupplyItemRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSupplyItemsApiCreateSupplyItemRequestWithDefaults

`func NewSupplyItemsApiCreateSupplyItemRequestWithDefaults() *SupplyItemsApiCreateSupplyItemRequest`

NewSupplyItemsApiCreateSupplyItemRequestWithDefaults instantiates a new SupplyItemsApiCreateSupplyItemRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SupplyItemsApiCreateSupplyItemRequest) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *SupplyItemsApiCreateSupplyItemRequest) HasId() bool`

HasId returns a boolean if a field has been set.

### GetSupplyItemNumber

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetSupplyItemNumber() string`

GetSupplyItemNumber returns the SupplyItemNumber field if non-nil, zero value otherwise.

### GetSupplyItemNumberOk

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetSupplyItemNumberOk() (*string, bool)`

GetSupplyItemNumberOk returns a tuple with the SupplyItemNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplyItemNumber

`func (o *SupplyItemsApiCreateSupplyItemRequest) SetSupplyItemNumber(v string)`

SetSupplyItemNumber sets SupplyItemNumber field to given value.

### HasSupplyItemNumber

`func (o *SupplyItemsApiCreateSupplyItemRequest) HasSupplyItemNumber() bool`

HasSupplyItemNumber returns a boolean if a field has been set.

### GetType

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *SupplyItemsApiCreateSupplyItemRequest) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *SupplyItemsApiCreateSupplyItemRequest) HasType() bool`

HasType returns a boolean if a field has been set.

### GetCategory

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetCategory() string`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetCategoryOk() (*string, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *SupplyItemsApiCreateSupplyItemRequest) SetCategory(v string)`

SetCategory sets Category field to given value.

### HasCategory

`func (o *SupplyItemsApiCreateSupplyItemRequest) HasCategory() bool`

HasCategory returns a boolean if a field has been set.

### GetPriority

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetPriority() string`

GetPriority returns the Priority field if non-nil, zero value otherwise.

### GetPriorityOk

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetPriorityOk() (*string, bool)`

GetPriorityOk returns a tuple with the Priority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriority

`func (o *SupplyItemsApiCreateSupplyItemRequest) SetPriority(v string)`

SetPriority sets Priority field to given value.

### HasPriority

`func (o *SupplyItemsApiCreateSupplyItemRequest) HasPriority() bool`

HasPriority returns a boolean if a field has been set.

### GetGroup

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetGroup() string`

GetGroup returns the Group field if non-nil, zero value otherwise.

### GetGroupOk

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetGroupOk() (*string, bool)`

GetGroupOk returns a tuple with the Group field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroup

`func (o *SupplyItemsApiCreateSupplyItemRequest) SetGroup(v string)`

SetGroup sets Group field to given value.

### HasGroup

`func (o *SupplyItemsApiCreateSupplyItemRequest) HasGroup() bool`

HasGroup returns a boolean if a field has been set.

### GetCustomerUnitPrice

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetCustomerUnitPrice() float64`

GetCustomerUnitPrice returns the CustomerUnitPrice field if non-nil, zero value otherwise.

### GetCustomerUnitPriceOk

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetCustomerUnitPriceOk() (*float64, bool)`

GetCustomerUnitPriceOk returns a tuple with the CustomerUnitPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerUnitPrice

`func (o *SupplyItemsApiCreateSupplyItemRequest) SetCustomerUnitPrice(v float64)`

SetCustomerUnitPrice sets CustomerUnitPrice field to given value.

### HasCustomerUnitPrice

`func (o *SupplyItemsApiCreateSupplyItemRequest) HasCustomerUnitPrice() bool`

HasCustomerUnitPrice returns a boolean if a field has been set.

### GetDescription

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *SupplyItemsApiCreateSupplyItemRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *SupplyItemsApiCreateSupplyItemRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetInventoryUnit

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetInventoryUnit() string`

GetInventoryUnit returns the InventoryUnit field if non-nil, zero value otherwise.

### GetInventoryUnitOk

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetInventoryUnitOk() (*string, bool)`

GetInventoryUnitOk returns a tuple with the InventoryUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInventoryUnit

`func (o *SupplyItemsApiCreateSupplyItemRequest) SetInventoryUnit(v string)`

SetInventoryUnit sets InventoryUnit field to given value.

### HasInventoryUnit

`func (o *SupplyItemsApiCreateSupplyItemRequest) HasInventoryUnit() bool`

HasInventoryUnit returns a boolean if a field has been set.

### GetBriefDescription

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetBriefDescription() string`

GetBriefDescription returns the BriefDescription field if non-nil, zero value otherwise.

### GetBriefDescriptionOk

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetBriefDescriptionOk() (*string, bool)`

GetBriefDescriptionOk returns a tuple with the BriefDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBriefDescription

`func (o *SupplyItemsApiCreateSupplyItemRequest) SetBriefDescription(v string)`

SetBriefDescription sets BriefDescription field to given value.

### HasBriefDescription

`func (o *SupplyItemsApiCreateSupplyItemRequest) HasBriefDescription() bool`

HasBriefDescription returns a boolean if a field has been set.

### GetAccountId

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetAccountId() string`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetAccountIdOk() (*string, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *SupplyItemsApiCreateSupplyItemRequest) SetAccountId(v string)`

SetAccountId sets AccountId field to given value.

### HasAccountId

`func (o *SupplyItemsApiCreateSupplyItemRequest) HasAccountId() bool`

HasAccountId returns a boolean if a field has been set.

### GetManufacturerCode

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetManufacturerCode() string`

GetManufacturerCode returns the ManufacturerCode field if non-nil, zero value otherwise.

### GetManufacturerCodeOk

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetManufacturerCodeOk() (*string, bool)`

GetManufacturerCodeOk returns a tuple with the ManufacturerCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManufacturerCode

`func (o *SupplyItemsApiCreateSupplyItemRequest) SetManufacturerCode(v string)`

SetManufacturerCode sets ManufacturerCode field to given value.

### HasManufacturerCode

`func (o *SupplyItemsApiCreateSupplyItemRequest) HasManufacturerCode() bool`

HasManufacturerCode returns a boolean if a field has been set.

### GetSupplierId

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetSupplierId() string`

GetSupplierId returns the SupplierId field if non-nil, zero value otherwise.

### GetSupplierIdOk

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetSupplierIdOk() (*string, bool)`

GetSupplierIdOk returns a tuple with the SupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierId

`func (o *SupplyItemsApiCreateSupplyItemRequest) SetSupplierId(v string)`

SetSupplierId sets SupplierId field to given value.

### HasSupplierId

`func (o *SupplyItemsApiCreateSupplyItemRequest) HasSupplierId() bool`

HasSupplierId returns a boolean if a field has been set.

### GetManufacturerItemNumber

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetManufacturerItemNumber() string`

GetManufacturerItemNumber returns the ManufacturerItemNumber field if non-nil, zero value otherwise.

### GetManufacturerItemNumberOk

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetManufacturerItemNumberOk() (*string, bool)`

GetManufacturerItemNumberOk returns a tuple with the ManufacturerItemNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManufacturerItemNumber

`func (o *SupplyItemsApiCreateSupplyItemRequest) SetManufacturerItemNumber(v string)`

SetManufacturerItemNumber sets ManufacturerItemNumber field to given value.

### HasManufacturerItemNumber

`func (o *SupplyItemsApiCreateSupplyItemRequest) HasManufacturerItemNumber() bool`

HasManufacturerItemNumber returns a boolean if a field has been set.

### GetManufacturerItemRevision

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetManufacturerItemRevision() string`

GetManufacturerItemRevision returns the ManufacturerItemRevision field if non-nil, zero value otherwise.

### GetManufacturerItemRevisionOk

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetManufacturerItemRevisionOk() (*string, bool)`

GetManufacturerItemRevisionOk returns a tuple with the ManufacturerItemRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManufacturerItemRevision

`func (o *SupplyItemsApiCreateSupplyItemRequest) SetManufacturerItemRevision(v string)`

SetManufacturerItemRevision sets ManufacturerItemRevision field to given value.

### HasManufacturerItemRevision

`func (o *SupplyItemsApiCreateSupplyItemRequest) HasManufacturerItemRevision() bool`

HasManufacturerItemRevision returns a boolean if a field has been set.

### GetManufacturerText

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetManufacturerText() string`

GetManufacturerText returns the ManufacturerText field if non-nil, zero value otherwise.

### GetManufacturerTextOk

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetManufacturerTextOk() (*string, bool)`

GetManufacturerTextOk returns a tuple with the ManufacturerText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManufacturerText

`func (o *SupplyItemsApiCreateSupplyItemRequest) SetManufacturerText(v string)`

SetManufacturerText sets ManufacturerText field to given value.

### HasManufacturerText

`func (o *SupplyItemsApiCreateSupplyItemRequest) HasManufacturerText() bool`

HasManufacturerText returns a boolean if a field has been set.

### GetTaxCodeNumber

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetTaxCodeNumber() int32`

GetTaxCodeNumber returns the TaxCodeNumber field if non-nil, zero value otherwise.

### GetTaxCodeNumberOk

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetTaxCodeNumberOk() (*int32, bool)`

GetTaxCodeNumberOk returns a tuple with the TaxCodeNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxCodeNumber

`func (o *SupplyItemsApiCreateSupplyItemRequest) SetTaxCodeNumber(v int32)`

SetTaxCodeNumber sets TaxCodeNumber field to given value.

### HasTaxCodeNumber

`func (o *SupplyItemsApiCreateSupplyItemRequest) HasTaxCodeNumber() bool`

HasTaxCodeNumber returns a boolean if a field has been set.

### GetMaxQuantity

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetMaxQuantity() float64`

GetMaxQuantity returns the MaxQuantity field if non-nil, zero value otherwise.

### GetMaxQuantityOk

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetMaxQuantityOk() (*float64, bool)`

GetMaxQuantityOk returns a tuple with the MaxQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxQuantity

`func (o *SupplyItemsApiCreateSupplyItemRequest) SetMaxQuantity(v float64)`

SetMaxQuantity sets MaxQuantity field to given value.

### HasMaxQuantity

`func (o *SupplyItemsApiCreateSupplyItemRequest) HasMaxQuantity() bool`

HasMaxQuantity returns a boolean if a field has been set.

### GetMinQuantity

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetMinQuantity() float64`

GetMinQuantity returns the MinQuantity field if non-nil, zero value otherwise.

### GetMinQuantityOk

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetMinQuantityOk() (*float64, bool)`

GetMinQuantityOk returns a tuple with the MinQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinQuantity

`func (o *SupplyItemsApiCreateSupplyItemRequest) SetMinQuantity(v float64)`

SetMinQuantity sets MinQuantity field to given value.

### HasMinQuantity

`func (o *SupplyItemsApiCreateSupplyItemRequest) HasMinQuantity() bool`

HasMinQuantity returns a boolean if a field has been set.

### GetNote

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *SupplyItemsApiCreateSupplyItemRequest) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *SupplyItemsApiCreateSupplyItemRequest) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetUpdateWhenReceived

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetUpdateWhenReceived() bool`

GetUpdateWhenReceived returns the UpdateWhenReceived field if non-nil, zero value otherwise.

### GetUpdateWhenReceivedOk

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetUpdateWhenReceivedOk() (*bool, bool)`

GetUpdateWhenReceivedOk returns a tuple with the UpdateWhenReceived field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdateWhenReceived

`func (o *SupplyItemsApiCreateSupplyItemRequest) SetUpdateWhenReceived(v bool)`

SetUpdateWhenReceived sets UpdateWhenReceived field to given value.

### HasUpdateWhenReceived

`func (o *SupplyItemsApiCreateSupplyItemRequest) HasUpdateWhenReceived() bool`

HasUpdateWhenReceived returns a boolean if a field has been set.

### GetActive

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *SupplyItemsApiCreateSupplyItemRequest) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *SupplyItemsApiCreateSupplyItemRequest) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetAverageCost

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetAverageCost() float64`

GetAverageCost returns the AverageCost field if non-nil, zero value otherwise.

### GetAverageCostOk

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetAverageCostOk() (*float64, bool)`

GetAverageCostOk returns a tuple with the AverageCost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAverageCost

`func (o *SupplyItemsApiCreateSupplyItemRequest) SetAverageCost(v float64)`

SetAverageCost sets AverageCost field to given value.

### HasAverageCost

`func (o *SupplyItemsApiCreateSupplyItemRequest) HasAverageCost() bool`

HasAverageCost returns a boolean if a field has been set.

### GetResponsiblePersonId

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetResponsiblePersonId() string`

GetResponsiblePersonId returns the ResponsiblePersonId field if non-nil, zero value otherwise.

### GetResponsiblePersonIdOk

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetResponsiblePersonIdOk() (*string, bool)`

GetResponsiblePersonIdOk returns a tuple with the ResponsiblePersonId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResponsiblePersonId

`func (o *SupplyItemsApiCreateSupplyItemRequest) SetResponsiblePersonId(v string)`

SetResponsiblePersonId sets ResponsiblePersonId field to given value.

### HasResponsiblePersonId

`func (o *SupplyItemsApiCreateSupplyItemRequest) HasResponsiblePersonId() bool`

HasResponsiblePersonId returns a boolean if a field has been set.

### GetVendorManaged

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetVendorManaged() bool`

GetVendorManaged returns the VendorManaged field if non-nil, zero value otherwise.

### GetVendorManagedOk

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetVendorManagedOk() (*bool, bool)`

GetVendorManagedOk returns a tuple with the VendorManaged field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVendorManaged

`func (o *SupplyItemsApiCreateSupplyItemRequest) SetVendorManaged(v bool)`

SetVendorManaged sets VendorManaged field to given value.

### HasVendorManaged

`func (o *SupplyItemsApiCreateSupplyItemRequest) HasVendorManaged() bool`

HasVendorManaged returns a boolean if a field has been set.

### GetCommodity

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetCommodity() string`

GetCommodity returns the Commodity field if non-nil, zero value otherwise.

### GetCommodityOk

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetCommodityOk() (*string, bool)`

GetCommodityOk returns a tuple with the Commodity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCommodity

`func (o *SupplyItemsApiCreateSupplyItemRequest) SetCommodity(v string)`

SetCommodity sets Commodity field to given value.

### HasCommodity

`func (o *SupplyItemsApiCreateSupplyItemRequest) HasCommodity() bool`

HasCommodity returns a boolean if a field has been set.

### GetCountryOfOrigin

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetCountryOfOrigin() string`

GetCountryOfOrigin returns the CountryOfOrigin field if non-nil, zero value otherwise.

### GetCountryOfOriginOk

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetCountryOfOriginOk() (*string, bool)`

GetCountryOfOriginOk returns a tuple with the CountryOfOrigin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryOfOrigin

`func (o *SupplyItemsApiCreateSupplyItemRequest) SetCountryOfOrigin(v string)`

SetCountryOfOrigin sets CountryOfOrigin field to given value.

### HasCountryOfOrigin

`func (o *SupplyItemsApiCreateSupplyItemRequest) HasCountryOfOrigin() bool`

HasCountryOfOrigin returns a boolean if a field has been set.

### GetConsignment

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetConsignment() bool`

GetConsignment returns the Consignment field if non-nil, zero value otherwise.

### GetConsignmentOk

`func (o *SupplyItemsApiCreateSupplyItemRequest) GetConsignmentOk() (*bool, bool)`

GetConsignmentOk returns a tuple with the Consignment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsignment

`func (o *SupplyItemsApiCreateSupplyItemRequest) SetConsignment(v bool)`

SetConsignment sets Consignment field to given value.

### HasConsignment

`func (o *SupplyItemsApiCreateSupplyItemRequest) HasConsignment() bool`

HasConsignment returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


