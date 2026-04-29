# ProcessControlPlansApiGetProcessControlRecipePlanLineResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | ID representing the Control Plan Line. | [optional] 
**ControlPlanId** | Pointer to **string** | ID representing the control plan. | [optional] 
**ControlPlanLineStatus** | Pointer to **string** | The status of the control plan line. | [optional] 
**InspectionMode** | Pointer to **string** | The inspection mode. | [optional] 
**ProcessControlRecipeId** | Pointer to **string** | ID representing the process control recipe. | [optional] 
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
**DefaultAttributeAnswerPass** | Pointer to **bool** | The designation if the attribute answer defaults to the pass value. | [optional] 
**SortOrder** | Pointer to **float64** | The sort order. | [optional] 
**ChecksheetSortOrder** | Pointer to **float64** | The checksheet sort order. | [optional] 
**Symbol** | Pointer to **string** | The special symbol association with the specification. | [optional] 
**SymbolAbbreviation** | Pointer to **string** | The special symbol abbreviation. | [optional] 
**TrackFailureModes** | Pointer to **bool** | The designation if failure modes are tracked. Requires the Control Plan setting &amp;quot;Specification Tool Linking Use&amp;quot; be enabled. | [optional] 

## Methods

### NewProcessControlPlansApiGetProcessControlRecipePlanLineResponse

`func NewProcessControlPlansApiGetProcessControlRecipePlanLineResponse() *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse`

NewProcessControlPlansApiGetProcessControlRecipePlanLineResponse instantiates a new ProcessControlPlansApiGetProcessControlRecipePlanLineResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProcessControlPlansApiGetProcessControlRecipePlanLineResponseWithDefaults

`func NewProcessControlPlansApiGetProcessControlRecipePlanLineResponseWithDefaults() *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse`

NewProcessControlPlansApiGetProcessControlRecipePlanLineResponseWithDefaults instantiates a new ProcessControlPlansApiGetProcessControlRecipePlanLineResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetControlPlanId

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetControlPlanId() string`

GetControlPlanId returns the ControlPlanId field if non-nil, zero value otherwise.

### GetControlPlanIdOk

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetControlPlanIdOk() (*string, bool)`

GetControlPlanIdOk returns a tuple with the ControlPlanId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetControlPlanId

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) SetControlPlanId(v string)`

SetControlPlanId sets ControlPlanId field to given value.

### HasControlPlanId

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) HasControlPlanId() bool`

HasControlPlanId returns a boolean if a field has been set.

### GetControlPlanLineStatus

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetControlPlanLineStatus() string`

GetControlPlanLineStatus returns the ControlPlanLineStatus field if non-nil, zero value otherwise.

### GetControlPlanLineStatusOk

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetControlPlanLineStatusOk() (*string, bool)`

GetControlPlanLineStatusOk returns a tuple with the ControlPlanLineStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetControlPlanLineStatus

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) SetControlPlanLineStatus(v string)`

SetControlPlanLineStatus sets ControlPlanLineStatus field to given value.

### HasControlPlanLineStatus

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) HasControlPlanLineStatus() bool`

HasControlPlanLineStatus returns a boolean if a field has been set.

### GetInspectionMode

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetInspectionMode() string`

GetInspectionMode returns the InspectionMode field if non-nil, zero value otherwise.

### GetInspectionModeOk

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetInspectionModeOk() (*string, bool)`

GetInspectionModeOk returns a tuple with the InspectionMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInspectionMode

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) SetInspectionMode(v string)`

SetInspectionMode sets InspectionMode field to given value.

### HasInspectionMode

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) HasInspectionMode() bool`

HasInspectionMode returns a boolean if a field has been set.

### GetProcessControlRecipeId

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetProcessControlRecipeId() string`

GetProcessControlRecipeId returns the ProcessControlRecipeId field if non-nil, zero value otherwise.

### GetProcessControlRecipeIdOk

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetProcessControlRecipeIdOk() (*string, bool)`

GetProcessControlRecipeIdOk returns a tuple with the ProcessControlRecipeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessControlRecipeId

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) SetProcessControlRecipeId(v string)`

SetProcessControlRecipeId sets ProcessControlRecipeId field to given value.

### HasProcessControlRecipeId

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) HasProcessControlRecipeId() bool`

HasProcessControlRecipeId returns a boolean if a field has been set.

### GetOperationId

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetOperationId() string`

GetOperationId returns the OperationId field if non-nil, zero value otherwise.

### GetOperationIdOk

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetOperationIdOk() (*string, bool)`

GetOperationIdOk returns a tuple with the OperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationId

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) SetOperationId(v string)`

SetOperationId sets OperationId field to given value.

### HasOperationId

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) HasOperationId() bool`

HasOperationId returns a boolean if a field has been set.

### GetOperationCode

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetOperationCode() string`

GetOperationCode returns the OperationCode field if non-nil, zero value otherwise.

### GetOperationCodeOk

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetOperationCodeOk() (*string, bool)`

GetOperationCodeOk returns a tuple with the OperationCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationCode

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) SetOperationCode(v string)`

SetOperationCode sets OperationCode field to given value.

### HasOperationCode

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) HasOperationCode() bool`

HasOperationCode returns a boolean if a field has been set.

### GetSpecificationId

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetSpecificationId() string`

GetSpecificationId returns the SpecificationId field if non-nil, zero value otherwise.

### GetSpecificationIdOk

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetSpecificationIdOk() (*string, bool)`

GetSpecificationIdOk returns a tuple with the SpecificationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpecificationId

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) SetSpecificationId(v string)`

SetSpecificationId sets SpecificationId field to given value.

### HasSpecificationId

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) HasSpecificationId() bool`

HasSpecificationId returns a boolean if a field has been set.

### GetDescription

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetPassAnswer

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetPassAnswer() string`

GetPassAnswer returns the PassAnswer field if non-nil, zero value otherwise.

### GetPassAnswerOk

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetPassAnswerOk() (*string, bool)`

GetPassAnswerOk returns a tuple with the PassAnswer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassAnswer

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) SetPassAnswer(v string)`

SetPassAnswer sets PassAnswer field to given value.

### HasPassAnswer

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) HasPassAnswer() bool`

HasPassAnswer returns a boolean if a field has been set.

### GetFailAnswer

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetFailAnswer() string`

GetFailAnswer returns the FailAnswer field if non-nil, zero value otherwise.

### GetFailAnswerOk

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetFailAnswerOk() (*string, bool)`

GetFailAnswerOk returns a tuple with the FailAnswer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailAnswer

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) SetFailAnswer(v string)`

SetFailAnswer sets FailAnswer field to given value.

### HasFailAnswer

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) HasFailAnswer() bool`

HasFailAnswer returns a boolean if a field has been set.

### GetNote

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetGageType

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetGageType() string`

GetGageType returns the GageType field if non-nil, zero value otherwise.

### GetGageTypeOk

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetGageTypeOk() (*string, bool)`

GetGageTypeOk returns a tuple with the GageType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGageType

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) SetGageType(v string)`

SetGageType sets GageType field to given value.

### HasGageType

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) HasGageType() bool`

HasGageType returns a boolean if a field has been set.

### GetGageNote

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetGageNote() string`

GetGageNote returns the GageNote field if non-nil, zero value otherwise.

### GetGageNoteOk

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetGageNoteOk() (*string, bool)`

GetGageNoteOk returns a tuple with the GageNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGageNote

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) SetGageNote(v string)`

SetGageNote sets GageNote field to given value.

### HasGageNote

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) HasGageNote() bool`

HasGageNote returns a boolean if a field has been set.

### GetPartSpecificGages

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetPartSpecificGages() []PartSpecificGagesItem`

GetPartSpecificGages returns the PartSpecificGages field if non-nil, zero value otherwise.

### GetPartSpecificGagesOk

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetPartSpecificGagesOk() (*[]PartSpecificGagesItem, bool)`

GetPartSpecificGagesOk returns a tuple with the PartSpecificGages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartSpecificGages

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) SetPartSpecificGages(v []PartSpecificGagesItem)`

SetPartSpecificGages sets PartSpecificGages field to given value.

### HasPartSpecificGages

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) HasPartSpecificGages() bool`

HasPartSpecificGages returns a boolean if a field has been set.

### GetSamplePlan

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetSamplePlan() string`

GetSamplePlan returns the SamplePlan field if non-nil, zero value otherwise.

### GetSamplePlanOk

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetSamplePlanOk() (*string, bool)`

GetSamplePlanOk returns a tuple with the SamplePlan field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSamplePlan

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) SetSamplePlan(v string)`

SetSamplePlan sets SamplePlan field to given value.

### HasSamplePlan

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) HasSamplePlan() bool`

HasSamplePlan returns a boolean if a field has been set.

### GetCustomChecksheetDataCollectionType

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetCustomChecksheetDataCollectionType() string`

GetCustomChecksheetDataCollectionType returns the CustomChecksheetDataCollectionType field if non-nil, zero value otherwise.

### GetCustomChecksheetDataCollectionTypeOk

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetCustomChecksheetDataCollectionTypeOk() (*string, bool)`

GetCustomChecksheetDataCollectionTypeOk returns a tuple with the CustomChecksheetDataCollectionType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomChecksheetDataCollectionType

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) SetCustomChecksheetDataCollectionType(v string)`

SetCustomChecksheetDataCollectionType sets CustomChecksheetDataCollectionType field to given value.

### HasCustomChecksheetDataCollectionType

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) HasCustomChecksheetDataCollectionType() bool`

HasCustomChecksheetDataCollectionType returns a boolean if a field has been set.

### GetReactionPlan

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetReactionPlan() string`

GetReactionPlan returns the ReactionPlan field if non-nil, zero value otherwise.

### GetReactionPlanOk

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetReactionPlanOk() (*string, bool)`

GetReactionPlanOk returns a tuple with the ReactionPlan field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReactionPlan

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) SetReactionPlan(v string)`

SetReactionPlan sets ReactionPlan field to given value.

### HasReactionPlan

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) HasReactionPlan() bool`

HasReactionPlan returns a boolean if a field has been set.

### GetReactionPlanOwner

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetReactionPlanOwner() string`

GetReactionPlanOwner returns the ReactionPlanOwner field if non-nil, zero value otherwise.

### GetReactionPlanOwnerOk

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetReactionPlanOwnerOk() (*string, bool)`

GetReactionPlanOwnerOk returns a tuple with the ReactionPlanOwner field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReactionPlanOwner

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) SetReactionPlanOwner(v string)`

SetReactionPlanOwner sets ReactionPlanOwner field to given value.

### HasReactionPlanOwner

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) HasReactionPlanOwner() bool`

HasReactionPlanOwner returns a boolean if a field has been set.

### GetDefaultAttributeAnswerPass

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetDefaultAttributeAnswerPass() bool`

GetDefaultAttributeAnswerPass returns the DefaultAttributeAnswerPass field if non-nil, zero value otherwise.

### GetDefaultAttributeAnswerPassOk

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetDefaultAttributeAnswerPassOk() (*bool, bool)`

GetDefaultAttributeAnswerPassOk returns a tuple with the DefaultAttributeAnswerPass field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultAttributeAnswerPass

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) SetDefaultAttributeAnswerPass(v bool)`

SetDefaultAttributeAnswerPass sets DefaultAttributeAnswerPass field to given value.

### HasDefaultAttributeAnswerPass

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) HasDefaultAttributeAnswerPass() bool`

HasDefaultAttributeAnswerPass returns a boolean if a field has been set.

### GetSortOrder

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetSortOrder() float64`

GetSortOrder returns the SortOrder field if non-nil, zero value otherwise.

### GetSortOrderOk

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetSortOrderOk() (*float64, bool)`

GetSortOrderOk returns a tuple with the SortOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSortOrder

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) SetSortOrder(v float64)`

SetSortOrder sets SortOrder field to given value.

### HasSortOrder

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) HasSortOrder() bool`

HasSortOrder returns a boolean if a field has been set.

### GetChecksheetSortOrder

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetChecksheetSortOrder() float64`

GetChecksheetSortOrder returns the ChecksheetSortOrder field if non-nil, zero value otherwise.

### GetChecksheetSortOrderOk

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetChecksheetSortOrderOk() (*float64, bool)`

GetChecksheetSortOrderOk returns a tuple with the ChecksheetSortOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChecksheetSortOrder

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) SetChecksheetSortOrder(v float64)`

SetChecksheetSortOrder sets ChecksheetSortOrder field to given value.

### HasChecksheetSortOrder

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) HasChecksheetSortOrder() bool`

HasChecksheetSortOrder returns a boolean if a field has been set.

### GetSymbol

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetSymbol() string`

GetSymbol returns the Symbol field if non-nil, zero value otherwise.

### GetSymbolOk

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetSymbolOk() (*string, bool)`

GetSymbolOk returns a tuple with the Symbol field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSymbol

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) SetSymbol(v string)`

SetSymbol sets Symbol field to given value.

### HasSymbol

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) HasSymbol() bool`

HasSymbol returns a boolean if a field has been set.

### GetSymbolAbbreviation

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetSymbolAbbreviation() string`

GetSymbolAbbreviation returns the SymbolAbbreviation field if non-nil, zero value otherwise.

### GetSymbolAbbreviationOk

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetSymbolAbbreviationOk() (*string, bool)`

GetSymbolAbbreviationOk returns a tuple with the SymbolAbbreviation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSymbolAbbreviation

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) SetSymbolAbbreviation(v string)`

SetSymbolAbbreviation sets SymbolAbbreviation field to given value.

### HasSymbolAbbreviation

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) HasSymbolAbbreviation() bool`

HasSymbolAbbreviation returns a boolean if a field has been set.

### GetTrackFailureModes

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetTrackFailureModes() bool`

GetTrackFailureModes returns the TrackFailureModes field if non-nil, zero value otherwise.

### GetTrackFailureModesOk

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) GetTrackFailureModesOk() (*bool, bool)`

GetTrackFailureModesOk returns a tuple with the TrackFailureModes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackFailureModes

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) SetTrackFailureModes(v bool)`

SetTrackFailureModes sets TrackFailureModes field to given value.

### HasTrackFailureModes

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanLineResponse) HasTrackFailureModes() bool`

HasTrackFailureModes returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


