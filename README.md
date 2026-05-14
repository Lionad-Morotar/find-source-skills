# find-source-skills

为代码改动、配置变更或技术决策查找文档源头和依据的 Claude Code 技能。

## 安装

```bash
npx skills add -g Lionad-Morotar/find-source-skills
```

## 使用

```sh
/find-source {你的要求}
```

如果你的 IDE 不支持 SlashCommand，那么为了获得最可靠的结果，需要提示词前加上前缀，比如：

```plaintext
使用 find-source 技能，{你的要求}
```

这会明确触发技能并确保 AI 遵循文档化的模式。如果不加前缀，技能触发可能不一致，具体取决于你的提示词与技能描述关键词的匹配程度。
