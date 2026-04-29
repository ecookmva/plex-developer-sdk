# SalesOrdersApiUpdateSalesOrderLinePriceRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Price** | Pointer to **float64** | The price specified on the price record. | [optional] 
**Unit** | Pointer to **string** | The unit of measure used in the sales order. The unit must be a member of the unit group that is specified in the &amp;quot;Price Unit Group Name&amp;quot; setting (which defaults to Customer Orders). If the specified unit is not included in this unit group, the response will include an error code of FIELD_REFERENCE_NOT_FOUND. | [optional] 
**CurrencyCode** | Pointer to **string** | The ISO 4217 three-digit alphanumeric currency code designation. | [optional] 
**BreakpointQuantity** | Pointer to **float64** | The minimum quantity that must be ordered or shipped at one time for the price to apply. | [optional] 
**Active** | Pointer to **bool** | Identifies whether a sales order price record is considered active, regardless of effective or expiration dates. | [optional] 
**EffectiveDate** | Pointer to **time.Time** | The date on which a price on the sales order will go into effect. | [optional] 
**ExpirationDate** | Pointer to **time.Time** | The date on which a price on the sales order will expire. | [optional] 

## Methods

### NewSalesOrdersApiUpdateSalesOrderLinePriceRequest

`func NewSalesOrdersApiUpdateSalesOrderLinePriceRequest() *SalesOrdersApiUpdateSalesOrderLinePriceRequest`

NewSalesOrdersApiUpdateSalesOrderLinePriceRequest instantiates a new SalesOrdersApiUpdateSalesOrderLinePriceRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSalesOrdersApiUpdateSalesOrderLinePriceRequestWithDefaults

`func NewSalesOrdersApiUpdateSalesOrderLinePriceRequestWithDefaults() *SalesOrdersApiUpdateSalesOrderLinePriceRequest`

NewSalesOrdersApiUpdateSalesOrderLinePriceRequestWithDefaults instantiates a new SalesOrdersApiUpdateSalesOrderLinePriceRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPrice

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceRequest) GetPrice() float64`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceRequest) GetPriceOk() (*float64, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceRequest) SetPrice(v float64)`

SetPrice sets Price field to given value.

### HasPrice

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceRequest) HasPrice() bool`

HasPrice returns a boolean if a field has been set.

### GetUnit

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceRequest) GetUnit() string`

GetUnit returns the Unit field if non-nil, zero value otherwise.

### GetUnitOk

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceRequest) GetUnitOk() (*string, bool)`

GetUnitOk returns a tuple with the Unit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnit

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceRequest) SetUnit(v string)`

SetUnit sets Unit field to given value.

### HasUnit

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceRequest) HasUnit() bool`

HasUnit returns a boolean if a field has been set.

### GetCurrencyCode

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceRequest) GetCurrencyCode() string`

GetCurrencyCode returns the CurrencyCode field if non-nil, zero value otherwise.

### GetCurrencyCodeOk

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceRequest) GetCurrencyCodeOk() (*string, bool)`

GetCurrencyCodeOk returns a tuple with the CurrencyCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyCode

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceRequest) SetCurrencyCode(v string)`

SetCurrencyCode sets CurrencyCode field to given value.

### HasCurrencyCode

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceRequest) HasCurrencyCode() bool`

HasCurrencyCode returns a boolean if a field has been set.

### GetBreakpointQuantity

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceRequest) GetBreakpointQuantity() float64`

GetBreakpointQuantity returns the BreakpointQuantity field if non-nil, zero value otherwise.

### GetBreakpointQuantityOk

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceRequest) GetBreakpointQuantityOk() (*float64, bool)`

GetBreakpointQuantityOk returns a tuple with the BreakpointQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBreakpointQuantity

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceRequest) SetBreakpointQuantity(v float64)`

SetBreakpointQuantity sets BreakpointQuantity field to given value.

### HasBreakpointQuantity

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceRequest) HasBreakpointQuantity() bool`

HasBreakpointQuantity returns a boolean if a field has been set.

### GetActive

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceRequest) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceRequest) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceRequest) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceRequest) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetEffectiveDate

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceRequest) GetEffectiveDate() time.Time`

GetEffectiveDate returns the EffectiveDate field if non-nil, zero value otherwise.

### GetEffectiveDateOk

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceRequest) GetEffectiveDateOk() (*time.Time, bool)`

GetEffectiveDateOk returns a tuple with the EffectiveDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEffectiveDate

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceRequest) SetEffectiveDate(v time.Time)`

SetEffectiveDate sets EffectiveDate field to given value.

### HasEffectiveDate

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceRequest) HasEffectiveDate() bool`

HasEffectiveDate returns a boolean if a field has been set.

### GetExpirationDate

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceRequest) GetExpirationDate() time.Time`

GetExpirationDate returns the ExpirationDate field if non-nil, zero value otherwise.

### GetExpirationDateOk

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceRequest) GetExpirationDateOk() (*time.Time, bool)`

GetExpirationDateOk returns a tuple with the ExpirationDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpirationDate

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceRequest) SetExpirationDate(v time.Time)`

SetExpirationDate sets ExpirationDate field to given value.

### HasExpirationDate

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceRequest) HasExpirationDate() bool`

HasExpirationDate returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


