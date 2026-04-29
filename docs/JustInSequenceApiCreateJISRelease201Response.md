# JustInSequenceApiCreateJISRelease201Response

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

### NewJustInSequenceApiCreateJISRelease201Response

`func NewJustInSequenceApiCreateJISRelease201Response() *JustInSequenceApiCreateJISRelease201Response`

NewJustInSequenceApiCreateJISRelease201Response instantiates a new JustInSequenceApiCreateJISRelease201Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewJustInSequenceApiCreateJISRelease201ResponseWithDefaults

`func NewJustInSequenceApiCreateJISRelease201ResponseWithDefaults() *JustInSequenceApiCreateJISRelease201Response`

NewJustInSequenceApiCreateJISRelease201ResponseWithDefaults instantiates a new JustInSequenceApiCreateJISRelease201Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *JustInSequenceApiCreateJISRelease201Response) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *JustInSequenceApiCreateJISRelease201Response) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *JustInSequenceApiCreateJISRelease201Response) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *JustInSequenceApiCreateJISRelease201Response) HasId() bool`

HasId returns a boolean if a field has been set.

### GetSalesReleaseNumber

`func (o *JustInSequenceApiCreateJISRelease201Response) GetSalesReleaseNumber() string`

GetSalesReleaseNumber returns the SalesReleaseNumber field if non-nil, zero value otherwise.

### GetSalesReleaseNumberOk

`func (o *JustInSequenceApiCreateJISRelease201Response) GetSalesReleaseNumberOk() (*string, bool)`

GetSalesReleaseNumberOk returns a tuple with the SalesReleaseNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSalesReleaseNumber

`func (o *JustInSequenceApiCreateJISRelease201Response) SetSalesReleaseNumber(v string)`

SetSalesReleaseNumber sets SalesReleaseNumber field to given value.

### HasSalesReleaseNumber

`func (o *JustInSequenceApiCreateJISRelease201Response) HasSalesReleaseNumber() bool`

HasSalesReleaseNumber returns a boolean if a field has been set.

### GetReleaseStatus

`func (o *JustInSequenceApiCreateJISRelease201Response) GetReleaseStatus() string`

GetReleaseStatus returns the ReleaseStatus field if non-nil, zero value otherwise.

### GetReleaseStatusOk

`func (o *JustInSequenceApiCreateJISRelease201Response) GetReleaseStatusOk() (*string, bool)`

GetReleaseStatusOk returns a tuple with the ReleaseStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleaseStatus

`func (o *JustInSequenceApiCreateJISRelease201Response) SetReleaseStatus(v string)`

SetReleaseStatus sets ReleaseStatus field to given value.

### HasReleaseStatus

`func (o *JustInSequenceApiCreateJISRelease201Response) HasReleaseStatus() bool`

HasReleaseStatus returns a boolean if a field has been set.

### GetSalesReleaseId

`func (o *JustInSequenceApiCreateJISRelease201Response) GetSalesReleaseId() string`

GetSalesReleaseId returns the SalesReleaseId field if non-nil, zero value otherwise.

### GetSalesReleaseIdOk

`func (o *JustInSequenceApiCreateJISRelease201Response) GetSalesReleaseIdOk() (*string, bool)`

GetSalesReleaseIdOk returns a tuple with the SalesReleaseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSalesReleaseId

`func (o *JustInSequenceApiCreateJISRelease201Response) SetSalesReleaseId(v string)`

SetSalesReleaseId sets SalesReleaseId field to given value.

### HasSalesReleaseId

`func (o *JustInSequenceApiCreateJISRelease201Response) HasSalesReleaseId() bool`

HasSalesReleaseId returns a boolean if a field has been set.

### GetKitId

`func (o *JustInSequenceApiCreateJISRelease201Response) GetKitId() string`

GetKitId returns the KitId field if non-nil, zero value otherwise.

### GetKitIdOk

`func (o *JustInSequenceApiCreateJISRelease201Response) GetKitIdOk() (*string, bool)`

GetKitIdOk returns a tuple with the KitId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKitId

`func (o *JustInSequenceApiCreateJISRelease201Response) SetKitId(v string)`

SetKitId sets KitId field to given value.

### HasKitId

`func (o *JustInSequenceApiCreateJISRelease201Response) HasKitId() bool`

HasKitId returns a boolean if a field has been set.

### GetKitName

`func (o *JustInSequenceApiCreateJISRelease201Response) GetKitName() string`

GetKitName returns the KitName field if non-nil, zero value otherwise.

### GetKitNameOk

`func (o *JustInSequenceApiCreateJISRelease201Response) GetKitNameOk() (*string, bool)`

GetKitNameOk returns a tuple with the KitName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKitName

`func (o *JustInSequenceApiCreateJISRelease201Response) SetKitName(v string)`

SetKitName sets KitName field to given value.

### HasKitName

`func (o *JustInSequenceApiCreateJISRelease201Response) HasKitName() bool`

HasKitName returns a boolean if a field has been set.

### GetCreatedById

`func (o *JustInSequenceApiCreateJISRelease201Response) GetCreatedById() string`

GetCreatedById returns the CreatedById field if non-nil, zero value otherwise.

### GetCreatedByIdOk

`func (o *JustInSequenceApiCreateJISRelease201Response) GetCreatedByIdOk() (*string, bool)`

GetCreatedByIdOk returns a tuple with the CreatedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedById

`func (o *JustInSequenceApiCreateJISRelease201Response) SetCreatedById(v string)`

SetCreatedById sets CreatedById field to given value.

### HasCreatedById

`func (o *JustInSequenceApiCreateJISRelease201Response) HasCreatedById() bool`

HasCreatedById returns a boolean if a field has been set.

### GetCreatedDateTime

`func (o *JustInSequenceApiCreateJISRelease201Response) GetCreatedDateTime() time.Time`

GetCreatedDateTime returns the CreatedDateTime field if non-nil, zero value otherwise.

### GetCreatedDateTimeOk

`func (o *JustInSequenceApiCreateJISRelease201Response) GetCreatedDateTimeOk() (*time.Time, bool)`

GetCreatedDateTimeOk returns a tuple with the CreatedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDateTime

`func (o *JustInSequenceApiCreateJISRelease201Response) SetCreatedDateTime(v time.Time)`

SetCreatedDateTime sets CreatedDateTime field to given value.

### HasCreatedDateTime

`func (o *JustInSequenceApiCreateJISRelease201Response) HasCreatedDateTime() bool`

HasCreatedDateTime returns a boolean if a field has been set.

### GetModifiedById

`func (o *JustInSequenceApiCreateJISRelease201Response) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *JustInSequenceApiCreateJISRelease201Response) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *JustInSequenceApiCreateJISRelease201Response) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *JustInSequenceApiCreateJISRelease201Response) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetModifiedDateTime

`func (o *JustInSequenceApiCreateJISRelease201Response) GetModifiedDateTime() time.Time`

GetModifiedDateTime returns the ModifiedDateTime field if non-nil, zero value otherwise.

### GetModifiedDateTimeOk

`func (o *JustInSequenceApiCreateJISRelease201Response) GetModifiedDateTimeOk() (*time.Time, bool)`

GetModifiedDateTimeOk returns a tuple with the ModifiedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDateTime

`func (o *JustInSequenceApiCreateJISRelease201Response) SetModifiedDateTime(v time.Time)`

SetModifiedDateTime sets ModifiedDateTime field to given value.

### HasModifiedDateTime

`func (o *JustInSequenceApiCreateJISRelease201Response) HasModifiedDateTime() bool`

HasModifiedDateTime returns a boolean if a field has been set.

### GetPackedById

`func (o *JustInSequenceApiCreateJISRelease201Response) GetPackedById() string`

GetPackedById returns the PackedById field if non-nil, zero value otherwise.

### GetPackedByIdOk

`func (o *JustInSequenceApiCreateJISRelease201Response) GetPackedByIdOk() (*string, bool)`

GetPackedByIdOk returns a tuple with the PackedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackedById

`func (o *JustInSequenceApiCreateJISRelease201Response) SetPackedById(v string)`

SetPackedById sets PackedById field to given value.

### HasPackedById

`func (o *JustInSequenceApiCreateJISRelease201Response) HasPackedById() bool`

HasPackedById returns a boolean if a field has been set.

### GetPackedDateTime

`func (o *JustInSequenceApiCreateJISRelease201Response) GetPackedDateTime() time.Time`

GetPackedDateTime returns the PackedDateTime field if non-nil, zero value otherwise.

### GetPackedDateTimeOk

`func (o *JustInSequenceApiCreateJISRelease201Response) GetPackedDateTimeOk() (*time.Time, bool)`

GetPackedDateTimeOk returns a tuple with the PackedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackedDateTime

`func (o *JustInSequenceApiCreateJISRelease201Response) SetPackedDateTime(v time.Time)`

SetPackedDateTime sets PackedDateTime field to given value.

### HasPackedDateTime

`func (o *JustInSequenceApiCreateJISRelease201Response) HasPackedDateTime() bool`

HasPackedDateTime returns a boolean if a field has been set.

### GetUnPackedById

`func (o *JustInSequenceApiCreateJISRelease201Response) GetUnPackedById() string`

GetUnPackedById returns the UnPackedById field if non-nil, zero value otherwise.

### GetUnPackedByIdOk

`func (o *JustInSequenceApiCreateJISRelease201Response) GetUnPackedByIdOk() (*string, bool)`

GetUnPackedByIdOk returns a tuple with the UnPackedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnPackedById

`func (o *JustInSequenceApiCreateJISRelease201Response) SetUnPackedById(v string)`

SetUnPackedById sets UnPackedById field to given value.

### HasUnPackedById

`func (o *JustInSequenceApiCreateJISRelease201Response) HasUnPackedById() bool`

HasUnPackedById returns a boolean if a field has been set.

### GetUnPackedDateTime

`func (o *JustInSequenceApiCreateJISRelease201Response) GetUnPackedDateTime() time.Time`

GetUnPackedDateTime returns the UnPackedDateTime field if non-nil, zero value otherwise.

### GetUnPackedDateTimeOk

`func (o *JustInSequenceApiCreateJISRelease201Response) GetUnPackedDateTimeOk() (*time.Time, bool)`

GetUnPackedDateTimeOk returns a tuple with the UnPackedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnPackedDateTime

`func (o *JustInSequenceApiCreateJISRelease201Response) SetUnPackedDateTime(v time.Time)`

SetUnPackedDateTime sets UnPackedDateTime field to given value.

### HasUnPackedDateTime

`func (o *JustInSequenceApiCreateJISRelease201Response) HasUnPackedDateTime() bool`

HasUnPackedDateTime returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


