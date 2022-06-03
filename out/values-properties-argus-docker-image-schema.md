# Argus Docker Image Schema Schema

```txt
#/properties/image#/properties/image
```

The image holds the Argus docker image details.

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [values.schema.json\*](values.schema.json "open original schema") |

## image Type

`object` ([Argus Docker Image Schema](values-properties-argus-docker-image-schema.md))

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

| Property                  | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                          |
| :------------------------ | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [registry](#registry)     | `string` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-argus-docker-image-schema-properties-argus-image-registry-schema.md "#/properties/image/properties/registry#/properties/image/properties/registry")       |
| [repository](#repository) | `string` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-argus-docker-image-schema-properties-argus-image-repository-schema.md "#/properties/image/properties/repository#/properties/image/properties/repository") |
| [pullPolicy](#pullpolicy) | `string` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-argus-docker-image-schema-properties-the-argus-pullpolicy-schema.md "#/properties/image/properties/pullPolicy#/properties/image/properties/pullPolicy")   |
| [tag](#tag)               | `string` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-argus-docker-image-schema-properties-the-argus-image-tag-schema.md "#/properties/image/properties/tag#/properties/image/properties/tag")                  |

## registry

The Docker Registry from which Argus image to pull.
defaults to empty value.

`registry`

*   is optional

*   Type: `string` ([Argus Image Registry Schema](values-properties-argus-docker-image-schema-properties-argus-image-registry-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-argus-docker-image-schema-properties-argus-image-registry-schema.md "#/properties/image/properties/registry#/properties/image/properties/registry")

### registry Type

`string` ([Argus Image Registry Schema](values-properties-argus-docker-image-schema-properties-argus-image-registry-schema.md))

### registry Constraints

**minimum length**: the minimum number of characters for this string is: `0`

### registry Examples

```json
"382028353997.dkr.ecr.us-west-2.amazonaws.com"
```

## repository

The Docker Repository Name for Argus Image

`repository`

*   is optional

*   Type: `string` ([Argus Image Repository Schema](values-properties-argus-docker-image-schema-properties-argus-image-repository-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-argus-docker-image-schema-properties-argus-image-repository-schema.md "#/properties/image/properties/repository#/properties/image/properties/repository")

### repository Type

`string` ([Argus Image Repository Schema](values-properties-argus-docker-image-schema-properties-argus-image-repository-schema.md))

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

Overrides the image pullPolicy.
Defaults to Always.

`pullPolicy`

*   is optional

*   Type: `string` ([The Argus pullPolicy Schema](values-properties-argus-docker-image-schema-properties-the-argus-pullpolicy-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-argus-docker-image-schema-properties-the-argus-pullpolicy-schema.md "#/properties/image/properties/pullPolicy#/properties/image/properties/pullPolicy")

### pullPolicy Type

`string` ([The Argus pullPolicy Schema](values-properties-argus-docker-image-schema-properties-the-argus-pullpolicy-schema.md))

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

The Argus Docker Image Tag

`tag`

*   is optional

*   Type: `string` ([The Argus Image tag schema](values-properties-argus-docker-image-schema-properties-the-argus-image-tag-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-argus-docker-image-schema-properties-the-argus-image-tag-schema.md "#/properties/image/properties/tag#/properties/image/properties/tag")

### tag Type

`string` ([The Argus Image tag schema](values-properties-argus-docker-image-schema-properties-the-argus-image-tag-schema.md))

### tag Examples

```json
""
```
