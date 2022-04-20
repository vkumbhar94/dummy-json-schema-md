# The lmlogs schema Schema

```txt
#/properties/lm/properties/lmlogs#/properties/lm/properties/lmlogs
```

Logicmonitor Logs collection settings

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## lmlogs Type

`object` ([The lmlogs schema](values-properties-the-lm-schema-properties-the-lmlogs-schema.md))

## lmlogs Default Value

The default value is:

```json
{}
```

## lmlogs Examples

```json
{
  "k8sevent": {
    "enable": false
  },
  "k8spodlog": {
    "enable": false
  }
}
```

# lmlogs Properties

| Property                | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                        |
| :---------------------- | :------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [k8sevent](#k8sevent)   | `object` | Optional | cannot be null | [The root schema](values-properties-the-lm-schema-properties-the-lmlogs-schema-properties-the-k8sevent-schema.md "#/properties/lm/properties/lmlogs/properties/k8sevent#/properties/lm/properties/lmlogs/properties/k8sevent")    |
| [k8spodlog](#k8spodlog) | `object` | Optional | cannot be null | [The root schema](values-properties-the-lm-schema-properties-the-lmlogs-schema-properties-the-k8spodlog-schema.md "#/properties/lm/properties/lmlogs/properties/k8spodlog#/properties/lm/properties/lmlogs/properties/k8spodlog") |

## k8sevent

Kubernetes Events collection configurations

`k8sevent`

*   is optional

*   Type: `object` ([The k8sevent schema](values-properties-the-lm-schema-properties-the-lmlogs-schema-properties-the-k8sevent-schema.md))

*   cannot be null

*   defined in: [The root schema](values-properties-the-lm-schema-properties-the-lmlogs-schema-properties-the-k8sevent-schema.md "#/properties/lm/properties/lmlogs/properties/k8sevent#/properties/lm/properties/lmlogs/properties/k8sevent")

### k8sevent Type

`object` ([The k8sevent schema](values-properties-the-lm-schema-properties-the-lmlogs-schema-properties-the-k8sevent-schema.md))

### k8sevent Default Value

The default value is:

```json
{}
```

### k8sevent Examples

```json
{
  "enable": false
}
```

## k8spodlog

Kubernetes Pod Logs collection configurations

`k8spodlog`

*   is optional

*   Type: `object` ([The k8spodlog schema](values-properties-the-lm-schema-properties-the-lmlogs-schema-properties-the-k8spodlog-schema.md))

*   cannot be null

*   defined in: [The root schema](values-properties-the-lm-schema-properties-the-lmlogs-schema-properties-the-k8spodlog-schema.md "#/properties/lm/properties/lmlogs/properties/k8spodlog#/properties/lm/properties/lmlogs/properties/k8spodlog")

### k8spodlog Type

`object` ([The k8spodlog schema](values-properties-the-lm-schema-properties-the-lmlogs-schema-properties-the-k8spodlog-schema.md))

### k8spodlog Default Value

The default value is:

```json
{}
```

### k8spodlog Examples

```json
{
  "enable": false
}
```
