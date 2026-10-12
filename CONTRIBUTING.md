# 贡献指南

感谢参与 mugsun。本文说明如何报告问题、提交改动与提 Pull Request。英文短版见 [CONTRIBUTING_EN.md](./CONTRIBUTING_EN.md)。

## 开始之前

1. 阅读目标仓库的 `README.md` 与文档站对应章节：[docs.mugsun.com](https://docs.mugsun.com/)
2. 搜索已有 [Issues](https://github.com/mugsun) 与 Pull Request，避免重复
3. 大改动（新模块、破坏性 API、许可证相关）请先开 Issue 说明动机与方案，再动手

## 开发约定

- **提交信息**：采用 [Conventional Commits](https://www.conventionalcommits.org/zh-hans/)。`type` / `scope` 用英文小写，**主题用中文**，不使用 emoji。各仓 `.github/COMMIT_CONVENTION.md`（若有）为准。
- **代码风格**：遵循该仓既有格式与 CI；勿顺手大范围无关重排。
- **测试**：能跑的测试请本地跑通再推；新增行为尽量补测。
- **文档**：用户可见行为变更时，同步更新 README 或 docs（视影响范围）。

## 提 Issue

请使用仓库提供的 Issue 模板：

- **缺陷报告**：可复现步骤、期望与实际、环境（版本 / OS / 浏览器或 JDK）
- **功能建议**：场景、收益、是否可接受替代方案

安全漏洞**不要**公开开 Issue，见 [SECURITY.md](./SECURITY.md)。

## 提 Pull Request

1. Fork 或从最新 `main` 拉分支
2. 单 PR 聚焦一件事；破坏性变更在说明中写清迁移方式
3. 填写 PR 模板中的勾选项
4. 保持与 `main` 可合并；CI 通过后再请求评审
5. 维护者合并前可能要求小改；请保持讨论在 PR 内可追溯

## 行为准则

友善、具体、对事不对人。人身攻击、垃圾信息、未授权扫描或利用他人部署，将被关闭并视情况限制互动。

## 许可证

除非另有说明，对本账号下开源仓库的贡献按该仓库 `LICENSE` 授权。
