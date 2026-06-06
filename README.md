<div align="center">
  <img src="docs/nb-panel-logo.png" alt="NP主控端" height="120">
</div>

# NP主控端

一键安装管理脚本，支持 Linux / Docker 环境。

## 一键安装

```bash
bash <(wget -qO- https://raw.githubusercontent.com/lima-droid/NP-Master/main/scripts/np.sh) -i
```

## 特性

- 三版本支持：稳定版(v1.15.0) / 最新版(v1.16.0) / 经典版(v1.10.3)
- 版本切换 `np -t`，无需重装
- 双击安装，GitHub 离线包模式
- 全 Linux 发行版支持（Debian/Ubuntu/CentOS/Alpine/OpenWRT/Arch）
- TLS 加密（自签/自定义证书）
- 内网穿透
- Docker 容器环境自动检测

## 使用方法

```bash
np        # 交互式菜单
np -i     # 安装
np -u     # 卸载
np -v     # 升级内核
np -t     # 切换版本（稳定/最新/经典）
np -o     # 启动/停止服务
np -k     # 更换 API Key
np -c     # 更换内网穿透
np -s     # 查看 API 信息
np -p     # 端口转发规则
np -h     # 帮助
```

## 系统要求

- Linux
- root 权限
- wget 或 curl

## 更新日志

- GitHub 直达包


## Stargazers

[![GitHub Stars](https://img.shields.io/github/stars/lima-droid/NP-Master?style=for-the-badge&logo=github&color=gold)](https://github.com/lima-droid/NP-Master)
