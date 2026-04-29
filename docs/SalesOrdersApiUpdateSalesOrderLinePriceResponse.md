# SalesOrdersApiUpdateSalesOrderLinePriceResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | The ID of the sales order price. | [optional] 
**OrderLineId** | Pointer to **string** | The ID of the sales order line. | [optional] 
**EffectiveDate** | Pointer to **time.Time** | The date on which a price on the sales order will go into effect. | [optional] 
**BreakpointQuantity** | Pointer to **float64** | The minimum quantity that must be ordered or shipped at one time for the price to apply. | [optional] 
**LotQuantity** | Pointer to **float64** | A lot quantity assigned to the sales order price. | [optional] 
**ShipToAddressId** | Pointer to **string** | The ID of a specific customer Ship To address for which a price is valid, when pricing varies per Ship To address. | [optional] 
**ContainerType** | Pointer to **string** | The container type applied to the sales order price. | [optional] 
**PartStatus** | Pointer to **string** | The status of the price record. | [optional] 
**Price** | Pointer to **float64** | The price specified on the price record. | [optional] 
**Note** | Pointer to **string** | A note on sales order price. | [optional] 
**Active** | Pointer to **bool** | Identifies whether a sales order price record is considered active, regardless of effective or expiration dates. | [optional] 
**ExpirationDate** | Pointer to **time.Time** | The date on which a price on the sales order will expire. | [optional] 
**Unit** | Pointer to **string** | The unit of measure used in the sales order. | [optional] 
**CurrencyCode** | Pointer to **string** | The ISO 4217 three digit alphanumeric currency code designation. | [optional] 
**PartCost** | Pointer to **float64** | A cost assigned to the sales order price. Unrelated to standard or actual costing. | [optional] 
**PrimaryPrice** | Pointer to **bool** | When multiple price records contain the same Effective and Expiration Dates, the Primary Price is typically the correct Price to use in reporting. | [optional] 
**ShipmentPrice** | Pointer to **float64** | A price applied per shipment level, rather than per part. | [optional] 
**CreatedById** | Pointer to **string** | The IAM account ID of the user who created the record. | [optional] 
**CreatedDate** | Pointer to **time.Time** | The date on which the record was created. | [optional] 
**ModifiedById** | Pointer to **string** | The IAM account ID of the user who last modified the record. | [optional] 
**ModifiedDate** | Pointer to **time.Time** | The date on which the record was last modified. | [optional] 

## Methods

### NewSalesOrdersApiUpdateSalesOrderLinePriceResponse

`func NewSalesOrdersApiUpdateSalesOrderLinePriceResponse() *SalesOrdersApiUpdateSalesOrderLinePriceResponse`

NewSalesOrdersApiUpdateSalesOrderLinePriceResponse instantiates a new SalesOrdersApiUpdateSalesOrderLinePriceResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSalesOrdersApiUpdateSalesOrderLinePriceResponseWithDefaults

`func NewSalesOrdersApiUpdateSalesOrderLinePriceResponseWithDefaults() *SalesOrdersApiUpdateSalesOrderLinePriceResponse`

NewSalesOrdersApiUpdateSalesOrderLinePriceResponseWithDefaults instantiates a new SalesOrdersApiUpdateSalesOrderLinePriceResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetOrderLineId

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) GetOrderLineId() string`

GetOrderLineId returns the OrderLineId field if non-nil, zero value otherwise.

### GetOrderLineIdOk

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) GetOrderLineIdOk() (*string, bool)`

GetOrderLineIdOk returns a tuple with the OrderLineId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderLineId

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) SetOrderLineId(v string)`

SetOrderLineId sets OrderLineId field to given value.

### HasOrderLineId

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) HasOrderLineId() bool`

HasOrderLineId returns a boolean if a field has been set.

### GetEffectiveDate

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) GetEffectiveDate() time.Time`

GetEffectiveDate returns the EffectiveDate field if non-nil, zero value otherwise.

### GetEffectiveDateOk

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) GetEffectiveDateOk() (*time.Time, bool)`

GetEffectiveDateOk returns a tuple with the EffectiveDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEffectiveDate

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) SetEffectiveDate(v time.Time)`

SetEffectiveDate sets EffectiveDate field to given value.

### HasEffectiveDate

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) HasEffectiveDate() bool`

HasEffectiveDate returns a boolean if a field has been set.

### GetBreakpointQuantity

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) GetBreakpointQuantity() float64`

GetBreakpointQuantity returns the BreakpointQuantity field if non-nil, zero value otherwise.

### GetBreakpointQuantityOk

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) GetBreakpointQuantityOk() (*float64, bool)`

GetBreakpointQuantityOk returns a tuple with the BreakpointQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBreakpointQuantity

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) SetBreakpointQuantity(v float64)`

SetBreakpointQuantity sets BreakpointQuantity field to given value.

### HasBreakpointQuantity

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) HasBreakpointQuantity() bool`

HasBreakpointQuantity returns a boolean if a field has been set.

### GetLotQuantity

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) GetLotQuantity() float64`

GetLotQuantity returns the LotQuantity field if non-nil, zero value otherwise.

### GetLotQuantityOk

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) GetLotQuantityOk() (*float64, bool)`

GetLotQuantityOk returns a tuple with the LotQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLotQuantity

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) SetLotQuantity(v float64)`

SetLotQuantity sets LotQuantity field to given value.

### HasLotQuantity

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) HasLotQuantity() bool`

HasLotQuantity returns a boolean if a field has been set.

### GetShipToAddressId

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) GetShipToAddressId() string`

GetShipToAddressId returns the ShipToAddressId field if non-nil, zero value otherwise.

### GetShipToAddressIdOk

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) GetShipToAddressIdOk() (*string, bool)`

GetShipToAddressIdOk returns a tuple with the ShipToAddressId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipToAddressId

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) SetShipToAddressId(v string)`

SetShipToAddressId sets ShipToAddressId field to given value.

### HasShipToAddressId

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) HasShipToAddressId() bool`

HasShipToAddressId returns a boolean if a field has been set.

### GetContainerType

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) GetContainerType() string`

GetContainerType returns the ContainerType field if non-nil, zero value otherwise.

### GetContainerTypeOk

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) GetContainerTypeOk() (*string, bool)`

GetContainerTypeOk returns a tuple with the ContainerType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContainerType

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) SetContainerType(v string)`

SetContainerType sets ContainerType field to given value.

### HasContainerType

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) HasContainerType() bool`

HasContainerType returns a boolean if a field has been set.

### GetPartStatus

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) GetPartStatus() string`

GetPartStatus returns the PartStatus field if non-nil, zero value otherwise.

### GetPartStatusOk

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) GetPartStatusOk() (*string, bool)`

GetPartStatusOk returns a tuple with the PartStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartStatus

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) SetPartStatus(v string)`

SetPartStatus sets PartStatus field to given value.

### HasPartStatus

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) HasPartStatus() bool`

HasPartStatus returns a boolean if a field has been set.

### GetPrice

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) GetPrice() float64`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) GetPriceOk() (*float64, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) SetPrice(v float64)`

SetPrice sets Price field to given value.

### HasPrice

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) HasPrice() bool`

HasPrice returns a boolean if a field has been set.

### GetNote

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetActive

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetExpirationDate

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) GetExpirationDate() time.Time`

GetExpirationDate returns the ExpirationDate field if non-nil, zero value otherwise.

### GetExpirationDateOk

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) GetExpirationDateOk() (*time.Time, bool)`

GetExpirationDateOk returns a tuple with the ExpirationDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpirationDate

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) SetExpirationDate(v time.Time)`

SetExpirationDate sets ExpirationDate field to given value.

### HasExpirationDate

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) HasExpirationDate() bool`

HasExpirationDate returns a boolean if a field has been set.

### GetUnit

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) GetUnit() string`

GetUnit returns the Unit field if non-nil, zero value otherwise.

### GetUnitOk

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) GetUnitOk() (*string, bool)`

GetUnitOk returns a tuple with the Unit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnit

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) SetUnit(v string)`

SetUnit sets Unit field to given value.

### HasUnit

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) HasUnit() bool`

HasUnit returns a boolean if a field has been set.

### GetCurrencyCode

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) GetCurrencyCode() string`

GetCurrencyCode returns the CurrencyCode field if non-nil, zero value otherwise.

### GetCurrencyCodeOk

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) GetCurrencyCodeOk() (*string, bool)`

GetCurrencyCodeOk returns a tuple with the CurrencyCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyCode

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) SetCurrencyCode(v string)`

SetCurrencyCode sets CurrencyCode field to given value.

### HasCurrencyCode

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) HasCurrencyCode() bool`

HasCurrencyCode returns a boolean if a field has been set.

### GetPartCost

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) GetPartCost() float64`

GetPartCost returns the PartCost field if non-nil, zero value otherwise.

### GetPartCostOk

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) GetPartCostOk() (*float64, bool)`

GetPartCostOk returns a tuple with the PartCost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartCost

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) SetPartCost(v float64)`

SetPartCost sets PartCost field to given value.

### HasPartCost

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) HasPartCost() bool`

HasPartCost returns a boolean if a field has been set.

### GetPrimaryPrice

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) GetPrimaryPrice() bool`

GetPrimaryPrice returns the PrimaryPrice field if non-nil, zero value otherwise.

### GetPrimaryPriceOk

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) GetPrimaryPriceOk() (*bool, bool)`

GetPrimaryPriceOk returns a tuple with the PrimaryPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrimaryPrice

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) SetPrimaryPrice(v bool)`

SetPrimaryPrice sets PrimaryPrice field to given value.

### HasPrimaryPrice

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) HasPrimaryPrice() bool`

HasPrimaryPrice returns a boolean if a field has been set.

### GetShipmentPrice

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) GetShipmentPrice() float64`

GetShipmentPrice returns the ShipmentPrice field if non-nil, zero value otherwise.

### GetShipmentPriceOk

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) GetShipmentPriceOk() (*float64, bool)`

GetShipmentPriceOk returns a tuple with the ShipmentPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipmentPrice

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) SetShipmentPrice(v float64)`

SetShipmentPrice sets ShipmentPrice field to given value.

### HasShipmentPrice

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) HasShipmentPrice() bool`

HasShipmentPrice returns a boolean if a field has been set.

### GetCreatedById

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) GetCreatedById() string`

GetCreatedById returns the CreatedById field if non-nil, zero value otherwise.

### GetCreatedByIdOk

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) GetCreatedByIdOk() (*string, bool)`

GetCreatedByIdOk returns a tuple with the CreatedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedById

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) SetCreatedById(v string)`

SetCreatedById sets CreatedById field to given value.

### HasCreatedById

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) HasCreatedById() bool`

HasCreatedById returns a boolean if a field has been set.

### GetCreatedDate

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.

### GetModifiedById

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetModifiedDate

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) GetModifiedDate() time.Time`

GetModifiedDate returns the ModifiedDate field if non-nil, zero value otherwise.

### GetModifiedDateOk

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) GetModifiedDateOk() (*time.Time, bool)`

GetModifiedDateOk returns a tuple with the ModifiedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDate

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) SetModifiedDate(v time.Time)`

SetModifiedDate sets ModifiedDate field to given value.

### HasModifiedDate

`func (o *SalesOrdersApiUpdateSalesOrderLinePriceResponse) HasModifiedDate() bool`

HasModifiedDate returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


