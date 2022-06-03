# The Worker poolSize schema Schema

```txt
#/properties/daemons/properties/worker/properties/poolSize#/properties/daemons/properties/worker/properties/poolSize
```

The Number of workers in a pool

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## poolSize Type

`integer` ([The Worker poolSize schema](values-properties-the-argus-daemon-configurations-schema-properties-the-worker-configurations-schema-properties-the-worker-poolsize-schema.md))

## poolSize Constraints

**minimum**: the value of this number must greater than or equal to: `1`

## poolSize Default Value

The default value is:

```json
10
```

## poolSize Examples

```json
10
```
