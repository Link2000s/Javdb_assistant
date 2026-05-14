# Javdb全能助手（JavdbBuddy）

[![MIT License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-0.7.0-blue.svg)](https://github.com/86168057/JavdbBuddy/releases)
[![Greasy Fork](https://img.shields.io/badge/Greasy%20Fork-Javdb全能助手-orange)](https://greasyfork.org/scripts/564141)

JAVDB 一站式增强 Tampermonkey 用户脚本，集成 Emby 入库状态同步、预览图查看、磁力链管理、多站点快捷搜索、免VIP热播/Top250/FC2PPV、全部评论、相关清单等功能。

> **English**: JavdbBuddy - JAVDB All-in-One Assistant Tampermonkey userscript. Features: Emby library sync, preview image viewer, magnet link management, multi-site quick search, Hot/Top250/FC2PPV, all reviews, related lists, and more.

---

## ✨ 功能特性

| 功能 | 说明 |
|------|------|
| 📋 **Emby 入库状态** | 列表页/详情页实时显示影片在 Emby 服务器中的入库状态 |
| 🖼️ **预览图查看** | 一键弹窗查看所有预览大图，支持全屏浏览 |
| 🧲 **磁力链管理** | JAVDB + JAVBUS 双标签磁力链弹窗，支持复制/下载 |
| 👩 **演员名单** | 预览图/磁力链弹窗顶部显示完整演员名单，可点击跳转 |
| 🔍 **多站点搜索** | 详情页一键搜索 98堂、BTSOW、JAVDB、JAVBUS、谷歌 |
| ⬆ **返回顶部/底部** | 右下角浮动按钮，快速跳转页面顶部或底部 |
| 📝 **短评查看** | 一键查看影片短评（需登录 JAVDB） |
| 🔥 **免VIP热播** | 无需VIP即可查看热播榜单 |
| 🏆 **免VIP Top250** | 无需VIP即可查看 Top250 榜单 |
| 🎥 **免VIP FC2PPV** | 无需VIP即可查看 FC2PPV 内容 |
| 💬 **全部评论** | 详情页加载全部评论内容 |
| 📑 **相关清单** | 免VIP查看相关清单内容 |
| 🖱️ **封面悬停放大** | 列表页封面图鼠标悬停自动放大展示 |

---

## 📦 安装

### 方法一：Greasy Fork（推荐）
前往 [Greasy Fork 页面](https://greasyfork.org/scripts/564141) 点击安装。

### 方法二：GitHub Releases
从 [Releases 页面](https://github.com/86168057/JavdbBuddy/releases) 下载最新版本，在 Tampermonkey 中通过"从文件导入"安装。

### 方法三：手动安装
1. 安装 [Tampermonkey](https://www.tampermonkey.net/) 浏览器扩展
2. 打开 [JavdbBuddy_v0.7.0.js](https://github.com/86168057/JavdbBuddy/raw/main/JavdbBuddy_v0.7.0.js)
3. Tampermonkey 自动弹出安装提示

---

## 🚀 使用方法

### 列表页

![列表页快捷按钮效果展示](https://raw.githubusercontent.com/86168057/JavdbBuddy/main/展示图/列表页快捷按钮效果展示.png)

- **小蓝按钮 🖼️ 预览图**：点击弹窗查看所有预览图
- **小粉按钮 🧲 磁力链**：点击弹窗查看 JAVDB + JAVBUS 双标签磁力链
- **小橙按钮 📝 短评**：点击获取影片短评

![列表页-预览图+演员名字-快捷键内容展示](https://raw.githubusercontent.com/86168057/JavdbBuddy/main/展示图/列表页-预览图+演员名字-快捷键内容展示.png)

![列表页-磁力链-快捷键内容展示](https://raw.githubusercontent.com/86168057/JavdbBuddy/main/展示图/列表页-磁力链-快捷键内容展示.png)

![列表页-短评-快捷键内容展示](https://raw.githubusercontent.com/86168057/JavdbBuddy/main/展示图/列表页-短评-快捷键内容展示.png)

![列表页-封面图-鼠标悬停图片放大功能展示](https://raw.githubusercontent.com/86168057/JavdbBuddy/main/展示图/列表页-封面图-鼠标悬停，图片放大功能展示.png)

### 详情页

![详情页emby入库状态标签+中多网站搜索功能展示](https://raw.githubusercontent.com/86168057/JavdbBuddy/main/展示图/详情页emby入库状态标签+中多网站搜索功能展示.png)

- **Emby 状态标签**：显示该影片的 Emby 入库状态
- **多站点搜索按钮**：一键在多个平台搜索该影片

![详情页-javdb+javbus-双标签磁力页展示](https://raw.githubusercontent.com/86168057/JavdbBuddy/main/展示图/详情页-javdb+javbus-双标签磁力页展示.png)

- **JAVDB / JAVBUS 双标签**：点击切换不同来源的磁力链列表

![详情页-短评-功能加载全部评论的功能展示](https://raw.githubusercontent.com/86168057/JavdbBuddy/main/展示图/详情页-短评-功能加载全部评论的功能展示.png)

![详情页-相关清单-免vip功能展示](https://raw.githubusercontent.com/86168057/JavdbBuddy/main/展示图/详情页-相关清单-免vip功能展示.png)

### 超级功能标签

![超级功能标签下的热播免VIP功能展示](https://raw.githubusercontent.com/86168057/JavdbBuddy/main/展示图/超级功能标签下的热播免VIP功能展示.png)

![超级功能标签下的top250免VIP功能展示](https://raw.githubusercontent.com/86168057/JavdbBuddy/main/展示图/超级功能标签下的top250免VIP功能展示.png)

![超级功能标签下的FC2免VIP功能展示](https://raw.githubusercontent.com/86168057/JavdbBuddy/main/展示图/超级功能标签下的FC2免VIP功能展示.png)

### 设置界面

![设置中-通用设置-界面展示](https://raw.githubusercontent.com/86168057/JavdbBuddy/main/展示图/设置中-通用设置-界面展示.png)

---

## 🔧 Emby 配置

1. 点击页面右下角的 ⚙️ 设置按钮
2. 添加 Emby 服务器地址和 API Key
3. 点击"同步服务器"按钮，脚本将自动扫描 Emby 库建立索引
4. 完成！列表页和详情页将显示 Emby 入库状态

---

## 📄 脚本说明

- **脚本名**: Javdb全能助手（JavdbBuddy）
- **版本**: 0.7.0
- **适用站点**: javdb.com
- **依赖**: 需要 Tampermonkey / Violentmonkey 等用户脚本管理器
- **许可**: MIT License

---

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

---

## 💖 赞助

如果这个脚本对你有帮助，欢迎打赏支持：

| 微信 | 支付宝 |
|------|--------|
| ![微信收款二维码](https://raw.githubusercontent.com/86168057/JavdbBuddy/main/收款二维码/微信收款二维码.png) | ![支付宝收款二维码](https://raw.githubusercontent.com/86168057/JavdbBuddy/main/收款二维码/支付宝收款二维码.png) |

---

## 📜 更新日志

### v0.7.0
- ✨ 新增：多网站搜索功能（移植自 JAV 添加跳转在线观看脚本）
- ✨ 新增：免VIP热播/Top250/FC2PPV 功能
- ✨ 新增：全部评论加载功能
- ✨ 新增：相关清单免VIP查看功能
- ✨ 新增：列表页封面图鼠标悬停放大功能
- 🔧 优化：展示图全面更新

### v0.6.0
- ✨ 新增：演员列表按性别区分颜色（男蓝女粉）
- ✨ 新增：Emby 同步后自动刷新页面入库状态（无需手动刷新）
- 🔧 优化：弹窗不再导致页面跳回顶部
- 🔧 优化：获取失败时显示具体原因（登录/验证/超时等）
- 🔧 优化：降低请求频率，减少触发 Cloudflare 验证
- 🔧 优化：预览图/磁力链数据缓存 + 详情页直接 DOM 提取（无需额外请求）

### v0.5.0
- 🔧 优化：脚本名改为中文「Javdb全能助手」，更新描述信息
- 🔧 优化：README 图片路径改为 GitHub 绝对 URL
- 🔧 优化：添加英文描述 @description:en

### v0.4.1
- 🔧 优化：脚本名改为中文「Javdb全能助手」，更新描述信息
- 🔧 优化：README 图片路径改为 GitHub 绝对 URL

### v0.4.0
- 🔧 优化：仓库重命名为 JavdbBuddy，更新所有链接地址

### v0.3.0
- ✨ 新增：短评查看功能（列表页 📝 按钮）
- ✨ 新增：返回顶部/底部浮动按钮
- ✨ 新增：预览图/磁力链弹窗集成演员名单
- 🔧 优化：JAVDB/JAVBUS 磁力链缓存加速
- 🎨 优化：列表页按钮自适应布局

### v0.2.0
- ✨ 新增：JAVDB + JAVBUS 双标签磁力链弹窗
- ✨ 新增：详情页双标签磁力链
- 🔧 优化：磁力链数据解析兼容性

### v0.1.0
- 🎉 首个版本发布
- ✨ 基本 Emby 入库状态显示
- ✨ 预览图查看功能
- ✨ 多站点搜索功能
