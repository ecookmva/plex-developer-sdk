# CustomersApiCreateCustomerAddress201Response

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
**Region** | Pointer to **string** | Screen: Region List | [optional] 
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
**Terms** | Pointer to **string** |  | [optional] 
**Template** | Pointer to **bool** | Only one address can be used as the address template. | [optional] 
**IncoTerms** | Pointer to **string** |  | [optional] 
**NegotiatedPlace** | Pointer to **string** |  | [optional] 
**BackOrder** | Pointer to **string** | Setup Table: Back_Order | [optional] 
**CreatedById** | Pointer to **string** | IAM Account ID | [optional] 
**CreatedDate** | Pointer to **time.Time** |  | [optional] 
**ModifiedById** | Pointer to **string** | IAM Account ID | [optional] 
**ModifiedDate** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewCustomersApiCreateCustomerAddress201Response

`func NewCustomersApiCreateCustomerAddress201Response() *CustomersApiCreateCustomerAddress201Response`

NewCustomersApiCreateCustomerAddress201Response instantiates a new CustomersApiCreateCustomerAddress201Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomersApiCreateCustomerAddress201ResponseWithDefaults

`func NewCustomersApiCreateCustomerAddress201ResponseWithDefaults() *CustomersApiCreateCustomerAddress201Response`

NewCustomersApiCreateCustomerAddress201ResponseWithDefaults instantiates a new CustomersApiCreateCustomerAddress201Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CustomersApiCreateCustomerAddress201Response) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CustomersApiCreateCustomerAddress201Response) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *CustomersApiCreateCustomerAddress201Response) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCode

`func (o *CustomersApiCreateCustomerAddress201Response) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *CustomersApiCreateCustomerAddress201Response) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *CustomersApiCreateCustomerAddress201Response) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetNote

`func (o *CustomersApiCreateCustomerAddress201Response) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *CustomersApiCreateCustomerAddress201Response) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *CustomersApiCreateCustomerAddress201Response) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetQuoteTo

`func (o *CustomersApiCreateCustomerAddress201Response) GetQuoteTo() bool`

GetQuoteTo returns the QuoteTo field if non-nil, zero value otherwise.

### GetQuoteToOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetQuoteToOk() (*bool, bool)`

GetQuoteToOk returns a tuple with the QuoteTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuoteTo

`func (o *CustomersApiCreateCustomerAddress201Response) SetQuoteTo(v bool)`

SetQuoteTo sets QuoteTo field to given value.

### HasQuoteTo

`func (o *CustomersApiCreateCustomerAddress201Response) HasQuoteTo() bool`

HasQuoteTo returns a boolean if a field has been set.

### GetShipTo

`func (o *CustomersApiCreateCustomerAddress201Response) GetShipTo() bool`

GetShipTo returns the ShipTo field if non-nil, zero value otherwise.

### GetShipToOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetShipToOk() (*bool, bool)`

GetShipToOk returns a tuple with the ShipTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipTo

`func (o *CustomersApiCreateCustomerAddress201Response) SetShipTo(v bool)`

SetShipTo sets ShipTo field to given value.

### HasShipTo

`func (o *CustomersApiCreateCustomerAddress201Response) HasShipTo() bool`

HasShipTo returns a boolean if a field has been set.

### GetBillTo

`func (o *CustomersApiCreateCustomerAddress201Response) GetBillTo() bool`

GetBillTo returns the BillTo field if non-nil, zero value otherwise.

### GetBillToOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetBillToOk() (*bool, bool)`

GetBillToOk returns a tuple with the BillTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillTo

`func (o *CustomersApiCreateCustomerAddress201Response) SetBillTo(v bool)`

SetBillTo sets BillTo field to given value.

### HasBillTo

`func (o *CustomersApiCreateCustomerAddress201Response) HasBillTo() bool`

HasBillTo returns a boolean if a field has been set.

### GetBillToAddressId

`func (o *CustomersApiCreateCustomerAddress201Response) GetBillToAddressId() string`

GetBillToAddressId returns the BillToAddressId field if non-nil, zero value otherwise.

### GetBillToAddressIdOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetBillToAddressIdOk() (*string, bool)`

GetBillToAddressIdOk returns a tuple with the BillToAddressId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillToAddressId

`func (o *CustomersApiCreateCustomerAddress201Response) SetBillToAddressId(v string)`

SetBillToAddressId sets BillToAddressId field to given value.

### HasBillToAddressId

`func (o *CustomersApiCreateCustomerAddress201Response) HasBillToAddressId() bool`

HasBillToAddressId returns a boolean if a field has been set.

### GetRemitTo

`func (o *CustomersApiCreateCustomerAddress201Response) GetRemitTo() bool`

GetRemitTo returns the RemitTo field if non-nil, zero value otherwise.

### GetRemitToOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetRemitToOk() (*bool, bool)`

GetRemitToOk returns a tuple with the RemitTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemitTo

`func (o *CustomersApiCreateCustomerAddress201Response) SetRemitTo(v bool)`

SetRemitTo sets RemitTo field to given value.

### HasRemitTo

`func (o *CustomersApiCreateCustomerAddress201Response) HasRemitTo() bool`

HasRemitTo returns a boolean if a field has been set.

### GetThirdPartyShipTo

`func (o *CustomersApiCreateCustomerAddress201Response) GetThirdPartyShipTo() bool`

GetThirdPartyShipTo returns the ThirdPartyShipTo field if non-nil, zero value otherwise.

### GetThirdPartyShipToOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetThirdPartyShipToOk() (*bool, bool)`

GetThirdPartyShipToOk returns a tuple with the ThirdPartyShipTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThirdPartyShipTo

`func (o *CustomersApiCreateCustomerAddress201Response) SetThirdPartyShipTo(v bool)`

SetThirdPartyShipTo sets ThirdPartyShipTo field to given value.

### HasThirdPartyShipTo

`func (o *CustomersApiCreateCustomerAddress201Response) HasThirdPartyShipTo() bool`

HasThirdPartyShipTo returns a boolean if a field has been set.

### GetThirdPartyShipToAddressId

`func (o *CustomersApiCreateCustomerAddress201Response) GetThirdPartyShipToAddressId() string`

GetThirdPartyShipToAddressId returns the ThirdPartyShipToAddressId field if non-nil, zero value otherwise.

### GetThirdPartyShipToAddressIdOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetThirdPartyShipToAddressIdOk() (*string, bool)`

GetThirdPartyShipToAddressIdOk returns a tuple with the ThirdPartyShipToAddressId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThirdPartyShipToAddressId

`func (o *CustomersApiCreateCustomerAddress201Response) SetThirdPartyShipToAddressId(v string)`

SetThirdPartyShipToAddressId sets ThirdPartyShipToAddressId field to given value.

### HasThirdPartyShipToAddressId

`func (o *CustomersApiCreateCustomerAddress201Response) HasThirdPartyShipToAddressId() bool`

HasThirdPartyShipToAddressId returns a boolean if a field has been set.

### GetPool

`func (o *CustomersApiCreateCustomerAddress201Response) GetPool() bool`

GetPool returns the Pool field if non-nil, zero value otherwise.

### GetPoolOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetPoolOk() (*bool, bool)`

GetPoolOk returns a tuple with the Pool field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPool

`func (o *CustomersApiCreateCustomerAddress201Response) SetPool(v bool)`

SetPool sets Pool field to given value.

### HasPool

`func (o *CustomersApiCreateCustomerAddress201Response) HasPool() bool`

HasPool returns a boolean if a field has been set.

### GetPoolAddressId

`func (o *CustomersApiCreateCustomerAddress201Response) GetPoolAddressId() string`

GetPoolAddressId returns the PoolAddressId field if non-nil, zero value otherwise.

### GetPoolAddressIdOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetPoolAddressIdOk() (*string, bool)`

GetPoolAddressIdOk returns a tuple with the PoolAddressId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoolAddressId

`func (o *CustomersApiCreateCustomerAddress201Response) SetPoolAddressId(v string)`

SetPoolAddressId sets PoolAddressId field to given value.

### HasPoolAddressId

`func (o *CustomersApiCreateCustomerAddress201Response) HasPoolAddressId() bool`

HasPoolAddressId returns a boolean if a field has been set.

### GetOldCustomerNo

`func (o *CustomersApiCreateCustomerAddress201Response) GetOldCustomerNo() string`

GetOldCustomerNo returns the OldCustomerNo field if non-nil, zero value otherwise.

### GetOldCustomerNoOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetOldCustomerNoOk() (*string, bool)`

GetOldCustomerNoOk returns a tuple with the OldCustomerNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOldCustomerNo

`func (o *CustomersApiCreateCustomerAddress201Response) SetOldCustomerNo(v string)`

SetOldCustomerNo sets OldCustomerNo field to given value.

### HasOldCustomerNo

`func (o *CustomersApiCreateCustomerAddress201Response) HasOldCustomerNo() bool`

HasOldCustomerNo returns a boolean if a field has been set.

### GetActive

`func (o *CustomersApiCreateCustomerAddress201Response) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *CustomersApiCreateCustomerAddress201Response) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *CustomersApiCreateCustomerAddress201Response) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetPhone

`func (o *CustomersApiCreateCustomerAddress201Response) GetPhone() string`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetPhoneOk() (*string, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *CustomersApiCreateCustomerAddress201Response) SetPhone(v string)`

SetPhone sets Phone field to given value.

### HasPhone

`func (o *CustomersApiCreateCustomerAddress201Response) HasPhone() bool`

HasPhone returns a boolean if a field has been set.

### GetFax

`func (o *CustomersApiCreateCustomerAddress201Response) GetFax() string`

GetFax returns the Fax field if non-nil, zero value otherwise.

### GetFaxOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetFaxOk() (*string, bool)`

GetFaxOk returns a tuple with the Fax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFax

`func (o *CustomersApiCreateCustomerAddress201Response) SetFax(v string)`

SetFax sets Fax field to given value.

### HasFax

`func (o *CustomersApiCreateCustomerAddress201Response) HasFax() bool`

HasFax returns a boolean if a field has been set.

### GetEmail

`func (o *CustomersApiCreateCustomerAddress201Response) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *CustomersApiCreateCustomerAddress201Response) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *CustomersApiCreateCustomerAddress201Response) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetName

`func (o *CustomersApiCreateCustomerAddress201Response) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CustomersApiCreateCustomerAddress201Response) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *CustomersApiCreateCustomerAddress201Response) HasName() bool`

HasName returns a boolean if a field has been set.

### GetAddress

`func (o *CustomersApiCreateCustomerAddress201Response) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *CustomersApiCreateCustomerAddress201Response) SetAddress(v string)`

SetAddress sets Address field to given value.

### HasAddress

`func (o *CustomersApiCreateCustomerAddress201Response) HasAddress() bool`

HasAddress returns a boolean if a field has been set.

### GetCity

`func (o *CustomersApiCreateCustomerAddress201Response) GetCity() string`

GetCity returns the City field if non-nil, zero value otherwise.

### GetCityOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetCityOk() (*string, bool)`

GetCityOk returns a tuple with the City field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCity

`func (o *CustomersApiCreateCustomerAddress201Response) SetCity(v string)`

SetCity sets City field to given value.

### HasCity

`func (o *CustomersApiCreateCustomerAddress201Response) HasCity() bool`

HasCity returns a boolean if a field has been set.

### GetState

`func (o *CustomersApiCreateCustomerAddress201Response) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *CustomersApiCreateCustomerAddress201Response) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *CustomersApiCreateCustomerAddress201Response) HasState() bool`

HasState returns a boolean if a field has been set.

### GetZip

`func (o *CustomersApiCreateCustomerAddress201Response) GetZip() string`

GetZip returns the Zip field if non-nil, zero value otherwise.

### GetZipOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetZipOk() (*string, bool)`

GetZipOk returns a tuple with the Zip field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetZip

`func (o *CustomersApiCreateCustomerAddress201Response) SetZip(v string)`

SetZip sets Zip field to given value.

### HasZip

`func (o *CustomersApiCreateCustomerAddress201Response) HasZip() bool`

HasZip returns a boolean if a field has been set.

### GetCountry

`func (o *CustomersApiCreateCustomerAddress201Response) GetCountry() string`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetCountryOk() (*string, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *CustomersApiCreateCustomerAddress201Response) SetCountry(v string)`

SetCountry sets Country field to given value.

### HasCountry

`func (o *CustomersApiCreateCustomerAddress201Response) HasCountry() bool`

HasCountry returns a boolean if a field has been set.

### GetRegion

`func (o *CustomersApiCreateCustomerAddress201Response) GetRegion() string`

GetRegion returns the Region field if non-nil, zero value otherwise.

### GetRegionOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetRegionOk() (*string, bool)`

GetRegionOk returns a tuple with the Region field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegion

`func (o *CustomersApiCreateCustomerAddress201Response) SetRegion(v string)`

SetRegion sets Region field to given value.

### HasRegion

`func (o *CustomersApiCreateCustomerAddress201Response) HasRegion() bool`

HasRegion returns a boolean if a field has been set.

### GetCounty

`func (o *CustomersApiCreateCustomerAddress201Response) GetCounty() string`

GetCounty returns the County field if non-nil, zero value otherwise.

### GetCountyOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetCountyOk() (*string, bool)`

GetCountyOk returns a tuple with the County field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCounty

`func (o *CustomersApiCreateCustomerAddress201Response) SetCounty(v string)`

SetCounty sets County field to given value.

### HasCounty

`func (o *CustomersApiCreateCustomerAddress201Response) HasCounty() bool`

HasCounty returns a boolean if a field has been set.

### GetShippingInstructions

`func (o *CustomersApiCreateCustomerAddress201Response) GetShippingInstructions() string`

GetShippingInstructions returns the ShippingInstructions field if non-nil, zero value otherwise.

### GetShippingInstructionsOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetShippingInstructionsOk() (*string, bool)`

GetShippingInstructionsOk returns a tuple with the ShippingInstructions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingInstructions

`func (o *CustomersApiCreateCustomerAddress201Response) SetShippingInstructions(v string)`

SetShippingInstructions sets ShippingInstructions field to given value.

### HasShippingInstructions

`func (o *CustomersApiCreateCustomerAddress201Response) HasShippingInstructions() bool`

HasShippingInstructions returns a boolean if a field has been set.

### GetIgnoreTransitOnWeekends

`func (o *CustomersApiCreateCustomerAddress201Response) GetIgnoreTransitOnWeekends() bool`

GetIgnoreTransitOnWeekends returns the IgnoreTransitOnWeekends field if non-nil, zero value otherwise.

### GetIgnoreTransitOnWeekendsOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetIgnoreTransitOnWeekendsOk() (*bool, bool)`

GetIgnoreTransitOnWeekendsOk returns a tuple with the IgnoreTransitOnWeekends field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIgnoreTransitOnWeekends

`func (o *CustomersApiCreateCustomerAddress201Response) SetIgnoreTransitOnWeekends(v bool)`

SetIgnoreTransitOnWeekends sets IgnoreTransitOnWeekends field to given value.

### HasIgnoreTransitOnWeekends

`func (o *CustomersApiCreateCustomerAddress201Response) HasIgnoreTransitOnWeekends() bool`

HasIgnoreTransitOnWeekends returns a boolean if a field has been set.

### GetTransportationLeadTime

`func (o *CustomersApiCreateCustomerAddress201Response) GetTransportationLeadTime() int32`

GetTransportationLeadTime returns the TransportationLeadTime field if non-nil, zero value otherwise.

### GetTransportationLeadTimeOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetTransportationLeadTimeOk() (*int32, bool)`

GetTransportationLeadTimeOk returns a tuple with the TransportationLeadTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransportationLeadTime

`func (o *CustomersApiCreateCustomerAddress201Response) SetTransportationLeadTime(v int32)`

SetTransportationLeadTime sets TransportationLeadTime field to given value.

### HasTransportationLeadTime

`func (o *CustomersApiCreateCustomerAddress201Response) HasTransportationLeadTime() bool`

HasTransportationLeadTime returns a boolean if a field has been set.

### GetDefaultCarrierIds

`func (o *CustomersApiCreateCustomerAddress201Response) GetDefaultCarrierIds() []string`

GetDefaultCarrierIds returns the DefaultCarrierIds field if non-nil, zero value otherwise.

### GetDefaultCarrierIdsOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetDefaultCarrierIdsOk() (*[]string, bool)`

GetDefaultCarrierIdsOk returns a tuple with the DefaultCarrierIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultCarrierIds

`func (o *CustomersApiCreateCustomerAddress201Response) SetDefaultCarrierIds(v []string)`

SetDefaultCarrierIds sets DefaultCarrierIds field to given value.

### HasDefaultCarrierIds

`func (o *CustomersApiCreateCustomerAddress201Response) HasDefaultCarrierIds() bool`

HasDefaultCarrierIds returns a boolean if a field has been set.

### GetTruckType

`func (o *CustomersApiCreateCustomerAddress201Response) GetTruckType() string`

GetTruckType returns the TruckType field if non-nil, zero value otherwise.

### GetTruckTypeOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetTruckTypeOk() (*string, bool)`

GetTruckTypeOk returns a tuple with the TruckType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckType

`func (o *CustomersApiCreateCustomerAddress201Response) SetTruckType(v string)`

SetTruckType sets TruckType field to given value.

### HasTruckType

`func (o *CustomersApiCreateCustomerAddress201Response) HasTruckType() bool`

HasTruckType returns a boolean if a field has been set.

### GetSalesTaxExempt

`func (o *CustomersApiCreateCustomerAddress201Response) GetSalesTaxExempt() bool`

GetSalesTaxExempt returns the SalesTaxExempt field if non-nil, zero value otherwise.

### GetSalesTaxExemptOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetSalesTaxExemptOk() (*bool, bool)`

GetSalesTaxExemptOk returns a tuple with the SalesTaxExempt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSalesTaxExempt

`func (o *CustomersApiCreateCustomerAddress201Response) SetSalesTaxExempt(v bool)`

SetSalesTaxExempt sets SalesTaxExempt field to given value.

### HasSalesTaxExempt

`func (o *CustomersApiCreateCustomerAddress201Response) HasSalesTaxExempt() bool`

HasSalesTaxExempt returns a boolean if a field has been set.

### GetSalespersonId

`func (o *CustomersApiCreateCustomerAddress201Response) GetSalespersonId() string`

GetSalespersonId returns the SalespersonId field if non-nil, zero value otherwise.

### GetSalespersonIdOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetSalespersonIdOk() (*string, bool)`

GetSalespersonIdOk returns a tuple with the SalespersonId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSalespersonId

`func (o *CustomersApiCreateCustomerAddress201Response) SetSalespersonId(v string)`

SetSalespersonId sets SalespersonId field to given value.

### HasSalespersonId

`func (o *CustomersApiCreateCustomerAddress201Response) HasSalespersonId() bool`

HasSalespersonId returns a boolean if a field has been set.

### GetStatementAddressId

`func (o *CustomersApiCreateCustomerAddress201Response) GetStatementAddressId() string`

GetStatementAddressId returns the StatementAddressId field if non-nil, zero value otherwise.

### GetStatementAddressIdOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetStatementAddressIdOk() (*string, bool)`

GetStatementAddressIdOk returns a tuple with the StatementAddressId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatementAddressId

`func (o *CustomersApiCreateCustomerAddress201Response) SetStatementAddressId(v string)`

SetStatementAddressId sets StatementAddressId field to given value.

### HasStatementAddressId

`func (o *CustomersApiCreateCustomerAddress201Response) HasStatementAddressId() bool`

HasStatementAddressId returns a boolean if a field has been set.

### GetFreightTerms

`func (o *CustomersApiCreateCustomerAddress201Response) GetFreightTerms() string`

GetFreightTerms returns the FreightTerms field if non-nil, zero value otherwise.

### GetFreightTermsOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetFreightTermsOk() (*string, bool)`

GetFreightTermsOk returns a tuple with the FreightTerms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFreightTerms

`func (o *CustomersApiCreateCustomerAddress201Response) SetFreightTerms(v string)`

SetFreightTerms sets FreightTerms field to given value.

### HasFreightTerms

`func (o *CustomersApiCreateCustomerAddress201Response) HasFreightTerms() bool`

HasFreightTerms returns a boolean if a field has been set.

### GetInsideSalespersonId

`func (o *CustomersApiCreateCustomerAddress201Response) GetInsideSalespersonId() string`

GetInsideSalespersonId returns the InsideSalespersonId field if non-nil, zero value otherwise.

### GetInsideSalespersonIdOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetInsideSalespersonIdOk() (*string, bool)`

GetInsideSalespersonIdOk returns a tuple with the InsideSalespersonId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInsideSalespersonId

`func (o *CustomersApiCreateCustomerAddress201Response) SetInsideSalespersonId(v string)`

SetInsideSalespersonId sets InsideSalespersonId field to given value.

### HasInsideSalespersonId

`func (o *CustomersApiCreateCustomerAddress201Response) HasInsideSalespersonId() bool`

HasInsideSalespersonId returns a boolean if a field has been set.

### GetDefaultShipFrom

`func (o *CustomersApiCreateCustomerAddress201Response) GetDefaultShipFrom() string`

GetDefaultShipFrom returns the DefaultShipFrom field if non-nil, zero value otherwise.

### GetDefaultShipFromOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetDefaultShipFromOk() (*string, bool)`

GetDefaultShipFromOk returns a tuple with the DefaultShipFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultShipFrom

`func (o *CustomersApiCreateCustomerAddress201Response) SetDefaultShipFrom(v string)`

SetDefaultShipFrom sets DefaultShipFrom field to given value.

### HasDefaultShipFrom

`func (o *CustomersApiCreateCustomerAddress201Response) HasDefaultShipFrom() bool`

HasDefaultShipFrom returns a boolean if a field has been set.

### GetFreightBillTo

`func (o *CustomersApiCreateCustomerAddress201Response) GetFreightBillTo() bool`

GetFreightBillTo returns the FreightBillTo field if non-nil, zero value otherwise.

### GetFreightBillToOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetFreightBillToOk() (*bool, bool)`

GetFreightBillToOk returns a tuple with the FreightBillTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFreightBillTo

`func (o *CustomersApiCreateCustomerAddress201Response) SetFreightBillTo(v bool)`

SetFreightBillTo sets FreightBillTo field to given value.

### HasFreightBillTo

`func (o *CustomersApiCreateCustomerAddress201Response) HasFreightBillTo() bool`

HasFreightBillTo returns a boolean if a field has been set.

### GetFreightBillToAddressId

`func (o *CustomersApiCreateCustomerAddress201Response) GetFreightBillToAddressId() string`

GetFreightBillToAddressId returns the FreightBillToAddressId field if non-nil, zero value otherwise.

### GetFreightBillToAddressIdOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetFreightBillToAddressIdOk() (*string, bool)`

GetFreightBillToAddressIdOk returns a tuple with the FreightBillToAddressId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFreightBillToAddressId

`func (o *CustomersApiCreateCustomerAddress201Response) SetFreightBillToAddressId(v string)`

SetFreightBillToAddressId sets FreightBillToAddressId field to given value.

### HasFreightBillToAddressId

`func (o *CustomersApiCreateCustomerAddress201Response) HasFreightBillToAddressId() bool`

HasFreightBillToAddressId returns a boolean if a field has been set.

### GetCatalog

`func (o *CustomersApiCreateCustomerAddress201Response) GetCatalog() string`

GetCatalog returns the Catalog field if non-nil, zero value otherwise.

### GetCatalogOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetCatalogOk() (*string, bool)`

GetCatalogOk returns a tuple with the Catalog field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCatalog

`func (o *CustomersApiCreateCustomerAddress201Response) SetCatalog(v string)`

SetCatalog sets Catalog field to given value.

### HasCatalog

`func (o *CustomersApiCreateCustomerAddress201Response) HasCatalog() bool`

HasCatalog returns a boolean if a field has been set.

### GetSoldTo

`func (o *CustomersApiCreateCustomerAddress201Response) GetSoldTo() bool`

GetSoldTo returns the SoldTo field if non-nil, zero value otherwise.

### GetSoldToOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetSoldToOk() (*bool, bool)`

GetSoldToOk returns a tuple with the SoldTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSoldTo

`func (o *CustomersApiCreateCustomerAddress201Response) SetSoldTo(v bool)`

SetSoldTo sets SoldTo field to given value.

### HasSoldTo

`func (o *CustomersApiCreateCustomerAddress201Response) HasSoldTo() bool`

HasSoldTo returns a boolean if a field has been set.

### GetDunsNo

`func (o *CustomersApiCreateCustomerAddress201Response) GetDunsNo() string`

GetDunsNo returns the DunsNo field if non-nil, zero value otherwise.

### GetDunsNoOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetDunsNoOk() (*string, bool)`

GetDunsNoOk returns a tuple with the DunsNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDunsNo

`func (o *CustomersApiCreateCustomerAddress201Response) SetDunsNo(v string)`

SetDunsNo sets DunsNo field to given value.

### HasDunsNo

`func (o *CustomersApiCreateCustomerAddress201Response) HasDunsNo() bool`

HasDunsNo returns a boolean if a field has been set.

### GetCommercialInvoiceVatNo

`func (o *CustomersApiCreateCustomerAddress201Response) GetCommercialInvoiceVatNo() string`

GetCommercialInvoiceVatNo returns the CommercialInvoiceVatNo field if non-nil, zero value otherwise.

### GetCommercialInvoiceVatNoOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetCommercialInvoiceVatNoOk() (*string, bool)`

GetCommercialInvoiceVatNoOk returns a tuple with the CommercialInvoiceVatNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCommercialInvoiceVatNo

`func (o *CustomersApiCreateCustomerAddress201Response) SetCommercialInvoiceVatNo(v string)`

SetCommercialInvoiceVatNo sets CommercialInvoiceVatNo field to given value.

### HasCommercialInvoiceVatNo

`func (o *CustomersApiCreateCustomerAddress201Response) HasCommercialInvoiceVatNo() bool`

HasCommercialInvoiceVatNo returns a boolean if a field has been set.

### GetTerms

`func (o *CustomersApiCreateCustomerAddress201Response) GetTerms() string`

GetTerms returns the Terms field if non-nil, zero value otherwise.

### GetTermsOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetTermsOk() (*string, bool)`

GetTermsOk returns a tuple with the Terms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTerms

`func (o *CustomersApiCreateCustomerAddress201Response) SetTerms(v string)`

SetTerms sets Terms field to given value.

### HasTerms

`func (o *CustomersApiCreateCustomerAddress201Response) HasTerms() bool`

HasTerms returns a boolean if a field has been set.

### GetTemplate

`func (o *CustomersApiCreateCustomerAddress201Response) GetTemplate() bool`

GetTemplate returns the Template field if non-nil, zero value otherwise.

### GetTemplateOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetTemplateOk() (*bool, bool)`

GetTemplateOk returns a tuple with the Template field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemplate

`func (o *CustomersApiCreateCustomerAddress201Response) SetTemplate(v bool)`

SetTemplate sets Template field to given value.

### HasTemplate

`func (o *CustomersApiCreateCustomerAddress201Response) HasTemplate() bool`

HasTemplate returns a boolean if a field has been set.

### GetIncoTerms

`func (o *CustomersApiCreateCustomerAddress201Response) GetIncoTerms() string`

GetIncoTerms returns the IncoTerms field if non-nil, zero value otherwise.

### GetIncoTermsOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetIncoTermsOk() (*string, bool)`

GetIncoTermsOk returns a tuple with the IncoTerms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncoTerms

`func (o *CustomersApiCreateCustomerAddress201Response) SetIncoTerms(v string)`

SetIncoTerms sets IncoTerms field to given value.

### HasIncoTerms

`func (o *CustomersApiCreateCustomerAddress201Response) HasIncoTerms() bool`

HasIncoTerms returns a boolean if a field has been set.

### GetNegotiatedPlace

`func (o *CustomersApiCreateCustomerAddress201Response) GetNegotiatedPlace() string`

GetNegotiatedPlace returns the NegotiatedPlace field if non-nil, zero value otherwise.

### GetNegotiatedPlaceOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetNegotiatedPlaceOk() (*string, bool)`

GetNegotiatedPlaceOk returns a tuple with the NegotiatedPlace field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNegotiatedPlace

`func (o *CustomersApiCreateCustomerAddress201Response) SetNegotiatedPlace(v string)`

SetNegotiatedPlace sets NegotiatedPlace field to given value.

### HasNegotiatedPlace

`func (o *CustomersApiCreateCustomerAddress201Response) HasNegotiatedPlace() bool`

HasNegotiatedPlace returns a boolean if a field has been set.

### GetBackOrder

`func (o *CustomersApiCreateCustomerAddress201Response) GetBackOrder() string`

GetBackOrder returns the BackOrder field if non-nil, zero value otherwise.

### GetBackOrderOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetBackOrderOk() (*string, bool)`

GetBackOrderOk returns a tuple with the BackOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBackOrder

`func (o *CustomersApiCreateCustomerAddress201Response) SetBackOrder(v string)`

SetBackOrder sets BackOrder field to given value.

### HasBackOrder

`func (o *CustomersApiCreateCustomerAddress201Response) HasBackOrder() bool`

HasBackOrder returns a boolean if a field has been set.

### GetCreatedById

`func (o *CustomersApiCreateCustomerAddress201Response) GetCreatedById() string`

GetCreatedById returns the CreatedById field if non-nil, zero value otherwise.

### GetCreatedByIdOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetCreatedByIdOk() (*string, bool)`

GetCreatedByIdOk returns a tuple with the CreatedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedById

`func (o *CustomersApiCreateCustomerAddress201Response) SetCreatedById(v string)`

SetCreatedById sets CreatedById field to given value.

### HasCreatedById

`func (o *CustomersApiCreateCustomerAddress201Response) HasCreatedById() bool`

HasCreatedById returns a boolean if a field has been set.

### GetCreatedDate

`func (o *CustomersApiCreateCustomerAddress201Response) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *CustomersApiCreateCustomerAddress201Response) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *CustomersApiCreateCustomerAddress201Response) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.

### GetModifiedById

`func (o *CustomersApiCreateCustomerAddress201Response) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *CustomersApiCreateCustomerAddress201Response) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *CustomersApiCreateCustomerAddress201Response) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetModifiedDate

`func (o *CustomersApiCreateCustomerAddress201Response) GetModifiedDate() time.Time`

GetModifiedDate returns the ModifiedDate field if non-nil, zero value otherwise.

### GetModifiedDateOk

`func (o *CustomersApiCreateCustomerAddress201Response) GetModifiedDateOk() (*time.Time, bool)`

GetModifiedDateOk returns a tuple with the ModifiedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDate

`func (o *CustomersApiCreateCustomerAddress201Response) SetModifiedDate(v time.Time)`

SetModifiedDate sets ModifiedDate field to given value.

### HasModifiedDate

`func (o *CustomersApiCreateCustomerAddress201Response) HasModifiedDate() bool`

HasModifiedDate returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


