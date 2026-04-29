# TrialBalancesApiGetTrialBalanceResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**UnclosedPriorYearProfitLoss** | Pointer to **float64** | Identifies an unclosed prior year profit loss amount if applicable. | [optional] 
**TrialBalanceLines** | Pointer to [**[]TrialBalanceLinesItem**](TrialBalanceLinesItem.md) | A list of trial balance lines. | [optional] 

## Methods

### NewTrialBalancesApiGetTrialBalanceResponse

`func NewTrialBalancesApiGetTrialBalanceResponse() *TrialBalancesApiGetTrialBalanceResponse`

NewTrialBalancesApiGetTrialBalanceResponse instantiates a new TrialBalancesApiGetTrialBalanceResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrialBalancesApiGetTrialBalanceResponseWithDefaults

`func NewTrialBalancesApiGetTrialBalanceResponseWithDefaults() *TrialBalancesApiGetTrialBalanceResponse`

NewTrialBalancesApiGetTrialBalanceResponseWithDefaults instantiates a new TrialBalancesApiGetTrialBalanceResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUnclosedPriorYearProfitLoss

`func (o *TrialBalancesApiGetTrialBalanceResponse) GetUnclosedPriorYearProfitLoss() float64`

GetUnclosedPriorYearProfitLoss returns the UnclosedPriorYearProfitLoss field if non-nil, zero value otherwise.

### GetUnclosedPriorYearProfitLossOk

`func (o *TrialBalancesApiGetTrialBalanceResponse) GetUnclosedPriorYearProfitLossOk() (*float64, bool)`

GetUnclosedPriorYearProfitLossOk returns a tuple with the UnclosedPriorYearProfitLoss field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnclosedPriorYearProfitLoss

`func (o *TrialBalancesApiGetTrialBalanceResponse) SetUnclosedPriorYearProfitLoss(v float64)`

SetUnclosedPriorYearProfitLoss sets UnclosedPriorYearProfitLoss field to given value.

### HasUnclosedPriorYearProfitLoss

`func (o *TrialBalancesApiGetTrialBalanceResponse) HasUnclosedPriorYearProfitLoss() bool`

HasUnclosedPriorYearProfitLoss returns a boolean if a field has been set.

### GetTrialBalanceLines

`func (o *TrialBalancesApiGetTrialBalanceResponse) GetTrialBalanceLines() []TrialBalanceLinesItem`

GetTrialBalanceLines returns the TrialBalanceLines field if non-nil, zero value otherwise.

### GetTrialBalanceLinesOk

`func (o *TrialBalancesApiGetTrialBalanceResponse) GetTrialBalanceLinesOk() (*[]TrialBalanceLinesItem, bool)`

GetTrialBalanceLinesOk returns a tuple with the TrialBalanceLines field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrialBalanceLines

`func (o *TrialBalancesApiGetTrialBalanceResponse) SetTrialBalanceLines(v []TrialBalanceLinesItem)`

SetTrialBalanceLines sets TrialBalanceLines field to given value.

### HasTrialBalanceLines

`func (o *TrialBalancesApiGetTrialBalanceResponse) HasTrialBalanceLines() bool`

HasTrialBalanceLines returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


