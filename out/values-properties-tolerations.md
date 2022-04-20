# tolerations Schema

```txt
#/properties/tolerations#/properties/tolerations
```

tolerations are applied to pods, and allow the pods to schedule onto nodes with matching taints.

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## tolerations Type

unknown\[]

## tolerations Constraints

**unique items**: all items in this array must be unique. Duplicates are not allowed.

## tolerations Default Value

The default value is:

```json
[]
```

## tolerations Examples

```json
[]
```
