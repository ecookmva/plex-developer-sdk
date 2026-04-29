# PurchaseOrderReleasesBatchApiDeleteReleaseBatchRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeleteReleaseAcknowledgementRecords** | Pointer to **bool** | A flag indicating whether or not to delete the release acknowledgements which are associated with the releases. | [optional] 
**ReleaseId** | Pointer to **[]string** | A list of unique identifiers for releases to delete. | [optional] 
**Status** | Pointer to **[]string** | One or more release status names. | [optional] 
**PartId** | Pointer to **[]string** | One or more unique identifiers for parts which are associated with releases. | [optional] 
**SupplierId** | Pointer to **[]string** | One or more unique identifiers for suppliers which are associated with releases. | [optional] 

## Methods

### NewPurchaseOrderReleasesBatchApiDeleteReleaseBatchRequest

`func NewPurchaseOrderReleasesBatchApiDeleteReleaseBatchRequest() *PurchaseOrderReleasesBatchApiDeleteReleaseBatchRequest`

NewPurchaseOrderReleasesBatchApiDeleteReleaseBatchRequest instantiates a new PurchaseOrderReleasesBatchApiDeleteReleaseBatchRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPurchaseOrderReleasesBatchApiDeleteReleaseBatchRequestWithDefaults

`func NewPurchaseOrderReleasesBatchApiDeleteReleaseBatchRequestWithDefaults() *PurchaseOrderReleasesBatchApiDeleteReleaseBatchRequest`

NewPurchaseOrderReleasesBatchApiDeleteReleaseBatchRequestWithDefaults instantiates a new PurchaseOrderReleasesBatchApiDeleteReleaseBatchRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeleteReleaseAcknowledgementRecords

`func (o *PurchaseOrderReleasesBatchApiDeleteReleaseBatchRequest) GetDeleteReleaseAcknowledgementRecords() bool`

GetDeleteReleaseAcknowledgementRecords returns the DeleteReleaseAcknowledgementRecords field if non-nil, zero value otherwise.

### GetDeleteReleaseAcknowledgementRecordsOk

`func (o *PurchaseOrderReleasesBatchApiDeleteReleaseBatchRequest) GetDeleteReleaseAcknowledgementRecordsOk() (*bool, bool)`

GetDeleteReleaseAcknowledgementRecordsOk returns a tuple with the DeleteReleaseAcknowledgementRecords field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeleteReleaseAcknowledgementRecords

`func (o *PurchaseOrderReleasesBatchApiDeleteReleaseBatchRequest) SetDeleteReleaseAcknowledgementRecords(v bool)`

SetDeleteReleaseAcknowledgementRecords sets DeleteReleaseAcknowledgementRecords field to given value.

### HasDeleteReleaseAcknowledgementRecords

`func (o *PurchaseOrderReleasesBatchApiDeleteReleaseBatchRequest) HasDeleteReleaseAcknowledgementRecords() bool`

HasDeleteReleaseAcknowledgementRecords returns a boolean if a field has been set.

### GetReleaseId

`func (o *PurchaseOrderReleasesBatchApiDeleteReleaseBatchRequest) GetReleaseId() []string`

GetReleaseId returns the ReleaseId field if non-nil, zero value otherwise.

### GetReleaseIdOk

`func (o *PurchaseOrderReleasesBatchApiDeleteReleaseBatchRequest) GetReleaseIdOk() (*[]string, bool)`

GetReleaseIdOk returns a tuple with the ReleaseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleaseId

`func (o *PurchaseOrderReleasesBatchApiDeleteReleaseBatchRequest) SetReleaseId(v []string)`

SetReleaseId sets ReleaseId field to given value.

### HasReleaseId

`func (o *PurchaseOrderReleasesBatchApiDeleteReleaseBatchRequest) HasReleaseId() bool`

HasReleaseId returns a boolean if a field has been set.

### GetStatus

`func (o *PurchaseOrderReleasesBatchApiDeleteReleaseBatchRequest) GetStatus() []string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PurchaseOrderReleasesBatchApiDeleteReleaseBatchRequest) GetStatusOk() (*[]string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PurchaseOrderReleasesBatchApiDeleteReleaseBatchRequest) SetStatus(v []string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *PurchaseOrderReleasesBatchApiDeleteReleaseBatchRequest) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetPartId

`func (o *PurchaseOrderReleasesBatchApiDeleteReleaseBatchRequest) GetPartId() []string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *PurchaseOrderReleasesBatchApiDeleteReleaseBatchRequest) GetPartIdOk() (*[]string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *PurchaseOrderReleasesBatchApiDeleteReleaseBatchRequest) SetPartId(v []string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *PurchaseOrderReleasesBatchApiDeleteReleaseBatchRequest) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetSupplierId

`func (o *PurchaseOrderReleasesBatchApiDeleteReleaseBatchRequest) GetSupplierId() []string`

GetSupplierId returns the SupplierId field if non-nil, zero value otherwise.

### GetSupplierIdOk

`func (o *PurchaseOrderReleasesBatchApiDeleteReleaseBatchRequest) GetSupplierIdOk() (*[]string, bool)`

GetSupplierIdOk returns a tuple with the SupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierId

`func (o *PurchaseOrderReleasesBatchApiDeleteReleaseBatchRequest) SetSupplierId(v []string)`

SetSupplierId sets SupplierId field to given value.

### HasSupplierId

`func (o *PurchaseOrderReleasesBatchApiDeleteReleaseBatchRequest) HasSupplierId() bool`

HasSupplierId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


