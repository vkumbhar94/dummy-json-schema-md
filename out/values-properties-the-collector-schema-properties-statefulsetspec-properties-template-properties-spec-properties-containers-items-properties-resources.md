# Untitled object in Argus Helm Chart Configuration Schema Schema

```txt
#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/containers/items#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/containers/items/properties/resources
```

Compute Resources required by this container. Cannot be updated. More info: <https://kubernetes.io/docs/concepts/configuration/manage-compute-resources-container/>

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## resources Type

`object` ([Details](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-containers-items-properties-resources.md))

# resources Properties

| Property              | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| :-------------------- | :------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [limits](#limits)     | `object` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-containers-items-properties-resources-properties-limits.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/containers/items#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/containers/items/properties/resources/properties/limits")     |
| [requests](#requests) | `object` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-containers-items-properties-resources-properties-requests.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/containers/items#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/containers/items/properties/resources/properties/requests") |

## limits

Limits describes the maximum amount of compute resources allowed. More info: <https://kubernetes.io/docs/concepts/configuration/manage-compute-resources-container/>

`limits`

*   is optional

*   Type: `object` ([Details](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-containers-items-properties-resources-properties-limits.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-containers-items-properties-resources-properties-limits.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/containers/items#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/containers/items/properties/resources/properties/limits")

### limits Type

`object` ([Details](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-containers-items-properties-resources-properties-limits.md))

## requests

Requests describes the minimum amount of compute resources required. If Requests is omitted for a container, it defaults to Limits if that is explicitly specified, otherwise to an implementation-defined value. More info: <https://kubernetes.io/docs/concepts/configuration/manage-compute-resources-container/>

`requests`

*   is optional

*   Type: `object` ([Details](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-containers-items-properties-resources-properties-requests.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-containers-items-properties-resources-properties-requests.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/containers/items#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/containers/items/properties/resources/properties/requests")

### requests Type

`object` ([Details](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-containers-items-properties-resources-properties-requests.md))
