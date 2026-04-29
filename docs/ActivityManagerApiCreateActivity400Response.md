# ActivityManagerApiCreateActivity400Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TenantId** | Pointer to **string** | The Tenant ID. | [optional] 
**ActivityId** | Pointer to **string** | The ID of the activity. | [optional] 
**ActivityName** | Pointer to **string** | The name of the activity. | [optional] 
**Description** | Pointer to **string** | The description of the activity. | [optional] 
**ActivityType** | Pointer to **string** | The activity type. | [optional] 
**ActivityStatus** | Pointer to **string** | The status information of the activity. | [optional] 
**StatusNote** | Pointer to **string** | A note on the status of the activity. | [optional] 
**Cost** | Pointer to **float64** | The cost of the activity. | [optional] 
**Priority** | Pointer to **int32** | The priority information about the activity. | [optional] 
**DueDateTime** | Pointer to **time.Time** | The due date of the activity. | [optional] 
**CustomerCode** | Pointer to **string** | The customer code of the activity. | [optional] 
**SupplierCode** | Pointer to **string** | The supplier code of the activity. | [optional] 
**Location** | Pointer to **string** | The location of the activity. | [optional] 
**Private** | Pointer to **bool** | Indicates whether the activity is private or not. | [optional] 
**AssignedTo** | Pointer to **string** | The User ID assigned to the activity. | [optional] 
**AssignedBy** | Pointer to **string** | The User ID assigned by the activity. | [optional] 
**AssignedToDepartment** | Pointer to **string** | The department code to which the activity is assigned. | [optional] 
**InvolvedUsers** | Pointer to **[]string** | The user involved in the activity. | [optional] 
**ParentActivity** | Pointer to **string** | The parent ID of the activity. | [optional] 
**PlannedStartDateTime** | Pointer to **time.Time** | The planned start date of the activity. | [optional] 
**PlannedFinishDateTime** | Pointer to **time.Time** | The planned finish date of the activity. | [optional] 
**PercentageCompletion** | Pointer to **int32** | The completion percentage of the activity. | [optional] 
**SuggestionNos** | Pointer to **[]int32** | The suggestions related to the activity. | [optional] 
**Comments** | Pointer to **[]string** | The comments related to the activity. | [optional] 

## Methods

### NewActivityManagerApiCreateActivity400Response

`func NewActivityManagerApiCreateActivity400Response() *ActivityManagerApiCreateActivity400Response`

NewActivityManagerApiCreateActivity400Response instantiates a new ActivityManagerApiCreateActivity400Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewActivityManagerApiCreateActivity400ResponseWithDefaults

`func NewActivityManagerApiCreateActivity400ResponseWithDefaults() *ActivityManagerApiCreateActivity400Response`

NewActivityManagerApiCreateActivity400ResponseWithDefaults instantiates a new ActivityManagerApiCreateActivity400Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTenantId

`func (o *ActivityManagerApiCreateActivity400Response) GetTenantId() string`

GetTenantId returns the TenantId field if non-nil, zero value otherwise.

### GetTenantIdOk

`func (o *ActivityManagerApiCreateActivity400Response) GetTenantIdOk() (*string, bool)`

GetTenantIdOk returns a tuple with the TenantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantId

`func (o *ActivityManagerApiCreateActivity400Response) SetTenantId(v string)`

SetTenantId sets TenantId field to given value.

### HasTenantId

`func (o *ActivityManagerApiCreateActivity400Response) HasTenantId() bool`

HasTenantId returns a boolean if a field has been set.

### GetActivityId

`func (o *ActivityManagerApiCreateActivity400Response) GetActivityId() string`

GetActivityId returns the ActivityId field if non-nil, zero value otherwise.

### GetActivityIdOk

`func (o *ActivityManagerApiCreateActivity400Response) GetActivityIdOk() (*string, bool)`

GetActivityIdOk returns a tuple with the ActivityId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivityId

`func (o *ActivityManagerApiCreateActivity400Response) SetActivityId(v string)`

SetActivityId sets ActivityId field to given value.

### HasActivityId

`func (o *ActivityManagerApiCreateActivity400Response) HasActivityId() bool`

HasActivityId returns a boolean if a field has been set.

### GetActivityName

`func (o *ActivityManagerApiCreateActivity400Response) GetActivityName() string`

GetActivityName returns the ActivityName field if non-nil, zero value otherwise.

### GetActivityNameOk

`func (o *ActivityManagerApiCreateActivity400Response) GetActivityNameOk() (*string, bool)`

GetActivityNameOk returns a tuple with the ActivityName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivityName

`func (o *ActivityManagerApiCreateActivity400Response) SetActivityName(v string)`

SetActivityName sets ActivityName field to given value.

### HasActivityName

`func (o *ActivityManagerApiCreateActivity400Response) HasActivityName() bool`

HasActivityName returns a boolean if a field has been set.

### GetDescription

`func (o *ActivityManagerApiCreateActivity400Response) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ActivityManagerApiCreateActivity400Response) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ActivityManagerApiCreateActivity400Response) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ActivityManagerApiCreateActivity400Response) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetActivityType

`func (o *ActivityManagerApiCreateActivity400Response) GetActivityType() string`

GetActivityType returns the ActivityType field if non-nil, zero value otherwise.

### GetActivityTypeOk

`func (o *ActivityManagerApiCreateActivity400Response) GetActivityTypeOk() (*string, bool)`

GetActivityTypeOk returns a tuple with the ActivityType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivityType

`func (o *ActivityManagerApiCreateActivity400Response) SetActivityType(v string)`

SetActivityType sets ActivityType field to given value.

### HasActivityType

`func (o *ActivityManagerApiCreateActivity400Response) HasActivityType() bool`

HasActivityType returns a boolean if a field has been set.

### GetActivityStatus

`func (o *ActivityManagerApiCreateActivity400Response) GetActivityStatus() string`

GetActivityStatus returns the ActivityStatus field if non-nil, zero value otherwise.

### GetActivityStatusOk

`func (o *ActivityManagerApiCreateActivity400Response) GetActivityStatusOk() (*string, bool)`

GetActivityStatusOk returns a tuple with the ActivityStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivityStatus

`func (o *ActivityManagerApiCreateActivity400Response) SetActivityStatus(v string)`

SetActivityStatus sets ActivityStatus field to given value.

### HasActivityStatus

`func (o *ActivityManagerApiCreateActivity400Response) HasActivityStatus() bool`

HasActivityStatus returns a boolean if a field has been set.

### GetStatusNote

`func (o *ActivityManagerApiCreateActivity400Response) GetStatusNote() string`

GetStatusNote returns the StatusNote field if non-nil, zero value otherwise.

### GetStatusNoteOk

`func (o *ActivityManagerApiCreateActivity400Response) GetStatusNoteOk() (*string, bool)`

GetStatusNoteOk returns a tuple with the StatusNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatusNote

`func (o *ActivityManagerApiCreateActivity400Response) SetStatusNote(v string)`

SetStatusNote sets StatusNote field to given value.

### HasStatusNote

`func (o *ActivityManagerApiCreateActivity400Response) HasStatusNote() bool`

HasStatusNote returns a boolean if a field has been set.

### GetCost

`func (o *ActivityManagerApiCreateActivity400Response) GetCost() float64`

GetCost returns the Cost field if non-nil, zero value otherwise.

### GetCostOk

`func (o *ActivityManagerApiCreateActivity400Response) GetCostOk() (*float64, bool)`

GetCostOk returns a tuple with the Cost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCost

`func (o *ActivityManagerApiCreateActivity400Response) SetCost(v float64)`

SetCost sets Cost field to given value.

### HasCost

`func (o *ActivityManagerApiCreateActivity400Response) HasCost() bool`

HasCost returns a boolean if a field has been set.

### GetPriority

`func (o *ActivityManagerApiCreateActivity400Response) GetPriority() int32`

GetPriority returns the Priority field if non-nil, zero value otherwise.

### GetPriorityOk

`func (o *ActivityManagerApiCreateActivity400Response) GetPriorityOk() (*int32, bool)`

GetPriorityOk returns a tuple with the Priority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriority

`func (o *ActivityManagerApiCreateActivity400Response) SetPriority(v int32)`

SetPriority sets Priority field to given value.

### HasPriority

`func (o *ActivityManagerApiCreateActivity400Response) HasPriority() bool`

HasPriority returns a boolean if a field has been set.

### GetDueDateTime

`func (o *ActivityManagerApiCreateActivity400Response) GetDueDateTime() time.Time`

GetDueDateTime returns the DueDateTime field if non-nil, zero value otherwise.

### GetDueDateTimeOk

`func (o *ActivityManagerApiCreateActivity400Response) GetDueDateTimeOk() (*time.Time, bool)`

GetDueDateTimeOk returns a tuple with the DueDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueDateTime

`func (o *ActivityManagerApiCreateActivity400Response) SetDueDateTime(v time.Time)`

SetDueDateTime sets DueDateTime field to given value.

### HasDueDateTime

`func (o *ActivityManagerApiCreateActivity400Response) HasDueDateTime() bool`

HasDueDateTime returns a boolean if a field has been set.

### GetCustomerCode

`func (o *ActivityManagerApiCreateActivity400Response) GetCustomerCode() string`

GetCustomerCode returns the CustomerCode field if non-nil, zero value otherwise.

### GetCustomerCodeOk

`func (o *ActivityManagerApiCreateActivity400Response) GetCustomerCodeOk() (*string, bool)`

GetCustomerCodeOk returns a tuple with the CustomerCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerCode

`func (o *ActivityManagerApiCreateActivity400Response) SetCustomerCode(v string)`

SetCustomerCode sets CustomerCode field to given value.

### HasCustomerCode

`func (o *ActivityManagerApiCreateActivity400Response) HasCustomerCode() bool`

HasCustomerCode returns a boolean if a field has been set.

### GetSupplierCode

`func (o *ActivityManagerApiCreateActivity400Response) GetSupplierCode() string`

GetSupplierCode returns the SupplierCode field if non-nil, zero value otherwise.

### GetSupplierCodeOk

`func (o *ActivityManagerApiCreateActivity400Response) GetSupplierCodeOk() (*string, bool)`

GetSupplierCodeOk returns a tuple with the SupplierCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierCode

`func (o *ActivityManagerApiCreateActivity400Response) SetSupplierCode(v string)`

SetSupplierCode sets SupplierCode field to given value.

### HasSupplierCode

`func (o *ActivityManagerApiCreateActivity400Response) HasSupplierCode() bool`

HasSupplierCode returns a boolean if a field has been set.

### GetLocation

`func (o *ActivityManagerApiCreateActivity400Response) GetLocation() string`

GetLocation returns the Location field if non-nil, zero value otherwise.

### GetLocationOk

`func (o *ActivityManagerApiCreateActivity400Response) GetLocationOk() (*string, bool)`

GetLocationOk returns a tuple with the Location field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocation

`func (o *ActivityManagerApiCreateActivity400Response) SetLocation(v string)`

SetLocation sets Location field to given value.

### HasLocation

`func (o *ActivityManagerApiCreateActivity400Response) HasLocation() bool`

HasLocation returns a boolean if a field has been set.

### GetPrivate

`func (o *ActivityManagerApiCreateActivity400Response) GetPrivate() bool`

GetPrivate returns the Private field if non-nil, zero value otherwise.

### GetPrivateOk

`func (o *ActivityManagerApiCreateActivity400Response) GetPrivateOk() (*bool, bool)`

GetPrivateOk returns a tuple with the Private field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrivate

`func (o *ActivityManagerApiCreateActivity400Response) SetPrivate(v bool)`

SetPrivate sets Private field to given value.

### HasPrivate

`func (o *ActivityManagerApiCreateActivity400Response) HasPrivate() bool`

HasPrivate returns a boolean if a field has been set.

### GetAssignedTo

`func (o *ActivityManagerApiCreateActivity400Response) GetAssignedTo() string`

GetAssignedTo returns the AssignedTo field if non-nil, zero value otherwise.

### GetAssignedToOk

`func (o *ActivityManagerApiCreateActivity400Response) GetAssignedToOk() (*string, bool)`

GetAssignedToOk returns a tuple with the AssignedTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignedTo

`func (o *ActivityManagerApiCreateActivity400Response) SetAssignedTo(v string)`

SetAssignedTo sets AssignedTo field to given value.

### HasAssignedTo

`func (o *ActivityManagerApiCreateActivity400Response) HasAssignedTo() bool`

HasAssignedTo returns a boolean if a field has been set.

### GetAssignedBy

`func (o *ActivityManagerApiCreateActivity400Response) GetAssignedBy() string`

GetAssignedBy returns the AssignedBy field if non-nil, zero value otherwise.

### GetAssignedByOk

`func (o *ActivityManagerApiCreateActivity400Response) GetAssignedByOk() (*string, bool)`

GetAssignedByOk returns a tuple with the AssignedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignedBy

`func (o *ActivityManagerApiCreateActivity400Response) SetAssignedBy(v string)`

SetAssignedBy sets AssignedBy field to given value.

### HasAssignedBy

`func (o *ActivityManagerApiCreateActivity400Response) HasAssignedBy() bool`

HasAssignedBy returns a boolean if a field has been set.

### GetAssignedToDepartment

`func (o *ActivityManagerApiCreateActivity400Response) GetAssignedToDepartment() string`

GetAssignedToDepartment returns the AssignedToDepartment field if non-nil, zero value otherwise.

### GetAssignedToDepartmentOk

`func (o *ActivityManagerApiCreateActivity400Response) GetAssignedToDepartmentOk() (*string, bool)`

GetAssignedToDepartmentOk returns a tuple with the AssignedToDepartment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignedToDepartment

`func (o *ActivityManagerApiCreateActivity400Response) SetAssignedToDepartment(v string)`

SetAssignedToDepartment sets AssignedToDepartment field to given value.

### HasAssignedToDepartment

`func (o *ActivityManagerApiCreateActivity400Response) HasAssignedToDepartment() bool`

HasAssignedToDepartment returns a boolean if a field has been set.

### GetInvolvedUsers

`func (o *ActivityManagerApiCreateActivity400Response) GetInvolvedUsers() []string`

GetInvolvedUsers returns the InvolvedUsers field if non-nil, zero value otherwise.

### GetInvolvedUsersOk

`func (o *ActivityManagerApiCreateActivity400Response) GetInvolvedUsersOk() (*[]string, bool)`

GetInvolvedUsersOk returns a tuple with the InvolvedUsers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvolvedUsers

`func (o *ActivityManagerApiCreateActivity400Response) SetInvolvedUsers(v []string)`

SetInvolvedUsers sets InvolvedUsers field to given value.

### HasInvolvedUsers

`func (o *ActivityManagerApiCreateActivity400Response) HasInvolvedUsers() bool`

HasInvolvedUsers returns a boolean if a field has been set.

### GetParentActivity

`func (o *ActivityManagerApiCreateActivity400Response) GetParentActivity() string`

GetParentActivity returns the ParentActivity field if non-nil, zero value otherwise.

### GetParentActivityOk

`func (o *ActivityManagerApiCreateActivity400Response) GetParentActivityOk() (*string, bool)`

GetParentActivityOk returns a tuple with the ParentActivity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentActivity

`func (o *ActivityManagerApiCreateActivity400Response) SetParentActivity(v string)`

SetParentActivity sets ParentActivity field to given value.

### HasParentActivity

`func (o *ActivityManagerApiCreateActivity400Response) HasParentActivity() bool`

HasParentActivity returns a boolean if a field has been set.

### GetPlannedStartDateTime

`func (o *ActivityManagerApiCreateActivity400Response) GetPlannedStartDateTime() time.Time`

GetPlannedStartDateTime returns the PlannedStartDateTime field if non-nil, zero value otherwise.

### GetPlannedStartDateTimeOk

`func (o *ActivityManagerApiCreateActivity400Response) GetPlannedStartDateTimeOk() (*time.Time, bool)`

GetPlannedStartDateTimeOk returns a tuple with the PlannedStartDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlannedStartDateTime

`func (o *ActivityManagerApiCreateActivity400Response) SetPlannedStartDateTime(v time.Time)`

SetPlannedStartDateTime sets PlannedStartDateTime field to given value.

### HasPlannedStartDateTime

`func (o *ActivityManagerApiCreateActivity400Response) HasPlannedStartDateTime() bool`

HasPlannedStartDateTime returns a boolean if a field has been set.

### GetPlannedFinishDateTime

`func (o *ActivityManagerApiCreateActivity400Response) GetPlannedFinishDateTime() time.Time`

GetPlannedFinishDateTime returns the PlannedFinishDateTime field if non-nil, zero value otherwise.

### GetPlannedFinishDateTimeOk

`func (o *ActivityManagerApiCreateActivity400Response) GetPlannedFinishDateTimeOk() (*time.Time, bool)`

GetPlannedFinishDateTimeOk returns a tuple with the PlannedFinishDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlannedFinishDateTime

`func (o *ActivityManagerApiCreateActivity400Response) SetPlannedFinishDateTime(v time.Time)`

SetPlannedFinishDateTime sets PlannedFinishDateTime field to given value.

### HasPlannedFinishDateTime

`func (o *ActivityManagerApiCreateActivity400Response) HasPlannedFinishDateTime() bool`

HasPlannedFinishDateTime returns a boolean if a field has been set.

### GetPercentageCompletion

`func (o *ActivityManagerApiCreateActivity400Response) GetPercentageCompletion() int32`

GetPercentageCompletion returns the PercentageCompletion field if non-nil, zero value otherwise.

### GetPercentageCompletionOk

`func (o *ActivityManagerApiCreateActivity400Response) GetPercentageCompletionOk() (*int32, bool)`

GetPercentageCompletionOk returns a tuple with the PercentageCompletion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPercentageCompletion

`func (o *ActivityManagerApiCreateActivity400Response) SetPercentageCompletion(v int32)`

SetPercentageCompletion sets PercentageCompletion field to given value.

### HasPercentageCompletion

`func (o *ActivityManagerApiCreateActivity400Response) HasPercentageCompletion() bool`

HasPercentageCompletion returns a boolean if a field has been set.

### GetSuggestionNos

`func (o *ActivityManagerApiCreateActivity400Response) GetSuggestionNos() []int32`

GetSuggestionNos returns the SuggestionNos field if non-nil, zero value otherwise.

### GetSuggestionNosOk

`func (o *ActivityManagerApiCreateActivity400Response) GetSuggestionNosOk() (*[]int32, bool)`

GetSuggestionNosOk returns a tuple with the SuggestionNos field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuggestionNos

`func (o *ActivityManagerApiCreateActivity400Response) SetSuggestionNos(v []int32)`

SetSuggestionNos sets SuggestionNos field to given value.

### HasSuggestionNos

`func (o *ActivityManagerApiCreateActivity400Response) HasSuggestionNos() bool`

HasSuggestionNos returns a boolean if a field has been set.

### GetComments

`func (o *ActivityManagerApiCreateActivity400Response) GetComments() []string`

GetComments returns the Comments field if non-nil, zero value otherwise.

### GetCommentsOk

`func (o *ActivityManagerApiCreateActivity400Response) GetCommentsOk() (*[]string, bool)`

GetCommentsOk returns a tuple with the Comments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComments

`func (o *ActivityManagerApiCreateActivity400Response) SetComments(v []string)`

SetComments sets Comments field to given value.

### HasComments

`func (o *ActivityManagerApiCreateActivity400Response) HasComments() bool`

HasComments returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


