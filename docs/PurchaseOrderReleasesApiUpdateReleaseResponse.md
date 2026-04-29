# PurchaseOrderReleasesApiUpdateReleaseResponse

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

### NewPurchaseOrderReleasesApiUpdateReleaseResponse

`func NewPurchaseOrderReleasesApiUpdateReleaseResponse() *PurchaseOrderReleasesApiUpdateReleaseResponse`

NewPurchaseOrderReleasesApiUpdateReleaseResponse instantiates a new PurchaseOrderReleasesApiUpdateReleaseResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPurchaseOrderReleasesApiUpdateReleaseResponseWithDefaults

`func NewPurchaseOrderReleasesApiUpdateReleaseResponseWithDefaults() *PurchaseOrderReleasesApiUpdateReleaseResponse`

NewPurchaseOrderReleasesApiUpdateReleaseResponseWithDefaults instantiates a new PurchaseOrderReleasesApiUpdateReleaseResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetPoLineItemId

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetPoLineItemId() string`

GetPoLineItemId returns the PoLineItemId field if non-nil, zero value otherwise.

### GetPoLineItemIdOk

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetPoLineItemIdOk() (*string, bool)`

GetPoLineItemIdOk returns a tuple with the PoLineItemId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoLineItemId

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) SetPoLineItemId(v string)`

SetPoLineItemId sets PoLineItemId field to given value.

### HasPoLineItemId

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) HasPoLineItemId() bool`

HasPoLineItemId returns a boolean if a field has been set.

### GetStatus

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetReleaseDate

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetReleaseDate() time.Time`

GetReleaseDate returns the ReleaseDate field if non-nil, zero value otherwise.

### GetReleaseDateOk

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetReleaseDateOk() (*time.Time, bool)`

GetReleaseDateOk returns a tuple with the ReleaseDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleaseDate

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) SetReleaseDate(v time.Time)`

SetReleaseDate sets ReleaseDate field to given value.

### HasReleaseDate

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) HasReleaseDate() bool`

HasReleaseDate returns a boolean if a field has been set.

### GetReleaseById

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetReleaseById() string`

GetReleaseById returns the ReleaseById field if non-nil, zero value otherwise.

### GetReleaseByIdOk

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetReleaseByIdOk() (*string, bool)`

GetReleaseByIdOk returns a tuple with the ReleaseById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleaseById

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) SetReleaseById(v string)`

SetReleaseById sets ReleaseById field to given value.

### HasReleaseById

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) HasReleaseById() bool`

HasReleaseById returns a boolean if a field has been set.

### GetQuantity

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetDueDate

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetDueDate() time.Time`

GetDueDate returns the DueDate field if non-nil, zero value otherwise.

### GetDueDateOk

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetDueDateOk() (*time.Time, bool)`

GetDueDateOk returns a tuple with the DueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueDate

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) SetDueDate(v time.Time)`

SetDueDate sets DueDate field to given value.

### HasDueDate

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) HasDueDate() bool`

HasDueDate returns a boolean if a field has been set.

### GetReleaseLineNumber

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetReleaseLineNumber() int32`

GetReleaseLineNumber returns the ReleaseLineNumber field if non-nil, zero value otherwise.

### GetReleaseLineNumberOk

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetReleaseLineNumberOk() (*int32, bool)`

GetReleaseLineNumberOk returns a tuple with the ReleaseLineNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleaseLineNumber

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) SetReleaseLineNumber(v int32)`

SetReleaseLineNumber sets ReleaseLineNumber field to given value.

### HasReleaseLineNumber

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) HasReleaseLineNumber() bool`

HasReleaseLineNumber returns a boolean if a field has been set.

### GetNote

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetWeightQuantity

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetWeightQuantity() float64`

GetWeightQuantity returns the WeightQuantity field if non-nil, zero value otherwise.

### GetWeightQuantityOk

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetWeightQuantityOk() (*float64, bool)`

GetWeightQuantityOk returns a tuple with the WeightQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeightQuantity

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) SetWeightQuantity(v float64)`

SetWeightQuantity sets WeightQuantity field to given value.

### HasWeightQuantity

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) HasWeightQuantity() bool`

HasWeightQuantity returns a boolean if a field has been set.

### GetCreatedDate

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.

### HasCreatedDate

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) HasCreatedDate() bool`

HasCreatedDate returns a boolean if a field has been set.

### GetModifiedById

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetModifiedById() string`

GetModifiedById returns the ModifiedById field if non-nil, zero value otherwise.

### GetModifiedByIdOk

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetModifiedByIdOk() (*string, bool)`

GetModifiedByIdOk returns a tuple with the ModifiedById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedById

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) SetModifiedById(v string)`

SetModifiedById sets ModifiedById field to given value.

### HasModifiedById

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) HasModifiedById() bool`

HasModifiedById returns a boolean if a field has been set.

### GetModifiedDate

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetModifiedDate() time.Time`

GetModifiedDate returns the ModifiedDate field if non-nil, zero value otherwise.

### GetModifiedDateOk

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetModifiedDateOk() (*time.Time, bool)`

GetModifiedDateOk returns a tuple with the ModifiedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedDate

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) SetModifiedDate(v time.Time)`

SetModifiedDate sets ModifiedDate field to given value.

### HasModifiedDate

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) HasModifiedDate() bool`

HasModifiedDate returns a boolean if a field has been set.

### GetPartId

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetPartId() string`

GetPartId returns the PartId field if non-nil, zero value otherwise.

### GetPartIdOk

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetPartIdOk() (*string, bool)`

GetPartIdOk returns a tuple with the PartId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartId

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) SetPartId(v string)`

SetPartId sets PartId field to given value.

### HasPartId

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) HasPartId() bool`

HasPartId returns a boolean if a field has been set.

### GetOriginalDueDate

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetOriginalDueDate() time.Time`

GetOriginalDueDate returns the OriginalDueDate field if non-nil, zero value otherwise.

### GetOriginalDueDateOk

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetOriginalDueDateOk() (*time.Time, bool)`

GetOriginalDueDateOk returns a tuple with the OriginalDueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginalDueDate

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) SetOriginalDueDate(v time.Time)`

SetOriginalDueDate sets OriginalDueDate field to given value.

### HasOriginalDueDate

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) HasOriginalDueDate() bool`

HasOriginalDueDate returns a boolean if a field has been set.

### GetPoId

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetPoId() string`

GetPoId returns the PoId field if non-nil, zero value otherwise.

### GetPoIdOk

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetPoIdOk() (*string, bool)`

GetPoIdOk returns a tuple with the PoId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoId

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) SetPoId(v string)`

SetPoId sets PoId field to given value.

### HasPoId

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) HasPoId() bool`

HasPoId returns a boolean if a field has been set.

### GetSupplierId

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetSupplierId() string`

GetSupplierId returns the SupplierId field if non-nil, zero value otherwise.

### GetSupplierIdOk

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetSupplierIdOk() (*string, bool)`

GetSupplierIdOk returns a tuple with the SupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierId

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) SetSupplierId(v string)`

SetSupplierId sets SupplierId field to given value.

### HasSupplierId

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) HasSupplierId() bool`

HasSupplierId returns a boolean if a field has been set.

### GetReleaseAuthorizationNumber

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetReleaseAuthorizationNumber() string`

GetReleaseAuthorizationNumber returns the ReleaseAuthorizationNumber field if non-nil, zero value otherwise.

### GetReleaseAuthorizationNumberOk

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetReleaseAuthorizationNumberOk() (*string, bool)`

GetReleaseAuthorizationNumberOk returns a tuple with the ReleaseAuthorizationNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleaseAuthorizationNumber

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) SetReleaseAuthorizationNumber(v string)`

SetReleaseAuthorizationNumber sets ReleaseAuthorizationNumber field to given value.

### HasReleaseAuthorizationNumber

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) HasReleaseAuthorizationNumber() bool`

HasReleaseAuthorizationNumber returns a boolean if a field has been set.

### GetOperationCode

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetOperationCode() string`

GetOperationCode returns the OperationCode field if non-nil, zero value otherwise.

### GetOperationCodeOk

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetOperationCodeOk() (*string, bool)`

GetOperationCodeOk returns a tuple with the OperationCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationCode

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) SetOperationCode(v string)`

SetOperationCode sets OperationCode field to given value.

### HasOperationCode

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) HasOperationCode() bool`

HasOperationCode returns a boolean if a field has been set.

### GetType

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) HasType() bool`

HasType returns a boolean if a field has been set.

### GetLineItemNo

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetLineItemNo() int32`

GetLineItemNo returns the LineItemNo field if non-nil, zero value otherwise.

### GetLineItemNoOk

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetLineItemNoOk() (*int32, bool)`

GetLineItemNoOk returns a tuple with the LineItemNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineItemNo

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) SetLineItemNo(v int32)`

SetLineItemNo sets LineItemNo field to given value.

### HasLineItemNo

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) HasLineItemNo() bool`

HasLineItemNo returns a boolean if a field has been set.

### GetPoNumber

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetPoNumber() string`

GetPoNumber returns the PoNumber field if non-nil, zero value otherwise.

### GetPoNumberOk

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetPoNumberOk() (*string, bool)`

GetPoNumberOk returns a tuple with the PoNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoNumber

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) SetPoNumber(v string)`

SetPoNumber sets PoNumber field to given value.

### HasPoNumber

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) HasPoNumber() bool`

HasPoNumber returns a boolean if a field has been set.

### GetSupplierCode

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetSupplierCode() string`

GetSupplierCode returns the SupplierCode field if non-nil, zero value otherwise.

### GetSupplierCodeOk

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetSupplierCodeOk() (*string, bool)`

GetSupplierCodeOk returns a tuple with the SupplierCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierCode

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) SetSupplierCode(v string)`

SetSupplierCode sets SupplierCode field to given value.

### HasSupplierCode

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) HasSupplierCode() bool`

HasSupplierCode returns a boolean if a field has been set.

### GetReleaseByDisplayName

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetReleaseByDisplayName() string`

GetReleaseByDisplayName returns the ReleaseByDisplayName field if non-nil, zero value otherwise.

### GetReleaseByDisplayNameOk

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetReleaseByDisplayNameOk() (*string, bool)`

GetReleaseByDisplayNameOk returns a tuple with the ReleaseByDisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleaseByDisplayName

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) SetReleaseByDisplayName(v string)`

SetReleaseByDisplayName sets ReleaseByDisplayName field to given value.

### HasReleaseByDisplayName

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) HasReleaseByDisplayName() bool`

HasReleaseByDisplayName returns a boolean if a field has been set.

### GetModifiedByDisplayName

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetModifiedByDisplayName() string`

GetModifiedByDisplayName returns the ModifiedByDisplayName field if non-nil, zero value otherwise.

### GetModifiedByDisplayNameOk

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetModifiedByDisplayNameOk() (*string, bool)`

GetModifiedByDisplayNameOk returns a tuple with the ModifiedByDisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedByDisplayName

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) SetModifiedByDisplayName(v string)`

SetModifiedByDisplayName sets ModifiedByDisplayName field to given value.

### HasModifiedByDisplayName

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) HasModifiedByDisplayName() bool`

HasModifiedByDisplayName returns a boolean if a field has been set.

### GetPartNumber

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetPartNumber() string`

GetPartNumber returns the PartNumber field if non-nil, zero value otherwise.

### GetPartNumberOk

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetPartNumberOk() (*string, bool)`

GetPartNumberOk returns a tuple with the PartNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumber

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) SetPartNumber(v string)`

SetPartNumber sets PartNumber field to given value.

### HasPartNumber

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) HasPartNumber() bool`

HasPartNumber returns a boolean if a field has been set.

### GetPartRevision

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetPartRevision() string`

GetPartRevision returns the PartRevision field if non-nil, zero value otherwise.

### GetPartRevisionOk

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetPartRevisionOk() (*string, bool)`

GetPartRevisionOk returns a tuple with the PartRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartRevision

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) SetPartRevision(v string)`

SetPartRevision sets PartRevision field to given value.

### HasPartRevision

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) HasPartRevision() bool`

HasPartRevision returns a boolean if a field has been set.

### GetPartNumberRevision

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetPartNumberRevision() string`

GetPartNumberRevision returns the PartNumberRevision field if non-nil, zero value otherwise.

### GetPartNumberRevisionOk

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetPartNumberRevisionOk() (*string, bool)`

GetPartNumberRevisionOk returns a tuple with the PartNumberRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumberRevision

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) SetPartNumberRevision(v string)`

SetPartNumberRevision sets PartNumberRevision field to given value.

### HasPartNumberRevision

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) HasPartNumberRevision() bool`

HasPartNumberRevision returns a boolean if a field has been set.

### GetPoShipTo

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetPoShipTo() string`

GetPoShipTo returns the PoShipTo field if non-nil, zero value otherwise.

### GetPoShipToOk

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetPoShipToOk() (*string, bool)`

GetPoShipToOk returns a tuple with the PoShipTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoShipTo

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) SetPoShipTo(v string)`

SetPoShipTo sets PoShipTo field to given value.

### HasPoShipTo

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) HasPoShipTo() bool`

HasPoShipTo returns a boolean if a field has been set.

### GetBuildingCode

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetBuildingCode() string`

GetBuildingCode returns the BuildingCode field if non-nil, zero value otherwise.

### GetBuildingCodeOk

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetBuildingCodeOk() (*string, bool)`

GetBuildingCodeOk returns a tuple with the BuildingCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildingCode

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) SetBuildingCode(v string)`

SetBuildingCode sets BuildingCode field to given value.

### HasBuildingCode

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) HasBuildingCode() bool`

HasBuildingCode returns a boolean if a field has been set.

### GetBuildingId

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetBuildingId() string`

GetBuildingId returns the BuildingId field if non-nil, zero value otherwise.

### GetBuildingIdOk

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) GetBuildingIdOk() (*string, bool)`

GetBuildingIdOk returns a tuple with the BuildingId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildingId

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) SetBuildingId(v string)`

SetBuildingId sets BuildingId field to given value.

### HasBuildingId

`func (o *PurchaseOrderReleasesApiUpdateReleaseResponse) HasBuildingId() bool`

HasBuildingId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


