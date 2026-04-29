# BatchesItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | A unique identifier of the batch. | [optional] 
**Number** | Pointer to **int32** | Identifier of the batch for the current job operation. | [optional] 
**BatchStatus** | Pointer to **string** | The status of the batch. | [optional] 
**Size** | Pointer to **float64** | The quantity to be produced in the batch. | [optional] 

## Methods

### NewBatchesItem

`func NewBatchesItem() *BatchesItem`

NewBatchesItem instantiates a new BatchesItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBatchesItemWithDefaults

`func NewBatchesItemWithDefaults() *BatchesItem`

NewBatchesItemWithDefaults instantiates a new BatchesItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *BatchesItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *BatchesItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *BatchesItem) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *BatchesItem) HasId() bool`

HasId returns a boolean if a field has been set.

### GetNumber

`func (o *BatchesItem) GetNumber() int32`

GetNumber returns the Number field if non-nil, zero value otherwise.

### GetNumberOk

`func (o *BatchesItem) GetNumberOk() (*int32, bool)`

GetNumberOk returns a tuple with the Number field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumber

`func (o *BatchesItem) SetNumber(v int32)`

SetNumber sets Number field to given value.

### HasNumber

`func (o *BatchesItem) HasNumber() bool`

HasNumber returns a boolean if a field has been set.

### GetBatchStatus

`func (o *BatchesItem) GetBatchStatus() string`

GetBatchStatus returns the BatchStatus field if non-nil, zero value otherwise.

### GetBatchStatusOk

`func (o *BatchesItem) GetBatchStatusOk() (*string, bool)`

GetBatchStatusOk returns a tuple with the BatchStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBatchStatus

`func (o *BatchesItem) SetBatchStatus(v string)`

SetBatchStatus sets BatchStatus field to given value.

### HasBatchStatus

`func (o *BatchesItem) HasBatchStatus() bool`

HasBatchStatus returns a boolean if a field has been set.

### GetSize

`func (o *BatchesItem) GetSize() float64`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *BatchesItem) GetSizeOk() (*float64, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *BatchesItem) SetSize(v float64)`

SetSize sets Size field to given value.

### HasSize

`func (o *BatchesItem) HasSize() bool`

HasSize returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


