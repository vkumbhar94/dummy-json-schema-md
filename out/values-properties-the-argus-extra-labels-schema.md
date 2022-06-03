# The Argus extra labels schema Schema

```txt
#/properties/labels#/properties/labels
```

Labels to apply on all objects created by Argus. Map of string keys and values that can be used to organize and categorize (scope and select) objects. May match selectors of replication controllers and services. More info: <http://kubernetes.io/docs/user-guide/labels>

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## labels Type

`object` ([The Argus extra labels schema](values-properties-the-argus-extra-labels-schema.md))

## labels Default Value

The default value is:

```json
{}
```

## labels Examples

```json
{}
```

# labels Properties

| Property              | Type     | Required | Nullable       | Defined by                                                                                                                                                                     |
| :-------------------- | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Additional Properties | `string` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-argus-extra-labels-schema-additionalproperties.md "#/properties/labels#/properties/labels/additionalProperties") |

## Additional Properties

Additional properties are allowed, as long as they follow this schema:



*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-argus-extra-labels-schema-additionalproperties.md "#/properties/labels#/properties/labels/additionalProperties")

### additionalProperties Type

`string`
