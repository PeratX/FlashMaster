# FlashMaster Classic 已废弃 / Deprecated

[English](#flashmaster-classic-deprecated)

> 本仓库已废弃，不再作为 FlashMaster 的主要版本维护。请使用新版 FlashMaster。
>
> This repository is deprecated and is no longer maintained as the primary FlashMaster version. Please use the new FlashMaster.

## 请使用新版 FlashMaster

- 在线使用：[fm.itxtech.org](https://fm.itxtech.org)
- 新版仓库：[iTXTech/FlashMaster](https://github.com/iTXTech/FlashMaster)
- 新版解码引擎：[iTXTech/fdnext](https://github.com/iTXTech/fdnext)

新版 FlashMaster 是基于 Vue 3、Vite、Vuetify 和 Vue I18n 的静态 Web 工作站。它默认在浏览器内运行 fdnext 嵌入式解析器，可直接完成 NAND Flash 料号查询、Flash ID 解码、数据库搜索、结果检查、复制、语言切换、主题设置等工作，也保留了 FlashDetector HTTP API 兼容模式。

如果你只是想查询 NAND Flash 料号或 Flash ID，请直接使用新版 Web 版 FlashMaster，不建议继续使用本仓库中的经典桌面版资料。

## 本仓库是什么

本仓库保存的是旧版 FlashMaster 桌面 GUI 客户端相关资料。该客户端使用易语言编写，依赖 FlashDetector HTTP API 或内嵌服务端返回查询结果。

这些文件仅用于历史归档和兼容参考：

- `changelog.txt`：经典桌面版更新日志。
- `update.json` / `update_en.json`：旧版自动更新元信息。
- `servers.json`：旧版 FlashDetector 服务端列表。
- `FDOCS.md`：已废弃的一键服务端说明。
- `FlashInfo.md`：闪存数据提交说明。

## 旧版状态

- 经典桌面版已停止新功能开发。
- 本仓库不再推荐作为新用户入口。
- 旧版资料可能无法反映最新数据库、解析能力和 Web 版功能。
- 如需跨平台、免安装、最新 Flash ID 解码和 fdnext 本地解析能力，请迁移到新版 FlashMaster。

## 历史版本信息

以下内容仅供历史版本查阅：

- 版本：`1.9.0.30-Preview1`
- CRC32：`DEF34642`
- 内嵌服务端：SimpleFramework `2.2.1` / FlashDetector `V78`
- 系统要求：Windows 7 及以上
- 运行依赖：[VC++ x86 可再发行组件包](https://aka.ms/vs/17/release/vc_redist.x86.exe)
- 历史下载：[FlashMaster-1.9.0.30-Preview1-Full-FD78.zip](https://github.com/PeratX/FlashMaster/releases/download/V1218/FlashMaster-1.9.0.30-Preview1-Full-FD78.zip)

## 数据贡献

如果你希望补充或修正闪存数据，请优先到 [iTXTech/fdfdb](https://github.com/iTXTech/fdfdb) 提交 Pull Request。旧的邮件模板仍可参考 [FlashInfo.md](FlashInfo.md)。

## 相关项目

- [FlashMaster Web](https://github.com/iTXTech/FlashMaster)
- [fdnext](https://github.com/iTXTech/fdnext)
- [FlashDetector](https://github.com/iTXTech/FlashDetector)
- [fdfdb](https://github.com/iTXTech/fdfdb)
- [FlashMasterAndroid](https://github.com/iTXTech/FlashMasterAndroid)
- [FlashMasteriOS](https://github.com/iTXTech/FlashMasteriOS)

## 版权

[FlashDetector](https://github.com/iTXTech/FlashDetector) 是遵循 `GNU AGPL 3.0` 的开源项目，由 [iTX Technologies](https://itxtech.org) 创建并维护。

FlashMaster 经典桌面版由 `PeratX` 使用易语言编写。

Copyright (C) 2018-2022 PeratX. All rights reserved.

---

# FlashMaster Classic Deprecated

[中文](#flashmaster-classic-已废弃--deprecated)

This repository is deprecated. It is kept only for historical release metadata, legacy update files, and compatibility references for the old FlashMaster desktop GUI.

Please use the new FlashMaster instead:

- Launch online: [fm.itxtech.org](https://fm.itxtech.org)
- New repository: [iTXTech/FlashMaster](https://github.com/iTXTech/FlashMaster)
- New decoding engine: [iTXTech/fdnext](https://github.com/iTXTech/fdnext)

The new FlashMaster is a static Web workstation built with Vue 3, Vite, Vuetify, and Vue I18n. It runs the embedded fdnext parser directly in the browser by default, supports NAND Flash part-number lookup, Flash ID decoding, database search, result inspection, copy actions, language switching, theme settings, and keeps a FlashDetector HTTP API compatibility mode.

For normal NAND Flash part-number or Flash ID lookup, use the new Web version. The classic desktop edition in this repository is no longer recommended for new users.

## What This Repository Contains

This repository contains files for the old FlashMaster desktop GUI client written in 易语言. The client used FlashDetector HTTP API responses or a bundled embedded server to display query results.

The files are kept as an archive:

- `changelog.txt`: classic desktop changelog.
- `update.json` / `update_en.json`: legacy update metadata.
- `servers.json`: legacy FlashDetector server list.
- `FDOCS.md`: deprecated one-click server documentation.
- `FlashInfo.md`: NAND Flash data submission notes.

## Legacy Status

- No new features are planned for the classic desktop edition.
- This repository is no longer the recommended entry point for FlashMaster.
- Legacy metadata may not reflect the latest database, decoding behavior, or Web features.
- For cross-platform access, no-install usage, newer Flash ID decoding, and local fdnext parsing, migrate to the new FlashMaster.

## Historical Release

The following information is kept only for historical reference:

- Version: `1.9.0.30-Preview1`
- CRC32: `DEF34642`
- Embedded server: SimpleFramework `2.2.1` / FlashDetector `V78`
- System requirement: Windows 7 and above
- Runtime dependency: [VC++ x86 redistributable](https://aka.ms/vs/17/release/vc_redist.x86.exe)
- Historical download: [FlashMaster-1.9.0.30-Preview1-Full-FD78.zip](https://github.com/PeratX/FlashMaster/releases/download/V1218/FlashMaster-1.9.0.30-Preview1-Full-FD78.zip)

## Data Contribution

To add or correct NAND Flash data, please submit a Pull Request to [iTXTech/fdfdb](https://github.com/iTXTech/fdfdb). The old email template remains available in [FlashInfo.md](FlashInfo.md).

## Related Projects

- [FlashMaster Web](https://github.com/iTXTech/FlashMaster)
- [fdnext](https://github.com/iTXTech/fdnext)
- [FlashDetector](https://github.com/iTXTech/FlashDetector)
- [fdfdb](https://github.com/iTXTech/fdfdb)
- [FlashMasterAndroid](https://github.com/iTXTech/FlashMasterAndroid)
- [FlashMasteriOS](https://github.com/iTXTech/FlashMasteriOS)

## Copyright

[FlashDetector](https://github.com/iTXTech/FlashDetector) is an open-source project under `GNU AGPL 3.0`, created and maintained by [iTX Technologies](https://itxtech.org).

The classic FlashMaster desktop edition was written by `PeratX` in 易语言.

Copyright (C) 2018-2022 PeratX. All rights reserved.
