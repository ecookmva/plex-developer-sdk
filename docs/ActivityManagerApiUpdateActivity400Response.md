# ActivityManagerApiUpdateActivity400Response

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

### NewActivityManagerApiUpdateActivity400Response

`func NewActivityManagerApiUpdateActivity400Response() *ActivityManagerApiUpdateActivity400Response`

NewActivityManagerApiUpdateActivity400Response instantiates a new ActivityManagerApiUpdateActivity400Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewActivityManagerApiUpdateActivity400ResponseWithDefaults

`func NewActivityManagerApiUpdateActivity400ResponseWithDefaults() *ActivityManagerApiUpdateActivity400Response`

NewActivityManagerApiUpdateActivity400ResponseWithDefaults instantiates a new ActivityManagerApiUpdateActivity400Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTenantId

`func (o *ActivityManagerApiUpdateActivity400Response) GetTenantId() string`

GetTenantId returns the TenantId field if non-nil, zero value otherwise.

### GetTenantIdOk

`func (o *ActivityManagerApiUpdateActivity400Response) GetTenantIdOk() (*string, bool)`

GetTenantIdOk returns a tuple with the TenantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantId

`func (o *ActivityManagerApiUpdateActivity400Response) SetTenantId(v string)`

SetTenantId sets TenantId field to given value.

### HasTenantId

`func (o *ActivityManagerApiUpdateActivity400Response) HasTenantId() bool`

HasTenantId returns a boolean if a field has been set.

### GetActivityId

`func (o *ActivityManagerApiUpdateActivity400Response) GetActivityId() string`

GetActivityId returns the ActivityId field if non-nil, zero value otherwise.

### GetActivityIdOk

`func (o *ActivityManagerApiUpdateActivity400Response) GetActivityIdOk() (*string, bool)`

GetActivityIdOk returns a tuple with the ActivityId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivityId

`func (o *ActivityManagerApiUpdateActivity400Response) SetActivityId(v string)`

SetActivityId sets ActivityId field to given value.

### HasActivityId

`func (o *ActivityManagerApiUpdateActivity400Response) HasActivityId() bool`

HasActivityId returns a boolean if a field has been set.

### GetActivityName

`func (o *ActivityManagerApiUpdateActivity400Response) GetActivityName() string`

GetActivityName returns the ActivityName field if non-nil, zero value otherwise.

### GetActivityNameOk

`func (o *ActivityManagerApiUpdateActivity400Response) GetActivityNameOk() (*string, bool)`

GetActivityNameOk returns a tuple with the ActivityName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivityName

`func (o *ActivityManagerApiUpdateActivity400Response) SetActivityName(v string)`

SetActivityName sets ActivityName field to given value.

### HasActivityName

`func (o *ActivityManagerApiUpdateActivity400Response) HasActivityName() bool`

HasActivityName returns a boolean if a field has been set.

### GetDescription

`func (o *ActivityManagerApiUpdateActivity400Response) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ActivityManagerApiUpdateActivity400Response) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ActivityManagerApiUpdateActivity400Response) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ActivityManagerApiUpdateActivity400Response) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetActivityType

`func (o *ActivityManagerApiUpdateActivity400Response) GetActivityType() string`

GetActivityType returns the ActivityType field if non-nil, zero value otherwise.

### GetActivityTypeOk

`func (o *ActivityManagerApiUpdateActivity400Response) GetActivityTypeOk() (*string, bool)`

GetActivityTypeOk returns a tuple with the ActivityType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivityType

`func (o *ActivityManagerApiUpdateActivity400Response) SetActivityType(v string)`

SetActivityType sets ActivityType field to given value.

### HasActivityType

`func (o *ActivityManagerApiUpdateActivity400Response) HasActivityType() bool`

HasActivityType returns a boolean if a field has been set.

### GetActivityStatus

`func (o *ActivityManagerApiUpdateActivity400Response) GetActivityStatus() string`

GetActivityStatus returns the ActivityStatus field if non-nil, zero value otherwise.

### GetActivityStatusOk

`func (o *ActivityManagerApiUpdateActivity400Response) GetActivityStatusOk() (*string, bool)`

GetActivityStatusOk returns a tuple with the ActivityStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivityStatus

`func (o *ActivityManagerApiUpdateActivity400Response) SetActivityStatus(v string)`

SetActivityStatus sets ActivityStatus field to given value.

### HasActivityStatus

`func (o *ActivityManagerApiUpdateActivity400Response) HasActivityStatus() bool`

HasActivityStatus returns a boolean if a field has been set.

### GetStatusNote

`func (o *ActivityManagerApiUpdateActivity400Response) GetStatusNote() string`

GetStatusNote returns the StatusNote field if non-nil, zero value otherwise.

### GetStatusNoteOk

`func (o *ActivityManagerApiUpdateActivity400Response) GetStatusNoteOk() (*string, bool)`

GetStatusNoteOk returns a tuple with the StatusNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatusNote

`func (o *ActivityManagerApiUpdateActivity400Response) SetStatusNote(v string)`

SetStatusNote sets StatusNote field to given value.

### HasStatusNote

`func (o *ActivityManagerApiUpdateActivity400Response) HasStatusNote() bool`

HasStatusNote returns a boolean if a field has been set.

### GetCost

`func (o *ActivityManagerApiUpdateActivity400Response) GetCost() float64`

GetCost returns the Cost field if non-nil, zero value otherwise.

### GetCostOk

`func (o *ActivityManagerApiUpdateActivity400Response) GetCostOk() (*float64, bool)`

GetCostOk returns a tuple with the Cost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCost

`func (o *ActivityManagerApiUpdateActivity400Response) SetCost(v float64)`

SetCost sets Cost field to given value.

### HasCost

`func (o *ActivityManagerApiUpdateActivity400Response) HasCost() bool`

HasCost returns a boolean if a field has been set.

### GetPriority

`func (o *ActivityManagerApiUpdateActivity400Response) GetPriority() int32`

GetPriority returns the Priority field if non-nil, zero value otherwise.

### GetPriorityOk

`func (o *ActivityManagerApiUpdateActivity400Response) GetPriorityOk() (*int32, bool)`

GetPriorityOk returns a tuple with the Priority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriority

`func (o *ActivityManagerApiUpdateActivity400Response) SetPriority(v int32)`

SetPriority sets Priority field to given value.

### HasPriority

`func (o *ActivityManagerApiUpdateActivity400Response) HasPriority() bool`

HasPriority returns a boolean if a field has been set.

### GetDueDateTime

`func (o *ActivityManagerApiUpdateActivity400Response) GetDueDateTime() time.Time`

GetDueDateTime returns the DueDateTime field if non-nil, zero value otherwise.

### GetDueDateTimeOk

`func (o *ActivityManagerApiUpdateActivity400Response) GetDueDateTimeOk() (*time.Time, bool)`

GetDueDateTimeOk returns a tuple with the DueDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueDateTime

`func (o *ActivityManagerApiUpdateActivity400Response) SetDueDateTime(v time.Time)`

SetDueDateTime sets DueDateTime field to given value.

### HasDueDateTime

`func (o *ActivityManagerApiUpdateActivity400Response) HasDueDateTime() bool`

HasDueDateTime returns a boolean if a field has been set.

### GetCustomerCode

`func (o *ActivityManagerApiUpdateActivity400Response) GetCustomerCode() string`

GetCustomerCode returns the CustomerCode field if non-nil, zero value otherwise.

### GetCustomerCodeOk

`func (o *ActivityManagerApiUpdateActivity400Response) GetCustomerCodeOk() (*string, bool)`

GetCustomerCodeOk returns a tuple with the CustomerCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerCode

`func (o *ActivityManagerApiUpdateActivity400Response) SetCustomerCode(v string)`

SetCustomerCode sets CustomerCode field to given value.

### HasCustomerCode

`func (o *ActivityManagerApiUpdateActivity400Response) HasCustomerCode() bool`

HasCustomerCode returns a boolean if a field has been set.

### GetSupplierCode

`func (o *ActivityManagerApiUpdateActivity400Response) GetSupplierCode() string`

GetSupplierCode returns the SupplierCode field if non-nil, zero value otherwise.

### GetSupplierCodeOk

`func (o *ActivityManagerApiUpdateActivity400Response) GetSupplierCodeOk() (*string, bool)`

GetSupplierCodeOk returns a tuple with the SupplierCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierCode

`func (o *ActivityManagerApiUpdateActivity400Response) SetSupplierCode(v string)`

SetSupplierCode sets SupplierCode field to given value.

### HasSupplierCode

`func (o *ActivityManagerApiUpdateActivity400Response) HasSupplierCode() bool`

HasSupplierCode returns a boolean if a field has been set.

### GetLocation

`func (o *ActivityManagerApiUpdateActivity400Response) GetLocation() string`

GetLocation returns the Location field if non-nil, zero value otherwise.

### GetLocationOk

`func (o *ActivityManagerApiUpdateActivity400Response) GetLocationOk() (*string, bool)`

GetLocationOk returns a tuple with the Location field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocation

`func (o *ActivityManagerApiUpdateActivity400Response) SetLocation(v string)`

SetLocation sets Location field to given value.

### HasLocation

`func (o *ActivityManagerApiUpdateActivity400Response) HasLocation() bool`

HasLocation returns a boolean if a field has been set.

### GetPrivate

`func (o *ActivityManagerApiUpdateActivity400Response) GetPrivate() bool`

GetPrivate returns the Private field if non-nil, zero value otherwise.

### GetPrivateOk

`func (o *ActivityManagerApiUpdateActivity400Response) GetPrivateOk() (*bool, bool)`

GetPrivateOk returns a tuple with the Private field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrivate

`func (o *ActivityManagerApiUpdateActivity400Response) SetPrivate(v bool)`

SetPrivate sets Private field to given value.

### HasPrivate

`func (o *ActivityManagerApiUpdateActivity400Response) HasPrivate() bool`

HasPrivate returns a boolean if a field has been set.

### GetAssignedTo

`func (o *ActivityManagerApiUpdateActivity400Response) GetAssignedTo() string`

GetAssignedTo returns the AssignedTo field if non-nil, zero value otherwise.

### GetAssignedToOk

`func (o *ActivityManagerApiUpdateActivity400Response) GetAssignedToOk() (*string, bool)`

GetAssignedToOk returns a tuple with the AssignedTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignedTo

`func (o *ActivityManagerApiUpdateActivity400Response) SetAssignedTo(v string)`

SetAssignedTo sets AssignedTo field to given value.

### HasAssignedTo

`func (o *ActivityManagerApiUpdateActivity400Response) HasAssignedTo() bool`

HasAssignedTo returns a boolean if a field has been set.

### GetAssignedBy

`func (o *ActivityManagerApiUpdateActivity400Response) GetAssignedBy() string`

GetAssignedBy returns the AssignedBy field if non-nil, zero value otherwise.

### GetAssignedByOk

`func (o *ActivityManagerApiUpdateActivity400Response) GetAssignedByOk() (*string, bool)`

GetAssignedByOk returns a tuple with the AssignedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignedBy

`func (o *ActivityManagerApiUpdateActivity400Response) SetAssignedBy(v string)`

SetAssignedBy sets AssignedBy field to given value.

### HasAssignedBy

`func (o *ActivityManagerApiUpdateActivity400Response) HasAssignedBy() bool`

HasAssignedBy returns a boolean if a field has been set.

### GetAssignedToDepartment

`func (o *ActivityManagerApiUpdateActivity400Response) GetAssignedToDepartment() string`

GetAssignedToDepartment returns the AssignedToDepartment field if non-nil, zero value otherwise.

### GetAssignedToDepartmentOk

`func (o *ActivityManagerApiUpdateActivity400Response) GetAssignedToDepartmentOk() (*string, bool)`

GetAssignedToDepartmentOk returns a tuple with the AssignedToDepartment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignedToDepartment

`func (o *ActivityManagerApiUpdateActivity400Response) SetAssignedToDepartment(v string)`

SetAssignedToDepartment sets AssignedToDepartment field to given value.

### HasAssignedToDepartment

`func (o *ActivityManagerApiUpdateActivity400Response) HasAssignedToDepartment() bool`

HasAssignedToDepartment returns a boolean if a field has been set.

### GetInvolvedUsers

`func (o *ActivityManagerApiUpdateActivity400Response) GetInvolvedUsers() []string`

GetInvolvedUsers returns the InvolvedUsers field if non-nil, zero value otherwise.

### GetInvolvedUsersOk

`func (o *ActivityManagerApiUpdateActivity400Response) GetInvolvedUsersOk() (*[]string, bool)`

GetInvolvedUsersOk returns a tuple with the InvolvedUsers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvolvedUsers

`func (o *ActivityManagerApiUpdateActivity400Response) SetInvolvedUsers(v []string)`

SetInvolvedUsers sets InvolvedUsers field to given value.

### HasInvolvedUsers

`func (o *ActivityManagerApiUpdateActivity400Response) HasInvolvedUsers() bool`

HasInvolvedUsers returns a boolean if a field has been set.

### GetParentActivity

`func (o *ActivityManagerApiUpdateActivity400Response) GetParentActivity() string`

GetParentActivity returns the ParentActivity field if non-nil, zero value otherwise.

### GetParentActivityOk

`func (o *ActivityManagerApiUpdateActivity400Response) GetParentActivityOk() (*string, bool)`

GetParentActivityOk returns a tuple with the ParentActivity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentActivity

`func (o *ActivityManagerApiUpdateActivity400Response) SetParentActivity(v string)`

SetParentActivity sets ParentActivity field to given value.

### HasParentActivity

`func (o *ActivityManagerApiUpdateActivity400Response) HasParentActivity() bool`

HasParentActivity returns a boolean if a field has been set.

### GetPlannedStartDateTime

`func (o *ActivityManagerApiUpdateActivity400Response) GetPlannedStartDateTime() time.Time`

GetPlannedStartDateTime returns the PlannedStartDateTime field if non-nil, zero value otherwise.

### GetPlannedStartDateTimeOk

`func (o *ActivityManagerApiUpdateActivity400Response) GetPlannedStartDateTimeOk() (*time.Time, bool)`

GetPlannedStartDateTimeOk returns a tuple with the PlannedStartDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlannedStartDateTime

`func (o *ActivityManagerApiUpdateActivity400Response) SetPlannedStartDateTime(v time.Time)`

SetPlannedStartDateTime sets PlannedStartDateTime field to given value.

### HasPlannedStartDateTime

`func (o *ActivityManagerApiUpdateActivity400Response) HasPlannedStartDateTime() bool`

HasPlannedStartDateTime returns a boolean if a field has been set.

### GetPlannedFinishDateTime

`func (o *ActivityManagerApiUpdateActivity400Response) GetPlannedFinishDateTime() time.Time`

GetPlannedFinishDateTime returns the PlannedFinishDateTime field if non-nil, zero value otherwise.

### GetPlannedFinishDateTimeOk

`func (o *ActivityManagerApiUpdateActivity400Response) GetPlannedFinishDateTimeOk() (*time.Time, bool)`

GetPlannedFinishDateTimeOk returns a tuple with the PlannedFinishDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlannedFinishDateTime

`func (o *ActivityManagerApiUpdateActivity400Response) SetPlannedFinishDateTime(v time.Time)`

SetPlannedFinishDateTime sets PlannedFinishDateTime field to given value.

### HasPlannedFinishDateTime

`func (o *ActivityManagerApiUpdateActivity400Response) HasPlannedFinishDateTime() bool`

HasPlannedFinishDateTime returns a boolean if a field has been set.

### GetPercentageCompletion

`func (o *ActivityManagerApiUpdateActivity400Response) GetPercentageCompletion() int32`

GetPercentageCompletion returns the PercentageCompletion field if non-nil, zero value otherwise.

### GetPercentageCompletionOk

`func (o *ActivityManagerApiUpdateActivity400Response) GetPercentageCompletionOk() (*int32, bool)`

GetPercentageCompletionOk returns a tuple with the PercentageCompletion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPercentageCompletion

`func (o *ActivityManagerApiUpdateActivity400Response) SetPercentageCompletion(v int32)`

SetPercentageCompletion sets PercentageCompletion field to given value.

### HasPercentageCompletion

`func (o *ActivityManagerApiUpdateActivity400Response) HasPercentageCompletion() bool`

HasPercentageCompletion returns a boolean if a field has been set.

### GetSuggestionNos

`func (o *ActivityManagerApiUpdateActivity400Response) GetSuggestionNos() []int32`

GetSuggestionNos returns the SuggestionNos field if non-nil, zero value otherwise.

### GetSuggestionNosOk

`func (o *ActivityManagerApiUpdateActivity400Response) GetSuggestionNosOk() (*[]int32, bool)`

GetSuggestionNosOk returns a tuple with the SuggestionNos field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuggestionNos

`func (o *ActivityManagerApiUpdateActivity400Response) SetSuggestionNos(v []int32)`

SetSuggestionNos sets SuggestionNos field to given value.

### HasSuggestionNos

`func (o *ActivityManagerApiUpdateActivity400Response) HasSuggestionNos() bool`

HasSuggestionNos returns a boolean if a field has been set.

### GetComments

`func (o *ActivityManagerApiUpdateActivity400Response) GetComments() []string`

GetComments returns the Comments field if non-nil, zero value otherwise.

### GetCommentsOk

`func (o *ActivityManagerApiUpdateActivity400Response) GetCommentsOk() (*[]string, bool)`

GetCommentsOk returns a tuple with the Comments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComments

`func (o *ActivityManagerApiUpdateActivity400Response) SetComments(v []string)`

SetComments sets Comments field to given value.

### HasComments

`func (o *ActivityManagerApiUpdateActivity400Response) HasComments() bool`

HasComments returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


