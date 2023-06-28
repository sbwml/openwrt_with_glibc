<div align="center">
<img src="https://github.com/sbwml/openwrt_with_glibc/assets/16485166/1a8d8fb0-693a-4225-b4e6-10e629067831" height="120.0px"/>
<h3 align="center">NanoPi R4S/R5S/R5C based on OpenWrt-23.05 with GNU C Library</h3>
<h3 align="center">Simultaneously compatible with GNU C & MUSL Library</h3>
</div>

## 

### Build

nanopi-r4s
```bash
USE_GLIBC=y bash <(curl -sS https://init2.cooluc.com/build.sh) rc2 nanopi-r4s
```

nanopi-r5s/r5c
```bash
USE_GLIBC=y bash <(curl -sS https://init2.cooluc.com/build.sh) rc2 nanopi-r5s
```
