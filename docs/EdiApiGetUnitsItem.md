# EdiApiGetUnitsItem

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

### NewEdiApiGetUnitsItem

`func NewEdiApiGetUnitsItem() *EdiApiGetUnitsItem`

NewEdiApiGetUnitsItem instantiates a new EdiApiGetUnitsItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEdiApiGetUnitsItemWithDefaults

`func NewEdiApiGetUnitsItemWithDefaults() *EdiApiGetUnitsItem`

NewEdiApiGetUnitsItemWithDefaults instantiates a new EdiApiGetUnitsItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *EdiApiGetUnitsItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *EdiApiGetUnitsItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *EdiApiGetUnitsItem) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *EdiApiGetUnitsItem) HasId() bool`

HasId returns a boolean if a field has been set.

### GetUnit

`func (o *EdiApiGetUnitsItem) GetUnit() string`

GetUnit returns the Unit field if non-nil, zero value otherwise.

### GetUnitOk

`func (o *EdiApiGetUnitsItem) GetUnitOk() (*string, bool)`

GetUnitOk returns a tuple with the Unit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnit

`func (o *EdiApiGetUnitsItem) SetUnit(v string)`

SetUnit sets Unit field to given value.

### HasUnit

`func (o *EdiApiGetUnitsItem) HasUnit() bool`

HasUnit returns a boolean if a field has been set.

### GetDenominatorUnit

`func (o *EdiApiGetUnitsItem) GetDenominatorUnit() string`

GetDenominatorUnit returns the DenominatorUnit field if non-nil, zero value otherwise.

### GetDenominatorUnitOk

`func (o *EdiApiGetUnitsItem) GetDenominatorUnitOk() (*string, bool)`

GetDenominatorUnitOk returns a tuple with the DenominatorUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDenominatorUnit

`func (o *EdiApiGetUnitsItem) SetDenominatorUnit(v string)`

SetDenominatorUnit sets DenominatorUnit field to given value.

### HasDenominatorUnit

`func (o *EdiApiGetUnitsItem) HasDenominatorUnit() bool`

HasDenominatorUnit returns a boolean if a field has been set.

### GetEdiCode

`func (o *EdiApiGetUnitsItem) GetEdiCode() string`

GetEdiCode returns the EdiCode field if non-nil, zero value otherwise.

### GetEdiCodeOk

`func (o *EdiApiGetUnitsItem) GetEdiCodeOk() (*string, bool)`

GetEdiCodeOk returns a tuple with the EdiCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEdiCode

`func (o *EdiApiGetUnitsItem) SetEdiCode(v string)`

SetEdiCode sets EdiCode field to given value.

### HasEdiCode

`func (o *EdiApiGetUnitsItem) HasEdiCode() bool`

HasEdiCode returns a boolean if a field has been set.

### GetWeightUnit

`func (o *EdiApiGetUnitsItem) GetWeightUnit() bool`

GetWeightUnit returns the WeightUnit field if non-nil, zero value otherwise.

### GetWeightUnitOk

`func (o *EdiApiGetUnitsItem) GetWeightUnitOk() (*bool, bool)`

GetWeightUnitOk returns a tuple with the WeightUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeightUnit

`func (o *EdiApiGetUnitsItem) SetWeightUnit(v bool)`

SetWeightUnit sets WeightUnit field to given value.

### HasWeightUnit

`func (o *EdiApiGetUnitsItem) HasWeightUnit() bool`

HasWeightUnit returns a boolean if a field has been set.

### GetPieceUnit

`func (o *EdiApiGetUnitsItem) GetPieceUnit() bool`

GetPieceUnit returns the PieceUnit field if non-nil, zero value otherwise.

### GetPieceUnitOk

`func (o *EdiApiGetUnitsItem) GetPieceUnitOk() (*bool, bool)`

GetPieceUnitOk returns a tuple with the PieceUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPieceUnit

`func (o *EdiApiGetUnitsItem) SetPieceUnit(v bool)`

SetPieceUnit sets PieceUnit field to given value.

### HasPieceUnit

`func (o *EdiApiGetUnitsItem) HasPieceUnit() bool`

HasPieceUnit returns a boolean if a field has been set.

### GetHourUnit

`func (o *EdiApiGetUnitsItem) GetHourUnit() bool`

GetHourUnit returns the HourUnit field if non-nil, zero value otherwise.

### GetHourUnitOk

`func (o *EdiApiGetUnitsItem) GetHourUnitOk() (*bool, bool)`

GetHourUnitOk returns a tuple with the HourUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHourUnit

`func (o *EdiApiGetUnitsItem) SetHourUnit(v bool)`

SetHourUnit sets HourUnit field to given value.

### HasHourUnit

`func (o *EdiApiGetUnitsItem) HasHourUnit() bool`

HasHourUnit returns a boolean if a field has been set.

### GetDayUnit

`func (o *EdiApiGetUnitsItem) GetDayUnit() bool`

GetDayUnit returns the DayUnit field if non-nil, zero value otherwise.

### GetDayUnitOk

`func (o *EdiApiGetUnitsItem) GetDayUnitOk() (*bool, bool)`

GetDayUnitOk returns a tuple with the DayUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDayUnit

`func (o *EdiApiGetUnitsItem) SetDayUnit(v bool)`

SetDayUnit sets DayUnit field to given value.

### HasDayUnit

`func (o *EdiApiGetUnitsItem) HasDayUnit() bool`

HasDayUnit returns a boolean if a field has been set.

### GetWeekUnit

`func (o *EdiApiGetUnitsItem) GetWeekUnit() bool`

GetWeekUnit returns the WeekUnit field if non-nil, zero value otherwise.

### GetWeekUnitOk

`func (o *EdiApiGetUnitsItem) GetWeekUnitOk() (*bool, bool)`

GetWeekUnitOk returns a tuple with the WeekUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeekUnit

`func (o *EdiApiGetUnitsItem) SetWeekUnit(v bool)`

SetWeekUnit sets WeekUnit field to given value.

### HasWeekUnit

`func (o *EdiApiGetUnitsItem) HasWeekUnit() bool`

HasWeekUnit returns a boolean if a field has been set.

### GetMonthUnit

`func (o *EdiApiGetUnitsItem) GetMonthUnit() bool`

GetMonthUnit returns the MonthUnit field if non-nil, zero value otherwise.

### GetMonthUnitOk

`func (o *EdiApiGetUnitsItem) GetMonthUnitOk() (*bool, bool)`

GetMonthUnitOk returns a tuple with the MonthUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonthUnit

`func (o *EdiApiGetUnitsItem) SetMonthUnit(v bool)`

SetMonthUnit sets MonthUnit field to given value.

### HasMonthUnit

`func (o *EdiApiGetUnitsItem) HasMonthUnit() bool`

HasMonthUnit returns a boolean if a field has been set.

### GetYearUnit

`func (o *EdiApiGetUnitsItem) GetYearUnit() bool`

GetYearUnit returns the YearUnit field if non-nil, zero value otherwise.

### GetYearUnitOk

`func (o *EdiApiGetUnitsItem) GetYearUnitOk() (*bool, bool)`

GetYearUnitOk returns a tuple with the YearUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYearUnit

`func (o *EdiApiGetUnitsItem) SetYearUnit(v bool)`

SetYearUnit sets YearUnit field to given value.

### HasYearUnit

`func (o *EdiApiGetUnitsItem) HasYearUnit() bool`

HasYearUnit returns a boolean if a field has been set.

### GetUnitStandard

`func (o *EdiApiGetUnitsItem) GetUnitStandard() string`

GetUnitStandard returns the UnitStandard field if non-nil, zero value otherwise.

### GetUnitStandardOk

`func (o *EdiApiGetUnitsItem) GetUnitStandardOk() (*string, bool)`

GetUnitStandardOk returns a tuple with the UnitStandard field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitStandard

`func (o *EdiApiGetUnitsItem) SetUnitStandard(v string)`

SetUnitStandard sets UnitStandard field to given value.

### HasUnitStandard

`func (o *EdiApiGetUnitsItem) HasUnitStandard() bool`

HasUnitStandard returns a boolean if a field has been set.

### GetAreaUnit

`func (o *EdiApiGetUnitsItem) GetAreaUnit() bool`

GetAreaUnit returns the AreaUnit field if non-nil, zero value otherwise.

### GetAreaUnitOk

`func (o *EdiApiGetUnitsItem) GetAreaUnitOk() (*bool, bool)`

GetAreaUnitOk returns a tuple with the AreaUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAreaUnit

`func (o *EdiApiGetUnitsItem) SetAreaUnit(v bool)`

SetAreaUnit sets AreaUnit field to given value.

### HasAreaUnit

`func (o *EdiApiGetUnitsItem) HasAreaUnit() bool`

HasAreaUnit returns a boolean if a field has been set.

### GetReference

`func (o *EdiApiGetUnitsItem) GetReference() string`

GetReference returns the Reference field if non-nil, zero value otherwise.

### GetReferenceOk

`func (o *EdiApiGetUnitsItem) GetReferenceOk() (*string, bool)`

GetReferenceOk returns a tuple with the Reference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReference

`func (o *EdiApiGetUnitsItem) SetReference(v string)`

SetReference sets Reference field to given value.

### HasReference

`func (o *EdiApiGetUnitsItem) HasReference() bool`

HasReference returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


