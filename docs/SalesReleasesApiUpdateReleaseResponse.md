# SalesReleasesApiUpdateReleaseResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | The ID of the sales release. | [optional] 
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
**CreatedById** | Pointer to **string** | The ID of the Plex user who created the record. | [optional] 
**CreatedDate** | Pointer to **time.Time** | The date on which the record was created. | [optional] 
**ModifiedById** | Pointer to **string** | The ID of the Plex user who last modified the record. | [optional] 
**ModifiedDate** | Pointer to **time.Time** | The date on which the record was last modified. | [optional] 
**ForecastDate** | Pointer to **time.Time** | The sales release&#39;s forecast date. | [optional] 
**ShipFrom** | Pointer to **string** | The building code that the sales release will ship from. | [optional] 
**FabAuthorizationNo** | Pointer to **string** | The fabrication authorization number for the sales release. | [optional] 
**RawAuthorizationNo** | Pointer to **string** | The raw material authorization number for the sales release. | [optional] 
**PartNumber** | Pointer to **string** | The part number for the sales release. | [optional] 
**ProductionStartDate** | Pointer to **time.Time** | The date that production is expected to start for the sales release. | [optional] 
**ModelName** | Pointer to **string** | The model name associated with the sales release. | [optional] 
**PoLineDefaultOrderUnit** | Pointer to **string** | The sales release&#39;s order unit of measure. | [optional] 
**PackagingNote** | Pointer to **string** | A packaging note on the sales release. | [optional] 

## Methods

### NewSalesReleasesApiUpdateReleaseResponse

`func NewSalesReleasesApiUpdateReleaseResponse() *SalesReleasesApiUpdateReleaseResponse`

NewSalesReleasesApiUpdateReleaseResponse instantiates a new SalesReleasesApiUpdateReleaseResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSalesReleasesApiUpdateReleaseResponseWithDefaults

`func NewSalesReleasesApiUpdateReleaseResponseWithDefaults() *SalesReleasesApiUpdateReleaseResponse`

NewSalesReleasesApiUpdateReleaseResponseWithDefaults instantiates a new SalesReleasesApiUpdateReleaseResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SalesReleasesApiUpdateReleaseResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SalesReleasesApiUpdateReleaseResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SalesReleasesApiUpdateReleaseResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *SalesReleasesApiUpdateReleaseResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetReleaseNumber

`func (o *SalesReleasesApiUpdateReleaseResponse) GetReleaseNumber() string`

GetReleaseNumber returns the ReleaseNumber field if non-nil, zero value otherwise.

### GetReleaseNumberOk

`func (o *SalesReleasesApiUpdateReleaseResponse) GetReleaseNumberOk() (*string, bool)`

GetReleaseNumberOk returns a tuple with the ReleaseNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleaseNumber

`func (o *SalesReleasesApiUpdateReleaseResponse) SetReleaseNumber(v string)`

SetReleaseNumber sets ReleaseNumber field to given value.

### HasReleaseNumber

`func (o *SalesReleasesApiUpdateReleaseResponse) HasReleaseNumber() bool`

HasReleaseNumber returns a boolean if a field has been set.

### GetOrderLineId

`func (o *SalesReleasesApiUpdateReleaseResponse) GetOrderLineId() string`

GetOrderLineId returns the OrderLineId field if non-nil, zero value otherwise.

### GetOrderLineIdOk

`func (o *SalesReleasesApiUpdateReleaseResponse) GetOrderLineIdOk() (*string, bool)`

GetOrderLineIdOk returns a tuple with the OrderLineId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderLineId

`func (o *SalesReleasesApiUpdateReleaseResponse) SetOrderLineId(v string)`

SetOrderLineId sets OrderLineId field to given value.

### HasOrderLineId

`func (o *SalesReleasesApiUpdateReleaseResponse) HasOrderLineId() bool`

HasOrderLineId returns a boolean if a field has been set.

### GetType

`func (o *SalesReleasesApiUpdateReleaseResponse) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *SalesReleasesApiUpdateReleaseResponse) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *SalesReleasesApiUpdateReleaseResponse) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *SalesReleasesApiUpdateReleaseResponse) HasType() bool`

HasType returns a boolean if a field has been set.

### GetShipToAddressId

`func (o *SalesReleasesApiUpdateReleaseResponse) GetShipToAddressId() string`

GetShipToAddressId returns the ShipToAddressId field if non-nil, zero value otherwise.

### GetShipToAddressIdOk

`func (o *SalesReleasesApiUpdateReleaseResponse) GetShipToAddressIdOk() (*string, bool)`

GetShipToAddressIdOk returns a tuple with the ShipToAddressId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipToAddressId

`func (o *SalesReleasesApiUpdateReleaseResponse) SetShipToAddressId(v string)`

SetShipToAddressId sets ShipToAddressId field to given value.

### HasShipToAddressId

`func (o *SalesReleasesApiUpdateReleaseResponse) HasShipToAddressId() bool`

HasShipToAddressId returns a boolean if a field has been set.

### GetShipDate

`func (o *SalesReleasesApiUpdateReleaseResponse) GetShipDate() time.Time`

GetShipDate returns the ShipDate field if non-nil, zero value otherwise.

### GetShipDateOk

`func (o *SalesReleasesApiUpdateReleaseResponse) GetShipDateOk() (*time.Time, bool)`

GetShipDateOk returns a tuple with the ShipDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipDate

`func (o *SalesReleasesApiUpdateReleaseResponse) SetShipDate(v time.Time)`

SetShipDate sets ShipDate field to given value.

### HasShipDate

`func (o *SalesReleasesApiUpdateReleaseResponse) HasShipDate() bool`

HasShipDate returns a boolean if a field has been set.

### GetDueDate

`func (o *SalesReleasesApiUpdateReleaseResponse) GetDueDate() time.Time`

GetDueDate returns the DueDate field if non-nil, zero value otherwise.

### GetDueDateOk

`func (o *SalesReleasesApiUpdateReleaseResponse) GetDueDateOk() (*time.Time, bool)`

GetDueDateOk returns a tuple with the DueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueDate

`func (o *SalesReleasesApiUpdateReleaseResponse) SetDueDate(v time.Time)`

SetDueDate sets DueDate field to given value.

### HasDueDate

`func (o *SalesReleasesApiUpdateReleaseResponse) HasDueDate() bool`

HasDueDate returns a boolean if a field has been set.

### GetQuantity

`func (o *SalesReleasesApiUpdateReleaseResponse) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *SalesReleasesApiUpdateReleaseResponse) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *SalesReleasesApiUpdateReleaseResponse) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *SalesReleasesApiUpdateReleaseResponse) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetStatus

`func (o *SalesReleasesApiUpdateReleaseResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *SalesReleasesApiUpdateReleaseResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *SalesReleasesApiUpdateReleaseResponse) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *SalesReleasesApiUpdateReleaseResponse) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetSource

`func (o *SalesReleasesApiUpdateReleaseResponse) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *SalesReleasesApiUpdateReleaseResponse) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *SalesReleasesApiUpdateReleaseResponse) SetSource(v string)`

SetSource sets Source field to given value.

### HasSource

`func (o *SalesReleasesApiUpdateReleaseResponse) HasSource() bool`

HasSource returns a boolean if a field has been set.

### GetNote

`func (o *SalesReleasesApiUpdateReleaseResponse) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *SalesReleasesApiUpdateReleaseResponse) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *SalesReleasesApiUpdateReleaseResponse) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *SalesReleasesApiUpdateReleaseResponse) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetScheduleNo

`func (o *SalesReleasesApiUpdateReleaseResponse) GetScheduleNo() string`

GetScheduleNo returns the ScheduleNo field if non-nil, zero value otherwise.

### GetScheduleNoOk

`func (o *SalesReleasesApiUpdateReleaseResponse) GetScheduleNoOk() (*string, bool)`

GetScheduleNoOk returns a tuple with the ScheduleNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScheduleNo

`func (o *SalesReleasesApiUpdateReleaseResponse) SetScheduleNo(v string)`

SetScheduleNo sets ScheduleNo field to given value.

### HasScheduleNo

`func (o *SalesReleasesApiUpdateReleaseResponse) HasScheduleNo() bool`

HasScheduleNo returns a boolean if a field has been set.

### GetScheduleDate

`func (o *SalesReleasesApiUpdateReleaseResponse) GetScheduleDate() time.Time`

GetScheduleDate returns the ScheduleDate field if non-nil, zero value otherwise.

### GetScheduleDateOk

`func (o *SalesReleasesApiUpdateReleaseResponse) GetScheduleDateOk() (*time.Time, bool)`

GetScheduleDateOk returns a tuple with the ScheduleDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScheduleDate

`func (o *SalesReleasesApiUpdateReleaseResponse) SetScheduleDate(v time.Time)`

SetScheduleDate sets ScheduleDate field to given value.

### HasScheduleDate

`func (o *SalesReleasesApiUpdateReleaseResponse) HasScheduleDate() bool`

HasScheduleDate returns a boolean if a field has been set.

### GetQuantityShipped

`func (o *SalesReleasesApiUpdateReleaseResponse) GetQuantityShipped() int32`

GetQuantityShipped returns the QuantityShipped field if non-nil, zero value otherwise.

### GetQuantityShippedOk

`func (o *SalesReleasesApiUpdateReleaseResponse) GetQuantityShippedOk() (*int32, bool)`

GetQuantityShippedOk returns a tuple with the QuantityShipped field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantityShipped

`func (o *SalesReleasesApiUpdateReleaseResponse) SetQuantityShipped(v int32)`

SetQuantityShipped sets QuantityShipped field to given value.

### HasQuantityShipped

`func (o *SalesReleasesApiUpdateReleaseResponse) HasQuantityShipped() bool`

HasQuantityShipped returns a boolean if a field has been set.

### GetOrderQuantity

`func (o *SalesReleasesApiUpdateReleaseResponse) GetOrderQuantity() float64`

GetOrderQuantity returns the OrderQuantity field if non-nil, zero value otherwise.

### GetOrderQuantityOk

`func (o *SalesReleasesApiUpdateReleaseResponse) GetOrderQuantityOk() (*float64, bool)`

GetOrderQuantityOk returns a tuple with the OrderQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderQuantity

`func (o *SalesReleasesApiUpdateReleaseResponse) SetOrderQuantity(v float64)`

SetOrderQuantity sets OrderQuantity field to given value.

### HasOrderQuantity

`func (o *SalesReleasesApiUpdateReleaseResponse) HasOrderQuantity() bool`

HasOrderQuantity returns a boolean if a field has been set.

### GetCreatedById

`func (o *SalesReleasesApiUpdateReleaseResponse) GetCreatedById() string`

GetCreatedById returns the CreatedById field if non-nil, zero value otherwise.

### GetCreatedByIdOk

`func (o *SalesReleasesApiUpdateReleaseResponse) GetCreatedByIdOk() (*string, bool)`

GetCreatedByIdOk returns a tuple with the CreatedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedById

`func (o *SalesReleasesApiUpdateReleaseResponse) SetCreatedById(v string)`

SetCreatedById sets CreatedById field to given value.

### HasCreatedById

`func (o *SalesReleasesApiUpdateReleaseResponse) HasCreatedById() bool`

HasCreatedById returns a boolean if a field has been set.

### GetCreatedDate

`func (o *SalesReleasesApiUpdateReleaseResponse) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *SalesReleasesApiUpdateReleaseResponse) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *SalesReleasesApiUpdateReleaseResponse) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *SalesReleasesApiUpdateReleaseResponse) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.

### GetModifiedById

`func (o *SalesReleasesApiUpdateReleaseResponse) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *SalesReleasesApiUpdateReleaseResponse) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *SalesReleasesApiUpdateReleaseResponse) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *SalesReleasesApiUpdateReleaseResponse) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetModifiedDate

`func (o *SalesReleasesApiUpdateReleaseResponse) GetModifiedDate() time.Time`

GetModifiedDate returns the ModifiedDate field if non-nil, zero value otherwise.

### GetModifiedDateOk

`func (o *SalesReleasesApiUpdateReleaseResponse) GetModifiedDateOk() (*time.Time, bool)`

GetModifiedDateOk returns a tuple with the ModifiedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDate

`func (o *SalesReleasesApiUpdateReleaseResponse) SetModifiedDate(v time.Time)`

SetModifiedDate sets ModifiedDate field to given value.

### HasModifiedDate

`func (o *SalesReleasesApiUpdateReleaseResponse) HasModifiedDate() bool`

HasModifiedDate returns a boolean if a field has been set.

### GetForecastDate

`func (o *SalesReleasesApiUpdateReleaseResponse) GetForecastDate() time.Time`

GetForecastDate returns the ForecastDate field if non-nil, zero value otherwise.

### GetForecastDateOk

`func (o *SalesReleasesApiUpdateReleaseResponse) GetForecastDateOk() (*time.Time, bool)`

GetForecastDateOk returns a tuple with the ForecastDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForecastDate

`func (o *SalesReleasesApiUpdateReleaseResponse) SetForecastDate(v time.Time)`

SetForecastDate sets ForecastDate field to given value.

### HasForecastDate

`func (o *SalesReleasesApiUpdateReleaseResponse) HasForecastDate() bool`

HasForecastDate returns a boolean if a field has been set.

### GetShipFrom

`func (o *SalesReleasesApiUpdateReleaseResponse) GetShipFrom() string`

GetShipFrom returns the ShipFrom field if non-nil, zero value otherwise.

### GetShipFromOk

`func (o *SalesReleasesApiUpdateReleaseResponse) GetShipFromOk() (*string, bool)`

GetShipFromOk returns a tuple with the ShipFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipFrom

`func (o *SalesReleasesApiUpdateReleaseResponse) SetShipFrom(v string)`

SetShipFrom sets ShipFrom field to given value.

### HasShipFrom

`func (o *SalesReleasesApiUpdateReleaseResponse) HasShipFrom() bool`

HasShipFrom returns a boolean if a field has been set.

### GetFabAuthorizationNo

`func (o *SalesReleasesApiUpdateReleaseResponse) GetFabAuthorizationNo() string`

GetFabAuthorizationNo returns the FabAuthorizationNo field if non-nil, zero value otherwise.

### GetFabAuthorizationNoOk

`func (o *SalesReleasesApiUpdateReleaseResponse) GetFabAuthorizationNoOk() (*string, bool)`

GetFabAuthorizationNoOk returns a tuple with the FabAuthorizationNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFabAuthorizationNo

`func (o *SalesReleasesApiUpdateReleaseResponse) SetFabAuthorizationNo(v string)`

SetFabAuthorizationNo sets FabAuthorizationNo field to given value.

### HasFabAuthorizationNo

`func (o *SalesReleasesApiUpdateReleaseResponse) HasFabAuthorizationNo() bool`

HasFabAuthorizationNo returns a boolean if a field has been set.

### GetRawAuthorizationNo

`func (o *SalesReleasesApiUpdateReleaseResponse) GetRawAuthorizationNo() string`

GetRawAuthorizationNo returns the RawAuthorizationNo field if non-nil, zero value otherwise.

### GetRawAuthorizationNoOk

`func (o *SalesReleasesApiUpdateReleaseResponse) GetRawAuthorizationNoOk() (*string, bool)`

GetRawAuthorizationNoOk returns a tuple with the RawAuthorizationNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRawAuthorizationNo

`func (o *SalesReleasesApiUpdateReleaseResponse) SetRawAuthorizationNo(v string)`

SetRawAuthorizationNo sets RawAuthorizationNo field to given value.

### HasRawAuthorizationNo

`func (o *SalesReleasesApiUpdateReleaseResponse) HasRawAuthorizationNo() bool`

HasRawAuthorizationNo returns a boolean if a field has been set.

### GetPartNumber

`func (o *SalesReleasesApiUpdateReleaseResponse) GetPartNumber() string`

GetPartNumber returns the PartNumber field if non-nil, zero value otherwise.

### GetPartNumberOk

`func (o *SalesReleasesApiUpdateReleaseResponse) GetPartNumberOk() (*string, bool)`

GetPartNumberOk returns a tuple with the PartNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumber

`func (o *SalesReleasesApiUpdateReleaseResponse) SetPartNumber(v string)`

SetPartNumber sets PartNumber field to given value.

### HasPartNumber

`func (o *SalesReleasesApiUpdateReleaseResponse) HasPartNumber() bool`

HasPartNumber returns a boolean if a field has been set.

### GetProductionStartDate

`func (o *SalesReleasesApiUpdateReleaseResponse) GetProductionStartDate() time.Time`

GetProductionStartDate returns the ProductionStartDate field if non-nil, zero value otherwise.

### GetProductionStartDateOk

`func (o *SalesReleasesApiUpdateReleaseResponse) GetProductionStartDateOk() (*time.Time, bool)`

GetProductionStartDateOk returns a tuple with the ProductionStartDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductionStartDate

`func (o *SalesReleasesApiUpdateReleaseResponse) SetProductionStartDate(v time.Time)`

SetProductionStartDate sets ProductionStartDate field to given value.

### HasProductionStartDate

`func (o *SalesReleasesApiUpdateReleaseResponse) HasProductionStartDate() bool`

HasProductionStartDate returns a boolean if a field has been set.

### GetModelName

`func (o *SalesReleasesApiUpdateReleaseResponse) GetModelName() string`

GetModelName returns the ModelName field if non-nil, zero value otherwise.

### GetModelNameOk

`func (o *SalesReleasesApiUpdateReleaseResponse) GetModelNameOk() (*string, bool)`

GetModelNameOk returns a tuple with the ModelName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModelName

`func (o *SalesReleasesApiUpdateReleaseResponse) SetModelName(v string)`

SetModelName sets ModelName field to given value.

### HasModelName

`func (o *SalesReleasesApiUpdateReleaseResponse) HasModelName() bool`

HasModelName returns a boolean if a field has been set.

### GetPoLineDefaultOrderUnit

`func (o *SalesReleasesApiUpdateReleaseResponse) GetPoLineDefaultOrderUnit() string`

GetPoLineDefaultOrderUnit returns the PoLineDefaultOrderUnit field if non-nil, zero value otherwise.

### GetPoLineDefaultOrderUnitOk

`func (o *SalesReleasesApiUpdateReleaseResponse) GetPoLineDefaultOrderUnitOk() (*string, bool)`

GetPoLineDefaultOrderUnitOk returns a tuple with the PoLineDefaultOrderUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoLineDefaultOrderUnit

`func (o *SalesReleasesApiUpdateReleaseResponse) SetPoLineDefaultOrderUnit(v string)`

SetPoLineDefaultOrderUnit sets PoLineDefaultOrderUnit field to given value.

### HasPoLineDefaultOrderUnit

`func (o *SalesReleasesApiUpdateReleaseResponse) HasPoLineDefaultOrderUnit() bool`

HasPoLineDefaultOrderUnit returns a boolean if a field has been set.

### GetPackagingNote

`func (o *SalesReleasesApiUpdateReleaseResponse) GetPackagingNote() string`

GetPackagingNote returns the PackagingNote field if non-nil, zero value otherwise.

### GetPackagingNoteOk

`func (o *SalesReleasesApiUpdateReleaseResponse) GetPackagingNoteOk() (*string, bool)`

GetPackagingNoteOk returns a tuple with the PackagingNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackagingNote

`func (o *SalesReleasesApiUpdateReleaseResponse) SetPackagingNote(v string)`

SetPackagingNote sets PackagingNote field to given value.

### HasPackagingNote

`func (o *SalesReleasesApiUpdateReleaseResponse) HasPackagingNote() bool`

HasPackagingNote returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


