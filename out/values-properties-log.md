# Log Schema

```txt
#/properties/log#/properties/log
```

Log Configurations

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## log Type

`object` ([Log](values-properties-log.md))

## log Default Value

The default value is:

```json
{}
```

## log Examples

```json
{
  "level": "info"
}
```

# log Properties

| Property        | Type     | Required | Nullable       | Defined by                                                                                                                           |
| :-------------- | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------- |
| [level](#level) | `string` | Optional | cannot be null | [The root schema](values-properties-log-properties-loglevel.md "#/properties/log/properties/level#/properties/log/properties/level") |

## level

Log Level

`level`

*   is optional

*   Type: `string` ([log.level](values-properties-log-properties-loglevel.md))

*   cannot be null

*   defined in: [The root schema](values-properties-log-properties-loglevel.md "#/properties/log/properties/level#/properties/log/properties/level")

### level Type

`string` ([log.level](values-properties-log-properties-loglevel.md))

### level Constraints

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

### level Default Value

The default value is:

```json
"info"
```

### level Examples

```json
"info"
```
