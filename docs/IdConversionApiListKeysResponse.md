# IdConversionApiListKeysResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**StandardObject** | Pointer to [**StandardObject**](StandardObject.md) |  | [optional] 
**RecordIdentifiers** | Pointer to **[]map[string]interface{}** | A list of identity keys, IDs and their corresponding values that uniquely identify a standard object record. | [optional] 

## Methods

### NewIdConversionApiListKeysResponse

`func NewIdConversionApiListKeysResponse() *IdConversionApiListKeysResponse`

NewIdConversionApiListKeysResponse instantiates a new IdConversionApiListKeysResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIdConversionApiListKeysResponseWithDefaults

`func NewIdConversionApiListKeysResponseWithDefaults() *IdConversionApiListKeysResponse`

NewIdConversionApiListKeysResponseWithDefaults instantiates a new IdConversionApiListKeysResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStandardObject

`func (o *IdConversionApiListKeysResponse) GetStandardObject() StandardObject`

GetStandardObject returns the StandardObject field if non-nil, zero value otherwise.

### GetStandardObjectOk

`func (o *IdConversionApiListKeysResponse) GetStandardObjectOk() (*StandardObject, bool)`

GetStandardObjectOk returns a tuple with the StandardObject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStandardObject

`func (o *IdConversionApiListKeysResponse) SetStandardObject(v StandardObject)`

SetStandardObject sets StandardObject field to given value.

### HasStandardObject

`func (o *IdConversionApiListKeysResponse) HasStandardObject() bool`

HasStandardObject returns a boolean if a field has been set.

### GetRecordIdentifiers

`func (o *IdConversionApiListKeysResponse) GetRecordIdentifiers() []map[string]interface{}`

GetRecordIdentifiers returns the RecordIdentifiers field if non-nil, zero value otherwise.

### GetRecordIdentifiersOk

`func (o *IdConversionApiListKeysResponse) GetRecordIdentifiersOk() (*[]map[string]interface{}, bool)`

GetRecordIdentifiersOk returns a tuple with the RecordIdentifiers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecordIdentifiers

`func (o *IdConversionApiListKeysResponse) SetRecordIdentifiers(v []map[string]interface{})`

SetRecordIdentifiers sets RecordIdentifiers field to given value.

### HasRecordIdentifiers

`func (o *IdConversionApiListKeysResponse) HasRecordIdentifiers() bool`

HasRecordIdentifiers returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


