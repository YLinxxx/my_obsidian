# 事件循环

## 通俗总结

事件循环（event loop）是 Node.js 能在不让主线程一直卡住的前提下，同时处理很多等待型任务的关键机制。

## 为什么重要

理解事件循环，能帮助解释：

- 为什么会有异步代码
- 为什么阻塞型代码会伤害服务器性能
- timers、callbacks、promises 和 I/O 是如何互相影响的

## 关键理解

- 在大多数常见 Node.js 代码路径里，JavaScript 执行层面可以近似理解为单线程
- 等待 I/O 时，不应该让程序停在那里什么都不做
- runtime 会协调队列中的工作以及回调执行时机

## 之后要继续展开的问题

- microtask 和 macrotask 的差别
- Node.js event loop 的阶段划分
- Promise 的结算时机会怎样影响真实应用

## 相关

- [[wiki/concepts/nodejs-runtime|Node.js 运行时]]
- [[wiki/concepts/http-api-basics|HTTP API 基础]]
