<div align="center">

# 🚀 Antigravity 账号管理器 (Antigravity Switcher)

**专为 Google Antigravity 2.0 深度定制的多账号秒级切换、原生配额实时监控与一键中文汉化增强工具**

[![Release](https://img.shields.io/github/v/release/tangxiaomao6666/antigravity-switcher-releases?color=blue&label=最新版本&logo=github)](https://github.com/tangxiaomao6666/antigravity-switcher-releases/releases/latest)
[![Platform](https://img.shields.io/badge/Windows-10%20%7C%2011%20(64--bit)-0078D6?logo=windows&logoColor=white)](https://github.com/tangxiaomao6666/antigravity-switcher-releases/releases)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Antigravity](https://img.shields.io/badge/Antigravity-2.0%20Ready-7C3AED)](https://github.com/tangxiaomao6666/antigravity-switcher-releases)
[![Free CDN](https://img.shields.io/badge/CDN加速-内置国内镜像-success)](https://github.com/tangxiaomao6666/antigravity-switcher-releases)

[📥 立即下载最新版安装包](#-高速下载与安装) • [✨ 核心功能](#-核心特性) • [📖 使用说明](#-三分钟快速上手) • [🛡️ 安全声明](#️-安全与隐私说明)

</div>

---

## 🌟 为什么需要 Antigravity 账号管理器？

在使用 **Google Antigravity 2.0** 开展高强度编程与深度开发时，单一账号往往会迅速触碰 Gemini 与 Claude / GPT 的 **5 小时或每周限制**。官方客户端并不支持多账号并行管理，频繁注销、重新扫码授权极其繁琐，且无法直观查看各备用账号的额度恢复进度。

**Antigravity 账号管理器** 完美解决了上述所有痛点：
* **无缝秒级切换**：利用 Windows 凭据管理原生接管会话，一键切换账号，无需重新登录。
* **原生配额监控**：直连本地客户端内部信令，100% 精确还原官方 Gemini、Claude、GPT 额度环形图与恢复倒计时。
* **中文极速汉化**：一键注入中文汉化引擎，支持随时无损一键还原官方英文。
* **极致轻量顺滑**：常驻内存低至 10~18 MB，内置自愈单实例架构，稳定不卡死。

---

## ✨ 核心特性

### 1. ⚡ 毫秒级多账号安全热切换
* 深度整合 **Windows 凭据管理器（Credential Manager）** 与 Antigravity 本地 Session 存储。
* 一键重启并载入目标账号凭据，彻底告别频繁登出、重新授权与风控烦恼。
* 支持账号**自定义重命名**、**一键置顶常用号**与**一键覆盖更新当前凭据**。

### 2. 📊 100% 原生全自动额度监控与智能调度
* **直连底层服务**：与本地 `language_server` 内部高速通信（单次耗时仅 6ms），不向 Google 官方发送任何未授权网络爬虫请求，**0 封号风险**。
* **多模型精准展示**：
  * **Gemini 系列**：实时展示 5 小时高频限制与每周配额，像素级匹配官方恢复倒计时（如 `Resets in 3d 19h`）。
  * **Claude & GPT 系列**：独立双进度条直观呈现用量百分比。
* **全并发离线推算**：备用闲置账号基于配额快照与恢复时间戳，在后台全自动推算额度恢复进度。
* **智能闲置推荐**：主界面横幅智能探查各备用账号冷却状态，优先推荐“额度已完全回满”的账号。

### 3. 🌐 内置 Antigravity 2.0 中文汉化引擎
* 内嵌高精度本地化字典库，覆盖菜单、侧边栏、状态栏、设置面板等 95%+ 界面元素。
* **一键无损汉化**：点击即可快速完成汉化注入。
* **随时还原**：支持一键完整撤销并无损恢复官方原生英文。

### 4. 🧠 内核级内存压缩与自愈架构
* **内存极简**：引入 Windows 内核级工作集压缩算法（EmptyWorkingSet），后台常驻托盘内存仅 **10~18 MB**，资源占用降低 70%+。
* **双向信令自愈机制**：采用端口双向握手防卡死技术，若后台存在卡死僵尸进程，再次启动时自动自愈清理并唤醒窗口，**保证桌面图标双击 100% 响应**。
* **高 DPI 托盘图标**：采用 32x32 Lanczos 抗锯齿重采样，完美适配 Win10/Win11 任意高分屏缩放。

### 5. 🚀 国内免费 CDN 极速在线更新
* 客户端启动时自动检测 GitHub 最新发布版。
* **内置国内 CDN 免代理通道**（自动测速与轮询回退），无需开启科学上网即可满速下载更新并平滑覆盖升级。

---

## 📥 高速下载与安装

### 方式一：独立通用安装包（推荐）

| 下载通道 | 下载链接 | 适用环境 |
| :--- | :--- | :--- |
| 🚀 **GitHub 官方通道** | [AntigravitySwitcher_Setup.exe](https://github.com/tangxiaomao6666/antigravity-switcher-releases/releases/latest/download/AntigravitySwitcher_Setup.exe) | 海外 / 开启代理环境 |
| ⚡ **国内免费 CDN 镜像** | [免代理极速下载通道](https://gh-proxy.com/https://github.com/tangxiaomao6666/antigravity-switcher-releases/releases/latest/download/AntigravitySwitcher_Setup.exe) | 国内直连 / 满速下载 |

> **系统要求**：Windows 10 / Windows 11 (64-bit)，且本机已安装 [Google Antigravity](https://antigravity.google.com/)。

---

## 📖 三分钟快速上手

### 第一步：保存当前使用的账号
1. 启动并正常登录你的官方 Antigravity 客户端。
2. 打开 **AntigravitySwitcher**，点击右上角 **【＋ 保存新账号】**。
3. 输入易于识别的名称（如 `主力账号` 或 `工作账号`），管理器将自动绑定凭据与当前邮箱。

### 第二步：添加备用账号
1. 在官方 Antigravity 客户端中点击左下角头像退出当前登录，并登录你的第 2 个 Google 账号。
2. 回到 AntigravitySwitcher 界面，再次点击右上角 **【＋ 保存新账号】**，命名为 `备用账号 1`。
3. 依此类推，可自由录入 3 个、5 个或更多账号存档。

### 第三步：自由秒级切换
* 在主界面卡片中找到目标账号，点击 **【⚡ 切换至此账号】**。
* 管理器将自动无痕重载会话凭据并平滑拉起 Antigravity，耗时仅需 1~2 秒！

---

## ⚙️ 个性化设置推荐

点击界面右上角 **【⚙️ 设置】** 即可打开分类配置面板：
* **网络与代理**：若日常使用 Clash/V2Ray/Surge 等免 TUN 代理工具，可在此开启“启动联动环境变量代理”，解决部分环境下登录网络受阻问题。
* **托盘常驻**：可自由开关“点击右上角✕最小化至托盘”（默认关闭，点击✕直接干净退出）。
* **中文汉化**：在“界面汉化”标签页下一键执行汉化安装或卸载还原。

---

## 🛡️ 安全与隐私说明

* **100% 本地运行**：本工具为独立客户端，所有账号凭据与数据均存放在本机系统凭据管理器与 `%APPDATA%\AntigravitySwitcher` 目录。
* **不上传任何凭据**：本程序绝不收集、转发或上传用户的任何 Token、密码、私钥或代码片段到外部服务器。
* **官方无侵入**：额度探查仅利用本地回环接口（127.0.0.1）读取客户端状态，不修改核心通信协议，安全无风险。

---

## 📝 开源与免责声明

* 本项目为开源免费工具，仅供个人技术研究与日常开发提效使用。
* Google、Gemini、Antigravity 及其相关商标均为 Google LLC 的资产，本项目与 Google 官方无关。

<div align="center">
如果这个项目帮助你提升了开发效率，欢迎给本项目点个 ⭐️ <b>Star</b> 支持一下！
</div>
