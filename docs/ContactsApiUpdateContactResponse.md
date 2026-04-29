# ContactsApiUpdateContactResponse

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
**Type** | Pointer to **string** | Setup table: Contact Type. | [optional] 
**AssociatedWithId** | Pointer to **string** | IAM Account Id | [optional] 
**ModifiedById** | Pointer to **string** | IAM Account Id | [optional] 
**ModifiedDate** | Pointer to **time.Time** |  | [optional] 
**CreatedById** | Pointer to **string** | IAM Account Id | [optional] 
**CreatedDate** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewContactsApiUpdateContactResponse

`func NewContactsApiUpdateContactResponse() *ContactsApiUpdateContactResponse`

NewContactsApiUpdateContactResponse instantiates a new ContactsApiUpdateContactResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContactsApiUpdateContactResponseWithDefaults

`func NewContactsApiUpdateContactResponseWithDefaults() *ContactsApiUpdateContactResponse`

NewContactsApiUpdateContactResponseWithDefaults instantiates a new ContactsApiUpdateContactResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ContactsApiUpdateContactResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ContactsApiUpdateContactResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ContactsApiUpdateContactResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *ContactsApiUpdateContactResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCustomerId

`func (o *ContactsApiUpdateContactResponse) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *ContactsApiUpdateContactResponse) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *ContactsApiUpdateContactResponse) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *ContactsApiUpdateContactResponse) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### GetFirstName

`func (o *ContactsApiUpdateContactResponse) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *ContactsApiUpdateContactResponse) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *ContactsApiUpdateContactResponse) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.

### HasFirstName

`func (o *ContactsApiUpdateContactResponse) HasFirstName() bool`

HasFirstName returns a boolean if a field has been set.

### GetLastName

`func (o *ContactsApiUpdateContactResponse) GetLastName() string`

GetLastName returns the LastName field if non-nil, zero value otherwise.

### GetLastNameOk

`func (o *ContactsApiUpdateContactResponse) GetLastNameOk() (*string, bool)`

GetLastNameOk returns a tuple with the LastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastName

`func (o *ContactsApiUpdateContactResponse) SetLastName(v string)`

SetLastName sets LastName field to given value.

### HasLastName

`func (o *ContactsApiUpdateContactResponse) HasLastName() bool`

HasLastName returns a boolean if a field has been set.

### GetSupplierId

`func (o *ContactsApiUpdateContactResponse) GetSupplierId() string`

GetSupplierId returns the SupplierId field if non-nil, zero value otherwise.

### GetSupplierIdOk

`func (o *ContactsApiUpdateContactResponse) GetSupplierIdOk() (*string, bool)`

GetSupplierIdOk returns a tuple with the SupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierId

`func (o *ContactsApiUpdateContactResponse) SetSupplierId(v string)`

SetSupplierId sets SupplierId field to given value.

### HasSupplierId

`func (o *ContactsApiUpdateContactResponse) HasSupplierId() bool`

HasSupplierId returns a boolean if a field has been set.

### GetPhone

`func (o *ContactsApiUpdateContactResponse) GetPhone() string`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *ContactsApiUpdateContactResponse) GetPhoneOk() (*string, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *ContactsApiUpdateContactResponse) SetPhone(v string)`

SetPhone sets Phone field to given value.

### HasPhone

`func (o *ContactsApiUpdateContactResponse) HasPhone() bool`

HasPhone returns a boolean if a field has been set.

### GetFax

`func (o *ContactsApiUpdateContactResponse) GetFax() string`

GetFax returns the Fax field if non-nil, zero value otherwise.

### GetFaxOk

`func (o *ContactsApiUpdateContactResponse) GetFaxOk() (*string, bool)`

GetFaxOk returns a tuple with the Fax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFax

`func (o *ContactsApiUpdateContactResponse) SetFax(v string)`

SetFax sets Fax field to given value.

### HasFax

`func (o *ContactsApiUpdateContactResponse) HasFax() bool`

HasFax returns a boolean if a field has been set.

### GetMobilePhone

`func (o *ContactsApiUpdateContactResponse) GetMobilePhone() string`

GetMobilePhone returns the MobilePhone field if non-nil, zero value otherwise.

### GetMobilePhoneOk

`func (o *ContactsApiUpdateContactResponse) GetMobilePhoneOk() (*string, bool)`

GetMobilePhoneOk returns a tuple with the MobilePhone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMobilePhone

`func (o *ContactsApiUpdateContactResponse) SetMobilePhone(v string)`

SetMobilePhone sets MobilePhone field to given value.

### HasMobilePhone

`func (o *ContactsApiUpdateContactResponse) HasMobilePhone() bool`

HasMobilePhone returns a boolean if a field has been set.

### GetTitle

`func (o *ContactsApiUpdateContactResponse) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *ContactsApiUpdateContactResponse) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *ContactsApiUpdateContactResponse) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *ContactsApiUpdateContactResponse) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### GetNote

`func (o *ContactsApiUpdateContactResponse) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *ContactsApiUpdateContactResponse) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *ContactsApiUpdateContactResponse) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *ContactsApiUpdateContactResponse) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetEmail

`func (o *ContactsApiUpdateContactResponse) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *ContactsApiUpdateContactResponse) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *ContactsApiUpdateContactResponse) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *ContactsApiUpdateContactResponse) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetCompanyName

`func (o *ContactsApiUpdateContactResponse) GetCompanyName() string`

GetCompanyName returns the CompanyName field if non-nil, zero value otherwise.

### GetCompanyNameOk

`func (o *ContactsApiUpdateContactResponse) GetCompanyNameOk() (*string, bool)`

GetCompanyNameOk returns a tuple with the CompanyName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompanyName

`func (o *ContactsApiUpdateContactResponse) SetCompanyName(v string)`

SetCompanyName sets CompanyName field to given value.

### HasCompanyName

`func (o *ContactsApiUpdateContactResponse) HasCompanyName() bool`

HasCompanyName returns a boolean if a field has been set.

### GetOfficeAddress

`func (o *ContactsApiUpdateContactResponse) GetOfficeAddress() string`

GetOfficeAddress returns the OfficeAddress field if non-nil, zero value otherwise.

### GetOfficeAddressOk

`func (o *ContactsApiUpdateContactResponse) GetOfficeAddressOk() (*string, bool)`

GetOfficeAddressOk returns a tuple with the OfficeAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOfficeAddress

`func (o *ContactsApiUpdateContactResponse) SetOfficeAddress(v string)`

SetOfficeAddress sets OfficeAddress field to given value.

### HasOfficeAddress

`func (o *ContactsApiUpdateContactResponse) HasOfficeAddress() bool`

HasOfficeAddress returns a boolean if a field has been set.

### GetHomeAddress

`func (o *ContactsApiUpdateContactResponse) GetHomeAddress() string`

GetHomeAddress returns the HomeAddress field if non-nil, zero value otherwise.

### GetHomeAddressOk

`func (o *ContactsApiUpdateContactResponse) GetHomeAddressOk() (*string, bool)`

GetHomeAddressOk returns a tuple with the HomeAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHomeAddress

`func (o *ContactsApiUpdateContactResponse) SetHomeAddress(v string)`

SetHomeAddress sets HomeAddress field to given value.

### HasHomeAddress

`func (o *ContactsApiUpdateContactResponse) HasHomeAddress() bool`

HasHomeAddress returns a boolean if a field has been set.

### GetPrivate

`func (o *ContactsApiUpdateContactResponse) GetPrivate() int32`

GetPrivate returns the Private field if non-nil, zero value otherwise.

### GetPrivateOk

`func (o *ContactsApiUpdateContactResponse) GetPrivateOk() (*int32, bool)`

GetPrivateOk returns a tuple with the Private field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrivate

`func (o *ContactsApiUpdateContactResponse) SetPrivate(v int32)`

SetPrivate sets Private field to given value.

### HasPrivate

`func (o *ContactsApiUpdateContactResponse) HasPrivate() bool`

HasPrivate returns a boolean if a field has been set.

### GetDescription

`func (o *ContactsApiUpdateContactResponse) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ContactsApiUpdateContactResponse) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ContactsApiUpdateContactResponse) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ContactsApiUpdateContactResponse) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetBirthDate

`func (o *ContactsApiUpdateContactResponse) GetBirthDate() time.Time`

GetBirthDate returns the BirthDate field if non-nil, zero value otherwise.

### GetBirthDateOk

`func (o *ContactsApiUpdateContactResponse) GetBirthDateOk() (*time.Time, bool)`

GetBirthDateOk returns a tuple with the BirthDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBirthDate

`func (o *ContactsApiUpdateContactResponse) SetBirthDate(v time.Time)`

SetBirthDate sets BirthDate field to given value.

### HasBirthDate

`func (o *ContactsApiUpdateContactResponse) HasBirthDate() bool`

HasBirthDate returns a boolean if a field has been set.

### GetUrl

`func (o *ContactsApiUpdateContactResponse) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *ContactsApiUpdateContactResponse) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *ContactsApiUpdateContactResponse) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *ContactsApiUpdateContactResponse) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### GetSortOrder

`func (o *ContactsApiUpdateContactResponse) GetSortOrder() int32`

GetSortOrder returns the SortOrder field if non-nil, zero value otherwise.

### GetSortOrderOk

`func (o *ContactsApiUpdateContactResponse) GetSortOrderOk() (*int32, bool)`

GetSortOrderOk returns a tuple with the SortOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSortOrder

`func (o *ContactsApiUpdateContactResponse) SetSortOrder(v int32)`

SetSortOrder sets SortOrder field to given value.

### HasSortOrder

`func (o *ContactsApiUpdateContactResponse) HasSortOrder() bool`

HasSortOrder returns a boolean if a field has been set.

### GetType

`func (o *ContactsApiUpdateContactResponse) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ContactsApiUpdateContactResponse) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ContactsApiUpdateContactResponse) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *ContactsApiUpdateContactResponse) HasType() bool`

HasType returns a boolean if a field has been set.

### GetAssociatedWithId

`func (o *ContactsApiUpdateContactResponse) GetAssociatedWithId() string`

GetAssociatedWithId returns the AssociatedWithId field if non-nil, zero value otherwise.

### GetAssociatedWithIdOk

`func (o *ContactsApiUpdateContactResponse) GetAssociatedWithIdOk() (*string, bool)`

GetAssociatedWithIdOk returns a tuple with the AssociatedWithId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssociatedWithId

`func (o *ContactsApiUpdateContactResponse) SetAssociatedWithId(v string)`

SetAssociatedWithId sets AssociatedWithId field to given value.

### HasAssociatedWithId

`func (o *ContactsApiUpdateContactResponse) HasAssociatedWithId() bool`

HasAssociatedWithId returns a boolean if a field has been set.

### GetModifiedById

`func (o *ContactsApiUpdateContactResponse) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *ContactsApiUpdateContactResponse) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *ContactsApiUpdateContactResponse) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *ContactsApiUpdateContactResponse) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetModifiedDate

`func (o *ContactsApiUpdateContactResponse) GetModifiedDate() time.Time`

GetModifiedDate returns the ModifiedDate field if non-nil, zero value otherwise.

### GetModifiedDateOk

`func (o *ContactsApiUpdateContactResponse) GetModifiedDateOk() (*time.Time, bool)`

GetModifiedDateOk returns a tuple with the ModifiedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDate

`func (o *ContactsApiUpdateContactResponse) SetModifiedDate(v time.Time)`

SetModifiedDate sets ModifiedDate field to given value.

### HasModifiedDate

`func (o *ContactsApiUpdateContactResponse) HasModifiedDate() bool`

HasModifiedDate returns a boolean if a field has been set.

### GetCreatedById

`func (o *ContactsApiUpdateContactResponse) GetCreatedById() string`

GetCreatedById returns the CreatedById field if non-nil, zero value otherwise.

### GetCreatedByIdOk

`func (o *ContactsApiUpdateContactResponse) GetCreatedByIdOk() (*string, bool)`

GetCreatedByIdOk returns a tuple with the CreatedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedById

`func (o *ContactsApiUpdateContactResponse) SetCreatedById(v string)`

SetCreatedById sets CreatedById field to given value.

### HasCreatedById

`func (o *ContactsApiUpdateContactResponse) HasCreatedById() bool`

HasCreatedById returns a boolean if a field has been set.

### GetCreatedDate

`func (o *ContactsApiUpdateContactResponse) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *ContactsApiUpdateContactResponse) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *ContactsApiUpdateContactResponse) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *ContactsApiUpdateContactResponse) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


