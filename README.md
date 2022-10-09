# NanoPi-LEDE-PKG
## About this repository
This is an alternative to getting my self-compiled packages, because I don't have enough money to rent a server for downloading :(  
If you can provide a server or have any good ideas, please let me know.  
## How to use this repository
First, check your version number. For example:  
```
$ ssh root@192.168.2.1
     _________
    /        /\      _    ___ ___  ___
   /  LE    /  \    | |  | __|   \| __|
  /    DE  /    \   | |__| _|| |) | _|
 /________/  LE  \  |____|___|___/|___|
 \        \   DE /
  \    LE  \    /  -------------------------------------------
   \  DE    \  /    IFVWRT v1.0.0-0911 STABLE
    \________\/    -------------------------------------------

root@IFVWRT:~#
```
Here, you can see the version number is `v1.0.0-0911`. So you should add your feeds like this:  
`/etc/opkg/customfeeds.conf`
```
src/gz ifvwrt_core https://github.com/Ra2-IFV/NanoPi-LEDE-PKG/raw/main/v1.0.0-0911/Core
src/gz ifvwrt_base https://github.com/Ra2-IFV/NanoPi-LEDE-PKG/raw/main/v1.0.0-0911/Main/base
src/gz ifvwrt_helloworld https://github.com/Ra2-IFV/NanoPi-LEDE-PKG/raw/main/v1.0.0-0911/Main/helloworld
src/gz ifvwrt_kenzo https://github.com/Ra2-IFV/NanoPi-LEDE-PKG/raw/main/v1.0.0-0911/Main/kenzo
src/gz ifvwrt_luci https://github.com/Ra2-IFV/NanoPi-LEDE-PKG/raw/main/v1.0.0-0911/Main/luci
src/gz ifvwrt_packages https://github.com/Ra2-IFV/NanoPi-LEDE-PKG/raw/main/v1.0.0-0911/Main/packages
src/gz ifvwrt_routing https://github.com/Ra2-IFV/NanoPi-LEDE-PKG/raw/main/v1.0.0-0911/Main/routing
src/gz ifvwrt_small https://github.com/Ra2-IFV/NanoPi-LEDE-PKG/raw/main/v1.0.0-0911/Main/small
src/gz ifvwrt_telephony  https://github.com/Ra2-IFV/NanoPi-LEDE-PKG/raw/main/v1.0.0-0911/Main/telephony
```
### [WIP] Use my script to generate feeds
