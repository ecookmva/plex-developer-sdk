# CustomersApiCreateCustomerAddressRequest

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

### NewCustomersApiCreateCustomerAddressRequest

`func NewCustomersApiCreateCustomerAddressRequest() *CustomersApiCreateCustomerAddressRequest`

NewCustomersApiCreateCustomerAddressRequest instantiates a new CustomersApiCreateCustomerAddressRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomersApiCreateCustomerAddressRequestWithDefaults

`func NewCustomersApiCreateCustomerAddressRequestWithDefaults() *CustomersApiCreateCustomerAddressRequest`

NewCustomersApiCreateCustomerAddressRequestWithDefaults instantiates a new CustomersApiCreateCustomerAddressRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CustomersApiCreateCustomerAddressRequest) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CustomersApiCreateCustomerAddressRequest) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CustomersApiCreateCustomerAddressRequest) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *CustomersApiCreateCustomerAddressRequest) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCode

`func (o *CustomersApiCreateCustomerAddressRequest) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *CustomersApiCreateCustomerAddressRequest) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *CustomersApiCreateCustomerAddressRequest) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *CustomersApiCreateCustomerAddressRequest) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetNote

`func (o *CustomersApiCreateCustomerAddressRequest) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *CustomersApiCreateCustomerAddressRequest) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *CustomersApiCreateCustomerAddressRequest) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *CustomersApiCreateCustomerAddressRequest) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetQuoteTo

`func (o *CustomersApiCreateCustomerAddressRequest) GetQuoteTo() bool`

GetQuoteTo returns the QuoteTo field if non-nil, zero value otherwise.

### GetQuoteToOk

`func (o *CustomersApiCreateCustomerAddressRequest) GetQuoteToOk() (*bool, bool)`

GetQuoteToOk returns a tuple with the QuoteTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuoteTo

`func (o *CustomersApiCreateCustomerAddressRequest) SetQuoteTo(v bool)`

SetQuoteTo sets QuoteTo field to given value.

### HasQuoteTo

`func (o *CustomersApiCreateCustomerAddressRequest) HasQuoteTo() bool`

HasQuoteTo returns a boolean if a field has been set.

### GetShipTo

`func (o *CustomersApiCreateCustomerAddressRequest) GetShipTo() bool`

GetShipTo returns the ShipTo field if non-nil, zero value otherwise.

### GetShipToOk

`func (o *CustomersApiCreateCustomerAddressRequest) GetShipToOk() (*bool, bool)`

GetShipToOk returns a tuple with the ShipTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipTo

`func (o *CustomersApiCreateCustomerAddressRequest) SetShipTo(v bool)`

SetShipTo sets ShipTo field to given value.

### HasShipTo

`func (o *CustomersApiCreateCustomerAddressRequest) HasShipTo() bool`

HasShipTo returns a boolean if a field has been set.

### GetBillTo

`func (o *CustomersApiCreateCustomerAddressRequest) GetBillTo() bool`

GetBillTo returns the BillTo field if non-nil, zero value otherwise.

### GetBillToOk

`func (o *CustomersApiCreateCustomerAddressRequest) GetBillToOk() (*bool, bool)`

GetBillToOk returns a tuple with the BillTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillTo

`func (o *CustomersApiCreateCustomerAddressRequest) SetBillTo(v bool)`

SetBillTo sets BillTo field to given value.

### HasBillTo

`func (o *CustomersApiCreateCustomerAddressRequest) HasBillTo() bool`

HasBillTo returns a boolean if a field has been set.

### GetBillToAddressId

`func (o *CustomersApiCreateCustomerAddressRequest) GetBillToAddressId() string`

GetBillToAddressId returns the BillToAddressId field if non-nil, zero value otherwise.

### GetBillToAddressIdOk

`func (o *CustomersApiCreateCustomerAddressRequest) GetBillToAddressIdOk() (*string, bool)`

GetBillToAddressIdOk returns a tuple with the BillToAddressId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillToAddressId

`func (o *CustomersApiCreateCustomerAddressRequest) SetBillToAddressId(v string)`

SetBillToAddressId sets BillToAddressId field to given value.

### HasBillToAddressId

`func (o *CustomersApiCreateCustomerAddressRequest) HasBillToAddressId() bool`

HasBillToAddressId returns a boolean if a field has been set.

### GetRemitTo

`func (o *CustomersApiCreateCustomerAddressRequest) GetRemitTo() bool`

GetRemitTo returns the RemitTo field if non-nil, zero value otherwise.

### GetRemitToOk

`func (o *CustomersApiCreateCustomerAddressRequest) GetRemitToOk() (*bool, bool)`

GetRemitToOk returns a tuple with the RemitTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemitTo

`func (o *CustomersApiCreateCustomerAddressRequest) SetRemitTo(v bool)`

SetRemitTo sets RemitTo field to given value.

### HasRemitTo

`func (o *CustomersApiCreateCustomerAddressRequest) HasRemitTo() bool`

HasRemitTo returns a boolean if a field has been set.

### GetThirdPartyShipTo

`func (o *CustomersApiCreateCustomerAddressRequest) GetThirdPartyShipTo() bool`

GetThirdPartyShipTo returns the ThirdPartyShipTo field if non-nil, zero value otherwise.

### GetThirdPartyShipToOk

`func (o *CustomersApiCreateCustomerAddressRequest) GetThirdPartyShipToOk() (*bool, bool)`

GetThirdPartyShipToOk returns a tuple with the ThirdPartyShipTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThirdPartyShipTo

`func (o *CustomersApiCreateCustomerAddressRequest) SetThirdPartyShipTo(v bool)`

SetThirdPartyShipTo sets ThirdPartyShipTo field to given value.

### HasThirdPartyShipTo

`func (o *CustomersApiCreateCustomerAddressRequest) HasThirdPartyShipTo() bool`

HasThirdPartyShipTo returns a boolean if a field has been set.

### GetThirdPartyShipToAddressId

`func (o *CustomersApiCreateCustomerAddressRequest) GetThirdPartyShipToAddressId() string`

GetThirdPartyShipToAddressId returns the ThirdPartyShipToAddressId field if non-nil, zero value otherwise.

### GetThirdPartyShipToAddressIdOk

`func (o *CustomersApiCreateCustomerAddressRequest) GetThirdPartyShipToAddressIdOk() (*string, bool)`

GetThirdPartyShipToAddressIdOk returns a tuple with the ThirdPartyShipToAddressId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThirdPartyShipToAddressId

`func (o *CustomersApiCreateCustomerAddressRequest) SetThirdPartyShipToAddressId(v string)`

SetThirdPartyShipToAddressId sets ThirdPartyShipToAddressId field to given value.

### HasThirdPartyShipToAddressId

`func (o *CustomersApiCreateCustomerAddressRequest) HasThirdPartyShipToAddressId() bool`

HasThirdPartyShipToAddressId returns a boolean if a field has been set.

### GetPool

`func (o *CustomersApiCreateCustomerAddressRequest) GetPool() bool`

GetPool returns the Pool field if non-nil, zero value otherwise.

### GetPoolOk

`func (o *CustomersApiCreateCustomerAddressRequest) GetPoolOk() (*bool, bool)`

GetPoolOk returns a tuple with the Pool field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPool

`func (o *CustomersApiCreateCustomerAddressRequest) SetPool(v bool)`

SetPool sets Pool field to given value.

### HasPool

`func (o *CustomersApiCreateCustomerAddressRequest) HasPool() bool`

HasPool returns a boolean if a field has been set.

### GetPoolAddressId

`func (o *CustomersApiCreateCustomerAddressRequest) GetPoolAddressId() string`

GetPoolAddressId returns the PoolAddressId field if non-nil, zero value otherwise.

### GetPoolAddressIdOk

`func (o *CustomersApiCreateCustomerAddressRequest) GetPoolAddressIdOk() (*string, bool)`

GetPoolAddressIdOk returns a tuple with the PoolAddressId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoolAddressId

`func (o *CustomersApiCreateCustomerAddressRequest) SetPoolAddressId(v string)`

SetPoolAddressId sets PoolAddressId field to given value.

### HasPoolAddressId

`func (o *CustomersApiCreateCustomerAddressRequest) HasPoolAddressId() bool`

HasPoolAddressId returns a boolean if a field has been set.

### GetOldCustomerNo

`func (o *CustomersApiCreateCustomerAddressRequest) GetOldCustomerNo() string`

GetOldCustomerNo returns the OldCustomerNo field if non-nil, zero value otherwise.

### GetOldCustomerNoOk

`func (o *CustomersApiCreateCustomerAddressRequest) GetOldCustomerNoOk() (*string, bool)`

GetOldCustomerNoOk returns a tuple with the OldCustomerNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOldCustomerNo

`func (o *CustomersApiCreateCustomerAddressRequest) SetOldCustomerNo(v string)`

SetOldCustomerNo sets OldCustomerNo field to given value.

### HasOldCustomerNo

`func (o *CustomersApiCreateCustomerAddressRequest) HasOldCustomerNo() bool`

HasOldCustomerNo returns a boolean if a field has been set.

### GetActive

`func (o *CustomersApiCreateCustomerAddressRequest) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *CustomersApiCreateCustomerAddressRequest) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *CustomersApiCreateCustomerAddressRequest) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *CustomersApiCreateCustomerAddressRequest) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetPhone

`func (o *CustomersApiCreateCustomerAddressRequest) GetPhone() string`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *CustomersApiCreateCustomerAddressRequest) GetPhoneOk() (*string, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *CustomersApiCreateCustomerAddressRequest) SetPhone(v string)`

SetPhone sets Phone field to given value.

### HasPhone

`func (o *CustomersApiCreateCustomerAddressRequest) HasPhone() bool`

HasPhone returns a boolean if a field has been set.

### GetFax

`func (o *CustomersApiCreateCustomerAddressRequest) GetFax() string`

GetFax returns the Fax field if non-nil, zero value otherwise.

### GetFaxOk

`func (o *CustomersApiCreateCustomerAddressRequest) GetFaxOk() (*string, bool)`

GetFaxOk returns a tuple with the Fax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFax

`func (o *CustomersApiCreateCustomerAddressRequest) SetFax(v string)`

SetFax sets Fax field to given value.

### HasFax

`func (o *CustomersApiCreateCustomerAddressRequest) HasFax() bool`

HasFax returns a boolean if a field has been set.

### GetEmail

`func (o *CustomersApiCreateCustomerAddressRequest) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *CustomersApiCreateCustomerAddressRequest) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *CustomersApiCreateCustomerAddressRequest) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *CustomersApiCreateCustomerAddressRequest) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetName

`func (o *CustomersApiCreateCustomerAddressRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CustomersApiCreateCustomerAddressRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CustomersApiCreateCustomerAddressRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *CustomersApiCreateCustomerAddressRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### GetAddress

`func (o *CustomersApiCreateCustomerAddressRequest) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *CustomersApiCreateCustomerAddressRequest) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *CustomersApiCreateCustomerAddressRequest) SetAddress(v string)`

SetAddress sets Address field to given value.

### HasAddress

`func (o *CustomersApiCreateCustomerAddressRequest) HasAddress() bool`

HasAddress returns a boolean if a field has been set.

### GetCity

`func (o *CustomersApiCreateCustomerAddressRequest) GetCity() string`

GetCity returns the City field if non-nil, zero value otherwise.

### GetCityOk

`func (o *CustomersApiCreateCustomerAddressRequest) GetCityOk() (*string, bool)`

GetCityOk returns a tuple with the City field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCity

`func (o *CustomersApiCreateCustomerAddressRequest) SetCity(v string)`

SetCity sets City field to given value.

### HasCity

`func (o *CustomersApiCreateCustomerAddressRequest) HasCity() bool`

HasCity returns a boolean if a field has been set.

### GetState

`func (o *CustomersApiCreateCustomerAddressRequest) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *CustomersApiCreateCustomerAddressRequest) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *CustomersApiCreateCustomerAddressRequest) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *CustomersApiCreateCustomerAddressRequest) HasState() bool`

HasState returns a boolean if a field has been set.

### GetZip

`func (o *CustomersApiCreateCustomerAddressRequest) GetZip() string`

GetZip returns the Zip field if non-nil, zero value otherwise.

### GetZipOk

`func (o *CustomersApiCreateCustomerAddressRequest) GetZipOk() (*string, bool)`

GetZipOk returns a tuple with the Zip field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetZip

`func (o *CustomersApiCreateCustomerAddressRequest) SetZip(v string)`

SetZip sets Zip field to given value.

### HasZip

`func (o *CustomersApiCreateCustomerAddressRequest) HasZip() bool`

HasZip returns a boolean if a field has been set.

### GetCountry

`func (o *CustomersApiCreateCustomerAddressRequest) GetCountry() string`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *CustomersApiCreateCustomerAddressRequest) GetCountryOk() (*string, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *CustomersApiCreateCustomerAddressRequest) SetCountry(v string)`

SetCountry sets Country field to given value.

### HasCountry

`func (o *CustomersApiCreateCustomerAddressRequest) HasCountry() bool`

HasCountry returns a boolean if a field has been set.

### GetRegion

`func (o *CustomersApiCreateCustomerAddressRequest) GetRegion() string`

GetRegion returns the Region field if non-nil, zero value otherwise.

### GetRegionOk

`func (o *CustomersApiCreateCustomerAddressRequest) GetRegionOk() (*string, bool)`

GetRegionOk returns a tuple with the Region field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegion

`func (o *CustomersApiCreateCustomerAddressRequest) SetRegion(v string)`

SetRegion sets Region field to given value.

### HasRegion

`func (o *CustomersApiCreateCustomerAddressRequest) HasRegion() bool`

HasRegion returns a boolean if a field has been set.

### GetCounty

`func (o *CustomersApiCreateCustomerAddressRequest) GetCounty() string`

GetCounty returns the County field if non-nil, zero value otherwise.

### GetCountyOk

`func (o *CustomersApiCreateCustomerAddressRequest) GetCountyOk() (*string, bool)`

GetCountyOk returns a tuple with the County field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCounty

`func (o *CustomersApiCreateCustomerAddressRequest) SetCounty(v string)`

SetCounty sets County field to given value.

### HasCounty

`func (o *CustomersApiCreateCustomerAddressRequest) HasCounty() bool`

HasCounty returns a boolean if a field has been set.

### GetShippingInstructions

`func (o *CustomersApiCreateCustomerAddressRequest) GetShippingInstructions() string`

GetShippingInstructions returns the ShippingInstructions field if non-nil, zero value otherwise.

### GetShippingInstructionsOk

`func (o *CustomersApiCreateCustomerAddressRequest) GetShippingInstructionsOk() (*string, bool)`

GetShippingInstructionsOk returns a tuple with the ShippingInstructions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingInstructions

`func (o *CustomersApiCreateCustomerAddressRequest) SetShippingInstructions(v string)`

SetShippingInstructions sets ShippingInstructions field to given value.

### HasShippingInstructions

`func (o *CustomersApiCreateCustomerAddressRequest) HasShippingInstructions() bool`

HasShippingInstructions returns a boolean if a field has been set.

### GetIgnoreTransitOnWeekends

`func (o *CustomersApiCreateCustomerAddressRequest) GetIgnoreTransitOnWeekends() bool`

GetIgnoreTransitOnWeekends returns the IgnoreTransitOnWeekends field if non-nil, zero value otherwise.

### GetIgnoreTransitOnWeekendsOk

`func (o *CustomersApiCreateCustomerAddressRequest) GetIgnoreTransitOnWeekendsOk() (*bool, bool)`

GetIgnoreTransitOnWeekendsOk returns a tuple with the IgnoreTransitOnWeekends field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIgnoreTransitOnWeekends

`func (o *CustomersApiCreateCustomerAddressRequest) SetIgnoreTransitOnWeekends(v bool)`

SetIgnoreTransitOnWeekends sets IgnoreTransitOnWeekends field to given value.

### HasIgnoreTransitOnWeekends

`func (o *CustomersApiCreateCustomerAddressRequest) HasIgnoreTransitOnWeekends() bool`

HasIgnoreTransitOnWeekends returns a boolean if a field has been set.

### GetTransportationLeadTime

`func (o *CustomersApiCreateCustomerAddressRequest) GetTransportationLeadTime() int32`

GetTransportationLeadTime returns the TransportationLeadTime field if non-nil, zero value otherwise.

### GetTransportationLeadTimeOk

`func (o *CustomersApiCreateCustomerAddressRequest) GetTransportationLeadTimeOk() (*int32, bool)`

GetTransportationLeadTimeOk returns a tuple with the TransportationLeadTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransportationLeadTime

`func (o *CustomersApiCreateCustomerAddressRequest) SetTransportationLeadTime(v int32)`

SetTransportationLeadTime sets TransportationLeadTime field to given value.

### HasTransportationLeadTime

`func (o *CustomersApiCreateCustomerAddressRequest) HasTransportationLeadTime() bool`

HasTransportationLeadTime returns a boolean if a field has been set.

### GetDefaultCarrierIds

`func (o *CustomersApiCreateCustomerAddressRequest) GetDefaultCarrierIds() []string`

GetDefaultCarrierIds returns the DefaultCarrierIds field if non-nil, zero value otherwise.

### GetDefaultCarrierIdsOk

`func (o *CustomersApiCreateCustomerAddressRequest) GetDefaultCarrierIdsOk() (*[]string, bool)`

GetDefaultCarrierIdsOk returns a tuple with the DefaultCarrierIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultCarrierIds

`func (o *CustomersApiCreateCustomerAddressRequest) SetDefaultCarrierIds(v []string)`

SetDefaultCarrierIds sets DefaultCarrierIds field to given value.

### HasDefaultCarrierIds

`func (o *CustomersApiCreateCustomerAddressRequest) HasDefaultCarrierIds() bool`

HasDefaultCarrierIds returns a boolean if a field has been set.

### GetTruckType

`func (o *CustomersApiCreateCustomerAddressRequest) GetTruckType() string`

GetTruckType returns the TruckType field if non-nil, zero value otherwise.

### GetTruckTypeOk

`func (o *CustomersApiCreateCustomerAddressRequest) GetTruckTypeOk() (*string, bool)`

GetTruckTypeOk returns a tuple with the TruckType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckType

`func (o *CustomersApiCreateCustomerAddressRequest) SetTruckType(v string)`

SetTruckType sets TruckType field to given value.

### HasTruckType

`func (o *CustomersApiCreateCustomerAddressRequest) HasTruckType() bool`

HasTruckType returns a boolean if a field has been set.

### GetSalesTaxExempt

`func (o *CustomersApiCreateCustomerAddressRequest) GetSalesTaxExempt() bool`

GetSalesTaxExempt returns the SalesTaxExempt field if non-nil, zero value otherwise.

### GetSalesTaxExemptOk

`func (o *CustomersApiCreateCustomerAddressRequest) GetSalesTaxExemptOk() (*bool, bool)`

GetSalesTaxExemptOk returns a tuple with the SalesTaxExempt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSalesTaxExempt

`func (o *CustomersApiCreateCustomerAddressRequest) SetSalesTaxExempt(v bool)`

SetSalesTaxExempt sets SalesTaxExempt field to given value.

### HasSalesTaxExempt

`func (o *CustomersApiCreateCustomerAddressRequest) HasSalesTaxExempt() bool`

HasSalesTaxExempt returns a boolean if a field has been set.

### GetSalespersonId

`func (o *CustomersApiCreateCustomerAddressRequest) GetSalespersonId() string`

GetSalespersonId returns the SalespersonId field if non-nil, zero value otherwise.

### GetSalespersonIdOk

`func (o *CustomersApiCreateCustomerAddressRequest) GetSalespersonIdOk() (*string, bool)`

GetSalespersonIdOk returns a tuple with the SalespersonId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSalespersonId

`func (o *CustomersApiCreateCustomerAddressRequest) SetSalespersonId(v string)`

SetSalespersonId sets SalespersonId field to given value.

### HasSalespersonId

`func (o *CustomersApiCreateCustomerAddressRequest) HasSalespersonId() bool`

HasSalespersonId returns a boolean if a field has been set.

### GetStatementAddressId

`func (o *CustomersApiCreateCustomerAddressRequest) GetStatementAddressId() string`

GetStatementAddressId returns the StatementAddressId field if non-nil, zero value otherwise.

### GetStatementAddressIdOk

`func (o *CustomersApiCreateCustomerAddressRequest) GetStatementAddressIdOk() (*string, bool)`

GetStatementAddressIdOk returns a tuple with the StatementAddressId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatementAddressId

`func (o *CustomersApiCreateCustomerAddressRequest) SetStatementAddressId(v string)`

SetStatementAddressId sets StatementAddressId field to given value.

### HasStatementAddressId

`func (o *CustomersApiCreateCustomerAddressRequest) HasStatementAddressId() bool`

HasStatementAddressId returns a boolean if a field has been set.

### GetFreightTerms

`func (o *CustomersApiCreateCustomerAddressRequest) GetFreightTerms() string`

GetFreightTerms returns the FreightTerms field if non-nil, zero value otherwise.

### GetFreightTermsOk

`func (o *CustomersApiCreateCustomerAddressRequest) GetFreightTermsOk() (*string, bool)`

GetFreightTermsOk returns a tuple with the FreightTerms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFreightTerms

`func (o *CustomersApiCreateCustomerAddressRequest) SetFreightTerms(v string)`

SetFreightTerms sets FreightTerms field to given value.

### HasFreightTerms

`func (o *CustomersApiCreateCustomerAddressRequest) HasFreightTerms() bool`

HasFreightTerms returns a boolean if a field has been set.

### GetInsideSalespersonId

`func (o *CustomersApiCreateCustomerAddressRequest) GetInsideSalespersonId() string`

GetInsideSalespersonId returns the InsideSalespersonId field if non-nil, zero value otherwise.

### GetInsideSalespersonIdOk

`func (o *CustomersApiCreateCustomerAddressRequest) GetInsideSalespersonIdOk() (*string, bool)`

GetInsideSalespersonIdOk returns a tuple with the InsideSalespersonId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInsideSalespersonId

`func (o *CustomersApiCreateCustomerAddressRequest) SetInsideSalespersonId(v string)`

SetInsideSalespersonId sets InsideSalespersonId field to given value.

### HasInsideSalespersonId

`func (o *CustomersApiCreateCustomerAddressRequest) HasInsideSalespersonId() bool`

HasInsideSalespersonId returns a boolean if a field has been set.

### GetDefaultShipFrom

`func (o *CustomersApiCreateCustomerAddressRequest) GetDefaultShipFrom() string`

GetDefaultShipFrom returns the DefaultShipFrom field if non-nil, zero value otherwise.

### GetDefaultShipFromOk

`func (o *CustomersApiCreateCustomerAddressRequest) GetDefaultShipFromOk() (*string, bool)`

GetDefaultShipFromOk returns a tuple with the DefaultShipFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultShipFrom

`func (o *CustomersApiCreateCustomerAddressRequest) SetDefaultShipFrom(v string)`

SetDefaultShipFrom sets DefaultShipFrom field to given value.

### HasDefaultShipFrom

`func (o *CustomersApiCreateCustomerAddressRequest) HasDefaultShipFrom() bool`

HasDefaultShipFrom returns a boolean if a field has been set.

### GetFreightBillTo

`func (o *CustomersApiCreateCustomerAddressRequest) GetFreightBillTo() bool`

GetFreightBillTo returns the FreightBillTo field if non-nil, zero value otherwise.

### GetFreightBillToOk

`func (o *CustomersApiCreateCustomerAddressRequest) GetFreightBillToOk() (*bool, bool)`

GetFreightBillToOk returns a tuple with the FreightBillTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFreightBillTo

`func (o *CustomersApiCreateCustomerAddressRequest) SetFreightBillTo(v bool)`

SetFreightBillTo sets FreightBillTo field to given value.

### HasFreightBillTo

`func (o *CustomersApiCreateCustomerAddressRequest) HasFreightBillTo() bool`

HasFreightBillTo returns a boolean if a field has been set.

### GetFreightBillToAddressId

`func (o *CustomersApiCreateCustomerAddressRequest) GetFreightBillToAddressId() string`

GetFreightBillToAddressId returns the FreightBillToAddressId field if non-nil, zero value otherwise.

### GetFreightBillToAddressIdOk

`func (o *CustomersApiCreateCustomerAddressRequest) GetFreightBillToAddressIdOk() (*string, bool)`

GetFreightBillToAddressIdOk returns a tuple with the FreightBillToAddressId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFreightBillToAddressId

`func (o *CustomersApiCreateCustomerAddressRequest) SetFreightBillToAddressId(v string)`

SetFreightBillToAddressId sets FreightBillToAddressId field to given value.

### HasFreightBillToAddressId

`func (o *CustomersApiCreateCustomerAddressRequest) HasFreightBillToAddressId() bool`

HasFreightBillToAddressId returns a boolean if a field has been set.

### GetCatalog

`func (o *CustomersApiCreateCustomerAddressRequest) GetCatalog() string`

GetCatalog returns the Catalog field if non-nil, zero value otherwise.

### GetCatalogOk

`func (o *CustomersApiCreateCustomerAddressRequest) GetCatalogOk() (*string, bool)`

GetCatalogOk returns a tuple with the Catalog field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCatalog

`func (o *CustomersApiCreateCustomerAddressRequest) SetCatalog(v string)`

SetCatalog sets Catalog field to given value.

### HasCatalog

`func (o *CustomersApiCreateCustomerAddressRequest) HasCatalog() bool`

HasCatalog returns a boolean if a field has been set.

### GetSoldTo

`func (o *CustomersApiCreateCustomerAddressRequest) GetSoldTo() bool`

GetSoldTo returns the SoldTo field if non-nil, zero value otherwise.

### GetSoldToOk

`func (o *CustomersApiCreateCustomerAddressRequest) GetSoldToOk() (*bool, bool)`

GetSoldToOk returns a tuple with the SoldTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSoldTo

`func (o *CustomersApiCreateCustomerAddressRequest) SetSoldTo(v bool)`

SetSoldTo sets SoldTo field to given value.

### HasSoldTo

`func (o *CustomersApiCreateCustomerAddressRequest) HasSoldTo() bool`

HasSoldTo returns a boolean if a field has been set.

### GetDunsNo

`func (o *CustomersApiCreateCustomerAddressRequest) GetDunsNo() string`

GetDunsNo returns the DunsNo field if non-nil, zero value otherwise.

### GetDunsNoOk

`func (o *CustomersApiCreateCustomerAddressRequest) GetDunsNoOk() (*string, bool)`

GetDunsNoOk returns a tuple with the DunsNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDunsNo

`func (o *CustomersApiCreateCustomerAddressRequest) SetDunsNo(v string)`

SetDunsNo sets DunsNo field to given value.

### HasDunsNo

`func (o *CustomersApiCreateCustomerAddressRequest) HasDunsNo() bool`

HasDunsNo returns a boolean if a field has been set.

### GetCommercialInvoiceVatNo

`func (o *CustomersApiCreateCustomerAddressRequest) GetCommercialInvoiceVatNo() string`

GetCommercialInvoiceVatNo returns the CommercialInvoiceVatNo field if non-nil, zero value otherwise.

### GetCommercialInvoiceVatNoOk

`func (o *CustomersApiCreateCustomerAddressRequest) GetCommercialInvoiceVatNoOk() (*string, bool)`

GetCommercialInvoiceVatNoOk returns a tuple with the CommercialInvoiceVatNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCommercialInvoiceVatNo

`func (o *CustomersApiCreateCustomerAddressRequest) SetCommercialInvoiceVatNo(v string)`

SetCommercialInvoiceVatNo sets CommercialInvoiceVatNo field to given value.

### HasCommercialInvoiceVatNo

`func (o *CustomersApiCreateCustomerAddressRequest) HasCommercialInvoiceVatNo() bool`

HasCommercialInvoiceVatNo returns a boolean if a field has been set.

### GetTerms

`func (o *CustomersApiCreateCustomerAddressRequest) GetTerms() string`

GetTerms returns the Terms field if non-nil, zero value otherwise.

### GetTermsOk

`func (o *CustomersApiCreateCustomerAddressRequest) GetTermsOk() (*string, bool)`

GetTermsOk returns a tuple with the Terms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTerms

`func (o *CustomersApiCreateCustomerAddressRequest) SetTerms(v string)`

SetTerms sets Terms field to given value.

### HasTerms

`func (o *CustomersApiCreateCustomerAddressRequest) HasTerms() bool`

HasTerms returns a boolean if a field has been set.

### GetTemplate

`func (o *CustomersApiCreateCustomerAddressRequest) GetTemplate() bool`

GetTemplate returns the Template field if non-nil, zero value otherwise.

### GetTemplateOk

`func (o *CustomersApiCreateCustomerAddressRequest) GetTemplateOk() (*bool, bool)`

GetTemplateOk returns a tuple with the Template field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemplate

`func (o *CustomersApiCreateCustomerAddressRequest) SetTemplate(v bool)`

SetTemplate sets Template field to given value.

### HasTemplate

`func (o *CustomersApiCreateCustomerAddressRequest) HasTemplate() bool`

HasTemplate returns a boolean if a field has been set.

### GetIncoTerms

`func (o *CustomersApiCreateCustomerAddressRequest) GetIncoTerms() string`

GetIncoTerms returns the IncoTerms field if non-nil, zero value otherwise.

### GetIncoTermsOk

`func (o *CustomersApiCreateCustomerAddressRequest) GetIncoTermsOk() (*string, bool)`

GetIncoTermsOk returns a tuple with the IncoTerms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncoTerms

`func (o *CustomersApiCreateCustomerAddressRequest) SetIncoTerms(v string)`

SetIncoTerms sets IncoTerms field to given value.

### HasIncoTerms

`func (o *CustomersApiCreateCustomerAddressRequest) HasIncoTerms() bool`

HasIncoTerms returns a boolean if a field has been set.

### GetNegotiatedPlace

`func (o *CustomersApiCreateCustomerAddressRequest) GetNegotiatedPlace() string`

GetNegotiatedPlace returns the NegotiatedPlace field if non-nil, zero value otherwise.

### GetNegotiatedPlaceOk

`func (o *CustomersApiCreateCustomerAddressRequest) GetNegotiatedPlaceOk() (*string, bool)`

GetNegotiatedPlaceOk returns a tuple with the NegotiatedPlace field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNegotiatedPlace

`func (o *CustomersApiCreateCustomerAddressRequest) SetNegotiatedPlace(v string)`

SetNegotiatedPlace sets NegotiatedPlace field to given value.

### HasNegotiatedPlace

`func (o *CustomersApiCreateCustomerAddressRequest) HasNegotiatedPlace() bool`

HasNegotiatedPlace returns a boolean if a field has been set.

### GetBackOrder

`func (o *CustomersApiCreateCustomerAddressRequest) GetBackOrder() string`

GetBackOrder returns the BackOrder field if non-nil, zero value otherwise.

### GetBackOrderOk

`func (o *CustomersApiCreateCustomerAddressRequest) GetBackOrderOk() (*string, bool)`

GetBackOrderOk returns a tuple with the BackOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBackOrder

`func (o *CustomersApiCreateCustomerAddressRequest) SetBackOrder(v string)`

SetBackOrder sets BackOrder field to given value.

### HasBackOrder

`func (o *CustomersApiCreateCustomerAddressRequest) HasBackOrder() bool`

HasBackOrder returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


