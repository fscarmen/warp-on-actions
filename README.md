# warp-on-actions

* * *

### Usage example:

```
  - name: Set up WARP
    uses: fscarmen/warp-on-actions@v1.4
    with:
      stack: dual        # Optional. Support [ ipv4, ipv6, dual ]. Default is dual.
      mode: wireguard    # Optional. Support [ wireguard, client ]. Default is wireguard.
```

### Input Parameters

| Parameter | **Mandatory**/**Optional** | Description |
| --------- | -------- | ----------- |
| stack | **Optional** | WARP stack: one of `ipv4`, `ipv6`,`dual`. Default is `dual`. |
| mode  | **Optional** | WARP mode: one of `wireguard`, `client`. Default is `wireguard`. |