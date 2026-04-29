# MetadataItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Field** | Pointer to **string** |  | [optional] 
**ProvidedValues** | Pointer to **[]string** |  | [optional] 
**ValidValues** | Pointer to **[]string** |  | [optional] 

## Methods

### NewMetadataItem

`func NewMetadataItem() *MetadataItem`

NewMetadataItem instantiates a new MetadataItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMetadataItemWithDefaults

`func NewMetadataItemWithDefaults() *MetadataItem`

NewMetadataItemWithDefaults instantiates a new MetadataItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetField

`func (o *MetadataItem) GetField() string`

GetField returns the Field field if non-nil, zero value otherwise.

### GetFieldOk

`func (o *MetadataItem) GetFieldOk() (*string, bool)`

GetFieldOk returns a tuple with the Field field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetField

`func (o *MetadataItem) SetField(v string)`

SetField sets Field field to given value.

### HasField

`func (o *MetadataItem) HasField() bool`

HasField returns a boolean if a field has been set.

### GetProvidedValues

`func (o *MetadataItem) GetProvidedValues() []string`

GetProvidedValues returns the ProvidedValues field if non-nil, zero value otherwise.

### GetProvidedValuesOk

`func (o *MetadataItem) GetProvidedValuesOk() (*[]string, bool)`

GetProvidedValuesOk returns a tuple with the ProvidedValues field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvidedValues

`func (o *MetadataItem) SetProvidedValues(v []string)`

SetProvidedValues sets ProvidedValues field to given value.

### HasProvidedValues

`func (o *MetadataItem) HasProvidedValues() bool`

HasProvidedValues returns a boolean if a field has been set.

### GetValidValues

`func (o *MetadataItem) GetValidValues() []string`

GetValidValues returns the ValidValues field if non-nil, zero value otherwise.

### GetValidValuesOk

`func (o *MetadataItem) GetValidValuesOk() (*[]string, bool)`

GetValidValuesOk returns a tuple with the ValidValues field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidValues

`func (o *MetadataItem) SetValidValues(v []string)`

SetValidValues sets ValidValues field to given value.

### HasValidValues

`func (o *MetadataItem) HasValidValues() bool`

HasValidValues returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


