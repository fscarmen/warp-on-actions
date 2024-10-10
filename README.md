# warp-on-actions

* * *

### Usage example:
client warp+doh mode
```
  - name: Set up WARP
    uses: fscarmen/warp-on-actions@v1.2
    with:
      stack: dual   # Optional. Support [ ipv4, ipv6, dual ]. Default is dual.
```

### Input Parameters

| Parameter | **Mandatory**/**Optional** | Description |
| --------- | -------- | ----------- |
| stack | **Optional** | WARP stack: one of `ipv4`, `ipv6`,`dual`. Default is `dual`. |