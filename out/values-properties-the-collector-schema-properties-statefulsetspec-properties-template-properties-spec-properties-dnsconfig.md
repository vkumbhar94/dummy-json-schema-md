# Untitled object in Argus Helm Chart Configuration Schema Schema

```txt
#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/dnsConfig#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/dnsConfig
```

PodDNSConfig defines the DNS parameters of a pod in addition to those generated from DNSPolicy.

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## dnsConfig Type

`object` ([Details](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-dnsconfig.md))

# dnsConfig Properties

| Property                    | Type    | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| :-------------------------- | :------ | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [nameservers](#nameservers) | `array` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-dnsconfig-properties-nameservers.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/containers/properties/nameservers#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/dnsConfig/properties/nameservers") |
| [options](#options)         | `array` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-dnsconfig-properties-options.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/containers/properties/options#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/dnsConfig/properties/options")             |
| [searches](#searches)       | `array` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-dnsconfig-properties-searches.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/containers/properties/searches#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/dnsConfig/properties/searches")          |

## nameservers

A list of DNS name server IP addresses. This will be appended to the base nameservers generated from DNSPolicy. Duplicated nameservers will be removed.

`nameservers`

*   is optional

*   Type: `string[]`

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-dnsconfig-properties-nameservers.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/containers/properties/nameservers#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/dnsConfig/properties/nameservers")

### nameservers Type

`string[]`

## options

A list of DNS resolver options. This will be merged with the base options generated from DNSPolicy. Duplicated entries will be removed. Resolution options given in Options will override those that appear in the base DNSPolicy.

`options`

*   is optional

*   Type: `object[]` ([Details](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-dnsconfig-properties-options-items.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-dnsconfig-properties-options.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/containers/properties/options#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/dnsConfig/properties/options")

### options Type

`object[]` ([Details](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-dnsconfig-properties-options-items.md))

## searches

A list of DNS search domains for host-name lookup. This will be appended to the base search paths generated from DNSPolicy. Duplicated search paths will be removed.

`searches`

*   is optional

*   Type: `string[]`

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-dnsconfig-properties-searches.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/containers/properties/searches#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/dnsConfig/properties/searches")

### searches Type

`string[]`
