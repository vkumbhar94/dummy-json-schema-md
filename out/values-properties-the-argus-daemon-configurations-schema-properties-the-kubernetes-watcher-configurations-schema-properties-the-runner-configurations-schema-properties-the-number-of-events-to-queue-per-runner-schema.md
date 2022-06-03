# The Number of events to queue per runner schema Schema

```txt
#/properties/daemons/properties/watcher/properties/runner/properties/backPressureQueueSizePerRunner#/properties/daemons/properties/watcher/properties/runner/properties/backPressureQueueSizePerRunner
```

The Number of events to queue per runner

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## backPressureQueueSizePerRunner Type

`integer` ([The Number of events to queue per runner schema](values-properties-the-argus-daemon-configurations-schema-properties-the-kubernetes-watcher-configurations-schema-properties-the-runner-configurations-schema-properties-the-number-of-events-to-queue-per-runner-schema.md))

## backPressureQueueSizePerRunner Constraints

**minimum**: the value of this number must greater than or equal to: `1`

## backPressureQueueSizePerRunner Default Value

The default value is:

```json
10
```

## backPressureQueueSizePerRunner Examples

```json
10
```
