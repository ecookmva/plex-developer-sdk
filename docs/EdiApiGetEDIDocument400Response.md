# EdiApiGetEDIDocument400Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Code** | Pointer to **string** |  | [optional] 
**Message** | Pointer to **string** |  | [optional] 
**Errors** | Pointer to [**[]ErrorsItem**](ErrorsItem.md) |  | [optional] 

## Methods

### NewEdiApiGetEDIDocument400Response

`func NewEdiApiGetEDIDocument400Response() *EdiApiGetEDIDocument400Response`

NewEdiApiGetEDIDocument400Response instantiates a new EdiApiGetEDIDocument400Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEdiApiGetEDIDocument400ResponseWithDefaults

`func NewEdiApiGetEDIDocument400ResponseWithDefaults() *EdiApiGetEDIDocument400Response`

NewEdiApiGetEDIDocument400ResponseWithDefaults instantiates a new EdiApiGetEDIDocument400Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCode

`func (o *EdiApiGetEDIDocument400Response) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *EdiApiGetEDIDocument400Response) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *EdiApiGetEDIDocument400Response) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *EdiApiGetEDIDocument400Response) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetMessage

`func (o *EdiApiGetEDIDocument400Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *EdiApiGetEDIDocument400Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *EdiApiGetEDIDocument400Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *EdiApiGetEDIDocument400Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetErrors

`func (o *EdiApiGetEDIDocument400Response) GetErrors() []ErrorsItem`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *EdiApiGetEDIDocument400Response) GetErrorsOk() (*[]ErrorsItem, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *EdiApiGetEDIDocument400Response) SetErrors(v []ErrorsItem)`

SetErrors sets Errors field to given value.

### HasErrors

`func (o *EdiApiGetEDIDocument400Response) HasErrors() bool`

HasErrors returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


