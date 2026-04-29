# ProcessRoutingsApiUpdateSchedulingDetailsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | A unique identifier for the Part Operation. | [optional] 
**ScrapPercentage** | Pointer to **float64** | The scrap percentage for the Part Operation. | [optional] 
**OperatorScrapPercentage** | Pointer to **float64** | The Operator Scrap percentage for the Part Operation. | [optional] 
**FixedRunTimeHours** | Pointer to **float64** | Fixed Runtime Houses for the Part Operation. | [optional] 
**DelayBeforeHours** | Pointer to **float64** | Delay before hours for the Part Operation. | [optional] 
**DelayAfterHours** | Pointer to **float64** | Delay after house for the Part Operation. | [optional] 
**DelayReason** | Pointer to **string** | Delay reason for the Part Operation. | [optional] 
**OverlapPercentage** | Pointer to **float64** | Overlap percentage for the Part Operation. | [optional] 
**OverlapQuantity** | Pointer to **int32** | Overlap Quantity for the Part Operation. | [optional] 

## Methods

### NewProcessRoutingsApiUpdateSchedulingDetailsResponse

`func NewProcessRoutingsApiUpdateSchedulingDetailsResponse() *ProcessRoutingsApiUpdateSchedulingDetailsResponse`

NewProcessRoutingsApiUpdateSchedulingDetailsResponse instantiates a new ProcessRoutingsApiUpdateSchedulingDetailsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProcessRoutingsApiUpdateSchedulingDetailsResponseWithDefaults

`func NewProcessRoutingsApiUpdateSchedulingDetailsResponseWithDefaults() *ProcessRoutingsApiUpdateSchedulingDetailsResponse`

NewProcessRoutingsApiUpdateSchedulingDetailsResponseWithDefaults instantiates a new ProcessRoutingsApiUpdateSchedulingDetailsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetScrapPercentage

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsResponse) GetScrapPercentage() float64`

GetScrapPercentage returns the ScrapPercentage field if non-nil, zero value otherwise.

### GetScrapPercentageOk

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsResponse) GetScrapPercentageOk() (*float64, bool)`

GetScrapPercentageOk returns a tuple with the ScrapPercentage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScrapPercentage

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsResponse) SetScrapPercentage(v float64)`

SetScrapPercentage sets ScrapPercentage field to given value.

### HasScrapPercentage

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsResponse) HasScrapPercentage() bool`

HasScrapPercentage returns a boolean if a field has been set.

### GetOperatorScrapPercentage

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsResponse) GetOperatorScrapPercentage() float64`

GetOperatorScrapPercentage returns the OperatorScrapPercentage field if non-nil, zero value otherwise.

### GetOperatorScrapPercentageOk

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsResponse) GetOperatorScrapPercentageOk() (*float64, bool)`

GetOperatorScrapPercentageOk returns a tuple with the OperatorScrapPercentage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperatorScrapPercentage

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsResponse) SetOperatorScrapPercentage(v float64)`

SetOperatorScrapPercentage sets OperatorScrapPercentage field to given value.

### HasOperatorScrapPercentage

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsResponse) HasOperatorScrapPercentage() bool`

HasOperatorScrapPercentage returns a boolean if a field has been set.

### GetFixedRunTimeHours

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsResponse) GetFixedRunTimeHours() float64`

GetFixedRunTimeHours returns the FixedRunTimeHours field if non-nil, zero value otherwise.

### GetFixedRunTimeHoursOk

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsResponse) GetFixedRunTimeHoursOk() (*float64, bool)`

GetFixedRunTimeHoursOk returns a tuple with the FixedRunTimeHours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFixedRunTimeHours

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsResponse) SetFixedRunTimeHours(v float64)`

SetFixedRunTimeHours sets FixedRunTimeHours field to given value.

### HasFixedRunTimeHours

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsResponse) HasFixedRunTimeHours() bool`

HasFixedRunTimeHours returns a boolean if a field has been set.

### GetDelayBeforeHours

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsResponse) GetDelayBeforeHours() float64`

GetDelayBeforeHours returns the DelayBeforeHours field if non-nil, zero value otherwise.

### GetDelayBeforeHoursOk

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsResponse) GetDelayBeforeHoursOk() (*float64, bool)`

GetDelayBeforeHoursOk returns a tuple with the DelayBeforeHours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDelayBeforeHours

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsResponse) SetDelayBeforeHours(v float64)`

SetDelayBeforeHours sets DelayBeforeHours field to given value.

### HasDelayBeforeHours

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsResponse) HasDelayBeforeHours() bool`

HasDelayBeforeHours returns a boolean if a field has been set.

### GetDelayAfterHours

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsResponse) GetDelayAfterHours() float64`

GetDelayAfterHours returns the DelayAfterHours field if non-nil, zero value otherwise.

### GetDelayAfterHoursOk

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsResponse) GetDelayAfterHoursOk() (*float64, bool)`

GetDelayAfterHoursOk returns a tuple with the DelayAfterHours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDelayAfterHours

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsResponse) SetDelayAfterHours(v float64)`

SetDelayAfterHours sets DelayAfterHours field to given value.

### HasDelayAfterHours

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsResponse) HasDelayAfterHours() bool`

HasDelayAfterHours returns a boolean if a field has been set.

### GetDelayReason

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsResponse) GetDelayReason() string`

GetDelayReason returns the DelayReason field if non-nil, zero value otherwise.

### GetDelayReasonOk

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsResponse) GetDelayReasonOk() (*string, bool)`

GetDelayReasonOk returns a tuple with the DelayReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDelayReason

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsResponse) SetDelayReason(v string)`

SetDelayReason sets DelayReason field to given value.

### HasDelayReason

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsResponse) HasDelayReason() bool`

HasDelayReason returns a boolean if a field has been set.

### GetOverlapPercentage

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsResponse) GetOverlapPercentage() float64`

GetOverlapPercentage returns the OverlapPercentage field if non-nil, zero value otherwise.

### GetOverlapPercentageOk

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsResponse) GetOverlapPercentageOk() (*float64, bool)`

GetOverlapPercentageOk returns a tuple with the OverlapPercentage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOverlapPercentage

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsResponse) SetOverlapPercentage(v float64)`

SetOverlapPercentage sets OverlapPercentage field to given value.

### HasOverlapPercentage

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsResponse) HasOverlapPercentage() bool`

HasOverlapPercentage returns a boolean if a field has been set.

### GetOverlapQuantity

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsResponse) GetOverlapQuantity() int32`

GetOverlapQuantity returns the OverlapQuantity field if non-nil, zero value otherwise.

### GetOverlapQuantityOk

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsResponse) GetOverlapQuantityOk() (*int32, bool)`

GetOverlapQuantityOk returns a tuple with the OverlapQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOverlapQuantity

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsResponse) SetOverlapQuantity(v int32)`

SetOverlapQuantity sets OverlapQuantity field to given value.

### HasOverlapQuantity

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsResponse) HasOverlapQuantity() bool`

HasOverlapQuantity returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


