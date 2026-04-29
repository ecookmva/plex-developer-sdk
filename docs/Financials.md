# Financials

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**MaxDaysOutstanding** | Pointer to **int32** |  | [optional] 
**CurrencyCode** | Pointer to **string** |  | [optional] 
**Terms** | Pointer to **string** |  | [optional] 
**RequestedTerms** | Pointer to **string** |  | [optional] 
**CreditLimit** | Pointer to **float64** |  | [optional] 
**SalesTaxExempt** | Pointer to **int32** |  | [optional] 
**CreditHold** | Pointer to **bool** |  | [optional] 
**CreditStatus** | Pointer to **string** |  | [optional] 
**CreditRating** | Pointer to **string** |  | [optional] 
**CreditReviewDate** | Pointer to **time.Time** |  | [optional] 
**CreditNote** | Pointer to **string** |  | [optional] 
**InvoiceDelivery** | Pointer to **string** |  | [optional] 
**SalesTaxExemptNo** | Pointer to **string** |  | [optional] 
**BillingSeparation** | Pointer to **int32** |  | [optional] 
**InvoiceLineReference** | Pointer to **string** |  | [optional] 
**TaxIdNo** | Pointer to **string** |  | [optional] 
**RetroactivePricing** | Pointer to **bool** |  | [optional] 
**GovernmentIssuedTaxNo** | Pointer to **string** |  | [optional] 
**InvoicePo** | Pointer to **string** |  | [optional] 

## Methods

### NewFinancials

`func NewFinancials() *Financials`

NewFinancials instantiates a new Financials object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFinancialsWithDefaults

`func NewFinancialsWithDefaults() *Financials`

NewFinancialsWithDefaults instantiates a new Financials object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMaxDaysOutstanding

`func (o *Financials) GetMaxDaysOutstanding() int32`

GetMaxDaysOutstanding returns the MaxDaysOutstanding field if non-nil, zero value otherwise.

### GetMaxDaysOutstandingOk

`func (o *Financials) GetMaxDaysOutstandingOk() (*int32, bool)`

GetMaxDaysOutstandingOk returns a tuple with the MaxDaysOutstanding field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxDaysOutstanding

`func (o *Financials) SetMaxDaysOutstanding(v int32)`

SetMaxDaysOutstanding sets MaxDaysOutstanding field to given value.

### HasMaxDaysOutstanding

`func (o *Financials) HasMaxDaysOutstanding() bool`

HasMaxDaysOutstanding returns a boolean if a field has been set.

### GetCurrencyCode

`func (o *Financials) GetCurrencyCode() string`

GetCurrencyCode returns the CurrencyCode field if non-nil, zero value otherwise.

### GetCurrencyCodeOk

`func (o *Financials) GetCurrencyCodeOk() (*string, bool)`

GetCurrencyCodeOk returns a tuple with the CurrencyCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyCode

`func (o *Financials) SetCurrencyCode(v string)`

SetCurrencyCode sets CurrencyCode field to given value.

### HasCurrencyCode

`func (o *Financials) HasCurrencyCode() bool`

HasCurrencyCode returns a boolean if a field has been set.

### GetTerms

`func (o *Financials) GetTerms() string`

GetTerms returns the Terms field if non-nil, zero value otherwise.

### GetTermsOk

`func (o *Financials) GetTermsOk() (*string, bool)`

GetTermsOk returns a tuple with the Terms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTerms

`func (o *Financials) SetTerms(v string)`

SetTerms sets Terms field to given value.

### HasTerms

`func (o *Financials) HasTerms() bool`

HasTerms returns a boolean if a field has been set.

### GetRequestedTerms

`func (o *Financials) GetRequestedTerms() string`

GetRequestedTerms returns the RequestedTerms field if non-nil, zero value otherwise.

### GetRequestedTermsOk

`func (o *Financials) GetRequestedTermsOk() (*string, bool)`

GetRequestedTermsOk returns a tuple with the RequestedTerms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestedTerms

`func (o *Financials) SetRequestedTerms(v string)`

SetRequestedTerms sets RequestedTerms field to given value.

### HasRequestedTerms

`func (o *Financials) HasRequestedTerms() bool`

HasRequestedTerms returns a boolean if a field has been set.

### GetCreditLimit

`func (o *Financials) GetCreditLimit() float64`

GetCreditLimit returns the CreditLimit field if non-nil, zero value otherwise.

### GetCreditLimitOk

`func (o *Financials) GetCreditLimitOk() (*float64, bool)`

GetCreditLimitOk returns a tuple with the CreditLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditLimit

`func (o *Financials) SetCreditLimit(v float64)`

SetCreditLimit sets CreditLimit field to given value.

### HasCreditLimit

`func (o *Financials) HasCreditLimit() bool`

HasCreditLimit returns a boolean if a field has been set.

### GetSalesTaxExempt

`func (o *Financials) GetSalesTaxExempt() int32`

GetSalesTaxExempt returns the SalesTaxExempt field if non-nil, zero value otherwise.

### GetSalesTaxExemptOk

`func (o *Financials) GetSalesTaxExemptOk() (*int32, bool)`

GetSalesTaxExemptOk returns a tuple with the SalesTaxExempt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSalesTaxExempt

`func (o *Financials) SetSalesTaxExempt(v int32)`

SetSalesTaxExempt sets SalesTaxExempt field to given value.

### HasSalesTaxExempt

`func (o *Financials) HasSalesTaxExempt() bool`

HasSalesTaxExempt returns a boolean if a field has been set.

### GetCreditHold

`func (o *Financials) GetCreditHold() bool`

GetCreditHold returns the CreditHold field if non-nil, zero value otherwise.

### GetCreditHoldOk

`func (o *Financials) GetCreditHoldOk() (*bool, bool)`

GetCreditHoldOk returns a tuple with the CreditHold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditHold

`func (o *Financials) SetCreditHold(v bool)`

SetCreditHold sets CreditHold field to given value.

### HasCreditHold

`func (o *Financials) HasCreditHold() bool`

HasCreditHold returns a boolean if a field has been set.

### GetCreditStatus

`func (o *Financials) GetCreditStatus() string`

GetCreditStatus returns the CreditStatus field if non-nil, zero value otherwise.

### GetCreditStatusOk

`func (o *Financials) GetCreditStatusOk() (*string, bool)`

GetCreditStatusOk returns a tuple with the CreditStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditStatus

`func (o *Financials) SetCreditStatus(v string)`

SetCreditStatus sets CreditStatus field to given value.

### HasCreditStatus

`func (o *Financials) HasCreditStatus() bool`

HasCreditStatus returns a boolean if a field has been set.

### GetCreditRating

`func (o *Financials) GetCreditRating() string`

GetCreditRating returns the CreditRating field if non-nil, zero value otherwise.

### GetCreditRatingOk

`func (o *Financials) GetCreditRatingOk() (*string, bool)`

GetCreditRatingOk returns a tuple with the CreditRating field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditRating

`func (o *Financials) SetCreditRating(v string)`

SetCreditRating sets CreditRating field to given value.

### HasCreditRating

`func (o *Financials) HasCreditRating() bool`

HasCreditRating returns a boolean if a field has been set.

### GetCreditReviewDate

`func (o *Financials) GetCreditReviewDate() time.Time`

GetCreditReviewDate returns the CreditReviewDate field if non-nil, zero value otherwise.

### GetCreditReviewDateOk

`func (o *Financials) GetCreditReviewDateOk() (*time.Time, bool)`

GetCreditReviewDateOk returns a tuple with the CreditReviewDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditReviewDate

`func (o *Financials) SetCreditReviewDate(v time.Time)`

SetCreditReviewDate sets CreditReviewDate field to given value.

### HasCreditReviewDate

`func (o *Financials) HasCreditReviewDate() bool`

HasCreditReviewDate returns a boolean if a field has been set.

### GetCreditNote

`func (o *Financials) GetCreditNote() string`

GetCreditNote returns the CreditNote field if non-nil, zero value otherwise.

### GetCreditNoteOk

`func (o *Financials) GetCreditNoteOk() (*string, bool)`

GetCreditNoteOk returns a tuple with the CreditNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditNote

`func (o *Financials) SetCreditNote(v string)`

SetCreditNote sets CreditNote field to given value.

### HasCreditNote

`func (o *Financials) HasCreditNote() bool`

HasCreditNote returns a boolean if a field has been set.

### GetInvoiceDelivery

`func (o *Financials) GetInvoiceDelivery() string`

GetInvoiceDelivery returns the InvoiceDelivery field if non-nil, zero value otherwise.

### GetInvoiceDeliveryOk

`func (o *Financials) GetInvoiceDeliveryOk() (*string, bool)`

GetInvoiceDeliveryOk returns a tuple with the InvoiceDelivery field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceDelivery

`func (o *Financials) SetInvoiceDelivery(v string)`

SetInvoiceDelivery sets InvoiceDelivery field to given value.

### HasInvoiceDelivery

`func (o *Financials) HasInvoiceDelivery() bool`

HasInvoiceDelivery returns a boolean if a field has been set.

### GetSalesTaxExemptNo

`func (o *Financials) GetSalesTaxExemptNo() string`

GetSalesTaxExemptNo returns the SalesTaxExemptNo field if non-nil, zero value otherwise.

### GetSalesTaxExemptNoOk

`func (o *Financials) GetSalesTaxExemptNoOk() (*string, bool)`

GetSalesTaxExemptNoOk returns a tuple with the SalesTaxExemptNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSalesTaxExemptNo

`func (o *Financials) SetSalesTaxExemptNo(v string)`

SetSalesTaxExemptNo sets SalesTaxExemptNo field to given value.

### HasSalesTaxExemptNo

`func (o *Financials) HasSalesTaxExemptNo() bool`

HasSalesTaxExemptNo returns a boolean if a field has been set.

### GetBillingSeparation

`func (o *Financials) GetBillingSeparation() int32`

GetBillingSeparation returns the BillingSeparation field if non-nil, zero value otherwise.

### GetBillingSeparationOk

`func (o *Financials) GetBillingSeparationOk() (*int32, bool)`

GetBillingSeparationOk returns a tuple with the BillingSeparation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingSeparation

`func (o *Financials) SetBillingSeparation(v int32)`

SetBillingSeparation sets BillingSeparation field to given value.

### HasBillingSeparation

`func (o *Financials) HasBillingSeparation() bool`

HasBillingSeparation returns a boolean if a field has been set.

### GetInvoiceLineReference

`func (o *Financials) GetInvoiceLineReference() string`

GetInvoiceLineReference returns the InvoiceLineReference field if non-nil, zero value otherwise.

### GetInvoiceLineReferenceOk

`func (o *Financials) GetInvoiceLineReferenceOk() (*string, bool)`

GetInvoiceLineReferenceOk returns a tuple with the InvoiceLineReference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceLineReference

`func (o *Financials) SetInvoiceLineReference(v string)`

SetInvoiceLineReference sets InvoiceLineReference field to given value.

### HasInvoiceLineReference

`func (o *Financials) HasInvoiceLineReference() bool`

HasInvoiceLineReference returns a boolean if a field has been set.

### GetTaxIdNo

`func (o *Financials) GetTaxIdNo() string`

GetTaxIdNo returns the TaxIdNo field if non-nil, zero value otherwise.

### GetTaxIdNoOk

`func (o *Financials) GetTaxIdNoOk() (*string, bool)`

GetTaxIdNoOk returns a tuple with the TaxIdNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxIdNo

`func (o *Financials) SetTaxIdNo(v string)`

SetTaxIdNo sets TaxIdNo field to given value.

### HasTaxIdNo

`func (o *Financials) HasTaxIdNo() bool`

HasTaxIdNo returns a boolean if a field has been set.

### GetRetroactivePricing

`func (o *Financials) GetRetroactivePricing() bool`

GetRetroactivePricing returns the RetroactivePricing field if non-nil, zero value otherwise.

### GetRetroactivePricingOk

`func (o *Financials) GetRetroactivePricingOk() (*bool, bool)`

GetRetroactivePricingOk returns a tuple with the RetroactivePricing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRetroactivePricing

`func (o *Financials) SetRetroactivePricing(v bool)`

SetRetroactivePricing sets RetroactivePricing field to given value.

### HasRetroactivePricing

`func (o *Financials) HasRetroactivePricing() bool`

HasRetroactivePricing returns a boolean if a field has been set.

### GetGovernmentIssuedTaxNo

`func (o *Financials) GetGovernmentIssuedTaxNo() string`

GetGovernmentIssuedTaxNo returns the GovernmentIssuedTaxNo field if non-nil, zero value otherwise.

### GetGovernmentIssuedTaxNoOk

`func (o *Financials) GetGovernmentIssuedTaxNoOk() (*string, bool)`

GetGovernmentIssuedTaxNoOk returns a tuple with the GovernmentIssuedTaxNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGovernmentIssuedTaxNo

`func (o *Financials) SetGovernmentIssuedTaxNo(v string)`

SetGovernmentIssuedTaxNo sets GovernmentIssuedTaxNo field to given value.

### HasGovernmentIssuedTaxNo

`func (o *Financials) HasGovernmentIssuedTaxNo() bool`

HasGovernmentIssuedTaxNo returns a boolean if a field has been set.

### GetInvoicePo

`func (o *Financials) GetInvoicePo() string`

GetInvoicePo returns the InvoicePo field if non-nil, zero value otherwise.

### GetInvoicePoOk

`func (o *Financials) GetInvoicePoOk() (*string, bool)`

GetInvoicePoOk returns a tuple with the InvoicePo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoicePo

`func (o *Financials) SetInvoicePo(v string)`

SetInvoicePo sets InvoicePo field to given value.

### HasInvoicePo

`func (o *Financials) HasInvoicePo() bool`

HasInvoicePo returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


