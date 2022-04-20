# Friendly Cluster Name Schema

```txt
#/properties/clusterName#/properties/clusterName
```

A unique name given to the cluster's resource group.
NOTE: do not change name once application deployed in cluster, breaks correlation at multiple places
example: Organised Resource group name of kubernetes resource tree generated as "Kubernetes Cluster: <clusterName>"

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## clusterName Type

`string` ([Friendly Cluster Name](values-properties-friendly-cluster-name.md))

## clusterName Examples

```json
""
```
