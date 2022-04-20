# The pullPolicy schema Schema

```txt
#/properties/collector/properties/image/properties/pullPolicy#/properties/collector/properties/image/properties/pullPolicy
```

An explanation about the purpose of this instance.

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## pullPolicy Type

`string` ([The pullPolicy schema](values-properties-the-collector-schema-properties-the-image-schema-properties-the-pullpolicy-schema.md))

## pullPolicy Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value            | Explanation |
| :--------------- | :---------- |
| `"Always"`       |             |
| `"IfNotPresent"` |             |
| `"Never"`        |             |
| `""`             |             |

## pullPolicy Examples

```json
""
```
