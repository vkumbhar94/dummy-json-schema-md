# The sysIpsWaitTimeout schema Schema

```txt
#/properties/daemons/properties/watcher/properties/sysIpsWaitTimeout#/properties/daemons/properties/watcher/properties/sysIpsWaitTimeout
```

in case of IP update, need to wait till Logicmonitor portal copies system.hostname value into system.ips

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## sysIpsWaitTimeout Type

`string` ([The sysIpsWaitTimeout schema](values-properties-daemons-properties-watcher-properties-the-sysipswaittimeout-schema.md))

## sysIpsWaitTimeout Constraints

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^(\d+h)?(\d+m)?(\d+s)?(\d+[u]s)?(\d+ns)?$
```

[try pattern](https://regexr.com/?expression=%5E\(%5Cd%2Bh\)%3F\(%5Cd%2Bm\)%3F\(%5Cd%2Bs\)%3F\(%5Cd%2B%5Bu%5Ds\)%3F\(%5Cd%2Bns\)%3F%24 "try regular expression with regexr.com")

## sysIpsWaitTimeout Default Value

The default value is:

```json
"5m"
```

## sysIpsWaitTimeout Examples

```json
"5m"
```
