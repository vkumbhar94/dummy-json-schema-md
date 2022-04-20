# Untitled object in The root schema Schema

```txt
http://example.com/example.json#/definitions/toleration/oneOf/1
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## 1 Type

`object` ([Details](values-definitions-toleration-oneof-1.md))

# 1 Properties

| Property                                | Type      | Required | Nullable       | Defined by                                                                                                                                                                              |
| :-------------------------------------- | :-------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [effect](#effect)                       | `string`  | Optional | cannot be null | [The root schema](values-definitions-toleration-oneof-1-properties-effect.md "http://example.com/example.json#/definitions/toleration/oneOf/1/properties/effect")                       |
| [key](#key)                             | `string`  | Optional | cannot be null | [The root schema](values-definitions-toleration-oneof-1-properties-key.md "http://example.com/example.json#/definitions/toleration/oneOf/1/properties/key")                             |
| [operator](#operator)                   | `string`  | Optional | cannot be null | [The root schema](values-definitions-toleration-oneof-1-properties-operator.md "http://example.com/example.json#/definitions/toleration/oneOf/1/properties/operator")                   |
| [tolerationSeconds](#tolerationseconds) | `integer` | Optional | cannot be null | [The root schema](values-definitions-toleration-oneof-1-properties-tolerationseconds.md "http://example.com/example.json#/definitions/toleration/oneOf/1/properties/tolerationSeconds") |
| [value](#value)                         | `string`  | Optional | cannot be null | [The root schema](values-definitions-toleration-oneof-1-properties-value.md "http://example.com/example.json#/definitions/toleration/oneOf/1/properties/value")                         |

## effect

Effect indicates the taint effect to match. Empty means match all taint effects. When specified, allowed values are NoSchedule, PreferNoSchedule and NoExecute.

`effect`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [The root schema](values-definitions-toleration-oneof-1-properties-effect.md "http://example.com/example.json#/definitions/toleration/oneOf/1/properties/effect")

### effect Type

`string`

## key

Key is the taint key that the toleration applies to. Empty means match all taint keys. If the key is empty, operator must be Exists; this combination means to match all values and all keys.

`key`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [The root schema](values-definitions-toleration-oneof-1-properties-key.md "http://example.com/example.json#/definitions/toleration/oneOf/1/properties/key")

### key Type

`string`

## operator

Operator represents a key's relationship to the value. Valid operators are Exists and Equal. Defaults to Equal. Exists is equivalent to wildcard for value, so that a pod can tolerate all taints of a particular category.

`operator`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [The root schema](values-definitions-toleration-oneof-1-properties-operator.md "http://example.com/example.json#/definitions/toleration/oneOf/1/properties/operator")

### operator Type

`string`

### operator Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value     | Explanation |
| :-------- | :---------- |
| `"Equal"` |             |

## tolerationSeconds

TolerationSeconds represents the period of time the toleration (which must be of effect NoExecute, otherwise this field is ignored) tolerates the taint. By default, it is not set, which means tolerate the taint forever (do not evict). Zero and negative values will be treated as 0 (evict immediately) by the system.

`tolerationSeconds`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [The root schema](values-definitions-toleration-oneof-1-properties-tolerationseconds.md "http://example.com/example.json#/definitions/toleration/oneOf/1/properties/tolerationSeconds")

### tolerationSeconds Type

`integer`

### tolerationSeconds Constraints

**unknown format**: the value of this string must follow the format: `int64`

## value

Value is the taint value the toleration matches to. If the operator is Exists, the value should be empty, otherwise just a regular string.

`value`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [The root schema](values-definitions-toleration-oneof-1-properties-value.md "http://example.com/example.json#/definitions/toleration/oneOf/1/properties/value")

### value Type

`string`

### value Constraints

**minimum length**: the minimum number of characters for this string is: `1`
