# ControlPlansApiListControlPlanLinesItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | ID representing the Control Plan Line. | [optional] 
**ControlPlanId** | Pointer to **string** | ID representing the control plan. | [optional] 
**ControlPlanLineStatus** | Pointer to **string** | The status of the control plan line. | [optional] 
**InspectionMode** | Pointer to **string** | The inspection mode. | [optional] 
**PartId** | Pointer to **string** | ID representing the part. | [optional] 
**PartNo** | Pointer to **string** | The part no. | [optional] 
**PartRevision** | Pointer to **string** | The part revision. | [optional] 
**PartOperationId** | Pointer to **string** | ID representing the part operation. | [optional] 
**OperationId** | Pointer to **string** | ID representing the operation. | [optional] 
**OperationCode** | Pointer to **string** | The operation code. | [optional] 
**SpecificationId** | Pointer to **string** | ID representing the specification. | [optional] 
**Description** | Pointer to **string** | The description of the control plan line. | [optional] 
**PassAnswer** | Pointer to **string** | The pass answer. | [optional] 
**FailAnswer** | Pointer to **string** | The fail answer. | [optional] 
**Note** | Pointer to **string** | The note on the control plan line. | [optional] 
**GageType** | Pointer to **string** | The gage type of the control plan line. | [optional] 
**GageNote** | Pointer to **string** | The gage note of the control plan line. | [optional] 
**PartSpecificGages** | Pointer to [**[]PartSpecificGagesItem**](PartSpecificGagesItem.md) | A list of part-specific gages. | [optional] 
**SamplePlan** | Pointer to **string** | The sample plan. | [optional] 
**CustomChecksheetDataCollectionType** | Pointer to **string** | The custom checksheet data collection type. | [optional] 
**ReactionPlan** | Pointer to **string** | The reaction plan. | [optional] 
**ReactionPlanOwner** | Pointer to **string** | The reaction plan owner. | [optional] 
**SpecificToWorkcenterId** | Pointer to **string** | ID representing the workcenter. | [optional] 
**SpecificToWorkcenterCode** | Pointer to **string** | The workcenter code of the workcenter. | [optional] 
**DefaultAttributeAnswerPass** | Pointer to **bool** | The designation if the attribute answer defaults to the pass value. | [optional] 
**DeviationId** | Pointer to **string** | ID representing the deviation that is currently effective with the most recent effective date that has an approved deviation status if deviation statuses are used. | [optional] 
**SortOrder** | Pointer to **float64** | The sort order. | [optional] 
**ChecksheetSortOrder** | Pointer to **float64** | The sort order. | [optional] 
**Symbol** | Pointer to **string** | The special symbol association with the specification. | [optional] 
**SymbolAbbreviation** | Pointer to **string** | The special symbol abbreviation. | [optional] 
**TrackFailureModes** | Pointer to **bool** | The designation if failure modes are tracked. Requires the Control Plan setting &amp;quot;Specification Tool Linking Use&amp;quot; be enabled. | [optional] 

## Methods

### NewControlPlansApiListControlPlanLinesItem

`func NewControlPlansApiListControlPlanLinesItem() *ControlPlansApiListControlPlanLinesItem`

NewControlPlansApiListControlPlanLinesItem instantiates a new ControlPlansApiListControlPlanLinesItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewControlPlansApiListControlPlanLinesItemWithDefaults

`func NewControlPlansApiListControlPlanLinesItemWithDefaults() *ControlPlansApiListControlPlanLinesItem`

NewControlPlansApiListControlPlanLinesItemWithDefaults instantiates a new ControlPlansApiListControlPlanLinesItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ControlPlansApiListControlPlanLinesItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ControlPlansApiListControlPlanLinesItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ControlPlansApiListControlPlanLinesItem) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *ControlPlansApiListControlPlanLinesItem) HasId() bool`

HasId returns a boolean if a field has been set.

### GetControlPlanId

`func (o *ControlPlansApiListControlPlanLinesItem) GetControlPlanId() string`

GetControlPlanId returns the ControlPlanId field if non-nil, zero value otherwise.

### GetControlPlanIdOk

`func (o *ControlPlansApiListControlPlanLinesItem) GetControlPlanIdOk() (*string, bool)`

GetControlPlanIdOk returns a tuple with the ControlPlanId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetControlPlanId

`func (o *ControlPlansApiListControlPlanLinesItem) SetControlPlanId(v string)`

SetControlPlanId sets ControlPlanId field to given value.

### HasControlPlanId

`func (o *ControlPlansApiListControlPlanLinesItem) HasControlPlanId() bool`

HasControlPlanId returns a boolean if a field has been set.

### GetControlPlanLineStatus

`func (o *ControlPlansApiListControlPlanLinesItem) GetControlPlanLineStatus() string`

GetControlPlanLineStatus returns the ControlPlanLineStatus field if non-nil, zero value otherwise.

### GetControlPlanLineStatusOk

`func (o *ControlPlansApiListControlPlanLinesItem) GetControlPlanLineStatusOk() (*string, bool)`

GetControlPlanLineStatusOk returns a tuple with the ControlPlanLineStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetControlPlanLineStatus

`func (o *ControlPlansApiListControlPlanLinesItem) SetControlPlanLineStatus(v string)`

SetControlPlanLineStatus sets ControlPlanLineStatus field to given value.

### HasControlPlanLineStatus

`func (o *ControlPlansApiListControlPlanLinesItem) HasControlPlanLineStatus() bool`

HasControlPlanLineStatus returns a boolean if a field has been set.

### GetInspectionMode

`func (o *ControlPlansApiListControlPlanLinesItem) GetInspectionMode() string`

GetInspectionMode returns the InspectionMode field if non-nil, zero value otherwise.

### GetInspectionModeOk

`func (o *ControlPlansApiListControlPlanLinesItem) GetInspectionModeOk() (*string, bool)`

GetInspectionModeOk returns a tuple with the InspectionMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInspectionMode

`func (o *ControlPlansApiListControlPlanLinesItem) SetInspectionMode(v string)`

SetInspectionMode sets InspectionMode field to given value.

### HasInspectionMode

`func (o *ControlPlansApiListControlPlanLinesItem) HasInspectionMode() bool`

HasInspectionMode returns a boolean if a field has been set.

### GetPartId

`func (o *ControlPlansApiListControlPlanLinesItem) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *ControlPlansApiListControlPlanLinesItem) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *ControlPlansApiListControlPlanLinesItem) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *ControlPlansApiListControlPlanLinesItem) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetPartNo

`func (o *ControlPlansApiListControlPlanLinesItem) GetPartNo() string`

GetPartNo returns the PartNo field if non-nil, zero value otherwise.

### GetPartNoOk

`func (o *ControlPlansApiListControlPlanLinesItem) GetPartNoOk() (*string, bool)`

GetPartNoOk returns a tuple with the PartNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNo

`func (o *ControlPlansApiListControlPlanLinesItem) SetPartNo(v string)`

SetPartNo sets PartNo field to given value.

### HasPartNo

`func (o *ControlPlansApiListControlPlanLinesItem) HasPartNo() bool`

HasPartNo returns a boolean if a field has been set.

### GetPartRevision

`func (o *ControlPlansApiListControlPlanLinesItem) GetPartRevision() string`

GetPartRevision returns the PartRevision field if non-nil, zero value otherwise.

### GetPartRevisionOk

`func (o *ControlPlansApiListControlPlanLinesItem) GetPartRevisionOk() (*string, bool)`

GetPartRevisionOk returns a tuple with the PartRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartRevision

`func (o *ControlPlansApiListControlPlanLinesItem) SetPartRevision(v string)`

SetPartRevision sets PartRevision field to given value.

### HasPartRevision

`func (o *ControlPlansApiListControlPlanLinesItem) HasPartRevision() bool`

HasPartRevision returns a boolean if a field has been set.

### GetPartOperationId

`func (o *ControlPlansApiListControlPlanLinesItem) GetPartOperationId() string`

GetPartOperationId returns the PartOperationId field if non-nil, zero value otherwise.

### GetPartOperationIdOk

`func (o *ControlPlansApiListControlPlanLinesItem) GetPartOperationIdOk() (*string, bool)`

GetPartOperationIdOk returns a tuple with the PartOperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartOperationId

`func (o *ControlPlansApiListControlPlanLinesItem) SetPartOperationId(v string)`

SetPartOperationId sets PartOperationId field to given value.

### HasPartOperationId

`func (o *ControlPlansApiListControlPlanLinesItem) HasPartOperationId() bool`

HasPartOperationId returns a boolean if a field has been set.

### GetOperationId

`func (o *ControlPlansApiListControlPlanLinesItem) GetOperationId() string`

GetOperationId returns the OperationId field if non-nil, zero value otherwise.

### GetOperationIdOk

`func (o *ControlPlansApiListControlPlanLinesItem) GetOperationIdOk() (*string, bool)`

GetOperationIdOk returns a tuple with the OperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationId

`func (o *ControlPlansApiListControlPlanLinesItem) SetOperationId(v string)`

SetOperationId sets OperationId field to given value.

### HasOperationId

`func (o *ControlPlansApiListControlPlanLinesItem) HasOperationId() bool`

HasOperationId returns a boolean if a field has been set.

### GetOperationCode

`func (o *ControlPlansApiListControlPlanLinesItem) GetOperationCode() string`

GetOperationCode returns the OperationCode field if non-nil, zero value otherwise.

### GetOperationCodeOk

`func (o *ControlPlansApiListControlPlanLinesItem) GetOperationCodeOk() (*string, bool)`

GetOperationCodeOk returns a tuple with the OperationCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationCode

`func (o *ControlPlansApiListControlPlanLinesItem) SetOperationCode(v string)`

SetOperationCode sets OperationCode field to given value.

### HasOperationCode

`func (o *ControlPlansApiListControlPlanLinesItem) HasOperationCode() bool`

HasOperationCode returns a boolean if a field has been set.

### GetSpecificationId

`func (o *ControlPlansApiListControlPlanLinesItem) GetSpecificationId() string`

GetSpecificationId returns the SpecificationId field if non-nil, zero value otherwise.

### GetSpecificationIdOk

`func (o *ControlPlansApiListControlPlanLinesItem) GetSpecificationIdOk() (*string, bool)`

GetSpecificationIdOk returns a tuple with the SpecificationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpecificationId

`func (o *ControlPlansApiListControlPlanLinesItem) SetSpecificationId(v string)`

SetSpecificationId sets SpecificationId field to given value.

### HasSpecificationId

`func (o *ControlPlansApiListControlPlanLinesItem) HasSpecificationId() bool`

HasSpecificationId returns a boolean if a field has been set.

### GetDescription

`func (o *ControlPlansApiListControlPlanLinesItem) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ControlPlansApiListControlPlanLinesItem) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ControlPlansApiListControlPlanLinesItem) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ControlPlansApiListControlPlanLinesItem) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetPassAnswer

`func (o *ControlPlansApiListControlPlanLinesItem) GetPassAnswer() string`

GetPassAnswer returns the PassAnswer field if non-nil, zero value otherwise.

### GetPassAnswerOk

`func (o *ControlPlansApiListControlPlanLinesItem) GetPassAnswerOk() (*string, bool)`

GetPassAnswerOk returns a tuple with the PassAnswer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassAnswer

`func (o *ControlPlansApiListControlPlanLinesItem) SetPassAnswer(v string)`

SetPassAnswer sets PassAnswer field to given value.

### HasPassAnswer

`func (o *ControlPlansApiListControlPlanLinesItem) HasPassAnswer() bool`

HasPassAnswer returns a boolean if a field has been set.

### GetFailAnswer

`func (o *ControlPlansApiListControlPlanLinesItem) GetFailAnswer() string`

GetFailAnswer returns the FailAnswer field if non-nil, zero value otherwise.

### GetFailAnswerOk

`func (o *ControlPlansApiListControlPlanLinesItem) GetFailAnswerOk() (*string, bool)`

GetFailAnswerOk returns a tuple with the FailAnswer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailAnswer

`func (o *ControlPlansApiListControlPlanLinesItem) SetFailAnswer(v string)`

SetFailAnswer sets FailAnswer field to given value.

### HasFailAnswer

`func (o *ControlPlansApiListControlPlanLinesItem) HasFailAnswer() bool`

HasFailAnswer returns a boolean if a field has been set.

### GetNote

`func (o *ControlPlansApiListControlPlanLinesItem) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *ControlPlansApiListControlPlanLinesItem) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *ControlPlansApiListControlPlanLinesItem) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *ControlPlansApiListControlPlanLinesItem) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetGageType

`func (o *ControlPlansApiListControlPlanLinesItem) GetGageType() string`

GetGageType returns the GageType field if non-nil, zero value otherwise.

### GetGageTypeOk

`func (o *ControlPlansApiListControlPlanLinesItem) GetGageTypeOk() (*string, bool)`

GetGageTypeOk returns a tuple with the GageType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGageType

`func (o *ControlPlansApiListControlPlanLinesItem) SetGageType(v string)`

SetGageType sets GageType field to given value.

### HasGageType

`func (o *ControlPlansApiListControlPlanLinesItem) HasGageType() bool`

HasGageType returns a boolean if a field has been set.

### GetGageNote

`func (o *ControlPlansApiListControlPlanLinesItem) GetGageNote() string`

GetGageNote returns the GageNote field if non-nil, zero value otherwise.

### GetGageNoteOk

`func (o *ControlPlansApiListControlPlanLinesItem) GetGageNoteOk() (*string, bool)`

GetGageNoteOk returns a tuple with the GageNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGageNote

`func (o *ControlPlansApiListControlPlanLinesItem) SetGageNote(v string)`

SetGageNote sets GageNote field to given value.

### HasGageNote

`func (o *ControlPlansApiListControlPlanLinesItem) HasGageNote() bool`

HasGageNote returns a boolean if a field has been set.

### GetPartSpecificGages

`func (o *ControlPlansApiListControlPlanLinesItem) GetPartSpecificGages() []PartSpecificGagesItem`

GetPartSpecificGages returns the PartSpecificGages field if non-nil, zero value otherwise.

### GetPartSpecificGagesOk

`func (o *ControlPlansApiListControlPlanLinesItem) GetPartSpecificGagesOk() (*[]PartSpecificGagesItem, bool)`

GetPartSpecificGagesOk returns a tuple with the PartSpecificGages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartSpecificGages

`func (o *ControlPlansApiListControlPlanLinesItem) SetPartSpecificGages(v []PartSpecificGagesItem)`

SetPartSpecificGages sets PartSpecificGages field to given value.

### HasPartSpecificGages

`func (o *ControlPlansApiListControlPlanLinesItem) HasPartSpecificGages() bool`

HasPartSpecificGages returns a boolean if a field has been set.

### GetSamplePlan

`func (o *ControlPlansApiListControlPlanLinesItem) GetSamplePlan() string`

GetSamplePlan returns the SamplePlan field if non-nil, zero value otherwise.

### GetSamplePlanOk

`func (o *ControlPlansApiListControlPlanLinesItem) GetSamplePlanOk() (*string, bool)`

GetSamplePlanOk returns a tuple with the SamplePlan field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSamplePlan

`func (o *ControlPlansApiListControlPlanLinesItem) SetSamplePlan(v string)`

SetSamplePlan sets SamplePlan field to given value.

### HasSamplePlan

`func (o *ControlPlansApiListControlPlanLinesItem) HasSamplePlan() bool`

HasSamplePlan returns a boolean if a field has been set.

### GetCustomChecksheetDataCollectionType

`func (o *ControlPlansApiListControlPlanLinesItem) GetCustomChecksheetDataCollectionType() string`

GetCustomChecksheetDataCollectionType returns the CustomChecksheetDataCollectionType field if non-nil, zero value otherwise.

### GetCustomChecksheetDataCollectionTypeOk

`func (o *ControlPlansApiListControlPlanLinesItem) GetCustomChecksheetDataCollectionTypeOk() (*string, bool)`

GetCustomChecksheetDataCollectionTypeOk returns a tuple with the CustomChecksheetDataCollectionType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomChecksheetDataCollectionType

`func (o *ControlPlansApiListControlPlanLinesItem) SetCustomChecksheetDataCollectionType(v string)`

SetCustomChecksheetDataCollectionType sets CustomChecksheetDataCollectionType field to given value.

### HasCustomChecksheetDataCollectionType

`func (o *ControlPlansApiListControlPlanLinesItem) HasCustomChecksheetDataCollectionType() bool`

HasCustomChecksheetDataCollectionType returns a boolean if a field has been set.

### GetReactionPlan

`func (o *ControlPlansApiListControlPlanLinesItem) GetReactionPlan() string`

GetReactionPlan returns the ReactionPlan field if non-nil, zero value otherwise.

### GetReactionPlanOk

`func (o *ControlPlansApiListControlPlanLinesItem) GetReactionPlanOk() (*string, bool)`

GetReactionPlanOk returns a tuple with the ReactionPlan field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReactionPlan

`func (o *ControlPlansApiListControlPlanLinesItem) SetReactionPlan(v string)`

SetReactionPlan sets ReactionPlan field to given value.

### HasReactionPlan

`func (o *ControlPlansApiListControlPlanLinesItem) HasReactionPlan() bool`

HasReactionPlan returns a boolean if a field has been set.

### GetReactionPlanOwner

`func (o *ControlPlansApiListControlPlanLinesItem) GetReactionPlanOwner() string`

GetReactionPlanOwner returns the ReactionPlanOwner field if non-nil, zero value otherwise.

### GetReactionPlanOwnerOk

`func (o *ControlPlansApiListControlPlanLinesItem) GetReactionPlanOwnerOk() (*string, bool)`

GetReactionPlanOwnerOk returns a tuple with the ReactionPlanOwner field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReactionPlanOwner

`func (o *ControlPlansApiListControlPlanLinesItem) SetReactionPlanOwner(v string)`

SetReactionPlanOwner sets ReactionPlanOwner field to given value.

### HasReactionPlanOwner

`func (o *ControlPlansApiListControlPlanLinesItem) HasReactionPlanOwner() bool`

HasReactionPlanOwner returns a boolean if a field has been set.

### GetSpecificToWorkcenterId

`func (o *ControlPlansApiListControlPlanLinesItem) GetSpecificToWorkcenterId() string`

GetSpecificToWorkcenterId returns the SpecificToWorkcenterId field if non-nil, zero value otherwise.

### GetSpecificToWorkcenterIdOk

`func (o *ControlPlansApiListControlPlanLinesItem) GetSpecificToWorkcenterIdOk() (*string, bool)`

GetSpecificToWorkcenterIdOk returns a tuple with the SpecificToWorkcenterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpecificToWorkcenterId

`func (o *ControlPlansApiListControlPlanLinesItem) SetSpecificToWorkcenterId(v string)`

SetSpecificToWorkcenterId sets SpecificToWorkcenterId field to given value.

### HasSpecificToWorkcenterId

`func (o *ControlPlansApiListControlPlanLinesItem) HasSpecificToWorkcenterId() bool`

HasSpecificToWorkcenterId returns a boolean if a field has been set.

### GetSpecificToWorkcenterCode

`func (o *ControlPlansApiListControlPlanLinesItem) GetSpecificToWorkcenterCode() string`

GetSpecificToWorkcenterCode returns the SpecificToWorkcenterCode field if non-nil, zero value otherwise.

### GetSpecificToWorkcenterCodeOk

`func (o *ControlPlansApiListControlPlanLinesItem) GetSpecificToWorkcenterCodeOk() (*string, bool)`

GetSpecificToWorkcenterCodeOk returns a tuple with the SpecificToWorkcenterCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpecificToWorkcenterCode

`func (o *ControlPlansApiListControlPlanLinesItem) SetSpecificToWorkcenterCode(v string)`

SetSpecificToWorkcenterCode sets SpecificToWorkcenterCode field to given value.

### HasSpecificToWorkcenterCode

`func (o *ControlPlansApiListControlPlanLinesItem) HasSpecificToWorkcenterCode() bool`

HasSpecificToWorkcenterCode returns a boolean if a field has been set.

### GetDefaultAttributeAnswerPass

`func (o *ControlPlansApiListControlPlanLinesItem) GetDefaultAttributeAnswerPass() bool`

GetDefaultAttributeAnswerPass returns the DefaultAttributeAnswerPass field if non-nil, zero value otherwise.

### GetDefaultAttributeAnswerPassOk

`func (o *ControlPlansApiListControlPlanLinesItem) GetDefaultAttributeAnswerPassOk() (*bool, bool)`

GetDefaultAttributeAnswerPassOk returns a tuple with the DefaultAttributeAnswerPass field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultAttributeAnswerPass

`func (o *ControlPlansApiListControlPlanLinesItem) SetDefaultAttributeAnswerPass(v bool)`

SetDefaultAttributeAnswerPass sets DefaultAttributeAnswerPass field to given value.

### HasDefaultAttributeAnswerPass

`func (o *ControlPlansApiListControlPlanLinesItem) HasDefaultAttributeAnswerPass() bool`

HasDefaultAttributeAnswerPass returns a boolean if a field has been set.

### GetDeviationId

`func (o *ControlPlansApiListControlPlanLinesItem) GetDeviationId() string`

GetDeviationId returns the DeviationId field if non-nil, zero value otherwise.

### GetDeviationIdOk

`func (o *ControlPlansApiListControlPlanLinesItem) GetDeviationIdOk() (*string, bool)`

GetDeviationIdOk returns a tuple with the DeviationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviationId

`func (o *ControlPlansApiListControlPlanLinesItem) SetDeviationId(v string)`

SetDeviationId sets DeviationId field to given value.

### HasDeviationId

`func (o *ControlPlansApiListControlPlanLinesItem) HasDeviationId() bool`

HasDeviationId returns a boolean if a field has been set.

### GetSortOrder

`func (o *ControlPlansApiListControlPlanLinesItem) GetSortOrder() float64`

GetSortOrder returns the SortOrder field if non-nil, zero value otherwise.

### GetSortOrderOk

`func (o *ControlPlansApiListControlPlanLinesItem) GetSortOrderOk() (*float64, bool)`

GetSortOrderOk returns a tuple with the SortOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSortOrder

`func (o *ControlPlansApiListControlPlanLinesItem) SetSortOrder(v float64)`

SetSortOrder sets SortOrder field to given value.

### HasSortOrder

`func (o *ControlPlansApiListControlPlanLinesItem) HasSortOrder() bool`

HasSortOrder returns a boolean if a field has been set.

### GetChecksheetSortOrder

`func (o *ControlPlansApiListControlPlanLinesItem) GetChecksheetSortOrder() float64`

GetChecksheetSortOrder returns the ChecksheetSortOrder field if non-nil, zero value otherwise.

### GetChecksheetSortOrderOk

`func (o *ControlPlansApiListControlPlanLinesItem) GetChecksheetSortOrderOk() (*float64, bool)`

GetChecksheetSortOrderOk returns a tuple with the ChecksheetSortOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChecksheetSortOrder

`func (o *ControlPlansApiListControlPlanLinesItem) SetChecksheetSortOrder(v float64)`

SetChecksheetSortOrder sets ChecksheetSortOrder field to given value.

### HasChecksheetSortOrder

`func (o *ControlPlansApiListControlPlanLinesItem) HasChecksheetSortOrder() bool`

HasChecksheetSortOrder returns a boolean if a field has been set.

### GetSymbol

`func (o *ControlPlansApiListControlPlanLinesItem) GetSymbol() string`

GetSymbol returns the Symbol field if non-nil, zero value otherwise.

### GetSymbolOk

`func (o *ControlPlansApiListControlPlanLinesItem) GetSymbolOk() (*string, bool)`

GetSymbolOk returns a tuple with the Symbol field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSymbol

`func (o *ControlPlansApiListControlPlanLinesItem) SetSymbol(v string)`

SetSymbol sets Symbol field to given value.

### HasSymbol

`func (o *ControlPlansApiListControlPlanLinesItem) HasSymbol() bool`

HasSymbol returns a boolean if a field has been set.

### GetSymbolAbbreviation

`func (o *ControlPlansApiListControlPlanLinesItem) GetSymbolAbbreviation() string`

GetSymbolAbbreviation returns the SymbolAbbreviation field if non-nil, zero value otherwise.

### GetSymbolAbbreviationOk

`func (o *ControlPlansApiListControlPlanLinesItem) GetSymbolAbbreviationOk() (*string, bool)`

GetSymbolAbbreviationOk returns a tuple with the SymbolAbbreviation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSymbolAbbreviation

`func (o *ControlPlansApiListControlPlanLinesItem) SetSymbolAbbreviation(v string)`

SetSymbolAbbreviation sets SymbolAbbreviation field to given value.

### HasSymbolAbbreviation

`func (o *ControlPlansApiListControlPlanLinesItem) HasSymbolAbbreviation() bool`

HasSymbolAbbreviation returns a boolean if a field has been set.

### GetTrackFailureModes

`func (o *ControlPlansApiListControlPlanLinesItem) GetTrackFailureModes() bool`

GetTrackFailureModes returns the TrackFailureModes field if non-nil, zero value otherwise.

### GetTrackFailureModesOk

`func (o *ControlPlansApiListControlPlanLinesItem) GetTrackFailureModesOk() (*bool, bool)`

GetTrackFailureModesOk returns a tuple with the TrackFailureModes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackFailureModes

`func (o *ControlPlansApiListControlPlanLinesItem) SetTrackFailureModes(v bool)`

SetTrackFailureModes sets TrackFailureModes field to given value.

### HasTrackFailureModes

`func (o *ControlPlansApiListControlPlanLinesItem) HasTrackFailureModes() bool`

HasTrackFailureModes returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


