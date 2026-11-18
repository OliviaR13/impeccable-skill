# impeccable-skill

Claude Skill 打包版 [Impeccable](https://github.com/pbakaus/impeccable)（作者 Paul Bakaus），用于设计、评审、审计、打磨前端 UI。

## 说明
- 本仓库**不是原创作品**，内容来自上游 Impeccable，沿用其 **Apache License 2.0**，上游版权与第三方声明见 `LICENSE`、`NOTICE.md`。
- 相对上游的改动仅有一处：为通过 Claude Skill 校验，移除了 `SKILL.md` frontmatter 中的 `argument-hint`、`user-invocable`，并把 `version` 移入 `metadata`。
- 未包含上游的 hooks、子代理、live 模式及其他平台适配。

## 使用
- 在 Claude 网页端 / App：下载 `impeccable.skill`，点「Save skill」安装。
- 或直接使用 `impeccable/` 目录作为 skill 文件夹。
