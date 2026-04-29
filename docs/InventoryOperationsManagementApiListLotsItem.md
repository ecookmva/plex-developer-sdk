# InventoryOperationsManagementApiListLotsItem

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

### NewInventoryOperationsManagementApiListLotsItem

`func NewInventoryOperationsManagementApiListLotsItem() *InventoryOperationsManagementApiListLotsItem`

NewInventoryOperationsManagementApiListLotsItem instantiates a new InventoryOperationsManagementApiListLotsItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInventoryOperationsManagementApiListLotsItemWithDefaults

`func NewInventoryOperationsManagementApiListLotsItemWithDefaults() *InventoryOperationsManagementApiListLotsItem`

NewInventoryOperationsManagementApiListLotsItemWithDefaults instantiates a new InventoryOperationsManagementApiListLotsItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLotNumber

`func (o *InventoryOperationsManagementApiListLotsItem) GetLotNumber() string`

GetLotNumber returns the LotNumber field if non-nil, zero value otherwise.

### GetLotNumberOk

`func (o *InventoryOperationsManagementApiListLotsItem) GetLotNumberOk() (*string, bool)`

GetLotNumberOk returns a tuple with the LotNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLotNumber

`func (o *InventoryOperationsManagementApiListLotsItem) SetLotNumber(v string)`

SetLotNumber sets LotNumber field to given value.

### HasLotNumber

`func (o *InventoryOperationsManagementApiListLotsItem) HasLotNumber() bool`

HasLotNumber returns a boolean if a field has been set.

### GetSupplierLotNumber

`func (o *InventoryOperationsManagementApiListLotsItem) GetSupplierLotNumber() string`

GetSupplierLotNumber returns the SupplierLotNumber field if non-nil, zero value otherwise.

### GetSupplierLotNumberOk

`func (o *InventoryOperationsManagementApiListLotsItem) GetSupplierLotNumberOk() (*string, bool)`

GetSupplierLotNumberOk returns a tuple with the SupplierLotNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierLotNumber

`func (o *InventoryOperationsManagementApiListLotsItem) SetSupplierLotNumber(v string)`

SetSupplierLotNumber sets SupplierLotNumber field to given value.

### HasSupplierLotNumber

`func (o *InventoryOperationsManagementApiListLotsItem) HasSupplierLotNumber() bool`

HasSupplierLotNumber returns a boolean if a field has been set.

### GetCustomerLotNumber

`func (o *InventoryOperationsManagementApiListLotsItem) GetCustomerLotNumber() string`

GetCustomerLotNumber returns the CustomerLotNumber field if non-nil, zero value otherwise.

### GetCustomerLotNumberOk

`func (o *InventoryOperationsManagementApiListLotsItem) GetCustomerLotNumberOk() (*string, bool)`

GetCustomerLotNumberOk returns a tuple with the CustomerLotNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerLotNumber

`func (o *InventoryOperationsManagementApiListLotsItem) SetCustomerLotNumber(v string)`

SetCustomerLotNumber sets CustomerLotNumber field to given value.

### HasCustomerLotNumber

`func (o *InventoryOperationsManagementApiListLotsItem) HasCustomerLotNumber() bool`

HasCustomerLotNumber returns a boolean if a field has been set.

### GetLotPartConformant

`func (o *InventoryOperationsManagementApiListLotsItem) GetLotPartConformant() bool`

GetLotPartConformant returns the LotPartConformant field if non-nil, zero value otherwise.

### GetLotPartConformantOk

`func (o *InventoryOperationsManagementApiListLotsItem) GetLotPartConformantOk() (*bool, bool)`

GetLotPartConformantOk returns a tuple with the LotPartConformant field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLotPartConformant

`func (o *InventoryOperationsManagementApiListLotsItem) SetLotPartConformant(v bool)`

SetLotPartConformant sets LotPartConformant field to given value.

### HasLotPartConformant

`func (o *InventoryOperationsManagementApiListLotsItem) HasLotPartConformant() bool`

HasLotPartConformant returns a boolean if a field has been set.

### GetManufacturedDateTime

`func (o *InventoryOperationsManagementApiListLotsItem) GetManufacturedDateTime() time.Time`

GetManufacturedDateTime returns the ManufacturedDateTime field if non-nil, zero value otherwise.

### GetManufacturedDateTimeOk

`func (o *InventoryOperationsManagementApiListLotsItem) GetManufacturedDateTimeOk() (*time.Time, bool)`

GetManufacturedDateTimeOk returns a tuple with the ManufacturedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManufacturedDateTime

`func (o *InventoryOperationsManagementApiListLotsItem) SetManufacturedDateTime(v time.Time)`

SetManufacturedDateTime sets ManufacturedDateTime field to given value.

### HasManufacturedDateTime

`func (o *InventoryOperationsManagementApiListLotsItem) HasManufacturedDateTime() bool`

HasManufacturedDateTime returns a boolean if a field has been set.

### GetSellByDateTime

`func (o *InventoryOperationsManagementApiListLotsItem) GetSellByDateTime() time.Time`

GetSellByDateTime returns the SellByDateTime field if non-nil, zero value otherwise.

### GetSellByDateTimeOk

`func (o *InventoryOperationsManagementApiListLotsItem) GetSellByDateTimeOk() (*time.Time, bool)`

GetSellByDateTimeOk returns a tuple with the SellByDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSellByDateTime

`func (o *InventoryOperationsManagementApiListLotsItem) SetSellByDateTime(v time.Time)`

SetSellByDateTime sets SellByDateTime field to given value.

### HasSellByDateTime

`func (o *InventoryOperationsManagementApiListLotsItem) HasSellByDateTime() bool`

HasSellByDateTime returns a boolean if a field has been set.

### GetUseByDateTime

`func (o *InventoryOperationsManagementApiListLotsItem) GetUseByDateTime() time.Time`

GetUseByDateTime returns the UseByDateTime field if non-nil, zero value otherwise.

### GetUseByDateTimeOk

`func (o *InventoryOperationsManagementApiListLotsItem) GetUseByDateTimeOk() (*time.Time, bool)`

GetUseByDateTimeOk returns a tuple with the UseByDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUseByDateTime

`func (o *InventoryOperationsManagementApiListLotsItem) SetUseByDateTime(v time.Time)`

SetUseByDateTime sets UseByDateTime field to given value.

### HasUseByDateTime

`func (o *InventoryOperationsManagementApiListLotsItem) HasUseByDateTime() bool`

HasUseByDateTime returns a boolean if a field has been set.

### GetBestByDateTime

`func (o *InventoryOperationsManagementApiListLotsItem) GetBestByDateTime() time.Time`

GetBestByDateTime returns the BestByDateTime field if non-nil, zero value otherwise.

### GetBestByDateTimeOk

`func (o *InventoryOperationsManagementApiListLotsItem) GetBestByDateTimeOk() (*time.Time, bool)`

GetBestByDateTimeOk returns a tuple with the BestByDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBestByDateTime

`func (o *InventoryOperationsManagementApiListLotsItem) SetBestByDateTime(v time.Time)`

SetBestByDateTime sets BestByDateTime field to given value.

### HasBestByDateTime

`func (o *InventoryOperationsManagementApiListLotsItem) HasBestByDateTime() bool`

HasBestByDateTime returns a boolean if a field has been set.

### GetQuantity

`func (o *InventoryOperationsManagementApiListLotsItem) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *InventoryOperationsManagementApiListLotsItem) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *InventoryOperationsManagementApiListLotsItem) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *InventoryOperationsManagementApiListLotsItem) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetContainerCount

`func (o *InventoryOperationsManagementApiListLotsItem) GetContainerCount() int64`

GetContainerCount returns the ContainerCount field if non-nil, zero value otherwise.

### GetContainerCountOk

`func (o *InventoryOperationsManagementApiListLotsItem) GetContainerCountOk() (*int64, bool)`

GetContainerCountOk returns a tuple with the ContainerCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContainerCount

`func (o *InventoryOperationsManagementApiListLotsItem) SetContainerCount(v int64)`

SetContainerCount sets ContainerCount field to given value.

### HasContainerCount

`func (o *InventoryOperationsManagementApiListLotsItem) HasContainerCount() bool`

HasContainerCount returns a boolean if a field has been set.

### GetPartId

`func (o *InventoryOperationsManagementApiListLotsItem) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *InventoryOperationsManagementApiListLotsItem) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *InventoryOperationsManagementApiListLotsItem) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *InventoryOperationsManagementApiListLotsItem) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetPartNumber

`func (o *InventoryOperationsManagementApiListLotsItem) GetPartNumber() string`

GetPartNumber returns the PartNumber field if non-nil, zero value otherwise.

### GetPartNumberOk

`func (o *InventoryOperationsManagementApiListLotsItem) GetPartNumberOk() (*string, bool)`

GetPartNumberOk returns a tuple with the PartNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumber

`func (o *InventoryOperationsManagementApiListLotsItem) SetPartNumber(v string)`

SetPartNumber sets PartNumber field to given value.

### HasPartNumber

`func (o *InventoryOperationsManagementApiListLotsItem) HasPartNumber() bool`

HasPartNumber returns a boolean if a field has been set.

### GetPartNumberRevision

`func (o *InventoryOperationsManagementApiListLotsItem) GetPartNumberRevision() string`

GetPartNumberRevision returns the PartNumberRevision field if non-nil, zero value otherwise.

### GetPartNumberRevisionOk

`func (o *InventoryOperationsManagementApiListLotsItem) GetPartNumberRevisionOk() (*string, bool)`

GetPartNumberRevisionOk returns a tuple with the PartNumberRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumberRevision

`func (o *InventoryOperationsManagementApiListLotsItem) SetPartNumberRevision(v string)`

SetPartNumberRevision sets PartNumberRevision field to given value.

### HasPartNumberRevision

`func (o *InventoryOperationsManagementApiListLotsItem) HasPartNumberRevision() bool`

HasPartNumberRevision returns a boolean if a field has been set.

### GetId

`func (o *InventoryOperationsManagementApiListLotsItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *InventoryOperationsManagementApiListLotsItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *InventoryOperationsManagementApiListLotsItem) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *InventoryOperationsManagementApiListLotsItem) HasId() bool`

HasId returns a boolean if a field has been set.

### GetSupplierId

`func (o *InventoryOperationsManagementApiListLotsItem) GetSupplierId() string`

GetSupplierId returns the SupplierId field if non-nil, zero value otherwise.

### GetSupplierIdOk

`func (o *InventoryOperationsManagementApiListLotsItem) GetSupplierIdOk() (*string, bool)`

GetSupplierIdOk returns a tuple with the SupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierId

`func (o *InventoryOperationsManagementApiListLotsItem) SetSupplierId(v string)`

SetSupplierId sets SupplierId field to given value.

### HasSupplierId

`func (o *InventoryOperationsManagementApiListLotsItem) HasSupplierId() bool`

HasSupplierId returns a boolean if a field has been set.

### GetCustomerId

`func (o *InventoryOperationsManagementApiListLotsItem) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *InventoryOperationsManagementApiListLotsItem) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *InventoryOperationsManagementApiListLotsItem) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *InventoryOperationsManagementApiListLotsItem) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### GetPartRevision

`func (o *InventoryOperationsManagementApiListLotsItem) GetPartRevision() string`

GetPartRevision returns the PartRevision field if non-nil, zero value otherwise.

### GetPartRevisionOk

`func (o *InventoryOperationsManagementApiListLotsItem) GetPartRevisionOk() (*string, bool)`

GetPartRevisionOk returns a tuple with the PartRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartRevision

`func (o *InventoryOperationsManagementApiListLotsItem) SetPartRevision(v string)`

SetPartRevision sets PartRevision field to given value.

### HasPartRevision

`func (o *InventoryOperationsManagementApiListLotsItem) HasPartRevision() bool`

HasPartRevision returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


