# Untitled object in Argus Helm Chart Configuration Schema Schema

```txt
#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/awselasticblockstore#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/awsElasticBlockStore
```

Represents a Persistent Disk resource in AWS.

An AWS EBS disk must exist before mounting to a container. The disk must also be in the same AWS zone as the kubelet. An AWS EBS disk can only be mounted as read/write once. AWS EBS volumes support ownership management and SELinux relabeling.

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## awsElasticBlockStore Type

`object` ([Details](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-awselasticblockstore.md))

# awsElasticBlockStore Properties

| Property                | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| :---------------------- | :-------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [fsType](#fstype)       | `string`  | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-awselasticblockstore-properties-fstype.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/awselasticblockstore/properties/fstype#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/awsElasticBlockStore/properties/fsType")          |
| [partition](#partition) | `integer` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-awselasticblockstore-properties-partition.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/awselasticblockstore/properties/partition#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/awsElasticBlockStore/properties/partition") |
| [readOnly](#readonly)   | `boolean` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-awselasticblockstore-properties-readonly.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/awselasticblockstore/properties/readonly#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/awsElasticBlockStore/properties/readOnly")    |
| [volumeID](#volumeid)   | `string`  | Required | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-awselasticblockstore-properties-volumeid.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/awselasticblockstore/properties/volumeid#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/awsElasticBlockStore/properties/volumeID")    |

## fsType

Filesystem type of the volume that you want to mount. Tip: Ensure that the filesystem type is supported by the host operating system. Examples: "ext4", "xfs", "ntfs". Implicitly inferred to be "ext4" if unspecified. More info: <https://kubernetes.io/docs/concepts/storage/volumes#awselasticblockstore>

`fsType`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-awselasticblockstore-properties-fstype.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/awselasticblockstore/properties/fstype#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/awsElasticBlockStore/properties/fsType")

### fsType Type

`string`

## partition

The partition in the volume that you want to mount. If omitted, the default is to mount by volume name. Examples: For volume /dev/sda1, you specify the partition as "1". Similarly, the volume partition for /dev/sda is "0" (or you can leave the property empty).

`partition`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-awselasticblockstore-properties-partition.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/awselasticblockstore/properties/partition#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/awsElasticBlockStore/properties/partition")

### partition Type

`integer`

### partition Constraints

**unknown format**: the value of this string must follow the format: `int32`

## readOnly

Specify "true" to force and set the ReadOnly property in VolumeMounts to "true". If omitted, the default is "false". More info: <https://kubernetes.io/docs/concepts/storage/volumes#awselasticblockstore>

`readOnly`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-awselasticblockstore-properties-readonly.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/awselasticblockstore/properties/readonly#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/awsElasticBlockStore/properties/readOnly")

### readOnly Type

`boolean`

## volumeID

Unique ID of the persistent disk resource in AWS (Amazon EBS volume). More info: <https://kubernetes.io/docs/concepts/storage/volumes#awselasticblockstore>

`volumeID`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-awselasticblockstore-properties-volumeid.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/awselasticblockstore/properties/volumeid#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/awsElasticBlockStore/properties/volumeID")

### volumeID Type

`string`
