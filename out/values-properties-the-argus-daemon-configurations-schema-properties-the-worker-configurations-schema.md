# The Worker configurations Schema Schema

```txt
#/properties/daemons/properties/worker#/properties/daemons/properties/worker
```

The Worker configurations

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [values.schema.json\*](values.schema.json "open original schema") |

## worker Type

`object` ([The Worker configurations Schema](values-properties-the-argus-daemon-configurations-schema-properties-the-worker-configurations-schema.md))

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

| Property              | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                    |
| :-------------------- | :-------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [poolSize](#poolsize) | `integer` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-argus-daemon-configurations-schema-properties-the-worker-configurations-schema-properties-the-worker-poolsize-schema.md "#/properties/daemons/properties/worker/properties/poolSize#/properties/daemons/properties/worker/properties/poolSize") |

## poolSize

The Number of workers in a pool

`poolSize`

*   is optional

*   Type: `integer` ([The Worker poolSize schema](values-properties-the-argus-daemon-configurations-schema-properties-the-worker-configurations-schema-properties-the-worker-poolsize-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-argus-daemon-configurations-schema-properties-the-worker-configurations-schema-properties-the-worker-poolsize-schema.md "#/properties/daemons/properties/worker/properties/poolSize#/properties/daemons/properties/worker/properties/poolSize")

### poolSize Type

`integer` ([The Worker poolSize schema](values-properties-the-argus-daemon-configurations-schema-properties-the-worker-configurations-schema-properties-the-worker-poolsize-schema.md))

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
