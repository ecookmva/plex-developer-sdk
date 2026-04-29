# ProductionOperationsManagementApiGetProductionLineResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | The unique identifier assigned to the production line. | [optional] 
**Code** | Pointer to **string** | 50 characters max. A short name associated to the productionLineID, and a unique code to reference the production line. | [optional] 
**Description** | Pointer to **string** | 1000 characters max. The description associated to the productionLineID that describes the production line. | [optional] 
**EquipmentId** | Pointer to **string** | 50 characters max. A short name associated to the equipment. | [optional] 
**EquipmentDescription** | Pointer to **string** | 200 characters max. The description associated to the equipmentID that describes the equipment. | [optional] 
**Active** | Pointer to **bool** | The status of the production line if it is active or not. | [optional] 
**AddBy** | Pointer to **string** | 101 characters max. The name of the plex user who added the production line. | [optional] 
**AddDateTime** | Pointer to **time.Time** | The date and time the production line was added. | [optional] 
**UpdateBy** | Pointer to **string** | 101 characters max. The name of the plex user who last updated the production line. | [optional] 
**UpdateDateTime** | Pointer to **time.Time** | The date and time the production line was last updated. | [optional] 

## Methods

### NewProductionOperationsManagementApiGetProductionLineResponse

`func NewProductionOperationsManagementApiGetProductionLineResponse() *ProductionOperationsManagementApiGetProductionLineResponse`

NewProductionOperationsManagementApiGetProductionLineResponse instantiates a new ProductionOperationsManagementApiGetProductionLineResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductionOperationsManagementApiGetProductionLineResponseWithDefaults

`func NewProductionOperationsManagementApiGetProductionLineResponseWithDefaults() *ProductionOperationsManagementApiGetProductionLineResponse`

NewProductionOperationsManagementApiGetProductionLineResponseWithDefaults instantiates a new ProductionOperationsManagementApiGetProductionLineResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ProductionOperationsManagementApiGetProductionLineResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ProductionOperationsManagementApiGetProductionLineResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ProductionOperationsManagementApiGetProductionLineResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *ProductionOperationsManagementApiGetProductionLineResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCode

`func (o *ProductionOperationsManagementApiGetProductionLineResponse) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *ProductionOperationsManagementApiGetProductionLineResponse) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *ProductionOperationsManagementApiGetProductionLineResponse) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *ProductionOperationsManagementApiGetProductionLineResponse) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetDescription

`func (o *ProductionOperationsManagementApiGetProductionLineResponse) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ProductionOperationsManagementApiGetProductionLineResponse) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ProductionOperationsManagementApiGetProductionLineResponse) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ProductionOperationsManagementApiGetProductionLineResponse) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetEquipmentId

`func (o *ProductionOperationsManagementApiGetProductionLineResponse) GetEquipmentId() string`

GetEquipmentId returns the EquipmentId field if non-nil, zero value otherwise.

### GetEquipmentIdOk

`func (o *ProductionOperationsManagementApiGetProductionLineResponse) GetEquipmentIdOk() (*string, bool)`

GetEquipmentIdOk returns a tuple with the EquipmentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEquipmentId

`func (o *ProductionOperationsManagementApiGetProductionLineResponse) SetEquipmentId(v string)`

SetEquipmentId sets EquipmentId field to given value.

### HasEquipmentId

`func (o *ProductionOperationsManagementApiGetProductionLineResponse) HasEquipmentId() bool`

HasEquipmentId returns a boolean if a field has been set.

### GetEquipmentDescription

`func (o *ProductionOperationsManagementApiGetProductionLineResponse) GetEquipmentDescription() string`

GetEquipmentDescription returns the EquipmentDescription field if non-nil, zero value otherwise.

### GetEquipmentDescriptionOk

`func (o *ProductionOperationsManagementApiGetProductionLineResponse) GetEquipmentDescriptionOk() (*string, bool)`

GetEquipmentDescriptionOk returns a tuple with the EquipmentDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEquipmentDescription

`func (o *ProductionOperationsManagementApiGetProductionLineResponse) SetEquipmentDescription(v string)`

SetEquipmentDescription sets EquipmentDescription field to given value.

### HasEquipmentDescription

`func (o *ProductionOperationsManagementApiGetProductionLineResponse) HasEquipmentDescription() bool`

HasEquipmentDescription returns a boolean if a field has been set.

### GetActive

`func (o *ProductionOperationsManagementApiGetProductionLineResponse) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *ProductionOperationsManagementApiGetProductionLineResponse) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *ProductionOperationsManagementApiGetProductionLineResponse) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *ProductionOperationsManagementApiGetProductionLineResponse) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetAddBy

`func (o *ProductionOperationsManagementApiGetProductionLineResponse) GetAddBy() string`

GetAddBy returns the AddBy field if non-nil, zero value otherwise.

### GetAddByOk

`func (o *ProductionOperationsManagementApiGetProductionLineResponse) GetAddByOk() (*string, bool)`

GetAddByOk returns a tuple with the AddBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddBy

`func (o *ProductionOperationsManagementApiGetProductionLineResponse) SetAddBy(v string)`

SetAddBy sets AddBy field to given value.

### HasAddBy

`func (o *ProductionOperationsManagementApiGetProductionLineResponse) HasAddBy() bool`

HasAddBy returns a boolean if a field has been set.

### GetAddDateTime

`func (o *ProductionOperationsManagementApiGetProductionLineResponse) GetAddDateTime() time.Time`

GetAddDateTime returns the AddDateTime field if non-nil, zero value otherwise.

### GetAddDateTimeOk

`func (o *ProductionOperationsManagementApiGetProductionLineResponse) GetAddDateTimeOk() (*time.Time, bool)`

GetAddDateTimeOk returns a tuple with the AddDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddDateTime

`func (o *ProductionOperationsManagementApiGetProductionLineResponse) SetAddDateTime(v time.Time)`

SetAddDateTime sets AddDateTime field to given value.

### HasAddDateTime

`func (o *ProductionOperationsManagementApiGetProductionLineResponse) HasAddDateTime() bool`

HasAddDateTime returns a boolean if a field has been set.

### GetUpdateBy

`func (o *ProductionOperationsManagementApiGetProductionLineResponse) GetUpdateBy() string`

GetUpdateBy returns the UpdateBy field if non-nil, zero value otherwise.

### GetUpdateByOk

`func (o *ProductionOperationsManagementApiGetProductionLineResponse) GetUpdateByOk() (*string, bool)`

GetUpdateByOk returns a tuple with the UpdateBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdateBy

`func (o *ProductionOperationsManagementApiGetProductionLineResponse) SetUpdateBy(v string)`

SetUpdateBy sets UpdateBy field to given value.

### HasUpdateBy

`func (o *ProductionOperationsManagementApiGetProductionLineResponse) HasUpdateBy() bool`

HasUpdateBy returns a boolean if a field has been set.

### GetUpdateDateTime

`func (o *ProductionOperationsManagementApiGetProductionLineResponse) GetUpdateDateTime() time.Time`

GetUpdateDateTime returns the UpdateDateTime field if non-nil, zero value otherwise.

### GetUpdateDateTimeOk

`func (o *ProductionOperationsManagementApiGetProductionLineResponse) GetUpdateDateTimeOk() (*time.Time, bool)`

GetUpdateDateTimeOk returns a tuple with the UpdateDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdateDateTime

`func (o *ProductionOperationsManagementApiGetProductionLineResponse) SetUpdateDateTime(v time.Time)`

SetUpdateDateTime sets UpdateDateTime field to given value.

### HasUpdateDateTime

`func (o *ProductionOperationsManagementApiGetProductionLineResponse) HasUpdateDateTime() bool`

HasUpdateDateTime returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


