# EmployeesApiCreateEmployeeRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | A unique identifier for the Employee. This will be automatically generated if omitted from the request. | [optional] 
**BadgeNumber** | Pointer to **string** | Employee badge number as used in Plex. | [optional] 
**UserId** | Pointer to **string** | The User ID as seen on Plex login screens. | [optional] 
**FirstName** | Pointer to **string** |  | [optional] 
**MiddleName** | Pointer to **string** |  | [optional] 
**LastName** | Pointer to **string** |  | [optional] 
**SupervisorId** | Pointer to **string** | Refers to another Employee&#39;s ID within the same Enterprise. | [optional] 
**Status** | Pointer to **string** | Setup Table: Employee Status | [optional] 
**Position** | Pointer to **string** | Job title or position. Plex Classic Screen: Positions. Plex UX Screen: Employee Positions. | [optional] 
**Shift** | Pointer to **string** | The Employee&#39;s default shift. Setup Table: Shift | [optional] 
**Building** | Pointer to **string** | The Employee&#39;s default building. Screen: Buildings | [optional] 
**Type** | Pointer to **string** | Typically full-time or part-time. Setup Table: Employee Type | [optional] 
**Department** | Pointer to **string** | Setup Table: Department | [optional] 
**Email** | Pointer to **string** |  | [optional] 
**WorkPhone** | Pointer to **string** |  | [optional] 
**WorkExtension** | Pointer to **string** |  | [optional] 
**HomePhone** | Pointer to **string** |  | [optional] 
**MobilePhone** | Pointer to **string** |  | [optional] 

## Methods

### NewEmployeesApiCreateEmployeeRequest

`func NewEmployeesApiCreateEmployeeRequest() *EmployeesApiCreateEmployeeRequest`

NewEmployeesApiCreateEmployeeRequest instantiates a new EmployeesApiCreateEmployeeRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEmployeesApiCreateEmployeeRequestWithDefaults

`func NewEmployeesApiCreateEmployeeRequestWithDefaults() *EmployeesApiCreateEmployeeRequest`

NewEmployeesApiCreateEmployeeRequestWithDefaults instantiates a new EmployeesApiCreateEmployeeRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *EmployeesApiCreateEmployeeRequest) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *EmployeesApiCreateEmployeeRequest) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *EmployeesApiCreateEmployeeRequest) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *EmployeesApiCreateEmployeeRequest) HasId() bool`

HasId returns a boolean if a field has been set.

### GetBadgeNumber

`func (o *EmployeesApiCreateEmployeeRequest) GetBadgeNumber() string`

GetBadgeNumber returns the BadgeNumber field if non-nil, zero value otherwise.

### GetBadgeNumberOk

`func (o *EmployeesApiCreateEmployeeRequest) GetBadgeNumberOk() (*string, bool)`

GetBadgeNumberOk returns a tuple with the BadgeNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBadgeNumber

`func (o *EmployeesApiCreateEmployeeRequest) SetBadgeNumber(v string)`

SetBadgeNumber sets BadgeNumber field to given value.

### HasBadgeNumber

`func (o *EmployeesApiCreateEmployeeRequest) HasBadgeNumber() bool`

HasBadgeNumber returns a boolean if a field has been set.

### GetUserId

`func (o *EmployeesApiCreateEmployeeRequest) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *EmployeesApiCreateEmployeeRequest) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *EmployeesApiCreateEmployeeRequest) SetUserId(v string)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *EmployeesApiCreateEmployeeRequest) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### GetFirstName

`func (o *EmployeesApiCreateEmployeeRequest) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *EmployeesApiCreateEmployeeRequest) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *EmployeesApiCreateEmployeeRequest) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.

### HasFirstName

`func (o *EmployeesApiCreateEmployeeRequest) HasFirstName() bool`

HasFirstName returns a boolean if a field has been set.

### GetMiddleName

`func (o *EmployeesApiCreateEmployeeRequest) GetMiddleName() string`

GetMiddleName returns the MiddleName field if non-nil, zero value otherwise.

### GetMiddleNameOk

`func (o *EmployeesApiCreateEmployeeRequest) GetMiddleNameOk() (*string, bool)`

GetMiddleNameOk returns a tuple with the MiddleName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMiddleName

`func (o *EmployeesApiCreateEmployeeRequest) SetMiddleName(v string)`

SetMiddleName sets MiddleName field to given value.

### HasMiddleName

`func (o *EmployeesApiCreateEmployeeRequest) HasMiddleName() bool`

HasMiddleName returns a boolean if a field has been set.

### GetLastName

`func (o *EmployeesApiCreateEmployeeRequest) GetLastName() string`

GetLastName returns the LastName field if non-nil, zero value otherwise.

### GetLastNameOk

`func (o *EmployeesApiCreateEmployeeRequest) GetLastNameOk() (*string, bool)`

GetLastNameOk returns a tuple with the LastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastName

`func (o *EmployeesApiCreateEmployeeRequest) SetLastName(v string)`

SetLastName sets LastName field to given value.

### HasLastName

`func (o *EmployeesApiCreateEmployeeRequest) HasLastName() bool`

HasLastName returns a boolean if a field has been set.

### GetSupervisorId

`func (o *EmployeesApiCreateEmployeeRequest) GetSupervisorId() string`

GetSupervisorId returns the SupervisorId field if non-nil, zero value otherwise.

### GetSupervisorIdOk

`func (o *EmployeesApiCreateEmployeeRequest) GetSupervisorIdOk() (*string, bool)`

GetSupervisorIdOk returns a tuple with the SupervisorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupervisorId

`func (o *EmployeesApiCreateEmployeeRequest) SetSupervisorId(v string)`

SetSupervisorId sets SupervisorId field to given value.

### HasSupervisorId

`func (o *EmployeesApiCreateEmployeeRequest) HasSupervisorId() bool`

HasSupervisorId returns a boolean if a field has been set.

### GetStatus

`func (o *EmployeesApiCreateEmployeeRequest) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *EmployeesApiCreateEmployeeRequest) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *EmployeesApiCreateEmployeeRequest) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *EmployeesApiCreateEmployeeRequest) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetPosition

`func (o *EmployeesApiCreateEmployeeRequest) GetPosition() string`

GetPosition returns the Position field if non-nil, zero value otherwise.

### GetPositionOk

`func (o *EmployeesApiCreateEmployeeRequest) GetPositionOk() (*string, bool)`

GetPositionOk returns a tuple with the Position field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosition

`func (o *EmployeesApiCreateEmployeeRequest) SetPosition(v string)`

SetPosition sets Position field to given value.

### HasPosition

`func (o *EmployeesApiCreateEmployeeRequest) HasPosition() bool`

HasPosition returns a boolean if a field has been set.

### GetShift

`func (o *EmployeesApiCreateEmployeeRequest) GetShift() string`

GetShift returns the Shift field if non-nil, zero value otherwise.

### GetShiftOk

`func (o *EmployeesApiCreateEmployeeRequest) GetShiftOk() (*string, bool)`

GetShiftOk returns a tuple with the Shift field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShift

`func (o *EmployeesApiCreateEmployeeRequest) SetShift(v string)`

SetShift sets Shift field to given value.

### HasShift

`func (o *EmployeesApiCreateEmployeeRequest) HasShift() bool`

HasShift returns a boolean if a field has been set.

### GetBuilding

`func (o *EmployeesApiCreateEmployeeRequest) GetBuilding() string`

GetBuilding returns the Building field if non-nil, zero value otherwise.

### GetBuildingOk

`func (o *EmployeesApiCreateEmployeeRequest) GetBuildingOk() (*string, bool)`

GetBuildingOk returns a tuple with the Building field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuilding

`func (o *EmployeesApiCreateEmployeeRequest) SetBuilding(v string)`

SetBuilding sets Building field to given value.

### HasBuilding

`func (o *EmployeesApiCreateEmployeeRequest) HasBuilding() bool`

HasBuilding returns a boolean if a field has been set.

### GetType

`func (o *EmployeesApiCreateEmployeeRequest) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *EmployeesApiCreateEmployeeRequest) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *EmployeesApiCreateEmployeeRequest) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *EmployeesApiCreateEmployeeRequest) HasType() bool`

HasType returns a boolean if a field has been set.

### GetDepartment

`func (o *EmployeesApiCreateEmployeeRequest) GetDepartment() string`

GetDepartment returns the Department field if non-nil, zero value otherwise.

### GetDepartmentOk

`func (o *EmployeesApiCreateEmployeeRequest) GetDepartmentOk() (*string, bool)`

GetDepartmentOk returns a tuple with the Department field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDepartment

`func (o *EmployeesApiCreateEmployeeRequest) SetDepartment(v string)`

SetDepartment sets Department field to given value.

### HasDepartment

`func (o *EmployeesApiCreateEmployeeRequest) HasDepartment() bool`

HasDepartment returns a boolean if a field has been set.

### GetEmail

`func (o *EmployeesApiCreateEmployeeRequest) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *EmployeesApiCreateEmployeeRequest) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *EmployeesApiCreateEmployeeRequest) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *EmployeesApiCreateEmployeeRequest) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetWorkPhone

`func (o *EmployeesApiCreateEmployeeRequest) GetWorkPhone() string`

GetWorkPhone returns the WorkPhone field if non-nil, zero value otherwise.

### GetWorkPhoneOk

`func (o *EmployeesApiCreateEmployeeRequest) GetWorkPhoneOk() (*string, bool)`

GetWorkPhoneOk returns a tuple with the WorkPhone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkPhone

`func (o *EmployeesApiCreateEmployeeRequest) SetWorkPhone(v string)`

SetWorkPhone sets WorkPhone field to given value.

### HasWorkPhone

`func (o *EmployeesApiCreateEmployeeRequest) HasWorkPhone() bool`

HasWorkPhone returns a boolean if a field has been set.

### GetWorkExtension

`func (o *EmployeesApiCreateEmployeeRequest) GetWorkExtension() string`

GetWorkExtension returns the WorkExtension field if non-nil, zero value otherwise.

### GetWorkExtensionOk

`func (o *EmployeesApiCreateEmployeeRequest) GetWorkExtensionOk() (*string, bool)`

GetWorkExtensionOk returns a tuple with the WorkExtension field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkExtension

`func (o *EmployeesApiCreateEmployeeRequest) SetWorkExtension(v string)`

SetWorkExtension sets WorkExtension field to given value.

### HasWorkExtension

`func (o *EmployeesApiCreateEmployeeRequest) HasWorkExtension() bool`

HasWorkExtension returns a boolean if a field has been set.

### GetHomePhone

`func (o *EmployeesApiCreateEmployeeRequest) GetHomePhone() string`

GetHomePhone returns the HomePhone field if non-nil, zero value otherwise.

### GetHomePhoneOk

`func (o *EmployeesApiCreateEmployeeRequest) GetHomePhoneOk() (*string, bool)`

GetHomePhoneOk returns a tuple with the HomePhone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHomePhone

`func (o *EmployeesApiCreateEmployeeRequest) SetHomePhone(v string)`

SetHomePhone sets HomePhone field to given value.

### HasHomePhone

`func (o *EmployeesApiCreateEmployeeRequest) HasHomePhone() bool`

HasHomePhone returns a boolean if a field has been set.

### GetMobilePhone

`func (o *EmployeesApiCreateEmployeeRequest) GetMobilePhone() string`

GetMobilePhone returns the MobilePhone field if non-nil, zero value otherwise.

### GetMobilePhoneOk

`func (o *EmployeesApiCreateEmployeeRequest) GetMobilePhoneOk() (*string, bool)`

GetMobilePhoneOk returns a tuple with the MobilePhone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMobilePhone

`func (o *EmployeesApiCreateEmployeeRequest) SetMobilePhone(v string)`

SetMobilePhone sets MobilePhone field to given value.

### HasMobilePhone

`func (o *EmployeesApiCreateEmployeeRequest) HasMobilePhone() bool`

HasMobilePhone returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


