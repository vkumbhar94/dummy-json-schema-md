# Argus Image Registry Schema Schema

```txt
#/properties/image/properties/registry#/properties/image/properties/registry
```

The Docker Registry from which Argus image to pull.
defaults to empty value.

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## registry Type

`string` ([Argus Image Registry Schema](values-properties-argus-docker-image-schema-properties-argus-image-registry-schema.md))

## registry Constraints

**minimum length**: the minimum number of characters for this string is: `0`

## registry Examples

```json
"382028353997.dkr.ecr.us-west-2.amazonaws.com"
```
