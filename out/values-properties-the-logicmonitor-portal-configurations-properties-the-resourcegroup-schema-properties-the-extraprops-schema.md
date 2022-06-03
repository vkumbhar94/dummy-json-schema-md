# The extraProps schema Schema

```txt
#/properties/lm/properties/resourceGroup/properties/extraProps#/properties/lm/properties/resourceGroup/properties/extraProps
```

Extra Properties to add upon resource groups, only cluster scoped resources are valid, for rest others use namespace labels

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## extraProps Type

`object` ([The extraProps schema](values-properties-the-logicmonitor-portal-configurations-properties-the-resourcegroup-schema-properties-the-extraprops-schema.md))

## extraProps Default Value

The default value is:

```json
{}
```

## extraProps Examples

```json
{
  "cluster": [],
  "nodes": [],
  "etcd": []
}
```

# extraProps Properties

| Property              | Type          | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                                                                          |
| :-------------------- | :------------ | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [cluster](#cluster)   | `array`       | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-logicmonitor-portal-configurations-properties-the-resourcegroup-schema-properties-the-extraprops-schema-properties-the-cluster-schema.md "#/properties/lm/properties/resourceGroup/properties/extraProps/properties/cluster#/properties/lm/properties/resourceGroup/properties/extraProps/properties/cluster")                        |
| [nodes](#nodes)       | `array`       | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-logicmonitor-portal-configurations-properties-the-resourcegroup-schema-properties-the-extraprops-schema-properties-properties-to-apply-upon-nodes-resource-group.md "#/properties/lm/properties/resourceGroup/properties/extraProps/properties/nodes#/properties/lm/properties/resourceGroup/properties/extraProps/properties/nodes") |
| [etcd](#etcd)         | `array`       | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-logicmonitor-portal-configurations-properties-the-resourcegroup-schema-properties-the-extraprops-schema-properties-the-etcd-schema.md "#/properties/lm/properties/resourceGroup/properties/extraProps/properties/etcd#/properties/lm/properties/resourceGroup/properties/extraProps/properties/etcd")                                 |
| Additional Properties | Not specified | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-logicmonitor-portal-configurations-properties-the-resourcegroup-schema-properties-the-extraprops-schema-additionalproperties.md "#/properties/lm/properties/resourceGroup/properties/extraProps#/properties/lm/properties/resourceGroup/properties/extraProps/additionalProperties")                                                  |

## cluster

Properties to apply upon cluster tree root resource group

`cluster`

*   is optional

*   Type: unknown\[]

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-logicmonitor-portal-configurations-properties-the-resourcegroup-schema-properties-the-extraprops-schema-properties-the-cluster-schema.md "#/properties/lm/properties/resourceGroup/properties/extraProps/properties/cluster#/properties/lm/properties/resourceGroup/properties/extraProps/properties/cluster")

### cluster Type

unknown\[]

### cluster Default Value

The default value is:

```json
[]
```

### cluster Examples

```json
[]
```

## nodes



`nodes`

*   is optional

*   Type: unknown\[]

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-logicmonitor-portal-configurations-properties-the-resourcegroup-schema-properties-the-extraprops-schema-properties-properties-to-apply-upon-nodes-resource-group.md "#/properties/lm/properties/resourceGroup/properties/extraProps/properties/nodes#/properties/lm/properties/resourceGroup/properties/extraProps/properties/nodes")

### nodes Type

unknown\[]

### nodes Default Value

The default value is:

```json
[]
```

### nodes Examples

```json
[]
```

## etcd

Properties to apply upon ETCD resource group

`etcd`

*   is optional

*   Type: unknown\[]

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-logicmonitor-portal-configurations-properties-the-resourcegroup-schema-properties-the-extraprops-schema-properties-the-etcd-schema.md "#/properties/lm/properties/resourceGroup/properties/extraProps/properties/etcd#/properties/lm/properties/resourceGroup/properties/extraProps/properties/etcd")

### etcd Type

unknown\[]

### etcd Default Value

The default value is:

```json
[]
```

### etcd Examples

```json
[]
```

## Additional Properties

Additional properties are allowed, as long as they follow this schema:



*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-logicmonitor-portal-configurations-properties-the-resourcegroup-schema-properties-the-extraprops-schema-additionalproperties.md "#/properties/lm/properties/resourceGroup/properties/extraProps#/properties/lm/properties/resourceGroup/properties/extraProps/additionalProperties")

### additionalProperties Type

unknown
