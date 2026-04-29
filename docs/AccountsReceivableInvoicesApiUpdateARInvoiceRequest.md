# AccountsReceivableInvoicesApiUpdateARInvoiceRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CustomerId** | Pointer to **string** | The AR customer ID. | [optional] 
**CustomerCode** | Pointer to **string** | The AR customer code, typically an abbreviated name for the customer. | [optional] 
**CustomerBillToId** | Pointer to **string** | The AR customer bill to address ID. | [optional] 
**CustomerBillToCode** | Pointer to **string** | The AR customer bill to address code. | [optional] 
**CustomerShipToId** | Pointer to **string** | The AR customer ship to address ID. | [optional] 
**CustomerShipToCode** | Pointer to **string** | The AR customer ship to address code. | [optional] 
**BuildingCode** | Pointer to **string** | The code used to look up the building resource. | [optional] 
**PeriodDisplay** | Pointer to **string** | The period in which an AR invoice is recorded. | [optional] 
**InvoiceDate** | Pointer to **time.Time** | The date an AR invoice was created. | [optional] 
**CurrencyCode** | Pointer to **string** | The AR invoice currency code. | [optional] 
**ExchangeRate** | Pointer to **float64** | The AR invoice exchange rate. | [optional] 
**Terms** | Pointer to **string** | The AR terms. | [optional] 
**DueDate** | Pointer to **time.Time** | The AR invoice due date. | [optional] 
**InvoiceNote** | Pointer to **string** | A note added to an AR invoice. | [optional] 
**InternalNote** | Pointer to **string** | An internal note added to an AR invoice. | [optional] 
**InvoiceStatus** | Pointer to **string** | The AR invoice status. | [optional] 
**GovernmentIssuedNumber** | Pointer to **string** | The AR invoice government issued number. | [optional] 
**PoId** | Pointer to **string** | The AR invoice purchase order ID. | [optional] 
**PoNumber** | Pointer to **string** | The AR invoice purchase order number. | [optional] 
**PastDueReasonCode** | Pointer to **string** | The AR invoice past due reason code. | [optional] 
**Lines** | Pointer to [**[]LinesItem7**](LinesItem7.md) | A list of AR lines. | [optional] 
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

### NewAccountsReceivableInvoicesApiUpdateARInvoiceRequest

`func NewAccountsReceivableInvoicesApiUpdateARInvoiceRequest() *AccountsReceivableInvoicesApiUpdateARInvoiceRequest`

NewAccountsReceivableInvoicesApiUpdateARInvoiceRequest instantiates a new AccountsReceivableInvoicesApiUpdateARInvoiceRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccountsReceivableInvoicesApiUpdateARInvoiceRequestWithDefaults

`func NewAccountsReceivableInvoicesApiUpdateARInvoiceRequestWithDefaults() *AccountsReceivableInvoicesApiUpdateARInvoiceRequest`

NewAccountsReceivableInvoicesApiUpdateARInvoiceRequestWithDefaults instantiates a new AccountsReceivableInvoicesApiUpdateARInvoiceRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCustomerId

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### GetCustomerCode

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetCustomerCode() string`

GetCustomerCode returns the CustomerCode field if non-nil, zero value otherwise.

### GetCustomerCodeOk

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetCustomerCodeOk() (*string, bool)`

GetCustomerCodeOk returns a tuple with the CustomerCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerCode

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) SetCustomerCode(v string)`

SetCustomerCode sets CustomerCode field to given value.

### HasCustomerCode

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) HasCustomerCode() bool`

HasCustomerCode returns a boolean if a field has been set.

### GetCustomerBillToId

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetCustomerBillToId() string`

GetCustomerBillToId returns the CustomerBillToId field if non-nil, zero value otherwise.

### GetCustomerBillToIdOk

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetCustomerBillToIdOk() (*string, bool)`

GetCustomerBillToIdOk returns a tuple with the CustomerBillToId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerBillToId

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) SetCustomerBillToId(v string)`

SetCustomerBillToId sets CustomerBillToId field to given value.

### HasCustomerBillToId

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) HasCustomerBillToId() bool`

HasCustomerBillToId returns a boolean if a field has been set.

### GetCustomerBillToCode

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetCustomerBillToCode() string`

GetCustomerBillToCode returns the CustomerBillToCode field if non-nil, zero value otherwise.

### GetCustomerBillToCodeOk

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetCustomerBillToCodeOk() (*string, bool)`

GetCustomerBillToCodeOk returns a tuple with the CustomerBillToCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerBillToCode

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) SetCustomerBillToCode(v string)`

SetCustomerBillToCode sets CustomerBillToCode field to given value.

### HasCustomerBillToCode

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) HasCustomerBillToCode() bool`

HasCustomerBillToCode returns a boolean if a field has been set.

### GetCustomerShipToId

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetCustomerShipToId() string`

GetCustomerShipToId returns the CustomerShipToId field if non-nil, zero value otherwise.

### GetCustomerShipToIdOk

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetCustomerShipToIdOk() (*string, bool)`

GetCustomerShipToIdOk returns a tuple with the CustomerShipToId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerShipToId

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) SetCustomerShipToId(v string)`

SetCustomerShipToId sets CustomerShipToId field to given value.

### HasCustomerShipToId

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) HasCustomerShipToId() bool`

HasCustomerShipToId returns a boolean if a field has been set.

### GetCustomerShipToCode

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetCustomerShipToCode() string`

GetCustomerShipToCode returns the CustomerShipToCode field if non-nil, zero value otherwise.

### GetCustomerShipToCodeOk

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetCustomerShipToCodeOk() (*string, bool)`

GetCustomerShipToCodeOk returns a tuple with the CustomerShipToCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerShipToCode

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) SetCustomerShipToCode(v string)`

SetCustomerShipToCode sets CustomerShipToCode field to given value.

### HasCustomerShipToCode

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) HasCustomerShipToCode() bool`

HasCustomerShipToCode returns a boolean if a field has been set.

### GetBuildingCode

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetBuildingCode() string`

GetBuildingCode returns the BuildingCode field if non-nil, zero value otherwise.

### GetBuildingCodeOk

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetBuildingCodeOk() (*string, bool)`

GetBuildingCodeOk returns a tuple with the BuildingCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildingCode

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) SetBuildingCode(v string)`

SetBuildingCode sets BuildingCode field to given value.

### HasBuildingCode

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) HasBuildingCode() bool`

HasBuildingCode returns a boolean if a field has been set.

### GetPeriodDisplay

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetPeriodDisplay() string`

GetPeriodDisplay returns the PeriodDisplay field if non-nil, zero value otherwise.

### GetPeriodDisplayOk

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetPeriodDisplayOk() (*string, bool)`

GetPeriodDisplayOk returns a tuple with the PeriodDisplay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriodDisplay

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) SetPeriodDisplay(v string)`

SetPeriodDisplay sets PeriodDisplay field to given value.

### HasPeriodDisplay

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) HasPeriodDisplay() bool`

HasPeriodDisplay returns a boolean if a field has been set.

### GetInvoiceDate

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetInvoiceDate() time.Time`

GetInvoiceDate returns the InvoiceDate field if non-nil, zero value otherwise.

### GetInvoiceDateOk

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetInvoiceDateOk() (*time.Time, bool)`

GetInvoiceDateOk returns a tuple with the InvoiceDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceDate

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) SetInvoiceDate(v time.Time)`

SetInvoiceDate sets InvoiceDate field to given value.

### HasInvoiceDate

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) HasInvoiceDate() bool`

HasInvoiceDate returns a boolean if a field has been set.

### GetCurrencyCode

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetCurrencyCode() string`

GetCurrencyCode returns the CurrencyCode field if non-nil, zero value otherwise.

### GetCurrencyCodeOk

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetCurrencyCodeOk() (*string, bool)`

GetCurrencyCodeOk returns a tuple with the CurrencyCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyCode

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) SetCurrencyCode(v string)`

SetCurrencyCode sets CurrencyCode field to given value.

### HasCurrencyCode

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) HasCurrencyCode() bool`

HasCurrencyCode returns a boolean if a field has been set.

### GetExchangeRate

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetExchangeRate() float64`

GetExchangeRate returns the ExchangeRate field if non-nil, zero value otherwise.

### GetExchangeRateOk

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetExchangeRateOk() (*float64, bool)`

GetExchangeRateOk returns a tuple with the ExchangeRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExchangeRate

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) SetExchangeRate(v float64)`

SetExchangeRate sets ExchangeRate field to given value.

### HasExchangeRate

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) HasExchangeRate() bool`

HasExchangeRate returns a boolean if a field has been set.

### GetTerms

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetTerms() string`

GetTerms returns the Terms field if non-nil, zero value otherwise.

### GetTermsOk

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetTermsOk() (*string, bool)`

GetTermsOk returns a tuple with the Terms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTerms

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) SetTerms(v string)`

SetTerms sets Terms field to given value.

### HasTerms

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) HasTerms() bool`

HasTerms returns a boolean if a field has been set.

### GetDueDate

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetDueDate() time.Time`

GetDueDate returns the DueDate field if non-nil, zero value otherwise.

### GetDueDateOk

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetDueDateOk() (*time.Time, bool)`

GetDueDateOk returns a tuple with the DueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueDate

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) SetDueDate(v time.Time)`

SetDueDate sets DueDate field to given value.

### HasDueDate

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) HasDueDate() bool`

HasDueDate returns a boolean if a field has been set.

### GetInvoiceNote

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetInvoiceNote() string`

GetInvoiceNote returns the InvoiceNote field if non-nil, zero value otherwise.

### GetInvoiceNoteOk

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetInvoiceNoteOk() (*string, bool)`

GetInvoiceNoteOk returns a tuple with the InvoiceNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceNote

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) SetInvoiceNote(v string)`

SetInvoiceNote sets InvoiceNote field to given value.

### HasInvoiceNote

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) HasInvoiceNote() bool`

HasInvoiceNote returns a boolean if a field has been set.

### GetInternalNote

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetInternalNote() string`

GetInternalNote returns the InternalNote field if non-nil, zero value otherwise.

### GetInternalNoteOk

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetInternalNoteOk() (*string, bool)`

GetInternalNoteOk returns a tuple with the InternalNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInternalNote

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) SetInternalNote(v string)`

SetInternalNote sets InternalNote field to given value.

### HasInternalNote

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) HasInternalNote() bool`

HasInternalNote returns a boolean if a field has been set.

### GetInvoiceStatus

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetInvoiceStatus() string`

GetInvoiceStatus returns the InvoiceStatus field if non-nil, zero value otherwise.

### GetInvoiceStatusOk

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetInvoiceStatusOk() (*string, bool)`

GetInvoiceStatusOk returns a tuple with the InvoiceStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceStatus

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) SetInvoiceStatus(v string)`

SetInvoiceStatus sets InvoiceStatus field to given value.

### HasInvoiceStatus

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) HasInvoiceStatus() bool`

HasInvoiceStatus returns a boolean if a field has been set.

### GetGovernmentIssuedNumber

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetGovernmentIssuedNumber() string`

GetGovernmentIssuedNumber returns the GovernmentIssuedNumber field if non-nil, zero value otherwise.

### GetGovernmentIssuedNumberOk

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetGovernmentIssuedNumberOk() (*string, bool)`

GetGovernmentIssuedNumberOk returns a tuple with the GovernmentIssuedNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGovernmentIssuedNumber

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) SetGovernmentIssuedNumber(v string)`

SetGovernmentIssuedNumber sets GovernmentIssuedNumber field to given value.

### HasGovernmentIssuedNumber

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) HasGovernmentIssuedNumber() bool`

HasGovernmentIssuedNumber returns a boolean if a field has been set.

### GetPoId

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetPoId() string`

GetPoId returns the PoId field if non-nil, zero value otherwise.

### GetPoIdOk

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetPoIdOk() (*string, bool)`

GetPoIdOk returns a tuple with the PoId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoId

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) SetPoId(v string)`

SetPoId sets PoId field to given value.

### HasPoId

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) HasPoId() bool`

HasPoId returns a boolean if a field has been set.

### GetPoNumber

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetPoNumber() string`

GetPoNumber returns the PoNumber field if non-nil, zero value otherwise.

### GetPoNumberOk

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetPoNumberOk() (*string, bool)`

GetPoNumberOk returns a tuple with the PoNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoNumber

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) SetPoNumber(v string)`

SetPoNumber sets PoNumber field to given value.

### HasPoNumber

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) HasPoNumber() bool`

HasPoNumber returns a boolean if a field has been set.

### GetPastDueReasonCode

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetPastDueReasonCode() string`

GetPastDueReasonCode returns the PastDueReasonCode field if non-nil, zero value otherwise.

### GetPastDueReasonCodeOk

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetPastDueReasonCodeOk() (*string, bool)`

GetPastDueReasonCodeOk returns a tuple with the PastDueReasonCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPastDueReasonCode

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) SetPastDueReasonCode(v string)`

SetPastDueReasonCode sets PastDueReasonCode field to given value.

### HasPastDueReasonCode

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) HasPastDueReasonCode() bool`

HasPastDueReasonCode returns a boolean if a field has been set.

### GetLines

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetLines() []LinesItem7`

GetLines returns the Lines field if non-nil, zero value otherwise.

### GetLinesOk

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetLinesOk() (*[]LinesItem7, bool)`

GetLinesOk returns a tuple with the Lines field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLines

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) SetLines(v []LinesItem7)`

SetLines sets Lines field to given value.

### HasLines

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) HasLines() bool`

HasLines returns a boolean if a field has been set.

### GetLineId

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetLineId() string`

GetLineId returns the LineId field if non-nil, zero value otherwise.

### GetLineIdOk

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetLineIdOk() (*string, bool)`

GetLineIdOk returns a tuple with the LineId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineId

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) SetLineId(v string)`

SetLineId sets LineId field to given value.

### HasLineId

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) HasLineId() bool`

HasLineId returns a boolean if a field has been set.

### GetAccountId

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetAccountId() string`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetAccountIdOk() (*string, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) SetAccountId(v string)`

SetAccountId sets AccountId field to given value.

### HasAccountId

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) HasAccountId() bool`

HasAccountId returns a boolean if a field has been set.

### GetAccountNumber

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetAccountNumber() string`

GetAccountNumber returns the AccountNumber field if non-nil, zero value otherwise.

### GetAccountNumberOk

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetAccountNumberOk() (*string, bool)`

GetAccountNumberOk returns a tuple with the AccountNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumber

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) SetAccountNumber(v string)`

SetAccountNumber sets AccountNumber field to given value.

### HasAccountNumber

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) HasAccountNumber() bool`

HasAccountNumber returns a boolean if a field has been set.

### GetPartId

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetPartNumber

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetPartNumber() string`

GetPartNumber returns the PartNumber field if non-nil, zero value otherwise.

### GetPartNumberOk

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetPartNumberOk() (*string, bool)`

GetPartNumberOk returns a tuple with the PartNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumber

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) SetPartNumber(v string)`

SetPartNumber sets PartNumber field to given value.

### HasPartNumber

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) HasPartNumber() bool`

HasPartNumber returns a boolean if a field has been set.

### GetDescription

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetReferenceNo

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetReferenceNo() string`

GetReferenceNo returns the ReferenceNo field if non-nil, zero value otherwise.

### GetReferenceNoOk

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetReferenceNoOk() (*string, bool)`

GetReferenceNoOk returns a tuple with the ReferenceNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferenceNo

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) SetReferenceNo(v string)`

SetReferenceNo sets ReferenceNo field to given value.

### HasReferenceNo

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) HasReferenceNo() bool`

HasReferenceNo returns a boolean if a field has been set.

### GetUnitPrice

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetUnitPrice() float64`

GetUnitPrice returns the UnitPrice field if non-nil, zero value otherwise.

### GetUnitPriceOk

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetUnitPriceOk() (*float64, bool)`

GetUnitPriceOk returns a tuple with the UnitPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitPrice

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) SetUnitPrice(v float64)`

SetUnitPrice sets UnitPrice field to given value.

### HasUnitPrice

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) HasUnitPrice() bool`

HasUnitPrice returns a boolean if a field has been set.

### GetQuantity

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetAccountingJobNumber

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetAccountingJobNumber() string`

GetAccountingJobNumber returns the AccountingJobNumber field if non-nil, zero value otherwise.

### GetAccountingJobNumberOk

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetAccountingJobNumberOk() (*string, bool)`

GetAccountingJobNumberOk returns a tuple with the AccountingJobNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountingJobNumber

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) SetAccountingJobNumber(v string)`

SetAccountingJobNumber sets AccountingJobNumber field to given value.

### HasAccountingJobNumber

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) HasAccountingJobNumber() bool`

HasAccountingJobNumber returns a boolean if a field has been set.

### GetItemTaxCode

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetItemTaxCode() string`

GetItemTaxCode returns the ItemTaxCode field if non-nil, zero value otherwise.

### GetItemTaxCodeOk

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetItemTaxCodeOk() (*string, bool)`

GetItemTaxCodeOk returns a tuple with the ItemTaxCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItemTaxCode

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) SetItemTaxCode(v string)`

SetItemTaxCode sets ItemTaxCode field to given value.

### HasItemTaxCode

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) HasItemTaxCode() bool`

HasItemTaxCode returns a boolean if a field has been set.

### GetTaxCodes

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetTaxCodes() []string`

GetTaxCodes returns the TaxCodes field if non-nil, zero value otherwise.

### GetTaxCodesOk

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) GetTaxCodesOk() (*[]string, bool)`

GetTaxCodesOk returns a tuple with the TaxCodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxCodes

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) SetTaxCodes(v []string)`

SetTaxCodes sets TaxCodes field to given value.

### HasTaxCodes

`func (o *AccountsReceivableInvoicesApiUpdateARInvoiceRequest) HasTaxCodes() bool`

HasTaxCodes returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


