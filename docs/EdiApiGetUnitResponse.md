# EdiApiGetUnitResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | A unique identifier for the unit. | [optional] 
**Unit** | Pointer to **string** | The unique name of the actual unit. | [optional] 
**DenominatorUnit** | Pointer to **string** | The Denominator label is used whenever the Unit is required in the denominator of an equation. | [optional] 
**EdiCode** | Pointer to **string** | The code in an EDI document that represents the unit. | [optional] 
**WeightUnit** | Pointer to **bool** | True if this unit is used for weight. | [optional] 
**PieceUnit** | Pointer to **bool** | True if this unit is used for Pieces. | [optional] 
**HourUnit** | Pointer to **bool** | True if this unit is used for Hours. | [optional] 
**DayUnit** | Pointer to **bool** | True if this unit is used for calendar Days. | [optional] 
**WeekUnit** | Pointer to **bool** | True if this unit is used for calendar Weeks. | [optional] 
**MonthUnit** | Pointer to **bool** | True if this unit is used for calendar Months. | [optional] 
**YearUnit** | Pointer to **bool** | True if this unit is used for calendar Years. | [optional] 
**UnitStandard** | Pointer to **string** | The standard of the unit. | [optional] 
**AreaUnit** | Pointer to **bool** | True if this unit is used for Area measurement. | [optional] 
**Reference** | Pointer to **string** | Reference | [optional] 

## Methods

### NewEdiApiGetUnitResponse

`func NewEdiApiGetUnitResponse() *EdiApiGetUnitResponse`

NewEdiApiGetUnitResponse instantiates a new EdiApiGetUnitResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEdiApiGetUnitResponseWithDefaults

`func NewEdiApiGetUnitResponseWithDefaults() *EdiApiGetUnitResponse`

NewEdiApiGetUnitResponseWithDefaults instantiates a new EdiApiGetUnitResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *EdiApiGetUnitResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *EdiApiGetUnitResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *EdiApiGetUnitResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *EdiApiGetUnitResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetUnit

`func (o *EdiApiGetUnitResponse) GetUnit() string`

GetUnit returns the Unit field if non-nil, zero value otherwise.

### GetUnitOk

`func (o *EdiApiGetUnitResponse) GetUnitOk() (*string, bool)`

GetUnitOk returns a tuple with the Unit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnit

`func (o *EdiApiGetUnitResponse) SetUnit(v string)`

SetUnit sets Unit field to given value.

### HasUnit

`func (o *EdiApiGetUnitResponse) HasUnit() bool`

HasUnit returns a boolean if a field has been set.

### GetDenominatorUnit

`func (o *EdiApiGetUnitResponse) GetDenominatorUnit() string`

GetDenominatorUnit returns the DenominatorUnit field if non-nil, zero value otherwise.

### GetDenominatorUnitOk

`func (o *EdiApiGetUnitResponse) GetDenominatorUnitOk() (*string, bool)`

GetDenominatorUnitOk returns a tuple with the DenominatorUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDenominatorUnit

`func (o *EdiApiGetUnitResponse) SetDenominatorUnit(v string)`

SetDenominatorUnit sets DenominatorUnit field to given value.

### HasDenominatorUnit

`func (o *EdiApiGetUnitResponse) HasDenominatorUnit() bool`

HasDenominatorUnit returns a boolean if a field has been set.

### GetEdiCode

`func (o *EdiApiGetUnitResponse) GetEdiCode() string`

GetEdiCode returns the EdiCode field if non-nil, zero value otherwise.

### GetEdiCodeOk

`func (o *EdiApiGetUnitResponse) GetEdiCodeOk() (*string, bool)`

GetEdiCodeOk returns a tuple with the EdiCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEdiCode

`func (o *EdiApiGetUnitResponse) SetEdiCode(v string)`

SetEdiCode sets EdiCode field to given value.

### HasEdiCode

`func (o *EdiApiGetUnitResponse) HasEdiCode() bool`

HasEdiCode returns a boolean if a field has been set.

### GetWeightUnit

`func (o *EdiApiGetUnitResponse) GetWeightUnit() bool`

GetWeightUnit returns the WeightUnit field if non-nil, zero value otherwise.

### GetWeightUnitOk

`func (o *EdiApiGetUnitResponse) GetWeightUnitOk() (*bool, bool)`

GetWeightUnitOk returns a tuple with the WeightUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeightUnit

`func (o *EdiApiGetUnitResponse) SetWeightUnit(v bool)`

SetWeightUnit sets WeightUnit field to given value.

### HasWeightUnit

`func (o *EdiApiGetUnitResponse) HasWeightUnit() bool`

HasWeightUnit returns a boolean if a field has been set.

### GetPieceUnit

`func (o *EdiApiGetUnitResponse) GetPieceUnit() bool`

GetPieceUnit returns the PieceUnit field if non-nil, zero value otherwise.

### GetPieceUnitOk

`func (o *EdiApiGetUnitResponse) GetPieceUnitOk() (*bool, bool)`

GetPieceUnitOk returns a tuple with the PieceUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPieceUnit

`func (o *EdiApiGetUnitResponse) SetPieceUnit(v bool)`

SetPieceUnit sets PieceUnit field to given value.

### HasPieceUnit

`func (o *EdiApiGetUnitResponse) HasPieceUnit() bool`

HasPieceUnit returns a boolean if a field has been set.

### GetHourUnit

`func (o *EdiApiGetUnitResponse) GetHourUnit() bool`

GetHourUnit returns the HourUnit field if non-nil, zero value otherwise.

### GetHourUnitOk

`func (o *EdiApiGetUnitResponse) GetHourUnitOk() (*bool, bool)`

GetHourUnitOk returns a tuple with the HourUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHourUnit

`func (o *EdiApiGetUnitResponse) SetHourUnit(v bool)`

SetHourUnit sets HourUnit field to given value.

### HasHourUnit

`func (o *EdiApiGetUnitResponse) HasHourUnit() bool`

HasHourUnit returns a boolean if a field has been set.

### GetDayUnit

`func (o *EdiApiGetUnitResponse) GetDayUnit() bool`

GetDayUnit returns the DayUnit field if non-nil, zero value otherwise.

### GetDayUnitOk

`func (o *EdiApiGetUnitResponse) GetDayUnitOk() (*bool, bool)`

GetDayUnitOk returns a tuple with the DayUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDayUnit

`func (o *EdiApiGetUnitResponse) SetDayUnit(v bool)`

SetDayUnit sets DayUnit field to given value.

### HasDayUnit

`func (o *EdiApiGetUnitResponse) HasDayUnit() bool`

HasDayUnit returns a boolean if a field has been set.

### GetWeekUnit

`func (o *EdiApiGetUnitResponse) GetWeekUnit() bool`

GetWeekUnit returns the WeekUnit field if non-nil, zero value otherwise.

### GetWeekUnitOk

`func (o *EdiApiGetUnitResponse) GetWeekUnitOk() (*bool, bool)`

GetWeekUnitOk returns a tuple with the WeekUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeekUnit

`func (o *EdiApiGetUnitResponse) SetWeekUnit(v bool)`

SetWeekUnit sets WeekUnit field to given value.

### HasWeekUnit

`func (o *EdiApiGetUnitResponse) HasWeekUnit() bool`

HasWeekUnit returns a boolean if a field has been set.

### GetMonthUnit

`func (o *EdiApiGetUnitResponse) GetMonthUnit() bool`

GetMonthUnit returns the MonthUnit field if non-nil, zero value otherwise.

### GetMonthUnitOk

`func (o *EdiApiGetUnitResponse) GetMonthUnitOk() (*bool, bool)`

GetMonthUnitOk returns a tuple with the MonthUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonthUnit

`func (o *EdiApiGetUnitResponse) SetMonthUnit(v bool)`

SetMonthUnit sets MonthUnit field to given value.

### HasMonthUnit

`func (o *EdiApiGetUnitResponse) HasMonthUnit() bool`

HasMonthUnit returns a boolean if a field has been set.

### GetYearUnit

`func (o *EdiApiGetUnitResponse) GetYearUnit() bool`

GetYearUnit returns the YearUnit field if non-nil, zero value otherwise.

### GetYearUnitOk

`func (o *EdiApiGetUnitResponse) GetYearUnitOk() (*bool, bool)`

GetYearUnitOk returns a tuple with the YearUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYearUnit

`func (o *EdiApiGetUnitResponse) SetYearUnit(v bool)`

SetYearUnit sets YearUnit field to given value.

### HasYearUnit

`func (o *EdiApiGetUnitResponse) HasYearUnit() bool`

HasYearUnit returns a boolean if a field has been set.

### GetUnitStandard

`func (o *EdiApiGetUnitResponse) GetUnitStandard() string`

GetUnitStandard returns the UnitStandard field if non-nil, zero value otherwise.

### GetUnitStandardOk

`func (o *EdiApiGetUnitResponse) GetUnitStandardOk() (*string, bool)`

GetUnitStandardOk returns a tuple with the UnitStandard field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitStandard

`func (o *EdiApiGetUnitResponse) SetUnitStandard(v string)`

SetUnitStandard sets UnitStandard field to given value.

### HasUnitStandard

`func (o *EdiApiGetUnitResponse) HasUnitStandard() bool`

HasUnitStandard returns a boolean if a field has been set.

### GetAreaUnit

`func (o *EdiApiGetUnitResponse) GetAreaUnit() bool`

GetAreaUnit returns the AreaUnit field if non-nil, zero value otherwise.

### GetAreaUnitOk

`func (o *EdiApiGetUnitResponse) GetAreaUnitOk() (*bool, bool)`

GetAreaUnitOk returns a tuple with the AreaUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAreaUnit

`func (o *EdiApiGetUnitResponse) SetAreaUnit(v bool)`

SetAreaUnit sets AreaUnit field to given value.

### HasAreaUnit

`func (o *EdiApiGetUnitResponse) HasAreaUnit() bool`

HasAreaUnit returns a boolean if a field has been set.

### GetReference

`func (o *EdiApiGetUnitResponse) GetReference() string`

GetReference returns the Reference field if non-nil, zero value otherwise.

### GetReferenceOk

`func (o *EdiApiGetUnitResponse) GetReferenceOk() (*string, bool)`

GetReferenceOk returns a tuple with the Reference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReference

`func (o *EdiApiGetUnitResponse) SetReference(v string)`

SetReference sets Reference field to given value.

### HasReference

`func (o *EdiApiGetUnitResponse) HasReference() bool`

HasReference returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


