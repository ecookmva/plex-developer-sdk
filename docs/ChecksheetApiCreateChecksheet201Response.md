# ChecksheetApiCreateChecksheet201Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ChecksheetNo** | Pointer to **int32** | A unique Checksheet No. | [optional] 
**OutOfSpec** | Pointer to **bool** | Designation of whether the checksheet is out of spec or not. This is true if any of the measurements are out of spec. | [optional] 
**CreatedAt** | Pointer to **time.Time** | Created Date and Time of the checksheet. | [optional] 

## Methods

### NewChecksheetApiCreateChecksheet201Response

`func NewChecksheetApiCreateChecksheet201Response() *ChecksheetApiCreateChecksheet201Response`

NewChecksheetApiCreateChecksheet201Response instantiates a new ChecksheetApiCreateChecksheet201Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChecksheetApiCreateChecksheet201ResponseWithDefaults

`func NewChecksheetApiCreateChecksheet201ResponseWithDefaults() *ChecksheetApiCreateChecksheet201Response`

NewChecksheetApiCreateChecksheet201ResponseWithDefaults instantiates a new ChecksheetApiCreateChecksheet201Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetChecksheetNo

`func (o *ChecksheetApiCreateChecksheet201Response) GetChecksheetNo() int32`

GetChecksheetNo returns the ChecksheetNo field if non-nil, zero value otherwise.

### GetChecksheetNoOk

`func (o *ChecksheetApiCreateChecksheet201Response) GetChecksheetNoOk() (*int32, bool)`

GetChecksheetNoOk returns a tuple with the ChecksheetNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChecksheetNo

`func (o *ChecksheetApiCreateChecksheet201Response) SetChecksheetNo(v int32)`

SetChecksheetNo sets ChecksheetNo field to given value.

### HasChecksheetNo

`func (o *ChecksheetApiCreateChecksheet201Response) HasChecksheetNo() bool`

HasChecksheetNo returns a boolean if a field has been set.

### GetOutOfSpec

`func (o *ChecksheetApiCreateChecksheet201Response) GetOutOfSpec() bool`

GetOutOfSpec returns the OutOfSpec field if non-nil, zero value otherwise.

### GetOutOfSpecOk

`func (o *ChecksheetApiCreateChecksheet201Response) GetOutOfSpecOk() (*bool, bool)`

GetOutOfSpecOk returns a tuple with the OutOfSpec field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutOfSpec

`func (o *ChecksheetApiCreateChecksheet201Response) SetOutOfSpec(v bool)`

SetOutOfSpec sets OutOfSpec field to given value.

### HasOutOfSpec

`func (o *ChecksheetApiCreateChecksheet201Response) HasOutOfSpec() bool`

HasOutOfSpec returns a boolean if a field has been set.

### GetCreatedAt

`func (o *ChecksheetApiCreateChecksheet201Response) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ChecksheetApiCreateChecksheet201Response) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ChecksheetApiCreateChecksheet201Response) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *ChecksheetApiCreateChecksheet201Response) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


