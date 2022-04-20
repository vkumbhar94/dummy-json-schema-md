# The k8spodlog schema Schema

```txt
#/properties/lm/properties/lmlogs/properties/k8spodlog#/properties/lm/properties/lmlogs/properties/k8spodlog
```

Kubernetes Pod Logs collection configurations

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## k8spodlog Type

`object` ([The k8spodlog schema](values-properties-the-lm-schema-properties-the-lmlogs-schema-properties-the-k8spodlog-schema.md))

## k8spodlog Default Value

The default value is:

```json
{}
```

## k8spodlog Examples

```json
{
  "enable": false
}
```

# k8spodlog Properties

| Property          | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                     |
| :---------------- | :-------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [enable](#enable) | `boolean` | Optional | cannot be null | [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-lm-schema-properties-the-lmlogs-schema-properties-the-k8spodlog-schema-properties-the-enable-schema.md "#/properties/lm/properties/lmlogs/properties/k8spodlog/properties/enable#/properties/lm/properties/lmlogs/properties/k8spodlog/properties/enable") |

## enable

Setting this to true starts kuberentes pod's logs collection

`enable`

*   is optional

*   Type: `boolean` ([The enable schema](values-properties-the-lm-schema-properties-the-lmlogs-schema-properties-the-k8spodlog-schema-properties-the-enable-schema.md))

*   cannot be null

*   defined in: [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-lm-schema-properties-the-lmlogs-schema-properties-the-k8spodlog-schema-properties-the-enable-schema.md "#/properties/lm/properties/lmlogs/properties/k8spodlog/properties/enable#/properties/lm/properties/lmlogs/properties/k8spodlog/properties/enable")

### enable Type

`boolean` ([The enable schema](values-properties-the-lm-schema-properties-the-lmlogs-schema-properties-the-k8spodlog-schema-properties-the-enable-schema.md))

### enable Examples

```json
false
```
