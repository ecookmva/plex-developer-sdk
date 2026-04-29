# JustInSequenceApiCreateJISKit201Response

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

### NewJustInSequenceApiCreateJISKit201Response

`func NewJustInSequenceApiCreateJISKit201Response() *JustInSequenceApiCreateJISKit201Response`

NewJustInSequenceApiCreateJISKit201Response instantiates a new JustInSequenceApiCreateJISKit201Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewJustInSequenceApiCreateJISKit201ResponseWithDefaults

`func NewJustInSequenceApiCreateJISKit201ResponseWithDefaults() *JustInSequenceApiCreateJISKit201Response`

NewJustInSequenceApiCreateJISKit201ResponseWithDefaults instantiates a new JustInSequenceApiCreateJISKit201Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *JustInSequenceApiCreateJISKit201Response) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *JustInSequenceApiCreateJISKit201Response) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *JustInSequenceApiCreateJISKit201Response) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *JustInSequenceApiCreateJISKit201Response) HasId() bool`

HasId returns a boolean if a field has been set.

### GetRackId

`func (o *JustInSequenceApiCreateJISKit201Response) GetRackId() string`

GetRackId returns the RackId field if non-nil, zero value otherwise.

### GetRackIdOk

`func (o *JustInSequenceApiCreateJISKit201Response) GetRackIdOk() (*string, bool)`

GetRackIdOk returns a tuple with the RackId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRackId

`func (o *JustInSequenceApiCreateJISKit201Response) SetRackId(v string)`

SetRackId sets RackId field to given value.

### HasRackId

`func (o *JustInSequenceApiCreateJISKit201Response) HasRackId() bool`

HasRackId returns a boolean if a field has been set.

### GetJiSKitStatus

`func (o *JustInSequenceApiCreateJISKit201Response) GetJiSKitStatus() string`

GetJiSKitStatus returns the JiSKitStatus field if non-nil, zero value otherwise.

### GetJiSKitStatusOk

`func (o *JustInSequenceApiCreateJISKit201Response) GetJiSKitStatusOk() (*string, bool)`

GetJiSKitStatusOk returns a tuple with the JiSKitStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJiSKitStatus

`func (o *JustInSequenceApiCreateJISKit201Response) SetJiSKitStatus(v string)`

SetJiSKitStatus sets JiSKitStatus field to given value.

### HasJiSKitStatus

`func (o *JustInSequenceApiCreateJISKit201Response) HasJiSKitStatus() bool`

HasJiSKitStatus returns a boolean if a field has been set.

### GetPackOrder

`func (o *JustInSequenceApiCreateJISKit201Response) GetPackOrder() int32`

GetPackOrder returns the PackOrder field if non-nil, zero value otherwise.

### GetPackOrderOk

`func (o *JustInSequenceApiCreateJISKit201Response) GetPackOrderOk() (*int32, bool)`

GetPackOrderOk returns a tuple with the PackOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackOrder

`func (o *JustInSequenceApiCreateJISKit201Response) SetPackOrder(v int32)`

SetPackOrder sets PackOrder field to given value.

### HasPackOrder

`func (o *JustInSequenceApiCreateJISKit201Response) HasPackOrder() bool`

HasPackOrder returns a boolean if a field has been set.

### GetKitName

`func (o *JustInSequenceApiCreateJISKit201Response) GetKitName() string`

GetKitName returns the KitName field if non-nil, zero value otherwise.

### GetKitNameOk

`func (o *JustInSequenceApiCreateJISKit201Response) GetKitNameOk() (*string, bool)`

GetKitNameOk returns a tuple with the KitName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKitName

`func (o *JustInSequenceApiCreateJISKit201Response) SetKitName(v string)`

SetKitName sets KitName field to given value.

### HasKitName

`func (o *JustInSequenceApiCreateJISKit201Response) HasKitName() bool`

HasKitName returns a boolean if a field has been set.

### GetIsReprintNeeded

`func (o *JustInSequenceApiCreateJISKit201Response) GetIsReprintNeeded() bool`

GetIsReprintNeeded returns the IsReprintNeeded field if non-nil, zero value otherwise.

### GetIsReprintNeededOk

`func (o *JustInSequenceApiCreateJISKit201Response) GetIsReprintNeededOk() (*bool, bool)`

GetIsReprintNeededOk returns a tuple with the IsReprintNeeded field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsReprintNeeded

`func (o *JustInSequenceApiCreateJISKit201Response) SetIsReprintNeeded(v bool)`

SetIsReprintNeeded sets IsReprintNeeded field to given value.

### HasIsReprintNeeded

`func (o *JustInSequenceApiCreateJISKit201Response) HasIsReprintNeeded() bool`

HasIsReprintNeeded returns a boolean if a field has been set.

### GetCreatedById

`func (o *JustInSequenceApiCreateJISKit201Response) GetCreatedById() string`

GetCreatedById returns the CreatedById field if non-nil, zero value otherwise.

### GetCreatedByIdOk

`func (o *JustInSequenceApiCreateJISKit201Response) GetCreatedByIdOk() (*string, bool)`

GetCreatedByIdOk returns a tuple with the CreatedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedById

`func (o *JustInSequenceApiCreateJISKit201Response) SetCreatedById(v string)`

SetCreatedById sets CreatedById field to given value.

### HasCreatedById

`func (o *JustInSequenceApiCreateJISKit201Response) HasCreatedById() bool`

HasCreatedById returns a boolean if a field has been set.

### GetCreatedDateTime

`func (o *JustInSequenceApiCreateJISKit201Response) GetCreatedDateTime() time.Time`

GetCreatedDateTime returns the CreatedDateTime field if non-nil, zero value otherwise.

### GetCreatedDateTimeOk

`func (o *JustInSequenceApiCreateJISKit201Response) GetCreatedDateTimeOk() (*time.Time, bool)`

GetCreatedDateTimeOk returns a tuple with the CreatedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDateTime

`func (o *JustInSequenceApiCreateJISKit201Response) SetCreatedDateTime(v time.Time)`

SetCreatedDateTime sets CreatedDateTime field to given value.

### HasCreatedDateTime

`func (o *JustInSequenceApiCreateJISKit201Response) HasCreatedDateTime() bool`

HasCreatedDateTime returns a boolean if a field has been set.

### GetModifiedById

`func (o *JustInSequenceApiCreateJISKit201Response) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *JustInSequenceApiCreateJISKit201Response) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *JustInSequenceApiCreateJISKit201Response) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *JustInSequenceApiCreateJISKit201Response) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetModifiedDateTime

`func (o *JustInSequenceApiCreateJISKit201Response) GetModifiedDateTime() time.Time`

GetModifiedDateTime returns the ModifiedDateTime field if non-nil, zero value otherwise.

### GetModifiedDateTimeOk

`func (o *JustInSequenceApiCreateJISKit201Response) GetModifiedDateTimeOk() (*time.Time, bool)`

GetModifiedDateTimeOk returns a tuple with the ModifiedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDateTime

`func (o *JustInSequenceApiCreateJISKit201Response) SetModifiedDateTime(v time.Time)`

SetModifiedDateTime sets ModifiedDateTime field to given value.

### HasModifiedDateTime

`func (o *JustInSequenceApiCreateJISKit201Response) HasModifiedDateTime() bool`

HasModifiedDateTime returns a boolean if a field has been set.

### GetPrintedById

`func (o *JustInSequenceApiCreateJISKit201Response) GetPrintedById() string`

GetPrintedById returns the PrintedById field if non-nil, zero value otherwise.

### GetPrintedByIdOk

`func (o *JustInSequenceApiCreateJISKit201Response) GetPrintedByIdOk() (*string, bool)`

GetPrintedByIdOk returns a tuple with the PrintedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrintedById

`func (o *JustInSequenceApiCreateJISKit201Response) SetPrintedById(v string)`

SetPrintedById sets PrintedById field to given value.

### HasPrintedById

`func (o *JustInSequenceApiCreateJISKit201Response) HasPrintedById() bool`

HasPrintedById returns a boolean if a field has been set.

### GetPrintedDateTime

`func (o *JustInSequenceApiCreateJISKit201Response) GetPrintedDateTime() time.Time`

GetPrintedDateTime returns the PrintedDateTime field if non-nil, zero value otherwise.

### GetPrintedDateTimeOk

`func (o *JustInSequenceApiCreateJISKit201Response) GetPrintedDateTimeOk() (*time.Time, bool)`

GetPrintedDateTimeOk returns a tuple with the PrintedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrintedDateTime

`func (o *JustInSequenceApiCreateJISKit201Response) SetPrintedDateTime(v time.Time)`

SetPrintedDateTime sets PrintedDateTime field to given value.

### HasPrintedDateTime

`func (o *JustInSequenceApiCreateJISKit201Response) HasPrintedDateTime() bool`

HasPrintedDateTime returns a boolean if a field has been set.

### GetPackedById

`func (o *JustInSequenceApiCreateJISKit201Response) GetPackedById() string`

GetPackedById returns the PackedById field if non-nil, zero value otherwise.

### GetPackedByIdOk

`func (o *JustInSequenceApiCreateJISKit201Response) GetPackedByIdOk() (*string, bool)`

GetPackedByIdOk returns a tuple with the PackedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackedById

`func (o *JustInSequenceApiCreateJISKit201Response) SetPackedById(v string)`

SetPackedById sets PackedById field to given value.

### HasPackedById

`func (o *JustInSequenceApiCreateJISKit201Response) HasPackedById() bool`

HasPackedById returns a boolean if a field has been set.

### GetPackedDateTime

`func (o *JustInSequenceApiCreateJISKit201Response) GetPackedDateTime() time.Time`

GetPackedDateTime returns the PackedDateTime field if non-nil, zero value otherwise.

### GetPackedDateTimeOk

`func (o *JustInSequenceApiCreateJISKit201Response) GetPackedDateTimeOk() (*time.Time, bool)`

GetPackedDateTimeOk returns a tuple with the PackedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackedDateTime

`func (o *JustInSequenceApiCreateJISKit201Response) SetPackedDateTime(v time.Time)`

SetPackedDateTime sets PackedDateTime field to given value.

### HasPackedDateTime

`func (o *JustInSequenceApiCreateJISKit201Response) HasPackedDateTime() bool`

HasPackedDateTime returns a boolean if a field has been set.

### GetUnpackedById

`func (o *JustInSequenceApiCreateJISKit201Response) GetUnpackedById() string`

GetUnpackedById returns the UnpackedById field if non-nil, zero value otherwise.

### GetUnpackedByIdOk

`func (o *JustInSequenceApiCreateJISKit201Response) GetUnpackedByIdOk() (*string, bool)`

GetUnpackedByIdOk returns a tuple with the UnpackedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnpackedById

`func (o *JustInSequenceApiCreateJISKit201Response) SetUnpackedById(v string)`

SetUnpackedById sets UnpackedById field to given value.

### HasUnpackedById

`func (o *JustInSequenceApiCreateJISKit201Response) HasUnpackedById() bool`

HasUnpackedById returns a boolean if a field has been set.

### GetUnpackedDateTime

`func (o *JustInSequenceApiCreateJISKit201Response) GetUnpackedDateTime() time.Time`

GetUnpackedDateTime returns the UnpackedDateTime field if non-nil, zero value otherwise.

### GetUnpackedDateTimeOk

`func (o *JustInSequenceApiCreateJISKit201Response) GetUnpackedDateTimeOk() (*time.Time, bool)`

GetUnpackedDateTimeOk returns a tuple with the UnpackedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnpackedDateTime

`func (o *JustInSequenceApiCreateJISKit201Response) SetUnpackedDateTime(v time.Time)`

SetUnpackedDateTime sets UnpackedDateTime field to given value.

### HasUnpackedDateTime

`func (o *JustInSequenceApiCreateJISKit201Response) HasUnpackedDateTime() bool`

HasUnpackedDateTime returns a boolean if a field has been set.

### GetRackSequenceNumber

`func (o *JustInSequenceApiCreateJISKit201Response) GetRackSequenceNumber() string`

GetRackSequenceNumber returns the RackSequenceNumber field if non-nil, zero value otherwise.

### GetRackSequenceNumberOk

`func (o *JustInSequenceApiCreateJISKit201Response) GetRackSequenceNumberOk() (*string, bool)`

GetRackSequenceNumberOk returns a tuple with the RackSequenceNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRackSequenceNumber

`func (o *JustInSequenceApiCreateJISKit201Response) SetRackSequenceNumber(v string)`

SetRackSequenceNumber sets RackSequenceNumber field to given value.

### HasRackSequenceNumber

`func (o *JustInSequenceApiCreateJISKit201Response) HasRackSequenceNumber() bool`

HasRackSequenceNumber returns a boolean if a field has been set.

### GetLabelPrintedById

`func (o *JustInSequenceApiCreateJISKit201Response) GetLabelPrintedById() string`

GetLabelPrintedById returns the LabelPrintedById field if non-nil, zero value otherwise.

### GetLabelPrintedByIdOk

`func (o *JustInSequenceApiCreateJISKit201Response) GetLabelPrintedByIdOk() (*string, bool)`

GetLabelPrintedByIdOk returns a tuple with the LabelPrintedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabelPrintedById

`func (o *JustInSequenceApiCreateJISKit201Response) SetLabelPrintedById(v string)`

SetLabelPrintedById sets LabelPrintedById field to given value.

### HasLabelPrintedById

`func (o *JustInSequenceApiCreateJISKit201Response) HasLabelPrintedById() bool`

HasLabelPrintedById returns a boolean if a field has been set.

### GetLabelPrintedDateTime

`func (o *JustInSequenceApiCreateJISKit201Response) GetLabelPrintedDateTime() time.Time`

GetLabelPrintedDateTime returns the LabelPrintedDateTime field if non-nil, zero value otherwise.

### GetLabelPrintedDateTimeOk

`func (o *JustInSequenceApiCreateJISKit201Response) GetLabelPrintedDateTimeOk() (*time.Time, bool)`

GetLabelPrintedDateTimeOk returns a tuple with the LabelPrintedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabelPrintedDateTime

`func (o *JustInSequenceApiCreateJISKit201Response) SetLabelPrintedDateTime(v time.Time)`

SetLabelPrintedDateTime sets LabelPrintedDateTime field to given value.

### HasLabelPrintedDateTime

`func (o *JustInSequenceApiCreateJISKit201Response) HasLabelPrintedDateTime() bool`

HasLabelPrintedDateTime returns a boolean if a field has been set.

### GetRackCellName

`func (o *JustInSequenceApiCreateJISKit201Response) GetRackCellName() string`

GetRackCellName returns the RackCellName field if non-nil, zero value otherwise.

### GetRackCellNameOk

`func (o *JustInSequenceApiCreateJISKit201Response) GetRackCellNameOk() (*string, bool)`

GetRackCellNameOk returns a tuple with the RackCellName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRackCellName

`func (o *JustInSequenceApiCreateJISKit201Response) SetRackCellName(v string)`

SetRackCellName sets RackCellName field to given value.

### HasRackCellName

`func (o *JustInSequenceApiCreateJISKit201Response) HasRackCellName() bool`

HasRackCellName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


