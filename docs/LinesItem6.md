# LinesItem6

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**LineId** | Pointer to **string** | A unique identifier for the AR Invoice Line Item. This will be automatically generated if omitted from the request. | [optional] 
**AccountId** | Pointer to **string** | A unique identifier for the AR invoice line account. | [optional] 
**AccountNumber** | Pointer to **string** | The AR invoice line account number. | [optional] 
**PartId** | Pointer to **string** | The AR invoice line part ID. | [optional] 
**PartNumber** | Pointer to **string** | The AR invoice line part number. | [optional] 
**Description** | Pointer to **string** | A description of the AR invoice line. | [optional] 
**ReferenceNo** | Pointer to **string** | The AR invoice line reference number. | [optional] 
**UnitPrice** | Pointer to **float64** | The AR invoice line unit price. | [optional] 
**Quantity** | Pointer to **float64** | The AR invoice line quantity. | [optional] 
**AccountingJobNumber** | Pointer to **string** | The accounting job that the AR invoice line is a part of, if applicable. | [optional] 
**CustomerShipperId** | Pointer to **string** | The AR invoice line Customer Shipper ID. | [optional] 
**ItemTaxCode** | Pointer to **string** | The AR invoice item tax code. | [optional] 
**TaxCodes** | Pointer to **[]string** | The list of AR taxes. | [optional] 

## Methods

### NewLinesItem6

`func NewLinesItem6() *LinesItem6`

NewLinesItem6 instantiates a new LinesItem6 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLinesItem6WithDefaults

`func NewLinesItem6WithDefaults() *LinesItem6`

NewLinesItem6WithDefaults instantiates a new LinesItem6 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLineId

`func (o *LinesItem6) GetLineId() string`

GetLineId returns the LineId field if non-nil, zero value otherwise.

### GetLineIdOk

`func (o *LinesItem6) GetLineIdOk() (*string, bool)`

GetLineIdOk returns a tuple with the LineId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineId

`func (o *LinesItem6) SetLineId(v string)`

SetLineId sets LineId field to given value.

### HasLineId

`func (o *LinesItem6) HasLineId() bool`

HasLineId returns a boolean if a field has been set.

### GetAccountId

`func (o *LinesItem6) GetAccountId() string`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *LinesItem6) GetAccountIdOk() (*string, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *LinesItem6) SetAccountId(v string)`

SetAccountId sets AccountId field to given value.

### HasAccountId

`func (o *LinesItem6) HasAccountId() bool`

HasAccountId returns a boolean if a field has been set.

### GetAccountNumber

`func (o *LinesItem6) GetAccountNumber() string`

GetAccountNumber returns the AccountNumber field if non-nil, zero value otherwise.

### GetAccountNumberOk

`func (o *LinesItem6) GetAccountNumberOk() (*string, bool)`

GetAccountNumberOk returns a tuple with the AccountNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumber

`func (o *LinesItem6) SetAccountNumber(v string)`

SetAccountNumber sets AccountNumber field to given value.

### HasAccountNumber

`func (o *LinesItem6) HasAccountNumber() bool`

HasAccountNumber returns a boolean if a field has been set.

### GetPartId

`func (o *LinesItem6) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *LinesItem6) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *LinesItem6) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *LinesItem6) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetPartNumber

`func (o *LinesItem6) GetPartNumber() string`

GetPartNumber returns the PartNumber field if non-nil, zero value otherwise.

### GetPartNumberOk

`func (o *LinesItem6) GetPartNumberOk() (*string, bool)`

GetPartNumberOk returns a tuple with the PartNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumber

`func (o *LinesItem6) SetPartNumber(v string)`

SetPartNumber sets PartNumber field to given value.

### HasPartNumber

`func (o *LinesItem6) HasPartNumber() bool`

HasPartNumber returns a boolean if a field has been set.

### GetDescription

`func (o *LinesItem6) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *LinesItem6) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *LinesItem6) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *LinesItem6) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetReferenceNo

`func (o *LinesItem6) GetReferenceNo() string`

GetReferenceNo returns the ReferenceNo field if non-nil, zero value otherwise.

### GetReferenceNoOk

`func (o *LinesItem6) GetReferenceNoOk() (*string, bool)`

GetReferenceNoOk returns a tuple with the ReferenceNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferenceNo

`func (o *LinesItem6) SetReferenceNo(v string)`

SetReferenceNo sets ReferenceNo field to given value.

### HasReferenceNo

`func (o *LinesItem6) HasReferenceNo() bool`

HasReferenceNo returns a boolean if a field has been set.

### GetUnitPrice

`func (o *LinesItem6) GetUnitPrice() float64`

GetUnitPrice returns the UnitPrice field if non-nil, zero value otherwise.

### GetUnitPriceOk

`func (o *LinesItem6) GetUnitPriceOk() (*float64, bool)`

GetUnitPriceOk returns a tuple with the UnitPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitPrice

`func (o *LinesItem6) SetUnitPrice(v float64)`

SetUnitPrice sets UnitPrice field to given value.

### HasUnitPrice

`func (o *LinesItem6) HasUnitPrice() bool`

HasUnitPrice returns a boolean if a field has been set.

### GetQuantity

`func (o *LinesItem6) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *LinesItem6) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *LinesItem6) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *LinesItem6) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetAccountingJobNumber

`func (o *LinesItem6) GetAccountingJobNumber() string`

GetAccountingJobNumber returns the AccountingJobNumber field if non-nil, zero value otherwise.

### GetAccountingJobNumberOk

`func (o *LinesItem6) GetAccountingJobNumberOk() (*string, bool)`

GetAccountingJobNumberOk returns a tuple with the AccountingJobNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountingJobNumber

`func (o *LinesItem6) SetAccountingJobNumber(v string)`

SetAccountingJobNumber sets AccountingJobNumber field to given value.

### HasAccountingJobNumber

`func (o *LinesItem6) HasAccountingJobNumber() bool`

HasAccountingJobNumber returns a boolean if a field has been set.

### GetCustomerShipperId

`func (o *LinesItem6) GetCustomerShipperId() string`

GetCustomerShipperId returns the CustomerShipperId field if non-nil, zero value otherwise.

### GetCustomerShipperIdOk

`func (o *LinesItem6) GetCustomerShipperIdOk() (*string, bool)`

GetCustomerShipperIdOk returns a tuple with the CustomerShipperId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerShipperId

`func (o *LinesItem6) SetCustomerShipperId(v string)`

SetCustomerShipperId sets CustomerShipperId field to given value.

### HasCustomerShipperId

`func (o *LinesItem6) HasCustomerShipperId() bool`

HasCustomerShipperId returns a boolean if a field has been set.

### GetItemTaxCode

`func (o *LinesItem6) GetItemTaxCode() string`

GetItemTaxCode returns the ItemTaxCode field if non-nil, zero value otherwise.

### GetItemTaxCodeOk

`func (o *LinesItem6) GetItemTaxCodeOk() (*string, bool)`

GetItemTaxCodeOk returns a tuple with the ItemTaxCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItemTaxCode

`func (o *LinesItem6) SetItemTaxCode(v string)`

SetItemTaxCode sets ItemTaxCode field to given value.

### HasItemTaxCode

`func (o *LinesItem6) HasItemTaxCode() bool`

HasItemTaxCode returns a boolean if a field has been set.

### GetTaxCodes

`func (o *LinesItem6) GetTaxCodes() []string`

GetTaxCodes returns the TaxCodes field if non-nil, zero value otherwise.

### GetTaxCodesOk

`func (o *LinesItem6) GetTaxCodesOk() (*[]string, bool)`

GetTaxCodesOk returns a tuple with the TaxCodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxCodes

`func (o *LinesItem6) SetTaxCodes(v []string)`

SetTaxCodes sets TaxCodes field to given value.

### HasTaxCodes

`func (o *LinesItem6) HasTaxCodes() bool`

HasTaxCodes returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


