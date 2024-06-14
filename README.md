<div align="center">
<img src="https://github.com/sbwml/openwrt_with_glibc/assets/16485166/1a8d8fb0-693a-4225-b4e6-10e629067831" height="120.0px"/>
<h3 align="center">NanoPi R4S/R5S/R5C & x86_64 based on OpenWrt-23.05 with GNU C Library</h3>
</div>

##
<div align="center">
<h3 align="center">OpenWrt GNU C Library Test</h3>
</div>

##

build flags:
```bash
export USE_GLIBC=y BUILD_FAST=y KERNEL_CLANG_LTO=y ENABLE_BPF=y ENABLE_LRNG=y USE_GCC15=y ENABLE_LTO=y USE_MOLD=y
```

## 

armsr/armv8:
```bash
bash <(curl -sS https://init2.cooluc.com/build.sh) rc2 armv8
```

nanopi-r4s:
```bash
bash <(curl -sS https://init2.cooluc.com/build.sh) rc2 nanopi-r4s
```

nanopi-r5s/r5c:
```bash
bash <(curl -sS https://init2.cooluc.com/build.sh) rc2 nanopi-r5s
```

x86_64:
```bash
bash <(curl -sS https://init2.cooluc.com/build.sh) rc2 x86_64
```

##

PS:
- ⚠ Unable to install packages from OpenWrt source using opkg because the OpenWrt package repository is built based on the musl library, which is incompatible with glibc.
