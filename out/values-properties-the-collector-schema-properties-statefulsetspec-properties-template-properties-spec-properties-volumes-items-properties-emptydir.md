# Untitled object in Argus Helm Chart Configuration Schema Schema

```txt
#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/emptydir#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/emptyDir
```

Represents an empty directory for a pod. Empty directory volumes support ownership management and SELinux relabeling.

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## emptyDir Type

`object` ([Details](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-emptydir.md))

# emptyDir Properties

| Property                | Type          | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| :---------------------- | :------------ | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [medium](#medium)       | `string`      | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-emptydir-properties-medium.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/emptydir/properties/medium#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/emptyDir/properties/medium")          |
| [sizeLimit](#sizelimit) | Not specified | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-emptydir-properties-sizelimit.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/emptydir/properties/sizelimit#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/emptyDir/properties/sizeLimit") |

## medium

What type of storage medium should back this directory. The default is "" which means to use the node's default medium. Must be an empty string (default) or Memory. More info: <https://kubernetes.io/docs/concepts/storage/volumes#emptydir>

`medium`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-emptydir-properties-medium.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/emptydir/properties/medium#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/emptyDir/properties/medium")

### medium Type

`string`

## sizeLimit

Total amount of local storage required for this EmptyDir volume. The size limit is also applicable for memory medium. The maximum usage on memory medium EmptyDir would be the minimum value between the SizeLimit specified here and the sum of memory limits of all containers in a pod. The default is nil which means that the limit is undefined. More info: <https://kubernetes.io/docs/user-guide/volumes#emptydir>

`sizeLimit`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-emptydir-properties-sizelimit.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/emptydir/properties/sizelimit#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/emptyDir/properties/sizeLimit")

### sizeLimit Type

unknown
