# The collector schema Schema

```txt
#/properties/collector#/properties/collector
```

An explanation about the purpose of this instance.

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [values.schema.json\*](values.schema.json "open original schema") |

## collector Type

`object` ([The collector schema](values-properties-the-collector-schema.md))

## collector Default Value

The default value is:

```json
{}
```

## collector Examples

```json
{
  "replicas": 1,
  "version": 0,
  "size": "small",
  "useEA": false,
  "lm": {
    "groupID": 0,
    "escalationChainID": 0
  },
  "image": {
    "repository": "logicmonitor/collector",
    "tag": "latest",
    "pullPolicy": ""
  },
  "proxy": {
    "url": "",
    "user": "",
    "pass": ""
  },
  "annotations": {},
  "labels": {},
  "statefulsetSpec": {
    "template": {
      "spec": {
        "nodeSelector": {},
        "tolerations": [],
        "priorityClassName": ""
      }
    }
  }
}
```

# collector Properties

| Property                            | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                         |
| :---------------------------------- | :-------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [replicas](#replicas)               | `integer` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-the-replicas-schema.md "#/properties/collector/properties/replicas#/properties/collector/properties/replicas")           |
| [version](#version)                 | `integer` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-the-version-schema.md "#/properties/collector/properties/version#/properties/collector/properties/version")              |
| [size](#size)                       | `string`  | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-the-size-schema.md "#/properties/collector/properties/size#/properties/collector/properties/size")                       |
| [useEA](#useea)                     | `boolean` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-the-useea-schema.md "#/properties/collector/properties/useEA#/properties/collector/properties/useEA")                    |
| [lm](#lm)                           | `object`  | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-the-lm-schema.md "#/properties/collector/properties/lm#/properties/collector/properties/lm")                             |
| [image](#image)                     | `object`  | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-the-image-schema.md "#/properties/collector/properties/image#/properties/collector/properties/image")                    |
| [proxy](#proxy)                     | `object`  | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-the-proxy-schema.md "#/properties/collector/properties/proxy#/properties/collector/properties/proxy")                    |
| [annotations](#annotations)         | `object`  | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-the-annotations-schema.md "#/properties/collector/properties/annotations#/properties/collector/properties/annotations")  |
| [labels](#labels)                   | `object`  | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-the-labels-schema.md "#/properties/collector/properties/labels#/properties/collector/properties/labels")                 |
| [statefulsetSpec](#statefulsetspec) | `object`  | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-statefulsetspec.md "#/properties/collector/properties/statefulsetspec#/properties/collector/properties/statefulsetSpec") |
| [probe](#probe)                     | `object`  | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-probe.md "#/properties/collector/properties/probe#/properties/collector/properties/probe")                               |

## replicas

An explanation about the purpose of this instance.

`replicas`

*   is optional

*   Type: `integer` ([The replicas schema](values-properties-the-collector-schema-properties-the-replicas-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-the-replicas-schema.md "#/properties/collector/properties/replicas#/properties/collector/properties/replicas")

### replicas Type

`integer` ([The replicas schema](values-properties-the-collector-schema-properties-the-replicas-schema.md))

### replicas Constraints

**minimum**: the value of this number must greater than or equal to: `1`

### replicas Default Value

The default value is:

```json
1
```

### replicas Examples

```json
1
```

## version

An explanation about the purpose of this instance.

`version`

*   is optional

*   Type: `integer` ([The version schema](values-properties-the-collector-schema-properties-the-version-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-the-version-schema.md "#/properties/collector/properties/version#/properties/collector/properties/version")

### version Type

`integer` ([The version schema](values-properties-the-collector-schema-properties-the-version-schema.md))

### version Examples

```json
20101
```

## size

An explanation about the purpose of this instance.

`size`

*   is optional

*   Type: `string` ([The size schema](values-properties-the-collector-schema-properties-the-size-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-the-size-schema.md "#/properties/collector/properties/size#/properties/collector/properties/size")

### size Type

`string` ([The size schema](values-properties-the-collector-schema-properties-the-size-schema.md))

### size Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                  | Explanation |
| :--------------------- | :---------- |
| `"nano"`               |             |
| `"small"`              |             |
| `"medium"`             |             |
| `"large"`              |             |
| `"extra_large"`        |             |
| `"double_extra_large"` |             |

### size Examples

```json
"small"
```

## useEA

An explanation about the purpose of this instance.

`useEA`

*   is optional

*   Type: `boolean` ([The useEA schema](values-properties-the-collector-schema-properties-the-useea-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-the-useea-schema.md "#/properties/collector/properties/useEA#/properties/collector/properties/useEA")

### useEA Type

`boolean` ([The useEA schema](values-properties-the-collector-schema-properties-the-useea-schema.md))

### useEA Examples

```json
false
```

## lm

An explanation about the purpose of this instance.

`lm`

*   is optional

*   Type: `object` ([The lm schema](values-properties-the-collector-schema-properties-the-lm-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-the-lm-schema.md "#/properties/collector/properties/lm#/properties/collector/properties/lm")

### lm Type

`object` ([The lm schema](values-properties-the-collector-schema-properties-the-lm-schema.md))

### lm Default Value

The default value is:

```json
{}
```

### lm Examples

```json
{
  "groupID": 0,
  "escalationChainID": 0
}
```

## image

An explanation about the purpose of this instance.

`image`

*   is optional

*   Type: `object` ([The image schema](values-properties-the-collector-schema-properties-the-image-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-the-image-schema.md "#/properties/collector/properties/image#/properties/collector/properties/image")

### image Type

`object` ([The image schema](values-properties-the-collector-schema-properties-the-image-schema.md))

### image Default Value

The default value is:

```json
{}
```

### image Examples

```json
{
  "registry": "",
  "repository": "logicmonitor/collector",
  "tag": "latest",
  "pullPolicy": ""
}
```

## proxy

An explanation about the purpose of this instance.

`proxy`

*   is optional

*   Type: `object` ([The proxy schema](values-properties-the-collector-schema-properties-the-proxy-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-the-proxy-schema.md "#/properties/collector/properties/proxy#/properties/collector/properties/proxy")

### proxy Type

`object` ([The proxy schema](values-properties-the-collector-schema-properties-the-proxy-schema.md))

### proxy Default Value

The default value is:

```json
{}
```

### proxy Examples

```json
{
  "url": "",
  "user": "",
  "pass": ""
}
```

## annotations

An explanation about the purpose of this instance.

`annotations`

*   is optional

*   Type: `object` ([The annotations schema](values-properties-the-collector-schema-properties-the-annotations-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-the-annotations-schema.md "#/properties/collector/properties/annotations#/properties/collector/properties/annotations")

### annotations Type

`object` ([The annotations schema](values-properties-the-collector-schema-properties-the-annotations-schema.md))

### annotations Default Value

The default value is:

```json
{}
```

### annotations Examples

```json
{}
```

## labels

An explanation about the purpose of this instance.

`labels`

*   is optional

*   Type: `object` ([The labels schema](values-properties-the-collector-schema-properties-the-labels-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-the-labels-schema.md "#/properties/collector/properties/labels#/properties/collector/properties/labels")

### labels Type

`object` ([The labels schema](values-properties-the-collector-schema-properties-the-labels-schema.md))

### labels Default Value

The default value is:

```json
{}
```

### labels Examples

```json
{}
```

## statefulsetSpec

The collector StatefulSet specification for customizations

`statefulsetSpec`

*   is optional

*   Type: `object` ([Details](values-properties-the-collector-schema-properties-statefulsetspec.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-statefulsetspec.md "#/properties/collector/properties/statefulsetspec#/properties/collector/properties/statefulsetSpec")

### statefulsetSpec Type

`object` ([Details](values-properties-the-collector-schema-properties-statefulsetspec.md))

## probe

The container probe configuration schema

`probe`

*   is optional

*   Type: `object` ([Details](values-properties-the-collector-schema-properties-probe.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-probe.md "#/properties/collector/properties/probe#/properties/collector/properties/probe")

### probe Type

`object` ([Details](values-properties-the-collector-schema-properties-probe.md))
