# The disable schema Schema

```txt
#/properties/lm/properties/resource/properties/alerting/properties/disable#/properties/lm/properties/resource/properties/alerting/properties/disable
```

Set of resources to set disable upon resource groups.
Only cluster scoped resources are valid here.
Namespace scoped resources will get ignored if set any.

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## disable Type

`string[]`

## disable Constraints

**unique items**: all items in this array must be unique. Duplicates are not allowed.

## disable Default Value

The default value is:

```json
[]
```

## disable Examples

```json
[]
```
