# SalesReleasesApiUpdateReleaseRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ReleaseNumber** | Pointer to **string** | The release number, typically dictated by the customer, for a specific sales release. | [optional] 
**OrderLineId** | Pointer to **string** | The ID of the purchase order line. | [optional] 
**Type** | Pointer to **string** | The release type for a specific sales release. | [optional] 
**ShipToAddressId** | Pointer to **string** | The ID of the customer address to which the release will ship. | [optional] 
**ShipDate** | Pointer to **time.Time** | The date on which a sales release must be shipped to satisfy the release&#39;s due date. | [optional] 
**DueDate** | Pointer to **time.Time** | The date on which a sales release is expected to be fulfilled. | [optional] 
**Quantity** | Pointer to **float64** | The quantity of parts that were ordered and assigned to the sales release. | [optional] 
**Status** | Pointer to **string** | The sales release&#39;s current status. | [optional] 
**Source** | Pointer to **string** | Identifies the source of the sales release, such as EDI or email. | [optional] 
**Note** | Pointer to **string** | A note on the sales release. | [optional] 
**ScheduleNo** | Pointer to **string** | The schedule number relates multiple releases, which may span various parts and/or purchase orders, to a customer&#39;s schedule. This is typically populated via EDI. | [optional] 
**ScheduleDate** | Pointer to **time.Time** | The schedule date relates multiple releases, which may span various parts and/or purchase orders, to a customer&#39;s schedule. This is typically populated via EDI. | [optional] 
**QuantityShipped** | Pointer to **int32** | The quantity of parts that have been shipped against the sales release. | [optional] 
**OrderQuantity** | Pointer to **float64** | The quantity of parts from the sales order. | [optional] 
**ForecastDate** | Pointer to **time.Time** | The sales release&#39;s forecast date. | [optional] 
**ShipFrom** | Pointer to **string** | The building code that the sales release will ship from. | [optional] 
**FabAuthorizationNo** | Pointer to **string** | The fabrication authorization number for the sales release. | [optional] 
**RawAuthorizationNo** | Pointer to **string** | The raw material authorization number for the sales release. | [optional] 
**ProductionStartDate** | Pointer to **time.Time** | The date that production is expected to start for the sales release | [optional] 
**ModelName** | Pointer to **string** | The model name associated with the sales release. | [optional] 
**PackagingNote** | Pointer to **string** | A packaging note on the sales release. | [optional] 

## Methods

### NewSalesReleasesApiUpdateReleaseRequest

`func NewSalesReleasesApiUpdateReleaseRequest() *SalesReleasesApiUpdateReleaseRequest`

NewSalesReleasesApiUpdateReleaseRequest instantiates a new SalesReleasesApiUpdateReleaseRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSalesReleasesApiUpdateReleaseRequestWithDefaults

`func NewSalesReleasesApiUpdateReleaseRequestWithDefaults() *SalesReleasesApiUpdateReleaseRequest`

NewSalesReleasesApiUpdateReleaseRequestWithDefaults instantiates a new SalesReleasesApiUpdateReleaseRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetReleaseNumber

`func (o *SalesReleasesApiUpdateReleaseRequest) GetReleaseNumber() string`

GetReleaseNumber returns the ReleaseNumber field if non-nil, zero value otherwise.

### GetReleaseNumberOk

`func (o *SalesReleasesApiUpdateReleaseRequest) GetReleaseNumberOk() (*string, bool)`

GetReleaseNumberOk returns a tuple with the ReleaseNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleaseNumber

`func (o *SalesReleasesApiUpdateReleaseRequest) SetReleaseNumber(v string)`

SetReleaseNumber sets ReleaseNumber field to given value.

### HasReleaseNumber

`func (o *SalesReleasesApiUpdateReleaseRequest) HasReleaseNumber() bool`

HasReleaseNumber returns a boolean if a field has been set.

### GetOrderLineId

`func (o *SalesReleasesApiUpdateReleaseRequest) GetOrderLineId() string`

GetOrderLineId returns the OrderLineId field if non-nil, zero value otherwise.

### GetOrderLineIdOk

`func (o *SalesReleasesApiUpdateReleaseRequest) GetOrderLineIdOk() (*string, bool)`

GetOrderLineIdOk returns a tuple with the OrderLineId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderLineId

`func (o *SalesReleasesApiUpdateReleaseRequest) SetOrderLineId(v string)`

SetOrderLineId sets OrderLineId field to given value.

### HasOrderLineId

`func (o *SalesReleasesApiUpdateReleaseRequest) HasOrderLineId() bool`

HasOrderLineId returns a boolean if a field has been set.

### GetType

`func (o *SalesReleasesApiUpdateReleaseRequest) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *SalesReleasesApiUpdateReleaseRequest) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *SalesReleasesApiUpdateReleaseRequest) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *SalesReleasesApiUpdateReleaseRequest) HasType() bool`

HasType returns a boolean if a field has been set.

### GetShipToAddressId

`func (o *SalesReleasesApiUpdateReleaseRequest) GetShipToAddressId() string`

GetShipToAddressId returns the ShipToAddressId field if non-nil, zero value otherwise.

### GetShipToAddressIdOk

`func (o *SalesReleasesApiUpdateReleaseRequest) GetShipToAddressIdOk() (*string, bool)`

GetShipToAddressIdOk returns a tuple with the ShipToAddressId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipToAddressId

`func (o *SalesReleasesApiUpdateReleaseRequest) SetShipToAddressId(v string)`

SetShipToAddressId sets ShipToAddressId field to given value.

### HasShipToAddressId

`func (o *SalesReleasesApiUpdateReleaseRequest) HasShipToAddressId() bool`

HasShipToAddressId returns a boolean if a field has been set.

### GetShipDate

`func (o *SalesReleasesApiUpdateReleaseRequest) GetShipDate() time.Time`

GetShipDate returns the ShipDate field if non-nil, zero value otherwise.

### GetShipDateOk

`func (o *SalesReleasesApiUpdateReleaseRequest) GetShipDateOk() (*time.Time, bool)`

GetShipDateOk returns a tuple with the ShipDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipDate

`func (o *SalesReleasesApiUpdateReleaseRequest) SetShipDate(v time.Time)`

SetShipDate sets ShipDate field to given value.

### HasShipDate

`func (o *SalesReleasesApiUpdateReleaseRequest) HasShipDate() bool`

HasShipDate returns a boolean if a field has been set.

### GetDueDate

`func (o *SalesReleasesApiUpdateReleaseRequest) GetDueDate() time.Time`

GetDueDate returns the DueDate field if non-nil, zero value otherwise.

### GetDueDateOk

`func (o *SalesReleasesApiUpdateReleaseRequest) GetDueDateOk() (*time.Time, bool)`

GetDueDateOk returns a tuple with the DueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueDate

`func (o *SalesReleasesApiUpdateReleaseRequest) SetDueDate(v time.Time)`

SetDueDate sets DueDate field to given value.

### HasDueDate

`func (o *SalesReleasesApiUpdateReleaseRequest) HasDueDate() bool`

HasDueDate returns a boolean if a field has been set.

### GetQuantity

`func (o *SalesReleasesApiUpdateReleaseRequest) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *SalesReleasesApiUpdateReleaseRequest) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *SalesReleasesApiUpdateReleaseRequest) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *SalesReleasesApiUpdateReleaseRequest) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetStatus

`func (o *SalesReleasesApiUpdateReleaseRequest) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *SalesReleasesApiUpdateReleaseRequest) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *SalesReleasesApiUpdateReleaseRequest) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *SalesReleasesApiUpdateReleaseRequest) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetSource

`func (o *SalesReleasesApiUpdateReleaseRequest) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *SalesReleasesApiUpdateReleaseRequest) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *SalesReleasesApiUpdateReleaseRequest) SetSource(v string)`

SetSource sets Source field to given value.

### HasSource

`func (o *SalesReleasesApiUpdateReleaseRequest) HasSource() bool`

HasSource returns a boolean if a field has been set.

### GetNote

`func (o *SalesReleasesApiUpdateReleaseRequest) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *SalesReleasesApiUpdateReleaseRequest) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *SalesReleasesApiUpdateReleaseRequest) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *SalesReleasesApiUpdateReleaseRequest) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetScheduleNo

`func (o *SalesReleasesApiUpdateReleaseRequest) GetScheduleNo() string`

GetScheduleNo returns the ScheduleNo field if non-nil, zero value otherwise.

### GetScheduleNoOk

`func (o *SalesReleasesApiUpdateReleaseRequest) GetScheduleNoOk() (*string, bool)`

GetScheduleNoOk returns a tuple with the ScheduleNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScheduleNo

`func (o *SalesReleasesApiUpdateReleaseRequest) SetScheduleNo(v string)`

SetScheduleNo sets ScheduleNo field to given value.

### HasScheduleNo

`func (o *SalesReleasesApiUpdateReleaseRequest) HasScheduleNo() bool`

HasScheduleNo returns a boolean if a field has been set.

### GetScheduleDate

`func (o *SalesReleasesApiUpdateReleaseRequest) GetScheduleDate() time.Time`

GetScheduleDate returns the ScheduleDate field if non-nil, zero value otherwise.

### GetScheduleDateOk

`func (o *SalesReleasesApiUpdateReleaseRequest) GetScheduleDateOk() (*time.Time, bool)`

GetScheduleDateOk returns a tuple with the ScheduleDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScheduleDate

`func (o *SalesReleasesApiUpdateReleaseRequest) SetScheduleDate(v time.Time)`

SetScheduleDate sets ScheduleDate field to given value.

### HasScheduleDate

`func (o *SalesReleasesApiUpdateReleaseRequest) HasScheduleDate() bool`

HasScheduleDate returns a boolean if a field has been set.

### GetQuantityShipped

`func (o *SalesReleasesApiUpdateReleaseRequest) GetQuantityShipped() int32`

GetQuantityShipped returns the QuantityShipped field if non-nil, zero value otherwise.

### GetQuantityShippedOk

`func (o *SalesReleasesApiUpdateReleaseRequest) GetQuantityShippedOk() (*int32, bool)`

GetQuantityShippedOk returns a tuple with the QuantityShipped field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantityShipped

`func (o *SalesReleasesApiUpdateReleaseRequest) SetQuantityShipped(v int32)`

SetQuantityShipped sets QuantityShipped field to given value.

### HasQuantityShipped

`func (o *SalesReleasesApiUpdateReleaseRequest) HasQuantityShipped() bool`

HasQuantityShipped returns a boolean if a field has been set.

### GetOrderQuantity

`func (o *SalesReleasesApiUpdateReleaseRequest) GetOrderQuantity() float64`

GetOrderQuantity returns the OrderQuantity field if non-nil, zero value otherwise.

### GetOrderQuantityOk

`func (o *SalesReleasesApiUpdateReleaseRequest) GetOrderQuantityOk() (*float64, bool)`

GetOrderQuantityOk returns a tuple with the OrderQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderQuantity

`func (o *SalesReleasesApiUpdateReleaseRequest) SetOrderQuantity(v float64)`

SetOrderQuantity sets OrderQuantity field to given value.

### HasOrderQuantity

`func (o *SalesReleasesApiUpdateReleaseRequest) HasOrderQuantity() bool`

HasOrderQuantity returns a boolean if a field has been set.

### GetForecastDate

`func (o *SalesReleasesApiUpdateReleaseRequest) GetForecastDate() time.Time`

GetForecastDate returns the ForecastDate field if non-nil, zero value otherwise.

### GetForecastDateOk

`func (o *SalesReleasesApiUpdateReleaseRequest) GetForecastDateOk() (*time.Time, bool)`

GetForecastDateOk returns a tuple with the ForecastDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForecastDate

`func (o *SalesReleasesApiUpdateReleaseRequest) SetForecastDate(v time.Time)`

SetForecastDate sets ForecastDate field to given value.

### HasForecastDate

`func (o *SalesReleasesApiUpdateReleaseRequest) HasForecastDate() bool`

HasForecastDate returns a boolean if a field has been set.

### GetShipFrom

`func (o *SalesReleasesApiUpdateReleaseRequest) GetShipFrom() string`

GetShipFrom returns the ShipFrom field if non-nil, zero value otherwise.

### GetShipFromOk

`func (o *SalesReleasesApiUpdateReleaseRequest) GetShipFromOk() (*string, bool)`

GetShipFromOk returns a tuple with the ShipFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipFrom

`func (o *SalesReleasesApiUpdateReleaseRequest) SetShipFrom(v string)`

SetShipFrom sets ShipFrom field to given value.

### HasShipFrom

`func (o *SalesReleasesApiUpdateReleaseRequest) HasShipFrom() bool`

HasShipFrom returns a boolean if a field has been set.

### GetFabAuthorizationNo

`func (o *SalesReleasesApiUpdateReleaseRequest) GetFabAuthorizationNo() string`

GetFabAuthorizationNo returns the FabAuthorizationNo field if non-nil, zero value otherwise.

### GetFabAuthorizationNoOk

`func (o *SalesReleasesApiUpdateReleaseRequest) GetFabAuthorizationNoOk() (*string, bool)`

GetFabAuthorizationNoOk returns a tuple with the FabAuthorizationNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFabAuthorizationNo

`func (o *SalesReleasesApiUpdateReleaseRequest) SetFabAuthorizationNo(v string)`

SetFabAuthorizationNo sets FabAuthorizationNo field to given value.

### HasFabAuthorizationNo

`func (o *SalesReleasesApiUpdateReleaseRequest) HasFabAuthorizationNo() bool`

HasFabAuthorizationNo returns a boolean if a field has been set.

### GetRawAuthorizationNo

`func (o *SalesReleasesApiUpdateReleaseRequest) GetRawAuthorizationNo() string`

GetRawAuthorizationNo returns the RawAuthorizationNo field if non-nil, zero value otherwise.

### GetRawAuthorizationNoOk

`func (o *SalesReleasesApiUpdateReleaseRequest) GetRawAuthorizationNoOk() (*string, bool)`

GetRawAuthorizationNoOk returns a tuple with the RawAuthorizationNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRawAuthorizationNo

`func (o *SalesReleasesApiUpdateReleaseRequest) SetRawAuthorizationNo(v string)`

SetRawAuthorizationNo sets RawAuthorizationNo field to given value.

### HasRawAuthorizationNo

`func (o *SalesReleasesApiUpdateReleaseRequest) HasRawAuthorizationNo() bool`

HasRawAuthorizationNo returns a boolean if a field has been set.

### GetProductionStartDate

`func (o *SalesReleasesApiUpdateReleaseRequest) GetProductionStartDate() time.Time`

GetProductionStartDate returns the ProductionStartDate field if non-nil, zero value otherwise.

### GetProductionStartDateOk

`func (o *SalesReleasesApiUpdateReleaseRequest) GetProductionStartDateOk() (*time.Time, bool)`

GetProductionStartDateOk returns a tuple with the ProductionStartDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductionStartDate

`func (o *SalesReleasesApiUpdateReleaseRequest) SetProductionStartDate(v time.Time)`

SetProductionStartDate sets ProductionStartDate field to given value.

### HasProductionStartDate

`func (o *SalesReleasesApiUpdateReleaseRequest) HasProductionStartDate() bool`

HasProductionStartDate returns a boolean if a field has been set.

### GetModelName

`func (o *SalesReleasesApiUpdateReleaseRequest) GetModelName() string`

GetModelName returns the ModelName field if non-nil, zero value otherwise.

### GetModelNameOk

`func (o *SalesReleasesApiUpdateReleaseRequest) GetModelNameOk() (*string, bool)`

GetModelNameOk returns a tuple with the ModelName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModelName

`func (o *SalesReleasesApiUpdateReleaseRequest) SetModelName(v string)`

SetModelName sets ModelName field to given value.

### HasModelName

`func (o *SalesReleasesApiUpdateReleaseRequest) HasModelName() bool`

HasModelName returns a boolean if a field has been set.

### GetPackagingNote

`func (o *SalesReleasesApiUpdateReleaseRequest) GetPackagingNote() string`

GetPackagingNote returns the PackagingNote field if non-nil, zero value otherwise.

### GetPackagingNoteOk

`func (o *SalesReleasesApiUpdateReleaseRequest) GetPackagingNoteOk() (*string, bool)`

GetPackagingNoteOk returns a tuple with the PackagingNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackagingNote

`func (o *SalesReleasesApiUpdateReleaseRequest) SetPackagingNote(v string)`

SetPackagingNote sets PackagingNote field to given value.

### HasPackagingNote

`func (o *SalesReleasesApiUpdateReleaseRequest) HasPackagingNote() bool`

HasPackagingNote returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


