# Untitled object in Argus Helm Chart Configuration Schema Schema

```txt
#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/hostpath#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/hostPath
```

Represents a host path mapped into a pod. Host path volumes do not support ownership management or SELinux relabeling.

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## hostPath Type

`object` ([Details](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-hostpath.md))

# hostPath Properties

| Property      | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| :------------ | :------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [path](#path) | `string` | Required | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-hostpath-properties-path.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/hostpath/properties/path#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/hostPath/properties/path") |
| [type](#type) | `string` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-hostpath-properties-type.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/hostpath/properties/type#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/hostPath/properties/type") |

## path

Path of the directory on the host. If the path is a symlink, it will follow the link to the real path. More info: <https://kubernetes.io/docs/concepts/storage/volumes#hostpath>

`path`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-hostpath-properties-path.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/hostpath/properties/path#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/hostPath/properties/path")

### path Type

`string`

## type

Type for HostPath Volume Defaults to "" More info: <https://kubernetes.io/docs/concepts/storage/volumes#hostpath>

`type`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-hostpath-properties-type.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/hostpath/properties/type#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/hostPath/properties/type")

### type Type

`string`
