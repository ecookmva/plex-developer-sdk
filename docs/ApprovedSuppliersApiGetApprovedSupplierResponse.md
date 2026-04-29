# ApprovedSuppliersApiGetApprovedSupplierResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | A unique identifier for the Approved Supplier. | [optional] 
**PartId** | Pointer to **string** | The part ID. | [optional] 
**OperationCode** | Pointer to **string** | Application: Operation List | [optional] 
**SupplierId** | Pointer to **string** | The supplier ID. | [optional] 
**LeadTime** | Pointer to **float64** | Estimated lead time | [optional] 
**SupplierPartNumber** | Pointer to **string** | The part number used by the Supplier. | [optional] 
**BusinessPercentage** | Pointer to **float64** | The business percentage for the approved supplier. | [optional] 
**TransitTime** | Pointer to **float64** | Estimated transit time. | [optional] 
**Note** | Pointer to **string** | The approved supplier note. | [optional] 
**PartOperationId** | Pointer to **string** | The part operation ID. | [optional] 

## Methods

### NewApprovedSuppliersApiGetApprovedSupplierResponse

`func NewApprovedSuppliersApiGetApprovedSupplierResponse() *ApprovedSuppliersApiGetApprovedSupplierResponse`

NewApprovedSuppliersApiGetApprovedSupplierResponse instantiates a new ApprovedSuppliersApiGetApprovedSupplierResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewApprovedSuppliersApiGetApprovedSupplierResponseWithDefaults

`func NewApprovedSuppliersApiGetApprovedSupplierResponseWithDefaults() *ApprovedSuppliersApiGetApprovedSupplierResponse`

NewApprovedSuppliersApiGetApprovedSupplierResponseWithDefaults instantiates a new ApprovedSuppliersApiGetApprovedSupplierResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ApprovedSuppliersApiGetApprovedSupplierResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ApprovedSuppliersApiGetApprovedSupplierResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ApprovedSuppliersApiGetApprovedSupplierResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *ApprovedSuppliersApiGetApprovedSupplierResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetPartId

`func (o *ApprovedSuppliersApiGetApprovedSupplierResponse) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *ApprovedSuppliersApiGetApprovedSupplierResponse) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *ApprovedSuppliersApiGetApprovedSupplierResponse) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *ApprovedSuppliersApiGetApprovedSupplierResponse) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetOperationCode

`func (o *ApprovedSuppliersApiGetApprovedSupplierResponse) GetOperationCode() string`

GetOperationCode returns the OperationCode field if non-nil, zero value otherwise.

### GetOperationCodeOk

`func (o *ApprovedSuppliersApiGetApprovedSupplierResponse) GetOperationCodeOk() (*string, bool)`

GetOperationCodeOk returns a tuple with the OperationCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationCode

`func (o *ApprovedSuppliersApiGetApprovedSupplierResponse) SetOperationCode(v string)`

SetOperationCode sets OperationCode field to given value.

### HasOperationCode

`func (o *ApprovedSuppliersApiGetApprovedSupplierResponse) HasOperationCode() bool`

HasOperationCode returns a boolean if a field has been set.

### GetSupplierId

`func (o *ApprovedSuppliersApiGetApprovedSupplierResponse) GetSupplierId() string`

GetSupplierId returns the SupplierId field if non-nil, zero value otherwise.

### GetSupplierIdOk

`func (o *ApprovedSuppliersApiGetApprovedSupplierResponse) GetSupplierIdOk() (*string, bool)`

GetSupplierIdOk returns a tuple with the SupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierId

`func (o *ApprovedSuppliersApiGetApprovedSupplierResponse) SetSupplierId(v string)`

SetSupplierId sets SupplierId field to given value.

### HasSupplierId

`func (o *ApprovedSuppliersApiGetApprovedSupplierResponse) HasSupplierId() bool`

HasSupplierId returns a boolean if a field has been set.

### GetLeadTime

`func (o *ApprovedSuppliersApiGetApprovedSupplierResponse) GetLeadTime() float64`

GetLeadTime returns the LeadTime field if non-nil, zero value otherwise.

### GetLeadTimeOk

`func (o *ApprovedSuppliersApiGetApprovedSupplierResponse) GetLeadTimeOk() (*float64, bool)`

GetLeadTimeOk returns a tuple with the LeadTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeadTime

`func (o *ApprovedSuppliersApiGetApprovedSupplierResponse) SetLeadTime(v float64)`

SetLeadTime sets LeadTime field to given value.

### HasLeadTime

`func (o *ApprovedSuppliersApiGetApprovedSupplierResponse) HasLeadTime() bool`

HasLeadTime returns a boolean if a field has been set.

### GetSupplierPartNumber

`func (o *ApprovedSuppliersApiGetApprovedSupplierResponse) GetSupplierPartNumber() string`

GetSupplierPartNumber returns the SupplierPartNumber field if non-nil, zero value otherwise.

### GetSupplierPartNumberOk

`func (o *ApprovedSuppliersApiGetApprovedSupplierResponse) GetSupplierPartNumberOk() (*string, bool)`

GetSupplierPartNumberOk returns a tuple with the SupplierPartNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierPartNumber

`func (o *ApprovedSuppliersApiGetApprovedSupplierResponse) SetSupplierPartNumber(v string)`

SetSupplierPartNumber sets SupplierPartNumber field to given value.

### HasSupplierPartNumber

`func (o *ApprovedSuppliersApiGetApprovedSupplierResponse) HasSupplierPartNumber() bool`

HasSupplierPartNumber returns a boolean if a field has been set.

### GetBusinessPercentage

`func (o *ApprovedSuppliersApiGetApprovedSupplierResponse) GetBusinessPercentage() float64`

GetBusinessPercentage returns the BusinessPercentage field if non-nil, zero value otherwise.

### GetBusinessPercentageOk

`func (o *ApprovedSuppliersApiGetApprovedSupplierResponse) GetBusinessPercentageOk() (*float64, bool)`

GetBusinessPercentageOk returns a tuple with the BusinessPercentage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusinessPercentage

`func (o *ApprovedSuppliersApiGetApprovedSupplierResponse) SetBusinessPercentage(v float64)`

SetBusinessPercentage sets BusinessPercentage field to given value.

### HasBusinessPercentage

`func (o *ApprovedSuppliersApiGetApprovedSupplierResponse) HasBusinessPercentage() bool`

HasBusinessPercentage returns a boolean if a field has been set.

### GetTransitTime

`func (o *ApprovedSuppliersApiGetApprovedSupplierResponse) GetTransitTime() float64`

GetTransitTime returns the TransitTime field if non-nil, zero value otherwise.

### GetTransitTimeOk

`func (o *ApprovedSuppliersApiGetApprovedSupplierResponse) GetTransitTimeOk() (*float64, bool)`

GetTransitTimeOk returns a tuple with the TransitTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransitTime

`func (o *ApprovedSuppliersApiGetApprovedSupplierResponse) SetTransitTime(v float64)`

SetTransitTime sets TransitTime field to given value.

### HasTransitTime

`func (o *ApprovedSuppliersApiGetApprovedSupplierResponse) HasTransitTime() bool`

HasTransitTime returns a boolean if a field has been set.

### GetNote

`func (o *ApprovedSuppliersApiGetApprovedSupplierResponse) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *ApprovedSuppliersApiGetApprovedSupplierResponse) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *ApprovedSuppliersApiGetApprovedSupplierResponse) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *ApprovedSuppliersApiGetApprovedSupplierResponse) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetPartOperationId

`func (o *ApprovedSuppliersApiGetApprovedSupplierResponse) GetPartOperationId() string`

GetPartOperationId returns the PartOperationId field if non-nil, zero value otherwise.

### GetPartOperationIdOk

`func (o *ApprovedSuppliersApiGetApprovedSupplierResponse) GetPartOperationIdOk() (*string, bool)`

GetPartOperationIdOk returns a tuple with the PartOperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartOperationId

`func (o *ApprovedSuppliersApiGetApprovedSupplierResponse) SetPartOperationId(v string)`

SetPartOperationId sets PartOperationId field to given value.

### HasPartOperationId

`func (o *ApprovedSuppliersApiGetApprovedSupplierResponse) HasPartOperationId() bool`

HasPartOperationId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


