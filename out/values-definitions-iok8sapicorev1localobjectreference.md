# Untitled object in Argus Helm Chart Configuration Schema Schema

```txt
http://example.com/example.json#/definitions/io.k8s.api.core.v1.LocalObjectReference
```

LocalObjectReference contains enough information to let you locate the referenced object inside the same namespace.

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## io.k8s.api.core.v1.LocalObjectReference Type

`object` ([Details](values-definitions-iok8sapicorev1localobjectreference.md))

# io.k8s.api.core.v1.LocalObjectReference Properties

| Property      | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                               |
| :------------ | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [name](#name) | `string` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-definitions-iok8sapicorev1localobjectreference-properties-name.md "http://example.com/example.json#/definitions/io.k8s.api.core.v1.LocalObjectReference/properties/name") |

## name

Name of the referent. More info: <https://kubernetes.io/docs/concepts/overview/working-with-objects/names/#names>

`name`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-definitions-iok8sapicorev1localobjectreference-properties-name.md "http://example.com/example.json#/definitions/io.k8s.api.core.v1.LocalObjectReference/properties/name")

### name Type

`string`
