# PurchaseOrderReleasesApiUpdateReleaseRequest

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

## Methods

### NewPurchaseOrderReleasesApiUpdateReleaseRequest

`func NewPurchaseOrderReleasesApiUpdateReleaseRequest() *PurchaseOrderReleasesApiUpdateReleaseRequest`

NewPurchaseOrderReleasesApiUpdateReleaseRequest instantiates a new PurchaseOrderReleasesApiUpdateReleaseRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPurchaseOrderReleasesApiUpdateReleaseRequestWithDefaults

`func NewPurchaseOrderReleasesApiUpdateReleaseRequestWithDefaults() *PurchaseOrderReleasesApiUpdateReleaseRequest`

NewPurchaseOrderReleasesApiUpdateReleaseRequestWithDefaults instantiates a new PurchaseOrderReleasesApiUpdateReleaseRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatus

`func (o *PurchaseOrderReleasesApiUpdateReleaseRequest) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PurchaseOrderReleasesApiUpdateReleaseRequest) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PurchaseOrderReleasesApiUpdateReleaseRequest) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *PurchaseOrderReleasesApiUpdateReleaseRequest) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetDueDate

`func (o *PurchaseOrderReleasesApiUpdateReleaseRequest) GetDueDate() time.Time`

GetDueDate returns the DueDate field if non-nil, zero value otherwise.

### GetDueDateOk

`func (o *PurchaseOrderReleasesApiUpdateReleaseRequest) GetDueDateOk() (*time.Time, bool)`

GetDueDateOk returns a tuple with the DueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueDate

`func (o *PurchaseOrderReleasesApiUpdateReleaseRequest) SetDueDate(v time.Time)`

SetDueDate sets DueDate field to given value.

### HasDueDate

`func (o *PurchaseOrderReleasesApiUpdateReleaseRequest) HasDueDate() bool`

HasDueDate returns a boolean if a field has been set.

### GetQuantity

`func (o *PurchaseOrderReleasesApiUpdateReleaseRequest) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *PurchaseOrderReleasesApiUpdateReleaseRequest) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *PurchaseOrderReleasesApiUpdateReleaseRequest) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *PurchaseOrderReleasesApiUpdateReleaseRequest) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetType

`func (o *PurchaseOrderReleasesApiUpdateReleaseRequest) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *PurchaseOrderReleasesApiUpdateReleaseRequest) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *PurchaseOrderReleasesApiUpdateReleaseRequest) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *PurchaseOrderReleasesApiUpdateReleaseRequest) HasType() bool`

HasType returns a boolean if a field has been set.

### GetNote

`func (o *PurchaseOrderReleasesApiUpdateReleaseRequest) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *PurchaseOrderReleasesApiUpdateReleaseRequest) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *PurchaseOrderReleasesApiUpdateReleaseRequest) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *PurchaseOrderReleasesApiUpdateReleaseRequest) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetPoShipTo

`func (o *PurchaseOrderReleasesApiUpdateReleaseRequest) GetPoShipTo() string`

GetPoShipTo returns the PoShipTo field if non-nil, zero value otherwise.

### GetPoShipToOk

`func (o *PurchaseOrderReleasesApiUpdateReleaseRequest) GetPoShipToOk() (*string, bool)`

GetPoShipToOk returns a tuple with the PoShipTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoShipTo

`func (o *PurchaseOrderReleasesApiUpdateReleaseRequest) SetPoShipTo(v string)`

SetPoShipTo sets PoShipTo field to given value.

### HasPoShipTo

`func (o *PurchaseOrderReleasesApiUpdateReleaseRequest) HasPoShipTo() bool`

HasPoShipTo returns a boolean if a field has been set.

### GetFirmDays

`func (o *PurchaseOrderReleasesApiUpdateReleaseRequest) GetFirmDays() int32`

GetFirmDays returns the FirmDays field if non-nil, zero value otherwise.

### GetFirmDaysOk

`func (o *PurchaseOrderReleasesApiUpdateReleaseRequest) GetFirmDaysOk() (*int32, bool)`

GetFirmDaysOk returns a tuple with the FirmDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirmDays

`func (o *PurchaseOrderReleasesApiUpdateReleaseRequest) SetFirmDays(v int32)`

SetFirmDays sets FirmDays field to given value.

### HasFirmDays

`func (o *PurchaseOrderReleasesApiUpdateReleaseRequest) HasFirmDays() bool`

HasFirmDays returns a boolean if a field has been set.

### GetPlanDays

`func (o *PurchaseOrderReleasesApiUpdateReleaseRequest) GetPlanDays() int32`

GetPlanDays returns the PlanDays field if non-nil, zero value otherwise.

### GetPlanDaysOk

`func (o *PurchaseOrderReleasesApiUpdateReleaseRequest) GetPlanDaysOk() (*int32, bool)`

GetPlanDaysOk returns a tuple with the PlanDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlanDays

`func (o *PurchaseOrderReleasesApiUpdateReleaseRequest) SetPlanDays(v int32)`

SetPlanDays sets PlanDays field to given value.

### HasPlanDays

`func (o *PurchaseOrderReleasesApiUpdateReleaseRequest) HasPlanDays() bool`

HasPlanDays returns a boolean if a field has been set.

### GetForecastDays

`func (o *PurchaseOrderReleasesApiUpdateReleaseRequest) GetForecastDays() int32`

GetForecastDays returns the ForecastDays field if non-nil, zero value otherwise.

### GetForecastDaysOk

`func (o *PurchaseOrderReleasesApiUpdateReleaseRequest) GetForecastDaysOk() (*int32, bool)`

GetForecastDaysOk returns a tuple with the ForecastDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForecastDays

`func (o *PurchaseOrderReleasesApiUpdateReleaseRequest) SetForecastDays(v int32)`

SetForecastDays sets ForecastDays field to given value.

### HasForecastDays

`func (o *PurchaseOrderReleasesApiUpdateReleaseRequest) HasForecastDays() bool`

HasForecastDays returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


