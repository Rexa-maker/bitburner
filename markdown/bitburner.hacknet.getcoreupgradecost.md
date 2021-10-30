<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bitburner](./bitburner.md) &gt; [HackNet](./bitburner.hacknet.md) &gt; [getCoreUpgradeCost](./bitburner.hacknet.getcoreupgradecost.md)

## HackNet.getCoreUpgradeCost() method

Returns the cost of upgrading the number of cores of the specified Hacknet Node by n.

If an invalid value for n is provided, then this function returns 0. If the specified Hacknet Node is already at max level, then Infinity is returned.

<b>Signature:</b>

```typescript
getCoreUpgradeCost(index: number, n: number): number;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  index | number | Index/Identifier of Hacknet Node. |
|  n | number | Number of times to upgrade cores. Must be positive. Rounded to nearest integer. |

<b>Returns:</b>

number

Cost of upgrading the specified Hacknet Node's number of cores.

## Remarks

0 GB
