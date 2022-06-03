# Untitled string in Argus Helm Chart Configuration Schema Schema

```txt
#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/restartpolicy#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/restartPolicy
```

Restart policy for all containers within the pod. One of Always, OnFailure, Never. Default to Always. More info: <https://kubernetes.io/docs/concepts/workloads/pods/pod-lifecycle/#restart-policy>

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## restartPolicy Type

`string`
