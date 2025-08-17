# template-ai-coding-config
AI Coding をする際に利用するドキュメントのテンプレートを管理するリポジトリ

このリポジトリでは、 Claude Code か Cursor で作業することを前提にしているので、 CLAUDE.md はテンプレートファイルを別に用意しています。
- [CLAUDE.md.template](./CLAUDE.md.template)

## ディレクトリ構成

```
.
├── .claude/
│   ├── agents/
│   │   ├── phpstan-level9-engineer.md
│   │   └── tdd-test-creator.md
│   └── settings.json
├── .cursor/
│   └── rules/
│       ├── textlint.mdc
│       └── writing_style.mdc
├── .gemini/
│   ├── config.yaml
│   └── styleguide.md
├── mcp/                        # MCP (Model Context Protocol) 設定
│   ├── mcp.json
│   └── README.md
├── templates/                  # プロジェクトの種別ごとのテンプレート
│   ├── studying/
│   │   ├── .gemini/
│   │   │   └── commands/
│   │   │       └── explain-dev.toml
│   │   └── AGENTS.md
│   └── README.md
├── .coderabbit.yaml
├── AGENTS.md
├── CLAUDE.md
├── CLAUDE.md.template
├── GEMINI.md
└── README.md
```
