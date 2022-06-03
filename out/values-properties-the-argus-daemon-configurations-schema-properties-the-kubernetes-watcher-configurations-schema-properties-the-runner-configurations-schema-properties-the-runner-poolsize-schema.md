# The Runner poolSize schema Schema

```txt
#/properties/daemons/properties/watcher/properties/runner/properties/poolSize#/properties/daemons/properties/watcher/properties/runner/properties/poolSize
```

The Number runners in a pool

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## poolSize Type

`integer` ([The Runner poolSize schema](values-properties-the-argus-daemon-configurations-schema-properties-the-kubernetes-watcher-configurations-schema-properties-the-runner-configurations-schema-properties-the-runner-poolsize-schema.md))

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
