# TaxesItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**LineId** | Pointer to **string** | The AP invoice tax line ID. | [optional] 
**AccountNumber** | Pointer to **string** | The AP invoice tax account number. | [optional] 
**AccountId** | Pointer to **string** | A unique identifier for the AP invoice tax account. | [optional] 
**BaseSegment** | Pointer to **string** | The AP invoice tax base account segment. | [optional] 
**CostCenterSegment** | Pointer to **string** | The AP invoice tax account cost center segment. | [optional] 
**SubAccountSegment** | Pointer to **string** | The AP invoice tax account location segment. | [optional] 
**TaxCode** | Pointer to **string** | The AP invoice tax code. | [optional] 
**TaxDescription** | Pointer to **string** | A description of the AP invoice tax. | [optional] 
**TaxRate** | Pointer to **float64** | The AP invoice tax rate. | [optional] 
**TaxAmount** | Pointer to **float64** | The amount of tax owed on an AP invoice. | [optional] 
**TaxableAmount** | Pointer to **float64** | The amount of the AP invoice that is taxable. | [optional] 
**Tax** | Pointer to **bool** | The AP invoice tax. | [optional] 

## Methods

### NewTaxesItem

`func NewTaxesItem() *TaxesItem`

NewTaxesItem instantiates a new TaxesItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTaxesItemWithDefaults

`func NewTaxesItemWithDefaults() *TaxesItem`

NewTaxesItemWithDefaults instantiates a new TaxesItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLineId

`func (o *TaxesItem) GetLineId() string`

GetLineId returns the LineId field if non-nil, zero value otherwise.

### GetLineIdOk

`func (o *TaxesItem) GetLineIdOk() (*string, bool)`

GetLineIdOk returns a tuple with the LineId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineId

`func (o *TaxesItem) SetLineId(v string)`

SetLineId sets LineId field to given value.

### HasLineId

`func (o *TaxesItem) HasLineId() bool`

HasLineId returns a boolean if a field has been set.

### GetAccountNumber

`func (o *TaxesItem) GetAccountNumber() string`

GetAccountNumber returns the AccountNumber field if non-nil, zero value otherwise.

### GetAccountNumberOk

`func (o *TaxesItem) GetAccountNumberOk() (*string, bool)`

GetAccountNumberOk returns a tuple with the AccountNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumber

`func (o *TaxesItem) SetAccountNumber(v string)`

SetAccountNumber sets AccountNumber field to given value.

### HasAccountNumber

`func (o *TaxesItem) HasAccountNumber() bool`

HasAccountNumber returns a boolean if a field has been set.

### GetAccountId

`func (o *TaxesItem) GetAccountId() string`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *TaxesItem) GetAccountIdOk() (*string, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *TaxesItem) SetAccountId(v string)`

SetAccountId sets AccountId field to given value.

### HasAccountId

`func (o *TaxesItem) HasAccountId() bool`

HasAccountId returns a boolean if a field has been set.

### GetBaseSegment

`func (o *TaxesItem) GetBaseSegment() string`

GetBaseSegment returns the BaseSegment field if non-nil, zero value otherwise.

### GetBaseSegmentOk

`func (o *TaxesItem) GetBaseSegmentOk() (*string, bool)`

GetBaseSegmentOk returns a tuple with the BaseSegment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaseSegment

`func (o *TaxesItem) SetBaseSegment(v string)`

SetBaseSegment sets BaseSegment field to given value.

### HasBaseSegment

`func (o *TaxesItem) HasBaseSegment() bool`

HasBaseSegment returns a boolean if a field has been set.

### GetCostCenterSegment

`func (o *TaxesItem) GetCostCenterSegment() string`

GetCostCenterSegment returns the CostCenterSegment field if non-nil, zero value otherwise.

### GetCostCenterSegmentOk

`func (o *TaxesItem) GetCostCenterSegmentOk() (*string, bool)`

GetCostCenterSegmentOk returns a tuple with the CostCenterSegment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostCenterSegment

`func (o *TaxesItem) SetCostCenterSegment(v string)`

SetCostCenterSegment sets CostCenterSegment field to given value.

### HasCostCenterSegment

`func (o *TaxesItem) HasCostCenterSegment() bool`

HasCostCenterSegment returns a boolean if a field has been set.

### GetSubAccountSegment

`func (o *TaxesItem) GetSubAccountSegment() string`

GetSubAccountSegment returns the SubAccountSegment field if non-nil, zero value otherwise.

### GetSubAccountSegmentOk

`func (o *TaxesItem) GetSubAccountSegmentOk() (*string, bool)`

GetSubAccountSegmentOk returns a tuple with the SubAccountSegment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubAccountSegment

`func (o *TaxesItem) SetSubAccountSegment(v string)`

SetSubAccountSegment sets SubAccountSegment field to given value.

### HasSubAccountSegment

`func (o *TaxesItem) HasSubAccountSegment() bool`

HasSubAccountSegment returns a boolean if a field has been set.

### GetTaxCode

`func (o *TaxesItem) GetTaxCode() string`

GetTaxCode returns the TaxCode field if non-nil, zero value otherwise.

### GetTaxCodeOk

`func (o *TaxesItem) GetTaxCodeOk() (*string, bool)`

GetTaxCodeOk returns a tuple with the TaxCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxCode

`func (o *TaxesItem) SetTaxCode(v string)`

SetTaxCode sets TaxCode field to given value.

### HasTaxCode

`func (o *TaxesItem) HasTaxCode() bool`

HasTaxCode returns a boolean if a field has been set.

### GetTaxDescription

`func (o *TaxesItem) GetTaxDescription() string`

GetTaxDescription returns the TaxDescription field if non-nil, zero value otherwise.

### GetTaxDescriptionOk

`func (o *TaxesItem) GetTaxDescriptionOk() (*string, bool)`

GetTaxDescriptionOk returns a tuple with the TaxDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxDescription

`func (o *TaxesItem) SetTaxDescription(v string)`

SetTaxDescription sets TaxDescription field to given value.

### HasTaxDescription

`func (o *TaxesItem) HasTaxDescription() bool`

HasTaxDescription returns a boolean if a field has been set.

### GetTaxRate

`func (o *TaxesItem) GetTaxRate() float64`

GetTaxRate returns the TaxRate field if non-nil, zero value otherwise.

### GetTaxRateOk

`func (o *TaxesItem) GetTaxRateOk() (*float64, bool)`

GetTaxRateOk returns a tuple with the TaxRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxRate

`func (o *TaxesItem) SetTaxRate(v float64)`

SetTaxRate sets TaxRate field to given value.

### HasTaxRate

`func (o *TaxesItem) HasTaxRate() bool`

HasTaxRate returns a boolean if a field has been set.

### GetTaxAmount

`func (o *TaxesItem) GetTaxAmount() float64`

GetTaxAmount returns the TaxAmount field if non-nil, zero value otherwise.

### GetTaxAmountOk

`func (o *TaxesItem) GetTaxAmountOk() (*float64, bool)`

GetTaxAmountOk returns a tuple with the TaxAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxAmount

`func (o *TaxesItem) SetTaxAmount(v float64)`

SetTaxAmount sets TaxAmount field to given value.

### HasTaxAmount

`func (o *TaxesItem) HasTaxAmount() bool`

HasTaxAmount returns a boolean if a field has been set.

### GetTaxableAmount

`func (o *TaxesItem) GetTaxableAmount() float64`

GetTaxableAmount returns the TaxableAmount field if non-nil, zero value otherwise.

### GetTaxableAmountOk

`func (o *TaxesItem) GetTaxableAmountOk() (*float64, bool)`

GetTaxableAmountOk returns a tuple with the TaxableAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxableAmount

`func (o *TaxesItem) SetTaxableAmount(v float64)`

SetTaxableAmount sets TaxableAmount field to given value.

### HasTaxableAmount

`func (o *TaxesItem) HasTaxableAmount() bool`

HasTaxableAmount returns a boolean if a field has been set.

### GetTax

`func (o *TaxesItem) GetTax() bool`

GetTax returns the Tax field if non-nil, zero value otherwise.

### GetTaxOk

`func (o *TaxesItem) GetTaxOk() (*bool, bool)`

GetTaxOk returns a tuple with the Tax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTax

`func (o *TaxesItem) SetTax(v bool)`

SetTax sets Tax field to given value.

### HasTax

`func (o *TaxesItem) HasTax() bool`

HasTax returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


