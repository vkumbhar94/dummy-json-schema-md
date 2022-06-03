# Untitled integer in Argus Helm Chart Configuration Schema Schema

```txt
#/properties/collector/properties/probe/properties/startup/properties/failureThreshold#/properties/collector/properties/probe/properties/startup/properties/failureThreshold
```

The failureThreshold is maximum count before marking container start failed, typically collector installation time affects the argus startup

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## failureThreshold Type

`integer`

## failureThreshold Constraints

**minimum**: the value of this number must greater than or equal to: `1`

## failureThreshold Default Value

The default value is:

```json
20
```
