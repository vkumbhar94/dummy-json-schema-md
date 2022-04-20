# lmResourceSweeper Schema

```txt
#/properties/daemons/properties/lmResourceSweeper#/properties/daemons/properties/lmResourceSweeper
```

LM Resource sweeper configurations

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## lmResourceSweeper Type

`object` ([lmResourceSweeper](values-properties-daemons-properties-lmresourcesweeper.md))

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

| Property              | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                |
| :-------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [interval](#interval) | `string` | Optional | cannot be null | [Logicmonitor Argus Helm Chart Values Schema](values-properties-daemons-properties-lmresourcesweeper-properties-interval.md "#/properties/daemons/properties/lmResourceSweeper/properties/interval#/properties/daemons/properties/lmResourceSweeper/properties/interval") |

## interval

Execution run interval

`interval`

*   is optional

*   Type: `string` ([interval](values-properties-daemons-properties-lmresourcesweeper-properties-interval.md))

*   cannot be null

*   defined in: [Logicmonitor Argus Helm Chart Values Schema](values-properties-daemons-properties-lmresourcesweeper-properties-interval.md "#/properties/daemons/properties/lmResourceSweeper/properties/interval#/properties/daemons/properties/lmResourceSweeper/properties/interval")

### interval Type

`string` ([interval](values-properties-daemons-properties-lmresourcesweeper-properties-interval.md))

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
"10m"
```
