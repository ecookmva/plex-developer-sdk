# OperatingParametersApiListOperatingParameterGroupsItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** |  | [optional] 
**OperatingParameter** | Pointer to [**OperatingParameter**](OperatingParameter.md) |  | [optional] 
**PartOperation** | Pointer to **string** |  | [optional] 
**OperationNo** | Pointer to **int32** |  | [optional] 
**EquipmentType** | Pointer to **string** |  | [optional] 
**ApprovedEquipment** | Pointer to **string** |  | [optional] 
**EquipmentAttributeName** | Pointer to **string** |  | [optional] 
**TextValue** | Pointer to **string** |  | [optional] 
**ListValue** | Pointer to [**[]ListValueItem**](ListValueItem.md) |  | [optional] 
**NumericValue** | Pointer to **float64** |  | [optional] 
**Precision** | Pointer to **int32** |  | [optional] 
**Active** | Pointer to **bool** |  | [optional] 

## Methods

### NewOperatingParametersApiListOperatingParameterGroupsItem

`func NewOperatingParametersApiListOperatingParameterGroupsItem() *OperatingParametersApiListOperatingParameterGroupsItem`

NewOperatingParametersApiListOperatingParameterGroupsItem instantiates a new OperatingParametersApiListOperatingParameterGroupsItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperatingParametersApiListOperatingParameterGroupsItemWithDefaults

`func NewOperatingParametersApiListOperatingParameterGroupsItemWithDefaults() *OperatingParametersApiListOperatingParameterGroupsItem`

NewOperatingParametersApiListOperatingParameterGroupsItemWithDefaults instantiates a new OperatingParametersApiListOperatingParameterGroupsItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *OperatingParametersApiListOperatingParameterGroupsItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *OperatingParametersApiListOperatingParameterGroupsItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *OperatingParametersApiListOperatingParameterGroupsItem) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *OperatingParametersApiListOperatingParameterGroupsItem) HasId() bool`

HasId returns a boolean if a field has been set.

### GetOperatingParameter

`func (o *OperatingParametersApiListOperatingParameterGroupsItem) GetOperatingParameter() OperatingParameter`

GetOperatingParameter returns the OperatingParameter field if non-nil, zero value otherwise.

### GetOperatingParameterOk

`func (o *OperatingParametersApiListOperatingParameterGroupsItem) GetOperatingParameterOk() (*OperatingParameter, bool)`

GetOperatingParameterOk returns a tuple with the OperatingParameter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperatingParameter

`func (o *OperatingParametersApiListOperatingParameterGroupsItem) SetOperatingParameter(v OperatingParameter)`

SetOperatingParameter sets OperatingParameter field to given value.

### HasOperatingParameter

`func (o *OperatingParametersApiListOperatingParameterGroupsItem) HasOperatingParameter() bool`

HasOperatingParameter returns a boolean if a field has been set.

### GetPartOperation

`func (o *OperatingParametersApiListOperatingParameterGroupsItem) GetPartOperation() string`

GetPartOperation returns the PartOperation field if non-nil, zero value otherwise.

### GetPartOperationOk

`func (o *OperatingParametersApiListOperatingParameterGroupsItem) GetPartOperationOk() (*string, bool)`

GetPartOperationOk returns a tuple with the PartOperation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartOperation

`func (o *OperatingParametersApiListOperatingParameterGroupsItem) SetPartOperation(v string)`

SetPartOperation sets PartOperation field to given value.

### HasPartOperation

`func (o *OperatingParametersApiListOperatingParameterGroupsItem) HasPartOperation() bool`

HasPartOperation returns a boolean if a field has been set.

### GetOperationNo

`func (o *OperatingParametersApiListOperatingParameterGroupsItem) GetOperationNo() int32`

GetOperationNo returns the OperationNo field if non-nil, zero value otherwise.

### GetOperationNoOk

`func (o *OperatingParametersApiListOperatingParameterGroupsItem) GetOperationNoOk() (*int32, bool)`

GetOperationNoOk returns a tuple with the OperationNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationNo

`func (o *OperatingParametersApiListOperatingParameterGroupsItem) SetOperationNo(v int32)`

SetOperationNo sets OperationNo field to given value.

### HasOperationNo

`func (o *OperatingParametersApiListOperatingParameterGroupsItem) HasOperationNo() bool`

HasOperationNo returns a boolean if a field has been set.

### GetEquipmentType

`func (o *OperatingParametersApiListOperatingParameterGroupsItem) GetEquipmentType() string`

GetEquipmentType returns the EquipmentType field if non-nil, zero value otherwise.

### GetEquipmentTypeOk

`func (o *OperatingParametersApiListOperatingParameterGroupsItem) GetEquipmentTypeOk() (*string, bool)`

GetEquipmentTypeOk returns a tuple with the EquipmentType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEquipmentType

`func (o *OperatingParametersApiListOperatingParameterGroupsItem) SetEquipmentType(v string)`

SetEquipmentType sets EquipmentType field to given value.

### HasEquipmentType

`func (o *OperatingParametersApiListOperatingParameterGroupsItem) HasEquipmentType() bool`

HasEquipmentType returns a boolean if a field has been set.

### GetApprovedEquipment

`func (o *OperatingParametersApiListOperatingParameterGroupsItem) GetApprovedEquipment() string`

GetApprovedEquipment returns the ApprovedEquipment field if non-nil, zero value otherwise.

### GetApprovedEquipmentOk

`func (o *OperatingParametersApiListOperatingParameterGroupsItem) GetApprovedEquipmentOk() (*string, bool)`

GetApprovedEquipmentOk returns a tuple with the ApprovedEquipment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovedEquipment

`func (o *OperatingParametersApiListOperatingParameterGroupsItem) SetApprovedEquipment(v string)`

SetApprovedEquipment sets ApprovedEquipment field to given value.

### HasApprovedEquipment

`func (o *OperatingParametersApiListOperatingParameterGroupsItem) HasApprovedEquipment() bool`

HasApprovedEquipment returns a boolean if a field has been set.

### GetEquipmentAttributeName

`func (o *OperatingParametersApiListOperatingParameterGroupsItem) GetEquipmentAttributeName() string`

GetEquipmentAttributeName returns the EquipmentAttributeName field if non-nil, zero value otherwise.

### GetEquipmentAttributeNameOk

`func (o *OperatingParametersApiListOperatingParameterGroupsItem) GetEquipmentAttributeNameOk() (*string, bool)`

GetEquipmentAttributeNameOk returns a tuple with the EquipmentAttributeName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEquipmentAttributeName

`func (o *OperatingParametersApiListOperatingParameterGroupsItem) SetEquipmentAttributeName(v string)`

SetEquipmentAttributeName sets EquipmentAttributeName field to given value.

### HasEquipmentAttributeName

`func (o *OperatingParametersApiListOperatingParameterGroupsItem) HasEquipmentAttributeName() bool`

HasEquipmentAttributeName returns a boolean if a field has been set.

### GetTextValue

`func (o *OperatingParametersApiListOperatingParameterGroupsItem) GetTextValue() string`

GetTextValue returns the TextValue field if non-nil, zero value otherwise.

### GetTextValueOk

`func (o *OperatingParametersApiListOperatingParameterGroupsItem) GetTextValueOk() (*string, bool)`

GetTextValueOk returns a tuple with the TextValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTextValue

`func (o *OperatingParametersApiListOperatingParameterGroupsItem) SetTextValue(v string)`

SetTextValue sets TextValue field to given value.

### HasTextValue

`func (o *OperatingParametersApiListOperatingParameterGroupsItem) HasTextValue() bool`

HasTextValue returns a boolean if a field has been set.

### GetListValue

`func (o *OperatingParametersApiListOperatingParameterGroupsItem) GetListValue() []ListValueItem`

GetListValue returns the ListValue field if non-nil, zero value otherwise.

### GetListValueOk

`func (o *OperatingParametersApiListOperatingParameterGroupsItem) GetListValueOk() (*[]ListValueItem, bool)`

GetListValueOk returns a tuple with the ListValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetListValue

`func (o *OperatingParametersApiListOperatingParameterGroupsItem) SetListValue(v []ListValueItem)`

SetListValue sets ListValue field to given value.

### HasListValue

`func (o *OperatingParametersApiListOperatingParameterGroupsItem) HasListValue() bool`

HasListValue returns a boolean if a field has been set.

### GetNumericValue

`func (o *OperatingParametersApiListOperatingParameterGroupsItem) GetNumericValue() float64`

GetNumericValue returns the NumericValue field if non-nil, zero value otherwise.

### GetNumericValueOk

`func (o *OperatingParametersApiListOperatingParameterGroupsItem) GetNumericValueOk() (*float64, bool)`

GetNumericValueOk returns a tuple with the NumericValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumericValue

`func (o *OperatingParametersApiListOperatingParameterGroupsItem) SetNumericValue(v float64)`

SetNumericValue sets NumericValue field to given value.

### HasNumericValue

`func (o *OperatingParametersApiListOperatingParameterGroupsItem) HasNumericValue() bool`

HasNumericValue returns a boolean if a field has been set.

### GetPrecision

`func (o *OperatingParametersApiListOperatingParameterGroupsItem) GetPrecision() int32`

GetPrecision returns the Precision field if non-nil, zero value otherwise.

### GetPrecisionOk

`func (o *OperatingParametersApiListOperatingParameterGroupsItem) GetPrecisionOk() (*int32, bool)`

GetPrecisionOk returns a tuple with the Precision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrecision

`func (o *OperatingParametersApiListOperatingParameterGroupsItem) SetPrecision(v int32)`

SetPrecision sets Precision field to given value.

### HasPrecision

`func (o *OperatingParametersApiListOperatingParameterGroupsItem) HasPrecision() bool`

HasPrecision returns a boolean if a field has been set.

### GetActive

`func (o *OperatingParametersApiListOperatingParameterGroupsItem) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *OperatingParametersApiListOperatingParameterGroupsItem) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *OperatingParametersApiListOperatingParameterGroupsItem) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *OperatingParametersApiListOperatingParameterGroupsItem) HasActive() bool`

HasActive returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


