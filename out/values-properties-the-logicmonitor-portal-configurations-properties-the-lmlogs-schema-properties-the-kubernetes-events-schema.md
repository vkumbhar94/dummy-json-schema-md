# The Kubernetes Events schema Schema

```txt
#/properties/lm/properties/lmlogs/properties/k8sevent#/properties/lm/properties/lmlogs/properties/k8sevent
```

The Kubernetes Events collection configurations

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## k8sevent Type

`object` ([The Kubernetes Events schema](values-properties-the-logicmonitor-portal-configurations-properties-the-lmlogs-schema-properties-the-kubernetes-events-schema.md))

## k8sevent Default Value

The default value is:

```json
{}
```

## k8sevent Examples

```json
{
  "enable": false
}
```

# k8sevent Properties

| Property          | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                              |
| :---------------- | :-------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [enable](#enable) | `boolean` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-logicmonitor-portal-configurations-properties-the-lmlogs-schema-properties-the-kubernetes-events-schema-properties-the-enable-schema.md "#/properties/lm/properties/lmlogs/properties/k8sevent/properties/enable#/properties/lm/properties/lmlogs/properties/k8sevent/properties/enable") |

## enable

Setting this to true starts kuberentes events collection

`enable`

*   is optional

*   Type: `boolean` ([The enable schema](values-properties-the-logicmonitor-portal-configurations-properties-the-lmlogs-schema-properties-the-kubernetes-events-schema-properties-the-enable-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-logicmonitor-portal-configurations-properties-the-lmlogs-schema-properties-the-kubernetes-events-schema-properties-the-enable-schema.md "#/properties/lm/properties/lmlogs/properties/k8sevent/properties/enable#/properties/lm/properties/lmlogs/properties/k8sevent/properties/enable")

### enable Type

`boolean` ([The enable schema](values-properties-the-logicmonitor-portal-configurations-properties-the-lmlogs-schema-properties-the-kubernetes-events-schema-properties-the-enable-schema.md))

### enable Examples

```json
false
```
