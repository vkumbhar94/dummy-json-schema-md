# The profiling schema Schema

```txt
#/properties/debug/properties/profiling#/properties/debug/properties/profiling
```

Profile generation configurations

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## profiling Type

`object` ([The profiling schema](values-properties-the-debug-schema-properties-the-profiling-schema.md))

## profiling Default Value

The default value is:

```json
{}
```

## profiling Examples

```json
{
  "enable": false
}
```

# profiling Properties

| Property          | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                                       |
| :---------------- | :-------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [enable](#enable) | `boolean` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-debug-schema-properties-the-profiling-schema-properties-the-enable-schema.md "#/properties/debug/properties/profiling/properties/enable#/properties/debug/properties/profiling/properties/enable") |

## enable

Setting this to true start application profile generations

`enable`

*   is optional

*   Type: `boolean` ([The enable schema](values-properties-the-debug-schema-properties-the-profiling-schema-properties-the-enable-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-debug-schema-properties-the-profiling-schema-properties-the-enable-schema.md "#/properties/debug/properties/profiling/properties/enable#/properties/debug/properties/profiling/properties/enable")

### enable Type

`boolean` ([The enable schema](values-properties-the-debug-schema-properties-the-profiling-schema-properties-the-enable-schema.md))

### enable Examples

```json
false
```
