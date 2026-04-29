# CustomerPartsApiUpdateCustomerPartResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | A unique identifier for the Customer Part. This will be automatically generated if omitted from the request. | [optional] 
**Number** | Pointer to **string** | The customer part number. | [optional] 
**PartId** | Pointer to **string** | The part ID. | [optional] 
**CustomerId** | Pointer to **string** | The customer ID. | [optional] 
**Description** | Pointer to **string** | A description of the part. | [optional] 
**Revision** | Pointer to **string** | The customer part revision. | [optional] 
**ModifiedDateTime** | Pointer to **time.Time** | The date and time on which the record was last modified. | [optional] 
**ModifiedBy** | Pointer to **string** | The IAM account ID of the user who last modified this record. | [optional] 

## Methods

### NewCustomerPartsApiUpdateCustomerPartResponse

`func NewCustomerPartsApiUpdateCustomerPartResponse() *CustomerPartsApiUpdateCustomerPartResponse`

NewCustomerPartsApiUpdateCustomerPartResponse instantiates a new CustomerPartsApiUpdateCustomerPartResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomerPartsApiUpdateCustomerPartResponseWithDefaults

`func NewCustomerPartsApiUpdateCustomerPartResponseWithDefaults() *CustomerPartsApiUpdateCustomerPartResponse`

NewCustomerPartsApiUpdateCustomerPartResponseWithDefaults instantiates a new CustomerPartsApiUpdateCustomerPartResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CustomerPartsApiUpdateCustomerPartResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CustomerPartsApiUpdateCustomerPartResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CustomerPartsApiUpdateCustomerPartResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *CustomerPartsApiUpdateCustomerPartResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetNumber

`func (o *CustomerPartsApiUpdateCustomerPartResponse) GetNumber() string`

GetNumber returns the Number field if non-nil, zero value otherwise.

### GetNumberOk

`func (o *CustomerPartsApiUpdateCustomerPartResponse) GetNumberOk() (*string, bool)`

GetNumberOk returns a tuple with the Number field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumber

`func (o *CustomerPartsApiUpdateCustomerPartResponse) SetNumber(v string)`

SetNumber sets Number field to given value.

### HasNumber

`func (o *CustomerPartsApiUpdateCustomerPartResponse) HasNumber() bool`

HasNumber returns a boolean if a field has been set.

### GetPartId

`func (o *CustomerPartsApiUpdateCustomerPartResponse) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *CustomerPartsApiUpdateCustomerPartResponse) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *CustomerPartsApiUpdateCustomerPartResponse) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *CustomerPartsApiUpdateCustomerPartResponse) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetCustomerId

`func (o *CustomerPartsApiUpdateCustomerPartResponse) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *CustomerPartsApiUpdateCustomerPartResponse) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *CustomerPartsApiUpdateCustomerPartResponse) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *CustomerPartsApiUpdateCustomerPartResponse) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### GetDescription

`func (o *CustomerPartsApiUpdateCustomerPartResponse) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CustomerPartsApiUpdateCustomerPartResponse) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CustomerPartsApiUpdateCustomerPartResponse) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CustomerPartsApiUpdateCustomerPartResponse) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetRevision

`func (o *CustomerPartsApiUpdateCustomerPartResponse) GetRevision() string`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *CustomerPartsApiUpdateCustomerPartResponse) GetRevisionOk() (*string, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *CustomerPartsApiUpdateCustomerPartResponse) SetRevision(v string)`

SetRevision sets Revision field to given value.

### HasRevision

`func (o *CustomerPartsApiUpdateCustomerPartResponse) HasRevision() bool`

HasRevision returns a boolean if a field has been set.

### GetModifiedDateTime

`func (o *CustomerPartsApiUpdateCustomerPartResponse) GetModifiedDateTime() time.Time`

GetModifiedDateTime returns the ModifiedDateTime field if non-nil, zero value otherwise.

### GetModifiedDateTimeOk

`func (o *CustomerPartsApiUpdateCustomerPartResponse) GetModifiedDateTimeOk() (*time.Time, bool)`

GetModifiedDateTimeOk returns a tuple with the ModifiedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDateTime

`func (o *CustomerPartsApiUpdateCustomerPartResponse) SetModifiedDateTime(v time.Time)`

SetModifiedDateTime sets ModifiedDateTime field to given value.

### HasModifiedDateTime

`func (o *CustomerPartsApiUpdateCustomerPartResponse) HasModifiedDateTime() bool`

HasModifiedDateTime returns a boolean if a field has been set.

### GetModifiedBy

`func (o *CustomerPartsApiUpdateCustomerPartResponse) GetModifiedBy() string`

GetModifiedBy returns the ModifiedBy field if non-nil, zero value otherwise.

### GetModifiedByOk

`func (o *CustomerPartsApiUpdateCustomerPartResponse) GetModifiedByOk() (*string, bool)`

GetModifiedByOk returns a tuple with the ModifiedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedBy

`func (o *CustomerPartsApiUpdateCustomerPartResponse) SetModifiedBy(v string)`

SetModifiedBy sets ModifiedBy field to given value.

### HasModifiedBy

`func (o *CustomerPartsApiUpdateCustomerPartResponse) HasModifiedBy() bool`

HasModifiedBy returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


