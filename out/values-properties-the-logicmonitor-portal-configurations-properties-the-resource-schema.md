# The resource schema Schema

```txt
#/properties/lm/properties/resource#/properties/lm/properties/resource
```

An explanation about the purpose of this instance.

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [values.schema.json\*](values.schema.json "open original schema") |

## resource Type

`object` ([The resource schema](values-properties-the-logicmonitor-portal-configurations-properties-the-resource-schema.md))

## resource Default Value

The default value is:

```json
{}
```

## resource Examples

```json
{
  "globalDeleteAfterDuration": "P0DT0H0M0S",
  "alerting": {
    "disable": []
  }
}
```

# resource Properties

| Property                                                | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                             |
| :------------------------------------------------------ | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [globalDeleteAfterDuration](#globaldeleteafterduration) | `string` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-logicmonitor-portal-configurations-properties-the-resource-schema-properties-the-globaldeleteafterduration-schema.md "#/properties/lm/properties/resource/properties/globalDeleteAfterDuration#/properties/lm/properties/resource/properties/globalDeleteAfterDuration") |
| [alerting](#alerting)                                   | `object` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-logicmonitor-portal-configurations-properties-the-resource-schema-properties-the-alerting-schema.md "#/properties/lm/properties/resource/properties/alerting#/properties/lm/properties/resource/properties/alerting")                                                    |

## globalDeleteAfterDuration

Global scheduled delete duration to delete resources after, values must be in ISO8601 format

`globalDeleteAfterDuration`

*   is optional

*   Type: `string` ([The globalDeleteAfterDuration schema](values-properties-the-logicmonitor-portal-configurations-properties-the-resource-schema-properties-the-globaldeleteafterduration-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-logicmonitor-portal-configurations-properties-the-resource-schema-properties-the-globaldeleteafterduration-schema.md "#/properties/lm/properties/resource/properties/globalDeleteAfterDuration#/properties/lm/properties/resource/properties/globalDeleteAfterDuration")

### globalDeleteAfterDuration Type

`string` ([The globalDeleteAfterDuration schema](values-properties-the-logicmonitor-portal-configurations-properties-the-resource-schema-properties-the-globaldeleteafterduration-schema.md))

### globalDeleteAfterDuration Constraints

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^P(\d+Y)?(\d+M)?(\d+W)?(\d+D)?(T(\d+H)?(\d+M)?(\d+S)?)?$
```

[try pattern](https://regexr.com/?expression=%5EP\(%5Cd%2BY\)%3F\(%5Cd%2BM\)%3F\(%5Cd%2BW\)%3F\(%5Cd%2BD\)%3F\(T\(%5Cd%2BH\)%3F\(%5Cd%2BM\)%3F\(%5Cd%2BS\)%3F\)%3F%24 "try regular expression with regexr.com")

### globalDeleteAfterDuration Default Value

The default value is:

```json
"P0DT0H0M0S"
```

### globalDeleteAfterDuration Examples

```json
"P0DT0H0M0S"
```

## alerting

Alerting settings to apply on resource groups.
Only cluster scoped resources are valid here.
Namespace scoped resources will get ignored if set any.

`alerting`

*   is optional

*   Type: `object` ([The alerting schema](values-properties-the-logicmonitor-portal-configurations-properties-the-resource-schema-properties-the-alerting-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-logicmonitor-portal-configurations-properties-the-resource-schema-properties-the-alerting-schema.md "#/properties/lm/properties/resource/properties/alerting#/properties/lm/properties/resource/properties/alerting")

### alerting Type

`object` ([The alerting schema](values-properties-the-logicmonitor-portal-configurations-properties-the-resource-schema-properties-the-alerting-schema.md))

### alerting Default Value

The default value is:

```json
{}
```

### alerting Examples

```json
{
  "disable": []
}
```
