# SupplyItemsApiUpdateSupplyItemResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | A unique identifier for the Supply Item. This will be automatically generated if omitted from the request. | [optional] 
**SupplyItemNumber** | Pointer to **string** | A short identifier for the Supply Item. | [optional] 
**Type** | Pointer to **string** | Indicates the Supply Item type, such as office supplies or shop supplies. Setup Table: Item Type | [optional] 
**Category** | Pointer to **string** | Setup Table: Supply Category | [optional] 
**Priority** | Pointer to **string** | Setup Table: Item Priority | [optional] 
**Group** | Pointer to **string** | A supply group, used to categorize Supply Items, such as Electrical, Mechanical, Office Supplies. Setup Table: Item Group | [optional] 
**Description** | Pointer to **string** | Text description of the Supply Item. | [optional] 
**CustomerUnitPrice** | Pointer to **float64** | Customer price per unit. | [optional] 
**InventoryUnit** | Pointer to **string** | The unit of measure for the Supply Item. | [optional] 
**BriefDescription** | Pointer to **string** | Short description of the Supply Item. | [optional] 
**AccountId** | Pointer to **string** | The default expense account for the Supply Item. | [optional] 
**ManufacturerCode** | Pointer to **string** | The manufacturer&#39;s code for the Supply Item. | [optional] 
**SupplierId** | Pointer to **string** | The suppliers from whom the supplies are purchased. | [optional] 
**ManufacturerItemNumber** | Pointer to **string** | The manufacturer&#39;s item number. | [optional] 
**ManufacturerItemRevision** | Pointer to **string** | The manufacturer&#39;s revision number. | [optional] 
**ManufacturerText** | Pointer to **string** | Notes about the manufacturer | [optional] 
**CreatedDate** | Pointer to **time.Time** | The date on which the record was created. | [optional] 
**CreatedById** | Pointer to **string** | The IAM Account ID of the user who created the record. | [optional] 
**ModifiedDate** | Pointer to **time.Time** | The date on which the record was last modified. | [optional] 
**ModifiedById** | Pointer to **string** | The IAM Account ID of the user who last modified the record. | [optional] 
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

### NewSupplyItemsApiUpdateSupplyItemResponse

`func NewSupplyItemsApiUpdateSupplyItemResponse() *SupplyItemsApiUpdateSupplyItemResponse`

NewSupplyItemsApiUpdateSupplyItemResponse instantiates a new SupplyItemsApiUpdateSupplyItemResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSupplyItemsApiUpdateSupplyItemResponseWithDefaults

`func NewSupplyItemsApiUpdateSupplyItemResponseWithDefaults() *SupplyItemsApiUpdateSupplyItemResponse`

NewSupplyItemsApiUpdateSupplyItemResponseWithDefaults instantiates a new SupplyItemsApiUpdateSupplyItemResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SupplyItemsApiUpdateSupplyItemResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *SupplyItemsApiUpdateSupplyItemResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetSupplyItemNumber

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetSupplyItemNumber() string`

GetSupplyItemNumber returns the SupplyItemNumber field if non-nil, zero value otherwise.

### GetSupplyItemNumberOk

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetSupplyItemNumberOk() (*string, bool)`

GetSupplyItemNumberOk returns a tuple with the SupplyItemNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplyItemNumber

`func (o *SupplyItemsApiUpdateSupplyItemResponse) SetSupplyItemNumber(v string)`

SetSupplyItemNumber sets SupplyItemNumber field to given value.

### HasSupplyItemNumber

`func (o *SupplyItemsApiUpdateSupplyItemResponse) HasSupplyItemNumber() bool`

HasSupplyItemNumber returns a boolean if a field has been set.

### GetType

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *SupplyItemsApiUpdateSupplyItemResponse) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *SupplyItemsApiUpdateSupplyItemResponse) HasType() bool`

HasType returns a boolean if a field has been set.

### GetCategory

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetCategory() string`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetCategoryOk() (*string, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *SupplyItemsApiUpdateSupplyItemResponse) SetCategory(v string)`

SetCategory sets Category field to given value.

### HasCategory

`func (o *SupplyItemsApiUpdateSupplyItemResponse) HasCategory() bool`

HasCategory returns a boolean if a field has been set.

### GetPriority

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetPriority() string`

GetPriority returns the Priority field if non-nil, zero value otherwise.

### GetPriorityOk

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetPriorityOk() (*string, bool)`

GetPriorityOk returns a tuple with the Priority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriority

`func (o *SupplyItemsApiUpdateSupplyItemResponse) SetPriority(v string)`

SetPriority sets Priority field to given value.

### HasPriority

`func (o *SupplyItemsApiUpdateSupplyItemResponse) HasPriority() bool`

HasPriority returns a boolean if a field has been set.

### GetGroup

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetGroup() string`

GetGroup returns the Group field if non-nil, zero value otherwise.

### GetGroupOk

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetGroupOk() (*string, bool)`

GetGroupOk returns a tuple with the Group field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroup

`func (o *SupplyItemsApiUpdateSupplyItemResponse) SetGroup(v string)`

SetGroup sets Group field to given value.

### HasGroup

`func (o *SupplyItemsApiUpdateSupplyItemResponse) HasGroup() bool`

HasGroup returns a boolean if a field has been set.

### GetDescription

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *SupplyItemsApiUpdateSupplyItemResponse) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *SupplyItemsApiUpdateSupplyItemResponse) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetCustomerUnitPrice

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetCustomerUnitPrice() float64`

GetCustomerUnitPrice returns the CustomerUnitPrice field if non-nil, zero value otherwise.

### GetCustomerUnitPriceOk

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetCustomerUnitPriceOk() (*float64, bool)`

GetCustomerUnitPriceOk returns a tuple with the CustomerUnitPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerUnitPrice

`func (o *SupplyItemsApiUpdateSupplyItemResponse) SetCustomerUnitPrice(v float64)`

SetCustomerUnitPrice sets CustomerUnitPrice field to given value.

### HasCustomerUnitPrice

`func (o *SupplyItemsApiUpdateSupplyItemResponse) HasCustomerUnitPrice() bool`

HasCustomerUnitPrice returns a boolean if a field has been set.

### GetInventoryUnit

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetInventoryUnit() string`

GetInventoryUnit returns the InventoryUnit field if non-nil, zero value otherwise.

### GetInventoryUnitOk

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetInventoryUnitOk() (*string, bool)`

GetInventoryUnitOk returns a tuple with the InventoryUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInventoryUnit

`func (o *SupplyItemsApiUpdateSupplyItemResponse) SetInventoryUnit(v string)`

SetInventoryUnit sets InventoryUnit field to given value.

### HasInventoryUnit

`func (o *SupplyItemsApiUpdateSupplyItemResponse) HasInventoryUnit() bool`

HasInventoryUnit returns a boolean if a field has been set.

### GetBriefDescription

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetBriefDescription() string`

GetBriefDescription returns the BriefDescription field if non-nil, zero value otherwise.

### GetBriefDescriptionOk

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetBriefDescriptionOk() (*string, bool)`

GetBriefDescriptionOk returns a tuple with the BriefDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBriefDescription

`func (o *SupplyItemsApiUpdateSupplyItemResponse) SetBriefDescription(v string)`

SetBriefDescription sets BriefDescription field to given value.

### HasBriefDescription

`func (o *SupplyItemsApiUpdateSupplyItemResponse) HasBriefDescription() bool`

HasBriefDescription returns a boolean if a field has been set.

### GetAccountId

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetAccountId() string`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetAccountIdOk() (*string, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *SupplyItemsApiUpdateSupplyItemResponse) SetAccountId(v string)`

SetAccountId sets AccountId field to given value.

### HasAccountId

`func (o *SupplyItemsApiUpdateSupplyItemResponse) HasAccountId() bool`

HasAccountId returns a boolean if a field has been set.

### GetManufacturerCode

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetManufacturerCode() string`

GetManufacturerCode returns the ManufacturerCode field if non-nil, zero value otherwise.

### GetManufacturerCodeOk

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetManufacturerCodeOk() (*string, bool)`

GetManufacturerCodeOk returns a tuple with the ManufacturerCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManufacturerCode

`func (o *SupplyItemsApiUpdateSupplyItemResponse) SetManufacturerCode(v string)`

SetManufacturerCode sets ManufacturerCode field to given value.

### HasManufacturerCode

`func (o *SupplyItemsApiUpdateSupplyItemResponse) HasManufacturerCode() bool`

HasManufacturerCode returns a boolean if a field has been set.

### GetSupplierId

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetSupplierId() string`

GetSupplierId returns the SupplierId field if non-nil, zero value otherwise.

### GetSupplierIdOk

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetSupplierIdOk() (*string, bool)`

GetSupplierIdOk returns a tuple with the SupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierId

`func (o *SupplyItemsApiUpdateSupplyItemResponse) SetSupplierId(v string)`

SetSupplierId sets SupplierId field to given value.

### HasSupplierId

`func (o *SupplyItemsApiUpdateSupplyItemResponse) HasSupplierId() bool`

HasSupplierId returns a boolean if a field has been set.

### GetManufacturerItemNumber

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetManufacturerItemNumber() string`

GetManufacturerItemNumber returns the ManufacturerItemNumber field if non-nil, zero value otherwise.

### GetManufacturerItemNumberOk

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetManufacturerItemNumberOk() (*string, bool)`

GetManufacturerItemNumberOk returns a tuple with the ManufacturerItemNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManufacturerItemNumber

`func (o *SupplyItemsApiUpdateSupplyItemResponse) SetManufacturerItemNumber(v string)`

SetManufacturerItemNumber sets ManufacturerItemNumber field to given value.

### HasManufacturerItemNumber

`func (o *SupplyItemsApiUpdateSupplyItemResponse) HasManufacturerItemNumber() bool`

HasManufacturerItemNumber returns a boolean if a field has been set.

### GetManufacturerItemRevision

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetManufacturerItemRevision() string`

GetManufacturerItemRevision returns the ManufacturerItemRevision field if non-nil, zero value otherwise.

### GetManufacturerItemRevisionOk

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetManufacturerItemRevisionOk() (*string, bool)`

GetManufacturerItemRevisionOk returns a tuple with the ManufacturerItemRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManufacturerItemRevision

`func (o *SupplyItemsApiUpdateSupplyItemResponse) SetManufacturerItemRevision(v string)`

SetManufacturerItemRevision sets ManufacturerItemRevision field to given value.

### HasManufacturerItemRevision

`func (o *SupplyItemsApiUpdateSupplyItemResponse) HasManufacturerItemRevision() bool`

HasManufacturerItemRevision returns a boolean if a field has been set.

### GetManufacturerText

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetManufacturerText() string`

GetManufacturerText returns the ManufacturerText field if non-nil, zero value otherwise.

### GetManufacturerTextOk

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetManufacturerTextOk() (*string, bool)`

GetManufacturerTextOk returns a tuple with the ManufacturerText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManufacturerText

`func (o *SupplyItemsApiUpdateSupplyItemResponse) SetManufacturerText(v string)`

SetManufacturerText sets ManufacturerText field to given value.

### HasManufacturerText

`func (o *SupplyItemsApiUpdateSupplyItemResponse) HasManufacturerText() bool`

HasManufacturerText returns a boolean if a field has been set.

### GetCreatedDate

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *SupplyItemsApiUpdateSupplyItemResponse) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *SupplyItemsApiUpdateSupplyItemResponse) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.

### GetCreatedById

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetCreatedById() string`

GetCreatedById returns the CreatedById field if non-nil, zero value otherwise.

### GetCreatedByIdOk

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetCreatedByIdOk() (*string, bool)`

GetCreatedByIdOk returns a tuple with the CreatedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedById

`func (o *SupplyItemsApiUpdateSupplyItemResponse) SetCreatedById(v string)`

SetCreatedById sets CreatedById field to given value.

### HasCreatedById

`func (o *SupplyItemsApiUpdateSupplyItemResponse) HasCreatedById() bool`

HasCreatedById returns a boolean if a field has been set.

### GetModifiedDate

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetModifiedDate() time.Time`

GetModifiedDate returns the ModifiedDate field if non-nil, zero value otherwise.

### GetModifiedDateOk

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetModifiedDateOk() (*time.Time, bool)`

GetModifiedDateOk returns a tuple with the ModifiedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDate

`func (o *SupplyItemsApiUpdateSupplyItemResponse) SetModifiedDate(v time.Time)`

SetModifiedDate sets ModifiedDate field to given value.

### HasModifiedDate

`func (o *SupplyItemsApiUpdateSupplyItemResponse) HasModifiedDate() bool`

HasModifiedDate returns a boolean if a field has been set.

### GetModifiedById

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *SupplyItemsApiUpdateSupplyItemResponse) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *SupplyItemsApiUpdateSupplyItemResponse) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetTaxCodeNumber

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetTaxCodeNumber() int32`

GetTaxCodeNumber returns the TaxCodeNumber field if non-nil, zero value otherwise.

### GetTaxCodeNumberOk

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetTaxCodeNumberOk() (*int32, bool)`

GetTaxCodeNumberOk returns a tuple with the TaxCodeNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxCodeNumber

`func (o *SupplyItemsApiUpdateSupplyItemResponse) SetTaxCodeNumber(v int32)`

SetTaxCodeNumber sets TaxCodeNumber field to given value.

### HasTaxCodeNumber

`func (o *SupplyItemsApiUpdateSupplyItemResponse) HasTaxCodeNumber() bool`

HasTaxCodeNumber returns a boolean if a field has been set.

### GetMaxQuantity

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetMaxQuantity() float64`

GetMaxQuantity returns the MaxQuantity field if non-nil, zero value otherwise.

### GetMaxQuantityOk

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetMaxQuantityOk() (*float64, bool)`

GetMaxQuantityOk returns a tuple with the MaxQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxQuantity

`func (o *SupplyItemsApiUpdateSupplyItemResponse) SetMaxQuantity(v float64)`

SetMaxQuantity sets MaxQuantity field to given value.

### HasMaxQuantity

`func (o *SupplyItemsApiUpdateSupplyItemResponse) HasMaxQuantity() bool`

HasMaxQuantity returns a boolean if a field has been set.

### GetMinQuantity

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetMinQuantity() float64`

GetMinQuantity returns the MinQuantity field if non-nil, zero value otherwise.

### GetMinQuantityOk

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetMinQuantityOk() (*float64, bool)`

GetMinQuantityOk returns a tuple with the MinQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinQuantity

`func (o *SupplyItemsApiUpdateSupplyItemResponse) SetMinQuantity(v float64)`

SetMinQuantity sets MinQuantity field to given value.

### HasMinQuantity

`func (o *SupplyItemsApiUpdateSupplyItemResponse) HasMinQuantity() bool`

HasMinQuantity returns a boolean if a field has been set.

### GetNote

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *SupplyItemsApiUpdateSupplyItemResponse) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *SupplyItemsApiUpdateSupplyItemResponse) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetUpdateWhenReceived

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetUpdateWhenReceived() bool`

GetUpdateWhenReceived returns the UpdateWhenReceived field if non-nil, zero value otherwise.

### GetUpdateWhenReceivedOk

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetUpdateWhenReceivedOk() (*bool, bool)`

GetUpdateWhenReceivedOk returns a tuple with the UpdateWhenReceived field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdateWhenReceived

`func (o *SupplyItemsApiUpdateSupplyItemResponse) SetUpdateWhenReceived(v bool)`

SetUpdateWhenReceived sets UpdateWhenReceived field to given value.

### HasUpdateWhenReceived

`func (o *SupplyItemsApiUpdateSupplyItemResponse) HasUpdateWhenReceived() bool`

HasUpdateWhenReceived returns a boolean if a field has been set.

### GetActive

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *SupplyItemsApiUpdateSupplyItemResponse) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *SupplyItemsApiUpdateSupplyItemResponse) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetAverageCost

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetAverageCost() float64`

GetAverageCost returns the AverageCost field if non-nil, zero value otherwise.

### GetAverageCostOk

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetAverageCostOk() (*float64, bool)`

GetAverageCostOk returns a tuple with the AverageCost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAverageCost

`func (o *SupplyItemsApiUpdateSupplyItemResponse) SetAverageCost(v float64)`

SetAverageCost sets AverageCost field to given value.

### HasAverageCost

`func (o *SupplyItemsApiUpdateSupplyItemResponse) HasAverageCost() bool`

HasAverageCost returns a boolean if a field has been set.

### GetResponsiblePersonId

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetResponsiblePersonId() string`

GetResponsiblePersonId returns the ResponsiblePersonId field if non-nil, zero value otherwise.

### GetResponsiblePersonIdOk

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetResponsiblePersonIdOk() (*string, bool)`

GetResponsiblePersonIdOk returns a tuple with the ResponsiblePersonId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResponsiblePersonId

`func (o *SupplyItemsApiUpdateSupplyItemResponse) SetResponsiblePersonId(v string)`

SetResponsiblePersonId sets ResponsiblePersonId field to given value.

### HasResponsiblePersonId

`func (o *SupplyItemsApiUpdateSupplyItemResponse) HasResponsiblePersonId() bool`

HasResponsiblePersonId returns a boolean if a field has been set.

### GetVendorManaged

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetVendorManaged() bool`

GetVendorManaged returns the VendorManaged field if non-nil, zero value otherwise.

### GetVendorManagedOk

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetVendorManagedOk() (*bool, bool)`

GetVendorManagedOk returns a tuple with the VendorManaged field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVendorManaged

`func (o *SupplyItemsApiUpdateSupplyItemResponse) SetVendorManaged(v bool)`

SetVendorManaged sets VendorManaged field to given value.

### HasVendorManaged

`func (o *SupplyItemsApiUpdateSupplyItemResponse) HasVendorManaged() bool`

HasVendorManaged returns a boolean if a field has been set.

### GetCommodity

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetCommodity() string`

GetCommodity returns the Commodity field if non-nil, zero value otherwise.

### GetCommodityOk

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetCommodityOk() (*string, bool)`

GetCommodityOk returns a tuple with the Commodity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCommodity

`func (o *SupplyItemsApiUpdateSupplyItemResponse) SetCommodity(v string)`

SetCommodity sets Commodity field to given value.

### HasCommodity

`func (o *SupplyItemsApiUpdateSupplyItemResponse) HasCommodity() bool`

HasCommodity returns a boolean if a field has been set.

### GetCountryOfOrigin

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetCountryOfOrigin() string`

GetCountryOfOrigin returns the CountryOfOrigin field if non-nil, zero value otherwise.

### GetCountryOfOriginOk

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetCountryOfOriginOk() (*string, bool)`

GetCountryOfOriginOk returns a tuple with the CountryOfOrigin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryOfOrigin

`func (o *SupplyItemsApiUpdateSupplyItemResponse) SetCountryOfOrigin(v string)`

SetCountryOfOrigin sets CountryOfOrigin field to given value.

### HasCountryOfOrigin

`func (o *SupplyItemsApiUpdateSupplyItemResponse) HasCountryOfOrigin() bool`

HasCountryOfOrigin returns a boolean if a field has been set.

### GetConsignment

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetConsignment() bool`

GetConsignment returns the Consignment field if non-nil, zero value otherwise.

### GetConsignmentOk

`func (o *SupplyItemsApiUpdateSupplyItemResponse) GetConsignmentOk() (*bool, bool)`

GetConsignmentOk returns a tuple with the Consignment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsignment

`func (o *SupplyItemsApiUpdateSupplyItemResponse) SetConsignment(v bool)`

SetConsignment sets Consignment field to given value.

### HasConsignment

`func (o *SupplyItemsApiUpdateSupplyItemResponse) HasConsignment() bool`

HasConsignment returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


