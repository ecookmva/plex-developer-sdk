# SalesReleasesApiGetReleaseEDIDetailsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Line11** | Pointer to **string** | A line 11 value sent from EDI, typically for label usage. | [optional] 
**Line12** | Pointer to **string** | A line 12 value sent from EDI, typically for label usage. | [optional] 
**Line13** | Pointer to **string** | A line 13 value sent from EDI, typically for label usage. | [optional] 
**Line14** | Pointer to **string** | A line 14 value sent from EDI, typically for label usage. | [optional] 
**Line15** | Pointer to **string** | A line 15 value sent from EDI, typically for label usage. | [optional] 
**Line16** | Pointer to **string** | A line 16 value sent from EDI, typically for label usage. | [optional] 
**Line17** | Pointer to **string** | A line 17 value sent from EDI, typically for label usage. | [optional] 
**LineCode** | Pointer to **string** | The EDI line code associated with the release. | [optional] 
**PickupTime** | Pointer to **time.Time** | The time at which the sales release will be picked up. | [optional] 
**Batch** | Pointer to **string** | The sales release&#39;s batch number. | [optional] 
**DockCode** | Pointer to **string** | The dock to which the sales release is being sent. | [optional] 
**Document** | Pointer to **string** | A document number that&#39;s associated with the sales release. | [optional] 
**RCode** | Pointer to **string** | A line feed location sent from EDI that&#39;s associated with the sales release. | [optional] 
**ReferenceNumber** | Pointer to **string** | A reference number sent from EDI that&#39;s associated with the sales release. | [optional] 
**KanbanNumber** | Pointer to **string** | The kanban number associated with the sales release. | [optional] 
**IntermediateConsignee** | Pointer to **string** | The intermediate consignee associated with the release. | [optional] 
**LoadSequenceNumber** | Pointer to **string** | The loading sequence number associated with the sales release. | [optional] 
**LotNumber** | Pointer to **string** | The lot number associated with the sales release. | [optional] 
**MaterialHandlingCode** | Pointer to **string** | The material handling code associated with the sales release. | [optional] 
**TimeFrameCode** | Pointer to **string** | The time frame code, typically from EDI, for the sales release. | [optional] 
**Usepoint** | Pointer to **string** | The use point associated with the sales release. | [optional] 
**VehicleId** | Pointer to **string** | The vehicle ID on the sales release. | [optional] 
**LogId** | Pointer to **string** | The ID of the EDI log entry. | [optional] 
**OrderNumber** | Pointer to **string** | The EDI order number associated with the sales release. | [optional] 

## Methods

### NewSalesReleasesApiGetReleaseEDIDetailsResponse

`func NewSalesReleasesApiGetReleaseEDIDetailsResponse() *SalesReleasesApiGetReleaseEDIDetailsResponse`

NewSalesReleasesApiGetReleaseEDIDetailsResponse instantiates a new SalesReleasesApiGetReleaseEDIDetailsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSalesReleasesApiGetReleaseEDIDetailsResponseWithDefaults

`func NewSalesReleasesApiGetReleaseEDIDetailsResponseWithDefaults() *SalesReleasesApiGetReleaseEDIDetailsResponse`

NewSalesReleasesApiGetReleaseEDIDetailsResponseWithDefaults instantiates a new SalesReleasesApiGetReleaseEDIDetailsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLine11

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) GetLine11() string`

GetLine11 returns the Line11 field if non-nil, zero value otherwise.

### GetLine11Ok

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) GetLine11Ok() (*string, bool)`

GetLine11Ok returns a tuple with the Line11 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLine11

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) SetLine11(v string)`

SetLine11 sets Line11 field to given value.

### HasLine11

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) HasLine11() bool`

HasLine11 returns a boolean if a field has been set.

### GetLine12

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) GetLine12() string`

GetLine12 returns the Line12 field if non-nil, zero value otherwise.

### GetLine12Ok

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) GetLine12Ok() (*string, bool)`

GetLine12Ok returns a tuple with the Line12 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLine12

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) SetLine12(v string)`

SetLine12 sets Line12 field to given value.

### HasLine12

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) HasLine12() bool`

HasLine12 returns a boolean if a field has been set.

### GetLine13

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) GetLine13() string`

GetLine13 returns the Line13 field if non-nil, zero value otherwise.

### GetLine13Ok

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) GetLine13Ok() (*string, bool)`

GetLine13Ok returns a tuple with the Line13 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLine13

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) SetLine13(v string)`

SetLine13 sets Line13 field to given value.

### HasLine13

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) HasLine13() bool`

HasLine13 returns a boolean if a field has been set.

### GetLine14

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) GetLine14() string`

GetLine14 returns the Line14 field if non-nil, zero value otherwise.

### GetLine14Ok

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) GetLine14Ok() (*string, bool)`

GetLine14Ok returns a tuple with the Line14 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLine14

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) SetLine14(v string)`

SetLine14 sets Line14 field to given value.

### HasLine14

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) HasLine14() bool`

HasLine14 returns a boolean if a field has been set.

### GetLine15

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) GetLine15() string`

GetLine15 returns the Line15 field if non-nil, zero value otherwise.

### GetLine15Ok

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) GetLine15Ok() (*string, bool)`

GetLine15Ok returns a tuple with the Line15 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLine15

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) SetLine15(v string)`

SetLine15 sets Line15 field to given value.

### HasLine15

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) HasLine15() bool`

HasLine15 returns a boolean if a field has been set.

### GetLine16

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) GetLine16() string`

GetLine16 returns the Line16 field if non-nil, zero value otherwise.

### GetLine16Ok

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) GetLine16Ok() (*string, bool)`

GetLine16Ok returns a tuple with the Line16 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLine16

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) SetLine16(v string)`

SetLine16 sets Line16 field to given value.

### HasLine16

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) HasLine16() bool`

HasLine16 returns a boolean if a field has been set.

### GetLine17

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) GetLine17() string`

GetLine17 returns the Line17 field if non-nil, zero value otherwise.

### GetLine17Ok

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) GetLine17Ok() (*string, bool)`

GetLine17Ok returns a tuple with the Line17 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLine17

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) SetLine17(v string)`

SetLine17 sets Line17 field to given value.

### HasLine17

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) HasLine17() bool`

HasLine17 returns a boolean if a field has been set.

### GetLineCode

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) GetLineCode() string`

GetLineCode returns the LineCode field if non-nil, zero value otherwise.

### GetLineCodeOk

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) GetLineCodeOk() (*string, bool)`

GetLineCodeOk returns a tuple with the LineCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineCode

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) SetLineCode(v string)`

SetLineCode sets LineCode field to given value.

### HasLineCode

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) HasLineCode() bool`

HasLineCode returns a boolean if a field has been set.

### GetPickupTime

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) GetPickupTime() time.Time`

GetPickupTime returns the PickupTime field if non-nil, zero value otherwise.

### GetPickupTimeOk

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) GetPickupTimeOk() (*time.Time, bool)`

GetPickupTimeOk returns a tuple with the PickupTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPickupTime

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) SetPickupTime(v time.Time)`

SetPickupTime sets PickupTime field to given value.

### HasPickupTime

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) HasPickupTime() bool`

HasPickupTime returns a boolean if a field has been set.

### GetBatch

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) GetBatch() string`

GetBatch returns the Batch field if non-nil, zero value otherwise.

### GetBatchOk

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) GetBatchOk() (*string, bool)`

GetBatchOk returns a tuple with the Batch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBatch

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) SetBatch(v string)`

SetBatch sets Batch field to given value.

### HasBatch

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) HasBatch() bool`

HasBatch returns a boolean if a field has been set.

### GetDockCode

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) GetDockCode() string`

GetDockCode returns the DockCode field if non-nil, zero value otherwise.

### GetDockCodeOk

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) GetDockCodeOk() (*string, bool)`

GetDockCodeOk returns a tuple with the DockCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDockCode

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) SetDockCode(v string)`

SetDockCode sets DockCode field to given value.

### HasDockCode

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) HasDockCode() bool`

HasDockCode returns a boolean if a field has been set.

### GetDocument

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) GetDocument() string`

GetDocument returns the Document field if non-nil, zero value otherwise.

### GetDocumentOk

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) GetDocumentOk() (*string, bool)`

GetDocumentOk returns a tuple with the Document field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocument

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) SetDocument(v string)`

SetDocument sets Document field to given value.

### HasDocument

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) HasDocument() bool`

HasDocument returns a boolean if a field has been set.

### GetRCode

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) GetRCode() string`

GetRCode returns the RCode field if non-nil, zero value otherwise.

### GetRCodeOk

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) GetRCodeOk() (*string, bool)`

GetRCodeOk returns a tuple with the RCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRCode

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) SetRCode(v string)`

SetRCode sets RCode field to given value.

### HasRCode

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) HasRCode() bool`

HasRCode returns a boolean if a field has been set.

### GetReferenceNumber

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) GetReferenceNumber() string`

GetReferenceNumber returns the ReferenceNumber field if non-nil, zero value otherwise.

### GetReferenceNumberOk

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) GetReferenceNumberOk() (*string, bool)`

GetReferenceNumberOk returns a tuple with the ReferenceNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferenceNumber

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) SetReferenceNumber(v string)`

SetReferenceNumber sets ReferenceNumber field to given value.

### HasReferenceNumber

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) HasReferenceNumber() bool`

HasReferenceNumber returns a boolean if a field has been set.

### GetKanbanNumber

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) GetKanbanNumber() string`

GetKanbanNumber returns the KanbanNumber field if non-nil, zero value otherwise.

### GetKanbanNumberOk

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) GetKanbanNumberOk() (*string, bool)`

GetKanbanNumberOk returns a tuple with the KanbanNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKanbanNumber

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) SetKanbanNumber(v string)`

SetKanbanNumber sets KanbanNumber field to given value.

### HasKanbanNumber

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) HasKanbanNumber() bool`

HasKanbanNumber returns a boolean if a field has been set.

### GetIntermediateConsignee

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) GetIntermediateConsignee() string`

GetIntermediateConsignee returns the IntermediateConsignee field if non-nil, zero value otherwise.

### GetIntermediateConsigneeOk

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) GetIntermediateConsigneeOk() (*string, bool)`

GetIntermediateConsigneeOk returns a tuple with the IntermediateConsignee field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIntermediateConsignee

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) SetIntermediateConsignee(v string)`

SetIntermediateConsignee sets IntermediateConsignee field to given value.

### HasIntermediateConsignee

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) HasIntermediateConsignee() bool`

HasIntermediateConsignee returns a boolean if a field has been set.

### GetLoadSequenceNumber

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) GetLoadSequenceNumber() string`

GetLoadSequenceNumber returns the LoadSequenceNumber field if non-nil, zero value otherwise.

### GetLoadSequenceNumberOk

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) GetLoadSequenceNumberOk() (*string, bool)`

GetLoadSequenceNumberOk returns a tuple with the LoadSequenceNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLoadSequenceNumber

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) SetLoadSequenceNumber(v string)`

SetLoadSequenceNumber sets LoadSequenceNumber field to given value.

### HasLoadSequenceNumber

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) HasLoadSequenceNumber() bool`

HasLoadSequenceNumber returns a boolean if a field has been set.

### GetLotNumber

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) GetLotNumber() string`

GetLotNumber returns the LotNumber field if non-nil, zero value otherwise.

### GetLotNumberOk

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) GetLotNumberOk() (*string, bool)`

GetLotNumberOk returns a tuple with the LotNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLotNumber

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) SetLotNumber(v string)`

SetLotNumber sets LotNumber field to given value.

### HasLotNumber

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) HasLotNumber() bool`

HasLotNumber returns a boolean if a field has been set.

### GetMaterialHandlingCode

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) GetMaterialHandlingCode() string`

GetMaterialHandlingCode returns the MaterialHandlingCode field if non-nil, zero value otherwise.

### GetMaterialHandlingCodeOk

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) GetMaterialHandlingCodeOk() (*string, bool)`

GetMaterialHandlingCodeOk returns a tuple with the MaterialHandlingCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaterialHandlingCode

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) SetMaterialHandlingCode(v string)`

SetMaterialHandlingCode sets MaterialHandlingCode field to given value.

### HasMaterialHandlingCode

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) HasMaterialHandlingCode() bool`

HasMaterialHandlingCode returns a boolean if a field has been set.

### GetTimeFrameCode

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) GetTimeFrameCode() string`

GetTimeFrameCode returns the TimeFrameCode field if non-nil, zero value otherwise.

### GetTimeFrameCodeOk

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) GetTimeFrameCodeOk() (*string, bool)`

GetTimeFrameCodeOk returns a tuple with the TimeFrameCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeFrameCode

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) SetTimeFrameCode(v string)`

SetTimeFrameCode sets TimeFrameCode field to given value.

### HasTimeFrameCode

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) HasTimeFrameCode() bool`

HasTimeFrameCode returns a boolean if a field has been set.

### GetUsepoint

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) GetUsepoint() string`

GetUsepoint returns the Usepoint field if non-nil, zero value otherwise.

### GetUsepointOk

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) GetUsepointOk() (*string, bool)`

GetUsepointOk returns a tuple with the Usepoint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsepoint

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) SetUsepoint(v string)`

SetUsepoint sets Usepoint field to given value.

### HasUsepoint

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) HasUsepoint() bool`

HasUsepoint returns a boolean if a field has been set.

### GetVehicleId

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) GetVehicleId() string`

GetVehicleId returns the VehicleId field if non-nil, zero value otherwise.

### GetVehicleIdOk

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) GetVehicleIdOk() (*string, bool)`

GetVehicleIdOk returns a tuple with the VehicleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVehicleId

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) SetVehicleId(v string)`

SetVehicleId sets VehicleId field to given value.

### HasVehicleId

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) HasVehicleId() bool`

HasVehicleId returns a boolean if a field has been set.

### GetLogId

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) GetLogId() string`

GetLogId returns the LogId field if non-nil, zero value otherwise.

### GetLogIdOk

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) GetLogIdOk() (*string, bool)`

GetLogIdOk returns a tuple with the LogId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogId

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) SetLogId(v string)`

SetLogId sets LogId field to given value.

### HasLogId

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) HasLogId() bool`

HasLogId returns a boolean if a field has been set.

### GetOrderNumber

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) GetOrderNumber() string`

GetOrderNumber returns the OrderNumber field if non-nil, zero value otherwise.

### GetOrderNumberOk

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) GetOrderNumberOk() (*string, bool)`

GetOrderNumberOk returns a tuple with the OrderNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderNumber

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) SetOrderNumber(v string)`

SetOrderNumber sets OrderNumber field to given value.

### HasOrderNumber

`func (o *SalesReleasesApiGetReleaseEDIDetailsResponse) HasOrderNumber() bool`

HasOrderNumber returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


