# Untitled integer in Logicmonitor Argus Helm Chart Values Schema Schema

```txt
http://logicmonitor.com/helm-charts/argus/values.schema.json#/definitions/toleration/oneOf/1/properties/tolerationSeconds
```

TolerationSeconds represents the period of time the toleration (which must be of effect NoExecute, otherwise this field is ignored) tolerates the taint. By default, it is not set, which means tolerate the taint forever (do not evict). Zero and negative values will be treated as 0 (evict immediately) by the system.

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## tolerationSeconds Type

`integer`

## tolerationSeconds Constraints

**unknown format**: the value of this string must follow the format: `int64`
