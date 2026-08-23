---
name: qtfycg-skills
description: 根据用户目标、项目上下文和任务类型，自动识别当前软件生命周期阶段，选择并组合需求分析、架构设计、数据库设计、API 设计、后端开发、前端与跨端开发、软件质量、DevOps 和工程文档等专业 Skill，协调从需求、设计、开发、测试到部署、运维和持续演进的完整软件工程流程，并负责最终结果的验证与交付。
version: 1.0.0

# qtfycg-skills

### 1、定位
根据用户目标、项目上下文、任务类型和当前软件生命周期阶段，确定需要使用的专业 Skill，并协调多个 Skill 按合理顺序完成软件工程任务。

### 2、核心职责

* 理解用户目标
* 获取并分析项目上下文
* 判断任务类型与任务规模
* 判断当前软件生命周期阶段
* 分析修改影响范围
* 选择需要使用的专业 Skill
* 编排多个 Skill 的执行顺序
* 控制跨领域开发流程
* 验证实现结果
* 判断任务是否达到完成标准
* 形成最终工程交付闭环

## 3、技能列表

* [需求分析](./references/requirement/SKILL.md)
* [架构设计](./references/architecture/SKILL.md)
* [数据库设计](./references/database/SKILL.md)
* [API 设计](./references/api/SKILL.md)
* [后端开发](./references/backend/SKILL.md)
* [前端与跨端开发](./references/frontend/SKILL.md)
* [软件质量](./references/quality/SKILL.md)
* [DevOps](./references/devops/SKILL.md)
* [工程文档](./references/documentation/SKILL.md)

### 4、组合原则
* 专业skill可以独立使用
* 一个任务可同时涉及多个专业skill
* 仅选择完成当前任务所必须的skill，不为了流程完整而调用无关skill
* 工程文档属于横向能力，可根据需要参与软件生命周期的任意阶段
* 整个开发流程的总调度由qtfycg-skills负责，专业skill只需关注自身职责范围内的任务

### 5、核心原则
遵循以下基本流程：
![alt text](./resource/基本流程.png)
