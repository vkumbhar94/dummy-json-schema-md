# The selfMonitor schema Schema

```txt
#/properties/selfMonitor#/properties/selfMonitor
```

Configurations to expose self monitor metrics in Openmetrics format

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## selfMonitor Type

`object` ([The selfMonitor schema](values-properties-the-selfmonitor-schema.md))

## selfMonitor Default Value

The default value is:

```json
{}
```

## selfMonitor Examples

```json
{
  "enable": false,
  "port": 2112
}
```

# selfMonitor Properties

| Property          | Type      | Required | Nullable       | Defined by                                                                                                                                                                         |
| :---------------- | :-------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [enable](#enable) | `boolean` | Optional | cannot be null | [The root schema](values-properties-the-selfmonitor-schema-properties-the-enable-schema.md "#/properties/selfMonitor/properties/enable#/properties/selfMonitor/properties/enable") |
| [port](#port)     | `integer` | Optional | cannot be null | [The root schema](values-properties-the-selfmonitor-schema-properties-the-port-schema.md "#/properties/selfMonitor/properties/port#/properties/selfMonitor/properties/port")       |

## enable

Setting this to true starts exposing self monitor metrics

`enable`

*   is optional

*   Type: `boolean` ([The enable schema](values-properties-the-selfmonitor-schema-properties-the-enable-schema.md))

*   cannot be null

*   defined in: [The root schema](values-properties-the-selfmonitor-schema-properties-the-enable-schema.md "#/properties/selfMonitor/properties/enable#/properties/selfMonitor/properties/enable")

### enable Type

`boolean` ([The enable schema](values-properties-the-selfmonitor-schema-properties-the-enable-schema.md))

### enable Examples

```json
false
```

## port

port number to expose self monitor "/metrics" endpoint

`port`

*   is optional

*   Type: `integer` ([The port schema](values-properties-the-selfmonitor-schema-properties-the-port-schema.md))

*   cannot be null

*   defined in: [The root schema](values-properties-the-selfmonitor-schema-properties-the-port-schema.md "#/properties/selfMonitor/properties/port#/properties/selfMonitor/properties/port")

### port Type

`integer` ([The port schema](values-properties-the-selfmonitor-schema-properties-the-port-schema.md))

### port Constraints

**minimum**: the value of this number must greater than or equal to: `2`

### port Default Value

The default value is:

```json
2112
```

### port Examples

```json
2112
```
