# Five-Advisor Review

一个面向观点、方案、选题、决策与商业创意的多视角决策压力测试 Skill。

它不把“多位顾问同意”当作事实，也不把五种角色伪装成五个独立模型。框架要求先形成隔离的首轮判断，再进行匿名互审、共识压力测试，最后由主席给出带验证动作的可逆决策建议。

> 中文优先。English readers can start with the short overview below and the structured documents in `docs/`.

## 它解决什么问题

很多创意审查表面上有多个视角，实际仍在重复同一条推理路径。本项目把审查拆成五种不同的方法：

1. **反驳者**：逆向预演失败机制。
2. **本质追问者**：拆解目标、因果链和未验证假设。
3. **机会发现者**：从相邻场景寻找被忽略的替代路径。
4. **外行人**：从普通人的理解、信任、价格和麻烦成本提出问题。
5. **无情执行者**：找出第一阻塞点，把方案落到今天可完成的验证动作。

随后，框架会检查“共识是否同源”、主动写出最强反驳，并要求主席保留关键异议而不是用多数票压平分歧。

## 快速开始

1. 将 [`skill/`](skill/) 目录复制到你的 Codex Skills 目录，或按你的运行环境导入。
2. 在对话中使用：

   ```text
   使用 $five-advisor-review 审查这个想法：……
   ```

3. 低成本、可逆想法会使用快速模式；中高风险、不可逆或关键事实不明的决策会使用完整模式和验证标准。

完整使用说明见 [`skill/SKILL.md`](skill/SKILL.md)。

## 目录

```text
.
├── skill/                    # 可安装的 Skill 本体
│   ├── SKILL.md
│   ├── agents/openai.yaml
│   └── assets/report-template.html
├── docs/
│   ├── methodology.md         # 方法论与流程
│   └── core-design.md         # 核心设计、护栏与局限
├── examples/
│   └── b2b-pricing.md         # 完整模式的输入/输出骨架
└── CONTRIBUTING.md
```

## 核心原则

- **共识不是证据。** 多个视角的同意，只提高关注优先级；验证才提高可信度。
- **未知要显式写出。** 不能核验的数据、案例和基准率必须标为未知，不能用看似专业的数字填补。
- **实验阈值不是行业标准。** 未经来源验证的数值必须标为 `[实验阈值]`，并说明它服务的风险控制目的。
- **不伪造独立性。** 同一模型生成的五种视角是程序性隔离，不是多模型证据。
- **先可逆，再下注。** 高风险或不可逆决策的第一步应是验证或风险隔离。

## 适用与不适用

适用：商业模式、产品方案、内容选题、战略选择、架构取舍、研究假设和资源分配。

不适用：单一事实问答、纯翻译、纯创作、没有真实权衡的问题，以及已经明确授权的直接执行任务。

## 英文概览

Five-Advisor Review is a structured decision stress-test. It separates five reasoning methods, anonymizes peer review, tests whether consensus comes from one shared assumption, and requires an evidence-backed, reversible next step. It is not a voting system and does not claim that role prompts are independent models.

## 贡献

欢迎补充案例、评测、失败模式和改进建议。请先阅读 [贡献指南](CONTRIBUTING.md)，尤其不要用编造的市场数据、伪精确阈值或“多角色共识”替代真实证据。

## 许可

本项目采用 [MIT License](LICENSE)，允许学习、研究、复用、修改和再发布。
