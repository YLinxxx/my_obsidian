# LLM 知识 Wiki

## 通俗总结

LLM 知识 Wiki 指的是：由 agent 持续维护的 markdown 知识库。每当有新资料或新问题出现，知识库都会被增量更新，而不是每次从零开始检索。

## 核心模式

与其每次提问都重新从原始文档里搜索，不如把知识分层维护：

- 原始资料保留在 `raw/`
- 结构化知识沉淀在 `wiki/`
- 通过 `index.md` 导航
- 通过 `log.md` 追踪演化历史

## 为什么有用

- 知识会随着时间不断累积
- 交叉引用不会丢
- 冲突或版本变化更容易被记录
- 有价值的回答会留在 vault 中，而不是消失在聊天里

## 它怎样帮助这个 Vault

这种模式很适合：

- Node.js 学习笔记
- AI 与 LLM 研究笔记
- 长期概念积累
- 与项目实践联动的学习

## 来源

- [[wiki/sources/2026-06-17-llm-wiki-method|LLM Wiki 方法总结]]

## 相关

- [[index]]
- [[learning-records/current-focus|当前重点]]
