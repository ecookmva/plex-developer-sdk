# EdiApiCreateLog201Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | A unique identifier for the Log. | [optional] 
**Action** | Pointer to **string** | Send or Receive. Send indicates that the document is an outbound document whereas receive indicates that the document is an inbound document. | [optional] 
**Status** | Pointer to **string** | The Status of the EDI Log, such as Loaded or Accepted. | [optional] 
**LogDate** | Pointer to **time.Time** | The date on which the document was created. | [optional] 
**MailboxId** | Pointer to **string** | The ID of the EDI Mailbox. | [optional] 
**DocumentName** | Pointer to **string** | The name of the EDI document associated to the EDI Log entry. | [optional] 
**EdiKey** | Pointer to **int32** | The EDI Key associated to the EDI Log entry. | [optional] 
**MailboxActive** | Pointer to **bool** | The Active flag of the EDI Mailbox. | [optional] 
**CustomerId** | Pointer to **string** | The ID of the Customer. | [optional] 
**WorkflowType** | Pointer to **string** | The Workflow Type of the Mailbox associated to the EDI Log entry. | [optional] 
**WorkflowActive** | Pointer to **bool** | The Active flag of the Workflow of the EDI Mailbox. | [optional] 
**WorkflowName** | Pointer to **string** | The Workflow Name of the Mailbox associated to the EDI Log entry. | [optional] 
**PreviewMode** | Pointer to **bool** | The Preview flag of the Document Setup. | [optional] 
**PendingTransmission** | Pointer to **bool** | The Pending Transmission flag of the EDI Log entry. | [optional] 

## Methods

### NewEdiApiCreateLog201Response

`func NewEdiApiCreateLog201Response() *EdiApiCreateLog201Response`

NewEdiApiCreateLog201Response instantiates a new EdiApiCreateLog201Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEdiApiCreateLog201ResponseWithDefaults

`func NewEdiApiCreateLog201ResponseWithDefaults() *EdiApiCreateLog201Response`

NewEdiApiCreateLog201ResponseWithDefaults instantiates a new EdiApiCreateLog201Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *EdiApiCreateLog201Response) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *EdiApiCreateLog201Response) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *EdiApiCreateLog201Response) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *EdiApiCreateLog201Response) HasId() bool`

HasId returns a boolean if a field has been set.

### GetAction

`func (o *EdiApiCreateLog201Response) GetAction() string`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *EdiApiCreateLog201Response) GetActionOk() (*string, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *EdiApiCreateLog201Response) SetAction(v string)`

SetAction sets Action field to given value.

### HasAction

`func (o *EdiApiCreateLog201Response) HasAction() bool`

HasAction returns a boolean if a field has been set.

### GetStatus

`func (o *EdiApiCreateLog201Response) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *EdiApiCreateLog201Response) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *EdiApiCreateLog201Response) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *EdiApiCreateLog201Response) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetLogDate

`func (o *EdiApiCreateLog201Response) GetLogDate() time.Time`

GetLogDate returns the LogDate field if non-nil, zero value otherwise.

### GetLogDateOk

`func (o *EdiApiCreateLog201Response) GetLogDateOk() (*time.Time, bool)`

GetLogDateOk returns a tuple with the LogDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogDate

`func (o *EdiApiCreateLog201Response) SetLogDate(v time.Time)`

SetLogDate sets LogDate field to given value.

### HasLogDate

`func (o *EdiApiCreateLog201Response) HasLogDate() bool`

HasLogDate returns a boolean if a field has been set.

### GetMailboxId

`func (o *EdiApiCreateLog201Response) GetMailboxId() string`

GetMailboxId returns the MailboxId field if non-nil, zero value otherwise.

### GetMailboxIdOk

`func (o *EdiApiCreateLog201Response) GetMailboxIdOk() (*string, bool)`

GetMailboxIdOk returns a tuple with the MailboxId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMailboxId

`func (o *EdiApiCreateLog201Response) SetMailboxId(v string)`

SetMailboxId sets MailboxId field to given value.

### HasMailboxId

`func (o *EdiApiCreateLog201Response) HasMailboxId() bool`

HasMailboxId returns a boolean if a field has been set.

### GetDocumentName

`func (o *EdiApiCreateLog201Response) GetDocumentName() string`

GetDocumentName returns the DocumentName field if non-nil, zero value otherwise.

### GetDocumentNameOk

`func (o *EdiApiCreateLog201Response) GetDocumentNameOk() (*string, bool)`

GetDocumentNameOk returns a tuple with the DocumentName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocumentName

`func (o *EdiApiCreateLog201Response) SetDocumentName(v string)`

SetDocumentName sets DocumentName field to given value.

### HasDocumentName

`func (o *EdiApiCreateLog201Response) HasDocumentName() bool`

HasDocumentName returns a boolean if a field has been set.

### GetEdiKey

`func (o *EdiApiCreateLog201Response) GetEdiKey() int32`

GetEdiKey returns the EdiKey field if non-nil, zero value otherwise.

### GetEdiKeyOk

`func (o *EdiApiCreateLog201Response) GetEdiKeyOk() (*int32, bool)`

GetEdiKeyOk returns a tuple with the EdiKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEdiKey

`func (o *EdiApiCreateLog201Response) SetEdiKey(v int32)`

SetEdiKey sets EdiKey field to given value.

### HasEdiKey

`func (o *EdiApiCreateLog201Response) HasEdiKey() bool`

HasEdiKey returns a boolean if a field has been set.

### GetMailboxActive

`func (o *EdiApiCreateLog201Response) GetMailboxActive() bool`

GetMailboxActive returns the MailboxActive field if non-nil, zero value otherwise.

### GetMailboxActiveOk

`func (o *EdiApiCreateLog201Response) GetMailboxActiveOk() (*bool, bool)`

GetMailboxActiveOk returns a tuple with the MailboxActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMailboxActive

`func (o *EdiApiCreateLog201Response) SetMailboxActive(v bool)`

SetMailboxActive sets MailboxActive field to given value.

### HasMailboxActive

`func (o *EdiApiCreateLog201Response) HasMailboxActive() bool`

HasMailboxActive returns a boolean if a field has been set.

### GetCustomerId

`func (o *EdiApiCreateLog201Response) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *EdiApiCreateLog201Response) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *EdiApiCreateLog201Response) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *EdiApiCreateLog201Response) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### GetWorkflowType

`func (o *EdiApiCreateLog201Response) GetWorkflowType() string`

GetWorkflowType returns the WorkflowType field if non-nil, zero value otherwise.

### GetWorkflowTypeOk

`func (o *EdiApiCreateLog201Response) GetWorkflowTypeOk() (*string, bool)`

GetWorkflowTypeOk returns a tuple with the WorkflowType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflowType

`func (o *EdiApiCreateLog201Response) SetWorkflowType(v string)`

SetWorkflowType sets WorkflowType field to given value.

### HasWorkflowType

`func (o *EdiApiCreateLog201Response) HasWorkflowType() bool`

HasWorkflowType returns a boolean if a field has been set.

### GetWorkflowActive

`func (o *EdiApiCreateLog201Response) GetWorkflowActive() bool`

GetWorkflowActive returns the WorkflowActive field if non-nil, zero value otherwise.

### GetWorkflowActiveOk

`func (o *EdiApiCreateLog201Response) GetWorkflowActiveOk() (*bool, bool)`

GetWorkflowActiveOk returns a tuple with the WorkflowActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflowActive

`func (o *EdiApiCreateLog201Response) SetWorkflowActive(v bool)`

SetWorkflowActive sets WorkflowActive field to given value.

### HasWorkflowActive

`func (o *EdiApiCreateLog201Response) HasWorkflowActive() bool`

HasWorkflowActive returns a boolean if a field has been set.

### GetWorkflowName

`func (o *EdiApiCreateLog201Response) GetWorkflowName() string`

GetWorkflowName returns the WorkflowName field if non-nil, zero value otherwise.

### GetWorkflowNameOk

`func (o *EdiApiCreateLog201Response) GetWorkflowNameOk() (*string, bool)`

GetWorkflowNameOk returns a tuple with the WorkflowName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflowName

`func (o *EdiApiCreateLog201Response) SetWorkflowName(v string)`

SetWorkflowName sets WorkflowName field to given value.

### HasWorkflowName

`func (o *EdiApiCreateLog201Response) HasWorkflowName() bool`

HasWorkflowName returns a boolean if a field has been set.

### GetPreviewMode

`func (o *EdiApiCreateLog201Response) GetPreviewMode() bool`

GetPreviewMode returns the PreviewMode field if non-nil, zero value otherwise.

### GetPreviewModeOk

`func (o *EdiApiCreateLog201Response) GetPreviewModeOk() (*bool, bool)`

GetPreviewModeOk returns a tuple with the PreviewMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviewMode

`func (o *EdiApiCreateLog201Response) SetPreviewMode(v bool)`

SetPreviewMode sets PreviewMode field to given value.

### HasPreviewMode

`func (o *EdiApiCreateLog201Response) HasPreviewMode() bool`

HasPreviewMode returns a boolean if a field has been set.

### GetPendingTransmission

`func (o *EdiApiCreateLog201Response) GetPendingTransmission() bool`

GetPendingTransmission returns the PendingTransmission field if non-nil, zero value otherwise.

### GetPendingTransmissionOk

`func (o *EdiApiCreateLog201Response) GetPendingTransmissionOk() (*bool, bool)`

GetPendingTransmissionOk returns a tuple with the PendingTransmission field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPendingTransmission

`func (o *EdiApiCreateLog201Response) SetPendingTransmission(v bool)`

SetPendingTransmission sets PendingTransmission field to given value.

### HasPendingTransmission

`func (o *EdiApiCreateLog201Response) HasPendingTransmission() bool`

HasPendingTransmission returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


