# ProcessRoutingsApiGetSchedulingDetailsResponse

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

### NewProcessRoutingsApiGetSchedulingDetailsResponse

`func NewProcessRoutingsApiGetSchedulingDetailsResponse() *ProcessRoutingsApiGetSchedulingDetailsResponse`

NewProcessRoutingsApiGetSchedulingDetailsResponse instantiates a new ProcessRoutingsApiGetSchedulingDetailsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProcessRoutingsApiGetSchedulingDetailsResponseWithDefaults

`func NewProcessRoutingsApiGetSchedulingDetailsResponseWithDefaults() *ProcessRoutingsApiGetSchedulingDetailsResponse`

NewProcessRoutingsApiGetSchedulingDetailsResponseWithDefaults instantiates a new ProcessRoutingsApiGetSchedulingDetailsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ProcessRoutingsApiGetSchedulingDetailsResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ProcessRoutingsApiGetSchedulingDetailsResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ProcessRoutingsApiGetSchedulingDetailsResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *ProcessRoutingsApiGetSchedulingDetailsResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetScrapPercentage

`func (o *ProcessRoutingsApiGetSchedulingDetailsResponse) GetScrapPercentage() float64`

GetScrapPercentage returns the ScrapPercentage field if non-nil, zero value otherwise.

### GetScrapPercentageOk

`func (o *ProcessRoutingsApiGetSchedulingDetailsResponse) GetScrapPercentageOk() (*float64, bool)`

GetScrapPercentageOk returns a tuple with the ScrapPercentage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScrapPercentage

`func (o *ProcessRoutingsApiGetSchedulingDetailsResponse) SetScrapPercentage(v float64)`

SetScrapPercentage sets ScrapPercentage field to given value.

### HasScrapPercentage

`func (o *ProcessRoutingsApiGetSchedulingDetailsResponse) HasScrapPercentage() bool`

HasScrapPercentage returns a boolean if a field has been set.

### GetOperatorScrapPercentage

`func (o *ProcessRoutingsApiGetSchedulingDetailsResponse) GetOperatorScrapPercentage() float64`

GetOperatorScrapPercentage returns the OperatorScrapPercentage field if non-nil, zero value otherwise.

### GetOperatorScrapPercentageOk

`func (o *ProcessRoutingsApiGetSchedulingDetailsResponse) GetOperatorScrapPercentageOk() (*float64, bool)`

GetOperatorScrapPercentageOk returns a tuple with the OperatorScrapPercentage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperatorScrapPercentage

`func (o *ProcessRoutingsApiGetSchedulingDetailsResponse) SetOperatorScrapPercentage(v float64)`

SetOperatorScrapPercentage sets OperatorScrapPercentage field to given value.

### HasOperatorScrapPercentage

`func (o *ProcessRoutingsApiGetSchedulingDetailsResponse) HasOperatorScrapPercentage() bool`

HasOperatorScrapPercentage returns a boolean if a field has been set.

### GetFixedRunTimeHours

`func (o *ProcessRoutingsApiGetSchedulingDetailsResponse) GetFixedRunTimeHours() float64`

GetFixedRunTimeHours returns the FixedRunTimeHours field if non-nil, zero value otherwise.

### GetFixedRunTimeHoursOk

`func (o *ProcessRoutingsApiGetSchedulingDetailsResponse) GetFixedRunTimeHoursOk() (*float64, bool)`

GetFixedRunTimeHoursOk returns a tuple with the FixedRunTimeHours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFixedRunTimeHours

`func (o *ProcessRoutingsApiGetSchedulingDetailsResponse) SetFixedRunTimeHours(v float64)`

SetFixedRunTimeHours sets FixedRunTimeHours field to given value.

### HasFixedRunTimeHours

`func (o *ProcessRoutingsApiGetSchedulingDetailsResponse) HasFixedRunTimeHours() bool`

HasFixedRunTimeHours returns a boolean if a field has been set.

### GetDelayBeforeHours

`func (o *ProcessRoutingsApiGetSchedulingDetailsResponse) GetDelayBeforeHours() float64`

GetDelayBeforeHours returns the DelayBeforeHours field if non-nil, zero value otherwise.

### GetDelayBeforeHoursOk

`func (o *ProcessRoutingsApiGetSchedulingDetailsResponse) GetDelayBeforeHoursOk() (*float64, bool)`

GetDelayBeforeHoursOk returns a tuple with the DelayBeforeHours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDelayBeforeHours

`func (o *ProcessRoutingsApiGetSchedulingDetailsResponse) SetDelayBeforeHours(v float64)`

SetDelayBeforeHours sets DelayBeforeHours field to given value.

### HasDelayBeforeHours

`func (o *ProcessRoutingsApiGetSchedulingDetailsResponse) HasDelayBeforeHours() bool`

HasDelayBeforeHours returns a boolean if a field has been set.

### GetDelayAfterHours

`func (o *ProcessRoutingsApiGetSchedulingDetailsResponse) GetDelayAfterHours() float64`

GetDelayAfterHours returns the DelayAfterHours field if non-nil, zero value otherwise.

### GetDelayAfterHoursOk

`func (o *ProcessRoutingsApiGetSchedulingDetailsResponse) GetDelayAfterHoursOk() (*float64, bool)`

GetDelayAfterHoursOk returns a tuple with the DelayAfterHours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDelayAfterHours

`func (o *ProcessRoutingsApiGetSchedulingDetailsResponse) SetDelayAfterHours(v float64)`

SetDelayAfterHours sets DelayAfterHours field to given value.

### HasDelayAfterHours

`func (o *ProcessRoutingsApiGetSchedulingDetailsResponse) HasDelayAfterHours() bool`

HasDelayAfterHours returns a boolean if a field has been set.

### GetDelayReason

`func (o *ProcessRoutingsApiGetSchedulingDetailsResponse) GetDelayReason() string`

GetDelayReason returns the DelayReason field if non-nil, zero value otherwise.

### GetDelayReasonOk

`func (o *ProcessRoutingsApiGetSchedulingDetailsResponse) GetDelayReasonOk() (*string, bool)`

GetDelayReasonOk returns a tuple with the DelayReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDelayReason

`func (o *ProcessRoutingsApiGetSchedulingDetailsResponse) SetDelayReason(v string)`

SetDelayReason sets DelayReason field to given value.

### HasDelayReason

`func (o *ProcessRoutingsApiGetSchedulingDetailsResponse) HasDelayReason() bool`

HasDelayReason returns a boolean if a field has been set.

### GetOverlapPercentage

`func (o *ProcessRoutingsApiGetSchedulingDetailsResponse) GetOverlapPercentage() float64`

GetOverlapPercentage returns the OverlapPercentage field if non-nil, zero value otherwise.

### GetOverlapPercentageOk

`func (o *ProcessRoutingsApiGetSchedulingDetailsResponse) GetOverlapPercentageOk() (*float64, bool)`

GetOverlapPercentageOk returns a tuple with the OverlapPercentage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOverlapPercentage

`func (o *ProcessRoutingsApiGetSchedulingDetailsResponse) SetOverlapPercentage(v float64)`

SetOverlapPercentage sets OverlapPercentage field to given value.

### HasOverlapPercentage

`func (o *ProcessRoutingsApiGetSchedulingDetailsResponse) HasOverlapPercentage() bool`

HasOverlapPercentage returns a boolean if a field has been set.

### GetOverlapQuantity

`func (o *ProcessRoutingsApiGetSchedulingDetailsResponse) GetOverlapQuantity() int32`

GetOverlapQuantity returns the OverlapQuantity field if non-nil, zero value otherwise.

### GetOverlapQuantityOk

`func (o *ProcessRoutingsApiGetSchedulingDetailsResponse) GetOverlapQuantityOk() (*int32, bool)`

GetOverlapQuantityOk returns a tuple with the OverlapQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOverlapQuantity

`func (o *ProcessRoutingsApiGetSchedulingDetailsResponse) SetOverlapQuantity(v int32)`

SetOverlapQuantity sets OverlapQuantity field to given value.

### HasOverlapQuantity

`func (o *ProcessRoutingsApiGetSchedulingDetailsResponse) HasOverlapQuantity() bool`

HasOverlapQuantity returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


