软件工程在读，方向是后端。

做完的东西都在这儿：一套在线判题系统，几个给 AI 助手用的小工具。

## 在线判题系统 · HaxOJ

一套能真跑起来的 OJ。三个仓库独立部署，接口对得上。

**[微服务后端](https://github.com/heix0x/haxoj-backend-microservice)**
用户 / 题目 / 判题拆成三个服务，网关统一入口，Redis 共享 Session，异步判题带幂等。<br>
<sub>Spring Cloud Alibaba · Nacos · OpenFeign · RabbitMQ</sub>

**[代码沙箱](https://github.com/heix0x/haxoj-code-sandbox)**
独立服务，负责跑别人的代码。黑名单 + 安全管理器 + 容器三层隔离，另有本地轻量模式。<br>
<sub>Java · Docker · SecurityManager</sub>

**[前端](https://github.com/heix0x/haxoj-frontend)**
题库、比赛、排名、管理后台。在线写题，判题结果回显。<br>
<sub>Vue 3 · TypeScript · Vite · Monaco</sub>

## AI 助手工具

装一次，之后跟助手说一句话就能用。

**[对话录](https://github.com/heix0x/dsh-share-transcript)**
把一段对话导成可编辑的 Markdown 或 PNG 卡片。默认脱敏，路由只读。<br>
<sub>DSH 插件 · JavaScript</sub>

**[超星作业抓取](https://github.com/heix0x/chaoxing-work-extractor)**
把学习通作业页的题目抓下来整理成笔记，答案也能批量填回去。<br>
<sub>Python · Playwright</sub>

**[算法讲解](https://github.com/heix0x/algorithm-explainer)**
给 AI 助手的算法讲解 skill。最小例子、可执行比喻、逐步配表 —— 讲到你自己拿笔能算完。<br>
<sub>Skill · 纯文档</sub>

**[GitHub 发布](https://github.com/heix0x/github-release)**
把本地项目一路推到发版上线：建仓库、打 tag、传附件、设 About。git 连不上时改走 API 通道。<br>
<sub>Skill · Python</sub>

[关于](/about/) · [GitHub](https://github.com/heix0x)
