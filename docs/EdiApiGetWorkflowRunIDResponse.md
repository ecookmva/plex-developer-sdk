# EdiApiGetWorkflowRunIDResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RunId** | Pointer to **string** | A unique identifier for the Azure Logic Apps Workflow Run. | [optional] 
**WorkflowType** | Pointer to **string** | The Workflow Type that is being executed. | [optional] 

## Methods

### NewEdiApiGetWorkflowRunIDResponse

`func NewEdiApiGetWorkflowRunIDResponse() *EdiApiGetWorkflowRunIDResponse`

NewEdiApiGetWorkflowRunIDResponse instantiates a new EdiApiGetWorkflowRunIDResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEdiApiGetWorkflowRunIDResponseWithDefaults

`func NewEdiApiGetWorkflowRunIDResponseWithDefaults() *EdiApiGetWorkflowRunIDResponse`

NewEdiApiGetWorkflowRunIDResponseWithDefaults instantiates a new EdiApiGetWorkflowRunIDResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRunId

`func (o *EdiApiGetWorkflowRunIDResponse) GetRunId() string`

GetRunId returns the RunId field if non-nil, zero value otherwise.

### GetRunIdOk

`func (o *EdiApiGetWorkflowRunIDResponse) GetRunIdOk() (*string, bool)`

GetRunIdOk returns a tuple with the RunId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunId

`func (o *EdiApiGetWorkflowRunIDResponse) SetRunId(v string)`

SetRunId sets RunId field to given value.

### HasRunId

`func (o *EdiApiGetWorkflowRunIDResponse) HasRunId() bool`

HasRunId returns a boolean if a field has been set.

### GetWorkflowType

`func (o *EdiApiGetWorkflowRunIDResponse) GetWorkflowType() string`

GetWorkflowType returns the WorkflowType field if non-nil, zero value otherwise.

### GetWorkflowTypeOk

`func (o *EdiApiGetWorkflowRunIDResponse) GetWorkflowTypeOk() (*string, bool)`

GetWorkflowTypeOk returns a tuple with the WorkflowType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflowType

`func (o *EdiApiGetWorkflowRunIDResponse) SetWorkflowType(v string)`

SetWorkflowType sets WorkflowType field to given value.

### HasWorkflowType

`func (o *EdiApiGetWorkflowRunIDResponse) HasWorkflowType() bool`

HasWorkflowType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


