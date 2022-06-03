# bulkSyncInterval Schema

```txt
#/properties/daemons/properties/watcher/properties/bulkSyncInterval#/properties/daemons/properties/watcher/properties/bulkSyncInterval
```

The Bulk Discovery Run Interval Duration

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## bulkSyncInterval Type

`string` ([bulkSyncInterval](values-properties-the-argus-daemon-configurations-schema-properties-the-kubernetes-watcher-configurations-schema-properties-bulksyncinterval.md))

## bulkSyncInterval Constraints

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^(\d+h)?(\d+m)?(\d+s)?(\d+[u]s)?(\d+ns)?$
```

[try pattern](https://regexr.com/?expression=%5E\(%5Cd%2Bh\)%3F\(%5Cd%2Bm\)%3F\(%5Cd%2Bs\)%3F\(%5Cd%2B%5Bu%5Ds\)%3F\(%5Cd%2Bns\)%3F%24 "try regular expression with regexr.com")

## bulkSyncInterval Default Value

The default value is:

```json
"30m"
```

## bulkSyncInterval Examples

```json
"0h30m0s"
```
