# CustomerTrucksApiCreateCustomerTruck201Response

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

### NewCustomerTrucksApiCreateCustomerTruck201Response

`func NewCustomerTrucksApiCreateCustomerTruck201Response() *CustomerTrucksApiCreateCustomerTruck201Response`

NewCustomerTrucksApiCreateCustomerTruck201Response instantiates a new CustomerTrucksApiCreateCustomerTruck201Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomerTrucksApiCreateCustomerTruck201ResponseWithDefaults

`func NewCustomerTrucksApiCreateCustomerTruck201ResponseWithDefaults() *CustomerTrucksApiCreateCustomerTruck201Response`

NewCustomerTrucksApiCreateCustomerTruck201ResponseWithDefaults instantiates a new CustomerTrucksApiCreateCustomerTruck201Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) HasId() bool`

HasId returns a boolean if a field has been set.

### GetShipDate

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetShipDate() time.Time`

GetShipDate returns the ShipDate field if non-nil, zero value otherwise.

### GetShipDateOk

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetShipDateOk() (*time.Time, bool)`

GetShipDateOk returns a tuple with the ShipDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipDate

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) SetShipDate(v time.Time)`

SetShipDate sets ShipDate field to given value.

### HasShipDate

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) HasShipDate() bool`

HasShipDate returns a boolean if a field has been set.

### GetFreightTerms

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetFreightTerms() string`

GetFreightTerms returns the FreightTerms field if non-nil, zero value otherwise.

### GetFreightTermsOk

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetFreightTermsOk() (*string, bool)`

GetFreightTermsOk returns a tuple with the FreightTerms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFreightTerms

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) SetFreightTerms(v string)`

SetFreightTerms sets FreightTerms field to given value.

### HasFreightTerms

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) HasFreightTerms() bool`

HasFreightTerms returns a boolean if a field has been set.

### GetTrackingNumber

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetTrackingNumber() string`

GetTrackingNumber returns the TrackingNumber field if non-nil, zero value otherwise.

### GetTrackingNumberOk

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetTrackingNumberOk() (*string, bool)`

GetTrackingNumberOk returns a tuple with the TrackingNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackingNumber

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) SetTrackingNumber(v string)`

SetTrackingNumber sets TrackingNumber field to given value.

### HasTrackingNumber

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) HasTrackingNumber() bool`

HasTrackingNumber returns a boolean if a field has been set.

### GetTrailerNumber

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetTrailerNumber() string`

GetTrailerNumber returns the TrailerNumber field if non-nil, zero value otherwise.

### GetTrailerNumberOk

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetTrailerNumberOk() (*string, bool)`

GetTrailerNumberOk returns a tuple with the TrailerNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrailerNumber

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) SetTrailerNumber(v string)`

SetTrailerNumber sets TrailerNumber field to given value.

### HasTrailerNumber

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) HasTrailerNumber() bool`

HasTrailerNumber returns a boolean if a field has been set.

### GetNote

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetTruckCalled

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetTruckCalled() bool`

GetTruckCalled returns the TruckCalled field if non-nil, zero value otherwise.

### GetTruckCalledOk

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetTruckCalledOk() (*bool, bool)`

GetTruckCalledOk returns a tuple with the TruckCalled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckCalled

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) SetTruckCalled(v bool)`

SetTruckCalled sets TruckCalled field to given value.

### HasTruckCalled

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) HasTruckCalled() bool`

HasTruckCalled returns a boolean if a field has been set.

### GetTruckArrivalTime

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetTruckArrivalTime() time.Time`

GetTruckArrivalTime returns the TruckArrivalTime field if non-nil, zero value otherwise.

### GetTruckArrivalTimeOk

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetTruckArrivalTimeOk() (*time.Time, bool)`

GetTruckArrivalTimeOk returns a tuple with the TruckArrivalTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckArrivalTime

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) SetTruckArrivalTime(v time.Time)`

SetTruckArrivalTime sets TruckArrivalTime field to given value.

### HasTruckArrivalTime

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) HasTruckArrivalTime() bool`

HasTruckArrivalTime returns a boolean if a field has been set.

### GetBolNumber

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetBolNumber() string`

GetBolNumber returns the BolNumber field if non-nil, zero value otherwise.

### GetBolNumberOk

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetBolNumberOk() (*string, bool)`

GetBolNumberOk returns a tuple with the BolNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBolNumber

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) SetBolNumber(v string)`

SetBolNumber sets BolNumber field to given value.

### HasBolNumber

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) HasBolNumber() bool`

HasBolNumber returns a boolean if a field has been set.

### GetBolNote

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetBolNote() string`

GetBolNote returns the BolNote field if non-nil, zero value otherwise.

### GetBolNoteOk

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetBolNoteOk() (*string, bool)`

GetBolNoteOk returns a tuple with the BolNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBolNote

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) SetBolNote(v string)`

SetBolNote sets BolNote field to given value.

### HasBolNote

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) HasBolNote() bool`

HasBolNote returns a boolean if a field has been set.

### GetPool

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetPool() bool`

GetPool returns the Pool field if non-nil, zero value otherwise.

### GetPoolOk

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetPoolOk() (*bool, bool)`

GetPoolOk returns a tuple with the Pool field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPool

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) SetPool(v bool)`

SetPool sets Pool field to given value.

### HasPool

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) HasPool() bool`

HasPool returns a boolean if a field has been set.

### GetCarrierId

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetCarrierId() string`

GetCarrierId returns the CarrierId field if non-nil, zero value otherwise.

### GetCarrierIdOk

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetCarrierIdOk() (*string, bool)`

GetCarrierIdOk returns a tuple with the CarrierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierId

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) SetCarrierId(v string)`

SetCarrierId sets CarrierId field to given value.

### HasCarrierId

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) HasCarrierId() bool`

HasCarrierId returns a boolean if a field has been set.

### GetPoolCustomerAddressId

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetPoolCustomerAddressId() string`

GetPoolCustomerAddressId returns the PoolCustomerAddressId field if non-nil, zero value otherwise.

### GetPoolCustomerAddressIdOk

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetPoolCustomerAddressIdOk() (*string, bool)`

GetPoolCustomerAddressIdOk returns a tuple with the PoolCustomerAddressId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoolCustomerAddressId

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) SetPoolCustomerAddressId(v string)`

SetPoolCustomerAddressId sets PoolCustomerAddressId field to given value.

### HasPoolCustomerAddressId

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) HasPoolCustomerAddressId() bool`

HasPoolCustomerAddressId returns a boolean if a field has been set.

### GetTrailerCarrierId

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetTrailerCarrierId() string`

GetTrailerCarrierId returns the TrailerCarrierId field if non-nil, zero value otherwise.

### GetTrailerCarrierIdOk

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetTrailerCarrierIdOk() (*string, bool)`

GetTrailerCarrierIdOk returns a tuple with the TrailerCarrierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrailerCarrierId

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) SetTrailerCarrierId(v string)`

SetTrailerCarrierId sets TrailerCarrierId field to given value.

### HasTrailerCarrierId

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) HasTrailerCarrierId() bool`

HasTrailerCarrierId returns a boolean if a field has been set.

### GetBrokeredCarrierId

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetBrokeredCarrierId() string`

GetBrokeredCarrierId returns the BrokeredCarrierId field if non-nil, zero value otherwise.

### GetBrokeredCarrierIdOk

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetBrokeredCarrierIdOk() (*string, bool)`

GetBrokeredCarrierIdOk returns a tuple with the BrokeredCarrierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrokeredCarrierId

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) SetBrokeredCarrierId(v string)`

SetBrokeredCarrierId sets BrokeredCarrierId field to given value.

### HasBrokeredCarrierId

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) HasBrokeredCarrierId() bool`

HasBrokeredCarrierId returns a boolean if a field has been set.

### GetTruckCalledDate

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetTruckCalledDate() time.Time`

GetTruckCalledDate returns the TruckCalledDate field if non-nil, zero value otherwise.

### GetTruckCalledDateOk

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetTruckCalledDateOk() (*time.Time, bool)`

GetTruckCalledDateOk returns a tuple with the TruckCalledDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckCalledDate

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) SetTruckCalledDate(v time.Time)`

SetTruckCalledDate sets TruckCalledDate field to given value.

### HasTruckCalledDate

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) HasTruckCalledDate() bool`

HasTruckCalledDate returns a boolean if a field has been set.

### GetTruckConfirmation

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetTruckConfirmation() string`

GetTruckConfirmation returns the TruckConfirmation field if non-nil, zero value otherwise.

### GetTruckConfirmationOk

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetTruckConfirmationOk() (*string, bool)`

GetTruckConfirmationOk returns a tuple with the TruckConfirmation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckConfirmation

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) SetTruckConfirmation(v string)`

SetTruckConfirmation sets TruckConfirmation field to given value.

### HasTruckConfirmation

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) HasTruckConfirmation() bool`

HasTruckConfirmation returns a boolean if a field has been set.

### GetTruckContact

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetTruckContact() string`

GetTruckContact returns the TruckContact field if non-nil, zero value otherwise.

### GetTruckContactOk

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetTruckContactOk() (*string, bool)`

GetTruckContactOk returns a tuple with the TruckContact field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckContact

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) SetTruckContact(v string)`

SetTruckContact sets TruckContact field to given value.

### HasTruckContact

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) HasTruckContact() bool`

HasTruckContact returns a boolean if a field has been set.

### GetTruckDriverId

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetTruckDriverId() string`

GetTruckDriverId returns the TruckDriverId field if non-nil, zero value otherwise.

### GetTruckDriverIdOk

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetTruckDriverIdOk() (*string, bool)`

GetTruckDriverIdOk returns a tuple with the TruckDriverId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckDriverId

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) SetTruckDriverId(v string)`

SetTruckDriverId sets TruckDriverId field to given value.

### HasTruckDriverId

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) HasTruckDriverId() bool`

HasTruckDriverId returns a boolean if a field has been set.

### GetShippedById

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetShippedById() string`

GetShippedById returns the ShippedById field if non-nil, zero value otherwise.

### GetShippedByIdOk

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetShippedByIdOk() (*string, bool)`

GetShippedByIdOk returns a tuple with the ShippedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippedById

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) SetShippedById(v string)`

SetShippedById sets ShippedById field to given value.

### HasShippedById

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) HasShippedById() bool`

HasShippedById returns a boolean if a field has been set.

### GetScheduledShipDate

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetScheduledShipDate() time.Time`

GetScheduledShipDate returns the ScheduledShipDate field if non-nil, zero value otherwise.

### GetScheduledShipDateOk

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetScheduledShipDateOk() (*time.Time, bool)`

GetScheduledShipDateOk returns a tuple with the ScheduledShipDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScheduledShipDate

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) SetScheduledShipDate(v time.Time)`

SetScheduledShipDate sets ScheduledShipDate field to given value.

### HasScheduledShipDate

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) HasScheduledShipDate() bool`

HasScheduledShipDate returns a boolean if a field has been set.

### GetCreatedById

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetCreatedById() string`

GetCreatedById returns the CreatedById field if non-nil, zero value otherwise.

### GetCreatedByIdOk

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetCreatedByIdOk() (*string, bool)`

GetCreatedByIdOk returns a tuple with the CreatedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedById

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) SetCreatedById(v string)`

SetCreatedById sets CreatedById field to given value.

### HasCreatedById

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) HasCreatedById() bool`

HasCreatedById returns a boolean if a field has been set.

### GetCreatedDate

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.

### GetModifiedById

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetModifiedDate

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetModifiedDate() time.Time`

GetModifiedDate returns the ModifiedDate field if non-nil, zero value otherwise.

### GetModifiedDateOk

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetModifiedDateOk() (*time.Time, bool)`

GetModifiedDateOk returns a tuple with the ModifiedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDate

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) SetModifiedDate(v time.Time)`

SetModifiedDate sets ModifiedDate field to given value.

### HasModifiedDate

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) HasModifiedDate() bool`

HasModifiedDate returns a boolean if a field has been set.

### GetMilkRun

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetMilkRun() string`

GetMilkRun returns the MilkRun field if non-nil, zero value otherwise.

### GetMilkRunOk

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetMilkRunOk() (*string, bool)`

GetMilkRunOk returns a tuple with the MilkRun field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMilkRun

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) SetMilkRun(v string)`

SetMilkRun sets MilkRun field to given value.

### HasMilkRun

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) HasMilkRun() bool`

HasMilkRun returns a boolean if a field has been set.

### GetType

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) HasType() bool`

HasType returns a boolean if a field has been set.

### GetStatus

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetTruckNumber

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetTruckNumber() string`

GetTruckNumber returns the TruckNumber field if non-nil, zero value otherwise.

### GetTruckNumberOk

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetTruckNumberOk() (*string, bool)`

GetTruckNumberOk returns a tuple with the TruckNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckNumber

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) SetTruckNumber(v string)`

SetTruckNumber sets TruckNumber field to given value.

### HasTruckNumber

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) HasTruckNumber() bool`

HasTruckNumber returns a boolean if a field has been set.

### GetTransMode

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetTransMode() string`

GetTransMode returns the TransMode field if non-nil, zero value otherwise.

### GetTransModeOk

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetTransModeOk() (*string, bool)`

GetTransModeOk returns a tuple with the TransMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransMode

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) SetTransMode(v string)`

SetTransMode sets TransMode field to given value.

### HasTransMode

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) HasTransMode() bool`

HasTransMode returns a boolean if a field has been set.

### GetShipFromId

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetShipFromId() string`

GetShipFromId returns the ShipFromId field if non-nil, zero value otherwise.

### GetShipFromIdOk

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetShipFromIdOk() (*string, bool)`

GetShipFromIdOk returns a tuple with the ShipFromId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipFromId

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) SetShipFromId(v string)`

SetShipFromId sets ShipFromId field to given value.

### HasShipFromId

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) HasShipFromId() bool`

HasShipFromId returns a boolean if a field has been set.

### GetIncoTerms

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetIncoTerms() string`

GetIncoTerms returns the IncoTerms field if non-nil, zero value otherwise.

### GetIncoTermsOk

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetIncoTermsOk() (*string, bool)`

GetIncoTermsOk returns a tuple with the IncoTerms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncoTerms

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) SetIncoTerms(v string)`

SetIncoTerms sets IncoTerms field to given value.

### HasIncoTerms

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) HasIncoTerms() bool`

HasIncoTerms returns a boolean if a field has been set.

### GetCustomsBrokerSupplierId

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetCustomsBrokerSupplierId() string`

GetCustomsBrokerSupplierId returns the CustomsBrokerSupplierId field if non-nil, zero value otherwise.

### GetCustomsBrokerSupplierIdOk

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetCustomsBrokerSupplierIdOk() (*string, bool)`

GetCustomsBrokerSupplierIdOk returns a tuple with the CustomsBrokerSupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomsBrokerSupplierId

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) SetCustomsBrokerSupplierId(v string)`

SetCustomsBrokerSupplierId sets CustomsBrokerSupplierId field to given value.

### HasCustomsBrokerSupplierId

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) HasCustomsBrokerSupplierId() bool`

HasCustomsBrokerSupplierId returns a boolean if a field has been set.

### GetSubBuilding

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetSubBuilding() string`

GetSubBuilding returns the SubBuilding field if non-nil, zero value otherwise.

### GetSubBuildingOk

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetSubBuildingOk() (*string, bool)`

GetSubBuildingOk returns a tuple with the SubBuilding field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubBuilding

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) SetSubBuilding(v string)`

SetSubBuilding sets SubBuilding field to given value.

### HasSubBuilding

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) HasSubBuilding() bool`

HasSubBuilding returns a boolean if a field has been set.

### GetDropshipSupplierId

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetDropshipSupplierId() string`

GetDropshipSupplierId returns the DropshipSupplierId field if non-nil, zero value otherwise.

### GetDropshipSupplierIdOk

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetDropshipSupplierIdOk() (*string, bool)`

GetDropshipSupplierIdOk returns a tuple with the DropshipSupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDropshipSupplierId

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) SetDropshipSupplierId(v string)`

SetDropshipSupplierId sets DropshipSupplierId field to given value.

### HasDropshipSupplierId

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) HasDropshipSupplierId() bool`

HasDropshipSupplierId returns a boolean if a field has been set.

### GetDropshipSupplierCode

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetDropshipSupplierCode() string`

GetDropshipSupplierCode returns the DropshipSupplierCode field if non-nil, zero value otherwise.

### GetDropshipSupplierCodeOk

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetDropshipSupplierCodeOk() (*string, bool)`

GetDropshipSupplierCodeOk returns a tuple with the DropshipSupplierCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDropshipSupplierCode

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) SetDropshipSupplierCode(v string)`

SetDropshipSupplierCode sets DropshipSupplierCode field to given value.

### HasDropshipSupplierCode

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) HasDropshipSupplierCode() bool`

HasDropshipSupplierCode returns a boolean if a field has been set.

### GetTruckRoute

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetTruckRoute() string`

GetTruckRoute returns the TruckRoute field if non-nil, zero value otherwise.

### GetTruckRouteOk

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetTruckRouteOk() (*string, bool)`

GetTruckRouteOk returns a tuple with the TruckRoute field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckRoute

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) SetTruckRoute(v string)`

SetTruckRoute sets TruckRoute field to given value.

### HasTruckRoute

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) HasTruckRoute() bool`

HasTruckRoute returns a boolean if a field has been set.

### GetEstimatedArrivalDate

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetEstimatedArrivalDate() time.Time`

GetEstimatedArrivalDate returns the EstimatedArrivalDate field if non-nil, zero value otherwise.

### GetEstimatedArrivalDateOk

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetEstimatedArrivalDateOk() (*time.Time, bool)`

GetEstimatedArrivalDateOk returns a tuple with the EstimatedArrivalDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEstimatedArrivalDate

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) SetEstimatedArrivalDate(v time.Time)`

SetEstimatedArrivalDate sets EstimatedArrivalDate field to given value.

### HasEstimatedArrivalDate

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) HasEstimatedArrivalDate() bool`

HasEstimatedArrivalDate returns a boolean if a field has been set.

### GetTruckFreightAmount

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetTruckFreightAmount() float64`

GetTruckFreightAmount returns the TruckFreightAmount field if non-nil, zero value otherwise.

### GetTruckFreightAmountOk

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetTruckFreightAmountOk() (*float64, bool)`

GetTruckFreightAmountOk returns a tuple with the TruckFreightAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckFreightAmount

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) SetTruckFreightAmount(v float64)`

SetTruckFreightAmount sets TruckFreightAmount field to given value.

### HasTruckFreightAmount

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) HasTruckFreightAmount() bool`

HasTruckFreightAmount returns a boolean if a field has been set.

### GetTruckArrivalTimeOfDay

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetTruckArrivalTimeOfDay() string`

GetTruckArrivalTimeOfDay returns the TruckArrivalTimeOfDay field if non-nil, zero value otherwise.

### GetTruckArrivalTimeOfDayOk

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) GetTruckArrivalTimeOfDayOk() (*string, bool)`

GetTruckArrivalTimeOfDayOk returns a tuple with the TruckArrivalTimeOfDay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckArrivalTimeOfDay

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) SetTruckArrivalTimeOfDay(v string)`

SetTruckArrivalTimeOfDay sets TruckArrivalTimeOfDay field to given value.

### HasTruckArrivalTimeOfDay

`func (o *CustomerTrucksApiCreateCustomerTruck201Response) HasTruckArrivalTimeOfDay() bool`

HasTruckArrivalTimeOfDay returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


