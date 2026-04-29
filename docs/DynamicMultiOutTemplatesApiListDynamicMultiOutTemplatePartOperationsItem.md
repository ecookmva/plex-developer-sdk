# DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | A unique identifier for the Part Operation. | [optional] 
**TemplateId** | Pointer to **string** | A unique identifier for the Dynamic Multi Out Template. | [optional] 
**PartId** | Pointer to **string** | A unique identifier for the Part. | [optional] 
**PartNumber** | Pointer to **string** | The Part Number of the Part Operation. | [optional] 
**Revision** | Pointer to **string** | The Revision of the Part. | [optional] 
**PartNumberRevision** | Pointer to **string** | The Part Operation&#39;s Part Number Revision formatted with separator. | [optional] 
**OperationNumber** | Pointer to **int32** | The Operation Number of the Part Operation. | [optional] 
**OperationCode** | Pointer to **string** | The Operation Code of the Part Operation. | [optional] 
**Workcenters** | Pointer to **[]string** | The workcenters that belong to the operation and are valid for Multi Out Template execution. | [optional] 
**Multiple** | Pointer to **float64** | The multiple value of the Part Operation. | [optional] 
**Primary** | Pointer to **bool** | When true, flags this Part Operation as the primary for this template. | [optional] 

## Methods

### NewDynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem

`func NewDynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem() *DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem`

NewDynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem instantiates a new DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItemWithDefaults

`func NewDynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItemWithDefaults() *DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem`

NewDynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItemWithDefaults instantiates a new DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem) HasId() bool`

HasId returns a boolean if a field has been set.

### GetTemplateId

`func (o *DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem) GetTemplateId() string`

GetTemplateId returns the TemplateId field if non-nil, zero value otherwise.

### GetTemplateIdOk

`func (o *DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem) GetTemplateIdOk() (*string, bool)`

GetTemplateIdOk returns a tuple with the TemplateId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemplateId

`func (o *DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem) SetTemplateId(v string)`

SetTemplateId sets TemplateId field to given value.

### HasTemplateId

`func (o *DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem) HasTemplateId() bool`

HasTemplateId returns a boolean if a field has been set.

### GetPartId

`func (o *DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetPartNumber

`func (o *DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem) GetPartNumber() string`

GetPartNumber returns the PartNumber field if non-nil, zero value otherwise.

### GetPartNumberOk

`func (o *DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem) GetPartNumberOk() (*string, bool)`

GetPartNumberOk returns a tuple with the PartNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumber

`func (o *DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem) SetPartNumber(v string)`

SetPartNumber sets PartNumber field to given value.

### HasPartNumber

`func (o *DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem) HasPartNumber() bool`

HasPartNumber returns a boolean if a field has been set.

### GetRevision

`func (o *DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem) GetRevision() string`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem) GetRevisionOk() (*string, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem) SetRevision(v string)`

SetRevision sets Revision field to given value.

### HasRevision

`func (o *DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem) HasRevision() bool`

HasRevision returns a boolean if a field has been set.

### GetPartNumberRevision

`func (o *DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem) GetPartNumberRevision() string`

GetPartNumberRevision returns the PartNumberRevision field if non-nil, zero value otherwise.

### GetPartNumberRevisionOk

`func (o *DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem) GetPartNumberRevisionOk() (*string, bool)`

GetPartNumberRevisionOk returns a tuple with the PartNumberRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumberRevision

`func (o *DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem) SetPartNumberRevision(v string)`

SetPartNumberRevision sets PartNumberRevision field to given value.

### HasPartNumberRevision

`func (o *DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem) HasPartNumberRevision() bool`

HasPartNumberRevision returns a boolean if a field has been set.

### GetOperationNumber

`func (o *DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem) GetOperationNumber() int32`

GetOperationNumber returns the OperationNumber field if non-nil, zero value otherwise.

### GetOperationNumberOk

`func (o *DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem) GetOperationNumberOk() (*int32, bool)`

GetOperationNumberOk returns a tuple with the OperationNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationNumber

`func (o *DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem) SetOperationNumber(v int32)`

SetOperationNumber sets OperationNumber field to given value.

### HasOperationNumber

`func (o *DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem) HasOperationNumber() bool`

HasOperationNumber returns a boolean if a field has been set.

### GetOperationCode

`func (o *DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem) GetOperationCode() string`

GetOperationCode returns the OperationCode field if non-nil, zero value otherwise.

### GetOperationCodeOk

`func (o *DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem) GetOperationCodeOk() (*string, bool)`

GetOperationCodeOk returns a tuple with the OperationCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationCode

`func (o *DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem) SetOperationCode(v string)`

SetOperationCode sets OperationCode field to given value.

### HasOperationCode

`func (o *DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem) HasOperationCode() bool`

HasOperationCode returns a boolean if a field has been set.

### GetWorkcenters

`func (o *DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem) GetWorkcenters() []string`

GetWorkcenters returns the Workcenters field if non-nil, zero value otherwise.

### GetWorkcentersOk

`func (o *DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem) GetWorkcentersOk() (*[]string, bool)`

GetWorkcentersOk returns a tuple with the Workcenters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkcenters

`func (o *DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem) SetWorkcenters(v []string)`

SetWorkcenters sets Workcenters field to given value.

### HasWorkcenters

`func (o *DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem) HasWorkcenters() bool`

HasWorkcenters returns a boolean if a field has been set.

### GetMultiple

`func (o *DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem) GetMultiple() float64`

GetMultiple returns the Multiple field if non-nil, zero value otherwise.

### GetMultipleOk

`func (o *DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem) GetMultipleOk() (*float64, bool)`

GetMultipleOk returns a tuple with the Multiple field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMultiple

`func (o *DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem) SetMultiple(v float64)`

SetMultiple sets Multiple field to given value.

### HasMultiple

`func (o *DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem) HasMultiple() bool`

HasMultiple returns a boolean if a field has been set.

### GetPrimary

`func (o *DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem) GetPrimary() bool`

GetPrimary returns the Primary field if non-nil, zero value otherwise.

### GetPrimaryOk

`func (o *DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem) GetPrimaryOk() (*bool, bool)`

GetPrimaryOk returns a tuple with the Primary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrimary

`func (o *DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem) SetPrimary(v bool)`

SetPrimary sets Primary field to given value.

### HasPrimary

`func (o *DynamicMultiOutTemplatesApiListDynamicMultiOutTemplatePartOperationsItem) HasPrimary() bool`

HasPrimary returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


