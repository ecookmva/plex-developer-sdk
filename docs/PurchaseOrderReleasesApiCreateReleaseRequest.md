# PurchaseOrderReleasesApiCreateReleaseRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | A unique identifier for the Release. This will be automatically generated if omitted from the request. | [optional] 
**PoLineItemId** | Pointer to **string** | Purchase Order Line Item ID. | [optional] 
**Status** | Pointer to **string** | The status of the new release. If no value is provided for the status, it will be determined based on the firm and planned days by the values provided in this request or in the Approved Supplier record associated with the PO line item. | [optional] 
**DueDate** | Pointer to **time.Time** | The Due Date of the Release. | [optional] 
**Quantity** | Pointer to **float64** | Release Quantity. | [optional] 
**Type** | Pointer to **string** | Release Type. | [optional] 
**Note** | Pointer to **string** | Release Note. | [optional] 
**PoShipTo** | Pointer to **string** | Purchase Order Ship To. | [optional] 
**FirmDays** | Pointer to **int32** | The maximum number of days in which to create releases with a firm status. Any value provided in this parameter will override any Approved Supplier record associated with the PO line item. | [optional] 
**PlanDays** | Pointer to **int32** | The maximum number of days in which to create releases with a planned status. Any value provided in this parameter will override any Approved Supplier record associated with the PO line item. | [optional] 
**ForecastDays** | Pointer to **int32** | The maximum number of days in which to create releases with a forecast status. Provide a value in this parameter to limit the created releases (the Approved Supplier record is not used to limit the number of Forecast Days for releases). | [optional] 
**ReleaseLineNo** | Pointer to **int32** | The purchase order line item number that the release is associated with. When this is included in the request, the value is taken from the external system rather than assigned according to Plex logic when releases are created. | [optional] 

## Methods

### NewPurchaseOrderReleasesApiCreateReleaseRequest

`func NewPurchaseOrderReleasesApiCreateReleaseRequest() *PurchaseOrderReleasesApiCreateReleaseRequest`

NewPurchaseOrderReleasesApiCreateReleaseRequest instantiates a new PurchaseOrderReleasesApiCreateReleaseRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPurchaseOrderReleasesApiCreateReleaseRequestWithDefaults

`func NewPurchaseOrderReleasesApiCreateReleaseRequestWithDefaults() *PurchaseOrderReleasesApiCreateReleaseRequest`

NewPurchaseOrderReleasesApiCreateReleaseRequestWithDefaults instantiates a new PurchaseOrderReleasesApiCreateReleaseRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *PurchaseOrderReleasesApiCreateReleaseRequest) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PurchaseOrderReleasesApiCreateReleaseRequest) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PurchaseOrderReleasesApiCreateReleaseRequest) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *PurchaseOrderReleasesApiCreateReleaseRequest) HasId() bool`

HasId returns a boolean if a field has been set.

### GetPoLineItemId

`func (o *PurchaseOrderReleasesApiCreateReleaseRequest) GetPoLineItemId() string`

GetPoLineItemId returns the PoLineItemId field if non-nil, zero value otherwise.

### GetPoLineItemIdOk

`func (o *PurchaseOrderReleasesApiCreateReleaseRequest) GetPoLineItemIdOk() (*string, bool)`

GetPoLineItemIdOk returns a tuple with the PoLineItemId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoLineItemId

`func (o *PurchaseOrderReleasesApiCreateReleaseRequest) SetPoLineItemId(v string)`

SetPoLineItemId sets PoLineItemId field to given value.

### HasPoLineItemId

`func (o *PurchaseOrderReleasesApiCreateReleaseRequest) HasPoLineItemId() bool`

HasPoLineItemId returns a boolean if a field has been set.

### GetStatus

`func (o *PurchaseOrderReleasesApiCreateReleaseRequest) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PurchaseOrderReleasesApiCreateReleaseRequest) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PurchaseOrderReleasesApiCreateReleaseRequest) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *PurchaseOrderReleasesApiCreateReleaseRequest) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetDueDate

`func (o *PurchaseOrderReleasesApiCreateReleaseRequest) GetDueDate() time.Time`

GetDueDate returns the DueDate field if non-nil, zero value otherwise.

### GetDueDateOk

`func (o *PurchaseOrderReleasesApiCreateReleaseRequest) GetDueDateOk() (*time.Time, bool)`

GetDueDateOk returns a tuple with the DueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueDate

`func (o *PurchaseOrderReleasesApiCreateReleaseRequest) SetDueDate(v time.Time)`

SetDueDate sets DueDate field to given value.

### HasDueDate

`func (o *PurchaseOrderReleasesApiCreateReleaseRequest) HasDueDate() bool`

HasDueDate returns a boolean if a field has been set.

### GetQuantity

`func (o *PurchaseOrderReleasesApiCreateReleaseRequest) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *PurchaseOrderReleasesApiCreateReleaseRequest) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *PurchaseOrderReleasesApiCreateReleaseRequest) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *PurchaseOrderReleasesApiCreateReleaseRequest) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetType

`func (o *PurchaseOrderReleasesApiCreateReleaseRequest) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *PurchaseOrderReleasesApiCreateReleaseRequest) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *PurchaseOrderReleasesApiCreateReleaseRequest) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *PurchaseOrderReleasesApiCreateReleaseRequest) HasType() bool`

HasType returns a boolean if a field has been set.

### GetNote

`func (o *PurchaseOrderReleasesApiCreateReleaseRequest) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *PurchaseOrderReleasesApiCreateReleaseRequest) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *PurchaseOrderReleasesApiCreateReleaseRequest) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *PurchaseOrderReleasesApiCreateReleaseRequest) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetPoShipTo

`func (o *PurchaseOrderReleasesApiCreateReleaseRequest) GetPoShipTo() string`

GetPoShipTo returns the PoShipTo field if non-nil, zero value otherwise.

### GetPoShipToOk

`func (o *PurchaseOrderReleasesApiCreateReleaseRequest) GetPoShipToOk() (*string, bool)`

GetPoShipToOk returns a tuple with the PoShipTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoShipTo

`func (o *PurchaseOrderReleasesApiCreateReleaseRequest) SetPoShipTo(v string)`

SetPoShipTo sets PoShipTo field to given value.

### HasPoShipTo

`func (o *PurchaseOrderReleasesApiCreateReleaseRequest) HasPoShipTo() bool`

HasPoShipTo returns a boolean if a field has been set.

### GetFirmDays

`func (o *PurchaseOrderReleasesApiCreateReleaseRequest) GetFirmDays() int32`

GetFirmDays returns the FirmDays field if non-nil, zero value otherwise.

### GetFirmDaysOk

`func (o *PurchaseOrderReleasesApiCreateReleaseRequest) GetFirmDaysOk() (*int32, bool)`

GetFirmDaysOk returns a tuple with the FirmDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirmDays

`func (o *PurchaseOrderReleasesApiCreateReleaseRequest) SetFirmDays(v int32)`

SetFirmDays sets FirmDays field to given value.

### HasFirmDays

`func (o *PurchaseOrderReleasesApiCreateReleaseRequest) HasFirmDays() bool`

HasFirmDays returns a boolean if a field has been set.

### GetPlanDays

`func (o *PurchaseOrderReleasesApiCreateReleaseRequest) GetPlanDays() int32`

GetPlanDays returns the PlanDays field if non-nil, zero value otherwise.

### GetPlanDaysOk

`func (o *PurchaseOrderReleasesApiCreateReleaseRequest) GetPlanDaysOk() (*int32, bool)`

GetPlanDaysOk returns a tuple with the PlanDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlanDays

`func (o *PurchaseOrderReleasesApiCreateReleaseRequest) SetPlanDays(v int32)`

SetPlanDays sets PlanDays field to given value.

### HasPlanDays

`func (o *PurchaseOrderReleasesApiCreateReleaseRequest) HasPlanDays() bool`

HasPlanDays returns a boolean if a field has been set.

### GetForecastDays

`func (o *PurchaseOrderReleasesApiCreateReleaseRequest) GetForecastDays() int32`

GetForecastDays returns the ForecastDays field if non-nil, zero value otherwise.

### GetForecastDaysOk

`func (o *PurchaseOrderReleasesApiCreateReleaseRequest) GetForecastDaysOk() (*int32, bool)`

GetForecastDaysOk returns a tuple with the ForecastDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForecastDays

`func (o *PurchaseOrderReleasesApiCreateReleaseRequest) SetForecastDays(v int32)`

SetForecastDays sets ForecastDays field to given value.

### HasForecastDays

`func (o *PurchaseOrderReleasesApiCreateReleaseRequest) HasForecastDays() bool`

HasForecastDays returns a boolean if a field has been set.

### GetReleaseLineNo

`func (o *PurchaseOrderReleasesApiCreateReleaseRequest) GetReleaseLineNo() int32`

GetReleaseLineNo returns the ReleaseLineNo field if non-nil, zero value otherwise.

### GetReleaseLineNoOk

`func (o *PurchaseOrderReleasesApiCreateReleaseRequest) GetReleaseLineNoOk() (*int32, bool)`

GetReleaseLineNoOk returns a tuple with the ReleaseLineNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleaseLineNo

`func (o *PurchaseOrderReleasesApiCreateReleaseRequest) SetReleaseLineNo(v int32)`

SetReleaseLineNo sets ReleaseLineNo field to given value.

### HasReleaseLineNo

`func (o *PurchaseOrderReleasesApiCreateReleaseRequest) HasReleaseLineNo() bool`

HasReleaseLineNo returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


