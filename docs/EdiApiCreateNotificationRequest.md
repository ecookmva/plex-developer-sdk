# EdiApiCreateNotificationRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CustomerId** | Pointer to **string** | A unique identifier for the customer that the notification is being generated about. | [optional] 
**DocumentName** | Pointer to **string** | The name of the EDI document that the notification is being generated about (ex: DELJIT). | [optional] 
**NotificationBody** | Pointer to **string** | The body of the notification. | [optional] 
**NotificationSubject** | Pointer to **string** | The subject of the notification. | [optional] 
**NotificationType** | Pointer to **string** | The type of the notification. | [optional] 
**ShipFromId** | Pointer to **string** | Optional unique identifier identifying the ship from location that the notification is being generated about. | [optional] 

## Methods

### NewEdiApiCreateNotificationRequest

`func NewEdiApiCreateNotificationRequest() *EdiApiCreateNotificationRequest`

NewEdiApiCreateNotificationRequest instantiates a new EdiApiCreateNotificationRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEdiApiCreateNotificationRequestWithDefaults

`func NewEdiApiCreateNotificationRequestWithDefaults() *EdiApiCreateNotificationRequest`

NewEdiApiCreateNotificationRequestWithDefaults instantiates a new EdiApiCreateNotificationRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCustomerId

`func (o *EdiApiCreateNotificationRequest) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *EdiApiCreateNotificationRequest) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *EdiApiCreateNotificationRequest) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *EdiApiCreateNotificationRequest) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### GetDocumentName

`func (o *EdiApiCreateNotificationRequest) GetDocumentName() string`

GetDocumentName returns the DocumentName field if non-nil, zero value otherwise.

### GetDocumentNameOk

`func (o *EdiApiCreateNotificationRequest) GetDocumentNameOk() (*string, bool)`

GetDocumentNameOk returns a tuple with the DocumentName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocumentName

`func (o *EdiApiCreateNotificationRequest) SetDocumentName(v string)`

SetDocumentName sets DocumentName field to given value.

### HasDocumentName

`func (o *EdiApiCreateNotificationRequest) HasDocumentName() bool`

HasDocumentName returns a boolean if a field has been set.

### GetNotificationBody

`func (o *EdiApiCreateNotificationRequest) GetNotificationBody() string`

GetNotificationBody returns the NotificationBody field if non-nil, zero value otherwise.

### GetNotificationBodyOk

`func (o *EdiApiCreateNotificationRequest) GetNotificationBodyOk() (*string, bool)`

GetNotificationBodyOk returns a tuple with the NotificationBody field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotificationBody

`func (o *EdiApiCreateNotificationRequest) SetNotificationBody(v string)`

SetNotificationBody sets NotificationBody field to given value.

### HasNotificationBody

`func (o *EdiApiCreateNotificationRequest) HasNotificationBody() bool`

HasNotificationBody returns a boolean if a field has been set.

### GetNotificationSubject

`func (o *EdiApiCreateNotificationRequest) GetNotificationSubject() string`

GetNotificationSubject returns the NotificationSubject field if non-nil, zero value otherwise.

### GetNotificationSubjectOk

`func (o *EdiApiCreateNotificationRequest) GetNotificationSubjectOk() (*string, bool)`

GetNotificationSubjectOk returns a tuple with the NotificationSubject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotificationSubject

`func (o *EdiApiCreateNotificationRequest) SetNotificationSubject(v string)`

SetNotificationSubject sets NotificationSubject field to given value.

### HasNotificationSubject

`func (o *EdiApiCreateNotificationRequest) HasNotificationSubject() bool`

HasNotificationSubject returns a boolean if a field has been set.

### GetNotificationType

`func (o *EdiApiCreateNotificationRequest) GetNotificationType() string`

GetNotificationType returns the NotificationType field if non-nil, zero value otherwise.

### GetNotificationTypeOk

`func (o *EdiApiCreateNotificationRequest) GetNotificationTypeOk() (*string, bool)`

GetNotificationTypeOk returns a tuple with the NotificationType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotificationType

`func (o *EdiApiCreateNotificationRequest) SetNotificationType(v string)`

SetNotificationType sets NotificationType field to given value.

### HasNotificationType

`func (o *EdiApiCreateNotificationRequest) HasNotificationType() bool`

HasNotificationType returns a boolean if a field has been set.

### GetShipFromId

`func (o *EdiApiCreateNotificationRequest) GetShipFromId() string`

GetShipFromId returns the ShipFromId field if non-nil, zero value otherwise.

### GetShipFromIdOk

`func (o *EdiApiCreateNotificationRequest) GetShipFromIdOk() (*string, bool)`

GetShipFromIdOk returns a tuple with the ShipFromId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipFromId

`func (o *EdiApiCreateNotificationRequest) SetShipFromId(v string)`

SetShipFromId sets ShipFromId field to given value.

### HasShipFromId

`func (o *EdiApiCreateNotificationRequest) HasShipFromId() bool`

HasShipFromId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


