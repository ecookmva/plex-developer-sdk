# CustomFieldsApiGetFieldDefinitionItem

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

### NewCustomFieldsApiGetFieldDefinitionItem

`func NewCustomFieldsApiGetFieldDefinitionItem() *CustomFieldsApiGetFieldDefinitionItem`

NewCustomFieldsApiGetFieldDefinitionItem instantiates a new CustomFieldsApiGetFieldDefinitionItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomFieldsApiGetFieldDefinitionItemWithDefaults

`func NewCustomFieldsApiGetFieldDefinitionItemWithDefaults() *CustomFieldsApiGetFieldDefinitionItem`

NewCustomFieldsApiGetFieldDefinitionItemWithDefaults instantiates a new CustomFieldsApiGetFieldDefinitionItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStandardObjectName

`func (o *CustomFieldsApiGetFieldDefinitionItem) GetStandardObjectName() string`

GetStandardObjectName returns the StandardObjectName field if non-nil, zero value otherwise.

### GetStandardObjectNameOk

`func (o *CustomFieldsApiGetFieldDefinitionItem) GetStandardObjectNameOk() (*string, bool)`

GetStandardObjectNameOk returns a tuple with the StandardObjectName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStandardObjectName

`func (o *CustomFieldsApiGetFieldDefinitionItem) SetStandardObjectName(v string)`

SetStandardObjectName sets StandardObjectName field to given value.

### HasStandardObjectName

`func (o *CustomFieldsApiGetFieldDefinitionItem) HasStandardObjectName() bool`

HasStandardObjectName returns a boolean if a field has been set.

### GetFieldTypeName

`func (o *CustomFieldsApiGetFieldDefinitionItem) GetFieldTypeName() string`

GetFieldTypeName returns the FieldTypeName field if non-nil, zero value otherwise.

### GetFieldTypeNameOk

`func (o *CustomFieldsApiGetFieldDefinitionItem) GetFieldTypeNameOk() (*string, bool)`

GetFieldTypeNameOk returns a tuple with the FieldTypeName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldTypeName

`func (o *CustomFieldsApiGetFieldDefinitionItem) SetFieldTypeName(v string)`

SetFieldTypeName sets FieldTypeName field to given value.

### HasFieldTypeName

`func (o *CustomFieldsApiGetFieldDefinitionItem) HasFieldTypeName() bool`

HasFieldTypeName returns a boolean if a field has been set.

### GetFieldName

`func (o *CustomFieldsApiGetFieldDefinitionItem) GetFieldName() string`

GetFieldName returns the FieldName field if non-nil, zero value otherwise.

### GetFieldNameOk

`func (o *CustomFieldsApiGetFieldDefinitionItem) GetFieldNameOk() (*string, bool)`

GetFieldNameOk returns a tuple with the FieldName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldName

`func (o *CustomFieldsApiGetFieldDefinitionItem) SetFieldName(v string)`

SetFieldName sets FieldName field to given value.

### HasFieldName

`func (o *CustomFieldsApiGetFieldDefinitionItem) HasFieldName() bool`

HasFieldName returns a boolean if a field has been set.

### GetFieldLabel

`func (o *CustomFieldsApiGetFieldDefinitionItem) GetFieldLabel() string`

GetFieldLabel returns the FieldLabel field if non-nil, zero value otherwise.

### GetFieldLabelOk

`func (o *CustomFieldsApiGetFieldDefinitionItem) GetFieldLabelOk() (*string, bool)`

GetFieldLabelOk returns a tuple with the FieldLabel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldLabel

`func (o *CustomFieldsApiGetFieldDefinitionItem) SetFieldLabel(v string)`

SetFieldLabel sets FieldLabel field to given value.

### HasFieldLabel

`func (o *CustomFieldsApiGetFieldDefinitionItem) HasFieldLabel() bool`

HasFieldLabel returns a boolean if a field has been set.

### GetDescription

`func (o *CustomFieldsApiGetFieldDefinitionItem) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CustomFieldsApiGetFieldDefinitionItem) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CustomFieldsApiGetFieldDefinitionItem) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CustomFieldsApiGetFieldDefinitionItem) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetConstraints

`func (o *CustomFieldsApiGetFieldDefinitionItem) GetConstraints() string`

GetConstraints returns the Constraints field if non-nil, zero value otherwise.

### GetConstraintsOk

`func (o *CustomFieldsApiGetFieldDefinitionItem) GetConstraintsOk() (*string, bool)`

GetConstraintsOk returns a tuple with the Constraints field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConstraints

`func (o *CustomFieldsApiGetFieldDefinitionItem) SetConstraints(v string)`

SetConstraints sets Constraints field to given value.

### HasConstraints

`func (o *CustomFieldsApiGetFieldDefinitionItem) HasConstraints() bool`

HasConstraints returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


