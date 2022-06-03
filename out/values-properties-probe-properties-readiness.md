# Untitled undefined type in Argus Helm Chart Configuration Schema Schema

```txt
#/properties/probe/properties/readiness#/properties/probe/properties/readiness
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [values.schema.json\*](values.schema.json "open original schema") |

## readiness Type

unknown

# readiness Properties

| Property                              | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                                    |
| :------------------------------------ | :-------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [failureThreshold](#failurethreshold) | `integer` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-probe-properties-readiness-properties-failurethreshold.md "#/properties/probe/properties/readiness/properties/failureThreshold#/properties/probe/properties/readiness/properties/failureThreshold") |
| [periodSeconds](#periodseconds)       | `integer` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-probe-properties-readiness-properties-periodseconds.md "#/properties/probe/properties/readiness/properties/periodSeconds#/properties/probe/properties/readiness/properties/periodSeconds")          |

## failureThreshold

The failureThreshold is maximum count before marking container start failed, typically collector installation time affects the argus startup

`failureThreshold`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-probe-properties-readiness-properties-failurethreshold.md "#/properties/probe/properties/readiness/properties/failureThreshold#/properties/probe/properties/readiness/properties/failureThreshold")

### failureThreshold Type

`integer`

### failureThreshold Constraints

**minimum**: the value of this number must greater than or equal to: `1`

### failureThreshold Default Value

The default value is:

```json
3
```

## periodSeconds

How often (in seconds) to perform the probe. Default to 10 seconds. Minimum value is 1.

`periodSeconds`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-probe-properties-readiness-properties-periodseconds.md "#/properties/probe/properties/readiness/properties/periodSeconds#/properties/probe/properties/readiness/properties/periodSeconds")

### periodSeconds Type

`integer`

### periodSeconds Constraints

**minimum**: the value of this number must greater than or equal to: `1`

### periodSeconds Default Value

The default value is:

```json
10
```
