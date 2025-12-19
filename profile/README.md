# SharwAPI

[简体中文](/profile/README_CN.md) | [English](/profile/README.md)

[![Stars](https://img.shields.io/github/stars/sharwapi/sharwapi.core?label=Stars)](https://github.com/sharwapi/sharwapi.core)
[![Github release](https://img.shields.io/github/v/tag/sharwapi/sharwapi.core?label=API%20Release)](https://github.com/sharwapi/sharwapi.core/releases)
[![GitHub last commit](https://img.shields.io/github/last-commit/sharwapi/sharwapi.core)](https://github.com/sharwapi/sharwapi.core/commits/main)
[![GitHub issues](https://img.shields.io/github/issues/sharwapi/sharwapi.core)](https://github.com/sharwapi/sharwapi.core/issues)

SharwAPI (also known as Sharw's API) is a modular API framework built on .NET. It is lightweight, high-performance, extensible, and easy to use.

**[Documentation](https://sharwapi.hope-now.top)** | **[Download](https://github.com/sharwapi/sharwapi.core/releases)** | **[Plugin Market](https://sharwapi.hope-now.top/market)**

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

## Licenses

Different projects within this organization operate under different licenses, roughly as follows:

- [sharwapi_docs](https://github.com/sharwapi/sharwapi_docs) is licensed under the [MIT License](https://github.com/sharwapi/sharwapi_docs/blob/main/LICENSE-CODE.md) and [CC-BY-4.0 License](https://github.com/sharwapi/sharwapi_docs/blob/main/LICENSE-CONTENT.md).
- [sharwapi_plugins_collection](https://github.com/sharwapi/sharwapi_plugins_collection) is licensed under the [MIT License](https://github.com/sharwapi/sharwapi_plugins_collection/blob/main/LICENSE).
- [sharwapi.Plugin.guard](https://github.com/sharwapi/sharwapi.Plugin.guard) is licensed under the [GNU Lesser General Public License v3.0](https://github.com/sharwapi/sharwapi.Plugin.guard/blob/main/LICENSE).
- [sharwapi_market](https://github.com/sharwapi/sharwapi_market) is licensed under the [GNU Affero General Public License v3.0](https://github.com/sharwapi/sharwapi_market/blob/main/LICENSE).
- [sharwapi.Plugin.apimgr](https://github.com/sharwapi/sharwapi.Plugin.apimgr) is licensed under the [GNU Lesser General Public License v3.0](https://github.com/sharwapi/sharwapi.Plugin.apimgr/blob/main/LICENSE).
- [sharwapi.Contracts.Core](https://github.com/sharwapi/sharwapi.Contracts.Core) is licensed under the [GNU Lesser General Public License v3.0](https://github.com/sharwapi/sharwapi.Contracts.Core/blob/main/LICENSE).
- [sharwapi.Core](https://github.com/sharwapi/sharwapi.Core) is licensed under the [GNU General Public License v3.0](https://github.com/sharwapi/sharwapi.Core/blob/main/LICENSE).

## Todo

- [ ] Refactor the plugin system.
- [ ] Develop a database service plugin.
- [ ] Rewrite the plugin management system of the API framework.
- [ ] Draft the first edition of the Sharw API Plugin Specification.
- [ ] Release v0.1.0
- [ ] Change repositories from private to public