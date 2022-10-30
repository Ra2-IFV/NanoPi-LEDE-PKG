# NanoPi-LEDE-PKG
## About this repository
This is an alternative to getting my self-compiled packages, because I don't have enough money to rent a server for downloading :(  
If you can provide a server or have any good ideas, please let me know.  
## How to use this repository
`/etc/opkg/customfeeds.conf`
```
src/gz ifvwrt_base https://github.com/Ra2-IFV/NanoPi-LEDE-PKG/raw/main/base
src/gz ifvwrt_helloworld https://github.com/Ra2-IFV/NanoPi-LEDE-PKG/raw/main/helloworld
src/gz ifvwrt_kenzo https://github.com/Ra2-IFV/NanoPi-LEDE-PKG/raw/main/kenzo
src/gz ifvwrt_luci https://github.com/Ra2-IFV/NanoPi-LEDE-PKG/raw/main/luci
src/gz ifvwrt_packages https://github.com/Ra2-IFV/NanoPi-LEDE-PKG/raw/main/packages
src/gz ifvwrt_routing https://github.com/Ra2-IFV/NanoPi-LEDE-PKG/raw/main/routing
src/gz ifvwrt_small https://github.com/Ra2-IFV/NanoPi-LEDE-PKG/raw/main/small
src/gz ifvwrt_telephony  https://github.com/Ra2-IFV/NanoPi-LEDE-PKG/raw/main/telephony
```
The "core" feeds are provided in [NanoPi-LEDE-CPKG](https://github.com/Ra2-IFV/NanoPi-LEDE-CPKG)
### [WIP] Use my script to generate feeds
