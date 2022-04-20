# Untitled object in Logicmonitor Argus Helm Chart Values Schema Schema

```txt
#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/hostAliases#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/hostAliases/items
```

HostAlias holds the mapping between IP and hostnames that will be injected as an entry in the pod's hosts file.

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## items Type

`object` ([Details](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-hostaliases-items.md))

# items Properties

| Property                | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| :---------------------- | :------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [hostnames](#hostnames) | `array`  | Optional | cannot be null | [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-hostaliases-items-properties-hostnames.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/hostAliases#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/hostAliases/items/properties/hostnames") |
| [ip](#ip)               | `string` | Optional | cannot be null | [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-hostaliases-items-properties-ip.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/hostAliases#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/hostAliases/items/properties/ip")               |

## hostnames

Hostnames for the above IP address.

`hostnames`

*   is optional

*   Type: `string[]`

*   cannot be null

*   defined in: [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-hostaliases-items-properties-hostnames.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/hostAliases#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/hostAliases/items/properties/hostnames")

### hostnames Type

`string[]`

## ip

IP address of the host file entry.

`ip`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-hostaliases-items-properties-ip.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/hostAliases#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/hostAliases/items/properties/ip")

### ip Type

`string`
