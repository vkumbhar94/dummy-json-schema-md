# lmCacheSync Schema

```txt
#/properties/daemons/properties/lmCacheSync#/properties/daemons/properties/lmCacheSync
```

Cache Sync using LM resources configurations

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## lmCacheSync Type

`object` ([lmCacheSync](values-properties-daemons-properties-lmcachesync.md))

## lmCacheSync Default Value

The default value is:

```json
{}
```

## lmCacheSync Examples

```json
{
  "interval": "1h"
}
```

# lmCacheSync Properties

| Property              | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                              |
| :-------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [interval](#interval) | `string` | Optional | cannot be null | [Logicmonitor Argus Helm Chart Values Schema](values-properties-daemons-properties-lmcachesync-properties-interval.md "#/properties/daemons/properties/lmCacheSync/properties/interval#/properties/daemons/properties/lmCacheSync/properties/interval") |

## interval

Execution run interval

`interval`

*   is optional

*   Type: `string` ([interval](values-properties-daemons-properties-lmcachesync-properties-interval.md))

*   cannot be null

*   defined in: [Logicmonitor Argus Helm Chart Values Schema](values-properties-daemons-properties-lmcachesync-properties-interval.md "#/properties/daemons/properties/lmCacheSync/properties/interval#/properties/daemons/properties/lmCacheSync/properties/interval")

### interval Type

`string` ([interval](values-properties-daemons-properties-lmcachesync-properties-interval.md))

### interval Constraints

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^(\d+h)?(\d+m)?(\d+s)?(\d+[u]s)?(\d+ns)?$
```

[try pattern](https://regexr.com/?expression=%5E\(%5Cd%2Bh\)%3F\(%5Cd%2Bm\)%3F\(%5Cd%2Bs\)%3F\(%5Cd%2B%5Bu%5Ds\)%3F\(%5Cd%2Bns\)%3F%24 "try regular expression with regexr.com")

### interval Default Value

The default value is:

```json
"1h"
```

### interval Examples

```json
"1h"
```
