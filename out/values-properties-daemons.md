# daemons Schema

```txt
#/properties/daemons#/properties/daemons
```

Daemon configurations

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## daemons Type

`object` ([daemons](values-properties-daemons.md))

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

| Property                                | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                    |
| :-------------------------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [lmResourceSweeper](#lmresourcesweeper) | `object` | Optional | cannot be null | [Logicmonitor Argus Helm Chart Values Schema](values-properties-daemons-properties-lmresourcesweeper.md "#/properties/daemons/properties/lmResourceSweeper#/properties/daemons/properties/lmResourceSweeper") |
| [lmCacheSync](#lmcachesync)             | `object` | Optional | cannot be null | [Logicmonitor Argus Helm Chart Values Schema](values-properties-daemons-properties-lmcachesync.md "#/properties/daemons/properties/lmCacheSync#/properties/daemons/properties/lmCacheSync")                   |
| [worker](#worker)                       | `object` | Optional | cannot be null | [Logicmonitor Argus Helm Chart Values Schema](values-properties-daemons-properties-worker.md "#/properties/daemons/properties/worker#/properties/daemons/properties/worker")                                  |
| [watcher](#watcher)                     | `object` | Optional | cannot be null | [Logicmonitor Argus Helm Chart Values Schema](values-properties-daemons-properties-watcher.md "#/properties/daemons/properties/watcher#/properties/daemons/properties/watcher")                               |

## lmResourceSweeper

LM Resource sweeper configurations

`lmResourceSweeper`

*   is optional

*   Type: `object` ([lmResourceSweeper](values-properties-daemons-properties-lmresourcesweeper.md))

*   cannot be null

*   defined in: [Logicmonitor Argus Helm Chart Values Schema](values-properties-daemons-properties-lmresourcesweeper.md "#/properties/daemons/properties/lmResourceSweeper#/properties/daemons/properties/lmResourceSweeper")

### lmResourceSweeper Type

`object` ([lmResourceSweeper](values-properties-daemons-properties-lmresourcesweeper.md))

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

Cache Sync using LM resources configurations

`lmCacheSync`

*   is optional

*   Type: `object` ([lmCacheSync](values-properties-daemons-properties-lmcachesync.md))

*   cannot be null

*   defined in: [Logicmonitor Argus Helm Chart Values Schema](values-properties-daemons-properties-lmcachesync.md "#/properties/daemons/properties/lmCacheSync#/properties/daemons/properties/lmCacheSync")

### lmCacheSync Type

`object` ([lmCacheSync](values-properties-daemons-properties-lmcachesync.md))

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

Worker configurations

`worker`

*   is optional

*   Type: `object` ([worker](values-properties-daemons-properties-worker.md))

*   cannot be null

*   defined in: [Logicmonitor Argus Helm Chart Values Schema](values-properties-daemons-properties-worker.md "#/properties/daemons/properties/worker#/properties/daemons/properties/worker")

### worker Type

`object` ([worker](values-properties-daemons-properties-worker.md))

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

Kubernetes watcher configurations

`watcher`

*   is optional

*   Type: `object` ([watcher](values-properties-daemons-properties-watcher.md))

*   cannot be null

*   defined in: [Logicmonitor Argus Helm Chart Values Schema](values-properties-daemons-properties-watcher.md "#/properties/daemons/properties/watcher#/properties/daemons/properties/watcher")

### watcher Type

`object` ([watcher](values-properties-daemons-properties-watcher.md))

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
