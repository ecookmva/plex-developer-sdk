# ChartOfAccountsApiSyncAccountsRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | A unique identifier for the Account. This will be automatically generated if omitted from the request. | [optional] 
**AccountNumber** | Pointer to **string** | A supplemental ID field used to identify an account. | [optional] 
**Name** | Pointer to **string** | A unique name for the account. | [optional] 
**CategoryType** | Pointer to **string** | Must be one of the following values: Asset, Equity, Expense, Liability,  or Revenue. | [optional] 

## Methods

### NewChartOfAccountsApiSyncAccountsRequest

`func NewChartOfAccountsApiSyncAccountsRequest() *ChartOfAccountsApiSyncAccountsRequest`

NewChartOfAccountsApiSyncAccountsRequest instantiates a new ChartOfAccountsApiSyncAccountsRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChartOfAccountsApiSyncAccountsRequestWithDefaults

`func NewChartOfAccountsApiSyncAccountsRequestWithDefaults() *ChartOfAccountsApiSyncAccountsRequest`

NewChartOfAccountsApiSyncAccountsRequestWithDefaults instantiates a new ChartOfAccountsApiSyncAccountsRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ChartOfAccountsApiSyncAccountsRequest) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ChartOfAccountsApiSyncAccountsRequest) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ChartOfAccountsApiSyncAccountsRequest) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *ChartOfAccountsApiSyncAccountsRequest) HasId() bool`

HasId returns a boolean if a field has been set.

### GetAccountNumber

`func (o *ChartOfAccountsApiSyncAccountsRequest) GetAccountNumber() string`

GetAccountNumber returns the AccountNumber field if non-nil, zero value otherwise.

### GetAccountNumberOk

`func (o *ChartOfAccountsApiSyncAccountsRequest) GetAccountNumberOk() (*string, bool)`

GetAccountNumberOk returns a tuple with the AccountNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumber

`func (o *ChartOfAccountsApiSyncAccountsRequest) SetAccountNumber(v string)`

SetAccountNumber sets AccountNumber field to given value.

### HasAccountNumber

`func (o *ChartOfAccountsApiSyncAccountsRequest) HasAccountNumber() bool`

HasAccountNumber returns a boolean if a field has been set.

### GetName

`func (o *ChartOfAccountsApiSyncAccountsRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ChartOfAccountsApiSyncAccountsRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ChartOfAccountsApiSyncAccountsRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ChartOfAccountsApiSyncAccountsRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### GetCategoryType

`func (o *ChartOfAccountsApiSyncAccountsRequest) GetCategoryType() string`

GetCategoryType returns the CategoryType field if non-nil, zero value otherwise.

### GetCategoryTypeOk

`func (o *ChartOfAccountsApiSyncAccountsRequest) GetCategoryTypeOk() (*string, bool)`

GetCategoryTypeOk returns a tuple with the CategoryType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategoryType

`func (o *ChartOfAccountsApiSyncAccountsRequest) SetCategoryType(v string)`

SetCategoryType sets CategoryType field to given value.

### HasCategoryType

`func (o *ChartOfAccountsApiSyncAccountsRequest) HasCategoryType() bool`

HasCategoryType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


