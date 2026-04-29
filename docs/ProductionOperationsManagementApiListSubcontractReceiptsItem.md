# ProductionOperationsManagementApiListSubcontractReceiptsItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SupplierCode** | Pointer to **string** | 25 character max. The supplier code. | [optional] 
**SupplierId** | Pointer to **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. The supplier resource ID. | [optional] 
**SupplierShipperNo** | Pointer to **string** | 50 characters max. The supplier shipper number. | [optional] 
**ReceiptDate** | Pointer to **time.Time** | Date/Time Format YYYY-MM-DDThh:mm:ss.fffffffZ The date and time when the receipt was recorded. See &amp;quot;Dates and Times&amp;quot; in the Get Started section of the Plex Developer Portal (APIs &amp;gt; Get Started). | [optional] 
**PartId** | Pointer to **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. The part resource ID. | [optional] 
**PartNumber** | Pointer to **string** |  | [optional] 
**Revision** | Pointer to **string** | 8 characters max. The part revision. A revision level represents a change or modification to a part or part drawing that is usually initiated through an engineering change request (ECR). | [optional] 
**PartNumberRevision** | Pointer to **string** | Format {partNumber}{part rev separator}{revision}. The part number revision formatted with separator. If a part number has a revision, Plex will return the part number and the revision separated by the Part Rev Separator setting. A Part Rev Separator can be up to 5 characters long. | [optional] 
**PartOperationId** | Pointer to **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. The part operation resource ID. | [optional] 
**OperationCode** | Pointer to **string** | 10 characters max. The operation code. | [optional] 
**OperationNumber** | Pointer to **int32** | 30 characters max. The operation number (sequence order). | [optional] 
**SerialNo** | Pointer to **string** | 25 characters max. The serial number of the container that was received. | [optional] 
**LotNo** | Pointer to **string** | 25 characters max. The lot number of the container that was received. | [optional] 
**LotId** | Pointer to **string** | UUID V4 format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. The lot resource ID. | [optional] 
**TrackingNo** | Pointer to **string** | 50 characters max. The container&#39;s Tracking Number. | [optional] 
**HeatCode** | Pointer to **string** | 50 characters max. The heat receipt&#39;s heat code. | [optional] 
**HeatNo** | Pointer to **string** | 30 characters max. The short code or number identifying a heat. | [optional] 
**ReceivedQuantity** | Pointer to **float64** | Decimal, (19,5) max characters. The quantity recieved. | [optional] 
**ReceiptNote** | Pointer to **string** | 500 charcaters max. Receipt notes. | [optional] 

## Methods

### NewProductionOperationsManagementApiListSubcontractReceiptsItem

`func NewProductionOperationsManagementApiListSubcontractReceiptsItem() *ProductionOperationsManagementApiListSubcontractReceiptsItem`

NewProductionOperationsManagementApiListSubcontractReceiptsItem instantiates a new ProductionOperationsManagementApiListSubcontractReceiptsItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductionOperationsManagementApiListSubcontractReceiptsItemWithDefaults

`func NewProductionOperationsManagementApiListSubcontractReceiptsItemWithDefaults() *ProductionOperationsManagementApiListSubcontractReceiptsItem`

NewProductionOperationsManagementApiListSubcontractReceiptsItemWithDefaults instantiates a new ProductionOperationsManagementApiListSubcontractReceiptsItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSupplierCode

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) GetSupplierCode() string`

GetSupplierCode returns the SupplierCode field if non-nil, zero value otherwise.

### GetSupplierCodeOk

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) GetSupplierCodeOk() (*string, bool)`

GetSupplierCodeOk returns a tuple with the SupplierCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierCode

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) SetSupplierCode(v string)`

SetSupplierCode sets SupplierCode field to given value.

### HasSupplierCode

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) HasSupplierCode() bool`

HasSupplierCode returns a boolean if a field has been set.

### GetSupplierId

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) GetSupplierId() string`

GetSupplierId returns the SupplierId field if non-nil, zero value otherwise.

### GetSupplierIdOk

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) GetSupplierIdOk() (*string, bool)`

GetSupplierIdOk returns a tuple with the SupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierId

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) SetSupplierId(v string)`

SetSupplierId sets SupplierId field to given value.

### HasSupplierId

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) HasSupplierId() bool`

HasSupplierId returns a boolean if a field has been set.

### GetSupplierShipperNo

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) GetSupplierShipperNo() string`

GetSupplierShipperNo returns the SupplierShipperNo field if non-nil, zero value otherwise.

### GetSupplierShipperNoOk

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) GetSupplierShipperNoOk() (*string, bool)`

GetSupplierShipperNoOk returns a tuple with the SupplierShipperNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierShipperNo

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) SetSupplierShipperNo(v string)`

SetSupplierShipperNo sets SupplierShipperNo field to given value.

### HasSupplierShipperNo

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) HasSupplierShipperNo() bool`

HasSupplierShipperNo returns a boolean if a field has been set.

### GetReceiptDate

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) GetReceiptDate() time.Time`

GetReceiptDate returns the ReceiptDate field if non-nil, zero value otherwise.

### GetReceiptDateOk

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) GetReceiptDateOk() (*time.Time, bool)`

GetReceiptDateOk returns a tuple with the ReceiptDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceiptDate

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) SetReceiptDate(v time.Time)`

SetReceiptDate sets ReceiptDate field to given value.

### HasReceiptDate

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) HasReceiptDate() bool`

HasReceiptDate returns a boolean if a field has been set.

### GetPartId

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetPartNumber

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) GetPartNumber() string`

GetPartNumber returns the PartNumber field if non-nil, zero value otherwise.

### GetPartNumberOk

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) GetPartNumberOk() (*string, bool)`

GetPartNumberOk returns a tuple with the PartNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumber

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) SetPartNumber(v string)`

SetPartNumber sets PartNumber field to given value.

### HasPartNumber

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) HasPartNumber() bool`

HasPartNumber returns a boolean if a field has been set.

### GetRevision

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) GetRevision() string`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) GetRevisionOk() (*string, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) SetRevision(v string)`

SetRevision sets Revision field to given value.

### HasRevision

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) HasRevision() bool`

HasRevision returns a boolean if a field has been set.

### GetPartNumberRevision

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) GetPartNumberRevision() string`

GetPartNumberRevision returns the PartNumberRevision field if non-nil, zero value otherwise.

### GetPartNumberRevisionOk

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) GetPartNumberRevisionOk() (*string, bool)`

GetPartNumberRevisionOk returns a tuple with the PartNumberRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumberRevision

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) SetPartNumberRevision(v string)`

SetPartNumberRevision sets PartNumberRevision field to given value.

### HasPartNumberRevision

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) HasPartNumberRevision() bool`

HasPartNumberRevision returns a boolean if a field has been set.

### GetPartOperationId

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) GetPartOperationId() string`

GetPartOperationId returns the PartOperationId field if non-nil, zero value otherwise.

### GetPartOperationIdOk

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) GetPartOperationIdOk() (*string, bool)`

GetPartOperationIdOk returns a tuple with the PartOperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartOperationId

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) SetPartOperationId(v string)`

SetPartOperationId sets PartOperationId field to given value.

### HasPartOperationId

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) HasPartOperationId() bool`

HasPartOperationId returns a boolean if a field has been set.

### GetOperationCode

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) GetOperationCode() string`

GetOperationCode returns the OperationCode field if non-nil, zero value otherwise.

### GetOperationCodeOk

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) GetOperationCodeOk() (*string, bool)`

GetOperationCodeOk returns a tuple with the OperationCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationCode

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) SetOperationCode(v string)`

SetOperationCode sets OperationCode field to given value.

### HasOperationCode

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) HasOperationCode() bool`

HasOperationCode returns a boolean if a field has been set.

### GetOperationNumber

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) GetOperationNumber() int32`

GetOperationNumber returns the OperationNumber field if non-nil, zero value otherwise.

### GetOperationNumberOk

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) GetOperationNumberOk() (*int32, bool)`

GetOperationNumberOk returns a tuple with the OperationNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationNumber

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) SetOperationNumber(v int32)`

SetOperationNumber sets OperationNumber field to given value.

### HasOperationNumber

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) HasOperationNumber() bool`

HasOperationNumber returns a boolean if a field has been set.

### GetSerialNo

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) GetSerialNo() string`

GetSerialNo returns the SerialNo field if non-nil, zero value otherwise.

### GetSerialNoOk

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) GetSerialNoOk() (*string, bool)`

GetSerialNoOk returns a tuple with the SerialNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSerialNo

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) SetSerialNo(v string)`

SetSerialNo sets SerialNo field to given value.

### HasSerialNo

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) HasSerialNo() bool`

HasSerialNo returns a boolean if a field has been set.

### GetLotNo

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) GetLotNo() string`

GetLotNo returns the LotNo field if non-nil, zero value otherwise.

### GetLotNoOk

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) GetLotNoOk() (*string, bool)`

GetLotNoOk returns a tuple with the LotNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLotNo

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) SetLotNo(v string)`

SetLotNo sets LotNo field to given value.

### HasLotNo

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) HasLotNo() bool`

HasLotNo returns a boolean if a field has been set.

### GetLotId

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) GetLotId() string`

GetLotId returns the LotId field if non-nil, zero value otherwise.

### GetLotIdOk

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) GetLotIdOk() (*string, bool)`

GetLotIdOk returns a tuple with the LotId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLotId

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) SetLotId(v string)`

SetLotId sets LotId field to given value.

### HasLotId

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) HasLotId() bool`

HasLotId returns a boolean if a field has been set.

### GetTrackingNo

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) GetTrackingNo() string`

GetTrackingNo returns the TrackingNo field if non-nil, zero value otherwise.

### GetTrackingNoOk

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) GetTrackingNoOk() (*string, bool)`

GetTrackingNoOk returns a tuple with the TrackingNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackingNo

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) SetTrackingNo(v string)`

SetTrackingNo sets TrackingNo field to given value.

### HasTrackingNo

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) HasTrackingNo() bool`

HasTrackingNo returns a boolean if a field has been set.

### GetHeatCode

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) GetHeatCode() string`

GetHeatCode returns the HeatCode field if non-nil, zero value otherwise.

### GetHeatCodeOk

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) GetHeatCodeOk() (*string, bool)`

GetHeatCodeOk returns a tuple with the HeatCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeatCode

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) SetHeatCode(v string)`

SetHeatCode sets HeatCode field to given value.

### HasHeatCode

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) HasHeatCode() bool`

HasHeatCode returns a boolean if a field has been set.

### GetHeatNo

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) GetHeatNo() string`

GetHeatNo returns the HeatNo field if non-nil, zero value otherwise.

### GetHeatNoOk

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) GetHeatNoOk() (*string, bool)`

GetHeatNoOk returns a tuple with the HeatNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeatNo

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) SetHeatNo(v string)`

SetHeatNo sets HeatNo field to given value.

### HasHeatNo

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) HasHeatNo() bool`

HasHeatNo returns a boolean if a field has been set.

### GetReceivedQuantity

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) GetReceivedQuantity() float64`

GetReceivedQuantity returns the ReceivedQuantity field if non-nil, zero value otherwise.

### GetReceivedQuantityOk

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) GetReceivedQuantityOk() (*float64, bool)`

GetReceivedQuantityOk returns a tuple with the ReceivedQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceivedQuantity

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) SetReceivedQuantity(v float64)`

SetReceivedQuantity sets ReceivedQuantity field to given value.

### HasReceivedQuantity

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) HasReceivedQuantity() bool`

HasReceivedQuantity returns a boolean if a field has been set.

### GetReceiptNote

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) GetReceiptNote() string`

GetReceiptNote returns the ReceiptNote field if non-nil, zero value otherwise.

### GetReceiptNoteOk

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) GetReceiptNoteOk() (*string, bool)`

GetReceiptNoteOk returns a tuple with the ReceiptNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceiptNote

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) SetReceiptNote(v string)`

SetReceiptNote sets ReceiptNote field to given value.

### HasReceiptNote

`func (o *ProductionOperationsManagementApiListSubcontractReceiptsItem) HasReceiptNote() bool`

HasReceiptNote returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


