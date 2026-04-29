# JustInSequenceApiListJISReleasesItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | A unique identifier for the sequenced release. | [optional] 
**SalesReleaseNumber** | Pointer to **string** | The sales release number. | [optional] 
**ReleaseStatus** | Pointer to **string** | The status assigned to the sequenced release. | [optional] 
**SalesReleaseId** | Pointer to **string** | A unique identifier for the sales release. | [optional] 
**KitId** | Pointer to **string** | A unique identifier for the kit. | [optional] 
**KitName** | Pointer to **string** | The kit name. | [optional] 
**CreatedById** | Pointer to **string** | The user account ID that created the release. | [optional] 
**CreatedDateTime** | Pointer to **time.Time** | The date and time on which the release was created. | [optional] 
**ModifiedById** | Pointer to **string** | The user account ID that last modified the release record. | [optional] 
**ModifiedDateTime** | Pointer to **time.Time** | The date and time on which the release record was modified. | [optional] 
**PackedById** | Pointer to **string** | The account ID of the user who packed the release. | [optional] 
**PackedDateTime** | Pointer to **time.Time** | The date and time on which the release was packed. | [optional] 
**UnPackedById** | Pointer to **string** | The account ID of the user who unpacked the release. | [optional] 
**UnPackedDateTime** | Pointer to **time.Time** | The date and time on which the release was unpacked. | [optional] 

## Methods

### NewJustInSequenceApiListJISReleasesItem

`func NewJustInSequenceApiListJISReleasesItem() *JustInSequenceApiListJISReleasesItem`

NewJustInSequenceApiListJISReleasesItem instantiates a new JustInSequenceApiListJISReleasesItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewJustInSequenceApiListJISReleasesItemWithDefaults

`func NewJustInSequenceApiListJISReleasesItemWithDefaults() *JustInSequenceApiListJISReleasesItem`

NewJustInSequenceApiListJISReleasesItemWithDefaults instantiates a new JustInSequenceApiListJISReleasesItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *JustInSequenceApiListJISReleasesItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *JustInSequenceApiListJISReleasesItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *JustInSequenceApiListJISReleasesItem) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *JustInSequenceApiListJISReleasesItem) HasId() bool`

HasId returns a boolean if a field has been set.

### GetSalesReleaseNumber

`func (o *JustInSequenceApiListJISReleasesItem) GetSalesReleaseNumber() string`

GetSalesReleaseNumber returns the SalesReleaseNumber field if non-nil, zero value otherwise.

### GetSalesReleaseNumberOk

`func (o *JustInSequenceApiListJISReleasesItem) GetSalesReleaseNumberOk() (*string, bool)`

GetSalesReleaseNumberOk returns a tuple with the SalesReleaseNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSalesReleaseNumber

`func (o *JustInSequenceApiListJISReleasesItem) SetSalesReleaseNumber(v string)`

SetSalesReleaseNumber sets SalesReleaseNumber field to given value.

### HasSalesReleaseNumber

`func (o *JustInSequenceApiListJISReleasesItem) HasSalesReleaseNumber() bool`

HasSalesReleaseNumber returns a boolean if a field has been set.

### GetReleaseStatus

`func (o *JustInSequenceApiListJISReleasesItem) GetReleaseStatus() string`

GetReleaseStatus returns the ReleaseStatus field if non-nil, zero value otherwise.

### GetReleaseStatusOk

`func (o *JustInSequenceApiListJISReleasesItem) GetReleaseStatusOk() (*string, bool)`

GetReleaseStatusOk returns a tuple with the ReleaseStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleaseStatus

`func (o *JustInSequenceApiListJISReleasesItem) SetReleaseStatus(v string)`

SetReleaseStatus sets ReleaseStatus field to given value.

### HasReleaseStatus

`func (o *JustInSequenceApiListJISReleasesItem) HasReleaseStatus() bool`

HasReleaseStatus returns a boolean if a field has been set.

### GetSalesReleaseId

`func (o *JustInSequenceApiListJISReleasesItem) GetSalesReleaseId() string`

GetSalesReleaseId returns the SalesReleaseId field if non-nil, zero value otherwise.

### GetSalesReleaseIdOk

`func (o *JustInSequenceApiListJISReleasesItem) GetSalesReleaseIdOk() (*string, bool)`

GetSalesReleaseIdOk returns a tuple with the SalesReleaseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSalesReleaseId

`func (o *JustInSequenceApiListJISReleasesItem) SetSalesReleaseId(v string)`

SetSalesReleaseId sets SalesReleaseId field to given value.

### HasSalesReleaseId

`func (o *JustInSequenceApiListJISReleasesItem) HasSalesReleaseId() bool`

HasSalesReleaseId returns a boolean if a field has been set.

### GetKitId

`func (o *JustInSequenceApiListJISReleasesItem) GetKitId() string`

GetKitId returns the KitId field if non-nil, zero value otherwise.

### GetKitIdOk

`func (o *JustInSequenceApiListJISReleasesItem) GetKitIdOk() (*string, bool)`

GetKitIdOk returns a tuple with the KitId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKitId

`func (o *JustInSequenceApiListJISReleasesItem) SetKitId(v string)`

SetKitId sets KitId field to given value.

### HasKitId

`func (o *JustInSequenceApiListJISReleasesItem) HasKitId() bool`

HasKitId returns a boolean if a field has been set.

### GetKitName

`func (o *JustInSequenceApiListJISReleasesItem) GetKitName() string`

GetKitName returns the KitName field if non-nil, zero value otherwise.

### GetKitNameOk

`func (o *JustInSequenceApiListJISReleasesItem) GetKitNameOk() (*string, bool)`

GetKitNameOk returns a tuple with the KitName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKitName

`func (o *JustInSequenceApiListJISReleasesItem) SetKitName(v string)`

SetKitName sets KitName field to given value.

### HasKitName

`func (o *JustInSequenceApiListJISReleasesItem) HasKitName() bool`

HasKitName returns a boolean if a field has been set.

### GetCreatedById

`func (o *JustInSequenceApiListJISReleasesItem) GetCreatedById() string`

GetCreatedById returns the CreatedById field if non-nil, zero value otherwise.

### GetCreatedByIdOk

`func (o *JustInSequenceApiListJISReleasesItem) GetCreatedByIdOk() (*string, bool)`

GetCreatedByIdOk returns a tuple with the CreatedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedById

`func (o *JustInSequenceApiListJISReleasesItem) SetCreatedById(v string)`

SetCreatedById sets CreatedById field to given value.

### HasCreatedById

`func (o *JustInSequenceApiListJISReleasesItem) HasCreatedById() bool`

HasCreatedById returns a boolean if a field has been set.

### GetCreatedDateTime

`func (o *JustInSequenceApiListJISReleasesItem) GetCreatedDateTime() time.Time`

GetCreatedDateTime returns the CreatedDateTime field if non-nil, zero value otherwise.

### GetCreatedDateTimeOk

`func (o *JustInSequenceApiListJISReleasesItem) GetCreatedDateTimeOk() (*time.Time, bool)`

GetCreatedDateTimeOk returns a tuple with the CreatedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDateTime

`func (o *JustInSequenceApiListJISReleasesItem) SetCreatedDateTime(v time.Time)`

SetCreatedDateTime sets CreatedDateTime field to given value.

### HasCreatedDateTime

`func (o *JustInSequenceApiListJISReleasesItem) HasCreatedDateTime() bool`

HasCreatedDateTime returns a boolean if a field has been set.

### GetModifiedById

`func (o *JustInSequenceApiListJISReleasesItem) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *JustInSequenceApiListJISReleasesItem) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *JustInSequenceApiListJISReleasesItem) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *JustInSequenceApiListJISReleasesItem) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetModifiedDateTime

`func (o *JustInSequenceApiListJISReleasesItem) GetModifiedDateTime() time.Time`

GetModifiedDateTime returns the ModifiedDateTime field if non-nil, zero value otherwise.

### GetModifiedDateTimeOk

`func (o *JustInSequenceApiListJISReleasesItem) GetModifiedDateTimeOk() (*time.Time, bool)`

GetModifiedDateTimeOk returns a tuple with the ModifiedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDateTime

`func (o *JustInSequenceApiListJISReleasesItem) SetModifiedDateTime(v time.Time)`

SetModifiedDateTime sets ModifiedDateTime field to given value.

### HasModifiedDateTime

`func (o *JustInSequenceApiListJISReleasesItem) HasModifiedDateTime() bool`

HasModifiedDateTime returns a boolean if a field has been set.

### GetPackedById

`func (o *JustInSequenceApiListJISReleasesItem) GetPackedById() string`

GetPackedById returns the PackedById field if non-nil, zero value otherwise.

### GetPackedByIdOk

`func (o *JustInSequenceApiListJISReleasesItem) GetPackedByIdOk() (*string, bool)`

GetPackedByIdOk returns a tuple with the PackedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackedById

`func (o *JustInSequenceApiListJISReleasesItem) SetPackedById(v string)`

SetPackedById sets PackedById field to given value.

### HasPackedById

`func (o *JustInSequenceApiListJISReleasesItem) HasPackedById() bool`

HasPackedById returns a boolean if a field has been set.

### GetPackedDateTime

`func (o *JustInSequenceApiListJISReleasesItem) GetPackedDateTime() time.Time`

GetPackedDateTime returns the PackedDateTime field if non-nil, zero value otherwise.

### GetPackedDateTimeOk

`func (o *JustInSequenceApiListJISReleasesItem) GetPackedDateTimeOk() (*time.Time, bool)`

GetPackedDateTimeOk returns a tuple with the PackedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackedDateTime

`func (o *JustInSequenceApiListJISReleasesItem) SetPackedDateTime(v time.Time)`

SetPackedDateTime sets PackedDateTime field to given value.

### HasPackedDateTime

`func (o *JustInSequenceApiListJISReleasesItem) HasPackedDateTime() bool`

HasPackedDateTime returns a boolean if a field has been set.

### GetUnPackedById

`func (o *JustInSequenceApiListJISReleasesItem) GetUnPackedById() string`

GetUnPackedById returns the UnPackedById field if non-nil, zero value otherwise.

### GetUnPackedByIdOk

`func (o *JustInSequenceApiListJISReleasesItem) GetUnPackedByIdOk() (*string, bool)`

GetUnPackedByIdOk returns a tuple with the UnPackedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnPackedById

`func (o *JustInSequenceApiListJISReleasesItem) SetUnPackedById(v string)`

SetUnPackedById sets UnPackedById field to given value.

### HasUnPackedById

`func (o *JustInSequenceApiListJISReleasesItem) HasUnPackedById() bool`

HasUnPackedById returns a boolean if a field has been set.

### GetUnPackedDateTime

`func (o *JustInSequenceApiListJISReleasesItem) GetUnPackedDateTime() time.Time`

GetUnPackedDateTime returns the UnPackedDateTime field if non-nil, zero value otherwise.

### GetUnPackedDateTimeOk

`func (o *JustInSequenceApiListJISReleasesItem) GetUnPackedDateTimeOk() (*time.Time, bool)`

GetUnPackedDateTimeOk returns a tuple with the UnPackedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnPackedDateTime

`func (o *JustInSequenceApiListJISReleasesItem) SetUnPackedDateTime(v time.Time)`

SetUnPackedDateTime sets UnPackedDateTime field to given value.

### HasUnPackedDateTime

`func (o *JustInSequenceApiListJISReleasesItem) HasUnPackedDateTime() bool`

HasUnPackedDateTime returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


