# PurchaseOrdersApiListLineItemsItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | A unique identifier for the Line Item. | [optional] 
**LineItemNumber** | Pointer to **int32** | PO Line Item Number | [optional] 
**Status** | Pointer to **string** | Setup Table: PO Line Item Status | [optional] 
**ExpirationDate** | Pointer to **time.Time** | The Expiration Date of the Line Item. | [optional] 
**Unit** | Pointer to **string** |  | [optional] 
**OrderUnit** | Pointer to **string** | The unit of measure for the part on the PO. | [optional] 
**Description** | Pointer to **string** | The description of the product or service being ordered. | [optional] 
**UnitPrice** | Pointer to **float64** | Price per unit. | [optional] 
**EstimatedPrice** | Pointer to **bool** | If the unit price is estimated. | [optional] 
**AccountId** | Pointer to **string** | The ID of the General Ledger account associated with the PO Line. | [optional] 
**Manufacturer** | Pointer to **string** | Application: Manufacturers | [optional] 
**ManufacturerPartNumber** | Pointer to **string** | Manufacturer Part Number, this may be different than the Plex part number. | [optional] 
**SupplierPartNumber** | Pointer to **string** | Supplier Part Number, this may be different than the Plex part number. | [optional] 
**ItemId** | Pointer to **string** | A unique identifier for the supply item. | [optional] 
**TaxCode** | Pointer to **string** | Application: Tax Codes | [optional] 
**PartId** | Pointer to **string** | A unique identifier for the part. | [optional] 
**OperationCode** | Pointer to **string** | Application: Operation List | [optional] 
**PartOperationId** | Pointer to **string** | A unique identifier for the part operation. | [optional] 
**RouteToEmployeeId** | Pointer to **string** | The Employee ID to which the request is routed. | [optional] 
**RequestedById** | Pointer to **string** | The ID of the user who requested the record. | [optional] 
**WeightUnit** | Pointer to **string** |  | [optional] 
**WeightConversion** | Pointer to **float64** |  | [optional] 
**InternalNote** | Pointer to **string** | A note that can only be viewed on the Line Item Detail form. | [optional] 
**Note** | Pointer to **string** | A note for the line item that is displayed in grid records. | [optional] 
**Building** | Pointer to **string** | Application: Buildings | [optional] 
**Department** | Pointer to **string** | Application: Department List | [optional] 
**BlanketQuantity** | Pointer to **float64** | The blanket order quantity for the line item. | [optional] 
**CreatedDate** | Pointer to **time.Time** | The date on which the record was created. | [optional] 
**ModifiedById** | Pointer to **string** | The ID of the user who last modified the record. | [optional] 
**ModifiedDate** | Pointer to **time.Time** | The date on which the record was last modified. | [optional] 

## Methods

### NewPurchaseOrdersApiListLineItemsItem

`func NewPurchaseOrdersApiListLineItemsItem() *PurchaseOrdersApiListLineItemsItem`

NewPurchaseOrdersApiListLineItemsItem instantiates a new PurchaseOrdersApiListLineItemsItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPurchaseOrdersApiListLineItemsItemWithDefaults

`func NewPurchaseOrdersApiListLineItemsItemWithDefaults() *PurchaseOrdersApiListLineItemsItem`

NewPurchaseOrdersApiListLineItemsItemWithDefaults instantiates a new PurchaseOrdersApiListLineItemsItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *PurchaseOrdersApiListLineItemsItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PurchaseOrdersApiListLineItemsItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PurchaseOrdersApiListLineItemsItem) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *PurchaseOrdersApiListLineItemsItem) HasId() bool`

HasId returns a boolean if a field has been set.

### GetLineItemNumber

`func (o *PurchaseOrdersApiListLineItemsItem) GetLineItemNumber() int32`

GetLineItemNumber returns the LineItemNumber field if non-nil, zero value otherwise.

### GetLineItemNumberOk

`func (o *PurchaseOrdersApiListLineItemsItem) GetLineItemNumberOk() (*int32, bool)`

GetLineItemNumberOk returns a tuple with the LineItemNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineItemNumber

`func (o *PurchaseOrdersApiListLineItemsItem) SetLineItemNumber(v int32)`

SetLineItemNumber sets LineItemNumber field to given value.

### HasLineItemNumber

`func (o *PurchaseOrdersApiListLineItemsItem) HasLineItemNumber() bool`

HasLineItemNumber returns a boolean if a field has been set.

### GetStatus

`func (o *PurchaseOrdersApiListLineItemsItem) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PurchaseOrdersApiListLineItemsItem) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PurchaseOrdersApiListLineItemsItem) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *PurchaseOrdersApiListLineItemsItem) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetExpirationDate

`func (o *PurchaseOrdersApiListLineItemsItem) GetExpirationDate() time.Time`

GetExpirationDate returns the ExpirationDate field if non-nil, zero value otherwise.

### GetExpirationDateOk

`func (o *PurchaseOrdersApiListLineItemsItem) GetExpirationDateOk() (*time.Time, bool)`

GetExpirationDateOk returns a tuple with the ExpirationDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpirationDate

`func (o *PurchaseOrdersApiListLineItemsItem) SetExpirationDate(v time.Time)`

SetExpirationDate sets ExpirationDate field to given value.

### HasExpirationDate

`func (o *PurchaseOrdersApiListLineItemsItem) HasExpirationDate() bool`

HasExpirationDate returns a boolean if a field has been set.

### GetUnit

`func (o *PurchaseOrdersApiListLineItemsItem) GetUnit() string`

GetUnit returns the Unit field if non-nil, zero value otherwise.

### GetUnitOk

`func (o *PurchaseOrdersApiListLineItemsItem) GetUnitOk() (*string, bool)`

GetUnitOk returns a tuple with the Unit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnit

`func (o *PurchaseOrdersApiListLineItemsItem) SetUnit(v string)`

SetUnit sets Unit field to given value.

### HasUnit

`func (o *PurchaseOrdersApiListLineItemsItem) HasUnit() bool`

HasUnit returns a boolean if a field has been set.

### GetOrderUnit

`func (o *PurchaseOrdersApiListLineItemsItem) GetOrderUnit() string`

GetOrderUnit returns the OrderUnit field if non-nil, zero value otherwise.

### GetOrderUnitOk

`func (o *PurchaseOrdersApiListLineItemsItem) GetOrderUnitOk() (*string, bool)`

GetOrderUnitOk returns a tuple with the OrderUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderUnit

`func (o *PurchaseOrdersApiListLineItemsItem) SetOrderUnit(v string)`

SetOrderUnit sets OrderUnit field to given value.

### HasOrderUnit

`func (o *PurchaseOrdersApiListLineItemsItem) HasOrderUnit() bool`

HasOrderUnit returns a boolean if a field has been set.

### GetDescription

`func (o *PurchaseOrdersApiListLineItemsItem) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *PurchaseOrdersApiListLineItemsItem) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *PurchaseOrdersApiListLineItemsItem) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *PurchaseOrdersApiListLineItemsItem) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetUnitPrice

`func (o *PurchaseOrdersApiListLineItemsItem) GetUnitPrice() float64`

GetUnitPrice returns the UnitPrice field if non-nil, zero value otherwise.

### GetUnitPriceOk

`func (o *PurchaseOrdersApiListLineItemsItem) GetUnitPriceOk() (*float64, bool)`

GetUnitPriceOk returns a tuple with the UnitPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitPrice

`func (o *PurchaseOrdersApiListLineItemsItem) SetUnitPrice(v float64)`

SetUnitPrice sets UnitPrice field to given value.

### HasUnitPrice

`func (o *PurchaseOrdersApiListLineItemsItem) HasUnitPrice() bool`

HasUnitPrice returns a boolean if a field has been set.

### GetEstimatedPrice

`func (o *PurchaseOrdersApiListLineItemsItem) GetEstimatedPrice() bool`

GetEstimatedPrice returns the EstimatedPrice field if non-nil, zero value otherwise.

### GetEstimatedPriceOk

`func (o *PurchaseOrdersApiListLineItemsItem) GetEstimatedPriceOk() (*bool, bool)`

GetEstimatedPriceOk returns a tuple with the EstimatedPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEstimatedPrice

`func (o *PurchaseOrdersApiListLineItemsItem) SetEstimatedPrice(v bool)`

SetEstimatedPrice sets EstimatedPrice field to given value.

### HasEstimatedPrice

`func (o *PurchaseOrdersApiListLineItemsItem) HasEstimatedPrice() bool`

HasEstimatedPrice returns a boolean if a field has been set.

### GetAccountId

`func (o *PurchaseOrdersApiListLineItemsItem) GetAccountId() string`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *PurchaseOrdersApiListLineItemsItem) GetAccountIdOk() (*string, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *PurchaseOrdersApiListLineItemsItem) SetAccountId(v string)`

SetAccountId sets AccountId field to given value.

### HasAccountId

`func (o *PurchaseOrdersApiListLineItemsItem) HasAccountId() bool`

HasAccountId returns a boolean if a field has been set.

### GetManufacturer

`func (o *PurchaseOrdersApiListLineItemsItem) GetManufacturer() string`

GetManufacturer returns the Manufacturer field if non-nil, zero value otherwise.

### GetManufacturerOk

`func (o *PurchaseOrdersApiListLineItemsItem) GetManufacturerOk() (*string, bool)`

GetManufacturerOk returns a tuple with the Manufacturer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManufacturer

`func (o *PurchaseOrdersApiListLineItemsItem) SetManufacturer(v string)`

SetManufacturer sets Manufacturer field to given value.

### HasManufacturer

`func (o *PurchaseOrdersApiListLineItemsItem) HasManufacturer() bool`

HasManufacturer returns a boolean if a field has been set.

### GetManufacturerPartNumber

`func (o *PurchaseOrdersApiListLineItemsItem) GetManufacturerPartNumber() string`

GetManufacturerPartNumber returns the ManufacturerPartNumber field if non-nil, zero value otherwise.

### GetManufacturerPartNumberOk

`func (o *PurchaseOrdersApiListLineItemsItem) GetManufacturerPartNumberOk() (*string, bool)`

GetManufacturerPartNumberOk returns a tuple with the ManufacturerPartNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManufacturerPartNumber

`func (o *PurchaseOrdersApiListLineItemsItem) SetManufacturerPartNumber(v string)`

SetManufacturerPartNumber sets ManufacturerPartNumber field to given value.

### HasManufacturerPartNumber

`func (o *PurchaseOrdersApiListLineItemsItem) HasManufacturerPartNumber() bool`

HasManufacturerPartNumber returns a boolean if a field has been set.

### GetSupplierPartNumber

`func (o *PurchaseOrdersApiListLineItemsItem) GetSupplierPartNumber() string`

GetSupplierPartNumber returns the SupplierPartNumber field if non-nil, zero value otherwise.

### GetSupplierPartNumberOk

`func (o *PurchaseOrdersApiListLineItemsItem) GetSupplierPartNumberOk() (*string, bool)`

GetSupplierPartNumberOk returns a tuple with the SupplierPartNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierPartNumber

`func (o *PurchaseOrdersApiListLineItemsItem) SetSupplierPartNumber(v string)`

SetSupplierPartNumber sets SupplierPartNumber field to given value.

### HasSupplierPartNumber

`func (o *PurchaseOrdersApiListLineItemsItem) HasSupplierPartNumber() bool`

HasSupplierPartNumber returns a boolean if a field has been set.

### GetItemId

`func (o *PurchaseOrdersApiListLineItemsItem) GetItemId() string`

GetItemId returns the ItemId field if non-nil, zero value otherwise.

### GetItemIdOk

`func (o *PurchaseOrdersApiListLineItemsItem) GetItemIdOk() (*string, bool)`

GetItemIdOk returns a tuple with the ItemId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItemId

`func (o *PurchaseOrdersApiListLineItemsItem) SetItemId(v string)`

SetItemId sets ItemId field to given value.

### HasItemId

`func (o *PurchaseOrdersApiListLineItemsItem) HasItemId() bool`

HasItemId returns a boolean if a field has been set.

### GetTaxCode

`func (o *PurchaseOrdersApiListLineItemsItem) GetTaxCode() string`

GetTaxCode returns the TaxCode field if non-nil, zero value otherwise.

### GetTaxCodeOk

`func (o *PurchaseOrdersApiListLineItemsItem) GetTaxCodeOk() (*string, bool)`

GetTaxCodeOk returns a tuple with the TaxCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxCode

`func (o *PurchaseOrdersApiListLineItemsItem) SetTaxCode(v string)`

SetTaxCode sets TaxCode field to given value.

### HasTaxCode

`func (o *PurchaseOrdersApiListLineItemsItem) HasTaxCode() bool`

HasTaxCode returns a boolean if a field has been set.

### GetPartId

`func (o *PurchaseOrdersApiListLineItemsItem) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *PurchaseOrdersApiListLineItemsItem) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *PurchaseOrdersApiListLineItemsItem) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *PurchaseOrdersApiListLineItemsItem) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetOperationCode

`func (o *PurchaseOrdersApiListLineItemsItem) GetOperationCode() string`

GetOperationCode returns the OperationCode field if non-nil, zero value otherwise.

### GetOperationCodeOk

`func (o *PurchaseOrdersApiListLineItemsItem) GetOperationCodeOk() (*string, bool)`

GetOperationCodeOk returns a tuple with the OperationCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationCode

`func (o *PurchaseOrdersApiListLineItemsItem) SetOperationCode(v string)`

SetOperationCode sets OperationCode field to given value.

### HasOperationCode

`func (o *PurchaseOrdersApiListLineItemsItem) HasOperationCode() bool`

HasOperationCode returns a boolean if a field has been set.

### GetPartOperationId

`func (o *PurchaseOrdersApiListLineItemsItem) GetPartOperationId() string`

GetPartOperationId returns the PartOperationId field if non-nil, zero value otherwise.

### GetPartOperationIdOk

`func (o *PurchaseOrdersApiListLineItemsItem) GetPartOperationIdOk() (*string, bool)`

GetPartOperationIdOk returns a tuple with the PartOperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartOperationId

`func (o *PurchaseOrdersApiListLineItemsItem) SetPartOperationId(v string)`

SetPartOperationId sets PartOperationId field to given value.

### HasPartOperationId

`func (o *PurchaseOrdersApiListLineItemsItem) HasPartOperationId() bool`

HasPartOperationId returns a boolean if a field has been set.

### GetRouteToEmployeeId

`func (o *PurchaseOrdersApiListLineItemsItem) GetRouteToEmployeeId() string`

GetRouteToEmployeeId returns the RouteToEmployeeId field if non-nil, zero value otherwise.

### GetRouteToEmployeeIdOk

`func (o *PurchaseOrdersApiListLineItemsItem) GetRouteToEmployeeIdOk() (*string, bool)`

GetRouteToEmployeeIdOk returns a tuple with the RouteToEmployeeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRouteToEmployeeId

`func (o *PurchaseOrdersApiListLineItemsItem) SetRouteToEmployeeId(v string)`

SetRouteToEmployeeId sets RouteToEmployeeId field to given value.

### HasRouteToEmployeeId

`func (o *PurchaseOrdersApiListLineItemsItem) HasRouteToEmployeeId() bool`

HasRouteToEmployeeId returns a boolean if a field has been set.

### GetRequestedById

`func (o *PurchaseOrdersApiListLineItemsItem) GetRequestedById() string`

GetRequestedById returns the RequestedById field if non-nil, zero value otherwise.

### GetRequestedByIdOk

`func (o *PurchaseOrdersApiListLineItemsItem) GetRequestedByIdOk() (*string, bool)`

GetRequestedByIdOk returns a tuple with the RequestedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestedById

`func (o *PurchaseOrdersApiListLineItemsItem) SetRequestedById(v string)`

SetRequestedById sets RequestedById field to given value.

### HasRequestedById

`func (o *PurchaseOrdersApiListLineItemsItem) HasRequestedById() bool`

HasRequestedById returns a boolean if a field has been set.

### GetWeightUnit

`func (o *PurchaseOrdersApiListLineItemsItem) GetWeightUnit() string`

GetWeightUnit returns the WeightUnit field if non-nil, zero value otherwise.

### GetWeightUnitOk

`func (o *PurchaseOrdersApiListLineItemsItem) GetWeightUnitOk() (*string, bool)`

GetWeightUnitOk returns a tuple with the WeightUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeightUnit

`func (o *PurchaseOrdersApiListLineItemsItem) SetWeightUnit(v string)`

SetWeightUnit sets WeightUnit field to given value.

### HasWeightUnit

`func (o *PurchaseOrdersApiListLineItemsItem) HasWeightUnit() bool`

HasWeightUnit returns a boolean if a field has been set.

### GetWeightConversion

`func (o *PurchaseOrdersApiListLineItemsItem) GetWeightConversion() float64`

GetWeightConversion returns the WeightConversion field if non-nil, zero value otherwise.

### GetWeightConversionOk

`func (o *PurchaseOrdersApiListLineItemsItem) GetWeightConversionOk() (*float64, bool)`

GetWeightConversionOk returns a tuple with the WeightConversion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeightConversion

`func (o *PurchaseOrdersApiListLineItemsItem) SetWeightConversion(v float64)`

SetWeightConversion sets WeightConversion field to given value.

### HasWeightConversion

`func (o *PurchaseOrdersApiListLineItemsItem) HasWeightConversion() bool`

HasWeightConversion returns a boolean if a field has been set.

### GetInternalNote

`func (o *PurchaseOrdersApiListLineItemsItem) GetInternalNote() string`

GetInternalNote returns the InternalNote field if non-nil, zero value otherwise.

### GetInternalNoteOk

`func (o *PurchaseOrdersApiListLineItemsItem) GetInternalNoteOk() (*string, bool)`

GetInternalNoteOk returns a tuple with the InternalNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInternalNote

`func (o *PurchaseOrdersApiListLineItemsItem) SetInternalNote(v string)`

SetInternalNote sets InternalNote field to given value.

### HasInternalNote

`func (o *PurchaseOrdersApiListLineItemsItem) HasInternalNote() bool`

HasInternalNote returns a boolean if a field has been set.

### GetNote

`func (o *PurchaseOrdersApiListLineItemsItem) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *PurchaseOrdersApiListLineItemsItem) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *PurchaseOrdersApiListLineItemsItem) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *PurchaseOrdersApiListLineItemsItem) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetBuilding

`func (o *PurchaseOrdersApiListLineItemsItem) GetBuilding() string`

GetBuilding returns the Building field if non-nil, zero value otherwise.

### GetBuildingOk

`func (o *PurchaseOrdersApiListLineItemsItem) GetBuildingOk() (*string, bool)`

GetBuildingOk returns a tuple with the Building field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuilding

`func (o *PurchaseOrdersApiListLineItemsItem) SetBuilding(v string)`

SetBuilding sets Building field to given value.

### HasBuilding

`func (o *PurchaseOrdersApiListLineItemsItem) HasBuilding() bool`

HasBuilding returns a boolean if a field has been set.

### GetDepartment

`func (o *PurchaseOrdersApiListLineItemsItem) GetDepartment() string`

GetDepartment returns the Department field if non-nil, zero value otherwise.

### GetDepartmentOk

`func (o *PurchaseOrdersApiListLineItemsItem) GetDepartmentOk() (*string, bool)`

GetDepartmentOk returns a tuple with the Department field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDepartment

`func (o *PurchaseOrdersApiListLineItemsItem) SetDepartment(v string)`

SetDepartment sets Department field to given value.

### HasDepartment

`func (o *PurchaseOrdersApiListLineItemsItem) HasDepartment() bool`

HasDepartment returns a boolean if a field has been set.

### GetBlanketQuantity

`func (o *PurchaseOrdersApiListLineItemsItem) GetBlanketQuantity() float64`

GetBlanketQuantity returns the BlanketQuantity field if non-nil, zero value otherwise.

### GetBlanketQuantityOk

`func (o *PurchaseOrdersApiListLineItemsItem) GetBlanketQuantityOk() (*float64, bool)`

GetBlanketQuantityOk returns a tuple with the BlanketQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlanketQuantity

`func (o *PurchaseOrdersApiListLineItemsItem) SetBlanketQuantity(v float64)`

SetBlanketQuantity sets BlanketQuantity field to given value.

### HasBlanketQuantity

`func (o *PurchaseOrdersApiListLineItemsItem) HasBlanketQuantity() bool`

HasBlanketQuantity returns a boolean if a field has been set.

### GetCreatedDate

`func (o *PurchaseOrdersApiListLineItemsItem) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *PurchaseOrdersApiListLineItemsItem) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *PurchaseOrdersApiListLineItemsItem) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *PurchaseOrdersApiListLineItemsItem) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.

### GetModifiedById

`func (o *PurchaseOrdersApiListLineItemsItem) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *PurchaseOrdersApiListLineItemsItem) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *PurchaseOrdersApiListLineItemsItem) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *PurchaseOrdersApiListLineItemsItem) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetModifiedDate

`func (o *PurchaseOrdersApiListLineItemsItem) GetModifiedDate() time.Time`

GetModifiedDate returns the ModifiedDate field if non-nil, zero value otherwise.

### GetModifiedDateOk

`func (o *PurchaseOrdersApiListLineItemsItem) GetModifiedDateOk() (*time.Time, bool)`

GetModifiedDateOk returns a tuple with the ModifiedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDate

`func (o *PurchaseOrdersApiListLineItemsItem) SetModifiedDate(v time.Time)`

SetModifiedDate sets ModifiedDate field to given value.

### HasModifiedDate

`func (o *PurchaseOrdersApiListLineItemsItem) HasModifiedDate() bool`

HasModifiedDate returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


