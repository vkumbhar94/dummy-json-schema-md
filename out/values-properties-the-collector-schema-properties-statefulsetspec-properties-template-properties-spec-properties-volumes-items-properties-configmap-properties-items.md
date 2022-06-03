# Untitled array in Argus Helm Chart Configuration Schema Schema

```txt
#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/items#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/configMap/properties/items
```

If unspecified, each key-value pair in the Data field of the referenced ConfigMap will be projected into the volume as a file whose name is the key and content is the value. If specified, the listed keys will be projected into the specified paths, and unlisted keys will not be present. If a key is specified which is not present in the ConfigMap, the volume setup will error unless it is marked optional. Paths must be relative and may not contain the '..' path or start with '..'.

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## items Type

`object[]` ([Details](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-configmap-properties-items-items.md))
