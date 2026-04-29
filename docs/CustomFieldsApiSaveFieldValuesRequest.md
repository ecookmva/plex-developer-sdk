# CustomFieldsApiSaveFieldValuesRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**StandardObjectName** | Pointer to **string** | The name of the standard object that is used internally by the system. | [optional] 
**RecordIdentifiers** | Pointer to **map[string]interface{}** | A list of identity keys and their values that uniquely identify a standard object record. | [optional] 
**CustomFields** | Pointer to **map[string]interface{}** | The custom fields and values that have been saved to a standard object resource. The customFields property is an object with a schema derived from the relevant custom fields. Each property is the name of a custom field (not case sensitive) with a corresponding value matching the custom field&#39;s type. Custom Field Type to JSON Type Mapping  Boolean - boolean Custom Object Reference -  object Date - string(date) Date Time - string(date-time) Decimal - number(double) Integer - integer(int64) Standard Object Reference - object Text - string Time - string(time)  Custom Object Reference Format Custom Object References are always returned to the client as an object with three properties OR null. Properties  id - string(uuid) - The uuid used to uniquely identify a custom object record. recordIdentifier - integer(int64) - The value used to uniquely identify a custom object record. displayValue - string - This is either the object&#39;s Primary Field (when specified) or the object&#39;s first field.  When adding or updating a custom object reference, several formats can be used.  A string(uuid) representing the record&#39;s ID.  Example {   &amp;quot;customFields&amp;quot;: {     &amp;quot;MyCustomObjectReference&amp;quot;: &amp;quot;d13023f2-9841-4439-8f8b-2d75ef3e87f4&amp;quot;   } }   A integer(int64) representing a record identifier.  Example {   &amp;quot;customFields&amp;quot;: {     &amp;quot;MyCustomObjectReference&amp;quot;: 15   } }   An object with either a recordIdentifier or id property. Additional properties (such as displayName) are ignored with write operations.  Example {   &amp;quot;customFields&amp;quot;: {     &amp;quot;MyCustomObjectReference&amp;quot;: {       &amp;quot;recordIdentifier&amp;quot;: 15,       &amp;quot;id&amp;quot;: &amp;quot;d13023f2-9841-4439-8f8b-2d75ef3e87f4&amp;quot;,       &amp;quot;displayValue&amp;quot;: &amp;quot;Blue&amp;quot;     }   } }  Standard Object Reference Format Standard Object References are always returned to the client as an object with two properties OR null. Properties  recordIdentifiers - object - An object of identity keys and their values that uniquely identify a standard object record.  This object has a schema that is derived from the identifiers used by the referenced standard object. For example, the Part standard object has a single identifier named Part_Key. displayValue -  string - The human readable text used to represent the referenced record. This value alone may not uniquely identify a record.  When adding or updating a standard object reference, several formats can be used.  An object with the proper recordIdentifiers object. Additional properties (such as displayName) are ignored with write operations.  Example {   &amp;quot;customFields&amp;quot;: {     &amp;quot;MyPartReference&amp;quot;: {       &amp;quot;recordIdentifiers&amp;quot;: {         &amp;quot;Part_Key&amp;quot;: 1234       },       &amp;quot;displayValue&amp;quot;: &amp;quot;4799-AAA&amp;quot;     }   } }   When the referenced object only has one identifier, the single value may be used.  Example {   &amp;quot;customFields&amp;quot;: {     &amp;quot;MyPartReference&amp;quot;: 1234   } } | [optional] 

## Methods

### NewCustomFieldsApiSaveFieldValuesRequest

`func NewCustomFieldsApiSaveFieldValuesRequest() *CustomFieldsApiSaveFieldValuesRequest`

NewCustomFieldsApiSaveFieldValuesRequest instantiates a new CustomFieldsApiSaveFieldValuesRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomFieldsApiSaveFieldValuesRequestWithDefaults

`func NewCustomFieldsApiSaveFieldValuesRequestWithDefaults() *CustomFieldsApiSaveFieldValuesRequest`

NewCustomFieldsApiSaveFieldValuesRequestWithDefaults instantiates a new CustomFieldsApiSaveFieldValuesRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStandardObjectName

`func (o *CustomFieldsApiSaveFieldValuesRequest) GetStandardObjectName() string`

GetStandardObjectName returns the StandardObjectName field if non-nil, zero value otherwise.

### GetStandardObjectNameOk

`func (o *CustomFieldsApiSaveFieldValuesRequest) GetStandardObjectNameOk() (*string, bool)`

GetStandardObjectNameOk returns a tuple with the StandardObjectName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStandardObjectName

`func (o *CustomFieldsApiSaveFieldValuesRequest) SetStandardObjectName(v string)`

SetStandardObjectName sets StandardObjectName field to given value.

### HasStandardObjectName

`func (o *CustomFieldsApiSaveFieldValuesRequest) HasStandardObjectName() bool`

HasStandardObjectName returns a boolean if a field has been set.

### GetRecordIdentifiers

`func (o *CustomFieldsApiSaveFieldValuesRequest) GetRecordIdentifiers() map[string]interface{}`

GetRecordIdentifiers returns the RecordIdentifiers field if non-nil, zero value otherwise.

### GetRecordIdentifiersOk

`func (o *CustomFieldsApiSaveFieldValuesRequest) GetRecordIdentifiersOk() (*map[string]interface{}, bool)`

GetRecordIdentifiersOk returns a tuple with the RecordIdentifiers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecordIdentifiers

`func (o *CustomFieldsApiSaveFieldValuesRequest) SetRecordIdentifiers(v map[string]interface{})`

SetRecordIdentifiers sets RecordIdentifiers field to given value.

### HasRecordIdentifiers

`func (o *CustomFieldsApiSaveFieldValuesRequest) HasRecordIdentifiers() bool`

HasRecordIdentifiers returns a boolean if a field has been set.

### GetCustomFields

`func (o *CustomFieldsApiSaveFieldValuesRequest) GetCustomFields() map[string]interface{}`

GetCustomFields returns the CustomFields field if non-nil, zero value otherwise.

### GetCustomFieldsOk

`func (o *CustomFieldsApiSaveFieldValuesRequest) GetCustomFieldsOk() (*map[string]interface{}, bool)`

GetCustomFieldsOk returns a tuple with the CustomFields field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomFields

`func (o *CustomFieldsApiSaveFieldValuesRequest) SetCustomFields(v map[string]interface{})`

SetCustomFields sets CustomFields field to given value.

### HasCustomFields

`func (o *CustomFieldsApiSaveFieldValuesRequest) HasCustomFields() bool`

HasCustomFields returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


