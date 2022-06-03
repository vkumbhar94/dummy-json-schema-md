# The kube-state-metrics schema Schema

```txt
#/properties/kube-state-metrics#/properties/kube-state-metrics
```

An explanation about the purpose of this instance.

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## kube-state-metrics Type

`object` ([The kube-state-metrics schema](values-properties-the-kube-state-metrics-schema.md))

## kube-state-metrics Default Value

The default value is:

```json
{}
```

## kube-state-metrics Examples

```json
{
  "enabled": true,
  "replicas": 1,
  "collectors": [
    "daemonsets",
    "replicasets",
    "statefulsets",
    "persistentvolumes"
  ]
}
```

# kube-state-metrics Properties

| Property                                      | Type          | Required | Nullable       | Defined by                                                                                                                                                                                                                                |
| :-------------------------------------------- | :------------ | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [enabled](#enabled)                           | `boolean`     | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-kube-state-metrics-schema-properties-the-enabled-schema.md "#/properties/kube-state-metrics/properties/enabled#/properties/kube-state-metrics/properties/enabled")          |
| [replicas](#replicas)                         | `integer`     | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-kube-state-metrics-schema-properties-the-replicas-schema.md "#/properties/kube-state-metrics/properties/replicas#/properties/kube-state-metrics/properties/replicas")       |
| [collectors](#collectors)                     | `array`       | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-kube-state-metrics-schema-properties-the-collectors-schema.md "#/properties/kube-state-metrics/properties/collectors#/properties/kube-state-metrics/properties/collectors") |
| [additionalProperties](#additionalproperties) | Not specified | Optional | cannot be null | [Untitled schema](undefined.md "undefined#undefined")                                                                                                                                                                                     |

## enabled

An explanation about the purpose of this instance.

`enabled`

*   is optional

*   Type: `boolean` ([The enabled schema](values-properties-the-kube-state-metrics-schema-properties-the-enabled-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-kube-state-metrics-schema-properties-the-enabled-schema.md "#/properties/kube-state-metrics/properties/enabled#/properties/kube-state-metrics/properties/enabled")

### enabled Type

`boolean` ([The enabled schema](values-properties-the-kube-state-metrics-schema-properties-the-enabled-schema.md))

### enabled Examples

```json
true
```

## replicas

An explanation about the purpose of this instance.

`replicas`

*   is optional

*   Type: `integer` ([The replicas schema](values-properties-the-kube-state-metrics-schema-properties-the-replicas-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-kube-state-metrics-schema-properties-the-replicas-schema.md "#/properties/kube-state-metrics/properties/replicas#/properties/kube-state-metrics/properties/replicas")

### replicas Type

`integer` ([The replicas schema](values-properties-the-kube-state-metrics-schema-properties-the-replicas-schema.md))

### replicas Constraints

**minimum**: the value of this number must greater than or equal to: `0`

### replicas Default Value

The default value is:

```json
1
```

### replicas Examples

```json
1
```

## collectors

An explanation about the purpose of this instance.

`collectors`

*   is optional

*   Type: an array of merged types ([Details](values-properties-the-kube-state-metrics-schema-properties-the-collectors-schema-items.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-kube-state-metrics-schema-properties-the-collectors-schema.md "#/properties/kube-state-metrics/properties/collectors#/properties/kube-state-metrics/properties/collectors")

### collectors Type

an array of merged types ([Details](values-properties-the-kube-state-metrics-schema-properties-the-collectors-schema-items.md))

### collectors Constraints

**unique items**: all items in this array must be unique. Duplicates are not allowed.

### collectors Default Value

The default value is:

```json
[]
```

### collectors Examples

```json
[
  "daemonsets",
  "replicasets"
]
```

## additionalProperties

no description

`additionalProperties`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Untitled schema](undefined.md "undefined#undefined")

### Untitled schema Type

unknown
