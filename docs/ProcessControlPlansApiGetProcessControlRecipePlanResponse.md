# ProcessControlPlansApiGetProcessControlRecipePlanResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | ID representing the Control Plan. | [optional] 
**BuildingCode** | Pointer to **string** | The Control Plan building code. | [optional] 
**BuildingId** | Pointer to **string** | ID representing the Control Plan building. | [optional] 
**ControlPlanNo** | Pointer to **float64** | The Control Plan number. | [optional] 
**ControlPlanStatus** | Pointer to **string** | The Control Plan status. | [optional] 
**ControlPlanType** | Pointer to **string** | The Control Plan type. | [optional] 
**Description** | Pointer to **string** | The Control Plan description. | [optional] 
**ExternalDocumentId** | Pointer to **string** | The Control Plan external document ID. | [optional] 
**ExternalDocumentRevisionLevel** | Pointer to **string** | The revision level of the external document. | [optional] 
**OriginalDate** | Pointer to **time.Time** | The original date of the Control Plan. | [optional] 
**Primary** | Pointer to **bool** | The primary flag. | [optional] 
**RevisionDate** | Pointer to **time.Time** | The Control Plan revision date. | [optional] 
**ProcessControlRecipeFamilyId** | Pointer to **string** | The Process Control Recipe Family ID. | [optional] 

## Methods

### NewProcessControlPlansApiGetProcessControlRecipePlanResponse

`func NewProcessControlPlansApiGetProcessControlRecipePlanResponse() *ProcessControlPlansApiGetProcessControlRecipePlanResponse`

NewProcessControlPlansApiGetProcessControlRecipePlanResponse instantiates a new ProcessControlPlansApiGetProcessControlRecipePlanResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProcessControlPlansApiGetProcessControlRecipePlanResponseWithDefaults

`func NewProcessControlPlansApiGetProcessControlRecipePlanResponseWithDefaults() *ProcessControlPlansApiGetProcessControlRecipePlanResponse`

NewProcessControlPlansApiGetProcessControlRecipePlanResponseWithDefaults instantiates a new ProcessControlPlansApiGetProcessControlRecipePlanResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetBuildingCode

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) GetBuildingCode() string`

GetBuildingCode returns the BuildingCode field if non-nil, zero value otherwise.

### GetBuildingCodeOk

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) GetBuildingCodeOk() (*string, bool)`

GetBuildingCodeOk returns a tuple with the BuildingCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildingCode

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) SetBuildingCode(v string)`

SetBuildingCode sets BuildingCode field to given value.

### HasBuildingCode

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) HasBuildingCode() bool`

HasBuildingCode returns a boolean if a field has been set.

### GetBuildingId

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) GetBuildingId() string`

GetBuildingId returns the BuildingId field if non-nil, zero value otherwise.

### GetBuildingIdOk

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) GetBuildingIdOk() (*string, bool)`

GetBuildingIdOk returns a tuple with the BuildingId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildingId

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) SetBuildingId(v string)`

SetBuildingId sets BuildingId field to given value.

### HasBuildingId

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) HasBuildingId() bool`

HasBuildingId returns a boolean if a field has been set.

### GetControlPlanNo

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) GetControlPlanNo() float64`

GetControlPlanNo returns the ControlPlanNo field if non-nil, zero value otherwise.

### GetControlPlanNoOk

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) GetControlPlanNoOk() (*float64, bool)`

GetControlPlanNoOk returns a tuple with the ControlPlanNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetControlPlanNo

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) SetControlPlanNo(v float64)`

SetControlPlanNo sets ControlPlanNo field to given value.

### HasControlPlanNo

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) HasControlPlanNo() bool`

HasControlPlanNo returns a boolean if a field has been set.

### GetControlPlanStatus

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) GetControlPlanStatus() string`

GetControlPlanStatus returns the ControlPlanStatus field if non-nil, zero value otherwise.

### GetControlPlanStatusOk

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) GetControlPlanStatusOk() (*string, bool)`

GetControlPlanStatusOk returns a tuple with the ControlPlanStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetControlPlanStatus

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) SetControlPlanStatus(v string)`

SetControlPlanStatus sets ControlPlanStatus field to given value.

### HasControlPlanStatus

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) HasControlPlanStatus() bool`

HasControlPlanStatus returns a boolean if a field has been set.

### GetControlPlanType

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) GetControlPlanType() string`

GetControlPlanType returns the ControlPlanType field if non-nil, zero value otherwise.

### GetControlPlanTypeOk

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) GetControlPlanTypeOk() (*string, bool)`

GetControlPlanTypeOk returns a tuple with the ControlPlanType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetControlPlanType

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) SetControlPlanType(v string)`

SetControlPlanType sets ControlPlanType field to given value.

### HasControlPlanType

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) HasControlPlanType() bool`

HasControlPlanType returns a boolean if a field has been set.

### GetDescription

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetExternalDocumentId

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) GetExternalDocumentId() string`

GetExternalDocumentId returns the ExternalDocumentId field if non-nil, zero value otherwise.

### GetExternalDocumentIdOk

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) GetExternalDocumentIdOk() (*string, bool)`

GetExternalDocumentIdOk returns a tuple with the ExternalDocumentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalDocumentId

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) SetExternalDocumentId(v string)`

SetExternalDocumentId sets ExternalDocumentId field to given value.

### HasExternalDocumentId

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) HasExternalDocumentId() bool`

HasExternalDocumentId returns a boolean if a field has been set.

### GetExternalDocumentRevisionLevel

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) GetExternalDocumentRevisionLevel() string`

GetExternalDocumentRevisionLevel returns the ExternalDocumentRevisionLevel field if non-nil, zero value otherwise.

### GetExternalDocumentRevisionLevelOk

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) GetExternalDocumentRevisionLevelOk() (*string, bool)`

GetExternalDocumentRevisionLevelOk returns a tuple with the ExternalDocumentRevisionLevel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalDocumentRevisionLevel

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) SetExternalDocumentRevisionLevel(v string)`

SetExternalDocumentRevisionLevel sets ExternalDocumentRevisionLevel field to given value.

### HasExternalDocumentRevisionLevel

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) HasExternalDocumentRevisionLevel() bool`

HasExternalDocumentRevisionLevel returns a boolean if a field has been set.

### GetOriginalDate

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) GetOriginalDate() time.Time`

GetOriginalDate returns the OriginalDate field if non-nil, zero value otherwise.

### GetOriginalDateOk

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) GetOriginalDateOk() (*time.Time, bool)`

GetOriginalDateOk returns a tuple with the OriginalDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginalDate

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) SetOriginalDate(v time.Time)`

SetOriginalDate sets OriginalDate field to given value.

### HasOriginalDate

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) HasOriginalDate() bool`

HasOriginalDate returns a boolean if a field has been set.

### GetPrimary

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) GetPrimary() bool`

GetPrimary returns the Primary field if non-nil, zero value otherwise.

### GetPrimaryOk

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) GetPrimaryOk() (*bool, bool)`

GetPrimaryOk returns a tuple with the Primary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrimary

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) SetPrimary(v bool)`

SetPrimary sets Primary field to given value.

### HasPrimary

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) HasPrimary() bool`

HasPrimary returns a boolean if a field has been set.

### GetRevisionDate

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) GetRevisionDate() time.Time`

GetRevisionDate returns the RevisionDate field if non-nil, zero value otherwise.

### GetRevisionDateOk

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) GetRevisionDateOk() (*time.Time, bool)`

GetRevisionDateOk returns a tuple with the RevisionDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevisionDate

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) SetRevisionDate(v time.Time)`

SetRevisionDate sets RevisionDate field to given value.

### HasRevisionDate

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) HasRevisionDate() bool`

HasRevisionDate returns a boolean if a field has been set.

### GetProcessControlRecipeFamilyId

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) GetProcessControlRecipeFamilyId() string`

GetProcessControlRecipeFamilyId returns the ProcessControlRecipeFamilyId field if non-nil, zero value otherwise.

### GetProcessControlRecipeFamilyIdOk

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) GetProcessControlRecipeFamilyIdOk() (*string, bool)`

GetProcessControlRecipeFamilyIdOk returns a tuple with the ProcessControlRecipeFamilyId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessControlRecipeFamilyId

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) SetProcessControlRecipeFamilyId(v string)`

SetProcessControlRecipeFamilyId sets ProcessControlRecipeFamilyId field to given value.

### HasProcessControlRecipeFamilyId

`func (o *ProcessControlPlansApiGetProcessControlRecipePlanResponse) HasProcessControlRecipeFamilyId() bool`

HasProcessControlRecipeFamilyId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


