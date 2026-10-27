软件工程在读，方向是后端。

Java / Spring Cloud / Vue 3 / TypeScript，也写一些给 AI 助手用的工具。

## 在线判题系统 · HaxOJ

从判题服务到前端一整套写完，三个仓库可独立部署。

**[微服务后端](https://github.com/heix0x/haxoj-backend-microservice)**
Spring Cloud Alibaba + Nacos + OpenFeign，用户、题目、判题拆成三个服务。网关路由、Redis 共享 Session、RabbitMQ 异步判题带幂等。

**[代码沙箱](https://github.com/heix0x/haxoj-code-sandbox)**
独立服务，安全执行用户提交的 Java 代码。黑名单 + SecurityManager + Docker 容器三层隔离，另有本地轻量模式。

**[前端](https://github.com/heix0x/haxoj-frontend)**
Vue 3 + Vite + TypeScript。Monaco 在线编辑器写题，题库、比赛、排名、管理后台齐备。

## AI 助手工具

装一次，之后跟助手说一句话就能用。

**[对话录](https://github.com/heix0x/dsh-share-transcript)**
DSH 插件。把一段对话导成可编辑的 Markdown 或 PNG 卡片，勾轮次、改草稿、复制走人。默认脱敏，路由只读。

**[超星作业抓取](https://github.com/heix0x/chaoxing-work-extractor)**
把学习通作业页的题目抓下来整理成笔记，答案也能批量填回答题页。Python 写，交给 AI 助手跑，不用开终端。

**[算法讲解](https://github.com/heix0x/algorithm-explainer)**
给 AI 助手用的算法讲解 skill。最小例子 + 可执行比喻 + 逐步配表，目标是把一道题讲到你自己拿笔能算完。

[关于](/about/) · [GitHub](https://github.com/heix0x)
