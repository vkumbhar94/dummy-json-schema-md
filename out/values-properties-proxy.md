# proxy Schema

```txt
#/properties/proxy#/properties/proxy
```

Http/s proxy

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## proxy Type

`object` ([proxy](values-properties-proxy.md))

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

| Property      | Type     | Required | Nullable       | Defined by                                                                                                                                                                  |
| :------------ | :------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [url](#url)   | `string` | Optional | cannot be null | [Logicmonitor Argus Helm Chart Values Schema](values-properties-proxy-properties-url.md "#/properties/proxy/properties/url#/properties/proxy/properties/url")               |
| [user](#user) | `string` | Optional | cannot be null | [Logicmonitor Argus Helm Chart Values Schema](values-properties-proxy-properties-the-user-schema.md "#/properties/proxy/properties/user#/properties/proxy/properties/user") |
| [pass](#pass) | `string` | Optional | cannot be null | [Logicmonitor Argus Helm Chart Values Schema](values-properties-proxy-properties-pass.md "#/properties/proxy/properties/pass#/properties/proxy/properties/pass")            |

## url

Proxy service endpoint

`url`

*   is optional

*   Type: `string` ([url](values-properties-proxy-properties-url.md))

*   cannot be null

*   defined in: [Logicmonitor Argus Helm Chart Values Schema](values-properties-proxy-properties-url.md "#/properties/proxy/properties/url#/properties/proxy/properties/url")

### url Type

`string` ([url](values-properties-proxy-properties-url.md))

### url Examples

```json
""
```

## user

Proxy service user

`user`

*   is optional

*   Type: `string` ([The user schema](values-properties-proxy-properties-the-user-schema.md))

*   cannot be null

*   defined in: [Logicmonitor Argus Helm Chart Values Schema](values-properties-proxy-properties-the-user-schema.md "#/properties/proxy/properties/user#/properties/proxy/properties/user")

### user Type

`string` ([The user schema](values-properties-proxy-properties-the-user-schema.md))

### user Examples

```json
""
```

## pass

Proxy service password

`pass`

*   is optional

*   Type: `string` ([pass](values-properties-proxy-properties-pass.md))

*   cannot be null

*   defined in: [Logicmonitor Argus Helm Chart Values Schema](values-properties-proxy-properties-pass.md "#/properties/proxy/properties/pass#/properties/proxy/properties/pass")

### pass Type

`string` ([pass](values-properties-proxy-properties-pass.md))

### pass Examples

```json
""
```
