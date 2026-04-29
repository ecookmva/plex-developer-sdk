# EdiApiGetWorkflowRunID400Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Code** | Pointer to **string** |  | [optional] 
**Message** | Pointer to **string** |  | [optional] 
**Errors** | Pointer to [**[]ErrorsItem**](ErrorsItem.md) |  | [optional] 

## Methods

### NewEdiApiGetWorkflowRunID400Response

`func NewEdiApiGetWorkflowRunID400Response() *EdiApiGetWorkflowRunID400Response`

NewEdiApiGetWorkflowRunID400Response instantiates a new EdiApiGetWorkflowRunID400Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEdiApiGetWorkflowRunID400ResponseWithDefaults

`func NewEdiApiGetWorkflowRunID400ResponseWithDefaults() *EdiApiGetWorkflowRunID400Response`

NewEdiApiGetWorkflowRunID400ResponseWithDefaults instantiates a new EdiApiGetWorkflowRunID400Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCode

`func (o *EdiApiGetWorkflowRunID400Response) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *EdiApiGetWorkflowRunID400Response) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *EdiApiGetWorkflowRunID400Response) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *EdiApiGetWorkflowRunID400Response) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetMessage

`func (o *EdiApiGetWorkflowRunID400Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *EdiApiGetWorkflowRunID400Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *EdiApiGetWorkflowRunID400Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *EdiApiGetWorkflowRunID400Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetErrors

`func (o *EdiApiGetWorkflowRunID400Response) GetErrors() []ErrorsItem`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *EdiApiGetWorkflowRunID400Response) GetErrorsOk() (*[]ErrorsItem, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *EdiApiGetWorkflowRunID400Response) SetErrors(v []ErrorsItem)`

SetErrors sets Errors field to given value.

### HasErrors

`func (o *EdiApiGetWorkflowRunID400Response) HasErrors() bool`

HasErrors returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


