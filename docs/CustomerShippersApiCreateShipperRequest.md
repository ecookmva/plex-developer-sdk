# CustomerShippersApiCreateShipperRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | The ID of the shipper. | [optional] 
**ShipperNumber** | Pointer to **string** | The shipper number. | [optional] 
**CustomerId** | Pointer to **string** | The customer ID. | [optional] 
**CustomerAddressId** | Pointer to **string** | The customer address ID. | [optional] 
**CarrierId** | Pointer to **string** | The carrier ID. | [optional] 
**FreightTerms** | Pointer to **string** | The shipper&#39;s freight terms. | [optional] 
**Status** | Pointer to **string** | The shipper status. | [optional] 
**TrackingNumber** | Pointer to **string** | The shipper tracking number. | [optional] 
**TrailerNumber** | Pointer to **string** | The shipper trailer number. | [optional] 
**ScheduledShipDate** | Pointer to **time.Time** | The scheduled ship date. | [optional] 
**ShipperNote** | Pointer to **string** | A note to print on the shipper and the bill of lading. | [optional] 
**TruckId** | Pointer to **string** | The truck ID. | [optional] 
**ExpediteNote** | Pointer to **string** | The expedite note. | [optional] 
**ExpediteReason** | Pointer to **string** | The expedite reason. | [optional] 
**ExpediteDepartmentCode** | Pointer to **string** | The department code that authorized the expedite. | [optional] 
**ExpediteAdditionalCost** | Pointer to **float64** | Additional cost due to expedited shipping. | [optional] 
**ShipFromId** | Pointer to **string** | The ship from code. | [optional] 
**TruckArrivalTimeOfDay** | Pointer to **string** | The truck arrival time. Use format hh:mm:ss. | [optional] 
**FreightAmount** | Pointer to **float64** | The freight amount. | [optional] 
**BolNote** | Pointer to **string** | The bill of lading note. | [optional] 
**Note** | Pointer to **string** | An internal note. | [optional] 
**CustomsExporter** | Pointer to **string** | The customs exporter. | [optional] 
**DeliveryDate** | Pointer to **time.Time** | The delivery date. | [optional] 
**DropshipSupplierId** | Pointer to **string** | The dropship supplier ID. | [optional] 
**ChargeAmount** | Pointer to **float64** | The charge amount for the shipper. | [optional] 
**MasterBolNumber** | Pointer to **string** | The master bill of lading (BOL) number. | [optional] 
**Pallets** | Pointer to **int32** | The number of pallets on the shipper. | [optional] 
**PremiumTransAuth** | Pointer to **string** | The number specified in the shipper&#39;s Premium Trans Auth field (used for AETC numbers on expedited shipments). | [optional] 
**TruckConfirmation** | Pointer to **string** | The truck confirmation. | [optional] 
**TruckCalledDate** | Pointer to **string** | The truck called date. Use format YYYY-MM-DD. | [optional] 
**GrossWeightOverride** | Pointer to **float64** | The gross weight override. | [optional] 
**Mrn** | Pointer to **string** | The movement reference number (MRN) specified on the shipper. | [optional] 
**MrnDate** | Pointer to **string** | The movement reference number (MRN) date. Use format YYYY-MM-DD. | [optional] 
**MrnType** | Pointer to **string** | The MRN type. | [optional] 
**RoutingAuthorizationNumber** | Pointer to **string** | The routing authorization number. | [optional] 

## Methods

### NewCustomerShippersApiCreateShipperRequest

`func NewCustomerShippersApiCreateShipperRequest() *CustomerShippersApiCreateShipperRequest`

NewCustomerShippersApiCreateShipperRequest instantiates a new CustomerShippersApiCreateShipperRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomerShippersApiCreateShipperRequestWithDefaults

`func NewCustomerShippersApiCreateShipperRequestWithDefaults() *CustomerShippersApiCreateShipperRequest`

NewCustomerShippersApiCreateShipperRequestWithDefaults instantiates a new CustomerShippersApiCreateShipperRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CustomerShippersApiCreateShipperRequest) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CustomerShippersApiCreateShipperRequest) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CustomerShippersApiCreateShipperRequest) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *CustomerShippersApiCreateShipperRequest) HasId() bool`

HasId returns a boolean if a field has been set.

### GetShipperNumber

`func (o *CustomerShippersApiCreateShipperRequest) GetShipperNumber() string`

GetShipperNumber returns the ShipperNumber field if non-nil, zero value otherwise.

### GetShipperNumberOk

`func (o *CustomerShippersApiCreateShipperRequest) GetShipperNumberOk() (*string, bool)`

GetShipperNumberOk returns a tuple with the ShipperNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipperNumber

`func (o *CustomerShippersApiCreateShipperRequest) SetShipperNumber(v string)`

SetShipperNumber sets ShipperNumber field to given value.

### HasShipperNumber

`func (o *CustomerShippersApiCreateShipperRequest) HasShipperNumber() bool`

HasShipperNumber returns a boolean if a field has been set.

### GetCustomerId

`func (o *CustomerShippersApiCreateShipperRequest) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *CustomerShippersApiCreateShipperRequest) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *CustomerShippersApiCreateShipperRequest) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *CustomerShippersApiCreateShipperRequest) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### GetCustomerAddressId

`func (o *CustomerShippersApiCreateShipperRequest) GetCustomerAddressId() string`

GetCustomerAddressId returns the CustomerAddressId field if non-nil, zero value otherwise.

### GetCustomerAddressIdOk

`func (o *CustomerShippersApiCreateShipperRequest) GetCustomerAddressIdOk() (*string, bool)`

GetCustomerAddressIdOk returns a tuple with the CustomerAddressId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerAddressId

`func (o *CustomerShippersApiCreateShipperRequest) SetCustomerAddressId(v string)`

SetCustomerAddressId sets CustomerAddressId field to given value.

### HasCustomerAddressId

`func (o *CustomerShippersApiCreateShipperRequest) HasCustomerAddressId() bool`

HasCustomerAddressId returns a boolean if a field has been set.

### GetCarrierId

`func (o *CustomerShippersApiCreateShipperRequest) GetCarrierId() string`

GetCarrierId returns the CarrierId field if non-nil, zero value otherwise.

### GetCarrierIdOk

`func (o *CustomerShippersApiCreateShipperRequest) GetCarrierIdOk() (*string, bool)`

GetCarrierIdOk returns a tuple with the CarrierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierId

`func (o *CustomerShippersApiCreateShipperRequest) SetCarrierId(v string)`

SetCarrierId sets CarrierId field to given value.

### HasCarrierId

`func (o *CustomerShippersApiCreateShipperRequest) HasCarrierId() bool`

HasCarrierId returns a boolean if a field has been set.

### GetFreightTerms

`func (o *CustomerShippersApiCreateShipperRequest) GetFreightTerms() string`

GetFreightTerms returns the FreightTerms field if non-nil, zero value otherwise.

### GetFreightTermsOk

`func (o *CustomerShippersApiCreateShipperRequest) GetFreightTermsOk() (*string, bool)`

GetFreightTermsOk returns a tuple with the FreightTerms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFreightTerms

`func (o *CustomerShippersApiCreateShipperRequest) SetFreightTerms(v string)`

SetFreightTerms sets FreightTerms field to given value.

### HasFreightTerms

`func (o *CustomerShippersApiCreateShipperRequest) HasFreightTerms() bool`

HasFreightTerms returns a boolean if a field has been set.

### GetStatus

`func (o *CustomerShippersApiCreateShipperRequest) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CustomerShippersApiCreateShipperRequest) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CustomerShippersApiCreateShipperRequest) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *CustomerShippersApiCreateShipperRequest) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetTrackingNumber

`func (o *CustomerShippersApiCreateShipperRequest) GetTrackingNumber() string`

GetTrackingNumber returns the TrackingNumber field if non-nil, zero value otherwise.

### GetTrackingNumberOk

`func (o *CustomerShippersApiCreateShipperRequest) GetTrackingNumberOk() (*string, bool)`

GetTrackingNumberOk returns a tuple with the TrackingNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackingNumber

`func (o *CustomerShippersApiCreateShipperRequest) SetTrackingNumber(v string)`

SetTrackingNumber sets TrackingNumber field to given value.

### HasTrackingNumber

`func (o *CustomerShippersApiCreateShipperRequest) HasTrackingNumber() bool`

HasTrackingNumber returns a boolean if a field has been set.

### GetTrailerNumber

`func (o *CustomerShippersApiCreateShipperRequest) GetTrailerNumber() string`

GetTrailerNumber returns the TrailerNumber field if non-nil, zero value otherwise.

### GetTrailerNumberOk

`func (o *CustomerShippersApiCreateShipperRequest) GetTrailerNumberOk() (*string, bool)`

GetTrailerNumberOk returns a tuple with the TrailerNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrailerNumber

`func (o *CustomerShippersApiCreateShipperRequest) SetTrailerNumber(v string)`

SetTrailerNumber sets TrailerNumber field to given value.

### HasTrailerNumber

`func (o *CustomerShippersApiCreateShipperRequest) HasTrailerNumber() bool`

HasTrailerNumber returns a boolean if a field has been set.

### GetScheduledShipDate

`func (o *CustomerShippersApiCreateShipperRequest) GetScheduledShipDate() time.Time`

GetScheduledShipDate returns the ScheduledShipDate field if non-nil, zero value otherwise.

### GetScheduledShipDateOk

`func (o *CustomerShippersApiCreateShipperRequest) GetScheduledShipDateOk() (*time.Time, bool)`

GetScheduledShipDateOk returns a tuple with the ScheduledShipDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScheduledShipDate

`func (o *CustomerShippersApiCreateShipperRequest) SetScheduledShipDate(v time.Time)`

SetScheduledShipDate sets ScheduledShipDate field to given value.

### HasScheduledShipDate

`func (o *CustomerShippersApiCreateShipperRequest) HasScheduledShipDate() bool`

HasScheduledShipDate returns a boolean if a field has been set.

### GetShipperNote

`func (o *CustomerShippersApiCreateShipperRequest) GetShipperNote() string`

GetShipperNote returns the ShipperNote field if non-nil, zero value otherwise.

### GetShipperNoteOk

`func (o *CustomerShippersApiCreateShipperRequest) GetShipperNoteOk() (*string, bool)`

GetShipperNoteOk returns a tuple with the ShipperNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipperNote

`func (o *CustomerShippersApiCreateShipperRequest) SetShipperNote(v string)`

SetShipperNote sets ShipperNote field to given value.

### HasShipperNote

`func (o *CustomerShippersApiCreateShipperRequest) HasShipperNote() bool`

HasShipperNote returns a boolean if a field has been set.

### GetTruckId

`func (o *CustomerShippersApiCreateShipperRequest) GetTruckId() string`

GetTruckId returns the TruckId field if non-nil, zero value otherwise.

### GetTruckIdOk

`func (o *CustomerShippersApiCreateShipperRequest) GetTruckIdOk() (*string, bool)`

GetTruckIdOk returns a tuple with the TruckId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckId

`func (o *CustomerShippersApiCreateShipperRequest) SetTruckId(v string)`

SetTruckId sets TruckId field to given value.

### HasTruckId

`func (o *CustomerShippersApiCreateShipperRequest) HasTruckId() bool`

HasTruckId returns a boolean if a field has been set.

### GetExpediteNote

`func (o *CustomerShippersApiCreateShipperRequest) GetExpediteNote() string`

GetExpediteNote returns the ExpediteNote field if non-nil, zero value otherwise.

### GetExpediteNoteOk

`func (o *CustomerShippersApiCreateShipperRequest) GetExpediteNoteOk() (*string, bool)`

GetExpediteNoteOk returns a tuple with the ExpediteNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpediteNote

`func (o *CustomerShippersApiCreateShipperRequest) SetExpediteNote(v string)`

SetExpediteNote sets ExpediteNote field to given value.

### HasExpediteNote

`func (o *CustomerShippersApiCreateShipperRequest) HasExpediteNote() bool`

HasExpediteNote returns a boolean if a field has been set.

### GetExpediteReason

`func (o *CustomerShippersApiCreateShipperRequest) GetExpediteReason() string`

GetExpediteReason returns the ExpediteReason field if non-nil, zero value otherwise.

### GetExpediteReasonOk

`func (o *CustomerShippersApiCreateShipperRequest) GetExpediteReasonOk() (*string, bool)`

GetExpediteReasonOk returns a tuple with the ExpediteReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpediteReason

`func (o *CustomerShippersApiCreateShipperRequest) SetExpediteReason(v string)`

SetExpediteReason sets ExpediteReason field to given value.

### HasExpediteReason

`func (o *CustomerShippersApiCreateShipperRequest) HasExpediteReason() bool`

HasExpediteReason returns a boolean if a field has been set.

### GetExpediteDepartmentCode

`func (o *CustomerShippersApiCreateShipperRequest) GetExpediteDepartmentCode() string`

GetExpediteDepartmentCode returns the ExpediteDepartmentCode field if non-nil, zero value otherwise.

### GetExpediteDepartmentCodeOk

`func (o *CustomerShippersApiCreateShipperRequest) GetExpediteDepartmentCodeOk() (*string, bool)`

GetExpediteDepartmentCodeOk returns a tuple with the ExpediteDepartmentCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpediteDepartmentCode

`func (o *CustomerShippersApiCreateShipperRequest) SetExpediteDepartmentCode(v string)`

SetExpediteDepartmentCode sets ExpediteDepartmentCode field to given value.

### HasExpediteDepartmentCode

`func (o *CustomerShippersApiCreateShipperRequest) HasExpediteDepartmentCode() bool`

HasExpediteDepartmentCode returns a boolean if a field has been set.

### GetExpediteAdditionalCost

`func (o *CustomerShippersApiCreateShipperRequest) GetExpediteAdditionalCost() float64`

GetExpediteAdditionalCost returns the ExpediteAdditionalCost field if non-nil, zero value otherwise.

### GetExpediteAdditionalCostOk

`func (o *CustomerShippersApiCreateShipperRequest) GetExpediteAdditionalCostOk() (*float64, bool)`

GetExpediteAdditionalCostOk returns a tuple with the ExpediteAdditionalCost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpediteAdditionalCost

`func (o *CustomerShippersApiCreateShipperRequest) SetExpediteAdditionalCost(v float64)`

SetExpediteAdditionalCost sets ExpediteAdditionalCost field to given value.

### HasExpediteAdditionalCost

`func (o *CustomerShippersApiCreateShipperRequest) HasExpediteAdditionalCost() bool`

HasExpediteAdditionalCost returns a boolean if a field has been set.

### GetShipFromId

`func (o *CustomerShippersApiCreateShipperRequest) GetShipFromId() string`

GetShipFromId returns the ShipFromId field if non-nil, zero value otherwise.

### GetShipFromIdOk

`func (o *CustomerShippersApiCreateShipperRequest) GetShipFromIdOk() (*string, bool)`

GetShipFromIdOk returns a tuple with the ShipFromId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipFromId

`func (o *CustomerShippersApiCreateShipperRequest) SetShipFromId(v string)`

SetShipFromId sets ShipFromId field to given value.

### HasShipFromId

`func (o *CustomerShippersApiCreateShipperRequest) HasShipFromId() bool`

HasShipFromId returns a boolean if a field has been set.

### GetTruckArrivalTimeOfDay

`func (o *CustomerShippersApiCreateShipperRequest) GetTruckArrivalTimeOfDay() string`

GetTruckArrivalTimeOfDay returns the TruckArrivalTimeOfDay field if non-nil, zero value otherwise.

### GetTruckArrivalTimeOfDayOk

`func (o *CustomerShippersApiCreateShipperRequest) GetTruckArrivalTimeOfDayOk() (*string, bool)`

GetTruckArrivalTimeOfDayOk returns a tuple with the TruckArrivalTimeOfDay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckArrivalTimeOfDay

`func (o *CustomerShippersApiCreateShipperRequest) SetTruckArrivalTimeOfDay(v string)`

SetTruckArrivalTimeOfDay sets TruckArrivalTimeOfDay field to given value.

### HasTruckArrivalTimeOfDay

`func (o *CustomerShippersApiCreateShipperRequest) HasTruckArrivalTimeOfDay() bool`

HasTruckArrivalTimeOfDay returns a boolean if a field has been set.

### GetFreightAmount

`func (o *CustomerShippersApiCreateShipperRequest) GetFreightAmount() float64`

GetFreightAmount returns the FreightAmount field if non-nil, zero value otherwise.

### GetFreightAmountOk

`func (o *CustomerShippersApiCreateShipperRequest) GetFreightAmountOk() (*float64, bool)`

GetFreightAmountOk returns a tuple with the FreightAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFreightAmount

`func (o *CustomerShippersApiCreateShipperRequest) SetFreightAmount(v float64)`

SetFreightAmount sets FreightAmount field to given value.

### HasFreightAmount

`func (o *CustomerShippersApiCreateShipperRequest) HasFreightAmount() bool`

HasFreightAmount returns a boolean if a field has been set.

### GetBolNote

`func (o *CustomerShippersApiCreateShipperRequest) GetBolNote() string`

GetBolNote returns the BolNote field if non-nil, zero value otherwise.

### GetBolNoteOk

`func (o *CustomerShippersApiCreateShipperRequest) GetBolNoteOk() (*string, bool)`

GetBolNoteOk returns a tuple with the BolNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBolNote

`func (o *CustomerShippersApiCreateShipperRequest) SetBolNote(v string)`

SetBolNote sets BolNote field to given value.

### HasBolNote

`func (o *CustomerShippersApiCreateShipperRequest) HasBolNote() bool`

HasBolNote returns a boolean if a field has been set.

### GetNote

`func (o *CustomerShippersApiCreateShipperRequest) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *CustomerShippersApiCreateShipperRequest) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *CustomerShippersApiCreateShipperRequest) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *CustomerShippersApiCreateShipperRequest) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetCustomsExporter

`func (o *CustomerShippersApiCreateShipperRequest) GetCustomsExporter() string`

GetCustomsExporter returns the CustomsExporter field if non-nil, zero value otherwise.

### GetCustomsExporterOk

`func (o *CustomerShippersApiCreateShipperRequest) GetCustomsExporterOk() (*string, bool)`

GetCustomsExporterOk returns a tuple with the CustomsExporter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomsExporter

`func (o *CustomerShippersApiCreateShipperRequest) SetCustomsExporter(v string)`

SetCustomsExporter sets CustomsExporter field to given value.

### HasCustomsExporter

`func (o *CustomerShippersApiCreateShipperRequest) HasCustomsExporter() bool`

HasCustomsExporter returns a boolean if a field has been set.

### GetDeliveryDate

`func (o *CustomerShippersApiCreateShipperRequest) GetDeliveryDate() time.Time`

GetDeliveryDate returns the DeliveryDate field if non-nil, zero value otherwise.

### GetDeliveryDateOk

`func (o *CustomerShippersApiCreateShipperRequest) GetDeliveryDateOk() (*time.Time, bool)`

GetDeliveryDateOk returns a tuple with the DeliveryDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliveryDate

`func (o *CustomerShippersApiCreateShipperRequest) SetDeliveryDate(v time.Time)`

SetDeliveryDate sets DeliveryDate field to given value.

### HasDeliveryDate

`func (o *CustomerShippersApiCreateShipperRequest) HasDeliveryDate() bool`

HasDeliveryDate returns a boolean if a field has been set.

### GetDropshipSupplierId

`func (o *CustomerShippersApiCreateShipperRequest) GetDropshipSupplierId() string`

GetDropshipSupplierId returns the DropshipSupplierId field if non-nil, zero value otherwise.

### GetDropshipSupplierIdOk

`func (o *CustomerShippersApiCreateShipperRequest) GetDropshipSupplierIdOk() (*string, bool)`

GetDropshipSupplierIdOk returns a tuple with the DropshipSupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDropshipSupplierId

`func (o *CustomerShippersApiCreateShipperRequest) SetDropshipSupplierId(v string)`

SetDropshipSupplierId sets DropshipSupplierId field to given value.

### HasDropshipSupplierId

`func (o *CustomerShippersApiCreateShipperRequest) HasDropshipSupplierId() bool`

HasDropshipSupplierId returns a boolean if a field has been set.

### GetChargeAmount

`func (o *CustomerShippersApiCreateShipperRequest) GetChargeAmount() float64`

GetChargeAmount returns the ChargeAmount field if non-nil, zero value otherwise.

### GetChargeAmountOk

`func (o *CustomerShippersApiCreateShipperRequest) GetChargeAmountOk() (*float64, bool)`

GetChargeAmountOk returns a tuple with the ChargeAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChargeAmount

`func (o *CustomerShippersApiCreateShipperRequest) SetChargeAmount(v float64)`

SetChargeAmount sets ChargeAmount field to given value.

### HasChargeAmount

`func (o *CustomerShippersApiCreateShipperRequest) HasChargeAmount() bool`

HasChargeAmount returns a boolean if a field has been set.

### GetMasterBolNumber

`func (o *CustomerShippersApiCreateShipperRequest) GetMasterBolNumber() string`

GetMasterBolNumber returns the MasterBolNumber field if non-nil, zero value otherwise.

### GetMasterBolNumberOk

`func (o *CustomerShippersApiCreateShipperRequest) GetMasterBolNumberOk() (*string, bool)`

GetMasterBolNumberOk returns a tuple with the MasterBolNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMasterBolNumber

`func (o *CustomerShippersApiCreateShipperRequest) SetMasterBolNumber(v string)`

SetMasterBolNumber sets MasterBolNumber field to given value.

### HasMasterBolNumber

`func (o *CustomerShippersApiCreateShipperRequest) HasMasterBolNumber() bool`

HasMasterBolNumber returns a boolean if a field has been set.

### GetPallets

`func (o *CustomerShippersApiCreateShipperRequest) GetPallets() int32`

GetPallets returns the Pallets field if non-nil, zero value otherwise.

### GetPalletsOk

`func (o *CustomerShippersApiCreateShipperRequest) GetPalletsOk() (*int32, bool)`

GetPalletsOk returns a tuple with the Pallets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPallets

`func (o *CustomerShippersApiCreateShipperRequest) SetPallets(v int32)`

SetPallets sets Pallets field to given value.

### HasPallets

`func (o *CustomerShippersApiCreateShipperRequest) HasPallets() bool`

HasPallets returns a boolean if a field has been set.

### GetPremiumTransAuth

`func (o *CustomerShippersApiCreateShipperRequest) GetPremiumTransAuth() string`

GetPremiumTransAuth returns the PremiumTransAuth field if non-nil, zero value otherwise.

### GetPremiumTransAuthOk

`func (o *CustomerShippersApiCreateShipperRequest) GetPremiumTransAuthOk() (*string, bool)`

GetPremiumTransAuthOk returns a tuple with the PremiumTransAuth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPremiumTransAuth

`func (o *CustomerShippersApiCreateShipperRequest) SetPremiumTransAuth(v string)`

SetPremiumTransAuth sets PremiumTransAuth field to given value.

### HasPremiumTransAuth

`func (o *CustomerShippersApiCreateShipperRequest) HasPremiumTransAuth() bool`

HasPremiumTransAuth returns a boolean if a field has been set.

### GetTruckConfirmation

`func (o *CustomerShippersApiCreateShipperRequest) GetTruckConfirmation() string`

GetTruckConfirmation returns the TruckConfirmation field if non-nil, zero value otherwise.

### GetTruckConfirmationOk

`func (o *CustomerShippersApiCreateShipperRequest) GetTruckConfirmationOk() (*string, bool)`

GetTruckConfirmationOk returns a tuple with the TruckConfirmation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckConfirmation

`func (o *CustomerShippersApiCreateShipperRequest) SetTruckConfirmation(v string)`

SetTruckConfirmation sets TruckConfirmation field to given value.

### HasTruckConfirmation

`func (o *CustomerShippersApiCreateShipperRequest) HasTruckConfirmation() bool`

HasTruckConfirmation returns a boolean if a field has been set.

### GetTruckCalledDate

`func (o *CustomerShippersApiCreateShipperRequest) GetTruckCalledDate() string`

GetTruckCalledDate returns the TruckCalledDate field if non-nil, zero value otherwise.

### GetTruckCalledDateOk

`func (o *CustomerShippersApiCreateShipperRequest) GetTruckCalledDateOk() (*string, bool)`

GetTruckCalledDateOk returns a tuple with the TruckCalledDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckCalledDate

`func (o *CustomerShippersApiCreateShipperRequest) SetTruckCalledDate(v string)`

SetTruckCalledDate sets TruckCalledDate field to given value.

### HasTruckCalledDate

`func (o *CustomerShippersApiCreateShipperRequest) HasTruckCalledDate() bool`

HasTruckCalledDate returns a boolean if a field has been set.

### GetGrossWeightOverride

`func (o *CustomerShippersApiCreateShipperRequest) GetGrossWeightOverride() float64`

GetGrossWeightOverride returns the GrossWeightOverride field if non-nil, zero value otherwise.

### GetGrossWeightOverrideOk

`func (o *CustomerShippersApiCreateShipperRequest) GetGrossWeightOverrideOk() (*float64, bool)`

GetGrossWeightOverrideOk returns a tuple with the GrossWeightOverride field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrossWeightOverride

`func (o *CustomerShippersApiCreateShipperRequest) SetGrossWeightOverride(v float64)`

SetGrossWeightOverride sets GrossWeightOverride field to given value.

### HasGrossWeightOverride

`func (o *CustomerShippersApiCreateShipperRequest) HasGrossWeightOverride() bool`

HasGrossWeightOverride returns a boolean if a field has been set.

### GetMrn

`func (o *CustomerShippersApiCreateShipperRequest) GetMrn() string`

GetMrn returns the Mrn field if non-nil, zero value otherwise.

### GetMrnOk

`func (o *CustomerShippersApiCreateShipperRequest) GetMrnOk() (*string, bool)`

GetMrnOk returns a tuple with the Mrn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMrn

`func (o *CustomerShippersApiCreateShipperRequest) SetMrn(v string)`

SetMrn sets Mrn field to given value.

### HasMrn

`func (o *CustomerShippersApiCreateShipperRequest) HasMrn() bool`

HasMrn returns a boolean if a field has been set.

### GetMrnDate

`func (o *CustomerShippersApiCreateShipperRequest) GetMrnDate() string`

GetMrnDate returns the MrnDate field if non-nil, zero value otherwise.

### GetMrnDateOk

`func (o *CustomerShippersApiCreateShipperRequest) GetMrnDateOk() (*string, bool)`

GetMrnDateOk returns a tuple with the MrnDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMrnDate

`func (o *CustomerShippersApiCreateShipperRequest) SetMrnDate(v string)`

SetMrnDate sets MrnDate field to given value.

### HasMrnDate

`func (o *CustomerShippersApiCreateShipperRequest) HasMrnDate() bool`

HasMrnDate returns a boolean if a field has been set.

### GetMrnType

`func (o *CustomerShippersApiCreateShipperRequest) GetMrnType() string`

GetMrnType returns the MrnType field if non-nil, zero value otherwise.

### GetMrnTypeOk

`func (o *CustomerShippersApiCreateShipperRequest) GetMrnTypeOk() (*string, bool)`

GetMrnTypeOk returns a tuple with the MrnType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMrnType

`func (o *CustomerShippersApiCreateShipperRequest) SetMrnType(v string)`

SetMrnType sets MrnType field to given value.

### HasMrnType

`func (o *CustomerShippersApiCreateShipperRequest) HasMrnType() bool`

HasMrnType returns a boolean if a field has been set.

### GetRoutingAuthorizationNumber

`func (o *CustomerShippersApiCreateShipperRequest) GetRoutingAuthorizationNumber() string`

GetRoutingAuthorizationNumber returns the RoutingAuthorizationNumber field if non-nil, zero value otherwise.

### GetRoutingAuthorizationNumberOk

`func (o *CustomerShippersApiCreateShipperRequest) GetRoutingAuthorizationNumberOk() (*string, bool)`

GetRoutingAuthorizationNumberOk returns a tuple with the RoutingAuthorizationNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoutingAuthorizationNumber

`func (o *CustomerShippersApiCreateShipperRequest) SetRoutingAuthorizationNumber(v string)`

SetRoutingAuthorizationNumber sets RoutingAuthorizationNumber field to given value.

### HasRoutingAuthorizationNumber

`func (o *CustomerShippersApiCreateShipperRequest) HasRoutingAuthorizationNumber() bool`

HasRoutingAuthorizationNumber returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


