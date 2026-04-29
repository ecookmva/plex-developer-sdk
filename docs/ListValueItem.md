# ListValueItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | Pointer to **string** | Designates the value of the list item. | [optional] 
**Success** | Pointer to **bool** | Designates the item as a successful path, if applicable. | [optional] 
**Default** | Pointer to **bool** | Designates the default selected list item. | [optional] 

## Methods

### NewListValueItem

`func NewListValueItem() *ListValueItem`

NewListValueItem instantiates a new ListValueItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListValueItemWithDefaults

`func NewListValueItemWithDefaults() *ListValueItem`

NewListValueItemWithDefaults instantiates a new ListValueItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetValue

`func (o *ListValueItem) GetValue() string`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *ListValueItem) GetValueOk() (*string, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *ListValueItem) SetValue(v string)`

SetValue sets Value field to given value.

### HasValue

`func (o *ListValueItem) HasValue() bool`

HasValue returns a boolean if a field has been set.

### GetSuccess

`func (o *ListValueItem) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *ListValueItem) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *ListValueItem) SetSuccess(v bool)`

SetSuccess sets Success field to given value.

### HasSuccess

`func (o *ListValueItem) HasSuccess() bool`

HasSuccess returns a boolean if a field has been set.

### GetDefault

`func (o *ListValueItem) GetDefault() bool`

GetDefault returns the Default field if non-nil, zero value otherwise.

### GetDefaultOk

`func (o *ListValueItem) GetDefaultOk() (*bool, bool)`

GetDefaultOk returns a tuple with the Default field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefault

`func (o *ListValueItem) SetDefault(v bool)`

SetDefault sets Default field to given value.

### HasDefault

`func (o *ListValueItem) HasDefault() bool`

HasDefault returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


