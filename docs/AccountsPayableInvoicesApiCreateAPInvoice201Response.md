# AccountsPayableInvoicesApiCreateAPInvoice201Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | The AP invoice ID. | [optional] 
**InvoiceNumber** | Pointer to **string** | The AP invoice number. | [optional] 
**SupplierId** | Pointer to **string** | The AP supplier ID. | [optional] 
**SupplierCode** | Pointer to **string** | The AP supplier code. | [optional] 
**SupplierAddressId** | Pointer to **string** | The AP supplier address ID. | [optional] 
**SupplierAddressCode** | Pointer to **string** | The AP supplier address code. | [optional] 
**PeriodDisplay** | Pointer to **string** | The period in which an AP invoice was recorded. | [optional] 
**TransactionDate** | Pointer to **time.Time** | The date an AP transaction was recorded. | [optional] 
**BuildingCode** | Pointer to **string** | The code used to look up the building resource. | [optional] 
**CurrencyCode** | Pointer to **string** | The AP invoice currency code. | [optional] 
**ExchangeRate** | Pointer to **float64** | The AP invoice exchange rate. | [optional] 
**Department** | Pointer to **int32** | The AP invoice department number. | [optional] 
**Terms** | Pointer to **string** | The AP invoice terms. | [optional] 
**DueDate** | Pointer to **time.Time** | The AP invoice due date. | [optional] 
**Discount** | Pointer to **float64** | The discount applicable to an AP invoice. | [optional] 
**InternalNote** | Pointer to **string** | An internal note added to an AP invoice. | [optional] 
**VoucherNumber** | Pointer to **string** | The AP invoice voucher number. | [optional] 
**Status** | Pointer to **string** | The AP invoice status. | [optional] 
**GovernmentIssuedNumber** | Pointer to **string** | The AP invoice government issued number. | [optional] 
**Type** | Pointer to **string** | The AP invoice type. | [optional] 
**CreatedById** | Pointer to **string** | The ID of the user who created the record. | [optional] 
**CreatedDate** | Pointer to **time.Time** | The date an AP invoice was created. | [optional] 
**ModifiedById** | Pointer to **string** | The ID of the user who last modified the record. | [optional] 
**ModifiedDate** | Pointer to **time.Time** | The date an AP invoice was modified. | [optional] 
**Booked** | Pointer to **bool** | Specify that an AP invoice is booked. | [optional] 
**TaxableDate** | Pointer to **time.Time** | The date the AP invoice tax was calculated. | [optional] 
**Amount** | Pointer to **float64** | The AP invoice amount. | [optional] 
**Paid** | Pointer to **bool** | Specify that an AP invoice has been paid. | [optional] 
**PaidDate** | Pointer to **time.Time** | The date an AP invoice was paid. | [optional] 
**PaidPeriod** | Pointer to **string** | The period in which an AP invoice was paid. | [optional] 
**TotalControlAmount** | Pointer to **float64** | The AP invoice positive pay total payment amount. | [optional] 
**ExpectedPayDate** | Pointer to **time.Time** | The date an AP invoice payment is expected. | [optional] 
**TaxId** | Pointer to **string** | The AP invoice tax ID from the supplier record. | [optional] 
**ForeignCurrencyAmount** | Pointer to **float64** | The AP invoice foreign currency amount. | [optional] 
**DiscountDueDate** | Pointer to **time.Time** | The date an AP invoice must be paid to receive a defined discount. | [optional] 
**ExchangeRateDate** | Pointer to **time.Time** | The date an AP invoice exchange rate was calculated. | [optional] 
**Balance** | Pointer to **float64** | The AP invoice balance. | [optional] 
**DiscountableAmount** | Pointer to **float64** | The AP invoice discountable amount. | [optional] 
**DebitMemo** | Pointer to **int32** | Specify an AP invoice debit memo. | [optional] 
**Intercompany** | Pointer to **int32** | The AP invoice intercompany tax. | [optional] 
**CheckNote** | Pointer to **string** | A note added to an AP invoice check. | [optional] 
**ShipperNo** | Pointer to **string** | The AP invoice shipper number. | [optional] 
**ShipperId** | Pointer to **string** | The AP invoice shipper ID. | [optional] 
**PoNumber** | Pointer to **string** | The AP invoice purchase order number. | [optional] 
**PoId** | Pointer to **string** | The AP invoice purchase order ID. | [optional] 
**ExternalReferenceCode** | Pointer to **string** | The AP invoice external reference code. | [optional] 
**ForeignCurrencyBalance** | Pointer to **float64** | The AP invoice foreign balance. | [optional] 
**Lines** | Pointer to [**[]LinesItem**](LinesItem.md) | A list of AP invoice lines. | [optional] 

## Methods

### NewAccountsPayableInvoicesApiCreateAPInvoice201Response

`func NewAccountsPayableInvoicesApiCreateAPInvoice201Response() *AccountsPayableInvoicesApiCreateAPInvoice201Response`

NewAccountsPayableInvoicesApiCreateAPInvoice201Response instantiates a new AccountsPayableInvoicesApiCreateAPInvoice201Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccountsPayableInvoicesApiCreateAPInvoice201ResponseWithDefaults

`func NewAccountsPayableInvoicesApiCreateAPInvoice201ResponseWithDefaults() *AccountsPayableInvoicesApiCreateAPInvoice201Response`

NewAccountsPayableInvoicesApiCreateAPInvoice201ResponseWithDefaults instantiates a new AccountsPayableInvoicesApiCreateAPInvoice201Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) HasId() bool`

HasId returns a boolean if a field has been set.

### GetInvoiceNumber

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetInvoiceNumber() string`

GetInvoiceNumber returns the InvoiceNumber field if non-nil, zero value otherwise.

### GetInvoiceNumberOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetInvoiceNumberOk() (*string, bool)`

GetInvoiceNumberOk returns a tuple with the InvoiceNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceNumber

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) SetInvoiceNumber(v string)`

SetInvoiceNumber sets InvoiceNumber field to given value.

### HasInvoiceNumber

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) HasInvoiceNumber() bool`

HasInvoiceNumber returns a boolean if a field has been set.

### GetSupplierId

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetSupplierId() string`

GetSupplierId returns the SupplierId field if non-nil, zero value otherwise.

### GetSupplierIdOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetSupplierIdOk() (*string, bool)`

GetSupplierIdOk returns a tuple with the SupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierId

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) SetSupplierId(v string)`

SetSupplierId sets SupplierId field to given value.

### HasSupplierId

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) HasSupplierId() bool`

HasSupplierId returns a boolean if a field has been set.

### GetSupplierCode

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetSupplierCode() string`

GetSupplierCode returns the SupplierCode field if non-nil, zero value otherwise.

### GetSupplierCodeOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetSupplierCodeOk() (*string, bool)`

GetSupplierCodeOk returns a tuple with the SupplierCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierCode

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) SetSupplierCode(v string)`

SetSupplierCode sets SupplierCode field to given value.

### HasSupplierCode

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) HasSupplierCode() bool`

HasSupplierCode returns a boolean if a field has been set.

### GetSupplierAddressId

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetSupplierAddressId() string`

GetSupplierAddressId returns the SupplierAddressId field if non-nil, zero value otherwise.

### GetSupplierAddressIdOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetSupplierAddressIdOk() (*string, bool)`

GetSupplierAddressIdOk returns a tuple with the SupplierAddressId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierAddressId

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) SetSupplierAddressId(v string)`

SetSupplierAddressId sets SupplierAddressId field to given value.

### HasSupplierAddressId

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) HasSupplierAddressId() bool`

HasSupplierAddressId returns a boolean if a field has been set.

### GetSupplierAddressCode

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetSupplierAddressCode() string`

GetSupplierAddressCode returns the SupplierAddressCode field if non-nil, zero value otherwise.

### GetSupplierAddressCodeOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetSupplierAddressCodeOk() (*string, bool)`

GetSupplierAddressCodeOk returns a tuple with the SupplierAddressCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierAddressCode

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) SetSupplierAddressCode(v string)`

SetSupplierAddressCode sets SupplierAddressCode field to given value.

### HasSupplierAddressCode

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) HasSupplierAddressCode() bool`

HasSupplierAddressCode returns a boolean if a field has been set.

### GetPeriodDisplay

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetPeriodDisplay() string`

GetPeriodDisplay returns the PeriodDisplay field if non-nil, zero value otherwise.

### GetPeriodDisplayOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetPeriodDisplayOk() (*string, bool)`

GetPeriodDisplayOk returns a tuple with the PeriodDisplay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriodDisplay

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) SetPeriodDisplay(v string)`

SetPeriodDisplay sets PeriodDisplay field to given value.

### HasPeriodDisplay

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) HasPeriodDisplay() bool`

HasPeriodDisplay returns a boolean if a field has been set.

### GetTransactionDate

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetTransactionDate() time.Time`

GetTransactionDate returns the TransactionDate field if non-nil, zero value otherwise.

### GetTransactionDateOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetTransactionDateOk() (*time.Time, bool)`

GetTransactionDateOk returns a tuple with the TransactionDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransactionDate

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) SetTransactionDate(v time.Time)`

SetTransactionDate sets TransactionDate field to given value.

### HasTransactionDate

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) HasTransactionDate() bool`

HasTransactionDate returns a boolean if a field has been set.

### GetBuildingCode

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetBuildingCode() string`

GetBuildingCode returns the BuildingCode field if non-nil, zero value otherwise.

### GetBuildingCodeOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetBuildingCodeOk() (*string, bool)`

GetBuildingCodeOk returns a tuple with the BuildingCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildingCode

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) SetBuildingCode(v string)`

SetBuildingCode sets BuildingCode field to given value.

### HasBuildingCode

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) HasBuildingCode() bool`

HasBuildingCode returns a boolean if a field has been set.

### GetCurrencyCode

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetCurrencyCode() string`

GetCurrencyCode returns the CurrencyCode field if non-nil, zero value otherwise.

### GetCurrencyCodeOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetCurrencyCodeOk() (*string, bool)`

GetCurrencyCodeOk returns a tuple with the CurrencyCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyCode

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) SetCurrencyCode(v string)`

SetCurrencyCode sets CurrencyCode field to given value.

### HasCurrencyCode

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) HasCurrencyCode() bool`

HasCurrencyCode returns a boolean if a field has been set.

### GetExchangeRate

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetExchangeRate() float64`

GetExchangeRate returns the ExchangeRate field if non-nil, zero value otherwise.

### GetExchangeRateOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetExchangeRateOk() (*float64, bool)`

GetExchangeRateOk returns a tuple with the ExchangeRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExchangeRate

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) SetExchangeRate(v float64)`

SetExchangeRate sets ExchangeRate field to given value.

### HasExchangeRate

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) HasExchangeRate() bool`

HasExchangeRate returns a boolean if a field has been set.

### GetDepartment

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetDepartment() int32`

GetDepartment returns the Department field if non-nil, zero value otherwise.

### GetDepartmentOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetDepartmentOk() (*int32, bool)`

GetDepartmentOk returns a tuple with the Department field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDepartment

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) SetDepartment(v int32)`

SetDepartment sets Department field to given value.

### HasDepartment

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) HasDepartment() bool`

HasDepartment returns a boolean if a field has been set.

### GetTerms

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetTerms() string`

GetTerms returns the Terms field if non-nil, zero value otherwise.

### GetTermsOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetTermsOk() (*string, bool)`

GetTermsOk returns a tuple with the Terms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTerms

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) SetTerms(v string)`

SetTerms sets Terms field to given value.

### HasTerms

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) HasTerms() bool`

HasTerms returns a boolean if a field has been set.

### GetDueDate

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetDueDate() time.Time`

GetDueDate returns the DueDate field if non-nil, zero value otherwise.

### GetDueDateOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetDueDateOk() (*time.Time, bool)`

GetDueDateOk returns a tuple with the DueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueDate

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) SetDueDate(v time.Time)`

SetDueDate sets DueDate field to given value.

### HasDueDate

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) HasDueDate() bool`

HasDueDate returns a boolean if a field has been set.

### GetDiscount

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetDiscount() float64`

GetDiscount returns the Discount field if non-nil, zero value otherwise.

### GetDiscountOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetDiscountOk() (*float64, bool)`

GetDiscountOk returns a tuple with the Discount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscount

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) SetDiscount(v float64)`

SetDiscount sets Discount field to given value.

### HasDiscount

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) HasDiscount() bool`

HasDiscount returns a boolean if a field has been set.

### GetInternalNote

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetInternalNote() string`

GetInternalNote returns the InternalNote field if non-nil, zero value otherwise.

### GetInternalNoteOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetInternalNoteOk() (*string, bool)`

GetInternalNoteOk returns a tuple with the InternalNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInternalNote

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) SetInternalNote(v string)`

SetInternalNote sets InternalNote field to given value.

### HasInternalNote

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) HasInternalNote() bool`

HasInternalNote returns a boolean if a field has been set.

### GetVoucherNumber

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetVoucherNumber() string`

GetVoucherNumber returns the VoucherNumber field if non-nil, zero value otherwise.

### GetVoucherNumberOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetVoucherNumberOk() (*string, bool)`

GetVoucherNumberOk returns a tuple with the VoucherNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoucherNumber

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) SetVoucherNumber(v string)`

SetVoucherNumber sets VoucherNumber field to given value.

### HasVoucherNumber

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) HasVoucherNumber() bool`

HasVoucherNumber returns a boolean if a field has been set.

### GetStatus

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetGovernmentIssuedNumber

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetGovernmentIssuedNumber() string`

GetGovernmentIssuedNumber returns the GovernmentIssuedNumber field if non-nil, zero value otherwise.

### GetGovernmentIssuedNumberOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetGovernmentIssuedNumberOk() (*string, bool)`

GetGovernmentIssuedNumberOk returns a tuple with the GovernmentIssuedNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGovernmentIssuedNumber

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) SetGovernmentIssuedNumber(v string)`

SetGovernmentIssuedNumber sets GovernmentIssuedNumber field to given value.

### HasGovernmentIssuedNumber

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) HasGovernmentIssuedNumber() bool`

HasGovernmentIssuedNumber returns a boolean if a field has been set.

### GetType

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) HasType() bool`

HasType returns a boolean if a field has been set.

### GetCreatedById

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetCreatedById() string`

GetCreatedById returns the CreatedById field if non-nil, zero value otherwise.

### GetCreatedByIdOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetCreatedByIdOk() (*string, bool)`

GetCreatedByIdOk returns a tuple with the CreatedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedById

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) SetCreatedById(v string)`

SetCreatedById sets CreatedById field to given value.

### HasCreatedById

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) HasCreatedById() bool`

HasCreatedById returns a boolean if a field has been set.

### GetCreatedDate

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.

### GetModifiedById

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetModifiedDate

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetModifiedDate() time.Time`

GetModifiedDate returns the ModifiedDate field if non-nil, zero value otherwise.

### GetModifiedDateOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetModifiedDateOk() (*time.Time, bool)`

GetModifiedDateOk returns a tuple with the ModifiedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDate

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) SetModifiedDate(v time.Time)`

SetModifiedDate sets ModifiedDate field to given value.

### HasModifiedDate

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) HasModifiedDate() bool`

HasModifiedDate returns a boolean if a field has been set.

### GetBooked

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetBooked() bool`

GetBooked returns the Booked field if non-nil, zero value otherwise.

### GetBookedOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetBookedOk() (*bool, bool)`

GetBookedOk returns a tuple with the Booked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBooked

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) SetBooked(v bool)`

SetBooked sets Booked field to given value.

### HasBooked

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) HasBooked() bool`

HasBooked returns a boolean if a field has been set.

### GetTaxableDate

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetTaxableDate() time.Time`

GetTaxableDate returns the TaxableDate field if non-nil, zero value otherwise.

### GetTaxableDateOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetTaxableDateOk() (*time.Time, bool)`

GetTaxableDateOk returns a tuple with the TaxableDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxableDate

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) SetTaxableDate(v time.Time)`

SetTaxableDate sets TaxableDate field to given value.

### HasTaxableDate

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) HasTaxableDate() bool`

HasTaxableDate returns a boolean if a field has been set.

### GetAmount

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetAmount() float64`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetAmountOk() (*float64, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) SetAmount(v float64)`

SetAmount sets Amount field to given value.

### HasAmount

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) HasAmount() bool`

HasAmount returns a boolean if a field has been set.

### GetPaid

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetPaid() bool`

GetPaid returns the Paid field if non-nil, zero value otherwise.

### GetPaidOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetPaidOk() (*bool, bool)`

GetPaidOk returns a tuple with the Paid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaid

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) SetPaid(v bool)`

SetPaid sets Paid field to given value.

### HasPaid

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) HasPaid() bool`

HasPaid returns a boolean if a field has been set.

### GetPaidDate

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetPaidDate() time.Time`

GetPaidDate returns the PaidDate field if non-nil, zero value otherwise.

### GetPaidDateOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetPaidDateOk() (*time.Time, bool)`

GetPaidDateOk returns a tuple with the PaidDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaidDate

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) SetPaidDate(v time.Time)`

SetPaidDate sets PaidDate field to given value.

### HasPaidDate

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) HasPaidDate() bool`

HasPaidDate returns a boolean if a field has been set.

### GetPaidPeriod

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetPaidPeriod() string`

GetPaidPeriod returns the PaidPeriod field if non-nil, zero value otherwise.

### GetPaidPeriodOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetPaidPeriodOk() (*string, bool)`

GetPaidPeriodOk returns a tuple with the PaidPeriod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaidPeriod

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) SetPaidPeriod(v string)`

SetPaidPeriod sets PaidPeriod field to given value.

### HasPaidPeriod

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) HasPaidPeriod() bool`

HasPaidPeriod returns a boolean if a field has been set.

### GetTotalControlAmount

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetTotalControlAmount() float64`

GetTotalControlAmount returns the TotalControlAmount field if non-nil, zero value otherwise.

### GetTotalControlAmountOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetTotalControlAmountOk() (*float64, bool)`

GetTotalControlAmountOk returns a tuple with the TotalControlAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalControlAmount

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) SetTotalControlAmount(v float64)`

SetTotalControlAmount sets TotalControlAmount field to given value.

### HasTotalControlAmount

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) HasTotalControlAmount() bool`

HasTotalControlAmount returns a boolean if a field has been set.

### GetExpectedPayDate

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetExpectedPayDate() time.Time`

GetExpectedPayDate returns the ExpectedPayDate field if non-nil, zero value otherwise.

### GetExpectedPayDateOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetExpectedPayDateOk() (*time.Time, bool)`

GetExpectedPayDateOk returns a tuple with the ExpectedPayDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedPayDate

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) SetExpectedPayDate(v time.Time)`

SetExpectedPayDate sets ExpectedPayDate field to given value.

### HasExpectedPayDate

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) HasExpectedPayDate() bool`

HasExpectedPayDate returns a boolean if a field has been set.

### GetTaxId

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetTaxId() string`

GetTaxId returns the TaxId field if non-nil, zero value otherwise.

### GetTaxIdOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetTaxIdOk() (*string, bool)`

GetTaxIdOk returns a tuple with the TaxId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxId

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) SetTaxId(v string)`

SetTaxId sets TaxId field to given value.

### HasTaxId

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) HasTaxId() bool`

HasTaxId returns a boolean if a field has been set.

### GetForeignCurrencyAmount

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetForeignCurrencyAmount() float64`

GetForeignCurrencyAmount returns the ForeignCurrencyAmount field if non-nil, zero value otherwise.

### GetForeignCurrencyAmountOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetForeignCurrencyAmountOk() (*float64, bool)`

GetForeignCurrencyAmountOk returns a tuple with the ForeignCurrencyAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForeignCurrencyAmount

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) SetForeignCurrencyAmount(v float64)`

SetForeignCurrencyAmount sets ForeignCurrencyAmount field to given value.

### HasForeignCurrencyAmount

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) HasForeignCurrencyAmount() bool`

HasForeignCurrencyAmount returns a boolean if a field has been set.

### GetDiscountDueDate

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetDiscountDueDate() time.Time`

GetDiscountDueDate returns the DiscountDueDate field if non-nil, zero value otherwise.

### GetDiscountDueDateOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetDiscountDueDateOk() (*time.Time, bool)`

GetDiscountDueDateOk returns a tuple with the DiscountDueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscountDueDate

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) SetDiscountDueDate(v time.Time)`

SetDiscountDueDate sets DiscountDueDate field to given value.

### HasDiscountDueDate

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) HasDiscountDueDate() bool`

HasDiscountDueDate returns a boolean if a field has been set.

### GetExchangeRateDate

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetExchangeRateDate() time.Time`

GetExchangeRateDate returns the ExchangeRateDate field if non-nil, zero value otherwise.

### GetExchangeRateDateOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetExchangeRateDateOk() (*time.Time, bool)`

GetExchangeRateDateOk returns a tuple with the ExchangeRateDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExchangeRateDate

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) SetExchangeRateDate(v time.Time)`

SetExchangeRateDate sets ExchangeRateDate field to given value.

### HasExchangeRateDate

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) HasExchangeRateDate() bool`

HasExchangeRateDate returns a boolean if a field has been set.

### GetBalance

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetBalance() float64`

GetBalance returns the Balance field if non-nil, zero value otherwise.

### GetBalanceOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetBalanceOk() (*float64, bool)`

GetBalanceOk returns a tuple with the Balance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBalance

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) SetBalance(v float64)`

SetBalance sets Balance field to given value.

### HasBalance

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) HasBalance() bool`

HasBalance returns a boolean if a field has been set.

### GetDiscountableAmount

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetDiscountableAmount() float64`

GetDiscountableAmount returns the DiscountableAmount field if non-nil, zero value otherwise.

### GetDiscountableAmountOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetDiscountableAmountOk() (*float64, bool)`

GetDiscountableAmountOk returns a tuple with the DiscountableAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscountableAmount

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) SetDiscountableAmount(v float64)`

SetDiscountableAmount sets DiscountableAmount field to given value.

### HasDiscountableAmount

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) HasDiscountableAmount() bool`

HasDiscountableAmount returns a boolean if a field has been set.

### GetDebitMemo

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetDebitMemo() int32`

GetDebitMemo returns the DebitMemo field if non-nil, zero value otherwise.

### GetDebitMemoOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetDebitMemoOk() (*int32, bool)`

GetDebitMemoOk returns a tuple with the DebitMemo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDebitMemo

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) SetDebitMemo(v int32)`

SetDebitMemo sets DebitMemo field to given value.

### HasDebitMemo

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) HasDebitMemo() bool`

HasDebitMemo returns a boolean if a field has been set.

### GetIntercompany

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetIntercompany() int32`

GetIntercompany returns the Intercompany field if non-nil, zero value otherwise.

### GetIntercompanyOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetIntercompanyOk() (*int32, bool)`

GetIntercompanyOk returns a tuple with the Intercompany field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIntercompany

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) SetIntercompany(v int32)`

SetIntercompany sets Intercompany field to given value.

### HasIntercompany

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) HasIntercompany() bool`

HasIntercompany returns a boolean if a field has been set.

### GetCheckNote

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetCheckNote() string`

GetCheckNote returns the CheckNote field if non-nil, zero value otherwise.

### GetCheckNoteOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetCheckNoteOk() (*string, bool)`

GetCheckNoteOk returns a tuple with the CheckNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckNote

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) SetCheckNote(v string)`

SetCheckNote sets CheckNote field to given value.

### HasCheckNote

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) HasCheckNote() bool`

HasCheckNote returns a boolean if a field has been set.

### GetShipperNo

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetShipperNo() string`

GetShipperNo returns the ShipperNo field if non-nil, zero value otherwise.

### GetShipperNoOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetShipperNoOk() (*string, bool)`

GetShipperNoOk returns a tuple with the ShipperNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipperNo

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) SetShipperNo(v string)`

SetShipperNo sets ShipperNo field to given value.

### HasShipperNo

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) HasShipperNo() bool`

HasShipperNo returns a boolean if a field has been set.

### GetShipperId

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetShipperId() string`

GetShipperId returns the ShipperId field if non-nil, zero value otherwise.

### GetShipperIdOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetShipperIdOk() (*string, bool)`

GetShipperIdOk returns a tuple with the ShipperId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipperId

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) SetShipperId(v string)`

SetShipperId sets ShipperId field to given value.

### HasShipperId

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) HasShipperId() bool`

HasShipperId returns a boolean if a field has been set.

### GetPoNumber

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetPoNumber() string`

GetPoNumber returns the PoNumber field if non-nil, zero value otherwise.

### GetPoNumberOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetPoNumberOk() (*string, bool)`

GetPoNumberOk returns a tuple with the PoNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoNumber

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) SetPoNumber(v string)`

SetPoNumber sets PoNumber field to given value.

### HasPoNumber

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) HasPoNumber() bool`

HasPoNumber returns a boolean if a field has been set.

### GetPoId

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetPoId() string`

GetPoId returns the PoId field if non-nil, zero value otherwise.

### GetPoIdOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetPoIdOk() (*string, bool)`

GetPoIdOk returns a tuple with the PoId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoId

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) SetPoId(v string)`

SetPoId sets PoId field to given value.

### HasPoId

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) HasPoId() bool`

HasPoId returns a boolean if a field has been set.

### GetExternalReferenceCode

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetExternalReferenceCode() string`

GetExternalReferenceCode returns the ExternalReferenceCode field if non-nil, zero value otherwise.

### GetExternalReferenceCodeOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetExternalReferenceCodeOk() (*string, bool)`

GetExternalReferenceCodeOk returns a tuple with the ExternalReferenceCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalReferenceCode

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) SetExternalReferenceCode(v string)`

SetExternalReferenceCode sets ExternalReferenceCode field to given value.

### HasExternalReferenceCode

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) HasExternalReferenceCode() bool`

HasExternalReferenceCode returns a boolean if a field has been set.

### GetForeignCurrencyBalance

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetForeignCurrencyBalance() float64`

GetForeignCurrencyBalance returns the ForeignCurrencyBalance field if non-nil, zero value otherwise.

### GetForeignCurrencyBalanceOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetForeignCurrencyBalanceOk() (*float64, bool)`

GetForeignCurrencyBalanceOk returns a tuple with the ForeignCurrencyBalance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForeignCurrencyBalance

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) SetForeignCurrencyBalance(v float64)`

SetForeignCurrencyBalance sets ForeignCurrencyBalance field to given value.

### HasForeignCurrencyBalance

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) HasForeignCurrencyBalance() bool`

HasForeignCurrencyBalance returns a boolean if a field has been set.

### GetLines

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetLines() []LinesItem`

GetLines returns the Lines field if non-nil, zero value otherwise.

### GetLinesOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) GetLinesOk() (*[]LinesItem, bool)`

GetLinesOk returns a tuple with the Lines field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLines

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) SetLines(v []LinesItem)`

SetLines sets Lines field to given value.

### HasLines

`func (o *AccountsPayableInvoicesApiCreateAPInvoice201Response) HasLines() bool`

HasLines returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


