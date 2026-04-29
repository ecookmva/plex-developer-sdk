# LinesItem1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccountId** | Pointer to **string** | A unique identifier for the AP invoice line account. | [optional] 
**AccountNumber** | Pointer to **string** | The AP invoice line account number. | [optional] 
**ProjectCode** | Pointer to **string** | The AP invoice line project code. | [optional] 
**Description** | Pointer to **string** | A description of the AP invoice line. | [optional] 
**AccountingJobNumber** | Pointer to **string** | The accounting job number for an AP invoice line, if applicable. | [optional] 
**ItemTaxCode** | Pointer to **string** | The AP invoice line item tax code. | [optional] 
**TaxCodes** | Pointer to **[]string** | A list of tax codes. | [optional] 
**ShipperNo** | Pointer to **string** | The AP invoice line supplier shipper number. | [optional] 
**ReferenceNo** | Pointer to **string** | The AP invoice line reference number. | [optional] 
**UnitPrice** | Pointer to **float64** | The AP invoice line unit price. | [optional] 
**Quantity** | Pointer to **float64** | The AP invoice line unit quantity. | [optional] 
**IsTaxLine** | Pointer to **bool** | Specify that the AP invoice line is a tax line. | [optional] 

## Methods

### NewLinesItem1

`func NewLinesItem1() *LinesItem1`

NewLinesItem1 instantiates a new LinesItem1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLinesItem1WithDefaults

`func NewLinesItem1WithDefaults() *LinesItem1`

NewLinesItem1WithDefaults instantiates a new LinesItem1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccountId

`func (o *LinesItem1) GetAccountId() string`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *LinesItem1) GetAccountIdOk() (*string, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *LinesItem1) SetAccountId(v string)`

SetAccountId sets AccountId field to given value.

### HasAccountId

`func (o *LinesItem1) HasAccountId() bool`

HasAccountId returns a boolean if a field has been set.

### GetAccountNumber

`func (o *LinesItem1) GetAccountNumber() string`

GetAccountNumber returns the AccountNumber field if non-nil, zero value otherwise.

### GetAccountNumberOk

`func (o *LinesItem1) GetAccountNumberOk() (*string, bool)`

GetAccountNumberOk returns a tuple with the AccountNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumber

`func (o *LinesItem1) SetAccountNumber(v string)`

SetAccountNumber sets AccountNumber field to given value.

### HasAccountNumber

`func (o *LinesItem1) HasAccountNumber() bool`

HasAccountNumber returns a boolean if a field has been set.

### GetProjectCode

`func (o *LinesItem1) GetProjectCode() string`

GetProjectCode returns the ProjectCode field if non-nil, zero value otherwise.

### GetProjectCodeOk

`func (o *LinesItem1) GetProjectCodeOk() (*string, bool)`

GetProjectCodeOk returns a tuple with the ProjectCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectCode

`func (o *LinesItem1) SetProjectCode(v string)`

SetProjectCode sets ProjectCode field to given value.

### HasProjectCode

`func (o *LinesItem1) HasProjectCode() bool`

HasProjectCode returns a boolean if a field has been set.

### GetDescription

`func (o *LinesItem1) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *LinesItem1) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *LinesItem1) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *LinesItem1) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetAccountingJobNumber

`func (o *LinesItem1) GetAccountingJobNumber() string`

GetAccountingJobNumber returns the AccountingJobNumber field if non-nil, zero value otherwise.

### GetAccountingJobNumberOk

`func (o *LinesItem1) GetAccountingJobNumberOk() (*string, bool)`

GetAccountingJobNumberOk returns a tuple with the AccountingJobNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountingJobNumber

`func (o *LinesItem1) SetAccountingJobNumber(v string)`

SetAccountingJobNumber sets AccountingJobNumber field to given value.

### HasAccountingJobNumber

`func (o *LinesItem1) HasAccountingJobNumber() bool`

HasAccountingJobNumber returns a boolean if a field has been set.

### GetItemTaxCode

`func (o *LinesItem1) GetItemTaxCode() string`

GetItemTaxCode returns the ItemTaxCode field if non-nil, zero value otherwise.

### GetItemTaxCodeOk

`func (o *LinesItem1) GetItemTaxCodeOk() (*string, bool)`

GetItemTaxCodeOk returns a tuple with the ItemTaxCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItemTaxCode

`func (o *LinesItem1) SetItemTaxCode(v string)`

SetItemTaxCode sets ItemTaxCode field to given value.

### HasItemTaxCode

`func (o *LinesItem1) HasItemTaxCode() bool`

HasItemTaxCode returns a boolean if a field has been set.

### GetTaxCodes

`func (o *LinesItem1) GetTaxCodes() []string`

GetTaxCodes returns the TaxCodes field if non-nil, zero value otherwise.

### GetTaxCodesOk

`func (o *LinesItem1) GetTaxCodesOk() (*[]string, bool)`

GetTaxCodesOk returns a tuple with the TaxCodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxCodes

`func (o *LinesItem1) SetTaxCodes(v []string)`

SetTaxCodes sets TaxCodes field to given value.

### HasTaxCodes

`func (o *LinesItem1) HasTaxCodes() bool`

HasTaxCodes returns a boolean if a field has been set.

### GetShipperNo

`func (o *LinesItem1) GetShipperNo() string`

GetShipperNo returns the ShipperNo field if non-nil, zero value otherwise.

### GetShipperNoOk

`func (o *LinesItem1) GetShipperNoOk() (*string, bool)`

GetShipperNoOk returns a tuple with the ShipperNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipperNo

`func (o *LinesItem1) SetShipperNo(v string)`

SetShipperNo sets ShipperNo field to given value.

### HasShipperNo

`func (o *LinesItem1) HasShipperNo() bool`

HasShipperNo returns a boolean if a field has been set.

### GetReferenceNo

`func (o *LinesItem1) GetReferenceNo() string`

GetReferenceNo returns the ReferenceNo field if non-nil, zero value otherwise.

### GetReferenceNoOk

`func (o *LinesItem1) GetReferenceNoOk() (*string, bool)`

GetReferenceNoOk returns a tuple with the ReferenceNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferenceNo

`func (o *LinesItem1) SetReferenceNo(v string)`

SetReferenceNo sets ReferenceNo field to given value.

### HasReferenceNo

`func (o *LinesItem1) HasReferenceNo() bool`

HasReferenceNo returns a boolean if a field has been set.

### GetUnitPrice

`func (o *LinesItem1) GetUnitPrice() float64`

GetUnitPrice returns the UnitPrice field if non-nil, zero value otherwise.

### GetUnitPriceOk

`func (o *LinesItem1) GetUnitPriceOk() (*float64, bool)`

GetUnitPriceOk returns a tuple with the UnitPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitPrice

`func (o *LinesItem1) SetUnitPrice(v float64)`

SetUnitPrice sets UnitPrice field to given value.

### HasUnitPrice

`func (o *LinesItem1) HasUnitPrice() bool`

HasUnitPrice returns a boolean if a field has been set.

### GetQuantity

`func (o *LinesItem1) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *LinesItem1) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *LinesItem1) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *LinesItem1) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetIsTaxLine

`func (o *LinesItem1) GetIsTaxLine() bool`

GetIsTaxLine returns the IsTaxLine field if non-nil, zero value otherwise.

### GetIsTaxLineOk

`func (o *LinesItem1) GetIsTaxLineOk() (*bool, bool)`

GetIsTaxLineOk returns a tuple with the IsTaxLine field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsTaxLine

`func (o *LinesItem1) SetIsTaxLine(v bool)`

SetIsTaxLine sets IsTaxLine field to given value.

### HasIsTaxLine

`func (o *LinesItem1) HasIsTaxLine() bool`

HasIsTaxLine returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


