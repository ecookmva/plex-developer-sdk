# AddressesItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | A unique identifier for the Customer Address. This will be automatically generated if omitted from the request. | [optional] 
**Code** | Pointer to **string** |  | [optional] 
**Note** | Pointer to **string** |  | [optional] 
**QuoteTo** | Pointer to **bool** | If true, this address may be used for customer quotes. | [optional] 
**ShipTo** | Pointer to **bool** | If true, this address may be used for customer shipping. | [optional] 
**BillTo** | Pointer to **bool** | If true, this address may be used for customer invoices. | [optional] 
**BillToAddressId** | Pointer to **string** | The customer address ID to be used for customer billing. | [optional] 
**RemitTo** | Pointer to **bool** | If true, this address may be used for remittance. | [optional] 
**ThirdPartyShipTo** | Pointer to **bool** | If true, this is a valid third-party shipping address. | [optional] 
**ThirdPartyShipToAddressId** | Pointer to **string** | The customer address ID to be used for third-party shipping. | [optional] 
**Pool** | Pointer to **bool** | If true, this is a valid pool address. A pool is a location used to organize shipments and routes the shippers to the Ship To location. | [optional] 
**PoolAddressId** | Pointer to **string** | The customer address ID to be used for pooling. | [optional] 
**OldCustomerNo** | Pointer to **string** |  | [optional] 
**Active** | Pointer to **bool** |  | [optional] 
**Phone** | Pointer to **string** |  | [optional] 
**Fax** | Pointer to **string** |  | [optional] 
**Email** | Pointer to **string** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Address** | Pointer to **string** |  | [optional] 
**City** | Pointer to **string** |  | [optional] 
**State** | Pointer to **string** |  | [optional] 
**Zip** | Pointer to **string** |  | [optional] 
**Country** | Pointer to **string** |  | [optional] 
**Region** | Pointer to **string** |  | [optional] 
**County** | Pointer to **string** |  | [optional] 
**ShippingInstructions** | Pointer to **string** |  | [optional] 
**IgnoreTransitOnWeekends** | Pointer to **bool** |  | [optional] 
**TransportationLeadTime** | Pointer to **int32** |  | [optional] 
**DefaultCarrierIds** | Pointer to **[]string** | A list of Default Carriers, by Supplier ID. | [optional] 
**TruckType** | Pointer to **string** | Screen: Truck Types | [optional] 
**SalesTaxExempt** | Pointer to **bool** |  | [optional] 
**SalespersonId** | Pointer to **string** | The salesperson assigned to this customer, by IAM account ID. | [optional] 
**StatementAddressId** | Pointer to **string** | The address to which statements should be sent, if this address is a valid Billing address. | [optional] 
**FreightTerms** | Pointer to **string** | Setup Table: Freight Terms | [optional] 
**InsideSalespersonId** | Pointer to **string** | The salesperson assigned to this customer, by IAM account ID. | [optional] 
**DefaultShipFrom** | Pointer to **string** | Screen: Building List | [optional] 
**FreightBillTo** | Pointer to **bool** | If true, this is a valid address for freight billing. | [optional] 
**FreightBillToAddressId** | Pointer to **string** | The customer address to be used for freight billing. | [optional] 
**Catalog** | Pointer to **string** | Screen: Catalogs | [optional] 
**SoldTo** | Pointer to **bool** |  | [optional] 
**DunsNo** | Pointer to **string** |  | [optional] 
**CommercialInvoiceVatNo** | Pointer to **string** |  | [optional] 
**Terms** | Pointer to **string** | Setup Table: Terms | [optional] 
**Template** | Pointer to **bool** | Only one address can be used as the address template. | [optional] 
**IncoTerms** | Pointer to **string** |  | [optional] 
**NegotiatedPlace** | Pointer to **string** |  | [optional] 
**BackOrder** | Pointer to **string** | Setup Table: Back_Order | [optional] 

## Methods

### NewAddressesItem

`func NewAddressesItem() *AddressesItem`

NewAddressesItem instantiates a new AddressesItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAddressesItemWithDefaults

`func NewAddressesItemWithDefaults() *AddressesItem`

NewAddressesItemWithDefaults instantiates a new AddressesItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AddressesItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AddressesItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AddressesItem) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *AddressesItem) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCode

`func (o *AddressesItem) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *AddressesItem) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *AddressesItem) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *AddressesItem) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetNote

`func (o *AddressesItem) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *AddressesItem) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *AddressesItem) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *AddressesItem) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetQuoteTo

`func (o *AddressesItem) GetQuoteTo() bool`

GetQuoteTo returns the QuoteTo field if non-nil, zero value otherwise.

### GetQuoteToOk

`func (o *AddressesItem) GetQuoteToOk() (*bool, bool)`

GetQuoteToOk returns a tuple with the QuoteTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuoteTo

`func (o *AddressesItem) SetQuoteTo(v bool)`

SetQuoteTo sets QuoteTo field to given value.

### HasQuoteTo

`func (o *AddressesItem) HasQuoteTo() bool`

HasQuoteTo returns a boolean if a field has been set.

### GetShipTo

`func (o *AddressesItem) GetShipTo() bool`

GetShipTo returns the ShipTo field if non-nil, zero value otherwise.

### GetShipToOk

`func (o *AddressesItem) GetShipToOk() (*bool, bool)`

GetShipToOk returns a tuple with the ShipTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipTo

`func (o *AddressesItem) SetShipTo(v bool)`

SetShipTo sets ShipTo field to given value.

### HasShipTo

`func (o *AddressesItem) HasShipTo() bool`

HasShipTo returns a boolean if a field has been set.

### GetBillTo

`func (o *AddressesItem) GetBillTo() bool`

GetBillTo returns the BillTo field if non-nil, zero value otherwise.

### GetBillToOk

`func (o *AddressesItem) GetBillToOk() (*bool, bool)`

GetBillToOk returns a tuple with the BillTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillTo

`func (o *AddressesItem) SetBillTo(v bool)`

SetBillTo sets BillTo field to given value.

### HasBillTo

`func (o *AddressesItem) HasBillTo() bool`

HasBillTo returns a boolean if a field has been set.

### GetBillToAddressId

`func (o *AddressesItem) GetBillToAddressId() string`

GetBillToAddressId returns the BillToAddressId field if non-nil, zero value otherwise.

### GetBillToAddressIdOk

`func (o *AddressesItem) GetBillToAddressIdOk() (*string, bool)`

GetBillToAddressIdOk returns a tuple with the BillToAddressId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillToAddressId

`func (o *AddressesItem) SetBillToAddressId(v string)`

SetBillToAddressId sets BillToAddressId field to given value.

### HasBillToAddressId

`func (o *AddressesItem) HasBillToAddressId() bool`

HasBillToAddressId returns a boolean if a field has been set.

### GetRemitTo

`func (o *AddressesItem) GetRemitTo() bool`

GetRemitTo returns the RemitTo field if non-nil, zero value otherwise.

### GetRemitToOk

`func (o *AddressesItem) GetRemitToOk() (*bool, bool)`

GetRemitToOk returns a tuple with the RemitTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemitTo

`func (o *AddressesItem) SetRemitTo(v bool)`

SetRemitTo sets RemitTo field to given value.

### HasRemitTo

`func (o *AddressesItem) HasRemitTo() bool`

HasRemitTo returns a boolean if a field has been set.

### GetThirdPartyShipTo

`func (o *AddressesItem) GetThirdPartyShipTo() bool`

GetThirdPartyShipTo returns the ThirdPartyShipTo field if non-nil, zero value otherwise.

### GetThirdPartyShipToOk

`func (o *AddressesItem) GetThirdPartyShipToOk() (*bool, bool)`

GetThirdPartyShipToOk returns a tuple with the ThirdPartyShipTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThirdPartyShipTo

`func (o *AddressesItem) SetThirdPartyShipTo(v bool)`

SetThirdPartyShipTo sets ThirdPartyShipTo field to given value.

### HasThirdPartyShipTo

`func (o *AddressesItem) HasThirdPartyShipTo() bool`

HasThirdPartyShipTo returns a boolean if a field has been set.

### GetThirdPartyShipToAddressId

`func (o *AddressesItem) GetThirdPartyShipToAddressId() string`

GetThirdPartyShipToAddressId returns the ThirdPartyShipToAddressId field if non-nil, zero value otherwise.

### GetThirdPartyShipToAddressIdOk

`func (o *AddressesItem) GetThirdPartyShipToAddressIdOk() (*string, bool)`

GetThirdPartyShipToAddressIdOk returns a tuple with the ThirdPartyShipToAddressId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThirdPartyShipToAddressId

`func (o *AddressesItem) SetThirdPartyShipToAddressId(v string)`

SetThirdPartyShipToAddressId sets ThirdPartyShipToAddressId field to given value.

### HasThirdPartyShipToAddressId

`func (o *AddressesItem) HasThirdPartyShipToAddressId() bool`

HasThirdPartyShipToAddressId returns a boolean if a field has been set.

### GetPool

`func (o *AddressesItem) GetPool() bool`

GetPool returns the Pool field if non-nil, zero value otherwise.

### GetPoolOk

`func (o *AddressesItem) GetPoolOk() (*bool, bool)`

GetPoolOk returns a tuple with the Pool field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPool

`func (o *AddressesItem) SetPool(v bool)`

SetPool sets Pool field to given value.

### HasPool

`func (o *AddressesItem) HasPool() bool`

HasPool returns a boolean if a field has been set.

### GetPoolAddressId

`func (o *AddressesItem) GetPoolAddressId() string`

GetPoolAddressId returns the PoolAddressId field if non-nil, zero value otherwise.

### GetPoolAddressIdOk

`func (o *AddressesItem) GetPoolAddressIdOk() (*string, bool)`

GetPoolAddressIdOk returns a tuple with the PoolAddressId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoolAddressId

`func (o *AddressesItem) SetPoolAddressId(v string)`

SetPoolAddressId sets PoolAddressId field to given value.

### HasPoolAddressId

`func (o *AddressesItem) HasPoolAddressId() bool`

HasPoolAddressId returns a boolean if a field has been set.

### GetOldCustomerNo

`func (o *AddressesItem) GetOldCustomerNo() string`

GetOldCustomerNo returns the OldCustomerNo field if non-nil, zero value otherwise.

### GetOldCustomerNoOk

`func (o *AddressesItem) GetOldCustomerNoOk() (*string, bool)`

GetOldCustomerNoOk returns a tuple with the OldCustomerNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOldCustomerNo

`func (o *AddressesItem) SetOldCustomerNo(v string)`

SetOldCustomerNo sets OldCustomerNo field to given value.

### HasOldCustomerNo

`func (o *AddressesItem) HasOldCustomerNo() bool`

HasOldCustomerNo returns a boolean if a field has been set.

### GetActive

`func (o *AddressesItem) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *AddressesItem) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *AddressesItem) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *AddressesItem) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetPhone

`func (o *AddressesItem) GetPhone() string`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *AddressesItem) GetPhoneOk() (*string, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *AddressesItem) SetPhone(v string)`

SetPhone sets Phone field to given value.

### HasPhone

`func (o *AddressesItem) HasPhone() bool`

HasPhone returns a boolean if a field has been set.

### GetFax

`func (o *AddressesItem) GetFax() string`

GetFax returns the Fax field if non-nil, zero value otherwise.

### GetFaxOk

`func (o *AddressesItem) GetFaxOk() (*string, bool)`

GetFaxOk returns a tuple with the Fax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFax

`func (o *AddressesItem) SetFax(v string)`

SetFax sets Fax field to given value.

### HasFax

`func (o *AddressesItem) HasFax() bool`

HasFax returns a boolean if a field has been set.

### GetEmail

`func (o *AddressesItem) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *AddressesItem) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *AddressesItem) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *AddressesItem) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetName

`func (o *AddressesItem) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *AddressesItem) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *AddressesItem) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *AddressesItem) HasName() bool`

HasName returns a boolean if a field has been set.

### GetAddress

`func (o *AddressesItem) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *AddressesItem) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *AddressesItem) SetAddress(v string)`

SetAddress sets Address field to given value.

### HasAddress

`func (o *AddressesItem) HasAddress() bool`

HasAddress returns a boolean if a field has been set.

### GetCity

`func (o *AddressesItem) GetCity() string`

GetCity returns the City field if non-nil, zero value otherwise.

### GetCityOk

`func (o *AddressesItem) GetCityOk() (*string, bool)`

GetCityOk returns a tuple with the City field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCity

`func (o *AddressesItem) SetCity(v string)`

SetCity sets City field to given value.

### HasCity

`func (o *AddressesItem) HasCity() bool`

HasCity returns a boolean if a field has been set.

### GetState

`func (o *AddressesItem) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *AddressesItem) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *AddressesItem) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *AddressesItem) HasState() bool`

HasState returns a boolean if a field has been set.

### GetZip

`func (o *AddressesItem) GetZip() string`

GetZip returns the Zip field if non-nil, zero value otherwise.

### GetZipOk

`func (o *AddressesItem) GetZipOk() (*string, bool)`

GetZipOk returns a tuple with the Zip field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetZip

`func (o *AddressesItem) SetZip(v string)`

SetZip sets Zip field to given value.

### HasZip

`func (o *AddressesItem) HasZip() bool`

HasZip returns a boolean if a field has been set.

### GetCountry

`func (o *AddressesItem) GetCountry() string`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *AddressesItem) GetCountryOk() (*string, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *AddressesItem) SetCountry(v string)`

SetCountry sets Country field to given value.

### HasCountry

`func (o *AddressesItem) HasCountry() bool`

HasCountry returns a boolean if a field has been set.

### GetRegion

`func (o *AddressesItem) GetRegion() string`

GetRegion returns the Region field if non-nil, zero value otherwise.

### GetRegionOk

`func (o *AddressesItem) GetRegionOk() (*string, bool)`

GetRegionOk returns a tuple with the Region field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegion

`func (o *AddressesItem) SetRegion(v string)`

SetRegion sets Region field to given value.

### HasRegion

`func (o *AddressesItem) HasRegion() bool`

HasRegion returns a boolean if a field has been set.

### GetCounty

`func (o *AddressesItem) GetCounty() string`

GetCounty returns the County field if non-nil, zero value otherwise.

### GetCountyOk

`func (o *AddressesItem) GetCountyOk() (*string, bool)`

GetCountyOk returns a tuple with the County field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCounty

`func (o *AddressesItem) SetCounty(v string)`

SetCounty sets County field to given value.

### HasCounty

`func (o *AddressesItem) HasCounty() bool`

HasCounty returns a boolean if a field has been set.

### GetShippingInstructions

`func (o *AddressesItem) GetShippingInstructions() string`

GetShippingInstructions returns the ShippingInstructions field if non-nil, zero value otherwise.

### GetShippingInstructionsOk

`func (o *AddressesItem) GetShippingInstructionsOk() (*string, bool)`

GetShippingInstructionsOk returns a tuple with the ShippingInstructions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingInstructions

`func (o *AddressesItem) SetShippingInstructions(v string)`

SetShippingInstructions sets ShippingInstructions field to given value.

### HasShippingInstructions

`func (o *AddressesItem) HasShippingInstructions() bool`

HasShippingInstructions returns a boolean if a field has been set.

### GetIgnoreTransitOnWeekends

`func (o *AddressesItem) GetIgnoreTransitOnWeekends() bool`

GetIgnoreTransitOnWeekends returns the IgnoreTransitOnWeekends field if non-nil, zero value otherwise.

### GetIgnoreTransitOnWeekendsOk

`func (o *AddressesItem) GetIgnoreTransitOnWeekendsOk() (*bool, bool)`

GetIgnoreTransitOnWeekendsOk returns a tuple with the IgnoreTransitOnWeekends field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIgnoreTransitOnWeekends

`func (o *AddressesItem) SetIgnoreTransitOnWeekends(v bool)`

SetIgnoreTransitOnWeekends sets IgnoreTransitOnWeekends field to given value.

### HasIgnoreTransitOnWeekends

`func (o *AddressesItem) HasIgnoreTransitOnWeekends() bool`

HasIgnoreTransitOnWeekends returns a boolean if a field has been set.

### GetTransportationLeadTime

`func (o *AddressesItem) GetTransportationLeadTime() int32`

GetTransportationLeadTime returns the TransportationLeadTime field if non-nil, zero value otherwise.

### GetTransportationLeadTimeOk

`func (o *AddressesItem) GetTransportationLeadTimeOk() (*int32, bool)`

GetTransportationLeadTimeOk returns a tuple with the TransportationLeadTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransportationLeadTime

`func (o *AddressesItem) SetTransportationLeadTime(v int32)`

SetTransportationLeadTime sets TransportationLeadTime field to given value.

### HasTransportationLeadTime

`func (o *AddressesItem) HasTransportationLeadTime() bool`

HasTransportationLeadTime returns a boolean if a field has been set.

### GetDefaultCarrierIds

`func (o *AddressesItem) GetDefaultCarrierIds() []string`

GetDefaultCarrierIds returns the DefaultCarrierIds field if non-nil, zero value otherwise.

### GetDefaultCarrierIdsOk

`func (o *AddressesItem) GetDefaultCarrierIdsOk() (*[]string, bool)`

GetDefaultCarrierIdsOk returns a tuple with the DefaultCarrierIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultCarrierIds

`func (o *AddressesItem) SetDefaultCarrierIds(v []string)`

SetDefaultCarrierIds sets DefaultCarrierIds field to given value.

### HasDefaultCarrierIds

`func (o *AddressesItem) HasDefaultCarrierIds() bool`

HasDefaultCarrierIds returns a boolean if a field has been set.

### GetTruckType

`func (o *AddressesItem) GetTruckType() string`

GetTruckType returns the TruckType field if non-nil, zero value otherwise.

### GetTruckTypeOk

`func (o *AddressesItem) GetTruckTypeOk() (*string, bool)`

GetTruckTypeOk returns a tuple with the TruckType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckType

`func (o *AddressesItem) SetTruckType(v string)`

SetTruckType sets TruckType field to given value.

### HasTruckType

`func (o *AddressesItem) HasTruckType() bool`

HasTruckType returns a boolean if a field has been set.

### GetSalesTaxExempt

`func (o *AddressesItem) GetSalesTaxExempt() bool`

GetSalesTaxExempt returns the SalesTaxExempt field if non-nil, zero value otherwise.

### GetSalesTaxExemptOk

`func (o *AddressesItem) GetSalesTaxExemptOk() (*bool, bool)`

GetSalesTaxExemptOk returns a tuple with the SalesTaxExempt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSalesTaxExempt

`func (o *AddressesItem) SetSalesTaxExempt(v bool)`

SetSalesTaxExempt sets SalesTaxExempt field to given value.

### HasSalesTaxExempt

`func (o *AddressesItem) HasSalesTaxExempt() bool`

HasSalesTaxExempt returns a boolean if a field has been set.

### GetSalespersonId

`func (o *AddressesItem) GetSalespersonId() string`

GetSalespersonId returns the SalespersonId field if non-nil, zero value otherwise.

### GetSalespersonIdOk

`func (o *AddressesItem) GetSalespersonIdOk() (*string, bool)`

GetSalespersonIdOk returns a tuple with the SalespersonId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSalespersonId

`func (o *AddressesItem) SetSalespersonId(v string)`

SetSalespersonId sets SalespersonId field to given value.

### HasSalespersonId

`func (o *AddressesItem) HasSalespersonId() bool`

HasSalespersonId returns a boolean if a field has been set.

### GetStatementAddressId

`func (o *AddressesItem) GetStatementAddressId() string`

GetStatementAddressId returns the StatementAddressId field if non-nil, zero value otherwise.

### GetStatementAddressIdOk

`func (o *AddressesItem) GetStatementAddressIdOk() (*string, bool)`

GetStatementAddressIdOk returns a tuple with the StatementAddressId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatementAddressId

`func (o *AddressesItem) SetStatementAddressId(v string)`

SetStatementAddressId sets StatementAddressId field to given value.

### HasStatementAddressId

`func (o *AddressesItem) HasStatementAddressId() bool`

HasStatementAddressId returns a boolean if a field has been set.

### GetFreightTerms

`func (o *AddressesItem) GetFreightTerms() string`

GetFreightTerms returns the FreightTerms field if non-nil, zero value otherwise.

### GetFreightTermsOk

`func (o *AddressesItem) GetFreightTermsOk() (*string, bool)`

GetFreightTermsOk returns a tuple with the FreightTerms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFreightTerms

`func (o *AddressesItem) SetFreightTerms(v string)`

SetFreightTerms sets FreightTerms field to given value.

### HasFreightTerms

`func (o *AddressesItem) HasFreightTerms() bool`

HasFreightTerms returns a boolean if a field has been set.

### GetInsideSalespersonId

`func (o *AddressesItem) GetInsideSalespersonId() string`

GetInsideSalespersonId returns the InsideSalespersonId field if non-nil, zero value otherwise.

### GetInsideSalespersonIdOk

`func (o *AddressesItem) GetInsideSalespersonIdOk() (*string, bool)`

GetInsideSalespersonIdOk returns a tuple with the InsideSalespersonId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInsideSalespersonId

`func (o *AddressesItem) SetInsideSalespersonId(v string)`

SetInsideSalespersonId sets InsideSalespersonId field to given value.

### HasInsideSalespersonId

`func (o *AddressesItem) HasInsideSalespersonId() bool`

HasInsideSalespersonId returns a boolean if a field has been set.

### GetDefaultShipFrom

`func (o *AddressesItem) GetDefaultShipFrom() string`

GetDefaultShipFrom returns the DefaultShipFrom field if non-nil, zero value otherwise.

### GetDefaultShipFromOk

`func (o *AddressesItem) GetDefaultShipFromOk() (*string, bool)`

GetDefaultShipFromOk returns a tuple with the DefaultShipFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultShipFrom

`func (o *AddressesItem) SetDefaultShipFrom(v string)`

SetDefaultShipFrom sets DefaultShipFrom field to given value.

### HasDefaultShipFrom

`func (o *AddressesItem) HasDefaultShipFrom() bool`

HasDefaultShipFrom returns a boolean if a field has been set.

### GetFreightBillTo

`func (o *AddressesItem) GetFreightBillTo() bool`

GetFreightBillTo returns the FreightBillTo field if non-nil, zero value otherwise.

### GetFreightBillToOk

`func (o *AddressesItem) GetFreightBillToOk() (*bool, bool)`

GetFreightBillToOk returns a tuple with the FreightBillTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFreightBillTo

`func (o *AddressesItem) SetFreightBillTo(v bool)`

SetFreightBillTo sets FreightBillTo field to given value.

### HasFreightBillTo

`func (o *AddressesItem) HasFreightBillTo() bool`

HasFreightBillTo returns a boolean if a field has been set.

### GetFreightBillToAddressId

`func (o *AddressesItem) GetFreightBillToAddressId() string`

GetFreightBillToAddressId returns the FreightBillToAddressId field if non-nil, zero value otherwise.

### GetFreightBillToAddressIdOk

`func (o *AddressesItem) GetFreightBillToAddressIdOk() (*string, bool)`

GetFreightBillToAddressIdOk returns a tuple with the FreightBillToAddressId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFreightBillToAddressId

`func (o *AddressesItem) SetFreightBillToAddressId(v string)`

SetFreightBillToAddressId sets FreightBillToAddressId field to given value.

### HasFreightBillToAddressId

`func (o *AddressesItem) HasFreightBillToAddressId() bool`

HasFreightBillToAddressId returns a boolean if a field has been set.

### GetCatalog

`func (o *AddressesItem) GetCatalog() string`

GetCatalog returns the Catalog field if non-nil, zero value otherwise.

### GetCatalogOk

`func (o *AddressesItem) GetCatalogOk() (*string, bool)`

GetCatalogOk returns a tuple with the Catalog field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCatalog

`func (o *AddressesItem) SetCatalog(v string)`

SetCatalog sets Catalog field to given value.

### HasCatalog

`func (o *AddressesItem) HasCatalog() bool`

HasCatalog returns a boolean if a field has been set.

### GetSoldTo

`func (o *AddressesItem) GetSoldTo() bool`

GetSoldTo returns the SoldTo field if non-nil, zero value otherwise.

### GetSoldToOk

`func (o *AddressesItem) GetSoldToOk() (*bool, bool)`

GetSoldToOk returns a tuple with the SoldTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSoldTo

`func (o *AddressesItem) SetSoldTo(v bool)`

SetSoldTo sets SoldTo field to given value.

### HasSoldTo

`func (o *AddressesItem) HasSoldTo() bool`

HasSoldTo returns a boolean if a field has been set.

### GetDunsNo

`func (o *AddressesItem) GetDunsNo() string`

GetDunsNo returns the DunsNo field if non-nil, zero value otherwise.

### GetDunsNoOk

`func (o *AddressesItem) GetDunsNoOk() (*string, bool)`

GetDunsNoOk returns a tuple with the DunsNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDunsNo

`func (o *AddressesItem) SetDunsNo(v string)`

SetDunsNo sets DunsNo field to given value.

### HasDunsNo

`func (o *AddressesItem) HasDunsNo() bool`

HasDunsNo returns a boolean if a field has been set.

### GetCommercialInvoiceVatNo

`func (o *AddressesItem) GetCommercialInvoiceVatNo() string`

GetCommercialInvoiceVatNo returns the CommercialInvoiceVatNo field if non-nil, zero value otherwise.

### GetCommercialInvoiceVatNoOk

`func (o *AddressesItem) GetCommercialInvoiceVatNoOk() (*string, bool)`

GetCommercialInvoiceVatNoOk returns a tuple with the CommercialInvoiceVatNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCommercialInvoiceVatNo

`func (o *AddressesItem) SetCommercialInvoiceVatNo(v string)`

SetCommercialInvoiceVatNo sets CommercialInvoiceVatNo field to given value.

### HasCommercialInvoiceVatNo

`func (o *AddressesItem) HasCommercialInvoiceVatNo() bool`

HasCommercialInvoiceVatNo returns a boolean if a field has been set.

### GetTerms

`func (o *AddressesItem) GetTerms() string`

GetTerms returns the Terms field if non-nil, zero value otherwise.

### GetTermsOk

`func (o *AddressesItem) GetTermsOk() (*string, bool)`

GetTermsOk returns a tuple with the Terms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTerms

`func (o *AddressesItem) SetTerms(v string)`

SetTerms sets Terms field to given value.

### HasTerms

`func (o *AddressesItem) HasTerms() bool`

HasTerms returns a boolean if a field has been set.

### GetTemplate

`func (o *AddressesItem) GetTemplate() bool`

GetTemplate returns the Template field if non-nil, zero value otherwise.

### GetTemplateOk

`func (o *AddressesItem) GetTemplateOk() (*bool, bool)`

GetTemplateOk returns a tuple with the Template field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemplate

`func (o *AddressesItem) SetTemplate(v bool)`

SetTemplate sets Template field to given value.

### HasTemplate

`func (o *AddressesItem) HasTemplate() bool`

HasTemplate returns a boolean if a field has been set.

### GetIncoTerms

`func (o *AddressesItem) GetIncoTerms() string`

GetIncoTerms returns the IncoTerms field if non-nil, zero value otherwise.

### GetIncoTermsOk

`func (o *AddressesItem) GetIncoTermsOk() (*string, bool)`

GetIncoTermsOk returns a tuple with the IncoTerms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncoTerms

`func (o *AddressesItem) SetIncoTerms(v string)`

SetIncoTerms sets IncoTerms field to given value.

### HasIncoTerms

`func (o *AddressesItem) HasIncoTerms() bool`

HasIncoTerms returns a boolean if a field has been set.

### GetNegotiatedPlace

`func (o *AddressesItem) GetNegotiatedPlace() string`

GetNegotiatedPlace returns the NegotiatedPlace field if non-nil, zero value otherwise.

### GetNegotiatedPlaceOk

`func (o *AddressesItem) GetNegotiatedPlaceOk() (*string, bool)`

GetNegotiatedPlaceOk returns a tuple with the NegotiatedPlace field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNegotiatedPlace

`func (o *AddressesItem) SetNegotiatedPlace(v string)`

SetNegotiatedPlace sets NegotiatedPlace field to given value.

### HasNegotiatedPlace

`func (o *AddressesItem) HasNegotiatedPlace() bool`

HasNegotiatedPlace returns a boolean if a field has been set.

### GetBackOrder

`func (o *AddressesItem) GetBackOrder() string`

GetBackOrder returns the BackOrder field if non-nil, zero value otherwise.

### GetBackOrderOk

`func (o *AddressesItem) GetBackOrderOk() (*string, bool)`

GetBackOrderOk returns a tuple with the BackOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBackOrder

`func (o *AddressesItem) SetBackOrder(v string)`

SetBackOrder sets BackOrder field to given value.

### HasBackOrder

`func (o *AddressesItem) HasBackOrder() bool`

HasBackOrder returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


