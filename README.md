# Verdent Token Manager

<div align="center">

![Verdent Token Manager](https://img.shields.io/badge/Verdent-Token%20Manager-blue)
![Version](https://img.shields.io/github/v/release/Yuy-0415/verdent-token-mng)
![Downloads](https://img.shields.io/github/downloads/Yuy-0415/verdent-token-mng/total)
![License](https://img.shields.io/badge/license-MIT-green)

**一款专业的 Verdent AI 平台 Token 管理工具**

[下载安装](#-下载安装) • [功能特性](#-功能特性) • [使用说明](#-使用说明) • [常见问题](#-常见问题)

</div>

---

## 📥 下载安装

前往 [Releases](https://github.com/Yuy-0415/verdent-token-mng/releases) 页面下载最新版本。

### Windows

- **推荐**: `Verdent-Token-Manager_x.x.x_x64-setup.exe` (NSIS 安装包)
- 或者: `Verdent-Token-Manager_x.x.x_x64_en-US.msi` (MSI 安装包)

### macOS

- **Intel 芯片**: `Verdent-Token-Manager_x.x.x_x64.dmg`
- **M1/M2 芯片**: `Verdent-Token-Manager_x.x.x_aarch64.dmg`

### Linux

- **Debian/Ubuntu**: `verdent-token-manager_x.x.x_amd64.deb`
- **通用**: `verdent-token-manager_x.x.x_amd64.AppImage`

### VSCode 插件

- **Verdent 修改版插件**: `Verdent修改版.vsix`
- 下载后在 VSCode 中通过 "从 VSIX 安装" 进行安装

---

## ✨ 功能特性

### 🔐 Token 管理
- 批量添加和管理 Verdent AI Token
- 支持 Token 有效性检测
- 自动获取账户余额信息
- Token 分组和标签管理

### 💾 数据存储
- 本地文件存储
- PostgreSQL 数据库同步（可选）
- 双向数据同步功能

### 🔄 自动更新
- 自动检测新版本
- 一键更新到最新版本

### 🌐 代理支持
- HTTP/HTTPS 代理配置
- SOCKS5 代理支持

### 🎨 用户界面
- 现代化的用户界面
- 深色/浅色主题切换
- 多语言支持（中文/英文）

---

## 📖 使用说明

### 1. 安装应用

下载对应平台的安装包，按照提示完成安装。

### 2. 添加 Token

1. 点击 **"添加Token"** 按钮
2. 输入或粘贴 Token
3. 支持批量添加（每行一个 Token）
4. 点击保存

### 3. 管理 Token

- **查看余额**: 自动显示每个 Token 的余额
- **检测有效性**: 一键检测 Token 是否有效
- **删除 Token**: 选中后点击删除按钮
- **导出数据**: 支持导出为 JSON 格式

### 4. 数据库同步（可选）

1. 点击设置按钮
2. 配置 PostgreSQL 数据库连接
3. 测试连接成功后保存
4. 使用同步功能进行数据备份

---

## 🔧 系统要求

### Windows
- Windows 10 或更高版本
- 64 位系统

### macOS
- macOS 10.15 (Catalina) 或更高版本
- Intel 或 Apple Silicon (M1/M2) 芯片

### Linux
- Ubuntu 20.04 或更高版本
- Debian 11 或更高版本
- 其他发行版请使用 AppImage

---

## ❓ 常见问题

### 如何获取 Verdent AI Token?

请访问 [Verdent AI 官网](https://verdent.ai) 注册账户并获取 Token。

### Token 数据存储在哪里?

默认存储在本地应用数据目录：
- **Windows**: `%APPDATA%\com.verdent.token-manager`
- **macOS**: `~/Library/Application Support/com.verdent.token-manager`
- **Linux**: `~/.config/com.verdent.token-manager`

### 如何备份数据?

1. 使用导出功能导出为 JSON 文件
2. 或配置 PostgreSQL 数据库进行云端备份

### 应用无法启动怎么办?

1. 确认系统版本符合要求
2. Windows 用户请安装 [WebView2 Runtime](https://developer.microsoft.com/en-us/microsoft-edge/webview2/)
3. 尝试以管理员权限运行

---

## 🔗 相关项目

本项目参考了以下优秀项目：

- **ATM (Augment Token Manager)**: [zhaochengcube/augment-token-mng](https://github.com/zhaochengcube/augment-token-mng)
  - 参考此项目的布局以及部分功能

- **Verdent Account Manager**: [chaogei/verdent-account-manager](https://github.com/chaogei/verdent-account-manager)
  - 参考此项目提供的VSIX

---

## 📄 许可证

本项目采用 MIT 许可证。详见 [LICENSE](LICENSE) 文件。

---

## 🤝 支持

如有问题或建议，请在 [Issues](https://github.com/Yuy-0415/verdent-token-mng/issues) 中反馈。

---

<div align="center">

**Made with ❤️ by VTM Team**

</div>

