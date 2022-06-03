# Untitled boolean in Argus Helm Chart Configuration Schema Schema

```txt
#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/awselasticblockstore/properties/readonly#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/awsElasticBlockStore/properties/readOnly
```

Specify "true" to force and set the ReadOnly property in VolumeMounts to "true". If omitted, the default is "false". More info: <https://kubernetes.io/docs/concepts/storage/volumes#awselasticblockstore>

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## readOnly Type

`boolean`
