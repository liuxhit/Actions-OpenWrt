# Actions-OpenWrt

[![GitHub](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square)](https://github.com/P3TERX/Actions-OpenWrt/blob/master/LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/P3TERX/Actions-OpenWrt.svg?style=flat-square&label=Stars)](https://github.com/P3TERX/Actions-OpenWrt/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/P3TERX/Actions-OpenWrt.svg?style=flat-square&label=Fork)](https://github.com/P3TERX/Actions-OpenWrt/fork)

Build OpenWrt using GitHub Actions

## Usage

- Sign up for [GitHub Actions](https://github.com/features/actions/signup)
- Fork [this GitHub repository](https://github.com/P3TERX/Actions-OpenWrt)
- Generate `.config` files using [Lean's OpenWrt](https://github.com/coolsnowwolf/lede) source code.
- Push `.config` file to the GitHub repository, and the build starts automatically.Progress can be viewed on the Actions page.
- When the build is complete, click the `Artifacts` button in the upper right corner of the Actions page to download the binaries.

[Read the details in my blog (in Chinese) | 中文教程](https://p3terx.com/archives/build-openwrt-with-github-actions.html)

---
## 本fork改动如下
* 路由器型号：[K2P A1/A2](https://openwrt.org/toh/hwdata/phicomm/phicomm_k2p)
* 添加闭源无线驱动：[仓库](https://github.com/MeIsReallyBa/k2p-openwrt-mt7615_5.0.2.0)
* 添加锐捷认证软件包：[minieap](https://github.com/ysc3839/openwrt-minieap) [luci-proto-minieap](https://github.com/ysc3839/luci-proto-minieap)