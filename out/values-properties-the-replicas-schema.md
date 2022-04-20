# The replicas schema Schema

```txt
#/properties/replicas#/properties/replicas
```

Replicas - defaults to 1, param is just for development purpose, do not increase more than one replicas in production

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## replicas Type

`integer` ([The replicas schema](values-properties-the-replicas-schema.md))

## replicas Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

## replicas Default Value

The default value is:

```json
1
```

## replicas Examples

```json
1
```
