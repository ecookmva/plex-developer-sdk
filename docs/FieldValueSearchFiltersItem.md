# FieldValueSearchFiltersItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FieldName** | Pointer to **string** | The name of the field definition that uniquely identifies the field within a standard object and is used internally by the system. | [optional] 
**Operation** | Pointer to **string** | The operation to use to compare the specified operand with the custom field values of standard objects. Allowed values are &gt;, &#x3D;, &lt;&#x3D;, &#x3D;, StartsWith, IsNull. | [optional] 
**Operand** | Pointer to **string** | The value to compare using the specified operation with the custom field values of standard object records. | [optional] 

## Methods

### NewFieldValueSearchFiltersItem

`func NewFieldValueSearchFiltersItem() *FieldValueSearchFiltersItem`

NewFieldValueSearchFiltersItem instantiates a new FieldValueSearchFiltersItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFieldValueSearchFiltersItemWithDefaults

`func NewFieldValueSearchFiltersItemWithDefaults() *FieldValueSearchFiltersItem`

NewFieldValueSearchFiltersItemWithDefaults instantiates a new FieldValueSearchFiltersItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFieldName

`func (o *FieldValueSearchFiltersItem) GetFieldName() string`

GetFieldName returns the FieldName field if non-nil, zero value otherwise.

### GetFieldNameOk

`func (o *FieldValueSearchFiltersItem) GetFieldNameOk() (*string, bool)`

GetFieldNameOk returns a tuple with the FieldName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldName

`func (o *FieldValueSearchFiltersItem) SetFieldName(v string)`

SetFieldName sets FieldName field to given value.

### HasFieldName

`func (o *FieldValueSearchFiltersItem) HasFieldName() bool`

HasFieldName returns a boolean if a field has been set.

### GetOperation

`func (o *FieldValueSearchFiltersItem) GetOperation() string`

GetOperation returns the Operation field if non-nil, zero value otherwise.

### GetOperationOk

`func (o *FieldValueSearchFiltersItem) GetOperationOk() (*string, bool)`

GetOperationOk returns a tuple with the Operation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperation

`func (o *FieldValueSearchFiltersItem) SetOperation(v string)`

SetOperation sets Operation field to given value.

### HasOperation

`func (o *FieldValueSearchFiltersItem) HasOperation() bool`

HasOperation returns a boolean if a field has been set.

### GetOperand

`func (o *FieldValueSearchFiltersItem) GetOperand() string`

GetOperand returns the Operand field if non-nil, zero value otherwise.

### GetOperandOk

`func (o *FieldValueSearchFiltersItem) GetOperandOk() (*string, bool)`

GetOperandOk returns a tuple with the Operand field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperand

`func (o *FieldValueSearchFiltersItem) SetOperand(v string)`

SetOperand sets Operand field to given value.

### HasOperand

`func (o *FieldValueSearchFiltersItem) HasOperand() bool`

HasOperand returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


