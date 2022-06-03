# The monitoring schema Schema

```txt
#/properties/monitoring#/properties/monitoring
```

The Monitoring settings

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [values.schema.json\*](values.schema.json "open original schema") |

## monitoring Type

`object` ([The monitoring schema](values-properties-the-monitoring-schema.md))

## monitoring Default Value

The default value is:

```json
{}
```

## monitoring Examples

```json
{
  "disable": []
}
```

# monitoring Properties

| Property            | Type    | Required | Nullable       | Defined by                                                                                                                                                                                               |
| :------------------ | :------ | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [disable](#disable) | `array` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-monitoring-schema-properties-the-disable-schema.md "#/properties/monitoring/properties/disable#/properties/monitoring/properties/disable") |

## disable

Set of resource names to disable monitoring for

`disable`

*   is optional

*   Type: `string[]`

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-monitoring-schema-properties-the-disable-schema.md "#/properties/monitoring/properties/disable#/properties/monitoring/properties/disable")

### disable Type

`string[]`

### disable Constraints

**unique items**: all items in this array must be unique. Duplicates are not allowed.

### disable Default Value

The default value is:

```json
[]
```

### disable Examples

```json
[]
```
