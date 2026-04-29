# CustomersApiUpdateCustomerFinancialsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**MaxDaysOutstanding** | Pointer to **int32** |  | [optional] 
**CurrencyCode** | Pointer to **string** |  | [optional] 
**Terms** | Pointer to **string** | Setup Table: Terms | [optional] 
**RequestedTerms** | Pointer to **string** | Setup Table: Terms | [optional] 
**CreditLimit** | Pointer to **float64** |  | [optional] 
**SalesTaxExempt** | Pointer to **int32** |  | [optional] 
**CreditHold** | Pointer to **bool** |  | [optional] 
**CreditStatus** | Pointer to **string** | Setup Table: Credit Status | [optional] 
**CreditRating** | Pointer to **string** | Setup Table: Credit Rating | [optional] 
**CreditReviewDate** | Pointer to **time.Time** |  | [optional] 
**CreditNote** | Pointer to **string** |  | [optional] 
**InvoiceDelivery** | Pointer to **string** | Setup Table: Invoice Delivery. The default value is &amp;quot;Mail/Print Invoice&amp;quot;. | [optional] 
**SalesTaxExemptNo** | Pointer to **string** |  | [optional] 
**BillingSeparation** | Pointer to **int32** |  | [optional] 
**InvoiceLineReference** | Pointer to **string** | The customer&#39;s invoices will reference one of the following options: Part No, Release No, Customer Order No | [optional] 
**TaxIdNo** | Pointer to **string** |  | [optional] 
**RetroactivePricing** | Pointer to **bool** |  | [optional] 
**GovernmentIssuedTaxNo** | Pointer to **string** |  | [optional] 
**InvoicePo** | Pointer to **string** |  | [optional] 

## Methods

### NewCustomersApiUpdateCustomerFinancialsResponse

`func NewCustomersApiUpdateCustomerFinancialsResponse() *CustomersApiUpdateCustomerFinancialsResponse`

NewCustomersApiUpdateCustomerFinancialsResponse instantiates a new CustomersApiUpdateCustomerFinancialsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomersApiUpdateCustomerFinancialsResponseWithDefaults

`func NewCustomersApiUpdateCustomerFinancialsResponseWithDefaults() *CustomersApiUpdateCustomerFinancialsResponse`

NewCustomersApiUpdateCustomerFinancialsResponseWithDefaults instantiates a new CustomersApiUpdateCustomerFinancialsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMaxDaysOutstanding

`func (o *CustomersApiUpdateCustomerFinancialsResponse) GetMaxDaysOutstanding() int32`

GetMaxDaysOutstanding returns the MaxDaysOutstanding field if non-nil, zero value otherwise.

### GetMaxDaysOutstandingOk

`func (o *CustomersApiUpdateCustomerFinancialsResponse) GetMaxDaysOutstandingOk() (*int32, bool)`

GetMaxDaysOutstandingOk returns a tuple with the MaxDaysOutstanding field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxDaysOutstanding

`func (o *CustomersApiUpdateCustomerFinancialsResponse) SetMaxDaysOutstanding(v int32)`

SetMaxDaysOutstanding sets MaxDaysOutstanding field to given value.

### HasMaxDaysOutstanding

`func (o *CustomersApiUpdateCustomerFinancialsResponse) HasMaxDaysOutstanding() bool`

HasMaxDaysOutstanding returns a boolean if a field has been set.

### GetCurrencyCode

`func (o *CustomersApiUpdateCustomerFinancialsResponse) GetCurrencyCode() string`

GetCurrencyCode returns the CurrencyCode field if non-nil, zero value otherwise.

### GetCurrencyCodeOk

`func (o *CustomersApiUpdateCustomerFinancialsResponse) GetCurrencyCodeOk() (*string, bool)`

GetCurrencyCodeOk returns a tuple with the CurrencyCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyCode

`func (o *CustomersApiUpdateCustomerFinancialsResponse) SetCurrencyCode(v string)`

SetCurrencyCode sets CurrencyCode field to given value.

### HasCurrencyCode

`func (o *CustomersApiUpdateCustomerFinancialsResponse) HasCurrencyCode() bool`

HasCurrencyCode returns a boolean if a field has been set.

### GetTerms

`func (o *CustomersApiUpdateCustomerFinancialsResponse) GetTerms() string`

GetTerms returns the Terms field if non-nil, zero value otherwise.

### GetTermsOk

`func (o *CustomersApiUpdateCustomerFinancialsResponse) GetTermsOk() (*string, bool)`

GetTermsOk returns a tuple with the Terms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTerms

`func (o *CustomersApiUpdateCustomerFinancialsResponse) SetTerms(v string)`

SetTerms sets Terms field to given value.

### HasTerms

`func (o *CustomersApiUpdateCustomerFinancialsResponse) HasTerms() bool`

HasTerms returns a boolean if a field has been set.

### GetRequestedTerms

`func (o *CustomersApiUpdateCustomerFinancialsResponse) GetRequestedTerms() string`

GetRequestedTerms returns the RequestedTerms field if non-nil, zero value otherwise.

### GetRequestedTermsOk

`func (o *CustomersApiUpdateCustomerFinancialsResponse) GetRequestedTermsOk() (*string, bool)`

GetRequestedTermsOk returns a tuple with the RequestedTerms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestedTerms

`func (o *CustomersApiUpdateCustomerFinancialsResponse) SetRequestedTerms(v string)`

SetRequestedTerms sets RequestedTerms field to given value.

### HasRequestedTerms

`func (o *CustomersApiUpdateCustomerFinancialsResponse) HasRequestedTerms() bool`

HasRequestedTerms returns a boolean if a field has been set.

### GetCreditLimit

`func (o *CustomersApiUpdateCustomerFinancialsResponse) GetCreditLimit() float64`

GetCreditLimit returns the CreditLimit field if non-nil, zero value otherwise.

### GetCreditLimitOk

`func (o *CustomersApiUpdateCustomerFinancialsResponse) GetCreditLimitOk() (*float64, bool)`

GetCreditLimitOk returns a tuple with the CreditLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditLimit

`func (o *CustomersApiUpdateCustomerFinancialsResponse) SetCreditLimit(v float64)`

SetCreditLimit sets CreditLimit field to given value.

### HasCreditLimit

`func (o *CustomersApiUpdateCustomerFinancialsResponse) HasCreditLimit() bool`

HasCreditLimit returns a boolean if a field has been set.

### GetSalesTaxExempt

`func (o *CustomersApiUpdateCustomerFinancialsResponse) GetSalesTaxExempt() int32`

GetSalesTaxExempt returns the SalesTaxExempt field if non-nil, zero value otherwise.

### GetSalesTaxExemptOk

`func (o *CustomersApiUpdateCustomerFinancialsResponse) GetSalesTaxExemptOk() (*int32, bool)`

GetSalesTaxExemptOk returns a tuple with the SalesTaxExempt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSalesTaxExempt

`func (o *CustomersApiUpdateCustomerFinancialsResponse) SetSalesTaxExempt(v int32)`

SetSalesTaxExempt sets SalesTaxExempt field to given value.

### HasSalesTaxExempt

`func (o *CustomersApiUpdateCustomerFinancialsResponse) HasSalesTaxExempt() bool`

HasSalesTaxExempt returns a boolean if a field has been set.

### GetCreditHold

`func (o *CustomersApiUpdateCustomerFinancialsResponse) GetCreditHold() bool`

GetCreditHold returns the CreditHold field if non-nil, zero value otherwise.

### GetCreditHoldOk

`func (o *CustomersApiUpdateCustomerFinancialsResponse) GetCreditHoldOk() (*bool, bool)`

GetCreditHoldOk returns a tuple with the CreditHold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditHold

`func (o *CustomersApiUpdateCustomerFinancialsResponse) SetCreditHold(v bool)`

SetCreditHold sets CreditHold field to given value.

### HasCreditHold

`func (o *CustomersApiUpdateCustomerFinancialsResponse) HasCreditHold() bool`

HasCreditHold returns a boolean if a field has been set.

### GetCreditStatus

`func (o *CustomersApiUpdateCustomerFinancialsResponse) GetCreditStatus() string`

GetCreditStatus returns the CreditStatus field if non-nil, zero value otherwise.

### GetCreditStatusOk

`func (o *CustomersApiUpdateCustomerFinancialsResponse) GetCreditStatusOk() (*string, bool)`

GetCreditStatusOk returns a tuple with the CreditStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditStatus

`func (o *CustomersApiUpdateCustomerFinancialsResponse) SetCreditStatus(v string)`

SetCreditStatus sets CreditStatus field to given value.

### HasCreditStatus

`func (o *CustomersApiUpdateCustomerFinancialsResponse) HasCreditStatus() bool`

HasCreditStatus returns a boolean if a field has been set.

### GetCreditRating

`func (o *CustomersApiUpdateCustomerFinancialsResponse) GetCreditRating() string`

GetCreditRating returns the CreditRating field if non-nil, zero value otherwise.

### GetCreditRatingOk

`func (o *CustomersApiUpdateCustomerFinancialsResponse) GetCreditRatingOk() (*string, bool)`

GetCreditRatingOk returns a tuple with the CreditRating field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditRating

`func (o *CustomersApiUpdateCustomerFinancialsResponse) SetCreditRating(v string)`

SetCreditRating sets CreditRating field to given value.

### HasCreditRating

`func (o *CustomersApiUpdateCustomerFinancialsResponse) HasCreditRating() bool`

HasCreditRating returns a boolean if a field has been set.

### GetCreditReviewDate

`func (o *CustomersApiUpdateCustomerFinancialsResponse) GetCreditReviewDate() time.Time`

GetCreditReviewDate returns the CreditReviewDate field if non-nil, zero value otherwise.

### GetCreditReviewDateOk

`func (o *CustomersApiUpdateCustomerFinancialsResponse) GetCreditReviewDateOk() (*time.Time, bool)`

GetCreditReviewDateOk returns a tuple with the CreditReviewDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditReviewDate

`func (o *CustomersApiUpdateCustomerFinancialsResponse) SetCreditReviewDate(v time.Time)`

SetCreditReviewDate sets CreditReviewDate field to given value.

### HasCreditReviewDate

`func (o *CustomersApiUpdateCustomerFinancialsResponse) HasCreditReviewDate() bool`

HasCreditReviewDate returns a boolean if a field has been set.

### GetCreditNote

`func (o *CustomersApiUpdateCustomerFinancialsResponse) GetCreditNote() string`

GetCreditNote returns the CreditNote field if non-nil, zero value otherwise.

### GetCreditNoteOk

`func (o *CustomersApiUpdateCustomerFinancialsResponse) GetCreditNoteOk() (*string, bool)`

GetCreditNoteOk returns a tuple with the CreditNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditNote

`func (o *CustomersApiUpdateCustomerFinancialsResponse) SetCreditNote(v string)`

SetCreditNote sets CreditNote field to given value.

### HasCreditNote

`func (o *CustomersApiUpdateCustomerFinancialsResponse) HasCreditNote() bool`

HasCreditNote returns a boolean if a field has been set.

### GetInvoiceDelivery

`func (o *CustomersApiUpdateCustomerFinancialsResponse) GetInvoiceDelivery() string`

GetInvoiceDelivery returns the InvoiceDelivery field if non-nil, zero value otherwise.

### GetInvoiceDeliveryOk

`func (o *CustomersApiUpdateCustomerFinancialsResponse) GetInvoiceDeliveryOk() (*string, bool)`

GetInvoiceDeliveryOk returns a tuple with the InvoiceDelivery field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceDelivery

`func (o *CustomersApiUpdateCustomerFinancialsResponse) SetInvoiceDelivery(v string)`

SetInvoiceDelivery sets InvoiceDelivery field to given value.

### HasInvoiceDelivery

`func (o *CustomersApiUpdateCustomerFinancialsResponse) HasInvoiceDelivery() bool`

HasInvoiceDelivery returns a boolean if a field has been set.

### GetSalesTaxExemptNo

`func (o *CustomersApiUpdateCustomerFinancialsResponse) GetSalesTaxExemptNo() string`

GetSalesTaxExemptNo returns the SalesTaxExemptNo field if non-nil, zero value otherwise.

### GetSalesTaxExemptNoOk

`func (o *CustomersApiUpdateCustomerFinancialsResponse) GetSalesTaxExemptNoOk() (*string, bool)`

GetSalesTaxExemptNoOk returns a tuple with the SalesTaxExemptNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSalesTaxExemptNo

`func (o *CustomersApiUpdateCustomerFinancialsResponse) SetSalesTaxExemptNo(v string)`

SetSalesTaxExemptNo sets SalesTaxExemptNo field to given value.

### HasSalesTaxExemptNo

`func (o *CustomersApiUpdateCustomerFinancialsResponse) HasSalesTaxExemptNo() bool`

HasSalesTaxExemptNo returns a boolean if a field has been set.

### GetBillingSeparation

`func (o *CustomersApiUpdateCustomerFinancialsResponse) GetBillingSeparation() int32`

GetBillingSeparation returns the BillingSeparation field if non-nil, zero value otherwise.

### GetBillingSeparationOk

`func (o *CustomersApiUpdateCustomerFinancialsResponse) GetBillingSeparationOk() (*int32, bool)`

GetBillingSeparationOk returns a tuple with the BillingSeparation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingSeparation

`func (o *CustomersApiUpdateCustomerFinancialsResponse) SetBillingSeparation(v int32)`

SetBillingSeparation sets BillingSeparation field to given value.

### HasBillingSeparation

`func (o *CustomersApiUpdateCustomerFinancialsResponse) HasBillingSeparation() bool`

HasBillingSeparation returns a boolean if a field has been set.

### GetInvoiceLineReference

`func (o *CustomersApiUpdateCustomerFinancialsResponse) GetInvoiceLineReference() string`

GetInvoiceLineReference returns the InvoiceLineReference field if non-nil, zero value otherwise.

### GetInvoiceLineReferenceOk

`func (o *CustomersApiUpdateCustomerFinancialsResponse) GetInvoiceLineReferenceOk() (*string, bool)`

GetInvoiceLineReferenceOk returns a tuple with the InvoiceLineReference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceLineReference

`func (o *CustomersApiUpdateCustomerFinancialsResponse) SetInvoiceLineReference(v string)`

SetInvoiceLineReference sets InvoiceLineReference field to given value.

### HasInvoiceLineReference

`func (o *CustomersApiUpdateCustomerFinancialsResponse) HasInvoiceLineReference() bool`

HasInvoiceLineReference returns a boolean if a field has been set.

### GetTaxIdNo

`func (o *CustomersApiUpdateCustomerFinancialsResponse) GetTaxIdNo() string`

GetTaxIdNo returns the TaxIdNo field if non-nil, zero value otherwise.

### GetTaxIdNoOk

`func (o *CustomersApiUpdateCustomerFinancialsResponse) GetTaxIdNoOk() (*string, bool)`

GetTaxIdNoOk returns a tuple with the TaxIdNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxIdNo

`func (o *CustomersApiUpdateCustomerFinancialsResponse) SetTaxIdNo(v string)`

SetTaxIdNo sets TaxIdNo field to given value.

### HasTaxIdNo

`func (o *CustomersApiUpdateCustomerFinancialsResponse) HasTaxIdNo() bool`

HasTaxIdNo returns a boolean if a field has been set.

### GetRetroactivePricing

`func (o *CustomersApiUpdateCustomerFinancialsResponse) GetRetroactivePricing() bool`

GetRetroactivePricing returns the RetroactivePricing field if non-nil, zero value otherwise.

### GetRetroactivePricingOk

`func (o *CustomersApiUpdateCustomerFinancialsResponse) GetRetroactivePricingOk() (*bool, bool)`

GetRetroactivePricingOk returns a tuple with the RetroactivePricing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRetroactivePricing

`func (o *CustomersApiUpdateCustomerFinancialsResponse) SetRetroactivePricing(v bool)`

SetRetroactivePricing sets RetroactivePricing field to given value.

### HasRetroactivePricing

`func (o *CustomersApiUpdateCustomerFinancialsResponse) HasRetroactivePricing() bool`

HasRetroactivePricing returns a boolean if a field has been set.

### GetGovernmentIssuedTaxNo

`func (o *CustomersApiUpdateCustomerFinancialsResponse) GetGovernmentIssuedTaxNo() string`

GetGovernmentIssuedTaxNo returns the GovernmentIssuedTaxNo field if non-nil, zero value otherwise.

### GetGovernmentIssuedTaxNoOk

`func (o *CustomersApiUpdateCustomerFinancialsResponse) GetGovernmentIssuedTaxNoOk() (*string, bool)`

GetGovernmentIssuedTaxNoOk returns a tuple with the GovernmentIssuedTaxNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGovernmentIssuedTaxNo

`func (o *CustomersApiUpdateCustomerFinancialsResponse) SetGovernmentIssuedTaxNo(v string)`

SetGovernmentIssuedTaxNo sets GovernmentIssuedTaxNo field to given value.

### HasGovernmentIssuedTaxNo

`func (o *CustomersApiUpdateCustomerFinancialsResponse) HasGovernmentIssuedTaxNo() bool`

HasGovernmentIssuedTaxNo returns a boolean if a field has been set.

### GetInvoicePo

`func (o *CustomersApiUpdateCustomerFinancialsResponse) GetInvoicePo() string`

GetInvoicePo returns the InvoicePo field if non-nil, zero value otherwise.

### GetInvoicePoOk

`func (o *CustomersApiUpdateCustomerFinancialsResponse) GetInvoicePoOk() (*string, bool)`

GetInvoicePoOk returns a tuple with the InvoicePo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoicePo

`func (o *CustomersApiUpdateCustomerFinancialsResponse) SetInvoicePo(v string)`

SetInvoicePo sets InvoicePo field to given value.

### HasInvoicePo

`func (o *CustomersApiUpdateCustomerFinancialsResponse) HasInvoicePo() bool`

HasInvoicePo returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


