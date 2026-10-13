# mugsun

企业级中后台产品栈：Spring Boot 后端 + Vue 3 管理端 + uni-app x 移动端 + Web 埋点 SDK。
*An enterprise admin platform stack — backend, admin web, mobile, and analytics SDK.*

📖 文档：[docs.mugsun.com](https://docs.mugsun.com/)

## 仓库地图

| 层 | 仓库 | 说明 |
| --- | --- | --- |
| 后端 | [mugsun-boot](https://github.com/mugsun/mugsun-boot) | 单体后端，JDK 21 + Spring Boot 3.5；RBAC、多租户、工作流、代码生成、埋点分析 |
| 内核 | [mugsun-core](https://github.com/mugsun/mugsun-core) | 公共 BOM 与 starter：统一响应、异常处理、鉴权、国密加解密 |
| PC 端 | [mugsun-pc](https://github.com/mugsun/mugsun-pc) | 管理前端，Vue 3 + TypeScript + Vite + Element Plus |
| 移动端 | [mugsun-app](https://github.com/mugsun/mugsun-app) | uni-app x：Android / iOS / 鸿蒙 / 小程序 |
| 埋点 | [mugsun-track](https://github.com/mugsun/mugsun-track) | Web 行为埋点 SDK，插件化内核 |
| 组件库 | mugsun-uniappx-ui（商业版） | uni-app x 组件库，`ms-` 前缀；源码不公开，[文档开放](https://docs.mugsun.com/uniappx/) |
| 移动 SDK | mugsun-uniappx-sdk（私有） | uni-app x / UTS 能力仓 |
| 文档 | [mugsun-docs](https://github.com/mugsun/mugsun-docs) | 文档站源码（VitePress） |

贡献指南、安全披露与 Issue / PR 模板见 [mugsun/.github](https://github.com/mugsun/.github)。

© 2026 北京定旭晨 / mugsun
