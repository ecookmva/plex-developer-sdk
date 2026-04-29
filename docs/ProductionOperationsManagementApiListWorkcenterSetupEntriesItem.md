# ProductionOperationsManagementApiListWorkcenterSetupEntriesItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**WorkcenterId** | Pointer to **string** | Gets or sets the workcenterId (UUID) of the WorkCenter that was running jobs for the requested query parameters | [optional] 
**WorkcenterCode** | Pointer to **string** | Gets or sets the workcenterCode of the WorkCenter that was running jobs for the requested query | [optional] 
**SetupDateTime** | Pointer to **time.Time** | Gets or sets the date and time when the Setup was provisioned in the WorkCenter that was running jobs for the requested query | [optional] 
**SetupDateTimeChange** | Pointer to **time.Time** | Gets or sets the date and time when the Setup was updated/deleted in the WorkCenter that was running jobs for the requested query | [optional] 
**ParentPartId** | Pointer to **string** | Gets or sets the parent Part&#39;s Id (UUID) within a Setup in the WorkCenter that was running jobs for the requested query | [optional] 
**ParentPartNumber** | Pointer to **string** | Gets or sets the parent Part&#39;s Number within a Setup in the WorkCenter that was running jobs for the requested query | [optional] 
**ParentPartRevision** | Pointer to **string** | Gets or sets the parent Part&#39;s Revision within a Setup in the WorkCenter that was running jobs for the requested query | [optional] 
**ParentPartNumberRevision** | Pointer to **string** | Gets or sets the parent Part&#39;s Revision Number within a Setup in the WorkCenter that was running jobs for the requested query | [optional] 
**ParentPartOperationId** | Pointer to **string** | Gets or sets the parent Part&#39;s Operation id within a Setup in the WorkCenter that was running jobs for the requested query | [optional] 
**ParentPartOperationCode** | Pointer to **string** | Gets or sets the parent Part&#39;s Operation code within a Setup in the WorkCenter that was running jobs for the requested query | [optional] 
**ParentPartOperationNumber** | Pointer to **int32** | Gets or sets the parent Part&#39;s Operation Number within a Setup in the WorkCenter that was running jobs for the requested query | [optional] 
**ParentPartJobId** | Pointer to **string** | Gets or sets the parent Part&#39;s Job id within a Setup in the WorkCenter that was running jobs for the requested query | [optional] 
**ParentPartJobNumber** | Pointer to **string** | Gets or sets the parent Part&#39;s Job Number within a Setup in the WorkCenter that was running jobs for the requested query | [optional] 
**ParentPartJobOperationId** | Pointer to **string** | Gets or sets the parent Part&#39;s Job operation id within a Setup in the WorkCenter that was running jobs for the requested query | [optional] 
**ParentPartJobOperationNumber** | Pointer to **float64** | Gets or sets the parent Part&#39;s Job operation number within a Setup in the WorkCenter that was running jobs for the requested query | [optional] 
**ChildPartId** | Pointer to **string** | Gets or sets the child Part&#39;s Id (UUID) within a Setup in the WorkCenter that was running jobs for the requested query | [optional] 
**ChildPartNumber** | Pointer to **string** | Gets or sets the child Part&#39;s Number within a Setup in the WorkCenter that was running jobs for the requested query | [optional] 
**ChildPartRevision** | Pointer to **string** | Gets or sets the child Part&#39;s Revision within a Setup in the WorkCenter that was running jobs for the requested query | [optional] 
**ChildPartNumberRevision** | Pointer to **string** | Gets or sets the child Part&#39;s Revision Number within a Setup in the WorkCenter that was running jobs for the requested query | [optional] 
**ChildPartOperationId** | Pointer to **string** | Gets or sets the child Part&#39;s Operation id within a Setup in the WorkCenter that was running jobs for the requested query | [optional] 
**ChildPartOperationCode** | Pointer to **string** | Gets or sets the child Part&#39;s Operation code within a Setup in the WorkCenter that was running jobs for the requested query | [optional] 
**ChildPartOperationNumber** | Pointer to **int32** | Gets or sets the child Part&#39;s Operation Number within a Setup in the WorkCenter that was running jobs for the requested query | [optional] 
**ChildPartJobId** | Pointer to **string** | Gets or sets the child Part&#39;s Job id within a Setup in the WorkCenter that was running jobs for the requested query | [optional] 
**ChildPartJobNumber** | Pointer to **string** | Gets or sets the child Part&#39;s Job Number within a Setup in the WorkCenter that was running jobs for the requested query | [optional] 
**ChildPartJobOperationId** | Pointer to **string** | Gets or sets the child Part&#39;s Job operation id within a Setup in the WorkCenter that was running jobs for the requested query | [optional] 
**ChildPartJobOperationNumber** | Pointer to **float64** | Gets or sets the child Part&#39;s Job operation number within a Setup in the WorkCenter that was running jobs for the requested query | [optional] 
**DynamicMultiOut** | Pointer to **bool** | Gets or sets whether the performed Job is Dynamic MultiOut job within a Setup in the WorkCenter that was running jobs for the requested query | [optional] 
**TraditionalMultiOut** | Pointer to **bool** | Gets or sets whether the performed Job is Traditional MultiOut job within a Setup in the WorkCenter that was running jobs for the requested query | [optional] 
**Parent** | Pointer to **bool** | Gets or sets whether the part in question is a Parent part within a Setup in the WorkCenter that was running jobs for the requested query | [optional] 
**Companion** | Pointer to **bool** | Gets or sets whether the part in question is a Companion part within a Setup in the WorkCenter that was running jobs for the requested query | [optional] 

## Methods

### NewProductionOperationsManagementApiListWorkcenterSetupEntriesItem

`func NewProductionOperationsManagementApiListWorkcenterSetupEntriesItem() *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem`

NewProductionOperationsManagementApiListWorkcenterSetupEntriesItem instantiates a new ProductionOperationsManagementApiListWorkcenterSetupEntriesItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductionOperationsManagementApiListWorkcenterSetupEntriesItemWithDefaults

`func NewProductionOperationsManagementApiListWorkcenterSetupEntriesItemWithDefaults() *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem`

NewProductionOperationsManagementApiListWorkcenterSetupEntriesItemWithDefaults instantiates a new ProductionOperationsManagementApiListWorkcenterSetupEntriesItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetWorkcenterId

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetWorkcenterId() string`

GetWorkcenterId returns the WorkcenterId field if non-nil, zero value otherwise.

### GetWorkcenterIdOk

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetWorkcenterIdOk() (*string, bool)`

GetWorkcenterIdOk returns a tuple with the WorkcenterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkcenterId

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) SetWorkcenterId(v string)`

SetWorkcenterId sets WorkcenterId field to given value.

### HasWorkcenterId

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) HasWorkcenterId() bool`

HasWorkcenterId returns a boolean if a field has been set.

### GetWorkcenterCode

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetWorkcenterCode() string`

GetWorkcenterCode returns the WorkcenterCode field if non-nil, zero value otherwise.

### GetWorkcenterCodeOk

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetWorkcenterCodeOk() (*string, bool)`

GetWorkcenterCodeOk returns a tuple with the WorkcenterCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkcenterCode

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) SetWorkcenterCode(v string)`

SetWorkcenterCode sets WorkcenterCode field to given value.

### HasWorkcenterCode

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) HasWorkcenterCode() bool`

HasWorkcenterCode returns a boolean if a field has been set.

### GetSetupDateTime

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetSetupDateTime() time.Time`

GetSetupDateTime returns the SetupDateTime field if non-nil, zero value otherwise.

### GetSetupDateTimeOk

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetSetupDateTimeOk() (*time.Time, bool)`

GetSetupDateTimeOk returns a tuple with the SetupDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSetupDateTime

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) SetSetupDateTime(v time.Time)`

SetSetupDateTime sets SetupDateTime field to given value.

### HasSetupDateTime

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) HasSetupDateTime() bool`

HasSetupDateTime returns a boolean if a field has been set.

### GetSetupDateTimeChange

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetSetupDateTimeChange() time.Time`

GetSetupDateTimeChange returns the SetupDateTimeChange field if non-nil, zero value otherwise.

### GetSetupDateTimeChangeOk

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetSetupDateTimeChangeOk() (*time.Time, bool)`

GetSetupDateTimeChangeOk returns a tuple with the SetupDateTimeChange field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSetupDateTimeChange

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) SetSetupDateTimeChange(v time.Time)`

SetSetupDateTimeChange sets SetupDateTimeChange field to given value.

### HasSetupDateTimeChange

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) HasSetupDateTimeChange() bool`

HasSetupDateTimeChange returns a boolean if a field has been set.

### GetParentPartId

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetParentPartId() string`

GetParentPartId returns the ParentPartId field if non-nil, zero value otherwise.

### GetParentPartIdOk

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetParentPartIdOk() (*string, bool)`

GetParentPartIdOk returns a tuple with the ParentPartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentPartId

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) SetParentPartId(v string)`

SetParentPartId sets ParentPartId field to given value.

### HasParentPartId

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) HasParentPartId() bool`

HasParentPartId returns a boolean if a field has been set.

### GetParentPartNumber

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetParentPartNumber() string`

GetParentPartNumber returns the ParentPartNumber field if non-nil, zero value otherwise.

### GetParentPartNumberOk

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetParentPartNumberOk() (*string, bool)`

GetParentPartNumberOk returns a tuple with the ParentPartNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentPartNumber

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) SetParentPartNumber(v string)`

SetParentPartNumber sets ParentPartNumber field to given value.

### HasParentPartNumber

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) HasParentPartNumber() bool`

HasParentPartNumber returns a boolean if a field has been set.

### GetParentPartRevision

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetParentPartRevision() string`

GetParentPartRevision returns the ParentPartRevision field if non-nil, zero value otherwise.

### GetParentPartRevisionOk

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetParentPartRevisionOk() (*string, bool)`

GetParentPartRevisionOk returns a tuple with the ParentPartRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentPartRevision

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) SetParentPartRevision(v string)`

SetParentPartRevision sets ParentPartRevision field to given value.

### HasParentPartRevision

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) HasParentPartRevision() bool`

HasParentPartRevision returns a boolean if a field has been set.

### GetParentPartNumberRevision

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetParentPartNumberRevision() string`

GetParentPartNumberRevision returns the ParentPartNumberRevision field if non-nil, zero value otherwise.

### GetParentPartNumberRevisionOk

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetParentPartNumberRevisionOk() (*string, bool)`

GetParentPartNumberRevisionOk returns a tuple with the ParentPartNumberRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentPartNumberRevision

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) SetParentPartNumberRevision(v string)`

SetParentPartNumberRevision sets ParentPartNumberRevision field to given value.

### HasParentPartNumberRevision

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) HasParentPartNumberRevision() bool`

HasParentPartNumberRevision returns a boolean if a field has been set.

### GetParentPartOperationId

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetParentPartOperationId() string`

GetParentPartOperationId returns the ParentPartOperationId field if non-nil, zero value otherwise.

### GetParentPartOperationIdOk

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetParentPartOperationIdOk() (*string, bool)`

GetParentPartOperationIdOk returns a tuple with the ParentPartOperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentPartOperationId

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) SetParentPartOperationId(v string)`

SetParentPartOperationId sets ParentPartOperationId field to given value.

### HasParentPartOperationId

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) HasParentPartOperationId() bool`

HasParentPartOperationId returns a boolean if a field has been set.

### GetParentPartOperationCode

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetParentPartOperationCode() string`

GetParentPartOperationCode returns the ParentPartOperationCode field if non-nil, zero value otherwise.

### GetParentPartOperationCodeOk

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetParentPartOperationCodeOk() (*string, bool)`

GetParentPartOperationCodeOk returns a tuple with the ParentPartOperationCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentPartOperationCode

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) SetParentPartOperationCode(v string)`

SetParentPartOperationCode sets ParentPartOperationCode field to given value.

### HasParentPartOperationCode

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) HasParentPartOperationCode() bool`

HasParentPartOperationCode returns a boolean if a field has been set.

### GetParentPartOperationNumber

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetParentPartOperationNumber() int32`

GetParentPartOperationNumber returns the ParentPartOperationNumber field if non-nil, zero value otherwise.

### GetParentPartOperationNumberOk

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetParentPartOperationNumberOk() (*int32, bool)`

GetParentPartOperationNumberOk returns a tuple with the ParentPartOperationNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentPartOperationNumber

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) SetParentPartOperationNumber(v int32)`

SetParentPartOperationNumber sets ParentPartOperationNumber field to given value.

### HasParentPartOperationNumber

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) HasParentPartOperationNumber() bool`

HasParentPartOperationNumber returns a boolean if a field has been set.

### GetParentPartJobId

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetParentPartJobId() string`

GetParentPartJobId returns the ParentPartJobId field if non-nil, zero value otherwise.

### GetParentPartJobIdOk

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetParentPartJobIdOk() (*string, bool)`

GetParentPartJobIdOk returns a tuple with the ParentPartJobId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentPartJobId

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) SetParentPartJobId(v string)`

SetParentPartJobId sets ParentPartJobId field to given value.

### HasParentPartJobId

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) HasParentPartJobId() bool`

HasParentPartJobId returns a boolean if a field has been set.

### GetParentPartJobNumber

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetParentPartJobNumber() string`

GetParentPartJobNumber returns the ParentPartJobNumber field if non-nil, zero value otherwise.

### GetParentPartJobNumberOk

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetParentPartJobNumberOk() (*string, bool)`

GetParentPartJobNumberOk returns a tuple with the ParentPartJobNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentPartJobNumber

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) SetParentPartJobNumber(v string)`

SetParentPartJobNumber sets ParentPartJobNumber field to given value.

### HasParentPartJobNumber

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) HasParentPartJobNumber() bool`

HasParentPartJobNumber returns a boolean if a field has been set.

### GetParentPartJobOperationId

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetParentPartJobOperationId() string`

GetParentPartJobOperationId returns the ParentPartJobOperationId field if non-nil, zero value otherwise.

### GetParentPartJobOperationIdOk

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetParentPartJobOperationIdOk() (*string, bool)`

GetParentPartJobOperationIdOk returns a tuple with the ParentPartJobOperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentPartJobOperationId

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) SetParentPartJobOperationId(v string)`

SetParentPartJobOperationId sets ParentPartJobOperationId field to given value.

### HasParentPartJobOperationId

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) HasParentPartJobOperationId() bool`

HasParentPartJobOperationId returns a boolean if a field has been set.

### GetParentPartJobOperationNumber

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetParentPartJobOperationNumber() float64`

GetParentPartJobOperationNumber returns the ParentPartJobOperationNumber field if non-nil, zero value otherwise.

### GetParentPartJobOperationNumberOk

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetParentPartJobOperationNumberOk() (*float64, bool)`

GetParentPartJobOperationNumberOk returns a tuple with the ParentPartJobOperationNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentPartJobOperationNumber

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) SetParentPartJobOperationNumber(v float64)`

SetParentPartJobOperationNumber sets ParentPartJobOperationNumber field to given value.

### HasParentPartJobOperationNumber

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) HasParentPartJobOperationNumber() bool`

HasParentPartJobOperationNumber returns a boolean if a field has been set.

### GetChildPartId

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetChildPartId() string`

GetChildPartId returns the ChildPartId field if non-nil, zero value otherwise.

### GetChildPartIdOk

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetChildPartIdOk() (*string, bool)`

GetChildPartIdOk returns a tuple with the ChildPartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChildPartId

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) SetChildPartId(v string)`

SetChildPartId sets ChildPartId field to given value.

### HasChildPartId

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) HasChildPartId() bool`

HasChildPartId returns a boolean if a field has been set.

### GetChildPartNumber

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetChildPartNumber() string`

GetChildPartNumber returns the ChildPartNumber field if non-nil, zero value otherwise.

### GetChildPartNumberOk

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetChildPartNumberOk() (*string, bool)`

GetChildPartNumberOk returns a tuple with the ChildPartNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChildPartNumber

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) SetChildPartNumber(v string)`

SetChildPartNumber sets ChildPartNumber field to given value.

### HasChildPartNumber

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) HasChildPartNumber() bool`

HasChildPartNumber returns a boolean if a field has been set.

### GetChildPartRevision

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetChildPartRevision() string`

GetChildPartRevision returns the ChildPartRevision field if non-nil, zero value otherwise.

### GetChildPartRevisionOk

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetChildPartRevisionOk() (*string, bool)`

GetChildPartRevisionOk returns a tuple with the ChildPartRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChildPartRevision

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) SetChildPartRevision(v string)`

SetChildPartRevision sets ChildPartRevision field to given value.

### HasChildPartRevision

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) HasChildPartRevision() bool`

HasChildPartRevision returns a boolean if a field has been set.

### GetChildPartNumberRevision

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetChildPartNumberRevision() string`

GetChildPartNumberRevision returns the ChildPartNumberRevision field if non-nil, zero value otherwise.

### GetChildPartNumberRevisionOk

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetChildPartNumberRevisionOk() (*string, bool)`

GetChildPartNumberRevisionOk returns a tuple with the ChildPartNumberRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChildPartNumberRevision

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) SetChildPartNumberRevision(v string)`

SetChildPartNumberRevision sets ChildPartNumberRevision field to given value.

### HasChildPartNumberRevision

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) HasChildPartNumberRevision() bool`

HasChildPartNumberRevision returns a boolean if a field has been set.

### GetChildPartOperationId

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetChildPartOperationId() string`

GetChildPartOperationId returns the ChildPartOperationId field if non-nil, zero value otherwise.

### GetChildPartOperationIdOk

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetChildPartOperationIdOk() (*string, bool)`

GetChildPartOperationIdOk returns a tuple with the ChildPartOperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChildPartOperationId

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) SetChildPartOperationId(v string)`

SetChildPartOperationId sets ChildPartOperationId field to given value.

### HasChildPartOperationId

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) HasChildPartOperationId() bool`

HasChildPartOperationId returns a boolean if a field has been set.

### GetChildPartOperationCode

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetChildPartOperationCode() string`

GetChildPartOperationCode returns the ChildPartOperationCode field if non-nil, zero value otherwise.

### GetChildPartOperationCodeOk

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetChildPartOperationCodeOk() (*string, bool)`

GetChildPartOperationCodeOk returns a tuple with the ChildPartOperationCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChildPartOperationCode

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) SetChildPartOperationCode(v string)`

SetChildPartOperationCode sets ChildPartOperationCode field to given value.

### HasChildPartOperationCode

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) HasChildPartOperationCode() bool`

HasChildPartOperationCode returns a boolean if a field has been set.

### GetChildPartOperationNumber

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetChildPartOperationNumber() int32`

GetChildPartOperationNumber returns the ChildPartOperationNumber field if non-nil, zero value otherwise.

### GetChildPartOperationNumberOk

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetChildPartOperationNumberOk() (*int32, bool)`

GetChildPartOperationNumberOk returns a tuple with the ChildPartOperationNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChildPartOperationNumber

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) SetChildPartOperationNumber(v int32)`

SetChildPartOperationNumber sets ChildPartOperationNumber field to given value.

### HasChildPartOperationNumber

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) HasChildPartOperationNumber() bool`

HasChildPartOperationNumber returns a boolean if a field has been set.

### GetChildPartJobId

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetChildPartJobId() string`

GetChildPartJobId returns the ChildPartJobId field if non-nil, zero value otherwise.

### GetChildPartJobIdOk

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetChildPartJobIdOk() (*string, bool)`

GetChildPartJobIdOk returns a tuple with the ChildPartJobId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChildPartJobId

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) SetChildPartJobId(v string)`

SetChildPartJobId sets ChildPartJobId field to given value.

### HasChildPartJobId

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) HasChildPartJobId() bool`

HasChildPartJobId returns a boolean if a field has been set.

### GetChildPartJobNumber

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetChildPartJobNumber() string`

GetChildPartJobNumber returns the ChildPartJobNumber field if non-nil, zero value otherwise.

### GetChildPartJobNumberOk

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetChildPartJobNumberOk() (*string, bool)`

GetChildPartJobNumberOk returns a tuple with the ChildPartJobNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChildPartJobNumber

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) SetChildPartJobNumber(v string)`

SetChildPartJobNumber sets ChildPartJobNumber field to given value.

### HasChildPartJobNumber

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) HasChildPartJobNumber() bool`

HasChildPartJobNumber returns a boolean if a field has been set.

### GetChildPartJobOperationId

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetChildPartJobOperationId() string`

GetChildPartJobOperationId returns the ChildPartJobOperationId field if non-nil, zero value otherwise.

### GetChildPartJobOperationIdOk

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetChildPartJobOperationIdOk() (*string, bool)`

GetChildPartJobOperationIdOk returns a tuple with the ChildPartJobOperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChildPartJobOperationId

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) SetChildPartJobOperationId(v string)`

SetChildPartJobOperationId sets ChildPartJobOperationId field to given value.

### HasChildPartJobOperationId

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) HasChildPartJobOperationId() bool`

HasChildPartJobOperationId returns a boolean if a field has been set.

### GetChildPartJobOperationNumber

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetChildPartJobOperationNumber() float64`

GetChildPartJobOperationNumber returns the ChildPartJobOperationNumber field if non-nil, zero value otherwise.

### GetChildPartJobOperationNumberOk

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetChildPartJobOperationNumberOk() (*float64, bool)`

GetChildPartJobOperationNumberOk returns a tuple with the ChildPartJobOperationNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChildPartJobOperationNumber

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) SetChildPartJobOperationNumber(v float64)`

SetChildPartJobOperationNumber sets ChildPartJobOperationNumber field to given value.

### HasChildPartJobOperationNumber

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) HasChildPartJobOperationNumber() bool`

HasChildPartJobOperationNumber returns a boolean if a field has been set.

### GetDynamicMultiOut

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetDynamicMultiOut() bool`

GetDynamicMultiOut returns the DynamicMultiOut field if non-nil, zero value otherwise.

### GetDynamicMultiOutOk

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetDynamicMultiOutOk() (*bool, bool)`

GetDynamicMultiOutOk returns a tuple with the DynamicMultiOut field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDynamicMultiOut

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) SetDynamicMultiOut(v bool)`

SetDynamicMultiOut sets DynamicMultiOut field to given value.

### HasDynamicMultiOut

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) HasDynamicMultiOut() bool`

HasDynamicMultiOut returns a boolean if a field has been set.

### GetTraditionalMultiOut

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetTraditionalMultiOut() bool`

GetTraditionalMultiOut returns the TraditionalMultiOut field if non-nil, zero value otherwise.

### GetTraditionalMultiOutOk

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetTraditionalMultiOutOk() (*bool, bool)`

GetTraditionalMultiOutOk returns a tuple with the TraditionalMultiOut field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTraditionalMultiOut

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) SetTraditionalMultiOut(v bool)`

SetTraditionalMultiOut sets TraditionalMultiOut field to given value.

### HasTraditionalMultiOut

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) HasTraditionalMultiOut() bool`

HasTraditionalMultiOut returns a boolean if a field has been set.

### GetParent

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetParent() bool`

GetParent returns the Parent field if non-nil, zero value otherwise.

### GetParentOk

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetParentOk() (*bool, bool)`

GetParentOk returns a tuple with the Parent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParent

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) SetParent(v bool)`

SetParent sets Parent field to given value.

### HasParent

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) HasParent() bool`

HasParent returns a boolean if a field has been set.

### GetCompanion

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetCompanion() bool`

GetCompanion returns the Companion field if non-nil, zero value otherwise.

### GetCompanionOk

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) GetCompanionOk() (*bool, bool)`

GetCompanionOk returns a tuple with the Companion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompanion

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) SetCompanion(v bool)`

SetCompanion sets Companion field to given value.

### HasCompanion

`func (o *ProductionOperationsManagementApiListWorkcenterSetupEntriesItem) HasCompanion() bool`

HasCompanion returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


