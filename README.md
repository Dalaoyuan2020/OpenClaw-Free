# 🦞 5 分钟快速获得你的专属 OpenClaw！手把手保姆级教程

> 🎉 **前言**：本文将手把手教你如何免费白嫖腾讯云 VPS，并一键部署 OpenClaw！跟着下面的步骤走，5 分钟就能搞定！

---

## 📋 课前准备

- ✅ 微信账号（用于加群领福利）
- ✅ 可用邮箱（腾讯云注册）
- ✅ 5 分钟时间

---

## 🚀 完整教程（点击进入）

### 第一步：注册腾讯云 CodeBuddy

> 🔗 **详细步骤**：https://www.codebuddy.ai/promotion/?ref=chlw5oeiah

**简要流程：**
1. 打开上方链接，注册账号（可用邮箱或微信）
2. 输入 `help` 激活，领取红包封面 🎁

> 💡 这步很简单，1 分钟搞定！

---

### 第二步：领取免费 VPS

> 🔗 **详细步骤**：https://www.codebuddy.ai/promotion/?ref=chlw5oeiah

**简要流程：**
1. 完成简单任务后，进入领取页面
2. 选择服务器节点：
   - 🇨🇳 **北京** - 适合北方用户
   - 🇨🇳 **上海** - 适合南方用户
   - 🇨🇳 **广州** - 适合华南用户
   - 🇸🇬 **新加坡** - 选这个是因为 OpenClaw 分海内外版（见下方说明）

> 📌 **海内外版区别**：
> - **国内版**：使用国内模型（推荐 MiniMax）
> - **海外版**：使用国外模型（需要选新加坡节点）
> - 两个版本功能一样，看你需求选择！

> ⚠️ **注意**：CodeBuddy 活跃满 7 天，可再送 2 个月免费时长！

![免费领取 VPS](tutorial-images/01-vps-claim.jpg)

---

### 选做：完成贪吃蛇任务

> 🔗 **详细步骤**：https://www.codebuddy.ai/promotion/?ref=chlw5oeiah

这是为了熟悉部署流程，可做可不做～

---

### 第三步：重置 VPS，安装 OpenClaw 镜像

> 🔗 **详细步骤**：https://cloud.tencent.com/developer/article/2626151（见「重置镜像」部分）

**简要流程：**
1. 腾讯云控制台找到你的 VPS
2. 更多 → 重置镜像 → 选 OpenClaw 镜像
3. 等待安装完成（2-3 分钟）

![VPS 重置页面](tutorial-images/02-vps-reset.jpg)

---

### 第四步：配置 OpenClaw

> 🔗 **详细步骤**：https://cloud.tencent.com/developer/article/2626151（见「配置 OpenClaw」部分）

**简要流程：**
1. SSH 连接 VPS：`ssh root@你的IP`
2. 配置 API Key（见下方避坑指南）
3. 启动服务：`moltserv start`

> 📌 API Key 推荐用 **MiniMax**，性价比高！需要邀请码可加群获取～

---

### 第五步：接入飞书（可选）

> 🔗 **详细步骤**：https://cloud.tencent.com/developer/article/2626151（见「飞书接入」部分）

**简要流程：**
1. 飞书开放平台创建应用
2. 配置权限（发消息、收消息、群聊管理）
3. 获取 App ID + Secret
4. 配置到 OpenClaw，发布应用

> 💡 新版 OpenClaw 接入飞书超简单，按教程走就行！

---

## ⚠️ 重要避坑指南

### 坑1：API Key 决定 Agent 智商！
- ❌ 不要用免费 Key（不稳定、限制多）
- ✅ 用 MiniMax 或硅基流动等正规军
- 📌 不会配？让聪明的 AI 助手帮你配！

### 坑2：记得备份！
- ✅ 配置文件 `config.yaml` 要备份
- ✅ 记忆文件 `memory/` 目录要备份
- 📌 不会备份？让 AI 助手帮你：`tar -czvf backup.tar.gz /opt/moltbot/`

### 坑3：CodeBuddy 要活跃！
- 📌 CodeBuddy 活跃满 7 天，可再送 2 个月免费时长！
- 💡 记得保持活跃，续费免费时长！

---

## ❓ 常见问题

| 问题 | 答案 |
|------|------|
| VPS 领了不用会怎样？ | CodeBuddy 活跃满 7 天可续 2 个月，记得保持活跃！ |
| API Key 在哪买？ | 加群，群里分享 MiniMax 邀请码！ |
| 飞书接入失败？ | 检查 App ID/Secret 对不对，群里求助～ |
| 连接不上 VPS？ | 检查 IP 对不对，防火墙开了没 |

---

## 📬 加群交流

有任何问题，欢迎加群！

![微信群二维码](tutorial-images/wechat-group-qr.jpg)

---

## 🎉 祝大家玩得愉快！

> 🦞 **ClawNexus — Join the ClawRush**

---

*有问题？加群问！*
