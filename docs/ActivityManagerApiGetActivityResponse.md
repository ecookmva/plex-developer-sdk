# ActivityManagerApiGetActivityResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ActivityId** | Pointer to **string** | The ID of the activity. | [optional] 
**TenantId** | Pointer to **string** | The Tenant ID. | [optional] 
**ActivityName** | Pointer to **string** | The name of the activity. | [optional] 
**Description** | Pointer to **string** | The description of the activity. | [optional] 
**ActivityType** | Pointer to **string** | The activity type. | [optional] 
**ActivityStatus** | Pointer to **string** | The status information of the activity. | [optional] 
**StatusNote** | Pointer to **string** | A note on the status of the activity. | [optional] 
**Priority** | Pointer to **int32** | The priority information about the activity. | [optional] 
**DueDateTime** | Pointer to **time.Time** | The due date of the activity. | [optional] 
**AssignedTo** | Pointer to **string** | The User ID assigned to the activity. | [optional] 
**AssignedBy** | Pointer to **string** | The User ID assigned by the activity. | [optional] 
**Cost** | Pointer to **float64** | The cost of the activity. | [optional] 
**CustomerCode** | Pointer to **string** | The customer code of the activity. | [optional] 
**SupplierCode** | Pointer to **string** | The supplier code of the activity. | [optional] 
**Location** | Pointer to **string** | The location of the activity. | [optional] 
**Private** | Pointer to **bool** | Indicates whether the activity is private or not. | [optional] 
**AssignedToDepartment** | Pointer to **string** | The department code to which the activity is assigned. | [optional] 
**InvolvedUsers** | Pointer to **[]string** | The user involved in the activity. | [optional] 
**ParentActivity** | Pointer to **string** | The parent ID of the activity. | [optional] 
**ImprovementProject** | Pointer to **string** | The improvement project number of the activity. | [optional] 
**ExpenseProject** | Pointer to **string** | The expense project key of the activity. | [optional] 
**StrategicObjective** | Pointer to **string** | The objective of the activity. | [optional] 
**Opportunity** | Pointer to **string** | The opportunity associated with the activity. | [optional] 
**MetricName** | Pointer to **string** | The metric name of the activity. | [optional] 
**ChildActivities** | Pointer to **[]string** | The IDs of child activities. | [optional] 
**PlannedStartDateTime** | Pointer to **time.Time** | The planned start date of the activity. | [optional] 
**PlannedFinishDateTime** | Pointer to **time.Time** | The planned finish date of the activity. | [optional] 
**ActualStartDateTime** | Pointer to **time.Time** | The actual start date of the activity. | [optional] 
**ActualFinishDateTime** | Pointer to **time.Time** | The actual finish date of the activity. | [optional] 
**PercentageCompletion** | Pointer to **float64** | The completion percentage of the activity. | [optional] 
**Suggestions** | Pointer to **[]string** | The suggestions related to the activity. | [optional] 
**Comments** | Pointer to **[]string** | The comments related to the activity. | [optional] 
**CreatedDateTime** | Pointer to **time.Time** | The date the activity was created. | [optional] 

## Methods

### NewActivityManagerApiGetActivityResponse

`func NewActivityManagerApiGetActivityResponse() *ActivityManagerApiGetActivityResponse`

NewActivityManagerApiGetActivityResponse instantiates a new ActivityManagerApiGetActivityResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewActivityManagerApiGetActivityResponseWithDefaults

`func NewActivityManagerApiGetActivityResponseWithDefaults() *ActivityManagerApiGetActivityResponse`

NewActivityManagerApiGetActivityResponseWithDefaults instantiates a new ActivityManagerApiGetActivityResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActivityId

`func (o *ActivityManagerApiGetActivityResponse) GetActivityId() string`

GetActivityId returns the ActivityId field if non-nil, zero value otherwise.

### GetActivityIdOk

`func (o *ActivityManagerApiGetActivityResponse) GetActivityIdOk() (*string, bool)`

GetActivityIdOk returns a tuple with the ActivityId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivityId

`func (o *ActivityManagerApiGetActivityResponse) SetActivityId(v string)`

SetActivityId sets ActivityId field to given value.

### HasActivityId

`func (o *ActivityManagerApiGetActivityResponse) HasActivityId() bool`

HasActivityId returns a boolean if a field has been set.

### GetTenantId

`func (o *ActivityManagerApiGetActivityResponse) GetTenantId() string`

GetTenantId returns the TenantId field if non-nil, zero value otherwise.

### GetTenantIdOk

`func (o *ActivityManagerApiGetActivityResponse) GetTenantIdOk() (*string, bool)`

GetTenantIdOk returns a tuple with the TenantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantId

`func (o *ActivityManagerApiGetActivityResponse) SetTenantId(v string)`

SetTenantId sets TenantId field to given value.

### HasTenantId

`func (o *ActivityManagerApiGetActivityResponse) HasTenantId() bool`

HasTenantId returns a boolean if a field has been set.

### GetActivityName

`func (o *ActivityManagerApiGetActivityResponse) GetActivityName() string`

GetActivityName returns the ActivityName field if non-nil, zero value otherwise.

### GetActivityNameOk

`func (o *ActivityManagerApiGetActivityResponse) GetActivityNameOk() (*string, bool)`

GetActivityNameOk returns a tuple with the ActivityName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivityName

`func (o *ActivityManagerApiGetActivityResponse) SetActivityName(v string)`

SetActivityName sets ActivityName field to given value.

### HasActivityName

`func (o *ActivityManagerApiGetActivityResponse) HasActivityName() bool`

HasActivityName returns a boolean if a field has been set.

### GetDescription

`func (o *ActivityManagerApiGetActivityResponse) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ActivityManagerApiGetActivityResponse) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ActivityManagerApiGetActivityResponse) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ActivityManagerApiGetActivityResponse) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetActivityType

`func (o *ActivityManagerApiGetActivityResponse) GetActivityType() string`

GetActivityType returns the ActivityType field if non-nil, zero value otherwise.

### GetActivityTypeOk

`func (o *ActivityManagerApiGetActivityResponse) GetActivityTypeOk() (*string, bool)`

GetActivityTypeOk returns a tuple with the ActivityType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivityType

`func (o *ActivityManagerApiGetActivityResponse) SetActivityType(v string)`

SetActivityType sets ActivityType field to given value.

### HasActivityType

`func (o *ActivityManagerApiGetActivityResponse) HasActivityType() bool`

HasActivityType returns a boolean if a field has been set.

### GetActivityStatus

`func (o *ActivityManagerApiGetActivityResponse) GetActivityStatus() string`

GetActivityStatus returns the ActivityStatus field if non-nil, zero value otherwise.

### GetActivityStatusOk

`func (o *ActivityManagerApiGetActivityResponse) GetActivityStatusOk() (*string, bool)`

GetActivityStatusOk returns a tuple with the ActivityStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivityStatus

`func (o *ActivityManagerApiGetActivityResponse) SetActivityStatus(v string)`

SetActivityStatus sets ActivityStatus field to given value.

### HasActivityStatus

`func (o *ActivityManagerApiGetActivityResponse) HasActivityStatus() bool`

HasActivityStatus returns a boolean if a field has been set.

### GetStatusNote

`func (o *ActivityManagerApiGetActivityResponse) GetStatusNote() string`

GetStatusNote returns the StatusNote field if non-nil, zero value otherwise.

### GetStatusNoteOk

`func (o *ActivityManagerApiGetActivityResponse) GetStatusNoteOk() (*string, bool)`

GetStatusNoteOk returns a tuple with the StatusNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatusNote

`func (o *ActivityManagerApiGetActivityResponse) SetStatusNote(v string)`

SetStatusNote sets StatusNote field to given value.

### HasStatusNote

`func (o *ActivityManagerApiGetActivityResponse) HasStatusNote() bool`

HasStatusNote returns a boolean if a field has been set.

### GetPriority

`func (o *ActivityManagerApiGetActivityResponse) GetPriority() int32`

GetPriority returns the Priority field if non-nil, zero value otherwise.

### GetPriorityOk

`func (o *ActivityManagerApiGetActivityResponse) GetPriorityOk() (*int32, bool)`

GetPriorityOk returns a tuple with the Priority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriority

`func (o *ActivityManagerApiGetActivityResponse) SetPriority(v int32)`

SetPriority sets Priority field to given value.

### HasPriority

`func (o *ActivityManagerApiGetActivityResponse) HasPriority() bool`

HasPriority returns a boolean if a field has been set.

### GetDueDateTime

`func (o *ActivityManagerApiGetActivityResponse) GetDueDateTime() time.Time`

GetDueDateTime returns the DueDateTime field if non-nil, zero value otherwise.

### GetDueDateTimeOk

`func (o *ActivityManagerApiGetActivityResponse) GetDueDateTimeOk() (*time.Time, bool)`

GetDueDateTimeOk returns a tuple with the DueDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueDateTime

`func (o *ActivityManagerApiGetActivityResponse) SetDueDateTime(v time.Time)`

SetDueDateTime sets DueDateTime field to given value.

### HasDueDateTime

`func (o *ActivityManagerApiGetActivityResponse) HasDueDateTime() bool`

HasDueDateTime returns a boolean if a field has been set.

### GetAssignedTo

`func (o *ActivityManagerApiGetActivityResponse) GetAssignedTo() string`

GetAssignedTo returns the AssignedTo field if non-nil, zero value otherwise.

### GetAssignedToOk

`func (o *ActivityManagerApiGetActivityResponse) GetAssignedToOk() (*string, bool)`

GetAssignedToOk returns a tuple with the AssignedTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignedTo

`func (o *ActivityManagerApiGetActivityResponse) SetAssignedTo(v string)`

SetAssignedTo sets AssignedTo field to given value.

### HasAssignedTo

`func (o *ActivityManagerApiGetActivityResponse) HasAssignedTo() bool`

HasAssignedTo returns a boolean if a field has been set.

### GetAssignedBy

`func (o *ActivityManagerApiGetActivityResponse) GetAssignedBy() string`

GetAssignedBy returns the AssignedBy field if non-nil, zero value otherwise.

### GetAssignedByOk

`func (o *ActivityManagerApiGetActivityResponse) GetAssignedByOk() (*string, bool)`

GetAssignedByOk returns a tuple with the AssignedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignedBy

`func (o *ActivityManagerApiGetActivityResponse) SetAssignedBy(v string)`

SetAssignedBy sets AssignedBy field to given value.

### HasAssignedBy

`func (o *ActivityManagerApiGetActivityResponse) HasAssignedBy() bool`

HasAssignedBy returns a boolean if a field has been set.

### GetCost

`func (o *ActivityManagerApiGetActivityResponse) GetCost() float64`

GetCost returns the Cost field if non-nil, zero value otherwise.

### GetCostOk

`func (o *ActivityManagerApiGetActivityResponse) GetCostOk() (*float64, bool)`

GetCostOk returns a tuple with the Cost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCost

`func (o *ActivityManagerApiGetActivityResponse) SetCost(v float64)`

SetCost sets Cost field to given value.

### HasCost

`func (o *ActivityManagerApiGetActivityResponse) HasCost() bool`

HasCost returns a boolean if a field has been set.

### GetCustomerCode

`func (o *ActivityManagerApiGetActivityResponse) GetCustomerCode() string`

GetCustomerCode returns the CustomerCode field if non-nil, zero value otherwise.

### GetCustomerCodeOk

`func (o *ActivityManagerApiGetActivityResponse) GetCustomerCodeOk() (*string, bool)`

GetCustomerCodeOk returns a tuple with the CustomerCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerCode

`func (o *ActivityManagerApiGetActivityResponse) SetCustomerCode(v string)`

SetCustomerCode sets CustomerCode field to given value.

### HasCustomerCode

`func (o *ActivityManagerApiGetActivityResponse) HasCustomerCode() bool`

HasCustomerCode returns a boolean if a field has been set.

### GetSupplierCode

`func (o *ActivityManagerApiGetActivityResponse) GetSupplierCode() string`

GetSupplierCode returns the SupplierCode field if non-nil, zero value otherwise.

### GetSupplierCodeOk

`func (o *ActivityManagerApiGetActivityResponse) GetSupplierCodeOk() (*string, bool)`

GetSupplierCodeOk returns a tuple with the SupplierCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierCode

`func (o *ActivityManagerApiGetActivityResponse) SetSupplierCode(v string)`

SetSupplierCode sets SupplierCode field to given value.

### HasSupplierCode

`func (o *ActivityManagerApiGetActivityResponse) HasSupplierCode() bool`

HasSupplierCode returns a boolean if a field has been set.

### GetLocation

`func (o *ActivityManagerApiGetActivityResponse) GetLocation() string`

GetLocation returns the Location field if non-nil, zero value otherwise.

### GetLocationOk

`func (o *ActivityManagerApiGetActivityResponse) GetLocationOk() (*string, bool)`

GetLocationOk returns a tuple with the Location field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocation

`func (o *ActivityManagerApiGetActivityResponse) SetLocation(v string)`

SetLocation sets Location field to given value.

### HasLocation

`func (o *ActivityManagerApiGetActivityResponse) HasLocation() bool`

HasLocation returns a boolean if a field has been set.

### GetPrivate

`func (o *ActivityManagerApiGetActivityResponse) GetPrivate() bool`

GetPrivate returns the Private field if non-nil, zero value otherwise.

### GetPrivateOk

`func (o *ActivityManagerApiGetActivityResponse) GetPrivateOk() (*bool, bool)`

GetPrivateOk returns a tuple with the Private field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrivate

`func (o *ActivityManagerApiGetActivityResponse) SetPrivate(v bool)`

SetPrivate sets Private field to given value.

### HasPrivate

`func (o *ActivityManagerApiGetActivityResponse) HasPrivate() bool`

HasPrivate returns a boolean if a field has been set.

### GetAssignedToDepartment

`func (o *ActivityManagerApiGetActivityResponse) GetAssignedToDepartment() string`

GetAssignedToDepartment returns the AssignedToDepartment field if non-nil, zero value otherwise.

### GetAssignedToDepartmentOk

`func (o *ActivityManagerApiGetActivityResponse) GetAssignedToDepartmentOk() (*string, bool)`

GetAssignedToDepartmentOk returns a tuple with the AssignedToDepartment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignedToDepartment

`func (o *ActivityManagerApiGetActivityResponse) SetAssignedToDepartment(v string)`

SetAssignedToDepartment sets AssignedToDepartment field to given value.

### HasAssignedToDepartment

`func (o *ActivityManagerApiGetActivityResponse) HasAssignedToDepartment() bool`

HasAssignedToDepartment returns a boolean if a field has been set.

### GetInvolvedUsers

`func (o *ActivityManagerApiGetActivityResponse) GetInvolvedUsers() []string`

GetInvolvedUsers returns the InvolvedUsers field if non-nil, zero value otherwise.

### GetInvolvedUsersOk

`func (o *ActivityManagerApiGetActivityResponse) GetInvolvedUsersOk() (*[]string, bool)`

GetInvolvedUsersOk returns a tuple with the InvolvedUsers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvolvedUsers

`func (o *ActivityManagerApiGetActivityResponse) SetInvolvedUsers(v []string)`

SetInvolvedUsers sets InvolvedUsers field to given value.

### HasInvolvedUsers

`func (o *ActivityManagerApiGetActivityResponse) HasInvolvedUsers() bool`

HasInvolvedUsers returns a boolean if a field has been set.

### GetParentActivity

`func (o *ActivityManagerApiGetActivityResponse) GetParentActivity() string`

GetParentActivity returns the ParentActivity field if non-nil, zero value otherwise.

### GetParentActivityOk

`func (o *ActivityManagerApiGetActivityResponse) GetParentActivityOk() (*string, bool)`

GetParentActivityOk returns a tuple with the ParentActivity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentActivity

`func (o *ActivityManagerApiGetActivityResponse) SetParentActivity(v string)`

SetParentActivity sets ParentActivity field to given value.

### HasParentActivity

`func (o *ActivityManagerApiGetActivityResponse) HasParentActivity() bool`

HasParentActivity returns a boolean if a field has been set.

### GetImprovementProject

`func (o *ActivityManagerApiGetActivityResponse) GetImprovementProject() string`

GetImprovementProject returns the ImprovementProject field if non-nil, zero value otherwise.

### GetImprovementProjectOk

`func (o *ActivityManagerApiGetActivityResponse) GetImprovementProjectOk() (*string, bool)`

GetImprovementProjectOk returns a tuple with the ImprovementProject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImprovementProject

`func (o *ActivityManagerApiGetActivityResponse) SetImprovementProject(v string)`

SetImprovementProject sets ImprovementProject field to given value.

### HasImprovementProject

`func (o *ActivityManagerApiGetActivityResponse) HasImprovementProject() bool`

HasImprovementProject returns a boolean if a field has been set.

### GetExpenseProject

`func (o *ActivityManagerApiGetActivityResponse) GetExpenseProject() string`

GetExpenseProject returns the ExpenseProject field if non-nil, zero value otherwise.

### GetExpenseProjectOk

`func (o *ActivityManagerApiGetActivityResponse) GetExpenseProjectOk() (*string, bool)`

GetExpenseProjectOk returns a tuple with the ExpenseProject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpenseProject

`func (o *ActivityManagerApiGetActivityResponse) SetExpenseProject(v string)`

SetExpenseProject sets ExpenseProject field to given value.

### HasExpenseProject

`func (o *ActivityManagerApiGetActivityResponse) HasExpenseProject() bool`

HasExpenseProject returns a boolean if a field has been set.

### GetStrategicObjective

`func (o *ActivityManagerApiGetActivityResponse) GetStrategicObjective() string`

GetStrategicObjective returns the StrategicObjective field if non-nil, zero value otherwise.

### GetStrategicObjectiveOk

`func (o *ActivityManagerApiGetActivityResponse) GetStrategicObjectiveOk() (*string, bool)`

GetStrategicObjectiveOk returns a tuple with the StrategicObjective field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStrategicObjective

`func (o *ActivityManagerApiGetActivityResponse) SetStrategicObjective(v string)`

SetStrategicObjective sets StrategicObjective field to given value.

### HasStrategicObjective

`func (o *ActivityManagerApiGetActivityResponse) HasStrategicObjective() bool`

HasStrategicObjective returns a boolean if a field has been set.

### GetOpportunity

`func (o *ActivityManagerApiGetActivityResponse) GetOpportunity() string`

GetOpportunity returns the Opportunity field if non-nil, zero value otherwise.

### GetOpportunityOk

`func (o *ActivityManagerApiGetActivityResponse) GetOpportunityOk() (*string, bool)`

GetOpportunityOk returns a tuple with the Opportunity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpportunity

`func (o *ActivityManagerApiGetActivityResponse) SetOpportunity(v string)`

SetOpportunity sets Opportunity field to given value.

### HasOpportunity

`func (o *ActivityManagerApiGetActivityResponse) HasOpportunity() bool`

HasOpportunity returns a boolean if a field has been set.

### GetMetricName

`func (o *ActivityManagerApiGetActivityResponse) GetMetricName() string`

GetMetricName returns the MetricName field if non-nil, zero value otherwise.

### GetMetricNameOk

`func (o *ActivityManagerApiGetActivityResponse) GetMetricNameOk() (*string, bool)`

GetMetricNameOk returns a tuple with the MetricName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetricName

`func (o *ActivityManagerApiGetActivityResponse) SetMetricName(v string)`

SetMetricName sets MetricName field to given value.

### HasMetricName

`func (o *ActivityManagerApiGetActivityResponse) HasMetricName() bool`

HasMetricName returns a boolean if a field has been set.

### GetChildActivities

`func (o *ActivityManagerApiGetActivityResponse) GetChildActivities() []string`

GetChildActivities returns the ChildActivities field if non-nil, zero value otherwise.

### GetChildActivitiesOk

`func (o *ActivityManagerApiGetActivityResponse) GetChildActivitiesOk() (*[]string, bool)`

GetChildActivitiesOk returns a tuple with the ChildActivities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChildActivities

`func (o *ActivityManagerApiGetActivityResponse) SetChildActivities(v []string)`

SetChildActivities sets ChildActivities field to given value.

### HasChildActivities

`func (o *ActivityManagerApiGetActivityResponse) HasChildActivities() bool`

HasChildActivities returns a boolean if a field has been set.

### GetPlannedStartDateTime

`func (o *ActivityManagerApiGetActivityResponse) GetPlannedStartDateTime() time.Time`

GetPlannedStartDateTime returns the PlannedStartDateTime field if non-nil, zero value otherwise.

### GetPlannedStartDateTimeOk

`func (o *ActivityManagerApiGetActivityResponse) GetPlannedStartDateTimeOk() (*time.Time, bool)`

GetPlannedStartDateTimeOk returns a tuple with the PlannedStartDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlannedStartDateTime

`func (o *ActivityManagerApiGetActivityResponse) SetPlannedStartDateTime(v time.Time)`

SetPlannedStartDateTime sets PlannedStartDateTime field to given value.

### HasPlannedStartDateTime

`func (o *ActivityManagerApiGetActivityResponse) HasPlannedStartDateTime() bool`

HasPlannedStartDateTime returns a boolean if a field has been set.

### GetPlannedFinishDateTime

`func (o *ActivityManagerApiGetActivityResponse) GetPlannedFinishDateTime() time.Time`

GetPlannedFinishDateTime returns the PlannedFinishDateTime field if non-nil, zero value otherwise.

### GetPlannedFinishDateTimeOk

`func (o *ActivityManagerApiGetActivityResponse) GetPlannedFinishDateTimeOk() (*time.Time, bool)`

GetPlannedFinishDateTimeOk returns a tuple with the PlannedFinishDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlannedFinishDateTime

`func (o *ActivityManagerApiGetActivityResponse) SetPlannedFinishDateTime(v time.Time)`

SetPlannedFinishDateTime sets PlannedFinishDateTime field to given value.

### HasPlannedFinishDateTime

`func (o *ActivityManagerApiGetActivityResponse) HasPlannedFinishDateTime() bool`

HasPlannedFinishDateTime returns a boolean if a field has been set.

### GetActualStartDateTime

`func (o *ActivityManagerApiGetActivityResponse) GetActualStartDateTime() time.Time`

GetActualStartDateTime returns the ActualStartDateTime field if non-nil, zero value otherwise.

### GetActualStartDateTimeOk

`func (o *ActivityManagerApiGetActivityResponse) GetActualStartDateTimeOk() (*time.Time, bool)`

GetActualStartDateTimeOk returns a tuple with the ActualStartDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActualStartDateTime

`func (o *ActivityManagerApiGetActivityResponse) SetActualStartDateTime(v time.Time)`

SetActualStartDateTime sets ActualStartDateTime field to given value.

### HasActualStartDateTime

`func (o *ActivityManagerApiGetActivityResponse) HasActualStartDateTime() bool`

HasActualStartDateTime returns a boolean if a field has been set.

### GetActualFinishDateTime

`func (o *ActivityManagerApiGetActivityResponse) GetActualFinishDateTime() time.Time`

GetActualFinishDateTime returns the ActualFinishDateTime field if non-nil, zero value otherwise.

### GetActualFinishDateTimeOk

`func (o *ActivityManagerApiGetActivityResponse) GetActualFinishDateTimeOk() (*time.Time, bool)`

GetActualFinishDateTimeOk returns a tuple with the ActualFinishDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActualFinishDateTime

`func (o *ActivityManagerApiGetActivityResponse) SetActualFinishDateTime(v time.Time)`

SetActualFinishDateTime sets ActualFinishDateTime field to given value.

### HasActualFinishDateTime

`func (o *ActivityManagerApiGetActivityResponse) HasActualFinishDateTime() bool`

HasActualFinishDateTime returns a boolean if a field has been set.

### GetPercentageCompletion

`func (o *ActivityManagerApiGetActivityResponse) GetPercentageCompletion() float64`

GetPercentageCompletion returns the PercentageCompletion field if non-nil, zero value otherwise.

### GetPercentageCompletionOk

`func (o *ActivityManagerApiGetActivityResponse) GetPercentageCompletionOk() (*float64, bool)`

GetPercentageCompletionOk returns a tuple with the PercentageCompletion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPercentageCompletion

`func (o *ActivityManagerApiGetActivityResponse) SetPercentageCompletion(v float64)`

SetPercentageCompletion sets PercentageCompletion field to given value.

### HasPercentageCompletion

`func (o *ActivityManagerApiGetActivityResponse) HasPercentageCompletion() bool`

HasPercentageCompletion returns a boolean if a field has been set.

### GetSuggestions

`func (o *ActivityManagerApiGetActivityResponse) GetSuggestions() []string`

GetSuggestions returns the Suggestions field if non-nil, zero value otherwise.

### GetSuggestionsOk

`func (o *ActivityManagerApiGetActivityResponse) GetSuggestionsOk() (*[]string, bool)`

GetSuggestionsOk returns a tuple with the Suggestions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuggestions

`func (o *ActivityManagerApiGetActivityResponse) SetSuggestions(v []string)`

SetSuggestions sets Suggestions field to given value.

### HasSuggestions

`func (o *ActivityManagerApiGetActivityResponse) HasSuggestions() bool`

HasSuggestions returns a boolean if a field has been set.

### GetComments

`func (o *ActivityManagerApiGetActivityResponse) GetComments() []string`

GetComments returns the Comments field if non-nil, zero value otherwise.

### GetCommentsOk

`func (o *ActivityManagerApiGetActivityResponse) GetCommentsOk() (*[]string, bool)`

GetCommentsOk returns a tuple with the Comments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComments

`func (o *ActivityManagerApiGetActivityResponse) SetComments(v []string)`

SetComments sets Comments field to given value.

### HasComments

`func (o *ActivityManagerApiGetActivityResponse) HasComments() bool`

HasComments returns a boolean if a field has been set.

### GetCreatedDateTime

`func (o *ActivityManagerApiGetActivityResponse) GetCreatedDateTime() time.Time`

GetCreatedDateTime returns the CreatedDateTime field if non-nil, zero value otherwise.

### GetCreatedDateTimeOk

`func (o *ActivityManagerApiGetActivityResponse) GetCreatedDateTimeOk() (*time.Time, bool)`

GetCreatedDateTimeOk returns a tuple with the CreatedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDateTime

`func (o *ActivityManagerApiGetActivityResponse) SetCreatedDateTime(v time.Time)`

SetCreatedDateTime sets CreatedDateTime field to given value.

### HasCreatedDateTime

`func (o *ActivityManagerApiGetActivityResponse) HasCreatedDateTime() bool`

HasCreatedDateTime returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


