# EdiApiCreateReleaseSnapshotRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PoLineId** | Pointer to **string** | The Resource Id of the PO Line record. | [optional] 
**ShipToId** | Pointer to **string** | The Customer Address Resource Id ship to Address | [optional] 
**ReleaseNo** | Pointer to **string** | The Release Number | [optional] 
**ProcessDate** | Pointer to **time.Time** | The Process Date | [optional] 
**DueDate** | Pointer to **time.Time** | The Due Date | [optional] 
**ShipDate** | Pointer to **time.Time** | The Ship Date | [optional] 
**ReleaseQuantity** | Pointer to **int32** | The Release Quantity | [optional] 
**EdiAccumQuantity** | Pointer to **int32** | The EDI Accum Quantity | [optional] 
**AccumQuantity** | Pointer to **int32** | The Accum Quantity | [optional] 
**AccumAuthorizedQuantity** | Pointer to **int32** | The Accum Authorized Quantity | [optional] 
**IsDaily** | Pointer to **bool** | Is Daily | [optional] 
**IsChange** | Pointer to **bool** | Is Change | [optional] 
**OriginalEDIQuantity** | Pointer to **int32** | The Original EDI Quantity | [optional] 
**LastShipperNo** | Pointer to **string** | The Last Shipper Number | [optional] 
**LastShipDate** | Pointer to **time.Time** | The Last Ship Date | [optional] 
**LastShipQuantity** | Pointer to **int32** | The Last Ship Quantity | [optional] 

## Methods

### NewEdiApiCreateReleaseSnapshotRequest

`func NewEdiApiCreateReleaseSnapshotRequest() *EdiApiCreateReleaseSnapshotRequest`

NewEdiApiCreateReleaseSnapshotRequest instantiates a new EdiApiCreateReleaseSnapshotRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEdiApiCreateReleaseSnapshotRequestWithDefaults

`func NewEdiApiCreateReleaseSnapshotRequestWithDefaults() *EdiApiCreateReleaseSnapshotRequest`

NewEdiApiCreateReleaseSnapshotRequestWithDefaults instantiates a new EdiApiCreateReleaseSnapshotRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPoLineId

`func (o *EdiApiCreateReleaseSnapshotRequest) GetPoLineId() string`

GetPoLineId returns the PoLineId field if non-nil, zero value otherwise.

### GetPoLineIdOk

`func (o *EdiApiCreateReleaseSnapshotRequest) GetPoLineIdOk() (*string, bool)`

GetPoLineIdOk returns a tuple with the PoLineId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoLineId

`func (o *EdiApiCreateReleaseSnapshotRequest) SetPoLineId(v string)`

SetPoLineId sets PoLineId field to given value.

### HasPoLineId

`func (o *EdiApiCreateReleaseSnapshotRequest) HasPoLineId() bool`

HasPoLineId returns a boolean if a field has been set.

### GetShipToId

`func (o *EdiApiCreateReleaseSnapshotRequest) GetShipToId() string`

GetShipToId returns the ShipToId field if non-nil, zero value otherwise.

### GetShipToIdOk

`func (o *EdiApiCreateReleaseSnapshotRequest) GetShipToIdOk() (*string, bool)`

GetShipToIdOk returns a tuple with the ShipToId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipToId

`func (o *EdiApiCreateReleaseSnapshotRequest) SetShipToId(v string)`

SetShipToId sets ShipToId field to given value.

### HasShipToId

`func (o *EdiApiCreateReleaseSnapshotRequest) HasShipToId() bool`

HasShipToId returns a boolean if a field has been set.

### GetReleaseNo

`func (o *EdiApiCreateReleaseSnapshotRequest) GetReleaseNo() string`

GetReleaseNo returns the ReleaseNo field if non-nil, zero value otherwise.

### GetReleaseNoOk

`func (o *EdiApiCreateReleaseSnapshotRequest) GetReleaseNoOk() (*string, bool)`

GetReleaseNoOk returns a tuple with the ReleaseNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleaseNo

`func (o *EdiApiCreateReleaseSnapshotRequest) SetReleaseNo(v string)`

SetReleaseNo sets ReleaseNo field to given value.

### HasReleaseNo

`func (o *EdiApiCreateReleaseSnapshotRequest) HasReleaseNo() bool`

HasReleaseNo returns a boolean if a field has been set.

### GetProcessDate

`func (o *EdiApiCreateReleaseSnapshotRequest) GetProcessDate() time.Time`

GetProcessDate returns the ProcessDate field if non-nil, zero value otherwise.

### GetProcessDateOk

`func (o *EdiApiCreateReleaseSnapshotRequest) GetProcessDateOk() (*time.Time, bool)`

GetProcessDateOk returns a tuple with the ProcessDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessDate

`func (o *EdiApiCreateReleaseSnapshotRequest) SetProcessDate(v time.Time)`

SetProcessDate sets ProcessDate field to given value.

### HasProcessDate

`func (o *EdiApiCreateReleaseSnapshotRequest) HasProcessDate() bool`

HasProcessDate returns a boolean if a field has been set.

### GetDueDate

`func (o *EdiApiCreateReleaseSnapshotRequest) GetDueDate() time.Time`

GetDueDate returns the DueDate field if non-nil, zero value otherwise.

### GetDueDateOk

`func (o *EdiApiCreateReleaseSnapshotRequest) GetDueDateOk() (*time.Time, bool)`

GetDueDateOk returns a tuple with the DueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueDate

`func (o *EdiApiCreateReleaseSnapshotRequest) SetDueDate(v time.Time)`

SetDueDate sets DueDate field to given value.

### HasDueDate

`func (o *EdiApiCreateReleaseSnapshotRequest) HasDueDate() bool`

HasDueDate returns a boolean if a field has been set.

### GetShipDate

`func (o *EdiApiCreateReleaseSnapshotRequest) GetShipDate() time.Time`

GetShipDate returns the ShipDate field if non-nil, zero value otherwise.

### GetShipDateOk

`func (o *EdiApiCreateReleaseSnapshotRequest) GetShipDateOk() (*time.Time, bool)`

GetShipDateOk returns a tuple with the ShipDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipDate

`func (o *EdiApiCreateReleaseSnapshotRequest) SetShipDate(v time.Time)`

SetShipDate sets ShipDate field to given value.

### HasShipDate

`func (o *EdiApiCreateReleaseSnapshotRequest) HasShipDate() bool`

HasShipDate returns a boolean if a field has been set.

### GetReleaseQuantity

`func (o *EdiApiCreateReleaseSnapshotRequest) GetReleaseQuantity() int32`

GetReleaseQuantity returns the ReleaseQuantity field if non-nil, zero value otherwise.

### GetReleaseQuantityOk

`func (o *EdiApiCreateReleaseSnapshotRequest) GetReleaseQuantityOk() (*int32, bool)`

GetReleaseQuantityOk returns a tuple with the ReleaseQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleaseQuantity

`func (o *EdiApiCreateReleaseSnapshotRequest) SetReleaseQuantity(v int32)`

SetReleaseQuantity sets ReleaseQuantity field to given value.

### HasReleaseQuantity

`func (o *EdiApiCreateReleaseSnapshotRequest) HasReleaseQuantity() bool`

HasReleaseQuantity returns a boolean if a field has been set.

### GetEdiAccumQuantity

`func (o *EdiApiCreateReleaseSnapshotRequest) GetEdiAccumQuantity() int32`

GetEdiAccumQuantity returns the EdiAccumQuantity field if non-nil, zero value otherwise.

### GetEdiAccumQuantityOk

`func (o *EdiApiCreateReleaseSnapshotRequest) GetEdiAccumQuantityOk() (*int32, bool)`

GetEdiAccumQuantityOk returns a tuple with the EdiAccumQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEdiAccumQuantity

`func (o *EdiApiCreateReleaseSnapshotRequest) SetEdiAccumQuantity(v int32)`

SetEdiAccumQuantity sets EdiAccumQuantity field to given value.

### HasEdiAccumQuantity

`func (o *EdiApiCreateReleaseSnapshotRequest) HasEdiAccumQuantity() bool`

HasEdiAccumQuantity returns a boolean if a field has been set.

### GetAccumQuantity

`func (o *EdiApiCreateReleaseSnapshotRequest) GetAccumQuantity() int32`

GetAccumQuantity returns the AccumQuantity field if non-nil, zero value otherwise.

### GetAccumQuantityOk

`func (o *EdiApiCreateReleaseSnapshotRequest) GetAccumQuantityOk() (*int32, bool)`

GetAccumQuantityOk returns a tuple with the AccumQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccumQuantity

`func (o *EdiApiCreateReleaseSnapshotRequest) SetAccumQuantity(v int32)`

SetAccumQuantity sets AccumQuantity field to given value.

### HasAccumQuantity

`func (o *EdiApiCreateReleaseSnapshotRequest) HasAccumQuantity() bool`

HasAccumQuantity returns a boolean if a field has been set.

### GetAccumAuthorizedQuantity

`func (o *EdiApiCreateReleaseSnapshotRequest) GetAccumAuthorizedQuantity() int32`

GetAccumAuthorizedQuantity returns the AccumAuthorizedQuantity field if non-nil, zero value otherwise.

### GetAccumAuthorizedQuantityOk

`func (o *EdiApiCreateReleaseSnapshotRequest) GetAccumAuthorizedQuantityOk() (*int32, bool)`

GetAccumAuthorizedQuantityOk returns a tuple with the AccumAuthorizedQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccumAuthorizedQuantity

`func (o *EdiApiCreateReleaseSnapshotRequest) SetAccumAuthorizedQuantity(v int32)`

SetAccumAuthorizedQuantity sets AccumAuthorizedQuantity field to given value.

### HasAccumAuthorizedQuantity

`func (o *EdiApiCreateReleaseSnapshotRequest) HasAccumAuthorizedQuantity() bool`

HasAccumAuthorizedQuantity returns a boolean if a field has been set.

### GetIsDaily

`func (o *EdiApiCreateReleaseSnapshotRequest) GetIsDaily() bool`

GetIsDaily returns the IsDaily field if non-nil, zero value otherwise.

### GetIsDailyOk

`func (o *EdiApiCreateReleaseSnapshotRequest) GetIsDailyOk() (*bool, bool)`

GetIsDailyOk returns a tuple with the IsDaily field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDaily

`func (o *EdiApiCreateReleaseSnapshotRequest) SetIsDaily(v bool)`

SetIsDaily sets IsDaily field to given value.

### HasIsDaily

`func (o *EdiApiCreateReleaseSnapshotRequest) HasIsDaily() bool`

HasIsDaily returns a boolean if a field has been set.

### GetIsChange

`func (o *EdiApiCreateReleaseSnapshotRequest) GetIsChange() bool`

GetIsChange returns the IsChange field if non-nil, zero value otherwise.

### GetIsChangeOk

`func (o *EdiApiCreateReleaseSnapshotRequest) GetIsChangeOk() (*bool, bool)`

GetIsChangeOk returns a tuple with the IsChange field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsChange

`func (o *EdiApiCreateReleaseSnapshotRequest) SetIsChange(v bool)`

SetIsChange sets IsChange field to given value.

### HasIsChange

`func (o *EdiApiCreateReleaseSnapshotRequest) HasIsChange() bool`

HasIsChange returns a boolean if a field has been set.

### GetOriginalEDIQuantity

`func (o *EdiApiCreateReleaseSnapshotRequest) GetOriginalEDIQuantity() int32`

GetOriginalEDIQuantity returns the OriginalEDIQuantity field if non-nil, zero value otherwise.

### GetOriginalEDIQuantityOk

`func (o *EdiApiCreateReleaseSnapshotRequest) GetOriginalEDIQuantityOk() (*int32, bool)`

GetOriginalEDIQuantityOk returns a tuple with the OriginalEDIQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginalEDIQuantity

`func (o *EdiApiCreateReleaseSnapshotRequest) SetOriginalEDIQuantity(v int32)`

SetOriginalEDIQuantity sets OriginalEDIQuantity field to given value.

### HasOriginalEDIQuantity

`func (o *EdiApiCreateReleaseSnapshotRequest) HasOriginalEDIQuantity() bool`

HasOriginalEDIQuantity returns a boolean if a field has been set.

### GetLastShipperNo

`func (o *EdiApiCreateReleaseSnapshotRequest) GetLastShipperNo() string`

GetLastShipperNo returns the LastShipperNo field if non-nil, zero value otherwise.

### GetLastShipperNoOk

`func (o *EdiApiCreateReleaseSnapshotRequest) GetLastShipperNoOk() (*string, bool)`

GetLastShipperNoOk returns a tuple with the LastShipperNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastShipperNo

`func (o *EdiApiCreateReleaseSnapshotRequest) SetLastShipperNo(v string)`

SetLastShipperNo sets LastShipperNo field to given value.

### HasLastShipperNo

`func (o *EdiApiCreateReleaseSnapshotRequest) HasLastShipperNo() bool`

HasLastShipperNo returns a boolean if a field has been set.

### GetLastShipDate

`func (o *EdiApiCreateReleaseSnapshotRequest) GetLastShipDate() time.Time`

GetLastShipDate returns the LastShipDate field if non-nil, zero value otherwise.

### GetLastShipDateOk

`func (o *EdiApiCreateReleaseSnapshotRequest) GetLastShipDateOk() (*time.Time, bool)`

GetLastShipDateOk returns a tuple with the LastShipDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastShipDate

`func (o *EdiApiCreateReleaseSnapshotRequest) SetLastShipDate(v time.Time)`

SetLastShipDate sets LastShipDate field to given value.

### HasLastShipDate

`func (o *EdiApiCreateReleaseSnapshotRequest) HasLastShipDate() bool`

HasLastShipDate returns a boolean if a field has been set.

### GetLastShipQuantity

`func (o *EdiApiCreateReleaseSnapshotRequest) GetLastShipQuantity() int32`

GetLastShipQuantity returns the LastShipQuantity field if non-nil, zero value otherwise.

### GetLastShipQuantityOk

`func (o *EdiApiCreateReleaseSnapshotRequest) GetLastShipQuantityOk() (*int32, bool)`

GetLastShipQuantityOk returns a tuple with the LastShipQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastShipQuantity

`func (o *EdiApiCreateReleaseSnapshotRequest) SetLastShipQuantity(v int32)`

SetLastShipQuantity sets LastShipQuantity field to given value.

### HasLastShipQuantity

`func (o *EdiApiCreateReleaseSnapshotRequest) HasLastShipQuantity() bool`

HasLastShipQuantity returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


