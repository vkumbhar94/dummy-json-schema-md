# The image schema Schema

```txt
#/properties/global/properties/image#/properties/global/properties/image
```

An explanation about the purpose of this instance.

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## image Type

`object` ([The image schema](values-properties-global-properties-the-image-schema.md))

## image Default Value

The default value is:

```json
{}
```

## image Examples

```json
{
  "pullPolicy": "Always"
}
```

# image Properties

| Property                  | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                         |
| :------------------------ | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [registry](#registry)     | `string` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-global-properties-the-image-schema-properties-the-registry-schema.md "#/properties/global/properties/image/properties/registry#/properties/global/properties/image/properties/registry") |
| [pullPolicy](#pullpolicy) | `string` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-global-properties-the-image-schema-properties-pullpolicy.md "#/properties/global/properties/image/properties/pullpolicy#/properties/global/properties/image/properties/pullPolicy")      |

## registry

Container Image Registry

`registry`

*   is optional

*   Type: `string` ([The registry schema](values-properties-global-properties-the-image-schema-properties-the-registry-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-global-properties-the-image-schema-properties-the-registry-schema.md "#/properties/global/properties/image/properties/registry#/properties/global/properties/image/properties/registry")

### registry Type

`string` ([The registry schema](values-properties-global-properties-the-image-schema-properties-the-registry-schema.md))

### registry Constraints

**minimum length**: the minimum number of characters for this string is: `0`

### registry Examples

```json
"382028353997.dkr.ecr.us-west-2.amazonaws.com"
```

## pullPolicy

Overrides the image tag whose default is the chart appVersion.

`pullPolicy`

*   is optional

*   Type: `string` ([pullPolicy](values-properties-global-properties-the-image-schema-properties-pullpolicy.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-global-properties-the-image-schema-properties-pullpolicy.md "#/properties/global/properties/image/properties/pullpolicy#/properties/global/properties/image/properties/pullPolicy")

### pullPolicy Type

`string` ([pullPolicy](values-properties-global-properties-the-image-schema-properties-pullpolicy.md))

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
