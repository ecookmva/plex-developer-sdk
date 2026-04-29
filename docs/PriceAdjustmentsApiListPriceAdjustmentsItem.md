# PriceAdjustmentsApiListPriceAdjustmentsItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | The price adjustment ID. | [optional] 
**Description** | Pointer to **string** | Describes the reason for the price adjustment. | [optional] 
**Type** | Pointer to **string** | The price adjustment type assigned to the price adjustment. | [optional] 
**InvoiceLine** | Pointer to **string** | Information associated with a price adjustment record that can be passed to an Accounts Receivable invoice distribution line. | [optional] 
**OrderEntryLine** | Pointer to **string** | Information associated with a price adjustment record that can be passed to an order line entry. | [optional] 
**AccountNo** | Pointer to **string** | The GL account number associated with the price adjustment record. | [optional] 
**PartId** | Pointer to **string** | The internal part number ID to which the price adjustment record applies. | [optional] 
**Amount** | Pointer to **float64** | The price adjustment amount. | [optional] 
**Unit** | Pointer to **string** | The unit of measure for the price adjustment. | [optional] 
**Percentage** | Pointer to **bool** | Identifies if the amount associated with the price adjustment is a percentage or discrete amount. | [optional] 
**Active** | Pointer to **bool** | Identifies whether the sales price adjustment record is active, regardless of effective and expiration dates. | [optional] 
**EffectiveDate** | Pointer to **time.Time** | The date the price adjustment goes into effect. | [optional] 
**ExpirationDate** | Pointer to **time.Time** | The date the price adjustment expires. | [optional] 
**BreakpointQuantity** | Pointer to **int32** | The minimum quantity that must be shipped for a price adjustment to apply to a shipment. | [optional] 
**CustomerType** | Pointer to **string** | The customer type to which the price adjustment record applies. | [optional] 
**PartProductType** | Pointer to **string** | The price adjustment record pertains to internal part numbers of a specific part product type. | [optional] 
**Grade** | Pointer to **string** | The material grade assigned to a price adjustment. | [optional] 
**PartType** | Pointer to **string** | The price adjustment record pertains to part numbers of a specific part type. | [optional] 
**Region** | Pointer to **string** | The region associated with the price adjustment. | [optional] 
**PartGroup** | Pointer to **string** | The price adjustment record pertains to part numbers of a specific part group. | [optional] 
**PartProductGroup** | Pointer to **string** | The price adjustment record pertains to part numbers of a specific part product group. | [optional] 
**GradeType** | Pointer to **string** | The grade type associated with the price adjustment. | [optional] 
**PartNo** | Pointer to **string** | The part number associated with the price adjustment. | [optional] 
**PartRevision** | Pointer to **string** | The part revision associated with the price adjustment. | [optional] 
**PartSource** | Pointer to **string** | The part source associated with the price adjustment. | [optional] 
**PartTypeSubType** | Pointer to **string** | The part type sub type associated with the price adjustment. | [optional] 
**PriceSource** | Pointer to **string** | The price source associated with the price adjustment. | [optional] 
**SecondaryAmount** | Pointer to **float64** | The secondary amount associated with the price adjustment. | [optional] 
**Temper** | Pointer to **string** | The temper associated with the price adjustment. | [optional] 
**Customers** | Pointer to [**[]CustomersItem**](CustomersItem.md) | Customers associated with the price adjustment. | [optional] 
**CustomerAddresses** | Pointer to [**[]CustomerAddressesItem**](CustomerAddressesItem.md) | Customer addresses associated with the price adjustment. | [optional] 

## Methods

### NewPriceAdjustmentsApiListPriceAdjustmentsItem

`func NewPriceAdjustmentsApiListPriceAdjustmentsItem() *PriceAdjustmentsApiListPriceAdjustmentsItem`

NewPriceAdjustmentsApiListPriceAdjustmentsItem instantiates a new PriceAdjustmentsApiListPriceAdjustmentsItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPriceAdjustmentsApiListPriceAdjustmentsItemWithDefaults

`func NewPriceAdjustmentsApiListPriceAdjustmentsItemWithDefaults() *PriceAdjustmentsApiListPriceAdjustmentsItem`

NewPriceAdjustmentsApiListPriceAdjustmentsItemWithDefaults instantiates a new PriceAdjustmentsApiListPriceAdjustmentsItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) HasId() bool`

HasId returns a boolean if a field has been set.

### GetDescription

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetType

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) HasType() bool`

HasType returns a boolean if a field has been set.

### GetInvoiceLine

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetInvoiceLine() string`

GetInvoiceLine returns the InvoiceLine field if non-nil, zero value otherwise.

### GetInvoiceLineOk

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetInvoiceLineOk() (*string, bool)`

GetInvoiceLineOk returns a tuple with the InvoiceLine field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceLine

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) SetInvoiceLine(v string)`

SetInvoiceLine sets InvoiceLine field to given value.

### HasInvoiceLine

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) HasInvoiceLine() bool`

HasInvoiceLine returns a boolean if a field has been set.

### GetOrderEntryLine

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetOrderEntryLine() string`

GetOrderEntryLine returns the OrderEntryLine field if non-nil, zero value otherwise.

### GetOrderEntryLineOk

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetOrderEntryLineOk() (*string, bool)`

GetOrderEntryLineOk returns a tuple with the OrderEntryLine field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderEntryLine

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) SetOrderEntryLine(v string)`

SetOrderEntryLine sets OrderEntryLine field to given value.

### HasOrderEntryLine

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) HasOrderEntryLine() bool`

HasOrderEntryLine returns a boolean if a field has been set.

### GetAccountNo

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetAccountNo() string`

GetAccountNo returns the AccountNo field if non-nil, zero value otherwise.

### GetAccountNoOk

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetAccountNoOk() (*string, bool)`

GetAccountNoOk returns a tuple with the AccountNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNo

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) SetAccountNo(v string)`

SetAccountNo sets AccountNo field to given value.

### HasAccountNo

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) HasAccountNo() bool`

HasAccountNo returns a boolean if a field has been set.

### GetPartId

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetAmount

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetAmount() float64`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetAmountOk() (*float64, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) SetAmount(v float64)`

SetAmount sets Amount field to given value.

### HasAmount

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) HasAmount() bool`

HasAmount returns a boolean if a field has been set.

### GetUnit

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetUnit() string`

GetUnit returns the Unit field if non-nil, zero value otherwise.

### GetUnitOk

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetUnitOk() (*string, bool)`

GetUnitOk returns a tuple with the Unit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnit

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) SetUnit(v string)`

SetUnit sets Unit field to given value.

### HasUnit

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) HasUnit() bool`

HasUnit returns a boolean if a field has been set.

### GetPercentage

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetPercentage() bool`

GetPercentage returns the Percentage field if non-nil, zero value otherwise.

### GetPercentageOk

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetPercentageOk() (*bool, bool)`

GetPercentageOk returns a tuple with the Percentage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPercentage

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) SetPercentage(v bool)`

SetPercentage sets Percentage field to given value.

### HasPercentage

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) HasPercentage() bool`

HasPercentage returns a boolean if a field has been set.

### GetActive

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetEffectiveDate

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetEffectiveDate() time.Time`

GetEffectiveDate returns the EffectiveDate field if non-nil, zero value otherwise.

### GetEffectiveDateOk

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetEffectiveDateOk() (*time.Time, bool)`

GetEffectiveDateOk returns a tuple with the EffectiveDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEffectiveDate

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) SetEffectiveDate(v time.Time)`

SetEffectiveDate sets EffectiveDate field to given value.

### HasEffectiveDate

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) HasEffectiveDate() bool`

HasEffectiveDate returns a boolean if a field has been set.

### GetExpirationDate

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetExpirationDate() time.Time`

GetExpirationDate returns the ExpirationDate field if non-nil, zero value otherwise.

### GetExpirationDateOk

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetExpirationDateOk() (*time.Time, bool)`

GetExpirationDateOk returns a tuple with the ExpirationDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpirationDate

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) SetExpirationDate(v time.Time)`

SetExpirationDate sets ExpirationDate field to given value.

### HasExpirationDate

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) HasExpirationDate() bool`

HasExpirationDate returns a boolean if a field has been set.

### GetBreakpointQuantity

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetBreakpointQuantity() int32`

GetBreakpointQuantity returns the BreakpointQuantity field if non-nil, zero value otherwise.

### GetBreakpointQuantityOk

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetBreakpointQuantityOk() (*int32, bool)`

GetBreakpointQuantityOk returns a tuple with the BreakpointQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBreakpointQuantity

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) SetBreakpointQuantity(v int32)`

SetBreakpointQuantity sets BreakpointQuantity field to given value.

### HasBreakpointQuantity

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) HasBreakpointQuantity() bool`

HasBreakpointQuantity returns a boolean if a field has been set.

### GetCustomerType

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetCustomerType() string`

GetCustomerType returns the CustomerType field if non-nil, zero value otherwise.

### GetCustomerTypeOk

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetCustomerTypeOk() (*string, bool)`

GetCustomerTypeOk returns a tuple with the CustomerType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerType

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) SetCustomerType(v string)`

SetCustomerType sets CustomerType field to given value.

### HasCustomerType

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) HasCustomerType() bool`

HasCustomerType returns a boolean if a field has been set.

### GetPartProductType

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetPartProductType() string`

GetPartProductType returns the PartProductType field if non-nil, zero value otherwise.

### GetPartProductTypeOk

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetPartProductTypeOk() (*string, bool)`

GetPartProductTypeOk returns a tuple with the PartProductType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartProductType

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) SetPartProductType(v string)`

SetPartProductType sets PartProductType field to given value.

### HasPartProductType

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) HasPartProductType() bool`

HasPartProductType returns a boolean if a field has been set.

### GetGrade

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetGrade() string`

GetGrade returns the Grade field if non-nil, zero value otherwise.

### GetGradeOk

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetGradeOk() (*string, bool)`

GetGradeOk returns a tuple with the Grade field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrade

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) SetGrade(v string)`

SetGrade sets Grade field to given value.

### HasGrade

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) HasGrade() bool`

HasGrade returns a boolean if a field has been set.

### GetPartType

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetPartType() string`

GetPartType returns the PartType field if non-nil, zero value otherwise.

### GetPartTypeOk

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetPartTypeOk() (*string, bool)`

GetPartTypeOk returns a tuple with the PartType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartType

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) SetPartType(v string)`

SetPartType sets PartType field to given value.

### HasPartType

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) HasPartType() bool`

HasPartType returns a boolean if a field has been set.

### GetRegion

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetRegion() string`

GetRegion returns the Region field if non-nil, zero value otherwise.

### GetRegionOk

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetRegionOk() (*string, bool)`

GetRegionOk returns a tuple with the Region field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegion

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) SetRegion(v string)`

SetRegion sets Region field to given value.

### HasRegion

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) HasRegion() bool`

HasRegion returns a boolean if a field has been set.

### GetPartGroup

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetPartGroup() string`

GetPartGroup returns the PartGroup field if non-nil, zero value otherwise.

### GetPartGroupOk

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetPartGroupOk() (*string, bool)`

GetPartGroupOk returns a tuple with the PartGroup field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartGroup

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) SetPartGroup(v string)`

SetPartGroup sets PartGroup field to given value.

### HasPartGroup

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) HasPartGroup() bool`

HasPartGroup returns a boolean if a field has been set.

### GetPartProductGroup

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetPartProductGroup() string`

GetPartProductGroup returns the PartProductGroup field if non-nil, zero value otherwise.

### GetPartProductGroupOk

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetPartProductGroupOk() (*string, bool)`

GetPartProductGroupOk returns a tuple with the PartProductGroup field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartProductGroup

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) SetPartProductGroup(v string)`

SetPartProductGroup sets PartProductGroup field to given value.

### HasPartProductGroup

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) HasPartProductGroup() bool`

HasPartProductGroup returns a boolean if a field has been set.

### GetGradeType

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetGradeType() string`

GetGradeType returns the GradeType field if non-nil, zero value otherwise.

### GetGradeTypeOk

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetGradeTypeOk() (*string, bool)`

GetGradeTypeOk returns a tuple with the GradeType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGradeType

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) SetGradeType(v string)`

SetGradeType sets GradeType field to given value.

### HasGradeType

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) HasGradeType() bool`

HasGradeType returns a boolean if a field has been set.

### GetPartNo

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetPartNo() string`

GetPartNo returns the PartNo field if non-nil, zero value otherwise.

### GetPartNoOk

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetPartNoOk() (*string, bool)`

GetPartNoOk returns a tuple with the PartNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNo

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) SetPartNo(v string)`

SetPartNo sets PartNo field to given value.

### HasPartNo

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) HasPartNo() bool`

HasPartNo returns a boolean if a field has been set.

### GetPartRevision

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetPartRevision() string`

GetPartRevision returns the PartRevision field if non-nil, zero value otherwise.

### GetPartRevisionOk

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetPartRevisionOk() (*string, bool)`

GetPartRevisionOk returns a tuple with the PartRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartRevision

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) SetPartRevision(v string)`

SetPartRevision sets PartRevision field to given value.

### HasPartRevision

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) HasPartRevision() bool`

HasPartRevision returns a boolean if a field has been set.

### GetPartSource

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetPartSource() string`

GetPartSource returns the PartSource field if non-nil, zero value otherwise.

### GetPartSourceOk

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetPartSourceOk() (*string, bool)`

GetPartSourceOk returns a tuple with the PartSource field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartSource

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) SetPartSource(v string)`

SetPartSource sets PartSource field to given value.

### HasPartSource

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) HasPartSource() bool`

HasPartSource returns a boolean if a field has been set.

### GetPartTypeSubType

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetPartTypeSubType() string`

GetPartTypeSubType returns the PartTypeSubType field if non-nil, zero value otherwise.

### GetPartTypeSubTypeOk

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetPartTypeSubTypeOk() (*string, bool)`

GetPartTypeSubTypeOk returns a tuple with the PartTypeSubType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartTypeSubType

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) SetPartTypeSubType(v string)`

SetPartTypeSubType sets PartTypeSubType field to given value.

### HasPartTypeSubType

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) HasPartTypeSubType() bool`

HasPartTypeSubType returns a boolean if a field has been set.

### GetPriceSource

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetPriceSource() string`

GetPriceSource returns the PriceSource field if non-nil, zero value otherwise.

### GetPriceSourceOk

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetPriceSourceOk() (*string, bool)`

GetPriceSourceOk returns a tuple with the PriceSource field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriceSource

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) SetPriceSource(v string)`

SetPriceSource sets PriceSource field to given value.

### HasPriceSource

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) HasPriceSource() bool`

HasPriceSource returns a boolean if a field has been set.

### GetSecondaryAmount

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetSecondaryAmount() float64`

GetSecondaryAmount returns the SecondaryAmount field if non-nil, zero value otherwise.

### GetSecondaryAmountOk

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetSecondaryAmountOk() (*float64, bool)`

GetSecondaryAmountOk returns a tuple with the SecondaryAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecondaryAmount

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) SetSecondaryAmount(v float64)`

SetSecondaryAmount sets SecondaryAmount field to given value.

### HasSecondaryAmount

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) HasSecondaryAmount() bool`

HasSecondaryAmount returns a boolean if a field has been set.

### GetTemper

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetTemper() string`

GetTemper returns the Temper field if non-nil, zero value otherwise.

### GetTemperOk

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetTemperOk() (*string, bool)`

GetTemperOk returns a tuple with the Temper field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemper

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) SetTemper(v string)`

SetTemper sets Temper field to given value.

### HasTemper

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) HasTemper() bool`

HasTemper returns a boolean if a field has been set.

### GetCustomers

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetCustomers() []CustomersItem`

GetCustomers returns the Customers field if non-nil, zero value otherwise.

### GetCustomersOk

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetCustomersOk() (*[]CustomersItem, bool)`

GetCustomersOk returns a tuple with the Customers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomers

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) SetCustomers(v []CustomersItem)`

SetCustomers sets Customers field to given value.

### HasCustomers

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) HasCustomers() bool`

HasCustomers returns a boolean if a field has been set.

### GetCustomerAddresses

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetCustomerAddresses() []CustomerAddressesItem`

GetCustomerAddresses returns the CustomerAddresses field if non-nil, zero value otherwise.

### GetCustomerAddressesOk

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) GetCustomerAddressesOk() (*[]CustomerAddressesItem, bool)`

GetCustomerAddressesOk returns a tuple with the CustomerAddresses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerAddresses

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) SetCustomerAddresses(v []CustomerAddressesItem)`

SetCustomerAddresses sets CustomerAddresses field to given value.

### HasCustomerAddresses

`func (o *PriceAdjustmentsApiListPriceAdjustmentsItem) HasCustomerAddresses() bool`

HasCustomerAddresses returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


