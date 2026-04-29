# CustomerShippersApiListCustomerShippersItem

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

### NewCustomerShippersApiListCustomerShippersItem

`func NewCustomerShippersApiListCustomerShippersItem() *CustomerShippersApiListCustomerShippersItem`

NewCustomerShippersApiListCustomerShippersItem instantiates a new CustomerShippersApiListCustomerShippersItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomerShippersApiListCustomerShippersItemWithDefaults

`func NewCustomerShippersApiListCustomerShippersItemWithDefaults() *CustomerShippersApiListCustomerShippersItem`

NewCustomerShippersApiListCustomerShippersItemWithDefaults instantiates a new CustomerShippersApiListCustomerShippersItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CustomerShippersApiListCustomerShippersItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CustomerShippersApiListCustomerShippersItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CustomerShippersApiListCustomerShippersItem) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *CustomerShippersApiListCustomerShippersItem) HasId() bool`

HasId returns a boolean if a field has been set.

### GetShipperNumber

`func (o *CustomerShippersApiListCustomerShippersItem) GetShipperNumber() string`

GetShipperNumber returns the ShipperNumber field if non-nil, zero value otherwise.

### GetShipperNumberOk

`func (o *CustomerShippersApiListCustomerShippersItem) GetShipperNumberOk() (*string, bool)`

GetShipperNumberOk returns a tuple with the ShipperNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipperNumber

`func (o *CustomerShippersApiListCustomerShippersItem) SetShipperNumber(v string)`

SetShipperNumber sets ShipperNumber field to given value.

### HasShipperNumber

`func (o *CustomerShippersApiListCustomerShippersItem) HasShipperNumber() bool`

HasShipperNumber returns a boolean if a field has been set.

### GetCustomerId

`func (o *CustomerShippersApiListCustomerShippersItem) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *CustomerShippersApiListCustomerShippersItem) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *CustomerShippersApiListCustomerShippersItem) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *CustomerShippersApiListCustomerShippersItem) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### GetCustomerAddressId

`func (o *CustomerShippersApiListCustomerShippersItem) GetCustomerAddressId() string`

GetCustomerAddressId returns the CustomerAddressId field if non-nil, zero value otherwise.

### GetCustomerAddressIdOk

`func (o *CustomerShippersApiListCustomerShippersItem) GetCustomerAddressIdOk() (*string, bool)`

GetCustomerAddressIdOk returns a tuple with the CustomerAddressId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerAddressId

`func (o *CustomerShippersApiListCustomerShippersItem) SetCustomerAddressId(v string)`

SetCustomerAddressId sets CustomerAddressId field to given value.

### HasCustomerAddressId

`func (o *CustomerShippersApiListCustomerShippersItem) HasCustomerAddressId() bool`

HasCustomerAddressId returns a boolean if a field has been set.

### GetShipDate

`func (o *CustomerShippersApiListCustomerShippersItem) GetShipDate() time.Time`

GetShipDate returns the ShipDate field if non-nil, zero value otherwise.

### GetShipDateOk

`func (o *CustomerShippersApiListCustomerShippersItem) GetShipDateOk() (*time.Time, bool)`

GetShipDateOk returns a tuple with the ShipDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipDate

`func (o *CustomerShippersApiListCustomerShippersItem) SetShipDate(v time.Time)`

SetShipDate sets ShipDate field to given value.

### HasShipDate

`func (o *CustomerShippersApiListCustomerShippersItem) HasShipDate() bool`

HasShipDate returns a boolean if a field has been set.

### GetShippedById

`func (o *CustomerShippersApiListCustomerShippersItem) GetShippedById() string`

GetShippedById returns the ShippedById field if non-nil, zero value otherwise.

### GetShippedByIdOk

`func (o *CustomerShippersApiListCustomerShippersItem) GetShippedByIdOk() (*string, bool)`

GetShippedByIdOk returns a tuple with the ShippedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippedById

`func (o *CustomerShippersApiListCustomerShippersItem) SetShippedById(v string)`

SetShippedById sets ShippedById field to given value.

### HasShippedById

`func (o *CustomerShippersApiListCustomerShippersItem) HasShippedById() bool`

HasShippedById returns a boolean if a field has been set.

### GetCarrierId

`func (o *CustomerShippersApiListCustomerShippersItem) GetCarrierId() string`

GetCarrierId returns the CarrierId field if non-nil, zero value otherwise.

### GetCarrierIdOk

`func (o *CustomerShippersApiListCustomerShippersItem) GetCarrierIdOk() (*string, bool)`

GetCarrierIdOk returns a tuple with the CarrierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierId

`func (o *CustomerShippersApiListCustomerShippersItem) SetCarrierId(v string)`

SetCarrierId sets CarrierId field to given value.

### HasCarrierId

`func (o *CustomerShippersApiListCustomerShippersItem) HasCarrierId() bool`

HasCarrierId returns a boolean if a field has been set.

### GetFreightTerms

`func (o *CustomerShippersApiListCustomerShippersItem) GetFreightTerms() string`

GetFreightTerms returns the FreightTerms field if non-nil, zero value otherwise.

### GetFreightTermsOk

`func (o *CustomerShippersApiListCustomerShippersItem) GetFreightTermsOk() (*string, bool)`

GetFreightTermsOk returns a tuple with the FreightTerms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFreightTerms

`func (o *CustomerShippersApiListCustomerShippersItem) SetFreightTerms(v string)`

SetFreightTerms sets FreightTerms field to given value.

### HasFreightTerms

`func (o *CustomerShippersApiListCustomerShippersItem) HasFreightTerms() bool`

HasFreightTerms returns a boolean if a field has been set.

### GetStatus

`func (o *CustomerShippersApiListCustomerShippersItem) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CustomerShippersApiListCustomerShippersItem) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CustomerShippersApiListCustomerShippersItem) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *CustomerShippersApiListCustomerShippersItem) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetTrackingNumber

`func (o *CustomerShippersApiListCustomerShippersItem) GetTrackingNumber() string`

GetTrackingNumber returns the TrackingNumber field if non-nil, zero value otherwise.

### GetTrackingNumberOk

`func (o *CustomerShippersApiListCustomerShippersItem) GetTrackingNumberOk() (*string, bool)`

GetTrackingNumberOk returns a tuple with the TrackingNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackingNumber

`func (o *CustomerShippersApiListCustomerShippersItem) SetTrackingNumber(v string)`

SetTrackingNumber sets TrackingNumber field to given value.

### HasTrackingNumber

`func (o *CustomerShippersApiListCustomerShippersItem) HasTrackingNumber() bool`

HasTrackingNumber returns a boolean if a field has been set.

### GetTrailerNumber

`func (o *CustomerShippersApiListCustomerShippersItem) GetTrailerNumber() string`

GetTrailerNumber returns the TrailerNumber field if non-nil, zero value otherwise.

### GetTrailerNumberOk

`func (o *CustomerShippersApiListCustomerShippersItem) GetTrailerNumberOk() (*string, bool)`

GetTrailerNumberOk returns a tuple with the TrailerNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrailerNumber

`func (o *CustomerShippersApiListCustomerShippersItem) SetTrailerNumber(v string)`

SetTrailerNumber sets TrailerNumber field to given value.

### HasTrailerNumber

`func (o *CustomerShippersApiListCustomerShippersItem) HasTrailerNumber() bool`

HasTrailerNumber returns a boolean if a field has been set.

### GetNote

`func (o *CustomerShippersApiListCustomerShippersItem) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *CustomerShippersApiListCustomerShippersItem) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *CustomerShippersApiListCustomerShippersItem) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *CustomerShippersApiListCustomerShippersItem) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetScheduledShipDate

`func (o *CustomerShippersApiListCustomerShippersItem) GetScheduledShipDate() time.Time`

GetScheduledShipDate returns the ScheduledShipDate field if non-nil, zero value otherwise.

### GetScheduledShipDateOk

`func (o *CustomerShippersApiListCustomerShippersItem) GetScheduledShipDateOk() (*time.Time, bool)`

GetScheduledShipDateOk returns a tuple with the ScheduledShipDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScheduledShipDate

`func (o *CustomerShippersApiListCustomerShippersItem) SetScheduledShipDate(v time.Time)`

SetScheduledShipDate sets ScheduledShipDate field to given value.

### HasScheduledShipDate

`func (o *CustomerShippersApiListCustomerShippersItem) HasScheduledShipDate() bool`

HasScheduledShipDate returns a boolean if a field has been set.

### GetCreatedById

`func (o *CustomerShippersApiListCustomerShippersItem) GetCreatedById() string`

GetCreatedById returns the CreatedById field if non-nil, zero value otherwise.

### GetCreatedByIdOk

`func (o *CustomerShippersApiListCustomerShippersItem) GetCreatedByIdOk() (*string, bool)`

GetCreatedByIdOk returns a tuple with the CreatedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedById

`func (o *CustomerShippersApiListCustomerShippersItem) SetCreatedById(v string)`

SetCreatedById sets CreatedById field to given value.

### HasCreatedById

`func (o *CustomerShippersApiListCustomerShippersItem) HasCreatedById() bool`

HasCreatedById returns a boolean if a field has been set.

### GetCreatedDate

`func (o *CustomerShippersApiListCustomerShippersItem) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *CustomerShippersApiListCustomerShippersItem) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *CustomerShippersApiListCustomerShippersItem) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *CustomerShippersApiListCustomerShippersItem) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.

### GetModifiedById

`func (o *CustomerShippersApiListCustomerShippersItem) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *CustomerShippersApiListCustomerShippersItem) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *CustomerShippersApiListCustomerShippersItem) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *CustomerShippersApiListCustomerShippersItem) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetModifiedDate

`func (o *CustomerShippersApiListCustomerShippersItem) GetModifiedDate() time.Time`

GetModifiedDate returns the ModifiedDate field if non-nil, zero value otherwise.

### GetModifiedDateOk

`func (o *CustomerShippersApiListCustomerShippersItem) GetModifiedDateOk() (*time.Time, bool)`

GetModifiedDateOk returns a tuple with the ModifiedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDate

`func (o *CustomerShippersApiListCustomerShippersItem) SetModifiedDate(v time.Time)`

SetModifiedDate sets ModifiedDate field to given value.

### HasModifiedDate

`func (o *CustomerShippersApiListCustomerShippersItem) HasModifiedDate() bool`

HasModifiedDate returns a boolean if a field has been set.

### GetShipperNote

`func (o *CustomerShippersApiListCustomerShippersItem) GetShipperNote() string`

GetShipperNote returns the ShipperNote field if non-nil, zero value otherwise.

### GetShipperNoteOk

`func (o *CustomerShippersApiListCustomerShippersItem) GetShipperNoteOk() (*string, bool)`

GetShipperNoteOk returns a tuple with the ShipperNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipperNote

`func (o *CustomerShippersApiListCustomerShippersItem) SetShipperNote(v string)`

SetShipperNote sets ShipperNote field to given value.

### HasShipperNote

`func (o *CustomerShippersApiListCustomerShippersItem) HasShipperNote() bool`

HasShipperNote returns a boolean if a field has been set.

### GetTruckId

`func (o *CustomerShippersApiListCustomerShippersItem) GetTruckId() string`

GetTruckId returns the TruckId field if non-nil, zero value otherwise.

### GetTruckIdOk

`func (o *CustomerShippersApiListCustomerShippersItem) GetTruckIdOk() (*string, bool)`

GetTruckIdOk returns a tuple with the TruckId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckId

`func (o *CustomerShippersApiListCustomerShippersItem) SetTruckId(v string)`

SetTruckId sets TruckId field to given value.

### HasTruckId

`func (o *CustomerShippersApiListCustomerShippersItem) HasTruckId() bool`

HasTruckId returns a boolean if a field has been set.

### GetExpediteNote

`func (o *CustomerShippersApiListCustomerShippersItem) GetExpediteNote() string`

GetExpediteNote returns the ExpediteNote field if non-nil, zero value otherwise.

### GetExpediteNoteOk

`func (o *CustomerShippersApiListCustomerShippersItem) GetExpediteNoteOk() (*string, bool)`

GetExpediteNoteOk returns a tuple with the ExpediteNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpediteNote

`func (o *CustomerShippersApiListCustomerShippersItem) SetExpediteNote(v string)`

SetExpediteNote sets ExpediteNote field to given value.

### HasExpediteNote

`func (o *CustomerShippersApiListCustomerShippersItem) HasExpediteNote() bool`

HasExpediteNote returns a boolean if a field has been set.

### GetExpediteReason

`func (o *CustomerShippersApiListCustomerShippersItem) GetExpediteReason() string`

GetExpediteReason returns the ExpediteReason field if non-nil, zero value otherwise.

### GetExpediteReasonOk

`func (o *CustomerShippersApiListCustomerShippersItem) GetExpediteReasonOk() (*string, bool)`

GetExpediteReasonOk returns a tuple with the ExpediteReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpediteReason

`func (o *CustomerShippersApiListCustomerShippersItem) SetExpediteReason(v string)`

SetExpediteReason sets ExpediteReason field to given value.

### HasExpediteReason

`func (o *CustomerShippersApiListCustomerShippersItem) HasExpediteReason() bool`

HasExpediteReason returns a boolean if a field has been set.

### GetExpediteDepartment

`func (o *CustomerShippersApiListCustomerShippersItem) GetExpediteDepartment() string`

GetExpediteDepartment returns the ExpediteDepartment field if non-nil, zero value otherwise.

### GetExpediteDepartmentOk

`func (o *CustomerShippersApiListCustomerShippersItem) GetExpediteDepartmentOk() (*string, bool)`

GetExpediteDepartmentOk returns a tuple with the ExpediteDepartment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpediteDepartment

`func (o *CustomerShippersApiListCustomerShippersItem) SetExpediteDepartment(v string)`

SetExpediteDepartment sets ExpediteDepartment field to given value.

### HasExpediteDepartment

`func (o *CustomerShippersApiListCustomerShippersItem) HasExpediteDepartment() bool`

HasExpediteDepartment returns a boolean if a field has been set.

### GetExpediteAuthorizedById

`func (o *CustomerShippersApiListCustomerShippersItem) GetExpediteAuthorizedById() string`

GetExpediteAuthorizedById returns the ExpediteAuthorizedById field if non-nil, zero value otherwise.

### GetExpediteAuthorizedByIdOk

`func (o *CustomerShippersApiListCustomerShippersItem) GetExpediteAuthorizedByIdOk() (*string, bool)`

GetExpediteAuthorizedByIdOk returns a tuple with the ExpediteAuthorizedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpediteAuthorizedById

`func (o *CustomerShippersApiListCustomerShippersItem) SetExpediteAuthorizedById(v string)`

SetExpediteAuthorizedById sets ExpediteAuthorizedById field to given value.

### HasExpediteAuthorizedById

`func (o *CustomerShippersApiListCustomerShippersItem) HasExpediteAuthorizedById() bool`

HasExpediteAuthorizedById returns a boolean if a field has been set.

### GetExpediteAdditionalCost

`func (o *CustomerShippersApiListCustomerShippersItem) GetExpediteAdditionalCost() float64`

GetExpediteAdditionalCost returns the ExpediteAdditionalCost field if non-nil, zero value otherwise.

### GetExpediteAdditionalCostOk

`func (o *CustomerShippersApiListCustomerShippersItem) GetExpediteAdditionalCostOk() (*float64, bool)`

GetExpediteAdditionalCostOk returns a tuple with the ExpediteAdditionalCost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpediteAdditionalCost

`func (o *CustomerShippersApiListCustomerShippersItem) SetExpediteAdditionalCost(v float64)`

SetExpediteAdditionalCost sets ExpediteAdditionalCost field to given value.

### HasExpediteAdditionalCost

`func (o *CustomerShippersApiListCustomerShippersItem) HasExpediteAdditionalCost() bool`

HasExpediteAdditionalCost returns a boolean if a field has been set.

### GetShipFromCode

`func (o *CustomerShippersApiListCustomerShippersItem) GetShipFromCode() string`

GetShipFromCode returns the ShipFromCode field if non-nil, zero value otherwise.

### GetShipFromCodeOk

`func (o *CustomerShippersApiListCustomerShippersItem) GetShipFromCodeOk() (*string, bool)`

GetShipFromCodeOk returns a tuple with the ShipFromCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipFromCode

`func (o *CustomerShippersApiListCustomerShippersItem) SetShipFromCode(v string)`

SetShipFromCode sets ShipFromCode field to given value.

### HasShipFromCode

`func (o *CustomerShippersApiListCustomerShippersItem) HasShipFromCode() bool`

HasShipFromCode returns a boolean if a field has been set.

### GetTruckArrivalTime

`func (o *CustomerShippersApiListCustomerShippersItem) GetTruckArrivalTime() time.Time`

GetTruckArrivalTime returns the TruckArrivalTime field if non-nil, zero value otherwise.

### GetTruckArrivalTimeOk

`func (o *CustomerShippersApiListCustomerShippersItem) GetTruckArrivalTimeOk() (*time.Time, bool)`

GetTruckArrivalTimeOk returns a tuple with the TruckArrivalTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckArrivalTime

`func (o *CustomerShippersApiListCustomerShippersItem) SetTruckArrivalTime(v time.Time)`

SetTruckArrivalTime sets TruckArrivalTime field to given value.

### HasTruckArrivalTime

`func (o *CustomerShippersApiListCustomerShippersItem) HasTruckArrivalTime() bool`

HasTruckArrivalTime returns a boolean if a field has been set.

### GetPrintedById

`func (o *CustomerShippersApiListCustomerShippersItem) GetPrintedById() string`

GetPrintedById returns the PrintedById field if non-nil, zero value otherwise.

### GetPrintedByIdOk

`func (o *CustomerShippersApiListCustomerShippersItem) GetPrintedByIdOk() (*string, bool)`

GetPrintedByIdOk returns a tuple with the PrintedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrintedById

`func (o *CustomerShippersApiListCustomerShippersItem) SetPrintedById(v string)`

SetPrintedById sets PrintedById field to given value.

### HasPrintedById

`func (o *CustomerShippersApiListCustomerShippersItem) HasPrintedById() bool`

HasPrintedById returns a boolean if a field has been set.

### GetPrintedDate

`func (o *CustomerShippersApiListCustomerShippersItem) GetPrintedDate() time.Time`

GetPrintedDate returns the PrintedDate field if non-nil, zero value otherwise.

### GetPrintedDateOk

`func (o *CustomerShippersApiListCustomerShippersItem) GetPrintedDateOk() (*time.Time, bool)`

GetPrintedDateOk returns a tuple with the PrintedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrintedDate

`func (o *CustomerShippersApiListCustomerShippersItem) SetPrintedDate(v time.Time)`

SetPrintedDate sets PrintedDate field to given value.

### HasPrintedDate

`func (o *CustomerShippersApiListCustomerShippersItem) HasPrintedDate() bool`

HasPrintedDate returns a boolean if a field has been set.

### GetFreightAmount

`func (o *CustomerShippersApiListCustomerShippersItem) GetFreightAmount() float64`

GetFreightAmount returns the FreightAmount field if non-nil, zero value otherwise.

### GetFreightAmountOk

`func (o *CustomerShippersApiListCustomerShippersItem) GetFreightAmountOk() (*float64, bool)`

GetFreightAmountOk returns a tuple with the FreightAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFreightAmount

`func (o *CustomerShippersApiListCustomerShippersItem) SetFreightAmount(v float64)`

SetFreightAmount sets FreightAmount field to given value.

### HasFreightAmount

`func (o *CustomerShippersApiListCustomerShippersItem) HasFreightAmount() bool`

HasFreightAmount returns a boolean if a field has been set.

### GetBolNote

`func (o *CustomerShippersApiListCustomerShippersItem) GetBolNote() string`

GetBolNote returns the BolNote field if non-nil, zero value otherwise.

### GetBolNoteOk

`func (o *CustomerShippersApiListCustomerShippersItem) GetBolNoteOk() (*string, bool)`

GetBolNoteOk returns a tuple with the BolNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBolNote

`func (o *CustomerShippersApiListCustomerShippersItem) SetBolNote(v string)`

SetBolNote sets BolNote field to given value.

### HasBolNote

`func (o *CustomerShippersApiListCustomerShippersItem) HasBolNote() bool`

HasBolNote returns a boolean if a field has been set.

### GetCustomsExporter

`func (o *CustomerShippersApiListCustomerShippersItem) GetCustomsExporter() string`

GetCustomsExporter returns the CustomsExporter field if non-nil, zero value otherwise.

### GetCustomsExporterOk

`func (o *CustomerShippersApiListCustomerShippersItem) GetCustomsExporterOk() (*string, bool)`

GetCustomsExporterOk returns a tuple with the CustomsExporter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomsExporter

`func (o *CustomerShippersApiListCustomerShippersItem) SetCustomsExporter(v string)`

SetCustomsExporter sets CustomsExporter field to given value.

### HasCustomsExporter

`func (o *CustomerShippersApiListCustomerShippersItem) HasCustomsExporter() bool`

HasCustomsExporter returns a boolean if a field has been set.

### GetDeliveryDateTime

`func (o *CustomerShippersApiListCustomerShippersItem) GetDeliveryDateTime() time.Time`

GetDeliveryDateTime returns the DeliveryDateTime field if non-nil, zero value otherwise.

### GetDeliveryDateTimeOk

`func (o *CustomerShippersApiListCustomerShippersItem) GetDeliveryDateTimeOk() (*time.Time, bool)`

GetDeliveryDateTimeOk returns a tuple with the DeliveryDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliveryDateTime

`func (o *CustomerShippersApiListCustomerShippersItem) SetDeliveryDateTime(v time.Time)`

SetDeliveryDateTime sets DeliveryDateTime field to given value.

### HasDeliveryDateTime

`func (o *CustomerShippersApiListCustomerShippersItem) HasDeliveryDateTime() bool`

HasDeliveryDateTime returns a boolean if a field has been set.

### GetDropshipSupplierCode

`func (o *CustomerShippersApiListCustomerShippersItem) GetDropshipSupplierCode() string`

GetDropshipSupplierCode returns the DropshipSupplierCode field if non-nil, zero value otherwise.

### GetDropshipSupplierCodeOk

`func (o *CustomerShippersApiListCustomerShippersItem) GetDropshipSupplierCodeOk() (*string, bool)`

GetDropshipSupplierCodeOk returns a tuple with the DropshipSupplierCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDropshipSupplierCode

`func (o *CustomerShippersApiListCustomerShippersItem) SetDropshipSupplierCode(v string)`

SetDropshipSupplierCode sets DropshipSupplierCode field to given value.

### HasDropshipSupplierCode

`func (o *CustomerShippersApiListCustomerShippersItem) HasDropshipSupplierCode() bool`

HasDropshipSupplierCode returns a boolean if a field has been set.

### GetDropshipSupplierId

`func (o *CustomerShippersApiListCustomerShippersItem) GetDropshipSupplierId() string`

GetDropshipSupplierId returns the DropshipSupplierId field if non-nil, zero value otherwise.

### GetDropshipSupplierIdOk

`func (o *CustomerShippersApiListCustomerShippersItem) GetDropshipSupplierIdOk() (*string, bool)`

GetDropshipSupplierIdOk returns a tuple with the DropshipSupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDropshipSupplierId

`func (o *CustomerShippersApiListCustomerShippersItem) SetDropshipSupplierId(v string)`

SetDropshipSupplierId sets DropshipSupplierId field to given value.

### HasDropshipSupplierId

`func (o *CustomerShippersApiListCustomerShippersItem) HasDropshipSupplierId() bool`

HasDropshipSupplierId returns a boolean if a field has been set.

### GetShipperChargeAmount

`func (o *CustomerShippersApiListCustomerShippersItem) GetShipperChargeAmount() float64`

GetShipperChargeAmount returns the ShipperChargeAmount field if non-nil, zero value otherwise.

### GetShipperChargeAmountOk

`func (o *CustomerShippersApiListCustomerShippersItem) GetShipperChargeAmountOk() (*float64, bool)`

GetShipperChargeAmountOk returns a tuple with the ShipperChargeAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipperChargeAmount

`func (o *CustomerShippersApiListCustomerShippersItem) SetShipperChargeAmount(v float64)`

SetShipperChargeAmount sets ShipperChargeAmount field to given value.

### HasShipperChargeAmount

`func (o *CustomerShippersApiListCustomerShippersItem) HasShipperChargeAmount() bool`

HasShipperChargeAmount returns a boolean if a field has been set.

### GetMasterBolNo

`func (o *CustomerShippersApiListCustomerShippersItem) GetMasterBolNo() string`

GetMasterBolNo returns the MasterBolNo field if non-nil, zero value otherwise.

### GetMasterBolNoOk

`func (o *CustomerShippersApiListCustomerShippersItem) GetMasterBolNoOk() (*string, bool)`

GetMasterBolNoOk returns a tuple with the MasterBolNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMasterBolNo

`func (o *CustomerShippersApiListCustomerShippersItem) SetMasterBolNo(v string)`

SetMasterBolNo sets MasterBolNo field to given value.

### HasMasterBolNo

`func (o *CustomerShippersApiListCustomerShippersItem) HasMasterBolNo() bool`

HasMasterBolNo returns a boolean if a field has been set.

### GetPallets

`func (o *CustomerShippersApiListCustomerShippersItem) GetPallets() int32`

GetPallets returns the Pallets field if non-nil, zero value otherwise.

### GetPalletsOk

`func (o *CustomerShippersApiListCustomerShippersItem) GetPalletsOk() (*int32, bool)`

GetPalletsOk returns a tuple with the Pallets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPallets

`func (o *CustomerShippersApiListCustomerShippersItem) SetPallets(v int32)`

SetPallets sets Pallets field to given value.

### HasPallets

`func (o *CustomerShippersApiListCustomerShippersItem) HasPallets() bool`

HasPallets returns a boolean if a field has been set.

### GetPremiumTransAuth

`func (o *CustomerShippersApiListCustomerShippersItem) GetPremiumTransAuth() string`

GetPremiumTransAuth returns the PremiumTransAuth field if non-nil, zero value otherwise.

### GetPremiumTransAuthOk

`func (o *CustomerShippersApiListCustomerShippersItem) GetPremiumTransAuthOk() (*string, bool)`

GetPremiumTransAuthOk returns a tuple with the PremiumTransAuth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPremiumTransAuth

`func (o *CustomerShippersApiListCustomerShippersItem) SetPremiumTransAuth(v string)`

SetPremiumTransAuth sets PremiumTransAuth field to given value.

### HasPremiumTransAuth

`func (o *CustomerShippersApiListCustomerShippersItem) HasPremiumTransAuth() bool`

HasPremiumTransAuth returns a boolean if a field has been set.

### GetTruckConfirmation

`func (o *CustomerShippersApiListCustomerShippersItem) GetTruckConfirmation() string`

GetTruckConfirmation returns the TruckConfirmation field if non-nil, zero value otherwise.

### GetTruckConfirmationOk

`func (o *CustomerShippersApiListCustomerShippersItem) GetTruckConfirmationOk() (*string, bool)`

GetTruckConfirmationOk returns a tuple with the TruckConfirmation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckConfirmation

`func (o *CustomerShippersApiListCustomerShippersItem) SetTruckConfirmation(v string)`

SetTruckConfirmation sets TruckConfirmation field to given value.

### HasTruckConfirmation

`func (o *CustomerShippersApiListCustomerShippersItem) HasTruckConfirmation() bool`

HasTruckConfirmation returns a boolean if a field has been set.

### GetTruckCalledDate

`func (o *CustomerShippersApiListCustomerShippersItem) GetTruckCalledDate() string`

GetTruckCalledDate returns the TruckCalledDate field if non-nil, zero value otherwise.

### GetTruckCalledDateOk

`func (o *CustomerShippersApiListCustomerShippersItem) GetTruckCalledDateOk() (*string, bool)`

GetTruckCalledDateOk returns a tuple with the TruckCalledDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckCalledDate

`func (o *CustomerShippersApiListCustomerShippersItem) SetTruckCalledDate(v string)`

SetTruckCalledDate sets TruckCalledDate field to given value.

### HasTruckCalledDate

`func (o *CustomerShippersApiListCustomerShippersItem) HasTruckCalledDate() bool`

HasTruckCalledDate returns a boolean if a field has been set.

### GetGrossWeightOverride

`func (o *CustomerShippersApiListCustomerShippersItem) GetGrossWeightOverride() float64`

GetGrossWeightOverride returns the GrossWeightOverride field if non-nil, zero value otherwise.

### GetGrossWeightOverrideOk

`func (o *CustomerShippersApiListCustomerShippersItem) GetGrossWeightOverrideOk() (*float64, bool)`

GetGrossWeightOverrideOk returns a tuple with the GrossWeightOverride field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrossWeightOverride

`func (o *CustomerShippersApiListCustomerShippersItem) SetGrossWeightOverride(v float64)`

SetGrossWeightOverride sets GrossWeightOverride field to given value.

### HasGrossWeightOverride

`func (o *CustomerShippersApiListCustomerShippersItem) HasGrossWeightOverride() bool`

HasGrossWeightOverride returns a boolean if a field has been set.

### GetMrn

`func (o *CustomerShippersApiListCustomerShippersItem) GetMrn() string`

GetMrn returns the Mrn field if non-nil, zero value otherwise.

### GetMrnOk

`func (o *CustomerShippersApiListCustomerShippersItem) GetMrnOk() (*string, bool)`

GetMrnOk returns a tuple with the Mrn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMrn

`func (o *CustomerShippersApiListCustomerShippersItem) SetMrn(v string)`

SetMrn sets Mrn field to given value.

### HasMrn

`func (o *CustomerShippersApiListCustomerShippersItem) HasMrn() bool`

HasMrn returns a boolean if a field has been set.

### GetMrnDate

`func (o *CustomerShippersApiListCustomerShippersItem) GetMrnDate() string`

GetMrnDate returns the MrnDate field if non-nil, zero value otherwise.

### GetMrnDateOk

`func (o *CustomerShippersApiListCustomerShippersItem) GetMrnDateOk() (*string, bool)`

GetMrnDateOk returns a tuple with the MrnDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMrnDate

`func (o *CustomerShippersApiListCustomerShippersItem) SetMrnDate(v string)`

SetMrnDate sets MrnDate field to given value.

### HasMrnDate

`func (o *CustomerShippersApiListCustomerShippersItem) HasMrnDate() bool`

HasMrnDate returns a boolean if a field has been set.

### GetMrnType

`func (o *CustomerShippersApiListCustomerShippersItem) GetMrnType() string`

GetMrnType returns the MrnType field if non-nil, zero value otherwise.

### GetMrnTypeOk

`func (o *CustomerShippersApiListCustomerShippersItem) GetMrnTypeOk() (*string, bool)`

GetMrnTypeOk returns a tuple with the MrnType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMrnType

`func (o *CustomerShippersApiListCustomerShippersItem) SetMrnType(v string)`

SetMrnType sets MrnType field to given value.

### HasMrnType

`func (o *CustomerShippersApiListCustomerShippersItem) HasMrnType() bool`

HasMrnType returns a boolean if a field has been set.

### GetRoutingAuthorizationNumber

`func (o *CustomerShippersApiListCustomerShippersItem) GetRoutingAuthorizationNumber() string`

GetRoutingAuthorizationNumber returns the RoutingAuthorizationNumber field if non-nil, zero value otherwise.

### GetRoutingAuthorizationNumberOk

`func (o *CustomerShippersApiListCustomerShippersItem) GetRoutingAuthorizationNumberOk() (*string, bool)`

GetRoutingAuthorizationNumberOk returns a tuple with the RoutingAuthorizationNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoutingAuthorizationNumber

`func (o *CustomerShippersApiListCustomerShippersItem) SetRoutingAuthorizationNumber(v string)`

SetRoutingAuthorizationNumber sets RoutingAuthorizationNumber field to given value.

### HasRoutingAuthorizationNumber

`func (o *CustomerShippersApiListCustomerShippersItem) HasRoutingAuthorizationNumber() bool`

HasRoutingAuthorizationNumber returns a boolean if a field has been set.

### GetShipperWeight

`func (o *CustomerShippersApiListCustomerShippersItem) GetShipperWeight() float64`

GetShipperWeight returns the ShipperWeight field if non-nil, zero value otherwise.

### GetShipperWeightOk

`func (o *CustomerShippersApiListCustomerShippersItem) GetShipperWeightOk() (*float64, bool)`

GetShipperWeightOk returns a tuple with the ShipperWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipperWeight

`func (o *CustomerShippersApiListCustomerShippersItem) SetShipperWeight(v float64)`

SetShipperWeight sets ShipperWeight field to given value.

### HasShipperWeight

`func (o *CustomerShippersApiListCustomerShippersItem) HasShipperWeight() bool`

HasShipperWeight returns a boolean if a field has been set.

### GetPickListPrintedDateTime

`func (o *CustomerShippersApiListCustomerShippersItem) GetPickListPrintedDateTime() time.Time`

GetPickListPrintedDateTime returns the PickListPrintedDateTime field if non-nil, zero value otherwise.

### GetPickListPrintedDateTimeOk

`func (o *CustomerShippersApiListCustomerShippersItem) GetPickListPrintedDateTimeOk() (*time.Time, bool)`

GetPickListPrintedDateTimeOk returns a tuple with the PickListPrintedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPickListPrintedDateTime

`func (o *CustomerShippersApiListCustomerShippersItem) SetPickListPrintedDateTime(v time.Time)`

SetPickListPrintedDateTime sets PickListPrintedDateTime field to given value.

### HasPickListPrintedDateTime

`func (o *CustomerShippersApiListCustomerShippersItem) HasPickListPrintedDateTime() bool`

HasPickListPrintedDateTime returns a boolean if a field has been set.

### GetTruckArrivalTimeOfDay

`func (o *CustomerShippersApiListCustomerShippersItem) GetTruckArrivalTimeOfDay() string`

GetTruckArrivalTimeOfDay returns the TruckArrivalTimeOfDay field if non-nil, zero value otherwise.

### GetTruckArrivalTimeOfDayOk

`func (o *CustomerShippersApiListCustomerShippersItem) GetTruckArrivalTimeOfDayOk() (*string, bool)`

GetTruckArrivalTimeOfDayOk returns a tuple with the TruckArrivalTimeOfDay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckArrivalTimeOfDay

`func (o *CustomerShippersApiListCustomerShippersItem) SetTruckArrivalTimeOfDay(v string)`

SetTruckArrivalTimeOfDay sets TruckArrivalTimeOfDay field to given value.

### HasTruckArrivalTimeOfDay

`func (o *CustomerShippersApiListCustomerShippersItem) HasTruckArrivalTimeOfDay() bool`

HasTruckArrivalTimeOfDay returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


