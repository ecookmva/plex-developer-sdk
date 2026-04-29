# EdiApiCreateLogLoadErrorRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | A unique identifier for the EDI Log entry associated with this Error. | [optional] 
**LoadErrorTypeDescription** | Pointer to **string** | The Load Error Type Key. | [optional] 
**MailboxId** | Pointer to **string** | The ID of the EDI Mailbox. | [optional] 
**PartNumber** | Pointer to **string** | The Item Part Number. | [optional] 
**PlantCode** | Pointer to **string** | The Plant Code | [optional] 
**PoNumber** | Pointer to **string** | The Purchase Order Number. | [optional] 
**Revision** | Pointer to **string** | The Revision Number | [optional] 
**CustomerName** | Pointer to **string** | The Customer Name | [optional] 
**EdiDate** | Pointer to **time.Time** | EDI Date. | [optional] 
**Note** | Pointer to **string** | A note with further information describing the error. | [optional] 
**DockCode** | Pointer to **string** | The Dock Code. | [optional] 
**LoadErrorMessage** | Pointer to **string** | The Load Error Message | [optional] 

## Methods

### NewEdiApiCreateLogLoadErrorRequest

`func NewEdiApiCreateLogLoadErrorRequest() *EdiApiCreateLogLoadErrorRequest`

NewEdiApiCreateLogLoadErrorRequest instantiates a new EdiApiCreateLogLoadErrorRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEdiApiCreateLogLoadErrorRequestWithDefaults

`func NewEdiApiCreateLogLoadErrorRequestWithDefaults() *EdiApiCreateLogLoadErrorRequest`

NewEdiApiCreateLogLoadErrorRequestWithDefaults instantiates a new EdiApiCreateLogLoadErrorRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *EdiApiCreateLogLoadErrorRequest) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *EdiApiCreateLogLoadErrorRequest) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *EdiApiCreateLogLoadErrorRequest) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *EdiApiCreateLogLoadErrorRequest) HasId() bool`

HasId returns a boolean if a field has been set.

### GetLoadErrorTypeDescription

`func (o *EdiApiCreateLogLoadErrorRequest) GetLoadErrorTypeDescription() string`

GetLoadErrorTypeDescription returns the LoadErrorTypeDescription field if non-nil, zero value otherwise.

### GetLoadErrorTypeDescriptionOk

`func (o *EdiApiCreateLogLoadErrorRequest) GetLoadErrorTypeDescriptionOk() (*string, bool)`

GetLoadErrorTypeDescriptionOk returns a tuple with the LoadErrorTypeDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLoadErrorTypeDescription

`func (o *EdiApiCreateLogLoadErrorRequest) SetLoadErrorTypeDescription(v string)`

SetLoadErrorTypeDescription sets LoadErrorTypeDescription field to given value.

### HasLoadErrorTypeDescription

`func (o *EdiApiCreateLogLoadErrorRequest) HasLoadErrorTypeDescription() bool`

HasLoadErrorTypeDescription returns a boolean if a field has been set.

### GetMailboxId

`func (o *EdiApiCreateLogLoadErrorRequest) GetMailboxId() string`

GetMailboxId returns the MailboxId field if non-nil, zero value otherwise.

### GetMailboxIdOk

`func (o *EdiApiCreateLogLoadErrorRequest) GetMailboxIdOk() (*string, bool)`

GetMailboxIdOk returns a tuple with the MailboxId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMailboxId

`func (o *EdiApiCreateLogLoadErrorRequest) SetMailboxId(v string)`

SetMailboxId sets MailboxId field to given value.

### HasMailboxId

`func (o *EdiApiCreateLogLoadErrorRequest) HasMailboxId() bool`

HasMailboxId returns a boolean if a field has been set.

### GetPartNumber

`func (o *EdiApiCreateLogLoadErrorRequest) GetPartNumber() string`

GetPartNumber returns the PartNumber field if non-nil, zero value otherwise.

### GetPartNumberOk

`func (o *EdiApiCreateLogLoadErrorRequest) GetPartNumberOk() (*string, bool)`

GetPartNumberOk returns a tuple with the PartNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumber

`func (o *EdiApiCreateLogLoadErrorRequest) SetPartNumber(v string)`

SetPartNumber sets PartNumber field to given value.

### HasPartNumber

`func (o *EdiApiCreateLogLoadErrorRequest) HasPartNumber() bool`

HasPartNumber returns a boolean if a field has been set.

### GetPlantCode

`func (o *EdiApiCreateLogLoadErrorRequest) GetPlantCode() string`

GetPlantCode returns the PlantCode field if non-nil, zero value otherwise.

### GetPlantCodeOk

`func (o *EdiApiCreateLogLoadErrorRequest) GetPlantCodeOk() (*string, bool)`

GetPlantCodeOk returns a tuple with the PlantCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlantCode

`func (o *EdiApiCreateLogLoadErrorRequest) SetPlantCode(v string)`

SetPlantCode sets PlantCode field to given value.

### HasPlantCode

`func (o *EdiApiCreateLogLoadErrorRequest) HasPlantCode() bool`

HasPlantCode returns a boolean if a field has been set.

### GetPoNumber

`func (o *EdiApiCreateLogLoadErrorRequest) GetPoNumber() string`

GetPoNumber returns the PoNumber field if non-nil, zero value otherwise.

### GetPoNumberOk

`func (o *EdiApiCreateLogLoadErrorRequest) GetPoNumberOk() (*string, bool)`

GetPoNumberOk returns a tuple with the PoNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoNumber

`func (o *EdiApiCreateLogLoadErrorRequest) SetPoNumber(v string)`

SetPoNumber sets PoNumber field to given value.

### HasPoNumber

`func (o *EdiApiCreateLogLoadErrorRequest) HasPoNumber() bool`

HasPoNumber returns a boolean if a field has been set.

### GetRevision

`func (o *EdiApiCreateLogLoadErrorRequest) GetRevision() string`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *EdiApiCreateLogLoadErrorRequest) GetRevisionOk() (*string, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *EdiApiCreateLogLoadErrorRequest) SetRevision(v string)`

SetRevision sets Revision field to given value.

### HasRevision

`func (o *EdiApiCreateLogLoadErrorRequest) HasRevision() bool`

HasRevision returns a boolean if a field has been set.

### GetCustomerName

`func (o *EdiApiCreateLogLoadErrorRequest) GetCustomerName() string`

GetCustomerName returns the CustomerName field if non-nil, zero value otherwise.

### GetCustomerNameOk

`func (o *EdiApiCreateLogLoadErrorRequest) GetCustomerNameOk() (*string, bool)`

GetCustomerNameOk returns a tuple with the CustomerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerName

`func (o *EdiApiCreateLogLoadErrorRequest) SetCustomerName(v string)`

SetCustomerName sets CustomerName field to given value.

### HasCustomerName

`func (o *EdiApiCreateLogLoadErrorRequest) HasCustomerName() bool`

HasCustomerName returns a boolean if a field has been set.

### GetEdiDate

`func (o *EdiApiCreateLogLoadErrorRequest) GetEdiDate() time.Time`

GetEdiDate returns the EdiDate field if non-nil, zero value otherwise.

### GetEdiDateOk

`func (o *EdiApiCreateLogLoadErrorRequest) GetEdiDateOk() (*time.Time, bool)`

GetEdiDateOk returns a tuple with the EdiDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEdiDate

`func (o *EdiApiCreateLogLoadErrorRequest) SetEdiDate(v time.Time)`

SetEdiDate sets EdiDate field to given value.

### HasEdiDate

`func (o *EdiApiCreateLogLoadErrorRequest) HasEdiDate() bool`

HasEdiDate returns a boolean if a field has been set.

### GetNote

`func (o *EdiApiCreateLogLoadErrorRequest) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *EdiApiCreateLogLoadErrorRequest) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *EdiApiCreateLogLoadErrorRequest) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *EdiApiCreateLogLoadErrorRequest) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetDockCode

`func (o *EdiApiCreateLogLoadErrorRequest) GetDockCode() string`

GetDockCode returns the DockCode field if non-nil, zero value otherwise.

### GetDockCodeOk

`func (o *EdiApiCreateLogLoadErrorRequest) GetDockCodeOk() (*string, bool)`

GetDockCodeOk returns a tuple with the DockCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDockCode

`func (o *EdiApiCreateLogLoadErrorRequest) SetDockCode(v string)`

SetDockCode sets DockCode field to given value.

### HasDockCode

`func (o *EdiApiCreateLogLoadErrorRequest) HasDockCode() bool`

HasDockCode returns a boolean if a field has been set.

### GetLoadErrorMessage

`func (o *EdiApiCreateLogLoadErrorRequest) GetLoadErrorMessage() string`

GetLoadErrorMessage returns the LoadErrorMessage field if non-nil, zero value otherwise.

### GetLoadErrorMessageOk

`func (o *EdiApiCreateLogLoadErrorRequest) GetLoadErrorMessageOk() (*string, bool)`

GetLoadErrorMessageOk returns a tuple with the LoadErrorMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLoadErrorMessage

`func (o *EdiApiCreateLogLoadErrorRequest) SetLoadErrorMessage(v string)`

SetLoadErrorMessage sets LoadErrorMessage field to given value.

### HasLoadErrorMessage

`func (o *EdiApiCreateLogLoadErrorRequest) HasLoadErrorMessage() bool`

HasLoadErrorMessage returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


