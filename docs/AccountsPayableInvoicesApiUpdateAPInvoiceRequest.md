# AccountsPayableInvoicesApiUpdateAPInvoiceRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**InvoiceNumber** | Pointer to **string** | The AP invoice number. | [optional] 
**SupplierId** | Pointer to **string** | The AP invoice ID. | [optional] 
**SupplierCode** | Pointer to **string** | The AP invoice supplier code, typically an abbreviated name for the supplier. | [optional] 
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
**InvoiceDate** | Pointer to **time.Time** | The date an AP invoice was created. | [optional] 
**PoNumber** | Pointer to **string** | The AP invoice purchase order number. | [optional] 
**DueDate** | Pointer to **time.Time** | The AP invoice due date. | [optional] 
**Department** | Pointer to **string** | The AP invoice department code. | [optional] 
**ExchangeRate** | Pointer to **float64** | The AP invoice exchange rate. | [optional] 
**GovernmentIssuedNumber** | Pointer to **string** | The AP invoice government issued number. | [optional] 
**Discount** | Pointer to **float64** | The AP invoice discount. | [optional] 
**InterCompany** | Pointer to **bool** | The AP invoice intercompany tax. | [optional] 
**DiscountableAmount** | Pointer to **float64** | The AP invoice discountable amount. | [optional] 
**TaxPointDate** | Pointer to **time.Time** | The AP invoice tax point date. | [optional] 
**ExpectedPayDate** | Pointer to **time.Time** | The AP invoice expected pay date. | [optional] 
**Type** | Pointer to **string** | The AP invoice type. | [optional] 
**CheckNos** | Pointer to **string** | The AP invoice check numbers. | [optional] 
**Lines** | Pointer to [**[]LinesItem2**](LinesItem2.md) | A list of AP lines. | [optional] 
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

### NewAccountsPayableInvoicesApiUpdateAPInvoiceRequest

`func NewAccountsPayableInvoicesApiUpdateAPInvoiceRequest() *AccountsPayableInvoicesApiUpdateAPInvoiceRequest`

NewAccountsPayableInvoicesApiUpdateAPInvoiceRequest instantiates a new AccountsPayableInvoicesApiUpdateAPInvoiceRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccountsPayableInvoicesApiUpdateAPInvoiceRequestWithDefaults

`func NewAccountsPayableInvoicesApiUpdateAPInvoiceRequestWithDefaults() *AccountsPayableInvoicesApiUpdateAPInvoiceRequest`

NewAccountsPayableInvoicesApiUpdateAPInvoiceRequestWithDefaults instantiates a new AccountsPayableInvoicesApiUpdateAPInvoiceRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetInvoiceNumber

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetInvoiceNumber() string`

GetInvoiceNumber returns the InvoiceNumber field if non-nil, zero value otherwise.

### GetInvoiceNumberOk

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetInvoiceNumberOk() (*string, bool)`

GetInvoiceNumberOk returns a tuple with the InvoiceNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceNumber

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) SetInvoiceNumber(v string)`

SetInvoiceNumber sets InvoiceNumber field to given value.

### HasInvoiceNumber

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) HasInvoiceNumber() bool`

HasInvoiceNumber returns a boolean if a field has been set.

### GetSupplierId

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetSupplierId() string`

GetSupplierId returns the SupplierId field if non-nil, zero value otherwise.

### GetSupplierIdOk

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetSupplierIdOk() (*string, bool)`

GetSupplierIdOk returns a tuple with the SupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierId

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) SetSupplierId(v string)`

SetSupplierId sets SupplierId field to given value.

### HasSupplierId

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) HasSupplierId() bool`

HasSupplierId returns a boolean if a field has been set.

### GetSupplierCode

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetSupplierCode() string`

GetSupplierCode returns the SupplierCode field if non-nil, zero value otherwise.

### GetSupplierCodeOk

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetSupplierCodeOk() (*string, bool)`

GetSupplierCodeOk returns a tuple with the SupplierCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierCode

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) SetSupplierCode(v string)`

SetSupplierCode sets SupplierCode field to given value.

### HasSupplierCode

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) HasSupplierCode() bool`

HasSupplierCode returns a boolean if a field has been set.

### GetSupplierAddressCode

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetSupplierAddressCode() string`

GetSupplierAddressCode returns the SupplierAddressCode field if non-nil, zero value otherwise.

### GetSupplierAddressCodeOk

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetSupplierAddressCodeOk() (*string, bool)`

GetSupplierAddressCodeOk returns a tuple with the SupplierAddressCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierAddressCode

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) SetSupplierAddressCode(v string)`

SetSupplierAddressCode sets SupplierAddressCode field to given value.

### HasSupplierAddressCode

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) HasSupplierAddressCode() bool`

HasSupplierAddressCode returns a boolean if a field has been set.

### GetTerms

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetTerms() string`

GetTerms returns the Terms field if non-nil, zero value otherwise.

### GetTermsOk

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetTermsOk() (*string, bool)`

GetTermsOk returns a tuple with the Terms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTerms

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) SetTerms(v string)`

SetTerms sets Terms field to given value.

### HasTerms

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) HasTerms() bool`

HasTerms returns a boolean if a field has been set.

### GetPeriodDisplay

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetPeriodDisplay() string`

GetPeriodDisplay returns the PeriodDisplay field if non-nil, zero value otherwise.

### GetPeriodDisplayOk

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetPeriodDisplayOk() (*string, bool)`

GetPeriodDisplayOk returns a tuple with the PeriodDisplay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriodDisplay

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) SetPeriodDisplay(v string)`

SetPeriodDisplay sets PeriodDisplay field to given value.

### HasPeriodDisplay

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) HasPeriodDisplay() bool`

HasPeriodDisplay returns a boolean if a field has been set.

### GetCurrencyCode

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetCurrencyCode() string`

GetCurrencyCode returns the CurrencyCode field if non-nil, zero value otherwise.

### GetCurrencyCodeOk

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetCurrencyCodeOk() (*string, bool)`

GetCurrencyCodeOk returns a tuple with the CurrencyCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyCode

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) SetCurrencyCode(v string)`

SetCurrencyCode sets CurrencyCode field to given value.

### HasCurrencyCode

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) HasCurrencyCode() bool`

HasCurrencyCode returns a boolean if a field has been set.

### GetStatus

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetDiscountDueDate

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetDiscountDueDate() time.Time`

GetDiscountDueDate returns the DiscountDueDate field if non-nil, zero value otherwise.

### GetDiscountDueDateOk

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetDiscountDueDateOk() (*time.Time, bool)`

GetDiscountDueDateOk returns a tuple with the DiscountDueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscountDueDate

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) SetDiscountDueDate(v time.Time)`

SetDiscountDueDate sets DiscountDueDate field to given value.

### HasDiscountDueDate

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) HasDiscountDueDate() bool`

HasDiscountDueDate returns a boolean if a field has been set.

### GetPoId

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetPoId() string`

GetPoId returns the PoId field if non-nil, zero value otherwise.

### GetPoIdOk

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetPoIdOk() (*string, bool)`

GetPoIdOk returns a tuple with the PoId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoId

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) SetPoId(v string)`

SetPoId sets PoId field to given value.

### HasPoId

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) HasPoId() bool`

HasPoId returns a boolean if a field has been set.

### GetNote

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetCheckNote

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetCheckNote() string`

GetCheckNote returns the CheckNote field if non-nil, zero value otherwise.

### GetCheckNoteOk

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetCheckNoteOk() (*string, bool)`

GetCheckNoteOk returns a tuple with the CheckNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckNote

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) SetCheckNote(v string)`

SetCheckNote sets CheckNote field to given value.

### HasCheckNote

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) HasCheckNote() bool`

HasCheckNote returns a boolean if a field has been set.

### GetBuildingCode

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetBuildingCode() string`

GetBuildingCode returns the BuildingCode field if non-nil, zero value otherwise.

### GetBuildingCodeOk

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetBuildingCodeOk() (*string, bool)`

GetBuildingCodeOk returns a tuple with the BuildingCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildingCode

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) SetBuildingCode(v string)`

SetBuildingCode sets BuildingCode field to given value.

### HasBuildingCode

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) HasBuildingCode() bool`

HasBuildingCode returns a boolean if a field has been set.

### GetInvoiceDate

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetInvoiceDate() time.Time`

GetInvoiceDate returns the InvoiceDate field if non-nil, zero value otherwise.

### GetInvoiceDateOk

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetInvoiceDateOk() (*time.Time, bool)`

GetInvoiceDateOk returns a tuple with the InvoiceDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceDate

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) SetInvoiceDate(v time.Time)`

SetInvoiceDate sets InvoiceDate field to given value.

### HasInvoiceDate

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) HasInvoiceDate() bool`

HasInvoiceDate returns a boolean if a field has been set.

### GetPoNumber

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetPoNumber() string`

GetPoNumber returns the PoNumber field if non-nil, zero value otherwise.

### GetPoNumberOk

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetPoNumberOk() (*string, bool)`

GetPoNumberOk returns a tuple with the PoNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoNumber

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) SetPoNumber(v string)`

SetPoNumber sets PoNumber field to given value.

### HasPoNumber

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) HasPoNumber() bool`

HasPoNumber returns a boolean if a field has been set.

### GetDueDate

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetDueDate() time.Time`

GetDueDate returns the DueDate field if non-nil, zero value otherwise.

### GetDueDateOk

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetDueDateOk() (*time.Time, bool)`

GetDueDateOk returns a tuple with the DueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueDate

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) SetDueDate(v time.Time)`

SetDueDate sets DueDate field to given value.

### HasDueDate

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) HasDueDate() bool`

HasDueDate returns a boolean if a field has been set.

### GetDepartment

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetDepartment() string`

GetDepartment returns the Department field if non-nil, zero value otherwise.

### GetDepartmentOk

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetDepartmentOk() (*string, bool)`

GetDepartmentOk returns a tuple with the Department field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDepartment

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) SetDepartment(v string)`

SetDepartment sets Department field to given value.

### HasDepartment

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) HasDepartment() bool`

HasDepartment returns a boolean if a field has been set.

### GetExchangeRate

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetExchangeRate() float64`

GetExchangeRate returns the ExchangeRate field if non-nil, zero value otherwise.

### GetExchangeRateOk

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetExchangeRateOk() (*float64, bool)`

GetExchangeRateOk returns a tuple with the ExchangeRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExchangeRate

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) SetExchangeRate(v float64)`

SetExchangeRate sets ExchangeRate field to given value.

### HasExchangeRate

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) HasExchangeRate() bool`

HasExchangeRate returns a boolean if a field has been set.

### GetGovernmentIssuedNumber

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetGovernmentIssuedNumber() string`

GetGovernmentIssuedNumber returns the GovernmentIssuedNumber field if non-nil, zero value otherwise.

### GetGovernmentIssuedNumberOk

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetGovernmentIssuedNumberOk() (*string, bool)`

GetGovernmentIssuedNumberOk returns a tuple with the GovernmentIssuedNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGovernmentIssuedNumber

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) SetGovernmentIssuedNumber(v string)`

SetGovernmentIssuedNumber sets GovernmentIssuedNumber field to given value.

### HasGovernmentIssuedNumber

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) HasGovernmentIssuedNumber() bool`

HasGovernmentIssuedNumber returns a boolean if a field has been set.

### GetDiscount

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetDiscount() float64`

GetDiscount returns the Discount field if non-nil, zero value otherwise.

### GetDiscountOk

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetDiscountOk() (*float64, bool)`

GetDiscountOk returns a tuple with the Discount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscount

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) SetDiscount(v float64)`

SetDiscount sets Discount field to given value.

### HasDiscount

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) HasDiscount() bool`

HasDiscount returns a boolean if a field has been set.

### GetInterCompany

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetInterCompany() bool`

GetInterCompany returns the InterCompany field if non-nil, zero value otherwise.

### GetInterCompanyOk

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetInterCompanyOk() (*bool, bool)`

GetInterCompanyOk returns a tuple with the InterCompany field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterCompany

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) SetInterCompany(v bool)`

SetInterCompany sets InterCompany field to given value.

### HasInterCompany

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) HasInterCompany() bool`

HasInterCompany returns a boolean if a field has been set.

### GetDiscountableAmount

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetDiscountableAmount() float64`

GetDiscountableAmount returns the DiscountableAmount field if non-nil, zero value otherwise.

### GetDiscountableAmountOk

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetDiscountableAmountOk() (*float64, bool)`

GetDiscountableAmountOk returns a tuple with the DiscountableAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscountableAmount

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) SetDiscountableAmount(v float64)`

SetDiscountableAmount sets DiscountableAmount field to given value.

### HasDiscountableAmount

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) HasDiscountableAmount() bool`

HasDiscountableAmount returns a boolean if a field has been set.

### GetTaxPointDate

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetTaxPointDate() time.Time`

GetTaxPointDate returns the TaxPointDate field if non-nil, zero value otherwise.

### GetTaxPointDateOk

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetTaxPointDateOk() (*time.Time, bool)`

GetTaxPointDateOk returns a tuple with the TaxPointDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxPointDate

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) SetTaxPointDate(v time.Time)`

SetTaxPointDate sets TaxPointDate field to given value.

### HasTaxPointDate

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) HasTaxPointDate() bool`

HasTaxPointDate returns a boolean if a field has been set.

### GetExpectedPayDate

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetExpectedPayDate() time.Time`

GetExpectedPayDate returns the ExpectedPayDate field if non-nil, zero value otherwise.

### GetExpectedPayDateOk

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetExpectedPayDateOk() (*time.Time, bool)`

GetExpectedPayDateOk returns a tuple with the ExpectedPayDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedPayDate

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) SetExpectedPayDate(v time.Time)`

SetExpectedPayDate sets ExpectedPayDate field to given value.

### HasExpectedPayDate

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) HasExpectedPayDate() bool`

HasExpectedPayDate returns a boolean if a field has been set.

### GetType

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) HasType() bool`

HasType returns a boolean if a field has been set.

### GetCheckNos

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetCheckNos() string`

GetCheckNos returns the CheckNos field if non-nil, zero value otherwise.

### GetCheckNosOk

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetCheckNosOk() (*string, bool)`

GetCheckNosOk returns a tuple with the CheckNos field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckNos

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) SetCheckNos(v string)`

SetCheckNos sets CheckNos field to given value.

### HasCheckNos

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) HasCheckNos() bool`

HasCheckNos returns a boolean if a field has been set.

### GetLines

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetLines() []LinesItem2`

GetLines returns the Lines field if non-nil, zero value otherwise.

### GetLinesOk

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetLinesOk() (*[]LinesItem2, bool)`

GetLinesOk returns a tuple with the Lines field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLines

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) SetLines(v []LinesItem2)`

SetLines sets Lines field to given value.

### HasLines

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) HasLines() bool`

HasLines returns a boolean if a field has been set.

### GetLineId

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetLineId() string`

GetLineId returns the LineId field if non-nil, zero value otherwise.

### GetLineIdOk

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetLineIdOk() (*string, bool)`

GetLineIdOk returns a tuple with the LineId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineId

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) SetLineId(v string)`

SetLineId sets LineId field to given value.

### HasLineId

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) HasLineId() bool`

HasLineId returns a boolean if a field has been set.

### GetAccountId

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetAccountId() string`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetAccountIdOk() (*string, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) SetAccountId(v string)`

SetAccountId sets AccountId field to given value.

### HasAccountId

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) HasAccountId() bool`

HasAccountId returns a boolean if a field has been set.

### GetAccountNumber

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetAccountNumber() string`

GetAccountNumber returns the AccountNumber field if non-nil, zero value otherwise.

### GetAccountNumberOk

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetAccountNumberOk() (*string, bool)`

GetAccountNumberOk returns a tuple with the AccountNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumber

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) SetAccountNumber(v string)`

SetAccountNumber sets AccountNumber field to given value.

### HasAccountNumber

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) HasAccountNumber() bool`

HasAccountNumber returns a boolean if a field has been set.

### GetProjectCode

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetProjectCode() string`

GetProjectCode returns the ProjectCode field if non-nil, zero value otherwise.

### GetProjectCodeOk

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetProjectCodeOk() (*string, bool)`

GetProjectCodeOk returns a tuple with the ProjectCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectCode

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) SetProjectCode(v string)`

SetProjectCode sets ProjectCode field to given value.

### HasProjectCode

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) HasProjectCode() bool`

HasProjectCode returns a boolean if a field has been set.

### GetDescription

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetAccountingJobNumber

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetAccountingJobNumber() string`

GetAccountingJobNumber returns the AccountingJobNumber field if non-nil, zero value otherwise.

### GetAccountingJobNumberOk

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetAccountingJobNumberOk() (*string, bool)`

GetAccountingJobNumberOk returns a tuple with the AccountingJobNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountingJobNumber

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) SetAccountingJobNumber(v string)`

SetAccountingJobNumber sets AccountingJobNumber field to given value.

### HasAccountingJobNumber

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) HasAccountingJobNumber() bool`

HasAccountingJobNumber returns a boolean if a field has been set.

### GetItemTaxCode

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetItemTaxCode() string`

GetItemTaxCode returns the ItemTaxCode field if non-nil, zero value otherwise.

### GetItemTaxCodeOk

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetItemTaxCodeOk() (*string, bool)`

GetItemTaxCodeOk returns a tuple with the ItemTaxCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItemTaxCode

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) SetItemTaxCode(v string)`

SetItemTaxCode sets ItemTaxCode field to given value.

### HasItemTaxCode

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) HasItemTaxCode() bool`

HasItemTaxCode returns a boolean if a field has been set.

### GetTaxCodes

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetTaxCodes() []string`

GetTaxCodes returns the TaxCodes field if non-nil, zero value otherwise.

### GetTaxCodesOk

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetTaxCodesOk() (*[]string, bool)`

GetTaxCodesOk returns a tuple with the TaxCodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxCodes

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) SetTaxCodes(v []string)`

SetTaxCodes sets TaxCodes field to given value.

### HasTaxCodes

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) HasTaxCodes() bool`

HasTaxCodes returns a boolean if a field has been set.

### GetShipperNo

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetShipperNo() string`

GetShipperNo returns the ShipperNo field if non-nil, zero value otherwise.

### GetShipperNoOk

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetShipperNoOk() (*string, bool)`

GetShipperNoOk returns a tuple with the ShipperNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipperNo

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) SetShipperNo(v string)`

SetShipperNo sets ShipperNo field to given value.

### HasShipperNo

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) HasShipperNo() bool`

HasShipperNo returns a boolean if a field has been set.

### GetReferenceNo

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetReferenceNo() string`

GetReferenceNo returns the ReferenceNo field if non-nil, zero value otherwise.

### GetReferenceNoOk

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetReferenceNoOk() (*string, bool)`

GetReferenceNoOk returns a tuple with the ReferenceNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferenceNo

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) SetReferenceNo(v string)`

SetReferenceNo sets ReferenceNo field to given value.

### HasReferenceNo

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) HasReferenceNo() bool`

HasReferenceNo returns a boolean if a field has been set.

### GetUnitPrice

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetUnitPrice() float64`

GetUnitPrice returns the UnitPrice field if non-nil, zero value otherwise.

### GetUnitPriceOk

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetUnitPriceOk() (*float64, bool)`

GetUnitPriceOk returns a tuple with the UnitPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitPrice

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) SetUnitPrice(v float64)`

SetUnitPrice sets UnitPrice field to given value.

### HasUnitPrice

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) HasUnitPrice() bool`

HasUnitPrice returns a boolean if a field has been set.

### GetQuantity

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetIsTaxLine

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetIsTaxLine() bool`

GetIsTaxLine returns the IsTaxLine field if non-nil, zero value otherwise.

### GetIsTaxLineOk

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) GetIsTaxLineOk() (*bool, bool)`

GetIsTaxLineOk returns a tuple with the IsTaxLine field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsTaxLine

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) SetIsTaxLine(v bool)`

SetIsTaxLine sets IsTaxLine field to given value.

### HasIsTaxLine

`func (o *AccountsPayableInvoicesApiUpdateAPInvoiceRequest) HasIsTaxLine() bool`

HasIsTaxLine returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


