# The Log Level for Argus Schema Schema

```txt
#/properties/log/properties/level#/properties/log/properties/level
```

The Log Level for Argus

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## level Type

`string` ([The Log Level for Argus Schema](values-properties-log-properties-the-log-level-for-argus-schema.md))

## level Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value       | Explanation |
| :---------- | :---------- |
| `"info"`    |             |
| `"warn"`    |             |
| `"warning"` |             |
| `"debug"`   |             |
| `"trace"`   |             |
| `"error"`   |             |
| `"fatal"`   |             |
| `"panic"`   |             |

## level Default Value

The default value is:

```json
"info"
```

## level Examples

```json
"info"
```
