# JobSchedulingApiListJobTypesItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | Pointer to **string** | An umbrella category used to group similar jobs for ease of reporting. Setup Table &amp;quot;Job Type&amp;quot; (part.dbo.Job_Type). Maximum 50 characters. | [optional] 
**Default** | Pointer to **bool** | Job Type that will default to on job entry if no other Job Type is specified. | [optional] 
**DrType** | Pointer to **bool** | Indicates if a DR type. | [optional] 
**OverageType** | Pointer to **bool** | Indicates if a Overage type. | [optional] 
**FaType** | Pointer to **bool** | Indicates if a FA type. | [optional] 
**ReturnType** | Pointer to **bool** | Indicates if a Return type. | [optional] 
**RejectionType** | Pointer to **bool** | Indicates if a Rejection type. | [optional] 
**ServiceType** | Pointer to **bool** | Indicates if a Service type. | [optional] 
**ReworkType** | Pointer to **bool** | Indicates if a Rework type. | [optional] 
**StockInventoryType** | Pointer to **bool** | Indicates if a Stock Inventory type. | [optional] 
**InventoryType** | Pointer to **bool** | Indicates if a Inventory type. | [optional] 
**PackagingType** | Pointer to **bool** | Indicates if a Packaging type. | [optional] 
**PlanningType** | Pointer to **bool** | Indicates if a Planning type. | [optional] 
**ScrapType** | Pointer to **bool** | Indicates if a Scrap type. | [optional] 
**Subcontract** | Pointer to **bool** | Indicates if a Subcontract type. | [optional] 
**IncludeInMRP** | Pointer to **bool** | Indicates if an Include in MRP type. | [optional] 
**JobNumberPrefix** | Pointer to **string** | A prefix to be added before the job number. Maximum 4 characters. | [optional] 
**JobNumberSuffix** | Pointer to **string** | A suffix to be added after the job number. Maximum 4 characters. | [optional] 

## Methods

### NewJobSchedulingApiListJobTypesItem

`func NewJobSchedulingApiListJobTypesItem() *JobSchedulingApiListJobTypesItem`

NewJobSchedulingApiListJobTypesItem instantiates a new JobSchedulingApiListJobTypesItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewJobSchedulingApiListJobTypesItemWithDefaults

`func NewJobSchedulingApiListJobTypesItemWithDefaults() *JobSchedulingApiListJobTypesItem`

NewJobSchedulingApiListJobTypesItemWithDefaults instantiates a new JobSchedulingApiListJobTypesItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *JobSchedulingApiListJobTypesItem) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *JobSchedulingApiListJobTypesItem) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *JobSchedulingApiListJobTypesItem) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *JobSchedulingApiListJobTypesItem) HasType() bool`

HasType returns a boolean if a field has been set.

### GetDefault

`func (o *JobSchedulingApiListJobTypesItem) GetDefault() bool`

GetDefault returns the Default field if non-nil, zero value otherwise.

### GetDefaultOk

`func (o *JobSchedulingApiListJobTypesItem) GetDefaultOk() (*bool, bool)`

GetDefaultOk returns a tuple with the Default field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefault

`func (o *JobSchedulingApiListJobTypesItem) SetDefault(v bool)`

SetDefault sets Default field to given value.

### HasDefault

`func (o *JobSchedulingApiListJobTypesItem) HasDefault() bool`

HasDefault returns a boolean if a field has been set.

### GetDrType

`func (o *JobSchedulingApiListJobTypesItem) GetDrType() bool`

GetDrType returns the DrType field if non-nil, zero value otherwise.

### GetDrTypeOk

`func (o *JobSchedulingApiListJobTypesItem) GetDrTypeOk() (*bool, bool)`

GetDrTypeOk returns a tuple with the DrType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDrType

`func (o *JobSchedulingApiListJobTypesItem) SetDrType(v bool)`

SetDrType sets DrType field to given value.

### HasDrType

`func (o *JobSchedulingApiListJobTypesItem) HasDrType() bool`

HasDrType returns a boolean if a field has been set.

### GetOverageType

`func (o *JobSchedulingApiListJobTypesItem) GetOverageType() bool`

GetOverageType returns the OverageType field if non-nil, zero value otherwise.

### GetOverageTypeOk

`func (o *JobSchedulingApiListJobTypesItem) GetOverageTypeOk() (*bool, bool)`

GetOverageTypeOk returns a tuple with the OverageType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOverageType

`func (o *JobSchedulingApiListJobTypesItem) SetOverageType(v bool)`

SetOverageType sets OverageType field to given value.

### HasOverageType

`func (o *JobSchedulingApiListJobTypesItem) HasOverageType() bool`

HasOverageType returns a boolean if a field has been set.

### GetFaType

`func (o *JobSchedulingApiListJobTypesItem) GetFaType() bool`

GetFaType returns the FaType field if non-nil, zero value otherwise.

### GetFaTypeOk

`func (o *JobSchedulingApiListJobTypesItem) GetFaTypeOk() (*bool, bool)`

GetFaTypeOk returns a tuple with the FaType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFaType

`func (o *JobSchedulingApiListJobTypesItem) SetFaType(v bool)`

SetFaType sets FaType field to given value.

### HasFaType

`func (o *JobSchedulingApiListJobTypesItem) HasFaType() bool`

HasFaType returns a boolean if a field has been set.

### GetReturnType

`func (o *JobSchedulingApiListJobTypesItem) GetReturnType() bool`

GetReturnType returns the ReturnType field if non-nil, zero value otherwise.

### GetReturnTypeOk

`func (o *JobSchedulingApiListJobTypesItem) GetReturnTypeOk() (*bool, bool)`

GetReturnTypeOk returns a tuple with the ReturnType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReturnType

`func (o *JobSchedulingApiListJobTypesItem) SetReturnType(v bool)`

SetReturnType sets ReturnType field to given value.

### HasReturnType

`func (o *JobSchedulingApiListJobTypesItem) HasReturnType() bool`

HasReturnType returns a boolean if a field has been set.

### GetRejectionType

`func (o *JobSchedulingApiListJobTypesItem) GetRejectionType() bool`

GetRejectionType returns the RejectionType field if non-nil, zero value otherwise.

### GetRejectionTypeOk

`func (o *JobSchedulingApiListJobTypesItem) GetRejectionTypeOk() (*bool, bool)`

GetRejectionTypeOk returns a tuple with the RejectionType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRejectionType

`func (o *JobSchedulingApiListJobTypesItem) SetRejectionType(v bool)`

SetRejectionType sets RejectionType field to given value.

### HasRejectionType

`func (o *JobSchedulingApiListJobTypesItem) HasRejectionType() bool`

HasRejectionType returns a boolean if a field has been set.

### GetServiceType

`func (o *JobSchedulingApiListJobTypesItem) GetServiceType() bool`

GetServiceType returns the ServiceType field if non-nil, zero value otherwise.

### GetServiceTypeOk

`func (o *JobSchedulingApiListJobTypesItem) GetServiceTypeOk() (*bool, bool)`

GetServiceTypeOk returns a tuple with the ServiceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceType

`func (o *JobSchedulingApiListJobTypesItem) SetServiceType(v bool)`

SetServiceType sets ServiceType field to given value.

### HasServiceType

`func (o *JobSchedulingApiListJobTypesItem) HasServiceType() bool`

HasServiceType returns a boolean if a field has been set.

### GetReworkType

`func (o *JobSchedulingApiListJobTypesItem) GetReworkType() bool`

GetReworkType returns the ReworkType field if non-nil, zero value otherwise.

### GetReworkTypeOk

`func (o *JobSchedulingApiListJobTypesItem) GetReworkTypeOk() (*bool, bool)`

GetReworkTypeOk returns a tuple with the ReworkType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReworkType

`func (o *JobSchedulingApiListJobTypesItem) SetReworkType(v bool)`

SetReworkType sets ReworkType field to given value.

### HasReworkType

`func (o *JobSchedulingApiListJobTypesItem) HasReworkType() bool`

HasReworkType returns a boolean if a field has been set.

### GetStockInventoryType

`func (o *JobSchedulingApiListJobTypesItem) GetStockInventoryType() bool`

GetStockInventoryType returns the StockInventoryType field if non-nil, zero value otherwise.

### GetStockInventoryTypeOk

`func (o *JobSchedulingApiListJobTypesItem) GetStockInventoryTypeOk() (*bool, bool)`

GetStockInventoryTypeOk returns a tuple with the StockInventoryType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStockInventoryType

`func (o *JobSchedulingApiListJobTypesItem) SetStockInventoryType(v bool)`

SetStockInventoryType sets StockInventoryType field to given value.

### HasStockInventoryType

`func (o *JobSchedulingApiListJobTypesItem) HasStockInventoryType() bool`

HasStockInventoryType returns a boolean if a field has been set.

### GetInventoryType

`func (o *JobSchedulingApiListJobTypesItem) GetInventoryType() bool`

GetInventoryType returns the InventoryType field if non-nil, zero value otherwise.

### GetInventoryTypeOk

`func (o *JobSchedulingApiListJobTypesItem) GetInventoryTypeOk() (*bool, bool)`

GetInventoryTypeOk returns a tuple with the InventoryType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInventoryType

`func (o *JobSchedulingApiListJobTypesItem) SetInventoryType(v bool)`

SetInventoryType sets InventoryType field to given value.

### HasInventoryType

`func (o *JobSchedulingApiListJobTypesItem) HasInventoryType() bool`

HasInventoryType returns a boolean if a field has been set.

### GetPackagingType

`func (o *JobSchedulingApiListJobTypesItem) GetPackagingType() bool`

GetPackagingType returns the PackagingType field if non-nil, zero value otherwise.

### GetPackagingTypeOk

`func (o *JobSchedulingApiListJobTypesItem) GetPackagingTypeOk() (*bool, bool)`

GetPackagingTypeOk returns a tuple with the PackagingType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackagingType

`func (o *JobSchedulingApiListJobTypesItem) SetPackagingType(v bool)`

SetPackagingType sets PackagingType field to given value.

### HasPackagingType

`func (o *JobSchedulingApiListJobTypesItem) HasPackagingType() bool`

HasPackagingType returns a boolean if a field has been set.

### GetPlanningType

`func (o *JobSchedulingApiListJobTypesItem) GetPlanningType() bool`

GetPlanningType returns the PlanningType field if non-nil, zero value otherwise.

### GetPlanningTypeOk

`func (o *JobSchedulingApiListJobTypesItem) GetPlanningTypeOk() (*bool, bool)`

GetPlanningTypeOk returns a tuple with the PlanningType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlanningType

`func (o *JobSchedulingApiListJobTypesItem) SetPlanningType(v bool)`

SetPlanningType sets PlanningType field to given value.

### HasPlanningType

`func (o *JobSchedulingApiListJobTypesItem) HasPlanningType() bool`

HasPlanningType returns a boolean if a field has been set.

### GetScrapType

`func (o *JobSchedulingApiListJobTypesItem) GetScrapType() bool`

GetScrapType returns the ScrapType field if non-nil, zero value otherwise.

### GetScrapTypeOk

`func (o *JobSchedulingApiListJobTypesItem) GetScrapTypeOk() (*bool, bool)`

GetScrapTypeOk returns a tuple with the ScrapType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScrapType

`func (o *JobSchedulingApiListJobTypesItem) SetScrapType(v bool)`

SetScrapType sets ScrapType field to given value.

### HasScrapType

`func (o *JobSchedulingApiListJobTypesItem) HasScrapType() bool`

HasScrapType returns a boolean if a field has been set.

### GetSubcontract

`func (o *JobSchedulingApiListJobTypesItem) GetSubcontract() bool`

GetSubcontract returns the Subcontract field if non-nil, zero value otherwise.

### GetSubcontractOk

`func (o *JobSchedulingApiListJobTypesItem) GetSubcontractOk() (*bool, bool)`

GetSubcontractOk returns a tuple with the Subcontract field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubcontract

`func (o *JobSchedulingApiListJobTypesItem) SetSubcontract(v bool)`

SetSubcontract sets Subcontract field to given value.

### HasSubcontract

`func (o *JobSchedulingApiListJobTypesItem) HasSubcontract() bool`

HasSubcontract returns a boolean if a field has been set.

### GetIncludeInMRP

`func (o *JobSchedulingApiListJobTypesItem) GetIncludeInMRP() bool`

GetIncludeInMRP returns the IncludeInMRP field if non-nil, zero value otherwise.

### GetIncludeInMRPOk

`func (o *JobSchedulingApiListJobTypesItem) GetIncludeInMRPOk() (*bool, bool)`

GetIncludeInMRPOk returns a tuple with the IncludeInMRP field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludeInMRP

`func (o *JobSchedulingApiListJobTypesItem) SetIncludeInMRP(v bool)`

SetIncludeInMRP sets IncludeInMRP field to given value.

### HasIncludeInMRP

`func (o *JobSchedulingApiListJobTypesItem) HasIncludeInMRP() bool`

HasIncludeInMRP returns a boolean if a field has been set.

### GetJobNumberPrefix

`func (o *JobSchedulingApiListJobTypesItem) GetJobNumberPrefix() string`

GetJobNumberPrefix returns the JobNumberPrefix field if non-nil, zero value otherwise.

### GetJobNumberPrefixOk

`func (o *JobSchedulingApiListJobTypesItem) GetJobNumberPrefixOk() (*string, bool)`

GetJobNumberPrefixOk returns a tuple with the JobNumberPrefix field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobNumberPrefix

`func (o *JobSchedulingApiListJobTypesItem) SetJobNumberPrefix(v string)`

SetJobNumberPrefix sets JobNumberPrefix field to given value.

### HasJobNumberPrefix

`func (o *JobSchedulingApiListJobTypesItem) HasJobNumberPrefix() bool`

HasJobNumberPrefix returns a boolean if a field has been set.

### GetJobNumberSuffix

`func (o *JobSchedulingApiListJobTypesItem) GetJobNumberSuffix() string`

GetJobNumberSuffix returns the JobNumberSuffix field if non-nil, zero value otherwise.

### GetJobNumberSuffixOk

`func (o *JobSchedulingApiListJobTypesItem) GetJobNumberSuffixOk() (*string, bool)`

GetJobNumberSuffixOk returns a tuple with the JobNumberSuffix field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobNumberSuffix

`func (o *JobSchedulingApiListJobTypesItem) SetJobNumberSuffix(v string)`

SetJobNumberSuffix sets JobNumberSuffix field to given value.

### HasJobNumberSuffix

`func (o *JobSchedulingApiListJobTypesItem) HasJobNumberSuffix() bool`

HasJobNumberSuffix returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


