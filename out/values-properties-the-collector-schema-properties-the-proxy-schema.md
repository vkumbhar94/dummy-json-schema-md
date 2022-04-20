# The proxy schema Schema

```txt
#/properties/collector/properties/proxy#/properties/collector/properties/proxy
```

An explanation about the purpose of this instance.

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## proxy Type

`object` ([The proxy schema](values-properties-the-collector-schema-properties-the-proxy-schema.md))

## proxy Default Value

The default value is:

```json
{}
```

## proxy Examples

```json
{
  "url": "",
  "user": "",
  "pass": ""
}
```

# proxy Properties

| Property      | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                       |
| :------------ | :------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [url](#url)   | `string` | Optional | cannot be null | [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-collector-schema-properties-the-proxy-schema-properties-the-url-schema.md "#/properties/collector/properties/proxy/properties/url#/properties/collector/properties/proxy/properties/url")    |
| [user](#user) | `string` | Optional | cannot be null | [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-collector-schema-properties-the-proxy-schema-properties-the-user-schema.md "#/properties/collector/properties/proxy/properties/user#/properties/collector/properties/proxy/properties/user") |
| [pass](#pass) | `string` | Optional | cannot be null | [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-collector-schema-properties-the-proxy-schema-properties-the-pass-schema.md "#/properties/collector/properties/proxy/properties/pass#/properties/collector/properties/proxy/properties/pass") |

## url

An explanation about the purpose of this instance.

`url`

*   is optional

*   Type: `string` ([The url schema](values-properties-the-collector-schema-properties-the-proxy-schema-properties-the-url-schema.md))

*   cannot be null

*   defined in: [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-collector-schema-properties-the-proxy-schema-properties-the-url-schema.md "#/properties/collector/properties/proxy/properties/url#/properties/collector/properties/proxy/properties/url")

### url Type

`string` ([The url schema](values-properties-the-collector-schema-properties-the-proxy-schema-properties-the-url-schema.md))

### url Examples

```json
""
```

## user

An explanation about the purpose of this instance.

`user`

*   is optional

*   Type: `string` ([The user schema](values-properties-the-collector-schema-properties-the-proxy-schema-properties-the-user-schema.md))

*   cannot be null

*   defined in: [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-collector-schema-properties-the-proxy-schema-properties-the-user-schema.md "#/properties/collector/properties/proxy/properties/user#/properties/collector/properties/proxy/properties/user")

### user Type

`string` ([The user schema](values-properties-the-collector-schema-properties-the-proxy-schema-properties-the-user-schema.md))

### user Examples

```json
""
```

## pass

An explanation about the purpose of this instance.

`pass`

*   is optional

*   Type: `string` ([The pass schema](values-properties-the-collector-schema-properties-the-proxy-schema-properties-the-pass-schema.md))

*   cannot be null

*   defined in: [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-collector-schema-properties-the-proxy-schema-properties-the-pass-schema.md "#/properties/collector/properties/proxy/properties/pass#/properties/collector/properties/proxy/properties/pass")

### pass Type

`string` ([The pass schema](values-properties-the-collector-schema-properties-the-proxy-schema-properties-the-pass-schema.md))

### pass Examples

```json
""
```
