# CustomersApiUpdateCustomerFinancialsRequest

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
**InvoicePo** | Pointer to **string** | The invoice PO will reference of the following options: Release No or Customer Release No. | [optional] 

## Methods

### NewCustomersApiUpdateCustomerFinancialsRequest

`func NewCustomersApiUpdateCustomerFinancialsRequest() *CustomersApiUpdateCustomerFinancialsRequest`

NewCustomersApiUpdateCustomerFinancialsRequest instantiates a new CustomersApiUpdateCustomerFinancialsRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomersApiUpdateCustomerFinancialsRequestWithDefaults

`func NewCustomersApiUpdateCustomerFinancialsRequestWithDefaults() *CustomersApiUpdateCustomerFinancialsRequest`

NewCustomersApiUpdateCustomerFinancialsRequestWithDefaults instantiates a new CustomersApiUpdateCustomerFinancialsRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMaxDaysOutstanding

`func (o *CustomersApiUpdateCustomerFinancialsRequest) GetMaxDaysOutstanding() int32`

GetMaxDaysOutstanding returns the MaxDaysOutstanding field if non-nil, zero value otherwise.

### GetMaxDaysOutstandingOk

`func (o *CustomersApiUpdateCustomerFinancialsRequest) GetMaxDaysOutstandingOk() (*int32, bool)`

GetMaxDaysOutstandingOk returns a tuple with the MaxDaysOutstanding field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxDaysOutstanding

`func (o *CustomersApiUpdateCustomerFinancialsRequest) SetMaxDaysOutstanding(v int32)`

SetMaxDaysOutstanding sets MaxDaysOutstanding field to given value.

### HasMaxDaysOutstanding

`func (o *CustomersApiUpdateCustomerFinancialsRequest) HasMaxDaysOutstanding() bool`

HasMaxDaysOutstanding returns a boolean if a field has been set.

### GetCurrencyCode

`func (o *CustomersApiUpdateCustomerFinancialsRequest) GetCurrencyCode() string`

GetCurrencyCode returns the CurrencyCode field if non-nil, zero value otherwise.

### GetCurrencyCodeOk

`func (o *CustomersApiUpdateCustomerFinancialsRequest) GetCurrencyCodeOk() (*string, bool)`

GetCurrencyCodeOk returns a tuple with the CurrencyCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyCode

`func (o *CustomersApiUpdateCustomerFinancialsRequest) SetCurrencyCode(v string)`

SetCurrencyCode sets CurrencyCode field to given value.

### HasCurrencyCode

`func (o *CustomersApiUpdateCustomerFinancialsRequest) HasCurrencyCode() bool`

HasCurrencyCode returns a boolean if a field has been set.

### GetTerms

`func (o *CustomersApiUpdateCustomerFinancialsRequest) GetTerms() string`

GetTerms returns the Terms field if non-nil, zero value otherwise.

### GetTermsOk

`func (o *CustomersApiUpdateCustomerFinancialsRequest) GetTermsOk() (*string, bool)`

GetTermsOk returns a tuple with the Terms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTerms

`func (o *CustomersApiUpdateCustomerFinancialsRequest) SetTerms(v string)`

SetTerms sets Terms field to given value.

### HasTerms

`func (o *CustomersApiUpdateCustomerFinancialsRequest) HasTerms() bool`

HasTerms returns a boolean if a field has been set.

### GetRequestedTerms

`func (o *CustomersApiUpdateCustomerFinancialsRequest) GetRequestedTerms() string`

GetRequestedTerms returns the RequestedTerms field if non-nil, zero value otherwise.

### GetRequestedTermsOk

`func (o *CustomersApiUpdateCustomerFinancialsRequest) GetRequestedTermsOk() (*string, bool)`

GetRequestedTermsOk returns a tuple with the RequestedTerms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestedTerms

`func (o *CustomersApiUpdateCustomerFinancialsRequest) SetRequestedTerms(v string)`

SetRequestedTerms sets RequestedTerms field to given value.

### HasRequestedTerms

`func (o *CustomersApiUpdateCustomerFinancialsRequest) HasRequestedTerms() bool`

HasRequestedTerms returns a boolean if a field has been set.

### GetCreditLimit

`func (o *CustomersApiUpdateCustomerFinancialsRequest) GetCreditLimit() float64`

GetCreditLimit returns the CreditLimit field if non-nil, zero value otherwise.

### GetCreditLimitOk

`func (o *CustomersApiUpdateCustomerFinancialsRequest) GetCreditLimitOk() (*float64, bool)`

GetCreditLimitOk returns a tuple with the CreditLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditLimit

`func (o *CustomersApiUpdateCustomerFinancialsRequest) SetCreditLimit(v float64)`

SetCreditLimit sets CreditLimit field to given value.

### HasCreditLimit

`func (o *CustomersApiUpdateCustomerFinancialsRequest) HasCreditLimit() bool`

HasCreditLimit returns a boolean if a field has been set.

### GetSalesTaxExempt

`func (o *CustomersApiUpdateCustomerFinancialsRequest) GetSalesTaxExempt() int32`

GetSalesTaxExempt returns the SalesTaxExempt field if non-nil, zero value otherwise.

### GetSalesTaxExemptOk

`func (o *CustomersApiUpdateCustomerFinancialsRequest) GetSalesTaxExemptOk() (*int32, bool)`

GetSalesTaxExemptOk returns a tuple with the SalesTaxExempt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSalesTaxExempt

`func (o *CustomersApiUpdateCustomerFinancialsRequest) SetSalesTaxExempt(v int32)`

SetSalesTaxExempt sets SalesTaxExempt field to given value.

### HasSalesTaxExempt

`func (o *CustomersApiUpdateCustomerFinancialsRequest) HasSalesTaxExempt() bool`

HasSalesTaxExempt returns a boolean if a field has been set.

### GetCreditHold

`func (o *CustomersApiUpdateCustomerFinancialsRequest) GetCreditHold() bool`

GetCreditHold returns the CreditHold field if non-nil, zero value otherwise.

### GetCreditHoldOk

`func (o *CustomersApiUpdateCustomerFinancialsRequest) GetCreditHoldOk() (*bool, bool)`

GetCreditHoldOk returns a tuple with the CreditHold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditHold

`func (o *CustomersApiUpdateCustomerFinancialsRequest) SetCreditHold(v bool)`

SetCreditHold sets CreditHold field to given value.

### HasCreditHold

`func (o *CustomersApiUpdateCustomerFinancialsRequest) HasCreditHold() bool`

HasCreditHold returns a boolean if a field has been set.

### GetCreditStatus

`func (o *CustomersApiUpdateCustomerFinancialsRequest) GetCreditStatus() string`

GetCreditStatus returns the CreditStatus field if non-nil, zero value otherwise.

### GetCreditStatusOk

`func (o *CustomersApiUpdateCustomerFinancialsRequest) GetCreditStatusOk() (*string, bool)`

GetCreditStatusOk returns a tuple with the CreditStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditStatus

`func (o *CustomersApiUpdateCustomerFinancialsRequest) SetCreditStatus(v string)`

SetCreditStatus sets CreditStatus field to given value.

### HasCreditStatus

`func (o *CustomersApiUpdateCustomerFinancialsRequest) HasCreditStatus() bool`

HasCreditStatus returns a boolean if a field has been set.

### GetCreditRating

`func (o *CustomersApiUpdateCustomerFinancialsRequest) GetCreditRating() string`

GetCreditRating returns the CreditRating field if non-nil, zero value otherwise.

### GetCreditRatingOk

`func (o *CustomersApiUpdateCustomerFinancialsRequest) GetCreditRatingOk() (*string, bool)`

GetCreditRatingOk returns a tuple with the CreditRating field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditRating

`func (o *CustomersApiUpdateCustomerFinancialsRequest) SetCreditRating(v string)`

SetCreditRating sets CreditRating field to given value.

### HasCreditRating

`func (o *CustomersApiUpdateCustomerFinancialsRequest) HasCreditRating() bool`

HasCreditRating returns a boolean if a field has been set.

### GetCreditReviewDate

`func (o *CustomersApiUpdateCustomerFinancialsRequest) GetCreditReviewDate() time.Time`

GetCreditReviewDate returns the CreditReviewDate field if non-nil, zero value otherwise.

### GetCreditReviewDateOk

`func (o *CustomersApiUpdateCustomerFinancialsRequest) GetCreditReviewDateOk() (*time.Time, bool)`

GetCreditReviewDateOk returns a tuple with the CreditReviewDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditReviewDate

`func (o *CustomersApiUpdateCustomerFinancialsRequest) SetCreditReviewDate(v time.Time)`

SetCreditReviewDate sets CreditReviewDate field to given value.

### HasCreditReviewDate

`func (o *CustomersApiUpdateCustomerFinancialsRequest) HasCreditReviewDate() bool`

HasCreditReviewDate returns a boolean if a field has been set.

### GetCreditNote

`func (o *CustomersApiUpdateCustomerFinancialsRequest) GetCreditNote() string`

GetCreditNote returns the CreditNote field if non-nil, zero value otherwise.

### GetCreditNoteOk

`func (o *CustomersApiUpdateCustomerFinancialsRequest) GetCreditNoteOk() (*string, bool)`

GetCreditNoteOk returns a tuple with the CreditNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditNote

`func (o *CustomersApiUpdateCustomerFinancialsRequest) SetCreditNote(v string)`

SetCreditNote sets CreditNote field to given value.

### HasCreditNote

`func (o *CustomersApiUpdateCustomerFinancialsRequest) HasCreditNote() bool`

HasCreditNote returns a boolean if a field has been set.

### GetInvoiceDelivery

`func (o *CustomersApiUpdateCustomerFinancialsRequest) GetInvoiceDelivery() string`

GetInvoiceDelivery returns the InvoiceDelivery field if non-nil, zero value otherwise.

### GetInvoiceDeliveryOk

`func (o *CustomersApiUpdateCustomerFinancialsRequest) GetInvoiceDeliveryOk() (*string, bool)`

GetInvoiceDeliveryOk returns a tuple with the InvoiceDelivery field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceDelivery

`func (o *CustomersApiUpdateCustomerFinancialsRequest) SetInvoiceDelivery(v string)`

SetInvoiceDelivery sets InvoiceDelivery field to given value.

### HasInvoiceDelivery

`func (o *CustomersApiUpdateCustomerFinancialsRequest) HasInvoiceDelivery() bool`

HasInvoiceDelivery returns a boolean if a field has been set.

### GetSalesTaxExemptNo

`func (o *CustomersApiUpdateCustomerFinancialsRequest) GetSalesTaxExemptNo() string`

GetSalesTaxExemptNo returns the SalesTaxExemptNo field if non-nil, zero value otherwise.

### GetSalesTaxExemptNoOk

`func (o *CustomersApiUpdateCustomerFinancialsRequest) GetSalesTaxExemptNoOk() (*string, bool)`

GetSalesTaxExemptNoOk returns a tuple with the SalesTaxExemptNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSalesTaxExemptNo

`func (o *CustomersApiUpdateCustomerFinancialsRequest) SetSalesTaxExemptNo(v string)`

SetSalesTaxExemptNo sets SalesTaxExemptNo field to given value.

### HasSalesTaxExemptNo

`func (o *CustomersApiUpdateCustomerFinancialsRequest) HasSalesTaxExemptNo() bool`

HasSalesTaxExemptNo returns a boolean if a field has been set.

### GetBillingSeparation

`func (o *CustomersApiUpdateCustomerFinancialsRequest) GetBillingSeparation() int32`

GetBillingSeparation returns the BillingSeparation field if non-nil, zero value otherwise.

### GetBillingSeparationOk

`func (o *CustomersApiUpdateCustomerFinancialsRequest) GetBillingSeparationOk() (*int32, bool)`

GetBillingSeparationOk returns a tuple with the BillingSeparation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingSeparation

`func (o *CustomersApiUpdateCustomerFinancialsRequest) SetBillingSeparation(v int32)`

SetBillingSeparation sets BillingSeparation field to given value.

### HasBillingSeparation

`func (o *CustomersApiUpdateCustomerFinancialsRequest) HasBillingSeparation() bool`

HasBillingSeparation returns a boolean if a field has been set.

### GetInvoiceLineReference

`func (o *CustomersApiUpdateCustomerFinancialsRequest) GetInvoiceLineReference() string`

GetInvoiceLineReference returns the InvoiceLineReference field if non-nil, zero value otherwise.

### GetInvoiceLineReferenceOk

`func (o *CustomersApiUpdateCustomerFinancialsRequest) GetInvoiceLineReferenceOk() (*string, bool)`

GetInvoiceLineReferenceOk returns a tuple with the InvoiceLineReference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceLineReference

`func (o *CustomersApiUpdateCustomerFinancialsRequest) SetInvoiceLineReference(v string)`

SetInvoiceLineReference sets InvoiceLineReference field to given value.

### HasInvoiceLineReference

`func (o *CustomersApiUpdateCustomerFinancialsRequest) HasInvoiceLineReference() bool`

HasInvoiceLineReference returns a boolean if a field has been set.

### GetTaxIdNo

`func (o *CustomersApiUpdateCustomerFinancialsRequest) GetTaxIdNo() string`

GetTaxIdNo returns the TaxIdNo field if non-nil, zero value otherwise.

### GetTaxIdNoOk

`func (o *CustomersApiUpdateCustomerFinancialsRequest) GetTaxIdNoOk() (*string, bool)`

GetTaxIdNoOk returns a tuple with the TaxIdNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxIdNo

`func (o *CustomersApiUpdateCustomerFinancialsRequest) SetTaxIdNo(v string)`

SetTaxIdNo sets TaxIdNo field to given value.

### HasTaxIdNo

`func (o *CustomersApiUpdateCustomerFinancialsRequest) HasTaxIdNo() bool`

HasTaxIdNo returns a boolean if a field has been set.

### GetRetroactivePricing

`func (o *CustomersApiUpdateCustomerFinancialsRequest) GetRetroactivePricing() bool`

GetRetroactivePricing returns the RetroactivePricing field if non-nil, zero value otherwise.

### GetRetroactivePricingOk

`func (o *CustomersApiUpdateCustomerFinancialsRequest) GetRetroactivePricingOk() (*bool, bool)`

GetRetroactivePricingOk returns a tuple with the RetroactivePricing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRetroactivePricing

`func (o *CustomersApiUpdateCustomerFinancialsRequest) SetRetroactivePricing(v bool)`

SetRetroactivePricing sets RetroactivePricing field to given value.

### HasRetroactivePricing

`func (o *CustomersApiUpdateCustomerFinancialsRequest) HasRetroactivePricing() bool`

HasRetroactivePricing returns a boolean if a field has been set.

### GetGovernmentIssuedTaxNo

`func (o *CustomersApiUpdateCustomerFinancialsRequest) GetGovernmentIssuedTaxNo() string`

GetGovernmentIssuedTaxNo returns the GovernmentIssuedTaxNo field if non-nil, zero value otherwise.

### GetGovernmentIssuedTaxNoOk

`func (o *CustomersApiUpdateCustomerFinancialsRequest) GetGovernmentIssuedTaxNoOk() (*string, bool)`

GetGovernmentIssuedTaxNoOk returns a tuple with the GovernmentIssuedTaxNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGovernmentIssuedTaxNo

`func (o *CustomersApiUpdateCustomerFinancialsRequest) SetGovernmentIssuedTaxNo(v string)`

SetGovernmentIssuedTaxNo sets GovernmentIssuedTaxNo field to given value.

### HasGovernmentIssuedTaxNo

`func (o *CustomersApiUpdateCustomerFinancialsRequest) HasGovernmentIssuedTaxNo() bool`

HasGovernmentIssuedTaxNo returns a boolean if a field has been set.

### GetInvoicePo

`func (o *CustomersApiUpdateCustomerFinancialsRequest) GetInvoicePo() string`

GetInvoicePo returns the InvoicePo field if non-nil, zero value otherwise.

### GetInvoicePoOk

`func (o *CustomersApiUpdateCustomerFinancialsRequest) GetInvoicePoOk() (*string, bool)`

GetInvoicePoOk returns a tuple with the InvoicePo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoicePo

`func (o *CustomersApiUpdateCustomerFinancialsRequest) SetInvoicePo(v string)`

SetInvoicePo sets InvoicePo field to given value.

### HasInvoicePo

`func (o *CustomersApiUpdateCustomerFinancialsRequest) HasInvoicePo() bool`

HasInvoicePo returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


