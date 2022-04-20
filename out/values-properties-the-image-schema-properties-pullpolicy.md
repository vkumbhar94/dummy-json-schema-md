# pullPolicy Schema

```txt
#/properties/image/properties/pullPolicy#/properties/image/properties/pullPolicy
```

Overrides the image tag whose default is the chart appVersion.

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## pullPolicy Type

`string` ([pullPolicy](values-properties-the-image-schema-properties-pullpolicy.md))

## pullPolicy Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value            | Explanation |
| :--------------- | :---------- |
| `"Always"`       |             |
| `"IfNotPresent"` |             |
| `"Never"`        |             |
| `""`             |             |

## pullPolicy Default Value

The default value is:

```json
"Always"
```

## pullPolicy Examples

```json
"Always"
```
