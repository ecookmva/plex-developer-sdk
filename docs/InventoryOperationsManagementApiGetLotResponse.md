# InventoryOperationsManagementApiGetLotResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**LotNumber** | Pointer to **string** | 25 characters max. The unique lot number. | [optional] 
**SupplierLotNumber** | Pointer to **string** | 25 character max. The lot number provided by the supplier. Will be &amp;quot;null&amp;quot; if customer owns the lot. | [optional] 
**CustomerLotNumber** | Pointer to **string** | 25 character max. The lot number of the lot provided by the customer. Will be &amp;quot;null&amp;quot; if supplier owns the lot. | [optional] 
**LotPartConformant** | Pointer to **bool** | Boolean flag to indicate if the PCN has lot attribute management enabled. | [optional] 
**ManufacturedDateTime** | Pointer to **time.Time** | Manufactured date of the lot. | [optional] 
**SellByDateTime** | Pointer to **time.Time** | Date by which the lot can be sold. | [optional] 
**UseByDateTime** | Pointer to **time.Time** | Date by which the lot can be used. | [optional] 
**BestByDateTime** | Pointer to **time.Time** | Date by which the lot is considered best to be used. | [optional] 
**Quantity** | Pointer to **float64** | Decimal, (18,3) Total quantity contained in all the containers that are present in the lot. | [optional] 
**ContainerCount** | Pointer to **int64** | Number of containers that are associated with the lot. | [optional] 
**PartId** | Pointer to **string** | The part ID. | [optional] 
**PartNumber** | Pointer to **string** |  | [optional] 
**PartNumberRevision** | Pointer to **string** | Format {partNumber}{part rev separator}{revision}. If a part number has a revision, Plex will return the part number and the revision separated by the Part Rev Separator setting. A Part Rev Separator can be up to 5 characters long. | [optional] 
**Id** | Pointer to **string** | The Lot ID. | [optional] 
**SupplierId** | Pointer to **string** | The Supplier ID. | [optional] 
**CustomerId** | Pointer to **string** | The Customer ID. | [optional] 
**PartRevision** | Pointer to **string** | 8 characters max. The container&#39;s Part Revision. | [optional] 

## Methods

### NewInventoryOperationsManagementApiGetLotResponse

`func NewInventoryOperationsManagementApiGetLotResponse() *InventoryOperationsManagementApiGetLotResponse`

NewInventoryOperationsManagementApiGetLotResponse instantiates a new InventoryOperationsManagementApiGetLotResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInventoryOperationsManagementApiGetLotResponseWithDefaults

`func NewInventoryOperationsManagementApiGetLotResponseWithDefaults() *InventoryOperationsManagementApiGetLotResponse`

NewInventoryOperationsManagementApiGetLotResponseWithDefaults instantiates a new InventoryOperationsManagementApiGetLotResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLotNumber

`func (o *InventoryOperationsManagementApiGetLotResponse) GetLotNumber() string`

GetLotNumber returns the LotNumber field if non-nil, zero value otherwise.

### GetLotNumberOk

`func (o *InventoryOperationsManagementApiGetLotResponse) GetLotNumberOk() (*string, bool)`

GetLotNumberOk returns a tuple with the LotNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLotNumber

`func (o *InventoryOperationsManagementApiGetLotResponse) SetLotNumber(v string)`

SetLotNumber sets LotNumber field to given value.

### HasLotNumber

`func (o *InventoryOperationsManagementApiGetLotResponse) HasLotNumber() bool`

HasLotNumber returns a boolean if a field has been set.

### GetSupplierLotNumber

`func (o *InventoryOperationsManagementApiGetLotResponse) GetSupplierLotNumber() string`

GetSupplierLotNumber returns the SupplierLotNumber field if non-nil, zero value otherwise.

### GetSupplierLotNumberOk

`func (o *InventoryOperationsManagementApiGetLotResponse) GetSupplierLotNumberOk() (*string, bool)`

GetSupplierLotNumberOk returns a tuple with the SupplierLotNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierLotNumber

`func (o *InventoryOperationsManagementApiGetLotResponse) SetSupplierLotNumber(v string)`

SetSupplierLotNumber sets SupplierLotNumber field to given value.

### HasSupplierLotNumber

`func (o *InventoryOperationsManagementApiGetLotResponse) HasSupplierLotNumber() bool`

HasSupplierLotNumber returns a boolean if a field has been set.

### GetCustomerLotNumber

`func (o *InventoryOperationsManagementApiGetLotResponse) GetCustomerLotNumber() string`

GetCustomerLotNumber returns the CustomerLotNumber field if non-nil, zero value otherwise.

### GetCustomerLotNumberOk

`func (o *InventoryOperationsManagementApiGetLotResponse) GetCustomerLotNumberOk() (*string, bool)`

GetCustomerLotNumberOk returns a tuple with the CustomerLotNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerLotNumber

`func (o *InventoryOperationsManagementApiGetLotResponse) SetCustomerLotNumber(v string)`

SetCustomerLotNumber sets CustomerLotNumber field to given value.

### HasCustomerLotNumber

`func (o *InventoryOperationsManagementApiGetLotResponse) HasCustomerLotNumber() bool`

HasCustomerLotNumber returns a boolean if a field has been set.

### GetLotPartConformant

`func (o *InventoryOperationsManagementApiGetLotResponse) GetLotPartConformant() bool`

GetLotPartConformant returns the LotPartConformant field if non-nil, zero value otherwise.

### GetLotPartConformantOk

`func (o *InventoryOperationsManagementApiGetLotResponse) GetLotPartConformantOk() (*bool, bool)`

GetLotPartConformantOk returns a tuple with the LotPartConformant field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLotPartConformant

`func (o *InventoryOperationsManagementApiGetLotResponse) SetLotPartConformant(v bool)`

SetLotPartConformant sets LotPartConformant field to given value.

### HasLotPartConformant

`func (o *InventoryOperationsManagementApiGetLotResponse) HasLotPartConformant() bool`

HasLotPartConformant returns a boolean if a field has been set.

### GetManufacturedDateTime

`func (o *InventoryOperationsManagementApiGetLotResponse) GetManufacturedDateTime() time.Time`

GetManufacturedDateTime returns the ManufacturedDateTime field if non-nil, zero value otherwise.

### GetManufacturedDateTimeOk

`func (o *InventoryOperationsManagementApiGetLotResponse) GetManufacturedDateTimeOk() (*time.Time, bool)`

GetManufacturedDateTimeOk returns a tuple with the ManufacturedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManufacturedDateTime

`func (o *InventoryOperationsManagementApiGetLotResponse) SetManufacturedDateTime(v time.Time)`

SetManufacturedDateTime sets ManufacturedDateTime field to given value.

### HasManufacturedDateTime

`func (o *InventoryOperationsManagementApiGetLotResponse) HasManufacturedDateTime() bool`

HasManufacturedDateTime returns a boolean if a field has been set.

### GetSellByDateTime

`func (o *InventoryOperationsManagementApiGetLotResponse) GetSellByDateTime() time.Time`

GetSellByDateTime returns the SellByDateTime field if non-nil, zero value otherwise.

### GetSellByDateTimeOk

`func (o *InventoryOperationsManagementApiGetLotResponse) GetSellByDateTimeOk() (*time.Time, bool)`

GetSellByDateTimeOk returns a tuple with the SellByDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSellByDateTime

`func (o *InventoryOperationsManagementApiGetLotResponse) SetSellByDateTime(v time.Time)`

SetSellByDateTime sets SellByDateTime field to given value.

### HasSellByDateTime

`func (o *InventoryOperationsManagementApiGetLotResponse) HasSellByDateTime() bool`

HasSellByDateTime returns a boolean if a field has been set.

### GetUseByDateTime

`func (o *InventoryOperationsManagementApiGetLotResponse) GetUseByDateTime() time.Time`

GetUseByDateTime returns the UseByDateTime field if non-nil, zero value otherwise.

### GetUseByDateTimeOk

`func (o *InventoryOperationsManagementApiGetLotResponse) GetUseByDateTimeOk() (*time.Time, bool)`

GetUseByDateTimeOk returns a tuple with the UseByDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUseByDateTime

`func (o *InventoryOperationsManagementApiGetLotResponse) SetUseByDateTime(v time.Time)`

SetUseByDateTime sets UseByDateTime field to given value.

### HasUseByDateTime

`func (o *InventoryOperationsManagementApiGetLotResponse) HasUseByDateTime() bool`

HasUseByDateTime returns a boolean if a field has been set.

### GetBestByDateTime

`func (o *InventoryOperationsManagementApiGetLotResponse) GetBestByDateTime() time.Time`

GetBestByDateTime returns the BestByDateTime field if non-nil, zero value otherwise.

### GetBestByDateTimeOk

`func (o *InventoryOperationsManagementApiGetLotResponse) GetBestByDateTimeOk() (*time.Time, bool)`

GetBestByDateTimeOk returns a tuple with the BestByDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBestByDateTime

`func (o *InventoryOperationsManagementApiGetLotResponse) SetBestByDateTime(v time.Time)`

SetBestByDateTime sets BestByDateTime field to given value.

### HasBestByDateTime

`func (o *InventoryOperationsManagementApiGetLotResponse) HasBestByDateTime() bool`

HasBestByDateTime returns a boolean if a field has been set.

### GetQuantity

`func (o *InventoryOperationsManagementApiGetLotResponse) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *InventoryOperationsManagementApiGetLotResponse) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *InventoryOperationsManagementApiGetLotResponse) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *InventoryOperationsManagementApiGetLotResponse) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetContainerCount

`func (o *InventoryOperationsManagementApiGetLotResponse) GetContainerCount() int64`

GetContainerCount returns the ContainerCount field if non-nil, zero value otherwise.

### GetContainerCountOk

`func (o *InventoryOperationsManagementApiGetLotResponse) GetContainerCountOk() (*int64, bool)`

GetContainerCountOk returns a tuple with the ContainerCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContainerCount

`func (o *InventoryOperationsManagementApiGetLotResponse) SetContainerCount(v int64)`

SetContainerCount sets ContainerCount field to given value.

### HasContainerCount

`func (o *InventoryOperationsManagementApiGetLotResponse) HasContainerCount() bool`

HasContainerCount returns a boolean if a field has been set.

### GetPartId

`func (o *InventoryOperationsManagementApiGetLotResponse) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *InventoryOperationsManagementApiGetLotResponse) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *InventoryOperationsManagementApiGetLotResponse) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *InventoryOperationsManagementApiGetLotResponse) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetPartNumber

`func (o *InventoryOperationsManagementApiGetLotResponse) GetPartNumber() string`

GetPartNumber returns the PartNumber field if non-nil, zero value otherwise.

### GetPartNumberOk

`func (o *InventoryOperationsManagementApiGetLotResponse) GetPartNumberOk() (*string, bool)`

GetPartNumberOk returns a tuple with the PartNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumber

`func (o *InventoryOperationsManagementApiGetLotResponse) SetPartNumber(v string)`

SetPartNumber sets PartNumber field to given value.

### HasPartNumber

`func (o *InventoryOperationsManagementApiGetLotResponse) HasPartNumber() bool`

HasPartNumber returns a boolean if a field has been set.

### GetPartNumberRevision

`func (o *InventoryOperationsManagementApiGetLotResponse) GetPartNumberRevision() string`

GetPartNumberRevision returns the PartNumberRevision field if non-nil, zero value otherwise.

### GetPartNumberRevisionOk

`func (o *InventoryOperationsManagementApiGetLotResponse) GetPartNumberRevisionOk() (*string, bool)`

GetPartNumberRevisionOk returns a tuple with the PartNumberRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumberRevision

`func (o *InventoryOperationsManagementApiGetLotResponse) SetPartNumberRevision(v string)`

SetPartNumberRevision sets PartNumberRevision field to given value.

### HasPartNumberRevision

`func (o *InventoryOperationsManagementApiGetLotResponse) HasPartNumberRevision() bool`

HasPartNumberRevision returns a boolean if a field has been set.

### GetId

`func (o *InventoryOperationsManagementApiGetLotResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *InventoryOperationsManagementApiGetLotResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *InventoryOperationsManagementApiGetLotResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *InventoryOperationsManagementApiGetLotResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetSupplierId

`func (o *InventoryOperationsManagementApiGetLotResponse) GetSupplierId() string`

GetSupplierId returns the SupplierId field if non-nil, zero value otherwise.

### GetSupplierIdOk

`func (o *InventoryOperationsManagementApiGetLotResponse) GetSupplierIdOk() (*string, bool)`

GetSupplierIdOk returns a tuple with the SupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierId

`func (o *InventoryOperationsManagementApiGetLotResponse) SetSupplierId(v string)`

SetSupplierId sets SupplierId field to given value.

### HasSupplierId

`func (o *InventoryOperationsManagementApiGetLotResponse) HasSupplierId() bool`

HasSupplierId returns a boolean if a field has been set.

### GetCustomerId

`func (o *InventoryOperationsManagementApiGetLotResponse) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *InventoryOperationsManagementApiGetLotResponse) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *InventoryOperationsManagementApiGetLotResponse) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *InventoryOperationsManagementApiGetLotResponse) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### GetPartRevision

`func (o *InventoryOperationsManagementApiGetLotResponse) GetPartRevision() string`

GetPartRevision returns the PartRevision field if non-nil, zero value otherwise.

### GetPartRevisionOk

`func (o *InventoryOperationsManagementApiGetLotResponse) GetPartRevisionOk() (*string, bool)`

GetPartRevisionOk returns a tuple with the PartRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartRevision

`func (o *InventoryOperationsManagementApiGetLotResponse) SetPartRevision(v string)`

SetPartRevision sets PartRevision field to given value.

### HasPartRevision

`func (o *InventoryOperationsManagementApiGetLotResponse) HasPartRevision() bool`

HasPartRevision returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


