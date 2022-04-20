# The collectors schema Schema

```txt
#/properties/kube-state-metrics/properties/collectors#/properties/kube-state-metrics/properties/collectors
```

An explanation about the purpose of this instance.

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## collectors Type

an array of merged types ([Details](values-properties-the-kube-state-metrics-schema-properties-the-collectors-schema-items.md))

## collectors Constraints

**unique items**: all items in this array must be unique. Duplicates are not allowed.

## collectors Default Value

The default value is:

```json
[]
```

## collectors Examples

```json
[
  "daemonsets",
  "replicasets"
]
```
