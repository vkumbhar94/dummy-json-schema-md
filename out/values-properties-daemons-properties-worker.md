# worker Schema

```txt
#/properties/daemons/properties/worker#/properties/daemons/properties/worker
```

Worker configurations

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## worker Type

`object` ([worker](values-properties-daemons-properties-worker.md))

## worker Default Value

The default value is:

```json
{}
```

## worker Examples

```json
{
  "poolSize": 10
}
```

# worker Properties

| Property              | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                              |
| :-------------------- | :-------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [poolSize](#poolsize) | `integer` | Optional | cannot be null | [The root schema](values-properties-daemons-properties-worker-properties-the-poolsize-schema.md "#/properties/daemons/properties/worker/properties/poolSize#/properties/daemons/properties/worker/properties/poolSize") |

## poolSize

number of workers in a pool

`poolSize`

*   is optional

*   Type: `integer` ([The poolSize schema](values-properties-daemons-properties-worker-properties-the-poolsize-schema.md))

*   cannot be null

*   defined in: [The root schema](values-properties-daemons-properties-worker-properties-the-poolsize-schema.md "#/properties/daemons/properties/worker/properties/poolSize#/properties/daemons/properties/worker/properties/poolSize")

### poolSize Type

`integer` ([The poolSize schema](values-properties-daemons-properties-worker-properties-the-poolsize-schema.md))

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
