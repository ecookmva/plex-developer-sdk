# CustomObjectsApiListCustomObjectDataRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Ids** | Pointer to **[]string** | A list of ids that uniquely identify a custom object record. | [optional] 
**RecordIdentifiers** | Pointer to **[]int64** | A list of identity keys values that uniquely identify a custom object record. | [optional] 
**FieldValueSearchFilters** | Pointer to [**[]FieldValueSearchFiltersItem**](FieldValueSearchFiltersItem.md) | A list of custom fields and values on which to search, and the operation used to compare with the custom object resource&#39;s values. Allowed operations are &amp;gt;, &amp;lt;, &amp;gt;&#x3D;, &amp;lt;&#x3D;, &#x3D;, StartsWith, IsNull. | [optional] 
**FieldName** | Pointer to **string** | The name of the field definition that uniquely identifies the field within a standard object and is used internally by the system. | [optional] 
**Operation** | Pointer to **string** | The operation to use to compare the specified operand with the custom field values of standard objects. Allowed values are &amp;gt;, &amp;lt;, &amp;gt;&#x3D;, &amp;lt;&#x3D;, &#x3D;, StartsWith, IsNull. | [optional] 
**Operand** | Pointer to **string** | The value to compare using the specified operation with the custom field values of standard object records. | [optional] 

## Methods

### NewCustomObjectsApiListCustomObjectDataRequest

`func NewCustomObjectsApiListCustomObjectDataRequest() *CustomObjectsApiListCustomObjectDataRequest`

NewCustomObjectsApiListCustomObjectDataRequest instantiates a new CustomObjectsApiListCustomObjectDataRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomObjectsApiListCustomObjectDataRequestWithDefaults

`func NewCustomObjectsApiListCustomObjectDataRequestWithDefaults() *CustomObjectsApiListCustomObjectDataRequest`

NewCustomObjectsApiListCustomObjectDataRequestWithDefaults instantiates a new CustomObjectsApiListCustomObjectDataRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIds

`func (o *CustomObjectsApiListCustomObjectDataRequest) GetIds() []string`

GetIds returns the Ids field if non-nil, zero value otherwise.

### GetIdsOk

`func (o *CustomObjectsApiListCustomObjectDataRequest) GetIdsOk() (*[]string, bool)`

GetIdsOk returns a tuple with the Ids field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIds

`func (o *CustomObjectsApiListCustomObjectDataRequest) SetIds(v []string)`

SetIds sets Ids field to given value.

### HasIds

`func (o *CustomObjectsApiListCustomObjectDataRequest) HasIds() bool`

HasIds returns a boolean if a field has been set.

### GetRecordIdentifiers

`func (o *CustomObjectsApiListCustomObjectDataRequest) GetRecordIdentifiers() []int64`

GetRecordIdentifiers returns the RecordIdentifiers field if non-nil, zero value otherwise.

### GetRecordIdentifiersOk

`func (o *CustomObjectsApiListCustomObjectDataRequest) GetRecordIdentifiersOk() (*[]int64, bool)`

GetRecordIdentifiersOk returns a tuple with the RecordIdentifiers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecordIdentifiers

`func (o *CustomObjectsApiListCustomObjectDataRequest) SetRecordIdentifiers(v []int64)`

SetRecordIdentifiers sets RecordIdentifiers field to given value.

### HasRecordIdentifiers

`func (o *CustomObjectsApiListCustomObjectDataRequest) HasRecordIdentifiers() bool`

HasRecordIdentifiers returns a boolean if a field has been set.

### GetFieldValueSearchFilters

`func (o *CustomObjectsApiListCustomObjectDataRequest) GetFieldValueSearchFilters() []FieldValueSearchFiltersItem`

GetFieldValueSearchFilters returns the FieldValueSearchFilters field if non-nil, zero value otherwise.

### GetFieldValueSearchFiltersOk

`func (o *CustomObjectsApiListCustomObjectDataRequest) GetFieldValueSearchFiltersOk() (*[]FieldValueSearchFiltersItem, bool)`

GetFieldValueSearchFiltersOk returns a tuple with the FieldValueSearchFilters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldValueSearchFilters

`func (o *CustomObjectsApiListCustomObjectDataRequest) SetFieldValueSearchFilters(v []FieldValueSearchFiltersItem)`

SetFieldValueSearchFilters sets FieldValueSearchFilters field to given value.

### HasFieldValueSearchFilters

`func (o *CustomObjectsApiListCustomObjectDataRequest) HasFieldValueSearchFilters() bool`

HasFieldValueSearchFilters returns a boolean if a field has been set.

### GetFieldName

`func (o *CustomObjectsApiListCustomObjectDataRequest) GetFieldName() string`

GetFieldName returns the FieldName field if non-nil, zero value otherwise.

### GetFieldNameOk

`func (o *CustomObjectsApiListCustomObjectDataRequest) GetFieldNameOk() (*string, bool)`

GetFieldNameOk returns a tuple with the FieldName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldName

`func (o *CustomObjectsApiListCustomObjectDataRequest) SetFieldName(v string)`

SetFieldName sets FieldName field to given value.

### HasFieldName

`func (o *CustomObjectsApiListCustomObjectDataRequest) HasFieldName() bool`

HasFieldName returns a boolean if a field has been set.

### GetOperation

`func (o *CustomObjectsApiListCustomObjectDataRequest) GetOperation() string`

GetOperation returns the Operation field if non-nil, zero value otherwise.

### GetOperationOk

`func (o *CustomObjectsApiListCustomObjectDataRequest) GetOperationOk() (*string, bool)`

GetOperationOk returns a tuple with the Operation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperation

`func (o *CustomObjectsApiListCustomObjectDataRequest) SetOperation(v string)`

SetOperation sets Operation field to given value.

### HasOperation

`func (o *CustomObjectsApiListCustomObjectDataRequest) HasOperation() bool`

HasOperation returns a boolean if a field has been set.

### GetOperand

`func (o *CustomObjectsApiListCustomObjectDataRequest) GetOperand() string`

GetOperand returns the Operand field if non-nil, zero value otherwise.

### GetOperandOk

`func (o *CustomObjectsApiListCustomObjectDataRequest) GetOperandOk() (*string, bool)`

GetOperandOk returns a tuple with the Operand field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperand

`func (o *CustomObjectsApiListCustomObjectDataRequest) SetOperand(v string)`

SetOperand sets Operand field to given value.

### HasOperand

`func (o *CustomObjectsApiListCustomObjectDataRequest) HasOperand() bool`

HasOperand returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


