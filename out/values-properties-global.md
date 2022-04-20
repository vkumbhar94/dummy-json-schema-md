# Untitled object in Logicmonitor Argus Helm Chart Values Schema Schema

```txt
#/properties/global#/properties/global
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## global Type

`object` ([Details](values-properties-global.md))

# global Properties

| Property                                                        | Type     | Required | Nullable       | Defined by                                                                                                                                                                                            |
| :-------------------------------------------------------------- | :------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [imagePullSecrets](#imagepullsecrets)                           | `array`  | Optional | cannot be null | [Logicmonitor Argus Helm Chart Values Schema](values-properties-global-properties-imagepullsecrets.md "#/properties/global#/properties/global/properties/imagePullSecrets")                           |
| [image](#image)                                                 | `object` | Optional | cannot be null | [Logicmonitor Argus Helm Chart Values Schema](values-properties-global-properties-the-image-schema.md "#/properties/global/properties/image#/properties/global/properties/image")                     |
| [proxy](#proxy)                                                 | `object` | Optional | cannot be null | [Logicmonitor Argus Helm Chart Values Schema](values-properties-global-properties-proxy.md "#/properties/proxy#/properties/global/properties/proxy")                                                  |
| [collectorsetServiceNameSuffix](#collectorsetservicenamesuffix) | `string` | Optional | cannot be null | [Logicmonitor Argus Helm Chart Values Schema](values-properties-global-properties-collectorsetservicenamesuffix.md "#/properties/global#/properties/global/properties/collectorsetServiceNameSuffix") |
| Additional Properties                                           | Any      | Optional | can be null    |                                                                                                                                                                                                       |

## imagePullSecrets

ImagePullSecrets is an optional list of references to secrets in the same namespace to use for pulling any of the images used by this PodSpec. If specified, these secrets will be passed to individual puller implementations for them to use. For example, in the case of docker, only DockerConfig type secrets are honored. More info: <https://kubernetes.io/docs/concepts/containers/images#specifying-imagepullsecrets-on-a-pod>

`imagePullSecrets`

*   is optional

*   Type: unknown\[]

*   cannot be null

*   defined in: [Logicmonitor Argus Helm Chart Values Schema](values-properties-global-properties-imagepullsecrets.md "#/properties/global#/properties/global/properties/imagePullSecrets")

### imagePullSecrets Type

unknown\[]

### imagePullSecrets Examples

```json
[
  {
    "name": "imagepullsecret1"
  }
]
```

## image

An explanation about the purpose of this instance.

`image`

*   is optional

*   Type: `object` ([The image schema](values-properties-global-properties-the-image-schema.md))

*   cannot be null

*   defined in: [Logicmonitor Argus Helm Chart Values Schema](values-properties-global-properties-the-image-schema.md "#/properties/global/properties/image#/properties/global/properties/image")

### image Type

`object` ([The image schema](values-properties-global-properties-the-image-schema.md))

### image Default Value

The default value is:

```json
{}
```

### image Examples

```json
{
  "pullPolicy": "Always"
}
```

## proxy

Http/s proxy

`proxy`

*   is optional

*   Type: `object` ([proxy](values-properties-global-properties-proxy.md))

*   cannot be null

*   defined in: [Logicmonitor Argus Helm Chart Values Schema](values-properties-global-properties-proxy.md "#/properties/proxy#/properties/global/properties/proxy")

### proxy Type

`object` ([proxy](values-properties-global-properties-proxy.md))

### proxy Default Value

The default value is:

```json
{}
```

### proxy Examples

```json
{
  "url": "",
  "user": "",
  "pass": ""
}
```

## collectorsetServiceNameSuffix

Suffix to be added to .Release.name to generate Collectorset controller service URL.
Keep it empty while installing this chart individually, umbrella chart uses this to generate unique name across

`collectorsetServiceNameSuffix`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Logicmonitor Argus Helm Chart Values Schema](values-properties-global-properties-collectorsetservicenamesuffix.md "#/properties/global#/properties/global/properties/collectorsetServiceNameSuffix")

### collectorsetServiceNameSuffix Type

`string`

## Additional Properties

Additional properties are allowed and do not have to follow a specific schema
