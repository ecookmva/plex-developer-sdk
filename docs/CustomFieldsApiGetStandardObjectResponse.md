# CustomFieldsApiGetStandardObjectResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**StandardObjectName** | Pointer to **string** | The name of the standard object that is used internally by the system. | [optional] 
**StandardObjectLabel** | Pointer to **string** | The display name of the standard object that is used as a label on forms within Plex and on printed documents. | [optional] 
**TableName** | Pointer to **string** | The name of the table that a standard object represents. | [optional] 
**RecordIdentifiers** | Pointer to [**RecordIdentifiers**](RecordIdentifiers.md) |  | [optional] 

## Methods

### NewCustomFieldsApiGetStandardObjectResponse

`func NewCustomFieldsApiGetStandardObjectResponse() *CustomFieldsApiGetStandardObjectResponse`

NewCustomFieldsApiGetStandardObjectResponse instantiates a new CustomFieldsApiGetStandardObjectResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomFieldsApiGetStandardObjectResponseWithDefaults

`func NewCustomFieldsApiGetStandardObjectResponseWithDefaults() *CustomFieldsApiGetStandardObjectResponse`

NewCustomFieldsApiGetStandardObjectResponseWithDefaults instantiates a new CustomFieldsApiGetStandardObjectResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStandardObjectName

`func (o *CustomFieldsApiGetStandardObjectResponse) GetStandardObjectName() string`

GetStandardObjectName returns the StandardObjectName field if non-nil, zero value otherwise.

### GetStandardObjectNameOk

`func (o *CustomFieldsApiGetStandardObjectResponse) GetStandardObjectNameOk() (*string, bool)`

GetStandardObjectNameOk returns a tuple with the StandardObjectName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStandardObjectName

`func (o *CustomFieldsApiGetStandardObjectResponse) SetStandardObjectName(v string)`

SetStandardObjectName sets StandardObjectName field to given value.

### HasStandardObjectName

`func (o *CustomFieldsApiGetStandardObjectResponse) HasStandardObjectName() bool`

HasStandardObjectName returns a boolean if a field has been set.

### GetStandardObjectLabel

`func (o *CustomFieldsApiGetStandardObjectResponse) GetStandardObjectLabel() string`

GetStandardObjectLabel returns the StandardObjectLabel field if non-nil, zero value otherwise.

### GetStandardObjectLabelOk

`func (o *CustomFieldsApiGetStandardObjectResponse) GetStandardObjectLabelOk() (*string, bool)`

GetStandardObjectLabelOk returns a tuple with the StandardObjectLabel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStandardObjectLabel

`func (o *CustomFieldsApiGetStandardObjectResponse) SetStandardObjectLabel(v string)`

SetStandardObjectLabel sets StandardObjectLabel field to given value.

### HasStandardObjectLabel

`func (o *CustomFieldsApiGetStandardObjectResponse) HasStandardObjectLabel() bool`

HasStandardObjectLabel returns a boolean if a field has been set.

### GetTableName

`func (o *CustomFieldsApiGetStandardObjectResponse) GetTableName() string`

GetTableName returns the TableName field if non-nil, zero value otherwise.

### GetTableNameOk

`func (o *CustomFieldsApiGetStandardObjectResponse) GetTableNameOk() (*string, bool)`

GetTableNameOk returns a tuple with the TableName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTableName

`func (o *CustomFieldsApiGetStandardObjectResponse) SetTableName(v string)`

SetTableName sets TableName field to given value.

### HasTableName

`func (o *CustomFieldsApiGetStandardObjectResponse) HasTableName() bool`

HasTableName returns a boolean if a field has been set.

### GetRecordIdentifiers

`func (o *CustomFieldsApiGetStandardObjectResponse) GetRecordIdentifiers() RecordIdentifiers`

GetRecordIdentifiers returns the RecordIdentifiers field if non-nil, zero value otherwise.

### GetRecordIdentifiersOk

`func (o *CustomFieldsApiGetStandardObjectResponse) GetRecordIdentifiersOk() (*RecordIdentifiers, bool)`

GetRecordIdentifiersOk returns a tuple with the RecordIdentifiers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecordIdentifiers

`func (o *CustomFieldsApiGetStandardObjectResponse) SetRecordIdentifiers(v RecordIdentifiers)`

SetRecordIdentifiers sets RecordIdentifiers field to given value.

### HasRecordIdentifiers

`func (o *CustomFieldsApiGetStandardObjectResponse) HasRecordIdentifiers() bool`

HasRecordIdentifiers returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


