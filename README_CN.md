# BugX Kimi 插件

[![Release](https://img.shields.io/github/v/release/Bencibr/bugx-kimi-plugin?color=blue)](https://github/Bencibr/bugx-kimi-plugin/releases)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

面向 **Kimi Code CLI** 与 **Kimi Work** 的 BugX 官方插件。

将本地优先、具备 PoC 验证与覆盖账本的 AI 代码审计智能体无缝集成至 Kimi Code。

## 功能特性

- **自主代码审计**：深度遍历代码库，精准挖掘业务逻辑漏洞与安全隐患。
- **可复现 PoC 验证**：为确认的缺陷自动编写可复现的验证脚本，先证实再修复。
- **MCP 深度协议协同**：无缝挂载 `bugx-supervisor` 与 `bugx-docs` MCP 服务。

## 安装指南

### 前置条件

安装 BugX CLI 工具：

```bash
npm install -g @bugx/cli
# 或使用 pip：
pip install bugx
```

### 在 Kimi Code CLI 中安装

通过 GitHub 直接安装：

```bash
kimi plugin install https://github.com/Bencibr/bugx-kimi-plugin/archive/refs/heads/main.zip
```

或在 Kimi 交互界面执行：

```text
/plugins install https://github.com/Bencibr/bugx-kimi-plugin
```

## 使用方法

在项目目录下启动 Kimi Code：

```bash
kimi
```

呼叫 BugX 智能体执行审计：

```text
@bugx 审计本项目中的用户权限与敏感数据处理链路。
```

## 许可证

MIT License。详情见 [LICENSE](LICENSE)。
