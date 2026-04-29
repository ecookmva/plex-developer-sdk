# EmployeesApiUpdateEmployeeRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BadgeNumber** | Pointer to **string** | Employee badge number as used in Plex. | [optional] 
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

### NewEmployeesApiUpdateEmployeeRequest

`func NewEmployeesApiUpdateEmployeeRequest() *EmployeesApiUpdateEmployeeRequest`

NewEmployeesApiUpdateEmployeeRequest instantiates a new EmployeesApiUpdateEmployeeRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEmployeesApiUpdateEmployeeRequestWithDefaults

`func NewEmployeesApiUpdateEmployeeRequestWithDefaults() *EmployeesApiUpdateEmployeeRequest`

NewEmployeesApiUpdateEmployeeRequestWithDefaults instantiates a new EmployeesApiUpdateEmployeeRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBadgeNumber

`func (o *EmployeesApiUpdateEmployeeRequest) GetBadgeNumber() string`

GetBadgeNumber returns the BadgeNumber field if non-nil, zero value otherwise.

### GetBadgeNumberOk

`func (o *EmployeesApiUpdateEmployeeRequest) GetBadgeNumberOk() (*string, bool)`

GetBadgeNumberOk returns a tuple with the BadgeNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBadgeNumber

`func (o *EmployeesApiUpdateEmployeeRequest) SetBadgeNumber(v string)`

SetBadgeNumber sets BadgeNumber field to given value.

### HasBadgeNumber

`func (o *EmployeesApiUpdateEmployeeRequest) HasBadgeNumber() bool`

HasBadgeNumber returns a boolean if a field has been set.

### GetFirstName

`func (o *EmployeesApiUpdateEmployeeRequest) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *EmployeesApiUpdateEmployeeRequest) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *EmployeesApiUpdateEmployeeRequest) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.

### HasFirstName

`func (o *EmployeesApiUpdateEmployeeRequest) HasFirstName() bool`

HasFirstName returns a boolean if a field has been set.

### GetMiddleName

`func (o *EmployeesApiUpdateEmployeeRequest) GetMiddleName() string`

GetMiddleName returns the MiddleName field if non-nil, zero value otherwise.

### GetMiddleNameOk

`func (o *EmployeesApiUpdateEmployeeRequest) GetMiddleNameOk() (*string, bool)`

GetMiddleNameOk returns a tuple with the MiddleName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMiddleName

`func (o *EmployeesApiUpdateEmployeeRequest) SetMiddleName(v string)`

SetMiddleName sets MiddleName field to given value.

### HasMiddleName

`func (o *EmployeesApiUpdateEmployeeRequest) HasMiddleName() bool`

HasMiddleName returns a boolean if a field has been set.

### GetLastName

`func (o *EmployeesApiUpdateEmployeeRequest) GetLastName() string`

GetLastName returns the LastName field if non-nil, zero value otherwise.

### GetLastNameOk

`func (o *EmployeesApiUpdateEmployeeRequest) GetLastNameOk() (*string, bool)`

GetLastNameOk returns a tuple with the LastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastName

`func (o *EmployeesApiUpdateEmployeeRequest) SetLastName(v string)`

SetLastName sets LastName field to given value.

### HasLastName

`func (o *EmployeesApiUpdateEmployeeRequest) HasLastName() bool`

HasLastName returns a boolean if a field has been set.

### GetSupervisorId

`func (o *EmployeesApiUpdateEmployeeRequest) GetSupervisorId() string`

GetSupervisorId returns the SupervisorId field if non-nil, zero value otherwise.

### GetSupervisorIdOk

`func (o *EmployeesApiUpdateEmployeeRequest) GetSupervisorIdOk() (*string, bool)`

GetSupervisorIdOk returns a tuple with the SupervisorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupervisorId

`func (o *EmployeesApiUpdateEmployeeRequest) SetSupervisorId(v string)`

SetSupervisorId sets SupervisorId field to given value.

### HasSupervisorId

`func (o *EmployeesApiUpdateEmployeeRequest) HasSupervisorId() bool`

HasSupervisorId returns a boolean if a field has been set.

### GetStatus

`func (o *EmployeesApiUpdateEmployeeRequest) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *EmployeesApiUpdateEmployeeRequest) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *EmployeesApiUpdateEmployeeRequest) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *EmployeesApiUpdateEmployeeRequest) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetPosition

`func (o *EmployeesApiUpdateEmployeeRequest) GetPosition() string`

GetPosition returns the Position field if non-nil, zero value otherwise.

### GetPositionOk

`func (o *EmployeesApiUpdateEmployeeRequest) GetPositionOk() (*string, bool)`

GetPositionOk returns a tuple with the Position field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosition

`func (o *EmployeesApiUpdateEmployeeRequest) SetPosition(v string)`

SetPosition sets Position field to given value.

### HasPosition

`func (o *EmployeesApiUpdateEmployeeRequest) HasPosition() bool`

HasPosition returns a boolean if a field has been set.

### GetShift

`func (o *EmployeesApiUpdateEmployeeRequest) GetShift() string`

GetShift returns the Shift field if non-nil, zero value otherwise.

### GetShiftOk

`func (o *EmployeesApiUpdateEmployeeRequest) GetShiftOk() (*string, bool)`

GetShiftOk returns a tuple with the Shift field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShift

`func (o *EmployeesApiUpdateEmployeeRequest) SetShift(v string)`

SetShift sets Shift field to given value.

### HasShift

`func (o *EmployeesApiUpdateEmployeeRequest) HasShift() bool`

HasShift returns a boolean if a field has been set.

### GetBuilding

`func (o *EmployeesApiUpdateEmployeeRequest) GetBuilding() string`

GetBuilding returns the Building field if non-nil, zero value otherwise.

### GetBuildingOk

`func (o *EmployeesApiUpdateEmployeeRequest) GetBuildingOk() (*string, bool)`

GetBuildingOk returns a tuple with the Building field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuilding

`func (o *EmployeesApiUpdateEmployeeRequest) SetBuilding(v string)`

SetBuilding sets Building field to given value.

### HasBuilding

`func (o *EmployeesApiUpdateEmployeeRequest) HasBuilding() bool`

HasBuilding returns a boolean if a field has been set.

### GetType

`func (o *EmployeesApiUpdateEmployeeRequest) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *EmployeesApiUpdateEmployeeRequest) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *EmployeesApiUpdateEmployeeRequest) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *EmployeesApiUpdateEmployeeRequest) HasType() bool`

HasType returns a boolean if a field has been set.

### GetDepartment

`func (o *EmployeesApiUpdateEmployeeRequest) GetDepartment() string`

GetDepartment returns the Department field if non-nil, zero value otherwise.

### GetDepartmentOk

`func (o *EmployeesApiUpdateEmployeeRequest) GetDepartmentOk() (*string, bool)`

GetDepartmentOk returns a tuple with the Department field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDepartment

`func (o *EmployeesApiUpdateEmployeeRequest) SetDepartment(v string)`

SetDepartment sets Department field to given value.

### HasDepartment

`func (o *EmployeesApiUpdateEmployeeRequest) HasDepartment() bool`

HasDepartment returns a boolean if a field has been set.

### GetEmail

`func (o *EmployeesApiUpdateEmployeeRequest) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *EmployeesApiUpdateEmployeeRequest) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *EmployeesApiUpdateEmployeeRequest) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *EmployeesApiUpdateEmployeeRequest) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetWorkPhone

`func (o *EmployeesApiUpdateEmployeeRequest) GetWorkPhone() string`

GetWorkPhone returns the WorkPhone field if non-nil, zero value otherwise.

### GetWorkPhoneOk

`func (o *EmployeesApiUpdateEmployeeRequest) GetWorkPhoneOk() (*string, bool)`

GetWorkPhoneOk returns a tuple with the WorkPhone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkPhone

`func (o *EmployeesApiUpdateEmployeeRequest) SetWorkPhone(v string)`

SetWorkPhone sets WorkPhone field to given value.

### HasWorkPhone

`func (o *EmployeesApiUpdateEmployeeRequest) HasWorkPhone() bool`

HasWorkPhone returns a boolean if a field has been set.

### GetWorkExtension

`func (o *EmployeesApiUpdateEmployeeRequest) GetWorkExtension() string`

GetWorkExtension returns the WorkExtension field if non-nil, zero value otherwise.

### GetWorkExtensionOk

`func (o *EmployeesApiUpdateEmployeeRequest) GetWorkExtensionOk() (*string, bool)`

GetWorkExtensionOk returns a tuple with the WorkExtension field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkExtension

`func (o *EmployeesApiUpdateEmployeeRequest) SetWorkExtension(v string)`

SetWorkExtension sets WorkExtension field to given value.

### HasWorkExtension

`func (o *EmployeesApiUpdateEmployeeRequest) HasWorkExtension() bool`

HasWorkExtension returns a boolean if a field has been set.

### GetHomePhone

`func (o *EmployeesApiUpdateEmployeeRequest) GetHomePhone() string`

GetHomePhone returns the HomePhone field if non-nil, zero value otherwise.

### GetHomePhoneOk

`func (o *EmployeesApiUpdateEmployeeRequest) GetHomePhoneOk() (*string, bool)`

GetHomePhoneOk returns a tuple with the HomePhone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHomePhone

`func (o *EmployeesApiUpdateEmployeeRequest) SetHomePhone(v string)`

SetHomePhone sets HomePhone field to given value.

### HasHomePhone

`func (o *EmployeesApiUpdateEmployeeRequest) HasHomePhone() bool`

HasHomePhone returns a boolean if a field has been set.

### GetMobilePhone

`func (o *EmployeesApiUpdateEmployeeRequest) GetMobilePhone() string`

GetMobilePhone returns the MobilePhone field if non-nil, zero value otherwise.

### GetMobilePhoneOk

`func (o *EmployeesApiUpdateEmployeeRequest) GetMobilePhoneOk() (*string, bool)`

GetMobilePhoneOk returns a tuple with the MobilePhone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMobilePhone

`func (o *EmployeesApiUpdateEmployeeRequest) SetMobilePhone(v string)`

SetMobilePhone sets MobilePhone field to given value.

### HasMobilePhone

`func (o *EmployeesApiUpdateEmployeeRequest) HasMobilePhone() bool`

HasMobilePhone returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


