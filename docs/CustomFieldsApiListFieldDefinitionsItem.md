# CustomFieldsApiListFieldDefinitionsItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**StandardObjectName** | Pointer to **string** | The name of the standard object that is used internally by the system. | [optional] 
**FieldTypeName** | Pointer to **string** | The name of the data type used internally by the system. | [optional] 
**FieldName** | Pointer to **string** | The name of the field definition that uniquely identifies the field within a standard object and is used internally by the system. | [optional] 
**FieldLabel** | Pointer to **string** | The display name of the custom field that is used as a label on forms within Plex and on printed documents. | [optional] 
**Description** | Pointer to **string** | The description of the custom field definition that helps users understand of information should be saved to the custom field. | [optional] 
**Constraints** | Pointer to **string** | Constraints of the custom field definition, such as minimum and maximum values that are allowed. | [optional] 

## Methods

### NewCustomFieldsApiListFieldDefinitionsItem

`func NewCustomFieldsApiListFieldDefinitionsItem() *CustomFieldsApiListFieldDefinitionsItem`

NewCustomFieldsApiListFieldDefinitionsItem instantiates a new CustomFieldsApiListFieldDefinitionsItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomFieldsApiListFieldDefinitionsItemWithDefaults

`func NewCustomFieldsApiListFieldDefinitionsItemWithDefaults() *CustomFieldsApiListFieldDefinitionsItem`

NewCustomFieldsApiListFieldDefinitionsItemWithDefaults instantiates a new CustomFieldsApiListFieldDefinitionsItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStandardObjectName

`func (o *CustomFieldsApiListFieldDefinitionsItem) GetStandardObjectName() string`

GetStandardObjectName returns the StandardObjectName field if non-nil, zero value otherwise.

### GetStandardObjectNameOk

`func (o *CustomFieldsApiListFieldDefinitionsItem) GetStandardObjectNameOk() (*string, bool)`

GetStandardObjectNameOk returns a tuple with the StandardObjectName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStandardObjectName

`func (o *CustomFieldsApiListFieldDefinitionsItem) SetStandardObjectName(v string)`

SetStandardObjectName sets StandardObjectName field to given value.

### HasStandardObjectName

`func (o *CustomFieldsApiListFieldDefinitionsItem) HasStandardObjectName() bool`

HasStandardObjectName returns a boolean if a field has been set.

### GetFieldTypeName

`func (o *CustomFieldsApiListFieldDefinitionsItem) GetFieldTypeName() string`

GetFieldTypeName returns the FieldTypeName field if non-nil, zero value otherwise.

### GetFieldTypeNameOk

`func (o *CustomFieldsApiListFieldDefinitionsItem) GetFieldTypeNameOk() (*string, bool)`

GetFieldTypeNameOk returns a tuple with the FieldTypeName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldTypeName

`func (o *CustomFieldsApiListFieldDefinitionsItem) SetFieldTypeName(v string)`

SetFieldTypeName sets FieldTypeName field to given value.

### HasFieldTypeName

`func (o *CustomFieldsApiListFieldDefinitionsItem) HasFieldTypeName() bool`

HasFieldTypeName returns a boolean if a field has been set.

### GetFieldName

`func (o *CustomFieldsApiListFieldDefinitionsItem) GetFieldName() string`

GetFieldName returns the FieldName field if non-nil, zero value otherwise.

### GetFieldNameOk

`func (o *CustomFieldsApiListFieldDefinitionsItem) GetFieldNameOk() (*string, bool)`

GetFieldNameOk returns a tuple with the FieldName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldName

`func (o *CustomFieldsApiListFieldDefinitionsItem) SetFieldName(v string)`

SetFieldName sets FieldName field to given value.

### HasFieldName

`func (o *CustomFieldsApiListFieldDefinitionsItem) HasFieldName() bool`

HasFieldName returns a boolean if a field has been set.

### GetFieldLabel

`func (o *CustomFieldsApiListFieldDefinitionsItem) GetFieldLabel() string`

GetFieldLabel returns the FieldLabel field if non-nil, zero value otherwise.

### GetFieldLabelOk

`func (o *CustomFieldsApiListFieldDefinitionsItem) GetFieldLabelOk() (*string, bool)`

GetFieldLabelOk returns a tuple with the FieldLabel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldLabel

`func (o *CustomFieldsApiListFieldDefinitionsItem) SetFieldLabel(v string)`

SetFieldLabel sets FieldLabel field to given value.

### HasFieldLabel

`func (o *CustomFieldsApiListFieldDefinitionsItem) HasFieldLabel() bool`

HasFieldLabel returns a boolean if a field has been set.

### GetDescription

`func (o *CustomFieldsApiListFieldDefinitionsItem) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CustomFieldsApiListFieldDefinitionsItem) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CustomFieldsApiListFieldDefinitionsItem) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CustomFieldsApiListFieldDefinitionsItem) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetConstraints

`func (o *CustomFieldsApiListFieldDefinitionsItem) GetConstraints() string`

GetConstraints returns the Constraints field if non-nil, zero value otherwise.

### GetConstraintsOk

`func (o *CustomFieldsApiListFieldDefinitionsItem) GetConstraintsOk() (*string, bool)`

GetConstraintsOk returns a tuple with the Constraints field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConstraints

`func (o *CustomFieldsApiListFieldDefinitionsItem) SetConstraints(v string)`

SetConstraints sets Constraints field to given value.

### HasConstraints

`func (o *CustomFieldsApiListFieldDefinitionsItem) HasConstraints() bool`

HasConstraints returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


