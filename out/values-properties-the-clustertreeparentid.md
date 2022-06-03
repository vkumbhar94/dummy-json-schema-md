# The clusterTreeParentID Schema

```txt
#/properties/clusterTreeParentID#/properties/clusterTreeParentID
```

clusterTreeParentID is a parent static resource group ID underneath the organised kubernetes resource tree gets created.
A static resource group with the mentioned ID should exit beforehand.

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## clusterTreeParentID Type

`integer` ([The clusterTreeParentID](values-properties-the-clustertreeparentid.md))

## clusterTreeParentID Constraints

**minimum**: the value of this number must greater than or equal to: `1`

## clusterTreeParentID Default Value

The default value is:

```json
1
```

## clusterTreeParentID Examples

```json
1
```
