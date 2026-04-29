# PurchaseOrderReleasesApiCreateReleases201Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | The identifier for the Release. | [optional] 
**PoLineItemId** | Pointer to **string** | Purchase Order Line Item ID. | [optional] 
**Status** | Pointer to **string** | The Release Status. | [optional] 
**ReleaseDateTime** | Pointer to **time.Time** | The Release Date. | [optional] 
**ReleaseById** | Pointer to **string** | The IAM Account ID of the user who released the record. | [optional] 
**Quantity** | Pointer to **float64** | The Release Quantity. | [optional] 
**DueDateTime** | Pointer to **time.Time** | The Due Date of the Release. | [optional] 
**ReleaseLineNumber** | Pointer to **int32** | Release Line Number. | [optional] 
**Note** | Pointer to **string** | The Release Note. | [optional] 
**WeightQuantity** | Pointer to **float64** | The Weight Quantity. | [optional] 
**CreatedDateTime** | Pointer to **time.Time** | The date on which the record was created. | [optional] 
**ModifiedById** | Pointer to **string** | The IAM Account ID of the user who last modified the record. | [optional] 
**ModifiedDateTime** | Pointer to **time.Time** | The date on which the record was last modified. | [optional] 
**PartId** | Pointer to **string** | The Part ID associated with the Line Item. | [optional] 
**OriginalDueDateTime** | Pointer to **time.Time** | Original Due Date of the Release. | [optional] 
**PoId** | Pointer to **string** | Purchase Order ID. | [optional] 
**SupplierId** | Pointer to **string** | The Supplier ID. | [optional] 
**ReleaseAuthorizationNumber** | Pointer to **string** | Release Authorization Number. | [optional] 
**OperationCode** | Pointer to **string** | The Operation Code. | [optional] 
**Type** | Pointer to **string** | The Release Type. | [optional] 
**LineItemNo** | Pointer to **int32** | The Line Item No. | [optional] 
**PoNumber** | Pointer to **string** | The PO No. | [optional] 
**SupplierCode** | Pointer to **string** | The Supplier Code. | [optional] 
**ReleaseByDisplayName** | Pointer to **string** | Release added by (full name). | [optional] 
**ModifiedByDisplayName** | Pointer to **string** | Release last modified by (full name). | [optional] 
**PartNumber** | Pointer to **string** | The Releases part number. | [optional] 
**PartRevision** | Pointer to **string** | The Releases part revision. | [optional] 
**PartNumberRevision** | Pointer to **string** | Releases part number and revision concatenated. | [optional] 
**PoShipTo** | Pointer to **string** | Releases PO ship to location. | [optional] 
**BuildingCode** | Pointer to **string** | The code of the building associated with the PO. | [optional] 
**BuildingId** | Pointer to **string** | The ID of the building associated with the PO. | [optional] 

## Methods

### NewPurchaseOrderReleasesApiCreateReleases201Response

`func NewPurchaseOrderReleasesApiCreateReleases201Response() *PurchaseOrderReleasesApiCreateReleases201Response`

NewPurchaseOrderReleasesApiCreateReleases201Response instantiates a new PurchaseOrderReleasesApiCreateReleases201Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPurchaseOrderReleasesApiCreateReleases201ResponseWithDefaults

`func NewPurchaseOrderReleasesApiCreateReleases201ResponseWithDefaults() *PurchaseOrderReleasesApiCreateReleases201Response`

NewPurchaseOrderReleasesApiCreateReleases201ResponseWithDefaults instantiates a new PurchaseOrderReleasesApiCreateReleases201Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) HasId() bool`

HasId returns a boolean if a field has been set.

### GetPoLineItemId

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetPoLineItemId() string`

GetPoLineItemId returns the PoLineItemId field if non-nil, zero value otherwise.

### GetPoLineItemIdOk

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetPoLineItemIdOk() (*string, bool)`

GetPoLineItemIdOk returns a tuple with the PoLineItemId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoLineItemId

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) SetPoLineItemId(v string)`

SetPoLineItemId sets PoLineItemId field to given value.

### HasPoLineItemId

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) HasPoLineItemId() bool`

HasPoLineItemId returns a boolean if a field has been set.

### GetStatus

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetReleaseDateTime

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetReleaseDateTime() time.Time`

GetReleaseDateTime returns the ReleaseDateTime field if non-nil, zero value otherwise.

### GetReleaseDateTimeOk

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetReleaseDateTimeOk() (*time.Time, bool)`

GetReleaseDateTimeOk returns a tuple with the ReleaseDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleaseDateTime

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) SetReleaseDateTime(v time.Time)`

SetReleaseDateTime sets ReleaseDateTime field to given value.

### HasReleaseDateTime

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) HasReleaseDateTime() bool`

HasReleaseDateTime returns a boolean if a field has been set.

### GetReleaseById

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetReleaseById() string`

GetReleaseById returns the ReleaseById field if non-nil, zero value otherwise.

### GetReleaseByIdOk

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetReleaseByIdOk() (*string, bool)`

GetReleaseByIdOk returns a tuple with the ReleaseById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleaseById

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) SetReleaseById(v string)`

SetReleaseById sets ReleaseById field to given value.

### HasReleaseById

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) HasReleaseById() bool`

HasReleaseById returns a boolean if a field has been set.

### GetQuantity

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetDueDateTime

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetDueDateTime() time.Time`

GetDueDateTime returns the DueDateTime field if non-nil, zero value otherwise.

### GetDueDateTimeOk

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetDueDateTimeOk() (*time.Time, bool)`

GetDueDateTimeOk returns a tuple with the DueDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueDateTime

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) SetDueDateTime(v time.Time)`

SetDueDateTime sets DueDateTime field to given value.

### HasDueDateTime

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) HasDueDateTime() bool`

HasDueDateTime returns a boolean if a field has been set.

### GetReleaseLineNumber

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetReleaseLineNumber() int32`

GetReleaseLineNumber returns the ReleaseLineNumber field if non-nil, zero value otherwise.

### GetReleaseLineNumberOk

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetReleaseLineNumberOk() (*int32, bool)`

GetReleaseLineNumberOk returns a tuple with the ReleaseLineNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleaseLineNumber

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) SetReleaseLineNumber(v int32)`

SetReleaseLineNumber sets ReleaseLineNumber field to given value.

### HasReleaseLineNumber

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) HasReleaseLineNumber() bool`

HasReleaseLineNumber returns a boolean if a field has been set.

### GetNote

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetWeightQuantity

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetWeightQuantity() float64`

GetWeightQuantity returns the WeightQuantity field if non-nil, zero value otherwise.

### GetWeightQuantityOk

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetWeightQuantityOk() (*float64, bool)`

GetWeightQuantityOk returns a tuple with the WeightQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeightQuantity

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) SetWeightQuantity(v float64)`

SetWeightQuantity sets WeightQuantity field to given value.

### HasWeightQuantity

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) HasWeightQuantity() bool`

HasWeightQuantity returns a boolean if a field has been set.

### GetCreatedDateTime

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetCreatedDateTime() time.Time`

GetCreatedDateTime returns the CreatedDateTime field if non-nil, zero value otherwise.

### GetCreatedDateTimeOk

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetCreatedDateTimeOk() (*time.Time, bool)`

GetCreatedDateTimeOk returns a tuple with the CreatedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDateTime

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) SetCreatedDateTime(v time.Time)`

SetCreatedDateTime sets CreatedDateTime field to given value.

### HasCreatedDateTime

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) HasCreatedDateTime() bool`

HasCreatedDateTime returns a boolean if a field has been set.

### GetModifiedById

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetModifiedDateTime

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetModifiedDateTime() time.Time`

GetModifiedDateTime returns the ModifiedDateTime field if non-nil, zero value otherwise.

### GetModifiedDateTimeOk

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetModifiedDateTimeOk() (*time.Time, bool)`

GetModifiedDateTimeOk returns a tuple with the ModifiedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDateTime

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) SetModifiedDateTime(v time.Time)`

SetModifiedDateTime sets ModifiedDateTime field to given value.

### HasModifiedDateTime

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) HasModifiedDateTime() bool`

HasModifiedDateTime returns a boolean if a field has been set.

### GetPartId

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetOriginalDueDateTime

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetOriginalDueDateTime() time.Time`

GetOriginalDueDateTime returns the OriginalDueDateTime field if non-nil, zero value otherwise.

### GetOriginalDueDateTimeOk

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetOriginalDueDateTimeOk() (*time.Time, bool)`

GetOriginalDueDateTimeOk returns a tuple with the OriginalDueDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginalDueDateTime

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) SetOriginalDueDateTime(v time.Time)`

SetOriginalDueDateTime sets OriginalDueDateTime field to given value.

### HasOriginalDueDateTime

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) HasOriginalDueDateTime() bool`

HasOriginalDueDateTime returns a boolean if a field has been set.

### GetPoId

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetPoId() string`

GetPoId returns the PoId field if non-nil, zero value otherwise.

### GetPoIdOk

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetPoIdOk() (*string, bool)`

GetPoIdOk returns a tuple with the PoId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoId

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) SetPoId(v string)`

SetPoId sets PoId field to given value.

### HasPoId

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) HasPoId() bool`

HasPoId returns a boolean if a field has been set.

### GetSupplierId

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetSupplierId() string`

GetSupplierId returns the SupplierId field if non-nil, zero value otherwise.

### GetSupplierIdOk

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetSupplierIdOk() (*string, bool)`

GetSupplierIdOk returns a tuple with the SupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierId

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) SetSupplierId(v string)`

SetSupplierId sets SupplierId field to given value.

### HasSupplierId

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) HasSupplierId() bool`

HasSupplierId returns a boolean if a field has been set.

### GetReleaseAuthorizationNumber

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetReleaseAuthorizationNumber() string`

GetReleaseAuthorizationNumber returns the ReleaseAuthorizationNumber field if non-nil, zero value otherwise.

### GetReleaseAuthorizationNumberOk

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetReleaseAuthorizationNumberOk() (*string, bool)`

GetReleaseAuthorizationNumberOk returns a tuple with the ReleaseAuthorizationNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleaseAuthorizationNumber

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) SetReleaseAuthorizationNumber(v string)`

SetReleaseAuthorizationNumber sets ReleaseAuthorizationNumber field to given value.

### HasReleaseAuthorizationNumber

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) HasReleaseAuthorizationNumber() bool`

HasReleaseAuthorizationNumber returns a boolean if a field has been set.

### GetOperationCode

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetOperationCode() string`

GetOperationCode returns the OperationCode field if non-nil, zero value otherwise.

### GetOperationCodeOk

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetOperationCodeOk() (*string, bool)`

GetOperationCodeOk returns a tuple with the OperationCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationCode

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) SetOperationCode(v string)`

SetOperationCode sets OperationCode field to given value.

### HasOperationCode

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) HasOperationCode() bool`

HasOperationCode returns a boolean if a field has been set.

### GetType

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) HasType() bool`

HasType returns a boolean if a field has been set.

### GetLineItemNo

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetLineItemNo() int32`

GetLineItemNo returns the LineItemNo field if non-nil, zero value otherwise.

### GetLineItemNoOk

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetLineItemNoOk() (*int32, bool)`

GetLineItemNoOk returns a tuple with the LineItemNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineItemNo

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) SetLineItemNo(v int32)`

SetLineItemNo sets LineItemNo field to given value.

### HasLineItemNo

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) HasLineItemNo() bool`

HasLineItemNo returns a boolean if a field has been set.

### GetPoNumber

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetPoNumber() string`

GetPoNumber returns the PoNumber field if non-nil, zero value otherwise.

### GetPoNumberOk

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetPoNumberOk() (*string, bool)`

GetPoNumberOk returns a tuple with the PoNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoNumber

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) SetPoNumber(v string)`

SetPoNumber sets PoNumber field to given value.

### HasPoNumber

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) HasPoNumber() bool`

HasPoNumber returns a boolean if a field has been set.

### GetSupplierCode

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetSupplierCode() string`

GetSupplierCode returns the SupplierCode field if non-nil, zero value otherwise.

### GetSupplierCodeOk

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetSupplierCodeOk() (*string, bool)`

GetSupplierCodeOk returns a tuple with the SupplierCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierCode

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) SetSupplierCode(v string)`

SetSupplierCode sets SupplierCode field to given value.

### HasSupplierCode

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) HasSupplierCode() bool`

HasSupplierCode returns a boolean if a field has been set.

### GetReleaseByDisplayName

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetReleaseByDisplayName() string`

GetReleaseByDisplayName returns the ReleaseByDisplayName field if non-nil, zero value otherwise.

### GetReleaseByDisplayNameOk

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetReleaseByDisplayNameOk() (*string, bool)`

GetReleaseByDisplayNameOk returns a tuple with the ReleaseByDisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleaseByDisplayName

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) SetReleaseByDisplayName(v string)`

SetReleaseByDisplayName sets ReleaseByDisplayName field to given value.

### HasReleaseByDisplayName

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) HasReleaseByDisplayName() bool`

HasReleaseByDisplayName returns a boolean if a field has been set.

### GetModifiedByDisplayName

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetModifiedByDisplayName() string`

GetModifiedByDisplayName returns the ModifiedByDisplayName field if non-nil, zero value otherwise.

### GetModifiedByDisplayNameOk

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetModifiedByDisplayNameOk() (*string, bool)`

GetModifiedByDisplayNameOk returns a tuple with the ModifiedByDisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedByDisplayName

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) SetModifiedByDisplayName(v string)`

SetModifiedByDisplayName sets ModifiedByDisplayName field to given value.

### HasModifiedByDisplayName

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) HasModifiedByDisplayName() bool`

HasModifiedByDisplayName returns a boolean if a field has been set.

### GetPartNumber

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetPartNumber() string`

GetPartNumber returns the PartNumber field if non-nil, zero value otherwise.

### GetPartNumberOk

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetPartNumberOk() (*string, bool)`

GetPartNumberOk returns a tuple with the PartNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumber

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) SetPartNumber(v string)`

SetPartNumber sets PartNumber field to given value.

### HasPartNumber

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) HasPartNumber() bool`

HasPartNumber returns a boolean if a field has been set.

### GetPartRevision

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetPartRevision() string`

GetPartRevision returns the PartRevision field if non-nil, zero value otherwise.

### GetPartRevisionOk

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetPartRevisionOk() (*string, bool)`

GetPartRevisionOk returns a tuple with the PartRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartRevision

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) SetPartRevision(v string)`

SetPartRevision sets PartRevision field to given value.

### HasPartRevision

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) HasPartRevision() bool`

HasPartRevision returns a boolean if a field has been set.

### GetPartNumberRevision

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetPartNumberRevision() string`

GetPartNumberRevision returns the PartNumberRevision field if non-nil, zero value otherwise.

### GetPartNumberRevisionOk

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetPartNumberRevisionOk() (*string, bool)`

GetPartNumberRevisionOk returns a tuple with the PartNumberRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumberRevision

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) SetPartNumberRevision(v string)`

SetPartNumberRevision sets PartNumberRevision field to given value.

### HasPartNumberRevision

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) HasPartNumberRevision() bool`

HasPartNumberRevision returns a boolean if a field has been set.

### GetPoShipTo

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetPoShipTo() string`

GetPoShipTo returns the PoShipTo field if non-nil, zero value otherwise.

### GetPoShipToOk

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetPoShipToOk() (*string, bool)`

GetPoShipToOk returns a tuple with the PoShipTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoShipTo

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) SetPoShipTo(v string)`

SetPoShipTo sets PoShipTo field to given value.

### HasPoShipTo

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) HasPoShipTo() bool`

HasPoShipTo returns a boolean if a field has been set.

### GetBuildingCode

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetBuildingCode() string`

GetBuildingCode returns the BuildingCode field if non-nil, zero value otherwise.

### GetBuildingCodeOk

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetBuildingCodeOk() (*string, bool)`

GetBuildingCodeOk returns a tuple with the BuildingCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildingCode

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) SetBuildingCode(v string)`

SetBuildingCode sets BuildingCode field to given value.

### HasBuildingCode

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) HasBuildingCode() bool`

HasBuildingCode returns a boolean if a field has been set.

### GetBuildingId

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetBuildingId() string`

GetBuildingId returns the BuildingId field if non-nil, zero value otherwise.

### GetBuildingIdOk

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) GetBuildingIdOk() (*string, bool)`

GetBuildingIdOk returns a tuple with the BuildingId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildingId

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) SetBuildingId(v string)`

SetBuildingId sets BuildingId field to given value.

### HasBuildingId

`func (o *PurchaseOrderReleasesApiCreateReleases201Response) HasBuildingId() bool`

HasBuildingId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


