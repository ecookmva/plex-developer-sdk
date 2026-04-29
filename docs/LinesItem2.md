# LinesItem2

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**LineId** | Pointer to **string** | A unique identifier for the AP invoice line item. | [optional] 
**AccountId** | Pointer to **string** | A unique identifier for the AP invoice line account. | [optional] 
**AccountNumber** | Pointer to **string** | The AP invoice line account number. | [optional] 
**ProjectCode** | Pointer to **string** | The AP invoice line project code. | [optional] 
**Description** | Pointer to **string** | A description of the AP invoice line. | [optional] 
**AccountingJobNumber** | Pointer to **string** | The accounting job number for an AP invoice line, if applicable. | [optional] 
**ItemTaxCode** | Pointer to **string** | The AP invoice item tax code. | [optional] 
**TaxCodes** | Pointer to **[]string** | A list of tax codes. | [optional] 
**ShipperNo** | Pointer to **string** | The AP invoice line supplier shipper number. | [optional] 
**ReferenceNo** | Pointer to **string** | The AP invoice line reference number. | [optional] 
**UnitPrice** | Pointer to **float64** | The AP invoice line unit price. | [optional] 
**Quantity** | Pointer to **float64** | The AP invoice line quantity. | [optional] 
**IsTaxLine** | Pointer to **bool** | Specify that the AP invoice line is a tax line. | [optional] 

## Methods

### NewLinesItem2

`func NewLinesItem2() *LinesItem2`

NewLinesItem2 instantiates a new LinesItem2 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLinesItem2WithDefaults

`func NewLinesItem2WithDefaults() *LinesItem2`

NewLinesItem2WithDefaults instantiates a new LinesItem2 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLineId

`func (o *LinesItem2) GetLineId() string`

GetLineId returns the LineId field if non-nil, zero value otherwise.

### GetLineIdOk

`func (o *LinesItem2) GetLineIdOk() (*string, bool)`

GetLineIdOk returns a tuple with the LineId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineId

`func (o *LinesItem2) SetLineId(v string)`

SetLineId sets LineId field to given value.

### HasLineId

`func (o *LinesItem2) HasLineId() bool`

HasLineId returns a boolean if a field has been set.

### GetAccountId

`func (o *LinesItem2) GetAccountId() string`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *LinesItem2) GetAccountIdOk() (*string, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *LinesItem2) SetAccountId(v string)`

SetAccountId sets AccountId field to given value.

### HasAccountId

`func (o *LinesItem2) HasAccountId() bool`

HasAccountId returns a boolean if a field has been set.

### GetAccountNumber

`func (o *LinesItem2) GetAccountNumber() string`

GetAccountNumber returns the AccountNumber field if non-nil, zero value otherwise.

### GetAccountNumberOk

`func (o *LinesItem2) GetAccountNumberOk() (*string, bool)`

GetAccountNumberOk returns a tuple with the AccountNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumber

`func (o *LinesItem2) SetAccountNumber(v string)`

SetAccountNumber sets AccountNumber field to given value.

### HasAccountNumber

`func (o *LinesItem2) HasAccountNumber() bool`

HasAccountNumber returns a boolean if a field has been set.

### GetProjectCode

`func (o *LinesItem2) GetProjectCode() string`

GetProjectCode returns the ProjectCode field if non-nil, zero value otherwise.

### GetProjectCodeOk

`func (o *LinesItem2) GetProjectCodeOk() (*string, bool)`

GetProjectCodeOk returns a tuple with the ProjectCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectCode

`func (o *LinesItem2) SetProjectCode(v string)`

SetProjectCode sets ProjectCode field to given value.

### HasProjectCode

`func (o *LinesItem2) HasProjectCode() bool`

HasProjectCode returns a boolean if a field has been set.

### GetDescription

`func (o *LinesItem2) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *LinesItem2) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *LinesItem2) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *LinesItem2) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetAccountingJobNumber

`func (o *LinesItem2) GetAccountingJobNumber() string`

GetAccountingJobNumber returns the AccountingJobNumber field if non-nil, zero value otherwise.

### GetAccountingJobNumberOk

`func (o *LinesItem2) GetAccountingJobNumberOk() (*string, bool)`

GetAccountingJobNumberOk returns a tuple with the AccountingJobNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountingJobNumber

`func (o *LinesItem2) SetAccountingJobNumber(v string)`

SetAccountingJobNumber sets AccountingJobNumber field to given value.

### HasAccountingJobNumber

`func (o *LinesItem2) HasAccountingJobNumber() bool`

HasAccountingJobNumber returns a boolean if a field has been set.

### GetItemTaxCode

`func (o *LinesItem2) GetItemTaxCode() string`

GetItemTaxCode returns the ItemTaxCode field if non-nil, zero value otherwise.

### GetItemTaxCodeOk

`func (o *LinesItem2) GetItemTaxCodeOk() (*string, bool)`

GetItemTaxCodeOk returns a tuple with the ItemTaxCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItemTaxCode

`func (o *LinesItem2) SetItemTaxCode(v string)`

SetItemTaxCode sets ItemTaxCode field to given value.

### HasItemTaxCode

`func (o *LinesItem2) HasItemTaxCode() bool`

HasItemTaxCode returns a boolean if a field has been set.

### GetTaxCodes

`func (o *LinesItem2) GetTaxCodes() []string`

GetTaxCodes returns the TaxCodes field if non-nil, zero value otherwise.

### GetTaxCodesOk

`func (o *LinesItem2) GetTaxCodesOk() (*[]string, bool)`

GetTaxCodesOk returns a tuple with the TaxCodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxCodes

`func (o *LinesItem2) SetTaxCodes(v []string)`

SetTaxCodes sets TaxCodes field to given value.

### HasTaxCodes

`func (o *LinesItem2) HasTaxCodes() bool`

HasTaxCodes returns a boolean if a field has been set.

### GetShipperNo

`func (o *LinesItem2) GetShipperNo() string`

GetShipperNo returns the ShipperNo field if non-nil, zero value otherwise.

### GetShipperNoOk

`func (o *LinesItem2) GetShipperNoOk() (*string, bool)`

GetShipperNoOk returns a tuple with the ShipperNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipperNo

`func (o *LinesItem2) SetShipperNo(v string)`

SetShipperNo sets ShipperNo field to given value.

### HasShipperNo

`func (o *LinesItem2) HasShipperNo() bool`

HasShipperNo returns a boolean if a field has been set.

### GetReferenceNo

`func (o *LinesItem2) GetReferenceNo() string`

GetReferenceNo returns the ReferenceNo field if non-nil, zero value otherwise.

### GetReferenceNoOk

`func (o *LinesItem2) GetReferenceNoOk() (*string, bool)`

GetReferenceNoOk returns a tuple with the ReferenceNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferenceNo

`func (o *LinesItem2) SetReferenceNo(v string)`

SetReferenceNo sets ReferenceNo field to given value.

### HasReferenceNo

`func (o *LinesItem2) HasReferenceNo() bool`

HasReferenceNo returns a boolean if a field has been set.

### GetUnitPrice

`func (o *LinesItem2) GetUnitPrice() float64`

GetUnitPrice returns the UnitPrice field if non-nil, zero value otherwise.

### GetUnitPriceOk

`func (o *LinesItem2) GetUnitPriceOk() (*float64, bool)`

GetUnitPriceOk returns a tuple with the UnitPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitPrice

`func (o *LinesItem2) SetUnitPrice(v float64)`

SetUnitPrice sets UnitPrice field to given value.

### HasUnitPrice

`func (o *LinesItem2) HasUnitPrice() bool`

HasUnitPrice returns a boolean if a field has been set.

### GetQuantity

`func (o *LinesItem2) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *LinesItem2) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *LinesItem2) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *LinesItem2) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetIsTaxLine

`func (o *LinesItem2) GetIsTaxLine() bool`

GetIsTaxLine returns the IsTaxLine field if non-nil, zero value otherwise.

### GetIsTaxLineOk

`func (o *LinesItem2) GetIsTaxLineOk() (*bool, bool)`

GetIsTaxLineOk returns a tuple with the IsTaxLine field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsTaxLine

`func (o *LinesItem2) SetIsTaxLine(v bool)`

SetIsTaxLine sets IsTaxLine field to given value.

### HasIsTaxLine

`func (o *LinesItem2) HasIsTaxLine() bool`

HasIsTaxLine returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


