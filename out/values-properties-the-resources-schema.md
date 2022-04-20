# The resources schema Schema

```txt
#/properties/resources#/properties/resources
```

resources are Pod resource limits

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## resources Type

`object` ([The resources schema](values-properties-the-resources-schema.md))

## resources Default Value

The default value is:

```json
{}
```

## resources Examples

```json
{
  "limits": {
    "cpu": "1000m",
    "memory": "1Gi",
    "ephemeral-storage": "100Mi"
  },
  "requests": {
    "cpu": "1000m",
    "memory": "1Gi",
    "ephemeral-storage": "100Mi"
  }
}
```

# resources Properties

| Property              | Type     | Required | Nullable       | Defined by                                                                                                                                                                                          |
| :-------------------- | :------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [limits](#limits)     | `object` | Optional | cannot be null | [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-resources-schema-properties-limits.md "#/properties/resources/properties/limits#/properties/resources/properties/limits")       |
| [requests](#requests) | `object` | Optional | cannot be null | [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-resources-schema-properties-requests.md "#/properties/resources/properties/requests#/properties/resources/properties/requests") |

## limits

Limits describes the maximum amount of compute resources allowed. More info: <https://kubernetes.io/docs/concepts/configuration/manage-compute-resources-container/>

`limits`

*   is optional

*   Type: `object` ([Details](values-properties-the-resources-schema-properties-limits.md))

*   cannot be null

*   defined in: [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-resources-schema-properties-limits.md "#/properties/resources/properties/limits#/properties/resources/properties/limits")

### limits Type

`object` ([Details](values-properties-the-resources-schema-properties-limits.md))

## requests

Requests describes the minimum amount of compute resources required. If Requests is omitted for a container, it defaults to Limits if that is explicitly specified, otherwise to an implementation-defined value. More info: <https://kubernetes.io/docs/concepts/configuration/manage-compute-resources-container/>

`requests`

*   is optional

*   Type: `object` ([Details](values-properties-the-resources-schema-properties-requests.md))

*   cannot be null

*   defined in: [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-resources-schema-properties-requests.md "#/properties/resources/properties/requests#/properties/resources/properties/requests")

### requests Type

`object` ([Details](values-properties-the-resources-schema-properties-requests.md))
