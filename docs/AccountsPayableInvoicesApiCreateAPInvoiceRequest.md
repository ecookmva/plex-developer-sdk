# AccountsPayableInvoicesApiCreateAPInvoiceRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**InvoiceNumber** | Pointer to **string** | The AP invoice number. | [optional] 
**SupplierId** | Pointer to **string** | The AP invoice supplier ID. | [optional] 
**SupplierCode** | Pointer to **string** | The AP supplier code, typically an abbreviated name for the supplier. | [optional] 
**SupplierAddressCode** | Pointer to **string** | The AP invoice supplier address code. | [optional] 
**Terms** | Pointer to **string** | The AP invoice terms. | [optional] 
**PeriodDisplay** | Pointer to **string** | The period in which an AP invoice is recorded. | [optional] 
**CurrencyCode** | Pointer to **string** | The AP invoice currency code. | [optional] 
**Status** | Pointer to **string** | The AP invoice status. | [optional] 
**DiscountDueDate** | Pointer to **time.Time** | The AP invoice discount due date. | [optional] 
**PoId** | Pointer to **string** | The AP invoice purchase order ID. | [optional] 
**Note** | Pointer to **string** | A note added to an AP invoice. | [optional] 
**CheckNote** | Pointer to **string** | A check note added to an AP invoice. | [optional] 
**BuildingCode** | Pointer to **string** | The code used to look up the building resource. | [optional] 
**InvoiceDate** | Pointer to **time.Time** | The date an AP transaction was recorded. | [optional] 
**PoNumber** | Pointer to **string** | The AP invoice purchase order number. | [optional] 
**DueDate** | Pointer to **time.Time** | The AP invoice due date. | [optional] 
**Department** | Pointer to **string** | The AP invoice department code. | [optional] 
**ExchangeRate** | Pointer to **float64** | The AP invoice exchange rate. | [optional] 
**DebitMemo** | Pointer to **bool** | Specify that the AP invoice is a debit memo. | [optional] 
**GovernmentIssuedNumber** | Pointer to **string** | The AP invoice government issued number. | [optional] 
**Discount** | Pointer to **float64** | The AP invoice discount. | [optional] 
**InterCompany** | Pointer to **bool** | The AP invoice intercompany tax. | [optional] 
**DiscountableAmount** | Pointer to **float64** | The AP invoice discountable amount. | [optional] 
**TaxPointDate** | Pointer to **time.Time** | The AP invoice tax point date. | [optional] 
**ExpectedPayDate** | Pointer to **time.Time** | The AP invoice expected pay date. | [optional] 
**Type** | Pointer to **string** | The AP invoice type. | [optional] 
**Lines** | Pointer to [**[]LinesItem1**](LinesItem1.md) | A list of AP invoice lines. | [optional] 
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

### NewAccountsPayableInvoicesApiCreateAPInvoiceRequest

`func NewAccountsPayableInvoicesApiCreateAPInvoiceRequest() *AccountsPayableInvoicesApiCreateAPInvoiceRequest`

NewAccountsPayableInvoicesApiCreateAPInvoiceRequest instantiates a new AccountsPayableInvoicesApiCreateAPInvoiceRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccountsPayableInvoicesApiCreateAPInvoiceRequestWithDefaults

`func NewAccountsPayableInvoicesApiCreateAPInvoiceRequestWithDefaults() *AccountsPayableInvoicesApiCreateAPInvoiceRequest`

NewAccountsPayableInvoicesApiCreateAPInvoiceRequestWithDefaults instantiates a new AccountsPayableInvoicesApiCreateAPInvoiceRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetInvoiceNumber

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetInvoiceNumber() string`

GetInvoiceNumber returns the InvoiceNumber field if non-nil, zero value otherwise.

### GetInvoiceNumberOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetInvoiceNumberOk() (*string, bool)`

GetInvoiceNumberOk returns a tuple with the InvoiceNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceNumber

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) SetInvoiceNumber(v string)`

SetInvoiceNumber sets InvoiceNumber field to given value.

### HasInvoiceNumber

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) HasInvoiceNumber() bool`

HasInvoiceNumber returns a boolean if a field has been set.

### GetSupplierId

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetSupplierId() string`

GetSupplierId returns the SupplierId field if non-nil, zero value otherwise.

### GetSupplierIdOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetSupplierIdOk() (*string, bool)`

GetSupplierIdOk returns a tuple with the SupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierId

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) SetSupplierId(v string)`

SetSupplierId sets SupplierId field to given value.

### HasSupplierId

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) HasSupplierId() bool`

HasSupplierId returns a boolean if a field has been set.

### GetSupplierCode

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetSupplierCode() string`

GetSupplierCode returns the SupplierCode field if non-nil, zero value otherwise.

### GetSupplierCodeOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetSupplierCodeOk() (*string, bool)`

GetSupplierCodeOk returns a tuple with the SupplierCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierCode

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) SetSupplierCode(v string)`

SetSupplierCode sets SupplierCode field to given value.

### HasSupplierCode

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) HasSupplierCode() bool`

HasSupplierCode returns a boolean if a field has been set.

### GetSupplierAddressCode

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetSupplierAddressCode() string`

GetSupplierAddressCode returns the SupplierAddressCode field if non-nil, zero value otherwise.

### GetSupplierAddressCodeOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetSupplierAddressCodeOk() (*string, bool)`

GetSupplierAddressCodeOk returns a tuple with the SupplierAddressCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierAddressCode

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) SetSupplierAddressCode(v string)`

SetSupplierAddressCode sets SupplierAddressCode field to given value.

### HasSupplierAddressCode

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) HasSupplierAddressCode() bool`

HasSupplierAddressCode returns a boolean if a field has been set.

### GetTerms

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetTerms() string`

GetTerms returns the Terms field if non-nil, zero value otherwise.

### GetTermsOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetTermsOk() (*string, bool)`

GetTermsOk returns a tuple with the Terms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTerms

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) SetTerms(v string)`

SetTerms sets Terms field to given value.

### HasTerms

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) HasTerms() bool`

HasTerms returns a boolean if a field has been set.

### GetPeriodDisplay

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetPeriodDisplay() string`

GetPeriodDisplay returns the PeriodDisplay field if non-nil, zero value otherwise.

### GetPeriodDisplayOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetPeriodDisplayOk() (*string, bool)`

GetPeriodDisplayOk returns a tuple with the PeriodDisplay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriodDisplay

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) SetPeriodDisplay(v string)`

SetPeriodDisplay sets PeriodDisplay field to given value.

### HasPeriodDisplay

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) HasPeriodDisplay() bool`

HasPeriodDisplay returns a boolean if a field has been set.

### GetCurrencyCode

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetCurrencyCode() string`

GetCurrencyCode returns the CurrencyCode field if non-nil, zero value otherwise.

### GetCurrencyCodeOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetCurrencyCodeOk() (*string, bool)`

GetCurrencyCodeOk returns a tuple with the CurrencyCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyCode

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) SetCurrencyCode(v string)`

SetCurrencyCode sets CurrencyCode field to given value.

### HasCurrencyCode

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) HasCurrencyCode() bool`

HasCurrencyCode returns a boolean if a field has been set.

### GetStatus

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetDiscountDueDate

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetDiscountDueDate() time.Time`

GetDiscountDueDate returns the DiscountDueDate field if non-nil, zero value otherwise.

### GetDiscountDueDateOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetDiscountDueDateOk() (*time.Time, bool)`

GetDiscountDueDateOk returns a tuple with the DiscountDueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscountDueDate

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) SetDiscountDueDate(v time.Time)`

SetDiscountDueDate sets DiscountDueDate field to given value.

### HasDiscountDueDate

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) HasDiscountDueDate() bool`

HasDiscountDueDate returns a boolean if a field has been set.

### GetPoId

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetPoId() string`

GetPoId returns the PoId field if non-nil, zero value otherwise.

### GetPoIdOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetPoIdOk() (*string, bool)`

GetPoIdOk returns a tuple with the PoId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoId

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) SetPoId(v string)`

SetPoId sets PoId field to given value.

### HasPoId

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) HasPoId() bool`

HasPoId returns a boolean if a field has been set.

### GetNote

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetCheckNote

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetCheckNote() string`

GetCheckNote returns the CheckNote field if non-nil, zero value otherwise.

### GetCheckNoteOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetCheckNoteOk() (*string, bool)`

GetCheckNoteOk returns a tuple with the CheckNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckNote

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) SetCheckNote(v string)`

SetCheckNote sets CheckNote field to given value.

### HasCheckNote

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) HasCheckNote() bool`

HasCheckNote returns a boolean if a field has been set.

### GetBuildingCode

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetBuildingCode() string`

GetBuildingCode returns the BuildingCode field if non-nil, zero value otherwise.

### GetBuildingCodeOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetBuildingCodeOk() (*string, bool)`

GetBuildingCodeOk returns a tuple with the BuildingCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildingCode

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) SetBuildingCode(v string)`

SetBuildingCode sets BuildingCode field to given value.

### HasBuildingCode

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) HasBuildingCode() bool`

HasBuildingCode returns a boolean if a field has been set.

### GetInvoiceDate

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetInvoiceDate() time.Time`

GetInvoiceDate returns the InvoiceDate field if non-nil, zero value otherwise.

### GetInvoiceDateOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetInvoiceDateOk() (*time.Time, bool)`

GetInvoiceDateOk returns a tuple with the InvoiceDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceDate

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) SetInvoiceDate(v time.Time)`

SetInvoiceDate sets InvoiceDate field to given value.

### HasInvoiceDate

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) HasInvoiceDate() bool`

HasInvoiceDate returns a boolean if a field has been set.

### GetPoNumber

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetPoNumber() string`

GetPoNumber returns the PoNumber field if non-nil, zero value otherwise.

### GetPoNumberOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetPoNumberOk() (*string, bool)`

GetPoNumberOk returns a tuple with the PoNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoNumber

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) SetPoNumber(v string)`

SetPoNumber sets PoNumber field to given value.

### HasPoNumber

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) HasPoNumber() bool`

HasPoNumber returns a boolean if a field has been set.

### GetDueDate

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetDueDate() time.Time`

GetDueDate returns the DueDate field if non-nil, zero value otherwise.

### GetDueDateOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetDueDateOk() (*time.Time, bool)`

GetDueDateOk returns a tuple with the DueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueDate

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) SetDueDate(v time.Time)`

SetDueDate sets DueDate field to given value.

### HasDueDate

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) HasDueDate() bool`

HasDueDate returns a boolean if a field has been set.

### GetDepartment

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetDepartment() string`

GetDepartment returns the Department field if non-nil, zero value otherwise.

### GetDepartmentOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetDepartmentOk() (*string, bool)`

GetDepartmentOk returns a tuple with the Department field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDepartment

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) SetDepartment(v string)`

SetDepartment sets Department field to given value.

### HasDepartment

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) HasDepartment() bool`

HasDepartment returns a boolean if a field has been set.

### GetExchangeRate

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetExchangeRate() float64`

GetExchangeRate returns the ExchangeRate field if non-nil, zero value otherwise.

### GetExchangeRateOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetExchangeRateOk() (*float64, bool)`

GetExchangeRateOk returns a tuple with the ExchangeRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExchangeRate

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) SetExchangeRate(v float64)`

SetExchangeRate sets ExchangeRate field to given value.

### HasExchangeRate

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) HasExchangeRate() bool`

HasExchangeRate returns a boolean if a field has been set.

### GetDebitMemo

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetDebitMemo() bool`

GetDebitMemo returns the DebitMemo field if non-nil, zero value otherwise.

### GetDebitMemoOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetDebitMemoOk() (*bool, bool)`

GetDebitMemoOk returns a tuple with the DebitMemo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDebitMemo

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) SetDebitMemo(v bool)`

SetDebitMemo sets DebitMemo field to given value.

### HasDebitMemo

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) HasDebitMemo() bool`

HasDebitMemo returns a boolean if a field has been set.

### GetGovernmentIssuedNumber

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetGovernmentIssuedNumber() string`

GetGovernmentIssuedNumber returns the GovernmentIssuedNumber field if non-nil, zero value otherwise.

### GetGovernmentIssuedNumberOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetGovernmentIssuedNumberOk() (*string, bool)`

GetGovernmentIssuedNumberOk returns a tuple with the GovernmentIssuedNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGovernmentIssuedNumber

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) SetGovernmentIssuedNumber(v string)`

SetGovernmentIssuedNumber sets GovernmentIssuedNumber field to given value.

### HasGovernmentIssuedNumber

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) HasGovernmentIssuedNumber() bool`

HasGovernmentIssuedNumber returns a boolean if a field has been set.

### GetDiscount

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetDiscount() float64`

GetDiscount returns the Discount field if non-nil, zero value otherwise.

### GetDiscountOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetDiscountOk() (*float64, bool)`

GetDiscountOk returns a tuple with the Discount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscount

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) SetDiscount(v float64)`

SetDiscount sets Discount field to given value.

### HasDiscount

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) HasDiscount() bool`

HasDiscount returns a boolean if a field has been set.

### GetInterCompany

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetInterCompany() bool`

GetInterCompany returns the InterCompany field if non-nil, zero value otherwise.

### GetInterCompanyOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetInterCompanyOk() (*bool, bool)`

GetInterCompanyOk returns a tuple with the InterCompany field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterCompany

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) SetInterCompany(v bool)`

SetInterCompany sets InterCompany field to given value.

### HasInterCompany

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) HasInterCompany() bool`

HasInterCompany returns a boolean if a field has been set.

### GetDiscountableAmount

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetDiscountableAmount() float64`

GetDiscountableAmount returns the DiscountableAmount field if non-nil, zero value otherwise.

### GetDiscountableAmountOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetDiscountableAmountOk() (*float64, bool)`

GetDiscountableAmountOk returns a tuple with the DiscountableAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscountableAmount

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) SetDiscountableAmount(v float64)`

SetDiscountableAmount sets DiscountableAmount field to given value.

### HasDiscountableAmount

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) HasDiscountableAmount() bool`

HasDiscountableAmount returns a boolean if a field has been set.

### GetTaxPointDate

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetTaxPointDate() time.Time`

GetTaxPointDate returns the TaxPointDate field if non-nil, zero value otherwise.

### GetTaxPointDateOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetTaxPointDateOk() (*time.Time, bool)`

GetTaxPointDateOk returns a tuple with the TaxPointDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxPointDate

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) SetTaxPointDate(v time.Time)`

SetTaxPointDate sets TaxPointDate field to given value.

### HasTaxPointDate

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) HasTaxPointDate() bool`

HasTaxPointDate returns a boolean if a field has been set.

### GetExpectedPayDate

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetExpectedPayDate() time.Time`

GetExpectedPayDate returns the ExpectedPayDate field if non-nil, zero value otherwise.

### GetExpectedPayDateOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetExpectedPayDateOk() (*time.Time, bool)`

GetExpectedPayDateOk returns a tuple with the ExpectedPayDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedPayDate

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) SetExpectedPayDate(v time.Time)`

SetExpectedPayDate sets ExpectedPayDate field to given value.

### HasExpectedPayDate

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) HasExpectedPayDate() bool`

HasExpectedPayDate returns a boolean if a field has been set.

### GetType

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) HasType() bool`

HasType returns a boolean if a field has been set.

### GetLines

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetLines() []LinesItem1`

GetLines returns the Lines field if non-nil, zero value otherwise.

### GetLinesOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetLinesOk() (*[]LinesItem1, bool)`

GetLinesOk returns a tuple with the Lines field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLines

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) SetLines(v []LinesItem1)`

SetLines sets Lines field to given value.

### HasLines

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) HasLines() bool`

HasLines returns a boolean if a field has been set.

### GetAccountId

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetAccountId() string`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetAccountIdOk() (*string, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) SetAccountId(v string)`

SetAccountId sets AccountId field to given value.

### HasAccountId

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) HasAccountId() bool`

HasAccountId returns a boolean if a field has been set.

### GetAccountNumber

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetAccountNumber() string`

GetAccountNumber returns the AccountNumber field if non-nil, zero value otherwise.

### GetAccountNumberOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetAccountNumberOk() (*string, bool)`

GetAccountNumberOk returns a tuple with the AccountNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumber

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) SetAccountNumber(v string)`

SetAccountNumber sets AccountNumber field to given value.

### HasAccountNumber

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) HasAccountNumber() bool`

HasAccountNumber returns a boolean if a field has been set.

### GetProjectCode

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetProjectCode() string`

GetProjectCode returns the ProjectCode field if non-nil, zero value otherwise.

### GetProjectCodeOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetProjectCodeOk() (*string, bool)`

GetProjectCodeOk returns a tuple with the ProjectCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectCode

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) SetProjectCode(v string)`

SetProjectCode sets ProjectCode field to given value.

### HasProjectCode

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) HasProjectCode() bool`

HasProjectCode returns a boolean if a field has been set.

### GetDescription

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetAccountingJobNumber

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetAccountingJobNumber() string`

GetAccountingJobNumber returns the AccountingJobNumber field if non-nil, zero value otherwise.

### GetAccountingJobNumberOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetAccountingJobNumberOk() (*string, bool)`

GetAccountingJobNumberOk returns a tuple with the AccountingJobNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountingJobNumber

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) SetAccountingJobNumber(v string)`

SetAccountingJobNumber sets AccountingJobNumber field to given value.

### HasAccountingJobNumber

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) HasAccountingJobNumber() bool`

HasAccountingJobNumber returns a boolean if a field has been set.

### GetItemTaxCode

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetItemTaxCode() string`

GetItemTaxCode returns the ItemTaxCode field if non-nil, zero value otherwise.

### GetItemTaxCodeOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetItemTaxCodeOk() (*string, bool)`

GetItemTaxCodeOk returns a tuple with the ItemTaxCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItemTaxCode

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) SetItemTaxCode(v string)`

SetItemTaxCode sets ItemTaxCode field to given value.

### HasItemTaxCode

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) HasItemTaxCode() bool`

HasItemTaxCode returns a boolean if a field has been set.

### GetTaxCodes

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetTaxCodes() []string`

GetTaxCodes returns the TaxCodes field if non-nil, zero value otherwise.

### GetTaxCodesOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetTaxCodesOk() (*[]string, bool)`

GetTaxCodesOk returns a tuple with the TaxCodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxCodes

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) SetTaxCodes(v []string)`

SetTaxCodes sets TaxCodes field to given value.

### HasTaxCodes

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) HasTaxCodes() bool`

HasTaxCodes returns a boolean if a field has been set.

### GetShipperNo

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetShipperNo() string`

GetShipperNo returns the ShipperNo field if non-nil, zero value otherwise.

### GetShipperNoOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetShipperNoOk() (*string, bool)`

GetShipperNoOk returns a tuple with the ShipperNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipperNo

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) SetShipperNo(v string)`

SetShipperNo sets ShipperNo field to given value.

### HasShipperNo

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) HasShipperNo() bool`

HasShipperNo returns a boolean if a field has been set.

### GetReferenceNo

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetReferenceNo() string`

GetReferenceNo returns the ReferenceNo field if non-nil, zero value otherwise.

### GetReferenceNoOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetReferenceNoOk() (*string, bool)`

GetReferenceNoOk returns a tuple with the ReferenceNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferenceNo

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) SetReferenceNo(v string)`

SetReferenceNo sets ReferenceNo field to given value.

### HasReferenceNo

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) HasReferenceNo() bool`

HasReferenceNo returns a boolean if a field has been set.

### GetUnitPrice

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetUnitPrice() float64`

GetUnitPrice returns the UnitPrice field if non-nil, zero value otherwise.

### GetUnitPriceOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetUnitPriceOk() (*float64, bool)`

GetUnitPriceOk returns a tuple with the UnitPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitPrice

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) SetUnitPrice(v float64)`

SetUnitPrice sets UnitPrice field to given value.

### HasUnitPrice

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) HasUnitPrice() bool`

HasUnitPrice returns a boolean if a field has been set.

### GetQuantity

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetIsTaxLine

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetIsTaxLine() bool`

GetIsTaxLine returns the IsTaxLine field if non-nil, zero value otherwise.

### GetIsTaxLineOk

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) GetIsTaxLineOk() (*bool, bool)`

GetIsTaxLineOk returns a tuple with the IsTaxLine field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsTaxLine

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) SetIsTaxLine(v bool)`

SetIsTaxLine sets IsTaxLine field to given value.

### HasIsTaxLine

`func (o *AccountsPayableInvoicesApiCreateAPInvoiceRequest) HasIsTaxLine() bool`

HasIsTaxLine returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


