# The runner configurations schema Schema

```txt
#/properties/daemons/properties/watcher/properties/runner#/properties/daemons/properties/watcher/properties/runner
```

The configurations for parallel runners to process watcher events

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## runner Type

`object` ([The runner configurations schema](values-properties-the-argus-daemon-configurations-schema-properties-the-kubernetes-watcher-configurations-schema-properties-the-runner-configurations-schema.md))

## runner Default Value

The default value is:

```json
{}
```

## runner Examples

```json
{
  "poolSize": 10,
  "backPressureQueueSizePerRunner": 10
}
```

# runner Properties

| Property                                                          | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| :---------------------------------------------------------------- | :-------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [poolSize](#poolsize)                                             | `integer` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-argus-daemon-configurations-schema-properties-the-kubernetes-watcher-configurations-schema-properties-the-runner-configurations-schema-properties-the-runner-poolsize-schema.md "#/properties/daemons/properties/watcher/properties/runner/properties/poolSize#/properties/daemons/properties/watcher/properties/runner/properties/poolSize")                                                                  |
| [backPressureQueueSizePerRunner](#backpressurequeuesizeperrunner) | `integer` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-argus-daemon-configurations-schema-properties-the-kubernetes-watcher-configurations-schema-properties-the-runner-configurations-schema-properties-the-number-of-events-to-queue-per-runner-schema.md "#/properties/daemons/properties/watcher/properties/runner/properties/backPressureQueueSizePerRunner#/properties/daemons/properties/watcher/properties/runner/properties/backPressureQueueSizePerRunner") |

## poolSize

The Number runners in a pool

`poolSize`

*   is optional

*   Type: `integer` ([The Runner poolSize schema](values-properties-the-argus-daemon-configurations-schema-properties-the-kubernetes-watcher-configurations-schema-properties-the-runner-configurations-schema-properties-the-runner-poolsize-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-argus-daemon-configurations-schema-properties-the-kubernetes-watcher-configurations-schema-properties-the-runner-configurations-schema-properties-the-runner-poolsize-schema.md "#/properties/daemons/properties/watcher/properties/runner/properties/poolSize#/properties/daemons/properties/watcher/properties/runner/properties/poolSize")

### poolSize Type

`integer` ([The Runner poolSize schema](values-properties-the-argus-daemon-configurations-schema-properties-the-kubernetes-watcher-configurations-schema-properties-the-runner-configurations-schema-properties-the-runner-poolsize-schema.md))

### poolSize Constraints

**minimum**: the value of this number must greater than or equal to: `1`

### poolSize Default Value

The default value is:

```json
10
```

### poolSize Examples

```json
10
```

## backPressureQueueSizePerRunner

The Number of events to queue per runner

`backPressureQueueSizePerRunner`

*   is optional

*   Type: `integer` ([The Number of events to queue per runner schema](values-properties-the-argus-daemon-configurations-schema-properties-the-kubernetes-watcher-configurations-schema-properties-the-runner-configurations-schema-properties-the-number-of-events-to-queue-per-runner-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-argus-daemon-configurations-schema-properties-the-kubernetes-watcher-configurations-schema-properties-the-runner-configurations-schema-properties-the-number-of-events-to-queue-per-runner-schema.md "#/properties/daemons/properties/watcher/properties/runner/properties/backPressureQueueSizePerRunner#/properties/daemons/properties/watcher/properties/runner/properties/backPressureQueueSizePerRunner")

### backPressureQueueSizePerRunner Type

`integer` ([The Number of events to queue per runner schema](values-properties-the-argus-daemon-configurations-schema-properties-the-kubernetes-watcher-configurations-schema-properties-the-runner-configurations-schema-properties-the-number-of-events-to-queue-per-runner-schema.md))

### backPressureQueueSizePerRunner Constraints

**minimum**: the value of this number must greater than or equal to: `1`

### backPressureQueueSizePerRunner Default Value

The default value is:

```json
10
```

### backPressureQueueSizePerRunner Examples

```json
10
```
