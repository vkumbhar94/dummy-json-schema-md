# collectorsetcontroller Schema

```txt
#/properties/collectorsetcontroller#/properties/collectorsetcontroller
```

Collectorset-Controller Configurations

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## collectorsetcontroller Type

`object` ([collectorsetcontroller](values-properties-collectorsetcontroller.md))

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

| Property            | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                      |
| :------------------ | :-------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [address](#address) | `string`  | Optional | cannot be null | [The root schema](values-properties-collectorsetcontroller-properties-collectorsetcontroller.md "#/properties/collectorsetcontroller/properties/address#/properties/collectorsetcontroller/properties/address") |
| [port](#port)       | `integer` | Optional | cannot be null | [The root schema](values-properties-collectorsetcontroller-properties-port.md "#/properties/collectorsetcontroller/properties/port#/properties/collectorsetcontroller/properties/port")                         |

## address

Collectorset-controller grpc service address

`address`

*   is optional

*   Type: `string` ([collectorsetController](values-properties-collectorsetcontroller-properties-collectorsetcontroller.md))

*   cannot be null

*   defined in: [The root schema](values-properties-collectorsetcontroller-properties-collectorsetcontroller.md "#/properties/collectorsetcontroller/properties/address#/properties/collectorsetcontroller/properties/address")

### address Type

`string` ([collectorsetController](values-properties-collectorsetcontroller-properties-collectorsetcontroller.md))

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

Port service exposes

`port`

*   is optional

*   Type: `integer` ([port](values-properties-collectorsetcontroller-properties-port.md))

*   cannot be null

*   defined in: [The root schema](values-properties-collectorsetcontroller-properties-port.md "#/properties/collectorsetcontroller/properties/port#/properties/collectorsetcontroller/properties/port")

### port Type

`integer` ([port](values-properties-collectorsetcontroller-properties-port.md))

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
