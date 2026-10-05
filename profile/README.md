<div align="center">
  <img src="https://raw.githubusercontent.com/AniaBot-Project/AniaBot/main/README/logo.webp" width="160" alt="AniaBot Logo"/>
  <h1>AniaBot</h1>
  <p>一个插件驱动型多平台机器人框架</p>
  <p>
    <a href="https://aniabot-project.github.io/AniaBot/">📖 文档</a> ·
    <a href="https://github.com/AniaBot-Project/AniaBot">主仓库</a> ·
    <a href="https://github.com/AniaBot-Project/AniaBot-Plugins">插件仓库</a>
  </p>
</div>

## 关于

**AniaBot** 是一个基于 Go 开发的高性能、插件驱动型**多平台**机器人框架，内置 AI Agent 能力（LLM 对话 / MCP / 技能 / 定时任务），让开发者能够快速构建功能强大的机器人应用。

- **多平台**：QQ（NapCat / LLBot，OneBot v11）、微信、飞书、Telegram、Discord；新增平台只需实现一个适配器并注册，框架核心零改动
- **插件系统**：完整的插件生命周期与依赖注入，官方插件市场支持面板在线安装 / 升级 / 卸载（自动编译并重启）
- **AI 能力**：支持三种 LLM API 格式（OpenAI Chat Completions / Responses、Anthropic Messages），内置工具调用、MCP、长期记忆、子代理与定时任务
- **开箱即用**：Web 控制面板图形化配置（配置持久化在数据库），内置 AI 对话、复读机、每日新闻等插件

## 仓库

| 仓库 | 说明 |
| --- | --- |
| [AniaBot](https://github.com/AniaBot-Project/AniaBot) | 框架主仓库：核心、平台适配器、内置插件、Web 控制面板 |
| [AniaBot-Plugins](https://github.com/AniaBot-Project/AniaBot-Plugins) | 官方插件市场：浏览 / 安装第三方插件，欢迎 PR 提交 |
| [文档站](https://aniabot-project.github.io/AniaBot/) | 使用指南、插件开发教程、API 参考与技术原理 |

## 参与贡献

欢迎提交 Issue 和 Pull Request。想开发插件请先阅读[插件开发文档](https://aniabot-project.github.io/AniaBot/plugin/overview)，写好后到 [AniaBot-Plugins](https://github.com/AniaBot-Project/AniaBot-Plugins) 提交 PR 即可发布到插件市场。
