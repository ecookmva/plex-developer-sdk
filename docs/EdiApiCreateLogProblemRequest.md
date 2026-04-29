# EdiApiCreateLogProblemRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProblemType** | Pointer to **string** | The type of problem | [optional] 
**Description** | Pointer to **string** | A description of the problem. | [optional] 
**ProblemDate** | Pointer to **time.Time** | The date that the problem occurred. | [optional] 
**MailboxId** | Pointer to **string** | Optional unique identifier of the mailbox that the problem is associated with. | [optional] 
**ShipperId** | Pointer to **string** | Optional unique identifier of the shipper that the problem is associated with. | [optional] 
**DocumentName** | Pointer to **string** | Optional name of the document that the problem is associated with. | [optional] 

## Methods

### NewEdiApiCreateLogProblemRequest

`func NewEdiApiCreateLogProblemRequest() *EdiApiCreateLogProblemRequest`

NewEdiApiCreateLogProblemRequest instantiates a new EdiApiCreateLogProblemRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEdiApiCreateLogProblemRequestWithDefaults

`func NewEdiApiCreateLogProblemRequestWithDefaults() *EdiApiCreateLogProblemRequest`

NewEdiApiCreateLogProblemRequestWithDefaults instantiates a new EdiApiCreateLogProblemRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProblemType

`func (o *EdiApiCreateLogProblemRequest) GetProblemType() string`

GetProblemType returns the ProblemType field if non-nil, zero value otherwise.

### GetProblemTypeOk

`func (o *EdiApiCreateLogProblemRequest) GetProblemTypeOk() (*string, bool)`

GetProblemTypeOk returns a tuple with the ProblemType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProblemType

`func (o *EdiApiCreateLogProblemRequest) SetProblemType(v string)`

SetProblemType sets ProblemType field to given value.

### HasProblemType

`func (o *EdiApiCreateLogProblemRequest) HasProblemType() bool`

HasProblemType returns a boolean if a field has been set.

### GetDescription

`func (o *EdiApiCreateLogProblemRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *EdiApiCreateLogProblemRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *EdiApiCreateLogProblemRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *EdiApiCreateLogProblemRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetProblemDate

`func (o *EdiApiCreateLogProblemRequest) GetProblemDate() time.Time`

GetProblemDate returns the ProblemDate field if non-nil, zero value otherwise.

### GetProblemDateOk

`func (o *EdiApiCreateLogProblemRequest) GetProblemDateOk() (*time.Time, bool)`

GetProblemDateOk returns a tuple with the ProblemDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProblemDate

`func (o *EdiApiCreateLogProblemRequest) SetProblemDate(v time.Time)`

SetProblemDate sets ProblemDate field to given value.

### HasProblemDate

`func (o *EdiApiCreateLogProblemRequest) HasProblemDate() bool`

HasProblemDate returns a boolean if a field has been set.

### GetMailboxId

`func (o *EdiApiCreateLogProblemRequest) GetMailboxId() string`

GetMailboxId returns the MailboxId field if non-nil, zero value otherwise.

### GetMailboxIdOk

`func (o *EdiApiCreateLogProblemRequest) GetMailboxIdOk() (*string, bool)`

GetMailboxIdOk returns a tuple with the MailboxId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMailboxId

`func (o *EdiApiCreateLogProblemRequest) SetMailboxId(v string)`

SetMailboxId sets MailboxId field to given value.

### HasMailboxId

`func (o *EdiApiCreateLogProblemRequest) HasMailboxId() bool`

HasMailboxId returns a boolean if a field has been set.

### GetShipperId

`func (o *EdiApiCreateLogProblemRequest) GetShipperId() string`

GetShipperId returns the ShipperId field if non-nil, zero value otherwise.

### GetShipperIdOk

`func (o *EdiApiCreateLogProblemRequest) GetShipperIdOk() (*string, bool)`

GetShipperIdOk returns a tuple with the ShipperId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipperId

`func (o *EdiApiCreateLogProblemRequest) SetShipperId(v string)`

SetShipperId sets ShipperId field to given value.

### HasShipperId

`func (o *EdiApiCreateLogProblemRequest) HasShipperId() bool`

HasShipperId returns a boolean if a field has been set.

### GetDocumentName

`func (o *EdiApiCreateLogProblemRequest) GetDocumentName() string`

GetDocumentName returns the DocumentName field if non-nil, zero value otherwise.

### GetDocumentNameOk

`func (o *EdiApiCreateLogProblemRequest) GetDocumentNameOk() (*string, bool)`

GetDocumentNameOk returns a tuple with the DocumentName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocumentName

`func (o *EdiApiCreateLogProblemRequest) SetDocumentName(v string)`

SetDocumentName sets DocumentName field to given value.

### HasDocumentName

`func (o *EdiApiCreateLogProblemRequest) HasDocumentName() bool`

HasDocumentName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


