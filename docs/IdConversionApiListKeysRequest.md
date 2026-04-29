# IdConversionApiListKeysRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**StandardObjectName** | Pointer to **string** | The name of the standard object that is used internally by the system. | [optional] 
**Ids** | Pointer to **[]string** | A list of unique identifiers for the standard object record. | [optional] 

## Methods

### NewIdConversionApiListKeysRequest

`func NewIdConversionApiListKeysRequest() *IdConversionApiListKeysRequest`

NewIdConversionApiListKeysRequest instantiates a new IdConversionApiListKeysRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIdConversionApiListKeysRequestWithDefaults

`func NewIdConversionApiListKeysRequestWithDefaults() *IdConversionApiListKeysRequest`

NewIdConversionApiListKeysRequestWithDefaults instantiates a new IdConversionApiListKeysRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStandardObjectName

`func (o *IdConversionApiListKeysRequest) GetStandardObjectName() string`

GetStandardObjectName returns the StandardObjectName field if non-nil, zero value otherwise.

### GetStandardObjectNameOk

`func (o *IdConversionApiListKeysRequest) GetStandardObjectNameOk() (*string, bool)`

GetStandardObjectNameOk returns a tuple with the StandardObjectName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStandardObjectName

`func (o *IdConversionApiListKeysRequest) SetStandardObjectName(v string)`

SetStandardObjectName sets StandardObjectName field to given value.

### HasStandardObjectName

`func (o *IdConversionApiListKeysRequest) HasStandardObjectName() bool`

HasStandardObjectName returns a boolean if a field has been set.

### GetIds

`func (o *IdConversionApiListKeysRequest) GetIds() []string`

GetIds returns the Ids field if non-nil, zero value otherwise.

### GetIdsOk

`func (o *IdConversionApiListKeysRequest) GetIdsOk() (*[]string, bool)`

GetIdsOk returns a tuple with the Ids field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIds

`func (o *IdConversionApiListKeysRequest) SetIds(v []string)`

SetIds sets Ids field to given value.

### HasIds

`func (o *IdConversionApiListKeysRequest) HasIds() bool`

HasIds returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


