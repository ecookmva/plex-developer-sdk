# ReceiptsApiListReceiptsItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | A unique identifier for the Receipt. This will be automatically generated if omitted from the request. | [optional] 
**PoLineItemId** | Pointer to **string** |  | [optional] 
**SupplierId** | Pointer to **string** |  | [optional] 
**PoId** | Pointer to **string** |  | [optional] 
**PartId** | Pointer to **string** |  | [optional] 
**ItemId** | Pointer to **string** |  | [optional] 
**OperationCode** | Pointer to **string** |  | [optional] 
**ReleaseId** | Pointer to **string** |  | [optional] 
**SupplierShipperNumber** | Pointer to **string** |  | [optional] 
**ReceiveDate** | Pointer to **time.Time** | The date on which the Receipt was received. | [optional] 
**ReceivedById** | Pointer to **string** | The IAM Account ID of the user who received the receipt. | [optional] 
**CreatedDate** | Pointer to **time.Time** | The date on which the Receipt was created. | [optional] 
**Quantity** | Pointer to **float64** |  | [optional] 
**PriceUnit** | Pointer to **string** |  | [optional] 
**OrderUnit** | Pointer to **string** |  | [optional] 
**UnitPrice** | Pointer to **float64** |  | [optional] 
**UnitPriceOriginal** | Pointer to **float64** |  | [optional] 
**EstimatedPrice** | Pointer to **bool** | If the unit price is estimated. | [optional] 
**InventoryUnit** | Pointer to **string** |  | [optional] 
**ExchangeRate** | Pointer to **float64** |  | [optional] 
**TaxRate** | Pointer to **float64** |  | [optional] 
**ModifiedById** | Pointer to **string** | The IAM Account ID of the user who last modified the record. | [optional] 

## Methods

### NewReceiptsApiListReceiptsItem

`func NewReceiptsApiListReceiptsItem() *ReceiptsApiListReceiptsItem`

NewReceiptsApiListReceiptsItem instantiates a new ReceiptsApiListReceiptsItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReceiptsApiListReceiptsItemWithDefaults

`func NewReceiptsApiListReceiptsItemWithDefaults() *ReceiptsApiListReceiptsItem`

NewReceiptsApiListReceiptsItemWithDefaults instantiates a new ReceiptsApiListReceiptsItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ReceiptsApiListReceiptsItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ReceiptsApiListReceiptsItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ReceiptsApiListReceiptsItem) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *ReceiptsApiListReceiptsItem) HasId() bool`

HasId returns a boolean if a field has been set.

### GetPoLineItemId

`func (o *ReceiptsApiListReceiptsItem) GetPoLineItemId() string`

GetPoLineItemId returns the PoLineItemId field if non-nil, zero value otherwise.

### GetPoLineItemIdOk

`func (o *ReceiptsApiListReceiptsItem) GetPoLineItemIdOk() (*string, bool)`

GetPoLineItemIdOk returns a tuple with the PoLineItemId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoLineItemId

`func (o *ReceiptsApiListReceiptsItem) SetPoLineItemId(v string)`

SetPoLineItemId sets PoLineItemId field to given value.

### HasPoLineItemId

`func (o *ReceiptsApiListReceiptsItem) HasPoLineItemId() bool`

HasPoLineItemId returns a boolean if a field has been set.

### GetSupplierId

`func (o *ReceiptsApiListReceiptsItem) GetSupplierId() string`

GetSupplierId returns the SupplierId field if non-nil, zero value otherwise.

### GetSupplierIdOk

`func (o *ReceiptsApiListReceiptsItem) GetSupplierIdOk() (*string, bool)`

GetSupplierIdOk returns a tuple with the SupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierId

`func (o *ReceiptsApiListReceiptsItem) SetSupplierId(v string)`

SetSupplierId sets SupplierId field to given value.

### HasSupplierId

`func (o *ReceiptsApiListReceiptsItem) HasSupplierId() bool`

HasSupplierId returns a boolean if a field has been set.

### GetPoId

`func (o *ReceiptsApiListReceiptsItem) GetPoId() string`

GetPoId returns the PoId field if non-nil, zero value otherwise.

### GetPoIdOk

`func (o *ReceiptsApiListReceiptsItem) GetPoIdOk() (*string, bool)`

GetPoIdOk returns a tuple with the PoId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoId

`func (o *ReceiptsApiListReceiptsItem) SetPoId(v string)`

SetPoId sets PoId field to given value.

### HasPoId

`func (o *ReceiptsApiListReceiptsItem) HasPoId() bool`

HasPoId returns a boolean if a field has been set.

### GetPartId

`func (o *ReceiptsApiListReceiptsItem) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *ReceiptsApiListReceiptsItem) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *ReceiptsApiListReceiptsItem) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *ReceiptsApiListReceiptsItem) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetItemId

`func (o *ReceiptsApiListReceiptsItem) GetItemId() string`

GetItemId returns the ItemId field if non-nil, zero value otherwise.

### GetItemIdOk

`func (o *ReceiptsApiListReceiptsItem) GetItemIdOk() (*string, bool)`

GetItemIdOk returns a tuple with the ItemId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItemId

`func (o *ReceiptsApiListReceiptsItem) SetItemId(v string)`

SetItemId sets ItemId field to given value.

### HasItemId

`func (o *ReceiptsApiListReceiptsItem) HasItemId() bool`

HasItemId returns a boolean if a field has been set.

### GetOperationCode

`func (o *ReceiptsApiListReceiptsItem) GetOperationCode() string`

GetOperationCode returns the OperationCode field if non-nil, zero value otherwise.

### GetOperationCodeOk

`func (o *ReceiptsApiListReceiptsItem) GetOperationCodeOk() (*string, bool)`

GetOperationCodeOk returns a tuple with the OperationCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationCode

`func (o *ReceiptsApiListReceiptsItem) SetOperationCode(v string)`

SetOperationCode sets OperationCode field to given value.

### HasOperationCode

`func (o *ReceiptsApiListReceiptsItem) HasOperationCode() bool`

HasOperationCode returns a boolean if a field has been set.

### GetReleaseId

`func (o *ReceiptsApiListReceiptsItem) GetReleaseId() string`

GetReleaseId returns the ReleaseId field if non-nil, zero value otherwise.

### GetReleaseIdOk

`func (o *ReceiptsApiListReceiptsItem) GetReleaseIdOk() (*string, bool)`

GetReleaseIdOk returns a tuple with the ReleaseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleaseId

`func (o *ReceiptsApiListReceiptsItem) SetReleaseId(v string)`

SetReleaseId sets ReleaseId field to given value.

### HasReleaseId

`func (o *ReceiptsApiListReceiptsItem) HasReleaseId() bool`

HasReleaseId returns a boolean if a field has been set.

### GetSupplierShipperNumber

`func (o *ReceiptsApiListReceiptsItem) GetSupplierShipperNumber() string`

GetSupplierShipperNumber returns the SupplierShipperNumber field if non-nil, zero value otherwise.

### GetSupplierShipperNumberOk

`func (o *ReceiptsApiListReceiptsItem) GetSupplierShipperNumberOk() (*string, bool)`

GetSupplierShipperNumberOk returns a tuple with the SupplierShipperNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierShipperNumber

`func (o *ReceiptsApiListReceiptsItem) SetSupplierShipperNumber(v string)`

SetSupplierShipperNumber sets SupplierShipperNumber field to given value.

### HasSupplierShipperNumber

`func (o *ReceiptsApiListReceiptsItem) HasSupplierShipperNumber() bool`

HasSupplierShipperNumber returns a boolean if a field has been set.

### GetReceiveDate

`func (o *ReceiptsApiListReceiptsItem) GetReceiveDate() time.Time`

GetReceiveDate returns the ReceiveDate field if non-nil, zero value otherwise.

### GetReceiveDateOk

`func (o *ReceiptsApiListReceiptsItem) GetReceiveDateOk() (*time.Time, bool)`

GetReceiveDateOk returns a tuple with the ReceiveDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceiveDate

`func (o *ReceiptsApiListReceiptsItem) SetReceiveDate(v time.Time)`

SetReceiveDate sets ReceiveDate field to given value.

### HasReceiveDate

`func (o *ReceiptsApiListReceiptsItem) HasReceiveDate() bool`

HasReceiveDate returns a boolean if a field has been set.

### GetReceivedById

`func (o *ReceiptsApiListReceiptsItem) GetReceivedById() string`

GetReceivedById returns the ReceivedById field if non-nil, zero value otherwise.

### GetReceivedByIdOk

`func (o *ReceiptsApiListReceiptsItem) GetReceivedByIdOk() (*string, bool)`

GetReceivedByIdOk returns a tuple with the ReceivedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceivedById

`func (o *ReceiptsApiListReceiptsItem) SetReceivedById(v string)`

SetReceivedById sets ReceivedById field to given value.

### HasReceivedById

`func (o *ReceiptsApiListReceiptsItem) HasReceivedById() bool`

HasReceivedById returns a boolean if a field has been set.

### GetCreatedDate

`func (o *ReceiptsApiListReceiptsItem) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *ReceiptsApiListReceiptsItem) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *ReceiptsApiListReceiptsItem) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *ReceiptsApiListReceiptsItem) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.

### GetQuantity

`func (o *ReceiptsApiListReceiptsItem) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *ReceiptsApiListReceiptsItem) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *ReceiptsApiListReceiptsItem) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *ReceiptsApiListReceiptsItem) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetPriceUnit

`func (o *ReceiptsApiListReceiptsItem) GetPriceUnit() string`

GetPriceUnit returns the PriceUnit field if non-nil, zero value otherwise.

### GetPriceUnitOk

`func (o *ReceiptsApiListReceiptsItem) GetPriceUnitOk() (*string, bool)`

GetPriceUnitOk returns a tuple with the PriceUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriceUnit

`func (o *ReceiptsApiListReceiptsItem) SetPriceUnit(v string)`

SetPriceUnit sets PriceUnit field to given value.

### HasPriceUnit

`func (o *ReceiptsApiListReceiptsItem) HasPriceUnit() bool`

HasPriceUnit returns a boolean if a field has been set.

### GetOrderUnit

`func (o *ReceiptsApiListReceiptsItem) GetOrderUnit() string`

GetOrderUnit returns the OrderUnit field if non-nil, zero value otherwise.

### GetOrderUnitOk

`func (o *ReceiptsApiListReceiptsItem) GetOrderUnitOk() (*string, bool)`

GetOrderUnitOk returns a tuple with the OrderUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderUnit

`func (o *ReceiptsApiListReceiptsItem) SetOrderUnit(v string)`

SetOrderUnit sets OrderUnit field to given value.

### HasOrderUnit

`func (o *ReceiptsApiListReceiptsItem) HasOrderUnit() bool`

HasOrderUnit returns a boolean if a field has been set.

### GetUnitPrice

`func (o *ReceiptsApiListReceiptsItem) GetUnitPrice() float64`

GetUnitPrice returns the UnitPrice field if non-nil, zero value otherwise.

### GetUnitPriceOk

`func (o *ReceiptsApiListReceiptsItem) GetUnitPriceOk() (*float64, bool)`

GetUnitPriceOk returns a tuple with the UnitPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitPrice

`func (o *ReceiptsApiListReceiptsItem) SetUnitPrice(v float64)`

SetUnitPrice sets UnitPrice field to given value.

### HasUnitPrice

`func (o *ReceiptsApiListReceiptsItem) HasUnitPrice() bool`

HasUnitPrice returns a boolean if a field has been set.

### GetUnitPriceOriginal

`func (o *ReceiptsApiListReceiptsItem) GetUnitPriceOriginal() float64`

GetUnitPriceOriginal returns the UnitPriceOriginal field if non-nil, zero value otherwise.

### GetUnitPriceOriginalOk

`func (o *ReceiptsApiListReceiptsItem) GetUnitPriceOriginalOk() (*float64, bool)`

GetUnitPriceOriginalOk returns a tuple with the UnitPriceOriginal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitPriceOriginal

`func (o *ReceiptsApiListReceiptsItem) SetUnitPriceOriginal(v float64)`

SetUnitPriceOriginal sets UnitPriceOriginal field to given value.

### HasUnitPriceOriginal

`func (o *ReceiptsApiListReceiptsItem) HasUnitPriceOriginal() bool`

HasUnitPriceOriginal returns a boolean if a field has been set.

### GetEstimatedPrice

`func (o *ReceiptsApiListReceiptsItem) GetEstimatedPrice() bool`

GetEstimatedPrice returns the EstimatedPrice field if non-nil, zero value otherwise.

### GetEstimatedPriceOk

`func (o *ReceiptsApiListReceiptsItem) GetEstimatedPriceOk() (*bool, bool)`

GetEstimatedPriceOk returns a tuple with the EstimatedPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEstimatedPrice

`func (o *ReceiptsApiListReceiptsItem) SetEstimatedPrice(v bool)`

SetEstimatedPrice sets EstimatedPrice field to given value.

### HasEstimatedPrice

`func (o *ReceiptsApiListReceiptsItem) HasEstimatedPrice() bool`

HasEstimatedPrice returns a boolean if a field has been set.

### GetInventoryUnit

`func (o *ReceiptsApiListReceiptsItem) GetInventoryUnit() string`

GetInventoryUnit returns the InventoryUnit field if non-nil, zero value otherwise.

### GetInventoryUnitOk

`func (o *ReceiptsApiListReceiptsItem) GetInventoryUnitOk() (*string, bool)`

GetInventoryUnitOk returns a tuple with the InventoryUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInventoryUnit

`func (o *ReceiptsApiListReceiptsItem) SetInventoryUnit(v string)`

SetInventoryUnit sets InventoryUnit field to given value.

### HasInventoryUnit

`func (o *ReceiptsApiListReceiptsItem) HasInventoryUnit() bool`

HasInventoryUnit returns a boolean if a field has been set.

### GetExchangeRate

`func (o *ReceiptsApiListReceiptsItem) GetExchangeRate() float64`

GetExchangeRate returns the ExchangeRate field if non-nil, zero value otherwise.

### GetExchangeRateOk

`func (o *ReceiptsApiListReceiptsItem) GetExchangeRateOk() (*float64, bool)`

GetExchangeRateOk returns a tuple with the ExchangeRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExchangeRate

`func (o *ReceiptsApiListReceiptsItem) SetExchangeRate(v float64)`

SetExchangeRate sets ExchangeRate field to given value.

### HasExchangeRate

`func (o *ReceiptsApiListReceiptsItem) HasExchangeRate() bool`

HasExchangeRate returns a boolean if a field has been set.

### GetTaxRate

`func (o *ReceiptsApiListReceiptsItem) GetTaxRate() float64`

GetTaxRate returns the TaxRate field if non-nil, zero value otherwise.

### GetTaxRateOk

`func (o *ReceiptsApiListReceiptsItem) GetTaxRateOk() (*float64, bool)`

GetTaxRateOk returns a tuple with the TaxRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxRate

`func (o *ReceiptsApiListReceiptsItem) SetTaxRate(v float64)`

SetTaxRate sets TaxRate field to given value.

### HasTaxRate

`func (o *ReceiptsApiListReceiptsItem) HasTaxRate() bool`

HasTaxRate returns a boolean if a field has been set.

### GetModifiedById

`func (o *ReceiptsApiListReceiptsItem) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *ReceiptsApiListReceiptsItem) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *ReceiptsApiListReceiptsItem) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *ReceiptsApiListReceiptsItem) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


