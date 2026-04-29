# AccountsPayableInvoicesApiListAPInvoicesItem

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

### NewAccountsPayableInvoicesApiListAPInvoicesItem

`func NewAccountsPayableInvoicesApiListAPInvoicesItem() *AccountsPayableInvoicesApiListAPInvoicesItem`

NewAccountsPayableInvoicesApiListAPInvoicesItem instantiates a new AccountsPayableInvoicesApiListAPInvoicesItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccountsPayableInvoicesApiListAPInvoicesItemWithDefaults

`func NewAccountsPayableInvoicesApiListAPInvoicesItemWithDefaults() *AccountsPayableInvoicesApiListAPInvoicesItem`

NewAccountsPayableInvoicesApiListAPInvoicesItemWithDefaults instantiates a new AccountsPayableInvoicesApiListAPInvoicesItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) HasId() bool`

HasId returns a boolean if a field has been set.

### GetInvoiceNumber

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetInvoiceNumber() string`

GetInvoiceNumber returns the InvoiceNumber field if non-nil, zero value otherwise.

### GetInvoiceNumberOk

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetInvoiceNumberOk() (*string, bool)`

GetInvoiceNumberOk returns a tuple with the InvoiceNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceNumber

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) SetInvoiceNumber(v string)`

SetInvoiceNumber sets InvoiceNumber field to given value.

### HasInvoiceNumber

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) HasInvoiceNumber() bool`

HasInvoiceNumber returns a boolean if a field has been set.

### GetSupplierId

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetSupplierId() string`

GetSupplierId returns the SupplierId field if non-nil, zero value otherwise.

### GetSupplierIdOk

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetSupplierIdOk() (*string, bool)`

GetSupplierIdOk returns a tuple with the SupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierId

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) SetSupplierId(v string)`

SetSupplierId sets SupplierId field to given value.

### HasSupplierId

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) HasSupplierId() bool`

HasSupplierId returns a boolean if a field has been set.

### GetSupplierCode

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetSupplierCode() string`

GetSupplierCode returns the SupplierCode field if non-nil, zero value otherwise.

### GetSupplierCodeOk

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetSupplierCodeOk() (*string, bool)`

GetSupplierCodeOk returns a tuple with the SupplierCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierCode

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) SetSupplierCode(v string)`

SetSupplierCode sets SupplierCode field to given value.

### HasSupplierCode

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) HasSupplierCode() bool`

HasSupplierCode returns a boolean if a field has been set.

### GetSupplierAddressId

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetSupplierAddressId() string`

GetSupplierAddressId returns the SupplierAddressId field if non-nil, zero value otherwise.

### GetSupplierAddressIdOk

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetSupplierAddressIdOk() (*string, bool)`

GetSupplierAddressIdOk returns a tuple with the SupplierAddressId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierAddressId

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) SetSupplierAddressId(v string)`

SetSupplierAddressId sets SupplierAddressId field to given value.

### HasSupplierAddressId

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) HasSupplierAddressId() bool`

HasSupplierAddressId returns a boolean if a field has been set.

### GetSupplierAddressCode

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetSupplierAddressCode() string`

GetSupplierAddressCode returns the SupplierAddressCode field if non-nil, zero value otherwise.

### GetSupplierAddressCodeOk

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetSupplierAddressCodeOk() (*string, bool)`

GetSupplierAddressCodeOk returns a tuple with the SupplierAddressCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierAddressCode

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) SetSupplierAddressCode(v string)`

SetSupplierAddressCode sets SupplierAddressCode field to given value.

### HasSupplierAddressCode

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) HasSupplierAddressCode() bool`

HasSupplierAddressCode returns a boolean if a field has been set.

### GetPeriodDisplay

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetPeriodDisplay() string`

GetPeriodDisplay returns the PeriodDisplay field if non-nil, zero value otherwise.

### GetPeriodDisplayOk

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetPeriodDisplayOk() (*string, bool)`

GetPeriodDisplayOk returns a tuple with the PeriodDisplay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriodDisplay

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) SetPeriodDisplay(v string)`

SetPeriodDisplay sets PeriodDisplay field to given value.

### HasPeriodDisplay

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) HasPeriodDisplay() bool`

HasPeriodDisplay returns a boolean if a field has been set.

### GetTransactionDate

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetTransactionDate() time.Time`

GetTransactionDate returns the TransactionDate field if non-nil, zero value otherwise.

### GetTransactionDateOk

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetTransactionDateOk() (*time.Time, bool)`

GetTransactionDateOk returns a tuple with the TransactionDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransactionDate

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) SetTransactionDate(v time.Time)`

SetTransactionDate sets TransactionDate field to given value.

### HasTransactionDate

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) HasTransactionDate() bool`

HasTransactionDate returns a boolean if a field has been set.

### GetBuildingCode

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetBuildingCode() string`

GetBuildingCode returns the BuildingCode field if non-nil, zero value otherwise.

### GetBuildingCodeOk

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetBuildingCodeOk() (*string, bool)`

GetBuildingCodeOk returns a tuple with the BuildingCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildingCode

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) SetBuildingCode(v string)`

SetBuildingCode sets BuildingCode field to given value.

### HasBuildingCode

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) HasBuildingCode() bool`

HasBuildingCode returns a boolean if a field has been set.

### GetCurrencyCode

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetCurrencyCode() string`

GetCurrencyCode returns the CurrencyCode field if non-nil, zero value otherwise.

### GetCurrencyCodeOk

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetCurrencyCodeOk() (*string, bool)`

GetCurrencyCodeOk returns a tuple with the CurrencyCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyCode

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) SetCurrencyCode(v string)`

SetCurrencyCode sets CurrencyCode field to given value.

### HasCurrencyCode

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) HasCurrencyCode() bool`

HasCurrencyCode returns a boolean if a field has been set.

### GetExchangeRate

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetExchangeRate() float64`

GetExchangeRate returns the ExchangeRate field if non-nil, zero value otherwise.

### GetExchangeRateOk

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetExchangeRateOk() (*float64, bool)`

GetExchangeRateOk returns a tuple with the ExchangeRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExchangeRate

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) SetExchangeRate(v float64)`

SetExchangeRate sets ExchangeRate field to given value.

### HasExchangeRate

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) HasExchangeRate() bool`

HasExchangeRate returns a boolean if a field has been set.

### GetDepartment

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetDepartment() int32`

GetDepartment returns the Department field if non-nil, zero value otherwise.

### GetDepartmentOk

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetDepartmentOk() (*int32, bool)`

GetDepartmentOk returns a tuple with the Department field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDepartment

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) SetDepartment(v int32)`

SetDepartment sets Department field to given value.

### HasDepartment

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) HasDepartment() bool`

HasDepartment returns a boolean if a field has been set.

### GetTerms

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetTerms() string`

GetTerms returns the Terms field if non-nil, zero value otherwise.

### GetTermsOk

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetTermsOk() (*string, bool)`

GetTermsOk returns a tuple with the Terms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTerms

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) SetTerms(v string)`

SetTerms sets Terms field to given value.

### HasTerms

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) HasTerms() bool`

HasTerms returns a boolean if a field has been set.

### GetDueDate

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetDueDate() time.Time`

GetDueDate returns the DueDate field if non-nil, zero value otherwise.

### GetDueDateOk

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetDueDateOk() (*time.Time, bool)`

GetDueDateOk returns a tuple with the DueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueDate

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) SetDueDate(v time.Time)`

SetDueDate sets DueDate field to given value.

### HasDueDate

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) HasDueDate() bool`

HasDueDate returns a boolean if a field has been set.

### GetDiscount

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetDiscount() float64`

GetDiscount returns the Discount field if non-nil, zero value otherwise.

### GetDiscountOk

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetDiscountOk() (*float64, bool)`

GetDiscountOk returns a tuple with the Discount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscount

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) SetDiscount(v float64)`

SetDiscount sets Discount field to given value.

### HasDiscount

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) HasDiscount() bool`

HasDiscount returns a boolean if a field has been set.

### GetInternalNote

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetInternalNote() string`

GetInternalNote returns the InternalNote field if non-nil, zero value otherwise.

### GetInternalNoteOk

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetInternalNoteOk() (*string, bool)`

GetInternalNoteOk returns a tuple with the InternalNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInternalNote

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) SetInternalNote(v string)`

SetInternalNote sets InternalNote field to given value.

### HasInternalNote

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) HasInternalNote() bool`

HasInternalNote returns a boolean if a field has been set.

### GetVoucherNumber

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetVoucherNumber() string`

GetVoucherNumber returns the VoucherNumber field if non-nil, zero value otherwise.

### GetVoucherNumberOk

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetVoucherNumberOk() (*string, bool)`

GetVoucherNumberOk returns a tuple with the VoucherNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoucherNumber

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) SetVoucherNumber(v string)`

SetVoucherNumber sets VoucherNumber field to given value.

### HasVoucherNumber

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) HasVoucherNumber() bool`

HasVoucherNumber returns a boolean if a field has been set.

### GetStatus

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetGovernmentIssuedNumber

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetGovernmentIssuedNumber() string`

GetGovernmentIssuedNumber returns the GovernmentIssuedNumber field if non-nil, zero value otherwise.

### GetGovernmentIssuedNumberOk

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetGovernmentIssuedNumberOk() (*string, bool)`

GetGovernmentIssuedNumberOk returns a tuple with the GovernmentIssuedNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGovernmentIssuedNumber

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) SetGovernmentIssuedNumber(v string)`

SetGovernmentIssuedNumber sets GovernmentIssuedNumber field to given value.

### HasGovernmentIssuedNumber

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) HasGovernmentIssuedNumber() bool`

HasGovernmentIssuedNumber returns a boolean if a field has been set.

### GetType

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) HasType() bool`

HasType returns a boolean if a field has been set.

### GetCreatedById

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetCreatedById() string`

GetCreatedById returns the CreatedById field if non-nil, zero value otherwise.

### GetCreatedByIdOk

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetCreatedByIdOk() (*string, bool)`

GetCreatedByIdOk returns a tuple with the CreatedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedById

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) SetCreatedById(v string)`

SetCreatedById sets CreatedById field to given value.

### HasCreatedById

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) HasCreatedById() bool`

HasCreatedById returns a boolean if a field has been set.

### GetCreatedDate

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.

### GetModifiedById

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetModifiedDate

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetModifiedDate() time.Time`

GetModifiedDate returns the ModifiedDate field if non-nil, zero value otherwise.

### GetModifiedDateOk

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetModifiedDateOk() (*time.Time, bool)`

GetModifiedDateOk returns a tuple with the ModifiedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDate

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) SetModifiedDate(v time.Time)`

SetModifiedDate sets ModifiedDate field to given value.

### HasModifiedDate

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) HasModifiedDate() bool`

HasModifiedDate returns a boolean if a field has been set.

### GetBooked

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetBooked() bool`

GetBooked returns the Booked field if non-nil, zero value otherwise.

### GetBookedOk

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetBookedOk() (*bool, bool)`

GetBookedOk returns a tuple with the Booked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBooked

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) SetBooked(v bool)`

SetBooked sets Booked field to given value.

### HasBooked

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) HasBooked() bool`

HasBooked returns a boolean if a field has been set.

### GetTaxableDate

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetTaxableDate() time.Time`

GetTaxableDate returns the TaxableDate field if non-nil, zero value otherwise.

### GetTaxableDateOk

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetTaxableDateOk() (*time.Time, bool)`

GetTaxableDateOk returns a tuple with the TaxableDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxableDate

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) SetTaxableDate(v time.Time)`

SetTaxableDate sets TaxableDate field to given value.

### HasTaxableDate

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) HasTaxableDate() bool`

HasTaxableDate returns a boolean if a field has been set.

### GetAmount

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetAmount() float64`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetAmountOk() (*float64, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) SetAmount(v float64)`

SetAmount sets Amount field to given value.

### HasAmount

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) HasAmount() bool`

HasAmount returns a boolean if a field has been set.

### GetPaid

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetPaid() bool`

GetPaid returns the Paid field if non-nil, zero value otherwise.

### GetPaidOk

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetPaidOk() (*bool, bool)`

GetPaidOk returns a tuple with the Paid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaid

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) SetPaid(v bool)`

SetPaid sets Paid field to given value.

### HasPaid

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) HasPaid() bool`

HasPaid returns a boolean if a field has been set.

### GetPaidDate

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetPaidDate() time.Time`

GetPaidDate returns the PaidDate field if non-nil, zero value otherwise.

### GetPaidDateOk

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetPaidDateOk() (*time.Time, bool)`

GetPaidDateOk returns a tuple with the PaidDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaidDate

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) SetPaidDate(v time.Time)`

SetPaidDate sets PaidDate field to given value.

### HasPaidDate

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) HasPaidDate() bool`

HasPaidDate returns a boolean if a field has been set.

### GetPaidPeriod

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetPaidPeriod() string`

GetPaidPeriod returns the PaidPeriod field if non-nil, zero value otherwise.

### GetPaidPeriodOk

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetPaidPeriodOk() (*string, bool)`

GetPaidPeriodOk returns a tuple with the PaidPeriod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaidPeriod

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) SetPaidPeriod(v string)`

SetPaidPeriod sets PaidPeriod field to given value.

### HasPaidPeriod

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) HasPaidPeriod() bool`

HasPaidPeriod returns a boolean if a field has been set.

### GetTotalControlAmount

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetTotalControlAmount() float64`

GetTotalControlAmount returns the TotalControlAmount field if non-nil, zero value otherwise.

### GetTotalControlAmountOk

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetTotalControlAmountOk() (*float64, bool)`

GetTotalControlAmountOk returns a tuple with the TotalControlAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalControlAmount

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) SetTotalControlAmount(v float64)`

SetTotalControlAmount sets TotalControlAmount field to given value.

### HasTotalControlAmount

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) HasTotalControlAmount() bool`

HasTotalControlAmount returns a boolean if a field has been set.

### GetExpectedPayDate

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetExpectedPayDate() time.Time`

GetExpectedPayDate returns the ExpectedPayDate field if non-nil, zero value otherwise.

### GetExpectedPayDateOk

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetExpectedPayDateOk() (*time.Time, bool)`

GetExpectedPayDateOk returns a tuple with the ExpectedPayDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedPayDate

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) SetExpectedPayDate(v time.Time)`

SetExpectedPayDate sets ExpectedPayDate field to given value.

### HasExpectedPayDate

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) HasExpectedPayDate() bool`

HasExpectedPayDate returns a boolean if a field has been set.

### GetTaxId

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetTaxId() string`

GetTaxId returns the TaxId field if non-nil, zero value otherwise.

### GetTaxIdOk

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetTaxIdOk() (*string, bool)`

GetTaxIdOk returns a tuple with the TaxId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxId

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) SetTaxId(v string)`

SetTaxId sets TaxId field to given value.

### HasTaxId

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) HasTaxId() bool`

HasTaxId returns a boolean if a field has been set.

### GetForeignCurrencyAmount

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetForeignCurrencyAmount() float64`

GetForeignCurrencyAmount returns the ForeignCurrencyAmount field if non-nil, zero value otherwise.

### GetForeignCurrencyAmountOk

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetForeignCurrencyAmountOk() (*float64, bool)`

GetForeignCurrencyAmountOk returns a tuple with the ForeignCurrencyAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForeignCurrencyAmount

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) SetForeignCurrencyAmount(v float64)`

SetForeignCurrencyAmount sets ForeignCurrencyAmount field to given value.

### HasForeignCurrencyAmount

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) HasForeignCurrencyAmount() bool`

HasForeignCurrencyAmount returns a boolean if a field has been set.

### GetDiscountDueDate

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetDiscountDueDate() time.Time`

GetDiscountDueDate returns the DiscountDueDate field if non-nil, zero value otherwise.

### GetDiscountDueDateOk

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetDiscountDueDateOk() (*time.Time, bool)`

GetDiscountDueDateOk returns a tuple with the DiscountDueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscountDueDate

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) SetDiscountDueDate(v time.Time)`

SetDiscountDueDate sets DiscountDueDate field to given value.

### HasDiscountDueDate

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) HasDiscountDueDate() bool`

HasDiscountDueDate returns a boolean if a field has been set.

### GetExchangeRateDate

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetExchangeRateDate() time.Time`

GetExchangeRateDate returns the ExchangeRateDate field if non-nil, zero value otherwise.

### GetExchangeRateDateOk

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetExchangeRateDateOk() (*time.Time, bool)`

GetExchangeRateDateOk returns a tuple with the ExchangeRateDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExchangeRateDate

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) SetExchangeRateDate(v time.Time)`

SetExchangeRateDate sets ExchangeRateDate field to given value.

### HasExchangeRateDate

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) HasExchangeRateDate() bool`

HasExchangeRateDate returns a boolean if a field has been set.

### GetBalance

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetBalance() float64`

GetBalance returns the Balance field if non-nil, zero value otherwise.

### GetBalanceOk

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetBalanceOk() (*float64, bool)`

GetBalanceOk returns a tuple with the Balance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBalance

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) SetBalance(v float64)`

SetBalance sets Balance field to given value.

### HasBalance

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) HasBalance() bool`

HasBalance returns a boolean if a field has been set.

### GetDiscountableAmount

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetDiscountableAmount() float64`

GetDiscountableAmount returns the DiscountableAmount field if non-nil, zero value otherwise.

### GetDiscountableAmountOk

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetDiscountableAmountOk() (*float64, bool)`

GetDiscountableAmountOk returns a tuple with the DiscountableAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscountableAmount

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) SetDiscountableAmount(v float64)`

SetDiscountableAmount sets DiscountableAmount field to given value.

### HasDiscountableAmount

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) HasDiscountableAmount() bool`

HasDiscountableAmount returns a boolean if a field has been set.

### GetDebitMemo

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetDebitMemo() int32`

GetDebitMemo returns the DebitMemo field if non-nil, zero value otherwise.

### GetDebitMemoOk

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetDebitMemoOk() (*int32, bool)`

GetDebitMemoOk returns a tuple with the DebitMemo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDebitMemo

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) SetDebitMemo(v int32)`

SetDebitMemo sets DebitMemo field to given value.

### HasDebitMemo

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) HasDebitMemo() bool`

HasDebitMemo returns a boolean if a field has been set.

### GetIntercompany

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetIntercompany() int32`

GetIntercompany returns the Intercompany field if non-nil, zero value otherwise.

### GetIntercompanyOk

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetIntercompanyOk() (*int32, bool)`

GetIntercompanyOk returns a tuple with the Intercompany field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIntercompany

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) SetIntercompany(v int32)`

SetIntercompany sets Intercompany field to given value.

### HasIntercompany

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) HasIntercompany() bool`

HasIntercompany returns a boolean if a field has been set.

### GetCheckNote

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetCheckNote() string`

GetCheckNote returns the CheckNote field if non-nil, zero value otherwise.

### GetCheckNoteOk

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetCheckNoteOk() (*string, bool)`

GetCheckNoteOk returns a tuple with the CheckNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckNote

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) SetCheckNote(v string)`

SetCheckNote sets CheckNote field to given value.

### HasCheckNote

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) HasCheckNote() bool`

HasCheckNote returns a boolean if a field has been set.

### GetShipperNo

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetShipperNo() string`

GetShipperNo returns the ShipperNo field if non-nil, zero value otherwise.

### GetShipperNoOk

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetShipperNoOk() (*string, bool)`

GetShipperNoOk returns a tuple with the ShipperNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipperNo

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) SetShipperNo(v string)`

SetShipperNo sets ShipperNo field to given value.

### HasShipperNo

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) HasShipperNo() bool`

HasShipperNo returns a boolean if a field has been set.

### GetShipperId

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetShipperId() string`

GetShipperId returns the ShipperId field if non-nil, zero value otherwise.

### GetShipperIdOk

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetShipperIdOk() (*string, bool)`

GetShipperIdOk returns a tuple with the ShipperId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipperId

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) SetShipperId(v string)`

SetShipperId sets ShipperId field to given value.

### HasShipperId

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) HasShipperId() bool`

HasShipperId returns a boolean if a field has been set.

### GetPoNumber

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetPoNumber() string`

GetPoNumber returns the PoNumber field if non-nil, zero value otherwise.

### GetPoNumberOk

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetPoNumberOk() (*string, bool)`

GetPoNumberOk returns a tuple with the PoNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoNumber

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) SetPoNumber(v string)`

SetPoNumber sets PoNumber field to given value.

### HasPoNumber

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) HasPoNumber() bool`

HasPoNumber returns a boolean if a field has been set.

### GetPoId

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetPoId() string`

GetPoId returns the PoId field if non-nil, zero value otherwise.

### GetPoIdOk

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetPoIdOk() (*string, bool)`

GetPoIdOk returns a tuple with the PoId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoId

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) SetPoId(v string)`

SetPoId sets PoId field to given value.

### HasPoId

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) HasPoId() bool`

HasPoId returns a boolean if a field has been set.

### GetExternalReferenceCode

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetExternalReferenceCode() string`

GetExternalReferenceCode returns the ExternalReferenceCode field if non-nil, zero value otherwise.

### GetExternalReferenceCodeOk

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetExternalReferenceCodeOk() (*string, bool)`

GetExternalReferenceCodeOk returns a tuple with the ExternalReferenceCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalReferenceCode

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) SetExternalReferenceCode(v string)`

SetExternalReferenceCode sets ExternalReferenceCode field to given value.

### HasExternalReferenceCode

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) HasExternalReferenceCode() bool`

HasExternalReferenceCode returns a boolean if a field has been set.

### GetForeignCurrencyBalance

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetForeignCurrencyBalance() float64`

GetForeignCurrencyBalance returns the ForeignCurrencyBalance field if non-nil, zero value otherwise.

### GetForeignCurrencyBalanceOk

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetForeignCurrencyBalanceOk() (*float64, bool)`

GetForeignCurrencyBalanceOk returns a tuple with the ForeignCurrencyBalance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForeignCurrencyBalance

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) SetForeignCurrencyBalance(v float64)`

SetForeignCurrencyBalance sets ForeignCurrencyBalance field to given value.

### HasForeignCurrencyBalance

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) HasForeignCurrencyBalance() bool`

HasForeignCurrencyBalance returns a boolean if a field has been set.

### GetLines

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetLines() []LinesItem`

GetLines returns the Lines field if non-nil, zero value otherwise.

### GetLinesOk

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) GetLinesOk() (*[]LinesItem, bool)`

GetLinesOk returns a tuple with the Lines field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLines

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) SetLines(v []LinesItem)`

SetLines sets Lines field to given value.

### HasLines

`func (o *AccountsPayableInvoicesApiListAPInvoicesItem) HasLines() bool`

HasLines returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


