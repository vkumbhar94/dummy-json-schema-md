# The image schema Schema

```txt
#/properties/collector/properties/image#/properties/collector/properties/image
```

An explanation about the purpose of this instance.

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [values.schema.json\*](values.schema.json "open original schema") |

## image Type

`object` ([The image schema](values-properties-the-collector-schema-properties-the-image-schema.md))

## image Default Value

The default value is:

```json
{}
```

## image Examples

```json
{
  "registry": "",
  "repository": "logicmonitor/collector",
  "tag": "latest",
  "pullPolicy": ""
}
```

# image Properties

| Property                  | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                   |
| :------------------------ | :------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [registry](#registry)     | `string` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-the-image-schema-properties-the-registry-schema.md "#/properties/collector/properties/image/properties/registry#/properties/collector/properties/image/properties/registry")       |
| [repository](#repository) | `string` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-the-image-schema-properties-the-repository-schema.md "#/properties/collector/properties/image/properties/repository#/properties/collector/properties/image/properties/repository") |
| [tag](#tag)               | `string` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-the-image-schema-properties-the-tag-schema.md "#/properties/collector/properties/image/properties/tag#/properties/collector/properties/image/properties/tag")                      |
| [pullPolicy](#pullpolicy) | `string` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-the-image-schema-properties-the-pullpolicy-schema.md "#/properties/collector/properties/image/properties/pullPolicy#/properties/collector/properties/image/properties/pullPolicy") |

## registry

Container Image Registry

`registry`

*   is optional

*   Type: `string` ([The registry schema](values-properties-the-collector-schema-properties-the-image-schema-properties-the-registry-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-the-image-schema-properties-the-registry-schema.md "#/properties/collector/properties/image/properties/registry#/properties/collector/properties/image/properties/registry")

### registry Type

`string` ([The registry schema](values-properties-the-collector-schema-properties-the-image-schema-properties-the-registry-schema.md))

### registry Constraints

**minimum length**: the minimum number of characters for this string is: `0`

### registry Examples

```json
"382028353997.dkr.ecr.us-west-2.amazonaws.com"
```

## repository

An explanation about the purpose of this instance.

`repository`

*   is optional

*   Type: `string` ([The repository schema](values-properties-the-collector-schema-properties-the-image-schema-properties-the-repository-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-the-image-schema-properties-the-repository-schema.md "#/properties/collector/properties/image/properties/repository#/properties/collector/properties/image/properties/repository")

### repository Type

`string` ([The repository schema](values-properties-the-collector-schema-properties-the-image-schema-properties-the-repository-schema.md))

### repository Examples

```json
"logicmonitor/collector"
```

## tag

An explanation about the purpose of this instance.

`tag`

*   is optional

*   Type: `string` ([The tag schema](values-properties-the-collector-schema-properties-the-image-schema-properties-the-tag-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-the-image-schema-properties-the-tag-schema.md "#/properties/collector/properties/image/properties/tag#/properties/collector/properties/image/properties/tag")

### tag Type

`string` ([The tag schema](values-properties-the-collector-schema-properties-the-image-schema-properties-the-tag-schema.md))

### tag Examples

```json
"latest"
```

## pullPolicy

An explanation about the purpose of this instance.

`pullPolicy`

*   is optional

*   Type: `string` ([The pullPolicy schema](values-properties-the-collector-schema-properties-the-image-schema-properties-the-pullpolicy-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-the-image-schema-properties-the-pullpolicy-schema.md "#/properties/collector/properties/image/properties/pullPolicy#/properties/collector/properties/image/properties/pullPolicy")

### pullPolicy Type

`string` ([The pullPolicy schema](values-properties-the-collector-schema-properties-the-image-schema-properties-the-pullpolicy-schema.md))

### pullPolicy Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value            | Explanation |
| :--------------- | :---------- |
| `"Always"`       |             |
| `"IfNotPresent"` |             |
| `"Never"`        |             |
| `""`             |             |

### pullPolicy Examples

```json
""
```
