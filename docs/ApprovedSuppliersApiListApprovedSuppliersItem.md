# ApprovedSuppliersApiListApprovedSuppliersItem

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

### NewApprovedSuppliersApiListApprovedSuppliersItem

`func NewApprovedSuppliersApiListApprovedSuppliersItem() *ApprovedSuppliersApiListApprovedSuppliersItem`

NewApprovedSuppliersApiListApprovedSuppliersItem instantiates a new ApprovedSuppliersApiListApprovedSuppliersItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewApprovedSuppliersApiListApprovedSuppliersItemWithDefaults

`func NewApprovedSuppliersApiListApprovedSuppliersItemWithDefaults() *ApprovedSuppliersApiListApprovedSuppliersItem`

NewApprovedSuppliersApiListApprovedSuppliersItemWithDefaults instantiates a new ApprovedSuppliersApiListApprovedSuppliersItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ApprovedSuppliersApiListApprovedSuppliersItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ApprovedSuppliersApiListApprovedSuppliersItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ApprovedSuppliersApiListApprovedSuppliersItem) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *ApprovedSuppliersApiListApprovedSuppliersItem) HasId() bool`

HasId returns a boolean if a field has been set.

### GetPartId

`func (o *ApprovedSuppliersApiListApprovedSuppliersItem) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *ApprovedSuppliersApiListApprovedSuppliersItem) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *ApprovedSuppliersApiListApprovedSuppliersItem) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *ApprovedSuppliersApiListApprovedSuppliersItem) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetOperationCode

`func (o *ApprovedSuppliersApiListApprovedSuppliersItem) GetOperationCode() string`

GetOperationCode returns the OperationCode field if non-nil, zero value otherwise.

### GetOperationCodeOk

`func (o *ApprovedSuppliersApiListApprovedSuppliersItem) GetOperationCodeOk() (*string, bool)`

GetOperationCodeOk returns a tuple with the OperationCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationCode

`func (o *ApprovedSuppliersApiListApprovedSuppliersItem) SetOperationCode(v string)`

SetOperationCode sets OperationCode field to given value.

### HasOperationCode

`func (o *ApprovedSuppliersApiListApprovedSuppliersItem) HasOperationCode() bool`

HasOperationCode returns a boolean if a field has been set.

### GetSupplierId

`func (o *ApprovedSuppliersApiListApprovedSuppliersItem) GetSupplierId() string`

GetSupplierId returns the SupplierId field if non-nil, zero value otherwise.

### GetSupplierIdOk

`func (o *ApprovedSuppliersApiListApprovedSuppliersItem) GetSupplierIdOk() (*string, bool)`

GetSupplierIdOk returns a tuple with the SupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierId

`func (o *ApprovedSuppliersApiListApprovedSuppliersItem) SetSupplierId(v string)`

SetSupplierId sets SupplierId field to given value.

### HasSupplierId

`func (o *ApprovedSuppliersApiListApprovedSuppliersItem) HasSupplierId() bool`

HasSupplierId returns a boolean if a field has been set.

### GetLeadTime

`func (o *ApprovedSuppliersApiListApprovedSuppliersItem) GetLeadTime() float64`

GetLeadTime returns the LeadTime field if non-nil, zero value otherwise.

### GetLeadTimeOk

`func (o *ApprovedSuppliersApiListApprovedSuppliersItem) GetLeadTimeOk() (*float64, bool)`

GetLeadTimeOk returns a tuple with the LeadTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeadTime

`func (o *ApprovedSuppliersApiListApprovedSuppliersItem) SetLeadTime(v float64)`

SetLeadTime sets LeadTime field to given value.

### HasLeadTime

`func (o *ApprovedSuppliersApiListApprovedSuppliersItem) HasLeadTime() bool`

HasLeadTime returns a boolean if a field has been set.

### GetSupplierPartNumber

`func (o *ApprovedSuppliersApiListApprovedSuppliersItem) GetSupplierPartNumber() string`

GetSupplierPartNumber returns the SupplierPartNumber field if non-nil, zero value otherwise.

### GetSupplierPartNumberOk

`func (o *ApprovedSuppliersApiListApprovedSuppliersItem) GetSupplierPartNumberOk() (*string, bool)`

GetSupplierPartNumberOk returns a tuple with the SupplierPartNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierPartNumber

`func (o *ApprovedSuppliersApiListApprovedSuppliersItem) SetSupplierPartNumber(v string)`

SetSupplierPartNumber sets SupplierPartNumber field to given value.

### HasSupplierPartNumber

`func (o *ApprovedSuppliersApiListApprovedSuppliersItem) HasSupplierPartNumber() bool`

HasSupplierPartNumber returns a boolean if a field has been set.

### GetBusinessPercentage

`func (o *ApprovedSuppliersApiListApprovedSuppliersItem) GetBusinessPercentage() float64`

GetBusinessPercentage returns the BusinessPercentage field if non-nil, zero value otherwise.

### GetBusinessPercentageOk

`func (o *ApprovedSuppliersApiListApprovedSuppliersItem) GetBusinessPercentageOk() (*float64, bool)`

GetBusinessPercentageOk returns a tuple with the BusinessPercentage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusinessPercentage

`func (o *ApprovedSuppliersApiListApprovedSuppliersItem) SetBusinessPercentage(v float64)`

SetBusinessPercentage sets BusinessPercentage field to given value.

### HasBusinessPercentage

`func (o *ApprovedSuppliersApiListApprovedSuppliersItem) HasBusinessPercentage() bool`

HasBusinessPercentage returns a boolean if a field has been set.

### GetTransitTime

`func (o *ApprovedSuppliersApiListApprovedSuppliersItem) GetTransitTime() float64`

GetTransitTime returns the TransitTime field if non-nil, zero value otherwise.

### GetTransitTimeOk

`func (o *ApprovedSuppliersApiListApprovedSuppliersItem) GetTransitTimeOk() (*float64, bool)`

GetTransitTimeOk returns a tuple with the TransitTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransitTime

`func (o *ApprovedSuppliersApiListApprovedSuppliersItem) SetTransitTime(v float64)`

SetTransitTime sets TransitTime field to given value.

### HasTransitTime

`func (o *ApprovedSuppliersApiListApprovedSuppliersItem) HasTransitTime() bool`

HasTransitTime returns a boolean if a field has been set.

### GetNote

`func (o *ApprovedSuppliersApiListApprovedSuppliersItem) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *ApprovedSuppliersApiListApprovedSuppliersItem) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *ApprovedSuppliersApiListApprovedSuppliersItem) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *ApprovedSuppliersApiListApprovedSuppliersItem) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetPartOperationId

`func (o *ApprovedSuppliersApiListApprovedSuppliersItem) GetPartOperationId() string`

GetPartOperationId returns the PartOperationId field if non-nil, zero value otherwise.

### GetPartOperationIdOk

`func (o *ApprovedSuppliersApiListApprovedSuppliersItem) GetPartOperationIdOk() (*string, bool)`

GetPartOperationIdOk returns a tuple with the PartOperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartOperationId

`func (o *ApprovedSuppliersApiListApprovedSuppliersItem) SetPartOperationId(v string)`

SetPartOperationId sets PartOperationId field to given value.

### HasPartOperationId

`func (o *ApprovedSuppliersApiListApprovedSuppliersItem) HasPartOperationId() bool`

HasPartOperationId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


