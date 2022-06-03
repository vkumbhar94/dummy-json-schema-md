# The rbac schema Schema

```txt
#/properties/rbac#/properties/rbac
```

An explanation about the purpose of this instance.

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [values.schema.json\*](values.schema.json "open original schema") |

## rbac Type

`object` ([The rbac schema](values-properties-the-rbac-schema.md))

## rbac Default Value

The default value is:

```json
{}
```

## rbac Examples

```json
{
  "create": true
}
```

# rbac Properties

| Property          | Type      | Required | Nullable       | Defined by                                                                                                                                                                          |
| :---------------- | :-------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [create](#create) | `boolean` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-rbac-schema-properties-the-create-schema.md "#/properties/rbac/properties/create#/properties/rbac/properties/create") |

## create

An explanation about the purpose of this instance.

`create`

*   is optional

*   Type: `boolean` ([The create schema](values-properties-the-rbac-schema-properties-the-create-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-rbac-schema-properties-the-create-schema.md "#/properties/rbac/properties/create#/properties/rbac/properties/create")

### create Type

`boolean` ([The create schema](values-properties-the-rbac-schema-properties-the-create-schema.md))

### create Examples

```json
true
```
