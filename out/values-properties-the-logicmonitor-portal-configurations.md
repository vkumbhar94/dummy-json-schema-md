# The Logicmonitor Portal Configurations Schema

```txt
#/properties/lm#/properties/lm
```

The Settings/Configurations which reflect on Logicmonitor Portal

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [values.schema.json\*](values.schema.json "open original schema") |

## lm Type

`object` ([The Logicmonitor Portal Configurations](values-properties-the-logicmonitor-portal-configurations.md))

## lm Default Value

The default value is:

```json
{}
```

## lm Examples

```json
{
  "lmlogs": {
    "k8sevent": {
      "enable": false
    },
    "k8spodlog": {
      "enable": false
    }
  },
  "resource": {
    "globalDeleteAfterDuration": "P0DT0H0M0S",
    "alerting": {
      "disable": []
    }
  },
  "resourceGroup": {
    "extraProps": {
      "cluster": [],
      "nodes": [],
      "etcd": []
    }
  }
}
```

# lm Properties

| Property                        | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                  |
| :------------------------------ | :------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [lmlogs](#lmlogs)               | `object` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-logicmonitor-portal-configurations-properties-the-lmlogs-schema.md "#/properties/lm/properties/lmlogs#/properties/lm/properties/lmlogs")                      |
| [resource](#resource)           | `object` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-logicmonitor-portal-configurations-properties-the-resource-schema.md "#/properties/lm/properties/resource#/properties/lm/properties/resource")                |
| [resourceGroup](#resourcegroup) | `object` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-logicmonitor-portal-configurations-properties-the-resourcegroup-schema.md "#/properties/lm/properties/resourceGroup#/properties/lm/properties/resourceGroup") |

## lmlogs

The Logicmonitor Logs collection settings

`lmlogs`

*   is optional

*   Type: `object` ([The LMLogs schema](values-properties-the-logicmonitor-portal-configurations-properties-the-lmlogs-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-logicmonitor-portal-configurations-properties-the-lmlogs-schema.md "#/properties/lm/properties/lmlogs#/properties/lm/properties/lmlogs")

### lmlogs Type

`object` ([The LMLogs schema](values-properties-the-logicmonitor-portal-configurations-properties-the-lmlogs-schema.md))

### lmlogs Default Value

The default value is:

```json
{}
```

### lmlogs Examples

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

## resource

An explanation about the purpose of this instance.

`resource`

*   is optional

*   Type: `object` ([The resource schema](values-properties-the-logicmonitor-portal-configurations-properties-the-resource-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-logicmonitor-portal-configurations-properties-the-resource-schema.md "#/properties/lm/properties/resource#/properties/lm/properties/resource")

### resource Type

`object` ([The resource schema](values-properties-the-logicmonitor-portal-configurations-properties-the-resource-schema.md))

### resource Default Value

The default value is:

```json
{}
```

### resource Examples

```json
{
  "globalDeleteAfterDuration": "P0DT0H0M0S",
  "alerting": {
    "disable": []
  }
}
```

## resourceGroup

Resource Group Settings

`resourceGroup`

*   is optional

*   Type: `object` ([The resourceGroup schema](values-properties-the-logicmonitor-portal-configurations-properties-the-resourcegroup-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-logicmonitor-portal-configurations-properties-the-resourcegroup-schema.md "#/properties/lm/properties/resourceGroup#/properties/lm/properties/resourceGroup")

### resourceGroup Type

`object` ([The resourceGroup schema](values-properties-the-logicmonitor-portal-configurations-properties-the-resourcegroup-schema.md))

### resourceGroup Default Value

The default value is:

```json
{}
```

### resourceGroup Examples

```json
{
  "extraProps": {
    "cluster": [],
    "nodes": [],
    "etcd": []
  }
}
```
