# Bootimus - 懒猫云应用

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![LazyCat Cloud](https://img.shields.io/badge/LazyCat-Cloud-blue)](https://lazycat.cloud)

A Complete enhanced version of the PXE server supporting booting from ISOs written in Golang and Deployable via containers or binaries.

## 功能特性

- 🖥️ **PXE 启动**: 支持从 ISO 文件进行网络启动
- 🌐 **Web 管理界面**: 通过 8080 端口提供 Web UI
- 📦 **容器化部署**: 即开即用，无需复杂配置
- ⚡ **Golang 编写**: 高性能，低资源占用

## 安装说明

通过懒猫应用商店安装，搜索 "Bootimus" 即可。

## 端口说明

| 端口 | 协议 | 用途 |
|------|------|------|
| 8080 | TCP | Web 管理界面 |
| 8081 | TCP | PXE 启动 HTTP 服务 |
| 69 | UDP | TFTP 启动服务 |

## 相关链接

- **官方仓库**: https://github.com/garybowers/bootimus
- **懒猫开发者文档**: https://developer.lazycat.cloud

## 许可证

MIT License