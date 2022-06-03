# Log Schema

```txt
#/properties/log#/properties/log
```

The Argus Log Configurations Schema

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [values.schema.json\*](values.schema.json "open original schema") |

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

| Property        | Type     | Required | Nullable       | Defined by                                                                                                                                                                       |
| :-------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [level](#level) | `string` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-log-properties-the-log-level-for-argus-schema.md "#/properties/log/properties/level#/properties/log/properties/level") |

## level

The Log Level for Argus

`level`

*   is optional

*   Type: `string` ([The Log Level for Argus Schema](values-properties-log-properties-the-log-level-for-argus-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-log-properties-the-log-level-for-argus-schema.md "#/properties/log/properties/level#/properties/log/properties/level")

### level Type

`string` ([The Log Level for Argus Schema](values-properties-log-properties-the-log-level-for-argus-schema.md))

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
