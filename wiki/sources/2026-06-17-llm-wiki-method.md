# LLM Wiki 方法总结

## 来源

- 本地文件：`llm-wiki.md`
- 主题：AI 辅助的持续型个人知识库

## 总结

这份资料提出了一种模式：不要只在提问时临时从原始文档里检索，而是让 LLM 持续维护一个可增长的 wiki。

它的核心结构分为三层：

1. 原始资料
2. 持续维护的 wiki
3. 用来规范 agent 行为的 schema 或说明文件

## 主要观点

- 持续型 wiki 会让知识随着时间复利增长
- agent 应该把新资料整合进已有页面，而不是每次都从零回答
- 有价值的 query 结果通常应该写回 wiki
- 定期 lint 能帮助知识库保持健康

## 对当前 Vault 的直接启发

- 用 `AGENTS.md` 作为 schema 和工作流定义
- 让 raw 来源材料和整理后的知识分层存放
- 把 `index.md` 和 `log.md` 当作主导航与主时间线
- 让长期有价值的答案沉淀进 vault，而不是只存在聊天里

## 由这份资料触发的动作

- 创建了初始 vault 结构
- 创建了高层总览页
- 创建了 Node.js 与 AI 学习的起步概念页

## 相关

- [[wiki/concepts/llm-knowledge-wiki|LLM 知识 Wiki]]
- [[wiki/overviews/nodejs-backend-overview|Node.js 后端总览]]
- [[wiki/overviews/ai-llm-overview|AI 与 LLM 总览]]
