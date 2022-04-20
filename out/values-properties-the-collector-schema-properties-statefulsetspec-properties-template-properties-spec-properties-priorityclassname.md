# Untitled string in Logicmonitor Argus Helm Chart Values Schema Schema

```txt
#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/priorityclassname#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/priorityClassName
```

If specified, indicates the pod's priority. "system-node-critical" and "system-cluster-critical" are two special keywords which indicate the highest priorities with the former being the highest priority. Any other name must be defined by creating a PriorityClass object with that name. If not specified, the pod priority will be default or zero if there is no default.

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## priorityClassName Type

`string`
