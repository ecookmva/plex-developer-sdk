# ProductionOperationsManagementApiListApprovedSuppliersItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PartId** | Pointer to **string** | A unique identifier for the part. | [optional] 
**PartNo** | Pointer to **string** | A short code or number to reference the part. 100 characters max. | [optional] 
**PartRevision** | Pointer to **string** | The revision of the part. 8 characters max. | [optional] 
**PartNoRevision** | Pointer to **string** | Format {partNumber}{part rev separator}{revision}. If a part number has a revision, Plex will return the part number and the revision separated by the Part Rev Separator setting. | [optional] 
**PartOperationId** | Pointer to **string** | A unique identifier for the part operation. | [optional] 
**OperationNo** | Pointer to **int32** | The operation number of the part operation. | [optional] 
**OperationCode** | Pointer to **string** | The operation code of the part operation. 30 characters max. | [optional] 
**SupplierId** | Pointer to **string** | The ID of the supplier. | [optional] 
**SupplierCode** | Pointer to **string** | The supplier code of the supplier. 25 characters max. | [optional] 
**Note** | Pointer to **string** | Notes related to the supplier. 500 characters max. | [optional] 
**ApprovedSupplierId** | Pointer to **string** | The ID of the approved supplier. | [optional] 

## Methods

### NewProductionOperationsManagementApiListApprovedSuppliersItem

`func NewProductionOperationsManagementApiListApprovedSuppliersItem() *ProductionOperationsManagementApiListApprovedSuppliersItem`

NewProductionOperationsManagementApiListApprovedSuppliersItem instantiates a new ProductionOperationsManagementApiListApprovedSuppliersItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductionOperationsManagementApiListApprovedSuppliersItemWithDefaults

`func NewProductionOperationsManagementApiListApprovedSuppliersItemWithDefaults() *ProductionOperationsManagementApiListApprovedSuppliersItem`

NewProductionOperationsManagementApiListApprovedSuppliersItemWithDefaults instantiates a new ProductionOperationsManagementApiListApprovedSuppliersItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPartId

`func (o *ProductionOperationsManagementApiListApprovedSuppliersItem) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *ProductionOperationsManagementApiListApprovedSuppliersItem) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *ProductionOperationsManagementApiListApprovedSuppliersItem) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *ProductionOperationsManagementApiListApprovedSuppliersItem) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetPartNo

`func (o *ProductionOperationsManagementApiListApprovedSuppliersItem) GetPartNo() string`

GetPartNo returns the PartNo field if non-nil, zero value otherwise.

### GetPartNoOk

`func (o *ProductionOperationsManagementApiListApprovedSuppliersItem) GetPartNoOk() (*string, bool)`

GetPartNoOk returns a tuple with the PartNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNo

`func (o *ProductionOperationsManagementApiListApprovedSuppliersItem) SetPartNo(v string)`

SetPartNo sets PartNo field to given value.

### HasPartNo

`func (o *ProductionOperationsManagementApiListApprovedSuppliersItem) HasPartNo() bool`

HasPartNo returns a boolean if a field has been set.

### GetPartRevision

`func (o *ProductionOperationsManagementApiListApprovedSuppliersItem) GetPartRevision() string`

GetPartRevision returns the PartRevision field if non-nil, zero value otherwise.

### GetPartRevisionOk

`func (o *ProductionOperationsManagementApiListApprovedSuppliersItem) GetPartRevisionOk() (*string, bool)`

GetPartRevisionOk returns a tuple with the PartRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartRevision

`func (o *ProductionOperationsManagementApiListApprovedSuppliersItem) SetPartRevision(v string)`

SetPartRevision sets PartRevision field to given value.

### HasPartRevision

`func (o *ProductionOperationsManagementApiListApprovedSuppliersItem) HasPartRevision() bool`

HasPartRevision returns a boolean if a field has been set.

### GetPartNoRevision

`func (o *ProductionOperationsManagementApiListApprovedSuppliersItem) GetPartNoRevision() string`

GetPartNoRevision returns the PartNoRevision field if non-nil, zero value otherwise.

### GetPartNoRevisionOk

`func (o *ProductionOperationsManagementApiListApprovedSuppliersItem) GetPartNoRevisionOk() (*string, bool)`

GetPartNoRevisionOk returns a tuple with the PartNoRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNoRevision

`func (o *ProductionOperationsManagementApiListApprovedSuppliersItem) SetPartNoRevision(v string)`

SetPartNoRevision sets PartNoRevision field to given value.

### HasPartNoRevision

`func (o *ProductionOperationsManagementApiListApprovedSuppliersItem) HasPartNoRevision() bool`

HasPartNoRevision returns a boolean if a field has been set.

### GetPartOperationId

`func (o *ProductionOperationsManagementApiListApprovedSuppliersItem) GetPartOperationId() string`

GetPartOperationId returns the PartOperationId field if non-nil, zero value otherwise.

### GetPartOperationIdOk

`func (o *ProductionOperationsManagementApiListApprovedSuppliersItem) GetPartOperationIdOk() (*string, bool)`

GetPartOperationIdOk returns a tuple with the PartOperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartOperationId

`func (o *ProductionOperationsManagementApiListApprovedSuppliersItem) SetPartOperationId(v string)`

SetPartOperationId sets PartOperationId field to given value.

### HasPartOperationId

`func (o *ProductionOperationsManagementApiListApprovedSuppliersItem) HasPartOperationId() bool`

HasPartOperationId returns a boolean if a field has been set.

### GetOperationNo

`func (o *ProductionOperationsManagementApiListApprovedSuppliersItem) GetOperationNo() int32`

GetOperationNo returns the OperationNo field if non-nil, zero value otherwise.

### GetOperationNoOk

`func (o *ProductionOperationsManagementApiListApprovedSuppliersItem) GetOperationNoOk() (*int32, bool)`

GetOperationNoOk returns a tuple with the OperationNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationNo

`func (o *ProductionOperationsManagementApiListApprovedSuppliersItem) SetOperationNo(v int32)`

SetOperationNo sets OperationNo field to given value.

### HasOperationNo

`func (o *ProductionOperationsManagementApiListApprovedSuppliersItem) HasOperationNo() bool`

HasOperationNo returns a boolean if a field has been set.

### GetOperationCode

`func (o *ProductionOperationsManagementApiListApprovedSuppliersItem) GetOperationCode() string`

GetOperationCode returns the OperationCode field if non-nil, zero value otherwise.

### GetOperationCodeOk

`func (o *ProductionOperationsManagementApiListApprovedSuppliersItem) GetOperationCodeOk() (*string, bool)`

GetOperationCodeOk returns a tuple with the OperationCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationCode

`func (o *ProductionOperationsManagementApiListApprovedSuppliersItem) SetOperationCode(v string)`

SetOperationCode sets OperationCode field to given value.

### HasOperationCode

`func (o *ProductionOperationsManagementApiListApprovedSuppliersItem) HasOperationCode() bool`

HasOperationCode returns a boolean if a field has been set.

### GetSupplierId

`func (o *ProductionOperationsManagementApiListApprovedSuppliersItem) GetSupplierId() string`

GetSupplierId returns the SupplierId field if non-nil, zero value otherwise.

### GetSupplierIdOk

`func (o *ProductionOperationsManagementApiListApprovedSuppliersItem) GetSupplierIdOk() (*string, bool)`

GetSupplierIdOk returns a tuple with the SupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierId

`func (o *ProductionOperationsManagementApiListApprovedSuppliersItem) SetSupplierId(v string)`

SetSupplierId sets SupplierId field to given value.

### HasSupplierId

`func (o *ProductionOperationsManagementApiListApprovedSuppliersItem) HasSupplierId() bool`

HasSupplierId returns a boolean if a field has been set.

### GetSupplierCode

`func (o *ProductionOperationsManagementApiListApprovedSuppliersItem) GetSupplierCode() string`

GetSupplierCode returns the SupplierCode field if non-nil, zero value otherwise.

### GetSupplierCodeOk

`func (o *ProductionOperationsManagementApiListApprovedSuppliersItem) GetSupplierCodeOk() (*string, bool)`

GetSupplierCodeOk returns a tuple with the SupplierCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierCode

`func (o *ProductionOperationsManagementApiListApprovedSuppliersItem) SetSupplierCode(v string)`

SetSupplierCode sets SupplierCode field to given value.

### HasSupplierCode

`func (o *ProductionOperationsManagementApiListApprovedSuppliersItem) HasSupplierCode() bool`

HasSupplierCode returns a boolean if a field has been set.

### GetNote

`func (o *ProductionOperationsManagementApiListApprovedSuppliersItem) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *ProductionOperationsManagementApiListApprovedSuppliersItem) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *ProductionOperationsManagementApiListApprovedSuppliersItem) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *ProductionOperationsManagementApiListApprovedSuppliersItem) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetApprovedSupplierId

`func (o *ProductionOperationsManagementApiListApprovedSuppliersItem) GetApprovedSupplierId() string`

GetApprovedSupplierId returns the ApprovedSupplierId field if non-nil, zero value otherwise.

### GetApprovedSupplierIdOk

`func (o *ProductionOperationsManagementApiListApprovedSuppliersItem) GetApprovedSupplierIdOk() (*string, bool)`

GetApprovedSupplierIdOk returns a tuple with the ApprovedSupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovedSupplierId

`func (o *ProductionOperationsManagementApiListApprovedSuppliersItem) SetApprovedSupplierId(v string)`

SetApprovedSupplierId sets ApprovedSupplierId field to given value.

### HasApprovedSupplierId

`func (o *ProductionOperationsManagementApiListApprovedSuppliersItem) HasApprovedSupplierId() bool`

HasApprovedSupplierId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


