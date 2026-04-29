# JustInSequenceApiListJISKitsItem

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

### NewJustInSequenceApiListJISKitsItem

`func NewJustInSequenceApiListJISKitsItem() *JustInSequenceApiListJISKitsItem`

NewJustInSequenceApiListJISKitsItem instantiates a new JustInSequenceApiListJISKitsItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewJustInSequenceApiListJISKitsItemWithDefaults

`func NewJustInSequenceApiListJISKitsItemWithDefaults() *JustInSequenceApiListJISKitsItem`

NewJustInSequenceApiListJISKitsItemWithDefaults instantiates a new JustInSequenceApiListJISKitsItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *JustInSequenceApiListJISKitsItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *JustInSequenceApiListJISKitsItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *JustInSequenceApiListJISKitsItem) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *JustInSequenceApiListJISKitsItem) HasId() bool`

HasId returns a boolean if a field has been set.

### GetRackId

`func (o *JustInSequenceApiListJISKitsItem) GetRackId() string`

GetRackId returns the RackId field if non-nil, zero value otherwise.

### GetRackIdOk

`func (o *JustInSequenceApiListJISKitsItem) GetRackIdOk() (*string, bool)`

GetRackIdOk returns a tuple with the RackId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRackId

`func (o *JustInSequenceApiListJISKitsItem) SetRackId(v string)`

SetRackId sets RackId field to given value.

### HasRackId

`func (o *JustInSequenceApiListJISKitsItem) HasRackId() bool`

HasRackId returns a boolean if a field has been set.

### GetJiSKitStatus

`func (o *JustInSequenceApiListJISKitsItem) GetJiSKitStatus() string`

GetJiSKitStatus returns the JiSKitStatus field if non-nil, zero value otherwise.

### GetJiSKitStatusOk

`func (o *JustInSequenceApiListJISKitsItem) GetJiSKitStatusOk() (*string, bool)`

GetJiSKitStatusOk returns a tuple with the JiSKitStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJiSKitStatus

`func (o *JustInSequenceApiListJISKitsItem) SetJiSKitStatus(v string)`

SetJiSKitStatus sets JiSKitStatus field to given value.

### HasJiSKitStatus

`func (o *JustInSequenceApiListJISKitsItem) HasJiSKitStatus() bool`

HasJiSKitStatus returns a boolean if a field has been set.

### GetPackOrder

`func (o *JustInSequenceApiListJISKitsItem) GetPackOrder() int32`

GetPackOrder returns the PackOrder field if non-nil, zero value otherwise.

### GetPackOrderOk

`func (o *JustInSequenceApiListJISKitsItem) GetPackOrderOk() (*int32, bool)`

GetPackOrderOk returns a tuple with the PackOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackOrder

`func (o *JustInSequenceApiListJISKitsItem) SetPackOrder(v int32)`

SetPackOrder sets PackOrder field to given value.

### HasPackOrder

`func (o *JustInSequenceApiListJISKitsItem) HasPackOrder() bool`

HasPackOrder returns a boolean if a field has been set.

### GetKitName

`func (o *JustInSequenceApiListJISKitsItem) GetKitName() string`

GetKitName returns the KitName field if non-nil, zero value otherwise.

### GetKitNameOk

`func (o *JustInSequenceApiListJISKitsItem) GetKitNameOk() (*string, bool)`

GetKitNameOk returns a tuple with the KitName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKitName

`func (o *JustInSequenceApiListJISKitsItem) SetKitName(v string)`

SetKitName sets KitName field to given value.

### HasKitName

`func (o *JustInSequenceApiListJISKitsItem) HasKitName() bool`

HasKitName returns a boolean if a field has been set.

### GetIsReprintNeeded

`func (o *JustInSequenceApiListJISKitsItem) GetIsReprintNeeded() bool`

GetIsReprintNeeded returns the IsReprintNeeded field if non-nil, zero value otherwise.

### GetIsReprintNeededOk

`func (o *JustInSequenceApiListJISKitsItem) GetIsReprintNeededOk() (*bool, bool)`

GetIsReprintNeededOk returns a tuple with the IsReprintNeeded field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsReprintNeeded

`func (o *JustInSequenceApiListJISKitsItem) SetIsReprintNeeded(v bool)`

SetIsReprintNeeded sets IsReprintNeeded field to given value.

### HasIsReprintNeeded

`func (o *JustInSequenceApiListJISKitsItem) HasIsReprintNeeded() bool`

HasIsReprintNeeded returns a boolean if a field has been set.

### GetCreatedById

`func (o *JustInSequenceApiListJISKitsItem) GetCreatedById() string`

GetCreatedById returns the CreatedById field if non-nil, zero value otherwise.

### GetCreatedByIdOk

`func (o *JustInSequenceApiListJISKitsItem) GetCreatedByIdOk() (*string, bool)`

GetCreatedByIdOk returns a tuple with the CreatedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedById

`func (o *JustInSequenceApiListJISKitsItem) SetCreatedById(v string)`

SetCreatedById sets CreatedById field to given value.

### HasCreatedById

`func (o *JustInSequenceApiListJISKitsItem) HasCreatedById() bool`

HasCreatedById returns a boolean if a field has been set.

### GetCreatedDateTime

`func (o *JustInSequenceApiListJISKitsItem) GetCreatedDateTime() time.Time`

GetCreatedDateTime returns the CreatedDateTime field if non-nil, zero value otherwise.

### GetCreatedDateTimeOk

`func (o *JustInSequenceApiListJISKitsItem) GetCreatedDateTimeOk() (*time.Time, bool)`

GetCreatedDateTimeOk returns a tuple with the CreatedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDateTime

`func (o *JustInSequenceApiListJISKitsItem) SetCreatedDateTime(v time.Time)`

SetCreatedDateTime sets CreatedDateTime field to given value.

### HasCreatedDateTime

`func (o *JustInSequenceApiListJISKitsItem) HasCreatedDateTime() bool`

HasCreatedDateTime returns a boolean if a field has been set.

### GetModifiedById

`func (o *JustInSequenceApiListJISKitsItem) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *JustInSequenceApiListJISKitsItem) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *JustInSequenceApiListJISKitsItem) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *JustInSequenceApiListJISKitsItem) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetModifiedDateTime

`func (o *JustInSequenceApiListJISKitsItem) GetModifiedDateTime() time.Time`

GetModifiedDateTime returns the ModifiedDateTime field if non-nil, zero value otherwise.

### GetModifiedDateTimeOk

`func (o *JustInSequenceApiListJISKitsItem) GetModifiedDateTimeOk() (*time.Time, bool)`

GetModifiedDateTimeOk returns a tuple with the ModifiedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDateTime

`func (o *JustInSequenceApiListJISKitsItem) SetModifiedDateTime(v time.Time)`

SetModifiedDateTime sets ModifiedDateTime field to given value.

### HasModifiedDateTime

`func (o *JustInSequenceApiListJISKitsItem) HasModifiedDateTime() bool`

HasModifiedDateTime returns a boolean if a field has been set.

### GetPrintedById

`func (o *JustInSequenceApiListJISKitsItem) GetPrintedById() string`

GetPrintedById returns the PrintedById field if non-nil, zero value otherwise.

### GetPrintedByIdOk

`func (o *JustInSequenceApiListJISKitsItem) GetPrintedByIdOk() (*string, bool)`

GetPrintedByIdOk returns a tuple with the PrintedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrintedById

`func (o *JustInSequenceApiListJISKitsItem) SetPrintedById(v string)`

SetPrintedById sets PrintedById field to given value.

### HasPrintedById

`func (o *JustInSequenceApiListJISKitsItem) HasPrintedById() bool`

HasPrintedById returns a boolean if a field has been set.

### GetPrintedDateTime

`func (o *JustInSequenceApiListJISKitsItem) GetPrintedDateTime() time.Time`

GetPrintedDateTime returns the PrintedDateTime field if non-nil, zero value otherwise.

### GetPrintedDateTimeOk

`func (o *JustInSequenceApiListJISKitsItem) GetPrintedDateTimeOk() (*time.Time, bool)`

GetPrintedDateTimeOk returns a tuple with the PrintedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrintedDateTime

`func (o *JustInSequenceApiListJISKitsItem) SetPrintedDateTime(v time.Time)`

SetPrintedDateTime sets PrintedDateTime field to given value.

### HasPrintedDateTime

`func (o *JustInSequenceApiListJISKitsItem) HasPrintedDateTime() bool`

HasPrintedDateTime returns a boolean if a field has been set.

### GetPackedById

`func (o *JustInSequenceApiListJISKitsItem) GetPackedById() string`

GetPackedById returns the PackedById field if non-nil, zero value otherwise.

### GetPackedByIdOk

`func (o *JustInSequenceApiListJISKitsItem) GetPackedByIdOk() (*string, bool)`

GetPackedByIdOk returns a tuple with the PackedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackedById

`func (o *JustInSequenceApiListJISKitsItem) SetPackedById(v string)`

SetPackedById sets PackedById field to given value.

### HasPackedById

`func (o *JustInSequenceApiListJISKitsItem) HasPackedById() bool`

HasPackedById returns a boolean if a field has been set.

### GetPackedDateTime

`func (o *JustInSequenceApiListJISKitsItem) GetPackedDateTime() time.Time`

GetPackedDateTime returns the PackedDateTime field if non-nil, zero value otherwise.

### GetPackedDateTimeOk

`func (o *JustInSequenceApiListJISKitsItem) GetPackedDateTimeOk() (*time.Time, bool)`

GetPackedDateTimeOk returns a tuple with the PackedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackedDateTime

`func (o *JustInSequenceApiListJISKitsItem) SetPackedDateTime(v time.Time)`

SetPackedDateTime sets PackedDateTime field to given value.

### HasPackedDateTime

`func (o *JustInSequenceApiListJISKitsItem) HasPackedDateTime() bool`

HasPackedDateTime returns a boolean if a field has been set.

### GetUnpackedById

`func (o *JustInSequenceApiListJISKitsItem) GetUnpackedById() string`

GetUnpackedById returns the UnpackedById field if non-nil, zero value otherwise.

### GetUnpackedByIdOk

`func (o *JustInSequenceApiListJISKitsItem) GetUnpackedByIdOk() (*string, bool)`

GetUnpackedByIdOk returns a tuple with the UnpackedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnpackedById

`func (o *JustInSequenceApiListJISKitsItem) SetUnpackedById(v string)`

SetUnpackedById sets UnpackedById field to given value.

### HasUnpackedById

`func (o *JustInSequenceApiListJISKitsItem) HasUnpackedById() bool`

HasUnpackedById returns a boolean if a field has been set.

### GetUnpackedDateTime

`func (o *JustInSequenceApiListJISKitsItem) GetUnpackedDateTime() time.Time`

GetUnpackedDateTime returns the UnpackedDateTime field if non-nil, zero value otherwise.

### GetUnpackedDateTimeOk

`func (o *JustInSequenceApiListJISKitsItem) GetUnpackedDateTimeOk() (*time.Time, bool)`

GetUnpackedDateTimeOk returns a tuple with the UnpackedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnpackedDateTime

`func (o *JustInSequenceApiListJISKitsItem) SetUnpackedDateTime(v time.Time)`

SetUnpackedDateTime sets UnpackedDateTime field to given value.

### HasUnpackedDateTime

`func (o *JustInSequenceApiListJISKitsItem) HasUnpackedDateTime() bool`

HasUnpackedDateTime returns a boolean if a field has been set.

### GetRackSequenceNumber

`func (o *JustInSequenceApiListJISKitsItem) GetRackSequenceNumber() string`

GetRackSequenceNumber returns the RackSequenceNumber field if non-nil, zero value otherwise.

### GetRackSequenceNumberOk

`func (o *JustInSequenceApiListJISKitsItem) GetRackSequenceNumberOk() (*string, bool)`

GetRackSequenceNumberOk returns a tuple with the RackSequenceNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRackSequenceNumber

`func (o *JustInSequenceApiListJISKitsItem) SetRackSequenceNumber(v string)`

SetRackSequenceNumber sets RackSequenceNumber field to given value.

### HasRackSequenceNumber

`func (o *JustInSequenceApiListJISKitsItem) HasRackSequenceNumber() bool`

HasRackSequenceNumber returns a boolean if a field has been set.

### GetLabelPrintedById

`func (o *JustInSequenceApiListJISKitsItem) GetLabelPrintedById() string`

GetLabelPrintedById returns the LabelPrintedById field if non-nil, zero value otherwise.

### GetLabelPrintedByIdOk

`func (o *JustInSequenceApiListJISKitsItem) GetLabelPrintedByIdOk() (*string, bool)`

GetLabelPrintedByIdOk returns a tuple with the LabelPrintedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabelPrintedById

`func (o *JustInSequenceApiListJISKitsItem) SetLabelPrintedById(v string)`

SetLabelPrintedById sets LabelPrintedById field to given value.

### HasLabelPrintedById

`func (o *JustInSequenceApiListJISKitsItem) HasLabelPrintedById() bool`

HasLabelPrintedById returns a boolean if a field has been set.

### GetLabelPrintedDateTime

`func (o *JustInSequenceApiListJISKitsItem) GetLabelPrintedDateTime() time.Time`

GetLabelPrintedDateTime returns the LabelPrintedDateTime field if non-nil, zero value otherwise.

### GetLabelPrintedDateTimeOk

`func (o *JustInSequenceApiListJISKitsItem) GetLabelPrintedDateTimeOk() (*time.Time, bool)`

GetLabelPrintedDateTimeOk returns a tuple with the LabelPrintedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabelPrintedDateTime

`func (o *JustInSequenceApiListJISKitsItem) SetLabelPrintedDateTime(v time.Time)`

SetLabelPrintedDateTime sets LabelPrintedDateTime field to given value.

### HasLabelPrintedDateTime

`func (o *JustInSequenceApiListJISKitsItem) HasLabelPrintedDateTime() bool`

HasLabelPrintedDateTime returns a boolean if a field has been set.

### GetRackCellName

`func (o *JustInSequenceApiListJISKitsItem) GetRackCellName() string`

GetRackCellName returns the RackCellName field if non-nil, zero value otherwise.

### GetRackCellNameOk

`func (o *JustInSequenceApiListJISKitsItem) GetRackCellNameOk() (*string, bool)`

GetRackCellNameOk returns a tuple with the RackCellName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRackCellName

`func (o *JustInSequenceApiListJISKitsItem) SetRackCellName(v string)`

SetRackCellName sets RackCellName field to given value.

### HasRackCellName

`func (o *JustInSequenceApiListJISKitsItem) HasRackCellName() bool`

HasRackCellName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


