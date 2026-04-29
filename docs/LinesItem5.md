# LinesItem5

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**LineId** | Pointer to **string** | The distribution line ID. | [optional] 
**AccountNumber** | Pointer to **string** | The AR invoice line account number. | [optional] 
**AccountId** | Pointer to **string** | A unique identifier for the AR invoice line account. | [optional] 
**BaseSegment** | Pointer to **string** | The AR invoice line base account segment. | [optional] 
**CostCenterSegment** | Pointer to **string** | The AR invoice line account cost center segment. | [optional] 
**SubAccountSegment** | Pointer to **string** | The AR invoice line account location segment. | [optional] 
**Description** | Pointer to **string** | A description of the AR invoice line. | [optional] 
**Credit** | Pointer to **float64** | The AR invoice distribution line is calculated as a credit. | [optional] 
**Debit** | Pointer to **float64** | The AR invoice distribution line is calculated as a debit. | [optional] 
**CurrencyCredit** | Pointer to **float64** | The AR invoice distribution line amount is a foreign currency credit. | [optional] 
**CurrencyDebit** | Pointer to **float64** | The AR invoice distribution line amount is a foreign currency debit. | [optional] 
**UnitPrice** | Pointer to **float64** | The AR invoice line unit price. | [optional] 
**Quantity** | Pointer to **float64** | The AR invoice line quantity. | [optional] 
**AccountingJobNumber** | Pointer to **string** | The accounting job that the AR invoice line is a part of if applicable. | [optional] 
**ReferenceNo** | Pointer to **string** | The AR invoice line reference number. | [optional] 
**ItemTaxCode** | Pointer to **string** | The AR invoice item tax code. | [optional] 
**VoucherDescription** | Pointer to **string** | The AR invoice line voucher description. | [optional] 
**CustomerOrderNo** | Pointer to **string** | The AR invoice line customer order number. | [optional] 
**PoId** | Pointer to **string** | The AR invoice line purchase order ID. | [optional] 
**PoLineId** | Pointer to **string** | The AR invoice line purchase order line ID. | [optional] 
**ShipperNo** | Pointer to **string** | The AR invoice line shipper number. | [optional] 
**ShipperLineId** | Pointer to **string** | The AR invoice line shipper line ID. | [optional] 
**ShipperId** | Pointer to **string** | The AR invoice line shipper ID. | [optional] 
**UoM** | Pointer to **string** | The AR invoice line unit of measure. | [optional] 
**EndUnitNumber** | Pointer to **string** | The AR invoice line end unit number. | [optional] 
**Offset** | Pointer to **int32** | The AR invoice line offset. | [optional] 
**PartId** | Pointer to **string** | The AR invoice line part ID. | [optional] 
**PartNo** | Pointer to **string** | The AR invoice line part number. | [optional] 
**Taxes** | Pointer to [**[]TaxesItem1**](TaxesItem1.md) | The list of AR taxes. | [optional] 

## Methods

### NewLinesItem5

`func NewLinesItem5() *LinesItem5`

NewLinesItem5 instantiates a new LinesItem5 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLinesItem5WithDefaults

`func NewLinesItem5WithDefaults() *LinesItem5`

NewLinesItem5WithDefaults instantiates a new LinesItem5 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLineId

`func (o *LinesItem5) GetLineId() string`

GetLineId returns the LineId field if non-nil, zero value otherwise.

### GetLineIdOk

`func (o *LinesItem5) GetLineIdOk() (*string, bool)`

GetLineIdOk returns a tuple with the LineId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineId

`func (o *LinesItem5) SetLineId(v string)`

SetLineId sets LineId field to given value.

### HasLineId

`func (o *LinesItem5) HasLineId() bool`

HasLineId returns a boolean if a field has been set.

### GetAccountNumber

`func (o *LinesItem5) GetAccountNumber() string`

GetAccountNumber returns the AccountNumber field if non-nil, zero value otherwise.

### GetAccountNumberOk

`func (o *LinesItem5) GetAccountNumberOk() (*string, bool)`

GetAccountNumberOk returns a tuple with the AccountNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumber

`func (o *LinesItem5) SetAccountNumber(v string)`

SetAccountNumber sets AccountNumber field to given value.

### HasAccountNumber

`func (o *LinesItem5) HasAccountNumber() bool`

HasAccountNumber returns a boolean if a field has been set.

### GetAccountId

`func (o *LinesItem5) GetAccountId() string`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *LinesItem5) GetAccountIdOk() (*string, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *LinesItem5) SetAccountId(v string)`

SetAccountId sets AccountId field to given value.

### HasAccountId

`func (o *LinesItem5) HasAccountId() bool`

HasAccountId returns a boolean if a field has been set.

### GetBaseSegment

`func (o *LinesItem5) GetBaseSegment() string`

GetBaseSegment returns the BaseSegment field if non-nil, zero value otherwise.

### GetBaseSegmentOk

`func (o *LinesItem5) GetBaseSegmentOk() (*string, bool)`

GetBaseSegmentOk returns a tuple with the BaseSegment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaseSegment

`func (o *LinesItem5) SetBaseSegment(v string)`

SetBaseSegment sets BaseSegment field to given value.

### HasBaseSegment

`func (o *LinesItem5) HasBaseSegment() bool`

HasBaseSegment returns a boolean if a field has been set.

### GetCostCenterSegment

`func (o *LinesItem5) GetCostCenterSegment() string`

GetCostCenterSegment returns the CostCenterSegment field if non-nil, zero value otherwise.

### GetCostCenterSegmentOk

`func (o *LinesItem5) GetCostCenterSegmentOk() (*string, bool)`

GetCostCenterSegmentOk returns a tuple with the CostCenterSegment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostCenterSegment

`func (o *LinesItem5) SetCostCenterSegment(v string)`

SetCostCenterSegment sets CostCenterSegment field to given value.

### HasCostCenterSegment

`func (o *LinesItem5) HasCostCenterSegment() bool`

HasCostCenterSegment returns a boolean if a field has been set.

### GetSubAccountSegment

`func (o *LinesItem5) GetSubAccountSegment() string`

GetSubAccountSegment returns the SubAccountSegment field if non-nil, zero value otherwise.

### GetSubAccountSegmentOk

`func (o *LinesItem5) GetSubAccountSegmentOk() (*string, bool)`

GetSubAccountSegmentOk returns a tuple with the SubAccountSegment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubAccountSegment

`func (o *LinesItem5) SetSubAccountSegment(v string)`

SetSubAccountSegment sets SubAccountSegment field to given value.

### HasSubAccountSegment

`func (o *LinesItem5) HasSubAccountSegment() bool`

HasSubAccountSegment returns a boolean if a field has been set.

### GetDescription

`func (o *LinesItem5) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *LinesItem5) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *LinesItem5) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *LinesItem5) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetCredit

`func (o *LinesItem5) GetCredit() float64`

GetCredit returns the Credit field if non-nil, zero value otherwise.

### GetCreditOk

`func (o *LinesItem5) GetCreditOk() (*float64, bool)`

GetCreditOk returns a tuple with the Credit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCredit

`func (o *LinesItem5) SetCredit(v float64)`

SetCredit sets Credit field to given value.

### HasCredit

`func (o *LinesItem5) HasCredit() bool`

HasCredit returns a boolean if a field has been set.

### GetDebit

`func (o *LinesItem5) GetDebit() float64`

GetDebit returns the Debit field if non-nil, zero value otherwise.

### GetDebitOk

`func (o *LinesItem5) GetDebitOk() (*float64, bool)`

GetDebitOk returns a tuple with the Debit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDebit

`func (o *LinesItem5) SetDebit(v float64)`

SetDebit sets Debit field to given value.

### HasDebit

`func (o *LinesItem5) HasDebit() bool`

HasDebit returns a boolean if a field has been set.

### GetCurrencyCredit

`func (o *LinesItem5) GetCurrencyCredit() float64`

GetCurrencyCredit returns the CurrencyCredit field if non-nil, zero value otherwise.

### GetCurrencyCreditOk

`func (o *LinesItem5) GetCurrencyCreditOk() (*float64, bool)`

GetCurrencyCreditOk returns a tuple with the CurrencyCredit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyCredit

`func (o *LinesItem5) SetCurrencyCredit(v float64)`

SetCurrencyCredit sets CurrencyCredit field to given value.

### HasCurrencyCredit

`func (o *LinesItem5) HasCurrencyCredit() bool`

HasCurrencyCredit returns a boolean if a field has been set.

### GetCurrencyDebit

`func (o *LinesItem5) GetCurrencyDebit() float64`

GetCurrencyDebit returns the CurrencyDebit field if non-nil, zero value otherwise.

### GetCurrencyDebitOk

`func (o *LinesItem5) GetCurrencyDebitOk() (*float64, bool)`

GetCurrencyDebitOk returns a tuple with the CurrencyDebit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyDebit

`func (o *LinesItem5) SetCurrencyDebit(v float64)`

SetCurrencyDebit sets CurrencyDebit field to given value.

### HasCurrencyDebit

`func (o *LinesItem5) HasCurrencyDebit() bool`

HasCurrencyDebit returns a boolean if a field has been set.

### GetUnitPrice

`func (o *LinesItem5) GetUnitPrice() float64`

GetUnitPrice returns the UnitPrice field if non-nil, zero value otherwise.

### GetUnitPriceOk

`func (o *LinesItem5) GetUnitPriceOk() (*float64, bool)`

GetUnitPriceOk returns a tuple with the UnitPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitPrice

`func (o *LinesItem5) SetUnitPrice(v float64)`

SetUnitPrice sets UnitPrice field to given value.

### HasUnitPrice

`func (o *LinesItem5) HasUnitPrice() bool`

HasUnitPrice returns a boolean if a field has been set.

### GetQuantity

`func (o *LinesItem5) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *LinesItem5) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *LinesItem5) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *LinesItem5) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetAccountingJobNumber

`func (o *LinesItem5) GetAccountingJobNumber() string`

GetAccountingJobNumber returns the AccountingJobNumber field if non-nil, zero value otherwise.

### GetAccountingJobNumberOk

`func (o *LinesItem5) GetAccountingJobNumberOk() (*string, bool)`

GetAccountingJobNumberOk returns a tuple with the AccountingJobNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountingJobNumber

`func (o *LinesItem5) SetAccountingJobNumber(v string)`

SetAccountingJobNumber sets AccountingJobNumber field to given value.

### HasAccountingJobNumber

`func (o *LinesItem5) HasAccountingJobNumber() bool`

HasAccountingJobNumber returns a boolean if a field has been set.

### GetReferenceNo

`func (o *LinesItem5) GetReferenceNo() string`

GetReferenceNo returns the ReferenceNo field if non-nil, zero value otherwise.

### GetReferenceNoOk

`func (o *LinesItem5) GetReferenceNoOk() (*string, bool)`

GetReferenceNoOk returns a tuple with the ReferenceNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferenceNo

`func (o *LinesItem5) SetReferenceNo(v string)`

SetReferenceNo sets ReferenceNo field to given value.

### HasReferenceNo

`func (o *LinesItem5) HasReferenceNo() bool`

HasReferenceNo returns a boolean if a field has been set.

### GetItemTaxCode

`func (o *LinesItem5) GetItemTaxCode() string`

GetItemTaxCode returns the ItemTaxCode field if non-nil, zero value otherwise.

### GetItemTaxCodeOk

`func (o *LinesItem5) GetItemTaxCodeOk() (*string, bool)`

GetItemTaxCodeOk returns a tuple with the ItemTaxCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItemTaxCode

`func (o *LinesItem5) SetItemTaxCode(v string)`

SetItemTaxCode sets ItemTaxCode field to given value.

### HasItemTaxCode

`func (o *LinesItem5) HasItemTaxCode() bool`

HasItemTaxCode returns a boolean if a field has been set.

### GetVoucherDescription

`func (o *LinesItem5) GetVoucherDescription() string`

GetVoucherDescription returns the VoucherDescription field if non-nil, zero value otherwise.

### GetVoucherDescriptionOk

`func (o *LinesItem5) GetVoucherDescriptionOk() (*string, bool)`

GetVoucherDescriptionOk returns a tuple with the VoucherDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoucherDescription

`func (o *LinesItem5) SetVoucherDescription(v string)`

SetVoucherDescription sets VoucherDescription field to given value.

### HasVoucherDescription

`func (o *LinesItem5) HasVoucherDescription() bool`

HasVoucherDescription returns a boolean if a field has been set.

### GetCustomerOrderNo

`func (o *LinesItem5) GetCustomerOrderNo() string`

GetCustomerOrderNo returns the CustomerOrderNo field if non-nil, zero value otherwise.

### GetCustomerOrderNoOk

`func (o *LinesItem5) GetCustomerOrderNoOk() (*string, bool)`

GetCustomerOrderNoOk returns a tuple with the CustomerOrderNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerOrderNo

`func (o *LinesItem5) SetCustomerOrderNo(v string)`

SetCustomerOrderNo sets CustomerOrderNo field to given value.

### HasCustomerOrderNo

`func (o *LinesItem5) HasCustomerOrderNo() bool`

HasCustomerOrderNo returns a boolean if a field has been set.

### GetPoId

`func (o *LinesItem5) GetPoId() string`

GetPoId returns the PoId field if non-nil, zero value otherwise.

### GetPoIdOk

`func (o *LinesItem5) GetPoIdOk() (*string, bool)`

GetPoIdOk returns a tuple with the PoId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoId

`func (o *LinesItem5) SetPoId(v string)`

SetPoId sets PoId field to given value.

### HasPoId

`func (o *LinesItem5) HasPoId() bool`

HasPoId returns a boolean if a field has been set.

### GetPoLineId

`func (o *LinesItem5) GetPoLineId() string`

GetPoLineId returns the PoLineId field if non-nil, zero value otherwise.

### GetPoLineIdOk

`func (o *LinesItem5) GetPoLineIdOk() (*string, bool)`

GetPoLineIdOk returns a tuple with the PoLineId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoLineId

`func (o *LinesItem5) SetPoLineId(v string)`

SetPoLineId sets PoLineId field to given value.

### HasPoLineId

`func (o *LinesItem5) HasPoLineId() bool`

HasPoLineId returns a boolean if a field has been set.

### GetShipperNo

`func (o *LinesItem5) GetShipperNo() string`

GetShipperNo returns the ShipperNo field if non-nil, zero value otherwise.

### GetShipperNoOk

`func (o *LinesItem5) GetShipperNoOk() (*string, bool)`

GetShipperNoOk returns a tuple with the ShipperNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipperNo

`func (o *LinesItem5) SetShipperNo(v string)`

SetShipperNo sets ShipperNo field to given value.

### HasShipperNo

`func (o *LinesItem5) HasShipperNo() bool`

HasShipperNo returns a boolean if a field has been set.

### GetShipperLineId

`func (o *LinesItem5) GetShipperLineId() string`

GetShipperLineId returns the ShipperLineId field if non-nil, zero value otherwise.

### GetShipperLineIdOk

`func (o *LinesItem5) GetShipperLineIdOk() (*string, bool)`

GetShipperLineIdOk returns a tuple with the ShipperLineId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipperLineId

`func (o *LinesItem5) SetShipperLineId(v string)`

SetShipperLineId sets ShipperLineId field to given value.

### HasShipperLineId

`func (o *LinesItem5) HasShipperLineId() bool`

HasShipperLineId returns a boolean if a field has been set.

### GetShipperId

`func (o *LinesItem5) GetShipperId() string`

GetShipperId returns the ShipperId field if non-nil, zero value otherwise.

### GetShipperIdOk

`func (o *LinesItem5) GetShipperIdOk() (*string, bool)`

GetShipperIdOk returns a tuple with the ShipperId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipperId

`func (o *LinesItem5) SetShipperId(v string)`

SetShipperId sets ShipperId field to given value.

### HasShipperId

`func (o *LinesItem5) HasShipperId() bool`

HasShipperId returns a boolean if a field has been set.

### GetUoM

`func (o *LinesItem5) GetUoM() string`

GetUoM returns the UoM field if non-nil, zero value otherwise.

### GetUoMOk

`func (o *LinesItem5) GetUoMOk() (*string, bool)`

GetUoMOk returns a tuple with the UoM field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUoM

`func (o *LinesItem5) SetUoM(v string)`

SetUoM sets UoM field to given value.

### HasUoM

`func (o *LinesItem5) HasUoM() bool`

HasUoM returns a boolean if a field has been set.

### GetEndUnitNumber

`func (o *LinesItem5) GetEndUnitNumber() string`

GetEndUnitNumber returns the EndUnitNumber field if non-nil, zero value otherwise.

### GetEndUnitNumberOk

`func (o *LinesItem5) GetEndUnitNumberOk() (*string, bool)`

GetEndUnitNumberOk returns a tuple with the EndUnitNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndUnitNumber

`func (o *LinesItem5) SetEndUnitNumber(v string)`

SetEndUnitNumber sets EndUnitNumber field to given value.

### HasEndUnitNumber

`func (o *LinesItem5) HasEndUnitNumber() bool`

HasEndUnitNumber returns a boolean if a field has been set.

### GetOffset

`func (o *LinesItem5) GetOffset() int32`

GetOffset returns the Offset field if non-nil, zero value otherwise.

### GetOffsetOk

`func (o *LinesItem5) GetOffsetOk() (*int32, bool)`

GetOffsetOk returns a tuple with the Offset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffset

`func (o *LinesItem5) SetOffset(v int32)`

SetOffset sets Offset field to given value.

### HasOffset

`func (o *LinesItem5) HasOffset() bool`

HasOffset returns a boolean if a field has been set.

### GetPartId

`func (o *LinesItem5) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *LinesItem5) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *LinesItem5) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *LinesItem5) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetPartNo

`func (o *LinesItem5) GetPartNo() string`

GetPartNo returns the PartNo field if non-nil, zero value otherwise.

### GetPartNoOk

`func (o *LinesItem5) GetPartNoOk() (*string, bool)`

GetPartNoOk returns a tuple with the PartNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNo

`func (o *LinesItem5) SetPartNo(v string)`

SetPartNo sets PartNo field to given value.

### HasPartNo

`func (o *LinesItem5) HasPartNo() bool`

HasPartNo returns a boolean if a field has been set.

### GetTaxes

`func (o *LinesItem5) GetTaxes() []TaxesItem1`

GetTaxes returns the Taxes field if non-nil, zero value otherwise.

### GetTaxesOk

`func (o *LinesItem5) GetTaxesOk() (*[]TaxesItem1, bool)`

GetTaxesOk returns a tuple with the Taxes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxes

`func (o *LinesItem5) SetTaxes(v []TaxesItem1)`

SetTaxes sets Taxes field to given value.

### HasTaxes

`func (o *LinesItem5) HasTaxes() bool`

HasTaxes returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


