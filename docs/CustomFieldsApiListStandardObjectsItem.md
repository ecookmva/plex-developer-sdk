# CustomFieldsApiListStandardObjectsItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**StandardObjectName** | Pointer to **string** | The name of the standard object that is used internally by the system. | [optional] 
**StandardObjectLabel** | Pointer to **string** | The display name of the standard object that is used as a label on forms within Plex and on printed documents. | [optional] 
**TableName** | Pointer to **string** | The name of the table that a standard object represents. | [optional] 
**RecordIdentifiers** | Pointer to [**RecordIdentifiers**](RecordIdentifiers.md) |  | [optional] 

## Methods

### NewCustomFieldsApiListStandardObjectsItem

`func NewCustomFieldsApiListStandardObjectsItem() *CustomFieldsApiListStandardObjectsItem`

NewCustomFieldsApiListStandardObjectsItem instantiates a new CustomFieldsApiListStandardObjectsItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomFieldsApiListStandardObjectsItemWithDefaults

`func NewCustomFieldsApiListStandardObjectsItemWithDefaults() *CustomFieldsApiListStandardObjectsItem`

NewCustomFieldsApiListStandardObjectsItemWithDefaults instantiates a new CustomFieldsApiListStandardObjectsItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStandardObjectName

`func (o *CustomFieldsApiListStandardObjectsItem) GetStandardObjectName() string`

GetStandardObjectName returns the StandardObjectName field if non-nil, zero value otherwise.

### GetStandardObjectNameOk

`func (o *CustomFieldsApiListStandardObjectsItem) GetStandardObjectNameOk() (*string, bool)`

GetStandardObjectNameOk returns a tuple with the StandardObjectName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStandardObjectName

`func (o *CustomFieldsApiListStandardObjectsItem) SetStandardObjectName(v string)`

SetStandardObjectName sets StandardObjectName field to given value.

### HasStandardObjectName

`func (o *CustomFieldsApiListStandardObjectsItem) HasStandardObjectName() bool`

HasStandardObjectName returns a boolean if a field has been set.

### GetStandardObjectLabel

`func (o *CustomFieldsApiListStandardObjectsItem) GetStandardObjectLabel() string`

GetStandardObjectLabel returns the StandardObjectLabel field if non-nil, zero value otherwise.

### GetStandardObjectLabelOk

`func (o *CustomFieldsApiListStandardObjectsItem) GetStandardObjectLabelOk() (*string, bool)`

GetStandardObjectLabelOk returns a tuple with the StandardObjectLabel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStandardObjectLabel

`func (o *CustomFieldsApiListStandardObjectsItem) SetStandardObjectLabel(v string)`

SetStandardObjectLabel sets StandardObjectLabel field to given value.

### HasStandardObjectLabel

`func (o *CustomFieldsApiListStandardObjectsItem) HasStandardObjectLabel() bool`

HasStandardObjectLabel returns a boolean if a field has been set.

### GetTableName

`func (o *CustomFieldsApiListStandardObjectsItem) GetTableName() string`

GetTableName returns the TableName field if non-nil, zero value otherwise.

### GetTableNameOk

`func (o *CustomFieldsApiListStandardObjectsItem) GetTableNameOk() (*string, bool)`

GetTableNameOk returns a tuple with the TableName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTableName

`func (o *CustomFieldsApiListStandardObjectsItem) SetTableName(v string)`

SetTableName sets TableName field to given value.

### HasTableName

`func (o *CustomFieldsApiListStandardObjectsItem) HasTableName() bool`

HasTableName returns a boolean if a field has been set.

### GetRecordIdentifiers

`func (o *CustomFieldsApiListStandardObjectsItem) GetRecordIdentifiers() RecordIdentifiers`

GetRecordIdentifiers returns the RecordIdentifiers field if non-nil, zero value otherwise.

### GetRecordIdentifiersOk

`func (o *CustomFieldsApiListStandardObjectsItem) GetRecordIdentifiersOk() (*RecordIdentifiers, bool)`

GetRecordIdentifiersOk returns a tuple with the RecordIdentifiers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecordIdentifiers

`func (o *CustomFieldsApiListStandardObjectsItem) SetRecordIdentifiers(v RecordIdentifiers)`

SetRecordIdentifiers sets RecordIdentifiers field to given value.

### HasRecordIdentifiers

`func (o *CustomFieldsApiListStandardObjectsItem) HasRecordIdentifiers() bool`

HasRecordIdentifiers returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


