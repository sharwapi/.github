# SharwAPI

[简体中文](/profile/README_CN.md) | [English](/profile/README.md)

[![Stars](https://img.shields.io/github/stars/sharwapi/sharwapi.core?label=Stars)](https://github.com/sharwapi/sharwapi.core)
[![Github release](https://img.shields.io/github/v/tag/sharwapi/sharwapi.core?label=API)](https://github.com/sharwapi/sharwapi.core/releases)
[![GitHub last commit](https://img.shields.io/github/last-commit/sharwapi/sharwapi.core)](https://github.com/sharwapi/sharwapi.core/commits/main)
[![GitHub issues](https://img.shields.io/github/issues/sharwapi/sharwapi.core)](https://github.com/sharwapi/sharwapi.core/issues)

SharwAPI (又称Sharw's API) 是一款基于.NET开发的模块化API框架，轻量、高性能、可扩展，且简单易用。

**[文档](https://sharwapi.hope-now.top)** | **[下载](https://github.com/sharwapi/sharwapi.core/releases)** | **[插件市场](https://sharwapi-market.hope-now.top)**

## 特性

- **功能插件化**: 将实际功能分为独立的 **插件(Plugin)** ，**API本体(CoreAPI)** 仅负责插件加载、路由注册等底层任务，没有任何的业务代码
- **轻量化**: 相较于传统API框架，本项目可以让你像搭积木一样只加载你需要的插件，而不必分去大量的资源和时间给用不到的功能
- **简单易用**: 基础框架已经打好，你无须处理繁琐的底层工作，可以专注开发你想要的功能
- **跨平台**: 依托于.NET的强大能力，本项目可以运行到 **几乎** 任何平台上

## 仓库

本组织下的一些主要仓库：

- [sharwapi_docs](https://github.com/sharwapi/sharwapi_docs) - API框架的在线文档
- [sharwapi_plugins_collection](https://github.com/sharwapi/sharwapi_plugins_collection) - 插件索引仓库
- [sharwapi.Plugin.guard](https://github.com/sharwapi/sharwapi.Plugin.guard) - 路由保护插件仓库
- [sharwapi_market](https://github.com/sharwapi/sharwapi_market) - 插件市场源码仓库
- [sharwapi.Plugin.apimgr](https://github.com/sharwapi/sharwapi.Plugin.apimgr) - API管理插件仓库
- [sharwapi.Contracts.Core](https://github.com/sharwapi/sharwapi.Contracts.Core) - API框架接口层
- [sharwapi.Core](https://github.com/sharwapi/sharwapi.Core) - API框架本体仓库

## 许可证

本组织中的不同项目拥有不同的许可证，大致如下：

- [sharwapi_docs](https://github.com/sharwapi/sharwapi_docs) 基于 [MIT License](https://github.com/sharwapi/sharwapi_docs/blob/main/LICENSE-CODE.md) 和 [CC-BY-4.0 License](https://github.com/sharwapi/sharwapi_docs/blob/main/LICENSE-CONTENT.md) 获得许可
- [sharwapi_plugins_collection](https://github.com/sharwapi/sharwapi_plugins_collection) 基于 [MIT License](https://github.com/sharwapi/sharwapi_plugins_collection/blob/main/LICENSE) 获得许可
- [sharwapi.Plugin.guard](https://github.com/sharwapi/sharwapi.Plugin.guard) 基于 [GNU Lesser General Public License v3.0](https://github.com/sharwapi/sharwapi.Plugin.guard/blob/main/LICENSE) 获得许可
- [sharwapi_market](https://github.com/sharwapi/sharwapi_market) 基于 [GNU Affero General Public License v3.0](https://github.com/sharwapi/sharwapi_market/blob/main/LICENSE) 获得许可
- [sharwapi.Plugin.apimgr](https://github.com/sharwapi/sharwapi.Plugin.apimgr) 基于 [GNU Lesser General Public License v3.0](https://github.com/sharwapi/sharwapi.Plugin.apimgr/blob/main/LICENSE) 获得许可
- [sharwapi.Contracts.Core](https://github.com/sharwapi/sharwapi.Contracts.Core) 基于 [GNU Lesser General Public License v3.0](https://github.com/sharwapi/sharwapi.Contracts.Core/blob/main/COPYING.LESSER) 获得许可
- [sharwapi.Core](https://github.com/sharwapi/sharwapi.Core) 基于 [GNU General Public License v3.0](https://github.com/sharwapi/sharwapi.Core/blob/main/LICENSE) 获得许可

## 待办

~~ - [ ] 重构插件系统 ~~
- [ ] 编写用于提供数据库服务的插件
~~ - [ ] 重写API框架的插件管理系统 ~~
- [ ] 编写Sharw API第一版插件规范
- [x] 发布v0.1.0版本
- [x] 仓库从private修改为public