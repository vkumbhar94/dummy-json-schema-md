# The resourceContainerID schema Schema

```txt
#/properties/resourceContainerID#/properties/resourceContainerID
```

The resourceContainerID is recommended to when Argus is being installed with non-admin user credentials.
The resourceContainerID is A parent resource group id that will hold all cluster resources under it.

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
