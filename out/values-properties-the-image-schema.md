# The image schema Schema

```txt
#/properties/image#/properties/image
```

An explanation about the purpose of this instance.

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## image Type

`object` ([The image schema](values-properties-the-image-schema.md))

## image Default Value

The default value is:

```json
{}
```

## image Examples

```json
{
  "registry": "382028353997.dkr.ecr.us-west-2.amazonaws.com",
  "repository": "logicmonitor/argus",
  "pullPolicy": "Always",
  "tag": "v6"
}
```

# image Properties

| Property                  | Type     | Required | Nullable       | Defined by                                                                                                                                                                                               |
| :------------------------ | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [registry](#registry)     | `string` | Optional | cannot be null | [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-image-schema-properties-the-registry-schema.md "#/properties/image/properties/registry#/properties/image/properties/registry")       |
| [repository](#repository) | `string` | Optional | cannot be null | [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-image-schema-properties-the-repository-schema.md "#/properties/image/properties/repository#/properties/image/properties/repository") |
| [pullPolicy](#pullpolicy) | `string` | Optional | cannot be null | [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-image-schema-properties-pullpolicy.md "#/properties/image/properties/pullPolicy#/properties/image/properties/pullPolicy")            |
| [tag](#tag)               | `string` | Optional | cannot be null | [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-image-schema-properties-the-tag-schema.md "#/properties/image/properties/tag#/properties/image/properties/tag")                      |

## registry

Container Image Registry

`registry`

*   is optional

*   Type: `string` ([The registry schema](values-properties-the-image-schema-properties-the-registry-schema.md))

*   cannot be null

*   defined in: [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-image-schema-properties-the-registry-schema.md "#/properties/image/properties/registry#/properties/image/properties/registry")

### registry Type

`string` ([The registry schema](values-properties-the-image-schema-properties-the-registry-schema.md))

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

*   Type: `string` ([The repository schema](values-properties-the-image-schema-properties-the-repository-schema.md))

*   cannot be null

*   defined in: [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-image-schema-properties-the-repository-schema.md "#/properties/image/properties/repository#/properties/image/properties/repository")

### repository Type

`string` ([The repository schema](values-properties-the-image-schema-properties-the-repository-schema.md))

### repository Constraints

**minimum length**: the minimum number of characters for this string is: `1`

### repository Default Value

The default value is:

```json
"logicmonitor/argus"
```

### repository Examples

```json
"logicmonitor/argus"
```

## pullPolicy

Overrides the image tag whose default is the chart appVersion.

`pullPolicy`

*   is optional

*   Type: `string` ([pullPolicy](values-properties-the-image-schema-properties-pullpolicy.md))

*   cannot be null

*   defined in: [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-image-schema-properties-pullpolicy.md "#/properties/image/properties/pullPolicy#/properties/image/properties/pullPolicy")

### pullPolicy Type

`string` ([pullPolicy](values-properties-the-image-schema-properties-pullpolicy.md))

### pullPolicy Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value            | Explanation |
| :--------------- | :---------- |
| `"Always"`       |             |
| `"IfNotPresent"` |             |
| `"Never"`        |             |
| `""`             |             |

### pullPolicy Default Value

The default value is:

```json
"Always"
```

### pullPolicy Examples

```json
"Always"
```

## tag

An explanation about the purpose of this instance.

`tag`

*   is optional

*   Type: `string` ([The tag schema](values-properties-the-image-schema-properties-the-tag-schema.md))

*   cannot be null

*   defined in: [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-image-schema-properties-the-tag-schema.md "#/properties/image/properties/tag#/properties/image/properties/tag")

### tag Type

`string` ([The tag schema](values-properties-the-image-schema-properties-the-tag-schema.md))

### tag Examples

```json
""
```
