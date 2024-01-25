# warp-on-actions

* * *

Usage:
* client warp+doh mode
```
  - name: Set up WARP
    uses: fscarmen/warp-on-actions@v1.0
    with:
      mode: client  # Optional, default
```

* wireguard
```
  - name: Set up WARP
    uses: fscarmen/warp-on-actions@v1.0
    with:
      mode: wireguard
```