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



## 文件列表

| 文件 | 功能 |
|------|------|
| pomodoro.html | 番茄钟，25分钟工作/5分钟休息 |
| 2048.html | 2048 数字滑动游戏 |
| calculator.html | 计算器 |
| refraction.html | 折射演示 |
