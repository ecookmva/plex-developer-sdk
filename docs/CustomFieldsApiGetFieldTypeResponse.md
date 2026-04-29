# CustomFieldsApiGetFieldTypeResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FieldTypeName** | Pointer to **string** | The name of the data type used internally by the system. | [optional] 
**FieldTypeLabel** | Pointer to **string** | The display name of the data type that is used as a label on forms within Plex. | [optional] 
**AvailableConstraints** | Pointer to [**AvailableConstraints**](AvailableConstraints.md) |  | [optional] 

## Methods

### NewCustomFieldsApiGetFieldTypeResponse

`func NewCustomFieldsApiGetFieldTypeResponse() *CustomFieldsApiGetFieldTypeResponse`

NewCustomFieldsApiGetFieldTypeResponse instantiates a new CustomFieldsApiGetFieldTypeResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomFieldsApiGetFieldTypeResponseWithDefaults

`func NewCustomFieldsApiGetFieldTypeResponseWithDefaults() *CustomFieldsApiGetFieldTypeResponse`

NewCustomFieldsApiGetFieldTypeResponseWithDefaults instantiates a new CustomFieldsApiGetFieldTypeResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFieldTypeName

`func (o *CustomFieldsApiGetFieldTypeResponse) GetFieldTypeName() string`

GetFieldTypeName returns the FieldTypeName field if non-nil, zero value otherwise.

### GetFieldTypeNameOk

`func (o *CustomFieldsApiGetFieldTypeResponse) GetFieldTypeNameOk() (*string, bool)`

GetFieldTypeNameOk returns a tuple with the FieldTypeName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldTypeName

`func (o *CustomFieldsApiGetFieldTypeResponse) SetFieldTypeName(v string)`

SetFieldTypeName sets FieldTypeName field to given value.

### HasFieldTypeName

`func (o *CustomFieldsApiGetFieldTypeResponse) HasFieldTypeName() bool`

HasFieldTypeName returns a boolean if a field has been set.

### GetFieldTypeLabel

`func (o *CustomFieldsApiGetFieldTypeResponse) GetFieldTypeLabel() string`

GetFieldTypeLabel returns the FieldTypeLabel field if non-nil, zero value otherwise.

### GetFieldTypeLabelOk

`func (o *CustomFieldsApiGetFieldTypeResponse) GetFieldTypeLabelOk() (*string, bool)`

GetFieldTypeLabelOk returns a tuple with the FieldTypeLabel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldTypeLabel

`func (o *CustomFieldsApiGetFieldTypeResponse) SetFieldTypeLabel(v string)`

SetFieldTypeLabel sets FieldTypeLabel field to given value.

### HasFieldTypeLabel

`func (o *CustomFieldsApiGetFieldTypeResponse) HasFieldTypeLabel() bool`

HasFieldTypeLabel returns a boolean if a field has been set.

### GetAvailableConstraints

`func (o *CustomFieldsApiGetFieldTypeResponse) GetAvailableConstraints() AvailableConstraints`

GetAvailableConstraints returns the AvailableConstraints field if non-nil, zero value otherwise.

### GetAvailableConstraintsOk

`func (o *CustomFieldsApiGetFieldTypeResponse) GetAvailableConstraintsOk() (*AvailableConstraints, bool)`

GetAvailableConstraintsOk returns a tuple with the AvailableConstraints field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailableConstraints

`func (o *CustomFieldsApiGetFieldTypeResponse) SetAvailableConstraints(v AvailableConstraints)`

SetAvailableConstraints sets AvailableConstraints field to given value.

### HasAvailableConstraints

`func (o *CustomFieldsApiGetFieldTypeResponse) HasAvailableConstraints() bool`

HasAvailableConstraints returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


