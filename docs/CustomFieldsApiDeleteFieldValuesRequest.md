# CustomFieldsApiDeleteFieldValuesRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**StandardObjectName** | Pointer to **string** | The name of the standard object that is used internally by the system. | [optional] 
**RecordIdentifiers** | Pointer to **map[string]interface{}** | A list of identity keys and their values that uniquely identify a standard object record. | [optional] 

## Methods

### NewCustomFieldsApiDeleteFieldValuesRequest

`func NewCustomFieldsApiDeleteFieldValuesRequest() *CustomFieldsApiDeleteFieldValuesRequest`

NewCustomFieldsApiDeleteFieldValuesRequest instantiates a new CustomFieldsApiDeleteFieldValuesRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomFieldsApiDeleteFieldValuesRequestWithDefaults

`func NewCustomFieldsApiDeleteFieldValuesRequestWithDefaults() *CustomFieldsApiDeleteFieldValuesRequest`

NewCustomFieldsApiDeleteFieldValuesRequestWithDefaults instantiates a new CustomFieldsApiDeleteFieldValuesRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStandardObjectName

`func (o *CustomFieldsApiDeleteFieldValuesRequest) GetStandardObjectName() string`

GetStandardObjectName returns the StandardObjectName field if non-nil, zero value otherwise.

### GetStandardObjectNameOk

`func (o *CustomFieldsApiDeleteFieldValuesRequest) GetStandardObjectNameOk() (*string, bool)`

GetStandardObjectNameOk returns a tuple with the StandardObjectName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStandardObjectName

`func (o *CustomFieldsApiDeleteFieldValuesRequest) SetStandardObjectName(v string)`

SetStandardObjectName sets StandardObjectName field to given value.

### HasStandardObjectName

`func (o *CustomFieldsApiDeleteFieldValuesRequest) HasStandardObjectName() bool`

HasStandardObjectName returns a boolean if a field has been set.

### GetRecordIdentifiers

`func (o *CustomFieldsApiDeleteFieldValuesRequest) GetRecordIdentifiers() map[string]interface{}`

GetRecordIdentifiers returns the RecordIdentifiers field if non-nil, zero value otherwise.

### GetRecordIdentifiersOk

`func (o *CustomFieldsApiDeleteFieldValuesRequest) GetRecordIdentifiersOk() (*map[string]interface{}, bool)`

GetRecordIdentifiersOk returns a tuple with the RecordIdentifiers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecordIdentifiers

`func (o *CustomFieldsApiDeleteFieldValuesRequest) SetRecordIdentifiers(v map[string]interface{})`

SetRecordIdentifiers sets RecordIdentifiers field to given value.

### HasRecordIdentifiers

`func (o *CustomFieldsApiDeleteFieldValuesRequest) HasRecordIdentifiers() bool`

HasRecordIdentifiers returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


