# ProcessRoutingsApiUpdateSchedulingDetailsRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ScrapPercentage** | Pointer to **float64** | Scrap percentage of the Part Operation. | [optional] 
**OperatorScrapPercentage** | Pointer to **float64** | Operator Scrap Percentage of the Part Operation. | [optional] 
**FixedRunTimeHours** | Pointer to **float64** | Fixed run time hours of the Part Operation. | [optional] 
**DelayBeforeHours** | Pointer to **float64** | Delay before hours of the Part Operation. | [optional] 
**DelayAfterHours** | Pointer to **float64** | Delay after hours of the Part Operation. | [optional] 
**DelayReason** | Pointer to **string** | Delay reason of the Part Operation. | [optional] 
**OverlapPercentage** | Pointer to **float64** | Overlap percentage of the Part Operation. | [optional] 
**OverlapQuantity** | Pointer to **int32** | Overlap quantity of the Part Operation. | [optional] 

## Methods

### NewProcessRoutingsApiUpdateSchedulingDetailsRequest

`func NewProcessRoutingsApiUpdateSchedulingDetailsRequest() *ProcessRoutingsApiUpdateSchedulingDetailsRequest`

NewProcessRoutingsApiUpdateSchedulingDetailsRequest instantiates a new ProcessRoutingsApiUpdateSchedulingDetailsRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProcessRoutingsApiUpdateSchedulingDetailsRequestWithDefaults

`func NewProcessRoutingsApiUpdateSchedulingDetailsRequestWithDefaults() *ProcessRoutingsApiUpdateSchedulingDetailsRequest`

NewProcessRoutingsApiUpdateSchedulingDetailsRequestWithDefaults instantiates a new ProcessRoutingsApiUpdateSchedulingDetailsRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetScrapPercentage

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsRequest) GetScrapPercentage() float64`

GetScrapPercentage returns the ScrapPercentage field if non-nil, zero value otherwise.

### GetScrapPercentageOk

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsRequest) GetScrapPercentageOk() (*float64, bool)`

GetScrapPercentageOk returns a tuple with the ScrapPercentage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScrapPercentage

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsRequest) SetScrapPercentage(v float64)`

SetScrapPercentage sets ScrapPercentage field to given value.

### HasScrapPercentage

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsRequest) HasScrapPercentage() bool`

HasScrapPercentage returns a boolean if a field has been set.

### GetOperatorScrapPercentage

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsRequest) GetOperatorScrapPercentage() float64`

GetOperatorScrapPercentage returns the OperatorScrapPercentage field if non-nil, zero value otherwise.

### GetOperatorScrapPercentageOk

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsRequest) GetOperatorScrapPercentageOk() (*float64, bool)`

GetOperatorScrapPercentageOk returns a tuple with the OperatorScrapPercentage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperatorScrapPercentage

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsRequest) SetOperatorScrapPercentage(v float64)`

SetOperatorScrapPercentage sets OperatorScrapPercentage field to given value.

### HasOperatorScrapPercentage

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsRequest) HasOperatorScrapPercentage() bool`

HasOperatorScrapPercentage returns a boolean if a field has been set.

### GetFixedRunTimeHours

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsRequest) GetFixedRunTimeHours() float64`

GetFixedRunTimeHours returns the FixedRunTimeHours field if non-nil, zero value otherwise.

### GetFixedRunTimeHoursOk

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsRequest) GetFixedRunTimeHoursOk() (*float64, bool)`

GetFixedRunTimeHoursOk returns a tuple with the FixedRunTimeHours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFixedRunTimeHours

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsRequest) SetFixedRunTimeHours(v float64)`

SetFixedRunTimeHours sets FixedRunTimeHours field to given value.

### HasFixedRunTimeHours

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsRequest) HasFixedRunTimeHours() bool`

HasFixedRunTimeHours returns a boolean if a field has been set.

### GetDelayBeforeHours

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsRequest) GetDelayBeforeHours() float64`

GetDelayBeforeHours returns the DelayBeforeHours field if non-nil, zero value otherwise.

### GetDelayBeforeHoursOk

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsRequest) GetDelayBeforeHoursOk() (*float64, bool)`

GetDelayBeforeHoursOk returns a tuple with the DelayBeforeHours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDelayBeforeHours

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsRequest) SetDelayBeforeHours(v float64)`

SetDelayBeforeHours sets DelayBeforeHours field to given value.

### HasDelayBeforeHours

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsRequest) HasDelayBeforeHours() bool`

HasDelayBeforeHours returns a boolean if a field has been set.

### GetDelayAfterHours

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsRequest) GetDelayAfterHours() float64`

GetDelayAfterHours returns the DelayAfterHours field if non-nil, zero value otherwise.

### GetDelayAfterHoursOk

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsRequest) GetDelayAfterHoursOk() (*float64, bool)`

GetDelayAfterHoursOk returns a tuple with the DelayAfterHours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDelayAfterHours

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsRequest) SetDelayAfterHours(v float64)`

SetDelayAfterHours sets DelayAfterHours field to given value.

### HasDelayAfterHours

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsRequest) HasDelayAfterHours() bool`

HasDelayAfterHours returns a boolean if a field has been set.

### GetDelayReason

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsRequest) GetDelayReason() string`

GetDelayReason returns the DelayReason field if non-nil, zero value otherwise.

### GetDelayReasonOk

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsRequest) GetDelayReasonOk() (*string, bool)`

GetDelayReasonOk returns a tuple with the DelayReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDelayReason

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsRequest) SetDelayReason(v string)`

SetDelayReason sets DelayReason field to given value.

### HasDelayReason

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsRequest) HasDelayReason() bool`

HasDelayReason returns a boolean if a field has been set.

### GetOverlapPercentage

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsRequest) GetOverlapPercentage() float64`

GetOverlapPercentage returns the OverlapPercentage field if non-nil, zero value otherwise.

### GetOverlapPercentageOk

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsRequest) GetOverlapPercentageOk() (*float64, bool)`

GetOverlapPercentageOk returns a tuple with the OverlapPercentage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOverlapPercentage

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsRequest) SetOverlapPercentage(v float64)`

SetOverlapPercentage sets OverlapPercentage field to given value.

### HasOverlapPercentage

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsRequest) HasOverlapPercentage() bool`

HasOverlapPercentage returns a boolean if a field has been set.

### GetOverlapQuantity

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsRequest) GetOverlapQuantity() int32`

GetOverlapQuantity returns the OverlapQuantity field if non-nil, zero value otherwise.

### GetOverlapQuantityOk

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsRequest) GetOverlapQuantityOk() (*int32, bool)`

GetOverlapQuantityOk returns a tuple with the OverlapQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOverlapQuantity

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsRequest) SetOverlapQuantity(v int32)`

SetOverlapQuantity sets OverlapQuantity field to given value.

### HasOverlapQuantity

`func (o *ProcessRoutingsApiUpdateSchedulingDetailsRequest) HasOverlapQuantity() bool`

HasOverlapQuantity returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


