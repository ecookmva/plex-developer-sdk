# ActivityManagerApiListActivitiesItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ActivityId** | Pointer to **string** | The ID of the activity. | [optional] 
**TenantId** | Pointer to **string** | The Tenant ID. | [optional] 
**ActivityName** | Pointer to **string** | The name of the activity. | [optional] 
**Description** | Pointer to **string** | The description of the activity. | [optional] 
**ActivityType** | Pointer to **string** | The activity type. | [optional] 
**ActivityStatus** | Pointer to **string** | The status information of the activity. | [optional] 
**StatusNote** | Pointer to **string** | A note on the status of activity. | [optional] 
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
**ParentActivity** | Pointer to **string** | The parent ID of the activity. | [optional] 
**ImprovementProject** | Pointer to **string** | The improvement project number of the activity. | [optional] 
**ExpenseProject** | Pointer to **string** | The expense project key of the activity. | [optional] 
**StrategicObjective** | Pointer to **string** | The objective of the activity. | [optional] 
**Opportunity** | Pointer to **string** | The opportunity associated with the activity. | [optional] 
**PlannedStartDateTime** | Pointer to **time.Time** | The planned start date of the activity. | [optional] 
**PlannedFinishDateTime** | Pointer to **time.Time** | The planned finish date of the activity. | [optional] 
**ActualStartDateTime** | Pointer to **time.Time** | The actual start date of the activity. | [optional] 
**ActualFinishDateTime** | Pointer to **time.Time** | The actual finish date of the activity. | [optional] 
**PercentageCompletion** | Pointer to **float64** | The completion percentage of the activity. | [optional] 
**CreatedDateTime** | Pointer to **time.Time** | The date the activity was created. | [optional] 

## Methods

### NewActivityManagerApiListActivitiesItem

`func NewActivityManagerApiListActivitiesItem() *ActivityManagerApiListActivitiesItem`

NewActivityManagerApiListActivitiesItem instantiates a new ActivityManagerApiListActivitiesItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewActivityManagerApiListActivitiesItemWithDefaults

`func NewActivityManagerApiListActivitiesItemWithDefaults() *ActivityManagerApiListActivitiesItem`

NewActivityManagerApiListActivitiesItemWithDefaults instantiates a new ActivityManagerApiListActivitiesItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActivityId

`func (o *ActivityManagerApiListActivitiesItem) GetActivityId() string`

GetActivityId returns the ActivityId field if non-nil, zero value otherwise.

### GetActivityIdOk

`func (o *ActivityManagerApiListActivitiesItem) GetActivityIdOk() (*string, bool)`

GetActivityIdOk returns a tuple with the ActivityId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivityId

`func (o *ActivityManagerApiListActivitiesItem) SetActivityId(v string)`

SetActivityId sets ActivityId field to given value.

### HasActivityId

`func (o *ActivityManagerApiListActivitiesItem) HasActivityId() bool`

HasActivityId returns a boolean if a field has been set.

### GetTenantId

`func (o *ActivityManagerApiListActivitiesItem) GetTenantId() string`

GetTenantId returns the TenantId field if non-nil, zero value otherwise.

### GetTenantIdOk

`func (o *ActivityManagerApiListActivitiesItem) GetTenantIdOk() (*string, bool)`

GetTenantIdOk returns a tuple with the TenantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantId

`func (o *ActivityManagerApiListActivitiesItem) SetTenantId(v string)`

SetTenantId sets TenantId field to given value.

### HasTenantId

`func (o *ActivityManagerApiListActivitiesItem) HasTenantId() bool`

HasTenantId returns a boolean if a field has been set.

### GetActivityName

`func (o *ActivityManagerApiListActivitiesItem) GetActivityName() string`

GetActivityName returns the ActivityName field if non-nil, zero value otherwise.

### GetActivityNameOk

`func (o *ActivityManagerApiListActivitiesItem) GetActivityNameOk() (*string, bool)`

GetActivityNameOk returns a tuple with the ActivityName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivityName

`func (o *ActivityManagerApiListActivitiesItem) SetActivityName(v string)`

SetActivityName sets ActivityName field to given value.

### HasActivityName

`func (o *ActivityManagerApiListActivitiesItem) HasActivityName() bool`

HasActivityName returns a boolean if a field has been set.

### GetDescription

`func (o *ActivityManagerApiListActivitiesItem) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ActivityManagerApiListActivitiesItem) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ActivityManagerApiListActivitiesItem) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ActivityManagerApiListActivitiesItem) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetActivityType

`func (o *ActivityManagerApiListActivitiesItem) GetActivityType() string`

GetActivityType returns the ActivityType field if non-nil, zero value otherwise.

### GetActivityTypeOk

`func (o *ActivityManagerApiListActivitiesItem) GetActivityTypeOk() (*string, bool)`

GetActivityTypeOk returns a tuple with the ActivityType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivityType

`func (o *ActivityManagerApiListActivitiesItem) SetActivityType(v string)`

SetActivityType sets ActivityType field to given value.

### HasActivityType

`func (o *ActivityManagerApiListActivitiesItem) HasActivityType() bool`

HasActivityType returns a boolean if a field has been set.

### GetActivityStatus

`func (o *ActivityManagerApiListActivitiesItem) GetActivityStatus() string`

GetActivityStatus returns the ActivityStatus field if non-nil, zero value otherwise.

### GetActivityStatusOk

`func (o *ActivityManagerApiListActivitiesItem) GetActivityStatusOk() (*string, bool)`

GetActivityStatusOk returns a tuple with the ActivityStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivityStatus

`func (o *ActivityManagerApiListActivitiesItem) SetActivityStatus(v string)`

SetActivityStatus sets ActivityStatus field to given value.

### HasActivityStatus

`func (o *ActivityManagerApiListActivitiesItem) HasActivityStatus() bool`

HasActivityStatus returns a boolean if a field has been set.

### GetStatusNote

`func (o *ActivityManagerApiListActivitiesItem) GetStatusNote() string`

GetStatusNote returns the StatusNote field if non-nil, zero value otherwise.

### GetStatusNoteOk

`func (o *ActivityManagerApiListActivitiesItem) GetStatusNoteOk() (*string, bool)`

GetStatusNoteOk returns a tuple with the StatusNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatusNote

`func (o *ActivityManagerApiListActivitiesItem) SetStatusNote(v string)`

SetStatusNote sets StatusNote field to given value.

### HasStatusNote

`func (o *ActivityManagerApiListActivitiesItem) HasStatusNote() bool`

HasStatusNote returns a boolean if a field has been set.

### GetPriority

`func (o *ActivityManagerApiListActivitiesItem) GetPriority() int32`

GetPriority returns the Priority field if non-nil, zero value otherwise.

### GetPriorityOk

`func (o *ActivityManagerApiListActivitiesItem) GetPriorityOk() (*int32, bool)`

GetPriorityOk returns a tuple with the Priority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriority

`func (o *ActivityManagerApiListActivitiesItem) SetPriority(v int32)`

SetPriority sets Priority field to given value.

### HasPriority

`func (o *ActivityManagerApiListActivitiesItem) HasPriority() bool`

HasPriority returns a boolean if a field has been set.

### GetDueDateTime

`func (o *ActivityManagerApiListActivitiesItem) GetDueDateTime() time.Time`

GetDueDateTime returns the DueDateTime field if non-nil, zero value otherwise.

### GetDueDateTimeOk

`func (o *ActivityManagerApiListActivitiesItem) GetDueDateTimeOk() (*time.Time, bool)`

GetDueDateTimeOk returns a tuple with the DueDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueDateTime

`func (o *ActivityManagerApiListActivitiesItem) SetDueDateTime(v time.Time)`

SetDueDateTime sets DueDateTime field to given value.

### HasDueDateTime

`func (o *ActivityManagerApiListActivitiesItem) HasDueDateTime() bool`

HasDueDateTime returns a boolean if a field has been set.

### GetAssignedTo

`func (o *ActivityManagerApiListActivitiesItem) GetAssignedTo() string`

GetAssignedTo returns the AssignedTo field if non-nil, zero value otherwise.

### GetAssignedToOk

`func (o *ActivityManagerApiListActivitiesItem) GetAssignedToOk() (*string, bool)`

GetAssignedToOk returns a tuple with the AssignedTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignedTo

`func (o *ActivityManagerApiListActivitiesItem) SetAssignedTo(v string)`

SetAssignedTo sets AssignedTo field to given value.

### HasAssignedTo

`func (o *ActivityManagerApiListActivitiesItem) HasAssignedTo() bool`

HasAssignedTo returns a boolean if a field has been set.

### GetAssignedBy

`func (o *ActivityManagerApiListActivitiesItem) GetAssignedBy() string`

GetAssignedBy returns the AssignedBy field if non-nil, zero value otherwise.

### GetAssignedByOk

`func (o *ActivityManagerApiListActivitiesItem) GetAssignedByOk() (*string, bool)`

GetAssignedByOk returns a tuple with the AssignedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignedBy

`func (o *ActivityManagerApiListActivitiesItem) SetAssignedBy(v string)`

SetAssignedBy sets AssignedBy field to given value.

### HasAssignedBy

`func (o *ActivityManagerApiListActivitiesItem) HasAssignedBy() bool`

HasAssignedBy returns a boolean if a field has been set.

### GetCost

`func (o *ActivityManagerApiListActivitiesItem) GetCost() float64`

GetCost returns the Cost field if non-nil, zero value otherwise.

### GetCostOk

`func (o *ActivityManagerApiListActivitiesItem) GetCostOk() (*float64, bool)`

GetCostOk returns a tuple with the Cost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCost

`func (o *ActivityManagerApiListActivitiesItem) SetCost(v float64)`

SetCost sets Cost field to given value.

### HasCost

`func (o *ActivityManagerApiListActivitiesItem) HasCost() bool`

HasCost returns a boolean if a field has been set.

### GetCustomerCode

`func (o *ActivityManagerApiListActivitiesItem) GetCustomerCode() string`

GetCustomerCode returns the CustomerCode field if non-nil, zero value otherwise.

### GetCustomerCodeOk

`func (o *ActivityManagerApiListActivitiesItem) GetCustomerCodeOk() (*string, bool)`

GetCustomerCodeOk returns a tuple with the CustomerCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerCode

`func (o *ActivityManagerApiListActivitiesItem) SetCustomerCode(v string)`

SetCustomerCode sets CustomerCode field to given value.

### HasCustomerCode

`func (o *ActivityManagerApiListActivitiesItem) HasCustomerCode() bool`

HasCustomerCode returns a boolean if a field has been set.

### GetSupplierCode

`func (o *ActivityManagerApiListActivitiesItem) GetSupplierCode() string`

GetSupplierCode returns the SupplierCode field if non-nil, zero value otherwise.

### GetSupplierCodeOk

`func (o *ActivityManagerApiListActivitiesItem) GetSupplierCodeOk() (*string, bool)`

GetSupplierCodeOk returns a tuple with the SupplierCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierCode

`func (o *ActivityManagerApiListActivitiesItem) SetSupplierCode(v string)`

SetSupplierCode sets SupplierCode field to given value.

### HasSupplierCode

`func (o *ActivityManagerApiListActivitiesItem) HasSupplierCode() bool`

HasSupplierCode returns a boolean if a field has been set.

### GetLocation

`func (o *ActivityManagerApiListActivitiesItem) GetLocation() string`

GetLocation returns the Location field if non-nil, zero value otherwise.

### GetLocationOk

`func (o *ActivityManagerApiListActivitiesItem) GetLocationOk() (*string, bool)`

GetLocationOk returns a tuple with the Location field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocation

`func (o *ActivityManagerApiListActivitiesItem) SetLocation(v string)`

SetLocation sets Location field to given value.

### HasLocation

`func (o *ActivityManagerApiListActivitiesItem) HasLocation() bool`

HasLocation returns a boolean if a field has been set.

### GetPrivate

`func (o *ActivityManagerApiListActivitiesItem) GetPrivate() bool`

GetPrivate returns the Private field if non-nil, zero value otherwise.

### GetPrivateOk

`func (o *ActivityManagerApiListActivitiesItem) GetPrivateOk() (*bool, bool)`

GetPrivateOk returns a tuple with the Private field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrivate

`func (o *ActivityManagerApiListActivitiesItem) SetPrivate(v bool)`

SetPrivate sets Private field to given value.

### HasPrivate

`func (o *ActivityManagerApiListActivitiesItem) HasPrivate() bool`

HasPrivate returns a boolean if a field has been set.

### GetAssignedToDepartment

`func (o *ActivityManagerApiListActivitiesItem) GetAssignedToDepartment() string`

GetAssignedToDepartment returns the AssignedToDepartment field if non-nil, zero value otherwise.

### GetAssignedToDepartmentOk

`func (o *ActivityManagerApiListActivitiesItem) GetAssignedToDepartmentOk() (*string, bool)`

GetAssignedToDepartmentOk returns a tuple with the AssignedToDepartment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignedToDepartment

`func (o *ActivityManagerApiListActivitiesItem) SetAssignedToDepartment(v string)`

SetAssignedToDepartment sets AssignedToDepartment field to given value.

### HasAssignedToDepartment

`func (o *ActivityManagerApiListActivitiesItem) HasAssignedToDepartment() bool`

HasAssignedToDepartment returns a boolean if a field has been set.

### GetParentActivity

`func (o *ActivityManagerApiListActivitiesItem) GetParentActivity() string`

GetParentActivity returns the ParentActivity field if non-nil, zero value otherwise.

### GetParentActivityOk

`func (o *ActivityManagerApiListActivitiesItem) GetParentActivityOk() (*string, bool)`

GetParentActivityOk returns a tuple with the ParentActivity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentActivity

`func (o *ActivityManagerApiListActivitiesItem) SetParentActivity(v string)`

SetParentActivity sets ParentActivity field to given value.

### HasParentActivity

`func (o *ActivityManagerApiListActivitiesItem) HasParentActivity() bool`

HasParentActivity returns a boolean if a field has been set.

### GetImprovementProject

`func (o *ActivityManagerApiListActivitiesItem) GetImprovementProject() string`

GetImprovementProject returns the ImprovementProject field if non-nil, zero value otherwise.

### GetImprovementProjectOk

`func (o *ActivityManagerApiListActivitiesItem) GetImprovementProjectOk() (*string, bool)`

GetImprovementProjectOk returns a tuple with the ImprovementProject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImprovementProject

`func (o *ActivityManagerApiListActivitiesItem) SetImprovementProject(v string)`

SetImprovementProject sets ImprovementProject field to given value.

### HasImprovementProject

`func (o *ActivityManagerApiListActivitiesItem) HasImprovementProject() bool`

HasImprovementProject returns a boolean if a field has been set.

### GetExpenseProject

`func (o *ActivityManagerApiListActivitiesItem) GetExpenseProject() string`

GetExpenseProject returns the ExpenseProject field if non-nil, zero value otherwise.

### GetExpenseProjectOk

`func (o *ActivityManagerApiListActivitiesItem) GetExpenseProjectOk() (*string, bool)`

GetExpenseProjectOk returns a tuple with the ExpenseProject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpenseProject

`func (o *ActivityManagerApiListActivitiesItem) SetExpenseProject(v string)`

SetExpenseProject sets ExpenseProject field to given value.

### HasExpenseProject

`func (o *ActivityManagerApiListActivitiesItem) HasExpenseProject() bool`

HasExpenseProject returns a boolean if a field has been set.

### GetStrategicObjective

`func (o *ActivityManagerApiListActivitiesItem) GetStrategicObjective() string`

GetStrategicObjective returns the StrategicObjective field if non-nil, zero value otherwise.

### GetStrategicObjectiveOk

`func (o *ActivityManagerApiListActivitiesItem) GetStrategicObjectiveOk() (*string, bool)`

GetStrategicObjectiveOk returns a tuple with the StrategicObjective field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStrategicObjective

`func (o *ActivityManagerApiListActivitiesItem) SetStrategicObjective(v string)`

SetStrategicObjective sets StrategicObjective field to given value.

### HasStrategicObjective

`func (o *ActivityManagerApiListActivitiesItem) HasStrategicObjective() bool`

HasStrategicObjective returns a boolean if a field has been set.

### GetOpportunity

`func (o *ActivityManagerApiListActivitiesItem) GetOpportunity() string`

GetOpportunity returns the Opportunity field if non-nil, zero value otherwise.

### GetOpportunityOk

`func (o *ActivityManagerApiListActivitiesItem) GetOpportunityOk() (*string, bool)`

GetOpportunityOk returns a tuple with the Opportunity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpportunity

`func (o *ActivityManagerApiListActivitiesItem) SetOpportunity(v string)`

SetOpportunity sets Opportunity field to given value.

### HasOpportunity

`func (o *ActivityManagerApiListActivitiesItem) HasOpportunity() bool`

HasOpportunity returns a boolean if a field has been set.

### GetPlannedStartDateTime

`func (o *ActivityManagerApiListActivitiesItem) GetPlannedStartDateTime() time.Time`

GetPlannedStartDateTime returns the PlannedStartDateTime field if non-nil, zero value otherwise.

### GetPlannedStartDateTimeOk

`func (o *ActivityManagerApiListActivitiesItem) GetPlannedStartDateTimeOk() (*time.Time, bool)`

GetPlannedStartDateTimeOk returns a tuple with the PlannedStartDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlannedStartDateTime

`func (o *ActivityManagerApiListActivitiesItem) SetPlannedStartDateTime(v time.Time)`

SetPlannedStartDateTime sets PlannedStartDateTime field to given value.

### HasPlannedStartDateTime

`func (o *ActivityManagerApiListActivitiesItem) HasPlannedStartDateTime() bool`

HasPlannedStartDateTime returns a boolean if a field has been set.

### GetPlannedFinishDateTime

`func (o *ActivityManagerApiListActivitiesItem) GetPlannedFinishDateTime() time.Time`

GetPlannedFinishDateTime returns the PlannedFinishDateTime field if non-nil, zero value otherwise.

### GetPlannedFinishDateTimeOk

`func (o *ActivityManagerApiListActivitiesItem) GetPlannedFinishDateTimeOk() (*time.Time, bool)`

GetPlannedFinishDateTimeOk returns a tuple with the PlannedFinishDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlannedFinishDateTime

`func (o *ActivityManagerApiListActivitiesItem) SetPlannedFinishDateTime(v time.Time)`

SetPlannedFinishDateTime sets PlannedFinishDateTime field to given value.

### HasPlannedFinishDateTime

`func (o *ActivityManagerApiListActivitiesItem) HasPlannedFinishDateTime() bool`

HasPlannedFinishDateTime returns a boolean if a field has been set.

### GetActualStartDateTime

`func (o *ActivityManagerApiListActivitiesItem) GetActualStartDateTime() time.Time`

GetActualStartDateTime returns the ActualStartDateTime field if non-nil, zero value otherwise.

### GetActualStartDateTimeOk

`func (o *ActivityManagerApiListActivitiesItem) GetActualStartDateTimeOk() (*time.Time, bool)`

GetActualStartDateTimeOk returns a tuple with the ActualStartDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActualStartDateTime

`func (o *ActivityManagerApiListActivitiesItem) SetActualStartDateTime(v time.Time)`

SetActualStartDateTime sets ActualStartDateTime field to given value.

### HasActualStartDateTime

`func (o *ActivityManagerApiListActivitiesItem) HasActualStartDateTime() bool`

HasActualStartDateTime returns a boolean if a field has been set.

### GetActualFinishDateTime

`func (o *ActivityManagerApiListActivitiesItem) GetActualFinishDateTime() time.Time`

GetActualFinishDateTime returns the ActualFinishDateTime field if non-nil, zero value otherwise.

### GetActualFinishDateTimeOk

`func (o *ActivityManagerApiListActivitiesItem) GetActualFinishDateTimeOk() (*time.Time, bool)`

GetActualFinishDateTimeOk returns a tuple with the ActualFinishDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActualFinishDateTime

`func (o *ActivityManagerApiListActivitiesItem) SetActualFinishDateTime(v time.Time)`

SetActualFinishDateTime sets ActualFinishDateTime field to given value.

### HasActualFinishDateTime

`func (o *ActivityManagerApiListActivitiesItem) HasActualFinishDateTime() bool`

HasActualFinishDateTime returns a boolean if a field has been set.

### GetPercentageCompletion

`func (o *ActivityManagerApiListActivitiesItem) GetPercentageCompletion() float64`

GetPercentageCompletion returns the PercentageCompletion field if non-nil, zero value otherwise.

### GetPercentageCompletionOk

`func (o *ActivityManagerApiListActivitiesItem) GetPercentageCompletionOk() (*float64, bool)`

GetPercentageCompletionOk returns a tuple with the PercentageCompletion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPercentageCompletion

`func (o *ActivityManagerApiListActivitiesItem) SetPercentageCompletion(v float64)`

SetPercentageCompletion sets PercentageCompletion field to given value.

### HasPercentageCompletion

`func (o *ActivityManagerApiListActivitiesItem) HasPercentageCompletion() bool`

HasPercentageCompletion returns a boolean if a field has been set.

### GetCreatedDateTime

`func (o *ActivityManagerApiListActivitiesItem) GetCreatedDateTime() time.Time`

GetCreatedDateTime returns the CreatedDateTime field if non-nil, zero value otherwise.

### GetCreatedDateTimeOk

`func (o *ActivityManagerApiListActivitiesItem) GetCreatedDateTimeOk() (*time.Time, bool)`

GetCreatedDateTimeOk returns a tuple with the CreatedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDateTime

`func (o *ActivityManagerApiListActivitiesItem) SetCreatedDateTime(v time.Time)`

SetCreatedDateTime sets CreatedDateTime field to given value.

### HasCreatedDateTime

`func (o *ActivityManagerApiListActivitiesItem) HasCreatedDateTime() bool`

HasCreatedDateTime returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


