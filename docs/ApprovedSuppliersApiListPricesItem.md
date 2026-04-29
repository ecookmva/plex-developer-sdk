# ApprovedSuppliersApiListPricesItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Price** | Pointer to **float64** |  | [optional] 
**PriceUnit** | Pointer to **string** | The unit of measure of the part, such as pcs. | [optional] 
**EstimatedPrice** | Pointer to **bool** | If the price is an estimated price. | [optional] 
**CurrencyCode** | Pointer to **string** | The ISO 4217 three digit alphanumeric currency code designation. | [optional] 
**Active** | Pointer to **bool** |  | [optional] 
**EffectiveDate** | Pointer to **time.Time** | The date on which the price is effective. | [optional] 
**ExpirationDate** | Pointer to **time.Time** | The date on which the price expires. | [optional] 
**PriceConversion** | Pointer to **float64** |  | [optional] 
**Breakpoint** | Pointer to **int32** |  | [optional] 
**ModifiedById** | Pointer to **string** | The ID of the last person to modify the record. | [optional] 
**ModifiedDate** | Pointer to **time.Time** | The date on which the record was last modified. | [optional] 

## Methods

### NewApprovedSuppliersApiListPricesItem

`func NewApprovedSuppliersApiListPricesItem() *ApprovedSuppliersApiListPricesItem`

NewApprovedSuppliersApiListPricesItem instantiates a new ApprovedSuppliersApiListPricesItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewApprovedSuppliersApiListPricesItemWithDefaults

`func NewApprovedSuppliersApiListPricesItemWithDefaults() *ApprovedSuppliersApiListPricesItem`

NewApprovedSuppliersApiListPricesItemWithDefaults instantiates a new ApprovedSuppliersApiListPricesItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPrice

`func (o *ApprovedSuppliersApiListPricesItem) GetPrice() float64`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *ApprovedSuppliersApiListPricesItem) GetPriceOk() (*float64, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *ApprovedSuppliersApiListPricesItem) SetPrice(v float64)`

SetPrice sets Price field to given value.

### HasPrice

`func (o *ApprovedSuppliersApiListPricesItem) HasPrice() bool`

HasPrice returns a boolean if a field has been set.

### GetPriceUnit

`func (o *ApprovedSuppliersApiListPricesItem) GetPriceUnit() string`

GetPriceUnit returns the PriceUnit field if non-nil, zero value otherwise.

### GetPriceUnitOk

`func (o *ApprovedSuppliersApiListPricesItem) GetPriceUnitOk() (*string, bool)`

GetPriceUnitOk returns a tuple with the PriceUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriceUnit

`func (o *ApprovedSuppliersApiListPricesItem) SetPriceUnit(v string)`

SetPriceUnit sets PriceUnit field to given value.

### HasPriceUnit

`func (o *ApprovedSuppliersApiListPricesItem) HasPriceUnit() bool`

HasPriceUnit returns a boolean if a field has been set.

### GetEstimatedPrice

`func (o *ApprovedSuppliersApiListPricesItem) GetEstimatedPrice() bool`

GetEstimatedPrice returns the EstimatedPrice field if non-nil, zero value otherwise.

### GetEstimatedPriceOk

`func (o *ApprovedSuppliersApiListPricesItem) GetEstimatedPriceOk() (*bool, bool)`

GetEstimatedPriceOk returns a tuple with the EstimatedPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEstimatedPrice

`func (o *ApprovedSuppliersApiListPricesItem) SetEstimatedPrice(v bool)`

SetEstimatedPrice sets EstimatedPrice field to given value.

### HasEstimatedPrice

`func (o *ApprovedSuppliersApiListPricesItem) HasEstimatedPrice() bool`

HasEstimatedPrice returns a boolean if a field has been set.

### GetCurrencyCode

`func (o *ApprovedSuppliersApiListPricesItem) GetCurrencyCode() string`

GetCurrencyCode returns the CurrencyCode field if non-nil, zero value otherwise.

### GetCurrencyCodeOk

`func (o *ApprovedSuppliersApiListPricesItem) GetCurrencyCodeOk() (*string, bool)`

GetCurrencyCodeOk returns a tuple with the CurrencyCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyCode

`func (o *ApprovedSuppliersApiListPricesItem) SetCurrencyCode(v string)`

SetCurrencyCode sets CurrencyCode field to given value.

### HasCurrencyCode

`func (o *ApprovedSuppliersApiListPricesItem) HasCurrencyCode() bool`

HasCurrencyCode returns a boolean if a field has been set.

### GetActive

`func (o *ApprovedSuppliersApiListPricesItem) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *ApprovedSuppliersApiListPricesItem) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *ApprovedSuppliersApiListPricesItem) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *ApprovedSuppliersApiListPricesItem) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetEffectiveDate

`func (o *ApprovedSuppliersApiListPricesItem) GetEffectiveDate() time.Time`

GetEffectiveDate returns the EffectiveDate field if non-nil, zero value otherwise.

### GetEffectiveDateOk

`func (o *ApprovedSuppliersApiListPricesItem) GetEffectiveDateOk() (*time.Time, bool)`

GetEffectiveDateOk returns a tuple with the EffectiveDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEffectiveDate

`func (o *ApprovedSuppliersApiListPricesItem) SetEffectiveDate(v time.Time)`

SetEffectiveDate sets EffectiveDate field to given value.

### HasEffectiveDate

`func (o *ApprovedSuppliersApiListPricesItem) HasEffectiveDate() bool`

HasEffectiveDate returns a boolean if a field has been set.

### GetExpirationDate

`func (o *ApprovedSuppliersApiListPricesItem) GetExpirationDate() time.Time`

GetExpirationDate returns the ExpirationDate field if non-nil, zero value otherwise.

### GetExpirationDateOk

`func (o *ApprovedSuppliersApiListPricesItem) GetExpirationDateOk() (*time.Time, bool)`

GetExpirationDateOk returns a tuple with the ExpirationDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpirationDate

`func (o *ApprovedSuppliersApiListPricesItem) SetExpirationDate(v time.Time)`

SetExpirationDate sets ExpirationDate field to given value.

### HasExpirationDate

`func (o *ApprovedSuppliersApiListPricesItem) HasExpirationDate() bool`

HasExpirationDate returns a boolean if a field has been set.

### GetPriceConversion

`func (o *ApprovedSuppliersApiListPricesItem) GetPriceConversion() float64`

GetPriceConversion returns the PriceConversion field if non-nil, zero value otherwise.

### GetPriceConversionOk

`func (o *ApprovedSuppliersApiListPricesItem) GetPriceConversionOk() (*float64, bool)`

GetPriceConversionOk returns a tuple with the PriceConversion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriceConversion

`func (o *ApprovedSuppliersApiListPricesItem) SetPriceConversion(v float64)`

SetPriceConversion sets PriceConversion field to given value.

### HasPriceConversion

`func (o *ApprovedSuppliersApiListPricesItem) HasPriceConversion() bool`

HasPriceConversion returns a boolean if a field has been set.

### GetBreakpoint

`func (o *ApprovedSuppliersApiListPricesItem) GetBreakpoint() int32`

GetBreakpoint returns the Breakpoint field if non-nil, zero value otherwise.

### GetBreakpointOk

`func (o *ApprovedSuppliersApiListPricesItem) GetBreakpointOk() (*int32, bool)`

GetBreakpointOk returns a tuple with the Breakpoint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBreakpoint

`func (o *ApprovedSuppliersApiListPricesItem) SetBreakpoint(v int32)`

SetBreakpoint sets Breakpoint field to given value.

### HasBreakpoint

`func (o *ApprovedSuppliersApiListPricesItem) HasBreakpoint() bool`

HasBreakpoint returns a boolean if a field has been set.

### GetModifiedById

`func (o *ApprovedSuppliersApiListPricesItem) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *ApprovedSuppliersApiListPricesItem) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *ApprovedSuppliersApiListPricesItem) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *ApprovedSuppliersApiListPricesItem) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetModifiedDate

`func (o *ApprovedSuppliersApiListPricesItem) GetModifiedDate() time.Time`

GetModifiedDate returns the ModifiedDate field if non-nil, zero value otherwise.

### GetModifiedDateOk

`func (o *ApprovedSuppliersApiListPricesItem) GetModifiedDateOk() (*time.Time, bool)`

GetModifiedDateOk returns a tuple with the ModifiedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDate

`func (o *ApprovedSuppliersApiListPricesItem) SetModifiedDate(v time.Time)`

SetModifiedDate sets ModifiedDate field to given value.

### HasModifiedDate

`func (o *ApprovedSuppliersApiListPricesItem) HasModifiedDate() bool`

HasModifiedDate returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


