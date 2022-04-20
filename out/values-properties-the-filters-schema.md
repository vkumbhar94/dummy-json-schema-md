# The filters schema Schema

```txt
#/properties/filters#/properties/filters
```

Set of filter rules to exclude from adding into Logimonitor

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## filters Type

`string[]`

## filters Constraints

**unique items**: all items in this array must be unique. Duplicates are not allowed.

## filters Default Value

The default value is:

```json
[]
```

## filters Examples

```json
[
  "'!(type in (\"po\", (\"deploy\"), \"ep\"))'"
]
```

```json
[
  "'type == \"pod\" && [app.kubernetes.io/instance] != \"lm-container\""
]
```
