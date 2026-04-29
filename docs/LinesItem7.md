# LinesItem7

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**LineId** | Pointer to **string** | A unique identifier for the AR invoice line item. | [optional] 
**AccountId** | Pointer to **string** | A unique identifier for the AR invoice line account. | [optional] 
**AccountNumber** | Pointer to **string** | The AR invoice line account number. | [optional] 
**PartId** | Pointer to **string** | The AR invoice line part ID. | [optional] 
**PartNumber** | Pointer to **string** | The AR invoice line part number. | [optional] 
**Description** | Pointer to **string** | A description of the AR invoice line. | [optional] 
**ReferenceNo** | Pointer to **string** | The AR invoice line reference number. | [optional] 
**UnitPrice** | Pointer to **float64** | The AR invoice line unit price. | [optional] 
**Quantity** | Pointer to **float64** | The AR invoice line quantity. | [optional] 
**AccountingJobNumber** | Pointer to **string** | The accounting job that the AR invoice line is a part of, if applicable. | [optional] 
**ItemTaxCode** | Pointer to **string** | The AR invoice item tax code. | [optional] 
**TaxCodes** | Pointer to **[]string** | The list of AR taxes. | [optional] 

## Methods

### NewLinesItem7

`func NewLinesItem7() *LinesItem7`

NewLinesItem7 instantiates a new LinesItem7 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLinesItem7WithDefaults

`func NewLinesItem7WithDefaults() *LinesItem7`

NewLinesItem7WithDefaults instantiates a new LinesItem7 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLineId

`func (o *LinesItem7) GetLineId() string`

GetLineId returns the LineId field if non-nil, zero value otherwise.

### GetLineIdOk

`func (o *LinesItem7) GetLineIdOk() (*string, bool)`

GetLineIdOk returns a tuple with the LineId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineId

`func (o *LinesItem7) SetLineId(v string)`

SetLineId sets LineId field to given value.

### HasLineId

`func (o *LinesItem7) HasLineId() bool`

HasLineId returns a boolean if a field has been set.

### GetAccountId

`func (o *LinesItem7) GetAccountId() string`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *LinesItem7) GetAccountIdOk() (*string, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *LinesItem7) SetAccountId(v string)`

SetAccountId sets AccountId field to given value.

### HasAccountId

`func (o *LinesItem7) HasAccountId() bool`

HasAccountId returns a boolean if a field has been set.

### GetAccountNumber

`func (o *LinesItem7) GetAccountNumber() string`

GetAccountNumber returns the AccountNumber field if non-nil, zero value otherwise.

### GetAccountNumberOk

`func (o *LinesItem7) GetAccountNumberOk() (*string, bool)`

GetAccountNumberOk returns a tuple with the AccountNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumber

`func (o *LinesItem7) SetAccountNumber(v string)`

SetAccountNumber sets AccountNumber field to given value.

### HasAccountNumber

`func (o *LinesItem7) HasAccountNumber() bool`

HasAccountNumber returns a boolean if a field has been set.

### GetPartId

`func (o *LinesItem7) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *LinesItem7) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *LinesItem7) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *LinesItem7) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetPartNumber

`func (o *LinesItem7) GetPartNumber() string`

GetPartNumber returns the PartNumber field if non-nil, zero value otherwise.

### GetPartNumberOk

`func (o *LinesItem7) GetPartNumberOk() (*string, bool)`

GetPartNumberOk returns a tuple with the PartNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumber

`func (o *LinesItem7) SetPartNumber(v string)`

SetPartNumber sets PartNumber field to given value.

### HasPartNumber

`func (o *LinesItem7) HasPartNumber() bool`

HasPartNumber returns a boolean if a field has been set.

### GetDescription

`func (o *LinesItem7) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *LinesItem7) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *LinesItem7) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *LinesItem7) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetReferenceNo

`func (o *LinesItem7) GetReferenceNo() string`

GetReferenceNo returns the ReferenceNo field if non-nil, zero value otherwise.

### GetReferenceNoOk

`func (o *LinesItem7) GetReferenceNoOk() (*string, bool)`

GetReferenceNoOk returns a tuple with the ReferenceNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferenceNo

`func (o *LinesItem7) SetReferenceNo(v string)`

SetReferenceNo sets ReferenceNo field to given value.

### HasReferenceNo

`func (o *LinesItem7) HasReferenceNo() bool`

HasReferenceNo returns a boolean if a field has been set.

### GetUnitPrice

`func (o *LinesItem7) GetUnitPrice() float64`

GetUnitPrice returns the UnitPrice field if non-nil, zero value otherwise.

### GetUnitPriceOk

`func (o *LinesItem7) GetUnitPriceOk() (*float64, bool)`

GetUnitPriceOk returns a tuple with the UnitPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitPrice

`func (o *LinesItem7) SetUnitPrice(v float64)`

SetUnitPrice sets UnitPrice field to given value.

### HasUnitPrice

`func (o *LinesItem7) HasUnitPrice() bool`

HasUnitPrice returns a boolean if a field has been set.

### GetQuantity

`func (o *LinesItem7) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *LinesItem7) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *LinesItem7) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *LinesItem7) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetAccountingJobNumber

`func (o *LinesItem7) GetAccountingJobNumber() string`

GetAccountingJobNumber returns the AccountingJobNumber field if non-nil, zero value otherwise.

### GetAccountingJobNumberOk

`func (o *LinesItem7) GetAccountingJobNumberOk() (*string, bool)`

GetAccountingJobNumberOk returns a tuple with the AccountingJobNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountingJobNumber

`func (o *LinesItem7) SetAccountingJobNumber(v string)`

SetAccountingJobNumber sets AccountingJobNumber field to given value.

### HasAccountingJobNumber

`func (o *LinesItem7) HasAccountingJobNumber() bool`

HasAccountingJobNumber returns a boolean if a field has been set.

### GetItemTaxCode

`func (o *LinesItem7) GetItemTaxCode() string`

GetItemTaxCode returns the ItemTaxCode field if non-nil, zero value otherwise.

### GetItemTaxCodeOk

`func (o *LinesItem7) GetItemTaxCodeOk() (*string, bool)`

GetItemTaxCodeOk returns a tuple with the ItemTaxCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItemTaxCode

`func (o *LinesItem7) SetItemTaxCode(v string)`

SetItemTaxCode sets ItemTaxCode field to given value.

### HasItemTaxCode

`func (o *LinesItem7) HasItemTaxCode() bool`

HasItemTaxCode returns a boolean if a field has been set.

### GetTaxCodes

`func (o *LinesItem7) GetTaxCodes() []string`

GetTaxCodes returns the TaxCodes field if non-nil, zero value otherwise.

### GetTaxCodesOk

`func (o *LinesItem7) GetTaxCodesOk() (*[]string, bool)`

GetTaxCodesOk returns a tuple with the TaxCodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxCodes

`func (o *LinesItem7) SetTaxCodes(v []string)`

SetTaxCodes sets TaxCodes field to given value.

### HasTaxCodes

`func (o *LinesItem7) HasTaxCodes() bool`

HasTaxCodes returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


