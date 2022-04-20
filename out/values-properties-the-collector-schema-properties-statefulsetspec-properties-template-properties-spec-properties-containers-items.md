# Untitled object in The root schema Schema

```txt
#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/containers/items#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/containers/items
```

A single application container that you want to run within a pod.

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## items Type

`object` ([Details](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-containers-items.md))

# items Properties

| Property                | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                                                                                                             |
| :---------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [name](#name)           | `string` | Required | cannot be null | [The root schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-containers-items-properties-name.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/containers/items#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/containers/items/properties/name")           |
| [resources](#resources) | `object` | Optional | cannot be null | [The root schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-containers-items-properties-resources.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/containers/items#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/containers/items/properties/resources") |

## name



`name`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [The root schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-containers-items-properties-name.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/containers/items#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/containers/items/properties/name")

### name Type

`string`

### name Constraints

**minimum length**: the minimum number of characters for this string is: `1`

## resources

Compute Resources required by this container. Cannot be updated. More info: <https://kubernetes.io/docs/concepts/configuration/manage-compute-resources-container/>

`resources`

*   is optional

*   Type: `object` ([Details](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-containers-items-properties-resources.md))

*   cannot be null

*   defined in: [The root schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-containers-items-properties-resources.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/containers/items#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/containers/items/properties/resources")

### resources Type

`object` ([Details](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-containers-items-properties-resources.md))
