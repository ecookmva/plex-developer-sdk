# ContactsApiUpdateContactRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | A unique identifier for the Contact. | [optional] 
**CustomerId** | Pointer to **string** |  | [optional] 
**FirstName** | Pointer to **string** |  | [optional] 
**LastName** | Pointer to **string** |  | [optional] 
**SupplierId** | Pointer to **string** |  | [optional] 
**Phone** | Pointer to **string** |  | [optional] 
**Fax** | Pointer to **string** |  | [optional] 
**MobilePhone** | Pointer to **string** |  | [optional] 
**Title** | Pointer to **string** |  | [optional] 
**Note** | Pointer to **string** |  | [optional] 
**Email** | Pointer to **string** |  | [optional] 
**CompanyName** | Pointer to **string** |  | [optional] 
**OfficeAddress** | Pointer to **string** |  | [optional] 
**HomeAddress** | Pointer to **string** |  | [optional] 
**Private** | Pointer to **int32** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**BirthDate** | Pointer to **time.Time** |  | [optional] 
**Url** | Pointer to **string** |  | [optional] 
**SortOrder** | Pointer to **int32** |  | [optional] 
**Type** | Pointer to **string** | Setup Table: Contact Type. | [optional] 
**AssociatedWithId** | Pointer to **string** | IAM Account Id | [optional] 

## Methods

### NewContactsApiUpdateContactRequest

`func NewContactsApiUpdateContactRequest() *ContactsApiUpdateContactRequest`

NewContactsApiUpdateContactRequest instantiates a new ContactsApiUpdateContactRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContactsApiUpdateContactRequestWithDefaults

`func NewContactsApiUpdateContactRequestWithDefaults() *ContactsApiUpdateContactRequest`

NewContactsApiUpdateContactRequestWithDefaults instantiates a new ContactsApiUpdateContactRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ContactsApiUpdateContactRequest) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ContactsApiUpdateContactRequest) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ContactsApiUpdateContactRequest) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *ContactsApiUpdateContactRequest) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCustomerId

`func (o *ContactsApiUpdateContactRequest) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *ContactsApiUpdateContactRequest) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *ContactsApiUpdateContactRequest) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *ContactsApiUpdateContactRequest) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### GetFirstName

`func (o *ContactsApiUpdateContactRequest) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *ContactsApiUpdateContactRequest) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *ContactsApiUpdateContactRequest) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.

### HasFirstName

`func (o *ContactsApiUpdateContactRequest) HasFirstName() bool`

HasFirstName returns a boolean if a field has been set.

### GetLastName

`func (o *ContactsApiUpdateContactRequest) GetLastName() string`

GetLastName returns the LastName field if non-nil, zero value otherwise.

### GetLastNameOk

`func (o *ContactsApiUpdateContactRequest) GetLastNameOk() (*string, bool)`

GetLastNameOk returns a tuple with the LastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastName

`func (o *ContactsApiUpdateContactRequest) SetLastName(v string)`

SetLastName sets LastName field to given value.

### HasLastName

`func (o *ContactsApiUpdateContactRequest) HasLastName() bool`

HasLastName returns a boolean if a field has been set.

### GetSupplierId

`func (o *ContactsApiUpdateContactRequest) GetSupplierId() string`

GetSupplierId returns the SupplierId field if non-nil, zero value otherwise.

### GetSupplierIdOk

`func (o *ContactsApiUpdateContactRequest) GetSupplierIdOk() (*string, bool)`

GetSupplierIdOk returns a tuple with the SupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierId

`func (o *ContactsApiUpdateContactRequest) SetSupplierId(v string)`

SetSupplierId sets SupplierId field to given value.

### HasSupplierId

`func (o *ContactsApiUpdateContactRequest) HasSupplierId() bool`

HasSupplierId returns a boolean if a field has been set.

### GetPhone

`func (o *ContactsApiUpdateContactRequest) GetPhone() string`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *ContactsApiUpdateContactRequest) GetPhoneOk() (*string, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *ContactsApiUpdateContactRequest) SetPhone(v string)`

SetPhone sets Phone field to given value.

### HasPhone

`func (o *ContactsApiUpdateContactRequest) HasPhone() bool`

HasPhone returns a boolean if a field has been set.

### GetFax

`func (o *ContactsApiUpdateContactRequest) GetFax() string`

GetFax returns the Fax field if non-nil, zero value otherwise.

### GetFaxOk

`func (o *ContactsApiUpdateContactRequest) GetFaxOk() (*string, bool)`

GetFaxOk returns a tuple with the Fax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFax

`func (o *ContactsApiUpdateContactRequest) SetFax(v string)`

SetFax sets Fax field to given value.

### HasFax

`func (o *ContactsApiUpdateContactRequest) HasFax() bool`

HasFax returns a boolean if a field has been set.

### GetMobilePhone

`func (o *ContactsApiUpdateContactRequest) GetMobilePhone() string`

GetMobilePhone returns the MobilePhone field if non-nil, zero value otherwise.

### GetMobilePhoneOk

`func (o *ContactsApiUpdateContactRequest) GetMobilePhoneOk() (*string, bool)`

GetMobilePhoneOk returns a tuple with the MobilePhone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMobilePhone

`func (o *ContactsApiUpdateContactRequest) SetMobilePhone(v string)`

SetMobilePhone sets MobilePhone field to given value.

### HasMobilePhone

`func (o *ContactsApiUpdateContactRequest) HasMobilePhone() bool`

HasMobilePhone returns a boolean if a field has been set.

### GetTitle

`func (o *ContactsApiUpdateContactRequest) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *ContactsApiUpdateContactRequest) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *ContactsApiUpdateContactRequest) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *ContactsApiUpdateContactRequest) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### GetNote

`func (o *ContactsApiUpdateContactRequest) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *ContactsApiUpdateContactRequest) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *ContactsApiUpdateContactRequest) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *ContactsApiUpdateContactRequest) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetEmail

`func (o *ContactsApiUpdateContactRequest) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *ContactsApiUpdateContactRequest) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *ContactsApiUpdateContactRequest) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *ContactsApiUpdateContactRequest) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetCompanyName

`func (o *ContactsApiUpdateContactRequest) GetCompanyName() string`

GetCompanyName returns the CompanyName field if non-nil, zero value otherwise.

### GetCompanyNameOk

`func (o *ContactsApiUpdateContactRequest) GetCompanyNameOk() (*string, bool)`

GetCompanyNameOk returns a tuple with the CompanyName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompanyName

`func (o *ContactsApiUpdateContactRequest) SetCompanyName(v string)`

SetCompanyName sets CompanyName field to given value.

### HasCompanyName

`func (o *ContactsApiUpdateContactRequest) HasCompanyName() bool`

HasCompanyName returns a boolean if a field has been set.

### GetOfficeAddress

`func (o *ContactsApiUpdateContactRequest) GetOfficeAddress() string`

GetOfficeAddress returns the OfficeAddress field if non-nil, zero value otherwise.

### GetOfficeAddressOk

`func (o *ContactsApiUpdateContactRequest) GetOfficeAddressOk() (*string, bool)`

GetOfficeAddressOk returns a tuple with the OfficeAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOfficeAddress

`func (o *ContactsApiUpdateContactRequest) SetOfficeAddress(v string)`

SetOfficeAddress sets OfficeAddress field to given value.

### HasOfficeAddress

`func (o *ContactsApiUpdateContactRequest) HasOfficeAddress() bool`

HasOfficeAddress returns a boolean if a field has been set.

### GetHomeAddress

`func (o *ContactsApiUpdateContactRequest) GetHomeAddress() string`

GetHomeAddress returns the HomeAddress field if non-nil, zero value otherwise.

### GetHomeAddressOk

`func (o *ContactsApiUpdateContactRequest) GetHomeAddressOk() (*string, bool)`

GetHomeAddressOk returns a tuple with the HomeAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHomeAddress

`func (o *ContactsApiUpdateContactRequest) SetHomeAddress(v string)`

SetHomeAddress sets HomeAddress field to given value.

### HasHomeAddress

`func (o *ContactsApiUpdateContactRequest) HasHomeAddress() bool`

HasHomeAddress returns a boolean if a field has been set.

### GetPrivate

`func (o *ContactsApiUpdateContactRequest) GetPrivate() int32`

GetPrivate returns the Private field if non-nil, zero value otherwise.

### GetPrivateOk

`func (o *ContactsApiUpdateContactRequest) GetPrivateOk() (*int32, bool)`

GetPrivateOk returns a tuple with the Private field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrivate

`func (o *ContactsApiUpdateContactRequest) SetPrivate(v int32)`

SetPrivate sets Private field to given value.

### HasPrivate

`func (o *ContactsApiUpdateContactRequest) HasPrivate() bool`

HasPrivate returns a boolean if a field has been set.

### GetDescription

`func (o *ContactsApiUpdateContactRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ContactsApiUpdateContactRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ContactsApiUpdateContactRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ContactsApiUpdateContactRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetBirthDate

`func (o *ContactsApiUpdateContactRequest) GetBirthDate() time.Time`

GetBirthDate returns the BirthDate field if non-nil, zero value otherwise.

### GetBirthDateOk

`func (o *ContactsApiUpdateContactRequest) GetBirthDateOk() (*time.Time, bool)`

GetBirthDateOk returns a tuple with the BirthDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBirthDate

`func (o *ContactsApiUpdateContactRequest) SetBirthDate(v time.Time)`

SetBirthDate sets BirthDate field to given value.

### HasBirthDate

`func (o *ContactsApiUpdateContactRequest) HasBirthDate() bool`

HasBirthDate returns a boolean if a field has been set.

### GetUrl

`func (o *ContactsApiUpdateContactRequest) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *ContactsApiUpdateContactRequest) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *ContactsApiUpdateContactRequest) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *ContactsApiUpdateContactRequest) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### GetSortOrder

`func (o *ContactsApiUpdateContactRequest) GetSortOrder() int32`

GetSortOrder returns the SortOrder field if non-nil, zero value otherwise.

### GetSortOrderOk

`func (o *ContactsApiUpdateContactRequest) GetSortOrderOk() (*int32, bool)`

GetSortOrderOk returns a tuple with the SortOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSortOrder

`func (o *ContactsApiUpdateContactRequest) SetSortOrder(v int32)`

SetSortOrder sets SortOrder field to given value.

### HasSortOrder

`func (o *ContactsApiUpdateContactRequest) HasSortOrder() bool`

HasSortOrder returns a boolean if a field has been set.

### GetType

`func (o *ContactsApiUpdateContactRequest) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ContactsApiUpdateContactRequest) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ContactsApiUpdateContactRequest) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *ContactsApiUpdateContactRequest) HasType() bool`

HasType returns a boolean if a field has been set.

### GetAssociatedWithId

`func (o *ContactsApiUpdateContactRequest) GetAssociatedWithId() string`

GetAssociatedWithId returns the AssociatedWithId field if non-nil, zero value otherwise.

### GetAssociatedWithIdOk

`func (o *ContactsApiUpdateContactRequest) GetAssociatedWithIdOk() (*string, bool)`

GetAssociatedWithIdOk returns a tuple with the AssociatedWithId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssociatedWithId

`func (o *ContactsApiUpdateContactRequest) SetAssociatedWithId(v string)`

SetAssociatedWithId sets AssociatedWithId field to given value.

### HasAssociatedWithId

`func (o *ContactsApiUpdateContactRequest) HasAssociatedWithId() bool`

HasAssociatedWithId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


