# CustomerTrucksApiUpdateCustomerTruckRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FreightTerms** | Pointer to **string** | Terms of the freight payment; for example, COD, Collect, or Prepaid. | [optional] 
**TrackingNumber** | Pointer to **string** | The tracking number, often provided by a carrier, related to a specific shipment. | [optional] 
**TrailerNumber** | Pointer to **string** | The trailer number associated with the physical trailer that a specific shipment was shipped on. | [optional] 
**Note** | Pointer to **string** | A note assigned to the truck. | [optional] 
**TruckCalled** | Pointer to **bool** | Indicates if the carrier has been contacted. | [optional] 
**TruckArrivalTimeOfDay** | Pointer to **string** | The arrival time of the truck (arrival time can be planned or actual, depending on implementation). | [optional] 
**BolNumber** | Pointer to **string** | The bill of lading number. | [optional] 
**BolNote** | Pointer to **string** | A note on the bill of lading. | [optional] 
**Pool** | Pointer to **bool** | Indicates that the truck is part of a pool shipment. A pool is a central warehouse that redistributes shippers from one truck to another before shipping to customer locations. | [optional] 
**CarrierId** | Pointer to **string** | The ID of the carrier associated with the truck. (A carrier is a supplier with a supplier type of &amp;quot;Carrier&amp;quot;.) | [optional] 
**TrailerCarrierId** | Pointer to **string** | The ID of the supplier with a &amp;quot;Carrier&amp;quot; type used as the trailer carrier. | [optional] 
**BrokeredCarrierId** | Pointer to **string** | The ID of the supplier with a &amp;quot;Carrier&amp;quot; type used as the brokered carrier. | [optional] 
**TruckCalledDate** | Pointer to **string** | The date the carrier was called regarding the shipment or truck. Use format YYYY-MM-DD. | [optional] 
**TruckConfirmation** | Pointer to **string** | The confirmation from the carrier regarding the shipment or truck. | [optional] 
**TruckContact** | Pointer to **string** | A contact person, typically at the carrier, regarding the shipment or truck. | [optional] 
**ScheduledShipDate** | Pointer to **string** | The date on which the truck is scheduled to ship. Use format YYYY-MM-DD. | [optional] 
**MilkRunDescription** | Pointer to **string** | The name of a route with multiple stops that happens on a recurring basis. | [optional] 
**TruckType** | Pointer to **string** | The truck type. | [optional] 
**TruckStatus** | Pointer to **string** | The truck status. | [optional] 
**TransMode** | Pointer to **string** | The transportation mode associated with the truck. | [optional] 
**DropshipSupplierId** | Pointer to **string** | The dropship supplier resource ID associated with the truck. | [optional] 
**IncoTerms** | Pointer to **string** | International Commercial (INCO) terms applied to the sales order. | [optional] 
**CustomsBrokerSupplierId** | Pointer to **string** | The ID of the supplier with a &amp;quot;Customs Broker&amp;quot; type. | [optional] 
**SubBuildingCode** | Pointer to **string** | The sub-building code indicating the location in the building where the truck will be loaded. | [optional] 
**TruckRoute** | Pointer to **string** | The route for the truck. | [optional] 
**EstimatedArrivalDate** | Pointer to **time.Time** | The estimated arrival date of the truck. | [optional] 
**TruckFreightAmount** | Pointer to **float64** | The amount of the truck freight charge. | [optional] 

## Methods

### NewCustomerTrucksApiUpdateCustomerTruckRequest

`func NewCustomerTrucksApiUpdateCustomerTruckRequest() *CustomerTrucksApiUpdateCustomerTruckRequest`

NewCustomerTrucksApiUpdateCustomerTruckRequest instantiates a new CustomerTrucksApiUpdateCustomerTruckRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomerTrucksApiUpdateCustomerTruckRequestWithDefaults

`func NewCustomerTrucksApiUpdateCustomerTruckRequestWithDefaults() *CustomerTrucksApiUpdateCustomerTruckRequest`

NewCustomerTrucksApiUpdateCustomerTruckRequestWithDefaults instantiates a new CustomerTrucksApiUpdateCustomerTruckRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFreightTerms

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetFreightTerms() string`

GetFreightTerms returns the FreightTerms field if non-nil, zero value otherwise.

### GetFreightTermsOk

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetFreightTermsOk() (*string, bool)`

GetFreightTermsOk returns a tuple with the FreightTerms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFreightTerms

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) SetFreightTerms(v string)`

SetFreightTerms sets FreightTerms field to given value.

### HasFreightTerms

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) HasFreightTerms() bool`

HasFreightTerms returns a boolean if a field has been set.

### GetTrackingNumber

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetTrackingNumber() string`

GetTrackingNumber returns the TrackingNumber field if non-nil, zero value otherwise.

### GetTrackingNumberOk

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetTrackingNumberOk() (*string, bool)`

GetTrackingNumberOk returns a tuple with the TrackingNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackingNumber

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) SetTrackingNumber(v string)`

SetTrackingNumber sets TrackingNumber field to given value.

### HasTrackingNumber

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) HasTrackingNumber() bool`

HasTrackingNumber returns a boolean if a field has been set.

### GetTrailerNumber

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetTrailerNumber() string`

GetTrailerNumber returns the TrailerNumber field if non-nil, zero value otherwise.

### GetTrailerNumberOk

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetTrailerNumberOk() (*string, bool)`

GetTrailerNumberOk returns a tuple with the TrailerNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrailerNumber

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) SetTrailerNumber(v string)`

SetTrailerNumber sets TrailerNumber field to given value.

### HasTrailerNumber

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) HasTrailerNumber() bool`

HasTrailerNumber returns a boolean if a field has been set.

### GetNote

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetTruckCalled

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetTruckCalled() bool`

GetTruckCalled returns the TruckCalled field if non-nil, zero value otherwise.

### GetTruckCalledOk

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetTruckCalledOk() (*bool, bool)`

GetTruckCalledOk returns a tuple with the TruckCalled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckCalled

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) SetTruckCalled(v bool)`

SetTruckCalled sets TruckCalled field to given value.

### HasTruckCalled

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) HasTruckCalled() bool`

HasTruckCalled returns a boolean if a field has been set.

### GetTruckArrivalTimeOfDay

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetTruckArrivalTimeOfDay() string`

GetTruckArrivalTimeOfDay returns the TruckArrivalTimeOfDay field if non-nil, zero value otherwise.

### GetTruckArrivalTimeOfDayOk

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetTruckArrivalTimeOfDayOk() (*string, bool)`

GetTruckArrivalTimeOfDayOk returns a tuple with the TruckArrivalTimeOfDay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckArrivalTimeOfDay

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) SetTruckArrivalTimeOfDay(v string)`

SetTruckArrivalTimeOfDay sets TruckArrivalTimeOfDay field to given value.

### HasTruckArrivalTimeOfDay

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) HasTruckArrivalTimeOfDay() bool`

HasTruckArrivalTimeOfDay returns a boolean if a field has been set.

### GetBolNumber

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetBolNumber() string`

GetBolNumber returns the BolNumber field if non-nil, zero value otherwise.

### GetBolNumberOk

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetBolNumberOk() (*string, bool)`

GetBolNumberOk returns a tuple with the BolNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBolNumber

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) SetBolNumber(v string)`

SetBolNumber sets BolNumber field to given value.

### HasBolNumber

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) HasBolNumber() bool`

HasBolNumber returns a boolean if a field has been set.

### GetBolNote

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetBolNote() string`

GetBolNote returns the BolNote field if non-nil, zero value otherwise.

### GetBolNoteOk

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetBolNoteOk() (*string, bool)`

GetBolNoteOk returns a tuple with the BolNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBolNote

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) SetBolNote(v string)`

SetBolNote sets BolNote field to given value.

### HasBolNote

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) HasBolNote() bool`

HasBolNote returns a boolean if a field has been set.

### GetPool

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetPool() bool`

GetPool returns the Pool field if non-nil, zero value otherwise.

### GetPoolOk

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetPoolOk() (*bool, bool)`

GetPoolOk returns a tuple with the Pool field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPool

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) SetPool(v bool)`

SetPool sets Pool field to given value.

### HasPool

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) HasPool() bool`

HasPool returns a boolean if a field has been set.

### GetCarrierId

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetCarrierId() string`

GetCarrierId returns the CarrierId field if non-nil, zero value otherwise.

### GetCarrierIdOk

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetCarrierIdOk() (*string, bool)`

GetCarrierIdOk returns a tuple with the CarrierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierId

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) SetCarrierId(v string)`

SetCarrierId sets CarrierId field to given value.

### HasCarrierId

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) HasCarrierId() bool`

HasCarrierId returns a boolean if a field has been set.

### GetTrailerCarrierId

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetTrailerCarrierId() string`

GetTrailerCarrierId returns the TrailerCarrierId field if non-nil, zero value otherwise.

### GetTrailerCarrierIdOk

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetTrailerCarrierIdOk() (*string, bool)`

GetTrailerCarrierIdOk returns a tuple with the TrailerCarrierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrailerCarrierId

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) SetTrailerCarrierId(v string)`

SetTrailerCarrierId sets TrailerCarrierId field to given value.

### HasTrailerCarrierId

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) HasTrailerCarrierId() bool`

HasTrailerCarrierId returns a boolean if a field has been set.

### GetBrokeredCarrierId

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetBrokeredCarrierId() string`

GetBrokeredCarrierId returns the BrokeredCarrierId field if non-nil, zero value otherwise.

### GetBrokeredCarrierIdOk

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetBrokeredCarrierIdOk() (*string, bool)`

GetBrokeredCarrierIdOk returns a tuple with the BrokeredCarrierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrokeredCarrierId

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) SetBrokeredCarrierId(v string)`

SetBrokeredCarrierId sets BrokeredCarrierId field to given value.

### HasBrokeredCarrierId

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) HasBrokeredCarrierId() bool`

HasBrokeredCarrierId returns a boolean if a field has been set.

### GetTruckCalledDate

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetTruckCalledDate() string`

GetTruckCalledDate returns the TruckCalledDate field if non-nil, zero value otherwise.

### GetTruckCalledDateOk

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetTruckCalledDateOk() (*string, bool)`

GetTruckCalledDateOk returns a tuple with the TruckCalledDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckCalledDate

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) SetTruckCalledDate(v string)`

SetTruckCalledDate sets TruckCalledDate field to given value.

### HasTruckCalledDate

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) HasTruckCalledDate() bool`

HasTruckCalledDate returns a boolean if a field has been set.

### GetTruckConfirmation

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetTruckConfirmation() string`

GetTruckConfirmation returns the TruckConfirmation field if non-nil, zero value otherwise.

### GetTruckConfirmationOk

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetTruckConfirmationOk() (*string, bool)`

GetTruckConfirmationOk returns a tuple with the TruckConfirmation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckConfirmation

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) SetTruckConfirmation(v string)`

SetTruckConfirmation sets TruckConfirmation field to given value.

### HasTruckConfirmation

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) HasTruckConfirmation() bool`

HasTruckConfirmation returns a boolean if a field has been set.

### GetTruckContact

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetTruckContact() string`

GetTruckContact returns the TruckContact field if non-nil, zero value otherwise.

### GetTruckContactOk

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetTruckContactOk() (*string, bool)`

GetTruckContactOk returns a tuple with the TruckContact field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckContact

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) SetTruckContact(v string)`

SetTruckContact sets TruckContact field to given value.

### HasTruckContact

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) HasTruckContact() bool`

HasTruckContact returns a boolean if a field has been set.

### GetScheduledShipDate

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetScheduledShipDate() string`

GetScheduledShipDate returns the ScheduledShipDate field if non-nil, zero value otherwise.

### GetScheduledShipDateOk

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetScheduledShipDateOk() (*string, bool)`

GetScheduledShipDateOk returns a tuple with the ScheduledShipDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScheduledShipDate

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) SetScheduledShipDate(v string)`

SetScheduledShipDate sets ScheduledShipDate field to given value.

### HasScheduledShipDate

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) HasScheduledShipDate() bool`

HasScheduledShipDate returns a boolean if a field has been set.

### GetMilkRunDescription

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetMilkRunDescription() string`

GetMilkRunDescription returns the MilkRunDescription field if non-nil, zero value otherwise.

### GetMilkRunDescriptionOk

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetMilkRunDescriptionOk() (*string, bool)`

GetMilkRunDescriptionOk returns a tuple with the MilkRunDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMilkRunDescription

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) SetMilkRunDescription(v string)`

SetMilkRunDescription sets MilkRunDescription field to given value.

### HasMilkRunDescription

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) HasMilkRunDescription() bool`

HasMilkRunDescription returns a boolean if a field has been set.

### GetTruckType

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetTruckType() string`

GetTruckType returns the TruckType field if non-nil, zero value otherwise.

### GetTruckTypeOk

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetTruckTypeOk() (*string, bool)`

GetTruckTypeOk returns a tuple with the TruckType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckType

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) SetTruckType(v string)`

SetTruckType sets TruckType field to given value.

### HasTruckType

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) HasTruckType() bool`

HasTruckType returns a boolean if a field has been set.

### GetTruckStatus

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetTruckStatus() string`

GetTruckStatus returns the TruckStatus field if non-nil, zero value otherwise.

### GetTruckStatusOk

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetTruckStatusOk() (*string, bool)`

GetTruckStatusOk returns a tuple with the TruckStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckStatus

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) SetTruckStatus(v string)`

SetTruckStatus sets TruckStatus field to given value.

### HasTruckStatus

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) HasTruckStatus() bool`

HasTruckStatus returns a boolean if a field has been set.

### GetTransMode

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetTransMode() string`

GetTransMode returns the TransMode field if non-nil, zero value otherwise.

### GetTransModeOk

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetTransModeOk() (*string, bool)`

GetTransModeOk returns a tuple with the TransMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransMode

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) SetTransMode(v string)`

SetTransMode sets TransMode field to given value.

### HasTransMode

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) HasTransMode() bool`

HasTransMode returns a boolean if a field has been set.

### GetDropshipSupplierId

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetDropshipSupplierId() string`

GetDropshipSupplierId returns the DropshipSupplierId field if non-nil, zero value otherwise.

### GetDropshipSupplierIdOk

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetDropshipSupplierIdOk() (*string, bool)`

GetDropshipSupplierIdOk returns a tuple with the DropshipSupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDropshipSupplierId

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) SetDropshipSupplierId(v string)`

SetDropshipSupplierId sets DropshipSupplierId field to given value.

### HasDropshipSupplierId

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) HasDropshipSupplierId() bool`

HasDropshipSupplierId returns a boolean if a field has been set.

### GetIncoTerms

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetIncoTerms() string`

GetIncoTerms returns the IncoTerms field if non-nil, zero value otherwise.

### GetIncoTermsOk

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetIncoTermsOk() (*string, bool)`

GetIncoTermsOk returns a tuple with the IncoTerms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncoTerms

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) SetIncoTerms(v string)`

SetIncoTerms sets IncoTerms field to given value.

### HasIncoTerms

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) HasIncoTerms() bool`

HasIncoTerms returns a boolean if a field has been set.

### GetCustomsBrokerSupplierId

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetCustomsBrokerSupplierId() string`

GetCustomsBrokerSupplierId returns the CustomsBrokerSupplierId field if non-nil, zero value otherwise.

### GetCustomsBrokerSupplierIdOk

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetCustomsBrokerSupplierIdOk() (*string, bool)`

GetCustomsBrokerSupplierIdOk returns a tuple with the CustomsBrokerSupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomsBrokerSupplierId

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) SetCustomsBrokerSupplierId(v string)`

SetCustomsBrokerSupplierId sets CustomsBrokerSupplierId field to given value.

### HasCustomsBrokerSupplierId

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) HasCustomsBrokerSupplierId() bool`

HasCustomsBrokerSupplierId returns a boolean if a field has been set.

### GetSubBuildingCode

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetSubBuildingCode() string`

GetSubBuildingCode returns the SubBuildingCode field if non-nil, zero value otherwise.

### GetSubBuildingCodeOk

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetSubBuildingCodeOk() (*string, bool)`

GetSubBuildingCodeOk returns a tuple with the SubBuildingCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubBuildingCode

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) SetSubBuildingCode(v string)`

SetSubBuildingCode sets SubBuildingCode field to given value.

### HasSubBuildingCode

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) HasSubBuildingCode() bool`

HasSubBuildingCode returns a boolean if a field has been set.

### GetTruckRoute

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetTruckRoute() string`

GetTruckRoute returns the TruckRoute field if non-nil, zero value otherwise.

### GetTruckRouteOk

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetTruckRouteOk() (*string, bool)`

GetTruckRouteOk returns a tuple with the TruckRoute field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckRoute

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) SetTruckRoute(v string)`

SetTruckRoute sets TruckRoute field to given value.

### HasTruckRoute

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) HasTruckRoute() bool`

HasTruckRoute returns a boolean if a field has been set.

### GetEstimatedArrivalDate

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetEstimatedArrivalDate() time.Time`

GetEstimatedArrivalDate returns the EstimatedArrivalDate field if non-nil, zero value otherwise.

### GetEstimatedArrivalDateOk

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetEstimatedArrivalDateOk() (*time.Time, bool)`

GetEstimatedArrivalDateOk returns a tuple with the EstimatedArrivalDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEstimatedArrivalDate

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) SetEstimatedArrivalDate(v time.Time)`

SetEstimatedArrivalDate sets EstimatedArrivalDate field to given value.

### HasEstimatedArrivalDate

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) HasEstimatedArrivalDate() bool`

HasEstimatedArrivalDate returns a boolean if a field has been set.

### GetTruckFreightAmount

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetTruckFreightAmount() float64`

GetTruckFreightAmount returns the TruckFreightAmount field if non-nil, zero value otherwise.

### GetTruckFreightAmountOk

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) GetTruckFreightAmountOk() (*float64, bool)`

GetTruckFreightAmountOk returns a tuple with the TruckFreightAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckFreightAmount

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) SetTruckFreightAmount(v float64)`

SetTruckFreightAmount sets TruckFreightAmount field to given value.

### HasTruckFreightAmount

`func (o *CustomerTrucksApiUpdateCustomerTruckRequest) HasTruckFreightAmount() bool`

HasTruckFreightAmount returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


