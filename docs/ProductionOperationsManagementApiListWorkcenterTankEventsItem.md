# ProductionOperationsManagementApiListWorkcenterTankEventsItem

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

### NewProductionOperationsManagementApiListWorkcenterTankEventsItem

`func NewProductionOperationsManagementApiListWorkcenterTankEventsItem() *ProductionOperationsManagementApiListWorkcenterTankEventsItem`

NewProductionOperationsManagementApiListWorkcenterTankEventsItem instantiates a new ProductionOperationsManagementApiListWorkcenterTankEventsItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductionOperationsManagementApiListWorkcenterTankEventsItemWithDefaults

`func NewProductionOperationsManagementApiListWorkcenterTankEventsItemWithDefaults() *ProductionOperationsManagementApiListWorkcenterTankEventsItem`

NewProductionOperationsManagementApiListWorkcenterTankEventsItemWithDefaults instantiates a new ProductionOperationsManagementApiListWorkcenterTankEventsItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTankSiloCode

`func (o *ProductionOperationsManagementApiListWorkcenterTankEventsItem) GetTankSiloCode() string`

GetTankSiloCode returns the TankSiloCode field if non-nil, zero value otherwise.

### GetTankSiloCodeOk

`func (o *ProductionOperationsManagementApiListWorkcenterTankEventsItem) GetTankSiloCodeOk() (*string, bool)`

GetTankSiloCodeOk returns a tuple with the TankSiloCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTankSiloCode

`func (o *ProductionOperationsManagementApiListWorkcenterTankEventsItem) SetTankSiloCode(v string)`

SetTankSiloCode sets TankSiloCode field to given value.

### HasTankSiloCode

`func (o *ProductionOperationsManagementApiListWorkcenterTankEventsItem) HasTankSiloCode() bool`

HasTankSiloCode returns a boolean if a field has been set.

### GetTankName

`func (o *ProductionOperationsManagementApiListWorkcenterTankEventsItem) GetTankName() string`

GetTankName returns the TankName field if non-nil, zero value otherwise.

### GetTankNameOk

`func (o *ProductionOperationsManagementApiListWorkcenterTankEventsItem) GetTankNameOk() (*string, bool)`

GetTankNameOk returns a tuple with the TankName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTankName

`func (o *ProductionOperationsManagementApiListWorkcenterTankEventsItem) SetTankName(v string)`

SetTankName sets TankName field to given value.

### HasTankName

`func (o *ProductionOperationsManagementApiListWorkcenterTankEventsItem) HasTankName() bool`

HasTankName returns a boolean if a field has been set.

### GetEventType

`func (o *ProductionOperationsManagementApiListWorkcenterTankEventsItem) GetEventType() string`

GetEventType returns the EventType field if non-nil, zero value otherwise.

### GetEventTypeOk

`func (o *ProductionOperationsManagementApiListWorkcenterTankEventsItem) GetEventTypeOk() (*string, bool)`

GetEventTypeOk returns a tuple with the EventType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventType

`func (o *ProductionOperationsManagementApiListWorkcenterTankEventsItem) SetEventType(v string)`

SetEventType sets EventType field to given value.

### HasEventType

`func (o *ProductionOperationsManagementApiListWorkcenterTankEventsItem) HasEventType() bool`

HasEventType returns a boolean if a field has been set.

### GetPartNo

`func (o *ProductionOperationsManagementApiListWorkcenterTankEventsItem) GetPartNo() string`

GetPartNo returns the PartNo field if non-nil, zero value otherwise.

### GetPartNoOk

`func (o *ProductionOperationsManagementApiListWorkcenterTankEventsItem) GetPartNoOk() (*string, bool)`

GetPartNoOk returns a tuple with the PartNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNo

`func (o *ProductionOperationsManagementApiListWorkcenterTankEventsItem) SetPartNo(v string)`

SetPartNo sets PartNo field to given value.

### HasPartNo

`func (o *ProductionOperationsManagementApiListWorkcenterTankEventsItem) HasPartNo() bool`

HasPartNo returns a boolean if a field has been set.

### GetPartName

`func (o *ProductionOperationsManagementApiListWorkcenterTankEventsItem) GetPartName() string`

GetPartName returns the PartName field if non-nil, zero value otherwise.

### GetPartNameOk

`func (o *ProductionOperationsManagementApiListWorkcenterTankEventsItem) GetPartNameOk() (*string, bool)`

GetPartNameOk returns a tuple with the PartName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartName

`func (o *ProductionOperationsManagementApiListWorkcenterTankEventsItem) SetPartName(v string)`

SetPartName sets PartName field to given value.

### HasPartName

`func (o *ProductionOperationsManagementApiListWorkcenterTankEventsItem) HasPartName() bool`

HasPartName returns a boolean if a field has been set.

### GetLotId

`func (o *ProductionOperationsManagementApiListWorkcenterTankEventsItem) GetLotId() string`

GetLotId returns the LotId field if non-nil, zero value otherwise.

### GetLotIdOk

`func (o *ProductionOperationsManagementApiListWorkcenterTankEventsItem) GetLotIdOk() (*string, bool)`

GetLotIdOk returns a tuple with the LotId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLotId

`func (o *ProductionOperationsManagementApiListWorkcenterTankEventsItem) SetLotId(v string)`

SetLotId sets LotId field to given value.

### HasLotId

`func (o *ProductionOperationsManagementApiListWorkcenterTankEventsItem) HasLotId() bool`

HasLotId returns a boolean if a field has been set.

### GetLotNo

`func (o *ProductionOperationsManagementApiListWorkcenterTankEventsItem) GetLotNo() string`

GetLotNo returns the LotNo field if non-nil, zero value otherwise.

### GetLotNoOk

`func (o *ProductionOperationsManagementApiListWorkcenterTankEventsItem) GetLotNoOk() (*string, bool)`

GetLotNoOk returns a tuple with the LotNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLotNo

`func (o *ProductionOperationsManagementApiListWorkcenterTankEventsItem) SetLotNo(v string)`

SetLotNo sets LotNo field to given value.

### HasLotNo

`func (o *ProductionOperationsManagementApiListWorkcenterTankEventsItem) HasLotNo() bool`

HasLotNo returns a boolean if a field has been set.

### GetAddDateTime

`func (o *ProductionOperationsManagementApiListWorkcenterTankEventsItem) GetAddDateTime() time.Time`

GetAddDateTime returns the AddDateTime field if non-nil, zero value otherwise.

### GetAddDateTimeOk

`func (o *ProductionOperationsManagementApiListWorkcenterTankEventsItem) GetAddDateTimeOk() (*time.Time, bool)`

GetAddDateTimeOk returns a tuple with the AddDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddDateTime

`func (o *ProductionOperationsManagementApiListWorkcenterTankEventsItem) SetAddDateTime(v time.Time)`

SetAddDateTime sets AddDateTime field to given value.

### HasAddDateTime

`func (o *ProductionOperationsManagementApiListWorkcenterTankEventsItem) HasAddDateTime() bool`

HasAddDateTime returns a boolean if a field has been set.

### GetIgnoreForLotTraceDateTime

`func (o *ProductionOperationsManagementApiListWorkcenterTankEventsItem) GetIgnoreForLotTraceDateTime() time.Time`

GetIgnoreForLotTraceDateTime returns the IgnoreForLotTraceDateTime field if non-nil, zero value otherwise.

### GetIgnoreForLotTraceDateTimeOk

`func (o *ProductionOperationsManagementApiListWorkcenterTankEventsItem) GetIgnoreForLotTraceDateTimeOk() (*time.Time, bool)`

GetIgnoreForLotTraceDateTimeOk returns a tuple with the IgnoreForLotTraceDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIgnoreForLotTraceDateTime

`func (o *ProductionOperationsManagementApiListWorkcenterTankEventsItem) SetIgnoreForLotTraceDateTime(v time.Time)`

SetIgnoreForLotTraceDateTime sets IgnoreForLotTraceDateTime field to given value.

### HasIgnoreForLotTraceDateTime

`func (o *ProductionOperationsManagementApiListWorkcenterTankEventsItem) HasIgnoreForLotTraceDateTime() bool`

HasIgnoreForLotTraceDateTime returns a boolean if a field has been set.

### GetSanitizationCode

`func (o *ProductionOperationsManagementApiListWorkcenterTankEventsItem) GetSanitizationCode() string`

GetSanitizationCode returns the SanitizationCode field if non-nil, zero value otherwise.

### GetSanitizationCodeOk

`func (o *ProductionOperationsManagementApiListWorkcenterTankEventsItem) GetSanitizationCodeOk() (*string, bool)`

GetSanitizationCodeOk returns a tuple with the SanitizationCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSanitizationCode

`func (o *ProductionOperationsManagementApiListWorkcenterTankEventsItem) SetSanitizationCode(v string)`

SetSanitizationCode sets SanitizationCode field to given value.

### HasSanitizationCode

`func (o *ProductionOperationsManagementApiListWorkcenterTankEventsItem) HasSanitizationCode() bool`

HasSanitizationCode returns a boolean if a field has been set.

### GetResetLotTrace

`func (o *ProductionOperationsManagementApiListWorkcenterTankEventsItem) GetResetLotTrace() bool`

GetResetLotTrace returns the ResetLotTrace field if non-nil, zero value otherwise.

### GetResetLotTraceOk

`func (o *ProductionOperationsManagementApiListWorkcenterTankEventsItem) GetResetLotTraceOk() (*bool, bool)`

GetResetLotTraceOk returns a tuple with the ResetLotTrace field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResetLotTrace

`func (o *ProductionOperationsManagementApiListWorkcenterTankEventsItem) SetResetLotTrace(v bool)`

SetResetLotTrace sets ResetLotTrace field to given value.

### HasResetLotTrace

`func (o *ProductionOperationsManagementApiListWorkcenterTankEventsItem) HasResetLotTrace() bool`

HasResetLotTrace returns a boolean if a field has been set.

### GetNote

`func (o *ProductionOperationsManagementApiListWorkcenterTankEventsItem) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *ProductionOperationsManagementApiListWorkcenterTankEventsItem) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *ProductionOperationsManagementApiListWorkcenterTankEventsItem) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *ProductionOperationsManagementApiListWorkcenterTankEventsItem) HasNote() bool`

HasNote returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


