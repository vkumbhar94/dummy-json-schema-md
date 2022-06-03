# The LM Resource sweeper Interval Schema Schema

```txt
#/properties/daemons/properties/lmResourceSweeper/properties/interval#/properties/daemons/properties/lmResourceSweeper/properties/interval
```

The LM Resource sweeper Run Interval Duration

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## interval Type

`string` ([The LM Resource sweeper Interval Schema](values-properties-the-argus-daemon-configurations-schema-properties-the-lm-resource-sweeper-configurations-schema-properties-the-lm-resource-sweeper-interval-schema.md))

## interval Constraints

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^(\d+h)?(\d+m)?(\d+s)?(\d+[u]s)?(\d+ns)?$
```

[try pattern](https://regexr.com/?expression=%5E\(%5Cd%2Bh\)%3F\(%5Cd%2Bm\)%3F\(%5Cd%2Bs\)%3F\(%5Cd%2B%5Bu%5Ds\)%3F\(%5Cd%2Bns\)%3F%24 "try regular expression with regexr.com")

## interval Default Value

The default value is:

```json
"10m"
```

## interval Examples

```json
"0h10m0s"
```
