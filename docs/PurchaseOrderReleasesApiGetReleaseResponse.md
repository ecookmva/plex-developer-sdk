# PurchaseOrderReleasesApiGetReleaseResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | The identifier for the Release. | [optional] 
**PoLineItemId** | Pointer to **string** | Purchase Order Line Item ID. | [optional] 
**Status** | Pointer to **string** | Release Status. | [optional] 
**ReleaseDate** | Pointer to **time.Time** | Release Date. | [optional] 
**ReleaseById** | Pointer to **string** | The IAM Account ID of the user who released the record. | [optional] 
**Quantity** | Pointer to **float64** | Release Quantity. | [optional] 
**DueDate** | Pointer to **time.Time** | The Due Date of the Release. | [optional] 
**ReleaseLineNumber** | Pointer to **int32** | Release Line Number. | [optional] 
**Note** | Pointer to **string** | Release Note. | [optional] 
**WeightQuantity** | Pointer to **float64** | Weight Quantity. | [optional] 
**CreatedDate** | Pointer to **time.Time** | The date on which the record was created. | [optional] 
**ModifiedById** | Pointer to **string** | The IAM Account ID of the user who last modified the record. | [optional] 
**ModifiedDate** | Pointer to **time.Time** | The date on which the record was last modified. | [optional] 
**PartId** | Pointer to **string** | The Part ID associated with the Line Item. | [optional] 
**OriginalDueDate** | Pointer to **time.Time** | Original Due Date of the Release. | [optional] 
**PoId** | Pointer to **string** | Purchase Order ID. | [optional] 
**SupplierId** | Pointer to **string** | Supplier ID. | [optional] 
**ReleaseAuthorizationNumber** | Pointer to **string** | Release Authorization Number. | [optional] 
**OperationCode** | Pointer to **string** | Operation Code. | [optional] 
**Type** | Pointer to **string** | Release Type. | [optional] 
**LineItemNo** | Pointer to **int32** | Line Item No. | [optional] 
**PoNumber** | Pointer to **string** | PO No. | [optional] 
**SupplierCode** | Pointer to **string** | Supplier Code. | [optional] 
**ReleaseByDisplayName** | Pointer to **string** | Release added by (full name). | [optional] 
**ModifiedByDisplayName** | Pointer to **string** | Release last modified by (full name). | [optional] 
**PartNumber** | Pointer to **string** | Releases part number. | [optional] 
**PartRevision** | Pointer to **string** | Releases part revision | [optional] 
**PartNumberRevision** | Pointer to **string** | Releases part number and revision concatenated | [optional] 
**PoShipTo** | Pointer to **string** | Releases PO ship to location. | [optional] 
**BuildingCode** | Pointer to **string** | The code of the building associated with the PO. | [optional] 
**BuildingId** | Pointer to **string** | The ID of the building associated with the PO. | [optional] 

## Methods

### NewPurchaseOrderReleasesApiGetReleaseResponse

`func NewPurchaseOrderReleasesApiGetReleaseResponse() *PurchaseOrderReleasesApiGetReleaseResponse`

NewPurchaseOrderReleasesApiGetReleaseResponse instantiates a new PurchaseOrderReleasesApiGetReleaseResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPurchaseOrderReleasesApiGetReleaseResponseWithDefaults

`func NewPurchaseOrderReleasesApiGetReleaseResponseWithDefaults() *PurchaseOrderReleasesApiGetReleaseResponse`

NewPurchaseOrderReleasesApiGetReleaseResponseWithDefaults instantiates a new PurchaseOrderReleasesApiGetReleaseResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetPoLineItemId

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetPoLineItemId() string`

GetPoLineItemId returns the PoLineItemId field if non-nil, zero value otherwise.

### GetPoLineItemIdOk

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetPoLineItemIdOk() (*string, bool)`

GetPoLineItemIdOk returns a tuple with the PoLineItemId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoLineItemId

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) SetPoLineItemId(v string)`

SetPoLineItemId sets PoLineItemId field to given value.

### HasPoLineItemId

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) HasPoLineItemId() bool`

HasPoLineItemId returns a boolean if a field has been set.

### GetStatus

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetReleaseDate

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetReleaseDate() time.Time`

GetReleaseDate returns the ReleaseDate field if non-nil, zero value otherwise.

### GetReleaseDateOk

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetReleaseDateOk() (*time.Time, bool)`

GetReleaseDateOk returns a tuple with the ReleaseDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleaseDate

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) SetReleaseDate(v time.Time)`

SetReleaseDate sets ReleaseDate field to given value.

### HasReleaseDate

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) HasReleaseDate() bool`

HasReleaseDate returns a boolean if a field has been set.

### GetReleaseById

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetReleaseById() string`

GetReleaseById returns the ReleaseById field if non-nil, zero value otherwise.

### GetReleaseByIdOk

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetReleaseByIdOk() (*string, bool)`

GetReleaseByIdOk returns a tuple with the ReleaseById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleaseById

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) SetReleaseById(v string)`

SetReleaseById sets ReleaseById field to given value.

### HasReleaseById

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) HasReleaseById() bool`

HasReleaseById returns a boolean if a field has been set.

### GetQuantity

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetDueDate

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetDueDate() time.Time`

GetDueDate returns the DueDate field if non-nil, zero value otherwise.

### GetDueDateOk

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetDueDateOk() (*time.Time, bool)`

GetDueDateOk returns a tuple with the DueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueDate

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) SetDueDate(v time.Time)`

SetDueDate sets DueDate field to given value.

### HasDueDate

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) HasDueDate() bool`

HasDueDate returns a boolean if a field has been set.

### GetReleaseLineNumber

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetReleaseLineNumber() int32`

GetReleaseLineNumber returns the ReleaseLineNumber field if non-nil, zero value otherwise.

### GetReleaseLineNumberOk

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetReleaseLineNumberOk() (*int32, bool)`

GetReleaseLineNumberOk returns a tuple with the ReleaseLineNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleaseLineNumber

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) SetReleaseLineNumber(v int32)`

SetReleaseLineNumber sets ReleaseLineNumber field to given value.

### HasReleaseLineNumber

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) HasReleaseLineNumber() bool`

HasReleaseLineNumber returns a boolean if a field has been set.

### GetNote

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetWeightQuantity

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetWeightQuantity() float64`

GetWeightQuantity returns the WeightQuantity field if non-nil, zero value otherwise.

### GetWeightQuantityOk

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetWeightQuantityOk() (*float64, bool)`

GetWeightQuantityOk returns a tuple with the WeightQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeightQuantity

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) SetWeightQuantity(v float64)`

SetWeightQuantity sets WeightQuantity field to given value.

### HasWeightQuantity

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) HasWeightQuantity() bool`

HasWeightQuantity returns a boolean if a field has been set.

### GetCreatedDate

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.

### GetModifiedById

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetModifiedDate

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetModifiedDate() time.Time`

GetModifiedDate returns the ModifiedDate field if non-nil, zero value otherwise.

### GetModifiedDateOk

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetModifiedDateOk() (*time.Time, bool)`

GetModifiedDateOk returns a tuple with the ModifiedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDate

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) SetModifiedDate(v time.Time)`

SetModifiedDate sets ModifiedDate field to given value.

### HasModifiedDate

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) HasModifiedDate() bool`

HasModifiedDate returns a boolean if a field has been set.

### GetPartId

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetOriginalDueDate

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetOriginalDueDate() time.Time`

GetOriginalDueDate returns the OriginalDueDate field if non-nil, zero value otherwise.

### GetOriginalDueDateOk

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetOriginalDueDateOk() (*time.Time, bool)`

GetOriginalDueDateOk returns a tuple with the OriginalDueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginalDueDate

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) SetOriginalDueDate(v time.Time)`

SetOriginalDueDate sets OriginalDueDate field to given value.

### HasOriginalDueDate

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) HasOriginalDueDate() bool`

HasOriginalDueDate returns a boolean if a field has been set.

### GetPoId

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetPoId() string`

GetPoId returns the PoId field if non-nil, zero value otherwise.

### GetPoIdOk

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetPoIdOk() (*string, bool)`

GetPoIdOk returns a tuple with the PoId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoId

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) SetPoId(v string)`

SetPoId sets PoId field to given value.

### HasPoId

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) HasPoId() bool`

HasPoId returns a boolean if a field has been set.

### GetSupplierId

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetSupplierId() string`

GetSupplierId returns the SupplierId field if non-nil, zero value otherwise.

### GetSupplierIdOk

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetSupplierIdOk() (*string, bool)`

GetSupplierIdOk returns a tuple with the SupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierId

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) SetSupplierId(v string)`

SetSupplierId sets SupplierId field to given value.

### HasSupplierId

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) HasSupplierId() bool`

HasSupplierId returns a boolean if a field has been set.

### GetReleaseAuthorizationNumber

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetReleaseAuthorizationNumber() string`

GetReleaseAuthorizationNumber returns the ReleaseAuthorizationNumber field if non-nil, zero value otherwise.

### GetReleaseAuthorizationNumberOk

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetReleaseAuthorizationNumberOk() (*string, bool)`

GetReleaseAuthorizationNumberOk returns a tuple with the ReleaseAuthorizationNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleaseAuthorizationNumber

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) SetReleaseAuthorizationNumber(v string)`

SetReleaseAuthorizationNumber sets ReleaseAuthorizationNumber field to given value.

### HasReleaseAuthorizationNumber

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) HasReleaseAuthorizationNumber() bool`

HasReleaseAuthorizationNumber returns a boolean if a field has been set.

### GetOperationCode

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetOperationCode() string`

GetOperationCode returns the OperationCode field if non-nil, zero value otherwise.

### GetOperationCodeOk

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetOperationCodeOk() (*string, bool)`

GetOperationCodeOk returns a tuple with the OperationCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationCode

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) SetOperationCode(v string)`

SetOperationCode sets OperationCode field to given value.

### HasOperationCode

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) HasOperationCode() bool`

HasOperationCode returns a boolean if a field has been set.

### GetType

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) HasType() bool`

HasType returns a boolean if a field has been set.

### GetLineItemNo

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetLineItemNo() int32`

GetLineItemNo returns the LineItemNo field if non-nil, zero value otherwise.

### GetLineItemNoOk

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetLineItemNoOk() (*int32, bool)`

GetLineItemNoOk returns a tuple with the LineItemNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineItemNo

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) SetLineItemNo(v int32)`

SetLineItemNo sets LineItemNo field to given value.

### HasLineItemNo

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) HasLineItemNo() bool`

HasLineItemNo returns a boolean if a field has been set.

### GetPoNumber

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetPoNumber() string`

GetPoNumber returns the PoNumber field if non-nil, zero value otherwise.

### GetPoNumberOk

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetPoNumberOk() (*string, bool)`

GetPoNumberOk returns a tuple with the PoNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoNumber

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) SetPoNumber(v string)`

SetPoNumber sets PoNumber field to given value.

### HasPoNumber

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) HasPoNumber() bool`

HasPoNumber returns a boolean if a field has been set.

### GetSupplierCode

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetSupplierCode() string`

GetSupplierCode returns the SupplierCode field if non-nil, zero value otherwise.

### GetSupplierCodeOk

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetSupplierCodeOk() (*string, bool)`

GetSupplierCodeOk returns a tuple with the SupplierCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierCode

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) SetSupplierCode(v string)`

SetSupplierCode sets SupplierCode field to given value.

### HasSupplierCode

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) HasSupplierCode() bool`

HasSupplierCode returns a boolean if a field has been set.

### GetReleaseByDisplayName

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetReleaseByDisplayName() string`

GetReleaseByDisplayName returns the ReleaseByDisplayName field if non-nil, zero value otherwise.

### GetReleaseByDisplayNameOk

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetReleaseByDisplayNameOk() (*string, bool)`

GetReleaseByDisplayNameOk returns a tuple with the ReleaseByDisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleaseByDisplayName

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) SetReleaseByDisplayName(v string)`

SetReleaseByDisplayName sets ReleaseByDisplayName field to given value.

### HasReleaseByDisplayName

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) HasReleaseByDisplayName() bool`

HasReleaseByDisplayName returns a boolean if a field has been set.

### GetModifiedByDisplayName

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetModifiedByDisplayName() string`

GetModifiedByDisplayName returns the ModifiedByDisplayName field if non-nil, zero value otherwise.

### GetModifiedByDisplayNameOk

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetModifiedByDisplayNameOk() (*string, bool)`

GetModifiedByDisplayNameOk returns a tuple with the ModifiedByDisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedByDisplayName

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) SetModifiedByDisplayName(v string)`

SetModifiedByDisplayName sets ModifiedByDisplayName field to given value.

### HasModifiedByDisplayName

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) HasModifiedByDisplayName() bool`

HasModifiedByDisplayName returns a boolean if a field has been set.

### GetPartNumber

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetPartNumber() string`

GetPartNumber returns the PartNumber field if non-nil, zero value otherwise.

### GetPartNumberOk

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetPartNumberOk() (*string, bool)`

GetPartNumberOk returns a tuple with the PartNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumber

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) SetPartNumber(v string)`

SetPartNumber sets PartNumber field to given value.

### HasPartNumber

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) HasPartNumber() bool`

HasPartNumber returns a boolean if a field has been set.

### GetPartRevision

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetPartRevision() string`

GetPartRevision returns the PartRevision field if non-nil, zero value otherwise.

### GetPartRevisionOk

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetPartRevisionOk() (*string, bool)`

GetPartRevisionOk returns a tuple with the PartRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartRevision

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) SetPartRevision(v string)`

SetPartRevision sets PartRevision field to given value.

### HasPartRevision

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) HasPartRevision() bool`

HasPartRevision returns a boolean if a field has been set.

### GetPartNumberRevision

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetPartNumberRevision() string`

GetPartNumberRevision returns the PartNumberRevision field if non-nil, zero value otherwise.

### GetPartNumberRevisionOk

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetPartNumberRevisionOk() (*string, bool)`

GetPartNumberRevisionOk returns a tuple with the PartNumberRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumberRevision

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) SetPartNumberRevision(v string)`

SetPartNumberRevision sets PartNumberRevision field to given value.

### HasPartNumberRevision

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) HasPartNumberRevision() bool`

HasPartNumberRevision returns a boolean if a field has been set.

### GetPoShipTo

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetPoShipTo() string`

GetPoShipTo returns the PoShipTo field if non-nil, zero value otherwise.

### GetPoShipToOk

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetPoShipToOk() (*string, bool)`

GetPoShipToOk returns a tuple with the PoShipTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoShipTo

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) SetPoShipTo(v string)`

SetPoShipTo sets PoShipTo field to given value.

### HasPoShipTo

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) HasPoShipTo() bool`

HasPoShipTo returns a boolean if a field has been set.

### GetBuildingCode

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetBuildingCode() string`

GetBuildingCode returns the BuildingCode field if non-nil, zero value otherwise.

### GetBuildingCodeOk

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetBuildingCodeOk() (*string, bool)`

GetBuildingCodeOk returns a tuple with the BuildingCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildingCode

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) SetBuildingCode(v string)`

SetBuildingCode sets BuildingCode field to given value.

### HasBuildingCode

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) HasBuildingCode() bool`

HasBuildingCode returns a boolean if a field has been set.

### GetBuildingId

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetBuildingId() string`

GetBuildingId returns the BuildingId field if non-nil, zero value otherwise.

### GetBuildingIdOk

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) GetBuildingIdOk() (*string, bool)`

GetBuildingIdOk returns a tuple with the BuildingId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildingId

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) SetBuildingId(v string)`

SetBuildingId sets BuildingId field to given value.

### HasBuildingId

`func (o *PurchaseOrderReleasesApiGetReleaseResponse) HasBuildingId() bool`

HasBuildingId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


