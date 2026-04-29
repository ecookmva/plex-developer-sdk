# TaxesItem1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**LineId** | Pointer to **string** | The distribution line ID. | [optional] 
**AccountNumber** | Pointer to **string** | The AR invoice tax account number. | [optional] 
**AccountId** | Pointer to **string** | A unique identifier for the AR invoice tax account. | [optional] 
**BaseSegment** | Pointer to **string** | The AR invoice tax base account segment. | [optional] 
**CostCenterSegment** | Pointer to **string** | The AR invoice tax account cost center segment. | [optional] 
**SubAccountSegment** | Pointer to **string** | The AR invoice tax account location segment. | [optional] 
**TaxCode** | Pointer to **string** | The AR invoice tax code. | [optional] 
**TaxDescription** | Pointer to **string** | A description of the AR invoice tax. | [optional] 
**TaxRate** | Pointer to **float64** | The AR invoice tax rate. | [optional] 
**TaxAmount** | Pointer to **float64** | The amount of AR invoice tax. | [optional] 
**TaxbleAmount** | Pointer to **float64** | The AR invoice taxable amount. | [optional] 
**Tax** | Pointer to **bool** | The AR invoice tax. | [optional] 

## Methods

### NewTaxesItem1

`func NewTaxesItem1() *TaxesItem1`

NewTaxesItem1 instantiates a new TaxesItem1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTaxesItem1WithDefaults

`func NewTaxesItem1WithDefaults() *TaxesItem1`

NewTaxesItem1WithDefaults instantiates a new TaxesItem1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLineId

`func (o *TaxesItem1) GetLineId() string`

GetLineId returns the LineId field if non-nil, zero value otherwise.

### GetLineIdOk

`func (o *TaxesItem1) GetLineIdOk() (*string, bool)`

GetLineIdOk returns a tuple with the LineId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineId

`func (o *TaxesItem1) SetLineId(v string)`

SetLineId sets LineId field to given value.

### HasLineId

`func (o *TaxesItem1) HasLineId() bool`

HasLineId returns a boolean if a field has been set.

### GetAccountNumber

`func (o *TaxesItem1) GetAccountNumber() string`

GetAccountNumber returns the AccountNumber field if non-nil, zero value otherwise.

### GetAccountNumberOk

`func (o *TaxesItem1) GetAccountNumberOk() (*string, bool)`

GetAccountNumberOk returns a tuple with the AccountNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumber

`func (o *TaxesItem1) SetAccountNumber(v string)`

SetAccountNumber sets AccountNumber field to given value.

### HasAccountNumber

`func (o *TaxesItem1) HasAccountNumber() bool`

HasAccountNumber returns a boolean if a field has been set.

### GetAccountId

`func (o *TaxesItem1) GetAccountId() string`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *TaxesItem1) GetAccountIdOk() (*string, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *TaxesItem1) SetAccountId(v string)`

SetAccountId sets AccountId field to given value.

### HasAccountId

`func (o *TaxesItem1) HasAccountId() bool`

HasAccountId returns a boolean if a field has been set.

### GetBaseSegment

`func (o *TaxesItem1) GetBaseSegment() string`

GetBaseSegment returns the BaseSegment field if non-nil, zero value otherwise.

### GetBaseSegmentOk

`func (o *TaxesItem1) GetBaseSegmentOk() (*string, bool)`

GetBaseSegmentOk returns a tuple with the BaseSegment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaseSegment

`func (o *TaxesItem1) SetBaseSegment(v string)`

SetBaseSegment sets BaseSegment field to given value.

### HasBaseSegment

`func (o *TaxesItem1) HasBaseSegment() bool`

HasBaseSegment returns a boolean if a field has been set.

### GetCostCenterSegment

`func (o *TaxesItem1) GetCostCenterSegment() string`

GetCostCenterSegment returns the CostCenterSegment field if non-nil, zero value otherwise.

### GetCostCenterSegmentOk

`func (o *TaxesItem1) GetCostCenterSegmentOk() (*string, bool)`

GetCostCenterSegmentOk returns a tuple with the CostCenterSegment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostCenterSegment

`func (o *TaxesItem1) SetCostCenterSegment(v string)`

SetCostCenterSegment sets CostCenterSegment field to given value.

### HasCostCenterSegment

`func (o *TaxesItem1) HasCostCenterSegment() bool`

HasCostCenterSegment returns a boolean if a field has been set.

### GetSubAccountSegment

`func (o *TaxesItem1) GetSubAccountSegment() string`

GetSubAccountSegment returns the SubAccountSegment field if non-nil, zero value otherwise.

### GetSubAccountSegmentOk

`func (o *TaxesItem1) GetSubAccountSegmentOk() (*string, bool)`

GetSubAccountSegmentOk returns a tuple with the SubAccountSegment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubAccountSegment

`func (o *TaxesItem1) SetSubAccountSegment(v string)`

SetSubAccountSegment sets SubAccountSegment field to given value.

### HasSubAccountSegment

`func (o *TaxesItem1) HasSubAccountSegment() bool`

HasSubAccountSegment returns a boolean if a field has been set.

### GetTaxCode

`func (o *TaxesItem1) GetTaxCode() string`

GetTaxCode returns the TaxCode field if non-nil, zero value otherwise.

### GetTaxCodeOk

`func (o *TaxesItem1) GetTaxCodeOk() (*string, bool)`

GetTaxCodeOk returns a tuple with the TaxCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxCode

`func (o *TaxesItem1) SetTaxCode(v string)`

SetTaxCode sets TaxCode field to given value.

### HasTaxCode

`func (o *TaxesItem1) HasTaxCode() bool`

HasTaxCode returns a boolean if a field has been set.

### GetTaxDescription

`func (o *TaxesItem1) GetTaxDescription() string`

GetTaxDescription returns the TaxDescription field if non-nil, zero value otherwise.

### GetTaxDescriptionOk

`func (o *TaxesItem1) GetTaxDescriptionOk() (*string, bool)`

GetTaxDescriptionOk returns a tuple with the TaxDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxDescription

`func (o *TaxesItem1) SetTaxDescription(v string)`

SetTaxDescription sets TaxDescription field to given value.

### HasTaxDescription

`func (o *TaxesItem1) HasTaxDescription() bool`

HasTaxDescription returns a boolean if a field has been set.

### GetTaxRate

`func (o *TaxesItem1) GetTaxRate() float64`

GetTaxRate returns the TaxRate field if non-nil, zero value otherwise.

### GetTaxRateOk

`func (o *TaxesItem1) GetTaxRateOk() (*float64, bool)`

GetTaxRateOk returns a tuple with the TaxRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxRate

`func (o *TaxesItem1) SetTaxRate(v float64)`

SetTaxRate sets TaxRate field to given value.

### HasTaxRate

`func (o *TaxesItem1) HasTaxRate() bool`

HasTaxRate returns a boolean if a field has been set.

### GetTaxAmount

`func (o *TaxesItem1) GetTaxAmount() float64`

GetTaxAmount returns the TaxAmount field if non-nil, zero value otherwise.

### GetTaxAmountOk

`func (o *TaxesItem1) GetTaxAmountOk() (*float64, bool)`

GetTaxAmountOk returns a tuple with the TaxAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxAmount

`func (o *TaxesItem1) SetTaxAmount(v float64)`

SetTaxAmount sets TaxAmount field to given value.

### HasTaxAmount

`func (o *TaxesItem1) HasTaxAmount() bool`

HasTaxAmount returns a boolean if a field has been set.

### GetTaxbleAmount

`func (o *TaxesItem1) GetTaxbleAmount() float64`

GetTaxbleAmount returns the TaxbleAmount field if non-nil, zero value otherwise.

### GetTaxbleAmountOk

`func (o *TaxesItem1) GetTaxbleAmountOk() (*float64, bool)`

GetTaxbleAmountOk returns a tuple with the TaxbleAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxbleAmount

`func (o *TaxesItem1) SetTaxbleAmount(v float64)`

SetTaxbleAmount sets TaxbleAmount field to given value.

### HasTaxbleAmount

`func (o *TaxesItem1) HasTaxbleAmount() bool`

HasTaxbleAmount returns a boolean if a field has been set.

### GetTax

`func (o *TaxesItem1) GetTax() bool`

GetTax returns the Tax field if non-nil, zero value otherwise.

### GetTaxOk

`func (o *TaxesItem1) GetTaxOk() (*bool, bool)`

GetTaxOk returns a tuple with the Tax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTax

`func (o *TaxesItem1) SetTax(v bool)`

SetTax sets Tax field to given value.

### HasTax

`func (o *TaxesItem1) HasTax() bool`

HasTax returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


