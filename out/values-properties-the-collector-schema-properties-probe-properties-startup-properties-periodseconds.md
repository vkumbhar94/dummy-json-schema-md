# Untitled integer in Argus Helm Chart Configuration Schema Schema

```txt
#/properties/collector/properties/probe/properties/startup/properties/periodSeconds#/properties/collector/properties/probe/properties/startup/properties/periodSeconds
```

How often (in seconds) to perform the probe. Default to 10 seconds. Minimum value is 1.

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## periodSeconds Type

`integer`

## periodSeconds Constraints

**minimum**: the value of this number must greater than or equal to: `1`

## periodSeconds Default Value

The default value is:

```json
30
```
