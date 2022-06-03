# The Kubernetes watcher configurations Schema Schema

```txt
#/properties/daemons/properties/watcher#/properties/daemons/properties/watcher
```

The Kubernetes watcher configurations

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [values.schema.json\*](values.schema.json "open original schema") |

## watcher Type

`object` ([The Kubernetes watcher configurations Schema](values-properties-the-argus-daemon-configurations-schema-properties-the-kubernetes-watcher-configurations-schema.md))

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

| Property                                | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                      |
| :-------------------------------------- | :------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [bulkSyncInterval](#bulksyncinterval)   | `string` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-argus-daemon-configurations-schema-properties-the-kubernetes-watcher-configurations-schema-properties-bulksyncinterval.md "#/properties/daemons/properties/watcher/properties/bulkSyncInterval#/properties/daemons/properties/watcher/properties/bulkSyncInterval")               |
| [runner](#runner)                       | `object` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-argus-daemon-configurations-schema-properties-the-kubernetes-watcher-configurations-schema-properties-the-runner-configurations-schema.md "#/properties/daemons/properties/watcher/properties/runner#/properties/daemons/properties/watcher/properties/runner")                   |
| [sysIpsWaitTimeout](#sysipswaittimeout) | `string` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-argus-daemon-configurations-schema-properties-the-kubernetes-watcher-configurations-schema-properties-the-sysipswaittimeout-schema.md "#/properties/daemons/properties/watcher/properties/sysIpsWaitTimeout#/properties/daemons/properties/watcher/properties/sysIpsWaitTimeout") |

## bulkSyncInterval

The Bulk Discovery Run Interval Duration

`bulkSyncInterval`

*   is optional

*   Type: `string` ([bulkSyncInterval](values-properties-the-argus-daemon-configurations-schema-properties-the-kubernetes-watcher-configurations-schema-properties-bulksyncinterval.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-argus-daemon-configurations-schema-properties-the-kubernetes-watcher-configurations-schema-properties-bulksyncinterval.md "#/properties/daemons/properties/watcher/properties/bulkSyncInterval#/properties/daemons/properties/watcher/properties/bulkSyncInterval")

### bulkSyncInterval Type

`string` ([bulkSyncInterval](values-properties-the-argus-daemon-configurations-schema-properties-the-kubernetes-watcher-configurations-schema-properties-bulksyncinterval.md))

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
"0h30m0s"
```

## runner

The configurations for parallel runners to process watcher events

`runner`

*   is optional

*   Type: `object` ([The runner configurations schema](values-properties-the-argus-daemon-configurations-schema-properties-the-kubernetes-watcher-configurations-schema-properties-the-runner-configurations-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-argus-daemon-configurations-schema-properties-the-kubernetes-watcher-configurations-schema-properties-the-runner-configurations-schema.md "#/properties/daemons/properties/watcher/properties/runner#/properties/daemons/properties/watcher/properties/runner")

### runner Type

`object` ([The runner configurations schema](values-properties-the-argus-daemon-configurations-schema-properties-the-kubernetes-watcher-configurations-schema-properties-the-runner-configurations-schema.md))

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

The sysIpsWaitTimeout is a timout for argus to wait till Logicmonitor portal copies system.hostname value into system.ips for updated IP of resource

`sysIpsWaitTimeout`

*   is optional

*   Type: `string` ([The sysIpsWaitTimeout schema](values-properties-the-argus-daemon-configurations-schema-properties-the-kubernetes-watcher-configurations-schema-properties-the-sysipswaittimeout-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-argus-daemon-configurations-schema-properties-the-kubernetes-watcher-configurations-schema-properties-the-sysipswaittimeout-schema.md "#/properties/daemons/properties/watcher/properties/sysIpsWaitTimeout#/properties/daemons/properties/watcher/properties/sysIpsWaitTimeout")

### sysIpsWaitTimeout Type

`string` ([The sysIpsWaitTimeout schema](values-properties-the-argus-daemon-configurations-schema-properties-the-kubernetes-watcher-configurations-schema-properties-the-sysipswaittimeout-schema.md))

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
"0h5m0s"
```
