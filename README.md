# 🎯 Token池 - Augment OAuth 凭证管理插件

<div align="center">

![Token池](https://img.shields.io/badge/Token池-v1.1.0-blue.svg)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ%20IDEA-2023.1+-orange.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![QQ群](https://img.shields.io/badge/QQ群-1017212982-red.svg)

**一个专业的 Augment OAuth 凭证管理插件，提供无感换号、Token池管理等强大功能**

[📥 快速安装](#-快速安装) • [🎯 核心功能](#-核心功能) • [🌐 生态系统](#-完整生态系统) • [💬 技术支持](#-技术支持)

</div>

---

## 🌐 完整生态系统

Token池插件是 Augment 开发生态系统的重要组成部分，与以下平台完美配合：

### 🔗 核心平台

| 平台 | 地址 | 功能描述 |
|------|------|----------|
| 🎯 **Token池管理平台** | [augment.184772.xyz](https://augment.184772.xyz) | Token池管理、用户认证、API服务 |
| 📧 **Go-Email邮箱服务** | [gomail.184772.xyz](https://gomail.184772.xyz) | 临时邮箱、邮件接收、验证码获取 |
| 🔧 **IDEA插件** | 本插件 | 无感换号、凭证管理、自动切换 |

### 🔄 工作流程

```
┌─────────────────┐    ┌─────────────────┐    ┌─────────────────┐
│   Go-Email      │    │   Token池       │    │   IDEA插件      │
│   邮箱服务      │───▶│   管理平台      │───▶│   无感换号      │
│                 │    │                 │    │                 │
```
---

## 🎯 核心功能

### ✨ 主要特性

- **🔐 Personal Token管理** - 验证和管理个人Token，确保凭证有效性
- **🎯 无感换号** - 一键自动获取最优Token，智能选择使用次数最少的可用凭证
- **⚙️ Session ID修改** - 实时修改和更新Session ID，无需重启IDEA
- **🔄 免重启更新** - 动态更新凭证，提升开发效率
- **📊 Token池统计** - 实时显示Token池状态和使用情况
- **🛡️ 智能检测** - 自动检测Token状态，智能切换到可用凭证

### 🎨 界面预览

- 简洁直观的图形化管理界面
- 实时状态显示和操作反馈
- 一键操作，简化使用流程

---

## 📥 快速安装
1. 下载最新版本：[GitHub Releases](https://github.com/xn030523/augment-token-idea/releases)
2. `File → Settings → Plugins → ⚙️ → Install Plugin from Disk...`
3. 选择下载的zip文件并安装

> 📖 详细安装指南请参考：[INSTALL.md](./INSTALL.md)

---

## 🚀 快速开始

### 第一步：准备工作

1. **获取临时邮箱**
   - 访问 [gomail.184772.xyz](https://gomail.184772.xyz)
   - 获取临时邮箱地址用于注册

2. **注册Augment账号**
   - 使用临时邮箱注册Augment账号
   - 完成邮箱验证

3. **获取Personal Token**
   - 登录 [augment.184772.xyz](https://augment.184772.xyz)
   - 在个人设置中生成Personal Token

### 第二步：插件配置

1. **打开插件设置**
   ```
   File → Settings → Tools → Token池
   ```

2. **配置Personal Token**
   - 输入从管理平台获取的Personal Token
   - 点击"验证Token"确认有效性

3. **开始使用**
   - 使用"无感换号"功能自动获取最优凭证
   - 享受无缝的开发体验

---

## 🌟 使用场景

### 👥 团队协作
- 多人共享Token池，避免凭证冲突
- 统一管理团队凭证，提升协作效率

### 🔄 自动化开发
- 自动切换可用凭证，减少手动操作
- 智能检测Token状态，保证开发连续性

### 🛡️ 安全管理
- 集中管理所有凭证，提升安全性
- 实时监控Token使用情况

---

## 🔧 高级功能

### API集成
插件与以下API完美集成：

- **用户信息API**: `/api/user/info?token={token}`
- **Token池API**: `/api/tokens`
- **状态检查**: 实时验证Token有效性

### 智能算法
- **负载均衡**: 智能选择使用次数最少的Token
- **故障转移**: 自动切换到可用凭证
- **状态缓存**: 优化API调用性能

---

## 💬 技术支持

### 🆘 获取帮助

- **QQ技术群**: [1017212982](https://qm.qq.com/cgi-bin/qm/qr?k=xxx) 
- **GitHub Issues**: [提交问题](https://github.com/xn030523/augment-token-idea/issues)
- **邮件支持**: 通过 [gomail.184772.xyz](https://gomail.184772.xyz) 联系

### 📚 相关资源

- **管理平台**: [augment.184772.xyz](https://augment.184772.xyz)
- **邮箱服务**: [gomail.184772.xyz](https://gomail.184772.xyz)
- **插件源码**: [GitHub仓库](https://github.com/xn030523/augment-token-idea-free.git)

### 🐛 问题反馈

遇到问题？请提供以下信息：
- IDEA版本和插件版本
- 错误日志和截图
- 复现步骤

---

## 🔄 更新日志

### v1.1.0 (2025-06-20)
- 🔧 修复Token验证逻辑，正确解析API响应格式
- ✅ 支持"status":"success"响应格式验证
- 📝 更新插件描述，详细说明无感换号功能
- 💬 添加QQ群技术支持信息
- 🎯 完善无感换号功能说明和使用指南

[查看完整更新日志](./CHANGELOG.md)

---



## 👨‍💻 开发者

**xn030523** - *主要开发者*

- GitHub: [@xn030523](https://github.com/xn030523)
- QQ群: 1017212982

---

<div align="center">

**⭐ 如果这个项目对你有帮助，请给个Star支持一下！**

[⬆ 回到顶部](#-token池---augment-oauth-凭证管理插件)

</div>
