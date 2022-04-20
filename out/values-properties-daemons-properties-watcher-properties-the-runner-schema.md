# The runner schema Schema

```txt
#/properties/daemons/properties/watcher/properties/runner#/properties/daemons/properties/watcher/properties/runner
```

configurations for parallel runners to process watcher events

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## runner Type

`object` ([The runner schema](values-properties-daemons-properties-watcher-properties-the-runner-schema.md))

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

| Property                                                          | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                                                                |
| :---------------------------------------------------------------- | :-------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [poolSize](#poolsize)                                             | `integer` | Optional | cannot be null | [Logicmonitor Argus Helm Chart Values Schema](values-properties-daemons-properties-watcher-properties-the-runner-schema-properties-the-poolsize-schema.md "#/properties/daemons/properties/watcher/properties/runner/properties/poolSize#/properties/daemons/properties/watcher/properties/runner/properties/poolSize")                                                                   |
| [backPressureQueueSizePerRunner](#backpressurequeuesizeperrunner) | `integer` | Optional | cannot be null | [Logicmonitor Argus Helm Chart Values Schema](values-properties-daemons-properties-watcher-properties-the-runner-schema-properties-the-backpressurequeuesizeperrunner-schema.md "#/properties/daemons/properties/watcher/properties/runner/properties/backPressureQueueSizePerRunner#/properties/daemons/properties/watcher/properties/runner/properties/backPressureQueueSizePerRunner") |

## poolSize

Number of runner in a pool

`poolSize`

*   is optional

*   Type: `integer` ([The poolSize schema](values-properties-daemons-properties-watcher-properties-the-runner-schema-properties-the-poolsize-schema.md))

*   cannot be null

*   defined in: [Logicmonitor Argus Helm Chart Values Schema](values-properties-daemons-properties-watcher-properties-the-runner-schema-properties-the-poolsize-schema.md "#/properties/daemons/properties/watcher/properties/runner/properties/poolSize#/properties/daemons/properties/watcher/properties/runner/properties/poolSize")

### poolSize Type

`integer` ([The poolSize schema](values-properties-daemons-properties-watcher-properties-the-runner-schema-properties-the-poolsize-schema.md))

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

Number of events to queue per runner

`backPressureQueueSizePerRunner`

*   is optional

*   Type: `integer` ([The backPressureQueueSizePerRunner schema](values-properties-daemons-properties-watcher-properties-the-runner-schema-properties-the-backpressurequeuesizeperrunner-schema.md))

*   cannot be null

*   defined in: [Logicmonitor Argus Helm Chart Values Schema](values-properties-daemons-properties-watcher-properties-the-runner-schema-properties-the-backpressurequeuesizeperrunner-schema.md "#/properties/daemons/properties/watcher/properties/runner/properties/backPressureQueueSizePerRunner#/properties/daemons/properties/watcher/properties/runner/properties/backPressureQueueSizePerRunner")

### backPressureQueueSizePerRunner Type

`integer` ([The backPressureQueueSizePerRunner schema](values-properties-daemons-properties-watcher-properties-the-runner-schema-properties-the-backpressurequeuesizeperrunner-schema.md))

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
