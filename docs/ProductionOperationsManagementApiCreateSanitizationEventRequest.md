# ProductionOperationsManagementApiCreateSanitizationEventRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SanitizationCode** | Pointer to **string** | The Sanitization Code (100 chars max). | [optional] 
**SanitizationDateTime** | Pointer to **time.Time** | The Sanitization event date/time. | [optional] 
**Note** | Pointer to **string** | The note about the sanitization event (500 chars max). | [optional] 

## Methods

### NewProductionOperationsManagementApiCreateSanitizationEventRequest

`func NewProductionOperationsManagementApiCreateSanitizationEventRequest() *ProductionOperationsManagementApiCreateSanitizationEventRequest`

NewProductionOperationsManagementApiCreateSanitizationEventRequest instantiates a new ProductionOperationsManagementApiCreateSanitizationEventRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductionOperationsManagementApiCreateSanitizationEventRequestWithDefaults

`func NewProductionOperationsManagementApiCreateSanitizationEventRequestWithDefaults() *ProductionOperationsManagementApiCreateSanitizationEventRequest`

NewProductionOperationsManagementApiCreateSanitizationEventRequestWithDefaults instantiates a new ProductionOperationsManagementApiCreateSanitizationEventRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSanitizationCode

`func (o *ProductionOperationsManagementApiCreateSanitizationEventRequest) GetSanitizationCode() string`

GetSanitizationCode returns the SanitizationCode field if non-nil, zero value otherwise.

### GetSanitizationCodeOk

`func (o *ProductionOperationsManagementApiCreateSanitizationEventRequest) GetSanitizationCodeOk() (*string, bool)`

GetSanitizationCodeOk returns a tuple with the SanitizationCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSanitizationCode

`func (o *ProductionOperationsManagementApiCreateSanitizationEventRequest) SetSanitizationCode(v string)`

SetSanitizationCode sets SanitizationCode field to given value.

### HasSanitizationCode

`func (o *ProductionOperationsManagementApiCreateSanitizationEventRequest) HasSanitizationCode() bool`

HasSanitizationCode returns a boolean if a field has been set.

### GetSanitizationDateTime

`func (o *ProductionOperationsManagementApiCreateSanitizationEventRequest) GetSanitizationDateTime() time.Time`

GetSanitizationDateTime returns the SanitizationDateTime field if non-nil, zero value otherwise.

### GetSanitizationDateTimeOk

`func (o *ProductionOperationsManagementApiCreateSanitizationEventRequest) GetSanitizationDateTimeOk() (*time.Time, bool)`

GetSanitizationDateTimeOk returns a tuple with the SanitizationDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSanitizationDateTime

`func (o *ProductionOperationsManagementApiCreateSanitizationEventRequest) SetSanitizationDateTime(v time.Time)`

SetSanitizationDateTime sets SanitizationDateTime field to given value.

### HasSanitizationDateTime

`func (o *ProductionOperationsManagementApiCreateSanitizationEventRequest) HasSanitizationDateTime() bool`

HasSanitizationDateTime returns a boolean if a field has been set.

### GetNote

`func (o *ProductionOperationsManagementApiCreateSanitizationEventRequest) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *ProductionOperationsManagementApiCreateSanitizationEventRequest) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *ProductionOperationsManagementApiCreateSanitizationEventRequest) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *ProductionOperationsManagementApiCreateSanitizationEventRequest) HasNote() bool`

HasNote returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


