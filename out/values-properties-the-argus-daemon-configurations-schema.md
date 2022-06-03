# The Argus Daemon configurations Schema Schema

```txt
#/properties/daemons#/properties/daemons
```

The Argus Daemon configurations

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [values.schema.json\*](values.schema.json "open original schema") |

## daemons Type

`object` ([The Argus Daemon configurations Schema](values-properties-the-argus-daemon-configurations-schema.md))

## daemons Default Value

The default value is:

```json
{}
```

## daemons Examples

```json
{
  "lmResourceSweeper": {
    "interval": "10m"
  },
  "lmCacheSync": {
    "interval": "1h"
  },
  "worker": {
    "poolSize": 10
  },
  "watcher": {
    "bulkSyncInterval": "30m",
    "runner": {
      "poolSize": 10,
      "backPressureQueueSizePerRunner": 10
    },
    "sysIpsWaitTimeout": "5m"
  }
}
```

# daemons Properties

| Property                                | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                         |
| :-------------------------------------- | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [lmResourceSweeper](#lmresourcesweeper) | `object` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-argus-daemon-configurations-schema-properties-the-lm-resource-sweeper-configurations-schema.md "#/properties/daemons/properties/lmResourceSweeper#/properties/daemons/properties/lmResourceSweeper") |
| [lmCacheSync](#lmcachesync)             | `object` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-argus-daemon-configurations-schema-properties-the-cache-sync-using-lm-resources-configurations-schema.md "#/properties/daemons/properties/lmCacheSync#/properties/daemons/properties/lmCacheSync")   |
| [worker](#worker)                       | `object` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-argus-daemon-configurations-schema-properties-the-worker-configurations-schema.md "#/properties/daemons/properties/worker#/properties/daemons/properties/worker")                                    |
| [watcher](#watcher)                     | `object` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-argus-daemon-configurations-schema-properties-the-kubernetes-watcher-configurations-schema.md "#/properties/daemons/properties/watcher#/properties/daemons/properties/watcher")                      |

## lmResourceSweeper

The LM Resource sweeper configurations

`lmResourceSweeper`

*   is optional

*   Type: `object` ([The LM Resource sweeper configurations Schema](values-properties-the-argus-daemon-configurations-schema-properties-the-lm-resource-sweeper-configurations-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-argus-daemon-configurations-schema-properties-the-lm-resource-sweeper-configurations-schema.md "#/properties/daemons/properties/lmResourceSweeper#/properties/daemons/properties/lmResourceSweeper")

### lmResourceSweeper Type

`object` ([The LM Resource sweeper configurations Schema](values-properties-the-argus-daemon-configurations-schema-properties-the-lm-resource-sweeper-configurations-schema.md))

### lmResourceSweeper Default Value

The default value is:

```json
{}
```

### lmResourceSweeper Examples

```json
{
  "interval": "10m"
}
```

## lmCacheSync

The Cache Sync using LM resources configurations

`lmCacheSync`

*   is optional

*   Type: `object` ([The Cache Sync using LM resources configurations Schema](values-properties-the-argus-daemon-configurations-schema-properties-the-cache-sync-using-lm-resources-configurations-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-argus-daemon-configurations-schema-properties-the-cache-sync-using-lm-resources-configurations-schema.md "#/properties/daemons/properties/lmCacheSync#/properties/daemons/properties/lmCacheSync")

### lmCacheSync Type

`object` ([The Cache Sync using LM resources configurations Schema](values-properties-the-argus-daemon-configurations-schema-properties-the-cache-sync-using-lm-resources-configurations-schema.md))

### lmCacheSync Default Value

The default value is:

```json
{}
```

### lmCacheSync Examples

```json
{
  "interval": "1h"
}
```

## worker

The Worker configurations

`worker`

*   is optional

*   Type: `object` ([The Worker configurations Schema](values-properties-the-argus-daemon-configurations-schema-properties-the-worker-configurations-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-argus-daemon-configurations-schema-properties-the-worker-configurations-schema.md "#/properties/daemons/properties/worker#/properties/daemons/properties/worker")

### worker Type

`object` ([The Worker configurations Schema](values-properties-the-argus-daemon-configurations-schema-properties-the-worker-configurations-schema.md))

### worker Default Value

The default value is:

```json
{}
```

### worker Examples

```json
{
  "poolSize": 10
}
```

## watcher

The Kubernetes watcher configurations

`watcher`

*   is optional

*   Type: `object` ([The Kubernetes watcher configurations Schema](values-properties-the-argus-daemon-configurations-schema-properties-the-kubernetes-watcher-configurations-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-argus-daemon-configurations-schema-properties-the-kubernetes-watcher-configurations-schema.md "#/properties/daemons/properties/watcher#/properties/daemons/properties/watcher")

### watcher Type

`object` ([The Kubernetes watcher configurations Schema](values-properties-the-argus-daemon-configurations-schema-properties-the-kubernetes-watcher-configurations-schema.md))

### watcher Default Value

The default value is:

```json
{}
```

### watcher Examples

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
