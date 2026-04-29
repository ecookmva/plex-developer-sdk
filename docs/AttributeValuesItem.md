# AttributeValuesItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AttributeValue** | Pointer to **string** | A value of the Equipment Attribute. | [optional] 
**SortOrder** | Pointer to **int32** | The sort order for the Equipment Attribute Value. | [optional] 

## Methods

### NewAttributeValuesItem

`func NewAttributeValuesItem() *AttributeValuesItem`

NewAttributeValuesItem instantiates a new AttributeValuesItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAttributeValuesItemWithDefaults

`func NewAttributeValuesItemWithDefaults() *AttributeValuesItem`

NewAttributeValuesItemWithDefaults instantiates a new AttributeValuesItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAttributeValue

`func (o *AttributeValuesItem) GetAttributeValue() string`

GetAttributeValue returns the AttributeValue field if non-nil, zero value otherwise.

### GetAttributeValueOk

`func (o *AttributeValuesItem) GetAttributeValueOk() (*string, bool)`

GetAttributeValueOk returns a tuple with the AttributeValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttributeValue

`func (o *AttributeValuesItem) SetAttributeValue(v string)`

SetAttributeValue sets AttributeValue field to given value.

### HasAttributeValue

`func (o *AttributeValuesItem) HasAttributeValue() bool`

HasAttributeValue returns a boolean if a field has been set.

### GetSortOrder

`func (o *AttributeValuesItem) GetSortOrder() int32`

GetSortOrder returns the SortOrder field if non-nil, zero value otherwise.

### GetSortOrderOk

`func (o *AttributeValuesItem) GetSortOrderOk() (*int32, bool)`

GetSortOrderOk returns a tuple with the SortOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSortOrder

`func (o *AttributeValuesItem) SetSortOrder(v int32)`

SetSortOrder sets SortOrder field to given value.

### HasSortOrder

`func (o *AttributeValuesItem) HasSortOrder() bool`

HasSortOrder returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


