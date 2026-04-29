# PriceAdjustmentsApiCreatePriceAdjustmentRequest

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

### NewPriceAdjustmentsApiCreatePriceAdjustmentRequest

`func NewPriceAdjustmentsApiCreatePriceAdjustmentRequest() *PriceAdjustmentsApiCreatePriceAdjustmentRequest`

NewPriceAdjustmentsApiCreatePriceAdjustmentRequest instantiates a new PriceAdjustmentsApiCreatePriceAdjustmentRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPriceAdjustmentsApiCreatePriceAdjustmentRequestWithDefaults

`func NewPriceAdjustmentsApiCreatePriceAdjustmentRequestWithDefaults() *PriceAdjustmentsApiCreatePriceAdjustmentRequest`

NewPriceAdjustmentsApiCreatePriceAdjustmentRequestWithDefaults instantiates a new PriceAdjustmentsApiCreatePriceAdjustmentRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPriceAdjustmentType

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetPriceAdjustmentType() string`

GetPriceAdjustmentType returns the PriceAdjustmentType field if non-nil, zero value otherwise.

### GetPriceAdjustmentTypeOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetPriceAdjustmentTypeOk() (*string, bool)`

GetPriceAdjustmentTypeOk returns a tuple with the PriceAdjustmentType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriceAdjustmentType

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) SetPriceAdjustmentType(v string)`

SetPriceAdjustmentType sets PriceAdjustmentType field to given value.

### HasPriceAdjustmentType

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) HasPriceAdjustmentType() bool`

HasPriceAdjustmentType returns a boolean if a field has been set.

### GetAccountNo

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetAccountNo() string`

GetAccountNo returns the AccountNo field if non-nil, zero value otherwise.

### GetAccountNoOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetAccountNoOk() (*string, bool)`

GetAccountNoOk returns a tuple with the AccountNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNo

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) SetAccountNo(v string)`

SetAccountNo sets AccountNo field to given value.

### HasAccountNo

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) HasAccountNo() bool`

HasAccountNo returns a boolean if a field has been set.

### GetActive

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetAmount

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetAmount() float64`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetAmountOk() (*float64, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) SetAmount(v float64)`

SetAmount sets Amount field to given value.

### HasAmount

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) HasAmount() bool`

HasAmount returns a boolean if a field has been set.

### GetSecondaryAmount

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetSecondaryAmount() float64`

GetSecondaryAmount returns the SecondaryAmount field if non-nil, zero value otherwise.

### GetSecondaryAmountOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetSecondaryAmountOk() (*float64, bool)`

GetSecondaryAmountOk returns a tuple with the SecondaryAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecondaryAmount

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) SetSecondaryAmount(v float64)`

SetSecondaryAmount sets SecondaryAmount field to given value.

### HasSecondaryAmount

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) HasSecondaryAmount() bool`

HasSecondaryAmount returns a boolean if a field has been set.

### GetBreakPointQuantity

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetBreakPointQuantity() int32`

GetBreakPointQuantity returns the BreakPointQuantity field if non-nil, zero value otherwise.

### GetBreakPointQuantityOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetBreakPointQuantityOk() (*int32, bool)`

GetBreakPointQuantityOk returns a tuple with the BreakPointQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBreakPointQuantity

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) SetBreakPointQuantity(v int32)`

SetBreakPointQuantity sets BreakPointQuantity field to given value.

### HasBreakPointQuantity

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) HasBreakPointQuantity() bool`

HasBreakPointQuantity returns a boolean if a field has been set.

### GetDescription

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetEffectiveDate

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetEffectiveDate() time.Time`

GetEffectiveDate returns the EffectiveDate field if non-nil, zero value otherwise.

### GetEffectiveDateOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetEffectiveDateOk() (*time.Time, bool)`

GetEffectiveDateOk returns a tuple with the EffectiveDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEffectiveDate

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) SetEffectiveDate(v time.Time)`

SetEffectiveDate sets EffectiveDate field to given value.

### HasEffectiveDate

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) HasEffectiveDate() bool`

HasEffectiveDate returns a boolean if a field has been set.

### GetExpirationDate

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetExpirationDate() time.Time`

GetExpirationDate returns the ExpirationDate field if non-nil, zero value otherwise.

### GetExpirationDateOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetExpirationDateOk() (*time.Time, bool)`

GetExpirationDateOk returns a tuple with the ExpirationDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpirationDate

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) SetExpirationDate(v time.Time)`

SetExpirationDate sets ExpirationDate field to given value.

### HasExpirationDate

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) HasExpirationDate() bool`

HasExpirationDate returns a boolean if a field has been set.

### GetInvoiceLine

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetInvoiceLine() string`

GetInvoiceLine returns the InvoiceLine field if non-nil, zero value otherwise.

### GetInvoiceLineOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetInvoiceLineOk() (*string, bool)`

GetInvoiceLineOk returns a tuple with the InvoiceLine field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceLine

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) SetInvoiceLine(v string)`

SetInvoiceLine sets InvoiceLine field to given value.

### HasInvoiceLine

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) HasInvoiceLine() bool`

HasInvoiceLine returns a boolean if a field has been set.

### GetOrderEntryLine

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetOrderEntryLine() string`

GetOrderEntryLine returns the OrderEntryLine field if non-nil, zero value otherwise.

### GetOrderEntryLineOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetOrderEntryLineOk() (*string, bool)`

GetOrderEntryLineOk returns a tuple with the OrderEntryLine field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderEntryLine

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) SetOrderEntryLine(v string)`

SetOrderEntryLine sets OrderEntryLine field to given value.

### HasOrderEntryLine

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) HasOrderEntryLine() bool`

HasOrderEntryLine returns a boolean if a field has been set.

### GetPartNo

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetPartNo() string`

GetPartNo returns the PartNo field if non-nil, zero value otherwise.

### GetPartNoOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetPartNoOk() (*string, bool)`

GetPartNoOk returns a tuple with the PartNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNo

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) SetPartNo(v string)`

SetPartNo sets PartNo field to given value.

### HasPartNo

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) HasPartNo() bool`

HasPartNo returns a boolean if a field has been set.

### GetPartRevision

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetPartRevision() string`

GetPartRevision returns the PartRevision field if non-nil, zero value otherwise.

### GetPartRevisionOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetPartRevisionOk() (*string, bool)`

GetPartRevisionOk returns a tuple with the PartRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartRevision

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) SetPartRevision(v string)`

SetPartRevision sets PartRevision field to given value.

### HasPartRevision

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) HasPartRevision() bool`

HasPartRevision returns a boolean if a field has been set.

### GetPartId

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetPartType

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetPartType() string`

GetPartType returns the PartType field if non-nil, zero value otherwise.

### GetPartTypeOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetPartTypeOk() (*string, bool)`

GetPartTypeOk returns a tuple with the PartType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartType

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) SetPartType(v string)`

SetPartType sets PartType field to given value.

### HasPartType

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) HasPartType() bool`

HasPartType returns a boolean if a field has been set.

### GetPartGroup

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetPartGroup() string`

GetPartGroup returns the PartGroup field if non-nil, zero value otherwise.

### GetPartGroupOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetPartGroupOk() (*string, bool)`

GetPartGroupOk returns a tuple with the PartGroup field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartGroup

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) SetPartGroup(v string)`

SetPartGroup sets PartGroup field to given value.

### HasPartGroup

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) HasPartGroup() bool`

HasPartGroup returns a boolean if a field has been set.

### GetPartProductType

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetPartProductType() string`

GetPartProductType returns the PartProductType field if non-nil, zero value otherwise.

### GetPartProductTypeOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetPartProductTypeOk() (*string, bool)`

GetPartProductTypeOk returns a tuple with the PartProductType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartProductType

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) SetPartProductType(v string)`

SetPartProductType sets PartProductType field to given value.

### HasPartProductType

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) HasPartProductType() bool`

HasPartProductType returns a boolean if a field has been set.

### GetPartProductGroup

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetPartProductGroup() string`

GetPartProductGroup returns the PartProductGroup field if non-nil, zero value otherwise.

### GetPartProductGroupOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetPartProductGroupOk() (*string, bool)`

GetPartProductGroupOk returns a tuple with the PartProductGroup field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartProductGroup

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) SetPartProductGroup(v string)`

SetPartProductGroup sets PartProductGroup field to given value.

### HasPartProductGroup

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) HasPartProductGroup() bool`

HasPartProductGroup returns a boolean if a field has been set.

### GetPartSource

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetPartSource() string`

GetPartSource returns the PartSource field if non-nil, zero value otherwise.

### GetPartSourceOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetPartSourceOk() (*string, bool)`

GetPartSourceOk returns a tuple with the PartSource field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartSource

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) SetPartSource(v string)`

SetPartSource sets PartSource field to given value.

### HasPartSource

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) HasPartSource() bool`

HasPartSource returns a boolean if a field has been set.

### GetPartTypeSubType

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetPartTypeSubType() string`

GetPartTypeSubType returns the PartTypeSubType field if non-nil, zero value otherwise.

### GetPartTypeSubTypeOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetPartTypeSubTypeOk() (*string, bool)`

GetPartTypeSubTypeOk returns a tuple with the PartTypeSubType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartTypeSubType

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) SetPartTypeSubType(v string)`

SetPartTypeSubType sets PartTypeSubType field to given value.

### HasPartTypeSubType

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) HasPartTypeSubType() bool`

HasPartTypeSubType returns a boolean if a field has been set.

### GetGrade

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetGrade() string`

GetGrade returns the Grade field if non-nil, zero value otherwise.

### GetGradeOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetGradeOk() (*string, bool)`

GetGradeOk returns a tuple with the Grade field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrade

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) SetGrade(v string)`

SetGrade sets Grade field to given value.

### HasGrade

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) HasGrade() bool`

HasGrade returns a boolean if a field has been set.

### GetGradeType

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetGradeType() string`

GetGradeType returns the GradeType field if non-nil, zero value otherwise.

### GetGradeTypeOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetGradeTypeOk() (*string, bool)`

GetGradeTypeOk returns a tuple with the GradeType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGradeType

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) SetGradeType(v string)`

SetGradeType sets GradeType field to given value.

### HasGradeType

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) HasGradeType() bool`

HasGradeType returns a boolean if a field has been set.

### GetTemper

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetTemper() string`

GetTemper returns the Temper field if non-nil, zero value otherwise.

### GetTemperOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetTemperOk() (*string, bool)`

GetTemperOk returns a tuple with the Temper field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemper

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) SetTemper(v string)`

SetTemper sets Temper field to given value.

### HasTemper

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) HasTemper() bool`

HasTemper returns a boolean if a field has been set.

### GetPercentage

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetPercentage() bool`

GetPercentage returns the Percentage field if non-nil, zero value otherwise.

### GetPercentageOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetPercentageOk() (*bool, bool)`

GetPercentageOk returns a tuple with the Percentage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPercentage

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) SetPercentage(v bool)`

SetPercentage sets Percentage field to given value.

### HasPercentage

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) HasPercentage() bool`

HasPercentage returns a boolean if a field has been set.

### GetPriceSource

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetPriceSource() string`

GetPriceSource returns the PriceSource field if non-nil, zero value otherwise.

### GetPriceSourceOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetPriceSourceOk() (*string, bool)`

GetPriceSourceOk returns a tuple with the PriceSource field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriceSource

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) SetPriceSource(v string)`

SetPriceSource sets PriceSource field to given value.

### HasPriceSource

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) HasPriceSource() bool`

HasPriceSource returns a boolean if a field has been set.

### GetUnit

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetUnit() string`

GetUnit returns the Unit field if non-nil, zero value otherwise.

### GetUnitOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetUnitOk() (*string, bool)`

GetUnitOk returns a tuple with the Unit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnit

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) SetUnit(v string)`

SetUnit sets Unit field to given value.

### HasUnit

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) HasUnit() bool`

HasUnit returns a boolean if a field has been set.

### GetCustomerCodes

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetCustomerCodes() []string`

GetCustomerCodes returns the CustomerCodes field if non-nil, zero value otherwise.

### GetCustomerCodesOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetCustomerCodesOk() (*[]string, bool)`

GetCustomerCodesOk returns a tuple with the CustomerCodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerCodes

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) SetCustomerCodes(v []string)`

SetCustomerCodes sets CustomerCodes field to given value.

### HasCustomerCodes

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) HasCustomerCodes() bool`

HasCustomerCodes returns a boolean if a field has been set.

### GetCustomerAddressCodes

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetCustomerAddressCodes() []string`

GetCustomerAddressCodes returns the CustomerAddressCodes field if non-nil, zero value otherwise.

### GetCustomerAddressCodesOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetCustomerAddressCodesOk() (*[]string, bool)`

GetCustomerAddressCodesOk returns a tuple with the CustomerAddressCodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerAddressCodes

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) SetCustomerAddressCodes(v []string)`

SetCustomerAddressCodes sets CustomerAddressCodes field to given value.

### HasCustomerAddressCodes

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) HasCustomerAddressCodes() bool`

HasCustomerAddressCodes returns a boolean if a field has been set.

### GetCustomerAddressIds

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetCustomerAddressIds() []string`

GetCustomerAddressIds returns the CustomerAddressIds field if non-nil, zero value otherwise.

### GetCustomerAddressIdsOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetCustomerAddressIdsOk() (*[]string, bool)`

GetCustomerAddressIdsOk returns a tuple with the CustomerAddressIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerAddressIds

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) SetCustomerAddressIds(v []string)`

SetCustomerAddressIds sets CustomerAddressIds field to given value.

### HasCustomerAddressIds

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) HasCustomerAddressIds() bool`

HasCustomerAddressIds returns a boolean if a field has been set.

### GetCustomerType

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetCustomerType() string`

GetCustomerType returns the CustomerType field if non-nil, zero value otherwise.

### GetCustomerTypeOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetCustomerTypeOk() (*string, bool)`

GetCustomerTypeOk returns a tuple with the CustomerType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerType

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) SetCustomerType(v string)`

SetCustomerType sets CustomerType field to given value.

### HasCustomerType

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) HasCustomerType() bool`

HasCustomerType returns a boolean if a field has been set.

### GetRegion

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetRegion() string`

GetRegion returns the Region field if non-nil, zero value otherwise.

### GetRegionOk

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) GetRegionOk() (*string, bool)`

GetRegionOk returns a tuple with the Region field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegion

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) SetRegion(v string)`

SetRegion sets Region field to given value.

### HasRegion

`func (o *PriceAdjustmentsApiCreatePriceAdjustmentRequest) HasRegion() bool`

HasRegion returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


