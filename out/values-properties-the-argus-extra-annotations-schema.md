# The Argus extra annotations schema Schema

```txt
#/properties/annotations#/properties/annotations
```

Annotations to apply on all objects created by Argus. Annotations is an unstructured key value map stored with a resource that may be set by external tools to store and retrieve arbitrary metadata. They are not queryable and should be preserved when modifying objects. More info: <http://kubernetes.io/docs/user-guide/annotations>

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## annotations Type

`object` ([The Argus extra annotations schema](values-properties-the-argus-extra-annotations-schema.md))

## annotations Default Value

The default value is:

```json
{}
```

## annotations Examples

```json
{}
```

# annotations Properties

| Property              | Type     | Required | Nullable       | Defined by                                                                                                                                                                                    |
| :-------------------- | :------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Additional Properties | `string` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-argus-extra-annotations-schema-additionalproperties.md "#/properties/annotations#/properties/annotations/additionalProperties") |

## Additional Properties

Additional properties are allowed, as long as they follow this schema:



*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-argus-extra-annotations-schema-additionalproperties.md "#/properties/annotations#/properties/annotations/additionalProperties")

### additionalProperties Type

`string`
