<p align="center">
  <img src="./assets/hero-geek.webp" width="100%" alt="sep-zxy：Agent Systems、知识检索与开发者工具。" />
</p>

<p align="center">
  <strong>AI Engineer · Agent Systems · Knowledge Engineering</strong><br />
  <sub>关注 Agent 的执行语义、上下文组织，以及知识如何被构建、检索和持续更新。</sub>
</p>

<p align="center">
  <a href="#focus">技术方向</a> ·
  <a href="#engineering-notes">工程判断</a> ·
  <a href="#open-source">开源作品</a> ·
  <a href="mailto:1583701031@qq.com">联系我</a>
</p>

我是zxy，主要构建 **有状态的 Agent 应用与可追溯的知识系统**。实践覆盖工具协议、上下文与记忆、混合检索和持久化任务执行，也开发 Local-first 应用与自动化工具。

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&amp;logo=python&amp;logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&amp;logo=typescript&amp;logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&amp;logo=react&amp;logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&amp;logo=fastapi&amp;logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&amp;logo=postgresql&amp;logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Rust-383838?style=flat-square&amp;logo=rust&amp;logoColor=white" alt="Rust" />
  <img src="https://img.shields.io/badge/Tauri-24C8D8?style=flat-square&amp;logo=tauri&amp;logoColor=111111" alt="Tauri" />
</p>

### Focus

**Agent Systems & Tooling**

`Tool Calling` · `Tool Contracts` · `Structured Outputs` · `Stateful Sessions`

围绕模型与业务系统之间的执行层，设计工具参数契约、身份与动作校验、结构化结果和多轮任务状态，让一次对话能够继续查询、补充条件并调用真实业务能力。

**Context & Memory**

`Context Engineering` · `Context Assembly` · `Session Memory` · `Summarization`

组织页面上下文、近期对话、摘要、结构化事实和用户状态，处理跨角色记忆、历史恢复与上下文裁剪，保留信息来源和身份边界。

**Retrieval & Knowledge Engineering**

`Hybrid Search` · `RRF` · `Reranking` · `Provenance` · `Knowledge Pipelines`

将原始材料加工为证据、特点关系、Wiki 正文与检索索引，融合向量、文字及关系信号，结合结构化条件完成召回与重排。关注来源引用、冲突信息、版本演进，以及检索结果的解释依据。

**Reliable Execution**

`Idempotency` · `Worker Leases` · `Version Fencing` · `Backpressure` · `Recovery`

围绕任务持久化、租约和执行版本设计取消、重试与恢复；通过幂等、受控写入、负载感知调度和预算预扣，约束重复副作用与过期结果提交。

### Engineering Notes

- **工具契约决定执行边界。** 参数、身份、实体和允许执行的动作由服务端核验；历史结果在执行前重新检查当前条件。
- **取消是执行状态的变化。** Worker 重试或任务被替换后，旧执行需要失去提交资格；租约与版本校验共同约束结果写入。
- **来源属于知识模型。** 正文、证据、特点关系和向量索引各自承担明确职责；结论能回到原始片段，修订保留版本与冲突。
- **模型判断与数据变更分离。** 模型只读查证，结构化决定交由执行器校验；低把握结果补证复判，重要变更保留人工确认、快照与撤回入口。

### Open Source

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/sep-zxy/zhizhi"><img src="./assets/project-zhizhi.svg" width="48" height="48" alt="知枝 · Zhizhi图标" /></a><br />
      <strong><a href="https://github.com/sep-zxy/zhizhi">知枝 · Zhizhi</a></strong><br />
      <p>从 Git 与代码证据提炼知识，经过理解练习沉淀到 Obsidian。</p>
      <sub>Python · React · Electron</sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/sep-zxy/zhizhi-next"><img src="./assets/project-zhizhi-next.svg" width="48" height="48" alt="知枝 Next图标" /></a><br />
      <strong><a href="https://github.com/sep-zxy/zhizhi-next">知枝 Next</a></strong><br />
      <p>连接材料、项目实践与知识 Wiki，探索有依据的知识关联。开发中。</p>
      <sub>Knowledge Systems · Local-first</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/sep-zxy/game-mode-rust"><img src="./assets/project-gamemode.svg" width="48" height="48" alt="GameMode Switcher图标" /></a><br />
      <strong><a href="https://github.com/sep-zxy/game-mode-rust">GameMode Switcher</a></strong><br />
      <p>用场景预设编排应用启停、代理切换和环境恢复。</p>
      <sub>Rust · Tauri · Windows</sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/sep-zxy/Auto-login-on-campus-network"><img src="./assets/project-portal.svg" width="48" height="48" alt="校园网认证自动化图标" /></a><br />
      <strong><a href="https://github.com/sep-zxy/Auto-login-on-campus-network">校园网认证自动化</a></strong><br />
      <p>用无头浏览器编排 Portal 状态检测、表单填充与后台登录。</p>
      <sub>Python · Playwright · AutoHotkey</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/sep-zxy/Better-CE-Switch"><img src="./assets/project-ime.svg" width="48" height="48" alt="Better-CE-Switch图标" /></a><br />
      <strong><a href="https://github.com/sep-zxy/Better-CE-Switch">Better-CE-Switch</a></strong><br />
      <p>通过快捷键和超时回切，管理中英文输入法。</p>
      <sub>AutoHotkey · Automation</sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/sep-zxy?tab=repositories"><img src="./assets/project-more.svg" width="48" height="48" alt="更多公开代码图标" /></a><br />
      <strong><a href="https://github.com/sep-zxy?tab=repositories">更多公开代码</a></strong><br />
      <p>查看其他开源工具、实验与持续迭代的项目。</p>
      <sub>Repositories</sub>
    </td>
  </tr>
</table>

<sub>知枝基于 AhaDiff 继续开发，保留上游署名与许可证。</sub>

---

<p align="center">
  <samp>Agent Systems / Context / Retrieval / Knowledge</samp><br />
  <a href="mailto:1583701031@qq.com">1583701031@qq.com</a>
</p>
