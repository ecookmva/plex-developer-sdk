# EdiApiCreateLogRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DocumentNumber** | Pointer to **string** | The document number provided in the document. | [optional] 
**DocumentName** | Pointer to **string** | The EDI document name for this document (i.e. 830, DELJIT). | [optional] 
**InterchangeNo** | Pointer to **string** | The interchange no provided in the document. | [optional] 
**MailboxId** | Pointer to **string** | The identifier for the mailbox that the EDI Log belongs to. | [optional] 
**Status** | Pointer to **string** | The status to set the added EDI log record to. | [optional] 

## Methods

### NewEdiApiCreateLogRequest

`func NewEdiApiCreateLogRequest() *EdiApiCreateLogRequest`

NewEdiApiCreateLogRequest instantiates a new EdiApiCreateLogRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEdiApiCreateLogRequestWithDefaults

`func NewEdiApiCreateLogRequestWithDefaults() *EdiApiCreateLogRequest`

NewEdiApiCreateLogRequestWithDefaults instantiates a new EdiApiCreateLogRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDocumentNumber

`func (o *EdiApiCreateLogRequest) GetDocumentNumber() string`

GetDocumentNumber returns the DocumentNumber field if non-nil, zero value otherwise.

### GetDocumentNumberOk

`func (o *EdiApiCreateLogRequest) GetDocumentNumberOk() (*string, bool)`

GetDocumentNumberOk returns a tuple with the DocumentNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocumentNumber

`func (o *EdiApiCreateLogRequest) SetDocumentNumber(v string)`

SetDocumentNumber sets DocumentNumber field to given value.

### HasDocumentNumber

`func (o *EdiApiCreateLogRequest) HasDocumentNumber() bool`

HasDocumentNumber returns a boolean if a field has been set.

### GetDocumentName

`func (o *EdiApiCreateLogRequest) GetDocumentName() string`

GetDocumentName returns the DocumentName field if non-nil, zero value otherwise.

### GetDocumentNameOk

`func (o *EdiApiCreateLogRequest) GetDocumentNameOk() (*string, bool)`

GetDocumentNameOk returns a tuple with the DocumentName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocumentName

`func (o *EdiApiCreateLogRequest) SetDocumentName(v string)`

SetDocumentName sets DocumentName field to given value.

### HasDocumentName

`func (o *EdiApiCreateLogRequest) HasDocumentName() bool`

HasDocumentName returns a boolean if a field has been set.

### GetInterchangeNo

`func (o *EdiApiCreateLogRequest) GetInterchangeNo() string`

GetInterchangeNo returns the InterchangeNo field if non-nil, zero value otherwise.

### GetInterchangeNoOk

`func (o *EdiApiCreateLogRequest) GetInterchangeNoOk() (*string, bool)`

GetInterchangeNoOk returns a tuple with the InterchangeNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterchangeNo

`func (o *EdiApiCreateLogRequest) SetInterchangeNo(v string)`

SetInterchangeNo sets InterchangeNo field to given value.

### HasInterchangeNo

`func (o *EdiApiCreateLogRequest) HasInterchangeNo() bool`

HasInterchangeNo returns a boolean if a field has been set.

### GetMailboxId

`func (o *EdiApiCreateLogRequest) GetMailboxId() string`

GetMailboxId returns the MailboxId field if non-nil, zero value otherwise.

### GetMailboxIdOk

`func (o *EdiApiCreateLogRequest) GetMailboxIdOk() (*string, bool)`

GetMailboxIdOk returns a tuple with the MailboxId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMailboxId

`func (o *EdiApiCreateLogRequest) SetMailboxId(v string)`

SetMailboxId sets MailboxId field to given value.

### HasMailboxId

`func (o *EdiApiCreateLogRequest) HasMailboxId() bool`

HasMailboxId returns a boolean if a field has been set.

### GetStatus

`func (o *EdiApiCreateLogRequest) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *EdiApiCreateLogRequest) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *EdiApiCreateLogRequest) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *EdiApiCreateLogRequest) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


