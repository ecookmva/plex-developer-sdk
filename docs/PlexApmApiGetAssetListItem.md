# PlexApmApiGetAssetListItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Enabled** | Pointer to **bool** | Returns true if the asset is currently marked as active | [optional] 
**AssetNames** | Pointer to **string** | Asset Names. | [optional] 
**AssetCodes** | Pointer to **string** | Asset Codes. | [optional] 
**AssetSerialNumber** | Pointer to **string** | The serial number of a physical asset | [optional] 
**AssetDescription** | Pointer to **string** | Descriptions | [optional] 
**GatewayName** | Pointer to **string** | Gateway Names | [optional] 
**GatewayId** | Pointer to **string** | GatewayIds | [optional] 
**FiixSiteName** | Pointer to **string** | Fiix Site Names | [optional] 
**FiixAssetName** | Pointer to **string** | Fiix Asset Names | [optional] 
**PlexMaintenanceEquipmentId** | Pointer to **string** | Plex Maintenance Equipment Ids | [optional] 
**BridgeAttributes** | Pointer to **string** | Asset Bridge Attribute Name | [optional] 
**Attributes** | Pointer to **string** | Asset Attribute Name | [optional] 

## Methods

### NewPlexApmApiGetAssetListItem

`func NewPlexApmApiGetAssetListItem() *PlexApmApiGetAssetListItem`

NewPlexApmApiGetAssetListItem instantiates a new PlexApmApiGetAssetListItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPlexApmApiGetAssetListItemWithDefaults

`func NewPlexApmApiGetAssetListItemWithDefaults() *PlexApmApiGetAssetListItem`

NewPlexApmApiGetAssetListItemWithDefaults instantiates a new PlexApmApiGetAssetListItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEnabled

`func (o *PlexApmApiGetAssetListItem) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *PlexApmApiGetAssetListItem) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *PlexApmApiGetAssetListItem) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *PlexApmApiGetAssetListItem) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetAssetNames

`func (o *PlexApmApiGetAssetListItem) GetAssetNames() string`

GetAssetNames returns the AssetNames field if non-nil, zero value otherwise.

### GetAssetNamesOk

`func (o *PlexApmApiGetAssetListItem) GetAssetNamesOk() (*string, bool)`

GetAssetNamesOk returns a tuple with the AssetNames field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetNames

`func (o *PlexApmApiGetAssetListItem) SetAssetNames(v string)`

SetAssetNames sets AssetNames field to given value.

### HasAssetNames

`func (o *PlexApmApiGetAssetListItem) HasAssetNames() bool`

HasAssetNames returns a boolean if a field has been set.

### GetAssetCodes

`func (o *PlexApmApiGetAssetListItem) GetAssetCodes() string`

GetAssetCodes returns the AssetCodes field if non-nil, zero value otherwise.

### GetAssetCodesOk

`func (o *PlexApmApiGetAssetListItem) GetAssetCodesOk() (*string, bool)`

GetAssetCodesOk returns a tuple with the AssetCodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetCodes

`func (o *PlexApmApiGetAssetListItem) SetAssetCodes(v string)`

SetAssetCodes sets AssetCodes field to given value.

### HasAssetCodes

`func (o *PlexApmApiGetAssetListItem) HasAssetCodes() bool`

HasAssetCodes returns a boolean if a field has been set.

### GetAssetSerialNumber

`func (o *PlexApmApiGetAssetListItem) GetAssetSerialNumber() string`

GetAssetSerialNumber returns the AssetSerialNumber field if non-nil, zero value otherwise.

### GetAssetSerialNumberOk

`func (o *PlexApmApiGetAssetListItem) GetAssetSerialNumberOk() (*string, bool)`

GetAssetSerialNumberOk returns a tuple with the AssetSerialNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetSerialNumber

`func (o *PlexApmApiGetAssetListItem) SetAssetSerialNumber(v string)`

SetAssetSerialNumber sets AssetSerialNumber field to given value.

### HasAssetSerialNumber

`func (o *PlexApmApiGetAssetListItem) HasAssetSerialNumber() bool`

HasAssetSerialNumber returns a boolean if a field has been set.

### GetAssetDescription

`func (o *PlexApmApiGetAssetListItem) GetAssetDescription() string`

GetAssetDescription returns the AssetDescription field if non-nil, zero value otherwise.

### GetAssetDescriptionOk

`func (o *PlexApmApiGetAssetListItem) GetAssetDescriptionOk() (*string, bool)`

GetAssetDescriptionOk returns a tuple with the AssetDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetDescription

`func (o *PlexApmApiGetAssetListItem) SetAssetDescription(v string)`

SetAssetDescription sets AssetDescription field to given value.

### HasAssetDescription

`func (o *PlexApmApiGetAssetListItem) HasAssetDescription() bool`

HasAssetDescription returns a boolean if a field has been set.

### GetGatewayName

`func (o *PlexApmApiGetAssetListItem) GetGatewayName() string`

GetGatewayName returns the GatewayName field if non-nil, zero value otherwise.

### GetGatewayNameOk

`func (o *PlexApmApiGetAssetListItem) GetGatewayNameOk() (*string, bool)`

GetGatewayNameOk returns a tuple with the GatewayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGatewayName

`func (o *PlexApmApiGetAssetListItem) SetGatewayName(v string)`

SetGatewayName sets GatewayName field to given value.

### HasGatewayName

`func (o *PlexApmApiGetAssetListItem) HasGatewayName() bool`

HasGatewayName returns a boolean if a field has been set.

### GetGatewayId

`func (o *PlexApmApiGetAssetListItem) GetGatewayId() string`

GetGatewayId returns the GatewayId field if non-nil, zero value otherwise.

### GetGatewayIdOk

`func (o *PlexApmApiGetAssetListItem) GetGatewayIdOk() (*string, bool)`

GetGatewayIdOk returns a tuple with the GatewayId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGatewayId

`func (o *PlexApmApiGetAssetListItem) SetGatewayId(v string)`

SetGatewayId sets GatewayId field to given value.

### HasGatewayId

`func (o *PlexApmApiGetAssetListItem) HasGatewayId() bool`

HasGatewayId returns a boolean if a field has been set.

### GetFiixSiteName

`func (o *PlexApmApiGetAssetListItem) GetFiixSiteName() string`

GetFiixSiteName returns the FiixSiteName field if non-nil, zero value otherwise.

### GetFiixSiteNameOk

`func (o *PlexApmApiGetAssetListItem) GetFiixSiteNameOk() (*string, bool)`

GetFiixSiteNameOk returns a tuple with the FiixSiteName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFiixSiteName

`func (o *PlexApmApiGetAssetListItem) SetFiixSiteName(v string)`

SetFiixSiteName sets FiixSiteName field to given value.

### HasFiixSiteName

`func (o *PlexApmApiGetAssetListItem) HasFiixSiteName() bool`

HasFiixSiteName returns a boolean if a field has been set.

### GetFiixAssetName

`func (o *PlexApmApiGetAssetListItem) GetFiixAssetName() string`

GetFiixAssetName returns the FiixAssetName field if non-nil, zero value otherwise.

### GetFiixAssetNameOk

`func (o *PlexApmApiGetAssetListItem) GetFiixAssetNameOk() (*string, bool)`

GetFiixAssetNameOk returns a tuple with the FiixAssetName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFiixAssetName

`func (o *PlexApmApiGetAssetListItem) SetFiixAssetName(v string)`

SetFiixAssetName sets FiixAssetName field to given value.

### HasFiixAssetName

`func (o *PlexApmApiGetAssetListItem) HasFiixAssetName() bool`

HasFiixAssetName returns a boolean if a field has been set.

### GetPlexMaintenanceEquipmentId

`func (o *PlexApmApiGetAssetListItem) GetPlexMaintenanceEquipmentId() string`

GetPlexMaintenanceEquipmentId returns the PlexMaintenanceEquipmentId field if non-nil, zero value otherwise.

### GetPlexMaintenanceEquipmentIdOk

`func (o *PlexApmApiGetAssetListItem) GetPlexMaintenanceEquipmentIdOk() (*string, bool)`

GetPlexMaintenanceEquipmentIdOk returns a tuple with the PlexMaintenanceEquipmentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlexMaintenanceEquipmentId

`func (o *PlexApmApiGetAssetListItem) SetPlexMaintenanceEquipmentId(v string)`

SetPlexMaintenanceEquipmentId sets PlexMaintenanceEquipmentId field to given value.

### HasPlexMaintenanceEquipmentId

`func (o *PlexApmApiGetAssetListItem) HasPlexMaintenanceEquipmentId() bool`

HasPlexMaintenanceEquipmentId returns a boolean if a field has been set.

### GetBridgeAttributes

`func (o *PlexApmApiGetAssetListItem) GetBridgeAttributes() string`

GetBridgeAttributes returns the BridgeAttributes field if non-nil, zero value otherwise.

### GetBridgeAttributesOk

`func (o *PlexApmApiGetAssetListItem) GetBridgeAttributesOk() (*string, bool)`

GetBridgeAttributesOk returns a tuple with the BridgeAttributes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBridgeAttributes

`func (o *PlexApmApiGetAssetListItem) SetBridgeAttributes(v string)`

SetBridgeAttributes sets BridgeAttributes field to given value.

### HasBridgeAttributes

`func (o *PlexApmApiGetAssetListItem) HasBridgeAttributes() bool`

HasBridgeAttributes returns a boolean if a field has been set.

### GetAttributes

`func (o *PlexApmApiGetAssetListItem) GetAttributes() string`

GetAttributes returns the Attributes field if non-nil, zero value otherwise.

### GetAttributesOk

`func (o *PlexApmApiGetAssetListItem) GetAttributesOk() (*string, bool)`

GetAttributesOk returns a tuple with the Attributes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttributes

`func (o *PlexApmApiGetAssetListItem) SetAttributes(v string)`

SetAttributes sets Attributes field to given value.

### HasAttributes

`func (o *PlexApmApiGetAssetListItem) HasAttributes() bool`

HasAttributes returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


