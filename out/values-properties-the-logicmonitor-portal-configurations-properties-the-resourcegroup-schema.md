# The resourceGroup schema Schema

```txt
#/properties/lm/properties/resourceGroup#/properties/lm/properties/resourceGroup
```

Resource Group Settings

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [values.schema.json\*](values.schema.json "open original schema") |

## resourceGroup Type

`object` ([The resourceGroup schema](values-properties-the-logicmonitor-portal-configurations-properties-the-resourcegroup-schema.md))

## resourceGroup Default Value

The default value is:

```json
{}
```

## resourceGroup Examples

```json
{
  "extraProps": {
    "cluster": [],
    "nodes": [],
    "etcd": []
  }
}
```

# resourceGroup Properties

| Property                  | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                               |
| :------------------------ | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [extraProps](#extraprops) | `object` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-logicmonitor-portal-configurations-properties-the-resourcegroup-schema-properties-the-extraprops-schema.md "#/properties/lm/properties/resourceGroup/properties/extraProps#/properties/lm/properties/resourceGroup/properties/extraProps") |

## extraProps

Extra Properties to add upon resource groups, only cluster scoped resources are valid, for rest others use namespace labels

`extraProps`

*   is optional

*   Type: `object` ([The extraProps schema](values-properties-the-logicmonitor-portal-configurations-properties-the-resourcegroup-schema-properties-the-extraprops-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-logicmonitor-portal-configurations-properties-the-resourcegroup-schema-properties-the-extraprops-schema.md "#/properties/lm/properties/resourceGroup/properties/extraProps#/properties/lm/properties/resourceGroup/properties/extraProps")

### extraProps Type

`object` ([The extraProps schema](values-properties-the-logicmonitor-portal-configurations-properties-the-resourcegroup-schema-properties-the-extraprops-schema.md))

### extraProps Default Value

The default value is:

```json
{}
```

### extraProps Examples

```json
{
  "cluster": [],
  "nodes": [],
  "etcd": []
}
```
