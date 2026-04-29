# ReceiptsApiGetReceiptResponse

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

### NewReceiptsApiGetReceiptResponse

`func NewReceiptsApiGetReceiptResponse() *ReceiptsApiGetReceiptResponse`

NewReceiptsApiGetReceiptResponse instantiates a new ReceiptsApiGetReceiptResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReceiptsApiGetReceiptResponseWithDefaults

`func NewReceiptsApiGetReceiptResponseWithDefaults() *ReceiptsApiGetReceiptResponse`

NewReceiptsApiGetReceiptResponseWithDefaults instantiates a new ReceiptsApiGetReceiptResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ReceiptsApiGetReceiptResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ReceiptsApiGetReceiptResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ReceiptsApiGetReceiptResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *ReceiptsApiGetReceiptResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetPoLineItemId

`func (o *ReceiptsApiGetReceiptResponse) GetPoLineItemId() string`

GetPoLineItemId returns the PoLineItemId field if non-nil, zero value otherwise.

### GetPoLineItemIdOk

`func (o *ReceiptsApiGetReceiptResponse) GetPoLineItemIdOk() (*string, bool)`

GetPoLineItemIdOk returns a tuple with the PoLineItemId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoLineItemId

`func (o *ReceiptsApiGetReceiptResponse) SetPoLineItemId(v string)`

SetPoLineItemId sets PoLineItemId field to given value.

### HasPoLineItemId

`func (o *ReceiptsApiGetReceiptResponse) HasPoLineItemId() bool`

HasPoLineItemId returns a boolean if a field has been set.

### GetSupplierId

`func (o *ReceiptsApiGetReceiptResponse) GetSupplierId() string`

GetSupplierId returns the SupplierId field if non-nil, zero value otherwise.

### GetSupplierIdOk

`func (o *ReceiptsApiGetReceiptResponse) GetSupplierIdOk() (*string, bool)`

GetSupplierIdOk returns a tuple with the SupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierId

`func (o *ReceiptsApiGetReceiptResponse) SetSupplierId(v string)`

SetSupplierId sets SupplierId field to given value.

### HasSupplierId

`func (o *ReceiptsApiGetReceiptResponse) HasSupplierId() bool`

HasSupplierId returns a boolean if a field has been set.

### GetPoId

`func (o *ReceiptsApiGetReceiptResponse) GetPoId() string`

GetPoId returns the PoId field if non-nil, zero value otherwise.

### GetPoIdOk

`func (o *ReceiptsApiGetReceiptResponse) GetPoIdOk() (*string, bool)`

GetPoIdOk returns a tuple with the PoId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoId

`func (o *ReceiptsApiGetReceiptResponse) SetPoId(v string)`

SetPoId sets PoId field to given value.

### HasPoId

`func (o *ReceiptsApiGetReceiptResponse) HasPoId() bool`

HasPoId returns a boolean if a field has been set.

### GetPartId

`func (o *ReceiptsApiGetReceiptResponse) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *ReceiptsApiGetReceiptResponse) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *ReceiptsApiGetReceiptResponse) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *ReceiptsApiGetReceiptResponse) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetItemId

`func (o *ReceiptsApiGetReceiptResponse) GetItemId() string`

GetItemId returns the ItemId field if non-nil, zero value otherwise.

### GetItemIdOk

`func (o *ReceiptsApiGetReceiptResponse) GetItemIdOk() (*string, bool)`

GetItemIdOk returns a tuple with the ItemId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItemId

`func (o *ReceiptsApiGetReceiptResponse) SetItemId(v string)`

SetItemId sets ItemId field to given value.

### HasItemId

`func (o *ReceiptsApiGetReceiptResponse) HasItemId() bool`

HasItemId returns a boolean if a field has been set.

### GetOperationCode

`func (o *ReceiptsApiGetReceiptResponse) GetOperationCode() string`

GetOperationCode returns the OperationCode field if non-nil, zero value otherwise.

### GetOperationCodeOk

`func (o *ReceiptsApiGetReceiptResponse) GetOperationCodeOk() (*string, bool)`

GetOperationCodeOk returns a tuple with the OperationCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationCode

`func (o *ReceiptsApiGetReceiptResponse) SetOperationCode(v string)`

SetOperationCode sets OperationCode field to given value.

### HasOperationCode

`func (o *ReceiptsApiGetReceiptResponse) HasOperationCode() bool`

HasOperationCode returns a boolean if a field has been set.

### GetReleaseId

`func (o *ReceiptsApiGetReceiptResponse) GetReleaseId() string`

GetReleaseId returns the ReleaseId field if non-nil, zero value otherwise.

### GetReleaseIdOk

`func (o *ReceiptsApiGetReceiptResponse) GetReleaseIdOk() (*string, bool)`

GetReleaseIdOk returns a tuple with the ReleaseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleaseId

`func (o *ReceiptsApiGetReceiptResponse) SetReleaseId(v string)`

SetReleaseId sets ReleaseId field to given value.

### HasReleaseId

`func (o *ReceiptsApiGetReceiptResponse) HasReleaseId() bool`

HasReleaseId returns a boolean if a field has been set.

### GetSupplierShipperNumber

`func (o *ReceiptsApiGetReceiptResponse) GetSupplierShipperNumber() string`

GetSupplierShipperNumber returns the SupplierShipperNumber field if non-nil, zero value otherwise.

### GetSupplierShipperNumberOk

`func (o *ReceiptsApiGetReceiptResponse) GetSupplierShipperNumberOk() (*string, bool)`

GetSupplierShipperNumberOk returns a tuple with the SupplierShipperNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierShipperNumber

`func (o *ReceiptsApiGetReceiptResponse) SetSupplierShipperNumber(v string)`

SetSupplierShipperNumber sets SupplierShipperNumber field to given value.

### HasSupplierShipperNumber

`func (o *ReceiptsApiGetReceiptResponse) HasSupplierShipperNumber() bool`

HasSupplierShipperNumber returns a boolean if a field has been set.

### GetReceiveDate

`func (o *ReceiptsApiGetReceiptResponse) GetReceiveDate() time.Time`

GetReceiveDate returns the ReceiveDate field if non-nil, zero value otherwise.

### GetReceiveDateOk

`func (o *ReceiptsApiGetReceiptResponse) GetReceiveDateOk() (*time.Time, bool)`

GetReceiveDateOk returns a tuple with the ReceiveDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceiveDate

`func (o *ReceiptsApiGetReceiptResponse) SetReceiveDate(v time.Time)`

SetReceiveDate sets ReceiveDate field to given value.

### HasReceiveDate

`func (o *ReceiptsApiGetReceiptResponse) HasReceiveDate() bool`

HasReceiveDate returns a boolean if a field has been set.

### GetReceivedById

`func (o *ReceiptsApiGetReceiptResponse) GetReceivedById() string`

GetReceivedById returns the ReceivedById field if non-nil, zero value otherwise.

### GetReceivedByIdOk

`func (o *ReceiptsApiGetReceiptResponse) GetReceivedByIdOk() (*string, bool)`

GetReceivedByIdOk returns a tuple with the ReceivedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceivedById

`func (o *ReceiptsApiGetReceiptResponse) SetReceivedById(v string)`

SetReceivedById sets ReceivedById field to given value.

### HasReceivedById

`func (o *ReceiptsApiGetReceiptResponse) HasReceivedById() bool`

HasReceivedById returns a boolean if a field has been set.

### GetCreatedDate

`func (o *ReceiptsApiGetReceiptResponse) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *ReceiptsApiGetReceiptResponse) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *ReceiptsApiGetReceiptResponse) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *ReceiptsApiGetReceiptResponse) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.

### GetQuantity

`func (o *ReceiptsApiGetReceiptResponse) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *ReceiptsApiGetReceiptResponse) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *ReceiptsApiGetReceiptResponse) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *ReceiptsApiGetReceiptResponse) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetPriceUnit

`func (o *ReceiptsApiGetReceiptResponse) GetPriceUnit() string`

GetPriceUnit returns the PriceUnit field if non-nil, zero value otherwise.

### GetPriceUnitOk

`func (o *ReceiptsApiGetReceiptResponse) GetPriceUnitOk() (*string, bool)`

GetPriceUnitOk returns a tuple with the PriceUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriceUnit

`func (o *ReceiptsApiGetReceiptResponse) SetPriceUnit(v string)`

SetPriceUnit sets PriceUnit field to given value.

### HasPriceUnit

`func (o *ReceiptsApiGetReceiptResponse) HasPriceUnit() bool`

HasPriceUnit returns a boolean if a field has been set.

### GetOrderUnit

`func (o *ReceiptsApiGetReceiptResponse) GetOrderUnit() string`

GetOrderUnit returns the OrderUnit field if non-nil, zero value otherwise.

### GetOrderUnitOk

`func (o *ReceiptsApiGetReceiptResponse) GetOrderUnitOk() (*string, bool)`

GetOrderUnitOk returns a tuple with the OrderUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderUnit

`func (o *ReceiptsApiGetReceiptResponse) SetOrderUnit(v string)`

SetOrderUnit sets OrderUnit field to given value.

### HasOrderUnit

`func (o *ReceiptsApiGetReceiptResponse) HasOrderUnit() bool`

HasOrderUnit returns a boolean if a field has been set.

### GetUnitPrice

`func (o *ReceiptsApiGetReceiptResponse) GetUnitPrice() float64`

GetUnitPrice returns the UnitPrice field if non-nil, zero value otherwise.

### GetUnitPriceOk

`func (o *ReceiptsApiGetReceiptResponse) GetUnitPriceOk() (*float64, bool)`

GetUnitPriceOk returns a tuple with the UnitPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitPrice

`func (o *ReceiptsApiGetReceiptResponse) SetUnitPrice(v float64)`

SetUnitPrice sets UnitPrice field to given value.

### HasUnitPrice

`func (o *ReceiptsApiGetReceiptResponse) HasUnitPrice() bool`

HasUnitPrice returns a boolean if a field has been set.

### GetUnitPriceOriginal

`func (o *ReceiptsApiGetReceiptResponse) GetUnitPriceOriginal() float64`

GetUnitPriceOriginal returns the UnitPriceOriginal field if non-nil, zero value otherwise.

### GetUnitPriceOriginalOk

`func (o *ReceiptsApiGetReceiptResponse) GetUnitPriceOriginalOk() (*float64, bool)`

GetUnitPriceOriginalOk returns a tuple with the UnitPriceOriginal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitPriceOriginal

`func (o *ReceiptsApiGetReceiptResponse) SetUnitPriceOriginal(v float64)`

SetUnitPriceOriginal sets UnitPriceOriginal field to given value.

### HasUnitPriceOriginal

`func (o *ReceiptsApiGetReceiptResponse) HasUnitPriceOriginal() bool`

HasUnitPriceOriginal returns a boolean if a field has been set.

### GetEstimatedPrice

`func (o *ReceiptsApiGetReceiptResponse) GetEstimatedPrice() bool`

GetEstimatedPrice returns the EstimatedPrice field if non-nil, zero value otherwise.

### GetEstimatedPriceOk

`func (o *ReceiptsApiGetReceiptResponse) GetEstimatedPriceOk() (*bool, bool)`

GetEstimatedPriceOk returns a tuple with the EstimatedPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEstimatedPrice

`func (o *ReceiptsApiGetReceiptResponse) SetEstimatedPrice(v bool)`

SetEstimatedPrice sets EstimatedPrice field to given value.

### HasEstimatedPrice

`func (o *ReceiptsApiGetReceiptResponse) HasEstimatedPrice() bool`

HasEstimatedPrice returns a boolean if a field has been set.

### GetInventoryUnit

`func (o *ReceiptsApiGetReceiptResponse) GetInventoryUnit() string`

GetInventoryUnit returns the InventoryUnit field if non-nil, zero value otherwise.

### GetInventoryUnitOk

`func (o *ReceiptsApiGetReceiptResponse) GetInventoryUnitOk() (*string, bool)`

GetInventoryUnitOk returns a tuple with the InventoryUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInventoryUnit

`func (o *ReceiptsApiGetReceiptResponse) SetInventoryUnit(v string)`

SetInventoryUnit sets InventoryUnit field to given value.

### HasInventoryUnit

`func (o *ReceiptsApiGetReceiptResponse) HasInventoryUnit() bool`

HasInventoryUnit returns a boolean if a field has been set.

### GetExchangeRate

`func (o *ReceiptsApiGetReceiptResponse) GetExchangeRate() float64`

GetExchangeRate returns the ExchangeRate field if non-nil, zero value otherwise.

### GetExchangeRateOk

`func (o *ReceiptsApiGetReceiptResponse) GetExchangeRateOk() (*float64, bool)`

GetExchangeRateOk returns a tuple with the ExchangeRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExchangeRate

`func (o *ReceiptsApiGetReceiptResponse) SetExchangeRate(v float64)`

SetExchangeRate sets ExchangeRate field to given value.

### HasExchangeRate

`func (o *ReceiptsApiGetReceiptResponse) HasExchangeRate() bool`

HasExchangeRate returns a boolean if a field has been set.

### GetTaxRate

`func (o *ReceiptsApiGetReceiptResponse) GetTaxRate() float64`

GetTaxRate returns the TaxRate field if non-nil, zero value otherwise.

### GetTaxRateOk

`func (o *ReceiptsApiGetReceiptResponse) GetTaxRateOk() (*float64, bool)`

GetTaxRateOk returns a tuple with the TaxRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxRate

`func (o *ReceiptsApiGetReceiptResponse) SetTaxRate(v float64)`

SetTaxRate sets TaxRate field to given value.

### HasTaxRate

`func (o *ReceiptsApiGetReceiptResponse) HasTaxRate() bool`

HasTaxRate returns a boolean if a field has been set.

### GetModifiedById

`func (o *ReceiptsApiGetReceiptResponse) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *ReceiptsApiGetReceiptResponse) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *ReceiptsApiGetReceiptResponse) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *ReceiptsApiGetReceiptResponse) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


