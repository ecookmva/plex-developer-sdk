# SupplyItemsApiCreateSupplyItem201Response

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

### NewSupplyItemsApiCreateSupplyItem201Response

`func NewSupplyItemsApiCreateSupplyItem201Response() *SupplyItemsApiCreateSupplyItem201Response`

NewSupplyItemsApiCreateSupplyItem201Response instantiates a new SupplyItemsApiCreateSupplyItem201Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSupplyItemsApiCreateSupplyItem201ResponseWithDefaults

`func NewSupplyItemsApiCreateSupplyItem201ResponseWithDefaults() *SupplyItemsApiCreateSupplyItem201Response`

NewSupplyItemsApiCreateSupplyItem201ResponseWithDefaults instantiates a new SupplyItemsApiCreateSupplyItem201Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SupplyItemsApiCreateSupplyItem201Response) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *SupplyItemsApiCreateSupplyItem201Response) HasId() bool`

HasId returns a boolean if a field has been set.

### GetSupplyItemNumber

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetSupplyItemNumber() string`

GetSupplyItemNumber returns the SupplyItemNumber field if non-nil, zero value otherwise.

### GetSupplyItemNumberOk

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetSupplyItemNumberOk() (*string, bool)`

GetSupplyItemNumberOk returns a tuple with the SupplyItemNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplyItemNumber

`func (o *SupplyItemsApiCreateSupplyItem201Response) SetSupplyItemNumber(v string)`

SetSupplyItemNumber sets SupplyItemNumber field to given value.

### HasSupplyItemNumber

`func (o *SupplyItemsApiCreateSupplyItem201Response) HasSupplyItemNumber() bool`

HasSupplyItemNumber returns a boolean if a field has been set.

### GetType

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *SupplyItemsApiCreateSupplyItem201Response) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *SupplyItemsApiCreateSupplyItem201Response) HasType() bool`

HasType returns a boolean if a field has been set.

### GetCategory

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetCategory() string`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetCategoryOk() (*string, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *SupplyItemsApiCreateSupplyItem201Response) SetCategory(v string)`

SetCategory sets Category field to given value.

### HasCategory

`func (o *SupplyItemsApiCreateSupplyItem201Response) HasCategory() bool`

HasCategory returns a boolean if a field has been set.

### GetPriority

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetPriority() string`

GetPriority returns the Priority field if non-nil, zero value otherwise.

### GetPriorityOk

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetPriorityOk() (*string, bool)`

GetPriorityOk returns a tuple with the Priority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriority

`func (o *SupplyItemsApiCreateSupplyItem201Response) SetPriority(v string)`

SetPriority sets Priority field to given value.

### HasPriority

`func (o *SupplyItemsApiCreateSupplyItem201Response) HasPriority() bool`

HasPriority returns a boolean if a field has been set.

### GetGroup

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetGroup() string`

GetGroup returns the Group field if non-nil, zero value otherwise.

### GetGroupOk

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetGroupOk() (*string, bool)`

GetGroupOk returns a tuple with the Group field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroup

`func (o *SupplyItemsApiCreateSupplyItem201Response) SetGroup(v string)`

SetGroup sets Group field to given value.

### HasGroup

`func (o *SupplyItemsApiCreateSupplyItem201Response) HasGroup() bool`

HasGroup returns a boolean if a field has been set.

### GetDescription

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *SupplyItemsApiCreateSupplyItem201Response) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *SupplyItemsApiCreateSupplyItem201Response) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetCustomerUnitPrice

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetCustomerUnitPrice() float64`

GetCustomerUnitPrice returns the CustomerUnitPrice field if non-nil, zero value otherwise.

### GetCustomerUnitPriceOk

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetCustomerUnitPriceOk() (*float64, bool)`

GetCustomerUnitPriceOk returns a tuple with the CustomerUnitPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerUnitPrice

`func (o *SupplyItemsApiCreateSupplyItem201Response) SetCustomerUnitPrice(v float64)`

SetCustomerUnitPrice sets CustomerUnitPrice field to given value.

### HasCustomerUnitPrice

`func (o *SupplyItemsApiCreateSupplyItem201Response) HasCustomerUnitPrice() bool`

HasCustomerUnitPrice returns a boolean if a field has been set.

### GetInventoryUnit

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetInventoryUnit() string`

GetInventoryUnit returns the InventoryUnit field if non-nil, zero value otherwise.

### GetInventoryUnitOk

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetInventoryUnitOk() (*string, bool)`

GetInventoryUnitOk returns a tuple with the InventoryUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInventoryUnit

`func (o *SupplyItemsApiCreateSupplyItem201Response) SetInventoryUnit(v string)`

SetInventoryUnit sets InventoryUnit field to given value.

### HasInventoryUnit

`func (o *SupplyItemsApiCreateSupplyItem201Response) HasInventoryUnit() bool`

HasInventoryUnit returns a boolean if a field has been set.

### GetBriefDescription

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetBriefDescription() string`

GetBriefDescription returns the BriefDescription field if non-nil, zero value otherwise.

### GetBriefDescriptionOk

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetBriefDescriptionOk() (*string, bool)`

GetBriefDescriptionOk returns a tuple with the BriefDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBriefDescription

`func (o *SupplyItemsApiCreateSupplyItem201Response) SetBriefDescription(v string)`

SetBriefDescription sets BriefDescription field to given value.

### HasBriefDescription

`func (o *SupplyItemsApiCreateSupplyItem201Response) HasBriefDescription() bool`

HasBriefDescription returns a boolean if a field has been set.

### GetAccountId

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetAccountId() string`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetAccountIdOk() (*string, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *SupplyItemsApiCreateSupplyItem201Response) SetAccountId(v string)`

SetAccountId sets AccountId field to given value.

### HasAccountId

`func (o *SupplyItemsApiCreateSupplyItem201Response) HasAccountId() bool`

HasAccountId returns a boolean if a field has been set.

### GetManufacturerCode

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetManufacturerCode() string`

GetManufacturerCode returns the ManufacturerCode field if non-nil, zero value otherwise.

### GetManufacturerCodeOk

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetManufacturerCodeOk() (*string, bool)`

GetManufacturerCodeOk returns a tuple with the ManufacturerCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManufacturerCode

`func (o *SupplyItemsApiCreateSupplyItem201Response) SetManufacturerCode(v string)`

SetManufacturerCode sets ManufacturerCode field to given value.

### HasManufacturerCode

`func (o *SupplyItemsApiCreateSupplyItem201Response) HasManufacturerCode() bool`

HasManufacturerCode returns a boolean if a field has been set.

### GetSupplierId

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetSupplierId() string`

GetSupplierId returns the SupplierId field if non-nil, zero value otherwise.

### GetSupplierIdOk

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetSupplierIdOk() (*string, bool)`

GetSupplierIdOk returns a tuple with the SupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierId

`func (o *SupplyItemsApiCreateSupplyItem201Response) SetSupplierId(v string)`

SetSupplierId sets SupplierId field to given value.

### HasSupplierId

`func (o *SupplyItemsApiCreateSupplyItem201Response) HasSupplierId() bool`

HasSupplierId returns a boolean if a field has been set.

### GetManufacturerItemNumber

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetManufacturerItemNumber() string`

GetManufacturerItemNumber returns the ManufacturerItemNumber field if non-nil, zero value otherwise.

### GetManufacturerItemNumberOk

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetManufacturerItemNumberOk() (*string, bool)`

GetManufacturerItemNumberOk returns a tuple with the ManufacturerItemNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManufacturerItemNumber

`func (o *SupplyItemsApiCreateSupplyItem201Response) SetManufacturerItemNumber(v string)`

SetManufacturerItemNumber sets ManufacturerItemNumber field to given value.

### HasManufacturerItemNumber

`func (o *SupplyItemsApiCreateSupplyItem201Response) HasManufacturerItemNumber() bool`

HasManufacturerItemNumber returns a boolean if a field has been set.

### GetManufacturerItemRevision

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetManufacturerItemRevision() string`

GetManufacturerItemRevision returns the ManufacturerItemRevision field if non-nil, zero value otherwise.

### GetManufacturerItemRevisionOk

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetManufacturerItemRevisionOk() (*string, bool)`

GetManufacturerItemRevisionOk returns a tuple with the ManufacturerItemRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManufacturerItemRevision

`func (o *SupplyItemsApiCreateSupplyItem201Response) SetManufacturerItemRevision(v string)`

SetManufacturerItemRevision sets ManufacturerItemRevision field to given value.

### HasManufacturerItemRevision

`func (o *SupplyItemsApiCreateSupplyItem201Response) HasManufacturerItemRevision() bool`

HasManufacturerItemRevision returns a boolean if a field has been set.

### GetManufacturerText

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetManufacturerText() string`

GetManufacturerText returns the ManufacturerText field if non-nil, zero value otherwise.

### GetManufacturerTextOk

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetManufacturerTextOk() (*string, bool)`

GetManufacturerTextOk returns a tuple with the ManufacturerText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManufacturerText

`func (o *SupplyItemsApiCreateSupplyItem201Response) SetManufacturerText(v string)`

SetManufacturerText sets ManufacturerText field to given value.

### HasManufacturerText

`func (o *SupplyItemsApiCreateSupplyItem201Response) HasManufacturerText() bool`

HasManufacturerText returns a boolean if a field has been set.

### GetCreatedDate

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *SupplyItemsApiCreateSupplyItem201Response) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *SupplyItemsApiCreateSupplyItem201Response) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.

### GetCreatedById

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetCreatedById() string`

GetCreatedById returns the CreatedById field if non-nil, zero value otherwise.

### GetCreatedByIdOk

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetCreatedByIdOk() (*string, bool)`

GetCreatedByIdOk returns a tuple with the CreatedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedById

`func (o *SupplyItemsApiCreateSupplyItem201Response) SetCreatedById(v string)`

SetCreatedById sets CreatedById field to given value.

### HasCreatedById

`func (o *SupplyItemsApiCreateSupplyItem201Response) HasCreatedById() bool`

HasCreatedById returns a boolean if a field has been set.

### GetModifiedDate

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetModifiedDate() time.Time`

GetModifiedDate returns the ModifiedDate field if non-nil, zero value otherwise.

### GetModifiedDateOk

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetModifiedDateOk() (*time.Time, bool)`

GetModifiedDateOk returns a tuple with the ModifiedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDate

`func (o *SupplyItemsApiCreateSupplyItem201Response) SetModifiedDate(v time.Time)`

SetModifiedDate sets ModifiedDate field to given value.

### HasModifiedDate

`func (o *SupplyItemsApiCreateSupplyItem201Response) HasModifiedDate() bool`

HasModifiedDate returns a boolean if a field has been set.

### GetModifiedById

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *SupplyItemsApiCreateSupplyItem201Response) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *SupplyItemsApiCreateSupplyItem201Response) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetTaxCodeNumber

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetTaxCodeNumber() int32`

GetTaxCodeNumber returns the TaxCodeNumber field if non-nil, zero value otherwise.

### GetTaxCodeNumberOk

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetTaxCodeNumberOk() (*int32, bool)`

GetTaxCodeNumberOk returns a tuple with the TaxCodeNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxCodeNumber

`func (o *SupplyItemsApiCreateSupplyItem201Response) SetTaxCodeNumber(v int32)`

SetTaxCodeNumber sets TaxCodeNumber field to given value.

### HasTaxCodeNumber

`func (o *SupplyItemsApiCreateSupplyItem201Response) HasTaxCodeNumber() bool`

HasTaxCodeNumber returns a boolean if a field has been set.

### GetMaxQuantity

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetMaxQuantity() float64`

GetMaxQuantity returns the MaxQuantity field if non-nil, zero value otherwise.

### GetMaxQuantityOk

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetMaxQuantityOk() (*float64, bool)`

GetMaxQuantityOk returns a tuple with the MaxQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxQuantity

`func (o *SupplyItemsApiCreateSupplyItem201Response) SetMaxQuantity(v float64)`

SetMaxQuantity sets MaxQuantity field to given value.

### HasMaxQuantity

`func (o *SupplyItemsApiCreateSupplyItem201Response) HasMaxQuantity() bool`

HasMaxQuantity returns a boolean if a field has been set.

### GetMinQuantity

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetMinQuantity() float64`

GetMinQuantity returns the MinQuantity field if non-nil, zero value otherwise.

### GetMinQuantityOk

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetMinQuantityOk() (*float64, bool)`

GetMinQuantityOk returns a tuple with the MinQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinQuantity

`func (o *SupplyItemsApiCreateSupplyItem201Response) SetMinQuantity(v float64)`

SetMinQuantity sets MinQuantity field to given value.

### HasMinQuantity

`func (o *SupplyItemsApiCreateSupplyItem201Response) HasMinQuantity() bool`

HasMinQuantity returns a boolean if a field has been set.

### GetNote

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *SupplyItemsApiCreateSupplyItem201Response) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *SupplyItemsApiCreateSupplyItem201Response) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetUpdateWhenReceived

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetUpdateWhenReceived() bool`

GetUpdateWhenReceived returns the UpdateWhenReceived field if non-nil, zero value otherwise.

### GetUpdateWhenReceivedOk

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetUpdateWhenReceivedOk() (*bool, bool)`

GetUpdateWhenReceivedOk returns a tuple with the UpdateWhenReceived field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdateWhenReceived

`func (o *SupplyItemsApiCreateSupplyItem201Response) SetUpdateWhenReceived(v bool)`

SetUpdateWhenReceived sets UpdateWhenReceived field to given value.

### HasUpdateWhenReceived

`func (o *SupplyItemsApiCreateSupplyItem201Response) HasUpdateWhenReceived() bool`

HasUpdateWhenReceived returns a boolean if a field has been set.

### GetActive

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *SupplyItemsApiCreateSupplyItem201Response) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *SupplyItemsApiCreateSupplyItem201Response) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetAverageCost

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetAverageCost() float64`

GetAverageCost returns the AverageCost field if non-nil, zero value otherwise.

### GetAverageCostOk

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetAverageCostOk() (*float64, bool)`

GetAverageCostOk returns a tuple with the AverageCost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAverageCost

`func (o *SupplyItemsApiCreateSupplyItem201Response) SetAverageCost(v float64)`

SetAverageCost sets AverageCost field to given value.

### HasAverageCost

`func (o *SupplyItemsApiCreateSupplyItem201Response) HasAverageCost() bool`

HasAverageCost returns a boolean if a field has been set.

### GetResponsiblePersonId

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetResponsiblePersonId() string`

GetResponsiblePersonId returns the ResponsiblePersonId field if non-nil, zero value otherwise.

### GetResponsiblePersonIdOk

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetResponsiblePersonIdOk() (*string, bool)`

GetResponsiblePersonIdOk returns a tuple with the ResponsiblePersonId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResponsiblePersonId

`func (o *SupplyItemsApiCreateSupplyItem201Response) SetResponsiblePersonId(v string)`

SetResponsiblePersonId sets ResponsiblePersonId field to given value.

### HasResponsiblePersonId

`func (o *SupplyItemsApiCreateSupplyItem201Response) HasResponsiblePersonId() bool`

HasResponsiblePersonId returns a boolean if a field has been set.

### GetVendorManaged

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetVendorManaged() bool`

GetVendorManaged returns the VendorManaged field if non-nil, zero value otherwise.

### GetVendorManagedOk

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetVendorManagedOk() (*bool, bool)`

GetVendorManagedOk returns a tuple with the VendorManaged field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVendorManaged

`func (o *SupplyItemsApiCreateSupplyItem201Response) SetVendorManaged(v bool)`

SetVendorManaged sets VendorManaged field to given value.

### HasVendorManaged

`func (o *SupplyItemsApiCreateSupplyItem201Response) HasVendorManaged() bool`

HasVendorManaged returns a boolean if a field has been set.

### GetCommodity

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetCommodity() string`

GetCommodity returns the Commodity field if non-nil, zero value otherwise.

### GetCommodityOk

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetCommodityOk() (*string, bool)`

GetCommodityOk returns a tuple with the Commodity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCommodity

`func (o *SupplyItemsApiCreateSupplyItem201Response) SetCommodity(v string)`

SetCommodity sets Commodity field to given value.

### HasCommodity

`func (o *SupplyItemsApiCreateSupplyItem201Response) HasCommodity() bool`

HasCommodity returns a boolean if a field has been set.

### GetCountryOfOrigin

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetCountryOfOrigin() string`

GetCountryOfOrigin returns the CountryOfOrigin field if non-nil, zero value otherwise.

### GetCountryOfOriginOk

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetCountryOfOriginOk() (*string, bool)`

GetCountryOfOriginOk returns a tuple with the CountryOfOrigin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryOfOrigin

`func (o *SupplyItemsApiCreateSupplyItem201Response) SetCountryOfOrigin(v string)`

SetCountryOfOrigin sets CountryOfOrigin field to given value.

### HasCountryOfOrigin

`func (o *SupplyItemsApiCreateSupplyItem201Response) HasCountryOfOrigin() bool`

HasCountryOfOrigin returns a boolean if a field has been set.

### GetConsignment

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetConsignment() bool`

GetConsignment returns the Consignment field if non-nil, zero value otherwise.

### GetConsignmentOk

`func (o *SupplyItemsApiCreateSupplyItem201Response) GetConsignmentOk() (*bool, bool)`

GetConsignmentOk returns a tuple with the Consignment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsignment

`func (o *SupplyItemsApiCreateSupplyItem201Response) SetConsignment(v bool)`

SetConsignment sets Consignment field to given value.

### HasConsignment

`func (o *SupplyItemsApiCreateSupplyItem201Response) HasConsignment() bool`

HasConsignment returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


