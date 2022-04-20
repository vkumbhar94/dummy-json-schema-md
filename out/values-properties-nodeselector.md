# nodeSelector Schema

```txt
#/properties/nodeSelector#/properties/nodeSelector
```

NodeSelector is a selector which must be true for the pod to fit on a node. Selector which must match a node's labels for the pod to be scheduled on that node. More info: <https://kubernetes.io/docs/concepts/configuration/assign-pod-node/>

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## nodeSelector Type

`object` ([nodeSelector](values-properties-nodeselector.md))

## nodeSelector Default Value

The default value is:

```json
{}
```

## nodeSelector Examples

```json
{}
```

# nodeSelector Properties

| Property              | Type     | Required | Nullable       | Defined by                                                                                                                                          |
| :-------------------- | :------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------- |
| Additional Properties | `string` | Optional | cannot be null | [The root schema](values-properties-nodeselector-additionalproperties.md "#/properties/nodeSelector#/properties/nodeSelector/additionalProperties") |

## Additional Properties

Additional properties are allowed, as long as they follow this schema:



*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [The root schema](values-properties-nodeselector-additionalproperties.md "#/properties/nodeSelector#/properties/nodeSelector/additionalProperties")

### additionalProperties Type

`string`
