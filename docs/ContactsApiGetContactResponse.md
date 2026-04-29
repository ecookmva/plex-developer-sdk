# ContactsApiGetContactResponse

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

### NewContactsApiGetContactResponse

`func NewContactsApiGetContactResponse() *ContactsApiGetContactResponse`

NewContactsApiGetContactResponse instantiates a new ContactsApiGetContactResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContactsApiGetContactResponseWithDefaults

`func NewContactsApiGetContactResponseWithDefaults() *ContactsApiGetContactResponse`

NewContactsApiGetContactResponseWithDefaults instantiates a new ContactsApiGetContactResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ContactsApiGetContactResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ContactsApiGetContactResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ContactsApiGetContactResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *ContactsApiGetContactResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCustomerId

`func (o *ContactsApiGetContactResponse) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *ContactsApiGetContactResponse) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *ContactsApiGetContactResponse) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *ContactsApiGetContactResponse) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### GetFirstName

`func (o *ContactsApiGetContactResponse) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *ContactsApiGetContactResponse) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *ContactsApiGetContactResponse) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.

### HasFirstName

`func (o *ContactsApiGetContactResponse) HasFirstName() bool`

HasFirstName returns a boolean if a field has been set.

### GetLastName

`func (o *ContactsApiGetContactResponse) GetLastName() string`

GetLastName returns the LastName field if non-nil, zero value otherwise.

### GetLastNameOk

`func (o *ContactsApiGetContactResponse) GetLastNameOk() (*string, bool)`

GetLastNameOk returns a tuple with the LastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastName

`func (o *ContactsApiGetContactResponse) SetLastName(v string)`

SetLastName sets LastName field to given value.

### HasLastName

`func (o *ContactsApiGetContactResponse) HasLastName() bool`

HasLastName returns a boolean if a field has been set.

### GetSupplierId

`func (o *ContactsApiGetContactResponse) GetSupplierId() string`

GetSupplierId returns the SupplierId field if non-nil, zero value otherwise.

### GetSupplierIdOk

`func (o *ContactsApiGetContactResponse) GetSupplierIdOk() (*string, bool)`

GetSupplierIdOk returns a tuple with the SupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierId

`func (o *ContactsApiGetContactResponse) SetSupplierId(v string)`

SetSupplierId sets SupplierId field to given value.

### HasSupplierId

`func (o *ContactsApiGetContactResponse) HasSupplierId() bool`

HasSupplierId returns a boolean if a field has been set.

### GetPhone

`func (o *ContactsApiGetContactResponse) GetPhone() string`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *ContactsApiGetContactResponse) GetPhoneOk() (*string, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *ContactsApiGetContactResponse) SetPhone(v string)`

SetPhone sets Phone field to given value.

### HasPhone

`func (o *ContactsApiGetContactResponse) HasPhone() bool`

HasPhone returns a boolean if a field has been set.

### GetFax

`func (o *ContactsApiGetContactResponse) GetFax() string`

GetFax returns the Fax field if non-nil, zero value otherwise.

### GetFaxOk

`func (o *ContactsApiGetContactResponse) GetFaxOk() (*string, bool)`

GetFaxOk returns a tuple with the Fax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFax

`func (o *ContactsApiGetContactResponse) SetFax(v string)`

SetFax sets Fax field to given value.

### HasFax

`func (o *ContactsApiGetContactResponse) HasFax() bool`

HasFax returns a boolean if a field has been set.

### GetMobilePhone

`func (o *ContactsApiGetContactResponse) GetMobilePhone() string`

GetMobilePhone returns the MobilePhone field if non-nil, zero value otherwise.

### GetMobilePhoneOk

`func (o *ContactsApiGetContactResponse) GetMobilePhoneOk() (*string, bool)`

GetMobilePhoneOk returns a tuple with the MobilePhone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMobilePhone

`func (o *ContactsApiGetContactResponse) SetMobilePhone(v string)`

SetMobilePhone sets MobilePhone field to given value.

### HasMobilePhone

`func (o *ContactsApiGetContactResponse) HasMobilePhone() bool`

HasMobilePhone returns a boolean if a field has been set.

### GetTitle

`func (o *ContactsApiGetContactResponse) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *ContactsApiGetContactResponse) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *ContactsApiGetContactResponse) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *ContactsApiGetContactResponse) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### GetNote

`func (o *ContactsApiGetContactResponse) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *ContactsApiGetContactResponse) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *ContactsApiGetContactResponse) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *ContactsApiGetContactResponse) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetEmail

`func (o *ContactsApiGetContactResponse) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *ContactsApiGetContactResponse) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *ContactsApiGetContactResponse) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *ContactsApiGetContactResponse) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetCompanyName

`func (o *ContactsApiGetContactResponse) GetCompanyName() string`

GetCompanyName returns the CompanyName field if non-nil, zero value otherwise.

### GetCompanyNameOk

`func (o *ContactsApiGetContactResponse) GetCompanyNameOk() (*string, bool)`

GetCompanyNameOk returns a tuple with the CompanyName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompanyName

`func (o *ContactsApiGetContactResponse) SetCompanyName(v string)`

SetCompanyName sets CompanyName field to given value.

### HasCompanyName

`func (o *ContactsApiGetContactResponse) HasCompanyName() bool`

HasCompanyName returns a boolean if a field has been set.

### GetOfficeAddress

`func (o *ContactsApiGetContactResponse) GetOfficeAddress() string`

GetOfficeAddress returns the OfficeAddress field if non-nil, zero value otherwise.

### GetOfficeAddressOk

`func (o *ContactsApiGetContactResponse) GetOfficeAddressOk() (*string, bool)`

GetOfficeAddressOk returns a tuple with the OfficeAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOfficeAddress

`func (o *ContactsApiGetContactResponse) SetOfficeAddress(v string)`

SetOfficeAddress sets OfficeAddress field to given value.

### HasOfficeAddress

`func (o *ContactsApiGetContactResponse) HasOfficeAddress() bool`

HasOfficeAddress returns a boolean if a field has been set.

### GetHomeAddress

`func (o *ContactsApiGetContactResponse) GetHomeAddress() string`

GetHomeAddress returns the HomeAddress field if non-nil, zero value otherwise.

### GetHomeAddressOk

`func (o *ContactsApiGetContactResponse) GetHomeAddressOk() (*string, bool)`

GetHomeAddressOk returns a tuple with the HomeAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHomeAddress

`func (o *ContactsApiGetContactResponse) SetHomeAddress(v string)`

SetHomeAddress sets HomeAddress field to given value.

### HasHomeAddress

`func (o *ContactsApiGetContactResponse) HasHomeAddress() bool`

HasHomeAddress returns a boolean if a field has been set.

### GetPrivate

`func (o *ContactsApiGetContactResponse) GetPrivate() int32`

GetPrivate returns the Private field if non-nil, zero value otherwise.

### GetPrivateOk

`func (o *ContactsApiGetContactResponse) GetPrivateOk() (*int32, bool)`

GetPrivateOk returns a tuple with the Private field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrivate

`func (o *ContactsApiGetContactResponse) SetPrivate(v int32)`

SetPrivate sets Private field to given value.

### HasPrivate

`func (o *ContactsApiGetContactResponse) HasPrivate() bool`

HasPrivate returns a boolean if a field has been set.

### GetDescription

`func (o *ContactsApiGetContactResponse) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ContactsApiGetContactResponse) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ContactsApiGetContactResponse) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ContactsApiGetContactResponse) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetBirthDate

`func (o *ContactsApiGetContactResponse) GetBirthDate() time.Time`

GetBirthDate returns the BirthDate field if non-nil, zero value otherwise.

### GetBirthDateOk

`func (o *ContactsApiGetContactResponse) GetBirthDateOk() (*time.Time, bool)`

GetBirthDateOk returns a tuple with the BirthDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBirthDate

`func (o *ContactsApiGetContactResponse) SetBirthDate(v time.Time)`

SetBirthDate sets BirthDate field to given value.

### HasBirthDate

`func (o *ContactsApiGetContactResponse) HasBirthDate() bool`

HasBirthDate returns a boolean if a field has been set.

### GetUrl

`func (o *ContactsApiGetContactResponse) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *ContactsApiGetContactResponse) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *ContactsApiGetContactResponse) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *ContactsApiGetContactResponse) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### GetSortOrder

`func (o *ContactsApiGetContactResponse) GetSortOrder() int32`

GetSortOrder returns the SortOrder field if non-nil, zero value otherwise.

### GetSortOrderOk

`func (o *ContactsApiGetContactResponse) GetSortOrderOk() (*int32, bool)`

GetSortOrderOk returns a tuple with the SortOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSortOrder

`func (o *ContactsApiGetContactResponse) SetSortOrder(v int32)`

SetSortOrder sets SortOrder field to given value.

### HasSortOrder

`func (o *ContactsApiGetContactResponse) HasSortOrder() bool`

HasSortOrder returns a boolean if a field has been set.

### GetType

`func (o *ContactsApiGetContactResponse) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ContactsApiGetContactResponse) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ContactsApiGetContactResponse) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *ContactsApiGetContactResponse) HasType() bool`

HasType returns a boolean if a field has been set.

### GetAssociatedWithId

`func (o *ContactsApiGetContactResponse) GetAssociatedWithId() string`

GetAssociatedWithId returns the AssociatedWithId field if non-nil, zero value otherwise.

### GetAssociatedWithIdOk

`func (o *ContactsApiGetContactResponse) GetAssociatedWithIdOk() (*string, bool)`

GetAssociatedWithIdOk returns a tuple with the AssociatedWithId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssociatedWithId

`func (o *ContactsApiGetContactResponse) SetAssociatedWithId(v string)`

SetAssociatedWithId sets AssociatedWithId field to given value.

### HasAssociatedWithId

`func (o *ContactsApiGetContactResponse) HasAssociatedWithId() bool`

HasAssociatedWithId returns a boolean if a field has been set.

### GetModifiedById

`func (o *ContactsApiGetContactResponse) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *ContactsApiGetContactResponse) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *ContactsApiGetContactResponse) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *ContactsApiGetContactResponse) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetModifiedDate

`func (o *ContactsApiGetContactResponse) GetModifiedDate() time.Time`

GetModifiedDate returns the ModifiedDate field if non-nil, zero value otherwise.

### GetModifiedDateOk

`func (o *ContactsApiGetContactResponse) GetModifiedDateOk() (*time.Time, bool)`

GetModifiedDateOk returns a tuple with the ModifiedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDate

`func (o *ContactsApiGetContactResponse) SetModifiedDate(v time.Time)`

SetModifiedDate sets ModifiedDate field to given value.

### HasModifiedDate

`func (o *ContactsApiGetContactResponse) HasModifiedDate() bool`

HasModifiedDate returns a boolean if a field has been set.

### GetCreatedById

`func (o *ContactsApiGetContactResponse) GetCreatedById() string`

GetCreatedById returns the CreatedById field if non-nil, zero value otherwise.

### GetCreatedByIdOk

`func (o *ContactsApiGetContactResponse) GetCreatedByIdOk() (*string, bool)`

GetCreatedByIdOk returns a tuple with the CreatedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedById

`func (o *ContactsApiGetContactResponse) SetCreatedById(v string)`

SetCreatedById sets CreatedById field to given value.

### HasCreatedById

`func (o *ContactsApiGetContactResponse) HasCreatedById() bool`

HasCreatedById returns a boolean if a field has been set.

### GetCreatedDate

`func (o *ContactsApiGetContactResponse) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *ContactsApiGetContactResponse) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *ContactsApiGetContactResponse) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *ContactsApiGetContactResponse) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


