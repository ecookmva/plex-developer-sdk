# EdiApiCreateDocumentRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RawDocument** | Pointer to **string** | The base 64 encoded raw EDI document to be parsed for the given standard and document type. | [optional] 
**Standard** | Pointer to **string** | The EDI document standard for this document (i.e. X12, EDIFACT). | [optional] 

## Methods

### NewEdiApiCreateDocumentRequest

`func NewEdiApiCreateDocumentRequest() *EdiApiCreateDocumentRequest`

NewEdiApiCreateDocumentRequest instantiates a new EdiApiCreateDocumentRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEdiApiCreateDocumentRequestWithDefaults

`func NewEdiApiCreateDocumentRequestWithDefaults() *EdiApiCreateDocumentRequest`

NewEdiApiCreateDocumentRequestWithDefaults instantiates a new EdiApiCreateDocumentRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRawDocument

`func (o *EdiApiCreateDocumentRequest) GetRawDocument() string`

GetRawDocument returns the RawDocument field if non-nil, zero value otherwise.

### GetRawDocumentOk

`func (o *EdiApiCreateDocumentRequest) GetRawDocumentOk() (*string, bool)`

GetRawDocumentOk returns a tuple with the RawDocument field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRawDocument

`func (o *EdiApiCreateDocumentRequest) SetRawDocument(v string)`

SetRawDocument sets RawDocument field to given value.

### HasRawDocument

`func (o *EdiApiCreateDocumentRequest) HasRawDocument() bool`

HasRawDocument returns a boolean if a field has been set.

### GetStandard

`func (o *EdiApiCreateDocumentRequest) GetStandard() string`

GetStandard returns the Standard field if non-nil, zero value otherwise.

### GetStandardOk

`func (o *EdiApiCreateDocumentRequest) GetStandardOk() (*string, bool)`

GetStandardOk returns a tuple with the Standard field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStandard

`func (o *EdiApiCreateDocumentRequest) SetStandard(v string)`

SetStandard sets Standard field to given value.

### HasStandard

`func (o *EdiApiCreateDocumentRequest) HasStandard() bool`

HasStandard returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


