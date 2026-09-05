# AI PM Prompt Suite

> © 2026 王天娇（anlan-dev）· GPL-3.0 开源 · 使用时保留作者署名与版权声明 / keep attribution


A curated collection of 12 AI prompts covering the complete product manager workflow — from raw requirement discovery to PRD delivery.

Designed for Chinese-speaking AI/tech PMs who use LLMs (ChatGPT, Claude, DeepSeek, etc.) in their daily workflow.

## The Workflow

```
Raw meeting notes / chat logs / user feedback
    ↓
⓪ Requirement Refinement    →  Extract structured requirements
    ↓
Competitor screenshots
    ↓
① Extract PRD              →  Features & interactions from screenshots
② Extract Design Spec      →  Colors / typography / components
③ Restructure PRD          →  Merge old PRD + new design spec
④ Rewrite Copy             →  Differentiated copywriting
⑤ Merge & Output GM        →  Final Golden Master document
⑥ Pre-review Checklist     →  AI-powered quality scan
    ↓
Final PRD → Formal Review
```

## What's Inside

| File | Scenario | Type |
|------|----------|------|
| `AI产品PRD写作指南.md` | PRD methodology & 19-item checklist | Guide |
| `AI生成PRD prompt模板.md` | Generate a full PRD in one shot | Template |
| `PRD全流程工作流-AI prompt套件.md` | End-to-end workflow overview | Workflow |
| `Prompt调优指南.md` | Prompt optimization best practices | Guide |
| `workflow/步骤0-需求梳理.md` | From meeting recordings to structured reqs | Workflow |
| `workflow/步骤1-截图转PRD.md` | Competitor screenshots → PRD items | Workflow |
| `workflow/步骤2-提取设计规范.md` | Screenshots → design system extraction | Workflow |
| `workflow/步骤3-重构PRD.md` | Merge design spec into existing PRD | Workflow |
| `workflow/步骤4-重构文案.md` | Differentiate competitor copy | Workflow |
| `workflow/步骤5-融合输出GM.md` | Final Golden Master delivery document | Workflow |
| `workflow/步骤6-评审自查.md` | AI quality check before formal review | Workflow |

## Usage

```bash
git clone https://github.com/anlan-dev/ai-pm-prompts.git
cd ai-pm-prompts/prompts
```

Open any `.md` file and feed its content to your preferred LLM (ChatGPT, Claude, DeepSeek, etc.).

## Design Decisions

- **Workflow-ordered, not capability-ordered**: Prompts are arranged by how PMs actually work (start with requirement refinement, not PRD writing)
- **Prompt content is in Chinese**: Because the target users are Chinese-speaking product managers
- **No code, no dependencies**: Each prompt is a standalone markdown file — just copy and paste

## License

GPL-3.0 — 保留作者署名权，遵循 GNU GPL v3.0 条款。
