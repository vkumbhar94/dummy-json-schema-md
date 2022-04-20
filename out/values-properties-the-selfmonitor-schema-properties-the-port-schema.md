# The port schema Schema

```txt
#/properties/selfMonitor/properties/port#/properties/selfMonitor/properties/port
```

port number to expose self monitor "/metrics" endpoint

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## port Type

`integer` ([The port schema](values-properties-the-selfmonitor-schema-properties-the-port-schema.md))

## port Constraints

**minimum**: the value of this number must greater than or equal to: `2`

## port Default Value

The default value is:

```json
2112
```

## port Examples

```json
2112
```
