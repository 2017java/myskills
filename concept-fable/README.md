# Concept Fable

用寓言故事学概念。

## 它做什么

你告诉它想学什么，它讲一个故事。故事里没有专业术语，读到最后才揭晓概念。之后给隐喻对照表，还会告诉你"这个隐喻没覆盖什么"。

## 怎么用

```
我想学博弈论
用武侠风格讲囚徒困境
用 concept-fable 讲解纳什均衡
只要故事，不要解析
```

## 流程

1. 确定概念（不暴露名称）
2. 写故事（内部选钩子/引擎/技法，对外只说风格）
3. 展示故事（纯文本流式输出）
4. 猜谜（揭晓前问用户想不想猜）
5. 解析（揭晓 + 定义 + 对照表 + 边界 + 重要性）
6. 交互（深度追问 / 反向创作 / 跨概念串联）

## 目录

```
concept-fable/
├── SKILL.md              # 核心流程
├── README.md
├── LICENSE
├── references/
│   ├── writing-techniques.md   # 6种开篇钩子 + 6种故事引擎 + 6种写作技法
│   └── html-template.md        # HTML模板（可选，用户要求时生成）
└── examples/
    └── concept-fable-demo.md   # 完整对话记录
```

## 安装

复制到 TRAE SOLO 的 skills 目录：

- Windows: `%USERPROFILE%\.trae-cn\skills\concept-fable\`
- macOS/Linux: `~/.trae-cn/skills/concept-fable/`

## 真实案例

**输入**：`我要学习agent`

**故事**：《第三把钥匙》——一个维护员守着"看、想、动"三把钥匙的科幻故事。

**猜谜**：用户猜"agent的感知-决策-行动模式" → 猜对了。

**解析**：三把钥匙分别对应感知模块、决策模块、行动模块。"卡住是自由的一部分"对应独立性的代价。

完整对话记录见 `examples/concept-fable-demo.md`。

## 来源

基于 Amanda Askell 的 AI 辅助深度学习方法论。

## 许可

MIT
