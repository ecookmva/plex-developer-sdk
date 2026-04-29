# CustomersApiUpdateCustomerAddressEDIDetailsRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PlantCode** | Pointer to **string** |  | [optional] 
**UltimateDestinationCode** | Pointer to **string** |  | [optional] 
**DefaultDockCode** | Pointer to **string** |  | [optional] 
**SupplierCode** | Pointer to **string** |  | [optional] 
**BillToCode** | Pointer to **string** |  | [optional] 
**InvoiceShipToCode** | Pointer to **string** |  | [optional] 
**RouteCode** | Pointer to **string** |  | [optional] 
**PoolCode** | Pointer to **string** |  | [optional] 
**WarehouseCode** | Pointer to **string** |  | [optional] 
**FunctionalGroupCode** | Pointer to **string** |  | [optional] 
**LineFeed** | Pointer to **string** |  | [optional] 
**PrimaryMailboxId** | Pointer to **string** |  | [optional] 
**InvoiceMailboxId** | Pointer to **string** |  | [optional] 
**BillAndHoldMailboxId** | Pointer to **string** |  | [optional] 
**CreateInvoice** | Pointer to **bool** |  | [optional] 
**SuppressAsn** | Pointer to **bool** |  | [optional] 
**SuppressEdiLoad** | Pointer to **bool** |  | [optional] 
**IgnoreAccums** | Pointer to **bool** |  | [optional] 
**ServiceShipment** | Pointer to **bool** |  | [optional] 
**ShipTime** | Pointer to **int32** |  | [optional] 
**ShipTimeUnit** | Pointer to **string** |  | [optional] 

## Methods

### NewCustomersApiUpdateCustomerAddressEDIDetailsRequest

`func NewCustomersApiUpdateCustomerAddressEDIDetailsRequest() *CustomersApiUpdateCustomerAddressEDIDetailsRequest`

NewCustomersApiUpdateCustomerAddressEDIDetailsRequest instantiates a new CustomersApiUpdateCustomerAddressEDIDetailsRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomersApiUpdateCustomerAddressEDIDetailsRequestWithDefaults

`func NewCustomersApiUpdateCustomerAddressEDIDetailsRequestWithDefaults() *CustomersApiUpdateCustomerAddressEDIDetailsRequest`

NewCustomersApiUpdateCustomerAddressEDIDetailsRequestWithDefaults instantiates a new CustomersApiUpdateCustomerAddressEDIDetailsRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPlantCode

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) GetPlantCode() string`

GetPlantCode returns the PlantCode field if non-nil, zero value otherwise.

### GetPlantCodeOk

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) GetPlantCodeOk() (*string, bool)`

GetPlantCodeOk returns a tuple with the PlantCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlantCode

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) SetPlantCode(v string)`

SetPlantCode sets PlantCode field to given value.

### HasPlantCode

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) HasPlantCode() bool`

HasPlantCode returns a boolean if a field has been set.

### GetUltimateDestinationCode

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) GetUltimateDestinationCode() string`

GetUltimateDestinationCode returns the UltimateDestinationCode field if non-nil, zero value otherwise.

### GetUltimateDestinationCodeOk

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) GetUltimateDestinationCodeOk() (*string, bool)`

GetUltimateDestinationCodeOk returns a tuple with the UltimateDestinationCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUltimateDestinationCode

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) SetUltimateDestinationCode(v string)`

SetUltimateDestinationCode sets UltimateDestinationCode field to given value.

### HasUltimateDestinationCode

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) HasUltimateDestinationCode() bool`

HasUltimateDestinationCode returns a boolean if a field has been set.

### GetDefaultDockCode

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) GetDefaultDockCode() string`

GetDefaultDockCode returns the DefaultDockCode field if non-nil, zero value otherwise.

### GetDefaultDockCodeOk

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) GetDefaultDockCodeOk() (*string, bool)`

GetDefaultDockCodeOk returns a tuple with the DefaultDockCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultDockCode

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) SetDefaultDockCode(v string)`

SetDefaultDockCode sets DefaultDockCode field to given value.

### HasDefaultDockCode

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) HasDefaultDockCode() bool`

HasDefaultDockCode returns a boolean if a field has been set.

### GetSupplierCode

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) GetSupplierCode() string`

GetSupplierCode returns the SupplierCode field if non-nil, zero value otherwise.

### GetSupplierCodeOk

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) GetSupplierCodeOk() (*string, bool)`

GetSupplierCodeOk returns a tuple with the SupplierCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierCode

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) SetSupplierCode(v string)`

SetSupplierCode sets SupplierCode field to given value.

### HasSupplierCode

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) HasSupplierCode() bool`

HasSupplierCode returns a boolean if a field has been set.

### GetBillToCode

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) GetBillToCode() string`

GetBillToCode returns the BillToCode field if non-nil, zero value otherwise.

### GetBillToCodeOk

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) GetBillToCodeOk() (*string, bool)`

GetBillToCodeOk returns a tuple with the BillToCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillToCode

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) SetBillToCode(v string)`

SetBillToCode sets BillToCode field to given value.

### HasBillToCode

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) HasBillToCode() bool`

HasBillToCode returns a boolean if a field has been set.

### GetInvoiceShipToCode

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) GetInvoiceShipToCode() string`

GetInvoiceShipToCode returns the InvoiceShipToCode field if non-nil, zero value otherwise.

### GetInvoiceShipToCodeOk

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) GetInvoiceShipToCodeOk() (*string, bool)`

GetInvoiceShipToCodeOk returns a tuple with the InvoiceShipToCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceShipToCode

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) SetInvoiceShipToCode(v string)`

SetInvoiceShipToCode sets InvoiceShipToCode field to given value.

### HasInvoiceShipToCode

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) HasInvoiceShipToCode() bool`

HasInvoiceShipToCode returns a boolean if a field has been set.

### GetRouteCode

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) GetRouteCode() string`

GetRouteCode returns the RouteCode field if non-nil, zero value otherwise.

### GetRouteCodeOk

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) GetRouteCodeOk() (*string, bool)`

GetRouteCodeOk returns a tuple with the RouteCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRouteCode

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) SetRouteCode(v string)`

SetRouteCode sets RouteCode field to given value.

### HasRouteCode

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) HasRouteCode() bool`

HasRouteCode returns a boolean if a field has been set.

### GetPoolCode

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) GetPoolCode() string`

GetPoolCode returns the PoolCode field if non-nil, zero value otherwise.

### GetPoolCodeOk

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) GetPoolCodeOk() (*string, bool)`

GetPoolCodeOk returns a tuple with the PoolCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoolCode

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) SetPoolCode(v string)`

SetPoolCode sets PoolCode field to given value.

### HasPoolCode

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) HasPoolCode() bool`

HasPoolCode returns a boolean if a field has been set.

### GetWarehouseCode

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) GetWarehouseCode() string`

GetWarehouseCode returns the WarehouseCode field if non-nil, zero value otherwise.

### GetWarehouseCodeOk

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) GetWarehouseCodeOk() (*string, bool)`

GetWarehouseCodeOk returns a tuple with the WarehouseCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarehouseCode

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) SetWarehouseCode(v string)`

SetWarehouseCode sets WarehouseCode field to given value.

### HasWarehouseCode

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) HasWarehouseCode() bool`

HasWarehouseCode returns a boolean if a field has been set.

### GetFunctionalGroupCode

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) GetFunctionalGroupCode() string`

GetFunctionalGroupCode returns the FunctionalGroupCode field if non-nil, zero value otherwise.

### GetFunctionalGroupCodeOk

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) GetFunctionalGroupCodeOk() (*string, bool)`

GetFunctionalGroupCodeOk returns a tuple with the FunctionalGroupCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFunctionalGroupCode

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) SetFunctionalGroupCode(v string)`

SetFunctionalGroupCode sets FunctionalGroupCode field to given value.

### HasFunctionalGroupCode

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) HasFunctionalGroupCode() bool`

HasFunctionalGroupCode returns a boolean if a field has been set.

### GetLineFeed

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) GetLineFeed() string`

GetLineFeed returns the LineFeed field if non-nil, zero value otherwise.

### GetLineFeedOk

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) GetLineFeedOk() (*string, bool)`

GetLineFeedOk returns a tuple with the LineFeed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineFeed

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) SetLineFeed(v string)`

SetLineFeed sets LineFeed field to given value.

### HasLineFeed

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) HasLineFeed() bool`

HasLineFeed returns a boolean if a field has been set.

### GetPrimaryMailboxId

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) GetPrimaryMailboxId() string`

GetPrimaryMailboxId returns the PrimaryMailboxId field if non-nil, zero value otherwise.

### GetPrimaryMailboxIdOk

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) GetPrimaryMailboxIdOk() (*string, bool)`

GetPrimaryMailboxIdOk returns a tuple with the PrimaryMailboxId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrimaryMailboxId

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) SetPrimaryMailboxId(v string)`

SetPrimaryMailboxId sets PrimaryMailboxId field to given value.

### HasPrimaryMailboxId

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) HasPrimaryMailboxId() bool`

HasPrimaryMailboxId returns a boolean if a field has been set.

### GetInvoiceMailboxId

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) GetInvoiceMailboxId() string`

GetInvoiceMailboxId returns the InvoiceMailboxId field if non-nil, zero value otherwise.

### GetInvoiceMailboxIdOk

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) GetInvoiceMailboxIdOk() (*string, bool)`

GetInvoiceMailboxIdOk returns a tuple with the InvoiceMailboxId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceMailboxId

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) SetInvoiceMailboxId(v string)`

SetInvoiceMailboxId sets InvoiceMailboxId field to given value.

### HasInvoiceMailboxId

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) HasInvoiceMailboxId() bool`

HasInvoiceMailboxId returns a boolean if a field has been set.

### GetBillAndHoldMailboxId

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) GetBillAndHoldMailboxId() string`

GetBillAndHoldMailboxId returns the BillAndHoldMailboxId field if non-nil, zero value otherwise.

### GetBillAndHoldMailboxIdOk

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) GetBillAndHoldMailboxIdOk() (*string, bool)`

GetBillAndHoldMailboxIdOk returns a tuple with the BillAndHoldMailboxId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillAndHoldMailboxId

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) SetBillAndHoldMailboxId(v string)`

SetBillAndHoldMailboxId sets BillAndHoldMailboxId field to given value.

### HasBillAndHoldMailboxId

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) HasBillAndHoldMailboxId() bool`

HasBillAndHoldMailboxId returns a boolean if a field has been set.

### GetCreateInvoice

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) GetCreateInvoice() bool`

GetCreateInvoice returns the CreateInvoice field if non-nil, zero value otherwise.

### GetCreateInvoiceOk

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) GetCreateInvoiceOk() (*bool, bool)`

GetCreateInvoiceOk returns a tuple with the CreateInvoice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreateInvoice

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) SetCreateInvoice(v bool)`

SetCreateInvoice sets CreateInvoice field to given value.

### HasCreateInvoice

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) HasCreateInvoice() bool`

HasCreateInvoice returns a boolean if a field has been set.

### GetSuppressAsn

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) GetSuppressAsn() bool`

GetSuppressAsn returns the SuppressAsn field if non-nil, zero value otherwise.

### GetSuppressAsnOk

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) GetSuppressAsnOk() (*bool, bool)`

GetSuppressAsnOk returns a tuple with the SuppressAsn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuppressAsn

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) SetSuppressAsn(v bool)`

SetSuppressAsn sets SuppressAsn field to given value.

### HasSuppressAsn

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) HasSuppressAsn() bool`

HasSuppressAsn returns a boolean if a field has been set.

### GetSuppressEdiLoad

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) GetSuppressEdiLoad() bool`

GetSuppressEdiLoad returns the SuppressEdiLoad field if non-nil, zero value otherwise.

### GetSuppressEdiLoadOk

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) GetSuppressEdiLoadOk() (*bool, bool)`

GetSuppressEdiLoadOk returns a tuple with the SuppressEdiLoad field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuppressEdiLoad

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) SetSuppressEdiLoad(v bool)`

SetSuppressEdiLoad sets SuppressEdiLoad field to given value.

### HasSuppressEdiLoad

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) HasSuppressEdiLoad() bool`

HasSuppressEdiLoad returns a boolean if a field has been set.

### GetIgnoreAccums

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) GetIgnoreAccums() bool`

GetIgnoreAccums returns the IgnoreAccums field if non-nil, zero value otherwise.

### GetIgnoreAccumsOk

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) GetIgnoreAccumsOk() (*bool, bool)`

GetIgnoreAccumsOk returns a tuple with the IgnoreAccums field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIgnoreAccums

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) SetIgnoreAccums(v bool)`

SetIgnoreAccums sets IgnoreAccums field to given value.

### HasIgnoreAccums

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) HasIgnoreAccums() bool`

HasIgnoreAccums returns a boolean if a field has been set.

### GetServiceShipment

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) GetServiceShipment() bool`

GetServiceShipment returns the ServiceShipment field if non-nil, zero value otherwise.

### GetServiceShipmentOk

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) GetServiceShipmentOk() (*bool, bool)`

GetServiceShipmentOk returns a tuple with the ServiceShipment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceShipment

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) SetServiceShipment(v bool)`

SetServiceShipment sets ServiceShipment field to given value.

### HasServiceShipment

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) HasServiceShipment() bool`

HasServiceShipment returns a boolean if a field has been set.

### GetShipTime

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) GetShipTime() int32`

GetShipTime returns the ShipTime field if non-nil, zero value otherwise.

### GetShipTimeOk

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) GetShipTimeOk() (*int32, bool)`

GetShipTimeOk returns a tuple with the ShipTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipTime

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) SetShipTime(v int32)`

SetShipTime sets ShipTime field to given value.

### HasShipTime

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) HasShipTime() bool`

HasShipTime returns a boolean if a field has been set.

### GetShipTimeUnit

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) GetShipTimeUnit() string`

GetShipTimeUnit returns the ShipTimeUnit field if non-nil, zero value otherwise.

### GetShipTimeUnitOk

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) GetShipTimeUnitOk() (*string, bool)`

GetShipTimeUnitOk returns a tuple with the ShipTimeUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipTimeUnit

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) SetShipTimeUnit(v string)`

SetShipTimeUnit sets ShipTimeUnit field to given value.

### HasShipTimeUnit

`func (o *CustomersApiUpdateCustomerAddressEDIDetailsRequest) HasShipTimeUnit() bool`

HasShipTimeUnit returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


