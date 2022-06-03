# The debug schema Schema

```txt
#/properties/debug#/properties/debug
```

The Application debugging configurations

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [values.schema.json\*](values.schema.json "open original schema") |

## debug Type

`object` ([The debug schema](values-properties-the-debug-schema.md))

## debug Default Value

The default value is:

```json
{}
```

## debug Examples

```json
{
  "profiling": {
    "enable": false
  }
}
```

# debug Properties

| Property                | Type     | Required | Nullable       | Defined by                                                                                                                                                                                      |
| :---------------------- | :------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [profiling](#profiling) | `object` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-debug-schema-properties-the-profiling-schema.md "#/properties/debug/properties/profiling#/properties/debug/properties/profiling") |

## profiling

Profile generation configurations

`profiling`

*   is optional

*   Type: `object` ([The profiling schema](values-properties-the-debug-schema-properties-the-profiling-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-debug-schema-properties-the-profiling-schema.md "#/properties/debug/properties/profiling#/properties/debug/properties/profiling")

### profiling Type

`object` ([The profiling schema](values-properties-the-debug-schema-properties-the-profiling-schema.md))

### profiling Default Value

The default value is:

```json
{}
```

### profiling Examples

```json
{
  "enable": false
}
```
