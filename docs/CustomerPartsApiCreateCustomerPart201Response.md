# CustomerPartsApiCreateCustomerPart201Response

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

### NewCustomerPartsApiCreateCustomerPart201Response

`func NewCustomerPartsApiCreateCustomerPart201Response() *CustomerPartsApiCreateCustomerPart201Response`

NewCustomerPartsApiCreateCustomerPart201Response instantiates a new CustomerPartsApiCreateCustomerPart201Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomerPartsApiCreateCustomerPart201ResponseWithDefaults

`func NewCustomerPartsApiCreateCustomerPart201ResponseWithDefaults() *CustomerPartsApiCreateCustomerPart201Response`

NewCustomerPartsApiCreateCustomerPart201ResponseWithDefaults instantiates a new CustomerPartsApiCreateCustomerPart201Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CustomerPartsApiCreateCustomerPart201Response) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CustomerPartsApiCreateCustomerPart201Response) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CustomerPartsApiCreateCustomerPart201Response) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *CustomerPartsApiCreateCustomerPart201Response) HasId() bool`

HasId returns a boolean if a field has been set.

### GetNumber

`func (o *CustomerPartsApiCreateCustomerPart201Response) GetNumber() string`

GetNumber returns the Number field if non-nil, zero value otherwise.

### GetNumberOk

`func (o *CustomerPartsApiCreateCustomerPart201Response) GetNumberOk() (*string, bool)`

GetNumberOk returns a tuple with the Number field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumber

`func (o *CustomerPartsApiCreateCustomerPart201Response) SetNumber(v string)`

SetNumber sets Number field to given value.

### HasNumber

`func (o *CustomerPartsApiCreateCustomerPart201Response) HasNumber() bool`

HasNumber returns a boolean if a field has been set.

### GetPartId

`func (o *CustomerPartsApiCreateCustomerPart201Response) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *CustomerPartsApiCreateCustomerPart201Response) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *CustomerPartsApiCreateCustomerPart201Response) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *CustomerPartsApiCreateCustomerPart201Response) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetCustomerId

`func (o *CustomerPartsApiCreateCustomerPart201Response) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *CustomerPartsApiCreateCustomerPart201Response) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *CustomerPartsApiCreateCustomerPart201Response) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *CustomerPartsApiCreateCustomerPart201Response) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### GetDescription

`func (o *CustomerPartsApiCreateCustomerPart201Response) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CustomerPartsApiCreateCustomerPart201Response) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CustomerPartsApiCreateCustomerPart201Response) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CustomerPartsApiCreateCustomerPart201Response) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetRevision

`func (o *CustomerPartsApiCreateCustomerPart201Response) GetRevision() string`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *CustomerPartsApiCreateCustomerPart201Response) GetRevisionOk() (*string, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *CustomerPartsApiCreateCustomerPart201Response) SetRevision(v string)`

SetRevision sets Revision field to given value.

### HasRevision

`func (o *CustomerPartsApiCreateCustomerPart201Response) HasRevision() bool`

HasRevision returns a boolean if a field has been set.

### GetModifiedDateTime

`func (o *CustomerPartsApiCreateCustomerPart201Response) GetModifiedDateTime() time.Time`

GetModifiedDateTime returns the ModifiedDateTime field if non-nil, zero value otherwise.

### GetModifiedDateTimeOk

`func (o *CustomerPartsApiCreateCustomerPart201Response) GetModifiedDateTimeOk() (*time.Time, bool)`

GetModifiedDateTimeOk returns a tuple with the ModifiedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDateTime

`func (o *CustomerPartsApiCreateCustomerPart201Response) SetModifiedDateTime(v time.Time)`

SetModifiedDateTime sets ModifiedDateTime field to given value.

### HasModifiedDateTime

`func (o *CustomerPartsApiCreateCustomerPart201Response) HasModifiedDateTime() bool`

HasModifiedDateTime returns a boolean if a field has been set.

### GetModifiedBy

`func (o *CustomerPartsApiCreateCustomerPart201Response) GetModifiedBy() string`

GetModifiedBy returns the ModifiedBy field if non-nil, zero value otherwise.

### GetModifiedByOk

`func (o *CustomerPartsApiCreateCustomerPart201Response) GetModifiedByOk() (*string, bool)`

GetModifiedByOk returns a tuple with the ModifiedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedBy

`func (o *CustomerPartsApiCreateCustomerPart201Response) SetModifiedBy(v string)`

SetModifiedBy sets ModifiedBy field to given value.

### HasModifiedBy

`func (o *CustomerPartsApiCreateCustomerPart201Response) HasModifiedBy() bool`

HasModifiedBy returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


