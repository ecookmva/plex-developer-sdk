# SalesReleasesApiCreateReleaseRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | The ID of the Release. | [optional] 
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
**ProductionStartDate** | Pointer to **time.Time** | The date that production is expected to start for the sales release. | [optional] 
**ModelName** | Pointer to **string** | The model name associated with the sales release. | [optional] 
**PackagingNote** | Pointer to **string** | A packaging note on the release | [optional] 

## Methods

### NewSalesReleasesApiCreateReleaseRequest

`func NewSalesReleasesApiCreateReleaseRequest() *SalesReleasesApiCreateReleaseRequest`

NewSalesReleasesApiCreateReleaseRequest instantiates a new SalesReleasesApiCreateReleaseRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSalesReleasesApiCreateReleaseRequestWithDefaults

`func NewSalesReleasesApiCreateReleaseRequestWithDefaults() *SalesReleasesApiCreateReleaseRequest`

NewSalesReleasesApiCreateReleaseRequestWithDefaults instantiates a new SalesReleasesApiCreateReleaseRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SalesReleasesApiCreateReleaseRequest) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SalesReleasesApiCreateReleaseRequest) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SalesReleasesApiCreateReleaseRequest) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *SalesReleasesApiCreateReleaseRequest) HasId() bool`

HasId returns a boolean if a field has been set.

### GetReleaseNumber

`func (o *SalesReleasesApiCreateReleaseRequest) GetReleaseNumber() string`

GetReleaseNumber returns the ReleaseNumber field if non-nil, zero value otherwise.

### GetReleaseNumberOk

`func (o *SalesReleasesApiCreateReleaseRequest) GetReleaseNumberOk() (*string, bool)`

GetReleaseNumberOk returns a tuple with the ReleaseNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleaseNumber

`func (o *SalesReleasesApiCreateReleaseRequest) SetReleaseNumber(v string)`

SetReleaseNumber sets ReleaseNumber field to given value.

### HasReleaseNumber

`func (o *SalesReleasesApiCreateReleaseRequest) HasReleaseNumber() bool`

HasReleaseNumber returns a boolean if a field has been set.

### GetOrderLineId

`func (o *SalesReleasesApiCreateReleaseRequest) GetOrderLineId() string`

GetOrderLineId returns the OrderLineId field if non-nil, zero value otherwise.

### GetOrderLineIdOk

`func (o *SalesReleasesApiCreateReleaseRequest) GetOrderLineIdOk() (*string, bool)`

GetOrderLineIdOk returns a tuple with the OrderLineId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderLineId

`func (o *SalesReleasesApiCreateReleaseRequest) SetOrderLineId(v string)`

SetOrderLineId sets OrderLineId field to given value.

### HasOrderLineId

`func (o *SalesReleasesApiCreateReleaseRequest) HasOrderLineId() bool`

HasOrderLineId returns a boolean if a field has been set.

### GetType

`func (o *SalesReleasesApiCreateReleaseRequest) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *SalesReleasesApiCreateReleaseRequest) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *SalesReleasesApiCreateReleaseRequest) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *SalesReleasesApiCreateReleaseRequest) HasType() bool`

HasType returns a boolean if a field has been set.

### GetShipToAddressId

`func (o *SalesReleasesApiCreateReleaseRequest) GetShipToAddressId() string`

GetShipToAddressId returns the ShipToAddressId field if non-nil, zero value otherwise.

### GetShipToAddressIdOk

`func (o *SalesReleasesApiCreateReleaseRequest) GetShipToAddressIdOk() (*string, bool)`

GetShipToAddressIdOk returns a tuple with the ShipToAddressId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipToAddressId

`func (o *SalesReleasesApiCreateReleaseRequest) SetShipToAddressId(v string)`

SetShipToAddressId sets ShipToAddressId field to given value.

### HasShipToAddressId

`func (o *SalesReleasesApiCreateReleaseRequest) HasShipToAddressId() bool`

HasShipToAddressId returns a boolean if a field has been set.

### GetShipDate

`func (o *SalesReleasesApiCreateReleaseRequest) GetShipDate() time.Time`

GetShipDate returns the ShipDate field if non-nil, zero value otherwise.

### GetShipDateOk

`func (o *SalesReleasesApiCreateReleaseRequest) GetShipDateOk() (*time.Time, bool)`

GetShipDateOk returns a tuple with the ShipDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipDate

`func (o *SalesReleasesApiCreateReleaseRequest) SetShipDate(v time.Time)`

SetShipDate sets ShipDate field to given value.

### HasShipDate

`func (o *SalesReleasesApiCreateReleaseRequest) HasShipDate() bool`

HasShipDate returns a boolean if a field has been set.

### GetDueDate

`func (o *SalesReleasesApiCreateReleaseRequest) GetDueDate() time.Time`

GetDueDate returns the DueDate field if non-nil, zero value otherwise.

### GetDueDateOk

`func (o *SalesReleasesApiCreateReleaseRequest) GetDueDateOk() (*time.Time, bool)`

GetDueDateOk returns a tuple with the DueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueDate

`func (o *SalesReleasesApiCreateReleaseRequest) SetDueDate(v time.Time)`

SetDueDate sets DueDate field to given value.

### HasDueDate

`func (o *SalesReleasesApiCreateReleaseRequest) HasDueDate() bool`

HasDueDate returns a boolean if a field has been set.

### GetQuantity

`func (o *SalesReleasesApiCreateReleaseRequest) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *SalesReleasesApiCreateReleaseRequest) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *SalesReleasesApiCreateReleaseRequest) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *SalesReleasesApiCreateReleaseRequest) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetStatus

`func (o *SalesReleasesApiCreateReleaseRequest) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *SalesReleasesApiCreateReleaseRequest) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *SalesReleasesApiCreateReleaseRequest) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *SalesReleasesApiCreateReleaseRequest) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetSource

`func (o *SalesReleasesApiCreateReleaseRequest) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *SalesReleasesApiCreateReleaseRequest) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *SalesReleasesApiCreateReleaseRequest) SetSource(v string)`

SetSource sets Source field to given value.

### HasSource

`func (o *SalesReleasesApiCreateReleaseRequest) HasSource() bool`

HasSource returns a boolean if a field has been set.

### GetNote

`func (o *SalesReleasesApiCreateReleaseRequest) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *SalesReleasesApiCreateReleaseRequest) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *SalesReleasesApiCreateReleaseRequest) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *SalesReleasesApiCreateReleaseRequest) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetScheduleNo

`func (o *SalesReleasesApiCreateReleaseRequest) GetScheduleNo() string`

GetScheduleNo returns the ScheduleNo field if non-nil, zero value otherwise.

### GetScheduleNoOk

`func (o *SalesReleasesApiCreateReleaseRequest) GetScheduleNoOk() (*string, bool)`

GetScheduleNoOk returns a tuple with the ScheduleNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScheduleNo

`func (o *SalesReleasesApiCreateReleaseRequest) SetScheduleNo(v string)`

SetScheduleNo sets ScheduleNo field to given value.

### HasScheduleNo

`func (o *SalesReleasesApiCreateReleaseRequest) HasScheduleNo() bool`

HasScheduleNo returns a boolean if a field has been set.

### GetScheduleDate

`func (o *SalesReleasesApiCreateReleaseRequest) GetScheduleDate() time.Time`

GetScheduleDate returns the ScheduleDate field if non-nil, zero value otherwise.

### GetScheduleDateOk

`func (o *SalesReleasesApiCreateReleaseRequest) GetScheduleDateOk() (*time.Time, bool)`

GetScheduleDateOk returns a tuple with the ScheduleDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScheduleDate

`func (o *SalesReleasesApiCreateReleaseRequest) SetScheduleDate(v time.Time)`

SetScheduleDate sets ScheduleDate field to given value.

### HasScheduleDate

`func (o *SalesReleasesApiCreateReleaseRequest) HasScheduleDate() bool`

HasScheduleDate returns a boolean if a field has been set.

### GetQuantityShipped

`func (o *SalesReleasesApiCreateReleaseRequest) GetQuantityShipped() int32`

GetQuantityShipped returns the QuantityShipped field if non-nil, zero value otherwise.

### GetQuantityShippedOk

`func (o *SalesReleasesApiCreateReleaseRequest) GetQuantityShippedOk() (*int32, bool)`

GetQuantityShippedOk returns a tuple with the QuantityShipped field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantityShipped

`func (o *SalesReleasesApiCreateReleaseRequest) SetQuantityShipped(v int32)`

SetQuantityShipped sets QuantityShipped field to given value.

### HasQuantityShipped

`func (o *SalesReleasesApiCreateReleaseRequest) HasQuantityShipped() bool`

HasQuantityShipped returns a boolean if a field has been set.

### GetOrderQuantity

`func (o *SalesReleasesApiCreateReleaseRequest) GetOrderQuantity() float64`

GetOrderQuantity returns the OrderQuantity field if non-nil, zero value otherwise.

### GetOrderQuantityOk

`func (o *SalesReleasesApiCreateReleaseRequest) GetOrderQuantityOk() (*float64, bool)`

GetOrderQuantityOk returns a tuple with the OrderQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderQuantity

`func (o *SalesReleasesApiCreateReleaseRequest) SetOrderQuantity(v float64)`

SetOrderQuantity sets OrderQuantity field to given value.

### HasOrderQuantity

`func (o *SalesReleasesApiCreateReleaseRequest) HasOrderQuantity() bool`

HasOrderQuantity returns a boolean if a field has been set.

### GetForecastDate

`func (o *SalesReleasesApiCreateReleaseRequest) GetForecastDate() time.Time`

GetForecastDate returns the ForecastDate field if non-nil, zero value otherwise.

### GetForecastDateOk

`func (o *SalesReleasesApiCreateReleaseRequest) GetForecastDateOk() (*time.Time, bool)`

GetForecastDateOk returns a tuple with the ForecastDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForecastDate

`func (o *SalesReleasesApiCreateReleaseRequest) SetForecastDate(v time.Time)`

SetForecastDate sets ForecastDate field to given value.

### HasForecastDate

`func (o *SalesReleasesApiCreateReleaseRequest) HasForecastDate() bool`

HasForecastDate returns a boolean if a field has been set.

### GetShipFrom

`func (o *SalesReleasesApiCreateReleaseRequest) GetShipFrom() string`

GetShipFrom returns the ShipFrom field if non-nil, zero value otherwise.

### GetShipFromOk

`func (o *SalesReleasesApiCreateReleaseRequest) GetShipFromOk() (*string, bool)`

GetShipFromOk returns a tuple with the ShipFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipFrom

`func (o *SalesReleasesApiCreateReleaseRequest) SetShipFrom(v string)`

SetShipFrom sets ShipFrom field to given value.

### HasShipFrom

`func (o *SalesReleasesApiCreateReleaseRequest) HasShipFrom() bool`

HasShipFrom returns a boolean if a field has been set.

### GetFabAuthorizationNo

`func (o *SalesReleasesApiCreateReleaseRequest) GetFabAuthorizationNo() string`

GetFabAuthorizationNo returns the FabAuthorizationNo field if non-nil, zero value otherwise.

### GetFabAuthorizationNoOk

`func (o *SalesReleasesApiCreateReleaseRequest) GetFabAuthorizationNoOk() (*string, bool)`

GetFabAuthorizationNoOk returns a tuple with the FabAuthorizationNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFabAuthorizationNo

`func (o *SalesReleasesApiCreateReleaseRequest) SetFabAuthorizationNo(v string)`

SetFabAuthorizationNo sets FabAuthorizationNo field to given value.

### HasFabAuthorizationNo

`func (o *SalesReleasesApiCreateReleaseRequest) HasFabAuthorizationNo() bool`

HasFabAuthorizationNo returns a boolean if a field has been set.

### GetRawAuthorizationNo

`func (o *SalesReleasesApiCreateReleaseRequest) GetRawAuthorizationNo() string`

GetRawAuthorizationNo returns the RawAuthorizationNo field if non-nil, zero value otherwise.

### GetRawAuthorizationNoOk

`func (o *SalesReleasesApiCreateReleaseRequest) GetRawAuthorizationNoOk() (*string, bool)`

GetRawAuthorizationNoOk returns a tuple with the RawAuthorizationNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRawAuthorizationNo

`func (o *SalesReleasesApiCreateReleaseRequest) SetRawAuthorizationNo(v string)`

SetRawAuthorizationNo sets RawAuthorizationNo field to given value.

### HasRawAuthorizationNo

`func (o *SalesReleasesApiCreateReleaseRequest) HasRawAuthorizationNo() bool`

HasRawAuthorizationNo returns a boolean if a field has been set.

### GetProductionStartDate

`func (o *SalesReleasesApiCreateReleaseRequest) GetProductionStartDate() time.Time`

GetProductionStartDate returns the ProductionStartDate field if non-nil, zero value otherwise.

### GetProductionStartDateOk

`func (o *SalesReleasesApiCreateReleaseRequest) GetProductionStartDateOk() (*time.Time, bool)`

GetProductionStartDateOk returns a tuple with the ProductionStartDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductionStartDate

`func (o *SalesReleasesApiCreateReleaseRequest) SetProductionStartDate(v time.Time)`

SetProductionStartDate sets ProductionStartDate field to given value.

### HasProductionStartDate

`func (o *SalesReleasesApiCreateReleaseRequest) HasProductionStartDate() bool`

HasProductionStartDate returns a boolean if a field has been set.

### GetModelName

`func (o *SalesReleasesApiCreateReleaseRequest) GetModelName() string`

GetModelName returns the ModelName field if non-nil, zero value otherwise.

### GetModelNameOk

`func (o *SalesReleasesApiCreateReleaseRequest) GetModelNameOk() (*string, bool)`

GetModelNameOk returns a tuple with the ModelName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModelName

`func (o *SalesReleasesApiCreateReleaseRequest) SetModelName(v string)`

SetModelName sets ModelName field to given value.

### HasModelName

`func (o *SalesReleasesApiCreateReleaseRequest) HasModelName() bool`

HasModelName returns a boolean if a field has been set.

### GetPackagingNote

`func (o *SalesReleasesApiCreateReleaseRequest) GetPackagingNote() string`

GetPackagingNote returns the PackagingNote field if non-nil, zero value otherwise.

### GetPackagingNoteOk

`func (o *SalesReleasesApiCreateReleaseRequest) GetPackagingNoteOk() (*string, bool)`

GetPackagingNoteOk returns a tuple with the PackagingNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackagingNote

`func (o *SalesReleasesApiCreateReleaseRequest) SetPackagingNote(v string)`

SetPackagingNote sets PackagingNote field to given value.

### HasPackagingNote

`func (o *SalesReleasesApiCreateReleaseRequest) HasPackagingNote() bool`

HasPackagingNote returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


