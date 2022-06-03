# The proxy schema Schema

```txt
#/properties/proxy#/properties/proxy
```

The Http/s proxy for Argus

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [values.schema.json\*](values.schema.json "open original schema") |

## proxy Type

`object` ([The proxy schema](values-properties-the-proxy-schema.md))

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

| Property      | Type     | Required | Nullable       | Defined by                                                                                                                                                                                         |
| :------------ | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [url](#url)   | `string` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-proxy-schema-properties-the-proxy-server-url-schema.md "#/properties/proxy/properties/url#/properties/proxy/properties/url")         |
| [user](#user) | `string` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-proxy-schema-properties-the-proxy-servers-user-schema.md "#/properties/proxy/properties/user#/properties/proxy/properties/user")     |
| [pass](#pass) | `string` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-proxy-schema-properties-the-proxy-servers-password-schema.md "#/properties/proxy/properties/pass#/properties/proxy/properties/pass") |

## url

The Proxy Server's URL

`url`

*   is optional

*   Type: `string` ([The Proxy Server URL Schema](values-properties-the-proxy-schema-properties-the-proxy-server-url-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-proxy-schema-properties-the-proxy-server-url-schema.md "#/properties/proxy/properties/url#/properties/proxy/properties/url")

### url Type

`string` ([The Proxy Server URL Schema](values-properties-the-proxy-schema-properties-the-proxy-server-url-schema.md))

### url Examples

```json
""
```

## user

The Proxy Server's User

`user`

*   is optional

*   Type: `string` ([The Proxy Server's User schema](values-properties-the-proxy-schema-properties-the-proxy-servers-user-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-proxy-schema-properties-the-proxy-servers-user-schema.md "#/properties/proxy/properties/user#/properties/proxy/properties/user")

### user Type

`string` ([The Proxy Server's User schema](values-properties-the-proxy-schema-properties-the-proxy-servers-user-schema.md))

### user Examples

```json
""
```

## pass

The Proxy Server's Password

`pass`

*   is optional

*   Type: `string` ([The Proxy Server's Password schema](values-properties-the-proxy-schema-properties-the-proxy-servers-password-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-proxy-schema-properties-the-proxy-servers-password-schema.md "#/properties/proxy/properties/pass#/properties/proxy/properties/pass")

### pass Type

`string` ([The Proxy Server's Password schema](values-properties-the-proxy-schema-properties-the-proxy-servers-password-schema.md))

### pass Examples

```json
""
```
