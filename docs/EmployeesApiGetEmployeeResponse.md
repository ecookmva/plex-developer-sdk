# EmployeesApiGetEmployeeResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | A unique identifier for the Employee. | [optional] 
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

### NewEmployeesApiGetEmployeeResponse

`func NewEmployeesApiGetEmployeeResponse() *EmployeesApiGetEmployeeResponse`

NewEmployeesApiGetEmployeeResponse instantiates a new EmployeesApiGetEmployeeResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEmployeesApiGetEmployeeResponseWithDefaults

`func NewEmployeesApiGetEmployeeResponseWithDefaults() *EmployeesApiGetEmployeeResponse`

NewEmployeesApiGetEmployeeResponseWithDefaults instantiates a new EmployeesApiGetEmployeeResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *EmployeesApiGetEmployeeResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *EmployeesApiGetEmployeeResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *EmployeesApiGetEmployeeResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *EmployeesApiGetEmployeeResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetBadgeNumber

`func (o *EmployeesApiGetEmployeeResponse) GetBadgeNumber() string`

GetBadgeNumber returns the BadgeNumber field if non-nil, zero value otherwise.

### GetBadgeNumberOk

`func (o *EmployeesApiGetEmployeeResponse) GetBadgeNumberOk() (*string, bool)`

GetBadgeNumberOk returns a tuple with the BadgeNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBadgeNumber

`func (o *EmployeesApiGetEmployeeResponse) SetBadgeNumber(v string)`

SetBadgeNumber sets BadgeNumber field to given value.

### HasBadgeNumber

`func (o *EmployeesApiGetEmployeeResponse) HasBadgeNumber() bool`

HasBadgeNumber returns a boolean if a field has been set.

### GetUserId

`func (o *EmployeesApiGetEmployeeResponse) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *EmployeesApiGetEmployeeResponse) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *EmployeesApiGetEmployeeResponse) SetUserId(v string)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *EmployeesApiGetEmployeeResponse) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### GetFirstName

`func (o *EmployeesApiGetEmployeeResponse) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *EmployeesApiGetEmployeeResponse) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *EmployeesApiGetEmployeeResponse) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.

### HasFirstName

`func (o *EmployeesApiGetEmployeeResponse) HasFirstName() bool`

HasFirstName returns a boolean if a field has been set.

### GetMiddleName

`func (o *EmployeesApiGetEmployeeResponse) GetMiddleName() string`

GetMiddleName returns the MiddleName field if non-nil, zero value otherwise.

### GetMiddleNameOk

`func (o *EmployeesApiGetEmployeeResponse) GetMiddleNameOk() (*string, bool)`

GetMiddleNameOk returns a tuple with the MiddleName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMiddleName

`func (o *EmployeesApiGetEmployeeResponse) SetMiddleName(v string)`

SetMiddleName sets MiddleName field to given value.

### HasMiddleName

`func (o *EmployeesApiGetEmployeeResponse) HasMiddleName() bool`

HasMiddleName returns a boolean if a field has been set.

### GetLastName

`func (o *EmployeesApiGetEmployeeResponse) GetLastName() string`

GetLastName returns the LastName field if non-nil, zero value otherwise.

### GetLastNameOk

`func (o *EmployeesApiGetEmployeeResponse) GetLastNameOk() (*string, bool)`

GetLastNameOk returns a tuple with the LastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastName

`func (o *EmployeesApiGetEmployeeResponse) SetLastName(v string)`

SetLastName sets LastName field to given value.

### HasLastName

`func (o *EmployeesApiGetEmployeeResponse) HasLastName() bool`

HasLastName returns a boolean if a field has been set.

### GetSupervisorId

`func (o *EmployeesApiGetEmployeeResponse) GetSupervisorId() string`

GetSupervisorId returns the SupervisorId field if non-nil, zero value otherwise.

### GetSupervisorIdOk

`func (o *EmployeesApiGetEmployeeResponse) GetSupervisorIdOk() (*string, bool)`

GetSupervisorIdOk returns a tuple with the SupervisorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupervisorId

`func (o *EmployeesApiGetEmployeeResponse) SetSupervisorId(v string)`

SetSupervisorId sets SupervisorId field to given value.

### HasSupervisorId

`func (o *EmployeesApiGetEmployeeResponse) HasSupervisorId() bool`

HasSupervisorId returns a boolean if a field has been set.

### GetStatus

`func (o *EmployeesApiGetEmployeeResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *EmployeesApiGetEmployeeResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *EmployeesApiGetEmployeeResponse) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *EmployeesApiGetEmployeeResponse) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetPosition

`func (o *EmployeesApiGetEmployeeResponse) GetPosition() string`

GetPosition returns the Position field if non-nil, zero value otherwise.

### GetPositionOk

`func (o *EmployeesApiGetEmployeeResponse) GetPositionOk() (*string, bool)`

GetPositionOk returns a tuple with the Position field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosition

`func (o *EmployeesApiGetEmployeeResponse) SetPosition(v string)`

SetPosition sets Position field to given value.

### HasPosition

`func (o *EmployeesApiGetEmployeeResponse) HasPosition() bool`

HasPosition returns a boolean if a field has been set.

### GetShift

`func (o *EmployeesApiGetEmployeeResponse) GetShift() string`

GetShift returns the Shift field if non-nil, zero value otherwise.

### GetShiftOk

`func (o *EmployeesApiGetEmployeeResponse) GetShiftOk() (*string, bool)`

GetShiftOk returns a tuple with the Shift field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShift

`func (o *EmployeesApiGetEmployeeResponse) SetShift(v string)`

SetShift sets Shift field to given value.

### HasShift

`func (o *EmployeesApiGetEmployeeResponse) HasShift() bool`

HasShift returns a boolean if a field has been set.

### GetBuilding

`func (o *EmployeesApiGetEmployeeResponse) GetBuilding() string`

GetBuilding returns the Building field if non-nil, zero value otherwise.

### GetBuildingOk

`func (o *EmployeesApiGetEmployeeResponse) GetBuildingOk() (*string, bool)`

GetBuildingOk returns a tuple with the Building field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuilding

`func (o *EmployeesApiGetEmployeeResponse) SetBuilding(v string)`

SetBuilding sets Building field to given value.

### HasBuilding

`func (o *EmployeesApiGetEmployeeResponse) HasBuilding() bool`

HasBuilding returns a boolean if a field has been set.

### GetType

`func (o *EmployeesApiGetEmployeeResponse) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *EmployeesApiGetEmployeeResponse) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *EmployeesApiGetEmployeeResponse) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *EmployeesApiGetEmployeeResponse) HasType() bool`

HasType returns a boolean if a field has been set.

### GetDepartment

`func (o *EmployeesApiGetEmployeeResponse) GetDepartment() string`

GetDepartment returns the Department field if non-nil, zero value otherwise.

### GetDepartmentOk

`func (o *EmployeesApiGetEmployeeResponse) GetDepartmentOk() (*string, bool)`

GetDepartmentOk returns a tuple with the Department field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDepartment

`func (o *EmployeesApiGetEmployeeResponse) SetDepartment(v string)`

SetDepartment sets Department field to given value.

### HasDepartment

`func (o *EmployeesApiGetEmployeeResponse) HasDepartment() bool`

HasDepartment returns a boolean if a field has been set.

### GetEmail

`func (o *EmployeesApiGetEmployeeResponse) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *EmployeesApiGetEmployeeResponse) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *EmployeesApiGetEmployeeResponse) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *EmployeesApiGetEmployeeResponse) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetWorkPhone

`func (o *EmployeesApiGetEmployeeResponse) GetWorkPhone() string`

GetWorkPhone returns the WorkPhone field if non-nil, zero value otherwise.

### GetWorkPhoneOk

`func (o *EmployeesApiGetEmployeeResponse) GetWorkPhoneOk() (*string, bool)`

GetWorkPhoneOk returns a tuple with the WorkPhone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkPhone

`func (o *EmployeesApiGetEmployeeResponse) SetWorkPhone(v string)`

SetWorkPhone sets WorkPhone field to given value.

### HasWorkPhone

`func (o *EmployeesApiGetEmployeeResponse) HasWorkPhone() bool`

HasWorkPhone returns a boolean if a field has been set.

### GetWorkExtension

`func (o *EmployeesApiGetEmployeeResponse) GetWorkExtension() string`

GetWorkExtension returns the WorkExtension field if non-nil, zero value otherwise.

### GetWorkExtensionOk

`func (o *EmployeesApiGetEmployeeResponse) GetWorkExtensionOk() (*string, bool)`

GetWorkExtensionOk returns a tuple with the WorkExtension field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkExtension

`func (o *EmployeesApiGetEmployeeResponse) SetWorkExtension(v string)`

SetWorkExtension sets WorkExtension field to given value.

### HasWorkExtension

`func (o *EmployeesApiGetEmployeeResponse) HasWorkExtension() bool`

HasWorkExtension returns a boolean if a field has been set.

### GetHomePhone

`func (o *EmployeesApiGetEmployeeResponse) GetHomePhone() string`

GetHomePhone returns the HomePhone field if non-nil, zero value otherwise.

### GetHomePhoneOk

`func (o *EmployeesApiGetEmployeeResponse) GetHomePhoneOk() (*string, bool)`

GetHomePhoneOk returns a tuple with the HomePhone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHomePhone

`func (o *EmployeesApiGetEmployeeResponse) SetHomePhone(v string)`

SetHomePhone sets HomePhone field to given value.

### HasHomePhone

`func (o *EmployeesApiGetEmployeeResponse) HasHomePhone() bool`

HasHomePhone returns a boolean if a field has been set.

### GetMobilePhone

`func (o *EmployeesApiGetEmployeeResponse) GetMobilePhone() string`

GetMobilePhone returns the MobilePhone field if non-nil, zero value otherwise.

### GetMobilePhoneOk

`func (o *EmployeesApiGetEmployeeResponse) GetMobilePhoneOk() (*string, bool)`

GetMobilePhoneOk returns a tuple with the MobilePhone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMobilePhone

`func (o *EmployeesApiGetEmployeeResponse) SetMobilePhone(v string)`

SetMobilePhone sets MobilePhone field to given value.

### HasMobilePhone

`func (o *EmployeesApiGetEmployeeResponse) HasMobilePhone() bool`

HasMobilePhone returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


