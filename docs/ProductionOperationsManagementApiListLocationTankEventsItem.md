# ProductionOperationsManagementApiListLocationTankEventsItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TankSiloCode** | Pointer to **string** | The tank/silo code. | [optional] 
**TankName** | Pointer to **string** | The tank name. | [optional] 
**EventType** | Pointer to **string** | The tank event type: Sanitize if it is a sanitization event; if not, it should be a system lot event, including but not limited to Inventory Create, Production, and Move. | [optional] 
**PartNo** | Pointer to **string** | The part number. | [optional] 
**PartName** | Pointer to **string** | The part name. | [optional] 
**LotId** | Pointer to **string** | The lot ID. | [optional] 
**LotNo** | Pointer to **string** | The lot number. | [optional] 
**AddDateTime** | Pointer to **time.Time** | The record add datetime. | [optional] 
**IgnoreForLotTraceDateTime** | Pointer to **time.Time** | The ignore for lot trace datetime. | [optional] 
**SanitizationCode** | Pointer to **string** | The sanitization code. | [optional] 
**ResetLotTrace** | Pointer to **bool** | The reset lot trace flag. | [optional] 
**Note** | Pointer to **string** | The tank lot log note. | [optional] 

## Methods

### NewProductionOperationsManagementApiListLocationTankEventsItem

`func NewProductionOperationsManagementApiListLocationTankEventsItem() *ProductionOperationsManagementApiListLocationTankEventsItem`

NewProductionOperationsManagementApiListLocationTankEventsItem instantiates a new ProductionOperationsManagementApiListLocationTankEventsItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductionOperationsManagementApiListLocationTankEventsItemWithDefaults

`func NewProductionOperationsManagementApiListLocationTankEventsItemWithDefaults() *ProductionOperationsManagementApiListLocationTankEventsItem`

NewProductionOperationsManagementApiListLocationTankEventsItemWithDefaults instantiates a new ProductionOperationsManagementApiListLocationTankEventsItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTankSiloCode

`func (o *ProductionOperationsManagementApiListLocationTankEventsItem) GetTankSiloCode() string`

GetTankSiloCode returns the TankSiloCode field if non-nil, zero value otherwise.

### GetTankSiloCodeOk

`func (o *ProductionOperationsManagementApiListLocationTankEventsItem) GetTankSiloCodeOk() (*string, bool)`

GetTankSiloCodeOk returns a tuple with the TankSiloCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTankSiloCode

`func (o *ProductionOperationsManagementApiListLocationTankEventsItem) SetTankSiloCode(v string)`

SetTankSiloCode sets TankSiloCode field to given value.

### HasTankSiloCode

`func (o *ProductionOperationsManagementApiListLocationTankEventsItem) HasTankSiloCode() bool`

HasTankSiloCode returns a boolean if a field has been set.

### GetTankName

`func (o *ProductionOperationsManagementApiListLocationTankEventsItem) GetTankName() string`

GetTankName returns the TankName field if non-nil, zero value otherwise.

### GetTankNameOk

`func (o *ProductionOperationsManagementApiListLocationTankEventsItem) GetTankNameOk() (*string, bool)`

GetTankNameOk returns a tuple with the TankName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTankName

`func (o *ProductionOperationsManagementApiListLocationTankEventsItem) SetTankName(v string)`

SetTankName sets TankName field to given value.

### HasTankName

`func (o *ProductionOperationsManagementApiListLocationTankEventsItem) HasTankName() bool`

HasTankName returns a boolean if a field has been set.

### GetEventType

`func (o *ProductionOperationsManagementApiListLocationTankEventsItem) GetEventType() string`

GetEventType returns the EventType field if non-nil, zero value otherwise.

### GetEventTypeOk

`func (o *ProductionOperationsManagementApiListLocationTankEventsItem) GetEventTypeOk() (*string, bool)`

GetEventTypeOk returns a tuple with the EventType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventType

`func (o *ProductionOperationsManagementApiListLocationTankEventsItem) SetEventType(v string)`

SetEventType sets EventType field to given value.

### HasEventType

`func (o *ProductionOperationsManagementApiListLocationTankEventsItem) HasEventType() bool`

HasEventType returns a boolean if a field has been set.

### GetPartNo

`func (o *ProductionOperationsManagementApiListLocationTankEventsItem) GetPartNo() string`

GetPartNo returns the PartNo field if non-nil, zero value otherwise.

### GetPartNoOk

`func (o *ProductionOperationsManagementApiListLocationTankEventsItem) GetPartNoOk() (*string, bool)`

GetPartNoOk returns a tuple with the PartNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNo

`func (o *ProductionOperationsManagementApiListLocationTankEventsItem) SetPartNo(v string)`

SetPartNo sets PartNo field to given value.

### HasPartNo

`func (o *ProductionOperationsManagementApiListLocationTankEventsItem) HasPartNo() bool`

HasPartNo returns a boolean if a field has been set.

### GetPartName

`func (o *ProductionOperationsManagementApiListLocationTankEventsItem) GetPartName() string`

GetPartName returns the PartName field if non-nil, zero value otherwise.

### GetPartNameOk

`func (o *ProductionOperationsManagementApiListLocationTankEventsItem) GetPartNameOk() (*string, bool)`

GetPartNameOk returns a tuple with the PartName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartName

`func (o *ProductionOperationsManagementApiListLocationTankEventsItem) SetPartName(v string)`

SetPartName sets PartName field to given value.

### HasPartName

`func (o *ProductionOperationsManagementApiListLocationTankEventsItem) HasPartName() bool`

HasPartName returns a boolean if a field has been set.

### GetLotId

`func (o *ProductionOperationsManagementApiListLocationTankEventsItem) GetLotId() string`

GetLotId returns the LotId field if non-nil, zero value otherwise.

### GetLotIdOk

`func (o *ProductionOperationsManagementApiListLocationTankEventsItem) GetLotIdOk() (*string, bool)`

GetLotIdOk returns a tuple with the LotId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLotId

`func (o *ProductionOperationsManagementApiListLocationTankEventsItem) SetLotId(v string)`

SetLotId sets LotId field to given value.

### HasLotId

`func (o *ProductionOperationsManagementApiListLocationTankEventsItem) HasLotId() bool`

HasLotId returns a boolean if a field has been set.

### GetLotNo

`func (o *ProductionOperationsManagementApiListLocationTankEventsItem) GetLotNo() string`

GetLotNo returns the LotNo field if non-nil, zero value otherwise.

### GetLotNoOk

`func (o *ProductionOperationsManagementApiListLocationTankEventsItem) GetLotNoOk() (*string, bool)`

GetLotNoOk returns a tuple with the LotNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLotNo

`func (o *ProductionOperationsManagementApiListLocationTankEventsItem) SetLotNo(v string)`

SetLotNo sets LotNo field to given value.

### HasLotNo

`func (o *ProductionOperationsManagementApiListLocationTankEventsItem) HasLotNo() bool`

HasLotNo returns a boolean if a field has been set.

### GetAddDateTime

`func (o *ProductionOperationsManagementApiListLocationTankEventsItem) GetAddDateTime() time.Time`

GetAddDateTime returns the AddDateTime field if non-nil, zero value otherwise.

### GetAddDateTimeOk

`func (o *ProductionOperationsManagementApiListLocationTankEventsItem) GetAddDateTimeOk() (*time.Time, bool)`

GetAddDateTimeOk returns a tuple with the AddDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddDateTime

`func (o *ProductionOperationsManagementApiListLocationTankEventsItem) SetAddDateTime(v time.Time)`

SetAddDateTime sets AddDateTime field to given value.

### HasAddDateTime

`func (o *ProductionOperationsManagementApiListLocationTankEventsItem) HasAddDateTime() bool`

HasAddDateTime returns a boolean if a field has been set.

### GetIgnoreForLotTraceDateTime

`func (o *ProductionOperationsManagementApiListLocationTankEventsItem) GetIgnoreForLotTraceDateTime() time.Time`

GetIgnoreForLotTraceDateTime returns the IgnoreForLotTraceDateTime field if non-nil, zero value otherwise.

### GetIgnoreForLotTraceDateTimeOk

`func (o *ProductionOperationsManagementApiListLocationTankEventsItem) GetIgnoreForLotTraceDateTimeOk() (*time.Time, bool)`

GetIgnoreForLotTraceDateTimeOk returns a tuple with the IgnoreForLotTraceDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIgnoreForLotTraceDateTime

`func (o *ProductionOperationsManagementApiListLocationTankEventsItem) SetIgnoreForLotTraceDateTime(v time.Time)`

SetIgnoreForLotTraceDateTime sets IgnoreForLotTraceDateTime field to given value.

### HasIgnoreForLotTraceDateTime

`func (o *ProductionOperationsManagementApiListLocationTankEventsItem) HasIgnoreForLotTraceDateTime() bool`

HasIgnoreForLotTraceDateTime returns a boolean if a field has been set.

### GetSanitizationCode

`func (o *ProductionOperationsManagementApiListLocationTankEventsItem) GetSanitizationCode() string`

GetSanitizationCode returns the SanitizationCode field if non-nil, zero value otherwise.

### GetSanitizationCodeOk

`func (o *ProductionOperationsManagementApiListLocationTankEventsItem) GetSanitizationCodeOk() (*string, bool)`

GetSanitizationCodeOk returns a tuple with the SanitizationCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSanitizationCode

`func (o *ProductionOperationsManagementApiListLocationTankEventsItem) SetSanitizationCode(v string)`

SetSanitizationCode sets SanitizationCode field to given value.

### HasSanitizationCode

`func (o *ProductionOperationsManagementApiListLocationTankEventsItem) HasSanitizationCode() bool`

HasSanitizationCode returns a boolean if a field has been set.

### GetResetLotTrace

`func (o *ProductionOperationsManagementApiListLocationTankEventsItem) GetResetLotTrace() bool`

GetResetLotTrace returns the ResetLotTrace field if non-nil, zero value otherwise.

### GetResetLotTraceOk

`func (o *ProductionOperationsManagementApiListLocationTankEventsItem) GetResetLotTraceOk() (*bool, bool)`

GetResetLotTraceOk returns a tuple with the ResetLotTrace field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResetLotTrace

`func (o *ProductionOperationsManagementApiListLocationTankEventsItem) SetResetLotTrace(v bool)`

SetResetLotTrace sets ResetLotTrace field to given value.

### HasResetLotTrace

`func (o *ProductionOperationsManagementApiListLocationTankEventsItem) HasResetLotTrace() bool`

HasResetLotTrace returns a boolean if a field has been set.

### GetNote

`func (o *ProductionOperationsManagementApiListLocationTankEventsItem) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *ProductionOperationsManagementApiListLocationTankEventsItem) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *ProductionOperationsManagementApiListLocationTankEventsItem) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *ProductionOperationsManagementApiListLocationTankEventsItem) HasNote() bool`

HasNote returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


