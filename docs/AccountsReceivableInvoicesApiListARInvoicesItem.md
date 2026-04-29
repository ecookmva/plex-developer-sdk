# AccountsReceivableInvoicesApiListARInvoicesItem

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

### NewAccountsReceivableInvoicesApiListARInvoicesItem

`func NewAccountsReceivableInvoicesApiListARInvoicesItem() *AccountsReceivableInvoicesApiListARInvoicesItem`

NewAccountsReceivableInvoicesApiListARInvoicesItem instantiates a new AccountsReceivableInvoicesApiListARInvoicesItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccountsReceivableInvoicesApiListARInvoicesItemWithDefaults

`func NewAccountsReceivableInvoicesApiListARInvoicesItemWithDefaults() *AccountsReceivableInvoicesApiListARInvoicesItem`

NewAccountsReceivableInvoicesApiListARInvoicesItemWithDefaults instantiates a new AccountsReceivableInvoicesApiListARInvoicesItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) HasId() bool`

HasId returns a boolean if a field has been set.

### GetInvoiceNumber

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetInvoiceNumber() string`

GetInvoiceNumber returns the InvoiceNumber field if non-nil, zero value otherwise.

### GetInvoiceNumberOk

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetInvoiceNumberOk() (*string, bool)`

GetInvoiceNumberOk returns a tuple with the InvoiceNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceNumber

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) SetInvoiceNumber(v string)`

SetInvoiceNumber sets InvoiceNumber field to given value.

### HasInvoiceNumber

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) HasInvoiceNumber() bool`

HasInvoiceNumber returns a boolean if a field has been set.

### GetCreditMemo

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetCreditMemo() int32`

GetCreditMemo returns the CreditMemo field if non-nil, zero value otherwise.

### GetCreditMemoOk

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetCreditMemoOk() (*int32, bool)`

GetCreditMemoOk returns a tuple with the CreditMemo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditMemo

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) SetCreditMemo(v int32)`

SetCreditMemo sets CreditMemo field to given value.

### HasCreditMemo

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) HasCreditMemo() bool`

HasCreditMemo returns a boolean if a field has been set.

### GetCustomerId

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### GetCustomerCode

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetCustomerCode() string`

GetCustomerCode returns the CustomerCode field if non-nil, zero value otherwise.

### GetCustomerCodeOk

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetCustomerCodeOk() (*string, bool)`

GetCustomerCodeOk returns a tuple with the CustomerCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerCode

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) SetCustomerCode(v string)`

SetCustomerCode sets CustomerCode field to given value.

### HasCustomerCode

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) HasCustomerCode() bool`

HasCustomerCode returns a boolean if a field has been set.

### GetCustomerBillToId

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetCustomerBillToId() string`

GetCustomerBillToId returns the CustomerBillToId field if non-nil, zero value otherwise.

### GetCustomerBillToIdOk

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetCustomerBillToIdOk() (*string, bool)`

GetCustomerBillToIdOk returns a tuple with the CustomerBillToId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerBillToId

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) SetCustomerBillToId(v string)`

SetCustomerBillToId sets CustomerBillToId field to given value.

### HasCustomerBillToId

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) HasCustomerBillToId() bool`

HasCustomerBillToId returns a boolean if a field has been set.

### GetCustomerBillToCode

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetCustomerBillToCode() string`

GetCustomerBillToCode returns the CustomerBillToCode field if non-nil, zero value otherwise.

### GetCustomerBillToCodeOk

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetCustomerBillToCodeOk() (*string, bool)`

GetCustomerBillToCodeOk returns a tuple with the CustomerBillToCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerBillToCode

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) SetCustomerBillToCode(v string)`

SetCustomerBillToCode sets CustomerBillToCode field to given value.

### HasCustomerBillToCode

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) HasCustomerBillToCode() bool`

HasCustomerBillToCode returns a boolean if a field has been set.

### GetCustomerShipToId

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetCustomerShipToId() string`

GetCustomerShipToId returns the CustomerShipToId field if non-nil, zero value otherwise.

### GetCustomerShipToIdOk

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetCustomerShipToIdOk() (*string, bool)`

GetCustomerShipToIdOk returns a tuple with the CustomerShipToId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerShipToId

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) SetCustomerShipToId(v string)`

SetCustomerShipToId sets CustomerShipToId field to given value.

### HasCustomerShipToId

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) HasCustomerShipToId() bool`

HasCustomerShipToId returns a boolean if a field has been set.

### GetCustomerShipToCode

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetCustomerShipToCode() string`

GetCustomerShipToCode returns the CustomerShipToCode field if non-nil, zero value otherwise.

### GetCustomerShipToCodeOk

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetCustomerShipToCodeOk() (*string, bool)`

GetCustomerShipToCodeOk returns a tuple with the CustomerShipToCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerShipToCode

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) SetCustomerShipToCode(v string)`

SetCustomerShipToCode sets CustomerShipToCode field to given value.

### HasCustomerShipToCode

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) HasCustomerShipToCode() bool`

HasCustomerShipToCode returns a boolean if a field has been set.

### GetCustomerOrderNos

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetCustomerOrderNos() string`

GetCustomerOrderNos returns the CustomerOrderNos field if non-nil, zero value otherwise.

### GetCustomerOrderNosOk

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetCustomerOrderNosOk() (*string, bool)`

GetCustomerOrderNosOk returns a tuple with the CustomerOrderNos field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerOrderNos

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) SetCustomerOrderNos(v string)`

SetCustomerOrderNos sets CustomerOrderNos field to given value.

### HasCustomerOrderNos

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) HasCustomerOrderNos() bool`

HasCustomerOrderNos returns a boolean if a field has been set.

### GetCustomerPONo

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetCustomerPONo() string`

GetCustomerPONo returns the CustomerPONo field if non-nil, zero value otherwise.

### GetCustomerPONoOk

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetCustomerPONoOk() (*string, bool)`

GetCustomerPONoOk returns a tuple with the CustomerPONo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerPONo

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) SetCustomerPONo(v string)`

SetCustomerPONo sets CustomerPONo field to given value.

### HasCustomerPONo

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) HasCustomerPONo() bool`

HasCustomerPONo returns a boolean if a field has been set.

### GetBuildingCode

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetBuildingCode() string`

GetBuildingCode returns the BuildingCode field if non-nil, zero value otherwise.

### GetBuildingCodeOk

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetBuildingCodeOk() (*string, bool)`

GetBuildingCodeOk returns a tuple with the BuildingCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildingCode

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) SetBuildingCode(v string)`

SetBuildingCode sets BuildingCode field to given value.

### HasBuildingCode

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) HasBuildingCode() bool`

HasBuildingCode returns a boolean if a field has been set.

### GetPeriodDisplay

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetPeriodDisplay() string`

GetPeriodDisplay returns the PeriodDisplay field if non-nil, zero value otherwise.

### GetPeriodDisplayOk

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetPeriodDisplayOk() (*string, bool)`

GetPeriodDisplayOk returns a tuple with the PeriodDisplay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriodDisplay

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) SetPeriodDisplay(v string)`

SetPeriodDisplay sets PeriodDisplay field to given value.

### HasPeriodDisplay

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) HasPeriodDisplay() bool`

HasPeriodDisplay returns a boolean if a field has been set.

### GetTransactionDate

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetTransactionDate() time.Time`

GetTransactionDate returns the TransactionDate field if non-nil, zero value otherwise.

### GetTransactionDateOk

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetTransactionDateOk() (*time.Time, bool)`

GetTransactionDateOk returns a tuple with the TransactionDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransactionDate

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) SetTransactionDate(v time.Time)`

SetTransactionDate sets TransactionDate field to given value.

### HasTransactionDate

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) HasTransactionDate() bool`

HasTransactionDate returns a boolean if a field has been set.

### GetCurrencyCode

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetCurrencyCode() string`

GetCurrencyCode returns the CurrencyCode field if non-nil, zero value otherwise.

### GetCurrencyCodeOk

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetCurrencyCodeOk() (*string, bool)`

GetCurrencyCodeOk returns a tuple with the CurrencyCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyCode

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) SetCurrencyCode(v string)`

SetCurrencyCode sets CurrencyCode field to given value.

### HasCurrencyCode

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) HasCurrencyCode() bool`

HasCurrencyCode returns a boolean if a field has been set.

### GetExchangeRate

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetExchangeRate() float64`

GetExchangeRate returns the ExchangeRate field if non-nil, zero value otherwise.

### GetExchangeRateOk

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetExchangeRateOk() (*float64, bool)`

GetExchangeRateOk returns a tuple with the ExchangeRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExchangeRate

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) SetExchangeRate(v float64)`

SetExchangeRate sets ExchangeRate field to given value.

### HasExchangeRate

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) HasExchangeRate() bool`

HasExchangeRate returns a boolean if a field has been set.

### GetTerms

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetTerms() string`

GetTerms returns the Terms field if non-nil, zero value otherwise.

### GetTermsOk

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetTermsOk() (*string, bool)`

GetTermsOk returns a tuple with the Terms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTerms

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) SetTerms(v string)`

SetTerms sets Terms field to given value.

### HasTerms

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) HasTerms() bool`

HasTerms returns a boolean if a field has been set.

### GetDueDate

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetDueDate() time.Time`

GetDueDate returns the DueDate field if non-nil, zero value otherwise.

### GetDueDateOk

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetDueDateOk() (*time.Time, bool)`

GetDueDateOk returns a tuple with the DueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueDate

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) SetDueDate(v time.Time)`

SetDueDate sets DueDate field to given value.

### HasDueDate

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) HasDueDate() bool`

HasDueDate returns a boolean if a field has been set.

### GetInvoiceNote

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetInvoiceNote() string`

GetInvoiceNote returns the InvoiceNote field if non-nil, zero value otherwise.

### GetInvoiceNoteOk

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetInvoiceNoteOk() (*string, bool)`

GetInvoiceNoteOk returns a tuple with the InvoiceNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceNote

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) SetInvoiceNote(v string)`

SetInvoiceNote sets InvoiceNote field to given value.

### HasInvoiceNote

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) HasInvoiceNote() bool`

HasInvoiceNote returns a boolean if a field has been set.

### GetInternalNote

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetInternalNote() string`

GetInternalNote returns the InternalNote field if non-nil, zero value otherwise.

### GetInternalNoteOk

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetInternalNoteOk() (*string, bool)`

GetInternalNoteOk returns a tuple with the InternalNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInternalNote

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) SetInternalNote(v string)`

SetInternalNote sets InternalNote field to given value.

### HasInternalNote

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) HasInternalNote() bool`

HasInternalNote returns a boolean if a field has been set.

### GetVoucherNumber

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetVoucherNumber() string`

GetVoucherNumber returns the VoucherNumber field if non-nil, zero value otherwise.

### GetVoucherNumberOk

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetVoucherNumberOk() (*string, bool)`

GetVoucherNumberOk returns a tuple with the VoucherNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoucherNumber

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) SetVoucherNumber(v string)`

SetVoucherNumber sets VoucherNumber field to given value.

### HasVoucherNumber

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) HasVoucherNumber() bool`

HasVoucherNumber returns a boolean if a field has been set.

### GetStatus

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetGovernmentIssuedNumber

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetGovernmentIssuedNumber() string`

GetGovernmentIssuedNumber returns the GovernmentIssuedNumber field if non-nil, zero value otherwise.

### GetGovernmentIssuedNumberOk

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetGovernmentIssuedNumberOk() (*string, bool)`

GetGovernmentIssuedNumberOk returns a tuple with the GovernmentIssuedNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGovernmentIssuedNumber

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) SetGovernmentIssuedNumber(v string)`

SetGovernmentIssuedNumber sets GovernmentIssuedNumber field to given value.

### HasGovernmentIssuedNumber

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) HasGovernmentIssuedNumber() bool`

HasGovernmentIssuedNumber returns a boolean if a field has been set.

### GetType

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) HasType() bool`

HasType returns a boolean if a field has been set.

### GetCreatedById

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetCreatedById() string`

GetCreatedById returns the CreatedById field if non-nil, zero value otherwise.

### GetCreatedByIdOk

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetCreatedByIdOk() (*string, bool)`

GetCreatedByIdOk returns a tuple with the CreatedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedById

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) SetCreatedById(v string)`

SetCreatedById sets CreatedById field to given value.

### HasCreatedById

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) HasCreatedById() bool`

HasCreatedById returns a boolean if a field has been set.

### GetCreatedDate

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.

### GetModifiedById

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetModifiedDate

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetModifiedDate() time.Time`

GetModifiedDate returns the ModifiedDate field if non-nil, zero value otherwise.

### GetModifiedDateOk

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetModifiedDateOk() (*time.Time, bool)`

GetModifiedDateOk returns a tuple with the ModifiedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDate

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) SetModifiedDate(v time.Time)`

SetModifiedDate sets ModifiedDate field to given value.

### HasModifiedDate

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) HasModifiedDate() bool`

HasModifiedDate returns a boolean if a field has been set.

### GetTaxableDate

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetTaxableDate() time.Time`

GetTaxableDate returns the TaxableDate field if non-nil, zero value otherwise.

### GetTaxableDateOk

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetTaxableDateOk() (*time.Time, bool)`

GetTaxableDateOk returns a tuple with the TaxableDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxableDate

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) SetTaxableDate(v time.Time)`

SetTaxableDate sets TaxableDate field to given value.

### HasTaxableDate

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) HasTaxableDate() bool`

HasTaxableDate returns a boolean if a field has been set.

### GetAmount

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetAmount() float64`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetAmountOk() (*float64, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) SetAmount(v float64)`

SetAmount sets Amount field to given value.

### HasAmount

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) HasAmount() bool`

HasAmount returns a boolean if a field has been set.

### GetCurrencyAmount

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetCurrencyAmount() float64`

GetCurrencyAmount returns the CurrencyAmount field if non-nil, zero value otherwise.

### GetCurrencyAmountOk

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetCurrencyAmountOk() (*float64, bool)`

GetCurrencyAmountOk returns a tuple with the CurrencyAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyAmount

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) SetCurrencyAmount(v float64)`

SetCurrencyAmount sets CurrencyAmount field to given value.

### HasCurrencyAmount

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) HasCurrencyAmount() bool`

HasCurrencyAmount returns a boolean if a field has been set.

### GetPaid

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetPaid() bool`

GetPaid returns the Paid field if non-nil, zero value otherwise.

### GetPaidOk

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetPaidOk() (*bool, bool)`

GetPaidOk returns a tuple with the Paid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaid

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) SetPaid(v bool)`

SetPaid sets Paid field to given value.

### HasPaid

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) HasPaid() bool`

HasPaid returns a boolean if a field has been set.

### GetPaidDate

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetPaidDate() time.Time`

GetPaidDate returns the PaidDate field if non-nil, zero value otherwise.

### GetPaidDateOk

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetPaidDateOk() (*time.Time, bool)`

GetPaidDateOk returns a tuple with the PaidDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaidDate

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) SetPaidDate(v time.Time)`

SetPaidDate sets PaidDate field to given value.

### HasPaidDate

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) HasPaidDate() bool`

HasPaidDate returns a boolean if a field has been set.

### GetExpectedPayDate

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetExpectedPayDate() time.Time`

GetExpectedPayDate returns the ExpectedPayDate field if non-nil, zero value otherwise.

### GetExpectedPayDateOk

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetExpectedPayDateOk() (*time.Time, bool)`

GetExpectedPayDateOk returns a tuple with the ExpectedPayDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedPayDate

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) SetExpectedPayDate(v time.Time)`

SetExpectedPayDate sets ExpectedPayDate field to given value.

### HasExpectedPayDate

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) HasExpectedPayDate() bool`

HasExpectedPayDate returns a boolean if a field has been set.

### GetPaidPeriod

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetPaidPeriod() string`

GetPaidPeriod returns the PaidPeriod field if non-nil, zero value otherwise.

### GetPaidPeriodOk

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetPaidPeriodOk() (*string, bool)`

GetPaidPeriodOk returns a tuple with the PaidPeriod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaidPeriod

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) SetPaidPeriod(v string)`

SetPaidPeriod sets PaidPeriod field to given value.

### HasPaidPeriod

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) HasPaidPeriod() bool`

HasPaidPeriod returns a boolean if a field has been set.

### GetDiscount

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetDiscount() float64`

GetDiscount returns the Discount field if non-nil, zero value otherwise.

### GetDiscountOk

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetDiscountOk() (*float64, bool)`

GetDiscountOk returns a tuple with the Discount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscount

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) SetDiscount(v float64)`

SetDiscount sets Discount field to given value.

### HasDiscount

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) HasDiscount() bool`

HasDiscount returns a boolean if a field has been set.

### GetDiscountDueDate

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetDiscountDueDate() time.Time`

GetDiscountDueDate returns the DiscountDueDate field if non-nil, zero value otherwise.

### GetDiscountDueDateOk

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetDiscountDueDateOk() (*time.Time, bool)`

GetDiscountDueDateOk returns a tuple with the DiscountDueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscountDueDate

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) SetDiscountDueDate(v time.Time)`

SetDiscountDueDate sets DiscountDueDate field to given value.

### HasDiscountDueDate

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) HasDiscountDueDate() bool`

HasDiscountDueDate returns a boolean if a field has been set.

### GetBalance

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetBalance() float64`

GetBalance returns the Balance field if non-nil, zero value otherwise.

### GetBalanceOk

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetBalanceOk() (*float64, bool)`

GetBalanceOk returns a tuple with the Balance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBalance

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) SetBalance(v float64)`

SetBalance sets Balance field to given value.

### HasBalance

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) HasBalance() bool`

HasBalance returns a boolean if a field has been set.

### GetCurrencyBalance

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetCurrencyBalance() float64`

GetCurrencyBalance returns the CurrencyBalance field if non-nil, zero value otherwise.

### GetCurrencyBalanceOk

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetCurrencyBalanceOk() (*float64, bool)`

GetCurrencyBalanceOk returns a tuple with the CurrencyBalance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyBalance

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) SetCurrencyBalance(v float64)`

SetCurrencyBalance sets CurrencyBalance field to given value.

### HasCurrencyBalance

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) HasCurrencyBalance() bool`

HasCurrencyBalance returns a boolean if a field has been set.

### GetVoid

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetVoid() bool`

GetVoid returns the Void field if non-nil, zero value otherwise.

### GetVoidOk

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetVoidOk() (*bool, bool)`

GetVoidOk returns a tuple with the Void field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoid

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) SetVoid(v bool)`

SetVoid sets Void field to given value.

### HasVoid

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) HasVoid() bool`

HasVoid returns a boolean if a field has been set.

### GetConsolidatedLinkId

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetConsolidatedLinkId() string`

GetConsolidatedLinkId returns the ConsolidatedLinkId field if non-nil, zero value otherwise.

### GetConsolidatedLinkIdOk

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetConsolidatedLinkIdOk() (*string, bool)`

GetConsolidatedLinkIdOk returns a tuple with the ConsolidatedLinkId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsolidatedLinkId

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) SetConsolidatedLinkId(v string)`

SetConsolidatedLinkId sets ConsolidatedLinkId field to given value.

### HasConsolidatedLinkId

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) HasConsolidatedLinkId() bool`

HasConsolidatedLinkId returns a boolean if a field has been set.

### GetBooked

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetBooked() bool`

GetBooked returns the Booked field if non-nil, zero value otherwise.

### GetBookedOk

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetBookedOk() (*bool, bool)`

GetBookedOk returns a tuple with the Booked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBooked

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) SetBooked(v bool)`

SetBooked sets Booked field to given value.

### HasBooked

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) HasBooked() bool`

HasBooked returns a boolean if a field has been set.

### GetReferenceNo

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetReferenceNo() string`

GetReferenceNo returns the ReferenceNo field if non-nil, zero value otherwise.

### GetReferenceNoOk

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetReferenceNoOk() (*string, bool)`

GetReferenceNoOk returns a tuple with the ReferenceNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferenceNo

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) SetReferenceNo(v string)`

SetReferenceNo sets ReferenceNo field to given value.

### HasReferenceNo

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) HasReferenceNo() bool`

HasReferenceNo returns a boolean if a field has been set.

### GetShipperNo

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetShipperNo() string`

GetShipperNo returns the ShipperNo field if non-nil, zero value otherwise.

### GetShipperNoOk

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetShipperNoOk() (*string, bool)`

GetShipperNoOk returns a tuple with the ShipperNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipperNo

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) SetShipperNo(v string)`

SetShipperNo sets ShipperNo field to given value.

### HasShipperNo

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) HasShipperNo() bool`

HasShipperNo returns a boolean if a field has been set.

### GetPoNumber

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetPoNumber() string`

GetPoNumber returns the PoNumber field if non-nil, zero value otherwise.

### GetPoNumberOk

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetPoNumberOk() (*string, bool)`

GetPoNumberOk returns a tuple with the PoNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoNumber

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) SetPoNumber(v string)`

SetPoNumber sets PoNumber field to given value.

### HasPoNumber

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) HasPoNumber() bool`

HasPoNumber returns a boolean if a field has been set.

### GetPoId

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetPoId() string`

GetPoId returns the PoId field if non-nil, zero value otherwise.

### GetPoIdOk

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetPoIdOk() (*string, bool)`

GetPoIdOk returns a tuple with the PoId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoId

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) SetPoId(v string)`

SetPoId sets PoId field to given value.

### HasPoId

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) HasPoId() bool`

HasPoId returns a boolean if a field has been set.

### GetLines

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetLines() []LinesItem5`

GetLines returns the Lines field if non-nil, zero value otherwise.

### GetLinesOk

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) GetLinesOk() (*[]LinesItem5, bool)`

GetLinesOk returns a tuple with the Lines field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLines

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) SetLines(v []LinesItem5)`

SetLines sets Lines field to given value.

### HasLines

`func (o *AccountsReceivableInvoicesApiListARInvoicesItem) HasLines() bool`

HasLines returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


