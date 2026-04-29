# PriceAdjustmentsApiCreatePriceAdjustment201Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PriceAdjustmentType** | Pointer to **string** | The price adjustment type assigned to the price adjustment. | [optional] 
**AccountNo** | Pointer to **string** | The GL account number associated with the price adjustment record. | [optional] 
**Active** | Pointer to **bool** | Identifies if the price adjustment record is active regardless of effective and expiration dates. | [optional] 
**Amount** | Pointer to **float64** | The price adjustment amount. | [optional] 
**SecondaryAmount** | Pointer to **float64** | The secondary amount associated with the price adjustment. | [optional] 
**BreakPointQuantity** | Pointer to **int32** | The minimum quantity that must be shipped for a price adjustment to apply to a shipment. | [optional] 
**Description** | Pointer to **string** | Describes the reason for the price adjustment. | [optional] 
**EffectiveDate** | Pointer to **time.Time** | The date the price adjustment goes into effect. | [optional] 
**ExpirationDate** | Pointer to **time.Time** | The date the price adjustment expires. | [optional] 
**InvoiceLine** | Pointer to **string** | Information associated with a price adjustment record that can be passed to an Accounts Receivable invoice distribution line. | [optional] 
**OrderEntryLine** | Pointer to **string** | Information associated with a price adjustment record that can be passed to an order line entry. | [optional] 
**PartNo** | Pointer to **string** | The part number associated with the price adjustment. | [optional] 
**PartRevision** | Pointer to **string** | The part revision associated with the price adjustment. | [optional] 
**PartId** | Pointer to **string** | The internal part number ID to which the price adjustment record applies. | [optional] 
**PartType** | Pointer to **string** | The price adjustment record pertains to part numbers of a specific part type. | [optional] 
**PartGroup** | Pointer to **string** | The price adjustment record pertains to part numbers of a specific part group. | [optional] 
**PartProductType** | Pointer to **string** | The price adjustment record pertains to internal part numbers of a specific part product type. | [optional] 
**PartProductGroup** | Pointer to **string** | The price adjustment record pertains to part numbers of a specific part product group. | [optional] 
**PartSource** | Pointer to **string** | The part source associated with the price adjustment. | [optional] 
**PartTypeSubType** | Pointer to **string** | The part type sub type associated with the price adjustment. | [optional] 
**Grade** | Pointer to **string** | The material grade assigned to a price adjustment. | [optional] 
**GradeType** | Pointer to **string** | The grade type associated with the price adjustment. | [optional] 
**Temper** | Pointer to **string** | The temper associated with the price adjustment. | [optional] 
**Percentage** | Pointer to **bool** | Identifies if the amount associated with the price adjustment is a percentage or discrete amount. | [optional] 
**PriceSource** | Pointer to **string** | The price source associated with the price adjustment. | [optional] 
**Unit** | Pointer to **string** | The unit of measure for the price adjustment. | [optional] 
**CustomerCodes** | Pointer to **[]string** | The customer codes associated with the price adjustment. | [optional] 
**CustomerAddressCodes** | Pointer to **[]string** | The customer address codes associated with the price adjustment. | [optional] 
**CustomerAddressIds** | Pointer to **[]string** | The customer address IDs associated with the price adjustment. | [optional] 
**CustomerType** | Pointer to **string** | The customer type to which the price adjustment record applies. | [optional] 
**Region** | Pointer to **string** | The region associated with the price adjustment. | [optional] 

## Methods

### NewPriceAdjustmentsApiCreatePriceAdjustment201Response

`func NewPriceAdjustmentsApiCreatePriceAdjustment201Response() *PriceAdjustmentsApiCreatePriceAdjustment201Response`

NewPriceAdjustmentsApiCreatePriceAdjustment201Response instantiates a new PriceAdjustmentsApiCreatePriceAdjustment201Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPriceAdjustmentsApiCreatePriceAdjustment201ResponseWithDefaults

`func NewPriceAdjustmentsApiCreatePriceAdjustment201ResponseWithDefaults() *PriceAdjustmentsApiCreatePriceAdjustment201Response`

NewPriceAdjustmentsApiCreatePriceAdjustment201ResponseWithDefaults instantiates a new PriceAdjustmentsApiCreatePriceAdjustment201Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPriceAdjustmentType

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetPriceAdjustmentType() string`

GetPriceAdjustmentType returns the PriceAdjustmentType field if non-nil, zero value otherwise.

### GetPriceAdjustmentTypeOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetPriceAdjustmentTypeOk() (*string, bool)`

GetPriceAdjustmentTypeOk returns a tuple with the PriceAdjustmentType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriceAdjustmentType

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) SetPriceAdjustmentType(v string)`

SetPriceAdjustmentType sets PriceAdjustmentType field to given value.

### HasPriceAdjustmentType

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) HasPriceAdjustmentType() bool`

HasPriceAdjustmentType returns a boolean if a field has been set.

### GetAccountNo

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetAccountNo() string`

GetAccountNo returns the AccountNo field if non-nil, zero value otherwise.

### GetAccountNoOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetAccountNoOk() (*string, bool)`

GetAccountNoOk returns a tuple with the AccountNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNo

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) SetAccountNo(v string)`

SetAccountNo sets AccountNo field to given value.

### HasAccountNo

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) HasAccountNo() bool`

HasAccountNo returns a boolean if a field has been set.

### GetActive

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetAmount

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetAmount() float64`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetAmountOk() (*float64, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) SetAmount(v float64)`

SetAmount sets Amount field to given value.

### HasAmount

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) HasAmount() bool`

HasAmount returns a boolean if a field has been set.

### GetSecondaryAmount

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetSecondaryAmount() float64`

GetSecondaryAmount returns the SecondaryAmount field if non-nil, zero value otherwise.

### GetSecondaryAmountOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetSecondaryAmountOk() (*float64, bool)`

GetSecondaryAmountOk returns a tuple with the SecondaryAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecondaryAmount

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) SetSecondaryAmount(v float64)`

SetSecondaryAmount sets SecondaryAmount field to given value.

### HasSecondaryAmount

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) HasSecondaryAmount() bool`

HasSecondaryAmount returns a boolean if a field has been set.

### GetBreakPointQuantity

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetBreakPointQuantity() int32`

GetBreakPointQuantity returns the BreakPointQuantity field if non-nil, zero value otherwise.

### GetBreakPointQuantityOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetBreakPointQuantityOk() (*int32, bool)`

GetBreakPointQuantityOk returns a tuple with the BreakPointQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBreakPointQuantity

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) SetBreakPointQuantity(v int32)`

SetBreakPointQuantity sets BreakPointQuantity field to given value.

### HasBreakPointQuantity

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) HasBreakPointQuantity() bool`

HasBreakPointQuantity returns a boolean if a field has been set.

### GetDescription

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetEffectiveDate

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetEffectiveDate() time.Time`

GetEffectiveDate returns the EffectiveDate field if non-nil, zero value otherwise.

### GetEffectiveDateOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetEffectiveDateOk() (*time.Time, bool)`

GetEffectiveDateOk returns a tuple with the EffectiveDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEffectiveDate

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) SetEffectiveDate(v time.Time)`

SetEffectiveDate sets EffectiveDate field to given value.

### HasEffectiveDate

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) HasEffectiveDate() bool`

HasEffectiveDate returns a boolean if a field has been set.

### GetExpirationDate

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetExpirationDate() time.Time`

GetExpirationDate returns the ExpirationDate field if non-nil, zero value otherwise.

### GetExpirationDateOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetExpirationDateOk() (*time.Time, bool)`

GetExpirationDateOk returns a tuple with the ExpirationDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpirationDate

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) SetExpirationDate(v time.Time)`

SetExpirationDate sets ExpirationDate field to given value.

### HasExpirationDate

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) HasExpirationDate() bool`

HasExpirationDate returns a boolean if a field has been set.

### GetInvoiceLine

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetInvoiceLine() string`

GetInvoiceLine returns the InvoiceLine field if non-nil, zero value otherwise.

### GetInvoiceLineOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetInvoiceLineOk() (*string, bool)`

GetInvoiceLineOk returns a tuple with the InvoiceLine field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceLine

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) SetInvoiceLine(v string)`

SetInvoiceLine sets InvoiceLine field to given value.

### HasInvoiceLine

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) HasInvoiceLine() bool`

HasInvoiceLine returns a boolean if a field has been set.

### GetOrderEntryLine

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetOrderEntryLine() string`

GetOrderEntryLine returns the OrderEntryLine field if non-nil, zero value otherwise.

### GetOrderEntryLineOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetOrderEntryLineOk() (*string, bool)`

GetOrderEntryLineOk returns a tuple with the OrderEntryLine field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderEntryLine

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) SetOrderEntryLine(v string)`

SetOrderEntryLine sets OrderEntryLine field to given value.

### HasOrderEntryLine

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) HasOrderEntryLine() bool`

HasOrderEntryLine returns a boolean if a field has been set.

### GetPartNo

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetPartNo() string`

GetPartNo returns the PartNo field if non-nil, zero value otherwise.

### GetPartNoOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetPartNoOk() (*string, bool)`

GetPartNoOk returns a tuple with the PartNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNo

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) SetPartNo(v string)`

SetPartNo sets PartNo field to given value.

### HasPartNo

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) HasPartNo() bool`

HasPartNo returns a boolean if a field has been set.

### GetPartRevision

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetPartRevision() string`

GetPartRevision returns the PartRevision field if non-nil, zero value otherwise.

### GetPartRevisionOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetPartRevisionOk() (*string, bool)`

GetPartRevisionOk returns a tuple with the PartRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartRevision

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) SetPartRevision(v string)`

SetPartRevision sets PartRevision field to given value.

### HasPartRevision

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) HasPartRevision() bool`

HasPartRevision returns a boolean if a field has been set.

### GetPartId

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetPartType

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetPartType() string`

GetPartType returns the PartType field if non-nil, zero value otherwise.

### GetPartTypeOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetPartTypeOk() (*string, bool)`

GetPartTypeOk returns a tuple with the PartType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartType

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) SetPartType(v string)`

SetPartType sets PartType field to given value.

### HasPartType

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) HasPartType() bool`

HasPartType returns a boolean if a field has been set.

### GetPartGroup

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetPartGroup() string`

GetPartGroup returns the PartGroup field if non-nil, zero value otherwise.

### GetPartGroupOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetPartGroupOk() (*string, bool)`

GetPartGroupOk returns a tuple with the PartGroup field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartGroup

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) SetPartGroup(v string)`

SetPartGroup sets PartGroup field to given value.

### HasPartGroup

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) HasPartGroup() bool`

HasPartGroup returns a boolean if a field has been set.

### GetPartProductType

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetPartProductType() string`

GetPartProductType returns the PartProductType field if non-nil, zero value otherwise.

### GetPartProductTypeOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetPartProductTypeOk() (*string, bool)`

GetPartProductTypeOk returns a tuple with the PartProductType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartProductType

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) SetPartProductType(v string)`

SetPartProductType sets PartProductType field to given value.

### HasPartProductType

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) HasPartProductType() bool`

HasPartProductType returns a boolean if a field has been set.

### GetPartProductGroup

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetPartProductGroup() string`

GetPartProductGroup returns the PartProductGroup field if non-nil, zero value otherwise.

### GetPartProductGroupOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetPartProductGroupOk() (*string, bool)`

GetPartProductGroupOk returns a tuple with the PartProductGroup field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartProductGroup

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) SetPartProductGroup(v string)`

SetPartProductGroup sets PartProductGroup field to given value.

### HasPartProductGroup

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) HasPartProductGroup() bool`

HasPartProductGroup returns a boolean if a field has been set.

### GetPartSource

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetPartSource() string`

GetPartSource returns the PartSource field if non-nil, zero value otherwise.

### GetPartSourceOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetPartSourceOk() (*string, bool)`

GetPartSourceOk returns a tuple with the PartSource field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartSource

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) SetPartSource(v string)`

SetPartSource sets PartSource field to given value.

### HasPartSource

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) HasPartSource() bool`

HasPartSource returns a boolean if a field has been set.

### GetPartTypeSubType

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetPartTypeSubType() string`

GetPartTypeSubType returns the PartTypeSubType field if non-nil, zero value otherwise.

### GetPartTypeSubTypeOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetPartTypeSubTypeOk() (*string, bool)`

GetPartTypeSubTypeOk returns a tuple with the PartTypeSubType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartTypeSubType

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) SetPartTypeSubType(v string)`

SetPartTypeSubType sets PartTypeSubType field to given value.

### HasPartTypeSubType

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) HasPartTypeSubType() bool`

HasPartTypeSubType returns a boolean if a field has been set.

### GetGrade

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetGrade() string`

GetGrade returns the Grade field if non-nil, zero value otherwise.

### GetGradeOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetGradeOk() (*string, bool)`

GetGradeOk returns a tuple with the Grade field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrade

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) SetGrade(v string)`

SetGrade sets Grade field to given value.

### HasGrade

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) HasGrade() bool`

HasGrade returns a boolean if a field has been set.

### GetGradeType

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetGradeType() string`

GetGradeType returns the GradeType field if non-nil, zero value otherwise.

### GetGradeTypeOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetGradeTypeOk() (*string, bool)`

GetGradeTypeOk returns a tuple with the GradeType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGradeType

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) SetGradeType(v string)`

SetGradeType sets GradeType field to given value.

### HasGradeType

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) HasGradeType() bool`

HasGradeType returns a boolean if a field has been set.

### GetTemper

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetTemper() string`

GetTemper returns the Temper field if non-nil, zero value otherwise.

### GetTemperOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetTemperOk() (*string, bool)`

GetTemperOk returns a tuple with the Temper field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemper

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) SetTemper(v string)`

SetTemper sets Temper field to given value.

### HasTemper

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) HasTemper() bool`

HasTemper returns a boolean if a field has been set.

### GetPercentage

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetPercentage() bool`

GetPercentage returns the Percentage field if non-nil, zero value otherwise.

### GetPercentageOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetPercentageOk() (*bool, bool)`

GetPercentageOk returns a tuple with the Percentage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPercentage

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) SetPercentage(v bool)`

SetPercentage sets Percentage field to given value.

### HasPercentage

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) HasPercentage() bool`

HasPercentage returns a boolean if a field has been set.

### GetPriceSource

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetPriceSource() string`

GetPriceSource returns the PriceSource field if non-nil, zero value otherwise.

### GetPriceSourceOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetPriceSourceOk() (*string, bool)`

GetPriceSourceOk returns a tuple with the PriceSource field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriceSource

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) SetPriceSource(v string)`

SetPriceSource sets PriceSource field to given value.

### HasPriceSource

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) HasPriceSource() bool`

HasPriceSource returns a boolean if a field has been set.

### GetUnit

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetUnit() string`

GetUnit returns the Unit field if non-nil, zero value otherwise.

### GetUnitOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetUnitOk() (*string, bool)`

GetUnitOk returns a tuple with the Unit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnit

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) SetUnit(v string)`

SetUnit sets Unit field to given value.

### HasUnit

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) HasUnit() bool`

HasUnit returns a boolean if a field has been set.

### GetCustomerCodes

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetCustomerCodes() []string`

GetCustomerCodes returns the CustomerCodes field if non-nil, zero value otherwise.

### GetCustomerCodesOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetCustomerCodesOk() (*[]string, bool)`

GetCustomerCodesOk returns a tuple with the CustomerCodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerCodes

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) SetCustomerCodes(v []string)`

SetCustomerCodes sets CustomerCodes field to given value.

### HasCustomerCodes

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) HasCustomerCodes() bool`

HasCustomerCodes returns a boolean if a field has been set.

### GetCustomerAddressCodes

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetCustomerAddressCodes() []string`

GetCustomerAddressCodes returns the CustomerAddressCodes field if non-nil, zero value otherwise.

### GetCustomerAddressCodesOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetCustomerAddressCodesOk() (*[]string, bool)`

GetCustomerAddressCodesOk returns a tuple with the CustomerAddressCodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerAddressCodes

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) SetCustomerAddressCodes(v []string)`

SetCustomerAddressCodes sets CustomerAddressCodes field to given value.

### HasCustomerAddressCodes

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) HasCustomerAddressCodes() bool`

HasCustomerAddressCodes returns a boolean if a field has been set.

### GetCustomerAddressIds

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetCustomerAddressIds() []string`

GetCustomerAddressIds returns the CustomerAddressIds field if non-nil, zero value otherwise.

### GetCustomerAddressIdsOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetCustomerAddressIdsOk() (*[]string, bool)`

GetCustomerAddressIdsOk returns a tuple with the CustomerAddressIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerAddressIds

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) SetCustomerAddressIds(v []string)`

SetCustomerAddressIds sets CustomerAddressIds field to given value.

### HasCustomerAddressIds

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) HasCustomerAddressIds() bool`

HasCustomerAddressIds returns a boolean if a field has been set.

### GetCustomerType

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetCustomerType() string`

GetCustomerType returns the CustomerType field if non-nil, zero value otherwise.

### GetCustomerTypeOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetCustomerTypeOk() (*string, bool)`

GetCustomerTypeOk returns a tuple with the CustomerType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerType

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) SetCustomerType(v string)`

SetCustomerType sets CustomerType field to given value.

### HasCustomerType

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) HasCustomerType() bool`

HasCustomerType returns a boolean if a field has been set.

### GetRegion

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetRegion() string`

GetRegion returns the Region field if non-nil, zero value otherwise.

### GetRegionOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) GetRegionOk() (*string, bool)`

GetRegionOk returns a tuple with the Region field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegion

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) SetRegion(v string)`

SetRegion sets Region field to given value.

### HasRegion

`func (o *PriceAdjustmentsApiCreatePriceAdjustment201Response) HasRegion() bool`

HasRegion returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


