# Untitled object in Argus Helm Chart Configuration Schema Schema

```txt
#/properties/resources/properties/requests#/properties/resources/properties/requests
```

Requests describes the minimum amount of compute resources required. If Requests is omitted for a container, it defaults to Limits if that is explicitly specified, otherwise to an implementation-defined value. More info: <https://kubernetes.io/docs/concepts/configuration/manage-compute-resources-container/>

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## requests Type

`object` ([Details](values-properties-the-argus-resource-limits-schema-properties-requests.md))

# requests Properties

| Property              | Type          | Required | Nullable       | Defined by                                                                                                                                                                                                                                          |
| :-------------------- | :------------ | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Additional Properties | Not specified | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-argus-resource-limits-schema-properties-requests-additionalproperties.md "#/properties/resources/properties/requests#/properties/resources/properties/requests/additionalProperties") |

## Additional Properties

Additional properties are allowed, as long as they follow this schema:



*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-argus-resource-limits-schema-properties-requests-additionalproperties.md "#/properties/resources/properties/requests#/properties/resources/properties/requests/additionalProperties")

### additionalProperties Type

unknown
