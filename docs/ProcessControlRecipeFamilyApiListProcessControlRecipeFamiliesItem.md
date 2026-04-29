# ProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | ID representing the Process Control Recipe Family. | [optional] 
**Code** | Pointer to **string** | The Process Control Recipe Family Code. | [optional] 
**Name** | Pointer to **string** | The Process Control Recipe Family Name. | [optional] 
**Type** | Pointer to **string** | The Process Control Recipe Family Type. | [optional] 
**OperationId** | Pointer to **string** | ID representing the Operation. | [optional] 
**ControlPlanId** | Pointer to **string** | ID representing the Control Plan. | [optional] 
**PartIds** | Pointer to **[]string** | A list of IDs representing the Parts. | [optional] 
**ProcessControlRecipeIds** | Pointer to **[]string** | A list of IDs representing the Process Control Recipes. | [optional] 
**UpdatedDate** | Pointer to **time.Time** | The Updated Date. | [optional] 

## Methods

### NewProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItem

`func NewProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItem() *ProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItem`

NewProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItem instantiates a new ProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItemWithDefaults

`func NewProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItemWithDefaults() *ProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItem`

NewProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItemWithDefaults instantiates a new ProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItem) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *ProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItem) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCode

`func (o *ProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItem) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *ProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItem) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *ProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItem) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *ProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItem) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetName

`func (o *ProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItem) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItem) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItem) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItem) HasName() bool`

HasName returns a boolean if a field has been set.

### GetType

`func (o *ProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItem) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItem) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItem) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *ProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItem) HasType() bool`

HasType returns a boolean if a field has been set.

### GetOperationId

`func (o *ProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItem) GetOperationId() string`

GetOperationId returns the OperationId field if non-nil, zero value otherwise.

### GetOperationIdOk

`func (o *ProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItem) GetOperationIdOk() (*string, bool)`

GetOperationIdOk returns a tuple with the OperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationId

`func (o *ProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItem) SetOperationId(v string)`

SetOperationId sets OperationId field to given value.

### HasOperationId

`func (o *ProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItem) HasOperationId() bool`

HasOperationId returns a boolean if a field has been set.

### GetControlPlanId

`func (o *ProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItem) GetControlPlanId() string`

GetControlPlanId returns the ControlPlanId field if non-nil, zero value otherwise.

### GetControlPlanIdOk

`func (o *ProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItem) GetControlPlanIdOk() (*string, bool)`

GetControlPlanIdOk returns a tuple with the ControlPlanId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetControlPlanId

`func (o *ProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItem) SetControlPlanId(v string)`

SetControlPlanId sets ControlPlanId field to given value.

### HasControlPlanId

`func (o *ProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItem) HasControlPlanId() bool`

HasControlPlanId returns a boolean if a field has been set.

### GetPartIds

`func (o *ProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItem) GetPartIds() []string`

GetPartIds returns the PartIds field if non-nil, zero value otherwise.

### GetPartIdsOk

`func (o *ProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItem) GetPartIdsOk() (*[]string, bool)`

GetPartIdsOk returns a tuple with the PartIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartIds

`func (o *ProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItem) SetPartIds(v []string)`

SetPartIds sets PartIds field to given value.

### HasPartIds

`func (o *ProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItem) HasPartIds() bool`

HasPartIds returns a boolean if a field has been set.

### GetProcessControlRecipeIds

`func (o *ProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItem) GetProcessControlRecipeIds() []string`

GetProcessControlRecipeIds returns the ProcessControlRecipeIds field if non-nil, zero value otherwise.

### GetProcessControlRecipeIdsOk

`func (o *ProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItem) GetProcessControlRecipeIdsOk() (*[]string, bool)`

GetProcessControlRecipeIdsOk returns a tuple with the ProcessControlRecipeIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessControlRecipeIds

`func (o *ProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItem) SetProcessControlRecipeIds(v []string)`

SetProcessControlRecipeIds sets ProcessControlRecipeIds field to given value.

### HasProcessControlRecipeIds

`func (o *ProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItem) HasProcessControlRecipeIds() bool`

HasProcessControlRecipeIds returns a boolean if a field has been set.

### GetUpdatedDate

`func (o *ProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItem) GetUpdatedDate() time.Time`

GetUpdatedDate returns the UpdatedDate field if non-nil, zero value otherwise.

### GetUpdatedDateOk

`func (o *ProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItem) GetUpdatedDateOk() (*time.Time, bool)`

GetUpdatedDateOk returns a tuple with the UpdatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedDate

`func (o *ProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItem) SetUpdatedDate(v time.Time)`

SetUpdatedDate sets UpdatedDate field to given value.

### HasUpdatedDate

`func (o *ProcessControlRecipeFamilyApiListProcessControlRecipeFamiliesItem) HasUpdatedDate() bool`

HasUpdatedDate returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


