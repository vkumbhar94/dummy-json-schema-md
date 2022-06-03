# The collectorsetcontroller schema Schema

```txt
#/properties/collectorsetcontroller#/properties/collectorsetcontroller
```

The Collectorset-Controller Configurations

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [values.schema.json\*](values.schema.json "open original schema") |

## collectorsetcontroller Type

`object` ([The collectorsetcontroller schema](values-properties-the-collectorsetcontroller-schema.md))

## collectorsetcontroller Default Value

The default value is:

```json
{}
```

## collectorsetcontroller Examples

```json
{
  "address": "collectorset-controller",
  "port": 50000
}
```

# collectorsetcontroller Properties

| Property            | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                                          |
| :------------------ | :-------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [address](#address) | `string`  | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-collectorsetcontroller-schema-properties-the-collectorsetcontroller-address-schema.md "#/properties/collectorsetcontroller/properties/address#/properties/collectorsetcontroller/properties/address") |
| [port](#port)       | `integer` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-collectorsetcontroller-schema-properties-port.md "#/properties/collectorsetcontroller/properties/port#/properties/collectorsetcontroller/properties/port")                                            |

## address

The Collectorset-controller grpc service address

`address`

*   is optional

*   Type: `string` ([The CollectorsetController Address Schema](values-properties-the-collectorsetcontroller-schema-properties-the-collectorsetcontroller-address-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-collectorsetcontroller-schema-properties-the-collectorsetcontroller-address-schema.md "#/properties/collectorsetcontroller/properties/address#/properties/collectorsetcontroller/properties/address")

### address Type

`string` ([The CollectorsetController Address Schema](values-properties-the-collectorsetcontroller-schema-properties-the-collectorsetcontroller-address-schema.md))

### address Constraints

**minimum length**: the minimum number of characters for this string is: `1`

### address Default Value

The default value is:

```json
"collectorset-controller"
```

### address Examples

```json
"collectorset-controller"
```

## port

The Collectorset-controller grpc service port

`port`

*   is optional

*   Type: `integer` ([port](values-properties-the-collectorsetcontroller-schema-properties-port.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-collectorsetcontroller-schema-properties-port.md "#/properties/collectorsetcontroller/properties/port#/properties/collectorsetcontroller/properties/port")

### port Type

`integer` ([port](values-properties-the-collectorsetcontroller-schema-properties-port.md))

### port Constraints

**minimum**: the value of this number must greater than or equal to: `2`

### port Default Value

The default value is:

```json
50000
```

### port Examples

```json
50000
```
