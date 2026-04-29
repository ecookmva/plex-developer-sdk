# CustomersApiListCustomerAddressesItem

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

### NewCustomersApiListCustomerAddressesItem

`func NewCustomersApiListCustomerAddressesItem() *CustomersApiListCustomerAddressesItem`

NewCustomersApiListCustomerAddressesItem instantiates a new CustomersApiListCustomerAddressesItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomersApiListCustomerAddressesItemWithDefaults

`func NewCustomersApiListCustomerAddressesItemWithDefaults() *CustomersApiListCustomerAddressesItem`

NewCustomersApiListCustomerAddressesItemWithDefaults instantiates a new CustomersApiListCustomerAddressesItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CustomersApiListCustomerAddressesItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CustomersApiListCustomerAddressesItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CustomersApiListCustomerAddressesItem) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *CustomersApiListCustomerAddressesItem) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCode

`func (o *CustomersApiListCustomerAddressesItem) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *CustomersApiListCustomerAddressesItem) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *CustomersApiListCustomerAddressesItem) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *CustomersApiListCustomerAddressesItem) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetNote

`func (o *CustomersApiListCustomerAddressesItem) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *CustomersApiListCustomerAddressesItem) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *CustomersApiListCustomerAddressesItem) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *CustomersApiListCustomerAddressesItem) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetQuoteTo

`func (o *CustomersApiListCustomerAddressesItem) GetQuoteTo() bool`

GetQuoteTo returns the QuoteTo field if non-nil, zero value otherwise.

### GetQuoteToOk

`func (o *CustomersApiListCustomerAddressesItem) GetQuoteToOk() (*bool, bool)`

GetQuoteToOk returns a tuple with the QuoteTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuoteTo

`func (o *CustomersApiListCustomerAddressesItem) SetQuoteTo(v bool)`

SetQuoteTo sets QuoteTo field to given value.

### HasQuoteTo

`func (o *CustomersApiListCustomerAddressesItem) HasQuoteTo() bool`

HasQuoteTo returns a boolean if a field has been set.

### GetShipTo

`func (o *CustomersApiListCustomerAddressesItem) GetShipTo() bool`

GetShipTo returns the ShipTo field if non-nil, zero value otherwise.

### GetShipToOk

`func (o *CustomersApiListCustomerAddressesItem) GetShipToOk() (*bool, bool)`

GetShipToOk returns a tuple with the ShipTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipTo

`func (o *CustomersApiListCustomerAddressesItem) SetShipTo(v bool)`

SetShipTo sets ShipTo field to given value.

### HasShipTo

`func (o *CustomersApiListCustomerAddressesItem) HasShipTo() bool`

HasShipTo returns a boolean if a field has been set.

### GetBillTo

`func (o *CustomersApiListCustomerAddressesItem) GetBillTo() bool`

GetBillTo returns the BillTo field if non-nil, zero value otherwise.

### GetBillToOk

`func (o *CustomersApiListCustomerAddressesItem) GetBillToOk() (*bool, bool)`

GetBillToOk returns a tuple with the BillTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillTo

`func (o *CustomersApiListCustomerAddressesItem) SetBillTo(v bool)`

SetBillTo sets BillTo field to given value.

### HasBillTo

`func (o *CustomersApiListCustomerAddressesItem) HasBillTo() bool`

HasBillTo returns a boolean if a field has been set.

### GetBillToAddressId

`func (o *CustomersApiListCustomerAddressesItem) GetBillToAddressId() string`

GetBillToAddressId returns the BillToAddressId field if non-nil, zero value otherwise.

### GetBillToAddressIdOk

`func (o *CustomersApiListCustomerAddressesItem) GetBillToAddressIdOk() (*string, bool)`

GetBillToAddressIdOk returns a tuple with the BillToAddressId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillToAddressId

`func (o *CustomersApiListCustomerAddressesItem) SetBillToAddressId(v string)`

SetBillToAddressId sets BillToAddressId field to given value.

### HasBillToAddressId

`func (o *CustomersApiListCustomerAddressesItem) HasBillToAddressId() bool`

HasBillToAddressId returns a boolean if a field has been set.

### GetRemitTo

`func (o *CustomersApiListCustomerAddressesItem) GetRemitTo() bool`

GetRemitTo returns the RemitTo field if non-nil, zero value otherwise.

### GetRemitToOk

`func (o *CustomersApiListCustomerAddressesItem) GetRemitToOk() (*bool, bool)`

GetRemitToOk returns a tuple with the RemitTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemitTo

`func (o *CustomersApiListCustomerAddressesItem) SetRemitTo(v bool)`

SetRemitTo sets RemitTo field to given value.

### HasRemitTo

`func (o *CustomersApiListCustomerAddressesItem) HasRemitTo() bool`

HasRemitTo returns a boolean if a field has been set.

### GetThirdPartyShipTo

`func (o *CustomersApiListCustomerAddressesItem) GetThirdPartyShipTo() bool`

GetThirdPartyShipTo returns the ThirdPartyShipTo field if non-nil, zero value otherwise.

### GetThirdPartyShipToOk

`func (o *CustomersApiListCustomerAddressesItem) GetThirdPartyShipToOk() (*bool, bool)`

GetThirdPartyShipToOk returns a tuple with the ThirdPartyShipTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThirdPartyShipTo

`func (o *CustomersApiListCustomerAddressesItem) SetThirdPartyShipTo(v bool)`

SetThirdPartyShipTo sets ThirdPartyShipTo field to given value.

### HasThirdPartyShipTo

`func (o *CustomersApiListCustomerAddressesItem) HasThirdPartyShipTo() bool`

HasThirdPartyShipTo returns a boolean if a field has been set.

### GetThirdPartyShipToAddressId

`func (o *CustomersApiListCustomerAddressesItem) GetThirdPartyShipToAddressId() string`

GetThirdPartyShipToAddressId returns the ThirdPartyShipToAddressId field if non-nil, zero value otherwise.

### GetThirdPartyShipToAddressIdOk

`func (o *CustomersApiListCustomerAddressesItem) GetThirdPartyShipToAddressIdOk() (*string, bool)`

GetThirdPartyShipToAddressIdOk returns a tuple with the ThirdPartyShipToAddressId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThirdPartyShipToAddressId

`func (o *CustomersApiListCustomerAddressesItem) SetThirdPartyShipToAddressId(v string)`

SetThirdPartyShipToAddressId sets ThirdPartyShipToAddressId field to given value.

### HasThirdPartyShipToAddressId

`func (o *CustomersApiListCustomerAddressesItem) HasThirdPartyShipToAddressId() bool`

HasThirdPartyShipToAddressId returns a boolean if a field has been set.

### GetPool

`func (o *CustomersApiListCustomerAddressesItem) GetPool() bool`

GetPool returns the Pool field if non-nil, zero value otherwise.

### GetPoolOk

`func (o *CustomersApiListCustomerAddressesItem) GetPoolOk() (*bool, bool)`

GetPoolOk returns a tuple with the Pool field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPool

`func (o *CustomersApiListCustomerAddressesItem) SetPool(v bool)`

SetPool sets Pool field to given value.

### HasPool

`func (o *CustomersApiListCustomerAddressesItem) HasPool() bool`

HasPool returns a boolean if a field has been set.

### GetPoolAddressId

`func (o *CustomersApiListCustomerAddressesItem) GetPoolAddressId() string`

GetPoolAddressId returns the PoolAddressId field if non-nil, zero value otherwise.

### GetPoolAddressIdOk

`func (o *CustomersApiListCustomerAddressesItem) GetPoolAddressIdOk() (*string, bool)`

GetPoolAddressIdOk returns a tuple with the PoolAddressId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoolAddressId

`func (o *CustomersApiListCustomerAddressesItem) SetPoolAddressId(v string)`

SetPoolAddressId sets PoolAddressId field to given value.

### HasPoolAddressId

`func (o *CustomersApiListCustomerAddressesItem) HasPoolAddressId() bool`

HasPoolAddressId returns a boolean if a field has been set.

### GetOldCustomerNo

`func (o *CustomersApiListCustomerAddressesItem) GetOldCustomerNo() string`

GetOldCustomerNo returns the OldCustomerNo field if non-nil, zero value otherwise.

### GetOldCustomerNoOk

`func (o *CustomersApiListCustomerAddressesItem) GetOldCustomerNoOk() (*string, bool)`

GetOldCustomerNoOk returns a tuple with the OldCustomerNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOldCustomerNo

`func (o *CustomersApiListCustomerAddressesItem) SetOldCustomerNo(v string)`

SetOldCustomerNo sets OldCustomerNo field to given value.

### HasOldCustomerNo

`func (o *CustomersApiListCustomerAddressesItem) HasOldCustomerNo() bool`

HasOldCustomerNo returns a boolean if a field has been set.

### GetActive

`func (o *CustomersApiListCustomerAddressesItem) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *CustomersApiListCustomerAddressesItem) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *CustomersApiListCustomerAddressesItem) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *CustomersApiListCustomerAddressesItem) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetPhone

`func (o *CustomersApiListCustomerAddressesItem) GetPhone() string`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *CustomersApiListCustomerAddressesItem) GetPhoneOk() (*string, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *CustomersApiListCustomerAddressesItem) SetPhone(v string)`

SetPhone sets Phone field to given value.

### HasPhone

`func (o *CustomersApiListCustomerAddressesItem) HasPhone() bool`

HasPhone returns a boolean if a field has been set.

### GetFax

`func (o *CustomersApiListCustomerAddressesItem) GetFax() string`

GetFax returns the Fax field if non-nil, zero value otherwise.

### GetFaxOk

`func (o *CustomersApiListCustomerAddressesItem) GetFaxOk() (*string, bool)`

GetFaxOk returns a tuple with the Fax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFax

`func (o *CustomersApiListCustomerAddressesItem) SetFax(v string)`

SetFax sets Fax field to given value.

### HasFax

`func (o *CustomersApiListCustomerAddressesItem) HasFax() bool`

HasFax returns a boolean if a field has been set.

### GetEmail

`func (o *CustomersApiListCustomerAddressesItem) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *CustomersApiListCustomerAddressesItem) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *CustomersApiListCustomerAddressesItem) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *CustomersApiListCustomerAddressesItem) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetName

`func (o *CustomersApiListCustomerAddressesItem) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CustomersApiListCustomerAddressesItem) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CustomersApiListCustomerAddressesItem) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *CustomersApiListCustomerAddressesItem) HasName() bool`

HasName returns a boolean if a field has been set.

### GetAddress

`func (o *CustomersApiListCustomerAddressesItem) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *CustomersApiListCustomerAddressesItem) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *CustomersApiListCustomerAddressesItem) SetAddress(v string)`

SetAddress sets Address field to given value.

### HasAddress

`func (o *CustomersApiListCustomerAddressesItem) HasAddress() bool`

HasAddress returns a boolean if a field has been set.

### GetCity

`func (o *CustomersApiListCustomerAddressesItem) GetCity() string`

GetCity returns the City field if non-nil, zero value otherwise.

### GetCityOk

`func (o *CustomersApiListCustomerAddressesItem) GetCityOk() (*string, bool)`

GetCityOk returns a tuple with the City field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCity

`func (o *CustomersApiListCustomerAddressesItem) SetCity(v string)`

SetCity sets City field to given value.

### HasCity

`func (o *CustomersApiListCustomerAddressesItem) HasCity() bool`

HasCity returns a boolean if a field has been set.

### GetState

`func (o *CustomersApiListCustomerAddressesItem) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *CustomersApiListCustomerAddressesItem) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *CustomersApiListCustomerAddressesItem) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *CustomersApiListCustomerAddressesItem) HasState() bool`

HasState returns a boolean if a field has been set.

### GetZip

`func (o *CustomersApiListCustomerAddressesItem) GetZip() string`

GetZip returns the Zip field if non-nil, zero value otherwise.

### GetZipOk

`func (o *CustomersApiListCustomerAddressesItem) GetZipOk() (*string, bool)`

GetZipOk returns a tuple with the Zip field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetZip

`func (o *CustomersApiListCustomerAddressesItem) SetZip(v string)`

SetZip sets Zip field to given value.

### HasZip

`func (o *CustomersApiListCustomerAddressesItem) HasZip() bool`

HasZip returns a boolean if a field has been set.

### GetCountry

`func (o *CustomersApiListCustomerAddressesItem) GetCountry() string`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *CustomersApiListCustomerAddressesItem) GetCountryOk() (*string, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *CustomersApiListCustomerAddressesItem) SetCountry(v string)`

SetCountry sets Country field to given value.

### HasCountry

`func (o *CustomersApiListCustomerAddressesItem) HasCountry() bool`

HasCountry returns a boolean if a field has been set.

### GetRegion

`func (o *CustomersApiListCustomerAddressesItem) GetRegion() string`

GetRegion returns the Region field if non-nil, zero value otherwise.

### GetRegionOk

`func (o *CustomersApiListCustomerAddressesItem) GetRegionOk() (*string, bool)`

GetRegionOk returns a tuple with the Region field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegion

`func (o *CustomersApiListCustomerAddressesItem) SetRegion(v string)`

SetRegion sets Region field to given value.

### HasRegion

`func (o *CustomersApiListCustomerAddressesItem) HasRegion() bool`

HasRegion returns a boolean if a field has been set.

### GetCounty

`func (o *CustomersApiListCustomerAddressesItem) GetCounty() string`

GetCounty returns the County field if non-nil, zero value otherwise.

### GetCountyOk

`func (o *CustomersApiListCustomerAddressesItem) GetCountyOk() (*string, bool)`

GetCountyOk returns a tuple with the County field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCounty

`func (o *CustomersApiListCustomerAddressesItem) SetCounty(v string)`

SetCounty sets County field to given value.

### HasCounty

`func (o *CustomersApiListCustomerAddressesItem) HasCounty() bool`

HasCounty returns a boolean if a field has been set.

### GetShippingInstructions

`func (o *CustomersApiListCustomerAddressesItem) GetShippingInstructions() string`

GetShippingInstructions returns the ShippingInstructions field if non-nil, zero value otherwise.

### GetShippingInstructionsOk

`func (o *CustomersApiListCustomerAddressesItem) GetShippingInstructionsOk() (*string, bool)`

GetShippingInstructionsOk returns a tuple with the ShippingInstructions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingInstructions

`func (o *CustomersApiListCustomerAddressesItem) SetShippingInstructions(v string)`

SetShippingInstructions sets ShippingInstructions field to given value.

### HasShippingInstructions

`func (o *CustomersApiListCustomerAddressesItem) HasShippingInstructions() bool`

HasShippingInstructions returns a boolean if a field has been set.

### GetIgnoreTransitOnWeekends

`func (o *CustomersApiListCustomerAddressesItem) GetIgnoreTransitOnWeekends() bool`

GetIgnoreTransitOnWeekends returns the IgnoreTransitOnWeekends field if non-nil, zero value otherwise.

### GetIgnoreTransitOnWeekendsOk

`func (o *CustomersApiListCustomerAddressesItem) GetIgnoreTransitOnWeekendsOk() (*bool, bool)`

GetIgnoreTransitOnWeekendsOk returns a tuple with the IgnoreTransitOnWeekends field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIgnoreTransitOnWeekends

`func (o *CustomersApiListCustomerAddressesItem) SetIgnoreTransitOnWeekends(v bool)`

SetIgnoreTransitOnWeekends sets IgnoreTransitOnWeekends field to given value.

### HasIgnoreTransitOnWeekends

`func (o *CustomersApiListCustomerAddressesItem) HasIgnoreTransitOnWeekends() bool`

HasIgnoreTransitOnWeekends returns a boolean if a field has been set.

### GetTransportationLeadTime

`func (o *CustomersApiListCustomerAddressesItem) GetTransportationLeadTime() int32`

GetTransportationLeadTime returns the TransportationLeadTime field if non-nil, zero value otherwise.

### GetTransportationLeadTimeOk

`func (o *CustomersApiListCustomerAddressesItem) GetTransportationLeadTimeOk() (*int32, bool)`

GetTransportationLeadTimeOk returns a tuple with the TransportationLeadTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransportationLeadTime

`func (o *CustomersApiListCustomerAddressesItem) SetTransportationLeadTime(v int32)`

SetTransportationLeadTime sets TransportationLeadTime field to given value.

### HasTransportationLeadTime

`func (o *CustomersApiListCustomerAddressesItem) HasTransportationLeadTime() bool`

HasTransportationLeadTime returns a boolean if a field has been set.

### GetDefaultCarrierIds

`func (o *CustomersApiListCustomerAddressesItem) GetDefaultCarrierIds() []string`

GetDefaultCarrierIds returns the DefaultCarrierIds field if non-nil, zero value otherwise.

### GetDefaultCarrierIdsOk

`func (o *CustomersApiListCustomerAddressesItem) GetDefaultCarrierIdsOk() (*[]string, bool)`

GetDefaultCarrierIdsOk returns a tuple with the DefaultCarrierIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultCarrierIds

`func (o *CustomersApiListCustomerAddressesItem) SetDefaultCarrierIds(v []string)`

SetDefaultCarrierIds sets DefaultCarrierIds field to given value.

### HasDefaultCarrierIds

`func (o *CustomersApiListCustomerAddressesItem) HasDefaultCarrierIds() bool`

HasDefaultCarrierIds returns a boolean if a field has been set.

### GetTruckType

`func (o *CustomersApiListCustomerAddressesItem) GetTruckType() string`

GetTruckType returns the TruckType field if non-nil, zero value otherwise.

### GetTruckTypeOk

`func (o *CustomersApiListCustomerAddressesItem) GetTruckTypeOk() (*string, bool)`

GetTruckTypeOk returns a tuple with the TruckType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruckType

`func (o *CustomersApiListCustomerAddressesItem) SetTruckType(v string)`

SetTruckType sets TruckType field to given value.

### HasTruckType

`func (o *CustomersApiListCustomerAddressesItem) HasTruckType() bool`

HasTruckType returns a boolean if a field has been set.

### GetSalesTaxExempt

`func (o *CustomersApiListCustomerAddressesItem) GetSalesTaxExempt() bool`

GetSalesTaxExempt returns the SalesTaxExempt field if non-nil, zero value otherwise.

### GetSalesTaxExemptOk

`func (o *CustomersApiListCustomerAddressesItem) GetSalesTaxExemptOk() (*bool, bool)`

GetSalesTaxExemptOk returns a tuple with the SalesTaxExempt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSalesTaxExempt

`func (o *CustomersApiListCustomerAddressesItem) SetSalesTaxExempt(v bool)`

SetSalesTaxExempt sets SalesTaxExempt field to given value.

### HasSalesTaxExempt

`func (o *CustomersApiListCustomerAddressesItem) HasSalesTaxExempt() bool`

HasSalesTaxExempt returns a boolean if a field has been set.

### GetSalespersonId

`func (o *CustomersApiListCustomerAddressesItem) GetSalespersonId() string`

GetSalespersonId returns the SalespersonId field if non-nil, zero value otherwise.

### GetSalespersonIdOk

`func (o *CustomersApiListCustomerAddressesItem) GetSalespersonIdOk() (*string, bool)`

GetSalespersonIdOk returns a tuple with the SalespersonId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSalespersonId

`func (o *CustomersApiListCustomerAddressesItem) SetSalespersonId(v string)`

SetSalespersonId sets SalespersonId field to given value.

### HasSalespersonId

`func (o *CustomersApiListCustomerAddressesItem) HasSalespersonId() bool`

HasSalespersonId returns a boolean if a field has been set.

### GetStatementAddressId

`func (o *CustomersApiListCustomerAddressesItem) GetStatementAddressId() string`

GetStatementAddressId returns the StatementAddressId field if non-nil, zero value otherwise.

### GetStatementAddressIdOk

`func (o *CustomersApiListCustomerAddressesItem) GetStatementAddressIdOk() (*string, bool)`

GetStatementAddressIdOk returns a tuple with the StatementAddressId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatementAddressId

`func (o *CustomersApiListCustomerAddressesItem) SetStatementAddressId(v string)`

SetStatementAddressId sets StatementAddressId field to given value.

### HasStatementAddressId

`func (o *CustomersApiListCustomerAddressesItem) HasStatementAddressId() bool`

HasStatementAddressId returns a boolean if a field has been set.

### GetFreightTerms

`func (o *CustomersApiListCustomerAddressesItem) GetFreightTerms() string`

GetFreightTerms returns the FreightTerms field if non-nil, zero value otherwise.

### GetFreightTermsOk

`func (o *CustomersApiListCustomerAddressesItem) GetFreightTermsOk() (*string, bool)`

GetFreightTermsOk returns a tuple with the FreightTerms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFreightTerms

`func (o *CustomersApiListCustomerAddressesItem) SetFreightTerms(v string)`

SetFreightTerms sets FreightTerms field to given value.

### HasFreightTerms

`func (o *CustomersApiListCustomerAddressesItem) HasFreightTerms() bool`

HasFreightTerms returns a boolean if a field has been set.

### GetInsideSalespersonId

`func (o *CustomersApiListCustomerAddressesItem) GetInsideSalespersonId() string`

GetInsideSalespersonId returns the InsideSalespersonId field if non-nil, zero value otherwise.

### GetInsideSalespersonIdOk

`func (o *CustomersApiListCustomerAddressesItem) GetInsideSalespersonIdOk() (*string, bool)`

GetInsideSalespersonIdOk returns a tuple with the InsideSalespersonId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInsideSalespersonId

`func (o *CustomersApiListCustomerAddressesItem) SetInsideSalespersonId(v string)`

SetInsideSalespersonId sets InsideSalespersonId field to given value.

### HasInsideSalespersonId

`func (o *CustomersApiListCustomerAddressesItem) HasInsideSalespersonId() bool`

HasInsideSalespersonId returns a boolean if a field has been set.

### GetDefaultShipFrom

`func (o *CustomersApiListCustomerAddressesItem) GetDefaultShipFrom() string`

GetDefaultShipFrom returns the DefaultShipFrom field if non-nil, zero value otherwise.

### GetDefaultShipFromOk

`func (o *CustomersApiListCustomerAddressesItem) GetDefaultShipFromOk() (*string, bool)`

GetDefaultShipFromOk returns a tuple with the DefaultShipFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultShipFrom

`func (o *CustomersApiListCustomerAddressesItem) SetDefaultShipFrom(v string)`

SetDefaultShipFrom sets DefaultShipFrom field to given value.

### HasDefaultShipFrom

`func (o *CustomersApiListCustomerAddressesItem) HasDefaultShipFrom() bool`

HasDefaultShipFrom returns a boolean if a field has been set.

### GetFreightBillTo

`func (o *CustomersApiListCustomerAddressesItem) GetFreightBillTo() bool`

GetFreightBillTo returns the FreightBillTo field if non-nil, zero value otherwise.

### GetFreightBillToOk

`func (o *CustomersApiListCustomerAddressesItem) GetFreightBillToOk() (*bool, bool)`

GetFreightBillToOk returns a tuple with the FreightBillTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFreightBillTo

`func (o *CustomersApiListCustomerAddressesItem) SetFreightBillTo(v bool)`

SetFreightBillTo sets FreightBillTo field to given value.

### HasFreightBillTo

`func (o *CustomersApiListCustomerAddressesItem) HasFreightBillTo() bool`

HasFreightBillTo returns a boolean if a field has been set.

### GetFreightBillToAddressId

`func (o *CustomersApiListCustomerAddressesItem) GetFreightBillToAddressId() string`

GetFreightBillToAddressId returns the FreightBillToAddressId field if non-nil, zero value otherwise.

### GetFreightBillToAddressIdOk

`func (o *CustomersApiListCustomerAddressesItem) GetFreightBillToAddressIdOk() (*string, bool)`

GetFreightBillToAddressIdOk returns a tuple with the FreightBillToAddressId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFreightBillToAddressId

`func (o *CustomersApiListCustomerAddressesItem) SetFreightBillToAddressId(v string)`

SetFreightBillToAddressId sets FreightBillToAddressId field to given value.

### HasFreightBillToAddressId

`func (o *CustomersApiListCustomerAddressesItem) HasFreightBillToAddressId() bool`

HasFreightBillToAddressId returns a boolean if a field has been set.

### GetCatalog

`func (o *CustomersApiListCustomerAddressesItem) GetCatalog() string`

GetCatalog returns the Catalog field if non-nil, zero value otherwise.

### GetCatalogOk

`func (o *CustomersApiListCustomerAddressesItem) GetCatalogOk() (*string, bool)`

GetCatalogOk returns a tuple with the Catalog field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCatalog

`func (o *CustomersApiListCustomerAddressesItem) SetCatalog(v string)`

SetCatalog sets Catalog field to given value.

### HasCatalog

`func (o *CustomersApiListCustomerAddressesItem) HasCatalog() bool`

HasCatalog returns a boolean if a field has been set.

### GetSoldTo

`func (o *CustomersApiListCustomerAddressesItem) GetSoldTo() bool`

GetSoldTo returns the SoldTo field if non-nil, zero value otherwise.

### GetSoldToOk

`func (o *CustomersApiListCustomerAddressesItem) GetSoldToOk() (*bool, bool)`

GetSoldToOk returns a tuple with the SoldTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSoldTo

`func (o *CustomersApiListCustomerAddressesItem) SetSoldTo(v bool)`

SetSoldTo sets SoldTo field to given value.

### HasSoldTo

`func (o *CustomersApiListCustomerAddressesItem) HasSoldTo() bool`

HasSoldTo returns a boolean if a field has been set.

### GetDunsNo

`func (o *CustomersApiListCustomerAddressesItem) GetDunsNo() string`

GetDunsNo returns the DunsNo field if non-nil, zero value otherwise.

### GetDunsNoOk

`func (o *CustomersApiListCustomerAddressesItem) GetDunsNoOk() (*string, bool)`

GetDunsNoOk returns a tuple with the DunsNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDunsNo

`func (o *CustomersApiListCustomerAddressesItem) SetDunsNo(v string)`

SetDunsNo sets DunsNo field to given value.

### HasDunsNo

`func (o *CustomersApiListCustomerAddressesItem) HasDunsNo() bool`

HasDunsNo returns a boolean if a field has been set.

### GetCommercialInvoiceVatNo

`func (o *CustomersApiListCustomerAddressesItem) GetCommercialInvoiceVatNo() string`

GetCommercialInvoiceVatNo returns the CommercialInvoiceVatNo field if non-nil, zero value otherwise.

### GetCommercialInvoiceVatNoOk

`func (o *CustomersApiListCustomerAddressesItem) GetCommercialInvoiceVatNoOk() (*string, bool)`

GetCommercialInvoiceVatNoOk returns a tuple with the CommercialInvoiceVatNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCommercialInvoiceVatNo

`func (o *CustomersApiListCustomerAddressesItem) SetCommercialInvoiceVatNo(v string)`

SetCommercialInvoiceVatNo sets CommercialInvoiceVatNo field to given value.

### HasCommercialInvoiceVatNo

`func (o *CustomersApiListCustomerAddressesItem) HasCommercialInvoiceVatNo() bool`

HasCommercialInvoiceVatNo returns a boolean if a field has been set.

### GetTerms

`func (o *CustomersApiListCustomerAddressesItem) GetTerms() string`

GetTerms returns the Terms field if non-nil, zero value otherwise.

### GetTermsOk

`func (o *CustomersApiListCustomerAddressesItem) GetTermsOk() (*string, bool)`

GetTermsOk returns a tuple with the Terms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTerms

`func (o *CustomersApiListCustomerAddressesItem) SetTerms(v string)`

SetTerms sets Terms field to given value.

### HasTerms

`func (o *CustomersApiListCustomerAddressesItem) HasTerms() bool`

HasTerms returns a boolean if a field has been set.

### GetTemplate

`func (o *CustomersApiListCustomerAddressesItem) GetTemplate() bool`

GetTemplate returns the Template field if non-nil, zero value otherwise.

### GetTemplateOk

`func (o *CustomersApiListCustomerAddressesItem) GetTemplateOk() (*bool, bool)`

GetTemplateOk returns a tuple with the Template field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemplate

`func (o *CustomersApiListCustomerAddressesItem) SetTemplate(v bool)`

SetTemplate sets Template field to given value.

### HasTemplate

`func (o *CustomersApiListCustomerAddressesItem) HasTemplate() bool`

HasTemplate returns a boolean if a field has been set.

### GetIncoTerms

`func (o *CustomersApiListCustomerAddressesItem) GetIncoTerms() string`

GetIncoTerms returns the IncoTerms field if non-nil, zero value otherwise.

### GetIncoTermsOk

`func (o *CustomersApiListCustomerAddressesItem) GetIncoTermsOk() (*string, bool)`

GetIncoTermsOk returns a tuple with the IncoTerms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncoTerms

`func (o *CustomersApiListCustomerAddressesItem) SetIncoTerms(v string)`

SetIncoTerms sets IncoTerms field to given value.

### HasIncoTerms

`func (o *CustomersApiListCustomerAddressesItem) HasIncoTerms() bool`

HasIncoTerms returns a boolean if a field has been set.

### GetNegotiatedPlace

`func (o *CustomersApiListCustomerAddressesItem) GetNegotiatedPlace() string`

GetNegotiatedPlace returns the NegotiatedPlace field if non-nil, zero value otherwise.

### GetNegotiatedPlaceOk

`func (o *CustomersApiListCustomerAddressesItem) GetNegotiatedPlaceOk() (*string, bool)`

GetNegotiatedPlaceOk returns a tuple with the NegotiatedPlace field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNegotiatedPlace

`func (o *CustomersApiListCustomerAddressesItem) SetNegotiatedPlace(v string)`

SetNegotiatedPlace sets NegotiatedPlace field to given value.

### HasNegotiatedPlace

`func (o *CustomersApiListCustomerAddressesItem) HasNegotiatedPlace() bool`

HasNegotiatedPlace returns a boolean if a field has been set.

### GetBackOrder

`func (o *CustomersApiListCustomerAddressesItem) GetBackOrder() string`

GetBackOrder returns the BackOrder field if non-nil, zero value otherwise.

### GetBackOrderOk

`func (o *CustomersApiListCustomerAddressesItem) GetBackOrderOk() (*string, bool)`

GetBackOrderOk returns a tuple with the BackOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBackOrder

`func (o *CustomersApiListCustomerAddressesItem) SetBackOrder(v string)`

SetBackOrder sets BackOrder field to given value.

### HasBackOrder

`func (o *CustomersApiListCustomerAddressesItem) HasBackOrder() bool`

HasBackOrder returns a boolean if a field has been set.

### GetCreatedById

`func (o *CustomersApiListCustomerAddressesItem) GetCreatedById() string`

GetCreatedById returns the CreatedById field if non-nil, zero value otherwise.

### GetCreatedByIdOk

`func (o *CustomersApiListCustomerAddressesItem) GetCreatedByIdOk() (*string, bool)`

GetCreatedByIdOk returns a tuple with the CreatedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedById

`func (o *CustomersApiListCustomerAddressesItem) SetCreatedById(v string)`

SetCreatedById sets CreatedById field to given value.

### HasCreatedById

`func (o *CustomersApiListCustomerAddressesItem) HasCreatedById() bool`

HasCreatedById returns a boolean if a field has been set.

### GetCreatedDate

`func (o *CustomersApiListCustomerAddressesItem) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *CustomersApiListCustomerAddressesItem) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *CustomersApiListCustomerAddressesItem) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *CustomersApiListCustomerAddressesItem) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.

### GetModifiedById

`func (o *CustomersApiListCustomerAddressesItem) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *CustomersApiListCustomerAddressesItem) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *CustomersApiListCustomerAddressesItem) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *CustomersApiListCustomerAddressesItem) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetModifiedDate

`func (o *CustomersApiListCustomerAddressesItem) GetModifiedDate() time.Time`

GetModifiedDate returns the ModifiedDate field if non-nil, zero value otherwise.

### GetModifiedDateOk

`func (o *CustomersApiListCustomerAddressesItem) GetModifiedDateOk() (*time.Time, bool)`

GetModifiedDateOk returns a tuple with the ModifiedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDate

`func (o *CustomersApiListCustomerAddressesItem) SetModifiedDate(v time.Time)`

SetModifiedDate sets ModifiedDate field to given value.

### HasModifiedDate

`func (o *CustomersApiListCustomerAddressesItem) HasModifiedDate() bool`

HasModifiedDate returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


