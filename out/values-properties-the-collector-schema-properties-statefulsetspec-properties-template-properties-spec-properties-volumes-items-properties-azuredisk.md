# Untitled object in Logicmonitor Argus Helm Chart Values Schema Schema

```txt
#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/azuredisk#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/azureDisk
```

AzureDisk represents an Azure Data Disk mount on the host and bind mount to the pod.

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## azureDisk Type

`object` ([Details](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-azuredisk.md))

# azureDisk Properties

| Property                    | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| :-------------------------- | :-------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [cachingMode](#cachingmode) | `string`  | Optional | cannot be null | [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-azuredisk-properties-cachingmode.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/azuredisk/properties/cachingmode#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/azureDisk/properties/cachingMode") |
| [diskName](#diskname)       | `string`  | Required | cannot be null | [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-azuredisk-properties-diskname.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/azuredisk/properties/diskname#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/azureDisk/properties/diskName")          |
| [diskURI](#diskuri)         | `string`  | Required | cannot be null | [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-azuredisk-properties-diskuri.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/azuredisk/properties/diskuri#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/azureDisk/properties/diskURI")             |
| [fsType](#fstype)           | `string`  | Optional | cannot be null | [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-azuredisk-properties-fstype.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/azuredisk/properties/fstype#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/azureDisk/properties/fsType")                |
| [kind](#kind)               | `string`  | Optional | cannot be null | [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-azuredisk-properties-kind.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/azuredisk/properties/kind#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/azureDisk/properties/kind")                      |
| [readOnly](#readonly)       | `boolean` | Optional | cannot be null | [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-azuredisk-properties-readonly.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/azuredisk/properties/readonly#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/azureDisk/properties/readOnly")          |

## cachingMode

Host Caching mode: None, Read Only, Read Write.

`cachingMode`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-azuredisk-properties-cachingmode.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/azuredisk/properties/cachingmode#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/azureDisk/properties/cachingMode")

### cachingMode Type

`string`

## diskName

The Name of the data disk in the blob storage

`diskName`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-azuredisk-properties-diskname.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/azuredisk/properties/diskname#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/azureDisk/properties/diskName")

### diskName Type

`string`

## diskURI

The URI the data disk in the blob storage

`diskURI`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-azuredisk-properties-diskuri.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/azuredisk/properties/diskuri#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/azureDisk/properties/diskURI")

### diskURI Type

`string`

## fsType

Filesystem type to mount. Must be a filesystem type supported by the host operating system. Ex. "ext4", "xfs", "ntfs". Implicitly inferred to be "ext4" if unspecified.

`fsType`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-azuredisk-properties-fstype.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/azuredisk/properties/fstype#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/azureDisk/properties/fsType")

### fsType Type

`string`

## kind

Expected values Shared: multiple blob disks per storage account  Dedicated: single blob disk per storage account  Managed: azure managed data disk (only in managed availability set). defaults to shared

`kind`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-azuredisk-properties-kind.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/azuredisk/properties/kind#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/azureDisk/properties/kind")

### kind Type

`string`

## readOnly

Defaults to false (read/write). ReadOnly here will force the ReadOnly setting in VolumeMounts.

`readOnly`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-azuredisk-properties-readonly.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/azuredisk/properties/readonly#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/azureDisk/properties/readOnly")

### readOnly Type

`boolean`
