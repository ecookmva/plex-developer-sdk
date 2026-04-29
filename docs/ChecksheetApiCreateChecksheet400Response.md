# ChecksheetApiCreateChecksheet400Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Code** | Pointer to **string** |  | [optional] 
**Message** | Pointer to **string** |  | [optional] 
**Errors** | Pointer to [**[]ErrorsItem**](ErrorsItem.md) |  | [optional] 

## Methods

### NewChecksheetApiCreateChecksheet400Response

`func NewChecksheetApiCreateChecksheet400Response() *ChecksheetApiCreateChecksheet400Response`

NewChecksheetApiCreateChecksheet400Response instantiates a new ChecksheetApiCreateChecksheet400Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChecksheetApiCreateChecksheet400ResponseWithDefaults

`func NewChecksheetApiCreateChecksheet400ResponseWithDefaults() *ChecksheetApiCreateChecksheet400Response`

NewChecksheetApiCreateChecksheet400ResponseWithDefaults instantiates a new ChecksheetApiCreateChecksheet400Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCode

`func (o *ChecksheetApiCreateChecksheet400Response) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *ChecksheetApiCreateChecksheet400Response) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *ChecksheetApiCreateChecksheet400Response) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *ChecksheetApiCreateChecksheet400Response) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetMessage

`func (o *ChecksheetApiCreateChecksheet400Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *ChecksheetApiCreateChecksheet400Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *ChecksheetApiCreateChecksheet400Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *ChecksheetApiCreateChecksheet400Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetErrors

`func (o *ChecksheetApiCreateChecksheet400Response) GetErrors() []ErrorsItem`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *ChecksheetApiCreateChecksheet400Response) GetErrorsOk() (*[]ErrorsItem, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *ChecksheetApiCreateChecksheet400Response) SetErrors(v []ErrorsItem)`

SetErrors sets Errors field to given value.

### HasErrors

`func (o *ChecksheetApiCreateChecksheet400Response) HasErrors() bool`

HasErrors returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


