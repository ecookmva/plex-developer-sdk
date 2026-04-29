# EmployeesApiListEmployeesItem

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

### NewEmployeesApiListEmployeesItem

`func NewEmployeesApiListEmployeesItem() *EmployeesApiListEmployeesItem`

NewEmployeesApiListEmployeesItem instantiates a new EmployeesApiListEmployeesItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEmployeesApiListEmployeesItemWithDefaults

`func NewEmployeesApiListEmployeesItemWithDefaults() *EmployeesApiListEmployeesItem`

NewEmployeesApiListEmployeesItemWithDefaults instantiates a new EmployeesApiListEmployeesItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *EmployeesApiListEmployeesItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *EmployeesApiListEmployeesItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *EmployeesApiListEmployeesItem) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *EmployeesApiListEmployeesItem) HasId() bool`

HasId returns a boolean if a field has been set.

### GetBadgeNumber

`func (o *EmployeesApiListEmployeesItem) GetBadgeNumber() string`

GetBadgeNumber returns the BadgeNumber field if non-nil, zero value otherwise.

### GetBadgeNumberOk

`func (o *EmployeesApiListEmployeesItem) GetBadgeNumberOk() (*string, bool)`

GetBadgeNumberOk returns a tuple with the BadgeNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBadgeNumber

`func (o *EmployeesApiListEmployeesItem) SetBadgeNumber(v string)`

SetBadgeNumber sets BadgeNumber field to given value.

### HasBadgeNumber

`func (o *EmployeesApiListEmployeesItem) HasBadgeNumber() bool`

HasBadgeNumber returns a boolean if a field has been set.

### GetUserId

`func (o *EmployeesApiListEmployeesItem) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *EmployeesApiListEmployeesItem) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *EmployeesApiListEmployeesItem) SetUserId(v string)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *EmployeesApiListEmployeesItem) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### GetFirstName

`func (o *EmployeesApiListEmployeesItem) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *EmployeesApiListEmployeesItem) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *EmployeesApiListEmployeesItem) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.

### HasFirstName

`func (o *EmployeesApiListEmployeesItem) HasFirstName() bool`

HasFirstName returns a boolean if a field has been set.

### GetMiddleName

`func (o *EmployeesApiListEmployeesItem) GetMiddleName() string`

GetMiddleName returns the MiddleName field if non-nil, zero value otherwise.

### GetMiddleNameOk

`func (o *EmployeesApiListEmployeesItem) GetMiddleNameOk() (*string, bool)`

GetMiddleNameOk returns a tuple with the MiddleName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMiddleName

`func (o *EmployeesApiListEmployeesItem) SetMiddleName(v string)`

SetMiddleName sets MiddleName field to given value.

### HasMiddleName

`func (o *EmployeesApiListEmployeesItem) HasMiddleName() bool`

HasMiddleName returns a boolean if a field has been set.

### GetLastName

`func (o *EmployeesApiListEmployeesItem) GetLastName() string`

GetLastName returns the LastName field if non-nil, zero value otherwise.

### GetLastNameOk

`func (o *EmployeesApiListEmployeesItem) GetLastNameOk() (*string, bool)`

GetLastNameOk returns a tuple with the LastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastName

`func (o *EmployeesApiListEmployeesItem) SetLastName(v string)`

SetLastName sets LastName field to given value.

### HasLastName

`func (o *EmployeesApiListEmployeesItem) HasLastName() bool`

HasLastName returns a boolean if a field has been set.

### GetSupervisorId

`func (o *EmployeesApiListEmployeesItem) GetSupervisorId() string`

GetSupervisorId returns the SupervisorId field if non-nil, zero value otherwise.

### GetSupervisorIdOk

`func (o *EmployeesApiListEmployeesItem) GetSupervisorIdOk() (*string, bool)`

GetSupervisorIdOk returns a tuple with the SupervisorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupervisorId

`func (o *EmployeesApiListEmployeesItem) SetSupervisorId(v string)`

SetSupervisorId sets SupervisorId field to given value.

### HasSupervisorId

`func (o *EmployeesApiListEmployeesItem) HasSupervisorId() bool`

HasSupervisorId returns a boolean if a field has been set.

### GetStatus

`func (o *EmployeesApiListEmployeesItem) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *EmployeesApiListEmployeesItem) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *EmployeesApiListEmployeesItem) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *EmployeesApiListEmployeesItem) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetPosition

`func (o *EmployeesApiListEmployeesItem) GetPosition() string`

GetPosition returns the Position field if non-nil, zero value otherwise.

### GetPositionOk

`func (o *EmployeesApiListEmployeesItem) GetPositionOk() (*string, bool)`

GetPositionOk returns a tuple with the Position field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosition

`func (o *EmployeesApiListEmployeesItem) SetPosition(v string)`

SetPosition sets Position field to given value.

### HasPosition

`func (o *EmployeesApiListEmployeesItem) HasPosition() bool`

HasPosition returns a boolean if a field has been set.

### GetShift

`func (o *EmployeesApiListEmployeesItem) GetShift() string`

GetShift returns the Shift field if non-nil, zero value otherwise.

### GetShiftOk

`func (o *EmployeesApiListEmployeesItem) GetShiftOk() (*string, bool)`

GetShiftOk returns a tuple with the Shift field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShift

`func (o *EmployeesApiListEmployeesItem) SetShift(v string)`

SetShift sets Shift field to given value.

### HasShift

`func (o *EmployeesApiListEmployeesItem) HasShift() bool`

HasShift returns a boolean if a field has been set.

### GetBuilding

`func (o *EmployeesApiListEmployeesItem) GetBuilding() string`

GetBuilding returns the Building field if non-nil, zero value otherwise.

### GetBuildingOk

`func (o *EmployeesApiListEmployeesItem) GetBuildingOk() (*string, bool)`

GetBuildingOk returns a tuple with the Building field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuilding

`func (o *EmployeesApiListEmployeesItem) SetBuilding(v string)`

SetBuilding sets Building field to given value.

### HasBuilding

`func (o *EmployeesApiListEmployeesItem) HasBuilding() bool`

HasBuilding returns a boolean if a field has been set.

### GetType

`func (o *EmployeesApiListEmployeesItem) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *EmployeesApiListEmployeesItem) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *EmployeesApiListEmployeesItem) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *EmployeesApiListEmployeesItem) HasType() bool`

HasType returns a boolean if a field has been set.

### GetDepartment

`func (o *EmployeesApiListEmployeesItem) GetDepartment() string`

GetDepartment returns the Department field if non-nil, zero value otherwise.

### GetDepartmentOk

`func (o *EmployeesApiListEmployeesItem) GetDepartmentOk() (*string, bool)`

GetDepartmentOk returns a tuple with the Department field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDepartment

`func (o *EmployeesApiListEmployeesItem) SetDepartment(v string)`

SetDepartment sets Department field to given value.

### HasDepartment

`func (o *EmployeesApiListEmployeesItem) HasDepartment() bool`

HasDepartment returns a boolean if a field has been set.

### GetEmail

`func (o *EmployeesApiListEmployeesItem) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *EmployeesApiListEmployeesItem) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *EmployeesApiListEmployeesItem) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *EmployeesApiListEmployeesItem) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetWorkPhone

`func (o *EmployeesApiListEmployeesItem) GetWorkPhone() string`

GetWorkPhone returns the WorkPhone field if non-nil, zero value otherwise.

### GetWorkPhoneOk

`func (o *EmployeesApiListEmployeesItem) GetWorkPhoneOk() (*string, bool)`

GetWorkPhoneOk returns a tuple with the WorkPhone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkPhone

`func (o *EmployeesApiListEmployeesItem) SetWorkPhone(v string)`

SetWorkPhone sets WorkPhone field to given value.

### HasWorkPhone

`func (o *EmployeesApiListEmployeesItem) HasWorkPhone() bool`

HasWorkPhone returns a boolean if a field has been set.

### GetWorkExtension

`func (o *EmployeesApiListEmployeesItem) GetWorkExtension() string`

GetWorkExtension returns the WorkExtension field if non-nil, zero value otherwise.

### GetWorkExtensionOk

`func (o *EmployeesApiListEmployeesItem) GetWorkExtensionOk() (*string, bool)`

GetWorkExtensionOk returns a tuple with the WorkExtension field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkExtension

`func (o *EmployeesApiListEmployeesItem) SetWorkExtension(v string)`

SetWorkExtension sets WorkExtension field to given value.

### HasWorkExtension

`func (o *EmployeesApiListEmployeesItem) HasWorkExtension() bool`

HasWorkExtension returns a boolean if a field has been set.

### GetHomePhone

`func (o *EmployeesApiListEmployeesItem) GetHomePhone() string`

GetHomePhone returns the HomePhone field if non-nil, zero value otherwise.

### GetHomePhoneOk

`func (o *EmployeesApiListEmployeesItem) GetHomePhoneOk() (*string, bool)`

GetHomePhoneOk returns a tuple with the HomePhone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHomePhone

`func (o *EmployeesApiListEmployeesItem) SetHomePhone(v string)`

SetHomePhone sets HomePhone field to given value.

### HasHomePhone

`func (o *EmployeesApiListEmployeesItem) HasHomePhone() bool`

HasHomePhone returns a boolean if a field has been set.

### GetMobilePhone

`func (o *EmployeesApiListEmployeesItem) GetMobilePhone() string`

GetMobilePhone returns the MobilePhone field if non-nil, zero value otherwise.

### GetMobilePhoneOk

`func (o *EmployeesApiListEmployeesItem) GetMobilePhoneOk() (*string, bool)`

GetMobilePhoneOk returns a tuple with the MobilePhone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMobilePhone

`func (o *EmployeesApiListEmployeesItem) SetMobilePhone(v string)`

SetMobilePhone sets MobilePhone field to given value.

### HasMobilePhone

`func (o *EmployeesApiListEmployeesItem) HasMobilePhone() bool`

HasMobilePhone returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


