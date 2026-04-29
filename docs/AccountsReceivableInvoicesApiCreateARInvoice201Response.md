# AccountsReceivableInvoicesApiCreateARInvoice201Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | The AR invoice ID. | [optional] 
**InvoiceNumber** | Pointer to **string** | The AR invoice number. | [optional] 
**CreditMemo** | Pointer to **int32** | Specify an AR invoice credit memo. | [optional] 
**CustomerId** | Pointer to **string** | The AR customer ID. | [optional] 
**CustomerCode** | Pointer to **string** | The AR customer code, typically an abbreviated name for the customer. | [optional] 
**CustomerBillToId** | Pointer to **string** | The AR customer bill to address ID. | [optional] 
**CustomerBillToCode** | Pointer to **string** | The AR customer bill to address code. | [optional] 
**CustomerShipToId** | Pointer to **string** | The AR customer ship to address ID. | [optional] 
**CustomerShipToCode** | Pointer to **string** | The AR customer ship to address. | [optional] 
**CustomerOrderNos** | Pointer to **string** | The AR customer order numbers. | [optional] 
**CustomerPONo** | Pointer to **string** | The AR customer purchase order number. | [optional] 
**BuildingCode** | Pointer to **string** | The code used to look up the building resource. | [optional] 
**PeriodDisplay** | Pointer to **string** | The period in which an AR invoice is recorded. | [optional] 
**TransactionDate** | Pointer to **time.Time** | The date on which an AR transaction was recorded. | [optional] 
**CurrencyCode** | Pointer to **string** | The AR invoice currency code. | [optional] 
**ExchangeRate** | Pointer to **float64** | The AR invoice exchange rate. | [optional] 
**Terms** | Pointer to **string** | The AR terms. | [optional] 
**DueDate** | Pointer to **time.Time** | The AR invoice due date. | [optional] 
**InvoiceNote** | Pointer to **string** | A note added to an AR invoice. | [optional] 
**InternalNote** | Pointer to **string** | An internal note added to an AR invoice. | [optional] 
**VoucherNumber** | Pointer to **string** | The AR invoice voucher number. | [optional] 
**Status** | Pointer to **string** | The AR invoice status. | [optional] 
**GovernmentIssuedNumber** | Pointer to **string** | The AR invoice government issued number. | [optional] 
**Type** | Pointer to **string** | The AR invoice type. | [optional] 
**CreatedById** | Pointer to **string** | The ID of the user who created the record. | [optional] 
**CreatedDate** | Pointer to **time.Time** | The date an AR invoice was created. | [optional] 
**ModifiedById** | Pointer to **string** | The ID of the user who last modified the record. | [optional] 
**ModifiedDate** | Pointer to **time.Time** | The date an AR invoice was modified. | [optional] 
**TaxableDate** | Pointer to **time.Time** | The date the AR invoice tax was calculated. | [optional] 
**Amount** | Pointer to **float64** | The AR invoice amount. | [optional] 
**CurrencyAmount** | Pointer to **float64** | The AR invoice currency amount. | [optional] 
**Paid** | Pointer to **bool** | Specify that an AR invoice has been paid. | [optional] 
**PaidDate** | Pointer to **time.Time** | The date an AR invoice was paid. | [optional] 
**ExpectedPayDate** | Pointer to **time.Time** | The date an AR invoice payment is due. | [optional] 
**PaidPeriod** | Pointer to **string** | The period in which an AR invoice was paid. | [optional] 
**Discount** | Pointer to **float64** | The discount applicable to an AR invoice. | [optional] 
**DiscountDueDate** | Pointer to **time.Time** | The date an AR invoice discount is due. | [optional] 
**Balance** | Pointer to **float64** | The AR invoice balance. | [optional] 
**CurrencyBalance** | Pointer to **float64** | The AR invoice currency balance. | [optional] 
**Void** | Pointer to **bool** | Specify that an AR invoice has been voided. | [optional] 
**ConsolidatedLinkId** | Pointer to **string** | The consolidated AR invoice ID. | [optional] 
**Booked** | Pointer to **bool** | Specify that an AR invoice has a booked status. | [optional] 
**ReferenceNo** | Pointer to **string** | The AR invoice reference number. | [optional] 
**ShipperNo** | Pointer to **string** | The AR invoice shipper number. | [optional] 
**PoNumber** | Pointer to **string** | The AR invoice purchase order number. | [optional] 
**PoId** | Pointer to **string** | The AR invoice purchase order ID. | [optional] 
**Lines** | Pointer to [**[]LinesItem5**](LinesItem5.md) | A list of AR invoice lines. | [optional] 

## Methods

### NewAccountsReceivableInvoicesApiCreateARInvoice201Response

`func NewAccountsReceivableInvoicesApiCreateARInvoice201Response() *AccountsReceivableInvoicesApiCreateARInvoice201Response`

NewAccountsReceivableInvoicesApiCreateARInvoice201Response instantiates a new AccountsReceivableInvoicesApiCreateARInvoice201Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccountsReceivableInvoicesApiCreateARInvoice201ResponseWithDefaults

`func NewAccountsReceivableInvoicesApiCreateARInvoice201ResponseWithDefaults() *AccountsReceivableInvoicesApiCreateARInvoice201Response`

NewAccountsReceivableInvoicesApiCreateARInvoice201ResponseWithDefaults instantiates a new AccountsReceivableInvoicesApiCreateARInvoice201Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) HasId() bool`

HasId returns a boolean if a field has been set.

### GetInvoiceNumber

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetInvoiceNumber() string`

GetInvoiceNumber returns the InvoiceNumber field if non-nil, zero value otherwise.

### GetInvoiceNumberOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetInvoiceNumberOk() (*string, bool)`

GetInvoiceNumberOk returns a tuple with the InvoiceNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceNumber

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) SetInvoiceNumber(v string)`

SetInvoiceNumber sets InvoiceNumber field to given value.

### HasInvoiceNumber

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) HasInvoiceNumber() bool`

HasInvoiceNumber returns a boolean if a field has been set.

### GetCreditMemo

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetCreditMemo() int32`

GetCreditMemo returns the CreditMemo field if non-nil, zero value otherwise.

### GetCreditMemoOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetCreditMemoOk() (*int32, bool)`

GetCreditMemoOk returns a tuple with the CreditMemo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditMemo

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) SetCreditMemo(v int32)`

SetCreditMemo sets CreditMemo field to given value.

### HasCreditMemo

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) HasCreditMemo() bool`

HasCreditMemo returns a boolean if a field has been set.

### GetCustomerId

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### GetCustomerCode

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetCustomerCode() string`

GetCustomerCode returns the CustomerCode field if non-nil, zero value otherwise.

### GetCustomerCodeOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetCustomerCodeOk() (*string, bool)`

GetCustomerCodeOk returns a tuple with the CustomerCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerCode

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) SetCustomerCode(v string)`

SetCustomerCode sets CustomerCode field to given value.

### HasCustomerCode

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) HasCustomerCode() bool`

HasCustomerCode returns a boolean if a field has been set.

### GetCustomerBillToId

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetCustomerBillToId() string`

GetCustomerBillToId returns the CustomerBillToId field if non-nil, zero value otherwise.

### GetCustomerBillToIdOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetCustomerBillToIdOk() (*string, bool)`

GetCustomerBillToIdOk returns a tuple with the CustomerBillToId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerBillToId

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) SetCustomerBillToId(v string)`

SetCustomerBillToId sets CustomerBillToId field to given value.

### HasCustomerBillToId

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) HasCustomerBillToId() bool`

HasCustomerBillToId returns a boolean if a field has been set.

### GetCustomerBillToCode

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetCustomerBillToCode() string`

GetCustomerBillToCode returns the CustomerBillToCode field if non-nil, zero value otherwise.

### GetCustomerBillToCodeOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetCustomerBillToCodeOk() (*string, bool)`

GetCustomerBillToCodeOk returns a tuple with the CustomerBillToCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerBillToCode

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) SetCustomerBillToCode(v string)`

SetCustomerBillToCode sets CustomerBillToCode field to given value.

### HasCustomerBillToCode

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) HasCustomerBillToCode() bool`

HasCustomerBillToCode returns a boolean if a field has been set.

### GetCustomerShipToId

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetCustomerShipToId() string`

GetCustomerShipToId returns the CustomerShipToId field if non-nil, zero value otherwise.

### GetCustomerShipToIdOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetCustomerShipToIdOk() (*string, bool)`

GetCustomerShipToIdOk returns a tuple with the CustomerShipToId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerShipToId

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) SetCustomerShipToId(v string)`

SetCustomerShipToId sets CustomerShipToId field to given value.

### HasCustomerShipToId

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) HasCustomerShipToId() bool`

HasCustomerShipToId returns a boolean if a field has been set.

### GetCustomerShipToCode

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetCustomerShipToCode() string`

GetCustomerShipToCode returns the CustomerShipToCode field if non-nil, zero value otherwise.

### GetCustomerShipToCodeOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetCustomerShipToCodeOk() (*string, bool)`

GetCustomerShipToCodeOk returns a tuple with the CustomerShipToCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerShipToCode

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) SetCustomerShipToCode(v string)`

SetCustomerShipToCode sets CustomerShipToCode field to given value.

### HasCustomerShipToCode

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) HasCustomerShipToCode() bool`

HasCustomerShipToCode returns a boolean if a field has been set.

### GetCustomerOrderNos

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetCustomerOrderNos() string`

GetCustomerOrderNos returns the CustomerOrderNos field if non-nil, zero value otherwise.

### GetCustomerOrderNosOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetCustomerOrderNosOk() (*string, bool)`

GetCustomerOrderNosOk returns a tuple with the CustomerOrderNos field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerOrderNos

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) SetCustomerOrderNos(v string)`

SetCustomerOrderNos sets CustomerOrderNos field to given value.

### HasCustomerOrderNos

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) HasCustomerOrderNos() bool`

HasCustomerOrderNos returns a boolean if a field has been set.

### GetCustomerPONo

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetCustomerPONo() string`

GetCustomerPONo returns the CustomerPONo field if non-nil, zero value otherwise.

### GetCustomerPONoOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetCustomerPONoOk() (*string, bool)`

GetCustomerPONoOk returns a tuple with the CustomerPONo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerPONo

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) SetCustomerPONo(v string)`

SetCustomerPONo sets CustomerPONo field to given value.

### HasCustomerPONo

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) HasCustomerPONo() bool`

HasCustomerPONo returns a boolean if a field has been set.

### GetBuildingCode

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetBuildingCode() string`

GetBuildingCode returns the BuildingCode field if non-nil, zero value otherwise.

### GetBuildingCodeOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetBuildingCodeOk() (*string, bool)`

GetBuildingCodeOk returns a tuple with the BuildingCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildingCode

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) SetBuildingCode(v string)`

SetBuildingCode sets BuildingCode field to given value.

### HasBuildingCode

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) HasBuildingCode() bool`

HasBuildingCode returns a boolean if a field has been set.

### GetPeriodDisplay

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetPeriodDisplay() string`

GetPeriodDisplay returns the PeriodDisplay field if non-nil, zero value otherwise.

### GetPeriodDisplayOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetPeriodDisplayOk() (*string, bool)`

GetPeriodDisplayOk returns a tuple with the PeriodDisplay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriodDisplay

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) SetPeriodDisplay(v string)`

SetPeriodDisplay sets PeriodDisplay field to given value.

### HasPeriodDisplay

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) HasPeriodDisplay() bool`

HasPeriodDisplay returns a boolean if a field has been set.

### GetTransactionDate

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetTransactionDate() time.Time`

GetTransactionDate returns the TransactionDate field if non-nil, zero value otherwise.

### GetTransactionDateOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetTransactionDateOk() (*time.Time, bool)`

GetTransactionDateOk returns a tuple with the TransactionDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransactionDate

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) SetTransactionDate(v time.Time)`

SetTransactionDate sets TransactionDate field to given value.

### HasTransactionDate

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) HasTransactionDate() bool`

HasTransactionDate returns a boolean if a field has been set.

### GetCurrencyCode

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetCurrencyCode() string`

GetCurrencyCode returns the CurrencyCode field if non-nil, zero value otherwise.

### GetCurrencyCodeOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetCurrencyCodeOk() (*string, bool)`

GetCurrencyCodeOk returns a tuple with the CurrencyCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyCode

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) SetCurrencyCode(v string)`

SetCurrencyCode sets CurrencyCode field to given value.

### HasCurrencyCode

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) HasCurrencyCode() bool`

HasCurrencyCode returns a boolean if a field has been set.

### GetExchangeRate

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetExchangeRate() float64`

GetExchangeRate returns the ExchangeRate field if non-nil, zero value otherwise.

### GetExchangeRateOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetExchangeRateOk() (*float64, bool)`

GetExchangeRateOk returns a tuple with the ExchangeRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExchangeRate

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) SetExchangeRate(v float64)`

SetExchangeRate sets ExchangeRate field to given value.

### HasExchangeRate

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) HasExchangeRate() bool`

HasExchangeRate returns a boolean if a field has been set.

### GetTerms

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetTerms() string`

GetTerms returns the Terms field if non-nil, zero value otherwise.

### GetTermsOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetTermsOk() (*string, bool)`

GetTermsOk returns a tuple with the Terms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTerms

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) SetTerms(v string)`

SetTerms sets Terms field to given value.

### HasTerms

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) HasTerms() bool`

HasTerms returns a boolean if a field has been set.

### GetDueDate

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetDueDate() time.Time`

GetDueDate returns the DueDate field if non-nil, zero value otherwise.

### GetDueDateOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetDueDateOk() (*time.Time, bool)`

GetDueDateOk returns a tuple with the DueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueDate

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) SetDueDate(v time.Time)`

SetDueDate sets DueDate field to given value.

### HasDueDate

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) HasDueDate() bool`

HasDueDate returns a boolean if a field has been set.

### GetInvoiceNote

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetInvoiceNote() string`

GetInvoiceNote returns the InvoiceNote field if non-nil, zero value otherwise.

### GetInvoiceNoteOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetInvoiceNoteOk() (*string, bool)`

GetInvoiceNoteOk returns a tuple with the InvoiceNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceNote

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) SetInvoiceNote(v string)`

SetInvoiceNote sets InvoiceNote field to given value.

### HasInvoiceNote

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) HasInvoiceNote() bool`

HasInvoiceNote returns a boolean if a field has been set.

### GetInternalNote

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetInternalNote() string`

GetInternalNote returns the InternalNote field if non-nil, zero value otherwise.

### GetInternalNoteOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetInternalNoteOk() (*string, bool)`

GetInternalNoteOk returns a tuple with the InternalNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInternalNote

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) SetInternalNote(v string)`

SetInternalNote sets InternalNote field to given value.

### HasInternalNote

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) HasInternalNote() bool`

HasInternalNote returns a boolean if a field has been set.

### GetVoucherNumber

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetVoucherNumber() string`

GetVoucherNumber returns the VoucherNumber field if non-nil, zero value otherwise.

### GetVoucherNumberOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetVoucherNumberOk() (*string, bool)`

GetVoucherNumberOk returns a tuple with the VoucherNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoucherNumber

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) SetVoucherNumber(v string)`

SetVoucherNumber sets VoucherNumber field to given value.

### HasVoucherNumber

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) HasVoucherNumber() bool`

HasVoucherNumber returns a boolean if a field has been set.

### GetStatus

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetGovernmentIssuedNumber

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetGovernmentIssuedNumber() string`

GetGovernmentIssuedNumber returns the GovernmentIssuedNumber field if non-nil, zero value otherwise.

### GetGovernmentIssuedNumberOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetGovernmentIssuedNumberOk() (*string, bool)`

GetGovernmentIssuedNumberOk returns a tuple with the GovernmentIssuedNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGovernmentIssuedNumber

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) SetGovernmentIssuedNumber(v string)`

SetGovernmentIssuedNumber sets GovernmentIssuedNumber field to given value.

### HasGovernmentIssuedNumber

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) HasGovernmentIssuedNumber() bool`

HasGovernmentIssuedNumber returns a boolean if a field has been set.

### GetType

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) HasType() bool`

HasType returns a boolean if a field has been set.

### GetCreatedById

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetCreatedById() string`

GetCreatedById returns the CreatedById field if non-nil, zero value otherwise.

### GetCreatedByIdOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetCreatedByIdOk() (*string, bool)`

GetCreatedByIdOk returns a tuple with the CreatedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedById

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) SetCreatedById(v string)`

SetCreatedById sets CreatedById field to given value.

### HasCreatedById

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) HasCreatedById() bool`

HasCreatedById returns a boolean if a field has been set.

### GetCreatedDate

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.

### GetModifiedById

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetModifiedDate

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetModifiedDate() time.Time`

GetModifiedDate returns the ModifiedDate field if non-nil, zero value otherwise.

### GetModifiedDateOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetModifiedDateOk() (*time.Time, bool)`

GetModifiedDateOk returns a tuple with the ModifiedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDate

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) SetModifiedDate(v time.Time)`

SetModifiedDate sets ModifiedDate field to given value.

### HasModifiedDate

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) HasModifiedDate() bool`

HasModifiedDate returns a boolean if a field has been set.

### GetTaxableDate

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetTaxableDate() time.Time`

GetTaxableDate returns the TaxableDate field if non-nil, zero value otherwise.

### GetTaxableDateOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetTaxableDateOk() (*time.Time, bool)`

GetTaxableDateOk returns a tuple with the TaxableDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxableDate

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) SetTaxableDate(v time.Time)`

SetTaxableDate sets TaxableDate field to given value.

### HasTaxableDate

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) HasTaxableDate() bool`

HasTaxableDate returns a boolean if a field has been set.

### GetAmount

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetAmount() float64`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetAmountOk() (*float64, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) SetAmount(v float64)`

SetAmount sets Amount field to given value.

### HasAmount

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) HasAmount() bool`

HasAmount returns a boolean if a field has been set.

### GetCurrencyAmount

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetCurrencyAmount() float64`

GetCurrencyAmount returns the CurrencyAmount field if non-nil, zero value otherwise.

### GetCurrencyAmountOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetCurrencyAmountOk() (*float64, bool)`

GetCurrencyAmountOk returns a tuple with the CurrencyAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyAmount

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) SetCurrencyAmount(v float64)`

SetCurrencyAmount sets CurrencyAmount field to given value.

### HasCurrencyAmount

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) HasCurrencyAmount() bool`

HasCurrencyAmount returns a boolean if a field has been set.

### GetPaid

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetPaid() bool`

GetPaid returns the Paid field if non-nil, zero value otherwise.

### GetPaidOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetPaidOk() (*bool, bool)`

GetPaidOk returns a tuple with the Paid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaid

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) SetPaid(v bool)`

SetPaid sets Paid field to given value.

### HasPaid

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) HasPaid() bool`

HasPaid returns a boolean if a field has been set.

### GetPaidDate

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetPaidDate() time.Time`

GetPaidDate returns the PaidDate field if non-nil, zero value otherwise.

### GetPaidDateOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetPaidDateOk() (*time.Time, bool)`

GetPaidDateOk returns a tuple with the PaidDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaidDate

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) SetPaidDate(v time.Time)`

SetPaidDate sets PaidDate field to given value.

### HasPaidDate

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) HasPaidDate() bool`

HasPaidDate returns a boolean if a field has been set.

### GetExpectedPayDate

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetExpectedPayDate() time.Time`

GetExpectedPayDate returns the ExpectedPayDate field if non-nil, zero value otherwise.

### GetExpectedPayDateOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetExpectedPayDateOk() (*time.Time, bool)`

GetExpectedPayDateOk returns a tuple with the ExpectedPayDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedPayDate

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) SetExpectedPayDate(v time.Time)`

SetExpectedPayDate sets ExpectedPayDate field to given value.

### HasExpectedPayDate

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) HasExpectedPayDate() bool`

HasExpectedPayDate returns a boolean if a field has been set.

### GetPaidPeriod

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetPaidPeriod() string`

GetPaidPeriod returns the PaidPeriod field if non-nil, zero value otherwise.

### GetPaidPeriodOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetPaidPeriodOk() (*string, bool)`

GetPaidPeriodOk returns a tuple with the PaidPeriod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaidPeriod

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) SetPaidPeriod(v string)`

SetPaidPeriod sets PaidPeriod field to given value.

### HasPaidPeriod

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) HasPaidPeriod() bool`

HasPaidPeriod returns a boolean if a field has been set.

### GetDiscount

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetDiscount() float64`

GetDiscount returns the Discount field if non-nil, zero value otherwise.

### GetDiscountOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetDiscountOk() (*float64, bool)`

GetDiscountOk returns a tuple with the Discount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscount

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) SetDiscount(v float64)`

SetDiscount sets Discount field to given value.

### HasDiscount

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) HasDiscount() bool`

HasDiscount returns a boolean if a field has been set.

### GetDiscountDueDate

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetDiscountDueDate() time.Time`

GetDiscountDueDate returns the DiscountDueDate field if non-nil, zero value otherwise.

### GetDiscountDueDateOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetDiscountDueDateOk() (*time.Time, bool)`

GetDiscountDueDateOk returns a tuple with the DiscountDueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscountDueDate

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) SetDiscountDueDate(v time.Time)`

SetDiscountDueDate sets DiscountDueDate field to given value.

### HasDiscountDueDate

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) HasDiscountDueDate() bool`

HasDiscountDueDate returns a boolean if a field has been set.

### GetBalance

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetBalance() float64`

GetBalance returns the Balance field if non-nil, zero value otherwise.

### GetBalanceOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetBalanceOk() (*float64, bool)`

GetBalanceOk returns a tuple with the Balance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBalance

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) SetBalance(v float64)`

SetBalance sets Balance field to given value.

### HasBalance

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) HasBalance() bool`

HasBalance returns a boolean if a field has been set.

### GetCurrencyBalance

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetCurrencyBalance() float64`

GetCurrencyBalance returns the CurrencyBalance field if non-nil, zero value otherwise.

### GetCurrencyBalanceOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetCurrencyBalanceOk() (*float64, bool)`

GetCurrencyBalanceOk returns a tuple with the CurrencyBalance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyBalance

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) SetCurrencyBalance(v float64)`

SetCurrencyBalance sets CurrencyBalance field to given value.

### HasCurrencyBalance

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) HasCurrencyBalance() bool`

HasCurrencyBalance returns a boolean if a field has been set.

### GetVoid

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetVoid() bool`

GetVoid returns the Void field if non-nil, zero value otherwise.

### GetVoidOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetVoidOk() (*bool, bool)`

GetVoidOk returns a tuple with the Void field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoid

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) SetVoid(v bool)`

SetVoid sets Void field to given value.

### HasVoid

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) HasVoid() bool`

HasVoid returns a boolean if a field has been set.

### GetConsolidatedLinkId

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetConsolidatedLinkId() string`

GetConsolidatedLinkId returns the ConsolidatedLinkId field if non-nil, zero value otherwise.

### GetConsolidatedLinkIdOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetConsolidatedLinkIdOk() (*string, bool)`

GetConsolidatedLinkIdOk returns a tuple with the ConsolidatedLinkId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsolidatedLinkId

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) SetConsolidatedLinkId(v string)`

SetConsolidatedLinkId sets ConsolidatedLinkId field to given value.

### HasConsolidatedLinkId

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) HasConsolidatedLinkId() bool`

HasConsolidatedLinkId returns a boolean if a field has been set.

### GetBooked

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetBooked() bool`

GetBooked returns the Booked field if non-nil, zero value otherwise.

### GetBookedOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetBookedOk() (*bool, bool)`

GetBookedOk returns a tuple with the Booked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBooked

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) SetBooked(v bool)`

SetBooked sets Booked field to given value.

### HasBooked

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) HasBooked() bool`

HasBooked returns a boolean if a field has been set.

### GetReferenceNo

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetReferenceNo() string`

GetReferenceNo returns the ReferenceNo field if non-nil, zero value otherwise.

### GetReferenceNoOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetReferenceNoOk() (*string, bool)`

GetReferenceNoOk returns a tuple with the ReferenceNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferenceNo

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) SetReferenceNo(v string)`

SetReferenceNo sets ReferenceNo field to given value.

### HasReferenceNo

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) HasReferenceNo() bool`

HasReferenceNo returns a boolean if a field has been set.

### GetShipperNo

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetShipperNo() string`

GetShipperNo returns the ShipperNo field if non-nil, zero value otherwise.

### GetShipperNoOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetShipperNoOk() (*string, bool)`

GetShipperNoOk returns a tuple with the ShipperNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipperNo

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) SetShipperNo(v string)`

SetShipperNo sets ShipperNo field to given value.

### HasShipperNo

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) HasShipperNo() bool`

HasShipperNo returns a boolean if a field has been set.

### GetPoNumber

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetPoNumber() string`

GetPoNumber returns the PoNumber field if non-nil, zero value otherwise.

### GetPoNumberOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetPoNumberOk() (*string, bool)`

GetPoNumberOk returns a tuple with the PoNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoNumber

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) SetPoNumber(v string)`

SetPoNumber sets PoNumber field to given value.

### HasPoNumber

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) HasPoNumber() bool`

HasPoNumber returns a boolean if a field has been set.

### GetPoId

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetPoId() string`

GetPoId returns the PoId field if non-nil, zero value otherwise.

### GetPoIdOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetPoIdOk() (*string, bool)`

GetPoIdOk returns a tuple with the PoId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoId

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) SetPoId(v string)`

SetPoId sets PoId field to given value.

### HasPoId

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) HasPoId() bool`

HasPoId returns a boolean if a field has been set.

### GetLines

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetLines() []LinesItem5`

GetLines returns the Lines field if non-nil, zero value otherwise.

### GetLinesOk

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) GetLinesOk() (*[]LinesItem5, bool)`

GetLinesOk returns a tuple with the Lines field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLines

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) SetLines(v []LinesItem5)`

SetLines sets Lines field to given value.

### HasLines

`func (o *AccountsReceivableInvoicesApiCreateARInvoice201Response) HasLines() bool`

HasLines returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


