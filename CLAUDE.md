# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## 项目概况

纯 HTML/CSS/JS 单页面工具集合，每个 HTML 文件独立运行，零依赖，双击即可在浏览器打开。

## 技术约束

- 每个文件必须自包含（CSS/JS 内嵌在 HTML 内），不可引入外部依赖
- 只修改用户指定的文件，不要跨文件重构

## Git 版本规范

- 提交信息风格：简洁中文，如 `V3: 修复番茄钟暂停bug`
- 版本标签格式：`V{序号}-{YYYYMMDD}-{HHMM}`，如 `V3-20260521-1430`
- 请勿提交 `.claude/` 目录下的个人配置、记忆文件到版本库

### 版本号规则

- **本地提交（未推送）**：使用小数版本，基于当前大版本递增，如 `V3.1`、`V3.2`、`V4.1`
- **推送远端**：在用户明确要求推送并指定升级大版本号（如"推到 V4"）后，才打大版本标签 `V{整数}-{时间戳}`
- 用户未明确要求推送时，默认只在本地保存，不打远端标签



## 文件列表

| 文件 | 功能 |
|------|------|
| pomodoro.html | 番茄钟，25分钟工作/5分钟休息 |
| 2048.html | 2048 数字滑动游戏 |
| calculator.html | 计算器 |
| refraction.html | 折射演示 |
