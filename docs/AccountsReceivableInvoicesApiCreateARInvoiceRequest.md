# AccountsReceivableInvoicesApiCreateARInvoiceRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**InvoiceNumber** | Pointer to **string** | The AR invoice number. | [optional] 
**CustomerId** | Pointer to **string** | The AR customer ID. | [optional] 
**CustomerCode** | Pointer to **string** | The AR customer code, typically an abbreviated name for the customer. | [optional] 
**CustomerBillToId** | Pointer to **string** | The AR customer bill to address ID. | [optional] 
**CustomerBillToCode** | Pointer to **string** | The AR customer bill to address code. | [optional] 
**CustomerShipToId** | Pointer to **string** | The AR customer ship to address ID. | [optional] 
**CustomerShipToCode** | Pointer to **string** | The AR customer ship to address. | [optional] 
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
**Type** | Pointer to **string** | The AR invoice type. | [optional] 
**CreatedById** | Pointer to **string** | The ID of the user who created the record. | [optional] 
**CreatedDate** | Pointer to **time.Time** | The date on which an AR invoice was created. | [optional] 
**ModifiedById** | Pointer to **string** | The ID of the user who last modified the record. | [optional] 
**ModifiedDate** | Pointer to **time.Time** | The date an AR invoice was modified. | [optional] 
**PoId** | Pointer to **string** | The AR invoice purchase order ID. | [optional] 
**PoNumber** | Pointer to **string** | The AR invoice purchase order number. | [optional] 
**CreditMemo** | Pointer to **bool** | Specify an AR invoice credit memo. | [optional] 
**Lines** | Pointer to [**[]LinesItem6**](LinesItem6.md) | A list of AR invoice lines. | [optional] 
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

### NewAccountsReceivableInvoicesApiCreateARInvoiceRequest

`func NewAccountsReceivableInvoicesApiCreateARInvoiceRequest() *AccountsReceivableInvoicesApiCreateARInvoiceRequest`

NewAccountsReceivableInvoicesApiCreateARInvoiceRequest instantiates a new AccountsReceivableInvoicesApiCreateARInvoiceRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccountsReceivableInvoicesApiCreateARInvoiceRequestWithDefaults

`func NewAccountsReceivableInvoicesApiCreateARInvoiceRequestWithDefaults() *AccountsReceivableInvoicesApiCreateARInvoiceRequest`

NewAccountsReceivableInvoicesApiCreateARInvoiceRequestWithDefaults instantiates a new AccountsReceivableInvoicesApiCreateARInvoiceRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetInvoiceNumber

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetInvoiceNumber() string`

GetInvoiceNumber returns the InvoiceNumber field if non-nil, zero value otherwise.

### GetInvoiceNumberOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetInvoiceNumberOk() (*string, bool)`

GetInvoiceNumberOk returns a tuple with the InvoiceNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceNumber

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) SetInvoiceNumber(v string)`

SetInvoiceNumber sets InvoiceNumber field to given value.

### HasInvoiceNumber

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) HasInvoiceNumber() bool`

HasInvoiceNumber returns a boolean if a field has been set.

### GetCustomerId

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### GetCustomerCode

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetCustomerCode() string`

GetCustomerCode returns the CustomerCode field if non-nil, zero value otherwise.

### GetCustomerCodeOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetCustomerCodeOk() (*string, bool)`

GetCustomerCodeOk returns a tuple with the CustomerCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerCode

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) SetCustomerCode(v string)`

SetCustomerCode sets CustomerCode field to given value.

### HasCustomerCode

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) HasCustomerCode() bool`

HasCustomerCode returns a boolean if a field has been set.

### GetCustomerBillToId

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetCustomerBillToId() string`

GetCustomerBillToId returns the CustomerBillToId field if non-nil, zero value otherwise.

### GetCustomerBillToIdOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetCustomerBillToIdOk() (*string, bool)`

GetCustomerBillToIdOk returns a tuple with the CustomerBillToId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerBillToId

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) SetCustomerBillToId(v string)`

SetCustomerBillToId sets CustomerBillToId field to given value.

### HasCustomerBillToId

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) HasCustomerBillToId() bool`

HasCustomerBillToId returns a boolean if a field has been set.

### GetCustomerBillToCode

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetCustomerBillToCode() string`

GetCustomerBillToCode returns the CustomerBillToCode field if non-nil, zero value otherwise.

### GetCustomerBillToCodeOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetCustomerBillToCodeOk() (*string, bool)`

GetCustomerBillToCodeOk returns a tuple with the CustomerBillToCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerBillToCode

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) SetCustomerBillToCode(v string)`

SetCustomerBillToCode sets CustomerBillToCode field to given value.

### HasCustomerBillToCode

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) HasCustomerBillToCode() bool`

HasCustomerBillToCode returns a boolean if a field has been set.

### GetCustomerShipToId

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetCustomerShipToId() string`

GetCustomerShipToId returns the CustomerShipToId field if non-nil, zero value otherwise.

### GetCustomerShipToIdOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetCustomerShipToIdOk() (*string, bool)`

GetCustomerShipToIdOk returns a tuple with the CustomerShipToId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerShipToId

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) SetCustomerShipToId(v string)`

SetCustomerShipToId sets CustomerShipToId field to given value.

### HasCustomerShipToId

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) HasCustomerShipToId() bool`

HasCustomerShipToId returns a boolean if a field has been set.

### GetCustomerShipToCode

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetCustomerShipToCode() string`

GetCustomerShipToCode returns the CustomerShipToCode field if non-nil, zero value otherwise.

### GetCustomerShipToCodeOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetCustomerShipToCodeOk() (*string, bool)`

GetCustomerShipToCodeOk returns a tuple with the CustomerShipToCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerShipToCode

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) SetCustomerShipToCode(v string)`

SetCustomerShipToCode sets CustomerShipToCode field to given value.

### HasCustomerShipToCode

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) HasCustomerShipToCode() bool`

HasCustomerShipToCode returns a boolean if a field has been set.

### GetBuildingCode

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetBuildingCode() string`

GetBuildingCode returns the BuildingCode field if non-nil, zero value otherwise.

### GetBuildingCodeOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetBuildingCodeOk() (*string, bool)`

GetBuildingCodeOk returns a tuple with the BuildingCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildingCode

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) SetBuildingCode(v string)`

SetBuildingCode sets BuildingCode field to given value.

### HasBuildingCode

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) HasBuildingCode() bool`

HasBuildingCode returns a boolean if a field has been set.

### GetPeriodDisplay

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetPeriodDisplay() string`

GetPeriodDisplay returns the PeriodDisplay field if non-nil, zero value otherwise.

### GetPeriodDisplayOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetPeriodDisplayOk() (*string, bool)`

GetPeriodDisplayOk returns a tuple with the PeriodDisplay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriodDisplay

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) SetPeriodDisplay(v string)`

SetPeriodDisplay sets PeriodDisplay field to given value.

### HasPeriodDisplay

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) HasPeriodDisplay() bool`

HasPeriodDisplay returns a boolean if a field has been set.

### GetInvoiceDate

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetInvoiceDate() time.Time`

GetInvoiceDate returns the InvoiceDate field if non-nil, zero value otherwise.

### GetInvoiceDateOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetInvoiceDateOk() (*time.Time, bool)`

GetInvoiceDateOk returns a tuple with the InvoiceDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceDate

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) SetInvoiceDate(v time.Time)`

SetInvoiceDate sets InvoiceDate field to given value.

### HasInvoiceDate

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) HasInvoiceDate() bool`

HasInvoiceDate returns a boolean if a field has been set.

### GetCurrencyCode

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetCurrencyCode() string`

GetCurrencyCode returns the CurrencyCode field if non-nil, zero value otherwise.

### GetCurrencyCodeOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetCurrencyCodeOk() (*string, bool)`

GetCurrencyCodeOk returns a tuple with the CurrencyCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyCode

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) SetCurrencyCode(v string)`

SetCurrencyCode sets CurrencyCode field to given value.

### HasCurrencyCode

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) HasCurrencyCode() bool`

HasCurrencyCode returns a boolean if a field has been set.

### GetExchangeRate

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetExchangeRate() float64`

GetExchangeRate returns the ExchangeRate field if non-nil, zero value otherwise.

### GetExchangeRateOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetExchangeRateOk() (*float64, bool)`

GetExchangeRateOk returns a tuple with the ExchangeRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExchangeRate

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) SetExchangeRate(v float64)`

SetExchangeRate sets ExchangeRate field to given value.

### HasExchangeRate

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) HasExchangeRate() bool`

HasExchangeRate returns a boolean if a field has been set.

### GetTerms

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetTerms() string`

GetTerms returns the Terms field if non-nil, zero value otherwise.

### GetTermsOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetTermsOk() (*string, bool)`

GetTermsOk returns a tuple with the Terms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTerms

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) SetTerms(v string)`

SetTerms sets Terms field to given value.

### HasTerms

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) HasTerms() bool`

HasTerms returns a boolean if a field has been set.

### GetDueDate

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetDueDate() time.Time`

GetDueDate returns the DueDate field if non-nil, zero value otherwise.

### GetDueDateOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetDueDateOk() (*time.Time, bool)`

GetDueDateOk returns a tuple with the DueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueDate

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) SetDueDate(v time.Time)`

SetDueDate sets DueDate field to given value.

### HasDueDate

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) HasDueDate() bool`

HasDueDate returns a boolean if a field has been set.

### GetInvoiceNote

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetInvoiceNote() string`

GetInvoiceNote returns the InvoiceNote field if non-nil, zero value otherwise.

### GetInvoiceNoteOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetInvoiceNoteOk() (*string, bool)`

GetInvoiceNoteOk returns a tuple with the InvoiceNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceNote

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) SetInvoiceNote(v string)`

SetInvoiceNote sets InvoiceNote field to given value.

### HasInvoiceNote

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) HasInvoiceNote() bool`

HasInvoiceNote returns a boolean if a field has been set.

### GetInternalNote

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetInternalNote() string`

GetInternalNote returns the InternalNote field if non-nil, zero value otherwise.

### GetInternalNoteOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetInternalNoteOk() (*string, bool)`

GetInternalNoteOk returns a tuple with the InternalNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInternalNote

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) SetInternalNote(v string)`

SetInternalNote sets InternalNote field to given value.

### HasInternalNote

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) HasInternalNote() bool`

HasInternalNote returns a boolean if a field has been set.

### GetInvoiceStatus

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetInvoiceStatus() string`

GetInvoiceStatus returns the InvoiceStatus field if non-nil, zero value otherwise.

### GetInvoiceStatusOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetInvoiceStatusOk() (*string, bool)`

GetInvoiceStatusOk returns a tuple with the InvoiceStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceStatus

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) SetInvoiceStatus(v string)`

SetInvoiceStatus sets InvoiceStatus field to given value.

### HasInvoiceStatus

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) HasInvoiceStatus() bool`

HasInvoiceStatus returns a boolean if a field has been set.

### GetGovernmentIssuedNumber

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetGovernmentIssuedNumber() string`

GetGovernmentIssuedNumber returns the GovernmentIssuedNumber field if non-nil, zero value otherwise.

### GetGovernmentIssuedNumberOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetGovernmentIssuedNumberOk() (*string, bool)`

GetGovernmentIssuedNumberOk returns a tuple with the GovernmentIssuedNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGovernmentIssuedNumber

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) SetGovernmentIssuedNumber(v string)`

SetGovernmentIssuedNumber sets GovernmentIssuedNumber field to given value.

### HasGovernmentIssuedNumber

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) HasGovernmentIssuedNumber() bool`

HasGovernmentIssuedNumber returns a boolean if a field has been set.

### GetType

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) HasType() bool`

HasType returns a boolean if a field has been set.

### GetCreatedById

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetCreatedById() string`

GetCreatedById returns the CreatedById field if non-nil, zero value otherwise.

### GetCreatedByIdOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetCreatedByIdOk() (*string, bool)`

GetCreatedByIdOk returns a tuple with the CreatedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedById

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) SetCreatedById(v string)`

SetCreatedById sets CreatedById field to given value.

### HasCreatedById

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) HasCreatedById() bool`

HasCreatedById returns a boolean if a field has been set.

### GetCreatedDate

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.

### GetModifiedById

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetModifiedDate

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetModifiedDate() time.Time`

GetModifiedDate returns the ModifiedDate field if non-nil, zero value otherwise.

### GetModifiedDateOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetModifiedDateOk() (*time.Time, bool)`

GetModifiedDateOk returns a tuple with the ModifiedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDate

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) SetModifiedDate(v time.Time)`

SetModifiedDate sets ModifiedDate field to given value.

### HasModifiedDate

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) HasModifiedDate() bool`

HasModifiedDate returns a boolean if a field has been set.

### GetPoId

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetPoId() string`

GetPoId returns the PoId field if non-nil, zero value otherwise.

### GetPoIdOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetPoIdOk() (*string, bool)`

GetPoIdOk returns a tuple with the PoId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoId

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) SetPoId(v string)`

SetPoId sets PoId field to given value.

### HasPoId

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) HasPoId() bool`

HasPoId returns a boolean if a field has been set.

### GetPoNumber

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetPoNumber() string`

GetPoNumber returns the PoNumber field if non-nil, zero value otherwise.

### GetPoNumberOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetPoNumberOk() (*string, bool)`

GetPoNumberOk returns a tuple with the PoNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoNumber

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) SetPoNumber(v string)`

SetPoNumber sets PoNumber field to given value.

### HasPoNumber

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) HasPoNumber() bool`

HasPoNumber returns a boolean if a field has been set.

### GetCreditMemo

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetCreditMemo() bool`

GetCreditMemo returns the CreditMemo field if non-nil, zero value otherwise.

### GetCreditMemoOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetCreditMemoOk() (*bool, bool)`

GetCreditMemoOk returns a tuple with the CreditMemo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditMemo

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) SetCreditMemo(v bool)`

SetCreditMemo sets CreditMemo field to given value.

### HasCreditMemo

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) HasCreditMemo() bool`

HasCreditMemo returns a boolean if a field has been set.

### GetLines

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetLines() []LinesItem6`

GetLines returns the Lines field if non-nil, zero value otherwise.

### GetLinesOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetLinesOk() (*[]LinesItem6, bool)`

GetLinesOk returns a tuple with the Lines field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLines

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) SetLines(v []LinesItem6)`

SetLines sets Lines field to given value.

### HasLines

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) HasLines() bool`

HasLines returns a boolean if a field has been set.

### GetLineId

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetLineId() string`

GetLineId returns the LineId field if non-nil, zero value otherwise.

### GetLineIdOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetLineIdOk() (*string, bool)`

GetLineIdOk returns a tuple with the LineId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineId

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) SetLineId(v string)`

SetLineId sets LineId field to given value.

### HasLineId

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) HasLineId() bool`

HasLineId returns a boolean if a field has been set.

### GetAccountId

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetAccountId() string`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetAccountIdOk() (*string, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) SetAccountId(v string)`

SetAccountId sets AccountId field to given value.

### HasAccountId

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) HasAccountId() bool`

HasAccountId returns a boolean if a field has been set.

### GetAccountNumber

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetAccountNumber() string`

GetAccountNumber returns the AccountNumber field if non-nil, zero value otherwise.

### GetAccountNumberOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetAccountNumberOk() (*string, bool)`

GetAccountNumberOk returns a tuple with the AccountNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumber

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) SetAccountNumber(v string)`

SetAccountNumber sets AccountNumber field to given value.

### HasAccountNumber

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) HasAccountNumber() bool`

HasAccountNumber returns a boolean if a field has been set.

### GetPartId

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetPartNumber

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetPartNumber() string`

GetPartNumber returns the PartNumber field if non-nil, zero value otherwise.

### GetPartNumberOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetPartNumberOk() (*string, bool)`

GetPartNumberOk returns a tuple with the PartNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumber

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) SetPartNumber(v string)`

SetPartNumber sets PartNumber field to given value.

### HasPartNumber

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) HasPartNumber() bool`

HasPartNumber returns a boolean if a field has been set.

### GetDescription

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetReferenceNo

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetReferenceNo() string`

GetReferenceNo returns the ReferenceNo field if non-nil, zero value otherwise.

### GetReferenceNoOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetReferenceNoOk() (*string, bool)`

GetReferenceNoOk returns a tuple with the ReferenceNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferenceNo

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) SetReferenceNo(v string)`

SetReferenceNo sets ReferenceNo field to given value.

### HasReferenceNo

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) HasReferenceNo() bool`

HasReferenceNo returns a boolean if a field has been set.

### GetUnitPrice

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetUnitPrice() float64`

GetUnitPrice returns the UnitPrice field if non-nil, zero value otherwise.

### GetUnitPriceOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetUnitPriceOk() (*float64, bool)`

GetUnitPriceOk returns a tuple with the UnitPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitPrice

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) SetUnitPrice(v float64)`

SetUnitPrice sets UnitPrice field to given value.

### HasUnitPrice

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) HasUnitPrice() bool`

HasUnitPrice returns a boolean if a field has been set.

### GetQuantity

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetAccountingJobNumber

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetAccountingJobNumber() string`

GetAccountingJobNumber returns the AccountingJobNumber field if non-nil, zero value otherwise.

### GetAccountingJobNumberOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetAccountingJobNumberOk() (*string, bool)`

GetAccountingJobNumberOk returns a tuple with the AccountingJobNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountingJobNumber

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) SetAccountingJobNumber(v string)`

SetAccountingJobNumber sets AccountingJobNumber field to given value.

### HasAccountingJobNumber

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) HasAccountingJobNumber() bool`

HasAccountingJobNumber returns a boolean if a field has been set.

### GetCustomerShipperId

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetCustomerShipperId() string`

GetCustomerShipperId returns the CustomerShipperId field if non-nil, zero value otherwise.

### GetCustomerShipperIdOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetCustomerShipperIdOk() (*string, bool)`

GetCustomerShipperIdOk returns a tuple with the CustomerShipperId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerShipperId

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) SetCustomerShipperId(v string)`

SetCustomerShipperId sets CustomerShipperId field to given value.

### HasCustomerShipperId

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) HasCustomerShipperId() bool`

HasCustomerShipperId returns a boolean if a field has been set.

### GetItemTaxCode

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetItemTaxCode() string`

GetItemTaxCode returns the ItemTaxCode field if non-nil, zero value otherwise.

### GetItemTaxCodeOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetItemTaxCodeOk() (*string, bool)`

GetItemTaxCodeOk returns a tuple with the ItemTaxCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItemTaxCode

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) SetItemTaxCode(v string)`

SetItemTaxCode sets ItemTaxCode field to given value.

### HasItemTaxCode

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) HasItemTaxCode() bool`

HasItemTaxCode returns a boolean if a field has been set.

### GetTaxCodes

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetTaxCodes() []string`

GetTaxCodes returns the TaxCodes field if non-nil, zero value otherwise.

### GetTaxCodesOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) GetTaxCodesOk() (*[]string, bool)`

GetTaxCodesOk returns a tuple with the TaxCodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxCodes

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) SetTaxCodes(v []string)`

SetTaxCodes sets TaxCodes field to given value.

### HasTaxCodes

`func (o *AccountsReceivableInvoicesApiCreateARInvoiceRequest) HasTaxCodes() bool`

HasTaxCodes returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


