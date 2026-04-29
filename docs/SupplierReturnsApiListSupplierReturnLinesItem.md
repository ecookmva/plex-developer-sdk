# SupplierReturnsApiListSupplierReturnLinesItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Reason** | Pointer to **string** | Setup Table: Supplier Return Reason | [optional] 
**Category** | Pointer to **string** | Setup Table: Supplier Return Category | [optional] 
**CreatedById** | Pointer to **string** | The ID of the user who created the record. | [optional] 
**CreatedDate** | Pointer to **time.Time** | The date on which the record was created. | [optional] 
**Quantity** | Pointer to **float64** | Quantity of items to be returned. | [optional] 
**ModifiedById** | Pointer to **string** | The ID of the user who last modified the record. | [optional] 
**ModifiedDate** | Pointer to **time.Time** | The date and time of the last modification to the record. | [optional] 
**PartId** | Pointer to **string** | ID of the part being returned. | [optional] 
**AuthorizationNumber** | Pointer to **string** | Supplier Return Authorization Number | [optional] 
**Unit** | Pointer to **string** | The unit of measure for the Item. | [optional] 
**DefectType** | Pointer to **string** | Setup Table: Type of Defect. | [optional] 
**InvoiceUnitPrice** | Pointer to **float64** | Price per unit from the invoice. | [optional] 
**InvoiceQuantity** | Pointer to **float64** | Quantity of units from the invoice. | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**Note** | Pointer to **string** |  | [optional] 
**AssembledPartId** | Pointer to **string** |  | [optional] 
**PriceLookupMethod** | Pointer to **string** |  | [optional] 
**AdditionalCharge** | Pointer to **float64** | Additional charges on the Return. | [optional] 
**OperationCode** | Pointer to **string** |  | [optional] 
**AssembledOperationCode** | Pointer to **string** |  | [optional] 
**SupplyItemId** | Pointer to **string** | ID of the Supply Item. | [optional] 

## Methods

### NewSupplierReturnsApiListSupplierReturnLinesItem

`func NewSupplierReturnsApiListSupplierReturnLinesItem() *SupplierReturnsApiListSupplierReturnLinesItem`

NewSupplierReturnsApiListSupplierReturnLinesItem instantiates a new SupplierReturnsApiListSupplierReturnLinesItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSupplierReturnsApiListSupplierReturnLinesItemWithDefaults

`func NewSupplierReturnsApiListSupplierReturnLinesItemWithDefaults() *SupplierReturnsApiListSupplierReturnLinesItem`

NewSupplierReturnsApiListSupplierReturnLinesItemWithDefaults instantiates a new SupplierReturnsApiListSupplierReturnLinesItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetReason

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) SetReason(v string)`

SetReason sets Reason field to given value.

### HasReason

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) HasReason() bool`

HasReason returns a boolean if a field has been set.

### GetCategory

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) GetCategory() string`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) GetCategoryOk() (*string, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) SetCategory(v string)`

SetCategory sets Category field to given value.

### HasCategory

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) HasCategory() bool`

HasCategory returns a boolean if a field has been set.

### GetCreatedById

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) GetCreatedById() string`

GetCreatedById returns the CreatedById field if non-nil, zero value otherwise.

### GetCreatedByIdOk

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) GetCreatedByIdOk() (*string, bool)`

GetCreatedByIdOk returns a tuple with the CreatedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedById

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) SetCreatedById(v string)`

SetCreatedById sets CreatedById field to given value.

### HasCreatedById

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) HasCreatedById() bool`

HasCreatedById returns a boolean if a field has been set.

### GetCreatedDate

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.

### GetQuantity

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetModifiedById

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetModifiedDate

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) GetModifiedDate() time.Time`

GetModifiedDate returns the ModifiedDate field if non-nil, zero value otherwise.

### GetModifiedDateOk

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) GetModifiedDateOk() (*time.Time, bool)`

GetModifiedDateOk returns a tuple with the ModifiedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDate

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) SetModifiedDate(v time.Time)`

SetModifiedDate sets ModifiedDate field to given value.

### HasModifiedDate

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) HasModifiedDate() bool`

HasModifiedDate returns a boolean if a field has been set.

### GetPartId

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetAuthorizationNumber

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) GetAuthorizationNumber() string`

GetAuthorizationNumber returns the AuthorizationNumber field if non-nil, zero value otherwise.

### GetAuthorizationNumberOk

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) GetAuthorizationNumberOk() (*string, bool)`

GetAuthorizationNumberOk returns a tuple with the AuthorizationNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthorizationNumber

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) SetAuthorizationNumber(v string)`

SetAuthorizationNumber sets AuthorizationNumber field to given value.

### HasAuthorizationNumber

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) HasAuthorizationNumber() bool`

HasAuthorizationNumber returns a boolean if a field has been set.

### GetUnit

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) GetUnit() string`

GetUnit returns the Unit field if non-nil, zero value otherwise.

### GetUnitOk

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) GetUnitOk() (*string, bool)`

GetUnitOk returns a tuple with the Unit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnit

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) SetUnit(v string)`

SetUnit sets Unit field to given value.

### HasUnit

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) HasUnit() bool`

HasUnit returns a boolean if a field has been set.

### GetDefectType

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) GetDefectType() string`

GetDefectType returns the DefectType field if non-nil, zero value otherwise.

### GetDefectTypeOk

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) GetDefectTypeOk() (*string, bool)`

GetDefectTypeOk returns a tuple with the DefectType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefectType

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) SetDefectType(v string)`

SetDefectType sets DefectType field to given value.

### HasDefectType

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) HasDefectType() bool`

HasDefectType returns a boolean if a field has been set.

### GetInvoiceUnitPrice

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) GetInvoiceUnitPrice() float64`

GetInvoiceUnitPrice returns the InvoiceUnitPrice field if non-nil, zero value otherwise.

### GetInvoiceUnitPriceOk

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) GetInvoiceUnitPriceOk() (*float64, bool)`

GetInvoiceUnitPriceOk returns a tuple with the InvoiceUnitPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceUnitPrice

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) SetInvoiceUnitPrice(v float64)`

SetInvoiceUnitPrice sets InvoiceUnitPrice field to given value.

### HasInvoiceUnitPrice

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) HasInvoiceUnitPrice() bool`

HasInvoiceUnitPrice returns a boolean if a field has been set.

### GetInvoiceQuantity

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) GetInvoiceQuantity() float64`

GetInvoiceQuantity returns the InvoiceQuantity field if non-nil, zero value otherwise.

### GetInvoiceQuantityOk

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) GetInvoiceQuantityOk() (*float64, bool)`

GetInvoiceQuantityOk returns a tuple with the InvoiceQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceQuantity

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) SetInvoiceQuantity(v float64)`

SetInvoiceQuantity sets InvoiceQuantity field to given value.

### HasInvoiceQuantity

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) HasInvoiceQuantity() bool`

HasInvoiceQuantity returns a boolean if a field has been set.

### GetDescription

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetNote

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetAssembledPartId

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) GetAssembledPartId() string`

GetAssembledPartId returns the AssembledPartId field if non-nil, zero value otherwise.

### GetAssembledPartIdOk

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) GetAssembledPartIdOk() (*string, bool)`

GetAssembledPartIdOk returns a tuple with the AssembledPartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssembledPartId

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) SetAssembledPartId(v string)`

SetAssembledPartId sets AssembledPartId field to given value.

### HasAssembledPartId

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) HasAssembledPartId() bool`

HasAssembledPartId returns a boolean if a field has been set.

### GetPriceLookupMethod

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) GetPriceLookupMethod() string`

GetPriceLookupMethod returns the PriceLookupMethod field if non-nil, zero value otherwise.

### GetPriceLookupMethodOk

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) GetPriceLookupMethodOk() (*string, bool)`

GetPriceLookupMethodOk returns a tuple with the PriceLookupMethod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriceLookupMethod

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) SetPriceLookupMethod(v string)`

SetPriceLookupMethod sets PriceLookupMethod field to given value.

### HasPriceLookupMethod

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) HasPriceLookupMethod() bool`

HasPriceLookupMethod returns a boolean if a field has been set.

### GetAdditionalCharge

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) GetAdditionalCharge() float64`

GetAdditionalCharge returns the AdditionalCharge field if non-nil, zero value otherwise.

### GetAdditionalChargeOk

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) GetAdditionalChargeOk() (*float64, bool)`

GetAdditionalChargeOk returns a tuple with the AdditionalCharge field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdditionalCharge

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) SetAdditionalCharge(v float64)`

SetAdditionalCharge sets AdditionalCharge field to given value.

### HasAdditionalCharge

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) HasAdditionalCharge() bool`

HasAdditionalCharge returns a boolean if a field has been set.

### GetOperationCode

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) GetOperationCode() string`

GetOperationCode returns the OperationCode field if non-nil, zero value otherwise.

### GetOperationCodeOk

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) GetOperationCodeOk() (*string, bool)`

GetOperationCodeOk returns a tuple with the OperationCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationCode

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) SetOperationCode(v string)`

SetOperationCode sets OperationCode field to given value.

### HasOperationCode

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) HasOperationCode() bool`

HasOperationCode returns a boolean if a field has been set.

### GetAssembledOperationCode

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) GetAssembledOperationCode() string`

GetAssembledOperationCode returns the AssembledOperationCode field if non-nil, zero value otherwise.

### GetAssembledOperationCodeOk

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) GetAssembledOperationCodeOk() (*string, bool)`

GetAssembledOperationCodeOk returns a tuple with the AssembledOperationCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssembledOperationCode

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) SetAssembledOperationCode(v string)`

SetAssembledOperationCode sets AssembledOperationCode field to given value.

### HasAssembledOperationCode

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) HasAssembledOperationCode() bool`

HasAssembledOperationCode returns a boolean if a field has been set.

### GetSupplyItemId

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) GetSupplyItemId() string`

GetSupplyItemId returns the SupplyItemId field if non-nil, zero value otherwise.

### GetSupplyItemIdOk

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) GetSupplyItemIdOk() (*string, bool)`

GetSupplyItemIdOk returns a tuple with the SupplyItemId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplyItemId

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) SetSupplyItemId(v string)`

SetSupplyItemId sets SupplyItemId field to given value.

### HasSupplyItemId

`func (o *SupplierReturnsApiListSupplierReturnLinesItem) HasSupplyItemId() bool`

HasSupplyItemId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


