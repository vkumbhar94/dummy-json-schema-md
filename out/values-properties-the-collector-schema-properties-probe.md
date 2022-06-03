# Untitled object in Argus Helm Chart Configuration Schema Schema

```txt
#/properties/collector/properties/probe#/properties/collector/properties/probe
```

The container probe configuration schema

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [values.schema.json\*](values.schema.json "open original schema") |

## probe Type

`object` ([Details](values-properties-the-collector-schema-properties-probe.md))

# probe Properties

| Property                | Type          | Required | Nullable       | Defined by                                                                                                                                                                                                                                          |
| :---------------------- | :------------ | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [enabled](#enabled)     | `boolean`     | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-probe-properties-enabled.md "#/properties/collector/properties/probe/properties/enabled#/properties/collector/properties/probe/properties/enabled")       |
| [startup](#startup)     | Not specified | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-probe-properties-startup.md "#/properties/collector/properties/probe/properties/startup#/properties/collector/properties/probe/properties/startup")       |
| [liveness](#liveness)   | Not specified | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-probe-properties-liveness.md "#/properties/collector/properties/probe/properties/liveness#/properties/collector/properties/probe/properties/liveness")    |
| [readiness](#readiness) | Not specified | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-probe-properties-readiness.md "#/properties/collector/properties/probe/properties/readiness#/properties/collector/properties/probe/properties/readiness") |

## enabled

Enables container probes

`enabled`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-probe-properties-enabled.md "#/properties/collector/properties/probe/properties/enabled#/properties/collector/properties/probe/properties/enabled")

### enabled Type

`boolean`

### enabled Default Value

The default value is:

```json
true
```

## startup



`startup`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-probe-properties-startup.md "#/properties/collector/properties/probe/properties/startup#/properties/collector/properties/probe/properties/startup")

### startup Type

unknown

## liveness



`liveness`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-probe-properties-liveness.md "#/properties/collector/properties/probe/properties/liveness#/properties/collector/properties/probe/properties/liveness")

### liveness Type

unknown

## readiness



`readiness`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-probe-properties-readiness.md "#/properties/collector/properties/probe/properties/readiness#/properties/collector/properties/probe/properties/readiness")

### readiness Type

unknown
