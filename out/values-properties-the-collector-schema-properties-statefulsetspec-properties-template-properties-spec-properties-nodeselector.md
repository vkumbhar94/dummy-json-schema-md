# Untitled object in Logicmonitor Argus Helm Chart Values Schema Schema

```txt
#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/nodeselector#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/nodeSelector
```

NodeSelector is a selector which must be true for the pod to fit on a node. Selector which must match a node's labels for the pod to be scheduled on that node. More info: <https://kubernetes.io/docs/concepts/configuration/assign-pod-node/>

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## nodeSelector Type

`object` ([Details](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-nodeselector.md))

# nodeSelector Properties

| Property              | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| :-------------------- | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Additional Properties | `string` | Optional | cannot be null | [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-nodeselector-additionalproperties.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/nodeselector#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/nodeSelector/additionalProperties") |

## Additional Properties

Additional properties are allowed, as long as they follow this schema:



*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-nodeselector-additionalproperties.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/nodeselector#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/nodeSelector/additionalProperties")

### additionalProperties Type

`string`
