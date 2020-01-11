# rust-unofficial/awesome-rust [![explain]][source] [![translate-svg]][translate-list]

<!-- [![size-img]][size] -->

[explain]: http://llever.com/explain.svg
[source]: https://github.com/chinanf-boy/Source-Explain
[translate-svg]: http://llever.com/translate.svg
[translate-list]: https://github.com/chinanf-boy/chinese-translate-list
[size-img]: https://packagephobia.now.sh/badge?p=Name
[size]: https://packagephobia.now.sh/result?p=Name

「 Rust 代码和资源的精选列表. 」

[中文](./readme.md) | [english](https://github.com/rust-unofficial/awesome-rust)

---

## 更新 ✅

<!-- doc-templite START generated -->
<!--  repo = 'rust-unofficial/awesome-rust' -->
<!--  commit = '4fee3208ae5812875767510f30aa62a48c04bfab' -->
<!--  time = '2019-09-05' -->
翻译的原文 | 与日期 | 最新更新 | 更多
---|---|---|---
[commit] | ⏰ 2019-09-05 | ![last] | [中文翻译][translate-list]

[last]: https://img.shields.io/github/last-commit/rust-unofficial/awesome-rust.svg
[commit]: https://github.com/rust-unofficial/awesome-rust/tree/4fee3208ae5812875767510f30aa62a48c04bfab

<!-- doc-templite END generated -->

- [x] readme.md

### 贡献

欢迎 👏 勘误/校对/更新贡献 😊 [具体贡献请看](https://github.com/chinanf-boy/chinese-translate-list#贡献)

## 生活

[If help, **buy** me coffee —— 营养跟不上了，给我来瓶营养快线吧! 💰](https://github.com/chinanf-boy/live-need-money)

---

# 真棒螃蟹[<img src="https://api.travis-ci.org/rust-unofficial/awesome-rust.svg?branch=master">](https://travis-ci.org/rust-unofficial/awesome-rust)

Rust 代码和资源的精选列表。

> (译者) 螃蟹 🦀️ == Rust；箱子 📦 == crate；绑定 == bindings；

> (译者) 绑定的一般含义是，将其他 (多数为) C/C++ 库，通过用 Rust 重新包装，给出类似/相同的 API，这样从此，就多了个绑定着 C/C++库的 Rust 箱子。

如果您想贡献，请阅读[this](CONTRIBUTING.md)。

## 目录

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [应用](#%E5%BA%94%E7%94%A8)
  - [音频](#%E9%9F%B3%E9%A2%91)
  - [加密货币](#%E5%8A%A0%E5%AF%86%E8%B4%A7%E5%B8%81)
  - [数据库](#%E6%95%B0%E6%8D%AE%E5%BA%93)
  - [仿真器](#%E4%BB%BF%E7%9C%9F%E5%99%A8)
  - [游戏](#%E6%B8%B8%E6%88%8F)
  - [图像](#%E5%9B%BE%E5%83%8F)
  - [工业自动化](#%E5%B7%A5%E4%B8%9A%E8%87%AA%E5%8A%A8%E5%8C%96)
  - [可观察](#%E5%8F%AF%E8%A7%82%E5%AF%9F)
  - [操作系统](#%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F)
  - [生产工具](#%E7%94%9F%E4%BA%A7%E5%B7%A5%E5%85%B7)
  - [安全工具](#%E5%AE%89%E5%85%A8%E5%B7%A5%E5%85%B7)
  - [系统工具](#%E7%B3%BB%E7%BB%9F%E5%B7%A5%E5%85%B7)
  - [文本编辑](#%E6%96%87%E6%9C%AC%E7%BC%96%E8%BE%91)
  - [文本处理](#%E6%96%87%E6%9C%AC%E5%A4%84%E7%90%86)
  - [实用](#%E5%AE%9E%E7%94%A8)
  - [视频](#%E8%A7%86%E9%A2%91)
  - [虚拟化](#%E8%99%9A%E6%8B%9F%E5%8C%96)
  - [窗口管理员](#%E7%AA%97%E5%8F%A3%E7%AE%A1%E7%90%86%E5%91%98)
  - [Web](#web)
  - [Web 服务器](#web-%E6%9C%8D%E5%8A%A1%E5%99%A8)
- [开发工具](#%E5%BC%80%E5%8F%91%E5%B7%A5%E5%85%B7)
  - [构建系统](#%E6%9E%84%E5%BB%BA%E7%B3%BB%E7%BB%9F)
  - [调试](#%E8%B0%83%E8%AF%95)
  - [部署](#%E9%83%A8%E7%BD%B2)
  - [嵌入式](#%E5%B5%8C%E5%85%A5%E5%BC%8F)
  - [FFI](#ffi)
  - [集成开发环境(IDE)](#%E9%9B%86%E6%88%90%E5%BC%80%E5%8F%91%E7%8E%AF%E5%A2%83ide)
  - [模式识别](#%E6%A8%A1%E5%BC%8F%E8%AF%86%E5%88%AB)
  - [剖析](#%E5%89%96%E6%9E%90)
  - [服务](#%E6%9C%8D%E5%8A%A1)
  - [静态分析](#%E9%9D%99%E6%80%81%E5%88%86%E6%9E%90)
  - [测试](#%E6%B5%8B%E8%AF%95)
  - [Transpiling](#transpiling)
- [库](#%E5%BA%93)
  - [人工智能](#%E4%BA%BA%E5%B7%A5%E6%99%BA%E8%83%BD)
    - [遗传算法](#%E9%81%97%E4%BC%A0%E7%AE%97%E6%B3%95)
    - [机器学习](#%E6%9C%BA%E5%99%A8%E5%AD%A6%E4%B9%A0)
  - [天文学](#%E5%A4%A9%E6%96%87%E5%AD%A6)
  - [异步](#%E5%BC%82%E6%AD%A5)
  - [音频](#%E9%9F%B3%E9%A2%91-1)
  - [认证](#%E8%AE%A4%E8%AF%81)
  - [汽车](#%E6%B1%BD%E8%BD%A6)
  - [生物信息学](#%E7%94%9F%E7%89%A9%E4%BF%A1%E6%81%AF%E5%AD%A6)
  - [高速缓存](#%E9%AB%98%E9%80%9F%E7%BC%93%E5%AD%98)
  - [并发](#%E5%B9%B6%E5%8F%91)
  - [云](#%E4%BA%91)
  - [命令行](#%E5%91%BD%E4%BB%A4%E8%A1%8C)
  - [压缩](#%E5%8E%8B%E7%BC%A9)
  - [计算](#%E8%AE%A1%E7%AE%97)
  - [配置](#%E9%85%8D%E7%BD%AE)
  - [加密](#%E5%8A%A0%E5%AF%86)
  - [数据库](#%E6%95%B0%E6%8D%AE%E5%BA%93-1)
  - [数据处理](#%E6%95%B0%E6%8D%AE%E5%A4%84%E7%90%86)
  - [数据结构](#%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84)
  - [数据可视化](#%E6%95%B0%E6%8D%AE%E5%8F%AF%E8%A7%86%E5%8C%96)
  - [日期和时间](#%E6%97%A5%E6%9C%9F%E5%92%8C%E6%97%B6%E9%97%B4)
  - [分布式系统](#%E5%88%86%E5%B8%83%E5%BC%8F%E7%B3%BB%E7%BB%9F)
  - [电子邮件](#%E7%94%B5%E5%AD%90%E9%82%AE%E4%BB%B6)
  - [编码(Encoding)](#%E7%BC%96%E7%A0%81encoding)
  - [文件系统](#%E6%96%87%E4%BB%B6%E7%B3%BB%E7%BB%9F)
  - [游戏开发](#%E6%B8%B8%E6%88%8F%E5%BC%80%E5%8F%91)
  - [地理位置](#%E5%9C%B0%E7%90%86%E4%BD%8D%E7%BD%AE)
  - [图像](#%E5%9B%BE%E5%83%8F-1)
  - [图处理](#%E5%9B%BE%E5%A4%84%E7%90%86)
  - [GUI](#gui)
  - [图像处理](#%E5%9B%BE%E5%83%8F%E5%A4%84%E7%90%86)
  - [语言规范](#%E8%AF%AD%E8%A8%80%E8%A7%84%E8%8C%83)
  - [日志](#%E6%97%A5%E5%BF%97)
  - [宏](#%E5%AE%8F)
  - [Markup 语言](#markup-%E8%AF%AD%E8%A8%80)
  - [移动](#%E7%A7%BB%E5%8A%A8)
  - [网络编程](#%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B)
  - [解析](#%E8%A7%A3%E6%9E%90)
  - [包装格式](#%E5%8C%85%E8%A3%85%E6%A0%BC%E5%BC%8F)
  - [外部设备](#%E5%A4%96%E9%83%A8%E8%AE%BE%E5%A4%87)
  - [平台特定](#%E5%B9%B3%E5%8F%B0%E7%89%B9%E5%AE%9A)
  - [脚本编写](#%E8%84%9A%E6%9C%AC%E7%BC%96%E5%86%99)
  - [模板引擎](#%E6%A8%A1%E6%9D%BF%E5%BC%95%E6%93%8E)
  - [文本处理](#%E6%96%87%E6%9C%AC%E5%A4%84%E7%90%86-1)
  - [文本搜索](#%E6%96%87%E6%9C%AC%E6%90%9C%E7%B4%A2)
  - [Unsafe](#unsafe)
  - [虚拟化](#%E8%99%9A%E6%8B%9F%E5%8C%96-1)
  - [网页编程](#%E7%BD%91%E9%A1%B5%E7%BC%96%E7%A8%8B)
- [注册中心](#%E6%B3%A8%E5%86%8C%E4%B8%AD%E5%BF%83)
- [资源](#%E8%B5%84%E6%BA%90)
- [许可证](#%E8%AE%B8%E5%8F%AF%E8%AF%81)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## 应用

也可以看看[Rust — 生产](https://www.rust-lang.org/production)（在生产中运行 Rust 的组织）。

- [alacritty](https://github.com/jwilm/alacritty) >>- 跨平台，GPU 增强型终端仿真器
- [asm-cli-rust](https://github.com/cch123/asm-cli-rust) >>- 用螃蟹写的 交互式汇编 shell。
- [AnderEnder/s3find-rs](https://github.com/AnderEnder/s3find-rs) >>- 用于遍历 Amazon S3 层次结构的命令行实用程序，类似于 Amazon S3 的 find[<img src="https://api.travis-ci.org/AnderEnder/s3find-rs.svg?branch=master">](https://travis-ci.org/AnderEnder/s3find-rs)
- [andschwa/rust-genetic-algorithm](https://github.com/andschwa/rust-genetic-algorithm) >>- 用于学术基准问题的遗传算法[<img src="https://api.travis-ci.org/andschwa/rust-genetic-algorithm.svg?branch=master">](https://travis-ci.org/andschwa/rust-genetic-algorithm)
- [cloudflare/boringtun](https://github.com/cloudflare/boringtun) >>- 一个 WireGuard VPN 用户空间实现[<img src="https://img.shields.io/badge/crates.io-v0.2.0-orange.svg">](https://crates.io/crates/boringtun)
- [denoland/deno](https://github.com/denoland/deno) >>— 一个安全的 JavaScript/TypeScript 运行时，以 V8, Rust, 和 Tokio 作为地基 [<img src="https://api.travis-ci.com/denoland/deno.svg?branch=master">](https://travis-ci.com/denoland/deno)
- [ivanceras/diwata](https://github.com/ivanceras/diwata) >>- postgresql 数据库管理工具[<img src="https://api.travis-ci.org/ivanceras/diwata.svg">](https://travis-ci.org/ivanceras/diwata)
- [linkerd/linkerd2-proxy](https://github.com/linkerd/linkerd2-proxy) >>- Kubernetes 超轻型服务网。
- [darrint/device-blocker](https://github.com/darrint/device-blocker) >>- 通过阻止家庭 Wifi 路由器上的互联网访问，限制儿童各种移动设备的屏幕时间。
- [dlecan/generic-dns-update](https://github.com/dlecan/generic-dns-update) >>- 使用您的 IP 地址，更新 DNS 区域文件的工具[<img src="https://api.travis-ci.org/dlecan/generic-dns-update.svg?branch=master">](https://travis-ci.org/dlecan/generic-dns-update)
- [Factotum](https://github.com/snowplow/factotum) >>- [一种以编程方式，管道化运行数据的系统](https://snowplowanalytics.com/blog/2016/04/09/introducing-factotum-data-pipeline-runner/) [<img src="https://api.travis-ci.org/snowplow/factotum.svg?branch=master">](https://travis-ci.org/snowplow/factotum)
- [fcsonline/drill](https://github.com/fcsonline/drill) >>- 受 Ansible 语法启发的 HTTP 负载测试应用程序[<img src="https://api.travis-ci.org/fcsonline/drill.svg?branch=master">](https://travis-ci.org/fcsonline/drill)
- [Fractalide](https://github.com/fractalide/fractalide) >>- 简单的 Rust 微服务
- [habitat](https://www.habitat.sh) >>- 由[Chef](https://www.chef.io/)创建的工具，用于构建，部署和管理应用程序。
- [Herd](https://github.com/imjacobclark/Herd) >>- 实验性 HTTP 负载测试应用程序
- [intecture/api](https://github.com/intecture/api) >>- API 驱动的服务器管理和配置工具[<img src="https://api.travis-ci.org/intecture/api.svg?branch=master">](https://travis-ci.org/intecture/api)
- [jedisct1/flowgger](https://github.com/awslabs/flowgger) >>- 快速，简单和轻量级的数据收集器
- [kbknapp/docli](https://github.com/kbknapp/docli-rs) >>- 用于管理 DigitalOcean 基础架构的命令行实用程序[<img src="https://api.travis-ci.org/kbknapp/docli-rs.svg?branch=master">](https://travis-ci.org/kbknapp/docli-rs)
- [limonite](https://crates.io/crates/limonite) >>- 静态博客/网站生成器[<img src="https://api.travis-ci.org/qmx/limonite.svg?branch=master">](https://travis-ci.org/qmx/limonite)
- [MaidSafe](https://maidsafe.net) >>- 一个去中心化的平台。
- [mdBook](https://crates.io/crates/mdbook) >>- 用于从 markdown 文件，创建网页书的命令行实用程序[<img src="https://api.travis-ci.com/azerupi/mdBook.svg?branch=master">](https://travis-ci.com/azerupi/mdBook)
- [nicohman/eidolon](https://github.com/nicohman/eidolon) >>- 适用于 linux 和 macosx 的 Steam 和 drm-free 游戏注册表和启动器[<img src="https://api.travis-ci.org/nicohman/eidolon.svg?branch=master">](https://travis-ci.org/nicohman/eidolon)
- [notty](https://github.com/withoutboats/notty) >>- 一种新型终端
- [Pijul](https://pijul.org) >>- 基于补丁的分布式版本控制系统
- [rsign](https://crates.io/crates/rsign) >>- 一个简单的命令行工具，用于生成/签名/验证数字签名，旨在与 Minisign 兼容[![Codeship Status for danielrangel/rsign](https://app.codeship.com/projects/60b28d80-7645-0135-4402-1639b58199d0/status?branch=master)](https://app.codeship.com/projects/244452)
- [Sandstorm Collections App](https://github.com/sandstorm-io/collections-app)
- [Servo](https://github.com/servo/servo) >>- Web 浏览器引擎原型
- [trust-dns](https://crates.io/crates/trust-dns) >>- DNS 服务器[<img src="https://api.travis-ci.org/bluejekyll/trust-dns.svg?branch=master">](https://travis-ci.org/bluejekyll/trust-dns)
- [Weld](https://github.com/serayuzgur/weld) >>- 完整的模拟 REST API 生成器[<img src="https://api.travis-ci.org/serayuzgur/weld.svg">](https://travis-ci.org/serayuzgur/weld)
- [kytan](https://github.com/changlan/kytan) >>- 高性能点对点 VPN

### 音频

- [indiscipline/zrtstr](https://github.com/indiscipline/zrtstr) >>- 一个命令行实用程序，用于检查立体声 wav 文件是否是人造立体声（即具有相同的通道），并将这些文件转换为单声道。[<img src="https://api.travis-ci.org/indiscipline/zrtstr.svg?branch=master">](https://travis-ci.org/indiscipline/zrtstr)
- [Polaris](https://github.com/agersant/polaris) >>— 一个音乐流应用。  [<img src="https://api.travis-ci.org/agersant/polaris.svg?branch=master">](https://travis-ci.org/agersant/polaris)

### 加密货币

- [Bitcoin Satoshi's Vision](https://github.com/brentongunning/rust-sv) >>- 用于处理比特币 SV 的 Rust 库。
- [cardano-cli](https://github.com/input-output-hk/cardano-cli) >>— Cardano CLI
- [coinbase-pro-rs](https://github.com/inv2004/coinbase-pro-rs) >>— Coinbase pro 客户端, 支持 sync/async/websocket [<img src="https://api.travis-ci.org/inv2004/coinbase-pro-rs.svg?branch=master">](https://travis-ci.org/inv2004/coinbase-pro-rs)
- [ethaddrgen](https://github.com/Limeth/ethaddrgen) >>- Rust 所写的，自定义以太坊虚荣地址生成器[<img src="https://api.travis-ci.org/Limeth/ethaddrgen.svg?branch=master">](https://travis-ci.org/Limeth/ethaddrgen)
- [hdwallet](https://github.com/jjyr/hdwallet) >>- BIP-32 HD 钱包相关的密钥派生工具。
* [Holochain](https://github.com/holochain/holochain-rust) >>— 区块链可延展 P2P 备选项，用于所有你想要构建的分布式应用 [![Build Status](https://api.travis-ci.com/holochain/holochain-rust.svg?branch=master)](https://travis-ci.com/holochain/holochain-rust)
- [infincia/bip39-rs](https://github.com/infincia/bip39-rs) >>— Rust 实现 BIP39.
- [Joystream](https://github.com/Joystream/substrate-runtime-joystream) >>— 一个用户治理的视频平台。
* [Libra](https://github.com/libra/libra) >>— Libra’s 任务是建立一个简单的，授予数亿人的全球货币和金融基本机构。
- [nearprotocol/nearcore](https://github.com/nearprotocol/nearcore) >>- 针对低端移动设备的分散式智能合约平台。
- [coinbase-pro-rs](https://github.com/inv2004/coinbase-pro-rs) >>- Rust 中的 Coinbase pro 客户端，支持 sync / async / websocket[<img src="https://api.travis-ci.org/inv2004/coinbase-pro-rs.svg?branch=master">](https://travis-ci.org/inv2004/coinbase-pro-rs)
- [Grin](https://github.com/mimblewimble/grin/) >>- MimbleWimble 协议的演变
- [Substrate](https://github.com/paritytech/substrate) >>- 用 Rust 编写的通用模块化区块链模板
- [Polkadot](https://github.com/paritytech/polkadot) >>- 具有池化安全性的异构多链技术
- [Parity-Ethereum](https://github.com/paritytech/parity-ethereum) >>- 快速，轻便，强大的以太坊客户端
- [Parity-Bridge](https://github.com/paritytech/parity-bridge) >>- 在任何两个基于以太坊的网络之间架起桥梁
- [Parity-Bitcoin](https://github.com/paritytech/parity-bitcoin) >>- 奇偶校验比特币客户端[<img src="https://api.travis-ci.org/paritytech/parity-bitcoin.svg?branch=master">](https://travis-ci.com/paritytech/parity-bitcoin)
- [Parity-Zcash](https://github.com/paritytech/parity-zcash) >>- Rust 实现 Zcash 协议
- [rust-cardano](https://github.com/input-output-hk/rust-cardano) >>- Cardano 原语，帮助程序和相关应用程序的 Rust 实现
- [cardano-cli](https://github.com/input-output-hk/cardano-cli) >>- Cardano 命令行界面（CLI）
- [Nervos CKB](https://github.com/nervosnetwork/ckb) >>- Nervos CKB 是一个公共许可区块链，是 Nervos 网络的常识层。
- [infincia/bip39-rs](https://github.com/infincia/bip39-rs) >>- BIP39 的 Rust 实现。
- [ChainX](https://github.com/chainx-org/ChainX) >>- Polkadot 上完全分散的链间加密资产管理。
- [rbtc](https://github.com/lucawen/rbtc) >>- 将 BTC 转换为任何货币，反之亦然。[<img src="https://api.travis-ci.com/lucawen/rbtc.svg?branch=master">](https://travis-ci.com/lucawen/rbtc/)
- [wagu](https://crates.io/crates/wagu) >>- 生成加密货币钱包的 Rust 库 [<img src="https://api.travis-ci.com/ArgusHQ/wagyu.svg?branch=master">](https://api.travis-ci.com/ArgusHQ/wagyu.svg?branch=master)
- [zcash](https://github.com/zcash/zcash) >>— Zcash 是一个 "Zerocash" 协议的实现。
- [Holochain](https://github.com/holochain/holochain-rust) >>— 区块链的可伸缩 P2P 备选，用于你想构建的分布式应用 [![Build Status](https://api.travis-ci.com/holochain/holochain-rust.svg?branch=master)](https://travis-ci.com/holochain/holochain-rust)

### 数据库

- [indradb](https://crates.io/crates/indradb) >>- 基于 Rust 的图形数据库[<img src="https://api.travis-ci.org/indradb/indradb.svg?branch=master">](https://travis-ci.org/indradb/indradb)
- [noria](https://crates.io/crates/noria) >>- Web 应用程序后端的动态更改，部分状态的数据流[<img src="https://api.travis-ci.org/mit-pdos/noria.svg?branch=master">](https://travis-ci.org/mit-pdos/noria)
- [ParityDB](https://github.com/paritytech/paritydb) >>— Fast 和可靠数据库, 优化 read 操作 
[<img src="https://api.travis-ci.org/paritytech/paritydb.svg?branch=master">](https://travis-ci.org/paritytech/paritydb)
- [PumpkinDB](https://github.com/PumpkinDB/PumpkinDB) >>- 一个事件采购数据库引擎[<img src="https://api.travis-ci.org/PumpkinDB/PumpkinDB.svg?branch=master">](https://travis-ci.org/PumpkinDB/PumpkinDB)
- [seppo0010/rsedis](https://github.com/seppo0010/rsedis) >>- Rust 中的 Redis 重新实现[<img src="https://api.travis-ci.org/seppo0010/rsedis.svg?branch=master">](https://travis-ci.org/seppo0010/rsedis)
- [ParityDB](https://github.com/paritytech/paritydb) >>- 快速可靠的数据库，针对读取操作进行了优化[<img src="https://api.travis-ci.org/paritytech/paritydb.svg?branch=master">](https://travis-ci.org/paritytech/paritydb)
- [tikv](https://github.com/tikv/tikv) >>- Rust 中的分布式 KV(键值) 数据库[<img src="https://circleci.com/gh/tikv/tikv.svg?style=shield&circle-token=36bab0a8e43edb0941b31c38557d2d9d0d58f708">](https://circleci.com/gh/tikv/tikv)

### 仿真器

也可以看看[crates 关键字 'emulator'](https://crates.io/keywords/emulator)。

- Commodore 64
  - [kondrak/rust64](https://github.com/kondrak/rust64) >>- [<img src="https://api.travis-ci.org/kondrak/rust64.svg?branch=master">](https://travis-ci.org/kondrak/rust64)
- 掌上游戏机
  - [Gekkio/mooneye-gb](https://github.com/Gekkio/mooneye-gb) >>- [<img src="https://api.travis-ci.org/Gekkio/mooneye-gb.svg?branch=master">](https://travis-ci.org/Gekkio/mooneye-gb)
  - [mvdnes/rboy](https://github.com/mvdnes/rboy) >>- [<img src="https://api.travis-ci.org/mvdnes/rboy.svg?branch=master">](https://travis-ci.org/mvdnes/rboy)
  - [NivenT/RGB](https://github.com/nivent/RGB) >>- [<img src="https://api.travis-ci.org/NivenT/RGB.svg?branch=master">](https://travis-ci.org/NivenT/RGB)
  - [mohanson/gameboy](https://github.com/mohanson/gameboy) >>- 全功能跨平台 GameBoy 模拟器。永远都是孩子！
- NES
  - [iamsix/oxidenes](https://github.com/iamsix/oxidenes) >>- [<img src="https://api.travis-ci.com/iamsix/oxidenes.svg?branch=master">](https://travis-ci.org/iamsix/oxidenes)
  - [koute/pinky](https://github.com/koute/pinky) >>- [<img src="https://api.travis-ci.org/koute/pinky.svg?branch=master">](https://travis-ci.org/koute/pinky)
  - [pcwalton/sprocketnes](https://github.com/pcwalton/sprocketnes) >>- [<img src="https://api.travis-ci.org/pcwalton/sprocketnes.svg?branch=master">](https://travis-ci.org/pcwalton/sprocketnes)
- Playstation
  - [simias/rustation](https://github.com/simias/rustation) >>- [<img src="https://api.travis-ci.org/simias/rustation.svg?branch=master">](https://travis-ci.org/simias/rustation)
- ZX Spectrum
  - [pacmancoder/rustzx](https://github.com/pacmancoder/rustzx) >>- [<img src="https://api.travis-ci.org/pacmancoder/rustzx.svg?branch=master">](https://travis-ci.org/pacmancoder/rustzx)
  - [rodrigorc/raze](https://github.com/rodrigorc/raze) >>— WebAssembly 使用, [这是活例子](https://rodrigorc.github.io/raze/)
- Virtual Boy
  - [emu-rs/rustual-boy](https://github.com/emu-rs/rustual-boy) >>- [<img src="https://api.travis-ci.org/emu-rs/rustual-boy.svg?branch=master">](https://travis-ci.org/emu-rs/rustual-boy)
- 英特尔 8080 CPU
  - [mohanson/i8080](https://github.com/mohanson/i8080) >>- Rust 的 Intel 8080 cpu 仿真器
- 仿真器开发工具
  - SNES
    - [ioncodes/snesutilities](https://github.com/ioncodes/snesutilities) >>- ROM 分析仪/提取器

### 游戏

也可以看看[Piston 的游戏制作](https://github.com/PistonDevelopers/piston/wiki/Games-Made-With-Piston)。

- [lifthrasiir/angolmois-rust](https://github.com/lifthrasiir/angolmois-rust) >>- 支持 BMS 格式的简约音乐视频游戏[<img src="https://api.travis-ci.org/lifthrasiir/angolmois-rust.svg?branch=master">](https://travis-ci.org/lifthrasiir/angolmois-rust)
- [swatteau/sokoban-rs](https://github.com/swatteau/sokoban-rs) >>- 推箱子实现
- [Zone of Control](https://github.com/ozkriff/zoc) >>- 基于回合制的六角地形战略游戏[<img src="https://api.travis-ci.org/ozkriff/zoc.svg?branch=master">](https://travis-ci.org/ozkriff/zoc)
- [rhex](https://github.com/dpc/rhex) >>- 六角地形， ascii roguelike
- [citybound](https://github.com/citybound/citybound) >>- 你值得拥有的城市
- [ozkriff/zemeroth](https://github.com/ozkriff/zemeroth) >>- 一个小型的回合制的六角地形策略游戏[<img src="https://api.travis-ci.org/ozkriff/zemeroth.svg?branch=master">](https://travis-ci.org/ozkriff/zemeroth)
- [rsaarelm/magog](https://github.com/rsaarelm/magog) >>- Rust 的 roguelike 游戏
- [schulke-214/rsnake](https://github.com/schulke-214/rsnake) >>- Rust 蛇。
- [schulke-214/connect-four](https://github.com/schulke-214/connect-four) >>— 一个简单的 connect four 实现.
- [cristicbz/rust-doom](https://github.com/cristicbz/rust-doom) >>- Doom 的渲染器，可能会成为一款能玩的游戏[<img src="https://api.travis-ci.org/cristicbz/rust-doom.svg?branch=master">](https://travis-ci.org/cristicbz/rust-doom)
- [Thinkofname/rust-quake](https://github.com/Thinkofname/rust-quake) >>- 用 Rust 写的 Quake map 渲染器
- [aleshaleksey/TGWM](https://github.com/aleshaleksey/TGWM) >>- 回合制的 RPG（正在工作中）[<img src="https://api.travis-ci.org/aleshaleksey/TGWM.svg?branch=master">](https://travis-ci.org/aleshaleksey/TGWM)
- [garkimasera/rusted-ruins](https://github.com/garkimasera/rusted-ruins) >>- 可扩展的开放世界，像素艺术的 rougelike 游戏[<img src="https://api.travis-ci.org/garkimasera/rusted-ruins.svg?branch=master">](https://travis-ci.org/garkimasera/rusted-ruins)
- [Veloren](https://gitlab.com/veloren/veloren) >>- 一个开放世界，开源多人 voxel RPG，目前处于alpha阶段。

### 图像

- [Limeth/euclider](https://github.com/Limeth/euclider) >>- 实时 4D CPU 光线跟踪器 [<img src="https://api.travis-ci.org/Limeth/euclider.svg?branch=master">](https://travis-ci.org/Limeth/euclider)
- [RazrFalcon/resvg](https://github.com/RazrFalcon/resvg) >>— 一个 SVG 渲染库。 [<img src="https://api.travis-ci.org/RazrFalcon/resvg.svg">](https://travis-ci.org/RazrFalcon/resvg)
- [ivanceras/svgbob](https://github.com/ivanceras/svgbob) >>- 将 ASCII 图，转换为 SVG 图形[<img src="https://api.travis-ci.org/ivanceras/svgbob.svg">](https://travis-ci.org/ivanceras/svgbob)
- [RazrFalcon/svgcleaner](https://github.com/RazrFalcon/svgcleaner) >>- 整理 SVG 图形
- [Twinklebear/tray_rust](https://github.com/Twinklebear/tray_rust) >>- 一个光线追踪器[<img src="https://api.travis-ci.org/Twinklebear/tray_rust.svg">](https://travis-ci.org/Twinklebear/tray_rust)
- 图像处理：
  - [spejss/Image-Processing-CLI-in-Rust](https://github.com/spejss/Image-Processing-CLI-in-Rust) >>- 用于处理图像的 CLI，生成直方图。[![Build Status](https://api.travis-ci.org/spejss/Image-Processing-CLI-in-Rust.svg?branch=master)](https://travis-ci.org/spejss/Image-Processing-CLI-in-Rust)

### 工业自动化

- [locka99/opcua](https://github.com/locka99/opcua) >>— 一个纯 rust [OPC UA](https://opcfoundation.org/about/opc-technologies/opc-ua/) 库.
- [slowtec/tokio-modbus](https://github.com/slowtec/tokio-modbus) >>- 一个基于[tokio](https://tokio.rs)的[modbus](http://modbus.org) 库。[![Build Status](https://api.travis-ci.org/slowtec/tokio-modbus.svg?branch=master)](https://travis-ci.org/slowtec/tokio-modbus)
- [BiancoRoyal/modbus-iiot-rust](https://github.com/BiancoRoyal/modbus-iiot-rust) >>- 纯螃蟹[modbus](http://modbus.org)，没有或更少依赖的库。[![Build Status](https://api.travis-ci.org/BiancoRoyal/modbus-iiot-rust.svg?branch=master)](https://travis-ci.org/BiancoRoyal/modbus-iiot-rust)

### 可观察

- [timberio/vector](https://github.com/timberio/vector) - 一个高性能, Logs, 指标性, & 事件路由器。

### 操作系统

也可以看看[对用 Rust 写的操作系统的比较](https://github.com/flosse/rust-os-comparison)。

- [redox-os/redox](https://gitlab.redox-os.org/redox-os/redox) >>- [<img   src="https://api.travis-ci.org/redox-os/redox.svg?branch=master">](https://travis-ci.org/redox-os/redox)
- [thepowersgang/rust_os](https://github.com/thepowersgang/rust_os) >>- [<img src="https://api.travis-ci.org/thepowersgang/rust_os.svg?branch=master">](https://travis-ci.org/thepowersgang/rust_os)
- [tock/tock](https://github.com/tock/tock) >>- 基于 Cortex-M 微控制器的安全嵌入式操作系统
- [nebulet/nebulet](https://github.com/nebulet/nebulet) >>- 实现在 Ring 0 中，运行的 WebAssembly“usermode”的微内核。

### 生产工具

- [eureka](https://crates.io/crates/eureka) >>- 一个 CLI 工具，无需离开终端，即可输入和存储您的想法
- [BenSchZA/pier](https://github.com/BenSchZA/pier) >>- 用于管理（添加，搜索元数据等）所有的一行(完成)，脚本，工具和 CLI 的中央存储库[<img src="https://api.travis-ci.com/BenSchZA/pier.svg?branch=master">](https://travis-ci.com/BenSchZA/pier)

### 安全工具

- [arvancloud/libinjection-rs](https://github.com/arvancloud/libinjection-rs) >>- [libinjection](https://github.com/client9/libinjection)的 Rust 绑定 [<img src="https://api.travis-ci.org/arvancloud/libinjection-rs.svg?branch=master">](https://travis-ci.org/arvancloud/libinjection-rs)
- [kpcyrd/badtouch](https://github.com/kpcyrd/badtouch) >>- 可编写脚本的，网络身份验证破解程序[<img src="https://api.travis-ci.org/kpcyrd/badtouch.svg?branch=master">](https://travis-ci.org/kpcyrd/badtouch)
- [kpcyrd/rshijack](https://github.com/kpcyrd/rshijack) >>- 一个 TCP 连接劫持者，螃蟹重写 shijack[<img src="https://api.travis-ci.org/kpcyrd/rshijack.svg?branch=master">](https://travis-ci.org/kpcyrd/rshijack)
- [kpcyrd/sniffglue](https://github.com/kpcyrd/sniffglue) >>- 安全的多线程数据包嗅探器[<img src="https://api.travis-ci.org/kpcyrd/sniffglue.svg?branch=master">](https://travis-ci.org/kpcyrd/sniffglue)
- [kpcyrd/sn0int](https://github.com/kpcyrd/sn0int) >>- 半自动 OSINT 框架和包管理器[<img src="https://api.travis-ci.org/kpcyrd/sn0int.svg?branch=master">](https://travis-ci.org/kpcyrd/sn0int)
- [Gymmasssorla/anevicon](https://github.com/Gymmasssorla/anevicon) >>- 最强大的基于 UDP 的负载生成器，用 Rust 编写[<img src="https://api.travis-ci.com/Gymmasssorla/anevicon.svg?branch=master">](https://travis-ci.com/Gymmasssorla/anevicon)
- [Gymmasssorla/finshir](https://github.com/Gymmasssorla/finshir) >>- 用 Rust 编写的，协程底层驱动，和慢流量生成器[<img src="https://api.travis-ci.com/Gymmasssorla/finshir.svg?branch=master">](https://travis-ci.com/Gymmasssorla/finshir)

### 系统工具

- [brocode/fblog](https://github.com/brocode/fblog) >>- 小命令行，JSON 日志查看器[<img src="https://api.travis-ci.org/brocode/fblog.svg?branch=master">](https://travis-ci.org/brocode/fblog)
- [buster/rrun](https://github.com/buster/rrun) >>- Linux 的命令启动器，类似于 gmrun[<img src="https://api.travis-ci.org/buster/rrun.svg?branch=master">](https://travis-ci.org/buster/rrun)
- [cristianoliveira/funzzy](https://github.com/cristianoliveira/funzzy) >>- 灵感来自[entr](http://entrproject.org/) 的可配置文件系统观察者 [<img src="https://api.travis-ci.org/cristianoliveira/funzzy.svg?branch=master">](https://travis-ci.org/cristianoliveira/funzzy)
- [dalance/procs](https://github.com/dalance/procs) >>- Rust 写的'ps'的现代替代品[<img src="https://dev.azure.com/dalance/procs/_apis/build/status/dalance.procs?branchName=master">](https://dev.azure.com/dalance/procs/_build/results?buildId=250)
- [ddh](https://github.com/darakian/ddh) >>- 重复文件的快速查找器[<img src="https://api.travis-ci.org/darakian/ddh.svg?branch=master">](https://travis-ci.org/darakian/ddh)
- [fselect](https://crates.io/crates/fselect) >>- 使用类-SQL 查询，查找文件[<img src="https://api.travis-ci.org/jhspetersson/fselect.svg?branch=master">](https://travis-ci.org/jhspetersson/fselect)
- [k0pernicus/zou](https://github.com/k0pernicus/zou) >>- 下载加速器[<img src="https://api.travis-ci.org/k0pernicus/zou.svg?branch=master">](https://travis-ci.org/k0pernicus/zou)
- [lotabout/rargs](https://github.com/lotabout/rargs) \[[rargs](https://crates.io/crates/rargs)] - xargs + awk，支持模式匹配[<img src="https://api.travis-ci.org/lotabout/rargs.svg?branch=master">](https://travis-ci.org/lotabout/rargs)
- [lotabout/skim](https://github.com/lotabout/skim) >>- 纯螃蟹的模糊 finder[<img src="https://api.travis-ci.org/lotabout/skim.svg?branch=master">](https://travis-ci.org/lotabout/skim)
- [mitnk/cicada](https://github.com/mitnk/cicada) >>- 类 bash 的 Unix shell[<img src="https://api.travis-ci.org/mitnk/cicada.svg?branch=master">](https://travis-ci.org/mitnk/cicada)
- [mmstick/concurr](https://github.com/mmstick/concurr) >>- 替代 GNU Parallel w/ 一个客户端+服务器架构
- [mmstick/fontfinder](https://github.com/mmstick/fontfinder) >>- 用于预览和安装 Google 字体的 GTK3 应用程序
- [mmstick/parallel](https://github.com/mmstick/parallel) >>- 重新实现 GNU Parallel
- [mmstick/systemd-manager](https://github.com/mmstick/systemd-manager) >>- 使用 GTK-rs ，编写 systemd 服务管理器。
- [mmstick/tv-renamer](https://github.com/mmstick/tv-renamer) >>- 带有可选 GTK3 前端的，电视连续剧重命名应用程序。[<img src="https://api.travis-ci.org/mmstick/tv-renamer.svg?branch=master">](https://travis-ci.org/mmstick/tv-renamer)
- [Peltoche/lsd](https://github.com/Peltoche/lsd) >>- 有很多漂亮颜色和真棒图标的 ls [<img src="https://api.travis-ci.org/Peltoche/lsd.svg?branch=master">](https://travis-ci.org/Peltoche/lsd)
- [ogham/exa](https://github.com/ogham/exa) >>- 'ls'的替代品[<img src="https://api.travis-ci.org/ogham/exa.svg?branch=master">](https://travis-ci.org/ogham/exa)
- [pop-os/debrep](https://github.com/pop-os/debrepbuild) >>- 用于构建和管理 APT 仓库的 APT 存储库工具
- [pop-os/popsicle](https://github.com/pop-os/popsicle) >>- GTK3 加 CLI 实用程序，用于并行闪存多个 USB 设备
- [Luminarys/synapse](https://github.com/Luminarys/synapse) >>— 灵活且快速的 BitTorrent daemon. [![Build Status](https://api.travis-ci.org/Luminarys/synapse.svg?branch=master)](https://travis-ci.org/Luminarys/synapse)
- [pop-os/system76-power](https://github.com/pop-os/system76-power/) >>- CLI 工具，Linux 电源管理守护程序（DBus 接口）。
- [Ralvke/logram](https://github.com/Ralvke/logram) >>- 将日志文件的更新，推送到 Telegram[<img src="https://api.travis-ci.org/Ralvke/logram.svg?branch=master">](https://travis-ci.org/Ralvke/logram)
- [redox-os/ion](https://github.com/redox-os/ion) >>- 下一代系统 shell [<img src="https://api.travis-ci.org/redox-os/ion.svg?branch=master">](https://travis-ci.org/redox-os/ion)
- [sharkdp/bat](https://github.com/sharkdp/bat) >>- 带翅膀的 cat（1）克隆。[<img src="https://api.travis-ci.org/sharkdp/bat.svg?branch=master">](https://travis-ci.org/sharkdp/bat)
- [sharkdp/fd](https://github.com/sharkdp/fd) >>- 一种简单，快速且用户友好的 find 替代品。[![Build Status](https://api.travis-ci.org/sharkdp/fd.svg?branch=master)](https://travis-ci.org/sharkdp/fd)
- [sitkevij/hex](https://github.com/sitkevij/hex) >>- 彩色 hexdump 终端实用程序。[<img src="https://api.travis-ci.org/sitkevij/hex.svg?branch=master">](https://travis-ci.org/sitkevij/hex)
- [m4b/bingrep](https://github.com/m4b/bingrep) >>- 通过来自各种操作系统和体系结构的二进制文件，并对它们进行着色。[<img src="https://api.travis-ci.org/m4b/bingrep.svg?branch=master">](https://travis-ci.org/m4b/bingrep)
- [uutils/coreutils](https://github.com/uutils/coreutils) >>- GNU coreutils 的跨平台 Rust 重写[<img src="https://api.travis-ci.org/uutils/coreutils.svg?branch=master">](https://travis-ci.org/uutils/coreutils)
- [watchexec](https://github.com/watchexec/watchexec) >>- 执行命令，以响应文件的修改[<img src="https://api.travis-ci.org/watchexec/watchexec.svg?branch=master">](https://travis-ci.org/watchexec/watchexec)
- [XAMPPRocky/tokei](https://github.com/XAMPPRocky/tokei) >>- 计算代码行数 [<img src="https://img.shields.io/travis/XAMPPRocky/tokei.svg">](https://travis-ci.org/XAMPPRocky/tokei)

### 文本编辑

- [gchp/iota](https://github.com/gchp/iota) >>- 一个简单的文本编辑器[<img src="https://api.travis-ci.org/gchp/iota.svg?branch=master">](https://travis-ci.org/gchp/iota)
- [mathall/rim](https://github.com/mathall/rim) >>- 用 Rust 编写的，类似 Vim 的文本编辑器[<img src="https://api.travis-ci.org/mathall/rim.svg?branch=master">](https://travis-ci.org/mathall/rim)
- [Remacs](https://github.com/remacs/remacs) >>- 一个由社区驱动的 Emacs 到 Rust 的端口。[<img src="https://api.travis-ci.org/remacs/remacs.svg?branch=master">](https://travis-ci.org/remacs/remacs)
- [xi-editor](https://github.com/xi-editor/xi-editor) >>- 一个现代编辑器，后端用 Rust 编写。
- [xray](https://github.com/atom-archive/xray) >>- 实验性的下一代基于 Electron 的文本编辑器。[<img src="https://api.travis-ci.org/atom/xray.svg?branch=master">](https://travis-ci.org/atom/xray)

### 文本处理

- [TankerHQ/ruplacer](https://github.com/TankerHQ/ruplacer) >>- 查找，并替换源文件中的文本[<img img src="https://api.travis-ci.org/TankerHQ/ruplacer.svg?branch=master">](https://travis-ci.org/TankerHQ/ruplacer)
- [ripgrep](https://crates.io/crates/ripgrep) >>- 结合了 Silver Searcher 的可用性，和 grep 的原始速度[<img src="https://api.travis-ci.org/BurntSushi/ripgrep.svg?branch=master">](https://travis-ci.org/BurntSushi/ripgrep)
- [phiresky/ripgrep-all](https://github.com/phiresky/ripgrep-all) >>— ripgrep, 但还能搜索 PDFs, E-Books, Office documents, zip, tar.gz, etc. [![Build Status](https://api.travis-ci.org/phiresky/ripgrep-all.svg?branch=master)](https://travis-ci.org/phiresky/ripgrep-all)
- [sd](https://crates.io/crates/sd) >>- 直观的查找和替换 CLI[<img src="https://api.travis-ci.org/chmln/sd.svg?branch=master">](https://travis-ci.org/chmln/sd)
- [lavifb/todo_r](https://github.com/lavifb/todo_r) >>- 使用一个命令，查找所有 TODO 笔记！[<img src="https://api.travis-ci.org/lavifb/todo_r.svg?branch=master">](https://travis-ci.org/lavifb/todo_r)
- [whitfin/runiq](https://github.com/whitfin/runiq) >>- 从未排序的输入中，过滤重复行的有效方法。
- [whitfin/bytelines](https://github.com/whitfin/bytelines) >>- 将输入行，读取为字节切片，以实现高效率。
- [vishaltelangre/ff](https://github.com/vishaltelangre/ff) >>- 按名称查找文件（ff）！[<img src="https://api.travis-ci.org/vishaltelangre/ff.svg?branch=master">](https://travis-ci.org/vishaltelangre/ff)
- [xsv](https://crates.io/crates/xsv) >>- 快速 CSV 命令行工具（切片，索引，选择，搜索，采样等）[<img src="https://api.travis-ci.org/BurntSushi/xsv.svg?branch=master">](https://travis-ci.org/BurntSushi/xsv)
- [Lispre/so_stupid_search](https://github.com/Lispre/so_stupid_search) - 人类专属，简便快捷的字符串查找工具

### 实用

> (译者) Pwned：黑客术语，代指攻击成功的声效词，就像枪响击败的感觉。

- [brycx/checkpwn](https://github.com/brycx/checkpwn) >>- A Have I Pwned（HIBP）命令行实用工具，可让您轻松检查危险帐户和密码。
- [evansmurithi/cloak](https://github.com/evansmurithi/cloak) >>- 命令行 OTP（一次性密码）身份验证器应用程序。[<img src="https://api.travis-ci.com/evansmurithi/cloak.svg?branch=master">](https://travis-ci.com/evansmurithi/cloak) [<img src="https://ci.appveyor.com/api/projects/status/9mlfpfru3ng4c689/branch/master?svg=true">](https://ci.appveyor.com/project/evansmurithi/cloak)
- [arthrp/consoletimer](https://github.com/arthrp/consoleTimer) >>- 终端的简单计时器。[<img src="https://api.travis-ci.org/arthrp/consoleTimer.svg?branch=master">](https://travis-ci.org/arthrp/consoleTimer)
- [myfreeweb/freepass](https://github.com/myfreeweb/freepass) >>- 高级用户的免费密码管理器。[<img src="https://api.travis-ci.org/myfreeweb/freepass.svg?branch=master">](https://travis-ci.org/myfreeweb/freepass)
- [arthrp/quick-skeleton](https://github.com/arthrp/quick-skeleton) >>- 项目脚手架工具，类似于 Yeoman 和 Slush。[<img src="https://api.travis-ci.org/arthrp/quick-skeleton.svg?branch=master">](https://travis-ci.org/arthrp/quick-skeleton)
- [yaa110/rubigo](https://github.com/yaa110/rubigo) >>- Golang 依赖工具和包管理器，用 Rust 编写[<img src="https://api.travis-ci.org/yaa110/rubigo.svg?branch=master">](https://travis-ci.org/yaa110/rubigo)
- [whitfin/s3-concat](https://github.com/whitfin/s3-concat) >>- 使用灵活模式，远程连接 Amazon S3 文件的命令行工具。
- [whitfin/s3-meta](https://github.com/whitfin/s3-meta) >>- 用于收集，有关 Amazon S3 存储桶的元数据的命令行工具。
- [amar-laksh/workstation](https://github.com/amar-laksh/workstation) >>- 一个(运用 OPENCV 的)命令行工具，通过将您与屏幕隔开来，帮助您管理工作台，当您不在其他地方时，锁定屏幕！
- [aleshaleksey/AZDice](https://github.com/aleshaleksey/AZDice) >>- 给桌面 homebrew 使用者的，可视化，成功分布生成器。[<img src="https://api.travis-ci.org/aleshaleksey/AZDice.svg?branch=master">](https://travis-ci.org/aleshaleksey/AZDice)
- [fcsonline/tmux-thumbs](https://github.com/fcsonline/tmux-thumbs) >>- 用 Rust 所编写的，快速版本的 tmux-fingers，复制/粘贴 tmux，如 vimium / vimperator。
- [repoch](https://github.com/lucawen/repoch) >>- 将纪元转换为日期时间，和日期时间转换为纪元[<img src="https://api.travis-ci.com/lucawen/repoch.svg?branch=master">](https://travis-ci.com/lucawen/repoch/)
- [yaa110/cb](https://github.com/yaa110/cb) >>- 用于管理剪贴板的命令行界面[![Build Status](https://api.travis-ci.org/yaa110/cb.svg?branch=master)](https://travis-ci.org/yaa110/cb)

### 视频

- [yuvadm/slingr](https://github.com/yuvadm/slingr) >>- 一个简单的 CLI，通过本地网络，将媒体文件流式传输到 UPnP 媒体渲染器[<img src="https://api.travis-ci.org/yuvadm/slingr.svg?branch=master">](https://travis-ci.org/yuvadm/slingr)
- [yuvadm/streamlib](https://github.com/streamlib/streamlib) - 从命令行上，播放你的在线视频与音频数据流

### 虚拟化

- [firecracker-microvm/firecracker](https://github.com/firecracker-microvm/firecracker) >>- 用于容器工作负载的，轻量级虚拟机[Firecracker Microvm](https://firecracker-microvm.github.io/)
- [oracle/railcar](https://github.com/oracle/railcar) >>- Rust 中，类似 Docker 的容器 OCI 运行时实现[![wercker status](https://app.wercker.com/status/730e874772dc02c6005f4ae4e42b0ca4/s/master 'wercker status')](https://app.wercker.com/applications/59696a02ee70670100155ae2)
- [tailhook/vagga](https://github.com/tailhook/vagga) >>- 没有守护进程的，容器化工具[<img src="https://api.travis-ci.org/tailhook/vagga.svg?branch=master">](https://travis-ci.org/tailhook/vagga)

### 窗口管理员

- [way-cooler/way-cooler](https://github.com/way-cooler/way-cooler) >>- 可定制的 Wayland 组合器（窗口管理器）[<img src="https://api.travis-ci.org/way-cooler/way-cooler.svg?branch=master">](https://travis-ci.org/way-cooler/way-cooler)

### Web

- [Plume-org/Plume](https://github.com/Plume-org/Plume) >>- ActivityPub 联合博客应用程序[<img src="https://api.travis-ci.org/Plume-org/Plume.svg?branch=master">](https://travis-ci.org/Plume-org/Plume)

### Web 服务器

- [thecoshman/http](https://github.com/thecoshman/http) >>- 请托管这些东西 - 一个基本的 http 服务器，用于快速简单地托管文件夹[<img src="https://api.travis-ci.org/thecoshman/http.svg?branch=master">](https://travis-ci.org/thecoshman/http)
- [svenstaro/miniserve](https://github.com/svenstaro/miniserve) >>- 一个小型，独立的跨平台 CLI 工具，您只需抓取二进制文件，并通过 HTTP 提供一些文件[<img src="https://api.travis-ci.org/svenstaro/miniserve.svg?branch=master">](https://travis-ci.org/svenstaro/miniserve)
- [TheWaWaR/simple-http-server](https://github.com/TheWaWaR/simple-http-server) >>- 简单的静态 http 服务器
- [wyhaya/see](https://github.com/wyhaya/see) >>- 静态文件服务器[![Build Status](https://img.shields.io/travis/wyhaya/see.svg)](https://travis-ci.org/wyhaya/see)

## 开发工具

- [clippy](https://crates.io/crates/clippy) >>- Rust lints[<img src="https://api.travis-ci.com/rust-lang/rust-clippy.svg?branch=master">](https://travis-ci.org/rust-lang/rust-clippy)
- [clog-tool/clog-cli](https://github.com/clog-tool/clog-cli) >>- 从 git 元数据，生成 changelog（[conventional changelog](https://blog.thoughtram.io/announcements/tools/2014/09/18/announcing-clog-a-conventional-changelog-generator-for-the-rest-of-us.html)）[<img src="https://api.travis-ci.org/clog-tool/clog-cli.svg?branch=master">](https://travis-ci.org/clog-tool/clog-cli)
- [dan-t/rusty-tags](https://github.com/dan-t/rusty-tags) >>- 为 Cargo 项目及其所有依赖项，创建 ctags / etags[<img src="https://api.travis-ci.org/dan-t/rusty-tags.svg?branch=master">](https://travis-ci.org/dan-t/rusty-tags)
- [frewsxcv/crate-deps](https://github.com/frewsxcv/crate-deps) >>- 为 crates.io 上托管的箱子，生成依赖图的图像
- [git-journal](https://github.com/saschagrunert/git-journal/) >>- Git Commit 消息和 Changelog 生成框架[<img src="https://api.travis-ci.org/saschagrunert/git-journal.svg?branch=master">](https://travis-ci.org/saschagrunert/git-journal)
- [rust-lang-nursery/rustfix](https://github.com/rust-lang/rustfix) >>- 自动应用 rustc 提出的建议[<img src="https://api.travis-ci.org/killercup/rustfix.svg?branch=master">](https://travis-ci.org/killercup/rustfix)
- [just](https://github.com/casey/just) >>- 构建特定项目的任务，便捷命令运行程序[<img src="https://api.travis-ci.org/casey/just.svg?branch=master">](https://travis-ci.org/casey/just)
- [Module Linker](https://github.com/fiatjaf/module-linker) >>- 增加`<a>`链接扩展，让 Github 可以落实(链接)到`mod`，`use`和`extern crate`语句。
- [ptags](https://github.com/dalance/ptags) >>- 用于 git 存储库的，并行通用 ctags 包装器[![Build Status](https://api.travis-ci.org/dalance/ptags.svg?branch=master)](https://travis-ci.org/dalance/ptags)
- [Racer](https://github.com/racer-rust/racer) >>- Rust 的代码补全[<img src="https://api.travis-ci.com/phildawes/racer.svg?branch=master">](https://travis-ci.org/phildawes/racer)
- [rustfmt](https://github.com/rust-lang/rustfmt) >>- Rust 代码格式化程序[<img src="https://api.travis-ci.com/rust-lang/rustfmt.svg?branch=master">](https://travis-ci.org/rust-lang/rustfmt)
- [Rustup](https://github.com/rust-lang/rustup.rs) >>- Rust 工具链安装程序[<img src="https://api.travis-ci.com/rust-lang/rustup.rs.svg?branch=master">](https://travis-ci.org/rust-lang/rustup.rs)
- [Rust Language Server](https://github.com/rust-lang/rls) >>- 在后台运行的服务器，为 IDE，编辑器和其他工具，提供有关 Rust 程序的信息
- [Rust Regex Playground](https://2fd.github.io/rust-regex-playground/#method=find&regex=%5Cw%2B&text=abc) >>— 网络工具：执行 rust 正则表达式
- [artifact](https://github.com/vitiral/artifact) >>- 为开发人员设计的文档设计工具[![Build Status](https://api.travis-ci.org/vitiral/artifact.svg?branch=master)](https://travis-ci.org/vitiral/artifact)
- [semantic-rs](https://github.com/semantic-rs/semantic-rs) >>- 自动 crate 发布[<img src="https://api.travis-ci.org/semantic-rs/semantic-rs.svg?branch=master">](https://travis-ci.org/semantic-rs/semantic-rs)
- [fw](https://github.com/brocode/fw) >>- 工作空间的生产力助推器[<img src="https://api.travis-ci.org/brocode/fw.svg?branch=master">](https://travis-ci.org/brocode/fw)
- [tinyrick](https://github.com/mcandre/tinyrick)一个基本任务依赖的工具，强调 Rust 函数，优于原始 shell 命令。

### 构建系统

- [Cargo](https://crates.io/) >>- Rust 包管理器
  - [cargo-benchcmp](https://crates.io/crates/cargo-benchcmp) >>- 用于比较 Rust 微基准测试的实用程序[<img src="https://api.travis-ci.org/BurntSushi/cargo-benchcmp.svg?branch=master">](https://travis-ci.org/BurntSushi/cargo-benchcmp)
  - [cargo-bitbake](https://crates.io/crates/cargo-bitbake) >>- Cargo 扩展，可以利用 meta-rust 中的类，生成 BitBake 配方[<img src="https://api.travis-ci.org/cardoe/cargo-bitbake.svg?branch=master">](https://travis-ci.org/cardoe/cargo-bitbake)
  - [cargo-cache](https://crates.io/crates/cargo-cache) >>- 检查/管理/清理您的 Cargo 缓存（`~/.cargo/`/`${CARGO_HOME}`），打印尺寸等[<img src="https://api.travis-ci.org/matthiaskrgr/cargo-cache.svg?branch=master">](https://travis-ci.org/matthiaskrgr/cargo-cache)
  - [cargo-check](https://crates.io/crates/cargo-check) >>- `cargo rustc -- -Zno-trans`的包装，如果您只需要正确性检查，这对于运行更快的编译很有帮助[<img src="https://api.travis-ci.org/rsolomo/cargo-check.svg?branch=master">](https://travis-ci.org/rsolomo/cargo-check)
  - [cargo-count](https://crates.io/crates/cargo-count) >>- 列出源代码计数和 Cargo 项目的详细信息，包括不安全的统计数据[<img src="https://api.travis-ci.org/kbknapp/cargo-count.svg?branch=master">](https://travis-ci.org/kbknapp/cargo-count)
  - [cargo-deb](https://crates.io/crates/cargo-deb) >>- 生成二进制 Debian 软件包[<img src="https://api.travis-ci.org/mmstick/cargo-deb.svg?branch=master">](https://travis-ci.org/mmstick/cargo-deb)
  - [cargo-deps](https://crates.io/crates/cargo-deps) >>- 构建 Rust 项目的依赖图[<img src="https://api.travis-ci.org/m-cat/cargo-deps.svg?branch=master">](https://travis-ci.org/m-cat/cargo-deps)
  - [cargo-do](https://crates.io/crates/cargo-do) >>- 连续运行，多个 Cargo 命令[<img src="https://api.travis-ci.org/pwoolcoc/cargo-do.svg?branch=master">](https://travis-ci.org/pwoolcoc/cargo-do)
  - [cargo-ebuild](https://crates.io/crates/cargo-ebuild) >>- Cargo 扩展，可以使用树内 eclass 生成 ebuilds [<img src="https://api.travis-ci.org/cardoe/cargo-ebuild.svg?branch=master">](https://travis-ci.org/cardoe/cargo-ebuild)
  - [cargo-edit](https://crates.io/crates/cargo-edit) >>- 允许您，通过命令行读取/写入 Cargo.toml 文件，来添加和列出依赖项[<img src="https://api.travis-ci.org/killercup/cargo-edit.svg?branch=master">](https://travis-ci.org/killercup/cargo-edit)
  - [cargo-find](https://crates.io/crates/cargo-find) <sup>弃用</sup>- 从命令行，查找箱子[<img src="https://api.travis-ci.org/Ralvke/cargo-find.svg?branch=master">](https://travis-ci.org/Ralvke/cargo-find)
  - [cargo-graph](https://crates.io/crates/cargo-graph) >>- `cargo-dot`的加强分支，带有附加功能。没有维护，请参阅`cargo-deps` [<img src="https://api.travis-ci.org/kbknapp/cargo-graph.svg?branch=master">](https://travis-ci.org/kbknapp/cargo-graph)
  - [cargo-info](https://crates.io/crates/cargo-info) >>- 在命令行向 crates.io ，查询 crates 详细信息[<img src="https://api.travis-ci.org/imp/cargo-info.svg?branch=master">](https://travis-ci.org/imp/cargo-info)
  - [cargo-license](https://crates.io/crates/cargo-license) >>— cargo 子命令，快速产看所有依赖的许可证。 [<img src="https://api.travis-ci.org/onur/cargo-license.svg?branch=master">](https://travis-ci.org/onur/cargo-license)
  - [cargo-make](https://crates.io/crates/cargo-make) >>- Rust 任务运行器，和构建工具。[<img src="https://api.travis-ci.org/sagiegurari/cargo-make.svg?branch=master">](https://travis-ci.org/sagiegurari/cargo-make)
  - [cargo-modules](https://crates.io/crates/cargo-modules) >>- 一个 Cargo 插件，用于显示箱子模块的树状概览。[<img src="https://api.travis-ci.org/regexident/cargo-modules.svg?branch=master">](https://travis-ci.org/regexident/cargo-modules)
  - [cargo-multi](https://crates.io/crates/cargo-multi) >>- 在多个箱子上，运行指定的 Cargo 命令[<img src="https://api.travis-ci.org/imp/cargo-multi.svg?branch=master">](https://travis-ci.org/imp/cargo-multi)
  - [cargo-outdated](https://crates.io/crates/cargo-outdated) >>- 显示 Rust 依赖项的最新版本可用，或过期版本[<img src="https://api.travis-ci.org/kbknapp/cargo-outdated.svg?branch=master">](https://travis-ci.org/kbknapp/cargo-outdated)
  - [cargo-release](https://crates.io/crates/cargo-release) >>- 用于发布 git 管理的 Cargo 项目，构建，标记，发布，文档和推送的工具[<img src="https://api.travis-ci.org/sunng87/cargo-release.svg?branch=master">](https://travis-ci.org/sunng87/cargo-release)
  - [cargo-script](https://crates.io/crates/cargo-script) >>- 让人们快速轻松地运行 Rust“脚本”，可以利用 Cargo 的包生态系统[<img src="https://api.travis-ci.org/DanielKeep/cargo-script.svg?branch=master">](https://travis-ci.org/DanielKeep/cargo-script)
  - [cargo-testify](https://crates.io/crates/cargo-testify) >>- 监视文件更改，运行测试，并通过友好的操作系统，通知结果[<img src="https://api.travis-ci.org/greyblake/cargo-testify.svg?branch=master">](https://travis-ci.org/greyblake/cargo-testify)
  - [cargo-tree](https://github.com/sfackler/cargo-tree) >>– Cargo 子命令，对一个箱子的依赖图，进行类 tree 格式的可视化处理 [![CircleCI](https://circleci.com/gh/sfackler/cargo-tree.svg?style=shield)](https://circleci.com/gh/sfackler/cargo-tree)
  - [cargo-update](https://crates.io/crates/cargo-update) >>- cargo 子命令，用于检查和应用，已安装可执行文件的更新[<img src="https://api.travis-ci.org/nabijaczleweli/cargo-update.svg?branch=master">](https://travis-ci.org/nabijaczleweli/cargo-update)
  - [cargo-watch](https://crates.io/crates/cargo-watch) >>- 在源代码变更时，让 cargo 编译项目的实用程序[<img src="https://api.travis-ci.org/passcod/cargo-watch.svg?branch=master">](https://travis-ci.org/passcod/cargo-watch)
  - [liuchong/cargo-x](https://github.com/liuchong/cargo-x) >>- 执行自定义命令的，非常简单的第三方 Cargo 子命令[<img src="https://api.travis-ci.org/liuchong/cargo-x.svg?branch=master">](https://travis-ci.org/liuchong/cargo-x)
  - [dtolnay/cargo-expand](https://github.com/dtolnay/cargo-expand) >>- 在源代码中，展开宏
- CMake
  - [Devolutions/CMakeRust](https://github.com/Devolutions/CMakeRust) >>- 用于将 Rust 库，集成到 CMake 项目中
  - [SiegeLord/RustCMake](https://github.com/SiegeLord/RustCMake) >>- 一个示例项目，显示了 Rust 的 CMake 用法[<img src="https://api.travis-ci.org/SiegeLord/RustCMake.svg?branch=master">](https://travis-ci.org/SiegeLord/RustCMake)
- Github actions
  - [icepuma/rust-action](https://github.com/icepuma/rust-action) >>- 螃蟹 github action
- WebPack
  - [Ralvke/rust-loader](https://github.com/Ralvke/rust-loader) >>- Webpack Rust loader（wasm）

### 调试

- GDB
  - [rust-gdb](https://github.com/rust-lang/rust/blob/master/src/etc/rust-gdb)
  - [gdbgui](https://github.com/cs01/gdbgui) >>- 基于浏览器的 gdb 前端，用于调试 C，C ++，Rust 和 go。[<img src="https://api.travis-ci.org/cs01/gdbgui.svg?branch=master">](https://travis-ci.org/cs01/gdbgui)
- LLDB
  - [lldb_batchmode.py](https://github.com/rust-lang/rust/blob/master/src/etc/lldb_batchmode.py) >>- 允许以类 GDB 批处理模式的方式，使用 LLDB。
  - [CodeLLDB](https://marketplace.visualstudio.com/items?itemName=vadimcn.vscode-lldb) >>- LLDB 扩展，给予[Visual Studio Code](https://code.visualstudio.com/)。
- rr
  - [rr](https://rr-project.org/) >>- rr 是一个轻量级工具，用于记录和重放应用程序的执行。

### 部署

- Docker
  - [emk/rust-musl-builder](https://github.com/emk/rust-musl-builder) >>- 使用 musl-libc 和 musl-gcc，编译静态 Rust 二进制文件的 Docker 镜像，以及有用的 C 库的静态版本。
  - [kpcyrd/mini-docker-rust](https://github.com/kpcyrd/mini-docker-rust) >>- 非常小的，螃蟹 docker 镜像的示例项目[<img src="https://api.travis-ci.org/kpcyrd/mini-docker-rust.svg?branch=master">](https://travis-ci.org/kpcyrd/mini-docker-rust)
  - [liuchong/docker-rustup](https://github.com/liuchong/docker-rustup) >>- 多个版本（带有 musl 工具）Rust Docker 镜像
  - [messense/rust-musl-cross](https://github.com/messense/rust-musl-cross) >>- 用于使用 musl-cross 编译，静态 Rust 二进制文件的 Docker 镜像[<img src="https://api.travis-ci.org/messense/rust-musl-cross.svg?branch=master">](https://travis-ci.org/messense/rust-musl-cross)
  - [rust-lang-nursery/docker-rust](https://github.com/rust-lang/docker-rust) >>- Rust Docker 官方镜像
- Google App Engine
  - [DenisKolodin/rust-app-engine](https://github.com/DenisKolodin/rust-app-engine) >>- App Engine Rust 样板
- Heroku
  - [emk/heroku-buildpack-rust](https://github.com/emk/heroku-buildpack-rust) >>- Heroku 上，Rust 应用程序的 buildpack

### 嵌入式

[Rust Embedded](https://rust-embedded.org/)

- 跨平台编译
  - [japaric/rust-cross](https://github.com/japaric/rust-cross) >>- 关于跨平台编译 Rust 程序，需要了解的所有内容[<img src="https://api.travis-ci.org/japaric/rust-cross.svg?branch=master">](https://travis-ci.org/japaric/rust-cross)
  - [japaric/xargo](https://github.com/japaric/xargo) >>- 轻松地将 Rust 程序，跨平台编译为自定义裸机目标，如 ARM Cortex-M [<img src="https://api.travis-ci.org/japaric/xargo.svg?branch=master">](https://travis-ci.org/japaric/xargo)
- Raspberry Pi
  - [Ogeon/rust-on-raspberry-pi](https://github.com/Ogeon/rust-on-raspberry-pi) >>- 有关如何为 Raspberry Pi，跨平台编译 Rust 项目的说明。
- Arduino
  - [avr-rust/ruduino](https://github.com/avr-rust/ruduino) `^`^t` Arduino Uno 的可重用组件。

### FFI

也可以看看[对外函数 (Foreign Function) 接口](https://doc.rust-lang.org/book/first-edition/ffi.html)，[The Rust FFI 综合](http://jakegoulding.com/rust-ffi-omnibus/)（代码的示例集合，如何使用其他语言，运用 Rust 代码）和[Rust FFI 示例](https://github.com/alexcrichton/rust-ffi-examples)。

- C
  - [rlhunt/cbindgen](https://github.com/eqrion/cbindgen) >>- 从 Rust 源文件，生成 C 头文件。用于 Gecko 的 WebRender[<img src="https://api.travis-ci.org/eqrion/cbindgen.svg?branch=master">](https://travis-ci.org/eqrion/cbindgen)
  - [Sean1708/rusty-cheddar](https://github.com/Sean1708/rusty-cheddar) >>- 从 Rust 源文件，生成 C 头文件[<img src="https://api.travis-ci.org/Sean1708/rusty-cheddar.svg?branch=master">](https://travis-ci.org/Sean1708/rusty-cheddar)
- C ++
  - [rust-lang/rust-bindgen](https://github.com/rust-lang/rust-bindgen) >>- Rust 绑定生成器
- Erlang
  - [rusterlium/rustler](https://github.com/rusterlium/rustler) >>- 用于创建 Erlang NIF 功能的 Rust 安全桥梁 [<img src="https://api.travis-ci.org/rusterlium/rustler.svg?branch=master">](https://travis-ci.org/rusterlium/rustler)
- Haskell
  - [mgattozzi/curryrs](https://github.com/mgattozzi/curryrs) >>- 弥合 Haskell 和 Rust 之间的桥梁
  - [mgattozzi/haskellrs](https://github.com/mgattozzi/haskellrs) >>- 在 Haskell FFI 示例中的 螃蟹 代码
  - [mgattozzi/rushs](https://github.com/mgattozzi/rushs) >>- Rust FFI 示例中的 Haskell 代码
- Java
  - [j4rs](https://crates.io/crates/j4rs) >>- 使用 Rust 的 Java[<img src="https://api.travis-ci.org/astonbitecode/j4rs.svg?branch=master">](https://travis-ci.org/astonbitecode/j4rs)
  - [bennettanderson/rjni](https://github.com/benanders/rjni) >>- 使用 Rust 的 Java[<img src="https://api.travis-ci.com/bennettanderson/rjni.svg?branch=master">](https://travis-ci.org/GravityScore/RustJNI)
  - [drrb/java-rust-example](https://github.com/drrb/java-rust-example) >>- 使用 Java 中的 Rust[<img src="https://api.travis-ci.org/drrb/java-rust-example.svg?branch=master">](https://travis-ci.org/drrb/java-rust-example)
  - [jni](https://crates.io/crates/jni) >>- 使用 Java 中的 Rust[<img src="https://api.travis-ci.org/jni-rs/jni-rs.svg?branch=master">](https://travis-ci.org/jni-rs/jni-rs)
  - [jni-sys](https://crates.io/crates/jni-sys) >>- 与 jni.h 对应的 Rust 定义[<img src="https://api.travis-ci.org/sfackler/rust-jni-sys.svg?branch=master">](https://travis-ci.org/sfackler/rust-jni-sys)
  - [rucaja](https://crates.io/crates/rucaja) >>- 使用 Rust 的 Java[<img src="https://api.travis-ci.org/kud1ing/rucaja.svg?branch=master">](https://travis-ci.org/kud1ing/rucaja)
  - [rawrasaur/rust-jdbc](https://github.com/rawrasaur/rust-jdbc) >>- 使用 Rust 的 JDBC[<img src="https://api.travis-ci.org/rawrasaur/rust-jdbc.svg?branch=master">](https://travis-ci.org/rawrasaur/rust-jdbc)
- Lua
  - [jcmoyer/rust-lua53](https://github.com/jcmoyer/rust-lua53) >>- Lua 5.3 Rust 的绑定 [<img src="https://api.travis-ci.org/jcmoyer/rust-lua53.svg?branch=master">](https://travis-ci.org/jcmoyer/rust-lua53)
  - [kballard/rust-lua](https://github.com/lilyball/rust-lua) >>- 安全 Rust 绑定到 Lua 5.1[<img src="https://api.travis-ci.org/lilyball/rust-lua.svg">](https://travis-ci.org/lilyball/rust-lua)
  - [tickbh/td_rlua](https://github.com/tickbh/td_rlua) >>- 适用于 Rust 的零成本高级 lua 5.3 包装[<img src="https://api.travis-ci.org/tickbh/td_rlua.svg?branch=master">](https://travis-ci.org/tickbh/td_rlua)
  - [tomaka/hlua](https://github.com/tomaka/hlua) >>- 与 Lua 接口的 Rust 库[<img src="https://api.travis-ci.org/tomaka/hlua.svg?branch=master">](https://travis-ci.org/tomaka/hlua)
- mruby
  - [anima-engine/mrusty](https://github.com/anima-engine/mrusty) >>- Rust 的 mruby 安全绑定 [<img src="https://api.travis-ci.org/anima-engine/mrusty.svg?branch=master">](https://travis-ci.org/anima-engine/mrusty)
- Node.js
  - [neon-bindings/neon](https://github.com/neon-bindings/neon) >>- 使用 Node.js 中的 Rust[<img src="https://api.travis-ci.org/neon-bindings/neon.svg?branch=master">](https://travis-ci.org/neon-bindings/neon)
- Objective-C
  - [SSheldon/rust-objc](https://github.com/SSheldon/rust-objc) >>- Objective-C 运行时绑定和 Rust 的包装器
- Perl
  - [vickenty/mi-rust](https://github.com/vickenty/mi-rust) >>- 添加对 M::I 的支持，用于构建 Cargo 模块
  - [vickenty/perl-xs](https://github.com/vickenty/perl-xs) >>- 使用 Rust 创建 Perl XS 模块[<img src="https://api.travis-ci.org/vickenty/perl-xs.svg?branch=master">](https://travis-ci.org/vickenty/perl-xs)
- Python
  - [getsentry/milksnake](https://github.com/getsentry/milksnake) >>- python setuptools 的扩展，允许您以最便携的方式在 Python 轮中分发动态链接库。
  - [dgrunwald/rust-cpython](https://github.com/dgrunwald/rust-cpython) >>- Python 绑定 [<img src="https://api.travis-ci.org/dgrunwald/rust-cpython.svg?branch=master">](https://travis-ci.org/dgrunwald/rust-cpython)
  - [PyO3/PyO3](https://github.com/PyO3/PyO3) >>- Python 解释器的 Rust 绑定 [<img src="https://api.travis-ci.org/PyO3/pyo3.svg?branch=master">](https://travis-ci.org/PyO3/pyo3)
- R
  - [rustr/rustr](https://github.com/rustr/rustr) >>- 使用 R 中的 Rust，并在 Rust 中使用 R.[<img src="https://api.travis-ci.org/rustr/rustr.svg?branch=master">](https://travis-ci.org/rustr/rustr)
- Ruby
  - [d-unseductable/ruru](https://github.com/d-unseductable/ruru) >>- 用 Rust 编写的原生 Ruby 扩展[<img src="https://api.travis-ci.org/d-unseductable/ruru.svg?branch=master">](https://travis-ci.org/d-unseductable/ruru)
  - [danielpclark/rutie](https://github.com/danielpclark/rutie) >>- 用 Rust 编写的原生 Ruby 扩展，反之亦然[![Build Status](https://api.travis-ci.org/danielpclark/rutie.svg?branch=master)](https://travis-ci.org/danielpclark/rutie)
  - [tildeio/helix](https://github.com/tildeio/helix) >>- 在 Rust 中编写 Ruby 类[<img src="https://api.travis-ci.org/tildeio/helix.svg?branch=master">](https://travis-ci.org/tildeio/helix)
- Web Assembly
  - [rustwasm/wasm-pack](https://github.com/rustwasm/wasm-pack) >>- :package: :sparkles: 打包成 wasm 并将其发布到 npm！[<img src="https://api.travis-ci.com/rustwasm/wasm-pack.svg?branch=master">](https://travis-ci.org/rustwasm/wasm-packn)
  - [rustwasm/wasm-bindgen](https://github.com/rustwasm/wasm-bindgen) >>- 促进 wasm 模块和 JS 之间高级交互的项目。[<img src="https://api.travis-ci.com/rustwasm/wasm-bindgen.svg?branch=master">](https://travis-ci.org/rustwasm/wasm-bindgen)

### 集成开发环境(IDE)

也可以看看[Are we (I)DE yet?](https://areweideyet.com/)和[Rust 工具](https://www.rust-lang.org/tools)。

- [Atom](https://atom.io/)
  - [zargony/atom-language-rust](https://github.com/zargony/atom-language-rust)
- [Eclipse](https://www.eclipse.org/)
  - [Eclipse Corrosion](https://github.com/eclipse/corrosion)
  - [RustDT](https://github.com/RustDT/RustDT) >>- [<img src="https://api.travis-ci.org/RustDT/RustDT.svg?branch=master">](https://travis-ci.org/RustDT/RustDT)
- [Emacs](https://www.gnu.org/software/emacs/)
  - [rust-mode](https://github.com/rust-lang/rust-mode) >>- Rust Major Mode
  - [flycheck-rust](https://github.com/flycheck/flycheck-rust) >>- Rust 支持[Flycheck](https://github.com/flycheck/flycheck)
  - [emacs-racer](https://github.com/racer-rust/emacs-racer) >>- 自动补全（另见[company](https://company-mode.github.io)和[auto-complete](https://github.com/auto-complete/auto-complete)）
  - [lsp-rust](https://github.com/emacs-lsp-legacy/lsp-rust) >>- 添加 rls 支持[lsp-mode](https://github.com/emacs-lsp/lsp-mode)
- [gitpod.io](https://gitpod.io) >>- 基于 Rust 语言服务器的完整 Rust 支持的在线 IDE
- [gnome-builder](https://wiki.gnome.org/Apps/Builder)自版本 3.22.2 起，对螃蟹和 Cargo 的原生支持
- [Kakoune](http://kakoune.org/)
  - [ul/kak-lsp](https://github.com/ul/kak-lsp/) >>- [LSP](https://microsoft.github.io/language-server-protocol/)客户端。在 Rust 中实现并支持 rls 开箱即用。
- [NetBeans](https://netbeans.org/)
  - [drrb/rust-netbeans](https://github.com/drrb/rust-netbeans)
- [IntelliJ](https://www.jetbrains.com/idea/)
  - [intellij-rust/intellij-rust](https://github.com/intellij-rust/intellij-rust) >>- [<img src="https://api.travis-ci.org/intellij-rust/intellij-rust.svg?branch=master">](https://travis-ci.org/intellij-rust/intellij-rust)
  - [intellij-rust/intellij-toml](https://github.com/intellij-rust/intellij-toml) >>- 基本的 Toml 支持
- [Ride](https://github.com/madeso/ride) >>- [<img src="https://api.travis-ci.org/madeso/ride.svg?branch=master">](https://travis-ci.org/madeso/ride)
- [SolidOak](https://github.com/oakes/SolidOak) >>- 一个简单的 Rust IDE，基于 GTK+ 和[Neovim](https://github.com/neovim/neovim)
- [Sublime Text](https://www.sublimetext.com/)
  - [rust-lang/rust-enhanced](https://github.com/rust-lang/rust-enhanced) >>- 官方 Rust 包
  - [sublimehq/packages](https://github.com/sublimehq/Packages/tree/master/Rust) >>- 原生 Sublime 支持（已安装）
- [Vim](https://vim.sourceforge.io/) >>- 无处不在的文本编辑器
  - [rust.vim](https://github.com/rust-lang/rust.vim) >>- 提供文件检测，语法突出显示，格式化，合成集成等。
  - [vim-cargo](https://github.com/timonv/vim-cargo) >>- 命令绑定，让 vim 快速运行 Cargo。
  - [vim-racer](https://github.com/racer-rust/vim-racer) >>- 允许 vim 使用[Racer](https://github.com/racer-rust/racer)用于 Rust 代码完成和导航。
  - [autozimu/LanguageClient-neovim](https://github.com/autozimu/LanguageClient-neovim) >>- [LSP](https://microsoft.github.io/language-server-protocol/)客户端。在 Rust 中实现并支持 rls 开箱即用。
- Visual Studio
  - [PistonDevelopers/VisualRust](https://github.com/PistonDevelopers/VisualRust) >>- Rust 的 Visual Studio 扩展[<img src="https://api.travis-ci.org/PistonDevelopers/VisualRust.svg?branch=master">](https://travis-ci.org/PistonDevelopers/VisualRust)
  - [dgriffen/rls-vs2017](https://github.com/ZoeyR/rls-vs2017) >>- Visual Studio 2017 Preview 的 Rust 支持[<img src="https://ci.appveyor.com/api/projects/status/d2lxlincwninhsng?svg=true">](https://ci.appveyor.com/project/dgriffen/rls-vs2017)
- [Visual Studio Code](https://code.visualstudio.com/)
  - [rust-lang/rls-vscode](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust) >>- 对 Visual Studio Code 的 Rust 支持
  - [CodeLLDB](https://marketplace.visualstudio.com/items?itemName=vadimcn.vscode-lldb) >>- LLDB 扩展
  - [crates](https://github.com/serayuzgur/crates) >>- crates 是 crates.io 依赖项的扩展。[<img src="https://img.shields.io/vscode-marketplace/v/serayuzgur.crates.svg">](https://github.com/serayuzgur/crates) [<img src="https://api.travis-ci.org/serayuzgur/crates.svg?branch=master">](https://travis-ci.org/serayuzgur/crates)
  - [KalitaAlexey/vscode-rust](https://marketplace.visualstudio.com/items?itemName=kalitaalexey.vscode-rust) >>- RustyCode 的一个分支

### 模式识别

- [sfikas/rusteval](https://github.com/sfikas/rusteval) >>- 用于评估，检索算法输出的工具[![Build Status](https://api.travis-ci.org/sfikas/rusteval.svg?branch=master)](https://travis-ci.org/sfikas/rusteval)

### 剖析

- [sharkdp/hyperfine](https://github.com/sharkdp/hyperfine) >>- 命令行，基准测试工具[![Version info](https://img.shields.io/crates/v/hyperfine.svg)](https://crates.io/crates/hyperfine) [![Build Status](https://api.travis-ci.org/sharkdp/hyperfine.svg?branch=master)](https://travis-ci.org/sharkdp/hyperfine)
- [performancecopilot/hornet](https://github.com/performancecopilot/hornet) >>- Performance Co-Pilot 的内存映射值检测库[![crates.io badge](https://img.shields.io/crates/v/hornet.svg)](https://crates.io/crates/hornet) [<img src="https://api.travis-ci.org/performancecopilot/hornet.svg?branch=master">](https://travis-ci.org/performancecopilot/hornet)
- [nokia/memory-profiler](https://github.com/koute/memory-profiler) >>- Linux 的内存分析器[![Build Status](https://api.travis-ci.org/nokia/memory-profiler.svg?branch=master)](https://travis-ci.org/nokia/memory-profiler)
- [ellisonch/rust-stopwatch](https://github.com/ellisonch/rust-stopwatch) >>- 秒表库[<img src="https://api.travis-ci.org/ellisonch/rust-stopwatch.svg?branch=master">](https://travis-ci.org/ellisonch/rust-stopwatch)
- FlameGraphs
  - [mrhooray/torch](https://github.com/mrhooray/torch) >>- 基于 DWARF 调试信息，生成 FlameGraphs
  - [TyOverby/flame](https://github.com/llogiq/flame) >>- [<img src="https://api.travis-ci.org/TyOverby/flame.svg?branch=master">](https://travis-ci.org/TyOverby/flame)

### 服务

- [deps.rs](https://github.com/srijs/deps.rs) >>- 检测过时或不安全的依赖项
- [docs.rs](https://docs.rs) >>- 自动生成箱子的文档

### 静态分析

\[[assert](https://crates.io/keywords/assert)，[static](https://crates.io/keywords/static)]

- [static_assertions](https://crates.io/crates/static_assertions) >>- 编译-时刻的断言(工具)，以确保满足不变量 [![Build Status](https://api.travis-ci.org/nvzqz/static-assertions-rs.svg?branch=master)](https://travis-ci.org/nvzqz/static-assertions-rs/)

### 测试

\[[testing](https://crates.io/keywords/testing)]

- [mockiato](https://crates.io/crates/mockiato) >>— 一个严格的, 同时还很友好的，Rust 2018 的 mock 库 [<img src="https://api.travis-ci.com/myelin-ai/mockiato.svg?branch=master">](https://travis-ci.com/myelin-ai/mockiato)
- [mutagen](https://crates.io/crates/mutagen) >>- 可变源-级，测试框架（仅限 nightly）[<img src="https://api.travis-ci.org/llogiq/mutagen.svg?branch=master">](https://travis-ci.org/llogiq/mutagen)
- [AlKass/polish](https://github.com/AlKass/polish) >>- 测试/测试-驱动的迷你框架[![Build Status](https://api.travis-ci.org/AlKass/polish.svg?branch=master)](https://travis-ci.org/AlKass/polish) [![Crates Package Status](https://img.shields.io/crates/v/polish.svg)](https://crates.io/crates/polish)
- [proptest](https://crates.io/crates/proptest) >>- 属性(property)测试框架，灵感来自[Hypothesis](https://hypothesis.works/)Python 的框架[<img src="https://api.travis-ci.org/altsysrq/proptest.svg?branch=master">](https://travis-ci.org/altsysrq/proptest)
- [quickcheck](https://crates.io/crates/quickcheck) >>- Rust 的一个[QuickCheck](https://wiki.haskell.org/Introduction_to_QuickCheck1) 实现 [<img src="https://api.travis-ci.org/BurntSushi/quickcheck.svg?branch=master">](https://travis-ci.org/BurntSushi/quickcheck)
- [mockito](https://crates.io/crates/mockito) >>- HTTP 模拟[<img src="https://api.travis-ci.org/lipanski/mockito.svg?branch=master">](https://travis-ci.org/lipanski/mockito)
- [speculate](https://crates.io/crates/speculate) >>- 一个受 RSpec 启发的，Rust 的最小测试框架
- [rust-fuzz/afl.rs](https://github.com/rust-fuzz/afl.rs) >>- 一个 Rust fuzzer，使用[AFL](http://lcamtuf.coredump.cx/afl/) [<img src="https://api.travis-ci.org/rust-fuzz/afl.rs.svg?branch=master">](https://travis-ci.org/rust-fuzz/afl.rs)
- [tarpaulin](https://crates.io/crates/cargo-tarpaulin) >>- 为 Rust 设计的代码覆盖工具[<img src="https://api.travis-ci.org/repositories/xd009642/tarpaulin.svg?branch=master">](https://travis-ci.org/xd009642/tarpaulin)
- [trust](https://github.com/japaric/trust) >>- Travis CI 和 AppVeyor 模板，用于在 5 种体系结构上，测试 Rust crate 并根据 Linux，macOS 和 Windows 发布它的二进制版本

### Transpiling

- [immunant/c2rust](https://github.com/immunant/c2rust) >>- 在 Clang / LLVM 之上构建的， C 到 Rust 转换器和交叉检查器。[![Build Status](https://api.travis-ci.org/immunant/c2rust.svg?branch=master)](https://travis-ci.org/immunant/c2rust)
- [jameysharp/corrode](https://github.com/jameysharp/corrode) >>- 用 Haskell 编写的， C to Rust 转换器。

## 库

### 人工智能

#### 遗传算法

- [Martin1887/oxigen](https://github.com/Martin1887/oxigen) >>- 快速，并行，可扩展和适应性强的遗传算法库。使用此库的示例仅在几秒钟内解决 N = 255 的 N Queens 问题，并使用少于 1 MB 的 RAM。
- [innoave/genevo](https://github.com/innoave/genevo) >>- 以可定制和可扩展的方式执行遗传算法（GA）模拟。
- [willi-kappler/darwin-rs](https://github.com/willi-kappler/darwin-rs) >>- 该库允许您使用 Rust 编程语言编写进化算法（EA）。作者：Willi Kappler，执照：麻省理工学院 - 版本 0.4（2017.06.26）。
- [m-decoster/RsGenetic](https://github.com/m-decoster/RsGenetic) >>- Rust 中的遗传算法库。在维护模式下。
- [mneumann/evo-rs](https://github.com/mneumann/evo-rs) >>- Rust 的进化算法库。 3 年没有变。
- [yurytsoy/revonet](https://github.com/yurytsoy/revonet) >>- 用于解决优化问题和神经网络训练的实际编码 GA 的 Rust 实现。

#### 机器学习

\[[machine learning](https://crates.io/keywords/machine-learning)]

也可以看看[关于 Rust 机器学习的社区](https://medium.com/@autumn_eng/about-rust-s-machine-learning-community-4cda5ec8a790#.hvkp56j3f)。

- [AtheMathmo/rusty-machine](https://github.com/AtheMathmo/rusty-machine) >>- Rust 的机器学习库[![Build Status](https://api.travis-ci.org/AtheMathmo/rusty-machine.svg?branch=master)](https://travis-ci.org/AtheMathmo/rusty-machine)
- [avinashshenoy97/RusticSOM](https://github.com/avinashshenoy97/RusticSOM) >>- 自组织映射（SOM）的 Rust 库。[![Build Status](https://api.travis-ci.org/avinashshenoy97/RusticSOM.svg?branch=master)](https://travis-ci.org/avinashshenoy97/RusticSOM)
- [autumnai/leaf](https://github.com/autumnai/leaf) >>- 开源机器智能框架。[![Build Status](https://api.travis-ci.org/autumnai/leaf.svg?branch=master)](https://travis-ci.org/autumnai/leaf)。被遗弃的项目。最新的分支是[spearow/juice](https://github.com/spearow/juice)。
- [tensorflow/rust](https://github.com/tensorflow/rust) >>- TensorFlow 的 Rust 语言绑定。[![Build Status](https://api.travis-ci.org/tensorflow/rust.svg?branch=master)](https://travis-ci.org/tensorflow/rust)
- [maciejkula/rustlearn](https://github.com/maciejkula/rustlearn) >>- Rust 的机器学习箱。[![Circle CI](https://circleci.com/gh/maciejkula/rustlearn.svg?style=svg)](https://circleci.com/gh/maciejkula/rustlearn)
- [LaurentMazare/tch-rs](https://github.com/LaurentMazare/tch-rs) >>- PyTorch 的 Rust 语言绑定。[![Build Status](https://api.travis-ci.org/LaurentMazare/tch-rs.svg?branch=master)](https://travis-ci.org/LaurentMazare/tch-rs)

### 天文学

\[[astronomy](https://crates.io/keywords/astronomy)]

- [saurvs/astro-rust](https://github.com/saurvs/astro-rust) >>- Rust 的天文学 [<img src="https://api.travis-ci.org/saurvs/astro-rust.svg?branch=master">](https://travis-ci.org/saurvs/astro-rust)
- [fitsio](https://crates.io/crates/fitsio) >>- 包装 cfitsio 的合理接口库[<img src="https://api.travis-ci.org/mindriot101/rust-fitsio.svg?branch=master">](https://travis-ci.org/mindriot101/rust-fitsio)
- [flosse/rust-sun](https://github.com/flosse/rust-sun) >>- JS 库 suncalc 的螃蟹端口[<img src="https://api.travis-ci.org/flosse/rust-sun.svg?branch=master">](https://travis-ci.org/flosse/rust-sun)

### 异步

- [zonyitoo/coio-rs](https://github.com/zonyitoo/coio-rs) >>- 带有工作窃取(working-stealing)调度程序的协程 I/O 库[<img src="https://api.travis-ci.org/zonyitoo/coio-rs.svg?branch=master">](https://travis-ci.org/zonyitoo/coio-rs)
- [dpc/mioco](https://github.com/dpc/mioco) >>- 可扩展，基于协程的异步 IO 处理库[<img src="https://img.shields.io/travis/dpc/mioco/master.svg?style=flat-square" alt="Travis CI Build Status">](https://travis-ci.org/dpc/mioco)
- [TeaEntityLab/fpRust](https://github.com/TeaEntityLab/fpRust) >>- Monad / MonadIO，Handler，Coroutine / doNotation，Rust 的函数式程序功能[<img src="https://api.travis-ci.org/TeaEntityLab/fpRust.svg?branch=master" alt="Travis CI Build Status">](https://travis-ci.org/TeaEntityLab/fpRust)
- [rust-lang-nursery/futures-rs](https://github.com/rust-lang-nursery/futures-rs) >>- Rust 的零成本 futures[<img src="https://api.travis-ci.com/rust-lang-nursery/futures-rs.svg?branch=master" alt="Travis CI Build Status">](https://travis-ci.org/rust-lang-nursery/futures-rs)
- [mio](https://github.com/tokio-rs/mio) >>- MIO 是 Rust 的轻量级 IO 库，专注于在 OS 抽象上，添加尽可能少的开销[<img src="https://api.travis-ci.org/tokio-rs/mio.svg?branch=master">](https://travis-ci.org/tokio-rs/mio)
- [Xudong-Huang/may](https://github.com/Xudong-Huang/may) >>- 螃蟹 stackful 的协程库[<img src="https://api.travis-ci.org/Xudong-Huang/may.svg?branch=master">](https://travis-ci.org/Xudong-Huang/may)
- [rustasync/runtime](https://github.com/rustasync/runtime) >>- 可在未知运行时下的 API，旨在使异步感觉像 stdlib 的一部分[![Crates.io](https://img.shields.io/crates/v/runtime.svg?style=flat-square)](https://crates.io/crates/runtime) [![Build status](https://img.shields.io/azure-devops/build/yoshuawuyts/rustasync/2/master.svg?style=flat-square)](https://dev.azure.com/yoshuawuyts/rustasync/_build?definitionId=2)

### 音频

\[[audio](https://crates.io/keywords/audio)]

- [GuillaumeGomez/rust-fmod](https://github.com/GuillaumeGomez/rust-fmod) >>- [FMOD](https://www.fmod.com)绑定 [![Build Status](https://api.travis-ci.org/GuillaumeGomez/rust-fmod.svg?branch=master)](https://travis-ci.org/GuillaumeGomez/rust-fmod)
- [jhasse/ears](https://github.com/jhasse/ears) >>- 一个简单的库，可以在 OpenAL 和 libsndfile 之上，播放声音和音乐[<img src="https://api.travis-ci.org/jhasse/ears.svg?branch=master">](https://travis-ci.org/jhasse/ears)
- [jpernst/alto](https://github.com/jpernst/alto) >>- OpenAL 1.1 绑定 [<img src="https://api.travis-ci.org/jpernst/alto.svg?branch=master">](https://travis-ci.org/jpernst/alto)
- [musitdev/portmidi-rs](https://github.com/musitdev/portmidi-rs) >>- [PortMidi](http://portmedia.sourceforge.net/portmidi/)绑定 [<img src="https://api.travis-ci.org/musitdev/portmidi-rs.svg?branch=master">](https://travis-ci.org/musitdev/portmidi-rs)
- [hound](https://crates.io/crates/hound) >>- WAV 编码和解码库[<img src="https://api.travis-ci.org/ruuda/hound.svg?branch=master">](https://travis-ci.org/ruuda/hound)
- [tomaka/rodio](https://github.com/RustAudio/rodio) >>- Rust 音频播放库[![Build Status](https://api.travis-ci.org/tomaka/rodio.svg?branch=master)](https://travis-ci.org/tomaka/rodio)
- [RustAudio](https://github.com/RustAudio)
  - [RustAudio/rust-portaudio](https://github.com/RustAudio/rust-portaudio) >>- [PortAudio](http://www.portaudio.com/)绑定 [<img src="https://api.travis-ci.org/RustAudio/rust-portaudio.svg?branch=master">](https://travis-ci.org/RustAudio/rust-portaudio)

### 认证

- [Keats/jsonwebtoken](https://github.com/Keats/jsonwebtoken) >>- 螃蟹的 [JSON Web Token](https://en.wikipedia.org/wiki/JSON_Web_Token) lib[![Build Status](https://api.travis-ci.org/Keats/jsonwebtoken.svg?branch=master)](https://travis-ci.org/Keats/jsonwebtoken)

### 汽车

- [canparse](https://crates.io/crates/canparse) >>- CAN 信号和定义解析器[<img src="https://api.travis-ci.org/jmagnuson/canparse.svg?branch=master">](https://travis-ci.org/jmagnuson/canparse)
- [j2534](https://crates.io/crates/j2534) >>- J2534 PassThru 绑定
- [JulianSchmid/dlt_parse](https://github.com/JulianSchmid/dlt-parse-rs) >>- Rust DLT（诊断日志和跟踪）数据包解析器[<img src="https://api.travis-ci.org/JulianSchmid/dlt-parse-rs.svg?branch=master">](https://travis-ci.org/JulianSchmid/dlt-parse-rs)
- [JulianSchmid/someip_parse](https://github.com/JulianSchmid/someip-parse-rs) \[[someip_parse](https://crates.io/crates/someip_parse)] - 用于解析 SOME / IP 网络协议的库（无有效负载解释）[<img src="https://api.travis-ci.org/JulianSchmid/someip-parse-rs.svg?branch=master">](https://travis-ci.org/JulianSchmid/someip-parse-rs)
- [LibreTuner/tuneutils](https://github.com/LibreTuner/tuneutils) \[[tuneutils](https://crates.io/crates/tuneutils)] - 用于连接，诊断和调整汽车的实用程序
- [marcelbuesing/can-dbc](https://github.com/marcelbuesing/can-dbc) \[[can-dbc](https://crates.io/crates/can-dbc)] - DBC 格式的解析器[<img src="https://api.travis-ci.org/marcelbuesing/can-dbc.svg?branch=dev">](https://travis-ci.org/marcelbuesing/can-dbc)
- [marcelbuesing/tokio-socketcan-bcm](https://github.com/marcelbuesing/tokio-socketcan-bcm) \[[tokio-socketcan-bcm](https://crates.io/crates/tokio-socketcan-bcm)] - Linux SocketCAN BCM，支持 tokio[<img src="https://api.travis-ci.org/marcelbuesing/tokio-socketcan-bcm.svg?branch=master">](https://travis-ci.org/marcelbuesing/tokio-socketcan-bcm)
- [mbr/socketcan](https://github.com/mbr/socketcan-rs) \[[socketcan](https://crates.io/crates/socketcan)] - Linux SocketCAN 库[<img src="https://api.travis-ci.org/mbr/socketcan-rs.svg?branch=master">](https://travis-ci.org/mbr/socketcan-rs)
- [oefd/tokio-socketcan](https://github.com/oefd/tokio-socketcan) [\[tokio-socketcan\]](https://crates.io/crates/tokio-socketcan)] - Linux SocketCAN，支持基于 socketcan 箱的 tokio
- [Sensirion/lin-bus](https://github.com/Sensirion/lin-bus-rs) \[[lin-bus](https://crates.io/crates/lin-bus)] - LIN 总线驱动程序的特性和协议实现[<img src="https://circleci.com/gh/Sensirion/lin-bus-rs.svg?style=svg">](https://circleci.com/gh/Sensirion/lin-bus-rs)

### 生物信息学

- [Rust-Bio](https://github.com/rust-bio) >>- Rust 的生物信息学库。

### 高速缓存

- [jaysonsantos/bmemcached-rs](https://github.com/jaysonsantos/bmemcached-rs) >>- 用纯螃蟹写的 Memcached 库[<img src="https://api.travis-ci.org/jaysonsantos/bmemcached-rs.svg?branch=master">](https://travis-ci.org/jaysonsantos/bmemcached-rs)
- [jaemk/cached](https://github.com/jaemk/cached) >>- 简单的 缓存/记忆 函数
- [aisk/rust-memcache](https://github.com/aisk/rust-memcache) >>- Memcached 客户端库[<img src="https://api.travis-ci.org/aisk/rust-memcache.svg?branch=master">](https://travis-ci.org/aisk/rust-memcache)

### 并发

- [aymanmadkour/glock](https://github.com/aymanmadkour/glock) >>- Rust 的多粒度锁（Granular locking）箱子。[<img src="https://api.travis-ci.org/aymanmadkour/glock.svg?branch=master">](https://travis-ci.org/aymanmadkour/glock)
- [crossbeam-rs/crossbeam](https://github.com/crossbeam-rs/crossbeam) >>- Rust 支持并行性和低级并发性[<img src="https://api.travis-ci.org/crossbeam-rs/crossbeam.svg?branch=master">](https://travis-ci.org/crossbeam-rs/crossbeam)
- [orium/archery](https://github.com/orium/archery) \[[archery](https://crates.io/crates/archery)] - 从`Rc`/`Arc`指针类型抽象出来的 库。[<img src="https://api.travis-ci.org/orium/archery.svg?branch=master">](https://travis-ci.org/orium/archery)
- [pop-os/bus-writer](https://github.com/pop-os/bus-writer) >>- 通用单-reader，多-writer
- [Rayon](https://github.com/rayon-rs/rayon) >>- Rust 的数据并行库[<img src="https://api.travis-ci.org/rayon-rs/rayon.svg?branch=master">](https://travis-ci.org/rayon-rs/rayon)
- [rustcc/coroutine-rs](https://github.com/rustcc/coroutine-rs) >>- Rust Coroutine 库[<img src="https://img.shields.io/travis/rustcc/coroutine-rs.svg">](https://travis-ci.org/rustcc/coroutine-rs)
- [zonyitoo/coio-rs](https://github.com/zonyitoo/coio-rs) >>- Rust Coroutine I/O.[<img src="https://api.travis-ci.org/zonyitoo/coio-rs.svg?branch=master">](https://travis-ci.org/zonyitoo/coio-rs)

### 云

- AWS \[[aws](https://crates.io/keywords/aws)]
  - [rusoto/rusoto](https://github.com/rusoto/rusoto) >>- [<img src="https://api.travis-ci.org/rusoto/rusoto.svg?branch=master">](https://travis-ci.org/rusoto/rusoto)

### 命令行

- 参数解析
  - [clap-rs](https://github.com/clap-rs/clap) \[[clap](https://crates.io/crates/clap)] - 一个简单易用，功能齐全的命令行参数解析器[<img src="https://api.travis-ci.com/clap-rs/clap-rs.svg?branch=master">](https://travis-ci.org/clap-rs/clap-rs)
  - [docopt/docopt.rs](https://github.com/docopt/docopt.rs) \[[docopt](https://crates.io/crates/docopt)] - Rust 的[DocOpt](http://docopt.org) 实现 [<img src="https://api.travis-ci.org/docopt/docopt.rs.svg?branch=master">](https://travis-ci.org/docopt/docopt.rs)
  - [TeXitoi/structopt](https://github.com/TeXitoi/structopt) \[[structopt](https://crates.io/crates/structopt)] - 通过定义一个结构，来解析命令行参数[<img src="https://api.travis-ci.org/TeXitoi/structopt.svg?branch=master">](https://travis-ci.org/TeXitoi/structopt)
  - [killercup/quicli](https://github.com/killercup/quicli) \[[quicli](https://crates.io/crates/quicli)] - 在 Rust 中，快速构建很酷的 CLI 应用程序[<img src="https://api.travis-ci.org/killercup/quicli.svg">](https://travis-ci.org/killercup/quicli)
- 以人为本的设计
  - [rust-cli/human-panic](https://github.com/rust-cli/human-panic) \[[human-panic](https://crates.io/crates/human-panic)] - 人类的 panic 信息[<img src="https://api.travis-ci.org/rust-cli/human-panic.svg">](https://travis-ci.org/rust-cli/human-panic)
- Line 编辑器
  - [srijs/rust-copperline](https://github.com/srijs/rust-copperline) \[[copperline](https://crates.io/crates/copperline)] - 纯-Rust 命令行编辑库
  - [MovingtoMars/liner](https://github.com/MovingtoMars/liner) \[[liner](https://crates.io/crates/liner)] - 提供类似 readline 功能的库[<img src="https://api.travis-ci.org/MovingtoMars/liner.svg">](https://travis-ci.org/MovingtoMars/liner)
  - [murarth/linefeed](https://github.com/murarth/linefeed) \[[linefeed](https://crates.io/crates/linefeed)] - 可配置，可扩展的交互式线路阅读器[<img src="https://api.travis-ci.org/murarth/linefeed.svg">](https://travis-ci.org/murarth/linefeed)
  - [kkawakam/rustyline](https://github.com/kkawakam/rustyline) \[[rustyline](https://crates.io/crates/rustyline)] - Rust 中的 readline 实现[<img src="https://api.travis-ci.org/kkawakam/rustyline.svg?branch=master">](https://travis-ci.org/kkawakam/rustyline)
- 管道
  - [imp/pager-rs](https://gitlab.com/imp/pager-rs) \[[pager](https://crates.io/crates/pager)] - 通过一个外部 pager，对输出管道化[<img src="https://gitlab.com/imp/pager-rs/badges/master/build.svg">](https://gitlab.com/imp/pager-rs/pipelines)
  - [hniksic/rust-subprocess](https://github.com/hniksic/rust-subprocess) \[[subprocess](https://crates.io/crates/subprocess)] - 与外部管道交互的设施[<img src="https://api.travis-ci.org/hniksic/rust-subprocess.svg?branch=master">](https://travis-ci.org/hniksic/rust-subprocess)
  - [oconnor663/duct.rs](https://github.com/oconnor663/duct.rs) \[[duct](https://crates.io/crates/duct)] - 子进程管道化和 IO 重定向的构建器[<img src="https://api.travis-ci.org/oconnor663/duct.rs.svg?branch=master">](https://travis-ci.org/oconnor663/duct.rs)
  - [philippkeller/rexpect](https://github.com/philippkeller/rexpect) \[[rexpect](https://crates.io/crates/rexpect)] - 自动化交互式应用程序，如 ssh，ftp，passwd 等[<img src="https://api.travis-ci.org/philippkeller/rexpect.svg?branch=master">](https://travis-ci.org/philippkeller/rexpect)
- 进展
  - [mitsuhiko/indicatif](https://github.com/mitsuhiko/indicatif) \[[indicatif](https://crates.io/crates/indicatif)] - 向用户表明进度
  - [a8m/pb](https://github.com/a8m/pb) \[[pbr](https://crates.io/crates/pbr)] - Rust 的控制台进度条
  - [FGRibreau/spinners](https://github.com/FGRibreau/spinners) \[[spinners](https://crates.io/crates/spinners)] - 60 多个优雅的终端旋转器
- 提示
  - [hashmismatch/terminal_cli.rs](https://github.com/hashmismatch/terminal_cli.rs) \[[terminal_cli](https://crates.io/crates/terminal_cli)] - 构建一个交互式命令提示符[<img src="https://api.travis-ci.org/hashmismatch/terminal_cli.rs.svg?branch=master">](https://travis-ci.org/hashmismatch/terminal_cli.rs)
  - [starship/starship](https://starship.rs/) [[starship](https://crates.io/crates/starship)]  — 小，快，高定制的命令提示符，用于任意 shell [![Build status](https://badgen.net/azure-pipelines/starship-control/starship/Starship%20Test%20Suite)](https://dev.azure.com/starship-control/starship/_build)
- 样式
  - [ogham/rust-ansi-term](https://github.com/ogham/rust-ansi-term) \[[ansi_term](https://crates.io/crates/ansi_term)] - 控制 ANSI 终端上的颜色和格式[<img src="https://api.travis-ci.org/ogham/rust-ansi-term.svg?branch=master">](https://travis-ci.org/ogham/rust-ansi-term)
  - [LukasKalbertodt/term-painter](https://github.com/LukasKalbertodt/term-painter) \[[term-painter](https://crates.io/crates/term-painter)] - 跨平台风格的终端输出[<img src="https://img.shields.io/travis/LukasKalbertodt/term-painter/master.svg">](https://travis-ci.org/LukasKalbertodt/term-painter)
  - [vitiral/termstyle](https://github.com/vitiral/termstyle) \[[termstyle](https://docs.rs/termstyle/0.1.2/termstyle/)] - 构建（和测试）格式化和样式化的命令行应用程序
  - [SergioBenitez/yansi](https://github.com/SergioBenitez/yansi) \[[yansi](https://crates.io/crates/yansi)] - 一个简单的 ANSI 终端颜色绘图库
- TUI
  - [TimonPost/crossterm](https://github.com/crossterm-rs/crossterm) \[[crossterm](https://crates.io/crates/crossterm)] - 跨平台终端库
  - [gyscos/Cursive](https://github.com/gyscos/Cursive) \[[cursive](https://crates.io/crates/cursive)] - 构建丰富的 TUI 应用程序[<img src="https://api.travis-ci.org/gyscos/Cursive.svg?branch=master">](https://travis-ci.org/gyscos/Cursive)
  - [ogham/rust-term-grid](https://github.com/ogham/rust-term-grid) \[[term_grid](https://crates.io/crates/term_grid)] - 网格化的 Rust 库[<img src="https://api.travis-ci.org/ogham/rust-term-grid.svg?branch=master">](https://travis-ci.org/ogham/rust-term-grid)
  - [ticki/termion](https://github.com/redox-os/termion) \[[termion](https://crates.io/crates/termion)] - 用于控制终端/ TTY 的无绑定库[<img src="https://api.travis-ci.com/ticki/termion.svg?branch=master">](https://travis-ci.org/ticki/termion)
  - [fdehau/tui-rs](https://github.com/fdehau/tui-rs) \[[tui](https://crates.io/crates/tui)] - 受到[blessed-contrib](https://github.com/yaronn/blessed-contrib)和[termui](https://github.com/gizak/termui)启发的 TUI 库 [<img src="https://api.travis-ci.org/fdehau/tui-rs.svg?branch=master">](https://travis-ci.org/fdehau/tui-rs)
  - BearLibTerminal
    - [cfyzium/bearlibterminal](https://github.com/nabijaczleweli/BearLibTerminal.rs) \[[bear-lib-terminal](https://crates.io/crates/bear-lib-terminal)] -[BearLibTerminal](https://bitbucket.org/cfyzium/bearlibterminal)绑定 [<img src="https://api.travis-ci.org/nabijaczleweli/BearLibTerminal.rs.svg?branch=master">](https://travis-ci.org/nabijaczleweli/BearLibTerminal.rs)
  - ncurses
    - [jeaye/ncurses-rs](https://github.com/jeaye/ncurses-rs) \[[ncurses](https://crates.io/crates/ncurses)] -[ncurses](https://www.gnu.org/software/ncurses/)绑定 [<img src="https://api.travis-ci.org/jeaye/ncurses-rs.svg?branch=master">](https://travis-ci.org/jeaye/ncurses-rs)
    - [ihalila/pancurses](https://github.com/ihalila/pancurses) \[[pancurses](https://crates.io/crates/pancurses)] - curses 库，支持 linux 和 windows[<img src="https://api.travis-ci.org/ihalila/pancurses.svg?branch=master">](https://travis-ci.org/ihalila/pancurses)
  - Termbox
    - [gchp/rustbox](https://github.com/gchp/rustbox) \[[rustbox](https://crates.io/crates/rustbox)] - [Termbox](https://github.com/nsf/termbox) 绑定 [<img src="https://api.travis-ci.org/gchp/rustbox.svg?branch=master">](https://travis-ci.org/gchp/rustbox)

### 压缩

- [Brotli](https://opensource.googleblog.com/2015/09/introducing-brotli-new-compression.html)
  - [ende76/brotli-rs](https://github.com/ende76/brotli-rs) >>- Brotli 压缩实现
  - [dropbox/rust-brotli](https://github.com/dropbox/rust-brotli) >>- Rust 中的 Brotli 解压缩程序，可以选择性地避免使用 stdlib
- bzip2
  - [alexcrichton/bzip2-rs](https://github.com/alexcrichton/bzip2-rs) >>- [libbz2](http://www.bzip.org)绑定 [<img src="https://api.travis-ci.com/alexcrichton/bzip2-rs.svg?branch=master">](https://travis-ci.org/alexcrichton/bzip2-rs)
- gzip
  - [carols10cents/zopfli](https://github.com/carols10cents/zopfli) >>- 实现[Zopfli](https://github.com/google/zopfli)压缩算法，用于更高质量的 deflate 或 zlib 压缩
- miniz
  - [alexcrichton/flate2-rs](https://github.com/alexcrichton/flate2-rs) >>- [miniz](https://code.google.com/archive/p/miniz)绑定 [<img src="https://api.travis-ci.com/alexcrichton/flate2-rs.svg?branch=master">](https://travis-ci.org/alexcrichton/flate2-rs)
- snappy
  - [JeffBelgum/rust-snappy](https://github.com/JeffBelgum/rust-snappy) >>- [snappy](https://github.com/google/snappy)绑定 [<img src="https://api.travis-ci.org/JeffBelgum/rust-snappy.svg?branch=master">](https://travis-ci.org/JeffBelgum/rust-snappy)
- tar
  - [alexcrichton/tar-rs](https://github.com/alexcrichton/tar-rs) >>- 在 Rust 中读取/写入 tar 档案[<img src="https://api.travis-ci.com/alexcrichton/tar-rs.svg?branch=master">](https://travis-ci.org/alexcrichton/tar-rs)
- zip
  - [mvdnes/zip-rs](https://github.com/mvdnes/zip-rs) >>- 读取和写入 ZIP 存档[![Build Status](https://api.travis-ci.org/mvdnes/zip-rs.svg?branch=master)](https://travis-ci.org/mvdnes/zip-rs)

### 计算

- [argmin-rs/argmin](https://github.com/argmin-rs/argmin) \[[argmin](https://crates.io/crates/argmin)] - 纯 Rust 优化库[<img src="https://api.travis-ci.org/argmin-rs/argmin.svg?branch=master">](https://travis-ci.org/argmin-rs/argmin)
- [BLAS](https://en.wikipedia.org/wiki/Basic_Linear_Algebra_Subprograms) \[[blas](https://crates.io/keywords/blas)]
  - [mikkyang/rust-blas](https://github.com/mikkyang/rust-blas) >>- BLAS 绑定
  - [stainless-steel/blas](https://github.com/blas-lapack-rs/blas) >>- BLAS 绑定 [<img src="https://api.travis-ci.org/blas-lapack-rs/blas.svg?branch=master">](https://travis-ci.org/blas-lapack-rs/blas)
- [Conjugate Gradient](https://en.wikipedia.org/wiki/Limited-memory_BFGS)
  - [noshu/cg-sys](https://github.com/noshu/cg-sys) >>- fortran CG +子程序的 Rust 绑定
- [GMP](https://gmplib.org/)
  - [fizyk20/rust-gmp](https://github.com/fizyk20/rust-gmp) >>- libgmp 绑定 [<img src="https://api.travis-ci.org/fizyk20/rust-gmp.svg?branch=master">](https://travis-ci.org/fizyk20/rust-gmp)
- [GSL](http://www.gnu.org/software/gsl/)
  - [GuillaumeGomez/rust-GSL](https://github.com/GuillaumeGomez) >>- GSL 绑定 [<img src="https://api.travis-ci.org/GuillaumeGomez/rust-GSL.svg?branch=master">](https://travis-ci.org/GuillaumeGomez/rust-GSL)
- [LAPACK](https://en.wikipedia.org/wiki/LAPACK)
  - [stainless-steel/lapack](https://github.com/blas-lapack-rs/lapack) >>- LAPACK 绑定 [<img src="https://api.travis-ci.org/blas-lapack-rs/lapack.svg?branch=master">](https://travis-ci.org/blas-lapack-rs/lapack)
- [L-BFGS-B](https://en.wikipedia.org/wiki/Limited-memory_BFGS)
  - [noshu/lbfgsb-sys](https://github.com/noshu/lbfgsb-sys) >>- Fortran L-BFGS-B 子程序的 Rust 绑定
- [rustsim/nalgebra](https://github.com/rustsim/nalgebra) >>- 低维线性代数库[<img src="https://api.travis-ci.org/rustsim/nalgebra.svg?branch=master">](https://travis-ci.org/rustsim/nalgebra)
- 平行
  - [arrayfire/arrayfire-rust](https://github.com/arrayfire/arrayfire-rust) >>- [Arrayfire](https://arrayfire.com/)绑定
  - [autumnai/collenchyma](https://github.com/autumnai/collenchyma) >>- 可扩展，可插入，后端无关的框架，用于在 CUDA，OpenCL 和通用主机 CPU 上进行并行，高性能计算。[<img src="https://api.travis-ci.org/autumnai/collenchyma.svg?branch=master">](https://travis-ci.org/autumnai/collenchyma)
  - [luqmana/rust-opencl](https://github.com/luqmana/rust-opencl) >>- [OpenCL](https://www.khronos.org/opencl/)绑定 [<img src="https://api.travis-ci.org/luqmana/rust-opencl.svg?branch=master">](https://travis-ci.org/luqmana/rust-opencl)
- Scirust
  - [indigits/scirust](https://github.com/indigits/scirust) >>- Rust 的科学计算库[![Build Status](https://api.travis-ci.org/indigits/scirust.svg?branch=master)](https://travis-ci.org/indigits/scirust)
- Statrs
  - [boxtown/statrs](https://github.com/boxtown/statrs) >>- Rust 中强大的统计计算库[![Build Status](https://api.travis-ci.org/boxtown/statrs.svg?branch=master)](https://travis-ci.org/boxtown/statrs)
- Rustimization \[[rustimization](https://crates.io/crates/rustimization)]
  - [noshu/rustimization](https://github.com/noshu/rustimization) >>- Rust 优化库，包括 L-BFGS-B 和 Conjugate Gradient 算法
- [calebwin/emu](https://github.com/calebwin/emu) >>- 来自 Rust 宏， 给 GPGPU 数值的计算语言

### 配置

- [mehcode/config-rs](https://github.com/mehcode/config-rs)\[[config](https://crates.io/crates/config)] - Rust 应用程序的分层配置系统（对 12-factor 应用程序强大支持）。[<img src="https://api.travis-ci.org/mehcode/config-rs.svg?branch=master">](https://travis-ci.org/mehcode/config-rs)
- [Kixunil/configure_me](https://github.com/Kixunil/configure_me)\[[configure_me](https://crates.io/crates/configure_me)] - 用于轻松处理应用程序配置的库

### 加密

\[[crypto](https://crates.io/keywords/crypto)，[cryptography](https://crates.io/keywords/cryptography)]

- [briansmith/ring](https://github.com/briansmith/ring) >>- 使用 Rust 和 BoringSSL 的加密原语，做到安全，快速，小型加密。[<img src="https://api.travis-ci.org/briansmith/ring.svg?branch=master">](https://travis-ci.org/briansmith/ring)
- [briansmith/webpki](https://github.com/briansmith/webpki) >>- Rust 中的 Web PKI TLS X.509 证书验证。[<img src="https://api.travis-ci.org/briansmith/webpki.svg?branch=master">](https://travis-ci.org/briansmith/webpki)
- [brycx/orion](https://github.com/brycx/orion) >>- 该库旨在提供简单实用的加密。“可用”意味着公开易于使用，且难以滥用的高级 API。[<img src="https://api.travis-ci.org/brycx/orion.svg?branch=master">](https://travis-ci.org/brycx/orion)
- [ctz/rustls](https://github.com/ctz/rustls) >>- TLS 的 Rust 实现
- [DaGenix/rust-crypto](https://github.com/DaGenix/rust-crypto) >>- Rust 中的加密算法[<img src="https://api.travis-ci.org/DaGenix/rust-crypto.svg?branch=master">](https://travis-ci.org/DaGenix/rust-crypto)
- [dnaq/sodiumoxide](https://github.com/sodiumoxide/sodiumoxide) >>- [libsodium](https://github.com/jedisct1/libsodium)绑定 [<img src="https://api.travis-ci.com/dnaq/sodiumoxide.svg?branch=master">](https://travis-ci.org/dnaq/sodiumoxide)
- [doublify/libblockchain](https://github.com/doublify/libblockchain) >>- 区块链实现[<img src="https://api.travis-ci.org/doublify/libblockchain.svg?branch=master">](https://travis-ci.org/doublify/libblockchain)
- [exonum/exonum](https://github.com/exonum/exonum)\[[exonum](https://crates.io/crates/exonum)] - 区块链项目的可扩展框架[<img src="https://api.travis-ci.com/exonum/exonum.svg?branch=master">](https://travis-ci.org/exonum/exonum)
- [klutzy/suruga](https://github.com/klutzy/suruga) >>- Rust 的一个实现[TLS 1.2](https://tools.ietf.org/html/rfc5246)
- [libOctavo/octavo](https://github.com/libOctavo/octavo) >>- Rust 中的模块化哈希和加密库[<img src="https://api.travis-ci.org/libOctavo/octavo.svg?branch=master">](https://travis-ci.org/libOctavo/octavo)
- [RustCrypto/hashes](https://github.com/RustCrypto/hashes) >>- 用纯 Rust 编写的加密哈希函数的集合[<img src="https://api.travis-ci.org/RustCrypto/hashes.svg?branch=master">](https://travis-ci.org/RustCrypto/hashes)
- [rustindia/mpw-rs](https://github.com/rustindia/mpw-rs) >>- Master Password 密码管理器的 纯 Rust 实现[<img src="https://api.travis-ci.org/rustindia/mpw-rs.svg?branch=master">](https://travis-ci.org/rustindia/mpw-rs)
- [Fraunhofer-AISEC/rabe](https://github.com/Fraunhofer-AISEC/rabe) >>- 提供多种基于属性的加密（ABE）方案的库
- [racum/rust-djangohashers](https://github.com/racum/rust-djangohashers) >>- Django 项目中使用的密码原语的 Rust 端口。它不需要 Django，只根据其样式，哈希并验证密码。[<img src="https://api.travis-ci.org/Racum/rust-djangohashers.svg?branch=master">](https://travis-ci.org/Racum/rust-djangohashers)
- [RNCryptor/rncryptor-rs](https://github.com/RNCryptor/rncryptor-rs) >>- RNCryptor AES 文件格式的 纯 Rust 实现
- [conradkdotcom/rooster](https://github.com/conradkdotcom/rooster)\[[rooster](https://crates.io/crates/rooster)] - 在终端中，使用的简单密码管理器
- [sfackler/rust-native-tls](https://github.com/sfackler/rust-native-tls) >>- 原生 TLS 库的绑定
- [sfackler/rust-openssl](https://github.com/sfackler/rust-openssl) >>- [OpenSSL](https://www.openssl.org/)绑定 [<img src="https://api.travis-ci.org/sfackler/rust-openssl.svg?branch=master">](https://travis-ci.org/sfackler/rust-openssl)
- [kornelski/rust-security-framework](https://github.com/kornelski/rust-security-framework) >>- 安全框架的绑定（OSX 原生）
- [steffengy/schannel-rs](https://github.com/steffengy/schannel-rs) >>- Schannel 的绑定（Windows 原生 TLS）
- [zebradil/rustotpony](https://github.com/zebradil/rustotpony) >>- 一次性密码生成器的 CLI 管理器，即 Google Authenticator（TOTP）

### 数据库

\[[database](https://crates.io/keywords/database)]

- [sfackler/r2d2](https://github.com/sfackler/r2d2) >>- 通用连接池 [<img src="https://api.travis-ci.org/sfackler/r2d2.svg?branch=master">](https://travis-ci.org/sfackler/r2d2)
- NoSQL \[[nosql](https://crates.io/keywords/nosql)]

  - [ArangoDB](https://www.arangodb.com)
    - [Rincon](https://github.com/innoave/rincon) >>- Rust 的 ArangoDB（NoSQL 和 Graph store）驱动程序
  - [Cassandra](http://cassandra.apache.org)\[[cassandra](https://crates.io/keywords/cassandra)，[cql](https://crates.io/keywords/cql)]
    - [AlexPikalov/cdrs](https://github.com/AlexPikalov/cdrs)\[[cdrs](https://crates.io/crates/cdrs)] - 用 Rust 编写的原生客户端[<img src="https://api.travis-ci.org/AlexPikalov/cdrs.svg?branch=master">](https://travis-ci.org/AlexPikalov/cdrs)
    - [Metaswitch/cassandra-rs](https://github.com/Metaswitch/cassandra-rs) >>- 绑定到 DataStax C/C ++ 客户端[<img src="https://api.travis-ci.org/Metaswitch/cassandra-rs.svg?branch=master">](https://travis-ci.org/Metaswitch/cassandra-rs)
  - CouchDB \[[couchdb](https://crates.io/keywords/couchdb)]
    - [chill-rs/chill](https://github.com/chill-rs/chill)\[[couchdb](https://crates.io/crates/chill)] - CouchDB REST API 的 Rust 客户端[<img src="https://api.travis-ci.org/chill-rs/chill.svg?branch=master">](https://travis-ci.org/chill-rs/chill)
    - [Sofa](https://github.com/YellowInnovation/sofa) >>- CouchDB HTTP REST API 的接口，用于稳定螃蟹
  - Elasticsearch \[[elasticsearch](https://crates.io/keywords/elasticsearch)]
    - [benashford/rs-es](https://github.com/benashford/rs-es) \[[rs-es](https://crates.io/crates/rs-es)] - Rust 的客户端[Elastic](https://www.elastic.co/) REST API [<img src="https://api.travis-ci.org/benashford/rs-es.svg?branch=master">](https://travis-ci.org/benashford/rs-es)
    - [elastic-rs/elastic-reqwest](https://github.com/elastic-rs/elastic-reqwest) \[[elastic_reqwest](https://crates.io/crates/elastic_reqwest)] - 基于 Reqwest 的 Elasticsearch API 的轻量级实现[<img src="https://api.travis-ci.org/elastic-rs/elastic-reqwest.svg">](https://travis-ci.org/elastic-rs/elastic-reqwest)
  - etcd
    - [jimmycuadra/rust-etcd](https://github.com/jimmycuadra/rust-etcd) \[[etcd](https://crates.io/crates/etcd)] - CoreOS 的 etcd 客户端库。[<img src="https://api.travis-ci.org/jimmycuadra/rust-etcd.svg?branch=master">](https://travis-ci.org/jimmycuadra/rust-etcd)
  - ForestDB
    - [vhbit/sherwood](https://github.com/vhbit/sherwood) >>- [ForestDB](https://github.com/couchbase/forestdb)绑定 [<img src="https://api.travis-ci.org/vhbit/sherwood.svg?branch=master">](https://travis-ci.org/vhbit/sherwood)
  - [InfluxDB](https://www.influxdata.com/)
    - [panoptix-za/influxdb-rs](https://github.com/panoptix-za/influxdb-rs) >>- 异步接口[<img src="https://api.travis-ci.org/panoptix-za/influxdb-rs.svg?branch=master">](https://travis-ci.org/panoptix-za/influxdb-rs)
    - [driftluo/InfluxDBClient-rs](https://github.com/driftluo/InfluxDBClient-rs) >>- 同步接口[<img src="https://api.travis-ci.org/driftluo/InfluxDBClient-rs.svg?branch=master">](https://travis-ci.org/driftluo/InfluxDBClient-rs)
  - LevelDB
    - [skade/leveldb](https://github.com/skade/leveldb) >>- [LevelDB](https://github.com/google/leveldb)绑定 [<img src="https://api.travis-ci.org/skade/leveldb.svg?branch=master">](https://travis-ci.org/skade/leveldb)
  - LMDB \[[lmdb](https://crates.io/keywords/lmdb)]
    - [vhbit/lmdb-rs](https://github.com/vhbit/lmdb-rs) \[[lmdb-rs](https://crates.io/crates/lmdb-rs)] -[LMDB](https://symas.com/lmdb/)绑定 [<img src="https://api.travis-ci.org/vhbit/lmdb-rs.svg?branch=master">](https://travis-ci.org/vhbit/lmdb-rs)
  - MongoDB \[[mongodb](https://crates.io/keywords/mongodb)]
    - [mongodb-labs/mongo-rust-driver-prototype](https://github.com/mongodb-labs/mongo-rust-driver-prototype) \[[mongodb](https://crates.io/crates/mongodb)] -[MongoDB](https://www.mongodb.com/)绑定 [<img src="https://api.travis-ci.org/mongodb-labs/mongo-rust-driver-prototype.svg">](https://travis-ci.org/mongodb-labs/mongo-rust-driver-prototype)
  - Neo4j \[[cypher](https://crates.io/keywords/cypher)，[neo4j](https://crates.io/keywords/neo4j)]
  - Redis \[[redis](https://crates.io/keywords/redis)]
    - [mitsuhiko/redis-rs](https://github.com/mitsuhiko/redis-rs) >>- [Redis](https://redis.io/)Rust 库[<img src="https://api.travis-ci.org/mitsuhiko/redis-rs.svg?branch=master">](https://travis-ci.org/mitsuhiko/redis-rs)
  - [RocksDB](https://rocksdb.org/)
    - [rust-rocksdb/rust-rocksdb](https://github.com/rust-rocksdb/rust-rocksdb) >>- RocksDB 绑定 [<img src="https://api.travis-ci.org/rust-rocksdb/rust-rocksdb.svg?branch=master">](https://travis-ci.org/rust-rocksdb/rust-rocksdb)
  - [UnQLite](https://unqlite.org/)
    - [zitsen/unqlite.rs](https://github.com/zitsen/unqlite.rs) >>- UnQLite 绑定 [<img src="https://api.travis-ci.org/zitsen/unqlite.rs.svg?branch=master">](https://travis-ci.org/zitsen/unqlite.rs)
  - [ZooKeeper](https://zookeeper.apache.org/)
    - [bonifaido/rust-zookeeper](https://github.com/bonifaido/rust-zookeeper) \[[zookeeper](https://crates.io/crates/zookeeper)] - Apache ZooKeeper 的客户端库。[<img src="https://api.travis-ci.org/bonifaido/rust-zookeeper.svg?branch=master">](https://travis-ci.org/bonifaido/rust-zookeeper)
  - [PickleDB](https://pythonhosted.org/pickleDB/)
    - [seladb/pickledb-rs](https://github.com/seladb/pickledb-rs) >>- 一个轻量级和简单的键值存储，受 Python 的 PickleDB 的启发。[<img src="https://api.travis-ci.org/seladb/pickledb-rs.svg?branch=master">](https://travis-ci.org/seladb/pickledb-rs)

- SQL \[[sql](https://crates.io/keywords/sql)]
  - Microsoft SQL
    - [steffengy/tiberius](https://github.com/steffengy/tiberius) >>- [<img src="https://api.travis-ci.org/steffengy/tiberius.svg?branch=master">](https://travis-ci.org/steffengy/tiberius)
  - MySql \[[mysql](https://crates.io/keywords/mysql)]
    - [AgilData/mysql-proxy-rs](https://github.com/AgilData/mysql-proxy-rs) >>- MySQL 代理[<img src="https://api.travis-ci.org/AgilData/mysql-proxy-rs.svg?branch=master">](https://travis-ci.org/AgilData/mysql-proxy-rs)
    - [blackbeam/mysql_async](https://github.com/blackbeam/mysql_async) \[[mysql_async](https://crates.io/crates/mysql_async)] - 基于 Tokio 的 异步化， Rust Mysql 驱动程序。[![CircleCI](https://circleci.com/gh/blackbeam/mysql_async/tree/master.svg?style=shield)](https://circleci.com/gh/blackbeam/mysql_async/tree/master)
    - [blackbeam/rust-mysql-simple](https://github.com/blackbeam/rust-mysql-simple) \[[mysql](https://crates.io/crates/mysql)] - 原生 MySql 客户端[<img src="https://api.travis-ci.org/blackbeam/rust-mysql-simple.svg?branch=master">](https://travis-ci.org/blackbeam/rust-mysql-simple)
  - PostgreSql \[[postgres](https://crates.io/keywords/postgres)，[postgresql](https://crates.io/keywords/postgresql)]
    - [sfackler/rust-postgres](https://github.com/sfackler/rust-postgres) \[[postgres](https://crates.io/crates/postgres)] - 土生土长的[PostgreSQL](https://www.postgresql.org/)客户端 [<img src="https://api.travis-ci.org/sfackler/rust-postgres.svg?branch=master">](https://travis-ci.org/sfackler/rust-postgres)
  - Sqlite \[[sqlite](https://crates.io/keywords/sqlite)]
    - [jgallagher/rusqlite](https://github.com/jgallagher/rusqlite) >>- [Sqlite3](https://www.sqlite.org/index.html)绑定 [<img src="https://api.travis-ci.org/jgallagher/rusqlite.svg?branch=master">](https://travis-ci.org/jgallagher/rusqlite)
- ORM \[[orm](https://crates.io/keywords/orm)]
  - [diesel-rs/diesel](https://github.com/diesel-rs/diesel) >>- Rust 的 ORM 和 Query 构建器[![Build Status](https://api.travis-ci.org/diesel-rs/diesel.svg)](https://travis-ci.org/diesel-rs/diesel)
  - [ivanceras/rustorm](https://github.com/ivanceras/rustorm) >>- Rust 的 ORM[![Build Status](https://api.travis-ci.org/ivanceras/rustorm.svg)](https://travis-ci.org/ivanceras/rustorm)

### 数据处理

- [bluss/ndarray](https://github.com/rust-ndarray/ndarray) >>- 具有数组视图，多维切片和高效操作的 N 维数组
- [kernelmachine/utah](https://github.com/kernelmachine/utah) >>- 用 Rust 写的，数据帧结构及操作
- [weld-project/weld](https://github.com/weld-project/weld) >>- 数据分析应用程序的高性能运行时

### 数据结构

- [billyevans/tst](https://github.com/billyevans/tst)\[[tst](https://crates.io/crates/tst)] - 三元搜索树集合[<img src="https://api.travis-ci.org/billyevans/tst.svg?branch=master">](https://travis-ci.org/billyevans/tst)
- [bluss/rust-itertools](https://github.com/bluss/rust-itertools) >>- [<img src="https://api.travis-ci.com/bluss/rust-itertools.svg?branch=master">](https://travis-ci.org/bluss/rust-itertools)
- [contain-rs](https://github.com/contain-rs) >>- Rust 的 **std::collections** 的扩展
- [danielpclark/array_tool](https://github.com/danielpclark/array_tool) >>- Rust 的数组助手。您将在数组上使用的一些最常用的方法，都可在 Vectors 上使用。用于处理大多数用例的多态实现。[<img src="https://api.travis-ci.org/danielpclark/array_tool.svg?branch=master">](https://travis-ci.org/danielpclark/array_tool)
- [fizyk20/generic-array](https://github.com/fizyk20/generic-array) >>- 通过 typenums，允许 sized(固定大小)数组的 hack [<img src="https://api.travis-ci.org/fizyk20/generic-array.svg?branch=master">](https://travis-ci.org/fizyk20/generic-array)
- [garro95/priority-queue](https://github.com/garro95/priority-queue)\[[priority-queue](https://crates.io/crates/priority-queue)] - 实现优先级更改的优先队列。[<img src="https://api.travis-ci.org/garro95/priority-queue.svg?branch=master">](https://travis-ci.org/garro95/priority-queue)
- [Nemo157/roaring-rs](https://github.com/Nemo157/roaring-rs) >>- Roaring Bitmaps [<img src="https://api.travis-ci.org/Nemo157/roaring-rs.svg?branch=master">](https://travis-ci.org/Nemo157/roaring-rs)
- [orium/rpds](https://github.com/orium/rpds)\[[rpds](https://crates.io/crates/rpds)] - Rust 中的持久数据结构。[<img src="https://api.travis-ci.org/orium/rpds.svg?branch=master">](https://travis-ci.org/orium/rpds)
- [pop-os/progress-streams](https://github.com/pop-os/progress-streams) >>- 给实现`dyn io::Read`要么`dyn io::Write`类型的，进度回调函数。
- [whitfin/usher](https://github.com/whitfin/usher)\[[usher](https://crates.io/crates/usher)] - Rust 中通用资源的参数化路由。
- [xfix/enum-map](https://github.com/xfix/enum-map)\[[enum-map](https://crates.io/crates/enum-map)] - 枚举的优化映射实现：使用一个数组(array)存储值。[<img src="https://api.travis-ci.org/xfix/enum-map.svg?branch=master">](https://travis-ci.org/xfix/enum-map)

### 数据可视化

- [saresend/gust](https://github.com/saresend/Gust) >>- [<img src="https://api.travis-ci.org/saresend/Gust.svg?branch=master">](https://travis-ci.org/saresend/Gust)
- [milliams/plotlib](https://github.com/milliams/plotlib) >>— [<img src="https://api.travis-ci.org/milliams/plotlib.svg?branch=master">](https://travis-ci.org/milliams/plotlib)

### 日期和时间

\[[date](https://crates.io/keywords/date)，[time](https://crates.io/keywords/time)]

- [chronotope/chrono](https://github.com/chronotope/chrono) >>- [<img src="https://api.travis-ci.org/chronotope/chrono.svg?branch=master">](https://travis-ci.org/chronotope/chrono)
- [yaa110/rust-persian-calendar](https://github.com/yaa110/rust-persian-calendar) >>- [<img src="https://api.travis-ci.org/yaa110/rust-persian-calendar.svg?branch=master">](https://travis-ci.org/yaa110/rust-persian-calendar)

### 分布式系统

- Antimony
  - [antimonyproject/antimony](https://github.com/antimonyproject/antimony)\[[antimony](https://crates.io/crates/antimony)] - 流处理/分布式计算平台[<img src="https://api.travis-ci.org/antimonyproject/antimony.svg?branch=master">](https://travis-ci.org/antimonyproject/antimony)
- Apache Hadoop
  - [whitfin/efflux](https://github.com/whitfin/efflux) >>- Rust 中的 Easy Hadoop Streaming 和 MapReduce 接口。
- Apache Kafka
  - [fede1024/rust-rdkafka](https://github.com/fede1024/rust-rdkafka)\[[rdkafka](https://crates.io/crates/rdkafka)] -[librdkafka](https://github.com/edenhill/librdkafka)绑定 [<img src="https://api.travis-ci.org/fede1024/rust-rdkafka.svg?branch=master">](https://travis-ci.org/fede1024/rust-rdkafka)
  - [spicavigo/kafka-rust](https://github.com/spicavigo/kafka-rust) >>- [<img src="https://api.travis-ci.org/spicavigo/kafka-rust.svg?branch=master">](https://travis-ci.org/spicavigo/kafka-rust)
- Beanstalkd
  - [schickling/rust-beanstalkd](https://github.com/schickling/rust-beanstalkd) >>- [Beanstalkd](https://github.com/beanstalkd/beanstalkd)绑定 [<img src="https://api.travis-ci.org/schickling/rust-beanstalkd.svg?branch=master">](https://travis-ci.org/schickling/rust-beanstalkd)
- HDFS
  - [hyunsik/hdfs-rs](https://github.com/hyunsik/hdfs-rs) >>- libhdfs 绑定 [<img src="https://api.travis-ci.org/hyunsik/hdfs-rs.svg?branch=master">](https://travis-ci.org/hyunsik/hdfs-rs)

### 电子邮件

\[[email](https://crates.io/keywords/email)，[imap](https://crates.io/keywords/imap)，[smtp](https://crates.io/keywords/smtp)]

- [GildedHonour/atarashii_imap](https://github.com/GildedHonour/atarashii_imap) >>- （atarashii / new）Rust 的 IMAP 新客户端。它支持普通和安全连接[<img src="https://api.travis-ci.org/GildedHonour/atarashii_imap.svg?branch=master">](https://travis-ci.org/GildedHonour/atarashii_imap)
- [gsquire/sendgrid-rs](https://github.com/gsquire/sendgrid-rs) >>- SendGrid API 的非官方 Rust 库[<img src="https://api.travis-ci.org/gsquire/sendgrid-rs.svg?branch=master">](https://travis-ci.org/gsquire/sendgrid-rs)
- [lettre/lettre](https://github.com/lettre/lettre) >>- Rust 的 SMTP 库[<img src="https://api.travis-ci.org/lettre/lettre.svg?branch=master">](https://travis-ci.org/lettre/lettre)
- [staktrace/mailparse](https://github.com/staktrace/mailparse)\[[mailparse](https://crates.io/crates/mailparse)] - 用于解析真实世界电子邮件文件的库[<img src="https://api.travis-ci.org/staktrace/mailparse.svg?branch=master">](https://travis-ci.org/staktrace/mailparse)

### 编码(Encoding)

\[[encoding](https://crates.io/keywords/encoding)]

- ASN.1
  - [alex/rust-asn1](https://github.com/alex/rust-asn1) >>- Rust ASN.1（DER）序列化器[<img src="https://api.travis-ci.org/alex/rust-asn1.svg?branch=master">](https://travis-ci.org/alex/rust-asn1)
- Bencode
  - [arjantop/rust-bencode](https://github.com/arjantop/rust-bencode) >>- [Bencode](https://en.wikipedia.org/wiki/Bencode)在 Rust 中实现[<img src="https://api.travis-ci.org/arjantop/rust-bencode.svg?branch=master">](https://travis-ci.org/arjantop/rust-bencode)
- Binary
  - [arcnmx/nue](https://github.com/arcnmx/nue) >>- Rust 的 I/O 和二进制数据编码[<img src="https://api.travis-ci.org/arcnmx/nue.svg?branch=master">](https://travis-ci.org/arcnmx/nue)
  - [TyOverby/bincode](https://github.com/servo/bincode) >>- Rust 中的二进制编码器/解码器[<img src="https://api.travis-ci.com/servo/bincode.svg?branch=master">](https://travis-ci.org/servo/bincode)
  - [m4b/goblin](https://github.com/m4b/goblin) \[[goblin](https://crates.io/crates/goblin)] - 跨平台，零拷贝和感知-字节序的二进制解析[<img src="https://api.travis-ci.org/m4b/goblin.svg?branch=master">](https://travis-ci.org/m4b/goblin)
- BSON
  - [zonyitoo/bson-rs](https://github.com/zonyitoo/bson-rs) >>- [<img src="https://api.travis-ci.org/zonyitoo/bson-rs.svg?branch=master">](https://travis-ci.org/zonyitoo/bson-rs)
- Byte swapping
  - [BurntSushi/byteorder](https://github.com/BurntSushi/byteorder) >>- 支持 大-字节序，小-字节序 和 原生 字节顺序[<img src="https://api.travis-ci.org/BurntSushi/byteorder.svg?branch=master">](https://travis-ci.org/BurntSushi/byteorder)
- Cap'n Proto
  - [capnproto/capnproto-rust](https://github.com/capnproto/capnproto-rust) >>- [<img src="https://api.travis-ci.org/capnproto/capnproto-rust.svg?branch=master">](https://travis-ci.org/capnproto/capnproto-rust)
- CBOR
  - [serde_cbor](https://crates.io/crates/serde_cbor) >>- CBOR 对 serde 的支持[<img src="https://api.travis-ci.org/pyfisch/cbor.svg?branch=master">](https://travis-ci.org/pyfisch/cbor)
- 字符编码
  - [hsivonen/encoding_rs](https://github.com/hsivonen/encoding_rs) \[[encoding_rs](https://crates.io/crates/encoding_rs)] - 面向 Gecko 的编码标准 Rust 实现[<img src="https://api.travis-ci.org/hsivonen/encoding_rs.svg?branch=master">](https://travis-ci.org/hsivonen/encoding_rs)
  - [lifthrasiir/rust-encoding](https://github.com/lifthrasiir/rust-encoding) >>- [<img src="https://api.travis-ci.org/lifthrasiir/rust-encoding.svg?branch=master">](https://travis-ci.org/lifthrasiir/rust-encoding)
- CRC
  - [mrhooray/crc-rs](https://github.com/mrhooray/crc-rs) >>- [<img src="https://api.travis-ci.org/mrhooray/crc-rs.svg?branch=master">](https://travis-ci.org/mrhooray/crc-rs)
- CSV
  - [BurntSushi/rust-csv](https://github.com/BurntSushi/rust-csv) >>- 快速灵活的 CSV 读写器，支持 Serde[<img src="https://api.travis-ci.org/BurntSushi/rust-csv.svg?branch=master">](https://travis-ci.org/BurntSushi/rust-csv)
- [FlatBuffers](https://google.github.io/flatbuffers/)
  - [frol/flatc-rust](https://github.com/frol/flatc-rust) >>- 用于 Cargo 构建脚本的 FlatBuffers 编译器（flatc）集成[<img src="https://api.travis-ci.org/frol/flatc-rust.svg?branch=master">](https://travis-ci.org/frol/flatc-rust)
- HAR
  - [mandrean/har-rs](https://github.com/mandrean/har-rs) >>- HTTP 存档格式（HAR）序列化和反序列化库[![Build Status](https://api.travis-ci.org/mandrean/har-rs.svg?branch=master)](https://travis-ci.org/mandrean/har-rs)
- HTML
  - [servo/html5ever](https://github.com/servo/html5ever) >>- 高性能的浏览器级，HTML5 解析器[<img src="https://api.travis-ci.com/servo/html5ever.svg?branch=master">](https://travis-ci.org/servo/html5ever)
  - [veddan/rust-htmlescape](https://github.com/veddan/rust-htmlescape) >>- 编码/解码 HTML 条目[<img src="https://api.travis-ci.org/veddan/rust-htmlescape.svg?branch=master">](https://travis-ci.org/veddan/rust-htmlescape)
- JSON
  - [pikkr/pikkr](https://github.com/pikkr/pikkr) \[[pikkr](https://crates.io/crates/pikkr)] - JSON 解析器，直接获取值，而不会在 Rust 中执行标记化
  - [serde-rs/json](https://github.com/serde-rs/json) \[[serde_json](https://crates.io/crates/serde_json)] - JSON 支持[Serde](https://github.com/serde-rs/serde)框架 [<img src="https://api.travis-ci.org/serde-rs/json.svg?branch=master">](https://travis-ci.org/serde-rs/json)
  - [Licenser/simdjson-rs](https://github.com/simd-lite/simdjson-rs) [[simd-json](https://crates.io/crates/simd-json)] >>- 基于 simdjson 的一部分，制成的高性能 JSON 解析器
  - [maciejhirsz/json-rust](https://github.com/maciejhirsz/json-rust) \[[json](https://crates.io/crates/json)] - Rust 中的 JSON 实现[<img src="https://api.travis-ci.org/maciejhirsz/json-rust.svg?branch=master">](https://travis-ci.org/maciejhirsz/json-rust)
- Jsonnet
  - [Qihoo360/rust-jsonnet](https://github.com/Qihoo360/rust-jsonnet) >>- [<img src="https://api.travis-ci.org/Qihoo360/rust-jsonnet.svg?branch=master">](https://travis-ci.org/Qihoo360/rust-jsonnet)
- MsgPack
  - [3Hren/msgpack-rust](https://github.com/3Hren/msgpack-rust) >>- 纯 Rust 低层/高级 MessagePack 实现[<img src="https://api.travis-ci.org/3Hren/msgpack-rust.svg?branch=master">](https://travis-ci.org/3Hren/msgpack-rust)
- PEM
  - [jcreekmore/pem-rs](https://github.com/jcreekmore/pem-rs) \[[pem](https://crates.io/crates/pem)] - 基于 Rust 的解析和编码 PEM 编码数据的方法[<img src="https://api.travis-ci.org/jcreekmore/pem-rs.svg?branch=master">](https://travis-ci.org/jcreekmore/pem-rs)
- Postman Collection
  - [mandrean/postman-collection-rs](https://github.com/mandrean/postman-collection-rs) >>- Postman Collection v1，v2 和 v2.1 序列化和反序列化库[![Build Status](https://api.travis-ci.org/mandrean/postman-collection-rs.svg?branch=master)](https://travis-ci.org/mandrean/postman-collection-rs)
- ProtocolBuffers
  - [danburkert/prost](https://github.com/danburkert/prost) >>- [<img src="https://api.travis-ci.org/danburkert/prost.svg?branch=master">](https://travis-ci.org/danburkert/prost)
  - [stepancheg/rust-protobuf](https://github.com/stepancheg/rust-protobuf) >>- [<img src="https://api.travis-ci.org/stepancheg/rust-protobuf.svg?branch=master">](https://travis-ci.org/stepancheg/rust-protobuf)
- RON（Rust 的对象表示法）
  - <https://github.com/ron-rs/ron>-[<img src="https://api.travis-ci.org/ron-rs/ron.svg?branch=master">](https://travis-ci.org/https://github.com/ron-rs/ron)
- Tnetstring
  - [erickt/rust-tnetstring](https://github.com/erickt/rust-tnetstring) >>- [<img src="https://api.travis-ci.org/erickt/rust-tnetstring.svg?branch=master">](https://travis-ci.org/erickt/rust-tnetstring)
- TOML
  - [alexcrichton/toml-rs](https://github.com/alexcrichton/toml-rs) >>- [<img src="https://api.travis-ci.com/alexcrichton/toml-rs.svg?branch=master">](https://travis-ci.org/alexcrichton/toml-rs)
- XML
  - [tafia/quick-xml](https://github.com/tafia/quick-xml) >>- 高性能 XML 读/写器[<img src="https://api.travis-ci.org/tafia/quick-xml.svg?branch=master">](https://travis-ci.org/tafia/quick-xml)
  - [Florob/RustyXML](https://github.com/Florob/RustyXML) >>- 用 Rust 编写的 XML 解析器[<img src="https://api.travis-ci.org/Florob/RustyXML.svg?branch=master">](https://travis-ci.org/Florob/RustyXML)
  - [shepmaster/sxd-document](https://github.com/shepmaster/sxd-document) >>- Rust 中的 XML 库[<img src="https://api.travis-ci.org/shepmaster/sxd-document.svg?branch=master">](https://travis-ci.org/shepmaster/sxd-document)
  - [shepmaster/sxd-xpath](https://github.com/shepmaster/sxd-xpath) >>- Rust 中的 XPath 库[<img src="https://api.travis-ci.org/shepmaster/sxd-xpath.svg?branch=master">](https://travis-ci.org/shepmaster/sxd-xpath)
  - [netvl/xml-rs](https://github.com/netvl/xml-rs) >>- 流式 XML 库[<img src="https://api.travis-ci.org/netvl/xml-rs.svg?branch=master">](https://travis-ci.org/netvl/xml-rs)
  - [media-io/yaserde](https://github.com/media-io/yaserde) >>- 另一个专门用于 XML 的 Serializer / Deserializer（序列化/反序列化） [<img src="https://api.travis-ci.org/media-io/yaserde.svg?branch=master">](https://travis-ci.org/media-io/yaserde)
- YAML
  - [chyh1990/yaml-rust](https://github.com/chyh1990/yaml-rust) >>- YAML 1.2 Rust 缺失实现。[<img src="https://api.travis-ci.org/chyh1990/yaml-rust.svg?branch=master">](https://travis-ci.org/chyh1990/yaml-rust)
  - [dtolnay/serde-yaml](https://github.com/dtolnay/serde-yaml) \[[serde_yaml](https://crates.io/crates/serde_yaml)] - YAML 支持[Serde](https://github.com/serde-rs/serde)框架 [<img src="https://api.travis-ci.org/dtolnay/serde-yaml.svg?branch=master">](https://travis-ci.org/dtolnay/serde-yaml)
  - [kimhyunkang/libyaml-rust](https://github.com/kimhyunkang/libyaml-rust) >>- [libyaml](https://pyyaml.org/wiki/LibYAML)绑定 [<img src="https://api.travis-ci.org/kimhyunkang/libyaml-rust.svg?branch=master">](https://travis-ci.org/kimhyunkang/libyaml-rust)
  - [vitiral/stfu8](https://github.com/vitiral/stfu8) >>- UTF-8 排序文本格式[<img src="https://api.travis-ci.org/vitiral/stfu8.svg?branch=master">](https://travis-ci.org/vitiral/stfu8)

### 文件系统

\[[filesystem](https://crates.io/keywords/filesystem)]

- 操作
  - [pop-os/dbus-udisks2](https://github.com/pop-os/dbus-udisks2) >>- > UDisks2 DBus API
  - [pop-os/sys-mount](https://github.com/pop-os/sys-mount) >>- `mount` / `umount2`系统调用的高级抽象。
  - [vitiral/path_abs](https://github.com/vitiral/path_abs) >>- 可序列化的绝对路径类型和相关方法。[<img src="https://api.travis-ci.org/vitiral/path_abs.svg?branch=master">](https://travis-ci.org/webdesus/fs_extr://travis-ci.org/vitiral/path_abs)
  - [webdesus/fs_extra](https://github.com/webdesus/fs_extra) >>- 扩大标准库 std::fs 和 std::io 的机会 [<img src="https://api.travis-ci.org/webdesus/fs_extra.svg?branch=master">](https://travis-ci.org/webdesus/fs_extra)
- 临时文件
  - [rust-lang-deprecated/tempdir](https://github.com/rust-lang-deprecated/tempdir) >>- 临时目录库[<img src="https://api.travis-ci.com/rust-lang-nursery/tempdir.svg?branch=master">](https://travis-ci.org/rust-lang-nursery/tempdir)
  - [Stebalien/tempfile](https://github.com/Stebalien/tempfile) >>- 临时文件库[<img src="https://api.travis-ci.org/Stebalien/tempfile.svg?branch=master">](https://travis-ci.org/Stebalien/tempfile)
  - [Stebalien/xattr](https://github.com/Stebalien/xattr)\[[xattr](https://crates.io/crates/xattr)] - 列出，并操作 unix 扩展文件属性[<img src="https://api.travis-ci.org/Stebalien/xattr.svg?branch=master">](https://travis-ci.org/Stebalien/xattr)
  - [zboxfs/zbox](https://github.com/zboxfs/zbox)\[[zbox](https://crates.io/crates/zbox)] - 零细节，以隐私为重点的可嵌入文件系统。[<img src="https://api.travis-ci.org/zboxfs/zbox.svg?branch=master">](https://travis-ci.org/zboxfs/zbox)

### 游戏开发

也可以看看[Are we game yet?](http://arewegameyet.com)

- Allegro
  - [SiegeLord/RustAllegro](https://github.com/SiegeLord/RustAllegro) >>- [Allegro 5](https://liballeg.org/)绑定 [<img src="https://api.travis-ci.org/SiegeLord/RustAllegro.svg?branch=master">](https://travis-ci.org/SiegeLord/RustAllegro)
- Challonge
  - [vityafx/challonge-rs](https://github.com/vityafx/challonge-rs)\[[challonge](https://crates.io/crates/challonge)] - Challonge REST API 的客户端库。帮助组织比赛。[<img src="https://api.travis-ci.org/vityafx/challonge-rs.svg?branch=master">](https://travis-ci.org/vityafx/challonge-rs)
- Corange
  - [lucidscape/corange-rs](https://github.com/lucidscape/corange-rs) >>- [Corange](https://github.com/orangeduck/Corange)绑定
- Entity-Component Systems（ECS）
  - [slide-rs/specs](https://github.com/amethyst/specs) >>- Specs Parallel ECS[<img src="https://api.travis-ci.org/slide-rs/specs.svg">](httpsL//github.com/travis-ci.org/slide-rs/specs)
- 游戏引擎
  - [Amethyst](https://amethyst.rs) >>- 面向数据的游戏引擎[<img src="https://jenkins.amethyst-engine.org/job/amethyst/job/master/badge/icon">](https://jenkins.amethyst-engine.org/blue/organizations/jenkins/amethyst/activity/)
  - [Piston](https://www.piston.rs/) >>- [<img src="https://api.travis-ci.org/PistonDevelopers/piston.svg?branch=master">](https://travis-ci.org/PistonDevelopers/piston)
  - [ggez](https://github.com/ggez/ggez) >>- 轻量级游戏框架，最小摩擦力制作 2D 游戏[<img src="https://api.travis-ci.org/ggez/ggez.svg?branch=master">](https://travis-ci.org/ggez/ggez)
  - [Kiss3D](http://kiss3d.org/) >>- 用 Rust 编写的 Keep It Simple，Stupid 3d 图形引擎
  - [Unrust](https://github.com/unrust/unrust) >>- unrust - 基于纯螃蟹（webgl 2.0 /原生）游戏引擎
  - [Vulkust](https://github.com/Hossein-Noroozpour/vulkust) >>- Vulkust - 一个用 Rust 编写的安全，高度多线程，基于 Vulkan 的游戏引擎。
- [SDL](http://www.libsdl.org/)\[[sdl](https://crates.io/keywords/sdl)]
  - [brson/rust-sdl](https://github.com/brson/rust-sdl) >>- SDL1 绑定 [<img src="https://api.travis-ci.org/brson/rust-sdl.svg?branch=master">](https://travis-ci.org/brson/rust-sdl)
  - [Rust-SDL2/rust-sdl2](https://github.com/Rust-SDL2/rust-sdl2) >>- SDL2 绑定 [<img src="https://api.travis-ci.org/Rust-SDL2/rust-sdl2.svg?branch=master">](https://travis-ci.org/Rust-SDL2/rust-sdl2)
- SFML
  - [jeremyletang/rust-sfml](https://github.com/jeremyletang/rust-sfml) >>- [SFML](https://www.sfml-dev.org/)绑定 [<img src="https://api.travis-ci.org/jeremyletang/rust-sfml.svg?branch=master">](https://travis-ci.org/jeremyletang/rust-sfml)
- Tcod-rs
  - [tomassedovic/tcod-rs](https://github.com/tomassedovic/tcod-rs) >>- 用于 Rust 的 Libtcod 绑定。
- Victorem
  - [VictoremWinbringer/Victorem](https://github.com/VictoremWinbringer/Victorem) \[[Victorem](https://crates.io/crates/Victorem)] - 简易 UDP 游戏服务器和 UDP 客户端框架，用于创建简单的 2D 和 3D 在线游戏原型[<img src="https://api.travis-ci.org/VictoremWinbringer/Victorem.svg?branch=master">](https://travis-ci.org/VictoremWinbringer/Victorem)
- Voxlap
  - [bbodi/rust-voxlap](https://github.com/bbodi/rust-voxlap) >>- [Voxlap](http://advsys.net/ken/voxlap.htm)绑定

### 地理位置

\[[geo](https://crates.io/keywords/geo)，[gis](https://crates.io/keywords/gis)]

- [DaveKram/coord_transforms](https://github.com/DaveKram/coord_transforms) \[[coord_transforms](https://crates.io/crates/coord_transforms)] - 坐标转换（2-d，3-d 和地理位置）[<img src="https://api.travis-ci.org/DaveKram/coord_transforms.svg?branch=master">](https://travis-ci.org/DaveKram/coord_transforms)
- [Georust](https://github.com/georust) >>- 用 Rust 编写的地理位置工具和库
- [rust-reverse-geocoder](https://github.com/llambda/rrgeo) >>- 快速的，可离线的，Rust 反转地理位置编码器，灵感源自<https://github.com/thampiman/reverse-geocoder>
- [vlopes11/geomorph](https://github.com/vlopes11/geomorph) \[[geomorph](https://crates.io/crates/geomorph)] - UTM，LatLon 和 MGRS 坐标之间的转换[<img src="https://api.travis-ci.org/vlopes11/geomorph.svg?branch=master">](https://travis-ci.org/vlopes11/geomorph)

### 图像

\[[graphics](https://crates.io/keywords/graphics)]

- [gfx-rs/gfx](https://github.com/gfx-rs/gfx) >>- 高性能无绑定图形 Rust API。[<img src="https://img.shields.io/travis/gfx-rs/gfx/master.svg">](https://travis-ci.org/gfx-rs/gfx)
- Font
  - [redox-os/rusttype](https://github.com/redox-os/rusttype) >>- 纯 Rust 替代品，类似 FreeType 库 [<img src="https://img.shields.io/travis/dredox-os/rusttype/master.svg">](https://travis-ci.org/redox-os/rusttype)
- OpenGL \[[opengl](https://crates.io/keywords/opengl)]
  - [brendanzab/gl-rs](https://github.com/brendanzab/gl-rs) >>- [<img src="https://api.travis-ci.org/brendanzab/gl-rs.svg?branch=master">](https://travis-ci.org/brendanzab/gl-rs)
  - [glium/glium](https://github.com/glium/glium) >>- R 安全 OpenGL 包装器，Rust 语言。[<img src="https://api.travis-ci.org/glium/glium.svg?branch=master">](https://travis-ci.org/glium/glium)
  - [Kiss3d](http://kiss3d.org) >>- 绘制简单的几何图形，并用 one-liners 玩[<img src="https://api.travis-ci.com/repositories/sebcrozet/kiss3d.json.svg?branch=master">](https://api.travis-ci.org/repositories/sebcrozet/kiss3d.json)
  - [PistonDevelopers/glfw-rs](https://github.com/PistonDevelopers/glfw-rs) >>- [<img src="https://api.travis-ci.org/PistonDevelopers/glfw-rs.svg?branch=master">](https://travis-ci.org/PistonDevelopers/glfw-rs)
  - [glutin](https://crates.io/crates/glutin) >>- [GLFW](https://www.glfw.org/)的 Rust 替代品 [<img src="https://api.travis-ci.org/rust-windowing/glutin.svg?branch=master">](https://travis-ci.org/rust-windowing/glutin)
- PDF
  - [kaj/rust-pdf](https://github.com/kaj/rust-pdf) >>- [<img src="https://api.travis-ci.org/kaj/rust-pdf.svg?branch=master">](https://travis-ci.org/kaj/rust-pdf)
  - [fschutt/printpdf](https://github.com/fschutt/printpdf) >>- PDF 写入库[<img src="https://api.travis-ci.org/fschutt/printpdf.svg?branch=master">](https://travis-ci.org/fschutt/printpdf)
  - [J-F-Liu/lopdf](https://github.com/J-F-Liu/lopdf) >>- PDF 文档操作[<img src="https://api.travis-ci.org/J-F-Liu/lopdf.svg?branch=master">](https://travis-ci.org/J-F-Liu/lopdf)
  - [WASM-PDF](https://github.com/jussiniinikoski/wasm-pdf) >>– 用 JavaScript 和 WASM (WebAssembly)，生成 PDF 文件 [<img src="https://api.travis-ci.org/jussiniinikoski/wasm-pdf.svg?branch=master">](https://travis-ci.org/jussiniinikoski/wasm-pdf)
- [Vulkan](https://www.khronos.org/vulkan/) \[[vulkan](https://crates.io/keywords/vulkan)]
  - [vulkano](https://github.com/vulkano-rs/vulkano) \[[vulkano](https://crates.io/crates/vulkano)] -[<img src="https://api.travis-ci.org/vulkano-rs/vulkano.svg?branch=master">](https://travis-ci.org/vulkano-rs/vulkano)

### 图处理

- [kud1ing/tinkerpop-rs](https://github.com/kud1ing/tinkerpop-rs) >>- 一个如何使用 Rust 的 Apache TinkerPop 的例子[<img src="https://api.travis-ci.org/kud1ing/tinkerpop-rs.svg?branch=master">](https://travis-ci.org/kud1ing/tinkerpop-rs)

### GUI

\[[gui](https://crates.io/keywords/gui)]

- [autopilot-rs/autopilot-rs](https://github.com/autopilot-rs/autopilot-rs) >>- Rust 的简单跨平台 GUI 自动化库。
- [maps4print/azul](https://github.com/maps4print/azul) >>- 一个免费的，功能性的，面向 IMGUI 的 GUI 框架，用于快速开发用 Rust 编写的桌面应用程序，由 Mozilla WebRender 渲染引擎支持。[<img src="https://api.travis-ci.org/maps4print/azul.svg?branch=master">](https://travis-ci.org/maps4print/azul)
- [PistonDevelopers/conrod](https://github.com/PistonDevelopers/conrod/) >>- 一个易于使用的，即时模式， 2D GUI 库，完全用 Rust 编写[<img src="https://api.travis-ci.org/PistonDevelopers/conrod.svg?branch=master">](https://travis-ci.org/PistonDevelopers/conrod)
- [rise-ui](https://github.com/rise-ui/rise) >>- 基于组件的简单跨平台 GUI 工具包，用于开发美观且用户友好的界面。

* Cocoa
  - [kylewlacy/sorbet-cocoa](https://github.com/kylewlacy/sorbet-cocoa) >>- [<img src="https://api.travis-ci.org/kylewlacy/sorbet-cocoa.svg?branch=master">](https://travis-ci.org/kylewlacy/sorbet-cocoa)
  - [servo/core-foundation-rs](https://github.com/servo/core-foundation-rs) >>- [<img src="https://api.travis-ci.org/servo/core-foundation-rs.svg?branch=master">](https://travis-ci.org/servo/core-foundation-rs)

- [Flutter](https://flutter.dev/)
  - [flutter-rs](https://github.com/flutter-rs/flutter-rs) >>- 用 dart & rust，构建 flutter 桌面应用程序。
- [GTK+](https://www.gtk.org/) \[[gtk](https://crates.io/keywords/gtk)]
  - [gtk-rs/gtk](https://github.com/gtk-rs/gtk) >>- GTK+ 绑定 [<img src="https://api.travis-ci.org/gtk-rs/gtk.svg?branch=master">](https://travis-ci.org/gtk-rs/gtk)
  - [relm](https://github.com/antoyo/relm) >>- 基于 GTK+ 的异步 GUI 库，灵感来自 Elm[<img src="https://api.travis-ci.org/antoyo/relm.svg?branch=master">](https://travis-ci.org/antoyo/relm)
- [ImGui](https://github.com/ocornut/imgui)
  - [imgui-rs](https://github.com/Gekkio/imgui-rs) >>- ImGui 的 Rust 绑定 [<img src="https://api.travis-ci.org/Gekkio/imgui-rs.svg?branch=master">](https://travis-ci.org/Gekkio/imgui-rs)
- [IUP](http://webserver2.tecgraf.puc-rio.br/iup/)
  - [clear-coat](https://github.com/jminer/clear-coat) >>- Clear Coat 是 IUP GUI 库的 Rust 包装器
  - [dcampbell24/iup-rust](https://github.com/dcampbell24/iup-rust) >>- IUP 绑定 [<img src="https://api.travis-ci.org/dcampbell24/iup-rust.svg?branch=master">](https://travis-ci.org/dcampbell24/iup-rust)
  - [Kiss-ui](https://github.com/KISS-UI/kiss-ui) >>- 基于 IUP 构建的简单 UI 框架[![Build Status](https://api.travis-ci.org/cybergeek94/kiss-ui.svg?branch=master)](https://travis-ci.org/cybergeek94/kiss-ui)
- [libui](https://github.com/andlabs/libui)
  - [pcwalton/libui-rs](https://github.com/pcwalton/libui-rs) >>- libui 绑定 [<img src="https://api.travis-ci.org/pcwalton/libui-rs.svg?branch=master">](https://travis-ci.org/pcwalton/libui-rs)。被遗弃的项目。最新的分支是[NoraCodes/libui-rs](https://github.com/NoraCodes/libui-rs)。
- [Nuklear](https://github.com/vurtun/nuklear)
  - [nuklear-rust](https://github.com/snuk182/nuklear-rust) >>- Nuklear 的 Rust 绑定 [<img src="https://api.travis-ci.com/snuk182/nuklear-rust.svg?branch=master">](https://travis-ci.org/snuk182/nuklear-rust)
- [Qt](https://doc.qt.io)
  - [woboq/qmetaobject-rs](https://github.com/woboq/qmetaobject-rs) >>- 通过在编译时，去构建 QMetaObject ，来集成 Qml 和 Rust。[<img src="https://api.travis-ci.org/woboq/qmetaobject-rs.svg?branch=master">](https://travis-ci.org/woboq/qmetaobject-rs)
  - [cyndis/qmlrs](https://github.com/cyndis/qmlrs) >>- QtQuick 绑定 [<img src="https://api.travis-ci.org/cyndis/qmlrs.svg?branch=master">](https://travis-ci.org/cyndis/qmlrs)
  - [kitech/qt.rs](https://github.com/kitech/qt.rs) >>- Qt5 绑定 [<img src="https://api.travis-ci.org/kitech/qt.rs.svg?branch=master">](https://travis-ci.org/kitech/qt.rs)
  - [Rust Qt Binding Generator](https://phabricator.kde.org/source/rust-qt-binding-generator/) >>- 由 KDE 托管的绑定生成器。
  - [rust-qt](https://github.com/rust-qt) >>-
  - [White-Oak/qml-rust](https://github.com/White-Oak/qml-rust) >>- QML 绑定。[<img src="https://api.travis-ci.org/White-Oak/qml-rust.svg?branch=master">](https://travis-ci.org/White-Oak/qml-rust)
- [saurvs/nfd-rs](https://github.com/saurvs/nfd-rs) >>- [nativefiledialog](https://github.com/mlabbe/nativefiledialog)绑定
- [Sciter](https://sciter.com/)
  - [sciter-sdk/rust-sciter](https://github.com/sciter-sdk/rust-sciter) >>- Sciter 绑定 [<img src="https://ci.appveyor.com/api/projects/status/github/sciter-sdk/rust-sciter?svg=true">](https://ci.appveyor.com/project/sciter-sdk/rust-sciter)

### 图像处理

- [abonander/img_hash](https://github.com/abonander/img_hash) >>- 感知图像哈希，和比较相等性与相似性。
- [image-rs/image](https://github.com/image-rs/image) >>- 基本图像处理函数和方法，用于转换图像格式和从图像格式转换的[<img src="https://api.travis-ci.org/image-rs/image.svg?branch=master">](https://travis-ci.org/image-rs/image)
- [image-rs/imageproc](https://github.com/image-rs/imageproc) >>- 一个图像处理库，基于`image` 库。[![Build Status](https://api.travis-ci.org/image-rs/imageproc.svg?branch=master)](https://travis-ci.org/image-rs/imageproc)
- [twistedfall/opencv-rust](https://github.com/twistedfall/opencv-rust) >>- OpenCV 的 Rust 绑定 [<img src="https://api.travis-ci.org/twistedfall/opencv-rust.svg?branch=cv2">](https://travis-ci.org/twistedfall/opencv-rust)
- [teovoinea/steganography](https://github.com/teovoinea/steganography)\[[steganography](https://crates.io/crates/steganography)] - 一个简单的隐写术(steganography)库[<img src="https://api.travis-ci.org/teovoinea/steganography.svg?branch=master">](https://travis-ci.org/teovoinea/steganography)

> (译者) 隐写术是一门关于信息隐藏的技巧与科学。

### 语言规范

- [shnewto/bnf](https://github.com/shnewto/bnf) >>- 用于解析无关上下文， Backus-Naur 形式语法的库。[<img src="https://api.travis-ci.org/shnewto/bnf.svg?branch=master">](https://travis-ci.org/shnewto/bnf)

### 日志

\[[log](https://crates.io/keywords/log)]

- [seanmonstar/pretty-env-logger](https://github.com/seanmonstar/pretty-env-logger) >>— 一个给 Rust的，漂亮, 易于使用的 logger 。 [![Build Status](https://api.travis-ci.com/seanmonstar/pretty-env-logger.svg?branch=master)](https://travis-ci.org/seanmonstar/pretty-env-logger)
- [rust-lang-nursery/log](https://github.com/rust-lang-nursery/log) >>- Rust 的日志记录实现[![Build Status](https://api.travis-ci.com/rust-lang-nursery/log.svg?branch=master)](https://travis-ci.org/rust-lang-nursery/log)
- [slog-rs/slog](https://github.com/slog-rs/slog) >>- Rust 的结构化，可组合日志记录[![Build Status](https://api.travis-ci.org/slog-rs/slog.svg?branch=master)](https://travis-ci.org/slog-rs/slog)
- [sfackler/log4rs](https://github.com/sfackler/log4rs) >>- 高度可配置的日志框架，以 Java 的 Logback 和 log4j 库为模型 [![Build Status](https://api.travis-ci.org/sfackler/log4rs.svg?branch=master)](https://travis-ci.org/sfackler/log4rs)

### 宏

- cute
  - [mattgathu/cute](https://github.com/mattgathu/cute) >>- Python-esque 列表推导的 Rust 宏。[![Build Status](https://api.travis-ci.org/mattgathu/cute.svg?branch=master)](https://travis-ci.org/tensorflow/rust)
- hado
  - [ludat/hado-rs](https://github.com/ludat/hado-rs) >>- 写一个类似 haskell 的表达式，没有太多的仪式

### Markup 语言

- CommonMark
  - [raphlinus/pulldown-cmark](https://github.com/raphlinus/pulldown-cmark) >>- 用 Rust 编写的 [CommonMark](https://commonmark.org/)解析器

### 移动

[Geal/rust_on_mobile](https://github.com/Geal/rust_on_mobile)

- Android
  - [rust-windowing/android-rs-glue](https://github.com/rust-windowing/android-rs-glue) >>- Rust 和 Android 之间的粘合剂[<img src="https://api.travis-ci.org/rust-windowing/android-rs-glue.svg?branch=master">](https://travis-ci.org/rust-windowing/android-rs-glue)
- iOS 版
  - [TimNN/cargo-lipo](https://github.com/TimNN/cargo-lipo) >>- Cargo lipo 子命令，可自动创建用于 iOS 应用程序的通用库。[<img src="https://api.travis-ci.org/TimNN/cargo-lipo.svg?branch=master">](https://travis-ci.org/TimNN/cargo-lipo)
  - [vhbit/ObjCrust](https://github.com/vhbit/ObjCrust) >>- 使用 Rust 创建 iOS 静态库[<img src="https://api.travis-ci.org/vhbit/ObjCrust.svg?branch=master">](https://travis-ci.org/vhbit/ObjCrust)
- Pebble
  - [andars/pebble.rs](https://github.com/andars/pebble.rs) >>- 一个箱子，允许 Rust 用来开发 Pebble 应用程序。
- Android / iOS
  - [i-schuetz/rust_android_ios](https://github.com/i-schuetz/rust_android_ios) >>— 在 Android 和 iOS上，使用一个共享 Rust lib，各自使用 rust-swig 和 cbindgen 的例子
  
### 网络编程

- HTTP
  - [pop-os/parallel-getter](https://github.com/pop-os/parallel-getter) >>- 下载一个文件，并行 GET 请求，以最大化带宽。
  - [pop-os/url-crawler](https://github.com/pop-os/url-crawler) >>- 可配置的并行网络爬虫，旨在抓取网站内容。
  - [pop-os/url-scraper](https://github.com/pop-os/url-scraper) >>- 从 HTML 页面中，截取 URL
- FTP
  - [mattnenterprise/rust-ftp](https://github.com/mattnenterprise/rust-ftp) >>- 一个 Rust [FTP](https://en.wikipedia.org/wiki/File_Transfer_Protocol) 客户端[<img src="https://api.travis-ci.org/mattnenterprise/rust-ftp.svg?branch=master">](https://travis-ci.org/mattnenterprise/rust-ftp)
- gRPC
  - [pingcap/grpc-rs](https://github.com/tikv/grpc-rs) >>— The gRPC 用于，以 C Core 库和特性的 Rust built [![Build Status](https://api.travis-ci.org/pingcap/grpc-rs.svg?branch=master)](https://travis-ci.org/pingcap/grpc-rs)
- IPNetwork
  - [achanda/ipnetwork](https://github.com/achanda/ipnetwork) >>- 在纯 Rust 中，使用 IP 网络的库[<img src="https://api.travis-ci.org/achanda/ipnetwork.svg?branch=master">](https://travis-ci.org/achanda/ipnetwork)
  - [candrew/netsim](https://github.com/canndrew/netsim) >>- 用于网络模拟和测试的 Rust 库[<img src="https://api.travis-ci.org/canndrew/netsim.svg?branch=master">](https://travis-ci.org/canndrew/netsim)
- JSON-RPC
  - [vlopes11/futures-jsonrpc](https://github.com/vlopes11/futures-jsonrpc) \[[futures-jsonrpc](https://crates.io/crates/futures-jsonrpc)] - JSON-RPC 的 Futures 实现[<img src="https://api.travis-ci.org/vlopes11/futures-jsonrpc.svg?branch=master">](https://travis-ci.org/vlopes11/futures-jsonrpc)
- 底层
  - [libpnet/libpnet](https://github.com/libpnet/libpnet) >>- 跨平台，低级别的网络[<img src="https://api.travis-ci.org/libpnet/libpnet.svg?branch=master">](https://travis-ci.org/libpnet/libpnet)
  - [m-labs/smoltcp](https://github.com/m-labs/smoltcp) >>— 一个独立, 事件-驱动的 TCP/IP 栈，专为裸机, 实时系统所设计 [<img src="https://api.travis-ci.org/m-labs/smoltcp.svg?branch=master">](https://travis-ci.org/m-labs/smoltcp)
  - [tokio-rs/tokio](https://github.com/tokio-rs/tokio) >>- 用于客户端和服务器的快速开发，和高度可扩展的生产部署的网络应用程序框架。
  - [dylanmckay/protocol](https://github.com/dylanmckay/protocol) >>- 自定义 TCP / UDP 协议定义
  - [actix/actix](https://github.com/actix/actix) >>- Rust 的 Actor 库[<img src="https://api.travis-ci.org/actix/actix.svg?branch=master">](https://travis-ci.org/actix/actix)
- NanoMsg
  - [thehydroimpulse/nanomsg.rs](https://github.com/thehydroimpulse/nanomsg.rs) >>- [nanomsg](https://nanomsg.org/)绑定 [<img src="https://api.travis-ci.org/thehydroimpulse/nanomsg.rs.svg?branch=master">](https://travis-ci.org/thehydroimpulse/nanomsg.rs)
- Nng
  - [neachdainn/nng-rs](https://gitlab.com/neachdainn/nng-rs) \[[Nng](http://crates.io/crates/nng)] -[Nng (nanomsg v2)](https://nanomsg.github.io/nng/index.html)绑定 [<img src="https://gitlab.com/neachdainn/nng-rs/badges/master/pipeline.svg">](https://gitlab.com/neachdainn/nng-rs/pipelines)
- NNTP
  - [mattnenterprise/rust-nntp](https://github.com/mattnenterprise/rust-nntp) >>- 一个 Rust 的[NNTP](https://en.wikipedia.org/wiki/Network_News_Transfer_Protocol)客户端[<img src="https://api.travis-ci.org/mattnenterprise/rust-nntp.svg?branch=master">](https://travis-ci.org/mattnenterprise/rust-nntp)
- POP3
  - [mattnenterprise/rust-pop3](https://github.com/mattnenterprise/rust-pop3) >>- 一个 Rust 的[POP3](https://en.wikipedia.org/wiki/Post_Office_Protocol)客户端[<img src="https://api.travis-ci.org/mattnenterprise/rust-pop3.svg?branch=master">](https://travis-ci.org/mattnenterprise/rust-pop3)
- SSH
  - [alexcrichton/ssh2-rs](https://github.com/alexcrichton/ssh2-rs) >>- [libssh2](https://www.libssh2.org/)绑定 [<img src="https://api.travis-ci.com/alexcrichton/ssh2-rs.svg?branch=master">](https://travis-ci.org/alexcrichton/ssh2-rs)
  - [Thrussh](https://github.com/pijul-scm/thrussh/) >>- 在 Rust 中，从头开始编写的 SSH 库，由[libsodium](https://download.libsodium.org/doc/)提供支持
- Stomp
  - [zslayton/stomp-rs](https://github.com/zslayton/stomp-rs) >>- 一个 Rust 中的[STOMP 1.2](http://stomp.github.io/stomp-specification-1.2.html)客户端实现[<img src="https://api.travis-ci.org/zslayton/stomp-rs.svg?branch=master">](https://travis-ci.org/zslayton/stomp-rs)
- uTP
  - [meqif/rust-utp](https://github.com/meqif/rust-utp) >>- 一个[uTP](http://www.bittorrent.org/beps/bep_0029.html)Rust 的（微传输协议）库。[<img src="https://api.travis-ci.org/meqif/rust-utp.svg?branch=master">](https://travis-ci.org/meqif/rust-utp)
- ZeroMQ
  - [erickt/rust-zmq](https://github.com/erickt/rust-zmq) >>- [ZeroMQ](https://zeromq.org/)绑定 [<img src="https://api.travis-ci.org/erickt/rust-zmq.svg?branch=master">](https://travis-ci.org/erickt/rust-zmq)
- CoAP
  - [Covertness/coap-rs](https://github.com/Covertness/coap-rs) >>-一个[受限制的应用协议(CoAP)](https://tools.ietf.org/html/rfc7252)螃蟹库。[<img src="https://api.travis-ci.org/Covertness/coap-rs.svg?branch=master">](https://travis-ci.org/Covertness/coap-rs)
- Docker
  - [fussybeaver/bollard](https://github.com/fussybeaver/bollard) - Docker daemon API 
- RPC
  - [smallnest/rpcx-rs](https://github.com/smallnest/rpcx-rs) >>— A RPC library for Rust ，旨在简单明了的方式，开发微服务。 [<img src="https://api.travis-ci.org/smallnest/rpcx-rs.svg?branch=master">](https://travis-ci.org/smallnest/rpcx-rs)

### 解析

- [Geal/nom](https://github.com/Geal/nom) >>- 解析器组合库[<img src="https://api.travis-ci.org/Geal/nom.svg?branch=master">](https://travis-ci.org/Geal/nom)
- [ivanceras/inquerest](https://github.com/ivanceras/inquerest) >>-用于 REST 过滤器查询的 URL 参数解析器[![Build Status](https://api.travis-ci.org/ivanceras/inquerest.svg?branch=master)](https://travis-ci.org/ivanceras/inquerest)
- [kevinmehall/rust-peg](https://github.com/kevinmehall/rust-peg) >>-解析表达式语法（PEG）解析器生成器
- [m4rw3r/chomp](https://github.com/m4rw3r/chomp)–一个快速的单体风格的解析器组合[<img src="https://api.travis-ci.org/m4rw3r/chomp.svg?branch=master">](https://travis-ci.org/m4rw3r/chomp)
- [Marwes/combine](https://github.com/Marwes/combine) >>-解析器组合库[<img src="https://api.travis-ci.org/Marwes/combine.svg?branch=master">](https://travis-ci.org/Marwes/combine)
- [lalrpop/lalrpop](https://github.com/lalrpop/lalrpop) >>-LR（1）螃蟹解析器生成[![Build status](https://api.travis-ci.org/lalrpop/lalrpop.svg?branch=master)](https://travis-ci.org/lalrpop/lalrpop)
- [nrc/zero](https://github.com/nrc/zero) >>- 二进制数据的零分配解析[<img src="https://api.travis-ci.org/nrc/zero.svg?branch=master">](https://travis-ci.org/nrc/zero)
- [pest-parser/pest](https://github.com/pest-parser/pest) >>- 优雅的解析器[![Build Status](https://api.travis-ci.org/pest-parser/pest.svg?branch=master)](https://travis-ci.org/pest-parser/pest)
- [ptal/oak](https://github.com/ptal/oak) >>- 一个类型化的 PEG 解析器生成（编译器插件）
- [rustless/queryst](https://github.com/rustless/queryst) >>-受<https://github.com/ljharb/qs> 启发，一个查询字符串 Rust 解析库 [![Build Status](https://api.travis-ci.org/rustless/queryst.svg?branch=master)](https://travis-ci.org/rustless/queryst)
- [freestrings/jsonpath](https://github.com/freestrings/jsonpath) >>- [JsonPath](https://goessner.net/articles/JsonPath/) 引擎。 Webassembly 和 Javascript 都支持 [![Build Status](https://api.travis-ci.org/freestrings/jsonpath.svg?branch=master)](https://travis-ci.org/freestrings/jsonpath)

### 包装格式

- [pop-os/debarchive](https://github.com/pop-os/debarchive) 阅读和提取 Debian 存档库

### 外部设备

- 串口(Serial Port)
  - [Susurrus/serialport-rs](https://github.com/Susurrus/serialport-rs) \[[serialport](https://docs.rs/serialport/3.0.0/serialport/)] >>- 提供对串行端口访问的跨平台库。

### 平台特定

- 跨平台

  - [svartalf/rust-battery](https://crates.io/crates/battery) >>— 关于笔记本电池的跨平台信息 [<img src="https://api.travis-ci.org/svartalf/rust-battery.svg?branch=master">](https://travis-ci.org/svartalf/rust-battery)

* Linux
  - [frol/cgroups-fs](https://github.com/frol/cgroups-fs) >>- Rust 绑定 Linux 控制组（CGroups）[<img src="https://api.travis-ci.org/frol/cgroups-fs.svg?branch=master">](https://travis-ci.org/frol/cgroups-fs)
  - [pop-os/dbus-udisks2](https://github.com/pop-os/dbus-udisks2) >>- udisks2 数据库 API
  - [pop-os/distinst](https://github.com/pop-os/distinst/) >>-Linux 分发安装器库
  - [inotify-rs/inotify](https://github.com/inotify-rs/inotify) >>- [inotify](https://en.wikipedia.org/wiki/Inotify)绑定 [<img src="https://api.travis-ci.org/inotify-rs/inotify.svg?branch=master">](https://travis-ci.org/inotify-rs/inotify)
  - [arvancloud/nginx-rs](https://github.com/arvancloud/nginx-rs) >>- [Nginx](https://www.nginx.com)绑定 [<img src="https://api.travis-ci.org/arvancloud/nginx-rs.svg?branch=master">](https://travis-ci.org/arvancloud/nginx-rs)
  - [yaa110/rust-iptables](https://github.com/yaa110/rust-iptables) >>- [iptables](https://www.netfilter.org/projects/iptables/index.html)绑定 [<img src="https://api.travis-ci.org/yaa110/rust-iptables.svg?branch=master">](https://travis-ci.org/yaa110/rust-iptables)
* 类 UNIX
  - [nix-rust/nix](https://github.com/nix-rust/nix) >>-类 Unix 的 API 绑定 [<img src="https://api.travis-ci.org/nix-rust/nix.svg?branch=master">](https://travis-ci.org/nix-rust/nix)
  - [zargony/rust-fuse](https://github.com/zargony/rust-fuse) >>- [FUSE](https://github.com/libfuse/libfuse)绑定<img src="https://api.travis-ci.org/zargony/rust-fuse.svg?branch=master">
* Windows
  - [retep998/winapi-rs](https://github.com/retep998/winapi-rs) >>-Windows API 绑定 [<img src="https://api.travis-ci.org/retep998/winapi-rs.svg?branch=master">](https://travis-ci.org/retep998/winapi-rs)
* FreeBSD
  - [fubarnetes/libjail-rs](https://github.com/fubarnetes/libjail-rs/) >>- FreeBSD jail 库的 Rust 实现
  - [dlrobertson/capsicum-rs](https://github.com/dlrobertson/capsicum-rs) >>- Freebsd Capsicum 框架的 Rust 绑定

### 脚本编写

\[[scripting](https://crates.io/keywords/scripting)]

- [PistonDevelopers/dyon](https://github.com/PistonDevelopers/dyon) >>-一种 rusty 的动态类型脚本语言
- [gluon-lang/gluon](https://github.com/gluon-lang/gluon) >>- 一种小型的、静态类型的函数式编程语言。
- [murarth/ketos](https://github.com/murarth/ketos) >>-作为 rust 脚本和扩展语言的 lisp 方言函数式编程语言
- [moss](https://crates.io/crates/moss) >>- 动态类型的脚本语言
- [jonathandturner/rhai](https://github.com/jonathandturner/rhai) >>- 一种小巧快速的嵌入式脚本语言，类似于 JS 和 Rust 的组合。

### 模板引擎

- Handlebars
  - [sunng87/handlebars-rust](https://github.com/sunng87/handlebars-rust) >>-带有继承的 Handlebars 模板引擎，支持自定义助手。[<img src="https://api.travis-ci.org/sunng87/handlebars-rust.svg?branch=master">](https://travis-ci.org/sunng87/handlebars-rust)
- HTML
  - [lfairy/maud](https://github.com/lambda-lfairy/maud) >>-编译时 HTML 模板[<img src="https://api.travis-ci.org/lfairy/maud.svg?branch=master">](https://travis-ci.org/lfairy/maud)
  - [Stebalien/horrorshow-rs](https://github.com/Stebalien/horrorshow-rs) >>-编译时 HTML 模板[<img src="https://api.travis-ci.org/Stebalien/horrorshow-rs.svg?branch=master">](https://travis-ci.org/Stebalien/horrorshow-rs)
  - [kaj/ructe](https://github.com/kaj/ructe) >>- Rust 模板系统[<img src="https://api.travis-ci.org/kaj/ructe.svg?branch=master">](https://travis-ci.org/kaj/ructe)
  - [Keats/tera](https://github.com/Keats/tera) >>-模板引擎，基于 jinja2 和 django 模板语言。[<img src="https://api.travis-ci.org/Keats/tera.svg?branch=master">](https://travis-ci.org/Keats/tera)
  - [djc/askama](https://github.com/djc/askama) >>-基于 Jinja 的模板绘制引擎[<img src="https://api.travis-ci.org/djc/askama.svg?branch=master">](https://travis-ci.org/djc/askama)
- Mustache
  - [rustache/rustache](https://github.com/rustache/rustache) >>- [<img src="https://api.travis-ci.org/rustache/rustache.svg?branch=master">](https://travis-ci.org/rustache/rustache)
- [tailhook/marafet](https://github.com/tailhook/marafet) >>-基于 cito.js 的虚拟 DOM 的类 Jade 模板语言编译器

### 文本处理

- [BurntSushi/suffix](https://github.com/BurntSushi/suffix) >>- 线性时间及后缀的数组构造（支持 Unicode）[<img src="https://api.travis-ci.org/BurntSushi/suffix.svg?branch=master">](https://travis-ci.org/BurntSushi/suffix)
- [BurntSushi/tabwriter](https://github.com/BurntSushi/tabwriter) >>- 弹性 tab 位（即，文本列对齐）[<img src="https://api.travis-ci.org/BurntSushi/tabwriter.svg?branch=master">](https://travis-ci.org/BurntSushi/tabwriter)
- [mgeisler/textwrap](https://github.com/mgeisler/textwrap) \[[textwrap](https://crates.io/crates/textwrap)] >>- 自动换行文字（支持连字符）[<img src="https://api.travis-ci.org/mgeisler/textwrap.svg?branch=master">](https://travis-ci.org/mgeisler/textwrap)
- [pwoolcoc/ngrams](https://github.com/pwoolcoc/ngrams) >>- 从任意迭代器，构造[n-grams](https://en.wikipedia.org/wiki/N-gram)[<img src="https://api.travis-ci.org/pwoolcoc/ngrams.svg?branch=master">](https://travis-ci.org/pwoolcoc/ngrams)
- [ps1dr3x/easy_reader](https://github.com/ps1dr3x/easy_reader) >>- 一种 reader，它允许在大型文件行中，进行向前、向后和随机的导航，而不需要使用迭代器。[<img src="https://api.travis-ci.org/ps1dr3x/easy_reader.svg?branch=master">](https://travis-ci.org/ps1dr3x/easy_reader)
- [rust-lang/regex](https://github.com/rust-lang/regex) >>- 正则表达式（re2 样式）[<img src="https://api.travis-ci.com/rust-lang/regex.svg?branch=master">](https://travis-ci.org/rust-lang/regex)
- [strsim-rs](https://crates.io/crates/strsim) >>- 字符串相似性度量[<img src="https://api.travis-ci.org/dguo/strsim-rs.svg?branch=master">](https://travis-ci.org/dguo/strsim-rs)
- [greyblake/whatlang-rs](https://github.com/greyblake/whatlang-rs) >>- 基于 trigrams 的自然语言检测库[<img src="https://api.travis-ci.org/greyblake/whatlang-rs.svg?branch=master">](https://travis-ci.org/greyblake/whatlang-rs)
- [yaa110/rake-rs](https://github.com/yaa110/rake-rs) >>- Rake（快速自动关键字提取） 算法的多语言实现[<img src="https://api.travis-ci.org/yaa110/rake-rs.svg?branch=master">](https://travis-ci.org/yaa110/rake-rs)
- [Lucretiel/joinery](https://github.com/Lucretiel/joinery) \[[joinery](https://crates.io/crates/joinery)]>>- 通用字符串+可重复连接[<img src="https://api.travis-ci.org/Lucretiel/joinery.svg?branch=master">](https://travis-ci.org/Lucretiel/joinery)

### 文本搜索

- [andylokandy/simsearch-rs](https://github.com/andylokandy/simsearch-rs) [[simsearch](https://crates.io/crates/simsearch)] >>- 简单，小巧的模拟查询引擎，内存工作，相似字符串查询
- [BurntSushi/fst](https://github.com/BurntSushi/fst) \[[fst](https://crates.io/crates/fst) >>- [<img src="https://api.travis-ci.org/BurntSushi/fst.svg?branch=master">](https://travis-ci.org/BurntSushi/fst)
- [minio/minsql](https://github.com/minio/minsql) >>— 高性能，日志查询引擎。 [<img src="https://api.travis-ci.org/minio/minsql.svg?branch=master">](https://travis-ci.org/minio/minsql)
- [CurrySoftware/perlin](https://github.com/CurrySoftware/perlin) \[[perlin](https://crates.io/crates/perlin) >>- [<img src="https://api.travis-ci.org/CurrySoftware/perlin.svg?branch=master">](https://travis-ci.org/CurrySoftware/perlin)
- [tantivy-search/tantivy](https://github.com/tantivy-search/tantivy) \[[tantivy](https://crates.io/crates/tantivy) >>- [<img src="https://api.travis-ci.org/tantivy-search/tantivy.svg?branch=master">](https://travis-ci.org/tantivy-search/tantivy)

### Unsafe

- [zerocopy](https://crates.io/crates/zerocopy) >>- 用于安全地将任意字节序列，重新解释为原生 Rust 类型的实用程序

### 虚拟化

- [beneills/quantum](https://github.com/beneills/quantum) >>- 先进的 Rust 量子计算机模拟器[<img src="https://api.travis-ci.org/beneills/quantum.svg?branch=master">](https://travis-ci.org/beneills/quantum)
- [chromium/chromiumos/platform/crosvm](https://chromium.googlesource.com/chromiumos/platform/crosvm/)Crosvm - 使 Chrome OS 能够在快速、安全 虚拟化环境中运行 Linux 应用程序
- [ekse/unicorn-rs](https://github.com/ekse/unicorn-rs) >>- Unicorn CPU 模拟器的 Rust 绑定
- [saurvs/hypervisor-rs](https://github.com/saurvs/hypervisor-rs) >>- OS X 上的硬件加速虚拟化

### 网页编程

也见[Are we web yet?](http://www.arewewebyet.org)和[Rust web 框架比较](https://github.com/flosse/rust-web-framework-comparison).

- 客户端/WASM
  - [cargo-web](https://crates.io/crates/cargo-web) >>-客户端 Web 的 Cargo 子命令[![Build Status](https://api.travis-ci.org/koute/cargo-web.svg)](https://travis-ci.org/koute/cargo-web)
  - [seed](https://github.com/David-OConnor/seed) >>-  Rust 框架，用于创建 web ap应用ps [![Build Status](https://api.travis-ci.org/David-OConnor/seed.svg?branch=master)](https://travis-ci.org/David-OConnor/seed)
  - [stdweb](https://crates.io/crates/stdweb) >>- 客户端 Web 的标准库[![Build Status](https://api.travis-ci.org/koute/stdweb.svg)](https://travis-ci.org/koute/stdweb)
  - [yew](https://crates.io/crates/yew) >>- 用于制作客户端 Web 应用程序的 Rust 框架
- HTTP 客户端
  - [alexcrichton/curl-rust](https://github.com/alexcrichton/curl-rust) >>- [libcurl](https://curl.haxx.se/libcurl/)绑定 [<img src="https://api.travis-ci.com/alexcrichton/curl-rust.svg?branch=master">](https://travis-ci.org/alexcrichton/curl-rust)
  - [hyperium/hyper](https://github.com/hyperium/hyper) >>- HTTP 实现[<img src="https://api.travis-ci.org/hyperium/hyper.svg?branch=master">](https://travis-ci.org/hyperium/hyper)
  - [seanmonstar/reqwest](https://github.com/seanmonstar/reqwest) >>-一个符合人体工程学的 HTTP 客户端。[<img src="https://api.travis-ci.org/seanmonstar/reqwest.svg?branch=master">](https://travis-ci.org/seanmonstar/reqwest)
  - [DoumanAsh/yukikaze](https://gitlab.com/Douman/yukikaze) >>- 美观大方的 yukikaze 是基于 hyper 的小 HTTP 客户端库。[<img src="https://gitlab.com/Douman/yukikaze/badges/master/build.svg">](https://gitlab.com/Douman/yukikaze)
- HTTP 服务器
  - [actix/actix-web](https://github.com/actix/actix-web) >>-一个轻量级异步 Web 框架，支持 WebSocket 实现信任[<img src="https://api.travis-ci.org/actix/actix-web.svg?branch=master">](https://travis-ci.org/actix/actix-web)
  - [branca](https://crates.io/crates/branca) >>- Branca 的一个纯信任实现，用于认证和加密的 API 令牌。[<img src="https://api.travis-ci.org/return/branca.svg?branch=master">](https://travis-ci.org/return/branca)
  - [Gotham](https://github.com/gotham-rs/gotham) >>-一种不牺牲安全性、安全性和速度的灵活 Web 框架。[<img src="https://api.travis-ci.org/gotham-rs/gotham.svg?branch=master">](https://travis-ci.org/gotham-rs/gotham)
  - [hyperium/hyper](https://github.com/hyperium/hyper) >>-HTTP 实现[<img src="https://api.travis-ci.org/hyperium/hyper.svg?branch=master">](https://travis-ci.org/hyperium/hyper)
  - [GildedHonour/frank_jwt](https://github.com/GildedHonour/frank_jwt) >>- Rust 中的 JSON Web 令牌实现。[<img src="https://api.travis-ci.org/GildedHonour/frank_jwt.svg?branch=master">](https://travis-ci.org/GildedHonour/frank_jwt)
  - [handlebars-rust](https://github.com/sunng87/handlebars-rust) >>-一个 Iron 框架中间件。[<img src="https://api.travis-ci.org/sunng87/handlebars-iron.svg?branch=master">](https://travis-ci.org/sunng87/handlebars-iron)
  - [Iron](https://github.com/iron/iron) >>- 基于中间件的服务器框架[<img src="https://api.travis-ci.org/GildedHonour/frank_jwt.svg?branch=master">](https://travis-ci.org/GildedHonour/frank_jwt)
  - [Juniper](https://github.com/graphql-rust/juniper) >>— GraphQL server Rust 库  [<img src="https://api.travis-ci.org/graphql-rust/juniper.svg?branch=master">](https://travis-ci.org/graphql-rust/juniper)  
  - [Nickel](https://github.com/nickel-org/nickel.rs/)受启发[Express](http://expressjs.com/) [<img src="https://api.travis-ci.org/nickel-org/nickel.rs.svg?branch=master">](https://travis-ci.org/nickel-org/nickel.rs)
  - [Ogeon/rustful](https://github.com/Ogeon/rustful) >>-一个 RESTful 的螃蟹 Web 框架[<img src="https://api.travis-ci.org/Ogeon/rustful.svg?branch=master">](https://travis-ci.org/Ogeon/rustful)
  - [Rocket](https://github.com/SergioBenitez/Rocket) >>- Rocket 是 Rust 的 Web 框架（夜间），重点是易用性、可表达性和速度[<img src="https://api.travis-ci.org/SergioBenitez/Rocket.svg?branch=master">](https://travis-ci.org/SergioBenitez/Rocket)
  - [Rustless](https://github.com/rustless/rustless) >>-一个类似于 REST 的 API 微框架，受[Grape](https://github.com/ruby-grape/grape)和[Hyper](https://github.com/hyperium/hyper)启发 [<img src="https://api.travis-ci.org/rustless/rustless.svg?branch=master">](https://travis-ci.org/rustless/rustless)
  - [Saphir](https://github.com/richerarc/saphir) >>-一个渐进式的网络框架，具有低层的控制，没有痛苦。
  - [rustforce/sapper](https://github.com/daogangtang/sapper) >>-一个基于 AsyncHyper 的轻量级 Web 框架，用 Rust 语言实现。[<img src="https://api.travis-ci.com/rustforce/sapper.svg?branch=master">](https://travis-ci.org/rustforce/sapper)
  - [tiny-http](https://github.com/tiny-http/tiny-http) >>- 低级 HTTP 服务器库[<img src="https://api.travis-ci.com/frewsxcv/tiny-http.svg?branch=master">](https://travis-ci.org/frewsxcv/tiny-http)
  - [tomaka/rouille](https://github.com/tomaka/rouille) >>- Web 框架[<img src="https://api.travis-ci.org/tomaka/rouille.svg?branch=master">](https://travis-ci.org/tomaka/rouille)
  - [carllerche/tower-web](https://github.com/carllerche/tower-web) \[[tower-web](https://crates.io/crates/tower-web)]-一个快速的，样板自由，螃蟹的网络框架[<img src="https://api.travis-ci.org/carllerche/tower-web.svg?branch=master">](https://travis-ci.org/carllerche/tower-web)
  - [danclive/sincere](https://github.com/danclive/sincere) >>-基于 hyper 和多线程的 Rust（稳定）的微型 Web 框架。[<img src="https://api.travis-ci.org/danclive/sincere.svg?branch=master">](https://travis-ci.org/danclive/sincere)
  - [oltdaniel/zap](https://github.com/0x1daniel/zap) >>-一个迅雷不及掩耳的 Rust HTTP 框架[<img src="https://api.travis-ci.org/oltdaniel/zap.svg?branch=master">](https://travis-ci.org/oltdaniel/zap)
- [WebSocket](https://datatracker.ietf.org/doc/rfc6455/)
  - [actix/sockjs](https://github.com/actix/sockjs) >>- 一个[SockJS](https://github.com/sockjs)Rust 服务器[<img src="https://api.travis-ci.org/actix/sockjs.svg?branch=master">](https://travis-ci.org/actix/sockjs)
  - [cyderize/rust-websocket](https://github.com/cyderize/rust-websocket) >>- 用于处理 WebSocket 连接（客户端和服务器）的框架[<img src="https://api.travis-ci.org/cyderize/rust-websocket.svg?branch=master">](https://travis-ci.org/cyderize/rust-websocket)
  - [housleyjk/ws-rs](https://github.com/housleyjk/ws-rs) >>- 轻量级，事件驱动的螃蟹 WebSockets[<img src="https://api.travis-ci.org/housleyjk/ws-rs.svg?branch=stable">](https://travis-ci.org/housleyjk/ws-rs)
  - [snapview/tungstenite-rs](https://github.com/snapview/tungstenite-rs) >>- 轻量级的基于流的 WebSocket 实现。
  - [vi/websocat](https://github.com/vi/websocat) >>-用于与 WebSockets 交互的 CLI，具有 netcat、curl 和 socat 的功能。[<img src="https://api.travis-ci.org/vi/websocat.svg?branch=master">](https://travis-ci.org/vi/websocat)
  - [vityafx/urlshortener-rs](https://github.com/vityafx/urlshortener-rs) \[[urlshortener](https://crates.io/crates/urlshortener)] >>- 一个非常简单的 urlshortener Rust 库。[<img src="https://api.travis-ci.org/vityafx/urlshortener-rs.svg?branch=master">](https://travis-ci.org/vityafx/urlshortener-rs)
- 其他
  - [cargonauts](https://github.com/cargonauts-rs/cargonauts) >>- 一种用于构建可维护的、分解良好的 Web 应用程序的 Web 框架。
  - [pyros2097/rust-embed](https://github.com/pyros2097/rust-embed) >>- 将静态资产嵌入 rust 二进制文件的宏。
  - [utkarshkukreti/select.rs](https://github.com/utkarshkukreti/select.rs) \[[select](https://crates.io/crates/select)]-从 HTML 文档中提取有用数据的库，适用于 Web 抓取。[![Build Status](https://api.travis-ci.org/utkarshkukreti/select.rs.svg?branch=master)](https://travis-ci.org/utkarshkukreti/select.rs)
  - [pwoolcoc/soup](https://gitlab.com/pwoolcoc/soup) \[[soup](https://crates.io/crates/soup)] >>- 一个类似于 pythons beautifulsoup 的库，旨在实现对 HTML 文档的快速、简单的操作和查询。[![Build Status](https://gitlab.com/pwoolcoc/soup/badges/master/pipeline.svg)](https://gitlab.com/pwoolcoc/soup/badges/master/pipeline.svg)
- 反向代理
  - [sozu-proxy/sozu](https://github.com/sozu-proxy/sozu) \[[sozu](https://crates.io/crates/sozu)]>>- 一个 HTTP 反向代理。[![Build Status](https://api.travis-ci.org/sozu-proxy/sozu.svg?branch=master)](https://api.travis-ci.org/sozu-proxy/sozu)
- 静态站点生成器
  - [getzola/zola](https://github.com/getzola/zola) \[[zola](https://www.getzola.org/)] >>- 一个内置所有东西的固执静态站点生成器。[![Build Status](https://api.travis-ci.com/getzola/zola.svg?branch=master)](https://travis-ci.org/getzola/zola)
  - [cobalt-org/cobalt.rs](https://github.com/cobalt-org/cobalt.rs) >>- 用 Rust 编写的静态现场发电机[<img src="https://api.travis-ci.org/cobalt-org/cobalt.rs.svg?branch=master">](https://travis-ci.org/cobalt-org/cobalt.rs)
  - [FuGangqiang/mdblog.rs](https://github.com/FuGangqiang/mdblog.rs) >>- markdown 文件的静态站点生成器。
  - [leven-the-blog/leven](https://github.com/leven-the-blog/leven) \[[leven](https://crates.io/crates/leven)] >>- 一个简单的、并行的博客生成器。[<img src="https://api.travis-ci.com/leven-the-blog/leven.svg?branch=master">](https://travis-ci.org/leven-the-blog/leven)

## 注册中心

注册中心允许你以箱子(crate)的形式，发布你的 Rust 库，公开和私下与他人分享。

- [Crates](https://crates.io) >>- 官方 Rust/Cargo 登记处。
- [Cloudsmith :heavy_dollar_sign:](https://cloudsmith.io/l/cargo-registry/) >>- 全面管理的软件包管理 SaaS，对公共和私人 Cargo/Rust 登记处（以及许多其他）提供一流的支持。有一个慷慨的免费服务，也是完全免费的开放源码。

## 资源

- 基准点
  - [TeXitoi/benchmarksgame-rs](https://github.com/TeXitoi/benchmarksgame-rs) >>- [编程语言 Benchmarks 游戏](https://benchmarksgame-team.pages.debian.net/benchmarksgame/) 的 Rust 实现 [<img src="https://api.travis-ci.org/TeXitoi/benchmarksgame-rs.svg?branch=master">](https://travis-ci.org/TeXitoi/benchmarksgame-rs)
- 公示板和演示文稿
  - [学习系统编程 Rust](https://speakerdeck.com/jvns/learning-systems-programming-with-rust) >>- 提交人[Julia Evans](https://twitter.com/@b0rk)@Rustconf 2016 年。
  - [运输一个坚不可摧的 Rust Crate](https://www.youtube.com/watch?v=t4CyEKb-ywA) >>- 提交人[Michael Gattozzi](https://github.com/mgattozzi)@鲁斯康夫 2017 号
  - [Rust: Hack Without Fear!](https://www.youtube.com/watch?v=lO1z-7cuRYI) >>- 提交人[Nicholas Matsakis](https://github.com/nikomatsakis)@ C++ 2018
- 学习
  - [编程社区为学习 Rust 管理资源](https://hackr.io/tutorials/learn-rust) >>- 编程界投票推荐的资源清单。
  - [exercism.io](https://exercism.io/tracks/rust) >>-编程练习可以帮助您学习 Rust 中的新概念。
  - [习惯 Rust](https://github.com/mre/idiomatic-rust) >>- 同行评审的文章/谈话/报告集，教授习惯 Rust。
  - [Learning Rust With Entirely Too Many Linked Lists](http://cglab.ca/~abeinges/blah/too-many-lists/book/) >>- 深入探讨了 Rust 的内存管理规则，通过实现几种不同类型的列表结构。
  - [Rust by Example](https://doc.rust-lang.org/rust-by-example/)
  - [Rust Cookbook](https://rust-lang-nursery.github.io/rust-cookbook/) >>-一组简单的例子，用螃蟹生态系统的箱子证明了完成常见编程任务的良好实践。
  - [Rust in Motion](https://www.manning.com/livevideo/rust-in-motion?a_aid=cnichols&a_bid=6a993c2e) >>-视 频系列由[Carol Nichols](https://github.com/carols10cents)和[Jake Goulding](https://github.com/shepmaster)（已付）
  - [rust-learning](https://github.com/ctjhoa/rust-learning) >>- 学习螃蟹的有用资源的集合
  - [Rustlings](https://github.com/rust-lang/rustlings) >>- 小练习让你习惯读写 Rust 代码
  - [stdx](https://github.com/brson/stdx) >>- 首先学习这些箱子，作为标准的扩展
  - [Pennsylvania's 大学计算机科学 Rust 语言课](http://cis198-2016s.github.io/schedule/)
  - [构建一个语言 VM](https://blog.subnetzero.io/post/building-language-vm-part-00/)
- 播客
  - [New Rustacean](https://newrustacean.com) >>- 关于学习螃蟹的播客
  - [Rustacean Station](https://rustacean-station.org/) - 社区项目，创建 Rust 播客内容。
  - [Rusty Spike](https://rusty-spike.blubrry.net) >>-一切都是螃蟹的新闻
- [RustCamp 2015 Talks](http://confreaks.tv/events/rustcamp2015)
- [Rust Design Patterns](https://github.com/rust-unofficial/patterns)
- [Rust Guidelines](http://aturon.github.io/)
- [RustBooks](https://github.com/sger/RustBooks) >>- 螃蟹书清单
- [Rust Subreddit](https://www.reddit.com/r/rust/) >>-发布和讨论与螃蟹有关的问题、文章和资源的分论坛。

## 许可证

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
