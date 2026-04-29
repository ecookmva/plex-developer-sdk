# PartSpecificationsApiListPartSpecificationsItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | The Part Specification ID. | [optional] 
**PartId** | Pointer to **string** | The Part ID. | [optional] 
**PartNumber** | Pointer to **string** | Specify the part number requiring specifications. | [optional] 
**PartRevision** | Pointer to **string** | Specify the part revision requiring specifications. | [optional] 
**SpecificationNumber** | Pointer to **string** | The Specification Number of the Part Specification. | [optional] 
**Description** | Pointer to **string** | The description of the Part Specification. | [optional] 
**Formula** | Pointer to **string** | The specification formula. Formulas are used when a spec is calculated based on one or more other specs. For example, if a rectangular part includes specs for length and height, a calculated spec can be implemented to determine square inches: [60bdc4fa-67ea-4d25-b95c-06f67225db34] * [7acbf6bb-727b-4714-bf18-8c3f82a45f8c] Dependent specifications are contained within brackets and referenced by ID. When entering functions into the formula, make sure you use the proper character for separating the parameters. Mathematical Expressions Functions  AVG MAX MIN SUM STDEV SIN COS TAN ARCSIN ACOS ARCCOS ATAN ARCTAN LN LOG SQRT ABS  Constants  PI C E  Operators  *, +, -, /, ^ % DIV MOD  Here is an example formula using a combination of supported functions, constants and operators defined above: Pi * min([60bdc4fa-67ea-4d25-b95c-06f67225db34], [7acbf6bb-727b-4714-bf18-8c3f82a45f8c]) Parameters to defined functions are separated by a comma, but this delimiter may also be overridden by the Plex setting List Delimiter (Lists Setting Group). Aggregate Functions Aggregate functions can be used in the formula to provide functionality across a set of measurements for a single specification. This is achieved by the use of any aggregate function (min, max, avg, sum) in conjunction with a &amp;quot;token parameter&amp;quot; to indicate which specification(s) are being used as aggregates.  The Formula Type assigned to the formula is used to specify One-To-One (the setting by which all existing formula work) or Many-To-One (used when aggregating a measurement set down to a single value). For example, if specification A includes 3 measurements, a calculated specification B can utilize an aggregate formula to calculate a single value: | Specification | Measurements | ID | Formula | Formula Type | | ----| ---- | ---- | ---- | ---- | | A | 10, 20, 30 | 60bdc4fa-67ea-4d25-b95c-06f67225db34 | | | B | 20 | 7acbf6bb-727b-4714-bf18-8c3f82a45f8c | avg([60bdc4fa-67ea-4d25-b95c-06f67225db34:aggregate&#x3D;true) | Many-To-One | A formula type of One-To-One is the existing behavior of a formula, but it can be used in conjunction with aggregate functions to allow a single sample measurement to be used to output multiple measurements: | Specification | Measurements | ID | Formula | Formula Type | | ----| ---- | ---- | ---- | ---- | | C | 10, 0, -10 | 7acbf6bb-727b-4714-bf18-8c3f82a45f8c | sum([7acbf6bb-727b-4714-bf18-8c3f82a45f8c:aggregate&#x3D;true) - [60bdc4fa-67ea-4d25-b95c-06f67225db34] | One-To-One | Historical Data Special token parameters can be used to pull measurement data from past checksheets. A number of past checksheets to be used must be supplised along with an aggregate function (if applicable). The number of past checksheets that can be used in a calculation is limited to 50. For example, this formula is used to calculate the average value of a given specification for the last 5 submitted checksheets: avg([60bdc4fa-67ea-4d25-b95c-06f67225db34:pastchecksheets&#x3D;5 pastfunction&#x3D;avg]) If an aggregate is not necessary, the pastfunction argument can be set to none: avg([60bdc4fa-67ea-4d25-b95c-06f67225db34:pastchecksheets&#x3D;5 pastfunction&#x3D;none]) Note: it is important to use the &amp;quot;none&amp;quot; aggregation option in formulas where f(x0,...,xn) does not equal f(f(x0,...,xn-1), xn). For example, min(4, 6, 5) is equivalent to min(min(4,6), 5), while stdev(4, 6, 5) is not equivalent to stdev(stdev(4,6), 5). Offsheet Historical Data Historical data can also be referenced by using offsheet token parameters. This is used to pull aggregated measurements from data entered on any prior checksheet. The number of past checksheets must be specified as a separate checksheet specification measurement. This number is then referenced in subsequent formulas. For example, to pull the average value of a specification from a specific number of other checksheets, where its specification ID is 7acbf6bb-727b-4714-bf18-8c3f82a45f8c, a new specification should be created referencing this ID (We&#39;ll call the specification Sample Size): [7acbf6bb-727b-4714-bf18-8c3f82a45f8c:offsheetcalc&#x3D;samplesize] Assuming the ID of the above specification is 60bdc4fa-67ea-4d25-b95c-06f67225db34, we can then create a second specification called &#39;Average&#39; with the following formula: [60bdc4fa-67ea-4d25-b95c-06f67225db34:offsheetcalc&#x3D;avg] The above specification value will be calculated using the past X number of prior checksheets, where X is equal to the Sample Size specification value. Restrictions  The number of checksheets for the sample size is limited to a maximum of 50. The measurements are Container Serial specific.  This means that if a container is not specified then all checksheet measurements will be used. As Serialized Checksheets are Container specific (per row), the container serial must be set.  Attributes Attributes of a specification can be used as part of the formula. The supported attributes are tolerance, target, min, and max. Attribute usage in a formula will appear as follows: [60bdc4fa-67ea-4d25-b95c-06f67225db34:attribute&#x3D;tolerance] | [optional] 
**FormulaType** | Pointer to **string** | The specification formula type. | [optional] 
**DefaultGageType** | Pointer to **string** | The gage type defaulted on a control plan when specification is added. | [optional] 
**PlcName** | Pointer to **string** | The name of an associated programmable logic controller(PLC). | [optional] 
**SpecialSymbol** | Pointer to **string** | The special symbol to use for the part specification. | [optional] 
**CustomerSpecified** | Pointer to **bool** | Specifies that this is a part specification that your customer expects to be verified or not. | [optional] 
**ToleranceType** | Pointer to [**ToleranceType**](ToleranceType.md) |  | [optional] 
**Note** | Pointer to **string** | A short description or name for the specification. This typically comes from the drawing. | [optional] 
**FunctionRequirementType** | Pointer to **string** | The function requirement type of the part specification. | [optional] 
**SpecificationDimensionType** | Pointer to **string** | The specification dimension type of the part specification. | [optional] 
**UpdatedDateTime** | Pointer to **time.Time** | The latest date this specification was updated. | [optional] 

## Methods

### NewPartSpecificationsApiListPartSpecificationsItem

`func NewPartSpecificationsApiListPartSpecificationsItem() *PartSpecificationsApiListPartSpecificationsItem`

NewPartSpecificationsApiListPartSpecificationsItem instantiates a new PartSpecificationsApiListPartSpecificationsItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartSpecificationsApiListPartSpecificationsItemWithDefaults

`func NewPartSpecificationsApiListPartSpecificationsItemWithDefaults() *PartSpecificationsApiListPartSpecificationsItem`

NewPartSpecificationsApiListPartSpecificationsItemWithDefaults instantiates a new PartSpecificationsApiListPartSpecificationsItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *PartSpecificationsApiListPartSpecificationsItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PartSpecificationsApiListPartSpecificationsItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PartSpecificationsApiListPartSpecificationsItem) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *PartSpecificationsApiListPartSpecificationsItem) HasId() bool`

HasId returns a boolean if a field has been set.

### GetPartId

`func (o *PartSpecificationsApiListPartSpecificationsItem) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *PartSpecificationsApiListPartSpecificationsItem) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *PartSpecificationsApiListPartSpecificationsItem) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *PartSpecificationsApiListPartSpecificationsItem) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetPartNumber

`func (o *PartSpecificationsApiListPartSpecificationsItem) GetPartNumber() string`

GetPartNumber returns the PartNumber field if non-nil, zero value otherwise.

### GetPartNumberOk

`func (o *PartSpecificationsApiListPartSpecificationsItem) GetPartNumberOk() (*string, bool)`

GetPartNumberOk returns a tuple with the PartNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumber

`func (o *PartSpecificationsApiListPartSpecificationsItem) SetPartNumber(v string)`

SetPartNumber sets PartNumber field to given value.

### HasPartNumber

`func (o *PartSpecificationsApiListPartSpecificationsItem) HasPartNumber() bool`

HasPartNumber returns a boolean if a field has been set.

### GetPartRevision

`func (o *PartSpecificationsApiListPartSpecificationsItem) GetPartRevision() string`

GetPartRevision returns the PartRevision field if non-nil, zero value otherwise.

### GetPartRevisionOk

`func (o *PartSpecificationsApiListPartSpecificationsItem) GetPartRevisionOk() (*string, bool)`

GetPartRevisionOk returns a tuple with the PartRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartRevision

`func (o *PartSpecificationsApiListPartSpecificationsItem) SetPartRevision(v string)`

SetPartRevision sets PartRevision field to given value.

### HasPartRevision

`func (o *PartSpecificationsApiListPartSpecificationsItem) HasPartRevision() bool`

HasPartRevision returns a boolean if a field has been set.

### GetSpecificationNumber

`func (o *PartSpecificationsApiListPartSpecificationsItem) GetSpecificationNumber() string`

GetSpecificationNumber returns the SpecificationNumber field if non-nil, zero value otherwise.

### GetSpecificationNumberOk

`func (o *PartSpecificationsApiListPartSpecificationsItem) GetSpecificationNumberOk() (*string, bool)`

GetSpecificationNumberOk returns a tuple with the SpecificationNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpecificationNumber

`func (o *PartSpecificationsApiListPartSpecificationsItem) SetSpecificationNumber(v string)`

SetSpecificationNumber sets SpecificationNumber field to given value.

### HasSpecificationNumber

`func (o *PartSpecificationsApiListPartSpecificationsItem) HasSpecificationNumber() bool`

HasSpecificationNumber returns a boolean if a field has been set.

### GetDescription

`func (o *PartSpecificationsApiListPartSpecificationsItem) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *PartSpecificationsApiListPartSpecificationsItem) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *PartSpecificationsApiListPartSpecificationsItem) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *PartSpecificationsApiListPartSpecificationsItem) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetFormula

`func (o *PartSpecificationsApiListPartSpecificationsItem) GetFormula() string`

GetFormula returns the Formula field if non-nil, zero value otherwise.

### GetFormulaOk

`func (o *PartSpecificationsApiListPartSpecificationsItem) GetFormulaOk() (*string, bool)`

GetFormulaOk returns a tuple with the Formula field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormula

`func (o *PartSpecificationsApiListPartSpecificationsItem) SetFormula(v string)`

SetFormula sets Formula field to given value.

### HasFormula

`func (o *PartSpecificationsApiListPartSpecificationsItem) HasFormula() bool`

HasFormula returns a boolean if a field has been set.

### GetFormulaType

`func (o *PartSpecificationsApiListPartSpecificationsItem) GetFormulaType() string`

GetFormulaType returns the FormulaType field if non-nil, zero value otherwise.

### GetFormulaTypeOk

`func (o *PartSpecificationsApiListPartSpecificationsItem) GetFormulaTypeOk() (*string, bool)`

GetFormulaTypeOk returns a tuple with the FormulaType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormulaType

`func (o *PartSpecificationsApiListPartSpecificationsItem) SetFormulaType(v string)`

SetFormulaType sets FormulaType field to given value.

### HasFormulaType

`func (o *PartSpecificationsApiListPartSpecificationsItem) HasFormulaType() bool`

HasFormulaType returns a boolean if a field has been set.

### GetDefaultGageType

`func (o *PartSpecificationsApiListPartSpecificationsItem) GetDefaultGageType() string`

GetDefaultGageType returns the DefaultGageType field if non-nil, zero value otherwise.

### GetDefaultGageTypeOk

`func (o *PartSpecificationsApiListPartSpecificationsItem) GetDefaultGageTypeOk() (*string, bool)`

GetDefaultGageTypeOk returns a tuple with the DefaultGageType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultGageType

`func (o *PartSpecificationsApiListPartSpecificationsItem) SetDefaultGageType(v string)`

SetDefaultGageType sets DefaultGageType field to given value.

### HasDefaultGageType

`func (o *PartSpecificationsApiListPartSpecificationsItem) HasDefaultGageType() bool`

HasDefaultGageType returns a boolean if a field has been set.

### GetPlcName

`func (o *PartSpecificationsApiListPartSpecificationsItem) GetPlcName() string`

GetPlcName returns the PlcName field if non-nil, zero value otherwise.

### GetPlcNameOk

`func (o *PartSpecificationsApiListPartSpecificationsItem) GetPlcNameOk() (*string, bool)`

GetPlcNameOk returns a tuple with the PlcName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlcName

`func (o *PartSpecificationsApiListPartSpecificationsItem) SetPlcName(v string)`

SetPlcName sets PlcName field to given value.

### HasPlcName

`func (o *PartSpecificationsApiListPartSpecificationsItem) HasPlcName() bool`

HasPlcName returns a boolean if a field has been set.

### GetSpecialSymbol

`func (o *PartSpecificationsApiListPartSpecificationsItem) GetSpecialSymbol() string`

GetSpecialSymbol returns the SpecialSymbol field if non-nil, zero value otherwise.

### GetSpecialSymbolOk

`func (o *PartSpecificationsApiListPartSpecificationsItem) GetSpecialSymbolOk() (*string, bool)`

GetSpecialSymbolOk returns a tuple with the SpecialSymbol field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpecialSymbol

`func (o *PartSpecificationsApiListPartSpecificationsItem) SetSpecialSymbol(v string)`

SetSpecialSymbol sets SpecialSymbol field to given value.

### HasSpecialSymbol

`func (o *PartSpecificationsApiListPartSpecificationsItem) HasSpecialSymbol() bool`

HasSpecialSymbol returns a boolean if a field has been set.

### GetCustomerSpecified

`func (o *PartSpecificationsApiListPartSpecificationsItem) GetCustomerSpecified() bool`

GetCustomerSpecified returns the CustomerSpecified field if non-nil, zero value otherwise.

### GetCustomerSpecifiedOk

`func (o *PartSpecificationsApiListPartSpecificationsItem) GetCustomerSpecifiedOk() (*bool, bool)`

GetCustomerSpecifiedOk returns a tuple with the CustomerSpecified field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerSpecified

`func (o *PartSpecificationsApiListPartSpecificationsItem) SetCustomerSpecified(v bool)`

SetCustomerSpecified sets CustomerSpecified field to given value.

### HasCustomerSpecified

`func (o *PartSpecificationsApiListPartSpecificationsItem) HasCustomerSpecified() bool`

HasCustomerSpecified returns a boolean if a field has been set.

### GetToleranceType

`func (o *PartSpecificationsApiListPartSpecificationsItem) GetToleranceType() ToleranceType`

GetToleranceType returns the ToleranceType field if non-nil, zero value otherwise.

### GetToleranceTypeOk

`func (o *PartSpecificationsApiListPartSpecificationsItem) GetToleranceTypeOk() (*ToleranceType, bool)`

GetToleranceTypeOk returns a tuple with the ToleranceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToleranceType

`func (o *PartSpecificationsApiListPartSpecificationsItem) SetToleranceType(v ToleranceType)`

SetToleranceType sets ToleranceType field to given value.

### HasToleranceType

`func (o *PartSpecificationsApiListPartSpecificationsItem) HasToleranceType() bool`

HasToleranceType returns a boolean if a field has been set.

### GetNote

`func (o *PartSpecificationsApiListPartSpecificationsItem) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *PartSpecificationsApiListPartSpecificationsItem) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *PartSpecificationsApiListPartSpecificationsItem) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *PartSpecificationsApiListPartSpecificationsItem) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetFunctionRequirementType

`func (o *PartSpecificationsApiListPartSpecificationsItem) GetFunctionRequirementType() string`

GetFunctionRequirementType returns the FunctionRequirementType field if non-nil, zero value otherwise.

### GetFunctionRequirementTypeOk

`func (o *PartSpecificationsApiListPartSpecificationsItem) GetFunctionRequirementTypeOk() (*string, bool)`

GetFunctionRequirementTypeOk returns a tuple with the FunctionRequirementType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFunctionRequirementType

`func (o *PartSpecificationsApiListPartSpecificationsItem) SetFunctionRequirementType(v string)`

SetFunctionRequirementType sets FunctionRequirementType field to given value.

### HasFunctionRequirementType

`func (o *PartSpecificationsApiListPartSpecificationsItem) HasFunctionRequirementType() bool`

HasFunctionRequirementType returns a boolean if a field has been set.

### GetSpecificationDimensionType

`func (o *PartSpecificationsApiListPartSpecificationsItem) GetSpecificationDimensionType() string`

GetSpecificationDimensionType returns the SpecificationDimensionType field if non-nil, zero value otherwise.

### GetSpecificationDimensionTypeOk

`func (o *PartSpecificationsApiListPartSpecificationsItem) GetSpecificationDimensionTypeOk() (*string, bool)`

GetSpecificationDimensionTypeOk returns a tuple with the SpecificationDimensionType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpecificationDimensionType

`func (o *PartSpecificationsApiListPartSpecificationsItem) SetSpecificationDimensionType(v string)`

SetSpecificationDimensionType sets SpecificationDimensionType field to given value.

### HasSpecificationDimensionType

`func (o *PartSpecificationsApiListPartSpecificationsItem) HasSpecificationDimensionType() bool`

HasSpecificationDimensionType returns a boolean if a field has been set.

### GetUpdatedDateTime

`func (o *PartSpecificationsApiListPartSpecificationsItem) GetUpdatedDateTime() time.Time`

GetUpdatedDateTime returns the UpdatedDateTime field if non-nil, zero value otherwise.

### GetUpdatedDateTimeOk

`func (o *PartSpecificationsApiListPartSpecificationsItem) GetUpdatedDateTimeOk() (*time.Time, bool)`

GetUpdatedDateTimeOk returns a tuple with the UpdatedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedDateTime

`func (o *PartSpecificationsApiListPartSpecificationsItem) SetUpdatedDateTime(v time.Time)`

SetUpdatedDateTime sets UpdatedDateTime field to given value.

### HasUpdatedDateTime

`func (o *PartSpecificationsApiListPartSpecificationsItem) HasUpdatedDateTime() bool`

HasUpdatedDateTime returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


