# The alerting schema Schema

```txt
#/properties/lm/properties/resource/properties/alerting#/properties/lm/properties/resource/properties/alerting
```

Alerting settings to apply on resource groups.
Only cluster scoped resources are valid here.
Namespace scoped resources will get ignored if set any.

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## alerting Type

`object` ([The alerting schema](values-properties-the-logicmonitor-portal-configurations-properties-the-resource-schema-properties-the-alerting-schema.md))

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

| Property            | Type    | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                              |
| :------------------ | :------ | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [disable](#disable) | `array` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-logicmonitor-portal-configurations-properties-the-resource-schema-properties-the-alerting-schema-properties-the-disable-schema.md "#/properties/lm/properties/resource/properties/alerting/properties/disable#/properties/lm/properties/resource/properties/alerting/properties/disable") |

## disable

Set of resources to set disable upon resource groups.
Only cluster scoped resources are valid here.
Namespace scoped resources will get ignored if set any.

`disable`

*   is optional

*   Type: `string[]`

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-logicmonitor-portal-configurations-properties-the-resource-schema-properties-the-alerting-schema-properties-the-disable-schema.md "#/properties/lm/properties/resource/properties/alerting/properties/disable#/properties/lm/properties/resource/properties/alerting/properties/disable")

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
