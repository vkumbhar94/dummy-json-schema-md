# Untitled object in Argus Helm Chart Configuration Schema Schema

```txt
#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/persistentvolumeclaim#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/persistentVolumeClaim
```

PersistentVolumeClaimVolumeSource references the user's PVC in the same namespace. This volume finds the bound PV and mounts that volume for the pod. A PersistentVolumeClaimVolumeSource is, essentially, a wrapper around another type of volume that is owned by someone else (the system).

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## persistentVolumeClaim Type

`object` ([Details](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-persistentvolumeclaim.md))

# persistentVolumeClaim Properties

| Property                | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| :---------------------- | :-------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [claimName](#claimname) | `string`  | Required | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-persistentvolumeclaim-properties-claimname.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/persistentvolumeclaim/properties/claimname#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/persistentVolumeClaim/properties/claimName") |
| [readOnly](#readonly)   | `boolean` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-persistentvolumeclaim-properties-readonly.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/persistentvolumeclaim/properties/readonly#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/persistentVolumeClaim/properties/readOnly")    |

## claimName

ClaimName is the name of a PersistentVolumeClaim in the same namespace as the pod using this volume. More info: <https://kubernetes.io/docs/concepts/storage/persistent-volumes#persistentvolumeclaims>

`claimName`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-persistentvolumeclaim-properties-claimname.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/persistentvolumeclaim/properties/claimname#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/persistentVolumeClaim/properties/claimName")

### claimName Type

`string`

## readOnly

Will force the ReadOnly setting in VolumeMounts. Default false.

`readOnly`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-persistentvolumeclaim-properties-readonly.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/persistentvolumeclaim/properties/readonly#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/persistentVolumeClaim/properties/readOnly")

### readOnly Type

`boolean`
