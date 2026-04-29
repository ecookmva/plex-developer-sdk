# EdiApiGetMailboxResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | A unique identifier for the Mailbox. | [optional] 
**CreatedDate** | Pointer to **time.Time** | The date on which the mailbox was created. | [optional] 
**CreatedById** | Pointer to **string** | The IAM Account ID of the user who created the mailbox. | [optional] 
**ModifiedById** | Pointer to **string** | The IAM Account ID of the user who last modified the mailbox. | [optional] 
**ModifiedDate** | Pointer to **time.Time** | The date on which the mailbox was last modified. | [optional] 
**Code** | Pointer to **string** | The Mailbox Code of the EDI Mailbox, which identifies the user of the Mailbox. | [optional] 
**SupplierId** | Pointer to **string** | The ID of the Supplier. | [optional] 
**CustomerId** | Pointer to **string** | The ID of the Customer. | [optional] 
**ShipFromBuildingId** | Pointer to **string** | The ID of the building from which the order will ship. | [optional] 
**Note** | Pointer to **string** | EDI Mailbox Note. | [optional] 
**Status** | Pointer to **string** | EDI Mailbox Status. | [optional] 
**Name** | Pointer to **string** | EDI Mailbox Name. Must be a unique value. | [optional] 
**Qualifier** | Pointer to **string** | Indicates the type of data for the Mailbox Code value. Typically a two-character value. For example, 01 would be a DUNS Number. | [optional] 
**Use** | Pointer to **string** | Indicates how the Mailbox will be used, such as Send or Send/Receive. | [optional] 
**OriginCode** | Pointer to **string** | The User Code mapped to outbound documents. | [optional] 
**VendorCode** | Pointer to **string** | The Vendor Code mapped to outbound documents. | [optional] 
**DestinationQualifier** | Pointer to **string** | Indicates the type of data for the Destination Mailbox value. Typically a two-character value. For example, 01 would be a DUNS Number. | [optional] 
**DestinationMailbox** | Pointer to **string** | The Destination value of the EDI Mailbox, which is the identifier of the trading partner associated to the mailbox. | [optional] 
**DestinationCode** | Pointer to **string** | A Code used to identify the recipient at a trading partner, such as a specific DUNS Number. | [optional] 
**ElementSeparator** | Pointer to **string** | Single character code used to parse data. This separates each element of a segment. | [optional] 
**SubelementSeparator** | Pointer to **string** | Single character code used to parse data within an element. | [optional] 
**SegmentTerminator** | Pointer to **int32** | The ASCII value used to end segments. | [optional] 
**TransmissionCount** | Pointer to **int32** | A counter to track document creation. | [optional] 
**Isa01** | Pointer to **string** | First element of the ISA segment. | [optional] 
**Isa02** | Pointer to **string** | Second element of the ISA segment. | [optional] 
**Isa03** | Pointer to **string** | Third element of the ISA segment. | [optional] 
**Isa04** | Pointer to **string** | Fourth element of the ISA segment. | [optional] 
**ActualProcessorDuns** | Pointer to **string** | DUNS number used for outbound documents. | [optional] 
**ShipFromCode** | Pointer to **string** | Identifies the location for the shipment. | [optional] 
**SecondaryPlantCode** | Pointer to **string** | Secondary plant code. | [optional] 
**OverrideUnitOfMeasureCode** | Pointer to **string** | Use to override and specify the unit of measure for use on Outbound documents. | [optional] 
**Active** | Pointer to **bool** | Indicates whether the mailbox is active. | [optional] 
**TradingPartnerName** | Pointer to **string** | Trading Partner Name. | [optional] 

## Methods

### NewEdiApiGetMailboxResponse

`func NewEdiApiGetMailboxResponse() *EdiApiGetMailboxResponse`

NewEdiApiGetMailboxResponse instantiates a new EdiApiGetMailboxResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEdiApiGetMailboxResponseWithDefaults

`func NewEdiApiGetMailboxResponseWithDefaults() *EdiApiGetMailboxResponse`

NewEdiApiGetMailboxResponseWithDefaults instantiates a new EdiApiGetMailboxResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *EdiApiGetMailboxResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *EdiApiGetMailboxResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *EdiApiGetMailboxResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *EdiApiGetMailboxResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCreatedDate

`func (o *EdiApiGetMailboxResponse) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *EdiApiGetMailboxResponse) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *EdiApiGetMailboxResponse) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *EdiApiGetMailboxResponse) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.

### GetCreatedById

`func (o *EdiApiGetMailboxResponse) GetCreatedById() string`

GetCreatedById returns the CreatedById field if non-nil, zero value otherwise.

### GetCreatedByIdOk

`func (o *EdiApiGetMailboxResponse) GetCreatedByIdOk() (*string, bool)`

GetCreatedByIdOk returns a tuple with the CreatedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedById

`func (o *EdiApiGetMailboxResponse) SetCreatedById(v string)`

SetCreatedById sets CreatedById field to given value.

### HasCreatedById

`func (o *EdiApiGetMailboxResponse) HasCreatedById() bool`

HasCreatedById returns a boolean if a field has been set.

### GetModifiedById

`func (o *EdiApiGetMailboxResponse) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *EdiApiGetMailboxResponse) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *EdiApiGetMailboxResponse) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *EdiApiGetMailboxResponse) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetModifiedDate

`func (o *EdiApiGetMailboxResponse) GetModifiedDate() time.Time`

GetModifiedDate returns the ModifiedDate field if non-nil, zero value otherwise.

### GetModifiedDateOk

`func (o *EdiApiGetMailboxResponse) GetModifiedDateOk() (*time.Time, bool)`

GetModifiedDateOk returns a tuple with the ModifiedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDate

`func (o *EdiApiGetMailboxResponse) SetModifiedDate(v time.Time)`

SetModifiedDate sets ModifiedDate field to given value.

### HasModifiedDate

`func (o *EdiApiGetMailboxResponse) HasModifiedDate() bool`

HasModifiedDate returns a boolean if a field has been set.

### GetCode

`func (o *EdiApiGetMailboxResponse) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *EdiApiGetMailboxResponse) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *EdiApiGetMailboxResponse) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *EdiApiGetMailboxResponse) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetSupplierId

`func (o *EdiApiGetMailboxResponse) GetSupplierId() string`

GetSupplierId returns the SupplierId field if non-nil, zero value otherwise.

### GetSupplierIdOk

`func (o *EdiApiGetMailboxResponse) GetSupplierIdOk() (*string, bool)`

GetSupplierIdOk returns a tuple with the SupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierId

`func (o *EdiApiGetMailboxResponse) SetSupplierId(v string)`

SetSupplierId sets SupplierId field to given value.

### HasSupplierId

`func (o *EdiApiGetMailboxResponse) HasSupplierId() bool`

HasSupplierId returns a boolean if a field has been set.

### GetCustomerId

`func (o *EdiApiGetMailboxResponse) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *EdiApiGetMailboxResponse) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *EdiApiGetMailboxResponse) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *EdiApiGetMailboxResponse) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### GetShipFromBuildingId

`func (o *EdiApiGetMailboxResponse) GetShipFromBuildingId() string`

GetShipFromBuildingId returns the ShipFromBuildingId field if non-nil, zero value otherwise.

### GetShipFromBuildingIdOk

`func (o *EdiApiGetMailboxResponse) GetShipFromBuildingIdOk() (*string, bool)`

GetShipFromBuildingIdOk returns a tuple with the ShipFromBuildingId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipFromBuildingId

`func (o *EdiApiGetMailboxResponse) SetShipFromBuildingId(v string)`

SetShipFromBuildingId sets ShipFromBuildingId field to given value.

### HasShipFromBuildingId

`func (o *EdiApiGetMailboxResponse) HasShipFromBuildingId() bool`

HasShipFromBuildingId returns a boolean if a field has been set.

### GetNote

`func (o *EdiApiGetMailboxResponse) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *EdiApiGetMailboxResponse) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *EdiApiGetMailboxResponse) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *EdiApiGetMailboxResponse) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetStatus

`func (o *EdiApiGetMailboxResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *EdiApiGetMailboxResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *EdiApiGetMailboxResponse) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *EdiApiGetMailboxResponse) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetName

`func (o *EdiApiGetMailboxResponse) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *EdiApiGetMailboxResponse) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *EdiApiGetMailboxResponse) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *EdiApiGetMailboxResponse) HasName() bool`

HasName returns a boolean if a field has been set.

### GetQualifier

`func (o *EdiApiGetMailboxResponse) GetQualifier() string`

GetQualifier returns the Qualifier field if non-nil, zero value otherwise.

### GetQualifierOk

`func (o *EdiApiGetMailboxResponse) GetQualifierOk() (*string, bool)`

GetQualifierOk returns a tuple with the Qualifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQualifier

`func (o *EdiApiGetMailboxResponse) SetQualifier(v string)`

SetQualifier sets Qualifier field to given value.

### HasQualifier

`func (o *EdiApiGetMailboxResponse) HasQualifier() bool`

HasQualifier returns a boolean if a field has been set.

### GetUse

`func (o *EdiApiGetMailboxResponse) GetUse() string`

GetUse returns the Use field if non-nil, zero value otherwise.

### GetUseOk

`func (o *EdiApiGetMailboxResponse) GetUseOk() (*string, bool)`

GetUseOk returns a tuple with the Use field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUse

`func (o *EdiApiGetMailboxResponse) SetUse(v string)`

SetUse sets Use field to given value.

### HasUse

`func (o *EdiApiGetMailboxResponse) HasUse() bool`

HasUse returns a boolean if a field has been set.

### GetOriginCode

`func (o *EdiApiGetMailboxResponse) GetOriginCode() string`

GetOriginCode returns the OriginCode field if non-nil, zero value otherwise.

### GetOriginCodeOk

`func (o *EdiApiGetMailboxResponse) GetOriginCodeOk() (*string, bool)`

GetOriginCodeOk returns a tuple with the OriginCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginCode

`func (o *EdiApiGetMailboxResponse) SetOriginCode(v string)`

SetOriginCode sets OriginCode field to given value.

### HasOriginCode

`func (o *EdiApiGetMailboxResponse) HasOriginCode() bool`

HasOriginCode returns a boolean if a field has been set.

### GetVendorCode

`func (o *EdiApiGetMailboxResponse) GetVendorCode() string`

GetVendorCode returns the VendorCode field if non-nil, zero value otherwise.

### GetVendorCodeOk

`func (o *EdiApiGetMailboxResponse) GetVendorCodeOk() (*string, bool)`

GetVendorCodeOk returns a tuple with the VendorCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVendorCode

`func (o *EdiApiGetMailboxResponse) SetVendorCode(v string)`

SetVendorCode sets VendorCode field to given value.

### HasVendorCode

`func (o *EdiApiGetMailboxResponse) HasVendorCode() bool`

HasVendorCode returns a boolean if a field has been set.

### GetDestinationQualifier

`func (o *EdiApiGetMailboxResponse) GetDestinationQualifier() string`

GetDestinationQualifier returns the DestinationQualifier field if non-nil, zero value otherwise.

### GetDestinationQualifierOk

`func (o *EdiApiGetMailboxResponse) GetDestinationQualifierOk() (*string, bool)`

GetDestinationQualifierOk returns a tuple with the DestinationQualifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestinationQualifier

`func (o *EdiApiGetMailboxResponse) SetDestinationQualifier(v string)`

SetDestinationQualifier sets DestinationQualifier field to given value.

### HasDestinationQualifier

`func (o *EdiApiGetMailboxResponse) HasDestinationQualifier() bool`

HasDestinationQualifier returns a boolean if a field has been set.

### GetDestinationMailbox

`func (o *EdiApiGetMailboxResponse) GetDestinationMailbox() string`

GetDestinationMailbox returns the DestinationMailbox field if non-nil, zero value otherwise.

### GetDestinationMailboxOk

`func (o *EdiApiGetMailboxResponse) GetDestinationMailboxOk() (*string, bool)`

GetDestinationMailboxOk returns a tuple with the DestinationMailbox field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestinationMailbox

`func (o *EdiApiGetMailboxResponse) SetDestinationMailbox(v string)`

SetDestinationMailbox sets DestinationMailbox field to given value.

### HasDestinationMailbox

`func (o *EdiApiGetMailboxResponse) HasDestinationMailbox() bool`

HasDestinationMailbox returns a boolean if a field has been set.

### GetDestinationCode

`func (o *EdiApiGetMailboxResponse) GetDestinationCode() string`

GetDestinationCode returns the DestinationCode field if non-nil, zero value otherwise.

### GetDestinationCodeOk

`func (o *EdiApiGetMailboxResponse) GetDestinationCodeOk() (*string, bool)`

GetDestinationCodeOk returns a tuple with the DestinationCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestinationCode

`func (o *EdiApiGetMailboxResponse) SetDestinationCode(v string)`

SetDestinationCode sets DestinationCode field to given value.

### HasDestinationCode

`func (o *EdiApiGetMailboxResponse) HasDestinationCode() bool`

HasDestinationCode returns a boolean if a field has been set.

### GetElementSeparator

`func (o *EdiApiGetMailboxResponse) GetElementSeparator() string`

GetElementSeparator returns the ElementSeparator field if non-nil, zero value otherwise.

### GetElementSeparatorOk

`func (o *EdiApiGetMailboxResponse) GetElementSeparatorOk() (*string, bool)`

GetElementSeparatorOk returns a tuple with the ElementSeparator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetElementSeparator

`func (o *EdiApiGetMailboxResponse) SetElementSeparator(v string)`

SetElementSeparator sets ElementSeparator field to given value.

### HasElementSeparator

`func (o *EdiApiGetMailboxResponse) HasElementSeparator() bool`

HasElementSeparator returns a boolean if a field has been set.

### GetSubelementSeparator

`func (o *EdiApiGetMailboxResponse) GetSubelementSeparator() string`

GetSubelementSeparator returns the SubelementSeparator field if non-nil, zero value otherwise.

### GetSubelementSeparatorOk

`func (o *EdiApiGetMailboxResponse) GetSubelementSeparatorOk() (*string, bool)`

GetSubelementSeparatorOk returns a tuple with the SubelementSeparator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubelementSeparator

`func (o *EdiApiGetMailboxResponse) SetSubelementSeparator(v string)`

SetSubelementSeparator sets SubelementSeparator field to given value.

### HasSubelementSeparator

`func (o *EdiApiGetMailboxResponse) HasSubelementSeparator() bool`

HasSubelementSeparator returns a boolean if a field has been set.

### GetSegmentTerminator

`func (o *EdiApiGetMailboxResponse) GetSegmentTerminator() int32`

GetSegmentTerminator returns the SegmentTerminator field if non-nil, zero value otherwise.

### GetSegmentTerminatorOk

`func (o *EdiApiGetMailboxResponse) GetSegmentTerminatorOk() (*int32, bool)`

GetSegmentTerminatorOk returns a tuple with the SegmentTerminator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSegmentTerminator

`func (o *EdiApiGetMailboxResponse) SetSegmentTerminator(v int32)`

SetSegmentTerminator sets SegmentTerminator field to given value.

### HasSegmentTerminator

`func (o *EdiApiGetMailboxResponse) HasSegmentTerminator() bool`

HasSegmentTerminator returns a boolean if a field has been set.

### GetTransmissionCount

`func (o *EdiApiGetMailboxResponse) GetTransmissionCount() int32`

GetTransmissionCount returns the TransmissionCount field if non-nil, zero value otherwise.

### GetTransmissionCountOk

`func (o *EdiApiGetMailboxResponse) GetTransmissionCountOk() (*int32, bool)`

GetTransmissionCountOk returns a tuple with the TransmissionCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransmissionCount

`func (o *EdiApiGetMailboxResponse) SetTransmissionCount(v int32)`

SetTransmissionCount sets TransmissionCount field to given value.

### HasTransmissionCount

`func (o *EdiApiGetMailboxResponse) HasTransmissionCount() bool`

HasTransmissionCount returns a boolean if a field has been set.

### GetIsa01

`func (o *EdiApiGetMailboxResponse) GetIsa01() string`

GetIsa01 returns the Isa01 field if non-nil, zero value otherwise.

### GetIsa01Ok

`func (o *EdiApiGetMailboxResponse) GetIsa01Ok() (*string, bool)`

GetIsa01Ok returns a tuple with the Isa01 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsa01

`func (o *EdiApiGetMailboxResponse) SetIsa01(v string)`

SetIsa01 sets Isa01 field to given value.

### HasIsa01

`func (o *EdiApiGetMailboxResponse) HasIsa01() bool`

HasIsa01 returns a boolean if a field has been set.

### GetIsa02

`func (o *EdiApiGetMailboxResponse) GetIsa02() string`

GetIsa02 returns the Isa02 field if non-nil, zero value otherwise.

### GetIsa02Ok

`func (o *EdiApiGetMailboxResponse) GetIsa02Ok() (*string, bool)`

GetIsa02Ok returns a tuple with the Isa02 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsa02

`func (o *EdiApiGetMailboxResponse) SetIsa02(v string)`

SetIsa02 sets Isa02 field to given value.

### HasIsa02

`func (o *EdiApiGetMailboxResponse) HasIsa02() bool`

HasIsa02 returns a boolean if a field has been set.

### GetIsa03

`func (o *EdiApiGetMailboxResponse) GetIsa03() string`

GetIsa03 returns the Isa03 field if non-nil, zero value otherwise.

### GetIsa03Ok

`func (o *EdiApiGetMailboxResponse) GetIsa03Ok() (*string, bool)`

GetIsa03Ok returns a tuple with the Isa03 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsa03

`func (o *EdiApiGetMailboxResponse) SetIsa03(v string)`

SetIsa03 sets Isa03 field to given value.

### HasIsa03

`func (o *EdiApiGetMailboxResponse) HasIsa03() bool`

HasIsa03 returns a boolean if a field has been set.

### GetIsa04

`func (o *EdiApiGetMailboxResponse) GetIsa04() string`

GetIsa04 returns the Isa04 field if non-nil, zero value otherwise.

### GetIsa04Ok

`func (o *EdiApiGetMailboxResponse) GetIsa04Ok() (*string, bool)`

GetIsa04Ok returns a tuple with the Isa04 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsa04

`func (o *EdiApiGetMailboxResponse) SetIsa04(v string)`

SetIsa04 sets Isa04 field to given value.

### HasIsa04

`func (o *EdiApiGetMailboxResponse) HasIsa04() bool`

HasIsa04 returns a boolean if a field has been set.

### GetActualProcessorDuns

`func (o *EdiApiGetMailboxResponse) GetActualProcessorDuns() string`

GetActualProcessorDuns returns the ActualProcessorDuns field if non-nil, zero value otherwise.

### GetActualProcessorDunsOk

`func (o *EdiApiGetMailboxResponse) GetActualProcessorDunsOk() (*string, bool)`

GetActualProcessorDunsOk returns a tuple with the ActualProcessorDuns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActualProcessorDuns

`func (o *EdiApiGetMailboxResponse) SetActualProcessorDuns(v string)`

SetActualProcessorDuns sets ActualProcessorDuns field to given value.

### HasActualProcessorDuns

`func (o *EdiApiGetMailboxResponse) HasActualProcessorDuns() bool`

HasActualProcessorDuns returns a boolean if a field has been set.

### GetShipFromCode

`func (o *EdiApiGetMailboxResponse) GetShipFromCode() string`

GetShipFromCode returns the ShipFromCode field if non-nil, zero value otherwise.

### GetShipFromCodeOk

`func (o *EdiApiGetMailboxResponse) GetShipFromCodeOk() (*string, bool)`

GetShipFromCodeOk returns a tuple with the ShipFromCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipFromCode

`func (o *EdiApiGetMailboxResponse) SetShipFromCode(v string)`

SetShipFromCode sets ShipFromCode field to given value.

### HasShipFromCode

`func (o *EdiApiGetMailboxResponse) HasShipFromCode() bool`

HasShipFromCode returns a boolean if a field has been set.

### GetSecondaryPlantCode

`func (o *EdiApiGetMailboxResponse) GetSecondaryPlantCode() string`

GetSecondaryPlantCode returns the SecondaryPlantCode field if non-nil, zero value otherwise.

### GetSecondaryPlantCodeOk

`func (o *EdiApiGetMailboxResponse) GetSecondaryPlantCodeOk() (*string, bool)`

GetSecondaryPlantCodeOk returns a tuple with the SecondaryPlantCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecondaryPlantCode

`func (o *EdiApiGetMailboxResponse) SetSecondaryPlantCode(v string)`

SetSecondaryPlantCode sets SecondaryPlantCode field to given value.

### HasSecondaryPlantCode

`func (o *EdiApiGetMailboxResponse) HasSecondaryPlantCode() bool`

HasSecondaryPlantCode returns a boolean if a field has been set.

### GetOverrideUnitOfMeasureCode

`func (o *EdiApiGetMailboxResponse) GetOverrideUnitOfMeasureCode() string`

GetOverrideUnitOfMeasureCode returns the OverrideUnitOfMeasureCode field if non-nil, zero value otherwise.

### GetOverrideUnitOfMeasureCodeOk

`func (o *EdiApiGetMailboxResponse) GetOverrideUnitOfMeasureCodeOk() (*string, bool)`

GetOverrideUnitOfMeasureCodeOk returns a tuple with the OverrideUnitOfMeasureCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOverrideUnitOfMeasureCode

`func (o *EdiApiGetMailboxResponse) SetOverrideUnitOfMeasureCode(v string)`

SetOverrideUnitOfMeasureCode sets OverrideUnitOfMeasureCode field to given value.

### HasOverrideUnitOfMeasureCode

`func (o *EdiApiGetMailboxResponse) HasOverrideUnitOfMeasureCode() bool`

HasOverrideUnitOfMeasureCode returns a boolean if a field has been set.

### GetActive

`func (o *EdiApiGetMailboxResponse) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *EdiApiGetMailboxResponse) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *EdiApiGetMailboxResponse) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *EdiApiGetMailboxResponse) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetTradingPartnerName

`func (o *EdiApiGetMailboxResponse) GetTradingPartnerName() string`

GetTradingPartnerName returns the TradingPartnerName field if non-nil, zero value otherwise.

### GetTradingPartnerNameOk

`func (o *EdiApiGetMailboxResponse) GetTradingPartnerNameOk() (*string, bool)`

GetTradingPartnerNameOk returns a tuple with the TradingPartnerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTradingPartnerName

`func (o *EdiApiGetMailboxResponse) SetTradingPartnerName(v string)`

SetTradingPartnerName sets TradingPartnerName field to given value.

### HasTradingPartnerName

`func (o *EdiApiGetMailboxResponse) HasTradingPartnerName() bool`

HasTradingPartnerName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


