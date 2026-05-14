# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## 工作区概览

这是一个多项目工作区（workspace root），CLI 工具在任意子目录执行时会自动载入对应目录的 CLAUDE.md，无需手动指定。

| 目录 | 用途 |
|------|------|
| `active/` | 活跃项目，当前在开发 |
| `archive/` | 已完成或暂停的项目，保留代码参考 |
| `experiments/` | 实验、原型、探索性代码 |
| `templates/` | 项目模板、配置模板 |
| `agents/` | 自定义 Agent、Workflow 定义、MCP 配置 |
| `snippets/` | 跨项目可复用的代码片段 |
| `learning/` | 学习笔记 |
| `assets/` | 图片、素材等静态资源 |
| `memory/` | 跨会话持久记忆（用户偏好、项目上下文、反馈） |

## 用户偏好

- 主要语言：Python，但也用 Go、TypeScript 等，根据项目选最合适的
- 项目类型不限：全栈 Web、后端 API、AI/ML、脚本工具等
- 偏好务实方案，不做过早抽象，不过度设计

## 新项目初始化

在 `active/` 下创建项目目录时，复制 `templates/project/CLAUDE.md` 作为起点，然后根据项目实际情况填充。
