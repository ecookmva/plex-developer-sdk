# PurchaseOrderReleasesBatchApiGetReleaseBatchResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | The ID of the batch request. | [optional] 
**ReleasesCount** | Pointer to **int32** | The number of releases in the batch request. | [optional] 
**ReleasesProcessed** | Pointer to **int32** | The number of releases in the batch request that have been processed. | [optional] 
**Failures** | Pointer to **[]string** | Any errors encountered while processing the releases from a batch request. | [optional] 

## Methods

### NewPurchaseOrderReleasesBatchApiGetReleaseBatchResponse

`func NewPurchaseOrderReleasesBatchApiGetReleaseBatchResponse() *PurchaseOrderReleasesBatchApiGetReleaseBatchResponse`

NewPurchaseOrderReleasesBatchApiGetReleaseBatchResponse instantiates a new PurchaseOrderReleasesBatchApiGetReleaseBatchResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPurchaseOrderReleasesBatchApiGetReleaseBatchResponseWithDefaults

`func NewPurchaseOrderReleasesBatchApiGetReleaseBatchResponseWithDefaults() *PurchaseOrderReleasesBatchApiGetReleaseBatchResponse`

NewPurchaseOrderReleasesBatchApiGetReleaseBatchResponseWithDefaults instantiates a new PurchaseOrderReleasesBatchApiGetReleaseBatchResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *PurchaseOrderReleasesBatchApiGetReleaseBatchResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PurchaseOrderReleasesBatchApiGetReleaseBatchResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PurchaseOrderReleasesBatchApiGetReleaseBatchResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *PurchaseOrderReleasesBatchApiGetReleaseBatchResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetReleasesCount

`func (o *PurchaseOrderReleasesBatchApiGetReleaseBatchResponse) GetReleasesCount() int32`

GetReleasesCount returns the ReleasesCount field if non-nil, zero value otherwise.

### GetReleasesCountOk

`func (o *PurchaseOrderReleasesBatchApiGetReleaseBatchResponse) GetReleasesCountOk() (*int32, bool)`

GetReleasesCountOk returns a tuple with the ReleasesCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleasesCount

`func (o *PurchaseOrderReleasesBatchApiGetReleaseBatchResponse) SetReleasesCount(v int32)`

SetReleasesCount sets ReleasesCount field to given value.

### HasReleasesCount

`func (o *PurchaseOrderReleasesBatchApiGetReleaseBatchResponse) HasReleasesCount() bool`

HasReleasesCount returns a boolean if a field has been set.

### GetReleasesProcessed

`func (o *PurchaseOrderReleasesBatchApiGetReleaseBatchResponse) GetReleasesProcessed() int32`

GetReleasesProcessed returns the ReleasesProcessed field if non-nil, zero value otherwise.

### GetReleasesProcessedOk

`func (o *PurchaseOrderReleasesBatchApiGetReleaseBatchResponse) GetReleasesProcessedOk() (*int32, bool)`

GetReleasesProcessedOk returns a tuple with the ReleasesProcessed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleasesProcessed

`func (o *PurchaseOrderReleasesBatchApiGetReleaseBatchResponse) SetReleasesProcessed(v int32)`

SetReleasesProcessed sets ReleasesProcessed field to given value.

### HasReleasesProcessed

`func (o *PurchaseOrderReleasesBatchApiGetReleaseBatchResponse) HasReleasesProcessed() bool`

HasReleasesProcessed returns a boolean if a field has been set.

### GetFailures

`func (o *PurchaseOrderReleasesBatchApiGetReleaseBatchResponse) GetFailures() []string`

GetFailures returns the Failures field if non-nil, zero value otherwise.

### GetFailuresOk

`func (o *PurchaseOrderReleasesBatchApiGetReleaseBatchResponse) GetFailuresOk() (*[]string, bool)`

GetFailuresOk returns a tuple with the Failures field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailures

`func (o *PurchaseOrderReleasesBatchApiGetReleaseBatchResponse) SetFailures(v []string)`

SetFailures sets Failures field to given value.

### HasFailures

`func (o *PurchaseOrderReleasesBatchApiGetReleaseBatchResponse) HasFailures() bool`

HasFailures returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


