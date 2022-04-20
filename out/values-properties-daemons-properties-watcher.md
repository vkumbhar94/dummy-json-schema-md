# watcher Schema

```txt
#/properties/daemons/properties/watcher#/properties/daemons/properties/watcher
```

Kubernetes watcher configurations

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## watcher Type

`object` ([watcher](values-properties-daemons-properties-watcher.md))

## watcher Default Value

The default value is:

```json
{}
```

## watcher Examples

```json
{
  "bulkSyncInterval": "PT30M",
  "runner": {
    "poolSize": 10,
    "backPressureQueueSizePerRunner": 10
  },
  "sysIpsWaitTimeout": "PT5M"
}
```

# watcher Properties

| Property                                | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                        |
| :-------------------------------------- | :------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [bulkSyncInterval](#bulksyncinterval)   | `string` | Optional | cannot be null | [Logicmonitor Argus Helm Chart Values Schema](values-properties-daemons-properties-watcher-properties-bulksyncinterval.md "#/properties/daemons/properties/watcher/properties/bulkSyncInterval#/properties/daemons/properties/watcher/properties/bulkSyncInterval")               |
| [runner](#runner)                       | `object` | Optional | cannot be null | [Logicmonitor Argus Helm Chart Values Schema](values-properties-daemons-properties-watcher-properties-the-runner-schema.md "#/properties/daemons/properties/watcher/properties/runner#/properties/daemons/properties/watcher/properties/runner")                                  |
| [sysIpsWaitTimeout](#sysipswaittimeout) | `string` | Optional | cannot be null | [Logicmonitor Argus Helm Chart Values Schema](values-properties-daemons-properties-watcher-properties-the-sysipswaittimeout-schema.md "#/properties/daemons/properties/watcher/properties/sysIpsWaitTimeout#/properties/daemons/properties/watcher/properties/sysIpsWaitTimeout") |

## bulkSyncInterval

Execution run interval

`bulkSyncInterval`

*   is optional

*   Type: `string` ([bulkSyncInterval](values-properties-daemons-properties-watcher-properties-bulksyncinterval.md))

*   cannot be null

*   defined in: [Logicmonitor Argus Helm Chart Values Schema](values-properties-daemons-properties-watcher-properties-bulksyncinterval.md "#/properties/daemons/properties/watcher/properties/bulkSyncInterval#/properties/daemons/properties/watcher/properties/bulkSyncInterval")

### bulkSyncInterval Type

`string` ([bulkSyncInterval](values-properties-daemons-properties-watcher-properties-bulksyncinterval.md))

### bulkSyncInterval Constraints

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^(\d+h)?(\d+m)?(\d+s)?(\d+[u]s)?(\d+ns)?$
```

[try pattern](https://regexr.com/?expression=%5E\(%5Cd%2Bh\)%3F\(%5Cd%2Bm\)%3F\(%5Cd%2Bs\)%3F\(%5Cd%2B%5Bu%5Ds\)%3F\(%5Cd%2Bns\)%3F%24 "try regular expression with regexr.com")

### bulkSyncInterval Default Value

The default value is:

```json
"30m"
```

### bulkSyncInterval Examples

```json
"30m"
```

## runner

configurations for parallel runners to process watcher events

`runner`

*   is optional

*   Type: `object` ([The runner schema](values-properties-daemons-properties-watcher-properties-the-runner-schema.md))

*   cannot be null

*   defined in: [Logicmonitor Argus Helm Chart Values Schema](values-properties-daemons-properties-watcher-properties-the-runner-schema.md "#/properties/daemons/properties/watcher/properties/runner#/properties/daemons/properties/watcher/properties/runner")

### runner Type

`object` ([The runner schema](values-properties-daemons-properties-watcher-properties-the-runner-schema.md))

### runner Default Value

The default value is:

```json
{}
```

### runner Examples

```json
{
  "poolSize": 10,
  "backPressureQueueSizePerRunner": 10
}
```

## sysIpsWaitTimeout

in case of IP update, need to wait till Logicmonitor portal copies system.hostname value into system.ips

`sysIpsWaitTimeout`

*   is optional

*   Type: `string` ([The sysIpsWaitTimeout schema](values-properties-daemons-properties-watcher-properties-the-sysipswaittimeout-schema.md))

*   cannot be null

*   defined in: [Logicmonitor Argus Helm Chart Values Schema](values-properties-daemons-properties-watcher-properties-the-sysipswaittimeout-schema.md "#/properties/daemons/properties/watcher/properties/sysIpsWaitTimeout#/properties/daemons/properties/watcher/properties/sysIpsWaitTimeout")

### sysIpsWaitTimeout Type

`string` ([The sysIpsWaitTimeout schema](values-properties-daemons-properties-watcher-properties-the-sysipswaittimeout-schema.md))

### sysIpsWaitTimeout Constraints

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^(\d+h)?(\d+m)?(\d+s)?(\d+[u]s)?(\d+ns)?$
```

[try pattern](https://regexr.com/?expression=%5E\(%5Cd%2Bh\)%3F\(%5Cd%2Bm\)%3F\(%5Cd%2Bs\)%3F\(%5Cd%2B%5Bu%5Ds\)%3F\(%5Cd%2Bns\)%3F%24 "try regular expression with regexr.com")

### sysIpsWaitTimeout Default Value

The default value is:

```json
"5m"
```

### sysIpsWaitTimeout Examples

```json
"5m"
```
