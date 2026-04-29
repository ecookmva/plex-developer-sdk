# ProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OperationCode** | Pointer to **string** | The operation code of the part operation. 30 characters max. | [optional] 
**OperationNumber** | Pointer to **int32** | The operation number of the part operation. | [optional] 
**PartId** | Pointer to **string** | A unique identifier of a part. | [optional] 
**PartNumber** | Pointer to **string** | The part number associated with the part ID. | [optional] 
**PartNumberRevision** | Pointer to **string** | A combination of the part number and revision associated with the part ID, separated with the value from the Part Rev Separator setting. | [optional] 
**PartOperationId** | Pointer to **string** | A unique identifier of a part operation. | [optional] 
**PartRevision** | Pointer to **string** | The part revision associated with the part ID. | [optional] 
**TotalNetWeight** | Pointer to **float64** | The weight of the container. | [optional] 
**TotalQuantity** | Pointer to **float64** | The quantity in the container. | [optional] 
**Containers** | Pointer to [**[]ContainersItem1**](ContainersItem1.md) | A list of a parts loaded containers. | [optional] 

## Methods

### NewProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem

`func NewProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem() *ProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem`

NewProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem instantiates a new ProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItemWithDefaults

`func NewProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItemWithDefaults() *ProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem`

NewProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItemWithDefaults instantiates a new ProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOperationCode

`func (o *ProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem) GetOperationCode() string`

GetOperationCode returns the OperationCode field if non-nil, zero value otherwise.

### GetOperationCodeOk

`func (o *ProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem) GetOperationCodeOk() (*string, bool)`

GetOperationCodeOk returns a tuple with the OperationCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationCode

`func (o *ProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem) SetOperationCode(v string)`

SetOperationCode sets OperationCode field to given value.

### HasOperationCode

`func (o *ProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem) HasOperationCode() bool`

HasOperationCode returns a boolean if a field has been set.

### GetOperationNumber

`func (o *ProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem) GetOperationNumber() int32`

GetOperationNumber returns the OperationNumber field if non-nil, zero value otherwise.

### GetOperationNumberOk

`func (o *ProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem) GetOperationNumberOk() (*int32, bool)`

GetOperationNumberOk returns a tuple with the OperationNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationNumber

`func (o *ProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem) SetOperationNumber(v int32)`

SetOperationNumber sets OperationNumber field to given value.

### HasOperationNumber

`func (o *ProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem) HasOperationNumber() bool`

HasOperationNumber returns a boolean if a field has been set.

### GetPartId

`func (o *ProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *ProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *ProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *ProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetPartNumber

`func (o *ProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem) GetPartNumber() string`

GetPartNumber returns the PartNumber field if non-nil, zero value otherwise.

### GetPartNumberOk

`func (o *ProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem) GetPartNumberOk() (*string, bool)`

GetPartNumberOk returns a tuple with the PartNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumber

`func (o *ProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem) SetPartNumber(v string)`

SetPartNumber sets PartNumber field to given value.

### HasPartNumber

`func (o *ProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem) HasPartNumber() bool`

HasPartNumber returns a boolean if a field has been set.

### GetPartNumberRevision

`func (o *ProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem) GetPartNumberRevision() string`

GetPartNumberRevision returns the PartNumberRevision field if non-nil, zero value otherwise.

### GetPartNumberRevisionOk

`func (o *ProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem) GetPartNumberRevisionOk() (*string, bool)`

GetPartNumberRevisionOk returns a tuple with the PartNumberRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumberRevision

`func (o *ProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem) SetPartNumberRevision(v string)`

SetPartNumberRevision sets PartNumberRevision field to given value.

### HasPartNumberRevision

`func (o *ProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem) HasPartNumberRevision() bool`

HasPartNumberRevision returns a boolean if a field has been set.

### GetPartOperationId

`func (o *ProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem) GetPartOperationId() string`

GetPartOperationId returns the PartOperationId field if non-nil, zero value otherwise.

### GetPartOperationIdOk

`func (o *ProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem) GetPartOperationIdOk() (*string, bool)`

GetPartOperationIdOk returns a tuple with the PartOperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartOperationId

`func (o *ProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem) SetPartOperationId(v string)`

SetPartOperationId sets PartOperationId field to given value.

### HasPartOperationId

`func (o *ProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem) HasPartOperationId() bool`

HasPartOperationId returns a boolean if a field has been set.

### GetPartRevision

`func (o *ProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem) GetPartRevision() string`

GetPartRevision returns the PartRevision field if non-nil, zero value otherwise.

### GetPartRevisionOk

`func (o *ProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem) GetPartRevisionOk() (*string, bool)`

GetPartRevisionOk returns a tuple with the PartRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartRevision

`func (o *ProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem) SetPartRevision(v string)`

SetPartRevision sets PartRevision field to given value.

### HasPartRevision

`func (o *ProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem) HasPartRevision() bool`

HasPartRevision returns a boolean if a field has been set.

### GetTotalNetWeight

`func (o *ProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem) GetTotalNetWeight() float64`

GetTotalNetWeight returns the TotalNetWeight field if non-nil, zero value otherwise.

### GetTotalNetWeightOk

`func (o *ProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem) GetTotalNetWeightOk() (*float64, bool)`

GetTotalNetWeightOk returns a tuple with the TotalNetWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalNetWeight

`func (o *ProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem) SetTotalNetWeight(v float64)`

SetTotalNetWeight sets TotalNetWeight field to given value.

### HasTotalNetWeight

`func (o *ProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem) HasTotalNetWeight() bool`

HasTotalNetWeight returns a boolean if a field has been set.

### GetTotalQuantity

`func (o *ProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem) GetTotalQuantity() float64`

GetTotalQuantity returns the TotalQuantity field if non-nil, zero value otherwise.

### GetTotalQuantityOk

`func (o *ProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem) GetTotalQuantityOk() (*float64, bool)`

GetTotalQuantityOk returns a tuple with the TotalQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalQuantity

`func (o *ProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem) SetTotalQuantity(v float64)`

SetTotalQuantity sets TotalQuantity field to given value.

### HasTotalQuantity

`func (o *ProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem) HasTotalQuantity() bool`

HasTotalQuantity returns a boolean if a field has been set.

### GetContainers

`func (o *ProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem) GetContainers() []ContainersItem1`

GetContainers returns the Containers field if non-nil, zero value otherwise.

### GetContainersOk

`func (o *ProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem) GetContainersOk() (*[]ContainersItem1, bool)`

GetContainersOk returns a tuple with the Containers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContainers

`func (o *ProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem) SetContainers(v []ContainersItem1)`

SetContainers sets Containers field to given value.

### HasContainers

`func (o *ProductionOperationsManagementApiUnloadSourceInventoryBySerialNoItem) HasContainers() bool`

HasContainers returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


