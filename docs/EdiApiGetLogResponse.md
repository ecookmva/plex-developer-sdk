# EdiApiGetLogResponse

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

### NewEdiApiGetLogResponse

`func NewEdiApiGetLogResponse() *EdiApiGetLogResponse`

NewEdiApiGetLogResponse instantiates a new EdiApiGetLogResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEdiApiGetLogResponseWithDefaults

`func NewEdiApiGetLogResponseWithDefaults() *EdiApiGetLogResponse`

NewEdiApiGetLogResponseWithDefaults instantiates a new EdiApiGetLogResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *EdiApiGetLogResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *EdiApiGetLogResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *EdiApiGetLogResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *EdiApiGetLogResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetAction

`func (o *EdiApiGetLogResponse) GetAction() string`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *EdiApiGetLogResponse) GetActionOk() (*string, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *EdiApiGetLogResponse) SetAction(v string)`

SetAction sets Action field to given value.

### HasAction

`func (o *EdiApiGetLogResponse) HasAction() bool`

HasAction returns a boolean if a field has been set.

### GetStatus

`func (o *EdiApiGetLogResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *EdiApiGetLogResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *EdiApiGetLogResponse) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *EdiApiGetLogResponse) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetLogDate

`func (o *EdiApiGetLogResponse) GetLogDate() time.Time`

GetLogDate returns the LogDate field if non-nil, zero value otherwise.

### GetLogDateOk

`func (o *EdiApiGetLogResponse) GetLogDateOk() (*time.Time, bool)`

GetLogDateOk returns a tuple with the LogDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogDate

`func (o *EdiApiGetLogResponse) SetLogDate(v time.Time)`

SetLogDate sets LogDate field to given value.

### HasLogDate

`func (o *EdiApiGetLogResponse) HasLogDate() bool`

HasLogDate returns a boolean if a field has been set.

### GetMailboxId

`func (o *EdiApiGetLogResponse) GetMailboxId() string`

GetMailboxId returns the MailboxId field if non-nil, zero value otherwise.

### GetMailboxIdOk

`func (o *EdiApiGetLogResponse) GetMailboxIdOk() (*string, bool)`

GetMailboxIdOk returns a tuple with the MailboxId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMailboxId

`func (o *EdiApiGetLogResponse) SetMailboxId(v string)`

SetMailboxId sets MailboxId field to given value.

### HasMailboxId

`func (o *EdiApiGetLogResponse) HasMailboxId() bool`

HasMailboxId returns a boolean if a field has been set.

### GetDocumentName

`func (o *EdiApiGetLogResponse) GetDocumentName() string`

GetDocumentName returns the DocumentName field if non-nil, zero value otherwise.

### GetDocumentNameOk

`func (o *EdiApiGetLogResponse) GetDocumentNameOk() (*string, bool)`

GetDocumentNameOk returns a tuple with the DocumentName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocumentName

`func (o *EdiApiGetLogResponse) SetDocumentName(v string)`

SetDocumentName sets DocumentName field to given value.

### HasDocumentName

`func (o *EdiApiGetLogResponse) HasDocumentName() bool`

HasDocumentName returns a boolean if a field has been set.

### GetEdiKey

`func (o *EdiApiGetLogResponse) GetEdiKey() int32`

GetEdiKey returns the EdiKey field if non-nil, zero value otherwise.

### GetEdiKeyOk

`func (o *EdiApiGetLogResponse) GetEdiKeyOk() (*int32, bool)`

GetEdiKeyOk returns a tuple with the EdiKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEdiKey

`func (o *EdiApiGetLogResponse) SetEdiKey(v int32)`

SetEdiKey sets EdiKey field to given value.

### HasEdiKey

`func (o *EdiApiGetLogResponse) HasEdiKey() bool`

HasEdiKey returns a boolean if a field has been set.

### GetMailboxActive

`func (o *EdiApiGetLogResponse) GetMailboxActive() bool`

GetMailboxActive returns the MailboxActive field if non-nil, zero value otherwise.

### GetMailboxActiveOk

`func (o *EdiApiGetLogResponse) GetMailboxActiveOk() (*bool, bool)`

GetMailboxActiveOk returns a tuple with the MailboxActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMailboxActive

`func (o *EdiApiGetLogResponse) SetMailboxActive(v bool)`

SetMailboxActive sets MailboxActive field to given value.

### HasMailboxActive

`func (o *EdiApiGetLogResponse) HasMailboxActive() bool`

HasMailboxActive returns a boolean if a field has been set.

### GetCustomerId

`func (o *EdiApiGetLogResponse) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *EdiApiGetLogResponse) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *EdiApiGetLogResponse) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *EdiApiGetLogResponse) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### GetWorkflowType

`func (o *EdiApiGetLogResponse) GetWorkflowType() string`

GetWorkflowType returns the WorkflowType field if non-nil, zero value otherwise.

### GetWorkflowTypeOk

`func (o *EdiApiGetLogResponse) GetWorkflowTypeOk() (*string, bool)`

GetWorkflowTypeOk returns a tuple with the WorkflowType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflowType

`func (o *EdiApiGetLogResponse) SetWorkflowType(v string)`

SetWorkflowType sets WorkflowType field to given value.

### HasWorkflowType

`func (o *EdiApiGetLogResponse) HasWorkflowType() bool`

HasWorkflowType returns a boolean if a field has been set.

### GetWorkflowActive

`func (o *EdiApiGetLogResponse) GetWorkflowActive() bool`

GetWorkflowActive returns the WorkflowActive field if non-nil, zero value otherwise.

### GetWorkflowActiveOk

`func (o *EdiApiGetLogResponse) GetWorkflowActiveOk() (*bool, bool)`

GetWorkflowActiveOk returns a tuple with the WorkflowActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflowActive

`func (o *EdiApiGetLogResponse) SetWorkflowActive(v bool)`

SetWorkflowActive sets WorkflowActive field to given value.

### HasWorkflowActive

`func (o *EdiApiGetLogResponse) HasWorkflowActive() bool`

HasWorkflowActive returns a boolean if a field has been set.

### GetWorkflowName

`func (o *EdiApiGetLogResponse) GetWorkflowName() string`

GetWorkflowName returns the WorkflowName field if non-nil, zero value otherwise.

### GetWorkflowNameOk

`func (o *EdiApiGetLogResponse) GetWorkflowNameOk() (*string, bool)`

GetWorkflowNameOk returns a tuple with the WorkflowName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflowName

`func (o *EdiApiGetLogResponse) SetWorkflowName(v string)`

SetWorkflowName sets WorkflowName field to given value.

### HasWorkflowName

`func (o *EdiApiGetLogResponse) HasWorkflowName() bool`

HasWorkflowName returns a boolean if a field has been set.

### GetPreviewMode

`func (o *EdiApiGetLogResponse) GetPreviewMode() bool`

GetPreviewMode returns the PreviewMode field if non-nil, zero value otherwise.

### GetPreviewModeOk

`func (o *EdiApiGetLogResponse) GetPreviewModeOk() (*bool, bool)`

GetPreviewModeOk returns a tuple with the PreviewMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviewMode

`func (o *EdiApiGetLogResponse) SetPreviewMode(v bool)`

SetPreviewMode sets PreviewMode field to given value.

### HasPreviewMode

`func (o *EdiApiGetLogResponse) HasPreviewMode() bool`

HasPreviewMode returns a boolean if a field has been set.

### GetPendingTransmission

`func (o *EdiApiGetLogResponse) GetPendingTransmission() bool`

GetPendingTransmission returns the PendingTransmission field if non-nil, zero value otherwise.

### GetPendingTransmissionOk

`func (o *EdiApiGetLogResponse) GetPendingTransmissionOk() (*bool, bool)`

GetPendingTransmissionOk returns a tuple with the PendingTransmission field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPendingTransmission

`func (o *EdiApiGetLogResponse) SetPendingTransmission(v bool)`

SetPendingTransmission sets PendingTransmission field to given value.

### HasPendingTransmission

`func (o *EdiApiGetLogResponse) HasPendingTransmission() bool`

HasPendingTransmission returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


