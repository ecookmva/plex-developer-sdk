# ReceivedContainersItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PartId** | Pointer to **string** | A unique identifier for the part. | [optional] 
**PartNo** | Pointer to **string** | A short code or number to reference the part. 100 characters max. | [optional] 
**PartRevision** | Pointer to **string** | The revision of the part. 8 characters max. | [optional] 
**PartNoRevision** | Pointer to **string** | Format {partNumber}{part rev separator}{revision}. If a part number has a revision, Plex will return the part number and the revision separated by the Part Rev Separator setting. | [optional] 
**LotId** | Pointer to **string** | A unique identifier for the lot. | [optional] 
**LotNo** | Pointer to **string** | The unique number to reference lot. 25 characters max. | [optional] 
**HeatCode** | Pointer to **string** | A short code to reference the heat. 50 characters max. | [optional] 
**HeatNo** | Pointer to **string** | A number to reference the heat. 30 characters max. | [optional] 
**HeatId** | Pointer to **string** | A unique identifier for the heat. | [optional] 
**SerialNo** | Pointer to **string** | The serial number of the container that was received. 25 characters max. | [optional] 
**ExternalSerialNo** | Pointer to **string** | The from container number of the container that was received. 25 characters max. | [optional] 
**Quantity** | Pointer to **float64** | The received quantity of container. | [optional] 
**Unit** | Pointer to **string** | The unit of the part. 20 characters max. | [optional] 

## Methods

### NewReceivedContainersItem

`func NewReceivedContainersItem() *ReceivedContainersItem`

NewReceivedContainersItem instantiates a new ReceivedContainersItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReceivedContainersItemWithDefaults

`func NewReceivedContainersItemWithDefaults() *ReceivedContainersItem`

NewReceivedContainersItemWithDefaults instantiates a new ReceivedContainersItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPartId

`func (o *ReceivedContainersItem) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *ReceivedContainersItem) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *ReceivedContainersItem) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *ReceivedContainersItem) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetPartNo

`func (o *ReceivedContainersItem) GetPartNo() string`

GetPartNo returns the PartNo field if non-nil, zero value otherwise.

### GetPartNoOk

`func (o *ReceivedContainersItem) GetPartNoOk() (*string, bool)`

GetPartNoOk returns a tuple with the PartNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNo

`func (o *ReceivedContainersItem) SetPartNo(v string)`

SetPartNo sets PartNo field to given value.

### HasPartNo

`func (o *ReceivedContainersItem) HasPartNo() bool`

HasPartNo returns a boolean if a field has been set.

### GetPartRevision

`func (o *ReceivedContainersItem) GetPartRevision() string`

GetPartRevision returns the PartRevision field if non-nil, zero value otherwise.

### GetPartRevisionOk

`func (o *ReceivedContainersItem) GetPartRevisionOk() (*string, bool)`

GetPartRevisionOk returns a tuple with the PartRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartRevision

`func (o *ReceivedContainersItem) SetPartRevision(v string)`

SetPartRevision sets PartRevision field to given value.

### HasPartRevision

`func (o *ReceivedContainersItem) HasPartRevision() bool`

HasPartRevision returns a boolean if a field has been set.

### GetPartNoRevision

`func (o *ReceivedContainersItem) GetPartNoRevision() string`

GetPartNoRevision returns the PartNoRevision field if non-nil, zero value otherwise.

### GetPartNoRevisionOk

`func (o *ReceivedContainersItem) GetPartNoRevisionOk() (*string, bool)`

GetPartNoRevisionOk returns a tuple with the PartNoRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNoRevision

`func (o *ReceivedContainersItem) SetPartNoRevision(v string)`

SetPartNoRevision sets PartNoRevision field to given value.

### HasPartNoRevision

`func (o *ReceivedContainersItem) HasPartNoRevision() bool`

HasPartNoRevision returns a boolean if a field has been set.

### GetLotId

`func (o *ReceivedContainersItem) GetLotId() string`

GetLotId returns the LotId field if non-nil, zero value otherwise.

### GetLotIdOk

`func (o *ReceivedContainersItem) GetLotIdOk() (*string, bool)`

GetLotIdOk returns a tuple with the LotId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLotId

`func (o *ReceivedContainersItem) SetLotId(v string)`

SetLotId sets LotId field to given value.

### HasLotId

`func (o *ReceivedContainersItem) HasLotId() bool`

HasLotId returns a boolean if a field has been set.

### GetLotNo

`func (o *ReceivedContainersItem) GetLotNo() string`

GetLotNo returns the LotNo field if non-nil, zero value otherwise.

### GetLotNoOk

`func (o *ReceivedContainersItem) GetLotNoOk() (*string, bool)`

GetLotNoOk returns a tuple with the LotNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLotNo

`func (o *ReceivedContainersItem) SetLotNo(v string)`

SetLotNo sets LotNo field to given value.

### HasLotNo

`func (o *ReceivedContainersItem) HasLotNo() bool`

HasLotNo returns a boolean if a field has been set.

### GetHeatCode

`func (o *ReceivedContainersItem) GetHeatCode() string`

GetHeatCode returns the HeatCode field if non-nil, zero value otherwise.

### GetHeatCodeOk

`func (o *ReceivedContainersItem) GetHeatCodeOk() (*string, bool)`

GetHeatCodeOk returns a tuple with the HeatCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeatCode

`func (o *ReceivedContainersItem) SetHeatCode(v string)`

SetHeatCode sets HeatCode field to given value.

### HasHeatCode

`func (o *ReceivedContainersItem) HasHeatCode() bool`

HasHeatCode returns a boolean if a field has been set.

### GetHeatNo

`func (o *ReceivedContainersItem) GetHeatNo() string`

GetHeatNo returns the HeatNo field if non-nil, zero value otherwise.

### GetHeatNoOk

`func (o *ReceivedContainersItem) GetHeatNoOk() (*string, bool)`

GetHeatNoOk returns a tuple with the HeatNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeatNo

`func (o *ReceivedContainersItem) SetHeatNo(v string)`

SetHeatNo sets HeatNo field to given value.

### HasHeatNo

`func (o *ReceivedContainersItem) HasHeatNo() bool`

HasHeatNo returns a boolean if a field has been set.

### GetHeatId

`func (o *ReceivedContainersItem) GetHeatId() string`

GetHeatId returns the HeatId field if non-nil, zero value otherwise.

### GetHeatIdOk

`func (o *ReceivedContainersItem) GetHeatIdOk() (*string, bool)`

GetHeatIdOk returns a tuple with the HeatId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeatId

`func (o *ReceivedContainersItem) SetHeatId(v string)`

SetHeatId sets HeatId field to given value.

### HasHeatId

`func (o *ReceivedContainersItem) HasHeatId() bool`

HasHeatId returns a boolean if a field has been set.

### GetSerialNo

`func (o *ReceivedContainersItem) GetSerialNo() string`

GetSerialNo returns the SerialNo field if non-nil, zero value otherwise.

### GetSerialNoOk

`func (o *ReceivedContainersItem) GetSerialNoOk() (*string, bool)`

GetSerialNoOk returns a tuple with the SerialNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSerialNo

`func (o *ReceivedContainersItem) SetSerialNo(v string)`

SetSerialNo sets SerialNo field to given value.

### HasSerialNo

`func (o *ReceivedContainersItem) HasSerialNo() bool`

HasSerialNo returns a boolean if a field has been set.

### GetExternalSerialNo

`func (o *ReceivedContainersItem) GetExternalSerialNo() string`

GetExternalSerialNo returns the ExternalSerialNo field if non-nil, zero value otherwise.

### GetExternalSerialNoOk

`func (o *ReceivedContainersItem) GetExternalSerialNoOk() (*string, bool)`

GetExternalSerialNoOk returns a tuple with the ExternalSerialNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalSerialNo

`func (o *ReceivedContainersItem) SetExternalSerialNo(v string)`

SetExternalSerialNo sets ExternalSerialNo field to given value.

### HasExternalSerialNo

`func (o *ReceivedContainersItem) HasExternalSerialNo() bool`

HasExternalSerialNo returns a boolean if a field has been set.

### GetQuantity

`func (o *ReceivedContainersItem) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *ReceivedContainersItem) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *ReceivedContainersItem) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *ReceivedContainersItem) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetUnit

`func (o *ReceivedContainersItem) GetUnit() string`

GetUnit returns the Unit field if non-nil, zero value otherwise.

### GetUnitOk

`func (o *ReceivedContainersItem) GetUnitOk() (*string, bool)`

GetUnitOk returns a tuple with the Unit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnit

`func (o *ReceivedContainersItem) SetUnit(v string)`

SetUnit sets Unit field to given value.

### HasUnit

`func (o *ReceivedContainersItem) HasUnit() bool`

HasUnit returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


