# The size schema Schema

```txt
#/properties/collector/properties/size#/properties/collector/properties/size
```

An explanation about the purpose of this instance.

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## size Type

`string` ([The size schema](values-properties-the-collector-schema-properties-the-size-schema.md))

## size Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                  | Explanation |
| :--------------------- | :---------- |
| `"nano"`               |             |
| `"small"`              |             |
| `"medium"`             |             |
| `"large"`              |             |
| `"extra_large"`        |             |
| `"double_extra_large"` |             |

## size Examples

```json
"small"
```
