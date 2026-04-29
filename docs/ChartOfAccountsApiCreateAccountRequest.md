# ChartOfAccountsApiCreateAccountRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | A unique identifier for the Account. This will be automatically generated if omitted from the request. | [optional] 
**AccountNumber** | Pointer to **string** | A supplemental ID field used to identify an account. | [optional] 
**Name** | Pointer to **string** | A unique name for the account. | [optional] 
**CategoryType** | Pointer to **string** | Must be one of the following values: Asset, Equity, Expense, Liability,  or Revenue. | [optional] 

## Methods

### NewChartOfAccountsApiCreateAccountRequest

`func NewChartOfAccountsApiCreateAccountRequest() *ChartOfAccountsApiCreateAccountRequest`

NewChartOfAccountsApiCreateAccountRequest instantiates a new ChartOfAccountsApiCreateAccountRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChartOfAccountsApiCreateAccountRequestWithDefaults

`func NewChartOfAccountsApiCreateAccountRequestWithDefaults() *ChartOfAccountsApiCreateAccountRequest`

NewChartOfAccountsApiCreateAccountRequestWithDefaults instantiates a new ChartOfAccountsApiCreateAccountRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ChartOfAccountsApiCreateAccountRequest) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ChartOfAccountsApiCreateAccountRequest) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ChartOfAccountsApiCreateAccountRequest) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *ChartOfAccountsApiCreateAccountRequest) HasId() bool`

HasId returns a boolean if a field has been set.

### GetAccountNumber

`func (o *ChartOfAccountsApiCreateAccountRequest) GetAccountNumber() string`

GetAccountNumber returns the AccountNumber field if non-nil, zero value otherwise.

### GetAccountNumberOk

`func (o *ChartOfAccountsApiCreateAccountRequest) GetAccountNumberOk() (*string, bool)`

GetAccountNumberOk returns a tuple with the AccountNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumber

`func (o *ChartOfAccountsApiCreateAccountRequest) SetAccountNumber(v string)`

SetAccountNumber sets AccountNumber field to given value.

### HasAccountNumber

`func (o *ChartOfAccountsApiCreateAccountRequest) HasAccountNumber() bool`

HasAccountNumber returns a boolean if a field has been set.

### GetName

`func (o *ChartOfAccountsApiCreateAccountRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ChartOfAccountsApiCreateAccountRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ChartOfAccountsApiCreateAccountRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ChartOfAccountsApiCreateAccountRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### GetCategoryType

`func (o *ChartOfAccountsApiCreateAccountRequest) GetCategoryType() string`

GetCategoryType returns the CategoryType field if non-nil, zero value otherwise.

### GetCategoryTypeOk

`func (o *ChartOfAccountsApiCreateAccountRequest) GetCategoryTypeOk() (*string, bool)`

GetCategoryTypeOk returns a tuple with the CategoryType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategoryType

`func (o *ChartOfAccountsApiCreateAccountRequest) SetCategoryType(v string)`

SetCategoryType sets CategoryType field to given value.

### HasCategoryType

`func (o *ChartOfAccountsApiCreateAccountRequest) HasCategoryType() bool`

HasCategoryType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


