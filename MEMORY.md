# MEMORY.md - 长期记忆

## 关于用户
- **姓名**：简小白
- **工作盘**：`D:\!works`
- **备份路径**：`D:\!works\backups`（daily/weekly/manual）
- **时区**：Asia/Shanghai
- 重视独立思考，接受反对意见
- 不接受手动操作，期望 AI 自动完成
- **优先使用内网解决方案**（用户偏好）
- 要先搞清楚中心思想再解决需求

## 关于我
- **身份**：OpenClaw AI 助手，名字还没定
- **创建时间**：2026-03-31（第一次会话）
- 风格：直接、有观点、不拍马屁
- **工作方式**：主动思考，不只是回答问题

## 工作原则（用户核心期望）
- **主动思考**：不只回答问题，要主动帮用户想问题
- **想用户没想到的**：用户缺什么我要主动发现和提出
- **想在前面**：主动规划、主动提醒、主动建议
- **不等着被问**：有问题要主动说，而不是等用户来问

## 技术配置
- **默认模型**：`minimax-portal/MiniMax-M2.7`
- **当前会话模型**：`nvidia/qwen/qwen3.5-122b-a10b`（2026-04-05 确认正在使用）
- **可用模型**：
  - `nvidia/qwen/qwen3.5-122b-a10b` (NVIDIA，当前在用)
  - `minimax/MiniMax-M2.7` (MiniMax，可用)
  - `microsoft/phi-3.5-vision-instruct` (NVIDIA，视觉模型，2026-04-06 新增)
- **已移除**：Siliconflow 配置（2026-04-03 发现所有模型返回 403/401 认证失败，已清理）
- **Telegram bot token**：`8220940804:AAEdm-OrRdvqIBU889nDpIFIr5piARU2VyA`
- **插件**：@openclaw/telegram（手动配置，因 ClawHub 限流）

## 已知问题
- **webchat 界面卡住**：原因不明，2026-04-03 排查过，需进一步调查
- **Telegram 回复失败**：真正原因是 Siliconflow API key 认证失败，所有模型返回 403
- **网络搜索历史故障**：2026-03-31 首次发现，建议过切到国内模型
- **知乎自动验证**：知乎对自动化访问有严格检测，需手动完成验证码（2026-04-06 确认）

## 重要决策
- 2026-04-03：彻底移除 minimax 配置后又还原，用户希望继续使用 minimax 2.7
- 2026-04-03：修复死循环——唯一消息 ID 机制 + 单次执行原则
- 2026-04-06：配置 Microsoft Phi-3.5-Vision 视觉模型，成功实现截图 OCR 识别 K 线数据
- 2026-04-06：创建 GitHub 仓库 `bowen987456/works-backup`，备份工作区配置和记忆文件
- 2026-04-06：安装 154 个 AgentCrow agents（全局可用）

## Telegram 配置
- **Bot username**：@jianxiaobai_bot
- **Bot token**：8220940804:AAEdm-OrRdvqIBU889nDpIFIr5piARU2VyA
- **用户 chat_id**：8196943566
- 已测试发消息成功（2026-04-03 18:22）

## 变现项目
- **方向**：帮人写商业计划书
- **模式**：用户接单 → 我写内容 → 用户交付
- **定价**：300-1000 元/份
- **已准备素材**：`D:\!works\内容素材\`
- **状态**：待用户注册平台测试

## 待完成/跟进
- 调查 webchat 界面卡住问题
- **长期项目**：OpenClaw 多节点架构部署（Gateway + Node）
- **主要沟通渠道**：Telegram（@jianxiaobai_bot）

## ClawdChat 账号
- **用户名**：jishuzhushou
- **显示名**：简小白专属助手
- **序号**：第 3374 位成员
- **API Key**：保存在 `C:\Users\Administrator\.clawdchat\credentials.json`
- **认领链接**：https://clawdchat.ai/cl/GETGxROJ
- **账号状态**：已认领

---
## 2026-04-06 晚间日报
**完成事项：**
- ✅ 配置 Microsoft Phi-3.5-Vision 视觉模型，成功识别 K 线截图数据
- ✅ 创建 GitHub 仓库并备份工作区配置
- ✅ 安装 154 个 AgentCrow agents
- ✅ 安装 win-mouse-native 技能（Windows 鼠标模拟）
- ✅ 配置 GitHub CLI 并创建个人仓库

**阻塞事项：**
- ⚠️ 知乎自动验证问题（需手动完成验证码）
- ⚠️ webchat 界面卡住问题（待进一步调查）

**明日重点：**
- 测试视觉模型自动评分 K 线趋势功能
- 探索知乎验证码绕过方案（或等待用户手动验证后继续）
- 整理技能库，清理临时文件

HEARTBEAT_OK
