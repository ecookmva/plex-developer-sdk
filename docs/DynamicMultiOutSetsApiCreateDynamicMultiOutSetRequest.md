# DynamicMultiOutSetsApiCreateDynamicMultiOutSetRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | A unique identifier for the Dynamic Multi Out Set. This will be automatically generated if omitted from the request. | [optional] 
**Code** | Pointer to **string** | The unique code for the Dynamic Multi Out Set. | [optional] 
**Description** | Pointer to **string** | The description for the Dynamic Multi Out Set. | [optional] 
**PlannedCalendarStartDate** | Pointer to **string** | The planned start date for the Dynamic Multi Out Set. Format expected: uuuu-MM-dd. | [optional] 
**JobOperationIds** | Pointer to **[]string** | The Job Operation IDs tied to this Set. | [optional] 

## Methods

### NewDynamicMultiOutSetsApiCreateDynamicMultiOutSetRequest

`func NewDynamicMultiOutSetsApiCreateDynamicMultiOutSetRequest() *DynamicMultiOutSetsApiCreateDynamicMultiOutSetRequest`

NewDynamicMultiOutSetsApiCreateDynamicMultiOutSetRequest instantiates a new DynamicMultiOutSetsApiCreateDynamicMultiOutSetRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDynamicMultiOutSetsApiCreateDynamicMultiOutSetRequestWithDefaults

`func NewDynamicMultiOutSetsApiCreateDynamicMultiOutSetRequestWithDefaults() *DynamicMultiOutSetsApiCreateDynamicMultiOutSetRequest`

NewDynamicMultiOutSetsApiCreateDynamicMultiOutSetRequestWithDefaults instantiates a new DynamicMultiOutSetsApiCreateDynamicMultiOutSetRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *DynamicMultiOutSetsApiCreateDynamicMultiOutSetRequest) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *DynamicMultiOutSetsApiCreateDynamicMultiOutSetRequest) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *DynamicMultiOutSetsApiCreateDynamicMultiOutSetRequest) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *DynamicMultiOutSetsApiCreateDynamicMultiOutSetRequest) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCode

`func (o *DynamicMultiOutSetsApiCreateDynamicMultiOutSetRequest) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *DynamicMultiOutSetsApiCreateDynamicMultiOutSetRequest) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *DynamicMultiOutSetsApiCreateDynamicMultiOutSetRequest) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *DynamicMultiOutSetsApiCreateDynamicMultiOutSetRequest) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetDescription

`func (o *DynamicMultiOutSetsApiCreateDynamicMultiOutSetRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *DynamicMultiOutSetsApiCreateDynamicMultiOutSetRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *DynamicMultiOutSetsApiCreateDynamicMultiOutSetRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *DynamicMultiOutSetsApiCreateDynamicMultiOutSetRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetPlannedCalendarStartDate

`func (o *DynamicMultiOutSetsApiCreateDynamicMultiOutSetRequest) GetPlannedCalendarStartDate() string`

GetPlannedCalendarStartDate returns the PlannedCalendarStartDate field if non-nil, zero value otherwise.

### GetPlannedCalendarStartDateOk

`func (o *DynamicMultiOutSetsApiCreateDynamicMultiOutSetRequest) GetPlannedCalendarStartDateOk() (*string, bool)`

GetPlannedCalendarStartDateOk returns a tuple with the PlannedCalendarStartDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlannedCalendarStartDate

`func (o *DynamicMultiOutSetsApiCreateDynamicMultiOutSetRequest) SetPlannedCalendarStartDate(v string)`

SetPlannedCalendarStartDate sets PlannedCalendarStartDate field to given value.

### HasPlannedCalendarStartDate

`func (o *DynamicMultiOutSetsApiCreateDynamicMultiOutSetRequest) HasPlannedCalendarStartDate() bool`

HasPlannedCalendarStartDate returns a boolean if a field has been set.

### GetJobOperationIds

`func (o *DynamicMultiOutSetsApiCreateDynamicMultiOutSetRequest) GetJobOperationIds() []string`

GetJobOperationIds returns the JobOperationIds field if non-nil, zero value otherwise.

### GetJobOperationIdsOk

`func (o *DynamicMultiOutSetsApiCreateDynamicMultiOutSetRequest) GetJobOperationIdsOk() (*[]string, bool)`

GetJobOperationIdsOk returns a tuple with the JobOperationIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobOperationIds

`func (o *DynamicMultiOutSetsApiCreateDynamicMultiOutSetRequest) SetJobOperationIds(v []string)`

SetJobOperationIds sets JobOperationIds field to given value.

### HasJobOperationIds

`func (o *DynamicMultiOutSetsApiCreateDynamicMultiOutSetRequest) HasJobOperationIds() bool`

HasJobOperationIds returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


