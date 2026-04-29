# ChartOfAccountsApiCreateAccount201Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | A unique identifier for the Account. This will be automatically generated if omitted from the request. | [optional] 
**AccountNumber** | Pointer to **string** | A supplemental ID field used to identify an account. | [optional] 
**Name** | Pointer to **string** | A unique name for the account. | [optional] 
**CategoryType** | Pointer to **string** | Must be one of the following values: Asset, Equity, Expense, Liability,  or Revenue. | [optional] 
**Active** | Pointer to **bool** | This flag will be set to Active by default. | [optional] 
**InactiveDate** | Pointer to **time.Time** | The date on which the record became Inactive. | [optional] 
**CreatedDate** | Pointer to **time.Time** | The date on which the record was created. | [optional] 
**ModifiedBy** | Pointer to **string** | The ID of the user who last modified the record. | [optional] 
**ModifiedDate** | Pointer to **time.Time** | The date on which the record was last modified. | [optional] 

## Methods

### NewChartOfAccountsApiCreateAccount201Response

`func NewChartOfAccountsApiCreateAccount201Response() *ChartOfAccountsApiCreateAccount201Response`

NewChartOfAccountsApiCreateAccount201Response instantiates a new ChartOfAccountsApiCreateAccount201Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChartOfAccountsApiCreateAccount201ResponseWithDefaults

`func NewChartOfAccountsApiCreateAccount201ResponseWithDefaults() *ChartOfAccountsApiCreateAccount201Response`

NewChartOfAccountsApiCreateAccount201ResponseWithDefaults instantiates a new ChartOfAccountsApiCreateAccount201Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ChartOfAccountsApiCreateAccount201Response) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ChartOfAccountsApiCreateAccount201Response) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ChartOfAccountsApiCreateAccount201Response) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *ChartOfAccountsApiCreateAccount201Response) HasId() bool`

HasId returns a boolean if a field has been set.

### GetAccountNumber

`func (o *ChartOfAccountsApiCreateAccount201Response) GetAccountNumber() string`

GetAccountNumber returns the AccountNumber field if non-nil, zero value otherwise.

### GetAccountNumberOk

`func (o *ChartOfAccountsApiCreateAccount201Response) GetAccountNumberOk() (*string, bool)`

GetAccountNumberOk returns a tuple with the AccountNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumber

`func (o *ChartOfAccountsApiCreateAccount201Response) SetAccountNumber(v string)`

SetAccountNumber sets AccountNumber field to given value.

### HasAccountNumber

`func (o *ChartOfAccountsApiCreateAccount201Response) HasAccountNumber() bool`

HasAccountNumber returns a boolean if a field has been set.

### GetName

`func (o *ChartOfAccountsApiCreateAccount201Response) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ChartOfAccountsApiCreateAccount201Response) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ChartOfAccountsApiCreateAccount201Response) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ChartOfAccountsApiCreateAccount201Response) HasName() bool`

HasName returns a boolean if a field has been set.

### GetCategoryType

`func (o *ChartOfAccountsApiCreateAccount201Response) GetCategoryType() string`

GetCategoryType returns the CategoryType field if non-nil, zero value otherwise.

### GetCategoryTypeOk

`func (o *ChartOfAccountsApiCreateAccount201Response) GetCategoryTypeOk() (*string, bool)`

GetCategoryTypeOk returns a tuple with the CategoryType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategoryType

`func (o *ChartOfAccountsApiCreateAccount201Response) SetCategoryType(v string)`

SetCategoryType sets CategoryType field to given value.

### HasCategoryType

`func (o *ChartOfAccountsApiCreateAccount201Response) HasCategoryType() bool`

HasCategoryType returns a boolean if a field has been set.

### GetActive

`func (o *ChartOfAccountsApiCreateAccount201Response) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *ChartOfAccountsApiCreateAccount201Response) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *ChartOfAccountsApiCreateAccount201Response) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *ChartOfAccountsApiCreateAccount201Response) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetInactiveDate

`func (o *ChartOfAccountsApiCreateAccount201Response) GetInactiveDate() time.Time`

GetInactiveDate returns the InactiveDate field if non-nil, zero value otherwise.

### GetInactiveDateOk

`func (o *ChartOfAccountsApiCreateAccount201Response) GetInactiveDateOk() (*time.Time, bool)`

GetInactiveDateOk returns a tuple with the InactiveDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInactiveDate

`func (o *ChartOfAccountsApiCreateAccount201Response) SetInactiveDate(v time.Time)`

SetInactiveDate sets InactiveDate field to given value.

### HasInactiveDate

`func (o *ChartOfAccountsApiCreateAccount201Response) HasInactiveDate() bool`

HasInactiveDate returns a boolean if a field has been set.

### GetCreatedDate

`func (o *ChartOfAccountsApiCreateAccount201Response) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *ChartOfAccountsApiCreateAccount201Response) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *ChartOfAccountsApiCreateAccount201Response) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *ChartOfAccountsApiCreateAccount201Response) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.

### GetModifiedBy

`func (o *ChartOfAccountsApiCreateAccount201Response) GetModifiedBy() string`

GetModifiedBy returns the ModifiedBy field if non-nil, zero value otherwise.

### GetModifiedByOk

`func (o *ChartOfAccountsApiCreateAccount201Response) GetModifiedByOk() (*string, bool)`

GetModifiedByOk returns a tuple with the ModifiedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedBy

`func (o *ChartOfAccountsApiCreateAccount201Response) SetModifiedBy(v string)`

SetModifiedBy sets ModifiedBy field to given value.

### HasModifiedBy

`func (o *ChartOfAccountsApiCreateAccount201Response) HasModifiedBy() bool`

HasModifiedBy returns a boolean if a field has been set.

### GetModifiedDate

`func (o *ChartOfAccountsApiCreateAccount201Response) GetModifiedDate() time.Time`

GetModifiedDate returns the ModifiedDate field if non-nil, zero value otherwise.

### GetModifiedDateOk

`func (o *ChartOfAccountsApiCreateAccount201Response) GetModifiedDateOk() (*time.Time, bool)`

GetModifiedDateOk returns a tuple with the ModifiedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDate

`func (o *ChartOfAccountsApiCreateAccount201Response) SetModifiedDate(v time.Time)`

SetModifiedDate sets ModifiedDate field to given value.

### HasModifiedDate

`func (o *ChartOfAccountsApiCreateAccount201Response) HasModifiedDate() bool`

HasModifiedDate returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


