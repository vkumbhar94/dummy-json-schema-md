# The alerting schema Schema

```txt
#/properties/lm/properties/resource/properties/alerting#/properties/lm/properties/resource/properties/alerting
```

Alerting settings to apply on resource groups, only cluster scoped resources are valid here, other gets ignored

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## alerting Type

`object` ([The alerting schema](values-properties-the-lm-schema-properties-the-resource-schema-properties-the-alerting-schema.md))

## alerting Default Value

The default value is:

```json
{}
```

## alerting Examples

```json
{
  "disable": []
}
```

# alerting Properties

| Property            | Type    | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                               |
| :------------------ | :------ | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [disable](#disable) | `array` | Optional | cannot be null | [The root schema](values-properties-the-lm-schema-properties-the-resource-schema-properties-the-alerting-schema-properties-the-disable-schema.md "#/properties/lm/properties/resource/properties/alerting/properties/disable#/properties/lm/properties/resource/properties/alerting/properties/disable") |

## disable

Set of resources to disable alerting on

`disable`

*   is optional

*   Type: `string[]`

*   cannot be null

*   defined in: [The root schema](values-properties-the-lm-schema-properties-the-resource-schema-properties-the-alerting-schema-properties-the-disable-schema.md "#/properties/lm/properties/resource/properties/alerting/properties/disable#/properties/lm/properties/resource/properties/alerting/properties/disable")

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
