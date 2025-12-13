# SharwAPI

[![Stars](https://img.shields.io/github/stars/sharwapi/sharwapi.core?label=Stars)](https://github.com/sharwapi/sharwapi.core)
[![Github release](https://img.shields.io/github/v/tag/sharwapi/sharwapi.core)](https://github.com/sharwapi/sharwapi.core/releases)
[![GitHub](https://img.shields.io/github/license/sharwapi/sharwapi.core)](https://github.com/sharwapi/sharwapi.core/blob/main/LICENSE)
[![GitHub last commit](https://img.shields.io/github/last-commit/sharwapi/sharwapi.core)](https://github.com/sharwapi/sharwapi.core/commits/main)
[![GitHub issues](https://img.shields.io/github/issues/sharwapi/sharwapi.core)](https://github.com/sharwapi/sharwapi.core/issues)

SharwAPI (also known as Sharw's API) is a modular API framework built on .NET. It is lightweight, high-performance, extensible, and easy to use.

SharwAPI (又称Sharw's API) 是一款基于.NET开发的模块化API框架，轻量、高性能、可扩展，且简单易用。

**[Documentation | 文档](https://sharwapi.hope-now.top)** | **[Download | 下载](https://github.com/sharwapi/sharwapi.core/releases)** | 🧩 **[Plugin Market | 插件市场](https://sharwapi.hope-now.top/market)**

## Features

- **Plugin-Based Architecture**: Actual functionality is split into independent **Plugins**. The **CoreAPI** is only responsible for low-level tasks such as plugin loading and route registration, containing absolutely no business logic code.
- **Lightweight**: Compared to traditional API frameworks, SharwAPI allows you to assemble features like LEGO blocks. You only need to load the plugins you require, without wasting resources and time on unused functions.
- **Easy to Use**: The underlying infrastructure is already built for you. You don't need to deal with tedious low-level details—just focus on developing the features you want.
- **Cross-Platform**: Powered by the robust capabilities of .NET, this project can run on **almost** any platform.

## Repositories

Main repositories under this organization:

- [sharwapi_docs](https://github.com/sharwapi/sharwapi_docs) - Online documentation for the API framework.
- [sharwapi_plugins_collection](https://github.com/sharwapi/sharwapi_plugins_collection) - The plugin index repository.
- [sharwapi.Plugin.guard](https://github.com/sharwapi/sharwapi.Plugin.guard) - Route protection plugin repository.
- [sharwapi_market](https://github.com/sharwapi/sharwapi_market) - Source code for the Plugin Market.
- [sharwapi.Plugin.apimgr](https://github.com/sharwapi/sharwapi.Plugin.apimgr) - API management plugin repository.
- [sharwapi.Contracts.Core](https://github.com/sharwapi/sharwapi.Contracts.Core) - The interface layer of the API framework.
- [sharwapi.Core](https://github.com/sharwapi/sharwapi.Core) - The core repository of the API framework.

## Todo

- [ ] Refactor the plugin system.
- [ ] Develop a database service plugin.
- [ ] Rewrite the plugin management system of the API framework.
- [ ] Draft the first edition of the Sharw API Plugin Specification.
- [ ] Release v0.1.0
- [ ] Change repositories from private to public

---

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

## 待办

- [ ] 重构插件系统
- [ ] 编写用于提供数据库服务的插件
- [ ] 重写API框架的插件管理系统
- [ ] 编写Sharw API第一版插件规范
- [ ] 发布v0.1.0版本
- [ ] 仓库从private修改为public