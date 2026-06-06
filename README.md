<div align="center">
  <img src="docs/nb-panel-logo.png" alt="NP-Master" height="100">
  <h1>NP-Master</h1>
  <p><strong>NP 主控端 · 一键安装管理脚本</strong></p>
  <p>
    <a href="https://github.com/lima-droid/NP-Master/releases">
      <img src="https://img.shields.io/github/v/release/lima-droid/NP-Master?style=flat-square&label=版本&color=2496ed" alt="Release">
    </a>
    <a href="https://github.com/lima-droid/NP-Master">
      <img src="https://img.shields.io/github/stars/lima-droid/NP-Master?style=flat-square&label=Star&color=ffc107" alt="Stars">
    </a>
    <a href="https://github.com/lima-droid/NP-Master/blob/main/LICENSE">
      <img src="https://img.shields.io/github/license/lima-droid/NP-Master?style=flat-square&label=许可&color=success" alt="License">
    </a>
    <a href="https://github.com/lima-droid/NP-Master/actions">
      <img src="https://img.shields.io/github/actions/workflow/status/lima-droid/NP-Master/release.yml?style=flat-square&label=构建&color=ff69b4" alt="Build">
    </a>
    <a href="https://github.com/lima-droid/NP-Master">
      <img src="https://img.shields.io/github/last-commit/lima-droid/NP-Master?style=flat-square&label=更新&color=blueviolet" alt="Last Commit">
    </a>
  </p>
</div>

---

## 📦 一键安装

```bash
bash <(wget -qO- https://raw.githubusercontent.com/lima-droid/NP-Master/main/scripts/np.sh) -i
```

> 支持 Linux / Docker 环境，包含稳定版、最新版、经典版三版本。

---

## ✨ 核心特性

| 特性 | 说明 |
|------|------|
| 🎯 **三版本支持** | 稳定版(v1.15.0) / 最新版(v1.16.0) / 经典版(v1.10.3) |
| 🔄 **版本切换** | `np -t` 一键切换，无需重装 |
| 🚀 **离线安装** | GitHub 离线包模式，双击安装 |
| 🐧 **全平台** | Debian / Ubuntu / CentOS / Alpine / OpenWRT / Arch |
| 🔒 **TLS 加密** | 自签 / 自定义证书 |
| 🌐 **内网穿透** | 支持内网穿透配置 |
| 🐳 **Docker 检测** | 自动识别 Docker 容器环境 |

---

## 🚀 快速使用

| 命令 | 说明 |
|------|------|
| `np` | 🎛️ 交互式菜单 |
| `np -i` | 📥 安装 |
| `np -u` | 🗑️ 卸载 |
| `np -v` | ⬆️ 升级内核 |
| `np -t` | 🔄 切换版本 |
| `np -o` | ▶️ 启动 / ⏹️ 停止服务 |
| `np -k` | 🔑 更换 API Key |
| `np -c` | 🌐 更换内网穿透 |
| `np -s` | 📊 查看 API 信息 |
| `np -p` | 🚧 端口转发规则 |
| `np -h` | ❓ 帮助 |

---

## 📋 系统要求

- 🐧 **Linux**（发行版不限）
- 👑 **root 权限**
- 📡 **wget** 或 **curl**

---

## 📝 更新日志

- **v0.0.8** — 三版本绑定，GitHub 直达包

---

## ⭐ Stargazers

[![Stargazers](https://img.shields.io/github/stars/lima-droid/NP-Master?style=for-the-badge&logo=github&color=gold)](https://github.com/lima-droid/NP-Master)
