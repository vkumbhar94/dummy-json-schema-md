# Argus Image Repository Schema Schema

```txt
#/properties/image/properties/repository#/properties/image/properties/repository
```

The Docker Repository Name for Argus Image

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## repository Type

`string` ([Argus Image Repository Schema](values-properties-argus-docker-image-schema-properties-argus-image-repository-schema.md))

## repository Constraints

**minimum length**: the minimum number of characters for this string is: `1`

## repository Default Value

The default value is:

```json
"logicmonitor/argus"
```

## repository Examples

```json
"logicmonitor/argus"
```
