# CustomerPartsApiGetCustomerPartResponse

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

### NewCustomerPartsApiGetCustomerPartResponse

`func NewCustomerPartsApiGetCustomerPartResponse() *CustomerPartsApiGetCustomerPartResponse`

NewCustomerPartsApiGetCustomerPartResponse instantiates a new CustomerPartsApiGetCustomerPartResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomerPartsApiGetCustomerPartResponseWithDefaults

`func NewCustomerPartsApiGetCustomerPartResponseWithDefaults() *CustomerPartsApiGetCustomerPartResponse`

NewCustomerPartsApiGetCustomerPartResponseWithDefaults instantiates a new CustomerPartsApiGetCustomerPartResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CustomerPartsApiGetCustomerPartResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CustomerPartsApiGetCustomerPartResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CustomerPartsApiGetCustomerPartResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *CustomerPartsApiGetCustomerPartResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetNumber

`func (o *CustomerPartsApiGetCustomerPartResponse) GetNumber() string`

GetNumber returns the Number field if non-nil, zero value otherwise.

### GetNumberOk

`func (o *CustomerPartsApiGetCustomerPartResponse) GetNumberOk() (*string, bool)`

GetNumberOk returns a tuple with the Number field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumber

`func (o *CustomerPartsApiGetCustomerPartResponse) SetNumber(v string)`

SetNumber sets Number field to given value.

### HasNumber

`func (o *CustomerPartsApiGetCustomerPartResponse) HasNumber() bool`

HasNumber returns a boolean if a field has been set.

### GetPartId

`func (o *CustomerPartsApiGetCustomerPartResponse) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *CustomerPartsApiGetCustomerPartResponse) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *CustomerPartsApiGetCustomerPartResponse) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *CustomerPartsApiGetCustomerPartResponse) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetCustomerId

`func (o *CustomerPartsApiGetCustomerPartResponse) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *CustomerPartsApiGetCustomerPartResponse) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *CustomerPartsApiGetCustomerPartResponse) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *CustomerPartsApiGetCustomerPartResponse) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### GetDescription

`func (o *CustomerPartsApiGetCustomerPartResponse) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CustomerPartsApiGetCustomerPartResponse) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CustomerPartsApiGetCustomerPartResponse) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CustomerPartsApiGetCustomerPartResponse) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetRevision

`func (o *CustomerPartsApiGetCustomerPartResponse) GetRevision() string`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *CustomerPartsApiGetCustomerPartResponse) GetRevisionOk() (*string, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *CustomerPartsApiGetCustomerPartResponse) SetRevision(v string)`

SetRevision sets Revision field to given value.

### HasRevision

`func (o *CustomerPartsApiGetCustomerPartResponse) HasRevision() bool`

HasRevision returns a boolean if a field has been set.

### GetModifiedDateTime

`func (o *CustomerPartsApiGetCustomerPartResponse) GetModifiedDateTime() time.Time`

GetModifiedDateTime returns the ModifiedDateTime field if non-nil, zero value otherwise.

### GetModifiedDateTimeOk

`func (o *CustomerPartsApiGetCustomerPartResponse) GetModifiedDateTimeOk() (*time.Time, bool)`

GetModifiedDateTimeOk returns a tuple with the ModifiedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDateTime

`func (o *CustomerPartsApiGetCustomerPartResponse) SetModifiedDateTime(v time.Time)`

SetModifiedDateTime sets ModifiedDateTime field to given value.

### HasModifiedDateTime

`func (o *CustomerPartsApiGetCustomerPartResponse) HasModifiedDateTime() bool`

HasModifiedDateTime returns a boolean if a field has been set.

### GetModifiedBy

`func (o *CustomerPartsApiGetCustomerPartResponse) GetModifiedBy() string`

GetModifiedBy returns the ModifiedBy field if non-nil, zero value otherwise.

### GetModifiedByOk

`func (o *CustomerPartsApiGetCustomerPartResponse) GetModifiedByOk() (*string, bool)`

GetModifiedByOk returns a tuple with the ModifiedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedBy

`func (o *CustomerPartsApiGetCustomerPartResponse) SetModifiedBy(v string)`

SetModifiedBy sets ModifiedBy field to given value.

### HasModifiedBy

`func (o *CustomerPartsApiGetCustomerPartResponse) HasModifiedBy() bool`

HasModifiedBy returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


