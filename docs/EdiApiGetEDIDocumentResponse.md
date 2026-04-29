# EdiApiGetEDIDocumentResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | A unique identifier for the Log. | [optional] 
**RawDocument** | Pointer to **string** | Contains the segment data encoded in Base64. | [optional] 
**SegmentTerminator** | Pointer to **string** | The ASCII value used to end segments. | [optional] 

## Methods

### NewEdiApiGetEDIDocumentResponse

`func NewEdiApiGetEDIDocumentResponse() *EdiApiGetEDIDocumentResponse`

NewEdiApiGetEDIDocumentResponse instantiates a new EdiApiGetEDIDocumentResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEdiApiGetEDIDocumentResponseWithDefaults

`func NewEdiApiGetEDIDocumentResponseWithDefaults() *EdiApiGetEDIDocumentResponse`

NewEdiApiGetEDIDocumentResponseWithDefaults instantiates a new EdiApiGetEDIDocumentResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *EdiApiGetEDIDocumentResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *EdiApiGetEDIDocumentResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *EdiApiGetEDIDocumentResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *EdiApiGetEDIDocumentResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetRawDocument

`func (o *EdiApiGetEDIDocumentResponse) GetRawDocument() string`

GetRawDocument returns the RawDocument field if non-nil, zero value otherwise.

### GetRawDocumentOk

`func (o *EdiApiGetEDIDocumentResponse) GetRawDocumentOk() (*string, bool)`

GetRawDocumentOk returns a tuple with the RawDocument field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRawDocument

`func (o *EdiApiGetEDIDocumentResponse) SetRawDocument(v string)`

SetRawDocument sets RawDocument field to given value.

### HasRawDocument

`func (o *EdiApiGetEDIDocumentResponse) HasRawDocument() bool`

HasRawDocument returns a boolean if a field has been set.

### GetSegmentTerminator

`func (o *EdiApiGetEDIDocumentResponse) GetSegmentTerminator() string`

GetSegmentTerminator returns the SegmentTerminator field if non-nil, zero value otherwise.

### GetSegmentTerminatorOk

`func (o *EdiApiGetEDIDocumentResponse) GetSegmentTerminatorOk() (*string, bool)`

GetSegmentTerminatorOk returns a tuple with the SegmentTerminator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSegmentTerminator

`func (o *EdiApiGetEDIDocumentResponse) SetSegmentTerminator(v string)`

SetSegmentTerminator sets SegmentTerminator field to given value.

### HasSegmentTerminator

`func (o *EdiApiGetEDIDocumentResponse) HasSegmentTerminator() bool`

HasSegmentTerminator returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


