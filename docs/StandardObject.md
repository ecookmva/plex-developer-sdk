# StandardObject

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** |  | [optional] 
**Keys** | Pointer to **[]interface{}** |  | [optional] 

## Methods

### NewStandardObject

`func NewStandardObject() *StandardObject`

NewStandardObject instantiates a new StandardObject object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStandardObjectWithDefaults

`func NewStandardObjectWithDefaults() *StandardObject`

NewStandardObjectWithDefaults instantiates a new StandardObject object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *StandardObject) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *StandardObject) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *StandardObject) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *StandardObject) HasName() bool`

HasName returns a boolean if a field has been set.

### GetKeys

`func (o *StandardObject) GetKeys() []interface{}`

GetKeys returns the Keys field if non-nil, zero value otherwise.

### GetKeysOk

`func (o *StandardObject) GetKeysOk() (*[]interface{}, bool)`

GetKeysOk returns a tuple with the Keys field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeys

`func (o *StandardObject) SetKeys(v []interface{})`

SetKeys sets Keys field to given value.

### HasKeys

`func (o *StandardObject) HasKeys() bool`

HasKeys returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


