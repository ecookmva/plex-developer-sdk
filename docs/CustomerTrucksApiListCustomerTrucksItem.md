# CustomerTrucksApiListCustomerTrucksItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | A unique identifier for the truck. This will be automatically generated if omitted from the request. | [optional] 
**ShipDate** | Pointer to **time.Time** | The ship date assigned to the truck. | [optional] 
**FreightTerms** | Pointer to **string** | Terms of the freight payment; for example, COD, Collect, or Prepaid. | [optional] 
**TrackingNumber** | Pointer to **string** | The tracking number, often provided by a carrier, related to a specific shipment. | [optional] 
**TrailerNumber** | Pointer to **string** | The trailer number associated with the physical trailer that a specific shipment was shipped on. | [optional] 
**Note** | Pointer to **string** | A note assigned to the truck. | [optional] 
**TruckCalled** | Pointer to **bool** | Indicates if the carrier has been contacted. | [optional] 
**TruckArrivalTime** | Pointer to **time.Time** | The arrival time of the truck (arrival time can be planned or actual, depending on implementation). | [optional] 
**BolNumber** | Pointer to **string** | The bill of lading number. | [optional] 
**BolNote** | Pointer to **string** | A note on the bill of lading. | [optional] 
**Pool** | Pointer to **bool** | Indicates that the truck is part of a pool shipment. A pool is a central warehouse that redistributes shippers from one truck to another before shipping to customer locations. | [optional] 
**CarrierId** | Pointer to **string** | The ID of the carrier associated with the truck. (A carrier is a supplier with a supplier type of &amp;quot;Carrier&amp;quot;.) | [optional] 
**PoolCustomerAddressId** | Pointer to **string** | The customer address ID of the pool location associated with the truck. | [optional] 
**TrailerCarrierId** | Pointer to **string** | The ID of the supplier with a &amp;quot;Carrier&amp;quot; type used as the trailer carrier. | [optional] 
**BrokeredCarrierId** | Pointer to **string** | The ID of the supplier with a &amp;quot;Carrier&amp;quot; type used as the brokered carrier. | [optional] 
**TruckCalledDate** | Pointer to **time.Time** | The date the carrier was called regarding the shipment or truck. | [optional] 
**TruckConfirmation** | Pointer to **string** | The confirmation from the carrier regarding the shipment or truck. | [optional] 
**TruckContact** | Pointer to **string** | A contact person, typically at the carrier, regarding the shipment or truck. | [optional] 
**TruckDriverId** | Pointer to **string** | The Plex user ID of the truck driver associated with this Truck (Truck_Drive_Key). | [optional] 
**ShippedById** | Pointer to **string** | The ID of the user who shipped the truck. | [optional] 
**ScheduledShipDate** | Pointer to **time.Time** | The date on which the truck is scheduled to ship. | [optional] 
**CreatedById** | Pointer to **string** | The ID of the user who created the record. | [optional] 
**CreatedDate** | Pointer to **time.Time** | The date on which the record was created. | [optional] 
**ModifiedById** | Pointer to **string** | The ID of the user who last modified the record. | [optional] 
**ModifiedDate** | Pointer to **time.Time** | The date on which the record was last modified. | [optional] 
**MilkRun** | Pointer to **string** | The name of a route with multiple stops that happens on a recurring basis. | [optional] 
**Type** | Pointer to **string** | The truck type. | [optional] 
**Status** | Pointer to **string** | The truck status. | [optional] 
**TruckNumber** | Pointer to **string** | A Plex-generated unique number representing the truck shipment. | [optional] 
**TransMode** | Pointer to **string** | The transportation mode associated with the truck. | [optional] 
**ShipFromId** | Pointer to **string** | The ID of the customer address from which the truck was shipped. | [optional] 
**IncoTerms** | Pointer to **string** | International Commercial (INCO) terms applied to the sales order. | [optional] 
**CustomsBrokerSupplierId** | Pointer to **string** | The ID of the supplier with a &amp;quot;Customs Broker&amp;quot; type. | [optional] 
**SubBuilding** | Pointer to **string** | The sub-building code indicating the location in the building where the truck will be loaded. | [optional] 
**DropshipSupplierId** | Pointer to **string** | The dropship supplier resource ID associated with the truck. | [optional] 
**DropshipSupplierCode** | Pointer to **string** | The dropship supplier code associated with the truck. | [optional] 
**TruckRoute** | Pointer to **string** | The route for the truck. | [optional] 
**EstimatedArrivalDate** | Pointer to **time.Time** | The estimated arrival date of the truck. | [optional] 
**TruckFreightAmount** | Pointer to **float64** | The amount of the truck freight charge. | [optional] 
**TruckArrivalTimeOfDay** | Pointer to **string** | The time at which the truck arrived. | [optional] 

## Methods

### NewCustomerTrucksApiListCustomerTrucksItem

`func NewCustomerTrucksApiListCustomerTrucksItem() *CustomerTrucksApiListCustomerTrucksItem`

NewCustomerTrucksApiListCustomerTrucksItem instantiates a new CustomerTrucksApiListCustomerTrucksItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomerTrucksApiListCustomerTrucksItemWithDefaults

`func NewCustomerTrucksApiListCustomerTrucksItemWithDefaults() *CustomerTrucksApiListCustomerTrucksItem`

NewCustomerTrucksApiListCustomerTrucksItemWithDefaults instantiates a new CustomerTrucksApiListCustomerTrucksItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CustomerTrucksApiListCustomerTrucksItem) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *CustomerTrucksApiListCustomerTrucksItem) HasId() bool`

HasId returns a boolean if a field has been set.

### GetShipDate

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetShipDate() time.Time`

GetShipDate returns the ShipDate field if non-nil, zero value otherwise.

### GetShipDateOk

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetShipDateOk() (*time.Time, bool)`

GetShipDateOk returns a tuple with the ShipDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipDate

`func (o *CustomerTrucksApiListCustomerTrucksItem) SetShipDate(v time.Time)`

SetShipDate sets ShipDate field to given value.

### HasShipDate

`func (o *CustomerTrucksApiListCustomerTrucksItem) HasShipDate() bool`

HasShipDate returns a boolean if a field has been set.

### GetFreightTerms

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetFreightTerms() string`

GetFreightTerms returns the FreightTerms field if non-nil, zero value otherwise.

### GetFreightTermsOk

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetFreightTermsOk() (*string, bool)`

GetFreightTermsOk returns a tuple with the FreightTerms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFreightTerms

`func (o *CustomerTrucksApiListCustomerTrucksItem) SetFreightTerms(v string)`

SetFreightTerms sets FreightTerms field to given value.

### HasFreightTerms

`func (o *CustomerTrucksApiListCustomerTrucksItem) HasFreightTerms() bool`

HasFreightTerms returns a boolean if a field has been set.

### GetTrackingNumber

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetTrackingNumber() string`

GetTrackingNumber returns the TrackingNumber field if non-nil, zero value otherwise.

### GetTrackingNumberOk

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetTrackingNumberOk() (*string, bool)`

GetTrackingNumberOk returns a tuple with the TrackingNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackingNumber

`func (o *CustomerTrucksApiListCustomerTrucksItem) SetTrackingNumber(v string)`

SetTrackingNumber sets TrackingNumber field to given value.

### HasTrackingNumber

`func (o *CustomerTrucksApiListCustomerTrucksItem) HasTrackingNumber() bool`

HasTrackingNumber returns a boolean if a field has been set.

### GetTrailerNumber

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetTrailerNumber() string`

GetTrailerNumber returns the TrailerNumber field if non-nil, zero value otherwise.

### GetTrailerNumberOk

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetTrailerNumberOk() (*string, bool)`

GetTrailerNumberOk returns a tuple with the TrailerNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrailerNumber

`func (o *CustomerTrucksApiListCustomerTrucksItem) SetTrailerNumber(v string)`

SetTrailerNumber sets TrailerNumber field to given value.

### HasTrailerNumber

`func (o *CustomerTrucksApiListCustomerTrucksItem) HasTrailerNumber() bool`

HasTrailerNumber returns a boolean if a field has been set.

### GetNote

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *CustomerTrucksApiListCustomerTrucksItem) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *CustomerTrucksApiListCustomerTrucksItem) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetTruckCalled

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetTruckCalled() bool`

GetTruckCalled returns the TruckCalled field if non-nil, zero value otherwise.

### GetTruckCalledOk

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetTruckCalledOk() (*bool, bool)`

GetTruckCalledOk returns a tuple with the TruckCalled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckCalled

`func (o *CustomerTrucksApiListCustomerTrucksItem) SetTruckCalled(v bool)`

SetTruckCalled sets TruckCalled field to given value.

### HasTruckCalled

`func (o *CustomerTrucksApiListCustomerTrucksItem) HasTruckCalled() bool`

HasTruckCalled returns a boolean if a field has been set.

### GetTruckArrivalTime

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetTruckArrivalTime() time.Time`

GetTruckArrivalTime returns the TruckArrivalTime field if non-nil, zero value otherwise.

### GetTruckArrivalTimeOk

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetTruckArrivalTimeOk() (*time.Time, bool)`

GetTruckArrivalTimeOk returns a tuple with the TruckArrivalTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckArrivalTime

`func (o *CustomerTrucksApiListCustomerTrucksItem) SetTruckArrivalTime(v time.Time)`

SetTruckArrivalTime sets TruckArrivalTime field to given value.

### HasTruckArrivalTime

`func (o *CustomerTrucksApiListCustomerTrucksItem) HasTruckArrivalTime() bool`

HasTruckArrivalTime returns a boolean if a field has been set.

### GetBolNumber

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetBolNumber() string`

GetBolNumber returns the BolNumber field if non-nil, zero value otherwise.

### GetBolNumberOk

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetBolNumberOk() (*string, bool)`

GetBolNumberOk returns a tuple with the BolNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBolNumber

`func (o *CustomerTrucksApiListCustomerTrucksItem) SetBolNumber(v string)`

SetBolNumber sets BolNumber field to given value.

### HasBolNumber

`func (o *CustomerTrucksApiListCustomerTrucksItem) HasBolNumber() bool`

HasBolNumber returns a boolean if a field has been set.

### GetBolNote

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetBolNote() string`

GetBolNote returns the BolNote field if non-nil, zero value otherwise.

### GetBolNoteOk

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetBolNoteOk() (*string, bool)`

GetBolNoteOk returns a tuple with the BolNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBolNote

`func (o *CustomerTrucksApiListCustomerTrucksItem) SetBolNote(v string)`

SetBolNote sets BolNote field to given value.

### HasBolNote

`func (o *CustomerTrucksApiListCustomerTrucksItem) HasBolNote() bool`

HasBolNote returns a boolean if a field has been set.

### GetPool

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetPool() bool`

GetPool returns the Pool field if non-nil, zero value otherwise.

### GetPoolOk

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetPoolOk() (*bool, bool)`

GetPoolOk returns a tuple with the Pool field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPool

`func (o *CustomerTrucksApiListCustomerTrucksItem) SetPool(v bool)`

SetPool sets Pool field to given value.

### HasPool

`func (o *CustomerTrucksApiListCustomerTrucksItem) HasPool() bool`

HasPool returns a boolean if a field has been set.

### GetCarrierId

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetCarrierId() string`

GetCarrierId returns the CarrierId field if non-nil, zero value otherwise.

### GetCarrierIdOk

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetCarrierIdOk() (*string, bool)`

GetCarrierIdOk returns a tuple with the CarrierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierId

`func (o *CustomerTrucksApiListCustomerTrucksItem) SetCarrierId(v string)`

SetCarrierId sets CarrierId field to given value.

### HasCarrierId

`func (o *CustomerTrucksApiListCustomerTrucksItem) HasCarrierId() bool`

HasCarrierId returns a boolean if a field has been set.

### GetPoolCustomerAddressId

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetPoolCustomerAddressId() string`

GetPoolCustomerAddressId returns the PoolCustomerAddressId field if non-nil, zero value otherwise.

### GetPoolCustomerAddressIdOk

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetPoolCustomerAddressIdOk() (*string, bool)`

GetPoolCustomerAddressIdOk returns a tuple with the PoolCustomerAddressId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoolCustomerAddressId

`func (o *CustomerTrucksApiListCustomerTrucksItem) SetPoolCustomerAddressId(v string)`

SetPoolCustomerAddressId sets PoolCustomerAddressId field to given value.

### HasPoolCustomerAddressId

`func (o *CustomerTrucksApiListCustomerTrucksItem) HasPoolCustomerAddressId() bool`

HasPoolCustomerAddressId returns a boolean if a field has been set.

### GetTrailerCarrierId

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetTrailerCarrierId() string`

GetTrailerCarrierId returns the TrailerCarrierId field if non-nil, zero value otherwise.

### GetTrailerCarrierIdOk

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetTrailerCarrierIdOk() (*string, bool)`

GetTrailerCarrierIdOk returns a tuple with the TrailerCarrierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrailerCarrierId

`func (o *CustomerTrucksApiListCustomerTrucksItem) SetTrailerCarrierId(v string)`

SetTrailerCarrierId sets TrailerCarrierId field to given value.

### HasTrailerCarrierId

`func (o *CustomerTrucksApiListCustomerTrucksItem) HasTrailerCarrierId() bool`

HasTrailerCarrierId returns a boolean if a field has been set.

### GetBrokeredCarrierId

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetBrokeredCarrierId() string`

GetBrokeredCarrierId returns the BrokeredCarrierId field if non-nil, zero value otherwise.

### GetBrokeredCarrierIdOk

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetBrokeredCarrierIdOk() (*string, bool)`

GetBrokeredCarrierIdOk returns a tuple with the BrokeredCarrierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrokeredCarrierId

`func (o *CustomerTrucksApiListCustomerTrucksItem) SetBrokeredCarrierId(v string)`

SetBrokeredCarrierId sets BrokeredCarrierId field to given value.

### HasBrokeredCarrierId

`func (o *CustomerTrucksApiListCustomerTrucksItem) HasBrokeredCarrierId() bool`

HasBrokeredCarrierId returns a boolean if a field has been set.

### GetTruckCalledDate

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetTruckCalledDate() time.Time`

GetTruckCalledDate returns the TruckCalledDate field if non-nil, zero value otherwise.

### GetTruckCalledDateOk

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetTruckCalledDateOk() (*time.Time, bool)`

GetTruckCalledDateOk returns a tuple with the TruckCalledDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckCalledDate

`func (o *CustomerTrucksApiListCustomerTrucksItem) SetTruckCalledDate(v time.Time)`

SetTruckCalledDate sets TruckCalledDate field to given value.

### HasTruckCalledDate

`func (o *CustomerTrucksApiListCustomerTrucksItem) HasTruckCalledDate() bool`

HasTruckCalledDate returns a boolean if a field has been set.

### GetTruckConfirmation

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetTruckConfirmation() string`

GetTruckConfirmation returns the TruckConfirmation field if non-nil, zero value otherwise.

### GetTruckConfirmationOk

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetTruckConfirmationOk() (*string, bool)`

GetTruckConfirmationOk returns a tuple with the TruckConfirmation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckConfirmation

`func (o *CustomerTrucksApiListCustomerTrucksItem) SetTruckConfirmation(v string)`

SetTruckConfirmation sets TruckConfirmation field to given value.

### HasTruckConfirmation

`func (o *CustomerTrucksApiListCustomerTrucksItem) HasTruckConfirmation() bool`

HasTruckConfirmation returns a boolean if a field has been set.

### GetTruckContact

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetTruckContact() string`

GetTruckContact returns the TruckContact field if non-nil, zero value otherwise.

### GetTruckContactOk

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetTruckContactOk() (*string, bool)`

GetTruckContactOk returns a tuple with the TruckContact field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckContact

`func (o *CustomerTrucksApiListCustomerTrucksItem) SetTruckContact(v string)`

SetTruckContact sets TruckContact field to given value.

### HasTruckContact

`func (o *CustomerTrucksApiListCustomerTrucksItem) HasTruckContact() bool`

HasTruckContact returns a boolean if a field has been set.

### GetTruckDriverId

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetTruckDriverId() string`

GetTruckDriverId returns the TruckDriverId field if non-nil, zero value otherwise.

### GetTruckDriverIdOk

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetTruckDriverIdOk() (*string, bool)`

GetTruckDriverIdOk returns a tuple with the TruckDriverId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckDriverId

`func (o *CustomerTrucksApiListCustomerTrucksItem) SetTruckDriverId(v string)`

SetTruckDriverId sets TruckDriverId field to given value.

### HasTruckDriverId

`func (o *CustomerTrucksApiListCustomerTrucksItem) HasTruckDriverId() bool`

HasTruckDriverId returns a boolean if a field has been set.

### GetShippedById

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetShippedById() string`

GetShippedById returns the ShippedById field if non-nil, zero value otherwise.

### GetShippedByIdOk

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetShippedByIdOk() (*string, bool)`

GetShippedByIdOk returns a tuple with the ShippedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippedById

`func (o *CustomerTrucksApiListCustomerTrucksItem) SetShippedById(v string)`

SetShippedById sets ShippedById field to given value.

### HasShippedById

`func (o *CustomerTrucksApiListCustomerTrucksItem) HasShippedById() bool`

HasShippedById returns a boolean if a field has been set.

### GetScheduledShipDate

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetScheduledShipDate() time.Time`

GetScheduledShipDate returns the ScheduledShipDate field if non-nil, zero value otherwise.

### GetScheduledShipDateOk

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetScheduledShipDateOk() (*time.Time, bool)`

GetScheduledShipDateOk returns a tuple with the ScheduledShipDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScheduledShipDate

`func (o *CustomerTrucksApiListCustomerTrucksItem) SetScheduledShipDate(v time.Time)`

SetScheduledShipDate sets ScheduledShipDate field to given value.

### HasScheduledShipDate

`func (o *CustomerTrucksApiListCustomerTrucksItem) HasScheduledShipDate() bool`

HasScheduledShipDate returns a boolean if a field has been set.

### GetCreatedById

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetCreatedById() string`

GetCreatedById returns the CreatedById field if non-nil, zero value otherwise.

### GetCreatedByIdOk

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetCreatedByIdOk() (*string, bool)`

GetCreatedByIdOk returns a tuple with the CreatedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedById

`func (o *CustomerTrucksApiListCustomerTrucksItem) SetCreatedById(v string)`

SetCreatedById sets CreatedById field to given value.

### HasCreatedById

`func (o *CustomerTrucksApiListCustomerTrucksItem) HasCreatedById() bool`

HasCreatedById returns a boolean if a field has been set.

### GetCreatedDate

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *CustomerTrucksApiListCustomerTrucksItem) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *CustomerTrucksApiListCustomerTrucksItem) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.

### GetModifiedById

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *CustomerTrucksApiListCustomerTrucksItem) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *CustomerTrucksApiListCustomerTrucksItem) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetModifiedDate

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetModifiedDate() time.Time`

GetModifiedDate returns the ModifiedDate field if non-nil, zero value otherwise.

### GetModifiedDateOk

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetModifiedDateOk() (*time.Time, bool)`

GetModifiedDateOk returns a tuple with the ModifiedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDate

`func (o *CustomerTrucksApiListCustomerTrucksItem) SetModifiedDate(v time.Time)`

SetModifiedDate sets ModifiedDate field to given value.

### HasModifiedDate

`func (o *CustomerTrucksApiListCustomerTrucksItem) HasModifiedDate() bool`

HasModifiedDate returns a boolean if a field has been set.

### GetMilkRun

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetMilkRun() string`

GetMilkRun returns the MilkRun field if non-nil, zero value otherwise.

### GetMilkRunOk

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetMilkRunOk() (*string, bool)`

GetMilkRunOk returns a tuple with the MilkRun field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMilkRun

`func (o *CustomerTrucksApiListCustomerTrucksItem) SetMilkRun(v string)`

SetMilkRun sets MilkRun field to given value.

### HasMilkRun

`func (o *CustomerTrucksApiListCustomerTrucksItem) HasMilkRun() bool`

HasMilkRun returns a boolean if a field has been set.

### GetType

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *CustomerTrucksApiListCustomerTrucksItem) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *CustomerTrucksApiListCustomerTrucksItem) HasType() bool`

HasType returns a boolean if a field has been set.

### GetStatus

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CustomerTrucksApiListCustomerTrucksItem) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *CustomerTrucksApiListCustomerTrucksItem) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetTruckNumber

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetTruckNumber() string`

GetTruckNumber returns the TruckNumber field if non-nil, zero value otherwise.

### GetTruckNumberOk

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetTruckNumberOk() (*string, bool)`

GetTruckNumberOk returns a tuple with the TruckNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckNumber

`func (o *CustomerTrucksApiListCustomerTrucksItem) SetTruckNumber(v string)`

SetTruckNumber sets TruckNumber field to given value.

### HasTruckNumber

`func (o *CustomerTrucksApiListCustomerTrucksItem) HasTruckNumber() bool`

HasTruckNumber returns a boolean if a field has been set.

### GetTransMode

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetTransMode() string`

GetTransMode returns the TransMode field if non-nil, zero value otherwise.

### GetTransModeOk

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetTransModeOk() (*string, bool)`

GetTransModeOk returns a tuple with the TransMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransMode

`func (o *CustomerTrucksApiListCustomerTrucksItem) SetTransMode(v string)`

SetTransMode sets TransMode field to given value.

### HasTransMode

`func (o *CustomerTrucksApiListCustomerTrucksItem) HasTransMode() bool`

HasTransMode returns a boolean if a field has been set.

### GetShipFromId

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetShipFromId() string`

GetShipFromId returns the ShipFromId field if non-nil, zero value otherwise.

### GetShipFromIdOk

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetShipFromIdOk() (*string, bool)`

GetShipFromIdOk returns a tuple with the ShipFromId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipFromId

`func (o *CustomerTrucksApiListCustomerTrucksItem) SetShipFromId(v string)`

SetShipFromId sets ShipFromId field to given value.

### HasShipFromId

`func (o *CustomerTrucksApiListCustomerTrucksItem) HasShipFromId() bool`

HasShipFromId returns a boolean if a field has been set.

### GetIncoTerms

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetIncoTerms() string`

GetIncoTerms returns the IncoTerms field if non-nil, zero value otherwise.

### GetIncoTermsOk

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetIncoTermsOk() (*string, bool)`

GetIncoTermsOk returns a tuple with the IncoTerms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncoTerms

`func (o *CustomerTrucksApiListCustomerTrucksItem) SetIncoTerms(v string)`

SetIncoTerms sets IncoTerms field to given value.

### HasIncoTerms

`func (o *CustomerTrucksApiListCustomerTrucksItem) HasIncoTerms() bool`

HasIncoTerms returns a boolean if a field has been set.

### GetCustomsBrokerSupplierId

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetCustomsBrokerSupplierId() string`

GetCustomsBrokerSupplierId returns the CustomsBrokerSupplierId field if non-nil, zero value otherwise.

### GetCustomsBrokerSupplierIdOk

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetCustomsBrokerSupplierIdOk() (*string, bool)`

GetCustomsBrokerSupplierIdOk returns a tuple with the CustomsBrokerSupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomsBrokerSupplierId

`func (o *CustomerTrucksApiListCustomerTrucksItem) SetCustomsBrokerSupplierId(v string)`

SetCustomsBrokerSupplierId sets CustomsBrokerSupplierId field to given value.

### HasCustomsBrokerSupplierId

`func (o *CustomerTrucksApiListCustomerTrucksItem) HasCustomsBrokerSupplierId() bool`

HasCustomsBrokerSupplierId returns a boolean if a field has been set.

### GetSubBuilding

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetSubBuilding() string`

GetSubBuilding returns the SubBuilding field if non-nil, zero value otherwise.

### GetSubBuildingOk

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetSubBuildingOk() (*string, bool)`

GetSubBuildingOk returns a tuple with the SubBuilding field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubBuilding

`func (o *CustomerTrucksApiListCustomerTrucksItem) SetSubBuilding(v string)`

SetSubBuilding sets SubBuilding field to given value.

### HasSubBuilding

`func (o *CustomerTrucksApiListCustomerTrucksItem) HasSubBuilding() bool`

HasSubBuilding returns a boolean if a field has been set.

### GetDropshipSupplierId

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetDropshipSupplierId() string`

GetDropshipSupplierId returns the DropshipSupplierId field if non-nil, zero value otherwise.

### GetDropshipSupplierIdOk

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetDropshipSupplierIdOk() (*string, bool)`

GetDropshipSupplierIdOk returns a tuple with the DropshipSupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDropshipSupplierId

`func (o *CustomerTrucksApiListCustomerTrucksItem) SetDropshipSupplierId(v string)`

SetDropshipSupplierId sets DropshipSupplierId field to given value.

### HasDropshipSupplierId

`func (o *CustomerTrucksApiListCustomerTrucksItem) HasDropshipSupplierId() bool`

HasDropshipSupplierId returns a boolean if a field has been set.

### GetDropshipSupplierCode

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetDropshipSupplierCode() string`

GetDropshipSupplierCode returns the DropshipSupplierCode field if non-nil, zero value otherwise.

### GetDropshipSupplierCodeOk

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetDropshipSupplierCodeOk() (*string, bool)`

GetDropshipSupplierCodeOk returns a tuple with the DropshipSupplierCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDropshipSupplierCode

`func (o *CustomerTrucksApiListCustomerTrucksItem) SetDropshipSupplierCode(v string)`

SetDropshipSupplierCode sets DropshipSupplierCode field to given value.

### HasDropshipSupplierCode

`func (o *CustomerTrucksApiListCustomerTrucksItem) HasDropshipSupplierCode() bool`

HasDropshipSupplierCode returns a boolean if a field has been set.

### GetTruckRoute

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetTruckRoute() string`

GetTruckRoute returns the TruckRoute field if non-nil, zero value otherwise.

### GetTruckRouteOk

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetTruckRouteOk() (*string, bool)`

GetTruckRouteOk returns a tuple with the TruckRoute field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckRoute

`func (o *CustomerTrucksApiListCustomerTrucksItem) SetTruckRoute(v string)`

SetTruckRoute sets TruckRoute field to given value.

### HasTruckRoute

`func (o *CustomerTrucksApiListCustomerTrucksItem) HasTruckRoute() bool`

HasTruckRoute returns a boolean if a field has been set.

### GetEstimatedArrivalDate

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetEstimatedArrivalDate() time.Time`

GetEstimatedArrivalDate returns the EstimatedArrivalDate field if non-nil, zero value otherwise.

### GetEstimatedArrivalDateOk

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetEstimatedArrivalDateOk() (*time.Time, bool)`

GetEstimatedArrivalDateOk returns a tuple with the EstimatedArrivalDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEstimatedArrivalDate

`func (o *CustomerTrucksApiListCustomerTrucksItem) SetEstimatedArrivalDate(v time.Time)`

SetEstimatedArrivalDate sets EstimatedArrivalDate field to given value.

### HasEstimatedArrivalDate

`func (o *CustomerTrucksApiListCustomerTrucksItem) HasEstimatedArrivalDate() bool`

HasEstimatedArrivalDate returns a boolean if a field has been set.

### GetTruckFreightAmount

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetTruckFreightAmount() float64`

GetTruckFreightAmount returns the TruckFreightAmount field if non-nil, zero value otherwise.

### GetTruckFreightAmountOk

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetTruckFreightAmountOk() (*float64, bool)`

GetTruckFreightAmountOk returns a tuple with the TruckFreightAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckFreightAmount

`func (o *CustomerTrucksApiListCustomerTrucksItem) SetTruckFreightAmount(v float64)`

SetTruckFreightAmount sets TruckFreightAmount field to given value.

### HasTruckFreightAmount

`func (o *CustomerTrucksApiListCustomerTrucksItem) HasTruckFreightAmount() bool`

HasTruckFreightAmount returns a boolean if a field has been set.

### GetTruckArrivalTimeOfDay

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetTruckArrivalTimeOfDay() string`

GetTruckArrivalTimeOfDay returns the TruckArrivalTimeOfDay field if non-nil, zero value otherwise.

### GetTruckArrivalTimeOfDayOk

`func (o *CustomerTrucksApiListCustomerTrucksItem) GetTruckArrivalTimeOfDayOk() (*string, bool)`

GetTruckArrivalTimeOfDayOk returns a tuple with the TruckArrivalTimeOfDay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckArrivalTimeOfDay

`func (o *CustomerTrucksApiListCustomerTrucksItem) SetTruckArrivalTimeOfDay(v string)`

SetTruckArrivalTimeOfDay sets TruckArrivalTimeOfDay field to given value.

### HasTruckArrivalTimeOfDay

`func (o *CustomerTrucksApiListCustomerTrucksItem) HasTruckArrivalTimeOfDay() bool`

HasTruckArrivalTimeOfDay returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


