# Untitled undefined type in Argus Helm Chart Configuration Schema Schema

```txt
#/properties/collector/properties/probe/properties/startup#/properties/collector/properties/probe/properties/startup
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [values.schema.json\*](values.schema.json "open original schema") |

## startup Type

unknown

# startup Properties

| Property                              | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                        |
| :------------------------------------ | :-------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [failureThreshold](#failurethreshold) | `integer` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-probe-properties-startup-properties-failurethreshold.md "#/properties/collector/properties/probe/properties/startup/properties/failureThreshold#/properties/collector/properties/probe/properties/startup/properties/failureThreshold") |
| [periodSeconds](#periodseconds)       | `integer` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-probe-properties-startup-properties-periodseconds.md "#/properties/collector/properties/probe/properties/startup/properties/periodSeconds#/properties/collector/properties/probe/properties/startup/properties/periodSeconds")          |

## failureThreshold

The failureThreshold is maximum count before marking container start failed, typically collector installation time affects the argus startup

`failureThreshold`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-probe-properties-startup-properties-failurethreshold.md "#/properties/collector/properties/probe/properties/startup/properties/failureThreshold#/properties/collector/properties/probe/properties/startup/properties/failureThreshold")

### failureThreshold Type

`integer`

### failureThreshold Constraints

**minimum**: the value of this number must greater than or equal to: `1`

### failureThreshold Default Value

The default value is:

```json
20
```

## periodSeconds

How often (in seconds) to perform the probe. Default to 10 seconds. Minimum value is 1.

`periodSeconds`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-probe-properties-startup-properties-periodseconds.md "#/properties/collector/properties/probe/properties/startup/properties/periodSeconds#/properties/collector/properties/probe/properties/startup/properties/periodSeconds")

### periodSeconds Type

`integer`

### periodSeconds Constraints

**minimum**: the value of this number must greater than or equal to: `1`

### periodSeconds Default Value

The default value is:

```json
30
```
