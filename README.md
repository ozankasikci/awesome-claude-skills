# Awesome Claude Skills

A curated collection of Claude Skills, resources, and tools.

---

## Official Resources

### Anthropic Documentation
- [Agent Skills Announcement](https://www.anthropic.com/news/skills) - Official launch blog post
- [Skills Explained](https://www.anthropic.com/research/skills-explained) - Deep dive on progressive disclosure architecture
- [How to Create Custom Skills](https://support.claude.com/en/articles/12512198-how-to-create-custom-skills) - Official guide
- [Official Skills Repository](https://github.com/anthropics/skills) - Anthropic's public skills repo

### Key Points
- Skills require Claude Pro, Max, Team, or Enterprise access with code execution enabled
- Skills use progressive disclosure: ~100 tokens for metadata scanning, <5k tokens when activated
- Skills work across Claude.ai, Claude Code, and the API

---

## Skill Categories

### Document Creation (Official)

| Skill | Description |
|-------|-------------|
| **docx** | Create, edit, analyze Word documents with tracked changes, comments, formatting |
| **pdf** | Extract text/tables, create PDFs, merge/split documents, handle forms |
| **pptx** | Read, generate, adjust slides, layouts, templates, charts |
| **xlsx** | Spreadsheet manipulation: formulas, charts, data transformations |
| **Markdown to EPUB Converter** | Converts markdown and chat summaries into EPUB ebooks (by @smerchek) |

### Creative & Design

| Skill | Description | Author/Link |
|-------|-------------|-------------|
| **algorithmic-art** | Generative art using p5.js with seeded randomness, flow fields, particle systems | Official |
| **canvas-design** | Beautiful visual art in PNG/PDF using design philosophy | Official |
| **slack-gif-creator** | Animated GIFs optimized for Slack size constraints | Official |
| **theme-factory** | 10 pre-set themes for artifacts, slides, docs, reports | Official |
| **image-enhancer** | Improves image/screenshot quality for presentations | Community |
| **video-downloader** | Downloads videos from YouTube and other platforms | Community |

### Development & Coding

| Skill | Description | Author/Link |
|-------|-------------|-------------|
| **artifacts-builder** | Complex HTML artifacts with React, Tailwind, shadcn/ui | Official |
| **mcp-server** / **mcp-builder** | Guide for creating high-quality MCP servers | Official |
| **webapp-testing** | Test local web apps using Playwright for UI verification | Official |
| **test-driven-development** | Use before writing implementation code | [obra/superpowers](https://github.com/obra/superpowers) |
| **systematic-debugging** | Use when encountering bugs/test failures before proposing fixes | Community |
| **subagent-driven-development** | Dispatches independent subagents with code review checkpoints | Community |
| **software-architecture** | Clean Architecture, SOLID principles, design patterns | Community |
| **git-pushing** | Automate git operations and repository interactions | Community |
| **review-implementing** | Evaluate code implementation plans and align with specs | Community |
| **test-fixing** | Detect failing tests and propose patches or fixes | Community |
| **defense-in-depth** | Multi-layered testing and security best practices | Community |
| **using-git-worktrees** | Isolated git worktrees with smart directory selection | Community |
| **finishing-a-development-branch** | Guides completion of development work | Community |
| **root-cause-tracing** | Trace errors deep in execution to find original trigger | Community |

### Scientific & Research

| Skill | Description | Author/Link |
|-------|-------------|-------------|
| **scientific-databases** | Access to 26+ databases: PubMed, PubChem, UniProt, ChEMBL, AlphaFold DB | [K-Dense-AI/claude-scientific-skills](https://github.com/K-Dense-AI/claude-scientific-skills) |
| **scientific-packages** | 58 specialized Python packages for bioinformatics, cheminformatics, ML | K-Dense-AI |
| **scientific-integrations** | Benchling, DNAnexus, Opentrons, lab automation | K-Dense-AI |
| **scientific-thinking** | Scientific writing, visualization, methodology tools | K-Dense-AI |
| **single-cell-rna-qc** | Quality control on single-cell RNA-seq data using scverse | Official |
| **content-research-writer** | Research, citations, improving hooks, outline iteration | Community |
| **article-extractor** | Extract full article text and metadata from web pages | Community |

### Financial Services (Official)

| Skill | Description |
|-------|-------------|
| **Comparable Company Analysis** | Valuation multiples and operating metrics |
| **Discounted Cash Flow Models** | FCF projections, WACC calculations, scenario toggles |
| **Due Diligence Data Packs** | Process data room documents into Excel spreadsheets |
| **Company Teasers & Profiles** | Condensed overviews for pitch books |
| **Earnings Analyses** | Extract metrics, guidance changes, management commentary |
| **Initiating Coverage Reports** | Industry analysis, company deep-dives, valuation frameworks |

### Security & DevOps

| Skill | Description | Author/Link |
|-------|-------------|-------------|
| **ffuf_claude_skill** | Web fuzzing for penetration testing with FFUF | Community |
| **computer-forensics** | Digital forensics analysis and investigation | Community |
| **file-deletion** | Secure file deletion and data sanitization | Community |
| **metadata-extraction** | Extract/analyze file metadata for forensic purposes | Community |
| **threat-hunting-with-sigma-rules** | Use Sigma detection rules to hunt threats | Community |
| **iac-terraform** | Infrastructure as Code with Terraform/Terragrunt | [devops-claude-skills](https://github.com/ahmedasmar/devops-claude-skills) |
| **k8s-troubleshooter** | Kubernetes troubleshooting and incident response | devops-claude-skills |
| **aws-cost-optimization** | Find unused resources, analyze RIs, detect anomalies | devops-claude-skills |
| **ci-cd** | CI/CD pipeline automation | devops-claude-skills |
| **gitops-workflows** | GitOps workflow patterns | devops-claude-skills |
| **monitoring-observability** | Prometheus, Datadog, OpenTelemetry integration | devops-claude-skills |

### Data Analysis

| Skill | Description | Author/Link |
|-------|-------------|-------------|
| **csv-data-summarizer-claude-skill** | Analyze CSVs: columns, distributions, missing data, correlations | Community |
| **jupyter-notebooks** | Token-efficient notebook workflows with UV | [claude-plugins.dev](https://claude-plugins.dev/skills/@mbailey/claude/jupyter-notebooks) |
| **invoice-organizer** | Organize invoices and receipts for tax preparation | Community |

### Mobile & Platform-Specific

| Skill | Description | Author/Link |
|-------|-------------|-------------|
| **ios-simulator-skill** | Let Claude drive iOS Simulator via accessibility/screenshots | Community |
| **aws-skills** | AWS CDK best practices, serverless patterns | Community |

### Writing & Content

| Skill | Description | Author/Link |
|-------|-------------|-------------|
| **copywriter** | UX writing, marketing copy, product content | [claude-plugins.dev](https://claude-plugins.dev/skills/@daffy0208/ai-dev-standards/copywriter) |
| **internal-comms** | Status reports, newsletters, FAQs | Official |
| **brand-guidelines** | Apply brand colors and typography to artifacts | Official |
| **skill-creator** | Interactive guidance for creating new skills | Official |
| **template-skill** | Basic template for new skills | Official |

### Productivity & Utilities

| Skill | Description | Author/Link |
|-------|-------------|-------------|
| **meeting-insights-analyzer** | Transform meeting transcripts into actionable insights | Community |
| **linear-cli-skill** | Use linear-CLI to replace Linear MCP | Community |
| **claude-epub-skill** | Parse and analyze EPUB ebooks | Community |
| **youtube-transcript** | Fetch transcripts from YouTube videos | Community |
| **NotebookLM Integration** | Chat with NotebookLM for source-grounded answers | @PleasePrompto |
| **brainstorming** | Transform rough ideas into designs through structured questioning | Community |
| **ship-learn-next** | Iterate on what to build/learn based on feedback loops | Community |

### Game Development

| Skill | Description | Author/Link |
|-------|-------------|-------------|
| **Unity MCP** | AI-powered Unity Editor control with Claude | [CoplayDev/unity-mcp](https://github.com/CoplayDev/unity-mcp) |
| **Blender MCP** | Natural language 3D modeling and scene creation | Community |
| **Unreal MCP** | Unreal Engine integration | Community |

### Testing & QA

| Skill | Description | Author/Link |
|-------|-------------|-------------|
| **pypict-claude-skill** | PICT (Pairwise Independent Combinatorial Testing) test cases | Community |
| **Webapp Testing** | Playwright-based local web app testing | Official |

---

## Major Skill Collections

### [obra/superpowers](https://github.com/obra/superpowers)
Core skills library with 20+ battle-tested skills including TDD, debugging, and collaboration patterns. Features `/brainstorm`, `/write-plan`, `/execute-plan` commands.

**Installation**: `/plugin marketplace add obra/superpowers-marketplace`

### [K-Dense-AI/claude-scientific-skills](https://github.com/K-Dense-AI/claude-scientific-skills)
123+ scientific skills organized into:
- 26+ Scientific Databases
- 52+ Python Packages
- 15+ Scientific Integrations
- 20+ Analysis & Communication Tools

### [ahmedasmar/devops-claude-skills](https://github.com/ahmedasmar/devops-claude-skills)
DevOps-focused skills marketplace covering:
- Terraform/Terragrunt IaC
- Kubernetes troubleshooting
- AWS cost optimization
- CI/CD pipelines
- GitOps workflows
- Monitoring/observability

### [claude-starter](https://github.com/search?q=claude-starter+skills)
Production-ready Claude Code configuration with 40 auto-activating skills across 8 domains, TOON format support for 30-60% token savings.

---

## Related Lists

| Repository | Description |
|------------|-------------|
| [travisvn/awesome-claude-skills](https://github.com/travisvn/awesome-claude-skills) | Comprehensive list focused on Claude Code |
| [ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills) | Curated list with API usage examples |
| [BehiSecc/awesome-claude-skills](https://github.com/BehiSecc/awesome-claude-skills) | Well-organized by category |
| [VoltAgent/awesome-claude-skills](https://github.com/VoltAgent/awesome-claude-skills) | Maintained by VoltAgent community |
| [abubakarsiddik31/claude-skills-collection](https://github.com/abubakarsiddik31/claude-skills-collection) | Official + community skills |

---

## Learning Resources

### Tutorials & Guides
- [Simon Willison: Claude Skills are awesome](https://simonwillison.net/) - Technical deep dive
- [DEV.to Claude Skills tutorials](https://dev.to/t/claude) - Practical tutorials
- [Skills Explained (Anthropic)](https://www.anthropic.com/research/skills-explained) - Decision matrix for Skills vs Prompts/Subagents/Projects

### Video Tutorials
- "Stop Using MCP... Use NEW Claude Skills Instead" - Popular community video
- "Claude Skills explained: How to create reusable AI workflows"

### Courses
- [Claude Code: A Highly Agentic Coding Assistant](https://www.deeplearning.ai/short-courses/claude-code-a-highly-agentic-coding-assistant/) - DeepLearning.AI course

---

## Marketplaces & Discovery

| Platform | Description |
|----------|-------------|
| [SkillsMP.com](https://skillsmp.com/) | 16,000+ free skills marketplace with search and filtering |
| [claude-plugins.dev](https://claude-plugins.dev/) | Skills browser with metadata |
| [GitHub Topics: claude-skills](https://github.com/topics/claude-skills) | GitHub topic for discovery |
| [GitHub Topics: claude-code-skills](https://github.com/topics/claude-code-skills) | Claude Code specific |

---

## Skill Template

```yaml
---
name: my-skill-name
description: A clear description of what this skill does and when to use it (200 chars max)
version: 1.0.0
---

# My Skill Name

Detailed description of the skill's purpose and capabilities.

## When to Use This Skill
- Use case 1
- Use case 2
- Use case 3

## Instructions
[Detailed instructions for Claude on how to execute this skill]

## Examples
[Real-world examples showing the skill in action]

## Guidelines
- Guideline 1
- Guideline 2
```

---

## When to Use Skills vs Other Tools

| Use Case | Best Tool |
|----------|-----------|
| Capabilities for any Claude instance | Skills |
| One-time specific task | Custom Prompt |
| Complex multi-step workflows | Subagents |
| Project-specific context | Projects |
| External API integrations | MCP Servers |

### Best Practices
1. **Keep descriptions concise** - Claude uses them to decide when to invoke
2. **Start simple** - Begin with markdown instructions before adding scripts
3. **Include examples** - Show inputs and expected outputs
4. **Test incrementally** - Verify each batch of changes
5. **Use progressive disclosure** - Don't load everything upfront

---

## Security Notes

- Skills can execute arbitrary code in Claude's environment
- Only install skills from trusted sources
- Review skill code before enabling
- Skills from marketplaces should be treated like open-source code

---

## Timeline

- **Oct 16, 2025**: Claude Skills officially announced
- **Oct 17, 2025**: Community tutorials emerge on DEV.to and Medium
- **Oct 18, 2025**: Major community repositories emerge (obra/superpowers)
- **Oct 27, 2025**: Financial Services skills released
- **Nov 13, 2025**: Anthropic publishes comprehensive Skills Explained guide

---

## Contributing

To contribute to this list:
1. Fork the repository
2. Add your skill/resource with description
3. Follow the existing format
4. Submit a pull request

---

*Curated from official Anthropic resources, GitHub repositories, and community contributions.*
