# ControlPlansApiListControlPlansItem

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
**PartId** | Pointer to **string** | ID representing the Control Plan part number. | [optional] 
**PartNo** | Pointer to **string** | The Control Plan part number. | [optional] 
**PartRevision** | Pointer to **string** | The Control Plan part revision. | [optional] 
**PartName** | Pointer to **string** | The Control Plan part name. | [optional] 
**Primary** | Pointer to **bool** | The primary flag. | [optional] 
**RevisionDate** | Pointer to **time.Time** | The Control Plan revision date. | [optional] 

## Methods

### NewControlPlansApiListControlPlansItem

`func NewControlPlansApiListControlPlansItem() *ControlPlansApiListControlPlansItem`

NewControlPlansApiListControlPlansItem instantiates a new ControlPlansApiListControlPlansItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewControlPlansApiListControlPlansItemWithDefaults

`func NewControlPlansApiListControlPlansItemWithDefaults() *ControlPlansApiListControlPlansItem`

NewControlPlansApiListControlPlansItemWithDefaults instantiates a new ControlPlansApiListControlPlansItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ControlPlansApiListControlPlansItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ControlPlansApiListControlPlansItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ControlPlansApiListControlPlansItem) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *ControlPlansApiListControlPlansItem) HasId() bool`

HasId returns a boolean if a field has been set.

### GetBuildingCode

`func (o *ControlPlansApiListControlPlansItem) GetBuildingCode() string`

GetBuildingCode returns the BuildingCode field if non-nil, zero value otherwise.

### GetBuildingCodeOk

`func (o *ControlPlansApiListControlPlansItem) GetBuildingCodeOk() (*string, bool)`

GetBuildingCodeOk returns a tuple with the BuildingCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildingCode

`func (o *ControlPlansApiListControlPlansItem) SetBuildingCode(v string)`

SetBuildingCode sets BuildingCode field to given value.

### HasBuildingCode

`func (o *ControlPlansApiListControlPlansItem) HasBuildingCode() bool`

HasBuildingCode returns a boolean if a field has been set.

### GetBuildingId

`func (o *ControlPlansApiListControlPlansItem) GetBuildingId() string`

GetBuildingId returns the BuildingId field if non-nil, zero value otherwise.

### GetBuildingIdOk

`func (o *ControlPlansApiListControlPlansItem) GetBuildingIdOk() (*string, bool)`

GetBuildingIdOk returns a tuple with the BuildingId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildingId

`func (o *ControlPlansApiListControlPlansItem) SetBuildingId(v string)`

SetBuildingId sets BuildingId field to given value.

### HasBuildingId

`func (o *ControlPlansApiListControlPlansItem) HasBuildingId() bool`

HasBuildingId returns a boolean if a field has been set.

### GetControlPlanNo

`func (o *ControlPlansApiListControlPlansItem) GetControlPlanNo() float64`

GetControlPlanNo returns the ControlPlanNo field if non-nil, zero value otherwise.

### GetControlPlanNoOk

`func (o *ControlPlansApiListControlPlansItem) GetControlPlanNoOk() (*float64, bool)`

GetControlPlanNoOk returns a tuple with the ControlPlanNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetControlPlanNo

`func (o *ControlPlansApiListControlPlansItem) SetControlPlanNo(v float64)`

SetControlPlanNo sets ControlPlanNo field to given value.

### HasControlPlanNo

`func (o *ControlPlansApiListControlPlansItem) HasControlPlanNo() bool`

HasControlPlanNo returns a boolean if a field has been set.

### GetControlPlanStatus

`func (o *ControlPlansApiListControlPlansItem) GetControlPlanStatus() string`

GetControlPlanStatus returns the ControlPlanStatus field if non-nil, zero value otherwise.

### GetControlPlanStatusOk

`func (o *ControlPlansApiListControlPlansItem) GetControlPlanStatusOk() (*string, bool)`

GetControlPlanStatusOk returns a tuple with the ControlPlanStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetControlPlanStatus

`func (o *ControlPlansApiListControlPlansItem) SetControlPlanStatus(v string)`

SetControlPlanStatus sets ControlPlanStatus field to given value.

### HasControlPlanStatus

`func (o *ControlPlansApiListControlPlansItem) HasControlPlanStatus() bool`

HasControlPlanStatus returns a boolean if a field has been set.

### GetControlPlanType

`func (o *ControlPlansApiListControlPlansItem) GetControlPlanType() string`

GetControlPlanType returns the ControlPlanType field if non-nil, zero value otherwise.

### GetControlPlanTypeOk

`func (o *ControlPlansApiListControlPlansItem) GetControlPlanTypeOk() (*string, bool)`

GetControlPlanTypeOk returns a tuple with the ControlPlanType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetControlPlanType

`func (o *ControlPlansApiListControlPlansItem) SetControlPlanType(v string)`

SetControlPlanType sets ControlPlanType field to given value.

### HasControlPlanType

`func (o *ControlPlansApiListControlPlansItem) HasControlPlanType() bool`

HasControlPlanType returns a boolean if a field has been set.

### GetDescription

`func (o *ControlPlansApiListControlPlansItem) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ControlPlansApiListControlPlansItem) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ControlPlansApiListControlPlansItem) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ControlPlansApiListControlPlansItem) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetExternalDocumentId

`func (o *ControlPlansApiListControlPlansItem) GetExternalDocumentId() string`

GetExternalDocumentId returns the ExternalDocumentId field if non-nil, zero value otherwise.

### GetExternalDocumentIdOk

`func (o *ControlPlansApiListControlPlansItem) GetExternalDocumentIdOk() (*string, bool)`

GetExternalDocumentIdOk returns a tuple with the ExternalDocumentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalDocumentId

`func (o *ControlPlansApiListControlPlansItem) SetExternalDocumentId(v string)`

SetExternalDocumentId sets ExternalDocumentId field to given value.

### HasExternalDocumentId

`func (o *ControlPlansApiListControlPlansItem) HasExternalDocumentId() bool`

HasExternalDocumentId returns a boolean if a field has been set.

### GetExternalDocumentRevisionLevel

`func (o *ControlPlansApiListControlPlansItem) GetExternalDocumentRevisionLevel() string`

GetExternalDocumentRevisionLevel returns the ExternalDocumentRevisionLevel field if non-nil, zero value otherwise.

### GetExternalDocumentRevisionLevelOk

`func (o *ControlPlansApiListControlPlansItem) GetExternalDocumentRevisionLevelOk() (*string, bool)`

GetExternalDocumentRevisionLevelOk returns a tuple with the ExternalDocumentRevisionLevel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalDocumentRevisionLevel

`func (o *ControlPlansApiListControlPlansItem) SetExternalDocumentRevisionLevel(v string)`

SetExternalDocumentRevisionLevel sets ExternalDocumentRevisionLevel field to given value.

### HasExternalDocumentRevisionLevel

`func (o *ControlPlansApiListControlPlansItem) HasExternalDocumentRevisionLevel() bool`

HasExternalDocumentRevisionLevel returns a boolean if a field has been set.

### GetOriginalDate

`func (o *ControlPlansApiListControlPlansItem) GetOriginalDate() time.Time`

GetOriginalDate returns the OriginalDate field if non-nil, zero value otherwise.

### GetOriginalDateOk

`func (o *ControlPlansApiListControlPlansItem) GetOriginalDateOk() (*time.Time, bool)`

GetOriginalDateOk returns a tuple with the OriginalDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginalDate

`func (o *ControlPlansApiListControlPlansItem) SetOriginalDate(v time.Time)`

SetOriginalDate sets OriginalDate field to given value.

### HasOriginalDate

`func (o *ControlPlansApiListControlPlansItem) HasOriginalDate() bool`

HasOriginalDate returns a boolean if a field has been set.

### GetPartId

`func (o *ControlPlansApiListControlPlansItem) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *ControlPlansApiListControlPlansItem) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *ControlPlansApiListControlPlansItem) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *ControlPlansApiListControlPlansItem) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetPartNo

`func (o *ControlPlansApiListControlPlansItem) GetPartNo() string`

GetPartNo returns the PartNo field if non-nil, zero value otherwise.

### GetPartNoOk

`func (o *ControlPlansApiListControlPlansItem) GetPartNoOk() (*string, bool)`

GetPartNoOk returns a tuple with the PartNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNo

`func (o *ControlPlansApiListControlPlansItem) SetPartNo(v string)`

SetPartNo sets PartNo field to given value.

### HasPartNo

`func (o *ControlPlansApiListControlPlansItem) HasPartNo() bool`

HasPartNo returns a boolean if a field has been set.

### GetPartRevision

`func (o *ControlPlansApiListControlPlansItem) GetPartRevision() string`

GetPartRevision returns the PartRevision field if non-nil, zero value otherwise.

### GetPartRevisionOk

`func (o *ControlPlansApiListControlPlansItem) GetPartRevisionOk() (*string, bool)`

GetPartRevisionOk returns a tuple with the PartRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartRevision

`func (o *ControlPlansApiListControlPlansItem) SetPartRevision(v string)`

SetPartRevision sets PartRevision field to given value.

### HasPartRevision

`func (o *ControlPlansApiListControlPlansItem) HasPartRevision() bool`

HasPartRevision returns a boolean if a field has been set.

### GetPartName

`func (o *ControlPlansApiListControlPlansItem) GetPartName() string`

GetPartName returns the PartName field if non-nil, zero value otherwise.

### GetPartNameOk

`func (o *ControlPlansApiListControlPlansItem) GetPartNameOk() (*string, bool)`

GetPartNameOk returns a tuple with the PartName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartName

`func (o *ControlPlansApiListControlPlansItem) SetPartName(v string)`

SetPartName sets PartName field to given value.

### HasPartName

`func (o *ControlPlansApiListControlPlansItem) HasPartName() bool`

HasPartName returns a boolean if a field has been set.

### GetPrimary

`func (o *ControlPlansApiListControlPlansItem) GetPrimary() bool`

GetPrimary returns the Primary field if non-nil, zero value otherwise.

### GetPrimaryOk

`func (o *ControlPlansApiListControlPlansItem) GetPrimaryOk() (*bool, bool)`

GetPrimaryOk returns a tuple with the Primary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrimary

`func (o *ControlPlansApiListControlPlansItem) SetPrimary(v bool)`

SetPrimary sets Primary field to given value.

### HasPrimary

`func (o *ControlPlansApiListControlPlansItem) HasPrimary() bool`

HasPrimary returns a boolean if a field has been set.

### GetRevisionDate

`func (o *ControlPlansApiListControlPlansItem) GetRevisionDate() time.Time`

GetRevisionDate returns the RevisionDate field if non-nil, zero value otherwise.

### GetRevisionDateOk

`func (o *ControlPlansApiListControlPlansItem) GetRevisionDateOk() (*time.Time, bool)`

GetRevisionDateOk returns a tuple with the RevisionDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevisionDate

`func (o *ControlPlansApiListControlPlansItem) SetRevisionDate(v time.Time)`

SetRevisionDate sets RevisionDate field to given value.

### HasRevisionDate

`func (o *ControlPlansApiListControlPlansItem) HasRevisionDate() bool`

HasRevisionDate returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


