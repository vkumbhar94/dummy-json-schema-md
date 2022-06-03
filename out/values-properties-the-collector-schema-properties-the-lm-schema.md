# The lm schema Schema

```txt
#/properties/collector/properties/lm#/properties/collector/properties/lm
```

An explanation about the purpose of this instance.

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## lm Type

`object` ([The lm schema](values-properties-the-collector-schema-properties-the-lm-schema.md))

## lm Default Value

The default value is:

```json
{}
```

## lm Examples

```json
{
  "groupID": 0,
  "escalationChainID": 0
}
```

# lm Properties

| Property                                | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                               |
| :-------------------------------------- | :-------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [groupID](#groupid)                     | `integer` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-the-lm-schema-properties-the-groupid-schema.md "#/properties/collector/properties/lm/properties/groupID#/properties/collector/properties/lm/properties/groupID")                               |
| [escalationChainID](#escalationchainid) | `integer` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-the-lm-schema-properties-the-escalationchainid-schema.md "#/properties/collector/properties/lm/properties/escalationChainID#/properties/collector/properties/lm/properties/escalationChainID") |

## groupID

An explanation about the purpose of this instance.

`groupID`

*   is optional

*   Type: `integer` ([The groupID schema](values-properties-the-collector-schema-properties-the-lm-schema-properties-the-groupid-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-the-lm-schema-properties-the-groupid-schema.md "#/properties/collector/properties/lm/properties/groupID#/properties/collector/properties/lm/properties/groupID")

### groupID Type

`integer` ([The groupID schema](values-properties-the-collector-schema-properties-the-lm-schema-properties-the-groupid-schema.md))

### groupID Default Value

The default value is:

```json
1
```

### groupID Examples

```json
1
```

## escalationChainID

An explanation about the purpose of this instance.

`escalationChainID`

*   is optional

*   Type: `integer` ([The escalationChainID schema](values-properties-the-collector-schema-properties-the-lm-schema-properties-the-escalationchainid-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-the-lm-schema-properties-the-escalationchainid-schema.md "#/properties/collector/properties/lm/properties/escalationChainID#/properties/collector/properties/lm/properties/escalationChainID")

### escalationChainID Type

`integer` ([The escalationChainID schema](values-properties-the-collector-schema-properties-the-lm-schema-properties-the-escalationchainid-schema.md))

### escalationChainID Examples

```json
1
```
