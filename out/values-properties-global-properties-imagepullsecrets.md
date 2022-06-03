# Untitled array in Argus Helm Chart Configuration Schema Schema

```txt
#/properties/global#/properties/global/properties/imagePullSecrets
```

ImagePullSecrets is an optional list of references to secrets in the same namespace to use for pulling any of the images used by this PodSpec. If specified, these secrets will be passed to individual puller implementations for them to use. For example, in the case of docker, only DockerConfig type secrets are honored. More info: <https://kubernetes.io/docs/concepts/containers/images#specifying-imagepullsecrets-on-a-pod>

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## imagePullSecrets Type

unknown\[]

## imagePullSecrets Examples

```json
[
  {
    "name": "imagepullsecret1"
  }
]
```
