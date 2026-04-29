# PriceAdjustmentsApiGetPriceAdjustmentResponse

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

### NewPriceAdjustmentsApiGetPriceAdjustmentResponse

`func NewPriceAdjustmentsApiGetPriceAdjustmentResponse() *PriceAdjustmentsApiGetPriceAdjustmentResponse`

NewPriceAdjustmentsApiGetPriceAdjustmentResponse instantiates a new PriceAdjustmentsApiGetPriceAdjustmentResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPriceAdjustmentsApiGetPriceAdjustmentResponseWithDefaults

`func NewPriceAdjustmentsApiGetPriceAdjustmentResponseWithDefaults() *PriceAdjustmentsApiGetPriceAdjustmentResponse`

NewPriceAdjustmentsApiGetPriceAdjustmentResponseWithDefaults instantiates a new PriceAdjustmentsApiGetPriceAdjustmentResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetDescription

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetType

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) HasType() bool`

HasType returns a boolean if a field has been set.

### GetInvoiceLine

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetInvoiceLine() string`

GetInvoiceLine returns the InvoiceLine field if non-nil, zero value otherwise.

### GetInvoiceLineOk

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetInvoiceLineOk() (*string, bool)`

GetInvoiceLineOk returns a tuple with the InvoiceLine field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceLine

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) SetInvoiceLine(v string)`

SetInvoiceLine sets InvoiceLine field to given value.

### HasInvoiceLine

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) HasInvoiceLine() bool`

HasInvoiceLine returns a boolean if a field has been set.

### GetOrderEntryLine

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetOrderEntryLine() string`

GetOrderEntryLine returns the OrderEntryLine field if non-nil, zero value otherwise.

### GetOrderEntryLineOk

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetOrderEntryLineOk() (*string, bool)`

GetOrderEntryLineOk returns a tuple with the OrderEntryLine field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderEntryLine

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) SetOrderEntryLine(v string)`

SetOrderEntryLine sets OrderEntryLine field to given value.

### HasOrderEntryLine

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) HasOrderEntryLine() bool`

HasOrderEntryLine returns a boolean if a field has been set.

### GetAccountNo

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetAccountNo() string`

GetAccountNo returns the AccountNo field if non-nil, zero value otherwise.

### GetAccountNoOk

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetAccountNoOk() (*string, bool)`

GetAccountNoOk returns a tuple with the AccountNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNo

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) SetAccountNo(v string)`

SetAccountNo sets AccountNo field to given value.

### HasAccountNo

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) HasAccountNo() bool`

HasAccountNo returns a boolean if a field has been set.

### GetPartId

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetAmount

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetAmount() float64`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetAmountOk() (*float64, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) SetAmount(v float64)`

SetAmount sets Amount field to given value.

### HasAmount

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) HasAmount() bool`

HasAmount returns a boolean if a field has been set.

### GetUnit

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetUnit() string`

GetUnit returns the Unit field if non-nil, zero value otherwise.

### GetUnitOk

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetUnitOk() (*string, bool)`

GetUnitOk returns a tuple with the Unit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnit

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) SetUnit(v string)`

SetUnit sets Unit field to given value.

### HasUnit

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) HasUnit() bool`

HasUnit returns a boolean if a field has been set.

### GetPercentage

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetPercentage() bool`

GetPercentage returns the Percentage field if non-nil, zero value otherwise.

### GetPercentageOk

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetPercentageOk() (*bool, bool)`

GetPercentageOk returns a tuple with the Percentage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPercentage

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) SetPercentage(v bool)`

SetPercentage sets Percentage field to given value.

### HasPercentage

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) HasPercentage() bool`

HasPercentage returns a boolean if a field has been set.

### GetActive

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetEffectiveDate

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetEffectiveDate() time.Time`

GetEffectiveDate returns the EffectiveDate field if non-nil, zero value otherwise.

### GetEffectiveDateOk

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetEffectiveDateOk() (*time.Time, bool)`

GetEffectiveDateOk returns a tuple with the EffectiveDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEffectiveDate

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) SetEffectiveDate(v time.Time)`

SetEffectiveDate sets EffectiveDate field to given value.

### HasEffectiveDate

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) HasEffectiveDate() bool`

HasEffectiveDate returns a boolean if a field has been set.

### GetExpirationDate

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetExpirationDate() time.Time`

GetExpirationDate returns the ExpirationDate field if non-nil, zero value otherwise.

### GetExpirationDateOk

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetExpirationDateOk() (*time.Time, bool)`

GetExpirationDateOk returns a tuple with the ExpirationDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpirationDate

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) SetExpirationDate(v time.Time)`

SetExpirationDate sets ExpirationDate field to given value.

### HasExpirationDate

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) HasExpirationDate() bool`

HasExpirationDate returns a boolean if a field has been set.

### GetBreakpointQuantity

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetBreakpointQuantity() int32`

GetBreakpointQuantity returns the BreakpointQuantity field if non-nil, zero value otherwise.

### GetBreakpointQuantityOk

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetBreakpointQuantityOk() (*int32, bool)`

GetBreakpointQuantityOk returns a tuple with the BreakpointQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBreakpointQuantity

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) SetBreakpointQuantity(v int32)`

SetBreakpointQuantity sets BreakpointQuantity field to given value.

### HasBreakpointQuantity

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) HasBreakpointQuantity() bool`

HasBreakpointQuantity returns a boolean if a field has been set.

### GetCustomerType

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetCustomerType() string`

GetCustomerType returns the CustomerType field if non-nil, zero value otherwise.

### GetCustomerTypeOk

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetCustomerTypeOk() (*string, bool)`

GetCustomerTypeOk returns a tuple with the CustomerType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerType

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) SetCustomerType(v string)`

SetCustomerType sets CustomerType field to given value.

### HasCustomerType

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) HasCustomerType() bool`

HasCustomerType returns a boolean if a field has been set.

### GetPartProductType

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetPartProductType() string`

GetPartProductType returns the PartProductType field if non-nil, zero value otherwise.

### GetPartProductTypeOk

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetPartProductTypeOk() (*string, bool)`

GetPartProductTypeOk returns a tuple with the PartProductType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartProductType

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) SetPartProductType(v string)`

SetPartProductType sets PartProductType field to given value.

### HasPartProductType

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) HasPartProductType() bool`

HasPartProductType returns a boolean if a field has been set.

### GetGrade

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetGrade() string`

GetGrade returns the Grade field if non-nil, zero value otherwise.

### GetGradeOk

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetGradeOk() (*string, bool)`

GetGradeOk returns a tuple with the Grade field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrade

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) SetGrade(v string)`

SetGrade sets Grade field to given value.

### HasGrade

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) HasGrade() bool`

HasGrade returns a boolean if a field has been set.

### GetPartType

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetPartType() string`

GetPartType returns the PartType field if non-nil, zero value otherwise.

### GetPartTypeOk

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetPartTypeOk() (*string, bool)`

GetPartTypeOk returns a tuple with the PartType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartType

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) SetPartType(v string)`

SetPartType sets PartType field to given value.

### HasPartType

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) HasPartType() bool`

HasPartType returns a boolean if a field has been set.

### GetRegion

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetRegion() string`

GetRegion returns the Region field if non-nil, zero value otherwise.

### GetRegionOk

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetRegionOk() (*string, bool)`

GetRegionOk returns a tuple with the Region field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegion

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) SetRegion(v string)`

SetRegion sets Region field to given value.

### HasRegion

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) HasRegion() bool`

HasRegion returns a boolean if a field has been set.

### GetPartGroup

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetPartGroup() string`

GetPartGroup returns the PartGroup field if non-nil, zero value otherwise.

### GetPartGroupOk

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetPartGroupOk() (*string, bool)`

GetPartGroupOk returns a tuple with the PartGroup field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartGroup

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) SetPartGroup(v string)`

SetPartGroup sets PartGroup field to given value.

### HasPartGroup

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) HasPartGroup() bool`

HasPartGroup returns a boolean if a field has been set.

### GetPartProductGroup

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetPartProductGroup() string`

GetPartProductGroup returns the PartProductGroup field if non-nil, zero value otherwise.

### GetPartProductGroupOk

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetPartProductGroupOk() (*string, bool)`

GetPartProductGroupOk returns a tuple with the PartProductGroup field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartProductGroup

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) SetPartProductGroup(v string)`

SetPartProductGroup sets PartProductGroup field to given value.

### HasPartProductGroup

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) HasPartProductGroup() bool`

HasPartProductGroup returns a boolean if a field has been set.

### GetGradeType

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetGradeType() string`

GetGradeType returns the GradeType field if non-nil, zero value otherwise.

### GetGradeTypeOk

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetGradeTypeOk() (*string, bool)`

GetGradeTypeOk returns a tuple with the GradeType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGradeType

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) SetGradeType(v string)`

SetGradeType sets GradeType field to given value.

### HasGradeType

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) HasGradeType() bool`

HasGradeType returns a boolean if a field has been set.

### GetPartNo

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetPartNo() string`

GetPartNo returns the PartNo field if non-nil, zero value otherwise.

### GetPartNoOk

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetPartNoOk() (*string, bool)`

GetPartNoOk returns a tuple with the PartNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNo

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) SetPartNo(v string)`

SetPartNo sets PartNo field to given value.

### HasPartNo

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) HasPartNo() bool`

HasPartNo returns a boolean if a field has been set.

### GetPartRevision

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetPartRevision() string`

GetPartRevision returns the PartRevision field if non-nil, zero value otherwise.

### GetPartRevisionOk

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetPartRevisionOk() (*string, bool)`

GetPartRevisionOk returns a tuple with the PartRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartRevision

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) SetPartRevision(v string)`

SetPartRevision sets PartRevision field to given value.

### HasPartRevision

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) HasPartRevision() bool`

HasPartRevision returns a boolean if a field has been set.

### GetPartSource

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetPartSource() string`

GetPartSource returns the PartSource field if non-nil, zero value otherwise.

### GetPartSourceOk

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetPartSourceOk() (*string, bool)`

GetPartSourceOk returns a tuple with the PartSource field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartSource

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) SetPartSource(v string)`

SetPartSource sets PartSource field to given value.

### HasPartSource

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) HasPartSource() bool`

HasPartSource returns a boolean if a field has been set.

### GetPartTypeSubType

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetPartTypeSubType() string`

GetPartTypeSubType returns the PartTypeSubType field if non-nil, zero value otherwise.

### GetPartTypeSubTypeOk

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetPartTypeSubTypeOk() (*string, bool)`

GetPartTypeSubTypeOk returns a tuple with the PartTypeSubType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartTypeSubType

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) SetPartTypeSubType(v string)`

SetPartTypeSubType sets PartTypeSubType field to given value.

### HasPartTypeSubType

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) HasPartTypeSubType() bool`

HasPartTypeSubType returns a boolean if a field has been set.

### GetPriceSource

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetPriceSource() string`

GetPriceSource returns the PriceSource field if non-nil, zero value otherwise.

### GetPriceSourceOk

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetPriceSourceOk() (*string, bool)`

GetPriceSourceOk returns a tuple with the PriceSource field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriceSource

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) SetPriceSource(v string)`

SetPriceSource sets PriceSource field to given value.

### HasPriceSource

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) HasPriceSource() bool`

HasPriceSource returns a boolean if a field has been set.

### GetSecondaryAmount

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetSecondaryAmount() float64`

GetSecondaryAmount returns the SecondaryAmount field if non-nil, zero value otherwise.

### GetSecondaryAmountOk

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetSecondaryAmountOk() (*float64, bool)`

GetSecondaryAmountOk returns a tuple with the SecondaryAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecondaryAmount

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) SetSecondaryAmount(v float64)`

SetSecondaryAmount sets SecondaryAmount field to given value.

### HasSecondaryAmount

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) HasSecondaryAmount() bool`

HasSecondaryAmount returns a boolean if a field has been set.

### GetTemper

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetTemper() string`

GetTemper returns the Temper field if non-nil, zero value otherwise.

### GetTemperOk

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetTemperOk() (*string, bool)`

GetTemperOk returns a tuple with the Temper field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemper

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) SetTemper(v string)`

SetTemper sets Temper field to given value.

### HasTemper

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) HasTemper() bool`

HasTemper returns a boolean if a field has been set.

### GetCustomers

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetCustomers() []CustomersItem`

GetCustomers returns the Customers field if non-nil, zero value otherwise.

### GetCustomersOk

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetCustomersOk() (*[]CustomersItem, bool)`

GetCustomersOk returns a tuple with the Customers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomers

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) SetCustomers(v []CustomersItem)`

SetCustomers sets Customers field to given value.

### HasCustomers

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) HasCustomers() bool`

HasCustomers returns a boolean if a field has been set.

### GetCustomerAddresses

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetCustomerAddresses() []CustomerAddressesItem`

GetCustomerAddresses returns the CustomerAddresses field if non-nil, zero value otherwise.

### GetCustomerAddressesOk

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) GetCustomerAddressesOk() (*[]CustomerAddressesItem, bool)`

GetCustomerAddressesOk returns a tuple with the CustomerAddresses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerAddresses

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) SetCustomerAddresses(v []CustomerAddressesItem)`

SetCustomerAddresses sets CustomerAddresses field to given value.

### HasCustomerAddresses

`func (o *PriceAdjustmentsApiGetPriceAdjustmentResponse) HasCustomerAddresses() bool`

HasCustomerAddresses returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


