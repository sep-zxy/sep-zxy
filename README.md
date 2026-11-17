<div align="center">

# 周鑫宇 · sep-zxy

**AI 应用开发 · 数据工程实践 · 全栈产品交付**

把真实需求拆成清晰的数据、规则和交互，再做成可以使用的软件。

[知枝](https://github.com/sep-zxy/zhizhi) · [GameMode Switcher](https://github.com/sep-zxy/game-mode-rust) · [邮件联系](mailto:1583701031@qq.com)

</div>

---

### 我在做什么

我关注 LLM 应用、结构化数据和开发者工具，做过简历优化智能体、校园餐饮小程序、Windows 自动化工具和 Flutter 移动应用。

我习惯沿着一条完整链路解决问题：**理解需求 → 数据建模 → 核心逻辑 → 产品交互 → 部署交付**。在 AI 功能中，尤其关注输出约束、失败兜底、来源证据，以及用户能否理解和确认结果。

目前持续探索：如何把代码实践和阅读材料，沉淀为可追溯、可持续更新的个人知识。

### 公开代表作

#### [知枝 · Zhizhi](https://github.com/sep-zxy/zhizhi)

**从真实代码实践中提炼知识，经过理解与练习，沉淀到自己的知识 Wiki。**

- 以 Git 提交和代码片段作为来源，串起知识候选、审阅、知识卡、理解练习与 Wiki 草稿。
- 将模型生成接入可审阅的学习流程，保留来源，并由用户确认后写入 Obsidian。
- 使用 React / TypeScript、Electron、Python 和 SQLite，构建本地优先的桌面应用。

基于开源 AhaDiff 继续开发，保留上游署名与许可证。

[源码](https://github.com/sep-zxy/zhizhi) · [安装与构建说明](https://github.com/sep-zxy/zhizhi/blob/main/docs/BUILDING.md) · [使用指南](https://github.com/sep-zxy/zhizhi/blob/main/docs/USER_GUIDE.md)

#### [GameMode Switcher](https://github.com/sep-zxy/game-mode-rust)

**把进入游戏和恢复日常环境时的重复操作，整理成可切换的预设。**

- 从 Python MVP 迭代到 Rust + Tauri v2，拆分核心模型、模式编排服务与 Windows 平台能力。
- 编排应用启动与关闭，记录并恢复 Clash / TUN / 系统代理状态。
- 实现系统托盘、注册表自启和 Windows API 集成，让自动化进入日常使用流程。

`Rust` · `Tauri v2` · `React` · `TypeScript` · `Windows API`

[源码与使用说明](https://github.com/sep-zxy/game-mode-rust)

| 其他公开项目 | 解决的问题 | 技术 |
| --- | --- | --- |
| [校园网自动登录助手](https://github.com/sep-zxy/Auto-login-on-campus-network) | 面向巢湖学院的图形化配置、登录状态检测与开机静默登录 | Python / Playwright / AutoHotkey |
| [Better-CE-Switch](https://github.com/sep-zxy/Better-CE-Switch) | 用快捷键和超时回切减少中英文输入法切换操作 | AutoHotkey |
| [知枝 Next](https://github.com/sep-zxy/zhizhi-next) | 持续探索内容采集、项目实践与个人知识网络的整合，开发中 | 知识工作流 / AI 应用 |

### 简历中的项目实践

**AI 简历优化平台 · 主导开发**

围绕岗位 JD 解析、简历诊断、结构化建议和多版本优化构建工作流。用 zod schema 约束模型输出，处理 JSON 解析、建议归一化和规则兜底；通过修改原因与前后 diff，让用户判断并选择是否应用建议。

`React` · `TypeScript` · `TanStack Start` · `Zustand` · `zod` · `LLM API`

**今天吃什么 · 主导开发**

从食堂点餐页面的数据结构入手，还原门店、菜品、分类、口味和价格模型，完成数据接入、小程序筛选与随机推荐、后台管理，并引入 LLM 标签生成与标准化处理。

`微信小程序` · `Vue` · `Spring Boot` · `MySQL` · `Python` · `Docker`

### 技术如何落到项目里

| 方向 | 实践重点 |
| --- | --- |
| AI 应用 | Prompt 设计、结构化输出校验、规则兜底、工具调用、结果审阅 |
| 数据处理 | 多源字段映射、数据清洗、业务模型重建、标签标准化 |
| Web 产品 | React / TypeScript、Vue、前后端联调、筛选与管理流程 |
| 桌面与自动化 | Python、Playwright、Rust / Tauri、Windows 进程与代理管理 |
| 工程交付 | Git、Docker Compose、构建打包、配置管理与部署 |

<details>
<summary><strong>经历与竞赛</strong></summary>

- **合肥华宇智航 · 自动化工程师助理（2026.01—2026.03）**：参与储能监控平台的数据流转与自动化规则开发，梳理字段语义和映射关系，贯通接口、存储与页面展示。
- **巢湖学院 · 计算机科学与技术本科（2022—2026）**。
- 第九届数维杯大学生数学建模挑战赛：全国第七名。
- 安徽省计算机博弈大赛：省级一等奖。
- 第 16 届中国大学生计算机设计大赛：国家级三等奖。
- 2023 高教社杯全国大学生数学建模竞赛：省级二等奖。

</details>

---

欢迎交流 **LLM 应用、开发者工具、知识管理与自动化**，也欢迎在项目中提交 Issue 或 PR。
