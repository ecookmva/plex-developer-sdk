# CustomerPartsApiDeleteCustomerPartResponse

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

### NewCustomerPartsApiDeleteCustomerPartResponse

`func NewCustomerPartsApiDeleteCustomerPartResponse() *CustomerPartsApiDeleteCustomerPartResponse`

NewCustomerPartsApiDeleteCustomerPartResponse instantiates a new CustomerPartsApiDeleteCustomerPartResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomerPartsApiDeleteCustomerPartResponseWithDefaults

`func NewCustomerPartsApiDeleteCustomerPartResponseWithDefaults() *CustomerPartsApiDeleteCustomerPartResponse`

NewCustomerPartsApiDeleteCustomerPartResponseWithDefaults instantiates a new CustomerPartsApiDeleteCustomerPartResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CustomerPartsApiDeleteCustomerPartResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CustomerPartsApiDeleteCustomerPartResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CustomerPartsApiDeleteCustomerPartResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *CustomerPartsApiDeleteCustomerPartResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetNumber

`func (o *CustomerPartsApiDeleteCustomerPartResponse) GetNumber() string`

GetNumber returns the Number field if non-nil, zero value otherwise.

### GetNumberOk

`func (o *CustomerPartsApiDeleteCustomerPartResponse) GetNumberOk() (*string, bool)`

GetNumberOk returns a tuple with the Number field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumber

`func (o *CustomerPartsApiDeleteCustomerPartResponse) SetNumber(v string)`

SetNumber sets Number field to given value.

### HasNumber

`func (o *CustomerPartsApiDeleteCustomerPartResponse) HasNumber() bool`

HasNumber returns a boolean if a field has been set.

### GetPartId

`func (o *CustomerPartsApiDeleteCustomerPartResponse) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *CustomerPartsApiDeleteCustomerPartResponse) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *CustomerPartsApiDeleteCustomerPartResponse) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *CustomerPartsApiDeleteCustomerPartResponse) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetCustomerId

`func (o *CustomerPartsApiDeleteCustomerPartResponse) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *CustomerPartsApiDeleteCustomerPartResponse) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *CustomerPartsApiDeleteCustomerPartResponse) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *CustomerPartsApiDeleteCustomerPartResponse) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### GetDescription

`func (o *CustomerPartsApiDeleteCustomerPartResponse) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CustomerPartsApiDeleteCustomerPartResponse) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CustomerPartsApiDeleteCustomerPartResponse) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CustomerPartsApiDeleteCustomerPartResponse) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetRevision

`func (o *CustomerPartsApiDeleteCustomerPartResponse) GetRevision() string`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *CustomerPartsApiDeleteCustomerPartResponse) GetRevisionOk() (*string, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *CustomerPartsApiDeleteCustomerPartResponse) SetRevision(v string)`

SetRevision sets Revision field to given value.

### HasRevision

`func (o *CustomerPartsApiDeleteCustomerPartResponse) HasRevision() bool`

HasRevision returns a boolean if a field has been set.

### GetModifiedDateTime

`func (o *CustomerPartsApiDeleteCustomerPartResponse) GetModifiedDateTime() time.Time`

GetModifiedDateTime returns the ModifiedDateTime field if non-nil, zero value otherwise.

### GetModifiedDateTimeOk

`func (o *CustomerPartsApiDeleteCustomerPartResponse) GetModifiedDateTimeOk() (*time.Time, bool)`

GetModifiedDateTimeOk returns a tuple with the ModifiedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDateTime

`func (o *CustomerPartsApiDeleteCustomerPartResponse) SetModifiedDateTime(v time.Time)`

SetModifiedDateTime sets ModifiedDateTime field to given value.

### HasModifiedDateTime

`func (o *CustomerPartsApiDeleteCustomerPartResponse) HasModifiedDateTime() bool`

HasModifiedDateTime returns a boolean if a field has been set.

### GetModifiedBy

`func (o *CustomerPartsApiDeleteCustomerPartResponse) GetModifiedBy() string`

GetModifiedBy returns the ModifiedBy field if non-nil, zero value otherwise.

### GetModifiedByOk

`func (o *CustomerPartsApiDeleteCustomerPartResponse) GetModifiedByOk() (*string, bool)`

GetModifiedByOk returns a tuple with the ModifiedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedBy

`func (o *CustomerPartsApiDeleteCustomerPartResponse) SetModifiedBy(v string)`

SetModifiedBy sets ModifiedBy field to given value.

### HasModifiedBy

`func (o *CustomerPartsApiDeleteCustomerPartResponse) HasModifiedBy() bool`

HasModifiedBy returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


