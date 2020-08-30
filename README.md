# n2n v2 for openwrt with luci

Copy from coolsnowwolf's [code](https://github.com/coolsnowwolf/lede).

## How to use

Add "src-git n2n https://github.com/alecthw/openwrt-n2n.git" to feeds.conf.default.

``` bash
./scripts/feeds clean
./scripts/feeds update -a
./scripts/feeds install -a
```

Checked `luci-app-n2n_v2` in menuconfig.
