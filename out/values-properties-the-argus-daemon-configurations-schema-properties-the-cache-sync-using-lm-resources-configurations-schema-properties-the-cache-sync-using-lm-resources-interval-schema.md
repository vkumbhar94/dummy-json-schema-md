# The Cache Sync using LM resources Interval Schema Schema

```txt
#/properties/daemons/properties/lmCacheSync/properties/interval#/properties/daemons/properties/lmCacheSync/properties/interval
```

The Cache Sync using LM resources Run Interval Duration

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## interval Type

`string` ([The Cache Sync using LM resources Interval Schema](values-properties-the-argus-daemon-configurations-schema-properties-the-cache-sync-using-lm-resources-configurations-schema-properties-the-cache-sync-using-lm-resources-interval-schema.md))

## interval Constraints

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^(\d+h)?(\d+m)?(\d+s)?(\d+[u]s)?(\d+ns)?$
```

[try pattern](https://regexr.com/?expression=%5E\(%5Cd%2Bh\)%3F\(%5Cd%2Bm\)%3F\(%5Cd%2Bs\)%3F\(%5Cd%2B%5Bu%5Ds\)%3F\(%5Cd%2Bns\)%3F%24 "try regular expression with regexr.com")

## interval Default Value

The default value is:

```json
"1h"
```

## interval Examples

```json
"1h0m0s"
```
