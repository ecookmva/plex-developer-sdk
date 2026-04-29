# LinesItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**LineId** | Pointer to **string** | The AP invoice distribution line ID. | [optional] 
**AccountNumber** | Pointer to **string** | The AP invoice line account number. | [optional] 
**AccountId** | Pointer to **string** | A unique identifier for the AP invoice line account. | [optional] 
**BaseSegment** | Pointer to **string** | The AP invoice line base account segment. | [optional] 
**CostCenterSegment** | Pointer to **string** | The AP invoice line account cost center segment. | [optional] 
**SubAccountSegment** | Pointer to **string** | The AP invoice line account location segment. | [optional] 
**Description** | Pointer to **string** | A description of the AP invoice line. | [optional] 
**Credit** | Pointer to **float64** | The AP invoice distribution line is calculated as a credit. | [optional] 
**Debit** | Pointer to **float64** | The AP invoice distribution line is calculated as a debit. | [optional] 
**CurrencyCredit** | Pointer to **float64** | The AP invoice line amount is a foreign currency credit. | [optional] 
**CurrencyDebit** | Pointer to **float64** | The AP invoice line amount is a foreign currency debit. | [optional] 
**UnitPrice** | Pointer to **float64** | The AP invoice line unit price. | [optional] 
**Quantity** | Pointer to **float64** | The AP invoice line quantity. | [optional] 
**AccountingJobNumber** | Pointer to **string** | The accounting job for the AP invoice line, if applicable. | [optional] 
**ReferenceNo** | Pointer to **string** | The AP invoice line reference number. | [optional] 
**ShipperNo** | Pointer to **string** | The AP invoice line shipper number. | [optional] 
**ShipperLineId** | Pointer to **string** | The AP invoice line shipper line ID. | [optional] 
**VoucherDescription** | Pointer to **string** | The AP invoice line voucher description. | [optional] 
**ProjectCode** | Pointer to **string** | The AP invoice line project code. | [optional] 
**ItemTaxCode** | Pointer to **string** | The AP invoice line item tax code. | [optional] 
**ReceiptId** | Pointer to **string** | The AP invoice line receipt ID. | [optional] 
**Offset** | Pointer to **int32** | The AP invoice line offset. | [optional] 
**UoM** | Pointer to **string** | The AP invoice line unit of measure. | [optional] 
**Taxes** | Pointer to [**[]TaxesItem**](TaxesItem.md) | The list of AP invoice taxes. | [optional] 

## Methods

### NewLinesItem

`func NewLinesItem() *LinesItem`

NewLinesItem instantiates a new LinesItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLinesItemWithDefaults

`func NewLinesItemWithDefaults() *LinesItem`

NewLinesItemWithDefaults instantiates a new LinesItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLineId

`func (o *LinesItem) GetLineId() string`

GetLineId returns the LineId field if non-nil, zero value otherwise.

### GetLineIdOk

`func (o *LinesItem) GetLineIdOk() (*string, bool)`

GetLineIdOk returns a tuple with the LineId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineId

`func (o *LinesItem) SetLineId(v string)`

SetLineId sets LineId field to given value.

### HasLineId

`func (o *LinesItem) HasLineId() bool`

HasLineId returns a boolean if a field has been set.

### GetAccountNumber

`func (o *LinesItem) GetAccountNumber() string`

GetAccountNumber returns the AccountNumber field if non-nil, zero value otherwise.

### GetAccountNumberOk

`func (o *LinesItem) GetAccountNumberOk() (*string, bool)`

GetAccountNumberOk returns a tuple with the AccountNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumber

`func (o *LinesItem) SetAccountNumber(v string)`

SetAccountNumber sets AccountNumber field to given value.

### HasAccountNumber

`func (o *LinesItem) HasAccountNumber() bool`

HasAccountNumber returns a boolean if a field has been set.

### GetAccountId

`func (o *LinesItem) GetAccountId() string`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *LinesItem) GetAccountIdOk() (*string, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *LinesItem) SetAccountId(v string)`

SetAccountId sets AccountId field to given value.

### HasAccountId

`func (o *LinesItem) HasAccountId() bool`

HasAccountId returns a boolean if a field has been set.

### GetBaseSegment

`func (o *LinesItem) GetBaseSegment() string`

GetBaseSegment returns the BaseSegment field if non-nil, zero value otherwise.

### GetBaseSegmentOk

`func (o *LinesItem) GetBaseSegmentOk() (*string, bool)`

GetBaseSegmentOk returns a tuple with the BaseSegment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaseSegment

`func (o *LinesItem) SetBaseSegment(v string)`

SetBaseSegment sets BaseSegment field to given value.

### HasBaseSegment

`func (o *LinesItem) HasBaseSegment() bool`

HasBaseSegment returns a boolean if a field has been set.

### GetCostCenterSegment

`func (o *LinesItem) GetCostCenterSegment() string`

GetCostCenterSegment returns the CostCenterSegment field if non-nil, zero value otherwise.

### GetCostCenterSegmentOk

`func (o *LinesItem) GetCostCenterSegmentOk() (*string, bool)`

GetCostCenterSegmentOk returns a tuple with the CostCenterSegment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostCenterSegment

`func (o *LinesItem) SetCostCenterSegment(v string)`

SetCostCenterSegment sets CostCenterSegment field to given value.

### HasCostCenterSegment

`func (o *LinesItem) HasCostCenterSegment() bool`

HasCostCenterSegment returns a boolean if a field has been set.

### GetSubAccountSegment

`func (o *LinesItem) GetSubAccountSegment() string`

GetSubAccountSegment returns the SubAccountSegment field if non-nil, zero value otherwise.

### GetSubAccountSegmentOk

`func (o *LinesItem) GetSubAccountSegmentOk() (*string, bool)`

GetSubAccountSegmentOk returns a tuple with the SubAccountSegment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubAccountSegment

`func (o *LinesItem) SetSubAccountSegment(v string)`

SetSubAccountSegment sets SubAccountSegment field to given value.

### HasSubAccountSegment

`func (o *LinesItem) HasSubAccountSegment() bool`

HasSubAccountSegment returns a boolean if a field has been set.

### GetDescription

`func (o *LinesItem) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *LinesItem) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *LinesItem) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *LinesItem) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetCredit

`func (o *LinesItem) GetCredit() float64`

GetCredit returns the Credit field if non-nil, zero value otherwise.

### GetCreditOk

`func (o *LinesItem) GetCreditOk() (*float64, bool)`

GetCreditOk returns a tuple with the Credit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCredit

`func (o *LinesItem) SetCredit(v float64)`

SetCredit sets Credit field to given value.

### HasCredit

`func (o *LinesItem) HasCredit() bool`

HasCredit returns a boolean if a field has been set.

### GetDebit

`func (o *LinesItem) GetDebit() float64`

GetDebit returns the Debit field if non-nil, zero value otherwise.

### GetDebitOk

`func (o *LinesItem) GetDebitOk() (*float64, bool)`

GetDebitOk returns a tuple with the Debit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDebit

`func (o *LinesItem) SetDebit(v float64)`

SetDebit sets Debit field to given value.

### HasDebit

`func (o *LinesItem) HasDebit() bool`

HasDebit returns a boolean if a field has been set.

### GetCurrencyCredit

`func (o *LinesItem) GetCurrencyCredit() float64`

GetCurrencyCredit returns the CurrencyCredit field if non-nil, zero value otherwise.

### GetCurrencyCreditOk

`func (o *LinesItem) GetCurrencyCreditOk() (*float64, bool)`

GetCurrencyCreditOk returns a tuple with the CurrencyCredit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyCredit

`func (o *LinesItem) SetCurrencyCredit(v float64)`

SetCurrencyCredit sets CurrencyCredit field to given value.

### HasCurrencyCredit

`func (o *LinesItem) HasCurrencyCredit() bool`

HasCurrencyCredit returns a boolean if a field has been set.

### GetCurrencyDebit

`func (o *LinesItem) GetCurrencyDebit() float64`

GetCurrencyDebit returns the CurrencyDebit field if non-nil, zero value otherwise.

### GetCurrencyDebitOk

`func (o *LinesItem) GetCurrencyDebitOk() (*float64, bool)`

GetCurrencyDebitOk returns a tuple with the CurrencyDebit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyDebit

`func (o *LinesItem) SetCurrencyDebit(v float64)`

SetCurrencyDebit sets CurrencyDebit field to given value.

### HasCurrencyDebit

`func (o *LinesItem) HasCurrencyDebit() bool`

HasCurrencyDebit returns a boolean if a field has been set.

### GetUnitPrice

`func (o *LinesItem) GetUnitPrice() float64`

GetUnitPrice returns the UnitPrice field if non-nil, zero value otherwise.

### GetUnitPriceOk

`func (o *LinesItem) GetUnitPriceOk() (*float64, bool)`

GetUnitPriceOk returns a tuple with the UnitPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitPrice

`func (o *LinesItem) SetUnitPrice(v float64)`

SetUnitPrice sets UnitPrice field to given value.

### HasUnitPrice

`func (o *LinesItem) HasUnitPrice() bool`

HasUnitPrice returns a boolean if a field has been set.

### GetQuantity

`func (o *LinesItem) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *LinesItem) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *LinesItem) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *LinesItem) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetAccountingJobNumber

`func (o *LinesItem) GetAccountingJobNumber() string`

GetAccountingJobNumber returns the AccountingJobNumber field if non-nil, zero value otherwise.

### GetAccountingJobNumberOk

`func (o *LinesItem) GetAccountingJobNumberOk() (*string, bool)`

GetAccountingJobNumberOk returns a tuple with the AccountingJobNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountingJobNumber

`func (o *LinesItem) SetAccountingJobNumber(v string)`

SetAccountingJobNumber sets AccountingJobNumber field to given value.

### HasAccountingJobNumber

`func (o *LinesItem) HasAccountingJobNumber() bool`

HasAccountingJobNumber returns a boolean if a field has been set.

### GetReferenceNo

`func (o *LinesItem) GetReferenceNo() string`

GetReferenceNo returns the ReferenceNo field if non-nil, zero value otherwise.

### GetReferenceNoOk

`func (o *LinesItem) GetReferenceNoOk() (*string, bool)`

GetReferenceNoOk returns a tuple with the ReferenceNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferenceNo

`func (o *LinesItem) SetReferenceNo(v string)`

SetReferenceNo sets ReferenceNo field to given value.

### HasReferenceNo

`func (o *LinesItem) HasReferenceNo() bool`

HasReferenceNo returns a boolean if a field has been set.

### GetShipperNo

`func (o *LinesItem) GetShipperNo() string`

GetShipperNo returns the ShipperNo field if non-nil, zero value otherwise.

### GetShipperNoOk

`func (o *LinesItem) GetShipperNoOk() (*string, bool)`

GetShipperNoOk returns a tuple with the ShipperNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipperNo

`func (o *LinesItem) SetShipperNo(v string)`

SetShipperNo sets ShipperNo field to given value.

### HasShipperNo

`func (o *LinesItem) HasShipperNo() bool`

HasShipperNo returns a boolean if a field has been set.

### GetShipperLineId

`func (o *LinesItem) GetShipperLineId() string`

GetShipperLineId returns the ShipperLineId field if non-nil, zero value otherwise.

### GetShipperLineIdOk

`func (o *LinesItem) GetShipperLineIdOk() (*string, bool)`

GetShipperLineIdOk returns a tuple with the ShipperLineId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipperLineId

`func (o *LinesItem) SetShipperLineId(v string)`

SetShipperLineId sets ShipperLineId field to given value.

### HasShipperLineId

`func (o *LinesItem) HasShipperLineId() bool`

HasShipperLineId returns a boolean if a field has been set.

### GetVoucherDescription

`func (o *LinesItem) GetVoucherDescription() string`

GetVoucherDescription returns the VoucherDescription field if non-nil, zero value otherwise.

### GetVoucherDescriptionOk

`func (o *LinesItem) GetVoucherDescriptionOk() (*string, bool)`

GetVoucherDescriptionOk returns a tuple with the VoucherDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoucherDescription

`func (o *LinesItem) SetVoucherDescription(v string)`

SetVoucherDescription sets VoucherDescription field to given value.

### HasVoucherDescription

`func (o *LinesItem) HasVoucherDescription() bool`

HasVoucherDescription returns a boolean if a field has been set.

### GetProjectCode

`func (o *LinesItem) GetProjectCode() string`

GetProjectCode returns the ProjectCode field if non-nil, zero value otherwise.

### GetProjectCodeOk

`func (o *LinesItem) GetProjectCodeOk() (*string, bool)`

GetProjectCodeOk returns a tuple with the ProjectCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectCode

`func (o *LinesItem) SetProjectCode(v string)`

SetProjectCode sets ProjectCode field to given value.

### HasProjectCode

`func (o *LinesItem) HasProjectCode() bool`

HasProjectCode returns a boolean if a field has been set.

### GetItemTaxCode

`func (o *LinesItem) GetItemTaxCode() string`

GetItemTaxCode returns the ItemTaxCode field if non-nil, zero value otherwise.

### GetItemTaxCodeOk

`func (o *LinesItem) GetItemTaxCodeOk() (*string, bool)`

GetItemTaxCodeOk returns a tuple with the ItemTaxCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItemTaxCode

`func (o *LinesItem) SetItemTaxCode(v string)`

SetItemTaxCode sets ItemTaxCode field to given value.

### HasItemTaxCode

`func (o *LinesItem) HasItemTaxCode() bool`

HasItemTaxCode returns a boolean if a field has been set.

### GetReceiptId

`func (o *LinesItem) GetReceiptId() string`

GetReceiptId returns the ReceiptId field if non-nil, zero value otherwise.

### GetReceiptIdOk

`func (o *LinesItem) GetReceiptIdOk() (*string, bool)`

GetReceiptIdOk returns a tuple with the ReceiptId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceiptId

`func (o *LinesItem) SetReceiptId(v string)`

SetReceiptId sets ReceiptId field to given value.

### HasReceiptId

`func (o *LinesItem) HasReceiptId() bool`

HasReceiptId returns a boolean if a field has been set.

### GetOffset

`func (o *LinesItem) GetOffset() int32`

GetOffset returns the Offset field if non-nil, zero value otherwise.

### GetOffsetOk

`func (o *LinesItem) GetOffsetOk() (*int32, bool)`

GetOffsetOk returns a tuple with the Offset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffset

`func (o *LinesItem) SetOffset(v int32)`

SetOffset sets Offset field to given value.

### HasOffset

`func (o *LinesItem) HasOffset() bool`

HasOffset returns a boolean if a field has been set.

### GetUoM

`func (o *LinesItem) GetUoM() string`

GetUoM returns the UoM field if non-nil, zero value otherwise.

### GetUoMOk

`func (o *LinesItem) GetUoMOk() (*string, bool)`

GetUoMOk returns a tuple with the UoM field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUoM

`func (o *LinesItem) SetUoM(v string)`

SetUoM sets UoM field to given value.

### HasUoM

`func (o *LinesItem) HasUoM() bool`

HasUoM returns a boolean if a field has been set.

### GetTaxes

`func (o *LinesItem) GetTaxes() []TaxesItem`

GetTaxes returns the Taxes field if non-nil, zero value otherwise.

### GetTaxesOk

`func (o *LinesItem) GetTaxesOk() (*[]TaxesItem, bool)`

GetTaxesOk returns a tuple with the Taxes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxes

`func (o *LinesItem) SetTaxes(v []TaxesItem)`

SetTaxes sets Taxes field to given value.

### HasTaxes

`func (o *LinesItem) HasTaxes() bool`

HasTaxes returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


