# CustomFieldsApiSearchFieldValuesRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**StandardObjectName** | Pointer to **string** | The name of the standard object that is used internally by the system. | [optional] 
**RecordIdentifiers** | Pointer to **[]map[string]interface{}** | A list of identity keys and their values that uniquely identify a standard object record. | [optional] 
**FieldValueSearchFilters** | Pointer to [**[]FieldValueSearchFiltersItem**](FieldValueSearchFiltersItem.md) | A list of custom fields and values on which to search, and the operation used to compare with the standard object resource&#39;s values. Allowed operations are &amp;gt;, &amp;lt;, &amp;gt;&#x3D;, &amp;lt;&#x3D;, &#x3D;, StartsWith, IsNull. | [optional] 
**FieldName** | Pointer to **string** | The name of the field definition that uniquely identifies the field within a standard object and is used internally by the system. | [optional] 
**Operation** | Pointer to **string** | The operation to use to compare the specified operand with the custom field values of standard objects. Allowed values are &amp;gt;, &amp;lt;, &amp;gt;&#x3D;, &amp;lt;&#x3D;, &#x3D;, StartsWith, IsNull. | [optional] 
**Operand** | Pointer to **string** | The value to compare using the specified operation with the custom field values of standard object records. | [optional] 

## Methods

### NewCustomFieldsApiSearchFieldValuesRequest

`func NewCustomFieldsApiSearchFieldValuesRequest() *CustomFieldsApiSearchFieldValuesRequest`

NewCustomFieldsApiSearchFieldValuesRequest instantiates a new CustomFieldsApiSearchFieldValuesRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomFieldsApiSearchFieldValuesRequestWithDefaults

`func NewCustomFieldsApiSearchFieldValuesRequestWithDefaults() *CustomFieldsApiSearchFieldValuesRequest`

NewCustomFieldsApiSearchFieldValuesRequestWithDefaults instantiates a new CustomFieldsApiSearchFieldValuesRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStandardObjectName

`func (o *CustomFieldsApiSearchFieldValuesRequest) GetStandardObjectName() string`

GetStandardObjectName returns the StandardObjectName field if non-nil, zero value otherwise.

### GetStandardObjectNameOk

`func (o *CustomFieldsApiSearchFieldValuesRequest) GetStandardObjectNameOk() (*string, bool)`

GetStandardObjectNameOk returns a tuple with the StandardObjectName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStandardObjectName

`func (o *CustomFieldsApiSearchFieldValuesRequest) SetStandardObjectName(v string)`

SetStandardObjectName sets StandardObjectName field to given value.

### HasStandardObjectName

`func (o *CustomFieldsApiSearchFieldValuesRequest) HasStandardObjectName() bool`

HasStandardObjectName returns a boolean if a field has been set.

### GetRecordIdentifiers

`func (o *CustomFieldsApiSearchFieldValuesRequest) GetRecordIdentifiers() []map[string]interface{}`

GetRecordIdentifiers returns the RecordIdentifiers field if non-nil, zero value otherwise.

### GetRecordIdentifiersOk

`func (o *CustomFieldsApiSearchFieldValuesRequest) GetRecordIdentifiersOk() (*[]map[string]interface{}, bool)`

GetRecordIdentifiersOk returns a tuple with the RecordIdentifiers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecordIdentifiers

`func (o *CustomFieldsApiSearchFieldValuesRequest) SetRecordIdentifiers(v []map[string]interface{})`

SetRecordIdentifiers sets RecordIdentifiers field to given value.

### HasRecordIdentifiers

`func (o *CustomFieldsApiSearchFieldValuesRequest) HasRecordIdentifiers() bool`

HasRecordIdentifiers returns a boolean if a field has been set.

### GetFieldValueSearchFilters

`func (o *CustomFieldsApiSearchFieldValuesRequest) GetFieldValueSearchFilters() []FieldValueSearchFiltersItem`

GetFieldValueSearchFilters returns the FieldValueSearchFilters field if non-nil, zero value otherwise.

### GetFieldValueSearchFiltersOk

`func (o *CustomFieldsApiSearchFieldValuesRequest) GetFieldValueSearchFiltersOk() (*[]FieldValueSearchFiltersItem, bool)`

GetFieldValueSearchFiltersOk returns a tuple with the FieldValueSearchFilters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldValueSearchFilters

`func (o *CustomFieldsApiSearchFieldValuesRequest) SetFieldValueSearchFilters(v []FieldValueSearchFiltersItem)`

SetFieldValueSearchFilters sets FieldValueSearchFilters field to given value.

### HasFieldValueSearchFilters

`func (o *CustomFieldsApiSearchFieldValuesRequest) HasFieldValueSearchFilters() bool`

HasFieldValueSearchFilters returns a boolean if a field has been set.

### GetFieldName

`func (o *CustomFieldsApiSearchFieldValuesRequest) GetFieldName() string`

GetFieldName returns the FieldName field if non-nil, zero value otherwise.

### GetFieldNameOk

`func (o *CustomFieldsApiSearchFieldValuesRequest) GetFieldNameOk() (*string, bool)`

GetFieldNameOk returns a tuple with the FieldName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldName

`func (o *CustomFieldsApiSearchFieldValuesRequest) SetFieldName(v string)`

SetFieldName sets FieldName field to given value.

### HasFieldName

`func (o *CustomFieldsApiSearchFieldValuesRequest) HasFieldName() bool`

HasFieldName returns a boolean if a field has been set.

### GetOperation

`func (o *CustomFieldsApiSearchFieldValuesRequest) GetOperation() string`

GetOperation returns the Operation field if non-nil, zero value otherwise.

### GetOperationOk

`func (o *CustomFieldsApiSearchFieldValuesRequest) GetOperationOk() (*string, bool)`

GetOperationOk returns a tuple with the Operation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperation

`func (o *CustomFieldsApiSearchFieldValuesRequest) SetOperation(v string)`

SetOperation sets Operation field to given value.

### HasOperation

`func (o *CustomFieldsApiSearchFieldValuesRequest) HasOperation() bool`

HasOperation returns a boolean if a field has been set.

### GetOperand

`func (o *CustomFieldsApiSearchFieldValuesRequest) GetOperand() string`

GetOperand returns the Operand field if non-nil, zero value otherwise.

### GetOperandOk

`func (o *CustomFieldsApiSearchFieldValuesRequest) GetOperandOk() (*string, bool)`

GetOperandOk returns a tuple with the Operand field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperand

`func (o *CustomFieldsApiSearchFieldValuesRequest) SetOperand(v string)`

SetOperand sets Operand field to given value.

### HasOperand

`func (o *CustomFieldsApiSearchFieldValuesRequest) HasOperand() bool`

HasOperand returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


