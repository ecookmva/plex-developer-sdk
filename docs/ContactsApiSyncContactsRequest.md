# ContactsApiSyncContactsRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | A unique identifier for the Contact. This will be automatically generated if omitted from the request. | [optional] 
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

## Methods

### NewContactsApiSyncContactsRequest

`func NewContactsApiSyncContactsRequest() *ContactsApiSyncContactsRequest`

NewContactsApiSyncContactsRequest instantiates a new ContactsApiSyncContactsRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContactsApiSyncContactsRequestWithDefaults

`func NewContactsApiSyncContactsRequestWithDefaults() *ContactsApiSyncContactsRequest`

NewContactsApiSyncContactsRequestWithDefaults instantiates a new ContactsApiSyncContactsRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ContactsApiSyncContactsRequest) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ContactsApiSyncContactsRequest) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ContactsApiSyncContactsRequest) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *ContactsApiSyncContactsRequest) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCustomerId

`func (o *ContactsApiSyncContactsRequest) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *ContactsApiSyncContactsRequest) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *ContactsApiSyncContactsRequest) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *ContactsApiSyncContactsRequest) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### GetFirstName

`func (o *ContactsApiSyncContactsRequest) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *ContactsApiSyncContactsRequest) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *ContactsApiSyncContactsRequest) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.

### HasFirstName

`func (o *ContactsApiSyncContactsRequest) HasFirstName() bool`

HasFirstName returns a boolean if a field has been set.

### GetLastName

`func (o *ContactsApiSyncContactsRequest) GetLastName() string`

GetLastName returns the LastName field if non-nil, zero value otherwise.

### GetLastNameOk

`func (o *ContactsApiSyncContactsRequest) GetLastNameOk() (*string, bool)`

GetLastNameOk returns a tuple with the LastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastName

`func (o *ContactsApiSyncContactsRequest) SetLastName(v string)`

SetLastName sets LastName field to given value.

### HasLastName

`func (o *ContactsApiSyncContactsRequest) HasLastName() bool`

HasLastName returns a boolean if a field has been set.

### GetSupplierId

`func (o *ContactsApiSyncContactsRequest) GetSupplierId() string`

GetSupplierId returns the SupplierId field if non-nil, zero value otherwise.

### GetSupplierIdOk

`func (o *ContactsApiSyncContactsRequest) GetSupplierIdOk() (*string, bool)`

GetSupplierIdOk returns a tuple with the SupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierId

`func (o *ContactsApiSyncContactsRequest) SetSupplierId(v string)`

SetSupplierId sets SupplierId field to given value.

### HasSupplierId

`func (o *ContactsApiSyncContactsRequest) HasSupplierId() bool`

HasSupplierId returns a boolean if a field has been set.

### GetPhone

`func (o *ContactsApiSyncContactsRequest) GetPhone() string`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *ContactsApiSyncContactsRequest) GetPhoneOk() (*string, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *ContactsApiSyncContactsRequest) SetPhone(v string)`

SetPhone sets Phone field to given value.

### HasPhone

`func (o *ContactsApiSyncContactsRequest) HasPhone() bool`

HasPhone returns a boolean if a field has been set.

### GetFax

`func (o *ContactsApiSyncContactsRequest) GetFax() string`

GetFax returns the Fax field if non-nil, zero value otherwise.

### GetFaxOk

`func (o *ContactsApiSyncContactsRequest) GetFaxOk() (*string, bool)`

GetFaxOk returns a tuple with the Fax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFax

`func (o *ContactsApiSyncContactsRequest) SetFax(v string)`

SetFax sets Fax field to given value.

### HasFax

`func (o *ContactsApiSyncContactsRequest) HasFax() bool`

HasFax returns a boolean if a field has been set.

### GetMobilePhone

`func (o *ContactsApiSyncContactsRequest) GetMobilePhone() string`

GetMobilePhone returns the MobilePhone field if non-nil, zero value otherwise.

### GetMobilePhoneOk

`func (o *ContactsApiSyncContactsRequest) GetMobilePhoneOk() (*string, bool)`

GetMobilePhoneOk returns a tuple with the MobilePhone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMobilePhone

`func (o *ContactsApiSyncContactsRequest) SetMobilePhone(v string)`

SetMobilePhone sets MobilePhone field to given value.

### HasMobilePhone

`func (o *ContactsApiSyncContactsRequest) HasMobilePhone() bool`

HasMobilePhone returns a boolean if a field has been set.

### GetTitle

`func (o *ContactsApiSyncContactsRequest) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *ContactsApiSyncContactsRequest) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *ContactsApiSyncContactsRequest) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *ContactsApiSyncContactsRequest) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### GetNote

`func (o *ContactsApiSyncContactsRequest) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *ContactsApiSyncContactsRequest) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *ContactsApiSyncContactsRequest) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *ContactsApiSyncContactsRequest) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetEmail

`func (o *ContactsApiSyncContactsRequest) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *ContactsApiSyncContactsRequest) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *ContactsApiSyncContactsRequest) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *ContactsApiSyncContactsRequest) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetCompanyName

`func (o *ContactsApiSyncContactsRequest) GetCompanyName() string`

GetCompanyName returns the CompanyName field if non-nil, zero value otherwise.

### GetCompanyNameOk

`func (o *ContactsApiSyncContactsRequest) GetCompanyNameOk() (*string, bool)`

GetCompanyNameOk returns a tuple with the CompanyName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompanyName

`func (o *ContactsApiSyncContactsRequest) SetCompanyName(v string)`

SetCompanyName sets CompanyName field to given value.

### HasCompanyName

`func (o *ContactsApiSyncContactsRequest) HasCompanyName() bool`

HasCompanyName returns a boolean if a field has been set.

### GetOfficeAddress

`func (o *ContactsApiSyncContactsRequest) GetOfficeAddress() string`

GetOfficeAddress returns the OfficeAddress field if non-nil, zero value otherwise.

### GetOfficeAddressOk

`func (o *ContactsApiSyncContactsRequest) GetOfficeAddressOk() (*string, bool)`

GetOfficeAddressOk returns a tuple with the OfficeAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOfficeAddress

`func (o *ContactsApiSyncContactsRequest) SetOfficeAddress(v string)`

SetOfficeAddress sets OfficeAddress field to given value.

### HasOfficeAddress

`func (o *ContactsApiSyncContactsRequest) HasOfficeAddress() bool`

HasOfficeAddress returns a boolean if a field has been set.

### GetHomeAddress

`func (o *ContactsApiSyncContactsRequest) GetHomeAddress() string`

GetHomeAddress returns the HomeAddress field if non-nil, zero value otherwise.

### GetHomeAddressOk

`func (o *ContactsApiSyncContactsRequest) GetHomeAddressOk() (*string, bool)`

GetHomeAddressOk returns a tuple with the HomeAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHomeAddress

`func (o *ContactsApiSyncContactsRequest) SetHomeAddress(v string)`

SetHomeAddress sets HomeAddress field to given value.

### HasHomeAddress

`func (o *ContactsApiSyncContactsRequest) HasHomeAddress() bool`

HasHomeAddress returns a boolean if a field has been set.

### GetPrivate

`func (o *ContactsApiSyncContactsRequest) GetPrivate() int32`

GetPrivate returns the Private field if non-nil, zero value otherwise.

### GetPrivateOk

`func (o *ContactsApiSyncContactsRequest) GetPrivateOk() (*int32, bool)`

GetPrivateOk returns a tuple with the Private field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrivate

`func (o *ContactsApiSyncContactsRequest) SetPrivate(v int32)`

SetPrivate sets Private field to given value.

### HasPrivate

`func (o *ContactsApiSyncContactsRequest) HasPrivate() bool`

HasPrivate returns a boolean if a field has been set.

### GetDescription

`func (o *ContactsApiSyncContactsRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ContactsApiSyncContactsRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ContactsApiSyncContactsRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ContactsApiSyncContactsRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetBirthDate

`func (o *ContactsApiSyncContactsRequest) GetBirthDate() time.Time`

GetBirthDate returns the BirthDate field if non-nil, zero value otherwise.

### GetBirthDateOk

`func (o *ContactsApiSyncContactsRequest) GetBirthDateOk() (*time.Time, bool)`

GetBirthDateOk returns a tuple with the BirthDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBirthDate

`func (o *ContactsApiSyncContactsRequest) SetBirthDate(v time.Time)`

SetBirthDate sets BirthDate field to given value.

### HasBirthDate

`func (o *ContactsApiSyncContactsRequest) HasBirthDate() bool`

HasBirthDate returns a boolean if a field has been set.

### GetUrl

`func (o *ContactsApiSyncContactsRequest) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *ContactsApiSyncContactsRequest) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *ContactsApiSyncContactsRequest) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *ContactsApiSyncContactsRequest) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### GetSortOrder

`func (o *ContactsApiSyncContactsRequest) GetSortOrder() int32`

GetSortOrder returns the SortOrder field if non-nil, zero value otherwise.

### GetSortOrderOk

`func (o *ContactsApiSyncContactsRequest) GetSortOrderOk() (*int32, bool)`

GetSortOrderOk returns a tuple with the SortOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSortOrder

`func (o *ContactsApiSyncContactsRequest) SetSortOrder(v int32)`

SetSortOrder sets SortOrder field to given value.

### HasSortOrder

`func (o *ContactsApiSyncContactsRequest) HasSortOrder() bool`

HasSortOrder returns a boolean if a field has been set.

### GetType

`func (o *ContactsApiSyncContactsRequest) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ContactsApiSyncContactsRequest) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ContactsApiSyncContactsRequest) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *ContactsApiSyncContactsRequest) HasType() bool`

HasType returns a boolean if a field has been set.

### GetAssociatedWithId

`func (o *ContactsApiSyncContactsRequest) GetAssociatedWithId() string`

GetAssociatedWithId returns the AssociatedWithId field if non-nil, zero value otherwise.

### GetAssociatedWithIdOk

`func (o *ContactsApiSyncContactsRequest) GetAssociatedWithIdOk() (*string, bool)`

GetAssociatedWithIdOk returns a tuple with the AssociatedWithId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssociatedWithId

`func (o *ContactsApiSyncContactsRequest) SetAssociatedWithId(v string)`

SetAssociatedWithId sets AssociatedWithId field to given value.

### HasAssociatedWithId

`func (o *ContactsApiSyncContactsRequest) HasAssociatedWithId() bool`

HasAssociatedWithId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


