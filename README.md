# Web-to-Skills Agent Profile

[中文](#中文说明) | [English](#english)

---

## 中文说明

### 项目简介
这是一个用于“从 Web 能力生成 Skills”的 Agent 自述文件（Profile）。
核心目的是把网页侧能力沉淀为可调用、可复用、可测试的 Skills 产物。



### 工作流来源
本项目工作流借鉴了：
- https://github.com/UfoMiao/zcf

### 设计目标
1. 将 Web 行为与网页能力转化为可调用 Skill
2. 坚持“先证据后实现”（先确认官方 SDK/API 文档）
3. 按接口粒度推进计划、开发、测试与确认
4. 统一产物结构，便于后续集成与自动化调用

### 核心工作流（6 阶段）
1. 研究（Research）
2. 构思（Ideation）
3. 计划（Planning）
4. 执行（Execution）
5. 优化（Optimization）
6. 评审（Review）

### 快速开始
1. 阅读并按需调整 `web-to-skills.md` 中的规则
2. 将该 Agent 配置到你的开发环境/编排系统
3. 在任务输入中提供：`target_url`、`user_goal`、`auth_info`（可选）
4. 按流程执行并输出标准化结果（implementation_path、interface_plan、test_results 等）

### 推荐目录结构
```text
.
├─ web-to-skills.md
├─ README.md
└─ LICENSE
```

### 仓库内容
- `web-to-skills.md`：Agent 规则与执行规范
- `README.md`：中英双语说明
- `LICENSE`：MIT 协议

### 协议
本项目使用 **MIT License**。

---

## English

### Overview
This repository contains an agent profile for turning web capabilities into callable skills.
Its primary goal is to produce executable, reusable, and testable skill artifacts.



### Workflow Inspiration
The workflow is inspired by:
- https://github.com/UfoMiao/zcf

### Design Goals
1. Convert web capabilities into callable skills
2. Follow evidence-first implementation (confirm official SDK/API docs first)
3. Execute planning/build/testing/confirmation at per-interface granularity
4. Keep a standardized artifact structure for integration and automation

### Core Workflow (6 Stages)
1. Research
2. Ideation
3. Planning
4. Execution
5. Optimization
6. Review

### Quick Start
1. Read and adjust rules in `web-to-skills.md`
2. Load this agent profile into your runtime/orchestration setup
3. Provide task inputs: `target_url`, `user_goal`, and optional `auth_info`
4. Execute the workflow and return standardized outputs (implementation_path, interface_plan, test_results, etc.)

### Suggested Repository Layout
```text
.
├─ web-to-skills.md
├─ README.md
└─ LICENSE
```

### Repository Contents
- `web-to-skills.md`: agent rules and execution specification
- `README.md`: bilingual documentation
- `LICENSE`: MIT license

### License
This project is licensed under the **MIT License**.
