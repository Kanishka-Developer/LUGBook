# OpenWrt 22.03.4 Released
---

```
  _______                     ________        __
 |       |.-----.-----.-----.|  |  |  |.----.|  |_
 |   -   ||  _  |  -__|     ||  |  |  ||   _||   _|
 |_______||   __|_____|__|__||________||__|  |____|
          |__| W I R E L E S S   F R E E D O M
 -----------------------------------------------------
 OpenWrt 22.03.4, r20123-38ccc47687
 -----------------------------------------------------
 ```

## OpenWrt 22.03.4

The OpenWrt community is proud to announce the newest point release of the
OpenWrt 22.03 stable version series. It fixes security issues, improves device
support, and brings a few bug fixes.

Get OpenWrt Firmware at:

* https://firmware-selector.openwrt.org
* https://downloads.openwrt.org/releases/22.03.4/
* https://sysupgrade.openwrt.org

### Main changes between OpenWrt 22.03.3 and OpenWrt 22.03.4

Only the main changes are listed below. See [changelog-22.03.4](https://openwrt.org/releases/22.03/changelog-22.03.4) for the full changelog.

#### Security fixes

* CVE-2022-4304
* CVE-2022-4450
* CVE-2022-47522
* CVE-2022-47938
* CVE-2022-47939
* CVE-2022-47940
* CVE-2022-47941
* CVE-2022-47942
* CVE-2022-47943
* CVE-2023-0215
* CVE-2023-0286

#### Added devices

* 05ec70f kernel: add support for XMC XM25QH64C
* 0657576 ath79: add LTE led for GL.iNet GL-XE300
* 788a0cf mpc85xx: add support for Watchguard Firebox T10
* 3c6692b ramips: add support for TP-Link Archer AX23 v1
* f5db04e ramips: add support for Mercusys MR70X
* 711e45e ramips: add support for D-Link DAP-X1860 A1

#### Fixed issues

* #7757 via 4b7f9e4 lantiq-xrx200: fix wan LED on o2 box 6431
* #9491 via fea7478 iproute2: add missing libbpf dependency
* #10871 via 3bc6d2a tools/dosfstools: fix PKG_SOURCE
* #11701 via 50d707e lantiq: fix lzma-loader for Netgear DGN 3500(B)

#### Improvements

38ccc47 imagebuilder: allow to specific ROOTFS_PARTSIZE
7531ef7 sdk: expose PATENTED an NLS build options*

#### Core components update

f61c5cf kernel: bump 5.10 to 5.10.176
863288b mac80211: Update to version 5.15.92-1
7c10b7b CI: build: fix external toolchain use with release tag tests

### Upgrading to 22.03.4

Sysupgrade can be used to upgrade a device from OpenWrt 21.02 or 22.03 to
22.03.4 and configuration will be preserved in most cases.

> **Warning**\
> Sysupgrade from 19.07 to 22.03.x is not supported.

> **Warning**\
>There is no migration path for targets that switched from swconfig to [DSA](https://openwrt.org/docs/guide-user/network/dsa/start). In that case, sysupgrade will refuse to proceed with an appropriate error message: Image version mismatch. image 1.1 device 1.0 Please wipe config during upgrade (force required) or reinstall. Config cannot be migrated from swconfig to DSA Image check failed

### Known Issues
* [#12232](https://github.com/openwrt/openwrt/issues/12232) Linksys MR8300 may break after the update, wait for the next service release!