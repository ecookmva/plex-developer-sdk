# JustInSequenceApiGetJISReleaseResponse

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

### NewJustInSequenceApiGetJISReleaseResponse

`func NewJustInSequenceApiGetJISReleaseResponse() *JustInSequenceApiGetJISReleaseResponse`

NewJustInSequenceApiGetJISReleaseResponse instantiates a new JustInSequenceApiGetJISReleaseResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewJustInSequenceApiGetJISReleaseResponseWithDefaults

`func NewJustInSequenceApiGetJISReleaseResponseWithDefaults() *JustInSequenceApiGetJISReleaseResponse`

NewJustInSequenceApiGetJISReleaseResponseWithDefaults instantiates a new JustInSequenceApiGetJISReleaseResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *JustInSequenceApiGetJISReleaseResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *JustInSequenceApiGetJISReleaseResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *JustInSequenceApiGetJISReleaseResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *JustInSequenceApiGetJISReleaseResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetSalesReleaseNumber

`func (o *JustInSequenceApiGetJISReleaseResponse) GetSalesReleaseNumber() string`

GetSalesReleaseNumber returns the SalesReleaseNumber field if non-nil, zero value otherwise.

### GetSalesReleaseNumberOk

`func (o *JustInSequenceApiGetJISReleaseResponse) GetSalesReleaseNumberOk() (*string, bool)`

GetSalesReleaseNumberOk returns a tuple with the SalesReleaseNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSalesReleaseNumber

`func (o *JustInSequenceApiGetJISReleaseResponse) SetSalesReleaseNumber(v string)`

SetSalesReleaseNumber sets SalesReleaseNumber field to given value.

### HasSalesReleaseNumber

`func (o *JustInSequenceApiGetJISReleaseResponse) HasSalesReleaseNumber() bool`

HasSalesReleaseNumber returns a boolean if a field has been set.

### GetReleaseStatus

`func (o *JustInSequenceApiGetJISReleaseResponse) GetReleaseStatus() string`

GetReleaseStatus returns the ReleaseStatus field if non-nil, zero value otherwise.

### GetReleaseStatusOk

`func (o *JustInSequenceApiGetJISReleaseResponse) GetReleaseStatusOk() (*string, bool)`

GetReleaseStatusOk returns a tuple with the ReleaseStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleaseStatus

`func (o *JustInSequenceApiGetJISReleaseResponse) SetReleaseStatus(v string)`

SetReleaseStatus sets ReleaseStatus field to given value.

### HasReleaseStatus

`func (o *JustInSequenceApiGetJISReleaseResponse) HasReleaseStatus() bool`

HasReleaseStatus returns a boolean if a field has been set.

### GetSalesReleaseId

`func (o *JustInSequenceApiGetJISReleaseResponse) GetSalesReleaseId() string`

GetSalesReleaseId returns the SalesReleaseId field if non-nil, zero value otherwise.

### GetSalesReleaseIdOk

`func (o *JustInSequenceApiGetJISReleaseResponse) GetSalesReleaseIdOk() (*string, bool)`

GetSalesReleaseIdOk returns a tuple with the SalesReleaseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSalesReleaseId

`func (o *JustInSequenceApiGetJISReleaseResponse) SetSalesReleaseId(v string)`

SetSalesReleaseId sets SalesReleaseId field to given value.

### HasSalesReleaseId

`func (o *JustInSequenceApiGetJISReleaseResponse) HasSalesReleaseId() bool`

HasSalesReleaseId returns a boolean if a field has been set.

### GetKitId

`func (o *JustInSequenceApiGetJISReleaseResponse) GetKitId() string`

GetKitId returns the KitId field if non-nil, zero value otherwise.

### GetKitIdOk

`func (o *JustInSequenceApiGetJISReleaseResponse) GetKitIdOk() (*string, bool)`

GetKitIdOk returns a tuple with the KitId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKitId

`func (o *JustInSequenceApiGetJISReleaseResponse) SetKitId(v string)`

SetKitId sets KitId field to given value.

### HasKitId

`func (o *JustInSequenceApiGetJISReleaseResponse) HasKitId() bool`

HasKitId returns a boolean if a field has been set.

### GetKitName

`func (o *JustInSequenceApiGetJISReleaseResponse) GetKitName() string`

GetKitName returns the KitName field if non-nil, zero value otherwise.

### GetKitNameOk

`func (o *JustInSequenceApiGetJISReleaseResponse) GetKitNameOk() (*string, bool)`

GetKitNameOk returns a tuple with the KitName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKitName

`func (o *JustInSequenceApiGetJISReleaseResponse) SetKitName(v string)`

SetKitName sets KitName field to given value.

### HasKitName

`func (o *JustInSequenceApiGetJISReleaseResponse) HasKitName() bool`

HasKitName returns a boolean if a field has been set.

### GetCreatedById

`func (o *JustInSequenceApiGetJISReleaseResponse) GetCreatedById() string`

GetCreatedById returns the CreatedById field if non-nil, zero value otherwise.

### GetCreatedByIdOk

`func (o *JustInSequenceApiGetJISReleaseResponse) GetCreatedByIdOk() (*string, bool)`

GetCreatedByIdOk returns a tuple with the CreatedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedById

`func (o *JustInSequenceApiGetJISReleaseResponse) SetCreatedById(v string)`

SetCreatedById sets CreatedById field to given value.

### HasCreatedById

`func (o *JustInSequenceApiGetJISReleaseResponse) HasCreatedById() bool`

HasCreatedById returns a boolean if a field has been set.

### GetCreatedDateTime

`func (o *JustInSequenceApiGetJISReleaseResponse) GetCreatedDateTime() time.Time`

GetCreatedDateTime returns the CreatedDateTime field if non-nil, zero value otherwise.

### GetCreatedDateTimeOk

`func (o *JustInSequenceApiGetJISReleaseResponse) GetCreatedDateTimeOk() (*time.Time, bool)`

GetCreatedDateTimeOk returns a tuple with the CreatedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDateTime

`func (o *JustInSequenceApiGetJISReleaseResponse) SetCreatedDateTime(v time.Time)`

SetCreatedDateTime sets CreatedDateTime field to given value.

### HasCreatedDateTime

`func (o *JustInSequenceApiGetJISReleaseResponse) HasCreatedDateTime() bool`

HasCreatedDateTime returns a boolean if a field has been set.

### GetModifiedById

`func (o *JustInSequenceApiGetJISReleaseResponse) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *JustInSequenceApiGetJISReleaseResponse) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *JustInSequenceApiGetJISReleaseResponse) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *JustInSequenceApiGetJISReleaseResponse) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetModifiedDateTime

`func (o *JustInSequenceApiGetJISReleaseResponse) GetModifiedDateTime() time.Time`

GetModifiedDateTime returns the ModifiedDateTime field if non-nil, zero value otherwise.

### GetModifiedDateTimeOk

`func (o *JustInSequenceApiGetJISReleaseResponse) GetModifiedDateTimeOk() (*time.Time, bool)`

GetModifiedDateTimeOk returns a tuple with the ModifiedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDateTime

`func (o *JustInSequenceApiGetJISReleaseResponse) SetModifiedDateTime(v time.Time)`

SetModifiedDateTime sets ModifiedDateTime field to given value.

### HasModifiedDateTime

`func (o *JustInSequenceApiGetJISReleaseResponse) HasModifiedDateTime() bool`

HasModifiedDateTime returns a boolean if a field has been set.

### GetPackedById

`func (o *JustInSequenceApiGetJISReleaseResponse) GetPackedById() string`

GetPackedById returns the PackedById field if non-nil, zero value otherwise.

### GetPackedByIdOk

`func (o *JustInSequenceApiGetJISReleaseResponse) GetPackedByIdOk() (*string, bool)`

GetPackedByIdOk returns a tuple with the PackedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackedById

`func (o *JustInSequenceApiGetJISReleaseResponse) SetPackedById(v string)`

SetPackedById sets PackedById field to given value.

### HasPackedById

`func (o *JustInSequenceApiGetJISReleaseResponse) HasPackedById() bool`

HasPackedById returns a boolean if a field has been set.

### GetPackedDateTime

`func (o *JustInSequenceApiGetJISReleaseResponse) GetPackedDateTime() time.Time`

GetPackedDateTime returns the PackedDateTime field if non-nil, zero value otherwise.

### GetPackedDateTimeOk

`func (o *JustInSequenceApiGetJISReleaseResponse) GetPackedDateTimeOk() (*time.Time, bool)`

GetPackedDateTimeOk returns a tuple with the PackedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackedDateTime

`func (o *JustInSequenceApiGetJISReleaseResponse) SetPackedDateTime(v time.Time)`

SetPackedDateTime sets PackedDateTime field to given value.

### HasPackedDateTime

`func (o *JustInSequenceApiGetJISReleaseResponse) HasPackedDateTime() bool`

HasPackedDateTime returns a boolean if a field has been set.

### GetUnPackedById

`func (o *JustInSequenceApiGetJISReleaseResponse) GetUnPackedById() string`

GetUnPackedById returns the UnPackedById field if non-nil, zero value otherwise.

### GetUnPackedByIdOk

`func (o *JustInSequenceApiGetJISReleaseResponse) GetUnPackedByIdOk() (*string, bool)`

GetUnPackedByIdOk returns a tuple with the UnPackedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnPackedById

`func (o *JustInSequenceApiGetJISReleaseResponse) SetUnPackedById(v string)`

SetUnPackedById sets UnPackedById field to given value.

### HasUnPackedById

`func (o *JustInSequenceApiGetJISReleaseResponse) HasUnPackedById() bool`

HasUnPackedById returns a boolean if a field has been set.

### GetUnPackedDateTime

`func (o *JustInSequenceApiGetJISReleaseResponse) GetUnPackedDateTime() time.Time`

GetUnPackedDateTime returns the UnPackedDateTime field if non-nil, zero value otherwise.

### GetUnPackedDateTimeOk

`func (o *JustInSequenceApiGetJISReleaseResponse) GetUnPackedDateTimeOk() (*time.Time, bool)`

GetUnPackedDateTimeOk returns a tuple with the UnPackedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnPackedDateTime

`func (o *JustInSequenceApiGetJISReleaseResponse) SetUnPackedDateTime(v time.Time)`

SetUnPackedDateTime sets UnPackedDateTime field to given value.

### HasUnPackedDateTime

`func (o *JustInSequenceApiGetJISReleaseResponse) HasUnPackedDateTime() bool`

HasUnPackedDateTime returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


