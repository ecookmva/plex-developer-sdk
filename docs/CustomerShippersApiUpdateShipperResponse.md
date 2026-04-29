# CustomerShippersApiUpdateShipperResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | A unique identifier for the shipper. | [optional] 
**ShipperNumber** | Pointer to **string** | The shipper number associated with a given shipment. | [optional] 
**CustomerId** | Pointer to **string** | The ID of the customer that is associated with the shipper. | [optional] 
**CustomerAddressId** | Pointer to **string** | The ID of the customer address that is associated with the shipper. | [optional] 
**ShipDate** | Pointer to **time.Time** | The date on which the shipper was shipped. | [optional] 
**ShippedById** | Pointer to **string** | The ID of the user who shipped the shipper. | [optional] 
**CarrierId** | Pointer to **string** | The supplier ID that is flagged as the carrier on the shipment. | [optional] 
**FreightTerms** | Pointer to **string** | Terms of the freight payment; for example, COD, Collect, or Prepaid. | [optional] 
**Status** | Pointer to **string** | The status of the shipper. | [optional] 
**TrackingNumber** | Pointer to **string** | The tracking number, often provided by a carrier, related to a specific shipment. | [optional] 
**TrailerNumber** | Pointer to **string** | The trailer number associated with the physical trailer that a specific shipment was shipped on. | [optional] 
**Note** | Pointer to **string** | An internal note on the shipper. | [optional] 
**ScheduledShipDate** | Pointer to **time.Time** | The date on which the shipper is scheduled to ship. | [optional] 
**CreatedById** | Pointer to **string** | The ID of the user who created the record. | [optional] 
**CreatedDate** | Pointer to **time.Time** | The date on which the record was created. | [optional] 
**ModifiedById** | Pointer to **string** | The ID of the user who last modified the record. | [optional] 
**ModifiedDate** | Pointer to **time.Time** | The date on which the record was last modified. | [optional] 
**ShipperNote** | Pointer to **string** | A note to print on the shipper and the bill of lading (BOL). | [optional] 
**TruckId** | Pointer to **string** | The ID of the truck associated with the shipper. | [optional] 
**ExpediteNote** | Pointer to **string** | Notes related to expedited shipping. | [optional] 
**ExpediteReason** | Pointer to **string** | The reason for expedited shipping as specified on the shipper. | [optional] 
**ExpediteDepartment** | Pointer to **string** | The department that authorized or required an expedited shipment. | [optional] 
**ExpediteAuthorizedById** | Pointer to **string** | The ID of the user who authorized the expedited shipping. | [optional] 
**ExpediteAdditionalCost** | Pointer to **float64** | Additional cost due to expedited shipping. | [optional] 
**ShipFromCode** | Pointer to **string** | The building code from which the shipper was shipped. | [optional] 
**TruckArrivalTime** | Pointer to **time.Time** | This field has been deprecated. Use TruckArrivalTimeOfDay. | [optional] 
**PrintedById** | Pointer to **string** | The ID of the user who printed the record. | [optional] 
**PrintedDate** | Pointer to **time.Time** | The date on which the record was printed. | [optional] 
**FreightAmount** | Pointer to **float64** | Freight amount is the freight cost associated with the shipment. | [optional] 
**BolNote** | Pointer to **string** | The bill of lading (BOL) note on the shipper. | [optional] 
**CustomsExporter** | Pointer to **string** | The customs exporter specified on the shipper. | [optional] 
**DeliveryDateTime** | Pointer to **time.Time** | The delivery date on the shipper. | [optional] 
**DropshipSupplierCode** | Pointer to **string** | The dropship supplier code. | [optional] 
**DropshipSupplierId** | Pointer to **string** | The dropship supplier ID. | [optional] 
**ShipperChargeAmount** | Pointer to **float64** | The charge amount specified on the shipper. | [optional] 
**MasterBolNo** | Pointer to **string** | The master bill of lading (BOL) number. | [optional] 
**Pallets** | Pointer to **int32** | The number of pallets on the shipper. | [optional] 
**PremiumTransAuth** | Pointer to **string** | The number specified in the shipper&#39;s Premium Trans Auth field (used for AETC numbers on expedited shipments). | [optional] 
**TruckConfirmation** | Pointer to **string** | The truck confirmation number. | [optional] 
**TruckCalledDate** | Pointer to **string** | The truck called date. Use format YYYY-MM-DD. | [optional] 
**GrossWeightOverride** | Pointer to **float64** | The gross weight override. | [optional] 
**Mrn** | Pointer to **string** | The Movement Reference Number (MRN) specified on the shipper. | [optional] 
**MrnDate** | Pointer to **string** | The movement reference number (MRN) date. Use format YYYY-MM-DD. | [optional] 
**MrnType** | Pointer to **string** | The movement reference number (MRN) type. | [optional] 
**RoutingAuthorizationNumber** | Pointer to **string** | The routing authorization number. | [optional] 
**ShipperWeight** | Pointer to **float64** | The shipper weight. | [optional] 
**PickListPrintedDateTime** | Pointer to **time.Time** | The date on which the pick list was printed. | [optional] 
**TruckArrivalTimeOfDay** | Pointer to **string** | The truck arrival time. Use format hh:mm:ss. | [optional] 

## Methods

### NewCustomerShippersApiUpdateShipperResponse

`func NewCustomerShippersApiUpdateShipperResponse() *CustomerShippersApiUpdateShipperResponse`

NewCustomerShippersApiUpdateShipperResponse instantiates a new CustomerShippersApiUpdateShipperResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomerShippersApiUpdateShipperResponseWithDefaults

`func NewCustomerShippersApiUpdateShipperResponseWithDefaults() *CustomerShippersApiUpdateShipperResponse`

NewCustomerShippersApiUpdateShipperResponseWithDefaults instantiates a new CustomerShippersApiUpdateShipperResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CustomerShippersApiUpdateShipperResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CustomerShippersApiUpdateShipperResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CustomerShippersApiUpdateShipperResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *CustomerShippersApiUpdateShipperResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetShipperNumber

`func (o *CustomerShippersApiUpdateShipperResponse) GetShipperNumber() string`

GetShipperNumber returns the ShipperNumber field if non-nil, zero value otherwise.

### GetShipperNumberOk

`func (o *CustomerShippersApiUpdateShipperResponse) GetShipperNumberOk() (*string, bool)`

GetShipperNumberOk returns a tuple with the ShipperNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipperNumber

`func (o *CustomerShippersApiUpdateShipperResponse) SetShipperNumber(v string)`

SetShipperNumber sets ShipperNumber field to given value.

### HasShipperNumber

`func (o *CustomerShippersApiUpdateShipperResponse) HasShipperNumber() bool`

HasShipperNumber returns a boolean if a field has been set.

### GetCustomerId

`func (o *CustomerShippersApiUpdateShipperResponse) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *CustomerShippersApiUpdateShipperResponse) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *CustomerShippersApiUpdateShipperResponse) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *CustomerShippersApiUpdateShipperResponse) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### GetCustomerAddressId

`func (o *CustomerShippersApiUpdateShipperResponse) GetCustomerAddressId() string`

GetCustomerAddressId returns the CustomerAddressId field if non-nil, zero value otherwise.

### GetCustomerAddressIdOk

`func (o *CustomerShippersApiUpdateShipperResponse) GetCustomerAddressIdOk() (*string, bool)`

GetCustomerAddressIdOk returns a tuple with the CustomerAddressId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerAddressId

`func (o *CustomerShippersApiUpdateShipperResponse) SetCustomerAddressId(v string)`

SetCustomerAddressId sets CustomerAddressId field to given value.

### HasCustomerAddressId

`func (o *CustomerShippersApiUpdateShipperResponse) HasCustomerAddressId() bool`

HasCustomerAddressId returns a boolean if a field has been set.

### GetShipDate

`func (o *CustomerShippersApiUpdateShipperResponse) GetShipDate() time.Time`

GetShipDate returns the ShipDate field if non-nil, zero value otherwise.

### GetShipDateOk

`func (o *CustomerShippersApiUpdateShipperResponse) GetShipDateOk() (*time.Time, bool)`

GetShipDateOk returns a tuple with the ShipDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipDate

`func (o *CustomerShippersApiUpdateShipperResponse) SetShipDate(v time.Time)`

SetShipDate sets ShipDate field to given value.

### HasShipDate

`func (o *CustomerShippersApiUpdateShipperResponse) HasShipDate() bool`

HasShipDate returns a boolean if a field has been set.

### GetShippedById

`func (o *CustomerShippersApiUpdateShipperResponse) GetShippedById() string`

GetShippedById returns the ShippedById field if non-nil, zero value otherwise.

### GetShippedByIdOk

`func (o *CustomerShippersApiUpdateShipperResponse) GetShippedByIdOk() (*string, bool)`

GetShippedByIdOk returns a tuple with the ShippedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippedById

`func (o *CustomerShippersApiUpdateShipperResponse) SetShippedById(v string)`

SetShippedById sets ShippedById field to given value.

### HasShippedById

`func (o *CustomerShippersApiUpdateShipperResponse) HasShippedById() bool`

HasShippedById returns a boolean if a field has been set.

### GetCarrierId

`func (o *CustomerShippersApiUpdateShipperResponse) GetCarrierId() string`

GetCarrierId returns the CarrierId field if non-nil, zero value otherwise.

### GetCarrierIdOk

`func (o *CustomerShippersApiUpdateShipperResponse) GetCarrierIdOk() (*string, bool)`

GetCarrierIdOk returns a tuple with the CarrierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierId

`func (o *CustomerShippersApiUpdateShipperResponse) SetCarrierId(v string)`

SetCarrierId sets CarrierId field to given value.

### HasCarrierId

`func (o *CustomerShippersApiUpdateShipperResponse) HasCarrierId() bool`

HasCarrierId returns a boolean if a field has been set.

### GetFreightTerms

`func (o *CustomerShippersApiUpdateShipperResponse) GetFreightTerms() string`

GetFreightTerms returns the FreightTerms field if non-nil, zero value otherwise.

### GetFreightTermsOk

`func (o *CustomerShippersApiUpdateShipperResponse) GetFreightTermsOk() (*string, bool)`

GetFreightTermsOk returns a tuple with the FreightTerms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFreightTerms

`func (o *CustomerShippersApiUpdateShipperResponse) SetFreightTerms(v string)`

SetFreightTerms sets FreightTerms field to given value.

### HasFreightTerms

`func (o *CustomerShippersApiUpdateShipperResponse) HasFreightTerms() bool`

HasFreightTerms returns a boolean if a field has been set.

### GetStatus

`func (o *CustomerShippersApiUpdateShipperResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CustomerShippersApiUpdateShipperResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CustomerShippersApiUpdateShipperResponse) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *CustomerShippersApiUpdateShipperResponse) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetTrackingNumber

`func (o *CustomerShippersApiUpdateShipperResponse) GetTrackingNumber() string`

GetTrackingNumber returns the TrackingNumber field if non-nil, zero value otherwise.

### GetTrackingNumberOk

`func (o *CustomerShippersApiUpdateShipperResponse) GetTrackingNumberOk() (*string, bool)`

GetTrackingNumberOk returns a tuple with the TrackingNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackingNumber

`func (o *CustomerShippersApiUpdateShipperResponse) SetTrackingNumber(v string)`

SetTrackingNumber sets TrackingNumber field to given value.

### HasTrackingNumber

`func (o *CustomerShippersApiUpdateShipperResponse) HasTrackingNumber() bool`

HasTrackingNumber returns a boolean if a field has been set.

### GetTrailerNumber

`func (o *CustomerShippersApiUpdateShipperResponse) GetTrailerNumber() string`

GetTrailerNumber returns the TrailerNumber field if non-nil, zero value otherwise.

### GetTrailerNumberOk

`func (o *CustomerShippersApiUpdateShipperResponse) GetTrailerNumberOk() (*string, bool)`

GetTrailerNumberOk returns a tuple with the TrailerNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrailerNumber

`func (o *CustomerShippersApiUpdateShipperResponse) SetTrailerNumber(v string)`

SetTrailerNumber sets TrailerNumber field to given value.

### HasTrailerNumber

`func (o *CustomerShippersApiUpdateShipperResponse) HasTrailerNumber() bool`

HasTrailerNumber returns a boolean if a field has been set.

### GetNote

`func (o *CustomerShippersApiUpdateShipperResponse) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *CustomerShippersApiUpdateShipperResponse) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *CustomerShippersApiUpdateShipperResponse) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *CustomerShippersApiUpdateShipperResponse) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetScheduledShipDate

`func (o *CustomerShippersApiUpdateShipperResponse) GetScheduledShipDate() time.Time`

GetScheduledShipDate returns the ScheduledShipDate field if non-nil, zero value otherwise.

### GetScheduledShipDateOk

`func (o *CustomerShippersApiUpdateShipperResponse) GetScheduledShipDateOk() (*time.Time, bool)`

GetScheduledShipDateOk returns a tuple with the ScheduledShipDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScheduledShipDate

`func (o *CustomerShippersApiUpdateShipperResponse) SetScheduledShipDate(v time.Time)`

SetScheduledShipDate sets ScheduledShipDate field to given value.

### HasScheduledShipDate

`func (o *CustomerShippersApiUpdateShipperResponse) HasScheduledShipDate() bool`

HasScheduledShipDate returns a boolean if a field has been set.

### GetCreatedById

`func (o *CustomerShippersApiUpdateShipperResponse) GetCreatedById() string`

GetCreatedById returns the CreatedById field if non-nil, zero value otherwise.

### GetCreatedByIdOk

`func (o *CustomerShippersApiUpdateShipperResponse) GetCreatedByIdOk() (*string, bool)`

GetCreatedByIdOk returns a tuple with the CreatedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedById

`func (o *CustomerShippersApiUpdateShipperResponse) SetCreatedById(v string)`

SetCreatedById sets CreatedById field to given value.

### HasCreatedById

`func (o *CustomerShippersApiUpdateShipperResponse) HasCreatedById() bool`

HasCreatedById returns a boolean if a field has been set.

### GetCreatedDate

`func (o *CustomerShippersApiUpdateShipperResponse) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *CustomerShippersApiUpdateShipperResponse) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *CustomerShippersApiUpdateShipperResponse) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *CustomerShippersApiUpdateShipperResponse) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.

### GetModifiedById

`func (o *CustomerShippersApiUpdateShipperResponse) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *CustomerShippersApiUpdateShipperResponse) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *CustomerShippersApiUpdateShipperResponse) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *CustomerShippersApiUpdateShipperResponse) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetModifiedDate

`func (o *CustomerShippersApiUpdateShipperResponse) GetModifiedDate() time.Time`

GetModifiedDate returns the ModifiedDate field if non-nil, zero value otherwise.

### GetModifiedDateOk

`func (o *CustomerShippersApiUpdateShipperResponse) GetModifiedDateOk() (*time.Time, bool)`

GetModifiedDateOk returns a tuple with the ModifiedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDate

`func (o *CustomerShippersApiUpdateShipperResponse) SetModifiedDate(v time.Time)`

SetModifiedDate sets ModifiedDate field to given value.

### HasModifiedDate

`func (o *CustomerShippersApiUpdateShipperResponse) HasModifiedDate() bool`

HasModifiedDate returns a boolean if a field has been set.

### GetShipperNote

`func (o *CustomerShippersApiUpdateShipperResponse) GetShipperNote() string`

GetShipperNote returns the ShipperNote field if non-nil, zero value otherwise.

### GetShipperNoteOk

`func (o *CustomerShippersApiUpdateShipperResponse) GetShipperNoteOk() (*string, bool)`

GetShipperNoteOk returns a tuple with the ShipperNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipperNote

`func (o *CustomerShippersApiUpdateShipperResponse) SetShipperNote(v string)`

SetShipperNote sets ShipperNote field to given value.

### HasShipperNote

`func (o *CustomerShippersApiUpdateShipperResponse) HasShipperNote() bool`

HasShipperNote returns a boolean if a field has been set.

### GetTruckId

`func (o *CustomerShippersApiUpdateShipperResponse) GetTruckId() string`

GetTruckId returns the TruckId field if non-nil, zero value otherwise.

### GetTruckIdOk

`func (o *CustomerShippersApiUpdateShipperResponse) GetTruckIdOk() (*string, bool)`

GetTruckIdOk returns a tuple with the TruckId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckId

`func (o *CustomerShippersApiUpdateShipperResponse) SetTruckId(v string)`

SetTruckId sets TruckId field to given value.

### HasTruckId

`func (o *CustomerShippersApiUpdateShipperResponse) HasTruckId() bool`

HasTruckId returns a boolean if a field has been set.

### GetExpediteNote

`func (o *CustomerShippersApiUpdateShipperResponse) GetExpediteNote() string`

GetExpediteNote returns the ExpediteNote field if non-nil, zero value otherwise.

### GetExpediteNoteOk

`func (o *CustomerShippersApiUpdateShipperResponse) GetExpediteNoteOk() (*string, bool)`

GetExpediteNoteOk returns a tuple with the ExpediteNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpediteNote

`func (o *CustomerShippersApiUpdateShipperResponse) SetExpediteNote(v string)`

SetExpediteNote sets ExpediteNote field to given value.

### HasExpediteNote

`func (o *CustomerShippersApiUpdateShipperResponse) HasExpediteNote() bool`

HasExpediteNote returns a boolean if a field has been set.

### GetExpediteReason

`func (o *CustomerShippersApiUpdateShipperResponse) GetExpediteReason() string`

GetExpediteReason returns the ExpediteReason field if non-nil, zero value otherwise.

### GetExpediteReasonOk

`func (o *CustomerShippersApiUpdateShipperResponse) GetExpediteReasonOk() (*string, bool)`

GetExpediteReasonOk returns a tuple with the ExpediteReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpediteReason

`func (o *CustomerShippersApiUpdateShipperResponse) SetExpediteReason(v string)`

SetExpediteReason sets ExpediteReason field to given value.

### HasExpediteReason

`func (o *CustomerShippersApiUpdateShipperResponse) HasExpediteReason() bool`

HasExpediteReason returns a boolean if a field has been set.

### GetExpediteDepartment

`func (o *CustomerShippersApiUpdateShipperResponse) GetExpediteDepartment() string`

GetExpediteDepartment returns the ExpediteDepartment field if non-nil, zero value otherwise.

### GetExpediteDepartmentOk

`func (o *CustomerShippersApiUpdateShipperResponse) GetExpediteDepartmentOk() (*string, bool)`

GetExpediteDepartmentOk returns a tuple with the ExpediteDepartment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpediteDepartment

`func (o *CustomerShippersApiUpdateShipperResponse) SetExpediteDepartment(v string)`

SetExpediteDepartment sets ExpediteDepartment field to given value.

### HasExpediteDepartment

`func (o *CustomerShippersApiUpdateShipperResponse) HasExpediteDepartment() bool`

HasExpediteDepartment returns a boolean if a field has been set.

### GetExpediteAuthorizedById

`func (o *CustomerShippersApiUpdateShipperResponse) GetExpediteAuthorizedById() string`

GetExpediteAuthorizedById returns the ExpediteAuthorizedById field if non-nil, zero value otherwise.

### GetExpediteAuthorizedByIdOk

`func (o *CustomerShippersApiUpdateShipperResponse) GetExpediteAuthorizedByIdOk() (*string, bool)`

GetExpediteAuthorizedByIdOk returns a tuple with the ExpediteAuthorizedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpediteAuthorizedById

`func (o *CustomerShippersApiUpdateShipperResponse) SetExpediteAuthorizedById(v string)`

SetExpediteAuthorizedById sets ExpediteAuthorizedById field to given value.

### HasExpediteAuthorizedById

`func (o *CustomerShippersApiUpdateShipperResponse) HasExpediteAuthorizedById() bool`

HasExpediteAuthorizedById returns a boolean if a field has been set.

### GetExpediteAdditionalCost

`func (o *CustomerShippersApiUpdateShipperResponse) GetExpediteAdditionalCost() float64`

GetExpediteAdditionalCost returns the ExpediteAdditionalCost field if non-nil, zero value otherwise.

### GetExpediteAdditionalCostOk

`func (o *CustomerShippersApiUpdateShipperResponse) GetExpediteAdditionalCostOk() (*float64, bool)`

GetExpediteAdditionalCostOk returns a tuple with the ExpediteAdditionalCost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpediteAdditionalCost

`func (o *CustomerShippersApiUpdateShipperResponse) SetExpediteAdditionalCost(v float64)`

SetExpediteAdditionalCost sets ExpediteAdditionalCost field to given value.

### HasExpediteAdditionalCost

`func (o *CustomerShippersApiUpdateShipperResponse) HasExpediteAdditionalCost() bool`

HasExpediteAdditionalCost returns a boolean if a field has been set.

### GetShipFromCode

`func (o *CustomerShippersApiUpdateShipperResponse) GetShipFromCode() string`

GetShipFromCode returns the ShipFromCode field if non-nil, zero value otherwise.

### GetShipFromCodeOk

`func (o *CustomerShippersApiUpdateShipperResponse) GetShipFromCodeOk() (*string, bool)`

GetShipFromCodeOk returns a tuple with the ShipFromCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipFromCode

`func (o *CustomerShippersApiUpdateShipperResponse) SetShipFromCode(v string)`

SetShipFromCode sets ShipFromCode field to given value.

### HasShipFromCode

`func (o *CustomerShippersApiUpdateShipperResponse) HasShipFromCode() bool`

HasShipFromCode returns a boolean if a field has been set.

### GetTruckArrivalTime

`func (o *CustomerShippersApiUpdateShipperResponse) GetTruckArrivalTime() time.Time`

GetTruckArrivalTime returns the TruckArrivalTime field if non-nil, zero value otherwise.

### GetTruckArrivalTimeOk

`func (o *CustomerShippersApiUpdateShipperResponse) GetTruckArrivalTimeOk() (*time.Time, bool)`

GetTruckArrivalTimeOk returns a tuple with the TruckArrivalTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckArrivalTime

`func (o *CustomerShippersApiUpdateShipperResponse) SetTruckArrivalTime(v time.Time)`

SetTruckArrivalTime sets TruckArrivalTime field to given value.

### HasTruckArrivalTime

`func (o *CustomerShippersApiUpdateShipperResponse) HasTruckArrivalTime() bool`

HasTruckArrivalTime returns a boolean if a field has been set.

### GetPrintedById

`func (o *CustomerShippersApiUpdateShipperResponse) GetPrintedById() string`

GetPrintedById returns the PrintedById field if non-nil, zero value otherwise.

### GetPrintedByIdOk

`func (o *CustomerShippersApiUpdateShipperResponse) GetPrintedByIdOk() (*string, bool)`

GetPrintedByIdOk returns a tuple with the PrintedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrintedById

`func (o *CustomerShippersApiUpdateShipperResponse) SetPrintedById(v string)`

SetPrintedById sets PrintedById field to given value.

### HasPrintedById

`func (o *CustomerShippersApiUpdateShipperResponse) HasPrintedById() bool`

HasPrintedById returns a boolean if a field has been set.

### GetPrintedDate

`func (o *CustomerShippersApiUpdateShipperResponse) GetPrintedDate() time.Time`

GetPrintedDate returns the PrintedDate field if non-nil, zero value otherwise.

### GetPrintedDateOk

`func (o *CustomerShippersApiUpdateShipperResponse) GetPrintedDateOk() (*time.Time, bool)`

GetPrintedDateOk returns a tuple with the PrintedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrintedDate

`func (o *CustomerShippersApiUpdateShipperResponse) SetPrintedDate(v time.Time)`

SetPrintedDate sets PrintedDate field to given value.

### HasPrintedDate

`func (o *CustomerShippersApiUpdateShipperResponse) HasPrintedDate() bool`

HasPrintedDate returns a boolean if a field has been set.

### GetFreightAmount

`func (o *CustomerShippersApiUpdateShipperResponse) GetFreightAmount() float64`

GetFreightAmount returns the FreightAmount field if non-nil, zero value otherwise.

### GetFreightAmountOk

`func (o *CustomerShippersApiUpdateShipperResponse) GetFreightAmountOk() (*float64, bool)`

GetFreightAmountOk returns a tuple with the FreightAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFreightAmount

`func (o *CustomerShippersApiUpdateShipperResponse) SetFreightAmount(v float64)`

SetFreightAmount sets FreightAmount field to given value.

### HasFreightAmount

`func (o *CustomerShippersApiUpdateShipperResponse) HasFreightAmount() bool`

HasFreightAmount returns a boolean if a field has been set.

### GetBolNote

`func (o *CustomerShippersApiUpdateShipperResponse) GetBolNote() string`

GetBolNote returns the BolNote field if non-nil, zero value otherwise.

### GetBolNoteOk

`func (o *CustomerShippersApiUpdateShipperResponse) GetBolNoteOk() (*string, bool)`

GetBolNoteOk returns a tuple with the BolNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBolNote

`func (o *CustomerShippersApiUpdateShipperResponse) SetBolNote(v string)`

SetBolNote sets BolNote field to given value.

### HasBolNote

`func (o *CustomerShippersApiUpdateShipperResponse) HasBolNote() bool`

HasBolNote returns a boolean if a field has been set.

### GetCustomsExporter

`func (o *CustomerShippersApiUpdateShipperResponse) GetCustomsExporter() string`

GetCustomsExporter returns the CustomsExporter field if non-nil, zero value otherwise.

### GetCustomsExporterOk

`func (o *CustomerShippersApiUpdateShipperResponse) GetCustomsExporterOk() (*string, bool)`

GetCustomsExporterOk returns a tuple with the CustomsExporter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomsExporter

`func (o *CustomerShippersApiUpdateShipperResponse) SetCustomsExporter(v string)`

SetCustomsExporter sets CustomsExporter field to given value.

### HasCustomsExporter

`func (o *CustomerShippersApiUpdateShipperResponse) HasCustomsExporter() bool`

HasCustomsExporter returns a boolean if a field has been set.

### GetDeliveryDateTime

`func (o *CustomerShippersApiUpdateShipperResponse) GetDeliveryDateTime() time.Time`

GetDeliveryDateTime returns the DeliveryDateTime field if non-nil, zero value otherwise.

### GetDeliveryDateTimeOk

`func (o *CustomerShippersApiUpdateShipperResponse) GetDeliveryDateTimeOk() (*time.Time, bool)`

GetDeliveryDateTimeOk returns a tuple with the DeliveryDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliveryDateTime

`func (o *CustomerShippersApiUpdateShipperResponse) SetDeliveryDateTime(v time.Time)`

SetDeliveryDateTime sets DeliveryDateTime field to given value.

### HasDeliveryDateTime

`func (o *CustomerShippersApiUpdateShipperResponse) HasDeliveryDateTime() bool`

HasDeliveryDateTime returns a boolean if a field has been set.

### GetDropshipSupplierCode

`func (o *CustomerShippersApiUpdateShipperResponse) GetDropshipSupplierCode() string`

GetDropshipSupplierCode returns the DropshipSupplierCode field if non-nil, zero value otherwise.

### GetDropshipSupplierCodeOk

`func (o *CustomerShippersApiUpdateShipperResponse) GetDropshipSupplierCodeOk() (*string, bool)`

GetDropshipSupplierCodeOk returns a tuple with the DropshipSupplierCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDropshipSupplierCode

`func (o *CustomerShippersApiUpdateShipperResponse) SetDropshipSupplierCode(v string)`

SetDropshipSupplierCode sets DropshipSupplierCode field to given value.

### HasDropshipSupplierCode

`func (o *CustomerShippersApiUpdateShipperResponse) HasDropshipSupplierCode() bool`

HasDropshipSupplierCode returns a boolean if a field has been set.

### GetDropshipSupplierId

`func (o *CustomerShippersApiUpdateShipperResponse) GetDropshipSupplierId() string`

GetDropshipSupplierId returns the DropshipSupplierId field if non-nil, zero value otherwise.

### GetDropshipSupplierIdOk

`func (o *CustomerShippersApiUpdateShipperResponse) GetDropshipSupplierIdOk() (*string, bool)`

GetDropshipSupplierIdOk returns a tuple with the DropshipSupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDropshipSupplierId

`func (o *CustomerShippersApiUpdateShipperResponse) SetDropshipSupplierId(v string)`

SetDropshipSupplierId sets DropshipSupplierId field to given value.

### HasDropshipSupplierId

`func (o *CustomerShippersApiUpdateShipperResponse) HasDropshipSupplierId() bool`

HasDropshipSupplierId returns a boolean if a field has been set.

### GetShipperChargeAmount

`func (o *CustomerShippersApiUpdateShipperResponse) GetShipperChargeAmount() float64`

GetShipperChargeAmount returns the ShipperChargeAmount field if non-nil, zero value otherwise.

### GetShipperChargeAmountOk

`func (o *CustomerShippersApiUpdateShipperResponse) GetShipperChargeAmountOk() (*float64, bool)`

GetShipperChargeAmountOk returns a tuple with the ShipperChargeAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipperChargeAmount

`func (o *CustomerShippersApiUpdateShipperResponse) SetShipperChargeAmount(v float64)`

SetShipperChargeAmount sets ShipperChargeAmount field to given value.

### HasShipperChargeAmount

`func (o *CustomerShippersApiUpdateShipperResponse) HasShipperChargeAmount() bool`

HasShipperChargeAmount returns a boolean if a field has been set.

### GetMasterBolNo

`func (o *CustomerShippersApiUpdateShipperResponse) GetMasterBolNo() string`

GetMasterBolNo returns the MasterBolNo field if non-nil, zero value otherwise.

### GetMasterBolNoOk

`func (o *CustomerShippersApiUpdateShipperResponse) GetMasterBolNoOk() (*string, bool)`

GetMasterBolNoOk returns a tuple with the MasterBolNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMasterBolNo

`func (o *CustomerShippersApiUpdateShipperResponse) SetMasterBolNo(v string)`

SetMasterBolNo sets MasterBolNo field to given value.

### HasMasterBolNo

`func (o *CustomerShippersApiUpdateShipperResponse) HasMasterBolNo() bool`

HasMasterBolNo returns a boolean if a field has been set.

### GetPallets

`func (o *CustomerShippersApiUpdateShipperResponse) GetPallets() int32`

GetPallets returns the Pallets field if non-nil, zero value otherwise.

### GetPalletsOk

`func (o *CustomerShippersApiUpdateShipperResponse) GetPalletsOk() (*int32, bool)`

GetPalletsOk returns a tuple with the Pallets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPallets

`func (o *CustomerShippersApiUpdateShipperResponse) SetPallets(v int32)`

SetPallets sets Pallets field to given value.

### HasPallets

`func (o *CustomerShippersApiUpdateShipperResponse) HasPallets() bool`

HasPallets returns a boolean if a field has been set.

### GetPremiumTransAuth

`func (o *CustomerShippersApiUpdateShipperResponse) GetPremiumTransAuth() string`

GetPremiumTransAuth returns the PremiumTransAuth field if non-nil, zero value otherwise.

### GetPremiumTransAuthOk

`func (o *CustomerShippersApiUpdateShipperResponse) GetPremiumTransAuthOk() (*string, bool)`

GetPremiumTransAuthOk returns a tuple with the PremiumTransAuth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPremiumTransAuth

`func (o *CustomerShippersApiUpdateShipperResponse) SetPremiumTransAuth(v string)`

SetPremiumTransAuth sets PremiumTransAuth field to given value.

### HasPremiumTransAuth

`func (o *CustomerShippersApiUpdateShipperResponse) HasPremiumTransAuth() bool`

HasPremiumTransAuth returns a boolean if a field has been set.

### GetTruckConfirmation

`func (o *CustomerShippersApiUpdateShipperResponse) GetTruckConfirmation() string`

GetTruckConfirmation returns the TruckConfirmation field if non-nil, zero value otherwise.

### GetTruckConfirmationOk

`func (o *CustomerShippersApiUpdateShipperResponse) GetTruckConfirmationOk() (*string, bool)`

GetTruckConfirmationOk returns a tuple with the TruckConfirmation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckConfirmation

`func (o *CustomerShippersApiUpdateShipperResponse) SetTruckConfirmation(v string)`

SetTruckConfirmation sets TruckConfirmation field to given value.

### HasTruckConfirmation

`func (o *CustomerShippersApiUpdateShipperResponse) HasTruckConfirmation() bool`

HasTruckConfirmation returns a boolean if a field has been set.

### GetTruckCalledDate

`func (o *CustomerShippersApiUpdateShipperResponse) GetTruckCalledDate() string`

GetTruckCalledDate returns the TruckCalledDate field if non-nil, zero value otherwise.

### GetTruckCalledDateOk

`func (o *CustomerShippersApiUpdateShipperResponse) GetTruckCalledDateOk() (*string, bool)`

GetTruckCalledDateOk returns a tuple with the TruckCalledDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckCalledDate

`func (o *CustomerShippersApiUpdateShipperResponse) SetTruckCalledDate(v string)`

SetTruckCalledDate sets TruckCalledDate field to given value.

### HasTruckCalledDate

`func (o *CustomerShippersApiUpdateShipperResponse) HasTruckCalledDate() bool`

HasTruckCalledDate returns a boolean if a field has been set.

### GetGrossWeightOverride

`func (o *CustomerShippersApiUpdateShipperResponse) GetGrossWeightOverride() float64`

GetGrossWeightOverride returns the GrossWeightOverride field if non-nil, zero value otherwise.

### GetGrossWeightOverrideOk

`func (o *CustomerShippersApiUpdateShipperResponse) GetGrossWeightOverrideOk() (*float64, bool)`

GetGrossWeightOverrideOk returns a tuple with the GrossWeightOverride field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrossWeightOverride

`func (o *CustomerShippersApiUpdateShipperResponse) SetGrossWeightOverride(v float64)`

SetGrossWeightOverride sets GrossWeightOverride field to given value.

### HasGrossWeightOverride

`func (o *CustomerShippersApiUpdateShipperResponse) HasGrossWeightOverride() bool`

HasGrossWeightOverride returns a boolean if a field has been set.

### GetMrn

`func (o *CustomerShippersApiUpdateShipperResponse) GetMrn() string`

GetMrn returns the Mrn field if non-nil, zero value otherwise.

### GetMrnOk

`func (o *CustomerShippersApiUpdateShipperResponse) GetMrnOk() (*string, bool)`

GetMrnOk returns a tuple with the Mrn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMrn

`func (o *CustomerShippersApiUpdateShipperResponse) SetMrn(v string)`

SetMrn sets Mrn field to given value.

### HasMrn

`func (o *CustomerShippersApiUpdateShipperResponse) HasMrn() bool`

HasMrn returns a boolean if a field has been set.

### GetMrnDate

`func (o *CustomerShippersApiUpdateShipperResponse) GetMrnDate() string`

GetMrnDate returns the MrnDate field if non-nil, zero value otherwise.

### GetMrnDateOk

`func (o *CustomerShippersApiUpdateShipperResponse) GetMrnDateOk() (*string, bool)`

GetMrnDateOk returns a tuple with the MrnDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMrnDate

`func (o *CustomerShippersApiUpdateShipperResponse) SetMrnDate(v string)`

SetMrnDate sets MrnDate field to given value.

### HasMrnDate

`func (o *CustomerShippersApiUpdateShipperResponse) HasMrnDate() bool`

HasMrnDate returns a boolean if a field has been set.

### GetMrnType

`func (o *CustomerShippersApiUpdateShipperResponse) GetMrnType() string`

GetMrnType returns the MrnType field if non-nil, zero value otherwise.

### GetMrnTypeOk

`func (o *CustomerShippersApiUpdateShipperResponse) GetMrnTypeOk() (*string, bool)`

GetMrnTypeOk returns a tuple with the MrnType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMrnType

`func (o *CustomerShippersApiUpdateShipperResponse) SetMrnType(v string)`

SetMrnType sets MrnType field to given value.

### HasMrnType

`func (o *CustomerShippersApiUpdateShipperResponse) HasMrnType() bool`

HasMrnType returns a boolean if a field has been set.

### GetRoutingAuthorizationNumber

`func (o *CustomerShippersApiUpdateShipperResponse) GetRoutingAuthorizationNumber() string`

GetRoutingAuthorizationNumber returns the RoutingAuthorizationNumber field if non-nil, zero value otherwise.

### GetRoutingAuthorizationNumberOk

`func (o *CustomerShippersApiUpdateShipperResponse) GetRoutingAuthorizationNumberOk() (*string, bool)`

GetRoutingAuthorizationNumberOk returns a tuple with the RoutingAuthorizationNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoutingAuthorizationNumber

`func (o *CustomerShippersApiUpdateShipperResponse) SetRoutingAuthorizationNumber(v string)`

SetRoutingAuthorizationNumber sets RoutingAuthorizationNumber field to given value.

### HasRoutingAuthorizationNumber

`func (o *CustomerShippersApiUpdateShipperResponse) HasRoutingAuthorizationNumber() bool`

HasRoutingAuthorizationNumber returns a boolean if a field has been set.

### GetShipperWeight

`func (o *CustomerShippersApiUpdateShipperResponse) GetShipperWeight() float64`

GetShipperWeight returns the ShipperWeight field if non-nil, zero value otherwise.

### GetShipperWeightOk

`func (o *CustomerShippersApiUpdateShipperResponse) GetShipperWeightOk() (*float64, bool)`

GetShipperWeightOk returns a tuple with the ShipperWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipperWeight

`func (o *CustomerShippersApiUpdateShipperResponse) SetShipperWeight(v float64)`

SetShipperWeight sets ShipperWeight field to given value.

### HasShipperWeight

`func (o *CustomerShippersApiUpdateShipperResponse) HasShipperWeight() bool`

HasShipperWeight returns a boolean if a field has been set.

### GetPickListPrintedDateTime

`func (o *CustomerShippersApiUpdateShipperResponse) GetPickListPrintedDateTime() time.Time`

GetPickListPrintedDateTime returns the PickListPrintedDateTime field if non-nil, zero value otherwise.

### GetPickListPrintedDateTimeOk

`func (o *CustomerShippersApiUpdateShipperResponse) GetPickListPrintedDateTimeOk() (*time.Time, bool)`

GetPickListPrintedDateTimeOk returns a tuple with the PickListPrintedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPickListPrintedDateTime

`func (o *CustomerShippersApiUpdateShipperResponse) SetPickListPrintedDateTime(v time.Time)`

SetPickListPrintedDateTime sets PickListPrintedDateTime field to given value.

### HasPickListPrintedDateTime

`func (o *CustomerShippersApiUpdateShipperResponse) HasPickListPrintedDateTime() bool`

HasPickListPrintedDateTime returns a boolean if a field has been set.

### GetTruckArrivalTimeOfDay

`func (o *CustomerShippersApiUpdateShipperResponse) GetTruckArrivalTimeOfDay() string`

GetTruckArrivalTimeOfDay returns the TruckArrivalTimeOfDay field if non-nil, zero value otherwise.

### GetTruckArrivalTimeOfDayOk

`func (o *CustomerShippersApiUpdateShipperResponse) GetTruckArrivalTimeOfDayOk() (*string, bool)`

GetTruckArrivalTimeOfDayOk returns a tuple with the TruckArrivalTimeOfDay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckArrivalTimeOfDay

`func (o *CustomerShippersApiUpdateShipperResponse) SetTruckArrivalTimeOfDay(v string)`

SetTruckArrivalTimeOfDay sets TruckArrivalTimeOfDay field to given value.

### HasTruckArrivalTimeOfDay

`func (o *CustomerShippersApiUpdateShipperResponse) HasTruckArrivalTimeOfDay() bool`

HasTruckArrivalTimeOfDay returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


