# The LM Resource sweeper configurations Schema Schema

```txt
#/properties/daemons/properties/lmResourceSweeper#/properties/daemons/properties/lmResourceSweeper
```

The LM Resource sweeper configurations

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [values.schema.json\*](values.schema.json "open original schema") |

## lmResourceSweeper Type

`object` ([The LM Resource sweeper configurations Schema](values-properties-the-argus-daemon-configurations-schema-properties-the-lm-resource-sweeper-configurations-schema.md))

## lmResourceSweeper Default Value

The default value is:

```json
{}
```

## lmResourceSweeper Examples

```json
{
  "interval": "10m"
}
```

# lmResourceSweeper Properties

| Property              | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                                    |
| :-------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [interval](#interval) | `string` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-argus-daemon-configurations-schema-properties-the-lm-resource-sweeper-configurations-schema-properties-the-lm-resource-sweeper-interval-schema.md "#/properties/daemons/properties/lmResourceSweeper/properties/interval#/properties/daemons/properties/lmResourceSweeper/properties/interval") |

## interval

The LM Resource sweeper Run Interval Duration

`interval`

*   is optional

*   Type: `string` ([The LM Resource sweeper Interval Schema](values-properties-the-argus-daemon-configurations-schema-properties-the-lm-resource-sweeper-configurations-schema-properties-the-lm-resource-sweeper-interval-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-argus-daemon-configurations-schema-properties-the-lm-resource-sweeper-configurations-schema-properties-the-lm-resource-sweeper-interval-schema.md "#/properties/daemons/properties/lmResourceSweeper/properties/interval#/properties/daemons/properties/lmResourceSweeper/properties/interval")

### interval Type

`string` ([The LM Resource sweeper Interval Schema](values-properties-the-argus-daemon-configurations-schema-properties-the-lm-resource-sweeper-configurations-schema-properties-the-lm-resource-sweeper-interval-schema.md))

### interval Constraints

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^(\d+h)?(\d+m)?(\d+s)?(\d+[u]s)?(\d+ns)?$
```

[try pattern](https://regexr.com/?expression=%5E\(%5Cd%2Bh\)%3F\(%5Cd%2Bm\)%3F\(%5Cd%2Bs\)%3F\(%5Cd%2B%5Bu%5Ds\)%3F\(%5Cd%2Bns\)%3F%24 "try regular expression with regexr.com")

### interval Default Value

The default value is:

```json
"10m"
```

### interval Examples

```json
"0h10m0s"
```
