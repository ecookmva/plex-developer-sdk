# PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | Pointer to **string** | The status of the release. If no value is provided for the status, it will be determined based on the firm and planned days by the values provided in this request or in the Approved Supplier record associated with the PO line item. | [optional] 
**DueDate** | Pointer to **time.Time** | The Due Date of the Release. | [optional] 
**Quantity** | Pointer to **float64** | Release Quantity. | [optional] 
**Type** | Pointer to **string** | Release Type. | [optional] 
**Note** | Pointer to **string** | Release Note. | [optional] 
**PoShipTo** | Pointer to **string** | Purchase Order Ship To. | [optional] 
**FirmDays** | Pointer to **int32** | The maximum number of days in which to create releases with a firm status. Any value provided in this parameter will override any Approved Supplier record associated with the PO line item. | [optional] 
**PlanDays** | Pointer to **int32** | The maximum number of days in which to create releases with a planned status. Any value provided in this parameter will override any Approved Supplier record associated with the PO line item. | [optional] 
**ForecastDays** | Pointer to **int32** | The maximum number of days in which to create releases with a forecast status. Provide a value in this parameter to limit the created releases (the Approved Supplier record is not used to limit the number of Forecast Days for releases). | [optional] 
**Id** | Pointer to **string** | The release id. | [optional] 

## Methods

### NewPurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest

`func NewPurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest() *PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest`

NewPurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest instantiates a new PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPurchaseOrderReleasesBatchApiUpdateReleaseBatchRequestWithDefaults

`func NewPurchaseOrderReleasesBatchApiUpdateReleaseBatchRequestWithDefaults() *PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest`

NewPurchaseOrderReleasesBatchApiUpdateReleaseBatchRequestWithDefaults instantiates a new PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatus

`func (o *PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetDueDate

`func (o *PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest) GetDueDate() time.Time`

GetDueDate returns the DueDate field if non-nil, zero value otherwise.

### GetDueDateOk

`func (o *PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest) GetDueDateOk() (*time.Time, bool)`

GetDueDateOk returns a tuple with the DueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueDate

`func (o *PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest) SetDueDate(v time.Time)`

SetDueDate sets DueDate field to given value.

### HasDueDate

`func (o *PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest) HasDueDate() bool`

HasDueDate returns a boolean if a field has been set.

### GetQuantity

`func (o *PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetType

`func (o *PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest) HasType() bool`

HasType returns a boolean if a field has been set.

### GetNote

`func (o *PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetPoShipTo

`func (o *PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest) GetPoShipTo() string`

GetPoShipTo returns the PoShipTo field if non-nil, zero value otherwise.

### GetPoShipToOk

`func (o *PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest) GetPoShipToOk() (*string, bool)`

GetPoShipToOk returns a tuple with the PoShipTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoShipTo

`func (o *PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest) SetPoShipTo(v string)`

SetPoShipTo sets PoShipTo field to given value.

### HasPoShipTo

`func (o *PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest) HasPoShipTo() bool`

HasPoShipTo returns a boolean if a field has been set.

### GetFirmDays

`func (o *PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest) GetFirmDays() int32`

GetFirmDays returns the FirmDays field if non-nil, zero value otherwise.

### GetFirmDaysOk

`func (o *PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest) GetFirmDaysOk() (*int32, bool)`

GetFirmDaysOk returns a tuple with the FirmDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirmDays

`func (o *PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest) SetFirmDays(v int32)`

SetFirmDays sets FirmDays field to given value.

### HasFirmDays

`func (o *PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest) HasFirmDays() bool`

HasFirmDays returns a boolean if a field has been set.

### GetPlanDays

`func (o *PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest) GetPlanDays() int32`

GetPlanDays returns the PlanDays field if non-nil, zero value otherwise.

### GetPlanDaysOk

`func (o *PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest) GetPlanDaysOk() (*int32, bool)`

GetPlanDaysOk returns a tuple with the PlanDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlanDays

`func (o *PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest) SetPlanDays(v int32)`

SetPlanDays sets PlanDays field to given value.

### HasPlanDays

`func (o *PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest) HasPlanDays() bool`

HasPlanDays returns a boolean if a field has been set.

### GetForecastDays

`func (o *PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest) GetForecastDays() int32`

GetForecastDays returns the ForecastDays field if non-nil, zero value otherwise.

### GetForecastDaysOk

`func (o *PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest) GetForecastDaysOk() (*int32, bool)`

GetForecastDaysOk returns a tuple with the ForecastDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForecastDays

`func (o *PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest) SetForecastDays(v int32)`

SetForecastDays sets ForecastDays field to given value.

### HasForecastDays

`func (o *PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest) HasForecastDays() bool`

HasForecastDays returns a boolean if a field has been set.

### GetId

`func (o *PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *PurchaseOrderReleasesBatchApiUpdateReleaseBatchRequest) HasId() bool`

HasId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


