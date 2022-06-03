# Untitled object in Argus Helm Chart Configuration Schema Schema

```txt
#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/configmap/items/items#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/configMap/properties/items/items
```

Maps a string key to a path within a volume.

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## items Type

`object` ([Details](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-configmap-properties-items-items.md))

# items Properties

| Property      | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| :------------ | :-------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [key](#key)   | `string`  | Required | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-configmap-properties-items-items-properties-key.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/configmap/items/items/properties/key#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/configMap/properties/items/items/properties/key")    |
| [mode](#mode) | `integer` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-configmap-properties-items-items-properties-mode.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/configmap/items/items/properties/mode#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/configMap/properties/items/items/properties/mode") |
| [path](#path) | `string`  | Required | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-configmap-properties-items-items-properties-path.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/configmap/items/items/properties/path#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/configMap/properties/items/items/properties/path") |

## key

The key to project.

`key`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-configmap-properties-items-items-properties-key.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/configmap/items/items/properties/key#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/configMap/properties/items/items/properties/key")

### key Type

`string`

## mode

Optional: mode bits to use on this file, must be a value between 0 and 0777. If not specified, the volume defaultMode will be used. This might be in conflict with other options that affect the file mode, like fsGroup, and the result can be other mode bits set.

`mode`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-configmap-properties-items-items-properties-mode.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/configmap/items/items/properties/mode#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/configMap/properties/items/items/properties/mode")

### mode Type

`integer`

### mode Constraints

**unknown format**: the value of this string must follow the format: `int32`

## path

The relative path of the file to map the key to. May not be an absolute path. May not contain the path element '..'. May not start with the string '..'.

`path`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-configmap-properties-items-items-properties-path.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/configmap/items/items/properties/path#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/configMap/properties/items/items/properties/path")

### path Type

`string`
