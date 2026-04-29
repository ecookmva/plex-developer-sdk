# CustomFieldsApiListFieldTypesItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FieldTypeName** | Pointer to **string** | The name of the data type used internally by the system. | [optional] 
**FieldTypeLabel** | Pointer to **string** | The display name of the data type that is used as a label on forms within Plex. | [optional] 
**AvailableConstraints** | Pointer to [**AvailableConstraints**](AvailableConstraints.md) |  | [optional] 

## Methods

### NewCustomFieldsApiListFieldTypesItem

`func NewCustomFieldsApiListFieldTypesItem() *CustomFieldsApiListFieldTypesItem`

NewCustomFieldsApiListFieldTypesItem instantiates a new CustomFieldsApiListFieldTypesItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomFieldsApiListFieldTypesItemWithDefaults

`func NewCustomFieldsApiListFieldTypesItemWithDefaults() *CustomFieldsApiListFieldTypesItem`

NewCustomFieldsApiListFieldTypesItemWithDefaults instantiates a new CustomFieldsApiListFieldTypesItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFieldTypeName

`func (o *CustomFieldsApiListFieldTypesItem) GetFieldTypeName() string`

GetFieldTypeName returns the FieldTypeName field if non-nil, zero value otherwise.

### GetFieldTypeNameOk

`func (o *CustomFieldsApiListFieldTypesItem) GetFieldTypeNameOk() (*string, bool)`

GetFieldTypeNameOk returns a tuple with the FieldTypeName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldTypeName

`func (o *CustomFieldsApiListFieldTypesItem) SetFieldTypeName(v string)`

SetFieldTypeName sets FieldTypeName field to given value.

### HasFieldTypeName

`func (o *CustomFieldsApiListFieldTypesItem) HasFieldTypeName() bool`

HasFieldTypeName returns a boolean if a field has been set.

### GetFieldTypeLabel

`func (o *CustomFieldsApiListFieldTypesItem) GetFieldTypeLabel() string`

GetFieldTypeLabel returns the FieldTypeLabel field if non-nil, zero value otherwise.

### GetFieldTypeLabelOk

`func (o *CustomFieldsApiListFieldTypesItem) GetFieldTypeLabelOk() (*string, bool)`

GetFieldTypeLabelOk returns a tuple with the FieldTypeLabel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldTypeLabel

`func (o *CustomFieldsApiListFieldTypesItem) SetFieldTypeLabel(v string)`

SetFieldTypeLabel sets FieldTypeLabel field to given value.

### HasFieldTypeLabel

`func (o *CustomFieldsApiListFieldTypesItem) HasFieldTypeLabel() bool`

HasFieldTypeLabel returns a boolean if a field has been set.

### GetAvailableConstraints

`func (o *CustomFieldsApiListFieldTypesItem) GetAvailableConstraints() AvailableConstraints`

GetAvailableConstraints returns the AvailableConstraints field if non-nil, zero value otherwise.

### GetAvailableConstraintsOk

`func (o *CustomFieldsApiListFieldTypesItem) GetAvailableConstraintsOk() (*AvailableConstraints, bool)`

GetAvailableConstraintsOk returns a tuple with the AvailableConstraints field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailableConstraints

`func (o *CustomFieldsApiListFieldTypesItem) SetAvailableConstraints(v AvailableConstraints)`

SetAvailableConstraints sets AvailableConstraints field to given value.

### HasAvailableConstraints

`func (o *CustomFieldsApiListFieldTypesItem) HasAvailableConstraints() bool`

HasAvailableConstraints returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


