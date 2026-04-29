# InventoryOperationsManagementApiListSupplyItemsItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | A unique identifier for the Supply Item. | [optional] 
**SupplyItemNumber** | Pointer to **string** | A short identifier for the Supply Item. | [optional] 
**Type** | Pointer to **string** | Indicates the Supply Item type, such as office supplies or shop supplies. Setup Table: Item Type | [optional] 
**Category** | Pointer to **string** | Setup Table: Supply Category | [optional] 
**Group** | Pointer to **string** | A supply group, used to categorize Supply Items, such as Electrical, Mechanical, Office Supplies. Setup Table: Item Group | [optional] 
**Description** | Pointer to **string** | Text description of the Supply Item. | [optional] 
**InventoryUnit** | Pointer to **string** | The unit of measure for the Supply Item. | [optional] 

## Methods

### NewInventoryOperationsManagementApiListSupplyItemsItem

`func NewInventoryOperationsManagementApiListSupplyItemsItem() *InventoryOperationsManagementApiListSupplyItemsItem`

NewInventoryOperationsManagementApiListSupplyItemsItem instantiates a new InventoryOperationsManagementApiListSupplyItemsItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInventoryOperationsManagementApiListSupplyItemsItemWithDefaults

`func NewInventoryOperationsManagementApiListSupplyItemsItemWithDefaults() *InventoryOperationsManagementApiListSupplyItemsItem`

NewInventoryOperationsManagementApiListSupplyItemsItemWithDefaults instantiates a new InventoryOperationsManagementApiListSupplyItemsItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *InventoryOperationsManagementApiListSupplyItemsItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *InventoryOperationsManagementApiListSupplyItemsItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *InventoryOperationsManagementApiListSupplyItemsItem) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *InventoryOperationsManagementApiListSupplyItemsItem) HasId() bool`

HasId returns a boolean if a field has been set.

### GetSupplyItemNumber

`func (o *InventoryOperationsManagementApiListSupplyItemsItem) GetSupplyItemNumber() string`

GetSupplyItemNumber returns the SupplyItemNumber field if non-nil, zero value otherwise.

### GetSupplyItemNumberOk

`func (o *InventoryOperationsManagementApiListSupplyItemsItem) GetSupplyItemNumberOk() (*string, bool)`

GetSupplyItemNumberOk returns a tuple with the SupplyItemNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplyItemNumber

`func (o *InventoryOperationsManagementApiListSupplyItemsItem) SetSupplyItemNumber(v string)`

SetSupplyItemNumber sets SupplyItemNumber field to given value.

### HasSupplyItemNumber

`func (o *InventoryOperationsManagementApiListSupplyItemsItem) HasSupplyItemNumber() bool`

HasSupplyItemNumber returns a boolean if a field has been set.

### GetType

`func (o *InventoryOperationsManagementApiListSupplyItemsItem) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *InventoryOperationsManagementApiListSupplyItemsItem) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *InventoryOperationsManagementApiListSupplyItemsItem) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *InventoryOperationsManagementApiListSupplyItemsItem) HasType() bool`

HasType returns a boolean if a field has been set.

### GetCategory

`func (o *InventoryOperationsManagementApiListSupplyItemsItem) GetCategory() string`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *InventoryOperationsManagementApiListSupplyItemsItem) GetCategoryOk() (*string, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *InventoryOperationsManagementApiListSupplyItemsItem) SetCategory(v string)`

SetCategory sets Category field to given value.

### HasCategory

`func (o *InventoryOperationsManagementApiListSupplyItemsItem) HasCategory() bool`

HasCategory returns a boolean if a field has been set.

### GetGroup

`func (o *InventoryOperationsManagementApiListSupplyItemsItem) GetGroup() string`

GetGroup returns the Group field if non-nil, zero value otherwise.

### GetGroupOk

`func (o *InventoryOperationsManagementApiListSupplyItemsItem) GetGroupOk() (*string, bool)`

GetGroupOk returns a tuple with the Group field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroup

`func (o *InventoryOperationsManagementApiListSupplyItemsItem) SetGroup(v string)`

SetGroup sets Group field to given value.

### HasGroup

`func (o *InventoryOperationsManagementApiListSupplyItemsItem) HasGroup() bool`

HasGroup returns a boolean if a field has been set.

### GetDescription

`func (o *InventoryOperationsManagementApiListSupplyItemsItem) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *InventoryOperationsManagementApiListSupplyItemsItem) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *InventoryOperationsManagementApiListSupplyItemsItem) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *InventoryOperationsManagementApiListSupplyItemsItem) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetInventoryUnit

`func (o *InventoryOperationsManagementApiListSupplyItemsItem) GetInventoryUnit() string`

GetInventoryUnit returns the InventoryUnit field if non-nil, zero value otherwise.

### GetInventoryUnitOk

`func (o *InventoryOperationsManagementApiListSupplyItemsItem) GetInventoryUnitOk() (*string, bool)`

GetInventoryUnitOk returns a tuple with the InventoryUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInventoryUnit

`func (o *InventoryOperationsManagementApiListSupplyItemsItem) SetInventoryUnit(v string)`

SetInventoryUnit sets InventoryUnit field to given value.

### HasInventoryUnit

`func (o *InventoryOperationsManagementApiListSupplyItemsItem) HasInventoryUnit() bool`

HasInventoryUnit returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


