# The resourceContainerID schema Schema

```txt
#/properties/resourceContainerID#/properties/resourceContainerID
```

A parent group id that will hold all cluster resources under it. This is useful when Argus is installed with non-admin user's token.

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## resourceContainerID Type

`integer` ([The resourceContainerID schema](values-properties-the-resourcecontainerid-schema.md))

## resourceContainerID Constraints

**minimum**: the value of this number must greater than or equal to: `1`

## resourceContainerID Default Value

The default value is:

```json
1
```

## resourceContainerID Examples

```json
1
```
