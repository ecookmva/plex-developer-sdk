# JustInSequenceApiGetJISKitResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | The ID of the sequenced kit. | [optional] 
**RackId** | Pointer to **string** | The ID of the sequenced rack. | [optional] 
**JiSKitStatus** | Pointer to **string** | The sequenced kit&#39;s status. | [optional] 
**PackOrder** | Pointer to **int32** | The kit&#39;s pack order. | [optional] 
**KitName** | Pointer to **string** | The sequenced kit&#39;s name. | [optional] 
**IsReprintNeeded** | Pointer to **bool** | Determines whether the kit requires its paperwork to be reprinted. | [optional] 
**CreatedById** | Pointer to **string** | The account ID of the user who created the kit. | [optional] 
**CreatedDateTime** | Pointer to **time.Time** | The date and time on which the kit was created. | [optional] 
**ModifiedById** | Pointer to **string** | The account ID of the user who last modified the kit. | [optional] 
**ModifiedDateTime** | Pointer to **time.Time** | The date and time on which the kit was modified. | [optional] 
**PrintedById** | Pointer to **string** | The accound ID of the user who printed the kit paperwork. | [optional] 
**PrintedDateTime** | Pointer to **time.Time** | The date and time on which the kit paperwork was printed. | [optional] 
**PackedById** | Pointer to **string** | The account ID of the user who packed the kit. | [optional] 
**PackedDateTime** | Pointer to **time.Time** | The date and time on which the kit was packed. | [optional] 
**UnpackedById** | Pointer to **string** | The account ID of the user who unpacked the kit. | [optional] 
**UnpackedDateTime** | Pointer to **time.Time** | The date and time on which the kit was unpacked. | [optional] 
**RackSequenceNumber** | Pointer to **string** | The kit&#39;s rack number. | [optional] 
**LabelPrintedById** | Pointer to **string** | The account ID of the user who last printed the kit label. | [optional] 
**LabelPrintedDateTime** | Pointer to **time.Time** | The date and time on which the kit label was last printed. | [optional] 
**RackCellName** | Pointer to **string** | The cell name on the rack (if a physical rack structure is defined). | [optional] 

## Methods

### NewJustInSequenceApiGetJISKitResponse

`func NewJustInSequenceApiGetJISKitResponse() *JustInSequenceApiGetJISKitResponse`

NewJustInSequenceApiGetJISKitResponse instantiates a new JustInSequenceApiGetJISKitResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewJustInSequenceApiGetJISKitResponseWithDefaults

`func NewJustInSequenceApiGetJISKitResponseWithDefaults() *JustInSequenceApiGetJISKitResponse`

NewJustInSequenceApiGetJISKitResponseWithDefaults instantiates a new JustInSequenceApiGetJISKitResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *JustInSequenceApiGetJISKitResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *JustInSequenceApiGetJISKitResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *JustInSequenceApiGetJISKitResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *JustInSequenceApiGetJISKitResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetRackId

`func (o *JustInSequenceApiGetJISKitResponse) GetRackId() string`

GetRackId returns the RackId field if non-nil, zero value otherwise.

### GetRackIdOk

`func (o *JustInSequenceApiGetJISKitResponse) GetRackIdOk() (*string, bool)`

GetRackIdOk returns a tuple with the RackId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRackId

`func (o *JustInSequenceApiGetJISKitResponse) SetRackId(v string)`

SetRackId sets RackId field to given value.

### HasRackId

`func (o *JustInSequenceApiGetJISKitResponse) HasRackId() bool`

HasRackId returns a boolean if a field has been set.

### GetJiSKitStatus

`func (o *JustInSequenceApiGetJISKitResponse) GetJiSKitStatus() string`

GetJiSKitStatus returns the JiSKitStatus field if non-nil, zero value otherwise.

### GetJiSKitStatusOk

`func (o *JustInSequenceApiGetJISKitResponse) GetJiSKitStatusOk() (*string, bool)`

GetJiSKitStatusOk returns a tuple with the JiSKitStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJiSKitStatus

`func (o *JustInSequenceApiGetJISKitResponse) SetJiSKitStatus(v string)`

SetJiSKitStatus sets JiSKitStatus field to given value.

### HasJiSKitStatus

`func (o *JustInSequenceApiGetJISKitResponse) HasJiSKitStatus() bool`

HasJiSKitStatus returns a boolean if a field has been set.

### GetPackOrder

`func (o *JustInSequenceApiGetJISKitResponse) GetPackOrder() int32`

GetPackOrder returns the PackOrder field if non-nil, zero value otherwise.

### GetPackOrderOk

`func (o *JustInSequenceApiGetJISKitResponse) GetPackOrderOk() (*int32, bool)`

GetPackOrderOk returns a tuple with the PackOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackOrder

`func (o *JustInSequenceApiGetJISKitResponse) SetPackOrder(v int32)`

SetPackOrder sets PackOrder field to given value.

### HasPackOrder

`func (o *JustInSequenceApiGetJISKitResponse) HasPackOrder() bool`

HasPackOrder returns a boolean if a field has been set.

### GetKitName

`func (o *JustInSequenceApiGetJISKitResponse) GetKitName() string`

GetKitName returns the KitName field if non-nil, zero value otherwise.

### GetKitNameOk

`func (o *JustInSequenceApiGetJISKitResponse) GetKitNameOk() (*string, bool)`

GetKitNameOk returns a tuple with the KitName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKitName

`func (o *JustInSequenceApiGetJISKitResponse) SetKitName(v string)`

SetKitName sets KitName field to given value.

### HasKitName

`func (o *JustInSequenceApiGetJISKitResponse) HasKitName() bool`

HasKitName returns a boolean if a field has been set.

### GetIsReprintNeeded

`func (o *JustInSequenceApiGetJISKitResponse) GetIsReprintNeeded() bool`

GetIsReprintNeeded returns the IsReprintNeeded field if non-nil, zero value otherwise.

### GetIsReprintNeededOk

`func (o *JustInSequenceApiGetJISKitResponse) GetIsReprintNeededOk() (*bool, bool)`

GetIsReprintNeededOk returns a tuple with the IsReprintNeeded field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsReprintNeeded

`func (o *JustInSequenceApiGetJISKitResponse) SetIsReprintNeeded(v bool)`

SetIsReprintNeeded sets IsReprintNeeded field to given value.

### HasIsReprintNeeded

`func (o *JustInSequenceApiGetJISKitResponse) HasIsReprintNeeded() bool`

HasIsReprintNeeded returns a boolean if a field has been set.

### GetCreatedById

`func (o *JustInSequenceApiGetJISKitResponse) GetCreatedById() string`

GetCreatedById returns the CreatedById field if non-nil, zero value otherwise.

### GetCreatedByIdOk

`func (o *JustInSequenceApiGetJISKitResponse) GetCreatedByIdOk() (*string, bool)`

GetCreatedByIdOk returns a tuple with the CreatedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedById

`func (o *JustInSequenceApiGetJISKitResponse) SetCreatedById(v string)`

SetCreatedById sets CreatedById field to given value.

### HasCreatedById

`func (o *JustInSequenceApiGetJISKitResponse) HasCreatedById() bool`

HasCreatedById returns a boolean if a field has been set.

### GetCreatedDateTime

`func (o *JustInSequenceApiGetJISKitResponse) GetCreatedDateTime() time.Time`

GetCreatedDateTime returns the CreatedDateTime field if non-nil, zero value otherwise.

### GetCreatedDateTimeOk

`func (o *JustInSequenceApiGetJISKitResponse) GetCreatedDateTimeOk() (*time.Time, bool)`

GetCreatedDateTimeOk returns a tuple with the CreatedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDateTime

`func (o *JustInSequenceApiGetJISKitResponse) SetCreatedDateTime(v time.Time)`

SetCreatedDateTime sets CreatedDateTime field to given value.

### HasCreatedDateTime

`func (o *JustInSequenceApiGetJISKitResponse) HasCreatedDateTime() bool`

HasCreatedDateTime returns a boolean if a field has been set.

### GetModifiedById

`func (o *JustInSequenceApiGetJISKitResponse) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *JustInSequenceApiGetJISKitResponse) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *JustInSequenceApiGetJISKitResponse) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *JustInSequenceApiGetJISKitResponse) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetModifiedDateTime

`func (o *JustInSequenceApiGetJISKitResponse) GetModifiedDateTime() time.Time`

GetModifiedDateTime returns the ModifiedDateTime field if non-nil, zero value otherwise.

### GetModifiedDateTimeOk

`func (o *JustInSequenceApiGetJISKitResponse) GetModifiedDateTimeOk() (*time.Time, bool)`

GetModifiedDateTimeOk returns a tuple with the ModifiedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDateTime

`func (o *JustInSequenceApiGetJISKitResponse) SetModifiedDateTime(v time.Time)`

SetModifiedDateTime sets ModifiedDateTime field to given value.

### HasModifiedDateTime

`func (o *JustInSequenceApiGetJISKitResponse) HasModifiedDateTime() bool`

HasModifiedDateTime returns a boolean if a field has been set.

### GetPrintedById

`func (o *JustInSequenceApiGetJISKitResponse) GetPrintedById() string`

GetPrintedById returns the PrintedById field if non-nil, zero value otherwise.

### GetPrintedByIdOk

`func (o *JustInSequenceApiGetJISKitResponse) GetPrintedByIdOk() (*string, bool)`

GetPrintedByIdOk returns a tuple with the PrintedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrintedById

`func (o *JustInSequenceApiGetJISKitResponse) SetPrintedById(v string)`

SetPrintedById sets PrintedById field to given value.

### HasPrintedById

`func (o *JustInSequenceApiGetJISKitResponse) HasPrintedById() bool`

HasPrintedById returns a boolean if a field has been set.

### GetPrintedDateTime

`func (o *JustInSequenceApiGetJISKitResponse) GetPrintedDateTime() time.Time`

GetPrintedDateTime returns the PrintedDateTime field if non-nil, zero value otherwise.

### GetPrintedDateTimeOk

`func (o *JustInSequenceApiGetJISKitResponse) GetPrintedDateTimeOk() (*time.Time, bool)`

GetPrintedDateTimeOk returns a tuple with the PrintedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrintedDateTime

`func (o *JustInSequenceApiGetJISKitResponse) SetPrintedDateTime(v time.Time)`

SetPrintedDateTime sets PrintedDateTime field to given value.

### HasPrintedDateTime

`func (o *JustInSequenceApiGetJISKitResponse) HasPrintedDateTime() bool`

HasPrintedDateTime returns a boolean if a field has been set.

### GetPackedById

`func (o *JustInSequenceApiGetJISKitResponse) GetPackedById() string`

GetPackedById returns the PackedById field if non-nil, zero value otherwise.

### GetPackedByIdOk

`func (o *JustInSequenceApiGetJISKitResponse) GetPackedByIdOk() (*string, bool)`

GetPackedByIdOk returns a tuple with the PackedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackedById

`func (o *JustInSequenceApiGetJISKitResponse) SetPackedById(v string)`

SetPackedById sets PackedById field to given value.

### HasPackedById

`func (o *JustInSequenceApiGetJISKitResponse) HasPackedById() bool`

HasPackedById returns a boolean if a field has been set.

### GetPackedDateTime

`func (o *JustInSequenceApiGetJISKitResponse) GetPackedDateTime() time.Time`

GetPackedDateTime returns the PackedDateTime field if non-nil, zero value otherwise.

### GetPackedDateTimeOk

`func (o *JustInSequenceApiGetJISKitResponse) GetPackedDateTimeOk() (*time.Time, bool)`

GetPackedDateTimeOk returns a tuple with the PackedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackedDateTime

`func (o *JustInSequenceApiGetJISKitResponse) SetPackedDateTime(v time.Time)`

SetPackedDateTime sets PackedDateTime field to given value.

### HasPackedDateTime

`func (o *JustInSequenceApiGetJISKitResponse) HasPackedDateTime() bool`

HasPackedDateTime returns a boolean if a field has been set.

### GetUnpackedById

`func (o *JustInSequenceApiGetJISKitResponse) GetUnpackedById() string`

GetUnpackedById returns the UnpackedById field if non-nil, zero value otherwise.

### GetUnpackedByIdOk

`func (o *JustInSequenceApiGetJISKitResponse) GetUnpackedByIdOk() (*string, bool)`

GetUnpackedByIdOk returns a tuple with the UnpackedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnpackedById

`func (o *JustInSequenceApiGetJISKitResponse) SetUnpackedById(v string)`

SetUnpackedById sets UnpackedById field to given value.

### HasUnpackedById

`func (o *JustInSequenceApiGetJISKitResponse) HasUnpackedById() bool`

HasUnpackedById returns a boolean if a field has been set.

### GetUnpackedDateTime

`func (o *JustInSequenceApiGetJISKitResponse) GetUnpackedDateTime() time.Time`

GetUnpackedDateTime returns the UnpackedDateTime field if non-nil, zero value otherwise.

### GetUnpackedDateTimeOk

`func (o *JustInSequenceApiGetJISKitResponse) GetUnpackedDateTimeOk() (*time.Time, bool)`

GetUnpackedDateTimeOk returns a tuple with the UnpackedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnpackedDateTime

`func (o *JustInSequenceApiGetJISKitResponse) SetUnpackedDateTime(v time.Time)`

SetUnpackedDateTime sets UnpackedDateTime field to given value.

### HasUnpackedDateTime

`func (o *JustInSequenceApiGetJISKitResponse) HasUnpackedDateTime() bool`

HasUnpackedDateTime returns a boolean if a field has been set.

### GetRackSequenceNumber

`func (o *JustInSequenceApiGetJISKitResponse) GetRackSequenceNumber() string`

GetRackSequenceNumber returns the RackSequenceNumber field if non-nil, zero value otherwise.

### GetRackSequenceNumberOk

`func (o *JustInSequenceApiGetJISKitResponse) GetRackSequenceNumberOk() (*string, bool)`

GetRackSequenceNumberOk returns a tuple with the RackSequenceNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRackSequenceNumber

`func (o *JustInSequenceApiGetJISKitResponse) SetRackSequenceNumber(v string)`

SetRackSequenceNumber sets RackSequenceNumber field to given value.

### HasRackSequenceNumber

`func (o *JustInSequenceApiGetJISKitResponse) HasRackSequenceNumber() bool`

HasRackSequenceNumber returns a boolean if a field has been set.

### GetLabelPrintedById

`func (o *JustInSequenceApiGetJISKitResponse) GetLabelPrintedById() string`

GetLabelPrintedById returns the LabelPrintedById field if non-nil, zero value otherwise.

### GetLabelPrintedByIdOk

`func (o *JustInSequenceApiGetJISKitResponse) GetLabelPrintedByIdOk() (*string, bool)`

GetLabelPrintedByIdOk returns a tuple with the LabelPrintedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabelPrintedById

`func (o *JustInSequenceApiGetJISKitResponse) SetLabelPrintedById(v string)`

SetLabelPrintedById sets LabelPrintedById field to given value.

### HasLabelPrintedById

`func (o *JustInSequenceApiGetJISKitResponse) HasLabelPrintedById() bool`

HasLabelPrintedById returns a boolean if a field has been set.

### GetLabelPrintedDateTime

`func (o *JustInSequenceApiGetJISKitResponse) GetLabelPrintedDateTime() time.Time`

GetLabelPrintedDateTime returns the LabelPrintedDateTime field if non-nil, zero value otherwise.

### GetLabelPrintedDateTimeOk

`func (o *JustInSequenceApiGetJISKitResponse) GetLabelPrintedDateTimeOk() (*time.Time, bool)`

GetLabelPrintedDateTimeOk returns a tuple with the LabelPrintedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabelPrintedDateTime

`func (o *JustInSequenceApiGetJISKitResponse) SetLabelPrintedDateTime(v time.Time)`

SetLabelPrintedDateTime sets LabelPrintedDateTime field to given value.

### HasLabelPrintedDateTime

`func (o *JustInSequenceApiGetJISKitResponse) HasLabelPrintedDateTime() bool`

HasLabelPrintedDateTime returns a boolean if a field has been set.

### GetRackCellName

`func (o *JustInSequenceApiGetJISKitResponse) GetRackCellName() string`

GetRackCellName returns the RackCellName field if non-nil, zero value otherwise.

### GetRackCellNameOk

`func (o *JustInSequenceApiGetJISKitResponse) GetRackCellNameOk() (*string, bool)`

GetRackCellNameOk returns a tuple with the RackCellName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRackCellName

`func (o *JustInSequenceApiGetJISKitResponse) SetRackCellName(v string)`

SetRackCellName sets RackCellName field to given value.

### HasRackCellName

`func (o *JustInSequenceApiGetJISKitResponse) HasRackCellName() bool`

HasRackCellName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


