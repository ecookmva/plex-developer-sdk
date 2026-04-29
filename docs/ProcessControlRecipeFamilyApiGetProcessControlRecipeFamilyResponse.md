# ProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponse

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

### NewProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponse

`func NewProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponse() *ProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponse`

NewProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponse instantiates a new ProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponseWithDefaults

`func NewProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponseWithDefaults() *ProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponse`

NewProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponseWithDefaults instantiates a new ProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *ProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCode

`func (o *ProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponse) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *ProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponse) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *ProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponse) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *ProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponse) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetName

`func (o *ProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponse) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponse) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponse) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponse) HasName() bool`

HasName returns a boolean if a field has been set.

### GetType

`func (o *ProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponse) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponse) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponse) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *ProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponse) HasType() bool`

HasType returns a boolean if a field has been set.

### GetOperationId

`func (o *ProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponse) GetOperationId() string`

GetOperationId returns the OperationId field if non-nil, zero value otherwise.

### GetOperationIdOk

`func (o *ProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponse) GetOperationIdOk() (*string, bool)`

GetOperationIdOk returns a tuple with the OperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationId

`func (o *ProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponse) SetOperationId(v string)`

SetOperationId sets OperationId field to given value.

### HasOperationId

`func (o *ProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponse) HasOperationId() bool`

HasOperationId returns a boolean if a field has been set.

### GetControlPlanId

`func (o *ProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponse) GetControlPlanId() string`

GetControlPlanId returns the ControlPlanId field if non-nil, zero value otherwise.

### GetControlPlanIdOk

`func (o *ProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponse) GetControlPlanIdOk() (*string, bool)`

GetControlPlanIdOk returns a tuple with the ControlPlanId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetControlPlanId

`func (o *ProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponse) SetControlPlanId(v string)`

SetControlPlanId sets ControlPlanId field to given value.

### HasControlPlanId

`func (o *ProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponse) HasControlPlanId() bool`

HasControlPlanId returns a boolean if a field has been set.

### GetPartIds

`func (o *ProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponse) GetPartIds() []string`

GetPartIds returns the PartIds field if non-nil, zero value otherwise.

### GetPartIdsOk

`func (o *ProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponse) GetPartIdsOk() (*[]string, bool)`

GetPartIdsOk returns a tuple with the PartIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartIds

`func (o *ProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponse) SetPartIds(v []string)`

SetPartIds sets PartIds field to given value.

### HasPartIds

`func (o *ProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponse) HasPartIds() bool`

HasPartIds returns a boolean if a field has been set.

### GetProcessControlRecipeIds

`func (o *ProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponse) GetProcessControlRecipeIds() []string`

GetProcessControlRecipeIds returns the ProcessControlRecipeIds field if non-nil, zero value otherwise.

### GetProcessControlRecipeIdsOk

`func (o *ProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponse) GetProcessControlRecipeIdsOk() (*[]string, bool)`

GetProcessControlRecipeIdsOk returns a tuple with the ProcessControlRecipeIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessControlRecipeIds

`func (o *ProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponse) SetProcessControlRecipeIds(v []string)`

SetProcessControlRecipeIds sets ProcessControlRecipeIds field to given value.

### HasProcessControlRecipeIds

`func (o *ProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponse) HasProcessControlRecipeIds() bool`

HasProcessControlRecipeIds returns a boolean if a field has been set.

### GetUpdatedDate

`func (o *ProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponse) GetUpdatedDate() time.Time`

GetUpdatedDate returns the UpdatedDate field if non-nil, zero value otherwise.

### GetUpdatedDateOk

`func (o *ProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponse) GetUpdatedDateOk() (*time.Time, bool)`

GetUpdatedDateOk returns a tuple with the UpdatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedDate

`func (o *ProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponse) SetUpdatedDate(v time.Time)`

SetUpdatedDate sets UpdatedDate field to given value.

### HasUpdatedDate

`func (o *ProcessControlRecipeFamilyApiGetProcessControlRecipeFamilyResponse) HasUpdatedDate() bool`

HasUpdatedDate returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


