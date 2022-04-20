# Untitled integer in The root schema Schema

```txt
#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/priority#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/priority
```

The priority value. Various system components use this field to find the priority of the pod. When Priority Admission Controller is enabled, it prevents users from setting this field. The admission controller populates this field from PriorityClassName. The higher the value, the higher the priority.

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## priority Type

`integer`

## priority Constraints

**unknown format**: the value of this string must follow the format: `int32`
